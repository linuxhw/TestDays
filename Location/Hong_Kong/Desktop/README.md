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

Total: 270

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 22.04       | 18       | 9.63%   |
| Ubuntu 20.04       | 18       | 9.63%   |
| Ubuntu 18.04       | 13       | 6.95%   |
| Arch Rolling       | 11       | 5.88%   |
| OpenMandriva 4.2   | 10       | 5.35%   |
| Debian 11          | 10       | 5.35%   |
| Pop!_OS 22.04      | 8        | 4.28%   |
| Ubuntu 16.04       | 6        | 3.21%   |
| OpenMandriva 4.3   | 5        | 2.67%   |
| KDE neon 20.04     | 5        | 2.67%   |
| Ubuntu 19.10       | 4        | 2.14%   |
| Fedora 35          | 4        | 2.14%   |
| Debian 12          | 4        | 2.14%   |
| Ubuntu 20.10       | 3        | 1.6%    |
| ArcoLinux Rolling  | 3        | 1.6%    |
| Ubuntu 23.04       | 2        | 1.07%   |
| Ubuntu 21.10       | 2        | 1.07%   |
| Ubuntu 19.04       | 2        | 1.07%   |
| Slackware 15.0     | 2        | 1.07%   |
| PostmarketOS Edge  | 2        | 1.07%   |
| Pop!_OS 20.10      | 2        | 1.07%   |
| Parrot 4.9         | 2        | 1.07%   |
| Gentoo 2.7         | 2        | 1.07%   |
| Fedora 38          | 2        | 1.07%   |
| Fedora 31          | 2        | 1.07%   |
| Elementary 5.1.7   | 2        | 1.07%   |
| CentOS 8           | 2        | 1.07%   |
| Zorin 15           | 1        | 0.53%   |
| Xubuntu 18.04      | 1        | 0.53%   |
| Ubuntu MATE 20.04  | 1        | 0.53%   |
| Ubuntu 23.10       | 1        | 0.53%   |
| Ubuntu 22.10       | 1        | 0.53%   |
| Ubuntu 21.04       | 1        | 0.53%   |
| SteamOS 3.3        | 1        | 0.53%   |
| Slackware 14.2     | 1        | 0.53%   |
| ROSA R8.1          | 1        | 0.53%   |
| Rocky Linux 9.2    | 1        | 0.53%   |
| Pop!_OS 21.04      | 1        | 0.53%   |
| OpenMandriva 4.50  | 1        | 0.53%   |
| OpenMandriva 23.01 | 1        | 0.53%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 66       | 36.87%  |
| OpenMandriva | 16       | 8.94%   |
| Debian       | 14       | 7.82%   |
| Fedora       | 12       | 6.7%    |
| Arch         | 12       | 6.7%    |
| Pop!_OS      | 11       | 6.15%   |
| Manjaro      | 5        | 2.79%   |
| KDE neon     | 5        | 2.79%   |
| Slackware    | 3        | 1.68%   |
| Linux Mint   | 3        | 1.68%   |
| Kubuntu      | 3        | 1.68%   |
| Gentoo       | 3        | 1.68%   |
| Elementary   | 3        | 1.68%   |
| CentOS       | 3        | 1.68%   |
| ArcoLinux    | 3        | 1.68%   |
| PostmarketOS | 2        | 1.12%   |
| Parrot       | 2        | 1.12%   |
| EndeavourOS  | 2        | 1.12%   |
| Clear Linux  | 2        | 1.12%   |
| Zorin        | 1        | 0.56%   |
| Xubuntu      | 1        | 0.56%   |
| Ubuntu MATE  | 1        | 0.56%   |
| SteamOS      | 1        | 0.56%   |
| ROSA         | 1        | 0.56%   |
| Rocky Linux  | 1        | 0.56%   |
| Lubuntu      | 1        | 0.56%   |
| Kali         | 1        | 0.56%   |
| Artix        | 1        | 0.56%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.14-desktop-1omv4002 | 9        | 4.25%   |
| 4.15.0-142-generic       | 6        | 2.83%   |
| 5.16.7-desktop-1omv4003  | 5        | 2.36%   |
| 5.4.0-42-generic         | 3        | 1.42%   |
| 5.15.0-46-generic        | 3        | 1.42%   |
| 6.2.0-33-generic         | 2        | 0.94%   |
| 6.2.0-20-generic         | 2        | 0.94%   |
| 6.1.1-arch1-1            | 2        | 0.94%   |
| 6.1.0-9-amd64            | 2        | 0.94%   |
| 5.5.0-1parrot1-amd64     | 2        | 0.94%   |
| 5.4.0-56-generic         | 2        | 0.94%   |
| 5.4.0-47-generic         | 2        | 0.94%   |
| 5.4.0-33-generic         | 2        | 0.94%   |
| 5.4.0-109-generic        | 2        | 0.94%   |
| 5.3.0-46-generic         | 2        | 0.94%   |
| 5.19.0-76051900-generic  | 2        | 0.94%   |
| 5.19.0-43-generic        | 2        | 0.94%   |
| 5.13.0-35-generic        | 2        | 0.94%   |
| 5.11.0-43-generic        | 2        | 0.94%   |
| 5.0.0-25-generic         | 2        | 0.94%   |
| 4.15.0-88-generic        | 2        | 0.94%   |
| 6.6.4-1389.native        | 1        | 0.47%   |
| 6.5.6-76060506-generic   | 1        | 0.47%   |
| 6.5.3-zen1-1-zen         | 1        | 0.47%   |
| 6.5.11-1-MANJARO         | 1        | 0.47%   |
| 6.5.0-9-generic          | 1        | 0.47%   |
| 6.5.0-14-generic         | 1        | 0.47%   |
| 6.4.5-arch1-1            | 1        | 0.47%   |
| 6.4.3-arch1-2            | 1        | 0.47%   |
| 6.3.9-arch1-1            | 1        | 0.47%   |
| 6.3.8-200.fc38.x86_64    | 1        | 0.47%   |
| 6.2.9-300.fc38.x86_64    | 1        | 0.47%   |
| 6.2.9-060209-generic     | 1        | 0.47%   |
| 6.2.8-200.fc37.x86_64    | 1        | 0.47%   |
| 6.2.6-arch1-1            | 1        | 0.47%   |
| 6.2.16-3-pve             | 1        | 0.47%   |
| 6.2.0-76060200-generic   | 1        | 0.47%   |
| 6.2.0-39-generic         | 1        | 0.47%   |
| 6.2.0-36-generic         | 1        | 0.47%   |
| 6.2.0-32-generic         | 1        | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 20       | 10.1%   |
| 5.15.0  | 12       | 6.06%   |
| 4.15.0  | 12       | 6.06%   |
| 5.8.0   | 9        | 4.55%   |
| 5.10.14 | 9        | 4.55%   |
| 6.2.0   | 8        | 4.04%   |
| 5.19.0  | 8        | 4.04%   |
| 5.3.0   | 7        | 3.54%   |
| 5.13.0  | 7        | 3.54%   |
| 5.11.0  | 7        | 3.54%   |
| 5.10.0  | 6        | 3.03%   |
| 6.1.0   | 5        | 2.53%   |
| 5.16.7  | 5        | 2.53%   |
| 5.0.0   | 5        | 2.53%   |
| 6.1.1   | 3        | 1.52%   |
| 5.17.5  | 3        | 1.52%   |
| 4.18.0  | 3        | 1.52%   |
| 6.5.0   | 2        | 1.01%   |
| 6.2.9   | 2        | 1.01%   |
| 6.0.0   | 2        | 1.01%   |
| 5.5.0   | 2        | 1.01%   |
| 5.14.14 | 2        | 1.01%   |
| 6.6.4   | 1        | 0.51%   |
| 6.5.6   | 1        | 0.51%   |
| 6.5.3   | 1        | 0.51%   |
| 6.5.11  | 1        | 0.51%   |
| 6.4.5   | 1        | 0.51%   |
| 6.4.3   | 1        | 0.51%   |
| 6.3.9   | 1        | 0.51%   |
| 6.3.8   | 1        | 0.51%   |
| 6.2.8   | 1        | 0.51%   |
| 6.2.6   | 1        | 0.51%   |
| 6.2.16  | 1        | 0.51%   |
| 6.1.5   | 1        | 0.51%   |
| 6.1.39  | 1        | 0.51%   |
| 6.1.10  | 1        | 0.51%   |
| 6.0.12  | 1        | 0.51%   |
| 6.0.1   | 1        | 0.51%   |
| 5.9.16  | 1        | 0.51%   |
| 5.9.12  | 1        | 0.51%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 20       | 10.36%  |
| 5.15    | 19       | 9.84%   |
| 5.10    | 19       | 9.84%   |
| 6.2     | 12       | 6.22%   |
| 4.15    | 12       | 6.22%   |
| 5.8     | 11       | 5.7%    |
| 5.19    | 10       | 5.18%   |
| 6.1     | 9        | 4.66%   |
| 5.13    | 9        | 4.66%   |
| 5.16    | 8        | 4.15%   |
| 5.11    | 8        | 4.15%   |
| 5.3     | 7        | 3.63%   |
| 6.5     | 5        | 2.59%   |
| 5.17    | 5        | 2.59%   |
| 5.0     | 5        | 2.59%   |
| 6.0     | 4        | 2.07%   |
| 5.9     | 3        | 1.55%   |
| 5.5     | 3        | 1.55%   |
| 5.18    | 3        | 1.55%   |
| 5.14    | 3        | 1.55%   |
| 4.18    | 3        | 1.55%   |
| 6.4     | 2        | 1.04%   |
| 6.3     | 2        | 1.04%   |
| 5.7     | 2        | 1.04%   |
| 5.6     | 2        | 1.04%   |
| 5.12    | 2        | 1.04%   |
| 6.6     | 1        | 0.52%   |
| 4.9     | 1        | 0.52%   |
| 4.4     | 1        | 0.52%   |
| 4.17    | 1        | 0.52%   |
| 3.10    | 1        | 0.52%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 169      | 98.26%  |
| aarch64 | 2        | 1.16%   |
| i686    | 1        | 0.58%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 80       | 44.2%   |
| KDE5          | 36       | 19.89%  |
| Unknown       | 34       | 18.78%  |
| XFCE          | 8        | 4.42%   |
| KDE           | 4        | 2.21%   |
| X-Cinnamon    | 3        | 1.66%   |
| Pantheon      | 3        | 1.66%   |
| MATE          | 3        | 1.66%   |
| sway          | 2        | 1.1%    |
| openbox       | 1        | 0.55%   |
| LXDE          | 1        | 0.55%   |
| KDE4          | 1        | 0.55%   |
| i3            | 1        | 0.55%   |
| Hyprland      | 1        | 0.55%   |
| GNOME Classic | 1        | 0.55%   |
| Deepin        | 1        | 0.55%   |
| awesome       | 1        | 0.55%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 127      | 69.4%   |
| Wayland | 36       | 19.67%  |
| Unknown | 11       | 6.01%   |
| Tty     | 9        | 4.92%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 80       | 44.2%   |
| SDDM    | 35       | 19.34%  |
| GDM3    | 32       | 17.68%  |
| GDM     | 14       | 7.73%   |
| LightDM | 13       | 7.18%   |
| TDM     | 2        | 1.1%    |
| Ly      | 2        | 1.1%    |
| XDM     | 1        | 0.55%   |
| KDM     | 1        | 0.55%   |
| GREETD  | 1        | 0.55%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 64       | 35.96%  |
| en_HK   | 56       | 31.46%  |
| zh_CN   | 16       | 8.99%   |
| Unknown | 14       | 7.87%   |
| zh_TW   | 13       | 7.3%    |
| en_GB   | 6        | 3.37%   |
| zh_HK   | 4        | 2.25%   |
| C       | 3        | 1.69%   |
| en_AU   | 2        | 1.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 99       | 55.93%  |
| BIOS | 78       | 44.07%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 123      | 69.1%   |
| Btrfs   | 18       | 10.11%  |
| Tmpfs   | 14       | 7.87%   |
| Overlay | 9        | 5.06%   |
| Xfs     | 7        | 3.93%   |
| Zfs     | 3        | 1.69%   |
| F2fs    | 1        | 0.56%   |
| Ext3    | 1        | 0.56%   |
| Ext2    | 1        | 0.56%   |
| Unknown | 1        | 0.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 90       | 51.14%  |
| Unknown | 70       | 39.77%  |
| MBR     | 16       | 9.09%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 145      | 81.46%  |
| Yes       | 33       | 18.54%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 120      | 67.42%  |
| Yes       | 58       | 32.58%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 44       | 25.58%  |
| Gigabyte Technology                  | 29       | 16.86%  |
| MSI                                  | 28       | 16.28%  |
| ASRock                               | 17       | 9.88%   |
| Dell                                 | 12       | 6.98%   |
| Lenovo                               | 8        | 4.65%   |
| Hewlett-Packard                      | 8        | 4.65%   |
| Intel                                | 7        | 4.07%   |
| Unknown                              | 6        | 3.49%   |
| Supermicro                           | 2        | 1.16%   |
| Acer                                 | 2        | 1.16%   |
| Soyo                                 | 1        | 0.58%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.58%   |
| Seco                                 | 1        | 0.58%   |
| Huanan                               | 1        | 0.58%   |
| HPE                                  | 1        | 0.58%   |
| Hardkernel                           | 1        | 0.58%   |
| Foxconn                              | 1        | 0.58%   |
| Biostar                              | 1        | 0.58%   |
| BESSTAR Tech                         | 1        | 0.58%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                         | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Unknown                                      | 6        | 3.49%   |
| Intel SKYBAY                                 | 4        | 2.33%   |
| ASUS All Series                              | 4        | 2.33%   |
| MSI MS-7C94                                  | 3        | 1.74%   |
| ASUS H110I-PLUS                              | 3        | 1.74%   |
| MSI MS-7D42                                  | 2        | 1.16%   |
| MSI MS-7C02                                  | 2        | 1.16%   |
| MSI MS-7B93                                  | 2        | 1.16%   |
| HP ProDesk 600 G1 SFF                        | 2        | 1.16%   |
| Gigabyte X570 AORUS ELITE                    | 2        | 1.16%   |
| ASUS Z8NA-D6                                 | 2        | 1.16%   |
| ASUS VM65                                    | 2        | 1.16%   |
| ASUS VM62                                    | 2        | 1.16%   |
| ASRock H410M-ITX/ac                          | 2        | 1.16%   |
| ASRock H410M-HDV                             | 2        | 1.16%   |
| Supermicro PIO-617R-TLN4F+-ST031             | 1        | 0.58%   |
| Supermicro C2SBC-Q                           | 1        | 0.58%   |
| Soyo SY-A68M FS V2.0                         | 1        | 0.58%   |
| Shenzhen Meigao Electronic Equipment HX90G   | 1        | 0.58%   |
| Seco C40                                     | 1        | 0.58%   |
| MSI Pro 3130 Small Form Factor PC            | 1        | 0.58%   |
| MSI MS-7E02                                  | 1        | 0.58%   |
| MSI MS-7D31                                  | 1        | 0.58%   |
| MSI MS-7C52                                  | 1        | 0.58%   |
| MSI MS-7C34                                  | 1        | 0.58%   |
| MSI MS-7B89                                  | 1        | 0.58%   |
| MSI MS-7B78                                  | 1        | 0.58%   |
| MSI MS-7B53                                  | 1        | 0.58%   |
| MSI MS-7A70                                  | 1        | 0.58%   |
| MSI MS-7A40                                  | 1        | 0.58%   |
| MSI MS-7A38                                  | 1        | 0.58%   |
| MSI MS-7918                                  | 1        | 0.58%   |
| MSI MS-7851                                  | 1        | 0.58%   |
| MSI MS-7817                                  | 1        | 0.58%   |
| MSI MS-7808                                  | 1        | 0.58%   |
| MSI MS-7798                                  | 1        | 0.58%   |
| MSI MS-7680                                  | 1        | 0.58%   |
| MSI MS-7599                                  | 1        | 0.58%   |
| MSI KT541AA-UUB a6528hk                      | 1        | 0.58%   |
| Lenovo ZHENGJIUZHE REN9000K-34IMZ 90Q90022CP | 1        | 0.58%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS PRIME                                 | 9        | 5.23%   |
| Dell OptiPlex                              | 6        | 3.49%   |
| ASUS ROG                                   | 6        | 3.49%   |
| Unknown                                    | 6        | 3.49%   |
| Lenovo ThinkCentre                         | 5        | 2.91%   |
| ASUS TUF                                   | 5        | 2.91%   |
| Intel SKYBAY                               | 4        | 2.33%   |
| ASUS All                                   | 4        | 2.33%   |
| MSI MS-7C94                                | 3        | 1.74%   |
| HP ProDesk                                 | 3        | 1.74%   |
| Gigabyte X570                              | 3        | 1.74%   |
| Dell Precision                             | 3        | 1.74%   |
| ASUS H110I-PLUS                            | 3        | 1.74%   |
| MSI MS-7D42                                | 2        | 1.16%   |
| MSI MS-7C02                                | 2        | 1.16%   |
| MSI MS-7B93                                | 2        | 1.16%   |
| HP EliteDesk                               | 2        | 1.16%   |
| Gigabyte B450                              | 2        | 1.16%   |
| Dell Inspiron                              | 2        | 1.16%   |
| ASUS Z8NA-D6                               | 2        | 1.16%   |
| ASUS VM65                                  | 2        | 1.16%   |
| ASUS VM62                                  | 2        | 1.16%   |
| ASRock H410M-ITX                           | 2        | 1.16%   |
| ASRock H410M-HDV                           | 2        | 1.16%   |
| Supermicro PIO-617R-TLN4F+-ST031           | 1        | 0.58%   |
| Supermicro C2SBC-Q                         | 1        | 0.58%   |
| Soyo SY-A68M                               | 1        | 0.58%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1        | 0.58%   |
| Seco C40                                   | 1        | 0.58%   |
| MSI Pro                                    | 1        | 0.58%   |
| MSI MS-7E02                                | 1        | 0.58%   |
| MSI MS-7D31                                | 1        | 0.58%   |
| MSI MS-7C52                                | 1        | 0.58%   |
| MSI MS-7C34                                | 1        | 0.58%   |
| MSI MS-7B89                                | 1        | 0.58%   |
| MSI MS-7B78                                | 1        | 0.58%   |
| MSI MS-7B53                                | 1        | 0.58%   |
| MSI MS-7A70                                | 1        | 0.58%   |
| MSI MS-7A40                                | 1        | 0.58%   |
| MSI MS-7A38                                | 1        | 0.58%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 20       | 11.63%  |
| 2020    | 16       | 9.3%    |
| 2019    | 16       | 9.3%    |
| 2014    | 14       | 8.14%   |
| 2016    | 13       | 7.56%   |
| 2013    | 13       | 7.56%   |
| 2021    | 12       | 6.98%   |
| 2022    | 11       | 6.4%    |
| 2017    | 10       | 5.81%   |
| 2010    | 10       | 5.81%   |
| 2015    | 8        | 4.65%   |
| 2011    | 7        | 4.07%   |
| 2012    | 6        | 3.49%   |
| 2023    | 5        | 2.91%   |
| 2008    | 5        | 2.91%   |
| 2009    | 3        | 1.74%   |
| Unknown | 2        | 1.16%   |
| 2007    | 1        | 0.58%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 172      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 167      | 97.09%  |
| Enabled  | 5        | 2.91%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 172      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 41       | 23.16%  |
| 32.01-64.0  | 35       | 19.77%  |
| 8.01-16.0   | 32       | 18.08%  |
| 64.01-256.0 | 22       | 12.43%  |
| 3.01-4.0    | 20       | 11.3%   |
| 4.01-8.0    | 19       | 10.73%  |
| 24.01-32.0  | 5        | 2.82%   |
| 1.01-2.0    | 2        | 1.13%   |
| 2.01-3.0    | 1        | 0.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 52       | 26.8%   |
| 2.01-3.0   | 43       | 22.16%  |
| 4.01-8.0   | 39       | 20.1%   |
| 3.01-4.0   | 22       | 11.34%  |
| 8.01-16.0  | 16       | 8.25%   |
| 0.51-1.0   | 11       | 5.67%   |
| 16.01-24.0 | 5        | 2.58%   |
| 0.01-0.5   | 3        | 1.55%   |
| 32.01-64.0 | 2        | 1.03%   |
| 24.01-32.0 | 1        | 0.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 72       | 39.56%  |
| 2      | 50       | 27.47%  |
| 3      | 32       | 17.58%  |
| 5      | 10       | 5.49%   |
| 4      | 9        | 4.95%   |
| 6      | 3        | 1.65%   |
| 9      | 2        | 1.1%    |
| 0      | 2        | 1.1%    |
| 11     | 1        | 0.55%   |
| 7      | 1        | 0.55%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 124      | 71.26%  |
| Yes       | 50       | 28.74%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 168      | 97.67%  |
| No        | 4        | 2.33%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 96       | 54.24%  |
| No        | 81       | 45.76%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 93       | 52.54%  |
| Yes       | 84       | 47.46%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Hong Kong | 172      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Central          | 101      | 54.3%   |
| Kowloon          | 11       | 5.91%   |
| Tuen Mun         | 9        | 4.84%   |
| Hong Kong        | 7        | 3.76%   |
| Wanchai          | 4        | 2.15%   |
| Ngau Wu Tok      | 4        | 2.15%   |
| Yuen Long        | 3        | 1.61%   |
| Tseung Kwan O    | 3        | 1.61%   |
| To Kwa Wan       | 3        | 1.61%   |
| Tai Po           | 3        | 1.61%   |
| Shatin           | 3        | 1.61%   |
| Ma On Shan Tsuen | 3        | 1.61%   |
| Hung Hom         | 3        | 1.61%   |
| Quarry Bay       | 2        | 1.08%   |
| Kwu Tung         | 2        | 1.08%   |
| Kwai Chung       | 2        | 1.08%   |
| Ho Man Tin       | 2        | 1.08%   |
| Cheung Sha Lan   | 2        | 1.08%   |
| Chai Wan         | 2        | 1.08%   |
| Wong Tai Sin     | 1        | 0.54%   |
| Tung Chung       | 1        | 0.54%   |
| Tsuen Wan        | 1        | 0.54%   |
| Tsimshatsui      | 1        | 0.54%   |
| Tai Wan To       | 1        | 0.54%   |
| Tai Kok Tsui     | 1        | 0.54%   |
| Sheung Shui      | 1        | 0.54%   |
| Sham Shui Po     | 1        | 0.54%   |
| Sha Tin Wai      | 1        | 0.54%   |
| Sai Kung         | 1        | 0.54%   |
| North Point      | 1        | 0.54%   |
| Ma Wan           | 1        | 0.54%   |
| Ma On Shan       | 1        | 0.54%   |
| Lai Chi Kok      | 1        | 0.54%   |
| Kwun Hang        | 1        | 0.54%   |
| Kowloon Bay      | 1        | 0.54%   |
| Fo Tan           | 1        | 0.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 49       | 72     | 14.89%  |
| WDC                         | 44       | 75     | 13.37%  |
| Samsung Electronics         | 30       | 48     | 9.12%   |
| Toshiba                     | 25       | 38     | 7.6%    |
| SanDisk                     | 18       | 20     | 5.47%   |
| Kingston                    | 16       | 21     | 4.86%   |
| A-DATA Technology           | 15       | 21     | 4.56%   |
| Crucial                     | 11       | 18     | 3.34%   |
| Hitachi                     | 9        | 18     | 2.74%   |
| Silicon Motion              | 8        | 11     | 2.43%   |
| SK hynix                    | 6        | 10     | 1.82%   |
| HGST                        | 6        | 7      | 1.82%   |
| Unknown                     | 6        | 6      | 1.82%   |
| Intel                       | 5        | 16     | 1.52%   |
| Transcend                   | 4        | 5      | 1.22%   |
| Phison                      | 4        | 7      | 1.22%   |
| LITEON                      | 4        | 4      | 1.22%   |
| Fujitsu                     | 4        | 9      | 1.22%   |
| Unknown                     | 3        | 3      | 0.91%   |
| Plextor                     | 3        | 3      | 0.91%   |
| Netac                       | 3        | 3      | 0.91%   |
| MAXIO Technology (Hangzhou) | 3        | 4      | 0.91%   |
| KIOXIA                      | 3        | 4      | 0.91%   |
| JMicron Technology          | 3        | 6      | 0.91%   |
| Hikvision                   | 3        | 3      | 0.91%   |
| Gigabyte Technology         | 3        | 6      | 0.91%   |
| DOGGO                       | 3        | 3      | 0.91%   |
| ZHITAI                      | 2        | 4      | 0.61%   |
| Team                        | 2        | 2      | 0.61%   |
| Micron/Crucial Technology   | 2        | 2      | 0.61%   |
| Lite-On                     | 2        | 4      | 0.61%   |
| KIOXIA-EXCERIA              | 2        | 3      | 0.61%   |
| ADATA Technology            | 2        | 4      | 0.61%   |
| Yangtze Memory Technologies | 1        | 1      | 0.3%    |
| XPG                         | 1        | 1      | 0.3%    |
| WXC-R1                      | 1        | 1      | 0.3%    |
| tigo                        | 1        | 1      | 0.3%    |
| Teclast                     | 1        | 1      | 0.3%    |
| SPCC                        | 1        | 1      | 0.3%    |
| ShiJi                       | 1        | 1      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB               | 6        | 1.64%   |
| Unknown                              | 6        | 1.64%   |
| Samsung SSD 860 EVO 1TB              | 5        | 1.37%   |
| A-DATA SP550 240GB SSD               | 5        | 1.37%   |
| WDC WD10EZEX-08WN4A0 1TB             | 4        | 1.09%   |
| Toshiba DT01ACA050 500GB             | 4        | 1.09%   |
| Seagate ST500DM002-1BD142 500GB      | 4        | 1.09%   |
| Kingston SA400S37480G 480GB SSD      | 4        | 1.09%   |
| WDC WD30EZRX-00D8PB0 3TB             | 3        | 0.82%   |
| Toshiba DT01ACA300 3TB               | 3        | 0.82%   |
| Toshiba DT01ACA200 2TB               | 3        | 0.82%   |
| Seagate ST4000DM004-2CV104 4TB       | 3        | 0.82%   |
| Seagate ST3500413AS 500GB            | 3        | 0.82%   |
| Seagate ST2000DM008-2FR102 2TB       | 3        | 0.82%   |
| SanDisk NVMe SSD Drive 1TB           | 3        | 0.82%   |
| JMicron Generic 250GB                | 3        | 0.82%   |
| Fujitsu F300 480GB                   | 3        | 0.82%   |
| DOGGO DQ-60G SSD                     | 3        | 0.82%   |
| Crucial CT500MX500SSD1 500GB         | 3        | 0.82%   |
| WDC WDS200T2B0A 2TB SSD              | 2        | 0.55%   |
| Toshiba MG05ACA800E 8TB              | 2        | 0.55%   |
| SK hynix SC311 SATA 128GB SSD        | 2        | 0.55%   |
| SK hynix BC711 NVMe 256GB            | 2        | 0.55%   |
| Silicon Motion NVMe SSD Drive 512GB  | 2        | 0.55%   |
| Silicon Motion NVMe SSD Drive 1024GB | 2        | 0.55%   |
| Seagate ST3500418AS 500GB            | 2        | 0.55%   |
| Seagate ST3250318AS 250GB            | 2        | 0.55%   |
| Seagate ST3250310AS 250GB            | 2        | 0.55%   |
| Seagate ST320LT007-9ZV142 320GB      | 2        | 0.55%   |
| Seagate ST3160815AS 160GB            | 2        | 0.55%   |
| Seagate ST2000DM001-1CH164 2TB       | 2        | 0.55%   |
| Seagate ST1000DM010-2EP102 1TB       | 2        | 0.55%   |
| Seagate ST1000DM003-1SB102 1TB       | 2        | 0.55%   |
| Seagate ST1000DM003-1ER162 1TB       | 2        | 0.55%   |
| Sandisk WD_BLACK SN770 1TB           | 2        | 0.55%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB | 2        | 0.55%   |
| SanDisk SDSSDX120GG25 120GB          | 2        | 0.55%   |
| Samsung SSD 970 EVO Plus 1TB         | 2        | 0.55%   |
| Samsung SSD 870 QVO 2TB              | 2        | 0.55%   |
| Samsung SSD 860 EVO 500GB            | 2        | 0.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Seagate  | 48       | 71     | 38.71%  |
| WDC      | 32       | 59     | 25.81%  |
| Toshiba  | 25       | 38     | 20.16%  |
| Hitachi  | 9        | 18     | 7.26%   |
| HGST     | 6        | 7      | 4.84%   |
| Unknown  | 1        | 1      | 0.81%   |
| Maxtor   | 1        | 1      | 0.81%   |
| HGST HTS | 1        | 1      | 0.81%   |
| Fujitsu  | 1        | 1      | 0.81%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 17       | 28     | 16.35%  |
| A-DATA Technology   | 12       | 18     | 11.54%  |
| Kingston            | 11       | 16     | 10.58%  |
| Crucial             | 8        | 15     | 7.69%   |
| WDC                 | 7        | 7      | 6.73%   |
| SanDisk             | 6        | 6      | 5.77%   |
| Transcend           | 4        | 5      | 3.85%   |
| Netac               | 3        | 3      | 2.88%   |
| LITEON              | 3        | 3      | 2.88%   |
| JMicron Technology  | 3        | 6      | 2.88%   |
| Fujitsu             | 3        | 8      | 2.88%   |
| DOGGO               | 3        | 3      | 2.88%   |
| Team                | 2        | 2      | 1.92%   |
| SK hynix            | 2        | 6      | 1.92%   |
| Plextor             | 2        | 2      | 1.92%   |
| ZHITAI              | 1        | 1      | 0.96%   |
| tigo                | 1        | 1      | 0.96%   |
| SPCC                | 1        | 1      | 0.96%   |
| ShiJi               | 1        | 1      | 0.96%   |
| PNY                 | 1        | 1      | 0.96%   |
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
| HDD     | 102      | 197    | 37.23%  |
| SSD     | 87       | 150    | 31.75%  |
| NVMe    | 72       | 128    | 26.28%  |
| Unknown | 12       | 13     | 4.38%   |
| MMC     | 1        | 1      | 0.36%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 142      | 335    | 61.47%  |
| NVMe | 72       | 127    | 31.17%  |
| SAS  | 16       | 26     | 6.93%   |
| MMC  | 1        | 1      | 0.43%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 94       | 167    | 47.24%  |
| 0.51-1.0   | 50       | 73     | 25.13%  |
| 1.01-2.0   | 22       | 31     | 11.06%  |
| 3.01-4.0   | 12       | 36     | 6.03%   |
| 2.01-3.0   | 11       | 19     | 5.53%   |
| 4.01-10.0  | 8        | 17     | 4.02%   |
| 10.01-20.0 | 2        | 4      | 1.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 38       | 20.21%  |
| More than 3000 | 26       | 13.83%  |
| 251-500        | 24       | 12.77%  |
| 501-1000       | 23       | 12.23%  |
| 1001-2000      | 20       | 10.64%  |
| 51-100         | 20       | 10.64%  |
| 2001-3000      | 13       | 6.91%   |
| Unknown        | 11       | 5.85%   |
| 21-50          | 7        | 3.72%   |
| 1-20           | 6        | 3.19%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 68       | 33.83%  |
| 101-250        | 27       | 13.43%  |
| 21-50          | 19       | 9.45%   |
| 251-500        | 18       | 8.96%   |
| 501-1000       | 16       | 7.96%   |
| 51-100         | 13       | 6.47%   |
| 1001-2000      | 12       | 5.97%   |
| Unknown        | 11       | 5.47%   |
| 2001-3000      | 10       | 4.98%   |
| More than 3000 | 7        | 3.48%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Desktops | Drives | Percent |
|----------------------------------------------|----------|--------|---------|
| ZHITAI TiPlus5000 512GB                      | 1        | 1      | 4.55%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD             | 1        | 1      | 4.55%   |
| WDC WD30EZRX-00D8PB0 3TB                     | 1        | 1      | 4.55%   |
| WDC WD10EZEX-60WN4A1 1TB                     | 1        | 1      | 4.55%   |
| WDC WD10EZEX-00RKKA0 1TB                     | 1        | 1      | 4.55%   |
| WDC WD10EALS-00Z8A0 1TB                      | 1        | 2      | 4.55%   |
| Toshiba MK1655GSX 160GB                      | 1        | 1      | 4.55%   |
| Toshiba MK1252GSX 120GB                      | 1        | 1      | 4.55%   |
| Toshiba DT01ACA100 1TB                       | 1        | 1      | 4.55%   |
| Seagate ST500DM002-1BD142 500GB              | 1        | 1      | 4.55%   |
| Seagate ST3500418AS 500GB                    | 1        | 1      | 4.55%   |
| Seagate ST3250310AS 250GB                    | 1        | 1      | 4.55%   |
| Seagate ST3160815AS 160GB                    | 1        | 1      | 4.55%   |
| Seagate ST1000LM014-1EJ164-SSHD 1TB          | 1        | 1      | 4.55%   |
| Samsung Electronics MZVLB512HAJQ-000L7 512GB | 1        | 1      | 4.55%   |
| LITEON IT LCS-128L9S-11 2.5 7mm 128GB SSD    | 1        | 1      | 4.55%   |
| Kingston SA400S37480G 480GB SSD              | 1        | 1      | 4.55%   |
| Intel SSDPEKKW128G7 128GB                    | 1        | 1      | 4.55%   |
| Intel SSD 600P Series 256GB                  | 1        | 4      | 4.55%   |
| Hitachi HTS542512K9SA00 120GB                | 1        | 1      | 4.55%   |
| HGST HTS 541010A9E680 1TB                    | 1        | 1      | 4.55%   |
| Crucial CT500MX500SSD1 500GB                 | 1        | 2      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 5      | 23.81%  |
| WDC                 | 4        | 6      | 19.05%  |
| Toshiba             | 3        | 3      | 14.29%  |
| Intel               | 2        | 5      | 9.52%   |
| ZHITAI              | 1        | 1      | 4.76%   |
| Samsung Electronics | 1        | 1      | 4.76%   |
| LITEON              | 1        | 1      | 4.76%   |
| Kingston            | 1        | 1      | 4.76%   |
| Hitachi             | 1        | 1      | 4.76%   |
| HGST HTS            | 1        | 1      | 4.76%   |
| Crucial             | 1        | 2      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Seagate  | 5        | 5      | 38.46%  |
| WDC      | 3        | 5      | 23.08%  |
| Toshiba  | 3        | 3      | 23.08%  |
| Hitachi  | 1        | 1      | 7.69%   |
| HGST HTS | 1        | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 12       | 15     | 60%     |
| NVMe | 4        | 7      | 20%     |
| SSD  | 4        | 5      | 20%     |

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
| Detected | 97       | 238    | 49.24%  |
| Works    | 80       | 224    | 40.61%  |
| Malfunc  | 20       | 27     | 10.15%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 124      | 44.77%  |
| AMD                              | 45       | 16.25%  |
| SanDisk                          | 17       | 6.14%   |
| Samsung Electronics              | 17       | 6.14%   |
| ASMedia Technology               | 13       | 4.69%   |
| Silicon Motion                   | 9        | 3.25%   |
| Phison Electronics               | 7        | 2.53%   |
| Micron/Crucial Technology        | 5        | 1.81%   |
| MAXIO Technology (Hangzhou)      | 5        | 1.81%   |
| Kingston Technology Company      | 5        | 1.81%   |
| ADATA Technology                 | 5        | 1.81%   |
| SK hynix                         | 4        | 1.44%   |
| Marvell Technology Group         | 4        | 1.44%   |
| KIOXIA                           | 4        | 1.44%   |
| Yangtze Memory Technologies      | 3        | 1.08%   |
| LSI Logic / Symbios Logic        | 2        | 0.72%   |
| Lite-On Technology               | 2        | 0.72%   |
| JMicron Technology               | 2        | 0.72%   |
| VIA Technologies                 | 1        | 0.36%   |
| Shenzhen Shichuangyi Electronics | 1        | 0.36%   |
| Nvidia                           | 1        | 0.36%   |
| Integrated Technology Express    | 1        | 0.36%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 28       | 8.75%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 17       | 5.31%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 14       | 4.38%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 13       | 4.06%   |
| AMD 400 Series Chipset SATA Controller                                                  | 13       | 4.06%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 12       | 3.75%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 11       | 3.44%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 10       | 3.13%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 9        | 2.81%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 8        | 2.5%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 7        | 2.19%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7        | 2.19%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 5        | 1.56%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 5        | 1.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 1.56%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 5        | 1.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 5        | 1.56%   |
| AMD 500 Series Chipset SATA Controller                                                  | 5        | 1.56%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 5        | 1.56%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 4        | 1.25%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 1.25%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 4        | 1.25%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 1.25%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 3        | 0.94%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 3        | 0.94%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                 | 3        | 0.94%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                   | 3        | 0.94%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 3        | 0.94%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 3        | 0.94%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                            | 3        | 0.94%   |
| KIOXIA NVMe SSD                                                                         | 3        | 0.94%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                                      | 3        | 0.94%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 3        | 0.94%   |
| Intel SSD 600P Series                                                                   | 3        | 0.94%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3        | 0.94%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3        | 0.94%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 3        | 0.94%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 0.94%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 0.94%   |
| Yangtze Memory ZHITAI PC005 NVMe SSD                                                    | 2        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 162      | 61.36%  |
| NVMe | 72       | 27.27%  |
| IDE  | 16       | 6.06%   |
| RAID | 12       | 4.55%   |
| SAS  | 2        | 0.76%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 123      | 71.51%  |
| AMD     | 47       | 27.33%  |
| Unknown | 2        | 1.16%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Pentium CPU G4560 @ 3.50GHz      | 5        | 2.89%   |
| AMD Ryzen 7 5700G with Radeon Graphics | 5        | 2.89%   |
| Intel Core i7-6700 CPU @ 3.40GHz       | 4        | 2.31%   |
| Intel Core i7-4790 CPU @ 3.60GHz       | 4        | 2.31%   |
| AMD Ryzen 5 3600 6-Core Processor      | 4        | 2.31%   |
| Intel Core i7-9700 CPU @ 3.00GHz       | 3        | 1.73%   |
| Intel Core i7-7700K CPU @ 4.20GHz      | 3        | 1.73%   |
| Intel Core i5-6400 CPU @ 2.70GHz       | 3        | 1.73%   |
| Intel Core i5-4460 CPU @ 3.20GHz       | 3        | 1.73%   |
| Intel Core i5-3470 CPU @ 3.20GHz       | 3        | 1.73%   |
| Intel Core i3-10100 CPU @ 3.60GHz      | 3        | 1.73%   |
| AMD Ryzen 9 7950X 16-Core Processor    | 3        | 1.73%   |
| AMD Ryzen 9 5900X 12-Core Processor    | 3        | 1.73%   |
| AMD Ryzen 7 3700X 8-Core Processor     | 3        | 1.73%   |
| Intel Xeon CPU X5675 @ 3.07GHz         | 2        | 1.16%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz    | 2        | 1.16%   |
| Intel Core i7-9700K CPU @ 3.60GHz      | 2        | 1.16%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 2        | 1.16%   |
| Intel Core i7-2600 CPU @ 3.40GHz       | 2        | 1.16%   |
| Intel Core i5-8400 CPU @ 2.80GHz       | 2        | 1.16%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 2        | 1.16%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 2        | 1.16%   |
| Intel Core i3-7100 CPU @ 3.90GHz       | 2        | 1.16%   |
| Intel 12th Gen Core i7-12700K          | 2        | 1.16%   |
| Intel 12th Gen Core i5-12600K          | 2        | 1.16%   |
| Intel 12th Gen Core i5-12500           | 2        | 1.16%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz | 2        | 1.16%   |
| AMD Ryzen 9 3900X 12-Core Processor    | 2        | 1.16%   |
| AMD Ryzen 5 5600X 6-Core Processor     | 2        | 1.16%   |
| AMD Ryzen 5 2600X Six-Core Processor   | 2        | 1.16%   |
| AMD Phenom II X6 1055T Processor       | 2        | 1.16%   |
|                                        | 2        | 1.16%   |
| Intel Xeon CPU X5650 @ 2.67GHz         | 1        | 0.58%   |
| Intel Xeon CPU E5-2697 v2 @ 2.70GHz    | 1        | 0.58%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz    | 1        | 0.58%   |
| Intel Xeon CPU E3-1265L v3 @ 2.50GHz   | 1        | 0.58%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz    | 1        | 0.58%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz    | 1        | 0.58%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz | 1        | 0.58%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz | 1        | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i7          | 27       | 15.61%  |
| Intel Core i5          | 25       | 14.45%  |
| Other                  | 23       | 13.29%  |
| Intel Core i3          | 17       | 9.83%   |
| AMD Ryzen 7            | 13       | 7.51%   |
| AMD Ryzen 5            | 12       | 6.94%   |
| Intel Xeon             | 10       | 5.78%   |
| Intel Pentium          | 10       | 5.78%   |
| AMD Ryzen 9            | 9        | 5.2%    |
| Intel Celeron          | 6        | 3.47%   |
| AMD Phenom II X4       | 3        | 1.73%   |
| Intel Core i9          | 2        | 1.16%   |
| AMD Phenom II X6       | 2        | 1.16%   |
| AMD FX                 | 2        | 1.16%   |
| Intel Pentium Gold     | 1        | 0.58%   |
| Intel Pentium Dual     | 1        | 0.58%   |
| Intel Core 2 Quad      | 1        | 0.58%   |
| Intel Core 2 Extreme   | 1        | 0.58%   |
| Intel Core 2 Duo       | 1        | 0.58%   |
| AMD Ryzen Threadripper | 1        | 0.58%   |
| AMD Ryzen Embedded     | 1        | 0.58%   |
| AMD Opteron            | 1        | 0.58%   |
| AMD Athlon II X4       | 1        | 0.58%   |
| AMD Athlon 64 X2       | 1        | 0.58%   |
| AMD A8                 | 1        | 0.58%   |
| AMD A10                | 1        | 0.58%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 57       | 32.95%  |
| 2       | 35       | 20.23%  |
| 8       | 26       | 15.03%  |
| 6       | 25       | 14.45%  |
| 12      | 13       | 7.51%   |
| 16      | 7        | 4.05%   |
| 10      | 4        | 2.31%   |
| 3       | 2        | 1.16%   |
| Unknown | 2        | 1.16%   |
| 24      | 1        | 0.58%   |
| 14      | 1        | 0.58%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 166      | 96.51%  |
| 2       | 4        | 2.33%   |
| Unknown | 2        | 1.16%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 113      | 65.32%  |
| 1       | 58       | 33.53%  |
| Unknown | 2        | 1.16%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 172      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 48       | 26.82%  |
| 0x306c3    | 12       | 6.7%    |
| 0x90672    | 10       | 5.59%   |
| 0x906e9    | 9        | 5.03%   |
| 0x306a9    | 7        | 3.91%   |
| 0x206a7    | 7        | 3.91%   |
| 0x506e3    | 6        | 3.35%   |
| 0x906ed    | 5        | 2.79%   |
| 0x906ea    | 5        | 2.79%   |
| 0x0a50000d | 4        | 2.23%   |
| 0x0800820d | 4        | 2.23%   |
| 0xa0653    | 3        | 1.68%   |
| 0x806e9    | 3        | 1.68%   |
| 0x40651    | 3        | 1.68%   |
| 0x20652    | 3        | 1.68%   |
| 0x0a50000c | 3        | 1.68%   |
| 0x0a201009 | 3        | 1.68%   |
| 0x08701021 | 3        | 1.68%   |
| 0x08701013 | 3        | 1.68%   |
| 0xa0671    | 2        | 1.12%   |
| 0x90675    | 2        | 1.12%   |
| 0x306e4    | 2        | 1.12%   |
| 0x206c2    | 2        | 1.12%   |
| 0x0a601203 | 2        | 1.12%   |
| 0x0a201016 | 2        | 1.12%   |
| 0x06003106 | 2        | 1.12%   |
| 0x010000c8 | 2        | 1.12%   |
| 0xb06e0    | 1        | 0.56%   |
| 0xb0671    | 1        | 0.56%   |
| 0xa0655    | 1        | 0.56%   |
| 0x906eb    | 1        | 0.56%   |
| 0x706a1    | 1        | 0.56%   |
| 0x6fd      | 1        | 0.56%   |
| 0x30678    | 1        | 0.56%   |
| 0x20655    | 1        | 0.56%   |
| 0x106e5    | 1        | 0.56%   |
| 0x1067a    | 1        | 0.56%   |
| 0x10677    | 1        | 0.56%   |
| 0x0a601201 | 1        | 0.56%   |
| 0x0a20120a | 1        | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 30       | 17.24%  |
| Haswell          | 22       | 12.64%  |
| Zen 3            | 13       | 7.47%   |
| Alderlake Hybrid | 13       | 7.47%   |
| Unknown          | 12       | 6.9%    |
| Zen 2            | 11       | 6.32%   |
| IvyBridge        | 11       | 6.32%   |
| Skylake          | 10       | 5.75%   |
| SandyBridge      | 8        | 4.6%    |
| Westmere         | 7        | 4.02%   |
| CometLake        | 7        | 4.02%   |
| Zen+             | 6        | 3.45%   |
| K10              | 6        | 3.45%   |
| Zen              | 2        | 1.15%   |
| Steamroller      | 2        | 1.15%   |
| Piledriver       | 2        | 1.15%   |
| Penryn           | 2        | 1.15%   |
| Icelake          | 2        | 1.15%   |
| Core             | 2        | 1.15%   |
| Silvermont       | 1        | 0.57%   |
| Nehalem          | 1        | 0.57%   |
| K8 Hammer        | 1        | 0.57%   |
| Gracemont        | 1        | 0.57%   |
| Goldmont plus    | 1        | 0.57%   |
| Excavator        | 1        | 0.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Intel             | 74       | 38.95%  |
| Nvidia            | 73       | 38.42%  |
| AMD               | 42       | 22.11%  |
| ASPEED Technology | 1        | 0.53%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 12       | 6.12%   |
| Intel HD Graphics 610                                                       | 7        | 3.57%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 7        | 3.57%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 7        | 3.57%   |
| Intel HD Graphics 530                                                       | 5        | 2.55%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 5        | 2.55%   |
| Intel AlderLake-S GT1                                                       | 5        | 2.55%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 5        | 2.55%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 4        | 2.04%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 2.04%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 2.04%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 4        | 2.04%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 4        | 2.04%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4        | 2.04%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 1.53%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 1.53%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 1.53%   |
| Intel HD Graphics 630                                                       | 3        | 1.53%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 3        | 1.53%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.53%   |
| AMD Raphael                                                                 | 3        | 1.53%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3        | 1.53%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 2        | 1.02%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 1.02%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 1.02%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 1.02%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 2        | 1.02%   |
| Nvidia AD104 [GeForce RTX 4070 Ti]                                          | 2        | 1.02%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 1.02%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 2        | 1.02%   |
| Intel HD Graphics 620                                                       | 2        | 1.02%   |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 1.02%   |
| Intel Alder Lake-S GT1 [UHD Graphics 770]                                   | 2        | 1.02%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.02%   |
| AMD RS780 [Radeon HD 3200]                                                  | 2        | 1.02%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 2        | 1.02%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 1.02%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 2        | 1.02%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 2        | 1.02%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 63       | 36.42%  |
| 1 x Intel      | 60       | 34.68%  |
| 1 x AMD        | 33       | 19.08%  |
| Intel + Nvidia | 6        | 3.47%   |
| AMD + Nvidia   | 4        | 2.31%   |
| 2 x AMD        | 3        | 1.73%   |
| Other          | 2        | 1.16%   |
| 3 x AMD        | 1        | 0.58%   |
| 1 x ASPEED     | 1        | 0.58%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 123      | 69.89%  |
| Proprietary | 44       | 25%     |
| Unknown     | 9        | 5.11%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 87       | 48.88%  |
| 7.01-8.0   | 21       | 11.8%   |
| 0.51-1.0   | 17       | 9.55%   |
| 3.01-4.0   | 16       | 8.99%   |
| 1.01-2.0   | 13       | 7.3%    |
| 0.01-0.5   | 8        | 4.49%   |
| 5.01-6.0   | 7        | 3.93%   |
| 8.01-16.0  | 5        | 2.81%   |
| 2.01-3.0   | 2        | 1.12%   |
| 4.01-5.0   | 1        | 0.56%   |
| 16.01-24.0 | 1        | 0.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 18       | 9.63%   |
| Dell                 | 18       | 9.63%   |
| Goldstar             | 17       | 9.09%   |
| AOC                  | 17       | 9.09%   |
| Philips              | 12       | 6.42%   |
| Ancor Communications | 9        | 4.81%   |
| BenQ                 | 8        | 4.28%   |
| Acer                 | 8        | 4.28%   |
| Unknown              | 6        | 3.21%   |
| JRY                  | 6        | 3.21%   |
| AMO                  | 6        | 3.21%   |
| ViewSonic            | 5        | 2.67%   |
| IPS                  | 5        | 2.67%   |
| ASUSTek Computer     | 5        | 2.67%   |
| Lenovo               | 4        | 2.14%   |
| Hewlett-Packard      | 4        | 2.14%   |
| SKY                  | 2        | 1.07%   |
| RTK                  | 2        | 1.07%   |
| HSO                  | 2        | 1.07%   |
| Eizo                 | 2        | 1.07%   |
| CHR                  | 2        | 1.07%   |
| AUS                  | 2        | 1.07%   |
| Xiaomi               | 1        | 0.53%   |
| Xiangye              | 1        | 0.53%   |
| Unknown (AAA)        | 1        | 0.53%   |
| Toshiba              | 1        | 0.53%   |
| TFC                  | 1        | 0.53%   |
| TCT                  | 1        | 0.53%   |
| TCL                  | 1        | 0.53%   |
| Sony                 | 1        | 0.53%   |
| SKG                  | 1        | 0.53%   |
| SAC                  | 1        | 0.53%   |
| PDA                  | 1        | 0.53%   |
| PANDA                | 1        | 0.53%   |
| Mi                   | 1        | 0.53%   |
| LYC                  | 1        | 0.53%   |
| LG Electronics       | 1        | 0.53%   |
| LDR                  | 1        | 0.53%   |
| Lanix                | 1        | 0.53%   |
| HPN                  | 1        | 0.53%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| JRY HDMI JRY1330 1920x1080 293x165mm 13.2-inch                        | 6        | 3.09%   |
| IPS HDMI IPS2700 1920x1080 597x336mm 27.0-inch                        | 4        | 2.06%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 4        | 2.06%   |
| AMO HS241P AMO2800 3840x2160 620x350mm 28.0-inch                      | 4        | 2.06%   |
| Unknown LCD Monitor XMD Mi TV 1360x768                                | 3        | 1.55%   |
| AOC U2790B AOC2790 3840x2160 597x336mm 27.0-inch                      | 3        | 1.55%   |
| Philips PHL 323E7 PHLC121 1920x1080 698x393mm 31.5-inch               | 2        | 1.03%   |
| Lenovo LEN L24e-20 LEN65DF 1920x1080 527x296mm 23.8-inch              | 2        | 1.03%   |
| HSO B2431M HSO2431 3840x2160 520x290mm 23.4-inch                      | 2        | 1.03%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch            | 2        | 1.03%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch              | 2        | 1.03%   |
| Dell U2417H DEL40E7 1920x1080 527x296mm 23.8-inch                     | 2        | 1.03%   |
| CHR CH7511B CHR7511 1920x1080 519x324mm 24.1-inch                     | 2        | 1.03%   |
| AOC 24B1W AOC2401 1920x1080 521x293mm 23.5-inch                       | 2        | 1.03%   |
| Xiaomi Mi TV XMD004A 1440x900 708x398mm 32.0-inch                     | 1        | 0.52%   |
| Xiangye XE2400 XYE2380 3840x2160 520x310mm 23.8-inch                  | 1        | 0.52%   |
| ViewSonic VX2260WM VSCFC21 1920x1080 480x270mm 21.7-inch              | 1        | 0.52%   |
| ViewSonic VX2239 SERIES VSC5225 1920x1080 480x270mm 21.7-inch         | 1        | 0.52%   |
| ViewSonic VG921m VSC301E 1280x1024 380x300mm 19.1-inch                | 1        | 0.52%   |
| ViewSonic VA2465 SERIES VSCB730 1920x1080 521x293mm 23.5-inch         | 1        | 0.52%   |
| ViewSonic VA1616wSERIES VSC0021 1366x768 348x197mm 15.7-inch          | 1        | 0.52%   |
| Unknown LCD Monitor hp f1523 1024x768                                 | 1        | 0.52%   |
| Unknown LCD Monitor GBT G32QC A 2560x1440                             | 1        | 0.52%   |
| Unknown LCD Monitor FST V22T-1R LED 1920x1080                         | 1        | 0.52%   |
| Unknown (AAA) U270 AAA2700 3840x2160 596x335mm 26.9-inch              | 1        | 0.52%   |
| Toshiba TV TSB2634 1920x1080 697x392mm 31.5-inch                      | 1        | 0.52%   |
| TFC TF2421 TFC2421 1920x1080 527x296mm 23.8-inch                      | 1        | 0.52%   |
| TCT DP1080P60 TCT0270 2560x1600 520x290mm 23.4-inch                   | 1        | 0.52%   |
| TCL SMART TV TCL5507 1920x1080 1209x680mm 54.6-inch                   | 1        | 0.52%   |
| Sony TV SNY4B03 1920x1080 708x398mm 32.0-inch                         | 1        | 0.52%   |
| SKY TV Monitor SKY0030 1920x1080 708x398mm 32.0-inch                  | 1        | 0.52%   |
| SKY M16U1 SKY0156 3840x2160 345x194mm 15.6-inch                       | 1        | 0.52%   |
| SKG PMO G270-CQK SKG2712 2560x1440 530x280mm 23.6-inch                | 1        | 0.52%   |
| Samsung Electronics SyncMaster SAM0372 1680x1050 459x296mm 21.5-inch  | 1        | 0.52%   |
| Samsung Electronics SyncMaster SAM01D4 1440x900 408x225mm 18.3-inch   | 1        | 0.52%   |
| Samsung Electronics S27D590 SAM0B49 1920x1080 598x336mm 27.0-inch     | 1        | 0.52%   |
| Samsung Electronics S24E390 SAM0C1A 1920x1080 520x290mm 23.4-inch     | 1        | 0.52%   |
| Samsung Electronics S22F350 SAM0D1B 1920x1080 477x268mm 21.5-inch     | 1        | 0.52%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1        | 0.52%   |
| Samsung Electronics S22C650 SAM09DB 1920x1080 477x268mm 21.5-inch     | 1        | 0.52%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 79       | 45.93%  |
| 3840x2160 (4K)     | 32       | 18.6%   |
| 2560x1440 (QHD)    | 16       | 9.3%    |
| 1440x900 (WXGA+)   | 7        | 4.07%   |
| 1680x1050 (WSXGA+) | 6        | 3.49%   |
| 1366x768 (WXGA)    | 6        | 3.49%   |
| 1280x1024 (SXGA)   | 4        | 2.33%   |
| Unknown            | 4        | 2.33%   |
| 3840x1080          | 3        | 1.74%   |
| 1360x768           | 3        | 1.74%   |
| 3440x1440          | 2        | 1.16%   |
| 2560x1600          | 2        | 1.16%   |
| 2560x1080          | 2        | 1.16%   |
| 1920x1200 (WUXGA)  | 2        | 1.16%   |
| 1024x768 (XGA)     | 2        | 1.16%   |
| 5120x1440          | 1        | 0.58%   |
| 3200x1080          | 1        | 0.58%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 29       | 15.93%  |
| 23      | 26       | 14.29%  |
| 27      | 23       | 12.64%  |
| 21      | 22       | 12.09%  |
| Unknown | 19       | 10.44%  |
| 31      | 9        | 4.95%   |
| 18      | 9        | 4.95%   |
| 13      | 6        | 3.3%    |
| 40      | 5        | 2.75%   |
| 28      | 5        | 2.75%   |
| 22      | 4        | 2.2%    |
| 19      | 4        | 2.2%    |
| 84      | 3        | 1.65%   |
| 34      | 3        | 1.65%   |
| 15      | 3        | 1.65%   |
| 32      | 2        | 1.1%    |
| 65      | 1        | 0.55%   |
| 58      | 1        | 0.55%   |
| 57      | 1        | 0.55%   |
| 54      | 1        | 0.55%   |
| 50      | 1        | 0.55%   |
| 48      | 1        | 0.55%   |
| 26      | 1        | 0.55%   |
| 25      | 1        | 0.55%   |
| 17      | 1        | 0.55%   |
| 16      | 1        | 0.55%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 74       | 42.29%  |
| 401-500     | 36       | 20.57%  |
| Unknown     | 19       | 10.86%  |
| 601-700     | 15       | 8.57%   |
| 701-800     | 6        | 3.43%   |
| 201-300     | 6        | 3.43%   |
| 801-900     | 5        | 2.86%   |
| 301-350     | 5        | 2.86%   |
| 1001-1500   | 5        | 2.86%   |
| 1501-2000   | 3        | 1.71%   |
| 351-400     | 1        | 0.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 118      | 71.08%  |
| 16/10   | 21       | 12.65%  |
| Unknown | 18       | 10.84%  |
| 21/9    | 3        | 1.81%   |
| 6/5     | 2        | 1.2%    |
| 5/4     | 1        | 0.6%    |
| 4/3     | 1        | 0.6%    |
| 32/9    | 1        | 0.6%    |
| 0.56    | 1        | 0.6%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 65       | 36.31%  |
| 301-350        | 29       | 16.2%   |
| Unknown        | 19       | 10.61%  |
| 351-500        | 14       | 7.82%   |
| 151-200        | 13       | 7.26%   |
| 251-300        | 9        | 5.03%   |
| More than 1000 | 8        | 4.47%   |
| 71-80          | 6        | 3.35%   |
| 141-150        | 6        | 3.35%   |
| 501-1000       | 6        | 3.35%   |
| 101-110        | 3        | 1.68%   |
| 131-140        | 1        | 0.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 92       | 52.27%  |
| 101-120       | 36       | 20.45%  |
| Unknown       | 19       | 10.8%   |
| 161-240       | 17       | 9.66%   |
| 1-50          | 6        | 3.41%   |
| 121-160       | 5        | 2.84%   |
| More than 240 | 1        | 0.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 132      | 76.3%   |
| 2     | 28       | 16.18%  |
| 0     | 12       | 6.94%   |
| 3     | 1        | 0.58%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 100      | 40.32%  |
| Intel                                  | 95       | 38.31%  |
| TP-Link                                | 8        | 3.23%   |
| Broadcom                               | 8        | 3.23%   |
| MediaTek                               | 7        | 2.82%   |
| Qualcomm Atheros                       | 6        | 2.42%   |
| Ralink Technology                      | 5        | 2.02%   |
| Microsoft                              | 3        | 1.21%   |
| Xiaomi                                 | 1        | 0.4%    |
| Sony Ericsson Mobile Communications AB | 1        | 0.4%    |
| SEGGER                                 | 1        | 0.4%    |
| Samsung Electronics                    | 1        | 0.4%    |
| PEAK-System Technik                    | 1        | 0.4%    |
| Nvidia                                 | 1        | 0.4%    |
| National Semiconductor                 | 1        | 0.4%    |
| Kinesis                                | 1        | 0.4%    |
| Google                                 | 1        | 0.4%    |
| D-Link System                          | 1        | 0.4%    |
| D-Link                                 | 1        | 0.4%    |
| Belkin Components                      | 1        | 0.4%    |
| ASUSTek Computer                       | 1        | 0.4%    |
| ASIX Electronics                       | 1        | 0.4%    |
| Arduino SA                             | 1        | 0.4%    |
| Aquantia                               | 1        | 0.4%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 81       | 27.18%  |
| Intel Wi-Fi 6 AX200                                               | 15       | 5.03%   |
| Realtek RTL8125 2.5GbE Controller                                 | 12       | 4.03%   |
| Intel I211 Gigabit Network Connection                             | 12       | 4.03%   |
| Intel Ethernet Controller I225-V                                  | 10       | 3.36%   |
| Intel Ethernet Connection (2) I219-V                              | 8        | 2.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 8        | 2.68%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 8        | 2.68%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 6        | 2.01%   |
| Intel Ethernet Connection I217-LM                                 | 6        | 2.01%   |
| Intel 82574L Gigabit Network Connection                           | 4        | 1.34%   |
| Ralink MT7601U Wireless Adapter                                   | 3        | 1.01%   |
| Microsoft XBOX ACC                                                | 3        | 1.01%   |
| Intel Wireless 7265                                               | 3        | 1.01%   |
| Intel Wireless 7260                                               | 3        | 1.01%   |
| Intel Ethernet Connection (7) I219-LM                             | 3        | 1.01%   |
| Intel Ethernet Connection (17) I219-LM                            | 3        | 1.01%   |
| Intel Ethernet Connection (11) I219-V                             | 3        | 1.01%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3        | 1.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3        | 1.01%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 1.01%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2        | 0.67%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2        | 0.67%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 2        | 0.67%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2        | 0.67%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.67%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 2        | 0.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 0.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 0.67%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2        | 0.67%   |
| Realtek 802.11ac NIC                                              | 2        | 0.67%   |
| Ralink RT5370 Wireless Adapter                                    | 2        | 0.67%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 2        | 0.67%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 2        | 0.67%   |
| Intel Wireless-AC 9260                                            | 2        | 0.67%   |
| Intel Wireless 8265 / 8275                                        | 2        | 0.67%   |
| Intel Ethernet Connection I217-V                                  | 2        | 0.67%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 0.67%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 0.67%   |
| Intel Ethernet Connection (12) I219-V                             | 2        | 0.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 60       | 58.25%  |
| Realtek Semiconductor | 11       | 10.68%  |
| TP-Link               | 8        | 7.77%   |
| MediaTek              | 7        | 6.8%    |
| Ralink Technology     | 5        | 4.85%   |
| Broadcom              | 4        | 3.88%   |
| Microsoft             | 3        | 2.91%   |
| Qualcomm Atheros      | 2        | 1.94%   |
| D-Link System         | 1        | 0.97%   |
| Belkin Components     | 1        | 0.97%   |
| ASUSTek Computer      | 1        | 0.97%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                           | 15       | 14.56%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 8        | 7.77%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 8        | 7.77%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 6        | 5.83%   |
| Ralink MT7601U Wireless Adapter                               | 3        | 2.91%   |
| Microsoft XBOX ACC                                            | 3        | 2.91%   |
| Intel Wireless 7265                                           | 3        | 2.91%   |
| Intel Wireless 7260                                           | 3        | 2.91%   |
| Intel Comet Lake PCH CNVi WiFi                                | 3        | 2.91%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 3        | 2.91%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                  | 2        | 1.94%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]    | 2        | 1.94%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 2        | 1.94%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 2        | 1.94%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                       | 2        | 1.94%   |
| Realtek 802.11ac NIC                                          | 2        | 1.94%   |
| Ralink RT5370 Wireless Adapter                                | 2        | 1.94%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 2        | 1.94%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 2        | 1.94%   |
| Intel Wireless-AC 9260                                        | 2        | 1.94%   |
| Intel Wireless 8265 / 8275                                    | 2        | 1.94%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter  | 2        | 1.94%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 1        | 0.97%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                         | 1        | 0.97%   |
| TP-Link Archer T4U ver.3                                      | 1        | 0.97%   |
| TP-Link 802.11n NIC                                           | 1        | 0.97%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter      | 1        | 0.97%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)     | 1        | 0.97%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 1        | 0.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 1        | 0.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 1        | 0.97%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 1        | 0.97%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter            | 1        | 0.97%   |
| MediaTek 802.11 n WLAN                                        | 1        | 0.97%   |
| Intel Wireless-AC                                             | 1        | 0.97%   |
| Intel Wireless 3160                                           | 1        | 0.97%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection | 1        | 0.97%   |
| Intel Centrino Wireless-N 2230                                | 1        | 0.97%   |
| Intel Centrino Wireless-N 105                                 | 1        | 0.97%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                 | 1        | 0.97%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 100      | 54.05%  |
| Intel                                  | 68       | 36.76%  |
| Qualcomm Atheros                       | 4        | 2.16%   |
| Broadcom                               | 4        | 2.16%   |
| Xiaomi                                 | 1        | 0.54%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.54%   |
| Samsung Electronics                    | 1        | 0.54%   |
| Nvidia                                 | 1        | 0.54%   |
| National Semiconductor                 | 1        | 0.54%   |
| Google                                 | 1        | 0.54%   |
| D-Link                                 | 1        | 0.54%   |
| ASIX Electronics                       | 1        | 0.54%   |
| Aquantia                               | 1        | 0.54%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 81       | 42.41%  |
| Realtek RTL8125 2.5GbE Controller                                 | 12       | 6.28%   |
| Intel I211 Gigabit Network Connection                             | 12       | 6.28%   |
| Intel Ethernet Controller I225-V                                  | 10       | 5.24%   |
| Intel Ethernet Connection (2) I219-V                              | 8        | 4.19%   |
| Intel Ethernet Connection I217-LM                                 | 6        | 3.14%   |
| Intel 82574L Gigabit Network Connection                           | 4        | 2.09%   |
| Intel Ethernet Connection (7) I219-LM                             | 3        | 1.57%   |
| Intel Ethernet Connection (17) I219-LM                            | 3        | 1.57%   |
| Intel Ethernet Connection (11) I219-V                             | 3        | 1.57%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 1.57%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 2        | 1.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 1.05%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.05%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2        | 1.05%   |
| Intel Ethernet Connection I217-V                                  | 2        | 1.05%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 1.05%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 1.05%   |
| Intel Ethernet Connection (12) I219-V                             | 2        | 1.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 1.05%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.52%   |
| Sony Ericsson Mobile AB XQ-CC54                                   | 1        | 0.52%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.52%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1        | 0.52%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.52%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.52%   |
| Nvidia MCP65 Ethernet                                             | 1        | 0.52%   |
| National DP83815 (MacPhyter) Ethernet Controller                  | 1        | 0.52%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.52%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1        | 0.52%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.52%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.52%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1        | 0.52%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 0.52%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 0.52%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1        | 0.52%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 0.52%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 168      | 62.69%  |
| WiFi     | 96       | 35.82%  |
| Modem    | 3        | 1.12%   |
| Unknown  | 1        | 0.37%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 140      | 74.07%  |
| WiFi     | 49       | 25.93%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 87       | 49.43%  |
| 2     | 76       | 43.18%  |
| 3     | 5        | 2.84%   |
| 0     | 4        | 2.27%   |
| 4     | 2        | 1.14%   |
| 8     | 1        | 0.57%   |
| 7     | 1        | 0.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 164      | 94.8%   |
| Yes  | 9        | 5.2%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 55       | 62.5%   |
| Cambridge Silicon Radio         | 16       | 18.18%  |
| Broadcom                        | 4        | 4.55%   |
| Realtek Semiconductor           | 2        | 2.27%   |
| MediaTek                        | 2        | 2.27%   |
| ASUSTek Computer                | 2        | 2.27%   |
| TP-Link                         | 1        | 1.14%   |
| SINO WEALTH                     | 1        | 1.14%   |
| Qualcomm Atheros Communications | 1        | 1.14%   |
| Micro Star International        | 1        | 1.14%   |
| Lite-On Technology              | 1        | 1.14%   |
| Foxconn / Hon Hai               | 1        | 1.14%   |
| Apple                           | 1        | 1.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 16       | 18.18%  |
| Intel AX200 Bluetooth                               | 14       | 15.91%  |
| Intel Bluetooth wireless interface                  | 9        | 10.23%  |
| Intel Wireless-AC 3168 Bluetooth                    | 8        | 9.09%   |
| Intel AX201 Bluetooth                               | 8        | 9.09%   |
| Intel AX210 Bluetooth                               | 6        | 6.82%   |
| Intel Bluetooth Device                              | 4        | 4.55%   |
| Realtek Bluetooth Radio                             | 2        | 2.27%   |
| MediaTek Wireless_Device                            | 2        | 2.27%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 2.27%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2        | 2.27%   |
| ASUS Bluetooth Radio                                | 2        | 2.27%   |
| TP-Link TP-Cdj+ UB5A Adapter                        | 1        | 1.14%   |
| SINO WEALTH RK Bluetooth Keyboar                    | 1        | 1.14%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 1.14%   |
| Micro Star International Bluetooth Dongle           | 1        | 1.14%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1        | 1.14%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 1.14%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1        | 1.14%   |
| Foxconn / Hon Hai Wireless_Device                   | 1        | 1.14%   |
| Broadcom Bluetooth Controller                       | 1        | 1.14%   |
| Broadcom Bluetooth 2.0+eDR dongle                   | 1        | 1.14%   |
| Broadcom BCM920702 Bluetooth 4.0 Zero Touch Dongle  | 1        | 1.14%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1        | 1.14%   |
| Apple Bluetooth Host Controller                     | 1        | 1.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 122      | 43.42%  |
| Nvidia                                       | 71       | 25.27%  |
| AMD                                          | 57       | 20.28%  |
| C-Media Electronics                          | 10       | 3.56%   |
| ASUSTek Computer                             | 3        | 1.07%   |
| Focusrite-Novation                           | 2        | 0.71%   |
| FiiO Electronics Technology                  | 2        | 0.71%   |
| Creative Labs                                | 2        | 0.71%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.36%   |
| XMOS                                         | 1        | 0.36%   |
| Thesycon Systemsoftware & Consulting         | 1        | 0.36%   |
| Texas Instruments                            | 1        | 0.36%   |
| Sony                                         | 1        | 0.36%   |
| SAVITECH                                     | 1        | 0.36%   |
| Micro Star International                     | 1        | 0.36%   |
| Lynx                                         | 1        | 0.36%   |
| Logitech                                     | 1        | 0.36%   |
| JMTek                                        | 1        | 0.36%   |
| AudioQuest                                   | 1        | 0.36%   |
| Anlya.cn                                     | 1        | 0.36%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 17       | 5.14%   |
| AMD Starship/Matisse HD Audio Controller                                   | 17       | 5.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 14       | 4.23%   |
| Intel Alder Lake-S HD Audio Controller                                     | 14       | 4.23%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13       | 3.93%   |
| Intel 200 Series PCH HD Audio                                              | 10       | 3.02%   |
| AMD Family 17h/19h HD Audio Controller                                     | 10       | 3.02%   |
| Intel Cannon Lake PCH cAVS                                                 | 8        | 2.42%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8        | 2.42%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8        | 2.42%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 8        | 2.42%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 8        | 2.42%   |
| Nvidia GP106 High Definition Audio Controller                              | 7        | 2.11%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 7        | 2.11%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7        | 2.11%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6        | 1.81%   |
| Nvidia GF108 High Definition Audio Controller                              | 6        | 1.81%   |
| Nvidia GA104 High Definition Audio Controller                              | 6        | 1.81%   |
| Nvidia TU106 High Definition Audio Controller                              | 5        | 1.51%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 5        | 1.51%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5        | 1.51%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5        | 1.51%   |
| Nvidia TU104 HD Audio Controller                                           | 4        | 1.21%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4        | 1.21%   |
| Nvidia GM206 High Definition Audio Controller                              | 4        | 1.21%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4        | 1.21%   |
| Intel Comet Lake PCH-V cAVS                                                | 4        | 1.21%   |
| AMD Navi 10 HDMI Audio                                                     | 4        | 1.21%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4        | 1.21%   |
| Nvidia TU116 High Definition Audio Controller                              | 3        | 0.91%   |
| Nvidia GP108 High Definition Audio Controller                              | 3        | 0.91%   |
| Nvidia GP104 High Definition Audio Controller                              | 3        | 0.91%   |
| Nvidia GF106 High Definition Audio Controller                              | 3        | 0.91%   |
| Intel Sunrise Point-LP HD Audio                                            | 3        | 0.91%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3        | 0.91%   |
| Intel Comet Lake PCH cAVS                                                  | 3        | 0.91%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 0.91%   |
| Intel 8 Series HD Audio Controller                                         | 3        | 0.91%   |
| ASUSTek Computer USB Audio                                                 | 3        | 0.91%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 3        | 0.91%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 28       | 26.42%  |
| A-DATA Technology   | 13       | 12.26%  |
| Corsair             | 12       | 11.32%  |
| Samsung Electronics | 11       | 10.38%  |
| Unknown             | 7        | 6.6%    |
| SK hynix            | 5        | 4.72%   |
| G.Skill             | 5        | 4.72%   |
| Crucial             | 5        | 4.72%   |
| Team                | 3        | 2.83%   |
| Micron Technology   | 3        | 2.83%   |
| Ramaxel Technology  | 2        | 1.89%   |
| Unknown (0x0AFD)    | 1        | 0.94%   |
| Transcend           | 1        | 0.94%   |
| Nanya Technology    | 1        | 0.94%   |
| KingSpec            | 1        | 0.94%   |
| Kingmax             | 1        | 0.94%   |
| Kimtigo             | 1        | 0.94%   |
| Juhor               | 1        | 0.94%   |
| GLOWAY              | 1        | 0.94%   |
| Essencore Limited   | 1        | 0.94%   |
| CUSO                | 1        | 0.94%   |
| Apacer              | 1        | 0.94%   |
| Unknown             | 1        | 0.94%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s      | 2        | 1.75%   |
| Kingston RAM KY7N41-MIE 8GB DIMM DDR4 2666MT/s            | 2        | 1.75%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s       | 2        | 1.75%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s     | 2        | 1.75%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s     | 2        | 1.75%   |
| Corsair RAM CM4X16GC3600C18K2D 16GB DIMM DDR4 3600MT/s    | 2        | 1.75%   |
| A-DATA RAM Module 4GB DIMM DDR3 1333MT/s                  | 2        | 1.75%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s              | 1        | 0.88%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s               | 1        | 0.88%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                 | 1        | 0.88%   |
| Unknown RAM Module 4GB DIMM 800MT/s                       | 1        | 0.88%   |
| Unknown RAM Module 4096MB DIMM DDR2 800MT/s               | 1        | 0.88%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                      | 1        | 0.88%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                    | 1        | 0.88%   |
| Unknown (0x0AFD) RAM SED2666U1932 32GB DIMM DDR4 2667MT/s | 1        | 0.88%   |
| Transcend RAM TS256MLQ72V6U 2GB DIMM DDR2 667MT/s         | 1        | 0.88%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 3000MT/s        | 1        | 0.88%   |
| Team RAM TEAMGROUP-UD4-2400 16GB DIMM DDR4 3007MT/s       | 1        | 0.88%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s        | 1        | 0.88%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s                | 1        | 0.88%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                | 1        | 0.88%   |
| SK hynix RAM HMCG66MEBUA084N 8GB DIMM DDR5 4800MT/s       | 1        | 0.88%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s    | 1        | 0.88%   |
| Samsung RAM Module 3GB Row Of Chips 6400MT/s              | 1        | 0.88%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s     | 1        | 0.88%   |
| Samsung RAM M471B1G73DH0-YK0 8GB SODIMM DDR3 1600MT/s     | 1        | 0.88%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s  | 1        | 0.88%   |
| Samsung RAM M471A1G43EB1-CPB 8GB SODIMM DDR4 2133MT/s     | 1        | 0.88%   |
| Samsung RAM M391A1K43BB1-CRC 8GB DIMM DDR4 2400MT/s       | 1        | 0.88%   |
| Samsung RAM M378B5773DH0-CK0 2GB DIMM DDR3 1600MT/s       | 1        | 0.88%   |
| Samsung RAM M378B5773CH0-CK0 2GB DIMM DDR3 1600MT/s       | 1        | 0.88%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s       | 1        | 0.88%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s       | 1        | 0.88%   |
| Samsung RAM M378A2K43CB1-CTD 16384MB DIMM DDR4 3200MT/s   | 1        | 0.88%   |
| Samsung RAM M378A2G43CB3-CWE 16GB DIMM DDR4 3200MT/s      | 1        | 0.88%   |
| Samsung RAM M323R2GA3BB0-CQKOD 16GB DIMM DDR5 4800MT/s    | 1        | 0.88%   |
| Ramaxel RAM RMR5040MM58F9F1600 4096MB DIMM DDR3 1600MT/s  | 1        | 0.88%   |
| Ramaxel RAM RMR1870ED48E8F1333 2048MB DIMM DDR3 1333MT/s  | 1        | 0.88%   |
| Nanya RAM NT2GC64B88G0NF-DI 2GB DIMM DDR3 1600MT/s        | 1        | 0.88%   |
| Micron RAM TEAMGROUP-UD4-2400 16GB DIMM DDR4 2400MT/s     | 1        | 0.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 65       | 65.66%  |
| DDR3    | 19       | 19.19%  |
| DDR5    | 7        | 7.07%   |
| Unknown | 4        | 4.04%   |
| SDRAM   | 2        | 2.02%   |
| DDR2    | 2        | 2.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 83       | 83.84%  |
| SODIMM       | 15       | 15.15%  |
| Row Of Chips | 1        | 1.01%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 32       | 30.77%  |
| 8192  | 29       | 27.88%  |
| 4096  | 19       | 18.27%  |
| 32768 | 14       | 13.46%  |
| 2048  | 8        | 7.69%   |
| 3072  | 1        | 0.96%   |
| 1024  | 1        | 0.96%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 18       | 17.48%  |
| 2667  | 12       | 11.65%  |
| 1600  | 11       | 10.68%  |
| 2400  | 9        | 8.74%   |
| 1333  | 8        | 7.77%   |
| 3600  | 7        | 6.8%    |
| 2666  | 5        | 4.85%   |
| 2133  | 5        | 4.85%   |
| 3000  | 4        | 3.88%   |
| 4800  | 3        | 2.91%   |
| 800   | 3        | 2.91%   |
| 3533  | 2        | 1.94%   |
| 7000  | 1        | 0.97%   |
| 6400  | 1        | 0.97%   |
| 6000  | 1        | 0.97%   |
| 5808  | 1        | 0.97%   |
| 5600  | 1        | 0.97%   |
| 4199  | 1        | 0.97%   |
| 3933  | 1        | 0.97%   |
| 3866  | 1        | 0.97%   |
| 3800  | 1        | 0.97%   |
| 3733  | 1        | 0.97%   |
| 3466  | 1        | 0.97%   |
| 3400  | 1        | 0.97%   |
| 3007  | 1        | 0.97%   |
| 1866  | 1        | 0.97%   |
| 1800  | 1        | 0.97%   |
| 667   | 1        | 0.97%   |

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
| Logitech                      | 8        | 40%     |
| Microdia                      | 2        | 10%     |
| Z-Star Microelectronics       | 1        | 5%      |
| Sunplus Innovation Technology | 1        | 5%      |
| SN0002                        | 1        | 5%      |
| Nokia Mobile Phones           | 1        | 5%      |
| Google                        | 1        | 5%      |
| Essential Products            | 1        | 5%      |
| eMPIA Technology              | 1        | 5%      |
| Cubeternet                    | 1        | 5%      |
| ARC International             | 1        | 5%      |
| A4Tech                        | 1        | 5%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech Webcam C270                    | 4        | 19.05%  |
| Logitech B525 HD Webcam                 | 2        | 9.52%   |
| Z-Star Sirius USB2.0 Camera             | 1        | 4.76%   |
| Sunplus SPCA2650 PC Camera              | 1        | 4.76%   |
| SN0002 2K USB Camera                    | 1        | 4.76%   |
| Nokia Mobile Phones Lumia 640 Phone     | 1        | 4.76%   |
| Microdia USB 2.0 Camera                 | 1        | 4.76%   |
| Microdia HP Integrated Webcam           | 1        | 4.76%   |
| Logitech C920 PRO HD Webcam             | 1        | 4.76%   |
| Logitech BRIO Ultra HD Webcam           | 1        | 4.76%   |
| Google Nexus/Pixel Device (PTP + debug) | 1        | 4.76%   |
| Google Nexus/Pixel Device (MTP + debug) | 1        | 4.76%   |
| Essential Products PH-1                 | 1        | 4.76%   |
| eMPIA M035 Compact Web Cam              | 1        | 4.76%   |
| Cubeternet GL-UPC822 UVC WebCam         | 1        | 4.76%   |
| ARC International Camera                | 1        | 4.76%   |
| A4Tech FHD 1080P PC Camera              | 1        | 4.76%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

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
| 0     | 145      | 81.01%  |
| 1     | 28       | 15.64%  |
| 2     | 4        | 2.23%   |
| 4     | 2        | 1.12%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 13       | 30.23%  |
| Graphics card            | 13       | 30.23%  |
| Communication controller | 7        | 16.28%  |
| Unassigned class         | 3        | 6.98%   |
| Chipcard                 | 2        | 4.65%   |
| Storage/ata              | 1        | 2.33%   |
| Sound                    | 1        | 2.33%   |
| Net/ethernet             | 1        | 2.33%   |
| Camera                   | 1        | 2.33%   |
| Bluetooth                | 1        | 2.33%   |

