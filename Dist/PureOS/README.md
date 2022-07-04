PureOS - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for PureOS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/PureOS/Desktop/README.md) and [notebooks](/Dist/PureOS/Notebook/README.md).

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

Total: 56

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Purism        | Librem 14                   | Notebook    | [89d920a7d2](https://linux-hardware.org/?probe=89d920a7d2) | Jun 11, 2022 |
| Apple         | MacBookPro6,1               | Notebook    | [40d33cea3f](https://linux-hardware.org/?probe=40d33cea3f) | May 23, 2022 |
| Purism        | Librem 14                   | Notebook    | [9d078217f1](https://linux-hardware.org/?probe=9d078217f1) | Apr 23, 2022 |
| HP            | Pavilion g6                 | Notebook    | [796bf7f467](https://linux-hardware.org/?probe=796bf7f467) | Apr 23, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [8cbc7d1caf](https://linux-hardware.org/?probe=8cbc7d1caf) | Apr 20, 2022 |
| Purism        | Librem 15 v4                | Notebook    | [061aeeecf7](https://linux-hardware.org/?probe=061aeeecf7) | Apr 13, 2022 |
| Lenovo        | ThinkPad T440p              | Notebook    | [45a1ee6fbf](https://linux-hardware.org/?probe=45a1ee6fbf) | Apr 12, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [c0dd92f23c](https://linux-hardware.org/?probe=c0dd92f23c) | Apr 03, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [e1386a38c7](https://linux-hardware.org/?probe=e1386a38c7) | Mar 20, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [c8723d2dd9](https://linux-hardware.org/?probe=c8723d2dd9) | Feb 21, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [45529bb469](https://linux-hardware.org/?probe=45529bb469) | Feb 21, 2022 |
| Lenovo        | ThinkPad T540p 20BFS23T0... | Notebook    | [c49acb0edf](https://linux-hardware.org/?probe=c49acb0edf) | Feb 21, 2022 |
| Lenovo        | ThinkPad T540p 20BFS23T0... | Notebook    | [6f13abc9eb](https://linux-hardware.org/?probe=6f13abc9eb) | Feb 21, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [1f5badca6e](https://linux-hardware.org/?probe=1f5badca6e) | Feb 06, 2022 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [5b34840f92](https://linux-hardware.org/?probe=5b34840f92) | Feb 04, 2022 |
| HP            | Spectre x360 Convertible    | Convertible | [8812b5d4fd](https://linux-hardware.org/?probe=8812b5d4fd) | Dec 03, 2021 |
| Dell          | 088DT1 A01                  | Desktop     | [6800234271](https://linux-hardware.org/?probe=6800234271) | Dec 02, 2021 |
| Dell          | 088DT1 A01                  | Desktop     | [9190925dba](https://linux-hardware.org/?probe=9190925dba) | Nov 26, 2021 |
| Lenovo        | ThinkPad E480 20KN003SUS    | Notebook    | [ad043b077a](https://linux-hardware.org/?probe=ad043b077a) | Nov 25, 2021 |
| Apple         | MacBookPro14,2              | Notebook    | [5f4d435f0d](https://linux-hardware.org/?probe=5f4d435f0d) | Nov 24, 2021 |
| Dell          | 088DT1 A01                  | Desktop     | [93a177ddce](https://linux-hardware.org/?probe=93a177ddce) | Nov 02, 2021 |
| Dell          | 088DT1 A01                  | Desktop     | [4917dcd8b3](https://linux-hardware.org/?probe=4917dcd8b3) | Nov 02, 2021 |
| ASUSTek       | A88X-PLUS/USB               | Desktop     | [ad21355553](https://linux-hardware.org/?probe=ad21355553) | Sep 27, 2021 |
| Purism        | Librem 14                   | Notebook    | [68e8f5b427](https://linux-hardware.org/?probe=68e8f5b427) | Sep 27, 2021 |
| HP            | Spectre x360 Convertible    | Convertible | [e1dfe46f2f](https://linux-hardware.org/?probe=e1dfe46f2f) | Aug 31, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | Notebook    | [077ff209de](https://linux-hardware.org/?probe=077ff209de) | Aug 18, 2021 |
| HP            | Spectre x360 Convertible    | Convertible | [a746c422c5](https://linux-hardware.org/?probe=a746c422c5) | Aug 14, 2021 |
| HP            | Spectre x360 Convertible    | Convertible | [cd8b8b47eb](https://linux-hardware.org/?probe=cd8b8b47eb) | Aug 14, 2021 |
| Gigabyte      | B85M-DS3H                   | Desktop     | [840cb54d82](https://linux-hardware.org/?probe=840cb54d82) | Jul 25, 2021 |
| Purism        | Librem 14                   | Notebook    | [295a2a1392](https://linux-hardware.org/?probe=295a2a1392) | Jul 15, 2021 |
| Purism        | Librem 14                   | Notebook    | [49d9b561c6](https://linux-hardware.org/?probe=49d9b561c6) | Jul 15, 2021 |
| Toshiba       | Satellite L500D             | Notebook    | [b830927060](https://linux-hardware.org/?probe=b830927060) | Jul 04, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [c8937f439d](https://linux-hardware.org/?probe=c8937f439d) | Jun 09, 2021 |
| Purism        | Librem 14                   | Notebook    | [0c18b37b73](https://linux-hardware.org/?probe=0c18b37b73) | Jun 01, 2021 |
| ASUSTek       | A88X-PLUS/USB               | Desktop     | [99e83e8dcf](https://linux-hardware.org/?probe=99e83e8dcf) | Mar 08, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [34fda13b24](https://linux-hardware.org/?probe=34fda13b24) | Nov 22, 2020 |
| Unknown       | Unknown                     | Soc         | [02f65d4d20](https://linux-hardware.org/?probe=02f65d4d20) | Oct 28, 2020 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [3bc62d47a9](https://linux-hardware.org/?probe=3bc62d47a9) | Oct 28, 2020 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [79c01fbf3a](https://linux-hardware.org/?probe=79c01fbf3a) | Oct 28, 2020 |
| Unknown       | Unknown                     | Notebook    | [c24817ee80](https://linux-hardware.org/?probe=c24817ee80) | Sep 15, 2020 |
| Purism        | Librem 5                    | Soc         | [2c6b84a04f](https://linux-hardware.org/?probe=2c6b84a04f) | Jul 23, 2020 |
| HP            | Pavilion g6                 | Notebook    | [eb23d17143](https://linux-hardware.org/?probe=eb23d17143) | Jul 15, 2020 |
| Lenovo        | ThinkPad T440 20B60044RT    | Notebook    | [db8ba33d45](https://linux-hardware.org/?probe=db8ba33d45) | Jun 02, 2020 |
| Purism        | Librem 15 v4                | Notebook    | [d9f38d66c3](https://linux-hardware.org/?probe=d9f38d66c3) | Apr 29, 2020 |
| Notebook      | P17SM                       | Notebook    | [730c65e65d](https://linux-hardware.org/?probe=730c65e65d) | Apr 22, 2020 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [542ee658b9](https://linux-hardware.org/?probe=542ee658b9) | Apr 17, 2020 |
| Purism        | Librem 15 v4                | Notebook    | [6e5f1119b7](https://linux-hardware.org/?probe=6e5f1119b7) | Apr 10, 2020 |
| Purism        | Librem 15 v3                | Notebook    | [a43311f999](https://linux-hardware.org/?probe=a43311f999) | Dec 18, 2019 |
| Purism        | Librem 13 v4                | Notebook    | [6d7a537e86](https://linux-hardware.org/?probe=6d7a537e86) | Nov 15, 2019 |
| Dell          | Inspiron 5547               | Notebook    | [689dfea547](https://linux-hardware.org/?probe=689dfea547) | Oct 25, 2019 |
| Purism        | Librem 13 v4                | Notebook    | [6d7c18d329](https://linux-hardware.org/?probe=6d7c18d329) | Oct 18, 2019 |
| Lenovo        | G505s 20255                 | Notebook    | [bce345b263](https://linux-hardware.org/?probe=bce345b263) | Aug 30, 2019 |
| ASUSTek       | Z97-A                       | Desktop     | [e6b1f9af05](https://linux-hardware.org/?probe=e6b1f9af05) | Aug 15, 2019 |
| ASUSTek       | Z97-A                       | Desktop     | [c8a97966c9](https://linux-hardware.org/?probe=c8a97966c9) | Aug 14, 2019 |
| Purism        | Librem 13 v2                | Notebook    | [3e70a8dff1](https://linux-hardware.org/?probe=3e70a8dff1) | Jul 13, 2019 |
| Purism        | Librem 15 v3                | Notebook    | [02e23b6024](https://linux-hardware.org/?probe=02e23b6024) | May 21, 2018 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| PureOS 9.0  | 12        | 31.58%  |
| PureOS 10.0 | 11        | 28.95%  |
| PureOS 10   | 10        | 26.32%  |
| PureOS 9    | 3         | 7.89%   |
| PureOS 8    | 2         | 5.26%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| PureOS | 37        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                          | Computers | Percent |
|----------------------------------|-----------|---------|
| 4.19.0-5-amd64                   | 9         | 21.95%  |
| 5.10.0-13-amd64                  | 5         | 12.2%   |
| 5.10.0-8-amd64                   | 4         | 9.76%   |
| 4.19.0-14-amd64                  | 4         | 9.76%   |
| 5.10.0-11-amd64                  | 3         | 7.32%   |
| 5.7.0-1-librem5                  | 2         | 4.88%   |
| 5.10.0-9-amd64                   | 2         | 4.88%   |
| 5.10.0-7-amd64                   | 2         | 4.88%   |
| 5.10.0-14-amd64                  | 2         | 4.88%   |
| 5.9-sunxi64                      | 1         | 2.44%   |
| 5.8-sunxi64                      | 1         | 2.44%   |
| 5.7.0-0.38-1-pinebookpro-hwaccel | 1         | 2.44%   |
| 5.15.0-2-amd64                   | 1         | 2.44%   |
| 5.10.0-6-amd64                   | 1         | 2.44%   |
| 5.10.0-12-amd64                  | 1         | 2.44%   |
| 4.19.72-imx8-sr                  | 1         | 2.44%   |
| 4.16.0-1-amd64                   | 1         | 2.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 18        | 46.15%  |
| 4.19.0  | 13        | 33.33%  |
| 5.7.0   | 3         | 7.69%   |
| 5.9     | 1         | 2.56%   |
| 5.8     | 1         | 2.56%   |
| 5.15.0  | 1         | 2.56%   |
| 4.19.72 | 1         | 2.56%   |
| 4.16.0  | 1         | 2.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 18        | 47.37%  |
| 4.19    | 14        | 36.84%  |
| 5.7     | 3         | 7.89%   |
| 5.15    | 1         | 2.63%   |
| 5       | 1         | 2.63%   |
| 4.16    | 1         | 2.63%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 32        | 86.49%  |
| aarch64 | 5         | 13.51%  |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 31        | 77.5%   |
| Unknown         | 6         | 15%     |
| MATE            | 1         | 2.5%    |
| KDE5            | 1         | 2.5%    |
| GNOME Flashback | 1         | 2.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 26        | 61.9%   |
| X11     | 6         | 14.29%  |
| Unknown | 6         | 14.29%  |
| Tty     | 4         | 9.52%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 24        | 64.86%  |
| GDM     | 10        | 27.03%  |
| GDM3    | 3         | 8.11%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 18        | 45%     |
| de_DE   | 5         | 12.5%   |
| Unknown | 4         | 10%     |
| en_GB   | 3         | 7.5%    |
| ru_RU   | 2         | 5%      |
| zh_CN   | 1         | 2.5%    |
| pt_PT   | 1         | 2.5%    |
| pl_PL   | 1         | 2.5%    |
| it_IT   | 1         | 2.5%    |
| es_CR   | 1         | 2.5%    |
| en_IL   | 1         | 2.5%    |
| en_AU   | 1         | 2.5%    |
| C       | 1         | 2.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 33        | 86.84%  |
| EFI  | 5         | 13.16%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 34        | 91.89%  |
| Unknown | 2         | 5.41%   |
| Ext2    | 1         | 2.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 22        | 56.41%  |
| MBR     | 11        | 28.21%  |
| GPT     | 6         | 15.38%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 30        | 81.08%  |
| Yes       | 7         | 18.92%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 34        | 91.89%  |
| Yes       | 3         | 8.11%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Purism              | 11        | 29.73%  |
| Lenovo              | 5         | 13.51%  |
| Hewlett-Packard     | 4         | 10.81%  |
| Dell                | 4         | 10.81%  |
| Apple               | 4         | 10.81%  |
| Pine Microsystems   | 2         | 5.41%   |
| Unknown             | 2         | 5.41%   |
| Toshiba             | 1         | 2.7%    |
| Notebook            | 1         | 2.7%    |
| Gigabyte Technology | 1         | 2.7%    |
| ASUSTek Computer    | 1         | 2.7%    |
| Acer                | 1         | 2.7%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Purism Librem 14                         | 5         | 13.51%  |
| Purism Librem 15 v4                      | 2         | 5.41%   |
| HP Pavilion g6                           | 2         | 5.41%   |
| Unknown                                  | 2         | 5.41%   |
| Toshiba Satellite L500D                  | 1         | 2.7%    |
| Purism Librem 5                          | 1         | 2.7%    |
| Purism Librem 15 v3                      | 1         | 2.7%    |
| Purism Librem 13 v4                      | 1         | 2.7%    |
| Purism Librem 13 v2                      | 1         | 2.7%    |
| Pine Microsystems Pine64 PinePhone (1.2) | 1         | 2.7%    |
| Pine Microsystems Pine64 Pinebook Pro    | 1         | 2.7%    |
| Notebook P17SM                           | 1         | 2.7%    |
| Lenovo ThinkPad T540p 20BFS23T00         | 1         | 2.7%    |
| Lenovo ThinkPad T440p                    | 1         | 2.7%    |
| Lenovo ThinkPad T440 20B60044RT          | 1         | 2.7%    |
| Lenovo ThinkPad E480 20KN003SUS          | 1         | 2.7%    |
| Lenovo ThinkPad 13 2nd Gen 20J2S00G00    | 1         | 2.7%    |
| HP Spectre x360 Convertible              | 1         | 2.7%    |
| HP Pavilion Notebook                     | 1         | 2.7%    |
| Gigabyte B85M-DS3H                       | 1         | 2.7%    |
| Dell XPS 13 9370                         | 1         | 2.7%    |
| Dell Inspiron 5547                       | 1         | 2.7%    |
| Dell Inspiron 3847                       | 1         | 2.7%    |
| Dell Inspiron 15-3567                    | 1         | 2.7%    |
| ASUS A88X-PLUS/USB                       | 1         | 2.7%    |
| Apple MacBookPro6,1                      | 1         | 2.7%    |
| Apple MacBookPro14,2                     | 1         | 2.7%    |
| Apple iMac7,1                            | 1         | 2.7%    |
| Apple iMac13,1                           | 1         | 2.7%    |
| Acer Nitro AN515-43                      | 1         | 2.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Purism Librem            | 11        | 29.73%  |
| Lenovo ThinkPad          | 5         | 13.51%  |
| HP Pavilion              | 3         | 8.11%   |
| Dell Inspiron            | 3         | 8.11%   |
| Pine Microsystems Pine64 | 2         | 5.41%   |
| Unknown                  | 2         | 5.41%   |
| Toshiba Satellite        | 1         | 2.7%    |
| Notebook P17SM           | 1         | 2.7%    |
| HP Spectre               | 1         | 2.7%    |
| Gigabyte B85M-DS3H       | 1         | 2.7%    |
| Dell XPS                 | 1         | 2.7%    |
| ASUS A88X-PLUS           | 1         | 2.7%    |
| Apple MacBookPro6        | 1         | 2.7%    |
| Apple MacBookPro14       | 1         | 2.7%    |
| Apple iMac7              | 1         | 2.7%    |
| Apple iMac13             | 1         | 2.7%    |
| Acer Nitro               | 1         | 2.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 6         | 16.22%  |
| 2013    | 5         | 13.51%  |
| Unknown | 5         | 13.51%  |
| 2019    | 4         | 10.81%  |
| 2017    | 4         | 10.81%  |
| 2015    | 3         | 8.11%   |
| 2018    | 2         | 5.41%   |
| 2016    | 2         | 5.41%   |
| 2011    | 2         | 5.41%   |
| 2020    | 1         | 2.7%    |
| 2014    | 1         | 2.7%    |
| 2009    | 1         | 2.7%    |
| 2007    | 1         | 2.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 28        | 75.68%  |
| Desktop        | 3         | 8.11%   |
| System on chip | 2         | 5.41%   |
| All in one     | 2         | 5.41%   |
| Phone          | 1         | 2.7%    |
| Convertible    | 1         | 2.7%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 37        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 26        | 70.27%  |
| Yes  | 11        | 29.73%  |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 16.01-24.0 | 9         | 24.32%  |
| 8.01-16.0  | 8         | 21.62%  |
| 32.01-64.0 | 6         | 16.22%  |
| 4.01-8.0   | 5         | 13.51%  |
| 3.01-4.0   | 5         | 13.51%  |
| 2.01-3.0   | 2         | 5.41%   |
| 24.01-32.0 | 1         | 2.7%    |
| 1.01-2.0   | 1         | 2.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 11        | 26.19%  |
| 2.01-3.0  | 10        | 23.81%  |
| 3.01-4.0  | 9         | 21.43%  |
| 4.01-8.0  | 8         | 19.05%  |
| 8.01-16.0 | 2         | 4.76%   |
| 0.51-1.0  | 1         | 2.38%   |
| 0.01-0.5  | 1         | 2.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 25        | 67.57%  |
| 2      | 11        | 29.73%  |
| 5      | 1         | 2.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 27        | 72.97%  |
| Yes       | 10        | 27.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 70.27%  |
| No        | 11        | 29.73%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 86.49%  |
| No        | 5         | 13.51%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 70.27%  |
| No        | 11        | 29.73%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 9         | 23.08%  |
| Germany                | 6         | 15.38%  |
| UK                     | 5         | 12.82%  |
| Canada                 | 3         | 7.69%   |
| Russia                 | 2         | 5.13%   |
| Australia              | 2         | 5.13%   |
| Turkey                 | 1         | 2.56%   |
| South Africa           | 1         | 2.56%   |
| Portugal               | 1         | 2.56%   |
| Poland                 | 1         | 2.56%   |
| Italy                  | 1         | 2.56%   |
| Israel                 | 1         | 2.56%   |
| Iran                   | 1         | 2.56%   |
| France                 | 1         | 2.56%   |
| Costa Rica             | 1         | 2.56%   |
| China                  | 1         | 2.56%   |
| Brazil                 | 1         | 2.56%   |
| Bosnia and Herzegovina | 1         | 2.56%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Stuttgart          | 3         | 7.32%   |
| New York           | 2         | 4.88%   |
| London             | 2         | 4.88%   |
| Yuzhnoural'sk      | 1         | 2.44%   |
| Wixom              | 1         | 2.44%   |
| Windsor            | 1         | 2.44%   |
| Warsaw             | 1         | 2.44%   |
| Vancouver          | 1         | 2.44%   |
| Troy               | 1         | 2.44%   |
| Thorpe Hamlet      | 1         | 2.44%   |
| Tel Aviv           | 1         | 2.44%   |
| Spencer            | 1         | 2.44%   |
| Seattle            | 1         | 2.44%   |
| San Jose           | 1         | 2.44%   |
| Paris              | 1         | 2.44%   |
| Montreal           | 1         | 2.44%   |
| Milwaukee          | 1         | 2.44%   |
| Melbourne          | 1         | 2.44%   |
| Liverpool          | 1         | 2.44%   |
| Leeds              | 1         | 2.44%   |
| Krasnogorsk        | 1         | 2.44%   |
| Istanbul           | 1         | 2.44%   |
| Guimaraes          | 1         | 2.44%   |
| Fort Collins       | 1         | 2.44%   |
| Eberswalde         | 1         | 2.44%   |
| Cape Town          | 1         | 2.44%   |
| Camden             | 1         | 2.44%   |
| Big Sky            | 1         | 2.44%   |
| Berlin             | 1         | 2.44%   |
| Banja Luka         | 1         | 2.44%   |
| Bandar-e Asalūyeh | 1         | 2.44%   |
| Balow              | 1         | 2.44%   |
| Araçatuba         | 1         | 2.44%   |
| Antioch            | 1         | 2.44%   |
| Ankang             | 1         | 2.44%   |
| Almese             | 1         | 2.44%   |
| Adelaide           | 1         | 2.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 15     | 23.4%   |
| Seagate             | 6         | 10     | 12.77%  |
| Unknown             | 5         | 9      | 10.64%  |
| WDC                 | 3         | 4      | 6.38%   |
| HGST                | 3         | 3      | 6.38%   |
| A-DATA Technology   | 3         | 4      | 6.38%   |
| Crucial             | 2         | 4      | 4.26%   |
| Apple               | 2         | 3      | 4.26%   |
| Transcend           | 1         | 1      | 2.13%   |
| Toshiba             | 1         | 1      | 2.13%   |
| SanDisk             | 1         | 1      | 2.13%   |
| Plextor             | 1         | 1      | 2.13%   |
| Phison              | 1         | 1      | 2.13%   |
| Mushkin             | 1         | 1      | 2.13%   |
| JMicron Technology  | 1         | 1      | 2.13%   |
| Intel               | 1         | 1      | 2.13%   |
| Hitachi             | 1         | 1      | 2.13%   |
| BIWIN               | 1         | 1      | 2.13%   |
| ASMT                | 1         | 2      | 2.13%   |
| ADATA Technology    | 1         | 1      | 2.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST1000LM048-2E7172 1TB      | 2         | 3.85%   |
| Samsung SSD 970 PRO 1TB             | 2         | 3.85%   |
| WDC WDS100T2B0C-00PXH0 1TB          | 1         | 1.92%   |
| WDC WDBNCE2500PNC 250GB SSD         | 1         | 1.92%   |
| WDC WD3200AAJS-40RYA0 320GB         | 1         | 1.92%   |
| Unknown SH64G  64GB                 | 1         | 1.92%   |
| Unknown MMC Card  32GB              | 1         | 1.92%   |
| Unknown MMC Card  16GB              | 1         | 1.92%   |
| Unknown DA4128  128GB               | 1         | 1.92%   |
| Unknown AFGCF  128GB                | 1         | 1.92%   |
| Unknown 8GTF4R  8GB                 | 1         | 1.92%   |
| Unknown 032G32  32GB                | 1         | 1.92%   |
| Transcend TS240GMTS420S 240GB SSD   | 1         | 1.92%   |
| Toshiba NVMe SSD Drive 512GB        | 1         | 1.92%   |
| Seagate ST480HM000-1G5162 480GB     | 1         | 1.92%   |
| Seagate ST3320418AS 320GB           | 1         | 1.92%   |
| Seagate ST31000524AS 1TB            | 1         | 1.92%   |
| Seagate ST1000DM003-1ER162 1TB      | 1         | 1.92%   |
| Seagate NVMe SSD Drive 2TB          | 1         | 1.92%   |
| SanDisk SDSSDH3500G 500GB           | 1         | 1.92%   |
| Samsung SSD 970 EVO Plus 500GB      | 1         | 1.92%   |
| Samsung SSD 970 EVO 250GB           | 1         | 1.92%   |
| Samsung SSD 960 EVO 500GB           | 1         | 1.92%   |
| Samsung SSD 960 EVO 250GB           | 1         | 1.92%   |
| Samsung SSD 860 EVO 500GB           | 1         | 1.92%   |
| Samsung SSD 860 EVO 250GB           | 1         | 1.92%   |
| Samsung SSD 860 EVO 1TB             | 1         | 1.92%   |
| Samsung SSD 850 EVO 500GB           | 1         | 1.92%   |
| Samsung SSD 850 EVO 250GB           | 1         | 1.92%   |
| Samsung NVMe SSD Drive 1TB          | 1         | 1.92%   |
| Plextor PX-1TM6Pro 1024GB SSD       | 1         | 1.92%   |
| Phison PM8512GPTCB4B8TF-E13T4 512GB | 1         | 1.92%   |
| Mushkin MKNSSDRE250GB-LT            | 1         | 1.92%   |
| JMicron Generic 2TB                 | 1         | 1.92%   |
| Intel SSDSC2BF180A4H 180GB          | 1         | 1.92%   |
| Hitachi HTS545050A7E380 500GB       | 1         | 1.92%   |
| HGST HTS721010A9E630 1TB            | 1         | 1.92%   |
| HGST HTS545050B7E660 500GB          | 1         | 1.92%   |
| HGST HTS541010A9E680 1TB            | 1         | 1.92%   |
| Crucial CT250MX500SSD4 250GB        | 1         | 1.92%   |
| Crucial CT2000MX500SSD1 2TB         | 1         | 1.92%   |
| BIWIN SSD 120GB                     | 1         | 1.92%   |
| ASMT 2235 240GB                     | 1         | 1.92%   |
| Apple NVMe SSD Drive 8KB            | 1         | 1.92%   |
| Apple NVMe SSD Drive 256GB          | 1         | 1.92%   |
| Apple HDD ST1000LM024 1TB           | 1         | 1.92%   |
| ADATA NVMe SSD Drive 512GB          | 1         | 1.92%   |
| A-DATA SU630 240GB SSD              | 1         | 1.92%   |
| A-DATA IM2S3138E-128GM-B 128GB SSD  | 1         | 1.92%   |
| A-DATA AXNS381E-256GM-B 256GB SSD   | 1         | 1.92%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Computers | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 5         | 9      | 41.67%  |
| HGST               | 3         | 3      | 25%     |
| WDC                | 1         | 1      | 8.33%   |
| JMicron Technology | 1         | 1      | 8.33%   |
| Hitachi            | 1         | 1      | 8.33%   |
| Apple              | 1         | 1      | 8.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 8      | 33.33%  |
| A-DATA Technology   | 3         | 4      | 16.67%  |
| Crucial             | 2         | 4      | 11.11%  |
| WDC                 | 1         | 2      | 5.56%   |
| Transcend           | 1         | 1      | 5.56%   |
| SanDisk             | 1         | 1      | 5.56%   |
| Plextor             | 1         | 1      | 5.56%   |
| Mushkin             | 1         | 1      | 5.56%   |
| Intel               | 1         | 1      | 5.56%   |
| BIWIN               | 1         | 1      | 5.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 16        | 24     | 34.78%  |
| NVMe    | 12        | 14     | 26.09%  |
| HDD     | 12        | 16     | 26.09%  |
| MMC     | 5         | 9      | 10.87%  |
| Unknown | 1         | 2      | 2.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 23        | 38     | 53.49%  |
| NVMe | 12        | 14     | 27.91%  |
| MMC  | 5         | 9      | 11.63%  |
| SAS  | 3         | 4      | 6.98%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 16        | 26     | 59.26%  |
| 0.51-1.0   | 8         | 10     | 29.63%  |
| 1.01-2.0   | 3         | 4      | 11.11%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 15        | 38.46%  |
| 251-500    | 5         | 12.82%  |
| 101-250    | 5         | 12.82%  |
| 21-50      | 3         | 7.69%   |
| 501-1000   | 3         | 7.69%   |
| Unknown    | 3         | 7.69%   |
| 1001-2000  | 2         | 5.13%   |
| 51-100     | 2         | 5.13%   |
| 2001-3000  | 1         | 2.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 21        | 53.85%  |
| 21-50    | 7         | 17.95%  |
| 101-250  | 3         | 7.69%   |
| 501-1000 | 3         | 7.69%   |
| Unknown  | 3         | 7.69%   |
| 251-500  | 1         | 2.56%   |
| 51-100   | 1         | 2.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                      | Computers | Drives | Percent |
|----------------------------|-----------|--------|---------|
| Seagate ST31000524AS 1TB   | 1         | 1      | 33.33%  |
| Intel SSDSC2BF180A4H 180GB | 1         | 1      | 33.33%  |
| Apple HDD ST1000LM024 1TB  | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 33.33%  |
| Intel   | 1         | 1      | 33.33%  |
| Apple   | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| Apple   | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 27        | 48     | 67.5%   |
| Works    | 10        | 14     | 25%     |
| Malfunc  | 3         | 3      | 7.5%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 21        | 58.33%  |
| Samsung Electronics          | 6         | 16.67%  |
| AMD                          | 3         | 8.33%   |
| Toshiba America Info Systems | 1         | 2.78%   |
| Seagate Technology           | 1         | 2.78%   |
| SanDisk                      | 1         | 2.78%   |
| Phison Electronics           | 1         | 2.78%   |
| Apple                        | 1         | 2.78%   |
| ADATA Technology             | 1         | 2.78%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 18.92%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 13.51%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 10.81%  |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 5.41%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 5.41%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 2         | 5.41%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 2.7%    |
| Seagate FireCuda 510 SSD                                                       | 1         | 2.7%    |
| SanDisk Non-Volatile memory controller                                         | 1         | 2.7%    |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 2.7%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 2.7%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 2.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 1         | 2.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 1         | 2.7%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1         | 2.7%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 2.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 2.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 2.7%    |
| Apple S3X NVMe Controller                                                      | 1         | 2.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 2.7%    |
| ADATA Non-Volatile memory controller                                           | 1         | 2.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 23        | 63.89%  |
| NVMe | 12        | 33.33%  |
| IDE  | 1         | 2.78%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 29        | 78.38%  |
| ARM    | 5         | 13.51%  |
| AMD    | 3         | 8.11%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-10710U CPU @ 1.10GHz              | 5         | 13.51%  |
| ARM Processor                                   | 5         | 13.51%  |
| Intel Core i7-7500U CPU @ 2.70GHz               | 4         | 10.81%  |
| Intel Core i7-6500U CPU @ 2.50GHz               | 2         | 5.41%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 5.41%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 1         | 2.7%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 2.7%    |
| Intel Core i7-7567U CPU @ 3.50GHz               | 1         | 2.7%    |
| Intel Core i7-4710MQ CPU @ 2.50GHz              | 1         | 2.7%    |
| Intel Core i7-4702MQ CPU @ 2.20GHz              | 1         | 2.7%    |
| Intel Core i7-4700MQ CPU @ 2.40GHz              | 1         | 2.7%    |
| Intel Core i7-4510U CPU @ 2.00GHz               | 1         | 2.7%    |
| Intel Core i5-5200U CPU @ 2.20GHz               | 1         | 2.7%    |
| Intel Core i5-4460 CPU @ 3.20GHz                | 1         | 2.7%    |
| Intel Core i5-3330S CPU @ 2.70GHz               | 1         | 2.7%    |
| Intel Core i5 CPU M 540 @ 2.53GHz               | 1         | 2.7%    |
| Intel Core i3-4130T CPU @ 2.90GHz               | 1         | 2.7%    |
| Intel Core i3-4010U CPU @ 1.70GHz               | 1         | 2.7%    |
| Intel Core i3-3120M CPU @ 2.50GHz               | 1         | 2.7%    |
| Intel Core i3-2330M CPU @ 2.20GHz               | 1         | 2.7%    |
| Intel Core 2 Duo CPU T7700 @ 2.40GHz            | 1         | 2.7%    |
| AMD Turion II Dual-Core Mobile M520             | 1         | 2.7%    |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx   | 1         | 2.7%    |
| AMD A10-7860K Radeon R7, 12 Compute Cores 4C+8G | 1         | 2.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 18        | 48.65%  |
| Intel Core i5           | 6         | 16.22%  |
| Other                   | 5         | 13.51%  |
| Intel Core i3           | 4         | 10.81%  |
| Intel Core 2 Duo        | 1         | 2.7%    |
| AMD Turion II Dual-Core | 1         | 2.7%    |
| AMD Ryzen 5             | 1         | 2.7%    |
| AMD A10                 | 1         | 2.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 19        | 51.35%  |
| 4      | 13        | 35.14%  |
| 6      | 5         | 13.51%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 37        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 28        | 75.68%  |
| 1      | 9         | 24.32%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 34        | 89.47%  |
| Unknown        | 4         | 10.53%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 29        | 74.36%  |
| 0xa0660    | 3         | 7.69%   |
| 0x406e3    | 2         | 5.13%   |
| 0x806e9    | 1         | 2.56%   |
| 0x40651    | 1         | 2.56%   |
| 0x306d4    | 1         | 2.56%   |
| 0x08108109 | 1         | 2.56%   |
| 0x06003106 | 1         | 2.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 9         | 24.32%  |
| Haswell     | 7         | 18.92%  |
| CometLake   | 5         | 13.51%  |
| Unknown     | 5         | 13.51%  |
| Skylake     | 2         | 5.41%   |
| IvyBridge   | 2         | 5.41%   |
| Zen+        | 1         | 2.7%    |
| Westmere    | 1         | 2.7%    |
| Steamroller | 1         | 2.7%    |
| SandyBridge | 1         | 2.7%    |
| K10         | 1         | 2.7%    |
| Core        | 1         | 2.7%    |
| Broadwell   | 1         | 2.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 26        | 66.67%  |
| Nvidia | 7         | 17.95%  |
| AMD    | 6         | 15.38%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                 | 6         | 14.63%  |
| Intel Comet Lake UHD Graphics                                                         | 5         | 12.2%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 3         | 7.32%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 2         | 4.88%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 2         | 4.88%   |
| Nvidia GT216M [GeForce GT 330M]                                                       | 1         | 2.44%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 1         | 2.44%   |
| Nvidia GK208M [GeForce GT 730M]                                                       | 1         | 2.44%   |
| Nvidia GK208B [GeForce GT 710]                                                        | 1         | 2.44%   |
| Nvidia GK107M [GeForce GT 640M Mac Edition]                                           | 1         | 2.44%   |
| Nvidia GK104M [GeForce GTX 870M]                                                      | 1         | 2.44%   |
| Nvidia GF116 [GeForce GTS 450 Rev. 2]                                                 | 1         | 2.44%   |
| Nvidia GF108 [GeForce GT 630]                                                         | 1         | 2.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 1         | 2.44%   |
| Intel UHD Graphics 620                                                                | 1         | 2.44%   |
| Intel Iris Plus Graphics 650                                                          | 1         | 2.44%   |
| Intel HD Graphics 630                                                                 | 1         | 2.44%   |
| Intel HD Graphics 5500                                                                | 1         | 2.44%   |
| Intel Core Processor Integrated Graphics Controller                                   | 1         | 2.44%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 1         | 2.44%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 1         | 2.44%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 2.44%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                             | 1         | 2.44%   |
| AMD RV630/M76 [Mobility Radeon HD 2600 XT/2700]                                       | 1         | 2.44%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                             | 1         | 2.44%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 1         | 2.44%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                                    | 1         | 2.44%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                   | 1         | 2.44%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 19        | 51.35%  |
| Other          | 5         | 13.51%  |
| Intel + Nvidia | 4         | 10.81%  |
| 1 x Nvidia     | 3         | 8.11%   |
| 1 x AMD        | 3         | 8.11%   |
| Intel + AMD    | 2         | 5.41%   |
| 2 x AMD        | 1         | 2.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 31        | 83.78%  |
| Unknown | 6         | 16.22%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 36        | 94.74%  |
| 3.01-4.0   | 1         | 2.63%   |
| 0.51-1.0   | 1         | 2.63%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 6         | 14.63%  |
| LG Display              | 6         | 14.63%  |
| Chimei Innolux          | 6         | 14.63%  |
| BOE                     | 5         | 12.2%   |
| Apple                   | 4         | 9.76%   |
| AU Optronics            | 2         | 4.88%   |
| Unknown                 | 1         | 2.44%   |
| Sharp                   | 1         | 2.44%   |
| Lenovo                  | 1         | 2.44%   |
| Iiyama                  | 1         | 2.44%   |
| Grundig                 | 1         | 2.44%   |
| Goldstar                | 1         | 2.44%   |
| Dell                    | 1         | 2.44%   |
| Chi Mei Optoelectronics | 1         | 2.44%   |
| BenQ                    | 1         | 2.44%   |
| ASUSTek Computer        | 1         | 2.44%   |
| AOC                     | 1         | 2.44%   |
| Acer                    | 1         | 2.44%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC434B 3840x2160 344x194mm 15.5-inch     | 3         | 7.32%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 3         | 7.32%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 1         | 2.44%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                   | 1         | 2.44%   |
| Samsung Electronics SyncMaster SAM01D3 1440x900 408x225mm 18.3-inch       | 1         | 2.44%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch      | 1         | 2.44%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 1         | 2.44%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch              | 1         | 2.44%   |
| LG Display LCD Monitor LGD053B 1920x1080 294x165mm 13.3-inch              | 1         | 2.44%   |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch              | 1         | 2.44%   |
| LG Display LCD Monitor LGD03F0 1366x768 310x174mm 14.0-inch               | 1         | 2.44%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch               | 1         | 2.44%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch               | 1         | 2.44%   |
| Lenovo LEN Y44w-10 LEN65EA 3840x1200 1052x329mm 43.4-inch                 | 1         | 2.44%   |
| Iiyama PL2792H IVM664F 1920x1080 598x336mm 27.0-inch                      | 1         | 2.44%   |
| Grundig WXGA GRU4448 1600x1200                                            | 1         | 2.44%   |
| Goldstar IPS231 GSM5817 1920x1080 510x290mm 23.1-inch                     | 1         | 2.44%   |
| Dell P2213 DELF042 1680x1050 473x296mm 22.0-inch                          | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch          | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN1415 1920x1080 309x173mm 13.9-inch          | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN1365 1920x1080 293x165mm 13.2-inch          | 1         | 2.44%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 2.44%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                     | 1         | 2.44%   |
| BOE LCD Monitor BOE079A 1920x1080 309x173mm 13.9-inch                     | 1         | 2.44%   |
| BOE LCD Monitor BOE06C2 1366x768 344x194mm 15.5-inch                      | 1         | 2.44%   |
| BOE LCD Monitor BOE06BE 1920x1080 294x165mm 13.3-inch                     | 1         | 2.44%   |
| BOE LCD Monitor BOE0641 1920x1080 344x193mm 15.5-inch                     | 1         | 2.44%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                         | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO713C 1366x768 309x173mm 13.9-inch             | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO10ED 1920x1080 344x193mm 15.5-inch            | 1         | 2.44%   |
| ASUSTek Computer VP249 AUS24AF 1920x1080 527x296mm 23.8-inch              | 1         | 2.44%   |
| Apple iMac APPA012 1920x1080 475x267mm 21.5-inch                          | 1         | 2.44%   |
| Apple Color LCD APPA034 2880x1800 286x179mm 13.3-inch                     | 1         | 2.44%   |
| Apple Color LCD APP9CCF 1920x1200 367x230mm 17.1-inch                     | 1         | 2.44%   |
| Apple Color LCD APP9C6B 1680x1050 433x270mm 20.1-inch                     | 1         | 2.44%   |
| AOC 2050W AOC2050 1600x900 432x240mm 19.5-inch                            | 1         | 2.44%   |
| Acer H236HL ACR0318 1920x1080 509x286mm 23.0-inch                         | 1         | 2.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 17        | 45.95%  |
| 3840x2160 (4K)     | 6         | 16.22%  |
| 1366x768 (WXGA)    | 6         | 16.22%  |
| 1680x1050 (WSXGA+) | 2         | 5.41%   |
| 3840x1200          | 1         | 2.7%    |
| 2880x1800          | 1         | 2.7%    |
| 2288x1287          | 1         | 2.7%    |
| 1920x1200 (WUXGA)  | 1         | 2.7%    |
| 1600x900 (HD+)     | 1         | 2.7%    |
| 1440x900 (WXGA+)   | 1         | 2.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 12        | 29.27%  |
| 13     | 11        | 26.83%  |
| 27     | 2         | 4.88%   |
| 24     | 2         | 4.88%   |
| 23     | 2         | 4.88%   |
| 20     | 2         | 4.88%   |
| 17     | 2         | 4.88%   |
| 14     | 2         | 4.88%   |
| 142    | 1         | 2.44%   |
| 54     | 1         | 2.44%   |
| 43     | 1         | 2.44%   |
| 22     | 1         | 2.44%   |
| 21     | 1         | 2.44%   |
| 19     | 1         | 2.44%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 18        | 45%     |
| 501-600        | 6         | 15%     |
| 401-500        | 5         | 12.5%   |
| 201-300        | 5         | 12.5%   |
| 351-400        | 3         | 7.5%    |
| 1001-1500      | 2         | 5%      |
| More than 2000 | 1         | 2.5%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 26        | 78.79%  |
| 16/10 | 5         | 15.15%  |
| 3.20  | 1         | 3.03%   |
| 1.00  | 1         | 3.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 12        | 29.27%  |
| 81-90          | 8         | 19.51%  |
| 201-250        | 6         | 14.63%  |
| 71-80          | 5         | 12.2%   |
| 151-200        | 3         | 7.32%   |
| More than 1000 | 2         | 4.88%   |
| 301-350        | 2         | 4.88%   |
| 131-140        | 1         | 2.44%   |
| 121-130        | 1         | 2.44%   |
| 501-1000       | 1         | 2.44%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 13        | 31.71%  |
| 121-160       | 12        | 29.27%  |
| More than 240 | 6         | 14.63%  |
| 101-120       | 6         | 14.63%  |
| 161-240       | 3         | 7.32%   |
| 1-50          | 1         | 2.44%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 24        | 64.86%  |
| 2     | 8         | 21.62%  |
| 0     | 4         | 10.81%  |
| 3     | 1         | 2.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 19        | 34.55%  |
| Qualcomm Atheros                | 14        | 25.45%  |
| Intel                           | 7         | 12.73%  |
| Broadcom                        | 5         | 9.09%   |
| Broadcom Limited                | 2         | 3.64%   |
| ASIX Electronics                | 2         | 3.64%   |
| Ralink                          | 1         | 1.82%   |
| Qualcomm Atheros Communications | 1         | 1.82%   |
| MediaTek                        | 1         | 1.82%   |
| Marvell Technology Group        | 1         | 1.82%   |
| Edimax Technology               | 1         | 1.82%   |
| ASUSTek Computer                | 1         | 1.82%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12        | 19.35%  |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 11        | 17.74%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 8.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 4.84%   |
| Intel Wireless 7265                                               | 3         | 4.84%   |
| Intel Wireless 7260                                               | 2         | 3.23%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 3.23%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 3.23%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 1.61%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 1.61%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1         | 1.61%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 1.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.61%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 1         | 1.61%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1         | 1.61%   |
| MediaTek WiFi                                                     | 1         | 1.61%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.61%   |
| Intel Wireless 8265 / 8275                                        | 1         | 1.61%   |
| Intel Ethernet Connection I218-V                                  | 1         | 1.61%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.61%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                       | 1         | 1.61%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.61%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 1.61%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 1         | 1.61%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                            | 1         | 1.61%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1         | 1.61%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 1         | 1.61%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 1         | 1.61%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 1         | 1.61%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]         | 1         | 1.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 14        | 40%     |
| Intel                           | 6         | 17.14%  |
| Realtek Semiconductor           | 4         | 11.43%  |
| Broadcom                        | 4         | 11.43%  |
| Broadcom Limited                | 2         | 5.71%   |
| Ralink                          | 1         | 2.86%   |
| Qualcomm Atheros Communications | 1         | 2.86%   |
| MediaTek                        | 1         | 2.86%   |
| Edimax Technology               | 1         | 2.86%   |
| ASUSTek Computer                | 1         | 2.86%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 11        | 31.43%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 3         | 8.57%   |
| Intel Wireless 7265                                        | 3         | 8.57%   |
| Intel Wireless 7260                                        | 2         | 5.71%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 1         | 2.86%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1         | 2.86%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter    | 1         | 2.86%   |
| Realtek RTL8191SEvB Wireless LAN Controller                | 1         | 2.86%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter     | 1         | 2.86%   |
| Qualcomm Atheros AR9271 802.11n                            | 1         | 2.86%   |
| MediaTek WiFi                                              | 1         | 2.86%   |
| Intel Wireless 8265 / 8275                                 | 1         | 2.86%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                | 1         | 2.86%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter | 1         | 2.86%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                     | 1         | 2.86%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                | 1         | 2.86%   |
| Broadcom BCM43224 802.11a/b/g/n                            | 1         | 2.86%   |
| Broadcom BCM4321 802.11a/b/g/n                             | 1         | 2.86%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter        | 1         | 2.86%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]  | 1         | 2.86%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 17        | 65.38%  |
| Intel                    | 4         | 15.38%  |
| Broadcom                 | 2         | 7.69%   |
| ASIX Electronics         | 2         | 7.69%   |
| Marvell Technology Group | 1         | 3.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12        | 44.44%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 18.52%  |
| Intel Ethernet Connection I217-LM                                 | 2         | 7.41%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 7.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 3.7%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 3.7%    |
| Intel Ethernet Connection I218-V                                  | 1         | 3.7%    |
| Intel Ethernet Connection (4) I219-V                              | 1         | 3.7%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 3.7%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 3.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 31        | 55.36%  |
| Ethernet | 25        | 44.64%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 18        | 56.25%  |
| WiFi     | 14        | 43.75%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 22        | 59.46%  |
| 1     | 9         | 24.32%  |
| 0     | 6         | 16.22%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 32        | 86.49%  |
| Yes  | 5         | 13.51%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros Communications | 5         | 18.52%  |
| Intel                           | 5         | 18.52%  |
| Foxconn / Hon Hai               | 5         | 18.52%  |
| Lite-On Technology              | 4         | 14.81%  |
| Apple                           | 4         | 14.81%  |
| Realtek Semiconductor           | 1         | 3.7%    |
| Cambridge Silicon Radio         | 1         | 3.7%    |
| Broadcom                        | 1         | 3.7%    |
| ASUSTek Computer                | 1         | 3.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 5         | 18.52%  |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 18.52%  |
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 14.81%  |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 7.41%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 7.41%   |
| Apple Bluetooth USB Host Controller                 | 2         | 7.41%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 3.7%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 3.7%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.7%    |
| Broadcom HP Portable Valentine                      | 1         | 3.7%    |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 3.7%    |
| Apple Bluetooth Host Controller                     | 1         | 3.7%    |
| Apple Bluetooth HCI                                 | 1         | 3.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 28        | 66.67%  |
| Nvidia   | 5         | 11.9%   |
| AMD      | 4         | 9.52%   |
| XMOS     | 1         | 2.38%   |
| Shure    | 1         | 2.38%   |
| Micronas | 1         | 2.38%   |
| M-Audio  | 1         | 2.38%   |
| Logitech | 1         | 2.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 10        | 19.61%  |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 9.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 7.84%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 7.84%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 3.92%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 3.92%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 3.92%   |
| XMOS xDuoo USB Audio 2.0                                                   | 1         | 1.96%   |
| Shure MV5                                                                  | 1         | 1.96%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 1.96%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.96%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.96%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 1.96%   |
| Nvidia GF116 High Definition Audio Controller                              | 1         | 1.96%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.96%   |
| Micronas QSB                                                               | 1         | 1.96%   |
| M-Audio M-Audio Fast Track MKII                                            | 1         | 1.96%   |
| Logitech Headset H340                                                      | 1         | 1.96%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 1.96%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.96%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 1.96%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 1.96%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 1.96%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.96%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 1.96%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 1.96%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.96%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1         | 1.96%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 6         | 40%     |
| Crucial             | 4         | 26.67%  |
| Unknown             | 2         | 13.33%  |
| Samsung Electronics | 2         | 13.33%  |
| Toshiba             | 1         | 6.67%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 2         | 11.76%  |
| Crucial RAM CT16G4SFD824A.M16FRS 16GB SODIMM DDR4 2400MT/s       | 2         | 11.76%  |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 5.88%   |
| Unknown RAM Module 16384MB 2133MT/s                              | 1         | 5.88%   |
| Toshiba RAM 8HTF12864HDY-800G1 2048MB SODIMM 1066MT/s            | 1         | 5.88%   |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 1066MT/s             | 1         | 5.88%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 5.88%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 5.88%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 5.88%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 5.88%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 5.88%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 5.88%   |
| SK hynix RAM H9CCNNNBLTALAR-NTD 4GB Row Of Chips LPDDR3 1600MT/s | 1         | 5.88%   |
| Crucial RAM CT4G4SFS8213.C8FBD1 4GB SODIMM DDR4 2133MT/s         | 1         | 5.88%   |
| Crucial RAM CT16G4S24AM.M16FE 16GB SODIMM DDR4 2400MT/s          | 1         | 5.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 7         | 53.85%  |
| DDR3    | 3         | 23.08%  |
| LPDDR3  | 1         | 7.69%   |
| DDR2    | 1         | 7.69%   |
| Unknown | 1         | 7.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 10        | 76.92%  |
| Row Of Chips | 1         | 7.69%   |
| DIMM         | 1         | 7.69%   |
| Unknown      | 1         | 7.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 6         | 40%     |
| 16384 | 4         | 26.67%  |
| 8192  | 3         | 20%     |
| 32768 | 2         | 13.33%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 4         | 26.67%  |
| 1600  | 4         | 26.67%  |
| 2400  | 3         | 20%     |
| 2133  | 2         | 13.33%  |
| 1333  | 1         | 6.67%   |
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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 4         | 16%     |
| Apple                                  | 4         | 16%     |
| Alcor Micro                            | 4         | 16%     |
| Acer                                   | 4         | 16%     |
| Sunplus Innovation Technology          | 2         | 8%      |
| Chicony Electronics                    | 2         | 8%      |
| Suyin                                  | 1         | 4%      |
| Microdia                               | 1         | 4%      |
| Lite-On Technology                     | 1         | 4%      |
| Google                                 | 1         | 4%      |
| Cheng Uei Precision Industry (Foxlink) | 1         | 4%      |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Alcor Micro HD WebCam                                                      | 3         | 11.54%  |
| Apple Built-in iSight                                                      | 2         | 7.69%   |
| Acer SunplusIT INC. Integrated Camera                                      | 2         | 7.69%   |
| Suyin HP TrueVision Full HD                                                | 1         | 3.85%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 3.85%   |
| Sunplus Integrated Camera                                                  | 1         | 3.85%   |
| Realtek USB2.0 camera                                                      | 1         | 3.85%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 3.85%   |
| Realtek Integrated Webcam                                                  | 1         | 3.85%   |
| Realtek HP Truevision HD                                                   | 1         | 3.85%   |
| Microdia HP Webcam-101                                                     | 1         | 3.85%   |
| Lite-On Integrated Camera                                                  | 1         | 3.85%   |
| Chicony USB2.0 UVC WebCam                                                  | 1         | 3.85%   |
| Chicony HD User Facing                                                     | 1         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 1         | 3.85%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 1         | 3.85%   |
| Apple iBridge                                                              | 1         | 3.85%   |
| Apple FaceTime HD Camera (Built-in)                                        | 1         | 3.85%   |
| Alcor Micro HP Webcam-101                                                  | 1         | 3.85%   |
| Acer SunplusIT Integrated Camera                                           | 1         | 3.85%   |
| Acer BisonCam, NB Pro                                                      | 1         | 3.85%   |
| Unknown                                                                    | 1         | 3.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 3         | 60%     |
| Synaptics             | 1         | 20%     |
| LighTuning Technology | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor     | 3         | 60%     |
| Synaptics Metallica MOH Touch Fingerprint Reader | 1         | 20%     |
| LighTuning ES603 Swipe Fingerprint Sensor        | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Purism, SPC | 2         | 50%     |
| Clay Logic  | 1         | 25%     |
| Alcor Micro | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Purism, SPC Librem Key              | 2         | 50%     |
| Clay Logic Nitrokey Pro             | 1         | 25%     |
| Alcor Micro AU9540 Smartcard Reader | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 19        | 50%     |
| 1     | 14        | 36.84%  |
| 2     | 3         | 7.89%   |
| 4     | 1         | 2.63%   |
| 3     | 1         | 2.63%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 8         | 29.63%  |
| Bluetooth             | 7         | 25.93%  |
| Fingerprint reader    | 5         | 18.52%  |
| Graphics card         | 4         | 14.81%  |
| Multimedia controller | 1         | 3.7%    |
| Chipcard              | 1         | 3.7%    |
| Camera                | 1         | 3.7%    |

