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

Total: 82

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Purism        | Librem 14                   | Notebook    | [8462dbaccb](https://linux-hardware.org/?probe=8462dbaccb) | Apr 25, 2023 |
| Shuttle       | DS10U                       | Desktop     | [ffcce61d82](https://linux-hardware.org/?probe=ffcce61d82) | Apr 22, 2023 |
| Shuttle       | DS10U                       | Desktop     | [b25013d04f](https://linux-hardware.org/?probe=b25013d04f) | Apr 18, 2023 |
| Shuttle       | DS10U                       | Desktop     | [a35fd102f2](https://linux-hardware.org/?probe=a35fd102f2) | Apr 04, 2023 |
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
| PureOS 10.0 | 20        | 34.48%  |
| PureOS 10   | 20        | 34.48%  |
| PureOS 9.0  | 13        | 22.41%  |
| PureOS 9    | 3         | 5.17%   |
| PureOS 8    | 2         | 3.45%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| PureOS | 57        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                          | Computers | Percent |
|----------------------------------|-----------|---------|
| 4.19.0-5-amd64                   | 10        | 16.13%  |
| 5.10.0-14-amd64                  | 7         | 11.29%  |
| 5.10.0-13-amd64                  | 5         | 8.06%   |
| 5.10.0-8-amd64                   | 4         | 6.45%   |
| 5.10.0-21-amd64                  | 4         | 6.45%   |
| 4.19.0-14-amd64                  | 4         | 6.45%   |
| 5.10.0-11-amd64                  | 3         | 4.84%   |
| 6.1.0-1-librem5                  | 2         | 3.23%   |
| 5.7.0-1-librem5                  | 2         | 3.23%   |
| 5.10.0-9-amd64                   | 2         | 3.23%   |
| 5.10.0-7-amd64                   | 2         | 3.23%   |
| 5.10.0-19-amd64                  | 2         | 3.23%   |
| 5.10.0-16-amd64                  | 2         | 3.23%   |
| 6.0.0-1-librem5                  | 1         | 1.61%   |
| 5.9-sunxi64                      | 1         | 1.61%   |
| 5.8-sunxi64                      | 1         | 1.61%   |
| 5.7.0-0.38-1-pinebookpro-hwaccel | 1         | 1.61%   |
| 5.15.0-2-amd64                   | 1         | 1.61%   |
| 5.10.0-6-amd64                   | 1         | 1.61%   |
| 5.10.0-20-amd64                  | 1         | 1.61%   |
| 5.10.0-18-amd64                  | 1         | 1.61%   |
| 5.10.0-17-amd64                  | 1         | 1.61%   |
| 5.10.0-15-amd64                  | 1         | 1.61%   |
| 5.10.0-12-amd64                  | 1         | 1.61%   |
| 4.19.72-imx8-sr                  | 1         | 1.61%   |
| 4.16.0-1-amd64                   | 1         | 1.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 35        | 58.33%  |
| 4.19.0  | 14        | 23.33%  |
| 5.7.0   | 3         | 5%      |
| 6.1.0   | 2         | 3.33%   |
| 6.0.0   | 1         | 1.67%   |
| 5.9     | 1         | 1.67%   |
| 5.8     | 1         | 1.67%   |
| 5.15.0  | 1         | 1.67%   |
| 4.19.72 | 1         | 1.67%   |
| 4.16.0  | 1         | 1.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 35        | 59.32%  |
| 4.19    | 15        | 25.42%  |
| 5.7     | 3         | 5.08%   |
| 6.1     | 2         | 3.39%   |
| 6.0     | 1         | 1.69%   |
| 5.15    | 1         | 1.69%   |
| 5       | 1         | 1.69%   |
| 4.16    | 1         | 1.69%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 50        | 87.72%  |
| aarch64 | 7         | 12.28%  |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 49        | 81.67%  |
| Unknown         | 6         | 10%     |
| KDE5            | 2         | 3.33%   |
| Phosh:GNOME     | 1         | 1.67%   |
| MATE            | 1         | 1.67%   |
| GNOME Flashback | 1         | 1.67%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 42        | 67.74%  |
| X11     | 9         | 14.52%  |
| Unknown | 6         | 9.68%   |
| Tty     | 5         | 8.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 34        | 59.65%  |
| GDM     | 15        | 26.32%  |
| GDM3    | 7         | 12.28%  |
| SDDM    | 1         | 1.75%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 25        | 41.67%  |
| de_DE   | 6         | 10%     |
| en_GB   | 5         | 8.33%   |
| Unknown | 4         | 6.67%   |
| C       | 3         | 5%      |
| ru_RU   | 2         | 3.33%   |
| pt_BR   | 2         | 3.33%   |
| pl_PL   | 2         | 3.33%   |
| it_IT   | 2         | 3.33%   |
| en_AU   | 2         | 3.33%   |
| zh_CN   | 1         | 1.67%   |
| pt_PT   | 1         | 1.67%   |
| hu_HU   | 1         | 1.67%   |
| fr_FR   | 1         | 1.67%   |
| es_CR   | 1         | 1.67%   |
| en_IL   | 1         | 1.67%   |
| bg_BG   | 1         | 1.67%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 49        | 84.48%  |
| EFI  | 9         | 15.52%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 51        | 89.47%  |
| Overlay | 2         | 3.51%   |
| Unknown | 2         | 3.51%   |
| Ext2    | 1         | 1.75%   |
| Btrfs   | 1         | 1.75%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 33        | 55.93%  |
| MBR     | 14        | 23.73%  |
| GPT     | 12        | 20.34%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 49        | 85.96%  |
| Yes       | 8         | 14.04%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 53        | 92.98%  |
| Yes       | 4         | 7.02%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Purism              | 14        | 24.56%  |
| Apple               | 7         | 12.28%  |
| Lenovo              | 6         | 10.53%  |
| Dell                | 6         | 10.53%  |
| Hewlett-Packard     | 4         | 7.02%   |
| Unknown             | 3         | 5.26%   |
| Pine Microsystems   | 2         | 3.51%   |
| Gigabyte Technology | 2         | 3.51%   |
| ASUSTek Computer    | 2         | 3.51%   |
| Acer                | 2         | 3.51%   |
| Toshiba             | 1         | 1.75%   |
| Shuttle             | 1         | 1.75%   |
| Samsung Electronics | 1         | 1.75%   |
| PCWare              | 1         | 1.75%   |
| Notebook            | 1         | 1.75%   |
| MSI                 | 1         | 1.75%   |
| LG Electronics      | 1         | 1.75%   |
| HUAWEI              | 1         | 1.75%   |
| Google              | 1         | 1.75%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Purism Librem 14                         | 6         | 10.53%  |
| Unknown                                  | 3         | 5.26%   |
| Purism Librem 15 v4                      | 2         | 3.51%   |
| HP Pavilion g6                           | 2         | 3.51%   |
| Toshiba Satellite L500D                  | 1         | 1.75%   |
| Shuttle DS10U                            | 1         | 1.75%   |
| Samsung 530U3C/530U4C/532U3C             | 1         | 1.75%   |
| Purism librem_mini_v2                    | 1         | 1.75%   |
| Purism Librem 5r4                        | 1         | 1.75%   |
| Purism Librem 5                          | 1         | 1.75%   |
| Purism Librem 15 v3                      | 1         | 1.75%   |
| Purism Librem 13 v4                      | 1         | 1.75%   |
| Purism Librem 13 v2                      | 1         | 1.75%   |
| Pine Microsystems Pine64 PinePhone (1.2) | 1         | 1.75%   |
| Pine Microsystems Pine64 Pinebook Pro    | 1         | 1.75%   |
| PCWare IPX4005G                          | 1         | 1.75%   |
| Notebook P17SM                           | 1         | 1.75%   |
| MSI MS-7788                              | 1         | 1.75%   |
| LG 22V280-L.BY31P1                       | 1         | 1.75%   |
| Lenovo ThinkPad T540p 20BFS23T00         | 1         | 1.75%   |
| Lenovo ThinkPad T440p                    | 1         | 1.75%   |
| Lenovo ThinkPad T440 20B60044RT          | 1         | 1.75%   |
| Lenovo ThinkPad E480 20KN003SUS          | 1         | 1.75%   |
| Lenovo ThinkPad 13 2nd Gen 20J2S00G00    | 1         | 1.75%   |
| Lenovo IdeaPad U430 Touch 20270          | 1         | 1.75%   |
| HUAWEI NBLB-WAX9N                        | 1         | 1.75%   |
| HP Spectre x360 Convertible              | 1         | 1.75%   |
| HP Pavilion Notebook                     | 1         | 1.75%   |
| Google Droid                             | 1         | 1.75%   |
| Gigabyte GA-MA78GM-UD2H                  | 1         | 1.75%   |
| Gigabyte B85M-DS3H                       | 1         | 1.75%   |
| Dell XPS 13 9370                         | 1         | 1.75%   |
| Dell OptiPlex 760                        | 1         | 1.75%   |
| Dell Latitude D430                       | 1         | 1.75%   |
| Dell Inspiron 5547                       | 1         | 1.75%   |
| Dell Inspiron 3847                       | 1         | 1.75%   |
| Dell Inspiron 15-3567                    | 1         | 1.75%   |
| ASUS EX-A320M-GAMING                     | 1         | 1.75%   |
| ASUS A88X-PLUS/USB                       | 1         | 1.75%   |
| Apple MacBookPro6,1                      | 1         | 1.75%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Purism Librem            | 14        | 24.56%  |
| Lenovo ThinkPad          | 5         | 8.77%   |
| HP Pavilion              | 3         | 5.26%   |
| Dell Inspiron            | 3         | 5.26%   |
| Unknown                  | 3         | 5.26%   |
| Pine Microsystems Pine64 | 2         | 3.51%   |
| Toshiba Satellite        | 1         | 1.75%   |
| Shuttle DS10U            | 1         | 1.75%   |
| Samsung 530U3C           | 1         | 1.75%   |
| PCWare IPX4005G          | 1         | 1.75%   |
| Notebook P17SM           | 1         | 1.75%   |
| MSI MS-7788              | 1         | 1.75%   |
| LG 22V280-L.BY31P1       | 1         | 1.75%   |
| Lenovo IdeaPad           | 1         | 1.75%   |
| HUAWEI NBLB-WAX9N        | 1         | 1.75%   |
| HP Spectre               | 1         | 1.75%   |
| Google Droid             | 1         | 1.75%   |
| Gigabyte GA-MA78GM-UD2H  | 1         | 1.75%   |
| Gigabyte B85M-DS3H       | 1         | 1.75%   |
| Dell XPS                 | 1         | 1.75%   |
| Dell OptiPlex            | 1         | 1.75%   |
| Dell Latitude            | 1         | 1.75%   |
| ASUS EX-A320M-GAMING     | 1         | 1.75%   |
| ASUS A88X-PLUS           | 1         | 1.75%   |
| Apple MacBookPro6        | 1         | 1.75%   |
| Apple MacBookPro14       | 1         | 1.75%   |
| Apple MacBookAir7        | 1         | 1.75%   |
| Apple MacBook9           | 1         | 1.75%   |
| Apple iMac7              | 1         | 1.75%   |
| Apple iMac13             | 1         | 1.75%   |
| Apple iMac11             | 1         | 1.75%   |
| Acer Swift               | 1         | 1.75%   |
| Acer Nitro               | 1         | 1.75%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 9         | 15.79%  |
| 2013    | 7         | 12.28%  |
| 2021    | 6         | 10.53%  |
| 2019    | 5         | 8.77%   |
| 2018    | 5         | 8.77%   |
| 2017    | 5         | 8.77%   |
| 2015    | 4         | 7.02%   |
| 2020    | 3         | 5.26%   |
| 2011    | 3         | 5.26%   |
| 2016    | 2         | 3.51%   |
| 2009    | 2         | 3.51%   |
| 2007    | 2         | 3.51%   |
| 2023    | 1         | 1.75%   |
| 2014    | 1         | 1.75%   |
| 2012    | 1         | 1.75%   |
| 2010    | 1         | 1.75%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 38        | 66.67%  |
| Desktop        | 10        | 17.54%  |
| All in one     | 4         | 7.02%   |
| System on chip | 3         | 5.26%   |
| Phone          | 1         | 1.75%   |
| Convertible    | 1         | 1.75%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 57        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 43        | 75.44%  |
| Yes  | 14        | 24.56%  |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 12        | 21.05%  |
| 8.01-16.0  | 12        | 21.05%  |
| 4.01-8.0   | 11        | 19.3%   |
| 16.01-24.0 | 11        | 19.3%   |
| 32.01-64.0 | 6         | 10.53%  |
| 2.01-3.0   | 2         | 3.51%   |
| 1.01-2.0   | 2         | 3.51%   |
| 24.01-32.0 | 1         | 1.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 20        | 31.75%  |
| 1.01-2.0  | 16        | 25.4%   |
| 3.01-4.0  | 12        | 19.05%  |
| 4.01-8.0  | 11        | 17.46%  |
| 8.01-16.0 | 2         | 3.17%   |
| 0.51-1.0  | 1         | 1.59%   |
| 0.01-0.5  | 1         | 1.59%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 39        | 67.24%  |
| 2      | 15        | 25.86%  |
| 0      | 3         | 5.17%   |
| 5      | 1         | 1.72%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 46        | 80.7%   |
| Yes       | 11        | 19.3%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 75.44%  |
| No        | 14        | 24.56%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 44        | 77.19%  |
| No        | 13        | 22.81%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 63.16%  |
| No        | 21        | 36.84%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 13        | 22.03%  |
| Germany                | 8         | 13.56%  |
| UK                     | 6         | 10.17%  |
| Brazil                 | 6         | 10.17%  |
| Italy                  | 3         | 5.08%   |
| Canada                 | 3         | 5.08%   |
| Australia              | 3         | 5.08%   |
| Russia                 | 2         | 3.39%   |
| Poland                 | 2         | 3.39%   |
| France                 | 2         | 3.39%   |
| Turkey                 | 1         | 1.69%   |
| South Africa           | 1         | 1.69%   |
| Portugal               | 1         | 1.69%   |
| Paraguay               | 1         | 1.69%   |
| Israel                 | 1         | 1.69%   |
| Iran                   | 1         | 1.69%   |
| Greece                 | 1         | 1.69%   |
| Costa Rica             | 1         | 1.69%   |
| China                  | 1         | 1.69%   |
| Bulgaria               | 1         | 1.69%   |
| Bosnia and Herzegovina | 1         | 1.69%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Stuttgart     | 3         | 4.92%   |
| Porto Alegre  | 3         | 4.92%   |
| London        | 3         | 4.92%   |
| Warsaw        | 2         | 3.28%   |
| New York      | 2         | 3.28%   |
| Berlin        | 2         | 3.28%   |
| Yuzhnoural'sk | 1         | 1.64%   |
| Wixom         | 1         | 1.64%   |
| Windsor       | 1         | 1.64%   |
| Vancouver     | 1         | 1.64%   |
| Troy          | 1         | 1.64%   |
| Thorpe Hamlet | 1         | 1.64%   |
| Tel Aviv      | 1         | 1.64%   |
| Spencer       | 1         | 1.64%   |
| Sofia         | 1         | 1.64%   |
| Seattle       | 1         | 1.64%   |
| Sao Paulo     | 1         | 1.64%   |
| San Jose      | 1         | 1.64%   |
| Perth         | 1         | 1.64%   |
| Paris         | 1         | 1.64%   |
| Montreal      | 1         | 1.64%   |
| Milwaukee     | 1         | 1.64%   |
| Milpitas      | 1         | 1.64%   |
| Milan         | 1         | 1.64%   |
| Melbourne     | 1         | 1.64%   |
| Mankato       | 1         | 1.64%   |
| Liverpool     | 1         | 1.64%   |
| Lenningen     | 1         | 1.64%   |
| Leeds         | 1         | 1.64%   |
| Krasnogorsk   | 1         | 1.64%   |
| Istanbul      | 1         | 1.64%   |
| Hernandarias  | 1         | 1.64%   |
| Harpswell     | 1         | 1.64%   |
| Guimaraes     | 1         | 1.64%   |
| Grasse        | 1         | 1.64%   |
| Genoa         | 1         | 1.64%   |
| Fort Collins  | 1         | 1.64%   |
| Eberswalde    | 1         | 1.64%   |
| Charleston    | 1         | 1.64%   |
| Cape Town     | 1         | 1.64%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 21     | 24.24%  |
| Unknown             | 8         | 12     | 12.12%  |
| Seagate             | 6         | 10     | 9.09%   |
| WDC                 | 5         | 6      | 7.58%   |
| Apple               | 5         | 7      | 7.58%   |
| SanDisk             | 3         | 3      | 4.55%   |
| HGST                | 3         | 3      | 4.55%   |
| A-DATA Technology   | 3         | 4      | 4.55%   |
| Crucial             | 2         | 4      | 3.03%   |
| Win Memory          | 1         | 1      | 1.52%   |
| Transcend           | 1         | 1      | 1.52%   |
| Toshiba             | 1         | 1      | 1.52%   |
| PNY                 | 1         | 1      | 1.52%   |
| Plextor             | 1         | 1      | 1.52%   |
| Phison              | 1         | 1      | 1.52%   |
| Patriot             | 1         | 1      | 1.52%   |
| Mushkin             | 1         | 1      | 1.52%   |
| JMicron Technology  | 1         | 1      | 1.52%   |
| Intenso             | 1         | 2      | 1.52%   |
| Intel               | 1         | 1      | 1.52%   |
| Hitachi             | 1         | 1      | 1.52%   |
| BIWIN               | 1         | 1      | 1.52%   |
| ASMT                | 1         | 2      | 1.52%   |
| ADATA Technology    | 1         | 1      | 1.52%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown MMC Card  64GB                            | 2         | 2.74%   |
| Unknown MMC Card  32GB                            | 2         | 2.74%   |
| Seagate ST1000LM048-2E7172 1TB                    | 2         | 2.74%   |
| Samsung SSD 970 PRO 1TB                           | 2         | 2.74%   |
| Samsung SSD 860 EVO 250GB                         | 2         | 2.74%   |
| Win Memory SWR256G-201II 256GB                    | 1         | 1.37%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 1         | 1.37%   |
| WDC WDS100T2B0C-00PXH0 1TB                        | 1         | 1.37%   |
| WDC WDBNCE2500PNC 250GB SSD                       | 1         | 1.37%   |
| WDC WD5000AZRX-00A8LB0 500GB                      | 1         | 1.37%   |
| WDC WD3200AAJS-40RYA0 320GB                       | 1         | 1.37%   |
| Unknown SH64G  64GB                               | 1         | 1.37%   |
| Unknown MMC Card  16GB                            | 1         | 1.37%   |
| Unknown DA4128  128GB                             | 1         | 1.37%   |
| Unknown AFGCF  128GB                              | 1         | 1.37%   |
| Unknown 8GTF4R  8GB                               | 1         | 1.37%   |
| Unknown 032G32  32GB                              | 1         | 1.37%   |
| Transcend TS240GMTS420S 240GB SSD                 | 1         | 1.37%   |
| Toshiba NVMe SSD Drive 512GB                      | 1         | 1.37%   |
| Seagate ST480HM000-1G5162 480GB                   | 1         | 1.37%   |
| Seagate ST3320418AS 320GB                         | 1         | 1.37%   |
| Seagate ST31000524AS 1TB                          | 1         | 1.37%   |
| Seagate ST1000DM003-1ER162 1TB                    | 1         | 1.37%   |
| Seagate NVMe SSD Drive 2TB                        | 1         | 1.37%   |
| SanDisk SSD i100 24GB                             | 1         | 1.37%   |
| SanDisk SDSSDH3500G 500GB                         | 1         | 1.37%   |
| SanDisk NVMe SSD Drive 500GB                      | 1         | 1.37%   |
| Samsung SSD 970 EVO Plus 500GB                    | 1         | 1.37%   |
| Samsung SSD 970 EVO Plus 2TB                      | 1         | 1.37%   |
| Samsung SSD 970 EVO 250GB                         | 1         | 1.37%   |
| Samsung SSD 960 EVO 500GB                         | 1         | 1.37%   |
| Samsung SSD 960 EVO 250GB                         | 1         | 1.37%   |
| Samsung SSD 860 EVO M.2 250GB                     | 1         | 1.37%   |
| Samsung SSD 860 EVO 500GB                         | 1         | 1.37%   |
| Samsung SSD 860 EVO 1TB                           | 1         | 1.37%   |
| Samsung SSD 850 EVO 500GB                         | 1         | 1.37%   |
| Samsung SSD 850 EVO 250GB                         | 1         | 1.37%   |
| Samsung SSD 830 Series 128GB                      | 1         | 1.37%   |
| Samsung NVMe SSD Drive 1TB                        | 1         | 1.37%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 1         | 1.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 9      | 31.25%  |
| HGST                | 3         | 3      | 18.75%  |
| WDC                 | 2         | 2      | 12.5%   |
| Apple               | 2         | 2      | 12.5%   |
| Samsung Electronics | 1         | 1      | 6.25%   |
| JMicron Technology  | 1         | 1      | 6.25%   |
| Hitachi             | 1         | 1      | 6.25%   |
| ASMT                | 1         | 2      | 6.25%   |

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
| PNY                 | 1         | 1      | 3.7%    |
| Plextor             | 1         | 1      | 3.7%    |
| Patriot             | 1         | 1      | 3.7%    |
| Mushkin             | 1         | 1      | 3.7%    |
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
| SSD  | 24        | 35     | 38.1%   |
| NVMe | 16        | 19     | 25.4%   |
| HDD  | 15        | 21     | 23.81%  |
| MMC  | 8         | 12     | 12.7%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 34        | 52     | 55.74%  |
| NVMe | 16        | 19     | 26.23%  |
| MMC  | 8         | 12     | 13.11%  |
| SAS  | 3         | 4      | 4.92%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 26        | 39     | 68.42%  |
| 0.51-1.0   | 10        | 14     | 26.32%  |
| 1.01-2.0   | 2         | 3      | 5.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 26        | 44.07%  |
| 101-250    | 7         | 11.86%  |
| 251-500    | 6         | 10.17%  |
| 21-50      | 5         | 8.47%   |
| 501-1000   | 4         | 6.78%   |
| 51-100     | 4         | 6.78%   |
| 1001-2000  | 3         | 5.08%   |
| Unknown    | 3         | 5.08%   |
| 2001-3000  | 1         | 1.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 37        | 62.71%  |
| 21-50    | 11        | 18.64%  |
| 101-250  | 3         | 5.08%   |
| 501-1000 | 3         | 5.08%   |
| Unknown  | 3         | 5.08%   |
| 251-500  | 1         | 1.69%   |
| 51-100   | 1         | 1.69%   |

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
| Detected | 39        | 62     | 67.24%  |
| Works    | 16        | 22     | 27.59%  |
| Malfunc  | 3         | 3      | 5.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 32        | 59.26%  |
| Samsung Electronics          | 9         | 16.67%  |
| AMD                          | 5         | 9.26%   |
| SanDisk                      | 2         | 3.7%    |
| Apple                        | 2         | 3.7%    |
| Toshiba America Info Systems | 1         | 1.85%   |
| Seagate Technology           | 1         | 1.85%   |
| Phison Electronics           | 1         | 1.85%   |
| ADATA Technology             | 1         | 1.85%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 12.28%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 6         | 10.53%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 8.77%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 3         | 5.26%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 3.51%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 3.51%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 3.51%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 3.51%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 3.51%   |
| Apple S3X NVMe Controller                                                      | 2         | 3.51%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 1.75%   |
| Seagate FireCuda 510 SSD                                                       | 1         | 1.75%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 1         | 1.75%   |
| SanDisk Non-Volatile memory controller                                         | 1         | 1.75%   |
| Samsung Electronics SATA controller                                            | 1         | 1.75%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 1.75%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.75%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.75%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 1.75%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.75%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 1         | 1.75%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 1         | 1.75%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 1         | 1.75%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 1.75%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1         | 1.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 1.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1         | 1.75%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 1.75%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 1         | 1.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 1.75%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 1         | 1.75%   |
| AMD FCH SATA Controller D                                                      | 1         | 1.75%   |
| ADATA Non-Volatile memory controller                                           | 1         | 1.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 36        | 65.45%  |
| NVMe | 16        | 29.09%  |
| IDE  | 3         | 5.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 45        | 77.59%  |
| ARM     | 6         | 10.34%  |
| AMD     | 5         | 8.62%   |
| Unknown | 2         | 3.45%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10710U CPU @ 1.10GHz            | 6         | 10.34%  |
| ARM Processor                                 | 6         | 10.34%  |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 6.9%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 3.45%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 3.45%   |
|                                               | 2         | 3.45%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 1.72%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 1.72%   |
| Intel Core m5-6Y54 CPU @ 1.10GHz              | 1         | 1.72%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 1.72%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 1.72%   |
| Intel Core i7-7567U CPU @ 3.50GHz             | 1         | 1.72%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz            | 1         | 1.72%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 1         | 1.72%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 1.72%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 1.72%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 1.72%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 1         | 1.72%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.72%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 1         | 1.72%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 1.72%   |
| Intel Core i5-3330S CPU @ 2.70GHz             | 1         | 1.72%   |
| Intel Core i5-2320 CPU @ 3.00GHz              | 1         | 1.72%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 1.72%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 1         | 1.72%   |
| Intel Core i5 CPU 750 @ 2.67GHz               | 1         | 1.72%   |
| Intel Core i3-4130T CPU @ 2.90GHz             | 1         | 1.72%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 1         | 1.72%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 1.72%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 1         | 1.72%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 1         | 1.72%   |
| Intel Core 2 Duo CPU U7700 @ 1.33GHz          | 1         | 1.72%   |
| Intel Core 2 Duo CPU T7700 @ 2.40GHz          | 1         | 1.72%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 1         | 1.72%   |
| Intel Celeron N4100 CPU @ 1.10GHz             | 1         | 1.72%   |
| Intel Celeron J4005 CPU @ 2.00GHz             | 1         | 1.72%   |
| Intel Celeron CPU 4205U @ 1.80GHz             | 1         | 1.72%   |
| AMD Turion II Dual-Core Mobile M520           | 1         | 1.72%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 1         | 1.72%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 1         | 1.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 20        | 35.09%  |
| Intel Core i5           | 11        | 19.3%   |
| Other                   | 7         | 12.28%  |
| Intel Core i3           | 5         | 8.77%   |
| Intel Core 2 Duo        | 3         | 5.26%   |
| Intel Celeron           | 3         | 5.26%   |
| Intel Pentium Silver    | 1         | 1.75%   |
| Intel Pentium           | 1         | 1.75%   |
| Intel Core m5           | 1         | 1.75%   |
| AMD Turion II Dual-Core | 1         | 1.75%   |
| AMD Ryzen 5             | 1         | 1.75%   |
| AMD Ryzen 3             | 1         | 1.75%   |
| AMD Athlon II X4        | 1         | 1.75%   |
| AMD A10                 | 1         | 1.75%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 27        | 47.37%  |
| 4       | 23        | 40.35%  |
| 6       | 6         | 10.53%  |
| Unknown | 1         | 1.75%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 56        | 98.25%  |
| Unknown | 1         | 1.75%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 35        | 61.4%   |
| 1       | 21        | 36.84%  |
| Unknown | 1         | 1.75%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 53        | 91.38%  |
| Unknown        | 4         | 6.9%    |
| 64-bit         | 1         | 1.72%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 42        | 71.19%  |
| 0xa0660    | 3         | 5.08%   |
| 0x406e3    | 3         | 5.08%   |
| 0x706a1    | 2         | 3.39%   |
| 0x40651    | 2         | 3.39%   |
| 0x806ec    | 1         | 1.69%   |
| 0x806e9    | 1         | 1.69%   |
| 0x306d4    | 1         | 1.69%   |
| 0x206a7    | 1         | 1.69%   |
| 0x1067a    | 1         | 1.69%   |
| 0x08108109 | 1         | 1.69%   |
| 0x06003106 | 1         | 1.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 12        | 21.05%  |
| Haswell       | 8         | 14.04%  |
| Unknown       | 7         | 12.28%  |
| CometLake     | 6         | 10.53%  |
| Skylake       | 3         | 5.26%   |
| IvyBridge     | 3         | 5.26%   |
| Goldmont plus | 3         | 5.26%   |
| Zen+          | 2         | 3.51%   |
| SandyBridge   | 2         | 3.51%   |
| K10           | 2         | 3.51%   |
| Core          | 2         | 3.51%   |
| Broadwell     | 2         | 3.51%   |
| Westmere      | 1         | 1.75%   |
| Steamroller   | 1         | 1.75%   |
| Penryn        | 1         | 1.75%   |
| Nehalem       | 1         | 1.75%   |
| Goldmont      | 1         | 1.75%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 41        | 71.93%  |
| Nvidia | 8         | 14.04%  |
| AMD    | 8         | 14.04%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                 | 6         | 10%     |
| Intel Comet Lake UHD Graphics                                                         | 6         | 10%     |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 3         | 5%      |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 3         | 5%      |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 2         | 3.33%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 2         | 3.33%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 2         | 3.33%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 2         | 3.33%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 2         | 3.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 2         | 3.33%   |
| Nvidia TU116 [GeForce GTX 1660]                                                       | 1         | 1.67%   |
| Nvidia GT216M [GeForce GT 330M]                                                       | 1         | 1.67%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 1         | 1.67%   |
| Nvidia GK208M [GeForce GT 730M]                                                       | 1         | 1.67%   |
| Nvidia GK208B [GeForce GT 710]                                                        | 1         | 1.67%   |
| Nvidia GK107M [GeForce GT 640M Mac Edition]                                           | 1         | 1.67%   |
| Nvidia GK104M [GeForce GTX 870M]                                                      | 1         | 1.67%   |
| Nvidia GF116 [GeForce GTS 450 Rev. 2]                                                 | 1         | 1.67%   |
| Nvidia GF108 [GeForce GT 630]                                                         | 1         | 1.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 1         | 1.67%   |
| Intel Whiskey Lake-U GT1 [UHD Graphics 610]                                           | 1         | 1.67%   |
| Intel UHD Graphics 620                                                                | 1         | 1.67%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller         | 1         | 1.67%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller             | 1         | 1.67%   |
| Intel Iris Plus Graphics 650                                                          | 1         | 1.67%   |
| Intel HD Graphics 630                                                                 | 1         | 1.67%   |
| Intel HD Graphics 6000                                                                | 1         | 1.67%   |
| Intel HD Graphics 5500                                                                | 1         | 1.67%   |
| Intel HD Graphics 515                                                                 | 1         | 1.67%   |
| Intel GeminiLake [UHD Graphics 605]                                                   | 1         | 1.67%   |
| Intel Core Processor Integrated Graphics Controller                                   | 1         | 1.67%   |
| Intel Apollo Lake [HD Graphics 505]                                                   | 1         | 1.67%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                 | 1         | 1.67%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 1.67%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                             | 1         | 1.67%   |
| AMD RV770/M98L [Mobility Radeon HD 4850]                                              | 1         | 1.67%   |
| AMD RV630/M76 [Mobility Radeon HD 2600 XT/2700]                                       | 1         | 1.67%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                             | 1         | 1.67%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                                    | 1         | 1.67%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                   | 1         | 1.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 33        | 57.89%  |
| Other          | 8         | 14.04%  |
| 1 x AMD        | 5         | 8.77%   |
| 1 x Nvidia     | 4         | 7.02%   |
| Intel + Nvidia | 4         | 7.02%   |
| Intel + AMD    | 2         | 3.51%   |
| 2 x AMD        | 1         | 1.75%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 48        | 84.21%  |
| Unknown | 9         | 15.79%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 56        | 96.55%  |
| 3.01-4.0   | 1         | 1.72%   |
| 0.51-1.0   | 1         | 1.72%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 8         | 14.04%  |
| Chimei Innolux          | 8         | 14.04%  |
| BOE                     | 7         | 12.28%  |
| LG Display              | 6         | 10.53%  |
| Apple                   | 6         | 10.53%  |
| Philips                 | 2         | 3.51%   |
| Goldstar                | 2         | 3.51%   |
| AU Optronics            | 2         | 3.51%   |
| Unknown                 | 1         | 1.75%   |
| Toshiba                 | 1         | 1.75%   |
| Sony                    | 1         | 1.75%   |
| Sharp                   | 1         | 1.75%   |
| RTK                     | 1         | 1.75%   |
| PRI                     | 1         | 1.75%   |
| PANDA                   | 1         | 1.75%   |
| Lenovo                  | 1         | 1.75%   |
| Iiyama                  | 1         | 1.75%   |
| Grundig                 | 1         | 1.75%   |
| Dell                    | 1         | 1.75%   |
| Chi Mei Optoelectronics | 1         | 1.75%   |
| BenQ                    | 1         | 1.75%   |
| ASUSTek Computer        | 1         | 1.75%   |
| AOC                     | 1         | 1.75%   |
| Acer                    | 1         | 1.75%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC434B 3840x2160 344x194mm 15.5-inch     | 3         | 5.26%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 3         | 5.26%   |
| Philips TV PHL5035 1920x1080 640x360mm 28.9-inch                          | 2         | 3.51%   |
| Chimei Innolux LCD Monitor CMN1415 1920x1080 309x173mm 13.9-inch          | 2         | 3.51%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 1         | 1.75%   |
| Toshiba LCD Monitor LCD3706 1280x800 261x163mm 12.1-inch                  | 1         | 1.75%   |
| Sony TV SNYAB03 1920x1080                                                 | 1         | 1.75%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                   | 1         | 1.75%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 474x296mm 22.0-inch      | 1         | 1.75%   |
| Samsung Electronics SyncMaster SAM01D3 1440x900 408x225mm 18.3-inch       | 1         | 1.75%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch      | 1         | 1.75%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 410x230mm 18.5-inch      | 1         | 1.75%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 1         | 1.75%   |
| RTK AIO PC RTK2136 1600x900 432x239mm 19.4-inch                           | 1         | 1.75%   |
| PRI Prima TV PRI1600 1920x1080                                            | 1         | 1.75%   |
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch                   | 1         | 1.75%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch              | 1         | 1.75%   |
| LG Display LCD Monitor LGD053B 1920x1080 294x165mm 13.3-inch              | 1         | 1.75%   |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch              | 1         | 1.75%   |
| LG Display LCD Monitor LGD03F0 1366x768 310x174mm 14.0-inch               | 1         | 1.75%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch               | 1         | 1.75%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch               | 1         | 1.75%   |
| Lenovo LEN Y44w-10 LEN65EA 3840x1200 1052x329mm 43.4-inch                 | 1         | 1.75%   |
| Iiyama PL2792H IVM664F 1920x1080 598x336mm 27.0-inch                      | 1         | 1.75%   |
| Grundig WUXGA GRU4448 1920x540                                            | 1         | 1.75%   |
| Goldstar IPS231 GSM5817 1920x1080 510x290mm 23.1-inch                     | 1         | 1.75%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                    | 1         | 1.75%   |
| Dell P2213 DELF042 1680x1050 473x296mm 22.0-inch                          | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch          | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch           | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN1365 1920x1080 293x165mm 13.2-inch          | 1         | 1.75%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 1.75%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                     | 1         | 1.75%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                     | 1         | 1.75%   |
| BOE LCD Monitor BOE079A 1920x1080 309x173mm 13.9-inch                     | 1         | 1.75%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                      | 1         | 1.75%   |
| BOE LCD Monitor BOE06C2 1366x768 344x194mm 15.5-inch                      | 1         | 1.75%   |
| BOE LCD Monitor BOE06BE 1920x1080 294x165mm 13.3-inch                     | 1         | 1.75%   |
| BOE LCD Monitor BOE0641 1920x1080 344x193mm 15.5-inch                     | 1         | 1.75%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                         | 1         | 1.75%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 26        | 49.06%  |
| 1366x768 (WXGA)    | 8         | 15.09%  |
| 3840x2160 (4K)     | 6         | 11.32%  |
| 1680x1050 (WSXGA+) | 3         | 5.66%   |
| 1600x900 (HD+)     | 2         | 3.77%   |
| 1440x900 (WXGA+)   | 2         | 3.77%   |
| 3840x1200          | 1         | 1.89%   |
| 2880x1800          | 1         | 1.89%   |
| 2304x1440          | 1         | 1.89%   |
| 2288x1287          | 1         | 1.89%   |
| 1920x1200 (WUXGA)  | 1         | 1.89%   |
| 1280x800 (WXGA)    | 1         | 1.89%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 16        | 28.07%  |
| 15      | 12        | 21.05%  |
| 23      | 3         | 5.26%   |
| 14      | 3         | 5.26%   |
| 28      | 2         | 3.51%   |
| 24      | 2         | 3.51%   |
| 22      | 2         | 3.51%   |
| 21      | 2         | 3.51%   |
| 20      | 2         | 3.51%   |
| 17      | 2         | 3.51%   |
| 12      | 2         | 3.51%   |
| 142     | 1         | 1.75%   |
| 72      | 1         | 1.75%   |
| 54      | 1         | 1.75%   |
| 43      | 1         | 1.75%   |
| 40      | 1         | 1.75%   |
| 31      | 1         | 1.75%   |
| 27      | 1         | 1.75%   |
| 19      | 1         | 1.75%   |
| Unknown | 1         | 1.75%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 22        | 39.29%  |
| 201-300        | 9         | 16.07%  |
| 401-500        | 7         | 12.5%   |
| 501-600        | 6         | 10.71%  |
| 601-700        | 3         | 5.36%   |
| 351-400        | 3         | 5.36%   |
| 1001-1500      | 2         | 3.57%   |
| More than 2000 | 1         | 1.79%   |
| 801-900        | 1         | 1.79%   |
| 1501-2000      | 1         | 1.79%   |
| Unknown        | 1         | 1.79%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 38        | 77.55%  |
| 16/10 | 9         | 18.37%  |
| 3.20  | 1         | 2.04%   |
| 1.00  | 1         | 2.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 12        | 21.05%  |
| 101-110        | 12        | 21.05%  |
| 201-250        | 9         | 15.79%  |
| 71-80          | 7         | 12.28%  |
| More than 1000 | 3         | 5.26%   |
| 351-500        | 3         | 5.26%   |
| 151-200        | 3         | 5.26%   |
| 61-70          | 2         | 3.51%   |
| 501-1000       | 2         | 3.51%   |
| 301-350        | 1         | 1.75%   |
| 131-140        | 1         | 1.75%   |
| 121-130        | 1         | 1.75%   |
| Unknown        | 1         | 1.75%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 17        | 29.82%  |
| 51-100        | 17        | 29.82%  |
| 101-120       | 8         | 14.04%  |
| More than 240 | 6         | 10.53%  |
| 161-240       | 5         | 8.77%   |
| 1-50          | 3         | 5.26%   |
| Unknown       | 1         | 1.75%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 40        | 70.18%  |
| 2     | 8         | 14.04%  |
| 0     | 8         | 14.04%  |
| 3     | 1         | 1.75%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 32        | 36.78%  |
| Qualcomm Atheros                | 17        | 19.54%  |
| Intel                           | 15        | 17.24%  |
| Broadcom                        | 8         | 9.2%    |
| Broadcom Limited                | 4         | 4.6%    |
| Qualcomm Atheros Communications | 2         | 2.3%    |
| ASIX Electronics                | 2         | 2.3%    |
| Samsung Electronics             | 1         | 1.15%   |
| Ralink                          | 1         | 1.15%   |
| OPPO Electronics                | 1         | 1.15%   |
| MediaTek                        | 1         | 1.15%   |
| Marvell Technology Group        | 1         | 1.15%   |
| Edimax Technology               | 1         | 1.15%   |
| ASUSTek Computer                | 1         | 1.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 21        | 22.11%  |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 12        | 12.63%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 5         | 5.26%   |
| Intel Wireless 7265                                                           | 4         | 4.21%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 3         | 3.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 3         | 3.16%   |
| Intel Wireless 7260                                                           | 3         | 3.16%   |
| Qualcomm Atheros AR9271 802.11n                                               | 2         | 2.11%   |
| Intel Ethernet Connection I217-LM                                             | 2         | 2.11%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2         | 2.11%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                    | 2         | 2.11%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 2         | 2.11%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1         | 1.05%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1         | 1.05%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 1.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.05%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 1         | 1.05%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 1.05%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1         | 1.05%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                        | 1         | 1.05%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 1.05%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.05%   |
| OPPO KALAMA-MTP_CID:0437_SN:AEEEF597                                          | 1         | 1.05%   |
| MediaTek WiFi                                                                 | 1         | 1.05%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                       | 1         | 1.05%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 1.05%   |
| Intel I211 Gigabit Network Connection                                         | 1         | 1.05%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1         | 1.05%   |
| Intel Ethernet Connection I218-V                                              | 1         | 1.05%   |
| Intel Ethernet Connection (6) I219-LM                                         | 1         | 1.05%   |
| Intel Ethernet Connection (4) I219-V                                          | 1         | 1.05%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 1.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 1         | 1.05%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 1.05%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1         | 1.05%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                                   | 1         | 1.05%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 1         | 1.05%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                       | 1         | 1.05%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                                        | 1         | 1.05%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                        | 1         | 1.05%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 17        | 34%     |
| Intel                           | 12        | 24%     |
| Realtek Semiconductor           | 6         | 12%     |
| Broadcom                        | 5         | 10%     |
| Broadcom Limited                | 4         | 8%      |
| Qualcomm Atheros Communications | 2         | 4%      |
| Ralink                          | 1         | 2%      |
| MediaTek                        | 1         | 2%      |
| Edimax Technology               | 1         | 2%      |
| ASUSTek Computer                | 1         | 2%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 12        | 24%     |
| Intel Wireless 7265                                                           | 4         | 8%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 3         | 6%      |
| Intel Wireless 7260                                                           | 3         | 6%      |
| Qualcomm Atheros AR9271 802.11n                                               | 2         | 4%      |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                    | 2         | 4%      |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1         | 2%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 2%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 2%      |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 1         | 2%      |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 2%      |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1         | 2%      |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                        | 1         | 2%      |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 2%      |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 2%      |
| MediaTek WiFi                                                                 | 1         | 2%      |
| Intel Wireless 8265 / 8275                                                    | 1         | 2%      |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1         | 2%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 2%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 1         | 2%      |
| Intel Centrino Advanced-N 6235                                                | 1         | 2%      |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                                   | 1         | 2%      |
| Broadcom Limited BCM4331 802.11a/b/g/n                                        | 1         | 2%      |
| Broadcom Limited BCM4321 802.11a/b/g/n                                        | 1         | 2%      |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 1         | 2%      |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                            | 1         | 2%      |
| Broadcom BCM43224 802.11a/b/g/n                                               | 1         | 2%      |
| Broadcom BCM4321 802.11a/b/g/n                                                | 1         | 2%      |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 1         | 2%      |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                     | 1         | 2%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 28        | 65.12%  |
| Intel                    | 6         | 13.95%  |
| Broadcom                 | 4         | 9.3%    |
| ASIX Electronics         | 2         | 4.65%   |
| Samsung Electronics      | 1         | 2.33%   |
| OPPO Electronics         | 1         | 2.33%   |
| Marvell Technology Group | 1         | 2.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21        | 46.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 11.11%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 6.67%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 4.44%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 4.44%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 4.44%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 2.22%   |
| OPPO KALAMA-MTP_CID:0437_SN:AEEEF597                              | 1         | 2.22%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 2.22%   |
| Intel I211 Gigabit Network Connection                             | 1         | 2.22%   |
| Intel Ethernet Connection I218-V                                  | 1         | 2.22%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 2.22%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 2.22%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 2.22%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 2.22%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 2.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 43        | 51.19%  |
| Ethernet | 41        | 48.81%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 31        | 62%     |
| WiFi     | 19        | 38%     |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 27        | 47.37%  |
| 1     | 20        | 35.09%  |
| 0     | 8         | 14.04%  |
| 3     | 2         | 3.51%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 44        | 77.19%  |
| Yes  | 13        | 22.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 11        | 29.73%  |
| Qualcomm Atheros Communications | 6         | 16.22%  |
| Apple                           | 6         | 16.22%  |
| Foxconn / Hon Hai               | 5         | 13.51%  |
| Lite-On Technology              | 4         | 10.81%  |
| Realtek Semiconductor           | 1         | 2.7%    |
| IMC Networks                    | 1         | 2.7%    |
| Cambridge Silicon Radio         | 1         | 2.7%    |
| Broadcom                        | 1         | 2.7%    |
| ASUSTek Computer                | 1         | 2.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                   | 7         | 18.92%  |
| Foxconn / Hon Hai Bluetooth Device                   | 5         | 13.51%  |
| Lite-On Atheros AR3012 Bluetooth                     | 4         | 10.81%  |
| Qualcomm Atheros  Bluetooth Device                   | 2         | 5.41%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                | 2         | 5.41%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)       | 2         | 5.41%   |
| Apple Bluetooth USB Host Controller                  | 2         | 5.41%   |
| Apple Bluetooth Host Controller                      | 2         | 5.41%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter              | 1         | 2.7%    |
| Qualcomm Atheros Dell Wireless 1802 Bluetooth 4.0 LE | 1         | 2.7%    |
| Qualcomm Atheros AR9462 Bluetooth                    | 1         | 2.7%    |
| Intel Wireless-AC 3168 Bluetooth                     | 1         | 2.7%    |
| Intel Centrino Bluetooth Wireless Transceiver        | 1         | 2.7%    |
| IMC Networks Bluetooth Radio                         | 1         | 2.7%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)  | 1         | 2.7%    |
| Broadcom HP Portable Valentine                       | 1         | 2.7%    |
| ASUS Broadcom BCM20702A0 Bluetooth                   | 1         | 2.7%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                 | 1         | 2.7%    |
| Apple Bluetooth HCI                                  | 1         | 2.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 44        | 70.97%  |
| AMD      | 7         | 11.29%  |
| Nvidia   | 6         | 9.68%   |
| XMOS     | 1         | 1.61%   |
| Shure    | 1         | 1.61%   |
| Micronas | 1         | 1.61%   |
| M-Audio  | 1         | 1.61%   |
| Logitech | 1         | 1.61%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 11        | 14.86%  |
| Intel Comet Lake PCH-LP cAVS                                               | 8         | 10.81%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 5.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 5.41%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 4.05%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 4.05%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 4.05%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 4.05%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 2.7%    |
| Intel Broadwell-U Audio Controller                                         | 2         | 2.7%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 2.7%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 2.7%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 2.7%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.7%    |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 2.7%    |
| XMOS xCORE USB Audio 2.0                                                   | 1         | 1.35%   |
| Shure MV5                                                                  | 1         | 1.35%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 1.35%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 1.35%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.35%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.35%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 1.35%   |
| Nvidia GF116 High Definition Audio Controller                              | 1         | 1.35%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.35%   |
| Micronas QSB                                                               | 1         | 1.35%   |
| M-Audio M-Audio Fast Track MKII                                            | 1         | 1.35%   |
| Logitech Headset H340                                                      | 1         | 1.35%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 1.35%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.35%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1.35%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.35%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1         | 1.35%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 1.35%   |
| AMD RV770 HDMI Audio [Radeon HD 4850/4870]                                 | 1         | 1.35%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 1.35%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.35%   |

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
| Toshiba RAM 8HTF12864HDY-800G1 4GB SODIMM 1066MT/s               | 1         | 4%      |
| Toshiba RAM 64T128020EDL2.5C2 1GB SODIMM 1066MT/s                | 1         | 4%      |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s            | 1         | 4%      |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 4%      |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 4%      |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1600MT/s          | 1         | 4%      |
| SK hynix RAM HMP125U6EFR8C-S6 2GB DIMM DDR2 800MT/s              | 1         | 4%      |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 4%      |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 4%      |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 4%      |
| SK hynix RAM H9CCNNNBLTALAR-NTD 4GB Row Of Chips LPDDR3 1600MT/s | 1         | 4%      |
| Samsung RAM Module 4GB SODIMM LPDDR3 1867MT/s                    | 1         | 4%      |
| Samsung RAM K4A8G165WC-BCTD 4GB SODIMM DDR4 2667MT/s             | 1         | 4%      |
| Micron RAM 16HTF25664AZ-800H1 2GB DIMM DDR2 800MT/s              | 1         | 4%      |
| Kingston RAM 9905471-011.A00LF 4096MB DIMM DDR3 1600MT/s         | 1         | 4%      |
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
| Apple                                  | 6         | 17.14%  |
| Realtek Semiconductor                  | 5         | 14.29%  |
| Chicony Electronics                    | 4         | 11.43%  |
| Alcor Micro                            | 4         | 11.43%  |
| Sunplus Innovation Technology          | 3         | 8.57%   |
| Acer                                   | 3         | 8.57%   |
| Suyin                                  | 1         | 2.86%   |
| Silicon Motion                         | 1         | 2.86%   |
| Quanta                                 | 1         | 2.86%   |
| Microdia                               | 1         | 2.86%   |
| Lite-On Technology                     | 1         | 2.86%   |
| IMC Networks                           | 1         | 2.86%   |
| Google                                 | 1         | 2.86%   |
| Genesys Logic                          | 1         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.86%   |
| Bison Electronics                      | 1         | 2.86%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Apple Built-in iSight                                                      | 3         | 8.33%   |
| Alcor Micro HD WebCam                                                      | 3         | 8.33%   |
| Realtek USB2.0 camera                                                      | 2         | 5.56%   |
| Chicony HD User Facing                                                     | 2         | 5.56%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 2         | 5.56%   |
| Acer SunplusIT INC. Integrated Camera                                      | 2         | 5.56%   |
| Suyin HP Wide Vision FHD Camera                                            | 1         | 2.78%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 2.78%   |
| Sunplus Integrated Camera                                                  | 1         | 2.78%   |
| Sunplus HD WebCam                                                          | 1         | 2.78%   |
| Silicon Motion WebCam SC-13HDL12131N                                       | 1         | 2.78%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 2.78%   |
| Realtek Integrated Webcam                                                  | 1         | 2.78%   |
| Realtek HP Truevision HD                                                   | 1         | 2.78%   |
| Quanta HD Camera                                                           | 1         | 2.78%   |
| Microdia HP Integrated Webcam                                              | 1         | 2.78%   |
| Lite-On Integrated Camera                                                  | 1         | 2.78%   |
| IMC Networks Lenovo EasyCamera                                             | 1         | 2.78%   |
| Genesys Logic Camera                                                       | 1         | 2.78%   |
| Chicony USB2.0 UVC WebCam                                                  | 1         | 2.78%   |
| Chicony LG HD WebCam                                                       | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 1         | 2.78%   |
| Bison SunplusIT Integrated Camera                                          | 1         | 2.78%   |
| Apple iBridge                                                              | 1         | 2.78%   |
| Apple FaceTime HD Camera (Built-in)                                        | 1         | 2.78%   |
| Alcor Micro HP Webcam-101                                                  | 1         | 2.78%   |
| Acer BisonCam, NB Pro                                                      | 1         | 2.78%   |
| Unknown                                                                    | 1         | 2.78%   |

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
| 0     | 32        | 55.17%  |
| 1     | 19        | 32.76%  |
| 2     | 4         | 6.9%    |
| 3     | 2         | 3.45%   |
| 4     | 1         | 1.72%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 11        | 30.56%  |
| Fingerprint reader    | 7         | 19.44%  |
| Bluetooth             | 7         | 19.44%  |
| Graphics card         | 5         | 13.89%  |
| Multimedia controller | 3         | 8.33%   |
| Chipcard              | 2         | 5.56%   |
| Camera                | 1         | 2.78%   |

