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

Total: 120

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Purism        | Librem 15 v3                | Notebook    | [185a31ed85](https://linux-hardware.org/?probe=185a31ed85) | Oct 19, 2025 |
| Acer          | Swift SF316-51              | Notebook    | [52afb3677e](https://linux-hardware.org/?probe=52afb3677e) | Oct 12, 2025 |
| Lenovo        | ThinkPad T440p              | Notebook    | [512d56828e](https://linux-hardware.org/?probe=512d56828e) | Jul 10, 2025 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [033c66b184](https://linux-hardware.org/?probe=033c66b184) | May 29, 2025 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [2d4e106b46](https://linux-hardware.org/?probe=2d4e106b46) | Jan 31, 2025 |
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

![OS](./images/pie_chart/os_name.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| PureOS 10   | 32        | 37.65%  |
| PureOS 10.0 | 22        | 25.88%  |
| PureOS 9.0  | 13        | 15.29%  |
| PureOS 10.x | 12        | 14.12%  |
| PureOS 9    | 3         | 3.53%   |
| PureOS 8    | 3         | 3.53%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| PureOS | 80        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Computers | Percent |
|----------------------------------|-----------|---------|
| 4.19.0-5-amd64                   | 10        | 10.75%  |
| 5.10.0-14-amd64                  | 8         | 8.6%    |
| 5.10.0-23-amd64                  | 7         | 7.53%   |
| 5.10.0-33-amd64                  | 5         | 5.38%   |
| 5.10.0-13-amd64                  | 5         | 5.38%   |
| 5.10.0-8-amd64                   | 4         | 4.3%    |
| 5.10.0-21-amd64                  | 4         | 4.3%    |
| 5.10.0-11-amd64                  | 4         | 4.3%    |
| 4.19.0-14-amd64                  | 4         | 4.3%    |
| 5.10.0-28-amd64                  | 3         | 3.23%   |
| 5.10.0-27-amd64                  | 3         | 3.23%   |
| 5.10.0-26-amd64                  | 3         | 3.23%   |
| 6.1.0-1-librem5                  | 2         | 2.15%   |
| 5.7.0-1-librem5                  | 2         | 2.15%   |
| 5.10.0-9-amd64                   | 2         | 2.15%   |
| 5.10.0-7-amd64                   | 2         | 2.15%   |
| 5.10.0-35-amd64                  | 2         | 2.15%   |
| 5.10.0-32-amd64                  | 2         | 2.15%   |
| 5.10.0-19-amd64                  | 2         | 2.15%   |
| 5.10.0-16-amd64                  | 2         | 2.15%   |
| 6.6.0-1-librem5                  | 1         | 1.08%   |
| 6.1.66-x64v2-xanmod1             | 1         | 1.08%   |
| 6.0.0-1-librem5                  | 1         | 1.08%   |
| 5.9-sunxi64                      | 1         | 1.08%   |
| 5.8-sunxi64                      | 1         | 1.08%   |
| 5.7.0-0.38-1-pinebookpro-hwaccel | 1         | 1.08%   |
| 5.15.0-2-amd64                   | 1         | 1.08%   |
| 5.10.0-6-amd64                   | 1         | 1.08%   |
| 5.10.0-36-amd64                  | 1         | 1.08%   |
| 5.10.0-25-amd64                  | 1         | 1.08%   |
| 5.10.0-20-amd64                  | 1         | 1.08%   |
| 5.10.0-18-amd64                  | 1         | 1.08%   |
| 5.10.0-17-amd64                  | 1         | 1.08%   |
| 5.10.0-15-amd64                  | 1         | 1.08%   |
| 5.10.0-12-amd64                  | 1         | 1.08%   |
| 4.19.72-imx8-sr                  | 1         | 1.08%   |
| 4.16.0-1-amd64                   | 1         | 1.08%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 58        | 68.24%  |
| 4.19.0  | 14        | 16.47%  |
| 5.7.0   | 3         | 3.53%   |
| 6.1.0   | 2         | 2.35%   |
| 6.6.0   | 1         | 1.18%   |
| 6.1.66  | 1         | 1.18%   |
| 6.0.0   | 1         | 1.18%   |
| 5.9     | 1         | 1.18%   |
| 5.8     | 1         | 1.18%   |
| 5.15.0  | 1         | 1.18%   |
| 4.19.72 | 1         | 1.18%   |
| 4.16.0  | 1         | 1.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 58        | 69.05%  |
| 4.19    | 15        | 17.86%  |
| 6.1     | 3         | 3.57%   |
| 5.7     | 3         | 3.57%   |
| 6.6     | 1         | 1.19%   |
| 6.0     | 1         | 1.19%   |
| 5.15    | 1         | 1.19%   |
| 5       | 1         | 1.19%   |
| 4.16    | 1         | 1.19%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 72        | 90%     |
| aarch64 | 8         | 10%     |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 67        | 80.72%  |
| Unknown         | 6         | 7.23%   |
| KDE5            | 5         | 6.02%   |
| Phosh:GNOME     | 2         | 2.41%   |
| MATE            | 2         | 2.41%   |
| GNOME Flashback | 1         | 1.2%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 60        | 69.77%  |
| X11     | 15        | 17.44%  |
| Unknown | 6         | 6.98%   |
| Tty     | 5         | 5.81%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 43        | 52.44%  |
| GDM     | 26        | 31.71%  |
| GDM3    | 10        | 12.2%   |
| SDDM    | 3         | 3.66%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 33        | 39.76%  |
| de_DE   | 11        | 13.25%  |
| en_GB   | 5         | 6.02%   |
| pl_PL   | 4         | 4.82%   |
| Unknown | 4         | 4.82%   |
| ru_RU   | 3         | 3.61%   |
| it_IT   | 3         | 3.61%   |
| C       | 3         | 3.61%   |
| pt_BR   | 2         | 2.41%   |
| fr_FR   | 2         | 2.41%   |
| es_ES   | 2         | 2.41%   |
| es_AR   | 2         | 2.41%   |
| en_AU   | 2         | 2.41%   |
| zh_CN   | 1         | 1.2%    |
| pt_PT   | 1         | 1.2%    |
| nl_NL   | 1         | 1.2%    |
| hu_HU   | 1         | 1.2%    |
| es_CR   | 1         | 1.2%    |
| en_IL   | 1         | 1.2%    |
| bg_BG   | 1         | 1.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 64        | 79.01%  |
| EFI  | 17        | 20.99%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 73        | 91.25%  |
| Overlay | 2         | 2.5%    |
| Ext2    | 2         | 2.5%    |
| Unknown | 2         | 2.5%    |
| Btrfs   | 1         | 1.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 42        | 51.22%  |
| GPT     | 21        | 25.61%  |
| MBR     | 19        | 23.17%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 64        | 79.01%  |
| Yes       | 17        | 20.99%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 72        | 90%     |
| Yes       | 8         | 10%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Purism              | 19        | 23.75%  |
| Lenovo              | 11        | 13.75%  |
| Apple               | 9         | 11.25%  |
| Dell                | 6         | 7.5%    |
| Hewlett-Packard     | 5         | 6.25%   |
| ASUSTek Computer    | 4         | 5%      |
| Gigabyte Technology | 3         | 3.75%   |
| Acer                | 3         | 3.75%   |
| Unknown             | 3         | 3.75%   |
| Pine Microsystems   | 2         | 2.5%    |
| Wortmann AG         | 1         | 1.25%   |
| Toshiba             | 1         | 1.25%   |
| Shuttle             | 1         | 1.25%   |
| Samsung Electronics | 1         | 1.25%   |
| PCWare              | 1         | 1.25%   |
| Notebook            | 1         | 1.25%   |
| MSI                 | 1         | 1.25%   |
| Microsoft           | 1         | 1.25%   |
| LG Electronics      | 1         | 1.25%   |
| Irbis               | 1         | 1.25%   |
| Intel               | 1         | 1.25%   |
| HUAWEI              | 1         | 1.25%   |
| Google              | 1         | 1.25%   |
| Fujitsu             | 1         | 1.25%   |
| Chuwi               | 1         | 1.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Purism Librem 14                           | 6         | 7.5%    |
| Purism Librem 15 v3                        | 3         | 3.75%   |
| Unknown                                    | 3         | 3.75%   |
| Purism Librem 5r4                          | 2         | 2.5%    |
| Purism Librem 15 v4                        | 2         | 2.5%    |
| Purism Librem 13 v4                        | 2         | 2.5%    |
| Lenovo ThinkPad T440p                      | 2         | 2.5%    |
| HP Pavilion g6                             | 2         | 2.5%    |
| Wortmann AG TERRA_PC                       | 1         | 1.25%   |
| Toshiba Satellite L500D                    | 1         | 1.25%   |
| Shuttle DS10U                              | 1         | 1.25%   |
| Samsung 530U3C/530U4C/532U3C               | 1         | 1.25%   |
| Purism librem_mini_v2                      | 1         | 1.25%   |
| Purism librem_13v2                         | 1         | 1.25%   |
| Purism Librem 5                            | 1         | 1.25%   |
| Purism Librem 13 v2                        | 1         | 1.25%   |
| Pine Microsystems Pine64 PinePhone (1.2)   | 1         | 1.25%   |
| Pine Microsystems Pine64 Pinebook Pro      | 1         | 1.25%   |
| PCWare IPX4005G                            | 1         | 1.25%   |
| Notebook P17SM                             | 1         | 1.25%   |
| MSI MS-7788                                | 1         | 1.25%   |
| Microsoft Surface Book 2                   | 1         | 1.25%   |
| LG 22V280-L.BY31P1                         | 1         | 1.25%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XXS3JC01 | 1         | 1.25%   |
| Lenovo ThinkPad T540p 20BFS23T00           | 1         | 1.25%   |
| Lenovo ThinkPad T440 20B60044RT            | 1         | 1.25%   |
| Lenovo ThinkPad P50 20ENCTO1WW             | 1         | 1.25%   |
| Lenovo ThinkPad E480 20KN003SUS            | 1         | 1.25%   |
| Lenovo ThinkPad 13 2nd Gen 20J2S00G00      | 1         | 1.25%   |
| Lenovo IdeaPad U430 Touch 20270            | 1         | 1.25%   |
| Lenovo G450 2949                           | 1         | 1.25%   |
| Lenovo B50-70 20384                        | 1         | 1.25%   |
| Irbis NB131                                | 1         | 1.25%   |
| Intel powered classmate PC                 | 1         | 1.25%   |
| HUAWEI NBLB-WAX9N                          | 1         | 1.25%   |
| HP Spectre x360 Convertible                | 1         | 1.25%   |
| HP Pavilion Notebook                       | 1         | 1.25%   |
| HP Laptop 15s-du3xxx                       | 1         | 1.25%   |
| Google Droid                               | 1         | 1.25%   |
| Gigabyte GA-MA78GM-UD2H                    | 1         | 1.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Purism Librem            | 19        | 23.75%  |
| Lenovo ThinkPad          | 8         | 10%     |
| HP Pavilion              | 3         | 3.75%   |
| Dell Inspiron            | 3         | 3.75%   |
| Unknown                  | 3         | 3.75%   |
| Pine Microsystems Pine64 | 2         | 2.5%    |
| Acer Swift               | 2         | 2.5%    |
| Wortmann AG TERRA        | 1         | 1.25%   |
| Toshiba Satellite        | 1         | 1.25%   |
| Shuttle DS10U            | 1         | 1.25%   |
| Samsung 530U3C           | 1         | 1.25%   |
| PCWare IPX4005G          | 1         | 1.25%   |
| Notebook P17SM           | 1         | 1.25%   |
| MSI MS-7788              | 1         | 1.25%   |
| Microsoft Surface        | 1         | 1.25%   |
| LG 22V280-L.BY31P1       | 1         | 1.25%   |
| Lenovo IdeaPad           | 1         | 1.25%   |
| Lenovo G450              | 1         | 1.25%   |
| Lenovo B50-70            | 1         | 1.25%   |
| Irbis NB131              | 1         | 1.25%   |
| Intel powered            | 1         | 1.25%   |
| HUAWEI NBLB-WAX9N        | 1         | 1.25%   |
| HP Spectre               | 1         | 1.25%   |
| HP Laptop                | 1         | 1.25%   |
| Google Droid             | 1         | 1.25%   |
| Gigabyte GA-MA78GM-UD2H  | 1         | 1.25%   |
| Gigabyte B85M-DS3H       | 1         | 1.25%   |
| Gigabyte B560M           | 1         | 1.25%   |
| Fujitsu LIFEBOOK         | 1         | 1.25%   |
| Dell XPS                 | 1         | 1.25%   |
| Dell OptiPlex            | 1         | 1.25%   |
| Dell Latitude            | 1         | 1.25%   |
| Chuwi Hi10               | 1         | 1.25%   |
| ASUS M4N68T              | 1         | 1.25%   |
| ASUS F2A85-M             | 1         | 1.25%   |
| ASUS EX-A320M-GAMING     | 1         | 1.25%   |
| ASUS A88X-PLUS           | 1         | 1.25%   |
| Apple Macmini6           | 1         | 1.25%   |
| Apple MacBookPro6        | 1         | 1.25%   |
| Apple MacBookPro14       | 1         | 1.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 11        | 13.75%  |
| Unknown | 10        | 12.5%   |
| 2017    | 8         | 10%     |
| 2013    | 8         | 10%     |
| 2019    | 6         | 7.5%    |
| 2018    | 5         | 6.25%   |
| 2020    | 4         | 5%      |
| 2016    | 4         | 5%      |
| 2015    | 4         | 5%      |
| 2009    | 4         | 5%      |
| 2014    | 3         | 3.75%   |
| 2012    | 3         | 3.75%   |
| 2011    | 3         | 3.75%   |
| 2010    | 2         | 2.5%    |
| 2007    | 2         | 2.5%    |
| 2023    | 1         | 1.25%   |
| 2022    | 1         | 1.25%   |
| 2006    | 1         | 1.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 52        | 65%     |
| Desktop        | 14        | 17.5%   |
| All in one     | 4         | 5%      |
| System on chip | 3         | 3.75%   |
| Convertible    | 3         | 3.75%   |
| Tablet         | 2         | 2.5%    |
| Phone          | 1         | 1.25%   |
| Mini pc        | 1         | 1.25%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 80        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 61        | 76.25%  |
| Yes  | 19        | 23.75%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 20        | 25%     |
| 3.01-4.0    | 15        | 18.75%  |
| 4.01-8.0    | 14        | 17.5%   |
| 8.01-16.0   | 14        | 17.5%   |
| 32.01-64.0  | 7         | 8.75%   |
| 2.01-3.0    | 4         | 5%      |
| 1.01-2.0    | 3         | 3.75%   |
| 24.01-32.0  | 2         | 2.5%    |
| 64.01-256.0 | 1         | 1.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 27        | 30%     |
| 1.01-2.0  | 25        | 27.78%  |
| 4.01-8.0  | 16        | 17.78%  |
| 3.01-4.0  | 16        | 17.78%  |
| 8.01-16.0 | 4         | 4.44%   |
| 0.51-1.0  | 1         | 1.11%   |
| 0.01-0.5  | 1         | 1.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 56        | 67.47%  |
| 2      | 19        | 22.89%  |
| 0      | 4         | 4.82%   |
| 3      | 2         | 2.41%   |
| 5      | 1         | 1.2%    |
| 4      | 1         | 1.2%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 66        | 81.48%  |
| Yes       | 15        | 18.52%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 61        | 76.25%  |
| No        | 19        | 23.75%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 63        | 78.75%  |
| No        | 17        | 21.25%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 49        | 61.25%  |
| No        | 31        | 38.75%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 16        | 19.51%  |
| Germany                | 15        | 18.29%  |
| UK                     | 6         | 7.32%   |
| Brazil                 | 6         | 7.32%   |
| Russia                 | 4         | 4.88%   |
| Italy                  | 4         | 4.88%   |
| Poland                 | 3         | 3.66%   |
| Canada                 | 3         | 3.66%   |
| Australia              | 3         | 3.66%   |
| Spain                  | 2         | 2.44%   |
| France                 | 2         | 2.44%   |
| Argentina              | 2         | 2.44%   |
| Turkey                 | 1         | 1.22%   |
| Sri Lanka              | 1         | 1.22%   |
| South Africa           | 1         | 1.22%   |
| Serbia                 | 1         | 1.22%   |
| Portugal               | 1         | 1.22%   |
| Paraguay               | 1         | 1.22%   |
| Pakistan               | 1         | 1.22%   |
| Netherlands            | 1         | 1.22%   |
| Martinique             | 1         | 1.22%   |
| Israel                 | 1         | 1.22%   |
| Iran                   | 1         | 1.22%   |
| Greece                 | 1         | 1.22%   |
| Costa Rica             | 1         | 1.22%   |
| China                  | 1         | 1.22%   |
| Bulgaria               | 1         | 1.22%   |
| Bosnia and Herzegovina | 1         | 1.22%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Stuttgart               | 3         | 3.45%   |
| Porto Alegre            | 3         | 3.45%   |
| Warsaw                  | 2         | 2.3%    |
| New York                | 2         | 2.3%    |
| London                  | 2         | 2.3%    |
| Berlin                  | 2         | 2.3%    |
| Yuzhnoural'sk           | 1         | 1.15%   |
| Wixom                   | 1         | 1.15%   |
| Windsor                 | 1         | 1.15%   |
| Vista                   | 1         | 1.15%   |
| Vancouver               | 1         | 1.15%   |
| Troy                    | 1         | 1.15%   |
| Tornesch                | 1         | 1.15%   |
| Tomsk                   | 1         | 1.15%   |
| Thorpe Hamlet           | 1         | 1.15%   |
| Tel Aviv                | 1         | 1.15%   |
| Stolberg                | 1         | 1.15%   |
| Stargard                | 1         | 1.15%   |
| Spencer                 | 1         | 1.15%   |
| Sofia                   | 1         | 1.15%   |
| Seattle                 | 1         | 1.15%   |
| Sao Paulo               | 1         | 1.15%   |
| Sant Cugat del Vallès  | 1         | 1.15%   |
| San Jose                | 1         | 1.15%   |
| Roetgen                 | 1         | 1.15%   |
| Plano                   | 1         | 1.15%   |
| Perth                   | 1         | 1.15%   |
| Paris                   | 1         | 1.15%   |
| Ouderkerk aan de Amstel | 1         | 1.15%   |
| Nizhnekamsk             | 1         | 1.15%   |
| Montreal                | 1         | 1.15%   |
| Milwaukee               | 1         | 1.15%   |
| Milpitas                | 1         | 1.15%   |
| Milan                   | 1         | 1.15%   |
| Melbourne               | 1         | 1.15%   |
| Mankato                 | 1         | 1.15%   |
| Magstadt                | 1         | 1.15%   |
| Madrid                  | 1         | 1.15%   |
| Liverpool               | 1         | 1.15%   |
| Lenningen               | 1         | 1.15%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 24        | 32     | 25.53%  |
| Unknown             | 8         | 12     | 8.51%   |
| Seagate             | 8         | 17     | 8.51%   |
| WDC                 | 7         | 8      | 7.45%   |
| SanDisk             | 6         | 6      | 6.38%   |
| Apple               | 6         | 8      | 6.38%   |
| Crucial             | 5         | 7      | 5.32%   |
| Kingston            | 3         | 4      | 3.19%   |
| HGST                | 3         | 3      | 3.19%   |
| A-DATA Technology   | 3         | 4      | 3.19%   |
| Intenso             | 2         | 3      | 2.13%   |
| Win Memory          | 1         | 1      | 1.06%   |
| Transcend           | 1         | 1      | 1.06%   |
| Toshiba             | 1         | 1      | 1.06%   |
| Team                | 1         | 1      | 1.06%   |
| Qumo                | 1         | 1      | 1.06%   |
| PNY                 | 1         | 2      | 1.06%   |
| Plextor             | 1         | 1      | 1.06%   |
| Phison              | 1         | 1      | 1.06%   |
| Patriot             | 1         | 1      | 1.06%   |
| Mushkin             | 1         | 1      | 1.06%   |
| Maxtor              | 1         | 1      | 1.06%   |
| JMicron Technology  | 1         | 1      | 1.06%   |
| Intel               | 1         | 1      | 1.06%   |
| Hitachi             | 1         | 1      | 1.06%   |
| China               | 1         | 3      | 1.06%   |
| BIWIN               | 1         | 1      | 1.06%   |
| ASMT                | 1         | 2      | 1.06%   |
| ADATA Technology    | 1         | 1      | 1.06%   |
| Unknown             | 1         | 2      | 1.06%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                         | 3         | 2.91%   |
| Unknown MMC Card  64GB                            | 2         | 1.94%   |
| Unknown MMC Card  32GB                            | 2         | 1.94%   |
| Seagate ST1000LM048-2E7172 1TB                    | 2         | 1.94%   |
| Samsung SSD 970 PRO 1TB                           | 2         | 1.94%   |
| Samsung SSD 860 EVO 250GB                         | 2         | 1.94%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 2         | 1.94%   |
| Crucial CT250MX500SSD4 250GB                      | 2         | 1.94%   |
| Win Memory SWR256G-201II 256GB SSD                | 1         | 0.97%   |
| WDC WDS500G2B0A-00SM50 500GB                      | 1         | 0.97%   |
| WDC WDS100T2B0C-00PXH0 1TB                        | 1         | 0.97%   |
| WDC WDBNCE2500PNC 250GB SSD                       | 1         | 0.97%   |
| WDC WDBNCE0010PNC 1TB SSD                         | 1         | 0.97%   |
| WDC WD5000LPCX-22VHAT0 500GB                      | 1         | 0.97%   |
| WDC WD5000AZRX-00A8LB0 500GB                      | 1         | 0.97%   |
| WDC WD3200AAJS-40RYA0 320GB                       | 1         | 0.97%   |
| Unknown SH64G  64GB                               | 1         | 0.97%   |
| Unknown MMC Card  16GB                            | 1         | 0.97%   |
| Unknown DA4128  128GB                             | 1         | 0.97%   |
| Unknown AFGCF  128GB                              | 1         | 0.97%   |
| Unknown 8GTF4R  8GB                               | 1         | 0.97%   |
| Unknown 032G32  32GB                              | 1         | 0.97%   |
| Transcend TS240GMTS420S 240GB SSD                 | 1         | 0.97%   |
| Toshiba NVMe SSD Drive 512GB                      | 1         | 0.97%   |
| Team TM8FP6256G 256GB                             | 1         | 0.97%   |
| Seagate ST480HM000-1G5162 506GB                   | 1         | 0.97%   |
| Seagate ST3500630AS 500GB                         | 1         | 0.97%   |
| Seagate ST3320418AS 320GB                         | 1         | 0.97%   |
| Seagate ST3250410AS 250GB                         | 1         | 0.97%   |
| Seagate ST3250312CS 250GB                         | 1         | 0.97%   |
| Seagate ST31000524AS 1TB                          | 1         | 0.97%   |
| Seagate ST1000DM003-1ER162 1TB                    | 1         | 0.97%   |
| Seagate ST1000DM003-1CH162 1TB                    | 1         | 0.97%   |
| Seagate NVMe SSD Drive 2TB                        | 1         | 0.97%   |
| SanDisk SSD i100 24GB                             | 1         | 0.97%   |
| SanDisk SDSSDP128G 128GB                          | 1         | 0.97%   |
| SanDisk SDSSDH3500G 500GB                         | 1         | 0.97%   |
| SanDisk NVMe SSD Drive 500GB                      | 1         | 0.97%   |
| SanDisk DF4128  128GB                             | 1         | 0.97%   |
| SanDisk DF4032  32GB                              | 1         | 0.97%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 16     | 30.43%  |
| WDC                 | 3         | 3      | 13.04%  |
| HGST                | 3         | 3      | 13.04%  |
| Apple               | 3         | 3      | 13.04%  |
| Samsung Electronics | 2         | 2      | 8.7%    |
| Maxtor              | 1         | 1      | 4.35%   |
| JMicron Technology  | 1         | 1      | 4.35%   |
| Intenso             | 1         | 1      | 4.35%   |
| Hitachi             | 1         | 1      | 4.35%   |
| ASMT                | 1         | 2      | 4.35%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 13     | 26.32%  |
| Crucial             | 4         | 6      | 10.53%  |
| WDC                 | 3         | 4      | 7.89%   |
| SanDisk             | 3         | 3      | 7.89%   |
| Kingston            | 3         | 4      | 7.89%   |
| A-DATA Technology   | 3         | 4      | 7.89%   |
| Win Memory          | 1         | 1      | 2.63%   |
| Transcend           | 1         | 1      | 2.63%   |
| Qumo                | 1         | 1      | 2.63%   |
| PNY                 | 1         | 2      | 2.63%   |
| Plextor             | 1         | 1      | 2.63%   |
| Patriot             | 1         | 1      | 2.63%   |
| Mushkin             | 1         | 1      | 2.63%   |
| Intenso             | 1         | 2      | 2.63%   |
| Intel               | 1         | 1      | 2.63%   |
| China               | 1         | 3      | 2.63%   |
| BIWIN               | 1         | 1      | 2.63%   |
| Apple               | 1         | 1      | 2.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 34        | 50     | 38.2%   |
| NVMe    | 23        | 29     | 25.84%  |
| HDD     | 21        | 33     | 23.6%   |
| MMC     | 10        | 14     | 11.24%  |
| Unknown | 1         | 2      | 1.12%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 48        | 80     | 56.47%  |
| NVMe | 23        | 29     | 27.06%  |
| MMC  | 10        | 14     | 11.76%  |
| SAS  | 4         | 5      | 4.71%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 38        | 61     | 71.7%   |
| 0.51-1.0   | 12        | 18     | 22.64%  |
| 1.01-2.0   | 3         | 4      | 5.66%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 40        | 48.19%  |
| 251-500    | 9         | 10.84%  |
| 101-250    | 9         | 10.84%  |
| 21-50      | 6         | 7.23%   |
| 51-100     | 6         | 7.23%   |
| 501-1000   | 5         | 6.02%   |
| Unknown    | 4         | 4.82%   |
| 1001-2000  | 3         | 3.61%   |
| 2001-3000  | 1         | 1.2%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 55        | 65.48%  |
| 21-50    | 15        | 17.86%  |
| 101-250  | 4         | 4.76%   |
| Unknown  | 4         | 4.76%   |
| 501-1000 | 3         | 3.57%   |
| 51-100   | 2         | 2.38%   |
| 251-500  | 1         | 1.19%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


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

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 4      | 40%     |
| Maxtor  | 1         | 1      | 20%     |
| Intel   | 1         | 1      | 20%     |
| Apple   | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 4      | 50%     |
| Maxtor  | 1         | 1      | 25%     |
| Apple   | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 50        | 83     | 58.82%  |
| Works    | 30        | 38     | 35.29%  |
| Malfunc  | 5         | 7      | 5.88%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 46        | 58.23%  |
| Samsung Electronics          | 14        | 17.72%  |
| AMD                          | 7         | 8.86%   |
| SanDisk                      | 2         | 2.53%   |
| Nvidia                       | 2         | 2.53%   |
| Apple                        | 2         | 2.53%   |
| Toshiba America Info Systems | 1         | 1.27%   |
| Seagate Technology           | 1         | 1.27%   |
| Phison Electronics           | 1         | 1.27%   |
| Micron/Crucial Technology    | 1         | 1.27%   |
| MAXIO Technology (Hangzhou)  | 1         | 1.27%   |
| ADATA Technology             | 1         | 1.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 11        | 13.1%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 8         | 9.52%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6         | 7.14%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 5         | 5.95%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 4.76%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 3.57%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 3.57%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 2.38%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 2.38%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 2.38%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 2         | 2.38%   |
| Apple S3X NVMe Controller                                                      | 2         | 2.38%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 1.19%   |
| Seagate FireCuda/IronWolf 510 SSD                                              | 1         | 1.19%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                     | 1         | 1.19%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 1         | 1.19%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 1         | 1.19%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 1         | 1.19%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 1.19%   |
| Nvidia MCP61 SATA Controller                                                   | 1         | 1.19%   |
| Nvidia MCP61 IDE                                                               | 1         | 1.19%   |
| Micron/Crucial P5 NVMe PCIe SSD[SlashP5]                                       | 1         | 1.19%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 1         | 1.19%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.19%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 1.19%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 1.19%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.19%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.19%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.19%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 1.19%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 1         | 1.19%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 1.19%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 1         | 1.19%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 1         | 1.19%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 1.19%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1         | 1.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 1.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1         | 1.19%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1         | 1.19%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 1.19%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 53        | 65.43%  |
| NVMe | 23        | 28.4%   |
| IDE  | 4         | 4.94%   |
| RAID | 1         | 1.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 65        | 80.25%  |
| AMD     | 7         | 8.64%   |
| ARM     | 6         | 7.41%   |
| Unknown | 3         | 3.7%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-10710U CPU @ 1.10GHz          | 6         | 7.41%   |
| ARM Processor                               | 6         | 7.41%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 5         | 6.17%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 5         | 6.17%   |
|                                             | 3         | 3.7%    |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 2         | 2.47%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 2.47%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 1         | 1.23%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 1.23%   |
| Intel Pentium CPU N4200 @ 1.10GHz           | 1         | 1.23%   |
| Intel Core m5-6Y54 CPU @ 1.10GHz            | 1         | 1.23%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 1.23%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 1.23%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 1.23%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 1.23%   |
| Intel Core i7-7567U CPU @ 3.50GHz           | 1         | 1.23%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 1         | 1.23%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz          | 1         | 1.23%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz          | 1         | 1.23%   |
| Intel Core i7-4510U CPU @ 2.00GHz           | 1         | 1.23%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 1.23%   |
| Intel Core i5-5250U CPU @ 1.60GHz           | 1         | 1.23%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 1         | 1.23%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1         | 1.23%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1         | 1.23%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 1.23%   |
| Intel Core i5-3330S CPU @ 2.70GHz           | 1         | 1.23%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.23%   |
| Intel Core i5-2320 CPU @ 3.00GHz            | 1         | 1.23%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 1         | 1.23%   |
| Intel Core i5 CPU M 540 @ 2.53GHz           | 1         | 1.23%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1         | 1.23%   |
| Intel Core i3-4130T CPU @ 2.90GHz           | 1         | 1.23%   |
| Intel Core i3-4010U CPU @ 1.70GHz           | 1         | 1.23%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 1         | 1.23%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 1         | 1.23%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 1         | 1.23%   |
| Intel Core i3-10100F CPU @ 3.60GHz          | 1         | 1.23%   |
| Intel Core 2 Duo CPU U7700 @ 1.33GHz        | 1         | 1.23%   |
| Intel Core 2 Duo CPU T7700 @ 2.40GHz        | 1         | 1.23%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 28        | 35%     |
| Intel Core i5           | 13        | 16.25%  |
| Other                   | 11        | 13.75%  |
| Intel Core i3           | 6         | 7.5%    |
| Intel Celeron           | 6         | 7.5%    |
| Intel Core 2 Duo        | 4         | 5%      |
| AMD A10                 | 2         | 2.5%    |
| Intel Pentium Silver    | 1         | 1.25%   |
| Intel Pentium Dual-Core | 1         | 1.25%   |
| Intel Pentium           | 1         | 1.25%   |
| Intel Core m5           | 1         | 1.25%   |
| Intel Atom              | 1         | 1.25%   |
| AMD Turion II Dual-Core | 1         | 1.25%   |
| AMD Ryzen 5             | 1         | 1.25%   |
| AMD Ryzen 3             | 1         | 1.25%   |
| AMD Athlon II X4        | 1         | 1.25%   |
| AMD Athlon II X3        | 1         | 1.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 40        | 50%     |
| 4       | 32        | 40%     |
| 6       | 6         | 7.5%    |
| 3       | 1         | 1.25%   |
| Unknown | 1         | 1.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 79        | 98.75%  |
| Unknown | 1         | 1.25%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 50        | 62.5%   |
| 1       | 29        | 36.25%  |
| Unknown | 1         | 1.25%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 76        | 93.83%  |
| Unknown        | 4         | 4.94%   |
| 64-bit         | 1         | 1.23%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 53        | 63.86%  |
| 0x406e3    | 5         | 6.02%   |
| 0xa0660    | 3         | 3.61%   |
| 0x806c1    | 3         | 3.61%   |
| 0x806ec    | 2         | 2.41%   |
| 0x806e9    | 2         | 2.41%   |
| 0x706a1    | 2         | 2.41%   |
| 0x40651    | 2         | 2.41%   |
| 0x1067a    | 2         | 2.41%   |
| 0x806ea    | 1         | 1.2%    |
| 0x506c9    | 1         | 1.2%    |
| 0x406c4    | 1         | 1.2%    |
| 0x306d4    | 1         | 1.2%    |
| 0x206a7    | 1         | 1.2%    |
| 0x08108109 | 1         | 1.2%    |
| 0x06003106 | 1         | 1.2%    |
| 0x06001119 | 1         | 1.2%    |
| 0x010000b6 | 1         | 1.2%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 15        | 18.75%  |
| Haswell       | 10        | 12.5%   |
| Unknown       | 8         | 10%     |
| Skylake       | 7         | 8.75%   |
| CometLake     | 7         | 8.75%   |
| IvyBridge     | 5         | 6.25%   |
| TigerLake     | 3         | 3.75%   |
| Penryn        | 3         | 3.75%   |
| K10           | 3         | 3.75%   |
| Goldmont plus | 3         | 3.75%   |
| Zen+          | 2         | 2.5%    |
| Silvermont    | 2         | 2.5%    |
| SandyBridge   | 2         | 2.5%    |
| Goldmont      | 2         | 2.5%    |
| Core          | 2         | 2.5%    |
| Broadwell     | 2         | 2.5%    |
| Westmere      | 1         | 1.25%   |
| Steamroller   | 1         | 1.25%   |
| Piledriver    | 1         | 1.25%   |
| Nehalem       | 1         | 1.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 58        | 70.73%  |
| Nvidia | 13        | 15.85%  |
| AMD    | 11        | 13.41%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 7         | 8.14%   |
| Intel Comet Lake UHD Graphics                                                            | 6         | 6.98%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 5         | 5.81%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 4.65%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 4.65%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 4.65%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 2.33%   |
| Nvidia GK208M [GeForce GT 730M]                                                          | 2         | 2.33%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 2.33%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 2.33%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 2         | 2.33%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 2.33%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 2.33%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 2.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 2.33%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1         | 1.16%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 1.16%   |
| Nvidia GM107GLM [Quadro M2000M]                                                          | 1         | 1.16%   |
| Nvidia GK107M [GeForce GT 640M Mac Edition]                                              | 1         | 1.16%   |
| Nvidia GK104M [GeForce GTX 870M]                                                         | 1         | 1.16%   |
| Nvidia GF116 [GeForce GTS 450 Rev. 2]                                                    | 1         | 1.16%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 1         | 1.16%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 1.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 1.16%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.16%   |
| Intel Whiskey Lake-U GT1 [UHD Graphics 610]                                              | 1         | 1.16%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 1         | 1.16%   |
| Intel Skylake-Y GT2 [HD Graphics 515]                                                    | 1         | 1.16%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.16%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.16%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.16%   |
| Intel Kaby Lake-U GT3 [Iris Plus Graphics 650]                                           | 1         | 1.16%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                                  | 1         | 1.16%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 1.16%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.16%   |
| Intel Broadwell-U GT3 [HD Graphics 6000]                                                 | 1         | 1.16%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 1         | 1.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 1.16%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 1         | 1.16%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 48        | 60%     |
| Other          | 9         | 11.25%  |
| 1 x Nvidia     | 7         | 8.75%   |
| 1 x AMD        | 7         | 8.75%   |
| Intel + Nvidia | 6         | 7.5%    |
| Intel + AMD    | 2         | 2.5%    |
| 2 x AMD        | 1         | 1.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 69        | 86.25%  |
| Unknown | 11        | 13.75%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 77        | 95.06%  |
| 0.51-1.0   | 2         | 2.47%   |
| 3.01-4.0   | 1         | 1.23%   |
| 1.01-2.0   | 1         | 1.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 13        | 15.66%  |
| Chimei Innolux          | 12        | 14.46%  |
| Samsung Electronics     | 10        | 12.05%  |
| LG Display              | 8         | 9.64%   |
| Apple                   | 7         | 8.43%   |
| Philips                 | 3         | 3.61%   |
| Goldstar                | 3         | 3.61%   |
| AU Optronics            | 3         | 3.61%   |
| Unknown                 | 2         | 2.41%   |
| Wacom                   | 1         | 1.2%    |
| ViewSonic               | 1         | 1.2%    |
| Toshiba                 | 1         | 1.2%    |
| Sony                    | 1         | 1.2%    |
| Sharp                   | 1         | 1.2%    |
| RTK                     | 1         | 1.2%    |
| PRI                     | 1         | 1.2%    |
| PANDA                   | 1         | 1.2%    |
| Panasonic               | 1         | 1.2%    |
| MSI                     | 1         | 1.2%    |
| Lenovo                  | 1         | 1.2%    |
| InfoVision              | 1         | 1.2%    |
| Iiyama                  | 1         | 1.2%    |
| Grundig                 | 1         | 1.2%    |
| Flipbook                | 1         | 1.2%    |
| Dell                    | 1         | 1.2%    |
| CSOT                    | 1         | 1.2%    |
| Chi Mei Optoelectronics | 1         | 1.2%    |
| BenQ                    | 1         | 1.2%    |
| ASUSTek Computer        | 1         | 1.2%    |
| AOC                     | 1         | 1.2%    |
| Acer                    | 1         | 1.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC434B 3840x2160 344x194mm 15.5-inch | 3         | 3.61%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 3.61%   |
| BOE LCD Monitor BOE06BE 1920x1080 294x165mm 13.3-inch                 | 3         | 3.61%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 2         | 2.41%   |
| Philips TV PHL5035 1920x1080 640x360mm 28.9-inch                      | 2         | 2.41%   |
| Chimei Innolux LCD Monitor CMN1415 1920x1080 309x173mm 13.9-inch      | 2         | 2.41%   |
| BOE LCD Monitor BOE0630 1920x1080 344x194mm 15.5-inch                 | 2         | 2.41%   |
| Wacom Cintiq 16 WAC1071 1920x1080 344x193mm 15.5-inch                 | 1         | 1.2%    |
| ViewSonic VA2719 Series VSCC132 1920x1080 598x336mm 27.0-inch         | 1         | 1.2%    |
| Toshiba LCD Monitor LCD3706 1280x800 261x163mm 12.1-inch              | 1         | 1.2%    |
| Sony TV SNYAB03 1920x1080                                             | 1         | 1.2%    |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch               | 1         | 1.2%    |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 474x296mm 22.0-inch  | 1         | 1.2%    |
| Samsung Electronics SyncMaster SAM01D3 1440x900 410x260mm 19.1-inch   | 1         | 1.2%    |
| Samsung Electronics SyncMaster SAM0193 1280x1024 376x301mm 19.0-inch  | 1         | 1.2%    |
| Samsung Electronics LS27A800U SAM71A3 3840x2160 597x336mm 27.0-inch   | 1         | 1.2%    |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch  | 1         | 1.2%    |
| Samsung Electronics LCD Monitor SAM0900 1366x768 580x320mm 26.1-inch  | 1         | 1.2%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1         | 1.2%    |
| RTK LCD Monitor RTK2136 1600x900 434x236mm 19.4-inch                  | 1         | 1.2%    |
| PRI Prima TV PRI1600 1920x1080                                        | 1         | 1.2%    |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 1         | 1.2%    |
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch               | 1         | 1.2%    |
| Panasonic VVX11F009G00 MEI96A2 1920x1080 344x193mm 15.5-inch          | 1         | 1.2%    |
| MSI MPG 491C OLED MSI3FA8 3840x1080 1197x339mm 49.0-inch              | 1         | 1.2%    |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 1         | 1.2%    |
| LG Display LCD Monitor LGD053B 1920x1080 294x165mm 13.3-inch          | 1         | 1.2%    |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch          | 1         | 1.2%    |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 1         | 1.2%    |
| LG Display LCD Monitor LGD03F0 1366x768 310x174mm 14.0-inch           | 1         | 1.2%    |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch           | 1         | 1.2%    |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch           | 1         | 1.2%    |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch           | 1         | 1.2%    |
| Lenovo LEN Y44w-10 LEN65EA 3840x1200 1052x329mm 43.4-inch             | 1         | 1.2%    |
| InfoVision LCD Monitor IVO03FA 1366x768 223x125mm 10.1-inch           | 1         | 1.2%    |
| Iiyama PL2792H IVM664F 1920x1080 598x336mm 27.0-inch                  | 1         | 1.2%    |
| Grundig WUXGA GRU4448 1360x768                                        | 1         | 1.2%    |
| Goldstar IPS231 GSM5817 1920x1080 510x290mm 23.1-inch                 | 1         | 1.2%    |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch             | 1         | 1.2%    |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                | 1         | 1.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 40        | 51.28%  |
| 1366x768 (WXGA)    | 12        | 15.38%  |
| 3840x2160 (4K)     | 8         | 10.26%  |
| 1680x1050 (WSXGA+) | 3         | 3.85%   |
| 2288x1287          | 2         | 2.56%   |
| 1920x1200 (WUXGA)  | 2         | 2.56%   |
| 1600x900 (HD+)     | 2         | 2.56%   |
| 1440x900 (WXGA+)   | 2         | 2.56%   |
| 1280x800 (WXGA)    | 2         | 2.56%   |
| 3840x1200          | 1         | 1.28%   |
| 3840x1080          | 1         | 1.28%   |
| 2880x1800          | 1         | 1.28%   |
| 2304x1440          | 1         | 1.28%   |
| 1280x1024 (SXGA)   | 1         | 1.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 23        | 27.71%  |
| 15      | 19        | 22.89%  |
| 14      | 5         | 6.02%   |
| 23      | 4         | 4.82%   |
| 27      | 3         | 3.61%   |
| 24      | 3         | 3.61%   |
| 142     | 2         | 2.41%   |
| 31      | 2         | 2.41%   |
| 28      | 2         | 2.41%   |
| 22      | 2         | 2.41%   |
| 21      | 2         | 2.41%   |
| 20      | 2         | 2.41%   |
| 19      | 2         | 2.41%   |
| 17      | 2         | 2.41%   |
| 12      | 2         | 2.41%   |
| 72      | 1         | 1.2%    |
| 54      | 1         | 1.2%    |
| 49      | 1         | 1.2%    |
| 43      | 1         | 1.2%    |
| 40      | 1         | 1.2%    |
| 16      | 1         | 1.2%    |
| 10      | 1         | 1.2%    |
| Unknown | 1         | 1.2%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 33        | 40.24%  |
| 201-300        | 15        | 18.29%  |
| 501-600        | 10        | 12.2%   |
| 401-500        | 7         | 8.54%   |
| 351-400        | 5         | 6.1%    |
| 601-700        | 4         | 4.88%   |
| 1001-1500      | 3         | 3.66%   |
| More than 2000 | 2         | 2.44%   |
| 801-900        | 1         | 1.22%   |
| 1501-2000      | 1         | 1.22%   |
| Unknown        | 1         | 1.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 57        | 78.08%  |
| 16/10 | 11        | 15.07%  |
| 1.00  | 2         | 2.74%   |
| 5/4   | 1         | 1.37%   |
| 32/9  | 1         | 1.37%   |
| 3.20  | 1         | 1.37%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 20        | 24.1%   |
| 81-90          | 18        | 21.69%  |
| 201-250        | 11        | 13.25%  |
| 71-80          | 10        | 12.05%  |
| More than 1000 | 4         | 4.82%   |
| 351-500        | 4         | 4.82%   |
| 151-200        | 4         | 4.82%   |
| 301-350        | 3         | 3.61%   |
| 501-1000       | 3         | 3.61%   |
| 61-70          | 2         | 2.41%   |
| 41-50          | 1         | 1.2%    |
| 131-140        | 1         | 1.2%    |
| 121-130        | 1         | 1.2%    |
| Unknown        | 1         | 1.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 26        | 31.33%  |
| 51-100        | 24        | 28.92%  |
| 161-240       | 11        | 13.25%  |
| 101-120       | 11        | 13.25%  |
| More than 240 | 6         | 7.23%   |
| 1-50          | 4         | 4.82%   |
| Unknown       | 1         | 1.2%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 60        | 74.07%  |
| 2     | 10        | 12.35%  |
| 0     | 9         | 11.11%  |
| 3     | 2         | 2.47%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 43        | 34.4%   |
| Intel                           | 22        | 17.6%   |
| Qualcomm Atheros                | 21        | 16.8%   |
| Broadcom                        | 11        | 8.8%    |
| Broadcom Limited                | 4         | 3.2%    |
| ASIX Electronics                | 4         | 3.2%    |
| Qualcomm Atheros Communications | 2         | 1.6%    |
| Nvidia                          | 2         | 1.6%    |
| Marvell Technology Group        | 2         | 1.6%    |
| Edimax Technology               | 2         | 1.6%    |
| Xiaomi                          | 1         | 0.8%    |
| TP-Link                         | 1         | 0.8%    |
| Sierra Wireless                 | 1         | 0.8%    |
| Samsung Electronics             | 1         | 0.8%    |
| Ralink Technology               | 1         | 0.8%    |
| Ralink                          | 1         | 0.8%    |
| OPPO Electronics                | 1         | 0.8%    |
| MediaTek                        | 1         | 0.8%    |
| Google                          | 1         | 0.8%    |
| DisplayLink                     | 1         | 0.8%    |
| D-Link                          | 1         | 0.8%    |
| ASUSTek Computer                | 1         | 0.8%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 26        | 18.44%  |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 15        | 10.64%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 6         | 4.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 5         | 3.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 4         | 2.84%   |
| Intel Wireless 7265                                                           | 4         | 2.84%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 4         | 2.84%   |
| Intel Wireless 7260                                                           | 3         | 2.13%   |
| Intel Ethernet Connection I217-LM                                             | 3         | 2.13%   |
| Qualcomm Atheros AR9271 802.11n                                               | 2         | 1.42%   |
| Intel Wi-Fi 6 AX201                                                           | 2         | 1.42%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 2         | 1.42%   |
| Intel Ethernet Connection (6) I219-LM                                         | 2         | 1.42%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 2         | 1.42%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2         | 1.42%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter          | 2         | 1.42%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 1         | 0.71%   |
| TP-Link 802.11ac NIC                                                          | 1         | 0.71%   |
| Sierra Wireless EM7455                                                        | 1         | 0.71%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1         | 0.71%   |
| Realtek USB 10/100/1G/2.5 LAN                                                 | 1         | 0.71%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1         | 0.71%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.71%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 0.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.71%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 1         | 0.71%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 0.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1         | 0.71%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 0.71%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1         | 0.71%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 1         | 0.71%   |
| Realtek RTL8152 Fast Ethernet Adapter                                         | 1         | 0.71%   |
| Ralink MT7601U Wireless Adapter                                               | 1         | 0.71%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                        | 1         | 0.71%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                        | 1         | 0.71%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 0.71%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 0.71%   |
| OPPO Ace 3V                                                                   | 1         | 0.71%   |
| Nvidia MCP79 Ethernet                                                         | 1         | 0.71%   |
| Nvidia MCP61 Ethernet                                                         | 1         | 0.71%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 21        | 28.77%  |
| Intel                           | 18        | 24.66%  |
| Realtek Semiconductor           | 10        | 13.7%   |
| Broadcom                        | 8         | 10.96%  |
| Broadcom Limited                | 4         | 5.48%   |
| Qualcomm Atheros Communications | 2         | 2.74%   |
| Edimax Technology               | 2         | 2.74%   |
| TP-Link                         | 1         | 1.37%   |
| Sierra Wireless                 | 1         | 1.37%   |
| Ralink Technology               | 1         | 1.37%   |
| Ralink                          | 1         | 1.37%   |
| MediaTek                        | 1         | 1.37%   |
| Marvell Technology Group        | 1         | 1.37%   |
| D-Link                          | 1         | 1.37%   |
| ASUSTek Computer                | 1         | 1.37%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 15        | 20.55%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 4         | 5.48%   |
| Intel Wireless 7265                                                           | 4         | 5.48%   |
| Intel Wireless 7260                                                           | 3         | 4.11%   |
| Qualcomm Atheros AR9271 802.11n                                               | 2         | 2.74%   |
| Intel Wi-Fi 6 AX201                                                           | 2         | 2.74%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 2         | 2.74%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter          | 2         | 2.74%   |
| TP-Link 802.11ac NIC                                                          | 1         | 1.37%   |
| Sierra Wireless EM7455                                                        | 1         | 1.37%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1         | 1.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.37%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 1.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.37%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 1         | 1.37%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 1.37%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1         | 1.37%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 1.37%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1         | 1.37%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 1         | 1.37%   |
| Ralink MT7601U Wireless Adapter                                               | 1         | 1.37%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                        | 1         | 1.37%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 1.37%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.37%   |
| MediaTek WiFi                                                                 | 1         | 1.37%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                             | 1         | 1.37%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 1.37%   |
| Intel Wireless 8260                                                           | 1         | 1.37%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1         | 1.37%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 1.37%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 1         | 1.37%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 1.37%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 1         | 1.37%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                | 1         | 1.37%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                                   | 1         | 1.37%   |
| D-Link 802.11ac NIC                                                           | 1         | 1.37%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                                        | 1         | 1.37%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                        | 1         | 1.37%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 1         | 1.37%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                            | 1         | 1.37%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 38        | 57.58%  |
| Intel                    | 9         | 13.64%  |
| Broadcom                 | 6         | 9.09%   |
| ASIX Electronics         | 4         | 6.06%   |
| Nvidia                   | 2         | 3.03%   |
| Xiaomi                   | 1         | 1.52%   |
| Samsung Electronics      | 1         | 1.52%   |
| Qualcomm Atheros         | 1         | 1.52%   |
| OPPO Electronics         | 1         | 1.52%   |
| Marvell Technology Group | 1         | 1.52%   |
| Google                   | 1         | 1.52%   |
| DisplayLink              | 1         | 1.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 26        | 38.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 6         | 8.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 7.35%   |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 5.88%   |
| Intel Ethernet Connection I217-LM                                      | 3         | 4.41%   |
| Intel Ethernet Connection (6) I219-LM                                  | 2         | 2.94%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 2         | 2.94%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2         | 2.94%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 1.47%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 1.47%   |
| Realtek USB 10/100/1G/2.5 LAN                                          | 1         | 1.47%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 1.47%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 1.47%   |
| OPPO Ace 3V                                                            | 1         | 1.47%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 1.47%   |
| Nvidia MCP61 Ethernet                                                  | 1         | 1.47%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 1         | 1.47%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 1.47%   |
| Intel Ethernet Connection I218-V                                       | 1         | 1.47%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 1.47%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 1.47%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 1         | 1.47%   |
| Google Nexus/Pixel Device (tether)                                     | 1         | 1.47%   |
| DisplayLink USB-C Triple-4K Dock                                       | 1         | 1.47%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 1         | 1.47%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 1         | 1.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 63        | 51.22%  |
| Ethernet | 60        | 48.78%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 44        | 57.89%  |
| WiFi     | 32        | 42.11%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 36        | 45%     |
| 1     | 31        | 38.75%  |
| 0     | 11        | 13.75%  |
| 3     | 2         | 2.5%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 60        | 72.29%  |
| Yes  | 23        | 27.71%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 17        | 34%     |
| Apple                           | 8         | 16%     |
| Qualcomm Atheros Communications | 6         | 12%     |
| Lite-On Technology              | 6         | 12%     |
| Foxconn / Hon Hai               | 5         | 10%     |
| Realtek Semiconductor           | 3         | 6%      |
| IMC Networks                    | 2         | 4%      |
| Cambridge Silicon Radio         | 1         | 2%      |
| Broadcom                        | 1         | 2%      |
| ASUSTek Computer                | 1         | 2%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                   | 8         | 16%     |
| Lite-On Atheros AR3012 Bluetooth                     | 6         | 12%     |
| Foxconn / Hon Hai Bluetooth Device                   | 5         | 10%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)       | 3         | 6%      |
| Apple Bluetooth USB Host Controller                  | 3         | 6%      |
| Apple Bluetooth Host Controller                      | 3         | 6%      |
| Qualcomm Atheros  Bluetooth Device                   | 2         | 4%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0                | 2         | 4%      |
| Intel Wireless-AC 9260 Bluetooth Adapter             | 2         | 4%      |
| Intel AX201 Bluetooth                                | 2         | 4%      |
| Realtek RTL8822BE Bluetooth 4.2 Adapter              | 1         | 2%      |
| Realtek RTL8723B Bluetooth                           | 1         | 2%      |
| Realtek Bluetooth Radio                              | 1         | 2%      |
| Qualcomm Atheros Dell Wireless 1802 Bluetooth 4.0 LE | 1         | 2%      |
| Qualcomm Atheros AR9462 Bluetooth                    | 1         | 2%      |
| Intel Wireless-AC 3168 Bluetooth                     | 1         | 2%      |
| Intel Centrino Bluetooth Wireless Transceiver        | 1         | 2%      |
| IMC Networks Bluetooth Radio                         | 1         | 2%      |
| IMC Networks Bluetooth Device                        | 1         | 2%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)  | 1         | 2%      |
| Broadcom HP Portable Valentine                       | 1         | 2%      |
| ASUS Broadcom BCM20702A0 Bluetooth                   | 1         | 2%      |
| Apple Built-in Bluetooth 2.0+EDR HCI                 | 1         | 2%      |
| Apple Bluetooth HCI                                  | 1         | 2%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 62        | 68.13%  |
| Nvidia              | 10        | 10.99%  |
| AMD                 | 10        | 10.99%  |
| XMOS                | 1         | 1.1%    |
| Shure               | 1         | 1.1%    |
| Micronas            | 1         | 1.1%    |
| M-Audio             | 1         | 1.1%    |
| Logitech            | 1         | 1.1%    |
| GN Netcom           | 1         | 1.1%    |
| Elgato Systems      | 1         | 1.1%    |
| C-Media Electronics | 1         | 1.1%    |
| Astro Gaming        | 1         | 1.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 16        | 14.95%  |
| Intel Comet Lake PCH-LP cAVS                                               | 8         | 7.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 4.67%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 4.67%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 4.67%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 3.74%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 3.74%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 2.8%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 2.8%    |
| AMD FCH Azalia Controller                                                  | 3         | 2.8%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 1.87%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 1.87%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 2         | 1.87%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 1.87%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 1.87%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 1.87%   |
| AMD Trinity HDMI Audio Controller                                          | 2         | 1.87%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 1.87%   |
| AMD Ryzen HD Audio Controller                                              | 2         | 1.87%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.87%   |
| XMOS Khadas Tone Control                                                   | 1         | 0.93%   |
| Shure MV5                                                                  | 1         | 0.93%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.93%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.93%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 0.93%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.93%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.93%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.93%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.93%   |
| Nvidia GF116 High Definition Audio Controller                              | 1         | 0.93%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.93%   |
| Micronas QSB                                                               | 1         | 0.93%   |
| M-Audio M-Audio Fast Track MKII                                            | 1         | 0.93%   |
| Logitech Headset H340                                                      | 1         | 0.93%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 1         | 0.93%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 0.93%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 0.93%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1         | 0.93%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 10        | 26.32%  |
| Unknown             | 5         | 13.16%  |
| Samsung Electronics | 5         | 13.16%  |
| Micron Technology   | 5         | 13.16%  |
| Crucial             | 4         | 10.53%  |
| Toshiba             | 2         | 5.26%   |
| Kingston            | 2         | 5.26%   |
| Unknown (ABCD)      | 1         | 2.63%   |
| Smart               | 1         | 2.63%   |
| Ramaxel Technology  | 1         | 2.63%   |
| G.Skill             | 1         | 2.63%   |
| Elpida              | 1         | 2.63%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 3         | 7.32%   |
| Micron RAM 16ATF2G64HZ-2G3B1 16GB SODIMM DDR4 2400MT/s           | 2         | 4.88%   |
| Crucial RAM CT16G4SFD824A.M16FRS 16GB SODIMM DDR4 2400MT/s       | 2         | 4.88%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 2.44%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 2.44%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 2.44%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                             | 1         | 2.44%   |
| Unknown RAM Module 16384MB 2133MT/s                              | 1         | 2.44%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 2.44%   |
| Toshiba RAM 9905711-015.A00G 4GB SODIMM DDR4 2400MT/s            | 1         | 2.44%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s               | 1         | 2.44%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s                | 1         | 2.44%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s            | 1         | 2.44%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 2.44%   |
| SK hynix RAM Module 4GB DIMM DDR3 1066MT/s                       | 1         | 2.44%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GiB SODIMM DDR3 2667MT/s          | 1         | 2.44%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 2.44%   |
| SK hynix RAM HMP125U6EFR8C-S6 2048MB DIMM DDR2 800MT/s           | 1         | 2.44%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 2.44%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 2.44%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 2.44%   |
| SK hynix RAM HCNNNCPMBLHR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 1         | 2.44%   |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 2.44%   |
| SK hynix RAM H9CCNNNBLTALAR-NTD 4GB Row Of Chips LPDDR3 1600MT/s | 1         | 2.44%   |
| Samsung RAM Module 4GB SODIMM LPDDR3 1867MT/s                    | 1         | 2.44%   |
| Samsung RAM K4A8G165WC-BCTD 4GB SODIMM DDR4 2667MT/s             | 1         | 2.44%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s          | 1         | 2.44%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 2.44%   |
| Micron RAM 16HTF25664AZ-800H1 2GB DIMM DDR2 800MT/s              | 1         | 2.44%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s           | 1         | 2.44%   |
| Kingston RAM HX432S20IB/8 8GB SODIMM DDR4 3200MT/s               | 1         | 2.44%   |
| Kingston RAM 9905625-004.A03LF 16GB SODIMM DDR4 3200MT/s         | 1         | 2.44%   |
| Kingston RAM 9905471-011.A00LF 4GB DIMM DDR3 1600MT/s            | 1         | 2.44%   |
| G.Skill RAM F3-14900CL8-4GBXM 4GB DIMM DDR3 1600MT/s             | 1         | 2.44%   |
| Elpida RAM EBJ21UE8BDS0-AE-F 2GB SODIMM DDR3 1067MT/s            | 1         | 2.44%   |
| Crucial RAM CT4G4SFS8213.C8FBD1 4GB SODIMM DDR4 2133MT/s         | 1         | 2.44%   |
| Crucial RAM CT16G4S24AM.M16FE 16GB SODIMM DDR4 2400MT/s          | 1         | 2.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 15        | 44.12%  |
| DDR3    | 9         | 26.47%  |
| LPDDR4  | 3         | 8.82%   |
| LPDDR3  | 3         | 8.82%   |
| DDR2    | 2         | 5.88%   |
| Unknown | 2         | 5.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 23        | 67.65%  |
| DIMM         | 6         | 17.65%  |
| Row Of Chips | 4         | 11.76%  |
| Unknown      | 1         | 2.94%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 15        | 39.47%  |
| 8192  | 10        | 26.32%  |
| 16384 | 7         | 18.42%  |
| 32768 | 4         | 10.53%  |
| 2048  | 2         | 5.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 9         | 25%     |
| 1600  | 8         | 22.22%  |
| 2400  | 7         | 19.44%  |
| 4267  | 2         | 5.56%   |
| 2133  | 2         | 5.56%   |
| 1867  | 2         | 5.56%   |
| 1066  | 2         | 5.56%   |
| 3200  | 1         | 2.78%   |
| 1333  | 1         | 2.78%   |
| 1067  | 1         | 2.78%   |
| 800   | 1         | 2.78%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Brother Industries | 2         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 8         | 16.67%  |
| Apple                                  | 7         | 14.58%  |
| Realtek Semiconductor                  | 6         | 12.5%   |
| Alcor Micro                            | 6         | 12.5%   |
| Bison Electronics                      | 5         | 10.42%  |
| Sunplus Innovation Technology          | 3         | 6.25%   |
| Suyin                                  | 2         | 4.17%   |
| Quanta                                 | 2         | 4.17%   |
| Silicon Motion                         | 1         | 2.08%   |
| Microdia                               | 1         | 2.08%   |
| Logitech                               | 1         | 2.08%   |
| Lite-On Technology                     | 1         | 2.08%   |
| IMC Networks                           | 1         | 2.08%   |
| Google                                 | 1         | 2.08%   |
| Genesys Logic                          | 1         | 2.08%   |
| Denron                                 | 1         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Alcor Micro HD WebCam                                                      | 5         | 10.2%   |
| Apple Built-in iSight                                                      | 4         | 8.16%   |
| Realtek USB2.0 camera                                                      | 2         | 4.08%   |
| Chicony HD User Facing                                                     | 2         | 4.08%   |
| Bison SunplusIT INC. Integrated Camera                                     | 2         | 4.08%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 2         | 4.08%   |
| Suyin HP TrueVision Full HD                                                | 1         | 2.04%   |
| Suyin HP Integrated Webcam                                                 | 1         | 2.04%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 2.04%   |
| Sunplus Integrated Camera                                                  | 1         | 2.04%   |
| Sunplus HD WebCam                                                          | 1         | 2.04%   |
| Silicon Motion WebCam SC-13HDL12131N                                       | 1         | 2.04%   |
| Realtek Lenovo EasyCamera                                                  | 1         | 2.04%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 2.04%   |
| Realtek Integrated Webcam                                                  | 1         | 2.04%   |
| Realtek HP Truevision HD                                                   | 1         | 2.04%   |
| Quanta HD User Facing                                                      | 1         | 2.04%   |
| Quanta HD Camera                                                           | 1         | 2.04%   |
| Microdia HP Integrated Webcam                                              | 1         | 2.04%   |
| Logitech C922 Pro Stream Webcam                                            | 1         | 2.04%   |
| Lite-On Integrated Camera                                                  | 1         | 2.04%   |
| IMC Networks Lenovo EasyCamera                                             | 1         | 2.04%   |
| Genesys Logic Camera                                                       | 1         | 2.04%   |
| Denron 2M Front Camera                                                     | 1         | 2.04%   |
| Chicony USB2.0 UVC WebCam                                                  | 1         | 2.04%   |
| Chicony USB 2.0 Camera                                                     | 1         | 2.04%   |
| Chicony LG HD WebCam                                                       | 1         | 2.04%   |
| Chicony Integrated Camera                                                  | 1         | 2.04%   |
| Chicony HP TrueVision HD Camera                                            | 1         | 2.04%   |
| Chicony FJ Camera                                                          | 1         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 1         | 2.04%   |
| Bison SunplusIT Integrated Camera                                          | 1         | 2.04%   |
| Bison Lenovo EasyCamera                                                    | 1         | 2.04%   |
| Bison BisonCam, NB Pro                                                     | 1         | 2.04%   |
| Apple iBridge                                                              | 1         | 2.04%   |
| Apple FaceTime HD Camera (Built-in)                                        | 1         | 2.04%   |
| Alcor Micro HP Webcam-101                                                  | 1         | 2.04%   |
| Unknown                                                                    | 1         | 2.04%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 6         | 54.55%  |
| Synaptics             | 2         | 18.18%  |
| LighTuning Technology | 2         | 18.18%  |
| STMicroelectronics    | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor      | 4         | 36.36%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 9.09%   |
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 9.09%   |
| Synaptics Prometheus Fingerprint Reader           | 1         | 9.09%   |
| Synaptics Metallica MOH Touch Fingerprint Reader  | 1         | 9.09%   |
| STMicroelectronics Fingerprint Reader             | 1         | 9.09%   |
| LighTuning ES603 Swipe Fingerprint Sensor         | 1         | 9.09%   |
| LighTuning EgisTec Touch Fingerprint Sensor       | 1         | 9.09%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Purism, SPC               | 4         | 36.36%  |
| Alcor Micro               | 3         | 27.27%  |
| Realtek Semiconductor     | 1         | 9.09%   |
| O2 Micro                  | 1         | 9.09%   |
| Clay Logic                | 1         | 9.09%   |
| Aladdin Knowledge Systems | 1         | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Purism, SPC Librem Key                            | 4         | 36.36%  |
| Alcor Micro AU9540 Smartcard Reader               | 3         | 27.27%  |
| Realtek Semiconductor Smart Card Reader Interface | 1         | 9.09%   |
| O2 Micro Oz776 SmartCard Reader                   | 1         | 9.09%   |
| Clay Logic Nitrokey Pro                           | 1         | 9.09%   |
| Aladdin Knowledge Systems Token JC                | 1         | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 45        | 54.22%  |
| 1     | 28        | 33.73%  |
| 2     | 6         | 7.23%   |
| 4     | 2         | 2.41%   |
| 5     | 1         | 1.2%    |
| 3     | 1         | 1.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Net/wireless             | 15        | 27.78%  |
| Fingerprint reader       | 11        | 20.37%  |
| Graphics card            | 9         | 16.67%  |
| Bluetooth                | 9         | 16.67%  |
| Multimedia controller    | 4         | 7.41%   |
| Chipcard                 | 4         | 7.41%   |
| Communication controller | 1         | 1.85%   |
| Camera                   | 1         | 1.85%   |

