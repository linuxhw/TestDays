Solus 4.3 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Solus 4.3.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 45

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Samsung       | R430/P430/R480              | [ae3789203b](https://linux-hardware.org/?probe=ae3789203b) | Dec 18, 2022 |
| Toshiba       | Satellite L855              | [932d8fec2d](https://linux-hardware.org/?probe=932d8fec2d) | Dec 12, 2022 |
| MSI           | Modern 14 B5M               | [2bd9abfe2c](https://linux-hardware.org/?probe=2bd9abfe2c) | Nov 20, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [12b14f3cbc](https://linux-hardware.org/?probe=12b14f3cbc) | Nov 06, 2022 |
| Quanta        | TWS                         | [a800f54191](https://linux-hardware.org/?probe=a800f54191) | Nov 06, 2022 |
| Toshiba       | Satellite L855              | [1065197a6e](https://linux-hardware.org/?probe=1065197a6e) | Sep 15, 2022 |
| Dell          | Latitude E5470              | [8cd7ffad9e](https://linux-hardware.org/?probe=8cd7ffad9e) | Aug 08, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [76083d81dc](https://linux-hardware.org/?probe=76083d81dc) | Jul 30, 2022 |
| Acer          | Aspire A315-54              | [9e0bbc26f4](https://linux-hardware.org/?probe=9e0bbc26f4) | Jul 22, 2022 |
| AZW           | SEi                         | [7556cabcae](https://linux-hardware.org/?probe=7556cabcae) | Jul 07, 2022 |
| GPU Compan... | GWTC116-2                   | [d0c0f4f120](https://linux-hardware.org/?probe=d0c0f4f120) | Jul 06, 2022 |
| GPU Compan... | GWTC116-2                   | [9d0dd21c70](https://linux-hardware.org/?probe=9d0dd21c70) | Jul 06, 2022 |
| HP            | ProBook 450 G5              | [c4880f9bab](https://linux-hardware.org/?probe=c4880f9bab) | Jun 02, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [5330a5aa11](https://linux-hardware.org/?probe=5330a5aa11) | Jun 02, 2022 |
| HP            | ProBook 450 G5              | [7f8acf64cd](https://linux-hardware.org/?probe=7f8acf64cd) | May 31, 2022 |
| HP            | ProBook 450 G5              | [2fbbe84744](https://linux-hardware.org/?probe=2fbbe84744) | May 31, 2022 |
| Google        | Edgar                       | [fef9eeb5db](https://linux-hardware.org/?probe=fef9eeb5db) | May 02, 2022 |
| Lenovo        | Z50-70 20354                | [6d50395aee](https://linux-hardware.org/?probe=6d50395aee) | Apr 22, 2022 |
| Dell          | XPS 13 7390                 | [80c38b1425](https://linux-hardware.org/?probe=80c38b1425) | Apr 19, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [9391fc9592](https://linux-hardware.org/?probe=9391fc9592) | Mar 23, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [81ec123b24](https://linux-hardware.org/?probe=81ec123b24) | Mar 15, 2022 |
| Dell          | XPS 13 9380                 | [efc6123d49](https://linux-hardware.org/?probe=efc6123d49) | Mar 06, 2022 |
| Google        | Delbin                      | [fbf8763bd4](https://linux-hardware.org/?probe=fbf8763bd4) | Feb 05, 2022 |
| Acer          | Aspire A315-54              | [5eb9b9e574](https://linux-hardware.org/?probe=5eb9b9e574) | Jan 22, 2022 |
| Acer          | Swift SF114-34              | [15431686d8](https://linux-hardware.org/?probe=15431686d8) | Jan 06, 2022 |
| Toshiba       | TECRA R840                  | [753c7caef6](https://linux-hardware.org/?probe=753c7caef6) | Dec 27, 2021 |
| Sony          | VPCYB15AB                   | [780ef18db3](https://linux-hardware.org/?probe=780ef18db3) | Dec 13, 2021 |
| Dell          | Latitude 5580               | [a10f022f63](https://linux-hardware.org/?probe=a10f022f63) | Nov 26, 2021 |
| Framework     | Laptop                      | [7995a7a4de](https://linux-hardware.org/?probe=7995a7a4de) | Nov 18, 2021 |
| Dell          | Latitude E6220              | [09a75055c9](https://linux-hardware.org/?probe=09a75055c9) | Nov 12, 2021 |
| Framework     | Laptop                      | [72a07a2e81](https://linux-hardware.org/?probe=72a07a2e81) | Nov 11, 2021 |
| AZW           | SEi                         | [0e29003348](https://linux-hardware.org/?probe=0e29003348) | Oct 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c7f1620c1c](https://linux-hardware.org/?probe=c7f1620c1c) | Oct 05, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | [f19ad7cba2](https://linux-hardware.org/?probe=f19ad7cba2) | Sep 16, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | [1cca1c6ce5](https://linux-hardware.org/?probe=1cca1c6ce5) | Sep 13, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | [888bf75e20](https://linux-hardware.org/?probe=888bf75e20) | Sep 13, 2021 |
| Acer          | Nitro AN515-45              | [5bad88330d](https://linux-hardware.org/?probe=5bad88330d) | Sep 01, 2021 |
| Dell          | Inspiron 1525               | [3f3cd9c9e2](https://linux-hardware.org/?probe=3f3cd9c9e2) | Aug 25, 2021 |
| Dell          | Inspiron 1525               | [de3cb038ef](https://linux-hardware.org/?probe=de3cb038ef) | Aug 25, 2021 |
| Acer          | Nitro AN515-45              | [d98d816e7f](https://linux-hardware.org/?probe=d98d816e7f) | Aug 18, 2021 |
| Acer          | Nitro AN515-45              | [5320b136ea](https://linux-hardware.org/?probe=5320b136ea) | Aug 12, 2021 |
| Dell          | Vostro 15-3568              | [5f68a1fdaa](https://linux-hardware.org/?probe=5f68a1fdaa) | Aug 07, 2021 |
| HP            | ProBook 650 G2              | [15257858f3](https://linux-hardware.org/?probe=15257858f3) | Aug 07, 2021 |
| Dell          | Inspiron 15-3573            | [52916532a3](https://linux-hardware.org/?probe=52916532a3) | Aug 06, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [75ec31cefd](https://linux-hardware.org/?probe=75ec31cefd) | Jul 16, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Notebooks | Percent |
|---------------------|-----------|---------|
| 5.15.50-216.current | 4         | 12.5%   |
| 5.13.1-187.current  | 4         | 12.5%   |
| 5.15.32-213.current | 3         | 9.38%   |
| 5.14.21-210.current | 3         | 9.38%   |
| 6.0.11-225.current  | 2         | 6.25%   |
| 5.15.77-219.current | 2         | 6.25%   |
| 5.14.16-205.current | 2         | 6.25%   |
| 5.13.6-190.current  | 2         | 6.25%   |
| 5.13.12-193.current | 2         | 6.25%   |
| 5.15.61-217.current | 1         | 3.13%   |
| 5.15.37-214.current | 1         | 3.13%   |
| 5.15.26-211.current | 1         | 3.13%   |
| 5.14.7-198.current  | 1         | 3.13%   |
| 5.14.16-204.current | 1         | 3.13%   |
| 5.14.15-203.current | 1         | 3.13%   |
| 5.14.12-201.current | 1         | 3.13%   |
| 5.13.15-194.current | 1         | 3.13%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.50 | 4         | 12.5%   |
| 5.13.1  | 4         | 12.5%   |
| 5.15.32 | 3         | 9.38%   |
| 5.14.21 | 3         | 9.38%   |
| 5.14.16 | 3         | 9.38%   |
| 6.0.11  | 2         | 6.25%   |
| 5.15.77 | 2         | 6.25%   |
| 5.13.6  | 2         | 6.25%   |
| 5.13.12 | 2         | 6.25%   |
| 5.15.61 | 1         | 3.13%   |
| 5.15.37 | 1         | 3.13%   |
| 5.15.26 | 1         | 3.13%   |
| 5.14.7  | 1         | 3.13%   |
| 5.14.15 | 1         | 3.13%   |
| 5.14.12 | 1         | 3.13%   |
| 5.13.15 | 1         | 3.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 12        | 37.5%   |
| 5.14    | 9         | 28.13%  |
| 5.13    | 9         | 28.13%  |
| 6.0     | 2         | 6.25%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 29        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Budgie  | 14        | 46.67%  |
| MATE    | 5         | 16.67%  |
| Unknown | 4         | 13.33%  |
| KDE5    | 3         | 10%     |
| KDE     | 2         | 6.67%   |
| GNOME   | 2         | 6.67%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 29        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 21        | 70%     |
| LightDM | 6         | 20%     |
| SDDM    | 2         | 6.67%   |
| GDM     | 1         | 3.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 19        | 65.52%  |
| en_GB | 3         | 10.34%  |
| de_DE | 3         | 10.34%  |
| pt_BR | 1         | 3.45%   |
| fr_FR | 1         | 3.45%   |
| es_ES | 1         | 3.45%   |
| en_IN | 1         | 3.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 21        | 67.74%  |
| BIOS | 10        | 32.26%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 28        | 96.55%  |
| Overlay | 1         | 3.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 19        | 65.52%  |
| GPT     | 8         | 27.59%  |
| MBR     | 2         | 6.9%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 28        | 96.55%  |
| Yes       | 1         | 3.45%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 24        | 82.76%  |
| Yes       | 5         | 17.24%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 8         | 27.59%  |
| Lenovo              | 5         | 17.24%  |
| Acer                | 3         | 10.34%  |
| Toshiba             | 2         | 6.9%    |
| Hewlett-Packard     | 2         | 6.9%    |
| Google              | 2         | 6.9%    |
| Sony                | 1         | 3.45%   |
| Samsung Electronics | 1         | 3.45%   |
| MSI                 | 1         | 3.45%   |
| GPU Company         | 1         | 3.45%   |
| Framework           | 1         | 3.45%   |
| AZW                 | 1         | 3.45%   |
| ASUSTek Computer    | 1         | 3.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Toshiba TECRA R840                     | 1         | 3.45%   |
| Toshiba Satellite L855                 | 1         | 3.45%   |
| Sony VPCYB15AB                         | 1         | 3.45%   |
| Samsung R430/P430/R480                 | 1         | 3.45%   |
| MSI Modern 14 B5M                      | 1         | 3.45%   |
| Lenovo Z50-70 20354                    | 1         | 3.45%   |
| Lenovo ThinkPad T15 Gen 2i 20W4CTO1WW  | 1         | 3.45%   |
| Lenovo IdeaPad S340-15API 81NC         | 1         | 3.45%   |
| Lenovo IdeaPad 5 15ALC05 82LN          | 1         | 3.45%   |
| Lenovo IdeaPad 320-15ISK 80XH          | 1         | 3.45%   |
| HP ProBook 450 G5                      | 1         | 3.45%   |
| HP OMEN Laptop 15-en0xxx               | 1         | 3.45%   |
| GPU Company GWTC116-2                  | 1         | 3.45%   |
| Google Edgar                           | 1         | 3.45%   |
| Google Delbin                          | 1         | 3.45%   |
| Framework Laptop                       | 1         | 3.45%   |
| Dell XPS 13 9380                       | 1         | 3.45%   |
| Dell XPS 13 7390                       | 1         | 3.45%   |
| Dell Vostro 15-3568                    | 1         | 3.45%   |
| Dell Latitude E6220                    | 1         | 3.45%   |
| Dell Latitude E5470                    | 1         | 3.45%   |
| Dell Latitude 5580                     | 1         | 3.45%   |
| Dell Inspiron 1525                     | 1         | 3.45%   |
| Dell Inspiron 15-3573                  | 1         | 3.45%   |
| AZW SEi                                | 1         | 3.45%   |
| ASUS VivoBook_ASUSLaptop X509DA_M509DA | 1         | 3.45%   |
| Acer Swift SF114-34                    | 1         | 3.45%   |
| Acer Nitro AN515-45                    | 1         | 3.45%   |
| Acer Aspire A315-54                    | 1         | 3.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo IdeaPad        | 3         | 10.34%  |
| Dell Latitude         | 3         | 10.34%  |
| Dell XPS              | 2         | 6.9%    |
| Dell Inspiron         | 2         | 6.9%    |
| Toshiba TECRA         | 1         | 3.45%   |
| Toshiba Satellite     | 1         | 3.45%   |
| Sony VPCYB15AB        | 1         | 3.45%   |
| Samsung R430          | 1         | 3.45%   |
| MSI Modern            | 1         | 3.45%   |
| Lenovo Z50-70         | 1         | 3.45%   |
| Lenovo ThinkPad       | 1         | 3.45%   |
| HP ProBook            | 1         | 3.45%   |
| HP OMEN               | 1         | 3.45%   |
| GPU Company GWTC116-2 | 1         | 3.45%   |
| Google Edgar          | 1         | 3.45%   |
| Google Delbin         | 1         | 3.45%   |
| Framework Laptop      | 1         | 3.45%   |
| Dell Vostro           | 1         | 3.45%   |
| AZW SEi               | 1         | 3.45%   |
| ASUS VivoBook         | 1         | 3.45%   |
| Acer Swift            | 1         | 3.45%   |
| Acer Nitro            | 1         | 3.45%   |
| Acer Aspire           | 1         | 3.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 7         | 24.14%  |
| 2019 | 5         | 17.24%  |
| 2020 | 3         | 10.34%  |
| 2017 | 3         | 10.34%  |
| 2018 | 2         | 6.9%    |
| 2016 | 2         | 6.9%    |
| 2011 | 2         | 6.9%    |
| 2010 | 2         | 6.9%    |
| 2014 | 1         | 3.45%   |
| 2012 | 1         | 3.45%   |
| 2008 | 1         | 3.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 29        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 29        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 27        | 93.1%   |
| Yes  | 2         | 6.9%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 7         | 24.14%  |
| 3.01-4.0   | 6         | 20.69%  |
| 8.01-16.0  | 5         | 17.24%  |
| 32.01-64.0 | 4         | 13.79%  |
| 16.01-24.0 | 4         | 13.79%  |
| 1.01-2.0   | 2         | 6.9%    |
| 2.01-3.0   | 1         | 3.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 13        | 41.94%  |
| 1.01-2.0 | 9         | 29.03%  |
| 3.01-4.0 | 4         | 12.9%   |
| 4.01-8.0 | 3         | 9.68%   |
| 0.51-1.0 | 2         | 6.45%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 23        | 79.31%  |
| 2      | 6         | 20.69%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 22        | 75.86%  |
| Yes       | 7         | 24.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 19        | 65.52%  |
| No        | 10        | 34.48%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 86.21%  |
| No        | 4         | 13.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 6         | 20.69%  |
| India       | 3         | 10.34%  |
| UK          | 2         | 6.9%    |
| Netherlands | 2         | 6.9%    |
| Germany     | 2         | 6.9%    |
| Brazil      | 2         | 6.9%    |
| Vietnam     | 1         | 3.45%   |
| Ukraine     | 1         | 3.45%   |
| Switzerland | 1         | 3.45%   |
| Poland      | 1         | 3.45%   |
| Norway      | 1         | 3.45%   |
| Nepal       | 1         | 3.45%   |
| Mexico      | 1         | 3.45%   |
| France      | 1         | 3.45%   |
| Czechia     | 1         | 3.45%   |
| Belgium     | 1         | 3.45%   |
| Australia   | 1         | 3.45%   |
| Argentina   | 1         | 3.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Yverdon-les-Bains        | 1         | 3.23%   |
| Wendell                  | 1         | 3.23%   |
| Vineland                 | 1         | 3.23%   |
| Vasco da Gama            | 1         | 3.23%   |
| Stare Babice             | 1         | 3.23%   |
| San Justo                | 1         | 3.23%   |
| Saint-Just-Saint-Rambert | 1         | 3.23%   |
| Red Oak                  | 1         | 3.23%   |
| Pomeroy                  | 1         | 3.23%   |
| Oslo                     | 1         | 3.23%   |
| Mohali                   | 1         | 3.23%   |
| Milwaukee                | 1         | 3.23%   |
| Melbourne                | 1         | 3.23%   |
| Lviv                     | 1         | 3.23%   |
| Luckenwalde              | 1         | 3.23%   |
| Linter                   | 1         | 3.23%   |
| León                    | 1         | 3.23%   |
| Kathmandu                | 1         | 3.23%   |
| Ilford                   | 1         | 3.23%   |
| Hanoi                    | 1         | 3.23%   |
| Guanajuato City          | 1         | 3.23%   |
| Groningen                | 1         | 3.23%   |
| Greenwich                | 1         | 3.23%   |
| Goiânia                 | 1         | 3.23%   |
| Essen                    | 1         | 3.23%   |
| Dubenec                  | 1         | 3.23%   |
| Coimbatore               | 1         | 3.23%   |
| Chelmsford               | 1         | 3.23%   |
| Belo Horizonte           | 1         | 3.23%   |
| Anacortes                | 1         | 3.23%   |
| Amsterdam                | 1         | 3.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 13.51%  |
| SanDisk             | 5         | 7      | 13.51%  |
| SK hynix            | 4         | 4      | 10.81%  |
| Samsung Electronics | 4         | 5      | 10.81%  |
| Unknown             | 3         | 3      | 8.11%   |
| Seagate             | 3         | 4      | 8.11%   |
| Intel               | 3         | 4      | 8.11%   |
| Toshiba             | 2         | 2      | 5.41%   |
| Kingston            | 2         | 2      | 5.41%   |
| Silicon Motion      | 1         | 1      | 2.7%    |
| SABRENT             | 1         | 1      | 2.7%    |
| PNY                 | 1         | 1      | 2.7%    |
| Phison              | 1         | 1      | 2.7%    |
| KIOXIA              | 1         | 1      | 2.7%    |
| Advantech           | 1         | 1      | 2.7%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| SK hynix NVMe SSD Drive 128GB          | 2         | 5.13%   |
| SanDisk NVMe SSD Drive 256GB           | 2         | 5.13%   |
| WDC WD3200BEVT-75ZCT2 320GB            | 1         | 2.56%   |
| WDC WD2500BEVT-22ZCT0 250GB            | 1         | 2.56%   |
| WDC WD10SPZX-24Z10T0 1TB               | 1         | 2.56%   |
| WDC WD10SPZX-24Z10 1TB                 | 1         | 2.56%   |
| WDC WD10JPCX-24UE4T0 1TB               | 1         | 2.56%   |
| Unknown USB DISK 3.2 1TB               | 1         | 2.56%   |
| Unknown MMC Card  64GB                 | 1         | 2.56%   |
| Unknown MMC Card  128GB                | 1         | 2.56%   |
| Toshiba MQ01ABF050 500GB               | 1         | 2.56%   |
| Toshiba KXG60ZNV512G NVMe 512GB        | 1         | 2.56%   |
| SK hynix NVMe SSD Drive 500GB          | 1         | 2.56%   |
| SK hynix NVMe SSD Drive 256GB          | 1         | 2.56%   |
| Silicon Motion NVMe SSD Drive 512GB    | 1         | 2.56%   |
| Seagate ST9320325AS 320GB              | 1         | 2.56%   |
| Seagate ST1000LM049-2GH172 1TB         | 1         | 2.56%   |
| Seagate ST1000LM035-1RK172 1TB         | 1         | 2.56%   |
| SanDisk SDSSDH32000G 2TB               | 1         | 2.56%   |
| SanDisk NVMe SSD Drive 1TB             | 1         | 2.56%   |
| SanDisk Extreme Pro 1TB                | 1         | 2.56%   |
| SanDisk DF4032  32GB                   | 1         | 2.56%   |
| Samsung SSD 850 EVO 250GB              | 1         | 2.56%   |
| Samsung NVMe SSD Drive 512GB           | 1         | 2.56%   |
| Samsung NVMe SSD Drive 2TB             | 1         | 2.56%   |
| Samsung MZVL22T0HBLB-00BL7 2TB         | 1         | 2.56%   |
| Samsung MZALQ512HBLU-00BL2 512GB       | 1         | 2.56%   |
| SABRENT Disk 1TB                       | 1         | 2.56%   |
| PNY CS900 240GB SSD                    | 1         | 2.56%   |
| Phison NVMe SSD Drive 512GB            | 1         | 2.56%   |
| KIOXIA KXG60ZNV512G NVMe 512GB         | 1         | 2.56%   |
| Kingston SA400S37240G 240GB SSD        | 1         | 2.56%   |
| Kingston OM8PCP3512F-AI1 512GB         | 1         | 2.56%   |
| Intel SSDPEKKW512G7 512GB              | 1         | 2.56%   |
| Intel NVMe SSD Drive 512GB             | 1         | 2.56%   |
| Intel NVMe SSD Drive 256GB             | 1         | 2.56%   |
| Advantech SQF-S25M8-128G-AAG 128GB SSD | 1         | 2.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 5      | 55.56%  |
| Seagate | 3         | 4      | 33.33%  |
| Toshiba | 1         | 1      | 11.11%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 1         | 1      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |
| PNY                 | 1         | 1      | 20%     |
| Kingston            | 1         | 1      | 20%     |
| Advantech           | 1         | 1      | 20%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 16        | 23     | 47.06%  |
| HDD     | 9         | 10     | 26.47%  |
| SSD     | 5         | 5      | 14.71%  |
| MMC     | 3         | 3      | 8.82%   |
| Unknown | 1         | 1      | 2.94%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 16        | 22     | 45.71%  |
| SATA | 13        | 14     | 37.14%  |
| SAS  | 3         | 3      | 8.57%   |
| MMC  | 3         | 3      | 8.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 8         | 9      | 57.14%  |
| 0.51-1.0   | 5         | 5      | 35.71%  |
| 1.01-2.0   | 1         | 1      | 7.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 10        | 33.33%  |
| 251-500    | 8         | 26.67%  |
| 501-1000   | 7         | 23.33%  |
| 21-50      | 2         | 6.67%   |
| 51-100     | 2         | 6.67%   |
| 2001-3000  | 1         | 3.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 13        | 40.63%  |
| 21-50     | 8         | 25%     |
| 51-100    | 4         | 12.5%   |
| 251-500   | 3         | 9.38%   |
| 101-250   | 3         | 9.38%   |
| 1001-2000 | 1         | 3.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                     | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST9320325AS 320GB | 1         | 2      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 2      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 2      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1         | 2      | 100%    |

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
| Detected | 22        | 32     | 70.97%  |
| Works    | 8         | 8      | 25.81%  |
| Malfunc  | 1         | 2      | 3.23%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 16        | 43.24%  |
| AMD                          | 6         | 16.22%  |
| SK hynix                     | 4         | 10.81%  |
| SanDisk                      | 3         | 8.11%   |
| Samsung Electronics          | 3         | 8.11%   |
| Toshiba America Info Systems | 2         | 5.41%   |
| Silicon Motion               | 1         | 2.7%    |
| Phison Electronics           | 1         | 2.7%    |
| Kingston Technology Company  | 1         | 2.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 5         | 12.5%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                          | 2         | 5%      |
| SK hynix BC501 NVMe Solid State Drive                                         | 2         | 5%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 2         | 5%      |
| Intel SSD 600P Series                                                         | 2         | 5%      |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 2         | 5%      |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 2         | 5%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 2         | 5%      |
| SK hynix PC300 NVMe Solid State Drive 256GB                                   | 1         | 2.5%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                | 1         | 2.5%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                               | 1         | 2.5%    |
| SanDisk WD Blue SN550 NVMe SSD                                                | 1         | 2.5%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                     | 1         | 2.5%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                               | 1         | 2.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 1         | 2.5%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 1         | 2.5%    |
| Samsung NVMe SSD Controller 980                                               | 1         | 2.5%    |
| Phison PS5013 E13 NVMe Controller                                             | 1         | 2.5%    |
| Kingston Company Company Non-Volatile memory controller                       | 1         | 2.5%    |
| Intel SSD 660P Series                                                         | 1         | 2.5%    |
| Intel Comet Lake SATA AHCI Controller                                         | 1         | 2.5%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                             | 1         | 2.5%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]         | 1         | 2.5%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                 | 1         | 2.5%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                              | 1         | 2.5%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 1         | 2.5%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 1         | 2.5%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 1         | 2.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 1         | 2.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 20        | 52.63%  |
| NVMe | 16        | 42.11%  |
| RAID | 1         | 2.63%   |
| IDE  | 1         | 2.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 22        | 75.86%  |
| AMD    | 7         | 24.14%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-2640M CPU @ 2.80GHz             | 2         | 6.9%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 6.9%    |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 3.45%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 3.45%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 3.45%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 3.45%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 3.45%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 3.45%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 1         | 3.45%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 3.45%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 3.45%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 3.45%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 3.45%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 3.45%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 3.45%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 1         | 3.45%   |
| Intel Celeron CPU B830 @ 1.80GHz              | 1         | 3.45%   |
| Intel Celeron CPU 540 @ 1.86GHz               | 1         | 3.45%   |
| Intel Atom x5-E8000 CPU @ 1.04GHz             | 1         | 3.45%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 3.45%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 1         | 3.45%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 1         | 3.45%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 3.45%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 1         | 3.45%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 1         | 3.45%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 3.45%   |
| AMD E-350 Processor                           | 1         | 3.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 6         | 20.69%  |
| Intel Core i5           | 5         | 17.24%  |
| Intel Celeron           | 4         | 13.79%  |
| Other                   | 3         | 10.34%  |
| AMD Ryzen 7             | 3         | 10.34%  |
| AMD Ryzen 5             | 3         | 10.34%  |
| Intel Pentium Silver    | 1         | 3.45%   |
| Intel Pentium Dual-Core | 1         | 3.45%   |
| Intel Core i3           | 1         | 3.45%   |
| Intel Atom              | 1         | 3.45%   |
| AMD E                   | 1         | 3.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 13        | 44.83%  |
| 2      | 11        | 37.93%  |
| 8      | 2         | 6.9%    |
| 6      | 2         | 6.9%    |
| 1      | 1         | 3.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 29        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 21        | 72.41%  |
| 1      | 8         | 27.59%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 29        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 4         | 13.33%  |
| 0x806ec    | 3         | 10%     |
| 0x806c1    | 3         | 10%     |
| 0x206a7    | 3         | 10%     |
| 0x806ea    | 2         | 6.67%   |
| 0x906e9    | 1         | 3.33%   |
| 0x906c0    | 1         | 3.33%   |
| 0x706a8    | 1         | 3.33%   |
| 0x706a1    | 1         | 3.33%   |
| 0x506e3    | 1         | 3.33%   |
| 0x406e3    | 1         | 3.33%   |
| 0x40651    | 1         | 3.33%   |
| 0x1067a    | 1         | 3.33%   |
| 0x10661    | 1         | 3.33%   |
| 0x0a50000c | 1         | 3.33%   |
| 0x08608103 | 1         | 3.33%   |
| 0x08600106 | 1         | 3.33%   |
| 0x08108109 | 1         | 3.33%   |
| 0x08108102 | 1         | 3.33%   |
| 0x05000029 | 1         | 3.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 7         | 24.14%  |
| TigerLake     | 3         | 10.34%  |
| SandyBridge   | 3         | 10.34%  |
| Zen+          | 2         | 6.9%    |
| Skylake       | 2         | 6.9%    |
| Goldmont plus | 2         | 6.9%    |
| Unknown       | 2         | 6.9%    |
| Zen 3         | 1         | 3.45%   |
| Zen 2         | 1         | 3.45%   |
| Tremont       | 1         | 3.45%   |
| Silvermont    | 1         | 3.45%   |
| Penryn        | 1         | 3.45%   |
| Haswell       | 1         | 3.45%   |
| Core          | 1         | 3.45%   |
| Bobcat        | 1         | 3.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 21        | 60%     |
| AMD    | 9         | 25.71%  |
| Nvidia | 5         | 14.29%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 5.56%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 5.56%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 5.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 5.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 5.56%   |
| AMD Lucienne                                                                             | 2         | 5.56%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 2.78%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 2.78%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 2.78%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 2.78%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 2.78%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 2.78%   |
| Intel UHD Graphics 620                                                                   | 1         | 2.78%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 1         | 2.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 2.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 2.78%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 2.78%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 2.78%   |
| Intel HD Graphics 630                                                                    | 1         | 2.78%   |
| Intel HD Graphics 620                                                                    | 1         | 2.78%   |
| Intel HD Graphics 530                                                                    | 1         | 2.78%   |
| Intel HD Graphics 520                                                                    | 1         | 2.78%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 2.78%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 1         | 2.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.78%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 2.78%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 2.78%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 2.78%   |
| AMD Renoir                                                                               | 1         | 2.78%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 1         | 2.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 17        | 58.62%  |
| 1 x AMD        | 6         | 20.69%  |
| Intel + Nvidia | 3         | 10.34%  |
| AMD + Nvidia   | 2         | 6.9%    |
| Intel + AMD    | 1         | 3.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 25        | 86.21%  |
| Proprietary | 4         | 13.79%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 19        | 65.52%  |
| 1.01-2.0   | 4         | 13.79%  |
| 0.01-0.5   | 3         | 10.34%  |
| 5.01-6.0   | 1         | 3.45%   |
| 3.01-4.0   | 1         | 3.45%   |
| 0.51-1.0   | 1         | 3.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 8         | 23.53%  |
| AU Optronics            | 6         | 17.65%  |
| BOE                     | 5         | 14.71%  |
| Samsung Electronics     | 4         | 11.76%  |
| LG Display              | 2         | 5.88%   |
| Ancor Communications    | 2         | 5.88%   |
| Toshiba                 | 1         | 2.94%   |
| Philips                 | 1         | 2.94%   |
| PANDA                   | 1         | 2.94%   |
| Lenovo                  | 1         | 2.94%   |
| CSO                     | 1         | 2.94%   |
| Chi Mei Optoelectronics | 1         | 2.94%   |
| Acer                    | 1         | 2.94%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Toshiba Internal LCD TOS5091 1366x768 344x193mm 15.5-inch                | 1         | 2.86%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 1         | 2.86%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch     | 1         | 2.86%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 1         | 2.86%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch        | 1         | 2.86%   |
| Samsung Electronics C27F591 SAM0D36 1920x1080 600x340mm 27.2-inch        | 1         | 2.86%   |
| Philips 273PLPH PHL08A8 1920x1080 598x336mm 27.0-inch                    | 1         | 2.86%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch                  | 1         | 2.86%   |
| LG Display LCD Monitor LGD06FB 1920x1080 309x174mm 14.0-inch             | 1         | 2.86%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch             | 1         | 2.86%   |
| Lenovo D22-10 LEN65E4 1920x1080 476x268mm 21.5-inch                      | 1         | 2.86%   |
| CSO LCD Monitor CSO1500 3840x2160 344x194mm 15.5-inch                    | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN15D3 1920x1080 344x193mm 15.5-inch         | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN15CB 1920x1080 344x193mm 15.5-inch         | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN15C5 1366x768 344x193mm 15.5-inch          | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN1480 1366x768 309x174mm 14.0-inch          | 1         | 2.86%   |
| Chi Mei Optoelectronics LCD Monitor CMO1113 1366x768 256x144mm 11.6-inch | 1         | 2.86%   |
| BOE NV116WHM-T16 BOE0956 1366x768 256x144mm 11.6-inch                    | 1         | 2.86%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 1         | 2.86%   |
| BOE LCD Monitor BOE06CB 1920x1080 344x194mm 15.5-inch                    | 1         | 2.86%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 1         | 2.86%   |
| BOE LCD Monitor BOE0653 1920x1080 309x173mm 13.9-inch                    | 1         | 2.86%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch           | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch            | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch           | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO282B 3840x2160 293x165mm 13.2-inch           | 1         | 2.86%   |
| Ancor Communications C624B ACI24A9 1920x1200 518x324mm 24.1-inch         | 1         | 2.86%   |
| Ancor Communications ASUS VS229 ACI22D3 1920x1080 475x267mm 21.5-inch    | 1         | 2.86%   |
| Acer K242HYL ACR064A 1920x1080 527x296mm 23.8-inch                       | 1         | 2.86%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 15        | 46.88%  |
| 1366x768 (WXGA)   | 12        | 37.5%   |
| 3840x2160 (4K)    | 2         | 6.25%   |
| 2256x1504         | 1         | 3.13%   |
| 1920x1200 (WUXGA) | 1         | 3.13%   |
| 1280x800 (WXGA)   | 1         | 3.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 18        | 52.94%  |
| 13     | 5         | 14.71%  |
| 14     | 3         | 8.82%   |
| 27     | 2         | 5.88%   |
| 21     | 2         | 5.88%   |
| 11     | 2         | 5.88%   |
| 24     | 1         | 2.94%   |
| 23     | 1         | 2.94%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 22        | 64.71%  |
| 201-300     | 5         | 14.71%  |
| 501-600     | 4         | 11.76%  |
| 401-500     | 2         | 5.88%   |
| 351-400     | 1         | 2.94%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 27        | 90%     |
| 16/10 | 2         | 6.67%   |
| 3/2   | 1         | 3.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 18        | 52.94%  |
| 81-90          | 6         | 17.65%  |
| 71-80          | 2         | 5.88%   |
| 51-60          | 2         | 5.88%   |
| 301-350        | 2         | 5.88%   |
| 201-250        | 2         | 5.88%   |
| 251-300        | 1         | 2.94%   |
| 151-200        | 1         | 2.94%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 13        | 40.63%  |
| 101-120       | 10        | 31.25%  |
| 51-100        | 5         | 15.63%  |
| More than 240 | 2         | 6.25%   |
| 161-240       | 2         | 6.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 24        | 82.76%  |
| 2     | 4         | 13.79%  |
| 3     | 1         | 3.45%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 14        | 33.33%  |
| Realtek Semiconductor    | 11        | 26.19%  |
| Qualcomm Atheros         | 8         | 19.05%  |
| MediaTek                 | 2         | 4.76%   |
| Marvell Technology Group | 2         | 4.76%   |
| TP-Link                  | 1         | 2.38%   |
| T & A Mobile Phones      | 1         | 2.38%   |
| Dell                     | 1         | 2.38%   |
| Broadcom                 | 1         | 2.38%   |
| ASIX Electronics         | 1         | 2.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 14%     |
| Intel Wi-Fi 6 AX200                                               | 4         | 8%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 6%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 4%      |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 4%      |
| Intel Wi-Fi 6 AX201                                               | 2         | 4%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 4%      |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 2%      |
| T & A Mobile Phones A509DL                                        | 1         | 2%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 2%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 2%      |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 2%      |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 2%      |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 2%      |
| Realtek 802.11n WLAN Adapter                                      | 1         | 2%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 2%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 2%      |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 2%      |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 2%      |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1         | 2%      |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 2%      |
| Intel Wireless 8265 / 8275                                        | 1         | 2%      |
| Intel Wireless 8260                                               | 1         | 2%      |
| Intel Wireless 7265                                               | 1         | 2%      |
| Intel Wireless 3165                                               | 1         | 2%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 2%      |
| Intel Wi-Fi 6 AX201 160MHz                                        | 1         | 2%      |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 2%      |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2%      |
| Intel Ethernet Connection (13) I219-V                             | 1         | 2%      |
| Intel Centrino Ultimate-N 6300                                    | 1         | 2%      |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                     | 1         | 2%      |
| Dell DW5550                                                       | 1         | 2%      |
| Broadcom BCM4311 802.11b/g WLAN                                   | 1         | 2%      |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 2%      |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 14        | 48.28%  |
| Qualcomm Atheros      | 7         | 24.14%  |
| Realtek Semiconductor | 5         | 17.24%  |
| MediaTek              | 2         | 6.9%    |
| Broadcom              | 1         | 3.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 4         | 13.79%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 3         | 10.34%  |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 6.9%    |
| Intel Wi-Fi 6 AX201                                            | 2         | 6.9%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 3.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 3.45%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 3.45%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 3.45%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 3.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 3.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 3.45%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 1         | 3.45%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 3.45%   |
| Intel Wireless 8265 / 8275                                     | 1         | 3.45%   |
| Intel Wireless 8260                                            | 1         | 3.45%   |
| Intel Wireless 7265                                            | 1         | 3.45%   |
| Intel Wireless 3165                                            | 1         | 3.45%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 3.45%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 1         | 3.45%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 3.45%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                  | 1         | 3.45%   |
| Broadcom BCM4311 802.11b/g WLAN                                | 1         | 3.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 8         | 42.11%  |
| Intel                    | 5         | 26.32%  |
| Qualcomm Atheros         | 2         | 10.53%  |
| Marvell Technology Group | 2         | 10.53%  |
| TP-Link                  | 1         | 5.26%   |
| ASIX Electronics         | 1         | 5.26%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 36.84%  |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 10.53%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 10.53%  |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 5.26%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 5.26%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 5.26%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 5.26%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 5.26%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 5.26%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 5.26%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 5.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 29        | 58%     |
| Ethernet | 19        | 38%     |
| Modem    | 1         | 2%      |
| Unknown  | 1         | 2%      |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 23        | 79.31%  |
| Ethernet | 6         | 20.69%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 17        | 58.62%  |
| 1     | 11        | 37.93%  |
| 0     | 1         | 3.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 21        | 72.41%  |
| Yes  | 8         | 27.59%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 12        | 48%     |
| Qualcomm Atheros Communications | 3         | 12%     |
| Realtek Semiconductor           | 2         | 8%      |
| Lite-On Technology              | 2         | 8%      |
| Toshiba                         | 1         | 4%      |
| MediaTek                        | 1         | 4%      |
| IMC Networks                    | 1         | 4%      |
| Foxconn / Hon Hai               | 1         | 4%      |
| Dell                            | 1         | 4%      |
| Broadcom                        | 1         | 4%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface         | 4         | 16%     |
| Intel AX200 Bluetooth                      | 4         | 16%     |
| Intel AX201 Bluetooth                      | 3         | 12%     |
| Qualcomm Atheros  Bluetooth Device         | 2         | 8%      |
| Toshiba RT Bluetooth Radio                 | 1         | 4%      |
| Realtek RTL8821A Bluetooth                 | 1         | 4%      |
| Realtek  Bluetooth 4.2 Adapter             | 1         | 4%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0      | 1         | 4%      |
| MediaTek Wireless_Device                   | 1         | 4%      |
| Lite-On Wireless_Device                    | 1         | 4%      |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth | 1         | 4%      |
| Intel AX210 Bluetooth                      | 1         | 4%      |
| IMC Networks Bluetooth Radio               | 1         | 4%      |
| Foxconn / Hon Hai Bluetooth Device         | 1         | 4%      |
| Dell DW375 Bluetooth Module                | 1         | 4%      |
| Broadcom Bluetooth 2.1 Device              | 1         | 4%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 22        | 62.86%  |
| AMD                 | 8         | 22.86%  |
| Nvidia              | 3         | 8.57%   |
| Samsung Electronics | 1         | 2.86%   |
| Conexant Systems    | 1         | 2.86%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 14.63%  |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 7.32%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 7.32%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 4.88%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 4.88%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 4.88%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 4.88%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 4.88%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 4.88%   |
| Samsung Electronics USBC Headset                                                                  | 1         | 2.44%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 2.44%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 2.44%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 2.44%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 2.44%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 2.44%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 2.44%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.44%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 2.44%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 2.44%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 2.44%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1         | 2.44%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 2.44%   |
| Conexant Systems Hi-Res Audio                                                                     | 1         | 2.44%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 2.44%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 2.44%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 2.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 41.18%  |
| SK hynix            | 3         | 17.65%  |
| Micron Technology   | 2         | 11.76%  |
| Unknown             | 1         | 5.88%   |
| Team                | 1         | 5.88%   |
| G.Skill             | 1         | 5.88%   |
| Crucial             | 1         | 5.88%   |
| A-DATA Technology   | 1         | 5.88%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 5.88%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 1         | 5.88%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 5.88%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 1GB Row Of Chips LPDDR4 4267MT/s   | 1         | 5.88%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 5.88%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 1         | 5.88%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 5.88%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 5.88%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 5.88%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 5.88%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 5.88%   |
| Samsung RAM K4E8E324EB-EGCF 2GB SODIMM LPDDR3 1867MT/s           | 1         | 5.88%   |
| Micron RAM 8HTF12864HDY-667E1 1GB SODIMM DDR2 667MT/s            | 1         | 5.88%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 1         | 5.88%   |
| G.Skill RAM F4-3200C22-16GRS 16GB SODIMM DDR4 3200MT/s           | 1         | 5.88%   |
| Crucial RAM CT16G4SFD8213.C16FBD 16GB SODIMM DDR4 2133MT/s       | 1         | 5.88%   |
| A-DATA RAM Module 8192MB SODIMM DDR4 2133MT/s                    | 1         | 5.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 7         | 46.67%  |
| LPDDR3 | 3         | 20%     |
| DDR3   | 2         | 13.33%  |
| LPDDR4 | 1         | 6.67%   |
| DDR2   | 1         | 6.67%   |
| DDR    | 1         | 6.67%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 11        | 78.57%  |
| Row Of Chips | 3         | 21.43%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 16384 | 4         | 28.57%  |
| 8192  | 4         | 28.57%  |
| 4096  | 3         | 21.43%  |
| 32768 | 1         | 7.14%   |
| 2048  | 1         | 7.14%   |
| 1024  | 1         | 7.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 4         | 26.67%  |
| 2133    | 4         | 26.67%  |
| 4267    | 1         | 6.67%   |
| 2667    | 1         | 6.67%   |
| 1867    | 1         | 6.67%   |
| 1600    | 1         | 6.67%   |
| 1333    | 1         | 6.67%   |
| 667     | 1         | 6.67%   |
| Unknown | 1         | 6.67%   |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 4         | 16%     |
| Quanta                                 | 4         | 16%     |
| Sunplus Innovation Technology          | 3         | 12%     |
| Microdia                               | 3         | 12%     |
| IMC Networks                           | 2         | 8%      |
| Chicony Electronics                    | 2         | 8%      |
| Cheng Uei Precision Industry (Foxlink) | 2         | 8%      |
| Z-Star Microelectronics                | 1         | 4%      |
| Syntek                                 | 1         | 4%      |
| Logitech                               | 1         | 4%      |
| Importek                               | 1         | 4%      |
| Acer                                   | 1         | 4%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                                    | 2         | 8%      |
| Quanta HD User Facing                                           | 2         | 8%      |
| Microdia Integrated_Webcam_HD                                   | 2         | 8%      |
| Z-Star Webcam                                                   | 1         | 4%      |
| Syntek Integrated Camera                                        | 1         | 4%      |
| Sunplus Laptop_Integrated_Webcam_HD                             | 1         | 4%      |
| Realtek Laptop Camera                                           | 1         | 4%      |
| Realtek Integrated Webcam_HD                                    | 1         | 4%      |
| Realtek Integrated Webcam                                       | 1         | 4%      |
| Realtek HD WebCam                                               | 1         | 4%      |
| Quanta VGA WebCam                                               | 1         | 4%      |
| Quanta USB2.0 HD UVC WebCam                                     | 1         | 4%      |
| Microdia USB 2.0 Camera                                         | 1         | 4%      |
| Logitech Webcam C270                                            | 1         | 4%      |
| Importek TOSHIBA Web Camera - HD                                | 1         | 4%      |
| IMC Networks USB2.0 VGA UVC WebCam                              | 1         | 4%      |
| IMC Networks Integrated Camera                                  | 1         | 4%      |
| Chicony Sony Visual Communication Camera                        | 1         | 4%      |
| Chicony EasyCamera                                              | 1         | 4%      |
| Cheng Uei Precision Industry (Foxlink) Webcam                   | 1         | 4%      |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 4%      |
| Acer Lenovo EasyCamera                                          | 1         | 4%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 2         | 40%     |
| Synaptics                  | 1         | 20%     |
| Shenzhen Goodix Technology | 1         | 20%     |
| AuthenTec                  | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 20%     |
| Validity Sensors VFS Fingerprint sensor           | 1         | 20%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 20%     |
| Shenzhen Goodix  FingerPrint Device               | 1         | 20%     |
| AuthenTec Fingerprint Sensor                      | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 50%     |
| O2 Micro    | 1         | 25%     |
| Alcor Micro | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader           | 1         | 25%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 25%     |
| Broadcom 5880                                  | 1         | 25%     |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 18        | 62.07%  |
| 1     | 6         | 20.69%  |
| 2     | 5         | 17.24%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 5         | 27.78%  |
| Net/wireless          | 4         | 22.22%  |
| Chipcard              | 4         | 22.22%  |
| Multimedia controller | 3         | 16.67%  |
| Unassigned class      | 1         | 5.56%   |
| Storage               | 1         | 5.56%   |

