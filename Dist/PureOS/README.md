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

Total: 60

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [a6f87d56db](https://linux-hardware.org/?probe=a6f87d56db) | Jul 20, 2022 |
| Apple         | Mac-F2268DAE                | All in one  | [69bd504820](https://linux-hardware.org/?probe=69bd504820) | Jul 17, 2022 |
| LG Electro... | 22V280 FAB1                 | All in one  | [315403b304](https://linux-hardware.org/?probe=315403b304) | Jul 11, 2022 |
| PCWare        | IPX4005G                    | Desktop     | [2e447eb751](https://linux-hardware.org/?probe=2e447eb751) | Jul 09, 2022 |
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
| PureOS 10.0 | 13        | 30.95%  |
| PureOS 9.0  | 12        | 28.57%  |
| PureOS 10   | 12        | 28.57%  |
| PureOS 9    | 3         | 7.14%   |
| PureOS 8    | 2         | 4.76%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| PureOS | 41        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                          | Computers | Percent |
|----------------------------------|-----------|---------|
| 4.19.0-5-amd64                   | 9         | 20%     |
| 5.10.0-13-amd64                  | 5         | 11.11%  |
| 5.10.0-8-amd64                   | 4         | 8.89%   |
| 4.19.0-14-amd64                  | 4         | 8.89%   |
| 5.10.0-14-amd64                  | 3         | 6.67%   |
| 5.10.0-11-amd64                  | 3         | 6.67%   |
| 5.7.0-1-librem5                  | 2         | 4.44%   |
| 5.10.0-9-amd64                   | 2         | 4.44%   |
| 5.10.0-7-amd64                   | 2         | 4.44%   |
| 5.10.0-16-amd64                  | 2         | 4.44%   |
| 5.9-sunxi64                      | 1         | 2.22%   |
| 5.8-sunxi64                      | 1         | 2.22%   |
| 5.7.0-0.38-1-pinebookpro-hwaccel | 1         | 2.22%   |
| 5.15.0-2-amd64                   | 1         | 2.22%   |
| 5.10.0-6-amd64                   | 1         | 2.22%   |
| 5.10.0-15-amd64                  | 1         | 2.22%   |
| 5.10.0-12-amd64                  | 1         | 2.22%   |
| 4.19.72-imx8-sr                  | 1         | 2.22%   |
| 4.16.0-1-amd64                   | 1         | 2.22%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 22        | 51.16%  |
| 4.19.0  | 13        | 30.23%  |
| 5.7.0   | 3         | 6.98%   |
| 5.9     | 1         | 2.33%   |
| 5.8     | 1         | 2.33%   |
| 5.15.0  | 1         | 2.33%   |
| 4.19.72 | 1         | 2.33%   |
| 4.16.0  | 1         | 2.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 22        | 52.38%  |
| 4.19    | 14        | 33.33%  |
| 5.7     | 3         | 7.14%   |
| 5.15    | 1         | 2.38%   |
| 5       | 1         | 2.38%   |
| 4.16    | 1         | 2.38%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 36        | 87.8%   |
| aarch64 | 5         | 12.2%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 35        | 79.55%  |
| Unknown         | 6         | 13.64%  |
| MATE            | 1         | 2.27%   |
| KDE5            | 1         | 2.27%   |
| GNOME Flashback | 1         | 2.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 28        | 60.87%  |
| X11     | 8         | 17.39%  |
| Unknown | 6         | 13.04%  |
| Tty     | 4         | 8.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 26        | 63.41%  |
| GDM     | 11        | 26.83%  |
| GDM3    | 4         | 9.76%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 18        | 40.91%  |
| de_DE   | 5         | 11.36%  |
| Unknown | 4         | 9.09%   |
| en_GB   | 3         | 6.82%   |
| ru_RU   | 2         | 4.55%   |
| pt_BR   | 2         | 4.55%   |
| C       | 2         | 4.55%   |
| zh_CN   | 1         | 2.27%   |
| pt_PT   | 1         | 2.27%   |
| pl_PL   | 1         | 2.27%   |
| it_IT   | 1         | 2.27%   |
| es_CR   | 1         | 2.27%   |
| en_IL   | 1         | 2.27%   |
| en_AU   | 1         | 2.27%   |
| bg_BG   | 1         | 2.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 35        | 83.33%  |
| EFI  | 7         | 16.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 37        | 90.24%  |
| Unknown | 2         | 4.88%   |
| Overlay | 1         | 2.44%   |
| Ext2    | 1         | 2.44%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 24        | 55.81%  |
| MBR     | 11        | 25.58%  |
| GPT     | 8         | 18.6%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 34        | 82.93%  |
| Yes       | 7         | 17.07%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 37        | 90.24%  |
| Yes       | 4         | 9.76%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Purism              | 11        | 26.83%  |
| Lenovo              | 5         | 12.2%   |
| Apple               | 5         | 12.2%   |
| Hewlett-Packard     | 4         | 9.76%   |
| Dell                | 4         | 9.76%   |
| Pine Microsystems   | 2         | 4.88%   |
| ASUSTek Computer    | 2         | 4.88%   |
| Unknown             | 2         | 4.88%   |
| Toshiba             | 1         | 2.44%   |
| PCWare              | 1         | 2.44%   |
| Notebook            | 1         | 2.44%   |
| LG Electronics      | 1         | 2.44%   |
| Gigabyte Technology | 1         | 2.44%   |
| Acer                | 1         | 2.44%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Purism Librem 14                         | 5         | 12.2%   |
| Purism Librem 15 v4                      | 2         | 4.88%   |
| HP Pavilion g6                           | 2         | 4.88%   |
| Unknown                                  | 2         | 4.88%   |
| Toshiba Satellite L500D                  | 1         | 2.44%   |
| Purism Librem 5                          | 1         | 2.44%   |
| Purism Librem 15 v3                      | 1         | 2.44%   |
| Purism Librem 13 v4                      | 1         | 2.44%   |
| Purism Librem 13 v2                      | 1         | 2.44%   |
| Pine Microsystems Pine64 PinePhone (1.2) | 1         | 2.44%   |
| Pine Microsystems Pine64 Pinebook Pro    | 1         | 2.44%   |
| PCWare IPX4005G                          | 1         | 2.44%   |
| Notebook P17SM                           | 1         | 2.44%   |
| LG 22V280-L.BY31P1                       | 1         | 2.44%   |
| Lenovo ThinkPad T540p 20BFS23T00         | 1         | 2.44%   |
| Lenovo ThinkPad T440p                    | 1         | 2.44%   |
| Lenovo ThinkPad T440 20B60044RT          | 1         | 2.44%   |
| Lenovo ThinkPad E480 20KN003SUS          | 1         | 2.44%   |
| Lenovo ThinkPad 13 2nd Gen 20J2S00G00    | 1         | 2.44%   |
| HP Spectre x360 Convertible              | 1         | 2.44%   |
| HP Pavilion Notebook                     | 1         | 2.44%   |
| Gigabyte B85M-DS3H                       | 1         | 2.44%   |
| Dell XPS 13 9370                         | 1         | 2.44%   |
| Dell Inspiron 5547                       | 1         | 2.44%   |
| Dell Inspiron 3847                       | 1         | 2.44%   |
| Dell Inspiron 15-3567                    | 1         | 2.44%   |
| ASUS EX-A320M-GAMING                     | 1         | 2.44%   |
| ASUS A88X-PLUS/USB                       | 1         | 2.44%   |
| Apple MacBookPro6,1                      | 1         | 2.44%   |
| Apple MacBookPro14,2                     | 1         | 2.44%   |
| Apple iMac7,1                            | 1         | 2.44%   |
| Apple iMac13,1                           | 1         | 2.44%   |
| Apple iMac11,1                           | 1         | 2.44%   |
| Acer Nitro AN515-43                      | 1         | 2.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Purism Librem            | 11        | 26.83%  |
| Lenovo ThinkPad          | 5         | 12.2%   |
| HP Pavilion              | 3         | 7.32%   |
| Dell Inspiron            | 3         | 7.32%   |
| Pine Microsystems Pine64 | 2         | 4.88%   |
| Unknown                  | 2         | 4.88%   |
| Toshiba Satellite        | 1         | 2.44%   |
| PCWare IPX4005G          | 1         | 2.44%   |
| Notebook P17SM           | 1         | 2.44%   |
| LG 22V280-L.BY31P1       | 1         | 2.44%   |
| HP Spectre               | 1         | 2.44%   |
| Gigabyte B85M-DS3H       | 1         | 2.44%   |
| Dell XPS                 | 1         | 2.44%   |
| ASUS EX-A320M-GAMING     | 1         | 2.44%   |
| ASUS A88X-PLUS           | 1         | 2.44%   |
| Apple MacBookPro6        | 1         | 2.44%   |
| Apple MacBookPro14       | 1         | 2.44%   |
| Apple iMac7              | 1         | 2.44%   |
| Apple iMac13             | 1         | 2.44%   |
| Apple iMac11             | 1         | 2.44%   |
| Acer Nitro               | 1         | 2.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 6         | 14.63%  |
| 2018    | 5         | 12.2%   |
| 2013    | 5         | 12.2%   |
| Unknown | 5         | 12.2%   |
| 2019    | 4         | 9.76%   |
| 2017    | 4         | 9.76%   |
| 2015    | 3         | 7.32%   |
| 2016    | 2         | 4.88%   |
| 2011    | 2         | 4.88%   |
| 2020    | 1         | 2.44%   |
| 2014    | 1         | 2.44%   |
| 2010    | 1         | 2.44%   |
| 2009    | 1         | 2.44%   |
| 2007    | 1         | 2.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 28        | 68.29%  |
| Desktop        | 5         | 12.2%   |
| All in one     | 4         | 9.76%   |
| System on chip | 2         | 4.88%   |
| Phone          | 1         | 2.44%   |
| Convertible    | 1         | 2.44%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 41        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 30        | 73.17%  |
| Yes  | 11        | 26.83%  |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 10        | 24.39%  |
| 16.01-24.0 | 9         | 21.95%  |
| 3.01-4.0   | 7         | 17.07%  |
| 32.01-64.0 | 6         | 14.63%  |
| 4.01-8.0   | 5         | 12.2%   |
| 2.01-3.0   | 2         | 4.88%   |
| 24.01-32.0 | 1         | 2.44%   |
| 1.01-2.0   | 1         | 2.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 12        | 26.09%  |
| 3.01-4.0  | 11        | 23.91%  |
| 2.01-3.0  | 11        | 23.91%  |
| 4.01-8.0  | 8         | 17.39%  |
| 8.01-16.0 | 2         | 4.35%   |
| 0.51-1.0  | 1         | 2.17%   |
| 0.01-0.5  | 1         | 2.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 29        | 70.73%  |
| 2      | 11        | 26.83%  |
| 5      | 1         | 2.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 30        | 73.17%  |
| Yes       | 11        | 26.83%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 73.17%  |
| No        | 11        | 26.83%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 82.93%  |
| No        | 7         | 17.07%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 28        | 68.29%  |
| No        | 13        | 31.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 9         | 20.93%  |
| Germany                | 6         | 13.95%  |
| UK                     | 5         | 11.63%  |
| Brazil                 | 4         | 9.3%    |
| Canada                 | 3         | 6.98%   |
| Russia                 | 2         | 4.65%   |
| Australia              | 2         | 4.65%   |
| Turkey                 | 1         | 2.33%   |
| South Africa           | 1         | 2.33%   |
| Portugal               | 1         | 2.33%   |
| Poland                 | 1         | 2.33%   |
| Italy                  | 1         | 2.33%   |
| Israel                 | 1         | 2.33%   |
| Iran                   | 1         | 2.33%   |
| France                 | 1         | 2.33%   |
| Costa Rica             | 1         | 2.33%   |
| China                  | 1         | 2.33%   |
| Bulgaria               | 1         | 2.33%   |
| Bosnia and Herzegovina | 1         | 2.33%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Stuttgart          | 3         | 6.67%   |
| Porto Alegre       | 3         | 6.67%   |
| New York           | 2         | 4.44%   |
| London             | 2         | 4.44%   |
| Yuzhnoural'sk      | 1         | 2.22%   |
| Wixom              | 1         | 2.22%   |
| Windsor            | 1         | 2.22%   |
| Warsaw             | 1         | 2.22%   |
| Vancouver          | 1         | 2.22%   |
| Troy               | 1         | 2.22%   |
| Thorpe Hamlet      | 1         | 2.22%   |
| Tel Aviv           | 1         | 2.22%   |
| Spencer            | 1         | 2.22%   |
| Sofia              | 1         | 2.22%   |
| Seattle            | 1         | 2.22%   |
| San Jose           | 1         | 2.22%   |
| Paris              | 1         | 2.22%   |
| Montreal           | 1         | 2.22%   |
| Milwaukee          | 1         | 2.22%   |
| Melbourne          | 1         | 2.22%   |
| Liverpool          | 1         | 2.22%   |
| Leeds              | 1         | 2.22%   |
| Krasnogorsk        | 1         | 2.22%   |
| Istanbul           | 1         | 2.22%   |
| Guimaraes          | 1         | 2.22%   |
| Fort Collins       | 1         | 2.22%   |
| Eberswalde         | 1         | 2.22%   |
| Cape Town          | 1         | 2.22%   |
| Camden             | 1         | 2.22%   |
| Big Sky            | 1         | 2.22%   |
| Berlin             | 1         | 2.22%   |
| Banja Luka         | 1         | 2.22%   |
| Bandar-e Asalūyeh | 1         | 2.22%   |
| Balow              | 1         | 2.22%   |
| Araçatuba         | 1         | 2.22%   |
| Antioch            | 1         | 2.22%   |
| Ankang             | 1         | 2.22%   |
| Almese             | 1         | 2.22%   |
| Adelaide           | 1         | 2.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 15     | 21.57%  |
| Seagate             | 6         | 10     | 11.76%  |
| Unknown             | 5         | 9      | 9.8%    |
| WDC                 | 3         | 4      | 5.88%   |
| HGST                | 3         | 3      | 5.88%   |
| Apple               | 3         | 4      | 5.88%   |
| A-DATA Technology   | 3         | 4      | 5.88%   |
| SanDisk             | 2         | 2      | 3.92%   |
| Crucial             | 2         | 4      | 3.92%   |
| Win Memory          | 1         | 1      | 1.96%   |
| Transcend           | 1         | 1      | 1.96%   |
| Toshiba             | 1         | 1      | 1.96%   |
| Plextor             | 1         | 1      | 1.96%   |
| Phison              | 1         | 1      | 1.96%   |
| Patriot             | 1         | 1      | 1.96%   |
| Mushkin             | 1         | 1      | 1.96%   |
| JMicron Technology  | 1         | 1      | 1.96%   |
| Intel               | 1         | 1      | 1.96%   |
| Hitachi             | 1         | 1      | 1.96%   |
| BIWIN               | 1         | 1      | 1.96%   |
| ASMT                | 1         | 2      | 1.96%   |
| ADATA Technology    | 1         | 1      | 1.96%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST1000LM048-2E7172 1TB      | 2         | 3.57%   |
| Samsung SSD 970 PRO 1TB             | 2         | 3.57%   |
| Win Memory SWR256G-201II 256GB      | 1         | 1.79%   |
| WDC WDS100T2B0C-00PXH0 1TB          | 1         | 1.79%   |
| WDC WDBNCE2500PNC 250GB SSD         | 1         | 1.79%   |
| WDC WD3200AAJS-40RYA0 320GB         | 1         | 1.79%   |
| Unknown SH64G  64GB                 | 1         | 1.79%   |
| Unknown MMC Card  32GB              | 1         | 1.79%   |
| Unknown MMC Card  16GB              | 1         | 1.79%   |
| Unknown DA4128  128GB               | 1         | 1.79%   |
| Unknown AFGCF  128GB                | 1         | 1.79%   |
| Unknown 8GTF4R  8GB                 | 1         | 1.79%   |
| Unknown 032G32  32GB                | 1         | 1.79%   |
| Transcend TS240GMTS420S 240GB SSD   | 1         | 1.79%   |
| Toshiba NVMe SSD Drive 512GB        | 1         | 1.79%   |
| Seagate ST480HM000-1G5162 480GB     | 1         | 1.79%   |
| Seagate ST3320418AS 320GB           | 1         | 1.79%   |
| Seagate ST31000524AS 1TB            | 1         | 1.79%   |
| Seagate ST1000DM003-1ER162 1TB      | 1         | 1.79%   |
| Seagate NVMe SSD Drive 2TB          | 1         | 1.79%   |
| SanDisk SDSSDH3500G 500GB           | 1         | 1.79%   |
| SanDisk NVMe SSD Drive 500GB        | 1         | 1.79%   |
| Samsung SSD 970 EVO Plus 500GB      | 1         | 1.79%   |
| Samsung SSD 970 EVO 250GB           | 1         | 1.79%   |
| Samsung SSD 960 EVO 500GB           | 1         | 1.79%   |
| Samsung SSD 960 EVO 250GB           | 1         | 1.79%   |
| Samsung SSD 860 EVO 500GB           | 1         | 1.79%   |
| Samsung SSD 860 EVO 250GB           | 1         | 1.79%   |
| Samsung SSD 860 EVO 1TB             | 1         | 1.79%   |
| Samsung SSD 850 EVO 500GB           | 1         | 1.79%   |
| Samsung SSD 850 EVO 250GB           | 1         | 1.79%   |
| Samsung NVMe SSD Drive 1TB          | 1         | 1.79%   |
| Plextor PX-1TM6Pro 1024GB SSD       | 1         | 1.79%   |
| Phison PM8512GPTCB4B8TF-E13T4 512GB | 1         | 1.79%   |
| Patriot Burst Elite 120GB SSD       | 1         | 1.79%   |
| Mushkin MKNSSDRE250GB-LT            | 1         | 1.79%   |
| JMicron Generic 160GB               | 1         | 1.79%   |
| Intel SSDSC2BF180A4H 180GB          | 1         | 1.79%   |
| Hitachi HTS545050A7E380 500GB       | 1         | 1.79%   |
| HGST HTS721010A9E630 1TB            | 1         | 1.79%   |
| HGST HTS545050B7E660 500GB          | 1         | 1.79%   |
| HGST HTS541010A9E680 1TB            | 1         | 1.79%   |
| Crucial CT250MX500SSD4 250GB        | 1         | 1.79%   |
| Crucial CT2000MX500SSD1 2TB         | 1         | 1.79%   |
| BIWIN SSD 120GB                     | 1         | 1.79%   |
| ASMT 2235 160GB                     | 1         | 1.79%   |
| Apple NVMe SSD Drive 8KB            | 1         | 1.79%   |
| Apple NVMe SSD Drive 256GB          | 1         | 1.79%   |
| Apple HDD ST1000LM024 1TB           | 1         | 1.79%   |
| Apple HDD HUA722010CLA330 1TB       | 1         | 1.79%   |
| ADATA NVMe SSD Drive 512GB          | 1         | 1.79%   |
| A-DATA SU630 240GB SSD              | 1         | 1.79%   |
| A-DATA IM2S3138E-128GM-B 128GB SSD  | 1         | 1.79%   |
| A-DATA AXNS381E-256GM-B 256GB SSD   | 1         | 1.79%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 9      | 38.46%  |
| HGST    | 3         | 3      | 23.08%  |
| Apple   | 2         | 2      | 15.38%  |
| WDC     | 1         | 1      | 7.69%   |
| Hitachi | 1         | 1      | 7.69%   |
| ASMT    | 1         | 2      | 7.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 8      | 28.57%  |
| A-DATA Technology   | 3         | 4      | 14.29%  |
| Crucial             | 2         | 4      | 9.52%   |
| Win Memory          | 1         | 1      | 4.76%   |
| WDC                 | 1         | 2      | 4.76%   |
| Transcend           | 1         | 1      | 4.76%   |
| SanDisk             | 1         | 1      | 4.76%   |
| Plextor             | 1         | 1      | 4.76%   |
| Patriot             | 1         | 1      | 4.76%   |
| Mushkin             | 1         | 1      | 4.76%   |
| JMicron Technology  | 1         | 1      | 4.76%   |
| Intel               | 1         | 1      | 4.76%   |
| BIWIN               | 1         | 1      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 18        | 27     | 37.5%   |
| NVMe | 13        | 15     | 27.08%  |
| HDD  | 12        | 18     | 25%     |
| MMC  | 5         | 9      | 10.42%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 26        | 41     | 55.32%  |
| NVMe | 13        | 15     | 27.66%  |
| MMC  | 5         | 9      | 10.64%  |
| SAS  | 3         | 4      | 6.38%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 18        | 31     | 62.07%  |
| 0.51-1.0   | 9         | 11     | 31.03%  |
| 1.01-2.0   | 2         | 3      | 6.9%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 17        | 39.53%  |
| 251-500    | 6         | 13.95%  |
| 101-250    | 5         | 11.63%  |
| 501-1000   | 4         | 9.3%    |
| 21-50      | 3         | 6.98%   |
| Unknown    | 3         | 6.98%   |
| 1001-2000  | 2         | 4.65%   |
| 51-100     | 2         | 4.65%   |
| 2001-3000  | 1         | 2.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 23        | 53.49%  |
| 21-50    | 9         | 20.93%  |
| 101-250  | 3         | 6.98%   |
| 501-1000 | 3         | 6.98%   |
| Unknown  | 3         | 6.98%   |
| 251-500  | 1         | 2.33%   |
| 51-100   | 1         | 2.33%   |

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
| Detected | 29        | 50     | 65.91%  |
| Works    | 12        | 16     | 27.27%  |
| Malfunc  | 3         | 3      | 6.82%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 24        | 58.54%  |
| Samsung Electronics          | 6         | 14.63%  |
| AMD                          | 4         | 9.76%   |
| SanDisk                      | 2         | 4.88%   |
| Toshiba America Info Systems | 1         | 2.44%   |
| Seagate Technology           | 1         | 2.44%   |
| Phison Electronics           | 1         | 2.44%   |
| Apple                        | 1         | 2.44%   |
| ADATA Technology             | 1         | 2.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 16.28%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 11.63%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 9.3%    |
| AMD FCH SATA Controller [AHCI mode]                                            | 3         | 6.98%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 4.65%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 4.65%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 4.65%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 2.33%   |
| Seagate FireCuda 510 SSD                                                       | 1         | 2.33%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 1         | 2.33%   |
| SanDisk Non-Volatile memory controller                                         | 1         | 2.33%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 2.33%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 2.33%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 2.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 1         | 2.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 1         | 2.33%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1         | 2.33%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 2.33%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 2.33%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 2.33%   |
| Apple S3X NVMe Controller                                                      | 1         | 2.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 2.33%   |
| AMD FCH SATA Controller D                                                      | 1         | 2.33%   |
| ADATA Non-Volatile memory controller                                           | 1         | 2.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 27        | 65.85%  |
| NVMe | 13        | 31.71%  |
| IDE  | 1         | 2.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 32        | 78.05%  |
| ARM    | 5         | 12.2%   |
| AMD    | 4         | 9.76%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-10710U CPU @ 1.10GHz              | 5         | 12.2%   |
| ARM Processor                                   | 5         | 12.2%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 4         | 9.76%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 2         | 4.88%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 4.88%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 1         | 2.44%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 2.44%   |
| Intel Core i7-7567U CPU @ 3.50GHz               | 1         | 2.44%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz              | 1         | 2.44%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz              | 1         | 2.44%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz              | 1         | 2.44%   |
| Intel Core i7-4510U CPU @ 2.00GHz               | 1         | 2.44%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 1         | 2.44%   |
| Intel Core i5-4460 CPU @ 3.20GHz                | 1         | 2.44%   |
| Intel Core i5-3330S CPU @ 2.70GHz               | 1         | 2.44%   |
| Intel Core i5 CPU M 540 @ 2.53GHz               | 1         | 2.44%   |
| Intel Core i5 CPU 750 @ 2.67GHz                 | 1         | 2.44%   |
| Intel Core i3-4130T CPU @ 2.90GHz               | 1         | 2.44%   |
| Intel Core i3-4010U CPU @ 1.70GHz               | 1         | 2.44%   |
| Intel Core i3-3120M CPU @ 2.50GHz               | 1         | 2.44%   |
| Intel Core i3-2330M CPU @ 2.20GHz               | 1         | 2.44%   |
| Intel Core 2 Duo CPU T7700 @ 2.40GHz            | 1         | 2.44%   |
| Intel Celeron N4100 CPU @ 1.10GHz               | 1         | 2.44%   |
| Intel Celeron J4005 CPU @ 2.00GHz               | 1         | 2.44%   |
| AMD Turion II Dual-Core Mobile M520             | 1         | 2.44%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx   | 1         | 2.44%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics     | 1         | 2.44%   |
| AMD A10-7860K Radeon R7, 12 Compute Cores 4C+8G | 1         | 2.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 18        | 43.9%   |
| Intel Core i5           | 7         | 17.07%  |
| Other                   | 5         | 12.2%   |
| Intel Core i3           | 4         | 9.76%   |
| Intel Celeron           | 2         | 4.88%   |
| Intel Core 2 Duo        | 1         | 2.44%   |
| AMD Turion II Dual-Core | 1         | 2.44%   |
| AMD Ryzen 5             | 1         | 2.44%   |
| AMD Ryzen 3             | 1         | 2.44%   |
| AMD A10                 | 1         | 2.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 20        | 48.78%  |
| 4      | 16        | 39.02%  |
| 6      | 5         | 12.2%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 41        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 28        | 68.29%  |
| 1      | 13        | 31.71%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 38        | 90.48%  |
| Unknown        | 4         | 9.52%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 72.09%  |
| 0xa0660    | 3         | 6.98%   |
| 0x706a1    | 2         | 4.65%   |
| 0x406e3    | 2         | 4.65%   |
| 0x806e9    | 1         | 2.33%   |
| 0x40651    | 1         | 2.33%   |
| 0x306d4    | 1         | 2.33%   |
| 0x08108109 | 1         | 2.33%   |
| 0x06003106 | 1         | 2.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 9         | 21.95%  |
| Haswell       | 7         | 17.07%  |
| CometLake     | 5         | 12.2%   |
| Unknown       | 5         | 12.2%   |
| Zen+          | 2         | 4.88%   |
| Skylake       | 2         | 4.88%   |
| IvyBridge     | 2         | 4.88%   |
| Goldmont plus | 2         | 4.88%   |
| Westmere      | 1         | 2.44%   |
| Steamroller   | 1         | 2.44%   |
| SandyBridge   | 1         | 2.44%   |
| Nehalem       | 1         | 2.44%   |
| K10           | 1         | 2.44%   |
| Core          | 1         | 2.44%   |
| Broadwell     | 1         | 2.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 28        | 65.12%  |
| AMD    | 8         | 18.6%   |
| Nvidia | 7         | 16.28%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                 | 6         | 13.33%  |
| Intel Comet Lake UHD Graphics                                                         | 5         | 11.11%  |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 3         | 6.67%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 2         | 4.44%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 2         | 4.44%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 2         | 4.44%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 2         | 4.44%   |
| Nvidia GT216M [GeForce GT 330M]                                                       | 1         | 2.22%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 1         | 2.22%   |
| Nvidia GK208M [GeForce GT 730M]                                                       | 1         | 2.22%   |
| Nvidia GK208B [GeForce GT 710]                                                        | 1         | 2.22%   |
| Nvidia GK107M [GeForce GT 640M Mac Edition]                                           | 1         | 2.22%   |
| Nvidia GK104M [GeForce GTX 870M]                                                      | 1         | 2.22%   |
| Nvidia GF116 [GeForce GTS 450 Rev. 2]                                                 | 1         | 2.22%   |
| Nvidia GF108 [GeForce GT 630]                                                         | 1         | 2.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 1         | 2.22%   |
| Intel UHD Graphics 620                                                                | 1         | 2.22%   |
| Intel Iris Plus Graphics 650                                                          | 1         | 2.22%   |
| Intel HD Graphics 630                                                                 | 1         | 2.22%   |
| Intel HD Graphics 5500                                                                | 1         | 2.22%   |
| Intel Core Processor Integrated Graphics Controller                                   | 1         | 2.22%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 1         | 2.22%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 1         | 2.22%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 2.22%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                             | 1         | 2.22%   |
| AMD RV770/M98L [Mobility Radeon HD 4850]                                              | 1         | 2.22%   |
| AMD RV630/M76 [Mobility Radeon HD 2600 XT/2700]                                       | 1         | 2.22%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                             | 1         | 2.22%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                                    | 1         | 2.22%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                   | 1         | 2.22%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 21        | 51.22%  |
| Other          | 5         | 12.2%   |
| 1 x AMD        | 5         | 12.2%   |
| Intel + Nvidia | 4         | 9.76%   |
| 1 x Nvidia     | 3         | 7.32%   |
| Intel + AMD    | 2         | 4.88%   |
| 2 x AMD        | 1         | 2.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 34        | 82.93%  |
| Unknown | 7         | 17.07%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 40        | 95.24%  |
| 3.01-4.0   | 1         | 2.38%   |
| 0.51-1.0   | 1         | 2.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 6         | 13.64%  |
| LG Display              | 6         | 13.64%  |
| Chimei Innolux          | 6         | 13.64%  |
| BOE                     | 5         | 11.36%  |
| Apple                   | 4         | 9.09%   |
| Philips                 | 2         | 4.55%   |
| AU Optronics            | 2         | 4.55%   |
| Unknown                 | 1         | 2.27%   |
| Sharp                   | 1         | 2.27%   |
| RTK                     | 1         | 2.27%   |
| Lenovo                  | 1         | 2.27%   |
| Iiyama                  | 1         | 2.27%   |
| Grundig                 | 1         | 2.27%   |
| Goldstar                | 1         | 2.27%   |
| Dell                    | 1         | 2.27%   |
| Chi Mei Optoelectronics | 1         | 2.27%   |
| BenQ                    | 1         | 2.27%   |
| ASUSTek Computer        | 1         | 2.27%   |
| AOC                     | 1         | 2.27%   |
| Acer                    | 1         | 2.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC434B 3840x2160 344x194mm 15.5-inch     | 3         | 6.82%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 3         | 6.82%   |
| Philips TV PHL5035 1920x1080 640x360mm 28.9-inch                          | 2         | 4.55%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 1         | 2.27%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                   | 1         | 2.27%   |
| Samsung Electronics SyncMaster SAM01D3 1440x900 408x225mm 18.3-inch       | 1         | 2.27%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch      | 1         | 2.27%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch         | 1         | 2.27%   |
| RTK LG AIO FHD RTK2136 1920x1080 477x268mm 21.5-inch                      | 1         | 2.27%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch              | 1         | 2.27%   |
| LG Display LCD Monitor LGD053B 1920x1080 294x165mm 13.3-inch              | 1         | 2.27%   |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch              | 1         | 2.27%   |
| LG Display LCD Monitor LGD03F0 1366x768 310x174mm 14.0-inch               | 1         | 2.27%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch               | 1         | 2.27%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch               | 1         | 2.27%   |
| Lenovo LEN Y44w-10 LEN65EA 3840x1200 1052x329mm 43.4-inch                 | 1         | 2.27%   |
| Iiyama PL2792H IVM664F 1920x1080 598x336mm 27.0-inch                      | 1         | 2.27%   |
| Grundig WUXGA GRU4448 1920x1080 1210x680mm 54.6-inch                      | 1         | 2.27%   |
| Goldstar IPS231 GSM5817 1920x1080 510x290mm 23.1-inch                     | 1         | 2.27%   |
| Dell P2213 DELF042 1680x1050 473x296mm 22.0-inch                          | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch          | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN1415 1920x1080 309x173mm 13.9-inch          | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN1365 1920x1080 293x165mm 13.2-inch          | 1         | 2.27%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 2.27%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                     | 1         | 2.27%   |
| BOE LCD Monitor BOE079A 1920x1080 309x173mm 13.9-inch                     | 1         | 2.27%   |
| BOE LCD Monitor BOE06C2 1366x768 344x194mm 15.5-inch                      | 1         | 2.27%   |
| BOE LCD Monitor BOE06BE 1920x1080 294x165mm 13.3-inch                     | 1         | 2.27%   |
| BOE LCD Monitor BOE0641 1920x1080 344x193mm 15.5-inch                     | 1         | 2.27%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                         | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO713C 1366x768 309x173mm 13.9-inch             | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO10ED 1920x1080 344x193mm 15.5-inch            | 1         | 2.27%   |
| ASUSTek Computer VP249 AUS24AF 1920x1080 527x296mm 23.8-inch              | 1         | 2.27%   |
| Apple iMac APPA012 1920x1080 475x267mm 21.5-inch                          | 1         | 2.27%   |
| Apple Color LCD APPA034 2880x1800 286x179mm 13.3-inch                     | 1         | 2.27%   |
| Apple Color LCD APP9CCF 1920x1200 367x230mm 17.1-inch                     | 1         | 2.27%   |
| Apple Color LCD APP9C6B 1680x1050 430x270mm 20.0-inch                     | 1         | 2.27%   |
| AOC 2050 AOC2050 1600x900 443x249mm 20.0-inch                             | 1         | 2.27%   |
| Acer H236HL ACR0318 1920x1080 509x286mm 23.0-inch                         | 1         | 2.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 20        | 50%     |
| 3840x2160 (4K)     | 6         | 15%     |
| 1366x768 (WXGA)    | 6         | 15%     |
| 1680x1050 (WSXGA+) | 2         | 5%      |
| 3840x1200          | 1         | 2.5%    |
| 2880x1800          | 1         | 2.5%    |
| 2288x1287          | 1         | 2.5%    |
| 1920x1200 (WUXGA)  | 1         | 2.5%    |
| 1600x900 (HD+)     | 1         | 2.5%    |
| 1440x900 (WXGA+)   | 1         | 2.5%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 12        | 27.27%  |
| 13     | 11        | 25%     |
| 23     | 3         | 6.82%   |
| 28     | 2         | 4.55%   |
| 27     | 2         | 4.55%   |
| 24     | 2         | 4.55%   |
| 20     | 2         | 4.55%   |
| 17     | 2         | 4.55%   |
| 14     | 2         | 4.55%   |
| 142    | 1         | 2.27%   |
| 54     | 1         | 2.27%   |
| 43     | 1         | 2.27%   |
| 22     | 1         | 2.27%   |
| 21     | 1         | 2.27%   |
| 19     | 1         | 2.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 18        | 41.86%  |
| 501-600        | 7         | 16.28%  |
| 401-500        | 5         | 11.63%  |
| 201-300        | 5         | 11.63%  |
| 351-400        | 3         | 6.98%   |
| 601-700        | 2         | 4.65%   |
| 1001-1500      | 2         | 4.65%   |
| More than 2000 | 1         | 2.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 29        | 80.56%  |
| 16/10 | 5         | 13.89%  |
| 3.20  | 1         | 2.78%   |
| 1.00  | 1         | 2.78%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 12        | 27.27%  |
| 81-90          | 8         | 18.18%  |
| 201-250        | 7         | 15.91%  |
| 71-80          | 5         | 11.36%  |
| 151-200        | 3         | 6.82%   |
| More than 1000 | 2         | 4.55%   |
| 351-500        | 2         | 4.55%   |
| 301-350        | 2         | 4.55%   |
| 131-140        | 1         | 2.27%   |
| 121-130        | 1         | 2.27%   |
| 501-1000       | 1         | 2.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 16        | 36.36%  |
| 121-160       | 12        | 27.27%  |
| More than 240 | 6         | 13.64%  |
| 101-120       | 6         | 13.64%  |
| 161-240       | 3         | 6.82%   |
| 1-50          | 1         | 2.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 27        | 65.85%  |
| 2     | 8         | 19.51%  |
| 0     | 5         | 12.2%   |
| 3     | 1         | 2.44%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 22        | 36.07%  |
| Qualcomm Atheros                | 15        | 24.59%  |
| Intel                           | 8         | 13.11%  |
| Broadcom                        | 6         | 9.84%   |
| Broadcom Limited                | 2         | 3.28%   |
| ASIX Electronics                | 2         | 3.28%   |
| Ralink                          | 1         | 1.64%   |
| Qualcomm Atheros Communications | 1         | 1.64%   |
| MediaTek                        | 1         | 1.64%   |
| Marvell Technology Group        | 1         | 1.64%   |
| Edimax Technology               | 1         | 1.64%   |
| ASUSTek Computer                | 1         | 1.64%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 15        | 22.06%  |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 11        | 16.18%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 7.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 4.41%   |
| Intel Wireless 7265                                               | 3         | 4.41%   |
| Intel Wireless 7260                                               | 2         | 2.94%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 2.94%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 2.94%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 2.94%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 1.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 1.47%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1         | 1.47%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 1.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.47%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 1         | 1.47%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1         | 1.47%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 1.47%   |
| MediaTek WiFi                                                     | 1         | 1.47%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.47%   |
| Intel Wireless 8265 / 8275                                        | 1         | 1.47%   |
| Intel Ethernet Connection I218-V                                  | 1         | 1.47%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1         | 1.47%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                       | 1         | 1.47%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.47%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 1         | 1.47%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                            | 1         | 1.47%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1         | 1.47%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 1         | 1.47%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 1         | 1.47%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 1         | 1.47%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]         | 1         | 1.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 15        | 40.54%  |
| Intel                           | 7         | 18.92%  |
| Realtek Semiconductor           | 4         | 10.81%  |
| Broadcom                        | 4         | 10.81%  |
| Broadcom Limited                | 2         | 5.41%   |
| Ralink                          | 1         | 2.7%    |
| Qualcomm Atheros Communications | 1         | 2.7%    |
| MediaTek                        | 1         | 2.7%    |
| Edimax Technology               | 1         | 2.7%    |
| ASUSTek Computer                | 1         | 2.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 11        | 29.73%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 3         | 8.11%   |
| Intel Wireless 7265                                            | 3         | 8.11%   |
| Intel Wireless 7260                                            | 2         | 5.41%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 2.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 2.7%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1         | 2.7%    |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 2.7%    |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter         | 1         | 2.7%    |
| Qualcomm Atheros AR9271 802.11n                                | 1         | 2.7%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 2.7%    |
| MediaTek WiFi                                                  | 1         | 2.7%    |
| Intel Wireless 8265 / 8275                                     | 1         | 2.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 2.7%    |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                    | 1         | 2.7%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 1         | 2.7%    |
| Broadcom Limited BCM4331 802.11a/b/g/n                         | 1         | 2.7%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 1         | 2.7%    |
| Broadcom BCM43224 802.11a/b/g/n                                | 1         | 2.7%    |
| Broadcom BCM4321 802.11a/b/g/n                                 | 1         | 2.7%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 2.7%    |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]      | 1         | 2.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 20        | 66.67%  |
| Intel                    | 4         | 13.33%  |
| Broadcom                 | 3         | 10%     |
| ASIX Electronics         | 2         | 6.67%   |
| Marvell Technology Group | 1         | 3.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 15        | 48.39%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 16.13%  |
| Intel Ethernet Connection I217-LM                                 | 2         | 6.45%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 6.45%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 6.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 3.23%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 3.23%   |
| Intel Ethernet Connection I218-V                                  | 1         | 3.23%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 3.23%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 3.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 33        | 53.23%  |
| Ethernet | 29        | 46.77%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 21        | 58.33%  |
| WiFi     | 15        | 41.67%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 24        | 58.54%  |
| 1     | 11        | 26.83%  |
| 0     | 6         | 14.63%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 35        | 85.37%  |
| Yes  | 6         | 14.63%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 6         | 20.69%  |
| Qualcomm Atheros Communications | 5         | 17.24%  |
| Foxconn / Hon Hai               | 5         | 17.24%  |
| Apple                           | 5         | 17.24%  |
| Lite-On Technology              | 4         | 13.79%  |
| Realtek Semiconductor           | 1         | 3.45%   |
| Cambridge Silicon Radio         | 1         | 3.45%   |
| Broadcom                        | 1         | 3.45%   |
| ASUSTek Computer                | 1         | 3.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 5         | 17.24%  |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 17.24%  |
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 13.79%  |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 6.9%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 6.9%    |
| Apple Bluetooth USB Host Controller                 | 2         | 6.9%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 3.45%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 3.45%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 3.45%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.45%   |
| Broadcom HP Portable Valentine                      | 1         | 3.45%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 3.45%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 3.45%   |
| Apple Bluetooth Host Controller                     | 1         | 3.45%   |
| Apple Bluetooth HCI                                 | 1         | 3.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 31        | 65.96%  |
| AMD      | 6         | 12.77%  |
| Nvidia   | 5         | 10.64%  |
| XMOS     | 1         | 2.13%   |
| Shure    | 1         | 2.13%   |
| Micronas | 1         | 2.13%   |
| M-Audio  | 1         | 2.13%   |
| Logitech | 1         | 2.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 10        | 17.54%  |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 8.77%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 7.02%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 7.02%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 3.51%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 3.51%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 3.51%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 3.51%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 3.51%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 3.51%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 3.51%   |
| XMOS xDuoo USB Audio 2.0                                                   | 1         | 1.75%   |
| Shure MV5                                                                  | 1         | 1.75%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 1.75%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.75%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.75%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 1.75%   |
| Nvidia GF116 High Definition Audio Controller                              | 1         | 1.75%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.75%   |
| Micronas QSB                                                               | 1         | 1.75%   |
| M-Audio M-Audio Fast Track MKII                                            | 1         | 1.75%   |
| Logitech Headset H340                                                      | 1         | 1.75%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 1.75%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.75%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 1.75%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 1.75%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 1.75%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.75%   |
| AMD RV770 HDMI Audio [Radeon HD 4850/4870]                                 | 1         | 1.75%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 1.75%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 6         | 35.29%  |
| Crucial             | 4         | 23.53%  |
| Unknown             | 2         | 11.76%  |
| Toshiba             | 2         | 11.76%  |
| Samsung Electronics | 2         | 11.76%  |
| Smart               | 1         | 5.88%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 2         | 10.53%  |
| Crucial RAM CT16G4SFD824A.M16FRS 16GB SODIMM DDR4 2400MT/s       | 2         | 10.53%  |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 5.26%   |
| Unknown RAM Module 16384MB 2133MT/s                              | 1         | 5.26%   |
| Toshiba RAM 9905711-015.A00G 4GB SODIMM DDR4 2400MT/s            | 1         | 5.26%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s               | 1         | 5.26%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s                | 1         | 5.26%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s            | 1         | 5.26%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 5.26%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 5.26%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 5.26%   |
| SK hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s        | 1         | 5.26%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 5.26%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 5.26%   |
| SK hynix RAM H9CCNNNBLTALAR-NTD 4GB Row Of Chips LPDDR3 1600MT/s | 1         | 5.26%   |
| Crucial RAM CT4G4SFS8213.C8FBD1 4GB SODIMM DDR4 2133MT/s         | 1         | 5.26%   |
| Crucial RAM CT16G4S24AM.M16FE 16GB SODIMM DDR4 2400MT/s          | 1         | 5.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 9         | 60%     |
| DDR3    | 3         | 20%     |
| LPDDR3  | 1         | 6.67%   |
| DDR2    | 1         | 6.67%   |
| Unknown | 1         | 6.67%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 12        | 80%     |
| Row Of Chips | 1         | 6.67%   |
| DIMM         | 1         | 6.67%   |
| Unknown      | 1         | 6.67%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 8         | 47.06%  |
| 16384 | 4         | 23.53%  |
| 8192  | 3         | 17.65%  |
| 32768 | 2         | 11.76%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 5         | 29.41%  |
| 2400  | 4         | 23.53%  |
| 1600  | 4         | 23.53%  |
| 2133  | 2         | 11.76%  |
| 1333  | 1         | 5.88%   |
| 1066  | 1         | 5.88%   |

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
| Apple                                  | 5         | 18.52%  |
| Realtek Semiconductor                  | 4         | 14.81%  |
| Alcor Micro                            | 4         | 14.81%  |
| Acer                                   | 4         | 14.81%  |
| Chicony Electronics                    | 3         | 11.11%  |
| Sunplus Innovation Technology          | 2         | 7.41%   |
| Suyin                                  | 1         | 3.7%    |
| Microdia                               | 1         | 3.7%    |
| Lite-On Technology                     | 1         | 3.7%    |
| Google                                 | 1         | 3.7%    |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.7%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Apple Built-in iSight                                                      | 3         | 10.71%  |
| Alcor Micro HD WebCam                                                      | 3         | 10.71%  |
| Acer SunplusIT INC. Integrated Camera                                      | 2         | 7.14%   |
| Suyin HP TrueVision Full HD                                                | 1         | 3.57%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 3.57%   |
| Sunplus Integrated Camera                                                  | 1         | 3.57%   |
| Realtek USB2.0 camera                                                      | 1         | 3.57%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 3.57%   |
| Realtek Integrated Webcam                                                  | 1         | 3.57%   |
| Realtek HP Truevision HD                                                   | 1         | 3.57%   |
| Microdia HP Integrated Webcam                                              | 1         | 3.57%   |
| Lite-On Integrated Camera                                                  | 1         | 3.57%   |
| Chicony USB2.0 UVC WebCam                                                  | 1         | 3.57%   |
| Chicony LG HD WebCam                                                       | 1         | 3.57%   |
| Chicony HD User Facing                                                     | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 1         | 3.57%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 1         | 3.57%   |
| Apple iBridge                                                              | 1         | 3.57%   |
| Apple FaceTime HD Camera (Built-in)                                        | 1         | 3.57%   |
| Alcor Micro HP Webcam-101                                                  | 1         | 3.57%   |
| Acer SunplusIT Integrated Camera                                           | 1         | 3.57%   |
| Acer BisonCam, NB Pro                                                      | 1         | 3.57%   |
| Unknown                                                                    | 1         | 3.57%   |

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
| 0     | 22        | 52.38%  |
| 1     | 15        | 35.71%  |
| 2     | 3         | 7.14%   |
| 4     | 1         | 2.38%   |
| 3     | 1         | 2.38%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 8         | 28.57%  |
| Bluetooth             | 7         | 25%     |
| Graphics card         | 5         | 17.86%  |
| Fingerprint reader    | 5         | 17.86%  |
| Multimedia controller | 1         | 3.57%   |
| Chipcard              | 1         | 3.57%   |
| Camera                | 1         | 3.57%   |

