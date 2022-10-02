PureOS - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for PureOS.

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

Total: 40

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Apple         | MacBook9,1                  | [e6898c8aa0](https://linux-hardware.org/?probe=e6898c8aa0) | Sep 19, 2022 |
| Acer          | Swift SF113-31              | [3c29601232](https://linux-hardware.org/?probe=3c29601232) | Sep 05, 2022 |
| Acer          | Swift SF113-31              | [f3753d28fb](https://linux-hardware.org/?probe=f3753d28fb) | Sep 05, 2022 |
| Purism        | Librem 14                   | [89d920a7d2](https://linux-hardware.org/?probe=89d920a7d2) | Jun 11, 2022 |
| Apple         | MacBookPro6,1               | [40d33cea3f](https://linux-hardware.org/?probe=40d33cea3f) | May 23, 2022 |
| Purism        | Librem 14                   | [9d078217f1](https://linux-hardware.org/?probe=9d078217f1) | Apr 23, 2022 |
| HP            | Pavilion g6                 | [796bf7f467](https://linux-hardware.org/?probe=796bf7f467) | Apr 23, 2022 |
| Dell          | Inspiron 15-3567            | [8cbc7d1caf](https://linux-hardware.org/?probe=8cbc7d1caf) | Apr 20, 2022 |
| Purism        | Librem 15 v4                | [061aeeecf7](https://linux-hardware.org/?probe=061aeeecf7) | Apr 13, 2022 |
| Lenovo        | ThinkPad T440p              | [45a1ee6fbf](https://linux-hardware.org/?probe=45a1ee6fbf) | Apr 12, 2022 |
| HP            | Pavilion Notebook           | [c0dd92f23c](https://linux-hardware.org/?probe=c0dd92f23c) | Apr 03, 2022 |
| Acer          | Nitro AN515-43              | [e1386a38c7](https://linux-hardware.org/?probe=e1386a38c7) | Mar 20, 2022 |
| Dell          | Inspiron 15-3567            | [c8723d2dd9](https://linux-hardware.org/?probe=c8723d2dd9) | Feb 21, 2022 |
| Dell          | Inspiron 15-3567            | [45529bb469](https://linux-hardware.org/?probe=45529bb469) | Feb 21, 2022 |
| Lenovo        | ThinkPad T540p 20BFS23T0... | [c49acb0edf](https://linux-hardware.org/?probe=c49acb0edf) | Feb 21, 2022 |
| Lenovo        | ThinkPad T540p 20BFS23T0... | [6f13abc9eb](https://linux-hardware.org/?probe=6f13abc9eb) | Feb 21, 2022 |
| Acer          | Aspire E5-553G              | [1f5badca6e](https://linux-hardware.org/?probe=1f5badca6e) | Feb 06, 2022 |
| Lenovo        | ThinkPad E480 20KN003SUS    | [ad043b077a](https://linux-hardware.org/?probe=ad043b077a) | Nov 25, 2021 |
| Apple         | MacBookPro14,2              | [5f4d435f0d](https://linux-hardware.org/?probe=5f4d435f0d) | Nov 24, 2021 |
| Purism        | Librem 14                   | [68e8f5b427](https://linux-hardware.org/?probe=68e8f5b427) | Sep 27, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [077ff209de](https://linux-hardware.org/?probe=077ff209de) | Aug 18, 2021 |
| Purism        | Librem 14                   | [295a2a1392](https://linux-hardware.org/?probe=295a2a1392) | Jul 15, 2021 |
| Purism        | Librem 14                   | [49d9b561c6](https://linux-hardware.org/?probe=49d9b561c6) | Jul 15, 2021 |
| Toshiba       | Satellite L500D             | [b830927060](https://linux-hardware.org/?probe=b830927060) | Jul 04, 2021 |
| Dell          | XPS 13 9370                 | [c8937f439d](https://linux-hardware.org/?probe=c8937f439d) | Jun 09, 2021 |
| Purism        | Librem 14                   | [0c18b37b73](https://linux-hardware.org/?probe=0c18b37b73) | Jun 01, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | [79c01fbf3a](https://linux-hardware.org/?probe=79c01fbf3a) | Oct 28, 2020 |
| Unknown       | Unknown                     | [c24817ee80](https://linux-hardware.org/?probe=c24817ee80) | Sep 15, 2020 |
| HP            | Pavilion g6                 | [eb23d17143](https://linux-hardware.org/?probe=eb23d17143) | Jul 15, 2020 |
| Lenovo        | ThinkPad T440 20B60044RT    | [db8ba33d45](https://linux-hardware.org/?probe=db8ba33d45) | Jun 02, 2020 |
| Purism        | Librem 15 v4                | [d9f38d66c3](https://linux-hardware.org/?probe=d9f38d66c3) | Apr 29, 2020 |
| Notebook      | P17SM                       | [730c65e65d](https://linux-hardware.org/?probe=730c65e65d) | Apr 22, 2020 |
| Purism        | Librem 15 v4                | [6e5f1119b7](https://linux-hardware.org/?probe=6e5f1119b7) | Apr 10, 2020 |
| Purism        | Librem 15 v3                | [a43311f999](https://linux-hardware.org/?probe=a43311f999) | Dec 18, 2019 |
| Purism        | Librem 13 v4                | [6d7a537e86](https://linux-hardware.org/?probe=6d7a537e86) | Nov 15, 2019 |
| Dell          | Inspiron 5547               | [689dfea547](https://linux-hardware.org/?probe=689dfea547) | Oct 25, 2019 |
| Purism        | Librem 13 v4                | [6d7c18d329](https://linux-hardware.org/?probe=6d7c18d329) | Oct 18, 2019 |
| Lenovo        | G505s 20255                 | [bce345b263](https://linux-hardware.org/?probe=bce345b263) | Aug 30, 2019 |
| Purism        | Librem 13 v2                | [3e70a8dff1](https://linux-hardware.org/?probe=3e70a8dff1) | Jul 13, 2019 |
| Purism        | Librem 15 v3                | [02e23b6024](https://linux-hardware.org/?probe=02e23b6024) | May 21, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| PureOS 10.0 | 10        | 32.26%  |
| PureOS 10   | 9         | 29.03%  |
| PureOS 9.0  | 8         | 25.81%  |
| PureOS 9    | 2         | 6.45%   |
| PureOS 8    | 2         | 6.45%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| PureOS | 30        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Notebooks | Percent |
|----------------------------------|-----------|---------|
| 4.19.0-5-amd64                   | 8         | 25%     |
| 5.10.0-13-amd64                  | 5         | 15.63%  |
| 5.10.0-8-amd64                   | 3         | 9.38%   |
| 5.10.0-14-amd64                  | 3         | 9.38%   |
| 5.10.0-7-amd64                   | 2         | 6.25%   |
| 5.10.0-11-amd64                  | 2         | 6.25%   |
| 5.7.0-1-librem5                  | 1         | 3.13%   |
| 5.7.0-0.38-1-pinebookpro-hwaccel | 1         | 3.13%   |
| 5.15.0-2-amd64                   | 1         | 3.13%   |
| 5.10.0-9-amd64                   | 1         | 3.13%   |
| 5.10.0-6-amd64                   | 1         | 3.13%   |
| 5.10.0-17-amd64                  | 1         | 3.13%   |
| 5.10.0-12-amd64                  | 1         | 3.13%   |
| 4.19.0-14-amd64                  | 1         | 3.13%   |
| 4.16.0-1-amd64                   | 1         | 3.13%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 18        | 58.06%  |
| 4.19.0  | 9         | 29.03%  |
| 5.7.0   | 2         | 6.45%   |
| 5.15.0  | 1         | 3.23%   |
| 4.16.0  | 1         | 3.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 18        | 58.06%  |
| 4.19    | 9         | 29.03%  |
| 5.7     | 2         | 6.45%   |
| 5.15    | 1         | 3.23%   |
| 4.16    | 1         | 3.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 28        | 93.33%  |
| aarch64 | 2         | 6.67%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 24        | 77.42%  |
| Unknown         | 4         | 12.9%   |
| MATE            | 1         | 3.23%   |
| KDE5            | 1         | 3.23%   |
| GNOME Flashback | 1         | 3.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 22        | 68.75%  |
| X11     | 5         | 15.63%  |
| Unknown | 4         | 12.5%   |
| Tty     | 1         | 3.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 17        | 56.67%  |
| GDM     | 10        | 33.33%  |
| GDM3    | 3         | 10%     |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 14        | 43.75%  |
| Unknown | 4         | 12.5%   |
| pl_PL   | 2         | 6.25%   |
| en_GB   | 2         | 6.25%   |
| de_DE   | 2         | 6.25%   |
| zh_CN   | 1         | 3.13%   |
| ru_RU   | 1         | 3.13%   |
| pt_PT   | 1         | 3.13%   |
| it_IT   | 1         | 3.13%   |
| es_CR   | 1         | 3.13%   |
| en_IL   | 1         | 3.13%   |
| en_AU   | 1         | 3.13%   |
| C       | 1         | 3.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 26        | 86.67%  |
| EFI  | 4         | 13.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 27        | 90%     |
| Unknown | 2         | 6.67%   |
| Ext2    | 1         | 3.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 18        | 60%     |
| MBR     | 8         | 26.67%  |
| GPT     | 4         | 13.33%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 24        | 80%     |
| Yes       | 6         | 20%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 27        | 90%     |
| Yes       | 3         | 10%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Purism            | 10        | 33.33%  |
| Lenovo            | 5         | 16.67%  |
| Hewlett-Packard   | 3         | 10%     |
| Dell              | 3         | 10%     |
| Apple             | 3         | 10%     |
| Acer              | 2         | 6.67%   |
| Toshiba           | 1         | 3.33%   |
| Pine Microsystems | 1         | 3.33%   |
| Notebook          | 1         | 3.33%   |
| Unknown           | 1         | 3.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Purism Librem 14                      | 5         | 16.67%  |
| Purism Librem 15 v4                   | 2         | 6.67%   |
| HP Pavilion g6                        | 2         | 6.67%   |
| Toshiba Satellite L500D               | 1         | 3.33%   |
| Purism Librem 15 v3                   | 1         | 3.33%   |
| Purism Librem 13 v4                   | 1         | 3.33%   |
| Purism Librem 13 v2                   | 1         | 3.33%   |
| Pine Microsystems Pine64 Pinebook Pro | 1         | 3.33%   |
| Notebook P17SM                        | 1         | 3.33%   |
| Lenovo ThinkPad T540p 20BFS23T00      | 1         | 3.33%   |
| Lenovo ThinkPad T440p                 | 1         | 3.33%   |
| Lenovo ThinkPad T440 20B60044RT       | 1         | 3.33%   |
| Lenovo ThinkPad E480 20KN003SUS       | 1         | 3.33%   |
| Lenovo ThinkPad 13 2nd Gen 20J2S00G00 | 1         | 3.33%   |
| HP Pavilion Notebook                  | 1         | 3.33%   |
| Dell XPS 13 9370                      | 1         | 3.33%   |
| Dell Inspiron 5547                    | 1         | 3.33%   |
| Dell Inspiron 15-3567                 | 1         | 3.33%   |
| Apple MacBookPro6,1                   | 1         | 3.33%   |
| Apple MacBookPro14,2                  | 1         | 3.33%   |
| Apple MacBook9,1                      | 1         | 3.33%   |
| Acer Swift SF113-31                   | 1         | 3.33%   |
| Acer Nitro AN515-43                   | 1         | 3.33%   |
| Unknown                               | 1         | 3.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Purism Librem            | 10        | 33.33%  |
| Lenovo ThinkPad          | 5         | 16.67%  |
| HP Pavilion              | 3         | 10%     |
| Dell Inspiron            | 2         | 6.67%   |
| Toshiba Satellite        | 1         | 3.33%   |
| Pine Microsystems Pine64 | 1         | 3.33%   |
| Notebook P17SM           | 1         | 3.33%   |
| Dell XPS                 | 1         | 3.33%   |
| Apple MacBookPro6        | 1         | 3.33%   |
| Apple MacBookPro14       | 1         | 3.33%   |
| Apple MacBook9           | 1         | 3.33%   |
| Acer Swift               | 1         | 3.33%   |
| Acer Nitro               | 1         | 3.33%   |
| Unknown                  | 1         | 3.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 6         | 20%     |
| 2017    | 5         | 16.67%  |
| 2019    | 4         | 13.33%  |
| 2013    | 3         | 10%     |
| 2020    | 2         | 6.67%   |
| 2018    | 2         | 6.67%   |
| 2011    | 2         | 6.67%   |
| Unknown | 2         | 6.67%   |
| 2016    | 1         | 3.33%   |
| 2015    | 1         | 3.33%   |
| 2014    | 1         | 3.33%   |
| 2009    | 1         | 3.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 30        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 30        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 19        | 63.33%  |
| Yes  | 11        | 36.67%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 16.01-24.0 | 9         | 30%     |
| 4.01-8.0   | 6         | 20%     |
| 32.01-64.0 | 6         | 20%     |
| 3.01-4.0   | 4         | 13.33%  |
| 8.01-16.0  | 3         | 10%     |
| 24.01-32.0 | 1         | 3.33%   |
| 2.01-3.0   | 1         | 3.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 10        | 31.25%  |
| 3.01-4.0  | 9         | 28.13%  |
| 1.01-2.0  | 6         | 18.75%  |
| 4.01-8.0  | 5         | 15.63%  |
| 8.01-16.0 | 2         | 6.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 20        | 66.67%  |
| 2      | 10        | 33.33%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 23        | 76.67%  |
| Yes       | 7         | 23.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 23        | 76.67%  |
| No        | 7         | 23.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 27        | 90%     |
| No        | 3         | 10%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 23        | 76.67%  |
| No        | 7         | 23.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Notebooks | Percent |
|------------------------|-----------|---------|
| USA                    | 7         | 21.88%  |
| UK                     | 4         | 12.5%   |
| Germany                | 3         | 9.38%   |
| Canada                 | 3         | 9.38%   |
| Australia              | 2         | 6.25%   |
| Turkey                 | 1         | 3.13%   |
| South Africa           | 1         | 3.13%   |
| Russia                 | 1         | 3.13%   |
| Portugal               | 1         | 3.13%   |
| Poland                 | 1         | 3.13%   |
| Italy                  | 1         | 3.13%   |
| Israel                 | 1         | 3.13%   |
| Iran                   | 1         | 3.13%   |
| France                 | 1         | 3.13%   |
| Costa Rica             | 1         | 3.13%   |
| China                  | 1         | 3.13%   |
| Brazil                 | 1         | 3.13%   |
| Bosnia and Herzegovina | 1         | 3.13%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| London             | 2         | 6.25%   |
| Windsor            | 1         | 3.13%   |
| Warsaw             | 1         | 3.13%   |
| Vancouver          | 1         | 3.13%   |
| Thorpe Hamlet      | 1         | 3.13%   |
| Tel Aviv           | 1         | 3.13%   |
| Stuttgart          | 1         | 3.13%   |
| Spencer            | 1         | 3.13%   |
| Seattle            | 1         | 3.13%   |
| San Jose           | 1         | 3.13%   |
| Paris              | 1         | 3.13%   |
| New York           | 1         | 3.13%   |
| Montreal           | 1         | 3.13%   |
| Milwaukee          | 1         | 3.13%   |
| Melbourne          | 1         | 3.13%   |
| Mankato            | 1         | 3.13%   |
| Krasnogorsk        | 1         | 3.13%   |
| Istanbul           | 1         | 3.13%   |
| Guimaraes          | 1         | 3.13%   |
| Eberswalde         | 1         | 3.13%   |
| Cape Town          | 1         | 3.13%   |
| Camden             | 1         | 3.13%   |
| Big Sky            | 1         | 3.13%   |
| Berlin             | 1         | 3.13%   |
| Banja Luka         | 1         | 3.13%   |
| Bandar-e Asalūyeh | 1         | 3.13%   |
| Araçatuba         | 1         | 3.13%   |
| Antioch            | 1         | 3.13%   |
| Ankang             | 1         | 3.13%   |
| Almese             | 1         | 3.13%   |
| Adelaide           | 1         | 3.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 15     | 28.95%  |
| Unknown             | 3         | 3      | 7.89%   |
| Seagate             | 3         | 3      | 7.89%   |
| HGST                | 3         | 3      | 7.89%   |
| Crucial             | 2         | 4      | 5.26%   |
| Apple               | 2         | 4      | 5.26%   |
| A-DATA Technology   | 2         | 2      | 5.26%   |
| WDC                 | 1         | 1      | 2.63%   |
| Transcend           | 1         | 1      | 2.63%   |
| Toshiba             | 1         | 1      | 2.63%   |
| SanDisk             | 1         | 1      | 2.63%   |
| Plextor             | 1         | 1      | 2.63%   |
| Phison              | 1         | 1      | 2.63%   |
| Mushkin             | 1         | 1      | 2.63%   |
| JMicron Technology  | 1         | 1      | 2.63%   |
| Intel               | 1         | 1      | 2.63%   |
| Hitachi             | 1         | 1      | 2.63%   |
| BIWIN               | 1         | 1      | 2.63%   |
| ADATA Technology    | 1         | 1      | 2.63%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST1000LM048-2E7172 1TB      | 2         | 5%      |
| Samsung SSD 970 PRO 1TB             | 2         | 5%      |
| WDC WDS100T2B0C-00PXH0 1TB          | 1         | 2.5%    |
| Unknown MMC Card  64GB              | 1         | 2.5%    |
| Unknown MMC Card  32GB              | 1         | 2.5%    |
| Unknown DA4128  128GB               | 1         | 2.5%    |
| Transcend TS240GMTS420S 240GB SSD   | 1         | 2.5%    |
| Toshiba NVMe SSD Drive 512GB        | 1         | 2.5%    |
| Seagate NVMe SSD Drive 2TB          | 1         | 2.5%    |
| SanDisk SDSSDH3500G 500GB           | 1         | 2.5%    |
| Samsung SSD 970 EVO Plus 500GB      | 1         | 2.5%    |
| Samsung SSD 970 EVO 250GB           | 1         | 2.5%    |
| Samsung SSD 960 EVO 500GB           | 1         | 2.5%    |
| Samsung SSD 960 EVO 250GB           | 1         | 2.5%    |
| Samsung SSD 860 EVO 500GB           | 1         | 2.5%    |
| Samsung SSD 860 EVO 250GB           | 1         | 2.5%    |
| Samsung SSD 860 EVO 1TB             | 1         | 2.5%    |
| Samsung SSD 850 EVO 500GB           | 1         | 2.5%    |
| Samsung SSD 850 EVO 250GB           | 1         | 2.5%    |
| Samsung NVMe SSD Drive 1TB          | 1         | 2.5%    |
| Plextor PX-1TM6Pro 1024GB SSD       | 1         | 2.5%    |
| Phison PM8512GPTCB4B8TF-E13T4 512GB | 1         | 2.5%    |
| Mushkin MKNSSDRE250GB-LT            | 1         | 2.5%    |
| JMicron Generic 120GB               | 1         | 2.5%    |
| Intel SSDSC2BF180A4H 180GB          | 1         | 2.5%    |
| Hitachi HTS545050A7E380 500GB       | 1         | 2.5%    |
| HGST HTS721010A9E630 1TB            | 1         | 2.5%    |
| HGST HTS545050B7E660 500GB          | 1         | 2.5%    |
| HGST HTS541010A9E680 1TB            | 1         | 2.5%    |
| Crucial CT250MX500SSD4 250GB        | 1         | 2.5%    |
| Crucial CT2000MX500SSD1 2TB         | 1         | 2.5%    |
| BIWIN SSD 120GB                     | 1         | 2.5%    |
| Apple SSD AP0512J 8.1KB             | 1         | 2.5%    |
| Apple NVMe SSD Drive 8KB            | 1         | 2.5%    |
| Apple NVMe SSD Drive 256GB          | 1         | 2.5%    |
| ADATA NVMe SSD Drive 512GB          | 1         | 2.5%    |
| A-DATA SU630 240GB SSD              | 1         | 2.5%    |
| A-DATA IM2S3138E-128GM-B 128GB SSD  | 1         | 2.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HGST    | 3         | 3      | 50%     |
| Seagate | 2         | 2      | 33.33%  |
| Hitachi | 1         | 1      | 16.67%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 8      | 37.5%   |
| Crucial             | 2         | 4      | 12.5%   |
| A-DATA Technology   | 2         | 2      | 12.5%   |
| Transcend           | 1         | 1      | 6.25%   |
| SanDisk             | 1         | 1      | 6.25%   |
| Plextor             | 1         | 1      | 6.25%   |
| Mushkin             | 1         | 1      | 6.25%   |
| Intel               | 1         | 1      | 6.25%   |
| BIWIN               | 1         | 1      | 6.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 14        | 17     | 37.84%  |
| SSD  | 14        | 20     | 37.84%  |
| HDD  | 6         | 6      | 16.22%  |
| MMC  | 3         | 3      | 8.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 17        | 25     | 48.57%  |
| NVMe | 13        | 16     | 37.14%  |
| MMC  | 3         | 3      | 8.57%   |
| SAS  | 2         | 2      | 5.71%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 12        | 18     | 63.16%  |
| 0.51-1.0   | 5         | 5      | 26.32%  |
| 1.01-2.0   | 2         | 3      | 10.53%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 14        | 46.67%  |
| 101-250    | 4         | 13.33%  |
| Unknown    | 3         | 10%     |
| 251-500    | 2         | 6.67%   |
| 21-50      | 2         | 6.67%   |
| 501-1000   | 2         | 6.67%   |
| 2001-3000  | 1         | 3.33%   |
| 1001-2000  | 1         | 3.33%   |
| 51-100     | 1         | 3.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 19        | 63.33%  |
| 21-50    | 3         | 10%     |
| 501-1000 | 3         | 10%     |
| Unknown  | 3         | 10%     |
| 251-500  | 1         | 3.33%   |
| 51-100   | 1         | 3.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                      | Notebooks | Drives | Percent |
|----------------------------|-----------|--------|---------|
| Intel SSDSC2BF180A4H 180GB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| Intel  | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1         | 1      | 100%    |

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
| Detected | 20        | 30     | 64.52%  |
| Works    | 10        | 15     | 32.26%  |
| Malfunc  | 1         | 1      | 3.23%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 17        | 53.13%  |
| Samsung Electronics          | 6         | 18.75%  |
| Apple                        | 2         | 6.25%   |
| AMD                          | 2         | 6.25%   |
| Toshiba America Info Systems | 1         | 3.13%   |
| Seagate Technology           | 1         | 3.13%   |
| SanDisk                      | 1         | 3.13%   |
| Phison Electronics           | 1         | 3.13%   |
| ADATA Technology             | 1         | 3.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 21.88%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 12.5%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 9.38%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 6.25%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 6.25%   |
| Apple S3X NVMe Controller                                                      | 2         | 6.25%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 3.13%   |
| Seagate FireCuda 510 SSD                                                       | 1         | 3.13%   |
| SanDisk Non-Volatile memory controller                                         | 1         | 3.13%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 3.13%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 3.13%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 3.13%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 3.13%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 3.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 3.13%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 1         | 3.13%   |
| ADATA Non-Volatile memory controller                                           | 1         | 3.13%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 19        | 59.38%  |
| NVMe | 13        | 40.63%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 26        | 86.67%  |
| ARM    | 2         | 6.67%   |
| AMD    | 2         | 6.67%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10710U CPU @ 1.10GHz            | 5         | 16.67%  |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 13.33%  |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 6.67%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 6.67%   |
| ARM Processor                                 | 2         | 6.67%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 3.33%   |
| Intel Core m5-6Y54 CPU @ 1.10GHz              | 1         | 3.33%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 3.33%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 3.33%   |
| Intel Core i7-7567U CPU @ 3.50GHz             | 1         | 3.33%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz            | 1         | 3.33%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 1         | 3.33%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 3.33%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 3.33%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 1         | 3.33%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 1         | 3.33%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 1         | 3.33%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 1         | 3.33%   |
| AMD Turion II Dual-Core Mobile M520           | 1         | 3.33%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 1         | 3.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 18        | 60%     |
| Intel Core i5           | 3         | 10%     |
| Intel Core i3           | 3         | 10%     |
| Other                   | 2         | 6.67%   |
| Intel Pentium           | 1         | 3.33%   |
| Intel Core m5           | 1         | 3.33%   |
| AMD Turion II Dual-Core | 1         | 3.33%   |
| AMD Ryzen 5             | 1         | 3.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 16        | 53.33%  |
| 4      | 9         | 30%     |
| 6      | 5         | 16.67%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 30        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 26        | 86.67%  |
| 1      | 4         | 13.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 28        | 90.32%  |
| Unknown        | 3         | 9.68%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 70%     |
| 0xa0660    | 3         | 10%     |
| 0x406e3    | 3         | 10%     |
| 0x806e9    | 1         | 3.33%   |
| 0x40651    | 1         | 3.33%   |
| 0x08108109 | 1         | 3.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 9         | 30%     |
| Haswell     | 5         | 16.67%  |
| CometLake   | 5         | 16.67%  |
| Skylake     | 3         | 10%     |
| Unknown     | 2         | 6.67%   |
| Zen+        | 1         | 3.33%   |
| Westmere    | 1         | 3.33%   |
| SandyBridge | 1         | 3.33%   |
| K10         | 1         | 3.33%   |
| IvyBridge   | 1         | 3.33%   |
| Goldmont    | 1         | 3.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 26        | 76.47%  |
| Nvidia | 4         | 11.76%  |
| AMD    | 4         | 11.76%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                 | 6         | 17.14%  |
| Intel Comet Lake UHD Graphics                                                         | 5         | 14.29%  |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 3         | 8.57%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 2         | 5.71%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 2         | 5.71%   |
| Nvidia GT216M [GeForce GT 330M]                                                       | 1         | 2.86%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 1         | 2.86%   |
| Nvidia GK208M [GeForce GT 730M]                                                       | 1         | 2.86%   |
| Nvidia GK104M [GeForce GTX 870M]                                                      | 1         | 2.86%   |
| Intel UHD Graphics 620                                                                | 1         | 2.86%   |
| Intel Iris Plus Graphics 650                                                          | 1         | 2.86%   |
| Intel HD Graphics 630                                                                 | 1         | 2.86%   |
| Intel HD Graphics 515                                                                 | 1         | 2.86%   |
| Intel Core Processor Integrated Graphics Controller                                   | 1         | 2.86%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller    | 1         | 2.86%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 1         | 2.86%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 1         | 2.86%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 2.86%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                             | 1         | 2.86%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                             | 1         | 2.86%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 1         | 2.86%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                   | 1         | 2.86%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 20        | 66.67%  |
| Intel + Nvidia | 4         | 13.33%  |
| Other          | 2         | 6.67%   |
| Intel + AMD    | 2         | 6.67%   |
| 2 x AMD        | 1         | 3.33%   |
| 1 x AMD        | 1         | 3.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 27        | 90%     |
| Unknown | 3         | 10%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 29        | 96.67%  |
| 3.01-4.0   | 1         | 3.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 6         | 16.22%  |
| Samsung Electronics     | 5         | 13.51%  |
| Chimei Innolux          | 5         | 13.51%  |
| BOE                     | 5         | 13.51%  |
| Apple                   | 3         | 8.11%   |
| AU Optronics            | 2         | 5.41%   |
| Unknown                 | 1         | 2.7%    |
| Sharp                   | 1         | 2.7%    |
| PANDA                   | 1         | 2.7%    |
| Lenovo                  | 1         | 2.7%    |
| Iiyama                  | 1         | 2.7%    |
| Grundig                 | 1         | 2.7%    |
| Goldstar                | 1         | 2.7%    |
| Chi Mei Optoelectronics | 1         | 2.7%    |
| BenQ                    | 1         | 2.7%    |
| ASUSTek Computer        | 1         | 2.7%    |
| Acer                    | 1         | 2.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC434B 3840x2160 344x194mm 15.5-inch     | 3         | 8.11%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 3         | 8.11%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 1         | 2.7%    |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                   | 1         | 2.7%    |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch      | 1         | 2.7%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch         | 1         | 2.7%    |
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch                   | 1         | 2.7%    |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch              | 1         | 2.7%    |
| LG Display LCD Monitor LGD053B 1920x1080 294x165mm 13.3-inch              | 1         | 2.7%    |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch              | 1         | 2.7%    |
| LG Display LCD Monitor LGD03F0 1366x768 310x174mm 14.0-inch               | 1         | 2.7%    |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch               | 1         | 2.7%    |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch               | 1         | 2.7%    |
| Lenovo LEN Y44w-10 LEN65EA 3840x1200 1052x329mm 43.4-inch                 | 1         | 2.7%    |
| Iiyama PL2792H IVM664F 1920x1080 600x340mm 27.2-inch                      | 1         | 2.7%    |
| Grundig TV GRU4448 1920x1080 1210x680mm 54.6-inch                         | 1         | 2.7%    |
| Goldstar IPS231 GSM5817 1920x1080 510x290mm 23.1-inch                     | 1         | 2.7%    |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch          | 1         | 2.7%    |
| Chimei Innolux LCD Monitor CMN1415 1920x1080 309x173mm 13.9-inch          | 1         | 2.7%    |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 2.7%    |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                     | 1         | 2.7%    |
| BOE LCD Monitor BOE079A 1920x1080 309x173mm 13.9-inch                     | 1         | 2.7%    |
| BOE LCD Monitor BOE06C2 1366x768 344x194mm 15.5-inch                      | 1         | 2.7%    |
| BOE LCD Monitor BOE06BE 1920x1080 294x165mm 13.3-inch                     | 1         | 2.7%    |
| BOE LCD Monitor BOE0641 1920x1080 344x193mm 15.5-inch                     | 1         | 2.7%    |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                         | 1         | 2.7%    |
| AU Optronics LCD Monitor AUO713C 1366x768 309x173mm 13.9-inch             | 1         | 2.7%    |
| AU Optronics LCD Monitor AUO10ED 1920x1080 344x193mm 15.5-inch            | 1         | 2.7%    |
| ASUSTek Computer VP249 AUS24AF 1920x1080 527x296mm 23.8-inch              | 1         | 2.7%    |
| Apple Color LCD APPA034 2880x1800 286x179mm 13.3-inch                     | 1         | 2.7%    |
| Apple Color LCD APPA027 2304x1440 259x162mm 12.0-inch                     | 1         | 2.7%    |
| Apple Color LCD APP9CCF 1920x1200 367x230mm 17.1-inch                     | 1         | 2.7%    |
| Acer H236HL ACR0318 1920x1080 509x286mm 23.0-inch                         | 1         | 2.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 16        | 48.48%  |
| 3840x2160 (4K)    | 6         | 18.18%  |
| 1366x768 (WXGA)   | 6         | 18.18%  |
| 3840x1200         | 1         | 3.03%   |
| 2880x1800         | 1         | 3.03%   |
| 2304x1440         | 1         | 3.03%   |
| 2288x1287         | 1         | 3.03%   |
| 1920x1200 (WUXGA) | 1         | 3.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 12        | 32.43%  |
| 13     | 11        | 29.73%  |
| 27     | 2         | 5.41%   |
| 24     | 2         | 5.41%   |
| 23     | 2         | 5.41%   |
| 17     | 2         | 5.41%   |
| 14     | 2         | 5.41%   |
| 142    | 1         | 2.7%    |
| 54     | 1         | 2.7%    |
| 43     | 1         | 2.7%    |
| 12     | 1         | 2.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 18        | 50%     |
| 501-600        | 6         | 16.67%  |
| 201-300        | 6         | 16.67%  |
| 351-400        | 3         | 8.33%   |
| 1001-1500      | 2         | 5.56%   |
| More than 2000 | 1         | 2.78%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 24        | 82.76%  |
| 16/10 | 3         | 10.34%  |
| 3.20  | 1         | 3.45%   |
| 1.00  | 1         | 3.45%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 12        | 32.43%  |
| 81-90          | 8         | 21.62%  |
| 71-80          | 5         | 13.51%  |
| 201-250        | 4         | 10.81%  |
| More than 1000 | 2         | 5.41%   |
| 301-350        | 2         | 5.41%   |
| 61-70          | 1         | 2.7%    |
| 131-140        | 1         | 2.7%    |
| 121-130        | 1         | 2.7%    |
| 501-1000       | 1         | 2.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 12        | 32.43%  |
| 51-100        | 9         | 24.32%  |
| More than 240 | 6         | 16.22%  |
| 101-120       | 5         | 13.51%  |
| 161-240       | 4         | 10.81%  |
| 1-50          | 1         | 2.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 21        | 70%     |
| 2     | 7         | 23.33%  |
| 3     | 1         | 3.33%   |
| 0     | 1         | 3.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 17        | 36.17%  |
| Qualcomm Atheros                | 13        | 27.66%  |
| Intel                           | 7         | 14.89%  |
| Broadcom                        | 4         | 8.51%   |
| ASIX Electronics                | 2         | 4.26%   |
| Ralink                          | 1         | 2.13%   |
| Qualcomm Atheros Communications | 1         | 2.13%   |
| MediaTek                        | 1         | 2.13%   |
| Broadcom Limited                | 1         | 2.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 11        | 20.37%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9         | 16.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 9.26%   |
| Intel Wireless 7265                                               | 3         | 5.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 3.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 3.7%    |
| Intel Wireless 7260                                               | 2         | 3.7%    |
| Intel Ethernet Connection I217-LM                                 | 2         | 3.7%    |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 3.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 1.85%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1         | 1.85%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 1.85%   |
| Realtek 802.11ac NIC                                              | 1         | 1.85%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 1         | 1.85%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1         | 1.85%   |
| MediaTek WiFi                                                     | 1         | 1.85%   |
| Intel Wireless 8265 / 8275                                        | 1         | 1.85%   |
| Intel Ethernet Connection I218-V                                  | 1         | 1.85%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.85%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 1.85%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 1         | 1.85%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1         | 1.85%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                | 1         | 1.85%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 1         | 1.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 1         | 1.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 13        | 41.94%  |
| Intel                           | 6         | 19.35%  |
| Realtek Semiconductor           | 4         | 12.9%   |
| Broadcom                        | 4         | 12.9%   |
| Ralink                          | 1         | 3.23%   |
| Qualcomm Atheros Communications | 1         | 3.23%   |
| MediaTek                        | 1         | 3.23%   |
| Broadcom Limited                | 1         | 3.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 11        | 35.48%  |
| Intel Wireless 7265                                        | 3         | 9.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 2         | 6.45%   |
| Intel Wireless 7260                                        | 2         | 6.45%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1         | 3.23%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter    | 1         | 3.23%   |
| Realtek RTL8191SEvB Wireless LAN Controller                | 1         | 3.23%   |
| Realtek 802.11ac NIC                                       | 1         | 3.23%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter     | 1         | 3.23%   |
| Qualcomm Atheros AR9271 802.11n                            | 1         | 3.23%   |
| MediaTek WiFi                                              | 1         | 3.23%   |
| Intel Wireless 8265 / 8275                                 | 1         | 3.23%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter | 1         | 3.23%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                | 1         | 3.23%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter         | 1         | 3.23%   |
| Broadcom BCM43224 802.11a/b/g/n                            | 1         | 3.23%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter        | 1         | 3.23%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 15        | 68.18%  |
| Intel                 | 4         | 18.18%  |
| ASIX Electronics      | 2         | 9.09%   |
| Broadcom              | 1         | 4.55%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9         | 39.13%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 21.74%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 8.7%    |
| Intel Ethernet Connection I217-LM                                 | 2         | 8.7%    |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 8.7%    |
| Intel Ethernet Connection I218-V                                  | 1         | 4.35%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 4.35%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 4.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 27        | 56.25%  |
| Ethernet | 21        | 43.75%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 14        | 51.85%  |
| WiFi     | 13        | 48.15%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 19        | 63.33%  |
| 1     | 8         | 26.67%  |
| 0     | 3         | 10%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 24        | 80%     |
| Yes  | 6         | 20%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 5         | 20.83%  |
| Foxconn / Hon Hai               | 5         | 20.83%  |
| Qualcomm Atheros Communications | 4         | 16.67%  |
| Lite-On Technology              | 4         | 16.67%  |
| Apple                           | 2         | 8.33%   |
| Realtek Semiconductor           | 1         | 4.17%   |
| Cambridge Silicon Radio         | 1         | 4.17%   |
| Broadcom                        | 1         | 4.17%   |
| ASUSTek Computer                | 1         | 4.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 5         | 20.83%  |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 20.83%  |
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 16.67%  |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 8.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 8.33%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 4.17%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 4.17%   |
| Broadcom HP Portable Valentine                      | 1         | 4.17%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 4.17%   |
| Apple Bluetooth USB Host Controller                 | 1         | 4.17%   |
| Apple Bluetooth Host Controller                     | 1         | 4.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Intel    | 26        | 76.47%  |
| Nvidia   | 2         | 5.88%   |
| AMD      | 2         | 5.88%   |
| XMOS     | 1         | 2.94%   |
| Shure    | 1         | 2.94%   |
| M-Audio  | 1         | 2.94%   |
| Logitech | 1         | 2.94%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 11        | 27.5%   |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 12.5%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 7.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 7.5%    |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 5%      |
| Intel 8 Series HD Audio Controller                                         | 2         | 5%      |
| XMOS xDuoo USB Audio 2.0                                                   | 1         | 2.5%    |
| Shure MV5                                                                  | 1         | 2.5%    |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 2.5%    |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 2.5%    |
| M-Audio M-Audio Fast Track MKII                                            | 1         | 2.5%    |
| Logitech Headset H340                                                      | 1         | 2.5%    |
| Intel CM238 HD Audio Controller                                            | 1         | 2.5%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 2.5%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1         | 2.5%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 2.5%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 2.5%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 2.5%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 2.5%    |
| AMD Family 17h/19h HD Audio Controller                                     | 1         | 2.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Crucial             | 4         | 33.33%  |
| SK hynix            | 3         | 25%     |
| Samsung Electronics | 3         | 25%     |
| Unknown             | 1         | 8.33%   |
| Toshiba             | 1         | 8.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s     | 2         | 14.29%  |
| Crucial RAM CT16G4SFD824A.M16FRS 16GB SODIMM DDR4 2400MT/s | 2         | 14.29%  |
| Unknown RAM Module 16384MB 2133MT/s                        | 1         | 7.14%   |
| Toshiba RAM 8HTF12864HDY-800G1 1024MB SODIMM 1066MT/s      | 1         | 7.14%   |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 1066MT/s       | 1         | 7.14%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s     | 1         | 7.14%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s     | 1         | 7.14%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s  | 1         | 7.14%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s  | 1         | 7.14%   |
| Samsung RAM Module 4GB SODIMM LPDDR3 1867MT/s              | 1         | 7.14%   |
| Crucial RAM CT4G4SFS8213.C8FBD1 4GB SODIMM DDR4 2133MT/s   | 1         | 7.14%   |
| Crucial RAM CT16G4S24AM.M16FE 16GB SODIMM DDR4 2400MT/s    | 1         | 7.14%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 7         | 63.64%  |
| LPDDR3  | 1         | 9.09%   |
| DDR3    | 1         | 9.09%   |
| DDR2    | 1         | 9.09%   |
| Unknown | 1         | 9.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SODIMM  | 10        | 90.91%  |
| Unknown | 1         | 9.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 16384 | 4         | 30.77%  |
| 4096  | 4         | 30.77%  |
| 8192  | 3         | 23.08%  |
| 32768 | 2         | 15.38%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 4         | 33.33%  |
| 2400  | 3         | 25%     |
| 2133  | 2         | 16.67%  |
| 1867  | 1         | 8.33%   |
| 1600  | 1         | 8.33%   |
| 1066  | 1         | 8.33%   |

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
| Realtek Semiconductor                  | 4         | 16.67%  |
| Alcor Micro                            | 4         | 16.67%  |
| Acer                                   | 4         | 16.67%  |
| Sunplus Innovation Technology          | 3         | 12.5%   |
| Apple                                  | 3         | 12.5%   |
| Chicony Electronics                    | 2         | 8.33%   |
| Microdia                               | 1         | 4.17%   |
| Lite-On Technology                     | 1         | 4.17%   |
| Google                                 | 1         | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 4.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Alcor Micro HD WebCam                                                      | 3         | 12%     |
| Apple iPhone5/5C/5S/6                                                      | 2         | 8%      |
| Acer SunplusIT INC. Integrated Camera                                      | 2         | 8%      |
| Sunplus Integrated_Webcam_HD                                               | 1         | 4%      |
| Sunplus Integrated Camera                                                  | 1         | 4%      |
| Sunplus HD WebCam                                                          | 1         | 4%      |
| Realtek USB2.0 camera                                                      | 1         | 4%      |
| Realtek Integrated_Webcam_HD                                               | 1         | 4%      |
| Realtek Integrated Webcam                                                  | 1         | 4%      |
| Realtek HP Truevision HD                                                   | 1         | 4%      |
| Microdia HP Integrated Webcam                                              | 1         | 4%      |
| Lite-On Integrated Camera                                                  | 1         | 4%      |
| Chicony USB2.0 UVC WebCam                                                  | 1         | 4%      |
| Chicony HD User Facing                                                     | 1         | 4%      |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 1         | 4%      |
| Apple iBridge                                                              | 1         | 4%      |
| Apple Built-in iSight                                                      | 1         | 4%      |
| Alcor Micro HP Webcam-101                                                  | 1         | 4%      |
| Acer SunplusIT Integrated Camera                                           | 1         | 4%      |
| Acer BisonCam, NB Pro                                                      | 1         | 4%      |
| Unknown                                                                    | 1         | 4%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 3         | 50%     |
| LighTuning Technology | 2         | 33.33%  |
| Synaptics             | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor     | 3         | 50%     |
| Synaptics Metallica MOH Touch Fingerprint Reader | 1         | 16.67%  |
| LighTuning ES603 Swipe Fingerprint Sensor        | 1         | 16.67%  |
| LighTuning EgisTec Touch Fingerprint Sensor      | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Purism, SPC | 2         | 50%     |
| Clay Logic  | 1         | 25%     |
| Alcor Micro | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Purism, SPC Librem Key              | 2         | 50%     |
| Clay Logic Nitrokey Pro             | 1         | 25%     |
| Alcor Micro AU9540 Smartcard Reader | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 13        | 41.94%  |
| 0     | 13        | 41.94%  |
| 2     | 3         | 9.68%   |
| 4     | 1         | 3.23%   |
| 3     | 1         | 3.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 6         | 23.08%  |
| Fingerprint reader    | 6         | 23.08%  |
| Bluetooth             | 6         | 23.08%  |
| Graphics card         | 4         | 15.38%  |
| Multimedia controller | 2         | 7.69%   |
| Chipcard              | 1         | 3.85%   |
| Camera                | 1         | 3.85%   |

