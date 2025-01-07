CentOS 9 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------

A project to collect tested hardware configurations for CentOS 9.

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

Total: 51

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Positivo B... | VJFE41F11X-XXXXXX           | [0efd10fc40](https://linux-hardware.org/?probe=0efd10fc40) | Nov 21, 2024 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | [e6d4792686](https://linux-hardware.org/?probe=e6d4792686) | Oct 09, 2024 |
| Dell          | Latitude 3490               | [e0b48e8d4f](https://linux-hardware.org/?probe=e0b48e8d4f) | Sep 07, 2024 |
| Lenovo        | ThinkPad T470p 20J7002GP... | [4f6dfce3d8](https://linux-hardware.org/?probe=4f6dfce3d8) | Aug 23, 2024 |
| Lenovo        | ThinkPad W510 431967G       | [58cb012163](https://linux-hardware.org/?probe=58cb012163) | Aug 06, 2024 |
| Dell          | Inspiron 3576               | [f14330846e](https://linux-hardware.org/?probe=f14330846e) | Aug 02, 2024 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [786c05a4a8](https://linux-hardware.org/?probe=786c05a4a8) | Jul 15, 2024 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [2431de91a7](https://linux-hardware.org/?probe=2431de91a7) | Jul 15, 2024 |
| Google        | Lick                        | [f8ad9ee153](https://linux-hardware.org/?probe=f8ad9ee153) | Jul 12, 2024 |
| HP            | Laptop 17-cp0xxx            | [e7c9470e44](https://linux-hardware.org/?probe=e7c9470e44) | Jun 23, 2024 |
| HP            | Laptop 17-cp0xxx            | [3b70ac5b2a](https://linux-hardware.org/?probe=3b70ac5b2a) | Jun 23, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [994aae0769](https://linux-hardware.org/?probe=994aae0769) | Apr 21, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [e26cecc411](https://linux-hardware.org/?probe=e26cecc411) | Apr 21, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [05372f86e5](https://linux-hardware.org/?probe=05372f86e5) | Apr 10, 2024 |
| Lenovo        | ThinkPad X390 20Q00039CD    | [9e8475784d](https://linux-hardware.org/?probe=9e8475784d) | Apr 05, 2024 |
| Micro Comp... | Venus series                | [ec0a83d39a](https://linux-hardware.org/?probe=ec0a83d39a) | Mar 27, 2024 |
| Notebook      | P377SM-A                    | [c073b6897b](https://linux-hardware.org/?probe=c073b6897b) | Mar 05, 2024 |
| Dell          | Precision 5560              | [e500714178](https://linux-hardware.org/?probe=e500714178) | Feb 22, 2024 |
| Dell          | Precision 5520              | [47f7336949](https://linux-hardware.org/?probe=47f7336949) | Jan 30, 2024 |
| Dell          | G5 5505                     | [fd284cda8a](https://linux-hardware.org/?probe=fd284cda8a) | Jan 04, 2024 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [ecc33f393d](https://linux-hardware.org/?probe=ecc33f393d) | Nov 22, 2023 |
| Dell          | Vostro 5402                 | [f23d8804a7](https://linux-hardware.org/?probe=f23d8804a7) | Oct 11, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [dfcebaef82](https://linux-hardware.org/?probe=dfcebaef82) | Aug 09, 2023 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | [61408603be](https://linux-hardware.org/?probe=61408603be) | Apr 21, 2023 |
| ASUSTek       | N751JK                      | [d148f91b52](https://linux-hardware.org/?probe=d148f91b52) | Mar 15, 2023 |
| ASUSTek       | Q550LF                      | [793bf0d1d8](https://linux-hardware.org/?probe=793bf0d1d8) | Mar 06, 2023 |
| ASUSTek       | N751JK                      | [a67a4d078f](https://linux-hardware.org/?probe=a67a4d078f) | Jan 21, 2023 |
| ASUSTek       | N751JK                      | [259556fd6f](https://linux-hardware.org/?probe=259556fd6f) | Jan 11, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | [b9522e3683](https://linux-hardware.org/?probe=b9522e3683) | Jan 02, 2023 |
| Lenovo        | ThinkPad T430 2347DE9       | [7b4305ce5a](https://linux-hardware.org/?probe=7b4305ce5a) | Dec 27, 2022 |
| Lenovo        | ThinkPad T430 2347DE9       | [afc91c5da0](https://linux-hardware.org/?probe=afc91c5da0) | Dec 24, 2022 |
| Acer          | Swift SF314-512             | [b2aac5194c](https://linux-hardware.org/?probe=b2aac5194c) | Dec 06, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [b981adc21a](https://linux-hardware.org/?probe=b981adc21a) | Nov 07, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | [8bd50f112b](https://linux-hardware.org/?probe=8bd50f112b) | Oct 15, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | [88497baf29](https://linux-hardware.org/?probe=88497baf29) | Oct 15, 2022 |
| Acer          | Aspire E1-570G              | [2293724ae2](https://linux-hardware.org/?probe=2293724ae2) | Sep 19, 2022 |
| Acer          | Aspire E1-570G              | [09db514840](https://linux-hardware.org/?probe=09db514840) | Sep 19, 2022 |
| Lenovo        | ThinkPad T430 2349DG5       | [740898521d](https://linux-hardware.org/?probe=740898521d) | Aug 27, 2022 |
| Timi          | Mi NoteBook Horizon Edit... | [52a0cb298b](https://linux-hardware.org/?probe=52a0cb298b) | Aug 09, 2022 |
| Lenovo        | G410 20237                  | [daea3239f0](https://linux-hardware.org/?probe=daea3239f0) | Aug 05, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [29f2cd44d5](https://linux-hardware.org/?probe=29f2cd44d5) | Jun 11, 2022 |
| HP            | ProBook 470 G2              | [9a331b90a5](https://linux-hardware.org/?probe=9a331b90a5) | May 19, 2022 |
| HP            | ProBook 470 G2              | [4c3a3b2de2](https://linux-hardware.org/?probe=4c3a3b2de2) | May 17, 2022 |
| MSI           | Katana GF76 12UE            | [460e78b93a](https://linux-hardware.org/?probe=460e78b93a) | May 15, 2022 |
| HP            | EliteBook 840 G3            | [a7fb96d9aa](https://linux-hardware.org/?probe=a7fb96d9aa) | May 13, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U5S... | [228ec1a5f7](https://linux-hardware.org/?probe=228ec1a5f7) | Apr 24, 2022 |
| Timi          | RedmiBook 16                | [bef46c5065](https://linux-hardware.org/?probe=bef46c5065) | Mar 20, 2022 |
| Lenovo        | G580 20150                  | [1f84b1e42d](https://linux-hardware.org/?probe=1f84b1e42d) | Mar 11, 2022 |
| Lenovo        | ThinkPad T460s 20FAS5WX0... | [6fa180d5fa](https://linux-hardware.org/?probe=6fa180d5fa) | Feb 06, 2022 |
| HP            | EliteBook 840 G1            | [cf90d5430c](https://linux-hardware.org/?probe=cf90d5430c) | Feb 04, 2022 |
| Acer          | Aspire 5740                 | [0c661cb2d6](https://linux-hardware.org/?probe=0c661cb2d6) | Nov 12, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Notebooks | Percent |
|-----------------------------|-----------|---------|
| 5.14.0-432.el9.x86_64       | 3         | 7.32%   |
| 5.14.0-86.el9.x86_64        | 2         | 4.88%   |
| 5.14.0-134.el9.x86_64       | 2         | 4.88%   |
| 6.10.6-1.el9.elrepo.x86_64  | 1         | 2.44%   |
| 6.1.8-1.el9.elrepo.x86_64   | 1         | 2.44%   |
| 6.1.102-1.el9.elrepo.x86_64 | 1         | 2.44%   |
| 6.1.1                       | 1         | 2.44%   |
| 5.14.0-78.el9.x86_64        | 1         | 2.44%   |
| 5.14.0-71.el9.x86_64        | 1         | 2.44%   |
| 5.14.0-66.el9.x86_64        | 1         | 2.44%   |
| 5.14.0-52.el9.x86_64        | 1         | 2.44%   |
| 5.14.0-516.el9.x86_64       | 1         | 2.44%   |
| 5.14.0-514.el9.x86_64       | 1         | 2.44%   |
| 5.14.0-496.el9.x86_64       | 1         | 2.44%   |
| 5.14.0-474.el9.x86_64       | 1         | 2.44%   |
| 5.14.0-460.el9.x86_64       | 1         | 2.44%   |
| 5.14.0-44.el9.x86_64        | 1         | 2.44%   |
| 5.14.0-437.el9.x86_64       | 1         | 2.44%   |
| 5.14.0-435.el9.x86_64       | 1         | 2.44%   |
| 5.14.0-427.el9.x86_64       | 1         | 2.44%   |
| 5.14.0-419.el9.x86_64       | 1         | 2.44%   |
| 5.14.0-410.el9.x86_64       | 1         | 2.44%   |
| 5.14.0-402.el9.x86_64       | 1         | 2.44%   |
| 5.14.0-383.el9.x86_64       | 1         | 2.44%   |
| 5.14.0-373.el9.x86_64       | 1         | 2.44%   |
| 5.14.0-350.el9.x86_64       | 1         | 2.44%   |
| 5.14.0-299.el9.x86_64       | 1         | 2.44%   |
| 5.14.0-282.el9.x86_64       | 1         | 2.44%   |
| 5.14.0-226.el9.x86_64       | 1         | 2.44%   |
| 5.14.0-214.el9.x86_64       | 1         | 2.44%   |
| 5.14.0-202.el9.x86_64       | 1         | 2.44%   |
| 5.14.0-183.el9.x86_64       | 1         | 2.44%   |
| 5.14.0-171.el9.x86_64       | 1         | 2.44%   |
| 5.14.0-163.el9.x86_64       | 1         | 2.44%   |
| 5.14.0-148.el9.x86_64       | 1         | 2.44%   |
| 5.14.0-12.el9.x86_64        | 1         | 2.44%   |
| 5.14.0-105.el9.x86_64       | 1         | 2.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.0  | 37        | 90.24%  |
| 6.10.6  | 1         | 2.44%   |
| 6.1.8   | 1         | 2.44%   |
| 6.1.102 | 1         | 2.44%   |
| 6.1.1   | 1         | 2.44%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14    | 37        | 90.24%  |
| 6.1     | 3         | 7.32%   |
| 6.10    | 1         | 2.44%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 40        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GNOME   | 36        | 90%     |
| KDE5    | 2         | 5%      |
| MATE    | 1         | 2.5%    |
| Unknown | 1         | 2.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 32        | 80%     |
| X11     | 7         | 17.5%   |
| Tty     | 1         | 2.5%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM     | 19        | 47.5%   |
| Unknown | 18        | 45%     |
| LightDM | 2         | 5%      |
| SDDM    | 1         | 2.5%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 28        | 70%     |
| ru_RU | 3         | 7.5%    |
| pt_BR | 2         | 5%      |
| de_DE | 2         | 5%      |
| zh_CN | 1         | 2.5%    |
| it_IT | 1         | 2.5%    |
| fr_FR | 1         | 2.5%    |
| en_IN | 1         | 2.5%    |
| C     | 1         | 2.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 33        | 82.5%   |
| BIOS | 7         | 17.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Xfs   | 35        | 87.5%   |
| Ext4  | 4         | 10%     |
| Tmpfs | 1         | 2.5%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 18        | 45%     |
| Unknown | 16        | 40%     |
| MBR     | 6         | 15%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 33        | 82.5%   |
| Yes       | 7         | 17.5%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 29        | 72.5%   |
| Yes       | 11        | 27.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Lenovo                           | 16        | 40%     |
| Dell                             | 6         | 15%     |
| Hewlett-Packard                  | 4         | 10%     |
| ASUSTek Computer                 | 3         | 7.5%    |
| Acer                             | 3         | 7.5%    |
| Timi                             | 2         | 5%      |
| Samsung Electronics              | 1         | 2.5%    |
| Razer                            | 1         | 2.5%    |
| Positivo Bahia - VAIO            | 1         | 2.5%    |
| Notebook                         | 1         | 2.5%    |
| MSI                              | 1         | 2.5%    |
| Micro Computer (HK) Tech Limited | 1         | 2.5%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Timi RedmiBook 16                           | 1         | 2.5%    |
| Timi Mi NoteBook Horizon Edition 14         | 1         | 2.5%    |
| Samsung 355V4C/356V4C/3445VC/3545VC         | 1         | 2.5%    |
| Razer Blade 15 (2022) - RZ09-0421           | 1         | 2.5%    |
| Positivo Bahia - VAIO VJFE41F11X-XXXXXX     | 1         | 2.5%    |
| Notebook P377SM-A                           | 1         | 2.5%    |
| MSI Katana GF76 12UE                        | 1         | 2.5%    |
| Micro (HK) Tech Limited Venus series        | 1         | 2.5%    |
| Lenovo Yoga S740-14IIL 81RS                 | 1         | 2.5%    |
| Lenovo V15 G2 ITL 82KB                      | 1         | 2.5%    |
| Lenovo ThinkPad X390 20Q00039CD             | 1         | 2.5%    |
| Lenovo ThinkPad X1 Carbon Gen 10 21CBCTO1WW | 1         | 2.5%    |
| Lenovo ThinkPad W510 431967G                | 1         | 2.5%    |
| Lenovo ThinkPad T470p 20J7002GPH            | 1         | 2.5%    |
| Lenovo ThinkPad T460s 20FAS5WX00            | 1         | 2.5%    |
| Lenovo ThinkPad T430 2349DG5                | 1         | 2.5%    |
| Lenovo ThinkPad T430 2347DE9                | 1         | 2.5%    |
| Lenovo ThinkPad T15 Gen 1 20S7S43600        | 1         | 2.5%    |
| Lenovo ThinkPad L14 Gen 1 20U5S0NT00        | 1         | 2.5%    |
| Lenovo Legion 5P 15IMH05H 82AW              | 1         | 2.5%    |
| Lenovo IdeaPad S145-15IWL 81S9              | 1         | 2.5%    |
| Lenovo IdeaPad 5 14ITL05 82FE               | 1         | 2.5%    |
| Lenovo G580 20150                           | 1         | 2.5%    |
| Lenovo G410 20237                           | 1         | 2.5%    |
| HP Pavilion Gaming Laptop 15-ec0xxx         | 1         | 2.5%    |
| HP Laptop 17-cp0xxx                         | 1         | 2.5%    |
| HP EliteBook 840 G3                         | 1         | 2.5%    |
| HP EliteBook 840 G1                         | 1         | 2.5%    |
| Dell Vostro 5402                            | 1         | 2.5%    |
| Dell Precision 5560                         | 1         | 2.5%    |
| Dell Precision 5520                         | 1         | 2.5%    |
| Dell Latitude 3490                          | 1         | 2.5%    |
| Dell Inspiron 3576                          | 1         | 2.5%    |
| Dell G5 5505                                | 1         | 2.5%    |
| ASUS VivoBook_ASUSLaptop X412FA_A412FA      | 1         | 2.5%    |
| ASUS Q550LF                                 | 1         | 2.5%    |
| ASUS N751JK                                 | 1         | 2.5%    |
| Acer Swift SF314-512                        | 1         | 2.5%    |
| Acer Aspire E1-570G                         | 1         | 2.5%    |
| Acer Aspire 5740                            | 1         | 2.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Lenovo ThinkPad                         | 9         | 22.5%   |
| Lenovo IdeaPad                          | 2         | 5%      |
| HP EliteBook                            | 2         | 5%      |
| Dell Precision                          | 2         | 5%      |
| Acer Aspire                             | 2         | 5%      |
| Timi RedmiBook                          | 1         | 2.5%    |
| Timi Mi                                 | 1         | 2.5%    |
| Samsung 355V4C                          | 1         | 2.5%    |
| Razer Blade                             | 1         | 2.5%    |
| Positivo Bahia - VAIO VJFE41F11X-XXXXXX | 1         | 2.5%    |
| Notebook P377SM-A                       | 1         | 2.5%    |
| MSI Katana                              | 1         | 2.5%    |
| Micro (HK) Tech Limited Venus           | 1         | 2.5%    |
| Lenovo Yoga                             | 1         | 2.5%    |
| Lenovo V15                              | 1         | 2.5%    |
| Lenovo Legion                           | 1         | 2.5%    |
| Lenovo G580                             | 1         | 2.5%    |
| Lenovo G410                             | 1         | 2.5%    |
| HP Pavilion                             | 1         | 2.5%    |
| HP Laptop                               | 1         | 2.5%    |
| Dell Vostro                             | 1         | 2.5%    |
| Dell Latitude                           | 1         | 2.5%    |
| Dell Inspiron                           | 1         | 2.5%    |
| Dell G5                                 | 1         | 2.5%    |
| ASUS VivoBook                           | 1         | 2.5%    |
| ASUS Q550LF                             | 1         | 2.5%    |
| ASUS N751JK                             | 1         | 2.5%    |
| Acer Swift                              | 1         | 2.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 9         | 22.5%   |
| 2019 | 5         | 12.5%   |
| 2013 | 5         | 12.5%   |
| 2021 | 4         | 10%     |
| 2017 | 3         | 7.5%    |
| 2012 | 3         | 7.5%    |
| 2022 | 2         | 5%      |
| 2016 | 2         | 5%      |
| 2014 | 2         | 5%      |
| 2023 | 1         | 2.5%    |
| 2018 | 1         | 2.5%    |
| 2015 | 1         | 2.5%    |
| 2010 | 1         | 2.5%    |
| 2009 | 1         | 2.5%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 40        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 38        | 95%     |
| Enabled  | 2         | 5%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 40        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 17        | 42.5%   |
| 8.01-16.0   | 12        | 30%     |
| 32.01-64.0  | 7         | 17.5%   |
| 3.01-4.0    | 2         | 5%      |
| 24.01-32.0  | 1         | 2.5%    |
| 64.01-256.0 | 1         | 2.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 21        | 52.5%   |
| 4.01-8.0   | 9         | 22.5%   |
| 3.01-4.0   | 6         | 15%     |
| 1.01-2.0   | 2         | 5%      |
| 16.01-24.0 | 1         | 2.5%    |
| 0.51-1.0   | 1         | 2.5%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 28        | 70%     |
| 2      | 9         | 22.5%   |
| 5      | 1         | 2.5%    |
| 4      | 1         | 2.5%    |
| 3      | 1         | 2.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 31        | 77.5%   |
| Yes       | 9         | 22.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 31        | 77.5%   |
| No        | 9         | 22.5%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 37        | 92.5%   |
| No        | 3         | 7.5%    |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 9         | 22.5%   |
| Germany     | 3         | 7.5%    |
| China       | 3         | 7.5%    |
| Brazil      | 3         | 7.5%    |
| Italy       | 2         | 5%      |
| Finland     | 2         | 5%      |
| Canada      | 2         | 5%      |
| Vietnam     | 1         | 2.5%    |
| Uzbekistan  | 1         | 2.5%    |
| Ukraine     | 1         | 2.5%    |
| Switzerland | 1         | 2.5%    |
| Russia      | 1         | 2.5%    |
| Poland      | 1         | 2.5%    |
| Philippines | 1         | 2.5%    |
| Norway      | 1         | 2.5%    |
| Netherlands | 1         | 2.5%    |
| Kazakhstan  | 1         | 2.5%    |
| India       | 1         | 2.5%    |
| France      | 1         | 2.5%    |
| Colombia    | 1         | 2.5%    |
| Chile       | 1         | 2.5%    |
| Australia   | 1         | 2.5%    |
| Argentina   | 1         | 2.5%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Beijing          | 3         | 7.32%   |
| Yakima           | 1         | 2.44%   |
| Vicenza          | 1         | 2.44%   |
| Tromsø          | 1         | 2.44%   |
| Tashkent         | 1         | 2.44%   |
| Sykesville       | 1         | 2.44%   |
| Soest            | 1         | 2.44%   |
| Schemmerhofen    | 1         | 2.44%   |
| Sao Paulo        | 1         | 2.44%   |
| Sanford          | 1         | 2.44%   |
| Ruda Śląska    | 1         | 2.44%   |
| Ribeirao Preto   | 1         | 2.44%   |
| Quitman          | 1         | 2.44%   |
| Puente Alto      | 1         | 2.44%   |
| Plano            | 1         | 2.44%   |
| Persan           | 1         | 2.44%   |
| Offenbach        | 1         | 2.44%   |
| Mumbai           | 1         | 2.44%   |
| Moscow           | 1         | 2.44%   |
| L'Isle-Adam      | 1         | 2.44%   |
| Kramatorsk       | 1         | 2.44%   |
| Kemi             | 1         | 2.44%   |
| Imus             | 1         | 2.44%   |
| Ho Chi Minh City | 1         | 2.44%   |
| Helsinki         | 1         | 2.44%   |
| Gravataí        | 1         | 2.44%   |
| Fort Thomas      | 1         | 2.44%   |
| Don Torcuato     | 1         | 2.44%   |
| Chicago          | 1         | 2.44%   |
| Canberra         | 1         | 2.44%   |
| Bristow          | 1         | 2.44%   |
| Bogotá          | 1         | 2.44%   |
| Birmensdorf      | 1         | 2.44%   |
| Berlin           | 1         | 2.44%   |
| Battle Creek     | 1         | 2.44%   |
| Barrie           | 1         | 2.44%   |
| Almaty           | 1         | 2.44%   |
| Airdrie          | 1         | 2.44%   |
| Adelfia          | 1         | 2.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 20     | 26.92%  |
| SK hynix            | 5         | 5      | 9.62%   |
| Kingston            | 4         | 5      | 7.69%   |
| Seagate             | 3         | 3      | 5.77%   |
| Micron Technology   | 3         | 3      | 5.77%   |
| Intel               | 3         | 3      | 5.77%   |
| HGST                | 3         | 4      | 5.77%   |
| WDC                 | 2         | 2      | 3.85%   |
| LITEON              | 2         | 2      | 3.85%   |
| VICKTER             | 1         | 1      | 1.92%   |
| Unknown             | 1         | 1      | 1.92%   |
| Union Memory        | 1         | 1      | 1.92%   |
| Toshiba             | 1         | 1      | 1.92%   |
| SPCC                | 1         | 1      | 1.92%   |
| SanDisk             | 1         | 2      | 1.92%   |
| Phison Electronics  | 1         | 1      | 1.92%   |
| HS-SSD-E100         | 1         | 1      | 1.92%   |
| Hjwdz               | 1         | 1      | 1.92%   |
| Hewlett-Packard     | 1         | 1      | 1.92%   |
| ETOPSO              | 1         | 1      | 1.92%   |
| Crucial             | 1         | 1      | 1.92%   |
| ASMT                | 1         | 1      | 1.92%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 3         | 5.45%   |
| SK hynix BC511 512GB                                 | 2         | 3.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 2         | 3.64%   |
| Samsung MZNLH512HALU-00000 512GB SSD                 | 2         | 3.64%   |
| Micron 2450_MTFDKBA512TFK 512GB                      | 2         | 3.64%   |
| WDC WD6400BEVT-22A0RT0 640GB                         | 1         | 1.82%   |
| WDC WD5000LPLX-60ZNTT1 500GB                         | 1         | 1.82%   |
| VICKTER SSD 128GB                                    | 1         | 1.82%   |
| Unknown MMC Card  7GB                                | 1         | 1.82%   |
| Union Memory UMIS RPJTJ256MEE1OWX 256GB              | 1         | 1.82%   |
| Toshiba MQ04ABF100 1TB                               | 1         | 1.82%   |
| SPCC Solid State Disk 120GB                          | 1         | 1.82%   |
| SK hynix PC711 NVMe 1TB                              | 1         | 1.82%   |
| SK hynix NVMe SSD Drive 256GB                        | 1         | 1.82%   |
| SK hynix BC501 NVMe 256GB                            | 1         | 1.82%   |
| Seagate ST500LT012-9WS142 500GB                      | 1         | 1.82%   |
| Seagate ST1000LM035-1RK172 1TB                       | 1         | 1.82%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 1         | 1.82%   |
| SanDisk Portable SSD 2TB                             | 1         | 1.82%   |
| Samsung SSD 870 EVO 1TB                              | 1         | 1.82%   |
| Samsung SSD 850 PRO 1TB                              | 1         | 1.82%   |
| Samsung SSD 850 EVO mSATA 1TB                        | 1         | 1.82%   |
| Samsung SSD 840 250GB                                | 1         | 1.82%   |
| Samsung PSSD T7 1TB                                  | 1         | 1.82%   |
| Samsung NVMe SSD Drive 1TB                           | 1         | 1.82%   |
| Samsung MZVLQ512HBLU-00BH1 512GB                     | 1         | 1.82%   |
| Samsung MZALQ512HBLU-00BL2 512GB                     | 1         | 1.82%   |
| Samsung MZALQ512HALU-000L2 512GB                     | 1         | 1.82%   |
| Samsung MMCRE28G8MXP-0VBL1 128GB SSD                 | 1         | 1.82%   |
| Phison PS5013 E13 NVMe Controller 512GB              | 1         | 1.82%   |
| Micron 2200S NVMe 512GB                              | 1         | 1.82%   |
| LITEON IT LST-32S9G-HP 32GB SSD                      | 1         | 1.82%   |
| LITEON CV3-SD128 128GB SSD                           | 1         | 1.82%   |
| Kingston SKC600/ 512GB SSD                           | 1         | 1.82%   |
| Kingston SH103S3240G 240GB SSD                       | 1         | 1.82%   |
| Kingston SA400S37240G 240GB SSD                      | 1         | 1.82%   |
| Kingston RBU-SC100S37128GD 128GB SSD                 | 1         | 1.82%   |
| Intel SSDSCKKF256H6L 256GB                           | 1         | 1.82%   |
| Intel SSDPEKNW512G8L 512GB                           | 1         | 1.82%   |
| Intel SSD 660P Series 1024GB                         | 1         | 1.82%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 30%     |
| HGST    | 3         | 4      | 30%     |
| WDC     | 2         | 2      | 20%     |
| Toshiba | 1         | 1      | 10%     |
| ASMT    | 1         | 1      | 10%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 11     | 30%     |
| Kingston            | 4         | 5      | 20%     |
| LITEON              | 2         | 2      | 10%     |
| VICKTER             | 1         | 1      | 5%      |
| SPCC                | 1         | 1      | 5%      |
| SanDisk             | 1         | 2      | 5%      |
| Intel               | 1         | 1      | 5%      |
| HS-SSD-E100         | 1         | 1      | 5%      |
| Hewlett-Packard     | 1         | 1      | 5%      |
| ETOPSO              | 1         | 1      | 5%      |
| Crucial             | 1         | 1      | 5%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 19        | 21     | 39.58%  |
| SSD     | 17        | 27     | 35.42%  |
| HDD     | 10        | 11     | 20.83%  |
| MMC     | 1         | 1      | 2.08%   |
| Unknown | 1         | 1      | 2.08%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 23        | 33     | 50%     |
| NVMe | 19        | 21     | 41.3%   |
| SAS  | 3         | 6      | 6.52%   |
| MMC  | 1         | 1      | 2.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 15        | 17     | 51.72%  |
| 0.51-1.0   | 12        | 17     | 41.38%  |
| 1.01-2.0   | 2         | 4      | 6.9%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 15        | 36.59%  |
| 501-1000       | 10        | 24.39%  |
| 251-500        | 9         | 21.95%  |
| 1001-2000      | 2         | 4.88%   |
| 51-100         | 2         | 4.88%   |
| More than 3000 | 1         | 2.44%   |
| 2001-3000      | 1         | 2.44%   |
| 1-20           | 1         | 2.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 23        | 56.1%   |
| 101-250   | 6         | 14.63%  |
| 251-500   | 5         | 12.2%   |
| 51-100    | 3         | 7.32%   |
| 21-50     | 2         | 4.88%   |
| 1001-2000 | 1         | 2.44%   |
| 501-1000  | 1         | 2.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD5000LPLX-60ZNTT1 500GB      | 1         | 1      | 33.33%  |
| Seagate ST500LT012-9WS142 500GB   | 1         | 1      | 33.33%  |
| Samsung Electronics SSD 840 250GB | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 33.33%  |
| Seagate             | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 2      | 66.67%  |
| SSD  | 1         | 1      | 33.33%  |

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
| Works    | 21        | 27     | 48.84%  |
| Detected | 19        | 31     | 44.19%  |
| Malfunc  | 3         | 3      | 6.98%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 26        | 56.52%  |
| Samsung Electronics     | 8         | 17.39%  |
| SK hynix                | 5         | 10.87%  |
| Micron Technology       | 3         | 6.52%   |
| AMD                     | 2         | 4.35%   |
| Union Memory (Shenzhen) | 1         | 2.17%   |
| Phison Electronics      | 1         | 2.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 4         | 7.84%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4         | 7.84%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 7.84%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 5.88%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 2         | 3.92%   |
| SK hynix BC511 NVMe SSD                                                        | 2         | 3.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 3.92%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 2         | 3.92%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 3.92%   |
| Intel SSD 660P Series                                                          | 2         | 3.92%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 3.92%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 3.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 3.92%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 3.92%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 2         | 3.92%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 256GB                          | 1         | 1.96%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 1.96%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 1         | 1.96%   |
| Micron 2200S NVMe SSD [Cassandra]                                              | 1         | 1.96%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 1.96%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.96%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.96%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 1.96%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 1         | 1.96%   |
| Intel Alder Lake-N SATA AHCI Controller                                        | 1         | 1.96%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 1         | 1.96%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.96%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 1         | 1.96%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 1.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 24        | 50%     |
| NVMe | 19        | 39.58%  |
| RAID | 4         | 8.33%   |
| IDE  | 1         | 2.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 34        | 85%     |
| AMD    | 6         | 15%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 5%      |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 5%      |
| Intel N100                                    | 1         | 2.5%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 2.5%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 2.5%    |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 2.5%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 2.5%    |
| Intel Core i7-4910MQ CPU @ 2.90GHz            | 1         | 2.5%    |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 2.5%    |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 2.5%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 2.5%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 2.5%    |
| Intel Core i7 CPU Q 820 @ 1.73GHz             | 1         | 2.5%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 2.5%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 2.5%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 2.5%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 2.5%    |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 2.5%    |
| Intel Core i5-3380M CPU @ 2.90GHz             | 1         | 2.5%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 2.5%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 2.5%    |
| Intel Core i5-10310U CPU @ 1.70GHz            | 1         | 2.5%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 2.5%    |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 1         | 2.5%    |
| Intel Core i3-8145U CPU @ 2.10GHz             | 1         | 2.5%    |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 2.5%    |
| Intel 12th Gen Core i7-12800H                 | 1         | 2.5%    |
| Intel 12th Gen Core i7-12700H                 | 1         | 2.5%    |
| Intel 12th Gen Core i7-1260P                  | 1         | 2.5%    |
| Intel 12th Gen Core i5-1250P                  | 1         | 2.5%    |
| Intel 11th Gen Core i7-11850H @ 2.50GHz       | 1         | 2.5%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 2.5%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 1         | 2.5%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 1         | 2.5%    |
| AMD Ryzen 5 4500U with Radeon Graphics        | 1         | 2.5%    |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 1         | 2.5%    |
| AMD Ryzen 3 PRO 4450U with Radeon Graphics    | 1         | 2.5%    |
| AMD A10-4600M APU with Radeon HD Graphics     | 1         | 2.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i5   | 13        | 32.5%   |
| Intel Core i7   | 10        | 25%     |
| Other           | 9         | 22.5%   |
| AMD Ryzen 5     | 3         | 7.5%    |
| Intel Core i3   | 2         | 5%      |
| AMD Ryzen 7     | 1         | 2.5%    |
| AMD Ryzen 3 PRO | 1         | 2.5%    |
| AMD A10         | 1         | 2.5%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 19        | 47.5%   |
| 2      | 12        | 30%     |
| 6      | 3         | 7.5%    |
| 14     | 2         | 5%      |
| 12     | 2         | 5%      |
| 8      | 2         | 5%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 40        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 35        | 87.5%   |
| 1      | 5         | 12.5%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 40        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 17        | 42.5%   |
| 0x306a9    | 4         | 10%     |
| 0x906a3    | 3         | 7.5%    |
| 0x08600106 | 3         | 7.5%    |
| 0x806ec    | 2         | 5%      |
| 0x406e3    | 2         | 5%      |
| 0x40651    | 2         | 5%      |
| 0x306c3    | 2         | 5%      |
| 0xa0652    | 1         | 2.5%    |
| 0x806ea    | 1         | 2.5%    |
| 0x706e5    | 1         | 2.5%    |
| 0x20652    | 1         | 2.5%    |
| 0x06001119 | 1         | 2.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 10        | 25%     |
| Haswell          | 5         | 12.5%   |
| IvyBridge        | 4         | 10%     |
| Alderlake Hybrid | 4         | 10%     |
| Zen 2            | 3         | 7.5%    |
| TigerLake        | 3         | 7.5%    |
| Skylake          | 2         | 5%      |
| Icelake          | 2         | 5%      |
| Zen+             | 1         | 2.5%    |
| Westmere         | 1         | 2.5%    |
| Piledriver       | 1         | 2.5%    |
| Nehalem          | 1         | 2.5%    |
| Gracemont        | 1         | 2.5%    |
| CometLake        | 1         | 2.5%    |
| Unknown          | 1         | 2.5%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 30        | 53.57%  |
| Nvidia | 17        | 30.36%  |
| AMD    | 9         | 16.07%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                            | 4         | 7.02%   |
| Intel 3rd Gen Core processor Graphics Controller                     | 4         | 7.02%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                           | 3         | 5.26%   |
| Intel UHD Graphics 620                                               | 3         | 5.26%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                            | 3         | 5.26%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]          | 3         | 5.26%   |
| Intel Skylake GT2 [HD Graphics 520]                                  | 2         | 3.51%   |
| Intel HD Graphics 630                                                | 2         | 3.51%   |
| Intel Haswell-ULT Integrated Graphics Controller                     | 2         | 3.51%   |
| Intel CometLake-U GT2 [UHD Graphics]                                 | 2         | 3.51%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller          | 2         | 3.51%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                      | 1         | 1.75%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                              | 1         | 1.75%   |
| Nvidia GT216GLM [Quadro FX 880M]                                     | 1         | 1.75%   |
| Nvidia GP108M [GeForce MX330]                                        | 1         | 1.75%   |
| Nvidia GP108M [GeForce MX250]                                        | 1         | 1.75%   |
| Nvidia GP107M [GeForce MX350]                                        | 1         | 1.75%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                              | 1         | 1.75%   |
| Nvidia GM108M [GeForce MX110]                                        | 1         | 1.75%   |
| Nvidia GM108M [GeForce 940MX]                                        | 1         | 1.75%   |
| Nvidia GM107M [GeForce GTX 850M]                                     | 1         | 1.75%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                | 1         | 1.75%   |
| Nvidia GK208M [GeForce GT 740M]                                      | 1         | 1.75%   |
| Nvidia GK107M [GeForce GT 745M]                                      | 1         | 1.75%   |
| Nvidia GF108M [NVS 5400M]                                            | 1         | 1.75%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                   | 1         | 1.75%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                      | 1         | 1.75%   |
| Nvidia GA103M [GeForce RTX 3080 Ti Mobile]                           | 1         | 1.75%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                 | 1         | 1.75%   |
| Intel Iris Plus Graphics G7                                          | 1         | 1.75%   |
| Intel Alder Lake-N [UHD Graphics]                                    | 1         | 1.75%   |
| AMD Trinity [Radeon HD 7660G]                                        | 1         | 1.75%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series] | 1         | 1.75%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                         | 1         | 1.75%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]              | 1         | 1.75%   |
| AMD Mars [Radeon HD 8730M]                                           | 1         | 1.75%   |
| AMD Lucienne                                                         | 1         | 1.75%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520/610 Mobile]     | 1         | 1.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 15        | 37.5%   |
| Intel + Nvidia | 13        | 32.5%   |
| 1 x AMD        | 5         | 12.5%   |
| 1 x Nvidia     | 3         | 7.5%    |
| Intel + AMD    | 2         | 5%      |
| 2 x AMD        | 1         | 2.5%    |
| AMD + Nvidia   | 1         | 2.5%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 36        | 90%     |
| Proprietary | 3         | 7.5%    |
| Unknown     | 1         | 2.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 19        | 46.34%  |
| 1.01-2.0   | 7         | 17.07%  |
| 0.01-0.5   | 5         | 12.2%   |
| 3.01-4.0   | 3         | 7.32%   |
| 0.51-1.0   | 3         | 7.32%   |
| 5.01-6.0   | 2         | 4.88%   |
| 7.01-8.0   | 1         | 2.44%   |
| 8.01-16.0  | 1         | 2.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 11        | 23.4%   |
| LG Display              | 9         | 19.15%  |
| Chimei Innolux          | 5         | 10.64%  |
| BOE                     | 4         | 8.51%   |
| Unknown (XXX)           | 2         | 4.26%   |
| Samsung Electronics     | 2         | 4.26%   |
| TMX                     | 1         | 2.13%   |
| SKY                     | 1         | 2.13%   |
| Sharp                   | 1         | 2.13%   |
| PANDA                   | 1         | 2.13%   |
| Lenovo                  | 1         | 2.13%   |
| Hewlett-Packard         | 1         | 2.13%   |
| Goldstar                | 1         | 2.13%   |
| Denver                  | 1         | 2.13%   |
| Dell                    | 1         | 2.13%   |
| CSO                     | 1         | 2.13%   |
| Chi Mei Optoelectronics | 1         | 2.13%   |
| CHD                     | 1         | 2.13%   |
| Acer                    | 1         | 2.13%   |
| Unknown                 | 1         | 2.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                    | 2         | 4.26%   |
| Unknown (XXX) FURRION TV XXX3553 1920x1080 520x290mm 23.4-inch           | 1         | 2.13%   |
| Unknown (XXX) Beyond TV XXX9221 1920x1080 1209x680mm 54.6-inch           | 1         | 2.13%   |
| TMX TL156VDXP01 TMX1560 1920x1080 344x194mm 15.5-inch                    | 1         | 2.13%   |
| SKY 22X1-M225F SKY2150 1920x1080 476x268mm 21.5-inch                     | 1         | 2.13%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                  | 1         | 2.13%   |
| Samsung Electronics SMT23A350 SAM07A7 1920x1080 510x287mm 23.0-inch      | 1         | 2.13%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch    | 1         | 2.13%   |
| PANDA LCD Monitor NCP0052 1920x1080 309x174mm 14.0-inch                  | 1         | 2.13%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch             | 1         | 2.13%   |
| LG Display LCD Monitor LGD068A 1920x1080 309x174mm 14.0-inch             | 1         | 2.13%   |
| LG Display LCD Monitor LGD0657 1920x1080 344x194mm 15.5-inch             | 1         | 2.13%   |
| LG Display LCD Monitor LGD05E4 1920x1080 344x194mm 15.5-inch             | 1         | 2.13%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 1         | 2.13%   |
| LG Display LCD Monitor LGD046C 1920x1080 382x215mm 17.3-inch             | 1         | 2.13%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch              | 1         | 2.13%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch              | 1         | 2.13%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch              | 1         | 2.13%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                 | 1         | 2.13%   |
| Hewlett-Packard L185x HWP298C 1366x768 410x230mm 18.5-inch               | 1         | 2.13%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 1         | 2.13%   |
| Denver V3L6W LHC3503 3440x1440 819x346mm 35.0-inch                       | 1         | 2.13%   |
| Dell P2214H DELA098 1920x1080 477x268mm 21.5-inch                        | 1         | 2.13%   |
| CSO LCD Monitor CSO1404 1920x1200 302x189mm 14.0-inch                    | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN1608 1920x1080 355x199mm 16.0-inch         | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN1515 1920x1080 344x193mm 15.5-inch         | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN14A3 1600x900 309x174mm 14.0-inch          | 1         | 2.13%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 1         | 2.13%   |
| CHD GDM-245LN CHD0240 1920x1080 470x280mm 21.5-inch                      | 1         | 2.13%   |
| BOE LCD Monitor BOE08D5 1920x1080 344x194mm 15.5-inch                    | 1         | 2.13%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 1         | 2.13%   |
| AU Optronics LCD Monitor AUOF992 1920x1080 382x215mm 17.3-inch           | 1         | 2.13%   |
| AU Optronics LCD Monitor AUO5A3D 1920x1080 309x174mm 14.0-inch           | 1         | 2.13%   |
| AU Optronics LCD Monitor AUO5A2D 1920x1080 290x170mm 13.2-inch           | 1         | 2.13%   |
| AU Optronics LCD Monitor AUO408D 1920x1080 309x174mm 14.0-inch           | 1         | 2.13%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 1         | 2.13%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch           | 1         | 2.13%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch           | 1         | 2.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 25        | 58.14%  |
| 1366x768 (WXGA)   | 8         | 18.6%   |
| 1920x1200 (WUXGA) | 2         | 4.65%   |
| 1600x900 (HD+)    | 2         | 4.65%   |
| 5760x1080         | 1         | 2.33%   |
| 3840x2160 (4K)    | 1         | 2.33%   |
| 3440x1440         | 1         | 2.33%   |
| 3200x2000         | 1         | 2.33%   |
| 2560x1440 (QHD)   | 1         | 2.33%   |
| Unknown           | 1         | 2.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 15        | 31.91%  |
| 14      | 15        | 31.91%  |
| 13      | 3         | 6.38%   |
| 23      | 2         | 4.26%   |
| 21      | 2         | 4.26%   |
| 17      | 2         | 4.26%   |
| 54      | 1         | 2.13%   |
| 35      | 1         | 2.13%   |
| 31      | 1         | 2.13%   |
| 27      | 1         | 2.13%   |
| 24      | 1         | 2.13%   |
| 18      | 1         | 2.13%   |
| 16      | 1         | 2.13%   |
| Unknown | 1         | 2.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 32        | 69.57%  |
| 501-600     | 3         | 6.52%   |
| 401-500     | 3         | 6.52%   |
| 351-400     | 3         | 6.52%   |
| 801-900     | 1         | 2.17%   |
| 601-700     | 1         | 2.17%   |
| 201-300     | 1         | 2.17%   |
| 1001-1500   | 1         | 2.17%   |
| Unknown     | 1         | 2.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 34        | 87.18%  |
| 16/10   | 3         | 7.69%   |
| 21/9    | 1         | 2.56%   |
| Unknown | 1         | 2.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 17        | 36.96%  |
| 101-110        | 15        | 32.61%  |
| 201-250        | 3         | 6.52%   |
| 351-500        | 2         | 4.35%   |
| 121-130        | 2         | 4.35%   |
| More than 1000 | 1         | 2.17%   |
| 71-80          | 1         | 2.17%   |
| 301-350        | 1         | 2.17%   |
| 151-200        | 1         | 2.17%   |
| 141-150        | 1         | 2.17%   |
| 111-120        | 1         | 2.17%   |
| Unknown        | 1         | 2.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 25        | 54.35%  |
| 101-120       | 9         | 19.57%  |
| 51-100        | 6         | 13.04%  |
| 161-240       | 3         | 6.52%   |
| More than 240 | 1         | 2.17%   |
| 1-50          | 1         | 2.17%   |
| Unknown       | 1         | 2.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 29        | 72.5%   |
| 2     | 8         | 20%     |
| 0     | 2         | 5%      |
| 3     | 1         | 2.5%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 27        | 42.86%  |
| Realtek Semiconductor             | 17        | 26.98%  |
| Qualcomm Atheros                  | 9         | 14.29%  |
| Broadcom                          | 3         | 4.76%   |
| ASUSTek Computer                  | 2         | 3.17%   |
| Xiaomi                            | 1         | 1.59%   |
| TP-Link                           | 1         | 1.59%   |
| Ralink Technology                 | 1         | 1.59%   |
| Ericsson Business Mobile Networks | 1         | 1.59%   |
| ASIX Electronics                  | 1         | 1.59%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 14        | 18.18%  |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 4         | 5.19%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 3         | 3.9%    |
| Intel Wireless 7260                                                    | 3         | 3.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2         | 2.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 2         | 2.6%    |
| Intel Wireless 8265 / 8275                                             | 2         | 2.6%    |
| Intel Wireless 8260                                                    | 2         | 2.6%    |
| Intel Wi-Fi 6 AX201                                                    | 2         | 2.6%    |
| Intel Wi-Fi 6 AX200                                                    | 2         | 2.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 2         | 2.6%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 2         | 2.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 2.6%    |
| ASUS 802.11ac NIC                                                      | 2         | 2.6%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 1.3%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 1         | 1.3%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 1         | 1.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 1         | 1.3%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 1         | 1.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1         | 1.3%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1         | 1.3%    |
| Ralink RT5370 Wireless Adapter                                         | 1         | 1.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 1         | 1.3%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 1.3%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 1         | 1.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 1         | 1.3%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 1.3%    |
| Intel Wireless 7265                                                    | 1         | 1.3%    |
| Intel Tiger Lake PCH CNVi WiFi                                         | 1         | 1.3%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 1         | 1.3%    |
| Intel Ethernet Connection I219-V                                       | 1         | 1.3%    |
| Intel Ethernet Connection I219-LM                                      | 1         | 1.3%    |
| Intel Ethernet Connection I218-LM                                      | 1         | 1.3%    |
| Intel Ethernet Connection (6) I219-V                                   | 1         | 1.3%    |
| Intel Ethernet Connection (5) I219-V                                   | 1         | 1.3%    |
| Intel Ethernet Connection (10) I219-LM                                 | 1         | 1.3%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 1         | 1.3%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 1         | 1.3%    |
| Intel Comet Lake PCH CNVi WiFi                                         | 1         | 1.3%    |
| Intel Centrino Ultimate-N 6300                                         | 1         | 1.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 27        | 61.36%  |
| Qualcomm Atheros      | 8         | 18.18%  |
| Realtek Semiconductor | 4         | 9.09%   |
| ASUSTek Computer      | 2         | 4.55%   |
| TP-Link               | 1         | 2.27%   |
| Ralink Technology     | 1         | 2.27%   |
| Broadcom              | 1         | 2.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P PCH CNVi WiFi                               | 4         | 9.09%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 6.82%   |
| Intel Wireless 7260                                            | 3         | 6.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 4.55%   |
| Intel Wireless 8265 / 8275                                     | 2         | 4.55%   |
| Intel Wireless 8260                                            | 2         | 4.55%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 4.55%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 4.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 4.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 4.55%   |
| ASUS 802.11ac NIC                                              | 2         | 4.55%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 2.27%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 2.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.27%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 2.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.27%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 2.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 2.27%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 2.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 2.27%   |
| Intel Wireless 7265                                            | 1         | 2.27%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 2.27%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 2.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 2.27%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 2.27%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 2.27%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 2.27%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 2.27%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 2.27%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 17        | 53.13%  |
| Intel                 | 9         | 28.13%  |
| Qualcomm Atheros      | 2         | 6.25%   |
| Broadcom              | 2         | 6.25%   |
| Xiaomi                | 1         | 3.13%   |
| ASIX Electronics      | 1         | 3.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 14        | 43.75%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2         | 6.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 6.25%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 3.13%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1         | 3.13%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 3.13%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 3.13%   |
| Intel Ethernet Connection I219-V                                       | 1         | 3.13%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 3.13%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 3.13%   |
| Intel Ethernet Connection (6) I219-V                                   | 1         | 3.13%   |
| Intel Ethernet Connection (5) I219-V                                   | 1         | 3.13%   |
| Intel Ethernet Connection (10) I219-LM                                 | 1         | 3.13%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 3.13%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 1         | 3.13%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 3.13%   |
| ASIX AX88179 Gigabit Ethernet                                          | 1         | 3.13%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 40        | 55.56%  |
| Ethernet | 31        | 43.06%  |
| Modem    | 1         | 1.39%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 31        | 75.61%  |
| Ethernet | 10        | 24.39%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 27        | 67.5%   |
| 1     | 12        | 30%     |
| 3     | 1         | 2.5%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 29        | 72.5%   |
| Yes  | 11        | 27.5%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 23        | 60.53%  |
| Qualcomm Atheros Communications | 5         | 13.16%  |
| Realtek Semiconductor           | 3         | 7.89%   |
| Broadcom                        | 3         | 7.89%   |
| Lite-On Technology              | 2         | 5.26%   |
| Integrated System Solution      | 1         | 2.63%   |
| IMC Networks                    | 1         | 2.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 9         | 23.68%  |
| Intel AX201 Bluetooth                          | 5         | 13.16%  |
| Realtek Bluetooth Radio                        | 3         | 7.89%   |
| Qualcomm Atheros  Bluetooth Device             | 3         | 7.89%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 3         | 7.89%   |
| Intel AX211 Bluetooth                          | 3         | 7.89%   |
| Intel AX200 Bluetooth                          | 2         | 5.26%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 2         | 5.26%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0          | 1         | 2.63%   |
| Qualcomm Atheros AR3011 Bluetooth              | 1         | 2.63%   |
| Lite-On Bluetooth Device                       | 1         | 2.63%   |
| Lite-On Atheros AR3012 Bluetooth               | 1         | 2.63%   |
| Intel Wireless-AC 3168 Bluetooth               | 1         | 2.63%   |
| Integrated System Solution Bluetooth Device    | 1         | 2.63%   |
| IMC Networks Bluetooth Radio                   | 1         | 2.63%   |
| Broadcom BCM2045B (BDC-2.1)                    | 1         | 2.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 33        | 66%     |
| AMD                    | 8         | 16%     |
| Nvidia                 | 7         | 14%     |
| JBL                    | 1         | 2%      |
| Generalplus Technology | 1         | 2%      |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                              | 5         | 8.33%   |
| Intel Sunrise Point-LP HD Audio                                         | 4         | 6.67%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                 | 4         | 6.67%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller     | 4         | 6.67%   |
| AMD Renoir Radeon High Definition Audio Controller                      | 4         | 6.67%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller             | 3         | 5%      |
| Intel Cannon Point-LP High Definition Audio Controller                  | 3         | 5%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 3         | 5%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller        | 2         | 3.33%   |
| Intel Haswell-ULT HD Audio Controller                                   | 2         | 3.33%   |
| Intel Comet Lake PCH-LP cAVS                                            | 2         | 3.33%   |
| Intel CM238 HD Audio Controller                                         | 2         | 3.33%   |
| Intel 8 Series HD Audio Controller                                      | 2         | 3.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                | 2         | 3.33%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller          | 1         | 1.67%   |
| Nvidia TU106 High Definition Audio Controller                           | 1         | 1.67%   |
| Nvidia GT216 HDMI Audio Controller                                      | 1         | 1.67%   |
| Nvidia GP104 High Definition Audio Controller                           | 1         | 1.67%   |
| Nvidia GF108 High Definition Audio Controller                           | 1         | 1.67%   |
| Nvidia GA106 High Definition Audio Controller                           | 1         | 1.67%   |
| Nvidia Audio device                                                     | 1         | 1.67%   |
| JBL Quantum 600                                                         | 1         | 1.67%   |
| Intel Tiger Lake-H HD Audio Controller                                  | 1         | 1.67%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller               | 1         | 1.67%   |
| Intel Comet Lake PCH cAVS                                               | 1         | 1.67%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                 | 1         | 1.67%   |
| Generalplus Technology USB Audio Device                                 | 1         | 1.67%   |
| AMD Trinity HDMI Audio Controller                                       | 1         | 1.67%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 1         | 1.67%   |
| AMD Navi 10 HDMI Audio                                                  | 1         | 1.67%   |
| AMD FCH Azalia Controller                                               | 1         | 1.67%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                  | 1         | 1.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 15        | 50%     |
| SK hynix            | 6         | 20%     |
| Kingston            | 2         | 6.67%   |
| Corsair             | 2         | 6.67%   |
| Smart Brazil        | 1         | 3.33%   |
| SHARETRONIC         | 1         | 3.33%   |
| G.Skill             | 1         | 3.33%   |
| Crucial             | 1         | 3.33%   |
| A-DATA Technology   | 1         | 3.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s        | 2         | 6.45%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s  | 2         | 6.45%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s | 1         | 3.23%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s       | 1         | 3.23%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s       | 1         | 3.23%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s      | 1         | 3.23%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 3.23%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s      | 1         | 3.23%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 1         | 3.23%   |
| SHARETRONIC RAM Module 4GB SODIMM DDR3 800MT/s               | 1         | 3.23%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 1         | 3.23%   |
| Samsung RAM Module 2GB Row Of Chips LPDDR5 4000MT/s          | 1         | 3.23%   |
| Samsung RAM M474A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s       | 1         | 3.23%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s        | 1         | 3.23%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 3.23%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 3.23%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 3.23%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s        | 1         | 3.23%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s        | 1         | 3.23%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 3.23%   |
| Samsung RAM K4UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s | 1         | 3.23%   |
| Samsung RAM K3LKBKB0BM-MGCP 4GB Row Of Chips LPDDR5 6400MT/s | 1         | 3.23%   |
| Kingston RAM 99U5700-027.A00G 8GB SODIMM DDR4 2667MT/s       | 1         | 3.23%   |
| Kingston RAM 9905417-083.A00G 4GB SODIMM DDR3 1600MT/s       | 1         | 3.23%   |
| G.Skill RAM F3-1600C9-8GRSL 8GB SODIMM DDR3 1600MT/s         | 1         | 3.23%   |
| Crucial RAM CT16G4SFRA32A.M16FR 16GB SODIMM DDR4 3200MT/s    | 1         | 3.23%   |
| Corsair RAM CMSX8GX4M1A2400C16 8GB SODIMM DDR4 2400MT/s      | 1         | 3.23%   |
| Corsair RAM CMSO8GX3M1C1600C11 8192MB SODIMM DDR3 1600MT/s   | 1         | 3.23%   |
| A-DATA RAM Module 32GB SODIMM DDR4 3200MT/s                  | 1         | 3.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 15        | 60%     |
| DDR3   | 7         | 28%     |
| LPDDR5 | 2         | 8%      |
| LPDDR4 | 1         | 4%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 19        | 79.17%  |
| Row Of Chips | 5         | 20.83%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 15        | 53.57%  |
| 4096  | 5         | 17.86%  |
| 16384 | 4         | 14.29%  |
| 32768 | 2         | 7.14%   |
| 2048  | 2         | 7.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 7         | 25%     |
| 2667  | 6         | 21.43%  |
| 1600  | 4         | 14.29%  |
| 2400  | 3         | 10.71%  |
| 1334  | 2         | 7.14%   |
| 6400  | 1         | 3.57%   |
| 4267  | 1         | 3.57%   |
| 4000  | 1         | 3.57%   |
| 2133  | 1         | 3.57%   |
| 1067  | 1         | 3.57%   |
| 800   | 1         | 3.57%   |

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
| Chicony Electronics                    | 7         | 20%     |
| IMC Networks                           | 5         | 14.29%  |
| Realtek Semiconductor                  | 4         | 11.43%  |
| Syntek                                 | 3         | 8.57%   |
| Bison Electronics                      | 3         | 8.57%   |
| Microdia                               | 2         | 5.71%   |
| Luxvisions Innotech Limited            | 2         | 5.71%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 5.71%   |
| Acer                                   | 2         | 5.71%   |
| Sunplus Innovation Technology          | 1         | 2.86%   |
| Silicon Motion                         | 1         | 2.86%   |
| Lite-On Technology                     | 1         | 2.86%   |
| Lenovo                                 | 1         | 2.86%   |
| Apple                                  | 1         | 2.86%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                            | 3         | 8.33%   |
| Realtek Integrated_Webcam_HD                        | 2         | 5.56%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 5.56%   |
| IMC Networks Integrated Camera                      | 2         | 5.56%   |
| Chicony Integrated Camera                           | 2         | 5.56%   |
| Acer Integrated Camera                              | 2         | 5.56%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 2.78%   |
| Silicon Motion WebCam SC-13HDL11939N                | 1         | 2.78%   |
| Realtek Lenovo EasyCamera                           | 1         | 2.78%   |
| Realtek Integrated Webcam                           | 1         | 2.78%   |
| Microdia USB 2.0 Camera                             | 1         | 2.78%   |
| Microdia Integrated_Webcam_HD                       | 1         | 2.78%   |
| Lite-On Integrated Camera                           | 1         | 2.78%   |
| Lenovo Integrated Webcam [R5U877]                   | 1         | 2.78%   |
| IMC Networks USB2.0 UVC HD Webcam                   | 1         | 2.78%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 2.78%   |
| IMC Networks Integrated RGB Camera                  | 1         | 2.78%   |
| Chicony USB2.0 2M WebCam                            | 1         | 2.78%   |
| Chicony USB 5M WebCam                               | 1         | 2.78%   |
| Chicony Thinkpad T430 camera                        | 1         | 2.78%   |
| Chicony HD WebCam (Asus N-series)                   | 1         | 2.78%   |
| Chicony HD WebCam                                   | 1         | 2.78%   |
| Chicony Acer CrystalEye Webcam                      | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 1         | 2.78%   |
| Bison Lenovo Integrated Webcam                      | 1         | 2.78%   |
| Bison Integrated Camera                             | 1         | 2.78%   |
| Bison HD Webcam                                     | 1         | 2.78%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 1         | 2.78%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 3         | 50%     |
| Upek                  | 1         | 16.67%  |
| Synaptics             | 1         | 16.67%  |
| LighTuning Technology | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 16.67%  |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 16.67%  |
| Validity Sensors Synaptics WBDI                        | 1         | 16.67%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 16.67%  |
| Synaptics Prometheus Fingerprint Reader                | 1         | 16.67%  |
| LighTuning ES603 Swipe Fingerprint Sensor              | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Upek   | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 26        | 63.41%  |
| 1     | 10        | 24.39%  |
| 2     | 5         | 12.2%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 6         | 35.29%  |
| Graphics card         | 4         | 23.53%  |
| Multimedia controller | 3         | 17.65%  |
| Net/wireless          | 2         | 11.76%  |
| Firewire controller   | 1         | 5.88%   |
| Chipcard              | 1         | 5.88%   |

