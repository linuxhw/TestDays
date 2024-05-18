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

Total: 107

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | F2A85-M PRO                 | Desktop     | [1a0e93d25f](https://linux-hardware.org/?probe=1a0e93d25f) | Apr 23, 2024 |
| Purism        | Librem 15 v3                | Notebook    | [e43654a7ca](https://linux-hardware.org/?probe=e43654a7ca) | Mar 20, 2024 |
| Purism        | librem_13v2                 | Notebook    | [e338abd505](https://linux-hardware.org/?probe=e338abd505) | Mar 15, 2024 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [44c9ce4d0c](https://linux-hardware.org/?probe=44c9ce4d0c) | Feb 13, 2024 |
| Apple         | MacBook5,1                  | Notebook    | [258dc80f87](https://linux-hardware.org/?probe=258dc80f87) | Feb 11, 2024 |
| Wortmann      | TERRA_PC                    | Desktop     | [670f98f66b](https://linux-hardware.org/?probe=670f98f66b) | Jan 27, 2024 |
| Wortmann      | TERRA_PC                    | Desktop     | [ef0c89a597](https://linux-hardware.org/?probe=ef0c89a597) | Jan 27, 2024 |
| Apple         | MacBook5,1                  | Notebook    | [3fb985c33d](https://linux-hardware.org/?probe=3fb985c33d) | Jan 21, 2024 |
| ASUSTek       | A88X-PLUS/USB               | Desktop     | [819679691a](https://linux-hardware.org/?probe=819679691a) | Jan 14, 2024 |
| Purism        | Librem 14                   | Notebook    | [215d922345](https://linux-hardware.org/?probe=215d922345) | Dec 28, 2023 |
| Shuttle       | DS10U                       | Desktop     | [333bcd6641](https://linux-hardware.org/?probe=333bcd6641) | Dec 26, 2023 |
| Shuttle       | DS10U                       | Desktop     | [2b28414f3d](https://linux-hardware.org/?probe=2b28414f3d) | Dec 14, 2023 |
| Shuttle       | DS10U                       | Desktop     | [0a9d211454](https://linux-hardware.org/?probe=0a9d211454) | Dec 14, 2023 |
| ASUSTek       | A88X-PLUS/USB               | Desktop     | [0856a3d881](https://linux-hardware.org/?probe=0856a3d881) | Dec 11, 2023 |
| ASUSTek       | A88X-PLUS/USB               | Desktop     | [8603cdd73e](https://linux-hardware.org/?probe=8603cdd73e) | Nov 28, 2023 |
| Purism        | Librem 13 v4                | Notebook    | [0fdc9f6ef8](https://linux-hardware.org/?probe=0fdc9f6ef8) | Nov 23, 2023 |
| Purism        | Librem 13 v4                | Notebook    | [83c0da5aab](https://linux-hardware.org/?probe=83c0da5aab) | Nov 23, 2023 |
| Lenovo        | ThinkPad P50 20ENCTO1WW     | Notebook    | [80851b7836](https://linux-hardware.org/?probe=80851b7836) | Aug 27, 2023 |
| Lenovo        | G450 2949                   | Notebook    | [a8ec62d51f](https://linux-hardware.org/?probe=a8ec62d51f) | Aug 21, 2023 |
| Lenovo        | G450 2949                   | Notebook    | [64d2950d7a](https://linux-hardware.org/?probe=64d2950d7a) | Aug 21, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [107c99d5ee](https://linux-hardware.org/?probe=107c99d5ee) | Jul 03, 2023 |
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

![OS](./All/images/pie_chart/os_name.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| PureOS 10   | 29        | 38.67%  |
| PureOS 10.0 | 22        | 29.33%  |
| PureOS 9.0  | 13        | 17.33%  |
| PureOS 10.x | 5         | 6.67%   |
| PureOS 9    | 3         | 4%      |
| PureOS 8    | 3         | 4%      |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| PureOS | 70        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                          | Computers | Percent |
|----------------------------------|-----------|---------|
| 4.19.0-5-amd64                   | 10        | 12.35%  |
| 5.10.0-14-amd64                  | 8         | 9.88%   |
| 5.10.0-23-amd64                  | 6         | 7.41%   |
| 5.10.0-13-amd64                  | 5         | 6.17%   |
| 5.10.0-8-amd64                   | 4         | 4.94%   |
| 5.10.0-21-amd64                  | 4         | 4.94%   |
| 5.10.0-11-amd64                  | 4         | 4.94%   |
| 4.19.0-14-amd64                  | 4         | 4.94%   |
| 5.10.0-28-amd64                  | 3         | 3.7%    |
| 5.10.0-27-amd64                  | 3         | 3.7%    |
| 5.10.0-26-amd64                  | 3         | 3.7%    |
| 6.1.0-1-librem5                  | 2         | 2.47%   |
| 5.7.0-1-librem5                  | 2         | 2.47%   |
| 5.10.0-9-amd64                   | 2         | 2.47%   |
| 5.10.0-7-amd64                   | 2         | 2.47%   |
| 5.10.0-19-amd64                  | 2         | 2.47%   |
| 5.10.0-16-amd64                  | 2         | 2.47%   |
| 6.1.66-x64v2-xanmod1             | 1         | 1.23%   |
| 6.0.0-1-librem5                  | 1         | 1.23%   |
| 5.9-sunxi64                      | 1         | 1.23%   |
| 5.8-sunxi64                      | 1         | 1.23%   |
| 5.7.0-0.38-1-pinebookpro-hwaccel | 1         | 1.23%   |
| 5.15.0-2-amd64                   | 1         | 1.23%   |
| 5.10.0-6-amd64                   | 1         | 1.23%   |
| 5.10.0-25-amd64                  | 1         | 1.23%   |
| 5.10.0-20-amd64                  | 1         | 1.23%   |
| 5.10.0-18-amd64                  | 1         | 1.23%   |
| 5.10.0-17-amd64                  | 1         | 1.23%   |
| 5.10.0-15-amd64                  | 1         | 1.23%   |
| 5.10.0-12-amd64                  | 1         | 1.23%   |
| 4.19.72-imx8-sr                  | 1         | 1.23%   |
| 4.16.0-1-amd64                   | 1         | 1.23%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 49        | 65.33%  |
| 4.19.0  | 14        | 18.67%  |
| 5.7.0   | 3         | 4%      |
| 6.1.0   | 2         | 2.67%   |
| 6.1.66  | 1         | 1.33%   |
| 6.0.0   | 1         | 1.33%   |
| 5.9     | 1         | 1.33%   |
| 5.8     | 1         | 1.33%   |
| 5.15.0  | 1         | 1.33%   |
| 4.19.72 | 1         | 1.33%   |
| 4.16.0  | 1         | 1.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 49        | 66.22%  |
| 4.19    | 15        | 20.27%  |
| 6.1     | 3         | 4.05%   |
| 5.7     | 3         | 4.05%   |
| 6.0     | 1         | 1.35%   |
| 5.15    | 1         | 1.35%   |
| 5       | 1         | 1.35%   |
| 4.16    | 1         | 1.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 63        | 90%     |
| aarch64 | 7         | 10%     |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 60        | 82.19%  |
| Unknown         | 6         | 8.22%   |
| KDE5            | 4         | 5.48%   |
| Phosh:GNOME     | 1         | 1.37%   |
| MATE            | 1         | 1.37%   |
| GNOME Flashback | 1         | 1.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 52        | 68.42%  |
| X11     | 13        | 17.11%  |
| Unknown | 6         | 7.89%   |
| Tty     | 5         | 6.58%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 40        | 55.56%  |
| GDM     | 21        | 29.17%  |
| GDM3    | 9         | 12.5%   |
| SDDM    | 2         | 2.78%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 30        | 41.1%   |
| de_DE   | 8         | 10.96%  |
| en_GB   | 5         | 6.85%   |
| Unknown | 4         | 5.48%   |
| ru_RU   | 3         | 4.11%   |
| pl_PL   | 3         | 4.11%   |
| it_IT   | 3         | 4.11%   |
| C       | 3         | 4.11%   |
| pt_BR   | 2         | 2.74%   |
| fr_FR   | 2         | 2.74%   |
| en_AU   | 2         | 2.74%   |
| zh_CN   | 1         | 1.37%   |
| pt_PT   | 1         | 1.37%   |
| hu_HU   | 1         | 1.37%   |
| es_ES   | 1         | 1.37%   |
| es_CR   | 1         | 1.37%   |
| es_AR   | 1         | 1.37%   |
| en_IL   | 1         | 1.37%   |
| bg_BG   | 1         | 1.37%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 59        | 83.1%   |
| EFI  | 12        | 16.9%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 64        | 91.43%  |
| Overlay | 2         | 2.86%   |
| Unknown | 2         | 2.86%   |
| Ext2    | 1         | 1.43%   |
| Btrfs   | 1         | 1.43%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 39        | 54.17%  |
| MBR     | 18        | 25%     |
| GPT     | 15        | 20.83%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 58        | 81.69%  |
| Yes       | 13        | 18.31%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 63        | 90%     |
| Yes       | 7         | 10%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Purism              | 17        | 24.29%  |
| Lenovo              | 9         | 12.86%  |
| Apple               | 9         | 12.86%  |
| Dell                | 6         | 8.57%   |
| Hewlett-Packard     | 4         | 5.71%   |
| ASUSTek Computer    | 4         | 5.71%   |
| Unknown             | 3         | 4.29%   |
| Pine Microsystems   | 2         | 2.86%   |
| Gigabyte Technology | 2         | 2.86%   |
| Acer                | 2         | 2.86%   |
| Wortmann AG         | 1         | 1.43%   |
| Toshiba             | 1         | 1.43%   |
| Shuttle             | 1         | 1.43%   |
| Samsung Electronics | 1         | 1.43%   |
| PCWare              | 1         | 1.43%   |
| Notebook            | 1         | 1.43%   |
| MSI                 | 1         | 1.43%   |
| Microsoft           | 1         | 1.43%   |
| LG Electronics      | 1         | 1.43%   |
| HUAWEI              | 1         | 1.43%   |
| Google              | 1         | 1.43%   |
| Chuwi               | 1         | 1.43%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Purism Librem 14                         | 6         | 8.57%   |
| Unknown                                  | 3         | 4.29%   |
| Purism Librem 15 v4                      | 2         | 2.86%   |
| Purism Librem 15 v3                      | 2         | 2.86%   |
| Purism Librem 13 v4                      | 2         | 2.86%   |
| HP Pavilion g6                           | 2         | 2.86%   |
| Wortmann AG TERRA_PC                     | 1         | 1.43%   |
| Toshiba Satellite L500D                  | 1         | 1.43%   |
| Shuttle DS10U                            | 1         | 1.43%   |
| Samsung 530U3C/530U4C/532U3C             | 1         | 1.43%   |
| Purism librem_mini_v2                    | 1         | 1.43%   |
| Purism librem_13v2                       | 1         | 1.43%   |
| Purism Librem 5r4                        | 1         | 1.43%   |
| Purism Librem 5                          | 1         | 1.43%   |
| Purism Librem 13 v2                      | 1         | 1.43%   |
| Pine Microsystems Pine64 PinePhone (1.2) | 1         | 1.43%   |
| Pine Microsystems Pine64 Pinebook Pro    | 1         | 1.43%   |
| PCWare IPX4005G                          | 1         | 1.43%   |
| Notebook P17SM                           | 1         | 1.43%   |
| MSI MS-7788                              | 1         | 1.43%   |
| Microsoft Surface Book 2                 | 1         | 1.43%   |
| LG 22V280-L.BY31P1                       | 1         | 1.43%   |
| Lenovo ThinkPad T540p 20BFS23T00         | 1         | 1.43%   |
| Lenovo ThinkPad T440p                    | 1         | 1.43%   |
| Lenovo ThinkPad T440 20B60044RT          | 1         | 1.43%   |
| Lenovo ThinkPad P50 20ENCTO1WW           | 1         | 1.43%   |
| Lenovo ThinkPad E480 20KN003SUS          | 1         | 1.43%   |
| Lenovo ThinkPad 13 2nd Gen 20J2S00G00    | 1         | 1.43%   |
| Lenovo IdeaPad U430 Touch 20270          | 1         | 1.43%   |
| Lenovo G450 2949                         | 1         | 1.43%   |
| Lenovo B50-70 20384                      | 1         | 1.43%   |
| HUAWEI NBLB-WAX9N                        | 1         | 1.43%   |
| HP Spectre x360 Convertible              | 1         | 1.43%   |
| HP Pavilion Notebook                     | 1         | 1.43%   |
| Google Droid                             | 1         | 1.43%   |
| Gigabyte GA-MA78GM-UD2H                  | 1         | 1.43%   |
| Gigabyte B85M-DS3H                       | 1         | 1.43%   |
| Dell XPS 13 9370                         | 1         | 1.43%   |
| Dell OptiPlex 760                        | 1         | 1.43%   |
| Dell Latitude D430                       | 1         | 1.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Purism librem            | 17        | 24.29%  |
| Lenovo ThinkPad          | 6         | 8.57%   |
| HP Pavilion              | 3         | 4.29%   |
| Dell Inspiron            | 3         | 4.29%   |
| Unknown                  | 3         | 4.29%   |
| Pine Microsystems Pine64 | 2         | 2.86%   |
| Wortmann AG TERRA        | 1         | 1.43%   |
| Toshiba Satellite        | 1         | 1.43%   |
| Shuttle DS10U            | 1         | 1.43%   |
| Samsung 530U3C           | 1         | 1.43%   |
| PCWare IPX4005G          | 1         | 1.43%   |
| Notebook P17SM           | 1         | 1.43%   |
| MSI MS-7788              | 1         | 1.43%   |
| Microsoft Surface        | 1         | 1.43%   |
| LG 22V280-L.BY31P1       | 1         | 1.43%   |
| Lenovo IdeaPad           | 1         | 1.43%   |
| Lenovo G450              | 1         | 1.43%   |
| Lenovo B50-70            | 1         | 1.43%   |
| HUAWEI NBLB-WAX9N        | 1         | 1.43%   |
| HP Spectre               | 1         | 1.43%   |
| Google Droid             | 1         | 1.43%   |
| Gigabyte GA-MA78GM-UD2H  | 1         | 1.43%   |
| Gigabyte B85M-DS3H       | 1         | 1.43%   |
| Dell XPS                 | 1         | 1.43%   |
| Dell OptiPlex            | 1         | 1.43%   |
| Dell Latitude            | 1         | 1.43%   |
| Chuwi Hi10               | 1         | 1.43%   |
| ASUS M4N68T              | 1         | 1.43%   |
| ASUS F2A85-M             | 1         | 1.43%   |
| ASUS EX-A320M-GAMING     | 1         | 1.43%   |
| ASUS A88X-PLUS           | 1         | 1.43%   |
| Apple Macmini6           | 1         | 1.43%   |
| Apple MacBookPro6        | 1         | 1.43%   |
| Apple MacBookPro14       | 1         | 1.43%   |
| Apple MacBookAir7        | 1         | 1.43%   |
| Apple MacBook9           | 1         | 1.43%   |
| Apple MacBook5           | 1         | 1.43%   |
| Apple iMac7              | 1         | 1.43%   |
| Apple iMac13             | 1         | 1.43%   |
| Apple iMac11             | 1         | 1.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 10        | 14.29%  |
| 2013    | 8         | 11.43%  |
| 2021    | 6         | 8.57%   |
| 2019    | 6         | 8.57%   |
| 2017    | 6         | 8.57%   |
| 2018    | 5         | 7.14%   |
| 2015    | 4         | 5.71%   |
| 2009    | 4         | 5.71%   |
| 2020    | 3         | 4.29%   |
| 2016    | 3         | 4.29%   |
| 2014    | 3         | 4.29%   |
| 2012    | 3         | 4.29%   |
| 2011    | 3         | 4.29%   |
| 2007    | 3         | 4.29%   |
| 2010    | 2         | 2.86%   |
| 2023    | 1         | 1.43%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 45        | 64.29%  |
| Desktop        | 13        | 18.57%  |
| All in one     | 4         | 5.71%   |
| System on chip | 3         | 4.29%   |
| Tablet         | 2         | 2.86%   |
| Phone          | 1         | 1.43%   |
| Convertible    | 1         | 1.43%   |
| Mini pc        | 1         | 1.43%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 70        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 53        | 75.71%  |
| Yes  | 17        | 24.29%  |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 15        | 21.43%  |
| 4.01-8.0    | 14        | 20%     |
| 3.01-4.0    | 14        | 20%     |
| 8.01-16.0   | 13        | 18.57%  |
| 32.01-64.0  | 7         | 10%     |
| 1.01-2.0    | 3         | 4.29%   |
| 2.01-3.0    | 2         | 2.86%   |
| 24.01-32.0  | 1         | 1.43%   |
| 64.01-256.0 | 1         | 1.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 23        | 29.11%  |
| 1.01-2.0  | 20        | 25.32%  |
| 3.01-4.0  | 16        | 20.25%  |
| 4.01-8.0  | 15        | 18.99%  |
| 8.01-16.0 | 3         | 3.8%    |
| 0.51-1.0  | 1         | 1.27%   |
| 0.01-0.5  | 1         | 1.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 49        | 68.06%  |
| 2      | 17        | 23.61%  |
| 0      | 3         | 4.17%   |
| 3      | 2         | 2.78%   |
| 5      | 1         | 1.39%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 56        | 78.87%  |
| Yes       | 15        | 21.13%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 54        | 77.14%  |
| No        | 16        | 22.86%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 54        | 77.14%  |
| No        | 16        | 22.86%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 61.43%  |
| No        | 27        | 38.57%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 15        | 20.83%  |
| Germany                | 11        | 15.28%  |
| UK                     | 6         | 8.33%   |
| Brazil                 | 6         | 8.33%   |
| Italy                  | 4         | 5.56%   |
| Russia                 | 3         | 4.17%   |
| Poland                 | 3         | 4.17%   |
| Canada                 | 3         | 4.17%   |
| Australia              | 3         | 4.17%   |
| France                 | 2         | 2.78%   |
| Turkey                 | 1         | 1.39%   |
| Spain                  | 1         | 1.39%   |
| South Africa           | 1         | 1.39%   |
| Serbia                 | 1         | 1.39%   |
| Portugal               | 1         | 1.39%   |
| Paraguay               | 1         | 1.39%   |
| Pakistan               | 1         | 1.39%   |
| Martinique             | 1         | 1.39%   |
| Israel                 | 1         | 1.39%   |
| Iran                   | 1         | 1.39%   |
| Greece                 | 1         | 1.39%   |
| Costa Rica             | 1         | 1.39%   |
| China                  | 1         | 1.39%   |
| Bulgaria               | 1         | 1.39%   |
| Bosnia and Herzegovina | 1         | 1.39%   |
| Argentina              | 1         | 1.39%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Stuttgart              | 3         | 4%      |
| Porto Alegre           | 3         | 4%      |
| Warsaw                 | 2         | 2.67%   |
| New York               | 2         | 2.67%   |
| London                 | 2         | 2.67%   |
| Berlin                 | 2         | 2.67%   |
| Yuzhnoural'sk          | 1         | 1.33%   |
| Wixom                  | 1         | 1.33%   |
| Windsor                | 1         | 1.33%   |
| Vista                  | 1         | 1.33%   |
| Vancouver              | 1         | 1.33%   |
| Troy                   | 1         | 1.33%   |
| Tomsk                  | 1         | 1.33%   |
| Thorpe Hamlet          | 1         | 1.33%   |
| Tel Aviv               | 1         | 1.33%   |
| Stolberg               | 1         | 1.33%   |
| Stargard               | 1         | 1.33%   |
| Spencer                | 1         | 1.33%   |
| Sofia                  | 1         | 1.33%   |
| Seattle                | 1         | 1.33%   |
| Sao Paulo              | 1         | 1.33%   |
| Sant Cugat del Vallès | 1         | 1.33%   |
| San Jose               | 1         | 1.33%   |
| Plano                  | 1         | 1.33%   |
| Perth                  | 1         | 1.33%   |
| Paris                  | 1         | 1.33%   |
| Montreal               | 1         | 1.33%   |
| Milwaukee              | 1         | 1.33%   |
| Milpitas               | 1         | 1.33%   |
| Milan                  | 1         | 1.33%   |
| Melbourne              | 1         | 1.33%   |
| Mankato                | 1         | 1.33%   |
| Liverpool              | 1         | 1.33%   |
| Lenningen              | 1         | 1.33%   |
| Leeds                  | 1         | 1.33%   |
| Lambeth                | 1         | 1.33%   |
| Krasnogorsk            | 1         | 1.33%   |
| Karachi                | 1         | 1.33%   |
| Ituzaingo              | 1         | 1.33%   |
| Istanbul               | 1         | 1.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 21        | 28     | 25.3%   |
| Unknown             | 8         | 12     | 9.64%   |
| Seagate             | 8         | 17     | 9.64%   |
| Apple               | 6         | 8      | 7.23%   |
| WDC                 | 5         | 6      | 6.02%   |
| SanDisk             | 5         | 5      | 6.02%   |
| HGST                | 3         | 3      | 3.61%   |
| Crucial             | 3         | 5      | 3.61%   |
| A-DATA Technology   | 3         | 4      | 3.61%   |
| Kingston            | 2         | 3      | 2.41%   |
| Win Memory          | 1         | 1      | 1.2%    |
| Transcend           | 1         | 1      | 1.2%    |
| Toshiba             | 1         | 1      | 1.2%    |
| Qumo                | 1         | 1      | 1.2%    |
| PNY                 | 1         | 2      | 1.2%    |
| Plextor             | 1         | 1      | 1.2%    |
| Phison              | 1         | 1      | 1.2%    |
| Patriot             | 1         | 1      | 1.2%    |
| Mushkin             | 1         | 1      | 1.2%    |
| Maxtor              | 1         | 1      | 1.2%    |
| JMicron Technology  | 1         | 1      | 1.2%    |
| Intenso             | 1         | 2      | 1.2%    |
| Intel               | 1         | 1      | 1.2%    |
| Hitachi             | 1         | 1      | 1.2%    |
| China               | 1         | 3      | 1.2%    |
| BIWIN               | 1         | 1      | 1.2%    |
| ASMT                | 1         | 2      | 1.2%    |
| ADATA Technology    | 1         | 1      | 1.2%    |
| Unknown             | 1         | 1      | 1.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown MMC Card  64GB                            | 2         | 2.17%   |
| Unknown MMC Card  32GB                            | 2         | 2.17%   |
| Seagate ST1000LM048-2E7172 1TB                    | 2         | 2.17%   |
| Samsung SSD 970 PRO 1TB                           | 2         | 2.17%   |
| Samsung SSD 860 EVO 500GB                         | 2         | 2.17%   |
| Samsung SSD 860 EVO 250GB                         | 2         | 2.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 2         | 2.17%   |
| Crucial CT250MX500SSD4 250GB                      | 2         | 2.17%   |
| Win Memory SWR256G-201II 256GB                    | 1         | 1.09%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 1         | 1.09%   |
| WDC WDS100T2B0C-00PXH0 1TB                        | 1         | 1.09%   |
| WDC WDBNCE2500PNC 250GB SSD                       | 1         | 1.09%   |
| WDC WD5000AZRX-00A8LB0 500GB                      | 1         | 1.09%   |
| WDC WD3200AAJS-40RYA0 320GB                       | 1         | 1.09%   |
| Unknown SH64G  64GB                               | 1         | 1.09%   |
| Unknown MMC Card  16GB                            | 1         | 1.09%   |
| Unknown DA4128  128GB                             | 1         | 1.09%   |
| Unknown AFGCF  128GB                              | 1         | 1.09%   |
| Unknown 8GTF4R  8GB                               | 1         | 1.09%   |
| Unknown 032G32  32GB                              | 1         | 1.09%   |
| Transcend TS240GMTS420S 240GB SSD                 | 1         | 1.09%   |
| Toshiba NVMe SSD Drive 512GB                      | 1         | 1.09%   |
| Seagate ST480HM000-1G5162 480GB                   | 1         | 1.09%   |
| Seagate ST3500630AS 500GB                         | 1         | 1.09%   |
| Seagate ST3320418AS 320GB                         | 1         | 1.09%   |
| Seagate ST3250410AS 250GB                         | 1         | 1.09%   |
| Seagate ST3250312CS 250GB                         | 1         | 1.09%   |
| Seagate ST31000524AS 1TB                          | 1         | 1.09%   |
| Seagate ST1000DM003-1ER162 1TB                    | 1         | 1.09%   |
| Seagate ST1000DM003-1CH162 1TB                    | 1         | 1.09%   |
| Seagate NVMe SSD Drive 2TB                        | 1         | 1.09%   |
| SanDisk SSD i100 24GB                             | 1         | 1.09%   |
| SanDisk SDSSDP128G 128GB                          | 1         | 1.09%   |
| SanDisk SDSSDH3500G 500GB                         | 1         | 1.09%   |
| SanDisk NVMe SSD Drive 500GB                      | 1         | 1.09%   |
| SanDisk DF4128  128GB                             | 1         | 1.09%   |
| Samsung SSD 970 EVO Plus 500GB                    | 1         | 1.09%   |
| Samsung SSD 970 EVO Plus 2TB                      | 1         | 1.09%   |
| Samsung SSD 970 EVO 250GB                         | 1         | 1.09%   |
| Samsung SSD 960 EVO 500GB                         | 1         | 1.09%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 16     | 33.33%  |
| HGST                | 3         | 3      | 14.29%  |
| Apple               | 3         | 3      | 14.29%  |
| WDC                 | 2         | 2      | 9.52%   |
| Samsung Electronics | 2         | 2      | 9.52%   |
| Maxtor              | 1         | 1      | 4.76%   |
| JMicron Technology  | 1         | 1      | 4.76%   |
| Hitachi             | 1         | 1      | 4.76%   |
| ASMT                | 1         | 2      | 4.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 12     | 26.47%  |
| SanDisk             | 3         | 3      | 8.82%   |
| Crucial             | 3         | 5      | 8.82%   |
| A-DATA Technology   | 3         | 4      | 8.82%   |
| WDC                 | 2         | 3      | 5.88%   |
| Kingston            | 2         | 3      | 5.88%   |
| Win Memory          | 1         | 1      | 2.94%   |
| Transcend           | 1         | 1      | 2.94%   |
| Qumo                | 1         | 1      | 2.94%   |
| PNY                 | 1         | 2      | 2.94%   |
| Plextor             | 1         | 1      | 2.94%   |
| Patriot             | 1         | 1      | 2.94%   |
| Mushkin             | 1         | 1      | 2.94%   |
| Intenso             | 1         | 2      | 2.94%   |
| Intel               | 1         | 1      | 2.94%   |
| China               | 1         | 3      | 2.94%   |
| BIWIN               | 1         | 1      | 2.94%   |
| Apple               | 1         | 1      | 2.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 31        | 46     | 39.24%  |
| NVMe    | 19        | 24     | 24.05%  |
| HDD     | 19        | 31     | 24.05%  |
| MMC     | 9         | 13     | 11.39%  |
| Unknown | 1         | 1      | 1.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 44        | 74     | 58.67%  |
| NVMe | 19        | 24     | 25.33%  |
| MMC  | 9         | 13     | 12%     |
| SAS  | 3         | 4      | 4%      |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 36        | 57     | 75%     |
| 0.51-1.0   | 10        | 17     | 20.83%  |
| 1.01-2.0   | 2         | 3      | 4.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 35        | 47.95%  |
| 251-500    | 8         | 10.96%  |
| 101-250    | 8         | 10.96%  |
| 51-100     | 6         | 8.22%   |
| 21-50      | 5         | 6.85%   |
| 501-1000   | 4         | 5.48%   |
| 1001-2000  | 3         | 4.11%   |
| Unknown    | 3         | 4.11%   |
| 2001-3000  | 1         | 1.37%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 49        | 66.22%  |
| 21-50    | 14        | 18.92%  |
| 101-250  | 3         | 4.05%   |
| 501-1000 | 3         | 4.05%   |
| Unknown  | 3         | 4.05%   |
| 251-500  | 1         | 1.35%   |
| 51-100   | 1         | 1.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                      | Computers | Drives | Percent |
|----------------------------|-----------|--------|---------|
| Seagate ST3250410AS 250GB  | 1         | 1      | 16.67%  |
| Seagate ST3250312CS 250GB  | 1         | 1      | 16.67%  |
| Seagate ST31000524AS 1TB   | 1         | 2      | 16.67%  |
| Maxtor 7V250F0 256GB       | 1         | 1      | 16.67%  |
| Intel SSDSC2BF180A4H 180GB | 1         | 1      | 16.67%  |
| Apple HDD ST1000LM024 1TB  | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 4      | 40%     |
| Maxtor  | 1         | 1      | 20%     |
| Intel   | 1         | 1      | 20%     |
| Apple   | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 4      | 50%     |
| Maxtor  | 1         | 1      | 25%     |
| Apple   | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 6      | 80%     |
| SSD  | 1         | 1      | 20%     |

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
| Detected | 46        | 77     | 61.33%  |
| Works    | 24        | 31     | 32%     |
| Malfunc  | 5         | 7      | 6.67%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 40        | 57.97%  |
| Samsung Electronics          | 12        | 17.39%  |
| AMD                          | 7         | 10.14%  |
| SanDisk                      | 2         | 2.9%    |
| Nvidia                       | 2         | 2.9%    |
| Apple                        | 2         | 2.9%    |
| Toshiba America Info Systems | 1         | 1.45%   |
| Seagate Technology           | 1         | 1.45%   |
| Phison Electronics           | 1         | 1.45%   |
| ADATA Technology             | 1         | 1.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 10        | 13.7%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7         | 9.59%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 6.85%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 5         | 6.85%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 5.48%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 4.11%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 4.11%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 2.74%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 2.74%   |
| Apple S3X NVMe Controller                                                      | 2         | 2.74%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 1.37%   |
| Seagate FireCuda/IronWolf 510 SSD                                              | 1         | 1.37%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                     | 1         | 1.37%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 1         | 1.37%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 1         | 1.37%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 1.37%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 1         | 1.37%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 1.37%   |
| Nvidia MCP61 SATA Controller                                                   | 1         | 1.37%   |
| Nvidia MCP61 IDE                                                               | 1         | 1.37%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.37%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.37%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.37%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 1.37%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.37%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 1         | 1.37%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 1.37%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 1         | 1.37%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 1         | 1.37%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 1.37%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1         | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1         | 1.37%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 1.37%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 1         | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 1         | 1.37%   |
| AMD FCH SATA Controller D                                                      | 1         | 1.37%   |
| ADATA IM2P33F3 NVMe SSD (DRAM-less)                                            | 1         | 1.37%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 47        | 67.14%  |
| NVMe | 19        | 27.14%  |
| IDE  | 4         | 5.71%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 56        | 78.87%  |
| AMD     | 7         | 9.86%   |
| ARM     | 6         | 8.45%   |
| Unknown | 2         | 2.82%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-10710U CPU @ 1.10GHz          | 6         | 8.45%   |
| ARM Processor                               | 6         | 8.45%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 5         | 7.04%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 4         | 5.63%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 2.82%   |
|                                             | 2         | 2.82%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 1         | 1.41%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 1.41%   |
| Intel Pentium CPU N4200 @ 1.10GHz           | 1         | 1.41%   |
| Intel Core m5-6Y54 CPU @ 1.10GHz            | 1         | 1.41%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 1.41%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 1.41%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 1.41%   |
| Intel Core i7-7567U CPU @ 3.50GHz           | 1         | 1.41%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 1         | 1.41%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz          | 1         | 1.41%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz          | 1         | 1.41%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 1.41%   |
| Intel Core i7-4510U CPU @ 2.00GHz           | 1         | 1.41%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 1.41%   |
| Intel Core i5-5250U CPU @ 1.60GHz           | 1         | 1.41%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 1         | 1.41%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1         | 1.41%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1         | 1.41%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 1.41%   |
| Intel Core i5-3330S CPU @ 2.70GHz           | 1         | 1.41%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.41%   |
| Intel Core i5-2320 CPU @ 3.00GHz            | 1         | 1.41%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 1         | 1.41%   |
| Intel Core i5 CPU M 540 @ 2.53GHz           | 1         | 1.41%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1         | 1.41%   |
| Intel Core i3-4130T CPU @ 2.90GHz           | 1         | 1.41%   |
| Intel Core i3-4010U CPU @ 1.70GHz           | 1         | 1.41%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 1         | 1.41%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 1         | 1.41%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 1         | 1.41%   |
| Intel Core 2 Duo CPU U7700 @ 1.33GHz        | 1         | 1.41%   |
| Intel Core 2 Duo CPU T7700 @ 2.40GHz        | 1         | 1.41%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz        | 1         | 1.41%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 1         | 1.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 25        | 35.71%  |
| Intel Core i5           | 13        | 18.57%  |
| Other                   | 7         | 10%     |
| Intel Core i3           | 5         | 7.14%   |
| Intel Core 2 Duo        | 4         | 5.71%   |
| Intel Celeron           | 4         | 5.71%   |
| AMD A10                 | 2         | 2.86%   |
| Intel Pentium Silver    | 1         | 1.43%   |
| Intel Pentium Dual-Core | 1         | 1.43%   |
| Intel Pentium           | 1         | 1.43%   |
| Intel Core m5           | 1         | 1.43%   |
| Intel Atom              | 1         | 1.43%   |
| AMD Turion II Dual-Core | 1         | 1.43%   |
| AMD Ryzen 5             | 1         | 1.43%   |
| AMD Ryzen 3             | 1         | 1.43%   |
| AMD Athlon II X4        | 1         | 1.43%   |
| AMD Athlon II X3        | 1         | 1.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 36        | 51.43%  |
| 4       | 26        | 37.14%  |
| 6       | 6         | 8.57%   |
| 3       | 1         | 1.43%   |
| Unknown | 1         | 1.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 69        | 98.57%  |
| Unknown | 1         | 1.43%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 43        | 61.43%  |
| 1       | 26        | 37.14%  |
| Unknown | 1         | 1.43%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 66        | 92.96%  |
| Unknown        | 4         | 5.63%   |
| 64-bit         | 1         | 1.41%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 48        | 66.67%  |
| 0x406e3    | 4         | 5.56%   |
| 0xa0660    | 3         | 4.17%   |
| 0x806e9    | 2         | 2.78%   |
| 0x706a1    | 2         | 2.78%   |
| 0x40651    | 2         | 2.78%   |
| 0x1067a    | 2         | 2.78%   |
| 0x806ec    | 1         | 1.39%   |
| 0x806ea    | 1         | 1.39%   |
| 0x406c4    | 1         | 1.39%   |
| 0x306d4    | 1         | 1.39%   |
| 0x206a7    | 1         | 1.39%   |
| 0x08108109 | 1         | 1.39%   |
| 0x06003106 | 1         | 1.39%   |
| 0x06001119 | 1         | 1.39%   |
| 0x010000b6 | 1         | 1.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 14        | 20%     |
| Haswell       | 9         | 12.86%  |
| Unknown       | 7         | 10%     |
| Skylake       | 6         | 8.57%   |
| CometLake     | 6         | 8.57%   |
| IvyBridge     | 5         | 7.14%   |
| Penryn        | 3         | 4.29%   |
| K10           | 3         | 4.29%   |
| Goldmont plus | 3         | 4.29%   |
| Zen+          | 2         | 2.86%   |
| SandyBridge   | 2         | 2.86%   |
| Core          | 2         | 2.86%   |
| Broadwell     | 2         | 2.86%   |
| Westmere      | 1         | 1.43%   |
| Steamroller   | 1         | 1.43%   |
| Silvermont    | 1         | 1.43%   |
| Piledriver    | 1         | 1.43%   |
| Nehalem       | 1         | 1.43%   |
| Goldmont      | 1         | 1.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 50        | 69.44%  |
| Nvidia | 11        | 15.28%  |
| AMD    | 11        | 15.28%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                    | 7         | 9.21%   |
| Intel Comet Lake UHD Graphics                                                            | 6         | 7.89%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 5.26%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 5.26%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 5.26%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 3.95%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 2.63%   |
| Intel UHD Graphics 620                                                                   | 2         | 2.63%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 2.63%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 2.63%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 2.63%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 2.63%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1         | 1.32%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 1.32%   |
| Nvidia GM107GLM [Quadro M2000M]                                                          | 1         | 1.32%   |
| Nvidia GK208M [GeForce GT 730M]                                                          | 1         | 1.32%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 1.32%   |
| Nvidia GK107M [GeForce GT 640M Mac Edition]                                              | 1         | 1.32%   |
| Nvidia GK104M [GeForce GTX 870M]                                                         | 1         | 1.32%   |
| Nvidia GF116 [GeForce GTS 450 Rev. 2]                                                    | 1         | 1.32%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 1         | 1.32%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 1.32%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 1.32%   |
| Intel Whiskey Lake-U GT1 [UHD Graphics 610]                                              | 1         | 1.32%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.32%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.32%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.32%   |
| Intel Iris Plus Graphics 650                                                             | 1         | 1.32%   |
| Intel HD Graphics 630                                                                    | 1         | 1.32%   |
| Intel HD Graphics 6000                                                                   | 1         | 1.32%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.32%   |
| Intel HD Graphics 515                                                                    | 1         | 1.32%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 1.32%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.32%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.32%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 1         | 1.32%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1         | 1.32%   |
| AMD Trinity [Radeon HD 7660D]                                                            | 1         | 1.32%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 1.32%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 1.32%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 41        | 58.57%  |
| Other          | 8         | 11.43%  |
| 1 x AMD        | 7         | 10%     |
| 1 x Nvidia     | 6         | 8.57%   |
| Intel + Nvidia | 5         | 7.14%   |
| Intel + AMD    | 2         | 2.86%   |
| 2 x AMD        | 1         | 1.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 60        | 85.71%  |
| Unknown | 10        | 14.29%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 67        | 94.37%  |
| 0.51-1.0   | 2         | 2.82%   |
| 3.01-4.0   | 1         | 1.41%   |
| 1.01-2.0   | 1         | 1.41%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 11        | 15.28%  |
| Samsung Electronics     | 9         | 12.5%   |
| Chimei Innolux          | 9         | 12.5%   |
| LG Display              | 8         | 11.11%  |
| Apple                   | 7         | 9.72%   |
| Philips                 | 3         | 4.17%   |
| Goldstar                | 3         | 4.17%   |
| Unknown                 | 2         | 2.78%   |
| AU Optronics            | 2         | 2.78%   |
| ViewSonic               | 1         | 1.39%   |
| Toshiba                 | 1         | 1.39%   |
| Sony                    | 1         | 1.39%   |
| Sharp                   | 1         | 1.39%   |
| RTK                     | 1         | 1.39%   |
| PRI                     | 1         | 1.39%   |
| PANDA                   | 1         | 1.39%   |
| Panasonic               | 1         | 1.39%   |
| Lenovo                  | 1         | 1.39%   |
| Iiyama                  | 1         | 1.39%   |
| Grundig                 | 1         | 1.39%   |
| Flipbook                | 1         | 1.39%   |
| Dell                    | 1         | 1.39%   |
| Chi Mei Optoelectronics | 1         | 1.39%   |
| BenQ                    | 1         | 1.39%   |
| ASUSTek Computer        | 1         | 1.39%   |
| AOC                     | 1         | 1.39%   |
| Acer                    | 1         | 1.39%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC434B 3840x2160 344x194mm 15.5-inch | 3         | 4.17%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 4.17%   |
| BOE LCD Monitor BOE06BE 1920x1080 294x165mm 13.3-inch                 | 3         | 4.17%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 2         | 2.78%   |
| Philips TV PHL5035 1920x1080 640x360mm 28.9-inch                      | 2         | 2.78%   |
| Chimei Innolux LCD Monitor CMN1415 1920x1080 309x173mm 13.9-inch      | 2         | 2.78%   |
| ViewSonic VA2719 Series VSCC132 1920x1080 598x336mm 27.0-inch         | 1         | 1.39%   |
| Toshiba LCD Monitor LCD3706 1280x800 261x163mm 12.1-inch              | 1         | 1.39%   |
| Sony TV SNYAB03 1920x1080                                             | 1         | 1.39%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch               | 1         | 1.39%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 474x296mm 22.0-inch  | 1         | 1.39%   |
| Samsung Electronics SyncMaster SAM01D3 1440x900 408x225mm 18.3-inch   | 1         | 1.39%   |
| Samsung Electronics LS27A800U SAM71A3 3840x2160 597x336mm 27.0-inch   | 1         | 1.39%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch  | 1         | 1.39%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 700x390mm 31.5-inch  | 1         | 1.39%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1         | 1.39%   |
| RTK LG AIO FHD RTK2136 1920x1080 477x268mm 21.5-inch                  | 1         | 1.39%   |
| PRI Prima TV PRI1600 1920x1080                                        | 1         | 1.39%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 1         | 1.39%   |
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch               | 1         | 1.39%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 344x193mm 15.5-inch          | 1         | 1.39%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 1         | 1.39%   |
| LG Display LCD Monitor LGD053B 1920x1080 294x165mm 13.3-inch          | 1         | 1.39%   |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch          | 1         | 1.39%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 1         | 1.39%   |
| LG Display LCD Monitor LGD03F0 1366x768 310x174mm 14.0-inch           | 1         | 1.39%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch           | 1         | 1.39%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch           | 1         | 1.39%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch           | 1         | 1.39%   |
| Lenovo LEN Y44w-10 LEN65EA 3840x1200 1052x329mm 43.4-inch             | 1         | 1.39%   |
| Iiyama PL2792H IVM664F 1920x1080 598x336mm 27.0-inch                  | 1         | 1.39%   |
| Grundig WXGA GRU4448 1600x1200                                        | 1         | 1.39%   |
| Goldstar IPS231 GSM5817 1920x1080 510x290mm 23.1-inch                 | 1         | 1.39%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch             | 1         | 1.39%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                | 1         | 1.39%   |
| Flipbook NexDock YUKBC34 1920x1080 290x170mm 13.2-inch                | 1         | 1.39%   |
| Dell P2213 DELF042 1680x1050 473x296mm 22.0-inch                      | 1         | 1.39%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 1         | 1.39%   |
| Chimei Innolux LCD Monitor CMN15BD 1366x768 344x193mm 15.5-inch       | 1         | 1.39%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch       | 1         | 1.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 34        | 50%     |
| 1366x768 (WXGA)    | 11        | 16.18%  |
| 3840x2160 (4K)     | 8         | 11.76%  |
| 1680x1050 (WSXGA+) | 3         | 4.41%   |
| 2288x1287          | 2         | 2.94%   |
| 1600x900 (HD+)     | 2         | 2.94%   |
| 1440x900 (WXGA+)   | 2         | 2.94%   |
| 1280x800 (WXGA)    | 2         | 2.94%   |
| 3840x1200          | 1         | 1.47%   |
| 2880x1800          | 1         | 1.47%   |
| 2304x1440          | 1         | 1.47%   |
| 1920x1200 (WUXGA)  | 1         | 1.47%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 21        | 29.17%  |
| 15      | 16        | 22.22%  |
| 27      | 3         | 4.17%   |
| 24      | 3         | 4.17%   |
| 23      | 3         | 4.17%   |
| 21      | 3         | 4.17%   |
| 17      | 3         | 4.17%   |
| 14      | 3         | 4.17%   |
| 142     | 2         | 2.78%   |
| 28      | 2         | 2.78%   |
| 22      | 2         | 2.78%   |
| 20      | 2         | 2.78%   |
| 12      | 2         | 2.78%   |
| 72      | 1         | 1.39%   |
| 54      | 1         | 1.39%   |
| 43      | 1         | 1.39%   |
| 40      | 1         | 1.39%   |
| 31      | 1         | 1.39%   |
| 19      | 1         | 1.39%   |
| Unknown | 1         | 1.39%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 27        | 38.03%  |
| 201-300        | 13        | 18.31%  |
| 501-600        | 9         | 12.68%  |
| 401-500        | 8         | 11.27%  |
| 351-400        | 4         | 5.63%   |
| 601-700        | 3         | 4.23%   |
| More than 2000 | 2         | 2.82%   |
| 1001-1500      | 2         | 2.82%   |
| 801-900        | 1         | 1.41%   |
| 1501-2000      | 1         | 1.41%   |
| Unknown        | 1         | 1.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 50        | 79.37%  |
| 16/10 | 10        | 15.87%  |
| 1.00  | 2         | 3.17%   |
| 3.20  | 1         | 1.59%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 16        | 22.22%  |
| 81-90          | 15        | 20.83%  |
| 201-250        | 11        | 15.28%  |
| 71-80          | 9         | 12.5%   |
| More than 1000 | 4         | 5.56%   |
| 351-500        | 3         | 4.17%   |
| 301-350        | 3         | 4.17%   |
| 151-200        | 3         | 4.17%   |
| 61-70          | 2         | 2.78%   |
| 121-130        | 2         | 2.78%   |
| 501-1000       | 2         | 2.78%   |
| 131-140        | 1         | 1.39%   |
| Unknown        | 1         | 1.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 20        | 27.78%  |
| 121-160       | 19        | 26.39%  |
| 101-120       | 12        | 16.67%  |
| 161-240       | 9         | 12.5%   |
| More than 240 | 7         | 9.72%   |
| 1-50          | 4         | 5.56%   |
| Unknown       | 1         | 1.39%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 52        | 74.29%  |
| 2     | 9         | 12.86%  |
| 0     | 8         | 11.43%  |
| 3     | 1         | 1.43%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 38        | 35.19%  |
| Qualcomm Atheros                | 20        | 18.52%  |
| Intel                           | 17        | 15.74%  |
| Broadcom                        | 11        | 10.19%  |
| Broadcom Limited                | 4         | 3.7%    |
| ASIX Electronics                | 3         | 2.78%   |
| Qualcomm Atheros Communications | 2         | 1.85%   |
| Nvidia                          | 2         | 1.85%   |
| Marvell Technology Group        | 2         | 1.85%   |
| Samsung Electronics             | 1         | 0.93%   |
| Ralink                          | 1         | 0.93%   |
| OPPO Electronics                | 1         | 0.93%   |
| MediaTek                        | 1         | 0.93%   |
| Google                          | 1         | 0.93%   |
| Edimax Technology               | 1         | 0.93%   |
| DisplayLink                     | 1         | 0.93%   |
| D-Link                          | 1         | 0.93%   |
| ASUSTek Computer                | 1         | 0.93%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 24        | 19.67%  |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 14        | 11.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 5         | 4.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 4         | 3.28%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 4         | 3.28%   |
| Intel Wireless 7265                                                           | 4         | 3.28%   |
| Intel Wireless 7260                                                           | 3         | 2.46%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 3         | 2.46%   |
| Qualcomm Atheros AR9271 802.11n                                               | 2         | 1.64%   |
| Intel Ethernet Connection I217-LM                                             | 2         | 1.64%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 2         | 1.64%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2         | 1.64%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter          | 2         | 1.64%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1         | 0.82%   |
| Realtek USB 10/100/1G/2.5G LAN                                                | 1         | 0.82%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1         | 0.82%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 0.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.82%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 1         | 0.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1         | 0.82%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 0.82%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1         | 0.82%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 1         | 0.82%   |
| Realtek RTL8152 Fast Ethernet Adapter                                         | 1         | 0.82%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                        | 1         | 0.82%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                        | 1         | 0.82%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 0.82%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 0.82%   |
| OPPO SM8350-MTP _SN:9338D66C                                                  | 1         | 0.82%   |
| Nvidia MCP79 Ethernet                                                         | 1         | 0.82%   |
| Nvidia MCP61 Ethernet                                                         | 1         | 0.82%   |
| MediaTek WiFi                                                                 | 1         | 0.82%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                             | 1         | 0.82%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                       | 1         | 0.82%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 0.82%   |
| Intel Wireless 8260                                                           | 1         | 0.82%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 1         | 0.82%   |
| Intel I211 Gigabit Network Connection                                         | 1         | 0.82%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1         | 0.82%   |
| Intel Ethernet Connection I218-V                                              | 1         | 0.82%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 20        | 32.26%  |
| Intel                           | 14        | 22.58%  |
| Realtek Semiconductor           | 8         | 12.9%   |
| Broadcom                        | 8         | 12.9%   |
| Broadcom Limited                | 4         | 6.45%   |
| Qualcomm Atheros Communications | 2         | 3.23%   |
| Ralink                          | 1         | 1.61%   |
| MediaTek                        | 1         | 1.61%   |
| Marvell Technology Group        | 1         | 1.61%   |
| Edimax Technology               | 1         | 1.61%   |
| D-Link                          | 1         | 1.61%   |
| ASUSTek Computer                | 1         | 1.61%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 14        | 22.58%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 4         | 6.45%   |
| Intel Wireless 7265                                                           | 4         | 6.45%   |
| Intel Wireless 7260                                                           | 3         | 4.84%   |
| Qualcomm Atheros AR9271 802.11n                                               | 2         | 3.23%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter          | 2         | 3.23%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1         | 1.61%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 1.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.61%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 1         | 1.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1         | 1.61%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 1.61%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1         | 1.61%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 1         | 1.61%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                        | 1         | 1.61%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 1.61%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.61%   |
| MediaTek WiFi                                                                 | 1         | 1.61%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                             | 1         | 1.61%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 1.61%   |
| Intel Wireless 8260                                                           | 1         | 1.61%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 1         | 1.61%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1         | 1.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 1.61%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 1         | 1.61%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 1.61%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                                   | 1         | 1.61%   |
| D-Link 802.11ac NIC                                                           | 1         | 1.61%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                                        | 1         | 1.61%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                        | 1         | 1.61%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 1         | 1.61%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                            | 1         | 1.61%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 1         | 1.61%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 1         | 1.61%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                        | 1         | 1.61%   |
| Broadcom BCM4321 802.11a/b/g/n                                                | 1         | 1.61%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 1         | 1.61%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 1         | 1.61%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                     | 1         | 1.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 34        | 58.62%  |
| Intel                    | 7         | 12.07%  |
| Broadcom                 | 6         | 10.34%  |
| ASIX Electronics         | 3         | 5.17%   |
| Nvidia                   | 2         | 3.45%   |
| Samsung Electronics      | 1         | 1.72%   |
| Qualcomm Atheros         | 1         | 1.72%   |
| OPPO Electronics         | 1         | 1.72%   |
| Marvell Technology Group | 1         | 1.72%   |
| Google                   | 1         | 1.72%   |
| DisplayLink              | 1         | 1.72%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 24        | 40%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 5         | 8.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4         | 6.67%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 5%      |
| Intel Ethernet Connection I217-LM                                      | 2         | 3.33%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 2         | 3.33%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2         | 3.33%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 1.67%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 1         | 1.67%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 1.67%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 1.67%   |
| OPPO SM8350-MTP _SN:9338D66C                                           | 1         | 1.67%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 1.67%   |
| Nvidia MCP61 Ethernet                                                  | 1         | 1.67%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 1         | 1.67%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 1.67%   |
| Intel Ethernet Connection I218-V                                       | 1         | 1.67%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 1.67%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 1.67%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 1.67%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 1         | 1.67%   |
| Google Nexus/Pixel Device (tether)                                     | 1         | 1.67%   |
| DisplayLink DL-Dock                                                    | 1         | 1.67%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 1         | 1.67%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 1         | 1.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 54        | 50.47%  |
| Ethernet | 53        | 49.53%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 41        | 61.19%  |
| WiFi     | 26        | 38.81%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 33        | 47.14%  |
| 1     | 26        | 37.14%  |
| 0     | 9         | 12.86%  |
| 3     | 2         | 2.86%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 55        | 76.39%  |
| Yes  | 17        | 23.61%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 13        | 29.55%  |
| Apple                           | 8         | 18.18%  |
| Qualcomm Atheros Communications | 6         | 13.64%  |
| Lite-On Technology              | 6         | 13.64%  |
| Foxconn / Hon Hai               | 5         | 11.36%  |
| Realtek Semiconductor           | 2         | 4.55%   |
| IMC Networks                    | 1         | 2.27%   |
| Cambridge Silicon Radio         | 1         | 2.27%   |
| Broadcom                        | 1         | 2.27%   |
| ASUSTek Computer                | 1         | 2.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Lite-On Atheros AR3012 Bluetooth                     | 6         | 13.64%  |
| Intel Bluetooth wireless interface                   | 6         | 13.64%  |
| Foxconn / Hon Hai Bluetooth Device                   | 5         | 11.36%  |
| Apple Bluetooth USB Host Controller                  | 3         | 6.82%   |
| Apple Bluetooth Host Controller                      | 3         | 6.82%   |
| Qualcomm Atheros  Bluetooth Device                   | 2         | 4.55%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                | 2         | 4.55%   |
| Intel Bluetooth Device                               | 2         | 4.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)       | 2         | 4.55%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter              | 1         | 2.27%   |
| Realtek RTL8723B Bluetooth                           | 1         | 2.27%   |
| Qualcomm Atheros Dell Wireless 1802 Bluetooth 4.0 LE | 1         | 2.27%   |
| Qualcomm Atheros AR9462 Bluetooth                    | 1         | 2.27%   |
| Intel Wireless-AC 9260 Bluetooth Adapter             | 1         | 2.27%   |
| Intel Wireless-AC 3168 Bluetooth                     | 1         | 2.27%   |
| Intel Centrino Bluetooth Wireless Transceiver        | 1         | 2.27%   |
| IMC Networks Bluetooth Radio                         | 1         | 2.27%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)  | 1         | 2.27%   |
| Broadcom HP Portable Valentine                       | 1         | 2.27%   |
| ASUS Broadcom BCM20702A0 Bluetooth                   | 1         | 2.27%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                 | 1         | 2.27%   |
| Apple Bluetooth HCI                                  | 1         | 2.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor    | Computers | Percent |
|-----------|-----------|---------|
| Intel     | 53        | 67.95%  |
| AMD       | 10        | 12.82%  |
| Nvidia    | 9         | 11.54%  |
| XMOS      | 1         | 1.28%   |
| Shure     | 1         | 1.28%   |
| Micronas  | 1         | 1.28%   |
| M-Audio   | 1         | 1.28%   |
| Logitech  | 1         | 1.28%   |
| GN Netcom | 1         | 1.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 15        | 16.13%  |
| Intel Comet Lake PCH-LP cAVS                                               | 8         | 8.6%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 5.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 4.3%    |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 4.3%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 4.3%    |
| Intel 8 Series HD Audio Controller                                         | 4         | 4.3%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 3.23%   |
| AMD FCH Azalia Controller                                                  | 3         | 3.23%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 2.15%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 2.15%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 2.15%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 2.15%   |
| AMD Trinity HDMI Audio Controller                                          | 2         | 2.15%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 2.15%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.15%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 2.15%   |
| XMOS xCORE USB Audio 2.0                                                   | 1         | 1.08%   |
| Shure MV5                                                                  | 1         | 1.08%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 1.08%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 1.08%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 1.08%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 1.08%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.08%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 1.08%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.08%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 1.08%   |
| Nvidia GF116 High Definition Audio Controller                              | 1         | 1.08%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.08%   |
| Micronas QSB                                                               | 1         | 1.08%   |
| M-Audio M-Audio Fast Track MKII                                            | 1         | 1.08%   |
| Logitech Headset H340                                                      | 1         | 1.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 1.08%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.08%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1.08%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.08%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1         | 1.08%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.08%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 1.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.08%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 9         | 28.13%  |
| Unknown             | 5         | 15.63%  |
| Samsung Electronics | 5         | 15.63%  |
| Crucial             | 4         | 12.5%   |
| Toshiba             | 2         | 6.25%   |
| Micron Technology   | 2         | 6.25%   |
| Smart               | 1         | 3.13%   |
| Ramaxel Technology  | 1         | 3.13%   |
| Kingston            | 1         | 3.13%   |
| G.Skill             | 1         | 3.13%   |
| Elpida              | 1         | 3.13%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 3         | 8.82%   |
| Crucial RAM CT16G4SFD824A.M16FRS 16GB SODIMM DDR4 2400MT/s       | 2         | 5.88%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 2.94%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 2.94%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 2.94%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                             | 1         | 2.94%   |
| Unknown RAM Module 16384MB 2133MT/s                              | 1         | 2.94%   |
| Toshiba RAM 9905711-015.A00G 4GB SODIMM DDR4 2400MT/s            | 1         | 2.94%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s               | 1         | 2.94%   |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 1066MT/s             | 1         | 2.94%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s            | 1         | 2.94%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 2.94%   |
| SK hynix RAM Module 4GB DIMM DDR3 1066MT/s                       | 1         | 2.94%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 2.94%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 2.94%   |
| SK hynix RAM HMP125U6EFR8C-S6 2GB DIMM DDR2 800MT/s              | 1         | 2.94%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 2.94%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 2.94%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 2.94%   |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 2.94%   |
| SK hynix RAM H9CCNNNBLTALAR-NTD 4GB Row Of Chips LPDDR3 1600MT/s | 1         | 2.94%   |
| Samsung RAM Module 4GB SODIMM LPDDR3 1867MT/s                    | 1         | 2.94%   |
| Samsung RAM K4A8G165WC-BCTD 4GB SODIMM DDR4 2667MT/s             | 1         | 2.94%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s          | 1         | 2.94%   |
| Micron RAM 16HTF25664AZ-800H1 2GB DIMM DDR2 800MT/s              | 1         | 2.94%   |
| Micron RAM 16ATF2G64HZ-2G3B1 16GB SODIMM DDR4 2400MT/s           | 1         | 2.94%   |
| Kingston RAM 9905471-011.A00LF 4GB DIMM DDR3 1600MT/s            | 1         | 2.94%   |
| G.Skill RAM F3-14900CL8-4GBXM 4GB DIMM DDR3 1600MT/s             | 1         | 2.94%   |
| Elpida RAM EBJ21UE8BDS0-AE-F 2GB SODIMM DDR3 1067MT/s            | 1         | 2.94%   |
| Crucial RAM CT4G4SFS8213.C8FBD1 4GB SODIMM DDR4 2133MT/s         | 1         | 2.94%   |
| Crucial RAM CT16G4S24AM.M16FE 16GB SODIMM DDR4 2400MT/s          | 1         | 2.94%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 12        | 42.86%  |
| DDR3    | 9         | 32.14%  |
| LPDDR3  | 3         | 10.71%  |
| DDR2    | 2         | 7.14%   |
| Unknown | 2         | 7.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 19        | 67.86%  |
| DIMM         | 6         | 21.43%  |
| Row Of Chips | 2         | 7.14%   |
| Unknown      | 1         | 3.57%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 15        | 50%     |
| 16384 | 5         | 16.67%  |
| 8192  | 5         | 16.67%  |
| 32768 | 3         | 10%     |
| 2048  | 2         | 6.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 9         | 30%     |
| 2667  | 7         | 23.33%  |
| 2400  | 5         | 16.67%  |
| 2133  | 2         | 6.67%   |
| 1867  | 2         | 6.67%   |
| 1066  | 2         | 6.67%   |
| 1333  | 1         | 3.33%   |
| 1067  | 1         | 3.33%   |
| 800   | 1         | 3.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Brother Industries | 2         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Brother MFC-J5330DW  | 1         | 50%     |
| Brother DCP-L3550CDW | 1         | 50%     |

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
| Apple                                  | 7         | 17.07%  |
| Realtek Semiconductor                  | 6         | 14.63%  |
| Chicony Electronics                    | 5         | 12.2%   |
| Alcor Micro                            | 5         | 12.2%   |
| Acer                                   | 4         | 9.76%   |
| Sunplus Innovation Technology          | 3         | 7.32%   |
| Suyin                                  | 2         | 4.88%   |
| Silicon Motion                         | 1         | 2.44%   |
| Quanta                                 | 1         | 2.44%   |
| Microdia                               | 1         | 2.44%   |
| Lite-On Technology                     | 1         | 2.44%   |
| IMC Networks                           | 1         | 2.44%   |
| Google                                 | 1         | 2.44%   |
| Genesys Logic                          | 1         | 2.44%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.44%   |
| Bison Electronics                      | 1         | 2.44%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Apple Built-in iSight                                                      | 4         | 9.52%   |
| Alcor Micro HD WebCam                                                      | 4         | 9.52%   |
| Realtek USB Camera                                                         | 2         | 4.76%   |
| Chicony HD User Facing                                                     | 2         | 4.76%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 2         | 4.76%   |
| Acer Integrated Camera                                                     | 2         | 4.76%   |
| Suyin HP Wide Vision FHD Camera                                            | 1         | 2.38%   |
| Suyin HP Integrated Webcam                                                 | 1         | 2.38%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 2.38%   |
| Sunplus Integrated Camera                                                  | 1         | 2.38%   |
| Sunplus HD WebCam                                                          | 1         | 2.38%   |
| Silicon Motion WebCam SC-13HDL12131N                                       | 1         | 2.38%   |
| Realtek Lenovo EasyCamera                                                  | 1         | 2.38%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 2.38%   |
| Realtek Integrated Webcam                                                  | 1         | 2.38%   |
| Realtek HP Truevision HD                                                   | 1         | 2.38%   |
| Quanta HD Camera                                                           | 1         | 2.38%   |
| Microdia HP Integrated Webcam                                              | 1         | 2.38%   |
| Lite-On Integrated Camera                                                  | 1         | 2.38%   |
| IMC Networks Lenovo EasyCamera                                             | 1         | 2.38%   |
| Genesys Logic Camera                                                       | 1         | 2.38%   |
| Chicony USB2.0 UVC WebCam                                                  | 1         | 2.38%   |
| Chicony LG HD WebCam                                                       | 1         | 2.38%   |
| Chicony Integrated Camera                                                  | 1         | 2.38%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 1         | 2.38%   |
| Bison SunplusIT Integrated Camera                                          | 1         | 2.38%   |
| Apple iBridge                                                              | 1         | 2.38%   |
| Apple FaceTime HD Camera (Built-in)                                        | 1         | 2.38%   |
| Alcor Micro HP Webcam-101                                                  | 1         | 2.38%   |
| Acer Lenovo EasyCamera                                                     | 1         | 2.38%   |
| Acer BisonCam, NB Pro                                                      | 1         | 2.38%   |
| Unknown                                                                    | 1         | 2.38%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 5         | 55.56%  |
| LighTuning Technology | 2         | 22.22%  |
| Synaptics             | 1         | 11.11%  |
| STMicroelectronics    | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
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

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Purism, SPC               | 4         | 44.44%  |
| Realtek Semiconductor     | 1         | 11.11%  |
| O2 Micro                  | 1         | 11.11%  |
| Clay Logic                | 1         | 11.11%  |
| Alcor Micro               | 1         | 11.11%  |
| Aladdin Knowledge Systems | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Purism, SPC Librem Key                            | 4         | 44.44%  |
| Realtek Semiconductor Smart Card Reader Interface | 1         | 11.11%  |
| O2 Micro Oz776 SmartCard Reader                   | 1         | 11.11%  |
| Clay Logic Nitrokey Pro                           | 1         | 11.11%  |
| Alcor Micro AU9540 Smartcard Reader               | 1         | 11.11%  |
| Aladdin Knowledge Systems Token JC                | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 41        | 56.16%  |
| 1     | 23        | 31.51%  |
| 2     | 6         | 8.22%   |
| 3     | 2         | 2.74%   |
| 4     | 1         | 1.37%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 13        | 30.23%  |
| Fingerprint reader    | 9         | 20.93%  |
| Bluetooth             | 8         | 18.6%   |
| Graphics card         | 6         | 13.95%  |
| Multimedia controller | 4         | 9.3%    |
| Chipcard              | 2         | 4.65%   |
| Camera                | 1         | 2.33%   |

