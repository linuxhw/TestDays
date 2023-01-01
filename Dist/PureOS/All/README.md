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

Total: 69

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | GA-MA78GM-UD2H              | Desktop     | [415844c745](https://linux-hardware.org/?probe=415844c745) | Dec 08, 2022 |
| Dell          | 0M859N A00                  | Desktop     | [95cf7fe257](https://linux-hardware.org/?probe=95cf7fe257) | Nov 29, 2022 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [c41d8da6ac](https://linux-hardware.org/?probe=c41d8da6ac) | Nov 26, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [6901439af7](https://linux-hardware.org/?probe=6901439af7) | Nov 17, 2022 |
| Lenovo        | IdeaPad U430 Touch 20270    | Notebook    | [707d2f74c7](https://linux-hardware.org/?probe=707d2f74c7) | Oct 24, 2022 |
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
| PureOS 10   | 17        | 34%     |
| PureOS 10.0 | 16        | 32%     |
| PureOS 9.0  | 12        | 24%     |
| PureOS 9    | 3         | 6%      |
| PureOS 8    | 2         | 4%      |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| PureOS | 49        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Computers | Percent |
|----------------------------------|-----------|---------|
| 4.19.0-5-amd64                   | 9         | 16.98%  |
| 5.10.0-14-amd64                  | 7         | 13.21%  |
| 5.10.0-13-amd64                  | 5         | 9.43%   |
| 5.10.0-8-amd64                   | 4         | 7.55%   |
| 4.19.0-14-amd64                  | 4         | 7.55%   |
| 5.10.0-11-amd64                  | 3         | 5.66%   |
| 5.7.0-1-librem5                  | 2         | 3.77%   |
| 5.10.0-9-amd64                   | 2         | 3.77%   |
| 5.10.0-7-amd64                   | 2         | 3.77%   |
| 5.10.0-19-amd64                  | 2         | 3.77%   |
| 5.10.0-16-amd64                  | 2         | 3.77%   |
| 5.9-sunxi64                      | 1         | 1.89%   |
| 5.8-sunxi64                      | 1         | 1.89%   |
| 5.7.0-0.38-1-pinebookpro-hwaccel | 1         | 1.89%   |
| 5.15.0-2-amd64                   | 1         | 1.89%   |
| 5.10.0-6-amd64                   | 1         | 1.89%   |
| 5.10.0-18-amd64                  | 1         | 1.89%   |
| 5.10.0-17-amd64                  | 1         | 1.89%   |
| 5.10.0-15-amd64                  | 1         | 1.89%   |
| 5.10.0-12-amd64                  | 1         | 1.89%   |
| 4.19.72-imx8-sr                  | 1         | 1.89%   |
| 4.16.0-1-amd64                   | 1         | 1.89%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 30        | 58.82%  |
| 4.19.0  | 13        | 25.49%  |
| 5.7.0   | 3         | 5.88%   |
| 5.9     | 1         | 1.96%   |
| 5.8     | 1         | 1.96%   |
| 5.15.0  | 1         | 1.96%   |
| 4.19.72 | 1         | 1.96%   |
| 4.16.0  | 1         | 1.96%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 30        | 60%     |
| 4.19    | 14        | 28%     |
| 5.7     | 3         | 6%      |
| 5.15    | 1         | 2%      |
| 5       | 1         | 2%      |
| 4.16    | 1         | 2%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 44        | 89.8%   |
| aarch64 | 5         | 10.2%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 42        | 80.77%  |
| Unknown         | 6         | 11.54%  |
| KDE5            | 2         | 3.85%   |
| MATE            | 1         | 1.92%   |
| GNOME Flashback | 1         | 1.92%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 35        | 64.81%  |
| X11     | 9         | 16.67%  |
| Unknown | 6         | 11.11%  |
| Tty     | 4         | 7.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 29        | 59.18%  |
| GDM     | 13        | 26.53%  |
| GDM3    | 6         | 12.24%  |
| SDDM    | 1         | 2.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 21        | 40.38%  |
| de_DE   | 5         | 9.62%   |
| Unknown | 4         | 7.69%   |
| en_GB   | 3         | 5.77%   |
| C       | 3         | 5.77%   |
| ru_RU   | 2         | 3.85%   |
| pt_BR   | 2         | 3.85%   |
| pl_PL   | 2         | 3.85%   |
| it_IT   | 2         | 3.85%   |
| zh_CN   | 1         | 1.92%   |
| pt_PT   | 1         | 1.92%   |
| hu_HU   | 1         | 1.92%   |
| fr_FR   | 1         | 1.92%   |
| es_CR   | 1         | 1.92%   |
| en_IL   | 1         | 1.92%   |
| en_AU   | 1         | 1.92%   |
| bg_BG   | 1         | 1.92%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 42        | 84%     |
| EFI  | 8         | 16%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 44        | 89.8%   |
| Overlay | 2         | 4.08%   |
| Unknown | 2         | 4.08%   |
| Ext2    | 1         | 2.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 28        | 54.9%   |
| MBR     | 14        | 27.45%  |
| GPT     | 9         | 17.65%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 42        | 85.71%  |
| Yes       | 7         | 14.29%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 45        | 91.84%  |
| Yes       | 4         | 8.16%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Purism              | 11        | 22.45%  |
| Apple               | 7         | 14.29%  |
| Lenovo              | 6         | 12.24%  |
| Dell                | 5         | 10.2%   |
| Hewlett-Packard     | 4         | 8.16%   |
| Pine Microsystems   | 2         | 4.08%   |
| Gigabyte Technology | 2         | 4.08%   |
| ASUSTek Computer    | 2         | 4.08%   |
| Acer                | 2         | 4.08%   |
| Unknown             | 2         | 4.08%   |
| Toshiba             | 1         | 2.04%   |
| Samsung Electronics | 1         | 2.04%   |
| PCWare              | 1         | 2.04%   |
| Notebook            | 1         | 2.04%   |
| MSI                 | 1         | 2.04%   |
| LG Electronics      | 1         | 2.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Purism Librem 14                         | 5         | 10.2%   |
| Purism Librem 15 v4                      | 2         | 4.08%   |
| HP Pavilion g6                           | 2         | 4.08%   |
| Unknown                                  | 2         | 4.08%   |
| Toshiba Satellite L500D                  | 1         | 2.04%   |
| Samsung 530U3C/530U4C/532U3C             | 1         | 2.04%   |
| Purism Librem 5                          | 1         | 2.04%   |
| Purism Librem 15 v3                      | 1         | 2.04%   |
| Purism Librem 13 v4                      | 1         | 2.04%   |
| Purism Librem 13 v2                      | 1         | 2.04%   |
| Pine Microsystems Pine64 PinePhone (1.2) | 1         | 2.04%   |
| Pine Microsystems Pine64 Pinebook Pro    | 1         | 2.04%   |
| PCWare IPX4005G                          | 1         | 2.04%   |
| Notebook P17SM                           | 1         | 2.04%   |
| MSI MS-7788                              | 1         | 2.04%   |
| LG 22V280-L.BY31P1                       | 1         | 2.04%   |
| Lenovo ThinkPad T540p 20BFS23T00         | 1         | 2.04%   |
| Lenovo ThinkPad T440p                    | 1         | 2.04%   |
| Lenovo ThinkPad T440 20B60044RT          | 1         | 2.04%   |
| Lenovo ThinkPad E480 20KN003SUS          | 1         | 2.04%   |
| Lenovo ThinkPad 13 2nd Gen 20J2S00G00    | 1         | 2.04%   |
| Lenovo IdeaPad U430 Touch 20270          | 1         | 2.04%   |
| HP Spectre x360 Convertible              | 1         | 2.04%   |
| HP Pavilion Notebook                     | 1         | 2.04%   |
| Gigabyte GA-MA78GM-UD2H                  | 1         | 2.04%   |
| Gigabyte B85M-DS3H                       | 1         | 2.04%   |
| Dell XPS 13 9370                         | 1         | 2.04%   |
| Dell OptiPlex 760                        | 1         | 2.04%   |
| Dell Inspiron 5547                       | 1         | 2.04%   |
| Dell Inspiron 3847                       | 1         | 2.04%   |
| Dell Inspiron 15-3567                    | 1         | 2.04%   |
| ASUS EX-A320M-GAMING                     | 1         | 2.04%   |
| ASUS A88X-PLUS/USB                       | 1         | 2.04%   |
| Apple MacBookPro6,1                      | 1         | 2.04%   |
| Apple MacBookPro14,2                     | 1         | 2.04%   |
| Apple MacBookAir7,2                      | 1         | 2.04%   |
| Apple MacBook9,1                         | 1         | 2.04%   |
| Apple iMac7,1                            | 1         | 2.04%   |
| Apple iMac13,1                           | 1         | 2.04%   |
| Apple iMac11,1                           | 1         | 2.04%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Purism Librem            | 11        | 22.45%  |
| Lenovo ThinkPad          | 5         | 10.2%   |
| HP Pavilion              | 3         | 6.12%   |
| Dell Inspiron            | 3         | 6.12%   |
| Pine Microsystems Pine64 | 2         | 4.08%   |
| Unknown                  | 2         | 4.08%   |
| Toshiba Satellite        | 1         | 2.04%   |
| Samsung 530U3C           | 1         | 2.04%   |
| PCWare IPX4005G          | 1         | 2.04%   |
| Notebook P17SM           | 1         | 2.04%   |
| MSI MS-7788              | 1         | 2.04%   |
| LG 22V280-L.BY31P1       | 1         | 2.04%   |
| Lenovo IdeaPad           | 1         | 2.04%   |
| HP Spectre               | 1         | 2.04%   |
| Gigabyte GA-MA78GM-UD2H  | 1         | 2.04%   |
| Gigabyte B85M-DS3H       | 1         | 2.04%   |
| Dell XPS                 | 1         | 2.04%   |
| Dell OptiPlex            | 1         | 2.04%   |
| ASUS EX-A320M-GAMING     | 1         | 2.04%   |
| ASUS A88X-PLUS           | 1         | 2.04%   |
| Apple MacBookPro6        | 1         | 2.04%   |
| Apple MacBookPro14       | 1         | 2.04%   |
| Apple MacBookAir7        | 1         | 2.04%   |
| Apple MacBook9           | 1         | 2.04%   |
| Apple iMac7              | 1         | 2.04%   |
| Apple iMac13             | 1         | 2.04%   |
| Apple iMac11             | 1         | 2.04%   |
| Acer Swift               | 1         | 2.04%   |
| Acer Nitro               | 1         | 2.04%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 7         | 14.29%  |
| 2021    | 6         | 12.24%  |
| 2018    | 5         | 10.2%   |
| 2017    | 5         | 10.2%   |
| Unknown | 5         | 10.2%   |
| 2019    | 4         | 8.16%   |
| 2015    | 4         | 8.16%   |
| 2011    | 3         | 6.12%   |
| 2020    | 2         | 4.08%   |
| 2016    | 2         | 4.08%   |
| 2009    | 2         | 4.08%   |
| 2014    | 1         | 2.04%   |
| 2012    | 1         | 2.04%   |
| 2010    | 1         | 2.04%   |
| 2007    | 1         | 2.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 33        | 67.35%  |
| Desktop        | 8         | 16.33%  |
| All in one     | 4         | 8.16%   |
| System on chip | 2         | 4.08%   |
| Phone          | 1         | 2.04%   |
| Convertible    | 1         | 2.04%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 49        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 38        | 77.55%  |
| Yes  | 11        | 22.45%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 12        | 24.49%  |
| 4.01-8.0   | 10        | 20.41%  |
| 16.01-24.0 | 9         | 18.37%  |
| 3.01-4.0   | 8         | 16.33%  |
| 32.01-64.0 | 6         | 12.24%  |
| 2.01-3.0   | 2         | 4.08%   |
| 24.01-32.0 | 1         | 2.04%   |
| 1.01-2.0   | 1         | 2.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 15        | 27.78%  |
| 1.01-2.0  | 13        | 24.07%  |
| 3.01-4.0  | 12        | 22.22%  |
| 4.01-8.0  | 10        | 18.52%  |
| 8.01-16.0 | 2         | 3.7%    |
| 0.51-1.0  | 1         | 1.85%   |
| 0.01-0.5  | 1         | 1.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 33        | 67.35%  |
| 2      | 14        | 28.57%  |
| 5      | 1         | 2.04%   |
| 0      | 1         | 2.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 38        | 77.55%  |
| Yes       | 11        | 22.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 77.55%  |
| No        | 11        | 22.45%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 79.59%  |
| No        | 10        | 20.41%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 65.31%  |
| No        | 17        | 34.69%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 10        | 19.61%  |
| Germany                | 7         | 13.73%  |
| UK                     | 5         | 9.8%    |
| Brazil                 | 5         | 9.8%    |
| Canada                 | 3         | 5.88%   |
| Russia                 | 2         | 3.92%   |
| Poland                 | 2         | 3.92%   |
| Italy                  | 2         | 3.92%   |
| France                 | 2         | 3.92%   |
| Australia              | 2         | 3.92%   |
| Turkey                 | 1         | 1.96%   |
| South Africa           | 1         | 1.96%   |
| Portugal               | 1         | 1.96%   |
| Paraguay               | 1         | 1.96%   |
| Israel                 | 1         | 1.96%   |
| Iran                   | 1         | 1.96%   |
| Greece                 | 1         | 1.96%   |
| Costa Rica             | 1         | 1.96%   |
| China                  | 1         | 1.96%   |
| Bulgaria               | 1         | 1.96%   |
| Bosnia and Herzegovina | 1         | 1.96%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Stuttgart          | 3         | 5.66%   |
| Porto Alegre       | 3         | 5.66%   |
| Warsaw             | 2         | 3.77%   |
| New York           | 2         | 3.77%   |
| London             | 2         | 3.77%   |
| Yuzhnoural'sk      | 1         | 1.89%   |
| Wixom              | 1         | 1.89%   |
| Windsor            | 1         | 1.89%   |
| Vancouver          | 1         | 1.89%   |
| Troy               | 1         | 1.89%   |
| Thorpe Hamlet      | 1         | 1.89%   |
| Tel Aviv           | 1         | 1.89%   |
| Spencer            | 1         | 1.89%   |
| Sofia              | 1         | 1.89%   |
| Seattle            | 1         | 1.89%   |
| San Jose           | 1         | 1.89%   |
| Paris              | 1         | 1.89%   |
| Montreal           | 1         | 1.89%   |
| Milwaukee          | 1         | 1.89%   |
| Milan              | 1         | 1.89%   |
| Melbourne          | 1         | 1.89%   |
| Mankato            | 1         | 1.89%   |
| Liverpool          | 1         | 1.89%   |
| Lenningen          | 1         | 1.89%   |
| Leeds              | 1         | 1.89%   |
| Krasnogorsk        | 1         | 1.89%   |
| Istanbul           | 1         | 1.89%   |
| Hernandarias       | 1         | 1.89%   |
| Guimaraes          | 1         | 1.89%   |
| Grasse             | 1         | 1.89%   |
| Fort Collins       | 1         | 1.89%   |
| Eberswalde         | 1         | 1.89%   |
| Cape Town          | 1         | 1.89%   |
| Camden             | 1         | 1.89%   |
| Blumenau           | 1         | 1.89%   |
| Big Sky            | 1         | 1.89%   |
| Berlin             | 1         | 1.89%   |
| Banja Luka         | 1         | 1.89%   |
| Bandar-e Asalūyeh | 1         | 1.89%   |
| Balow              | 1         | 1.89%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 16     | 20.34%  |
| Unknown             | 6         | 10     | 10.17%  |
| Seagate             | 6         | 10     | 10.17%  |
| WDC                 | 5         | 6      | 8.47%   |
| Apple               | 5         | 7      | 8.47%   |
| SanDisk             | 3         | 3      | 5.08%   |
| HGST                | 3         | 3      | 5.08%   |
| A-DATA Technology   | 3         | 4      | 5.08%   |
| Crucial             | 2         | 4      | 3.39%   |
| Win Memory          | 1         | 1      | 1.69%   |
| Transcend           | 1         | 1      | 1.69%   |
| Toshiba             | 1         | 1      | 1.69%   |
| Plextor             | 1         | 1      | 1.69%   |
| Phison              | 1         | 1      | 1.69%   |
| Patriot             | 1         | 1      | 1.69%   |
| Mushkin             | 1         | 1      | 1.69%   |
| JMicron Technology  | 1         | 1      | 1.69%   |
| Intenso             | 1         | 2      | 1.69%   |
| Intel               | 1         | 1      | 1.69%   |
| Hitachi             | 1         | 1      | 1.69%   |
| BIWIN               | 1         | 1      | 1.69%   |
| ASMT                | 1         | 2      | 1.69%   |
| ADATA Technology    | 1         | 1      | 1.69%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST1000LM048-2E7172 1TB      | 2         | 3.08%   |
| Samsung SSD 970 PRO 1TB             | 2         | 3.08%   |
| Samsung SSD 860 EVO 250GB           | 2         | 3.08%   |
| Win Memory SWR256G-201II 256GB      | 1         | 1.54%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 1         | 1.54%   |
| WDC WDS100T2B0C-00PXH0 1TB          | 1         | 1.54%   |
| WDC WDBNCE2500PNC 250GB SSD         | 1         | 1.54%   |
| WDC WD5000AZRX-00A8LB0 500GB        | 1         | 1.54%   |
| WDC WD3200AAJS-40RYA0 320GB         | 1         | 1.54%   |
| Unknown SH64G  64GB                 | 1         | 1.54%   |
| Unknown MMC Card  64GB              | 1         | 1.54%   |
| Unknown MMC Card  32GB              | 1         | 1.54%   |
| Unknown MMC Card  16GB              | 1         | 1.54%   |
| Unknown DA4128  128GB               | 1         | 1.54%   |
| Unknown AFGCF  128GB                | 1         | 1.54%   |
| Unknown 8GTF4R  8GB                 | 1         | 1.54%   |
| Unknown 032G32  32GB                | 1         | 1.54%   |
| Transcend TS240GMTS420S 240GB SSD   | 1         | 1.54%   |
| Toshiba NVMe SSD Drive 512GB        | 1         | 1.54%   |
| Seagate ST480HM000-1G5162 480GB     | 1         | 1.54%   |
| Seagate ST3320418AS 320GB           | 1         | 1.54%   |
| Seagate ST31000524AS 1TB            | 1         | 1.54%   |
| Seagate ST1000DM003-1ER162 1TB      | 1         | 1.54%   |
| Seagate NVMe SSD Drive 2TB          | 1         | 1.54%   |
| SanDisk SSD i100 24GB               | 1         | 1.54%   |
| SanDisk SDSSDH3500G 500GB           | 1         | 1.54%   |
| SanDisk NVMe SSD Drive 500GB        | 1         | 1.54%   |
| Samsung SSD 970 EVO Plus 500GB      | 1         | 1.54%   |
| Samsung SSD 970 EVO 250GB           | 1         | 1.54%   |
| Samsung SSD 960 EVO 500GB           | 1         | 1.54%   |
| Samsung SSD 960 EVO 250GB           | 1         | 1.54%   |
| Samsung SSD 860 EVO 500GB           | 1         | 1.54%   |
| Samsung SSD 860 EVO 1TB             | 1         | 1.54%   |
| Samsung SSD 850 EVO 500GB           | 1         | 1.54%   |
| Samsung SSD 850 EVO 250GB           | 1         | 1.54%   |
| Samsung NVMe SSD Drive 1TB          | 1         | 1.54%   |
| Plextor PX-1TM6Pro 1024GB SSD       | 1         | 1.54%   |
| Phison PM8512GPTCB4B8TF-E13T4 512GB | 1         | 1.54%   |
| Patriot Burst Elite 120GB SSD       | 1         | 1.54%   |
| Mushkin MKNSSDRE250GB-LT            | 1         | 1.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 9      | 38.46%  |
| HGST    | 3         | 3      | 23.08%  |
| WDC     | 2         | 2      | 15.38%  |
| Apple   | 2         | 2      | 15.38%  |
| Hitachi | 1         | 1      | 7.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 9      | 25.93%  |
| A-DATA Technology   | 3         | 4      | 11.11%  |
| WDC                 | 2         | 3      | 7.41%   |
| SanDisk             | 2         | 2      | 7.41%   |
| Crucial             | 2         | 4      | 7.41%   |
| Win Memory          | 1         | 1      | 3.7%    |
| Transcend           | 1         | 1      | 3.7%    |
| Plextor             | 1         | 1      | 3.7%    |
| Patriot             | 1         | 1      | 3.7%    |
| Mushkin             | 1         | 1      | 3.7%    |
| JMicron Technology  | 1         | 1      | 3.7%    |
| Intenso             | 1         | 2      | 3.7%    |
| Intel               | 1         | 1      | 3.7%    |
| BIWIN               | 1         | 1      | 3.7%    |
| ASMT                | 1         | 2      | 3.7%    |
| Apple               | 1         | 1      | 3.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 22        | 35     | 40%     |
| NVMe | 14        | 17     | 25.45%  |
| HDD  | 13        | 17     | 23.64%  |
| MMC  | 6         | 10     | 10.91%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 31        | 48     | 57.41%  |
| NVMe | 14        | 17     | 25.93%  |
| MMC  | 6         | 10     | 11.11%  |
| SAS  | 3         | 4      | 5.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 23        | 38     | 67.65%  |
| 0.51-1.0   | 9         | 11     | 26.47%  |
| 1.01-2.0   | 2         | 3      | 5.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 23        | 45.1%   |
| 251-500    | 6         | 11.76%  |
| 101-250    | 6         | 11.76%  |
| 501-1000   | 4         | 7.84%   |
| 21-50      | 3         | 5.88%   |
| 51-100     | 3         | 5.88%   |
| Unknown    | 3         | 5.88%   |
| 1001-2000  | 2         | 3.92%   |
| 2001-3000  | 1         | 1.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 30        | 58.82%  |
| 21-50    | 10        | 19.61%  |
| 101-250  | 3         | 5.88%   |
| 501-1000 | 3         | 5.88%   |
| Unknown  | 3         | 5.88%   |
| 251-500  | 1         | 1.96%   |
| 51-100   | 1         | 1.96%   |

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
| Detected | 33        | 55     | 64.71%  |
| Works    | 15        | 21     | 29.41%  |
| Malfunc  | 3         | 3      | 5.88%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 28        | 58.33%  |
| Samsung Electronics          | 7         | 14.58%  |
| AMD                          | 5         | 10.42%  |
| SanDisk                      | 2         | 4.17%   |
| Apple                        | 2         | 4.17%   |
| Toshiba America Info Systems | 1         | 2.08%   |
| Seagate Technology           | 1         | 2.08%   |
| Phison Electronics           | 1         | 2.08%   |
| ADATA Technology             | 1         | 2.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 13.73%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 9.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 7.84%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 3         | 5.88%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 3.92%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 3.92%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 3.92%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 3.92%   |
| Apple S3X NVMe Controller                                                      | 2         | 3.92%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 1.96%   |
| Seagate FireCuda 510 SSD                                                       | 1         | 1.96%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 1         | 1.96%   |
| SanDisk Non-Volatile memory controller                                         | 1         | 1.96%   |
| Samsung Electronics SATA controller                                            | 1         | 1.96%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 1.96%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.96%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.96%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 1.96%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 1         | 1.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 1         | 1.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 1         | 1.96%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1         | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1         | 1.96%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 1.96%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 1         | 1.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 1.96%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 1         | 1.96%   |
| AMD FCH SATA Controller D                                                      | 1         | 1.96%   |
| ADATA Non-Volatile memory controller                                           | 1         | 1.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 33        | 67.35%  |
| NVMe | 14        | 28.57%  |
| IDE  | 2         | 4.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 39        | 79.59%  |
| ARM    | 5         | 10.2%   |
| AMD    | 5         | 10.2%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-10710U CPU @ 1.10GHz              | 5         | 10.2%   |
| ARM Processor                                   | 5         | 10.2%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 4         | 8.16%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 2         | 4.08%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 4.08%   |
| Intel Pentium CPU N4200 @ 1.10GHz               | 1         | 2.04%   |
| Intel Core m5-6Y54 CPU @ 1.10GHz                | 1         | 2.04%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 1         | 2.04%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 2.04%   |
| Intel Core i7-7567U CPU @ 3.50GHz               | 1         | 2.04%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz              | 1         | 2.04%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz              | 1         | 2.04%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz              | 1         | 2.04%   |
| Intel Core i7-4510U CPU @ 2.00GHz               | 1         | 2.04%   |
| Intel Core i5-5250U CPU @ 1.60GHz               | 1         | 2.04%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 1         | 2.04%   |
| Intel Core i5-4460 CPU @ 3.20GHz                | 1         | 2.04%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 1         | 2.04%   |
| Intel Core i5-3330S CPU @ 2.70GHz               | 1         | 2.04%   |
| Intel Core i5-2320 CPU @ 3.00GHz                | 1         | 2.04%   |
| Intel Core i5 CPU M 540 @ 2.53GHz               | 1         | 2.04%   |
| Intel Core i5 CPU 750 @ 2.67GHz                 | 1         | 2.04%   |
| Intel Core i3-4130T CPU @ 2.90GHz               | 1         | 2.04%   |
| Intel Core i3-4010U CPU @ 1.70GHz               | 1         | 2.04%   |
| Intel Core i3-3217U CPU @ 1.80GHz               | 1         | 2.04%   |
| Intel Core i3-3120M CPU @ 2.50GHz               | 1         | 2.04%   |
| Intel Core i3-2330M CPU @ 2.20GHz               | 1         | 2.04%   |
| Intel Core 2 Duo CPU T7700 @ 2.40GHz            | 1         | 2.04%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz            | 1         | 2.04%   |
| Intel Celeron N4100 CPU @ 1.10GHz               | 1         | 2.04%   |
| Intel Celeron J4005 CPU @ 2.00GHz               | 1         | 2.04%   |
| AMD Turion II Dual-Core Mobile M520             | 1         | 2.04%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx   | 1         | 2.04%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics     | 1         | 2.04%   |
| AMD Athlon II X4 620 Processor                  | 1         | 2.04%   |
| AMD A10-7860K Radeon R7, 12 Compute Cores 4C+8G | 1         | 2.04%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 18        | 36.73%  |
| Intel Core i5           | 10        | 20.41%  |
| Other                   | 5         | 10.2%   |
| Intel Core i3           | 5         | 10.2%   |
| Intel Core 2 Duo        | 2         | 4.08%   |
| Intel Celeron           | 2         | 4.08%   |
| Intel Pentium           | 1         | 2.04%   |
| Intel Core m5           | 1         | 2.04%   |
| AMD Turion II Dual-Core | 1         | 2.04%   |
| AMD Ryzen 5             | 1         | 2.04%   |
| AMD Ryzen 3             | 1         | 2.04%   |
| AMD Athlon II X4        | 1         | 2.04%   |
| AMD A10                 | 1         | 2.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 25        | 51.02%  |
| 4      | 19        | 38.78%  |
| 6      | 5         | 10.2%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 49        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 32        | 65.31%  |
| 1      | 17        | 34.69%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 46        | 92%     |
| Unknown        | 4         | 8%      |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 35        | 68.63%  |
| 0xa0660    | 3         | 5.88%   |
| 0x406e3    | 3         | 5.88%   |
| 0x706a1    | 2         | 3.92%   |
| 0x40651    | 2         | 3.92%   |
| 0x806e9    | 1         | 1.96%   |
| 0x306d4    | 1         | 1.96%   |
| 0x206a7    | 1         | 1.96%   |
| 0x1067a    | 1         | 1.96%   |
| 0x08108109 | 1         | 1.96%   |
| 0x06003106 | 1         | 1.96%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 9         | 18.37%  |
| Haswell       | 8         | 16.33%  |
| CometLake     | 5         | 10.2%   |
| Unknown       | 5         | 10.2%   |
| Skylake       | 3         | 6.12%   |
| IvyBridge     | 3         | 6.12%   |
| Zen+          | 2         | 4.08%   |
| SandyBridge   | 2         | 4.08%   |
| K10           | 2         | 4.08%   |
| Goldmont plus | 2         | 4.08%   |
| Broadwell     | 2         | 4.08%   |
| Westmere      | 1         | 2.04%   |
| Steamroller   | 1         | 2.04%   |
| Penryn        | 1         | 2.04%   |
| Nehalem       | 1         | 2.04%   |
| Goldmont      | 1         | 2.04%   |
| Core          | 1         | 2.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 35        | 68.63%  |
| Nvidia | 8         | 15.69%  |
| AMD    | 8         | 15.69%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                 | 6         | 11.32%  |
| Intel Comet Lake UHD Graphics                                                         | 5         | 9.43%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 3         | 5.66%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 3         | 5.66%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 2         | 3.77%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 2         | 3.77%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 2         | 3.77%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 2         | 3.77%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 2         | 3.77%   |
| Nvidia TU116 [GeForce GTX 1660]                                                       | 1         | 1.89%   |
| Nvidia GT216M [GeForce GT 330M]                                                       | 1         | 1.89%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 1         | 1.89%   |
| Nvidia GK208M [GeForce GT 730M]                                                       | 1         | 1.89%   |
| Nvidia GK208B [GeForce GT 710]                                                        | 1         | 1.89%   |
| Nvidia GK107M [GeForce GT 640M Mac Edition]                                           | 1         | 1.89%   |
| Nvidia GK104M [GeForce GTX 870M]                                                      | 1         | 1.89%   |
| Nvidia GF116 [GeForce GTS 450 Rev. 2]                                                 | 1         | 1.89%   |
| Nvidia GF108 [GeForce GT 630]                                                         | 1         | 1.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 1         | 1.89%   |
| Intel UHD Graphics 620                                                                | 1         | 1.89%   |
| Intel Iris Plus Graphics 650                                                          | 1         | 1.89%   |
| Intel HD Graphics 630                                                                 | 1         | 1.89%   |
| Intel HD Graphics 6000                                                                | 1         | 1.89%   |
| Intel HD Graphics 5500                                                                | 1         | 1.89%   |
| Intel HD Graphics 515                                                                 | 1         | 1.89%   |
| Intel Core Processor Integrated Graphics Controller                                   | 1         | 1.89%   |
| Intel Apollo Lake [HD Graphics 505]                                                   | 1         | 1.89%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                 | 1         | 1.89%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 1.89%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                             | 1         | 1.89%   |
| AMD RV770/M98L [Mobility Radeon HD 4850]                                              | 1         | 1.89%   |
| AMD RV630/M76 [Mobility Radeon HD 2600 XT/2700]                                       | 1         | 1.89%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                             | 1         | 1.89%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                                    | 1         | 1.89%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                   | 1         | 1.89%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 28        | 57.14%  |
| Other          | 5         | 10.2%   |
| 1 x AMD        | 5         | 10.2%   |
| 1 x Nvidia     | 4         | 8.16%   |
| Intel + Nvidia | 4         | 8.16%   |
| Intel + AMD    | 2         | 4.08%   |
| 2 x AMD        | 1         | 2.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 42        | 85.71%  |
| Unknown | 7         | 14.29%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 48        | 96%     |
| 3.01-4.0   | 1         | 2%      |
| 0.51-1.0   | 1         | 2%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 8         | 15.69%  |
| Chimei Innolux          | 7         | 13.73%  |
| LG Display              | 6         | 11.76%  |
| Apple                   | 6         | 11.76%  |
| BOE                     | 5         | 9.8%    |
| Philips                 | 2         | 3.92%   |
| Goldstar                | 2         | 3.92%   |
| AU Optronics            | 2         | 3.92%   |
| Unknown                 | 1         | 1.96%   |
| Sharp                   | 1         | 1.96%   |
| RTK                     | 1         | 1.96%   |
| PANDA                   | 1         | 1.96%   |
| Lenovo                  | 1         | 1.96%   |
| Iiyama                  | 1         | 1.96%   |
| Grundig                 | 1         | 1.96%   |
| Dell                    | 1         | 1.96%   |
| Chi Mei Optoelectronics | 1         | 1.96%   |
| BenQ                    | 1         | 1.96%   |
| ASUSTek Computer        | 1         | 1.96%   |
| AOC                     | 1         | 1.96%   |
| Acer                    | 1         | 1.96%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC434B 3840x2160 344x194mm 15.5-inch     | 3         | 5.88%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 3         | 5.88%   |
| Philips TV PHL5035 1920x1080 640x360mm 28.9-inch                          | 2         | 3.92%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 1         | 1.96%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                   | 1         | 1.96%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 474x296mm 22.0-inch      | 1         | 1.96%   |
| Samsung Electronics SyncMaster SAM01D3 1440x900 408x225mm 18.3-inch       | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch      | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 700x390mm 31.5-inch      | 1         | 1.96%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 1         | 1.96%   |
| RTK LG AIO FHD RTK2136 1920x1080 477x268mm 21.5-inch                      | 1         | 1.96%   |
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch                   | 1         | 1.96%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch              | 1         | 1.96%   |
| LG Display LCD Monitor LGD053B 1920x1080 294x165mm 13.3-inch              | 1         | 1.96%   |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch              | 1         | 1.96%   |
| LG Display LCD Monitor LGD03F0 1366x768 310x174mm 14.0-inch               | 1         | 1.96%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch               | 1         | 1.96%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch               | 1         | 1.96%   |
| Lenovo LEN Y44w-10 LEN65EA 3840x1200 1052x329mm 43.4-inch                 | 1         | 1.96%   |
| Iiyama PL2792H IVM664F 1920x1080 598x336mm 27.0-inch                      | 1         | 1.96%   |
| Grundig WXGA GRU4448 1600x1200                                            | 1         | 1.96%   |
| Goldstar IPS231 GSM5817 1920x1080 510x290mm 23.1-inch                     | 1         | 1.96%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                    | 1         | 1.96%   |
| Dell P2213 DELF042 1680x1050 473x296mm 22.0-inch                          | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch          | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch           | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN1415 1920x1080 309x173mm 13.9-inch          | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN1365 1920x1080 293x165mm 13.2-inch          | 1         | 1.96%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 1.96%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                     | 1         | 1.96%   |
| BOE LCD Monitor BOE079A 1920x1080 309x173mm 13.9-inch                     | 1         | 1.96%   |
| BOE LCD Monitor BOE06C2 1366x768 344x194mm 15.5-inch                      | 1         | 1.96%   |
| BOE LCD Monitor BOE06BE 1920x1080 294x165mm 13.3-inch                     | 1         | 1.96%   |
| BOE LCD Monitor BOE0641 1920x1080 344x193mm 15.5-inch                     | 1         | 1.96%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                         | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO713C 1366x768 309x173mm 13.9-inch             | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO10ED 1920x1080 344x193mm 15.5-inch            | 1         | 1.96%   |
| ASUSTek Computer VP249 AUS24AF 1920x1080 527x296mm 23.8-inch              | 1         | 1.96%   |
| Apple iMac APPA012 1920x1080 475x267mm 21.5-inch                          | 1         | 1.96%   |
| Apple Color LCD APPA034 2880x1800 286x179mm 13.3-inch                     | 1         | 1.96%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 22        | 46.81%  |
| 1366x768 (WXGA)    | 7         | 14.89%  |
| 3840x2160 (4K)     | 6         | 12.77%  |
| 1680x1050 (WSXGA+) | 3         | 6.38%   |
| 1600x900 (HD+)     | 2         | 4.26%   |
| 1440x900 (WXGA+)   | 2         | 4.26%   |
| 3840x1200          | 1         | 2.13%   |
| 2880x1800          | 1         | 2.13%   |
| 2304x1440          | 1         | 2.13%   |
| 2288x1287          | 1         | 2.13%   |
| 1920x1200 (WUXGA)  | 1         | 2.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 13     | 13        | 25.49%  |
| 15     | 12        | 23.53%  |
| 23     | 3         | 5.88%   |
| 14     | 3         | 5.88%   |
| 28     | 2         | 3.92%   |
| 27     | 2         | 3.92%   |
| 24     | 2         | 3.92%   |
| 22     | 2         | 3.92%   |
| 21     | 2         | 3.92%   |
| 20     | 2         | 3.92%   |
| 17     | 2         | 3.92%   |
| 142    | 1         | 1.96%   |
| 54     | 1         | 1.96%   |
| 43     | 1         | 1.96%   |
| 31     | 1         | 1.96%   |
| 19     | 1         | 1.96%   |
| 12     | 1         | 1.96%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 19        | 38%     |
| 201-300        | 8         | 16%     |
| 501-600        | 7         | 14%     |
| 401-500        | 7         | 14%     |
| 601-700        | 3         | 6%      |
| 351-400        | 3         | 6%      |
| 1001-1500      | 2         | 4%      |
| More than 2000 | 1         | 2%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 33        | 76.74%  |
| 16/10 | 8         | 18.6%   |
| 3.20  | 1         | 2.33%   |
| 1.00  | 1         | 2.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 12        | 23.53%  |
| 81-90          | 9         | 17.65%  |
| 201-250        | 9         | 17.65%  |
| 71-80          | 7         | 13.73%  |
| 351-500        | 3         | 5.88%   |
| 151-200        | 3         | 5.88%   |
| More than 1000 | 2         | 3.92%   |
| 301-350        | 2         | 3.92%   |
| 61-70          | 1         | 1.96%   |
| 131-140        | 1         | 1.96%   |
| 121-130        | 1         | 1.96%   |
| 501-1000       | 1         | 1.96%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 17        | 33.33%  |
| 121-160       | 14        | 27.45%  |
| 101-120       | 7         | 13.73%  |
| More than 240 | 6         | 11.76%  |
| 161-240       | 5         | 9.8%    |
| 1-50          | 2         | 3.92%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 34        | 69.39%  |
| 2     | 8         | 16.33%  |
| 0     | 6         | 12.24%  |
| 3     | 1         | 2.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 27        | 36.99%  |
| Qualcomm Atheros                | 15        | 20.55%  |
| Intel                           | 12        | 16.44%  |
| Broadcom                        | 7         | 9.59%   |
| Broadcom Limited                | 3         | 4.11%   |
| ASIX Electronics                | 2         | 2.74%   |
| Ralink                          | 1         | 1.37%   |
| Qualcomm Atheros Communications | 1         | 1.37%   |
| OPPO Electronics                | 1         | 1.37%   |
| MediaTek                        | 1         | 1.37%   |
| Marvell Technology Group        | 1         | 1.37%   |
| Edimax Technology               | 1         | 1.37%   |
| ASUSTek Computer                | 1         | 1.37%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19        | 23.75%  |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 11        | 13.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 6.25%   |
| Intel Wireless 7265                                               | 4         | 5%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 3.75%   |
| Intel Wireless 7260                                               | 3         | 3.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.5%    |
| Intel Ethernet Connection I217-LM                                 | 2         | 2.5%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 2.5%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 2         | 2.5%    |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 2.5%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 1.25%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 1.25%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1         | 1.25%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 1.25%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 1         | 1.25%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1         | 1.25%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 1.25%   |
| OPPO RMX3263                                                      | 1         | 1.25%   |
| MediaTek WiFi                                                     | 1         | 1.25%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.25%   |
| Intel Wireless 8265 / 8275                                        | 1         | 1.25%   |
| Intel Ethernet Connection I218-V                                  | 1         | 1.25%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1         | 1.25%   |
| Intel Centrino Advanced-N 6235                                    | 1         | 1.25%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 1.25%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                       | 1         | 1.25%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.25%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                            | 1         | 1.25%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1         | 1.25%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                | 1         | 1.25%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 1         | 1.25%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 1         | 1.25%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 1         | 1.25%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]         | 1         | 1.25%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 15        | 35.71%  |
| Intel                           | 10        | 23.81%  |
| Broadcom                        | 5         | 11.9%   |
| Realtek Semiconductor           | 4         | 9.52%   |
| Broadcom Limited                | 3         | 7.14%   |
| Ralink                          | 1         | 2.38%   |
| Qualcomm Atheros Communications | 1         | 2.38%   |
| MediaTek                        | 1         | 2.38%   |
| Edimax Technology               | 1         | 2.38%   |
| ASUSTek Computer                | 1         | 2.38%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 11        | 26.19%  |
| Intel Wireless 7265                                            | 4         | 9.52%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 3         | 7.14%   |
| Intel Wireless 7260                                            | 3         | 7.14%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 2         | 4.76%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 2.38%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 2.38%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1         | 2.38%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 2.38%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter         | 1         | 2.38%   |
| Qualcomm Atheros AR9271 802.11n                                | 1         | 2.38%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 2.38%   |
| MediaTek WiFi                                                  | 1         | 2.38%   |
| Intel Wireless 8265 / 8275                                     | 1         | 2.38%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 2.38%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 2.38%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                    | 1         | 2.38%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                         | 1         | 2.38%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 1         | 2.38%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter             | 1         | 2.38%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 1         | 2.38%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 1         | 2.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 2.38%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]      | 1         | 2.38%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 25        | 67.57%  |
| Intel                    | 5         | 13.51%  |
| Broadcom                 | 3         | 8.11%   |
| ASIX Electronics         | 2         | 5.41%   |
| OPPO Electronics         | 1         | 2.7%    |
| Marvell Technology Group | 1         | 2.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19        | 50%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 13.16%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 5.26%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 5.26%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 5.26%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 5.26%   |
| OPPO RMX3263                                                      | 1         | 2.63%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 2.63%   |
| Intel Ethernet Connection I218-V                                  | 1         | 2.63%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 2.63%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 2.63%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 2.63%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 38        | 51.35%  |
| Ethernet | 36        | 48.65%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 28        | 63.64%  |
| WiFi     | 16        | 36.36%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 26        | 53.06%  |
| 1     | 17        | 34.69%  |
| 0     | 6         | 12.24%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 40        | 81.63%  |
| Yes  | 9         | 18.37%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 9         | 27.27%  |
| Apple                           | 6         | 18.18%  |
| Qualcomm Atheros Communications | 5         | 15.15%  |
| Foxconn / Hon Hai               | 5         | 15.15%  |
| Lite-On Technology              | 4         | 12.12%  |
| Realtek Semiconductor           | 1         | 3.03%   |
| Cambridge Silicon Radio         | 1         | 3.03%   |
| Broadcom                        | 1         | 3.03%   |
| ASUSTek Computer                | 1         | 3.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 7         | 21.21%  |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 15.15%  |
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 12.12%  |
| Apple Bluetooth USB Host Controller                 | 3         | 9.09%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 6.06%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 6.06%   |
| Realtek Bluetooth Radio                             | 1         | 3.03%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 3.03%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 3.03%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 3.03%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.03%   |
| Broadcom HP Portable Valentine                      | 1         | 3.03%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 3.03%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 3.03%   |
| Apple Bluetooth Host Controller                     | 1         | 3.03%   |
| Apple Bluetooth HCI                                 | 1         | 3.03%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 38        | 67.86%  |
| AMD      | 7         | 12.5%   |
| Nvidia   | 6         | 10.71%  |
| XMOS     | 1         | 1.79%   |
| Shure    | 1         | 1.79%   |
| Micronas | 1         | 1.79%   |
| M-Audio  | 1         | 1.79%   |
| Logitech | 1         | 1.79%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 11        | 16.18%  |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 7.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 5.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 5.88%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 4.41%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 4.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 4.41%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 2.94%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 2.94%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 2.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 2.94%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 2.94%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 2.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.94%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 2.94%   |
| XMOS xCORE USB Audio 2.0                                                   | 1         | 1.47%   |
| Shure MV5                                                                  | 1         | 1.47%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 1.47%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 1.47%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.47%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.47%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 1.47%   |
| Nvidia GF116 High Definition Audio Controller                              | 1         | 1.47%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.47%   |
| Micronas QSB                                                               | 1         | 1.47%   |
| M-Audio M-Audio Fast Track MKII                                            | 1         | 1.47%   |
| Logitech Headset H340                                                      | 1         | 1.47%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.47%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1.47%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1         | 1.47%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 1.47%   |
| AMD RV770 HDMI Audio [Radeon HD 4850/4870]                                 | 1         | 1.47%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 1.47%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 7         | 31.82%  |
| Crucial             | 4         | 18.18%  |
| Unknown             | 3         | 13.64%  |
| Samsung Electronics | 3         | 13.64%  |
| Toshiba             | 2         | 9.09%   |
| Smart               | 1         | 4.55%   |
| Micron Technology   | 1         | 4.55%   |
| Kingston            | 1         | 4.55%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 2         | 8.33%   |
| Crucial RAM CT16G4SFD824A.M16FRS 16GB SODIMM DDR4 2400MT/s       | 2         | 8.33%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 4.17%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 4.17%   |
| Unknown RAM Module 16384MB 2133MT/s                              | 1         | 4.17%   |
| Toshiba RAM 9905711-015.A00G 4GB SODIMM DDR4 2400MT/s            | 1         | 4.17%   |
| Toshiba RAM 8HTF12864HDY-800G1 4GB SODIMM 1066MT/s               | 1         | 4.17%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM DDR2 1066MT/s           | 1         | 4.17%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s            | 1         | 4.17%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 4.17%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 4.17%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 4.17%   |
| SK hynix RAM HMP125U6EFR8C-S6 2GB DIMM DDR2 800MT/s              | 1         | 4.17%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 4.17%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 4.17%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 4.17%   |
| SK hynix RAM H9CCNNNBLTALAR-NTD 4GB Row Of Chips LPDDR3 1600MT/s | 1         | 4.17%   |
| Samsung RAM Module 4GB SODIMM LPDDR3 1867MT/s                    | 1         | 4.17%   |
| Micron RAM 16HTF25664AZ-800H1 2GB DIMM DDR2 800MT/s              | 1         | 4.17%   |
| Kingston RAM 9905471-011.A00LF 4096MB DIMM DDR3 1600MT/s         | 1         | 4.17%   |
| Crucial RAM CT4G4SFS8213.C8FBD1 4GB SODIMM DDR4 2133MT/s         | 1         | 4.17%   |
| Crucial RAM CT16G4S24AM.M16FE 16GB SODIMM DDR4 2400MT/s          | 1         | 4.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 9         | 47.37%  |
| DDR3    | 5         | 26.32%  |
| LPDDR3  | 2         | 10.53%  |
| DDR2    | 2         | 10.53%  |
| Unknown | 1         | 5.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 14        | 73.68%  |
| DIMM         | 3         | 15.79%  |
| Row Of Chips | 1         | 5.26%   |
| Unknown      | 1         | 5.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 10        | 47.62%  |
| 16384 | 4         | 19.05%  |
| 8192  | 4         | 19.05%  |
| 32768 | 2         | 9.52%   |
| 2048  | 1         | 4.76%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 6         | 28.57%  |
| 2667  | 5         | 23.81%  |
| 2400  | 4         | 19.05%  |
| 2133  | 2         | 9.52%   |
| 1867  | 1         | 4.76%   |
| 1333  | 1         | 4.76%   |
| 1066  | 1         | 4.76%   |
| 800   | 1         | 4.76%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Brother Industries | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                       | Computers | Percent |
|-----------------------------|-----------|---------|
| Brother DCP-L3550CDW series | 1         | 100%    |

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
| Apple                                  | 6         | 19.35%  |
| Realtek Semiconductor                  | 4         | 12.9%   |
| Alcor Micro                            | 4         | 12.9%   |
| Acer                                   | 4         | 12.9%   |
| Sunplus Innovation Technology          | 3         | 9.68%   |
| Chicony Electronics                    | 3         | 9.68%   |
| Suyin                                  | 1         | 3.23%   |
| Silicon Motion                         | 1         | 3.23%   |
| Microdia                               | 1         | 3.23%   |
| Lite-On Technology                     | 1         | 3.23%   |
| IMC Networks                           | 1         | 3.23%   |
| Google                                 | 1         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Apple Built-in iSight                                                      | 3         | 9.38%   |
| Alcor Micro HD WebCam                                                      | 3         | 9.38%   |
| Apple iPhone5/5C/5S/6                                                      | 2         | 6.25%   |
| Acer SunplusIT INC. Integrated Camera                                      | 2         | 6.25%   |
| Suyin HP TrueVision Full HD                                                | 1         | 3.13%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 3.13%   |
| Sunplus Integrated Camera                                                  | 1         | 3.13%   |
| Sunplus HD WebCam                                                          | 1         | 3.13%   |
| Silicon Motion WebCam SC-13HDL12131N                                       | 1         | 3.13%   |
| Realtek USB2.0 camera                                                      | 1         | 3.13%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 3.13%   |
| Realtek Integrated Webcam                                                  | 1         | 3.13%   |
| Realtek HP Truevision HD                                                   | 1         | 3.13%   |
| Microdia USB 2.0 Camera                                                    | 1         | 3.13%   |
| Lite-On Integrated Camera                                                  | 1         | 3.13%   |
| IMC Networks Lenovo EasyCamera                                             | 1         | 3.13%   |
| Chicony USB2.0 UVC WebCam                                                  | 1         | 3.13%   |
| Chicony LG HD WebCam                                                       | 1         | 3.13%   |
| Chicony HD User Facing                                                     | 1         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 1         | 3.13%   |
| Apple iBridge                                                              | 1         | 3.13%   |
| Apple FaceTime HD Camera (Built-in)                                        | 1         | 3.13%   |
| Alcor Micro HP Webcam-101                                                  | 1         | 3.13%   |
| Acer SunplusIT Integrated Camera                                           | 1         | 3.13%   |
| Acer BisonCam, NB Pro                                                      | 1         | 3.13%   |
| Unknown                                                                    | 1         | 3.13%   |

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
| 0     | 26        | 52%     |
| 1     | 19        | 38%     |
| 2     | 3         | 6%      |
| 4     | 1         | 2%      |
| 3     | 1         | 2%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 9         | 28.13%  |
| Bluetooth             | 7         | 21.88%  |
| Fingerprint reader    | 6         | 18.75%  |
| Graphics card         | 5         | 15.63%  |
| Multimedia controller | 3         | 9.38%   |
| Chipcard              | 1         | 3.13%   |
| Camera                | 1         | 3.13%   |

