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

Total: 115

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Fujitsu       | LIFEBOOK T939               | Convertible | [86ef7e71ee](https://linux-hardware.org/?probe=86ef7e71ee) | Dec 31, 2024 |
| Wortmann      | TERRA_PC                    | Desktop     | [671f5d50a6](https://linux-hardware.org/?probe=671f5d50a6) | Dec 15, 2024 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [2c206de4b3](https://linux-hardware.org/?probe=2c206de4b3) | Dec 10, 2024 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [f20f71ea7f](https://linux-hardware.org/?probe=f20f71ea7f) | Dec 10, 2024 |
| Intel         | powered classmate PC        | Notebook    | [f3e434817c](https://linux-hardware.org/?probe=f3e434817c) | Nov 01, 2024 |
| Fujitsu       | LIFEBOOK T939               | Convertible | [8022eca94b](https://linux-hardware.org/?probe=8022eca94b) | Oct 08, 2024 |
| Irbis         | NB131                       | Convertible | [a54c081020](https://linux-hardware.org/?probe=a54c081020) | Aug 24, 2024 |
| Purism        | Librem 5r4                  | Notebook    | [e1a4890c78](https://linux-hardware.org/?probe=e1a4890c78) | May 28, 2024 |
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
| PureOS 10   | 30        | 37.5%   |
| PureOS 10.0 | 22        | 27.5%   |
| PureOS 9.0  | 13        | 16.25%  |
| PureOS 10.x | 9         | 11.25%  |
| PureOS 9    | 3         | 3.75%   |
| PureOS 8    | 3         | 3.75%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| PureOS | 75        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                          | Computers | Percent |
|----------------------------------|-----------|---------|
| 4.19.0-5-amd64                   | 10        | 11.36%  |
| 5.10.0-14-amd64                  | 8         | 9.09%   |
| 5.10.0-23-amd64                  | 7         | 7.95%   |
| 5.10.0-13-amd64                  | 5         | 5.68%   |
| 5.10.0-8-amd64                   | 4         | 4.55%   |
| 5.10.0-33-amd64                  | 4         | 4.55%   |
| 5.10.0-21-amd64                  | 4         | 4.55%   |
| 5.10.0-11-amd64                  | 4         | 4.55%   |
| 4.19.0-14-amd64                  | 4         | 4.55%   |
| 5.10.0-28-amd64                  | 3         | 3.41%   |
| 5.10.0-27-amd64                  | 3         | 3.41%   |
| 5.10.0-26-amd64                  | 3         | 3.41%   |
| 6.1.0-1-librem5                  | 2         | 2.27%   |
| 5.7.0-1-librem5                  | 2         | 2.27%   |
| 5.10.0-9-amd64                   | 2         | 2.27%   |
| 5.10.0-7-amd64                   | 2         | 2.27%   |
| 5.10.0-19-amd64                  | 2         | 2.27%   |
| 5.10.0-16-amd64                  | 2         | 2.27%   |
| 6.6.0-1-librem5                  | 1         | 1.14%   |
| 6.1.66-x64v2-xanmod1             | 1         | 1.14%   |
| 6.0.0-1-librem5                  | 1         | 1.14%   |
| 5.9-sunxi64                      | 1         | 1.14%   |
| 5.8-sunxi64                      | 1         | 1.14%   |
| 5.7.0-0.38-1-pinebookpro-hwaccel | 1         | 1.14%   |
| 5.15.0-2-amd64                   | 1         | 1.14%   |
| 5.10.0-6-amd64                   | 1         | 1.14%   |
| 5.10.0-32-amd64                  | 1         | 1.14%   |
| 5.10.0-25-amd64                  | 1         | 1.14%   |
| 5.10.0-20-amd64                  | 1         | 1.14%   |
| 5.10.0-18-amd64                  | 1         | 1.14%   |
| 5.10.0-17-amd64                  | 1         | 1.14%   |
| 5.10.0-15-amd64                  | 1         | 1.14%   |
| 5.10.0-12-amd64                  | 1         | 1.14%   |
| 4.19.72-imx8-sr                  | 1         | 1.14%   |
| 4.16.0-1-amd64                   | 1         | 1.14%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 53        | 66.25%  |
| 4.19.0  | 14        | 17.5%   |
| 5.7.0   | 3         | 3.75%   |
| 6.1.0   | 2         | 2.5%    |
| 6.6.0   | 1         | 1.25%   |
| 6.1.66  | 1         | 1.25%   |
| 6.0.0   | 1         | 1.25%   |
| 5.9     | 1         | 1.25%   |
| 5.8     | 1         | 1.25%   |
| 5.15.0  | 1         | 1.25%   |
| 4.19.72 | 1         | 1.25%   |
| 4.16.0  | 1         | 1.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 53        | 67.09%  |
| 4.19    | 15        | 18.99%  |
| 6.1     | 3         | 3.8%    |
| 5.7     | 3         | 3.8%    |
| 6.6     | 1         | 1.27%   |
| 6.0     | 1         | 1.27%   |
| 5.15    | 1         | 1.27%   |
| 5       | 1         | 1.27%   |
| 4.16    | 1         | 1.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 67        | 89.33%  |
| aarch64 | 8         | 10.67%  |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 63        | 80.77%  |
| Unknown         | 6         | 7.69%   |
| KDE5            | 5         | 6.41%   |
| Phosh:GNOME     | 2         | 2.56%   |
| MATE            | 1         | 1.28%   |
| GNOME Flashback | 1         | 1.28%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 56        | 69.14%  |
| X11     | 14        | 17.28%  |
| Unknown | 6         | 7.41%   |
| Tty     | 5         | 6.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 41        | 53.25%  |
| GDM     | 23        | 29.87%  |
| GDM3    | 10        | 12.99%  |
| SDDM    | 3         | 3.9%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 32        | 41.03%  |
| de_DE   | 9         | 11.54%  |
| en_GB   | 5         | 6.41%   |
| Unknown | 4         | 5.13%   |
| ru_RU   | 3         | 3.85%   |
| pl_PL   | 3         | 3.85%   |
| it_IT   | 3         | 3.85%   |
| C       | 3         | 3.85%   |
| pt_BR   | 2         | 2.56%   |
| fr_FR   | 2         | 2.56%   |
| es_ES   | 2         | 2.56%   |
| es_AR   | 2         | 2.56%   |
| en_AU   | 2         | 2.56%   |
| zh_CN   | 1         | 1.28%   |
| pt_PT   | 1         | 1.28%   |
| hu_HU   | 1         | 1.28%   |
| es_CR   | 1         | 1.28%   |
| en_IL   | 1         | 1.28%   |
| bg_BG   | 1         | 1.28%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 61        | 80.26%  |
| EFI  | 15        | 19.74%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 69        | 92%     |
| Overlay | 2         | 2.67%   |
| Unknown | 2         | 2.67%   |
| Ext2    | 1         | 1.33%   |
| Btrfs   | 1         | 1.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 40        | 51.95%  |
| GPT     | 19        | 24.68%  |
| MBR     | 18        | 23.38%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 60        | 78.95%  |
| Yes       | 16        | 21.05%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 67        | 89.33%  |
| Yes       | 8         | 10.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Purism              | 18        | 24%     |
| Lenovo              | 9         | 12%     |
| Apple               | 9         | 12%     |
| Dell                | 6         | 8%      |
| Hewlett-Packard     | 5         | 6.67%   |
| ASUSTek Computer    | 4         | 5.33%   |
| Unknown             | 3         | 4%      |
| Pine Microsystems   | 2         | 2.67%   |
| Gigabyte Technology | 2         | 2.67%   |
| Acer                | 2         | 2.67%   |
| Wortmann AG         | 1         | 1.33%   |
| Toshiba             | 1         | 1.33%   |
| Shuttle             | 1         | 1.33%   |
| Samsung Electronics | 1         | 1.33%   |
| PCWare              | 1         | 1.33%   |
| Notebook            | 1         | 1.33%   |
| MSI                 | 1         | 1.33%   |
| Microsoft           | 1         | 1.33%   |
| LG Electronics      | 1         | 1.33%   |
| Irbis               | 1         | 1.33%   |
| Intel               | 1         | 1.33%   |
| HUAWEI              | 1         | 1.33%   |
| Google              | 1         | 1.33%   |
| Fujitsu             | 1         | 1.33%   |
| Chuwi               | 1         | 1.33%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Purism Librem 14                         | 6         | 8%      |
| Unknown                                  | 3         | 4%      |
| Purism Librem 5r4                        | 2         | 2.67%   |
| Purism Librem 15 v4                      | 2         | 2.67%   |
| Purism Librem 15 v3                      | 2         | 2.67%   |
| Purism Librem 13 v4                      | 2         | 2.67%   |
| HP Pavilion g6                           | 2         | 2.67%   |
| Wortmann AG TERRA_PC                     | 1         | 1.33%   |
| Toshiba Satellite L500D                  | 1         | 1.33%   |
| Shuttle DS10U                            | 1         | 1.33%   |
| Samsung 530U3C/530U4C/532U3C             | 1         | 1.33%   |
| Purism librem_mini_v2                    | 1         | 1.33%   |
| Purism librem_13v2                       | 1         | 1.33%   |
| Purism Librem 5                          | 1         | 1.33%   |
| Purism Librem 13 v2                      | 1         | 1.33%   |
| Pine Microsystems Pine64 PinePhone (1.2) | 1         | 1.33%   |
| Pine Microsystems Pine64 Pinebook Pro    | 1         | 1.33%   |
| PCWare IPX4005G                          | 1         | 1.33%   |
| Notebook P17SM                           | 1         | 1.33%   |
| MSI MS-7788                              | 1         | 1.33%   |
| Microsoft Surface Book 2                 | 1         | 1.33%   |
| LG 22V280-L.BY31P1                       | 1         | 1.33%   |
| Lenovo ThinkPad T540p 20BFS23T00         | 1         | 1.33%   |
| Lenovo ThinkPad T440p                    | 1         | 1.33%   |
| Lenovo ThinkPad T440 20B60044RT          | 1         | 1.33%   |
| Lenovo ThinkPad P50 20ENCTO1WW           | 1         | 1.33%   |
| Lenovo ThinkPad E480 20KN003SUS          | 1         | 1.33%   |
| Lenovo ThinkPad 13 2nd Gen 20J2S00G00    | 1         | 1.33%   |
| Lenovo IdeaPad U430 Touch 20270          | 1         | 1.33%   |
| Lenovo G450 2949                         | 1         | 1.33%   |
| Lenovo B50-70 20384                      | 1         | 1.33%   |
| Irbis NB131                              | 1         | 1.33%   |
| Intel powered classmate PC               | 1         | 1.33%   |
| HUAWEI NBLB-WAX9N                        | 1         | 1.33%   |
| HP Spectre x360 Convertible              | 1         | 1.33%   |
| HP Pavilion Notebook                     | 1         | 1.33%   |
| HP Laptop 15s-du3xxx                     | 1         | 1.33%   |
| Google Droid                             | 1         | 1.33%   |
| Gigabyte GA-MA78GM-UD2H                  | 1         | 1.33%   |
| Gigabyte B85M-DS3H                       | 1         | 1.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Purism librem            | 18        | 24%     |
| Lenovo ThinkPad          | 6         | 8%      |
| HP Pavilion              | 3         | 4%      |
| Dell Inspiron            | 3         | 4%      |
| Unknown                  | 3         | 4%      |
| Pine Microsystems Pine64 | 2         | 2.67%   |
| Wortmann AG TERRA        | 1         | 1.33%   |
| Toshiba Satellite        | 1         | 1.33%   |
| Shuttle DS10U            | 1         | 1.33%   |
| Samsung 530U3C           | 1         | 1.33%   |
| PCWare IPX4005G          | 1         | 1.33%   |
| Notebook P17SM           | 1         | 1.33%   |
| MSI MS-7788              | 1         | 1.33%   |
| Microsoft Surface        | 1         | 1.33%   |
| LG 22V280-L.BY31P1       | 1         | 1.33%   |
| Lenovo IdeaPad           | 1         | 1.33%   |
| Lenovo G450              | 1         | 1.33%   |
| Lenovo B50-70            | 1         | 1.33%   |
| Irbis NB131              | 1         | 1.33%   |
| Intel powered            | 1         | 1.33%   |
| HUAWEI NBLB-WAX9N        | 1         | 1.33%   |
| HP Spectre               | 1         | 1.33%   |
| HP Laptop                | 1         | 1.33%   |
| Google Droid             | 1         | 1.33%   |
| Gigabyte GA-MA78GM-UD2H  | 1         | 1.33%   |
| Gigabyte B85M-DS3H       | 1         | 1.33%   |
| Fujitsu LIFEBOOK         | 1         | 1.33%   |
| Dell XPS                 | 1         | 1.33%   |
| Dell OptiPlex            | 1         | 1.33%   |
| Dell Latitude            | 1         | 1.33%   |
| Chuwi Hi10               | 1         | 1.33%   |
| ASUS M4N68T              | 1         | 1.33%   |
| ASUS F2A85-M             | 1         | 1.33%   |
| ASUS EX-A320M-GAMING     | 1         | 1.33%   |
| ASUS A88X-PLUS           | 1         | 1.33%   |
| Apple Macmini6           | 1         | 1.33%   |
| Apple MacBookPro6        | 1         | 1.33%   |
| Apple MacBookPro14       | 1         | 1.33%   |
| Apple MacBookAir7        | 1         | 1.33%   |
| Apple MacBook9           | 1         | 1.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 10        | 13.33%  |
| 2021    | 8         | 10.67%  |
| 2013    | 8         | 10.67%  |
| 2017    | 7         | 9.33%   |
| 2019    | 6         | 8%      |
| 2018    | 5         | 6.67%   |
| 2020    | 4         | 5.33%   |
| 2016    | 4         | 5.33%   |
| 2015    | 4         | 5.33%   |
| 2009    | 4         | 5.33%   |
| 2014    | 3         | 4%      |
| 2012    | 3         | 4%      |
| 2011    | 3         | 4%      |
| 2007    | 3         | 4%      |
| 2010    | 2         | 2.67%   |
| 2023    | 1         | 1.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 48        | 64%     |
| Desktop        | 13        | 17.33%  |
| All in one     | 4         | 5.33%   |
| System on chip | 3         | 4%      |
| Convertible    | 3         | 4%      |
| Tablet         | 2         | 2.67%   |
| Phone          | 1         | 1.33%   |
| Mini pc        | 1         | 1.33%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 75        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 58        | 77.33%  |
| Yes  | 17        | 22.67%  |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 16        | 21.33%  |
| 3.01-4.0    | 15        | 20%     |
| 4.01-8.0    | 14        | 18.67%  |
| 8.01-16.0   | 14        | 18.67%  |
| 32.01-64.0  | 7         | 9.33%   |
| 2.01-3.0    | 4         | 5.33%   |
| 1.01-2.0    | 3         | 4%      |
| 24.01-32.0  | 1         | 1.33%   |
| 64.01-256.0 | 1         | 1.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 24        | 28.24%  |
| 2.01-3.0  | 23        | 27.06%  |
| 4.01-8.0  | 16        | 18.82%  |
| 3.01-4.0  | 16        | 18.82%  |
| 8.01-16.0 | 4         | 4.71%   |
| 0.51-1.0  | 1         | 1.18%   |
| 0.01-0.5  | 1         | 1.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 52        | 67.53%  |
| 2      | 18        | 23.38%  |
| 0      | 4         | 5.19%   |
| 3      | 2         | 2.6%    |
| 5      | 1         | 1.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 61        | 80.26%  |
| Yes       | 15        | 19.74%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 57        | 76%     |
| No        | 18        | 24%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 58        | 77.33%  |
| No        | 17        | 22.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 60%     |
| No        | 30        | 40%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 15        | 19.48%  |
| Germany                | 12        | 15.58%  |
| UK                     | 6         | 7.79%   |
| Brazil                 | 6         | 7.79%   |
| Russia                 | 4         | 5.19%   |
| Italy                  | 4         | 5.19%   |
| Poland                 | 3         | 3.9%    |
| Canada                 | 3         | 3.9%    |
| Australia              | 3         | 3.9%    |
| Spain                  | 2         | 2.6%    |
| France                 | 2         | 2.6%    |
| Argentina              | 2         | 2.6%    |
| Turkey                 | 1         | 1.3%    |
| Sri Lanka              | 1         | 1.3%    |
| South Africa           | 1         | 1.3%    |
| Serbia                 | 1         | 1.3%    |
| Portugal               | 1         | 1.3%    |
| Paraguay               | 1         | 1.3%    |
| Pakistan               | 1         | 1.3%    |
| Martinique             | 1         | 1.3%    |
| Israel                 | 1         | 1.3%    |
| Iran                   | 1         | 1.3%    |
| Greece                 | 1         | 1.3%    |
| Costa Rica             | 1         | 1.3%    |
| China                  | 1         | 1.3%    |
| Bulgaria               | 1         | 1.3%    |
| Bosnia and Herzegovina | 1         | 1.3%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Stuttgart              | 3         | 3.66%   |
| Porto Alegre           | 3         | 3.66%   |
| Warsaw                 | 2         | 2.44%   |
| New York               | 2         | 2.44%   |
| London                 | 2         | 2.44%   |
| Berlin                 | 2         | 2.44%   |
| Yuzhnoural'sk          | 1         | 1.22%   |
| Wixom                  | 1         | 1.22%   |
| Windsor                | 1         | 1.22%   |
| Vista                  | 1         | 1.22%   |
| Vancouver              | 1         | 1.22%   |
| Troy                   | 1         | 1.22%   |
| Tomsk                  | 1         | 1.22%   |
| Thorpe Hamlet          | 1         | 1.22%   |
| Tel Aviv               | 1         | 1.22%   |
| Stolberg               | 1         | 1.22%   |
| Stargard               | 1         | 1.22%   |
| Spencer                | 1         | 1.22%   |
| Sofia                  | 1         | 1.22%   |
| Seattle                | 1         | 1.22%   |
| Sao Paulo              | 1         | 1.22%   |
| Sant Cugat del Vallès | 1         | 1.22%   |
| San Jose               | 1         | 1.22%   |
| Roetgen                | 1         | 1.22%   |
| Plano                  | 1         | 1.22%   |
| Perth                  | 1         | 1.22%   |
| Paris                  | 1         | 1.22%   |
| Nizhnekamsk            | 1         | 1.22%   |
| Montreal               | 1         | 1.22%   |
| Milwaukee              | 1         | 1.22%   |
| Milpitas               | 1         | 1.22%   |
| Milan                  | 1         | 1.22%   |
| Melbourne              | 1         | 1.22%   |
| Mankato                | 1         | 1.22%   |
| Madrid                 | 1         | 1.22%   |
| Liverpool              | 1         | 1.22%   |
| Lenningen              | 1         | 1.22%   |
| Leeds                  | 1         | 1.22%   |
| Landau                 | 1         | 1.22%   |
| Lambeth                | 1         | 1.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 22        | 30     | 25%     |
| Unknown             | 8         | 12     | 9.09%   |
| Seagate             | 8         | 17     | 9.09%   |
| WDC                 | 6         | 7      | 6.82%   |
| SanDisk             | 6         | 6      | 6.82%   |
| Apple               | 6         | 8      | 6.82%   |
| Kingston            | 3         | 4      | 3.41%   |
| HGST                | 3         | 3      | 3.41%   |
| Crucial             | 3         | 5      | 3.41%   |
| A-DATA Technology   | 3         | 4      | 3.41%   |
| Win Memory          | 1         | 1      | 1.14%   |
| Transcend           | 1         | 1      | 1.14%   |
| Toshiba             | 1         | 1      | 1.14%   |
| Team                | 1         | 1      | 1.14%   |
| Qumo                | 1         | 1      | 1.14%   |
| PNY                 | 1         | 2      | 1.14%   |
| Plextor             | 1         | 1      | 1.14%   |
| Phison              | 1         | 1      | 1.14%   |
| Patriot             | 1         | 1      | 1.14%   |
| Mushkin             | 1         | 1      | 1.14%   |
| Maxtor              | 1         | 1      | 1.14%   |
| JMicron Technology  | 1         | 1      | 1.14%   |
| Intenso             | 1         | 2      | 1.14%   |
| Intel               | 1         | 1      | 1.14%   |
| Hitachi             | 1         | 1      | 1.14%   |
| China               | 1         | 3      | 1.14%   |
| BIWIN               | 1         | 1      | 1.14%   |
| ASMT                | 1         | 2      | 1.14%   |
| ADATA Technology    | 1         | 1      | 1.14%   |
| Unknown             | 1         | 2      | 1.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  64GB                              | 2         | 2.06%   |
| Unknown MMC Card  32GB                              | 2         | 2.06%   |
| Seagate ST1000LM048-2E7172 1TB                      | 2         | 2.06%   |
| Samsung SSD 970 PRO 1TB                             | 2         | 2.06%   |
| Samsung SSD 860 EVO 500GB                           | 2         | 2.06%   |
| Samsung SSD 860 EVO 250GB                           | 2         | 2.06%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 2         | 2.06%   |
| Crucial CT250MX500SSD4 250GB                        | 2         | 2.06%   |
| Win Memory SWR256G-201II 256GB                      | 1         | 1.03%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1         | 1.03%   |
| WDC WDS100T2B0C-00PXH0 1TB                          | 1         | 1.03%   |
| WDC WDBNCE2500PNC 250GB SSD                         | 1         | 1.03%   |
| WDC WD5000LPCX-22VHAT0 500GB                        | 1         | 1.03%   |
| WDC WD5000AZRX-00A8LB0 500GB                        | 1         | 1.03%   |
| WDC WD3200AAJS-40RYA0 320GB                         | 1         | 1.03%   |
| Unknown SH64G  64GB                                 | 1         | 1.03%   |
| Unknown MMC Card  16GB                              | 1         | 1.03%   |
| Unknown DA4128  128GB                               | 1         | 1.03%   |
| Unknown AFGCF  128GB                                | 1         | 1.03%   |
| Unknown 8GTF4R  8GB                                 | 1         | 1.03%   |
| Unknown 032G32  32GB                                | 1         | 1.03%   |
| Transcend TS240GMTS420S 240GB SSD                   | 1         | 1.03%   |
| Toshiba NVMe SSD Drive 512GB                        | 1         | 1.03%   |
| Team TM8FP6256G 256GB                               | 1         | 1.03%   |
| Seagate ST480HM000-1G5162 506GB                     | 1         | 1.03%   |
| Seagate ST3500630AS 500GB                           | 1         | 1.03%   |
| Seagate ST3320418AS 320GB                           | 1         | 1.03%   |
| Seagate ST3250410AS 250GB                           | 1         | 1.03%   |
| Seagate ST3250312CS 250GB                           | 1         | 1.03%   |
| Seagate ST31000524AS 1TB                            | 1         | 1.03%   |
| Seagate ST1000DM003-1ER162 1TB                      | 1         | 1.03%   |
| Seagate ST1000DM003-1CH162 1TB                      | 1         | 1.03%   |
| Seagate NVMe SSD Drive 2TB                          | 1         | 1.03%   |
| SanDisk SSD i100 24GB                               | 1         | 1.03%   |
| SanDisk SDSSDP128G 128GB                            | 1         | 1.03%   |
| SanDisk SDSSDH3500G 500GB                           | 1         | 1.03%   |
| SanDisk NVMe SSD Drive 500GB                        | 1         | 1.03%   |
| SanDisk DF4128  128GB                               | 1         | 1.03%   |
| SanDisk DF4032  32GB                                | 1         | 1.03%   |
| Samsung SSD 970 EVO Plus 500GB                      | 1         | 1.03%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 16     | 33.33%  |
| WDC                 | 3         | 3      | 14.29%  |
| HGST                | 3         | 3      | 14.29%  |
| Apple               | 3         | 3      | 14.29%  |
| Samsung Electronics | 2         | 2      | 9.52%   |
| Maxtor              | 1         | 1      | 4.76%   |
| JMicron Technology  | 1         | 1      | 4.76%   |
| Hitachi             | 1         | 1      | 4.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 12     | 25%     |
| SanDisk             | 3         | 3      | 8.33%   |
| Kingston            | 3         | 4      | 8.33%   |
| Crucial             | 3         | 5      | 8.33%   |
| A-DATA Technology   | 3         | 4      | 8.33%   |
| WDC                 | 2         | 3      | 5.56%   |
| Win Memory          | 1         | 1      | 2.78%   |
| Transcend           | 1         | 1      | 2.78%   |
| Qumo                | 1         | 1      | 2.78%   |
| PNY                 | 1         | 2      | 2.78%   |
| Plextor             | 1         | 1      | 2.78%   |
| Patriot             | 1         | 1      | 2.78%   |
| Mushkin             | 1         | 1      | 2.78%   |
| Intenso             | 1         | 2      | 2.78%   |
| Intel               | 1         | 1      | 2.78%   |
| China               | 1         | 3      | 2.78%   |
| BIWIN               | 1         | 1      | 2.78%   |
| ASMT                | 1         | 2      | 2.78%   |
| Apple               | 1         | 1      | 2.78%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 32        | 49     | 38.1%   |
| NVMe    | 21        | 27     | 25%     |
| HDD     | 20        | 30     | 23.81%  |
| MMC     | 10        | 14     | 11.9%   |
| Unknown | 1         | 2      | 1.19%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 46        | 77     | 57.5%   |
| NVMe | 21        | 27     | 26.25%  |
| MMC  | 10        | 14     | 12.5%   |
| SAS  | 3         | 4      | 3.75%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 37        | 60     | 74%     |
| 0.51-1.0   | 11        | 16     | 22%     |
| 1.01-2.0   | 2         | 3      | 4%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 38        | 48.72%  |
| 251-500    | 8         | 10.26%  |
| 101-250    | 8         | 10.26%  |
| 21-50      | 6         | 7.69%   |
| 51-100     | 6         | 7.69%   |
| 501-1000   | 4         | 5.13%   |
| Unknown    | 4         | 5.13%   |
| 1001-2000  | 3         | 3.85%   |
| 2001-3000  | 1         | 1.28%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 53        | 67.09%  |
| 21-50    | 14        | 17.72%  |
| Unknown  | 4         | 5.06%   |
| 101-250  | 3         | 3.8%    |
| 501-1000 | 3         | 3.8%    |
| 251-500  | 1         | 1.27%   |
| 51-100   | 1         | 1.27%   |

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
| Detected | 48        | 80     | 60%     |
| Works    | 27        | 35     | 33.75%  |
| Malfunc  | 5         | 7      | 6.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 43        | 58.11%  |
| Samsung Electronics          | 13        | 17.57%  |
| AMD                          | 7         | 9.46%   |
| SanDisk                      | 2         | 2.7%    |
| Nvidia                       | 2         | 2.7%    |
| Apple                        | 2         | 2.7%    |
| Toshiba America Info Systems | 1         | 1.35%   |
| Seagate Technology           | 1         | 1.35%   |
| Phison Electronics           | 1         | 1.35%   |
| MAXIO Technology (Hangzhou)  | 1         | 1.35%   |
| ADATA Technology             | 1         | 1.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 10        | 12.66%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 8         | 10.13%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 6.33%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 5         | 6.33%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 5.06%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 3.8%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 3.8%    |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 2.53%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 2.53%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 2         | 2.53%   |
| Apple S3X NVMe Controller                                                      | 2         | 2.53%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 1.27%   |
| Seagate FireCuda/IronWolf 510 SSD                                              | 1         | 1.27%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                     | 1         | 1.27%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 1         | 1.27%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 1         | 1.27%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 1.27%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 1         | 1.27%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 1.27%   |
| Nvidia MCP61 SATA Controller                                                   | 1         | 1.27%   |
| Nvidia MCP61 IDE                                                               | 1         | 1.27%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 1         | 1.27%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.27%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 1.27%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 1.27%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.27%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.27%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.27%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 1.27%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 1         | 1.27%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 1.27%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 1         | 1.27%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 1         | 1.27%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 1.27%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1         | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1         | 1.27%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 1.27%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 1         | 1.27%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 50        | 65.79%  |
| NVMe | 21        | 27.63%  |
| IDE  | 4         | 5.26%   |
| RAID | 1         | 1.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 60        | 78.95%  |
| AMD     | 7         | 9.21%   |
| ARM     | 6         | 7.89%   |
| Unknown | 3         | 3.95%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-10710U CPU @ 1.10GHz          | 6         | 7.89%   |
| ARM Processor                               | 6         | 7.89%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 5         | 6.58%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 4         | 5.26%   |
|                                             | 3         | 3.95%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 2.63%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 1         | 1.32%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 1.32%   |
| Intel Pentium CPU N4200 @ 1.10GHz           | 1         | 1.32%   |
| Intel Core m5-6Y54 CPU @ 1.10GHz            | 1         | 1.32%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 1.32%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 1.32%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 1.32%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 1.32%   |
| Intel Core i7-7567U CPU @ 3.50GHz           | 1         | 1.32%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 1         | 1.32%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz          | 1         | 1.32%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz          | 1         | 1.32%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 1.32%   |
| Intel Core i7-4510U CPU @ 2.00GHz           | 1         | 1.32%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 1.32%   |
| Intel Core i5-5250U CPU @ 1.60GHz           | 1         | 1.32%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 1         | 1.32%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1         | 1.32%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1         | 1.32%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 1.32%   |
| Intel Core i5-3330S CPU @ 2.70GHz           | 1         | 1.32%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.32%   |
| Intel Core i5-2320 CPU @ 3.00GHz            | 1         | 1.32%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 1         | 1.32%   |
| Intel Core i5 CPU M 540 @ 2.53GHz           | 1         | 1.32%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1         | 1.32%   |
| Intel Core i3-4130T CPU @ 2.90GHz           | 1         | 1.32%   |
| Intel Core i3-4010U CPU @ 1.70GHz           | 1         | 1.32%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 1         | 1.32%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 1         | 1.32%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 1         | 1.32%   |
| Intel Core 2 Duo CPU U7700 @ 1.33GHz        | 1         | 1.32%   |
| Intel Core 2 Duo CPU T7700 @ 2.40GHz        | 1         | 1.32%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz        | 1         | 1.32%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 26        | 34.67%  |
| Intel Core i5           | 13        | 17.33%  |
| Other                   | 9         | 12%     |
| Intel Celeron           | 6         | 8%      |
| Intel Core i3           | 5         | 6.67%   |
| Intel Core 2 Duo        | 4         | 5.33%   |
| AMD A10                 | 2         | 2.67%   |
| Intel Pentium Silver    | 1         | 1.33%   |
| Intel Pentium Dual-Core | 1         | 1.33%   |
| Intel Pentium           | 1         | 1.33%   |
| Intel Core m5           | 1         | 1.33%   |
| Intel Atom              | 1         | 1.33%   |
| AMD Turion II Dual-Core | 1         | 1.33%   |
| AMD Ryzen 5             | 1         | 1.33%   |
| AMD Ryzen 3             | 1         | 1.33%   |
| AMD Athlon II X4        | 1         | 1.33%   |
| AMD Athlon II X3        | 1         | 1.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 39        | 52%     |
| 4       | 28        | 37.33%  |
| 6       | 6         | 8%      |
| 3       | 1         | 1.33%   |
| Unknown | 1         | 1.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 74        | 98.67%  |
| Unknown | 1         | 1.33%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 45        | 60%     |
| 1       | 29        | 38.67%  |
| Unknown | 1         | 1.33%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 71        | 93.42%  |
| Unknown        | 4         | 5.26%   |
| 64-bit         | 1         | 1.32%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 51        | 65.38%  |
| 0x406e3    | 4         | 5.13%   |
| 0xa0660    | 3         | 3.85%   |
| 0x806ec    | 2         | 2.56%   |
| 0x806e9    | 2         | 2.56%   |
| 0x706a1    | 2         | 2.56%   |
| 0x40651    | 2         | 2.56%   |
| 0x1067a    | 2         | 2.56%   |
| 0x806ea    | 1         | 1.28%   |
| 0x806c1    | 1         | 1.28%   |
| 0x506c9    | 1         | 1.28%   |
| 0x406c4    | 1         | 1.28%   |
| 0x306d4    | 1         | 1.28%   |
| 0x206a7    | 1         | 1.28%   |
| 0x08108109 | 1         | 1.28%   |
| 0x06003106 | 1         | 1.28%   |
| 0x06001119 | 1         | 1.28%   |
| 0x010000b6 | 1         | 1.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 15        | 20%     |
| Haswell       | 9         | 12%     |
| Unknown       | 8         | 10.67%  |
| Skylake       | 6         | 8%      |
| CometLake     | 6         | 8%      |
| IvyBridge     | 5         | 6.67%   |
| Penryn        | 3         | 4%      |
| K10           | 3         | 4%      |
| Goldmont plus | 3         | 4%      |
| Zen+          | 2         | 2.67%   |
| Silvermont    | 2         | 2.67%   |
| SandyBridge   | 2         | 2.67%   |
| Goldmont      | 2         | 2.67%   |
| Core          | 2         | 2.67%   |
| Broadwell     | 2         | 2.67%   |
| Westmere      | 1         | 1.33%   |
| TigerLake     | 1         | 1.33%   |
| Steamroller   | 1         | 1.33%   |
| Piledriver    | 1         | 1.33%   |
| Nehalem       | 1         | 1.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 54        | 71.05%  |
| Nvidia | 11        | 14.47%  |
| AMD    | 11        | 14.47%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                    | 7         | 8.75%   |
| Intel Comet Lake UHD Graphics                                                            | 6         | 7.5%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 5%      |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 5%      |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 5%      |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 3.75%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 2.5%    |
| Intel UHD Graphics 620                                                                   | 2         | 2.5%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 2.5%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 2.5%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 2.5%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 2.5%    |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1         | 1.25%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 1.25%   |
| Nvidia GM107GLM [Quadro M2000M]                                                          | 1         | 1.25%   |
| Nvidia GK208M [GeForce GT 730M]                                                          | 1         | 1.25%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 1.25%   |
| Nvidia GK107M [GeForce GT 640M Mac Edition]                                              | 1         | 1.25%   |
| Nvidia GK104M [GeForce GTX 870M]                                                         | 1         | 1.25%   |
| Nvidia GF116 [GeForce GTS 450 Rev. 2]                                                    | 1         | 1.25%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 1         | 1.25%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 1.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 1.25%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.25%   |
| Intel Whiskey Lake-U GT1 [UHD Graphics 610]                                              | 1         | 1.25%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 1         | 1.25%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.25%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.25%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.25%   |
| Intel Iris Plus Graphics 650                                                             | 1         | 1.25%   |
| Intel HD Graphics 630                                                                    | 1         | 1.25%   |
| Intel HD Graphics 6000                                                                   | 1         | 1.25%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.25%   |
| Intel HD Graphics 515                                                                    | 1         | 1.25%   |
| Intel HD Graphics 500                                                                    | 1         | 1.25%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 1.25%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 1.25%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 1         | 1.25%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 45        | 60%     |
| Other          | 9         | 12%     |
| 1 x AMD        | 7         | 9.33%   |
| 1 x Nvidia     | 6         | 8%      |
| Intel + Nvidia | 5         | 6.67%   |
| Intel + AMD    | 2         | 2.67%   |
| 2 x AMD        | 1         | 1.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 64        | 85.33%  |
| Unknown | 11        | 14.67%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 72        | 94.74%  |
| 0.51-1.0   | 2         | 2.63%   |
| 3.01-4.0   | 1         | 1.32%   |
| 1.01-2.0   | 1         | 1.32%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 12        | 15.38%  |
| Samsung Electronics     | 10        | 12.82%  |
| Chimei Innolux          | 10        | 12.82%  |
| LG Display              | 8         | 10.26%  |
| Apple                   | 7         | 8.97%   |
| Philips                 | 3         | 3.85%   |
| Goldstar                | 3         | 3.85%   |
| AU Optronics            | 3         | 3.85%   |
| Unknown                 | 2         | 2.56%   |
| Wacom                   | 1         | 1.28%   |
| ViewSonic               | 1         | 1.28%   |
| Toshiba                 | 1         | 1.28%   |
| Sony                    | 1         | 1.28%   |
| Sharp                   | 1         | 1.28%   |
| RTK                     | 1         | 1.28%   |
| PRI                     | 1         | 1.28%   |
| PANDA                   | 1         | 1.28%   |
| Panasonic               | 1         | 1.28%   |
| Lenovo                  | 1         | 1.28%   |
| InfoVision              | 1         | 1.28%   |
| Iiyama                  | 1         | 1.28%   |
| Grundig                 | 1         | 1.28%   |
| Flipbook                | 1         | 1.28%   |
| Dell                    | 1         | 1.28%   |
| Chi Mei Optoelectronics | 1         | 1.28%   |
| BenQ                    | 1         | 1.28%   |
| ASUSTek Computer        | 1         | 1.28%   |
| AOC                     | 1         | 1.28%   |
| Acer                    | 1         | 1.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC434B 3840x2160 344x194mm 15.5-inch | 3         | 3.85%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 3.85%   |
| BOE LCD Monitor BOE06BE 1920x1080 294x165mm 13.3-inch                 | 3         | 3.85%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 2         | 2.56%   |
| Philips TV PHL5035 1920x1080 640x360mm 28.9-inch                      | 2         | 2.56%   |
| Chimei Innolux LCD Monitor CMN1415 1920x1080 309x173mm 13.9-inch      | 2         | 2.56%   |
| Wacom Cintiq 16 WAC1071 1920x1080 344x193mm 15.5-inch                 | 1         | 1.28%   |
| ViewSonic VA2719 Series VSCC132 1920x1080 598x336mm 27.0-inch         | 1         | 1.28%   |
| Toshiba LCD Monitor LCD3706 1280x800 261x163mm 12.1-inch              | 1         | 1.28%   |
| Sony TV SNYAB03 1920x1080                                             | 1         | 1.28%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch               | 1         | 1.28%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 474x296mm 22.0-inch  | 1         | 1.28%   |
| Samsung Electronics SyncMaster SAM01D3 1440x900 408x225mm 18.3-inch   | 1         | 1.28%   |
| Samsung Electronics SyncMaster SAM0193 1280x1024 376x301mm 19.0-inch  | 1         | 1.28%   |
| Samsung Electronics LS27A800U SAM71A3 3840x2160 597x336mm 27.0-inch   | 1         | 1.28%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch  | 1         | 1.28%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 700x390mm 31.5-inch  | 1         | 1.28%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 1         | 1.28%   |
| RTK LG AIO FHD RTK2136 1920x1080 477x268mm 21.5-inch                  | 1         | 1.28%   |
| PRI Prima TV PRI1600 1920x1080                                        | 1         | 1.28%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 1         | 1.28%   |
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch               | 1         | 1.28%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch           | 1         | 1.28%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 1         | 1.28%   |
| LG Display LCD Monitor LGD053B 1920x1080 294x165mm 13.3-inch          | 1         | 1.28%   |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch          | 1         | 1.28%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 1         | 1.28%   |
| LG Display LCD Monitor LGD03F0 1366x768 310x174mm 14.0-inch           | 1         | 1.28%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch           | 1         | 1.28%   |
| LG Display LCD Monitor LGD034D 1366x768 340x190mm 15.3-inch           | 1         | 1.28%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch           | 1         | 1.28%   |
| Lenovo LEN Y44w-10 LEN65EA 3840x1200 1052x329mm 43.4-inch             | 1         | 1.28%   |
| InfoVision LCD Monitor IVO03FA 1366x768 223x125mm 10.1-inch           | 1         | 1.28%   |
| Iiyama PL2792H IVM664F 1920x1080 598x336mm 27.0-inch                  | 1         | 1.28%   |
| Grundig WXGA GRU4448 1600x1200                                        | 1         | 1.28%   |
| Goldstar IPS231 GSM5817 1920x1080 510x290mm 23.1-inch                 | 1         | 1.28%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch             | 1         | 1.28%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                | 1         | 1.28%   |
| Flipbook NexDock YUKBC34 1920x1080 293x165mm 13.2-inch                | 1         | 1.28%   |
| Dell P2213 DELF042 1680x1050 473x296mm 22.0-inch                      | 1         | 1.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 37        | 50.68%  |
| 1366x768 (WXGA)    | 12        | 16.44%  |
| 3840x2160 (4K)     | 8         | 10.96%  |
| 1680x1050 (WSXGA+) | 3         | 4.11%   |
| 2288x1287          | 2         | 2.74%   |
| 1600x900 (HD+)     | 2         | 2.74%   |
| 1440x900 (WXGA+)   | 2         | 2.74%   |
| 1280x800 (WXGA)    | 2         | 2.74%   |
| 3840x1200          | 1         | 1.37%   |
| 2880x1800          | 1         | 1.37%   |
| 2304x1440          | 1         | 1.37%   |
| 1920x1200 (WUXGA)  | 1         | 1.37%   |
| 1280x1024 (SXGA)   | 1         | 1.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 22        | 28.21%  |
| 15      | 18        | 23.08%  |
| 23      | 4         | 5.13%   |
| 14      | 4         | 5.13%   |
| 27      | 3         | 3.85%   |
| 24      | 3         | 3.85%   |
| 142     | 2         | 2.56%   |
| 31      | 2         | 2.56%   |
| 28      | 2         | 2.56%   |
| 22      | 2         | 2.56%   |
| 21      | 2         | 2.56%   |
| 20      | 2         | 2.56%   |
| 19      | 2         | 2.56%   |
| 17      | 2         | 2.56%   |
| 12      | 2         | 2.56%   |
| 72      | 1         | 1.28%   |
| 54      | 1         | 1.28%   |
| 43      | 1         | 1.28%   |
| 40      | 1         | 1.28%   |
| 10      | 1         | 1.28%   |
| Unknown | 1         | 1.28%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 30        | 38.96%  |
| 201-300        | 15        | 19.48%  |
| 501-600        | 10        | 12.99%  |
| 401-500        | 7         | 9.09%   |
| 601-700        | 4         | 5.19%   |
| 351-400        | 4         | 5.19%   |
| More than 2000 | 2         | 2.6%    |
| 1001-1500      | 2         | 2.6%    |
| 801-900        | 1         | 1.3%    |
| 1501-2000      | 1         | 1.3%    |
| Unknown        | 1         | 1.3%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 54        | 79.41%  |
| 16/10 | 10        | 14.71%  |
| 1.00  | 2         | 2.94%   |
| 5/4   | 1         | 1.47%   |
| 3.20  | 1         | 1.47%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 18        | 23.08%  |
| 81-90          | 16        | 20.51%  |
| 201-250        | 11        | 14.1%   |
| 71-80          | 10        | 12.82%  |
| More than 1000 | 4         | 5.13%   |
| 351-500        | 4         | 5.13%   |
| 151-200        | 4         | 5.13%   |
| 301-350        | 3         | 3.85%   |
| 61-70          | 2         | 2.56%   |
| 501-1000       | 2         | 2.56%   |
| 41-50          | 1         | 1.28%   |
| 131-140        | 1         | 1.28%   |
| 121-130        | 1         | 1.28%   |
| Unknown        | 1         | 1.28%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 23        | 29.49%  |
| 51-100        | 23        | 29.49%  |
| 101-120       | 11        | 14.1%   |
| 161-240       | 10        | 12.82%  |
| More than 240 | 6         | 7.69%   |
| 1-50          | 4         | 5.13%   |
| Unknown       | 1         | 1.28%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 56        | 73.68%  |
| 2     | 9         | 11.84%  |
| 0     | 9         | 11.84%  |
| 3     | 2         | 2.63%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 41        | 35.65%  |
| Qualcomm Atheros                | 20        | 17.39%  |
| Intel                           | 18        | 15.65%  |
| Broadcom                        | 11        | 9.57%   |
| Broadcom Limited                | 4         | 3.48%   |
| ASIX Electronics                | 3         | 2.61%   |
| Qualcomm Atheros Communications | 2         | 1.74%   |
| Nvidia                          | 2         | 1.74%   |
| Marvell Technology Group        | 2         | 1.74%   |
| Xiaomi                          | 1         | 0.87%   |
| Sierra Wireless                 | 1         | 0.87%   |
| Samsung Electronics             | 1         | 0.87%   |
| Ralink Technology               | 1         | 0.87%   |
| Ralink                          | 1         | 0.87%   |
| OPPO Electronics                | 1         | 0.87%   |
| MediaTek                        | 1         | 0.87%   |
| Google                          | 1         | 0.87%   |
| Edimax Technology               | 1         | 0.87%   |
| DisplayLink                     | 1         | 0.87%   |
| D-Link                          | 1         | 0.87%   |
| ASUSTek Computer                | 1         | 0.87%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 25        | 19.08%  |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 14        | 10.69%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 6         | 4.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 4         | 3.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 4         | 3.05%   |
| Intel Wireless 7265                                                           | 4         | 3.05%   |
| Intel Wireless 7260                                                           | 3         | 2.29%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 3         | 2.29%   |
| Qualcomm Atheros AR9271 802.11n                                               | 2         | 1.53%   |
| Intel Ethernet Connection I217-LM                                             | 2         | 1.53%   |
| Intel Ethernet Connection (6) I219-LM                                         | 2         | 1.53%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 2         | 1.53%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2         | 1.53%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter          | 2         | 1.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 1         | 0.76%   |
| Sierra Wireless EM7455                                                        | 1         | 0.76%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1         | 0.76%   |
| Realtek USB 10/100/1G/2.5G LAN                                                | 1         | 0.76%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1         | 0.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.76%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 0.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.76%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 1         | 0.76%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 0.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1         | 0.76%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 0.76%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1         | 0.76%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 1         | 0.76%   |
| Realtek RTL8152 Fast Ethernet Adapter                                         | 1         | 0.76%   |
| Ralink MT7601U Wireless Adapter                                               | 1         | 0.76%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                        | 1         | 0.76%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                        | 1         | 0.76%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 0.76%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 0.76%   |
| OPPO OnePlus Nord 4                                                           | 1         | 0.76%   |
| Nvidia MCP79 Ethernet                                                         | 1         | 0.76%   |
| Nvidia MCP61 Ethernet                                                         | 1         | 0.76%   |
| MediaTek WiFi                                                                 | 1         | 0.76%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                             | 1         | 0.76%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                       | 1         | 0.76%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 20        | 29.85%  |
| Intel                           | 15        | 22.39%  |
| Realtek Semiconductor           | 10        | 14.93%  |
| Broadcom                        | 8         | 11.94%  |
| Broadcom Limited                | 4         | 5.97%   |
| Qualcomm Atheros Communications | 2         | 2.99%   |
| Sierra Wireless                 | 1         | 1.49%   |
| Ralink Technology               | 1         | 1.49%   |
| Ralink                          | 1         | 1.49%   |
| MediaTek                        | 1         | 1.49%   |
| Marvell Technology Group        | 1         | 1.49%   |
| Edimax Technology               | 1         | 1.49%   |
| D-Link                          | 1         | 1.49%   |
| ASUSTek Computer                | 1         | 1.49%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 14        | 20.9%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 4         | 5.97%   |
| Intel Wireless 7265                                                           | 4         | 5.97%   |
| Intel Wireless 7260                                                           | 3         | 4.48%   |
| Qualcomm Atheros AR9271 802.11n                                               | 2         | 2.99%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter          | 2         | 2.99%   |
| Sierra Wireless EM7455                                                        | 1         | 1.49%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1         | 1.49%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.49%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 1.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.49%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 1         | 1.49%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 1.49%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1         | 1.49%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 1.49%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1         | 1.49%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 1         | 1.49%   |
| Ralink MT7601U Wireless Adapter                                               | 1         | 1.49%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                        | 1         | 1.49%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 1.49%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.49%   |
| MediaTek WiFi                                                                 | 1         | 1.49%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                             | 1         | 1.49%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 1.49%   |
| Intel Wireless 8260                                                           | 1         | 1.49%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 1         | 1.49%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1         | 1.49%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 1.49%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 1         | 1.49%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 1.49%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 1         | 1.49%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                                   | 1         | 1.49%   |
| D-Link 802.11ac NIC                                                           | 1         | 1.49%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                                        | 1         | 1.49%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                        | 1         | 1.49%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 1         | 1.49%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                            | 1         | 1.49%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 1         | 1.49%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 1         | 1.49%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                        | 1         | 1.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 36        | 58.06%  |
| Intel                    | 8         | 12.9%   |
| Broadcom                 | 6         | 9.68%   |
| ASIX Electronics         | 3         | 4.84%   |
| Nvidia                   | 2         | 3.23%   |
| Xiaomi                   | 1         | 1.61%   |
| Samsung Electronics      | 1         | 1.61%   |
| Qualcomm Atheros         | 1         | 1.61%   |
| OPPO Electronics         | 1         | 1.61%   |
| Marvell Technology Group | 1         | 1.61%   |
| Google                   | 1         | 1.61%   |
| DisplayLink              | 1         | 1.61%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 25        | 39.06%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 6         | 9.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4         | 6.25%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 4.69%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 3.13%   |
| Intel Ethernet Connection (6) I219-LM                                  | 2         | 3.13%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 2         | 3.13%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2         | 3.13%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 1.56%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 1.56%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 1         | 1.56%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 1.56%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 1.56%   |
| OPPO OnePlus Nord 4                                                    | 1         | 1.56%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 1.56%   |
| Nvidia MCP61 Ethernet                                                  | 1         | 1.56%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 1         | 1.56%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 1.56%   |
| Intel Ethernet Connection I218-V                                       | 1         | 1.56%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 1.56%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 1.56%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 1         | 1.56%   |
| Google Nexus/Pixel Device (tether)                                     | 1         | 1.56%   |
| DisplayLink USB 4K Graphic Docking                                     | 1         | 1.56%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 1         | 1.56%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 1         | 1.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 58        | 50.88%  |
| Ethernet | 56        | 49.12%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 42        | 60%     |
| WiFi     | 28        | 40%     |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 35        | 46.67%  |
| 1     | 27        | 36%     |
| 0     | 11        | 14.67%  |
| 3     | 2         | 2.67%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 58        | 74.36%  |
| Yes  | 20        | 25.64%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 14        | 30.43%  |
| Apple                           | 8         | 17.39%  |
| Qualcomm Atheros Communications | 6         | 13.04%  |
| Lite-On Technology              | 6         | 13.04%  |
| Foxconn / Hon Hai               | 5         | 10.87%  |
| Realtek Semiconductor           | 3         | 6.52%   |
| IMC Networks                    | 1         | 2.17%   |
| Cambridge Silicon Radio         | 1         | 2.17%   |
| Broadcom                        | 1         | 2.17%   |
| ASUSTek Computer                | 1         | 2.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                   | 8         | 17.39%  |
| Lite-On Atheros AR3012 Bluetooth                     | 6         | 13.04%  |
| Foxconn / Hon Hai Bluetooth Device                   | 5         | 10.87%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)       | 3         | 6.52%   |
| Apple Bluetooth USB Host Controller                  | 3         | 6.52%   |
| Apple Bluetooth Host Controller                      | 3         | 6.52%   |
| Qualcomm Atheros  Bluetooth Device                   | 2         | 4.35%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                | 2         | 4.35%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter              | 1         | 2.17%   |
| Realtek RTL8723B Bluetooth                           | 1         | 2.17%   |
| Realtek Bluetooth Radio                              | 1         | 2.17%   |
| Qualcomm Atheros Dell Wireless 1802 Bluetooth 4.0 LE | 1         | 2.17%   |
| Qualcomm Atheros AR9462 Bluetooth                    | 1         | 2.17%   |
| Intel Wireless-AC 9260 Bluetooth Adapter             | 1         | 2.17%   |
| Intel Wireless-AC 3168 Bluetooth                     | 1         | 2.17%   |
| Intel Centrino Bluetooth Wireless Transceiver        | 1         | 2.17%   |
| IMC Networks Bluetooth Radio                         | 1         | 2.17%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)  | 1         | 2.17%   |
| Broadcom HP Portable Valentine                       | 1         | 2.17%   |
| ASUS Broadcom BCM20702A0 Bluetooth                   | 1         | 2.17%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                 | 1         | 2.17%   |
| Apple Bluetooth HCI                                  | 1         | 2.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor    | Computers | Percent |
|-----------|-----------|---------|
| Intel     | 57        | 69.51%  |
| AMD       | 10        | 12.2%   |
| Nvidia    | 9         | 10.98%  |
| XMOS      | 1         | 1.22%   |
| Shure     | 1         | 1.22%   |
| Micronas  | 1         | 1.22%   |
| M-Audio   | 1         | 1.22%   |
| Logitech  | 1         | 1.22%   |
| GN Netcom | 1         | 1.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 15        | 15.46%  |
| Intel Comet Lake PCH-LP cAVS                                               | 8         | 8.25%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 5.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 4.12%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 4.12%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 4.12%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 4.12%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 3.09%   |
| AMD FCH Azalia Controller                                                  | 3         | 3.09%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 2.06%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 2         | 2.06%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 2.06%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 2.06%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 2.06%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 2.06%   |
| AMD Trinity HDMI Audio Controller                                          | 2         | 2.06%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 2.06%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.06%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 2         | 2.06%   |
| XMOS XMOS usb audio                                                        | 1         | 1.03%   |
| Shure MV5                                                                  | 1         | 1.03%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 1.03%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 1.03%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 1.03%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 1.03%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.03%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 1.03%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.03%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 1.03%   |
| Nvidia GF116 High Definition Audio Controller                              | 1         | 1.03%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.03%   |
| Micronas QSB                                                               | 1         | 1.03%   |
| M-Audio M-Audio Fast Track MKII                                            | 1         | 1.03%   |
| Logitech Headset H340                                                      | 1         | 1.03%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 1.03%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 1.03%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 1.03%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1         | 1.03%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.03%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 9         | 25.71%  |
| Unknown             | 5         | 14.29%  |
| Samsung Electronics | 5         | 14.29%  |
| Crucial             | 4         | 11.43%  |
| Micron Technology   | 3         | 8.57%   |
| Toshiba             | 2         | 5.71%   |
| Kingston            | 2         | 5.71%   |
| Unknown (ABCD)      | 1         | 2.86%   |
| Smart               | 1         | 2.86%   |
| Ramaxel Technology  | 1         | 2.86%   |
| G.Skill             | 1         | 2.86%   |
| Elpida              | 1         | 2.86%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 3         | 7.89%   |
| Crucial RAM CT16G4SFD824A.M16FRS 16GB SODIMM DDR4 2400MT/s       | 2         | 5.26%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 2.63%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 2.63%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 2.63%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                             | 1         | 2.63%   |
| Unknown RAM Module 16384MB 2133MT/s                              | 1         | 2.63%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 1         | 2.63%   |
| Toshiba RAM 9905711-015.A00G 4GB SODIMM DDR4 2400MT/s            | 1         | 2.63%   |
| Toshiba RAM 8HTF12864HDY-800G1 4096MB SODIMM 1066MT/s            | 1         | 2.63%   |
| Toshiba RAM 64T128020EDL2.5C2 4096MB SODIMM 1066MT/s             | 1         | 2.63%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s            | 1         | 2.63%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 2.63%   |
| SK hynix RAM Module 4GB DIMM DDR3 1066MT/s                       | 1         | 2.63%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 2667MT/s           | 1         | 2.63%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 2.63%   |
| SK hynix RAM HMP125U6EFR8C-S6 2GB DIMM DDR2 800MT/s              | 1         | 2.63%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 2.63%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 2.63%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 2.63%   |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 2.63%   |
| SK hynix RAM H9CCNNNBLTALAR-NTD 4GB Row Of Chips LPDDR3 1600MT/s | 1         | 2.63%   |
| Samsung RAM Module 4GB SODIMM LPDDR3 1867MT/s                    | 1         | 2.63%   |
| Samsung RAM K4A8G165WC-BCTD 4GB SODIMM DDR4 2667MT/s             | 1         | 2.63%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s          | 1         | 2.63%   |
| Micron RAM 16HTF25664AZ-800H1 2048MB DIMM DDR2 800MT/s           | 1         | 2.63%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s           | 1         | 2.63%   |
| Micron RAM 16ATF2G64HZ-2G3B1 16GB SODIMM DDR4 2400MT/s           | 1         | 2.63%   |
| Kingston RAM HX432S20IB/8 8GB SODIMM DDR4 3200MT/s               | 1         | 2.63%   |
| Kingston RAM 9905625-004.A03LF 8GB SODIMM DDR4 3200MT/s          | 1         | 2.63%   |
| Kingston RAM 9905471-011.A00LF 4GB DIMM DDR3 1600MT/s            | 1         | 2.63%   |
| G.Skill RAM F3-14900CL8-4GBXM 4GB DIMM DDR3 1600MT/s             | 1         | 2.63%   |
| Elpida RAM EBJ21UE8BDS0-AE-F 2GB SODIMM DDR3 1067MT/s            | 1         | 2.63%   |
| Crucial RAM CT4G4SFS8213.C8FBD1 4GB SODIMM DDR4 2133MT/s         | 1         | 2.63%   |
| Crucial RAM CT16G4S24AM.M16FE 16GB SODIMM DDR4 2400MT/s          | 1         | 2.63%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 14        | 45.16%  |
| DDR3    | 9         | 29.03%  |
| LPDDR3  | 3         | 9.68%   |
| DDR2    | 2         | 6.45%   |
| Unknown | 2         | 6.45%   |
| LPDDR4  | 1         | 3.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 22        | 70.97%  |
| DIMM         | 6         | 19.35%  |
| Row Of Chips | 2         | 6.45%   |
| Unknown      | 1         | 3.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 15        | 44.12%  |
| 8192  | 7         | 20.59%  |
| 16384 | 6         | 17.65%  |
| 32768 | 4         | 11.76%  |
| 2048  | 2         | 5.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 9         | 27.27%  |
| 1600  | 8         | 24.24%  |
| 2400  | 6         | 18.18%  |
| 2133  | 2         | 6.06%   |
| 1867  | 2         | 6.06%   |
| 1066  | 2         | 6.06%   |
| 3200  | 1         | 3.03%   |
| 1333  | 1         | 3.03%   |
| 1067  | 1         | 3.03%   |
| 800   | 1         | 3.03%   |

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
| Chicony Electronics                    | 8         | 17.78%  |
| Apple                                  | 7         | 15.56%  |
| Realtek Semiconductor                  | 6         | 13.33%  |
| Alcor Micro                            | 5         | 11.11%  |
| Bison Electronics                      | 4         | 8.89%   |
| Sunplus Innovation Technology          | 3         | 6.67%   |
| Suyin                                  | 2         | 4.44%   |
| Silicon Motion                         | 1         | 2.22%   |
| Quanta                                 | 1         | 2.22%   |
| Microdia                               | 1         | 2.22%   |
| Lite-On Technology                     | 1         | 2.22%   |
| IMC Networks                           | 1         | 2.22%   |
| Google                                 | 1         | 2.22%   |
| Genesys Logic                          | 1         | 2.22%   |
| Denron                                 | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.22%   |
| Acer                                   | 1         | 2.22%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Apple Built-in iSight                                                      | 4         | 8.7%    |
| Alcor Micro HD WebCam                                                      | 4         | 8.7%    |
| Realtek USB2.0 camera                                                      | 2         | 4.35%   |
| Chicony HD User Facing                                                     | 2         | 4.35%   |
| Bison SunplusIT INC. Integrated Camera                                     | 2         | 4.35%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                                         | 2         | 4.35%   |
| Suyin HP Wide Vision FHD Camera                                            | 1         | 2.17%   |
| Suyin HP Integrated Webcam                                                 | 1         | 2.17%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 2.17%   |
| Sunplus Integrated Camera                                                  | 1         | 2.17%   |
| Sunplus HD WebCam                                                          | 1         | 2.17%   |
| Silicon Motion WebCam SC-13HDL12131N                                       | 1         | 2.17%   |
| Realtek Lenovo EasyCamera                                                  | 1         | 2.17%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 2.17%   |
| Realtek Integrated Webcam                                                  | 1         | 2.17%   |
| Realtek HP Truevision HD                                                   | 1         | 2.17%   |
| Quanta HD Camera                                                           | 1         | 2.17%   |
| Microdia HP Integrated Webcam                                              | 1         | 2.17%   |
| Lite-On Integrated Camera                                                  | 1         | 2.17%   |
| IMC Networks Lenovo EasyCamera                                             | 1         | 2.17%   |
| Genesys Logic Camera                                                       | 1         | 2.17%   |
| Denron 2M Front Camera                                                     | 1         | 2.17%   |
| Chicony USB2.0 UVC WebCam                                                  | 1         | 2.17%   |
| Chicony USB 2.0 Camera                                                     | 1         | 2.17%   |
| Chicony LG HD WebCam                                                       | 1         | 2.17%   |
| Chicony Integrated Camera                                                  | 1         | 2.17%   |
| Chicony HP TrueVision HD Camera                                            | 1         | 2.17%   |
| Chicony FJ Camera                                                          | 1         | 2.17%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 1         | 2.17%   |
| Bison SunplusIT Integrated Camera                                          | 1         | 2.17%   |
| Bison Lenovo EasyCamera                                                    | 1         | 2.17%   |
| Apple iBridge                                                              | 1         | 2.17%   |
| Apple FaceTime HD Camera (Built-in)                                        | 1         | 2.17%   |
| Alcor Micro HP Webcam-101                                                  | 1         | 2.17%   |
| Acer BisonCam, NB Pro                                                      | 1         | 2.17%   |
| Unknown                                                                    | 1         | 2.17%   |

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
| Purism, SPC               | 4         | 40%     |
| Alcor Micro               | 2         | 20%     |
| Realtek Semiconductor     | 1         | 10%     |
| O2 Micro                  | 1         | 10%     |
| Clay Logic                | 1         | 10%     |
| Aladdin Knowledge Systems | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Purism, SPC Librem Key                            | 4         | 40%     |
| Alcor Micro AU9540 Smartcard Reader               | 2         | 20%     |
| Realtek Semiconductor Smart Card Reader Interface | 1         | 10%     |
| O2 Micro Oz776 SmartCard Reader                   | 1         | 10%     |
| Clay Logic Nitrokey Pro                           | 1         | 10%     |
| Aladdin Knowledge Systems Token JC                | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 42        | 53.85%  |
| 1     | 26        | 33.33%  |
| 2     | 7         | 8.97%   |
| 4     | 2         | 2.56%   |
| 3     | 1         | 1.28%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 14        | 28.57%  |
| Graphics card         | 10        | 20.41%  |
| Fingerprint reader    | 9         | 18.37%  |
| Bluetooth             | 8         | 16.33%  |
| Multimedia controller | 4         | 8.16%   |
| Chipcard              | 3         | 6.12%   |
| Camera                | 1         | 2.04%   |

