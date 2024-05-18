Linux in Hong Kong - Tested Hardware & Statistics (Desktops)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Hong Kong.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 302

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Huanan        | X99-TF                      | [804eb7916a](https://linux-hardware.org/?probe=804eb7916a) | May 05, 2024 |
| HP            | 2B2C                        | [082d220d35](https://linux-hardware.org/?probe=082d220d35) | May 04, 2024 |
| HP            | 158B                        | [38acb31ca9](https://linux-hardware.org/?probe=38acb31ca9) | Apr 24, 2024 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [ba12ac8498](https://linux-hardware.org/?probe=ba12ac8498) | Apr 17, 2024 |
| HP            | 158B                        | [d7c58cf079](https://linux-hardware.org/?probe=d7c58cf079) | Apr 09, 2024 |
| TSINGHUA T... | B560M-J01 V0.2              | [85ca1b62a7](https://linux-hardware.org/?probe=85ca1b62a7) | Apr 09, 2024 |
| Dell          | 02J54D A01                  | [28dc6c5c06](https://linux-hardware.org/?probe=28dc6c5c06) | Apr 01, 2024 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [b4b14726e3](https://linux-hardware.org/?probe=b4b14726e3) | Mar 23, 2024 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [2b17261b3a](https://linux-hardware.org/?probe=2b17261b3a) | Mar 23, 2024 |
| Gigabyte      | B360HD3                     | [a82720d3a4](https://linux-hardware.org/?probe=a82720d3a4) | Mar 18, 2024 |
| MSI           | MPG X570 GAMING PRO CARB... | [ec5e2c689a](https://linux-hardware.org/?probe=ec5e2c689a) | Mar 13, 2024 |
| Huanan        | X99-TF                      | [edb2ac80c9](https://linux-hardware.org/?probe=edb2ac80c9) | Mar 04, 2024 |
| MSI           | MEG Z790 ACE                | [0137944d6c](https://linux-hardware.org/?probe=0137944d6c) | Feb 22, 2024 |
| Unknown       | Unknown                     | [aa24b40efa](https://linux-hardware.org/?probe=aa24b40efa) | Feb 19, 2024 |
| Unknown       | Unknown                     | [e9ad690ec9](https://linux-hardware.org/?probe=e9ad690ec9) | Feb 19, 2024 |
| ASUSTek       | Rampage II Extreme          | [42f4db38c2](https://linux-hardware.org/?probe=42f4db38c2) | Feb 16, 2024 |
| Unknown       | Unknown                     | [255d81b8e9](https://linux-hardware.org/?probe=255d81b8e9) | Feb 15, 2024 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [140a2db49b](https://linux-hardware.org/?probe=140a2db49b) | Feb 03, 2024 |
| ASRock        | X300-ITX                    | [3390b15018](https://linux-hardware.org/?probe=3390b15018) | Feb 02, 2024 |
| HP            | 8B3C A                      | [12ec418267](https://linux-hardware.org/?probe=12ec418267) | Jan 31, 2024 |
| MSI           | MAG B550M BAZOOKA           | [c0d98503dd](https://linux-hardware.org/?probe=c0d98503dd) | Jan 29, 2024 |
| Unknown       | Unknown                     | [2bf1eac05d](https://linux-hardware.org/?probe=2bf1eac05d) | Jan 27, 2024 |
| ASRock        | B650M PG Riptide            | [1ebf8a3fea](https://linux-hardware.org/?probe=1ebf8a3fea) | Jan 21, 2024 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [53b28fea12](https://linux-hardware.org/?probe=53b28fea12) | Jan 21, 2024 |
| Unknown       | Unknown                     | [413fbae0c9](https://linux-hardware.org/?probe=413fbae0c9) | Jan 17, 2024 |
| Unknown       | Unknown                     | [69d393fc55](https://linux-hardware.org/?probe=69d393fc55) | Jan 17, 2024 |
| AZW           | GTR V21                     | [c87cc08a52](https://linux-hardware.org/?probe=c87cc08a52) | Jan 15, 2024 |
| Gigabyte      | G41M-Combo                  | [e34d332260](https://linux-hardware.org/?probe=e34d332260) | Jan 10, 2024 |
| Dell          | 0VNM11 A00                  | [060cdd6c04](https://linux-hardware.org/?probe=060cdd6c04) | Jan 04, 2024 |
| MSI           | B450M MORTAR MAX            | [0c20bdae04](https://linux-hardware.org/?probe=0c20bdae04) | Dec 31, 2023 |
| MSI           | B450M MORTAR MAX            | [d6622a2c0a](https://linux-hardware.org/?probe=d6622a2c0a) | Dec 31, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [0daa9bd3eb](https://linux-hardware.org/?probe=0daa9bd3eb) | Dec 29, 2023 |
| Dell          | 0PJDGF A02                  | [cfdd125cd5](https://linux-hardware.org/?probe=cfdd125cd5) | Dec 19, 2023 |
| Dell          | 0PJDGF A02                  | [edcd06b95f](https://linux-hardware.org/?probe=edcd06b95f) | Dec 19, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [c6fa46e494](https://linux-hardware.org/?probe=c6fa46e494) | Dec 17, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [ebfb65701f](https://linux-hardware.org/?probe=ebfb65701f) | Dec 14, 2023 |
| Huanan        | X99-TF                      | [2bf94ff272](https://linux-hardware.org/?probe=2bf94ff272) | Dec 13, 2023 |
| Gigabyte      | B85M-DS3H-A                 | [c4de324273](https://linux-hardware.org/?probe=c4de324273) | Dec 12, 2023 |
| Huanan        | X99-TF                      | [c617461c74](https://linux-hardware.org/?probe=c617461c74) | Dec 03, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [940148ec06](https://linux-hardware.org/?probe=940148ec06) | Dec 01, 2023 |
| Intel         | SKYBAY                      | [f802b552c5](https://linux-hardware.org/?probe=f802b552c5) | Nov 29, 2023 |
| Intel         | SKYBAY                      | [914eab8268](https://linux-hardware.org/?probe=914eab8268) | Nov 28, 2023 |
| Intel         | SKYBAY                      | [3e3de1a647](https://linux-hardware.org/?probe=3e3de1a647) | Nov 27, 2023 |
| Intel         | SKYBAY                      | [9d55b4f75f](https://linux-hardware.org/?probe=9d55b4f75f) | Nov 27, 2023 |
| Unknown       | Unknown                     | [3ccba31903](https://linux-hardware.org/?probe=3ccba31903) | Nov 27, 2023 |
| Intel         | SKYBAY                      | [21f1b67acc](https://linux-hardware.org/?probe=21f1b67acc) | Nov 24, 2023 |
| Unknown       | Unknown                     | [47bf46db9d](https://linux-hardware.org/?probe=47bf46db9d) | Nov 24, 2023 |
| Unknown       | Unknown                     | [e62a5fc1bc](https://linux-hardware.org/?probe=e62a5fc1bc) | Nov 24, 2023 |
| Intel         | SKYBAY                      | [03d84cbd00](https://linux-hardware.org/?probe=03d84cbd00) | Nov 24, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [bdbde84396](https://linux-hardware.org/?probe=bdbde84396) | Nov 18, 2023 |
| HPE           | ProLiant MicroServer Gen... | [7461a3b207](https://linux-hardware.org/?probe=7461a3b207) | Nov 08, 2023 |
| Unknown       | Unknown                     | [5c2d84d61d](https://linux-hardware.org/?probe=5c2d84d61d) | Nov 06, 2023 |
| Unknown       | Unknown                     | [e84ce1e0d3](https://linux-hardware.org/?probe=e84ce1e0d3) | Nov 06, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [37aa104ebf](https://linux-hardware.org/?probe=37aa104ebf) | Nov 06, 2023 |
| Intel         | X79 V1.0                    | [9483a097a1](https://linux-hardware.org/?probe=9483a097a1) | Nov 03, 2023 |
| Acer          | Nitro N50-600 V:1.1         | [b2c5bb3ed9](https://linux-hardware.org/?probe=b2c5bb3ed9) | Nov 02, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [650d69cdce](https://linux-hardware.org/?probe=650d69cdce) | Oct 31, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [6e87d140be](https://linux-hardware.org/?probe=6e87d140be) | Oct 25, 2023 |
| MSI           | PRO B760M-P DDR4            | [23f0d88b97](https://linux-hardware.org/?probe=23f0d88b97) | Oct 20, 2023 |
| Gigabyte      | B150M-HD3-CF                | [6f431b83bd](https://linux-hardware.org/?probe=6f431b83bd) | Oct 08, 2023 |
| Gigabyte      | B150M-HD3-CF                | [e524ccbf1b](https://linux-hardware.org/?probe=e524ccbf1b) | Oct 07, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | [ca79f8ce4c](https://linux-hardware.org/?probe=ca79f8ce4c) | Oct 04, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | [f4f3555c2b](https://linux-hardware.org/?probe=f4f3555c2b) | Oct 03, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | [9b86a89bf4](https://linux-hardware.org/?probe=9b86a89bf4) | Sep 29, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [08989d4bba](https://linux-hardware.org/?probe=08989d4bba) | Sep 21, 2023 |
| Gigabyte      | B85M-DS3H-A                 | [6d0e6a863d](https://linux-hardware.org/?probe=6d0e6a863d) | Sep 21, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [07d34fd9b5](https://linux-hardware.org/?probe=07d34fd9b5) | Sep 18, 2023 |
| Gigabyte      | H55N-USB3                   | [afefe4b055](https://linux-hardware.org/?probe=afefe4b055) | Sep 18, 2023 |
| Shenzhen M... | HX90G                       | [fda84a9c7c](https://linux-hardware.org/?probe=fda84a9c7c) | Sep 10, 2023 |
| Dell          | 0VNM11 A00                  | [e448e177d3](https://linux-hardware.org/?probe=e448e177d3) | Aug 21, 2023 |
| ASRock        | Q1900-ITX                   | [2c60ec2f95](https://linux-hardware.org/?probe=2c60ec2f95) | Aug 17, 2023 |
| ASRock        | Q1900-ITX                   | [b4a64727f4](https://linux-hardware.org/?probe=b4a64727f4) | Aug 14, 2023 |
| Dell          | 0VNM11 A00                  | [71cd1ddbf5](https://linux-hardware.org/?probe=71cd1ddbf5) | Aug 13, 2023 |
| ASRock        | 970 Extreme3 R2.0           | [cf233e5568](https://linux-hardware.org/?probe=cf233e5568) | Aug 13, 2023 |
| ASRock        | X300M-STX                   | [e43da17360](https://linux-hardware.org/?probe=e43da17360) | Jul 29, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [8c8e7f5edd](https://linux-hardware.org/?probe=8c8e7f5edd) | Jul 26, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c5475d0982](https://linux-hardware.org/?probe=c5475d0982) | Jul 18, 2023 |
| MSI           | B250M PRO-VDH               | [5b085b711b](https://linux-hardware.org/?probe=5b085b711b) | Jul 06, 2023 |
| Gigabyte      | B760M AORUS ELITE AX        | [8a5ddbbafc](https://linux-hardware.org/?probe=8a5ddbbafc) | Jul 05, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [a57586f69b](https://linux-hardware.org/?probe=a57586f69b) | Jul 01, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | [3f9d0da410](https://linux-hardware.org/?probe=3f9d0da410) | Jun 28, 2023 |
| BESSTAR Te... | B550                        | [87962635d3](https://linux-hardware.org/?probe=87962635d3) | Jun 26, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [8a9a60ca4d](https://linux-hardware.org/?probe=8a9a60ca4d) | Jun 19, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [eaca61c801](https://linux-hardware.org/?probe=eaca61c801) | Jun 19, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [c536181b6a](https://linux-hardware.org/?probe=c536181b6a) | Jun 14, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [8d783c6b00](https://linux-hardware.org/?probe=8d783c6b00) | Jun 03, 2023 |
| HP            | 83E2                        | [eaf5f90360](https://linux-hardware.org/?probe=eaf5f90360) | Jun 01, 2023 |
| HP            | 1632                        | [ed47689eec](https://linux-hardware.org/?probe=ed47689eec) | May 22, 2023 |
| Dell          | 0N0992 A01                  | [a8e8000610](https://linux-hardware.org/?probe=a8e8000610) | Apr 24, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [59f6a81039](https://linux-hardware.org/?probe=59f6a81039) | Apr 17, 2023 |
| Gigabyte      | X570S AERO G                | [30e0bd8317](https://linux-hardware.org/?probe=30e0bd8317) | Apr 02, 2023 |
| MSI           | B450 TOMAHAWK               | [4757b31751](https://linux-hardware.org/?probe=4757b31751) | Mar 19, 2023 |
| ASUSTek       | P8H61-M LX PLUS             | [cdf57a039e](https://linux-hardware.org/?probe=cdf57a039e) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [27356d58d5](https://linux-hardware.org/?probe=27356d58d5) | Mar 17, 2023 |
| MSI           | MPG Z690 EDGE TI WIFI DD... | [b42850eb13](https://linux-hardware.org/?probe=b42850eb13) | Mar 17, 2023 |
| ASUSTek       | PRIME H610M-K D4            | [601836815c](https://linux-hardware.org/?probe=601836815c) | Feb 22, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | [c1936488f5](https://linux-hardware.org/?probe=c1936488f5) | Feb 20, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [ee4e2b3cde](https://linux-hardware.org/?probe=ee4e2b3cde) | Feb 19, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [81c1e35182](https://linux-hardware.org/?probe=81c1e35182) | Jan 24, 2023 |
| Gigabyte      | H97N-WIFI                   | [a18f404d39](https://linux-hardware.org/?probe=a18f404d39) | Jan 17, 2023 |
| ASUSTek       | M4A78                       | [4ce5e1fd02](https://linux-hardware.org/?probe=4ce5e1fd02) | Jan 14, 2023 |
| ASUSTek       | M4A78                       | [09560460b9](https://linux-hardware.org/?probe=09560460b9) | Jan 14, 2023 |
| Dell          | 042P49 A02                  | [dc81fac0f7](https://linux-hardware.org/?probe=dc81fac0f7) | Jan 04, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [ecf944f539](https://linux-hardware.org/?probe=ecf944f539) | Dec 31, 2022 |
| ASUSTek       | PRIME H610M-K D4            | [0031785936](https://linux-hardware.org/?probe=0031785936) | Dec 31, 2022 |
| ASUSTek       | PRIME H610M-K D4            | [4bd2096c80](https://linux-hardware.org/?probe=4bd2096c80) | Dec 31, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [7b3c89637b](https://linux-hardware.org/?probe=7b3c89637b) | Dec 30, 2022 |
| Lenovo        | 3753 SDK0T76479 WIN 3423... | [5476b73cb7](https://linux-hardware.org/?probe=5476b73cb7) | Dec 02, 2022 |
| Lenovo        | 3753 SDK0T76479 WIN 3423... | [6d07106192](https://linux-hardware.org/?probe=6d07106192) | Dec 02, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [895a345eb9](https://linux-hardware.org/?probe=895a345eb9) | Nov 02, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [9d9d3a4967](https://linux-hardware.org/?probe=9d9d3a4967) | Nov 02, 2022 |
| MSI           | MAG B660M MORTAR WIFI DD... | [115e9027d0](https://linux-hardware.org/?probe=115e9027d0) | Nov 01, 2022 |
| ASRock        | H470M-STX                   | [02f3177542](https://linux-hardware.org/?probe=02f3177542) | Oct 26, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [ce7a9a3171](https://linux-hardware.org/?probe=ce7a9a3171) | Oct 23, 2022 |
| Lenovo        | SHARKBAY NOK                | [153aaa07cd](https://linux-hardware.org/?probe=153aaa07cd) | Oct 23, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [f20c990c1f](https://linux-hardware.org/?probe=f20c990c1f) | Oct 12, 2022 |
| ASRock        | AB350M Pro4                 | [6207d55486](https://linux-hardware.org/?probe=6207d55486) | Oct 05, 2022 |
| MSI           | B75MA-E33                   | [a14df6d116](https://linux-hardware.org/?probe=a14df6d116) | Oct 02, 2022 |
| HP            | 18E7                        | [132a87f746](https://linux-hardware.org/?probe=132a87f746) | Sep 28, 2022 |
| ASUSTek       | PRIME B660M-K D4            | [e939330716](https://linux-hardware.org/?probe=e939330716) | Sep 25, 2022 |
| Unknown       | Apple iPad Pro (9.7-inch... | [822d20fcdb](https://linux-hardware.org/?probe=822d20fcdb) | Sep 25, 2022 |
| Unknown       | Apple iPad Pro (9.7-inch... | [92f244ac1c](https://linux-hardware.org/?probe=92f244ac1c) | Sep 25, 2022 |
| MSI           | H81M-P33                    | [7e4f539e70](https://linux-hardware.org/?probe=7e4f539e70) | Sep 24, 2022 |
| MSI           | H81M-P33                    | [64cd74457e](https://linux-hardware.org/?probe=64cd74457e) | Sep 24, 2022 |
| ASRock        | H97M Anniversary            | [289532b8bb](https://linux-hardware.org/?probe=289532b8bb) | Sep 24, 2022 |
| ASRock        | Z490 PG Velocita            | [eac045585b](https://linux-hardware.org/?probe=eac045585b) | Sep 23, 2022 |
| Huanan        | X99-TF                      | [657d78e891](https://linux-hardware.org/?probe=657d78e891) | Sep 21, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [331a481ab0](https://linux-hardware.org/?probe=331a481ab0) | Sep 14, 2022 |
| Dell          | 0427JK A00                  | [8f6a2c8d0b](https://linux-hardware.org/?probe=8f6a2c8d0b) | Aug 22, 2022 |
| Dell          | 0200DY A03                  | [e0e14cd1f2](https://linux-hardware.org/?probe=e0e14cd1f2) | Aug 19, 2022 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | [58b22885a8](https://linux-hardware.org/?probe=58b22885a8) | Aug 18, 2022 |
| ASUSTek       | PRIME Z590M-PLUS            | [bd7c6f361d](https://linux-hardware.org/?probe=bd7c6f361d) | Aug 18, 2022 |
| MSI           | MAG B660M MORTAR WIFI DD... | [56ba58f5d0](https://linux-hardware.org/?probe=56ba58f5d0) | Aug 16, 2022 |
| ASRock        | B450M-HDV R4.0              | [f2172999c8](https://linux-hardware.org/?probe=f2172999c8) | Jul 24, 2022 |
| Huanan        | X99-TF                      | [55b43de5a6](https://linux-hardware.org/?probe=55b43de5a6) | Jul 17, 2022 |
| Soyo          | SY-A68M FS V2.0             | [ab243c130a](https://linux-hardware.org/?probe=ab243c130a) | Jul 06, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [518331cc83](https://linux-hardware.org/?probe=518331cc83) | Jun 21, 2022 |
| Huanan        | X99-TF                      | [04dc5246af](https://linux-hardware.org/?probe=04dc5246af) | Jun 18, 2022 |
| Lenovo        | 3715 SDK0L77769 WIN 3423... | [16d122d03e](https://linux-hardware.org/?probe=16d122d03e) | Jun 16, 2022 |
| Huanan        | X99-TF                      | [4e5364e832](https://linux-hardware.org/?probe=4e5364e832) | Jun 08, 2022 |
| Gigabyte      | HA65M-UD3H-B3               | [d368918a0b](https://linux-hardware.org/?probe=d368918a0b) | May 13, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [e45fa22892](https://linux-hardware.org/?probe=e45fa22892) | May 11, 2022 |
| Gigabyte      | GA-880GMA-UD2H              | [09d9f58ee7](https://linux-hardware.org/?probe=09d9f58ee7) | May 02, 2022 |
| MSI           | H87I                        | [af4a26a5ea](https://linux-hardware.org/?probe=af4a26a5ea) | Apr 30, 2022 |
| Gigabyte      | B660M DS3H AX DDR4          | [0633ac7757](https://linux-hardware.org/?probe=0633ac7757) | Apr 26, 2022 |
| Gigabyte      | B660M DS3H AX DDR4          | [56902c7998](https://linux-hardware.org/?probe=56902c7998) | Apr 26, 2022 |
| Gigabyte      | B660M DS3H AX DDR4          | [abed3ae34d](https://linux-hardware.org/?probe=abed3ae34d) | Apr 12, 2022 |
| ASUSTek       | VM62                        | [ae684cdf71](https://linux-hardware.org/?probe=ae684cdf71) | Apr 05, 2022 |
| ASRock        | H410M-ITX/ac                | [ae936790c9](https://linux-hardware.org/?probe=ae936790c9) | Apr 03, 2022 |
| MSI           | MAG B550M MORTAR            | [9ebb4c0fd3](https://linux-hardware.org/?probe=9ebb4c0fd3) | Mar 31, 2022 |
| Dell          | 0Y3R3K A03                  | [b772cf9d86](https://linux-hardware.org/?probe=b772cf9d86) | Mar 26, 2022 |
| ASUSTek       | PRIME Z590-A                | [7320ed668a](https://linux-hardware.org/?probe=7320ed668a) | Mar 12, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [99d3e16ede](https://linux-hardware.org/?probe=99d3e16ede) | Mar 12, 2022 |
| Unknown       | Intel X79                   | [e947d6af7f](https://linux-hardware.org/?probe=e947d6af7f) | Mar 11, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [4d16610cf3](https://linux-hardware.org/?probe=4d16610cf3) | Mar 10, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [4b2fe6657c](https://linux-hardware.org/?probe=4b2fe6657c) | Mar 04, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [0b9a7acb84](https://linux-hardware.org/?probe=0b9a7acb84) | Feb 27, 2022 |
| MSI           | B75MA-P45                   | [35ad54efc7](https://linux-hardware.org/?probe=35ad54efc7) | Feb 26, 2022 |
| Dell          | 0Y5DDC A00                  | [3c7daed552](https://linux-hardware.org/?probe=3c7daed552) | Feb 22, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [6e5689a733](https://linux-hardware.org/?probe=6e5689a733) | Jan 28, 2022 |
| ASRock        | Z270M-ITX/ac                | [4c32bf6d7b](https://linux-hardware.org/?probe=4c32bf6d7b) | Jan 18, 2022 |
| HP            | 8597                        | [09ed815dd0](https://linux-hardware.org/?probe=09ed815dd0) | Jan 08, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [83ff6966e1](https://linux-hardware.org/?probe=83ff6966e1) | Dec 24, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [c5fa4a0cec](https://linux-hardware.org/?probe=c5fa4a0cec) | Dec 24, 2021 |
| ASRock        | H410M-ITX/ac                | [99c341562a](https://linux-hardware.org/?probe=99c341562a) | Dec 21, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [d01abdcb39](https://linux-hardware.org/?probe=d01abdcb39) | Dec 19, 2021 |
| MSI           | 870-G45                     | [e6317a2b91](https://linux-hardware.org/?probe=e6317a2b91) | Dec 19, 2021 |
| Unknown       | Intel X79                   | [985655e4b3](https://linux-hardware.org/?probe=985655e4b3) | Dec 11, 2021 |
| Unknown       | Intel X79                   | [6f32192557](https://linux-hardware.org/?probe=6f32192557) | Dec 08, 2021 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | [bd8742e075](https://linux-hardware.org/?probe=bd8742e075) | Dec 08, 2021 |
| MSI           | Boston                      | [0b79772dfa](https://linux-hardware.org/?probe=0b79772dfa) | Dec 04, 2021 |
| Supermicro    | C2SBC-Q                     | [1099e48366](https://linux-hardware.org/?probe=1099e48366) | Nov 28, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | [58d43162d2](https://linux-hardware.org/?probe=58d43162d2) | Nov 28, 2021 |
| Gigabyte      | H310M S2H x.x               | [fc59694424](https://linux-hardware.org/?probe=fc59694424) | Nov 17, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | [35b58ec233](https://linux-hardware.org/?probe=35b58ec233) | Nov 16, 2021 |
| Seco          | C40 C                       | [27bff03d0c](https://linux-hardware.org/?probe=27bff03d0c) | Nov 08, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | [9bcd3d5479](https://linux-hardware.org/?probe=9bcd3d5479) | Oct 29, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | [c7a0fe2f88](https://linux-hardware.org/?probe=c7a0fe2f88) | Oct 26, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | [aedfc53de6](https://linux-hardware.org/?probe=aedfc53de6) | Oct 20, 2021 |
| MSI           | H61M-P23                    | [3a07878154](https://linux-hardware.org/?probe=3a07878154) | Sep 28, 2021 |
| MSI           | MEG X570 GODLIKE            | [1440e244f6](https://linux-hardware.org/?probe=1440e244f6) | Aug 26, 2021 |
| Gigabyte      | B365M GAMING HD             | [d920558127](https://linux-hardware.org/?probe=d920558127) | Aug 14, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [5cd377c0e0](https://linux-hardware.org/?probe=5cd377c0e0) | Aug 13, 2021 |
| Gigabyte      | B75M-D2P                    | [5e54c2a102](https://linux-hardware.org/?probe=5e54c2a102) | Aug 12, 2021 |
| HP            | 2B38                        | [be24f3f652](https://linux-hardware.org/?probe=be24f3f652) | Jul 26, 2021 |
| HP            | 2B38                        | [c1198b90f6](https://linux-hardware.org/?probe=c1198b90f6) | Jul 26, 2021 |
| ASRock        | H410M-HDV                   | [58b70e282d](https://linux-hardware.org/?probe=58b70e282d) | Jul 14, 2021 |
| Gigabyte      | B365M GAMING HD             | [66cf378cf1](https://linux-hardware.org/?probe=66cf378cf1) | Jul 10, 2021 |
| Gigabyte      | B85M-DS3H-A                 | [6496f18326](https://linux-hardware.org/?probe=6496f18326) | Jul 02, 2021 |
| Gigabyte      | B85M-DS3H-A                 | [71da4978c9](https://linux-hardware.org/?probe=71da4978c9) | Jun 29, 2021 |
| Gigabyte      | B365M GAMING HD             | [ed911e7e8c](https://linux-hardware.org/?probe=ed911e7e8c) | Jun 26, 2021 |
| Gigabyte      | B365M GAMING HD             | [8785d98b0b](https://linux-hardware.org/?probe=8785d98b0b) | Jun 19, 2021 |
| ASUSTek       | PRIME Z390-P                | [54e520ac17](https://linux-hardware.org/?probe=54e520ac17) | Jun 17, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [76219e9cca](https://linux-hardware.org/?probe=76219e9cca) | Jun 09, 2021 |
| ASRock        | H410M-HDV                   | [bcb80080a5](https://linux-hardware.org/?probe=bcb80080a5) | Jun 06, 2021 |
| HP            | 18E7                        | [9844f6635c](https://linux-hardware.org/?probe=9844f6635c) | May 30, 2021 |
| ASUSTek       | VM62                        | [486aeb5b89](https://linux-hardware.org/?probe=486aeb5b89) | May 25, 2021 |
| Gigabyte      | F2A88XN-WIFI                | [c22e6d8669](https://linux-hardware.org/?probe=c22e6d8669) | May 25, 2021 |
| Dell          | 0D02VH A01                  | [e19475cd4c](https://linux-hardware.org/?probe=e19475cd4c) | May 22, 2021 |
| ASUSTek       | PRIME X399-A                | [a201bdfc36](https://linux-hardware.org/?probe=a201bdfc36) | May 19, 2021 |
| ASUSTek       | M4A78-VM                    | [3313d34c41](https://linux-hardware.org/?probe=3313d34c41) | May 15, 2021 |
| ASUSTek       | Z8NA-D6                     | [1b777c6f08](https://linux-hardware.org/?probe=1b777c6f08) | May 02, 2021 |
| ASUSTek       | Z8NA-D6                     | [4c7956a34c](https://linux-hardware.org/?probe=4c7956a34c) | May 02, 2021 |
| MSI           | Boston                      | [e0cfb03088](https://linux-hardware.org/?probe=e0cfb03088) | Mar 30, 2021 |
| HP            | 1632                        | [adf9ebb679](https://linux-hardware.org/?probe=adf9ebb679) | Mar 25, 2021 |
| MSI           | B450I GAMING PLUS AC        | [6a4196e0aa](https://linux-hardware.org/?probe=6a4196e0aa) | Mar 23, 2021 |
| MSI           | B450M-A PRO MAX             | [dc64c81c35](https://linux-hardware.org/?probe=dc64c81c35) | Mar 23, 2021 |
| ASUSTek       | B85M-G R2.0                 | [71ef988016](https://linux-hardware.org/?probe=71ef988016) | Mar 21, 2021 |
| ASRock        | H410M-HDV                   | [e44a5ce779](https://linux-hardware.org/?probe=e44a5ce779) | Mar 14, 2021 |
| MSI           | Boston                      | [e9513c3b7a](https://linux-hardware.org/?probe=e9513c3b7a) | Mar 03, 2021 |
| ASUSTek       | P8H61-M LX PLUS             | [b94539c6dc](https://linux-hardware.org/?probe=b94539c6dc) | Mar 01, 2021 |
| ASUSTek       | B85M-G R2.0                 | [b2cb174b9a](https://linux-hardware.org/?probe=b2cb174b9a) | Mar 01, 2021 |
| Lenovo        | MAHOBAY NOK                 | [e3c14a6397](https://linux-hardware.org/?probe=e3c14a6397) | Feb 25, 2021 |
| Dell          | 0D02VH A01                  | [87c36a9322](https://linux-hardware.org/?probe=87c36a9322) | Feb 23, 2021 |
| ASUSTek       | VM45                        | [03eeb85521](https://linux-hardware.org/?probe=03eeb85521) | Feb 21, 2021 |
| ASUSTek       | VM65-K                      | [6b97cf71eb](https://linux-hardware.org/?probe=6b97cf71eb) | Feb 18, 2021 |
| ASUSTek       | VM65-K                      | [4f0bcd1276](https://linux-hardware.org/?probe=4f0bcd1276) | Feb 17, 2021 |
| ASUSTek       | VM40B                       | [6c0bf22f39](https://linux-hardware.org/?probe=6c0bf22f39) | Feb 17, 2021 |
| Dell          | 0D02VH A01                  | [ebc5645105](https://linux-hardware.org/?probe=ebc5645105) | Feb 11, 2021 |
| Lenovo        | IdeaCentre K330             | [78ce34058b](https://linux-hardware.org/?probe=78ce34058b) | Feb 11, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [39bc70ca5d](https://linux-hardware.org/?probe=39bc70ca5d) | Jan 13, 2021 |
| ASRock        | H410M-HDV                   | [d2420f233b](https://linux-hardware.org/?probe=d2420f233b) | Jan 10, 2021 |
| MSI           | H97 GAMING 3                | [7e25d7549f](https://linux-hardware.org/?probe=7e25d7549f) | Jan 09, 2021 |
| Dell          | 0TP412                      | [f0e56aacff](https://linux-hardware.org/?probe=f0e56aacff) | Jan 05, 2021 |
| ASRock        | Z390 Phantom Gaming-ITX/... | [cf7386e848](https://linux-hardware.org/?probe=cf7386e848) | Dec 18, 2020 |
| ASUSTek       | H97M-PLUS                   | [1d6b7df7b4](https://linux-hardware.org/?probe=1d6b7df7b4) | Dec 08, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [64adbf132b](https://linux-hardware.org/?probe=64adbf132b) | Dec 08, 2020 |
| Dell          | 0D02VH A01                  | [8309aa39cf](https://linux-hardware.org/?probe=8309aa39cf) | Nov 30, 2020 |
| Gigabyte      | B450M DS3H-CF               | [37d5acae7d](https://linux-hardware.org/?probe=37d5acae7d) | Nov 27, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [97c485886b](https://linux-hardware.org/?probe=97c485886b) | Nov 25, 2020 |
| Dell          | 0D02VH A01                  | [8f55b945a1](https://linux-hardware.org/?probe=8f55b945a1) | Nov 20, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [de597aa847](https://linux-hardware.org/?probe=de597aa847) | Nov 20, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [f5aa8c9150](https://linux-hardware.org/?probe=f5aa8c9150) | Nov 20, 2020 |
| ASUSTek       | H110I-PLUS                  | [a3c484b8ee](https://linux-hardware.org/?probe=a3c484b8ee) | Nov 16, 2020 |
| ASUSTek       | H97M-PLUS                   | [f90977870e](https://linux-hardware.org/?probe=f90977870e) | Nov 04, 2020 |
| Gigabyte      | Z370 HD3P-CF                | [1af7b2b551](https://linux-hardware.org/?probe=1af7b2b551) | Oct 13, 2020 |
| ASUSTek       | H110I-PLUS                  | [e292456297](https://linux-hardware.org/?probe=e292456297) | Sep 17, 2020 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [e7b41f62a4](https://linux-hardware.org/?probe=e7b41f62a4) | Sep 14, 2020 |
| ASUSTek       | H110I-PLUS                  | [20bdbc68b7](https://linux-hardware.org/?probe=20bdbc68b7) | Sep 12, 2020 |
| ASUSTek       | H81M-E                      | [43b8c677bc](https://linux-hardware.org/?probe=43b8c677bc) | Sep 10, 2020 |
| Lenovo        | MAHOBAY NOK                 | [d95b985658](https://linux-hardware.org/?probe=d95b985658) | Sep 01, 2020 |
| Foxconn       | 2ADA                        | [24cad8bed5](https://linux-hardware.org/?probe=24cad8bed5) | Aug 28, 2020 |
| Foxconn       | 2ADA                        | [3d4c2a283d](https://linux-hardware.org/?probe=3d4c2a283d) | Aug 28, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | [e27db6fb31](https://linux-hardware.org/?probe=e27db6fb31) | Aug 24, 2020 |
| HP            | 802E                        | [653b11eec3](https://linux-hardware.org/?probe=653b11eec3) | Aug 11, 2020 |
| HP            | 802E                        | [6f32afeb2b](https://linux-hardware.org/?probe=6f32afeb2b) | Aug 10, 2020 |
| HP            | 802E                        | [25d8ddc0bb](https://linux-hardware.org/?probe=25d8ddc0bb) | Aug 10, 2020 |
| Gigabyte      | B150M-D3H-CF                | [50dc692a9e](https://linux-hardware.org/?probe=50dc692a9e) | Jul 23, 2020 |
| Gigabyte      | Z170X-Gaming 5 Modified ... | [a62f520dc3](https://linux-hardware.org/?probe=a62f520dc3) | Jul 18, 2020 |
| MSI           | B450M MORTAR MAX            | [db0ff5f985](https://linux-hardware.org/?probe=db0ff5f985) | Jun 07, 2020 |
| HP            | 1998                        | [255863fefb](https://linux-hardware.org/?probe=255863fefb) | Jun 01, 2020 |
| Lenovo        | ThinkCentre M90p 3269A12    | [b159b440f2](https://linux-hardware.org/?probe=b159b440f2) | Jun 01, 2020 |
| Lenovo        | ThinkCentre M90p 3269A12    | [4181637bf3](https://linux-hardware.org/?probe=4181637bf3) | Jun 01, 2020 |
| Biostar       | H110MHC                     | [98d1029698](https://linux-hardware.org/?probe=98d1029698) | May 26, 2020 |
| ASUSTek       | B150M-C                     | [2229b866b3](https://linux-hardware.org/?probe=2229b866b3) | May 26, 2020 |
| ASUSTek       | H110I-PLUS                  | [8e55010bac](https://linux-hardware.org/?probe=8e55010bac) | May 22, 2020 |
| ASUSTek       | H110I-PLUS                  | [26293feb91](https://linux-hardware.org/?probe=26293feb91) | May 21, 2020 |
| ASUSTek       | STRIX H270F GAMING          | [c30a3e0ddd](https://linux-hardware.org/?probe=c30a3e0ddd) | May 11, 2020 |
| Dell          | 0C2KJT A00                  | [179a82277c](https://linux-hardware.org/?probe=179a82277c) | May 01, 2020 |
| MSI           | 2A9C                        | [23df26e5de](https://linux-hardware.org/?probe=23df26e5de) | Apr 25, 2020 |
| Acer          | Aspire XC-710 V:1.1         | [664ac5b85b](https://linux-hardware.org/?probe=664ac5b85b) | Apr 24, 2020 |
| MSI           | Boston                      | [e7cf465e34](https://linux-hardware.org/?probe=e7cf465e34) | Apr 22, 2020 |
| ASUSTek       | H110I-PLUS                  | [f504649d96](https://linux-hardware.org/?probe=f504649d96) | Apr 11, 2020 |
| ASUSTek       | H110I-PLUS                  | [3916938374](https://linux-hardware.org/?probe=3916938374) | Apr 11, 2020 |
| Gigabyte      | Z87-HD3                     | [52a7dab5ac](https://linux-hardware.org/?probe=52a7dab5ac) | Apr 09, 2020 |
| ASUSTek       | H110I-PLUS                  | [9c72670aa1](https://linux-hardware.org/?probe=9c72670aa1) | Apr 05, 2020 |
| ASUSTek       | H110I-PLUS                  | [37fb7cae94](https://linux-hardware.org/?probe=37fb7cae94) | Mar 30, 2020 |
| MSI           | B360M FIRE                  | [8bb021d2a6](https://linux-hardware.org/?probe=8bb021d2a6) | Mar 27, 2020 |
| ASUSTek       | H110I-PLUS                  | [18b565a861](https://linux-hardware.org/?probe=18b565a861) | Mar 26, 2020 |
| ASUSTek       | H110I-PLUS                  | [abce376627](https://linux-hardware.org/?probe=abce376627) | Mar 24, 2020 |
| ASUSTek       | H110I-PLUS                  | [e6860a26ae](https://linux-hardware.org/?probe=e6860a26ae) | Mar 24, 2020 |
| ASUSTek       | H110I-PLUS                  | [5f2e14b65b](https://linux-hardware.org/?probe=5f2e14b65b) | Mar 16, 2020 |
| ASUSTek       | H110I-PLUS                  | [1bcf8a4701](https://linux-hardware.org/?probe=1bcf8a4701) | Mar 14, 2020 |
| ASUSTek       | H110I-PLUS                  | [bd55777a4f](https://linux-hardware.org/?probe=bd55777a4f) | Mar 14, 2020 |
| ASUSTek       | H110I-PLUS                  | [137262daa3](https://linux-hardware.org/?probe=137262daa3) | Mar 05, 2020 |
| ASUSTek       | H110I-PLUS                  | [047acafb1a](https://linux-hardware.org/?probe=047acafb1a) | Feb 28, 2020 |
| ASUSTek       | H110I-PLUS                  | [e8315b1469](https://linux-hardware.org/?probe=e8315b1469) | Feb 28, 2020 |
| ASUSTek       | H110I-PLUS                  | [04e5b85d84](https://linux-hardware.org/?probe=04e5b85d84) | Feb 28, 2020 |
| Gigabyte      | Z390 GAMING X-CF            | [310ae04477](https://linux-hardware.org/?probe=310ae04477) | Feb 27, 2020 |
| ASUSTek       | H110I-PLUS                  | [046814376c](https://linux-hardware.org/?probe=046814376c) | Feb 20, 2020 |
| ASUSTek       | H110I-PLUS                  | [a417965167](https://linux-hardware.org/?probe=a417965167) | Feb 19, 2020 |
| Intel         | DH77DF AAG40293-301         | [ac00169b1c](https://linux-hardware.org/?probe=ac00169b1c) | Feb 14, 2020 |
| ASUSTek       | H110I-PLUS                  | [cef9a00862](https://linux-hardware.org/?probe=cef9a00862) | Feb 12, 2020 |
| ASUSTek       | H110I-PLUS                  | [dcc65f9ee3](https://linux-hardware.org/?probe=dcc65f9ee3) | Feb 11, 2020 |
| ASUSTek       | H110I-PLUS                  | [900a11f8b3](https://linux-hardware.org/?probe=900a11f8b3) | Feb 10, 2020 |
| Gigabyte      | GA-MA78GM-S2HP              | [20d5a3bd6a](https://linux-hardware.org/?probe=20d5a3bd6a) | Feb 01, 2020 |
| Gigabyte      | Z77N-WIFI                   | [94c13c0e97](https://linux-hardware.org/?probe=94c13c0e97) | Jan 11, 2020 |
| Gigabyte      | P55A-UD3                    | [7168fd0137](https://linux-hardware.org/?probe=7168fd0137) | Jan 11, 2020 |
| ASUSTek       | Z8NA-D6                     | [b2d6dabaa7](https://linux-hardware.org/?probe=b2d6dabaa7) | Dec 23, 2019 |
| MSI           | X470 GAMING PRO CARBON      | [e3b6ce369a](https://linux-hardware.org/?probe=e3b6ce369a) | Dec 23, 2019 |
| Intel         | DZ68DB AAG27985-101         | [15f84fa3f2](https://linux-hardware.org/?probe=15f84fa3f2) | Oct 26, 2019 |
| Gigabyte      | GA-MA78GM-S2HP              | [3392a03f3c](https://linux-hardware.org/?probe=3392a03f3c) | Oct 03, 2019 |
| Gigabyte      | B150M-D3H-CF                | [4302e84025](https://linux-hardware.org/?probe=4302e84025) | Sep 24, 2019 |
| ASUSTek       | B150M-A                     | [e8ccb234ed](https://linux-hardware.org/?probe=e8ccb234ed) | Aug 30, 2019 |
| ASRock        | B75M R2.0                   | [1479826c17](https://linux-hardware.org/?probe=1479826c17) | Aug 28, 2019 |
| Hardkernel    | ODROID-H2                   | [26d6c60ad5](https://linux-hardware.org/?probe=26d6c60ad5) | Jul 06, 2019 |
| Gigabyte      | GA-MA78GM-S2HP              | [ea2ad2bc4d](https://linux-hardware.org/?probe=ea2ad2bc4d) | Jun 05, 2019 |
| Dell          | 0CRH6C A01                  | [23dcf2aff6](https://linux-hardware.org/?probe=23dcf2aff6) | Apr 08, 2019 |
| ASUSTek       | B150M-A                     | [61bb547684](https://linux-hardware.org/?probe=61bb547684) | Apr 08, 2019 |
| ASUSTek       | B150M-A                     | [8549b6dfd8](https://linux-hardware.org/?probe=8549b6dfd8) | Apr 08, 2019 |
| ASRock        | Z270 Killer SLI             | [a03ea38833](https://linux-hardware.org/?probe=a03ea38833) | Jul 06, 2018 |
| Gigabyte      | GA-M56S-S3                  | [17f0958960](https://linux-hardware.org/?probe=17f0958960) | Oct 06, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Ubuntu 22.04      | 23       | 10.95%  |
| Ubuntu 20.04      | 18       | 8.57%   |
| Arch Rolling      | 15       | 7.14%   |
| Ubuntu 18.04      | 13       | 6.19%   |
| Debian 11         | 11       | 5.24%   |
| OpenMandriva 4.2  | 10       | 4.76%   |
| Pop!_OS 22.04     | 8        | 3.81%   |
| Ubuntu 16.04      | 6        | 2.86%   |
| OpenMandriva 4.3  | 5        | 2.38%   |
| KDE neon 20.04    | 5        | 2.38%   |
| Debian 12         | 5        | 2.38%   |
| Ubuntu 19.10      | 4        | 1.9%    |
| Fedora 35         | 4        | 1.9%    |
| Ubuntu 23.10      | 3        | 1.43%   |
| Ubuntu 23.04      | 3        | 1.43%   |
| Ubuntu 20.10      | 3        | 1.43%   |
| ArcoLinux Rolling | 3        | 1.43%   |
| Ubuntu 21.10      | 2        | 0.95%   |
| Ubuntu 19.04      | 2        | 0.95%   |
| Slackware 15.0    | 2        | 0.95%   |
| PostmarketOS Edge | 2        | 0.95%   |
| Pop!_OS 20.10     | 2        | 0.95%   |
| Parrot 4.9        | 2        | 0.95%   |
| Manjaro 23.1.0    | 2        | 0.95%   |
| Gentoo 2.7        | 2        | 0.95%   |
| Fedora 39         | 2        | 0.95%   |
| Fedora 38         | 2        | 0.95%   |
| Fedora 31         | 2        | 0.95%   |
| Elementary 5.1.7  | 2        | 0.95%   |
| CentOS 8          | 2        | 0.95%   |
| Zorin 16          | 1        | 0.48%   |
| Zorin 15          | 1        | 0.48%   |
| Xubuntu 18.04     | 1        | 0.48%   |
| Ubuntu MATE 20.04 | 1        | 0.48%   |
| Ubuntu 22.10      | 1        | 0.48%   |
| Ubuntu 21.04      | 1        | 0.48%   |
| SteamOS 3.3       | 1        | 0.48%   |
| Slackware 14.2    | 1        | 0.48%   |
| ROSA R8.1         | 1        | 0.48%   |
| Rocky Linux 9.2   | 1        | 0.48%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 74       | 36.63%  |
| OpenMandriva | 17       | 8.42%   |
| Debian       | 17       | 8.42%   |
| Arch         | 16       | 7.92%   |
| Fedora       | 14       | 6.93%   |
| Pop!_OS      | 11       | 5.45%   |
| Manjaro      | 7        | 3.47%   |
| KDE neon     | 5        | 2.48%   |
| Slackware    | 3        | 1.49%   |
| Linux Mint   | 3        | 1.49%   |
| Kubuntu      | 3        | 1.49%   |
| Elementary   | 3        | 1.49%   |
| CentOS       | 3        | 1.49%   |
| ArcoLinux    | 3        | 1.49%   |
| Zorin        | 2        | 0.99%   |
| PostmarketOS | 2        | 0.99%   |
| Parrot       | 2        | 0.99%   |
| Gentoo       | 2        | 0.99%   |
| EndeavourOS  | 2        | 0.99%   |
| Clear Linux  | 2        | 0.99%   |
| Xubuntu      | 1        | 0.5%    |
| Ubuntu MATE  | 1        | 0.5%    |
| SteamOS      | 1        | 0.5%    |
| ROSA         | 1        | 0.5%    |
| Rocky Linux  | 1        | 0.5%    |
| openSUSE     | 1        | 0.5%    |
| NixOS        | 1        | 0.5%    |
| Lubuntu      | 1        | 0.5%    |
| Kali         | 1        | 0.5%    |
| Artix        | 1        | 0.5%    |
| Alpine       | 1        | 0.5%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.14-desktop-1omv4002 | 9        | 3.78%   |
| 4.15.0-142-generic       | 6        | 2.52%   |
| 5.16.7-desktop-1omv4003  | 5        | 2.1%    |
| 6.2.0-26-generic         | 3        | 1.26%   |
| 5.4.0-42-generic         | 3        | 1.26%   |
| 5.15.0-46-generic        | 3        | 1.26%   |
| 6.7.0-zen3-1.1-zen       | 2        | 0.84%   |
| 6.5.0-9-generic          | 2        | 0.84%   |
| 6.5.0-14-generic         | 2        | 0.84%   |
| 6.2.0-39-generic         | 2        | 0.84%   |
| 6.2.0-33-generic         | 2        | 0.84%   |
| 6.2.0-20-generic         | 2        | 0.84%   |
| 6.1.1-arch1-1            | 2        | 0.84%   |
| 6.1.0-9-amd64            | 2        | 0.84%   |
| 5.5.0-1parrot1-amd64     | 2        | 0.84%   |
| 5.4.0-56-generic         | 2        | 0.84%   |
| 5.4.0-47-generic         | 2        | 0.84%   |
| 5.4.0-33-generic         | 2        | 0.84%   |
| 5.4.0-109-generic        | 2        | 0.84%   |
| 5.3.0-46-generic         | 2        | 0.84%   |
| 5.19.0-76051900-generic  | 2        | 0.84%   |
| 5.19.0-43-generic        | 2        | 0.84%   |
| 5.13.0-35-generic        | 2        | 0.84%   |
| 5.11.0-43-generic        | 2        | 0.84%   |
| 5.0.0-25-generic         | 2        | 0.84%   |
| 4.15.0-88-generic        | 2        | 0.84%   |
| 6.8.4-arch1-1            | 1        | 0.42%   |
| 6.7.8-arch1-1            | 1        | 0.42%   |
| 6.6.7-1-MANJARO          | 1        | 0.42%   |
| 6.6.4-1389.native        | 1        | 0.42%   |
| 6.6.18                   | 1        | 0.42%   |
| 6.6.11-200.fc39.x86_64   | 1        | 0.42%   |
| 6.6.10-zen1-1-zen        | 1        | 0.42%   |
| 6.5.6-76060506-generic   | 1        | 0.42%   |
| 6.5.6-300.fc39.x86_64    | 1        | 0.42%   |
| 6.5.3-zen1-1-zen         | 1        | 0.42%   |
| 6.5.11-1-MANJARO         | 1        | 0.42%   |
| 6.5.0-21-generic         | 1        | 0.42%   |
| 6.5.0-18-generic         | 1        | 0.42%   |
| 6.4.5-arch1-1            | 1        | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 20       | 8.93%   |
| 5.15.0  | 13       | 5.8%    |
| 4.15.0  | 12       | 5.36%   |
| 6.2.0   | 11       | 4.91%   |
| 5.8.0   | 9        | 4.02%   |
| 5.19.0  | 9        | 4.02%   |
| 5.10.14 | 9        | 4.02%   |
| 6.1.0   | 8        | 3.57%   |
| 5.3.0   | 7        | 3.13%   |
| 5.13.0  | 7        | 3.13%   |
| 5.11.0  | 7        | 3.13%   |
| 5.10.0  | 7        | 3.13%   |
| 6.5.0   | 6        | 2.68%   |
| 5.16.7  | 5        | 2.23%   |
| 5.0.0   | 5        | 2.23%   |
| 6.1.1   | 3        | 1.34%   |
| 5.17.5  | 3        | 1.34%   |
| 4.18.0  | 3        | 1.34%   |
| 6.7.0   | 2        | 0.89%   |
| 6.5.6   | 2        | 0.89%   |
| 6.2.9   | 2        | 0.89%   |
| 6.0.0   | 2        | 0.89%   |
| 5.5.0   | 2        | 0.89%   |
| 5.14.14 | 2        | 0.89%   |
| 6.8.4   | 1        | 0.45%   |
| 6.7.8   | 1        | 0.45%   |
| 6.6.7   | 1        | 0.45%   |
| 6.6.4   | 1        | 0.45%   |
| 6.6.18  | 1        | 0.45%   |
| 6.6.11  | 1        | 0.45%   |
| 6.6.10  | 1        | 0.45%   |
| 6.5.3   | 1        | 0.45%   |
| 6.5.11  | 1        | 0.45%   |
| 6.4.5   | 1        | 0.45%   |
| 6.4.3   | 1        | 0.45%   |
| 6.4.11  | 1        | 0.45%   |
| 6.3.9   | 1        | 0.45%   |
| 6.3.8   | 1        | 0.45%   |
| 6.2.8   | 1        | 0.45%   |
| 6.2.6   | 1        | 0.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 21       | 9.59%   |
| 5.4     | 20       | 9.13%   |
| 5.10    | 20       | 9.13%   |
| 6.2     | 15       | 6.85%   |
| 6.1     | 13       | 5.94%   |
| 4.15    | 12       | 5.48%   |
| 5.8     | 11       | 5.02%   |
| 5.19    | 11       | 5.02%   |
| 6.5     | 10       | 4.57%   |
| 5.13    | 9        | 4.11%   |
| 5.16    | 8        | 3.65%   |
| 5.11    | 8        | 3.65%   |
| 5.3     | 7        | 3.2%    |
| 6.6     | 5        | 2.28%   |
| 5.0     | 5        | 2.28%   |
| 6.0     | 4        | 1.83%   |
| 5.17    | 4        | 1.83%   |
| 5.14    | 4        | 1.83%   |
| 6.7     | 3        | 1.37%   |
| 6.4     | 3        | 1.37%   |
| 5.9     | 3        | 1.37%   |
| 5.5     | 3        | 1.37%   |
| 5.18    | 3        | 1.37%   |
| 4.18    | 3        | 1.37%   |
| 6.3     | 2        | 0.91%   |
| 5.7     | 2        | 0.91%   |
| 5.6     | 2        | 0.91%   |
| 5.12    | 2        | 0.91%   |
| 6.8     | 1        | 0.46%   |
| 4.9     | 1        | 0.46%   |
| 4.4     | 1        | 0.46%   |
| 4.20    | 1        | 0.46%   |
| 4.17    | 1        | 0.46%   |
| 3.10    | 1        | 0.46%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 188      | 96.91%  |
| riscv64 | 2        | 1.03%   |
| i686    | 2        | 1.03%   |
| aarch64 | 2        | 1.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 88       | 42.93%  |
| KDE5          | 42       | 20.49%  |
| Unknown       | 39       | 19.02%  |
| XFCE          | 8        | 3.9%    |
| KDE           | 5        | 2.44%   |
| X-Cinnamon    | 4        | 1.95%   |
| Pantheon      | 3        | 1.46%   |
| MATE          | 3        | 1.46%   |
| sway          | 2        | 0.98%   |
| openbox       | 1        | 0.49%   |
| LXQt          | 1        | 0.49%   |
| LXDE          | 1        | 0.49%   |
| KDE6          | 1        | 0.49%   |
| KDE4          | 1        | 0.49%   |
| ICEWM         | 1        | 0.49%   |
| i3            | 1        | 0.49%   |
| Hyprland      | 1        | 0.49%   |
| GNOME Classic | 1        | 0.49%   |
| Deepin        | 1        | 0.49%   |
| awesome       | 1        | 0.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 139      | 67.48%  |
| Wayland | 42       | 20.39%  |
| Tty     | 13       | 6.31%   |
| Unknown | 12       | 5.83%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 88       | 43.35%  |
| SDDM    | 40       | 19.7%   |
| GDM3    | 38       | 18.72%  |
| LightDM | 15       | 7.39%   |
| GDM     | 15       | 7.39%   |
| TDM     | 2        | 0.99%   |
| Ly      | 2        | 0.99%   |
| XDM     | 1        | 0.49%   |
| KDM     | 1        | 0.49%   |
| GREETD  | 1        | 0.49%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 73       | 36.14%  |
| en_HK   | 59       | 29.21%  |
| zh_CN   | 22       | 10.89%  |
| Unknown | 14       | 6.93%   |
| zh_TW   | 13       | 6.44%   |
| en_GB   | 7        | 3.47%   |
| zh_HK   | 6        | 2.97%   |
| C       | 6        | 2.97%   |
| en_AU   | 2        | 0.99%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 115      | 57.79%  |
| BIOS | 84       | 42.21%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 133      | 66.17%  |
| Btrfs   | 24       | 11.94%  |
| Tmpfs   | 18       | 8.96%   |
| Overlay | 11       | 5.47%   |
| Xfs     | 7        | 3.48%   |
| Zfs     | 3        | 1.49%   |
| Unknown | 2        | 1%      |
| F2fs    | 1        | 0.5%    |
| Ext3    | 1        | 0.5%    |
| Ext2    | 1        | 0.5%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 106      | 53.54%  |
| Unknown | 75       | 37.88%  |
| MBR     | 17       | 8.59%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 163      | 81.09%  |
| Yes       | 38       | 18.91%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 137      | 68.5%   |
| Yes       | 63       | 31.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 48       | 24.74%  |
| MSI                                  | 32       | 16.49%  |
| Gigabyte Technology                  | 31       | 15.98%  |
| ASRock                               | 19       | 9.79%   |
| Dell                                 | 13       | 6.7%    |
| Hewlett-Packard                      | 11       | 5.67%   |
| Unknown                              | 10       | 5.15%   |
| Lenovo                               | 8        | 4.12%   |
| Intel                                | 7        | 3.61%   |
| Supermicro                           | 2        | 1.03%   |
| Acer                                 | 2        | 1.03%   |
| TSINGHUA TONGFANG COMPUTER           | 1        | 0.52%   |
| Soyo                                 | 1        | 0.52%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.52%   |
| Seco                                 | 1        | 0.52%   |
| Huanan                               | 1        | 0.52%   |
| HPE                                  | 1        | 0.52%   |
| Hardkernel                           | 1        | 0.52%   |
| Foxconn                              | 1        | 0.52%   |
| Biostar                              | 1        | 0.52%   |
| BESSTAR Tech                         | 1        | 0.52%   |
| AZW                                  | 1        | 0.52%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Unknown                                    | 10       | 5.15%   |
| Intel SKYBAY                               | 4        | 2.06%   |
| ASUS All Series                            | 4        | 2.06%   |
| ASUS H110I-PLUS                            | 3        | 1.55%   |
| MSI MS-7D42                                | 2        | 1.03%   |
| MSI MS-7C94                                | 2        | 1.03%   |
| MSI MS-7C02                                | 2        | 1.03%   |
| MSI MS-7B93                                | 2        | 1.03%   |
| MSI MS-7B89                                | 2        | 1.03%   |
| HP ProDesk 600 G1 SFF                      | 2        | 1.03%   |
| Gigabyte X570 AORUS ELITE                  | 2        | 1.03%   |
| ASUS Z8NA-D6                               | 2        | 1.03%   |
| ASUS VM65                                  | 2        | 1.03%   |
| ASUS VM62                                  | 2        | 1.03%   |
| ASRock H410M-ITX/ac                        | 2        | 1.03%   |
| ASRock H410M-HDV                           | 2        | 1.03%   |
| TSINGHUA TONGFANG COMPUTER E500            | 1        | 0.52%   |
| Supermicro PIO-617R-TLN4F+-ST031           | 1        | 0.52%   |
| Supermicro C2SBC-Q                         | 1        | 0.52%   |
| Soyo SY-A68M FS V2.0                       | 1        | 0.52%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1        | 0.52%   |
| Seco C40                                   | 1        | 0.52%   |
| MSI Pro 3130 Small Form Factor PC          | 1        | 0.52%   |
| MSI MS-7E02                                | 1        | 0.52%   |
| MSI MS-7D86                                | 1        | 0.52%   |
| MSI MS-7D75                                | 1        | 0.52%   |
| MSI MS-7D32                                | 1        | 0.52%   |
| MSI MS-7D31                                | 1        | 0.52%   |
| MSI MS-7C95                                | 1        | 0.52%   |
| MSI MS-7C52                                | 1        | 0.52%   |
| MSI MS-7C34                                | 1        | 0.52%   |
| MSI MS-7B78                                | 1        | 0.52%   |
| MSI MS-7B53                                | 1        | 0.52%   |
| MSI MS-7A70                                | 1        | 0.52%   |
| MSI MS-7A40                                | 1        | 0.52%   |
| MSI MS-7A38                                | 1        | 0.52%   |
| MSI MS-7918                                | 1        | 0.52%   |
| MSI MS-7851                                | 1        | 0.52%   |
| MSI MS-7817                                | 1        | 0.52%   |
| MSI MS-7808                                | 1        | 0.52%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Unknown                                    | 10       | 5.15%   |
| ASUS PRIME                                 | 9        | 4.64%   |
| ASUS ROG                                   | 8        | 4.12%   |
| Dell OptiPlex                              | 7        | 3.61%   |
| ASUS TUF                                   | 6        | 3.09%   |
| Lenovo ThinkCentre                         | 5        | 2.58%   |
| Intel SKYBAY                               | 4        | 2.06%   |
| ASUS All                                   | 4        | 2.06%   |
| HP ProDesk                                 | 3        | 1.55%   |
| Gigabyte X570                              | 3        | 1.55%   |
| Dell Precision                             | 3        | 1.55%   |
| ASUS H110I-PLUS                            | 3        | 1.55%   |
| MSI MS-7D42                                | 2        | 1.03%   |
| MSI MS-7C94                                | 2        | 1.03%   |
| MSI MS-7C02                                | 2        | 1.03%   |
| MSI MS-7B93                                | 2        | 1.03%   |
| MSI MS-7B89                                | 2        | 1.03%   |
| HP EliteDesk                               | 2        | 1.03%   |
| Gigabyte B450                              | 2        | 1.03%   |
| Dell Inspiron                              | 2        | 1.03%   |
| ASUS Z8NA-D6                               | 2        | 1.03%   |
| ASUS VM65                                  | 2        | 1.03%   |
| ASUS VM62                                  | 2        | 1.03%   |
| ASRock H410M-ITX                           | 2        | 1.03%   |
| ASRock H410M-HDV                           | 2        | 1.03%   |
| TSINGHUA TONGFANG COMPUTER E500            | 1        | 0.52%   |
| Supermicro PIO-617R-TLN4F+-ST031           | 1        | 0.52%   |
| Supermicro C2SBC-Q                         | 1        | 0.52%   |
| Soyo SY-A68M                               | 1        | 0.52%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1        | 0.52%   |
| Seco C40                                   | 1        | 0.52%   |
| MSI Pro                                    | 1        | 0.52%   |
| MSI MS-7E02                                | 1        | 0.52%   |
| MSI MS-7D86                                | 1        | 0.52%   |
| MSI MS-7D75                                | 1        | 0.52%   |
| MSI MS-7D32                                | 1        | 0.52%   |
| MSI MS-7D31                                | 1        | 0.52%   |
| MSI MS-7C95                                | 1        | 0.52%   |
| MSI MS-7C52                                | 1        | 0.52%   |
| MSI MS-7C34                                | 1        | 0.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 22       | 11.34%  |
| 2022    | 17       | 8.76%   |
| 2021    | 16       | 8.25%   |
| 2020    | 16       | 8.25%   |
| 2019    | 16       | 8.25%   |
| 2014    | 15       | 7.73%   |
| 2016    | 13       | 6.7%    |
| 2013    | 13       | 6.7%    |
| 2010    | 11       | 5.67%   |
| 2017    | 10       | 5.15%   |
| 2023    | 9        | 4.64%   |
| 2015    | 8        | 4.12%   |
| 2011    | 8        | 4.12%   |
| 2012    | 7        | 3.61%   |
| 2008    | 5        | 2.58%   |
| 2009    | 4        | 2.06%   |
| Unknown | 3        | 1.55%   |
| 2007    | 1        | 0.52%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 194      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 185      | 95.36%  |
| Enabled  | 9        | 4.64%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 194      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 43       | 21.61%  |
| 32.01-64.0  | 42       | 21.11%  |
| 8.01-16.0   | 32       | 16.08%  |
| 64.01-256.0 | 25       | 12.56%  |
| 3.01-4.0    | 21       | 10.55%  |
| 4.01-8.0    | 20       | 10.05%  |
| 24.01-32.0  | 10       | 5.03%   |
| 1.01-2.0    | 3        | 1.51%   |
| 0.51-1.0    | 2        | 1.01%   |
| 2.01-3.0    | 1        | 0.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 53       | 24.31%  |
| 2.01-3.0   | 48       | 22.02%  |
| 4.01-8.0   | 42       | 19.27%  |
| 3.01-4.0   | 30       | 13.76%  |
| 8.01-16.0  | 16       | 7.34%   |
| 0.51-1.0   | 11       | 5.05%   |
| 16.01-24.0 | 7        | 3.21%   |
| 0.01-0.5   | 6        | 2.75%   |
| 32.01-64.0 | 3        | 1.38%   |
| 24.01-32.0 | 1        | 0.46%   |
| Unknown    | 1        | 0.46%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 84       | 41.18%  |
| 2      | 54       | 26.47%  |
| 3      | 36       | 17.65%  |
| 5      | 10       | 4.9%    |
| 4      | 9        | 4.41%   |
| 6      | 3        | 1.47%   |
| 0      | 3        | 1.47%   |
| 9      | 2        | 0.98%   |
| 7      | 2        | 0.98%   |
| 11     | 1        | 0.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 144      | 73.85%  |
| Yes       | 51       | 26.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 189      | 97.42%  |
| No        | 5        | 2.58%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 107      | 53.77%  |
| No        | 92       | 46.23%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 103      | 51.76%  |
| Yes       | 96       | 48.24%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Hong Kong | 194      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Central          | 110      | 52.63%  |
| Kowloon          | 13       | 6.22%   |
| Hong Kong        | 11       | 5.26%   |
| Tuen Mun         | 9        | 4.31%   |
| Wanchai          | 6        | 2.87%   |
| Tseung Kwan O    | 5        | 2.39%   |
| Ngau Wu Tok      | 4        | 1.91%   |
| Yuen Long        | 3        | 1.44%   |
| To Kwa Wan       | 3        | 1.44%   |
| Tai Po           | 3        | 1.44%   |
| Shatin           | 3        | 1.44%   |
| Ma On Shan Tsuen | 3        | 1.44%   |
| Hung Hom         | 3        | 1.44%   |
| Tsimshatsui      | 2        | 0.96%   |
| Sham Shui Po     | 2        | 0.96%   |
| Quarry Bay       | 2        | 0.96%   |
| Kwu Tung         | 2        | 0.96%   |
| Kwai Chung       | 2        | 0.96%   |
| Ho Man Tin       | 2        | 0.96%   |
| Cheung Sha Lan   | 2        | 0.96%   |
| Chai Wan         | 2        | 0.96%   |
| Wong Tai Sin     | 1        | 0.48%   |
| Tung Chung       | 1        | 0.48%   |
| Tsuen Wan        | 1        | 0.48%   |
| Tai Wan To       | 1        | 0.48%   |
| Tai Kok Tsui     | 1        | 0.48%   |
| Sheung Shui      | 1        | 0.48%   |
| Sha Tin Wai      | 1        | 0.48%   |
| Sai Kung         | 1        | 0.48%   |
| North Point      | 1        | 0.48%   |
| Ma Wan           | 1        | 0.48%   |
| Ma On Shan       | 1        | 0.48%   |
| Lai Chi Kok      | 1        | 0.48%   |
| Kwun Tong        | 1        | 0.48%   |
| Kwun Hang        | 1        | 0.48%   |
| Kowloon Bay      | 1        | 0.48%   |
| Fo Tan           | 1        | 0.48%   |
| Discovery Bay    | 1        | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 54       | 84     | 14.59%  |
| WDC                         | 49       | 82     | 13.24%  |
| Samsung Electronics         | 32       | 52     | 8.65%   |
| Toshiba                     | 27       | 41     | 7.3%    |
| Kingston                    | 20       | 26     | 5.41%   |
| SanDisk                     | 18       | 20     | 4.86%   |
| A-DATA Technology           | 15       | 21     | 4.05%   |
| Crucial                     | 12       | 22     | 3.24%   |
| Hitachi                     | 10       | 20     | 2.7%    |
| Silicon Motion              | 9        | 13     | 2.43%   |
| Unknown                     | 7        | 7      | 1.89%   |
| SK hynix                    | 7        | 12     | 1.89%   |
| HGST                        | 6        | 7      | 1.62%   |
| Unknown                     | 6        | 6      | 1.62%   |
| KIOXIA                      | 5        | 6      | 1.35%   |
| Intel                       | 5        | 16     | 1.35%   |
| Transcend                   | 4        | 5      | 1.08%   |
| Phison                      | 4        | 7      | 1.08%   |
| MAXIO Technology (Hangzhou) | 4        | 5      | 1.08%   |
| LITEON                      | 4        | 4      | 1.08%   |
| Fujitsu                     | 4        | 9      | 1.08%   |
| Plextor                     | 3        | 3      | 0.81%   |
| Netac                       | 3        | 3      | 0.81%   |
| JMicron Technology          | 3        | 6      | 0.81%   |
| Hikvision                   | 3        | 3      | 0.81%   |
| Gigabyte Technology         | 3        | 6      | 0.81%   |
| DOGGO                       | 3        | 3      | 0.81%   |
| ADATA Technology            | 3        | 6      | 0.81%   |
| ZHITAI                      | 2        | 4      | 0.54%   |
| Team                        | 2        | 2      | 0.54%   |
| SPCC                        | 2        | 2      | 0.54%   |
| Micron/Crucial Technology   | 2        | 2      | 0.54%   |
| Lite-On                     | 2        | 4      | 0.54%   |
| KIOXIA-EXCERIA              | 2        | 3      | 0.54%   |
| Yangtze Memory Technologies | 1        | 1      | 0.27%   |
| XPG                         | 1        | 1      | 0.27%   |
| WXC-R1                      | 1        | 1      | 0.27%   |
| WDC WDS2                    | 1        | 1      | 0.27%   |
| tigo                        | 1        | 1      | 0.27%   |
| Teclast                     | 1        | 1      | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB                                | 6        | 1.47%   |
| Unknown                                               | 6        | 1.47%   |
| Seagate ST500DM002-1BD142 500GB                       | 5        | 1.23%   |
| Samsung SSD 860 EVO 1TB                               | 5        | 1.23%   |
| A-DATA SP550 240GB SSD                                | 5        | 1.23%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 4        | 0.98%   |
| Toshiba DT01ACA050 500GB                              | 4        | 0.98%   |
| Kingston SA400S37480G 480GB SSD                       | 4        | 0.98%   |
| WDC WD30EZRX-00D8PB0 3TB                              | 3        | 0.74%   |
| Toshiba DT01ACA300 3TB                                | 3        | 0.74%   |
| Toshiba DT01ACA200 2TB                                | 3        | 0.74%   |
| Seagate ST4000DM004-2CV104 4TB                        | 3        | 0.74%   |
| Seagate ST3500413AS 500GB                             | 3        | 0.74%   |
| Seagate ST3250318AS 250GB                             | 3        | 0.74%   |
| Seagate ST2000DM008-2FR102 2TB                        | 3        | 0.74%   |
| Seagate ST1000DM010-2EP102 1TB                        | 3        | 0.74%   |
| SanDisk NVMe SSD Drive 1TB                            | 3        | 0.74%   |
| KIOXIA NVMe SSD 1TB                                   | 3        | 0.74%   |
| Kingston SA400S37960G 960GB SSD                       | 3        | 0.74%   |
| JMicron Generic 320GB                                 | 3        | 0.74%   |
| Fujitsu F300 480GB                                    | 3        | 0.74%   |
| DOGGO DQ-60G SSD                                      | 3        | 0.74%   |
| Crucial CT500MX500SSD1 500GB                          | 3        | 0.74%   |
| WDC WDS200T2B0A 2TB SSD                               | 2        | 0.49%   |
| WDC WD20EZBX-00AYRA0 2TB                              | 2        | 0.49%   |
| WDC WD10EZEX-75WN4A1 1TB                              | 2        | 0.49%   |
| Toshiba MG05ACA800E 8TB                               | 2        | 0.49%   |
| SK hynix SC311 SATA 128GB SSD                         | 2        | 0.49%   |
| SK hynix BC711 NVMe 256GB                             | 2        | 0.49%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 2        | 0.49%   |
| Silicon Motion NVMe SSD Drive 512GB                   | 2        | 0.49%   |
| Silicon Motion NVMe SSD Drive 1024GB                  | 2        | 0.49%   |
| Seagate ST3500418AS 500GB                             | 2        | 0.49%   |
| Seagate ST3250310AS 250GB                             | 2        | 0.49%   |
| Seagate ST320LT007-9ZV142 320GB                       | 2        | 0.49%   |
| Seagate ST3160815AS 160GB                             | 2        | 0.49%   |
| Seagate ST2000DM001-1CH164 2TB                        | 2        | 0.49%   |
| Seagate ST1000DM003-1SB102 1TB                        | 2        | 0.49%   |
| Seagate ST1000DM003-1ER162 1TB                        | 2        | 0.49%   |
| Sandisk WD_BLACK SN770 1TB                            | 2        | 0.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Desktops | Drives | Percent |
|--------------------|----------|--------|---------|
| Seagate            | 52       | 82     | 37.41%  |
| WDC                | 37       | 66     | 26.62%  |
| Toshiba            | 27       | 41     | 19.42%  |
| Hitachi            | 10       | 20     | 7.19%   |
| HGST               | 6        | 7      | 4.32%   |
| JMicron Technology | 3        | 6      | 2.16%   |
| Unknown            | 1        | 1      | 0.72%   |
| Maxtor             | 1        | 1      | 0.72%   |
| HGST HTS           | 1        | 1      | 0.72%   |
| Fujitsu            | 1        | 1      | 0.72%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 18       | 29     | 16.22%  |
| Kingston            | 13       | 19     | 11.71%  |
| A-DATA Technology   | 12       | 18     | 10.81%  |
| Crucial             | 8        | 18     | 7.21%   |
| WDC                 | 7        | 7      | 6.31%   |
| SanDisk             | 6        | 6      | 5.41%   |
| Transcend           | 4        | 5      | 3.6%    |
| SK hynix            | 3        | 7      | 2.7%    |
| Netac               | 3        | 3      | 2.7%    |
| LITEON              | 3        | 3      | 2.7%    |
| Fujitsu             | 3        | 8      | 2.7%    |
| DOGGO               | 3        | 3      | 2.7%    |
| Team                | 2        | 2      | 1.8%    |
| SPCC                | 2        | 2      | 1.8%    |
| Plextor             | 2        | 2      | 1.8%    |
| ZHITAI              | 1        | 1      | 0.9%    |
| WDC WDS2            | 1        | 1      | 0.9%    |
| tigo                | 1        | 1      | 0.9%    |
| Soyo                | 1        | 1      | 0.9%    |
| ShiJi               | 1        | 1      | 0.9%    |
| PNY                 | 1        | 1      | 0.9%    |
| Patriot             | 1        | 1      | 0.9%    |
| OCZ                 | 1        | 1      | 0.9%    |
| Micron Technology   | 1        | 1      | 0.9%    |
| MAXSUN              | 1        | 1      | 0.9%    |
| Lexar               | 1        | 1      | 0.9%    |
| Intel               | 1        | 3      | 0.9%    |
| Hikvision           | 1        | 1      | 0.9%    |
| External            | 1        | 1      | 0.9%    |
| Dogfish             | 1        | 1      | 0.9%    |
| Corsair             | 1        | 1      | 0.9%    |
| Colorful            | 1        | 1      | 0.9%    |
| China               | 1        | 1      | 0.9%    |
| Asgard              | 1        | 1      | 0.9%    |
| Apacer              | 1        | 3      | 0.9%    |
| Aoluska             | 1        | 1      | 0.9%    |
| AGI                 | 1        | 1      | 0.9%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 115      | 226    | 36.98%  |
| SSD     | 95       | 158    | 30.55%  |
| NVMe    | 86       | 151    | 27.65%  |
| Unknown | 12       | 13     | 3.86%   |
| MMC     | 3        | 3      | 0.96%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 156      | 368    | 59.32%  |
| NVMe | 86       | 150    | 32.7%   |
| SAS  | 18       | 30     | 6.84%   |
| MMC  | 3        | 3      | 1.14%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 100      | 179    | 45.87%  |
| 0.51-1.0   | 55       | 81     | 25.23%  |
| 1.01-2.0   | 25       | 38     | 11.47%  |
| 3.01-4.0   | 13       | 37     | 5.96%   |
| 2.01-3.0   | 12       | 20     | 5.5%    |
| 4.01-10.0  | 10       | 23     | 4.59%   |
| 10.01-20.0 | 3        | 6      | 1.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 40       | 19.05%  |
| More than 3000 | 30       | 14.29%  |
| 251-500        | 26       | 12.38%  |
| 501-1000       | 25       | 11.9%   |
| 1001-2000      | 24       | 11.43%  |
| 51-100         | 20       | 9.52%   |
| 2001-3000      | 14       | 6.67%   |
| Unknown        | 12       | 5.71%   |
| 1-20           | 11       | 5.24%   |
| 21-50          | 8        | 3.81%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 76       | 34.08%  |
| 101-250        | 29       | 13%     |
| 21-50          | 22       | 9.87%   |
| 501-1000       | 21       | 9.42%   |
| 251-500        | 16       | 7.17%   |
| 51-100         | 15       | 6.73%   |
| 1001-2000      | 13       | 5.83%   |
| Unknown        | 12       | 5.38%   |
| 2001-3000      | 11       | 4.93%   |
| More than 3000 | 8        | 3.59%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Desktops | Drives | Percent |
|----------------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB              | 2        | 3      | 8.33%   |
| ZHITAI TiPlus5000 512GB                      | 1        | 1      | 4.17%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD             | 1        | 1      | 4.17%   |
| WDC WD30EZRX-00D8PB0 3TB                     | 1        | 1      | 4.17%   |
| WDC WD10EZEX-60WN4A1 1TB                     | 1        | 1      | 4.17%   |
| WDC WD10EZEX-00RKKA0 1TB                     | 1        | 1      | 4.17%   |
| WDC WD10EALS-00Z8A0 1TB                      | 1        | 2      | 4.17%   |
| Toshiba MK1655GSX 160GB                      | 1        | 1      | 4.17%   |
| Toshiba MK1252GSX 120GB                      | 1        | 1      | 4.17%   |
| Toshiba DT01ACA100 1TB                       | 1        | 1      | 4.17%   |
| Seagate ST3500418AS 500GB                    | 1        | 1      | 4.17%   |
| Seagate ST3250318AS 250GB                    | 1        | 1      | 4.17%   |
| Seagate ST3250310AS 250GB                    | 1        | 1      | 4.17%   |
| Seagate ST3160815AS 160GB                    | 1        | 1      | 4.17%   |
| Seagate ST1000LM014-1EJ164-SSHD 1TB          | 1        | 1      | 4.17%   |
| Samsung Electronics MZVLB512HAJQ-000L7 512GB | 1        | 1      | 4.17%   |
| LITEON IT LCS-128L9S-11 2.5 7mm 128GB SSD    | 1        | 1      | 4.17%   |
| Kingston SA400S37480G 480GB SSD              | 1        | 1      | 4.17%   |
| Intel SSDPEKKW128G7 128GB                    | 1        | 1      | 4.17%   |
| Intel SSD 600P Series 256GB                  | 1        | 4      | 4.17%   |
| Hitachi HTS542512K9SA00 120GB                | 1        | 1      | 4.17%   |
| HGST HTS 541010A9E680 1TB                    | 1        | 1      | 4.17%   |
| Crucial CT500MX500SSD1 500GB                 | 1        | 2      | 4.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 7        | 8      | 30.43%  |
| WDC                 | 4        | 6      | 17.39%  |
| Toshiba             | 3        | 3      | 13.04%  |
| Intel               | 2        | 5      | 8.7%    |
| ZHITAI              | 1        | 1      | 4.35%   |
| Samsung Electronics | 1        | 1      | 4.35%   |
| LITEON              | 1        | 1      | 4.35%   |
| Kingston            | 1        | 1      | 4.35%   |
| Hitachi             | 1        | 1      | 4.35%   |
| HGST HTS            | 1        | 1      | 4.35%   |
| Crucial             | 1        | 2      | 4.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Seagate  | 7        | 8      | 46.67%  |
| WDC      | 3        | 5      | 20%     |
| Toshiba  | 3        | 3      | 20%     |
| Hitachi  | 1        | 1      | 6.67%   |
| HGST HTS | 1        | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 14       | 18     | 63.64%  |
| NVMe | 4        | 7      | 18.18%  |
| SSD  | 4        | 5      | 18.18%  |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 108      | 270    | 48.43%  |
| Works    | 93       | 251    | 41.7%   |
| Malfunc  | 22       | 30     | 9.87%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 136      | 42.9%   |
| AMD                              | 52       | 16.4%   |
| Samsung Electronics              | 19       | 5.99%   |
| Sandisk                          | 17       | 5.36%   |
| ASMedia Technology               | 16       | 5.05%   |
| Silicon Motion                   | 10       | 3.15%   |
| Phison Electronics               | 8        | 2.52%   |
| Kingston Technology Company      | 7        | 2.21%   |
| Micron/Crucial Technology        | 6        | 1.89%   |
| MAXIO Technology (Hangzhou)      | 6        | 1.89%   |
| KIOXIA                           | 6        | 1.89%   |
| ADATA Technology                 | 6        | 1.89%   |
| SK hynix                         | 4        | 1.26%   |
| Marvell Technology Group         | 4        | 1.26%   |
| Yangtze Memory Technologies      | 3        | 0.95%   |
| JMicron Technology               | 3        | 0.95%   |
| Solidigm                         | 2        | 0.63%   |
| LSI Logic / Symbios Logic        | 2        | 0.63%   |
| Lite-On Technology               | 2        | 0.63%   |
| VIA Technologies                 | 1        | 0.32%   |
| Shenzhen Shichuangyi Electronics | 1        | 0.32%   |
| Shenzhen Longsys Electronics     | 1        | 0.32%   |
| Seagate Technology               | 1        | 0.32%   |
| Nvidia                           | 1        | 0.32%   |
| Integrated Technology Express    | 1        | 0.32%   |
| INNOGRIT                         | 1        | 0.32%   |
| Broadcom / LSI                   | 1        | 0.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 24       | 6.56%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 18       | 4.92%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 17       | 4.64%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 15       | 4.1%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 14       | 3.83%   |
| AMD 400 Series Chipset SATA Controller                                         | 14       | 3.83%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 11       | 3.01%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 10       | 2.73%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 10       | 2.73%   |
| Intel Volume Management Device NVMe RAID Controller                            | 8        | 2.19%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 8        | 2.19%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 7        | 1.91%   |
| AMD 600 Series Chipset SATA Controller                                         | 7        | 1.91%   |
| AMD 500 Series Chipset SATA Controller                                         | 7        | 1.91%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 6        | 1.64%   |
| Intel Comet Lake SATA AHCI Controller                                          | 5        | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5        | 1.37%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5        | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 5        | 1.37%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 5        | 1.37%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 4        | 1.09%   |
| Phison E16 PCIe4 NVMe Controller                                               | 4        | 1.09%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 4        | 1.09%   |
| KIOXIA NVMe SSD                                                                | 4        | 1.09%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                             | 4        | 1.09%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 4        | 1.09%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 4        | 1.09%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4        | 1.09%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4        | 1.09%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3        | 0.82%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 3        | 0.82%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 3        | 0.82%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 3        | 0.82%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1602 (DRAM-less)                       | 3        | 0.82%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 3        | 0.82%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3        | 0.82%   |
| Intel SSD 600P Series                                                          | 3        | 0.82%   |
| Intel Raptor Lake SATA AHCI Controller                                         | 3        | 0.82%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3        | 0.82%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 3        | 0.82%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 177      | 58.8%   |
| NVMe | 86       | 28.57%  |
| IDE  | 20       | 6.64%   |
| RAID | 15       | 4.98%   |
| SAS  | 3        | 1%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor     | Desktops | Percent |
|------------|----------|---------|
| Intel      | 135      | 69.59%  |
| AMD        | 54       | 27.84%  |
| thead,c906 | 2        | 1.03%   |
| Unknown    | 2        | 1.03%   |
| iSH        | 1        | 0.52%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Pentium CPU G4560 @ 3.50GHz      | 5        | 2.56%   |
| AMD Ryzen 7 5700G with Radeon Graphics | 5        | 2.56%   |
| AMD Ryzen 5 3600 6-Core Processor      | 5        | 2.56%   |
| Intel Core i7-6700 CPU @ 3.40GHz       | 4        | 2.05%   |
| Intel Core i7-4790 CPU @ 3.60GHz       | 4        | 2.05%   |
| AMD Ryzen 9 7950X 16-Core Processor    | 4        | 2.05%   |
| Intel Xeon CPU X5675 @ 3.07GHz         | 3        | 1.54%   |
| Intel Core i7-9700 CPU @ 3.00GHz       | 3        | 1.54%   |
| Intel Core i7-7700K CPU @ 4.20GHz      | 3        | 1.54%   |
| Intel Core i5-6400 CPU @ 2.70GHz       | 3        | 1.54%   |
| Intel Core i5-4460 CPU @ 3.20GHz       | 3        | 1.54%   |
| Intel Core i5-3470 CPU @ 3.20GHz       | 3        | 1.54%   |
| Intel Core i3-10100 CPU @ 3.60GHz      | 3        | 1.54%   |
| AMD Ryzen 9 5900X 12-Core Processor    | 3        | 1.54%   |
| AMD Ryzen 7 7700X 8-Core Processor     | 3        | 1.54%   |
| AMD Ryzen 7 3700X 8-Core Processor     | 3        | 1.54%   |
| thead,c906 rv64imafdc                  | 2        | 1.03%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz    | 2        | 1.03%   |
| Intel Core i7-9700K CPU @ 3.60GHz      | 2        | 1.03%   |
| Intel Core i7-8700K CPU @ 3.70GHz      | 2        | 1.03%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 2        | 1.03%   |
| Intel Core i7-2600 CPU @ 3.40GHz       | 2        | 1.03%   |
| Intel Core i7-10700 CPU @ 2.90GHz      | 2        | 1.03%   |
| Intel Core i5-8400 CPU @ 2.80GHz       | 2        | 1.03%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 2        | 1.03%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 2        | 1.03%   |
| Intel Core i3-7100 CPU @ 3.90GHz       | 2        | 1.03%   |
| Intel 12th Gen Core i9-12900K          | 2        | 1.03%   |
| Intel 12th Gen Core i7-12700K          | 2        | 1.03%   |
| Intel 12th Gen Core i7-12700           | 2        | 1.03%   |
| Intel 12th Gen Core i5-12600K          | 2        | 1.03%   |
| Intel 12th Gen Core i5-12500           | 2        | 1.03%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz | 2        | 1.03%   |
| AMD Ryzen 9 3900X 12-Core Processor    | 2        | 1.03%   |
| AMD Ryzen 5 5600X 6-Core Processor     | 2        | 1.03%   |
| AMD Ryzen 5 2600X Six-Core Processor   | 2        | 1.03%   |
| AMD Phenom II X6 1055T Processor       | 2        | 1.03%   |
|                                        | 2        | 1.03%   |
| iSH Processor                          | 1        | 0.51%   |
| Intel Xeon CPU X5650 @ 2.67GHz         | 1        | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Other                   | 30       | 15.38%  |
| Intel Core i7           | 29       | 14.87%  |
| Intel Core i5           | 26       | 13.33%  |
| Intel Core i3           | 18       | 9.23%   |
| AMD Ryzen 7             | 16       | 8.21%   |
| AMD Ryzen 5             | 14       | 7.18%   |
| Intel Xeon              | 12       | 6.15%   |
| Intel Pentium           | 10       | 5.13%   |
| AMD Ryzen 9             | 10       | 5.13%   |
| Intel Celeron           | 6        | 3.08%   |
| AMD Phenom II X4        | 3        | 1.54%   |
| Intel Core i9           | 2        | 1.03%   |
| AMD Phenom II X6        | 2        | 1.03%   |
| AMD FX                  | 2        | 1.03%   |
| Intel Pentium Gold      | 1        | 0.51%   |
| Intel Pentium Dual-Core | 1        | 0.51%   |
| Intel Pentium Dual      | 1        | 0.51%   |
| Intel Core 2 Quad       | 1        | 0.51%   |
| Intel Core 2 Extreme    | 1        | 0.51%   |
| Intel Core 2 Duo        | 1        | 0.51%   |
| Intel Core 2            | 1        | 0.51%   |
| AMD Ryzen Threadripper  | 1        | 0.51%   |
| AMD Ryzen Embedded      | 1        | 0.51%   |
| AMD Ryzen 7 PRO         | 1        | 0.51%   |
| AMD Opteron             | 1        | 0.51%   |
| AMD Athlon II X4        | 1        | 0.51%   |
| AMD Athlon 64 X2        | 1        | 0.51%   |
| AMD A8                  | 1        | 0.51%   |
| AMD A10                 | 1        | 0.51%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 59       | 30.26%  |
| 2       | 37       | 18.97%  |
| 8       | 31       | 15.9%   |
| 6       | 29       | 14.87%  |
| 12      | 14       | 7.18%   |
| 16      | 11       | 5.64%   |
| Unknown | 5        | 2.56%   |
| 10      | 4        | 2.05%   |
| 24      | 2        | 1.03%   |
| 3       | 2        | 1.03%   |
| 14      | 1        | 0.51%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 184      | 94.85%  |
| 2       | 5        | 2.58%   |
| Unknown | 5        | 2.58%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 127      | 65.13%  |
| 1       | 63       | 32.31%  |
| Unknown | 5        | 2.56%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 191      | 98.45%  |
| Unknown        | 3        | 1.55%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 63       | 31.19%  |
| 0x306c3    | 12       | 5.94%   |
| 0x90672    | 11       | 5.45%   |
| 0x906e9    | 9        | 4.46%   |
| 0x306a9    | 7        | 3.47%   |
| 0x206a7    | 7        | 3.47%   |
| 0x906ea    | 6        | 2.97%   |
| 0x506e3    | 6        | 2.97%   |
| 0x906ed    | 5        | 2.48%   |
| 0x0a50000d | 5        | 2.48%   |
| 0x0800820d | 4        | 1.98%   |
| 0xa0653    | 3        | 1.49%   |
| 0x806e9    | 3        | 1.49%   |
| 0x40651    | 3        | 1.49%   |
| 0x206c2    | 3        | 1.49%   |
| 0x20652    | 3        | 1.49%   |
| 0x0a50000c | 3        | 1.49%   |
| 0x0a201009 | 3        | 1.49%   |
| 0x08701021 | 3        | 1.49%   |
| 0x08701013 | 3        | 1.49%   |
| 0xa0671    | 2        | 0.99%   |
| 0x90675    | 2        | 0.99%   |
| 0x306e4    | 2        | 0.99%   |
| 0x1067a    | 2        | 0.99%   |
| 0x0a601206 | 2        | 0.99%   |
| 0x0a601203 | 2        | 0.99%   |
| 0x0a201016 | 2        | 0.99%   |
| 0x06003106 | 2        | 0.99%   |
| 0x010000c8 | 2        | 0.99%   |
| 0xb06e0    | 1        | 0.5%    |
| 0xb0671    | 1        | 0.5%    |
| 0xa0655    | 1        | 0.5%    |
| 0x906eb    | 1        | 0.5%    |
| 0x706a1    | 1        | 0.5%    |
| 0x6fd      | 1        | 0.5%    |
| 0x30678    | 1        | 0.5%    |
| 0x20655    | 1        | 0.5%    |
| 0x106e5    | 1        | 0.5%    |
| 0x10677    | 1        | 0.5%    |
| 0x0a704103 | 1        | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 31       | 15.82%  |
| Haswell          | 23       | 11.73%  |
| Unknown          | 20       | 10.2%   |
| Alderlake Hybrid | 17       | 8.67%   |
| Zen 3            | 15       | 7.65%   |
| Zen 2            | 12       | 6.12%   |
| IvyBridge        | 11       | 5.61%   |
| Skylake          | 10       | 5.1%    |
| SandyBridge      | 9        | 4.59%   |
| Westmere         | 8        | 4.08%   |
| CometLake        | 8        | 4.08%   |
| Zen+             | 6        | 3.06%   |
| K10              | 6        | 3.06%   |
| Penryn           | 3        | 1.53%   |
| Core             | 3        | 1.53%   |
| Zen              | 2        | 1.02%   |
| Steamroller      | 2        | 1.02%   |
| Piledriver       | 2        | 1.02%   |
| Icelake          | 2        | 1.02%   |
| Silvermont       | 1        | 0.51%   |
| Nehalem          | 1        | 0.51%   |
| K8 Hammer        | 1        | 0.51%   |
| Gracemont        | 1        | 0.51%   |
| Goldmont plus    | 1        | 0.51%   |
| Excavator        | 1        | 0.51%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Intel             | 83       | 38.79%  |
| Nvidia            | 80       | 37.38%  |
| AMD               | 50       | 23.36%  |
| ASPEED Technology | 1        | 0.47%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 13       | 5.83%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 9        | 4.04%   |
| Intel HD Graphics 610                                                       | 7        | 3.14%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 7        | 3.14%   |
| Intel AlderLake-S GT1                                                       | 7        | 3.14%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 5        | 2.24%   |
| Intel HD Graphics 530                                                       | 5        | 2.24%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 5        | 2.24%   |
| AMD Raphael                                                                 | 5        | 2.24%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 5        | 2.24%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 4        | 1.79%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 4        | 1.79%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 1.79%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 4        | 1.79%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 4        | 1.79%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 4        | 1.79%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4        | 1.79%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 1.79%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 1.35%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 1.35%   |
| Intel HD Graphics 630                                                       | 3        | 1.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 3        | 1.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.35%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 2        | 0.9%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 0.9%    |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 0.9%    |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 0.9%    |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 0.9%    |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 2        | 0.9%    |
| Nvidia AD104 [GeForce RTX 4070 Ti]                                          | 2        | 0.9%    |
| Nvidia AD102 [GeForce RTX 4090]                                             | 2        | 0.9%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 0.9%    |
| Intel HD Graphics 620                                                       | 2        | 0.9%    |
| Intel DG2 [Arc A380]                                                        | 2        | 0.9%    |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 0.9%    |
| Intel Alder Lake-S GT1 [UHD Graphics 770]                                   | 2        | 0.9%    |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 2        | 0.9%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 0.9%    |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 0.9%    |
| AMD RS780 [Radeon HD 3200]                                                  | 2        | 0.9%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 68       | 34.69%  |
| 1 x Intel      | 64       | 32.65%  |
| 1 x AMD        | 39       | 19.9%   |
| Intel + Nvidia | 8        | 4.08%   |
| Other          | 5        | 2.55%   |
| 2 x AMD        | 5        | 2.55%   |
| AMD + Nvidia   | 4        | 2.04%   |
| 3 x AMD        | 1        | 0.51%   |
| 2 x Intel      | 1        | 0.51%   |
| 1 x ASPEED     | 1        | 0.51%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 135      | 68.18%  |
| Proprietary | 49       | 24.75%  |
| Unknown     | 14       | 7.07%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 102      | 51%     |
| 7.01-8.0   | 22       | 11%     |
| 3.01-4.0   | 18       | 9%      |
| 0.51-1.0   | 17       | 8.5%    |
| 1.01-2.0   | 16       | 8%      |
| 0.01-0.5   | 8        | 4%      |
| 5.01-6.0   | 7        | 3.5%    |
| 8.01-16.0  | 6        | 3%      |
| 2.01-3.0   | 2        | 1%      |
| 4.01-5.0   | 1        | 0.5%    |
| 16.01-24.0 | 1        | 0.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 20       | 9.71%   |
| Dell                 | 20       | 9.71%   |
| Goldstar             | 18       | 8.74%   |
| AOC                  | 17       | 8.25%   |
| Philips              | 12       | 5.83%   |
| Acer                 | 10       | 4.85%   |
| BenQ                 | 9        | 4.37%   |
| Ancor Communications | 9        | 4.37%   |
| JRY                  | 7        | 3.4%    |
| ViewSonic            | 6        | 2.91%   |
| Unknown              | 6        | 2.91%   |
| ASUSTek Computer     | 6        | 2.91%   |
| AMO                  | 6        | 2.91%   |
| IPS                  | 5        | 2.43%   |
| Lenovo               | 4        | 1.94%   |
| Hewlett-Packard      | 4        | 1.94%   |
| SOY                  | 3        | 1.46%   |
| Toshiba              | 2        | 0.97%   |
| SKY                  | 2        | 0.97%   |
| RTK                  | 2        | 0.97%   |
| HSO                  | 2        | 0.97%   |
| Eizo                 | 2        | 0.97%   |
| CHR                  | 2        | 0.97%   |
| AUS                  | 2        | 0.97%   |
| Unknown              | 2        | 0.97%   |
| Xiaomi               | 1        | 0.49%   |
| Xiangye              | 1        | 0.49%   |
| Unknown (AAA)        | 1        | 0.49%   |
| TFC                  | 1        | 0.49%   |
| TCT                  | 1        | 0.49%   |
| TCL                  | 1        | 0.49%   |
| Sony                 | 1        | 0.49%   |
| SKG                  | 1        | 0.49%   |
| SAC                  | 1        | 0.49%   |
| PDA                  | 1        | 0.49%   |
| PANDA                | 1        | 0.49%   |
| MSI                  | 1        | 0.49%   |
| Mi                   | 1        | 0.49%   |
| LYC                  | 1        | 0.49%   |
| LG Electronics       | 1        | 0.49%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| JRY HDMI JRY1330 1920x1080 293x165mm 13.2-inch                        | 6        | 2.79%   |
| IPS GF270C IPS2700 1920x1080 598x337mm 27.0-inch                      | 4        | 1.86%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 4        | 1.86%   |
| AMO HS241P AMO2800 3840x2160 620x350mm 28.0-inch                      | 4        | 1.86%   |
| Unknown LCD Monitor XMD Mi TV 1360x768                                | 3        | 1.4%    |
| AOC 2790WG5 AOC2790 1920x1080 598x336mm 27.0-inch                     | 3        | 1.4%    |
| Toshiba TV TSB2634 1920x1080                                          | 2        | 0.93%   |
| SOY M5 MONITOR SOY0240 1920x1080 520x320mm 24.0-inch                  | 2        | 0.93%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 2        | 0.93%   |
| Philips PHL 323E7 PHLC121 1920x1080 698x393mm 31.5-inch               | 2        | 0.93%   |
| Lenovo LEN L24e-20 LEN65DF 1920x1080 527x296mm 23.8-inch              | 2        | 0.93%   |
| HSO B2431M HSO2431 3840x2160 520x290mm 23.4-inch                      | 2        | 0.93%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 2        | 0.93%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch              | 2        | 0.93%   |
| Dell U2417H DEL40E7 1920x1080 530x300mm 24.0-inch                     | 2        | 0.93%   |
| CHR ET2031I CHR7511 1600x900 518x333mm 24.2-inch                      | 2        | 0.93%   |
| AOC 24B1W1G5 AOC2401 1920x1080 527x296mm 23.8-inch                    | 2        | 0.93%   |
| Acer V196HQL ACR033D 1366x768 410x230mm 18.5-inch                     | 2        | 0.93%   |
| Unknown                                                               | 2        | 0.93%   |
| Xiaomi Mi TV XMD004A 1440x900 708x398mm 32.0-inch                     | 1        | 0.47%   |
| Xiangye XE2400 XYE2380 3840x2160 520x310mm 23.8-inch                  | 1        | 0.47%   |
| ViewSonic VX2462 series VSC7A3F 1920x1080 530x300mm 24.0-inch         | 1        | 0.47%   |
| ViewSonic VX2260WM VSCFC21 1920x1080 477x268mm 21.5-inch              | 1        | 0.47%   |
| ViewSonic VX2239 SERIES VSC5225 1920x1080 480x270mm 21.7-inch         | 1        | 0.47%   |
| ViewSonic VG921m VSC301E 1280x1024 380x300mm 19.1-inch                | 1        | 0.47%   |
| ViewSonic VA2465 SERIES VSCB730 1920x1080 521x293mm 23.5-inch         | 1        | 0.47%   |
| ViewSonic VA1616wSERIES VSC0021 1366x768 348x197mm 15.7-inch          | 1        | 0.47%   |
| Unknown LCD Monitor hp f1523 1024x768                                 | 1        | 0.47%   |
| Unknown LCD Monitor GBT G32QC A 2560x1440                             | 1        | 0.47%   |
| Unknown LCD Monitor FST V22T-1R LED 1920x1080                         | 1        | 0.47%   |
| Unknown (AAA) U270 AAA2700 3840x2160 596x335mm 26.9-inch              | 1        | 0.47%   |
| TFC TF2421 TFC2421 1920x1080 527x296mm 23.8-inch                      | 1        | 0.47%   |
| TCT DP1080P60 TCT0270 2560x1600 520x290mm 23.4-inch                   | 1        | 0.47%   |
| TCL SMART TV TCL5507 1920x1080 1209x680mm 54.6-inch                   | 1        | 0.47%   |
| SOY M5 MONITOR SOY0240 1920x1080 443x249mm 20.0-inch                  | 1        | 0.47%   |
| Sony TV SNY4B03 1920x1080 708x398mm 32.0-inch                         | 1        | 0.47%   |
| SKY TV MONITOR SKY0030 1920x1080 1430x800mm 64.5-inch                 | 1        | 0.47%   |
| SKY M16U1 SKY0156 3840x2160 345x194mm 15.6-inch                       | 1        | 0.47%   |
| SKG PMO G270-CQK SKG2712 2560x1440 530x280mm 23.6-inch                | 1        | 0.47%   |
| Samsung Electronics SyncMaster SAM0372 1680x1050 459x296mm 21.5-inch  | 1        | 0.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 89       | 46.6%   |
| 3840x2160 (4K)     | 36       | 18.85%  |
| 2560x1440 (QHD)    | 18       | 9.42%   |
| 1366x768 (WXGA)    | 9        | 4.71%   |
| 1440x900 (WXGA+)   | 7        | 3.66%   |
| 1680x1050 (WSXGA+) | 6        | 3.14%   |
| 1280x1024 (SXGA)   | 4        | 2.09%   |
| Unknown            | 4        | 2.09%   |
| 3840x1080          | 3        | 1.57%   |
| 1360x768           | 3        | 1.57%   |
| 3440x1440          | 2        | 1.05%   |
| 2560x1080          | 2        | 1.05%   |
| 1920x1200 (WUXGA)  | 2        | 1.05%   |
| 1024x768 (XGA)     | 2        | 1.05%   |
| 5120x1440          | 1        | 0.52%   |
| 3200x1080          | 1        | 0.52%   |
| 2560x1600          | 1        | 0.52%   |
| 1400x1050          | 1        | 0.52%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 37       | 18.41%  |
| 23      | 28       | 13.93%  |
| 27      | 24       | 11.94%  |
| 21      | 23       | 11.44%  |
| Unknown | 20       | 9.95%   |
| 18      | 12       | 5.97%   |
| 31      | 10       | 4.98%   |
| 13      | 6        | 2.99%   |
| 40      | 5        | 2.49%   |
| 28      | 5        | 2.49%   |
| 84      | 4        | 1.99%   |
| 22      | 4        | 1.99%   |
| 19      | 4        | 1.99%   |
| 34      | 3        | 1.49%   |
| 15      | 3        | 1.49%   |
| 65      | 1        | 0.5%    |
| 64      | 1        | 0.5%    |
| 58      | 1        | 0.5%    |
| 57      | 1        | 0.5%    |
| 54      | 1        | 0.5%    |
| 50      | 1        | 0.5%    |
| 48      | 1        | 0.5%    |
| 32      | 1        | 0.5%    |
| 26      | 1        | 0.5%    |
| 25      | 1        | 0.5%    |
| 20      | 1        | 0.5%    |
| 17      | 1        | 0.5%    |
| 16      | 1        | 0.5%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 84       | 43.52%  |
| 401-500     | 41       | 21.24%  |
| Unknown     | 20       | 10.36%  |
| 601-700     | 16       | 8.29%   |
| 201-300     | 6        | 3.11%   |
| 1001-1500   | 6        | 3.11%   |
| 801-900     | 5        | 2.59%   |
| 701-800     | 5        | 2.59%   |
| 301-350     | 5        | 2.59%   |
| 1501-2000   | 4        | 2.07%   |
| 351-400     | 1        | 0.52%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 133      | 72.28%  |
| 16/10   | 23       | 12.5%   |
| Unknown | 19       | 10.33%  |
| 21/9    | 3        | 1.63%   |
| 6/5     | 2        | 1.09%   |
| 5/4     | 1        | 0.54%   |
| 4/3     | 1        | 0.54%   |
| 32/9    | 1        | 0.54%   |
| 0.56    | 1        | 0.54%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 73       | 36.87%  |
| 301-350        | 30       | 15.15%  |
| Unknown        | 20       | 10.1%   |
| 351-500        | 14       | 7.07%   |
| 151-200        | 14       | 7.07%   |
| 251-300        | 12       | 6.06%   |
| More than 1000 | 10       | 5.05%   |
| 141-150        | 9        | 4.55%   |
| 71-80          | 6        | 3.03%   |
| 501-1000       | 6        | 3.03%   |
| 101-110        | 3        | 1.52%   |
| 131-140        | 1        | 0.51%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 104      | 53.33%  |
| 101-120       | 39       | 20%     |
| Unknown       | 20       | 10.26%  |
| 161-240       | 17       | 8.72%   |
| 1-50          | 7        | 3.59%   |
| 121-160       | 7        | 3.59%   |
| More than 240 | 1        | 0.51%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 148      | 75.9%   |
| 2     | 29       | 14.87%  |
| 0     | 17       | 8.72%   |
| 3     | 1        | 0.51%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 114      | 40.86%  |
| Intel                                  | 108      | 38.71%  |
| TP-Link                                | 9        | 3.23%   |
| MediaTek                               | 8        | 2.87%   |
| Broadcom                               | 8        | 2.87%   |
| Qualcomm Atheros                       | 7        | 2.51%   |
| Ralink Technology                      | 5        | 1.79%   |
| Microsoft                              | 3        | 1.08%   |
| Xiaomi                                 | 1        | 0.36%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.36%   |
| SEGGER                                 | 1        | 0.36%   |
| Samsung Electronics                    | 1        | 0.36%   |
| PEAK-System Technik                    | 1        | 0.36%   |
| Nvidia                                 | 1        | 0.36%   |
| National Semiconductor                 | 1        | 0.36%   |
| Marvell Technology Group               | 1        | 0.36%   |
| Kinesis                                | 1        | 0.36%   |
| Google                                 | 1        | 0.36%   |
| D-Link System                          | 1        | 0.36%   |
| D-Link                                 | 1        | 0.36%   |
| Belkin Components                      | 1        | 0.36%   |
| ASUSTek Computer                       | 1        | 0.36%   |
| ASIX Electronics                       | 1        | 0.36%   |
| Arduino SA                             | 1        | 0.36%   |
| Aquantia                               | 1        | 0.36%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 88       | 26.11%  |
| Intel Wi-Fi 6 AX200                                                    | 18       | 5.34%   |
| Realtek RTL8125 2.5GbE Controller                                      | 14       | 4.15%   |
| Intel Ethernet Controller I225-V                                       | 14       | 4.15%   |
| Intel I211 Gigabit Network Connection                                  | 12       | 3.56%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 10       | 2.97%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 9        | 2.67%   |
| Intel Ethernet Connection (2) I219-V                                   | 8        | 2.37%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 7        | 2.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 6        | 1.78%   |
| Intel Ethernet Connection I217-LM                                      | 6        | 1.78%   |
| Intel 82574L Gigabit Network Connection                                | 5        | 1.48%   |
| Intel Wireless 7265                                                    | 4        | 1.19%   |
| Intel Ethernet Connection (17) I219-LM                                 | 4        | 1.19%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3        | 0.89%   |
| Realtek 802.11ac NIC                                                   | 3        | 0.89%   |
| Ralink MT7601U Wireless Adapter                                        | 3        | 0.89%   |
| Microsoft XBOX ACC                                                     | 3        | 0.89%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 3        | 0.89%   |
| Intel Wireless 7260                                                    | 3        | 0.89%   |
| Intel Ethernet Connection (7) I219-LM                                  | 3        | 0.89%   |
| Intel Ethernet Connection (11) I219-V                                  | 3        | 0.89%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 3        | 0.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 3        | 0.89%   |
| Intel 82579V Gigabit Network Connection                                | 3        | 0.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3        | 0.89%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 2        | 0.59%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 2        | 0.59%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 2        | 0.59%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 2        | 0.59%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 2        | 0.59%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 2        | 0.59%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 2        | 0.59%   |
| Realtek Killer E2600 GbE Controller                                    | 2        | 0.59%   |
| Ralink RT5370 Wireless Adapter                                         | 2        | 0.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2        | 0.59%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 2        | 0.59%   |
| Intel Wireless 8265 / 8275                                             | 2        | 0.59%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 2        | 0.59%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 2        | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 69       | 59.48%  |
| Realtek Semiconductor | 13       | 11.21%  |
| TP-Link               | 9        | 7.76%   |
| MediaTek              | 8        | 6.9%    |
| Ralink Technology     | 5        | 4.31%   |
| Broadcom              | 4        | 3.45%   |
| Microsoft             | 3        | 2.59%   |
| Qualcomm Atheros      | 2        | 1.72%   |
| D-Link System         | 1        | 0.86%   |
| Belkin Components     | 1        | 0.86%   |
| ASUSTek Computer      | 1        | 0.86%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                             | 18       | 15.52%  |
| Intel Alder Lake-S PCH CNVi WiFi                                | 10       | 8.62%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 9        | 7.76%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]       | 7        | 6.03%   |
| Intel Wireless 7265                                             | 4        | 3.45%   |
| Realtek 802.11ac NIC                                            | 3        | 2.59%   |
| Ralink MT7601U Wireless Adapter                                 | 3        | 2.59%   |
| Microsoft XBOX ACC                                              | 3        | 2.59%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter   | 3        | 2.59%   |
| Intel Wireless 7260                                             | 3        | 2.59%   |
| Intel Comet Lake PCH CNVi WiFi                                  | 3        | 2.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                 | 3        | 2.59%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                     | 2        | 1.72%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                    | 2        | 1.72%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]      | 2        | 1.72%   |
| Realtek RTL88x2bu [AC1200 Techkey]                              | 2        | 1.72%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter        | 2        | 1.72%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                         | 2        | 1.72%   |
| Ralink RT5370 Wireless Adapter                                  | 2        | 1.72%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                         | 2        | 1.72%   |
| Intel Wireless 8265 / 8275                                      | 2        | 1.72%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]         | 2        | 1.72%   |
| Intel Raptor Lake-S PCH CNVi WiFi                               | 2        | 1.72%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter    | 2        | 1.72%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                           | 1        | 0.86%   |
| TP-Link Archer T4U ver.3                                        | 1        | 0.86%   |
| TP-Link 802.11n NIC                                             | 1        | 0.86%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller     | 1        | 0.86%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter        | 1        | 0.86%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)       | 1        | 0.86%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter             | 1        | 0.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter      | 1        | 0.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter      | 1        | 0.86%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter   | 1        | 0.86%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter              | 1        | 0.86%   |
| MediaTek 802.11 n WLAN                                          | 1        | 0.86%   |
| Intel Wireless 3160                                             | 1        | 0.86%   |
| Intel Wi-Fi 7(802.11be) AX1775*/AX1790*/BE20*/BE401/BE1750* 2x2 | 1        | 0.86%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection   | 1        | 0.86%   |
| Intel Centrino Wireless-N 2230                                  | 1        | 0.86%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 114      | 54.55%  |
| Intel                                  | 76       | 36.36%  |
| Qualcomm Atheros                       | 5        | 2.39%   |
| Broadcom                               | 4        | 1.91%   |
| Xiaomi                                 | 1        | 0.48%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.48%   |
| Samsung Electronics                    | 1        | 0.48%   |
| Nvidia                                 | 1        | 0.48%   |
| National Semiconductor                 | 1        | 0.48%   |
| Marvell Technology Group               | 1        | 0.48%   |
| Google                                 | 1        | 0.48%   |
| D-Link                                 | 1        | 0.48%   |
| ASIX Electronics                       | 1        | 0.48%   |
| Aquantia                               | 1        | 0.48%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 88       | 40.55%  |
| Realtek RTL8125 2.5GbE Controller                                      | 14       | 6.45%   |
| Intel Ethernet Controller I225-V                                       | 14       | 6.45%   |
| Intel I211 Gigabit Network Connection                                  | 12       | 5.53%   |
| Intel Ethernet Connection (2) I219-V                                   | 8        | 3.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 6        | 2.76%   |
| Intel Ethernet Connection I217-LM                                      | 6        | 2.76%   |
| Intel 82574L Gigabit Network Connection                                | 5        | 2.3%    |
| Intel Ethernet Connection (17) I219-LM                                 | 4        | 1.84%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3        | 1.38%   |
| Intel Ethernet Connection (7) I219-LM                                  | 3        | 1.38%   |
| Intel Ethernet Connection (11) I219-V                                  | 3        | 1.38%   |
| Intel 82579V Gigabit Network Connection                                | 3        | 1.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3        | 1.38%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 2        | 0.92%   |
| Realtek Killer E2600 GbE Controller                                    | 2        | 0.92%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2        | 0.92%   |
| Intel Ethernet Connection I217-V                                       | 2        | 0.92%   |
| Intel Ethernet Connection (7) I219-V                                   | 2        | 0.92%   |
| Intel Ethernet Connection (2) I218-V                                   | 2        | 0.92%   |
| Intel Ethernet Connection (14) I219-V                                  | 2        | 0.92%   |
| Intel Ethernet Connection (12) I219-V                                  | 2        | 0.92%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1        | 0.46%   |
| Sony Ericsson Mobile AB XQ-AU52                                        | 1        | 0.46%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1        | 0.46%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1        | 0.46%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 1        | 0.46%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1        | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1        | 0.46%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1        | 0.46%   |
| Nvidia MCP65 Ethernet                                                  | 1        | 0.46%   |
| National DP83815 (MacPhyter) Ethernet Controller                       | 1        | 0.46%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 1        | 0.46%   |
| Intel I350 Gigabit Network Connection                                  | 1        | 0.46%   |
| Intel Ethernet Controller I226-V                                       | 1        | 0.46%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                          | 1        | 0.46%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1        | 0.46%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 1        | 0.46%   |
| Intel 82578DM Gigabit Network Connection                               | 1        | 0.46%   |
| Intel 82576 Gigabit Network Connection                                 | 1        | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 190      | 62.91%  |
| WiFi     | 108      | 35.76%  |
| Modem    | 3        | 0.99%   |
| Unknown  | 1        | 0.33%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 155      | 73.46%  |
| WiFi     | 56       | 26.54%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 95       | 47.98%  |
| 2     | 85       | 42.93%  |
| 3     | 7        | 3.54%   |
| 0     | 7        | 3.54%   |
| 4     | 2        | 1.01%   |
| 8     | 1        | 0.51%   |
| 7     | 1        | 0.51%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 185      | 94.87%  |
| Yes  | 10       | 5.13%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 63       | 63%     |
| Cambridge Silicon Radio         | 18       | 18%     |
| Broadcom                        | 4        | 4%      |
| Realtek Semiconductor           | 3        | 3%      |
| MediaTek                        | 3        | 3%      |
| ASUSTek Computer                | 2        | 2%      |
| TP-Link                         | 1        | 1%      |
| SINO WEALTH                     | 1        | 1%      |
| Qualcomm Atheros Communications | 1        | 1%      |
| Micro Star International        | 1        | 1%      |
| Lite-On Technology              | 1        | 1%      |
| Foxconn / Hon Hai               | 1        | 1%      |
| Apple                           | 1        | 1%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 18       | 18%     |
| Intel AX200 Bluetooth                               | 17       | 17%     |
| Intel Wireless-AC 3168 Bluetooth                    | 9        | 9%      |
| Intel AX201 Bluetooth                               | 9        | 9%      |
| Intel Bluetooth wireless interface                  | 7        | 7%      |
| Intel AX210 Bluetooth                               | 7        | 7%      |
| Intel AX211 Bluetooth                               | 6        | 6%      |
| Realtek Bluetooth Radio                             | 3        | 3%      |
| MediaTek Wireless_Device                            | 3        | 3%      |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 2%      |
| Intel Bluetooth Device                              | 2        | 2%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2        | 2%      |
| ASUS Bluetooth Radio                                | 2        | 2%      |
| TP-Link UB500 Adapter                               | 1        | 1%      |
| SINO WEALTH RK Bluetooth Keyboar                    | 1        | 1%      |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 1%      |
| Micro Star International Bluetooth Dongle           | 1        | 1%      |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1        | 1%      |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 1%      |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1        | 1%      |
| Foxconn / Hon Hai Wireless_Device                   | 1        | 1%      |
| Broadcom Bluetooth Controller                       | 1        | 1%      |
| Broadcom Bluetooth 2.0+eDR dongle                   | 1        | 1%      |
| Broadcom BCM920702 Bluetooth 4.0 Zero Touch Dongle  | 1        | 1%      |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1        | 1%      |
| Apple Bluetooth Host Controller                     | 1        | 1%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 134      | 42.54%  |
| Nvidia                                       | 78       | 24.76%  |
| AMD                                          | 66       | 20.95%  |
| C-Media Electronics                          | 10       | 3.17%   |
| Micro Star International                     | 4        | 1.27%   |
| ASUSTek Computer                             | 4        | 1.27%   |
| TX                                           | 2        | 0.63%   |
| Focusrite-Novation                           | 2        | 0.63%   |
| FiiO Electronics Technology                  | 2        | 0.63%   |
| Creative Labs                                | 2        | 0.63%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.32%   |
| XMOS                                         | 1        | 0.32%   |
| Thesycon Systemsoftware & Consulting         | 1        | 0.32%   |
| Texas Instruments                            | 1        | 0.32%   |
| SteelSeries ApS                              | 1        | 0.32%   |
| Sony                                         | 1        | 0.32%   |
| SAVITECH                                     | 1        | 0.32%   |
| Lynx                                         | 1        | 0.32%   |
| Logitech                                     | 1        | 0.32%   |
| JMTek                                        | 1        | 0.32%   |
| AudioQuest                                   | 1        | 0.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 19       | 5.08%   |
| Intel Alder Lake-S HD Audio Controller                                     | 18       | 4.81%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 17       | 4.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 15       | 4.01%   |
| AMD Family 17h/19h HD Audio Controller                                     | 15       | 4.01%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13       | 3.48%   |
| Intel 200 Series PCH HD Audio                                              | 10       | 2.67%   |
| Intel Cannon Lake PCH cAVS                                                 | 9        | 2.41%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 9        | 2.41%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 9        | 2.41%   |
| Nvidia GP106 High Definition Audio Controller                              | 8        | 2.14%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8        | 2.14%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8        | 2.14%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 8        | 2.14%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 7        | 1.87%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6        | 1.6%    |
| Nvidia GF108 High Definition Audio Controller                              | 6        | 1.6%    |
| Nvidia GA104 High Definition Audio Controller                              | 6        | 1.6%    |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 6        | 1.6%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 6        | 1.6%    |
| Nvidia TU106 High Definition Audio Controller                              | 5        | 1.34%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 5        | 1.34%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 5        | 1.34%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5        | 1.34%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5        | 1.34%   |
| Nvidia TU104 HD Audio Controller                                           | 4        | 1.07%   |
| Nvidia GP108 High Definition Audio Controller                              | 4        | 1.07%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4        | 1.07%   |
| Nvidia GM206 High Definition Audio Controller                              | 4        | 1.07%   |
| Micro Star International USB Audio                                         | 4        | 1.07%   |
| Intel Comet Lake PCH-V cAVS                                                | 4        | 1.07%   |
| ASUSTek Computer USB Audio                                                 | 4        | 1.07%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4        | 1.07%   |
| AMD Navi 10 HDMI Audio                                                     | 4        | 1.07%   |
| Nvidia TU116 High Definition Audio Controller                              | 3        | 0.8%    |
| Nvidia GP104 High Definition Audio Controller                              | 3        | 0.8%    |
| Nvidia GF106 High Definition Audio Controller                              | 3        | 0.8%    |
| Nvidia Audio device                                                        | 3        | 0.8%    |
| Nvidia AD102 High Definition Audio Controller                              | 3        | 0.8%    |
| Intel Sunrise Point-LP HD Audio                                            | 3        | 0.8%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Kingston                        | 32       | 26.45%  |
| Samsung Electronics             | 13       | 10.74%  |
| Corsair                         | 13       | 10.74%  |
| A-DATA Technology               | 13       | 10.74%  |
| Unknown                         | 8        | 6.61%   |
| SK hynix                        | 6        | 4.96%   |
| G.Skill                         | 6        | 4.96%   |
| Crucial                         | 6        | 4.96%   |
| Micron Technology               | 4        | 3.31%   |
| Team                            | 3        | 2.48%   |
| Ramaxel Technology              | 2        | 1.65%   |
| Unknown                         | 2        | 1.65%   |
| Unknown (0x0AFD)                | 1        | 0.83%   |
| Transcend                       | 1        | 0.83%   |
| Shenzhen SKIHOTAR Semiconductor | 1        | 0.83%   |
| Nanya Technology                | 1        | 0.83%   |
| KingSpec                        | 1        | 0.83%   |
| Kingmax                         | 1        | 0.83%   |
| KINGBANK                        | 1        | 0.83%   |
| Kimtigo                         | 1        | 0.83%   |
| Juhor                           | 1        | 0.83%   |
| GLOWAY                          | 1        | 0.83%   |
| Essencore Limited               | 1        | 0.83%   |
| CUSO                            | 1        | 0.83%   |
| Apacer                          | 1        | 0.83%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s             | 2        | 1.52%   |
| Kingston RAM KY7N41-MIE 8GB DIMM DDR4 2666MT/s                   | 2        | 1.52%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s              | 2        | 1.52%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s            | 2        | 1.52%   |
| Corsair RAM CMZ16GX3M2A1600C9 8GB DIMM DDR3 1600MT/s             | 2        | 1.52%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s            | 2        | 1.52%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3600MT/s            | 2        | 1.52%   |
| Corsair RAM CM4X16GC3600C18K2D 16GB DIMM DDR4 3600MT/s           | 2        | 1.52%   |
| A-DATA RAM Module 4GB DIMM DDR3 1333MT/s                         | 2        | 1.52%   |
| Unknown                                                          | 2        | 1.52%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                     | 1        | 0.76%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 1        | 0.76%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1        | 0.76%   |
| Unknown RAM Module 4GB DIMM 800MT/s                              | 1        | 0.76%   |
| Unknown RAM Module 4096MB DIMM DDR2 800MT/s                      | 1        | 0.76%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 1        | 0.76%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1        | 0.76%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                           | 1        | 0.76%   |
| Unknown (0x0AFD) RAM SED2666U1932 32GB DIMM DDR4 2667MT/s        | 1        | 0.76%   |
| Transcend RAM TS256MLQ72V6U 2GB DIMM DDR2 667MT/s                | 1        | 0.76%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 3000MT/s              | 1        | 0.76%   |
| Team RAM TEAMGROUP-UD4-2400 4GB DIMM DDR4 3007MT/s               | 1        | 0.76%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1067MT/s               | 1        | 0.76%   |
| SK hynix RAM Module 8GB DIMM DDR4 3200MT/s                       | 1        | 0.76%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s                       | 1        | 0.76%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                       | 1        | 0.76%   |
| SK hynix RAM HMCG66MEBUA084N 8GB DIMM DDR5 4800MT/s              | 1        | 0.76%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 1        | 0.76%   |
| Shenzhen SKIHOTAR RAM SKIHOTAR-32GB-2666 32GB DIMM DDR4 2667MT/s | 1        | 0.76%   |
| Samsung RAM Module 3GB Row Of Chips 6400MT/s                     | 1        | 0.76%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 1        | 0.76%   |
| Samsung RAM M471B1G73DH0-YK0 8GB SODIMM DDR3 1600MT/s            | 1        | 0.76%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1        | 0.76%   |
| Samsung RAM M471A1G43EB1-CPB 8GB SODIMM DDR4 2133MT/s            | 1        | 0.76%   |
| Samsung RAM M393B2G70QH0-YK0 16GB DIMM DDR3 1600MT/s             | 1        | 0.76%   |
| Samsung RAM M393B2G70EB0-YK0 16GB DIMM DDR3 1600MT/s             | 1        | 0.76%   |
| Samsung RAM M393B2G70DB0-YK0 16GB DIMM DDR3 1600MT/s             | 1        | 0.76%   |
| Samsung RAM M391A1K43BB1-CRC 8GB DIMM DDR4 2400MT/s              | 1        | 0.76%   |
| Samsung RAM M378B5773DH0-CK0 2GB DIMM DDR3 1600MT/s              | 1        | 0.76%   |
| Samsung RAM M378B5773CH0-CK0 2GB DIMM DDR3 1600MT/s              | 1        | 0.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 71       | 62.28%  |
| DDR3    | 21       | 18.42%  |
| DDR5    | 13       | 11.4%   |
| Unknown | 4        | 3.51%   |
| SDRAM   | 3        | 2.63%   |
| DDR2    | 2        | 1.75%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 97       | 85.09%  |
| SODIMM       | 16       | 14.04%  |
| Row Of Chips | 1        | 0.88%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 40       | 33.61%  |
| 8192  | 30       | 25.21%  |
| 32768 | 19       | 15.97%  |
| 4096  | 19       | 15.97%  |
| 2048  | 9        | 7.56%   |
| 3072  | 1        | 0.84%   |
| 1024  | 1        | 0.84%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 20       | 16.95%  |
| 2667    | 13       | 11.02%  |
| 1600    | 13       | 11.02%  |
| 2400    | 10       | 8.47%   |
| 3600    | 8        | 6.78%   |
| 1333    | 8        | 6.78%   |
| 4800    | 6        | 5.08%   |
| 2666    | 5        | 4.24%   |
| 2133    | 5        | 4.24%   |
| 3000    | 4        | 3.39%   |
| 800     | 3        | 2.54%   |
| 6000    | 2        | 1.69%   |
| 5600    | 2        | 1.69%   |
| 3933    | 2        | 1.69%   |
| 3866    | 2        | 1.69%   |
| 7000    | 1        | 0.85%   |
| 6400    | 1        | 0.85%   |
| 5808    | 1        | 0.85%   |
| 5200    | 1        | 0.85%   |
| 4199    | 1        | 0.85%   |
| 4000    | 1        | 0.85%   |
| 3800    | 1        | 0.85%   |
| 3733    | 1        | 0.85%   |
| 3466    | 1        | 0.85%   |
| 3400    | 1        | 0.85%   |
| 3007    | 1        | 0.85%   |
| 1866    | 1        | 0.85%   |
| 1800    | 1        | 0.85%   |
| 667     | 1        | 0.85%   |
| Unknown | 1        | 0.85%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 1        | 25%     |
| Fuji Xerox         | 1        | 25%     |
| Canon              | 1        | 25%     |
| Brother Industries | 1        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| HP HP LaserJet P2035        | 1        | 25%     |
| Fuji Xerox DocuPrint P158 b | 1        | 25%     |
| Canon MP160                 | 1        | 25%     |
| Brother HL-L2320D series    | 1        | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| Mustek Systems | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Mustek Systems ScanExpress 1200 UB | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 9        | 40.91%  |
| Microdia                      | 2        | 9.09%   |
| eMPIA Technology              | 2        | 9.09%   |
| Z-Star Microelectronics       | 1        | 4.55%   |
| Sunplus Innovation Technology | 1        | 4.55%   |
| SN0002                        | 1        | 4.55%   |
| Nokia Mobile Phones           | 1        | 4.55%   |
| Google                        | 1        | 4.55%   |
| Essential Products            | 1        | 4.55%   |
| Cubeternet                    | 1        | 4.55%   |
| ARC International             | 1        | 4.55%   |
| A4Tech                        | 1        | 4.55%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech Webcam C270                    | 4        | 17.39%  |
| Logitech BRIO Ultra HD Webcam           | 2        | 8.7%    |
| Logitech B525 HD Webcam                 | 2        | 8.7%    |
| eMPIA M035 Compact Web Cam              | 2        | 8.7%    |
| Z-Star Sirius USB2.0 Camera             | 1        | 4.35%   |
| Sunplus SPCA2650 PC Camera              | 1        | 4.35%   |
| SN0002 2K USB Camera                    | 1        | 4.35%   |
| Nokia Mobile Phones Lumia 640 Phone     | 1        | 4.35%   |
| Microdia USB 2.0 Camera                 | 1        | 4.35%   |
| Microdia HP Integrated Webcam           | 1        | 4.35%   |
| Logitech C920 PRO HD Webcam             | 1        | 4.35%   |
| Google Nexus/Pixel Device (PTP + debug) | 1        | 4.35%   |
| Google Nexus/Pixel Device (MTP + debug) | 1        | 4.35%   |
| Essential Products PH-1                 | 1        | 4.35%   |
| Cubeternet GL-UPC822 UVC WebCam         | 1        | 4.35%   |
| ARC International Camera                | 1        | 4.35%   |
| A4Tech FHD 1080P PC Camera              | 1        | 4.35%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| LighTuning Fingerprint Sensor | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Advanced Card Systems | 2        | 50%     |
| Yubico.com            | 1        | 25%     |
| Clay Logic            | 1        | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Advanced Card Systems ACR1281 1S Dual Reader | 2        | 50%     |
| Yubico.com Yubikey 4/5 U2F+CCID              | 1        | 25%     |
| Clay Logic Nitrokey HSM                      | 1        | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 163      | 81.09%  |
| 1     | 30       | 14.93%  |
| 2     | 6        | 2.99%   |
| 4     | 2        | 1%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 16       | 32.65%  |
| Net/wireless             | 14       | 28.57%  |
| Communication controller | 7        | 14.29%  |
| Unassigned class         | 3        | 6.12%   |
| Chipcard                 | 3        | 6.12%   |
| Storage/ata              | 1        | 2.04%   |
| Sound                    | 1        | 2.04%   |
| Net/ethernet             | 1        | 2.04%   |
| Fingerprint reader       | 1        | 2.04%   |
| Camera                   | 1        | 2.04%   |
| Bluetooth                | 1        | 2.04%   |

