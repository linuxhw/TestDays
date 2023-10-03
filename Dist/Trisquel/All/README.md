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

Total: 51

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [855f5edce0](https://linux-hardware.org/?probe=855f5edce0) | Sep 08, 2023 |
| Dell          | Latitude E6400              | Notebook    | [65c390fe0e](https://linux-hardware.org/?probe=65c390fe0e) | Aug 12, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [8375e909e7](https://linux-hardware.org/?probe=8375e909e7) | Jul 30, 2023 |
| Acer          | Aspire XC-885 V:1.1         | Desktop     | [eebd657892](https://linux-hardware.org/?probe=eebd657892) | Jul 27, 2023 |
| Lenovo        | ThinkPad X200 7458C23       | Notebook    | [3f09abaa12](https://linux-hardware.org/?probe=3f09abaa12) | Jul 24, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [154b34b737](https://linux-hardware.org/?probe=154b34b737) | Jul 18, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [4ec56be6a5](https://linux-hardware.org/?probe=4ec56be6a5) | Jul 03, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [2940c0be7d](https://linux-hardware.org/?probe=2940c0be7d) | Jul 01, 2023 |
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

![OS](./images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Trisquel 10.0.1 | 18        | 46.15%  |
| Trisquel 11.0   | 10        | 25.64%  |
| Trisquel 9.0    | 5         | 12.82%  |
| Trisquel 8.0    | 3         | 7.69%   |
| Trisquel 10.0   | 3         | 7.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Trisquel | 39        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 5.4.0-96-generic     | 4         | 9.52%   |
| 5.4.0-122-generic    | 4         | 9.52%   |
| 5.4.0-125-generic    | 3         | 7.14%   |
| 5.4.0-113-generic    | 3         | 7.14%   |
| 5.15.0-78-generic    | 3         | 7.14%   |
| 5.4.0-126-generic    | 2         | 4.76%   |
| 5.4.0-109-generic    | 2         | 4.76%   |
| 5.15.0-76-generic    | 2         | 4.76%   |
| 5.15.0-69-generic    | 2         | 4.76%   |
| 6.0.12-x64v1-xanmod1 | 1         | 2.38%   |
| 5.4.0-159-generic    | 1         | 2.38%   |
| 5.4.0-135-generic    | 1         | 2.38%   |
| 5.4.0-132-generic    | 1         | 2.38%   |
| 5.4.0-131-generic    | 1         | 2.38%   |
| 5.4.0-110-generic    | 1         | 2.38%   |
| 5.3.13-gnu           | 1         | 2.38%   |
| 5.3.1-gnu            | 1         | 2.38%   |
| 5.15.0-73-generic    | 1         | 2.38%   |
| 5.15.0-67-generic    | 1         | 2.38%   |
| 5.10.177-gnu1        | 1         | 2.38%   |
| 4.4.0-119-generic    | 1         | 2.38%   |
| 4.15.0-161-generic   | 1         | 2.38%   |
| 4.15.0-156-generic   | 1         | 2.38%   |
| 4.15.0-136-generic   | 1         | 2.38%   |
| 4.15.0-121-generic   | 1         | 2.38%   |
| 4.15.0-108-generic   | 1         | 2.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.4.0    | 20        | 51.28%  |
| 5.15.0   | 9         | 23.08%  |
| 4.15.0   | 5         | 12.82%  |
| 6.0.12   | 1         | 2.56%   |
| 5.3.13   | 1         | 2.56%   |
| 5.3.1    | 1         | 2.56%   |
| 5.10.177 | 1         | 2.56%   |
| 4.4.0    | 1         | 2.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 20        | 51.28%  |
| 5.15    | 9         | 23.08%  |
| 4.15    | 5         | 12.82%  |
| 5.3     | 2         | 5.13%   |
| 6.0     | 1         | 2.56%   |
| 5.10    | 1         | 2.56%   |
| 4.4     | 1         | 2.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 37        | 94.87%  |
| i686   | 1         | 2.56%   |
| armv7l | 1         | 2.56%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| MATE    | 29        | 74.36%  |
| LXDE    | 3         | 7.69%   |
| Unknown | 2         | 5.13%   |
| KDE5    | 1         | 2.56%   |
| KDE     | 1         | 2.56%   |
| GNOME   | 1         | 2.56%   |
| dwm     | 1         | 2.56%   |
| default | 1         | 2.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 37        | 94.87%  |
| Wayland | 1         | 2.56%   |
| Unknown | 1         | 2.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 26        | 66.67%  |
| Unknown | 7         | 17.95%  |
| TDM     | 4         | 10.26%  |
| SDDM    | 1         | 2.56%   |
| GDM     | 1         | 2.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 17        | 43.59%  |
| ru_RU   | 5         | 12.82%  |
| fr_FR   | 4         | 10.26%  |
| C       | 3         | 7.69%   |
| Unknown | 3         | 7.69%   |
| ru_UA   | 1         | 2.56%   |
| pt_BR   | 1         | 2.56%   |
| es_MX   | 1         | 2.56%   |
| es_ES   | 1         | 2.56%   |
| en_GB   | 1         | 2.56%   |
| en_CA   | 1         | 2.56%   |
| de_DE   | 1         | 2.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 20        | 51.28%  |
| BIOS | 19        | 48.72%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 35        | 89.74%  |
| Overlay | 2         | 5.13%   |
| Xfs     | 1         | 2.56%   |
| Unknown | 1         | 2.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 29        | 74.36%  |
| Unknown | 7         | 17.95%  |
| MBR     | 3         | 7.69%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 33        | 80.49%  |
| Yes       | 8         | 19.51%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 33        | 84.62%  |
| Yes       | 6         | 15.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 7         | 17.95%  |
| Lenovo              | 6         | 15.38%  |
| ASUSTek Computer    | 4         | 10.26%  |
| Hewlett-Packard     | 3         | 7.69%   |
| Acer                | 3         | 7.69%   |
| Toshiba             | 2         | 5.13%   |
| Samsung Electronics | 2         | 5.13%   |
| Timi                | 1         | 2.56%   |
| Packard Bell        | 1         | 2.56%   |
| MSI                 | 1         | 2.56%   |
| Libiquity           | 1         | 2.56%   |
| Itautec             | 1         | 2.56%   |
| Huanan              | 1         | 2.56%   |
| GPD                 | 1         | 2.56%   |
| Gigabyte Technology | 1         | 2.56%   |
| Fujitsu Siemens     | 1         | 2.56%   |
| ECS                 | 1         | 2.56%   |
| Apple               | 1         | 2.56%   |
| Unknown             | 1         | 2.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                                  | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Lenovo ThinkPad T420 4177QKU                                          | 2         | 5.13%   |
| Dell XPS 15 9510                                                      | 2         | 5.13%   |
| Toshiba Satellite C800D                                               | 1         | 2.56%   |
| Toshiba NB510                                                         | 1         | 2.56%   |
| Timi TM1709                                                           | 1         | 2.56%   |
| Samsung N130                                                          | 1         | 2.56%   |
| Samsung Galaxy TabPro S                                               | 1         | 2.56%   |
| Packard Bell IMEDIA S1300                                             | 1         | 2.56%   |
| MSI MS-7917                                                           | 1         | 2.56%   |
| Libiquity Taurinus X200                                               | 1         | 2.56%   |
| Lenovo ThinkPad X200 7458C23                                          | 1         | 2.56%   |
| Lenovo ThinkPad X200 7455FNG                                          | 1         | 2.56%   |
| Lenovo ThinkPad T430 2347G2U                                          | 1         | 2.56%   |
| Lenovo G505s 20255                                                    | 1         | 2.56%   |
| Itautec Infoway                                                       | 1         | 2.56%   |
| Huanan X79 INTEL (INTEL Xeon E5/Corei7 DMI2 - C600/C200 Cipset V2.49P | 1         | 2.56%   |
| HP Victus by Laptop 16-e0xxx                                          | 1         | 2.56%   |
| HP Stream Laptop 11-y0XX                                              | 1         | 2.56%   |
| HP EliteDesk 800 G3 SFF                                               | 1         | 2.56%   |
| GPD MicroPC                                                           | 1         | 2.56%   |
| Gigabyte M68MT-D3P                                                    | 1         | 2.56%   |
| Fujitsu Siemens ESPRIMO EDITION P2540                                 | 1         | 2.56%   |
| ECS H61H2-M2                                                          | 1         | 2.56%   |
| Dell XPS 13 9360                                                      | 1         | 2.56%   |
| Dell OptiPlex 3020                                                    | 1         | 2.56%   |
| Dell Latitude E6400                                                   | 1         | 2.56%   |
| Dell Inspiron 1545                                                    | 1         | 2.56%   |
| Dell Inspiron 15-3567                                                 | 1         | 2.56%   |
| ASUS U56E                                                             | 1         | 2.56%   |
| ASUS P8H61                                                            | 1         | 2.56%   |
| ASUS K55A                                                             | 1         | 2.56%   |
| ASUS A55BM-PLUS                                                       | 1         | 2.56%   |
| Apple MacPro5,1                                                       | 1         | 2.56%   |
| Acer TravelMate B115-M                                                | 1         | 2.56%   |
| Acer Nitro AN517-54                                                   | 1         | 2.56%   |
| Acer Aspire XC-885                                                    | 1         | 2.56%   |
| Unknown                                                               | 1         | 2.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 5         | 12.82%  |
| Dell XPS                | 3         | 7.69%   |
| Dell Inspiron           | 2         | 5.13%   |
| Toshiba Satellite       | 1         | 2.56%   |
| Toshiba NB510           | 1         | 2.56%   |
| Timi TM1709             | 1         | 2.56%   |
| Samsung N130            | 1         | 2.56%   |
| Samsung Galaxy          | 1         | 2.56%   |
| Packard Bell IMEDIA     | 1         | 2.56%   |
| MSI MS-7917             | 1         | 2.56%   |
| Libiquity Taurinus      | 1         | 2.56%   |
| Lenovo G505s            | 1         | 2.56%   |
| Itautec Infoway         | 1         | 2.56%   |
| Huanan X79              | 1         | 2.56%   |
| HP Victus               | 1         | 2.56%   |
| HP Stream               | 1         | 2.56%   |
| HP EliteDesk            | 1         | 2.56%   |
| GPD MicroPC             | 1         | 2.56%   |
| Gigabyte M68MT-D3P      | 1         | 2.56%   |
| Fujitsu Siemens ESPRIMO | 1         | 2.56%   |
| ECS H61H2-M2            | 1         | 2.56%   |
| Dell OptiPlex           | 1         | 2.56%   |
| Dell Latitude           | 1         | 2.56%   |
| ASUS U56E               | 1         | 2.56%   |
| ASUS P8H61              | 1         | 2.56%   |
| ASUS K55A               | 1         | 2.56%   |
| ASUS A55BM-PLUS         | 1         | 2.56%   |
| Apple MacPro5           | 1         | 2.56%   |
| Acer TravelMate         | 1         | 2.56%   |
| Acer Nitro              | 1         | 2.56%   |
| Acer Aspire             | 1         | 2.56%   |
| Unknown                 | 1         | 2.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2008    | 6         | 15.38%  |
| 2011    | 5         | 12.82%  |
| 2021    | 4         | 10.26%  |
| 2016    | 4         | 10.26%  |
| 2012    | 4         | 10.26%  |
| 2018    | 3         | 7.69%   |
| 2014    | 3         | 7.69%   |
| 2010    | 3         | 7.69%   |
| 2013    | 2         | 5.13%   |
| 2019    | 1         | 2.56%   |
| 2017    | 1         | 2.56%   |
| 2015    | 1         | 2.56%   |
| 2009    | 1         | 2.56%   |
| Unknown | 1         | 2.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 25        | 64.1%   |
| Desktop  | 13        | 33.33%  |
| Tablet   | 1         | 2.56%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 39        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 35        | 89.74%  |
| Yes  | 4         | 10.26%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 13        | 33.33%  |
| 8.01-16.0  | 8         | 20.51%  |
| 16.01-24.0 | 6         | 15.38%  |
| 3.01-4.0   | 5         | 12.82%  |
| 1.01-2.0   | 4         | 10.26%  |
| 32.01-64.0 | 2         | 5.13%   |
| 0.51-1.0   | 1         | 2.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 24        | 58.54%  |
| 2.01-3.0  | 4         | 9.76%   |
| 0.51-1.0  | 4         | 9.76%   |
| 3.01-4.0  | 3         | 7.32%   |
| 0.01-0.5  | 3         | 7.32%   |
| 4.01-8.0  | 2         | 4.88%   |
| 8.01-16.0 | 1         | 2.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 28        | 70%     |
| 2      | 9         | 22.5%   |
| 4      | 1         | 2.5%    |
| 3      | 1         | 2.5%    |
| 0      | 1         | 2.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 51.28%  |
| No        | 19        | 48.72%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 37        | 94.87%  |
| No        | 2         | 5.13%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 80%     |
| No        | 8         | 20%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 22        | 56.41%  |
| Yes       | 17        | 43.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 13        | 33.33%  |
| France      | 6         | 15.38%  |
| Russia      | 4         | 10.26%  |
| China       | 3         | 7.69%   |
| Spain       | 2         | 5.13%   |
| Germany     | 2         | 5.13%   |
| Brazil      | 2         | 5.13%   |
| Ukraine     | 1         | 2.56%   |
| Netherlands | 1         | 2.56%   |
| Mexico      | 1         | 2.56%   |
| Ireland     | 1         | 2.56%   |
| Indonesia   | 1         | 2.56%   |
| Canada      | 1         | 2.56%   |
| Belarus     | 1         | 2.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lincoln                  | 5         | 12.82%  |
| Corbeil-Essonnes         | 3         | 7.69%   |
| Omaha                    | 2         | 5.13%   |
| Moscow                   | 2         | 5.13%   |
| Malvern                  | 2         | 5.13%   |
| Wylie                    | 1         | 2.56%   |
| Wiesbaden                | 1         | 2.56%   |
| Vitebsk                  | 1         | 2.56%   |
| Vienne-le-Chateau        | 1         | 2.56%   |
| St Petersburg            | 1         | 2.56%   |
| Shenzhen                 | 1         | 2.56%   |
| Sabadell                 | 1         | 2.56%   |
| Rivne                    | 1         | 2.56%   |
| Pinangsia                | 1         | 2.56%   |
| Petropavlovsk-Kamchatsky | 1         | 2.56%   |
| Paris                    | 1         | 2.56%   |
| Oviedo                   | 1         | 2.56%   |
| Ottawa                   | 1         | 2.56%   |
| Missoula                 | 1         | 2.56%   |
| Lüdenscheid             | 1         | 2.56%   |
| Guangzhou                | 1         | 2.56%   |
| Fayetteville             | 1         | 2.56%   |
| Cork                     | 1         | 2.56%   |
| Ciudad del Carmen        | 1         | 2.56%   |
| Chengdu                  | 1         | 2.56%   |
| Cerons                   | 1         | 2.56%   |
| Blumenau                 | 1         | 2.56%   |
| Amsterdam                | 1         | 2.56%   |
| Americana                | 1         | 2.56%   |
| Acworth                  | 1         | 2.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 9      | 19.57%  |
| Seagate             | 7         | 14     | 15.22%  |
| WDC                 | 4         | 4      | 8.7%    |
| Toshiba             | 4         | 4      | 8.7%    |
| Sandisk             | 3         | 3      | 6.52%   |
| SK hynix            | 2         | 2      | 4.35%   |
| HGST HTS            | 2         | 4      | 4.35%   |
| Crucial             | 2         | 2      | 4.35%   |
| China               | 2         | 2      | 4.35%   |
| Unknown             | 1         | 1      | 2.17%   |
| Transcend           | 1         | 1      | 2.17%   |
| Silicon Motion      | 1         | 2      | 2.17%   |
| Qumo                | 1         | 1      | 2.17%   |
| Plextor             | 1         | 1      | 2.17%   |
| NFHK                | 1         | 1      | 2.17%   |
| LITEON              | 1         | 1      | 2.17%   |
| Kingston            | 1         | 1      | 2.17%   |
| Hitachi             | 1         | 1      | 2.17%   |
| Apacer              | 1         | 1      | 2.17%   |
| A-DATA Technology   | 1         | 1      | 2.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| SK hynix PC711 NVMe 512GB            | 2         | 4.08%   |
| Seagate ST500DM002-1BD142 500GB      | 2         | 4.08%   |
| Seagate ST4000NM 0033-9ZM170 4TB     | 2         | 4.08%   |
| Seagate ST1000DM010-2EP102 1TB       | 2         | 4.08%   |
| HGST HTS 721010A9E630 1TB            | 2         | 4.08%   |
| WDC WD6400BPVT-80HXZT3 640GB         | 1         | 2.04%   |
| WDC WD3200BEVT-75ZCT2 320GB          | 1         | 2.04%   |
| WDC WD3200AAKX-221CA1 320GB          | 1         | 2.04%   |
| WDC PC SN730 SDBPNTY-512G-1006 512GB | 1         | 2.04%   |
| Unknown SA32G  32GB                  | 1         | 2.04%   |
| Transcend TS256GMTS430S 256GB SSD    | 1         | 2.04%   |
| Toshiba THNSN5256GPUK NVMe 256GB     | 1         | 2.04%   |
| Toshiba MK3275GSX 320GB              | 1         | 2.04%   |
| Toshiba HDWL110 1TB                  | 1         | 2.04%   |
| Toshiba DT01ACA100 1TB               | 1         | 2.04%   |
| Silicon Motion MS10 1TB              | 1         | 2.04%   |
| Seagate ST320LT007-9ZV142 320GB      | 1         | 2.04%   |
| Seagate ST31000524AS 1TB             | 1         | 2.04%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 2.04%   |
| Seagate ST1000DM003-9YN162 1TB       | 1         | 2.04%   |
| Sandisk WD Blue SN570 1TB            | 1         | 2.04%   |
| SanDisk SSD PLUS 240GB               | 1         | 2.04%   |
| SanDisk DF4032  32GB                 | 1         | 2.04%   |
| Samsung SSD 860 EVO 500GB            | 1         | 2.04%   |
| Samsung SSD 860 EVO 250GB            | 1         | 2.04%   |
| Samsung SSD 840 PRO Series 256GB     | 1         | 2.04%   |
| Samsung SSD 840 EVO 120GB            | 1         | 2.04%   |
| Samsung MZVLW256HEHP-000H1 256GB     | 1         | 2.04%   |
| Samsung MZVLQ512HBLU-00BTW 512GB     | 1         | 2.04%   |
| Samsung MZNLN128HAHQ-00000 128GB SSD | 1         | 2.04%   |
| Samsung HM251JI 250GB                | 1         | 2.04%   |
| Samsung HM160HI 160GB                | 1         | 2.04%   |
| Qumo SSD 120GB                       | 1         | 2.04%   |
| Plextor PX-512M5Pro 512GB SSD        | 1         | 2.04%   |
| NFHK USB 3.0 120GB                   | 1         | 2.04%   |
| LITEON CV1-8B128 128GB SSD           | 1         | 2.04%   |
| Kingston SA400S37240G 240GB SSD      | 1         | 2.04%   |
| Hitachi HTS547575A9E384 752GB        | 1         | 2.04%   |
| Crucial CT250BX100SSD1 250GB         | 1         | 2.04%   |
| Crucial CT240BX200SSD1 240GB         | 1         | 2.04%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


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

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 5      | 29.41%  |
| Crucial             | 2         | 2      | 11.76%  |
| China               | 2         | 2      | 11.76%  |
| Transcend           | 1         | 1      | 5.88%   |
| SanDisk             | 1         | 1      | 5.88%   |
| Qumo                | 1         | 1      | 5.88%   |
| Plextor             | 1         | 1      | 5.88%   |
| LITEON              | 1         | 1      | 5.88%   |
| Kingston            | 1         | 1      | 5.88%   |
| Apacer              | 1         | 1      | 5.88%   |
| A-DATA Technology   | 1         | 1      | 5.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 16        | 17     | 39.02%  |
| HDD     | 15        | 27     | 36.59%  |
| NVMe    | 7         | 9      | 17.07%  |
| MMC     | 2         | 2      | 4.88%   |
| Unknown | 1         | 1      | 2.44%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 29        | 36     | 70.73%  |
| NVMe | 7         | 9      | 17.07%  |
| SAS  | 3         | 9      | 7.32%   |
| MMC  | 2         | 2      | 4.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 22        | 25     | 62.86%  |
| 0.51-1.0   | 11        | 15     | 31.43%  |
| 3.01-4.0   | 2         | 4      | 5.71%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 16        | 41.03%  |
| 251-500        | 7         | 17.95%  |
| 501-1000       | 6         | 15.38%  |
| 51-100         | 3         | 7.69%   |
| More than 3000 | 2         | 5.13%   |
| 21-50          | 2         | 5.13%   |
| 1-20           | 2         | 5.13%   |
| 2001-3000      | 1         | 2.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 20        | 48.78%  |
| 21-50          | 9         | 21.95%  |
| 101-250        | 5         | 12.2%   |
| 51-100         | 3         | 7.32%   |
| 2001-3000      | 2         | 4.88%   |
| More than 3000 | 1         | 2.44%   |
| 501-1000       | 1         | 2.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


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

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


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

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 3         | 5      | 42.86%  |
| HGST HTS | 2         | 4      | 28.57%  |
| WDC      | 1         | 1      | 14.29%  |
| Toshiba  | 1         | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 25        | 33     | 60.98%  |
| Detected | 9         | 11     | 21.95%  |
| Malfunc  | 7         | 12     | 17.07%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 28        | 68.29%  |
| AMD                          | 3         | 7.32%   |
| SK hynix                     | 2         | 4.88%   |
| SanDisk                      | 2         | 4.88%   |
| Samsung Electronics          | 2         | 4.88%   |
| Nvidia                       | 2         | 4.88%   |
| Toshiba America Info Systems | 1         | 2.44%   |
| Silicon Motion               | 1         | 2.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 5         | 10.87%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 3         | 6.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 3         | 6.52%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 3         | 6.52%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 2         | 4.35%   |
| Nvidia MCP61 SATA Controller                                                            | 2         | 4.35%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2         | 4.35%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 4.35%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 4.35%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1         | 2.17%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 1         | 2.17%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                                      | 1         | 2.17%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1         | 2.17%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1         | 2.17%   |
| Samsung NVMe SSD Controller 980                                                         | 1         | 2.17%   |
| Nvidia MCP61 IDE                                                                        | 1         | 2.17%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 1         | 2.17%   |
| Intel Tiger Lake SATA AHCI Controller                                                   | 1         | 2.17%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1         | 2.17%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 1         | 2.17%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1         | 2.17%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1         | 2.17%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1         | 2.17%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1         | 2.17%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1         | 2.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 1         | 2.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 1         | 2.17%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 1         | 2.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1         | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1         | 2.17%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1         | 2.17%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 27        | 64.29%  |
| NVMe | 7         | 16.67%  |
| IDE  | 7         | 16.67%  |
| RAID | 1         | 2.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 32        | 82.05%  |
| AMD    | 6         | 15.38%  |
| ARM    | 1         | 2.56%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-4590 CPU @ 3.30GHz            | 2         | 5.13%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 2         | 5.13%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz     | 2         | 5.13%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 1         | 2.56%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1         | 2.56%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1         | 2.56%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz      | 1         | 2.56%   |
| Intel Pentium CPU N3530 @ 2.16GHz           | 1         | 2.56%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz            | 1         | 2.56%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1         | 2.56%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 2.56%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1         | 2.56%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1         | 2.56%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 2.56%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 2.56%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 1         | 2.56%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 1         | 2.56%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 1         | 2.56%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 1         | 2.56%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz        | 1         | 2.56%   |
| Intel Core 2 Duo CPU P8800 @ 2.66GHz        | 1         | 2.56%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 1         | 2.56%   |
| Intel Core 2 CPU P8700 @ 2.53GHz            | 1         | 2.56%   |
| Intel Core 2 CPU P8600 @ 2.40GHz            | 1         | 2.56%   |
| Intel Celeron N4100 CPU @ 1.10GHz           | 1         | 2.56%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 1         | 2.56%   |
| Intel Atom CPU N270 @ 1.60GHz               | 1         | 2.56%   |
| Intel Atom CPU N2600 @ 1.60GHz              | 1         | 2.56%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz     | 1         | 2.56%   |
| ARM Allwinner sun8i Family Processor        | 1         | 2.56%   |
| AMD Ryzen 7 5800H with Radeon Graphics      | 1         | 2.56%   |
| AMD Phenom II X4 955 Processor              | 1         | 2.56%   |
| AMD E1-1200 APU with Radeon HD Graphics     | 1         | 2.56%   |
| AMD Athlon II X2 215 Processor              | 1         | 2.56%   |
| AMD A8-5550M APU with Radeon HD Graphics    | 1         | 2.56%   |
| AMD A4-5300 APU with Radeon HD Graphics     | 1         | 2.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 10        | 25.64%  |
| Other                   | 3         | 7.69%   |
| Intel Core i3           | 3         | 7.69%   |
| Intel Core 2 Duo        | 3         | 7.69%   |
| Intel Xeon              | 2         | 5.13%   |
| Intel Core 2            | 2         | 5.13%   |
| Intel Celeron           | 2         | 5.13%   |
| Intel Atom              | 2         | 5.13%   |
| Intel Pentium Dual-Core | 1         | 2.56%   |
| Intel Pentium Dual      | 1         | 2.56%   |
| Intel Pentium           | 1         | 2.56%   |
| Intel Core m3           | 1         | 2.56%   |
| Intel Core i7           | 1         | 2.56%   |
| ARM Allwinner           | 1         | 2.56%   |
| AMD Ryzen 7             | 1         | 2.56%   |
| AMD Phenom II X4        | 1         | 2.56%   |
| AMD E1                  | 1         | 2.56%   |
| AMD Athlon II X2        | 1         | 2.56%   |
| AMD A8                  | 1         | 2.56%   |
| AMD A4                  | 1         | 2.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 21        | 53.85%  |
| 4      | 10        | 25.64%  |
| 8      | 5         | 12.82%  |
| 1      | 2         | 5.13%   |
| 6      | 1         | 2.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 38        | 97.44%  |
| 2      | 1         | 2.56%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 21        | 53.85%  |
| 1      | 18        | 46.15%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 37        | 94.87%  |
| 32-bit         | 1         | 2.56%   |
| Unknown        | 1         | 2.56%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x1067a    | 5         | 12.82%  |
| Unknown    | 5         | 12.82%  |
| 0x206a7    | 4         | 10.26%  |
| 0x806d1    | 2         | 5.13%   |
| 0x406e3    | 2         | 5.13%   |
| 0x306c3    | 2         | 5.13%   |
| 0x306a9    | 2         | 5.13%   |
| 0x06001119 | 2         | 5.13%   |
| 0x906eb    | 1         | 2.56%   |
| 0x906e9    | 1         | 2.56%   |
| 0x806ea    | 1         | 2.56%   |
| 0x806e9    | 1         | 2.56%   |
| 0x706a1    | 1         | 2.56%   |
| 0x406c4    | 1         | 2.56%   |
| 0x30678    | 1         | 2.56%   |
| 0x206d7    | 1         | 2.56%   |
| 0x206c2    | 1         | 2.56%   |
| 0x106c2    | 1         | 2.56%   |
| 0x10676    | 1         | 2.56%   |
| 0x0a50000c | 1         | 2.56%   |
| 0x0500010d | 1         | 2.56%   |
| 0x010000c8 | 1         | 2.56%   |
| 0x010000b7 | 1         | 2.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Penryn        | 6         | 15.38%  |
| SandyBridge   | 5         | 12.82%  |
| KabyLake      | 4         | 10.26%  |
| IvyBridge     | 3         | 7.69%   |
| Skylake       | 2         | 5.13%   |
| Silvermont    | 2         | 5.13%   |
| Piledriver    | 2         | 5.13%   |
| K10           | 2         | 5.13%   |
| Icelake       | 2         | 5.13%   |
| Haswell       | 2         | 5.13%   |
| Bonnell       | 2         | 5.13%   |
| Unknown       | 2         | 5.13%   |
| Zen 3         | 1         | 2.56%   |
| Westmere      | 1         | 2.56%   |
| Goldmont plus | 1         | 2.56%   |
| Core          | 1         | 2.56%   |
| Bobcat        | 1         | 2.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 26        | 59.09%  |
| Nvidia | 14        | 31.82%  |
| AMD    | 4         | 9.09%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 10.87%  |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 6.52%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 6.52%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 4.35%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 4.35%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 4.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 4.35%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 4.35%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1         | 2.17%   |
| Nvidia GP107GL [Quadro P600]                                                             | 1         | 2.17%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 2.17%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 2.17%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 1         | 2.17%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 1         | 2.17%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                                      | 1         | 2.17%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 1         | 2.17%   |
| Intel UHD Graphics 620                                                                   | 1         | 2.17%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 2.17%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 2.17%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 2.17%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 2.17%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 2.17%   |
| Intel HD Graphics 620                                                                    | 1         | 2.17%   |
| Intel HD Graphics 515                                                                    | 1         | 2.17%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 2.17%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1         | 2.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 2.17%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1         | 2.17%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 1         | 2.17%   |
| AMD Richland [Radeon HD 8550G]                                                           | 1         | 2.17%   |
| AMD Juniper XT [Radeon HD 5770]                                                          | 1         | 2.17%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 1         | 2.17%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 21        | 53.85%  |
| 1 x Nvidia     | 8         | 20.51%  |
| Intel + Nvidia | 5         | 12.82%  |
| 1 x AMD        | 3         | 7.69%   |
| Other          | 1         | 2.56%   |
| AMD + Nvidia   | 1         | 2.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 35        | 89.74%  |
| Unknown | 4         | 10.26%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 23        | 58.97%  |
| 1.01-2.0   | 5         | 12.82%  |
| 0.01-0.5   | 4         | 10.26%  |
| 0.51-1.0   | 3         | 7.69%   |
| 3.01-4.0   | 2         | 5.13%   |
| 7.01-8.0   | 1         | 2.56%   |
| 5.01-6.0   | 1         | 2.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 9         | 24.32%  |
| LG Display              | 4         | 10.81%  |
| Lenovo                  | 3         | 8.11%   |
| Iiyama                  | 3         | 8.11%   |
| AU Optronics            | 3         | 8.11%   |
| Acer                    | 3         | 8.11%   |
| Dell                    | 2         | 5.41%   |
| BOE                     | 2         | 5.41%   |
| Sharp                   | 1         | 2.7%    |
| Plain Tree Systems      | 1         | 2.7%    |
| Philips                 | 1         | 2.7%    |
| Gateway                 | 1         | 2.7%    |
| CPT                     | 1         | 2.7%    |
| Chimei Innolux          | 1         | 2.7%    |
| Chi Mei Optoelectronics | 1         | 2.7%    |
| Ancor Communications    | 1         | 2.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Iiyama PL2283H IVM562E 1920x1080 496x292mm 22.7-inch                     | 3         | 8.11%   |
| Samsung Electronics LCD Monitor SDC414D 3456x2160 336x210mm 15.6-inch    | 2         | 5.41%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch              | 2         | 5.41%   |
| Lenovo LCD Monitor LEN4010 1280x800 261x163mm 12.1-inch                  | 2         | 5.41%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 1         | 2.7%    |
| Samsung Electronics SyncMaster SAM0216 1280x1024 338x270mm 17.0-inch     | 1         | 2.7%    |
| Samsung Electronics SMC27A550U SAM07F6 1920x1080 598x336mm 27.0-inch     | 1         | 2.7%    |
| Samsung Electronics LCD Monitor SEC5442 1440x900 303x190mm 14.1-inch     | 1         | 2.7%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 1         | 2.7%    |
| Samsung Electronics LCD Monitor SEC374E 1024x600 223x125mm 10.1-inch     | 1         | 2.7%    |
| Samsung Electronics LCD Monitor SEC3052 1024x600 223x125mm 10.1-inch     | 1         | 2.7%    |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch    | 1         | 2.7%    |
| Plain Tree Systems Monitor PTS076D 1280x1024 376x301mm 19.0-inch         | 1         | 2.7%    |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 1         | 2.7%    |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch              | 1         | 2.7%    |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch              | 1         | 2.7%    |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 1         | 2.7%    |
| Gateway FPD1976W GWY0785 1440x900 410x257mm 19.1-inch                    | 1         | 2.7%    |
| Dell E151FPp DEL7006 1024x768 300x230mm 14.9-inch                        | 1         | 2.7%    |
| Dell 1909W DELA03C 1440x900 408x255mm 18.9-inch                          | 1         | 2.7%    |
| CPT LCD Monitor CPT1401 1280x800 331x207mm 15.4-inch                     | 1         | 2.7%    |
| Chimei Innolux LCD Monitor CMN1139 1366x768 256x144mm 11.6-inch          | 1         | 2.7%    |
| Chi Mei Optoelectronics LCD Monitor CMO1590 1366x768 344x194mm 15.5-inch | 1         | 2.7%    |
| BOE LCD Monitor BOE07C5 1920x1080 344x194mm 15.5-inch                    | 1         | 2.7%    |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                     | 1         | 2.7%    |
| AU Optronics LCD Monitor AUO409D 1920x1080 382x215mm 17.3-inch           | 1         | 2.7%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 1         | 2.7%    |
| AU Optronics LCD Monitor AUO215C 1366x768 256x144mm 11.6-inch            | 1         | 2.7%    |
| Ancor Communications ASUS VS229 ACI22D3 1920x1080 475x267mm 21.5-inch    | 1         | 2.7%    |
| Acer KG251Q ACR0591 1920x1080 544x303mm 24.5-inch                        | 1         | 2.7%    |
| Acer K242HL ACR03E3 1920x1080 531x299mm 24.0-inch                        | 1         | 2.7%    |
| Acer H236HL ACR0318 1920x1080 509x286mm 23.0-inch                        | 1         | 2.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 12        | 34.29%  |
| 1366x768 (WXGA)  | 10        | 28.57%  |
| 1280x800 (WXGA)  | 4         | 11.43%  |
| 3456x2160        | 2         | 5.71%   |
| 1600x900 (HD+)   | 2         | 5.71%   |
| 1440x900 (WXGA+) | 2         | 5.71%   |
| 3840x2160 (4K)   | 1         | 2.86%   |
| 1280x1024 (SXGA) | 1         | 2.86%   |
| 1024x768 (XGA)   | 1         | 2.86%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 12        | 32.43%  |
| 23     | 5         | 13.51%  |
| 14     | 4         | 10.81%  |
| 19     | 3         | 8.11%   |
| 17     | 3         | 8.11%   |
| 12     | 3         | 8.11%   |
| 24     | 2         | 5.41%   |
| 11     | 2         | 5.41%   |
| 27     | 1         | 2.7%    |
| 21     | 1         | 2.7%    |
| 13     | 1         | 2.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 15        | 41.67%  |
| 501-600     | 8         | 22.22%  |
| 201-300     | 6         | 16.67%  |
| 351-400     | 4         | 11.11%  |
| 401-500     | 3         | 8.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 25        | 71.43%  |
| 16/10 | 7         | 20%     |
| 5/4   | 1         | 2.86%   |
| 4/3   | 1         | 2.86%   |
| 3/2   | 1         | 2.86%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 12        | 32.43%  |
| 201-250        | 7         | 18.92%  |
| 81-90          | 4         | 10.81%  |
| 61-70          | 3         | 8.11%   |
| 151-200        | 3         | 8.11%   |
| 51-60          | 2         | 5.41%   |
| 71-80          | 1         | 2.7%    |
| 301-350        | 1         | 2.7%    |
| 251-300        | 1         | 2.7%    |
| 141-150        | 1         | 2.7%    |
| 131-140        | 1         | 2.7%    |
| 121-130        | 1         | 2.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 13        | 38.24%  |
| 121-160       | 9         | 26.47%  |
| 101-120       | 8         | 23.53%  |
| More than 240 | 3         | 8.82%   |
| 161-240       | 1         | 2.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 35        | 87.5%   |
| 0     | 3         | 7.5%    |
| 3     | 1         | 2.5%    |
| 2     | 1         | 2.5%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 19        | 28.36%  |
| Qualcomm Atheros                | 17        | 25.37%  |
| Intel                           | 16        | 23.88%  |
| Qualcomm Atheros Communications | 4         | 5.97%   |
| Ralink Technology               | 2         | 2.99%   |
| Nvidia                          | 2         | 2.99%   |
| Marvell Technology Group        | 2         | 2.99%   |
| Broadcom                        | 2         | 2.99%   |
| Samsung Electronics             | 1         | 1.49%   |
| Qualcomm                        | 1         | 1.49%   |
| Microsoft                       | 1         | 1.49%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 10        | 13.33%  |
| Qualcomm Atheros AR9271 802.11n                                     | 4         | 5.33%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                    | 4         | 5.33%   |
| Intel Tiger Lake PCH CNVi WiFi                                      | 3         | 4%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 3         | 4%      |
| Intel 82567LM Gigabit Network Connection                            | 3         | 4%      |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter             | 2         | 2.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 2         | 2.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 2         | 2.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 2         | 2.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 2         | 2.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 2         | 2.67%   |
| Nvidia MCP61 Ethernet                                               | 2         | 2.67%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                        | 2         | 2.67%   |
| Samsung HSPA Modem                                                  | 1         | 1.33%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter            | 1         | 1.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 1         | 1.33%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                     | 1         | 1.33%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter            | 1         | 1.33%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                    | 1         | 1.33%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 1         | 1.33%   |
| Ralink MT7601U Wireless Adapter                                     | 1         | 1.33%   |
| Qualcomm POCO M2 Pro                                                | 1         | 1.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 1         | 1.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter          | 1         | 1.33%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                              | 1         | 1.33%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 1         | 1.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 1         | 1.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                    | 1         | 1.33%   |
| Qualcomm Atheros AR8162 Fast Ethernet                               | 1         | 1.33%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                          | 1         | 1.33%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg] | 1         | 1.33%   |
| Microsoft RTL8153 GigE [Surface Ethernet Adapter]                   | 1         | 1.33%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller             | 1         | 1.33%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                | 1         | 1.33%   |
| Intel Wireless 7265                                                 | 1         | 1.33%   |
| Intel Wireless 3165                                                 | 1         | 1.33%   |
| Intel WiFi Link 5100                                                | 1         | 1.33%   |
| Intel Ethernet Connection (5) I219-LM                               | 1         | 1.33%   |
| Intel Centrino Wireless-N 6150                                      | 1         | 1.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 13        | 36.11%  |
| Intel                           | 10        | 27.78%  |
| Realtek Semiconductor           | 6         | 16.67%  |
| Qualcomm Atheros Communications | 4         | 11.11%  |
| Ralink Technology               | 2         | 5.56%   |
| Broadcom                        | 1         | 2.78%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9271 802.11n                                     | 4         | 10.81%  |
| Qualcomm Atheros AR93xx Wireless Network Adapter                    | 4         | 10.81%  |
| Intel Tiger Lake PCH CNVi WiFi                                      | 3         | 8.11%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter             | 2         | 5.41%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 2         | 5.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 2         | 5.41%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                        | 2         | 5.41%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter            | 1         | 2.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 1         | 2.7%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                     | 1         | 2.7%    |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter            | 1         | 2.7%    |
| Ralink RT2870/RT3070 Wireless Adapter                               | 1         | 2.7%    |
| Ralink MT7601U Wireless Adapter                                     | 1         | 2.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 1         | 2.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter          | 1         | 2.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 1         | 2.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                    | 1         | 2.7%    |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg] | 1         | 2.7%    |
| Intel Wireless 7265                                                 | 1         | 2.7%    |
| Intel Wireless 3165                                                 | 1         | 2.7%    |
| Intel WiFi Link 5100                                                | 1         | 2.7%    |
| Intel Centrino Wireless-N 6150                                      | 1         | 2.7%    |
| Intel Centrino Wireless-N + WiMAX 6150                              | 1         | 2.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                        | 1         | 2.7%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller              | 1         | 2.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 15        | 40.54%  |
| Intel                    | 9         | 24.32%  |
| Qualcomm Atheros         | 6         | 16.22%  |
| Nvidia                   | 2         | 5.41%   |
| Marvell Technology Group | 2         | 5.41%   |
| Qualcomm                 | 1         | 2.7%    |
| Microsoft                | 1         | 2.7%    |
| Broadcom                 | 1         | 2.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10        | 27.03%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 8.11%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 8.11%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 5.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 5.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 5.41%   |
| Nvidia MCP61 Ethernet                                             | 2         | 5.41%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 2.7%    |
| Qualcomm POCO M2 Pro                                              | 1         | 2.7%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 2.7%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 2.7%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 2.7%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 2.7%    |
| Microsoft RTL8153 GigE [Surface Ethernet Adapter]                 | 1         | 2.7%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 2.7%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 2.7%    |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 2.7%    |
| Intel 82574L Gigabit Network Connection                           | 1         | 2.7%    |
| Intel 82567LF Gigabit Network Connection                          | 1         | 2.7%    |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 2.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 37        | 52.86%  |
| WiFi     | 32        | 45.71%  |
| Modem    | 1         | 1.43%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 20        | 52.63%  |
| WiFi     | 18        | 47.37%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 21        | 53.85%  |
| 1     | 16        | 41.03%  |
| 3     | 1         | 2.56%   |
| 0     | 1         | 2.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 30        | 76.92%  |
| Yes  | 9         | 23.08%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 5         | 27.78%  |
| Qualcomm Atheros Communications | 4         | 22.22%  |
| Broadcom                        | 3         | 16.67%  |
| Toshiba                         | 2         | 11.11%  |
| Realtek Semiconductor           | 2         | 11.11%  |
| Foxconn / Hon Hai               | 1         | 5.56%   |
| Apple                           | 1         | 5.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                              | 3         | 16.67%  |
| Realtek Bluetooth Radio                            | 2         | 11.11%  |
| Qualcomm Atheros  Bluetooth Device                 | 2         | 11.11%  |
| Intel Bluetooth wireless interface                 | 2         | 11.11%  |
| Toshiba RT Bluetooth Radio                         | 1         | 5.56%   |
| Toshiba Bluetooth Device                           | 1         | 5.56%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0             | 1         | 5.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0              | 1         | 5.56%   |
| Foxconn / Hon Hai Bluetooth Device                 | 1         | 5.56%   |
| Broadcom BCM20702A0 Bluetooth 4.0                  | 1         | 5.56%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]         | 1         | 5.56%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 5.56%   |
| Apple Built-in Bluetooth 2.0+EDR HCI               | 1         | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 32        | 66.67%  |
| Nvidia                | 10        | 20.83%  |
| AMD                   | 4         | 8.33%   |
| Realtek Semiconductor | 1         | 2.08%   |
| Creative Labs         | 1         | 2.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 11.54%  |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 9.62%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 4         | 7.69%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 5.77%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 5.77%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 5.77%   |
| Nvidia MCP61 High Definition Audio                                                                | 2         | 3.85%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 3.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 3.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 3.85%   |
| AMD FCH Azalia Controller                                                                         | 2         | 3.85%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 1.92%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.92%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 1.92%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 1.92%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 1.92%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.92%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 1.92%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1         | 1.92%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 1.92%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.92%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.92%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 1.92%   |
| Creative Labs CA0110 [Sound Blaster X-Fi Xtreme Audio]                                            | 1         | 1.92%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 1.92%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                                    | 1         | 1.92%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1         | 1.92%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 10        | 31.25%  |
| SK hynix            | 5         | 15.63%  |
| Micron Technology   | 5         | 15.63%  |
| Kingston            | 3         | 9.38%   |
| Unknown             | 2         | 6.25%   |
| Ramaxel Technology  | 1         | 3.13%   |
| Qimonda             | 1         | 3.13%   |
| PNY                 | 1         | 3.13%   |
| GOODRAM             | 1         | 3.13%   |
| G.Skill             | 1         | 3.13%   |
| Crucial             | 1         | 3.13%   |
| A-DATA Technology   | 1         | 3.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s                     | 2         | 6.25%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s                     | 2         | 6.25%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                              | 1         | 3.13%   |
| Unknown RAM 3634543235363032304555322E3543322020 2048MB DIMM DDR2 800MT/s | 1         | 3.13%   |
| SK hynix RAM Module 1024MB DIMM DDR3 1066MT/s                             | 1         | 3.13%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s                     | 1         | 3.13%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s                      | 1         | 3.13%   |
| SK hynix RAM HMT41GS6AFR8A-H9 8192MB SODIMM DDR3 1333MT/s                 | 1         | 3.13%   |
| SK hynix RAM HMA851S6CJR6N-UH 4GB SODIMM DDR4 2400MT/s                    | 1         | 3.13%   |
| Samsung RAM Module 4096MB DIMM DDR4 2400MT/s                              | 1         | 3.13%   |
| Samsung RAM Module 4096MB DIMM DDR3 1066MT/s                              | 1         | 3.13%   |
| Samsung RAM Module 2GB Row Of Chips DDR3 1600MT/s                         | 1         | 3.13%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s                     | 1         | 3.13%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 1         | 3.13%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s                       | 1         | 3.13%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s                   | 1         | 3.13%   |
| Qimonda RAM 64T512022EDL2.5A 4096MB SODIMM DDR 800MT/s                    | 1         | 3.13%   |
| PNY RAM Module 4096MB DIMM DDR3 1066MT/s                                  | 1         | 3.13%   |
| Micron RAM MT52L512M32D2PF-10 4GB Row Of Chips LPDDR3 1867MT/s            | 1         | 3.13%   |
| Micron RAM Module 2048MB DIMM DDR3 1066MT/s                               | 1         | 3.13%   |
| Micron RAM H6451U64F7066G 4096MB SODIMM DDR3 1067MT/s                     | 1         | 3.13%   |
| Micron RAM 4ATF51264HZ-2G3H1R 4GB SODIMM DDR4 2400MT/s                    | 1         | 3.13%   |
| Micron RAM 36JSF1G72PZ-1 8192MB DIMM DDR3 1866MT/s                        | 1         | 3.13%   |
| Kingston RAM ASU1600S11-4G-EDEG 4GB SODIMM DDR3 1600MT/s                  | 1         | 3.13%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s                     | 1         | 3.13%   |
| Kingston RAM 9905624-044.A00G 8GB SODIMM DDR4 2400MT/s                    | 1         | 3.13%   |
| GOODRAM RAM GY1600D364L9/4G 4GB DIMM DDR3 1333MT/s                        | 1         | 3.13%   |
| G.Skill RAM F3-2400C11-8GXM 8GB DIMM DDR3 2400MT/s                        | 1         | 3.13%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s                   | 1         | 3.13%   |
| A-DATA RAM Module 4096MB SODIMM DDR4 2400MT/s                             | 1         | 3.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR3   | 15        | 57.69%  |
| DDR4   | 7         | 26.92%  |
| DDR2   | 2         | 7.69%   |
| LPDDR3 | 1         | 3.85%   |
| DDR    | 1         | 3.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 13        | 52%     |
| DIMM         | 10        | 40%     |
| Row Of Chips | 2         | 8%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Computers | Percent |
|------|-----------|---------|
| 4096 | 15        | 50%     |
| 8192 | 9         | 30%     |
| 2048 | 5         | 16.67%  |
| 1024 | 1         | 3.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 8         | 28.57%  |
| 3200  | 4         | 14.29%  |
| 2400  | 4         | 14.29%  |
| 1333  | 2         | 7.14%   |
| 1066  | 2         | 7.14%   |
| 800   | 2         | 7.14%   |
| 2133  | 1         | 3.57%   |
| 1867  | 1         | 3.57%   |
| 1866  | 1         | 3.57%   |
| 1334  | 1         | 3.57%   |
| 1067  | 1         | 3.57%   |
| 975   | 1         | 3.57%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 5         | 22.73%  |
| Sunplus Innovation Technology          | 3         | 13.64%  |
| Microdia                               | 3         | 13.64%  |
| Lenovo                                 | 3         | 13.64%  |
| Z-Star Microelectronics                | 1         | 4.55%   |
| Realtek Semiconductor                  | 1         | 4.55%   |
| Quanta                                 | 1         | 4.55%   |
| Logitech                               | 1         | 4.55%   |
| Importek                               | 1         | 4.55%   |
| IMC Networks                           | 1         | 4.55%   |
| GoPro                                  | 1         | 4.55%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 4.55%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Lenovo Integrated Webcam                                     | 3         | 13.64%  |
| Z-Star Webcam                                                | 1         | 4.55%   |
| Sunplus HD WebCam                                            | 1         | 4.55%   |
| Sunplus Asus Webcam                                          | 1         | 4.55%   |
| Sunplus 2K FHD camera                                        | 1         | 4.55%   |
| Realtek Lenovo EasyCamera                                    | 1         | 4.55%   |
| Quanta HD User Facing                                        | 1         | 4.55%   |
| Microdia Integrated_Webcam_HD                                | 1         | 4.55%   |
| Microdia Integrated_Webcam_1.3M                              | 1         | 4.55%   |
| Microdia Integrated Webcam HD                                | 1         | 4.55%   |
| Logitech C505 HD Webcam                                      | 1         | 4.55%   |
| Importek TOSHIBA Web Camera                                  | 1         | 4.55%   |
| IMC Networks UVC VGA Webcam                                  | 1         | 4.55%   |
| GoPro HERO4 Black                                            | 1         | 4.55%   |
| Chicony TOSHIBA Web Camera                                   | 1         | 4.55%   |
| Chicony Thinkpad T430 camera                                 | 1         | 4.55%   |
| Chicony integrated camera                                    | 1         | 4.55%   |
| Chicony HP Wide Vision HD Camera                             | 1         | 4.55%   |
| Chicony HP Webcam                                            | 1         | 4.55%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 1         | 4.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor    | Computers | Percent |
|-----------|-----------|---------|
| AuthenTec | 1         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| AuthenTec AES2810 | 1         | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Upek     | 1         | 50%     |
| Broadcom | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 50%     |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 25        | 62.5%   |
| 1     | 10        | 25%     |
| 2     | 5         | 12.5%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 9         | 52.94%  |
| Net/wireless          | 2         | 11.76%  |
| Multimedia controller | 2         | 11.76%  |
| Chipcard              | 2         | 11.76%  |
| Fingerprint reader    | 1         | 5.88%   |
| Bluetooth             | 1         | 5.88%   |

