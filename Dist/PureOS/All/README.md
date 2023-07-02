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

Total: 86

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Microsoft     | Surface Book 2              | Tablet      | [b72660e9a4](https://linux-hardware.org/?probe=b72660e9a4) | Jun 17, 2023 |
| ASUSTek       | M4N68T V2                   | Desktop     | [4be2f626a3](https://linux-hardware.org/?probe=4be2f626a3) | Jun 11, 2023 |
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

![OS](./images/pie_chart/os_name.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| PureOS 10.0 | 22        | 35.48%  |
| PureOS 10   | 22        | 35.48%  |
| PureOS 9.0  | 13        | 20.97%  |
| PureOS 9    | 3         | 4.84%   |
| PureOS 8    | 2         | 3.23%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| PureOS | 61        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Computers | Percent |
|----------------------------------|-----------|---------|
| 4.19.0-5-amd64                   | 10        | 15.15%  |
| 5.10.0-14-amd64                  | 8         | 12.12%  |
| 5.10.0-13-amd64                  | 5         | 7.58%   |
| 5.10.0-8-amd64                   | 4         | 6.06%   |
| 5.10.0-21-amd64                  | 4         | 6.06%   |
| 5.10.0-11-amd64                  | 4         | 6.06%   |
| 4.19.0-14-amd64                  | 4         | 6.06%   |
| 6.1.0-1-librem5                  | 2         | 3.03%   |
| 5.7.0-1-librem5                  | 2         | 3.03%   |
| 5.10.0-9-amd64                   | 2         | 3.03%   |
| 5.10.0-7-amd64                   | 2         | 3.03%   |
| 5.10.0-23-amd64                  | 2         | 3.03%   |
| 5.10.0-19-amd64                  | 2         | 3.03%   |
| 5.10.0-16-amd64                  | 2         | 3.03%   |
| 6.0.0-1-librem5                  | 1         | 1.52%   |
| 5.9-sunxi64                      | 1         | 1.52%   |
| 5.8-sunxi64                      | 1         | 1.52%   |
| 5.7.0-0.38-1-pinebookpro-hwaccel | 1         | 1.52%   |
| 5.15.0-2-amd64                   | 1         | 1.52%   |
| 5.10.0-6-amd64                   | 1         | 1.52%   |
| 5.10.0-20-amd64                  | 1         | 1.52%   |
| 5.10.0-18-amd64                  | 1         | 1.52%   |
| 5.10.0-17-amd64                  | 1         | 1.52%   |
| 5.10.0-15-amd64                  | 1         | 1.52%   |
| 5.10.0-12-amd64                  | 1         | 1.52%   |
| 4.19.72-imx8-sr                  | 1         | 1.52%   |
| 4.16.0-1-amd64                   | 1         | 1.52%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 39        | 60.94%  |
| 4.19.0  | 14        | 21.88%  |
| 5.7.0   | 3         | 4.69%   |
| 6.1.0   | 2         | 3.13%   |
| 6.0.0   | 1         | 1.56%   |
| 5.9     | 1         | 1.56%   |
| 5.8     | 1         | 1.56%   |
| 5.15.0  | 1         | 1.56%   |
| 4.19.72 | 1         | 1.56%   |
| 4.16.0  | 1         | 1.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 39        | 61.9%   |
| 4.19    | 15        | 23.81%  |
| 5.7     | 3         | 4.76%   |
| 6.1     | 2         | 3.17%   |
| 6.0     | 1         | 1.59%   |
| 5.15    | 1         | 1.59%   |
| 5       | 1         | 1.59%   |
| 4.16    | 1         | 1.59%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 54        | 88.52%  |
| aarch64 | 7         | 11.48%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 52        | 81.25%  |
| Unknown         | 6         | 9.38%   |
| KDE5            | 3         | 4.69%   |
| Phosh:GNOME     | 1         | 1.56%   |
| MATE            | 1         | 1.56%   |
| GNOME Flashback | 1         | 1.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 44        | 66.67%  |
| X11     | 11        | 16.67%  |
| Unknown | 6         | 9.09%   |
| Tty     | 5         | 7.58%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 36        | 59.02%  |
| GDM     | 17        | 27.87%  |
| GDM3    | 7         | 11.48%  |
| SDDM    | 1         | 1.64%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 26        | 40.63%  |
| de_DE   | 6         | 9.38%   |
| en_GB   | 5         | 7.81%   |
| Unknown | 4         | 6.25%   |
| ru_RU   | 3         | 4.69%   |
| pl_PL   | 3         | 4.69%   |
| C       | 3         | 4.69%   |
| pt_BR   | 2         | 3.13%   |
| it_IT   | 2         | 3.13%   |
| fr_FR   | 2         | 3.13%   |
| en_AU   | 2         | 3.13%   |
| zh_CN   | 1         | 1.56%   |
| pt_PT   | 1         | 1.56%   |
| hu_HU   | 1         | 1.56%   |
| es_CR   | 1         | 1.56%   |
| en_IL   | 1         | 1.56%   |
| bg_BG   | 1         | 1.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 52        | 83.87%  |
| EFI  | 10        | 16.13%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 55        | 90.16%  |
| Overlay | 2         | 3.28%   |
| Unknown | 2         | 3.28%   |
| Ext2    | 1         | 1.64%   |
| Btrfs   | 1         | 1.64%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 35        | 55.56%  |
| MBR     | 15        | 23.81%  |
| GPT     | 13        | 20.63%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 52        | 85.25%  |
| Yes       | 9         | 14.75%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 55        | 90.16%  |
| Yes       | 6         | 9.84%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Purism              | 14        | 22.95%  |
| Apple               | 8         | 13.11%  |
| Lenovo              | 7         | 11.48%  |
| Dell                | 6         | 9.84%   |
| Hewlett-Packard     | 4         | 6.56%   |
| ASUSTek Computer    | 3         | 4.92%   |
| Unknown             | 3         | 4.92%   |
| Pine Microsystems   | 2         | 3.28%   |
| Gigabyte Technology | 2         | 3.28%   |
| Acer                | 2         | 3.28%   |
| Toshiba             | 1         | 1.64%   |
| Shuttle             | 1         | 1.64%   |
| Samsung Electronics | 1         | 1.64%   |
| PCWare              | 1         | 1.64%   |
| Notebook            | 1         | 1.64%   |
| MSI                 | 1         | 1.64%   |
| Microsoft           | 1         | 1.64%   |
| LG Electronics      | 1         | 1.64%   |
| HUAWEI              | 1         | 1.64%   |
| Google              | 1         | 1.64%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Purism Librem 14                         | 6         | 9.84%   |
| Unknown                                  | 3         | 4.92%   |
| Purism Librem 15 v4                      | 2         | 3.28%   |
| HP Pavilion g6                           | 2         | 3.28%   |
| Toshiba Satellite L500D                  | 1         | 1.64%   |
| Shuttle DS10U                            | 1         | 1.64%   |
| Samsung 530U3C/530U4C/532U3C             | 1         | 1.64%   |
| Purism librem_mini_v2                    | 1         | 1.64%   |
| Purism Librem 5r4                        | 1         | 1.64%   |
| Purism Librem 5                          | 1         | 1.64%   |
| Purism Librem 15 v3                      | 1         | 1.64%   |
| Purism Librem 13 v4                      | 1         | 1.64%   |
| Purism Librem 13 v2                      | 1         | 1.64%   |
| Pine Microsystems Pine64 PinePhone (1.2) | 1         | 1.64%   |
| Pine Microsystems Pine64 Pinebook Pro    | 1         | 1.64%   |
| PCWare IPX4005G                          | 1         | 1.64%   |
| Notebook P17SM                           | 1         | 1.64%   |
| MSI MS-7788                              | 1         | 1.64%   |
| Microsoft Surface Book 2                 | 1         | 1.64%   |
| LG 22V280-L.BY31P1                       | 1         | 1.64%   |
| Lenovo ThinkPad T540p 20BFS23T00         | 1         | 1.64%   |
| Lenovo ThinkPad T440p                    | 1         | 1.64%   |
| Lenovo ThinkPad T440 20B60044RT          | 1         | 1.64%   |
| Lenovo ThinkPad E480 20KN003SUS          | 1         | 1.64%   |
| Lenovo ThinkPad 13 2nd Gen 20J2S00G00    | 1         | 1.64%   |
| Lenovo IdeaPad U430 Touch 20270          | 1         | 1.64%   |
| Lenovo B50-70 20384                      | 1         | 1.64%   |
| HUAWEI NBLB-WAX9N                        | 1         | 1.64%   |
| HP Spectre x360 Convertible              | 1         | 1.64%   |
| HP Pavilion Notebook                     | 1         | 1.64%   |
| Google Droid                             | 1         | 1.64%   |
| Gigabyte GA-MA78GM-UD2H                  | 1         | 1.64%   |
| Gigabyte B85M-DS3H                       | 1         | 1.64%   |
| Dell XPS 13 9370                         | 1         | 1.64%   |
| Dell OptiPlex 760                        | 1         | 1.64%   |
| Dell Latitude D430                       | 1         | 1.64%   |
| Dell Inspiron 5547                       | 1         | 1.64%   |
| Dell Inspiron 3847                       | 1         | 1.64%   |
| Dell Inspiron 15-3567                    | 1         | 1.64%   |
| ASUS M4N68T V2                           | 1         | 1.64%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Purism Librem            | 14        | 22.95%  |
| Lenovo ThinkPad          | 5         | 8.2%    |
| HP Pavilion              | 3         | 4.92%   |
| Dell Inspiron            | 3         | 4.92%   |
| Unknown                  | 3         | 4.92%   |
| Pine Microsystems Pine64 | 2         | 3.28%   |
| Toshiba Satellite        | 1         | 1.64%   |
| Shuttle DS10U            | 1         | 1.64%   |
| Samsung 530U3C           | 1         | 1.64%   |
| PCWare IPX4005G          | 1         | 1.64%   |
| Notebook P17SM           | 1         | 1.64%   |
| MSI MS-7788              | 1         | 1.64%   |
| Microsoft Surface        | 1         | 1.64%   |
| LG 22V280-L.BY31P1       | 1         | 1.64%   |
| Lenovo IdeaPad           | 1         | 1.64%   |
| Lenovo B50-70            | 1         | 1.64%   |
| HUAWEI NBLB-WAX9N        | 1         | 1.64%   |
| HP Spectre               | 1         | 1.64%   |
| Google Droid             | 1         | 1.64%   |
| Gigabyte GA-MA78GM-UD2H  | 1         | 1.64%   |
| Gigabyte B85M-DS3H       | 1         | 1.64%   |
| Dell XPS                 | 1         | 1.64%   |
| Dell OptiPlex            | 1         | 1.64%   |
| Dell Latitude            | 1         | 1.64%   |
| ASUS M4N68T              | 1         | 1.64%   |
| ASUS EX-A320M-GAMING     | 1         | 1.64%   |
| ASUS A88X-PLUS           | 1         | 1.64%   |
| Apple Macmini6           | 1         | 1.64%   |
| Apple MacBookPro6        | 1         | 1.64%   |
| Apple MacBookPro14       | 1         | 1.64%   |
| Apple MacBookAir7        | 1         | 1.64%   |
| Apple MacBook9           | 1         | 1.64%   |
| Apple iMac7              | 1         | 1.64%   |
| Apple iMac13             | 1         | 1.64%   |
| Apple iMac11             | 1         | 1.64%   |
| Acer Swift               | 1         | 1.64%   |
| Acer Nitro               | 1         | 1.64%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 9         | 14.75%  |
| 2013    | 7         | 11.48%  |
| 2021    | 6         | 9.84%   |
| 2019    | 5         | 8.2%    |
| 2018    | 5         | 8.2%    |
| 2017    | 5         | 8.2%    |
| 2015    | 4         | 6.56%   |
| 2020    | 3         | 4.92%   |
| 2014    | 3         | 4.92%   |
| 2011    | 3         | 4.92%   |
| 2016    | 2         | 3.28%   |
| 2012    | 2         | 3.28%   |
| 2010    | 2         | 3.28%   |
| 2009    | 2         | 3.28%   |
| 2007    | 2         | 3.28%   |
| 2023    | 1         | 1.64%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 39        | 63.93%  |
| Desktop        | 11        | 18.03%  |
| All in one     | 4         | 6.56%   |
| System on chip | 3         | 4.92%   |
| Phone          | 1         | 1.64%   |
| Tablet         | 1         | 1.64%   |
| Convertible    | 1         | 1.64%   |
| Mini pc        | 1         | 1.64%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 61        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 47        | 77.05%  |
| Yes  | 14        | 22.95%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 13        | 21.31%  |
| 16.01-24.0 | 13        | 21.31%  |
| 8.01-16.0  | 13        | 21.31%  |
| 4.01-8.0   | 11        | 18.03%  |
| 32.01-64.0 | 6         | 9.84%   |
| 2.01-3.0   | 2         | 3.28%   |
| 1.01-2.0   | 2         | 3.28%   |
| 24.01-32.0 | 1         | 1.64%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 20        | 29.85%  |
| 1.01-2.0  | 17        | 25.37%  |
| 3.01-4.0  | 14        | 20.9%   |
| 4.01-8.0  | 12        | 17.91%  |
| 8.01-16.0 | 2         | 2.99%   |
| 0.51-1.0  | 1         | 1.49%   |
| 0.01-0.5  | 1         | 1.49%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 42        | 67.74%  |
| 2      | 15        | 24.19%  |
| 0      | 3         | 4.84%   |
| 5      | 1         | 1.61%   |
| 3      | 1         | 1.61%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 49        | 80.33%  |
| Yes       | 12        | 19.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 77.05%  |
| No        | 14        | 22.95%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 77.05%  |
| No        | 14        | 22.95%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 62.3%   |
| No        | 23        | 37.7%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 14        | 22.22%  |
| Germany                | 8         | 12.7%   |
| UK                     | 6         | 9.52%   |
| Brazil                 | 6         | 9.52%   |
| Russia                 | 3         | 4.76%   |
| Poland                 | 3         | 4.76%   |
| Italy                  | 3         | 4.76%   |
| Canada                 | 3         | 4.76%   |
| Australia              | 3         | 4.76%   |
| France                 | 2         | 3.17%   |
| Turkey                 | 1         | 1.59%   |
| South Africa           | 1         | 1.59%   |
| Portugal               | 1         | 1.59%   |
| Paraguay               | 1         | 1.59%   |
| Martinique             | 1         | 1.59%   |
| Israel                 | 1         | 1.59%   |
| Iran                   | 1         | 1.59%   |
| Greece                 | 1         | 1.59%   |
| Costa Rica             | 1         | 1.59%   |
| China                  | 1         | 1.59%   |
| Bulgaria               | 1         | 1.59%   |
| Bosnia and Herzegovina | 1         | 1.59%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Stuttgart      | 3         | 4.62%   |
| Porto Alegre   | 3         | 4.62%   |
| Warsaw         | 2         | 3.08%   |
| New York       | 2         | 3.08%   |
| London         | 2         | 3.08%   |
| Berlin         | 2         | 3.08%   |
| Yuzhnoural'sk  | 1         | 1.54%   |
| Wixom          | 1         | 1.54%   |
| Windsor        | 1         | 1.54%   |
| Vista          | 1         | 1.54%   |
| Vancouver      | 1         | 1.54%   |
| Troy           | 1         | 1.54%   |
| Tomsk          | 1         | 1.54%   |
| Thorpe Hamlet  | 1         | 1.54%   |
| Tel Aviv       | 1         | 1.54%   |
| Stargard       | 1         | 1.54%   |
| Spencer        | 1         | 1.54%   |
| Sofia          | 1         | 1.54%   |
| Seattle        | 1         | 1.54%   |
| Sao Paulo      | 1         | 1.54%   |
| San Jose       | 1         | 1.54%   |
| Perth          | 1         | 1.54%   |
| Paris          | 1         | 1.54%   |
| Montreal       | 1         | 1.54%   |
| Milwaukee      | 1         | 1.54%   |
| Milpitas       | 1         | 1.54%   |
| Milan          | 1         | 1.54%   |
| Melbourne      | 1         | 1.54%   |
| Mankato        | 1         | 1.54%   |
| Liverpool      | 1         | 1.54%   |
| Lenningen      | 1         | 1.54%   |
| Leeds          | 1         | 1.54%   |
| Lambeth        | 1         | 1.54%   |
| Krasnogorsk    | 1         | 1.54%   |
| Istanbul       | 1         | 1.54%   |
| Hernandarias   | 1         | 1.54%   |
| Guimaraes      | 1         | 1.54%   |
| Grasse         | 1         | 1.54%   |
| Genoa          | 1         | 1.54%   |
| Fort-de-France | 1         | 1.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 22     | 23.94%  |
| Unknown             | 8         | 12     | 11.27%  |
| Seagate             | 7         | 12     | 9.86%   |
| Apple               | 6         | 8      | 8.45%   |
| WDC                 | 5         | 6      | 7.04%   |
| SanDisk             | 4         | 4      | 5.63%   |
| HGST                | 3         | 3      | 4.23%   |
| A-DATA Technology   | 3         | 4      | 4.23%   |
| Crucial             | 2         | 4      | 2.82%   |
| Win Memory          | 1         | 1      | 1.41%   |
| Transcend           | 1         | 1      | 1.41%   |
| Toshiba             | 1         | 1      | 1.41%   |
| PNY                 | 1         | 1      | 1.41%   |
| Plextor             | 1         | 1      | 1.41%   |
| Phison              | 1         | 1      | 1.41%   |
| Patriot             | 1         | 1      | 1.41%   |
| Mushkin             | 1         | 1      | 1.41%   |
| Kingston            | 1         | 1      | 1.41%   |
| JMicron Technology  | 1         | 1      | 1.41%   |
| Intenso             | 1         | 2      | 1.41%   |
| Intel               | 1         | 1      | 1.41%   |
| Hitachi             | 1         | 1      | 1.41%   |
| BIWIN               | 1         | 1      | 1.41%   |
| ASMT                | 1         | 2      | 1.41%   |
| ADATA Technology    | 1         | 1      | 1.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Unknown MMC Card  64GB            | 2         | 2.53%   |
| Unknown MMC Card  32GB            | 2         | 2.53%   |
| Seagate ST1000LM048-2E7172 1TB    | 2         | 2.53%   |
| Samsung SSD 970 PRO 1TB           | 2         | 2.53%   |
| Samsung SSD 860 EVO 250GB         | 2         | 2.53%   |
| Win Memory SWR256G-201II 256GB    | 1         | 1.27%   |
| WDC WDS500G2B0A-00SM50 500GB SSD  | 1         | 1.27%   |
| WDC WDS100T2B0C-00PXH0 1TB        | 1         | 1.27%   |
| WDC WDBNCE2500PNC 250GB SSD       | 1         | 1.27%   |
| WDC WD5000AZRX-00A8LB0 500GB      | 1         | 1.27%   |
| WDC WD3200AAJS-40RYA0 320GB       | 1         | 1.27%   |
| Unknown SH64G  64GB               | 1         | 1.27%   |
| Unknown MMC Card  16GB            | 1         | 1.27%   |
| Unknown DA4128  128GB             | 1         | 1.27%   |
| Unknown AFGCF  128GB              | 1         | 1.27%   |
| Unknown 8GTF4R  8GB               | 1         | 1.27%   |
| Unknown 032G32  32GB              | 1         | 1.27%   |
| Transcend TS240GMTS420S 240GB SSD | 1         | 1.27%   |
| Toshiba NVMe SSD Drive 512GB      | 1         | 1.27%   |
| Seagate ST480HM000-1G5162 480GB   | 1         | 1.27%   |
| Seagate ST3320418AS 320GB         | 1         | 1.27%   |
| Seagate ST3250410AS 250GB         | 1         | 1.27%   |
| Seagate ST3250312CS 250GB         | 1         | 1.27%   |
| Seagate ST31000524AS 1TB          | 1         | 1.27%   |
| Seagate ST1000DM003-1ER162 1TB    | 1         | 1.27%   |
| Seagate NVMe SSD Drive 2TB        | 1         | 1.27%   |
| SanDisk SSD i100 24GB             | 1         | 1.27%   |
| SanDisk SDSSDP128G 128GB          | 1         | 1.27%   |
| SanDisk SDSSDH3500G 500GB         | 1         | 1.27%   |
| SanDisk NVMe SSD Drive 500GB      | 1         | 1.27%   |
| Samsung SSD 970 EVO Plus 500GB    | 1         | 1.27%   |
| Samsung SSD 970 EVO Plus 2TB      | 1         | 1.27%   |
| Samsung SSD 970 EVO 250GB         | 1         | 1.27%   |
| Samsung SSD 960 EVO 500GB         | 1         | 1.27%   |
| Samsung SSD 960 EVO 250GB         | 1         | 1.27%   |
| Samsung SSD 860 EVO M.2 250GB     | 1         | 1.27%   |
| Samsung SSD 860 EVO 500GB         | 1         | 1.27%   |
| Samsung SSD 860 EVO 1TB           | 1         | 1.27%   |
| Samsung SSD 850 EVO 500GB         | 1         | 1.27%   |
| Samsung SSD 850 EVO 250GB         | 1         | 1.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 11     | 35.29%  |
| HGST                | 3         | 3      | 17.65%  |
| Apple               | 3         | 3      | 17.65%  |
| WDC                 | 2         | 2      | 11.76%  |
| Samsung Electronics | 1         | 1      | 5.88%   |
| Hitachi             | 1         | 1      | 5.88%   |
| ASMT                | 1         | 2      | 5.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


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
| Kingston            | 1         | 1      | 3.45%   |
| Intenso             | 1         | 2      | 3.45%   |
| Intel               | 1         | 1      | 3.45%   |
| BIWIN               | 1         | 1      | 3.45%   |
| Apple               | 1         | 1      | 3.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 26        | 37     | 38.24%  |
| NVMe | 18        | 21     | 26.47%  |
| HDD  | 16        | 23     | 23.53%  |
| MMC  | 8         | 12     | 11.76%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 37        | 57     | 56.92%  |
| NVMe | 17        | 20     | 26.15%  |
| MMC  | 8         | 12     | 12.31%  |
| SAS  | 3         | 4      | 4.62%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 29        | 46     | 72.5%   |
| 0.51-1.0   | 9         | 11     | 22.5%   |
| 1.01-2.0   | 2         | 3      | 5%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 27        | 42.86%  |
| 101-250    | 8         | 12.7%   |
| 251-500    | 7         | 11.11%  |
| 21-50      | 5         | 7.94%   |
| 51-100     | 5         | 7.94%   |
| 501-1000   | 4         | 6.35%   |
| 1001-2000  | 3         | 4.76%   |
| Unknown    | 3         | 4.76%   |
| 2001-3000  | 1         | 1.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 40        | 63.49%  |
| 21-50    | 12        | 19.05%  |
| 101-250  | 3         | 4.76%   |
| 501-1000 | 3         | 4.76%   |
| Unknown  | 3         | 4.76%   |
| 251-500  | 1         | 1.59%   |
| 51-100   | 1         | 1.59%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                      | Computers | Drives | Percent |
|----------------------------|-----------|--------|---------|
| Seagate ST3250410AS 250GB  | 1         | 1      | 20%     |
| Seagate ST3250312CS 250GB  | 1         | 1      | 20%     |
| Seagate ST31000524AS 1TB   | 1         | 1      | 20%     |
| Intel SSDSC2BF180A4H 180GB | 1         | 1      | 20%     |
| Apple HDD ST1000LM024 1TB  | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 3      | 50%     |
| Intel   | 1         | 1      | 25%     |
| Apple   | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 3      | 66.67%  |
| Apple   | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 4      | 75%     |
| SSD  | 1         | 1      | 25%     |

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
| Detected | 41        | 64     | 65.08%  |
| Works    | 18        | 24     | 28.57%  |
| Malfunc  | 4         | 5      | 6.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 34        | 58.62%  |
| Samsung Electronics          | 10        | 17.24%  |
| AMD                          | 5         | 8.62%   |
| SanDisk                      | 2         | 3.45%   |
| Apple                        | 2         | 3.45%   |
| Toshiba America Info Systems | 1         | 1.72%   |
| Seagate Technology           | 1         | 1.72%   |
| Phison Electronics           | 1         | 1.72%   |
| Nvidia                       | 1         | 1.72%   |
| ADATA Technology             | 1         | 1.72%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 11.29%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 6         | 9.68%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 8.06%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 4.84%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 4.84%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 4.84%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 3         | 4.84%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 3.23%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 3.23%   |
| Apple S3X NVMe Controller                                                      | 2         | 3.23%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 1.61%   |
| Seagate FireCuda 510 SSD                                                       | 1         | 1.61%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 1         | 1.61%   |
| SanDisk Non-Volatile memory controller                                         | 1         | 1.61%   |
| Samsung Electronics SATA controller                                            | 1         | 1.61%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 1.61%   |
| Nvidia MCP61 SATA Controller                                                   | 1         | 1.61%   |
| Nvidia MCP61 IDE                                                               | 1         | 1.61%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.61%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.61%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 1.61%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.61%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 1         | 1.61%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 1         | 1.61%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 1         | 1.61%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 1.61%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1         | 1.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 1.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1         | 1.61%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 1.61%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.61%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 1         | 1.61%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 1.61%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 1         | 1.61%   |
| AMD FCH SATA Controller D                                                      | 1         | 1.61%   |
| ADATA Non-Volatile memory controller                                           | 1         | 1.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 38        | 64.41%  |
| NVMe | 17        | 28.81%  |
| IDE  | 4         | 6.78%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 48        | 77.42%  |
| ARM     | 6         | 9.68%   |
| AMD     | 6         | 9.68%   |
| Unknown | 2         | 3.23%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Core i7-10710U CPU @ 1.10GHz       | 6         | 9.68%   |
| ARM Processor                            | 6         | 9.68%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 4         | 6.45%   |
| Intel Core i7-6500U CPU @ 2.50GHz        | 2         | 3.23%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 2         | 3.23%   |
|                                          | 2         | 3.23%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz | 1         | 1.61%   |
| Intel Pentium CPU N4200 @ 1.10GHz        | 1         | 1.61%   |
| Intel Core m5-6Y54 CPU @ 1.10GHz         | 1         | 1.61%   |
| Intel Core i7-8650U CPU @ 1.90GHz        | 1         | 1.61%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 1         | 1.61%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz       | 1         | 1.61%   |
| Intel Core i7-7567U CPU @ 3.50GHz        | 1         | 1.61%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz       | 1         | 1.61%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz       | 1         | 1.61%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz       | 1         | 1.61%   |
| Intel Core i7-4510U CPU @ 2.00GHz        | 1         | 1.61%   |
| Intel Core i7-10510U CPU @ 1.80GHz       | 1         | 1.61%   |
| Intel Core i5-5250U CPU @ 1.60GHz        | 1         | 1.61%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 1         | 1.61%   |
| Intel Core i5-4460 CPU @ 3.20GHz         | 1         | 1.61%   |
| Intel Core i5-4210U CPU @ 1.70GHz        | 1         | 1.61%   |
| Intel Core i5-4200U CPU @ 1.60GHz        | 1         | 1.61%   |
| Intel Core i5-3330S CPU @ 2.70GHz        | 1         | 1.61%   |
| Intel Core i5-3210M CPU @ 2.50GHz        | 1         | 1.61%   |
| Intel Core i5-2320 CPU @ 3.00GHz         | 1         | 1.61%   |
| Intel Core i5-10210U CPU @ 1.60GHz       | 1         | 1.61%   |
| Intel Core i5 CPU M 540 @ 2.53GHz        | 1         | 1.61%   |
| Intel Core i5 CPU 750 @ 2.67GHz          | 1         | 1.61%   |
| Intel Core i3-4130T CPU @ 2.90GHz        | 1         | 1.61%   |
| Intel Core i3-4010U CPU @ 1.70GHz        | 1         | 1.61%   |
| Intel Core i3-3217U CPU @ 1.80GHz        | 1         | 1.61%   |
| Intel Core i3-3120M CPU @ 2.50GHz        | 1         | 1.61%   |
| Intel Core i3-2330M CPU @ 2.20GHz        | 1         | 1.61%   |
| Intel Core 2 Duo CPU U7700 @ 1.33GHz     | 1         | 1.61%   |
| Intel Core 2 Duo CPU T7700 @ 2.40GHz     | 1         | 1.61%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz     | 1         | 1.61%   |
| Intel Celeron N4100 CPU @ 1.10GHz        | 1         | 1.61%   |
| Intel Celeron J4005 CPU @ 2.00GHz        | 1         | 1.61%   |
| Intel Celeron CPU 4205U @ 1.80GHz        | 1         | 1.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 21        | 34.43%  |
| Intel Core i5           | 13        | 21.31%  |
| Other                   | 7         | 11.48%  |
| Intel Core i3           | 5         | 8.2%    |
| Intel Core 2 Duo        | 3         | 4.92%   |
| Intel Celeron           | 3         | 4.92%   |
| Intel Pentium Silver    | 1         | 1.64%   |
| Intel Pentium           | 1         | 1.64%   |
| Intel Core m5           | 1         | 1.64%   |
| AMD Turion II Dual-Core | 1         | 1.64%   |
| AMD Ryzen 5             | 1         | 1.64%   |
| AMD Ryzen 3             | 1         | 1.64%   |
| AMD Athlon II X4        | 1         | 1.64%   |
| AMD Athlon II X3        | 1         | 1.64%   |
| AMD A10                 | 1         | 1.64%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 29        | 47.54%  |
| 4       | 24        | 39.34%  |
| 6       | 6         | 9.84%   |
| 3       | 1         | 1.64%   |
| Unknown | 1         | 1.64%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 60        | 98.36%  |
| Unknown | 1         | 1.64%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 38        | 62.3%   |
| 1       | 22        | 36.07%  |
| Unknown | 1         | 1.64%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 57        | 91.94%  |
| Unknown        | 4         | 6.45%   |
| 64-bit         | 1         | 1.61%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 44        | 69.84%  |
| 0xa0660    | 3         | 4.76%   |
| 0x406e3    | 3         | 4.76%   |
| 0x706a1    | 2         | 3.17%   |
| 0x40651    | 2         | 3.17%   |
| 0x806ec    | 1         | 1.59%   |
| 0x806ea    | 1         | 1.59%   |
| 0x806e9    | 1         | 1.59%   |
| 0x306d4    | 1         | 1.59%   |
| 0x206a7    | 1         | 1.59%   |
| 0x1067a    | 1         | 1.59%   |
| 0x08108109 | 1         | 1.59%   |
| 0x06003106 | 1         | 1.59%   |
| 0x010000b6 | 1         | 1.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 13        | 21.31%  |
| Haswell       | 9         | 14.75%  |
| Unknown       | 7         | 11.48%  |
| CometLake     | 6         | 9.84%   |
| IvyBridge     | 4         | 6.56%   |
| Skylake       | 3         | 4.92%   |
| K10           | 3         | 4.92%   |
| Goldmont plus | 3         | 4.92%   |
| Zen+          | 2         | 3.28%   |
| SandyBridge   | 2         | 3.28%   |
| Core          | 2         | 3.28%   |
| Broadwell     | 2         | 3.28%   |
| Westmere      | 1         | 1.64%   |
| Steamroller   | 1         | 1.64%   |
| Penryn        | 1         | 1.64%   |
| Nehalem       | 1         | 1.64%   |
| Goldmont      | 1         | 1.64%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 44        | 70.97%  |
| Nvidia | 9         | 14.52%  |
| AMD    | 9         | 14.52%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                 | 6         | 9.23%   |
| Intel Comet Lake UHD Graphics                                                         | 6         | 9.23%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 4         | 6.15%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 3         | 4.62%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 3         | 4.62%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 2         | 3.08%   |
| Intel UHD Graphics 620                                                                | 2         | 3.08%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 2         | 3.08%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 2         | 3.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 2         | 3.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 2         | 3.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 2         | 3.08%   |
| Nvidia TU116 [GeForce GTX 1660]                                                       | 1         | 1.54%   |
| Nvidia GT216M [GeForce GT 330M]                                                       | 1         | 1.54%   |
| Nvidia GK208M [GeForce GT 730M]                                                       | 1         | 1.54%   |
| Nvidia GK208B [GeForce GT 710]                                                        | 1         | 1.54%   |
| Nvidia GK107M [GeForce GT 640M Mac Edition]                                           | 1         | 1.54%   |
| Nvidia GK104M [GeForce GTX 870M]                                                      | 1         | 1.54%   |
| Nvidia GF116 [GeForce GTS 450 Rev. 2]                                                 | 1         | 1.54%   |
| Nvidia GF108 [GeForce GT 630]                                                         | 1         | 1.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 1         | 1.54%   |
| Intel Whiskey Lake-U GT1 [UHD Graphics 610]                                           | 1         | 1.54%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller         | 1         | 1.54%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller             | 1         | 1.54%   |
| Intel Iris Plus Graphics 650                                                          | 1         | 1.54%   |
| Intel HD Graphics 630                                                                 | 1         | 1.54%   |
| Intel HD Graphics 6000                                                                | 1         | 1.54%   |
| Intel HD Graphics 5500                                                                | 1         | 1.54%   |
| Intel HD Graphics 515                                                                 | 1         | 1.54%   |
| Intel GeminiLake [UHD Graphics 605]                                                   | 1         | 1.54%   |
| Intel Core Processor Integrated Graphics Controller                                   | 1         | 1.54%   |
| Intel Apollo Lake [HD Graphics 505]                                                   | 1         | 1.54%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                 | 1         | 1.54%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 1.54%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                             | 1         | 1.54%   |
| AMD RV770/M98L [Mobility Radeon HD 4850]                                              | 1         | 1.54%   |
| AMD RV710 [Radeon HD 4350/4550]                                                       | 1         | 1.54%   |
| AMD RV630/M76 [Mobility Radeon HD 2600 XT/2700]                                       | 1         | 1.54%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                             | 1         | 1.54%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                                    | 1         | 1.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 35        | 57.38%  |
| Other          | 8         | 13.11%  |
| 1 x AMD        | 6         | 9.84%   |
| Intel + Nvidia | 5         | 8.2%    |
| 1 x Nvidia     | 4         | 6.56%   |
| Intel + AMD    | 2         | 3.28%   |
| 2 x AMD        | 1         | 1.64%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 51        | 83.61%  |
| Unknown | 10        | 16.39%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 59        | 95.16%  |
| 3.01-4.0   | 1         | 1.61%   |
| 1.01-2.0   | 1         | 1.61%   |
| 0.51-1.0   | 1         | 1.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 9         | 14.75%  |
| Samsung Electronics     | 8         | 13.11%  |
| BOE                     | 7         | 11.48%  |
| LG Display              | 6         | 9.84%   |
| Apple                   | 6         | 9.84%   |
| Goldstar                | 3         | 4.92%   |
| Philips                 | 2         | 3.28%   |
| AU Optronics            | 2         | 3.28%   |
| Unknown                 | 1         | 1.64%   |
| Toshiba                 | 1         | 1.64%   |
| Sony                    | 1         | 1.64%   |
| Sharp                   | 1         | 1.64%   |
| RTK                     | 1         | 1.64%   |
| PRI                     | 1         | 1.64%   |
| PANDA                   | 1         | 1.64%   |
| Panasonic               | 1         | 1.64%   |
| Lenovo                  | 1         | 1.64%   |
| Iiyama                  | 1         | 1.64%   |
| Grundig                 | 1         | 1.64%   |
| Flipbook                | 1         | 1.64%   |
| Dell                    | 1         | 1.64%   |
| Chi Mei Optoelectronics | 1         | 1.64%   |
| BenQ                    | 1         | 1.64%   |
| ASUSTek Computer        | 1         | 1.64%   |
| AOC                     | 1         | 1.64%   |
| Acer                    | 1         | 1.64%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC434B 3840x2160 344x194mm 15.5-inch     | 3         | 4.92%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 3         | 4.92%   |
| Philips TV PHL5035 1920x1080 640x360mm 28.9-inch                          | 2         | 3.28%   |
| Chimei Innolux LCD Monitor CMN1415 1920x1080 309x173mm 13.9-inch          | 2         | 3.28%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 1         | 1.64%   |
| Toshiba LCD Monitor LCD3706 1280x800 261x163mm 12.1-inch                  | 1         | 1.64%   |
| Sony TV SNYAB03 1920x1080                                                 | 1         | 1.64%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                   | 1         | 1.64%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 474x296mm 22.0-inch      | 1         | 1.64%   |
| Samsung Electronics SyncMaster SAM01D3 1440x900 408x225mm 18.3-inch       | 1         | 1.64%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch      | 1         | 1.64%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 410x230mm 18.5-inch      | 1         | 1.64%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 1         | 1.64%   |
| RTK LG AIO FHD RTK2136 1920x1080 477x268mm 21.5-inch                      | 1         | 1.64%   |
| PRI Prima TV PRI1600 1920x1080                                            | 1         | 1.64%   |
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch                   | 1         | 1.64%   |
| Panasonic VVX14T092N00 MEI96A2 2256x1504 285x190mm 13.5-inch              | 1         | 1.64%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch              | 1         | 1.64%   |
| LG Display LCD Monitor LGD053B 1920x1080 294x165mm 13.3-inch              | 1         | 1.64%   |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch              | 1         | 1.64%   |
| LG Display LCD Monitor LGD03F0 1366x768 310x174mm 14.0-inch               | 1         | 1.64%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch               | 1         | 1.64%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch               | 1         | 1.64%   |
| Lenovo LEN Y44w-10 LEN65EA 3840x1200 1052x329mm 43.4-inch                 | 1         | 1.64%   |
| Iiyama PL2792H IVM664F 1920x1080 598x336mm 27.0-inch                      | 1         | 1.64%   |
| Grundig WUXGA GRU4448 1920x1080                                           | 1         | 1.64%   |
| Goldstar IPS231 GSM5817 1920x1080 510x290mm 23.1-inch                     | 1         | 1.64%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch                 | 1         | 1.64%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                    | 1         | 1.64%   |
| Flipbook NexDock YUKBC34 1920x1080 290x170mm 13.2-inch                    | 1         | 1.64%   |
| Dell P2213 DELF042 1680x1050 470x300mm 22.0-inch                          | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch          | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN15BD 1366x768 344x194mm 15.5-inch           | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch           | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN1365 1920x1080 293x165mm 13.2-inch          | 1         | 1.64%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 1.64%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                     | 1         | 1.64%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                     | 1         | 1.64%   |
| BOE LCD Monitor BOE079A 1920x1080 309x173mm 13.9-inch                     | 1         | 1.64%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                      | 1         | 1.64%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 28        | 49.12%  |
| 1366x768 (WXGA)    | 9         | 15.79%  |
| 3840x2160 (4K)     | 7         | 12.28%  |
| 1680x1050 (WSXGA+) | 3         | 5.26%   |
| 1600x900 (HD+)     | 2         | 3.51%   |
| 1440x900 (WXGA+)   | 2         | 3.51%   |
| 3840x1200          | 1         | 1.75%   |
| 2880x1800          | 1         | 1.75%   |
| 2304x1440          | 1         | 1.75%   |
| 2288x1287          | 1         | 1.75%   |
| 1920x1200 (WUXGA)  | 1         | 1.75%   |
| 1280x800 (WXGA)    | 1         | 1.75%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 17        | 27.87%  |
| 15      | 13        | 21.31%  |
| 23      | 3         | 4.92%   |
| 21      | 3         | 4.92%   |
| 17      | 3         | 4.92%   |
| 14      | 3         | 4.92%   |
| 28      | 2         | 3.28%   |
| 24      | 2         | 3.28%   |
| 22      | 2         | 3.28%   |
| 20      | 2         | 3.28%   |
| 12      | 2         | 3.28%   |
| 142     | 1         | 1.64%   |
| 72      | 1         | 1.64%   |
| 54      | 1         | 1.64%   |
| 43      | 1         | 1.64%   |
| 40      | 1         | 1.64%   |
| 31      | 1         | 1.64%   |
| 27      | 1         | 1.64%   |
| 19      | 1         | 1.64%   |
| Unknown | 1         | 1.64%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 23        | 38.33%  |
| 201-300        | 10        | 16.67%  |
| 401-500        | 8         | 13.33%  |
| 501-600        | 6         | 10%     |
| 351-400        | 4         | 6.67%   |
| 601-700        | 3         | 5%      |
| 1001-1500      | 2         | 3.33%   |
| More than 2000 | 1         | 1.67%   |
| 801-900        | 1         | 1.67%   |
| 1501-2000      | 1         | 1.67%   |
| Unknown        | 1         | 1.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 42        | 79.25%  |
| 16/10 | 9         | 16.98%  |
| 3.20  | 1         | 1.89%   |
| 1.00  | 1         | 1.89%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 13        | 21.31%  |
| 101-110        | 13        | 21.31%  |
| 201-250        | 10        | 16.39%  |
| 71-80          | 7         | 11.48%  |
| More than 1000 | 3         | 4.92%   |
| 351-500        | 3         | 4.92%   |
| 151-200        | 3         | 4.92%   |
| 61-70          | 2         | 3.28%   |
| 121-130        | 2         | 3.28%   |
| 501-1000       | 2         | 3.28%   |
| 301-350        | 1         | 1.64%   |
| 131-140        | 1         | 1.64%   |
| Unknown        | 1         | 1.64%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 17        | 27.87%  |
| 51-100        | 17        | 27.87%  |
| 101-120       | 10        | 16.39%  |
| More than 240 | 7         | 11.48%  |
| 161-240       | 6         | 9.84%   |
| 1-50          | 3         | 4.92%   |
| Unknown       | 1         | 1.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 44        | 72.13%  |
| 2     | 8         | 13.11%  |
| 0     | 8         | 13.11%  |
| 3     | 1         | 1.64%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 34        | 36.96%  |
| Qualcomm Atheros                | 17        | 18.48%  |
| Intel                           | 15        | 16.3%   |
| Broadcom                        | 9         | 9.78%   |
| Broadcom Limited                | 4         | 4.35%   |
| Qualcomm Atheros Communications | 2         | 2.17%   |
| Marvell Technology Group        | 2         | 2.17%   |
| ASIX Electronics                | 2         | 2.17%   |
| Samsung Electronics             | 1         | 1.09%   |
| Ralink                          | 1         | 1.09%   |
| OPPO Electronics                | 1         | 1.09%   |
| Nvidia                          | 1         | 1.09%   |
| MediaTek                        | 1         | 1.09%   |
| Edimax Technology               | 1         | 1.09%   |
| ASUSTek Computer                | 1         | 1.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 22        | 21.57%  |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 12        | 11.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 5         | 4.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 4         | 3.92%   |
| Intel Wireless 7265                                                           | 4         | 3.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 3         | 2.94%   |
| Intel Wireless 7260                                                           | 3         | 2.94%   |
| Qualcomm Atheros AR9271 802.11n                                               | 2         | 1.96%   |
| Intel Ethernet Connection I217-LM                                             | 2         | 1.96%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 2         | 1.96%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2         | 1.96%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                    | 2         | 1.96%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 2         | 1.96%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1         | 0.98%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1         | 0.98%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 0.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.98%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 1         | 0.98%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1         | 0.98%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 0.98%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1         | 0.98%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                        | 1         | 0.98%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 0.98%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 0.98%   |
| OPPO CPH2411                                                                  | 1         | 0.98%   |
| Nvidia MCP61 Ethernet                                                         | 1         | 0.98%   |
| MediaTek WiFi                                                                 | 1         | 0.98%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                             | 1         | 0.98%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                       | 1         | 0.98%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 0.98%   |
| Intel I211 Gigabit Network Connection                                         | 1         | 0.98%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1         | 0.98%   |
| Intel Ethernet Connection I218-V                                              | 1         | 0.98%   |
| Intel Ethernet Connection (6) I219-LM                                         | 1         | 0.98%   |
| Intel Ethernet Connection (4) I219-V                                          | 1         | 0.98%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 0.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 1         | 0.98%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 0.98%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1         | 0.98%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                                   | 1         | 0.98%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 17        | 32.08%  |
| Intel                           | 12        | 22.64%  |
| Realtek Semiconductor           | 7         | 13.21%  |
| Broadcom                        | 6         | 11.32%  |
| Broadcom Limited                | 4         | 7.55%   |
| Qualcomm Atheros Communications | 2         | 3.77%   |
| Ralink                          | 1         | 1.89%   |
| MediaTek                        | 1         | 1.89%   |
| Marvell Technology Group        | 1         | 1.89%   |
| Edimax Technology               | 1         | 1.89%   |
| ASUSTek Computer                | 1         | 1.89%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 12        | 22.64%  |
| Intel Wireless 7265                                                           | 4         | 7.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 3         | 5.66%   |
| Intel Wireless 7260                                                           | 3         | 5.66%   |
| Qualcomm Atheros AR9271 802.11n                                               | 2         | 3.77%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                    | 2         | 3.77%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1         | 1.89%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 1.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.89%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 1         | 1.89%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1         | 1.89%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 1.89%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1         | 1.89%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                        | 1         | 1.89%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 1.89%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.89%   |
| MediaTek WiFi                                                                 | 1         | 1.89%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                             | 1         | 1.89%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 1.89%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1         | 1.89%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 1.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 1         | 1.89%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 1.89%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                                   | 1         | 1.89%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                                        | 1         | 1.89%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                        | 1         | 1.89%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 1         | 1.89%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                            | 1         | 1.89%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 1         | 1.89%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 1         | 1.89%   |
| Broadcom BCM4321 802.11a/b/g/n                                                | 1         | 1.89%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 1         | 1.89%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                     | 1         | 1.89%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 30        | 63.83%  |
| Intel                    | 6         | 12.77%  |
| Broadcom                 | 5         | 10.64%  |
| ASIX Electronics         | 2         | 4.26%   |
| Samsung Electronics      | 1         | 2.13%   |
| OPPO Electronics         | 1         | 2.13%   |
| Nvidia                   | 1         | 2.13%   |
| Marvell Technology Group | 1         | 2.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 22        | 44.9%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 10.2%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 8.16%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 4.08%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 4.08%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 4.08%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 4.08%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 2.04%   |
| OPPO CPH2411                                                      | 1         | 2.04%   |
| Nvidia MCP61 Ethernet                                             | 1         | 2.04%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 2.04%   |
| Intel I211 Gigabit Network Connection                             | 1         | 2.04%   |
| Intel Ethernet Connection I218-V                                  | 1         | 2.04%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 2.04%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 2.04%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 2.04%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 2.04%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 46        | 50.55%  |
| Ethernet | 45        | 49.45%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 34        | 62.96%  |
| WiFi     | 20        | 37.04%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 29        | 47.54%  |
| 1     | 22        | 36.07%  |
| 0     | 8         | 13.11%  |
| 3     | 2         | 3.28%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 46        | 75.41%  |
| Yes  | 15        | 24.59%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


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

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                   | 7         | 17.95%  |
| Foxconn / Hon Hai Bluetooth Device                   | 5         | 12.82%  |
| Lite-On Atheros AR3012 Bluetooth                     | 4         | 10.26%  |
| Apple Bluetooth USB Host Controller                  | 4         | 10.26%  |
| Qualcomm Atheros  Bluetooth Device                   | 2         | 5.13%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                | 2         | 5.13%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)       | 2         | 5.13%   |
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
| Apple Bluetooth Host Controller                      | 1         | 2.56%   |
| Apple Bluetooth HCI                                  | 1         | 2.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 47        | 70.15%  |
| AMD      | 8         | 11.94%  |
| Nvidia   | 7         | 10.45%  |
| XMOS     | 1         | 1.49%   |
| Shure    | 1         | 1.49%   |
| Micronas | 1         | 1.49%   |
| M-Audio  | 1         | 1.49%   |
| Logitech | 1         | 1.49%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 12        | 15%     |
| Intel Comet Lake PCH-LP cAVS                                               | 8         | 10%     |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 5%      |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 5%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 5%      |
| Intel 8 Series HD Audio Controller                                         | 4         | 5%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 5%      |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 3.75%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 2.5%    |
| Intel Broadwell-U Audio Controller                                         | 2         | 2.5%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 2.5%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 2.5%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 2.5%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.5%    |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 2.5%    |
| XMOS xCORE USB Audio 2.0                                                   | 1         | 1.25%   |
| Shure MV5                                                                  | 1         | 1.25%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 1.25%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 1.25%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 1.25%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.25%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.25%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 1.25%   |
| Nvidia GF116 High Definition Audio Controller                              | 1         | 1.25%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.25%   |
| Micronas QSB                                                               | 1         | 1.25%   |
| M-Audio M-Audio Fast Track MKII                                            | 1         | 1.25%   |
| Logitech Headset H340                                                      | 1         | 1.25%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 1.25%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.25%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1.25%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.25%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1         | 1.25%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 1.25%   |
| AMD RV770 HDMI Audio [Radeon HD 4850/4870]                                 | 1         | 1.25%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1         | 1.25%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 1.25%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.25%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 8         | 32%     |
| Unknown             | 4         | 16%     |
| Samsung Electronics | 4         | 16%     |
| Crucial             | 4         | 16%     |
| Toshiba             | 2         | 8%      |
| Smart               | 1         | 4%      |
| Micron Technology   | 1         | 4%      |
| Kingston            | 1         | 4%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 2         | 7.41%   |
| Crucial RAM CT16G4SFD824A.M16FRS 16GB SODIMM DDR4 2400MT/s       | 2         | 7.41%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 3.7%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 3.7%    |
| Unknown RAM Module 4GB DIMM 1600MT/s                             | 1         | 3.7%    |
| Unknown RAM Module 16384MB 2133MT/s                              | 1         | 3.7%    |
| Toshiba RAM 9905711-015.A00G 4GB SODIMM DDR4 2400MT/s            | 1         | 3.7%    |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s               | 1         | 3.7%    |
| Toshiba RAM 64T128020EDL2.5C2 1GB SODIMM 1066MT/s                | 1         | 3.7%    |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s            | 1         | 3.7%    |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 3.7%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 3.7%    |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1600MT/s          | 1         | 3.7%    |
| SK hynix RAM HMP125U6EFR8C-S6 2GB DIMM DDR2 800MT/s              | 1         | 3.7%    |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 3.7%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 3.7%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 3.7%    |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 3.7%    |
| SK hynix RAM H9CCNNNBLTALAR-NTD 4GB Row Of Chips LPDDR3 1600MT/s | 1         | 3.7%    |
| Samsung RAM Module 4GB SODIMM LPDDR3 1867MT/s                    | 1         | 3.7%    |
| Samsung RAM K4A8G165WC-BCTD 4GB SODIMM DDR4 2667MT/s             | 1         | 3.7%    |
| Micron RAM 16HTF25664AZ-800H1 2GB DIMM DDR2 800MT/s              | 1         | 3.7%    |
| Kingston RAM 9905471-011.A00LF 4GB DIMM DDR3 1600MT/s            | 1         | 3.7%    |
| Crucial RAM CT4G4SFS8213.C8FBD1 4GB SODIMM DDR4 2133MT/s         | 1         | 3.7%    |
| Crucial RAM CT16G4S24AM.M16FE 16GB SODIMM DDR4 2400MT/s          | 1         | 3.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 10        | 45.45%  |
| DDR3    | 5         | 22.73%  |
| LPDDR3  | 3         | 13.64%  |
| DDR2    | 2         | 9.09%   |
| Unknown | 2         | 9.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 15        | 68.18%  |
| DIMM         | 4         | 18.18%  |
| Row Of Chips | 2         | 9.09%   |
| Unknown      | 1         | 4.55%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 12        | 50%     |
| 8192  | 5         | 20.83%  |
| 16384 | 4         | 16.67%  |
| 32768 | 2         | 8.33%   |
| 2048  | 1         | 4.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 7         | 29.17%  |
| 2667  | 6         | 25%     |
| 2400  | 4         | 16.67%  |
| 2133  | 2         | 8.33%   |
| 1867  | 2         | 8.33%   |
| 1333  | 1         | 4.17%   |
| 1066  | 1         | 4.17%   |
| 800   | 1         | 4.17%   |

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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Apple                                  | 6         | 16.67%  |
| Realtek Semiconductor                  | 5         | 13.89%  |
| Chicony Electronics                    | 4         | 11.11%  |
| Bison Electronics                      | 4         | 11.11%  |
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
| Acer                                   | 1         | 2.78%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Apple Built-in iSight                                                      | 3         | 8.11%   |
| Alcor Micro HD WebCam                                                      | 3         | 8.11%   |
| Realtek USB2.0 camera                                                      | 2         | 5.41%   |
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
| Apple iBridge                                                              | 1         | 2.7%    |
| Apple FaceTime HD Camera (Built-in)                                        | 1         | 2.7%    |
| Alcor Micro HP Webcam-101                                                  | 1         | 2.7%    |
| Acer BisonCam, NB Pro                                                      | 1         | 2.7%    |
| Unknown                                                                    | 1         | 2.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 4         | 50%     |
| LighTuning Technology | 2         | 25%     |
| Synaptics             | 1         | 12.5%   |
| STMicroelectronics    | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Purism, SPC | 3         | 50%     |
| O2 Micro    | 1         | 16.67%  |
| Clay Logic  | 1         | 16.67%  |
| Alcor Micro | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 32        | 51.61%  |
| 1     | 22        | 35.48%  |
| 2     | 5         | 8.06%   |
| 3     | 2         | 3.23%   |
| 4     | 1         | 1.61%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 11        | 27.5%   |
| Fingerprint reader    | 8         | 20%     |
| Graphics card         | 7         | 17.5%   |
| Bluetooth             | 7         | 17.5%   |
| Multimedia controller | 4         | 10%     |
| Chipcard              | 2         | 5%      |
| Camera                | 1         | 2.5%    |

