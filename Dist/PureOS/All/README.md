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

Total: 64

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Apple         | MacBook9,1                  | Notebook    | [e6898c8aa0](https://linux-hardware.org/?probe=e6898c8aa0) | Sep 19, 2022 |
| MSI           | H61M-P31                    | Desktop     | [56a8b0b2a7](https://linux-hardware.org/?probe=56a8b0b2a7) | Sep 08, 2022 |
| Acer          | Swift SF113-31              | Notebook    | [3c29601232](https://linux-hardware.org/?probe=3c29601232) | Sep 05, 2022 |
| Acer          | Swift SF113-31              | Notebook    | [f3753d28fb](https://linux-hardware.org/?probe=f3753d28fb) | Sep 05, 2022 |
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

![OS](./images/pie_chart/os_name.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| PureOS 10   | 15        | 33.33%  |
| PureOS 10.0 | 13        | 28.89%  |
| PureOS 9.0  | 12        | 26.67%  |
| PureOS 9    | 3         | 6.67%   |
| PureOS 8    | 2         | 4.44%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| PureOS | 44        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Computers | Percent |
|----------------------------------|-----------|---------|
| 4.19.0-5-amd64                   | 9         | 18.75%  |
| 5.10.0-14-amd64                  | 5         | 10.42%  |
| 5.10.0-13-amd64                  | 5         | 10.42%  |
| 5.10.0-8-amd64                   | 4         | 8.33%   |
| 4.19.0-14-amd64                  | 4         | 8.33%   |
| 5.10.0-11-amd64                  | 3         | 6.25%   |
| 5.7.0-1-librem5                  | 2         | 4.17%   |
| 5.10.0-9-amd64                   | 2         | 4.17%   |
| 5.10.0-7-amd64                   | 2         | 4.17%   |
| 5.10.0-16-amd64                  | 2         | 4.17%   |
| 5.9-sunxi64                      | 1         | 2.08%   |
| 5.8-sunxi64                      | 1         | 2.08%   |
| 5.7.0-0.38-1-pinebookpro-hwaccel | 1         | 2.08%   |
| 5.15.0-2-amd64                   | 1         | 2.08%   |
| 5.10.0-6-amd64                   | 1         | 2.08%   |
| 5.10.0-17-amd64                  | 1         | 2.08%   |
| 5.10.0-15-amd64                  | 1         | 2.08%   |
| 5.10.0-12-amd64                  | 1         | 2.08%   |
| 4.19.72-imx8-sr                  | 1         | 2.08%   |
| 4.16.0-1-amd64                   | 1         | 2.08%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 25        | 54.35%  |
| 4.19.0  | 13        | 28.26%  |
| 5.7.0   | 3         | 6.52%   |
| 5.9     | 1         | 2.17%   |
| 5.8     | 1         | 2.17%   |
| 5.15.0  | 1         | 2.17%   |
| 4.19.72 | 1         | 2.17%   |
| 4.16.0  | 1         | 2.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 25        | 55.56%  |
| 4.19    | 14        | 31.11%  |
| 5.7     | 3         | 6.67%   |
| 5.15    | 1         | 2.22%   |
| 5       | 1         | 2.22%   |
| 4.16    | 1         | 2.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 39        | 88.64%  |
| aarch64 | 5         | 11.36%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 38        | 80.85%  |
| Unknown         | 6         | 12.77%  |
| MATE            | 1         | 2.13%   |
| KDE5            | 1         | 2.13%   |
| GNOME Flashback | 1         | 2.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 31        | 63.27%  |
| X11     | 8         | 16.33%  |
| Unknown | 6         | 12.24%  |
| Tty     | 4         | 8.16%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 26        | 59.09%  |
| GDM     | 13        | 29.55%  |
| GDM3    | 5         | 11.36%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 19        | 40.43%  |
| de_DE   | 5         | 10.64%  |
| Unknown | 4         | 8.51%   |
| en_GB   | 3         | 6.38%   |
| ru_RU   | 2         | 4.26%   |
| pt_BR   | 2         | 4.26%   |
| pl_PL   | 2         | 4.26%   |
| it_IT   | 2         | 4.26%   |
| C       | 2         | 4.26%   |
| zh_CN   | 1         | 2.13%   |
| pt_PT   | 1         | 2.13%   |
| es_CR   | 1         | 2.13%   |
| en_IL   | 1         | 2.13%   |
| en_AU   | 1         | 2.13%   |
| bg_BG   | 1         | 2.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 37        | 82.22%  |
| EFI  | 8         | 17.78%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 40        | 90.91%  |
| Unknown | 2         | 4.55%   |
| Overlay | 1         | 2.27%   |
| Ext2    | 1         | 2.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 25        | 54.35%  |
| MBR     | 12        | 26.09%  |
| GPT     | 9         | 19.57%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 37        | 84.09%  |
| Yes       | 7         | 15.91%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 40        | 90.91%  |
| Yes       | 4         | 9.09%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Purism              | 11        | 25%     |
| Apple               | 6         | 13.64%  |
| Lenovo              | 5         | 11.36%  |
| Hewlett-Packard     | 4         | 9.09%   |
| Dell                | 4         | 9.09%   |
| Pine Microsystems   | 2         | 4.55%   |
| ASUSTek Computer    | 2         | 4.55%   |
| Acer                | 2         | 4.55%   |
| Unknown             | 2         | 4.55%   |
| Toshiba             | 1         | 2.27%   |
| PCWare              | 1         | 2.27%   |
| Notebook            | 1         | 2.27%   |
| MSI                 | 1         | 2.27%   |
| LG Electronics      | 1         | 2.27%   |
| Gigabyte Technology | 1         | 2.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Purism Librem 14                         | 5         | 11.36%  |
| Purism Librem 15 v4                      | 2         | 4.55%   |
| HP Pavilion g6                           | 2         | 4.55%   |
| Unknown                                  | 2         | 4.55%   |
| Toshiba Satellite L500D                  | 1         | 2.27%   |
| Purism Librem 5                          | 1         | 2.27%   |
| Purism Librem 15 v3                      | 1         | 2.27%   |
| Purism Librem 13 v4                      | 1         | 2.27%   |
| Purism Librem 13 v2                      | 1         | 2.27%   |
| Pine Microsystems Pine64 PinePhone (1.2) | 1         | 2.27%   |
| Pine Microsystems Pine64 Pinebook Pro    | 1         | 2.27%   |
| PCWare IPX4005G                          | 1         | 2.27%   |
| Notebook P17SM                           | 1         | 2.27%   |
| MSI MS-7788                              | 1         | 2.27%   |
| LG 22V280-L.BY31P1                       | 1         | 2.27%   |
| Lenovo ThinkPad T540p 20BFS23T00         | 1         | 2.27%   |
| Lenovo ThinkPad T440p                    | 1         | 2.27%   |
| Lenovo ThinkPad T440 20B60044RT          | 1         | 2.27%   |
| Lenovo ThinkPad E480 20KN003SUS          | 1         | 2.27%   |
| Lenovo ThinkPad 13 2nd Gen 20J2S00G00    | 1         | 2.27%   |
| HP Spectre x360 Convertible              | 1         | 2.27%   |
| HP Pavilion Notebook                     | 1         | 2.27%   |
| Gigabyte B85M-DS3H                       | 1         | 2.27%   |
| Dell XPS 13 9370                         | 1         | 2.27%   |
| Dell Inspiron 5547                       | 1         | 2.27%   |
| Dell Inspiron 3847                       | 1         | 2.27%   |
| Dell Inspiron 15-3567                    | 1         | 2.27%   |
| ASUS EX-A320M-GAMING                     | 1         | 2.27%   |
| ASUS A88X-PLUS/USB                       | 1         | 2.27%   |
| Apple MacBookPro6,1                      | 1         | 2.27%   |
| Apple MacBookPro14,2                     | 1         | 2.27%   |
| Apple MacBook9,1                         | 1         | 2.27%   |
| Apple iMac7,1                            | 1         | 2.27%   |
| Apple iMac13,1                           | 1         | 2.27%   |
| Apple iMac11,1                           | 1         | 2.27%   |
| Acer Swift SF113-31                      | 1         | 2.27%   |
| Acer Nitro AN515-43                      | 1         | 2.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Purism Librem            | 11        | 25%     |
| Lenovo ThinkPad          | 5         | 11.36%  |
| HP Pavilion              | 3         | 6.82%   |
| Dell Inspiron            | 3         | 6.82%   |
| Pine Microsystems Pine64 | 2         | 4.55%   |
| Unknown                  | 2         | 4.55%   |
| Toshiba Satellite        | 1         | 2.27%   |
| PCWare IPX4005G          | 1         | 2.27%   |
| Notebook P17SM           | 1         | 2.27%   |
| MSI MS-7788              | 1         | 2.27%   |
| LG 22V280-L.BY31P1       | 1         | 2.27%   |
| HP Spectre               | 1         | 2.27%   |
| Gigabyte B85M-DS3H       | 1         | 2.27%   |
| Dell XPS                 | 1         | 2.27%   |
| ASUS EX-A320M-GAMING     | 1         | 2.27%   |
| ASUS A88X-PLUS           | 1         | 2.27%   |
| Apple MacBookPro6        | 1         | 2.27%   |
| Apple MacBookPro14       | 1         | 2.27%   |
| Apple MacBook9           | 1         | 2.27%   |
| Apple iMac7              | 1         | 2.27%   |
| Apple iMac13             | 1         | 2.27%   |
| Apple iMac11             | 1         | 2.27%   |
| Acer Swift               | 1         | 2.27%   |
| Acer Nitro               | 1         | 2.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 6         | 13.64%  |
| 2018    | 5         | 11.36%  |
| 2017    | 5         | 11.36%  |
| 2013    | 5         | 11.36%  |
| Unknown | 5         | 11.36%  |
| 2019    | 4         | 9.09%   |
| 2015    | 3         | 6.82%   |
| 2011    | 3         | 6.82%   |
| 2020    | 2         | 4.55%   |
| 2016    | 2         | 4.55%   |
| 2014    | 1         | 2.27%   |
| 2010    | 1         | 2.27%   |
| 2009    | 1         | 2.27%   |
| 2007    | 1         | 2.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 30        | 68.18%  |
| Desktop        | 6         | 13.64%  |
| All in one     | 4         | 9.09%   |
| System on chip | 2         | 4.55%   |
| Phone          | 1         | 2.27%   |
| Convertible    | 1         | 2.27%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 44        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 33        | 75%     |
| Yes  | 11        | 25%     |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 10        | 22.73%  |
| 16.01-24.0 | 9         | 20.45%  |
| 3.01-4.0   | 8         | 18.18%  |
| 4.01-8.0   | 7         | 15.91%  |
| 32.01-64.0 | 6         | 13.64%  |
| 2.01-3.0   | 2         | 4.55%   |
| 24.01-32.0 | 1         | 2.27%   |
| 1.01-2.0   | 1         | 2.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 14        | 28.57%  |
| 1.01-2.0  | 12        | 24.49%  |
| 3.01-4.0  | 11        | 22.45%  |
| 4.01-8.0  | 8         | 16.33%  |
| 8.01-16.0 | 2         | 4.08%   |
| 0.51-1.0  | 1         | 2.04%   |
| 0.01-0.5  | 1         | 2.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 31        | 70.45%  |
| 2      | 12        | 27.27%  |
| 5      | 1         | 2.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 33        | 75%     |
| Yes       | 11        | 25%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 33        | 75%     |
| No        | 11        | 25%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 81.82%  |
| No        | 8         | 18.18%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 65.91%  |
| No        | 15        | 34.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 10        | 21.74%  |
| Germany                | 6         | 13.04%  |
| UK                     | 5         | 10.87%  |
| Brazil                 | 4         | 8.7%    |
| Canada                 | 3         | 6.52%   |
| Russia                 | 2         | 4.35%   |
| Poland                 | 2         | 4.35%   |
| Italy                  | 2         | 4.35%   |
| Australia              | 2         | 4.35%   |
| Turkey                 | 1         | 2.17%   |
| South Africa           | 1         | 2.17%   |
| Portugal               | 1         | 2.17%   |
| Israel                 | 1         | 2.17%   |
| Iran                   | 1         | 2.17%   |
| France                 | 1         | 2.17%   |
| Costa Rica             | 1         | 2.17%   |
| China                  | 1         | 2.17%   |
| Bulgaria               | 1         | 2.17%   |
| Bosnia and Herzegovina | 1         | 2.17%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Stuttgart          | 3         | 6.25%   |
| Porto Alegre       | 3         | 6.25%   |
| Warsaw             | 2         | 4.17%   |
| New York           | 2         | 4.17%   |
| London             | 2         | 4.17%   |
| Yuzhnoural'sk      | 1         | 2.08%   |
| Wixom              | 1         | 2.08%   |
| Windsor            | 1         | 2.08%   |
| Vancouver          | 1         | 2.08%   |
| Troy               | 1         | 2.08%   |
| Thorpe Hamlet      | 1         | 2.08%   |
| Tel Aviv           | 1         | 2.08%   |
| Spencer            | 1         | 2.08%   |
| Sofia              | 1         | 2.08%   |
| Seattle            | 1         | 2.08%   |
| San Jose           | 1         | 2.08%   |
| Paris              | 1         | 2.08%   |
| Montreal           | 1         | 2.08%   |
| Milwaukee          | 1         | 2.08%   |
| Milan              | 1         | 2.08%   |
| Melbourne          | 1         | 2.08%   |
| Mankato            | 1         | 2.08%   |
| Liverpool          | 1         | 2.08%   |
| Leeds              | 1         | 2.08%   |
| Krasnogorsk        | 1         | 2.08%   |
| Istanbul           | 1         | 2.08%   |
| Guimaraes          | 1         | 2.08%   |
| Fort Collins       | 1         | 2.08%   |
| Eberswalde         | 1         | 2.08%   |
| Cape Town          | 1         | 2.08%   |
| Camden             | 1         | 2.08%   |
| Big Sky            | 1         | 2.08%   |
| Berlin             | 1         | 2.08%   |
| Banja Luka         | 1         | 2.08%   |
| Bandar-e Asalūyeh | 1         | 2.08%   |
| Balow              | 1         | 2.08%   |
| Araçatuba         | 1         | 2.08%   |
| Antioch            | 1         | 2.08%   |
| Ankang             | 1         | 2.08%   |
| Almese             | 1         | 2.08%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 15     | 20.37%  |
| Unknown             | 6         | 10     | 11.11%  |
| Seagate             | 6         | 10     | 11.11%  |
| WDC                 | 4         | 5      | 7.41%   |
| Apple               | 4         | 6      | 7.41%   |
| HGST                | 3         | 3      | 5.56%   |
| A-DATA Technology   | 3         | 4      | 5.56%   |
| SanDisk             | 2         | 2      | 3.7%    |
| Crucial             | 2         | 4      | 3.7%    |
| Win Memory          | 1         | 1      | 1.85%   |
| Transcend           | 1         | 1      | 1.85%   |
| Toshiba             | 1         | 1      | 1.85%   |
| Plextor             | 1         | 1      | 1.85%   |
| Phison              | 1         | 1      | 1.85%   |
| Patriot             | 1         | 1      | 1.85%   |
| Mushkin             | 1         | 1      | 1.85%   |
| JMicron Technology  | 1         | 1      | 1.85%   |
| Intel               | 1         | 1      | 1.85%   |
| Hitachi             | 1         | 1      | 1.85%   |
| BIWIN               | 1         | 1      | 1.85%   |
| ASMT                | 1         | 2      | 1.85%   |
| ADATA Technology    | 1         | 1      | 1.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST1000LM048-2E7172 1TB      | 2         | 3.39%   |
| Samsung SSD 970 PRO 1TB             | 2         | 3.39%   |
| Win Memory SWR256G-201II 256GB      | 1         | 1.69%   |
| WDC WDS100T2B0C-00PXH0 1TB          | 1         | 1.69%   |
| WDC WDBNCE2500PNC 250GB SSD         | 1         | 1.69%   |
| WDC WD5000AZRX-00A8LB0 500GB        | 1         | 1.69%   |
| WDC WD3200AAJS-40RYA0 320GB         | 1         | 1.69%   |
| Unknown SH64G  64GB                 | 1         | 1.69%   |
| Unknown MMC Card  64GB              | 1         | 1.69%   |
| Unknown MMC Card  32GB              | 1         | 1.69%   |
| Unknown MMC Card  16GB              | 1         | 1.69%   |
| Unknown DA4128  128GB               | 1         | 1.69%   |
| Unknown AFGCF  128GB                | 1         | 1.69%   |
| Unknown 8GTF4R  8GB                 | 1         | 1.69%   |
| Unknown 032G32  32GB                | 1         | 1.69%   |
| Transcend TS240GMTS420S 240GB SSD   | 1         | 1.69%   |
| Toshiba NVMe SSD Drive 512GB        | 1         | 1.69%   |
| Seagate ST480HM000-1G5162 480GB     | 1         | 1.69%   |
| Seagate ST3320418AS 320GB           | 1         | 1.69%   |
| Seagate ST31000524AS 1TB            | 1         | 1.69%   |
| Seagate ST1000DM003-1ER162 1TB      | 1         | 1.69%   |
| Seagate NVMe SSD Drive 2TB          | 1         | 1.69%   |
| SanDisk SDSSDH3500G 500GB           | 1         | 1.69%   |
| SanDisk NVMe SSD Drive 500GB        | 1         | 1.69%   |
| Samsung SSD 970 EVO Plus 500GB      | 1         | 1.69%   |
| Samsung SSD 970 EVO 250GB           | 1         | 1.69%   |
| Samsung SSD 960 EVO 500GB           | 1         | 1.69%   |
| Samsung SSD 960 EVO 250GB           | 1         | 1.69%   |
| Samsung SSD 860 EVO 500GB           | 1         | 1.69%   |
| Samsung SSD 860 EVO 250GB           | 1         | 1.69%   |
| Samsung SSD 860 EVO 1TB             | 1         | 1.69%   |
| Samsung SSD 850 EVO 500GB           | 1         | 1.69%   |
| Samsung SSD 850 EVO 250GB           | 1         | 1.69%   |
| Samsung NVMe SSD Drive 1TB          | 1         | 1.69%   |
| Plextor PX-1TM6Pro 1024GB SSD       | 1         | 1.69%   |
| Phison PM8512GPTCB4B8TF-E13T4 512GB | 1         | 1.69%   |
| Patriot Burst Elite 120GB SSD       | 1         | 1.69%   |
| Mushkin MKNSSDRE250GB-LT            | 1         | 1.69%   |
| JMicron Generic 120GB               | 1         | 1.69%   |
| Intel SSDSC2BF180A4H 180GB          | 1         | 1.69%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 9      | 35.71%  |
| HGST    | 3         | 3      | 21.43%  |
| WDC     | 2         | 2      | 14.29%  |
| Apple   | 2         | 2      | 14.29%  |
| Hitachi | 1         | 1      | 7.14%   |
| ASMT    | 1         | 2      | 7.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 8      | 30%     |
| A-DATA Technology   | 3         | 4      | 15%     |
| Crucial             | 2         | 4      | 10%     |
| Win Memory          | 1         | 1      | 5%      |
| WDC                 | 1         | 2      | 5%      |
| Transcend           | 1         | 1      | 5%      |
| SanDisk             | 1         | 1      | 5%      |
| Plextor             | 1         | 1      | 5%      |
| Patriot             | 1         | 1      | 5%      |
| Mushkin             | 1         | 1      | 5%      |
| Intel               | 1         | 1      | 5%      |
| BIWIN               | 1         | 1      | 5%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 18        | 26     | 34.62%  |
| NVMe | 15        | 18     | 28.85%  |
| HDD  | 13        | 19     | 25%     |
| MMC  | 6         | 10     | 11.54%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 27        | 42     | 54%     |
| NVMe | 14        | 17     | 28%     |
| MMC  | 6         | 10     | 12%     |
| SAS  | 3         | 4      | 6%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 19        | 31     | 63.33%  |
| 0.51-1.0   | 9         | 11     | 30%     |
| 1.01-2.0   | 2         | 3      | 6.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 20        | 43.48%  |
| 251-500    | 6         | 13.04%  |
| 101-250    | 5         | 10.87%  |
| 501-1000   | 4         | 8.7%    |
| 21-50      | 3         | 6.52%   |
| Unknown    | 3         | 6.52%   |
| 1001-2000  | 2         | 4.35%   |
| 51-100     | 2         | 4.35%   |
| 2001-3000  | 1         | 2.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 26        | 56.52%  |
| 21-50    | 9         | 19.57%  |
| 101-250  | 3         | 6.52%   |
| 501-1000 | 3         | 6.52%   |
| Unknown  | 3         | 6.52%   |
| 251-500  | 1         | 2.17%   |
| 51-100   | 1         | 2.17%   |

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
| Detected | 30        | 51     | 63.83%  |
| Works    | 14        | 19     | 29.79%  |
| Malfunc  | 3         | 3      | 6.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 26        | 59.09%  |
| Samsung Electronics          | 6         | 13.64%  |
| AMD                          | 4         | 9.09%   |
| SanDisk                      | 2         | 4.55%   |
| Apple                        | 2         | 4.55%   |
| Toshiba America Info Systems | 1         | 2.27%   |
| Seagate Technology           | 1         | 2.27%   |
| Phison Electronics           | 1         | 2.27%   |
| ADATA Technology             | 1         | 2.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 15.22%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 10.87%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 8.7%    |
| AMD FCH SATA Controller [AHCI mode]                                            | 3         | 6.52%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 4.35%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 4.35%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 4.35%   |
| Apple S3X NVMe Controller                                                      | 2         | 4.35%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 2.17%   |
| Seagate FireCuda 510 SSD                                                       | 1         | 2.17%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 1         | 2.17%   |
| SanDisk Non-Volatile memory controller                                         | 1         | 2.17%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 2.17%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 2.17%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 2.17%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 2.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 1         | 2.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 1         | 2.17%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1         | 2.17%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1         | 2.17%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 2.17%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 2.17%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 2.17%   |
| AMD FCH SATA Controller D                                                      | 1         | 2.17%   |
| ADATA Non-Volatile memory controller                                           | 1         | 2.17%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 29        | 65.91%  |
| NVMe | 14        | 31.82%  |
| IDE  | 1         | 2.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 35        | 79.55%  |
| ARM    | 5         | 11.36%  |
| AMD    | 4         | 9.09%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-10710U CPU @ 1.10GHz              | 5         | 11.36%  |
| ARM Processor                                   | 5         | 11.36%  |
| Intel Core i7-7500U CPU @ 2.70GHz               | 4         | 9.09%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 2         | 4.55%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 4.55%   |
| Intel Pentium CPU N4200 @ 1.10GHz               | 1         | 2.27%   |
| Intel Core m5-6Y54 CPU @ 1.10GHz                | 1         | 2.27%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 1         | 2.27%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 2.27%   |
| Intel Core i7-7567U CPU @ 3.50GHz               | 1         | 2.27%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz              | 1         | 2.27%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz              | 1         | 2.27%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz              | 1         | 2.27%   |
| Intel Core i7-4510U CPU @ 2.00GHz               | 1         | 2.27%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 1         | 2.27%   |
| Intel Core i5-4460 CPU @ 3.20GHz                | 1         | 2.27%   |
| Intel Core i5-3330S CPU @ 2.70GHz               | 1         | 2.27%   |
| Intel Core i5-2320 CPU @ 3.00GHz                | 1         | 2.27%   |
| Intel Core i5 CPU M 540 @ 2.53GHz               | 1         | 2.27%   |
| Intel Core i5 CPU 750 @ 2.67GHz                 | 1         | 2.27%   |
| Intel Core i3-4130T CPU @ 2.90GHz               | 1         | 2.27%   |
| Intel Core i3-4010U CPU @ 1.70GHz               | 1         | 2.27%   |
| Intel Core i3-3120M CPU @ 2.50GHz               | 1         | 2.27%   |
| Intel Core i3-2330M CPU @ 2.20GHz               | 1         | 2.27%   |
| Intel Core 2 Duo CPU T7700 @ 2.40GHz            | 1         | 2.27%   |
| Intel Celeron N4100 CPU @ 1.10GHz               | 1         | 2.27%   |
| Intel Celeron J4005 CPU @ 2.00GHz               | 1         | 2.27%   |
| AMD Turion II Dual-Core Mobile M520             | 1         | 2.27%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx   | 1         | 2.27%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics     | 1         | 2.27%   |
| AMD A10-7860K Radeon R7, 12 Compute Cores 4C+8G | 1         | 2.27%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 18        | 40.91%  |
| Intel Core i5           | 8         | 18.18%  |
| Other                   | 5         | 11.36%  |
| Intel Core i3           | 4         | 9.09%   |
| Intel Celeron           | 2         | 4.55%   |
| Intel Pentium           | 1         | 2.27%   |
| Intel Core m5           | 1         | 2.27%   |
| Intel Core 2 Duo        | 1         | 2.27%   |
| AMD Turion II Dual-Core | 1         | 2.27%   |
| AMD Ryzen 5             | 1         | 2.27%   |
| AMD Ryzen 3             | 1         | 2.27%   |
| AMD A10                 | 1         | 2.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 21        | 47.73%  |
| 4      | 18        | 40.91%  |
| 6      | 5         | 11.36%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 44        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 29        | 65.91%  |
| 1      | 15        | 34.09%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 41        | 91.11%  |
| Unknown        | 4         | 8.89%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 32        | 69.57%  |
| 0xa0660    | 3         | 6.52%   |
| 0x406e3    | 3         | 6.52%   |
| 0x706a1    | 2         | 4.35%   |
| 0x806e9    | 1         | 2.17%   |
| 0x40651    | 1         | 2.17%   |
| 0x306d4    | 1         | 2.17%   |
| 0x206a7    | 1         | 2.17%   |
| 0x08108109 | 1         | 2.17%   |
| 0x06003106 | 1         | 2.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 9         | 20.45%  |
| Haswell       | 7         | 15.91%  |
| CometLake     | 5         | 11.36%  |
| Unknown       | 5         | 11.36%  |
| Skylake       | 3         | 6.82%   |
| Zen+          | 2         | 4.55%   |
| SandyBridge   | 2         | 4.55%   |
| IvyBridge     | 2         | 4.55%   |
| Goldmont plus | 2         | 4.55%   |
| Westmere      | 1         | 2.27%   |
| Steamroller   | 1         | 2.27%   |
| Nehalem       | 1         | 2.27%   |
| K10           | 1         | 2.27%   |
| Goldmont      | 1         | 2.27%   |
| Core          | 1         | 2.27%   |
| Broadwell     | 1         | 2.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 31        | 67.39%  |
| AMD    | 8         | 17.39%  |
| Nvidia | 7         | 15.22%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                 | 6         | 12.5%   |
| Intel Comet Lake UHD Graphics                                                         | 5         | 10.42%  |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 3         | 6.25%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 2         | 4.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 2         | 4.17%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 2         | 4.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 2         | 4.17%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 2         | 4.17%   |
| Nvidia GT216M [GeForce GT 330M]                                                       | 1         | 2.08%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 1         | 2.08%   |
| Nvidia GK208M [GeForce GT 730M]                                                       | 1         | 2.08%   |
| Nvidia GK208B [GeForce GT 710]                                                        | 1         | 2.08%   |
| Nvidia GK107M [GeForce GT 640M Mac Edition]                                           | 1         | 2.08%   |
| Nvidia GK104M [GeForce GTX 870M]                                                      | 1         | 2.08%   |
| Nvidia GF116 [GeForce GTS 450 Rev. 2]                                                 | 1         | 2.08%   |
| Nvidia GF108 [GeForce GT 630]                                                         | 1         | 2.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 1         | 2.08%   |
| Intel UHD Graphics 620                                                                | 1         | 2.08%   |
| Intel Iris Plus Graphics 650                                                          | 1         | 2.08%   |
| Intel HD Graphics 630                                                                 | 1         | 2.08%   |
| Intel HD Graphics 5500                                                                | 1         | 2.08%   |
| Intel HD Graphics 515                                                                 | 1         | 2.08%   |
| Intel Core Processor Integrated Graphics Controller                                   | 1         | 2.08%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller    | 1         | 2.08%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 1         | 2.08%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 2.08%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                             | 1         | 2.08%   |
| AMD RV770/M98L [Mobility Radeon HD 4850]                                              | 1         | 2.08%   |
| AMD RV630/M76 [Mobility Radeon HD 2600 XT/2700]                                       | 1         | 2.08%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                             | 1         | 2.08%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                                    | 1         | 2.08%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                   | 1         | 2.08%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 24        | 54.55%  |
| Other          | 5         | 11.36%  |
| 1 x AMD        | 5         | 11.36%  |
| Intel + Nvidia | 4         | 9.09%   |
| 1 x Nvidia     | 3         | 6.82%   |
| Intel + AMD    | 2         | 4.55%   |
| 2 x AMD        | 1         | 2.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 37        | 84.09%  |
| Unknown | 7         | 15.91%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 43        | 95.56%  |
| 3.01-4.0   | 1         | 2.22%   |
| 0.51-1.0   | 1         | 2.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 6         | 12.77%  |
| LG Display              | 6         | 12.77%  |
| Chimei Innolux          | 6         | 12.77%  |
| BOE                     | 5         | 10.64%  |
| Apple                   | 5         | 10.64%  |
| Philips                 | 2         | 4.26%   |
| Goldstar                | 2         | 4.26%   |
| AU Optronics            | 2         | 4.26%   |
| Unknown                 | 1         | 2.13%   |
| Sharp                   | 1         | 2.13%   |
| RTK                     | 1         | 2.13%   |
| PANDA                   | 1         | 2.13%   |
| Lenovo                  | 1         | 2.13%   |
| Iiyama                  | 1         | 2.13%   |
| Grundig                 | 1         | 2.13%   |
| Dell                    | 1         | 2.13%   |
| Chi Mei Optoelectronics | 1         | 2.13%   |
| BenQ                    | 1         | 2.13%   |
| ASUSTek Computer        | 1         | 2.13%   |
| AOC                     | 1         | 2.13%   |
| Acer                    | 1         | 2.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC434B 3840x2160 344x194mm 15.5-inch     | 3         | 6.38%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 3         | 6.38%   |
| Philips TV PHL5035 1920x1080 640x360mm 28.9-inch                          | 2         | 4.26%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 1         | 2.13%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                   | 1         | 2.13%   |
| Samsung Electronics SyncMaster SAM01D3 1440x900 408x225mm 18.3-inch       | 1         | 2.13%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch      | 1         | 2.13%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch         | 1         | 2.13%   |
| RTK LCD Monitor RTK2136 1366x768 473x296mm 22.0-inch                      | 1         | 2.13%   |
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch                   | 1         | 2.13%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch              | 1         | 2.13%   |
| LG Display LCD Monitor LGD053B 1920x1080 294x165mm 13.3-inch              | 1         | 2.13%   |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch              | 1         | 2.13%   |
| LG Display LCD Monitor LGD03F0 1366x768 310x174mm 14.0-inch               | 1         | 2.13%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch               | 1         | 2.13%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch               | 1         | 2.13%   |
| Lenovo LEN Y44w-10 LEN65EA 3840x1200 1052x329mm 43.4-inch                 | 1         | 2.13%   |
| Iiyama PL2792H IVM664F 1920x1080 600x340mm 27.2-inch                      | 1         | 2.13%   |
| Grundig TV GRU4448 1920x1080 1210x680mm 54.6-inch                         | 1         | 2.13%   |
| Goldstar IPS231 GSM5817 1920x1080 510x290mm 23.1-inch                     | 1         | 2.13%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                    | 1         | 2.13%   |
| Dell P2213 DELF042 1680x1050 473x296mm 22.0-inch                          | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch          | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN1415 1920x1080 309x173mm 13.9-inch          | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN1365 1920x1080 293x165mm 13.2-inch          | 1         | 2.13%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 2.13%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                     | 1         | 2.13%   |
| BOE LCD Monitor BOE079A 1920x1080 309x173mm 13.9-inch                     | 1         | 2.13%   |
| BOE LCD Monitor BOE06C2 1366x768 344x194mm 15.5-inch                      | 1         | 2.13%   |
| BOE LCD Monitor BOE06BE 1920x1080 294x165mm 13.3-inch                     | 1         | 2.13%   |
| BOE LCD Monitor BOE0641 1920x1080 344x193mm 15.5-inch                     | 1         | 2.13%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                         | 1         | 2.13%   |
| AU Optronics LCD Monitor AUO713C 1366x768 309x173mm 13.9-inch             | 1         | 2.13%   |
| AU Optronics LCD Monitor AUO10ED 1920x1080 344x193mm 15.5-inch            | 1         | 2.13%   |
| ASUSTek Computer VP249 AUS24AF 1920x1080 527x296mm 23.8-inch              | 1         | 2.13%   |
| Apple iMac APPA012 1920x1080 475x267mm 21.5-inch                          | 1         | 2.13%   |
| Apple Color LCD APPA034 2880x1800 286x179mm 13.3-inch                     | 1         | 2.13%   |
| Apple Color LCD APPA027 2304x1440 259x162mm 12.0-inch                     | 1         | 2.13%   |
| Apple Color LCD APP9CCF 1920x1200 367x230mm 17.1-inch                     | 1         | 2.13%   |
| Apple Color LCD APP9C6B 1680x1050 433x270mm 20.1-inch                     | 1         | 2.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 22        | 51.16%  |
| 3840x2160 (4K)     | 6         | 13.95%  |
| 1366x768 (WXGA)    | 6         | 13.95%  |
| 1680x1050 (WSXGA+) | 2         | 4.65%   |
| 3840x1200          | 1         | 2.33%   |
| 2880x1800          | 1         | 2.33%   |
| 2304x1440          | 1         | 2.33%   |
| 2288x1287          | 1         | 2.33%   |
| 1920x1200 (WUXGA)  | 1         | 2.33%   |
| 1600x900 (HD+)     | 1         | 2.33%   |
| 1440x900 (WXGA+)   | 1         | 2.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 12        | 25.53%  |
| 13     | 12        | 25.53%  |
| 23     | 3         | 6.38%   |
| 28     | 2         | 4.26%   |
| 27     | 2         | 4.26%   |
| 24     | 2         | 4.26%   |
| 21     | 2         | 4.26%   |
| 20     | 2         | 4.26%   |
| 17     | 2         | 4.26%   |
| 14     | 2         | 4.26%   |
| 142    | 1         | 2.13%   |
| 54     | 1         | 2.13%   |
| 43     | 1         | 2.13%   |
| 22     | 1         | 2.13%   |
| 19     | 1         | 2.13%   |
| 12     | 1         | 2.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 18        | 39.13%  |
| 501-600        | 7         | 15.22%  |
| 201-300        | 7         | 15.22%  |
| 401-500        | 6         | 13.04%  |
| 351-400        | 3         | 6.52%   |
| 601-700        | 2         | 4.35%   |
| 1001-1500      | 2         | 4.35%   |
| More than 2000 | 1         | 2.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 31        | 79.49%  |
| 16/10 | 6         | 15.38%  |
| 3.20  | 1         | 2.56%   |
| 1.00  | 1         | 2.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 12        | 25.53%  |
| 81-90          | 8         | 17.02%  |
| 201-250        | 8         | 17.02%  |
| 71-80          | 6         | 12.77%  |
| 151-200        | 3         | 6.38%   |
| More than 1000 | 2         | 4.26%   |
| 351-500        | 2         | 4.26%   |
| 301-350        | 2         | 4.26%   |
| 61-70          | 1         | 2.13%   |
| 131-140        | 1         | 2.13%   |
| 121-130        | 1         | 2.13%   |
| 501-1000       | 1         | 2.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 16        | 34.04%  |
| 121-160       | 12        | 25.53%  |
| 101-120       | 7         | 14.89%  |
| More than 240 | 6         | 12.77%  |
| 161-240       | 5         | 10.64%  |
| 1-50          | 1         | 2.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 30        | 68.18%  |
| 2     | 8         | 18.18%  |
| 0     | 5         | 11.36%  |
| 3     | 1         | 2.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 24        | 36.92%  |
| Qualcomm Atheros                | 15        | 23.08%  |
| Intel                           | 9         | 13.85%  |
| Broadcom                        | 7         | 10.77%  |
| Broadcom Limited                | 2         | 3.08%   |
| ASIX Electronics                | 2         | 3.08%   |
| Ralink                          | 1         | 1.54%   |
| Qualcomm Atheros Communications | 1         | 1.54%   |
| MediaTek                        | 1         | 1.54%   |
| Marvell Technology Group        | 1         | 1.54%   |
| Edimax Technology               | 1         | 1.54%   |
| ASUSTek Computer                | 1         | 1.54%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 22.22%  |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 11        | 15.28%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 6.94%   |
| Intel Wireless 7265                                               | 4         | 5.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 4.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.78%   |
| Intel Wireless 7260                                               | 2         | 2.78%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 2.78%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 2.78%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 2.78%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 1.39%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1         | 1.39%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 1.39%   |
| Realtek 802.11ac NIC                                              | 1         | 1.39%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 1         | 1.39%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1         | 1.39%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 1.39%   |
| MediaTek WiFi                                                     | 1         | 1.39%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.39%   |
| Intel Wireless 8265 / 8275                                        | 1         | 1.39%   |
| Intel Ethernet Connection I218-V                                  | 1         | 1.39%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.39%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1         | 1.39%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                       | 1         | 1.39%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.39%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 1         | 1.39%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                            | 1         | 1.39%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1         | 1.39%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                | 1         | 1.39%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 1         | 1.39%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 1         | 1.39%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 1         | 1.39%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]         | 1         | 1.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 15        | 38.46%  |
| Intel                           | 8         | 20.51%  |
| Broadcom                        | 5         | 12.82%  |
| Realtek Semiconductor           | 4         | 10.26%  |
| Broadcom Limited                | 2         | 5.13%   |
| Ralink                          | 1         | 2.56%   |
| Qualcomm Atheros Communications | 1         | 2.56%   |
| MediaTek                        | 1         | 2.56%   |
| Edimax Technology               | 1         | 2.56%   |
| ASUSTek Computer                | 1         | 2.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 11        | 28.21%  |
| Intel Wireless 7265                                            | 4         | 10.26%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 3         | 7.69%   |
| Intel Wireless 7260                                            | 2         | 5.13%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 2.56%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1         | 2.56%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 2.56%   |
| Realtek 802.11ac NIC                                           | 1         | 2.56%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter         | 1         | 2.56%   |
| Qualcomm Atheros AR9271 802.11n                                | 1         | 2.56%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 2.56%   |
| MediaTek WiFi                                                  | 1         | 2.56%   |
| Intel Wireless 8265 / 8275                                     | 1         | 2.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 2.56%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                    | 1         | 2.56%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 1         | 2.56%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                         | 1         | 2.56%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 1         | 2.56%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter             | 1         | 2.56%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 1         | 2.56%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 1         | 2.56%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 2.56%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]      | 1         | 2.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 22        | 68.75%  |
| Intel                    | 4         | 12.5%   |
| Broadcom                 | 3         | 9.38%   |
| ASIX Electronics         | 2         | 6.25%   |
| Marvell Technology Group | 1         | 3.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 48.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 15.15%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 6.06%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 6.06%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 6.06%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 6.06%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 3.03%   |
| Intel Ethernet Connection I218-V                                  | 1         | 3.03%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 3.03%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 3.03%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 35        | 53.03%  |
| Ethernet | 31        | 46.97%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 23        | 58.97%  |
| WiFi     | 16        | 41.03%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 24        | 54.55%  |
| 1     | 14        | 31.82%  |
| 0     | 6         | 13.64%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 37        | 84.09%  |
| Yes  | 7         | 15.91%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 7         | 23.33%  |
| Qualcomm Atheros Communications | 5         | 16.67%  |
| Foxconn / Hon Hai               | 5         | 16.67%  |
| Apple                           | 5         | 16.67%  |
| Lite-On Technology              | 4         | 13.33%  |
| Realtek Semiconductor           | 1         | 3.33%   |
| Cambridge Silicon Radio         | 1         | 3.33%   |
| Broadcom                        | 1         | 3.33%   |
| ASUSTek Computer                | 1         | 3.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 6         | 20%     |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 16.67%  |
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 13.33%  |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 6.67%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 6.67%   |
| Apple Bluetooth USB Host Controller                 | 2         | 6.67%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 3.33%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 3.33%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 3.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.33%   |
| Broadcom HP Portable Valentine                      | 1         | 3.33%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 3.33%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 3.33%   |
| Apple Bluetooth Host Controller                     | 1         | 3.33%   |
| Apple Bluetooth HCI                                 | 1         | 3.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 34        | 68%     |
| AMD      | 6         | 12%     |
| Nvidia   | 5         | 10%     |
| XMOS     | 1         | 2%      |
| Shure    | 1         | 2%      |
| Micronas | 1         | 2%      |
| M-Audio  | 1         | 2%      |
| Logitech | 1         | 2%      |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 11        | 18.33%  |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 8.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 6.67%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 6.67%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 3.33%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 3.33%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 3.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 3.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 3.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 3.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 3.33%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 3.33%   |
| XMOS xDuoo USB Audio 2.0                                                   | 1         | 1.67%   |
| Shure MV5                                                                  | 1         | 1.67%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 1.67%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.67%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.67%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 1.67%   |
| Nvidia GF116 High Definition Audio Controller                              | 1         | 1.67%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.67%   |
| Micronas QSB                                                               | 1         | 1.67%   |
| M-Audio M-Audio Fast Track MKII                                            | 1         | 1.67%   |
| Logitech Headset H340                                                      | 1         | 1.67%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 1.67%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.67%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1.67%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 1.67%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 1.67%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.67%   |
| AMD RV770 HDMI Audio [Radeon HD 4850/4870]                                 | 1         | 1.67%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 1.67%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 6         | 31.58%  |
| Crucial             | 4         | 21.05%  |
| Samsung Electronics | 3         | 15.79%  |
| Unknown             | 2         | 10.53%  |
| Toshiba             | 2         | 10.53%  |
| Smart               | 1         | 5.26%   |
| Kingston            | 1         | 5.26%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 2         | 9.52%   |
| Crucial RAM CT16G4SFD824A.M16FRS 16GB SODIMM DDR4 2400MT/s       | 2         | 9.52%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 4.76%   |
| Unknown RAM Module 16384MB 2133MT/s                              | 1         | 4.76%   |
| Toshiba RAM 9905711-015.A00G 4GB SODIMM DDR4 2400MT/s            | 1         | 4.76%   |
| Toshiba RAM 8HTF12864HDY-800G1 1024MB SODIMM 1066MT/s            | 1         | 4.76%   |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 1066MT/s             | 1         | 4.76%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s            | 1         | 4.76%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 4.76%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 4.76%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 4.76%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 4.76%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 1         | 4.76%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 1         | 4.76%   |
| SK hynix RAM H9CCNNNBLTALAR-NTD 4GB Row Of Chips LPDDR3 1600MT/s | 1         | 4.76%   |
| Samsung RAM Module 4GB SODIMM LPDDR3 1867MT/s                    | 1         | 4.76%   |
| Kingston RAM 9905471-011.A00LF 4GB DIMM DDR3 1600MT/s            | 1         | 4.76%   |
| Crucial RAM CT4G4SFS8213.C8FBD1 4GB SODIMM DDR4 2133MT/s         | 1         | 4.76%   |
| Crucial RAM CT16G4S24AM.M16FE 16GB SODIMM DDR4 2400MT/s          | 1         | 4.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 9         | 52.94%  |
| DDR3    | 4         | 23.53%  |
| LPDDR3  | 2         | 11.76%  |
| DDR2    | 1         | 5.88%   |
| Unknown | 1         | 5.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 13        | 76.47%  |
| DIMM         | 2         | 11.76%  |
| Row Of Chips | 1         | 5.88%   |
| Unknown      | 1         | 5.88%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 10        | 52.63%  |
| 16384 | 4         | 21.05%  |
| 8192  | 3         | 15.79%  |
| 32768 | 2         | 10.53%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 5         | 26.32%  |
| 1600  | 5         | 26.32%  |
| 2400  | 4         | 21.05%  |
| 2133  | 2         | 10.53%  |
| 1867  | 1         | 5.26%   |
| 1333  | 1         | 5.26%   |
| 1066  | 1         | 5.26%   |

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
| Apple                                  | 6         | 20.69%  |
| Realtek Semiconductor                  | 4         | 13.79%  |
| Alcor Micro                            | 4         | 13.79%  |
| Acer                                   | 4         | 13.79%  |
| Sunplus Innovation Technology          | 3         | 10.34%  |
| Chicony Electronics                    | 3         | 10.34%  |
| Suyin                                  | 1         | 3.45%   |
| Microdia                               | 1         | 3.45%   |
| Lite-On Technology                     | 1         | 3.45%   |
| Google                                 | 1         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Apple Built-in iSight                                                      | 3         | 10%     |
| Alcor Micro HD WebCam                                                      | 3         | 10%     |
| Apple iPhone5/5C/5S/6                                                      | 2         | 6.67%   |
| Acer SunplusIT INC. Integrated Camera                                      | 2         | 6.67%   |
| Suyin HP TrueVision Full HD                                                | 1         | 3.33%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 3.33%   |
| Sunplus Integrated Camera                                                  | 1         | 3.33%   |
| Sunplus HD WebCam                                                          | 1         | 3.33%   |
| Realtek USB2.0 camera                                                      | 1         | 3.33%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 3.33%   |
| Realtek Integrated Webcam                                                  | 1         | 3.33%   |
| Realtek HP Truevision HD                                                   | 1         | 3.33%   |
| Microdia HP Integrated Webcam                                              | 1         | 3.33%   |
| Lite-On Integrated Camera                                                  | 1         | 3.33%   |
| Chicony USB2.0 UVC WebCam                                                  | 1         | 3.33%   |
| Chicony LG HD WebCam                                                       | 1         | 3.33%   |
| Chicony HD User Facing                                                     | 1         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 1         | 3.33%   |
| Apple iBridge                                                              | 1         | 3.33%   |
| Apple FaceTime HD Camera (Built-in)                                        | 1         | 3.33%   |
| Alcor Micro HP Webcam-101                                                  | 1         | 3.33%   |
| Acer SunplusIT Integrated Camera                                           | 1         | 3.33%   |
| Acer BisonCam, NB Pro                                                      | 1         | 3.33%   |
| Unknown                                                                    | 1         | 3.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 3         | 50%     |
| LighTuning Technology | 2         | 33.33%  |
| Synaptics             | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor     | 3         | 50%     |
| Synaptics Metallica MOH Touch Fingerprint Reader | 1         | 16.67%  |
| LighTuning ES603 Swipe Fingerprint Sensor        | 1         | 16.67%  |
| LighTuning EgisTec Touch Fingerprint Sensor      | 1         | 16.67%  |

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
| 0     | 23        | 51.11%  |
| 1     | 17        | 37.78%  |
| 2     | 3         | 6.67%   |
| 4     | 1         | 2.22%   |
| 3     | 1         | 2.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 8         | 26.67%  |
| Bluetooth             | 7         | 23.33%  |
| Fingerprint reader    | 6         | 20%     |
| Graphics card         | 5         | 16.67%  |
| Multimedia controller | 2         | 6.67%   |
| Chipcard              | 1         | 3.33%   |
| Camera                | 1         | 3.33%   |

