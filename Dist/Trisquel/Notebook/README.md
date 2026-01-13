Trisquel - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------

A project to collect tested hardware configurations for Trisquel.

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

Total: 53

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | ProBook 650 G8 Notebook ... | [49ad50d2a1](https://linux-hardware.org/?probe=49ad50d2a1) | Dec 22, 2025 |
| HP            | ProBook 650 G8 Notebook ... | [cd6b12b70f](https://linux-hardware.org/?probe=cd6b12b70f) | Dec 22, 2025 |
| Dell          | Latitude 5520               | [7c5b618d9f](https://linux-hardware.org/?probe=7c5b618d9f) | Dec 04, 2025 |
| ASUSTek       | K84L                        | [3bac93e134](https://linux-hardware.org/?probe=3bac93e134) | Sep 11, 2025 |
| ASUSTek       | X456URK                     | [63cca1412e](https://linux-hardware.org/?probe=63cca1412e) | Sep 04, 2025 |
| Acer          | TravelMate P215-54          | [dbf9a46580](https://linux-hardware.org/?probe=dbf9a46580) | Aug 08, 2025 |
| ASUSTek       | N56JK                       | [21e4b60b22](https://linux-hardware.org/?probe=21e4b60b22) | Jun 06, 2025 |
| ASUSTek       | N56JK                       | [d05bf7c7c7](https://linux-hardware.org/?probe=d05bf7c7c7) | Jun 06, 2025 |
| Fujitsu Si... | AMILO PRO V3515             | [63c032f435](https://linux-hardware.org/?probe=63c032f435) | Apr 24, 2025 |
| Lenovo        | ThinkPad X200 7459J74       | [8204d5546a](https://linux-hardware.org/?probe=8204d5546a) | Apr 04, 2025 |
| Lenovo        | ThinkPad X200 7455HS2       | [c9b05377a2](https://linux-hardware.org/?probe=c9b05377a2) | Mar 15, 2025 |
| Dell          | XPS 12 9Q23                 | [5a4c5a1eeb](https://linux-hardware.org/?probe=5a4c5a1eeb) | Feb 04, 2025 |
| Lenovo        | ThinkPad T480 20L5000UUS    | [e0cf37ba04](https://linux-hardware.org/?probe=e0cf37ba04) | Nov 26, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JK0... | [7b5c860bd2](https://linux-hardware.org/?probe=7b5c860bd2) | Nov 15, 2024 |
| Dell          | XPS 12 9Q23                 | [b842f0a090](https://linux-hardware.org/?probe=b842f0a090) | Sep 21, 2024 |
| LZ            | LZ1004_3                    | [8ad0eef591](https://linux-hardware.org/?probe=8ad0eef591) | Aug 28, 2024 |
| Lenovo        | ThinkPad X230 2325Y3C       | [31631cc4bd](https://linux-hardware.org/?probe=31631cc4bd) | Aug 04, 2024 |
| Dell          | Latitude E6540              | [c6c6acf7d2](https://linux-hardware.org/?probe=c6c6acf7d2) | May 08, 2024 |
| Dell          | Latitude E6540              | [a57f8ef498](https://linux-hardware.org/?probe=a57f8ef498) | May 08, 2024 |
| Lenovo        | ThinkPad T430s 2356C45      | [a76e3d7e43](https://linux-hardware.org/?probe=a76e3d7e43) | Dec 10, 2023 |
| Notebook      | NJ50_70CU                   | [ed00b585a3](https://linux-hardware.org/?probe=ed00b585a3) | Nov 12, 2023 |
| Dell          | Latitude 5590               | [5712f37060](https://linux-hardware.org/?probe=5712f37060) | Nov 09, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [855f5edce0](https://linux-hardware.org/?probe=855f5edce0) | Sep 08, 2023 |
| Dell          | Latitude E6400              | [65c390fe0e](https://linux-hardware.org/?probe=65c390fe0e) | Aug 12, 2023 |
| Dell          | XPS 15 9510                 | [8375e909e7](https://linux-hardware.org/?probe=8375e909e7) | Jul 30, 2023 |
| Lenovo        | ThinkPad X200 7458C23       | [3f09abaa12](https://linux-hardware.org/?probe=3f09abaa12) | Jul 24, 2023 |
| Dell          | XPS 15 9510                 | [154b34b737](https://linux-hardware.org/?probe=154b34b737) | Jul 18, 2023 |
| Lenovo        | G505s 20255                 | [4ec56be6a5](https://linux-hardware.org/?probe=4ec56be6a5) | Jul 03, 2023 |
| Lenovo        | G505s 20255                 | [2940c0be7d](https://linux-hardware.org/?probe=2940c0be7d) | Jul 01, 2023 |
| Toshiba       | NB510                       | [a66bda9742](https://linux-hardware.org/?probe=a66bda9742) | Jun 18, 2023 |
| HP            | Stream Laptop 11-y0XX       | [4f777df0e8](https://linux-hardware.org/?probe=4f777df0e8) | Apr 29, 2023 |
| Itautec       | Infoway                     | [c046d6e093](https://linux-hardware.org/?probe=c046d6e093) | Apr 16, 2023 |
| Acer          | Nitro AN517-54              | [185c4824b7](https://linux-hardware.org/?probe=185c4824b7) | Apr 07, 2023 |
| Dell          | Inspiron 15-3567            | [e94792b948](https://linux-hardware.org/?probe=e94792b948) | Dec 13, 2022 |
| Dell          | Inspiron 1545               | [5b13c289e1](https://linux-hardware.org/?probe=5b13c289e1) | Nov 26, 2022 |
| Libiquity     | Taurinus X200               | [75c0f41e26](https://linux-hardware.org/?probe=75c0f41e26) | Nov 09, 2022 |
| Lenovo        | ThinkPad T430 2347G2U       | [ab06dd40c4](https://linux-hardware.org/?probe=ab06dd40c4) | Oct 03, 2022 |
| Lenovo        | ThinkPad T430 2347G2U       | [5b08d764b4](https://linux-hardware.org/?probe=5b08d764b4) | Sep 27, 2022 |
| Lenovo        | G505s 20255                 | [a9e525c695](https://linux-hardware.org/?probe=a9e525c695) | Sep 16, 2022 |
| Timi          | TM1709                      | [2fb5436031](https://linux-hardware.org/?probe=2fb5436031) | Sep 04, 2022 |
| Lenovo        | ThinkPad T430 2347G2U       | [8d7c5df586](https://linux-hardware.org/?probe=8d7c5df586) | Sep 03, 2022 |
| ASUSTek       | K55A                        | [5d11054a36](https://linux-hardware.org/?probe=5d11054a36) | Aug 28, 2022 |
| Lenovo        | ThinkPad T420 4177QKU       | [a18ab36f34](https://linux-hardware.org/?probe=a18ab36f34) | Aug 17, 2022 |
| Lenovo        | ThinkPad T430 2347G2U       | [f6abe5392b](https://linux-hardware.org/?probe=f6abe5392b) | Aug 03, 2022 |
| Lenovo        | ThinkPad T430 2347G2U       | [b25d6bf66c](https://linux-hardware.org/?probe=b25d6bf66c) | Jul 27, 2022 |
| Lenovo        | ThinkPad T420 4177QKU       | [215758ad8a](https://linux-hardware.org/?probe=215758ad8a) | Apr 30, 2022 |
| Dell          | XPS 13 9360                 | [1126937638](https://linux-hardware.org/?probe=1126937638) | Apr 28, 2022 |
| Toshiba       | Satellite C800D             | [5cdc03cbdf](https://linux-hardware.org/?probe=5cdc03cbdf) | Feb 10, 2022 |
| Samsung       | N130                        | [1a88380af6](https://linux-hardware.org/?probe=1a88380af6) | Nov 27, 2021 |
| ASUSTek       | U56E                        | [99bd7dbfdf](https://linux-hardware.org/?probe=99bd7dbfdf) | Sep 09, 2021 |
| Lenovo        | ThinkPad X200 7455FNG       | [6fcadf1396](https://linux-hardware.org/?probe=6fcadf1396) | Mar 20, 2021 |
| Acer          | TravelMate B115-M           | [62239072f1](https://linux-hardware.org/?probe=62239072f1) | Nov 26, 2019 |
| GPD           | MicroPC                     | [8fc0176f69](https://linux-hardware.org/?probe=8fc0176f69) | Sep 28, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Trisquel 11.0.1 | 12        | 27.91%  |
| Trisquel 11.0   | 12        | 27.91%  |
| Trisquel 10.0.1 | 10        | 23.26%  |
| Trisquel 9.0    | 4         | 9.3%    |
| Trisquel 8.0    | 2         | 4.65%   |
| Trisquel 10.0   | 2         | 4.65%   |
| Trisquel 12.0   | 1         | 2.33%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Trisquel | 42        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 5.15.0-107-generic   | 4         | 8.7%    |
| 5.4.0-96-generic     | 3         | 6.52%   |
| 5.4.0-122-generic    | 3         | 6.52%   |
| 5.4.0-125-generic    | 2         | 4.35%   |
| 5.15.0-78-generic    | 2         | 4.35%   |
| 5.15.0-76-generic    | 2         | 4.35%   |
| 5.15.0-69-generic    | 2         | 4.35%   |
| 5.15.0-67-generic    | 2         | 4.35%   |
| 5.15.0-105-generic   | 2         | 4.35%   |
| 6.8.0-90-generic     | 1         | 2.17%   |
| 6.6.47-gnu           | 1         | 2.17%   |
| 6.0.12-x64v1-xanmod1 | 1         | 2.17%   |
| 5.4.0-159-generic    | 1         | 2.17%   |
| 5.4.0-132-generic    | 1         | 2.17%   |
| 5.4.0-131-generic    | 1         | 2.17%   |
| 5.4.0-126-generic    | 1         | 2.17%   |
| 5.4.0-113-generic    | 1         | 2.17%   |
| 5.3.13-gnu           | 1         | 2.17%   |
| 5.3.1-gnu            | 1         | 2.17%   |
| 5.15.0-91-generic    | 1         | 2.17%   |
| 5.15.0-88-generic    | 1         | 2.17%   |
| 5.15.0-86-generic    | 1         | 2.17%   |
| 5.15.0-73-generic    | 1         | 2.17%   |
| 5.15.0-135-generic   | 1         | 2.17%   |
| 5.15.0-133-generic   | 1         | 2.17%   |
| 5.15.0-130-generic   | 1         | 2.17%   |
| 5.15.0-124-generic   | 1         | 2.17%   |
| 5.15.0-122-generic   | 1         | 2.17%   |
| 5.15.0-117-generic   | 1         | 2.17%   |
| 4.15.0-161-generic   | 1         | 2.17%   |
| 4.15.0-156-generic   | 1         | 2.17%   |
| 4.15.0-136-generic   | 1         | 2.17%   |
| 4.15.0-121-generic   | 1         | 2.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 23        | 53.49%  |
| 5.4.0   | 11        | 25.58%  |
| 4.15.0  | 4         | 9.3%    |
| 6.8.0   | 1         | 2.33%   |
| 6.6.47  | 1         | 2.33%   |
| 6.0.12  | 1         | 2.33%   |
| 5.3.13  | 1         | 2.33%   |
| 5.3.1   | 1         | 2.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 23        | 53.49%  |
| 5.4     | 11        | 25.58%  |
| 4.15    | 4         | 9.3%    |
| 5.3     | 2         | 4.65%   |
| 6.8     | 1         | 2.33%   |
| 6.6     | 1         | 2.33%   |
| 6.0     | 1         | 2.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 40        | 95.24%  |
| i686   | 2         | 4.76%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| MATE    | 27        | 62.79%  |
| LXDE    | 5         | 11.63%  |
| KDE5    | 4         | 9.3%    |
| GNOME   | 3         | 6.98%   |
| Unknown | 2         | 4.65%   |
| XFCE    | 1         | 2.33%   |
| dwm     | 1         | 2.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 40        | 95.24%  |
| Wayland | 2         | 4.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 28        | 65.12%  |
| SDDM    | 4         | 9.3%    |
| Unknown | 4         | 9.3%    |
| TDM     | 3         | 6.98%   |
| SLiM    | 2         | 4.65%   |
| GDM3    | 1         | 2.33%   |
| GDM     | 1         | 2.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 19        | 45.24%  |
| C       | 5         | 11.9%   |
| fr_FR   | 4         | 9.52%   |
| ru_RU   | 3         | 7.14%   |
| Unknown | 2         | 4.76%   |
| tr_TR   | 1         | 2.38%   |
| ru_UA   | 1         | 2.38%   |
| pt_BR   | 1         | 2.38%   |
| pl_PL   | 1         | 2.38%   |
| nl_NL   | 1         | 2.38%   |
| es_MX   | 1         | 2.38%   |
| es_ES   | 1         | 2.38%   |
| en_GB   | 1         | 2.38%   |
| de_DE   | 1         | 2.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 23        | 54.76%  |
| BIOS | 19        | 45.24%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 35        | 83.33%  |
| Overlay | 6         | 14.29%  |
| Ext2    | 1         | 2.38%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 32        | 76.19%  |
| MBR     | 5         | 11.9%   |
| Unknown | 5         | 11.9%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 35        | 81.4%   |
| Yes       | 8         | 18.6%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 38        | 90.48%  |
| Yes       | 4         | 9.52%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 12        | 28.57%  |
| Dell                | 10        | 23.81%  |
| ASUSTek Computer    | 5         | 11.9%   |
| Hewlett-Packard     | 3         | 7.14%   |
| Toshiba             | 2         | 4.76%   |
| Acer                | 2         | 4.76%   |
| Timi                | 1         | 2.38%   |
| Samsung Electronics | 1         | 2.38%   |
| Notebook            | 1         | 2.38%   |
| LZ                  | 1         | 2.38%   |
| Libiquity           | 1         | 2.38%   |
| Itautec             | 1         | 2.38%   |
| GPD                 | 1         | 2.38%   |
| Fujitsu Siemens     | 1         | 2.38%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Lenovo ThinkPad T420 4177QKU         | 2         | 4.76%   |
| Dell XPS 15 9510                     | 2         | 4.76%   |
| Toshiba Satellite C800D              | 1         | 2.38%   |
| Toshiba NB510                        | 1         | 2.38%   |
| Timi TM1709                          | 1         | 2.38%   |
| Samsung N130                         | 1         | 2.38%   |
| Notebook NJ50_70CU                   | 1         | 2.38%   |
| LZ LZ1004_3                          | 1         | 2.38%   |
| Libiquity Taurinus X200              | 1         | 2.38%   |
| Lenovo ThinkPad X230 2325Y3C         | 1         | 2.38%   |
| Lenovo ThinkPad X200 7459J74         | 1         | 2.38%   |
| Lenovo ThinkPad X200 7458C23         | 1         | 2.38%   |
| Lenovo ThinkPad X200 7455HS2         | 1         | 2.38%   |
| Lenovo ThinkPad X200 7455FNG         | 1         | 2.38%   |
| Lenovo ThinkPad T480 20L5000UUS      | 1         | 2.38%   |
| Lenovo ThinkPad T430s 2356C45        | 1         | 2.38%   |
| Lenovo ThinkPad T430 2347G2U         | 1         | 2.38%   |
| Lenovo ThinkPad E14 Gen 5 21JK0006TX | 1         | 2.38%   |
| Lenovo G505s 20255                   | 1         | 2.38%   |
| Itautec Infoway                      | 1         | 2.38%   |
| HP Victus by Laptop 16-e0xxx         | 1         | 2.38%   |
| HP Stream Laptop 11-y0XX             | 1         | 2.38%   |
| HP ProBook 650 G8 Notebook PC        | 1         | 2.38%   |
| GPD MicroPC                          | 1         | 2.38%   |
| Fujitsu Siemens AMILO PRO V3515      | 1         | 2.38%   |
| Dell XPS 13 9360                     | 1         | 2.38%   |
| Dell XPS 12 9Q23                     | 1         | 2.38%   |
| Dell Latitude E6540                  | 1         | 2.38%   |
| Dell Latitude E6400                  | 1         | 2.38%   |
| Dell Latitude 5590                   | 1         | 2.38%   |
| Dell Latitude 5520                   | 1         | 2.38%   |
| Dell Inspiron 1545                   | 1         | 2.38%   |
| Dell Inspiron 15-3567                | 1         | 2.38%   |
| ASUS X456URK                         | 1         | 2.38%   |
| ASUS U56E                            | 1         | 2.38%   |
| ASUS N56JK                           | 1         | 2.38%   |
| ASUS K84L                            | 1         | 2.38%   |
| ASUS K55A                            | 1         | 2.38%   |
| Acer TravelMate B115-M               | 1         | 2.38%   |
| Acer Nitro AN517-54                  | 1         | 2.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 11        | 26.19%  |
| Dell XPS              | 4         | 9.52%   |
| Dell Latitude         | 4         | 9.52%   |
| Dell Inspiron         | 2         | 4.76%   |
| Toshiba Satellite     | 1         | 2.38%   |
| Toshiba NB510         | 1         | 2.38%   |
| Timi TM1709           | 1         | 2.38%   |
| Samsung N130          | 1         | 2.38%   |
| Notebook NJ50         | 1         | 2.38%   |
| LZ LZ1004             | 1         | 2.38%   |
| Libiquity Taurinus    | 1         | 2.38%   |
| Lenovo G505s          | 1         | 2.38%   |
| Itautec Infoway       | 1         | 2.38%   |
| HP Victus             | 1         | 2.38%   |
| HP Stream             | 1         | 2.38%   |
| HP ProBook            | 1         | 2.38%   |
| GPD MicroPC           | 1         | 2.38%   |
| Fujitsu Siemens AMILO | 1         | 2.38%   |
| ASUS X456URK          | 1         | 2.38%   |
| ASUS U56E             | 1         | 2.38%   |
| ASUS N56JK            | 1         | 2.38%   |
| ASUS K84L             | 1         | 2.38%   |
| ASUS K55A             | 1         | 2.38%   |
| Acer TravelMate       | 1         | 2.38%   |
| Acer Nitro            | 1         | 2.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2008 | 8         | 19.05%  |
| 2012 | 6         | 14.29%  |
| 2021 | 4         | 9.52%   |
| 2016 | 4         | 9.52%   |
| 2011 | 4         | 9.52%   |
| 2018 | 3         | 7.14%   |
| 2020 | 2         | 4.76%   |
| 2019 | 2         | 4.76%   |
| 2014 | 2         | 4.76%   |
| 2013 | 2         | 4.76%   |
| 2023 | 1         | 2.38%   |
| 2022 | 1         | 2.38%   |
| 2015 | 1         | 2.38%   |
| 2009 | 1         | 2.38%   |
| 2006 | 1         | 2.38%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 42        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 42        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 36        | 85.71%  |
| Yes  | 6         | 14.29%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 19        | 45.24%  |
| 16.01-24.0 | 8         | 19.05%  |
| 1.01-2.0   | 6         | 14.29%  |
| 8.01-16.0  | 5         | 11.9%   |
| 3.01-4.0   | 4         | 9.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 25        | 58.14%  |
| 2.01-3.0  | 6         | 13.95%  |
| 3.01-4.0  | 4         | 9.3%    |
| 0.51-1.0  | 4         | 9.3%    |
| 4.01-8.0  | 2         | 4.65%   |
| 8.01-16.0 | 1         | 2.33%   |
| 0.01-0.5  | 1         | 2.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 30        | 69.77%  |
| 2      | 10        | 23.26%  |
| 4      | 1         | 2.33%   |
| 3      | 1         | 2.33%   |
| 0      | 1         | 2.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 26        | 61.9%   |
| Yes       | 16        | 38.1%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 92.86%  |
| No        | 3         | 7.14%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 41        | 97.62%  |
| No        | 1         | 2.38%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 57.14%  |
| No        | 18        | 42.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 12        | 27.91%  |
| France      | 5         | 11.63%  |
| Russia      | 4         | 9.3%    |
| China       | 4         | 9.3%    |
| Indonesia   | 3         | 6.98%   |
| Germany     | 3         | 6.98%   |
| Turkey      | 2         | 4.65%   |
| Netherlands | 2         | 4.65%   |
| Brazil      | 2         | 4.65%   |
| Spain       | 1         | 2.33%   |
| South Korea | 1         | 2.33%   |
| Poland      | 1         | 2.33%   |
| Mexico      | 1         | 2.33%   |
| Kazakhstan  | 1         | 2.33%   |
| Belarus     | 1         | 2.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lincoln              | 4         | 9.3%    |
| Moscow               | 2         | 4.65%   |
| Malvern              | 2         | 4.65%   |
| Istanbul             | 2         | 4.65%   |
| Guangzhou            | 2         | 4.65%   |
| Cerons               | 2         | 4.65%   |
| Amsterdam            | 2         | 4.65%   |
| Yongin-si            | 1         | 2.33%   |
| Wylie                | 1         | 2.33%   |
| Wiesbaden            | 1         | 2.33%   |
| Vitebsk              | 1         | 2.33%   |
| Tychy                | 1         | 2.33%   |
| St Petersburg        | 1         | 2.33%   |
| Shenzhen             | 1         | 2.33%   |
| Sabadell             | 1         | 2.33%   |
| Pinangsia            | 1         | 2.33%   |
| Parksley             | 1         | 2.33%   |
| Paris                | 1         | 2.33%   |
| Oryol                | 1         | 2.33%   |
| Omaha                | 1         | 2.33%   |
| Missoula             | 1         | 2.33%   |
| Malang               | 1         | 2.33%   |
| Lüdenscheid         | 1         | 2.33%   |
| Leverkusen           | 1         | 2.33%   |
| Fayetteville         | 1         | 2.33%   |
| Depok                | 1         | 2.33%   |
| Ciudad del Carmen    | 1         | 2.33%   |
| Chengdu              | 1         | 2.33%   |
| Burgnac              | 1         | 2.33%   |
| Borderes-sur-l'Echez | 1         | 2.33%   |
| Blumenau             | 1         | 2.33%   |
| Americana            | 1         | 2.33%   |
| Almaty               | 1         | 2.33%   |
| Acworth              | 1         | 2.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 12     | 21.57%  |
| SanDisk             | 8         | 8      | 15.69%  |
| WDC                 | 5         | 5      | 9.8%    |
| Crucial             | 4         | 4      | 7.84%   |
| Toshiba             | 3         | 3      | 5.88%   |
| Seagate             | 3         | 9      | 5.88%   |
| Unknown             | 2         | 2      | 3.92%   |
| SK hynix            | 2         | 2      | 3.92%   |
| Kingston            | 2         | 2      | 3.92%   |
| HGST HTS            | 2         | 4      | 3.92%   |
| VISIPRO             | 1         | 1      | 1.96%   |
| Transcend           | 1         | 1      | 1.96%   |
| Qumo                | 1         | 1      | 1.96%   |
| Plextor             | 1         | 1      | 1.96%   |
| Patriot             | 1         | 1      | 1.96%   |
| Hitachi             | 1         | 1      | 1.96%   |
| HGST                | 1         | 1      | 1.96%   |
| China               | 1         | 1      | 1.96%   |
| A-DATA Technology   | 1         | 1      | 1.96%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| SK hynix PC711 NVMe 512GB                         | 2         | 3.77%   |
| Seagate ST4000NM 0033-9ZM170 4TB                  | 2         | 3.77%   |
| HGST HTS 721010A9E630 1TB                         | 2         | 3.77%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                  | 1         | 1.89%   |
| WDC WD6400BPVT-80HXZT3 640GB                      | 1         | 1.89%   |
| WDC WD3200BEVT-75ZCT2 320GB                       | 1         | 1.89%   |
| WDC WD1600BEVS-08RST2 160GB                       | 1         | 1.89%   |
| WDC PC SN730 SDBPNTY-512G-1006 512GB              | 1         | 1.89%   |
| VISIPRO SDVPSA1910256TMYTHK 256GB SSD             | 1         | 1.89%   |
| Unknown SC64G  64GB                               | 1         | 1.89%   |
| Unknown NCard  32GB                               | 1         | 1.89%   |
| Transcend TS256GMTS430S 256GB SSD                 | 1         | 1.89%   |
| Toshiba THNSN5256GPUK NVMe 256GB                  | 1         | 1.89%   |
| Toshiba MK3275GSX 320GB                           | 1         | 1.89%   |
| Toshiba HDWL110 1TB                               | 1         | 1.89%   |
| Seagate ST320LT007-9ZV142 320GB                   | 1         | 1.89%   |
| Seagate ST1000LM035-1RK172 1TB                    | 1         | 1.89%   |
| Seagate Expansion HDD 4TB                         | 1         | 1.89%   |
| Sandisk WD PC SN740 SDDQMQD-512G-1201 512GB       | 1         | 1.89%   |
| Sandisk WD Blue SN570 1TB                         | 1         | 1.89%   |
| SanDisk SSD U110 16GB                             | 1         | 1.89%   |
| SanDisk SSD PLUS 240GB                            | 1         | 1.89%   |
| SanDisk SSD PLUS 2000GB                           | 1         | 1.89%   |
| SanDisk SDSSDH3 2T00 2TB                          | 1         | 1.89%   |
| SanDisk NVMe SSD Drive 1TB                        | 1         | 1.89%   |
| SanDisk DF4032  32GB                              | 1         | 1.89%   |
| Samsung SSD PM830 mSATA 256GB                     | 1         | 1.89%   |
| Samsung SSD 860 EVO 250GB                         | 1         | 1.89%   |
| Samsung SSD 840 PRO Series 256GB                  | 1         | 1.89%   |
| Samsung SSD 840 EVO 120GB                         | 1         | 1.89%   |
| Samsung PM991a NVMe 256GB                         | 1         | 1.89%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 1         | 1.89%   |
| Samsung MZVLQ512HBLU-00BTW 512GB                  | 1         | 1.89%   |
| Samsung MZNLN128HAHQ-000H1 128GB SSD              | 1         | 1.89%   |
| Samsung MZNLN128HAHQ-00000 128GB SSD              | 1         | 1.89%   |
| Samsung HM251JI 250GB                             | 1         | 1.89%   |
| Samsung HM160HI 160GB                             | 1         | 1.89%   |
| Qumo SSD 120GB                                    | 1         | 1.89%   |
| Plextor PX-512M5Pro 512GB SSD                     | 1         | 1.89%   |
| Patriot P210 128GB SSD                            | 1         | 1.89%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 3      | 21.43%  |
| Seagate             | 3         | 9      | 21.43%  |
| Toshiba             | 2         | 2      | 14.29%  |
| Samsung Electronics | 2         | 2      | 14.29%  |
| HGST HTS            | 2         | 4      | 14.29%  |
| Hitachi             | 1         | 1      | 7.14%   |
| HGST                | 1         | 1      | 7.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 7      | 25%     |
| SanDisk             | 4         | 4      | 16.67%  |
| Crucial             | 4         | 4      | 16.67%  |
| Kingston            | 2         | 2      | 8.33%   |
| WDC                 | 1         | 1      | 4.17%   |
| VISIPRO             | 1         | 1      | 4.17%   |
| Transcend           | 1         | 1      | 4.17%   |
| Qumo                | 1         | 1      | 4.17%   |
| Plextor             | 1         | 1      | 4.17%   |
| Patriot             | 1         | 1      | 4.17%   |
| China               | 1         | 1      | 4.17%   |
| A-DATA Technology   | 1         | 1      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 23        | 25     | 51.11%  |
| HDD  | 11        | 22     | 24.44%  |
| NVMe | 8         | 10     | 17.78%  |
| MMC  | 3         | 3      | 6.67%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 31        | 38     | 68.89%  |
| NVMe | 8         | 10     | 17.78%  |
| SAS  | 3         | 9      | 6.67%   |
| MMC  | 3         | 3      | 6.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 24        | 28     | 64.86%  |
| 0.51-1.0   | 7         | 11     | 18.92%  |
| 3.01-4.0   | 4         | 6      | 10.81%  |
| 1.01-2.0   | 2         | 2      | 5.41%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 19        | 45.24%  |
| 251-500        | 5         | 11.9%   |
| More than 3000 | 4         | 9.52%   |
| 1-20           | 4         | 9.52%   |
| 21-50          | 3         | 7.14%   |
| 501-1000       | 3         | 7.14%   |
| 1001-2000      | 2         | 4.76%   |
| 51-100         | 2         | 4.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 19        | 43.18%  |
| 21-50          | 8         | 18.18%  |
| 101-250        | 6         | 13.64%  |
| 51-100         | 4         | 9.09%   |
| 2001-3000      | 2         | 4.55%   |
| 1001-2000      | 2         | 4.55%   |
| 501-1000       | 2         | 4.55%   |
| More than 3000 | 1         | 2.27%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Notebooks | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| HGST HTS 721010A9E630 1TB        | 2         | 4      | 28.57%  |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 1         | 1      | 14.29%  |
| WDC WD3200BEVT-75ZCT2 320GB      | 1         | 1      | 14.29%  |
| Toshiba MK3275GSX 320GB          | 1         | 1      | 14.29%  |
| Seagate ST320LT007-9ZV142 320GB  | 1         | 3      | 14.29%  |
| Crucial CT240BX200SSD1 240GB     | 1         | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 2         | 2      | 28.57%  |
| HGST HTS | 2         | 4      | 28.57%  |
| Toshiba  | 1         | 1      | 14.29%  |
| Seagate  | 1         | 3      | 14.29%  |
| Crucial  | 1         | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| HGST HTS | 2         | 4      | 40%     |
| WDC      | 1         | 1      | 20%     |
| Toshiba  | 1         | 1      | 20%     |
| Seagate  | 1         | 3      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 9      | 66.67%  |
| SSD  | 2         | 2      | 33.33%  |

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
| Works    | 30        | 39     | 65.22%  |
| Detected | 10        | 10     | 21.74%  |
| Malfunc  | 6         | 11     | 13.04%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 30        | 69.77%  |
| SanDisk                      | 4         | 9.3%    |
| Samsung Electronics          | 3         | 6.98%   |
| SK hynix                     | 2         | 4.65%   |
| AMD                          | 2         | 4.65%   |
| VIA Technologies             | 1         | 2.33%   |
| Toshiba America Info Systems | 1         | 2.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 7         | 14.89%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 5         | 10.64%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 8.51%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 6.38%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 2         | 4.26%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 2         | 4.26%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 4.26%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 4.26%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 2         | 4.26%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 2.13%   |
| VIA VT8237A Integrated SATA RAID Controller                                    | 1         | 2.13%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 2.13%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                   | 1         | 2.13%   |
| Sandisk WD PC SN740 NVMe SSD 512GB (DRAM-less)                                 | 1         | 2.13%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 1         | 2.13%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 1         | 2.13%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 2.13%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 2.13%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 1         | 2.13%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 2.13%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 2.13%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 2.13%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 2.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 1         | 2.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 1         | 2.13%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 1         | 2.13%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 1         | 2.13%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 30        | 68.18%  |
| NVMe | 8         | 18.18%  |
| RAID | 3         | 6.82%   |
| IDE  | 3         | 6.82%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 39        | 92.86%  |
| AMD    | 3         | 7.14%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel Core i5-3320M CPU @ 2.60GHz        | 3         | 7.14%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 2         | 4.76%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 2         | 4.76%   |
| Intel Core i5-2410M CPU @ 2.30GHz        | 2         | 4.76%   |
| Intel Core 2 CPU P8700 @ 2.53GHz         | 2         | 4.76%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz  | 2         | 4.76%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz   | 1         | 2.38%   |
| Intel Pentium CPU N3530 @ 2.16GHz        | 1         | 2.38%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 1         | 2.38%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz       | 1         | 2.38%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz       | 1         | 2.38%   |
| Intel Core i7-3687U CPU @ 2.10GHz        | 1         | 2.38%   |
| Intel Core i5-3210M CPU @ 2.50GHz        | 1         | 2.38%   |
| Intel Core i5-2430M CPU @ 2.40GHz        | 1         | 2.38%   |
| Intel Core i3-6006U CPU @ 2.00GHz        | 1         | 2.38%   |
| Intel Core i3-2330M CPU @ 2.20GHz        | 1         | 2.38%   |
| Intel Core i3-10110U CPU @ 2.10GHz       | 1         | 2.38%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz     | 1         | 2.38%   |
| Intel Core 2 Duo CPU P8800 @ 2.66GHz     | 1         | 2.38%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz     | 1         | 2.38%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz     | 1         | 2.38%   |
| Intel Core 2 CPU P8600 @ 2.40GHz         | 1         | 2.38%   |
| Intel Celeron N4100 CPU @ 1.10GHz        | 1         | 2.38%   |
| Intel Celeron M CPU 430 @ 1.73GHz        | 1         | 2.38%   |
| Intel Celeron CPU N3060 @ 1.60GHz        | 1         | 2.38%   |
| Intel Atom CPU Z3735F @ 1.33GHz          | 1         | 2.38%   |
| Intel Atom CPU N270 @ 1.60GHz            | 1         | 2.38%   |
| Intel Atom CPU N2600 @ 1.60GHz           | 1         | 2.38%   |
| Intel 13th Gen Core i7-1355U             | 1         | 2.38%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 1         | 2.38%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz  | 1         | 2.38%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz  | 1         | 2.38%   |
| AMD Ryzen 7 5800H with Radeon Graphics   | 1         | 2.38%   |
| AMD E1-1200 APU with Radeon HD Graphics  | 1         | 2.38%   |
| AMD A8-5550M APU with Radeon HD Graphics | 1         | 2.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 11        | 26.19%  |
| Other              | 6         | 14.29%  |
| Intel Core i7      | 4         | 9.52%   |
| Intel Core 2 Duo   | 4         | 9.52%   |
| Intel Core i3      | 3         | 7.14%   |
| Intel Core 2       | 3         | 7.14%   |
| Intel Atom         | 3         | 7.14%   |
| Intel Celeron      | 2         | 4.76%   |
| Intel Pentium Dual | 1         | 2.38%   |
| Intel Pentium      | 1         | 2.38%   |
| Intel Celeron M    | 1         | 2.38%   |
| AMD Ryzen 7        | 1         | 2.38%   |
| AMD E1             | 1         | 2.38%   |
| AMD A8             | 1         | 2.38%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 25        | 59.52%  |
| 4      | 10        | 23.81%  |
| 8      | 3         | 7.14%   |
| 1      | 2         | 4.76%   |
| 10     | 1         | 2.38%   |
| 6      | 1         | 2.38%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 42        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 28        | 66.67%  |
| 1      | 14        | 33.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 40        | 95.24%  |
| 32-bit         | 2         | 4.76%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 7         | 16.28%  |
| 0x1067a    | 5         | 11.63%  |
| 0x306a9    | 4         | 9.3%    |
| 0x206a7    | 4         | 9.3%    |
| 0x806ea    | 3         | 6.98%   |
| 0x806e9    | 2         | 4.65%   |
| 0x806d1    | 2         | 4.65%   |
| 0x306c3    | 2         | 4.65%   |
| 0x30678    | 2         | 4.65%   |
| 0x10676    | 2         | 4.65%   |
| 0xb06a3    | 1         | 2.33%   |
| 0x806ec    | 1         | 2.33%   |
| 0x706a1    | 1         | 2.33%   |
| 0x6e8      | 1         | 2.33%   |
| 0x406e3    | 1         | 2.33%   |
| 0x406c4    | 1         | 2.33%   |
| 0x106c2    | 1         | 2.33%   |
| 0x0a50000c | 1         | 2.33%   |
| 0x06001119 | 1         | 2.33%   |
| 0x0500010d | 1         | 2.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Penryn        | 7         | 16.67%  |
| KabyLake      | 6         | 14.29%  |
| IvyBridge     | 5         | 11.9%   |
| SandyBridge   | 4         | 9.52%   |
| Silvermont    | 3         | 7.14%   |
| TigerLake     | 2         | 4.76%   |
| Icelake       | 2         | 4.76%   |
| Haswell       | 2         | 4.76%   |
| Bonnell       | 2         | 4.76%   |
| Unknown       | 2         | 4.76%   |
| Zen 3         | 1         | 2.38%   |
| Skylake       | 1         | 2.38%   |
| Piledriver    | 1         | 2.38%   |
| P6            | 1         | 2.38%   |
| Goldmont plus | 1         | 2.38%   |
| Core          | 1         | 2.38%   |
| Bobcat        | 1         | 2.38%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 38        | 76%     |
| Nvidia           | 7         | 14%     |
| AMD              | 4         | 8%      |
| VIA Technologies | 1         | 2%      |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 13.46%  |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 9.62%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 7.69%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 5.77%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 3         | 5.77%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 3.85%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 3.85%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 3.85%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 2         | 3.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 3.85%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 3.85%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 1.92%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 1.92%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 1.92%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 1.92%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 1         | 1.92%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 1         | 1.92%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.92%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.92%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 1.92%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.92%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.92%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.92%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1         | 1.92%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 1         | 1.92%   |
| AMD Richland [Radeon HD 8550G]                                                           | 1         | 1.92%   |
| AMD Mars XTX [Radeon HD 8790M]                                                           | 1         | 1.92%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 1         | 1.92%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 31        | 72.09%  |
| Intel + Nvidia | 6         | 13.95%  |
| 1 x AMD        | 2         | 4.65%   |
| 2 x AMD        | 1         | 2.33%   |
| 1 x VIA        | 1         | 2.33%   |
| Intel + AMD    | 1         | 2.33%   |
| AMD + Nvidia   | 1         | 2.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 37        | 88.1%   |
| Unknown | 5         | 11.9%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 33        | 76.74%  |
| 1.01-2.0   | 6         | 13.95%  |
| 5.01-6.0   | 1         | 2.33%   |
| 3.01-4.0   | 1         | 2.33%   |
| 0.51-1.0   | 1         | 2.33%   |
| 0.01-0.5   | 1         | 2.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 9         | 21.95%  |
| Samsung Electronics     | 8         | 19.51%  |
| Lenovo                  | 5         | 12.2%   |
| AU Optronics            | 5         | 12.2%   |
| Chimei Innolux          | 4         | 9.76%   |
| BOE                     | 2         | 4.88%   |
| Sharp                   | 1         | 2.44%   |
| LG Philips              | 1         | 2.44%   |
| HKC                     | 1         | 2.44%   |
| Gateway                 | 1         | 2.44%   |
| Dell                    | 1         | 2.44%   |
| CPT                     | 1         | 2.44%   |
| Chi Mei Optoelectronics | 1         | 2.44%   |
| Acer                    | 1         | 2.44%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN4010 1280x800 261x163mm 12.1-inch                  | 4         | 9.52%   |
| Samsung Electronics LCD Monitor SDC414D 3456x2160 336x210mm 15.6-inch    | 2         | 4.76%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch              | 2         | 4.76%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 1         | 2.38%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 303x190mm 14.1-inch     | 1         | 2.38%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 1         | 2.38%   |
| Samsung Electronics LCD Monitor SEC374E 1024x600 223x125mm 10.1-inch     | 1         | 2.38%   |
| Samsung Electronics LCD Monitor SEC3052 1366x768 256x144mm 11.6-inch     | 1         | 2.38%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch    | 1         | 2.38%   |
| Samsung Electronics LC32G5xT SAM7080 2560x1440 698x393mm 31.5-inch       | 1         | 2.38%   |
| LG Philips LCD Monitor LPLAC00 1280x800 330x210mm 15.4-inch              | 1         | 2.38%   |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch             | 1         | 2.38%   |
| LG Display LCD Monitor LGD05D0 1920x1080 344x194mm 15.5-inch             | 1         | 2.38%   |
| LG Display LCD Monitor LGD03BD 1920x1080 276x156mm 12.5-inch             | 1         | 2.38%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch              | 1         | 2.38%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch              | 1         | 2.38%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch              | 1         | 2.38%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch              | 1         | 2.38%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 1         | 2.38%   |
| HKC LCD Monitor HKC3CFE 1920x1080 344x194mm 15.5-inch                    | 1         | 2.38%   |
| Gateway FPD1976W GWY0785 1440x900 410x257mm 19.1-inch                    | 1         | 2.38%   |
| Dell P3223DE DEL4295 2560x1440 698x393mm 31.5-inch                       | 1         | 2.38%   |
| Dell P2417H DELA0DB 1920x1080 527x296mm 23.8-inch                        | 1         | 2.38%   |
| CPT LCD Monitor CPT1401 1280x800 331x207mm 15.4-inch                     | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN15BA 1920x1080 344x194mm 15.5-inch         | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch          | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN1139 1366x768 256x144mm 11.6-inch          | 1         | 2.38%   |
| Chi Mei Optoelectronics LCD Monitor CMO1590 1366x768 344x194mm 15.5-inch | 1         | 2.38%   |
| BOE LCD Monitor BOE07C5 1920x1080 344x194mm 15.5-inch                    | 1         | 2.38%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                     | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO409D 1920x1080 382x215mm 17.3-inch           | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO215C 1366x768 256x144mm 11.6-inch            | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 1         | 2.38%   |
| Acer SA270 ACR0580 1920x1080 598x336mm 27.0-inch                         | 1         | 2.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 13        | 33.33%  |
| 1920x1080 (FHD)  | 11        | 28.21%  |
| 1280x800 (WXGA)  | 7         | 17.95%  |
| 1600x900 (HD+)   | 3         | 7.69%   |
| 3456x2160        | 2         | 5.13%   |
| 2560x1440 (QHD)  | 2         | 5.13%   |
| 1440x900 (WXGA+) | 1         | 2.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 17        | 40.48%  |
| 12     | 7         | 16.67%  |
| 14     | 6         | 14.29%  |
| 13     | 3         | 7.14%   |
| 31     | 2         | 4.76%   |
| 17     | 2         | 4.76%   |
| 11     | 2         | 4.76%   |
| 27     | 1         | 2.38%   |
| 24     | 1         | 2.38%   |
| 19     | 1         | 2.38%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 24        | 57.14%  |
| 201-300     | 10        | 23.81%  |
| 351-400     | 3         | 7.14%   |
| 601-700     | 2         | 4.76%   |
| 501-600     | 2         | 4.76%   |
| 401-500     | 1         | 2.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 27        | 72.97%  |
| 16/10 | 9         | 24.32%  |
| 3/2   | 1         | 2.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 17        | 40.48%  |
| 81-90          | 8         | 19.05%  |
| 61-70          | 7         | 16.67%  |
| 51-60          | 2         | 4.76%   |
| 351-500        | 2         | 4.76%   |
| 71-80          | 1         | 2.38%   |
| 301-350        | 1         | 2.38%   |
| 201-250        | 1         | 2.38%   |
| 151-200        | 1         | 2.38%   |
| 131-140        | 1         | 2.38%   |
| 121-130        | 1         | 2.38%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 20        | 50%     |
| 101-120       | 9         | 22.5%   |
| 51-100        | 7         | 17.5%   |
| More than 240 | 2         | 5%      |
| 161-240       | 2         | 5%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 36        | 83.72%  |
| 2     | 3         | 6.98%   |
| 0     | 3         | 6.98%   |
| 3     | 1         | 2.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 26        | 34.67%  |
| Qualcomm Atheros                | 20        | 26.67%  |
| Realtek Semiconductor           | 16        | 21.33%  |
| Qualcomm Atheros Communications | 6         | 8%      |
| Marvell Technology Group        | 2         | 2.67%   |
| VIA Technologies                | 1         | 1.33%   |
| Samsung Electronics             | 1         | 1.33%   |
| Qualcomm                        | 1         | 1.33%   |
| Microsoft                       | 1         | 1.33%   |
| Memorex                         | 1         | 1.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 9         | 10%     |
| Qualcomm Atheros AR9271 802.11n                                               | 5         | 5.56%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 5         | 5.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 5         | 5.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 4         | 4.44%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 4         | 4.44%   |
| Intel 82567LM Gigabit Network Connection                                      | 4         | 4.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 3         | 3.33%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 3         | 3.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 2         | 2.22%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2         | 2.22%   |
| Intel Wireless 8265 / 8275                                                    | 2         | 2.22%   |
| Intel Ethernet Connection (13) I219-V                                         | 2         | 2.22%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 2         | 2.22%   |
| Intel 82567LF Gigabit Network Connection                                      | 2         | 2.22%   |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 1         | 1.11%   |
| Samsung HSPA Modem                                                            | 1         | 1.11%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                      | 1         | 1.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.11%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                               | 1         | 1.11%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                      | 1         | 1.11%   |
| Realtek Killer E2600 GbE Controller                                           | 1         | 1.11%   |
| Qualcomm YUPIK-QRD _SN:AC1D5909                                               | 1         | 1.11%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 1.11%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                        | 1         | 1.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 1         | 1.11%   |
| Qualcomm Atheros Ubiquiti WiFiStationEXT 802.11n [Atheros AR9271]             | 1         | 1.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 1.11%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1         | 1.11%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 1.11%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                         | 1         | 1.11%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1         | 1.11%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1         | 1.11%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.11%   |
| Microsoft RTL8153 GigE [Surface Ethernet Adapter]                             | 1         | 1.11%   |
| Memorex 802.11n WLAN Adapter                                                  | 1         | 1.11%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                       | 1         | 1.11%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                          | 1         | 1.11%   |
| Intel Wireless 7265                                                           | 1         | 1.11%   |
| Intel Wireless 3165                                                           | 1         | 1.11%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 19        | 39.58%  |
| Qualcomm Atheros                | 18        | 37.5%   |
| Qualcomm Atheros Communications | 6         | 12.5%   |
| Realtek Semiconductor           | 4         | 8.33%   |
| Memorex                         | 1         | 2.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9271 802.11n                                               | 5         | 10.2%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 5         | 10.2%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 4         | 8.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 4         | 8.16%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 3         | 6.12%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 3         | 6.12%   |
| Intel Wireless 8265 / 8275                                                    | 2         | 4.08%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 2         | 4.08%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                      | 1         | 2.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 2.04%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                               | 1         | 2.04%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                      | 1         | 2.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 2.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 1         | 2.04%   |
| Qualcomm Atheros Ubiquiti WiFiStationEXT 802.11n [Atheros AR9271]             | 1         | 2.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 2.04%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1         | 2.04%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 2.04%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 2.04%   |
| Memorex 802.11n WLAN Adapter                                                  | 1         | 2.04%   |
| Intel Wireless 7265                                                           | 1         | 2.04%   |
| Intel Wireless 3165                                                           | 1         | 2.04%   |
| Intel WiFi Link 5100                                                          | 1         | 2.04%   |
| Intel Wi-Fi 6 AX201                                                           | 1         | 2.04%   |
| Intel Raptor Lake PCH CNVi WiFi                                               | 1         | 2.04%   |
| Intel Intel Centrino Wireless-N + WiMAX 6150                                  | 1         | 2.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 1         | 2.04%   |
| Intel Centrino Wireless-N 6150                                                | 1         | 2.04%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 2.04%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 17        | 42.5%   |
| Realtek Semiconductor    | 14        | 35%     |
| Qualcomm Atheros         | 4         | 10%     |
| Marvell Technology Group | 2         | 5%      |
| VIA Technologies         | 1         | 2.5%    |
| Qualcomm                 | 1         | 2.5%    |
| Microsoft                | 1         | 2.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 9         | 22.5%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 12.5%   |
| Intel 82567LM Gigabit Network Connection                               | 4         | 10%     |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2         | 5%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2         | 5%      |
| Intel Ethernet Connection (13) I219-V                                  | 2         | 5%      |
| Intel 82567LF Gigabit Network Connection                               | 2         | 5%      |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1         | 2.5%    |
| Realtek Killer E2600 GbE Controller                                    | 1         | 2.5%    |
| Qualcomm YUPIK-QRD _SN:AC1D5909                                        | 1         | 2.5%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 2.5%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 2.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 2.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 2.5%    |
| Microsoft RTL8153 GigE [Surface Ethernet Adapter]                      | 1         | 2.5%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 2.5%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 2.5%    |
| Intel Ethernet Connection I217-LM                                      | 1         | 2.5%    |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 2.5%    |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 2.5%    |
| Intel Ethernet Connection (23) I219-V                                  | 1         | 2.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 41        | 50.62%  |
| Ethernet | 39        | 48.15%  |
| Modem    | 1         | 1.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 29        | 69.05%  |
| Ethernet | 13        | 30.95%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 35        | 83.33%  |
| 1     | 6         | 14.29%  |
| 0     | 1         | 2.38%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 32        | 76.19%  |
| Yes  | 10        | 23.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 8         | 32%     |
| Broadcom                        | 5         | 20%     |
| Qualcomm Atheros Communications | 3         | 12%     |
| Toshiba                         | 2         | 8%      |
| Realtek Semiconductor           | 2         | 8%      |
| Lite-On Technology              | 1         | 4%      |
| IMC Networks                    | 1         | 4%      |
| Foxconn / Hon Hai               | 1         | 4%      |
| Cambridge Silicon Radio         | 1         | 4%      |
| Unknown                         | 1         | 4%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 6         | 24%     |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 12%     |
| Realtek Bluetooth Radio                             | 2         | 8%      |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 8%      |
| Intel Bluetooth wireless interface                  | 2         | 8%      |
| Toshiba RT Bluetooth Radio                          | 1         | 4%      |
| Toshiba Bluetooth Device                            | 1         | 4%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 4%      |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 4%      |
| IMC Networks Bluetooth Device                       | 1         | 4%      |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 4%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 4%      |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 4%      |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 4%      |
| Unknown                                             | 1         | 4%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 37        | 80.43%  |
| AMD                    | 3         | 6.52%   |
| Nvidia                 | 2         | 4.35%   |
| VIA Technologies       | 1         | 2.17%   |
| Realtek Semiconductor  | 1         | 2.17%   |
| Lenovo                 | 1         | 2.17%   |
| Generalplus Technology | 1         | 2.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 14.29%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 6         | 12.24%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 10.2%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 8.16%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 6.12%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 4.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 4.08%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 4.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 4.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 4.08%   |
| AMD FCH Azalia Controller                                                                         | 2         | 4.08%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 2.04%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 2.04%   |
| Lenovo ThinkPad Dock USB Audio                                                                    | 1         | 2.04%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 1         | 2.04%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 2.04%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 2.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 2.04%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 2.04%   |
| Generalplus Technology USB Audio Device                                                           | 1         | 2.04%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 2.04%   |
| AMD Ryzen HD Audio Controller                                                                     | 1         | 2.04%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 14        | 37.84%  |
| SK hynix            | 7         | 18.92%  |
| Micron Technology   | 5         | 13.51%  |
| Kingston            | 3         | 8.11%   |
| Unknown             | 2         | 5.41%   |
| TEXTORM             | 1         | 2.7%    |
| Ramaxel Technology  | 1         | 2.7%    |
| Qimonda             | 1         | 2.7%    |
| Hikvision           | 1         | 2.7%    |
| Crucial             | 1         | 2.7%    |
| A-DATA Technology   | 1         | 2.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s          | 3         | 7.89%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s          | 2         | 5.26%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                    | 1         | 2.63%   |
| Unknown RAM Module 1024MB SODIMM DRAM 533MT/s                  | 1         | 2.63%   |
| TEXTORM RAM TXS8G1M2666C19 8GB SODIMM DDR4 2667MT/s            | 1         | 2.63%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                   | 1         | 2.63%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s          | 1         | 2.63%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GiB SODIMM DDR3 2667MT/s        | 1         | 2.63%   |
| SK hynix RAM HMT41GS6AFR8A-H9 8192MB SODIMM DDR3 1333MT/s      | 1         | 2.63%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 2.63%   |
| SK hynix RAM HMA851S6CJR6N-UH 4GB SODIMM DDR4 2400MT/s         | 1         | 2.63%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 1         | 2.63%   |
| Samsung RAM Module 2GB Row Of Chips DDR3 1600MT/s              | 1         | 2.63%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s          | 1         | 2.63%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s          | 1         | 2.63%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s          | 1         | 2.63%   |
| Samsung RAM M471B5273CM0-CK0 4GB SODIMM DDR3 1600MT/s          | 1         | 2.63%   |
| Samsung RAM M471B5273CH0-CF8 4GB SODIMM DDR3 1333MT/s          | 1         | 2.63%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 1         | 2.63%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 1         | 2.63%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s          | 1         | 2.63%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s          | 1         | 2.63%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s        | 1         | 2.63%   |
| Qimonda RAM 64T512022EDL2.5A 4096MB SODIMM DDR 800MT/s         | 1         | 2.63%   |
| Micron RAM MT52L512M32D2PF-10 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 2.63%   |
| Micron RAM H6451U64F7066G 4GB SODIMM DDR3 1067MT/s             | 1         | 2.63%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s          | 1         | 2.63%   |
| Micron RAM 8ATF2G64HZ-3G2E2 16GB SODIMM DDR4 3200MT/s          | 1         | 2.63%   |
| Micron RAM 4ATF51264HZ-2G3H1R 4GB SODIMM DDR4 2400MT/s         | 1         | 2.63%   |
| Kingston RAM K821PJ-MID 16GB SODIMM DDR4 2400MT/s              | 1         | 2.63%   |
| Kingston RAM ASU1600S11-4G-EDEG 4GB SODIMM DDR3 1600MT/s       | 1         | 2.63%   |
| Kingston RAM 9905624-044.A00G 8GB SODIMM DDR4 2400MT/s         | 1         | 2.63%   |
| Hikvision RAM HKED4042BBA1D0ZA1 4GB SODIMM DDR4 2667MT/s       | 1         | 2.63%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 4199MT/s        | 1         | 2.63%   |
| A-DATA RAM Module 4096MB SODIMM DDR4 2400MT/s                  | 1         | 2.63%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 15        | 44.12%  |
| DDR3   | 14        | 41.18%  |
| SDRAM  | 1         | 2.94%   |
| LPDDR3 | 1         | 2.94%   |
| DRAM   | 1         | 2.94%   |
| DDR2   | 1         | 2.94%   |
| DDR    | 1         | 2.94%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 30        | 93.75%  |
| Row Of Chips | 2         | 6.25%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 14        | 38.89%  |
| 4096  | 14        | 38.89%  |
| 2048  | 4         | 11.11%  |
| 16384 | 3         | 8.33%   |
| 1024  | 1         | 2.78%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 10        | 27.78%  |
| 3200  | 8         | 22.22%  |
| 2667  | 4         | 11.11%  |
| 2400  | 4         | 11.11%  |
| 1333  | 3         | 8.33%   |
| 4199  | 1         | 2.78%   |
| 2133  | 1         | 2.78%   |
| 1867  | 1         | 2.78%   |
| 1067  | 1         | 2.78%   |
| 975   | 1         | 2.78%   |
| 800   | 1         | 2.78%   |
| 533   | 1         | 2.78%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| HP LaserJet Pro 4001 | 1         | 100%    |

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
| Chicony Electronics                    | 9         | 28.13%  |
| Sunplus Innovation Technology          | 4         | 12.5%   |
| Lenovo                                 | 4         | 12.5%   |
| Microdia                               | 3         | 9.38%   |
| Bison Electronics                      | 2         | 6.25%   |
| Z-Star Microelectronics                | 1         | 3.13%   |
| Realtek Semiconductor                  | 1         | 3.13%   |
| Quanta                                 | 1         | 3.13%   |
| Luxvisions Innotech Limited            | 1         | 3.13%   |
| Logitech                               | 1         | 3.13%   |
| Importek                               | 1         | 3.13%   |
| IMC Networks                           | 1         | 3.13%   |
| GoPro                                  | 1         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.13%   |
| Alcor Micro                            | 1         | 3.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Lenovo Integrated Webcam                                     | 4         | 12.5%   |
| Z-Star Webcam                                                | 1         | 3.13%   |
| Sunplus Laptop_Integrated_Webcam_1.3M                        | 1         | 3.13%   |
| Sunplus Integrated_Webcam_HD                                 | 1         | 3.13%   |
| Sunplus HD WebCam                                            | 1         | 3.13%   |
| Sunplus Asus Webcam                                          | 1         | 3.13%   |
| Realtek Lenovo EasyCamera                                    | 1         | 3.13%   |
| Quanta HD User Facing                                        | 1         | 3.13%   |
| Microdia Integrated_Webcam_HD                                | 1         | 3.13%   |
| Microdia Integrated_Webcam_1.3M                              | 1         | 3.13%   |
| Microdia Integrated Webcam HD                                | 1         | 3.13%   |
| Luxvisions Innotech Limited HP HD Camera                     | 1         | 3.13%   |
| Logitech C922 Pro Stream Webcam                              | 1         | 3.13%   |
| Importek TOSHIBA Web Camera                                  | 1         | 3.13%   |
| IMC Networks UVC VGA Webcam                                  | 1         | 3.13%   |
| GoPro HERO4 Black                                            | 1         | 3.13%   |
| Chicony UVC 1.00 device HD UVC WebCam                        | 1         | 3.13%   |
| Chicony USB2.0 VGA UVC WebCam                                | 1         | 3.13%   |
| Chicony TOSHIBA Web Camera                                   | 1         | 3.13%   |
| Chicony Thinkpad T430 camera                                 | 1         | 3.13%   |
| Chicony Integrated Camera (1920x1080)                        | 1         | 3.13%   |
| Chicony integrated camera                                    | 1         | 3.13%   |
| Chicony HP Wide Vision HD Camera                             | 1         | 3.13%   |
| Chicony HP Webcam                                            | 1         | 3.13%   |
| Chicony Chicony USB2.0 Camera                                | 1         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 1         | 3.13%   |
| Bison ThinkPad Integrated Camera                             | 1         | 3.13%   |
| Bison Integrated Camera                                      | 1         | 3.13%   |
| Alcor Micro Asus Integrated Webcam                           | 1         | 3.13%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor    | Notebooks | Percent |
|-----------|-----------|---------|
| Synaptics | 1         | 50%     |
| AuthenTec | 1         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 50%     |
| AuthenTec AES2810                                        | 1         | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 3         | 60%     |
| Upek     | 2         | 40%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 2         | 40%     |
| Broadcom BCM5880 Secure Applications Processor             | 2         | 40%     |
| Broadcom 5880                                              | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 23        | 53.49%  |
| 1     | 15        | 34.88%  |
| 2     | 5         | 11.63%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 12        | 54.55%  |
| Chipcard              | 5         | 22.73%  |
| Fingerprint reader    | 2         | 9.09%   |
| Net/wireless          | 1         | 4.55%   |
| Multimedia controller | 1         | 4.55%   |
| Bluetooth             | 1         | 4.55%   |

