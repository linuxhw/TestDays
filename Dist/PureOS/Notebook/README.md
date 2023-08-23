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

Total: 52

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | G505s 20255                 | [107c99d5ee](https://linux-hardware.org/?probe=107c99d5ee) | Jul 03, 2023 |
| Lenovo        | B50-70 20384                | [5e3a2796a9](https://linux-hardware.org/?probe=5e3a2796a9) | Jun 01, 2023 |
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
| PureOS 10.0 | 15        | 36.59%  |
| PureOS 10   | 12        | 29.27%  |
| PureOS 9.0  | 9         | 21.95%  |
| PureOS 9    | 2         | 4.88%   |
| PureOS 8    | 2         | 4.88%   |
| PureOS 10.x | 1         | 2.44%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| PureOS | 40        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Notebooks | Percent |
|----------------------------------|-----------|---------|
| 4.19.0-5-amd64                   | 9         | 21.43%  |
| 5.10.0-13-amd64                  | 5         | 11.9%   |
| 5.10.0-14-amd64                  | 4         | 9.52%   |
| 5.10.0-8-amd64                   | 3         | 7.14%   |
| 5.10.0-21-amd64                  | 3         | 7.14%   |
| 5.10.0-7-amd64                   | 2         | 4.76%   |
| 5.10.0-23-amd64                  | 2         | 4.76%   |
| 5.10.0-11-amd64                  | 2         | 4.76%   |
| 6.1.0-1-librem5                  | 1         | 2.38%   |
| 5.7.0-1-librem5                  | 1         | 2.38%   |
| 5.7.0-0.38-1-pinebookpro-hwaccel | 1         | 2.38%   |
| 5.15.0-2-amd64                   | 1         | 2.38%   |
| 5.10.0-9-amd64                   | 1         | 2.38%   |
| 5.10.0-6-amd64                   | 1         | 2.38%   |
| 5.10.0-19-amd64                  | 1         | 2.38%   |
| 5.10.0-18-amd64                  | 1         | 2.38%   |
| 5.10.0-17-amd64                  | 1         | 2.38%   |
| 5.10.0-12-amd64                  | 1         | 2.38%   |
| 4.19.0-14-amd64                  | 1         | 2.38%   |
| 4.16.0-1-amd64                   | 1         | 2.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 26        | 63.41%  |
| 4.19.0  | 10        | 24.39%  |
| 5.7.0   | 2         | 4.88%   |
| 6.1.0   | 1         | 2.44%   |
| 5.15.0  | 1         | 2.44%   |
| 4.16.0  | 1         | 2.44%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 26        | 63.41%  |
| 4.19    | 10        | 24.39%  |
| 5.7     | 2         | 4.88%   |
| 6.1     | 1         | 2.44%   |
| 5.15    | 1         | 2.44%   |
| 4.16    | 1         | 2.44%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 37        | 92.5%   |
| aarch64 | 3         | 7.5%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 33        | 80.49%  |
| Unknown         | 4         | 9.76%   |
| KDE5            | 2         | 4.88%   |
| MATE            | 1         | 2.44%   |
| GNOME Flashback | 1         | 2.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 29        | 69.05%  |
| X11     | 7         | 16.67%  |
| Unknown | 4         | 9.52%   |
| Tty     | 2         | 4.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 23        | 57.5%   |
| GDM     | 13        | 32.5%   |
| GDM3    | 4         | 10%     |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 18        | 42.86%  |
| en_GB   | 4         | 9.52%   |
| Unknown | 4         | 9.52%   |
| pl_PL   | 3         | 7.14%   |
| C       | 3         | 7.14%   |
| de_DE   | 2         | 4.76%   |
| zh_CN   | 1         | 2.38%   |
| ru_RU   | 1         | 2.38%   |
| pt_PT   | 1         | 2.38%   |
| it_IT   | 1         | 2.38%   |
| fr_FR   | 1         | 2.38%   |
| es_CR   | 1         | 2.38%   |
| en_IL   | 1         | 2.38%   |
| en_AU   | 1         | 2.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 35        | 87.5%   |
| EFI  | 5         | 12.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 34        | 85%     |
| Overlay | 2         | 5%      |
| Unknown | 2         | 5%      |
| Ext2    | 1         | 2.5%    |
| Btrfs   | 1         | 2.5%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 24        | 60%     |
| MBR     | 9         | 22.5%   |
| GPT     | 7         | 17.5%   |

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
| No        | 37        | 92.5%   |
| Yes       | 3         | 7.5%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Purism              | 12        | 30%     |
| Lenovo              | 8         | 20%     |
| Dell                | 4         | 10%     |
| Apple               | 4         | 10%     |
| Hewlett-Packard     | 3         | 7.5%    |
| Acer                | 2         | 5%      |
| Toshiba             | 1         | 2.5%    |
| Samsung Electronics | 1         | 2.5%    |
| Pine Microsystems   | 1         | 2.5%    |
| Notebook            | 1         | 2.5%    |
| HUAWEI              | 1         | 2.5%    |
| Google              | 1         | 2.5%    |
| Unknown             | 1         | 2.5%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Purism Librem 14                      | 6         | 15%     |
| Purism Librem 15 v4                   | 2         | 5%      |
| HP Pavilion g6                        | 2         | 5%      |
| Toshiba Satellite L500D               | 1         | 2.5%    |
| Samsung 530U3C/530U4C/532U3C          | 1         | 2.5%    |
| Purism Librem 5r4                     | 1         | 2.5%    |
| Purism Librem 15 v3                   | 1         | 2.5%    |
| Purism Librem 13 v4                   | 1         | 2.5%    |
| Purism Librem 13 v2                   | 1         | 2.5%    |
| Pine Microsystems Pine64 Pinebook Pro | 1         | 2.5%    |
| Notebook P17SM                        | 1         | 2.5%    |
| Lenovo ThinkPad T540p 20BFS23T00      | 1         | 2.5%    |
| Lenovo ThinkPad T440p                 | 1         | 2.5%    |
| Lenovo ThinkPad T440 20B60044RT       | 1         | 2.5%    |
| Lenovo ThinkPad E480 20KN003SUS       | 1         | 2.5%    |
| Lenovo ThinkPad 13 2nd Gen 20J2S00G00 | 1         | 2.5%    |
| Lenovo IdeaPad U430 Touch 20270       | 1         | 2.5%    |
| Lenovo G505s 20255                    | 1         | 2.5%    |
| Lenovo B50-70 20384                   | 1         | 2.5%    |
| HUAWEI NBLB-WAX9N                     | 1         | 2.5%    |
| HP Pavilion Notebook                  | 1         | 2.5%    |
| Google Droid                          | 1         | 2.5%    |
| Dell XPS 13 9370                      | 1         | 2.5%    |
| Dell Latitude D430                    | 1         | 2.5%    |
| Dell Inspiron 5547                    | 1         | 2.5%    |
| Dell Inspiron 15-3567                 | 1         | 2.5%    |
| Apple MacBookPro6,1                   | 1         | 2.5%    |
| Apple MacBookPro14,2                  | 1         | 2.5%    |
| Apple MacBookAir7,2                   | 1         | 2.5%    |
| Apple MacBook9,1                      | 1         | 2.5%    |
| Acer Swift SF113-31                   | 1         | 2.5%    |
| Acer Nitro AN515-43                   | 1         | 2.5%    |
| Unknown                               | 1         | 2.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Purism Librem            | 12        | 30%     |
| Lenovo ThinkPad          | 5         | 12.5%   |
| HP Pavilion              | 3         | 7.5%    |
| Dell Inspiron            | 2         | 5%      |
| Toshiba Satellite        | 1         | 2.5%    |
| Samsung 530U3C           | 1         | 2.5%    |
| Pine Microsystems Pine64 | 1         | 2.5%    |
| Notebook P17SM           | 1         | 2.5%    |
| Lenovo IdeaPad           | 1         | 2.5%    |
| Lenovo G505s             | 1         | 2.5%    |
| Lenovo B50-70            | 1         | 2.5%    |
| HUAWEI NBLB-WAX9N        | 1         | 2.5%    |
| Google Droid             | 1         | 2.5%    |
| Dell XPS                 | 1         | 2.5%    |
| Dell Latitude            | 1         | 2.5%    |
| Apple MacBookPro6        | 1         | 2.5%    |
| Apple MacBookPro14       | 1         | 2.5%    |
| Apple MacBookAir7        | 1         | 2.5%    |
| Apple MacBook9           | 1         | 2.5%    |
| Acer Swift               | 1         | 2.5%    |
| Acer Nitro               | 1         | 2.5%    |
| Unknown                  | 1         | 2.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 6         | 15%     |
| 2017    | 5         | 12.5%   |
| 2013    | 5         | 12.5%   |
| 2019    | 4         | 10%     |
| Unknown | 4         | 10%     |
| 2020    | 3         | 7.5%    |
| 2018    | 2         | 5%      |
| 2015    | 2         | 5%      |
| 2014    | 2         | 5%      |
| 2011    | 2         | 5%      |
| 2023    | 1         | 2.5%    |
| 2016    | 1         | 2.5%    |
| 2012    | 1         | 2.5%    |
| 2009    | 1         | 2.5%    |
| 2007    | 1         | 2.5%    |

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
| Disabled | 40        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 27        | 67.5%   |
| Yes  | 13        | 32.5%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 10        | 25%     |
| 16.01-24.0 | 10        | 25%     |
| 32.01-64.0 | 6         | 15%     |
| 3.01-4.0   | 6         | 15%     |
| 8.01-16.0  | 5         | 12.5%   |
| 24.01-32.0 | 1         | 2.5%    |
| 2.01-3.0   | 1         | 2.5%    |
| 1.01-2.0   | 1         | 2.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 13        | 30.95%  |
| 3.01-4.0  | 10        | 23.81%  |
| 1.01-2.0  | 10        | 23.81%  |
| 4.01-8.0  | 7         | 16.67%  |
| 8.01-16.0 | 2         | 4.76%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 27        | 67.5%   |
| 2      | 11        | 27.5%   |
| 0      | 2         | 5%      |

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
| Yes       | 36        | 90%     |
| No        | 4         | 10%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 31        | 77.5%   |
| No        | 9         | 22.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Notebooks | Percent |
|------------------------|-----------|---------|
| USA                    | 9         | 21.43%  |
| UK                     | 5         | 11.9%   |
| Germany                | 3         | 7.14%   |
| Canada                 | 3         | 7.14%   |
| Brazil                 | 3         | 7.14%   |
| Poland                 | 2         | 4.76%   |
| Italy                  | 2         | 4.76%   |
| France                 | 2         | 4.76%   |
| Australia              | 2         | 4.76%   |
| Turkey                 | 1         | 2.38%   |
| South Africa           | 1         | 2.38%   |
| Russia                 | 1         | 2.38%   |
| Portugal               | 1         | 2.38%   |
| Paraguay               | 1         | 2.38%   |
| Kazakhstan             | 1         | 2.38%   |
| Israel                 | 1         | 2.38%   |
| Iran                   | 1         | 2.38%   |
| Costa Rica             | 1         | 2.38%   |
| China                  | 1         | 2.38%   |
| Bosnia and Herzegovina | 1         | 2.38%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| London             | 2         | 4.76%   |
| Windsor            | 1         | 2.38%   |
| Warsaw             | 1         | 2.38%   |
| Vancouver          | 1         | 2.38%   |
| Thorpe Hamlet      | 1         | 2.38%   |
| Tel Aviv           | 1         | 2.38%   |
| Stuttgart          | 1         | 2.38%   |
| Stargard           | 1         | 2.38%   |
| Spencer            | 1         | 2.38%   |
| Seattle            | 1         | 2.38%   |
| Sao Paulo          | 1         | 2.38%   |
| San Jose           | 1         | 2.38%   |
| Paris              | 1         | 2.38%   |
| New York           | 1         | 2.38%   |
| Montreal           | 1         | 2.38%   |
| Milwaukee          | 1         | 2.38%   |
| Milpitas           | 1         | 2.38%   |
| Melbourne          | 1         | 2.38%   |
| Mankato            | 1         | 2.38%   |
| Lambeth            | 1         | 2.38%   |
| Krasnogorsk        | 1         | 2.38%   |
| Istanbul           | 1         | 2.38%   |
| Hernandarias       | 1         | 2.38%   |
| Guimaraes          | 1         | 2.38%   |
| Grasse             | 1         | 2.38%   |
| Genoa              | 1         | 2.38%   |
| Eberswalde         | 1         | 2.38%   |
| Cape Town          | 1         | 2.38%   |
| Camden             | 1         | 2.38%   |
| Bowdoin Center     | 1         | 2.38%   |
| Blumenau           | 1         | 2.38%   |
| Big Sky            | 1         | 2.38%   |
| Berlin             | 1         | 2.38%   |
| Banja Luka         | 1         | 2.38%   |
| Bandar-e Asalūyeh | 1         | 2.38%   |
| Araçatuba         | 1         | 2.38%   |
| Antioch            | 1         | 2.38%   |
| Ankang             | 1         | 2.38%   |
| Almese             | 1         | 2.38%   |
| Almaty             | 1         | 2.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 18     | 29.79%  |
| Unknown             | 4         | 4      | 8.51%   |
| Seagate             | 3         | 3      | 6.38%   |
| SanDisk             | 3         | 3      | 6.38%   |
| HGST                | 3         | 3      | 6.38%   |
| Apple               | 3         | 5      | 6.38%   |
| WDC                 | 2         | 2      | 4.26%   |
| Crucial             | 2         | 4      | 4.26%   |
| A-DATA Technology   | 2         | 2      | 4.26%   |
| Transcend           | 1         | 1      | 2.13%   |
| Toshiba             | 1         | 1      | 2.13%   |
| Qumo                | 1         | 1      | 2.13%   |
| Plextor             | 1         | 1      | 2.13%   |
| Phison              | 1         | 1      | 2.13%   |
| Mushkin             | 1         | 1      | 2.13%   |
| JMicron Technology  | 1         | 1      | 2.13%   |
| Intel               | 1         | 1      | 2.13%   |
| Hitachi             | 1         | 1      | 2.13%   |
| BIWIN               | 1         | 1      | 2.13%   |
| ADATA Technology    | 1         | 1      | 2.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  64GB                              | 2         | 4.08%   |
| Seagate ST1000LM048-2E7172 1TB                      | 2         | 4.08%   |
| Samsung SSD 970 PRO 1TB                             | 2         | 4.08%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1         | 2.04%   |
| WDC WDS100T2B0C-00PXH0 1TB                          | 1         | 2.04%   |
| Unknown MMC Card  32GB                              | 1         | 2.04%   |
| Unknown DA4128  128GB                               | 1         | 2.04%   |
| Transcend TS240GMTS420S 240GB SSD                   | 1         | 2.04%   |
| Toshiba NVMe SSD Drive 512GB                        | 1         | 2.04%   |
| Seagate NVMe SSD Drive 2TB                          | 1         | 2.04%   |
| SanDisk SSD i100 24GB                               | 1         | 2.04%   |
| SanDisk SDSSDP128G 128GB                            | 1         | 2.04%   |
| SanDisk SDSSDH3500G 500GB                           | 1         | 2.04%   |
| Samsung SSD 970 EVO Plus 500GB                      | 1         | 2.04%   |
| Samsung SSD 970 EVO Plus 2TB                        | 1         | 2.04%   |
| Samsung SSD 970 EVO 250GB                           | 1         | 2.04%   |
| Samsung SSD 960 EVO 500GB                           | 1         | 2.04%   |
| Samsung SSD 960 EVO 250GB                           | 1         | 2.04%   |
| Samsung SSD 860 EVO 500GB                           | 1         | 2.04%   |
| Samsung SSD 860 EVO 250GB                           | 1         | 2.04%   |
| Samsung SSD 860 EVO 1TB                             | 1         | 2.04%   |
| Samsung SSD 850 EVO 500GB                           | 1         | 2.04%   |
| Samsung SSD 850 EVO 250GB                           | 1         | 2.04%   |
| Samsung NVMe SSD Drive 1TB                          | 1         | 2.04%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 1         | 2.04%   |
| Samsung HS08XJC 80GB                                | 1         | 2.04%   |
| Qumo SSD 120GB                                      | 1         | 2.04%   |
| Plextor PX-1TM6Pro 1024GB SSD                       | 1         | 2.04%   |
| Phison PM8512GPTCB4B8TF-E13T4 512GB                 | 1         | 2.04%   |
| Mushkin MKNSSDRE250GB-LT                            | 1         | 2.04%   |
| JMicron Generic 512GB                               | 1         | 2.04%   |
| Intel SSDSC2BF180A4H 180GB                          | 1         | 2.04%   |
| Hitachi HTS545050A7E380 500GB                       | 1         | 2.04%   |
| HGST HTS721010A9E630 1TB                            | 1         | 2.04%   |
| HGST HTS545050B7E660 500GB                          | 1         | 2.04%   |
| HGST HTS541010A9E680 1TB                            | 1         | 2.04%   |
| Crucial CT250MX500SSD4 250GB                        | 1         | 2.04%   |
| Crucial CT2000MX500SSD1 2TB                         | 1         | 2.04%   |
| BIWIN SSD 120GB                                     | 1         | 2.04%   |
| Apple SSD SM0128G 121GB                             | 1         | 2.04%   |

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
| Samsung Electronics | 6         | 8      | 28.57%  |
| SanDisk             | 3         | 3      | 14.29%  |
| Crucial             | 2         | 4      | 9.52%   |
| A-DATA Technology   | 2         | 2      | 9.52%   |
| WDC                 | 1         | 1      | 4.76%   |
| Transcend           | 1         | 1      | 4.76%   |
| Qumo                | 1         | 1      | 4.76%   |
| Plextor             | 1         | 1      | 4.76%   |
| Mushkin             | 1         | 1      | 4.76%   |
| Intel               | 1         | 1      | 4.76%   |
| BIWIN               | 1         | 1      | 4.76%   |
| Apple               | 1         | 1      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 18        | 25     | 40%     |
| NVMe | 15        | 18     | 33.33%  |
| HDD  | 8         | 8      | 17.78%  |
| MMC  | 4         | 4      | 8.89%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 22        | 31     | 51.16%  |
| NVMe | 15        | 18     | 34.88%  |
| MMC  | 4         | 4      | 9.3%    |
| SAS  | 2         | 2      | 4.65%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 17        | 24     | 68%     |
| 0.51-1.0   | 6         | 6      | 24%     |
| 1.01-2.0   | 2         | 3      | 8%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 18        | 45%     |
| 101-250    | 6         | 15%     |
| 21-50      | 3         | 7.5%    |
| 51-100     | 3         | 7.5%    |
| Unknown    | 3         | 7.5%    |
| 251-500    | 2         | 5%      |
| 1001-2000  | 2         | 5%      |
| 501-1000   | 2         | 5%      |
| 2001-3000  | 1         | 2.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 28        | 70%     |
| 21-50    | 4         | 10%     |
| 501-1000 | 3         | 7.5%    |
| Unknown  | 3         | 7.5%    |
| 251-500  | 1         | 2.5%    |
| 51-100   | 1         | 2.5%    |

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
| Detected | 26        | 37     | 66.67%  |
| Works    | 12        | 17     | 30.77%  |
| Malfunc  | 1         | 1      | 2.56%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 21        | 52.5%   |
| Samsung Electronics          | 9         | 22.5%   |
| AMD                          | 3         | 7.5%    |
| Apple                        | 2         | 5%      |
| Toshiba America Info Systems | 1         | 2.5%    |
| Seagate Technology           | 1         | 2.5%    |
| SanDisk                      | 1         | 2.5%    |
| Phison Electronics           | 1         | 2.5%    |
| ADATA Technology             | 1         | 2.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 17.5%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 6         | 15%     |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 7.5%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 7.5%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 5%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 5%      |
| Apple S3X NVMe Controller                                                      | 2         | 5%      |
| AMD FCH SATA Controller [AHCI mode]                                            | 2         | 5%      |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 2.5%    |
| Seagate FireCuda/IronWolf 510 SSD                                              | 1         | 2.5%    |
| SanDisk WD Green SN350 NVMe SSD 240GB (DRAM-less)                              | 1         | 2.5%    |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 1         | 2.5%    |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 2.5%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 2.5%    |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 2.5%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 2.5%    |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 2.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 2.5%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 2.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 2.5%    |
| ADATA IM2P33F3 NVMe SSD (DRAM-less)                                            | 1         | 2.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 24        | 60%     |
| NVMe | 15        | 37.5%   |
| IDE  | 1         | 2.5%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 34        | 85%     |
| AMD     | 3         | 7.5%    |
| ARM     | 2         | 5%      |
| Unknown | 1         | 2.5%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10710U CPU @ 1.10GHz            | 6         | 15%     |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 10%     |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 5%      |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 5%      |
| ARM Processor                                 | 2         | 5%      |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 2.5%    |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 2.5%    |
| Intel Core m5-6Y54 CPU @ 1.10GHz              | 1         | 2.5%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 2.5%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 2.5%    |
| Intel Core i7-7567U CPU @ 3.50GHz             | 1         | 2.5%    |
| Intel Core i7-4710MQ CPU @ 2.50GHz            | 1         | 2.5%    |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 1         | 2.5%    |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 2.5%    |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 2.5%    |
| Intel Core i5-5250U CPU @ 1.60GHz             | 1         | 2.5%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 2.5%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 2.5%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 2.5%    |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 1         | 2.5%    |
| Intel Core i3-4010U CPU @ 1.70GHz             | 1         | 2.5%    |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 2.5%    |
| Intel Core i3-3120M CPU @ 2.50GHz             | 1         | 2.5%    |
| Intel Core i3-2330M CPU @ 2.20GHz             | 1         | 2.5%    |
| Intel Core 2 Duo CPU U7700 @ 1.33GHz          | 1         | 2.5%    |
| AMD Turion II Dual-Core Mobile M520           | 1         | 2.5%    |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 1         | 2.5%    |
| AMD A8-5550M APU with Radeon HD Graphics      | 1         | 2.5%    |
|                                               | 1         | 2.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 19        | 47.5%   |
| Intel Core i5           | 7         | 17.5%   |
| Intel Core i3           | 4         | 10%     |
| Other                   | 3         | 7.5%    |
| Intel Pentium Silver    | 1         | 2.5%    |
| Intel Pentium           | 1         | 2.5%    |
| Intel Core m5           | 1         | 2.5%    |
| Intel Core 2 Duo        | 1         | 2.5%    |
| AMD Turion II Dual-Core | 1         | 2.5%    |
| AMD Ryzen 5             | 1         | 2.5%    |
| AMD A8                  | 1         | 2.5%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 22        | 55%     |
| 4      | 12        | 30%     |
| 6      | 6         | 15%     |

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
| 2      | 33        | 82.5%   |
| 1      | 7         | 17.5%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 38        | 92.68%  |
| Unknown        | 3         | 7.32%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 28        | 70%     |
| 0xa0660    | 3         | 7.5%    |
| 0x406e3    | 3         | 7.5%    |
| 0x40651    | 2         | 5%      |
| 0x806ec    | 1         | 2.5%    |
| 0x806e9    | 1         | 2.5%    |
| 0x08108109 | 1         | 2.5%    |
| 0x06001119 | 1         | 2.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 10        | 25%     |
| Haswell       | 7         | 17.5%   |
| CometLake     | 6         | 15%     |
| Skylake       | 3         | 7.5%    |
| Unknown       | 3         | 7.5%    |
| IvyBridge     | 2         | 5%      |
| Zen+          | 1         | 2.5%    |
| Westmere      | 1         | 2.5%    |
| SandyBridge   | 1         | 2.5%    |
| Piledriver    | 1         | 2.5%    |
| K10           | 1         | 2.5%    |
| Goldmont plus | 1         | 2.5%    |
| Goldmont      | 1         | 2.5%    |
| Core          | 1         | 2.5%    |
| Broadwell     | 1         | 2.5%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 34        | 79.07%  |
| AMD    | 5         | 11.63%  |
| Nvidia | 4         | 9.3%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                 | 6         | 13.04%  |
| Intel Comet Lake UHD Graphics                                                         | 6         | 13.04%  |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 4         | 8.7%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 3         | 6.52%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 2         | 4.35%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 2         | 4.35%   |
| Nvidia GT216M [GeForce GT 330M]                                                       | 1         | 2.17%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 1         | 2.17%   |
| Nvidia GK208M [GeForce GT 730M]                                                       | 1         | 2.17%   |
| Nvidia GK104M [GeForce GTX 870M]                                                      | 1         | 2.17%   |
| Intel UHD Graphics 620                                                                | 1         | 2.17%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller         | 1         | 2.17%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller             | 1         | 2.17%   |
| Intel Iris Plus Graphics 650                                                          | 1         | 2.17%   |
| Intel HD Graphics 630                                                                 | 1         | 2.17%   |
| Intel HD Graphics 6000                                                                | 1         | 2.17%   |
| Intel HD Graphics 515                                                                 | 1         | 2.17%   |
| Intel GeminiLake [UHD Graphics 605]                                                   | 1         | 2.17%   |
| Intel Core Processor Integrated Graphics Controller                                   | 1         | 2.17%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 1         | 2.17%   |
| Intel Apollo Lake [HD Graphics 505]                                                   | 1         | 2.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 1         | 2.17%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 2.17%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                             | 1         | 2.17%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                             | 1         | 2.17%   |
| AMD Richland [Radeon HD 8550G]                                                        | 1         | 2.17%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 1         | 2.17%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520/610 Mobile]                      | 1         | 2.17%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                   | 1         | 2.17%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 27        | 67.5%   |
| Other          | 4         | 10%     |
| Intel + Nvidia | 4         | 10%     |
| 2 x AMD        | 2         | 5%      |
| Intel + AMD    | 2         | 5%      |
| 1 x AMD        | 1         | 2.5%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 36        | 90%     |
| Unknown | 4         | 10%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 39        | 97.5%   |
| 3.01-4.0   | 1         | 2.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 8         | 17.39%  |
| LG Display              | 7         | 15.22%  |
| BOE                     | 7         | 15.22%  |
| Samsung Electronics     | 5         | 10.87%  |
| Apple                   | 4         | 8.7%    |
| Unknown                 | 2         | 4.35%   |
| AU Optronics            | 2         | 4.35%   |
| Toshiba                 | 1         | 2.17%   |
| Sharp                   | 1         | 2.17%   |
| PANDA                   | 1         | 2.17%   |
| Lenovo                  | 1         | 2.17%   |
| Iiyama                  | 1         | 2.17%   |
| Grundig                 | 1         | 2.17%   |
| Goldstar                | 1         | 2.17%   |
| Chi Mei Optoelectronics | 1         | 2.17%   |
| BenQ                    | 1         | 2.17%   |
| ASUSTek Computer        | 1         | 2.17%   |
| Acer                    | 1         | 2.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC434B 3840x2160 344x194mm 15.5-inch     | 3         | 6.52%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 3         | 6.52%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 2         | 4.35%   |
| Chimei Innolux LCD Monitor CMN1415 1920x1080 309x173mm 13.9-inch          | 2         | 4.35%   |
| Toshiba LCD Monitor LCD3706 1280x800 261x163mm 12.1-inch                  | 1         | 2.17%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                   | 1         | 2.17%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch      | 1         | 2.17%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 1         | 2.17%   |
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch                   | 1         | 2.17%   |
| LG Display LCD Monitor LGD0563 1920x1080 340x190mm 15.3-inch              | 1         | 2.17%   |
| LG Display LCD Monitor LGD053B 1920x1080 294x165mm 13.3-inch              | 1         | 2.17%   |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch              | 1         | 2.17%   |
| LG Display LCD Monitor LGD03F0 1366x768 310x174mm 14.0-inch               | 1         | 2.17%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch               | 1         | 2.17%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch               | 1         | 2.17%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch               | 1         | 2.17%   |
| Lenovo LEN Y44w-10 LEN65EA 3840x1200 1052x329mm 43.4-inch                 | 1         | 2.17%   |
| Iiyama PL2792H IVM664F 1920x1080 598x336mm 27.0-inch                      | 1         | 2.17%   |
| Grundig WUXGA GRU4448 1920x1080                                           | 1         | 2.17%   |
| Goldstar IPS231 GSM5817 1920x1080 510x290mm 23.1-inch                     | 1         | 2.17%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch          | 1         | 2.17%   |
| Chimei Innolux LCD Monitor CMN15BD 1366x768 344x193mm 15.5-inch           | 1         | 2.17%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch           | 1         | 2.17%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 2.17%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                     | 1         | 2.17%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                     | 1         | 2.17%   |
| BOE LCD Monitor BOE079A 1920x1080 309x173mm 13.9-inch                     | 1         | 2.17%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                      | 1         | 2.17%   |
| BOE LCD Monitor BOE06C2 1366x768 344x194mm 15.5-inch                      | 1         | 2.17%   |
| BOE LCD Monitor BOE06BE 1920x1080 294x165mm 13.3-inch                     | 1         | 2.17%   |
| BOE LCD Monitor BOE0641 1920x1080 344x193mm 15.5-inch                     | 1         | 2.17%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                         | 1         | 2.17%   |
| AU Optronics LCD Monitor AUO713C 1366x768 309x173mm 13.9-inch             | 1         | 2.17%   |
| AU Optronics LCD Monitor AUO10ED 1920x1080 344x193mm 15.5-inch            | 1         | 2.17%   |
| ASUSTek Computer VP249 AUS24AF 1920x1080 527x296mm 23.8-inch              | 1         | 2.17%   |
| Apple Color LCD APPA034 2880x1800 286x179mm 13.3-inch                     | 1         | 2.17%   |
| Apple Color LCD APPA027 2304x1440 259x162mm 12.0-inch                     | 1         | 2.17%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 1         | 2.17%   |
| Apple Color LCD APP9CCF 1920x1200 367x230mm 17.1-inch                     | 1         | 2.17%   |
| Acer H236HL ACR0318 1920x1080 509x286mm 23.0-inch                         | 1         | 2.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 18        | 42.86%  |
| 1366x768 (WXGA)   | 9         | 21.43%  |
| 3840x2160 (4K)    | 6         | 14.29%  |
| 2288x1287         | 2         | 4.76%   |
| 3840x1200         | 1         | 2.38%   |
| 2880x1800         | 1         | 2.38%   |
| 2304x1440         | 1         | 2.38%   |
| 1920x1200 (WUXGA) | 1         | 2.38%   |
| 1600x900 (HD+)    | 1         | 2.38%   |
| 1440x900 (WXGA+)  | 1         | 2.38%   |
| 1280x800 (WXGA)   | 1         | 2.38%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 15        | 32.61%  |
| 15     | 14        | 30.43%  |
| 14     | 3         | 6.52%   |
| 142    | 2         | 4.35%   |
| 24     | 2         | 4.35%   |
| 23     | 2         | 4.35%   |
| 17     | 2         | 4.35%   |
| 12     | 2         | 4.35%   |
| 54     | 1         | 2.17%   |
| 43     | 1         | 2.17%   |
| 40     | 1         | 2.17%   |
| 27     | 1         | 2.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 24        | 53.33%  |
| 201-300        | 8         | 17.78%  |
| 501-600        | 5         | 11.11%  |
| 351-400        | 3         | 6.67%   |
| More than 2000 | 2         | 4.44%   |
| 1001-1500      | 2         | 4.44%   |
| 801-900        | 1         | 2.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 30        | 78.95%  |
| 16/10 | 5         | 13.16%  |
| 1.00  | 2         | 5.26%   |
| 3.20  | 1         | 2.63%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 14        | 30.43%  |
| 81-90          | 13        | 28.26%  |
| 71-80          | 5         | 10.87%  |
| 201-250        | 4         | 8.7%    |
| More than 1000 | 3         | 6.52%   |
| 61-70          | 2         | 4.35%   |
| 501-1000       | 2         | 4.35%   |
| 301-350        | 1         | 2.17%   |
| 131-140        | 1         | 2.17%   |
| 121-130        | 1         | 2.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 17        | 36.96%  |
| 51-100        | 10        | 21.74%  |
| 101-120       | 7         | 15.22%  |
| More than 240 | 6         | 13.04%  |
| 161-240       | 4         | 8.7%    |
| 1-50          | 2         | 4.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 28        | 70%     |
| 2     | 8         | 20%     |
| 0     | 3         | 7.5%    |
| 3     | 1         | 2.5%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 23        | 35.94%  |
| Qualcomm Atheros                | 16        | 25%     |
| Intel                           | 11        | 17.19%  |
| Broadcom                        | 5         | 7.81%   |
| Broadcom Limited                | 3         | 4.69%   |
| ASIX Electronics                | 2         | 3.13%   |
| Ralink                          | 1         | 1.56%   |
| Qualcomm Atheros Communications | 1         | 1.56%   |
| OPPO Electronics                | 1         | 1.56%   |
| MediaTek                        | 1         | 1.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 13        | 17.81%  |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 12        | 16.44%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 5         | 6.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 3         | 4.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 3         | 4.11%   |
| Intel Wireless 7265                                                           | 3         | 4.11%   |
| Intel Wireless 7260                                                           | 3         | 4.11%   |
| Intel Ethernet Connection I217-LM                                             | 2         | 2.74%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                    | 2         | 2.74%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 2         | 2.74%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1         | 1.37%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 1.37%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 1         | 1.37%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1         | 1.37%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 1.37%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1         | 1.37%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                        | 1         | 1.37%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                        | 1         | 1.37%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 1.37%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.37%   |
| OPPO SM6375-QRD _SN:F4A23F05                                                  | 1         | 1.37%   |
| MediaTek WiFi                                                                 | 1         | 1.37%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 1.37%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1         | 1.37%   |
| Intel Ethernet Connection I218-V                                              | 1         | 1.37%   |
| Intel Ethernet Connection (4) I219-V                                          | 1         | 1.37%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 1         | 1.37%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 1.37%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1         | 1.37%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                       | 1         | 1.37%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                        | 1         | 1.37%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 1         | 1.37%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                            | 1         | 1.37%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 1         | 1.37%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 1         | 1.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 16        | 38.1%   |
| Intel                           | 10        | 23.81%  |
| Realtek Semiconductor           | 6         | 14.29%  |
| Broadcom                        | 4         | 9.52%   |
| Broadcom Limited                | 3         | 7.14%   |
| Ralink                          | 1         | 2.38%   |
| Qualcomm Atheros Communications | 1         | 2.38%   |
| MediaTek                        | 1         | 2.38%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 12        | 28.57%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 3         | 7.14%   |
| Intel Wireless 7265                                                           | 3         | 7.14%   |
| Intel Wireless 7260                                                           | 3         | 7.14%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                    | 2         | 4.76%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1         | 2.38%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 2.38%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 1         | 2.38%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1         | 2.38%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 2.38%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1         | 2.38%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                        | 1         | 2.38%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 2.38%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 2.38%   |
| MediaTek WiFi                                                                 | 1         | 2.38%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 2.38%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1         | 2.38%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 1         | 2.38%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 2.38%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                        | 1         | 2.38%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 1         | 2.38%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                            | 1         | 2.38%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 1         | 2.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 1         | 2.38%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 20        | 66.67%  |
| Intel                 | 4         | 13.33%  |
| Broadcom              | 2         | 6.67%   |
| ASIX Electronics      | 2         | 6.67%   |
| Qualcomm Atheros      | 1         | 3.33%   |
| OPPO Electronics      | 1         | 3.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 41.94%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 16.13%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 9.68%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 6.45%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 6.45%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 3.23%   |
| OPPO SM6375-QRD _SN:F4A23F05                                      | 1         | 3.23%   |
| Intel Ethernet Connection I218-V                                  | 1         | 3.23%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 3.23%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 3.23%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 3.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 36        | 55.38%  |
| Ethernet | 29        | 44.62%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 19        | 52.78%  |
| WiFi     | 17        | 47.22%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 24        | 60%     |
| 1     | 11        | 27.5%   |
| 0     | 4         | 10%     |
| 3     | 1         | 2.5%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 30        | 75%     |
| Yes  | 10        | 25%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 9         | 29.03%  |
| Qualcomm Atheros Communications | 5         | 16.13%  |
| Foxconn / Hon Hai               | 5         | 16.13%  |
| Lite-On Technology              | 4         | 12.9%   |
| Apple                           | 3         | 9.68%   |
| Realtek Semiconductor           | 2         | 6.45%   |
| Cambridge Silicon Radio         | 1         | 3.23%   |
| Broadcom                        | 1         | 3.23%   |
| ASUSTek Computer                | 1         | 3.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                   | 6         | 19.35%  |
| Foxconn / Hon Hai Bluetooth Device                   | 5         | 16.13%  |
| Lite-On Atheros AR3012 Bluetooth                     | 4         | 12.9%   |
| Qualcomm Atheros  Bluetooth Device                   | 2         | 6.45%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                | 2         | 6.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)       | 2         | 6.45%   |
| Apple Bluetooth USB Host Controller                  | 2         | 6.45%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter              | 1         | 3.23%   |
| Realtek RTL8723B Bluetooth                           | 1         | 3.23%   |
| Qualcomm Atheros Dell Wireless 1802 Bluetooth 4.0 LE | 1         | 3.23%   |
| Intel Centrino Bluetooth Wireless Transceiver        | 1         | 3.23%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)  | 1         | 3.23%   |
| Broadcom HP Portable Valentine                       | 1         | 3.23%   |
| ASUS Broadcom BCM20702A0 Bluetooth                   | 1         | 3.23%   |
| Apple Bluetooth Host Controller                      | 1         | 3.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Intel    | 34        | 79.07%  |
| AMD      | 3         | 6.98%   |
| Nvidia   | 2         | 4.65%   |
| XMOS     | 1         | 2.33%   |
| Shure    | 1         | 2.33%   |
| M-Audio  | 1         | 2.33%   |
| Logitech | 1         | 2.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 11        | 20.75%  |
| Intel Comet Lake PCH-LP cAVS                                               | 7         | 13.21%  |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 7.55%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 7.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 5.66%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 5.66%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 3.77%   |
| XMOS xCORE USB Audio 2.0                                                   | 1         | 1.89%   |
| Shure MV5                                                                  | 1         | 1.89%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 1.89%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.89%   |
| M-Audio M-Audio Fast Track MKII                                            | 1         | 1.89%   |
| Logitech Headset H340                                                      | 1         | 1.89%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 1.89%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 1.89%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.89%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.89%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1.89%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 1.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 1.89%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 1.89%   |
| AMD Trinity HDMI Audio Controller                                          | 1         | 1.89%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.89%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 1.89%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.89%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1         | 1.89%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 4         | 26.67%  |
| Crucial             | 4         | 26.67%  |
| SK hynix            | 3         | 20%     |
| Unknown             | 2         | 13.33%  |
| Toshiba             | 1         | 6.67%   |
| Ramaxel Technology  | 1         | 6.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s     | 2         | 11.76%  |
| Crucial RAM CT16G4SFD824A.M16FRS 16GB SODIMM DDR4 2400MT/s | 2         | 11.76%  |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                | 1         | 5.88%   |
| Unknown RAM Module 16384MB 2133MT/s                        | 1         | 5.88%   |
| Toshiba RAM 8HTF12864HDY-800G1 2048MB SODIMM 1066MT/s      | 1         | 5.88%   |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 1066MT/s       | 1         | 5.88%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s  | 1         | 5.88%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s     | 1         | 5.88%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 1         | 5.88%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s     | 1         | 5.88%   |
| Samsung RAM Module 4GB SODIMM LPDDR3 1867MT/s              | 1         | 5.88%   |
| Samsung RAM K4A8G165WC-BCTD 4GB SODIMM DDR4 2667MT/s       | 1         | 5.88%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s    | 1         | 5.88%   |
| Crucial RAM CT4G4SFS8213.C8FBD1 4GB SODIMM DDR4 2133MT/s   | 1         | 5.88%   |
| Crucial RAM CT16G4S24AM.M16FE 16GB SODIMM DDR4 2400MT/s    | 1         | 5.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 8         | 57.14%  |
| DDR3    | 3         | 21.43%  |
| LPDDR3  | 1         | 7.14%   |
| DDR2    | 1         | 7.14%   |
| Unknown | 1         | 7.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SODIMM  | 13        | 92.86%  |
| Unknown | 1         | 7.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 6         | 37.5%   |
| 16384 | 4         | 25%     |
| 8192  | 4         | 25%     |
| 32768 | 2         | 12.5%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 5         | 33.33%  |
| 2400  | 3         | 20%     |
| 1600  | 3         | 20%     |
| 2133  | 2         | 13.33%  |
| 1867  | 1         | 6.67%   |
| 1066  | 1         | 6.67%   |

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
| Realtek Semiconductor                  | 6         | 18.75%  |
| Bison Electronics                      | 5         | 15.63%  |
| Alcor Micro                            | 4         | 12.5%   |
| Sunplus Innovation Technology          | 3         | 9.38%   |
| Chicony Electronics                    | 3         | 9.38%   |
| Apple                                  | 3         | 9.38%   |
| Silicon Motion                         | 1         | 3.13%   |
| Quanta                                 | 1         | 3.13%   |
| Microdia                               | 1         | 3.13%   |
| Lite-On Technology                     | 1         | 3.13%   |
| IMC Networks                           | 1         | 3.13%   |
| Google                                 | 1         | 3.13%   |
| Genesys Logic                          | 1         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Alcor Micro HD WebCam                                                      | 3         | 9.09%   |
| Realtek USB Camera                                                         | 2         | 6.06%   |
| Chicony HD User Facing                                                     | 2         | 6.06%   |
| Bison SunplusIT INC. Integrated Camera                                     | 2         | 6.06%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 2         | 6.06%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 3.03%   |
| Sunplus Integrated Camera                                                  | 1         | 3.03%   |
| Sunplus HD WebCam                                                          | 1         | 3.03%   |
| Silicon Motion WebCam SC-13HDL12131N                                       | 1         | 3.03%   |
| Realtek Lenovo EasyCamera                                                  | 1         | 3.03%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 3.03%   |
| Realtek Integrated Webcam                                                  | 1         | 3.03%   |
| Realtek HP Truevision HD                                                   | 1         | 3.03%   |
| Quanta HD Camera                                                           | 1         | 3.03%   |
| Microdia HP Integrated Webcam                                              | 1         | 3.03%   |
| Lite-On Integrated Camera                                                  | 1         | 3.03%   |
| IMC Networks Lenovo EasyCamera                                             | 1         | 3.03%   |
| Genesys Logic Camera                                                       | 1         | 3.03%   |
| Chicony USB2.0 UVC WebCam                                                  | 1         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 1         | 3.03%   |
| Bison SunplusIT Integrated Camera                                          | 1         | 3.03%   |
| Bison Lenovo EasyCamera                                                    | 1         | 3.03%   |
| Bison BisonCam, NB Pro                                                     | 1         | 3.03%   |
| Apple iBridge                                                              | 1         | 3.03%   |
| Apple Built-in iSight                                                      | 1         | 3.03%   |
| Alcor Micro HP Webcam-101                                                  | 1         | 3.03%   |
| Unknown                                                                    | 1         | 3.03%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 4         | 50%     |
| LighTuning Technology | 2         | 25%     |
| Synaptics             | 1         | 12.5%   |
| STMicroelectronics    | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor     | 3         | 37.5%   |
| Validity Sensors VFS5011 Fingerprint Reader      | 1         | 12.5%   |
| Synaptics Metallica MOH Touch Fingerprint Reader | 1         | 12.5%   |
| STMicroelectronics Fingerprint Reader            | 1         | 12.5%   |
| LighTuning ES603 Swipe Fingerprint Sensor        | 1         | 12.5%   |
| LighTuning EgisTec Touch Fingerprint Sensor      | 1         | 12.5%   |

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
| 0     | 18        | 43.9%   |
| 1     | 17        | 41.46%  |
| 2     | 3         | 7.32%   |
| 3     | 2         | 4.88%   |
| 4     | 1         | 2.44%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 8         | 25%     |
| Fingerprint reader    | 8         | 25%     |
| Bluetooth             | 6         | 18.75%  |
| Graphics card         | 4         | 12.5%   |
| Multimedia controller | 3         | 9.38%   |
| Chipcard              | 2         | 6.25%   |
| Camera                | 1         | 3.13%   |

