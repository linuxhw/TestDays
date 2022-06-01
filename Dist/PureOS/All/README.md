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

Total: 55

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![OS](./images/pie_chart/os_name.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| PureOS 9.0  | 12        | 32.43%  |
| PureOS 10.0 | 11        | 29.73%  |
| PureOS 10   | 9         | 24.32%  |
| PureOS 9    | 3         | 8.11%   |
| PureOS 8    | 2         | 5.41%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| PureOS | 36        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Computers | Percent |
|----------------------------------|-----------|---------|
| 4.19.0-5-amd64                   | 9         | 22.5%   |
| 5.10.0-13-amd64                  | 5         | 12.5%   |
| 5.10.0-8-amd64                   | 4         | 10%     |
| 4.19.0-14-amd64                  | 4         | 10%     |
| 5.10.0-11-amd64                  | 3         | 7.5%    |
| 5.7.0-1-librem5                  | 2         | 5%      |
| 5.10.0-9-amd64                   | 2         | 5%      |
| 5.10.0-7-amd64                   | 2         | 5%      |
| 5.9-sunxi64                      | 1         | 2.5%    |
| 5.8-sunxi64                      | 1         | 2.5%    |
| 5.7.0-0.38-1-pinebookpro-hwaccel | 1         | 2.5%    |
| 5.15.0-2-amd64                   | 1         | 2.5%    |
| 5.10.0-6-amd64                   | 1         | 2.5%    |
| 5.10.0-14-amd64                  | 1         | 2.5%    |
| 5.10.0-12-amd64                  | 1         | 2.5%    |
| 4.19.72-imx8-sr                  | 1         | 2.5%    |
| 4.16.0-1-amd64                   | 1         | 2.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 17        | 44.74%  |
| 4.19.0  | 13        | 34.21%  |
| 5.7.0   | 3         | 7.89%   |
| 5.9     | 1         | 2.63%   |
| 5.8     | 1         | 2.63%   |
| 5.15.0  | 1         | 2.63%   |
| 4.19.72 | 1         | 2.63%   |
| 4.16.0  | 1         | 2.63%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 17        | 45.95%  |
| 4.19    | 14        | 37.84%  |
| 5.7     | 3         | 8.11%   |
| 5.15    | 1         | 2.7%    |
| 5       | 1         | 2.7%    |
| 4.16    | 1         | 2.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 31        | 86.11%  |
| aarch64 | 5         | 13.89%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 30        | 76.92%  |
| Unknown         | 6         | 15.38%  |
| MATE            | 1         | 2.56%   |
| KDE5            | 1         | 2.56%   |
| GNOME Flashback | 1         | 2.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 26        | 63.41%  |
| Unknown | 6         | 14.63%  |
| X11     | 5         | 12.2%   |
| Tty     | 4         | 9.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 24        | 66.67%  |
| GDM     | 9         | 25%     |
| GDM3    | 3         | 8.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 18        | 46.15%  |
| de_DE   | 5         | 12.82%  |
| Unknown | 4         | 10.26%  |
| en_GB   | 3         | 7.69%   |
| ru_RU   | 2         | 5.13%   |
| zh_CN   | 1         | 2.56%   |
| pt_PT   | 1         | 2.56%   |
| pl_PL   | 1         | 2.56%   |
| it_IT   | 1         | 2.56%   |
| es_CR   | 1         | 2.56%   |
| en_AU   | 1         | 2.56%   |
| C       | 1         | 2.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 32        | 86.49%  |
| EFI  | 5         | 13.51%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 33        | 91.67%  |
| Unknown | 2         | 5.56%   |
| Ext2    | 1         | 2.78%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 22        | 57.89%  |
| MBR     | 10        | 26.32%  |
| GPT     | 6         | 15.79%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 30        | 83.33%  |
| Yes       | 6         | 16.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 33        | 91.67%  |
| Yes       | 3         | 8.33%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Purism              | 10        | 27.78%  |
| Lenovo              | 5         | 13.89%  |
| Hewlett-Packard     | 4         | 11.11%  |
| Dell                | 4         | 11.11%  |
| Apple               | 4         | 11.11%  |
| Pine Microsystems   | 2         | 5.56%   |
| Unknown             | 2         | 5.56%   |
| Toshiba             | 1         | 2.78%   |
| Notebook            | 1         | 2.78%   |
| Gigabyte Technology | 1         | 2.78%   |
| ASUSTek Computer    | 1         | 2.78%   |
| Acer                | 1         | 2.78%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Purism Librem 14                         | 4         | 11.11%  |
| Purism Librem 15 v4                      | 2         | 5.56%   |
| HP Pavilion g6                           | 2         | 5.56%   |
| Unknown                                  | 2         | 5.56%   |
| Toshiba Satellite L500D                  | 1         | 2.78%   |
| Purism Librem 5                          | 1         | 2.78%   |
| Purism Librem 15 v3                      | 1         | 2.78%   |
| Purism Librem 13 v4                      | 1         | 2.78%   |
| Purism Librem 13 v2                      | 1         | 2.78%   |
| Pine Microsystems Pine64 PinePhone (1.2) | 1         | 2.78%   |
| Pine Microsystems Pine64 Pinebook Pro    | 1         | 2.78%   |
| Notebook P17SM                           | 1         | 2.78%   |
| Lenovo ThinkPad T540p 20BFS23T00         | 1         | 2.78%   |
| Lenovo ThinkPad T440p                    | 1         | 2.78%   |
| Lenovo ThinkPad T440 20B60044RT          | 1         | 2.78%   |
| Lenovo ThinkPad E480 20KN003SUS          | 1         | 2.78%   |
| Lenovo ThinkPad 13 2nd Gen 20J2S00G00    | 1         | 2.78%   |
| HP Spectre x360 Convertible              | 1         | 2.78%   |
| HP Pavilion Notebook                     | 1         | 2.78%   |
| Gigabyte B85M-DS3H                       | 1         | 2.78%   |
| Dell XPS 13 9370                         | 1         | 2.78%   |
| Dell Inspiron 5547                       | 1         | 2.78%   |
| Dell Inspiron 3847                       | 1         | 2.78%   |
| Dell Inspiron 15-3567                    | 1         | 2.78%   |
| ASUS A88X-PLUS/USB                       | 1         | 2.78%   |
| Apple MacBookPro6,1                      | 1         | 2.78%   |
| Apple MacBookPro14,2                     | 1         | 2.78%   |
| Apple iMac7,1                            | 1         | 2.78%   |
| Apple iMac13,1                           | 1         | 2.78%   |
| Acer Nitro AN515-43                      | 1         | 2.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Purism Librem            | 10        | 27.78%  |
| Lenovo ThinkPad          | 5         | 13.89%  |
| HP Pavilion              | 3         | 8.33%   |
| Dell Inspiron            | 3         | 8.33%   |
| Pine Microsystems Pine64 | 2         | 5.56%   |
| Unknown                  | 2         | 5.56%   |
| Toshiba Satellite        | 1         | 2.78%   |
| Notebook P17SM           | 1         | 2.78%   |
| HP Spectre               | 1         | 2.78%   |
| Gigabyte B85M-DS3H       | 1         | 2.78%   |
| Dell XPS                 | 1         | 2.78%   |
| ASUS A88X-PLUS           | 1         | 2.78%   |
| Apple MacBookPro6        | 1         | 2.78%   |
| Apple MacBookPro14       | 1         | 2.78%   |
| Apple iMac7              | 1         | 2.78%   |
| Apple iMac13             | 1         | 2.78%   |
| Acer Nitro               | 1         | 2.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 7         | 19.44%  |
| 2013    | 5         | 13.89%  |
| 2019    | 4         | 11.11%  |
| 2017    | 4         | 11.11%  |
| 2021    | 3         | 8.33%   |
| 2015    | 3         | 8.33%   |
| 2018    | 2         | 5.56%   |
| 2016    | 2         | 5.56%   |
| 2011    | 2         | 5.56%   |
| 2020    | 1         | 2.78%   |
| 2014    | 1         | 2.78%   |
| 2009    | 1         | 2.78%   |
| 2007    | 1         | 2.78%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 27        | 75%     |
| Desktop        | 3         | 8.33%   |
| System on chip | 2         | 5.56%   |
| All in one     | 2         | 5.56%   |
| Phone          | 1         | 2.78%   |
| Convertible    | 1         | 2.78%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 36        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 26        | 72.22%  |
| Yes  | 10        | 27.78%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 16.01-24.0 | 9         | 25%     |
| 8.01-16.0  | 8         | 22.22%  |
| 4.01-8.0   | 5         | 13.89%  |
| 32.01-64.0 | 5         | 13.89%  |
| 3.01-4.0   | 5         | 13.89%  |
| 2.01-3.0   | 2         | 5.56%   |
| 24.01-32.0 | 1         | 2.78%   |
| 1.01-2.0   | 1         | 2.78%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 11        | 26.83%  |
| 2.01-3.0  | 10        | 24.39%  |
| 3.01-4.0  | 9         | 21.95%  |
| 4.01-8.0  | 8         | 19.51%  |
| 8.01-16.0 | 1         | 2.44%   |
| 0.51-1.0  | 1         | 2.44%   |
| 0.01-0.5  | 1         | 2.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 24        | 66.67%  |
| 2      | 11        | 30.56%  |
| 5      | 1         | 2.78%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 27        | 75%     |
| Yes       | 9         | 25%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 69.44%  |
| No        | 11        | 30.56%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 31        | 86.11%  |
| No        | 5         | 13.89%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 69.44%  |
| No        | 11        | 30.56%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 9         | 23.68%  |
| Germany                | 6         | 15.79%  |
| UK                     | 5         | 13.16%  |
| Canada                 | 3         | 7.89%   |
| Russia                 | 2         | 5.26%   |
| Australia              | 2         | 5.26%   |
| Turkey                 | 1         | 2.63%   |
| South Africa           | 1         | 2.63%   |
| Portugal               | 1         | 2.63%   |
| Poland                 | 1         | 2.63%   |
| Italy                  | 1         | 2.63%   |
| Iran                   | 1         | 2.63%   |
| France                 | 1         | 2.63%   |
| Costa Rica             | 1         | 2.63%   |
| China                  | 1         | 2.63%   |
| Brazil                 | 1         | 2.63%   |
| Bosnia and Herzegovina | 1         | 2.63%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Stuttgart          | 3         | 7.5%    |
| New York           | 2         | 5%      |
| London             | 2         | 5%      |
| Yuzhnoural'sk      | 1         | 2.5%    |
| Wixom              | 1         | 2.5%    |
| Windsor            | 1         | 2.5%    |
| Warsaw             | 1         | 2.5%    |
| Vancouver          | 1         | 2.5%    |
| Troy               | 1         | 2.5%    |
| Thorpe Hamlet      | 1         | 2.5%    |
| Spencer            | 1         | 2.5%    |
| Seattle            | 1         | 2.5%    |
| San Jose           | 1         | 2.5%    |
| Paris              | 1         | 2.5%    |
| Montreal           | 1         | 2.5%    |
| Milwaukee          | 1         | 2.5%    |
| Melbourne          | 1         | 2.5%    |
| Liverpool          | 1         | 2.5%    |
| Leeds              | 1         | 2.5%    |
| Krasnogorsk        | 1         | 2.5%    |
| Istanbul           | 1         | 2.5%    |
| Guimaraes          | 1         | 2.5%    |
| Fort Collins       | 1         | 2.5%    |
| Eberswalde         | 1         | 2.5%    |
| Cape Town          | 1         | 2.5%    |
| Camden             | 1         | 2.5%    |
| Big Sky            | 1         | 2.5%    |
| Berlin             | 1         | 2.5%    |
| Banja Luka         | 1         | 2.5%    |
| Bandar-e Asalūyeh | 1         | 2.5%    |
| Balow              | 1         | 2.5%    |
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


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 14     | 21.74%  |
| Seagate             | 6         | 10     | 13.04%  |
| Unknown             | 5         | 9      | 10.87%  |
| WDC                 | 3         | 4      | 6.52%   |
| HGST                | 3         | 3      | 6.52%   |
| A-DATA Technology   | 3         | 4      | 6.52%   |
| Crucial             | 2         | 4      | 4.35%   |
| Apple               | 2         | 3      | 4.35%   |
| Transcend           | 1         | 1      | 2.17%   |
| Toshiba             | 1         | 1      | 2.17%   |
| SanDisk             | 1         | 1      | 2.17%   |
| PLEXTOR             | 1         | 1      | 2.17%   |
| Phison              | 1         | 1      | 2.17%   |
| Mushkin             | 1         | 1      | 2.17%   |
| JMicron             | 1         | 1      | 2.17%   |
| Intel               | 1         | 1      | 2.17%   |
| Hitachi             | 1         | 1      | 2.17%   |
| BIWIN               | 1         | 1      | 2.17%   |
| ASMT                | 1         | 2      | 2.17%   |
| ADATA Technology    | 1         | 1      | 2.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST1000LM048-2E7172 1TB      | 2         | 3.92%   |
| Samsung SSD 970 PRO 1TB             | 2         | 3.92%   |
| WDC WDS100T2B0C-00PXH0 1TB          | 1         | 1.96%   |
| WDC WDBNCE2500PNC 250GB SSD         | 1         | 1.96%   |
| WDC WD3200AAJS-40RYA0 320GB         | 1         | 1.96%   |
| Unknown SH64G  64GB                 | 1         | 1.96%   |
| Unknown MMC Card  32GB              | 1         | 1.96%   |
| Unknown MMC Card  16GB              | 1         | 1.96%   |
| Unknown DA4128  128GB               | 1         | 1.96%   |
| Unknown AFGCF  128GB                | 1         | 1.96%   |
| Unknown 8GTF4R  8GB                 | 1         | 1.96%   |
| Unknown 032G32  32GB                | 1         | 1.96%   |
| Transcend TS240GMTS420S 240GB SSD   | 1         | 1.96%   |
| Toshiba NVMe SSD Drive 512GB        | 1         | 1.96%   |
| Seagate ST480HM000-1G5162 480GB     | 1         | 1.96%   |
| Seagate ST3320418AS 320GB           | 1         | 1.96%   |
| Seagate ST31000524AS 1TB            | 1         | 1.96%   |
| Seagate ST1000DM003-1ER162 1TB      | 1         | 1.96%   |
| Seagate NVMe SSD Drive 2TB          | 1         | 1.96%   |
| SanDisk SDSSDH3500G 500GB           | 1         | 1.96%   |
| Samsung SSD 970 EVO 250GB           | 1         | 1.96%   |
| Samsung SSD 960 EVO 500GB           | 1         | 1.96%   |
| Samsung SSD 960 EVO 250GB           | 1         | 1.96%   |
| Samsung SSD 860 EVO 500GB           | 1         | 1.96%   |
| Samsung SSD 860 EVO 250GB           | 1         | 1.96%   |
| Samsung SSD 860 EVO 1TB             | 1         | 1.96%   |
| Samsung SSD 850 EVO 500GB           | 1         | 1.96%   |
| Samsung SSD 850 EVO 250GB           | 1         | 1.96%   |
| Samsung NVMe SSD Drive 1TB          | 1         | 1.96%   |
| PLEXTOR PX-1TM6Pro 1024GB SSD       | 1         | 1.96%   |
| Phison PM8512GPTCB4B8TF-E13T4 512GB | 1         | 1.96%   |
| Mushkin MKNSSDRE250GB-LT            | 1         | 1.96%   |
| JMicron Generic 128GB               | 1         | 1.96%   |
| Intel SSDSC2BF180A4H 180GB          | 1         | 1.96%   |
| Hitachi HTS545050A7E380 500GB       | 1         | 1.96%   |
| HGST HTS721010A9E630 1TB            | 1         | 1.96%   |
| HGST HTS545050B7E660 500GB          | 1         | 1.96%   |
| HGST HTS541010A9E680 1TB            | 1         | 1.96%   |
| Crucial CT250MX500SSD4 250GB        | 1         | 1.96%   |
| Crucial CT2000MX500SSD1 2TB         | 1         | 1.96%   |
| BIWIN SSD 120GB                     | 1         | 1.96%   |
| ASMT 2235 240GB                     | 1         | 1.96%   |
| Apple NVMe SSD Drive 8KB            | 1         | 1.96%   |
| Apple NVMe SSD Drive 256GB          | 1         | 1.96%   |
| Apple HDD ST1000LM024 1TB           | 1         | 1.96%   |
| ADATA NVMe SSD Drive 512GB          | 1         | 1.96%   |
| A-DATA SU630 240GB SSD              | 1         | 1.96%   |
| A-DATA IM2S3138E-128GM-B 128GB SSD  | 1         | 1.96%   |
| A-DATA AXNS381E-256GM-B 256GB SSD   | 1         | 1.96%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 9      | 45.45%  |
| HGST    | 3         | 3      | 27.27%  |
| WDC     | 1         | 1      | 9.09%   |
| Hitachi | 1         | 1      | 9.09%   |
| Apple   | 1         | 1      | 9.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 8      | 31.58%  |
| A-DATA Technology   | 3         | 4      | 15.79%  |
| Crucial             | 2         | 4      | 10.53%  |
| WDC                 | 1         | 2      | 5.26%   |
| Transcend           | 1         | 1      | 5.26%   |
| SanDisk             | 1         | 1      | 5.26%   |
| PLEXTOR             | 1         | 1      | 5.26%   |
| Mushkin             | 1         | 1      | 5.26%   |
| JMicron             | 1         | 1      | 5.26%   |
| Intel               | 1         | 1      | 5.26%   |
| BIWIN               | 1         | 1      | 5.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 16        | 25     | 36.36%  |
| NVMe    | 11        | 13     | 25%     |
| HDD     | 11        | 15     | 25%     |
| MMC     | 5         | 9      | 11.36%  |
| Unknown | 1         | 2      | 2.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 23        | 38     | 54.76%  |
| NVMe | 11        | 13     | 26.19%  |
| MMC  | 5         | 9      | 11.9%   |
| SAS  | 3         | 4      | 7.14%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 16        | 27     | 61.54%  |
| 0.51-1.0   | 8         | 10     | 30.77%  |
| 1.01-2.0   | 2         | 3      | 7.69%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 15        | 39.47%  |
| 251-500    | 5         | 13.16%  |
| 101-250    | 5         | 13.16%  |
| 21-50      | 3         | 7.89%   |
| 501-1000   | 3         | 7.89%   |
| 1001-2000  | 2         | 5.26%   |
| 51-100     | 2         | 5.26%   |
| Unknown    | 2         | 5.26%   |
| 2001-3000  | 1         | 2.63%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 21        | 55.26%  |
| 21-50    | 7         | 18.42%  |
| 101-250  | 3         | 7.89%   |
| 501-1000 | 3         | 7.89%   |
| Unknown  | 2         | 5.26%   |
| 251-500  | 1         | 2.63%   |
| 51-100   | 1         | 2.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                      | Computers | Drives | Percent |
|----------------------------|-----------|--------|---------|
| Seagate ST31000524AS 1TB   | 1         | 1      | 33.33%  |
| Intel SSDSC2BF180A4H 180GB | 1         | 1      | 33.33%  |
| Apple HDD ST1000LM024 1TB  | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 33.33%  |
| Intel   | 1         | 1      | 33.33%  |
| Apple   | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| Apple   | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 27        | 48     | 69.23%  |
| Works    | 9         | 13     | 23.08%  |
| Malfunc  | 3         | 3      | 7.69%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 21        | 60%     |
| Samsung Electronics          | 5         | 14.29%  |
| AMD                          | 3         | 8.57%   |
| Toshiba America Info Systems | 1         | 2.86%   |
| Seagate Technology           | 1         | 2.86%   |
| Sandisk                      | 1         | 2.86%   |
| Phison Electronics           | 1         | 2.86%   |
| Apple                        | 1         | 2.86%   |
| ADATA Technology             | 1         | 2.86%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 19.44%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 13.89%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 8.33%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 5.56%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 5.56%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 2         | 5.56%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 2.78%   |
| Seagate FireCuda 510 SSD                                                       | 1         | 2.78%   |
| Sandisk Non-Volatile memory controller                                         | 1         | 2.78%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 2.78%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 2.78%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 2.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 1         | 2.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 1         | 2.78%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1         | 2.78%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 2.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 2.78%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 2.78%   |
| Apple S3X NVMe Controller                                                      | 1         | 2.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 2.78%   |
| ADATA Non-Volatile memory controller                                           | 1         | 2.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 23        | 65.71%  |
| NVMe | 11        | 31.43%  |
| IDE  | 1         | 2.86%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 28        | 77.78%  |
| ARM    | 5         | 13.89%  |
| AMD    | 3         | 8.33%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| ARM Processor                                   | 5         | 13.89%  |
| Intel Core i7-7500U CPU @ 2.70GHz               | 4         | 11.11%  |
| Intel Core i7-10710U CPU @ 1.10GHz              | 4         | 11.11%  |
| Intel Core i7-6500U CPU @ 2.50GHz               | 2         | 5.56%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 5.56%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 1         | 2.78%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 2.78%   |
| Intel Core i7-7567U CPU @ 3.50GHz               | 1         | 2.78%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz              | 1         | 2.78%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz              | 1         | 2.78%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz              | 1         | 2.78%   |
| Intel Core i7-4510U CPU @ 2.00GHz               | 1         | 2.78%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 1         | 2.78%   |
| Intel Core i5-4460 CPU @ 3.20GHz                | 1         | 2.78%   |
| Intel Core i5-3330S CPU @ 2.70GHz               | 1         | 2.78%   |
| Intel Core i5 CPU M 540 @ 2.53GHz               | 1         | 2.78%   |
| Intel Core i3-4130T CPU @ 2.90GHz               | 1         | 2.78%   |
| Intel Core i3-4010U CPU @ 1.70GHz               | 1         | 2.78%   |
| Intel Core i3-3120M CPU @ 2.50GHz               | 1         | 2.78%   |
| Intel Core i3-2330M CPU @ 2.20GHz               | 1         | 2.78%   |
| Intel Core 2 Duo CPU T7700 @ 2.40GHz            | 1         | 2.78%   |
| AMD Turion II Dual-Core Mobile M520             | 1         | 2.78%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx   | 1         | 2.78%   |
| AMD A10-7860K Radeon R7, 12 Compute Cores 4C+8G | 1         | 2.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 17        | 47.22%  |
| Intel Core i5           | 6         | 16.67%  |
| Other                   | 5         | 13.89%  |
| Intel Core i3           | 4         | 11.11%  |
| Intel Core 2 Duo        | 1         | 2.78%   |
| AMD Turion II Dual-Core | 1         | 2.78%   |
| AMD Ryzen 5             | 1         | 2.78%   |
| AMD A10                 | 1         | 2.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 19        | 52.78%  |
| 4      | 13        | 36.11%  |
| 6      | 4         | 11.11%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 36        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 27        | 75%     |
| 1      | 9         | 25%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 33        | 89.19%  |
| Unknown        | 4         | 10.81%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 29        | 76.32%  |
| 0xa0660    | 2         | 5.26%   |
| 0x406e3    | 2         | 5.26%   |
| 0x806e9    | 1         | 2.63%   |
| 0x40651    | 1         | 2.63%   |
| 0x306d4    | 1         | 2.63%   |
| 0x08108109 | 1         | 2.63%   |
| 0x06003106 | 1         | 2.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 9         | 25%     |
| Haswell     | 7         | 19.44%  |
| Unknown     | 5         | 13.89%  |
| CometLake   | 4         | 11.11%  |
| Skylake     | 2         | 5.56%   |
| IvyBridge   | 2         | 5.56%   |
| Zen+        | 1         | 2.78%   |
| Westmere    | 1         | 2.78%   |
| Steamroller | 1         | 2.78%   |
| SandyBridge | 1         | 2.78%   |
| K10         | 1         | 2.78%   |
| Core        | 1         | 2.78%   |
| Broadwell   | 1         | 2.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 25        | 65.79%  |
| Nvidia | 7         | 18.42%  |
| AMD    | 6         | 15.79%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                 | 6         | 15%     |
| Intel Comet Lake UHD Graphics                                                         | 4         | 10%     |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 3         | 7.5%    |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 2         | 5%      |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 2         | 5%      |
| Nvidia GT216M [GeForce GT 330M]                                                       | 1         | 2.5%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 1         | 2.5%    |
| Nvidia GK208M [GeForce GT 730M]                                                       | 1         | 2.5%    |
| Nvidia GK208B [GeForce GT 710]                                                        | 1         | 2.5%    |
| Nvidia GK107M [GeForce GT 640M Mac Edition]                                           | 1         | 2.5%    |
| Nvidia GK104M [GeForce GTX 870M]                                                      | 1         | 2.5%    |
| Nvidia GF116 [GeForce GTS 450 Rev. 2]                                                 | 1         | 2.5%    |
| Nvidia GF108 [GeForce GT 630]                                                         | 1         | 2.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 1         | 2.5%    |
| Intel UHD Graphics 620                                                                | 1         | 2.5%    |
| Intel Iris Plus Graphics 650                                                          | 1         | 2.5%    |
| Intel HD Graphics 630                                                                 | 1         | 2.5%    |
| Intel HD Graphics 5500                                                                | 1         | 2.5%    |
| Intel Core Processor Integrated Graphics Controller                                   | 1         | 2.5%    |
| Intel 3rd Gen Core processor Graphics Controller                                      | 1         | 2.5%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 1         | 2.5%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 2.5%    |
| AMD Thames [Radeon HD 7500M/7600M Series]                                             | 1         | 2.5%    |
| AMD RV630/M76 [Mobility Radeon HD 2600 XT/2700]                                       | 1         | 2.5%    |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                             | 1         | 2.5%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 1         | 2.5%    |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                                    | 1         | 2.5%    |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                   | 1         | 2.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 18        | 50%     |
| Other          | 5         | 13.89%  |
| Intel + Nvidia | 4         | 11.11%  |
| 1 x Nvidia     | 3         | 8.33%   |
| 1 x AMD        | 3         | 8.33%   |
| Intel + AMD    | 2         | 5.56%   |
| 2 x AMD        | 1         | 2.78%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 30        | 83.33%  |
| Unknown | 6         | 16.67%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 35        | 94.59%  |
| 3.01-4.0   | 1         | 2.7%    |
| 0.51-1.0   | 1         | 2.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 6         | 15%     |
| LG Display              | 6         | 15%     |
| Chimei Innolux          | 5         | 12.5%   |
| BOE                     | 5         | 12.5%   |
| Apple                   | 4         | 10%     |
| AU Optronics            | 2         | 5%      |
| Unknown                 | 1         | 2.5%    |
| Sharp                   | 1         | 2.5%    |
| Lenovo                  | 1         | 2.5%    |
| Iiyama                  | 1         | 2.5%    |
| Grundig                 | 1         | 2.5%    |
| Goldstar                | 1         | 2.5%    |
| Dell                    | 1         | 2.5%    |
| Chi Mei Optoelectronics | 1         | 2.5%    |
| BenQ                    | 1         | 2.5%    |
| ASUSTek Computer        | 1         | 2.5%    |
| AOC                     | 1         | 2.5%    |
| Acer                    | 1         | 2.5%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC434B 3840x2160 344x194mm 15.5-inch     | 3         | 7.5%    |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 2         | 5%      |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 1         | 2.5%    |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                   | 1         | 2.5%    |
| Samsung Electronics SyncMaster SAM01D3 1440x900 408x225mm 18.3-inch       | 1         | 2.5%    |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch      | 1         | 2.5%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 1         | 2.5%    |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch              | 1         | 2.5%    |
| LG Display LCD Monitor LGD053B 1920x1080 294x165mm 13.3-inch              | 1         | 2.5%    |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch              | 1         | 2.5%    |
| LG Display LCD Monitor LGD03F0 1366x768 310x174mm 14.0-inch               | 1         | 2.5%    |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch               | 1         | 2.5%    |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch               | 1         | 2.5%    |
| Lenovo LEN Y44w-10 LEN65EA 3840x1200 1052x329mm 43.4-inch                 | 1         | 2.5%    |
| Iiyama PL2792H IVM664F 1920x1080 598x336mm 27.0-inch                      | 1         | 2.5%    |
| Grundig WXGA GRU4448 1600x1200                                            | 1         | 2.5%    |
| Goldstar IPS231 GSM5817 1920x1080 510x290mm 23.1-inch                     | 1         | 2.5%    |
| Dell P2213 DELF042 1680x1050 473x296mm 22.0-inch                          | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch          | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN1415 1920x1080 309x173mm 13.9-inch          | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN1365 1920x1080 293x165mm 13.2-inch          | 1         | 2.5%    |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 2.5%    |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                     | 1         | 2.5%    |
| BOE LCD Monitor BOE079A 1920x1080 309x173mm 13.9-inch                     | 1         | 2.5%    |
| BOE LCD Monitor BOE06C2 1366x768 344x194mm 15.5-inch                      | 1         | 2.5%    |
| BOE LCD Monitor BOE06BE 1920x1080 294x165mm 13.3-inch                     | 1         | 2.5%    |
| BOE LCD Monitor BOE0641 1920x1080 344x193mm 15.5-inch                     | 1         | 2.5%    |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                         | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO713C 1366x768 309x173mm 13.9-inch             | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO10ED 1920x1080 344x193mm 15.5-inch            | 1         | 2.5%    |
| ASUSTek Computer VP249 AUS24AF 1920x1080 527x296mm 23.8-inch              | 1         | 2.5%    |
| Apple iMac APPA012 1920x1080 475x267mm 21.5-inch                          | 1         | 2.5%    |
| Apple Color LCD APPA034 2880x1800 286x179mm 13.3-inch                     | 1         | 2.5%    |
| Apple Color LCD APP9CCF 1920x1200 367x230mm 17.1-inch                     | 1         | 2.5%    |
| Apple Color LCD APP9C6B 1680x1050 433x270mm 20.1-inch                     | 1         | 2.5%    |
| AOC 2050W AOC2050 1600x900 432x240mm 19.5-inch                            | 1         | 2.5%    |
| Acer H236HL ACR0318 1920x1080 509x286mm 23.0-inch                         | 1         | 2.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 16        | 44.44%  |
| 3840x2160 (4K)     | 6         | 16.67%  |
| 1366x768 (WXGA)    | 6         | 16.67%  |
| 1680x1050 (WSXGA+) | 2         | 5.56%   |
| 3840x1200          | 1         | 2.78%   |
| 2880x1800          | 1         | 2.78%   |
| 2288x1287          | 1         | 2.78%   |
| 1920x1200 (WUXGA)  | 1         | 2.78%   |
| 1600x900 (HD+)     | 1         | 2.78%   |
| 1440x900 (WXGA+)   | 1         | 2.78%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 12        | 30%     |
| 13     | 10        | 25%     |
| 27     | 2         | 5%      |
| 24     | 2         | 5%      |
| 23     | 2         | 5%      |
| 20     | 2         | 5%      |
| 17     | 2         | 5%      |
| 14     | 2         | 5%      |
| 142    | 1         | 2.5%    |
| 54     | 1         | 2.5%    |
| 43     | 1         | 2.5%    |
| 22     | 1         | 2.5%    |
| 21     | 1         | 2.5%    |
| 19     | 1         | 2.5%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 17        | 43.59%  |
| 501-600        | 6         | 15.38%  |
| 401-500        | 5         | 12.82%  |
| 201-300        | 5         | 12.82%  |
| 351-400        | 3         | 7.69%   |
| 1001-1500      | 2         | 5.13%   |
| More than 2000 | 1         | 2.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 25        | 78.13%  |
| 16/10 | 5         | 15.63%  |
| 3.20  | 1         | 3.13%   |
| 1.00  | 1         | 3.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 12        | 30%     |
| 81-90          | 7         | 17.5%   |
| 201-250        | 6         | 15%     |
| 71-80          | 5         | 12.5%   |
| 151-200        | 3         | 7.5%    |
| More than 1000 | 2         | 5%      |
| 301-350        | 2         | 5%      |
| 131-140        | 1         | 2.5%    |
| 121-130        | 1         | 2.5%    |
| 501-1000       | 1         | 2.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 13        | 32.5%   |
| 121-160       | 11        | 27.5%   |
| More than 240 | 6         | 15%     |
| 101-120       | 6         | 15%     |
| 161-240       | 3         | 7.5%    |
| 1-50          | 1         | 2.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 23        | 63.89%  |
| 2     | 8         | 22.22%  |
| 0     | 4         | 11.11%  |
| 3     | 1         | 2.78%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 18        | 33.96%  |
| Qualcomm Atheros                | 13        | 24.53%  |
| Intel                           | 7         | 13.21%  |
| Broadcom                        | 5         | 9.43%   |
| Broadcom Limited                | 2         | 3.77%   |
| ASIX Electronics                | 2         | 3.77%   |
| Ralink                          | 1         | 1.89%   |
| Qualcomm Atheros Communications | 1         | 1.89%   |
| MediaTek                        | 1         | 1.89%   |
| Marvell Technology Group        | 1         | 1.89%   |
| Edimax Technology               | 1         | 1.89%   |
| ASUSTek Computer                | 1         | 1.89%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 18.33%  |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 10        | 16.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 8.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 5%      |
| Intel Wireless 7265                                               | 3         | 5%      |
| Intel Wireless 7260                                               | 2         | 3.33%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 3.33%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 3.33%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 1.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 1.67%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1         | 1.67%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 1.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.67%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 1         | 1.67%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1         | 1.67%   |
| MediaTek WiFi                                                     | 1         | 1.67%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.67%   |
| Intel Wireless 8265 / 8275                                        | 1         | 1.67%   |
| Intel Ethernet Connection I218-V                                  | 1         | 1.67%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.67%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                       | 1         | 1.67%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.67%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 1.67%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 1         | 1.67%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                            | 1         | 1.67%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1         | 1.67%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 1         | 1.67%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 1         | 1.67%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 1         | 1.67%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]         | 1         | 1.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 13        | 38.24%  |
| Intel                           | 6         | 17.65%  |
| Realtek Semiconductor           | 4         | 11.76%  |
| Broadcom                        | 4         | 11.76%  |
| Broadcom Limited                | 2         | 5.88%   |
| Ralink                          | 1         | 2.94%   |
| Qualcomm Atheros Communications | 1         | 2.94%   |
| MediaTek                        | 1         | 2.94%   |
| Edimax Technology               | 1         | 2.94%   |
| ASUSTek Computer                | 1         | 2.94%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 10        | 29.41%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 3         | 8.82%   |
| Intel Wireless 7265                                        | 3         | 8.82%   |
| Intel Wireless 7260                                        | 2         | 5.88%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 1         | 2.94%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1         | 2.94%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter    | 1         | 2.94%   |
| Realtek RTL8191SEvB Wireless LAN Controller                | 1         | 2.94%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter     | 1         | 2.94%   |
| Qualcomm Atheros AR9271 802.11n                            | 1         | 2.94%   |
| MediaTek WiFi                                              | 1         | 2.94%   |
| Intel Wireless 8265 / 8275                                 | 1         | 2.94%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                | 1         | 2.94%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter | 1         | 2.94%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                     | 1         | 2.94%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                | 1         | 2.94%   |
| Broadcom BCM43224 802.11a/b/g/n                            | 1         | 2.94%   |
| Broadcom BCM4321 802.11a/b/g/n                             | 1         | 2.94%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter        | 1         | 2.94%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]  | 1         | 2.94%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 16        | 64%     |
| Intel                    | 4         | 16%     |
| Broadcom                 | 2         | 8%      |
| ASIX Electronics         | 2         | 8%      |
| Marvell Technology Group | 1         | 4%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 42.31%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 19.23%  |
| Intel Ethernet Connection I217-LM                                 | 2         | 7.69%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 7.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 3.85%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 3.85%   |
| Intel Ethernet Connection I218-V                                  | 1         | 3.85%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 3.85%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 3.85%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 3.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 30        | 55.56%  |
| Ethernet | 24        | 44.44%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 18        | 58.06%  |
| WiFi     | 13        | 41.94%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 21        | 58.33%  |
| 1     | 9         | 25%     |
| 0     | 6         | 16.67%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 31        | 86.11%  |
| Yes  | 5         | 13.89%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros Communications | 5         | 19.23%  |
| Intel                           | 5         | 19.23%  |
| Lite-On Technology              | 4         | 15.38%  |
| Foxconn / Hon Hai               | 4         | 15.38%  |
| Apple                           | 4         | 15.38%  |
| Realtek Semiconductor           | 1         | 3.85%   |
| Cambridge Silicon Radio         | 1         | 3.85%   |
| Broadcom                        | 1         | 3.85%   |
| ASUSTek Computer                | 1         | 3.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 5         | 19.23%  |
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 15.38%  |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 15.38%  |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 11.54%  |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 7.69%   |
| Apple Bluetooth USB Host Controller                 | 2         | 7.69%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 3.85%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.85%   |
| Broadcom HP Portable Valentine                      | 1         | 3.85%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 3.85%   |
| Apple Bluetooth Host Controller                     | 1         | 3.85%   |
| Apple Bluetooth HCI                                 | 1         | 3.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 27        | 65.85%  |
| Nvidia   | 5         | 12.2%   |
| AMD      | 4         | 9.76%   |
| XMOS     | 1         | 2.44%   |
| Shure    | 1         | 2.44%   |
| Micronas | 1         | 2.44%   |
| M-Audio  | 1         | 2.44%   |
| Logitech | 1         | 2.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 10        | 20%     |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 8%      |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 8%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 8%      |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 4%      |
| Intel 8 Series HD Audio Controller                                         | 2         | 4%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 4%      |
| XMOS xCORE USB Audio 2.0                                                   | 1         | 2%      |
| Shure MV5                                                                  | 1         | 2%      |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 2%      |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 2%      |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 2%      |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 2%      |
| Nvidia GF116 High Definition Audio Controller                              | 1         | 2%      |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 2%      |
| Micronas QSB                                                               | 1         | 2%      |
| M-Audio M-Audio Fast Track MKII                                            | 1         | 2%      |
| Logitech Headset H340                                                      | 1         | 2%      |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 2%      |
| Intel CM238 HD Audio Controller                                            | 1         | 2%      |
| Intel Broadwell-U Audio Controller                                         | 1         | 2%      |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 2%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 2%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 2%      |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 2%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 2%      |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 2%      |
| AMD FCH Azalia Controller                                                  | 1         | 2%      |
| AMD Family 17h/19h HD Audio Controller                                     | 1         | 2%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 6         | 42.86%  |
| Crucial             | 3         | 21.43%  |
| Unknown             | 2         | 14.29%  |
| Samsung Electronics | 2         | 14.29%  |
| Toshiba             | 1         | 7.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 2         | 12.5%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 6.25%   |
| Unknown RAM Module 16384MB 2133MT/s                              | 1         | 6.25%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s               | 1         | 6.25%   |
| Toshiba RAM 64T128020EDL2.5C2 4GB SODIMM 1066MT/s                | 1         | 6.25%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 6.25%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 6.25%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 6.25%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s        | 1         | 6.25%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 1         | 6.25%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 6.25%   |
| SK Hynix RAM H9CCNNNBLTALAR-NTD 4GB Row Of Chips LPDDR3 1600MT/s | 1         | 6.25%   |
| Crucial RAM CT4G4SFS8213.C8FBD1 4GB SODIMM DDR4 2133MT/s         | 1         | 6.25%   |
| Crucial RAM CT16G4SFD824A.M16FRS 16384MB SODIMM DDR4 2400MT/s    | 1         | 6.25%   |
| Crucial RAM CT16G4S24AM.M16FE 16GB SODIMM DDR4 2400MT/s          | 1         | 6.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 6         | 50%     |
| DDR3    | 3         | 25%     |
| LPDDR3  | 1         | 8.33%   |
| DDR2    | 1         | 8.33%   |
| Unknown | 1         | 8.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 9         | 75%     |
| Row Of Chips | 1         | 8.33%   |
| DIMM         | 1         | 8.33%   |
| Unknown      | 1         | 8.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 6         | 42.86%  |
| 16384 | 3         | 21.43%  |
| 8192  | 3         | 21.43%  |
| 32768 | 2         | 14.29%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 4         | 28.57%  |
| 1600  | 4         | 28.57%  |
| 2400  | 2         | 14.29%  |
| 2133  | 2         | 14.29%  |
| 1333  | 1         | 7.14%   |
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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Apple                                  | 4         | 16.67%  |
| Alcor Micro                            | 4         | 16.67%  |
| Acer                                   | 4         | 16.67%  |
| Realtek Semiconductor                  | 3         | 12.5%   |
| Sunplus Innovation Technology          | 2         | 8.33%   |
| Chicony Electronics                    | 2         | 8.33%   |
| Suyin                                  | 1         | 4.17%   |
| Microdia                               | 1         | 4.17%   |
| Lite-On Technology                     | 1         | 4.17%   |
| Google                                 | 1         | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 4.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Alcor Micro HD WebCam                                                      | 3         | 12%     |
| Apple Built-in iSight                                                      | 2         | 8%      |
| Acer SunplusIT INC. Integrated Camera                                      | 2         | 8%      |
| Suyin HP Wide Vision FHD Camera                                            | 1         | 4%      |
| Sunplus Integrated_Webcam_HD                                               | 1         | 4%      |
| Sunplus Integrated Camera                                                  | 1         | 4%      |
| Realtek Integrated_Webcam_HD                                               | 1         | 4%      |
| Realtek Integrated Webcam                                                  | 1         | 4%      |
| Realtek HP Truevision HD                                                   | 1         | 4%      |
| Microdia HP Webcam-101                                                     | 1         | 4%      |
| Lite-On Integrated Camera                                                  | 1         | 4%      |
| Chicony USB2.0 UVC WebCam                                                  | 1         | 4%      |
| Chicony HD User Facing                                                     | 1         | 4%      |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 1         | 4%      |
| Apple iPhone 5/5C/5S/6/SE                                                  | 1         | 4%      |
| Apple iBridge                                                              | 1         | 4%      |
| Apple FaceTime HD Camera (Built-in)                                        | 1         | 4%      |
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


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 3         | 60%     |
| Synaptics             | 1         | 20%     |
| LighTuning Technology | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor     | 3         | 60%     |
| Synaptics Metallica MOH Touch Fingerprint Reader | 1         | 20%     |
| LighTuning ES603 Swipe Fingerprint Sensor        | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Purism, SPC | 2         | 50%     |
| Clay Logic  | 1         | 25%     |
| Alcor Micro | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 18        | 48.65%  |
| 1     | 14        | 37.84%  |
| 2     | 3         | 8.11%   |
| 4     | 1         | 2.7%    |
| 3     | 1         | 2.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 8         | 29.63%  |
| Bluetooth             | 7         | 25.93%  |
| Fingerprint reader    | 5         | 18.52%  |
| Graphics card         | 4         | 14.81%  |
| Multimedia controller | 1         | 3.7%    |
| Chipcard              | 1         | 3.7%    |
| Camera                | 1         | 3.7%    |

