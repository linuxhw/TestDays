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

Total: 84

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | B50-70 20384                | Notebook    | [5e3a2796a9](https://linux-hardware.org/?probe=5e3a2796a9) | Jun 01, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [21c01053ec](https://linux-hardware.org/?probe=21c01053ec) | May 19, 2023 |
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
| PureOS 10.0 | 22        | 36.67%  |
| PureOS 10   | 20        | 33.33%  |
| PureOS 9.0  | 13        | 21.67%  |
| PureOS 9    | 3         | 5%      |
| PureOS 8    | 2         | 3.33%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| PureOS | 59        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                          | Computers | Percent |
|----------------------------------|-----------|---------|
| 4.19.0-5-amd64                   | 10        | 15.63%  |
| 5.10.0-14-amd64                  | 7         | 10.94%  |
| 5.10.0-13-amd64                  | 5         | 7.81%   |
| 5.10.0-8-amd64                   | 4         | 6.25%   |
| 5.10.0-21-amd64                  | 4         | 6.25%   |
| 4.19.0-14-amd64                  | 4         | 6.25%   |
| 5.10.0-11-amd64                  | 3         | 4.69%   |
| 6.1.0-1-librem5                  | 2         | 3.13%   |
| 5.7.0-1-librem5                  | 2         | 3.13%   |
| 5.10.0-9-amd64                   | 2         | 3.13%   |
| 5.10.0-7-amd64                   | 2         | 3.13%   |
| 5.10.0-23-amd64                  | 2         | 3.13%   |
| 5.10.0-19-amd64                  | 2         | 3.13%   |
| 5.10.0-16-amd64                  | 2         | 3.13%   |
| 6.0.0-1-librem5                  | 1         | 1.56%   |
| 5.9-sunxi64                      | 1         | 1.56%   |
| 5.8-sunxi64                      | 1         | 1.56%   |
| 5.7.0-0.38-1-pinebookpro-hwaccel | 1         | 1.56%   |
| 5.15.0-2-amd64                   | 1         | 1.56%   |
| 5.10.0-6-amd64                   | 1         | 1.56%   |
| 5.10.0-20-amd64                  | 1         | 1.56%   |
| 5.10.0-18-amd64                  | 1         | 1.56%   |
| 5.10.0-17-amd64                  | 1         | 1.56%   |
| 5.10.0-15-amd64                  | 1         | 1.56%   |
| 5.10.0-12-amd64                  | 1         | 1.56%   |
| 4.19.72-imx8-sr                  | 1         | 1.56%   |
| 4.16.0-1-amd64                   | 1         | 1.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 37        | 59.68%  |
| 4.19.0  | 14        | 22.58%  |
| 5.7.0   | 3         | 4.84%   |
| 6.1.0   | 2         | 3.23%   |
| 6.0.0   | 1         | 1.61%   |
| 5.9     | 1         | 1.61%   |
| 5.8     | 1         | 1.61%   |
| 5.15.0  | 1         | 1.61%   |
| 4.19.72 | 1         | 1.61%   |
| 4.16.0  | 1         | 1.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 37        | 60.66%  |
| 4.19    | 15        | 24.59%  |
| 5.7     | 3         | 4.92%   |
| 6.1     | 2         | 3.28%   |
| 6.0     | 1         | 1.64%   |
| 5.15    | 1         | 1.64%   |
| 5       | 1         | 1.64%   |
| 4.16    | 1         | 1.64%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 52        | 88.14%  |
| aarch64 | 7         | 11.86%  |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 50        | 80.65%  |
| Unknown         | 6         | 9.68%   |
| KDE5            | 3         | 4.84%   |
| Phosh:GNOME     | 1         | 1.61%   |
| MATE            | 1         | 1.61%   |
| GNOME Flashback | 1         | 1.61%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 43        | 67.19%  |
| X11     | 10        | 15.63%  |
| Unknown | 6         | 9.38%   |
| Tty     | 5         | 7.81%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 36        | 61.02%  |
| GDM     | 15        | 25.42%  |
| GDM3    | 7         | 11.86%  |
| SDDM    | 1         | 1.69%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 25        | 40.32%  |
| de_DE   | 6         | 9.68%   |
| en_GB   | 5         | 8.06%   |
| Unknown | 4         | 6.45%   |
| pl_PL   | 3         | 4.84%   |
| C       | 3         | 4.84%   |
| ru_RU   | 2         | 3.23%   |
| pt_BR   | 2         | 3.23%   |
| it_IT   | 2         | 3.23%   |
| fr_FR   | 2         | 3.23%   |
| en_AU   | 2         | 3.23%   |
| zh_CN   | 1         | 1.61%   |
| pt_PT   | 1         | 1.61%   |
| hu_HU   | 1         | 1.61%   |
| es_CR   | 1         | 1.61%   |
| en_IL   | 1         | 1.61%   |
| bg_BG   | 1         | 1.61%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 51        | 85%     |
| EFI  | 9         | 15%     |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 53        | 89.83%  |
| Overlay | 2         | 3.39%   |
| Unknown | 2         | 3.39%   |
| Ext2    | 1         | 1.69%   |
| Btrfs   | 1         | 1.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 35        | 57.38%  |
| MBR     | 14        | 22.95%  |
| GPT     | 12        | 19.67%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 51        | 86.44%  |
| Yes       | 8         | 13.56%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 55        | 93.22%  |
| Yes       | 4         | 6.78%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Purism              | 14        | 23.73%  |
| Apple               | 8         | 13.56%  |
| Lenovo              | 7         | 11.86%  |
| Dell                | 6         | 10.17%  |
| Hewlett-Packard     | 4         | 6.78%   |
| Unknown             | 3         | 5.08%   |
| Pine Microsystems   | 2         | 3.39%   |
| Gigabyte Technology | 2         | 3.39%   |
| ASUSTek Computer    | 2         | 3.39%   |
| Acer                | 2         | 3.39%   |
| Toshiba             | 1         | 1.69%   |
| Shuttle             | 1         | 1.69%   |
| Samsung Electronics | 1         | 1.69%   |
| PCWare              | 1         | 1.69%   |
| Notebook            | 1         | 1.69%   |
| MSI                 | 1         | 1.69%   |
| LG Electronics      | 1         | 1.69%   |
| HUAWEI              | 1         | 1.69%   |
| Google              | 1         | 1.69%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Purism Librem 14                         | 6         | 10.17%  |
| Unknown                                  | 3         | 5.08%   |
| Purism Librem 15 v4                      | 2         | 3.39%   |
| HP Pavilion g6                           | 2         | 3.39%   |
| Toshiba Satellite L500D                  | 1         | 1.69%   |
| Shuttle DS10U                            | 1         | 1.69%   |
| Samsung 530U3C/530U4C/532U3C             | 1         | 1.69%   |
| Purism librem_mini_v2                    | 1         | 1.69%   |
| Purism Librem 5r4                        | 1         | 1.69%   |
| Purism Librem 5                          | 1         | 1.69%   |
| Purism Librem 15 v3                      | 1         | 1.69%   |
| Purism Librem 13 v4                      | 1         | 1.69%   |
| Purism Librem 13 v2                      | 1         | 1.69%   |
| Pine Microsystems Pine64 PinePhone (1.2) | 1         | 1.69%   |
| Pine Microsystems Pine64 Pinebook Pro    | 1         | 1.69%   |
| PCWare IPX4005G                          | 1         | 1.69%   |
| Notebook P17SM                           | 1         | 1.69%   |
| MSI MS-7788                              | 1         | 1.69%   |
| LG 22V280-L.BY31P1                       | 1         | 1.69%   |
| Lenovo ThinkPad T540p 20BFS23T00         | 1         | 1.69%   |
| Lenovo ThinkPad T440p                    | 1         | 1.69%   |
| Lenovo ThinkPad T440 20B60044RT          | 1         | 1.69%   |
| Lenovo ThinkPad E480 20KN003SUS          | 1         | 1.69%   |
| Lenovo ThinkPad 13 2nd Gen 20J2S00G00    | 1         | 1.69%   |
| Lenovo IdeaPad U430 Touch 20270          | 1         | 1.69%   |
| Lenovo B50-70 20384                      | 1         | 1.69%   |
| HUAWEI NBLB-WAX9N                        | 1         | 1.69%   |
| HP Spectre x360 Convertible              | 1         | 1.69%   |
| HP Pavilion Notebook                     | 1         | 1.69%   |
| Google Droid                             | 1         | 1.69%   |
| Gigabyte GA-MA78GM-UD2H                  | 1         | 1.69%   |
| Gigabyte B85M-DS3H                       | 1         | 1.69%   |
| Dell XPS 13 9370                         | 1         | 1.69%   |
| Dell OptiPlex 760                        | 1         | 1.69%   |
| Dell Latitude D430                       | 1         | 1.69%   |
| Dell Inspiron 5547                       | 1         | 1.69%   |
| Dell Inspiron 3847                       | 1         | 1.69%   |
| Dell Inspiron 15-3567                    | 1         | 1.69%   |
| ASUS EX-A320M-GAMING                     | 1         | 1.69%   |
| ASUS A88X-PLUS/USB                       | 1         | 1.69%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Purism Librem            | 14        | 23.73%  |
| Lenovo ThinkPad          | 5         | 8.47%   |
| HP Pavilion              | 3         | 5.08%   |
| Dell Inspiron            | 3         | 5.08%   |
| Unknown                  | 3         | 5.08%   |
| Pine Microsystems Pine64 | 2         | 3.39%   |
| Toshiba Satellite        | 1         | 1.69%   |
| Shuttle DS10U            | 1         | 1.69%   |
| Samsung 530U3C           | 1         | 1.69%   |
| PCWare IPX4005G          | 1         | 1.69%   |
| Notebook P17SM           | 1         | 1.69%   |
| MSI MS-7788              | 1         | 1.69%   |
| LG 22V280-L.BY31P1       | 1         | 1.69%   |
| Lenovo IdeaPad           | 1         | 1.69%   |
| Lenovo B50-70            | 1         | 1.69%   |
| HUAWEI NBLB-WAX9N        | 1         | 1.69%   |
| HP Spectre               | 1         | 1.69%   |
| Google Droid             | 1         | 1.69%   |
| Gigabyte GA-MA78GM-UD2H  | 1         | 1.69%   |
| Gigabyte B85M-DS3H       | 1         | 1.69%   |
| Dell XPS                 | 1         | 1.69%   |
| Dell OptiPlex            | 1         | 1.69%   |
| Dell Latitude            | 1         | 1.69%   |
| ASUS EX-A320M-GAMING     | 1         | 1.69%   |
| ASUS A88X-PLUS           | 1         | 1.69%   |
| Apple Macmini6           | 1         | 1.69%   |
| Apple MacBookPro6        | 1         | 1.69%   |
| Apple MacBookPro14       | 1         | 1.69%   |
| Apple MacBookAir7        | 1         | 1.69%   |
| Apple MacBook9           | 1         | 1.69%   |
| Apple iMac7              | 1         | 1.69%   |
| Apple iMac13             | 1         | 1.69%   |
| Apple iMac11             | 1         | 1.69%   |
| Acer Swift               | 1         | 1.69%   |
| Acer Nitro               | 1         | 1.69%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 9         | 15.25%  |
| 2013    | 7         | 11.86%  |
| 2021    | 6         | 10.17%  |
| 2019    | 5         | 8.47%   |
| 2018    | 5         | 8.47%   |
| 2017    | 5         | 8.47%   |
| 2015    | 4         | 6.78%   |
| 2020    | 3         | 5.08%   |
| 2011    | 3         | 5.08%   |
| 2016    | 2         | 3.39%   |
| 2014    | 2         | 3.39%   |
| 2012    | 2         | 3.39%   |
| 2009    | 2         | 3.39%   |
| 2007    | 2         | 3.39%   |
| 2023    | 1         | 1.69%   |
| 2010    | 1         | 1.69%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 39        | 66.1%   |
| Desktop        | 10        | 16.95%  |
| All in one     | 4         | 6.78%   |
| System on chip | 3         | 5.08%   |
| Phone          | 1         | 1.69%   |
| Convertible    | 1         | 1.69%   |
| Mini pc        | 1         | 1.69%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 59        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 45        | 76.27%  |
| Yes  | 14        | 23.73%  |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 13        | 22.03%  |
| 3.01-4.0   | 12        | 20.34%  |
| 16.01-24.0 | 12        | 20.34%  |
| 4.01-8.0   | 11        | 18.64%  |
| 32.01-64.0 | 6         | 10.17%  |
| 2.01-3.0   | 2         | 3.39%   |
| 1.01-2.0   | 2         | 3.39%   |
| 24.01-32.0 | 1         | 1.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 20        | 30.77%  |
| 1.01-2.0  | 17        | 26.15%  |
| 4.01-8.0  | 12        | 18.46%  |
| 3.01-4.0  | 12        | 18.46%  |
| 8.01-16.0 | 2         | 3.08%   |
| 0.51-1.0  | 1         | 1.54%   |
| 0.01-0.5  | 1         | 1.54%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 41        | 68.33%  |
| 2      | 15        | 25%     |
| 0      | 3         | 5%      |
| 5      | 1         | 1.67%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 47        | 79.66%  |
| Yes       | 12        | 20.34%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 76.27%  |
| No        | 14        | 23.73%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 46        | 77.97%  |
| No        | 13        | 22.03%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 64.41%  |
| No        | 21        | 35.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 13        | 21.31%  |
| Germany                | 8         | 13.11%  |
| UK                     | 6         | 9.84%   |
| Brazil                 | 6         | 9.84%   |
| Poland                 | 3         | 4.92%   |
| Italy                  | 3         | 4.92%   |
| Canada                 | 3         | 4.92%   |
| Australia              | 3         | 4.92%   |
| Russia                 | 2         | 3.28%   |
| France                 | 2         | 3.28%   |
| Turkey                 | 1         | 1.64%   |
| South Africa           | 1         | 1.64%   |
| Portugal               | 1         | 1.64%   |
| Paraguay               | 1         | 1.64%   |
| Martinique             | 1         | 1.64%   |
| Israel                 | 1         | 1.64%   |
| Iran                   | 1         | 1.64%   |
| Greece                 | 1         | 1.64%   |
| Costa Rica             | 1         | 1.64%   |
| China                  | 1         | 1.64%   |
| Bulgaria               | 1         | 1.64%   |
| Bosnia and Herzegovina | 1         | 1.64%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Stuttgart      | 3         | 4.76%   |
| Porto Alegre   | 3         | 4.76%   |
| Warsaw         | 2         | 3.17%   |
| New York       | 2         | 3.17%   |
| London         | 2         | 3.17%   |
| Berlin         | 2         | 3.17%   |
| Yuzhnoural'sk  | 1         | 1.59%   |
| Wixom          | 1         | 1.59%   |
| Windsor        | 1         | 1.59%   |
| Vancouver      | 1         | 1.59%   |
| Troy           | 1         | 1.59%   |
| Thorpe Hamlet  | 1         | 1.59%   |
| Tel Aviv       | 1         | 1.59%   |
| Stargard       | 1         | 1.59%   |
| Spencer        | 1         | 1.59%   |
| Sofia          | 1         | 1.59%   |
| Seattle        | 1         | 1.59%   |
| Sao Paulo      | 1         | 1.59%   |
| San Jose       | 1         | 1.59%   |
| Perth          | 1         | 1.59%   |
| Paris          | 1         | 1.59%   |
| Montreal       | 1         | 1.59%   |
| Milwaukee      | 1         | 1.59%   |
| Milpitas       | 1         | 1.59%   |
| Milan          | 1         | 1.59%   |
| Melbourne      | 1         | 1.59%   |
| Mankato        | 1         | 1.59%   |
| Liverpool      | 1         | 1.59%   |
| Lenningen      | 1         | 1.59%   |
| Leeds          | 1         | 1.59%   |
| Lambeth        | 1         | 1.59%   |
| Krasnogorsk    | 1         | 1.59%   |
| Istanbul       | 1         | 1.59%   |
| Hernandarias   | 1         | 1.59%   |
| Guimaraes      | 1         | 1.59%   |
| Grasse         | 1         | 1.59%   |
| Genoa          | 1         | 1.59%   |
| Fort-de-France | 1         | 1.59%   |
| Fort Collins   | 1         | 1.59%   |
| Eberswalde     | 1         | 1.59%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 21     | 23.53%  |
| Unknown             | 8         | 12     | 11.76%  |
| Seagate             | 6         | 10     | 8.82%   |
| Apple               | 6         | 8      | 8.82%   |
| WDC                 | 5         | 6      | 7.35%   |
| SanDisk             | 4         | 4      | 5.88%   |
| HGST                | 3         | 3      | 4.41%   |
| A-DATA Technology   | 3         | 4      | 4.41%   |
| Crucial             | 2         | 4      | 2.94%   |
| Win Memory          | 1         | 1      | 1.47%   |
| Transcend           | 1         | 1      | 1.47%   |
| Toshiba             | 1         | 1      | 1.47%   |
| PNY                 | 1         | 1      | 1.47%   |
| Plextor             | 1         | 1      | 1.47%   |
| Phison              | 1         | 1      | 1.47%   |
| Patriot             | 1         | 1      | 1.47%   |
| Mushkin             | 1         | 1      | 1.47%   |
| JMicron Technology  | 1         | 1      | 1.47%   |
| Intenso             | 1         | 2      | 1.47%   |
| Intel               | 1         | 1      | 1.47%   |
| Hitachi             | 1         | 1      | 1.47%   |
| BIWIN               | 1         | 1      | 1.47%   |
| ASMT                | 1         | 2      | 1.47%   |
| ADATA Technology    | 1         | 1      | 1.47%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Unknown MMC Card  64GB            | 2         | 2.67%   |
| Unknown MMC Card  32GB            | 2         | 2.67%   |
| Seagate ST1000LM048-2E7172 1TB    | 2         | 2.67%   |
| Samsung SSD 970 PRO 1TB           | 2         | 2.67%   |
| Samsung SSD 860 EVO 250GB         | 2         | 2.67%   |
| Win Memory SWR256G-201II 256GB    | 1         | 1.33%   |
| WDC WDS500G2B0A-00SM50 500GB SSD  | 1         | 1.33%   |
| WDC WDS100T2B0C-00PXH0 1TB        | 1         | 1.33%   |
| WDC WDBNCE2500PNC 250GB SSD       | 1         | 1.33%   |
| WDC WD5000AZRX-00A8LB0 500GB      | 1         | 1.33%   |
| WDC WD3200AAJS-40RYA0 320GB       | 1         | 1.33%   |
| Unknown SH64G  64GB               | 1         | 1.33%   |
| Unknown MMC Card  16GB            | 1         | 1.33%   |
| Unknown DA4128  128GB             | 1         | 1.33%   |
| Unknown AFGCF  128GB              | 1         | 1.33%   |
| Unknown 8GTF4R  8GB               | 1         | 1.33%   |
| Unknown 032G32  32GB              | 1         | 1.33%   |
| Transcend TS240GMTS420S 240GB SSD | 1         | 1.33%   |
| Toshiba NVMe SSD Drive 512GB      | 1         | 1.33%   |
| Seagate ST480HM000-1G5162 480GB   | 1         | 1.33%   |
| Seagate ST3320418AS 320GB         | 1         | 1.33%   |
| Seagate ST31000524AS 1TB          | 1         | 1.33%   |
| Seagate ST1000DM003-1ER162 1TB    | 1         | 1.33%   |
| Seagate NVMe SSD Drive 2TB        | 1         | 1.33%   |
| SanDisk SSD i100 24GB             | 1         | 1.33%   |
| SanDisk SDSSDP128G 128GB          | 1         | 1.33%   |
| SanDisk SDSSDH3500G 500GB         | 1         | 1.33%   |
| SanDisk NVMe SSD Drive 500GB      | 1         | 1.33%   |
| Samsung SSD 970 EVO Plus 500GB    | 1         | 1.33%   |
| Samsung SSD 970 EVO Plus 2TB      | 1         | 1.33%   |
| Samsung SSD 970 EVO 250GB         | 1         | 1.33%   |
| Samsung SSD 960 EVO 500GB         | 1         | 1.33%   |
| Samsung SSD 960 EVO 250GB         | 1         | 1.33%   |
| Samsung SSD 860 EVO M.2 250GB     | 1         | 1.33%   |
| Samsung SSD 860 EVO 500GB         | 1         | 1.33%   |
| Samsung SSD 860 EVO 1TB           | 1         | 1.33%   |
| Samsung SSD 850 EVO 500GB         | 1         | 1.33%   |
| Samsung SSD 850 EVO 250GB         | 1         | 1.33%   |
| Samsung SSD 830 Series 128GB      | 1         | 1.33%   |
| Samsung NVMe SSD Drive 1TB        | 1         | 1.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 9      | 31.25%  |
| HGST                | 3         | 3      | 18.75%  |
| Apple               | 3         | 3      | 18.75%  |
| WDC                 | 2         | 2      | 12.5%   |
| Samsung Electronics | 1         | 1      | 6.25%   |
| Hitachi             | 1         | 1      | 6.25%   |
| ASMT                | 1         | 2      | 6.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 11     | 27.59%  |
| SanDisk             | 3         | 3      | 10.34%  |
| A-DATA Technology   | 3         | 4      | 10.34%  |
| WDC                 | 2         | 3      | 6.9%    |
| Crucial             | 2         | 4      | 6.9%    |
| Win Memory          | 1         | 1      | 3.45%   |
| Transcend           | 1         | 1      | 3.45%   |
| PNY                 | 1         | 1      | 3.45%   |
| Plextor             | 1         | 1      | 3.45%   |
| Patriot             | 1         | 1      | 3.45%   |
| Mushkin             | 1         | 1      | 3.45%   |
| JMicron Technology  | 1         | 1      | 3.45%   |
| Intenso             | 1         | 2      | 3.45%   |
| Intel               | 1         | 1      | 3.45%   |
| BIWIN               | 1         | 1      | 3.45%   |
| Apple               | 1         | 1      | 3.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 25        | 37     | 39.06%  |
| NVMe | 16        | 19     | 25%     |
| HDD  | 15        | 21     | 23.44%  |
| MMC  | 8         | 12     | 12.5%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 36        | 54     | 57.14%  |
| NVMe | 16        | 19     | 25.4%   |
| MMC  | 8         | 12     | 12.7%   |
| SAS  | 3         | 4      | 4.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 28        | 44     | 71.79%  |
| 0.51-1.0   | 9         | 11     | 23.08%  |
| 1.01-2.0   | 2         | 3      | 5.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 27        | 44.26%  |
| 101-250    | 8         | 13.11%  |
| 251-500    | 6         | 9.84%   |
| 21-50      | 5         | 8.2%    |
| 501-1000   | 4         | 6.56%   |
| 51-100     | 4         | 6.56%   |
| 1001-2000  | 3         | 4.92%   |
| Unknown    | 3         | 4.92%   |
| 2001-3000  | 1         | 1.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 39        | 63.93%  |
| 21-50    | 11        | 18.03%  |
| 101-250  | 3         | 4.92%   |
| 501-1000 | 3         | 4.92%   |
| Unknown  | 3         | 4.92%   |
| 251-500  | 1         | 1.64%   |
| 51-100   | 1         | 1.64%   |

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
| Detected | 41        | 64     | 68.33%  |
| Works    | 16        | 22     | 26.67%  |
| Malfunc  | 3         | 3      | 5%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 34        | 60.71%  |
| Samsung Electronics          | 9         | 16.07%  |
| AMD                          | 5         | 8.93%   |
| SanDisk                      | 2         | 3.57%   |
| Apple                        | 2         | 3.57%   |
| Toshiba America Info Systems | 1         | 1.79%   |
| Seagate Technology           | 1         | 1.79%   |
| Phison Electronics           | 1         | 1.79%   |
| ADATA Technology             | 1         | 1.79%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 11.86%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 6         | 10.17%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 8.47%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 5.08%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 5.08%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 3         | 5.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 3.39%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 3.39%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 3.39%   |
| Apple S3X NVMe Controller                                                      | 2         | 3.39%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 1.69%   |
| Seagate FireCuda 510 SSD                                                       | 1         | 1.69%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 1         | 1.69%   |
| SanDisk Non-Volatile memory controller                                         | 1         | 1.69%   |
| Samsung Electronics SATA controller                                            | 1         | 1.69%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 1.69%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.69%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.69%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 1.69%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.69%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 1         | 1.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 1         | 1.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 1         | 1.69%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 1.69%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1         | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1         | 1.69%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 1.69%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 1         | 1.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 1.69%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 1         | 1.69%   |
| AMD FCH SATA Controller D                                                      | 1         | 1.69%   |
| ADATA Non-Volatile memory controller                                           | 1         | 1.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 38        | 66.67%  |
| NVMe | 16        | 28.07%  |
| IDE  | 3         | 5.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 47        | 78.33%  |
| ARM     | 6         | 10%     |
| AMD     | 5         | 8.33%   |
| Unknown | 2         | 3.33%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Core i7-10710U CPU @ 1.10GHz       | 6         | 10%     |
| ARM Processor                            | 6         | 10%     |
| Intel Core i7-7500U CPU @ 2.70GHz        | 4         | 6.67%   |
| Intel Core i7-6500U CPU @ 2.50GHz        | 2         | 3.33%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 2         | 3.33%   |
|                                          | 2         | 3.33%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz | 1         | 1.67%   |
| Intel Pentium CPU N4200 @ 1.10GHz        | 1         | 1.67%   |
| Intel Core m5-6Y54 CPU @ 1.10GHz         | 1         | 1.67%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 1         | 1.67%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz       | 1         | 1.67%   |
| Intel Core i7-7567U CPU @ 3.50GHz        | 1         | 1.67%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz       | 1         | 1.67%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz       | 1         | 1.67%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz       | 1         | 1.67%   |
| Intel Core i7-4510U CPU @ 2.00GHz        | 1         | 1.67%   |
| Intel Core i7-10510U CPU @ 1.80GHz       | 1         | 1.67%   |
| Intel Core i5-5250U CPU @ 1.60GHz        | 1         | 1.67%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 1         | 1.67%   |
| Intel Core i5-4460 CPU @ 3.20GHz         | 1         | 1.67%   |
| Intel Core i5-4210U CPU @ 1.70GHz        | 1         | 1.67%   |
| Intel Core i5-4200U CPU @ 1.60GHz        | 1         | 1.67%   |
| Intel Core i5-3330S CPU @ 2.70GHz        | 1         | 1.67%   |
| Intel Core i5-3210M CPU @ 2.50GHz        | 1         | 1.67%   |
| Intel Core i5-2320 CPU @ 3.00GHz         | 1         | 1.67%   |
| Intel Core i5-10210U CPU @ 1.60GHz       | 1         | 1.67%   |
| Intel Core i5 CPU M 540 @ 2.53GHz        | 1         | 1.67%   |
| Intel Core i5 CPU 750 @ 2.67GHz          | 1         | 1.67%   |
| Intel Core i3-4130T CPU @ 2.90GHz        | 1         | 1.67%   |
| Intel Core i3-4010U CPU @ 1.70GHz        | 1         | 1.67%   |
| Intel Core i3-3217U CPU @ 1.80GHz        | 1         | 1.67%   |
| Intel Core i3-3120M CPU @ 2.50GHz        | 1         | 1.67%   |
| Intel Core i3-2330M CPU @ 2.20GHz        | 1         | 1.67%   |
| Intel Core 2 Duo CPU U7700 @ 1.33GHz     | 1         | 1.67%   |
| Intel Core 2 Duo CPU T7700 @ 2.40GHz     | 1         | 1.67%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz     | 1         | 1.67%   |
| Intel Celeron N4100 CPU @ 1.10GHz        | 1         | 1.67%   |
| Intel Celeron J4005 CPU @ 2.00GHz        | 1         | 1.67%   |
| Intel Celeron CPU 4205U @ 1.80GHz        | 1         | 1.67%   |
| AMD Turion II Dual-Core Mobile M520      | 1         | 1.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 20        | 33.9%   |
| Intel Core i5           | 13        | 22.03%  |
| Other                   | 7         | 11.86%  |
| Intel Core i3           | 5         | 8.47%   |
| Intel Core 2 Duo        | 3         | 5.08%   |
| Intel Celeron           | 3         | 5.08%   |
| Intel Pentium Silver    | 1         | 1.69%   |
| Intel Pentium           | 1         | 1.69%   |
| Intel Core m5           | 1         | 1.69%   |
| AMD Turion II Dual-Core | 1         | 1.69%   |
| AMD Ryzen 5             | 1         | 1.69%   |
| AMD Ryzen 3             | 1         | 1.69%   |
| AMD Athlon II X4        | 1         | 1.69%   |
| AMD A10                 | 1         | 1.69%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 29        | 49.15%  |
| 4       | 23        | 38.98%  |
| 6       | 6         | 10.17%  |
| Unknown | 1         | 1.69%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 58        | 98.31%  |
| Unknown | 1         | 1.69%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 37        | 62.71%  |
| 1       | 21        | 35.59%  |
| Unknown | 1         | 1.69%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 55        | 91.67%  |
| Unknown        | 4         | 6.67%   |
| 64-bit         | 1         | 1.67%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 44        | 72.13%  |
| 0xa0660    | 3         | 4.92%   |
| 0x406e3    | 3         | 4.92%   |
| 0x706a1    | 2         | 3.28%   |
| 0x40651    | 2         | 3.28%   |
| 0x806ec    | 1         | 1.64%   |
| 0x806e9    | 1         | 1.64%   |
| 0x306d4    | 1         | 1.64%   |
| 0x206a7    | 1         | 1.64%   |
| 0x1067a    | 1         | 1.64%   |
| 0x08108109 | 1         | 1.64%   |
| 0x06003106 | 1         | 1.64%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 12        | 20.34%  |
| Haswell       | 9         | 15.25%  |
| Unknown       | 7         | 11.86%  |
| CometLake     | 6         | 10.17%  |
| IvyBridge     | 4         | 6.78%   |
| Skylake       | 3         | 5.08%   |
| Goldmont plus | 3         | 5.08%   |
| Zen+          | 2         | 3.39%   |
| SandyBridge   | 2         | 3.39%   |
| K10           | 2         | 3.39%   |
| Core          | 2         | 3.39%   |
| Broadwell     | 2         | 3.39%   |
| Westmere      | 1         | 1.69%   |
| Steamroller   | 1         | 1.69%   |
| Penryn        | 1         | 1.69%   |
| Nehalem       | 1         | 1.69%   |
| Goldmont      | 1         | 1.69%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 43        | 72.88%  |
| Nvidia | 8         | 13.56%  |
| AMD    | 8         | 13.56%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                 | 6         | 9.68%   |
| Intel Comet Lake UHD Graphics                                                         | 6         | 9.68%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 4         | 6.45%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 3         | 4.84%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 3         | 4.84%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 2         | 3.23%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 2         | 3.23%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 2         | 3.23%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 2         | 3.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 2         | 3.23%   |
| Nvidia TU116 [GeForce GTX 1660]                                                       | 1         | 1.61%   |
| Nvidia GT216M [GeForce GT 330M]                                                       | 1         | 1.61%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 1         | 1.61%   |
| Nvidia GK208M [GeForce GT 730M]                                                       | 1         | 1.61%   |
| Nvidia GK208B [GeForce GT 710]                                                        | 1         | 1.61%   |
| Nvidia GK107M [GeForce GT 640M Mac Edition]                                           | 1         | 1.61%   |
| Nvidia GK104M [GeForce GTX 870M]                                                      | 1         | 1.61%   |
| Nvidia GF116 [GeForce GTS 450 Rev. 2]                                                 | 1         | 1.61%   |
| Nvidia GF108 [GeForce GT 630]                                                         | 1         | 1.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 1         | 1.61%   |
| Intel Whiskey Lake-U GT1 [UHD Graphics 610]                                           | 1         | 1.61%   |
| Intel UHD Graphics 620                                                                | 1         | 1.61%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller         | 1         | 1.61%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller             | 1         | 1.61%   |
| Intel Iris Plus Graphics 650                                                          | 1         | 1.61%   |
| Intel HD Graphics 630                                                                 | 1         | 1.61%   |
| Intel HD Graphics 6000                                                                | 1         | 1.61%   |
| Intel HD Graphics 5500                                                                | 1         | 1.61%   |
| Intel HD Graphics 515                                                                 | 1         | 1.61%   |
| Intel GeminiLake [UHD Graphics 605]                                                   | 1         | 1.61%   |
| Intel Core Processor Integrated Graphics Controller                                   | 1         | 1.61%   |
| Intel Apollo Lake [HD Graphics 505]                                                   | 1         | 1.61%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                 | 1         | 1.61%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 1.61%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                             | 1         | 1.61%   |
| AMD RV770/M98L [Mobility Radeon HD 4850]                                              | 1         | 1.61%   |
| AMD RV630/M76 [Mobility Radeon HD 2600 XT/2700]                                       | 1         | 1.61%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                             | 1         | 1.61%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                                    | 1         | 1.61%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                   | 1         | 1.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 35        | 59.32%  |
| Other          | 8         | 13.56%  |
| 1 x AMD        | 5         | 8.47%   |
| 1 x Nvidia     | 4         | 6.78%   |
| Intel + Nvidia | 4         | 6.78%   |
| Intel + AMD    | 2         | 3.39%   |
| 2 x AMD        | 1         | 1.69%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 50        | 84.75%  |
| Unknown | 9         | 15.25%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 58        | 96.67%  |
| 3.01-4.0   | 1         | 1.67%   |
| 0.51-1.0   | 1         | 1.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 9         | 15.25%  |
| Samsung Electronics     | 8         | 13.56%  |
| BOE                     | 7         | 11.86%  |
| LG Display              | 6         | 10.17%  |
| Apple                   | 6         | 10.17%  |
| Philips                 | 2         | 3.39%   |
| Goldstar                | 2         | 3.39%   |
| AU Optronics            | 2         | 3.39%   |
| Unknown                 | 1         | 1.69%   |
| Toshiba                 | 1         | 1.69%   |
| Sony                    | 1         | 1.69%   |
| Sharp                   | 1         | 1.69%   |
| RTK                     | 1         | 1.69%   |
| PRI                     | 1         | 1.69%   |
| PANDA                   | 1         | 1.69%   |
| Lenovo                  | 1         | 1.69%   |
| Iiyama                  | 1         | 1.69%   |
| Grundig                 | 1         | 1.69%   |
| Flipbook                | 1         | 1.69%   |
| Dell                    | 1         | 1.69%   |
| Chi Mei Optoelectronics | 1         | 1.69%   |
| BenQ                    | 1         | 1.69%   |
| ASUSTek Computer        | 1         | 1.69%   |
| AOC                     | 1         | 1.69%   |
| Acer                    | 1         | 1.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC434B 3840x2160 344x194mm 15.5-inch     | 3         | 5.08%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 3         | 5.08%   |
| Philips TV PHL5035 1920x1080 640x360mm 28.9-inch                          | 2         | 3.39%   |
| Chimei Innolux LCD Monitor CMN1415 1920x1080 309x173mm 13.9-inch          | 2         | 3.39%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 1         | 1.69%   |
| Toshiba LCD Monitor LCD3706 1280x800 261x163mm 12.1-inch                  | 1         | 1.69%   |
| Sony TV SNYAB03 1920x1080                                                 | 1         | 1.69%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                   | 1         | 1.69%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 474x296mm 22.0-inch      | 1         | 1.69%   |
| Samsung Electronics SyncMaster SAM01D3 1440x900 408x225mm 18.3-inch       | 1         | 1.69%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch      | 1         | 1.69%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 410x230mm 18.5-inch      | 1         | 1.69%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 1         | 1.69%   |
| RTK LG AIO FHD RTK2136 1920x1080 477x268mm 21.5-inch                      | 1         | 1.69%   |
| PRI Prima TV PRI1600 1920x1080                                            | 1         | 1.69%   |
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch                   | 1         | 1.69%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch              | 1         | 1.69%   |
| LG Display LCD Monitor LGD053B 1920x1080 294x165mm 13.3-inch              | 1         | 1.69%   |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch              | 1         | 1.69%   |
| LG Display LCD Monitor LGD03F0 1366x768 310x174mm 14.0-inch               | 1         | 1.69%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch               | 1         | 1.69%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch               | 1         | 1.69%   |
| Lenovo LEN Y44w-10 LEN65EA 3840x1200 1052x329mm 43.4-inch                 | 1         | 1.69%   |
| Iiyama PL2792H IVM664F 1920x1080 598x336mm 27.0-inch                      | 1         | 1.69%   |
| Grundig WUXGA GRU4448 1920x1080                                           | 1         | 1.69%   |
| Goldstar IPS231 GSM5817 1920x1080 510x290mm 23.1-inch                     | 1         | 1.69%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                    | 1         | 1.69%   |
| Flipbook NexDock YUKBC34 1920x1080 290x170mm 13.2-inch                    | 1         | 1.69%   |
| Dell P2213 DELF042 1680x1050 473x296mm 22.0-inch                          | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch          | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN15BD 1366x768 344x193mm 15.5-inch           | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch           | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN1365 1920x1080 293x165mm 13.2-inch          | 1         | 1.69%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 1.69%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                     | 1         | 1.69%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                     | 1         | 1.69%   |
| BOE LCD Monitor BOE079A 1920x1080 309x173mm 13.9-inch                     | 1         | 1.69%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                      | 1         | 1.69%   |
| BOE LCD Monitor BOE06C2 1366x768 344x194mm 15.5-inch                      | 1         | 1.69%   |
| BOE LCD Monitor BOE06BE 1920x1080 294x165mm 13.3-inch                     | 1         | 1.69%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 27        | 49.09%  |
| 1366x768 (WXGA)    | 9         | 16.36%  |
| 3840x2160 (4K)     | 6         | 10.91%  |
| 1680x1050 (WSXGA+) | 3         | 5.45%   |
| 1600x900 (HD+)     | 2         | 3.64%   |
| 1440x900 (WXGA+)   | 2         | 3.64%   |
| 3840x1200          | 1         | 1.82%   |
| 2880x1800          | 1         | 1.82%   |
| 2304x1440          | 1         | 1.82%   |
| 2288x1287          | 1         | 1.82%   |
| 1920x1200 (WUXGA)  | 1         | 1.82%   |
| 1280x800 (WXGA)    | 1         | 1.82%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 17        | 28.81%  |
| 15      | 13        | 22.03%  |
| 23      | 3         | 5.08%   |
| 14      | 3         | 5.08%   |
| 28      | 2         | 3.39%   |
| 24      | 2         | 3.39%   |
| 22      | 2         | 3.39%   |
| 21      | 2         | 3.39%   |
| 20      | 2         | 3.39%   |
| 17      | 2         | 3.39%   |
| 12      | 2         | 3.39%   |
| 142     | 1         | 1.69%   |
| 72      | 1         | 1.69%   |
| 54      | 1         | 1.69%   |
| 43      | 1         | 1.69%   |
| 40      | 1         | 1.69%   |
| 31      | 1         | 1.69%   |
| 27      | 1         | 1.69%   |
| 19      | 1         | 1.69%   |
| Unknown | 1         | 1.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 23        | 39.66%  |
| 201-300        | 10        | 17.24%  |
| 401-500        | 7         | 12.07%  |
| 501-600        | 6         | 10.34%  |
| 601-700        | 3         | 5.17%   |
| 351-400        | 3         | 5.17%   |
| 1001-1500      | 2         | 3.45%   |
| More than 2000 | 1         | 1.72%   |
| 801-900        | 1         | 1.72%   |
| 1501-2000      | 1         | 1.72%   |
| Unknown        | 1         | 1.72%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 40        | 78.43%  |
| 16/10 | 9         | 17.65%  |
| 3.20  | 1         | 1.96%   |
| 1.00  | 1         | 1.96%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 13        | 22.03%  |
| 101-110        | 13        | 22.03%  |
| 201-250        | 9         | 15.25%  |
| 71-80          | 7         | 11.86%  |
| More than 1000 | 3         | 5.08%   |
| 351-500        | 3         | 5.08%   |
| 151-200        | 3         | 5.08%   |
| 61-70          | 2         | 3.39%   |
| 501-1000       | 2         | 3.39%   |
| 301-350        | 1         | 1.69%   |
| 131-140        | 1         | 1.69%   |
| 121-130        | 1         | 1.69%   |
| Unknown        | 1         | 1.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 17        | 28.81%  |
| 51-100        | 17        | 28.81%  |
| 101-120       | 9         | 15.25%  |
| More than 240 | 6         | 10.17%  |
| 161-240       | 6         | 10.17%  |
| 1-50          | 3         | 5.08%   |
| Unknown       | 1         | 1.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 42        | 71.19%  |
| 2     | 8         | 13.56%  |
| 0     | 8         | 13.56%  |
| 3     | 1         | 1.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 33        | 37.08%  |
| Qualcomm Atheros                | 17        | 19.1%   |
| Intel                           | 15        | 16.85%  |
| Broadcom                        | 9         | 10.11%  |
| Broadcom Limited                | 4         | 4.49%   |
| Qualcomm Atheros Communications | 2         | 2.25%   |
| ASIX Electronics                | 2         | 2.25%   |
| Samsung Electronics             | 1         | 1.12%   |
| Ralink                          | 1         | 1.12%   |
| OPPO Electronics                | 1         | 1.12%   |
| MediaTek                        | 1         | 1.12%   |
| Marvell Technology Group        | 1         | 1.12%   |
| Edimax Technology               | 1         | 1.12%   |
| ASUSTek Computer                | 1         | 1.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 22        | 22.22%  |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 12        | 12.12%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 5         | 5.05%   |
| Intel Wireless 7265                                                           | 4         | 4.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 3         | 3.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 3         | 3.03%   |
| Intel Wireless 7260                                                           | 3         | 3.03%   |
| Qualcomm Atheros AR9271 802.11n                                               | 2         | 2.02%   |
| Intel Ethernet Connection I217-LM                                             | 2         | 2.02%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 2         | 2.02%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2         | 2.02%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                    | 2         | 2.02%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 2         | 2.02%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1         | 1.01%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1         | 1.01%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 1.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.01%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 1         | 1.01%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1         | 1.01%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 1.01%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1         | 1.01%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                        | 1         | 1.01%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 1.01%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.01%   |
| OPPO SM8350-MTP _SN:1518BD09                                                  | 1         | 1.01%   |
| MediaTek WiFi                                                                 | 1         | 1.01%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                       | 1         | 1.01%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 1.01%   |
| Intel I211 Gigabit Network Connection                                         | 1         | 1.01%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1         | 1.01%   |
| Intel Ethernet Connection I218-V                                              | 1         | 1.01%   |
| Intel Ethernet Connection (6) I219-LM                                         | 1         | 1.01%   |
| Intel Ethernet Connection (4) I219-V                                          | 1         | 1.01%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 1.01%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 1         | 1.01%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 1.01%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1         | 1.01%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                                   | 1         | 1.01%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                       | 1         | 1.01%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                                        | 1         | 1.01%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 17        | 32.69%  |
| Intel                           | 12        | 23.08%  |
| Realtek Semiconductor           | 7         | 13.46%  |
| Broadcom                        | 6         | 11.54%  |
| Broadcom Limited                | 4         | 7.69%   |
| Qualcomm Atheros Communications | 2         | 3.85%   |
| Ralink                          | 1         | 1.92%   |
| MediaTek                        | 1         | 1.92%   |
| Edimax Technology               | 1         | 1.92%   |
| ASUSTek Computer                | 1         | 1.92%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 12        | 23.08%  |
| Intel Wireless 7265                                                           | 4         | 7.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 3         | 5.77%   |
| Intel Wireless 7260                                                           | 3         | 5.77%   |
| Qualcomm Atheros AR9271 802.11n                                               | 2         | 3.85%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                    | 2         | 3.85%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1         | 1.92%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 1.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.92%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 1         | 1.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1         | 1.92%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 1.92%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1         | 1.92%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                        | 1         | 1.92%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 1.92%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.92%   |
| MediaTek WiFi                                                                 | 1         | 1.92%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 1.92%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1         | 1.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 1.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 1         | 1.92%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 1.92%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                                   | 1         | 1.92%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                                        | 1         | 1.92%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                        | 1         | 1.92%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 1         | 1.92%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                            | 1         | 1.92%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 1         | 1.92%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 1         | 1.92%   |
| Broadcom BCM4321 802.11a/b/g/n                                                | 1         | 1.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 1         | 1.92%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                     | 1         | 1.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 29        | 64.44%  |
| Intel                    | 6         | 13.33%  |
| Broadcom                 | 5         | 11.11%  |
| ASIX Electronics         | 2         | 4.44%   |
| Samsung Electronics      | 1         | 2.22%   |
| OPPO Electronics         | 1         | 2.22%   |
| Marvell Technology Group | 1         | 2.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 22        | 46.81%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 10.64%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 6.38%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 4.26%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 4.26%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 4.26%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 4.26%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 2.13%   |
| OPPO SM8350-MTP _SN:1518BD09                                      | 1         | 2.13%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 2.13%   |
| Intel I211 Gigabit Network Connection                             | 1         | 2.13%   |
| Intel Ethernet Connection I218-V                                  | 1         | 2.13%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 2.13%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 2.13%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 2.13%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 2.13%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 45        | 51.14%  |
| Ethernet | 43        | 48.86%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 32        | 61.54%  |
| WiFi     | 20        | 38.46%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 29        | 49.15%  |
| 1     | 20        | 33.9%   |
| 0     | 8         | 13.56%  |
| 3     | 2         | 3.39%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 45        | 76.27%  |
| Yes  | 14        | 23.73%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 11        | 28.21%  |
| Apple                           | 7         | 17.95%  |
| Qualcomm Atheros Communications | 6         | 15.38%  |
| Foxconn / Hon Hai               | 5         | 12.82%  |
| Lite-On Technology              | 4         | 10.26%  |
| Realtek Semiconductor           | 2         | 5.13%   |
| IMC Networks                    | 1         | 2.56%   |
| Cambridge Silicon Radio         | 1         | 2.56%   |
| Broadcom                        | 1         | 2.56%   |
| ASUSTek Computer                | 1         | 2.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                   | 7         | 17.95%  |
| Foxconn / Hon Hai Bluetooth Device                   | 5         | 12.82%  |
| Lite-On Atheros AR3012 Bluetooth                     | 4         | 10.26%  |
| Apple Bluetooth USB Host Controller                  | 3         | 7.69%   |
| Qualcomm Atheros  Bluetooth Device                   | 2         | 5.13%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                | 2         | 5.13%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)       | 2         | 5.13%   |
| Apple Bluetooth Host Controller                      | 2         | 5.13%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter              | 1         | 2.56%   |
| Realtek RTL8723B Bluetooth                           | 1         | 2.56%   |
| Qualcomm Atheros Dell Wireless 1802 Bluetooth 4.0 LE | 1         | 2.56%   |
| Qualcomm Atheros AR9462 Bluetooth                    | 1         | 2.56%   |
| Intel Wireless-AC 3168 Bluetooth                     | 1         | 2.56%   |
| Intel Centrino Bluetooth Wireless Transceiver        | 1         | 2.56%   |
| IMC Networks Bluetooth Radio                         | 1         | 2.56%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)  | 1         | 2.56%   |
| Broadcom HP Portable Valentine                       | 1         | 2.56%   |
| ASUS Broadcom BCM20702A0 Bluetooth                   | 1         | 2.56%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                 | 1         | 2.56%   |
| Apple Bluetooth HCI                                  | 1         | 2.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 46        | 71.88%  |
| AMD      | 7         | 10.94%  |
| Nvidia   | 6         | 9.38%   |
| XMOS     | 1         | 1.56%   |
| Shure    | 1         | 1.56%   |
| Micronas | 1         | 1.56%   |
| M-Audio  | 1         | 1.56%   |
| Logitech | 1         | 1.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 11        | 14.29%  |
| Intel Comet Lake PCH-LP cAVS                                               | 8         | 10.39%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 5.19%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 5.19%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 5.19%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 5.19%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 5.19%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 3.9%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 2.6%    |
| Intel Broadwell-U Audio Controller                                         | 2         | 2.6%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 2.6%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 2.6%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 2.6%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.6%    |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 2.6%    |
| XMOS xCORE USB Audio 2.0                                                   | 1         | 1.3%    |
| Shure MV5                                                                  | 1         | 1.3%    |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 1.3%    |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 1.3%    |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.3%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.3%    |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 1.3%    |
| Nvidia GF116 High Definition Audio Controller                              | 1         | 1.3%    |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.3%    |
| Micronas QSB                                                               | 1         | 1.3%    |
| M-Audio M-Audio Fast Track MKII                                            | 1         | 1.3%    |
| Logitech Headset H340                                                      | 1         | 1.3%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 1.3%    |
| Intel CM238 HD Audio Controller                                            | 1         | 1.3%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1.3%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.3%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1         | 1.3%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 1.3%    |
| AMD RV770 HDMI Audio [Radeon HD 4850/4870]                                 | 1         | 1.3%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 1.3%    |
| AMD FCH Azalia Controller                                                  | 1         | 1.3%    |

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
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1600MT/s          | 1         | 4%      |
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


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Brother DCP-L3550CDW | 1         | 100%    |

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
| Apple                                  | 6         | 16.67%  |
| Realtek Semiconductor                  | 5         | 13.89%  |
| Bison Electronics                      | 5         | 13.89%  |
| Chicony Electronics                    | 4         | 11.11%  |
| Alcor Micro                            | 4         | 11.11%  |
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

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Apple Built-in iSight                                                      | 3         | 8.11%   |
| Alcor Micro HD WebCam                                                      | 3         | 8.11%   |
| Realtek USB Camera                                                         | 2         | 5.41%   |
| Chicony HD User Facing                                                     | 2         | 5.41%   |
| Bison SunplusIT INC. Integrated Camera                                     | 2         | 5.41%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 2         | 5.41%   |
| Suyin HP Wide Vision FHD Camera                                            | 1         | 2.7%    |
| Sunplus Integrated_Webcam_HD                                               | 1         | 2.7%    |
| Sunplus Integrated Camera                                                  | 1         | 2.7%    |
| Sunplus HD WebCam                                                          | 1         | 2.7%    |
| Silicon Motion WebCam SC-13HDL12131N                                       | 1         | 2.7%    |
| Realtek Integrated_Webcam_HD                                               | 1         | 2.7%    |
| Realtek Integrated Webcam                                                  | 1         | 2.7%    |
| Realtek HP Truevision HD                                                   | 1         | 2.7%    |
| Quanta HD Camera                                                           | 1         | 2.7%    |
| Microdia HP Integrated Webcam                                              | 1         | 2.7%    |
| Lite-On Integrated Camera                                                  | 1         | 2.7%    |
| IMC Networks Lenovo EasyCamera                                             | 1         | 2.7%    |
| Genesys Logic Camera                                                       | 1         | 2.7%    |
| Chicony USB2.0 UVC WebCam                                                  | 1         | 2.7%    |
| Chicony LG HD WebCam                                                       | 1         | 2.7%    |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 1         | 2.7%    |
| Bison SunplusIT Integrated Camera                                          | 1         | 2.7%    |
| Bison Lenovo EasyCamera                                                    | 1         | 2.7%    |
| Bison BisonCam, NB Pro                                                     | 1         | 2.7%    |
| Apple iBridge                                                              | 1         | 2.7%    |
| Apple FaceTime HD Camera (Built-in)                                        | 1         | 2.7%    |
| Alcor Micro HP Webcam-101                                                  | 1         | 2.7%    |
| Unknown                                                                    | 1         | 2.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 4         | 50%     |
| LighTuning Technology | 2         | 25%     |
| Synaptics             | 1         | 12.5%   |
| STMicroelectronics    | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                            | Computers | Percent |
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
| 0     | 32        | 53.33%  |
| 1     | 21        | 35%     |
| 2     | 4         | 6.67%   |
| 3     | 2         | 3.33%   |
| 4     | 1         | 1.67%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 11        | 28.95%  |
| Fingerprint reader    | 8         | 21.05%  |
| Bluetooth             | 7         | 18.42%  |
| Graphics card         | 6         | 15.79%  |
| Multimedia controller | 3         | 7.89%   |
| Chipcard              | 2         | 5.26%   |
| Camera                | 1         | 2.63%   |

