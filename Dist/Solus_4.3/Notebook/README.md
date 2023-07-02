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

Total: 49

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 3420               | [730bdb05fe](https://linux-hardware.org/?probe=730bdb05fe) | Jun 23, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [299733170c](https://linux-hardware.org/?probe=299733170c) | Apr 03, 2023 |
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
| 5.13.1-187.current  | 5         | 13.89%  |
| 5.15.50-216.current | 4         | 11.11%  |
| 5.15.32-213.current | 3         | 8.33%   |
| 5.14.21-210.current | 3         | 8.33%   |
| 6.1.5-229.current   | 2         | 5.56%   |
| 6.0.11-225.current  | 2         | 5.56%   |
| 5.15.77-219.current | 2         | 5.56%   |
| 5.14.16-205.current | 2         | 5.56%   |
| 5.13.6-190.current  | 2         | 5.56%   |
| 5.13.12-193.current | 2         | 5.56%   |
| 6.1.2-228.current   | 1         | 2.78%   |
| 5.15.61-217.current | 1         | 2.78%   |
| 5.15.37-214.current | 1         | 2.78%   |
| 5.15.26-211.current | 1         | 2.78%   |
| 5.14.7-198.current  | 1         | 2.78%   |
| 5.14.16-204.current | 1         | 2.78%   |
| 5.14.15-203.current | 1         | 2.78%   |
| 5.14.12-201.current | 1         | 2.78%   |
| 5.13.15-194.current | 1         | 2.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.13.1  | 5         | 13.89%  |
| 5.15.50 | 4         | 11.11%  |
| 5.15.32 | 3         | 8.33%   |
| 5.14.21 | 3         | 8.33%   |
| 5.14.16 | 3         | 8.33%   |
| 6.1.5   | 2         | 5.56%   |
| 6.0.11  | 2         | 5.56%   |
| 5.15.77 | 2         | 5.56%   |
| 5.13.6  | 2         | 5.56%   |
| 5.13.12 | 2         | 5.56%   |
| 6.1.2   | 1         | 2.78%   |
| 5.15.61 | 1         | 2.78%   |
| 5.15.37 | 1         | 2.78%   |
| 5.15.26 | 1         | 2.78%   |
| 5.14.7  | 1         | 2.78%   |
| 5.14.15 | 1         | 2.78%   |
| 5.14.12 | 1         | 2.78%   |
| 5.13.15 | 1         | 2.78%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 12        | 33.33%  |
| 5.13    | 10        | 27.78%  |
| 5.14    | 9         | 25%     |
| 6.1     | 3         | 8.33%   |
| 6.0     | 2         | 5.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 33        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Budgie  | 16        | 47.06%  |
| MATE    | 5         | 14.71%  |
| KDE5    | 4         | 11.76%  |
| Unknown | 4         | 11.76%  |
| KDE     | 3         | 8.82%   |
| GNOME   | 2         | 5.88%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 33        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 24        | 70.59%  |
| LightDM | 7         | 20.59%  |
| SDDM    | 2         | 5.88%   |
| GDM     | 1         | 2.94%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 21        | 63.64%  |
| de_DE | 5         | 15.15%  |
| en_GB | 3         | 9.09%   |
| pt_BR | 1         | 3.03%   |
| fr_FR | 1         | 3.03%   |
| es_ES | 1         | 3.03%   |
| en_IN | 1         | 3.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 24        | 68.57%  |
| BIOS | 11        | 31.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 31        | 93.94%  |
| Overlay | 2         | 6.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 20        | 60.61%  |
| GPT     | 11        | 33.33%  |
| MBR     | 2         | 6.06%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 31        | 93.94%  |
| Yes       | 2         | 6.06%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 28        | 84.85%  |
| Yes       | 5         | 15.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 10        | 30.3%   |
| Lenovo              | 7         | 21.21%  |
| Acer                | 3         | 9.09%   |
| Toshiba             | 2         | 6.06%   |
| Hewlett-Packard     | 2         | 6.06%   |
| Google              | 2         | 6.06%   |
| Sony                | 1         | 3.03%   |
| Samsung Electronics | 1         | 3.03%   |
| MSI                 | 1         | 3.03%   |
| GPU Company         | 1         | 3.03%   |
| Framework           | 1         | 3.03%   |
| AZW                 | 1         | 3.03%   |
| ASUSTek Computer    | 1         | 3.03%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Toshiba TECRA R840                     | 1         | 3.03%   |
| Toshiba Satellite L855                 | 1         | 3.03%   |
| Sony VPCYB15AB                         | 1         | 3.03%   |
| Samsung R430/P430/R480                 | 1         | 3.03%   |
| MSI Modern 14 B5M                      | 1         | 3.03%   |
| Lenovo Z50-70 20354                    | 1         | 3.03%   |
| Lenovo ThinkPad T15 Gen 2i 20W4CTO1WW  | 1         | 3.03%   |
| Lenovo ThinkPad T14 Gen 1 20S00013FR   | 1         | 3.03%   |
| Lenovo IdeaPad S340-15API 81NC         | 1         | 3.03%   |
| Lenovo IdeaPad 530S-14ARR 81H1         | 1         | 3.03%   |
| Lenovo IdeaPad 5 15ALC05 82LN          | 1         | 3.03%   |
| Lenovo IdeaPad 320-15ISK 80XH          | 1         | 3.03%   |
| HP ProBook 450 G5                      | 1         | 3.03%   |
| HP OMEN Laptop 15-en0xxx               | 1         | 3.03%   |
| GPU Company GWTC116-2                  | 1         | 3.03%   |
| Google Edgar                           | 1         | 3.03%   |
| Google Delbin                          | 1         | 3.03%   |
| Framework Laptop                       | 1         | 3.03%   |
| Dell XPS 13 9380                       | 1         | 3.03%   |
| Dell XPS 13 7390                       | 1         | 3.03%   |
| Dell Vostro 15-3568                    | 1         | 3.03%   |
| Dell Latitude E6220                    | 1         | 3.03%   |
| Dell Latitude E5470                    | 1         | 3.03%   |
| Dell Latitude 5580                     | 1         | 3.03%   |
| Dell Latitude 3420                     | 1         | 3.03%   |
| Dell Inspiron 7460                     | 1         | 3.03%   |
| Dell Inspiron 1525                     | 1         | 3.03%   |
| Dell Inspiron 15-3573                  | 1         | 3.03%   |
| AZW SEi                                | 1         | 3.03%   |
| ASUS VivoBook_ASUSLaptop X509DA_M509DA | 1         | 3.03%   |
| Acer Swift SF114-34                    | 1         | 3.03%   |
| Acer Nitro AN515-45                    | 1         | 3.03%   |
| Acer Aspire A315-54                    | 1         | 3.03%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo IdeaPad        | 4         | 12.12%  |
| Dell Latitude         | 4         | 12.12%  |
| Dell Inspiron         | 3         | 9.09%   |
| Lenovo ThinkPad       | 2         | 6.06%   |
| Dell XPS              | 2         | 6.06%   |
| Toshiba TECRA         | 1         | 3.03%   |
| Toshiba Satellite     | 1         | 3.03%   |
| Sony VPCYB15AB        | 1         | 3.03%   |
| Samsung R430          | 1         | 3.03%   |
| MSI Modern            | 1         | 3.03%   |
| Lenovo Z50-70         | 1         | 3.03%   |
| HP ProBook            | 1         | 3.03%   |
| HP OMEN               | 1         | 3.03%   |
| GPU Company GWTC116-2 | 1         | 3.03%   |
| Google Edgar          | 1         | 3.03%   |
| Google Delbin         | 1         | 3.03%   |
| Framework Laptop      | 1         | 3.03%   |
| Dell Vostro           | 1         | 3.03%   |
| AZW SEi               | 1         | 3.03%   |
| ASUS VivoBook         | 1         | 3.03%   |
| Acer Swift            | 1         | 3.03%   |
| Acer Nitro            | 1         | 3.03%   |
| Acer Aspire           | 1         | 3.03%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 8         | 24.24%  |
| 2019 | 5         | 15.15%  |
| 2020 | 4         | 12.12%  |
| 2017 | 4         | 12.12%  |
| 2018 | 3         | 9.09%   |
| 2016 | 2         | 6.06%   |
| 2011 | 2         | 6.06%   |
| 2010 | 2         | 6.06%   |
| 2014 | 1         | 3.03%   |
| 2012 | 1         | 3.03%   |
| 2008 | 1         | 3.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 33        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 33        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 31        | 93.94%  |
| Yes  | 2         | 6.06%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 7         | 21.21%  |
| 3.01-4.0   | 6         | 18.18%  |
| 16.01-24.0 | 6         | 18.18%  |
| 32.01-64.0 | 5         | 15.15%  |
| 8.01-16.0  | 5         | 15.15%  |
| 1.01-2.0   | 2         | 6.06%   |
| 24.01-32.0 | 1         | 3.03%   |
| 2.01-3.0   | 1         | 3.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 16        | 45.71%  |
| 1.01-2.0  | 9         | 25.71%  |
| 3.01-4.0  | 4         | 11.43%  |
| 4.01-8.0  | 3         | 8.57%   |
| 0.51-1.0  | 2         | 5.71%   |
| 8.01-16.0 | 1         | 2.86%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 27        | 81.82%  |
| 2      | 6         | 18.18%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 26        | 78.79%  |
| Yes       | 7         | 21.21%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 66.67%  |
| No        | 11        | 33.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 33        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 87.88%  |
| No        | 4         | 12.12%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 7         | 21.21%  |
| Germany     | 4         | 12.12%  |
| India       | 3         | 9.09%   |
| Brazil      | 3         | 9.09%   |
| UK          | 2         | 6.06%   |
| Netherlands | 2         | 6.06%   |
| Vietnam     | 1         | 3.03%   |
| Ukraine     | 1         | 3.03%   |
| Switzerland | 1         | 3.03%   |
| Poland      | 1         | 3.03%   |
| Norway      | 1         | 3.03%   |
| Nepal       | 1         | 3.03%   |
| Mexico      | 1         | 3.03%   |
| France      | 1         | 3.03%   |
| Czechia     | 1         | 3.03%   |
| Belgium     | 1         | 3.03%   |
| Australia   | 1         | 3.03%   |
| Argentina   | 1         | 3.03%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Yverdon-les-Bains        | 1         | 2.86%   |
| Wendell                  | 1         | 2.86%   |
| Vineland                 | 1         | 2.86%   |
| Vasco da Gama            | 1         | 2.86%   |
| Uberlândia              | 1         | 2.86%   |
| Stare Babice             | 1         | 2.86%   |
| San Justo                | 1         | 2.86%   |
| Saint-Just-Saint-Rambert | 1         | 2.86%   |
| Red Oak                  | 1         | 2.86%   |
| Pomeroy                  | 1         | 2.86%   |
| Oslo                     | 1         | 2.86%   |
| Mohali                   | 1         | 2.86%   |
| Milwaukee                | 1         | 2.86%   |
| Melbourne                | 1         | 2.86%   |
| Mainz                    | 1         | 2.86%   |
| Lviv                     | 1         | 2.86%   |
| Luckenwalde              | 1         | 2.86%   |
| Lübeck                  | 1         | 2.86%   |
| Linter                   | 1         | 2.86%   |
| León                    | 1         | 2.86%   |
| Kathmandu                | 1         | 2.86%   |
| Jackson                  | 1         | 2.86%   |
| Ilford                   | 1         | 2.86%   |
| Hanoi                    | 1         | 2.86%   |
| Guanajuato City          | 1         | 2.86%   |
| Groningen                | 1         | 2.86%   |
| Greenwich                | 1         | 2.86%   |
| Goiânia                 | 1         | 2.86%   |
| Essen                    | 1         | 2.86%   |
| Dubenec                  | 1         | 2.86%   |
| Coimbatore               | 1         | 2.86%   |
| Chelmsford               | 1         | 2.86%   |
| Belo Horizonte           | 1         | 2.86%   |
| Anacortes                | 1         | 2.86%   |
| Amsterdam                | 1         | 2.86%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 7         | 9      | 17.07%  |
| WDC                 | 5         | 5      | 12.2%   |
| SK hynix            | 5         | 5      | 12.2%   |
| Samsung Electronics | 4         | 5      | 9.76%   |
| Unknown             | 3         | 3      | 7.32%   |
| Seagate             | 3         | 4      | 7.32%   |
| Intel               | 3         | 4      | 7.32%   |
| Toshiba             | 2         | 2      | 4.88%   |
| Kingston            | 2         | 2      | 4.88%   |
| Silicon Motion      | 1         | 1      | 2.44%   |
| SABRENT             | 1         | 1      | 2.44%   |
| PNY                 | 1         | 1      | 2.44%   |
| Phison              | 1         | 1      | 2.44%   |
| KIOXIA              | 1         | 1      | 2.44%   |
| Advantech           | 1         | 1      | 2.44%   |
| A-DATA Technology   | 1         | 1      | 2.44%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| SK hynix NVMe SSD Drive 128GB                    | 2         | 4.65%   |
| SanDisk NVMe SSD Drive 256GB                     | 2         | 4.65%   |
| WDC WD3200BEVT-75ZCT2 320GB                      | 1         | 2.33%   |
| WDC WD2500BEVT-22ZCT0 250GB                      | 1         | 2.33%   |
| WDC WD10SPZX-24Z10T0 1TB                         | 1         | 2.33%   |
| WDC WD10SPZX-24Z10 1TB                           | 1         | 2.33%   |
| WDC WD10JPCX-24UE4T0 1TB                         | 1         | 2.33%   |
| Unknown USB DISK 3.2 2TB                         | 1         | 2.33%   |
| Unknown MMC Card  64GB                           | 1         | 2.33%   |
| Unknown MMC Card  128GB                          | 1         | 2.33%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 2.33%   |
| Toshiba KXG60ZNV512G NVMe 512GB                  | 1         | 2.33%   |
| SK hynix SC311 SATA 256GB SSD                    | 1         | 2.33%   |
| SK hynix NVMe SSD Drive 500GB                    | 1         | 2.33%   |
| SK hynix NVMe SSD Drive 256GB                    | 1         | 2.33%   |
| Silicon Motion NVMe SSD Drive 512GB              | 1         | 2.33%   |
| Seagate ST9320325AS 320GB                        | 1         | 2.33%   |
| Seagate ST1000LM049-2GH172 1TB                   | 1         | 2.33%   |
| Seagate ST1000LM035-1RK172 1TB                   | 1         | 2.33%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB | 1         | 2.33%   |
| SanDisk SDSSDH32000G 2TB                         | 1         | 2.33%   |
| Sandisk PC SN520 NVMe SSD 512GB                  | 1         | 2.33%   |
| SanDisk NVMe SSD Drive 1TB                       | 1         | 2.33%   |
| SanDisk Extreme Pro 1TB                          | 1         | 2.33%   |
| SanDisk DF4032  32GB                             | 1         | 2.33%   |
| Samsung SSD 850 EVO 250GB                        | 1         | 2.33%   |
| Samsung NVMe SSD Drive 512GB                     | 1         | 2.33%   |
| Samsung NVMe SSD Drive 2TB                       | 1         | 2.33%   |
| Samsung MZVL22T0HBLB-00BL7 2TB                   | 1         | 2.33%   |
| Samsung MZALQ512HBLU-00BL2 512GB                 | 1         | 2.33%   |
| SABRENT Disk 1TB                                 | 1         | 2.33%   |
| PNY CS900 240GB SSD                              | 1         | 2.33%   |
| Phison NVMe SSD Drive 512GB                      | 1         | 2.33%   |
| KIOXIA KXG60ZNV512G NVMe 512GB                   | 1         | 2.33%   |
| Kingston SA400S37240G 240GB SSD                  | 1         | 2.33%   |
| Kingston OM8PCP3512F-AI1 512GB                   | 1         | 2.33%   |
| Intel SSDPEKKW512G7 512GB                        | 1         | 2.33%   |
| Intel NVMe SSD Drive 512GB                       | 1         | 2.33%   |
| Intel NVMe SSD Drive 256GB                       | 1         | 2.33%   |
| Advantech SQF-S25M8-128G-AAG 128GB SSD           | 1         | 2.33%   |

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
| NVMe    | 19        | 26     | 50%     |
| HDD     | 9         | 10     | 23.68%  |
| SSD     | 6         | 6      | 15.79%  |
| MMC     | 3         | 3      | 7.89%   |
| Unknown | 1         | 1      | 2.63%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 19        | 25     | 48.72%  |
| SATA | 14        | 15     | 35.9%   |
| SAS  | 3         | 3      | 7.69%   |
| MMC  | 3         | 3      | 7.69%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 9         | 10     | 60%     |
| 0.51-1.0   | 5         | 5      | 33.33%  |
| 1.01-2.0   | 1         | 1      | 6.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 11        | 32.35%  |
| 251-500    | 9         | 26.47%  |
| 501-1000   | 8         | 23.53%  |
| 21-50      | 2         | 5.88%   |
| 51-100     | 2         | 5.88%   |
| 2001-3000  | 1         | 2.94%   |
| Unknown    | 1         | 2.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 13        | 36.11%  |
| 21-50     | 9         | 25%     |
| 51-100    | 5         | 13.89%  |
| 251-500   | 4         | 11.11%  |
| 101-250   | 3         | 8.33%   |
| 1001-2000 | 1         | 2.78%   |
| Unknown   | 1         | 2.78%   |

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
| Detected | 23        | 33     | 65.71%  |
| Works    | 11        | 11     | 31.43%  |
| Malfunc  | 1         | 2      | 2.86%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 18        | 42.86%  |
| AMD                          | 6         | 14.29%  |
| SanDisk                      | 5         | 11.9%   |
| SK hynix                     | 4         | 9.52%   |
| Samsung Electronics          | 3         | 7.14%   |
| Toshiba America Info Systems | 2         | 4.76%   |
| Silicon Motion               | 1         | 2.38%   |
| Phison Electronics           | 1         | 2.38%   |
| Kingston Technology Company  | 1         | 2.38%   |
| ADATA Technology             | 1         | 2.38%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 5         | 11.11%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 3         | 6.67%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                          | 2         | 4.44%   |
| SK hynix BC501 NVMe Solid State Drive                                         | 2         | 4.44%   |
| Intel SSD 600P Series                                                         | 2         | 4.44%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 2         | 4.44%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 2         | 4.44%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 2         | 4.44%   |
| SK hynix PC300 NVMe Solid State Drive 256GB                                   | 1         | 2.22%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                          | 1         | 2.22%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                               | 1         | 2.22%   |
| SanDisk WD Blue SN550 NVMe SSD                                                | 1         | 2.22%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                     | 1         | 2.22%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                    | 1         | 2.22%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                               | 1         | 2.22%   |
| SanDisk PC SN520 NVMe SSD                                                     | 1         | 2.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 1         | 2.22%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 1         | 2.22%   |
| Samsung NVMe SSD Controller 980                                               | 1         | 2.22%   |
| Phison PS5013 E13 NVMe Controller                                             | 1         | 2.22%   |
| Kingston Company Company Non-Volatile memory controller                       | 1         | 2.22%   |
| Intel Tiger Lake-LP SATA Controller                                           | 1         | 2.22%   |
| Intel SSD 660P Series                                                         | 1         | 2.22%   |
| Intel Comet Lake SATA AHCI Controller                                         | 1         | 2.22%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                             | 1         | 2.22%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]         | 1         | 2.22%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                 | 1         | 2.22%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                              | 1         | 2.22%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 1         | 2.22%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 1         | 2.22%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 1         | 2.22%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 1         | 2.22%   |
| ADATA Non-Volatile memory controller                                          | 1         | 2.22%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 22        | 51.16%  |
| NVMe | 19        | 44.19%  |
| RAID | 1         | 2.33%   |
| IDE  | 1         | 2.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 25        | 75.76%  |
| AMD    | 8         | 24.24%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 9.09%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 2         | 6.06%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 6.06%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 3.03%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 3.03%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 3.03%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 3.03%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 3.03%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 3.03%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 1         | 3.03%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 3.03%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 3.03%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 3.03%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 3.03%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 3.03%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 3.03%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 1         | 3.03%   |
| Intel Celeron CPU B830 @ 1.80GHz              | 1         | 3.03%   |
| Intel Celeron CPU 540 @ 1.86GHz               | 1         | 3.03%   |
| Intel Atom x5-E8000 CPU @ 1.04GHz             | 1         | 3.03%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 3.03%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 1         | 3.03%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 1         | 3.03%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 3.03%   |
| AMD Ryzen 7 2700U with Radeon Vega Mobile Gfx | 1         | 3.03%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 1         | 3.03%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 1         | 3.03%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 3.03%   |
| AMD E-350 Processor                           | 1         | 3.03%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 8         | 24.24%  |
| Intel Core i5           | 5         | 15.15%  |
| Other                   | 4         | 12.12%  |
| Intel Celeron           | 4         | 12.12%  |
| AMD Ryzen 7             | 4         | 12.12%  |
| AMD Ryzen 5             | 3         | 9.09%   |
| Intel Pentium Silver    | 1         | 3.03%   |
| Intel Pentium Dual-Core | 1         | 3.03%   |
| Intel Core i3           | 1         | 3.03%   |
| Intel Atom              | 1         | 3.03%   |
| AMD E                   | 1         | 3.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 16        | 48.48%  |
| 2      | 12        | 36.36%  |
| 8      | 2         | 6.06%   |
| 6      | 2         | 6.06%   |
| 1      | 1         | 3.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 33        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 25        | 75.76%  |
| 1      | 8         | 24.24%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 33        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ec    | 4         | 11.76%  |
| 0x806c1    | 4         | 11.76%  |
| Unknown    | 4         | 11.76%  |
| 0x206a7    | 3         | 8.82%   |
| 0x806ea    | 2         | 5.88%   |
| 0x906e9    | 1         | 2.94%   |
| 0x906c0    | 1         | 2.94%   |
| 0x806e9    | 1         | 2.94%   |
| 0x706a8    | 1         | 2.94%   |
| 0x706a1    | 1         | 2.94%   |
| 0x506e3    | 1         | 2.94%   |
| 0x406e3    | 1         | 2.94%   |
| 0x40651    | 1         | 2.94%   |
| 0x1067a    | 1         | 2.94%   |
| 0x10661    | 1         | 2.94%   |
| 0x0a50000c | 1         | 2.94%   |
| 0x08608103 | 1         | 2.94%   |
| 0x08600106 | 1         | 2.94%   |
| 0x08108109 | 1         | 2.94%   |
| 0x08108102 | 1         | 2.94%   |
| 0x0810100b | 1         | 2.94%   |
| 0x05000029 | 1         | 2.94%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 9         | 27.27%  |
| TigerLake     | 4         | 12.12%  |
| SandyBridge   | 3         | 9.09%   |
| Zen+          | 2         | 6.06%   |
| Skylake       | 2         | 6.06%   |
| Goldmont plus | 2         | 6.06%   |
| Unknown       | 2         | 6.06%   |
| Zen 3         | 1         | 3.03%   |
| Zen 2         | 1         | 3.03%   |
| Zen           | 1         | 3.03%   |
| Tremont       | 1         | 3.03%   |
| Silvermont    | 1         | 3.03%   |
| Penryn        | 1         | 3.03%   |
| Haswell       | 1         | 3.03%   |
| Core          | 1         | 3.03%   |
| Bobcat        | 1         | 3.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 24        | 61.54%  |
| AMD    | 10        | 25.64%  |
| Nvidia | 5         | 12.82%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 7.5%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 7.5%    |
| Intel HD Graphics 620                                                                    | 2         | 5%      |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 5%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 5%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 5%      |
| AMD Lucienne                                                                             | 2         | 5%      |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 2.5%    |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 2.5%    |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 2.5%    |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 2.5%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 2.5%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 2.5%    |
| Intel UHD Graphics 620                                                                   | 1         | 2.5%    |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 1         | 2.5%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 2.5%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 2.5%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 2.5%    |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 2.5%    |
| Intel HD Graphics 630                                                                    | 1         | 2.5%    |
| Intel HD Graphics 530                                                                    | 1         | 2.5%    |
| Intel HD Graphics 520                                                                    | 1         | 2.5%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 2.5%    |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 1         | 2.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.5%    |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 2.5%    |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 2.5%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 2.5%    |
| AMD Renoir                                                                               | 1         | 2.5%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 2.5%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 1         | 2.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 20        | 60.61%  |
| 1 x AMD        | 7         | 21.21%  |
| Intel + Nvidia | 3         | 9.09%   |
| AMD + Nvidia   | 2         | 6.06%   |
| Intel + AMD    | 1         | 3.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 29        | 87.88%  |
| Proprietary | 4         | 12.12%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 66.67%  |
| 1.01-2.0   | 4         | 12.12%  |
| 0.01-0.5   | 4         | 12.12%  |
| 5.01-6.0   | 1         | 3.03%   |
| 3.01-4.0   | 1         | 3.03%   |
| 0.51-1.0   | 1         | 3.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 9         | 22.5%   |
| BOE                     | 6         | 15%     |
| AU Optronics            | 6         | 15%     |
| Samsung Electronics     | 4         | 10%     |
| LG Display              | 4         | 10%     |
| Ancor Communications    | 2         | 5%      |
| Toshiba                 | 1         | 2.5%    |
| Philips                 | 1         | 2.5%    |
| PANDA                   | 1         | 2.5%    |
| Lenovo                  | 1         | 2.5%    |
| Dell                    | 1         | 2.5%    |
| CSO                     | 1         | 2.5%    |
| Chi Mei Optoelectronics | 1         | 2.5%    |
| AOC                     | 1         | 2.5%    |
| Acer                    | 1         | 2.5%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Toshiba Internal LCD TOS5091 1366x768 344x193mm 15.5-inch                | 1         | 2.44%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch     | 1         | 2.44%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch     | 1         | 2.44%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 1         | 2.44%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch        | 1         | 2.44%   |
| Samsung Electronics C27F591 SAM0D36 1920x1080 600x340mm 27.2-inch        | 1         | 2.44%   |
| Philips 273PLPH PHL08A8 1920x1080 598x336mm 27.0-inch                    | 1         | 2.44%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch                  | 1         | 2.44%   |
| LG Display LCD Monitor LGD06FB 1920x1080 309x174mm 14.0-inch             | 1         | 2.44%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch             | 1         | 2.44%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch             | 1         | 2.44%   |
| LG Display LCD Monitor LGD053C 1920x1080 309x174mm 14.0-inch             | 1         | 2.44%   |
| Lenovo D22-10 LEN65E4 1920x1080 476x268mm 21.5-inch                      | 1         | 2.44%   |
| Dell U4919DW DELA109 3840x1080 1198x337mm 49.0-inch                      | 1         | 2.44%   |
| CSO LCD Monitor CSO1500 3840x2160 344x194mm 15.5-inch                    | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN15D3 1920x1080 344x193mm 15.5-inch         | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN15CB 1920x1080 344x193mm 15.5-inch         | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN15C5 1366x768 344x193mm 15.5-inch          | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN14E0 1920x1080 309x173mm 13.9-inch         | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN1480 1366x768 309x174mm 14.0-inch          | 1         | 2.44%   |
| Chi Mei Optoelectronics LCD Monitor CMO1113 1366x768 256x144mm 11.6-inch | 1         | 2.44%   |
| BOE NV116WHM-T16 BOE0956 1366x768 256x144mm 11.6-inch                    | 1         | 2.44%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 1         | 2.44%   |
| BOE LCD Monitor BOE091D 1920x1080 309x174mm 14.0-inch                    | 1         | 2.44%   |
| BOE LCD Monitor BOE06CB 1920x1080 344x194mm 15.5-inch                    | 1         | 2.44%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 1         | 2.44%   |
| BOE LCD Monitor BOE0653 1920x1080 309x173mm 13.9-inch                    | 1         | 2.44%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch           | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch            | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch           | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO282B 3840x2160 293x165mm 13.2-inch           | 1         | 2.44%   |
| AOC AG323FWG3R3 AOC3230 1920x1080 698x393mm 31.5-inch                    | 1         | 2.44%   |
| Ancor Communications C624B ACI24A9 1920x1200 518x324mm 24.1-inch         | 1         | 2.44%   |
| Ancor Communications ASUS VS229 ACI22D3 1920x1080 475x267mm 21.5-inch    | 1         | 2.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 19        | 50%     |
| 1366x768 (WXGA)   | 12        | 31.58%  |
| 3840x2160 (4K)    | 2         | 5.26%   |
| 3840x1080         | 1         | 2.63%   |
| 2560x1440 (QHD)   | 1         | 2.63%   |
| 2256x1504         | 1         | 2.63%   |
| 1920x1200 (WUXGA) | 1         | 2.63%   |
| 1280x800 (WXGA)   | 1         | 2.63%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 18        | 45%     |
| 14     | 6         | 15%     |
| 13     | 6         | 15%     |
| 27     | 2         | 5%      |
| 21     | 2         | 5%      |
| 11     | 2         | 5%      |
| 49     | 1         | 2.5%    |
| 31     | 1         | 2.5%    |
| 24     | 1         | 2.5%    |
| 23     | 1         | 2.5%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 26        | 65%     |
| 201-300     | 5         | 12.5%   |
| 501-600     | 4         | 10%     |
| 401-500     | 2         | 5%      |
| 601-700     | 1         | 2.5%    |
| 351-400     | 1         | 2.5%    |
| 1001-1500   | 1         | 2.5%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 31        | 88.57%  |
| 16/10 | 2         | 5.71%   |
| 32/9  | 1         | 2.86%   |
| 3/2   | 1         | 2.86%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 18        | 45%     |
| 81-90          | 10        | 25%     |
| 71-80          | 2         | 5%      |
| 51-60          | 2         | 5%      |
| 301-350        | 2         | 5%      |
| 201-250        | 2         | 5%      |
| 351-500        | 1         | 2.5%    |
| 251-300        | 1         | 2.5%    |
| 151-200        | 1         | 2.5%    |
| 501-1000       | 1         | 2.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 17        | 44.74%  |
| 101-120       | 10        | 26.32%  |
| 51-100        | 7         | 18.42%  |
| More than 240 | 2         | 5.26%   |
| 161-240       | 2         | 5.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 26        | 78.79%  |
| 2     | 6         | 18.18%  |
| 3     | 1         | 3.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 17        | 35.42%  |
| Realtek Semiconductor    | 13        | 27.08%  |
| Qualcomm Atheros         | 9         | 18.75%  |
| MediaTek                 | 2         | 4.17%   |
| Marvell Technology Group | 2         | 4.17%   |
| TP-Link                  | 1         | 2.08%   |
| T & A Mobile Phones      | 1         | 2.08%   |
| Dell                     | 1         | 2.08%   |
| Broadcom                 | 1         | 2.08%   |
| ASIX Electronics         | 1         | 2.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9         | 15.79%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 7.02%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 7.02%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 5.26%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 3.51%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 3.51%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 3.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.51%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.75%   |
| T & A Mobile Phones 5007Z                                         | 1         | 1.75%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 1.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.75%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.75%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 1.75%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.75%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 1.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.75%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.75%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.75%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1         | 1.75%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 1.75%   |
| Intel Wireless 8265 / 8275                                        | 1         | 1.75%   |
| Intel Wireless 8260                                               | 1         | 1.75%   |
| Intel Wireless 7265                                               | 1         | 1.75%   |
| Intel Wireless 3165                                               | 1         | 1.75%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 1         | 1.75%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.75%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.75%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.75%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.75%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.75%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 1.75%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                     | 1         | 1.75%   |
| Dell DW5550                                                       | 1         | 1.75%   |
| Broadcom BCM4311 802.11b/g WLAN                                   | 1         | 1.75%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.75%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 17        | 51.52%  |
| Qualcomm Atheros      | 8         | 24.24%  |
| Realtek Semiconductor | 5         | 15.15%  |
| MediaTek              | 2         | 6.06%   |
| Broadcom              | 1         | 3.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 12.12%  |
| Intel Wi-Fi 6 AX200                                            | 4         | 12.12%  |
| Intel Wi-Fi 6 AX201                                            | 3         | 9.09%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 6.06%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 6.06%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 3.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 3.03%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 3.03%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 3.03%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 3.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 3.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 3.03%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 1         | 3.03%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 3.03%   |
| Intel Wireless 8265 / 8275                                     | 1         | 3.03%   |
| Intel Wireless 8260                                            | 1         | 3.03%   |
| Intel Wireless 7265                                            | 1         | 3.03%   |
| Intel Wireless 3165                                            | 1         | 3.03%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 1         | 3.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 3.03%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 3.03%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                  | 1         | 3.03%   |
| Broadcom BCM4311 802.11b/g WLAN                                | 1         | 3.03%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 10        | 45.45%  |
| Intel                    | 6         | 27.27%  |
| Qualcomm Atheros         | 2         | 9.09%   |
| Marvell Technology Group | 2         | 9.09%   |
| TP-Link                  | 1         | 4.55%   |
| ASIX Electronics         | 1         | 4.55%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9         | 40.91%  |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 9.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 9.09%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 4.55%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 4.55%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 4.55%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 4.55%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 4.55%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 4.55%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 4.55%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 4.55%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 4.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 33        | 57.89%  |
| Ethernet | 22        | 38.6%   |
| Modem    | 1         | 1.75%   |
| Unknown  | 1         | 1.75%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 26        | 78.79%  |
| Ethernet | 7         | 21.21%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 20        | 60.61%  |
| 1     | 12        | 36.36%  |
| 0     | 1         | 3.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 25        | 75.76%  |
| Yes  | 8         | 24.24%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 15        | 51.72%  |
| Qualcomm Atheros Communications | 4         | 13.79%  |
| Realtek Semiconductor           | 2         | 6.9%    |
| Lite-On Technology              | 2         | 6.9%    |
| Toshiba                         | 1         | 3.45%   |
| MediaTek                        | 1         | 3.45%   |
| IMC Networks                    | 1         | 3.45%   |
| Foxconn / Hon Hai               | 1         | 3.45%   |
| Dell                            | 1         | 3.45%   |
| Broadcom                        | 1         | 3.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                      | 5         | 17.24%  |
| Intel Bluetooth wireless interface         | 4         | 13.79%  |
| Intel AX200 Bluetooth                      | 4         | 13.79%  |
| Qualcomm Atheros  Bluetooth Device         | 3         | 10.34%  |
| Intel AX210 Bluetooth                      | 2         | 6.9%    |
| Toshiba RT Bluetooth Radio                 | 1         | 3.45%   |
| Realtek RTL8821A Bluetooth                 | 1         | 3.45%   |
| Realtek  Bluetooth 4.2 Adapter             | 1         | 3.45%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0      | 1         | 3.45%   |
| MediaTek Wireless_Device                   | 1         | 3.45%   |
| Lite-On Wireless_Device                    | 1         | 3.45%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth | 1         | 3.45%   |
| IMC Networks Bluetooth Radio               | 1         | 3.45%   |
| Foxconn / Hon Hai Bluetooth Device         | 1         | 3.45%   |
| Dell DW375 Bluetooth Module                | 1         | 3.45%   |
| Broadcom Bluetooth 2.1 Device              | 1         | 3.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 25        | 64.1%   |
| AMD                 | 9         | 23.08%  |
| Nvidia              | 3         | 7.69%   |
| Samsung Electronics | 1         | 2.56%   |
| Conexant Systems    | 1         | 2.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 15.22%  |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 8.7%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 4         | 8.7%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 6.52%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 6.52%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 4.35%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 4.35%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 4.35%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 4.35%   |
| Samsung Electronics USBC Headset                                                                  | 1         | 2.17%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 2.17%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 2.17%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 2.17%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 2.17%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 2.17%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 2.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.17%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 2.17%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 2.17%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 2.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1         | 2.17%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 2.17%   |
| Conexant Systems Hi-Res Audio                                                                     | 1         | 2.17%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 2.17%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 2.17%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 2.17%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 38.1%   |
| SK hynix            | 3         | 14.29%  |
| Micron Technology   | 3         | 14.29%  |
| Crucial             | 2         | 9.52%   |
| A-DATA Technology   | 2         | 9.52%   |
| Unknown             | 1         | 4.76%   |
| Team                | 1         | 4.76%   |
| G.Skill             | 1         | 4.76%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 4.55%   |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s            | 1         | 4.55%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 4.55%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 4.55%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 4.55%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 1         | 4.55%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 4.55%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 4.55%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 1         | 4.55%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 4.55%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 4.55%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 4.55%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 4.55%   |
| Samsung RAM K4E8E324EB-EGCF 2GB SODIMM LPDDR3 1867MT/s           | 1         | 4.55%   |
| Micron RAM 8HTF12864HDY-667E1 1GB SODIMM DDR2 667MT/s            | 1         | 4.55%   |
| Micron RAM 8ATF1G64HZ-2G3H1 8GB SODIMM DDR4 2400MT/s             | 1         | 4.55%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 1         | 4.55%   |
| G.Skill RAM F4-3200C22-16GRS 16GB SODIMM DDR4 3200MT/s           | 1         | 4.55%   |
| Crucial RAM CT8G4SFS824A.M8FJ 8GB SODIMM DDR4 2400MT/s           | 1         | 4.55%   |
| Crucial RAM CT16G4SFD8213.C16FBD 16GB SODIMM DDR4 2133MT/s       | 1         | 4.55%   |
| A-DATA RAM Module 8192MB SODIMM DDR4 2133MT/s                    | 1         | 4.55%   |
| A-DATA RAM AL1P32NCST2-B87S 16GB SODIMM DDR4 3200MT/s            | 1         | 4.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 10        | 55.56%  |
| LPDDR3 | 3         | 16.67%  |
| DDR3   | 2         | 11.11%  |
| LPDDR4 | 1         | 5.56%   |
| DDR2   | 1         | 5.56%   |
| DDR    | 1         | 5.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 14        | 82.35%  |
| Row Of Chips | 3         | 17.65%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 16384 | 6         | 33.33%  |
| 8192  | 5         | 27.78%  |
| 4096  | 3         | 16.67%  |
| 32768 | 2         | 11.11%  |
| 2048  | 1         | 5.56%   |
| 1024  | 1         | 5.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 6         | 31.58%  |
| 2133    | 4         | 21.05%  |
| 2667    | 2         | 10.53%  |
| 4267    | 1         | 5.26%   |
| 2400    | 1         | 5.26%   |
| 1867    | 1         | 5.26%   |
| 1600    | 1         | 5.26%   |
| 1333    | 1         | 5.26%   |
| 667     | 1         | 5.26%   |
| Unknown | 1         | 5.26%   |

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
| Realtek Semiconductor                  | 5         | 16.67%  |
| Quanta                                 | 4         | 13.33%  |
| Microdia                               | 4         | 13.33%  |
| Sunplus Innovation Technology          | 3         | 10%     |
| IMC Networks                           | 3         | 10%     |
| Chicony Electronics                    | 3         | 10%     |
| Cheng Uei Precision Industry (Foxlink) | 2         | 6.67%   |
| Z-Star Microelectronics                | 1         | 3.33%   |
| Syntek                                 | 1         | 3.33%   |
| Microsoft                              | 1         | 3.33%   |
| Logitech                               | 1         | 3.33%   |
| Importek                               | 1         | 3.33%   |
| Acer                                   | 1         | 3.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                   | 3         | 10%     |
| Sunplus Integrated_Webcam_HD                                    | 2         | 6.67%   |
| Quanta HD User Facing                                           | 2         | 6.67%   |
| IMC Networks Integrated Camera                                  | 2         | 6.67%   |
| Z-Star Webcam                                                   | 1         | 3.33%   |
| Syntek Integrated Camera                                        | 1         | 3.33%   |
| Sunplus Laptop_Integrated_Webcam_HD                             | 1         | 3.33%   |
| Realtek Laptop Camera                                           | 1         | 3.33%   |
| Realtek Integrated_Webcam_HD                                    | 1         | 3.33%   |
| Realtek Integrated Webcam_HD                                    | 1         | 3.33%   |
| Realtek Integrated Webcam                                       | 1         | 3.33%   |
| Realtek HD WebCam                                               | 1         | 3.33%   |
| Quanta VGA WebCam                                               | 1         | 3.33%   |
| Quanta USB2.0 HD UVC WebCam                                     | 1         | 3.33%   |
| Microsoft LifeCam Studio                                        | 1         | 3.33%   |
| Microdia REDRAGON Live Camera Audio                             | 1         | 3.33%   |
| Logitech Webcam C270                                            | 1         | 3.33%   |
| Importek TOSHIBA Web Camera - HD                                | 1         | 3.33%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 1         | 3.33%   |
| Chicony Sony Visual Communication Camera                        | 1         | 3.33%   |
| Chicony Integrated Camera                                       | 1         | 3.33%   |
| Chicony EasyCamera                                              | 1         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                   | 1         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 3.33%   |
| Acer Lenovo EasyCamera                                          | 1         | 3.33%   |

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
| 0     | 20        | 60.61%  |
| 1     | 7         | 21.21%  |
| 2     | 6         | 18.18%  |

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

