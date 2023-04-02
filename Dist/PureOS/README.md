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

Total: 78

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Purism        | Librem 5r4                  | Notebook    | [6c71601fdd](https://linux-hardware.org/?probe=6c71601fdd) | Mar 11, 2023 |
| Unknown       | Unknown                     | Soc         | [5d9ced37d2](https://linux-hardware.org/?probe=5d9ced37d2) | Feb 26, 2023 |
| Google        | Droid                       | Notebook    | [e576f650b7](https://linux-hardware.org/?probe=e576f650b7) | Feb 22, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [519a211655](https://linux-hardware.org/?probe=519a211655) | Jan 30, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [edd571ba94](https://linux-hardware.org/?probe=edd571ba94) | Jan 28, 2023 |
| Dell          | Latitude D430               | Notebook    | [e171875163](https://linux-hardware.org/?probe=e171875163) | Jan 27, 2023 |
| Dell          | Latitude D430               | Notebook    | [6245710c10](https://linux-hardware.org/?probe=6245710c10) | Jan 26, 2023 |
| Purism        | librem_mini_v2              | Desktop     | [ded1ed1a93](https://linux-hardware.org/?probe=ded1ed1a93) | Jan 23, 2023 |
| Unknown       | Unknown                     | Soc         | [c7fc2227fd](https://linux-hardware.org/?probe=c7fc2227fd) | Jan 17, 2023 |
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

![OS](./All/images/pie_chart/os_name.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| PureOS 10   | 20        | 35.71%  |
| PureOS 10.0 | 18        | 32.14%  |
| PureOS 9.0  | 13        | 23.21%  |
| PureOS 9    | 3         | 5.36%   |
| PureOS 8    | 2         | 3.57%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| PureOS | 55        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                          | Computers | Percent |
|----------------------------------|-----------|---------|
| 4.19.0-5-amd64                   | 10        | 16.67%  |
| 5.10.0-14-amd64                  | 7         | 11.67%  |
| 5.10.0-13-amd64                  | 5         | 8.33%   |
| 5.10.0-8-amd64                   | 4         | 6.67%   |
| 4.19.0-14-amd64                  | 4         | 6.67%   |
| 5.10.0-11-amd64                  | 3         | 5%      |
| 6.1.0-1-librem5                  | 2         | 3.33%   |
| 5.7.0-1-librem5                  | 2         | 3.33%   |
| 5.10.0-9-amd64                   | 2         | 3.33%   |
| 5.10.0-7-amd64                   | 2         | 3.33%   |
| 5.10.0-21-amd64                  | 2         | 3.33%   |
| 5.10.0-19-amd64                  | 2         | 3.33%   |
| 5.10.0-16-amd64                  | 2         | 3.33%   |
| 6.0.0-1-librem5                  | 1         | 1.67%   |
| 5.9-sunxi64                      | 1         | 1.67%   |
| 5.8-sunxi64                      | 1         | 1.67%   |
| 5.7.0-0.38-1-pinebookpro-hwaccel | 1         | 1.67%   |
| 5.15.0-2-amd64                   | 1         | 1.67%   |
| 5.10.0-6-amd64                   | 1         | 1.67%   |
| 5.10.0-20-amd64                  | 1         | 1.67%   |
| 5.10.0-18-amd64                  | 1         | 1.67%   |
| 5.10.0-17-amd64                  | 1         | 1.67%   |
| 5.10.0-15-amd64                  | 1         | 1.67%   |
| 5.10.0-12-amd64                  | 1         | 1.67%   |
| 4.19.72-imx8-sr                  | 1         | 1.67%   |
| 4.16.0-1-amd64                   | 1         | 1.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 33        | 56.9%   |
| 4.19.0  | 14        | 24.14%  |
| 5.7.0   | 3         | 5.17%   |
| 6.1.0   | 2         | 3.45%   |
| 6.0.0   | 1         | 1.72%   |
| 5.9     | 1         | 1.72%   |
| 5.8     | 1         | 1.72%   |
| 5.15.0  | 1         | 1.72%   |
| 4.19.72 | 1         | 1.72%   |
| 4.16.0  | 1         | 1.72%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 33        | 57.89%  |
| 4.19    | 15        | 26.32%  |
| 5.7     | 3         | 5.26%   |
| 6.1     | 2         | 3.51%   |
| 6.0     | 1         | 1.75%   |
| 5.15    | 1         | 1.75%   |
| 5       | 1         | 1.75%   |
| 4.16    | 1         | 1.75%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 48        | 87.27%  |
| aarch64 | 7         | 12.73%  |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 47        | 81.03%  |
| Unknown         | 6         | 10.34%  |
| KDE5            | 2         | 3.45%   |
| Phosh:GNOME     | 1         | 1.72%   |
| MATE            | 1         | 1.72%   |
| GNOME Flashback | 1         | 1.72%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 40        | 66.67%  |
| X11     | 9         | 15%     |
| Unknown | 6         | 10%     |
| Tty     | 5         | 8.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 32        | 58.18%  |
| GDM     | 15        | 27.27%  |
| GDM3    | 7         | 12.73%  |
| SDDM    | 1         | 1.82%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 24        | 41.38%  |
| de_DE   | 6         | 10.34%  |
| en_GB   | 5         | 8.62%   |
| Unknown | 4         | 6.9%    |
| C       | 3         | 5.17%   |
| ru_RU   | 2         | 3.45%   |
| pt_BR   | 2         | 3.45%   |
| pl_PL   | 2         | 3.45%   |
| it_IT   | 2         | 3.45%   |
| zh_CN   | 1         | 1.72%   |
| pt_PT   | 1         | 1.72%   |
| hu_HU   | 1         | 1.72%   |
| fr_FR   | 1         | 1.72%   |
| es_CR   | 1         | 1.72%   |
| en_IL   | 1         | 1.72%   |
| en_AU   | 1         | 1.72%   |
| bg_BG   | 1         | 1.72%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 47        | 83.93%  |
| EFI  | 9         | 16.07%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 49        | 89.09%  |
| Overlay | 2         | 3.64%   |
| Unknown | 2         | 3.64%   |
| Ext2    | 1         | 1.82%   |
| Btrfs   | 1         | 1.82%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 31        | 54.39%  |
| MBR     | 14        | 24.56%  |
| GPT     | 12        | 21.05%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 47        | 85.45%  |
| Yes       | 8         | 14.55%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 51        | 92.73%  |
| Yes       | 4         | 7.27%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Purism              | 13        | 23.64%  |
| Apple               | 7         | 12.73%  |
| Lenovo              | 6         | 10.91%  |
| Dell                | 6         | 10.91%  |
| Hewlett-Packard     | 4         | 7.27%   |
| Unknown             | 3         | 5.45%   |
| Pine Microsystems   | 2         | 3.64%   |
| Gigabyte Technology | 2         | 3.64%   |
| ASUSTek Computer    | 2         | 3.64%   |
| Acer                | 2         | 3.64%   |
| Toshiba             | 1         | 1.82%   |
| Samsung Electronics | 1         | 1.82%   |
| PCWare              | 1         | 1.82%   |
| Notebook            | 1         | 1.82%   |
| MSI                 | 1         | 1.82%   |
| LG Electronics      | 1         | 1.82%   |
| HUAWEI              | 1         | 1.82%   |
| Google              | 1         | 1.82%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Purism Librem 14                         | 5         | 9.09%   |
| Unknown                                  | 3         | 5.45%   |
| Purism Librem 15 v4                      | 2         | 3.64%   |
| HP Pavilion g6                           | 2         | 3.64%   |
| Toshiba Satellite L500D                  | 1         | 1.82%   |
| Samsung 530U3C/530U4C/532U3C             | 1         | 1.82%   |
| Purism librem_mini_v2                    | 1         | 1.82%   |
| Purism Librem 5r4                        | 1         | 1.82%   |
| Purism Librem 5                          | 1         | 1.82%   |
| Purism Librem 15 v3                      | 1         | 1.82%   |
| Purism Librem 13 v4                      | 1         | 1.82%   |
| Purism Librem 13 v2                      | 1         | 1.82%   |
| Pine Microsystems Pine64 PinePhone (1.2) | 1         | 1.82%   |
| Pine Microsystems Pine64 Pinebook Pro    | 1         | 1.82%   |
| PCWare IPX4005G                          | 1         | 1.82%   |
| Notebook P17SM                           | 1         | 1.82%   |
| MSI MS-7788                              | 1         | 1.82%   |
| LG 22V280-L.BY31P1                       | 1         | 1.82%   |
| Lenovo ThinkPad T540p 20BFS23T00         | 1         | 1.82%   |
| Lenovo ThinkPad T440p                    | 1         | 1.82%   |
| Lenovo ThinkPad T440 20B60044RT          | 1         | 1.82%   |
| Lenovo ThinkPad E480 20KN003SUS          | 1         | 1.82%   |
| Lenovo ThinkPad 13 2nd Gen 20J2S00G00    | 1         | 1.82%   |
| Lenovo IdeaPad U430 Touch 20270          | 1         | 1.82%   |
| HUAWEI NBLB-WAX9N                        | 1         | 1.82%   |
| HP Spectre x360 Convertible              | 1         | 1.82%   |
| HP Pavilion Notebook                     | 1         | 1.82%   |
| Google Droid                             | 1         | 1.82%   |
| Gigabyte GA-MA78GM-UD2H                  | 1         | 1.82%   |
| Gigabyte B85M-DS3H                       | 1         | 1.82%   |
| Dell XPS 13 9370                         | 1         | 1.82%   |
| Dell OptiPlex 760                        | 1         | 1.82%   |
| Dell Latitude D430                       | 1         | 1.82%   |
| Dell Inspiron 5547                       | 1         | 1.82%   |
| Dell Inspiron 3847                       | 1         | 1.82%   |
| Dell Inspiron 15-3567                    | 1         | 1.82%   |
| ASUS EX-A320M-GAMING                     | 1         | 1.82%   |
| ASUS A88X-PLUS/USB                       | 1         | 1.82%   |
| Apple MacBookPro6,1                      | 1         | 1.82%   |
| Apple MacBookPro14,2                     | 1         | 1.82%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Purism Librem            | 13        | 23.64%  |
| Lenovo ThinkPad          | 5         | 9.09%   |
| HP Pavilion              | 3         | 5.45%   |
| Dell Inspiron            | 3         | 5.45%   |
| Unknown                  | 3         | 5.45%   |
| Pine Microsystems Pine64 | 2         | 3.64%   |
| Toshiba Satellite        | 1         | 1.82%   |
| Samsung 530U3C           | 1         | 1.82%   |
| PCWare IPX4005G          | 1         | 1.82%   |
| Notebook P17SM           | 1         | 1.82%   |
| MSI MS-7788              | 1         | 1.82%   |
| LG 22V280-L.BY31P1       | 1         | 1.82%   |
| Lenovo IdeaPad           | 1         | 1.82%   |
| HUAWEI NBLB-WAX9N        | 1         | 1.82%   |
| HP Spectre               | 1         | 1.82%   |
| Google Droid             | 1         | 1.82%   |
| Gigabyte GA-MA78GM-UD2H  | 1         | 1.82%   |
| Gigabyte B85M-DS3H       | 1         | 1.82%   |
| Dell XPS                 | 1         | 1.82%   |
| Dell OptiPlex            | 1         | 1.82%   |
| Dell Latitude            | 1         | 1.82%   |
| ASUS EX-A320M-GAMING     | 1         | 1.82%   |
| ASUS A88X-PLUS           | 1         | 1.82%   |
| Apple MacBookPro6        | 1         | 1.82%   |
| Apple MacBookPro14       | 1         | 1.82%   |
| Apple MacBookAir7        | 1         | 1.82%   |
| Apple MacBook9           | 1         | 1.82%   |
| Apple iMac7              | 1         | 1.82%   |
| Apple iMac13             | 1         | 1.82%   |
| Apple iMac11             | 1         | 1.82%   |
| Acer Swift               | 1         | 1.82%   |
| Acer Nitro               | 1         | 1.82%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 8         | 14.55%  |
| 2013    | 7         | 12.73%  |
| 2021    | 6         | 10.91%  |
| 2018    | 5         | 9.09%   |
| 2017    | 5         | 9.09%   |
| 2019    | 4         | 7.27%   |
| 2015    | 4         | 7.27%   |
| 2020    | 3         | 5.45%   |
| 2011    | 3         | 5.45%   |
| 2016    | 2         | 3.64%   |
| 2009    | 2         | 3.64%   |
| 2007    | 2         | 3.64%   |
| 2023    | 1         | 1.82%   |
| 2014    | 1         | 1.82%   |
| 2012    | 1         | 1.82%   |
| 2010    | 1         | 1.82%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 37        | 67.27%  |
| Desktop        | 9         | 16.36%  |
| All in one     | 4         | 7.27%   |
| System on chip | 3         | 5.45%   |
| Phone          | 1         | 1.82%   |
| Convertible    | 1         | 1.82%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 55        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 42        | 76.36%  |
| Yes  | 13        | 23.64%  |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 12        | 21.82%  |
| 4.01-8.0   | 11        | 20%     |
| 3.01-4.0   | 11        | 20%     |
| 16.01-24.0 | 10        | 18.18%  |
| 32.01-64.0 | 6         | 10.91%  |
| 2.01-3.0   | 2         | 3.64%   |
| 1.01-2.0   | 2         | 3.64%   |
| 24.01-32.0 | 1         | 1.82%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 20        | 32.79%  |
| 1.01-2.0  | 15        | 24.59%  |
| 3.01-4.0  | 12        | 19.67%  |
| 4.01-8.0  | 10        | 16.39%  |
| 8.01-16.0 | 2         | 3.28%   |
| 0.51-1.0  | 1         | 1.64%   |
| 0.01-0.5  | 1         | 1.64%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 37        | 66.07%  |
| 2      | 15        | 26.79%  |
| 0      | 3         | 5.36%   |
| 5      | 1         | 1.79%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 44        | 80%     |
| Yes       | 11        | 20%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 41        | 74.55%  |
| No        | 14        | 25.45%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 42        | 76.36%  |
| No        | 13        | 23.64%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 61.82%  |
| No        | 21        | 38.18%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 13        | 22.81%  |
| Germany                | 8         | 14.04%  |
| UK                     | 6         | 10.53%  |
| Brazil                 | 5         | 8.77%   |
| Italy                  | 3         | 5.26%   |
| Canada                 | 3         | 5.26%   |
| Russia                 | 2         | 3.51%   |
| Poland                 | 2         | 3.51%   |
| France                 | 2         | 3.51%   |
| Australia              | 2         | 3.51%   |
| Turkey                 | 1         | 1.75%   |
| South Africa           | 1         | 1.75%   |
| Portugal               | 1         | 1.75%   |
| Paraguay               | 1         | 1.75%   |
| Israel                 | 1         | 1.75%   |
| Iran                   | 1         | 1.75%   |
| Greece                 | 1         | 1.75%   |
| Costa Rica             | 1         | 1.75%   |
| China                  | 1         | 1.75%   |
| Bulgaria               | 1         | 1.75%   |
| Bosnia and Herzegovina | 1         | 1.75%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Stuttgart     | 3         | 5.08%   |
| Porto Alegre  | 3         | 5.08%   |
| London        | 3         | 5.08%   |
| Warsaw        | 2         | 3.39%   |
| New York      | 2         | 3.39%   |
| Berlin        | 2         | 3.39%   |
| Yuzhnoural'sk | 1         | 1.69%   |
| Wixom         | 1         | 1.69%   |
| Windsor       | 1         | 1.69%   |
| Vancouver     | 1         | 1.69%   |
| Troy          | 1         | 1.69%   |
| Thorpe Hamlet | 1         | 1.69%   |
| Tel Aviv      | 1         | 1.69%   |
| Spencer       | 1         | 1.69%   |
| Sofia         | 1         | 1.69%   |
| Seattle       | 1         | 1.69%   |
| San Jose      | 1         | 1.69%   |
| Paris         | 1         | 1.69%   |
| Montreal      | 1         | 1.69%   |
| Milwaukee     | 1         | 1.69%   |
| Milpitas      | 1         | 1.69%   |
| Milan         | 1         | 1.69%   |
| Melbourne     | 1         | 1.69%   |
| Mankato       | 1         | 1.69%   |
| Liverpool     | 1         | 1.69%   |
| Lenningen     | 1         | 1.69%   |
| Leeds         | 1         | 1.69%   |
| Krasnogorsk   | 1         | 1.69%   |
| Istanbul      | 1         | 1.69%   |
| Hernandarias  | 1         | 1.69%   |
| Harpswell     | 1         | 1.69%   |
| Guimaraes     | 1         | 1.69%   |
| Grasse        | 1         | 1.69%   |
| Genoa         | 1         | 1.69%   |
| Fort Collins  | 1         | 1.69%   |
| Eberswalde    | 1         | 1.69%   |
| Charleston    | 1         | 1.69%   |
| Cape Town     | 1         | 1.69%   |
| Camden        | 1         | 1.69%   |
| Blumenau      | 1         | 1.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 20     | 23.44%  |
| Unknown             | 8         | 12     | 12.5%   |
| Seagate             | 6         | 10     | 9.38%   |
| WDC                 | 5         | 6      | 7.81%   |
| Apple               | 5         | 7      | 7.81%   |
| SanDisk             | 3         | 3      | 4.69%   |
| HGST                | 3         | 3      | 4.69%   |
| A-DATA Technology   | 3         | 4      | 4.69%   |
| Crucial             | 2         | 4      | 3.13%   |
| Win Memory          | 1         | 1      | 1.56%   |
| Transcend           | 1         | 1      | 1.56%   |
| Toshiba             | 1         | 1      | 1.56%   |
| Plextor             | 1         | 1      | 1.56%   |
| Phison              | 1         | 1      | 1.56%   |
| Patriot             | 1         | 1      | 1.56%   |
| Mushkin             | 1         | 1      | 1.56%   |
| JMicron Technology  | 1         | 1      | 1.56%   |
| Intenso             | 1         | 2      | 1.56%   |
| Intel               | 1         | 1      | 1.56%   |
| Hitachi             | 1         | 1      | 1.56%   |
| BIWIN               | 1         | 1      | 1.56%   |
| ASMT                | 1         | 2      | 1.56%   |
| ADATA Technology    | 1         | 1      | 1.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Unknown MMC Card  64GB            | 2         | 2.82%   |
| Unknown MMC Card  32GB            | 2         | 2.82%   |
| Seagate ST1000LM048-2E7172 1TB    | 2         | 2.82%   |
| Samsung SSD 970 PRO 1TB           | 2         | 2.82%   |
| Samsung SSD 860 EVO 250GB         | 2         | 2.82%   |
| Win Memory SWR256G-201II 256GB    | 1         | 1.41%   |
| WDC WDS500G2B0A-00SM50 500GB SSD  | 1         | 1.41%   |
| WDC WDS100T2B0C-00PXH0 1TB        | 1         | 1.41%   |
| WDC WDBNCE2500PNC 250GB SSD       | 1         | 1.41%   |
| WDC WD5000AZRX-00A8LB0 500GB      | 1         | 1.41%   |
| WDC WD3200AAJS-40RYA0 320GB       | 1         | 1.41%   |
| Unknown SH64G  64GB               | 1         | 1.41%   |
| Unknown MMC Card  16GB            | 1         | 1.41%   |
| Unknown DA4128  128GB             | 1         | 1.41%   |
| Unknown AFGCF  128GB              | 1         | 1.41%   |
| Unknown 8GTF4R  8GB               | 1         | 1.41%   |
| Unknown 032G32  32GB              | 1         | 1.41%   |
| Transcend TS240GMTS420S 240GB SSD | 1         | 1.41%   |
| Toshiba NVMe SSD Drive 512GB      | 1         | 1.41%   |
| Seagate ST480HM000-1G5162 480GB   | 1         | 1.41%   |
| Seagate ST3320418AS 320GB         | 1         | 1.41%   |
| Seagate ST31000524AS 1TB          | 1         | 1.41%   |
| Seagate ST1000DM003-1ER162 1TB    | 1         | 1.41%   |
| Seagate NVMe SSD Drive 2TB        | 1         | 1.41%   |
| SanDisk SSD i100 24GB             | 1         | 1.41%   |
| SanDisk SDSSDH3500G 500GB         | 1         | 1.41%   |
| SanDisk NVMe SSD Drive 500GB      | 1         | 1.41%   |
| Samsung SSD 970 EVO Plus 500GB    | 1         | 1.41%   |
| Samsung SSD 970 EVO Plus 2TB      | 1         | 1.41%   |
| Samsung SSD 970 EVO 250GB         | 1         | 1.41%   |
| Samsung SSD 960 EVO 500GB         | 1         | 1.41%   |
| Samsung SSD 960 EVO 250GB         | 1         | 1.41%   |
| Samsung SSD 860 EVO M.2 250GB     | 1         | 1.41%   |
| Samsung SSD 860 EVO 500GB         | 1         | 1.41%   |
| Samsung SSD 860 EVO 1TB           | 1         | 1.41%   |
| Samsung SSD 850 EVO 500GB         | 1         | 1.41%   |
| Samsung SSD 850 EVO 250GB         | 1         | 1.41%   |
| Samsung SSD 830 Series 128GB      | 1         | 1.41%   |
| Samsung NVMe SSD Drive 1TB        | 1         | 1.41%   |
| Samsung HS08XJC 80GB              | 1         | 1.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 9      | 33.33%  |
| HGST                | 3         | 3      | 20%     |
| WDC                 | 2         | 2      | 13.33%  |
| Apple               | 2         | 2      | 13.33%  |
| Samsung Electronics | 1         | 1      | 6.67%   |
| Hitachi             | 1         | 1      | 6.67%   |
| ASMT                | 1         | 2      | 6.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 11     | 29.63%  |
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
| Apple               | 1         | 1      | 3.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 23        | 35     | 38.33%  |
| NVMe | 15        | 18     | 25%     |
| HDD  | 14        | 20     | 23.33%  |
| MMC  | 8         | 12     | 13.33%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 33        | 51     | 55.93%  |
| NVMe | 15        | 18     | 25.42%  |
| MMC  | 8         | 12     | 13.56%  |
| SAS  | 3         | 4      | 5.08%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 25        | 41     | 69.44%  |
| 0.51-1.0   | 9         | 11     | 25%     |
| 1.01-2.0   | 2         | 3      | 5.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 25        | 43.86%  |
| 251-500    | 6         | 10.53%  |
| 101-250    | 6         | 10.53%  |
| 21-50      | 5         | 8.77%   |
| 501-1000   | 4         | 7.02%   |
| 51-100     | 4         | 7.02%   |
| 1001-2000  | 3         | 5.26%   |
| Unknown    | 3         | 5.26%   |
| 2001-3000  | 1         | 1.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 35        | 61.4%   |
| 21-50    | 11        | 19.3%   |
| 101-250  | 3         | 5.26%   |
| 501-1000 | 3         | 5.26%   |
| Unknown  | 3         | 5.26%   |
| 251-500  | 1         | 1.75%   |
| 51-100   | 1         | 1.75%   |

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
| Detected | 37        | 60     | 66.07%  |
| Works    | 16        | 22     | 28.57%  |
| Malfunc  | 3         | 3      | 5.36%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 31        | 59.62%  |
| Samsung Electronics          | 8         | 15.38%  |
| AMD                          | 5         | 9.62%   |
| SanDisk                      | 2         | 3.85%   |
| Apple                        | 2         | 3.85%   |
| Toshiba America Info Systems | 1         | 1.92%   |
| Seagate Technology           | 1         | 1.92%   |
| Phison Electronics           | 1         | 1.92%   |
| ADATA Technology             | 1         | 1.92%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 12.73%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 9.09%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 9.09%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 3         | 5.45%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 3.64%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 3.64%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 3.64%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 3.64%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 3.64%   |
| Apple S3X NVMe Controller                                                      | 2         | 3.64%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 1.82%   |
| Seagate FireCuda 510 SSD                                                       | 1         | 1.82%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 1         | 1.82%   |
| SanDisk Non-Volatile memory controller                                         | 1         | 1.82%   |
| Samsung Electronics SATA controller                                            | 1         | 1.82%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 1.82%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.82%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.82%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 1.82%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 1         | 1.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 1         | 1.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 1         | 1.82%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 1.82%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1         | 1.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 1.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1         | 1.82%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 1.82%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 1         | 1.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 1.82%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 1         | 1.82%   |
| AMD FCH SATA Controller D                                                      | 1         | 1.82%   |
| ADATA Non-Volatile memory controller                                           | 1         | 1.82%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 35        | 66.04%  |
| NVMe | 15        | 28.3%   |
| IDE  | 3         | 5.66%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 43        | 76.79%  |
| ARM     | 6         | 10.71%  |
| AMD     | 5         | 8.93%   |
| Unknown | 2         | 3.57%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| ARM Processor                                 | 6         | 10.71%  |
| Intel Core i7-10710U CPU @ 1.10GHz            | 5         | 8.93%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 7.14%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 3.57%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 3.57%   |
|                                               | 2         | 3.57%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 1.79%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 1.79%   |
| Intel Core m5-6Y54 CPU @ 1.10GHz              | 1         | 1.79%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 1.79%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 1.79%   |
| Intel Core i7-7567U CPU @ 3.50GHz             | 1         | 1.79%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz            | 1         | 1.79%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 1         | 1.79%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 1.79%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 1.79%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 1.79%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 1         | 1.79%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.79%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 1         | 1.79%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 1.79%   |
| Intel Core i5-3330S CPU @ 2.70GHz             | 1         | 1.79%   |
| Intel Core i5-2320 CPU @ 3.00GHz              | 1         | 1.79%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 1.79%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 1         | 1.79%   |
| Intel Core i5 CPU 750 @ 2.67GHz               | 1         | 1.79%   |
| Intel Core i3-4130T CPU @ 2.90GHz             | 1         | 1.79%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 1         | 1.79%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 1.79%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 1         | 1.79%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 1         | 1.79%   |
| Intel Core 2 Duo CPU U7700 @ 1.33GHz          | 1         | 1.79%   |
| Intel Core 2 Duo CPU T7700 @ 2.40GHz          | 1         | 1.79%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 1         | 1.79%   |
| Intel Celeron N4100 CPU @ 1.10GHz             | 1         | 1.79%   |
| Intel Celeron J4005 CPU @ 2.00GHz             | 1         | 1.79%   |
| AMD Turion II Dual-Core Mobile M520           | 1         | 1.79%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 1         | 1.79%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 1         | 1.79%   |
| AMD Athlon II X4 620 Processor                | 1         | 1.79%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 19        | 34.55%  |
| Intel Core i5           | 11        | 20%     |
| Other                   | 7         | 12.73%  |
| Intel Core i3           | 5         | 9.09%   |
| Intel Core 2 Duo        | 3         | 5.45%   |
| Intel Celeron           | 2         | 3.64%   |
| Intel Pentium Silver    | 1         | 1.82%   |
| Intel Pentium           | 1         | 1.82%   |
| Intel Core m5           | 1         | 1.82%   |
| AMD Turion II Dual-Core | 1         | 1.82%   |
| AMD Ryzen 5             | 1         | 1.82%   |
| AMD Ryzen 3             | 1         | 1.82%   |
| AMD Athlon II X4        | 1         | 1.82%   |
| AMD A10                 | 1         | 1.82%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 26        | 47.27%  |
| 4       | 23        | 41.82%  |
| 6       | 5         | 9.09%   |
| Unknown | 1         | 1.82%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 54        | 98.18%  |
| Unknown | 1         | 1.82%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 34        | 61.82%  |
| 1       | 20        | 36.36%  |
| Unknown | 1         | 1.82%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 51        | 91.07%  |
| Unknown        | 4         | 7.14%   |
| 64-bit         | 1         | 1.79%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 40        | 70.18%  |
| 0xa0660    | 3         | 5.26%   |
| 0x406e3    | 3         | 5.26%   |
| 0x706a1    | 2         | 3.51%   |
| 0x40651    | 2         | 3.51%   |
| 0x806ec    | 1         | 1.75%   |
| 0x806e9    | 1         | 1.75%   |
| 0x306d4    | 1         | 1.75%   |
| 0x206a7    | 1         | 1.75%   |
| 0x1067a    | 1         | 1.75%   |
| 0x08108109 | 1         | 1.75%   |
| 0x06003106 | 1         | 1.75%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 11        | 20%     |
| Haswell       | 8         | 14.55%  |
| Unknown       | 7         | 12.73%  |
| CometLake     | 5         | 9.09%   |
| Skylake       | 3         | 5.45%   |
| IvyBridge     | 3         | 5.45%   |
| Goldmont plus | 3         | 5.45%   |
| Zen+          | 2         | 3.64%   |
| SandyBridge   | 2         | 3.64%   |
| K10           | 2         | 3.64%   |
| Core          | 2         | 3.64%   |
| Broadwell     | 2         | 3.64%   |
| Westmere      | 1         | 1.82%   |
| Steamroller   | 1         | 1.82%   |
| Penryn        | 1         | 1.82%   |
| Nehalem       | 1         | 1.82%   |
| Goldmont      | 1         | 1.82%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 39        | 70.91%  |
| Nvidia | 8         | 14.55%  |
| AMD    | 8         | 14.55%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                 | 6         | 10.34%  |
| Intel Comet Lake UHD Graphics                                                         | 5         | 8.62%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 3         | 5.17%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 3         | 5.17%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 2         | 3.45%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 2         | 3.45%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 2         | 3.45%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 2         | 3.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 2         | 3.45%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 2         | 3.45%   |
| Nvidia TU116 [GeForce GTX 1660]                                                       | 1         | 1.72%   |
| Nvidia GT216M [GeForce GT 330M]                                                       | 1         | 1.72%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 1         | 1.72%   |
| Nvidia GK208M [GeForce GT 730M]                                                       | 1         | 1.72%   |
| Nvidia GK208B [GeForce GT 710]                                                        | 1         | 1.72%   |
| Nvidia GK107M [GeForce GT 640M Mac Edition]                                           | 1         | 1.72%   |
| Nvidia GK104M [GeForce GTX 870M]                                                      | 1         | 1.72%   |
| Nvidia GF116 [GeForce GTS 450 Rev. 2]                                                 | 1         | 1.72%   |
| Nvidia GF108 [GeForce GT 630]                                                         | 1         | 1.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 1         | 1.72%   |
| Intel UHD Graphics 620                                                                | 1         | 1.72%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller         | 1         | 1.72%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller             | 1         | 1.72%   |
| Intel Iris Plus Graphics 650                                                          | 1         | 1.72%   |
| Intel HD Graphics 630                                                                 | 1         | 1.72%   |
| Intel HD Graphics 6000                                                                | 1         | 1.72%   |
| Intel HD Graphics 5500                                                                | 1         | 1.72%   |
| Intel HD Graphics 515                                                                 | 1         | 1.72%   |
| Intel GeminiLake [UHD Graphics 605]                                                   | 1         | 1.72%   |
| Intel Core Processor Integrated Graphics Controller                                   | 1         | 1.72%   |
| Intel Apollo Lake [HD Graphics 505]                                                   | 1         | 1.72%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                 | 1         | 1.72%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 1.72%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                             | 1         | 1.72%   |
| AMD RV770/M98L [Mobility Radeon HD 4850]                                              | 1         | 1.72%   |
| AMD RV630/M76 [Mobility Radeon HD 2600 XT/2700]                                       | 1         | 1.72%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                             | 1         | 1.72%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                                    | 1         | 1.72%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                   | 1         | 1.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 31        | 56.36%  |
| Other          | 8         | 14.55%  |
| 1 x AMD        | 5         | 9.09%   |
| 1 x Nvidia     | 4         | 7.27%   |
| Intel + Nvidia | 4         | 7.27%   |
| Intel + AMD    | 2         | 3.64%   |
| 2 x AMD        | 1         | 1.82%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 46        | 83.64%  |
| Unknown | 9         | 16.36%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 54        | 96.43%  |
| 3.01-4.0   | 1         | 1.79%   |
| 0.51-1.0   | 1         | 1.79%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 8         | 14.55%  |
| Chimei Innolux          | 7         | 12.73%  |
| BOE                     | 7         | 12.73%  |
| LG Display              | 6         | 10.91%  |
| Apple                   | 6         | 10.91%  |
| Philips                 | 2         | 3.64%   |
| Goldstar                | 2         | 3.64%   |
| AU Optronics            | 2         | 3.64%   |
| Unknown                 | 1         | 1.82%   |
| Toshiba                 | 1         | 1.82%   |
| Sony                    | 1         | 1.82%   |
| Sharp                   | 1         | 1.82%   |
| RTK                     | 1         | 1.82%   |
| PANDA                   | 1         | 1.82%   |
| Lenovo                  | 1         | 1.82%   |
| Iiyama                  | 1         | 1.82%   |
| Grundig                 | 1         | 1.82%   |
| Dell                    | 1         | 1.82%   |
| Chi Mei Optoelectronics | 1         | 1.82%   |
| BenQ                    | 1         | 1.82%   |
| ASUSTek Computer        | 1         | 1.82%   |
| AOC                     | 1         | 1.82%   |
| Acer                    | 1         | 1.82%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC434B 3840x2160 344x194mm 15.5-inch     | 3         | 5.45%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 3         | 5.45%   |
| Philips TV PHL5035 1920x1080 640x360mm 28.9-inch                          | 2         | 3.64%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 1         | 1.82%   |
| Toshiba LCD Monitor LCD3706 1280x800 261x163mm 12.1-inch                  | 1         | 1.82%   |
| Sony TV SNYAB03 1920x1080                                                 | 1         | 1.82%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                   | 1         | 1.82%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 474x296mm 22.0-inch      | 1         | 1.82%   |
| Samsung Electronics SyncMaster SAM01D3 1440x900 408x225mm 18.3-inch       | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch      | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 410x230mm 18.5-inch      | 1         | 1.82%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 1         | 1.82%   |
| RTK AIO PC RTK2136 1600x900 432x239mm 19.4-inch                           | 1         | 1.82%   |
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch                   | 1         | 1.82%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch              | 1         | 1.82%   |
| LG Display LCD Monitor LGD053B 1920x1080 294x165mm 13.3-inch              | 1         | 1.82%   |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch              | 1         | 1.82%   |
| LG Display LCD Monitor LGD03F0 1366x768 310x174mm 14.0-inch               | 1         | 1.82%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch               | 1         | 1.82%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch               | 1         | 1.82%   |
| Lenovo LEN Y44w-10 LEN65EA 3840x1200 1052x329mm 43.4-inch                 | 1         | 1.82%   |
| Iiyama PL2792H IVM664F 1920x1080 598x336mm 27.0-inch                      | 1         | 1.82%   |
| Grundig WUXGA GRU4448 1920x1080                                           | 1         | 1.82%   |
| Goldstar IPS231 GSM5817 1920x1080 510x290mm 23.1-inch                     | 1         | 1.82%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                    | 1         | 1.82%   |
| Dell P2213 DELF042 1680x1050 473x296mm 22.0-inch                          | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch          | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch           | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN1415 1920x1080 309x173mm 13.9-inch          | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN1365 1920x1080 293x165mm 13.2-inch          | 1         | 1.82%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 1.82%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                     | 1         | 1.82%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                     | 1         | 1.82%   |
| BOE LCD Monitor BOE079A 1920x1080 309x173mm 13.9-inch                     | 1         | 1.82%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                      | 1         | 1.82%   |
| BOE LCD Monitor BOE06C2 1366x768 344x194mm 15.5-inch                      | 1         | 1.82%   |
| BOE LCD Monitor BOE06BE 1920x1080 294x165mm 13.3-inch                     | 1         | 1.82%   |
| BOE LCD Monitor BOE0641 1920x1080 344x193mm 15.5-inch                     | 1         | 1.82%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                         | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO713C 1366x768 309x173mm 13.9-inch             | 1         | 1.82%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 24        | 47.06%  |
| 1366x768 (WXGA)    | 8         | 15.69%  |
| 3840x2160 (4K)     | 6         | 11.76%  |
| 1680x1050 (WSXGA+) | 3         | 5.88%   |
| 1600x900 (HD+)     | 2         | 3.92%   |
| 1440x900 (WXGA+)   | 2         | 3.92%   |
| 3840x1200          | 1         | 1.96%   |
| 2880x1800          | 1         | 1.96%   |
| 2304x1440          | 1         | 1.96%   |
| 2288x1287          | 1         | 1.96%   |
| 1920x1200 (WUXGA)  | 1         | 1.96%   |
| 1280x800 (WXGA)    | 1         | 1.96%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 13     | 15        | 27.27%  |
| 15     | 12        | 21.82%  |
| 23     | 3         | 5.45%   |
| 14     | 3         | 5.45%   |
| 28     | 2         | 3.64%   |
| 24     | 2         | 3.64%   |
| 22     | 2         | 3.64%   |
| 21     | 2         | 3.64%   |
| 20     | 2         | 3.64%   |
| 17     | 2         | 3.64%   |
| 12     | 2         | 3.64%   |
| 142    | 1         | 1.82%   |
| 72     | 1         | 1.82%   |
| 54     | 1         | 1.82%   |
| 43     | 1         | 1.82%   |
| 40     | 1         | 1.82%   |
| 31     | 1         | 1.82%   |
| 27     | 1         | 1.82%   |
| 19     | 1         | 1.82%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 21        | 38.89%  |
| 201-300        | 9         | 16.67%  |
| 401-500        | 7         | 12.96%  |
| 501-600        | 6         | 11.11%  |
| 601-700        | 3         | 5.56%   |
| 351-400        | 3         | 5.56%   |
| 1001-1500      | 2         | 3.7%    |
| More than 2000 | 1         | 1.85%   |
| 801-900        | 1         | 1.85%   |
| 1501-2000      | 1         | 1.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 36        | 76.6%   |
| 16/10 | 9         | 19.15%  |
| 3.20  | 1         | 2.13%   |
| 1.00  | 1         | 2.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 12        | 21.82%  |
| 81-90          | 11        | 20%     |
| 201-250        | 9         | 16.36%  |
| 71-80          | 7         | 12.73%  |
| More than 1000 | 3         | 5.45%   |
| 351-500        | 3         | 5.45%   |
| 151-200        | 3         | 5.45%   |
| 61-70          | 2         | 3.64%   |
| 501-1000       | 2         | 3.64%   |
| 301-350        | 1         | 1.82%   |
| 131-140        | 1         | 1.82%   |
| 121-130        | 1         | 1.82%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 17        | 30.91%  |
| 121-160       | 16        | 29.09%  |
| 101-120       | 8         | 14.55%  |
| More than 240 | 6         | 10.91%  |
| 161-240       | 5         | 9.09%   |
| 1-50          | 3         | 5.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 38        | 69.09%  |
| 2     | 8         | 14.55%  |
| 0     | 8         | 14.55%  |
| 3     | 1         | 1.82%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 30        | 37.04%  |
| Qualcomm Atheros                | 16        | 19.75%  |
| Intel                           | 14        | 17.28%  |
| Broadcom                        | 8         | 9.88%   |
| Broadcom Limited                | 4         | 4.94%   |
| ASIX Electronics                | 2         | 2.47%   |
| Ralink                          | 1         | 1.23%   |
| Qualcomm Atheros Communications | 1         | 1.23%   |
| OPPO Electronics                | 1         | 1.23%   |
| MediaTek                        | 1         | 1.23%   |
| Marvell Technology Group        | 1         | 1.23%   |
| Edimax Technology               | 1         | 1.23%   |
| ASUSTek Computer                | 1         | 1.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 20        | 22.73%  |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 11        | 12.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 5         | 5.68%   |
| Intel Wireless 7265                                                           | 4         | 4.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 3         | 3.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 3         | 3.41%   |
| Intel Wireless 7260                                                           | 3         | 3.41%   |
| Intel Ethernet Connection I217-LM                                             | 2         | 2.27%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2         | 2.27%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                    | 2         | 2.27%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 2         | 2.27%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1         | 1.14%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 1.14%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 1         | 1.14%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 1.14%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1         | 1.14%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                        | 1         | 1.14%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 1.14%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 1.14%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.14%   |
| OPPO RMX3263                                                                  | 1         | 1.14%   |
| MediaTek WiFi                                                                 | 1         | 1.14%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                       | 1         | 1.14%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 1.14%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1         | 1.14%   |
| Intel Ethernet Connection I218-V                                              | 1         | 1.14%   |
| Intel Ethernet Connection (4) I219-V                                          | 1         | 1.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 1.14%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 1         | 1.14%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 1.14%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1         | 1.14%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                                   | 1         | 1.14%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 1         | 1.14%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                       | 1         | 1.14%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                                        | 1         | 1.14%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                        | 1         | 1.14%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 1         | 1.14%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                            | 1         | 1.14%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 1         | 1.14%   |
| Broadcom BCM4321 802.11a/b/g/n                                                | 1         | 1.14%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 16        | 34.04%  |
| Intel                           | 12        | 25.53%  |
| Realtek Semiconductor           | 5         | 10.64%  |
| Broadcom                        | 5         | 10.64%  |
| Broadcom Limited                | 4         | 8.51%   |
| Ralink                          | 1         | 2.13%   |
| Qualcomm Atheros Communications | 1         | 2.13%   |
| MediaTek                        | 1         | 2.13%   |
| Edimax Technology               | 1         | 2.13%   |
| ASUSTek Computer                | 1         | 2.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 11        | 23.4%   |
| Intel Wireless 7265                                                           | 4         | 8.51%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 3         | 6.38%   |
| Intel Wireless 7260                                                           | 3         | 6.38%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                    | 2         | 4.26%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1         | 2.13%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 2.13%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 1         | 2.13%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 2.13%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1         | 2.13%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                        | 1         | 2.13%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 2.13%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 2.13%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 2.13%   |
| MediaTek WiFi                                                                 | 1         | 2.13%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 2.13%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1         | 2.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 2.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 1         | 2.13%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 2.13%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                                   | 1         | 2.13%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                                        | 1         | 2.13%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                        | 1         | 2.13%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 1         | 2.13%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                            | 1         | 2.13%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 1         | 2.13%   |
| Broadcom BCM4321 802.11a/b/g/n                                                | 1         | 2.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 1         | 2.13%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                     | 1         | 2.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 27        | 67.5%   |
| Intel                    | 5         | 12.5%   |
| Broadcom                 | 4         | 10%     |
| ASIX Electronics         | 2         | 5%      |
| OPPO Electronics         | 1         | 2.5%    |
| Marvell Technology Group | 1         | 2.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 20        | 48.78%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 12.2%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 7.32%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 4.88%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 4.88%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 4.88%   |
| OPPO RMX3263                                                      | 1         | 2.44%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 2.44%   |
| Intel Ethernet Connection I218-V                                  | 1         | 2.44%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 2.44%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 2.44%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 2.44%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 2.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 41        | 51.25%  |
| Ethernet | 39        | 48.75%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 30        | 62.5%   |
| WiFi     | 18        | 37.5%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 26        | 47.27%  |
| 1     | 20        | 36.36%  |
| 0     | 8         | 14.55%  |
| 3     | 1         | 1.82%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 43        | 78.18%  |
| Yes  | 12        | 21.82%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 11        | 31.43%  |
| Apple                           | 6         | 17.14%  |
| Qualcomm Atheros Communications | 5         | 14.29%  |
| Foxconn / Hon Hai               | 5         | 14.29%  |
| Lite-On Technology              | 4         | 11.43%  |
| Realtek Semiconductor           | 1         | 2.86%   |
| Cambridge Silicon Radio         | 1         | 2.86%   |
| Broadcom                        | 1         | 2.86%   |
| ASUSTek Computer                | 1         | 2.86%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 7         | 20%     |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 14.29%  |
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 11.43%  |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 5.71%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 5.71%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 5.71%   |
| Apple Bluetooth USB Host Controller                 | 2         | 5.71%   |
| Apple Bluetooth Host Controller                     | 2         | 5.71%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 2.86%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 2.86%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.86%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.86%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.86%   |
| Broadcom HP Portable Valentine                      | 1         | 2.86%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 2.86%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 2.86%   |
| Apple Bluetooth HCI                                 | 1         | 2.86%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 42        | 70%     |
| AMD      | 7         | 11.67%  |
| Nvidia   | 6         | 10%     |
| XMOS     | 1         | 1.67%   |
| Shure    | 1         | 1.67%   |
| Micronas | 1         | 1.67%   |
| M-Audio  | 1         | 1.67%   |
| Logitech | 1         | 1.67%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 11        | 15.28%  |
| Intel Comet Lake PCH-LP cAVS                                               | 7         | 9.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 5.56%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 5.56%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 4.17%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 4.17%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 4.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 4.17%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 2.78%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 2.78%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 2.78%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 2.78%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 2.78%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.78%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 2.78%   |
| XMOS xCORE USB Audio 2.0                                                   | 1         | 1.39%   |
| Shure MV5                                                                  | 1         | 1.39%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 1.39%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 1.39%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.39%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.39%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 1.39%   |
| Nvidia GF116 High Definition Audio Controller                              | 1         | 1.39%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.39%   |
| Micronas QSB                                                               | 1         | 1.39%   |
| M-Audio M-Audio Fast Track MKII                                            | 1         | 1.39%   |
| Logitech Headset H340                                                      | 1         | 1.39%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 1.39%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.39%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1.39%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1         | 1.39%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 1.39%   |
| AMD RV770 HDMI Audio [Radeon HD 4850/4870]                                 | 1         | 1.39%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 1.39%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.39%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 7         | 30.43%  |
| Samsung Electronics | 4         | 17.39%  |
| Crucial             | 4         | 17.39%  |
| Unknown             | 3         | 13.04%  |
| Toshiba             | 2         | 8.7%    |
| Smart               | 1         | 4.35%   |
| Micron Technology   | 1         | 4.35%   |
| Kingston            | 1         | 4.35%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 2         | 8%      |
| Crucial RAM CT16G4SFD824A.M16FRS 16GB SODIMM DDR4 2400MT/s       | 2         | 8%      |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 4%      |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 4%      |
| Unknown RAM Module 16384MB 2133MT/s                              | 1         | 4%      |
| Toshiba RAM 9905711-015.A00G 4GB SODIMM DDR4 2400MT/s            | 1         | 4%      |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s               | 1         | 4%      |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s                | 1         | 4%      |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s            | 1         | 4%      |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 4%      |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 4%      |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 4%      |
| SK hynix RAM HMP125U6EFR8C-S6 2GB DIMM DDR2 800MT/s              | 1         | 4%      |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 4%      |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 4%      |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 4%      |
| SK hynix RAM H9CCNNNBLTALAR-NTD 4GB Row Of Chips LPDDR3 1600MT/s | 1         | 4%      |
| Samsung RAM Module 4GB SODIMM LPDDR3 1867MT/s                    | 1         | 4%      |
| Samsung RAM K4A8G165WC-BCTD 4GB SODIMM DDR4 2667MT/s             | 1         | 4%      |
| Micron RAM 16HTF25664AZ-800H1 2GB DIMM DDR2 800MT/s              | 1         | 4%      |
| Kingston RAM 9905471-011.A00LF 4GB DIMM DDR3 1600MT/s            | 1         | 4%      |
| Crucial RAM CT4G4SFS8213.C8FBD1 4GB SODIMM DDR4 2133MT/s         | 1         | 4%      |
| Crucial RAM CT16G4S24AM.M16FE 16GB SODIMM DDR4 2400MT/s          | 1         | 4%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 10        | 50%     |
| DDR3    | 5         | 25%     |
| LPDDR3  | 2         | 10%     |
| DDR2    | 2         | 10%     |
| Unknown | 1         | 5%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 15        | 75%     |
| DIMM         | 3         | 15%     |
| Row Of Chips | 1         | 5%      |
| Unknown      | 1         | 5%      |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 11        | 50%     |
| 16384 | 4         | 18.18%  |
| 8192  | 4         | 18.18%  |
| 32768 | 2         | 9.09%   |
| 2048  | 1         | 4.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 6         | 27.27%  |
| 1600  | 6         | 27.27%  |
| 2400  | 4         | 18.18%  |
| 2133  | 2         | 9.09%   |
| 1867  | 1         | 4.55%   |
| 1333  | 1         | 4.55%   |
| 1066  | 1         | 4.55%   |
| 800   | 1         | 4.55%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Brother Industries | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Apple                                  | 6         | 18.18%  |
| Realtek Semiconductor                  | 4         | 12.12%  |
| Chicony Electronics                    | 4         | 12.12%  |
| Alcor Micro                            | 4         | 12.12%  |
| Acer                                   | 4         | 12.12%  |
| Sunplus Innovation Technology          | 3         | 9.09%   |
| Suyin                                  | 1         | 3.03%   |
| Silicon Motion                         | 1         | 3.03%   |
| Quanta                                 | 1         | 3.03%   |
| Microdia                               | 1         | 3.03%   |
| Lite-On Technology                     | 1         | 3.03%   |
| IMC Networks                           | 1         | 3.03%   |
| Google                                 | 1         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.03%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Apple Built-in iSight                                                      | 3         | 8.82%   |
| Alcor Micro HD WebCam                                                      | 3         | 8.82%   |
| Chicony HD User Facing                                                     | 2         | 5.88%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 2         | 5.88%   |
| Acer SunplusIT INC. Integrated Camera                                      | 2         | 5.88%   |
| Suyin HP TrueVision Full HD                                                | 1         | 2.94%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 2.94%   |
| Sunplus Integrated Camera                                                  | 1         | 2.94%   |
| Sunplus HD WebCam                                                          | 1         | 2.94%   |
| Silicon Motion WebCam SC-13HDL12131N                                       | 1         | 2.94%   |
| Realtek USB2.0 camera                                                      | 1         | 2.94%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 2.94%   |
| Realtek Integrated Webcam                                                  | 1         | 2.94%   |
| Realtek HP Truevision HD                                                   | 1         | 2.94%   |
| Quanta HD Camera                                                           | 1         | 2.94%   |
| Microdia HP Integrated Webcam                                              | 1         | 2.94%   |
| Lite-On Integrated Camera                                                  | 1         | 2.94%   |
| IMC Networks Lenovo EasyCamera                                             | 1         | 2.94%   |
| Chicony USB2.0 UVC WebCam                                                  | 1         | 2.94%   |
| Chicony LG HD WebCam                                                       | 1         | 2.94%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 1         | 2.94%   |
| Apple iBridge                                                              | 1         | 2.94%   |
| Apple FaceTime HD Camera (Built-in)                                        | 1         | 2.94%   |
| Alcor Micro HP Webcam-101                                                  | 1         | 2.94%   |
| Acer SunplusIT Integrated Camera                                           | 1         | 2.94%   |
| Acer BisonCam, NB Pro                                                      | 1         | 2.94%   |
| Unknown                                                                    | 1         | 2.94%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 3         | 42.86%  |
| LighTuning Technology | 2         | 28.57%  |
| Synaptics             | 1         | 14.29%  |
| STMicroelectronics    | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor     | 3         | 42.86%  |
| Synaptics Metallica MOH Touch Fingerprint Reader | 1         | 14.29%  |
| STMicroelectronics Fingerprint Reader            | 1         | 14.29%  |
| LighTuning ES603 Swipe Fingerprint Sensor        | 1         | 14.29%  |
| LighTuning EgisTec Touch Fingerprint Sensor      | 1         | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Purism, SPC | 3         | 50%     |
| O2 Micro    | 1         | 16.67%  |
| Clay Logic  | 1         | 16.67%  |
| Alcor Micro | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Purism, SPC Librem Key              | 3         | 50%     |
| O2 Micro Oz776 SmartCard Reader     | 1         | 16.67%  |
| Clay Logic Nitrokey Pro             | 1         | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 30        | 53.57%  |
| 1     | 20        | 35.71%  |
| 2     | 3         | 5.36%   |
| 3     | 2         | 3.57%   |
| 4     | 1         | 1.79%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 10        | 27.78%  |
| Fingerprint reader    | 7         | 19.44%  |
| Bluetooth             | 7         | 19.44%  |
| Graphics card         | 6         | 16.67%  |
| Multimedia controller | 3         | 8.33%   |
| Chipcard              | 2         | 5.56%   |
| Camera                | 1         | 2.78%   |

