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

Total: 284

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 22.04      | 19       | 9.6%    |
| Ubuntu 20.04      | 18       | 9.09%   |
| Arch Rolling      | 14       | 7.07%   |
| Ubuntu 18.04      | 13       | 6.57%   |
| OpenMandriva 4.2  | 10       | 5.05%   |
| Debian 11         | 10       | 5.05%   |
| Pop!_OS 22.04     | 8        | 4.04%   |
| Ubuntu 16.04      | 6        | 3.03%   |
| OpenMandriva 4.3  | 5        | 2.53%   |
| KDE neon 20.04    | 5        | 2.53%   |
| Ubuntu 19.10      | 4        | 2.02%   |
| Fedora 35         | 4        | 2.02%   |
| Debian 12         | 4        | 2.02%   |
| Ubuntu 23.04      | 3        | 1.52%   |
| Ubuntu 20.10      | 3        | 1.52%   |
| ArcoLinux Rolling | 3        | 1.52%   |
| Ubuntu 23.10      | 2        | 1.01%   |
| Ubuntu 21.10      | 2        | 1.01%   |
| Ubuntu 19.04      | 2        | 1.01%   |
| Slackware 15.0    | 2        | 1.01%   |
| PostmarketOS Edge | 2        | 1.01%   |
| Pop!_OS 20.10     | 2        | 1.01%   |
| Parrot 4.9        | 2        | 1.01%   |
| Manjaro 23.1.0    | 2        | 1.01%   |
| Gentoo 2.7        | 2        | 1.01%   |
| Fedora 38         | 2        | 1.01%   |
| Fedora 31         | 2        | 1.01%   |
| Elementary 5.1.7  | 2        | 1.01%   |
| CentOS 8          | 2        | 1.01%   |
| Zorin 15          | 1        | 0.51%   |
| Xubuntu 18.04     | 1        | 0.51%   |
| Ubuntu MATE 20.04 | 1        | 0.51%   |
| Ubuntu 22.10      | 1        | 0.51%   |
| Ubuntu 21.04      | 1        | 0.51%   |
| SteamOS 3.3       | 1        | 0.51%   |
| Slackware 14.2    | 1        | 0.51%   |
| ROSA R8.1         | 1        | 0.51%   |
| Rocky Linux 9.2   | 1        | 0.51%   |
| Pop!_OS 21.04     | 1        | 0.51%   |
| OpenMandriva 4.50 | 1        | 0.51%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 69       | 36.32%  |
| OpenMandriva | 17       | 8.95%   |
| Debian       | 15       | 7.89%   |
| Arch         | 15       | 7.89%   |
| Fedora       | 13       | 6.84%   |
| Pop!_OS      | 11       | 5.79%   |
| Manjaro      | 6        | 3.16%   |
| KDE neon     | 5        | 2.63%   |
| Slackware    | 3        | 1.58%   |
| Linux Mint   | 3        | 1.58%   |
| Kubuntu      | 3        | 1.58%   |
| Gentoo       | 3        | 1.58%   |
| Elementary   | 3        | 1.58%   |
| CentOS       | 3        | 1.58%   |
| ArcoLinux    | 3        | 1.58%   |
| PostmarketOS | 2        | 1.05%   |
| Parrot       | 2        | 1.05%   |
| EndeavourOS  | 2        | 1.05%   |
| Clear Linux  | 2        | 1.05%   |
| Zorin        | 1        | 0.53%   |
| Xubuntu      | 1        | 0.53%   |
| Ubuntu MATE  | 1        | 0.53%   |
| SteamOS      | 1        | 0.53%   |
| ROSA         | 1        | 0.53%   |
| Rocky Linux  | 1        | 0.53%   |
| Lubuntu      | 1        | 0.53%   |
| Kali         | 1        | 0.53%   |
| Artix        | 1        | 0.53%   |
| Alpine       | 1        | 0.53%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.14-desktop-1omv4002 | 9        | 4.02%   |
| 4.15.0-142-generic       | 6        | 2.68%   |
| 5.16.7-desktop-1omv4003  | 5        | 2.23%   |
| 5.4.0-42-generic         | 3        | 1.34%   |
| 5.15.0-46-generic        | 3        | 1.34%   |
| 6.7.0-zen3-1.1-zen       | 2        | 0.89%   |
| 6.5.0-14-generic         | 2        | 0.89%   |
| 6.2.0-39-generic         | 2        | 0.89%   |
| 6.2.0-33-generic         | 2        | 0.89%   |
| 6.2.0-26-generic         | 2        | 0.89%   |
| 6.2.0-20-generic         | 2        | 0.89%   |
| 6.1.1-arch1-1            | 2        | 0.89%   |
| 6.1.0-9-amd64            | 2        | 0.89%   |
| 5.5.0-1parrot1-amd64     | 2        | 0.89%   |
| 5.4.0-56-generic         | 2        | 0.89%   |
| 5.4.0-47-generic         | 2        | 0.89%   |
| 5.4.0-33-generic         | 2        | 0.89%   |
| 5.4.0-109-generic        | 2        | 0.89%   |
| 5.3.0-46-generic         | 2        | 0.89%   |
| 5.19.0-76051900-generic  | 2        | 0.89%   |
| 5.19.0-43-generic        | 2        | 0.89%   |
| 5.13.0-35-generic        | 2        | 0.89%   |
| 5.11.0-43-generic        | 2        | 0.89%   |
| 5.0.0-25-generic         | 2        | 0.89%   |
| 4.15.0-88-generic        | 2        | 0.89%   |
| 6.6.7-1-MANJARO          | 1        | 0.45%   |
| 6.6.4-1389.native        | 1        | 0.45%   |
| 6.6.11-200.fc39.x86_64   | 1        | 0.45%   |
| 6.6.10-zen1-1-zen        | 1        | 0.45%   |
| 6.5.6-76060506-generic   | 1        | 0.45%   |
| 6.5.3-zen1-1-zen         | 1        | 0.45%   |
| 6.5.11-1-MANJARO         | 1        | 0.45%   |
| 6.5.0-9-generic          | 1        | 0.45%   |
| 6.4.5-arch1-1            | 1        | 0.45%   |
| 6.4.3-arch1-2            | 1        | 0.45%   |
| 6.4.11-desktop-1omv2390  | 1        | 0.45%   |
| 6.3.9-arch1-1            | 1        | 0.45%   |
| 6.3.8-200.fc38.x86_64    | 1        | 0.45%   |
| 6.2.9-300.fc38.x86_64    | 1        | 0.45%   |
| 6.2.9-060209-generic     | 1        | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 20       | 9.52%   |
| 5.15.0  | 12       | 5.71%   |
| 4.15.0  | 12       | 5.71%   |
| 6.2.0   | 10       | 4.76%   |
| 5.8.0   | 9        | 4.29%   |
| 5.10.14 | 9        | 4.29%   |
| 5.19.0  | 8        | 3.81%   |
| 6.1.0   | 7        | 3.33%   |
| 5.3.0   | 7        | 3.33%   |
| 5.13.0  | 7        | 3.33%   |
| 5.11.0  | 7        | 3.33%   |
| 5.10.0  | 6        | 2.86%   |
| 5.16.7  | 5        | 2.38%   |
| 5.0.0   | 5        | 2.38%   |
| 6.5.0   | 3        | 1.43%   |
| 6.1.1   | 3        | 1.43%   |
| 5.17.5  | 3        | 1.43%   |
| 4.18.0  | 3        | 1.43%   |
| 6.7.0   | 2        | 0.95%   |
| 6.2.9   | 2        | 0.95%   |
| 6.0.0   | 2        | 0.95%   |
| 5.5.0   | 2        | 0.95%   |
| 5.14.14 | 2        | 0.95%   |
| 6.6.7   | 1        | 0.48%   |
| 6.6.4   | 1        | 0.48%   |
| 6.6.11  | 1        | 0.48%   |
| 6.6.10  | 1        | 0.48%   |
| 6.5.6   | 1        | 0.48%   |
| 6.5.3   | 1        | 0.48%   |
| 6.5.11  | 1        | 0.48%   |
| 6.4.5   | 1        | 0.48%   |
| 6.4.3   | 1        | 0.48%   |
| 6.4.11  | 1        | 0.48%   |
| 6.3.9   | 1        | 0.48%   |
| 6.3.8   | 1        | 0.48%   |
| 6.2.8   | 1        | 0.48%   |
| 6.2.6   | 1        | 0.48%   |
| 6.2.16  | 1        | 0.48%   |
| 6.1.5   | 1        | 0.48%   |
| 6.1.39  | 1        | 0.48%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 20       | 9.76%   |
| 5.15    | 19       | 9.27%   |
| 5.10    | 19       | 9.27%   |
| 6.2     | 14       | 6.83%   |
| 4.15    | 12       | 5.85%   |
| 6.1     | 11       | 5.37%   |
| 5.8     | 11       | 5.37%   |
| 5.19    | 10       | 4.88%   |
| 5.13    | 9        | 4.39%   |
| 5.16    | 8        | 3.9%    |
| 5.11    | 8        | 3.9%    |
| 5.3     | 7        | 3.41%   |
| 6.5     | 6        | 2.93%   |
| 5.17    | 5        | 2.44%   |
| 5.0     | 5        | 2.44%   |
| 6.6     | 4        | 1.95%   |
| 6.0     | 4        | 1.95%   |
| 6.4     | 3        | 1.46%   |
| 5.9     | 3        | 1.46%   |
| 5.5     | 3        | 1.46%   |
| 5.18    | 3        | 1.46%   |
| 5.14    | 3        | 1.46%   |
| 4.18    | 3        | 1.46%   |
| 6.7     | 2        | 0.98%   |
| 6.3     | 2        | 0.98%   |
| 5.7     | 2        | 0.98%   |
| 5.6     | 2        | 0.98%   |
| 5.12    | 2        | 0.98%   |
| 4.9     | 1        | 0.49%   |
| 4.4     | 1        | 0.49%   |
| 4.20    | 1        | 0.49%   |
| 4.17    | 1        | 0.49%   |
| 3.10    | 1        | 0.49%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 178      | 97.27%  |
| i686    | 2        | 1.09%   |
| aarch64 | 2        | 1.09%   |
| riscv64 | 1        | 0.55%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 83       | 43.23%  |
| KDE5          | 40       | 20.83%  |
| Unknown       | 35       | 18.23%  |
| XFCE          | 8        | 4.17%   |
| X-Cinnamon    | 4        | 2.08%   |
| KDE           | 4        | 2.08%   |
| Pantheon      | 3        | 1.56%   |
| MATE          | 3        | 1.56%   |
| sway          | 2        | 1.04%   |
| openbox       | 1        | 0.52%   |
| LXDE          | 1        | 0.52%   |
| KDE6          | 1        | 0.52%   |
| KDE4          | 1        | 0.52%   |
| ICEWM         | 1        | 0.52%   |
| i3            | 1        | 0.52%   |
| Hyprland      | 1        | 0.52%   |
| GNOME Classic | 1        | 0.52%   |
| Deepin        | 1        | 0.52%   |
| awesome       | 1        | 0.52%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 133      | 68.21%  |
| Wayland | 41       | 21.03%  |
| Unknown | 12       | 6.15%   |
| Tty     | 9        | 4.62%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 82       | 42.71%  |
| SDDM    | 39       | 20.31%  |
| GDM3    | 35       | 18.23%  |
| LightDM | 15       | 7.81%   |
| GDM     | 14       | 7.29%   |
| TDM     | 2        | 1.04%   |
| Ly      | 2        | 1.04%   |
| XDM     | 1        | 0.52%   |
| KDM     | 1        | 0.52%   |
| GREETD  | 1        | 0.52%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 67       | 35.45%  |
| en_HK   | 58       | 30.69%  |
| zh_CN   | 20       | 10.58%  |
| Unknown | 14       | 7.41%   |
| zh_TW   | 13       | 6.88%   |
| en_GB   | 7        | 3.7%    |
| zh_HK   | 4        | 2.12%   |
| C       | 4        | 2.12%   |
| en_AU   | 2        | 1.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 106      | 56.38%  |
| BIOS | 82       | 43.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 127      | 67.2%   |
| Btrfs   | 21       | 11.11%  |
| Tmpfs   | 16       | 8.47%   |
| Overlay | 10       | 5.29%   |
| Xfs     | 7        | 3.7%    |
| Zfs     | 3        | 1.59%   |
| Unknown | 2        | 1.06%   |
| F2fs    | 1        | 0.53%   |
| Ext3    | 1        | 0.53%   |
| Ext2    | 1        | 0.53%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 98       | 52.41%  |
| Unknown | 72       | 38.5%   |
| MBR     | 17       | 9.09%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 154      | 81.05%  |
| Yes       | 36       | 18.95%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 130      | 68.78%  |
| Yes       | 59       | 31.22%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 45       | 24.59%  |
| MSI                                  | 31       | 16.94%  |
| Gigabyte Technology                  | 30       | 16.39%  |
| ASRock                               | 19       | 10.38%  |
| Dell                                 | 12       | 6.56%   |
| Hewlett-Packard                      | 9        | 4.92%   |
| Lenovo                               | 8        | 4.37%   |
| Unknown                              | 8        | 4.37%   |
| Intel                                | 7        | 3.83%   |
| Supermicro                           | 2        | 1.09%   |
| Acer                                 | 2        | 1.09%   |
| Soyo                                 | 1        | 0.55%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.55%   |
| Seco                                 | 1        | 0.55%   |
| Huanan                               | 1        | 0.55%   |
| HPE                                  | 1        | 0.55%   |
| Hardkernel                           | 1        | 0.55%   |
| Foxconn                              | 1        | 0.55%   |
| Biostar                              | 1        | 0.55%   |
| BESSTAR Tech                         | 1        | 0.55%   |
| AZW                                  | 1        | 0.55%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Unknown                                    | 8        | 4.37%   |
| Intel SKYBAY                               | 4        | 2.19%   |
| ASUS All Series                            | 4        | 2.19%   |
| MSI MS-7C94                                | 3        | 1.64%   |
| ASUS H110I-PLUS                            | 3        | 1.64%   |
| MSI MS-7D42                                | 2        | 1.09%   |
| MSI MS-7C02                                | 2        | 1.09%   |
| MSI MS-7B93                                | 2        | 1.09%   |
| MSI MS-7B89                                | 2        | 1.09%   |
| HP ProDesk 600 G1 SFF                      | 2        | 1.09%   |
| Gigabyte X570 AORUS ELITE                  | 2        | 1.09%   |
| ASUS Z8NA-D6                               | 2        | 1.09%   |
| ASUS VM65                                  | 2        | 1.09%   |
| ASUS VM62                                  | 2        | 1.09%   |
| ASRock H410M-ITX/ac                        | 2        | 1.09%   |
| ASRock H410M-HDV                           | 2        | 1.09%   |
| Supermicro PIO-617R-TLN4F+-ST031           | 1        | 0.55%   |
| Supermicro C2SBC-Q                         | 1        | 0.55%   |
| Soyo SY-A68M FS V2.0                       | 1        | 0.55%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1        | 0.55%   |
| Seco C40                                   | 1        | 0.55%   |
| MSI Pro 3130 Small Form Factor PC          | 1        | 0.55%   |
| MSI MS-7E02                                | 1        | 0.55%   |
| MSI MS-7D32                                | 1        | 0.55%   |
| MSI MS-7D31                                | 1        | 0.55%   |
| MSI MS-7C95                                | 1        | 0.55%   |
| MSI MS-7C52                                | 1        | 0.55%   |
| MSI MS-7C34                                | 1        | 0.55%   |
| MSI MS-7B78                                | 1        | 0.55%   |
| MSI MS-7B53                                | 1        | 0.55%   |
| MSI MS-7A70                                | 1        | 0.55%   |
| MSI MS-7A40                                | 1        | 0.55%   |
| MSI MS-7A38                                | 1        | 0.55%   |
| MSI MS-7918                                | 1        | 0.55%   |
| MSI MS-7851                                | 1        | 0.55%   |
| MSI MS-7817                                | 1        | 0.55%   |
| MSI MS-7808                                | 1        | 0.55%   |
| MSI MS-7798                                | 1        | 0.55%   |
| MSI MS-7680                                | 1        | 0.55%   |
| MSI MS-7599                                | 1        | 0.55%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS PRIME                                 | 9        | 4.92%   |
| Unknown                                    | 8        | 4.37%   |
| Dell OptiPlex                              | 6        | 3.28%   |
| ASUS TUF                                   | 6        | 3.28%   |
| ASUS ROG                                   | 6        | 3.28%   |
| Lenovo ThinkCentre                         | 5        | 2.73%   |
| Intel SKYBAY                               | 4        | 2.19%   |
| ASUS All                                   | 4        | 2.19%   |
| MSI MS-7C94                                | 3        | 1.64%   |
| HP ProDesk                                 | 3        | 1.64%   |
| Gigabyte X570                              | 3        | 1.64%   |
| Dell Precision                             | 3        | 1.64%   |
| ASUS H110I-PLUS                            | 3        | 1.64%   |
| MSI MS-7D42                                | 2        | 1.09%   |
| MSI MS-7C02                                | 2        | 1.09%   |
| MSI MS-7B93                                | 2        | 1.09%   |
| MSI MS-7B89                                | 2        | 1.09%   |
| HP EliteDesk                               | 2        | 1.09%   |
| Gigabyte B450                              | 2        | 1.09%   |
| Dell Inspiron                              | 2        | 1.09%   |
| ASUS Z8NA-D6                               | 2        | 1.09%   |
| ASUS VM65                                  | 2        | 1.09%   |
| ASUS VM62                                  | 2        | 1.09%   |
| ASRock H410M-ITX                           | 2        | 1.09%   |
| ASRock H410M-HDV                           | 2        | 1.09%   |
| Supermicro PIO-617R-TLN4F+-ST031           | 1        | 0.55%   |
| Supermicro C2SBC-Q                         | 1        | 0.55%   |
| Soyo SY-A68M                               | 1        | 0.55%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1        | 0.55%   |
| Seco C40                                   | 1        | 0.55%   |
| MSI Pro                                    | 1        | 0.55%   |
| MSI MS-7E02                                | 1        | 0.55%   |
| MSI MS-7D32                                | 1        | 0.55%   |
| MSI MS-7D31                                | 1        | 0.55%   |
| MSI MS-7C95                                | 1        | 0.55%   |
| MSI MS-7C52                                | 1        | 0.55%   |
| MSI MS-7C34                                | 1        | 0.55%   |
| MSI MS-7B78                                | 1        | 0.55%   |
| MSI MS-7B53                                | 1        | 0.55%   |
| MSI MS-7A70                                | 1        | 0.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 20       | 10.93%  |
| 2020    | 17       | 9.29%   |
| 2019    | 16       | 8.74%   |
| 2021    | 15       | 8.2%    |
| 2014    | 15       | 8.2%    |
| 2022    | 13       | 7.1%    |
| 2016    | 13       | 7.1%    |
| 2013    | 13       | 7.1%    |
| 2010    | 11       | 6.01%   |
| 2017    | 10       | 5.46%   |
| 2015    | 8        | 4.37%   |
| 2023    | 7        | 3.83%   |
| 2011    | 7        | 3.83%   |
| 2012    | 6        | 3.28%   |
| 2008    | 5        | 2.73%   |
| 2009    | 3        | 1.64%   |
| Unknown | 3        | 1.64%   |
| 2007    | 1        | 0.55%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 183      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 177      | 96.72%  |
| Enabled  | 6        | 3.28%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 183      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 43       | 22.87%  |
| 32.01-64.0  | 36       | 19.15%  |
| 8.01-16.0   | 33       | 17.55%  |
| 64.01-256.0 | 23       | 12.23%  |
| 3.01-4.0    | 21       | 11.17%  |
| 4.01-8.0    | 20       | 10.64%  |
| 24.01-32.0  | 8        | 4.26%   |
| 1.01-2.0    | 2        | 1.06%   |
| 2.01-3.0    | 1        | 0.53%   |
| 0.51-1.0    | 1        | 0.53%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 53       | 25.85%  |
| 2.01-3.0   | 45       | 21.95%  |
| 4.01-8.0   | 39       | 19.02%  |
| 3.01-4.0   | 24       | 11.71%  |
| 8.01-16.0  | 17       | 8.29%   |
| 0.51-1.0   | 11       | 5.37%   |
| 16.01-24.0 | 7        | 3.41%   |
| 0.01-0.5   | 4        | 1.95%   |
| 32.01-64.0 | 3        | 1.46%   |
| 24.01-32.0 | 1        | 0.49%   |
| Unknown    | 1        | 0.49%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 79       | 40.93%  |
| 2      | 52       | 26.94%  |
| 3      | 33       | 17.1%   |
| 5      | 10       | 5.18%   |
| 4      | 9        | 4.66%   |
| 6      | 3        | 1.55%   |
| 0      | 3        | 1.55%   |
| 9      | 2        | 1.04%   |
| 11     | 1        | 0.52%   |
| 7      | 1        | 0.52%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 135      | 73.37%  |
| Yes       | 49       | 26.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 178      | 97.27%  |
| No        | 5        | 2.73%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 102      | 54.26%  |
| No        | 86       | 45.74%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 97       | 51.6%   |
| Yes       | 91       | 48.4%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Hong Kong | 183      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Central          | 106      | 53.81%  |
| Kowloon          | 12       | 6.09%   |
| Tuen Mun         | 9        | 4.57%   |
| Hong Kong        | 9        | 4.57%   |
| Wanchai          | 5        | 2.54%   |
| Tseung Kwan O    | 4        | 2.03%   |
| Ngau Wu Tok      | 4        | 2.03%   |
| Yuen Long        | 3        | 1.52%   |
| To Kwa Wan       | 3        | 1.52%   |
| Tai Po           | 3        | 1.52%   |
| Shatin           | 3        | 1.52%   |
| Ma On Shan Tsuen | 3        | 1.52%   |
| Hung Hom         | 3        | 1.52%   |
| Tsimshatsui      | 2        | 1.02%   |
| Quarry Bay       | 2        | 1.02%   |
| Kwu Tung         | 2        | 1.02%   |
| Kwai Chung       | 2        | 1.02%   |
| Ho Man Tin       | 2        | 1.02%   |
| Cheung Sha Lan   | 2        | 1.02%   |
| Chai Wan         | 2        | 1.02%   |
| Wong Tai Sin     | 1        | 0.51%   |
| Tung Chung       | 1        | 0.51%   |
| Tsuen Wan        | 1        | 0.51%   |
| Tai Wan To       | 1        | 0.51%   |
| Tai Kok Tsui     | 1        | 0.51%   |
| Sheung Shui      | 1        | 0.51%   |
| Sham Shui Po     | 1        | 0.51%   |
| Sha Tin Wai      | 1        | 0.51%   |
| Sai Kung         | 1        | 0.51%   |
| North Point      | 1        | 0.51%   |
| Ma Wan           | 1        | 0.51%   |
| Ma On Shan       | 1        | 0.51%   |
| Lai Chi Kok      | 1        | 0.51%   |
| Kwun Hang        | 1        | 0.51%   |
| Kowloon Bay      | 1        | 0.51%   |
| Fo Tan           | 1        | 0.51%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 50       | 74     | 14.62%  |
| WDC                         | 45       | 78     | 13.16%  |
| Samsung Electronics         | 30       | 49     | 8.77%   |
| Toshiba                     | 25       | 38     | 7.31%   |
| Sandisk                     | 18       | 20     | 5.26%   |
| Kingston                    | 18       | 23     | 5.26%   |
| A-DATA Technology           | 15       | 21     | 4.39%   |
| Crucial                     | 12       | 19     | 3.51%   |
| Hitachi                     | 9        | 18     | 2.63%   |
| Silicon Motion              | 8        | 11     | 2.34%   |
| SK hynix                    | 6        | 11     | 1.75%   |
| HGST                        | 6        | 7      | 1.75%   |
| Unknown                     | 6        | 6      | 1.75%   |
| Unknown                     | 5        | 5      | 1.46%   |
| KIOXIA                      | 5        | 6      | 1.46%   |
| Intel                       | 5        | 16     | 1.46%   |
| Transcend                   | 4        | 5      | 1.17%   |
| Phison                      | 4        | 7      | 1.17%   |
| LITEON                      | 4        | 4      | 1.17%   |
| Fujitsu                     | 4        | 9      | 1.17%   |
| Plextor                     | 3        | 3      | 0.88%   |
| Netac                       | 3        | 3      | 0.88%   |
| MAXIO Technology (Hangzhou) | 3        | 4      | 0.88%   |
| JMicron Technology          | 3        | 6      | 0.88%   |
| Hikvision                   | 3        | 3      | 0.88%   |
| Gigabyte Technology         | 3        | 6      | 0.88%   |
| DOGGO                       | 3        | 3      | 0.88%   |
| ZHITAI                      | 2        | 4      | 0.58%   |
| Team                        | 2        | 2      | 0.58%   |
| SPCC                        | 2        | 2      | 0.58%   |
| Micron/Crucial Technology   | 2        | 2      | 0.58%   |
| Lite-On                     | 2        | 4      | 0.58%   |
| KIOXIA-EXCERIA              | 2        | 3      | 0.58%   |
| ADATA Technology            | 2        | 4      | 0.58%   |
| Yangtze Memory Technologies | 1        | 1      | 0.29%   |
| XPG                         | 1        | 1      | 0.29%   |
| WXC-R1                      | 1        | 1      | 0.29%   |
| tigo                        | 1        | 1      | 0.29%   |
| Teclast                     | 1        | 1      | 0.29%   |
| ShiJi                       | 1        | 1      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB               | 6        | 1.58%   |
| Unknown                              | 6        | 1.58%   |
| Seagate ST500DM002-1BD142 500GB      | 5        | 1.32%   |
| Samsung SSD 860 EVO 1TB              | 5        | 1.32%   |
| A-DATA SP550 240GB SSD               | 5        | 1.32%   |
| WDC WD10EZEX-08WN4A0 1TB             | 4        | 1.06%   |
| Toshiba DT01ACA050 500GB             | 4        | 1.06%   |
| Kingston SA400S37480G 480GB SSD      | 4        | 1.06%   |
| WDC WD30EZRX-00D8PB0 3TB             | 3        | 0.79%   |
| Toshiba DT01ACA300 3TB               | 3        | 0.79%   |
| Toshiba DT01ACA200 2TB               | 3        | 0.79%   |
| Seagate ST4000DM004-2CV104 4TB       | 3        | 0.79%   |
| Seagate ST3500413AS 500GB            | 3        | 0.79%   |
| Seagate ST2000DM008-2FR102 2TB       | 3        | 0.79%   |
| SanDisk NVMe SSD Drive 1TB           | 3        | 0.79%   |
| KIOXIA NVMe SSD 500GB                | 3        | 0.79%   |
| Kingston SA400S37960G 960GB SSD      | 3        | 0.79%   |
| JMicron Generic 8GB                  | 3        | 0.79%   |
| Fujitsu F300 480GB                   | 3        | 0.79%   |
| DOGGO DQ-60G SSD                     | 3        | 0.79%   |
| Crucial CT500MX500SSD1 500GB         | 3        | 0.79%   |
| WDC WDS200T2B0A 2TB SSD              | 2        | 0.53%   |
| Toshiba MG05ACA800E 8TB              | 2        | 0.53%   |
| SK hynix SC311 SATA 128GB SSD        | 2        | 0.53%   |
| SK hynix BC711 NVMe 256GB            | 2        | 0.53%   |
| Silicon Motion NVMe SSD Drive 512GB  | 2        | 0.53%   |
| Silicon Motion NVMe SSD Drive 1024GB | 2        | 0.53%   |
| Seagate ST3500418AS 500GB            | 2        | 0.53%   |
| Seagate ST3250318AS 250GB            | 2        | 0.53%   |
| Seagate ST3250310AS 250GB            | 2        | 0.53%   |
| Seagate ST320LT007-9ZV142 320GB      | 2        | 0.53%   |
| Seagate ST3160815AS 160GB            | 2        | 0.53%   |
| Seagate ST2000DM001-1CH164 2TB       | 2        | 0.53%   |
| Seagate ST1000DM010-2EP102 1TB       | 2        | 0.53%   |
| Seagate ST1000DM003-1SB102 1TB       | 2        | 0.53%   |
| Seagate ST1000DM003-1ER162 1TB       | 2        | 0.53%   |
| Sandisk WD_BLACK SN770 1TB           | 2        | 0.53%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB | 2        | 0.53%   |
| SanDisk SDSSDX120GG25 120GB          | 2        | 0.53%   |
| Samsung SSD 970 EVO Plus 1TB         | 2        | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Desktops | Drives | Percent |
|--------------------|----------|--------|---------|
| Seagate            | 49       | 73     | 37.98%  |
| WDC                | 33       | 62     | 25.58%  |
| Toshiba            | 25       | 38     | 19.38%  |
| Hitachi            | 9        | 18     | 6.98%   |
| HGST               | 6        | 7      | 4.65%   |
| JMicron Technology | 3        | 6      | 2.33%   |
| Unknown            | 1        | 1      | 0.78%   |
| Maxtor             | 1        | 1      | 0.78%   |
| HGST HTS           | 1        | 1      | 0.78%   |
| Fujitsu            | 1        | 1      | 0.78%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 17       | 28     | 16.35%  |
| Kingston            | 12       | 17     | 11.54%  |
| A-DATA Technology   | 12       | 18     | 11.54%  |
| Crucial             | 8        | 15     | 7.69%   |
| WDC                 | 7        | 7      | 6.73%   |
| SanDisk             | 6        | 6      | 5.77%   |
| Transcend           | 4        | 5      | 3.85%   |
| Netac               | 3        | 3      | 2.88%   |
| LITEON              | 3        | 3      | 2.88%   |
| Fujitsu             | 3        | 8      | 2.88%   |
| DOGGO               | 3        | 3      | 2.88%   |
| Team                | 2        | 2      | 1.92%   |
| SPCC                | 2        | 2      | 1.92%   |
| SK hynix            | 2        | 6      | 1.92%   |
| Plextor             | 2        | 2      | 1.92%   |
| ZHITAI              | 1        | 1      | 0.96%   |
| tigo                | 1        | 1      | 0.96%   |
| ShiJi               | 1        | 1      | 0.96%   |
| PNY                 | 1        | 1      | 0.96%   |
| Patriot             | 1        | 1      | 0.96%   |
| OCZ                 | 1        | 1      | 0.96%   |
| Micron Technology   | 1        | 1      | 0.96%   |
| MAXSUN              | 1        | 1      | 0.96%   |
| Lexar               | 1        | 1      | 0.96%   |
| Intel               | 1        | 3      | 0.96%   |
| Hikvision           | 1        | 1      | 0.96%   |
| Dogfish             | 1        | 1      | 0.96%   |
| Corsair             | 1        | 1      | 0.96%   |
| Colorful            | 1        | 1      | 0.96%   |
| China               | 1        | 1      | 0.96%   |
| Apacer              | 1        | 3      | 0.96%   |
| Aoluska             | 1        | 1      | 0.96%   |
| AGI                 | 1        | 1      | 0.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 106      | 208    | 36.81%  |
| SSD     | 89       | 147    | 30.9%   |
| NVMe    | 79       | 137    | 27.43%  |
| Unknown | 12       | 13     | 4.17%   |
| MMC     | 2        | 2      | 0.69%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 147      | 341    | 60.25%  |
| NVMe | 79       | 136    | 32.38%  |
| SAS  | 16       | 28     | 6.56%   |
| MMC  | 2        | 2      | 0.82%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 96       | 170    | 47.06%  |
| 0.51-1.0   | 50       | 73     | 24.51%  |
| 1.01-2.0   | 24       | 35     | 11.76%  |
| 3.01-4.0   | 13       | 37     | 6.37%   |
| 2.01-3.0   | 11       | 19     | 5.39%   |
| 4.01-10.0  | 8        | 17     | 3.92%   |
| 10.01-20.0 | 2        | 4      | 0.98%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 40       | 20.1%   |
| More than 3000 | 28       | 14.07%  |
| 251-500        | 24       | 12.06%  |
| 501-1000       | 24       | 12.06%  |
| 1001-2000      | 23       | 11.56%  |
| 51-100         | 20       | 10.05%  |
| 2001-3000      | 13       | 6.53%   |
| Unknown        | 12       | 6.03%   |
| 1-20           | 8        | 4.02%   |
| 21-50          | 7        | 3.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 71       | 33.49%  |
| 101-250        | 27       | 12.74%  |
| 21-50          | 21       | 9.91%   |
| 501-1000       | 19       | 8.96%   |
| 251-500        | 18       | 8.49%   |
| 1001-2000      | 13       | 6.13%   |
| 51-100         | 13       | 6.13%   |
| Unknown        | 12       | 5.66%   |
| 2001-3000      | 10       | 4.72%   |
| More than 3000 | 8        | 3.77%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Desktops | Drives | Percent |
|----------------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB              | 2        | 3      | 8.7%    |
| ZHITAI TiPlus5000 512GB                      | 1        | 1      | 4.35%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD             | 1        | 1      | 4.35%   |
| WDC WD30EZRX-00D8PB0 3TB                     | 1        | 1      | 4.35%   |
| WDC WD10EZEX-60WN4A1 1TB                     | 1        | 1      | 4.35%   |
| WDC WD10EZEX-00RKKA0 1TB                     | 1        | 1      | 4.35%   |
| WDC WD10EALS-00Z8A0 1TB                      | 1        | 2      | 4.35%   |
| Toshiba MK1655GSX 160GB                      | 1        | 1      | 4.35%   |
| Toshiba MK1252GSX 120GB                      | 1        | 1      | 4.35%   |
| Toshiba DT01ACA100 1TB                       | 1        | 1      | 4.35%   |
| Seagate ST3500418AS 500GB                    | 1        | 1      | 4.35%   |
| Seagate ST3250310AS 250GB                    | 1        | 1      | 4.35%   |
| Seagate ST3160815AS 160GB                    | 1        | 1      | 4.35%   |
| Seagate ST1000LM014-1EJ164-SSHD 1TB          | 1        | 1      | 4.35%   |
| Samsung Electronics MZVLB512HAJQ-000L7 512GB | 1        | 1      | 4.35%   |
| LITEON IT LCS-128L9S-11 2.5 7mm 128GB SSD    | 1        | 1      | 4.35%   |
| Kingston SA400S37480G 480GB SSD              | 1        | 1      | 4.35%   |
| Intel SSDPEKKW128G7 128GB                    | 1        | 1      | 4.35%   |
| Intel SSD 600P Series 256GB                  | 1        | 4      | 4.35%   |
| Hitachi HTS542512K9SA00 120GB                | 1        | 1      | 4.35%   |
| HGST HTS 541010A9E680 1TB                    | 1        | 1      | 4.35%   |
| Crucial CT500MX500SSD1 500GB                 | 1        | 2      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 6        | 7      | 27.27%  |
| WDC                 | 4        | 6      | 18.18%  |
| Toshiba             | 3        | 3      | 13.64%  |
| Intel               | 2        | 5      | 9.09%   |
| ZHITAI              | 1        | 1      | 4.55%   |
| Samsung Electronics | 1        | 1      | 4.55%   |
| LITEON              | 1        | 1      | 4.55%   |
| Kingston            | 1        | 1      | 4.55%   |
| Hitachi             | 1        | 1      | 4.55%   |
| HGST HTS            | 1        | 1      | 4.55%   |
| Crucial             | 1        | 2      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Seagate  | 6        | 7      | 42.86%  |
| WDC      | 3        | 5      | 21.43%  |
| Toshiba  | 3        | 3      | 21.43%  |
| Hitachi  | 1        | 1      | 7.14%   |
| HGST HTS | 1        | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 13       | 17     | 61.9%   |
| NVMe | 4        | 7      | 19.05%  |
| SSD  | 4        | 5      | 19.05%  |

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
| Detected | 102      | 245    | 48.8%   |
| Works    | 86       | 233    | 41.15%  |
| Malfunc  | 21       | 29     | 10.05%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 127      | 43.64%  |
| AMD                              | 50       | 17.18%  |
| SanDisk                          | 17       | 5.84%   |
| Samsung Electronics              | 17       | 5.84%   |
| ASMedia Technology               | 13       | 4.47%   |
| Silicon Motion                   | 9        | 3.09%   |
| Phison Electronics               | 8        | 2.75%   |
| Micron/Crucial Technology        | 6        | 2.06%   |
| KIOXIA                           | 6        | 2.06%   |
| Kingston Technology Company      | 6        | 2.06%   |
| MAXIO Technology (Hangzhou)      | 5        | 1.72%   |
| ADATA Technology                 | 5        | 1.72%   |
| SK hynix                         | 4        | 1.37%   |
| Marvell Technology Group         | 4        | 1.37%   |
| Yangtze Memory Technologies      | 3        | 1.03%   |
| LSI Logic / Symbios Logic        | 2        | 0.69%   |
| Lite-On Technology               | 2        | 0.69%   |
| JMicron Technology               | 2        | 0.69%   |
| VIA Technologies                 | 1        | 0.34%   |
| Solidigm                         | 1        | 0.34%   |
| Shenzhen Shichuangyi Electronics | 1        | 0.34%   |
| Nvidia                           | 1        | 0.34%   |
| Integrated Technology Express    | 1        | 0.34%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 24       | 7.16%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 17       | 5.07%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 16       | 4.78%   |
| AMD 400 Series Chipset SATA Controller                                                  | 14       | 4.18%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 13       | 3.88%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 12       | 3.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 11       | 3.28%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 10       | 2.99%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 9        | 2.69%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 8        | 2.39%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 7        | 2.09%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7        | 2.09%   |
| AMD 500 Series Chipset SATA Controller                                                  | 7        | 2.09%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 5        | 1.49%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 5        | 1.49%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 1.49%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 5        | 1.49%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 5        | 1.49%   |
| AMD 600 Series Chipset SATA Controller                                                  | 5        | 1.49%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 5        | 1.49%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 4        | 1.19%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 4        | 1.19%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 4        | 1.19%   |
| KIOXIA NVMe SSD                                                                         | 4        | 1.19%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 1.19%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 4        | 1.19%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 1.19%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 3        | 0.9%    |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 3        | 0.9%    |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                 | 3        | 0.9%    |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                   | 3        | 0.9%    |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 3        | 0.9%    |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                                      | 3        | 0.9%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 3        | 0.9%    |
| Intel SSD 600P Series                                                                   | 3        | 0.9%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3        | 0.9%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3        | 0.9%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 3        | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 0.9%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 168      | 60.43%  |
| NVMe | 79       | 28.42%  |
| IDE  | 17       | 6.12%   |
| RAID | 12       | 4.32%   |
| SAS  | 2        | 0.72%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor     | Desktops | Percent |
|------------|----------|---------|
| Intel      | 126      | 68.85%  |
| AMD        | 53       | 28.96%  |
| Unknown    | 2        | 1.09%   |
| thead,c906 | 1        | 0.55%   |
| iSH        | 1        | 0.55%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| AMD Ryzen 7 5700G with Radeon Graphics | 6        | 3.26%   |
| Intel Pentium CPU G4560 @ 3.50GHz      | 5        | 2.72%   |
| AMD Ryzen 5 3600 6-Core Processor      | 5        | 2.72%   |
| Intel Core i7-6700 CPU @ 3.40GHz       | 4        | 2.17%   |
| Intel Core i7-4790 CPU @ 3.60GHz       | 4        | 2.17%   |
| Intel Core i7-9700 CPU @ 3.00GHz       | 3        | 1.63%   |
| Intel Core i7-7700K CPU @ 4.20GHz      | 3        | 1.63%   |
| Intel Core i5-6400 CPU @ 2.70GHz       | 3        | 1.63%   |
| Intel Core i5-4460 CPU @ 3.20GHz       | 3        | 1.63%   |
| Intel Core i5-3470 CPU @ 3.20GHz       | 3        | 1.63%   |
| Intel Core i3-10100 CPU @ 3.60GHz      | 3        | 1.63%   |
| AMD Ryzen 9 7950X 16-Core Processor    | 3        | 1.63%   |
| AMD Ryzen 9 5900X 12-Core Processor    | 3        | 1.63%   |
| AMD Ryzen 7 3700X 8-Core Processor     | 3        | 1.63%   |
| Intel Xeon CPU X5675 @ 3.07GHz         | 2        | 1.09%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz    | 2        | 1.09%   |
| Intel Core i7-9700K CPU @ 3.60GHz      | 2        | 1.09%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 2        | 1.09%   |
| Intel Core i7-2600 CPU @ 3.40GHz       | 2        | 1.09%   |
| Intel Core i5-8400 CPU @ 2.80GHz       | 2        | 1.09%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 2        | 1.09%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 2        | 1.09%   |
| Intel Core i3-7100 CPU @ 3.90GHz       | 2        | 1.09%   |
| Intel 12th Gen Core i9-12900K          | 2        | 1.09%   |
| Intel 12th Gen Core i7-12700K          | 2        | 1.09%   |
| Intel 12th Gen Core i5-12600K          | 2        | 1.09%   |
| Intel 12th Gen Core i5-12500           | 2        | 1.09%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz | 2        | 1.09%   |
| AMD Ryzen 9 3900X 12-Core Processor    | 2        | 1.09%   |
| AMD Ryzen 7 7700X 8-Core Processor     | 2        | 1.09%   |
| AMD Ryzen 5 5600X 6-Core Processor     | 2        | 1.09%   |
| AMD Ryzen 5 2600X Six-Core Processor   | 2        | 1.09%   |
| AMD Phenom II X6 1055T Processor       | 2        | 1.09%   |
|                                        | 2        | 1.09%   |
| thead,c906 rv64imafdc                  | 1        | 0.54%   |
| iSH Processor                          | 1        | 0.54%   |
| Intel Xeon CPU X5650 @ 2.67GHz         | 1        | 0.54%   |
| Intel Xeon CPU E5-2697 v2 @ 2.70GHz    | 1        | 0.54%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz    | 1        | 0.54%   |
| Intel Xeon CPU E3-1265L v3 @ 2.50GHz   | 1        | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i7          | 27       | 14.67%  |
| Other                  | 26       | 14.13%  |
| Intel Core i5          | 25       | 13.59%  |
| Intel Core i3          | 18       | 9.78%   |
| AMD Ryzen 7            | 16       | 8.7%    |
| AMD Ryzen 5            | 14       | 7.61%   |
| Intel Xeon             | 10       | 5.43%   |
| Intel Pentium          | 10       | 5.43%   |
| AMD Ryzen 9            | 9        | 4.89%   |
| Intel Celeron          | 6        | 3.26%   |
| AMD Phenom II X4       | 3        | 1.63%   |
| Intel Core i9          | 2        | 1.09%   |
| AMD Phenom II X6       | 2        | 1.09%   |
| AMD FX                 | 2        | 1.09%   |
| Intel Pentium Gold     | 1        | 0.54%   |
| Intel Pentium Dual     | 1        | 0.54%   |
| Intel Core 2 Quad      | 1        | 0.54%   |
| Intel Core 2 Extreme   | 1        | 0.54%   |
| Intel Core 2 Duo       | 1        | 0.54%   |
| Intel Core 2           | 1        | 0.54%   |
| AMD Ryzen Threadripper | 1        | 0.54%   |
| AMD Ryzen Embedded     | 1        | 0.54%   |
| AMD Ryzen 7 PRO        | 1        | 0.54%   |
| AMD Opteron            | 1        | 0.54%   |
| AMD Athlon II X4       | 1        | 0.54%   |
| AMD Athlon 64 X2       | 1        | 0.54%   |
| AMD A8                 | 1        | 0.54%   |
| AMD A10                | 1        | 0.54%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 58       | 31.52%  |
| 2       | 36       | 19.57%  |
| 8       | 30       | 16.3%   |
| 6       | 27       | 14.67%  |
| 12      | 13       | 7.07%   |
| 16      | 8        | 4.35%   |
| 10      | 4        | 2.17%   |
| Unknown | 4        | 2.17%   |
| 3       | 2        | 1.09%   |
| 24      | 1        | 0.54%   |
| 14      | 1        | 0.54%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 175      | 95.63%  |
| 2       | 4        | 2.19%   |
| Unknown | 4        | 2.19%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 121      | 65.76%  |
| 1       | 59       | 32.07%  |
| Unknown | 4        | 2.17%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 181      | 98.91%  |
| Unknown        | 2        | 1.09%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 56       | 29.47%  |
| 0x306c3    | 12       | 6.32%   |
| 0x90672    | 10       | 5.26%   |
| 0x906e9    | 9        | 4.74%   |
| 0x306a9    | 7        | 3.68%   |
| 0x206a7    | 7        | 3.68%   |
| 0x506e3    | 6        | 3.16%   |
| 0x906ed    | 5        | 2.63%   |
| 0x906ea    | 5        | 2.63%   |
| 0x0a50000d | 5        | 2.63%   |
| 0x0a50000c | 4        | 2.11%   |
| 0x0800820d | 4        | 2.11%   |
| 0xa0653    | 3        | 1.58%   |
| 0x806e9    | 3        | 1.58%   |
| 0x40651    | 3        | 1.58%   |
| 0x20652    | 3        | 1.58%   |
| 0x0a201009 | 3        | 1.58%   |
| 0x08701021 | 3        | 1.58%   |
| 0x08701013 | 3        | 1.58%   |
| 0xa0671    | 2        | 1.05%   |
| 0x90675    | 2        | 1.05%   |
| 0x306e4    | 2        | 1.05%   |
| 0x206c2    | 2        | 1.05%   |
| 0x0a601203 | 2        | 1.05%   |
| 0x0a201016 | 2        | 1.05%   |
| 0x06003106 | 2        | 1.05%   |
| 0x010000c8 | 2        | 1.05%   |
| 0xb06e0    | 1        | 0.53%   |
| 0xb0671    | 1        | 0.53%   |
| 0xa0655    | 1        | 0.53%   |
| 0x906eb    | 1        | 0.53%   |
| 0x706a1    | 1        | 0.53%   |
| 0x6fd      | 1        | 0.53%   |
| 0x30678    | 1        | 0.53%   |
| 0x20655    | 1        | 0.53%   |
| 0x106e5    | 1        | 0.53%   |
| 0x1067a    | 1        | 0.53%   |
| 0x10677    | 1        | 0.53%   |
| 0x0a704103 | 1        | 0.53%   |
| 0x0a601201 | 1        | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 30       | 16.22%  |
| Haswell          | 22       | 11.89%  |
| Unknown          | 17       | 9.19%   |
| Zen 3            | 16       | 8.65%   |
| Alderlake Hybrid | 14       | 7.57%   |
| Zen 2            | 12       | 6.49%   |
| IvyBridge        | 11       | 5.95%   |
| Skylake          | 10       | 5.41%   |
| SandyBridge      | 8        | 4.32%   |
| Westmere         | 7        | 3.78%   |
| CometLake        | 7        | 3.78%   |
| Zen+             | 6        | 3.24%   |
| K10              | 6        | 3.24%   |
| Core             | 3        | 1.62%   |
| Zen              | 2        | 1.08%   |
| Steamroller      | 2        | 1.08%   |
| Piledriver       | 2        | 1.08%   |
| Penryn           | 2        | 1.08%   |
| Icelake          | 2        | 1.08%   |
| Silvermont       | 1        | 0.54%   |
| Nehalem          | 1        | 0.54%   |
| K8 Hammer        | 1        | 0.54%   |
| Gracemont        | 1        | 0.54%   |
| Goldmont plus    | 1        | 0.54%   |
| Excavator        | 1        | 0.54%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Intel             | 77       | 38.69%  |
| Nvidia            | 74       | 37.19%  |
| AMD               | 47       | 23.62%  |
| ASPEED Technology | 1        | 0.5%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 12       | 5.8%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 9        | 4.35%   |
| Intel HD Graphics 610                                                       | 7        | 3.38%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 7        | 3.38%   |
| Intel AlderLake-S GT1                                                       | 6        | 2.9%    |
| Intel HD Graphics 530                                                       | 5        | 2.42%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 5        | 2.42%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 5        | 2.42%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 4        | 1.93%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 1.93%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 1.93%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 4        | 1.93%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 4        | 1.93%   |
| AMD Raphael                                                                 | 4        | 1.93%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4        | 1.93%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 1.45%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 1.45%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 1.45%   |
| Intel HD Graphics 630                                                       | 3        | 1.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 3        | 1.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.45%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3        | 1.45%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 2        | 0.97%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 0.97%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 0.97%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 0.97%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 2        | 0.97%   |
| Nvidia AD104 [GeForce RTX 4070 Ti]                                          | 2        | 0.97%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 0.97%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 2        | 0.97%   |
| Intel HD Graphics 620                                                       | 2        | 0.97%   |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 0.97%   |
| Intel Alder Lake-S GT1 [UHD Graphics 770]                                   | 2        | 0.97%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 2        | 0.97%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 0.97%   |
| AMD RS780 [Radeon HD 3200]                                                  | 2        | 0.97%   |
| AMD Navi 23 [Radeon RX 6650 XT / 6700S / 6800S]                             | 2        | 0.97%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 2        | 0.97%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 0.97%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 2        | 0.97%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 64       | 34.78%  |
| 1 x Intel      | 62       | 33.7%   |
| 1 x AMD        | 37       | 20.11%  |
| Intel + Nvidia | 6        | 3.26%   |
| Other          | 4        | 2.17%   |
| 2 x AMD        | 4        | 2.17%   |
| AMD + Nvidia   | 4        | 2.17%   |
| 3 x AMD        | 1        | 0.54%   |
| 2 x Intel      | 1        | 0.54%   |
| 1 x ASPEED     | 1        | 0.54%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 131      | 70.05%  |
| Proprietary | 45       | 24.06%  |
| Unknown     | 11       | 5.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 94       | 49.74%  |
| 7.01-8.0   | 22       | 11.64%  |
| 3.01-4.0   | 18       | 9.52%   |
| 0.51-1.0   | 18       | 9.52%   |
| 1.01-2.0   | 13       | 6.88%   |
| 0.01-0.5   | 8        | 4.23%   |
| 5.01-6.0   | 7        | 3.7%    |
| 8.01-16.0  | 5        | 2.65%   |
| 2.01-3.0   | 2        | 1.06%   |
| 4.01-5.0   | 1        | 0.53%   |
| 16.01-24.0 | 1        | 0.53%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 18       | 9.14%   |
| Goldstar             | 18       | 9.14%   |
| Dell                 | 18       | 9.14%   |
| AOC                  | 17       | 8.63%   |
| Philips              | 12       | 6.09%   |
| Acer                 | 10       | 5.08%   |
| BenQ                 | 9        | 4.57%   |
| Ancor Communications | 9        | 4.57%   |
| JRY                  | 7        | 3.55%   |
| ViewSonic            | 6        | 3.05%   |
| Unknown              | 6        | 3.05%   |
| AMO                  | 6        | 3.05%   |
| IPS                  | 5        | 2.54%   |
| ASUSTek Computer     | 5        | 2.54%   |
| Lenovo               | 4        | 2.03%   |
| Hewlett-Packard      | 4        | 2.03%   |
| SKY                  | 2        | 1.02%   |
| RTK                  | 2        | 1.02%   |
| HSO                  | 2        | 1.02%   |
| Eizo                 | 2        | 1.02%   |
| CHR                  | 2        | 1.02%   |
| AUS                  | 2        | 1.02%   |
| Xiaomi               | 1        | 0.51%   |
| Xiangye              | 1        | 0.51%   |
| Unknown (AAA)        | 1        | 0.51%   |
| Toshiba              | 1        | 0.51%   |
| TFC                  | 1        | 0.51%   |
| TCT                  | 1        | 0.51%   |
| TCL                  | 1        | 0.51%   |
| SOY                  | 1        | 0.51%   |
| Sony                 | 1        | 0.51%   |
| SKG                  | 1        | 0.51%   |
| SAC                  | 1        | 0.51%   |
| PDA                  | 1        | 0.51%   |
| PANDA                | 1        | 0.51%   |
| MSI                  | 1        | 0.51%   |
| Mi                   | 1        | 0.51%   |
| LYC                  | 1        | 0.51%   |
| LG Electronics       | 1        | 0.51%   |
| LDR                  | 1        | 0.51%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| JRY HDMI JRY1330 1920x1080 293x165mm 13.2-inch                        | 6        | 2.94%   |
| IPS HDMI IPS2700 1920x1080 597x336mm 27.0-inch                        | 4        | 1.96%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 4        | 1.96%   |
| AMO HS241P AMO2800 3840x2160 620x350mm 28.0-inch                      | 4        | 1.96%   |
| Unknown LCD Monitor XMD Mi TV 1360x768                                | 3        | 1.47%   |
| AOC Q2790 AOC2790 2560x1440 597x336mm 27.0-inch                       | 3        | 1.47%   |
| Philips PHL 323E7 PHLC121 1920x1080 698x393mm 31.5-inch               | 2        | 0.98%   |
| Lenovo LEN L24e-20 LEN65DF 1920x1080 527x296mm 23.8-inch              | 2        | 0.98%   |
| HSO B2431M HSO2431 3840x2160 520x290mm 23.4-inch                      | 2        | 0.98%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 2        | 0.98%   |
| Goldstar MONITOR GSM59C6 1920x1080 509x286mm 23.0-inch                | 2        | 0.98%   |
| Dell U2417H DEL40E7 1920x1080 530x300mm 24.0-inch                     | 2        | 0.98%   |
| CHR LCD Monitor CHR7511 1920x1080 519x324mm 24.1-inch                 | 2        | 0.98%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 2        | 0.98%   |
| Acer V196HQL ACR033D 1366x768 410x230mm 18.5-inch                     | 2        | 0.98%   |
| Xiaomi Mi TV XMD004A 1440x900 708x398mm 32.0-inch                     | 1        | 0.49%   |
| Xiangye XE2400 XYE2380 3840x2160 520x310mm 23.8-inch                  | 1        | 0.49%   |
| ViewSonic VX2462 series VSC7A3F 1920x1080 530x300mm 24.0-inch         | 1        | 0.49%   |
| ViewSonic VX2260WM VSCFC21 1920x1080 480x270mm 21.7-inch              | 1        | 0.49%   |
| ViewSonic VX2239 SERIES VSC5225 1920x1080 480x270mm 21.7-inch         | 1        | 0.49%   |
| ViewSonic VG921m VSC301E 1280x1024 380x300mm 19.1-inch                | 1        | 0.49%   |
| ViewSonic VA2465 SERIES VSCB730 1920x1080 521x293mm 23.5-inch         | 1        | 0.49%   |
| ViewSonic VA1616wSERIES VSC0021 1366x768 348x197mm 15.7-inch          | 1        | 0.49%   |
| Unknown LCD Monitor hp f1523 1024x768                                 | 1        | 0.49%   |
| Unknown LCD Monitor GBT G32QC A 2560x1440                             | 1        | 0.49%   |
| Unknown LCD Monitor FST V22T-1R LED 1920x1080                         | 1        | 0.49%   |
| Unknown (AAA) U270 AAA2700 3840x2160 596x335mm 26.9-inch              | 1        | 0.49%   |
| Toshiba TV TSB2634 1920x1080 697x392mm 31.5-inch                      | 1        | 0.49%   |
| TFC TF2421 TFC2421 1920x1080 527x296mm 23.8-inch                      | 1        | 0.49%   |
| TCT DP1080P60 TCT0270 2560x1600 520x290mm 23.4-inch                   | 1        | 0.49%   |
| TCL SMART TV TCL5507 1920x1080 1209x680mm 54.6-inch                   | 1        | 0.49%   |
| SOY M5 MONITOR SOY0240 1920x1080 520x320mm 24.0-inch                  | 1        | 0.49%   |
| Sony TV SNY4B03 1920x1080 708x398mm 32.0-inch                         | 1        | 0.49%   |
| SKY TV MONITOR SKY0030 3840x2160 708x398mm 32.0-inch                  | 1        | 0.49%   |
| SKY M16U1 SKY0156 3840x2160 345x194mm 15.6-inch                       | 1        | 0.49%   |
| SKG PMO G270-CQK SKG2712 2560x1440 530x280mm 23.6-inch                | 1        | 0.49%   |
| Samsung Electronics SyncMaster SAM0372 1680x1050 459x296mm 21.5-inch  | 1        | 0.49%   |
| Samsung Electronics SyncMaster SAM01D4 1440x900 408x225mm 18.3-inch   | 1        | 0.49%   |
| Samsung Electronics S27D590 SAM0B49 1920x1080 598x336mm 27.0-inch     | 1        | 0.49%   |
| Samsung Electronics S24E390 SAM0C1A 1920x1080 521x293mm 23.5-inch     | 1        | 0.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 83       | 45.6%   |
| 3840x2160 (4K)     | 33       | 18.13%  |
| 2560x1440 (QHD)    | 17       | 9.34%   |
| 1366x768 (WXGA)    | 9        | 4.95%   |
| 1440x900 (WXGA+)   | 7        | 3.85%   |
| 1680x1050 (WSXGA+) | 6        | 3.3%    |
| 1280x1024 (SXGA)   | 4        | 2.2%    |
| Unknown            | 4        | 2.2%    |
| 3840x1080          | 3        | 1.65%   |
| 1360x768           | 3        | 1.65%   |
| 3440x1440          | 2        | 1.1%    |
| 2560x1600          | 2        | 1.1%    |
| 2560x1080          | 2        | 1.1%    |
| 1920x1200 (WUXGA)  | 2        | 1.1%    |
| 1024x768 (XGA)     | 2        | 1.1%    |
| 5120x1440          | 1        | 0.55%   |
| 3200x1080          | 1        | 0.55%   |
| 1400x1050          | 1        | 0.55%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 32       | 16.67%  |
| 23      | 29       | 15.1%   |
| 27      | 24       | 12.5%   |
| 21      | 22       | 11.46%  |
| Unknown | 19       | 9.9%    |
| 18      | 12       | 6.25%   |
| 31      | 9        | 4.69%   |
| 13      | 6        | 3.13%   |
| 40      | 5        | 2.6%    |
| 28      | 5        | 2.6%    |
| 22      | 4        | 2.08%   |
| 19      | 4        | 2.08%   |
| 84      | 3        | 1.56%   |
| 34      | 3        | 1.56%   |
| 15      | 3        | 1.56%   |
| 32      | 2        | 1.04%   |
| 65      | 1        | 0.52%   |
| 58      | 1        | 0.52%   |
| 57      | 1        | 0.52%   |
| 54      | 1        | 0.52%   |
| 50      | 1        | 0.52%   |
| 48      | 1        | 0.52%   |
| 26      | 1        | 0.52%   |
| 25      | 1        | 0.52%   |
| 17      | 1        | 0.52%   |
| 16      | 1        | 0.52%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 80       | 43.48%  |
| 401-500     | 39       | 21.2%   |
| Unknown     | 19       | 10.33%  |
| 601-700     | 15       | 8.15%   |
| 701-800     | 6        | 3.26%   |
| 201-300     | 6        | 3.26%   |
| 801-900     | 5        | 2.72%   |
| 301-350     | 5        | 2.72%   |
| 1001-1500   | 5        | 2.72%   |
| 1501-2000   | 3        | 1.63%   |
| 351-400     | 1        | 0.54%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 126      | 72%     |
| 16/10   | 22       | 12.57%  |
| Unknown | 18       | 10.29%  |
| 21/9    | 3        | 1.71%   |
| 6/5     | 2        | 1.14%   |
| 5/4     | 1        | 0.57%   |
| 4/3     | 1        | 0.57%   |
| 32/9    | 1        | 0.57%   |
| 0.56    | 1        | 0.57%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 70       | 37.04%  |
| 301-350        | 30       | 15.87%  |
| Unknown        | 19       | 10.05%  |
| 351-500        | 14       | 7.41%   |
| 151-200        | 13       | 6.88%   |
| 251-300        | 10       | 5.29%   |
| 141-150        | 9        | 4.76%   |
| More than 1000 | 8        | 4.23%   |
| 71-80          | 6        | 3.17%   |
| 501-1000       | 6        | 3.17%   |
| 101-110        | 3        | 1.59%   |
| 131-140        | 1        | 0.53%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 100      | 53.76%  |
| 101-120       | 37       | 19.89%  |
| Unknown       | 19       | 10.22%  |
| 161-240       | 17       | 9.14%   |
| 1-50          | 6        | 3.23%   |
| 121-160       | 6        | 3.23%   |
| More than 240 | 1        | 0.54%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 140      | 76.09%  |
| 2     | 29       | 15.76%  |
| 0     | 14       | 7.61%   |
| 3     | 1        | 0.54%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 107      | 40.84%  |
| Intel                                  | 101      | 38.55%  |
| TP-Link                                | 8        | 3.05%   |
| Broadcom                               | 8        | 3.05%   |
| Qualcomm Atheros                       | 7        | 2.67%   |
| MediaTek                               | 7        | 2.67%   |
| Ralink Technology                      | 5        | 1.91%   |
| Microsoft                              | 3        | 1.15%   |
| Xiaomi                                 | 1        | 0.38%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.38%   |
| SEGGER                                 | 1        | 0.38%   |
| Samsung Electronics                    | 1        | 0.38%   |
| PEAK-System Technik                    | 1        | 0.38%   |
| Nvidia                                 | 1        | 0.38%   |
| National Semiconductor                 | 1        | 0.38%   |
| Kinesis                                | 1        | 0.38%   |
| Google                                 | 1        | 0.38%   |
| D-Link System                          | 1        | 0.38%   |
| D-Link                                 | 1        | 0.38%   |
| Belkin Components                      | 1        | 0.38%   |
| ASUSTek Computer                       | 1        | 0.38%   |
| ASIX Electronics                       | 1        | 0.38%   |
| Arduino SA                             | 1        | 0.38%   |
| Aquantia                               | 1        | 0.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 86       | 27.3%   |
| Intel Wi-Fi 6 AX200                                                    | 18       | 5.71%   |
| Realtek RTL8125 2.5GbE Controller                                      | 13       | 4.13%   |
| Intel I211 Gigabit Network Connection                                  | 12       | 3.81%   |
| Intel Ethernet Controller I225-V                                       | 12       | 3.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 9        | 2.86%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 9        | 2.86%   |
| Intel Ethernet Connection (2) I219-V                                   | 8        | 2.54%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 6        | 1.9%    |
| Intel Ethernet Connection I217-LM                                      | 6        | 1.9%    |
| Intel Wireless 7265                                                    | 4        | 1.27%   |
| Intel 82574L Gigabit Network Connection                                | 4        | 1.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3        | 0.95%   |
| Ralink MT7601U Wireless Adapter                                        | 3        | 0.95%   |
| Microsoft Xbox Wireless Adapter for Windows                            | 3        | 0.95%   |
| Intel Wireless 7260                                                    | 3        | 0.95%   |
| Intel Ethernet Connection (7) I219-LM                                  | 3        | 0.95%   |
| Intel Ethernet Connection (17) I219-LM                                 | 3        | 0.95%   |
| Intel Ethernet Connection (11) I219-V                                  | 3        | 0.95%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 3        | 0.95%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 3        | 0.95%   |
| Intel 82579V Gigabit Network Connection                                | 3        | 0.95%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 2        | 0.63%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 2        | 0.63%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 2        | 0.63%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 2        | 0.63%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 2        | 0.63%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 2        | 0.63%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2        | 0.63%   |
| Realtek Killer E2600 GbE Controller                                    | 2        | 0.63%   |
| Realtek 802.11ac NIC                                                   | 2        | 0.63%   |
| Ralink RT5370 Wireless Adapter                                         | 2        | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2        | 0.63%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 2        | 0.63%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 2        | 0.63%   |
| Intel Wireless 8265 / 8275                                             | 2        | 0.63%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 2        | 0.63%   |
| Intel Ethernet Connection I217-V                                       | 2        | 0.63%   |
| Intel Ethernet Connection (7) I219-V                                   | 2        | 0.63%   |
| Intel Ethernet Connection (2) I218-V                                   | 2        | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 65       | 59.63%  |
| Realtek Semiconductor | 12       | 11.01%  |
| TP-Link               | 8        | 7.34%   |
| MediaTek              | 7        | 6.42%   |
| Ralink Technology     | 5        | 4.59%   |
| Broadcom              | 4        | 3.67%   |
| Microsoft             | 3        | 2.75%   |
| Qualcomm Atheros      | 2        | 1.83%   |
| D-Link System         | 1        | 0.92%   |
| Belkin Components     | 1        | 0.92%   |
| ASUSTek Computer      | 1        | 0.92%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                           | 18       | 16.51%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 9        | 8.26%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 9        | 8.26%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]     | 6        | 5.5%    |
| Intel Wireless 7265                                           | 4        | 3.67%   |
| Ralink MT7601U Wireless Adapter                               | 3        | 2.75%   |
| Microsoft Xbox Wireless Adapter for Windows                   | 3        | 2.75%   |
| Intel Wireless 7260                                           | 3        | 2.75%   |
| Intel Comet Lake PCH CNVi WiFi                                | 3        | 2.75%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 3        | 2.75%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                  | 2        | 1.83%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]    | 2        | 1.83%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 2        | 1.83%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 2        | 1.83%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                       | 2        | 1.83%   |
| Realtek 802.11ac NIC                                          | 2        | 1.83%   |
| Ralink RT5370 Wireless Adapter                                | 2        | 1.83%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 2        | 1.83%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 2        | 1.83%   |
| Intel Wireless 8265 / 8275                                    | 2        | 1.83%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]       | 2        | 1.83%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter  | 2        | 1.83%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 1        | 0.92%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                         | 1        | 0.92%   |
| TP-Link Archer T4U ver.3                                      | 1        | 0.92%   |
| TP-Link 802.11n NIC                                           | 1        | 0.92%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 1        | 0.92%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter      | 1        | 0.92%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)     | 1        | 0.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 1        | 0.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 1        | 0.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 1        | 0.92%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 1        | 0.92%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter            | 1        | 0.92%   |
| MediaTek 802.11 n WLAN                                        | 1        | 0.92%   |
| Intel Wireless 3160                                           | 1        | 0.92%   |
| Intel Raptor Lake-S PCH CNVi WiFi                             | 1        | 0.92%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection | 1        | 0.92%   |
| Intel Centrino Wireless-N 2230                                | 1        | 0.92%   |
| Intel Centrino Wireless-N 105                                 | 1        | 0.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 107      | 54.87%  |
| Intel                                  | 70       | 35.9%   |
| Qualcomm Atheros                       | 5        | 2.56%   |
| Broadcom                               | 4        | 2.05%   |
| Xiaomi                                 | 1        | 0.51%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.51%   |
| Samsung Electronics                    | 1        | 0.51%   |
| Nvidia                                 | 1        | 0.51%   |
| National Semiconductor                 | 1        | 0.51%   |
| Google                                 | 1        | 0.51%   |
| D-Link                                 | 1        | 0.51%   |
| ASIX Electronics                       | 1        | 0.51%   |
| Aquantia                               | 1        | 0.51%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 86       | 42.57%  |
| Realtek RTL8125 2.5GbE Controller                                      | 13       | 6.44%   |
| Intel I211 Gigabit Network Connection                                  | 12       | 5.94%   |
| Intel Ethernet Controller I225-V                                       | 12       | 5.94%   |
| Intel Ethernet Connection (2) I219-V                                   | 8        | 3.96%   |
| Intel Ethernet Connection I217-LM                                      | 6        | 2.97%   |
| Intel 82574L Gigabit Network Connection                                | 4        | 1.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3        | 1.49%   |
| Intel Ethernet Connection (7) I219-LM                                  | 3        | 1.49%   |
| Intel Ethernet Connection (17) I219-LM                                 | 3        | 1.49%   |
| Intel Ethernet Connection (11) I219-V                                  | 3        | 1.49%   |
| Intel 82579V Gigabit Network Connection                                | 3        | 1.49%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 2        | 0.99%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2        | 0.99%   |
| Realtek Killer E2600 GbE Controller                                    | 2        | 0.99%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2        | 0.99%   |
| Intel Ethernet Connection I217-V                                       | 2        | 0.99%   |
| Intel Ethernet Connection (7) I219-V                                   | 2        | 0.99%   |
| Intel Ethernet Connection (2) I218-V                                   | 2        | 0.99%   |
| Intel Ethernet Connection (12) I219-V                                  | 2        | 0.99%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2        | 0.99%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1        | 0.5%    |
| Sony Ericsson Mobile AB XQ-CC54                                        | 1        | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 1        | 0.5%    |
| Realtek Killer E3000 2.5GbE Controller                                 | 1        | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1        | 0.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1        | 0.5%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1        | 0.5%    |
| Nvidia MCP65 Ethernet                                                  | 1        | 0.5%    |
| National DP83815 (MacPhyter) Ethernet Controller                       | 1        | 0.5%    |
| Intel Wi-Fi 7(802.11be) AX1775*/AX1790*/BE20*/BE401/BE1750* 2x2        | 1        | 0.5%    |
| Intel I350 Gigabit Network Connection                                  | 1        | 0.5%    |
| Intel Ethernet Controller 10-Gigabit X540-AT2                          | 1        | 0.5%    |
| Intel Ethernet Connection (2) I219-LM                                  | 1        | 0.5%    |
| Intel Ethernet Connection (14) I219-V                                  | 1        | 0.5%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 1        | 0.5%    |
| Intel 82578DM Gigabit Network Connection                               | 1        | 0.5%    |
| Intel 82576 Gigabit Network Connection                                 | 1        | 0.5%    |
| Intel 82573L Gigabit Ethernet Controller                               | 1        | 0.5%    |
| Intel 82567LM-3 Gigabit Network Connection                             | 1        | 0.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 178      | 62.68%  |
| WiFi     | 102      | 35.92%  |
| Modem    | 3        | 1.06%   |
| Unknown  | 1        | 0.35%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 147      | 73.87%  |
| WiFi     | 52       | 26.13%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 89       | 47.59%  |
| 2     | 82       | 43.85%  |
| 3     | 6        | 3.21%   |
| 0     | 6        | 3.21%   |
| 4     | 2        | 1.07%   |
| 8     | 1        | 0.53%   |
| 7     | 1        | 0.53%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 175      | 95.11%  |
| Yes  | 9        | 4.89%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 60       | 63.16%  |
| Cambridge Silicon Radio         | 17       | 17.89%  |
| Broadcom                        | 4        | 4.21%   |
| Realtek Semiconductor           | 3        | 3.16%   |
| MediaTek                        | 2        | 2.11%   |
| ASUSTek Computer                | 2        | 2.11%   |
| TP-Link                         | 1        | 1.05%   |
| SINO WEALTH                     | 1        | 1.05%   |
| Qualcomm Atheros Communications | 1        | 1.05%   |
| Micro Star International        | 1        | 1.05%   |
| Lite-On Technology              | 1        | 1.05%   |
| Foxconn / Hon Hai               | 1        | 1.05%   |
| Apple                           | 1        | 1.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 17       | 17.89%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 17       | 17.89%  |
| Intel Wireless-AC 3168 Bluetooth                    | 9        | 9.47%   |
| Intel Bluetooth wireless interface                  | 9        | 9.47%   |
| Intel AX201 Bluetooth                               | 9        | 9.47%   |
| Intel AX210 Bluetooth                               | 6        | 6.32%   |
| Intel Bluetooth Device                              | 5        | 5.26%   |
| Realtek Bluetooth Radio                             | 3        | 3.16%   |
| MediaTek Wireless_Device                            | 2        | 2.11%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 2.11%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2        | 2.11%   |
| ASUS Bluetooth Radio                                | 2        | 2.11%   |
| TP-Link UB500 Adapter                               | 1        | 1.05%   |
| SINO WEALTH RK Bluetooth Keyboar                    | 1        | 1.05%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 1.05%   |
| Micro Star International Bluetooth Dongle           | 1        | 1.05%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1        | 1.05%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 1.05%   |
| Foxconn / Hon Hai Wireless_Device                   | 1        | 1.05%   |
| Broadcom Bluetooth Controller                       | 1        | 1.05%   |
| Broadcom Bluetooth 2.0+eDR dongle                   | 1        | 1.05%   |
| Broadcom BCM920702 Bluetooth 4.0 Zero Touch Dongle  | 1        | 1.05%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1        | 1.05%   |
| Apple Bluetooth Host Controller                     | 1        | 1.05%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 125      | 42.66%  |
| Nvidia                                       | 72       | 24.57%  |
| AMD                                          | 63       | 21.5%   |
| C-Media Electronics                          | 10       | 3.41%   |
| ASUSTek Computer                             | 3        | 1.02%   |
| Micro Star International                     | 2        | 0.68%   |
| Focusrite-Novation                           | 2        | 0.68%   |
| FiiO Electronics Technology                  | 2        | 0.68%   |
| Creative Labs                                | 2        | 0.68%   |
| Anlya.cn                                     | 2        | 0.68%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.34%   |
| XMOS                                         | 1        | 0.34%   |
| Thesycon Systemsoftware & Consulting         | 1        | 0.34%   |
| Texas Instruments                            | 1        | 0.34%   |
| Sony                                         | 1        | 0.34%   |
| SAVITECH                                     | 1        | 0.34%   |
| Lynx                                         | 1        | 0.34%   |
| Logitech                                     | 1        | 0.34%   |
| JMTek                                        | 1        | 0.34%   |
| AudioQuest                                   | 1        | 0.34%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 19       | 5.43%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 17       | 4.86%   |
| Intel Alder Lake-S HD Audio Controller                                     | 16       | 4.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 14       | 4%      |
| AMD Family 17h/19h HD Audio Controller                                     | 14       | 4%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13       | 3.71%   |
| Intel 200 Series PCH HD Audio                                              | 10       | 2.86%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 9        | 2.57%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 9        | 2.57%   |
| Intel Cannon Lake PCH cAVS                                                 | 8        | 2.29%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8        | 2.29%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8        | 2.29%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 8        | 2.29%   |
| Nvidia GP106 High Definition Audio Controller                              | 7        | 2%      |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 7        | 2%      |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6        | 1.71%   |
| Nvidia GF108 High Definition Audio Controller                              | 6        | 1.71%   |
| Nvidia GA104 High Definition Audio Controller                              | 6        | 1.71%   |
| Nvidia TU106 High Definition Audio Controller                              | 5        | 1.43%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 5        | 1.43%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 5        | 1.43%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5        | 1.43%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 5        | 1.43%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5        | 1.43%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5        | 1.43%   |
| Nvidia TU104 HD Audio Controller                                           | 4        | 1.14%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4        | 1.14%   |
| Nvidia GM206 High Definition Audio Controller                              | 4        | 1.14%   |
| Intel Comet Lake PCH-V cAVS                                                | 4        | 1.14%   |
| AMD Navi 10 HDMI Audio                                                     | 4        | 1.14%   |
| Nvidia TU116 High Definition Audio Controller                              | 3        | 0.86%   |
| Nvidia GP108 High Definition Audio Controller                              | 3        | 0.86%   |
| Nvidia GP104 High Definition Audio Controller                              | 3        | 0.86%   |
| Nvidia GF106 High Definition Audio Controller                              | 3        | 0.86%   |
| Intel Sunrise Point-LP HD Audio                                            | 3        | 0.86%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3        | 0.86%   |
| Intel Comet Lake PCH cAVS                                                  | 3        | 0.86%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 0.86%   |
| Intel 8 Series HD Audio Controller                                         | 3        | 0.86%   |
| ASUSTek Computer USB Audio                                                 | 3        | 0.86%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 30       | 26.79%  |
| A-DATA Technology   | 13       | 11.61%  |
| Corsair             | 12       | 10.71%  |
| Samsung Electronics | 11       | 9.82%   |
| Unknown             | 7        | 6.25%   |
| SK hynix            | 6        | 5.36%   |
| G.Skill             | 5        | 4.46%   |
| Crucial             | 5        | 4.46%   |
| Micron Technology   | 4        | 3.57%   |
| Team                | 3        | 2.68%   |
| Ramaxel Technology  | 2        | 1.79%   |
| Unknown             | 2        | 1.79%   |
| Unknown (0x0AFD)    | 1        | 0.89%   |
| Transcend           | 1        | 0.89%   |
| Nanya Technology    | 1        | 0.89%   |
| KingSpec            | 1        | 0.89%   |
| Kingmax             | 1        | 0.89%   |
| KINGBANK            | 1        | 0.89%   |
| Kimtigo             | 1        | 0.89%   |
| Juhor               | 1        | 0.89%   |
| GLOWAY              | 1        | 0.89%   |
| Essencore Limited   | 1        | 0.89%   |
| CUSO                | 1        | 0.89%   |
| Apacer              | 1        | 0.89%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s      | 2        | 1.67%   |
| Kingston RAM KY7N41-MIE 8GB DIMM DDR4 2666MT/s            | 2        | 1.67%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s       | 2        | 1.67%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s     | 2        | 1.67%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s     | 2        | 1.67%   |
| Corsair RAM CM4X16GC3600C18K2D 16GB DIMM DDR4 3600MT/s    | 2        | 1.67%   |
| A-DATA RAM Module 4GB DIMM DDR3 1333MT/s                  | 2        | 1.67%   |
| Unknown                                                   | 2        | 1.67%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s              | 1        | 0.83%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s               | 1        | 0.83%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                 | 1        | 0.83%   |
| Unknown RAM Module 4GB DIMM 800MT/s                       | 1        | 0.83%   |
| Unknown RAM Module 4096MB DIMM DDR2 800MT/s               | 1        | 0.83%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                      | 1        | 0.83%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                    | 1        | 0.83%   |
| Unknown (0x0AFD) RAM SED2666U1932 32GB DIMM DDR4 2667MT/s | 1        | 0.83%   |
| Transcend RAM TS256MLQ72V6U 2GB DIMM DDR2 667MT/s         | 1        | 0.83%   |
| Team RAM TEAMGROUP-UD4-2666 8192MB DIMM DDR4 3000MT/s     | 1        | 0.83%   |
| Team RAM TEAMGROUP-UD4-2400 16GB DIMM DDR4 3007MT/s       | 1        | 0.83%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s        | 1        | 0.83%   |
| SK hynix RAM Module 8GB DIMM DDR4 3200MT/s                | 1        | 0.83%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s                | 1        | 0.83%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                | 1        | 0.83%   |
| SK hynix RAM HMCG66MEBUA084N 8GB DIMM DDR5 4800MT/s       | 1        | 0.83%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s    | 1        | 0.83%   |
| Samsung RAM Module 3GB Row Of Chips 6400MT/s              | 1        | 0.83%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s  | 1        | 0.83%   |
| Samsung RAM M471B1G73DH0-YK0 8GB SODIMM DDR3 1600MT/s     | 1        | 0.83%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s     | 1        | 0.83%   |
| Samsung RAM M471A1G43EB1-CPB 8GB SODIMM DDR4 2133MT/s     | 1        | 0.83%   |
| Samsung RAM M391A1K43BB1-CRC 8GB DIMM DDR4 2400MT/s       | 1        | 0.83%   |
| Samsung RAM M378B5773DH0-CK0 2GB DIMM DDR3 1600MT/s       | 1        | 0.83%   |
| Samsung RAM M378B5773CH0-CK0 2GB DIMM DDR3 1600MT/s       | 1        | 0.83%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s       | 1        | 0.83%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s       | 1        | 0.83%   |
| Samsung RAM M378A2K43CB1-CTD 16384MB DIMM DDR4 3200MT/s   | 1        | 0.83%   |
| Samsung RAM M378A2G43CB3-CWE 16GB DIMM DDR4 3200MT/s      | 1        | 0.83%   |
| Samsung RAM M323R2GA3BB0-CQKOD 16GB DIMM DDR5 4800MT/s    | 1        | 0.83%   |
| Ramaxel RAM RMR5040MM58F9F1600 4GB DIMM DDR3 1600MT/s     | 1        | 0.83%   |
| Ramaxel RAM RMR1870ED48E8F1333 2048MB DIMM DDR3 1333MT/s  | 1        | 0.83%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 69       | 65.71%  |
| DDR3    | 19       | 18.1%   |
| DDR5    | 9        | 8.57%   |
| Unknown | 4        | 3.81%   |
| SDRAM   | 2        | 1.9%    |
| DDR2    | 2        | 1.9%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 88       | 83.81%  |
| SODIMM       | 16       | 15.24%  |
| Row Of Chips | 1        | 0.95%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 34       | 30.91%  |
| 8192  | 31       | 28.18%  |
| 4096  | 19       | 17.27%  |
| 32768 | 16       | 14.55%  |
| 2048  | 8        | 7.27%   |
| 3072  | 1        | 0.91%   |
| 1024  | 1        | 0.91%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 21       | 19.27%  |
| 2667  | 12       | 11.01%  |
| 1600  | 11       | 10.09%  |
| 2400  | 9        | 8.26%   |
| 3600  | 8        | 7.34%   |
| 1333  | 8        | 7.34%   |
| 2666  | 5        | 4.59%   |
| 2133  | 5        | 4.59%   |
| 4800  | 4        | 3.67%   |
| 3000  | 4        | 3.67%   |
| 800   | 3        | 2.75%   |
| 6000  | 2        | 1.83%   |
| 3533  | 2        | 1.83%   |
| 7000  | 1        | 0.92%   |
| 6400  | 1        | 0.92%   |
| 5808  | 1        | 0.92%   |
| 5600  | 1        | 0.92%   |
| 4199  | 1        | 0.92%   |
| 3933  | 1        | 0.92%   |
| 3866  | 1        | 0.92%   |
| 3800  | 1        | 0.92%   |
| 3733  | 1        | 0.92%   |
| 3466  | 1        | 0.92%   |
| 3400  | 1        | 0.92%   |
| 3007  | 1        | 0.92%   |
| 1866  | 1        | 0.92%   |
| 1800  | 1        | 0.92%   |
| 667   | 1        | 0.92%   |

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
| HP LaserJet P2035           | 1        | 25%     |
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
| Logitech                      | 8        | 38.1%   |
| Microdia                      | 2        | 9.52%   |
| eMPIA Technology              | 2        | 9.52%   |
| Z-Star Microelectronics       | 1        | 4.76%   |
| Sunplus Innovation Technology | 1        | 4.76%   |
| SN0002                        | 1        | 4.76%   |
| Nokia Mobile Phones           | 1        | 4.76%   |
| Google                        | 1        | 4.76%   |
| Essential Products            | 1        | 4.76%   |
| Cubeternet                    | 1        | 4.76%   |
| ARC International             | 1        | 4.76%   |
| A4Tech                        | 1        | 4.76%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech Webcam C270                    | 4        | 18.18%  |
| Logitech B525 HD Webcam                 | 2        | 9.09%   |
| eMPIA M035 Compact Web Cam              | 2        | 9.09%   |
| Z-Star Sirius USB2.0 Camera             | 1        | 4.55%   |
| Sunplus SPCA2650 PC Camera              | 1        | 4.55%   |
| SN0002 2K USB Camera                    | 1        | 4.55%   |
| Nokia Mobile Phones Lumia 640 Phone     | 1        | 4.55%   |
| Microdia USB 2.0 Camera                 | 1        | 4.55%   |
| Microdia HP Integrated Webcam           | 1        | 4.55%   |
| Logitech C920 PRO HD Webcam             | 1        | 4.55%   |
| Logitech BRIO Ultra HD Webcam           | 1        | 4.55%   |
| Google Nexus/Pixel Device (PTP + debug) | 1        | 4.55%   |
| Google Nexus/Pixel Device (MTP + debug) | 1        | 4.55%   |
| Essential Products PH-1                 | 1        | 4.55%   |
| Cubeternet GL-UPC822 UVC WebCam         | 1        | 4.55%   |
| ARC International Camera                | 1        | 4.55%   |
| A4Tech FHD 1080P PC Camera              | 1        | 4.55%   |

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
| Advanced Card Systems | 2        | 66.67%  |
| Yubico.com            | 1        | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Advanced Card Systems ACR1281 1S Dual Reader | 2        | 66.67%  |
| Yubico.com Yubikey 4/5 U2F+CCID              | 1        | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 155      | 81.58%  |
| 1     | 29       | 15.26%  |
| 2     | 4        | 2.11%   |
| 4     | 2        | 1.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 13       | 29.55%  |
| Graphics card            | 13       | 29.55%  |
| Communication controller | 7        | 15.91%  |
| Unassigned class         | 3        | 6.82%   |
| Chipcard                 | 2        | 4.55%   |
| Storage/ata              | 1        | 2.27%   |
| Sound                    | 1        | 2.27%   |
| Net/ethernet             | 1        | 2.27%   |
| Fingerprint reader       | 1        | 2.27%   |
| Camera                   | 1        | 2.27%   |
| Bluetooth                | 1        | 2.27%   |

