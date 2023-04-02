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

Total: 47

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [db0f4c6df3](https://linux-hardware.org/?probe=db0f4c6df3) | Mar 16, 2023 |
| Dell          | Inspiron 7460               | [141874b125](https://linux-hardware.org/?probe=141874b125) | Jan 08, 2023 |
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
| 5.15.50-216.current | 4         | 11.76%  |
| 5.13.1-187.current  | 4         | 11.76%  |
| 5.15.32-213.current | 3         | 8.82%   |
| 5.14.21-210.current | 3         | 8.82%   |
| 6.0.11-225.current  | 2         | 5.88%   |
| 5.15.77-219.current | 2         | 5.88%   |
| 5.14.16-205.current | 2         | 5.88%   |
| 5.13.6-190.current  | 2         | 5.88%   |
| 5.13.12-193.current | 2         | 5.88%   |
| 6.1.5-229.current   | 1         | 2.94%   |
| 6.1.2-228.current   | 1         | 2.94%   |
| 5.15.61-217.current | 1         | 2.94%   |
| 5.15.37-214.current | 1         | 2.94%   |
| 5.15.26-211.current | 1         | 2.94%   |
| 5.14.7-198.current  | 1         | 2.94%   |
| 5.14.16-204.current | 1         | 2.94%   |
| 5.14.15-203.current | 1         | 2.94%   |
| 5.14.12-201.current | 1         | 2.94%   |
| 5.13.15-194.current | 1         | 2.94%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.50 | 4         | 11.76%  |
| 5.13.1  | 4         | 11.76%  |
| 5.15.32 | 3         | 8.82%   |
| 5.14.21 | 3         | 8.82%   |
| 5.14.16 | 3         | 8.82%   |
| 6.0.11  | 2         | 5.88%   |
| 5.15.77 | 2         | 5.88%   |
| 5.13.6  | 2         | 5.88%   |
| 5.13.12 | 2         | 5.88%   |
| 6.1.5   | 1         | 2.94%   |
| 6.1.2   | 1         | 2.94%   |
| 5.15.61 | 1         | 2.94%   |
| 5.15.37 | 1         | 2.94%   |
| 5.15.26 | 1         | 2.94%   |
| 5.14.7  | 1         | 2.94%   |
| 5.14.15 | 1         | 2.94%   |
| 5.14.12 | 1         | 2.94%   |
| 5.13.15 | 1         | 2.94%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 12        | 35.29%  |
| 5.14    | 9         | 26.47%  |
| 5.13    | 9         | 26.47%  |
| 6.1     | 2         | 5.88%   |
| 6.0     | 2         | 5.88%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 31        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Budgie  | 15        | 46.88%  |
| MATE    | 5         | 15.63%  |
| Unknown | 4         | 12.5%   |
| KDE5    | 3         | 9.38%   |
| KDE     | 3         | 9.38%   |
| GNOME   | 2         | 6.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 31        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 23        | 71.88%  |
| LightDM | 6         | 18.75%  |
| SDDM    | 2         | 6.25%   |
| GDM     | 1         | 3.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 20        | 64.52%  |
| de_DE | 4         | 12.9%   |
| en_GB | 3         | 9.68%   |
| pt_BR | 1         | 3.23%   |
| fr_FR | 1         | 3.23%   |
| es_ES | 1         | 3.23%   |
| en_IN | 1         | 3.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 22        | 66.67%  |
| BIOS | 11        | 33.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 30        | 96.77%  |
| Overlay | 1         | 3.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 19        | 61.29%  |
| GPT     | 10        | 32.26%  |
| MBR     | 2         | 6.45%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 30        | 96.77%  |
| Yes       | 1         | 3.23%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 26        | 83.87%  |
| Yes       | 5         | 16.13%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 9         | 29.03%  |
| Lenovo              | 6         | 19.35%  |
| Acer                | 3         | 9.68%   |
| Toshiba             | 2         | 6.45%   |
| Hewlett-Packard     | 2         | 6.45%   |
| Google              | 2         | 6.45%   |
| Sony                | 1         | 3.23%   |
| Samsung Electronics | 1         | 3.23%   |
| MSI                 | 1         | 3.23%   |
| GPU Company         | 1         | 3.23%   |
| Framework           | 1         | 3.23%   |
| AZW                 | 1         | 3.23%   |
| ASUSTek Computer    | 1         | 3.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Toshiba TECRA R840                     | 1         | 3.23%   |
| Toshiba Satellite L855                 | 1         | 3.23%   |
| Sony VPCYB15AB                         | 1         | 3.23%   |
| Samsung R430/P430/R480                 | 1         | 3.23%   |
| MSI Modern 14 B5M                      | 1         | 3.23%   |
| Lenovo Z50-70 20354                    | 1         | 3.23%   |
| Lenovo ThinkPad T15 Gen 2i 20W4CTO1WW  | 1         | 3.23%   |
| Lenovo ThinkPad T14 Gen 1 20S00013FR   | 1         | 3.23%   |
| Lenovo IdeaPad S340-15API 81NC         | 1         | 3.23%   |
| Lenovo IdeaPad 5 15ALC05 82LN          | 1         | 3.23%   |
| Lenovo IdeaPad 320-15ISK 80XH          | 1         | 3.23%   |
| HP ProBook 450 G5                      | 1         | 3.23%   |
| HP OMEN Laptop 15-en0xxx               | 1         | 3.23%   |
| GPU Company GWTC116-2                  | 1         | 3.23%   |
| Google Edgar                           | 1         | 3.23%   |
| Google Delbin                          | 1         | 3.23%   |
| Framework Laptop                       | 1         | 3.23%   |
| Dell XPS 13 9380                       | 1         | 3.23%   |
| Dell XPS 13 7390                       | 1         | 3.23%   |
| Dell Vostro 15-3568                    | 1         | 3.23%   |
| Dell Latitude E6220                    | 1         | 3.23%   |
| Dell Latitude E5470                    | 1         | 3.23%   |
| Dell Latitude 5580                     | 1         | 3.23%   |
| Dell Inspiron 7460                     | 1         | 3.23%   |
| Dell Inspiron 1525                     | 1         | 3.23%   |
| Dell Inspiron 15-3573                  | 1         | 3.23%   |
| AZW SEi                                | 1         | 3.23%   |
| ASUS VivoBook_ASUSLaptop X509DA_M509DA | 1         | 3.23%   |
| Acer Swift SF114-34                    | 1         | 3.23%   |
| Acer Nitro AN515-45                    | 1         | 3.23%   |
| Acer Aspire A315-54                    | 1         | 3.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo IdeaPad        | 3         | 9.68%   |
| Dell Latitude         | 3         | 9.68%   |
| Dell Inspiron         | 3         | 9.68%   |
| Lenovo ThinkPad       | 2         | 6.45%   |
| Dell XPS              | 2         | 6.45%   |
| Toshiba TECRA         | 1         | 3.23%   |
| Toshiba Satellite     | 1         | 3.23%   |
| Sony VPCYB15AB        | 1         | 3.23%   |
| Samsung R430          | 1         | 3.23%   |
| MSI Modern            | 1         | 3.23%   |
| Lenovo Z50-70         | 1         | 3.23%   |
| HP ProBook            | 1         | 3.23%   |
| HP OMEN               | 1         | 3.23%   |
| GPU Company GWTC116-2 | 1         | 3.23%   |
| Google Edgar          | 1         | 3.23%   |
| Google Delbin         | 1         | 3.23%   |
| Framework Laptop      | 1         | 3.23%   |
| Dell Vostro           | 1         | 3.23%   |
| AZW SEi               | 1         | 3.23%   |
| ASUS VivoBook         | 1         | 3.23%   |
| Acer Swift            | 1         | 3.23%   |
| Acer Nitro            | 1         | 3.23%   |
| Acer Aspire           | 1         | 3.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 7         | 22.58%  |
| 2019 | 5         | 16.13%  |
| 2020 | 4         | 12.9%   |
| 2017 | 4         | 12.9%   |
| 2018 | 2         | 6.45%   |
| 2016 | 2         | 6.45%   |
| 2011 | 2         | 6.45%   |
| 2010 | 2         | 6.45%   |
| 2014 | 1         | 3.23%   |
| 2012 | 1         | 3.23%   |
| 2008 | 1         | 3.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 31        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 31        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 29        | 93.55%  |
| Yes  | 2         | 6.45%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 7         | 22.58%  |
| 3.01-4.0   | 6         | 19.35%  |
| 32.01-64.0 | 5         | 16.13%  |
| 16.01-24.0 | 5         | 16.13%  |
| 8.01-16.0  | 5         | 16.13%  |
| 1.01-2.0   | 2         | 6.45%   |
| 2.01-3.0   | 1         | 3.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 14        | 42.42%  |
| 1.01-2.0  | 9         | 27.27%  |
| 3.01-4.0  | 4         | 12.12%  |
| 4.01-8.0  | 3         | 9.09%   |
| 0.51-1.0  | 2         | 6.06%   |
| 8.01-16.0 | 1         | 3.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 25        | 80.65%  |
| 2      | 6         | 19.35%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 24        | 77.42%  |
| Yes       | 7         | 22.58%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 21        | 67.74%  |
| No        | 10        | 32.26%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 31        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 27        | 87.1%   |
| No        | 4         | 12.9%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 7         | 22.58%  |
| India       | 3         | 9.68%   |
| Germany     | 3         | 9.68%   |
| UK          | 2         | 6.45%   |
| Netherlands | 2         | 6.45%   |
| Brazil      | 2         | 6.45%   |
| Vietnam     | 1         | 3.23%   |
| Ukraine     | 1         | 3.23%   |
| Switzerland | 1         | 3.23%   |
| Poland      | 1         | 3.23%   |
| Norway      | 1         | 3.23%   |
| Nepal       | 1         | 3.23%   |
| Mexico      | 1         | 3.23%   |
| France      | 1         | 3.23%   |
| Czechia     | 1         | 3.23%   |
| Belgium     | 1         | 3.23%   |
| Australia   | 1         | 3.23%   |
| Argentina   | 1         | 3.23%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Yverdon-les-Bains        | 1         | 3.03%   |
| Wendell                  | 1         | 3.03%   |
| Vineland                 | 1         | 3.03%   |
| Vasco da Gama            | 1         | 3.03%   |
| Stare Babice             | 1         | 3.03%   |
| San Justo                | 1         | 3.03%   |
| Saint-Just-Saint-Rambert | 1         | 3.03%   |
| Red Oak                  | 1         | 3.03%   |
| Pomeroy                  | 1         | 3.03%   |
| Oslo                     | 1         | 3.03%   |
| Mohali                   | 1         | 3.03%   |
| Milwaukee                | 1         | 3.03%   |
| Melbourne                | 1         | 3.03%   |
| Lviv                     | 1         | 3.03%   |
| Luckenwalde              | 1         | 3.03%   |
| Lübeck                  | 1         | 3.03%   |
| Linter                   | 1         | 3.03%   |
| León                    | 1         | 3.03%   |
| Kathmandu                | 1         | 3.03%   |
| Jackson                  | 1         | 3.03%   |
| Ilford                   | 1         | 3.03%   |
| Hanoi                    | 1         | 3.03%   |
| Guanajuato City          | 1         | 3.03%   |
| Groningen                | 1         | 3.03%   |
| Greenwich                | 1         | 3.03%   |
| Goiânia                 | 1         | 3.03%   |
| Essen                    | 1         | 3.03%   |
| Dubenec                  | 1         | 3.03%   |
| Coimbatore               | 1         | 3.03%   |
| Chelmsford               | 1         | 3.03%   |
| Belo Horizonte           | 1         | 3.03%   |
| Anacortes                | 1         | 3.03%   |
| Amsterdam                | 1         | 3.03%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 6         | 8      | 15.38%  |
| WDC                 | 5         | 5      | 12.82%  |
| SK hynix            | 5         | 5      | 12.82%  |
| Samsung Electronics | 4         | 5      | 10.26%  |
| Unknown             | 3         | 3      | 7.69%   |
| Seagate             | 3         | 4      | 7.69%   |
| Intel               | 3         | 4      | 7.69%   |
| Toshiba             | 2         | 2      | 5.13%   |
| Kingston            | 2         | 2      | 5.13%   |
| Silicon Motion      | 1         | 1      | 2.56%   |
| SABRENT             | 1         | 1      | 2.56%   |
| PNY                 | 1         | 1      | 2.56%   |
| Phison              | 1         | 1      | 2.56%   |
| KIOXIA              | 1         | 1      | 2.56%   |
| Advantech           | 1         | 1      | 2.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| SK hynix NVMe SSD Drive 128GB                  | 2         | 4.88%   |
| SanDisk NVMe SSD Drive 256GB                   | 2         | 4.88%   |
| WDC WD3200BEVT-75ZCT2 320GB                    | 1         | 2.44%   |
| WDC WD2500BEVT-22ZCT0 250GB                    | 1         | 2.44%   |
| WDC WD10SPZX-24Z10T0 1TB                       | 1         | 2.44%   |
| WDC WD10SPZX-24Z10 1TB                         | 1         | 2.44%   |
| WDC WD10JPCX-24UE4T0 1TB                       | 1         | 2.44%   |
| Unknown USB DISK 3.2 250GB                     | 1         | 2.44%   |
| Unknown MMC Card  64GB                         | 1         | 2.44%   |
| Unknown MMC Card  128GB                        | 1         | 2.44%   |
| Toshiba MQ01ABF050 500GB                       | 1         | 2.44%   |
| Toshiba KXG60ZNV512G NVMe 512GB                | 1         | 2.44%   |
| SK hynix SC311 SATA 256GB SSD                  | 1         | 2.44%   |
| SK hynix NVMe SSD Drive 500GB                  | 1         | 2.44%   |
| SK hynix NVMe SSD Drive 256GB                  | 1         | 2.44%   |
| Silicon Motion NVMe SSD Drive 512GB            | 1         | 2.44%   |
| Seagate ST9320325AS 320GB                      | 1         | 2.44%   |
| Seagate ST1000LM049-2GH172 1TB                 | 1         | 2.44%   |
| Seagate ST1000LM035-1RK172 1TB                 | 1         | 2.44%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1TB | 1         | 2.44%   |
| SanDisk SDSSDH32000G 2TB                       | 1         | 2.44%   |
| SanDisk NVMe SSD Drive 1TB                     | 1         | 2.44%   |
| SanDisk Extreme Pro 1TB                        | 1         | 2.44%   |
| SanDisk DF4032  32GB                           | 1         | 2.44%   |
| Samsung SSD 850 EVO 250GB                      | 1         | 2.44%   |
| Samsung NVMe SSD Drive 512GB                   | 1         | 2.44%   |
| Samsung NVMe SSD Drive 2TB                     | 1         | 2.44%   |
| Samsung MZVL22T0HBLB-00BL7 2TB                 | 1         | 2.44%   |
| Samsung MZALQ512HBLU-00BL2 512GB               | 1         | 2.44%   |
| SABRENT Disk 160GB                             | 1         | 2.44%   |
| PNY CS900 240GB SSD                            | 1         | 2.44%   |
| Phison NVMe SSD Drive 512GB                    | 1         | 2.44%   |
| KIOXIA KXG60ZNV512G NVMe 512GB                 | 1         | 2.44%   |
| Kingston SA400S37240G 240GB SSD                | 1         | 2.44%   |
| Kingston OM8PCP3512F-AI1 512GB                 | 1         | 2.44%   |
| Intel SSDPEKKW512G7 512GB                      | 1         | 2.44%   |
| Intel NVMe SSD Drive 512GB                     | 1         | 2.44%   |
| Intel NVMe SSD Drive 256GB                     | 1         | 2.44%   |
| Advantech SQF-S25M8-128G-AAG 128GB SSD         | 1         | 2.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 5      | 50%     |
| Seagate | 3         | 4      | 30%     |
| Toshiba | 1         | 1      | 10%     |
| SABRENT | 1         | 1      | 10%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SK hynix            | 1         | 1      | 16.67%  |
| SanDisk             | 1         | 1      | 16.67%  |
| Samsung Electronics | 1         | 1      | 16.67%  |
| PNY                 | 1         | 1      | 16.67%  |
| Kingston            | 1         | 1      | 16.67%  |
| Advantech           | 1         | 1      | 16.67%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 17        | 23     | 45.95%  |
| HDD     | 10        | 11     | 27.03%  |
| SSD     | 6         | 6      | 16.22%  |
| MMC     | 3         | 3      | 8.11%   |
| Unknown | 1         | 1      | 2.7%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 17        | 23     | 45.95%  |
| SATA | 14        | 15     | 37.84%  |
| SAS  | 3         | 3      | 8.11%   |
| MMC  | 3         | 3      | 8.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 9         | 11     | 60%     |
| 0.51-1.0   | 5         | 5      | 33.33%  |
| 1.01-2.0   | 1         | 1      | 6.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 11        | 34.38%  |
| 251-500    | 8         | 25%     |
| 501-1000   | 8         | 25%     |
| 21-50      | 2         | 6.25%   |
| 51-100     | 2         | 6.25%   |
| 2001-3000  | 1         | 3.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 13        | 38.24%  |
| 21-50     | 8         | 23.53%  |
| 51-100    | 5         | 14.71%  |
| 251-500   | 4         | 11.76%  |
| 101-250   | 3         | 8.82%   |
| 1001-2000 | 1         | 2.94%   |

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
| Detected | 22        | 32     | 66.67%  |
| Works    | 10        | 10     | 30.3%   |
| Malfunc  | 1         | 2      | 3.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 17        | 43.59%  |
| AMD                          | 6         | 15.38%  |
| SK hynix                     | 4         | 10.26%  |
| SanDisk                      | 4         | 10.26%  |
| Samsung Electronics          | 3         | 7.69%   |
| Toshiba America Info Systems | 2         | 5.13%   |
| Silicon Motion               | 1         | 2.56%   |
| Phison Electronics           | 1         | 2.56%   |
| Kingston Technology Company  | 1         | 2.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 5         | 11.9%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 3         | 7.14%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                          | 2         | 4.76%   |
| SK hynix BC501 NVMe Solid State Drive                                         | 2         | 4.76%   |
| Intel SSD 600P Series                                                         | 2         | 4.76%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 2         | 4.76%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 2         | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 2         | 4.76%   |
| SK hynix PC300 NVMe Solid State Drive 256GB                                   | 1         | 2.38%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                | 1         | 2.38%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                               | 1         | 2.38%   |
| SanDisk WD Blue SN550 NVMe SSD                                                | 1         | 2.38%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                     | 1         | 2.38%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                    | 1         | 2.38%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                               | 1         | 2.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 1         | 2.38%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 1         | 2.38%   |
| Samsung NVMe SSD Controller 980                                               | 1         | 2.38%   |
| Phison PS5013 E13 NVMe Controller                                             | 1         | 2.38%   |
| Kingston Company Company Non-Volatile memory controller                       | 1         | 2.38%   |
| Intel SSD 660P Series                                                         | 1         | 2.38%   |
| Intel Comet Lake SATA AHCI Controller                                         | 1         | 2.38%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                             | 1         | 2.38%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]         | 1         | 2.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                 | 1         | 2.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                              | 1         | 2.38%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 1         | 2.38%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 1         | 2.38%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 1         | 2.38%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 1         | 2.38%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 21        | 52.5%   |
| NVMe | 17        | 42.5%   |
| RAID | 1         | 2.5%    |
| IDE  | 1         | 2.5%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 24        | 77.42%  |
| AMD    | 7         | 22.58%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-2640M CPU @ 2.80GHz             | 2         | 6.45%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 6.45%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 6.45%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 3.23%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 3.23%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 3.23%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 3.23%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 3.23%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 3.23%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 1         | 3.23%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 3.23%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 3.23%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 3.23%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 3.23%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 3.23%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 3.23%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 1         | 3.23%   |
| Intel Celeron CPU B830 @ 1.80GHz              | 1         | 3.23%   |
| Intel Celeron CPU 540 @ 1.86GHz               | 1         | 3.23%   |
| Intel Atom x5-E8000 CPU @ 1.04GHz             | 1         | 3.23%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 3.23%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 1         | 3.23%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 1         | 3.23%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 3.23%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 1         | 3.23%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 1         | 3.23%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 3.23%   |
| AMD E-350 Processor                           | 1         | 3.23%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 8         | 25.81%  |
| Intel Core i5           | 5         | 16.13%  |
| Intel Celeron           | 4         | 12.9%   |
| Other                   | 3         | 9.68%   |
| AMD Ryzen 7             | 3         | 9.68%   |
| AMD Ryzen 5             | 3         | 9.68%   |
| Intel Pentium Silver    | 1         | 3.23%   |
| Intel Pentium Dual-Core | 1         | 3.23%   |
| Intel Core i3           | 1         | 3.23%   |
| Intel Atom              | 1         | 3.23%   |
| AMD E                   | 1         | 3.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 14        | 45.16%  |
| 2      | 12        | 38.71%  |
| 8      | 2         | 6.45%   |
| 6      | 2         | 6.45%   |
| 1      | 1         | 3.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 31        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 23        | 74.19%  |
| 1      | 8         | 25.81%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 31        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ec    | 4         | 12.5%   |
| Unknown    | 4         | 12.5%   |
| 0x806c1    | 3         | 9.38%   |
| 0x206a7    | 3         | 9.38%   |
| 0x806ea    | 2         | 6.25%   |
| 0x906e9    | 1         | 3.13%   |
| 0x906c0    | 1         | 3.13%   |
| 0x806e9    | 1         | 3.13%   |
| 0x706a8    | 1         | 3.13%   |
| 0x706a1    | 1         | 3.13%   |
| 0x506e3    | 1         | 3.13%   |
| 0x406e3    | 1         | 3.13%   |
| 0x40651    | 1         | 3.13%   |
| 0x1067a    | 1         | 3.13%   |
| 0x10661    | 1         | 3.13%   |
| 0x0a50000c | 1         | 3.13%   |
| 0x08608103 | 1         | 3.13%   |
| 0x08600106 | 1         | 3.13%   |
| 0x08108109 | 1         | 3.13%   |
| 0x08108102 | 1         | 3.13%   |
| 0x05000029 | 1         | 3.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 9         | 29.03%  |
| TigerLake     | 3         | 9.68%   |
| SandyBridge   | 3         | 9.68%   |
| Zen+          | 2         | 6.45%   |
| Skylake       | 2         | 6.45%   |
| Goldmont plus | 2         | 6.45%   |
| Unknown       | 2         | 6.45%   |
| Zen 3         | 1         | 3.23%   |
| Zen 2         | 1         | 3.23%   |
| Tremont       | 1         | 3.23%   |
| Silvermont    | 1         | 3.23%   |
| Penryn        | 1         | 3.23%   |
| Haswell       | 1         | 3.23%   |
| Core          | 1         | 3.23%   |
| Bobcat        | 1         | 3.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 23        | 62.16%  |
| AMD    | 9         | 24.32%  |
| Nvidia | 5         | 13.51%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 7.89%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 5.26%   |
| Intel HD Graphics 620                                                                    | 2         | 5.26%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 5.26%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 5.26%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 5.26%   |
| AMD Lucienne                                                                             | 2         | 5.26%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 2.63%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 2.63%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 2.63%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 2.63%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 2.63%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 2.63%   |
| Intel UHD Graphics 620                                                                   | 1         | 2.63%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 1         | 2.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 2.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 2.63%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 2.63%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 2.63%   |
| Intel HD Graphics 630                                                                    | 1         | 2.63%   |
| Intel HD Graphics 530                                                                    | 1         | 2.63%   |
| Intel HD Graphics 520                                                                    | 1         | 2.63%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 2.63%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 1         | 2.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.63%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 2.63%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 2.63%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 2.63%   |
| AMD Renoir                                                                               | 1         | 2.63%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 1         | 2.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 19        | 61.29%  |
| 1 x AMD        | 6         | 19.35%  |
| Intel + Nvidia | 3         | 9.68%   |
| AMD + Nvidia   | 2         | 6.45%   |
| Intel + AMD    | 1         | 3.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 27        | 87.1%   |
| Proprietary | 4         | 12.9%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 67.74%  |
| 1.01-2.0   | 4         | 12.9%   |
| 0.01-0.5   | 3         | 9.68%   |
| 5.01-6.0   | 1         | 3.23%   |
| 3.01-4.0   | 1         | 3.23%   |
| 0.51-1.0   | 1         | 3.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 8         | 21.62%  |
| AU Optronics            | 6         | 16.22%  |
| BOE                     | 5         | 13.51%  |
| Samsung Electronics     | 4         | 10.81%  |
| LG Display              | 4         | 10.81%  |
| Ancor Communications    | 2         | 5.41%   |
| Toshiba                 | 1         | 2.7%    |
| Philips                 | 1         | 2.7%    |
| PANDA                   | 1         | 2.7%    |
| Lenovo                  | 1         | 2.7%    |
| Dell                    | 1         | 2.7%    |
| CSO                     | 1         | 2.7%    |
| Chi Mei Optoelectronics | 1         | 2.7%    |
| Acer                    | 1         | 2.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Toshiba Internal LCD TOS5091 1366x768 344x193mm 15.5-inch                | 1         | 2.63%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 1         | 2.63%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch     | 1         | 2.63%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 1         | 2.63%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch        | 1         | 2.63%   |
| Samsung Electronics C27F591 SAM0D36 1920x1080 598x336mm 27.0-inch        | 1         | 2.63%   |
| Philips 273PLPH PHL08A8 1920x1080 598x336mm 27.0-inch                    | 1         | 2.63%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch                  | 1         | 2.63%   |
| LG Display LCD Monitor LGD06FB 1920x1080 309x174mm 14.0-inch             | 1         | 2.63%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch             | 1         | 2.63%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch             | 1         | 2.63%   |
| LG Display LCD Monitor LGD053C 1920x1080 309x174mm 14.0-inch             | 1         | 2.63%   |
| Lenovo D22-10 LEN65E4 1920x1080 476x268mm 21.5-inch                      | 1         | 2.63%   |
| Dell U4919DW DELA109 3840x1080 1198x337mm 49.0-inch                      | 1         | 2.63%   |
| CSO LCD Monitor CSO1500 3840x2160 344x194mm 15.5-inch                    | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN15D3 1920x1080 344x193mm 15.5-inch         | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN15CB 1920x1080 344x193mm 15.5-inch         | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN15C5 1366x768 344x193mm 15.5-inch          | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN1480 1366x768 309x174mm 14.0-inch          | 1         | 2.63%   |
| Chi Mei Optoelectronics LCD Monitor CMO1113 1366x768 256x144mm 11.6-inch | 1         | 2.63%   |
| BOE NV116WHM-T16 BOE0956 1366x768 256x144mm 11.6-inch                    | 1         | 2.63%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 1         | 2.63%   |
| BOE LCD Monitor BOE06CB 1920x1080 344x194mm 15.5-inch                    | 1         | 2.63%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 1         | 2.63%   |
| BOE LCD Monitor BOE0653 1920x1080 309x173mm 13.9-inch                    | 1         | 2.63%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch           | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch            | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch           | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO282B 3840x2160 293x165mm 13.2-inch           | 1         | 2.63%   |
| Ancor Communications C624B ACI24A9 1920x1200 518x324mm 24.1-inch         | 1         | 2.63%   |
| Ancor Communications ASUS VS229 ACI22D3 1920x1080 475x267mm 21.5-inch    | 1         | 2.63%   |
| Acer K242HYL ACR064A 1920x1080 527x296mm 23.8-inch                       | 1         | 2.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 17        | 48.57%  |
| 1366x768 (WXGA)   | 12        | 34.29%  |
| 3840x2160 (4K)    | 2         | 5.71%   |
| 3840x1080         | 1         | 2.86%   |
| 2256x1504         | 1         | 2.86%   |
| 1920x1200 (WUXGA) | 1         | 2.86%   |
| 1280x800 (WXGA)   | 1         | 2.86%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 18        | 48.65%  |
| 14     | 5         | 13.51%  |
| 13     | 5         | 13.51%  |
| 27     | 2         | 5.41%   |
| 21     | 2         | 5.41%   |
| 11     | 2         | 5.41%   |
| 49     | 1         | 2.7%    |
| 24     | 1         | 2.7%    |
| 23     | 1         | 2.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 24        | 64.86%  |
| 201-300     | 5         | 13.51%  |
| 501-600     | 4         | 10.81%  |
| 401-500     | 2         | 5.41%   |
| 351-400     | 1         | 2.7%    |
| 1001-1500   | 1         | 2.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 29        | 87.88%  |
| 16/10 | 2         | 6.06%   |
| 32/9  | 1         | 3.03%   |
| 3/2   | 1         | 3.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 18        | 48.65%  |
| 81-90          | 8         | 21.62%  |
| 71-80          | 2         | 5.41%   |
| 51-60          | 2         | 5.41%   |
| 301-350        | 2         | 5.41%   |
| 201-250        | 2         | 5.41%   |
| 251-300        | 1         | 2.7%    |
| 151-200        | 1         | 2.7%    |
| 501-1000       | 1         | 2.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 15        | 42.86%  |
| 101-120       | 10        | 28.57%  |
| 51-100        | 6         | 17.14%  |
| More than 240 | 2         | 5.71%   |
| 161-240       | 2         | 5.71%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 25        | 80.65%  |
| 2     | 5         | 16.13%  |
| 3     | 1         | 3.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 16        | 35.56%  |
| Realtek Semiconductor    | 12        | 26.67%  |
| Qualcomm Atheros         | 8         | 17.78%  |
| MediaTek                 | 2         | 4.44%   |
| Marvell Technology Group | 2         | 4.44%   |
| TP-Link                  | 1         | 2.22%   |
| T & A Mobile Phones      | 1         | 2.22%   |
| Dell                     | 1         | 2.22%   |
| Broadcom                 | 1         | 2.22%   |
| ASIX Electronics         | 1         | 2.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8         | 14.81%  |
| Intel Wi-Fi 6 AX200                                               | 4         | 7.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 5.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 3.7%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 3.7%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 3.7%    |
| Intel Wi-Fi 6 AX201                                               | 2         | 3.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.7%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.85%   |
| T & A Mobile Phones Unisoc Phone                                  | 1         | 1.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 1.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.85%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.85%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 1.85%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.85%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 1.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.85%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.85%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.85%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1         | 1.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 1.85%   |
| Intel Wireless 8265 / 8275                                        | 1         | 1.85%   |
| Intel Wireless 8260                                               | 1         | 1.85%   |
| Intel Wireless 7265                                               | 1         | 1.85%   |
| Intel Wireless 3165                                               | 1         | 1.85%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 1         | 1.85%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.85%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.85%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.85%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.85%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 1.85%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                     | 1         | 1.85%   |
| Dell DW5550                                                       | 1         | 1.85%   |
| Broadcom BCM4311 802.11b/g WLAN                                   | 1         | 1.85%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 16        | 51.61%  |
| Qualcomm Atheros      | 7         | 22.58%  |
| Realtek Semiconductor | 5         | 16.13%  |
| MediaTek              | 2         | 6.45%   |
| Broadcom              | 1         | 3.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 4         | 12.9%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 3         | 9.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 6.45%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 6.45%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 6.45%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 3.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 3.23%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 3.23%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 3.23%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 3.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 3.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 3.23%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 1         | 3.23%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 3.23%   |
| Intel Wireless 8265 / 8275                                     | 1         | 3.23%   |
| Intel Wireless 8260                                            | 1         | 3.23%   |
| Intel Wireless 7265                                            | 1         | 3.23%   |
| Intel Wireless 3165                                            | 1         | 3.23%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 1         | 3.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 3.23%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 3.23%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                  | 1         | 3.23%   |
| Broadcom BCM4311 802.11b/g WLAN                                | 1         | 3.23%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 9         | 42.86%  |
| Intel                    | 6         | 28.57%  |
| Qualcomm Atheros         | 2         | 9.52%   |
| Marvell Technology Group | 2         | 9.52%   |
| TP-Link                  | 1         | 4.76%   |
| ASIX Electronics         | 1         | 4.76%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8         | 38.1%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 9.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 9.52%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 4.76%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 4.76%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 4.76%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 4.76%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 4.76%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 4.76%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 4.76%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 4.76%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 4.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 31        | 57.41%  |
| Ethernet | 21        | 38.89%  |
| Modem    | 1         | 1.85%   |
| Unknown  | 1         | 1.85%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 25        | 80.65%  |
| Ethernet | 6         | 19.35%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 19        | 61.29%  |
| 1     | 11        | 35.48%  |
| 0     | 1         | 3.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 23        | 74.19%  |
| Yes  | 8         | 25.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 14        | 51.85%  |
| Qualcomm Atheros Communications | 3         | 11.11%  |
| Realtek Semiconductor           | 2         | 7.41%   |
| Lite-On Technology              | 2         | 7.41%   |
| Toshiba                         | 1         | 3.7%    |
| MediaTek                        | 1         | 3.7%    |
| IMC Networks                    | 1         | 3.7%    |
| Foxconn / Hon Hai               | 1         | 3.7%    |
| Dell                            | 1         | 3.7%    |
| Broadcom                        | 1         | 3.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface         | 4         | 14.81%  |
| Intel AX201 Bluetooth                      | 4         | 14.81%  |
| Intel AX200 Bluetooth                      | 4         | 14.81%  |
| Qualcomm Atheros  Bluetooth Device         | 2         | 7.41%   |
| Intel AX210 Bluetooth                      | 2         | 7.41%   |
| Toshiba RT Bluetooth Radio                 | 1         | 3.7%    |
| Realtek RTL8821A Bluetooth                 | 1         | 3.7%    |
| Realtek  Bluetooth 4.2 Adapter             | 1         | 3.7%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0      | 1         | 3.7%    |
| MediaTek Wireless_Device                   | 1         | 3.7%    |
| Lite-On Wireless_Device                    | 1         | 3.7%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth | 1         | 3.7%    |
| IMC Networks Bluetooth Radio               | 1         | 3.7%    |
| Foxconn / Hon Hai Bluetooth Device         | 1         | 3.7%    |
| Dell DW375 Bluetooth Module                | 1         | 3.7%    |
| Broadcom Bluetooth 2.1 Device              | 1         | 3.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 24        | 64.86%  |
| AMD                 | 8         | 21.62%  |
| Nvidia              | 3         | 8.11%   |
| Samsung Electronics | 1         | 2.7%    |
| Conexant Systems    | 1         | 2.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 13.95%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 4         | 9.3%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 6.98%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 6.98%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 4.65%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 4.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 4.65%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 4.65%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 4.65%   |
| Samsung Electronics USBC Headset                                                                  | 1         | 2.33%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 2.33%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 2.33%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 2.33%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 2.33%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 2.33%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 2.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 2.33%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 2.33%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 2.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1         | 2.33%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 2.33%   |
| Conexant Systems Hi-Res Audio                                                                     | 1         | 2.33%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 2.33%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 2.33%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 2.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 40%     |
| SK hynix            | 3         | 15%     |
| Micron Technology   | 3         | 15%     |
| Crucial             | 2         | 10%     |
| Unknown             | 1         | 5%      |
| Team                | 1         | 5%      |
| G.Skill             | 1         | 5%      |
| A-DATA Technology   | 1         | 5%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 4.76%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s             | 1         | 4.76%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 4.76%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 4.76%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 4.76%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 1         | 4.76%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 4.76%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 4.76%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 1         | 4.76%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 4.76%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 4.76%   |
| Samsung RAM M471A2G43AB2-CWE 16384MB SODIMM DDR4 3200MT/s        | 1         | 4.76%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 4.76%   |
| Samsung RAM K4E8E324EB-EGCF 2GB SODIMM LPDDR3 1867MT/s           | 1         | 4.76%   |
| Micron RAM 8HTF12864HDY-667E1 1GB SODIMM DDR2 667MT/s            | 1         | 4.76%   |
| Micron RAM 8ATF1G64HZ-2G3H1 8GB SODIMM DDR4 2400MT/s             | 1         | 4.76%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 1         | 4.76%   |
| G.Skill RAM F4-3200C22-16GRS 16GB SODIMM DDR4 3200MT/s           | 1         | 4.76%   |
| Crucial RAM CT8G4SFS824A.M8FJ 8GB SODIMM DDR4 2400MT/s           | 1         | 4.76%   |
| Crucial RAM CT16G4SFD8213.C16FBD 16GB SODIMM DDR4 2133MT/s       | 1         | 4.76%   |
| A-DATA RAM Module 8192MB SODIMM DDR4 2133MT/s                    | 1         | 4.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 9         | 52.94%  |
| LPDDR3 | 3         | 17.65%  |
| DDR3   | 2         | 11.76%  |
| LPDDR4 | 1         | 5.88%   |
| DDR2   | 1         | 5.88%   |
| DDR    | 1         | 5.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 13        | 81.25%  |
| Row Of Chips | 3         | 18.75%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 16384 | 5         | 29.41%  |
| 8192  | 5         | 29.41%  |
| 4096  | 3         | 17.65%  |
| 32768 | 2         | 11.76%  |
| 2048  | 1         | 5.88%   |
| 1024  | 1         | 5.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 5         | 27.78%  |
| 2133    | 4         | 22.22%  |
| 2667    | 2         | 11.11%  |
| 4267    | 1         | 5.56%   |
| 2400    | 1         | 5.56%   |
| 1867    | 1         | 5.56%   |
| 1600    | 1         | 5.56%   |
| 1333    | 1         | 5.56%   |
| 667     | 1         | 5.56%   |
| Unknown | 1         | 5.56%   |

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
| Realtek Semiconductor                  | 5         | 17.86%  |
| Quanta                                 | 4         | 14.29%  |
| Sunplus Innovation Technology          | 3         | 10.71%  |
| Microdia                               | 3         | 10.71%  |
| Chicony Electronics                    | 3         | 10.71%  |
| IMC Networks                           | 2         | 7.14%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 7.14%   |
| Z-Star Microelectronics                | 1         | 3.57%   |
| Syntek                                 | 1         | 3.57%   |
| Microsoft                              | 1         | 3.57%   |
| Logitech                               | 1         | 3.57%   |
| Importek                               | 1         | 3.57%   |
| Acer                                   | 1         | 3.57%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                                    | 2         | 7.14%   |
| Quanta HD User Facing                                           | 2         | 7.14%   |
| Microdia Integrated_Webcam_HD                                   | 2         | 7.14%   |
| Z-Star Webcam                                                   | 1         | 3.57%   |
| Syntek Integrated Camera                                        | 1         | 3.57%   |
| Sunplus Laptop_Integrated_Webcam_HD                             | 1         | 3.57%   |
| Realtek Laptop Camera                                           | 1         | 3.57%   |
| Realtek Integrated_Webcam_HD                                    | 1         | 3.57%   |
| Realtek Integrated Webcam_HD                                    | 1         | 3.57%   |
| Realtek Integrated Webcam                                       | 1         | 3.57%   |
| Realtek HD WebCam                                               | 1         | 3.57%   |
| Quanta VGA WebCam                                               | 1         | 3.57%   |
| Quanta USB2.0 HD UVC WebCam                                     | 1         | 3.57%   |
| Microsoft LifeCam Studio                                        | 1         | 3.57%   |
| Microdia USB 2.0 Camera                                         | 1         | 3.57%   |
| Logitech Webcam C270                                            | 1         | 3.57%   |
| Importek TOSHIBA Web Camera - HD                                | 1         | 3.57%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 1         | 3.57%   |
| IMC Networks Integrated Camera                                  | 1         | 3.57%   |
| Chicony Sony Visual Communication Camera                        | 1         | 3.57%   |
| Chicony Integrated Camera                                       | 1         | 3.57%   |
| Chicony EasyCamera                                              | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                   | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 3.57%   |
| Acer Lenovo EasyCamera                                          | 1         | 3.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 2         | 33.33%  |
| Synaptics                  | 2         | 33.33%  |
| Shenzhen Goodix Technology | 1         | 16.67%  |
| AuthenTec                  | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader | 2         | 33.33%  |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 16.67%  |
| Validity Sensors VFS Fingerprint sensor           | 1         | 16.67%  |
| Shenzhen Goodix  FingerPrint Device               | 1         | 16.67%  |
| AuthenTec Fingerprint Sensor                      | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 40%     |
| Alcor Micro | 2         | 40%     |
| O2 Micro    | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 2         | 40%     |
| O2 Micro OZ776 CCID Smartcard Reader           | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 20%     |
| Broadcom 5880                                  | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 19        | 61.29%  |
| 2     | 7         | 22.58%  |
| 1     | 5         | 16.13%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 6         | 28.57%  |
| Chipcard              | 5         | 23.81%  |
| Net/wireless          | 4         | 19.05%  |
| Multimedia controller | 3         | 14.29%  |
| Unassigned class      | 1         | 4.76%   |
| Storage               | 1         | 4.76%   |
| Graphics card         | 1         | 4.76%   |

