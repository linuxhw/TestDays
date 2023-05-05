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

Total: 50

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Purism        | Librem 14                   | [8462dbaccb](https://linux-hardware.org/?probe=8462dbaccb) | Apr 25, 2023 |
| Purism        | Librem 5r4                  | [6c71601fdd](https://linux-hardware.org/?probe=6c71601fdd) | Mar 11, 2023 |
| Google        | Droid                       | [e576f650b7](https://linux-hardware.org/?probe=e576f650b7) | Feb 22, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [519a211655](https://linux-hardware.org/?probe=519a211655) | Jan 30, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [edd571ba94](https://linux-hardware.org/?probe=edd571ba94) | Jan 28, 2023 |
| Dell          | Latitude D430               | [e171875163](https://linux-hardware.org/?probe=e171875163) | Jan 27, 2023 |
| Dell          | Latitude D430               | [6245710c10](https://linux-hardware.org/?probe=6245710c10) | Jan 26, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | [c41d8da6ac](https://linux-hardware.org/?probe=c41d8da6ac) | Nov 26, 2022 |
| Apple         | MacBookAir7,2               | [6901439af7](https://linux-hardware.org/?probe=6901439af7) | Nov 17, 2022 |
| Lenovo        | IdeaPad U430 Touch 20270    | [707d2f74c7](https://linux-hardware.org/?probe=707d2f74c7) | Oct 24, 2022 |
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
| PureOS 10.0 | 14        | 35.9%   |
| PureOS 10   | 12        | 30.77%  |
| PureOS 9.0  | 9         | 23.08%  |
| PureOS 9    | 2         | 5.13%   |
| PureOS 8    | 2         | 5.13%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| PureOS | 38        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Notebooks | Percent |
|----------------------------------|-----------|---------|
| 4.19.0-5-amd64                   | 9         | 22.5%   |
| 5.10.0-13-amd64                  | 5         | 12.5%   |
| 5.10.0-14-amd64                  | 4         | 10%     |
| 5.10.0-8-amd64                   | 3         | 7.5%    |
| 5.10.0-21-amd64                  | 3         | 7.5%    |
| 5.10.0-7-amd64                   | 2         | 5%      |
| 5.10.0-11-amd64                  | 2         | 5%      |
| 6.1.0-1-librem5                  | 1         | 2.5%    |
| 5.7.0-1-librem5                  | 1         | 2.5%    |
| 5.7.0-0.38-1-pinebookpro-hwaccel | 1         | 2.5%    |
| 5.15.0-2-amd64                   | 1         | 2.5%    |
| 5.10.0-9-amd64                   | 1         | 2.5%    |
| 5.10.0-6-amd64                   | 1         | 2.5%    |
| 5.10.0-19-amd64                  | 1         | 2.5%    |
| 5.10.0-18-amd64                  | 1         | 2.5%    |
| 5.10.0-17-amd64                  | 1         | 2.5%    |
| 5.10.0-12-amd64                  | 1         | 2.5%    |
| 4.19.0-14-amd64                  | 1         | 2.5%    |
| 4.16.0-1-amd64                   | 1         | 2.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 24        | 61.54%  |
| 4.19.0  | 10        | 25.64%  |
| 5.7.0   | 2         | 5.13%   |
| 6.1.0   | 1         | 2.56%   |
| 5.15.0  | 1         | 2.56%   |
| 4.16.0  | 1         | 2.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 24        | 61.54%  |
| 4.19    | 10        | 25.64%  |
| 5.7     | 2         | 5.13%   |
| 6.1     | 1         | 2.56%   |
| 5.15    | 1         | 2.56%   |
| 4.16    | 1         | 2.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 35        | 92.11%  |
| aarch64 | 3         | 7.89%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 32        | 82.05%  |
| Unknown         | 4         | 10.26%  |
| MATE            | 1         | 2.56%   |
| KDE5            | 1         | 2.56%   |
| GNOME Flashback | 1         | 2.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 29        | 72.5%   |
| X11     | 5         | 12.5%   |
| Unknown | 4         | 10%     |
| Tty     | 2         | 5%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 22        | 57.89%  |
| GDM     | 12        | 31.58%  |
| GDM3    | 4         | 10.53%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 18        | 45%     |
| en_GB   | 4         | 10%     |
| Unknown | 4         | 10%     |
| pl_PL   | 2         | 5%      |
| de_DE   | 2         | 5%      |
| C       | 2         | 5%      |
| zh_CN   | 1         | 2.5%    |
| ru_RU   | 1         | 2.5%    |
| pt_PT   | 1         | 2.5%    |
| it_IT   | 1         | 2.5%    |
| fr_FR   | 1         | 2.5%    |
| es_CR   | 1         | 2.5%    |
| en_IL   | 1         | 2.5%    |
| en_AU   | 1         | 2.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 33        | 86.84%  |
| EFI  | 5         | 13.16%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 33        | 86.84%  |
| Unknown | 2         | 5.26%   |
| Overlay | 1         | 2.63%   |
| Ext2    | 1         | 2.63%   |
| Btrfs   | 1         | 2.63%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 23        | 60.53%  |
| MBR     | 9         | 23.68%  |
| GPT     | 6         | 15.79%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 32        | 84.21%  |
| Yes       | 6         | 15.79%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 35        | 92.11%  |
| Yes       | 3         | 7.89%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Purism              | 12        | 31.58%  |
| Lenovo              | 6         | 15.79%  |
| Dell                | 4         | 10.53%  |
| Apple               | 4         | 10.53%  |
| Hewlett-Packard     | 3         | 7.89%   |
| Acer                | 2         | 5.26%   |
| Toshiba             | 1         | 2.63%   |
| Samsung Electronics | 1         | 2.63%   |
| Pine Microsystems   | 1         | 2.63%   |
| Notebook            | 1         | 2.63%   |
| HUAWEI              | 1         | 2.63%   |
| Google              | 1         | 2.63%   |
| Unknown             | 1         | 2.63%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Purism Librem 14                      | 6         | 15.79%  |
| Purism Librem 15 v4                   | 2         | 5.26%   |
| HP Pavilion g6                        | 2         | 5.26%   |
| Toshiba Satellite L500D               | 1         | 2.63%   |
| Samsung 530U3C/530U4C/532U3C          | 1         | 2.63%   |
| Purism Librem 5r4                     | 1         | 2.63%   |
| Purism Librem 15 v3                   | 1         | 2.63%   |
| Purism Librem 13 v4                   | 1         | 2.63%   |
| Purism Librem 13 v2                   | 1         | 2.63%   |
| Pine Microsystems Pine64 Pinebook Pro | 1         | 2.63%   |
| Notebook P17SM                        | 1         | 2.63%   |
| Lenovo ThinkPad T540p 20BFS23T00      | 1         | 2.63%   |
| Lenovo ThinkPad T440p                 | 1         | 2.63%   |
| Lenovo ThinkPad T440 20B60044RT       | 1         | 2.63%   |
| Lenovo ThinkPad E480 20KN003SUS       | 1         | 2.63%   |
| Lenovo ThinkPad 13 2nd Gen 20J2S00G00 | 1         | 2.63%   |
| Lenovo IdeaPad U430 Touch 20270       | 1         | 2.63%   |
| HUAWEI NBLB-WAX9N                     | 1         | 2.63%   |
| HP Pavilion Notebook                  | 1         | 2.63%   |
| Google Droid                          | 1         | 2.63%   |
| Dell XPS 13 9370                      | 1         | 2.63%   |
| Dell Latitude D430                    | 1         | 2.63%   |
| Dell Inspiron 5547                    | 1         | 2.63%   |
| Dell Inspiron 15-3567                 | 1         | 2.63%   |
| Apple MacBookPro6,1                   | 1         | 2.63%   |
| Apple MacBookPro14,2                  | 1         | 2.63%   |
| Apple MacBookAir7,2                   | 1         | 2.63%   |
| Apple MacBook9,1                      | 1         | 2.63%   |
| Acer Swift SF113-31                   | 1         | 2.63%   |
| Acer Nitro AN515-43                   | 1         | 2.63%   |
| Unknown                               | 1         | 2.63%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Purism Librem            | 12        | 31.58%  |
| Lenovo ThinkPad          | 5         | 13.16%  |
| HP Pavilion              | 3         | 7.89%   |
| Dell Inspiron            | 2         | 5.26%   |
| Toshiba Satellite        | 1         | 2.63%   |
| Samsung 530U3C           | 1         | 2.63%   |
| Pine Microsystems Pine64 | 1         | 2.63%   |
| Notebook P17SM           | 1         | 2.63%   |
| Lenovo IdeaPad           | 1         | 2.63%   |
| HUAWEI NBLB-WAX9N        | 1         | 2.63%   |
| Google Droid             | 1         | 2.63%   |
| Dell XPS                 | 1         | 2.63%   |
| Dell Latitude            | 1         | 2.63%   |
| Apple MacBookPro6        | 1         | 2.63%   |
| Apple MacBookPro14       | 1         | 2.63%   |
| Apple MacBookAir7        | 1         | 2.63%   |
| Apple MacBook9           | 1         | 2.63%   |
| Acer Swift               | 1         | 2.63%   |
| Acer Nitro               | 1         | 2.63%   |
| Unknown                  | 1         | 2.63%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 6         | 15.79%  |
| 2017    | 5         | 13.16%  |
| 2019    | 4         | 10.53%  |
| 2013    | 4         | 10.53%  |
| Unknown | 4         | 10.53%  |
| 2020    | 3         | 7.89%   |
| 2018    | 2         | 5.26%   |
| 2015    | 2         | 5.26%   |
| 2011    | 2         | 5.26%   |
| 2023    | 1         | 2.63%   |
| 2016    | 1         | 2.63%   |
| 2014    | 1         | 2.63%   |
| 2012    | 1         | 2.63%   |
| 2009    | 1         | 2.63%   |
| 2007    | 1         | 2.63%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 38        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 38        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 25        | 65.79%  |
| Yes  | 13        | 34.21%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 16.01-24.0 | 10        | 26.32%  |
| 4.01-8.0   | 9         | 23.68%  |
| 32.01-64.0 | 6         | 15.79%  |
| 3.01-4.0   | 6         | 15.79%  |
| 8.01-16.0  | 4         | 10.53%  |
| 24.01-32.0 | 1         | 2.63%   |
| 2.01-3.0   | 1         | 2.63%   |
| 1.01-2.0   | 1         | 2.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 13        | 32.5%   |
| 3.01-4.0  | 10        | 25%     |
| 1.01-2.0  | 8         | 20%     |
| 4.01-8.0  | 7         | 17.5%   |
| 8.01-16.0 | 2         | 5%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 25        | 65.79%  |
| 2      | 11        | 28.95%  |
| 0      | 2         | 5.26%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 31        | 81.58%  |
| Yes       | 7         | 18.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 76.32%  |
| No        | 9         | 23.68%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 89.47%  |
| No        | 4         | 10.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 76.32%  |
| No        | 9         | 23.68%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Notebooks | Percent |
|------------------------|-----------|---------|
| USA                    | 9         | 22.5%   |
| UK                     | 5         | 12.5%   |
| Germany                | 3         | 7.5%    |
| Canada                 | 3         | 7.5%    |
| Brazil                 | 3         | 7.5%    |
| Italy                  | 2         | 5%      |
| France                 | 2         | 5%      |
| Australia              | 2         | 5%      |
| Turkey                 | 1         | 2.5%    |
| South Africa           | 1         | 2.5%    |
| Russia                 | 1         | 2.5%    |
| Portugal               | 1         | 2.5%    |
| Poland                 | 1         | 2.5%    |
| Paraguay               | 1         | 2.5%    |
| Israel                 | 1         | 2.5%    |
| Iran                   | 1         | 2.5%    |
| Costa Rica             | 1         | 2.5%    |
| China                  | 1         | 2.5%    |
| Bosnia and Herzegovina | 1         | 2.5%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| London             | 3         | 7.5%    |
| Windsor            | 1         | 2.5%    |
| Warsaw             | 1         | 2.5%    |
| Vancouver          | 1         | 2.5%    |
| Thorpe Hamlet      | 1         | 2.5%    |
| Tel Aviv           | 1         | 2.5%    |
| Stuttgart          | 1         | 2.5%    |
| Spencer            | 1         | 2.5%    |
| Seattle            | 1         | 2.5%    |
| Sao Paulo          | 1         | 2.5%    |
| San Jose           | 1         | 2.5%    |
| Paris              | 1         | 2.5%    |
| New York           | 1         | 2.5%    |
| Montreal           | 1         | 2.5%    |
| Milwaukee          | 1         | 2.5%    |
| Milpitas           | 1         | 2.5%    |
| Melbourne          | 1         | 2.5%    |
| Mankato            | 1         | 2.5%    |
| Krasnogorsk        | 1         | 2.5%    |
| Istanbul           | 1         | 2.5%    |
| Hernandarias       | 1         | 2.5%    |
| Harpswell          | 1         | 2.5%    |
| Guimaraes          | 1         | 2.5%    |
| Grasse             | 1         | 2.5%    |
| Genoa              | 1         | 2.5%    |
| Eberswalde         | 1         | 2.5%    |
| Cape Town          | 1         | 2.5%    |
| Camden             | 1         | 2.5%    |
| Blumenau           | 1         | 2.5%    |
| Big Sky            | 1         | 2.5%    |
| Berlin             | 1         | 2.5%    |
| Banja Luka         | 1         | 2.5%    |
| Bandar-e Asalūyeh | 1         | 2.5%    |
| Araçatuba         | 1         | 2.5%    |
| Antioch            | 1         | 2.5%    |
| Ankang             | 1         | 2.5%    |
| Almese             | 1         | 2.5%    |
| Adelaide           | 1         | 2.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 18     | 31.11%  |
| Unknown             | 4         | 4      | 8.89%   |
| Seagate             | 3         | 3      | 6.67%   |
| HGST                | 3         | 3      | 6.67%   |
| Apple               | 3         | 5      | 6.67%   |
| WDC                 | 2         | 2      | 4.44%   |
| SanDisk             | 2         | 2      | 4.44%   |
| Crucial             | 2         | 4      | 4.44%   |
| A-DATA Technology   | 2         | 2      | 4.44%   |
| Transcend           | 1         | 1      | 2.22%   |
| Toshiba             | 1         | 1      | 2.22%   |
| Plextor             | 1         | 1      | 2.22%   |
| Phison              | 1         | 1      | 2.22%   |
| Mushkin             | 1         | 1      | 2.22%   |
| JMicron Technology  | 1         | 1      | 2.22%   |
| Intel               | 1         | 1      | 2.22%   |
| Hitachi             | 1         | 1      | 2.22%   |
| BIWIN               | 1         | 1      | 2.22%   |
| ADATA Technology    | 1         | 1      | 2.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown MMC Card  64GB                            | 2         | 4.26%   |
| Seagate ST1000LM048-2E7172 1TB                    | 2         | 4.26%   |
| Samsung SSD 970 PRO 1TB                           | 2         | 4.26%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 1         | 2.13%   |
| WDC WDS100T2B0C-00PXH0 1TB                        | 1         | 2.13%   |
| Unknown MMC Card  32GB                            | 1         | 2.13%   |
| Unknown DA4128  128GB                             | 1         | 2.13%   |
| Transcend TS240GMTS420S 240GB SSD                 | 1         | 2.13%   |
| Toshiba NVMe SSD Drive 512GB                      | 1         | 2.13%   |
| Seagate NVMe SSD Drive 2TB                        | 1         | 2.13%   |
| SanDisk SSD i100 24GB                             | 1         | 2.13%   |
| SanDisk SDSSDH3500G 500GB                         | 1         | 2.13%   |
| Samsung SSD 970 EVO Plus 500GB                    | 1         | 2.13%   |
| Samsung SSD 970 EVO Plus 2TB                      | 1         | 2.13%   |
| Samsung SSD 970 EVO 250GB                         | 1         | 2.13%   |
| Samsung SSD 960 EVO 500GB                         | 1         | 2.13%   |
| Samsung SSD 960 EVO 250GB                         | 1         | 2.13%   |
| Samsung SSD 860 EVO 500GB                         | 1         | 2.13%   |
| Samsung SSD 860 EVO 250GB                         | 1         | 2.13%   |
| Samsung SSD 860 EVO 1TB                           | 1         | 2.13%   |
| Samsung SSD 850 EVO 500GB                         | 1         | 2.13%   |
| Samsung SSD 850 EVO 250GB                         | 1         | 2.13%   |
| Samsung NVMe SSD Drive 1TB                        | 1         | 2.13%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 1         | 2.13%   |
| Samsung HS08XJC 80GB                              | 1         | 2.13%   |
| Plextor PX-1TM6Pro 1024GB SSD                     | 1         | 2.13%   |
| Phison PM8512GPTCB4B8TF-E13T4 512GB               | 1         | 2.13%   |
| Mushkin MKNSSDRE250GB-LT                          | 1         | 2.13%   |
| JMicron Generic 1TB                               | 1         | 2.13%   |
| Intel SSDSC2BF180A4H 180GB                        | 1         | 2.13%   |
| Hitachi HTS545050A7E380 500GB                     | 1         | 2.13%   |
| HGST HTS721010A9E630 1TB                          | 1         | 2.13%   |
| HGST HTS545050B7E660 500GB                        | 1         | 2.13%   |
| HGST HTS541010A9E680 1TB                          | 1         | 2.13%   |
| Crucial CT250MX500SSD4 250GB                      | 1         | 2.13%   |
| Crucial CT2000MX500SSD1 2TB                       | 1         | 2.13%   |
| BIWIN SSD 120GB                                   | 1         | 2.13%   |
| Apple SSD SM0128G 121GB                           | 1         | 2.13%   |
| Apple SSD AP0512J 500GB                           | 1         | 2.13%   |
| Apple NVMe SSD Drive 8KB                          | 1         | 2.13%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 3         | 3      | 37.5%   |
| Seagate             | 2         | 2      | 25%     |
| Samsung Electronics | 1         | 1      | 12.5%   |
| JMicron Technology  | 1         | 1      | 12.5%   |
| Hitachi             | 1         | 1      | 12.5%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 8      | 31.58%  |
| SanDisk             | 2         | 2      | 10.53%  |
| Crucial             | 2         | 4      | 10.53%  |
| A-DATA Technology   | 2         | 2      | 10.53%  |
| WDC                 | 1         | 1      | 5.26%   |
| Transcend           | 1         | 1      | 5.26%   |
| Plextor             | 1         | 1      | 5.26%   |
| Mushkin             | 1         | 1      | 5.26%   |
| Intel               | 1         | 1      | 5.26%   |
| BIWIN               | 1         | 1      | 5.26%   |
| Apple               | 1         | 1      | 5.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 16        | 23     | 37.21%  |
| NVMe | 15        | 18     | 34.88%  |
| HDD  | 8         | 8      | 18.6%   |
| MMC  | 4         | 4      | 9.3%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 20        | 29     | 48.78%  |
| NVMe | 15        | 18     | 36.59%  |
| MMC  | 4         | 4      | 9.76%   |
| SAS  | 2         | 2      | 4.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 15        | 22     | 65.22%  |
| 0.51-1.0   | 6         | 6      | 26.09%  |
| 1.01-2.0   | 2         | 3      | 8.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 17        | 44.74%  |
| 101-250    | 5         | 13.16%  |
| 21-50      | 3         | 7.89%   |
| 51-100     | 3         | 7.89%   |
| Unknown    | 3         | 7.89%   |
| 251-500    | 2         | 5.26%   |
| 1001-2000  | 2         | 5.26%   |
| 501-1000   | 2         | 5.26%   |
| 2001-3000  | 1         | 2.63%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 26        | 68.42%  |
| 21-50    | 4         | 10.53%  |
| 501-1000 | 3         | 7.89%   |
| Unknown  | 3         | 7.89%   |
| 251-500  | 1         | 2.63%   |
| 51-100   | 1         | 2.63%   |

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
| Detected | 25        | 36     | 67.57%  |
| Works    | 11        | 16     | 29.73%  |
| Malfunc  | 1         | 1      | 2.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 20        | 52.63%  |
| Samsung Electronics          | 9         | 23.68%  |
| Apple                        | 2         | 5.26%   |
| AMD                          | 2         | 5.26%   |
| Toshiba America Info Systems | 1         | 2.63%   |
| Seagate Technology           | 1         | 2.63%   |
| SanDisk                      | 1         | 2.63%   |
| Phison Electronics           | 1         | 2.63%   |
| ADATA Technology             | 1         | 2.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 18.42%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 6         | 15.79%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 7.89%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 5.26%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 5.26%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 5.26%   |
| Apple S3X NVMe Controller                                                      | 2         | 5.26%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 2.63%   |
| Seagate FireCuda 510 SSD                                                       | 1         | 2.63%   |
| SanDisk Non-Volatile memory controller                                         | 1         | 2.63%   |
| Samsung Electronics SATA controller                                            | 1         | 2.63%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 2.63%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 2.63%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 2.63%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 2.63%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 2.63%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 2.63%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 2.63%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 2.63%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 1         | 2.63%   |
| ADATA Non-Volatile memory controller                                           | 1         | 2.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 22        | 57.89%  |
| NVMe | 15        | 39.47%  |
| IDE  | 1         | 2.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 33        | 86.84%  |
| ARM     | 2         | 5.26%   |
| AMD     | 2         | 5.26%   |
| Unknown | 1         | 2.63%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10710U CPU @ 1.10GHz            | 6         | 15.79%  |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 10.53%  |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 5.26%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 5.26%   |
| ARM Processor                                 | 2         | 5.26%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 2.63%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 2.63%   |
| Intel Core m5-6Y54 CPU @ 1.10GHz              | 1         | 2.63%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 2.63%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 2.63%   |
| Intel Core i7-7567U CPU @ 3.50GHz             | 1         | 2.63%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz            | 1         | 2.63%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 1         | 2.63%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 2.63%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 2.63%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 1         | 2.63%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 2.63%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 2.63%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 1         | 2.63%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 1         | 2.63%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 2.63%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 1         | 2.63%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 1         | 2.63%   |
| Intel Core 2 Duo CPU U7700 @ 1.33GHz          | 1         | 2.63%   |
| AMD Turion II Dual-Core Mobile M520           | 1         | 2.63%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 1         | 2.63%   |
|                                               | 1         | 2.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 19        | 50%     |
| Intel Core i5           | 6         | 15.79%  |
| Intel Core i3           | 4         | 10.53%  |
| Other                   | 3         | 7.89%   |
| Intel Pentium Silver    | 1         | 2.63%   |
| Intel Pentium           | 1         | 2.63%   |
| Intel Core m5           | 1         | 2.63%   |
| Intel Core 2 Duo        | 1         | 2.63%   |
| AMD Turion II Dual-Core | 1         | 2.63%   |
| AMD Ryzen 5             | 1         | 2.63%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 20        | 52.63%  |
| 4      | 12        | 31.58%  |
| 6      | 6         | 15.79%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 38        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 31        | 81.58%  |
| 1      | 7         | 18.42%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 36        | 92.31%  |
| Unknown        | 3         | 7.69%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 27        | 71.05%  |
| 0xa0660    | 3         | 7.89%   |
| 0x406e3    | 3         | 7.89%   |
| 0x40651    | 2         | 5.26%   |
| 0x806ec    | 1         | 2.63%   |
| 0x806e9    | 1         | 2.63%   |
| 0x08108109 | 1         | 2.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 10        | 26.32%  |
| Haswell       | 6         | 15.79%  |
| CometLake     | 6         | 15.79%  |
| Skylake       | 3         | 7.89%   |
| Unknown       | 3         | 7.89%   |
| IvyBridge     | 2         | 5.26%   |
| Zen+          | 1         | 2.63%   |
| Westmere      | 1         | 2.63%   |
| SandyBridge   | 1         | 2.63%   |
| K10           | 1         | 2.63%   |
| Goldmont plus | 1         | 2.63%   |
| Goldmont      | 1         | 2.63%   |
| Core          | 1         | 2.63%   |
| Broadwell     | 1         | 2.63%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 33        | 80.49%  |
| Nvidia | 4         | 9.76%   |
| AMD    | 4         | 9.76%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                 | 6         | 13.95%  |
| Intel Comet Lake UHD Graphics                                                         | 6         | 13.95%  |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 3         | 6.98%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 3         | 6.98%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 2         | 4.65%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 2         | 4.65%   |
| Nvidia GT216M [GeForce GT 330M]                                                       | 1         | 2.33%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 1         | 2.33%   |
| Nvidia GK208M [GeForce GT 730M]                                                       | 1         | 2.33%   |
| Nvidia GK104M [GeForce GTX 870M]                                                      | 1         | 2.33%   |
| Intel UHD Graphics 620                                                                | 1         | 2.33%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller         | 1         | 2.33%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller             | 1         | 2.33%   |
| Intel Iris Plus Graphics 650                                                          | 1         | 2.33%   |
| Intel HD Graphics 630                                                                 | 1         | 2.33%   |
| Intel HD Graphics 6000                                                                | 1         | 2.33%   |
| Intel HD Graphics 515                                                                 | 1         | 2.33%   |
| Intel GeminiLake [UHD Graphics 605]                                                   | 1         | 2.33%   |
| Intel Core Processor Integrated Graphics Controller                                   | 1         | 2.33%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 1         | 2.33%   |
| Intel Apollo Lake [HD Graphics 505]                                                   | 1         | 2.33%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 1         | 2.33%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 2.33%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                             | 1         | 2.33%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                             | 1         | 2.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 1         | 2.33%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                   | 1         | 2.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 26        | 68.42%  |
| Other          | 4         | 10.53%  |
| Intel + Nvidia | 4         | 10.53%  |
| Intel + AMD    | 2         | 5.26%   |
| 2 x AMD        | 1         | 2.63%   |
| 1 x AMD        | 1         | 2.63%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 34        | 89.47%  |
| Unknown | 4         | 10.53%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 37        | 97.37%  |
| 3.01-4.0   | 1         | 2.63%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 7         | 16.28%  |
| BOE                     | 7         | 16.28%  |
| LG Display              | 6         | 13.95%  |
| Samsung Electronics     | 5         | 11.63%  |
| Apple                   | 4         | 9.3%    |
| AU Optronics            | 2         | 4.65%   |
| Unknown                 | 1         | 2.33%   |
| Toshiba                 | 1         | 2.33%   |
| Sharp                   | 1         | 2.33%   |
| PANDA                   | 1         | 2.33%   |
| Lenovo                  | 1         | 2.33%   |
| Iiyama                  | 1         | 2.33%   |
| Grundig                 | 1         | 2.33%   |
| Goldstar                | 1         | 2.33%   |
| Chi Mei Optoelectronics | 1         | 2.33%   |
| BenQ                    | 1         | 2.33%   |
| ASUSTek Computer        | 1         | 2.33%   |
| Acer                    | 1         | 2.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC434B 3840x2160 344x194mm 15.5-inch     | 3         | 6.98%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 3         | 6.98%   |
| Chimei Innolux LCD Monitor CMN1415 1920x1080 309x173mm 13.9-inch          | 2         | 4.65%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 1         | 2.33%   |
| Toshiba LCD Monitor LCD3706 1280x800 261x163mm 12.1-inch                  | 1         | 2.33%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                   | 1         | 2.33%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch      | 1         | 2.33%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 1         | 2.33%   |
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch                   | 1         | 2.33%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch              | 1         | 2.33%   |
| LG Display LCD Monitor LGD053B 1920x1080 294x165mm 13.3-inch              | 1         | 2.33%   |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch              | 1         | 2.33%   |
| LG Display LCD Monitor LGD03F0 1366x768 310x174mm 14.0-inch               | 1         | 2.33%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch               | 1         | 2.33%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch               | 1         | 2.33%   |
| Lenovo LEN Y44w-10 LEN65EA 3840x1200 1052x329mm 43.4-inch                 | 1         | 2.33%   |
| Iiyama PL2792H IVM664F 1920x1080 598x336mm 27.0-inch                      | 1         | 2.33%   |
| Grundig WUXGA GRU4448 1920x540                                            | 1         | 2.33%   |
| Goldstar IPS231 GSM5817 1920x1080 510x290mm 23.1-inch                     | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch          | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch           | 1         | 2.33%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 2.33%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                     | 1         | 2.33%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                     | 1         | 2.33%   |
| BOE LCD Monitor BOE079A 1920x1080 309x173mm 13.9-inch                     | 1         | 2.33%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                      | 1         | 2.33%   |
| BOE LCD Monitor BOE06C2 1366x768 344x194mm 15.5-inch                      | 1         | 2.33%   |
| BOE LCD Monitor BOE06BE 1920x1080 294x165mm 13.3-inch                     | 1         | 2.33%   |
| BOE LCD Monitor BOE0641 1920x1080 344x193mm 15.5-inch                     | 1         | 2.33%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                         | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO713C 1366x768 309x173mm 13.9-inch             | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO10ED 1920x1080 344x193mm 15.5-inch            | 1         | 2.33%   |
| ASUSTek Computer VP249 AUS24AF 1920x1080 527x296mm 23.8-inch              | 1         | 2.33%   |
| Apple Color LCD APPA034 2880x1800 286x179mm 13.3-inch                     | 1         | 2.33%   |
| Apple Color LCD APPA027 2304x1440 259x162mm 12.0-inch                     | 1         | 2.33%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 1         | 2.33%   |
| Apple Color LCD APP9CCF 1920x1200 367x230mm 17.1-inch                     | 1         | 2.33%   |
| Acer H236HL ACR0318 1920x1080 509x286mm 23.0-inch                         | 1         | 2.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 18        | 46.15%  |
| 1366x768 (WXGA)   | 7         | 17.95%  |
| 3840x2160 (4K)    | 6         | 15.38%  |
| 3840x1200         | 1         | 2.56%   |
| 2880x1800         | 1         | 2.56%   |
| 2304x1440         | 1         | 2.56%   |
| 2288x1287         | 1         | 2.56%   |
| 1920x1200 (WUXGA) | 1         | 2.56%   |
| 1600x900 (HD+)    | 1         | 2.56%   |
| 1440x900 (WXGA+)  | 1         | 2.56%   |
| 1280x800 (WXGA)   | 1         | 2.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 15        | 34.88%  |
| 15     | 12        | 27.91%  |
| 14     | 3         | 6.98%   |
| 24     | 2         | 4.65%   |
| 23     | 2         | 4.65%   |
| 17     | 2         | 4.65%   |
| 12     | 2         | 4.65%   |
| 142    | 1         | 2.33%   |
| 54     | 1         | 2.33%   |
| 43     | 1         | 2.33%   |
| 40     | 1         | 2.33%   |
| 27     | 1         | 2.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 22        | 52.38%  |
| 201-300        | 8         | 19.05%  |
| 501-600        | 5         | 11.9%   |
| 351-400        | 3         | 7.14%   |
| 1001-1500      | 2         | 4.76%   |
| More than 2000 | 1         | 2.38%   |
| 801-900        | 1         | 2.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 28        | 80%     |
| 16/10 | 5         | 14.29%  |
| 3.20  | 1         | 2.86%   |
| 1.00  | 1         | 2.86%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 12        | 27.91%  |
| 101-110        | 12        | 27.91%  |
| 71-80          | 6         | 13.95%  |
| 201-250        | 4         | 9.3%    |
| More than 1000 | 2         | 4.65%   |
| 61-70          | 2         | 4.65%   |
| 501-1000       | 2         | 4.65%   |
| 301-350        | 1         | 2.33%   |
| 131-140        | 1         | 2.33%   |
| 121-130        | 1         | 2.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 17        | 39.53%  |
| 51-100        | 9         | 20.93%  |
| More than 240 | 6         | 13.95%  |
| 101-120       | 6         | 13.95%  |
| 161-240       | 4         | 9.3%    |
| 1-50          | 1         | 2.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 27        | 71.05%  |
| 2     | 7         | 18.42%  |
| 0     | 3         | 7.89%   |
| 3     | 1         | 2.63%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 22        | 35.48%  |
| Qualcomm Atheros                | 15        | 24.19%  |
| Intel                           | 11        | 17.74%  |
| Broadcom                        | 5         | 8.06%   |
| Broadcom Limited                | 3         | 4.84%   |
| ASIX Electronics                | 2         | 3.23%   |
| Ralink                          | 1         | 1.61%   |
| Qualcomm Atheros Communications | 1         | 1.61%   |
| OPPO Electronics                | 1         | 1.61%   |
| MediaTek                        | 1         | 1.61%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 12        | 17.39%  |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 12        | 17.39%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 5         | 7.25%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 3         | 4.35%   |
| Intel Wireless 7265                                                           | 3         | 4.35%   |
| Intel Wireless 7260                                                           | 3         | 4.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 2         | 2.9%    |
| Intel Ethernet Connection I217-LM                                             | 2         | 2.9%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                    | 2         | 2.9%    |
| ASIX AX88179 Gigabit Ethernet                                                 | 2         | 2.9%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1         | 1.45%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 1.45%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 1         | 1.45%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 1.45%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1         | 1.45%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                        | 1         | 1.45%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 1.45%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.45%   |
| OPPO KALAMA-MTP_CID:0437_SN:AEEEF597                                          | 1         | 1.45%   |
| MediaTek WiFi                                                                 | 1         | 1.45%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 1.45%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1         | 1.45%   |
| Intel Ethernet Connection I218-V                                              | 1         | 1.45%   |
| Intel Ethernet Connection (4) I219-V                                          | 1         | 1.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 1         | 1.45%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 1.45%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1         | 1.45%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                       | 1         | 1.45%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                        | 1         | 1.45%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 1         | 1.45%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                            | 1         | 1.45%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 1         | 1.45%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 1         | 1.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 15        | 37.5%   |
| Intel                           | 10        | 25%     |
| Realtek Semiconductor           | 5         | 12.5%   |
| Broadcom                        | 4         | 10%     |
| Broadcom Limited                | 3         | 7.5%    |
| Ralink                          | 1         | 2.5%    |
| Qualcomm Atheros Communications | 1         | 2.5%    |
| MediaTek                        | 1         | 2.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 12        | 30%     |
| Intel Wireless 7265                                                           | 3         | 7.5%    |
| Intel Wireless 7260                                                           | 3         | 7.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 2         | 5%      |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                    | 2         | 5%      |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1         | 2.5%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 2.5%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 1         | 2.5%    |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 2.5%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1         | 2.5%    |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                        | 1         | 2.5%    |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 2.5%    |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 2.5%    |
| MediaTek WiFi                                                                 | 1         | 2.5%    |
| Intel Wireless 8265 / 8275                                                    | 1         | 2.5%    |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1         | 2.5%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 1         | 2.5%    |
| Intel Centrino Advanced-N 6235                                                | 1         | 2.5%    |
| Broadcom Limited BCM4321 802.11a/b/g/n                                        | 1         | 2.5%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 1         | 2.5%    |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                            | 1         | 2.5%    |
| Broadcom BCM43224 802.11a/b/g/n                                               | 1         | 2.5%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 1         | 2.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 19        | 67.86%  |
| Intel                 | 4         | 14.29%  |
| Broadcom              | 2         | 7.14%   |
| ASIX Electronics      | 2         | 7.14%   |
| OPPO Electronics      | 1         | 3.57%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12        | 41.38%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 17.24%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 10.34%  |
| Intel Ethernet Connection I217-LM                                 | 2         | 6.9%    |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 6.9%    |
| OPPO KALAMA-MTP_CID:0437_SN:AEEEF597                              | 1         | 3.45%   |
| Intel Ethernet Connection I218-V                                  | 1         | 3.45%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 3.45%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 3.45%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 3.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 34        | 55.74%  |
| Ethernet | 27        | 44.26%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 18        | 52.94%  |
| WiFi     | 16        | 47.06%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 22        | 57.89%  |
| 1     | 11        | 28.95%  |
| 0     | 4         | 10.53%  |
| 3     | 1         | 2.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 28        | 73.68%  |
| Yes  | 10        | 26.32%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 9         | 30%     |
| Qualcomm Atheros Communications | 5         | 16.67%  |
| Foxconn / Hon Hai               | 5         | 16.67%  |
| Lite-On Technology              | 4         | 13.33%  |
| Apple                           | 3         | 10%     |
| Realtek Semiconductor           | 1         | 3.33%   |
| Cambridge Silicon Radio         | 1         | 3.33%   |
| Broadcom                        | 1         | 3.33%   |
| ASUSTek Computer                | 1         | 3.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                   | 6         | 20%     |
| Foxconn / Hon Hai Bluetooth Device                   | 5         | 16.67%  |
| Lite-On Atheros AR3012 Bluetooth                     | 4         | 13.33%  |
| Qualcomm Atheros  Bluetooth Device                   | 2         | 6.67%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                | 2         | 6.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)       | 2         | 6.67%   |
| Apple Bluetooth Host Controller                      | 2         | 6.67%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter              | 1         | 3.33%   |
| Qualcomm Atheros Dell Wireless 1802 Bluetooth 4.0 LE | 1         | 3.33%   |
| Intel Centrino Bluetooth Wireless Transceiver        | 1         | 3.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)  | 1         | 3.33%   |
| Broadcom HP Portable Valentine                       | 1         | 3.33%   |
| ASUS Broadcom BCM20702A0 Bluetooth                   | 1         | 3.33%   |
| Apple Bluetooth USB Host Controller                  | 1         | 3.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Intel    | 33        | 80.49%  |
| Nvidia   | 2         | 4.88%   |
| AMD      | 2         | 4.88%   |
| XMOS     | 1         | 2.44%   |
| Shure    | 1         | 2.44%   |
| M-Audio  | 1         | 2.44%   |
| Logitech | 1         | 2.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 11        | 22.45%  |
| Intel Comet Lake PCH-LP cAVS                                               | 7         | 14.29%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 6.12%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 6.12%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 6.12%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 6.12%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 4.08%   |
| XMOS xCORE USB Audio 2.0                                                   | 1         | 2.04%   |
| Shure MV5                                                                  | 1         | 2.04%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 2.04%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 2.04%   |
| M-Audio M-Audio Fast Track MKII                                            | 1         | 2.04%   |
| Logitech Headset H340                                                      | 1         | 2.04%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 2.04%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 2.04%   |
| Intel CM238 HD Audio Controller                                            | 1         | 2.04%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 2.04%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 2.04%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 2.04%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 2.04%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 2.04%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 2.04%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 2.04%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1         | 2.04%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 4         | 28.57%  |
| Crucial             | 4         | 28.57%  |
| SK hynix            | 3         | 21.43%  |
| Unknown             | 2         | 14.29%  |
| Toshiba             | 1         | 7.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s     | 2         | 12.5%   |
| Crucial RAM CT16G4SFD824A.M16FRS 16GB SODIMM DDR4 2400MT/s | 2         | 12.5%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                | 1         | 6.25%   |
| Unknown RAM Module 16384MB 2133MT/s                        | 1         | 6.25%   |
| Toshiba RAM 8HTF12864HDY-800G1 4GB SODIMM 1066MT/s         | 1         | 6.25%   |
| Toshiba RAM 64T128020EDL2.5C2 1GB SODIMM 1066MT/s          | 1         | 6.25%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s     | 1         | 6.25%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s     | 1         | 6.25%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 1         | 6.25%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s     | 1         | 6.25%   |
| Samsung RAM Module 4GB SODIMM LPDDR3 1867MT/s              | 1         | 6.25%   |
| Samsung RAM K4A8G165WC-BCTD 4GB SODIMM DDR4 2667MT/s       | 1         | 6.25%   |
| Crucial RAM CT4G4SFS8213.C8FBD1 4GB SODIMM DDR4 2133MT/s   | 1         | 6.25%   |
| Crucial RAM CT16G4S24AM.M16FE 16GB SODIMM DDR4 2400MT/s    | 1         | 6.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 8         | 61.54%  |
| DDR3    | 2         | 15.38%  |
| LPDDR3  | 1         | 7.69%   |
| DDR2    | 1         | 7.69%   |
| Unknown | 1         | 7.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SODIMM  | 12        | 92.31%  |
| Unknown | 1         | 7.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 5         | 33.33%  |
| 16384 | 4         | 26.67%  |
| 8192  | 4         | 26.67%  |
| 32768 | 2         | 13.33%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 5         | 35.71%  |
| 2400  | 3         | 21.43%  |
| 2133  | 2         | 14.29%  |
| 1600  | 2         | 14.29%  |
| 1867  | 1         | 7.14%   |
| 1066  | 1         | 7.14%   |

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
| Alcor Micro                            | 4         | 13.33%  |
| Sunplus Innovation Technology          | 3         | 10%     |
| Chicony Electronics                    | 3         | 10%     |
| Apple                                  | 3         | 10%     |
| Acer                                   | 3         | 10%     |
| Silicon Motion                         | 1         | 3.33%   |
| Quanta                                 | 1         | 3.33%   |
| Microdia                               | 1         | 3.33%   |
| Lite-On Technology                     | 1         | 3.33%   |
| IMC Networks                           | 1         | 3.33%   |
| Google                                 | 1         | 3.33%   |
| Genesys Logic                          | 1         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.33%   |
| Bison Electronics                      | 1         | 3.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Alcor Micro HD WebCam                                                      | 3         | 9.68%   |
| Realtek USB2.0 camera                                                      | 2         | 6.45%   |
| Chicony HD User Facing                                                     | 2         | 6.45%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 2         | 6.45%   |
| Acer SunplusIT INC. Integrated Camera                                      | 2         | 6.45%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 3.23%   |
| Sunplus Integrated Camera                                                  | 1         | 3.23%   |
| Sunplus HD WebCam                                                          | 1         | 3.23%   |
| Silicon Motion WebCam SC-13HDL12131N                                       | 1         | 3.23%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 3.23%   |
| Realtek Integrated Webcam                                                  | 1         | 3.23%   |
| Realtek HP Truevision HD                                                   | 1         | 3.23%   |
| Quanta HD Camera                                                           | 1         | 3.23%   |
| Microdia HP Integrated Webcam                                              | 1         | 3.23%   |
| Lite-On Integrated Camera                                                  | 1         | 3.23%   |
| IMC Networks Lenovo EasyCamera                                             | 1         | 3.23%   |
| Genesys Logic Camera                                                       | 1         | 3.23%   |
| Chicony USB2.0 UVC WebCam                                                  | 1         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 1         | 3.23%   |
| Bison SunplusIT Integrated Camera                                          | 1         | 3.23%   |
| Apple iBridge                                                              | 1         | 3.23%   |
| Apple Built-in iSight                                                      | 1         | 3.23%   |
| Alcor Micro HP Webcam-101                                                  | 1         | 3.23%   |
| Acer BisonCam, NB Pro                                                      | 1         | 3.23%   |
| Unknown                                                                    | 1         | 3.23%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 3         | 42.86%  |
| LighTuning Technology | 2         | 28.57%  |
| Synaptics             | 1         | 14.29%  |
| STMicroelectronics    | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor     | 3         | 42.86%  |
| Synaptics Metallica MOH Touch Fingerprint Reader | 1         | 14.29%  |
| STMicroelectronics Fingerprint Reader            | 1         | 14.29%  |
| LighTuning ES603 Swipe Fingerprint Sensor        | 1         | 14.29%  |
| LighTuning EgisTec Touch Fingerprint Sensor      | 1         | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Purism, SPC | 2         | 40%     |
| O2 Micro    | 1         | 20%     |
| Clay Logic  | 1         | 20%     |
| Alcor Micro | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Purism, SPC Librem Key              | 2         | 40%     |
| O2 Micro Oz776 SmartCard Reader     | 1         | 20%     |
| Clay Logic Nitrokey Pro             | 1         | 20%     |
| Alcor Micro AU9540 Smartcard Reader | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 18        | 46.15%  |
| 1     | 15        | 38.46%  |
| 2     | 3         | 7.69%   |
| 3     | 2         | 5.13%   |
| 4     | 1         | 2.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 8         | 25.81%  |
| Fingerprint reader    | 7         | 22.58%  |
| Bluetooth             | 6         | 19.35%  |
| Graphics card         | 4         | 12.9%   |
| Multimedia controller | 3         | 9.68%   |
| Chipcard              | 2         | 6.45%   |
| Camera                | 1         | 3.23%   |

