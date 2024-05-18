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

Total: 62

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Purism        | Librem 15 v3                | [e43654a7ca](https://linux-hardware.org/?probe=e43654a7ca) | Mar 20, 2024 |
| Purism        | librem_13v2                 | [e338abd505](https://linux-hardware.org/?probe=e338abd505) | Mar 15, 2024 |
| Apple         | MacBook5,1                  | [258dc80f87](https://linux-hardware.org/?probe=258dc80f87) | Feb 11, 2024 |
| Apple         | MacBook5,1                  | [3fb985c33d](https://linux-hardware.org/?probe=3fb985c33d) | Jan 21, 2024 |
| Purism        | Librem 14                   | [215d922345](https://linux-hardware.org/?probe=215d922345) | Dec 28, 2023 |
| Purism        | Librem 13 v4                | [0fdc9f6ef8](https://linux-hardware.org/?probe=0fdc9f6ef8) | Nov 23, 2023 |
| Purism        | Librem 13 v4                | [83c0da5aab](https://linux-hardware.org/?probe=83c0da5aab) | Nov 23, 2023 |
| Lenovo        | ThinkPad P50 20ENCTO1WW     | [80851b7836](https://linux-hardware.org/?probe=80851b7836) | Aug 27, 2023 |
| Lenovo        | G450 2949                   | [a8ec62d51f](https://linux-hardware.org/?probe=a8ec62d51f) | Aug 21, 2023 |
| Lenovo        | G450 2949                   | [64d2950d7a](https://linux-hardware.org/?probe=64d2950d7a) | Aug 21, 2023 |
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
| PureOS 10   | 16        | 34.04%  |
| PureOS 10.0 | 15        | 31.91%  |
| PureOS 9.0  | 9         | 19.15%  |
| PureOS 8    | 3         | 6.38%   |
| PureOS 9    | 2         | 4.26%   |
| PureOS 10.x | 2         | 4.26%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| PureOS | 45        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Notebooks | Percent |
|----------------------------------|-----------|---------|
| 4.19.0-5-amd64                   | 9         | 18.37%  |
| 5.10.0-13-amd64                  | 5         | 10.2%   |
| 5.10.0-14-amd64                  | 4         | 8.16%   |
| 5.10.0-8-amd64                   | 3         | 6.12%   |
| 5.10.0-23-amd64                  | 3         | 6.12%   |
| 5.10.0-21-amd64                  | 3         | 6.12%   |
| 5.10.0-7-amd64                   | 2         | 4.08%   |
| 5.10.0-28-amd64                  | 2         | 4.08%   |
| 5.10.0-26-amd64                  | 2         | 4.08%   |
| 5.10.0-11-amd64                  | 2         | 4.08%   |
| 6.1.0-1-librem5                  | 1         | 2.04%   |
| 5.7.0-1-librem5                  | 1         | 2.04%   |
| 5.7.0-0.38-1-pinebookpro-hwaccel | 1         | 2.04%   |
| 5.15.0-2-amd64                   | 1         | 2.04%   |
| 5.10.0-9-amd64                   | 1         | 2.04%   |
| 5.10.0-6-amd64                   | 1         | 2.04%   |
| 5.10.0-27-amd64                  | 1         | 2.04%   |
| 5.10.0-25-amd64                  | 1         | 2.04%   |
| 5.10.0-19-amd64                  | 1         | 2.04%   |
| 5.10.0-18-amd64                  | 1         | 2.04%   |
| 5.10.0-17-amd64                  | 1         | 2.04%   |
| 5.10.0-12-amd64                  | 1         | 2.04%   |
| 4.19.0-14-amd64                  | 1         | 2.04%   |
| 4.16.0-1-amd64                   | 1         | 2.04%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 31        | 67.39%  |
| 4.19.0  | 10        | 21.74%  |
| 5.7.0   | 2         | 4.35%   |
| 6.1.0   | 1         | 2.17%   |
| 5.15.0  | 1         | 2.17%   |
| 4.16.0  | 1         | 2.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 31        | 67.39%  |
| 4.19    | 10        | 21.74%  |
| 5.7     | 2         | 4.35%   |
| 6.1     | 1         | 2.17%   |
| 5.15    | 1         | 2.17%   |
| 4.16    | 1         | 2.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 42        | 93.33%  |
| aarch64 | 3         | 6.67%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 38        | 82.61%  |
| Unknown         | 4         | 8.7%    |
| KDE5            | 2         | 4.35%   |
| MATE            | 1         | 2.17%   |
| GNOME Flashback | 1         | 2.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 35        | 74.47%  |
| X11     | 6         | 12.77%  |
| Unknown | 4         | 8.51%   |
| Tty     | 2         | 4.26%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 26        | 57.78%  |
| GDM     | 14        | 31.11%  |
| GDM3    | 5         | 11.11%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 22        | 46.81%  |
| en_GB   | 4         | 8.51%   |
| Unknown | 4         | 8.51%   |
| pl_PL   | 3         | 6.38%   |
| de_DE   | 3         | 6.38%   |
| C       | 2         | 4.26%   |
| zh_CN   | 1         | 2.13%   |
| ru_RU   | 1         | 2.13%   |
| pt_PT   | 1         | 2.13%   |
| it_IT   | 1         | 2.13%   |
| fr_FR   | 1         | 2.13%   |
| es_CR   | 1         | 2.13%   |
| es_AR   | 1         | 2.13%   |
| en_IL   | 1         | 2.13%   |
| en_AU   | 1         | 2.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 40        | 88.89%  |
| EFI  | 5         | 11.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 40        | 88.89%  |
| Unknown | 2         | 4.44%   |
| Overlay | 1         | 2.22%   |
| Ext2    | 1         | 2.22%   |
| Btrfs   | 1         | 2.22%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 27        | 60%     |
| MBR     | 12        | 26.67%  |
| GPT     | 6         | 13.33%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 37        | 82.22%  |
| Yes       | 8         | 17.78%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 42        | 93.33%  |
| Yes       | 3         | 6.67%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Purism              | 15        | 33.33%  |
| Lenovo              | 9         | 20%     |
| Apple               | 5         | 11.11%  |
| Dell                | 4         | 8.89%   |
| Hewlett-Packard     | 3         | 6.67%   |
| Acer                | 2         | 4.44%   |
| Toshiba             | 1         | 2.22%   |
| Samsung Electronics | 1         | 2.22%   |
| Pine Microsystems   | 1         | 2.22%   |
| Notebook            | 1         | 2.22%   |
| HUAWEI              | 1         | 2.22%   |
| Google              | 1         | 2.22%   |
| Unknown             | 1         | 2.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Purism Librem 14                      | 6         | 13.33%  |
| Purism Librem 15 v4                   | 2         | 4.44%   |
| Purism Librem 15 v3                   | 2         | 4.44%   |
| Purism Librem 13 v4                   | 2         | 4.44%   |
| HP Pavilion g6                        | 2         | 4.44%   |
| Toshiba Satellite L500D               | 1         | 2.22%   |
| Samsung 530U3C/530U4C/532U3C          | 1         | 2.22%   |
| Purism librem_13v2                    | 1         | 2.22%   |
| Purism Librem 5r4                     | 1         | 2.22%   |
| Purism Librem 13 v2                   | 1         | 2.22%   |
| Pine Microsystems Pine64 Pinebook Pro | 1         | 2.22%   |
| Notebook P17SM                        | 1         | 2.22%   |
| Lenovo ThinkPad T540p 20BFS23T00      | 1         | 2.22%   |
| Lenovo ThinkPad T440p                 | 1         | 2.22%   |
| Lenovo ThinkPad T440 20B60044RT       | 1         | 2.22%   |
| Lenovo ThinkPad P50 20ENCTO1WW        | 1         | 2.22%   |
| Lenovo ThinkPad E480 20KN003SUS       | 1         | 2.22%   |
| Lenovo ThinkPad 13 2nd Gen 20J2S00G00 | 1         | 2.22%   |
| Lenovo IdeaPad U430 Touch 20270       | 1         | 2.22%   |
| Lenovo G450 2949                      | 1         | 2.22%   |
| Lenovo B50-70 20384                   | 1         | 2.22%   |
| HUAWEI NBLB-WAX9N                     | 1         | 2.22%   |
| HP Pavilion Notebook                  | 1         | 2.22%   |
| Google Droid                          | 1         | 2.22%   |
| Dell XPS 13 9370                      | 1         | 2.22%   |
| Dell Latitude D430                    | 1         | 2.22%   |
| Dell Inspiron 5547                    | 1         | 2.22%   |
| Dell Inspiron 15-3567                 | 1         | 2.22%   |
| Apple MacBookPro6,1                   | 1         | 2.22%   |
| Apple MacBookPro14,2                  | 1         | 2.22%   |
| Apple MacBookAir7,2                   | 1         | 2.22%   |
| Apple MacBook9,1                      | 1         | 2.22%   |
| Apple MacBook5,1                      | 1         | 2.22%   |
| Acer Swift SF113-31                   | 1         | 2.22%   |
| Acer Nitro AN515-43                   | 1         | 2.22%   |
| Unknown                               | 1         | 2.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Purism Librem            | 15        | 33.33%  |
| Lenovo ThinkPad          | 6         | 13.33%  |
| HP Pavilion              | 3         | 6.67%   |
| Dell Inspiron            | 2         | 4.44%   |
| Toshiba Satellite        | 1         | 2.22%   |
| Samsung 530U3C           | 1         | 2.22%   |
| Pine Microsystems Pine64 | 1         | 2.22%   |
| Notebook P17SM           | 1         | 2.22%   |
| Lenovo IdeaPad           | 1         | 2.22%   |
| Lenovo G450              | 1         | 2.22%   |
| Lenovo B50-70            | 1         | 2.22%   |
| HUAWEI NBLB-WAX9N        | 1         | 2.22%   |
| Google Droid             | 1         | 2.22%   |
| Dell XPS                 | 1         | 2.22%   |
| Dell Latitude            | 1         | 2.22%   |
| Apple MacBookPro6        | 1         | 2.22%   |
| Apple MacBookPro14       | 1         | 2.22%   |
| Apple MacBookAir7        | 1         | 2.22%   |
| Apple MacBook9           | 1         | 2.22%   |
| Apple MacBook5           | 1         | 2.22%   |
| Acer Swift               | 1         | 2.22%   |
| Acer Nitro               | 1         | 2.22%   |
| Unknown                  | 1         | 2.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 6         | 13.33%  |
| 2017    | 6         | 13.33%  |
| 2019    | 5         | 11.11%  |
| Unknown | 5         | 11.11%  |
| 2013    | 4         | 8.89%   |
| 2020    | 3         | 6.67%   |
| 2009    | 3         | 6.67%   |
| 2018    | 2         | 4.44%   |
| 2015    | 2         | 4.44%   |
| 2014    | 2         | 4.44%   |
| 2011    | 2         | 4.44%   |
| 2007    | 2         | 4.44%   |
| 2023    | 1         | 2.22%   |
| 2016    | 1         | 2.22%   |
| 2012    | 1         | 2.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 45        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 45        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 29        | 64.44%  |
| Yes  | 16        | 35.56%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 11        | 24.44%  |
| 16.01-24.0  | 11        | 24.44%  |
| 32.01-64.0  | 7         | 15.56%  |
| 3.01-4.0    | 6         | 13.33%  |
| 8.01-16.0   | 5         | 11.11%  |
| 1.01-2.0    | 2         | 4.44%   |
| 24.01-32.0  | 1         | 2.22%   |
| 2.01-3.0    | 1         | 2.22%   |
| 64.01-256.0 | 1         | 2.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 15        | 30.61%  |
| 3.01-4.0  | 12        | 24.49%  |
| 1.01-2.0  | 11        | 22.45%  |
| 4.01-8.0  | 8         | 16.33%  |
| 8.01-16.0 | 3         | 6.12%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 31        | 68.89%  |
| 2      | 12        | 26.67%  |
| 0      | 2         | 4.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 35        | 77.78%  |
| Yes       | 10        | 22.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 75.56%  |
| No        | 11        | 24.44%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 41        | 91.11%  |
| No        | 4         | 8.89%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 35        | 77.78%  |
| No        | 10        | 22.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Notebooks | Percent |
|------------------------|-----------|---------|
| USA                    | 10        | 21.28%  |
| UK                     | 5         | 10.64%  |
| Germany                | 5         | 10.64%  |
| Canada                 | 3         | 6.38%   |
| Brazil                 | 3         | 6.38%   |
| Poland                 | 2         | 4.26%   |
| Italy                  | 2         | 4.26%   |
| France                 | 2         | 4.26%   |
| Australia              | 2         | 4.26%   |
| Turkey                 | 1         | 2.13%   |
| South Africa           | 1         | 2.13%   |
| Serbia                 | 1         | 2.13%   |
| Russia                 | 1         | 2.13%   |
| Portugal               | 1         | 2.13%   |
| Paraguay               | 1         | 2.13%   |
| Pakistan               | 1         | 2.13%   |
| Israel                 | 1         | 2.13%   |
| Iran                   | 1         | 2.13%   |
| Costa Rica             | 1         | 2.13%   |
| China                  | 1         | 2.13%   |
| Bosnia and Herzegovina | 1         | 2.13%   |
| Argentina              | 1         | 2.13%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| London            | 2         | 4.17%   |
| Windsor           | 1         | 2.08%   |
| Warsaw            | 1         | 2.08%   |
| Vancouver         | 1         | 2.08%   |
| Thorpe Hamlet     | 1         | 2.08%   |
| Tel Aviv          | 1         | 2.08%   |
| Stuttgart         | 1         | 2.08%   |
| Stargard          | 1         | 2.08%   |
| Spencer           | 1         | 2.08%   |
| Seattle           | 1         | 2.08%   |
| Sao Paulo         | 1         | 2.08%   |
| San Jose          | 1         | 2.08%   |
| Plano             | 1         | 2.08%   |
| Paris             | 1         | 2.08%   |
| New York          | 1         | 2.08%   |
| Montreal          | 1         | 2.08%   |
| Milwaukee         | 1         | 2.08%   |
| Milpitas          | 1         | 2.08%   |
| Melbourne         | 1         | 2.08%   |
| Mankato           | 1         | 2.08%   |
| Lambeth           | 1         | 2.08%   |
| Krasnogorsk       | 1         | 2.08%   |
| Karachi           | 1         | 2.08%   |
| Ituzaingo         | 1         | 2.08%   |
| Istanbul          | 1         | 2.08%   |
| Hernandarias      | 1         | 2.08%   |
| Guimaraes         | 1         | 2.08%   |
| Grasse            | 1         | 2.08%   |
| Genoa             | 1         | 2.08%   |
| Eberswalde        | 1         | 2.08%   |
| Cape Town         | 1         | 2.08%   |
| Camden            | 1         | 2.08%   |
| Brandenburg       | 1         | 2.08%   |
| Braganca Paulista | 1         | 2.08%   |
| Bowdoin Center    | 1         | 2.08%   |
| Blumenau          | 1         | 2.08%   |
| Big Sky           | 1         | 2.08%   |
| Berlin            | 1         | 2.08%   |
| Belgrade          | 1         | 2.08%   |
| Banja Luka        | 1         | 2.08%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 18        | 24     | 33.96%  |
| Unknown             | 4         | 4      | 7.55%   |
| Seagate             | 3         | 3      | 5.66%   |
| SanDisk             | 3         | 3      | 5.66%   |
| HGST                | 3         | 3      | 5.66%   |
| Crucial             | 3         | 5      | 5.66%   |
| Apple               | 3         | 5      | 5.66%   |
| WDC                 | 2         | 2      | 3.77%   |
| A-DATA Technology   | 2         | 2      | 3.77%   |
| Transcend           | 1         | 1      | 1.89%   |
| Toshiba             | 1         | 1      | 1.89%   |
| Qumo                | 1         | 1      | 1.89%   |
| Plextor             | 1         | 1      | 1.89%   |
| Phison              | 1         | 1      | 1.89%   |
| Mushkin             | 1         | 1      | 1.89%   |
| Kingston            | 1         | 2      | 1.89%   |
| JMicron Technology  | 1         | 1      | 1.89%   |
| Intel               | 1         | 1      | 1.89%   |
| Hitachi             | 1         | 1      | 1.89%   |
| BIWIN               | 1         | 1      | 1.89%   |
| ADATA Technology    | 1         | 1      | 1.89%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Unknown MMC Card  64GB                             | 2         | 3.64%   |
| Seagate ST1000LM048-2E7172 1TB                     | 2         | 3.64%   |
| Samsung SSD 970 PRO 1TB                            | 2         | 3.64%   |
| Samsung SSD 860 EVO 500GB                          | 2         | 3.64%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 2         | 3.64%   |
| Crucial CT250MX500SSD4 250GB                       | 2         | 3.64%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                   | 1         | 1.82%   |
| WDC WDS100T2B0C-00PXH0 1TB                         | 1         | 1.82%   |
| Unknown MMC Card  32GB                             | 1         | 1.82%   |
| Unknown DA4128  128GB                              | 1         | 1.82%   |
| Transcend TS240GMTS420S 240GB SSD                  | 1         | 1.82%   |
| Toshiba NVMe SSD Drive 512GB                       | 1         | 1.82%   |
| Seagate NVMe SSD Drive 2TB                         | 1         | 1.82%   |
| SanDisk SSD i100 24GB                              | 1         | 1.82%   |
| SanDisk SDSSDP128G 128GB                           | 1         | 1.82%   |
| SanDisk SDSSDH3500G 500GB                          | 1         | 1.82%   |
| Samsung SSD 970 EVO Plus 500GB                     | 1         | 1.82%   |
| Samsung SSD 970 EVO Plus 2TB                       | 1         | 1.82%   |
| Samsung SSD 970 EVO 250GB                          | 1         | 1.82%   |
| Samsung SSD 960 EVO 500GB                          | 1         | 1.82%   |
| Samsung SSD 960 EVO 250GB                          | 1         | 1.82%   |
| Samsung SSD 860 EVO 250GB                          | 1         | 1.82%   |
| Samsung SSD 860 EVO 1TB                            | 1         | 1.82%   |
| Samsung SSD 850 EVO 500GB                          | 1         | 1.82%   |
| Samsung SSD 850 EVO 250GB                          | 1         | 1.82%   |
| Samsung NVMe SSD Drive 1TB                         | 1         | 1.82%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 1         | 1.82%   |
| Samsung HS08XJC 80GB                               | 1         | 1.82%   |
| Samsung HM321HI 320GB                              | 1         | 1.82%   |
| Qumo SSD 120GB                                     | 1         | 1.82%   |
| Plextor PX-1TM6Pro 1024GB SSD                      | 1         | 1.82%   |
| Phison PM8512GPTCB4B8TF-E13T4 512GB                | 1         | 1.82%   |
| Mushkin MKNSSDRE250GB-LT                           | 1         | 1.82%   |
| Kingston SVP200S360G 64GB SSD                      | 1         | 1.82%   |
| JMicron Generic 320GB                              | 1         | 1.82%   |
| Intel SSDSC2BF180A4H 180GB                         | 1         | 1.82%   |
| Hitachi HTS545050A7E380 500GB                      | 1         | 1.82%   |
| HGST HTS721010A9E630 1TB                           | 1         | 1.82%   |
| HGST HTS545050B7E660 500GB                         | 1         | 1.82%   |
| HGST HTS541010A9E680 1TB                           | 1         | 1.82%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 3         | 3      | 33.33%  |
| Seagate             | 2         | 2      | 22.22%  |
| Samsung Electronics | 2         | 2      | 22.22%  |
| JMicron Technology  | 1         | 1      | 11.11%  |
| Hitachi             | 1         | 1      | 11.11%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 9      | 29.17%  |
| SanDisk             | 3         | 3      | 12.5%   |
| Crucial             | 3         | 5      | 12.5%   |
| A-DATA Technology   | 2         | 2      | 8.33%   |
| WDC                 | 1         | 1      | 4.17%   |
| Transcend           | 1         | 1      | 4.17%   |
| Qumo                | 1         | 1      | 4.17%   |
| Plextor             | 1         | 1      | 4.17%   |
| Mushkin             | 1         | 1      | 4.17%   |
| Kingston            | 1         | 2      | 4.17%   |
| Intel               | 1         | 1      | 4.17%   |
| BIWIN               | 1         | 1      | 4.17%   |
| Apple               | 1         | 1      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 21        | 29     | 41.18%  |
| NVMe | 17        | 22     | 33.33%  |
| HDD  | 9         | 9      | 17.65%  |
| MMC  | 4         | 4      | 7.84%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 26        | 36     | 53.06%  |
| NVMe | 17        | 22     | 34.69%  |
| MMC  | 4         | 4      | 8.16%   |
| SAS  | 2         | 2      | 4.08%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 21        | 30     | 75%     |
| 0.51-1.0   | 5         | 5      | 17.86%  |
| 1.01-2.0   | 2         | 3      | 7.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 22        | 48.89%  |
| 101-250    | 6         | 13.33%  |
| 251-500    | 3         | 6.67%   |
| 21-50      | 3         | 6.67%   |
| 51-100     | 3         | 6.67%   |
| Unknown    | 3         | 6.67%   |
| 1001-2000  | 2         | 4.44%   |
| 501-1000   | 2         | 4.44%   |
| 2001-3000  | 1         | 2.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 32        | 71.11%  |
| 21-50    | 5         | 11.11%  |
| 501-1000 | 3         | 6.67%   |
| Unknown  | 3         | 6.67%   |
| 251-500  | 1         | 2.22%   |
| 51-100   | 1         | 2.22%   |

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
| Detected | 29        | 43     | 64.44%  |
| Works    | 15        | 20     | 33.33%  |
| Malfunc  | 1         | 1      | 2.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 26        | 54.17%  |
| Samsung Electronics          | 11        | 22.92%  |
| AMD                          | 3         | 6.25%   |
| Apple                        | 2         | 4.17%   |
| Toshiba America Info Systems | 1         | 2.08%   |
| Seagate Technology           | 1         | 2.08%   |
| SanDisk                      | 1         | 2.08%   |
| Phison Electronics           | 1         | 2.08%   |
| Nvidia                       | 1         | 2.08%   |
| ADATA Technology             | 1         | 2.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 10        | 20.83%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7         | 14.58%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 6.25%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 6.25%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 4.17%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 4.17%   |
| Apple S3X NVMe Controller                                                      | 2         | 4.17%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 2         | 4.17%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 2.08%   |
| Seagate FireCuda/IronWolf 510 SSD                                              | 1         | 2.08%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                     | 1         | 2.08%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 1         | 2.08%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 2.08%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 1         | 2.08%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 2.08%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 2.08%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 2.08%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 2.08%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 2.08%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 2.08%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 2.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 2.08%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 2.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 2.08%   |
| ADATA IM2P33F3 NVMe SSD (DRAM-less)                                            | 1         | 2.08%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 30        | 62.5%   |
| NVMe | 17        | 35.42%  |
| IDE  | 1         | 2.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 40        | 88.89%  |
| ARM     | 2         | 4.44%   |
| AMD     | 2         | 4.44%   |
| Unknown | 1         | 2.22%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10710U CPU @ 1.10GHz            | 6         | 13.33%  |
| Intel Core i7-7500U CPU @ 2.70GHz             | 5         | 11.11%  |
| Intel Core i7-6500U CPU @ 2.50GHz             | 4         | 8.89%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 4.44%   |
| ARM Processor                                 | 2         | 4.44%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 2.22%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 2.22%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 2.22%   |
| Intel Core m5-6Y54 CPU @ 1.10GHz              | 1         | 2.22%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 2.22%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 2.22%   |
| Intel Core i7-7567U CPU @ 3.50GHz             | 1         | 2.22%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 2.22%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz            | 1         | 2.22%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 1         | 2.22%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 2.22%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 2.22%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 1         | 2.22%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 2.22%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 2.22%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 2.22%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 1         | 2.22%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 1         | 2.22%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 2.22%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 1         | 2.22%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 1         | 2.22%   |
| Intel Core 2 Duo CPU U7700 @ 1.33GHz          | 1         | 2.22%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz          | 1         | 2.22%   |
| AMD Turion II Dual-Core Mobile M520           | 1         | 2.22%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 1         | 2.22%   |
|                                               | 1         | 2.22%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 23        | 51.11%  |
| Intel Core i5           | 7         | 15.56%  |
| Intel Core i3           | 4         | 8.89%   |
| Other                   | 3         | 6.67%   |
| Intel Core 2 Duo        | 2         | 4.44%   |
| Intel Pentium Silver    | 1         | 2.22%   |
| Intel Pentium Dual-Core | 1         | 2.22%   |
| Intel Pentium           | 1         | 2.22%   |
| Intel Core m5           | 1         | 2.22%   |
| AMD Turion II Dual-Core | 1         | 2.22%   |
| AMD Ryzen 5             | 1         | 2.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 26        | 57.78%  |
| 4      | 13        | 28.89%  |
| 6      | 6         | 13.33%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 45        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 36        | 80%     |
| 1      | 9         | 20%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 43        | 93.48%  |
| Unknown        | 3         | 6.52%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 68.89%  |
| 0x406e3    | 4         | 8.89%   |
| 0xa0660    | 3         | 6.67%   |
| 0x806e9    | 2         | 4.44%   |
| 0x40651    | 2         | 4.44%   |
| 0x806ec    | 1         | 2.22%   |
| 0x1067a    | 1         | 2.22%   |
| 0x08108109 | 1         | 2.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 11        | 24.44%  |
| Haswell       | 7         | 15.56%  |
| Skylake       | 6         | 13.33%  |
| CometLake     | 6         | 13.33%  |
| Unknown       | 3         | 6.67%   |
| Penryn        | 2         | 4.44%   |
| IvyBridge     | 2         | 4.44%   |
| Zen+          | 1         | 2.22%   |
| Westmere      | 1         | 2.22%   |
| SandyBridge   | 1         | 2.22%   |
| K10           | 1         | 2.22%   |
| Goldmont plus | 1         | 2.22%   |
| Goldmont      | 1         | 2.22%   |
| Core          | 1         | 2.22%   |
| Broadwell     | 1         | 2.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 38        | 77.55%  |
| Nvidia | 6         | 12.24%  |
| AMD    | 5         | 10.2%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                 | 7         | 13.46%  |
| Intel Comet Lake UHD Graphics                                                         | 6         | 11.54%  |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 4         | 7.69%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 4         | 7.69%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 3         | 5.77%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 2         | 3.85%   |
| Nvidia GT216M [GeForce GT 330M]                                                       | 1         | 1.92%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 1         | 1.92%   |
| Nvidia GM107GLM [Quadro M2000M]                                                       | 1         | 1.92%   |
| Nvidia GK208M [GeForce GT 730M]                                                       | 1         | 1.92%   |
| Nvidia GK104M [GeForce GTX 870M]                                                      | 1         | 1.92%   |
| Nvidia C79 [GeForce 9400M]                                                            | 1         | 1.92%   |
| Intel UHD Graphics 620                                                                | 1         | 1.92%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller         | 1         | 1.92%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller             | 1         | 1.92%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 1         | 1.92%   |
| Intel Iris Plus Graphics 650                                                          | 1         | 1.92%   |
| Intel HD Graphics 630                                                                 | 1         | 1.92%   |
| Intel HD Graphics 6000                                                                | 1         | 1.92%   |
| Intel HD Graphics 515                                                                 | 1         | 1.92%   |
| Intel GeminiLake [UHD Graphics 605]                                                   | 1         | 1.92%   |
| Intel Core Processor Integrated Graphics Controller                                   | 1         | 1.92%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 1         | 1.92%   |
| Intel Apollo Lake [HD Graphics 505]                                                   | 1         | 1.92%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 1         | 1.92%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 1.92%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                             | 1         | 1.92%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                             | 1         | 1.92%   |
| AMD Richland [Radeon HD 8550G]                                                        | 1         | 1.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 1         | 1.92%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520/610 Mobile]                      | 1         | 1.92%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                   | 1         | 1.92%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 31        | 68.89%  |
| Other          | 4         | 8.89%   |
| Intel + Nvidia | 4         | 8.89%   |
| 1 x Nvidia     | 2         | 4.44%   |
| Intel + AMD    | 2         | 4.44%   |
| 2 x AMD        | 1         | 2.22%   |
| 1 x AMD        | 1         | 2.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 41        | 91.11%  |
| Unknown | 4         | 8.89%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 44        | 97.78%  |
| 3.01-4.0   | 1         | 2.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 11        | 20.75%  |
| LG Display              | 8         | 15.09%  |
| Chimei Innolux          | 8         | 15.09%  |
| Samsung Electronics     | 6         | 11.32%  |
| Apple                   | 5         | 9.43%   |
| Unknown                 | 2         | 3.77%   |
| AU Optronics            | 2         | 3.77%   |
| Toshiba                 | 1         | 1.89%   |
| Sharp                   | 1         | 1.89%   |
| PANDA                   | 1         | 1.89%   |
| Lenovo                  | 1         | 1.89%   |
| Iiyama                  | 1         | 1.89%   |
| Grundig                 | 1         | 1.89%   |
| Goldstar                | 1         | 1.89%   |
| Chi Mei Optoelectronics | 1         | 1.89%   |
| BenQ                    | 1         | 1.89%   |
| ASUSTek Computer        | 1         | 1.89%   |
| Acer                    | 1         | 1.89%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC434B 3840x2160 344x194mm 15.5-inch     | 3         | 5.66%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 3         | 5.66%   |
| BOE LCD Monitor BOE06BE 1920x1080 294x165mm 13.3-inch                     | 3         | 5.66%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 2         | 3.77%   |
| Chimei Innolux LCD Monitor CMN1415 1920x1080 309x173mm 13.9-inch          | 2         | 3.77%   |
| Toshiba LCD Monitor LCD3706 1280x800 261x163mm 12.1-inch                  | 1         | 1.89%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                   | 1         | 1.89%   |
| Samsung Electronics LS27A800U SAM71A3 3840x2160 597x336mm 27.0-inch       | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch      | 1         | 1.89%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 1         | 1.89%   |
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch                   | 1         | 1.89%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch              | 1         | 1.89%   |
| LG Display LCD Monitor LGD053B 1920x1080 294x165mm 13.3-inch              | 1         | 1.89%   |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch              | 1         | 1.89%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch              | 1         | 1.89%   |
| LG Display LCD Monitor LGD03F0 1366x768 310x174mm 14.0-inch               | 1         | 1.89%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch               | 1         | 1.89%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch               | 1         | 1.89%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch               | 1         | 1.89%   |
| Lenovo LEN Y44w-10 LEN65EA 3840x1200 1052x329mm 43.4-inch                 | 1         | 1.89%   |
| Iiyama PL2792H IVM664F 1920x1080 598x336mm 27.0-inch                      | 1         | 1.89%   |
| Grundig WXGA GRU4448 1600x1200                                            | 1         | 1.89%   |
| Goldstar IPS231 GSM5817 1920x1080 510x290mm 23.1-inch                     | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch          | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN15BD 1366x768 344x193mm 15.5-inch           | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch           | 1         | 1.89%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 1.89%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                     | 1         | 1.89%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                     | 1         | 1.89%   |
| BOE LCD Monitor BOE079A 1920x1080 309x173mm 13.9-inch                     | 1         | 1.89%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                      | 1         | 1.89%   |
| BOE LCD Monitor BOE06C2 1366x768 344x194mm 15.5-inch                      | 1         | 1.89%   |
| BOE LCD Monitor BOE0641 1920x1080 344x193mm 15.5-inch                     | 1         | 1.89%   |
| BOE LCD Monitor BOE0630 1920x1080 344x194mm 15.5-inch                     | 1         | 1.89%   |
| BOE LCD Monitor BOE0586 1366x768 309x173mm 13.9-inch                      | 1         | 1.89%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                         | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO713C 1366x768 309x173mm 13.9-inch             | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO10ED 1920x1080 344x193mm 15.5-inch            | 1         | 1.89%   |
| ASUSTek Computer VP249 AUS24AF 1920x1080 527x296mm 23.8-inch              | 1         | 1.89%   |
| Apple LCD Monitor APP9C8C 1280x800 286x179mm 13.3-inch                    | 1         | 1.89%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 22        | 44.9%   |
| 1366x768 (WXGA)   | 10        | 20.41%  |
| 3840x2160 (4K)    | 7         | 14.29%  |
| 2288x1287         | 2         | 4.08%   |
| 1280x800 (WXGA)   | 2         | 4.08%   |
| 3840x1200         | 1         | 2.04%   |
| 2880x1800         | 1         | 2.04%   |
| 2304x1440         | 1         | 2.04%   |
| 1920x1200 (WUXGA) | 1         | 2.04%   |
| 1600x900 (HD+)    | 1         | 2.04%   |
| 1440x900 (WXGA+)  | 1         | 2.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 19        | 35.85%  |
| 15     | 16        | 30.19%  |
| 14     | 3         | 5.66%   |
| 142    | 2         | 3.77%   |
| 27     | 2         | 3.77%   |
| 24     | 2         | 3.77%   |
| 23     | 2         | 3.77%   |
| 17     | 2         | 3.77%   |
| 12     | 2         | 3.77%   |
| 54     | 1         | 1.89%   |
| 43     | 1         | 1.89%   |
| 40     | 1         | 1.89%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 27        | 51.92%  |
| 201-300        | 11        | 21.15%  |
| 501-600        | 6         | 11.54%  |
| 351-400        | 3         | 5.77%   |
| More than 2000 | 2         | 3.85%   |
| 1001-1500      | 2         | 3.85%   |
| 801-900        | 1         | 1.92%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 35        | 79.55%  |
| 16/10 | 6         | 13.64%  |
| 1.00  | 2         | 4.55%   |
| 3.20  | 1         | 2.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 16        | 30.19%  |
| 81-90          | 15        | 28.3%   |
| 71-80          | 7         | 13.21%  |
| 201-250        | 4         | 7.55%   |
| More than 1000 | 3         | 5.66%   |
| 61-70          | 2         | 3.77%   |
| 301-350        | 2         | 3.77%   |
| 501-1000       | 2         | 3.77%   |
| 131-140        | 1         | 1.89%   |
| 121-130        | 1         | 1.89%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 19        | 35.85%  |
| 51-100        | 10        | 18.87%  |
| 101-120       | 9         | 16.98%  |
| 161-240       | 7         | 13.21%  |
| More than 240 | 6         | 11.32%  |
| 1-50          | 2         | 3.77%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 33        | 73.33%  |
| 2     | 8         | 17.78%  |
| 0     | 3         | 6.67%   |
| 3     | 1         | 2.22%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 24        | 31.58%  |
| Qualcomm Atheros                | 18        | 23.68%  |
| Intel                           | 13        | 17.11%  |
| Broadcom                        | 7         | 9.21%   |
| Broadcom Limited                | 3         | 3.95%   |
| ASIX Electronics                | 3         | 3.95%   |
| Ralink                          | 1         | 1.32%   |
| Qualcomm Atheros Communications | 1         | 1.32%   |
| OPPO Electronics                | 1         | 1.32%   |
| Nvidia                          | 1         | 1.32%   |
| MediaTek                        | 1         | 1.32%   |
| Google                          | 1         | 1.32%   |
| DisplayLink                     | 1         | 1.32%   |
| D-Link                          | 1         | 1.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 14        | 16.09%  |
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 13        | 14.94%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 5         | 5.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 3         | 3.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 3         | 3.45%   |
| Intel Wireless 7265                                                           | 3         | 3.45%   |
| Intel Wireless 7260                                                           | 3         | 3.45%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 3         | 3.45%   |
| Intel Ethernet Connection I217-LM                                             | 2         | 2.3%    |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter          | 2         | 2.3%    |
| Realtek USB 10/100/1G/2.5G LAN                                                | 1         | 1.15%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1         | 1.15%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 1.15%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 1         | 1.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1         | 1.15%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 1.15%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1         | 1.15%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                        | 1         | 1.15%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                        | 1         | 1.15%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 1.15%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.15%   |
| OPPO SM8350-MTP _SN:9338D66C                                                  | 1         | 1.15%   |
| Nvidia MCP79 Ethernet                                                         | 1         | 1.15%   |
| MediaTek WiFi                                                                 | 1         | 1.15%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 1.15%   |
| Intel Wireless 8260                                                           | 1         | 1.15%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 1         | 1.15%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1         | 1.15%   |
| Intel Ethernet Connection I218-V                                              | 1         | 1.15%   |
| Intel Ethernet Connection (4) I219-V                                          | 1         | 1.15%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1         | 1.15%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 1         | 1.15%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 1.15%   |
| Google Nexus/Pixel Device (tether)                                            | 1         | 1.15%   |
| DisplayLink DL-Dock                                                           | 1         | 1.15%   |
| D-Link 802.11ac NIC                                                           | 1         | 1.15%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1         | 1.15%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                       | 1         | 1.15%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                           | 1         | 1.15%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                        | 1         | 1.15%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 18        | 36.73%  |
| Intel                           | 12        | 24.49%  |
| Realtek Semiconductor           | 6         | 12.24%  |
| Broadcom                        | 6         | 12.24%  |
| Broadcom Limited                | 3         | 6.12%   |
| Ralink                          | 1         | 2.04%   |
| Qualcomm Atheros Communications | 1         | 2.04%   |
| MediaTek                        | 1         | 2.04%   |
| D-Link                          | 1         | 2.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 14        | 28.57%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 3         | 6.12%   |
| Intel Wireless 7265                                                           | 3         | 6.12%   |
| Intel Wireless 7260                                                           | 3         | 6.12%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter          | 2         | 4.08%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1         | 2.04%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 2.04%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 1         | 2.04%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1         | 2.04%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 2.04%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1         | 2.04%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                        | 1         | 2.04%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 2.04%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 2.04%   |
| MediaTek WiFi                                                                 | 1         | 2.04%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 2.04%   |
| Intel Wireless 8260                                                           | 1         | 2.04%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 1         | 2.04%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1         | 2.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 1         | 2.04%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 2.04%   |
| D-Link 802.11ac NIC                                                           | 1         | 2.04%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                        | 1         | 2.04%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 1         | 2.04%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                            | 1         | 2.04%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 1         | 2.04%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                        | 1         | 2.04%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 1         | 2.04%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 1         | 2.04%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 21        | 56.76%  |
| Intel                 | 5         | 13.51%  |
| Broadcom              | 3         | 8.11%   |
| ASIX Electronics      | 3         | 8.11%   |
| Qualcomm Atheros      | 1         | 2.7%    |
| OPPO Electronics      | 1         | 2.7%    |
| Nvidia                | 1         | 2.7%    |
| Google                | 1         | 2.7%    |
| DisplayLink           | 1         | 2.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 13        | 34.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 5         | 13.16%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3         | 7.89%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 7.89%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 5.26%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 1         | 2.63%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 2.63%   |
| OPPO SM8350-MTP _SN:9338D66C                                           | 1         | 2.63%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 2.63%   |
| Intel Ethernet Connection I218-V                                       | 1         | 2.63%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 2.63%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 2.63%   |
| Google Nexus/Pixel Device (tether)                                     | 1         | 2.63%   |
| DisplayLink DL-Dock                                                    | 1         | 2.63%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 1         | 2.63%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 1         | 2.63%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 1         | 2.63%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 42        | 56%     |
| Ethernet | 33        | 44%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 23        | 52.27%  |
| WiFi     | 21        | 47.73%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 26        | 57.78%  |
| 1     | 14        | 31.11%  |
| 0     | 4         | 8.89%   |
| 3     | 1         | 2.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 35        | 76.09%  |
| Yes  | 11        | 23.91%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 11        | 30.56%  |
| Lite-On Technology              | 6         | 16.67%  |
| Qualcomm Atheros Communications | 5         | 13.89%  |
| Foxconn / Hon Hai               | 5         | 13.89%  |
| Apple                           | 4         | 11.11%  |
| Realtek Semiconductor           | 2         | 5.56%   |
| Cambridge Silicon Radio         | 1         | 2.78%   |
| Broadcom                        | 1         | 2.78%   |
| ASUSTek Computer                | 1         | 2.78%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Lite-On Atheros AR3012 Bluetooth                     | 6         | 16.67%  |
| Intel Bluetooth wireless interface                   | 5         | 13.89%  |
| Foxconn / Hon Hai Bluetooth Device                   | 5         | 13.89%  |
| Apple Bluetooth Host Controller                      | 3         | 8.33%   |
| Qualcomm Atheros  Bluetooth Device                   | 2         | 5.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                | 2         | 5.56%   |
| Intel Bluetooth Device                               | 2         | 5.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)       | 2         | 5.56%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter              | 1         | 2.78%   |
| Realtek RTL8723B Bluetooth                           | 1         | 2.78%   |
| Qualcomm Atheros Dell Wireless 1802 Bluetooth 4.0 LE | 1         | 2.78%   |
| Intel Wireless-AC 9260 Bluetooth Adapter             | 1         | 2.78%   |
| Intel Centrino Bluetooth Wireless Transceiver        | 1         | 2.78%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)  | 1         | 2.78%   |
| Broadcom HP Portable Valentine                       | 1         | 2.78%   |
| ASUS Broadcom BCM20702A0 Bluetooth                   | 1         | 2.78%   |
| Apple Bluetooth USB Host Controller                  | 1         | 2.78%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor    | Notebooks | Percent |
|-----------|-----------|---------|
| Intel     | 39        | 76.47%  |
| Nvidia    | 4         | 7.84%   |
| AMD       | 3         | 5.88%   |
| XMOS      | 1         | 1.96%   |
| Shure     | 1         | 1.96%   |
| M-Audio   | 1         | 1.96%   |
| Logitech  | 1         | 1.96%   |
| GN Netcom | 1         | 1.96%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 14        | 22.95%  |
| Intel Comet Lake PCH-LP cAVS                                               | 7         | 11.48%  |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 6.56%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 6.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 4.92%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 4.92%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 3.28%   |
| XMOS xCORE USB Audio 2.0                                                   | 1         | 1.64%   |
| Shure MV5                                                                  | 1         | 1.64%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 1.64%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 1.64%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.64%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 1.64%   |
| M-Audio M-Audio Fast Track MKII                                            | 1         | 1.64%   |
| Logitech Headset H340                                                      | 1         | 1.64%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 1.64%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 1.64%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.64%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.64%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1.64%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 1.64%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.64%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 1.64%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 1.64%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.64%   |
| GN Netcom Jabra Link 380                                                   | 1         | 1.64%   |
| AMD Trinity HDMI Audio Controller                                          | 1         | 1.64%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.64%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 1.64%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.64%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1         | 1.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 5         | 27.78%  |
| Crucial             | 4         | 22.22%  |
| SK hynix            | 3         | 16.67%  |
| Unknown             | 2         | 11.11%  |
| Toshiba             | 1         | 5.56%   |
| Ramaxel Technology  | 1         | 5.56%   |
| Micron Technology   | 1         | 5.56%   |
| Elpida              | 1         | 5.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s     | 3         | 15%     |
| Crucial RAM CT16G4SFD824A.M16FRS 16GB SODIMM DDR4 2400MT/s | 2         | 10%     |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                | 1         | 5%      |
| Unknown RAM Module 16384MB 2133MT/s                        | 1         | 5%      |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s         | 1         | 5%      |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 1066MT/s       | 1         | 5%      |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s     | 1         | 5%      |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s     | 1         | 5%      |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 1         | 5%      |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s     | 1         | 5%      |
| Samsung RAM Module 4GB SODIMM LPDDR3 1867MT/s              | 1         | 5%      |
| Samsung RAM K4A8G165WC-BCTD 4GB SODIMM DDR4 2667MT/s       | 1         | 5%      |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s    | 1         | 5%      |
| Micron RAM 16ATF2G64HZ-2G3B1 16GB SODIMM DDR4 2400MT/s     | 1         | 5%      |
| Elpida RAM EBJ21UE8BDS0-AE-F 2GB SODIMM DDR3 1067MT/s      | 1         | 5%      |
| Crucial RAM CT4G4SFS8213.C8FBD1 4GB SODIMM DDR4 2133MT/s   | 1         | 5%      |
| Crucial RAM CT16G4S24AM.M16FE 16GB SODIMM DDR4 2400MT/s    | 1         | 5%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 10        | 58.82%  |
| DDR3    | 4         | 23.53%  |
| LPDDR3  | 1         | 5.88%   |
| DDR2    | 1         | 5.88%   |
| Unknown | 1         | 5.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SODIMM  | 16        | 94.12%  |
| Unknown | 1         | 5.88%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 6         | 31.58%  |
| 16384 | 5         | 26.32%  |
| 8192  | 4         | 21.05%  |
| 32768 | 3         | 15.79%  |
| 2048  | 1         | 5.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 6         | 33.33%  |
| 2400  | 4         | 22.22%  |
| 1600  | 3         | 16.67%  |
| 2133  | 2         | 11.11%  |
| 1867  | 1         | 5.56%   |
| 1067  | 1         | 5.56%   |
| 1066  | 1         | 5.56%   |

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
| Realtek Semiconductor                  | 6         | 16.67%  |
| Alcor Micro                            | 5         | 13.89%  |
| Chicony Electronics                    | 4         | 11.11%  |
| Apple                                  | 4         | 11.11%  |
| Acer                                   | 4         | 11.11%  |
| Sunplus Innovation Technology          | 3         | 8.33%   |
| Suyin                                  | 1         | 2.78%   |
| Silicon Motion                         | 1         | 2.78%   |
| Quanta                                 | 1         | 2.78%   |
| Microdia                               | 1         | 2.78%   |
| Lite-On Technology                     | 1         | 2.78%   |
| IMC Networks                           | 1         | 2.78%   |
| Google                                 | 1         | 2.78%   |
| Genesys Logic                          | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.78%   |
| Bison Electronics                      | 1         | 2.78%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Alcor Micro HD WebCam                                                      | 4         | 10.81%  |
| Realtek USB Camera                                                         | 2         | 5.41%   |
| Chicony HD User Facing                                                     | 2         | 5.41%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 2         | 5.41%   |
| Apple Built-in iSight                                                      | 2         | 5.41%   |
| Acer Integrated Camera                                                     | 2         | 5.41%   |
| Suyin HP Integrated Webcam                                                 | 1         | 2.7%    |
| Sunplus Integrated_Webcam_HD                                               | 1         | 2.7%    |
| Sunplus Integrated Camera                                                  | 1         | 2.7%    |
| Sunplus HD WebCam                                                          | 1         | 2.7%    |
| Silicon Motion WebCam SC-13HDL12131N                                       | 1         | 2.7%    |
| Realtek Lenovo EasyCamera                                                  | 1         | 2.7%    |
| Realtek Integrated_Webcam_HD                                               | 1         | 2.7%    |
| Realtek Integrated Webcam                                                  | 1         | 2.7%    |
| Realtek HP Truevision HD                                                   | 1         | 2.7%    |
| Quanta HD Camera                                                           | 1         | 2.7%    |
| Microdia HP Integrated Webcam                                              | 1         | 2.7%    |
| Lite-On Integrated Camera                                                  | 1         | 2.7%    |
| IMC Networks Lenovo EasyCamera                                             | 1         | 2.7%    |
| Genesys Logic Camera                                                       | 1         | 2.7%    |
| Chicony USB2.0 UVC WebCam                                                  | 1         | 2.7%    |
| Chicony Integrated Camera                                                  | 1         | 2.7%    |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 1         | 2.7%    |
| Bison SunplusIT Integrated Camera                                          | 1         | 2.7%    |
| Apple iBridge                                                              | 1         | 2.7%    |
| Alcor Micro HP Webcam-101                                                  | 1         | 2.7%    |
| Acer Lenovo EasyCamera                                                     | 1         | 2.7%    |
| Acer BisonCam, NB Pro                                                      | 1         | 2.7%    |
| Unknown                                                                    | 1         | 2.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 5         | 55.56%  |
| LighTuning Technology | 2         | 22.22%  |
| Synaptics             | 1         | 11.11%  |
| STMicroelectronics    | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor      | 3         | 33.33%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 11.11%  |
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 11.11%  |
| Synaptics Metallica MOH Touch Fingerprint Reader  | 1         | 11.11%  |
| STMicroelectronics Fingerprint Reader             | 1         | 11.11%  |
| LighTuning ES603 Swipe Fingerprint Sensor         | 1         | 11.11%  |
| LighTuning EgisTec Touch Fingerprint Sensor       | 1         | 11.11%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Purism, SPC               | 3         | 37.5%   |
| Realtek Semiconductor     | 1         | 12.5%   |
| O2 Micro                  | 1         | 12.5%   |
| Clay Logic                | 1         | 12.5%   |
| Alcor Micro               | 1         | 12.5%   |
| Aladdin Knowledge Systems | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Purism, SPC Librem Key                            | 3         | 37.5%   |
| Realtek Semiconductor Smart Card Reader Interface | 1         | 12.5%   |
| O2 Micro Oz776 SmartCard Reader                   | 1         | 12.5%   |
| Clay Logic Nitrokey Pro                           | 1         | 12.5%   |
| Alcor Micro AU9540 Smartcard Reader               | 1         | 12.5%   |
| Aladdin Knowledge Systems Token JC                | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 22        | 46.81%  |
| 1     | 18        | 38.3%   |
| 2     | 4         | 8.51%   |
| 3     | 2         | 4.26%   |
| 4     | 1         | 2.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 10        | 27.78%  |
| Fingerprint reader    | 9         | 25%     |
| Bluetooth             | 7         | 19.44%  |
| Graphics card         | 4         | 11.11%  |
| Multimedia controller | 3         | 8.33%   |
| Chipcard              | 2         | 5.56%   |
| Camera                | 1         | 2.78%   |

