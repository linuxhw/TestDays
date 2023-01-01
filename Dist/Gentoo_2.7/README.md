Gentoo 2.7 - Tested Hardware & Statistics
-----------------------------------------

A project to collect tested hardware configurations for Gentoo 2.7.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Gentoo_2.7/Desktop/README.md) and [notebooks](/Dist/Gentoo_2.7/Notebook/README.md).

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 892

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Toshiba       | Satellite A200              | Notebook    | [d030e357db](https://linux-hardware.org/?probe=d030e357db) | Jul 02, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [9d03e8cba7](https://linux-hardware.org/?probe=9d03e8cba7) | Jun 18, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [fd5c0c6f83](https://linux-hardware.org/?probe=fd5c0c6f83) | Jun 06, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [bd36f27f9b](https://linux-hardware.org/?probe=bd36f27f9b) | May 29, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [b253c6e007](https://linux-hardware.org/?probe=b253c6e007) | May 24, 2022 |
| ASRockRack    | E3C232D2I                   | Desktop     | [0442460b97](https://linux-hardware.org/?probe=0442460b97) | May 24, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [93700a286d](https://linux-hardware.org/?probe=93700a286d) | May 23, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [f129f3b1d5](https://linux-hardware.org/?probe=f129f3b1d5) | May 22, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [d5477b3bb9](https://linux-hardware.org/?probe=d5477b3bb9) | May 17, 2022 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [818ee286b7](https://linux-hardware.org/?probe=818ee286b7) | May 17, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [0de514cd0b](https://linux-hardware.org/?probe=0de514cd0b) | May 16, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [f64f274146](https://linux-hardware.org/?probe=f64f274146) | May 16, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [28b47bc364](https://linux-hardware.org/?probe=28b47bc364) | May 15, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [020e862674](https://linux-hardware.org/?probe=020e862674) | May 15, 2022 |
| HP            | Pavilion ZV6100 (EE984EA... | Notebook    | [59c5dbcb22](https://linux-hardware.org/?probe=59c5dbcb22) | May 15, 2022 |
| ASUSTek       | Z8NR-D12                    | Desktop     | [e65adcd0da](https://linux-hardware.org/?probe=e65adcd0da) | May 14, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [cf73bc12e8](https://linux-hardware.org/?probe=cf73bc12e8) | May 13, 2022 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [8328bbecb9](https://linux-hardware.org/?probe=8328bbecb9) | May 12, 2022 |
| HP            | 8704                        | Desktop     | [b66f290b02](https://linux-hardware.org/?probe=b66f290b02) | May 09, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [81aa293c77](https://linux-hardware.org/?probe=81aa293c77) | May 08, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [8919eebaa3](https://linux-hardware.org/?probe=8919eebaa3) | May 05, 2022 |
| ASRock        | A320M Pro4                  | Desktop     | [b51c7ae18b](https://linux-hardware.org/?probe=b51c7ae18b) | May 04, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [01369642f4](https://linux-hardware.org/?probe=01369642f4) | May 03, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [fcca76f1e5](https://linux-hardware.org/?probe=fcca76f1e5) | May 01, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [94d74e9b78](https://linux-hardware.org/?probe=94d74e9b78) | Apr 29, 2022 |
| Dell          | G3 3500                     | Notebook    | [e3f0210b87](https://linux-hardware.org/?probe=e3f0210b87) | Apr 24, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [46dd37cb4b](https://linux-hardware.org/?probe=46dd37cb4b) | Apr 16, 2022 |
| ASUSTek       | Z97-K/USB                   | Desktop     | [16aaadda77](https://linux-hardware.org/?probe=16aaadda77) | Apr 14, 2022 |
| Gigabyte      | B460 HD3                    | Desktop     | [c3c9ea3a20](https://linux-hardware.org/?probe=c3c9ea3a20) | Apr 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [dccdc2c9f5](https://linux-hardware.org/?probe=dccdc2c9f5) | Apr 12, 2022 |
| Dell          | Precision 7560              | Notebook    | [f8641cc115](https://linux-hardware.org/?probe=f8641cc115) | Apr 10, 2022 |
| Apple         | MacBookAir3,1               | Notebook    | [212412e4d5](https://linux-hardware.org/?probe=212412e4d5) | Apr 09, 2022 |
| ASRock        | Z390 Extreme4               | Desktop     | [ed2dd10e6e](https://linux-hardware.org/?probe=ed2dd10e6e) | Apr 09, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [3f086610fc](https://linux-hardware.org/?probe=3f086610fc) | Apr 05, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [368a64422d](https://linux-hardware.org/?probe=368a64422d) | Apr 03, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [b47301d663](https://linux-hardware.org/?probe=b47301d663) | Mar 31, 2022 |
| HP            | Pavilion ZV6100 (EE984EA... | Notebook    | [282dfe7eb0](https://linux-hardware.org/?probe=282dfe7eb0) | Mar 23, 2022 |
| Dell          | XPS 12-9Q33                 | Notebook    | [f4829632f8](https://linux-hardware.org/?probe=f4829632f8) | Mar 20, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [3be092b600](https://linux-hardware.org/?probe=3be092b600) | Mar 18, 2022 |
| MSI           | B560M PRO-VDH WIFI          | Desktop     | [c15007b668](https://linux-hardware.org/?probe=c15007b668) | Mar 15, 2022 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [adad5f6ce0](https://linux-hardware.org/?probe=adad5f6ce0) | Mar 15, 2022 |
| Alienware     | 0TYR0X A00                  | Desktop     | [b82ab5d2d7](https://linux-hardware.org/?probe=b82ab5d2d7) | Mar 14, 2022 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [6b45f989ae](https://linux-hardware.org/?probe=6b45f989ae) | Mar 13, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [624daf4b10](https://linux-hardware.org/?probe=624daf4b10) | Mar 12, 2022 |
| Toshiba       | Satellite L50-C             | Notebook    | [0e6289a2ad](https://linux-hardware.org/?probe=0e6289a2ad) | Mar 04, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [5c95114871](https://linux-hardware.org/?probe=5c95114871) | Mar 02, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [6931b9fe82](https://linux-hardware.org/?probe=6931b9fe82) | Mar 02, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [842379fc35](https://linux-hardware.org/?probe=842379fc35) | Mar 01, 2022 |
| Alienware     | 0TYR0X A00                  | Desktop     | [17eda5de26](https://linux-hardware.org/?probe=17eda5de26) | Feb 28, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [875e06d62c](https://linux-hardware.org/?probe=875e06d62c) | Feb 27, 2022 |
| MSI           | H81I                        | Desktop     | [c556e9c713](https://linux-hardware.org/?probe=c556e9c713) | Feb 20, 2022 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [8b0dc90a9e](https://linux-hardware.org/?probe=8b0dc90a9e) | Feb 19, 2022 |
| Lenovo        | Legion Y530-15ICH-1060 8... | Notebook    | [9df089b1ef](https://linux-hardware.org/?probe=9df089b1ef) | Feb 19, 2022 |
| Gigabyte      | B460 HD3                    | Desktop     | [661166a163](https://linux-hardware.org/?probe=661166a163) | Feb 17, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [6278830433](https://linux-hardware.org/?probe=6278830433) | Feb 17, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [7737b54f68](https://linux-hardware.org/?probe=7737b54f68) | Feb 16, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [92456282bc](https://linux-hardware.org/?probe=92456282bc) | Feb 14, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [8286f26e6e](https://linux-hardware.org/?probe=8286f26e6e) | Feb 12, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [a8d3ef29f1](https://linux-hardware.org/?probe=a8d3ef29f1) | Feb 11, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [49cf4eba76](https://linux-hardware.org/?probe=49cf4eba76) | Feb 08, 2022 |
| Lenovo        | ThinkPad X13 Yoga Gen 2 ... | Convertible | [661baafcd7](https://linux-hardware.org/?probe=661baafcd7) | Feb 07, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [68c1afd184](https://linux-hardware.org/?probe=68c1afd184) | Feb 06, 2022 |
| Samsung       | RC530/RC730                 | Notebook    | [c4651bdbc6](https://linux-hardware.org/?probe=c4651bdbc6) | Jan 31, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [f49f9dddd2](https://linux-hardware.org/?probe=f49f9dddd2) | Jan 29, 2022 |
| Dell          | Precision 7520              | Notebook    | [4cdcfc0e31](https://linux-hardware.org/?probe=4cdcfc0e31) | Jan 29, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [cd1ab231e7](https://linux-hardware.org/?probe=cd1ab231e7) | Jan 28, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [1ccb1fd970](https://linux-hardware.org/?probe=1ccb1fd970) | Jan 23, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [ab4793dc5e](https://linux-hardware.org/?probe=ab4793dc5e) | Jan 22, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [0799e18f8b](https://linux-hardware.org/?probe=0799e18f8b) | Jan 20, 2022 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [d1697052d6](https://linux-hardware.org/?probe=d1697052d6) | Jan 20, 2022 |
| ASRock        | AM1H-ITX                    | Desktop     | [d22612635e](https://linux-hardware.org/?probe=d22612635e) | Jan 16, 2022 |
| Gigabyte      | AX370-Gaming 3-CF           | Desktop     | [73773b7de6](https://linux-hardware.org/?probe=73773b7de6) | Jan 16, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [cdb65d6460](https://linux-hardware.org/?probe=cdb65d6460) | Jan 13, 2022 |
| Dell          | Inspiron 5402               | Notebook    | [6b764029b7](https://linux-hardware.org/?probe=6b764029b7) | Jan 11, 2022 |
| Dell          | Inspiron 5402               | Notebook    | [60f264617e](https://linux-hardware.org/?probe=60f264617e) | Jan 11, 2022 |
| ASRock        | AM1H-ITX                    | Desktop     | [32aec4ead0](https://linux-hardware.org/?probe=32aec4ead0) | Jan 10, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [a519d3f9af](https://linux-hardware.org/?probe=a519d3f9af) | Jan 07, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [596fafa091](https://linux-hardware.org/?probe=596fafa091) | Jan 07, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [d4b7cd87ac](https://linux-hardware.org/?probe=d4b7cd87ac) | Jan 05, 2022 |
| ASRock        | Q1900-ITX                   | Desktop     | [e7b19454b7](https://linux-hardware.org/?probe=e7b19454b7) | Jan 04, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [519b9f223e](https://linux-hardware.org/?probe=519b9f223e) | Jan 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [08b04c15d3](https://linux-hardware.org/?probe=08b04c15d3) | Jan 03, 2022 |
| Dell          | Precision 7560              | Notebook    | [158ff657e7](https://linux-hardware.org/?probe=158ff657e7) | Jan 02, 2022 |
| Timi          | A35                         | Notebook    | [253959bb70](https://linux-hardware.org/?probe=253959bb70) | Dec 30, 2021 |
| Lenovo        | ThinkPad T480s 20L7001MR... | Notebook    | [199482a1fe](https://linux-hardware.org/?probe=199482a1fe) | Dec 26, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [913bb7bf0b](https://linux-hardware.org/?probe=913bb7bf0b) | Dec 25, 2021 |
| Timi          | A35                         | Notebook    | [66e9c6919d](https://linux-hardware.org/?probe=66e9c6919d) | Dec 24, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [83ff6966e1](https://linux-hardware.org/?probe=83ff6966e1) | Dec 24, 2021 |
| Apple         | MacBook10,1                 | Notebook    | [4b98d2c8ba](https://linux-hardware.org/?probe=4b98d2c8ba) | Dec 24, 2021 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [2144a3a32c](https://linux-hardware.org/?probe=2144a3a32c) | Dec 23, 2021 |
| Dell          | 0J3C2F A02                  | Desktop     | [a450e584b2](https://linux-hardware.org/?probe=a450e584b2) | Dec 22, 2021 |
| Dell          | Inspiron 15 5510            | Notebook    | [2018752b06](https://linux-hardware.org/?probe=2018752b06) | Dec 21, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [201e93fd24](https://linux-hardware.org/?probe=201e93fd24) | Dec 20, 2021 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [b03f7a8ab8](https://linux-hardware.org/?probe=b03f7a8ab8) | Dec 20, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [fbd0755545](https://linux-hardware.org/?probe=fbd0755545) | Dec 19, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [d01abdcb39](https://linux-hardware.org/?probe=d01abdcb39) | Dec 19, 2021 |
| Dell          | Latitude 5420               | Notebook    | [f8313f07c4](https://linux-hardware.org/?probe=f8313f07c4) | Dec 18, 2021 |
| HP            | EliteBook 830 G5            | Notebook    | [bf884733a1](https://linux-hardware.org/?probe=bf884733a1) | Dec 16, 2021 |
| Dell          | 0J3C2F A02                  | Desktop     | [b6d326beab](https://linux-hardware.org/?probe=b6d326beab) | Dec 16, 2021 |
| HP            | EliteBook 830 G5            | Notebook    | [61d4bff2bd](https://linux-hardware.org/?probe=61d4bff2bd) | Dec 15, 2021 |
| MSI           | Z87-G45 GAMING              | Desktop     | [882428b431](https://linux-hardware.org/?probe=882428b431) | Dec 15, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [d94711b81b](https://linux-hardware.org/?probe=d94711b81b) | Dec 13, 2021 |
| Dell          | XPS 17 9710                 | Notebook    | [ade9c0e3ec](https://linux-hardware.org/?probe=ade9c0e3ec) | Dec 13, 2021 |
| ASUSTek       | M3N78-EM                    | Desktop     | [bf180c5c33](https://linux-hardware.org/?probe=bf180c5c33) | Dec 11, 2021 |
| Dell          | XPS 17 9710                 | Notebook    | [fd6cff7345](https://linux-hardware.org/?probe=fd6cff7345) | Dec 10, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [4b39700892](https://linux-hardware.org/?probe=4b39700892) | Dec 09, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [53fb790458](https://linux-hardware.org/?probe=53fb790458) | Dec 08, 2021 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [208868fbae](https://linux-hardware.org/?probe=208868fbae) | Dec 07, 2021 |
| ASUSTek       | X200MA                      | Notebook    | [c81483b4db](https://linux-hardware.org/?probe=c81483b4db) | Dec 04, 2021 |
| Samsung       | RC530/RC730                 | Notebook    | [6105853b97](https://linux-hardware.org/?probe=6105853b97) | Dec 04, 2021 |
| Dell          | 0J584C A00                  | Desktop     | [d443412bd4](https://linux-hardware.org/?probe=d443412bd4) | Dec 03, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [903f3e93ee](https://linux-hardware.org/?probe=903f3e93ee) | Dec 03, 2021 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [5c530c94b3](https://linux-hardware.org/?probe=5c530c94b3) | Dec 02, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [7a8a79d813](https://linux-hardware.org/?probe=7a8a79d813) | Dec 02, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [baa3bf4a04](https://linux-hardware.org/?probe=baa3bf4a04) | Nov 27, 2021 |
| Timi          | A35                         | Notebook    | [d1461858c8](https://linux-hardware.org/?probe=d1461858c8) | Nov 27, 2021 |
| Toshiba       | Satellite C850D-118         | Notebook    | [db07af607f](https://linux-hardware.org/?probe=db07af607f) | Nov 26, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [b0329b0b3f](https://linux-hardware.org/?probe=b0329b0b3f) | Nov 25, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [4492677869](https://linux-hardware.org/?probe=4492677869) | Nov 24, 2021 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [58684dd498](https://linux-hardware.org/?probe=58684dd498) | Nov 23, 2021 |
| SIEMENS       | SIMATIC Field PG M6         | Notebook    | [a0e1ef3935](https://linux-hardware.org/?probe=a0e1ef3935) | Nov 22, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [89c87a0f8c](https://linux-hardware.org/?probe=89c87a0f8c) | Nov 21, 2021 |
| HP            | Compaq 6730b (KE717AV)      | Notebook    | [71527b8152](https://linux-hardware.org/?probe=71527b8152) | Nov 21, 2021 |
| Supermicro    | A2SDV-4C-LN8F               | Server      | [f96b0cfda0](https://linux-hardware.org/?probe=f96b0cfda0) | Nov 21, 2021 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [674bb00d63](https://linux-hardware.org/?probe=674bb00d63) | Nov 21, 2021 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [47908fe107](https://linux-hardware.org/?probe=47908fe107) | Nov 21, 2021 |
| HP            | ProLiant ML150 G6           | Desktop     | [ddb6ba2a2b](https://linux-hardware.org/?probe=ddb6ba2a2b) | Nov 21, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [f8501c9239](https://linux-hardware.org/?probe=f8501c9239) | Nov 21, 2021 |
| HP            | ProLiant ML150 G6           | Desktop     | [734028d2b9](https://linux-hardware.org/?probe=734028d2b9) | Nov 21, 2021 |
| Supermicro    | A2SDV-4C-LN8F               | Server      | [48a89bb904](https://linux-hardware.org/?probe=48a89bb904) | Nov 21, 2021 |
| Intel         | DP35DP AAD81073-205         | Desktop     | [be9ba487cd](https://linux-hardware.org/?probe=be9ba487cd) | Nov 21, 2021 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [10578c9535](https://linux-hardware.org/?probe=10578c9535) | Nov 18, 2021 |
| HP            | ProBook 430 G5              | Notebook    | [634b7c7102](https://linux-hardware.org/?probe=634b7c7102) | Nov 18, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [cf48db68a3](https://linux-hardware.org/?probe=cf48db68a3) | Nov 18, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [05879919b0](https://linux-hardware.org/?probe=05879919b0) | Nov 17, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [6d93d44cf9](https://linux-hardware.org/?probe=6d93d44cf9) | Nov 17, 2021 |
| Gigabyte      | B150M-HD3-CF                | Desktop     | [c35117afe2](https://linux-hardware.org/?probe=c35117afe2) | Nov 17, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [5f0f191f13](https://linux-hardware.org/?probe=5f0f191f13) | Nov 16, 2021 |
| MOTILE        | M142                        | Notebook    | [d56931cbc6](https://linux-hardware.org/?probe=d56931cbc6) | Nov 15, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [5c55a759db](https://linux-hardware.org/?probe=5c55a759db) | Nov 13, 2021 |
| HP            | EliteBook 745 G6            | Notebook    | [a4bc523c79](https://linux-hardware.org/?probe=a4bc523c79) | Nov 12, 2021 |
| HP            | EliteBook 745 G6            | Notebook    | [faa7680568](https://linux-hardware.org/?probe=faa7680568) | Nov 12, 2021 |
| Lenovo        | XiaoXin Chao7000-14IKBR ... | Notebook    | [531b838f59](https://linux-hardware.org/?probe=531b838f59) | Nov 09, 2021 |
| Lenovo        | XiaoXin Chao7000-14IKBR ... | Notebook    | [8ea29d23df](https://linux-hardware.org/?probe=8ea29d23df) | Nov 09, 2021 |
| ASUSTek       | 900                         | Notebook    | [b3f1475dcf](https://linux-hardware.org/?probe=b3f1475dcf) | Nov 08, 2021 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [efd3dadc76](https://linux-hardware.org/?probe=efd3dadc76) | Nov 08, 2021 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [76d6e63da5](https://linux-hardware.org/?probe=76d6e63da5) | Nov 07, 2021 |
| ASRock        | B550M Steel Legend          | Desktop     | [fada2e4c02](https://linux-hardware.org/?probe=fada2e4c02) | Nov 06, 2021 |
| ASUSTek       | P5LD2-Deluxe                | Desktop     | [d1dcf79c72](https://linux-hardware.org/?probe=d1dcf79c72) | Nov 05, 2021 |
| Dell          | Latitude E7440              | Notebook    | [96a92b3d98](https://linux-hardware.org/?probe=96a92b3d98) | Nov 04, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [3691e08d6d](https://linux-hardware.org/?probe=3691e08d6d) | Nov 03, 2021 |
| Dell          | Latitude 5520               | Notebook    | [49a6b5ef90](https://linux-hardware.org/?probe=49a6b5ef90) | Nov 01, 2021 |
| Purism        | librem_15v4                 | Notebook    | [f3e5eba0c2](https://linux-hardware.org/?probe=f3e5eba0c2) | Oct 31, 2021 |
| Purism        | librem_15v4                 | Notebook    | [c74129a618](https://linux-hardware.org/?probe=c74129a618) | Oct 31, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [1719b2dc9d](https://linux-hardware.org/?probe=1719b2dc9d) | Oct 30, 2021 |
| ASUSTek       | X556URK                     | Notebook    | [212240b258](https://linux-hardware.org/?probe=212240b258) | Oct 29, 2021 |
| Gigabyte      | B460 HD3                    | Desktop     | [d3aa74a821](https://linux-hardware.org/?probe=d3aa74a821) | Oct 29, 2021 |
| ASRock        | B550M Steel Legend          | Desktop     | [df8ab9effb](https://linux-hardware.org/?probe=df8ab9effb) | Oct 28, 2021 |
| Supermicro    | X10SRA                      | Server      | [6a333a499d](https://linux-hardware.org/?probe=6a333a499d) | Oct 28, 2021 |
| Dell          | Latitude E6530              | Notebook    | [fd1375d5f1](https://linux-hardware.org/?probe=fd1375d5f1) | Oct 28, 2021 |
| Dell          | Latitude E6530              | Notebook    | [f37394899f](https://linux-hardware.org/?probe=f37394899f) | Oct 28, 2021 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [6f6e5daf18](https://linux-hardware.org/?probe=6f6e5daf18) | Oct 28, 2021 |
| HP            | ProLiant DL380 G7           | Server      | [a9c87c6c9c](https://linux-hardware.org/?probe=a9c87c6c9c) | Oct 27, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [4b691f2884](https://linux-hardware.org/?probe=4b691f2884) | Oct 27, 2021 |
| HP            | 0B4Ch D                     | Desktop     | [eb0c052885](https://linux-hardware.org/?probe=eb0c052885) | Oct 26, 2021 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [740c97fb1c](https://linux-hardware.org/?probe=740c97fb1c) | Oct 26, 2021 |
| ASUSTek       | M3A78-CM                    | Desktop     | [aa48dedaf3](https://linux-hardware.org/?probe=aa48dedaf3) | Oct 25, 2021 |
| ASRock        | X570 Pro4                   | Desktop     | [ba339b925b](https://linux-hardware.org/?probe=ba339b925b) | Oct 21, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [7ffce9bbc2](https://linux-hardware.org/?probe=7ffce9bbc2) | Oct 21, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [b37e349828](https://linux-hardware.org/?probe=b37e349828) | Oct 19, 2021 |
| Fujitsu       | D3417-B2 S26361-D3417-B2    | Desktop     | [8b5c674cb9](https://linux-hardware.org/?probe=8b5c674cb9) | Oct 17, 2021 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [e7ab53c038](https://linux-hardware.org/?probe=e7ab53c038) | Oct 15, 2021 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [42b4e70ef9](https://linux-hardware.org/?probe=42b4e70ef9) | Oct 15, 2021 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | Desktop     | [38a6005914](https://linux-hardware.org/?probe=38a6005914) | Oct 15, 2021 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | Desktop     | [a6457a6f8e](https://linux-hardware.org/?probe=a6457a6f8e) | Oct 15, 2021 |
| Timi          | RedmiBook 13 R              | Notebook    | [18263076ea](https://linux-hardware.org/?probe=18263076ea) | Oct 14, 2021 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [10d09b7d77](https://linux-hardware.org/?probe=10d09b7d77) | Oct 12, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [d7a870e424](https://linux-hardware.org/?probe=d7a870e424) | Oct 11, 2021 |
| ASRock        | Z390 Extreme4               | Desktop     | [2da9a06ef2](https://linux-hardware.org/?probe=2da9a06ef2) | Oct 11, 2021 |
| Acer          | TravelMate P648-M           | Notebook    | [03350be971](https://linux-hardware.org/?probe=03350be971) | Oct 11, 2021 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [7fbd3218a8](https://linux-hardware.org/?probe=7fbd3218a8) | Oct 11, 2021 |
| Acer          | TravelMate P648-M           | Notebook    | [6e6d3fe55c](https://linux-hardware.org/?probe=6e6d3fe55c) | Oct 10, 2021 |
| IBM           | ThinkPad T43 2668Z3S        | Notebook    | [67510cc1aa](https://linux-hardware.org/?probe=67510cc1aa) | Oct 10, 2021 |
| Timi          | RedmiBook 13 R              | Notebook    | [e6c38e5b79](https://linux-hardware.org/?probe=e6c38e5b79) | Oct 10, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [2e312a734f](https://linux-hardware.org/?probe=2e312a734f) | Oct 08, 2021 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | Desktop     | [8319b2b5c6](https://linux-hardware.org/?probe=8319b2b5c6) | Oct 08, 2021 |
| Intel         | NUC11PHBi7 M26151-402       | Mini pc     | [bc9337f46e](https://linux-hardware.org/?probe=bc9337f46e) | Oct 07, 2021 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [a8ea4ccbef](https://linux-hardware.org/?probe=a8ea4ccbef) | Oct 06, 2021 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [233f451319](https://linux-hardware.org/?probe=233f451319) | Oct 06, 2021 |
| HP            | 0B4Ch D                     | Desktop     | [02b5492901](https://linux-hardware.org/?probe=02b5492901) | Oct 06, 2021 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [634113d340](https://linux-hardware.org/?probe=634113d340) | Oct 06, 2021 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [666f9cb875](https://linux-hardware.org/?probe=666f9cb875) | Oct 06, 2021 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | Desktop     | [67fc73c11e](https://linux-hardware.org/?probe=67fc73c11e) | Oct 04, 2021 |
| MSI           | Z370-A PRO                  | Desktop     | [e7742aa472](https://linux-hardware.org/?probe=e7742aa472) | Oct 03, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [5ce182d7ae](https://linux-hardware.org/?probe=5ce182d7ae) | Oct 01, 2021 |
| ASUSTek       | Unknown                     | Notebook    | [9b357ee9bb](https://linux-hardware.org/?probe=9b357ee9bb) | Oct 01, 2021 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [4044b3b3b2](https://linux-hardware.org/?probe=4044b3b3b2) | Oct 01, 2021 |
| Lenovo        | Legion 5P 15IMH05 82AW      | Notebook    | [fbade9e61e](https://linux-hardware.org/?probe=fbade9e61e) | Oct 01, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [6b625a8736](https://linux-hardware.org/?probe=6b625a8736) | Oct 01, 2021 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [1fce457ac6](https://linux-hardware.org/?probe=1fce457ac6) | Oct 01, 2021 |
| ASUSTek       | X555LJ                      | Notebook    | [dea4201e98](https://linux-hardware.org/?probe=dea4201e98) | Oct 01, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [27707fb954](https://linux-hardware.org/?probe=27707fb954) | Oct 01, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [87f779767d](https://linux-hardware.org/?probe=87f779767d) | Oct 01, 2021 |
| Acer          | Aspire XC-780               | Desktop     | [f723ac396a](https://linux-hardware.org/?probe=f723ac396a) | Oct 01, 2021 |
| HP            | 255 G6 Notebook PC          | Notebook    | [9823c616ed](https://linux-hardware.org/?probe=9823c616ed) | Sep 30, 2021 |
| Lenovo        | ThinkPad X13 Yoga Gen 2 ... | Convertible | [a30ab1431c](https://linux-hardware.org/?probe=a30ab1431c) | Sep 30, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [f7cc61788a](https://linux-hardware.org/?probe=f7cc61788a) | Sep 30, 2021 |
| HP            | ProBook 430 G5              | Notebook    | [6ee2943500](https://linux-hardware.org/?probe=6ee2943500) | Sep 30, 2021 |
| Dell          | Inspiron 5577               | Notebook    | [f5ec85dd12](https://linux-hardware.org/?probe=f5ec85dd12) | Sep 29, 2021 |
| Dell          | Inspiron 5577               | Notebook    | [80e36f9785](https://linux-hardware.org/?probe=80e36f9785) | Sep 29, 2021 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [de13c8f3fa](https://linux-hardware.org/?probe=de13c8f3fa) | Sep 29, 2021 |
| TYAN Compu... | S7025                       | Server      | [6b7a9d9bdb](https://linux-hardware.org/?probe=6b7a9d9bdb) | Sep 29, 2021 |
| ASRock        | H170 Pro4                   | Desktop     | [a0d0f5002e](https://linux-hardware.org/?probe=a0d0f5002e) | Sep 29, 2021 |
| ASRock        | H170 Pro4                   | Desktop     | [5a3652f38b](https://linux-hardware.org/?probe=5a3652f38b) | Sep 29, 2021 |
| Gigabyte      | 990FXA-UD5                  | Desktop     | [c3bb6d3afa](https://linux-hardware.org/?probe=c3bb6d3afa) | Sep 29, 2021 |
| Dell          | 0J3C2F A02                  | Desktop     | [88104169a4](https://linux-hardware.org/?probe=88104169a4) | Sep 28, 2021 |
| Lenovo        | ThinkPad X240 20AMS1LN00    | Notebook    | [71d301cc84](https://linux-hardware.org/?probe=71d301cc84) | Sep 26, 2021 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [241866fa37](https://linux-hardware.org/?probe=241866fa37) | Sep 26, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [116e97036b](https://linux-hardware.org/?probe=116e97036b) | Sep 25, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [8b939aae88](https://linux-hardware.org/?probe=8b939aae88) | Sep 25, 2021 |
| ASUSTek       | GX501VIK                    | Notebook    | [b36bf17cc2](https://linux-hardware.org/?probe=b36bf17cc2) | Sep 24, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 O... | Notebook    | [f40c18c3b8](https://linux-hardware.org/?probe=f40c18c3b8) | Sep 23, 2021 |
| ASRock        | X370 Professional Gaming    | Desktop     | [546f692061](https://linux-hardware.org/?probe=546f692061) | Sep 23, 2021 |
| Intel         | DG31PR AAD97573-205         | Desktop     | [2c022c21f0](https://linux-hardware.org/?probe=2c022c21f0) | Sep 22, 2021 |
| Lenovo        | ThinkPad X13 Yoga Gen 2 ... | Convertible | [ec47ffaeac](https://linux-hardware.org/?probe=ec47ffaeac) | Sep 22, 2021 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y3C... | Notebook    | [4698844ec0](https://linux-hardware.org/?probe=4698844ec0) | Sep 20, 2021 |
| Lenovo        | B51-80 80LM                 | Notebook    | [320ab41cbb](https://linux-hardware.org/?probe=320ab41cbb) | Sep 17, 2021 |
| Tekram Tec... | P6B40-A4X-i440BX Rev        | Desktop     | [86d356f643](https://linux-hardware.org/?probe=86d356f643) | Sep 16, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [2f9b27ad89](https://linux-hardware.org/?probe=2f9b27ad89) | Sep 16, 2021 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [4c18c08616](https://linux-hardware.org/?probe=4c18c08616) | Sep 15, 2021 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [d406b31a3a](https://linux-hardware.org/?probe=d406b31a3a) | Sep 15, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [3d0115d011](https://linux-hardware.org/?probe=3d0115d011) | Sep 15, 2021 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | Desktop     | [308d39b0dc](https://linux-hardware.org/?probe=308d39b0dc) | Sep 15, 2021 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [21e3d9bccb](https://linux-hardware.org/?probe=21e3d9bccb) | Sep 14, 2021 |
| Notebook      | P65xHP                      | Notebook    | [12a7ec2b86](https://linux-hardware.org/?probe=12a7ec2b86) | Sep 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [b1c5ad62b3](https://linux-hardware.org/?probe=b1c5ad62b3) | Sep 13, 2021 |
| Dell          | Latitude 5410               | Notebook    | [97ed647d4c](https://linux-hardware.org/?probe=97ed647d4c) | Sep 10, 2021 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [9dcddb807d](https://linux-hardware.org/?probe=9dcddb807d) | Sep 10, 2021 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [572c0c5198](https://linux-hardware.org/?probe=572c0c5198) | Sep 10, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [36bf3dd55d](https://linux-hardware.org/?probe=36bf3dd55d) | Sep 09, 2021 |
| Intel         | NUC11PHBi7 M26151-402       | Mini pc     | [c18b4f0dab](https://linux-hardware.org/?probe=c18b4f0dab) | Sep 09, 2021 |
| Intel         | NUC11PHBi7 M26151-402       | Mini pc     | [35ee76ca1b](https://linux-hardware.org/?probe=35ee76ca1b) | Sep 08, 2021 |
| ASUSTek       | ZenBook UX425IA_U4700IA     | Notebook    | [fa970f7a80](https://linux-hardware.org/?probe=fa970f7a80) | Sep 08, 2021 |
| HP            | Pavilion g6                 | Notebook    | [1161032a20](https://linux-hardware.org/?probe=1161032a20) | Sep 08, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [19555ed132](https://linux-hardware.org/?probe=19555ed132) | Sep 07, 2021 |
| Dell          | Precision 7560              | Notebook    | [03d7773132](https://linux-hardware.org/?probe=03d7773132) | Sep 06, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [a629879646](https://linux-hardware.org/?probe=a629879646) | Sep 06, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [78fc85808c](https://linux-hardware.org/?probe=78fc85808c) | Sep 05, 2021 |
| ASUSTek       | P5P41C                      | Desktop     | [e68f372c7b](https://linux-hardware.org/?probe=e68f372c7b) | Sep 05, 2021 |
| Tekram Tec... | P6B40-A4X-i440BX Rev        | Desktop     | [f63a2003ab](https://linux-hardware.org/?probe=f63a2003ab) | Sep 05, 2021 |
| ASUSTek       | X550ZA                      | Notebook    | [0d41969b6b](https://linux-hardware.org/?probe=0d41969b6b) | Sep 02, 2021 |
| Dell          | Latitude E6510              | Notebook    | [2ab208b5cd](https://linux-hardware.org/?probe=2ab208b5cd) | Sep 02, 2021 |
| HP            | 255 G6 Notebook PC          | Notebook    | [4f71a8ad02](https://linux-hardware.org/?probe=4f71a8ad02) | Sep 01, 2021 |
| HP            | ZBook 15 G3                 | Notebook    | [d6872bd9e9](https://linux-hardware.org/?probe=d6872bd9e9) | Sep 01, 2021 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | Desktop     | [40d01ef03e](https://linux-hardware.org/?probe=40d01ef03e) | Aug 31, 2021 |
| Lenovo        | Legion 5P 15IMH05 82AW      | Notebook    | [f1b58d72ac](https://linux-hardware.org/?probe=f1b58d72ac) | Aug 31, 2021 |
| Packard Be... | FMCP7AM                     | Desktop     | [6872ae9fb4](https://linux-hardware.org/?probe=6872ae9fb4) | Aug 31, 2021 |
| Gigabyte      | EP43-DS3                    | Desktop     | [0eaf518e06](https://linux-hardware.org/?probe=0eaf518e06) | Aug 29, 2021 |
| Dell          | 0U1325                      | Desktop     | [0a58fab188](https://linux-hardware.org/?probe=0a58fab188) | Aug 28, 2021 |
| IBM           | ThinkPad T42 2373V4F        | Notebook    | [2362291c05](https://linux-hardware.org/?probe=2362291c05) | Aug 28, 2021 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | Desktop     | [00b0f43680](https://linux-hardware.org/?probe=00b0f43680) | Aug 28, 2021 |
| IBM           | ThinkPad T43 2668Z3S        | Notebook    | [5a606b504c](https://linux-hardware.org/?probe=5a606b504c) | Aug 28, 2021 |
| Packard Be... | FMCP7AM                     | Desktop     | [07fb4f5678](https://linux-hardware.org/?probe=07fb4f5678) | Aug 28, 2021 |
| MSI           | MS-7369                     | Desktop     | [0c6668dee5](https://linux-hardware.org/?probe=0c6668dee5) | Aug 28, 2021 |
| IBM           | ThinkPad T43 2668Z3S        | Notebook    | [2af8736235](https://linux-hardware.org/?probe=2af8736235) | Aug 28, 2021 |
| Dell          | 0U1325                      | Desktop     | [1b5dfb4b59](https://linux-hardware.org/?probe=1b5dfb4b59) | Aug 28, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [aabbe0dbcc](https://linux-hardware.org/?probe=aabbe0dbcc) | Aug 26, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | Notebook    | [cf76a62cf4](https://linux-hardware.org/?probe=cf76a62cf4) | Aug 26, 2021 |
| HP            | 255 G6 Notebook PC          | Notebook    | [b776f7f3b7](https://linux-hardware.org/?probe=b776f7f3b7) | Aug 26, 2021 |
| ASUSTek       | P9X79 WS                    | Desktop     | [0569365ea0](https://linux-hardware.org/?probe=0569365ea0) | Aug 26, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | Notebook    | [62ba09ac38](https://linux-hardware.org/?probe=62ba09ac38) | Aug 26, 2021 |
| Lenovo        | Legion 5P 15IMH05 82AW      | Notebook    | [994e94defa](https://linux-hardware.org/?probe=994e94defa) | Aug 26, 2021 |
| Lenovo        | ThinkPad X230 23259H1       | Notebook    | [fb125d2779](https://linux-hardware.org/?probe=fb125d2779) | Aug 25, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [f521a0c69c](https://linux-hardware.org/?probe=f521a0c69c) | Aug 25, 2021 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [c09944da60](https://linux-hardware.org/?probe=c09944da60) | Aug 24, 2021 |
| Supermicro    | X10SAE                      | Server      | [019914cc29](https://linux-hardware.org/?probe=019914cc29) | Aug 24, 2021 |
| Gigabyte      | Z170-Gaming K3-CF           | Desktop     | [ae02b6e88b](https://linux-hardware.org/?probe=ae02b6e88b) | Aug 19, 2021 |
| ASUSTek       | P5P41C                      | Desktop     | [0eb4111089](https://linux-hardware.org/?probe=0eb4111089) | Aug 18, 2021 |
| NZXT          | N7 Z370                     | Desktop     | [4eb4c77752](https://linux-hardware.org/?probe=4eb4c77752) | Aug 18, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [5ffe57957d](https://linux-hardware.org/?probe=5ffe57957d) | Aug 18, 2021 |
| NZXT          | N7 Z370                     | Desktop     | [40f0739800](https://linux-hardware.org/?probe=40f0739800) | Aug 17, 2021 |
| Dell          | Inspiron 5415               | Notebook    | [909e2cdc93](https://linux-hardware.org/?probe=909e2cdc93) | Aug 15, 2021 |
| Tekram Tec... | P6B40-A4X-i440BX Rev        | Desktop     | [211803a510](https://linux-hardware.org/?probe=211803a510) | Aug 15, 2021 |
| MSI           | B550-A PRO                  | Desktop     | [b3ff3985c5](https://linux-hardware.org/?probe=b3ff3985c5) | Aug 13, 2021 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [843279faa7](https://linux-hardware.org/?probe=843279faa7) | Aug 13, 2021 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [28ecd70483](https://linux-hardware.org/?probe=28ecd70483) | Aug 12, 2021 |
| HP            | 158B                        | Desktop     | [d47aa82b20](https://linux-hardware.org/?probe=d47aa82b20) | Aug 12, 2021 |
| Intel         | D525MW AAE93082-301         | Desktop     | [fc72f0a0ea](https://linux-hardware.org/?probe=fc72f0a0ea) | Aug 11, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [21b619d91b](https://linux-hardware.org/?probe=21b619d91b) | Aug 11, 2021 |
| Dell          | Inspiron 5415               | Notebook    | [63594290cf](https://linux-hardware.org/?probe=63594290cf) | Aug 11, 2021 |
| TUXEDO        | Book XC1711                 | Notebook    | [806e284c8a](https://linux-hardware.org/?probe=806e284c8a) | Aug 11, 2021 |
| Jumper        | EZpad                       | Notebook    | [da2436c208](https://linux-hardware.org/?probe=da2436c208) | Aug 11, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [d74d9e37ce](https://linux-hardware.org/?probe=d74d9e37ce) | Aug 10, 2021 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [aaef52aca2](https://linux-hardware.org/?probe=aaef52aca2) | Aug 10, 2021 |
| Jumper        | EZpad                       | Notebook    | [6215ba7396](https://linux-hardware.org/?probe=6215ba7396) | Aug 10, 2021 |
| Tekram Tec... | P6B40-A4X-i440BX Rev        | Desktop     | [33fffaf1c3](https://linux-hardware.org/?probe=33fffaf1c3) | Aug 07, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [ddf6a2277a](https://linux-hardware.org/?probe=ddf6a2277a) | Aug 07, 2021 |
| MSI           | GF63 Thin 9SCSR             | Notebook    | [0fac51313a](https://linux-hardware.org/?probe=0fac51313a) | Aug 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [30131c51fb](https://linux-hardware.org/?probe=30131c51fb) | Aug 05, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [ef7a0635f4](https://linux-hardware.org/?probe=ef7a0635f4) | Aug 04, 2021 |
| ASUSTek       | X510UR                      | Notebook    | [8e08727583](https://linux-hardware.org/?probe=8e08727583) | Aug 03, 2021 |
| TUXEDO        | Book_XA1510                 | Notebook    | [f4f777ed12](https://linux-hardware.org/?probe=f4f777ed12) | Aug 03, 2021 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [51a1b8132e](https://linux-hardware.org/?probe=51a1b8132e) | Aug 01, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [754750effc](https://linux-hardware.org/?probe=754750effc) | Jul 31, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [0f19cc3c0e](https://linux-hardware.org/?probe=0f19cc3c0e) | Jul 31, 2021 |
| Dell          | 09WH54 A00                  | Desktop     | [9885d45d4f](https://linux-hardware.org/?probe=9885d45d4f) | Jul 28, 2021 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [380758e335](https://linux-hardware.org/?probe=380758e335) | Jul 28, 2021 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [a5a11a0de1](https://linux-hardware.org/?probe=a5a11a0de1) | Jul 28, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [46b71409d7](https://linux-hardware.org/?probe=46b71409d7) | Jul 27, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c824226d1e](https://linux-hardware.org/?probe=c824226d1e) | Jul 26, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [f22f34ea9a](https://linux-hardware.org/?probe=f22f34ea9a) | Jul 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [3de3129139](https://linux-hardware.org/?probe=3de3129139) | Jul 22, 2021 |
| Gigabyte      | 990FXA-UD5                  | Desktop     | [5a32ec902e](https://linux-hardware.org/?probe=5a32ec902e) | Jul 22, 2021 |
| Gigabyte      | H110-D3-CF                  | Desktop     | [7d25217f50](https://linux-hardware.org/?probe=7d25217f50) | Jul 22, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [c6a7c7d9d8](https://linux-hardware.org/?probe=c6a7c7d9d8) | Jul 19, 2021 |
| Gigabyte      | B460 HD3                    | Desktop     | [a43624a24b](https://linux-hardware.org/?probe=a43624a24b) | Jul 18, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [236639a923](https://linux-hardware.org/?probe=236639a923) | Jul 16, 2021 |
| Lenovo        | ThinkPad T480 20L5000AMC    | Notebook    | [4b6bb5e980](https://linux-hardware.org/?probe=4b6bb5e980) | Jul 16, 2021 |
| Dell          | Latitude E6430              | Notebook    | [3dc281ca01](https://linux-hardware.org/?probe=3dc281ca01) | Jul 13, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [9356542b15](https://linux-hardware.org/?probe=9356542b15) | Jul 12, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [6835266a32](https://linux-hardware.org/?probe=6835266a32) | Jul 10, 2021 |
| ASRock        | B550M Steel Legend          | Desktop     | [4d378eb681](https://linux-hardware.org/?probe=4d378eb681) | Jul 10, 2021 |
| MSI           | MEG X570 GODLIKE            | Desktop     | [517a612c58](https://linux-hardware.org/?probe=517a612c58) | Jul 10, 2021 |
| Dell          | Latitude E6430              | Notebook    | [f5a73f4d90](https://linux-hardware.org/?probe=f5a73f4d90) | Jul 09, 2021 |
| Dell          | Latitude E6430              | Notebook    | [8d685287ce](https://linux-hardware.org/?probe=8d685287ce) | Jul 09, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [68c41ed42b](https://linux-hardware.org/?probe=68c41ed42b) | Jul 08, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [5a6fca486a](https://linux-hardware.org/?probe=5a6fca486a) | Jul 08, 2021 |
| ASRock        | B550M Steel Legend          | Desktop     | [ab93056d13](https://linux-hardware.org/?probe=ab93056d13) | Jul 08, 2021 |
| Acer          | Aspire A315-32              | Notebook    | [3a9edbefac](https://linux-hardware.org/?probe=3a9edbefac) | Jul 06, 2021 |
| Acer          | Aspire A315-32              | Notebook    | [09f71bed72](https://linux-hardware.org/?probe=09f71bed72) | Jul 06, 2021 |
| MSI           | Z590-A PRO                  | Desktop     | [50d75ad77d](https://linux-hardware.org/?probe=50d75ad77d) | Jul 03, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [4ef1e3ccac](https://linux-hardware.org/?probe=4ef1e3ccac) | Jul 03, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [4e618f85f9](https://linux-hardware.org/?probe=4e618f85f9) | Jul 03, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [a2acbde7fd](https://linux-hardware.org/?probe=a2acbde7fd) | Jul 02, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [cbb60edb8c](https://linux-hardware.org/?probe=cbb60edb8c) | Jul 02, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [26a655c4b4](https://linux-hardware.org/?probe=26a655c4b4) | Jul 02, 2021 |
| Intel         | DZ77BH-55K AAG39008-400     | Desktop     | [04692a4293](https://linux-hardware.org/?probe=04692a4293) | Jul 02, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [ac2a4b3aea](https://linux-hardware.org/?probe=ac2a4b3aea) | Jul 01, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [b8cc7c380d](https://linux-hardware.org/?probe=b8cc7c380d) | Jun 28, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2831e5a8cf](https://linux-hardware.org/?probe=2831e5a8cf) | Jun 28, 2021 |
| HP            | Pro Tablet 608 G1           | Notebook    | [c1a115b721](https://linux-hardware.org/?probe=c1a115b721) | Jun 28, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [d442a66371](https://linux-hardware.org/?probe=d442a66371) | Jun 27, 2021 |
| Razer         | Blade 15 Mid 2019-Base      | Notebook    | [69f9da2ac3](https://linux-hardware.org/?probe=69f9da2ac3) | Jun 26, 2021 |
| HUAWEI        | HN-WX9X                     | Notebook    | [c9180096a8](https://linux-hardware.org/?probe=c9180096a8) | Jun 26, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [84bf6743c1](https://linux-hardware.org/?probe=84bf6743c1) | Jun 25, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [ced7e0d00d](https://linux-hardware.org/?probe=ced7e0d00d) | Jun 25, 2021 |
| Lenovo        | ThinkPad T480 20L5000AMC    | Notebook    | [e1fe98a9de](https://linux-hardware.org/?probe=e1fe98a9de) | Jun 23, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [8ac09d11a4](https://linux-hardware.org/?probe=8ac09d11a4) | Jun 20, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [70c10f988f](https://linux-hardware.org/?probe=70c10f988f) | Jun 20, 2021 |
| MSI           | GS66 Stealth 10SFS          | Notebook    | [7535868db2](https://linux-hardware.org/?probe=7535868db2) | Jun 18, 2021 |
| MSI           | GS66 Stealth 10SFS          | Notebook    | [c095a4437c](https://linux-hardware.org/?probe=c095a4437c) | Jun 17, 2021 |
| ASUSTek       | PRIME TRX40-PRO             | Desktop     | [f0c7a3a628](https://linux-hardware.org/?probe=f0c7a3a628) | Jun 15, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [8d612e77f2](https://linux-hardware.org/?probe=8d612e77f2) | Jun 14, 2021 |
| ASUSTek       | P7P55D-E PRO                | Desktop     | [9a91c78c7a](https://linux-hardware.org/?probe=9a91c78c7a) | Jun 14, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | Notebook    | [8d5844241c](https://linux-hardware.org/?probe=8d5844241c) | Jun 13, 2021 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [3013608130](https://linux-hardware.org/?probe=3013608130) | Jun 12, 2021 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [704bf0bba3](https://linux-hardware.org/?probe=704bf0bba3) | Jun 12, 2021 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [9b07d82840](https://linux-hardware.org/?probe=9b07d82840) | Jun 12, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [efab65cf1d](https://linux-hardware.org/?probe=efab65cf1d) | Jun 12, 2021 |
| Dell          | XPS 17 9700                 | Notebook    | [293537d794](https://linux-hardware.org/?probe=293537d794) | Jun 11, 2021 |
| Lenovo        | ThinkPad X390 20Q0000KRT    | Notebook    | [f1d0d2bda6](https://linux-hardware.org/?probe=f1d0d2bda6) | Jun 09, 2021 |
| Lenovo        | G50-30 80G0                 | Notebook    | [ab9da369c0](https://linux-hardware.org/?probe=ab9da369c0) | Jun 09, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [407abb051f](https://linux-hardware.org/?probe=407abb051f) | Jun 09, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [5e6aba1341](https://linux-hardware.org/?probe=5e6aba1341) | Jun 09, 2021 |
| Dell          | Inspiron 7375               | Notebook    | [7704e5289b](https://linux-hardware.org/?probe=7704e5289b) | Jun 07, 2021 |
| Lenovo        | ThinkPad L450 20DTS01R00    | Notebook    | [f8e58be450](https://linux-hardware.org/?probe=f8e58be450) | Jun 03, 2021 |
| Lenovo        | ThinkPad X390 20Q0000KRT    | Notebook    | [b571e885e2](https://linux-hardware.org/?probe=b571e885e2) | Jun 03, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [f3f3c323ab](https://linux-hardware.org/?probe=f3f3c323ab) | Jun 03, 2021 |
| MSI           | Z97 PC Mate                 | Desktop     | [73ece6c322](https://linux-hardware.org/?probe=73ece6c322) | Jun 02, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [e85b21841c](https://linux-hardware.org/?probe=e85b21841c) | Jun 01, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [024ffa0922](https://linux-hardware.org/?probe=024ffa0922) | Jun 01, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [eed35a825a](https://linux-hardware.org/?probe=eed35a825a) | May 31, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [a04eb698f8](https://linux-hardware.org/?probe=a04eb698f8) | May 30, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [4f69bed2ff](https://linux-hardware.org/?probe=4f69bed2ff) | May 28, 2021 |
| Lenovo        | 3098 SDK0J40705 WIN 3425... | Desktop     | [2767965856](https://linux-hardware.org/?probe=2767965856) | May 27, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [052b95ba1d](https://linux-hardware.org/?probe=052b95ba1d) | May 27, 2021 |
| Dell          | Inspiron 5415               | Notebook    | [bbf1e95976](https://linux-hardware.org/?probe=bbf1e95976) | May 27, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [83d261308f](https://linux-hardware.org/?probe=83d261308f) | May 26, 2021 |
| Dell          | Inspiron 5415               | Notebook    | [abc4464787](https://linux-hardware.org/?probe=abc4464787) | May 26, 2021 |
| Dell          | Inspiron 5415               | Notebook    | [27c5c40e12](https://linux-hardware.org/?probe=27c5c40e12) | May 26, 2021 |
| Lenovo        | ThinkPad X230 2325BF1       | Notebook    | [0d334af224](https://linux-hardware.org/?probe=0d334af224) | May 26, 2021 |
| Lenovo        | 3098 SDK0J40705 WIN 3425... | Desktop     | [843f1d9b38](https://linux-hardware.org/?probe=843f1d9b38) | May 25, 2021 |
| Lenovo        | 3098 SDK0J40705 WIN 3425... | Desktop     | [5794d366c2](https://linux-hardware.org/?probe=5794d366c2) | May 25, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e1cf7f4599](https://linux-hardware.org/?probe=e1cf7f4599) | May 24, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [49458a2df1](https://linux-hardware.org/?probe=49458a2df1) | May 24, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [73ff247804](https://linux-hardware.org/?probe=73ff247804) | May 24, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [61a5d17b5b](https://linux-hardware.org/?probe=61a5d17b5b) | May 22, 2021 |
| MSI           | Z590-A PRO                  | Desktop     | [b74e96d4be](https://linux-hardware.org/?probe=b74e96d4be) | May 22, 2021 |
| Unknown       | Cubietech Cubieboard2       | Desktop     | [d777d4b535](https://linux-hardware.org/?probe=d777d4b535) | May 22, 2021 |
| Toshiba       | Satellite A200              | Notebook    | [455915e23a](https://linux-hardware.org/?probe=455915e23a) | May 21, 2021 |
| ASUSTek       | ROG STRIX Z490-I GAMING     | Desktop     | [95fb77ceae](https://linux-hardware.org/?probe=95fb77ceae) | May 21, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [1c2f94847e](https://linux-hardware.org/?probe=1c2f94847e) | May 20, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [5104abb7a7](https://linux-hardware.org/?probe=5104abb7a7) | May 20, 2021 |
| ASUSTek       | X550ZA                      | Notebook    | [aef8ea73d8](https://linux-hardware.org/?probe=aef8ea73d8) | May 20, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [72904aba23](https://linux-hardware.org/?probe=72904aba23) | May 20, 2021 |
| HP            | 8643 SMVB                   | Desktop     | [b183baddef](https://linux-hardware.org/?probe=b183baddef) | May 19, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [4f3165b957](https://linux-hardware.org/?probe=4f3165b957) | May 19, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [2679a5931a](https://linux-hardware.org/?probe=2679a5931a) | May 19, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [089c319771](https://linux-hardware.org/?probe=089c319771) | May 18, 2021 |
| Lenovo        | ThinkPad T61p 8891CTO       | Notebook    | [8a05529e0c](https://linux-hardware.org/?probe=8a05529e0c) | May 18, 2021 |
| Lenovo        | ThinkPad T61p 8891CTO       | Notebook    | [6daf66a738](https://linux-hardware.org/?probe=6daf66a738) | May 18, 2021 |
| Raspberry ... | Raspberry Pi Model B Rev... | Soc         | [7a83ffc7d8](https://linux-hardware.org/?probe=7a83ffc7d8) | May 18, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [7ae6a0f74b](https://linux-hardware.org/?probe=7ae6a0f74b) | May 18, 2021 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [2b97441fb1](https://linux-hardware.org/?probe=2b97441fb1) | May 17, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [8110fad44d](https://linux-hardware.org/?probe=8110fad44d) | May 17, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [9a767f85c2](https://linux-hardware.org/?probe=9a767f85c2) | May 17, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [50b75a0212](https://linux-hardware.org/?probe=50b75a0212) | May 17, 2021 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [d75aff5a0a](https://linux-hardware.org/?probe=d75aff5a0a) | May 16, 2021 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [f9420a7960](https://linux-hardware.org/?probe=f9420a7960) | May 16, 2021 |
| MSI           | Z590-A PRO                  | Desktop     | [b2cc4333b0](https://linux-hardware.org/?probe=b2cc4333b0) | May 16, 2021 |
| HP            | Unknown                     | Notebook    | [554d7cd528](https://linux-hardware.org/?probe=554d7cd528) | May 14, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [065d69be16](https://linux-hardware.org/?probe=065d69be16) | May 13, 2021 |
| Dell          | Inspiron 3135               | Notebook    | [2773a72a9b](https://linux-hardware.org/?probe=2773a72a9b) | May 10, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [6c504fbdf0](https://linux-hardware.org/?probe=6c504fbdf0) | May 10, 2021 |
| ASUSTek       | P5LD2-Deluxe                | Desktop     | [46242d579f](https://linux-hardware.org/?probe=46242d579f) | May 09, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | Notebook    | [5b8198d382](https://linux-hardware.org/?probe=5b8198d382) | May 08, 2021 |
| ASUSTek       | P5LD2-Deluxe                | Desktop     | [0b6b9eab78](https://linux-hardware.org/?probe=0b6b9eab78) | May 07, 2021 |
| Dell          | Inspiron 3135               | Notebook    | [9bcfced245](https://linux-hardware.org/?probe=9bcfced245) | May 07, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [c3e8ad6826](https://linux-hardware.org/?probe=c3e8ad6826) | May 07, 2021 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [0b4a5c33ef](https://linux-hardware.org/?probe=0b4a5c33ef) | May 06, 2021 |
| Dell          | G3 3500                     | Notebook    | [f6624959c4](https://linux-hardware.org/?probe=f6624959c4) | May 05, 2021 |
| ASUSTek       | P5LD2-Deluxe                | Desktop     | [70bb3aecd9](https://linux-hardware.org/?probe=70bb3aecd9) | May 05, 2021 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e305a7301f](https://linux-hardware.org/?probe=e305a7301f) | May 05, 2021 |
| ASUSTek       | P5LD2-Deluxe                | Desktop     | [193ecc62cf](https://linux-hardware.org/?probe=193ecc62cf) | May 03, 2021 |
| QDI           | P4I865A                     | Desktop     | [a3df896b35](https://linux-hardware.org/?probe=a3df896b35) | May 03, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1d95f1feca](https://linux-hardware.org/?probe=1d95f1feca) | May 02, 2021 |
| Toshiba       | NB100                       | Notebook    | [9540e0d0d5](https://linux-hardware.org/?probe=9540e0d0d5) | May 02, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [ae4420d3a9](https://linux-hardware.org/?probe=ae4420d3a9) | May 01, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [aa72a49a15](https://linux-hardware.org/?probe=aa72a49a15) | Apr 30, 2021 |
| Lenovo        | ThinkPad P50 20EN0006UK     | Notebook    | [6f9d0f45bb](https://linux-hardware.org/?probe=6f9d0f45bb) | Apr 30, 2021 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [aff27ae264](https://linux-hardware.org/?probe=aff27ae264) | Apr 29, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [fe32c3d470](https://linux-hardware.org/?probe=fe32c3d470) | Apr 29, 2021 |
| Dell          | XPS 17 9700                 | Notebook    | [02dae8d8ba](https://linux-hardware.org/?probe=02dae8d8ba) | Apr 24, 2021 |
| Unknown       | Freecom Silverstore HNCN... | Desktop     | [c54d9f2c0c](https://linux-hardware.org/?probe=c54d9f2c0c) | Apr 23, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [267f559e91](https://linux-hardware.org/?probe=267f559e91) | Apr 20, 2021 |
| Dell          | G3 3500                     | Notebook    | [d1a4723065](https://linux-hardware.org/?probe=d1a4723065) | Apr 20, 2021 |
| Dell          | G3 3500                     | Notebook    | [3295e38ea9](https://linux-hardware.org/?probe=3295e38ea9) | Apr 20, 2021 |
| Dell          | XPS 17 9700                 | Notebook    | [84387a75f7](https://linux-hardware.org/?probe=84387a75f7) | Apr 18, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b10d744c6c](https://linux-hardware.org/?probe=b10d744c6c) | Apr 18, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [0db8148a33](https://linux-hardware.org/?probe=0db8148a33) | Apr 17, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [5bc34889b8](https://linux-hardware.org/?probe=5bc34889b8) | Apr 17, 2021 |
| Lenovo        | ThinkPad P53 20QN001JUS     | Notebook    | [6d94f31cd6](https://linux-hardware.org/?probe=6d94f31cd6) | Apr 14, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [5159073240](https://linux-hardware.org/?probe=5159073240) | Apr 11, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [99daea7567](https://linux-hardware.org/?probe=99daea7567) | Apr 11, 2021 |
| Dell          | G3 3500                     | Notebook    | [3510f864f1](https://linux-hardware.org/?probe=3510f864f1) | Apr 10, 2021 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [de7b86720f](https://linux-hardware.org/?probe=de7b86720f) | Apr 10, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [7c883d58c6](https://linux-hardware.org/?probe=7c883d58c6) | Apr 10, 2021 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [07427b8218](https://linux-hardware.org/?probe=07427b8218) | Apr 09, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [ab8b789fc2](https://linux-hardware.org/?probe=ab8b789fc2) | Apr 06, 2021 |
| Dell          | Latitude X1                 | Notebook    | [a35f6c0969](https://linux-hardware.org/?probe=a35f6c0969) | Apr 05, 2021 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [39f6ad5463](https://linux-hardware.org/?probe=39f6ad5463) | Apr 04, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | Desktop     | [1f560968ab](https://linux-hardware.org/?probe=1f560968ab) | Apr 04, 2021 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [93033ed87e](https://linux-hardware.org/?probe=93033ed87e) | Apr 04, 2021 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [6b926d1195](https://linux-hardware.org/?probe=6b926d1195) | Apr 04, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [66d76dda01](https://linux-hardware.org/?probe=66d76dda01) | Apr 03, 2021 |
| Dell          | Latitude X1                 | Notebook    | [1e053513e0](https://linux-hardware.org/?probe=1e053513e0) | Apr 03, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [d51b8b7f04](https://linux-hardware.org/?probe=d51b8b7f04) | Apr 02, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [88b1b582b5](https://linux-hardware.org/?probe=88b1b582b5) | Apr 01, 2021 |
| MSI           | GE62 6QD                    | Notebook    | [d76949a11c](https://linux-hardware.org/?probe=d76949a11c) | Apr 01, 2021 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [95722413a6](https://linux-hardware.org/?probe=95722413a6) | Mar 29, 2021 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [65b87ee7d8](https://linux-hardware.org/?probe=65b87ee7d8) | Mar 29, 2021 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [58e2163a18](https://linux-hardware.org/?probe=58e2163a18) | Mar 29, 2021 |
| ASUSTek       | PRIME TRX40-PRO             | Desktop     | [f4da24790d](https://linux-hardware.org/?probe=f4da24790d) | Mar 27, 2021 |
| BESSTAR Te... | DMAF5 V1.0                  | Desktop     | [ea2ebcb877](https://linux-hardware.org/?probe=ea2ebcb877) | Mar 26, 2021 |
| ASUSTek       | N501VW                      | Notebook    | [46863f1f90](https://linux-hardware.org/?probe=46863f1f90) | Mar 24, 2021 |
| ASUSTek       | M4N78-VM                    | Desktop     | [b3d61c6fbd](https://linux-hardware.org/?probe=b3d61c6fbd) | Mar 24, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [0c715becee](https://linux-hardware.org/?probe=0c715becee) | Mar 23, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [fbd81069cc](https://linux-hardware.org/?probe=fbd81069cc) | Mar 23, 2021 |
| Gigabyte      | Z490 AORUS MASTER           | Desktop     | [b89f0d11bd](https://linux-hardware.org/?probe=b89f0d11bd) | Mar 23, 2021 |
| Gigabyte      | Z490 AORUS MASTER           | Desktop     | [c17cb184a4](https://linux-hardware.org/?probe=c17cb184a4) | Mar 22, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [26b5c18aba](https://linux-hardware.org/?probe=26b5c18aba) | Mar 22, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [63c58340d1](https://linux-hardware.org/?probe=63c58340d1) | Mar 20, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [41c48a20a2](https://linux-hardware.org/?probe=41c48a20a2) | Mar 19, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [c3f70afbd8](https://linux-hardware.org/?probe=c3f70afbd8) | Mar 18, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [b075ade19c](https://linux-hardware.org/?probe=b075ade19c) | Mar 18, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [8e8d411ccb](https://linux-hardware.org/?probe=8e8d411ccb) | Mar 17, 2021 |
| ASUSTek       | B85M-E                      | Desktop     | [46c2411987](https://linux-hardware.org/?probe=46c2411987) | Mar 17, 2021 |
| ASRock        | X370 Professional Gaming    | Desktop     | [677c76f624](https://linux-hardware.org/?probe=677c76f624) | Mar 17, 2021 |
| Dell          | XPS 13 9380                 | Notebook    | [a8f5a8232e](https://linux-hardware.org/?probe=a8f5a8232e) | Mar 17, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [fb88aba821](https://linux-hardware.org/?probe=fb88aba821) | Mar 17, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [65f8817baf](https://linux-hardware.org/?probe=65f8817baf) | Mar 17, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [3d16f2ffb4](https://linux-hardware.org/?probe=3d16f2ffb4) | Mar 16, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [b96252ab8f](https://linux-hardware.org/?probe=b96252ab8f) | Mar 15, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [aac20e8dce](https://linux-hardware.org/?probe=aac20e8dce) | Mar 15, 2021 |
| Lenovo        | ThinkPad T470s 20HFCTO1W... | Notebook    | [6c33ce2e79](https://linux-hardware.org/?probe=6c33ce2e79) | Mar 14, 2021 |
| HP            | Laptop 15-bs1xx             | Notebook    | [bd1886f540](https://linux-hardware.org/?probe=bd1886f540) | Mar 14, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [01681dba78](https://linux-hardware.org/?probe=01681dba78) | Mar 14, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [14d6107700](https://linux-hardware.org/?probe=14d6107700) | Mar 13, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [3043c4c8ed](https://linux-hardware.org/?probe=3043c4c8ed) | Mar 13, 2021 |
| HP            | ZBook Power G7 Mobile Wo... | Notebook    | [edbe4b927f](https://linux-hardware.org/?probe=edbe4b927f) | Mar 12, 2021 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [ed79695034](https://linux-hardware.org/?probe=ed79695034) | Mar 12, 2021 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [755b723bb0](https://linux-hardware.org/?probe=755b723bb0) | Mar 11, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [bf856bd378](https://linux-hardware.org/?probe=bf856bd378) | Mar 11, 2021 |
| ASUSTek       | Z10PR-D16 Series            | Server      | [4158cb76ef](https://linux-hardware.org/?probe=4158cb76ef) | Mar 09, 2021 |
| ASUSTek       | Z11PH-D12 Series            | Server      | [c934f8e023](https://linux-hardware.org/?probe=c934f8e023) | Mar 09, 2021 |
| Dell          | Latitude 5410               | Notebook    | [f7ff0d1881](https://linux-hardware.org/?probe=f7ff0d1881) | Mar 07, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [c19dde029b](https://linux-hardware.org/?probe=c19dde029b) | Mar 06, 2021 |
| ASRock        | B550M Steel Legend          | Desktop     | [0c34f3246f](https://linux-hardware.org/?probe=0c34f3246f) | Mar 06, 2021 |
| ASRock        | B550M Steel Legend          | Desktop     | [fb91319fa1](https://linux-hardware.org/?probe=fb91319fa1) | Mar 06, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [9f55c5ece0](https://linux-hardware.org/?probe=9f55c5ece0) | Mar 06, 2021 |
| Dell          | Latitude 5410               | Notebook    | [2f64a4536e](https://linux-hardware.org/?probe=2f64a4536e) | Mar 06, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [ebc962c6c8](https://linux-hardware.org/?probe=ebc962c6c8) | Mar 05, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [d7384efac7](https://linux-hardware.org/?probe=d7384efac7) | Mar 05, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [ff3a458300](https://linux-hardware.org/?probe=ff3a458300) | Mar 04, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [eb357781c5](https://linux-hardware.org/?probe=eb357781c5) | Mar 04, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [18e2e1ba5d](https://linux-hardware.org/?probe=18e2e1ba5d) | Mar 04, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [ff0e82cc06](https://linux-hardware.org/?probe=ff0e82cc06) | Mar 03, 2021 |
| ASRock        | B550M Steel Legend          | Desktop     | [4c28c6d22c](https://linux-hardware.org/?probe=4c28c6d22c) | Mar 03, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [6cd953f597](https://linux-hardware.org/?probe=6cd953f597) | Mar 02, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [41b4c51802](https://linux-hardware.org/?probe=41b4c51802) | Mar 02, 2021 |
| Lenovo        | Yoga Slim 7 14IIL05 82A1    | Notebook    | [f2ce82aade](https://linux-hardware.org/?probe=f2ce82aade) | Feb 27, 2021 |
| Lenovo        | Yoga Slim 7 14IIL05 82A1    | Notebook    | [83b0002691](https://linux-hardware.org/?probe=83b0002691) | Feb 27, 2021 |
| Lenovo        | ThinkPad P53 20QN001JUS     | Notebook    | [b8542f3302](https://linux-hardware.org/?probe=b8542f3302) | Feb 27, 2021 |
| Lenovo        | ThinkBook 14s-IWL 20RM      | Notebook    | [922d2a406f](https://linux-hardware.org/?probe=922d2a406f) | Feb 26, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [99ee0e5718](https://linux-hardware.org/?probe=99ee0e5718) | Feb 24, 2021 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [d7a5611d8a](https://linux-hardware.org/?probe=d7a5611d8a) | Feb 23, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [89497c0f27](https://linux-hardware.org/?probe=89497c0f27) | Feb 23, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [d854654bad](https://linux-hardware.org/?probe=d854654bad) | Feb 23, 2021 |
| MSI           | 970 GAMING                  | Desktop     | [062ccac9ff](https://linux-hardware.org/?probe=062ccac9ff) | Feb 22, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [ad91e37e92](https://linux-hardware.org/?probe=ad91e37e92) | Feb 22, 2021 |
| ASUSTek       | PRIME H470M-PLUS            | Desktop     | [0e4ce5d923](https://linux-hardware.org/?probe=0e4ce5d923) | Feb 22, 2021 |
| ASUSTek       | M3A78-CM                    | Desktop     | [ae309000e1](https://linux-hardware.org/?probe=ae309000e1) | Feb 22, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [e6ea03de75](https://linux-hardware.org/?probe=e6ea03de75) | Feb 21, 2021 |
| ASRock        | X370 Gaming X               | Desktop     | [97b686fad6](https://linux-hardware.org/?probe=97b686fad6) | Feb 21, 2021 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [f9639ea950](https://linux-hardware.org/?probe=f9639ea950) | Feb 20, 2021 |
| HP            | EliteBook 820 G3            | Notebook    | [e9e3b904a9](https://linux-hardware.org/?probe=e9e3b904a9) | Feb 19, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [ac8250480a](https://linux-hardware.org/?probe=ac8250480a) | Feb 16, 2021 |
| ASUSTek       | G2SV                        | Notebook    | [2dcd0e4e69](https://linux-hardware.org/?probe=2dcd0e4e69) | Feb 15, 2021 |
| ASUSTek       | G2SV                        | Notebook    | [5b8e446be1](https://linux-hardware.org/?probe=5b8e446be1) | Feb 15, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [8565fa7232](https://linux-hardware.org/?probe=8565fa7232) | Feb 15, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [c1b424bc28](https://linux-hardware.org/?probe=c1b424bc28) | Feb 15, 2021 |
| MSI           | B350M BAZOOKA               | Desktop     | [19cf6a4def](https://linux-hardware.org/?probe=19cf6a4def) | Feb 15, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [418d6ee98e](https://linux-hardware.org/?probe=418d6ee98e) | Feb 13, 2021 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [47dbd40dae](https://linux-hardware.org/?probe=47dbd40dae) | Feb 13, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [d2a976e336](https://linux-hardware.org/?probe=d2a976e336) | Feb 13, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [d20f245092](https://linux-hardware.org/?probe=d20f245092) | Feb 13, 2021 |
| Acer          | Nitro AN515-53              | Notebook    | [66e023417c](https://linux-hardware.org/?probe=66e023417c) | Feb 13, 2021 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | Notebook    | [c77ec688d3](https://linux-hardware.org/?probe=c77ec688d3) | Feb 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [d538017b75](https://linux-hardware.org/?probe=d538017b75) | Feb 04, 2021 |
| ASRock        | AM1H-ITX                    | Desktop     | [a1c5772342](https://linux-hardware.org/?probe=a1c5772342) | Feb 03, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [1df927bea6](https://linux-hardware.org/?probe=1df927bea6) | Feb 03, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [39c3dd1edd](https://linux-hardware.org/?probe=39c3dd1edd) | Feb 02, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [0d787440f2](https://linux-hardware.org/?probe=0d787440f2) | Feb 01, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [8e541c3c46](https://linux-hardware.org/?probe=8e541c3c46) | Feb 01, 2021 |
| ASUSTek       | PRIME B460-PLUS             | Desktop     | [ec933f8e8a](https://linux-hardware.org/?probe=ec933f8e8a) | Jan 31, 2021 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [37f6052109](https://linux-hardware.org/?probe=37f6052109) | Jan 30, 2021 |
| HP            | Unknown                     | Notebook    | [437cd35d62](https://linux-hardware.org/?probe=437cd35d62) | Jan 28, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [6d86921fcf](https://linux-hardware.org/?probe=6d86921fcf) | Jan 26, 2021 |
| Google        | Peppy                       | Notebook    | [0b7e4ccb8e](https://linux-hardware.org/?probe=0b7e4ccb8e) | Jan 26, 2021 |
| ASRock        | X370 Gaming X               | Desktop     | [8f0d93f4e1](https://linux-hardware.org/?probe=8f0d93f4e1) | Jan 25, 2021 |
| ASUSTek       | ROG Maximus XII HERO        | Desktop     | [1b3702adc5](https://linux-hardware.org/?probe=1b3702adc5) | Jan 25, 2021 |
| ASUSTek       | ROG Maximus XII HERO        | Desktop     | [8eb3edac54](https://linux-hardware.org/?probe=8eb3edac54) | Jan 24, 2021 |
| ASUSTek       | PRIME B460-PLUS             | Desktop     | [dc087e0399](https://linux-hardware.org/?probe=dc087e0399) | Jan 24, 2021 |
| ASUSTek       | PRIME B460-PLUS             | Desktop     | [de171f7a35](https://linux-hardware.org/?probe=de171f7a35) | Jan 24, 2021 |
| MSI           | Z170-A PRO                  | Desktop     | [6c8926dc8c](https://linux-hardware.org/?probe=6c8926dc8c) | Jan 23, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [23602ad020](https://linux-hardware.org/?probe=23602ad020) | Jan 20, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | Desktop     | [b5f6cc5993](https://linux-hardware.org/?probe=b5f6cc5993) | Jan 19, 2021 |
| HP            | Unknown                     | Notebook    | [db1b52d959](https://linux-hardware.org/?probe=db1b52d959) | Jan 19, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [8c1e988f7e](https://linux-hardware.org/?probe=8c1e988f7e) | Jan 18, 2021 |
| MSI           | MEG X570 GODLIKE            | Desktop     | [5964a40d34](https://linux-hardware.org/?probe=5964a40d34) | Jan 17, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | Desktop     | [25fb58cc9f](https://linux-hardware.org/?probe=25fb58cc9f) | Jan 16, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [88cf2bc0f5](https://linux-hardware.org/?probe=88cf2bc0f5) | Jan 15, 2021 |
| Lenovo        | Unknown                     | Notebook    | [38c41d5178](https://linux-hardware.org/?probe=38c41d5178) | Jan 13, 2021 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [e4ab17605e](https://linux-hardware.org/?probe=e4ab17605e) | Jan 13, 2021 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [202d822436](https://linux-hardware.org/?probe=202d822436) | Jan 12, 2021 |
| ASRock        | J3455-ITX                   | Desktop     | [89257face1](https://linux-hardware.org/?probe=89257face1) | Jan 12, 2021 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [c364bd9f45](https://linux-hardware.org/?probe=c364bd9f45) | Jan 11, 2021 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [38332ee350](https://linux-hardware.org/?probe=38332ee350) | Jan 11, 2021 |
| ASUSTek       | X555LJ                      | Notebook    | [1b20a57823](https://linux-hardware.org/?probe=1b20a57823) | Jan 10, 2021 |
| HP            | 158B                        | Desktop     | [6bc73950dd](https://linux-hardware.org/?probe=6bc73950dd) | Jan 10, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [1b9975eef6](https://linux-hardware.org/?probe=1b9975eef6) | Jan 08, 2021 |
| ASRock        | X570 Steel Legend           | Desktop     | [48d53df339](https://linux-hardware.org/?probe=48d53df339) | Jan 08, 2021 |
| Lenovo        | Legion Y530-15ICH-1060 8... | Notebook    | [77af1025e7](https://linux-hardware.org/?probe=77af1025e7) | Jan 08, 2021 |
| HP            | Pavilion dm1                | Notebook    | [db518ed539](https://linux-hardware.org/?probe=db518ed539) | Jan 08, 2021 |
| MSI           | 990FXA-GD80                 | Desktop     | [cc4b365068](https://linux-hardware.org/?probe=cc4b365068) | Jan 08, 2021 |
| ASRock        | B550M Steel Legend          | Desktop     | [a6b6bbef69](https://linux-hardware.org/?probe=a6b6bbef69) | Jan 07, 2021 |
| Lenovo        | Legion Y530-15ICH-1060 8... | Notebook    | [f3d55068a4](https://linux-hardware.org/?probe=f3d55068a4) | Jan 06, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [6d67af2066](https://linux-hardware.org/?probe=6d67af2066) | Jan 06, 2021 |
| Lenovo        | ThinkPad T480 20L5000WUS    | Notebook    | [d6cb8dec76](https://linux-hardware.org/?probe=d6cb8dec76) | Jan 05, 2021 |
| ASRock        | AB350M Pro4                 | Desktop     | [b75dcb6545](https://linux-hardware.org/?probe=b75dcb6545) | Jan 05, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [6f95de2b32](https://linux-hardware.org/?probe=6f95de2b32) | Jan 05, 2021 |
| HP            | ZBook 15 G4                 | Notebook    | [46ee3cd25c](https://linux-hardware.org/?probe=46ee3cd25c) | Jan 04, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [7c04f61d39](https://linux-hardware.org/?probe=7c04f61d39) | Jan 04, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [367d882a57](https://linux-hardware.org/?probe=367d882a57) | Jan 04, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [39cec3e63e](https://linux-hardware.org/?probe=39cec3e63e) | Jan 03, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [a011c9b38f](https://linux-hardware.org/?probe=a011c9b38f) | Jan 02, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [182deb31fb](https://linux-hardware.org/?probe=182deb31fb) | Jan 02, 2021 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | Notebook    | [4460990877](https://linux-hardware.org/?probe=4460990877) | Jan 02, 2021 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | Notebook    | [3f3cc6b9d6](https://linux-hardware.org/?probe=3f3cc6b9d6) | Jan 02, 2021 |
| Unknown       | Unknown                     | Notebook    | [1eb453e2b1](https://linux-hardware.org/?probe=1eb453e2b1) | Jan 02, 2021 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [b83ea4b5b3](https://linux-hardware.org/?probe=b83ea4b5b3) | Jan 02, 2021 |
| Unknown       | Unknown                     | Notebook    | [fee86bed02](https://linux-hardware.org/?probe=fee86bed02) | Dec 31, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [61ce6be19c](https://linux-hardware.org/?probe=61ce6be19c) | Dec 29, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [4301611dfb](https://linux-hardware.org/?probe=4301611dfb) | Dec 28, 2020 |
| ASRock        | AM1H-ITX                    | Desktop     | [2bd69bdc3e](https://linux-hardware.org/?probe=2bd69bdc3e) | Dec 27, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [8a19941ffe](https://linux-hardware.org/?probe=8a19941ffe) | Dec 26, 2020 |
| Intel         | S1200RP G62251-407          | Server      | [f3c8ac67b6](https://linux-hardware.org/?probe=f3c8ac67b6) | Dec 25, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [87e72db668](https://linux-hardware.org/?probe=87e72db668) | Dec 23, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [d00787942f](https://linux-hardware.org/?probe=d00787942f) | Dec 22, 2020 |
| ASRock        | B550M Steel Legend          | Desktop     | [a733d01196](https://linux-hardware.org/?probe=a733d01196) | Dec 22, 2020 |
| ASRock        | B550M Steel Legend          | Desktop     | [bd927d4e12](https://linux-hardware.org/?probe=bd927d4e12) | Dec 22, 2020 |
| ASRock        | B550M Steel Legend          | Desktop     | [a41b1e7e12](https://linux-hardware.org/?probe=a41b1e7e12) | Dec 22, 2020 |
| Lenovo        | ThinkPad X1 Yoga Gen 5 2... | Convertible | [3a31c6d289](https://linux-hardware.org/?probe=3a31c6d289) | Dec 20, 2020 |
| Dell          | 01CTXG A07                  | Server      | [1f6afdc077](https://linux-hardware.org/?probe=1f6afdc077) | Dec 20, 2020 |
| ASRock        | X570 Taichi                 | Desktop     | [29d14ce28a](https://linux-hardware.org/?probe=29d14ce28a) | Dec 19, 2020 |
| Acer          | Swift SF314-42              | Notebook    | [6e2749f503](https://linux-hardware.org/?probe=6e2749f503) | Dec 16, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [4312c9878e](https://linux-hardware.org/?probe=4312c9878e) | Dec 14, 2020 |
| Lenovo        | ThinkPad X201 3249CTO       | Notebook    | [a4e14d24c6](https://linux-hardware.org/?probe=a4e14d24c6) | Dec 13, 2020 |
| ASRock        | H170M Pro4S                 | Desktop     | [debbcde352](https://linux-hardware.org/?probe=debbcde352) | Dec 11, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [3396357637](https://linux-hardware.org/?probe=3396357637) | Dec 11, 2020 |
| HP            | ProBook 430 G5              | Notebook    | [c9a8c10a8f](https://linux-hardware.org/?probe=c9a8c10a8f) | Dec 10, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [3ea971b812](https://linux-hardware.org/?probe=3ea971b812) | Dec 10, 2020 |
| MSI           | GF63 Thin 9SC               | Notebook    | [5a23e8cfc4](https://linux-hardware.org/?probe=5a23e8cfc4) | Dec 06, 2020 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [e8e2d0cdfc](https://linux-hardware.org/?probe=e8e2d0cdfc) | Dec 05, 2020 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [3dc100c9a1](https://linux-hardware.org/?probe=3dc100c9a1) | Dec 03, 2020 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [50917002e1](https://linux-hardware.org/?probe=50917002e1) | Dec 01, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [193e7f8bf4](https://linux-hardware.org/?probe=193e7f8bf4) | Dec 01, 2020 |
| HP            | Unknown                     | Notebook    | [6ecc666f9f](https://linux-hardware.org/?probe=6ecc666f9f) | Dec 01, 2020 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [03753743e7](https://linux-hardware.org/?probe=03753743e7) | Nov 30, 2020 |
| Gigabyte      | EP45T-DS3                   | Desktop     | [45142a6931](https://linux-hardware.org/?probe=45142a6931) | Nov 30, 2020 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [7eeb446aee](https://linux-hardware.org/?probe=7eeb446aee) | Nov 30, 2020 |
| ASUSTek       | P9X79 WS                    | Desktop     | [24cfa19ea6](https://linux-hardware.org/?probe=24cfa19ea6) | Nov 30, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [3bd13280cc](https://linux-hardware.org/?probe=3bd13280cc) | Nov 28, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [b1e71861a5](https://linux-hardware.org/?probe=b1e71861a5) | Nov 27, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ba86d65e42](https://linux-hardware.org/?probe=ba86d65e42) | Nov 27, 2020 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [78d68d35d8](https://linux-hardware.org/?probe=78d68d35d8) | Nov 26, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [35233c6000](https://linux-hardware.org/?probe=35233c6000) | Nov 26, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [dcaf1f3521](https://linux-hardware.org/?probe=dcaf1f3521) | Nov 24, 2020 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [af91f8b0d0](https://linux-hardware.org/?probe=af91f8b0d0) | Nov 24, 2020 |
| MSI           | B350 GAMING PLUS            | Desktop     | [3e9e5d4c8d](https://linux-hardware.org/?probe=3e9e5d4c8d) | Nov 22, 2020 |
| ASUSTek       | PRIME TRX40-PRO             | Desktop     | [9b888a1a9c](https://linux-hardware.org/?probe=9b888a1a9c) | Nov 21, 2020 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [23418fe6cc](https://linux-hardware.org/?probe=23418fe6cc) | Nov 19, 2020 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [a6ab09a54b](https://linux-hardware.org/?probe=a6ab09a54b) | Nov 19, 2020 |
| ASRock        | X570 Pro4                   | Desktop     | [963200e763](https://linux-hardware.org/?probe=963200e763) | Nov 18, 2020 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [04abcfd451](https://linux-hardware.org/?probe=04abcfd451) | Nov 18, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [7ac134ec7a](https://linux-hardware.org/?probe=7ac134ec7a) | Nov 18, 2020 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [a4bdac2cea](https://linux-hardware.org/?probe=a4bdac2cea) | Nov 18, 2020 |
| HP            | OMEN by Laptop 17-cb0xxx    | Notebook    | [43f7b0ed5e](https://linux-hardware.org/?probe=43f7b0ed5e) | Nov 16, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [49a0bab061](https://linux-hardware.org/?probe=49a0bab061) | Nov 15, 2020 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [5d53e48607](https://linux-hardware.org/?probe=5d53e48607) | Nov 15, 2020 |
| ASRock        | B450 Pro4                   | Desktop     | [c920df4f73](https://linux-hardware.org/?probe=c920df4f73) | Nov 13, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a175dbabc2](https://linux-hardware.org/?probe=a175dbabc2) | Nov 12, 2020 |
| Dell          | Latitude 5490               | Notebook    | [894bd38b38](https://linux-hardware.org/?probe=894bd38b38) | Nov 11, 2020 |
| HP            | EliteBook 820 G4            | Notebook    | [13e0c5e646](https://linux-hardware.org/?probe=13e0c5e646) | Nov 10, 2020 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [3a052bbb91](https://linux-hardware.org/?probe=3a052bbb91) | Nov 09, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [53efc559ad](https://linux-hardware.org/?probe=53efc559ad) | Nov 08, 2020 |
| MSI           | B450-A PRO                  | Desktop     | [00aeeab6da](https://linux-hardware.org/?probe=00aeeab6da) | Nov 08, 2020 |
| Dell          | XPS 13 9360                 | Notebook    | [a6cf5e7036](https://linux-hardware.org/?probe=a6cf5e7036) | Nov 07, 2020 |
| MSI           | B450-A PRO                  | Desktop     | [cd67b65826](https://linux-hardware.org/?probe=cd67b65826) | Nov 06, 2020 |
| Dell          | Latitude 7410               | Notebook    | [af066ad306](https://linux-hardware.org/?probe=af066ad306) | Nov 04, 2020 |
| Dell          | G3 3500                     | Notebook    | [fb7c201de0](https://linux-hardware.org/?probe=fb7c201de0) | Nov 01, 2020 |
| Acer          | Aspire E5-771G              | Notebook    | [9d967e969d](https://linux-hardware.org/?probe=9d967e969d) | Nov 01, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | Notebook    | [ec44c959a4](https://linux-hardware.org/?probe=ec44c959a4) | Nov 01, 2020 |
| ASUSTek       | A88XM-A                     | Desktop     | [45cf973d9c](https://linux-hardware.org/?probe=45cf973d9c) | Oct 31, 2020 |
| MSI           | Z170-A PRO                  | Desktop     | [6f36f04e56](https://linux-hardware.org/?probe=6f36f04e56) | Oct 31, 2020 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [539bba5a4d](https://linux-hardware.org/?probe=539bba5a4d) | Oct 26, 2020 |
| Sony          | VPCSC41FM                   | Notebook    | [a7607a7b93](https://linux-hardware.org/?probe=a7607a7b93) | Oct 26, 2020 |
| HP            | Laptop 14-cf0xxx            | Notebook    | [5ae192d7e1](https://linux-hardware.org/?probe=5ae192d7e1) | Oct 26, 2020 |
| Lenovo        | ThinkPad X13 Gen 1 20UFC... | Notebook    | [ef90a9df54](https://linux-hardware.org/?probe=ef90a9df54) | Oct 25, 2020 |
| ASRock        | AM1H-ITX                    | Desktop     | [4a6634694e](https://linux-hardware.org/?probe=4a6634694e) | Oct 25, 2020 |
| ASRock        | X370 Gaming X               | Desktop     | [7b50c1e794](https://linux-hardware.org/?probe=7b50c1e794) | Oct 25, 2020 |
| Acer          | Aspire E5-571G              | Notebook    | [b52fb33c4d](https://linux-hardware.org/?probe=b52fb33c4d) | Oct 25, 2020 |
| HP            | Laptop 14-cf0xxx            | Notebook    | [8999670eb2](https://linux-hardware.org/?probe=8999670eb2) | Oct 25, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [447a3a003d](https://linux-hardware.org/?probe=447a3a003d) | Oct 25, 2020 |
| HP            | ProBook 430 G5              | Notebook    | [f8f15c63ad](https://linux-hardware.org/?probe=f8f15c63ad) | Oct 25, 2020 |
| HP            | ProBook 430 G5              | Notebook    | [b3df3d26f0](https://linux-hardware.org/?probe=b3df3d26f0) | Oct 24, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [f0cf2671f2](https://linux-hardware.org/?probe=f0cf2671f2) | Oct 24, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | Notebook    | [77849f8db0](https://linux-hardware.org/?probe=77849f8db0) | Oct 23, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | Notebook    | [77d6dd66e2](https://linux-hardware.org/?probe=77d6dd66e2) | Oct 23, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [b7a16467ac](https://linux-hardware.org/?probe=b7a16467ac) | Oct 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [30cef457c4](https://linux-hardware.org/?probe=30cef457c4) | Oct 19, 2020 |
| HP            | ProBook 455 G7              | Notebook    | [70aaf58443](https://linux-hardware.org/?probe=70aaf58443) | Oct 19, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [daa70ce737](https://linux-hardware.org/?probe=daa70ce737) | Oct 17, 2020 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [3a4156ad86](https://linux-hardware.org/?probe=3a4156ad86) | Oct 17, 2020 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [3264edefe8](https://linux-hardware.org/?probe=3264edefe8) | Oct 17, 2020 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [49f9ade50f](https://linux-hardware.org/?probe=49f9ade50f) | Oct 17, 2020 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [2fe8128b94](https://linux-hardware.org/?probe=2fe8128b94) | Oct 15, 2020 |
| HP            | EliteBook 820 G4            | Notebook    | [ea2fe3b4dc](https://linux-hardware.org/?probe=ea2fe3b4dc) | Oct 15, 2020 |
| HP            | 8643 SMVB                   | Desktop     | [b1ebd820ea](https://linux-hardware.org/?probe=b1ebd820ea) | Oct 14, 2020 |
| ASRock        | N3150-ITX                   | Desktop     | [50872ff699](https://linux-hardware.org/?probe=50872ff699) | Oct 14, 2020 |
| MSI           | Z370 PC PRO                 | Desktop     | [6fdfdd701e](https://linux-hardware.org/?probe=6fdfdd701e) | Oct 14, 2020 |
| Dell          | 0PC5F7 A02                  | Desktop     | [0b4436db73](https://linux-hardware.org/?probe=0b4436db73) | Oct 14, 2020 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [bb7e9817f3](https://linux-hardware.org/?probe=bb7e9817f3) | Oct 13, 2020 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [979e26a9ff](https://linux-hardware.org/?probe=979e26a9ff) | Oct 13, 2020 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [e13bfd8911](https://linux-hardware.org/?probe=e13bfd8911) | Oct 13, 2020 |
| ASRock        | X570M Pro4                  | Desktop     | [11624f2e68](https://linux-hardware.org/?probe=11624f2e68) | Oct 12, 2020 |
| ASRock        | X370 Professional Gaming    | Desktop     | [2b432df0be](https://linux-hardware.org/?probe=2b432df0be) | Oct 12, 2020 |
| Dell          | Latitude E7270              | Notebook    | [efcbc76194](https://linux-hardware.org/?probe=efcbc76194) | Oct 12, 2020 |
| Dell          | Latitude E7270              | Notebook    | [6199eaf93c](https://linux-hardware.org/?probe=6199eaf93c) | Oct 12, 2020 |
| Dell          | Latitude E7270              | Notebook    | [c04da65193](https://linux-hardware.org/?probe=c04da65193) | Oct 11, 2020 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [4c9fc71c64](https://linux-hardware.org/?probe=4c9fc71c64) | Oct 06, 2020 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [f3201a0e2c](https://linux-hardware.org/?probe=f3201a0e2c) | Oct 06, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [5cd90973fc](https://linux-hardware.org/?probe=5cd90973fc) | Oct 04, 2020 |
| ASUSTek       | H61M-K                      | Desktop     | [f813fe20d2](https://linux-hardware.org/?probe=f813fe20d2) | Oct 04, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [9c5d15be62](https://linux-hardware.org/?probe=9c5d15be62) | Oct 04, 2020 |
| ASUSTek       | X555LJ                      | Notebook    | [bd5306ec57](https://linux-hardware.org/?probe=bd5306ec57) | Oct 01, 2020 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [f09de8f7dc](https://linux-hardware.org/?probe=f09de8f7dc) | Oct 01, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [85a733886a](https://linux-hardware.org/?probe=85a733886a) | Sep 29, 2020 |
| Unknown       | Intel X79                   | Desktop     | [3849825892](https://linux-hardware.org/?probe=3849825892) | Sep 29, 2020 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [b048626385](https://linux-hardware.org/?probe=b048626385) | Sep 29, 2020 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [e26cc6bcb0](https://linux-hardware.org/?probe=e26cc6bcb0) | Sep 29, 2020 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [c8d28c60cd](https://linux-hardware.org/?probe=c8d28c60cd) | Sep 27, 2020 |
| ASRock        | Z170 OC Formula             | Desktop     | [b478607fef](https://linux-hardware.org/?probe=b478607fef) | Sep 26, 2020 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [0997ff40b0](https://linux-hardware.org/?probe=0997ff40b0) | Sep 26, 2020 |
| MSI           | B350 TOMAHAWK               | Desktop     | [00290a5d85](https://linux-hardware.org/?probe=00290a5d85) | Sep 26, 2020 |
| MSI           | B350 TOMAHAWK               | Desktop     | [449d8022e1](https://linux-hardware.org/?probe=449d8022e1) | Sep 26, 2020 |
| Dell          | G3 3500                     | Notebook    | [23b58bcd77](https://linux-hardware.org/?probe=23b58bcd77) | Sep 25, 2020 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [87f345b258](https://linux-hardware.org/?probe=87f345b258) | Sep 24, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [96d1d6229b](https://linux-hardware.org/?probe=96d1d6229b) | Sep 23, 2020 |
| Acer          | Aspire XC-710 V:1.1         | Desktop     | [644c742328](https://linux-hardware.org/?probe=644c742328) | Sep 23, 2020 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [aac147ef3c](https://linux-hardware.org/?probe=aac147ef3c) | Sep 22, 2020 |
| ASRock        | AB350M Pro4                 | Desktop     | [6cd6f20aef](https://linux-hardware.org/?probe=6cd6f20aef) | Sep 22, 2020 |
| HP            | Pavilion ZV6100 (EE984EA... | Notebook    | [951fafbea0](https://linux-hardware.org/?probe=951fafbea0) | Sep 19, 2020 |
| HP            | Pavilion ZV6100 (EE984EA... | Notebook    | [e638fa0818](https://linux-hardware.org/?probe=e638fa0818) | Sep 19, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [f2bdd44684](https://linux-hardware.org/?probe=f2bdd44684) | Sep 18, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [15e4e278e8](https://linux-hardware.org/?probe=15e4e278e8) | Sep 18, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [a1e9bd74fd](https://linux-hardware.org/?probe=a1e9bd74fd) | Sep 17, 2020 |
| Lenovo        | Unknown                     | Notebook    | [5107d64dc0](https://linux-hardware.org/?probe=5107d64dc0) | Sep 16, 2020 |
| ASRock        | 970A-G                      | Desktop     | [c76564a1e5](https://linux-hardware.org/?probe=c76564a1e5) | Sep 16, 2020 |
| HP            | ProBook 450 G5              | Notebook    | [9d3b97061b](https://linux-hardware.org/?probe=9d3b97061b) | Sep 15, 2020 |
| HP            | ProBook 450 G5              | Notebook    | [4d67605a9a](https://linux-hardware.org/?probe=4d67605a9a) | Sep 14, 2020 |
| Dell          | G3 3500                     | Notebook    | [73839e86fc](https://linux-hardware.org/?probe=73839e86fc) | Sep 14, 2020 |
| Lenovo        | FLEX-14IWL Laptop 81SQ      | Convertible | [998884be70](https://linux-hardware.org/?probe=998884be70) | Sep 14, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [9199843c31](https://linux-hardware.org/?probe=9199843c31) | Sep 11, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [5eae12f393](https://linux-hardware.org/?probe=5eae12f393) | Sep 11, 2020 |
| PC Special... | GK7NP5R                     | Notebook    | [2ba7289378](https://linux-hardware.org/?probe=2ba7289378) | Sep 11, 2020 |
| Dell          | Latitude 5501               | Notebook    | [bceeec9520](https://linux-hardware.org/?probe=bceeec9520) | Sep 10, 2020 |
| Dell          | Latitude 5501               | Notebook    | [0df822dc02](https://linux-hardware.org/?probe=0df822dc02) | Sep 09, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [a1cc53584d](https://linux-hardware.org/?probe=a1cc53584d) | Sep 05, 2020 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [92b57f7ab5](https://linux-hardware.org/?probe=92b57f7ab5) | Sep 05, 2020 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [cf465b6ceb](https://linux-hardware.org/?probe=cf465b6ceb) | Sep 05, 2020 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [34b84c17b7](https://linux-hardware.org/?probe=34b84c17b7) | Sep 04, 2020 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [4a62067798](https://linux-hardware.org/?probe=4a62067798) | Sep 03, 2020 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [ced4076cfe](https://linux-hardware.org/?probe=ced4076cfe) | Sep 03, 2020 |
| MSI           | B450M MORTAR MAX            | Desktop     | [aacb67377f](https://linux-hardware.org/?probe=aacb67377f) | Sep 03, 2020 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [3aacd1b61b](https://linux-hardware.org/?probe=3aacd1b61b) | Sep 03, 2020 |
| Apple         | MacBookPro12,1              | Notebook    | [0f915dee52](https://linux-hardware.org/?probe=0f915dee52) | Sep 03, 2020 |
| MSI           | Z97-G45 GAMING              | Desktop     | [e86bf6dfb8](https://linux-hardware.org/?probe=e86bf6dfb8) | Sep 03, 2020 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [4bf504d82b](https://linux-hardware.org/?probe=4bf504d82b) | Sep 03, 2020 |
| MSI           | X470 GAMING PLUS            | Desktop     | [84aef475d9](https://linux-hardware.org/?probe=84aef475d9) | Sep 02, 2020 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | Notebook    | [294fd98c3f](https://linux-hardware.org/?probe=294fd98c3f) | Sep 01, 2020 |
| Apple         | MacBookPro12,1              | Notebook    | [08ca1bc0c6](https://linux-hardware.org/?probe=08ca1bc0c6) | Aug 31, 2020 |
| MSI           | Z77IA-E53                   | Desktop     | [bf99082e95](https://linux-hardware.org/?probe=bf99082e95) | Aug 28, 2020 |
| ASUSTek       | Z170-A                      | Desktop     | [af1f86e610](https://linux-hardware.org/?probe=af1f86e610) | Aug 25, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [d17e5bf1f8](https://linux-hardware.org/?probe=d17e5bf1f8) | Aug 25, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [744c56e875](https://linux-hardware.org/?probe=744c56e875) | Aug 25, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a0960a7256](https://linux-hardware.org/?probe=a0960a7256) | Aug 25, 2020 |
| Wortmann      | TERRA_MOBILE_1590S          | Notebook    | [ade9df5306](https://linux-hardware.org/?probe=ade9df5306) | Aug 21, 2020 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [8f067e33b6](https://linux-hardware.org/?probe=8f067e33b6) | Aug 21, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [0230526040](https://linux-hardware.org/?probe=0230526040) | Aug 20, 2020 |
| Unknown       | Unknown                     | Desktop     | [41ab260322](https://linux-hardware.org/?probe=41ab260322) | Aug 20, 2020 |
| Lenovo        | ThinkPad T590 20N4001YPB    | Notebook    | [c6283736fd](https://linux-hardware.org/?probe=c6283736fd) | Aug 19, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [2afa749d39](https://linux-hardware.org/?probe=2afa749d39) | Aug 19, 2020 |
| Unknown       | Unknown                     | Desktop     | [6a7fc0088c](https://linux-hardware.org/?probe=6a7fc0088c) | Aug 19, 2020 |
| MSI           | B350 GAMING PRO CARBON      | Desktop     | [762b0fed7b](https://linux-hardware.org/?probe=762b0fed7b) | Aug 18, 2020 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | Notebook    | [fd339f3d69](https://linux-hardware.org/?probe=fd339f3d69) | Aug 17, 2020 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [19177595c8](https://linux-hardware.org/?probe=19177595c8) | Aug 16, 2020 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [c7793f1daa](https://linux-hardware.org/?probe=c7793f1daa) | Aug 15, 2020 |
| Unknown       | Unknown                     | Desktop     | [3d3ed1b8ce](https://linux-hardware.org/?probe=3d3ed1b8ce) | Aug 15, 2020 |
| Unknown       | Unknown                     | Desktop     | [55f1b3cdce](https://linux-hardware.org/?probe=55f1b3cdce) | Aug 15, 2020 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [7d01f814d5](https://linux-hardware.org/?probe=7d01f814d5) | Aug 10, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [cc14f627f3](https://linux-hardware.org/?probe=cc14f627f3) | Aug 07, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [7b17868903](https://linux-hardware.org/?probe=7b17868903) | Aug 07, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d76a630eb2](https://linux-hardware.org/?probe=d76a630eb2) | Aug 07, 2020 |
| Lenovo        | ThinkPad X270 20HN002UGE    | Notebook    | [c0b7a3c300](https://linux-hardware.org/?probe=c0b7a3c300) | Aug 07, 2020 |
| ASUSTek       | X406UAR                     | Notebook    | [97f52734c2](https://linux-hardware.org/?probe=97f52734c2) | Aug 06, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [d67ba67beb](https://linux-hardware.org/?probe=d67ba67beb) | Aug 05, 2020 |
| ASUSTek       | P6X58D-E                    | Desktop     | [3db01937e1](https://linux-hardware.org/?probe=3db01937e1) | Aug 05, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [b948b0ffe7](https://linux-hardware.org/?probe=b948b0ffe7) | Aug 03, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [0f826bb295](https://linux-hardware.org/?probe=0f826bb295) | Aug 03, 2020 |
| Sony          | VPCSC41FM                   | Notebook    | [3a1470664d](https://linux-hardware.org/?probe=3a1470664d) | Jul 24, 2020 |
| ASRock        | X370 Taichi                 | Desktop     | [e08f62cb80](https://linux-hardware.org/?probe=e08f62cb80) | Jul 23, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [a235d0f3c3](https://linux-hardware.org/?probe=a235d0f3c3) | Jul 21, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [68c95d0921](https://linux-hardware.org/?probe=68c95d0921) | Jul 17, 2020 |
| ASUSTek       | X99-M WS                    | Desktop     | [7a813c93b0](https://linux-hardware.org/?probe=7a813c93b0) | Jul 15, 2020 |
| Unknown       | Unknown                     | Desktop     | [d83097e656](https://linux-hardware.org/?probe=d83097e656) | Jul 13, 2020 |
| XMG           | C504                        | Notebook    | [a97e52282c](https://linux-hardware.org/?probe=a97e52282c) | Jul 13, 2020 |
| Dell          | 0DK9CR A02                  | Server      | [13e5ec2882](https://linux-hardware.org/?probe=13e5ec2882) | Jul 11, 2020 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [7e9e11b2bf](https://linux-hardware.org/?probe=7e9e11b2bf) | Jul 09, 2020 |
| System76      | Lemur Pro                   | Notebook    | [ef0445b033](https://linux-hardware.org/?probe=ef0445b033) | Jul 09, 2020 |
| ASUSTek       | GRYPHON Z97                 | Desktop     | [e7b3ad7e11](https://linux-hardware.org/?probe=e7b3ad7e11) | Jul 07, 2020 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [dd3e957888](https://linux-hardware.org/?probe=dd3e957888) | Jul 03, 2020 |
| Samsung       | R530/R730/P530              | Notebook    | [e1539a8d98](https://linux-hardware.org/?probe=e1539a8d98) | Jul 01, 2020 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [f54a86a6b4](https://linux-hardware.org/?probe=f54a86a6b4) | Jun 30, 2020 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [c9529f922d](https://linux-hardware.org/?probe=c9529f922d) | Jun 29, 2020 |
| ASRockRack    | C226M WS                    | Desktop     | [adb729fe45](https://linux-hardware.org/?probe=adb729fe45) | Jun 29, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [53834118cb](https://linux-hardware.org/?probe=53834118cb) | Jun 27, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [12ca04e727](https://linux-hardware.org/?probe=12ca04e727) | Jun 27, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [819f972d3a](https://linux-hardware.org/?probe=819f972d3a) | Jun 25, 2020 |
| ASUSTek       | PRIME X570-P                | Desktop     | [16394021f5](https://linux-hardware.org/?probe=16394021f5) | Jun 21, 2020 |
| ASRock        | X370 Killer SLI             | Desktop     | [e68e55ff91](https://linux-hardware.org/?probe=e68e55ff91) | Jun 20, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [723898cdec](https://linux-hardware.org/?probe=723898cdec) | Jun 20, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [26036b16aa](https://linux-hardware.org/?probe=26036b16aa) | Jun 17, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [db18eac4ef](https://linux-hardware.org/?probe=db18eac4ef) | Jun 16, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [a91b7a6ef3](https://linux-hardware.org/?probe=a91b7a6ef3) | Jun 16, 2020 |
| Dell          | Latitude 5480               | Notebook    | [d0d56fbb1d](https://linux-hardware.org/?probe=d0d56fbb1d) | Jun 14, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [78a788e5aa](https://linux-hardware.org/?probe=78a788e5aa) | Jun 14, 2020 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [d1c9757c3c](https://linux-hardware.org/?probe=d1c9757c3c) | Jun 11, 2020 |
| MSI           | X570-A PRO                  | Desktop     | [d330af6317](https://linux-hardware.org/?probe=d330af6317) | Jun 09, 2020 |
| ASUSTek       | Z170-A                      | Desktop     | [81dbec3df4](https://linux-hardware.org/?probe=81dbec3df4) | Jun 09, 2020 |
| Dell          | XPS 13 9360                 | Notebook    | [b4be1dd313](https://linux-hardware.org/?probe=b4be1dd313) | Jun 09, 2020 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [40b9dbe4a5](https://linux-hardware.org/?probe=40b9dbe4a5) | Jun 08, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [50cf5c19df](https://linux-hardware.org/?probe=50cf5c19df) | Jun 08, 2020 |
| ASRock        | X570 Extreme4               | Desktop     | [add6daf97a](https://linux-hardware.org/?probe=add6daf97a) | Jun 07, 2020 |
| Lenovo        | ThinkPad X230 232425J       | Notebook    | [2ebe6149b7](https://linux-hardware.org/?probe=2ebe6149b7) | Jun 06, 2020 |
| Intel         | S2600GZ G11481-354          | Server      | [9f6d925b73](https://linux-hardware.org/?probe=9f6d925b73) | Jun 06, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [ca7ca5b14e](https://linux-hardware.org/?probe=ca7ca5b14e) | Jun 06, 2020 |
| Lenovo        | ThinkPad P52 20M9001LMC     | Notebook    | [2902bb9460](https://linux-hardware.org/?probe=2902bb9460) | Jun 06, 2020 |
| Lenovo        | ThinkPad P52 20M9001LMC     | Notebook    | [065bddf59b](https://linux-hardware.org/?probe=065bddf59b) | Jun 06, 2020 |
| ASUSTek       | WS X299 SAGE                | Desktop     | [bfc9505d4b](https://linux-hardware.org/?probe=bfc9505d4b) | Jun 05, 2020 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [9c7b7cde1e](https://linux-hardware.org/?probe=9c7b7cde1e) | Jun 04, 2020 |
| ASRock        | Z390 Extreme4               | Desktop     | [e64653b77c](https://linux-hardware.org/?probe=e64653b77c) | Jun 04, 2020 |
| ASRock        | X399 Taichi                 | Desktop     | [ff470637f1](https://linux-hardware.org/?probe=ff470637f1) | Jun 04, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [38d7220c47](https://linux-hardware.org/?probe=38d7220c47) | Jun 04, 2020 |
| Dell          | XPS 13 9360                 | Notebook    | [e1d648a5f2](https://linux-hardware.org/?probe=e1d648a5f2) | Jun 04, 2020 |
| Lenovo        | ThinkPad L390 20NR001KRT    | Notebook    | [19809108e4](https://linux-hardware.org/?probe=19809108e4) | Jun 04, 2020 |
| ASRock        | Z390 Extreme4               | Desktop     | [b379b98120](https://linux-hardware.org/?probe=b379b98120) | Jun 04, 2020 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [cf5cf7d297](https://linux-hardware.org/?probe=cf5cf7d297) | Jun 04, 2020 |
| Dell          | Inspiron 5577               | Notebook    | [b29e45343d](https://linux-hardware.org/?probe=b29e45343d) | Jun 04, 2020 |
| ASUSTek       | P6X58D-E                    | Desktop     | [219e253757](https://linux-hardware.org/?probe=219e253757) | Jun 04, 2020 |
| MSI           | X470 GAMING PLUS            | Desktop     | [713a47cd93](https://linux-hardware.org/?probe=713a47cd93) | Jun 04, 2020 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [66b855cb1f](https://linux-hardware.org/?probe=66b855cb1f) | Jun 04, 2020 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [3eeead93cd](https://linux-hardware.org/?probe=3eeead93cd) | Jun 03, 2020 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | Desktop     | [19202ed9bc](https://linux-hardware.org/?probe=19202ed9bc) | Jun 03, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [781f2cda04](https://linux-hardware.org/?probe=781f2cda04) | Jun 03, 2020 |
| Intel         | S2600GZ G11481-354          | Server      | [d52f36d4e5](https://linux-hardware.org/?probe=d52f36d4e5) | Jun 03, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [d082b8d834](https://linux-hardware.org/?probe=d082b8d834) | Jun 03, 2020 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [03524be236](https://linux-hardware.org/?probe=03524be236) | Jun 03, 2020 |
| ASUSTek       | UX310UAR                    | Notebook    | [1b9a59e4ca](https://linux-hardware.org/?probe=1b9a59e4ca) | Jun 03, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [452ae63632](https://linux-hardware.org/?probe=452ae63632) | Jun 03, 2020 |
| Intel         | DH77KC AAG39641-400         | Desktop     | [c70d57d5e5](https://linux-hardware.org/?probe=c70d57d5e5) | Jun 03, 2020 |
| ASRock        | X399 Taichi                 | Desktop     | [9c9844febe](https://linux-hardware.org/?probe=9c9844febe) | Jun 03, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [656aaf0582](https://linux-hardware.org/?probe=656aaf0582) | Jun 03, 2020 |
| Apple         | MacBookPro12,1              | Notebook    | [3b583f9685](https://linux-hardware.org/?probe=3b583f9685) | Jun 03, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [e69d1396bf](https://linux-hardware.org/?probe=e69d1396bf) | Jun 03, 2020 |
| ASRock        | X570 Steel Legend           | Desktop     | [379b9c17e4](https://linux-hardware.org/?probe=379b9c17e4) | May 31, 2020 |
| Acer          | Aspire VN7-592G             | Notebook    | [aa51c338b2](https://linux-hardware.org/?probe=aa51c338b2) | May 26, 2020 |
| MSI           | GT63 Titan 8SG              | Notebook    | [85363c0652](https://linux-hardware.org/?probe=85363c0652) | May 25, 2020 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [e0cde3f93b](https://linux-hardware.org/?probe=e0cde3f93b) | May 25, 2020 |
| ASUSTek       | P6TD DELUXE                 | Desktop     | [2a97c35b6b](https://linux-hardware.org/?probe=2a97c35b6b) | May 23, 2020 |
| Sun Micros... | Ultra 24 50                 | Desktop     | [2541d35bd4](https://linux-hardware.org/?probe=2541d35bd4) | May 23, 2020 |
| Gigabyte      | H370M D3H-CF                | Desktop     | [1f405a7557](https://linux-hardware.org/?probe=1f405a7557) | May 23, 2020 |
| HP            | 3648h                       | Desktop     | [14b2a01c1d](https://linux-hardware.org/?probe=14b2a01c1d) | May 23, 2020 |
| ASRockRack    | X470D4U                     | Desktop     | [09640a1376](https://linux-hardware.org/?probe=09640a1376) | May 23, 2020 |
| HP            | 0B54h D                     | Desktop     | [4ef026497f](https://linux-hardware.org/?probe=4ef026497f) | May 23, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [72f3e05699](https://linux-hardware.org/?probe=72f3e05699) | May 22, 2020 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [0efeb1e15a](https://linux-hardware.org/?probe=0efeb1e15a) | May 14, 2020 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [7d37b8ad19](https://linux-hardware.org/?probe=7d37b8ad19) | May 12, 2020 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [9e904a50ca](https://linux-hardware.org/?probe=9e904a50ca) | May 12, 2020 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [4e05b9111b](https://linux-hardware.org/?probe=4e05b9111b) | May 12, 2020 |
| HP            | 83C1                        | Desktop     | [8b7d6722b2](https://linux-hardware.org/?probe=8b7d6722b2) | May 11, 2020 |
| ASRock        | X370 Gaming K4              | Desktop     | [42ec09f78b](https://linux-hardware.org/?probe=42ec09f78b) | May 11, 2020 |
| ASRock        | X370 Gaming K4              | Desktop     | [6874d82c83](https://linux-hardware.org/?probe=6874d82c83) | May 11, 2020 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [86a0177aac](https://linux-hardware.org/?probe=86a0177aac) | May 11, 2020 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [8bca8a21eb](https://linux-hardware.org/?probe=8bca8a21eb) | May 11, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [57203b3010](https://linux-hardware.org/?probe=57203b3010) | May 11, 2020 |
| ASRock        | X470 Taichi                 | Desktop     | [8ca172b725](https://linux-hardware.org/?probe=8ca172b725) | May 11, 2020 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [c30a3e0ddd](https://linux-hardware.org/?probe=c30a3e0ddd) | May 11, 2020 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [748a1ea384](https://linux-hardware.org/?probe=748a1ea384) | May 11, 2020 |
| ASUSTek       | E402NA                      | Notebook    | [bc0fa6176d](https://linux-hardware.org/?probe=bc0fa6176d) | May 11, 2020 |
| ASUSTek       | P8B75-V                     | Desktop     | [05258aea35](https://linux-hardware.org/?probe=05258aea35) | May 11, 2020 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [61bf6587d2](https://linux-hardware.org/?probe=61bf6587d2) | May 10, 2020 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [0a33d02a42](https://linux-hardware.org/?probe=0a33d02a42) | May 10, 2020 |
| Supermicro    | X10SAE                      | Server      | [2ff14127d7](https://linux-hardware.org/?probe=2ff14127d7) | Apr 30, 2020 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [9fce6c2df1](https://linux-hardware.org/?probe=9fce6c2df1) | Apr 25, 2020 |
| Dell          | Latitude 7390               | Notebook    | [59c245d756](https://linux-hardware.org/?probe=59c245d756) | Apr 20, 2020 |
| Dell          | Latitude 7390               | Notebook    | [c91eb58962](https://linux-hardware.org/?probe=c91eb58962) | Apr 20, 2020 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [8625c51506](https://linux-hardware.org/?probe=8625c51506) | Apr 19, 2020 |
| Dell          | Latitude E5470              | Notebook    | [568a079f29](https://linux-hardware.org/?probe=568a079f29) | Apr 17, 2020 |
| Dell          | Latitude E5470              | Notebook    | [c2b554cdcf](https://linux-hardware.org/?probe=c2b554cdcf) | Apr 15, 2020 |
| HP            | x360 310 G1 PC              | Notebook    | [9751d299ad](https://linux-hardware.org/?probe=9751d299ad) | Apr 15, 2020 |
| Dell          | Inspiron 7520               | Notebook    | [31c3181139](https://linux-hardware.org/?probe=31c3181139) | Apr 12, 2020 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [6dad99eced](https://linux-hardware.org/?probe=6dad99eced) | Apr 11, 2020 |
| Acer          | Aspire V3-331               | Notebook    | [3556b592c2](https://linux-hardware.org/?probe=3556b592c2) | Apr 09, 2020 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [baaff2d847](https://linux-hardware.org/?probe=baaff2d847) | Mar 30, 2020 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [8b2b986525](https://linux-hardware.org/?probe=8b2b986525) | Mar 29, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [22662aad4d](https://linux-hardware.org/?probe=22662aad4d) | Mar 26, 2020 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [4514d59538](https://linux-hardware.org/?probe=4514d59538) | Mar 19, 2020 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [26c5187786](https://linux-hardware.org/?probe=26c5187786) | Mar 19, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [c3d3d42413](https://linux-hardware.org/?probe=c3d3d42413) | Mar 05, 2020 |
| ASRock        | Z170 OC Formula             | Desktop     | [189475c3f5](https://linux-hardware.org/?probe=189475c3f5) | Mar 04, 2020 |
| ASRock        | Z170 OC Formula             | Desktop     | [a405f01061](https://linux-hardware.org/?probe=a405f01061) | Mar 04, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [fba41b433f](https://linux-hardware.org/?probe=fba41b433f) | Feb 27, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [b417c8e979](https://linux-hardware.org/?probe=b417c8e979) | Feb 24, 2020 |
| Acer          | Aspire V3-331               | Notebook    | [98986faf06](https://linux-hardware.org/?probe=98986faf06) | Feb 21, 2020 |
| Acer          | Aspire V3-331               | Notebook    | [400111ccfc](https://linux-hardware.org/?probe=400111ccfc) | Feb 21, 2020 |
| MSI           | GT73EVR 7RF                 | Notebook    | [99e70d86e2](https://linux-hardware.org/?probe=99e70d86e2) | Feb 18, 2020 |
| Acer          | Aspire V3-331               | Notebook    | [68e659c87d](https://linux-hardware.org/?probe=68e659c87d) | Feb 16, 2020 |
| Gigabyte      | GA-990FXA-UD5               | Desktop     | [24bf705591](https://linux-hardware.org/?probe=24bf705591) | Feb 14, 2020 |
| LG Electro... | 17Z990-R.AAS8U1             | Notebook    | [5fe84895f2](https://linux-hardware.org/?probe=5fe84895f2) | Feb 10, 2020 |
| LG Electro... | 17Z990-R.AAS8U1             | Notebook    | [bf08aa9738](https://linux-hardware.org/?probe=bf08aa9738) | Feb 10, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [169fe41d8b](https://linux-hardware.org/?probe=169fe41d8b) | Jan 20, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Gentoo_2.7/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.27-gentoo           | 25        | 3.63%   |
| 5.10.61-gentoo           | 23        | 3.34%   |
| 5.10.27-gentoo-x86_64    | 13        | 1.89%   |
| 5.10.76-gentoo-r1        | 12        | 1.74%   |
| 5.10.61-gentoo-x86_64    | 12        | 1.74%   |
| 5.10.52-gentoo           | 12        | 1.74%   |
| 5.7.0-gentoo             | 10        | 1.45%   |
| 5.15.32-gentoo-r1        | 9         | 1.31%   |
| 5.10.76-gentoo-r1-x86_64 | 9         | 1.31%   |
| 5.6.15-gentoo            | 8         | 1.16%   |
| 5.8.0-gentoo-r1          | 6         | 0.87%   |
| 5.4.97-gentoo            | 6         | 0.87%   |
| 5.4.80-gentoo-r1         | 6         | 0.87%   |
| 5.9.8-gentoo             | 5         | 0.73%   |
| 5.6.11-gentoo            | 5         | 0.73%   |
| 5.11.6-gentoo            | 5         | 0.73%   |
| 5.10.52-gentoo-x86_64    | 5         | 0.73%   |
| 5.10.4-gentoo            | 5         | 0.73%   |
| 5.9.11-gentoo            | 4         | 0.58%   |
| 5.9.1-gentoo             | 4         | 0.58%   |
| 5.4.60-gentoo            | 4         | 0.58%   |
| 5.11.2-gentoo            | 4         | 0.58%   |
| 5.11.0-gentoo            | 4         | 0.58%   |
| 5.10.2-gentoo            | 4         | 0.58%   |
| 5.9.9-gentoo             | 3         | 0.44%   |
| 5.9.13-gentoo            | 3         | 0.44%   |
| 5.9.11                   | 3         | 0.44%   |
| 5.8.5-gentoo             | 3         | 0.44%   |
| 5.8.16-gentoo            | 3         | 0.44%   |
| 5.7.9-gentoo             | 3         | 0.44%   |
| 5.7.4-gentoo             | 3         | 0.44%   |
| 5.6.15-gentoo-x86_64     | 3         | 0.44%   |
| 5.6.15                   | 3         | 0.44%   |
| 5.15.26-gentoo           | 3         | 0.44%   |
| 5.13.5-gentoo            | 3         | 0.44%   |
| 5.13.13-gentoo           | 3         | 0.44%   |
| 5.12.13-gentoo           | 3         | 0.44%   |
| 5.10.7-gentoo            | 3         | 0.44%   |
| 5.10.4-gentoo-x86_64     | 3         | 0.44%   |
| 5.10.35-gentoo           | 3         | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.27 | 46        | 6.69%   |
| 5.10.61 | 38        | 5.52%   |
| 5.10.76 | 30        | 4.36%   |
| 5.10.52 | 23        | 3.34%   |
| 5.6.15  | 16        | 2.33%   |
| 5.15.32 | 14        | 2.03%   |
| 5.7.0   | 13        | 1.89%   |
| 5.9.11  | 12        | 1.74%   |
| 5.9.8   | 10        | 1.45%   |
| 5.8.0   | 10        | 1.45%   |
| 5.4.97  | 10        | 1.45%   |
| 5.9.0   | 8         | 1.16%   |
| 5.6.11  | 8         | 1.16%   |
| 5.11.6  | 8         | 1.16%   |
| 5.11.0  | 8         | 1.16%   |
| 5.10.4  | 8         | 1.16%   |
| 5.9.1   | 7         | 1.02%   |
| 5.4.80  | 7         | 1.02%   |
| 5.13.12 | 7         | 1.02%   |
| 5.11.2  | 7         | 1.02%   |
| 5.10.11 | 7         | 1.02%   |
| 5.9.13  | 6         | 0.87%   |
| 5.8.10  | 6         | 0.87%   |
| 5.6.0   | 6         | 0.87%   |
| 5.8.9   | 5         | 0.73%   |
| 5.8.5   | 5         | 0.73%   |
| 5.7.9   | 5         | 0.73%   |
| 5.6.14  | 5         | 0.73%   |
| 5.6.13  | 5         | 0.73%   |
| 5.4.60  | 5         | 0.73%   |
| 5.17.1  | 5         | 0.73%   |
| 5.12.4  | 5         | 0.73%   |
| 5.10.6  | 5         | 0.73%   |
| 5.10.5  | 5         | 0.73%   |
| 5.10.33 | 5         | 0.73%   |
| 5.10.2  | 5         | 0.73%   |
| 5.8.16  | 4         | 0.58%   |
| 5.7.6   | 4         | 0.58%   |
| 5.6.8   | 4         | 0.58%   |
| 5.15.26 | 4         | 0.58%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 215       | 32.82%  |
| 5.9     | 58        | 8.85%   |
| 5.6     | 56        | 8.55%   |
| 5.8     | 52        | 7.94%   |
| 5.7     | 40        | 6.11%   |
| 5.11    | 40        | 6.11%   |
| 5.4     | 37        | 5.65%   |
| 5.13    | 34        | 5.19%   |
| 5.15    | 32        | 4.89%   |
| 5.14    | 32        | 4.89%   |
| 5.12    | 28        | 4.27%   |
| 5.5     | 13        | 1.98%   |
| 5.17    | 10        | 1.53%   |
| 4.19    | 4         | 0.61%   |
| 5.16    | 3         | 0.46%   |
| 4.9     | 1         | 0.15%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| x86_64   | 532       | 95.86%  |
| i686     | 12        | 2.16%   |
| aarch64  | 6         | 1.08%   |
| armv7l   | 2         | 0.36%   |
| ppc64le  | 1         | 0.18%   |
| armv6l   | 1         | 0.18%   |
| armv5tel | 1         | 0.18%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 224       | 37.84%  |
| KDE5           | 107       | 18.07%  |
| GNOME          | 101       | 17.06%  |
| XFCE           | 52        | 8.78%   |
| KDE            | 36        | 6.08%   |
| MATE           | 22        | 3.72%   |
| Sway           | 7         | 1.18%   |
| DWM            | 7         | 1.18%   |
| LXQt           | 6         | 1.01%   |
| XSession       | 5         | 0.84%   |
| X-Cinnamon     | 5         | 0.84%   |
| LXDE           | 5         | 0.84%   |
| Enlightenment  | 4         | 0.68%   |
| openbox        | 3         | 0.51%   |
| awesome        | 2         | 0.34%   |
| i3-with-shmlog | 1         | 0.17%   |
| i3             | 1         | 0.17%   |
| GNOME Classic  | 1         | 0.17%   |
| fluxbox        | 1         | 0.17%   |
| Cinnamon       | 1         | 0.17%   |
| bspwm          | 1         | 0.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 327       | 55.71%  |
| Unknown | 112       | 19.08%  |
| Tty     | 99        | 16.87%  |
| Wayland | 49        | 8.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 264       | 45.52%  |
| SDDM    | 133       | 22.93%  |
| LightDM | 82        | 14.14%  |
| GDM     | 66        | 11.38%  |
| SLiM    | 12        | 2.07%   |
| XDM     | 10        | 1.72%   |
| LXDM    | 8         | 1.38%   |
| TDM     | 3         | 0.52%   |
| GREETD  | 1         | 0.17%   |
| GDM3    | 1         | 0.17%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 231       | 40.38%  |
| en_GB      | 41        | 7.17%   |
| Unknown    | 40        | 6.99%   |
| de_DE      | 37        | 6.47%   |
| ru_RU      | 30        | 5.24%   |
| C.UTF8     | 30        | 5.24%   |
| es_ES      | 16        | 2.8%    |
| C          | 16        | 2.8%    |
| fr_FR      | 14        | 2.45%   |
| en_CA      | 13        | 2.27%   |
| pl_PL      | 9         | 1.57%   |
| pt_BR      | 7         | 1.22%   |
| it_IT      | 7         | 1.22%   |
| sv_SE      | 6         | 1.05%   |
| ru_RU.UTF8 | 5         | 0.87%   |
| nl_NL      | 5         | 0.87%   |
| en_AU      | 5         | 0.87%   |
| el_GR      | 5         | 0.87%   |
| zh_CN      | 4         | 0.7%    |
| POSIX      | 3         | 0.52%   |
| ja_JP      | 3         | 0.52%   |
| fi_FI      | 3         | 0.52%   |
| en_US.UTF8 | 3         | 0.52%   |
| en_IE      | 3         | 0.52%   |
| ca_ES      | 3         | 0.52%   |
| uk_UA      | 2         | 0.35%   |
| ru_UA      | 2         | 0.35%   |
| nl_BE      | 2         | 0.35%   |
| es_CL      | 2         | 0.35%   |
| de_DE.UTF8 | 2         | 0.35%   |
| de_CH      | 2         | 0.35%   |
| zh_TW      | 1         | 0.17%   |
| pt_PT      | 1         | 0.17%   |
| lt_LT      | 1         | 0.17%   |
| ko_KR      | 1         | 0.17%   |
| hu_HU      | 1         | 0.17%   |
| fr_FR.UTF8 | 1         | 0.17%   |
| fr_CA      | 1         | 0.17%   |
| fr_BE      | 1         | 0.17%   |
| et_EE      | 1         | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 399       | 70.87%  |
| BIOS | 164       | 29.13%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 339       | 59.89%  |
| Btrfs    | 126       | 22.26%  |
| Xfs      | 32        | 5.65%   |
| Zfs      | 25        | 4.42%   |
| F2fs     | 24        | 4.24%   |
| Reiserfs | 9         | 1.59%   |
| Unknown  | 4         | 0.71%   |
| XXX      | 2         | 0.35%   |
| Jfs      | 2         | 0.35%   |
| Ext3     | 2         | 0.35%   |
| Overlay  | 1         | 0.18%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 459       | 81.53%  |
| MBR     | 71        | 12.61%  |
| Unknown | 33        | 5.86%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 380       | 66.2%   |
| Yes       | 194       | 33.8%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 372       | 65.26%  |
| Yes       | 198       | 34.74%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 128       | 23.06%  |
| Lenovo                  | 86        | 15.5%   |
| Dell                    | 53        | 9.55%   |
| MSI                     | 51        | 9.19%   |
| Hewlett-Packard         | 51        | 9.19%   |
| ASRock                  | 40        | 7.21%   |
| Gigabyte Technology     | 39        | 7.03%   |
| Acer                    | 13        | 2.34%   |
| Intel                   | 11        | 1.98%   |
| Raspberry Pi Foundation | 8         | 1.44%   |
| Apple                   | 7         | 1.26%   |
| Unknown                 | 7         | 1.26%   |
| Fujitsu                 | 5         | 0.9%    |
| TUXEDO                  | 4         | 0.72%   |
| Toshiba                 | 4         | 0.72%   |
| Timi                    | 4         | 0.72%   |
| Supermicro              | 4         | 0.72%   |
| Samsung Electronics     | 4         | 0.72%   |
| HUAWEI                  | 4         | 0.72%   |
| Tekram Technology       | 3         | 0.54%   |
| Razer                   | 3         | 0.54%   |
| ASRockRack              | 3         | 0.54%   |
| IBM                     | 2         | 0.36%   |
| XMG                     | 1         | 0.18%   |
| Wortmann AG             | 1         | 0.18%   |
| TYAN Computer           | 1         | 0.18%   |
| System76                | 1         | 0.18%   |
| Sun Microsystems        | 1         | 0.18%   |
| Sony                    | 1         | 0.18%   |
| SIEMENS                 | 1         | 0.18%   |
| QDI                     | 1         | 0.18%   |
| Purism                  | 1         | 0.18%   |
| PC Specialist           | 1         | 0.18%   |
| Packard Bell            | 1         | 0.18%   |
| NZXT                    | 1         | 0.18%   |
| Notebook                | 1         | 0.18%   |
| MOTILE                  | 1         | 0.18%   |
| LG Electronics          | 1         | 0.18%   |
| Jumper                  | 1         | 0.18%   |
| Google                  | 1         | 0.18%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 13        | 2.34%   |
| ASUS PRIME X470-PRO                  | 7         | 1.26%   |
| ASUS All Series                      | 6         | 1.08%   |
| MSI MS-7A38                          | 4         | 0.72%   |
| ASUS ROG STRIX B550-F GAMING         | 4         | 0.72%   |
| ASRock B550M Steel Legend            | 4         | 0.72%   |
| Tekram P6B40-A4X-i440BX Rev          | 3         | 0.54%   |
| MSI MS-7C35                          | 3         | 0.54%   |
| MSI MS-7C02                          | 3         | 0.54%   |
| MSI MS-7B79                          | 3         | 0.54%   |
| Lenovo Legion Y530-15ICH 81FV        | 3         | 0.54%   |
| HP Pavilion Notebook                 | 3         | 0.54%   |
| HP Pavilion Gaming Laptop 15-ec1xxx  | 3         | 0.54%   |
| Dell XPS 15 7590                     | 3         | 0.54%   |
| Dell XPS 13 9360                     | 3         | 0.54%   |
| Dell XPS 13 9310                     | 3         | 0.54%   |
| ASUS Z170 PRO GAMING                 | 3         | 0.54%   |
| ASUS TUF Gaming X570-PLUS            | 3         | 0.54%   |
| ASUS ROG CROSSHAIR VIII HERO         | 3         | 0.54%   |
| ASUS PRIME X570-PRO                  | 3         | 0.54%   |
| ASUS PRIME X370-PRO                  | 3         | 0.54%   |
| ASRock B450M-HDV R4.0                | 3         | 0.54%   |
| Timi RedmiBook 13 R                  | 2         | 0.36%   |
| Supermicro X10SAE                    | 2         | 0.36%   |
| MSI MS-7C84                          | 2         | 0.36%   |
| MSI MS-7C37                          | 2         | 0.36%   |
| MSI MS-7C34                          | 2         | 0.36%   |
| MSI MS-7A34                          | 2         | 0.36%   |
| Lenovo ThinkPad T14 Gen 1 20UD0013GE | 2         | 0.36%   |
| Lenovo Legion R7000 2020 82B6        | 2         | 0.36%   |
| HP ProBook 455 G7                    | 2         | 0.36%   |
| HP EliteBook 855 G7 Notebook PC      | 2         | 0.36%   |
| Gigabyte X570 AORUS XTREME           | 2         | 0.36%   |
| Gigabyte X570 AORUS ELITE            | 2         | 0.36%   |
| Gigabyte AB350-Gaming 3              | 2         | 0.36%   |
| Fujitsu ESPRIMO P7935                | 2         | 0.36%   |
| Fujitsu D3401-H1                     | 2         | 0.36%   |
| Dell XPS 15 9570                     | 2         | 0.36%   |
| Dell Precision 7560                  | 2         | 0.36%   |
| Dell Inspiron 5577                   | 2         | 0.36%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 43        | 7.75%   |
| ASUS ROG                | 27        | 4.86%   |
| ASUS PRIME              | 26        | 4.68%   |
| Dell XPS                | 18        | 3.24%   |
| Lenovo Legion           | 14        | 2.52%   |
| Dell Latitude           | 14        | 2.52%   |
| Unknown                 | 13        | 2.34%   |
| Lenovo IdeaPad          | 12        | 2.16%   |
| HP Pavilion             | 11        | 1.98%   |
| ASUS TUF                | 11        | 1.98%   |
| Acer Aspire             | 9         | 1.62%   |
| RPi Raspberry           | 8         | 1.44%   |
| Dell Inspiron           | 8         | 1.44%   |
| Lenovo Yoga             | 7         | 1.26%   |
| HP EliteBook            | 6         | 1.08%   |
| Gigabyte X570           | 6         | 1.08%   |
| ASUS All                | 6         | 1.08%   |
| ASRock X570             | 6         | 1.08%   |
| HP ProBook              | 5         | 0.9%    |
| HP OMEN                 | 5         | 0.9%    |
| HP Laptop               | 5         | 0.9%    |
| ASRock X370             | 5         | 0.9%    |
| MSI MS-7A38             | 4         | 0.72%   |
| HP ENVY                 | 4         | 0.72%   |
| Dell Precision          | 4         | 0.72%   |
| ASUS ZenBook            | 4         | 0.72%   |
| ASRock B550M            | 4         | 0.72%   |
| Toshiba Satellite       | 3         | 0.54%   |
| Tekram P6B40-A4X-i440BX | 3         | 0.54%   |
| Razer Blade             | 3         | 0.54%   |
| MSI MS-7C35             | 3         | 0.54%   |
| MSI MS-7C02             | 3         | 0.54%   |
| MSI MS-7B79             | 3         | 0.54%   |
| HP ZBook                | 3         | 0.54%   |
| Gigabyte B450           | 3         | 0.54%   |
| Gigabyte AB350-Gaming   | 3         | 0.54%   |
| Dell OptiPlex           | 3         | 0.54%   |
| ASUS Z170               | 3         | 0.54%   |
| ASRock B450M-HDV        | 3         | 0.54%   |
| TUXEDO Book             | 2         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 112       | 20.18%  |
| 2019    | 99        | 17.84%  |
| 2018    | 75        | 13.51%  |
| 2017    | 44        | 7.93%   |
| 2021    | 32        | 5.77%   |
| 2015    | 28        | 5.05%   |
| 2016    | 26        | 4.68%   |
| 2014    | 22        | 3.96%   |
| 2012    | 22        | 3.96%   |
| 2013    | 18        | 3.24%   |
| 2010    | 17        | 3.06%   |
| 2008    | 13        | 2.34%   |
| 2011    | 12        | 2.16%   |
| 2009    | 10        | 1.8%    |
| Unknown | 9         | 1.62%   |
| 2007    | 4         | 0.72%   |
| 2005    | 3         | 0.54%   |
| 2000    | 3         | 0.54%   |
| 2006    | 2         | 0.36%   |
| 2004    | 2         | 0.36%   |
| 2022    | 1         | 0.18%   |
| 2003    | 1         | 0.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 271       | 48.83%  |
| Notebook       | 243       | 43.78%  |
| Convertible    | 13        | 2.34%   |
| Server         | 13        | 2.34%   |
| System on chip | 8         | 1.44%   |
| Mini pc        | 5         | 0.9%    |
| Stick pc       | 1         | 0.18%   |
| All in one     | 1         | 0.18%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 545       | 98.2%   |
| Enabled  | 10        | 1.8%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 551       | 99.28%  |
| Yes  | 4         | 0.72%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 32.01-64.0      | 147       | 26.02%  |
| 16.01-24.0      | 135       | 23.89%  |
| 8.01-16.0       | 78        | 13.81%  |
| 4.01-8.0        | 70        | 12.39%  |
| 64.01-256.0     | 63        | 11.15%  |
| 3.01-4.0        | 32        | 5.66%   |
| 24.01-32.0      | 19        | 3.36%   |
| 1.01-2.0        | 8         | 1.42%   |
| 2.01-3.0        | 5         | 0.88%   |
| 0.51-1.0        | 5         | 0.88%   |
| 0.01-0.5        | 2         | 0.35%   |
| More than 256.0 | 1         | 0.18%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 134       | 20.74%  |
| 1.01-2.0    | 133       | 20.59%  |
| 2.01-3.0    | 106       | 16.41%  |
| 3.01-4.0    | 77        | 11.92%  |
| 8.01-16.0   | 68        | 10.53%  |
| 0.01-0.5    | 53        | 8.2%    |
| 0.51-1.0    | 46        | 7.12%   |
| 16.01-24.0  | 18        | 2.79%   |
| 32.01-64.0  | 6         | 0.93%   |
| 24.01-32.0  | 4         | 0.62%   |
| 64.01-256.0 | 1         | 0.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 238       | 40.75%  |
| 2      | 154       | 26.37%  |
| 3      | 74        | 12.67%  |
| 4      | 48        | 8.22%   |
| 5      | 34        | 5.82%   |
| 6      | 11        | 1.88%   |
| 7      | 9         | 1.54%   |
| 0      | 6         | 1.03%   |
| 8      | 3         | 0.51%   |
| 13     | 2         | 0.34%   |
| 9      | 2         | 0.34%   |
| 18     | 1         | 0.17%   |
| 17     | 1         | 0.17%   |
| 11     | 1         | 0.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 442       | 78.37%  |
| Yes       | 122       | 21.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 481       | 86.05%  |
| No        | 78        | 13.95%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 366       | 65.36%  |
| No        | 194       | 34.64%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 346       | 61.79%  |
| No        | 214       | 38.21%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 97        | 17.35%  |
| Germany     | 81        | 14.49%  |
| Russia      | 52        | 9.3%    |
| UK          | 30        | 5.37%   |
| Spain       | 24        | 4.29%   |
| France      | 24        | 4.29%   |
| Poland      | 21        | 3.76%   |
| Canada      | 21        | 3.76%   |
| China       | 16        | 2.86%   |
| Netherlands | 15        | 2.68%   |
| Finland     | 15        | 2.68%   |
| Ukraine     | 14        | 2.5%    |
| Sweden      | 12        | 2.15%   |
| Italy       | 12        | 2.15%   |
| Greece      | 12        | 2.15%   |
| Australia   | 10        | 1.79%   |
| Brazil      | 9         | 1.61%   |
| Czechia     | 8         | 1.43%   |
| Japan       | 7         | 1.25%   |
| Switzerland | 6         | 1.07%   |
| Hong Kong   | 6         | 1.07%   |
| Belgium     | 6         | 1.07%   |
| Norway      | 5         | 0.89%   |
| Austria     | 5         | 0.89%   |
| Turkey      | 4         | 0.72%   |
| Belarus     | 4         | 0.72%   |
| Slovakia    | 3         | 0.54%   |
| Tunisia     | 2         | 0.36%   |
| Taiwan      | 2         | 0.36%   |
| Romania     | 2         | 0.36%   |
| Portugal    | 2         | 0.36%   |
| New Zealand | 2         | 0.36%   |
| Mexico      | 2         | 0.36%   |
| Jamaica     | 2         | 0.36%   |
| Ireland     | 2         | 0.36%   |
| Indonesia   | 2         | 0.36%   |
| India       | 2         | 0.36%   |
| Hungary     | 2         | 0.36%   |
| Chile       | 2         | 0.36%   |
| Bulgaria    | 2         | 0.36%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 17        | 2.86%   |
| Berlin            | 13        | 2.19%   |
| Athens            | 12        | 2.02%   |
| St Petersburg     | 10        | 1.68%   |
| Warsaw            | 7         | 1.18%   |
| Vladivostok       | 7         | 1.18%   |
| Kyiv              | 7         | 1.18%   |
| Ottawa            | 6         | 1.01%   |
| Munich            | 6         | 1.01%   |
| Helsinki          | 6         | 1.01%   |
| Dienheim          | 6         | 1.01%   |
| Sao Paulo         | 5         | 0.84%   |
| Cieszyn           | 5         | 0.84%   |
| Amsterdam         | 5         | 0.84%   |
| Zurich            | 4         | 0.67%   |
| Swansea           | 4         | 0.67%   |
| Suffolk           | 4         | 0.67%   |
| Paris             | 4         | 0.67%   |
| Oulu              | 4         | 0.67%   |
| Melbourne         | 4         | 0.67%   |
| Hamburg           | 4         | 0.67%   |
| Guangzhou         | 4         | 0.67%   |
| Frankfurt am Main | 4         | 0.67%   |
| Almere Stad       | 4         | 0.67%   |
| Yuen Long         | 3         | 0.51%   |
| Vancouver         | 3         | 0.51%   |
| Tromsø           | 3         | 0.51%   |
| Minsk             | 3         | 0.51%   |
| Marburg           | 3         | 0.51%   |
| Manitowoc         | 3         | 0.51%   |
| Madrid            | 3         | 0.51%   |
| London            | 3         | 0.51%   |
| Falkenstein       | 3         | 0.51%   |
| Combrit           | 3         | 0.51%   |
| Chongqing         | 3         | 0.51%   |
| Beijing           | 3         | 0.51%   |
| Zaragoza          | 2         | 0.34%   |
| Yekaterinburg     | 2         | 0.34%   |
| Vigo              | 2         | 0.34%   |
| Vechelde          | 2         | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 219       | 401    | 22.77%  |
| WDC                            | 183       | 355    | 19.02%  |
| Seagate                        | 135       | 269    | 14.03%  |
| Kingston                       | 58        | 76     | 6.03%   |
| Toshiba                        | 49        | 64     | 5.09%   |
| Intel                          | 46        | 73     | 4.78%   |
| SanDisk                        | 28        | 40     | 2.91%   |
| Unknown                        | 26        | 34     | 2.7%    |
| Hitachi                        | 26        | 57     | 2.7%    |
| Crucial                        | 22        | 32     | 2.29%   |
| SK hynix                       | 20        | 26     | 2.08%   |
| A-DATA Technology              | 20        | 30     | 2.08%   |
| HGST                           | 15        | 24     | 1.56%   |
| Phison                         | 10        | 16     | 1.04%   |
| Corsair                        | 10        | 15     | 1.04%   |
| Micron Technology              | 7         | 10     | 0.73%   |
| OCZ                            | 6         | 8      | 0.62%   |
| KIOXIA                         | 6         | 9      | 0.62%   |
| GOODRAM                        | 5         | 10     | 0.52%   |
| Apple                          | 5         | 6      | 0.52%   |
| Plextor                        | 4         | 4      | 0.42%   |
| IBM                            | 4         | 5      | 0.42%   |
| XPG                            | 3         | 3      | 0.31%   |
| Transcend                      | 3         | 3      | 0.31%   |
| Team                           | 3         | 6      | 0.31%   |
| Mushkin                        | 3         | 3      | 0.31%   |
| Gigabyte Technology            | 3         | 4      | 0.31%   |
| SPCC                           | 2         | 2      | 0.21%   |
| Patriot                        | 2         | 3      | 0.21%   |
| MDT                            | 2         | 2      | 0.21%   |
| LITEONIT                       | 2         | 2      | 0.21%   |
| LITEON                         | 2         | 2      | 0.21%   |
| Intenso                        | 2         | 3      | 0.21%   |
| Fujitsu                        | 2         | 3      | 0.21%   |
| Apacer                         | 2         | 3      | 0.21%   |
| T-FORCE                        | 1         | 1      | 0.1%    |
| SSSTC                          | 1         | 1      | 0.1%    |
| Solid State Storage Technology | 1         | 1      | 0.1%    |
| Silicon Motion                 | 1         | 4      | 0.1%    |
| ShanDianZhe                    | 1         | 2      | 0.1%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Samsung SSD 850 EVO 500GB        | 13        | 1.12%   |
| Samsung SSD 860 EVO 1TB          | 12        | 1.04%   |
| Samsung SSD 850 EVO 250GB        | 12        | 1.04%   |
| WDC WD30EFRX-68EUZN0 3TB         | 10        | 0.86%   |
| Samsung SSD 970 EVO 500GB        | 10        | 0.86%   |
| Samsung SSD 860 EVO 250GB        | 10        | 0.86%   |
| Kingston SA400S37240G 240GB SSD  | 10        | 0.86%   |
| Samsung SSD 970 EVO Plus 500GB   | 9         | 0.78%   |
| Samsung SSD 860 EVO 500GB        | 9         | 0.78%   |
| Samsung SSD 840 EVO 120GB        | 9         | 0.78%   |
| Kingston SA400S37480G 480GB SSD  | 9         | 0.78%   |
| Seagate ST1000DM010-2EP102 1TB   | 8         | 0.69%   |
| Samsung SSD 970 EVO 1TB          | 8         | 0.69%   |
| WDC WD40EFRX-68WT0N0 4TB         | 7         | 0.6%    |
| Samsung SSD 970 PRO 512GB        | 7         | 0.6%    |
| Samsung SSD 970 EVO 250GB        | 7         | 0.6%    |
| Samsung SSD 960 EVO 500GB        | 7         | 0.6%    |
| Intel SSDPEKNW010T8 1TB          | 7         | 0.6%    |
| WDC WD40EFRX-68N32N0 4TB         | 6         | 0.52%   |
| WDC WD20EFRX-68EUZN0 2TB         | 6         | 0.52%   |
| WDC WD10EZEX-08WN4A0 1TB         | 6         | 0.52%   |
| Seagate ST2000DM001-1ER164 2TB   | 6         | 0.52%   |
| Seagate ST1000LM049-2GH172 1TB   | 6         | 0.52%   |
| Samsung SSD 970 EVO Plus 250GB   | 6         | 0.52%   |
| Samsung SSD 970 EVO Plus 1TB     | 6         | 0.52%   |
| Samsung MZVLB512HBJQ-000L2 512GB | 6         | 0.52%   |
| Kingston SA400S37120G 120GB SSD  | 6         | 0.52%   |
| WDC WD40EZRZ-00GXCB0 4TB         | 5         | 0.43%   |
| Unknown MMC Card  32GB           | 5         | 0.43%   |
| Toshiba MQ04ABF100 1TB           | 5         | 0.43%   |
| Seagate ST4000DM004-2CV104 4TB   | 5         | 0.43%   |
| Seagate ST3500418AS 500GB        | 5         | 0.43%   |
| Seagate ST2000DM006-2DM164 2TB   | 5         | 0.43%   |
| Seagate ST1000DM003-1CH162 1TB   | 5         | 0.43%   |
| Samsung SSD 980 PRO 1TB          | 5         | 0.43%   |
| Samsung SSD 840 PRO Series 256GB | 5         | 0.43%   |
| Samsung SSD 840 EVO 250GB        | 5         | 0.43%   |
| Kingston SA2000M81000G 1TB       | 5         | 0.43%   |
| Intel SSDPEKNW512G8 512GB        | 5         | 0.43%   |
| HGST HTS721010A9E630 1TB         | 5         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 134       | 267    | 37.02%  |
| Seagate             | 130       | 261    | 35.91%  |
| Toshiba             | 32        | 44     | 8.84%   |
| Hitachi             | 26        | 57     | 7.18%   |
| HGST                | 15        | 24     | 4.14%   |
| Samsung Electronics | 12        | 18     | 3.31%   |
| IBM                 | 4         | 5      | 1.1%    |
| Unknown             | 3         | 3      | 0.83%   |
| MDT                 | 2         | 2      | 0.55%   |
| Fujitsu             | 2         | 3      | 0.55%   |
| IBM/Hitachi         | 1         | 1      | 0.28%   |
| Apple               | 1         | 1      | 0.28%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 108       | 169    | 35.76%  |
| Kingston            | 44        | 56     | 14.57%  |
| SanDisk             | 23        | 35     | 7.62%   |
| Crucial             | 20        | 30     | 6.62%   |
| WDC                 | 16        | 24     | 5.3%    |
| Intel               | 15        | 17     | 4.97%   |
| A-DATA Technology   | 9         | 14     | 2.98%   |
| OCZ                 | 6         | 8      | 1.99%   |
| Micron Technology   | 6         | 9      | 1.99%   |
| SK hynix            | 5         | 5      | 1.66%   |
| GOODRAM             | 5         | 10     | 1.66%   |
| Plextor             | 4         | 4      | 1.32%   |
| Corsair             | 4         | 5      | 1.32%   |
| Transcend           | 3         | 3      | 0.99%   |
| Team                | 2         | 3      | 0.66%   |
| Seagate             | 2         | 5      | 0.66%   |
| Mushkin             | 2         | 2      | 0.66%   |
| LITEONIT            | 2         | 2      | 0.66%   |
| Intenso             | 2         | 3      | 0.66%   |
| Apple               | 2         | 2      | 0.66%   |
| Unknown             | 1         | 1      | 0.33%   |
| Toshiba             | 1         | 1      | 0.33%   |
| SPCC                | 1         | 1      | 0.33%   |
| ShanDianZhe         | 1         | 2      | 0.33%   |
| RevuAhn             | 1         | 1      | 0.33%   |
| PNY                 | 1         | 1      | 0.33%   |
| Patriot             | 1         | 2      | 0.33%   |
| MyDigitalSSD        | 1         | 1      | 0.33%   |
| Lite-On             | 1         | 1      | 0.33%   |
| Linux               | 1         | 1      | 0.33%   |
| Leven               | 1         | 2      | 0.33%   |
| Lenovo              | 1         | 2      | 0.33%   |
| KingDian            | 1         | 1      | 0.33%   |
| Kimtigo             | 1         | 1      | 0.33%   |
| Faspeed             | 1         | 1      | 0.33%   |
| EMTEC               | 1         | 3      | 0.33%   |
| China               | 1         | 1      | 0.33%   |
| BIWIN               | 1         | 1      | 0.33%   |
| ASUS-PHISON         | 1         | 1      | 0.33%   |
| Apacer              | 1         | 2      | 0.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 311       | 486    | 36.29%  |
| HDD     | 277       | 686    | 32.32%  |
| SSD     | 245       | 436    | 28.59%  |
| MMC     | 21        | 29     | 2.45%   |
| Unknown | 3         | 3      | 0.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 380       | 1101   | 52.13%  |
| NVMe | 310       | 485    | 42.52%  |
| MMC  | 21        | 29     | 2.88%   |
| SAS  | 18        | 25     | 2.47%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 255       | 482    | 43.74%  |
| 0.51-1.0   | 166       | 253    | 28.47%  |
| 1.01-2.0   | 74        | 164    | 12.69%  |
| 3.01-4.0   | 39        | 81     | 6.69%   |
| 2.01-3.0   | 27        | 58     | 4.63%   |
| 4.01-10.0  | 18        | 76     | 3.09%   |
| 10.01-20.0 | 3         | 7      | 0.51%   |
| 20.01-50.0 | 1         | 1      | 0.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 112       | 18.95%  |
| 251-500        | 105       | 17.77%  |
| 101-250        | 100       | 16.92%  |
| 1001-2000      | 76        | 12.86%  |
| More than 3000 | 63        | 10.66%  |
| Unknown        | 33        | 5.58%   |
| 2001-3000      | 30        | 5.08%   |
| 1-20           | 28        | 4.74%   |
| 51-100         | 28        | 4.74%   |
| 21-50          | 16        | 2.71%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 105       | 16.85%  |
| 101-250        | 97        | 15.57%  |
| 21-50          | 88        | 14.13%  |
| 251-500        | 80        | 12.84%  |
| 501-1000       | 64        | 10.27%  |
| 51-100         | 58        | 9.31%   |
| 1001-2000      | 49        | 7.87%   |
| Unknown        | 33        | 5.3%    |
| More than 3000 | 31        | 4.98%   |
| 2001-3000      | 18        | 2.89%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST3500418AS 500GB                    | 4         | 5      | 3.31%   |
| WDC WD40EFRX-68WT0N0 4TB                     | 3         | 13     | 2.48%   |
| Seagate ST8000AS0002-1NA17Z 8TB              | 3         | 15     | 2.48%   |
| Seagate ST500DM002-1BC142 500GB              | 3         | 3      | 2.48%   |
| IBM DJSA-220 12GB                            | 3         | 3      | 2.48%   |
| WDC WD2002FAEX-007BA0 2TB                    | 2         | 2      | 1.65%   |
| Seagate ST31000340NS 1TB                     | 2         | 3      | 1.65%   |
| Seagate ST2000LX001-1RG174 2TB               | 2         | 2      | 1.65%   |
| Seagate ST2000DL003-9VT166 2TB               | 2         | 3      | 1.65%   |
| Seagate ST1000NM0011 1TB                     | 2         | 6      | 1.65%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD          | 2         | 2      | 1.65%   |
| Samsung Electronics SSD 840 PRO Series 512GB | 2         | 4      | 1.65%   |
| MDT MD2000KS-00MJB0 200GB                    | 2         | 2      | 1.65%   |
| Hitachi HDS722020ALA330 2TB                  | 2         | 14     | 1.65%   |
| HGST HTS721010A9E630 1TB                     | 2         | 2      | 1.65%   |
| WDC WD80EFZX-68UW8N0 8TB                     | 1         | 2      | 0.83%   |
| WDC WD6401AALS-00J7B0 640GB                  | 1         | 1      | 0.83%   |
| WDC WD6400AAKS-65A7B2 640GB                  | 1         | 1      | 0.83%   |
| WDC WD60EFRX-68MYMN1 6TB                     | 1         | 1      | 0.83%   |
| WDC WD60EFRX-68L0BN1 6TB                     | 1         | 6      | 0.83%   |
| WDC WD5000AAVS-22G9B1 500GB                  | 1         | 1      | 0.83%   |
| WDC WD5000AAKX-003CA0 500GB                  | 1         | 1      | 0.83%   |
| WDC WD40EFRX-68N32N0 4TB                     | 1         | 1      | 0.83%   |
| WDC WD4004FZWX-00GBGB0 4TB                   | 1         | 1      | 0.83%   |
| WDC WD30EFRX-68EUZN0 3TB                     | 1         | 1      | 0.83%   |
| WDC WD30EFRX-68AX9N0 3TB                     | 1         | 1      | 0.83%   |
| WDC WD3001FAEX-00MJRA0 3TB                   | 1         | 2      | 0.83%   |
| WDC WD2502ABYS-02B7A0 256GB                  | 1         | 1      | 0.83%   |
| WDC WD20EZRZ-00Z5HB0 2TB                     | 1         | 1      | 0.83%   |
| WDC WD20EZRX-00D8PB0 2TB                     | 1         | 2      | 0.83%   |
| WDC WD2003FZEX-00Z4SA0 2TB                   | 1         | 1      | 0.83%   |
| WDC WD1600AAJS-75B4A0 160GB                  | 1         | 1      | 0.83%   |
| WDC WD10SPZX-24Z10T0 1TB                     | 1         | 1      | 0.83%   |
| WDC WD10EZRX-00A8LB0 1TB                     | 1         | 1      | 0.83%   |
| WDC WD10EACS-22D6B0 1TB                      | 1         | 1      | 0.83%   |
| WDC WD1003FZEX-00MK2A0 1TB                   | 1         | 2      | 0.83%   |
| Toshiba MQ04ABF100 1TB                       | 1         | 1      | 0.83%   |
| Toshiba HDWD130 3TB                          | 1         | 1      | 0.83%   |
| Toshiba HDWD105 500GB                        | 1         | 2      | 0.83%   |
| Toshiba DT01ACA300 3TB                       | 1         | 1      | 0.83%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 34        | 59     | 30.09%  |
| WDC                 | 24        | 45     | 21.24%  |
| Samsung Electronics | 12        | 17     | 10.62%  |
| Hitachi             | 8         | 20     | 7.08%   |
| Toshiba             | 5         | 6      | 4.42%   |
| SanDisk             | 4         | 5      | 3.54%   |
| HGST                | 4         | 5      | 3.54%   |
| IBM                 | 3         | 3      | 2.65%   |
| SK hynix            | 2         | 2      | 1.77%   |
| Plextor             | 2         | 2      | 1.77%   |
| MDT                 | 2         | 2      | 1.77%   |
| Kingston            | 2         | 2      | 1.77%   |
| Intel               | 2         | 2      | 1.77%   |
| Crucial             | 2         | 2      | 1.77%   |
| OCZ                 | 1         | 1      | 0.88%   |
| Mushkin             | 1         | 1      | 0.88%   |
| IBM/Hitachi         | 1         | 1      | 0.88%   |
| Fujitsu             | 1         | 1      | 0.88%   |
| EMTEC               | 1         | 2      | 0.88%   |
| Corsair             | 1         | 2      | 0.88%   |
| Apple               | 1         | 1      | 0.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 34        | 59     | 40%     |
| WDC                 | 24        | 45     | 28.24%  |
| Hitachi             | 8         | 20     | 9.41%   |
| Toshiba             | 5         | 6      | 5.88%   |
| HGST                | 4         | 5      | 4.71%   |
| IBM                 | 3         | 3      | 3.53%   |
| Samsung Electronics | 2         | 3      | 2.35%   |
| MDT                 | 2         | 2      | 2.35%   |
| IBM/Hitachi         | 1         | 1      | 1.18%   |
| Fujitsu             | 1         | 1      | 1.18%   |
| Apple               | 1         | 1      | 1.18%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 79        | 146    | 73.83%  |
| SSD  | 23        | 28     | 21.5%   |
| NVMe | 5         | 7      | 4.67%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD6400BEVT-22A0RT0 640GB                     | 1         | 1      | 20%     |
| Toshiba THNSN5512GPUK NVMe 512GB                 | 1         | 1      | 20%     |
| Seagate ST31500341AS 1TB                         | 1         | 1      | 20%     |
| Samsung Electronics MZ7LN256HCHP-00000 256GB SSD | 1         | 2      | 20%     |
| Hitachi HTS721010G9SA00 100GB                    | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 20%     |
| Toshiba             | 1         | 1      | 20%     |
| Seagate             | 1         | 1      | 20%     |
| Samsung Electronics | 1         | 2      | 20%     |
| Hitachi             | 1         | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 496       | 1327   | 74.14%  |
| Malfunc  | 104       | 181    | 15.55%  |
| Detected | 64        | 126    | 9.57%   |
| Failed   | 5         | 6      | 0.75%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 283       | 33.49%  |
| AMD                            | 184       | 21.78%  |
| Samsung Electronics            | 144       | 17.04%  |
| SanDisk                        | 48        | 5.68%   |
| ASMedia Technology             | 30        | 3.55%   |
| Phison Electronics             | 23        | 2.72%   |
| Toshiba America Info Systems   | 19        | 2.25%   |
| Kingston Technology Company    | 16        | 1.89%   |
| SK hynix                       | 15        | 1.78%   |
| ADATA Technology               | 14        | 1.66%   |
| Marvell Technology Group       | 11        | 1.3%    |
| LSI Logic / Symbios Logic      | 7         | 0.83%   |
| KIOXIA                         | 7         | 0.83%   |
| JMicron Technology             | 7         | 0.83%   |
| Nvidia                         | 5         | 0.59%   |
| Silicon Motion                 | 4         | 0.47%   |
| Silicon Image                  | 3         | 0.36%   |
| Realtek Semiconductor          | 3         | 0.36%   |
| Broadcom / LSI                 | 3         | 0.36%   |
| Adaptec                        | 3         | 0.36%   |
| Solid State Storage Technology | 2         | 0.24%   |
| Seagate Technology             | 2         | 0.24%   |
| Micron/Crucial Technology      | 2         | 0.24%   |
| Lite-On Technology             | 2         | 0.24%   |
| Apple                          | 2         | 0.24%   |
| VIA Technologies               | 1         | 0.12%   |
| Union Memory (Shenzhen)        | 1         | 0.12%   |
| Micron Technology              | 1         | 0.12%   |
| Lite-On IT Corp. / Plextor     | 1         | 0.12%   |
| Integrated Technology Express  | 1         | 0.12%   |
| Hewlett-Packard                | 1         | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 145       | 14.87%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 92        | 9.44%   |
| AMD 400 Series Chipset SATA Controller                                         | 45        | 4.62%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 29        | 2.97%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 27        | 2.77%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 24        | 2.46%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 23        | 2.36%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 20        | 2.05%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 19        | 1.95%   |
| Intel SSD 660P Series                                                          | 17        | 1.74%   |
| AMD 500 Series Chipset SATA Controller                                         | 16        | 1.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 15        | 1.54%   |
| Samsung NVMe SSD Controller 980                                                | 15        | 1.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 14        | 1.44%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 14        | 1.44%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 12        | 1.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 12        | 1.23%   |
| AMD X370 Series Chipset SATA Controller                                        | 12        | 1.23%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 11        | 1.13%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 10        | 1.03%   |
| Phison E16 PCIe4 NVMe Controller                                               | 10        | 1.03%   |
| Intel SATA Controller [RAID mode]                                              | 10        | 1.03%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 10        | 1.03%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 9         | 0.92%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 9         | 0.92%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 9         | 0.92%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 9         | 0.92%   |
| AMD 300 Series Chipset SATA Controller                                         | 9         | 0.92%   |
| Phison E12 NVMe Controller                                                     | 8         | 0.82%   |
| Intel Volume Management Device NVMe RAID Controller                            | 8         | 0.82%   |
| Intel Comet Lake SATA AHCI Controller                                          | 8         | 0.82%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 8         | 0.82%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 8         | 0.82%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 7         | 0.72%   |
| Kingston Company A2000 NVMe SSD                                                | 7         | 0.72%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 0.72%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 6         | 0.62%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 6         | 0.62%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 5         | 0.51%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 410       | 49.82%  |
| NVMe | 315       | 38.27%  |
| IDE  | 44        | 5.35%   |
| RAID | 42        | 5.1%    |
| SAS  | 8         | 0.97%   |
| SCSI | 4         | 0.49%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 329       | 59.28%  |
| AMD                      | 215       | 38.74%  |
| ARM                      | 9         | 1.62%   |
| PowerNV C1P9S01 REV 1.01 | 1         | 0.18%   |
| Marvell Semiconductor    | 1         | 0.18%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor            | 15        | 2.69%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 13        | 2.33%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 12        | 2.15%   |
| AMD Ryzen 5 3600 6-Core Processor             | 11        | 1.97%   |
| AMD Ryzen 9 3950X 16-Core Processor           | 10        | 1.79%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 10        | 1.79%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 10        | 1.79%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 1.61%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 8         | 1.43%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 8         | 1.43%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 8         | 1.43%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 7         | 1.25%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 7         | 1.25%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 7         | 1.25%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 6         | 1.08%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 6         | 1.08%   |
| ARM Processor                                 | 6         | 1.08%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 6         | 1.08%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 6         | 1.08%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 6         | 1.08%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 0.9%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 5         | 0.9%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 0.9%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 0.9%    |
| AMD Ryzen 7 2700 Eight-Core Processor         | 5         | 0.9%    |
| AMD Ryzen 5 4600H with Radeon Graphics        | 5         | 0.9%    |
| AMD Ryzen 5 1600 Six-Core Processor           | 5         | 0.9%    |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 5         | 0.9%    |
| AMD FX-8350 Eight-Core Processor              | 5         | 0.9%    |
| Intel Core i9-9900K CPU @ 3.60GHz             | 4         | 0.72%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 4         | 0.72%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 4         | 0.72%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 4         | 0.72%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 4         | 0.72%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 0.72%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 4         | 0.72%   |
| AMD Ryzen 7 1700 Eight-Core Processor         | 4         | 0.72%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 0.72%   |
| Intel Pentium III (Katmai)                    | 3         | 0.54%   |
| Intel Pentium 4 CPU 3.20GHz                   | 3         | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 122       | 21.94%  |
| Intel Core i5          | 75        | 13.49%  |
| AMD Ryzen 7            | 74        | 13.31%  |
| AMD Ryzen 5            | 56        | 10.07%  |
| Other                  | 35        | 6.29%   |
| AMD Ryzen 9            | 28        | 5.04%   |
| Intel Xeon             | 24        | 4.32%   |
| Intel Core i9          | 13        | 2.34%   |
| AMD Ryzen 7 PRO        | 13        | 2.34%   |
| Intel Core i3          | 10        | 1.8%    |
| Intel Core 2 Duo       | 10        | 1.8%    |
| Intel Celeron          | 10        | 1.8%    |
| AMD FX                 | 10        | 1.8%    |
| Intel Pentium          | 8         | 1.44%   |
| Intel Core 2 Quad      | 7         | 1.26%   |
| AMD Ryzen 3            | 7         | 1.26%   |
| Intel Atom             | 5         | 0.9%    |
| Intel Pentium 4        | 4         | 0.72%   |
| AMD Ryzen Threadripper | 4         | 0.72%   |
| AMD Ryzen 5 PRO        | 4         | 0.72%   |
| AMD Phenom II X4       | 4         | 0.72%   |
| Intel Pentium M        | 3         | 0.54%   |
| Intel Pentium III      | 3         | 0.54%   |
| AMD A6                 | 3         | 0.54%   |
| Intel Pentium Silver   | 2         | 0.36%   |
| Intel Core 2           | 2         | 0.36%   |
| ARM BCM                | 2         | 0.36%   |
| AMD Sempron            | 2         | 0.36%   |
| AMD Phenom II X6       | 2         | 0.36%   |
| AMD Athlon 64 X2       | 2         | 0.36%   |
| AMD A8                 | 2         | 0.36%   |
| AMD A10                | 2         | 0.36%   |
| Intel Xeon Silver      | 1         | 0.18%   |
| Intel Xeon Gold        | 1         | 0.18%   |
| Intel Core m3          | 1         | 0.18%   |
| Intel Celeron M        | 1         | 0.18%   |
| ARM Allwinner          | 1         | 0.18%   |
| AMD E1                 | 1         | 0.18%   |
| AMD E                  | 1         | 0.18%   |
| AMD Athlon 64          | 1         | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 198       | 35.48%  |
| 8       | 114       | 20.43%  |
| 6       | 101       | 18.1%   |
| 2       | 81        | 14.52%  |
| 16      | 17        | 3.05%   |
| 12      | 17        | 3.05%   |
| 1       | 16        | 2.87%   |
| Unknown | 3         | 0.54%   |
| 32      | 2         | 0.36%   |
| 14      | 2         | 0.36%   |
| 10      | 2         | 0.36%   |
| 3       | 2         | 0.36%   |
| 64      | 1         | 0.18%   |
| 24      | 1         | 0.18%   |
| 18      | 1         | 0.18%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 542       | 97.31%  |
| 2       | 12        | 2.15%   |
| Unknown | 3         | 0.54%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 423       | 75.81%  |
| 1       | 131       | 23.48%  |
| Unknown | 3         | 0.54%   |
| 4       | 1         | 0.18%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 540       | 97.3%   |
| 32-bit         | 10        | 1.8%    |
| Unknown        | 5         | 0.9%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 81        | 14.06%  |
| 0x08701021 | 31        | 5.38%   |
| 0x906ea    | 28        | 4.86%   |
| 0x0800820d | 26        | 4.51%   |
| 0x08701013 | 22        | 3.82%   |
| 0x506e3    | 21        | 3.65%   |
| 0x906e9    | 19        | 3.3%    |
| 0x08600106 | 18        | 3.13%   |
| 0x806ea    | 17        | 2.95%   |
| 0x806c1    | 15        | 2.6%    |
| 0x306c3    | 15        | 2.6%    |
| 0x306a9    | 15        | 2.6%    |
| 0x806ec    | 14        | 2.43%   |
| 0x0a201009 | 14        | 2.43%   |
| 0xa0652    | 12        | 2.08%   |
| 0x08001138 | 11        | 1.91%   |
| 0x806e9    | 10        | 1.74%   |
| 0x08600103 | 10        | 1.74%   |
| 0x40651    | 9         | 1.56%   |
| 0x1067a    | 9         | 1.56%   |
| 0xa0655    | 8         | 1.39%   |
| 0x0a201016 | 8         | 1.39%   |
| 0x906ed    | 7         | 1.22%   |
| 0x08108109 | 7         | 1.22%   |
| 0x306d4    | 6         | 1.04%   |
| 0x206c2    | 6         | 1.04%   |
| 0x806eb    | 5         | 0.87%   |
| 0x806d1    | 5         | 0.87%   |
| 0x406e3    | 5         | 0.87%   |
| 0x206a7    | 5         | 0.87%   |
| 0x08600104 | 5         | 0.87%   |
| 0xa0671    | 4         | 0.69%   |
| 0x906ec    | 4         | 0.69%   |
| 0x6fb      | 4         | 0.69%   |
| 0x30678    | 4         | 0.69%   |
| 0x0a50000c | 4         | 0.69%   |
| 0x706e5    | 3         | 0.52%   |
| 0x706a1    | 3         | 0.52%   |
| 0x6d8      | 3         | 0.52%   |
| 0x673      | 3         | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 118       | 21.11%  |
| Zen 2            | 98        | 17.53%  |
| Zen+             | 40        | 7.16%   |
| Skylake          | 32        | 5.72%   |
| Zen 3            | 27        | 4.83%   |
| Haswell          | 26        | 4.65%   |
| Zen              | 22        | 3.94%   |
| CometLake        | 21        | 3.76%   |
| IvyBridge        | 18        | 3.22%   |
| Unknown          | 17        | 3.04%   |
| TigerLake        | 16        | 2.86%   |
| Penryn           | 12        | 2.15%   |
| IceLake          | 11        | 1.97%   |
| Westmere         | 10        | 1.79%   |
| Piledriver       | 9         | 1.61%   |
| Broadwell        | 9         | 1.61%   |
| Core             | 8         | 1.43%   |
| Silvermont       | 7         | 1.25%   |
| SandyBridge      | 7         | 1.25%   |
| P6               | 7         | 1.25%   |
| Nehalem          | 7         | 1.25%   |
| K10              | 6         | 1.07%   |
| Goldmont plus    | 5         | 0.89%   |
| NetBurst         | 4         | 0.72%   |
| K8 Hammer        | 3         | 0.54%   |
| Jaguar           | 3         | 0.54%   |
| Goldmont         | 3         | 0.54%   |
| Bonnell          | 3         | 0.54%   |
| Steamroller      | 2         | 0.36%   |
| Excavator        | 2         | 0.36%   |
| Bulldozer        | 2         | 0.36%   |
| Bobcat           | 2         | 0.36%   |
| K10 Llano        | 1         | 0.18%   |
| Alderlake Hybrid | 1         | 0.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Nvidia                     | 217       | 33.49%  |
| Intel                      | 213       | 32.87%  |
| AMD                        | 205       | 31.64%  |
| ASPEED Technology          | 7         | 1.08%   |
| Matrox Electronics Systems | 6         | 0.93%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 39        | 5.86%   |
| AMD Renoir                                                                  | 37        | 5.56%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 24        | 3.61%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 21        | 3.16%   |
| Intel UHD Graphics 620                                                      | 19        | 2.86%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 16        | 2.41%   |
| Intel HD Graphics 530                                                       | 16        | 2.41%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 14        | 2.11%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 12        | 1.8%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 10        | 1.5%    |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 10        | 1.5%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 10        | 1.5%    |
| Intel HD Graphics 620                                                       | 9         | 1.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 9         | 1.35%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 9         | 1.35%   |
| Intel HD Graphics 630                                                       | 8         | 1.2%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 7         | 1.05%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 7         | 1.05%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 7         | 1.05%   |
| ASPEED Technology ASPEED Graphics Family                                    | 7         | 1.05%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 7         | 1.05%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 6         | 0.9%    |
| Nvidia TU117M                                                               | 6         | 0.9%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 6         | 0.9%    |
| Nvidia GP104 [GeForce GTX 1070]                                             | 6         | 0.9%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 6         | 0.9%    |
| Nvidia GM204 [GeForce GTX 970]                                              | 6         | 0.9%    |
| Nvidia GK208B [GeForce GT 710]                                              | 6         | 0.9%    |
| Intel Skylake GT2 [HD Graphics 520]                                         | 6         | 0.9%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 5         | 0.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5         | 0.75%   |
| Intel HD Graphics 5500                                                      | 5         | 0.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 5         | 0.75%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5         | 0.75%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 4         | 0.6%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 4         | 0.6%    |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                     | 4         | 0.6%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 4         | 0.6%    |
| Nvidia GA102 [GeForce RTX 3090]                                             | 4         | 0.6%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 4         | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x AMD                  | 173       | 30.84%  |
| 1 x Nvidia               | 130       | 23.17%  |
| 1 x Intel                | 130       | 23.17%  |
| Intel + Nvidia           | 68        | 12.12%  |
| AMD + Nvidia             | 16        | 2.85%   |
| Other                    | 13        | 2.32%   |
| Intel + AMD              | 9         | 1.6%    |
| 1 x ASPEED               | 6         | 1.07%   |
| 2 x AMD                  | 5         | 0.89%   |
| 1 x Matrox               | 4         | 0.71%   |
| 2 x Nvidia               | 3         | 0.53%   |
| Nvidia + Matrox          | 1         | 0.18%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.18%   |
| AMD + Matrox             | 1         | 0.18%   |
| AMD + ASPEED             | 1         | 0.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 379       | 66.96%  |
| Proprietary | 149       | 26.33%  |
| Unknown     | 38        | 6.71%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 252       | 43.6%   |
| 7.01-8.0   | 80        | 13.84%  |
| 0.01-0.5   | 68        | 11.76%  |
| 1.01-2.0   | 56        | 9.69%   |
| 3.01-4.0   | 54        | 9.34%   |
| 5.01-6.0   | 22        | 3.81%   |
| 0.51-1.0   | 20        | 3.46%   |
| 8.01-16.0  | 14        | 2.42%   |
| 2.01-3.0   | 9         | 1.56%   |
| 16.01-24.0 | 3         | 0.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 67        | 10.24%  |
| Dell                    | 57        | 8.72%   |
| AU Optronics            | 55        | 8.41%   |
| LG Display              | 50        | 7.65%   |
| Goldstar                | 44        | 6.73%   |
| BOE                     | 41        | 6.27%   |
| Chimei Innolux          | 39        | 5.96%   |
| Ancor Communications    | 24        | 3.67%   |
| BenQ                    | 23        | 3.52%   |
| AOC                     | 23        | 3.52%   |
| Iiyama                  | 22        | 3.36%   |
| Sharp                   | 21        | 3.21%   |
| Hewlett-Packard         | 21        | 3.21%   |
| Philips                 | 15        | 2.29%   |
| Acer                    | 15        | 2.29%   |
| Lenovo                  | 13        | 1.99%   |
| ViewSonic               | 12        | 1.83%   |
| ASUSTek Computer        | 10        | 1.53%   |
| Fujitsu Siemens         | 8         | 1.22%   |
| Eizo                    | 8         | 1.22%   |
| Apple                   | 8         | 1.22%   |
| Chi Mei Optoelectronics | 7         | 1.07%   |
| MSI                     | 6         | 0.92%   |
| Idek Iiyama             | 5         | 0.76%   |
| Unknown                 | 4         | 0.61%   |
| PANDA                   | 4         | 0.61%   |
| Gigabyte Technology     | 4         | 0.61%   |
| LG Electronics          | 3         | 0.46%   |
| Envision Peripherals    | 3         | 0.46%   |
| CSO                     | 3         | 0.46%   |
| NEC Computers           | 2         | 0.31%   |
| LGD                     | 2         | 0.31%   |
| InfoVision              | 2         | 0.31%   |
| AUS                     | 2         | 0.31%   |
| YTH                     | 1         | 0.15%   |
| Yamaha                  | 1         | 0.15%   |
| WST                     | 1         | 0.15%   |
| Vizio                   | 1         | 0.15%   |
| Vestel Elektronik       | 1         | 0.15%   |
| Toshiba                 | 1         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Iiyama PL2473HD IVM6107 1920x1080 521x293mm 23.5-inch                  | 6         | 0.87%   |
| Fujitsu Siemens P24W-6 IPS FUS07EA 1920x1200 518x324mm 24.1-inch       | 6         | 0.87%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 6         | 0.87%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch           | 5         | 0.73%   |
| Dell P2418D DELD0C1 2560x1440 526x296mm 23.8-inch                      | 5         | 0.73%   |
| Iiyama PL2409HD IVM560C 1920x1080 520x290mm 23.4-inch                  | 4         | 0.58%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch               | 4         | 0.58%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 4         | 0.58%   |
| Goldstar LG ULTRAGEAR GSM5B7F 2560x1440 600x340mm 27.2-inch            | 4         | 0.58%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                  | 4         | 0.58%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch      | 3         | 0.44%   |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch           | 3         | 0.44%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch           | 3         | 0.44%   |
| Goldstar ULTRAWIDE GSM76E4 3440x1440 800x335mm 34.1-inch               | 3         | 0.44%   |
| Gigabyte Technology G34WQC GBT3400 3440x1440 800x330mm 34.1-inch       | 3         | 0.44%   |
| Envision Peripherals LCD2361 ENV2361 1920x1080 521x293mm 23.5-inch     | 3         | 0.44%   |
| BenQ PD3200U BNQ8025 3840x2160 708x399mm 32.0-inch                     | 3         | 0.44%   |
| BenQ LCD BNQ801E 3840x2160 596x335mm 26.9-inch                         | 3         | 0.44%   |
| ViewSonic VG3448 VSC0D38 3440x1440 800x330mm 34.1-inch                 | 2         | 0.29%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch                | 2         | 0.29%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                | 2         | 0.29%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                | 2         | 0.29%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                | 2         | 0.29%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 2         | 0.29%   |
| Samsung Electronics U28E570 SAM0D71 3840x2160 608x345mm 27.5-inch      | 2         | 0.29%   |
| Samsung Electronics S24B300 SAM08CC 1920x1080 521x293mm 23.5-inch      | 2         | 0.29%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch   | 2         | 0.29%   |
| Samsung Electronics LCD Monitor SAM0D74 1920x1080 1210x680mm 54.6-inch | 2         | 0.29%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch  | 2         | 0.29%   |
| Samsung Electronics LCD Monitor SAM0B7C 1920x1080 890x500mm 40.2-inch  | 2         | 0.29%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch    | 2         | 0.29%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch     | 2         | 0.29%   |
| Samsung Electronics C49HG9x SAM0E5E 3840x1080 1200x340mm 49.1-inch     | 2         | 0.29%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 2         | 0.29%   |
| Philips PHL 246E9Q PHLC17C 1920x1080 527x296mm 23.8-inch               | 2         | 0.29%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 2         | 0.29%   |
| MSI Optix G241VC MSI1462 1920x1080 521x294mm 23.6-inch                 | 2         | 0.29%   |
| MSI MAG274QRF MSI3CA8 2560x1440 597x336mm 27.0-inch                    | 2         | 0.29%   |
| LGD LCD Monitor 1920x1080                                              | 2         | 0.29%   |
| LG Display LCD Monitor LGD0657 1920x1080 344x194mm 15.5-inch           | 2         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 299       | 47.99%  |
| 3840x2160 (4K)     | 63        | 10.11%  |
| 2560x1440 (QHD)    | 57        | 9.15%   |
| 1366x768 (WXGA)    | 38        | 6.1%    |
| 1920x1200 (WUXGA)  | 27        | 4.33%   |
| 3440x1440          | 23        | 3.69%   |
| 1280x1024 (SXGA)   | 14        | 2.25%   |
| 1680x1050 (WSXGA+) | 11        | 1.77%   |
| 1600x900 (HD+)     | 11        | 1.77%   |
| 2560x1080          | 9         | 1.44%   |
| Unknown            | 9         | 1.44%   |
| 3840x1080          | 8         | 1.28%   |
| 3840x2400          | 7         | 1.12%   |
| 2560x1600          | 7         | 1.12%   |
| 1440x900 (WXGA+)   | 6         | 0.96%   |
| 1280x800 (WXGA)    | 5         | 0.8%    |
| 3840x1200          | 3         | 0.48%   |
| 3200x1800 (QHD+)   | 2         | 0.32%   |
| 2160x1440          | 2         | 0.32%   |
| 1600x1200          | 2         | 0.32%   |
| 1400x1050          | 2         | 0.32%   |
| 1280x960           | 2         | 0.32%   |
| 6720x2160          | 1         | 0.16%   |
| 5040x1080          | 1         | 0.16%   |
| 4880x1080          | 1         | 0.16%   |
| 4382x1080          | 1         | 0.16%   |
| 3926x1440          | 1         | 0.16%   |
| 3600x1080          | 1         | 0.16%   |
| 3456x2160          | 1         | 0.16%   |
| 3072x1920          | 1         | 0.16%   |
| 2880x1800          | 1         | 0.16%   |
| 2304x1440          | 1         | 0.16%   |
| 2288x1287          | 1         | 0.16%   |
| 2160x1200          | 1         | 0.16%   |
| 2048x1152          | 1         | 0.16%   |
| 1920x540           | 1         | 0.16%   |
| 1280x768           | 1         | 0.16%   |
| 1024x600           | 1         | 0.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 117       | 18.06%  |
| 27      | 87        | 13.43%  |
| 24      | 75        | 11.57%  |
| 23      | 62        | 9.57%   |
| 13      | 53        | 8.18%   |
| Unknown | 40        | 6.17%   |
| 14      | 36        | 5.56%   |
| 21      | 30        | 4.63%   |
| 34      | 25        | 3.86%   |
| 17      | 18        | 2.78%   |
| 19      | 16        | 2.47%   |
| 12      | 13        | 2.01%   |
| 31      | 10        | 1.54%   |
| 11      | 8         | 1.23%   |
| 25      | 7         | 1.08%   |
| 20      | 7         | 1.08%   |
| 22      | 6         | 0.93%   |
| 48      | 5         | 0.77%   |
| 32      | 4         | 0.62%   |
| 84      | 3         | 0.46%   |
| 54      | 3         | 0.46%   |
| 18      | 3         | 0.46%   |
| 16      | 3         | 0.46%   |
| 58      | 2         | 0.31%   |
| 49      | 2         | 0.31%   |
| 47      | 2         | 0.31%   |
| 43      | 2         | 0.31%   |
| 29      | 2         | 0.31%   |
| 26      | 2         | 0.31%   |
| 142     | 1         | 0.15%   |
| 40      | 1         | 0.15%   |
| 37      | 1         | 0.15%   |
| 33      | 1         | 0.15%   |
| 8       | 1         | 0.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 501-600        | 195       | 31.15%  |
| 301-350        | 182       | 29.07%  |
| 401-500        | 53        | 8.47%   |
| 201-300        | 52        | 8.31%   |
| Unknown        | 40        | 6.39%   |
| 701-800        | 30        | 4.79%   |
| 601-700        | 28        | 4.47%   |
| 351-400        | 23        | 3.67%   |
| 1001-1500      | 15        | 2.4%    |
| 1501-2000      | 3         | 0.48%   |
| 801-900        | 2         | 0.32%   |
| More than 2000 | 1         | 0.16%   |
| 101-200        | 1         | 0.16%   |
| 901-1000       | 1         | 0.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 402       | 70.9%   |
| 16/10   | 71        | 12.52%  |
| Unknown | 37        | 6.53%   |
| 21/9    | 26        | 4.59%   |
| 5/4     | 14        | 2.47%   |
| 32/9    | 7         | 1.23%   |
| 3/2     | 4         | 0.71%   |
| 4/3     | 3         | 0.53%   |
| 6/5     | 1         | 0.18%   |
| 3.20    | 1         | 0.18%   |
| 1.00    | 1         | 0.18%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 127       | 19.81%  |
| 101-110        | 116       | 18.1%   |
| 301-350        | 88        | 13.73%  |
| 81-90          | 60        | 9.36%   |
| 351-500        | 41        | 6.4%    |
| 251-300        | 41        | 6.4%    |
| Unknown        | 40        | 6.24%   |
| 151-200        | 29        | 4.52%   |
| 71-80          | 28        | 4.37%   |
| 61-70          | 13        | 2.03%   |
| 501-1000       | 12        | 1.87%   |
| 121-130        | 11        | 1.72%   |
| More than 1000 | 10        | 1.56%   |
| 141-150        | 9         | 1.4%    |
| 51-60          | 8         | 1.25%   |
| 111-120        | 3         | 0.47%   |
| 91-100         | 3         | 0.47%   |
| 1-40           | 1         | 0.16%   |
| 131-140        | 1         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 206       | 33.28%  |
| 121-160       | 181       | 29.24%  |
| 101-120       | 106       | 17.12%  |
| 161-240       | 50        | 8.08%   |
| Unknown       | 40        | 6.46%   |
| More than 240 | 25        | 4.04%   |
| 1-50          | 11        | 1.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 394       | 68.4%   |
| 2     | 119       | 20.66%  |
| 0     | 44        | 7.64%   |
| 3     | 17        | 2.95%   |
| 4     | 2         | 0.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 345       | 42.8%   |
| Realtek Semiconductor             | 266       | 33%     |
| Qualcomm Atheros                  | 67        | 8.31%   |
| Broadcom                          | 27        | 3.35%   |
| ASIX Electronics                  | 10        | 1.24%   |
| Lenovo                            | 9         | 1.12%   |
| Marvell Technology Group          | 8         | 0.99%   |
| Aquantia                          | 7         | 0.87%   |
| TP-Link                           | 6         | 0.74%   |
| Dell                              | 5         | 0.62%   |
| Qualcomm Atheros Communications   | 4         | 0.5%    |
| MediaTek                          | 4         | 0.5%    |
| Ralink Technology                 | 3         | 0.37%   |
| Qualcomm                          | 3         | 0.37%   |
| Nvidia                            | 3         | 0.37%   |
| Fibocom                           | 3         | 0.37%   |
| D-Link System                     | 3         | 0.37%   |
| Broadcom Limited                  | 3         | 0.37%   |
| Xiaomi                            | 2         | 0.25%   |
| Ralink                            | 2         | 0.25%   |
| QLogic                            | 2         | 0.25%   |
| Netchip Technology                | 2         | 0.25%   |
| Metrologic Instruments            | 2         | 0.25%   |
| D-Link                            | 2         | 0.25%   |
| Apple                             | 2         | 0.25%   |
| 3Com                              | 2         | 0.25%   |
| U-Blox                            | 1         | 0.12%   |
| Texas Instruments                 | 1         | 0.12%   |
| Standard Microsystems             | 1         | 0.12%   |
| Sierra Wireless                   | 1         | 0.12%   |
| Shenzhen Goodix Technology        | 1         | 0.12%   |
| Quectel Wireless Solutions        | 1         | 0.12%   |
| Pulse-Eight                       | 1         | 0.12%   |
| Microchip Technology              | 1         | 0.12%   |
| Kyocera                           | 1         | 0.12%   |
| InterBiometrics                   | 1         | 0.12%   |
| Google                            | 1         | 0.12%   |
| Ericsson Business Mobile Networks | 1         | 0.12%   |
| Davicom Semiconductor             | 1         | 0.12%   |
| AMD                               | 1         | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 201       | 20.72%  |
| Intel Wi-Fi 6 AX200                                               | 69        | 7.11%   |
| Intel I211 Gigabit Network Connection                             | 57        | 5.88%   |
| Intel Wireless 8265 / 8275                                        | 21        | 2.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 20        | 2.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 19        | 1.96%   |
| Realtek RTL8125 2.5GbE Controller                                 | 18        | 1.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 14        | 1.44%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 1.44%   |
| Intel Wi-Fi 6 AX201                                               | 14        | 1.44%   |
| Intel I210 Gigabit Network Connection                             | 14        | 1.44%   |
| Intel Ethernet Connection (2) I219-V                              | 14        | 1.44%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 14        | 1.44%   |
| Intel Ethernet Controller I225-V                                  | 13        | 1.34%   |
| Intel Ethernet Connection (2) I219-LM                             | 12        | 1.24%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 11        | 1.13%   |
| Intel 82574L Gigabit Network Connection                           | 11        | 1.13%   |
| Intel Wireless-AC 9260                                            | 9         | 0.93%   |
| Intel Wireless 8260                                               | 9         | 0.93%   |
| Intel Ethernet Connection (7) I219-V                              | 9         | 0.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 9         | 0.93%   |
| Intel Wireless 7260                                               | 8         | 0.82%   |
| Intel Wireless 3165                                               | 8         | 0.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 8         | 0.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 8         | 0.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 0.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 7         | 0.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7         | 0.72%   |
| Intel I350 Gigabit Network Connection                             | 7         | 0.72%   |
| Intel Ethernet Connection (4) I219-V                              | 7         | 0.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 0.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 6         | 0.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 6         | 0.62%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 6         | 0.62%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 0.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 0.52%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 5         | 0.52%   |
| Intel Wireless 7265                                               | 5         | 0.52%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 5         | 0.52%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 237       | 61.24%  |
| Qualcomm Atheros                | 58        | 14.99%  |
| Realtek Semiconductor           | 44        | 11.37%  |
| Broadcom                        | 14        | 3.62%   |
| TP-Link                         | 5         | 1.29%   |
| Qualcomm Atheros Communications | 4         | 1.03%   |
| Dell                            | 4         | 1.03%   |
| Ralink Technology               | 3         | 0.78%   |
| Qualcomm                        | 3         | 0.78%   |
| Fibocom                         | 3         | 0.78%   |
| Ralink                          | 2         | 0.52%   |
| MediaTek                        | 2         | 0.52%   |
| D-Link System                   | 2         | 0.52%   |
| D-Link                          | 2         | 0.52%   |
| Texas Instruments               | 1         | 0.26%   |
| Sierra Wireless                 | 1         | 0.26%   |
| Quectel Wireless Solutions      | 1         | 0.26%   |
| Broadcom Limited                | 1         | 0.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 69        | 17.69%  |
| Intel Wireless 8265 / 8275                                     | 21        | 5.38%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 19        | 4.87%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 14        | 3.59%   |
| Intel Wi-Fi 6 AX201                                            | 14        | 3.59%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 14        | 3.59%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 11        | 2.82%   |
| Intel Wireless-AC 9260                                         | 9         | 2.31%   |
| Intel Wireless 8260                                            | 9         | 2.31%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 9         | 2.31%   |
| Intel Wireless 7260                                            | 8         | 2.05%   |
| Intel Wireless 3165                                            | 8         | 2.05%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 8         | 2.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 8         | 2.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 7         | 1.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 7         | 1.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 7         | 1.79%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 6         | 1.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 6         | 1.54%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 6         | 1.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 1.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 5         | 1.28%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 5         | 1.28%   |
| Intel Wireless 7265                                            | 5         | 1.28%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 5         | 1.28%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 4         | 1.03%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 4         | 1.03%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection       | 4         | 1.03%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 4         | 1.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 1.03%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 4         | 1.03%   |
| Ralink MT7601U Wireless Adapter                                | 3         | 0.77%   |
| Qualcomm QCA6390 Wireless Network Adapter                      | 3         | 0.77%   |
| Qualcomm Atheros AR9271 802.11n                                | 3         | 0.77%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 0.77%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 2         | 0.51%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 2         | 0.51%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 2         | 0.51%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.51%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 0.51%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 255       | 47.93%  |
| Intel                    | 199       | 37.41%  |
| Broadcom                 | 13        | 2.44%   |
| Qualcomm Atheros         | 11        | 2.07%   |
| ASIX Electronics         | 10        | 1.88%   |
| Lenovo                   | 9         | 1.69%   |
| Marvell Technology Group | 8         | 1.5%    |
| Aquantia                 | 7         | 1.32%   |
| Nvidia                   | 3         | 0.56%   |
| Xiaomi                   | 2         | 0.38%   |
| QLogic                   | 2         | 0.38%   |
| Broadcom Limited         | 2         | 0.38%   |
| Apple                    | 2         | 0.38%   |
| 3Com                     | 2         | 0.38%   |
| TP-Link                  | 1         | 0.19%   |
| Standard Microsystems    | 1         | 0.19%   |
| Microchip Technology     | 1         | 0.19%   |
| MediaTek                 | 1         | 0.19%   |
| Google                   | 1         | 0.19%   |
| Davicom Semiconductor    | 1         | 0.19%   |
| D-Link System            | 1         | 0.19%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 201       | 35.64%  |
| Intel I211 Gigabit Network Connection                             | 57        | 10.11%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 20        | 3.55%   |
| Realtek RTL8125 2.5GbE Controller                                 | 18        | 3.19%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 2.48%   |
| Intel I210 Gigabit Network Connection                             | 14        | 2.48%   |
| Intel Ethernet Connection (2) I219-V                              | 14        | 2.48%   |
| Intel Ethernet Controller I225-V                                  | 13        | 2.3%    |
| Intel Ethernet Connection (2) I219-LM                             | 12        | 2.13%   |
| Intel 82574L Gigabit Network Connection                           | 11        | 1.95%   |
| Intel Ethernet Connection (7) I219-V                              | 9         | 1.6%    |
| Intel I350 Gigabit Network Connection                             | 7         | 1.24%   |
| Intel Ethernet Connection (4) I219-V                              | 7         | 1.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 1.24%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 0.89%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 5         | 0.89%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 5         | 0.89%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4         | 0.71%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4         | 0.71%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 0.71%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.71%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 4         | 0.71%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3         | 0.53%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 0.53%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.53%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 3         | 0.53%   |
| Lenovo USB-C Dock Ethernet                                        | 3         | 0.53%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 3         | 0.53%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 0.53%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 0.53%   |
| Intel Ethernet Connection (10) I219-V                             | 3         | 0.53%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3         | 0.53%   |
| ASIX AX88772B Fast Ethernet Controller                            | 3         | 0.53%   |
| ASIX AX88772                                                      | 3         | 0.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.35%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.35%   |
| Nvidia MCP77 Ethernet                                             | 2         | 0.35%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 2         | 0.35%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                     | 2         | 0.35%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 481       | 55.8%   |
| WiFi     | 365       | 42.34%  |
| Modem    | 15        | 1.74%   |
| Unknown  | 1         | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 314       | 54.33%  |
| WiFi     | 264       | 45.67%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 268       | 47.6%   |
| 1     | 234       | 41.56%  |
| 3     | 30        | 5.33%   |
| 0     | 12        | 2.13%   |
| 4     | 9         | 1.6%    |
| 5     | 4         | 0.71%   |
| 6     | 3         | 0.53%   |
| 8     | 2         | 0.36%   |
| 9     | 1         | 0.18%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 501       | 88.52%  |
| Yes  | 65        | 11.48%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 220       | 62.68%  |
| Realtek Semiconductor           | 31        | 8.83%   |
| Cambridge Silicon Radio         | 28        | 7.98%   |
| Qualcomm Atheros Communications | 16        | 4.56%   |
| Lite-On Technology              | 11        | 3.13%   |
| Broadcom                        | 8         | 2.28%   |
| Apple                           | 7         | 1.99%   |
| ASUSTek Computer                | 6         | 1.71%   |
| IMC Networks                    | 5         | 1.42%   |
| Foxconn / Hon Hai               | 4         | 1.14%   |
| Toshiba                         | 3         | 0.85%   |
| Realtek                         | 3         | 0.85%   |
| Dell                            | 3         | 0.85%   |
| Hewlett-Packard                 | 2         | 0.57%   |
| Ralink Technology               | 1         | 0.28%   |
| HTC (High Tech Computer)        | 1         | 0.28%   |
| Chicony Electronics             | 1         | 0.28%   |
| Belkin Components               | 1         | 0.28%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                               | 74        | 21.08%  |
| Intel Bluetooth wireless interface                  | 49        | 13.96%  |
| Intel AX201 Bluetooth                               | 38        | 10.83%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 35        | 9.97%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 28        | 7.98%   |
| Realtek Bluetooth Radio                             | 19        | 5.41%   |
| Realtek  Bluetooth 4.2 Adapter                      | 9         | 2.56%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 9         | 2.56%   |
| Intel Wireless-AC 3168 Bluetooth                    | 8         | 2.28%   |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 1.42%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 5         | 1.42%   |
| Lite-On Bluetooth Device                            | 4         | 1.14%   |
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 1.14%   |
| Intel AX210 Bluetooth                               | 4         | 1.14%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 4         | 1.14%   |
| Realtek RTL8723B Bluetooth                          | 3         | 0.85%   |
| Realtek Bluetooth Radio                             | 3         | 0.85%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 0.85%   |
| Apple Bluetooth USB Host Controller                 | 3         | 0.85%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.57%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 0.57%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 0.57%   |
| IMC Networks Wireless_Device                        | 2         | 0.57%   |
| IMC Networks Bluetooth Radio                        | 2         | 0.57%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 0.57%   |
| Broadcom BCM920702 Bluetooth 4.0 Zero Touch Dongle  | 2         | 0.57%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 0.57%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 0.57%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 0.57%   |
| Apple Bluetooth Host Controller                     | 2         | 0.57%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.28%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)          | 1         | 0.28%   |
| Toshiba Atheros AR3012 Bluetooth                    | 1         | 0.28%   |
| Ralink CSR BS8510                                   | 1         | 0.28%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.28%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.28%   |
| Lite-On Bluetooth Radio                             | 1         | 0.28%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.28%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.28%   |
| Intel Bluetooth Device                              | 1         | 0.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 296       | 33.94%  |
| AMD                                  | 239       | 27.41%  |
| Nvidia                               | 171       | 19.61%  |
| C-Media Electronics                  | 27        | 3.1%    |
| Logitech                             | 14        | 1.61%   |
| Creative Labs                        | 11        | 1.26%   |
| Lenovo                               | 9         | 1.03%   |
| Texas Instruments                    | 7         | 0.8%    |
| Creative Technology                  | 7         | 0.8%    |
| Realtek Semiconductor                | 6         | 0.69%   |
| Razer USA                            | 6         | 0.69%   |
| Kingston Technology                  | 5         | 0.57%   |
| JMTek                                | 5         | 0.57%   |
| SteelSeries ApS                      | 4         | 0.46%   |
| Plantronics                          | 4         | 0.46%   |
| GYROCOM C&C                          | 4         | 0.46%   |
| Focusrite-Novation                   | 4         | 0.46%   |
| Blue Microphones                     | 4         | 0.46%   |
| BEHRINGER International              | 4         | 0.46%   |
| RODE Microphones                     | 3         | 0.34%   |
| Dell                                 | 3         | 0.34%   |
| ASUSTek Computer                     | 3         | 0.34%   |
| SAVITECH                             | 2         | 0.23%   |
| No brand                             | 2         | 0.23%   |
| GN Netcom                            | 2         | 0.23%   |
| FiiO Electronics Technology          | 2         | 0.23%   |
| AudioQuest                           | 2         | 0.23%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.11%   |
| Tdlasunnic                           | 1         | 0.11%   |
| Syntek                               | 1         | 0.11%   |
| Solid State Logic                    | 1         | 0.11%   |
| Sennheiser Communications            | 1         | 0.11%   |
| Samson Technologies                  | 1         | 0.11%   |
| QinHeng Electronics                  | 1         | 0.11%   |
| Nektar                               | 1         | 0.11%   |
| Microsoft                            | 1         | 0.11%   |
| Micronas                             | 1         | 0.11%   |
| LG Electronics                       | 1         | 0.11%   |
| JOUNIVO                              | 1         | 0.11%   |
| iCreate Technologies                 | 1         | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Starship/Matisse HD Audio Controller                            | 73        | 6.91%   |
| AMD Family 17h/19h HD Audio Controller                              | 63        | 5.96%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                 | 42        | 3.97%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]          | 41        | 3.88%   |
| Intel Cannon Lake PCH cAVS                                          | 38        | 3.6%    |
| Intel Sunrise Point-LP HD Audio                                     | 36        | 3.41%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 36        | 3.41%   |
| AMD Navi 10 HDMI Audio                                              | 25        | 2.37%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller      | 23        | 2.18%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 23        | 2.18%   |
| Intel Comet Lake PCH cAVS                                           | 17        | 1.61%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 17        | 1.61%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 16        | 1.51%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                          | 15        | 1.42%   |
| Nvidia TU106 High Definition Audio Controller                       | 14        | 1.32%   |
| AMD SBx00 Azalia (Intel HDA)                                        | 14        | 1.32%   |
| Nvidia GP107GL High Definition Audio Controller                     | 12        | 1.14%   |
| Intel Cannon Point-LP High Definition Audio Controller              | 12        | 1.14%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 12        | 1.14%   |
| Nvidia TU116 High Definition Audio Controller                       | 11        | 1.04%   |
| Nvidia TU104 HD Audio Controller                                    | 11        | 1.04%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                    | 11        | 1.04%   |
| Nvidia GP106 High Definition Audio Controller                       | 10        | 0.95%   |
| Nvidia GP104 High Definition Audio Controller                       | 10        | 0.95%   |
| Intel Comet Lake PCH-LP cAVS                                        | 10        | 0.95%   |
| Intel 200 Series PCH HD Audio                                       | 10        | 0.95%   |
| Nvidia GM206 High Definition Audio Controller                       | 9         | 0.85%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]       | 9         | 0.85%   |
| Nvidia GK208 HDMI/DP Audio Controller                               | 9         | 0.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 9         | 0.85%   |
| Intel Tiger Lake-H HD Audio Controller                              | 9         | 0.85%   |
| Intel Haswell-ULT HD Audio Controller                               | 9         | 0.85%   |
| Intel CM238 HD Audio Controller                                     | 9         | 0.85%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 9         | 0.85%   |
| Intel 8 Series HD Audio Controller                                  | 9         | 0.85%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]        | 9         | 0.85%   |
| Nvidia GA104 High Definition Audio Controller                       | 8         | 0.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller             | 8         | 0.76%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                             | 8         | 0.76%   |
| AMD FCH Azalia Controller                                           | 8         | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 108       | 18.18%  |
| Kingston            | 78        | 13.13%  |
| SK hynix            | 72        | 12.12%  |
| G.Skill             | 60        | 10.1%   |
| Unknown             | 55        | 9.26%   |
| Micron Technology   | 55        | 9.26%   |
| Crucial             | 54        | 9.09%   |
| Corsair             | 49        | 8.25%   |
| Ramaxel Technology  | 11        | 1.85%   |
| Team                | 6         | 1.01%   |
| Patriot             | 6         | 1.01%   |
| A-DATA Technology   | 6         | 1.01%   |
| Nanya Technology    | 5         | 0.84%   |
| Goodram             | 5         | 0.84%   |
| Transcend           | 4         | 0.67%   |
| Elpida              | 3         | 0.51%   |
| Unknown (ABCD)      | 2         | 0.34%   |
| AMD                 | 2         | 0.34%   |
| Teikon              | 1         | 0.17%   |
| T-FORCE             | 1         | 0.17%   |
| Kllisre             | 1         | 0.17%   |
| KLEVV               | 1         | 0.17%   |
| Kimtigo             | 1         | 0.17%   |
| Goldkey             | 1         | 0.17%   |
| Golden Empire       | 1         | 0.17%   |
| GeIL                | 1         | 0.17%   |
| Exceleram           | 1         | 0.17%   |
| Chun Well           | 1         | 0.17%   |
| A Force             | 1         | 0.17%   |
| 48spaces            | 1         | 0.17%   |
| Unknown             | 1         | 0.17%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 8         | 1.26%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s       | 7         | 1.1%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 6         | 0.95%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 6         | 0.95%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s        | 6         | 0.95%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s      | 6         | 0.95%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s        | 6         | 0.95%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s     | 5         | 0.79%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s      | 5         | 0.79%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s           | 5         | 0.79%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s      | 5         | 0.79%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s      | 4         | 0.63%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s       | 4         | 0.63%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 4         | 0.63%   |
| Unknown RAM Module 512MB DIMM SDRAM                         | 3         | 0.47%   |
| Unknown RAM Module 1GB SODIMM DDR                           | 3         | 0.47%   |
| Unknown RAM Module 1024MB DIMM SDRAM                        | 3         | 0.47%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s             | 3         | 0.47%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s      | 3         | 0.47%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 3         | 0.47%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s       | 3         | 0.47%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 3         | 0.47%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s       | 3         | 0.47%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s       | 3         | 0.47%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 3         | 0.47%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s       | 3         | 0.47%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s        | 3         | 0.47%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s | 3         | 0.47%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s       | 3         | 0.47%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s      | 3         | 0.47%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s         | 3         | 0.47%   |
| Kingston RAM KHX2666C15D4/8G 8GB DIMM DDR4 3200MT/s         | 3         | 0.47%   |
| Kingston RAM 9965745-002.A00G 16GB DIMM DDR4 3000MT/s       | 3         | 0.47%   |
| Kingston RAM 9905744-066.A00G 32GB SODIMM DDR4 3200MT/s     | 3         | 0.47%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s      | 3         | 0.47%   |
| G.Skill RAM F4-3200C16-16GTZ 16GB DIMM DDR4 3200MT/s        | 3         | 0.47%   |
| G.Skill RAM F4-3200C14-8GTZ 8GB DIMM DDR4 3733MT/s          | 3         | 0.47%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s         | 3         | 0.47%   |
| Crucial RAM CT8G4DFS824A.C8FE 8GB DIMM DDR4 3000MT/s        | 3         | 0.47%   |
| Crucial RAM CT4G4DFS8213.C8FAD11 4GB DIMM DDR4 2133MT/s     | 3         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 354       | 67.17%  |
| DDR3    | 99        | 18.79%  |
| LPDDR4  | 18        | 3.42%   |
| DDR2    | 18        | 3.42%   |
| Unknown | 13        | 2.47%   |
| LPDDR3  | 9         | 1.71%   |
| SDRAM   | 8         | 1.52%   |
| DDR     | 6         | 1.14%   |
| DRAM    | 1         | 0.19%   |
| DDR5    | 1         | 0.19%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 268       | 51.15%  |
| SODIMM       | 226       | 43.13%  |
| Row Of Chips | 28        | 5.34%   |
| RIMM         | 1         | 0.19%   |
| Chip         | 1         | 0.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 225       | 39.75%  |
| 16384 | 152       | 26.86%  |
| 4096  | 95        | 16.78%  |
| 32768 | 40        | 7.07%   |
| 2048  | 36        | 6.36%   |
| 1024  | 13        | 2.3%    |
| 512   | 3         | 0.53%   |
| 256   | 2         | 0.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 103       | 18.07%  |
| 2667    | 89        | 15.61%  |
| 1600    | 67        | 11.75%  |
| 2400    | 47        | 8.25%   |
| 3600    | 39        | 6.84%   |
| 2133    | 29        | 5.09%   |
| 1333    | 21        | 3.68%   |
| 3000    | 17        | 2.98%   |
| 3733    | 14        | 2.46%   |
| 667     | 14        | 2.46%   |
| 800     | 12        | 2.11%   |
| 4267    | 11        | 1.93%   |
| 2933    | 11        | 1.93%   |
| Unknown | 11        | 1.93%   |
| 3400    | 9         | 1.58%   |
| 1867    | 8         | 1.4%    |
| 3466    | 7         | 1.23%   |
| 3266    | 7         | 1.23%   |
| 2666    | 7         | 1.23%   |
| 1066    | 6         | 1.05%   |
| 3866    | 4         | 0.7%    |
| 3800    | 4         | 0.7%    |
| 400     | 4         | 0.7%    |
| 3333    | 3         | 0.53%   |
| 3100    | 3         | 0.53%   |
| 4800    | 2         | 0.35%   |
| 4266    | 2         | 0.35%   |
| 4000    | 2         | 0.35%   |
| 3066    | 2         | 0.35%   |
| 2465    | 2         | 0.35%   |
| 1866    | 2         | 0.35%   |
| 1067    | 2         | 0.35%   |
| 8400    | 1         | 0.18%   |
| 4199    | 1         | 0.18%   |
| 3666    | 1         | 0.18%   |
| 3467    | 1         | 0.18%   |
| 2800    | 1         | 0.18%   |
| 2134    | 1         | 0.18%   |
| 1800    | 1         | 0.18%   |
| 1334    | 1         | 0.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 5         | 55.56%  |
| Xiaomi             | 1         | 11.11%  |
| Seiko Epson        | 1         | 11.11%  |
| Konica Minolta     | 1         | 11.11%  |
| Brother Industries | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Xiaomi MiMouse 2                     | 1         | 11.11%  |
| Seiko Epson AL-M310DN                | 1         | 11.11%  |
| Konica Minolta magicolor 1680MF scan | 1         | 11.11%  |
| HP PhotoSmart 130                    | 1         | 11.11%  |
| HP LaserJet M14-M17                  | 1         | 11.11%  |
| HP LaserJet 1020                     | 1         | 11.11%  |
| HP LaserJet 1018                     | 1         | 11.11%  |
| HP LaserJet 1010                     | 1         | 11.11%  |
| Brother MFC-9130CW                   | 1         | 11.11%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 3         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 33.33%  |
| Canon CanoScan LiDE 600F      | 1         | 33.33%  |
| Canon CanoScan LiDE 110       | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 61        | 20.07%  |
| Logitech                               | 53        | 17.43%  |
| IMC Networks                           | 36        | 11.84%  |
| Microdia                               | 25        | 8.22%   |
| Realtek Semiconductor                  | 23        | 7.57%   |
| Acer                                   | 19        | 6.25%   |
| Lite-On Technology                     | 11        | 3.62%   |
| Sunplus Innovation Technology          | 10        | 3.29%   |
| Quanta                                 | 9         | 2.96%   |
| Syntek                                 | 8         | 2.63%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 2.63%   |
| Z-Star Microelectronics                | 6         | 1.97%   |
| Samsung Electronics                    | 5         | 1.64%   |
| Luxvisions Innotech Limited            | 5         | 1.64%   |
| ARC International                      | 3         | 0.99%   |
| Microsoft                              | 2         | 0.66%   |
| MacroSilicon                           | 2         | 0.66%   |
| DigiTech                               | 2         | 0.66%   |
| Apple                                  | 2         | 0.66%   |
| Silicon Motion                         | 1         | 0.33%   |
| Razer USA                              | 1         | 0.33%   |
| Omnivision                             | 1         | 0.33%   |
| LG Electronics                         | 1         | 0.33%   |
| Lenovo                                 | 1         | 0.33%   |
| KYE Systems (Mouse Systems)            | 1         | 0.33%   |
| Hewlett-Packard                        | 1         | 0.33%   |
| HD 2MP WEBCAM                          | 1         | 0.33%   |
| Genesys Logic                          | 1         | 0.33%   |
| Creative Technology                    | 1         | 0.33%   |
| AVerMedia Technologies                 | 1         | 0.33%   |
| AVer Information                       | 1         | 0.33%   |
| Alcor Micro                            | 1         | 0.33%   |
| A4Tech                                 | 1         | 0.33%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 20        | 6.51%   |
| IMC Networks Integrated Camera                      | 18        | 5.86%   |
| Microdia Integrated_Webcam_HD                       | 17        | 5.54%   |
| Logitech HD Pro Webcam C920                         | 15        | 4.89%   |
| Realtek Integrated_Webcam_HD                        | 11        | 3.58%   |
| Acer Integrated Camera                              | 11        | 3.58%   |
| Logitech Webcam C270                                | 9         | 2.93%   |
| Chicony HD Webcam                                   | 7         | 2.28%   |
| Chicony HP HD Camera                                | 6         | 1.95%   |
| Syntek Integrated Camera                            | 5         | 1.63%   |
| Samsung Galaxy A5 (MTP)                             | 5         | 1.63%   |
| Lite-On Integrated Camera                           | 5         | 1.63%   |
| Z-Star Venus USB2.0 Camera                          | 4         | 1.3%    |
| Sunplus Integrated_Webcam_HD                        | 4         | 1.3%    |
| Logitech Webcam C310                                | 4         | 1.3%    |
| Logitech C922 Pro Stream Webcam                     | 4         | 1.3%    |
| IMC Networks USB2.0 HD UVC WebCam                   | 4         | 1.3%    |
| Chicony USB2.0 Camera                               | 4         | 1.3%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 4         | 1.3%    |
| Quanta HP Wide Vision HD Camera                     | 3         | 0.98%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 3         | 0.98%   |
| ARC International Camera                            | 3         | 0.98%   |
| Sunplus HD WebCam                                   | 2         | 0.65%   |
| Realtek USB2.0 HD UVC WebCam                        | 2         | 0.65%   |
| Realtek USB Camera                                  | 2         | 0.65%   |
| Realtek Integrated Webcam                           | 2         | 0.65%   |
| Quanta VGA WebCam                                   | 2         | 0.65%   |
| Microdia USB 2.0 Camera                             | 2         | 0.65%   |
| MacroSilicon USB Video                              | 2         | 0.65%   |
| Luxvisions Innotech Limited HP HD Camera            | 2         | 0.65%   |
| Logitech Webcam C925e                               | 2         | 0.65%   |
| Logitech Webcam C200                                | 2         | 0.65%   |
| Logitech HD Webcam C615                             | 2         | 0.65%   |
| Logitech C920 PRO HD Webcam                         | 2         | 0.65%   |
| Logitech B525 HD Webcam                             | 2         | 0.65%   |
| Lite-On TOSHIBA Web Camera - HD                     | 2         | 0.65%   |
| Lite-On HP Wide Vision HD Camera                    | 2         | 0.65%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 2         | 0.65%   |
| IMC Networks USB Camera                             | 2         | 0.65%   |
| IMC Networks ov9734_azurewave_camera                | 2         | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 34        | 56.67%  |
| Shenzhen Goodix Technology | 11        | 18.33%  |
| Validity Sensors           | 7         | 11.67%  |
| Elan Microelectronics      | 3         | 5%      |
| STMicroelectronics         | 2         | 3.33%   |
| Upek                       | 1         | 1.67%   |
| LighTuning Technology      | 1         | 1.67%   |
| AuthenTec                  | 1         | 1.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 16        | 26.67%  |
| Unknown                                                    | 8         | 13.33%  |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 5         | 8.33%   |
| Shenzhen Goodix Fingerprint Reader                         | 4         | 6.67%   |
| Shenzhen Goodix FingerPrint                                | 4         | 6.67%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 3         | 5%      |
| Shenzhen Goodix  Fingerprint Device                        | 3         | 5%      |
| Validity Sensors VFS5011 Fingerprint Reader                | 2         | 3.33%   |
| Validity Sensors Synaptics WBDI                            | 2         | 3.33%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 2         | 3.33%   |
| STMicroelectronics Fingerprint Reader                      | 2         | 3.33%   |
| Elan ELAN:Fingerprint                                      | 2         | 3.33%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 1         | 1.67%   |
| Synaptics  WBDI                                            | 1         | 1.67%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.67%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 1.67%   |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 1         | 1.67%   |
| Elan ELAN:ARM-M4                                           | 1         | 1.67%   |
| AuthenTec AES2501 Fingerprint Sensor                       | 1         | 1.67%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Alcor Micro                       | 20        | 51.28%  |
| Broadcom                          | 11        | 28.21%  |
| Upek                              | 2         | 5.13%   |
| Clay Logic                        | 2         | 5.13%   |
| VASCO Data Security International | 1         | 2.56%   |
| Purism, SPC                       | 1         | 2.56%   |
| Microchip Technology              | 1         | 2.56%   |
| Aktiv                             | 1         | 2.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 20        | 51.28%  |
| Broadcom 5880                                                                | 5         | 12.82%  |
| Broadcom 58200                                                               | 4         | 10.26%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 5.13%   |
| Clay Logic Nitrokey Pro                                                      | 2         | 5.13%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 2.56%   |
| Purism, SPC Librem Key                                                       | 1         | 2.56%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 2.56%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 2.56%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 2.56%   |
| Aktiv Rutoken lite                                                           | 1         | 2.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 279       | 46.89%  |
| 1     | 174       | 29.24%  |
| 2     | 65        | 10.92%  |
| 3     | 38        | 6.39%   |
| 4     | 25        | 4.2%    |
| 5     | 9         | 1.51%   |
| 6     | 4         | 0.67%   |
| 7     | 1         | 0.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 99        | 17.58%  |
| Bluetooth                | 79        | 14.03%  |
| Fingerprint reader       | 60        | 10.66%  |
| Camera                   | 59        | 10.48%  |
| Graphics card            | 55        | 9.77%   |
| Net/wireless             | 39        | 6.93%   |
| Chipcard                 | 30        | 5.33%   |
| Multimedia controller    | 28        | 4.97%   |
| Sound                    | 26        | 4.62%   |
| Card reader              | 25        | 4.44%   |
| Firewire controller      | 13        | 2.31%   |
| Net/ethernet             | 9         | 1.6%    |
| Network                  | 8         | 1.42%   |
| Modem                    | 7         | 1.24%   |
| Storage/ata              | 6         | 1.07%   |
| Unassigned class         | 5         | 0.89%   |
| Dvb card                 | 4         | 0.71%   |
| Storage/raid             | 3         | 0.53%   |
| Storage/ide              | 3         | 0.53%   |
| Tv card                  | 2         | 0.36%   |
| Wireless                 | 1         | 0.18%   |
| Storage/nvme             | 1         | 0.18%   |
| Storage                  | 1         | 0.18%   |

