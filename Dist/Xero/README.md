Xero - Tested Hardware & Statistics
-----------------------------------

A project to collect tested hardware configurations for Xero.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Xero/Desktop/README.md) and [notebooks](/Dist/Xero/Notebook/README.md).

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

Total: 271

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | G3 3590                     | Notebook    | [084d659110](https://linux-hardware.org/?probe=084d659110) | Aug 11, 2023 |
| LNV           | L40-70                      | Notebook    | [66fe107447](https://linux-hardware.org/?probe=66fe107447) | Aug 11, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [93a61b62a5](https://linux-hardware.org/?probe=93a61b62a5) | Aug 11, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [eee160a070](https://linux-hardware.org/?probe=eee160a070) | Aug 10, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [284cfb0f6d](https://linux-hardware.org/?probe=284cfb0f6d) | Aug 08, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [c9c978701a](https://linux-hardware.org/?probe=c9c978701a) | Aug 08, 2023 |
| ASUSTek       | PRIME H510M-R               | Desktop     | [38ab435feb](https://linux-hardware.org/?probe=38ab435feb) | Aug 08, 2023 |
| MSI           | B350 GAMING PLUS            | Desktop     | [951597859a](https://linux-hardware.org/?probe=951597859a) | Aug 08, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [e642e8e489](https://linux-hardware.org/?probe=e642e8e489) | Aug 08, 2023 |
| Sony          | VAIO                        | All in one  | [e924df8ac8](https://linux-hardware.org/?probe=e924df8ac8) | Aug 07, 2023 |
| Sony          | VAIO                        | All in one  | [8349b185e4](https://linux-hardware.org/?probe=8349b185e4) | Aug 07, 2023 |
| ECS           | H61H2-CM                    | Desktop     | [e2b9ff65d7](https://linux-hardware.org/?probe=e2b9ff65d7) | Aug 06, 2023 |
| WEIGO         | CDA-141AU                   | Notebook    | [35c705bd70](https://linux-hardware.org/?probe=35c705bd70) | Aug 05, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [5331913f13](https://linux-hardware.org/?probe=5331913f13) | Aug 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [8b84e48f4c](https://linux-hardware.org/?probe=8b84e48f4c) | Aug 04, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [6dbeaa5f27](https://linux-hardware.org/?probe=6dbeaa5f27) | Aug 04, 2023 |
| Acer          | Aspire V3-371               | Notebook    | [5d5a4b489b](https://linux-hardware.org/?probe=5d5a4b489b) | Aug 03, 2023 |
| ASRock        | Z77 Professional            | Desktop     | [2f0bc369b4](https://linux-hardware.org/?probe=2f0bc369b4) | Aug 03, 2023 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [7281304bf0](https://linux-hardware.org/?probe=7281304bf0) | Aug 02, 2023 |
| Dell          | G3 3590                     | Notebook    | [78aeeb1aa3](https://linux-hardware.org/?probe=78aeeb1aa3) | Aug 02, 2023 |
| Dell          | G3 3590                     | Notebook    | [47d3c9b9fe](https://linux-hardware.org/?probe=47d3c9b9fe) | Aug 02, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [b0d7ab05f0](https://linux-hardware.org/?probe=b0d7ab05f0) | Aug 02, 2023 |
| AZW           | SER                         | Mini pc     | [de1abb2584](https://linux-hardware.org/?probe=de1abb2584) | Aug 02, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [39216c08ff](https://linux-hardware.org/?probe=39216c08ff) | Aug 01, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [70a56ad26d](https://linux-hardware.org/?probe=70a56ad26d) | Aug 01, 2023 |
| Gigabyte      | Z490 GAMING X               | Desktop     | [f710ad8b96](https://linux-hardware.org/?probe=f710ad8b96) | Jul 31, 2023 |
| Lenovo        | ThinkPad T480 20L6S2CE00    | Notebook    | [eb14620792](https://linux-hardware.org/?probe=eb14620792) | Jul 30, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [2c6149347b](https://linux-hardware.org/?probe=2c6149347b) | Jul 30, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [20d5d0a3ad](https://linux-hardware.org/?probe=20d5d0a3ad) | Jul 30, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [3fb2cba3db](https://linux-hardware.org/?probe=3fb2cba3db) | Jul 29, 2023 |
| HP            | 82DD 0001                   | All in one  | [e6da7743f0](https://linux-hardware.org/?probe=e6da7743f0) | Jul 28, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [37440e19b5](https://linux-hardware.org/?probe=37440e19b5) | Jul 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [a467ce5440](https://linux-hardware.org/?probe=a467ce5440) | Jul 28, 2023 |
| Acer          | Aspire A315-42              | Notebook    | [3afa5a3034](https://linux-hardware.org/?probe=3afa5a3034) | Jul 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [dc632de3b5](https://linux-hardware.org/?probe=dc632de3b5) | Jul 27, 2023 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [5de59d7736](https://linux-hardware.org/?probe=5de59d7736) | Jul 27, 2023 |
| Apple         | MacBook7,1                  | Notebook    | [762861205a](https://linux-hardware.org/?probe=762861205a) | Jul 26, 2023 |
| Intel         | B75                         | Desktop     | [492fa4fc25](https://linux-hardware.org/?probe=492fa4fc25) | Jul 26, 2023 |
| Lenovo        | ThinkCentre M58 3231W2Y     | Desktop     | [72f09cd320](https://linux-hardware.org/?probe=72f09cd320) | Jul 26, 2023 |
| Lenovo        | ThinkPad T470p 20J6003DG... | Notebook    | [5693ac5e4c](https://linux-hardware.org/?probe=5693ac5e4c) | Jul 25, 2023 |
| ASUSTek       | ROG Flow X13 GV301RC_GV3... | Convertible | [676bfc8484](https://linux-hardware.org/?probe=676bfc8484) | Jul 25, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [032db75736](https://linux-hardware.org/?probe=032db75736) | Jul 23, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [f5174240a7](https://linux-hardware.org/?probe=f5174240a7) | Jul 23, 2023 |
| Dell          | Inspiron 3476               | Notebook    | [eb12521a96](https://linux-hardware.org/?probe=eb12521a96) | Jul 23, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [c95c0b0730](https://linux-hardware.org/?probe=c95c0b0730) | Jul 22, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [96f5f9ffdc](https://linux-hardware.org/?probe=96f5f9ffdc) | Jul 19, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [c10ecff0f6](https://linux-hardware.org/?probe=c10ecff0f6) | Jul 19, 2023 |
| ASUSTek       | PRIME X299-A II             | Desktop     | [54f9bd2050](https://linux-hardware.org/?probe=54f9bd2050) | Jul 18, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [d688be2c92](https://linux-hardware.org/?probe=d688be2c92) | Jul 18, 2023 |
| Gigabyte      | Z490 GAMING X               | Desktop     | [866bc45d05](https://linux-hardware.org/?probe=866bc45d05) | Jul 18, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [4c8b8b5a8a](https://linux-hardware.org/?probe=4c8b8b5a8a) | Jul 18, 2023 |
| ASUSTek       | TUF Z270 MARK 2             | Desktop     | [d23b7166b1](https://linux-hardware.org/?probe=d23b7166b1) | Jul 18, 2023 |
| Lenovo        | ThinkPad T420 4236C92       | Notebook    | [a7b56f640a](https://linux-hardware.org/?probe=a7b56f640a) | Jul 18, 2023 |
| Gigabyte      | Z490 GAMING X               | Desktop     | [3c5ef629e4](https://linux-hardware.org/?probe=3c5ef629e4) | Jul 18, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [4d00148664](https://linux-hardware.org/?probe=4d00148664) | Jul 16, 2023 |
| Lenovo        | ThinkPad T480 20L6S2CE00    | Notebook    | [e88c64ac3c](https://linux-hardware.org/?probe=e88c64ac3c) | Jul 16, 2023 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [59bf614ae2](https://linux-hardware.org/?probe=59bf614ae2) | Jul 14, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [9ec51bc7eb](https://linux-hardware.org/?probe=9ec51bc7eb) | Jul 14, 2023 |
| Lenovo        | ThinkPad T450 20BUS1BW01    | Notebook    | [db28c39c19](https://linux-hardware.org/?probe=db28c39c19) | Jul 14, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [75d40e5a2b](https://linux-hardware.org/?probe=75d40e5a2b) | Jul 14, 2023 |
| Intel         | NUC7i5BNB J31144-305        | Mini pc     | [d477369e7e](https://linux-hardware.org/?probe=d477369e7e) | Jul 14, 2023 |
| Lenovo        | ThinkPad T460s 20F90057M... | Notebook    | [698c4a8958](https://linux-hardware.org/?probe=698c4a8958) | Jul 14, 2023 |
| ASUSTek       | GL553VW                     | Notebook    | [9946c63986](https://linux-hardware.org/?probe=9946c63986) | Jul 12, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [06f4243bee](https://linux-hardware.org/?probe=06f4243bee) | Jul 12, 2023 |
| Lenovo        | ThinkPad T450 20BUS1BW01    | Notebook    | [91d748c376](https://linux-hardware.org/?probe=91d748c376) | Jul 11, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [995e13dee9](https://linux-hardware.org/?probe=995e13dee9) | Jul 11, 2023 |
| Lenovo        | ThinkPad P72 20MCS0EU00     | Notebook    | [394bdbc596](https://linux-hardware.org/?probe=394bdbc596) | Jul 11, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [a5d9143c99](https://linux-hardware.org/?probe=a5d9143c99) | Jul 10, 2023 |
| Lenovo        | ThinkPad T480 20L6S2CE00    | Notebook    | [bbc78272ea](https://linux-hardware.org/?probe=bbc78272ea) | Jul 10, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [b5ddf3381c](https://linux-hardware.org/?probe=b5ddf3381c) | Jul 10, 2023 |
| Lenovo        | ThinkPad T470p 20J6003DG... | Notebook    | [a7632f8c4b](https://linux-hardware.org/?probe=a7632f8c4b) | Jul 09, 2023 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [8fcda3580f](https://linux-hardware.org/?probe=8fcda3580f) | Jul 08, 2023 |
| Alienware     | 17                          | Notebook    | [b8b8032da9](https://linux-hardware.org/?probe=b8b8032da9) | Jul 08, 2023 |
| Lenovo        | ThinkPad T460s 20F90057M... | Notebook    | [cd45163d47](https://linux-hardware.org/?probe=cd45163d47) | Jul 08, 2023 |
| Gigabyte      | Z490 GAMING X               | Desktop     | [27e600a93b](https://linux-hardware.org/?probe=27e600a93b) | Jul 07, 2023 |
| Dell          | Latitude 7480               | Notebook    | [4c07c7b04a](https://linux-hardware.org/?probe=4c07c7b04a) | Jul 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [b23ba37244](https://linux-hardware.org/?probe=b23ba37244) | Jul 06, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [d25474786c](https://linux-hardware.org/?probe=d25474786c) | Jul 05, 2023 |
| Acer          | TravelMate 8572T            | Notebook    | [67f4a2af7e](https://linux-hardware.org/?probe=67f4a2af7e) | Jul 05, 2023 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [c945bae843](https://linux-hardware.org/?probe=c945bae843) | Jul 05, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [ca637a5884](https://linux-hardware.org/?probe=ca637a5884) | Jul 05, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [407e00921f](https://linux-hardware.org/?probe=407e00921f) | Jul 04, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [fc70411ea4](https://linux-hardware.org/?probe=fc70411ea4) | Jul 03, 2023 |
| Gigabyte      | Z490 GAMING X               | Desktop     | [107fe61a53](https://linux-hardware.org/?probe=107fe61a53) | Jul 02, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [7fee63007e](https://linux-hardware.org/?probe=7fee63007e) | Jul 02, 2023 |
| Acer          | Aspire 7715Z                | Notebook    | [b288a09d6e](https://linux-hardware.org/?probe=b288a09d6e) | Jul 01, 2023 |
| Lenovo        | ThinkPad T460s 20F90057M... | Notebook    | [a78e2b4096](https://linux-hardware.org/?probe=a78e2b4096) | Jun 29, 2023 |
| Medion        | Akoya P7818                 | Notebook    | [cfe9ae82fa](https://linux-hardware.org/?probe=cfe9ae82fa) | Jun 29, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [c3118a3d89](https://linux-hardware.org/?probe=c3118a3d89) | Jun 29, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [895760e7db](https://linux-hardware.org/?probe=895760e7db) | Jun 27, 2023 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [fa162784e0](https://linux-hardware.org/?probe=fa162784e0) | Jun 24, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [b67f86bedc](https://linux-hardware.org/?probe=b67f86bedc) | Jun 21, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [5314aeb7e0](https://linux-hardware.org/?probe=5314aeb7e0) | Jun 21, 2023 |
| MSI           | Z77A-G41                    | Desktop     | [e7e4924bda](https://linux-hardware.org/?probe=e7e4924bda) | Jun 20, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [284344e775](https://linux-hardware.org/?probe=284344e775) | Jun 14, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [859f1b3a88](https://linux-hardware.org/?probe=859f1b3a88) | Jun 13, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [95bc101c80](https://linux-hardware.org/?probe=95bc101c80) | Jun 09, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [277ddf45b4](https://linux-hardware.org/?probe=277ddf45b4) | Jun 08, 2023 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [1d8b78cbdc](https://linux-hardware.org/?probe=1d8b78cbdc) | May 29, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [6dc6a9d6f5](https://linux-hardware.org/?probe=6dc6a9d6f5) | May 29, 2023 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [2cdf1c9e61](https://linux-hardware.org/?probe=2cdf1c9e61) | May 23, 2023 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [cca41e18cb](https://linux-hardware.org/?probe=cca41e18cb) | May 23, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [89d6a4edd2](https://linux-hardware.org/?probe=89d6a4edd2) | May 13, 2023 |
| Lenovo        | Yoga 730-15IKB 81CU         | Convertible | [5cfbeb30e0](https://linux-hardware.org/?probe=5cfbeb30e0) | May 10, 2023 |
| Unknown       | Intel X79                   | Desktop     | [6b1ddbd923](https://linux-hardware.org/?probe=6b1ddbd923) | May 03, 2023 |
| Biostar       | H110MHV3                    | Desktop     | [95b25ba480](https://linux-hardware.org/?probe=95b25ba480) | Apr 29, 2023 |
| Samsung       | 950QED                      | Convertible | [f2568c7949](https://linux-hardware.org/?probe=f2568c7949) | Apr 07, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [ba6e80b2b7](https://linux-hardware.org/?probe=ba6e80b2b7) | Apr 02, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [195ab3d907](https://linux-hardware.org/?probe=195ab3d907) | Apr 02, 2023 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [520ad2ca86](https://linux-hardware.org/?probe=520ad2ca86) | Mar 31, 2023 |
| Lenovo        | ThinkPad T440 20B7A0CYMH    | Notebook    | [428491a9d5](https://linux-hardware.org/?probe=428491a9d5) | Mar 29, 2023 |
| HP            | 8437                        | Desktop     | [cdc32d8d8b](https://linux-hardware.org/?probe=cdc32d8d8b) | Mar 25, 2023 |
| HP            | 8437                        | Desktop     | [6fbb459a03](https://linux-hardware.org/?probe=6fbb459a03) | Mar 25, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [f8cd7d94b2](https://linux-hardware.org/?probe=f8cd7d94b2) | Mar 23, 2023 |
| Dell          | G5 5500                     | Notebook    | [f9b3b5d852](https://linux-hardware.org/?probe=f9b3b5d852) | Mar 19, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [90ef6ca2b7](https://linux-hardware.org/?probe=90ef6ca2b7) | Mar 18, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [b769745990](https://linux-hardware.org/?probe=b769745990) | Mar 18, 2023 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [5d307f2d26](https://linux-hardware.org/?probe=5d307f2d26) | Mar 18, 2023 |
| Dell          | Latitude 5420               | Notebook    | [318da7f6c0](https://linux-hardware.org/?probe=318da7f6c0) | Mar 18, 2023 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [d1bf2f0a8b](https://linux-hardware.org/?probe=d1bf2f0a8b) | Mar 12, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [bccc889328](https://linux-hardware.org/?probe=bccc889328) | Mar 10, 2023 |
| Lenovo        | ThinkPad P51 20HJS11Y00     | Notebook    | [0843074b87](https://linux-hardware.org/?probe=0843074b87) | Mar 09, 2023 |
| Lenovo        | IdeaPad S540-15IML D 81N... | Notebook    | [31e144de96](https://linux-hardware.org/?probe=31e144de96) | Mar 08, 2023 |
| Acer          | Aspire GX-281               | Desktop     | [d318df6931](https://linux-hardware.org/?probe=d318df6931) | Mar 04, 2023 |
| JINGSHA       | Unknown                     | Desktop     | [c8bd846b63](https://linux-hardware.org/?probe=c8bd846b63) | Feb 26, 2023 |
| Dell          | 0G3HR7 A00                  | Desktop     | [33723c8b80](https://linux-hardware.org/?probe=33723c8b80) | Feb 25, 2023 |
| Dell          | Inspiron 3505               | Notebook    | [324020ca8b](https://linux-hardware.org/?probe=324020ca8b) | Feb 24, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [503fe663b4](https://linux-hardware.org/?probe=503fe663b4) | Feb 20, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [d76b048134](https://linux-hardware.org/?probe=d76b048134) | Feb 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [efd9f878d2](https://linux-hardware.org/?probe=efd9f878d2) | Feb 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [3c2d4cf289](https://linux-hardware.org/?probe=3c2d4cf289) | Feb 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [0de8121880](https://linux-hardware.org/?probe=0de8121880) | Feb 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [f39ab69b74](https://linux-hardware.org/?probe=f39ab69b74) | Feb 01, 2023 |
| HP            | ProBook 6565b               | Notebook    | [0ef00f6bcc](https://linux-hardware.org/?probe=0ef00f6bcc) | Jan 25, 2023 |
| HP            | 828A                        | Desktop     | [5f430ba8d1](https://linux-hardware.org/?probe=5f430ba8d1) | Jan 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [5661d09dd0](https://linux-hardware.org/?probe=5661d09dd0) | Jan 15, 2023 |
| HP            | 245 G7 Notebook PC          | Notebook    | [3997d98a9a](https://linux-hardware.org/?probe=3997d98a9a) | Jan 11, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [21fcd391f1](https://linux-hardware.org/?probe=21fcd391f1) | Jan 08, 2023 |
| HP            | 86EE                        | All in one  | [1fc671302e](https://linux-hardware.org/?probe=1fc671302e) | Jan 06, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | Notebook    | [86cf09380a](https://linux-hardware.org/?probe=86cf09380a) | Jan 02, 2023 |
| Pegatron      | 2AF0                        | Desktop     | [77768feff6](https://linux-hardware.org/?probe=77768feff6) | Jan 01, 2023 |
| ASUSTek       | X540LA                      | Notebook    | [65f5548781](https://linux-hardware.org/?probe=65f5548781) | Dec 30, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [fb1d454bc2](https://linux-hardware.org/?probe=fb1d454bc2) | Dec 29, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [62010fe267](https://linux-hardware.org/?probe=62010fe267) | Dec 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6b34107dcf](https://linux-hardware.org/?probe=6b34107dcf) | Dec 21, 2022 |
| HP            | ZBook 15 G4                 | Notebook    | [669d7e74a2](https://linux-hardware.org/?probe=669d7e74a2) | Dec 19, 2022 |
| HP            | ZBook 15 G4                 | Notebook    | [91391127d1](https://linux-hardware.org/?probe=91391127d1) | Dec 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3111a63a09](https://linux-hardware.org/?probe=3111a63a09) | Dec 16, 2022 |
| Lenovo        | ThinkPad T490s 20NX001KM... | Notebook    | [49f30d3eee](https://linux-hardware.org/?probe=49f30d3eee) | Dec 06, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [16f086de33](https://linux-hardware.org/?probe=16f086de33) | Nov 25, 2022 |
| Medion        | P6816                       | Notebook    | [3aadacefe7](https://linux-hardware.org/?probe=3aadacefe7) | Nov 17, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [f074ef2e7c](https://linux-hardware.org/?probe=f074ef2e7c) | Nov 15, 2022 |
| Dell          | Latitude E6530              | Notebook    | [c87c9abe22](https://linux-hardware.org/?probe=c87c9abe22) | Nov 14, 2022 |
| Toshiba       | TECRA A11                   | Notebook    | [ba91b9d331](https://linux-hardware.org/?probe=ba91b9d331) | Nov 09, 2022 |
| Lenovo        | ThinkPad L450 20DT0000GE    | Notebook    | [1a925e0302](https://linux-hardware.org/?probe=1a925e0302) | Nov 06, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [711e95b72e](https://linux-hardware.org/?probe=711e95b72e) | Nov 02, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [ff0c19c661](https://linux-hardware.org/?probe=ff0c19c661) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [4cd7aa6350](https://linux-hardware.org/?probe=4cd7aa6350) | Nov 01, 2022 |
| ASUSTek       | K53SJ                       | Notebook    | [8c85e545f2](https://linux-hardware.org/?probe=8c85e545f2) | Oct 23, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [bcf4fa1baf](https://linux-hardware.org/?probe=bcf4fa1baf) | Oct 18, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [07b256f333](https://linux-hardware.org/?probe=07b256f333) | Oct 17, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [fc1ec464bf](https://linux-hardware.org/?probe=fc1ec464bf) | Oct 17, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [bf0e112f9a](https://linux-hardware.org/?probe=bf0e112f9a) | Oct 16, 2022 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [00ab764924](https://linux-hardware.org/?probe=00ab764924) | Oct 15, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [e037086b30](https://linux-hardware.org/?probe=e037086b30) | Oct 14, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [ef1974cfc8](https://linux-hardware.org/?probe=ef1974cfc8) | Oct 10, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [69e60dfe44](https://linux-hardware.org/?probe=69e60dfe44) | Oct 07, 2022 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [a11de13c4f](https://linux-hardware.org/?probe=a11de13c4f) | Oct 04, 2022 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [6de76ddb0e](https://linux-hardware.org/?probe=6de76ddb0e) | Oct 04, 2022 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [a7764ad0f6](https://linux-hardware.org/?probe=a7764ad0f6) | Oct 03, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [9931b35717](https://linux-hardware.org/?probe=9931b35717) | Sep 24, 2022 |
| MSI           | Katana GF66 11UE            | Notebook    | [36b2cba297](https://linux-hardware.org/?probe=36b2cba297) | Sep 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [b28edd3886](https://linux-hardware.org/?probe=b28edd3886) | Aug 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [97770c5716](https://linux-hardware.org/?probe=97770c5716) | Aug 26, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [4c95b1bccf](https://linux-hardware.org/?probe=4c95b1bccf) | Aug 22, 2022 |
| Lenovo        | ThinkPad T430s 2356FG9      | Notebook    | [9a10c152af](https://linux-hardware.org/?probe=9a10c152af) | Aug 17, 2022 |
| Aquarius      | NS585                       | Notebook    | [db9cbd5688](https://linux-hardware.org/?probe=db9cbd5688) | Aug 17, 2022 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [2522ff1530](https://linux-hardware.org/?probe=2522ff1530) | Aug 13, 2022 |
| ASUSTek       | P7P55 LX                    | Desktop     | [8211ccc6cc](https://linux-hardware.org/?probe=8211ccc6cc) | Aug 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [b73e5f9cbf](https://linux-hardware.org/?probe=b73e5f9cbf) | Aug 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [f483092edf](https://linux-hardware.org/?probe=f483092edf) | Aug 07, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a0507fae02](https://linux-hardware.org/?probe=a0507fae02) | Jul 31, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [7c46c8f737](https://linux-hardware.org/?probe=7c46c8f737) | Jul 15, 2022 |
| ASUSTek       | G551JM                      | Notebook    | [599c7b9eae](https://linux-hardware.org/?probe=599c7b9eae) | Jul 14, 2022 |
| ASUSTek       | G551JM                      | Notebook    | [9f4536df1c](https://linux-hardware.org/?probe=9f4536df1c) | Jul 14, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [7049f819f0](https://linux-hardware.org/?probe=7049f819f0) | Jun 30, 2022 |
| HP            | 3396                        | Desktop     | [00782afa06](https://linux-hardware.org/?probe=00782afa06) | Jun 22, 2022 |
| ASUSTek       | UX303LN                     | Notebook    | [9ce42e1b01](https://linux-hardware.org/?probe=9ce42e1b01) | Jun 12, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [8109a04ffa](https://linux-hardware.org/?probe=8109a04ffa) | Jun 12, 2022 |
| BESSTAR Te... | ATB15                       | Server      | [d6e47a7c18](https://linux-hardware.org/?probe=d6e47a7c18) | Jun 12, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [8a7401e54a](https://linux-hardware.org/?probe=8a7401e54a) | Jun 11, 2022 |
| Acer          | Aspire XC-886 V:2.0         | Desktop     | [2fe8cdaf93](https://linux-hardware.org/?probe=2fe8cdaf93) | May 31, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [ce0e24a314](https://linux-hardware.org/?probe=ce0e24a314) | May 28, 2022 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [53475a6004](https://linux-hardware.org/?probe=53475a6004) | May 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [80d32848bf](https://linux-hardware.org/?probe=80d32848bf) | May 21, 2022 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [3ddad532a9](https://linux-hardware.org/?probe=3ddad532a9) | May 08, 2022 |
| Dell          | Inspiron 7786               | Convertible | [0ef12447d9](https://linux-hardware.org/?probe=0ef12447d9) | May 02, 2022 |
| Dell          | Precision M3800             | Notebook    | [7b63874768](https://linux-hardware.org/?probe=7b63874768) | Apr 25, 2022 |
| Dell          | Precision M3800             | Notebook    | [fbabacd835](https://linux-hardware.org/?probe=fbabacd835) | Apr 24, 2022 |
| Lenovo        | ThinkPad X230 2325HR9       | Notebook    | [a9d9d3fbb2](https://linux-hardware.org/?probe=a9d9d3fbb2) | Apr 21, 2022 |
| MSI           | Z170-A PRO                  | Desktop     | [db5ab86328](https://linux-hardware.org/?probe=db5ab86328) | Apr 11, 2022 |
| Acer          | Aspire A515-54G             | Notebook    | [52b660d8fb](https://linux-hardware.org/?probe=52b660d8fb) | Apr 11, 2022 |
| MSI           | Z170-A PRO                  | Desktop     | [3bd5bb8d08](https://linux-hardware.org/?probe=3bd5bb8d08) | Apr 10, 2022 |
| Dell          | Precision M3800             | Notebook    | [1ef57b39a7](https://linux-hardware.org/?probe=1ef57b39a7) | Apr 10, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [8d251b1b2a](https://linux-hardware.org/?probe=8d251b1b2a) | Apr 03, 2022 |
| Dell          | Precision M3800             | Notebook    | [9fc15d1ae6](https://linux-hardware.org/?probe=9fc15d1ae6) | Mar 31, 2022 |
| HP            | 843B                        | Desktop     | [a88ff7cf5c](https://linux-hardware.org/?probe=a88ff7cf5c) | Mar 27, 2022 |
| Pegatron      | 2AC2                        | Desktop     | [d3c82e973b](https://linux-hardware.org/?probe=d3c82e973b) | Mar 25, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [745cc1d638](https://linux-hardware.org/?probe=745cc1d638) | Mar 25, 2022 |
| MSI           | GF63 Thin 9SCX              | Notebook    | [4501fa1556](https://linux-hardware.org/?probe=4501fa1556) | Mar 25, 2022 |
| Dell          | Latitude 7480               | Notebook    | [bf00ec6a76](https://linux-hardware.org/?probe=bf00ec6a76) | Mar 23, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [8eb98db533](https://linux-hardware.org/?probe=8eb98db533) | Mar 22, 2022 |
| HUAWEI        | WRT-WX9                     | Notebook    | [70ec26bed6](https://linux-hardware.org/?probe=70ec26bed6) | Mar 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [13cdf54c81](https://linux-hardware.org/?probe=13cdf54c81) | Mar 21, 2022 |
| Dell          | Latitude 7480               | Notebook    | [faddba28a8](https://linux-hardware.org/?probe=faddba28a8) | Mar 19, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [b71110144d](https://linux-hardware.org/?probe=b71110144d) | Mar 19, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [bb9074ccdf](https://linux-hardware.org/?probe=bb9074ccdf) | Mar 18, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WR      | Notebook    | [918c951cd1](https://linux-hardware.org/?probe=918c951cd1) | Mar 12, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [639e7361ef](https://linux-hardware.org/?probe=639e7361ef) | Mar 12, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [e251c9f079](https://linux-hardware.org/?probe=e251c9f079) | Mar 11, 2022 |
| MSI           | Z170A PC MATE               | Desktop     | [181e014823](https://linux-hardware.org/?probe=181e014823) | Mar 08, 2022 |
| Gigabyte      | Z170X-UD3-CF                | Desktop     | [3ec7a7f643](https://linux-hardware.org/?probe=3ec7a7f643) | Mar 06, 2022 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [57b302b119](https://linux-hardware.org/?probe=57b302b119) | Mar 05, 2022 |
| Lenovo        | ThinkPad T460 20FMS1XX00    | Notebook    | [78e82c6674](https://linux-hardware.org/?probe=78e82c6674) | Feb 24, 2022 |
| Dell          | Latitude E6430              | Notebook    | [e1de4e80fe](https://linux-hardware.org/?probe=e1de4e80fe) | Feb 15, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [a3c5f00a2a](https://linux-hardware.org/?probe=a3c5f00a2a) | Feb 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [e53fb31614](https://linux-hardware.org/?probe=e53fb31614) | Feb 10, 2022 |
| Lenovo        | Legion Y740-15IRHg 81UH     | Notebook    | [b0cc5e0cbc](https://linux-hardware.org/?probe=b0cc5e0cbc) | Jan 29, 2022 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [83ca29c9c8](https://linux-hardware.org/?probe=83ca29c9c8) | Jan 28, 2022 |
| Acer          | Aspire A315-58G             | Notebook    | [cb4f253c1c](https://linux-hardware.org/?probe=cb4f253c1c) | Jan 28, 2022 |
| Dell          | Latitude E6520              | Notebook    | [ee96960cec](https://linux-hardware.org/?probe=ee96960cec) | Jan 25, 2022 |
| Lenovo        | Yoga 710-15IKB 80V5         | Convertible | [3d5fe9fc42](https://linux-hardware.org/?probe=3d5fe9fc42) | Jan 22, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [0df160c245](https://linux-hardware.org/?probe=0df160c245) | Jan 21, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [230373b3ff](https://linux-hardware.org/?probe=230373b3ff) | Jan 09, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [3df8a1c560](https://linux-hardware.org/?probe=3df8a1c560) | Jan 08, 2022 |
| HP            | 1906                        | Desktop     | [5f8fe7cb20](https://linux-hardware.org/?probe=5f8fe7cb20) | Jan 06, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [793bfa4f40](https://linux-hardware.org/?probe=793bfa4f40) | Jan 04, 2022 |
| HP            | 2179                        | Desktop     | [79bac7ce1b](https://linux-hardware.org/?probe=79bac7ce1b) | Jan 01, 2022 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | Desktop     | [512091cd1c](https://linux-hardware.org/?probe=512091cd1c) | Dec 30, 2021 |
| Dell          | Vostro 3590                 | Notebook    | [9e77a2584c](https://linux-hardware.org/?probe=9e77a2584c) | Dec 30, 2021 |
| HP            | 2179                        | Desktop     | [9b6358ce37](https://linux-hardware.org/?probe=9b6358ce37) | Dec 30, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | Notebook    | [78e3fbdf6a](https://linux-hardware.org/?probe=78e3fbdf6a) | Dec 28, 2021 |
| HP            | Notebook                    | Notebook    | [c14ea64659](https://linux-hardware.org/?probe=c14ea64659) | Dec 23, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [5c2c86f287](https://linux-hardware.org/?probe=5c2c86f287) | Dec 23, 2021 |
| ASUSTek       | X510UNR                     | Notebook    | [0733a05806](https://linux-hardware.org/?probe=0733a05806) | Dec 21, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | Notebook    | [b4425de4a6](https://linux-hardware.org/?probe=b4425de4a6) | Dec 17, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [6f3bd18b3f](https://linux-hardware.org/?probe=6f3bd18b3f) | Dec 06, 2021 |
| Pegatron      | D15K                        | Notebook    | [eaeaad8d39](https://linux-hardware.org/?probe=eaeaad8d39) | Nov 29, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [728b23aa46](https://linux-hardware.org/?probe=728b23aa46) | Nov 26, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [9e9b6fd944](https://linux-hardware.org/?probe=9e9b6fd944) | Nov 21, 2021 |
| MSI           | GP73 Leopard 8RD            | Notebook    | [5bafb43f78](https://linux-hardware.org/?probe=5bafb43f78) | Nov 21, 2021 |
| Acer          | Aspire A315-58G             | Notebook    | [911895fcf2](https://linux-hardware.org/?probe=911895fcf2) | Nov 19, 2021 |
| Acer          | Aspire A315-58G             | Notebook    | [5748b3cd05](https://linux-hardware.org/?probe=5748b3cd05) | Nov 12, 2021 |
| Lenovo        | ThinkPad W530 24384CU       | Notebook    | [d18d3495e0](https://linux-hardware.org/?probe=d18d3495e0) | Nov 05, 2021 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [4877535f8b](https://linux-hardware.org/?probe=4877535f8b) | Nov 03, 2021 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [8dd5924480](https://linux-hardware.org/?probe=8dd5924480) | Oct 31, 2021 |
| Acer          | Aspire A315-58G             | Notebook    | [905fce5118](https://linux-hardware.org/?probe=905fce5118) | Oct 29, 2021 |
| HP            | ENVY Sleekbook 4            | Notebook    | [ebea056239](https://linux-hardware.org/?probe=ebea056239) | Oct 29, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [2a54689fb3](https://linux-hardware.org/?probe=2a54689fb3) | Oct 24, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [fb95cbb063](https://linux-hardware.org/?probe=fb95cbb063) | Oct 19, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [6cd76dfa2a](https://linux-hardware.org/?probe=6cd76dfa2a) | Oct 13, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e3a8d1ca32](https://linux-hardware.org/?probe=e3a8d1ca32) | Oct 11, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [c7c4a74bb8](https://linux-hardware.org/?probe=c7c4a74bb8) | Oct 11, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [68865693c7](https://linux-hardware.org/?probe=68865693c7) | Oct 09, 2021 |
| Dell          | 0XC7MM A01                  | Desktop     | [390c5408b2](https://linux-hardware.org/?probe=390c5408b2) | Oct 05, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [e804a59920](https://linux-hardware.org/?probe=e804a59920) | Oct 02, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [a198e8517a](https://linux-hardware.org/?probe=a198e8517a) | Oct 01, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [50fd919991](https://linux-hardware.org/?probe=50fd919991) | Aug 29, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [a3c6fe4037](https://linux-hardware.org/?probe=a3c6fe4037) | Jul 24, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [57d19e2c3a](https://linux-hardware.org/?probe=57d19e2c3a) | May 19, 2021 |
| Acer          | FIH57                       | Desktop     | [9c3e383ea5](https://linux-hardware.org/?probe=9c3e383ea5) | Apr 30, 2021 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Xero Rolling | 191       | 93.63%  |
| Xero         | 13        | 6.37%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| Xero | 203       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version          | Computers | Percent |
|------------------|-----------|---------|
| 6.4.3-arch1-2    | 26        | 11.93%  |
| 6.4.2-arch1-1    | 6         | 2.75%   |
| 5.16.15-arch1-1  | 6         | 2.75%   |
| 6.4.1-arch2-1    | 5         | 2.29%   |
| 6.1.12-arch1-1   | 5         | 2.29%   |
| 6.4.4-arch1-1    | 4         | 1.83%   |
| 6.3.9-arch1-1    | 4         | 1.83%   |
| 6.2.6-arch1-1    | 4         | 1.83%   |
| 6.0.12-arch1-1   | 4         | 1.83%   |
| 5.18.16-arch1-1  | 4         | 1.83%   |
| 6.4.3-arch1-1    | 3         | 1.38%   |
| 6.1.1-arch1-1    | 3         | 1.38%   |
| 5.17.9-arch1-1   | 3         | 1.38%   |
| 5.16.2-arch1-1   | 3         | 1.38%   |
| 5.16.1-arch1-1   | 3         | 1.38%   |
| 5.15.33-1-lts    | 3         | 1.38%   |
| 5.14.14-arch1-1  | 3         | 1.38%   |
| 6.4.9-arch1-1    | 2         | 0.92%   |
| 6.4.8-arch1-1    | 2         | 0.92%   |
| 6.4.7-zen1-1-zen | 2         | 0.92%   |
| 6.4.7-arch1-2    | 2         | 0.92%   |
| 6.4.7-arch1-1    | 2         | 0.92%   |
| 6.4.2-zen1-1-zen | 2         | 0.92%   |
| 6.4.1-arch1-1    | 2         | 0.92%   |
| 6.3.8-arch1-1    | 2         | 0.92%   |
| 6.3.6-arch1-1    | 2         | 0.92%   |
| 6.2.8-arch1-1    | 2         | 0.92%   |
| 6.2.7-arch1-1    | 2         | 0.92%   |
| 6.2.12-arch1-1   | 2         | 0.92%   |
| 6.0.7-arch1-1    | 2         | 0.92%   |
| 5.19.9-arch1-1   | 2         | 0.92%   |
| 5.19.13-arch1-1  | 2         | 0.92%   |
| 5.19.12-arch1-1  | 2         | 0.92%   |
| 5.18.3-arch1-1   | 2         | 0.92%   |
| 5.18.11-arch1-1  | 2         | 0.92%   |
| 5.17.5-arch1-1   | 2         | 0.92%   |
| 5.17.1-arch1-1   | 2         | 0.92%   |
| 5.16.8-arch1-1   | 2         | 0.92%   |
| 5.16.16-arch1-1  | 2         | 0.92%   |
| 5.16.13-arch1-1  | 2         | 0.92%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.4.3   | 30        | 13.76%  |
| 6.4.7   | 8         | 3.67%   |
| 6.4.2   | 8         | 3.67%   |
| 6.4.1   | 7         | 3.21%   |
| 6.3.9   | 6         | 2.75%   |
| 5.16.15 | 6         | 2.75%   |
| 6.4.4   | 5         | 2.29%   |
| 6.1.12  | 5         | 2.29%   |
| 6.2.6   | 4         | 1.83%   |
| 6.0.12  | 4         | 1.83%   |
| 5.18.16 | 4         | 1.83%   |
| 5.14.14 | 4         | 1.83%   |
| 6.3.8   | 3         | 1.38%   |
| 6.1.1   | 3         | 1.38%   |
| 5.19.13 | 3         | 1.38%   |
| 5.17.9  | 3         | 1.38%   |
| 5.16.2  | 3         | 1.38%   |
| 5.16.16 | 3         | 1.38%   |
| 5.16.1  | 3         | 1.38%   |
| 5.15.33 | 3         | 1.38%   |
| 5.15.12 | 3         | 1.38%   |
| 5.14.8  | 3         | 1.38%   |
| 5.14.16 | 3         | 1.38%   |
| 6.4.9   | 2         | 0.92%   |
| 6.4.8   | 2         | 0.92%   |
| 6.3.6   | 2         | 0.92%   |
| 6.2.8   | 2         | 0.92%   |
| 6.2.7   | 2         | 0.92%   |
| 6.2.12  | 2         | 0.92%   |
| 6.1.6   | 2         | 0.92%   |
| 6.1.38  | 2         | 0.92%   |
| 6.0.8   | 2         | 0.92%   |
| 6.0.7   | 2         | 0.92%   |
| 6.0.6   | 2         | 0.92%   |
| 6.0.2   | 2         | 0.92%   |
| 5.19.9  | 2         | 0.92%   |
| 5.19.12 | 2         | 0.92%   |
| 5.18.3  | 2         | 0.92%   |
| 5.18.11 | 2         | 0.92%   |
| 5.17.5  | 2         | 0.92%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.4     | 63        | 29.44%  |
| 5.16    | 23        | 10.75%  |
| 5.15    | 18        | 8.41%   |
| 6.1     | 16        | 7.48%   |
| 6.3     | 15        | 7.01%   |
| 6.0     | 15        | 7.01%   |
| 6.2     | 14        | 6.54%   |
| 5.14    | 13        | 6.07%   |
| 5.19    | 11        | 5.14%   |
| 5.18    | 11        | 5.14%   |
| 5.17    | 8         | 3.74%   |
| 5.10    | 3         | 1.4%    |
| 5.13    | 2         | 0.93%   |
| 5.12    | 1         | 0.47%   |
| 5.11    | 1         | 0.47%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 203       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| KDE5     | 192       | 93.66%  |
| XFCE     | 6         | 2.93%   |
| GNOME    | 4         | 1.95%   |
| LeftWM   | 1         | 0.49%   |
| KDE      | 1         | 0.49%   |
| Hyprland | 1         | 0.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 183       | 89.71%  |
| Wayland | 18        | 8.82%   |
| Tty     | 2         | 0.98%   |
| Unknown | 1         | 0.49%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 157       | 75.85%  |
| Unknown | 30        | 14.49%  |
| LightDM | 17        | 8.21%   |
| GDM     | 2         | 0.97%   |
| TDM     | 1         | 0.48%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 95        | 46.57%  |
| de_DE | 17        | 8.33%   |
| en_IN | 14        | 6.86%   |
| en_GB | 8         | 3.92%   |
| C     | 7         | 3.43%   |
| pl_PL | 6         | 2.94%   |
| es_MX | 6         | 2.94%   |
| tr_TR | 5         | 2.45%   |
| ru_RU | 5         | 2.45%   |
| en_AU | 5         | 2.45%   |
| it_IT | 4         | 1.96%   |
| en_CA | 4         | 1.96%   |
| fr_FR | 3         | 1.47%   |
| vi_VN | 2         | 0.98%   |
| hu_HU | 2         | 0.98%   |
| es_ES | 2         | 0.98%   |
| es_AR | 2         | 0.98%   |
| en_ZA | 2         | 0.98%   |
| en_DK | 2         | 0.98%   |
| zh_CN | 1         | 0.49%   |
| sv_SE | 1         | 0.49%   |
| pt_BR | 1         | 0.49%   |
| nb_NO | 1         | 0.49%   |
| es_SV | 1         | 0.49%   |
| es_CL | 1         | 0.49%   |
| en_PH | 1         | 0.49%   |
| en_IL | 1         | 0.49%   |
| en_AG | 1         | 0.49%   |
| de_CH | 1         | 0.49%   |
| de_AT | 1         | 0.49%   |
| ca_ES | 1         | 0.49%   |
| ba_RU | 1         | 0.49%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 141       | 68.78%  |
| BIOS | 64        | 31.22%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 83        | 40.49%  |
| Xfs     | 82        | 40%     |
| Ext4    | 32        | 15.61%  |
| Overlay | 8         | 3.9%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 151       | 73.66%  |
| Unknown | 30        | 14.63%  |
| MBR     | 24        | 11.71%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 155       | 74.52%  |
| Yes       | 53        | 25.48%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 128       | 62.75%  |
| Yes       | 76        | 37.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 48        | 23.65%  |
| Lenovo              | 38        | 18.72%  |
| Hewlett-Packard     | 24        | 11.82%  |
| Dell                | 23        | 11.33%  |
| MSI                 | 12        | 5.91%   |
| Acer                | 11        | 5.42%   |
| Gigabyte Technology | 7         | 3.45%   |
| ASRock              | 6         | 2.96%   |
| Apple               | 6         | 2.96%   |
| Pegatron            | 3         | 1.48%   |
| Microsoft           | 3         | 1.48%   |
| Medion              | 2         | 0.99%   |
| Intel               | 2         | 0.99%   |
| HUAWEI              | 2         | 0.99%   |
| Unknown             | 2         | 0.99%   |
| WEIGO               | 1         | 0.49%   |
| Toshiba             | 1         | 0.49%   |
| Timi                | 1         | 0.49%   |
| Sony                | 1         | 0.49%   |
| Samsung Electronics | 1         | 0.49%   |
| LNV                 | 1         | 0.49%   |
| JINGSHA             | 1         | 0.49%   |
| Fujitsu             | 1         | 0.49%   |
| ECS                 | 1         | 0.49%   |
| Biostar             | 1         | 0.49%   |
| BESSTAR Tech        | 1         | 0.49%   |
| AZW                 | 1         | 0.49%   |
| Aquarius            | 1         | 0.49%   |
| Alienware           | 1         | 0.49%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Dell Precision M3800                       | 3         | 1.48%   |
| Unknown                                    | 3         | 1.48%   |
| MSI MS-7971                                | 2         | 0.99%   |
| Dell Latitude 7480                         | 2         | 0.99%   |
| ASUS TUF Gaming X570-PLUS                  | 2         | 0.99%   |
| WEIGO CDA-141AU                            | 1         | 0.49%   |
| Toshiba TECRA A11                          | 1         | 0.49%   |
| Timi Redmi Book Pro 15 2022                | 1         | 0.49%   |
| Sony VGC-LV180ME                           | 1         | 0.49%   |
| Samsung 950QED                             | 1         | 0.49%   |
| Pegatron p6-2026                           | 1         | 0.49%   |
| Pegatron D15K                              | 1         | 0.49%   |
| Pegatron 20-b010                           | 1         | 0.49%   |
| MSI MS-7D22                                | 1         | 0.49%   |
| MSI MS-7C94                                | 1         | 0.49%   |
| MSI MS-7C91                                | 1         | 0.49%   |
| MSI MS-7C52                                | 1         | 0.49%   |
| MSI MS-7B61                                | 1         | 0.49%   |
| MSI MS-7A34                                | 1         | 0.49%   |
| MSI MS-7758                                | 1         | 0.49%   |
| MSI Katana GF66 11UE                       | 1         | 0.49%   |
| MSI GP73 Leopard 8RD                       | 1         | 0.49%   |
| MSI GF63 Thin 9SCX                         | 1         | 0.49%   |
| Microsoft Surface Pro 7                    | 1         | 0.49%   |
| Microsoft Surface Pro 6                    | 1         | 0.49%   |
| Microsoft Surface Pro 3                    | 1         | 0.49%   |
| Medion P6816                               | 1         | 0.49%   |
| Medion Akoya P7818                         | 1         | 0.49%   |
| LNV L40-70                                 | 1         | 0.49%   |
| Lenovo Yoga 730-15IKB 81CU                 | 1         | 0.49%   |
| Lenovo Yoga 710-15IKB 80V5                 | 1         | 0.49%   |
| Lenovo Yoga 3 Pro-1370 80HE                | 1         | 0.49%   |
| Lenovo Y520-15IKBN 80WK                    | 1         | 0.49%   |
| Lenovo ThinkPad Yoga 370 20JJS0SB00        | 1         | 0.49%   |
| Lenovo ThinkPad X230 2325HR9               | 1         | 0.49%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW0055MH | 1         | 0.49%   |
| Lenovo ThinkPad W530 24384CU               | 1         | 0.49%   |
| Lenovo ThinkPad T490s 20NX001KMX           | 1         | 0.49%   |
| Lenovo ThinkPad T480 20L6S2CE00            | 1         | 0.49%   |
| Lenovo ThinkPad T470p 20J6003DGE           | 1         | 0.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 16        | 7.88%   |
| Lenovo IdeaPad     | 12        | 5.91%   |
| ASUS ROG           | 10        | 4.93%   |
| Acer Aspire        | 10        | 4.93%   |
| ASUS TUF           | 8         | 3.94%   |
| HP Laptop          | 7         | 3.45%   |
| ASUS VivoBook      | 7         | 3.45%   |
| Dell Latitude      | 6         | 2.96%   |
| ASUS PRIME         | 6         | 2.96%   |
| Lenovo Legion      | 5         | 2.46%   |
| Dell Inspiron      | 5         | 2.46%   |
| Dell Precision     | 4         | 1.97%   |
| ASUS ASUS          | 4         | 1.97%   |
| Microsoft Surface  | 3         | 1.48%   |
| Lenovo Yoga        | 3         | 1.48%   |
| HP Pavilion        | 3         | 1.48%   |
| Unknown            | 3         | 1.48%   |
| MSI MS-7971        | 2         | 0.99%   |
| HP ENVY            | 2         | 0.99%   |
| Dell OptiPlex      | 2         | 0.99%   |
| Apple MacBookPro11 | 2         | 0.99%   |
| WEIGO CDA-141AU    | 1         | 0.49%   |
| Toshiba TECRA      | 1         | 0.49%   |
| Timi Redmi         | 1         | 0.49%   |
| Sony VGC-LV180ME   | 1         | 0.49%   |
| Samsung 950QED     | 1         | 0.49%   |
| Pegatron p6-2026   | 1         | 0.49%   |
| Pegatron D15K      | 1         | 0.49%   |
| Pegatron 20-b010   | 1         | 0.49%   |
| MSI MS-7D22        | 1         | 0.49%   |
| MSI MS-7C94        | 1         | 0.49%   |
| MSI MS-7C91        | 1         | 0.49%   |
| MSI MS-7C52        | 1         | 0.49%   |
| MSI MS-7B61        | 1         | 0.49%   |
| MSI MS-7A34        | 1         | 0.49%   |
| MSI MS-7758        | 1         | 0.49%   |
| MSI Katana         | 1         | 0.49%   |
| MSI GP73           | 1         | 0.49%   |
| MSI GF63           | 1         | 0.49%   |
| Medion P6816       | 1         | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 35        | 17.24%  |
| 2020 | 27        | 13.3%   |
| 2021 | 21        | 10.34%  |
| 2018 | 21        | 10.34%  |
| 2017 | 19        | 9.36%   |
| 2012 | 12        | 5.91%   |
| 2014 | 11        | 5.42%   |
| 2015 | 10        | 4.93%   |
| 2013 | 10        | 4.93%   |
| 2022 | 8         | 3.94%   |
| 2011 | 8         | 3.94%   |
| 2016 | 7         | 3.45%   |
| 2010 | 6         | 2.96%   |
| 2009 | 5         | 2.46%   |
| 2008 | 2         | 0.99%   |
| 2023 | 1         | 0.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 117       | 57.64%  |
| Desktop     | 70        | 34.48%  |
| Convertible | 8         | 3.94%   |
| Tablet      | 3         | 1.48%   |
| Mini pc     | 2         | 0.99%   |
| All in one  | 2         | 0.99%   |
| Server      | 1         | 0.49%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 203       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 203       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 58        | 28.57%  |
| 16.01-24.0  | 50        | 24.63%  |
| 8.01-16.0   | 39        | 19.21%  |
| 32.01-64.0  | 27        | 13.3%   |
| 3.01-4.0    | 21        | 10.34%  |
| 24.01-32.0  | 5         | 2.46%   |
| 64.01-256.0 | 3         | 1.48%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 65        | 30.37%  |
| 2.01-3.0   | 56        | 26.17%  |
| 4.01-8.0   | 41        | 19.16%  |
| 3.01-4.0   | 32        | 14.95%  |
| 8.01-16.0  | 9         | 4.21%   |
| 16.01-24.0 | 6         | 2.8%    |
| 0.51-1.0   | 3         | 1.4%    |
| 0.01-0.5   | 2         | 0.93%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 106       | 51.46%  |
| 2      | 58        | 28.16%  |
| 3      | 23        | 11.17%  |
| 4      | 9         | 4.37%   |
| 5      | 5         | 2.43%   |
| 7      | 2         | 0.97%   |
| 6      | 2         | 0.97%   |
| 8      | 1         | 0.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 159       | 77.94%  |
| Yes       | 45        | 22.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 164       | 80.79%  |
| No        | 39        | 19.21%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 167       | 81.86%  |
| No        | 37        | 18.14%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 153       | 75%     |
| No        | 51        | 25%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country               | Computers | Percent |
|-----------------------|-----------|---------|
| USA                   | 43        | 21.08%  |
| Germany               | 21        | 10.29%  |
| India                 | 16        | 7.84%   |
| Turkey                | 7         | 3.43%   |
| Russia                | 7         | 3.43%   |
| Poland                | 7         | 3.43%   |
| Italy                 | 7         | 3.43%   |
| Canada                | 7         | 3.43%   |
| France                | 6         | 2.94%   |
| Australia             | 5         | 2.45%   |
| UK                    | 4         | 1.96%   |
| Mexico                | 4         | 1.96%   |
| Argentina             | 4         | 1.96%   |
| Spain                 | 3         | 1.47%   |
| Norway                | 3         | 1.47%   |
| Hungary               | 3         | 1.47%   |
| Greece                | 3         | 1.47%   |
| Chile                 | 3         | 1.47%   |
| Vietnam               | 2         | 0.98%   |
| Switzerland           | 2         | 0.98%   |
| Sweden                | 2         | 0.98%   |
| South Africa          | 2         | 0.98%   |
| Romania               | 2         | 0.98%   |
| Portugal              | 2         | 0.98%   |
| Philippines           | 2         | 0.98%   |
| Pakistan              | 2         | 0.98%   |
| Netherlands           | 2         | 0.98%   |
| Lebanon               | 2         | 0.98%   |
| Indonesia             | 2         | 0.98%   |
| Egypt                 | 2         | 0.98%   |
| Denmark               | 2         | 0.98%   |
| Colombia              | 2         | 0.98%   |
| Brazil                | 2         | 0.98%   |
| Zambia                | 1         | 0.49%   |
| Venezuela             | 1         | 0.49%   |
| Togo                  | 1         | 0.49%   |
| Thailand              | 1         | 0.49%   |
| Palestinian Territory | 1         | 0.49%   |
| Nepal                 | 1         | 0.49%   |
| Morocco               | 1         | 0.49%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Istanbul       | 5         | 2.44%   |
| Longmont       | 4         | 1.95%   |
| Hamburg        | 3         | 1.46%   |
| Berlin         | 3         | 1.46%   |
| Warsaw         | 2         | 0.98%   |
| Tangerang      | 2         | 0.98%   |
| Stuttgart      | 2         | 0.98%   |
| St Petersburg  | 2         | 0.98%   |
| Red Lake       | 2         | 0.98%   |
| Pune           | 2         | 0.98%   |
| Phoenix        | 2         | 0.98%   |
| Madurai        | 2         | 0.98%   |
| Chicago        | 2         | 0.98%   |
| Chennai        | 2         | 0.98%   |
| Cairo          | 2         | 0.98%   |
| Cagayan de Oro | 2         | 0.98%   |
| Buenos Aires   | 2         | 0.98%   |
| Brisbane       | 2         | 0.98%   |
| Bremen         | 2         | 0.98%   |
| Beirut         | 2         | 0.98%   |
| Zurich         | 1         | 0.49%   |
| Zenica         | 1         | 0.49%   |
| Zell am See    | 1         | 0.49%   |
| Zalaegerszeg   | 1         | 0.49%   |
| York           | 1         | 0.49%   |
| Wroclaw        | 1         | 0.49%   |
| Wrexham        | 1         | 0.49%   |
| Wolfsburg      | 1         | 0.49%   |
| Wells          | 1         | 0.49%   |
| Wangen         | 1         | 0.49%   |
| Vredenburg     | 1         | 0.49%   |
| Viburnum       | 1         | 0.49%   |
| Vejle          | 1         | 0.49%   |
| Vechelde       | 1         | 0.49%   |
| Valladolid     | 1         | 0.49%   |
| Ulan Bator     | 1         | 0.49%   |
| Ufa            | 1         | 0.49%   |
| Toronto        | 1         | 0.49%   |
| Tirana         | 1         | 0.49%   |
| Tigre          | 1         | 0.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 54        | 73     | 15.79%  |
| Seagate                      | 46        | 62     | 13.45%  |
| WDC                          | 39        | 53     | 11.4%   |
| Toshiba                      | 22        | 25     | 6.43%   |
| SanDisk                      | 19        | 25     | 5.56%   |
| Kingston                     | 18        | 22     | 5.26%   |
| Intel                        | 14        | 19     | 4.09%   |
| Crucial                      | 12        | 16     | 3.51%   |
| Unknown                      | 11        | 12     | 3.22%   |
| SK hynix                     | 9         | 9      | 2.63%   |
| Micron Technology            | 7         | 9      | 2.05%   |
| HGST                         | 7         | 7      | 2.05%   |
| KIOXIA                       | 6         | 7      | 1.75%   |
| Micron/Crucial Technology    | 5         | 5      | 1.46%   |
| Transcend                    | 4         | 4      | 1.17%   |
| Hitachi                      | 4         | 4      | 1.17%   |
| China                        | 4         | 4      | 1.17%   |
| A-DATA Technology            | 4         | 4      | 1.17%   |
| Realtek Semiconductor        | 3         | 3      | 0.88%   |
| Phison                       | 3         | 3      | 0.88%   |
| Intenso                      | 3         | 4      | 0.88%   |
| Apple                        | 3         | 3      | 0.88%   |
| Apacer                       | 3         | 3      | 0.88%   |
| Shenzhen Longsys Electronics | 2         | 2      | 0.58%   |
| PNY                          | 2         | 2      | 0.58%   |
| OWC                          | 2         | 2      | 0.58%   |
| LITEONIT                     | 2         | 2      | 0.58%   |
| LITEON                       | 2         | 2      | 0.58%   |
| Kingston Technology Company  | 2         | 2      | 0.58%   |
| ADATA Technology             | 2         | 2      | 0.58%   |
| XPG                          | 1         | 1      | 0.29%   |
| Vaseky                       | 1         | 1      | 0.29%   |
| Team                         | 1         | 1      | 0.29%   |
| SPCC                         | 1         | 1      | 0.29%   |
| Silicon Motion               | 1         | 1      | 0.29%   |
| SandWind                     | 1         | 1      | 0.29%   |
| SAGE                         | 1         | 1      | 0.29%   |
| S3+                          | 1         | 1      | 0.29%   |
| Plextor                      | 1         | 1      | 0.29%   |
| Phison Electronics           | 1         | 1      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 7         | 1.86%   |
| Toshiba MQ04ABF100 1TB                              | 6         | 1.6%    |
| Unknown SD/MMC/MS PRO 128GB                         | 5         | 1.33%   |
| Crucial CT500MX500SSD1 500GB                        | 5         | 1.33%   |
| Seagate ST1000LM035-1RK172 1TB                      | 4         | 1.06%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 4         | 1.06%   |
| Kingston SA400S37240G 240GB SSD                     | 4         | 1.06%   |
| Unknown MMC Card  64GB                              | 3         | 0.8%    |
| Seagate ST1000LM049-2GH172 1TB                      | 3         | 0.8%    |
| Seagate ST1000DM003-1SB102 1TB                      | 3         | 0.8%    |
| Seagate One Touch HDD 1TB                           | 3         | 0.8%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB   | 3         | 0.8%    |
| Samsung SSD 860 EVO 1TB                             | 3         | 0.8%    |
| Kingston SA400S37960G 960GB SSD                     | 3         | 0.8%    |
| WDC WD10SPZX-60Z10T0 1TB                            | 2         | 0.53%   |
| WDC WD10SPZX-24Z10 1TB                              | 2         | 0.53%   |
| WDC WD10EZEX-60WN4A0 1TB                            | 2         | 0.53%   |
| Toshiba XG6 NVMe SSD Controller 512GB               | 2         | 0.53%   |
| Toshiba DT01ACA300 3TB                              | 2         | 0.53%   |
| Seagate ST750LM022 HN-M750MBB 752GB                 | 2         | 0.53%   |
| Seagate ST250DM000-1BD141 250GB                     | 2         | 0.53%   |
| Seagate ST2000DM006-2DM164 2TB                      | 2         | 0.53%   |
| Seagate ST1000LM048-2E7172 1TB                      | 2         | 0.53%   |
| Seagate ST1000DM010-2EP102 1TB                      | 2         | 0.53%   |
| Sandisk WD Blue SN550 NVMe SSD 250GB                | 2         | 0.53%   |
| SanDisk NVMe SSD Drive 500GB                        | 2         | 0.53%   |
| Samsung SSD 980 1TB                                 | 2         | 0.53%   |
| Samsung SSD 970 EVO 1TB                             | 2         | 0.53%   |
| Samsung SSD 860 EVO 250GB                           | 2         | 0.53%   |
| Samsung SSD 850 EVO 250GB                           | 2         | 0.53%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 2         | 0.53%   |
| Realtek RTS5763DL NVMe SSD Controller 1TB           | 2         | 0.53%   |
| OWC Mercury Electra 3G SSD                          | 2         | 0.53%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 2         | 0.53%   |
| Micron 2210_MTFDHBA512QFD 512GB                     | 2         | 0.53%   |
| Kingston SA400S37480G 480GB SSD                     | 2         | 0.53%   |
| Intenso External USB 3.0 1TB                        | 2         | 0.53%   |
| Intel SSD Pro 7600p/760p/E 6100p Series 1TB         | 2         | 0.53%   |
| Intel SSD 660P Series 1024GB                        | 2         | 0.53%   |
| HGST HTS545050A7E680 500GB                          | 2         | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 46        | 61     | 40.35%  |
| WDC                 | 29        | 38     | 25.44%  |
| Toshiba             | 16        | 18     | 14.04%  |
| HGST                | 7         | 7      | 6.14%   |
| Unknown             | 5         | 5      | 4.39%   |
| Samsung Electronics | 4         | 4      | 3.51%   |
| Hitachi             | 4         | 4      | 3.51%   |
| Intenso             | 2         | 3      | 1.75%   |
| ASMedia             | 1         | 1      | 0.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 22        | 28     | 20.18%  |
| Kingston            | 13        | 16     | 11.93%  |
| Crucial             | 12        | 16     | 11.01%  |
| WDC                 | 6         | 6      | 5.5%    |
| SanDisk             | 6         | 6      | 5.5%    |
| Transcend           | 4         | 4      | 3.67%   |
| China               | 4         | 4      | 3.67%   |
| Apple               | 3         | 3      | 2.75%   |
| Apacer              | 3         | 3      | 2.75%   |
| SK hynix            | 2         | 2      | 1.83%   |
| PNY                 | 2         | 2      | 1.83%   |
| OWC                 | 2         | 2      | 1.83%   |
| Micron Technology   | 2         | 2      | 1.83%   |
| LITEONIT            | 2         | 2      | 1.83%   |
| LITEON              | 2         | 2      | 1.83%   |
| Intel               | 2         | 2      | 1.83%   |
| A-DATA Technology   | 2         | 2      | 1.83%   |
| Vaseky              | 1         | 1      | 0.92%   |
| Team                | 1         | 1      | 0.92%   |
| SPCC                | 1         | 1      | 0.92%   |
| SAGE                | 1         | 1      | 0.92%   |
| S3+                 | 1         | 1      | 0.92%   |
| Plextor             | 1         | 1      | 0.92%   |
| Patriot             | 1         | 1      | 0.92%   |
| OSCOO               | 1         | 1      | 0.92%   |
| Mushkin             | 1         | 1      | 0.92%   |
| Leven               | 1         | 1      | 0.92%   |
| KingFast            | 1         | 1      | 0.92%   |
| Intenso             | 1         | 1      | 0.92%   |
| Hikvision           | 1         | 1      | 0.92%   |
| Hewlett-Packard     | 1         | 1      | 0.92%   |
| GOODRAM             | 1         | 1      | 0.92%   |
| Gigabyte Technology | 1         | 1      | 0.92%   |
| Emtec               | 1         | 1      | 0.92%   |
| Corsair             | 1         | 1      | 0.92%   |
| Biostar             | 1         | 1      | 0.92%   |
| 2-Power             | 1         | 1      | 0.92%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 106       | 145    | 35.45%  |
| SSD     | 92        | 122    | 30.77%  |
| HDD     | 92        | 141    | 30.77%  |
| MMC     | 7         | 8      | 2.34%   |
| Unknown | 2         | 2      | 0.67%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 140       | 239    | 51.28%  |
| NVMe | 106       | 144    | 38.83%  |
| SAS  | 20        | 27     | 7.33%   |
| MMC  | 7         | 8      | 2.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 91        | 127    | 46.43%  |
| 0.51-1.0   | 77        | 97     | 39.29%  |
| 1.01-2.0   | 15        | 18     | 7.65%   |
| 4.01-10.0  | 6         | 11     | 3.06%   |
| 3.01-4.0   | 4         | 7      | 2.04%   |
| 2.01-3.0   | 3         | 3      | 1.53%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 39        | 18.75%  |
| 251-500        | 37        | 17.79%  |
| 101-250        | 36        | 17.31%  |
| 1001-2000      | 29        | 13.94%  |
| 501-1000       | 24        | 11.54%  |
| 51-100         | 12        | 5.77%   |
| Unknown        | 10        | 4.81%   |
| 2001-3000      | 8         | 3.85%   |
| 21-50          | 7         | 3.37%   |
| 1-20           | 6         | 2.88%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 61        | 29.19%  |
| 21-50          | 33        | 15.79%  |
| 101-250        | 33        | 15.79%  |
| 51-100         | 26        | 12.44%  |
| 251-500        | 14        | 6.7%    |
| 501-1000       | 12        | 5.74%   |
| Unknown        | 10        | 4.78%   |
| 2001-3000      | 7         | 3.35%   |
| 1001-2000      | 7         | 3.35%   |
| More than 3000 | 6         | 2.87%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                                           | Computers | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-60U6AA0 500GB                                    | 1         | 1      | 2.17%   |
| WDC WD3200AAJS-08L7A0 320GB                                     | 1         | 1      | 2.17%   |
| WDC WD10SPZX-60Z10T0 1TB                                        | 1         | 1      | 2.17%   |
| WDC WD10SPZX-24Z10 1TB                                          | 1         | 1      | 2.17%   |
| WDC WD10EZEX-08WN4A0 1TB                                        | 1         | 1      | 2.17%   |
| WDC WD10EADS-00M2B0 1TB                                         | 1         | 1      | 2.17%   |
| WDC WD1002FAEX-00Z3A0 1TB                                       | 1         | 2      | 2.17%   |
| Toshiba MQ04ABF100 1TB                                          | 1         | 1      | 2.17%   |
| Toshiba MQ01ABF050M 500GB                                       | 1         | 1      | 2.17%   |
| Toshiba MQ01ABF050 500GB                                        | 1         | 1      | 2.17%   |
| Toshiba MQ01ABD100 1TB                                          | 1         | 1      | 2.17%   |
| Toshiba MK4058GSX 400GB                                         | 1         | 1      | 2.17%   |
| Toshiba MK3261GSY 320GB                                         | 1         | 1      | 2.17%   |
| Toshiba MK2555GSX 250GB                                         | 1         | 1      | 2.17%   |
| SK hynix HFS128G3BTND-N210A 128GB SSD                           | 1         | 1      | 2.17%   |
| SK hynix HFS128G3AMNB-2200A 128GB SSD                           | 1         | 1      | 2.17%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                            | 1         | 1      | 2.17%   |
| Seagate ST9500420AS 500GB                                       | 1         | 1      | 2.17%   |
| Seagate ST9500325AS 500GB                                       | 1         | 1      | 2.17%   |
| Seagate ST500LT012-1DG142 500GB                                 | 1         | 1      | 2.17%   |
| Seagate ST500LM000-SSHD-8GB                                     | 1         | 1      | 2.17%   |
| Seagate ST500DM009-2F110A 500GB                                 | 1         | 1      | 2.17%   |
| Seagate ST3500820AS 500GB                                       | 1         | 1      | 2.17%   |
| Seagate ST31000524AS 1TB                                        | 1         | 1      | 2.17%   |
| Seagate ST2000VX000-1CU164 2TB                                  | 1         | 1      | 2.17%   |
| Seagate ST2000DM006-2DM164 2TB                                  | 1         | 1      | 2.17%   |
| Seagate ST2000DL003-9VT166 2TB                                  | 1         | 1      | 2.17%   |
| Seagate ST1000LM049-2GH172 1TB                                  | 1         | 1      | 2.17%   |
| Seagate ST1000LM048-2E7172 1TB                                  | 1         | 1      | 2.17%   |
| Seagate ST1000LM035-1RK172 1TB                                  | 1         | 1      | 2.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                              | 1         | 1      | 2.17%   |
| Seagate ST1000DM003-1SB102 1TB                                  | 1         | 1      | 2.17%   |
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 256GB | 1         | 1      | 2.17%   |
| Samsung Electronics HM100UI 1TB                                 | 1         | 1      | 2.17%   |
| LITEONIT DMT-80M6M-11 mSATA 80GB SSD                            | 1         | 1      | 2.17%   |
| Kingston SV300S37A120G 120GB SSD                                | 1         | 1      | 2.17%   |
| Kingston SUV400S37240G 240GB SSD                                | 1         | 1      | 2.17%   |
| Hitachi HTS725050A9A364 500GB                                   | 1         | 1      | 2.17%   |
| Hitachi HTS547575A9E384 752GB                                   | 1         | 1      | 2.17%   |
| Hitachi HCP725050GLA380 500GB                                   | 1         | 1      | 2.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 15     | 33.33%  |
| WDC                 | 7         | 8      | 15.56%  |
| Toshiba             | 6         | 7      | 13.33%  |
| SK hynix            | 3         | 3      | 6.67%   |
| Hitachi             | 3         | 3      | 6.67%   |
| Samsung Electronics | 2         | 2      | 4.44%   |
| Kingston            | 2         | 2      | 4.44%   |
| HGST                | 2         | 2      | 4.44%   |
| LITEONIT            | 1         | 1      | 2.22%   |
| Crucial             | 1         | 1      | 2.22%   |
| China               | 1         | 1      | 2.22%   |
| ASMedia             | 1         | 1      | 2.22%   |
| ADATA Technology    | 1         | 1      | 2.22%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 15     | 42.86%  |
| WDC                 | 7         | 8      | 20%     |
| Toshiba             | 6         | 7      | 17.14%  |
| Hitachi             | 3         | 3      | 8.57%   |
| HGST                | 2         | 2      | 5.71%   |
| Samsung Electronics | 1         | 1      | 2.86%   |
| ASMedia             | 1         | 1      | 2.86%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 34        | 37     | 77.27%  |
| SSD  | 7         | 7      | 15.91%  |
| NVMe | 3         | 3      | 6.82%   |

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
| Works    | 155       | 276    | 63.52%  |
| Detected | 47        | 95     | 19.26%  |
| Malfunc  | 42        | 47     | 17.21%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 139       | 47.77%  |
| AMD                          | 38        | 13.06%  |
| Samsung Electronics          | 31        | 10.65%  |
| SanDisk                      | 21        | 7.22%   |
| SK hynix                     | 7         | 2.41%   |
| Kingston Technology Company  | 7         | 2.41%   |
| Toshiba America Info Systems | 6         | 2.06%   |
| Micron Technology            | 6         | 2.06%   |
| KIOXIA                       | 6         | 2.06%   |
| Micron/Crucial Technology    | 5         | 1.72%   |
| Realtek Semiconductor        | 4         | 1.37%   |
| Phison Electronics           | 4         | 1.37%   |
| ADATA Technology             | 4         | 1.37%   |
| ASMedia Technology           | 3         | 1.03%   |
| Shenzhen Longsys Electronics | 2         | 0.69%   |
| Nvidia                       | 2         | 0.69%   |
| Marvell Technology Group     | 2         | 0.69%   |
| VIA Technologies             | 1         | 0.34%   |
| Silicon Motion               | 1         | 0.34%   |
| Seagate Technology           | 1         | 0.34%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.34%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 32        | 10.09%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 12        | 3.79%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 11        | 3.47%   |
| Intel Volume Management Device NVMe RAID Controller                            | 10        | 3.15%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 9         | 2.84%   |
| Samsung NVMe SSD Controller 980                                                | 8         | 2.52%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 8         | 2.52%   |
| Intel SATA Controller [RAID mode]                                              | 8         | 2.52%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 8         | 2.52%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 7         | 2.21%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 2.21%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 1.89%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 1.89%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 6         | 1.89%   |
| AMD 400 Series Chipset SATA Controller                                         | 6         | 1.89%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 5         | 1.58%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 1.58%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 5         | 1.58%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 1.58%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5         | 1.58%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 4         | 1.26%   |
| Intel Tiger Lake-LP SATA Controller                                            | 4         | 1.26%   |
| Intel SSD 660P Series                                                          | 4         | 1.26%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 4         | 1.26%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 1.26%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 1.26%   |
| AMD 500 Series Chipset SATA Controller                                         | 4         | 1.26%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 3         | 0.95%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 3         | 0.95%   |
| Phison E12 NVMe Controller                                                     | 3         | 0.95%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 3         | 0.95%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]             | 3         | 0.95%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3         | 0.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 3         | 0.95%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3         | 0.95%   |
| AMD 300 Series Chipset SATA Controller                                         | 3         | 0.95%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 0.63%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 0.63%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 0.63%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 2         | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 150       | 52.08%  |
| NVMe | 106       | 36.81%  |
| RAID | 28        | 9.72%   |
| IDE  | 4         | 1.39%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 153       | 75.37%  |
| AMD    | 50        | 24.63%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 2.45%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 2.45%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 4         | 1.96%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 4         | 1.96%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 4         | 1.96%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 3         | 1.47%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 1.47%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 1.47%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.47%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 3         | 1.47%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 1.47%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 1.47%   |
| AMD Ryzen 5 3600X 6-Core Processor            | 3         | 1.47%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.98%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 2         | 0.98%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 0.98%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 2         | 0.98%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 2         | 0.98%   |
| Intel Core i7-4712HQ CPU @ 2.30GHz            | 2         | 0.98%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.98%   |
| Intel Core i7 CPU 870 @ 2.93GHz               | 2         | 0.98%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.98%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.98%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 2         | 0.98%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2         | 0.98%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 0.98%   |
| Intel Core i3-8100 CPU @ 3.60GHz              | 2         | 0.98%   |
| Intel Core i3-6100 CPU @ 3.70GHz              | 2         | 0.98%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz       | 2         | 0.98%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 2         | 0.98%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 2         | 0.98%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 2         | 0.98%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 0.98%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 2         | 0.98%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 2         | 0.98%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 2         | 0.98%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 0.98%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2         | 0.98%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 0.98%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 2         | 0.98%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 53        | 25.98%  |
| Intel Core i7           | 50        | 24.51%  |
| AMD Ryzen 5             | 24        | 11.76%  |
| Other                   | 17        | 8.33%   |
| Intel Core i3           | 15        | 7.35%   |
| AMD Ryzen 7             | 15        | 7.35%   |
| Intel Core 2 Duo        | 5         | 2.45%   |
| Intel Xeon              | 4         | 1.96%   |
| Intel Celeron           | 4         | 1.96%   |
| AMD Ryzen 3             | 4         | 1.96%   |
| AMD A8                  | 2         | 0.98%   |
| Intel Pentium Dual-Core | 1         | 0.49%   |
| Intel Pentium           | 1         | 0.49%   |
| Intel Genuine           | 1         | 0.49%   |
| Intel Core i9           | 1         | 0.49%   |
| Intel Core 2 Quad       | 1         | 0.49%   |
| AMD Ryzen Threadripper  | 1         | 0.49%   |
| AMD Ryzen 9             | 1         | 0.49%   |
| AMD E1                  | 1         | 0.49%   |
| AMD Athlon              | 1         | 0.49%   |
| AMD A6                  | 1         | 0.49%   |
| AMD A4                  | 1         | 0.49%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 78        | 38.24%  |
| 2      | 65        | 31.86%  |
| 6      | 34        | 16.67%  |
| 8      | 20        | 9.8%    |
| 16     | 2         | 0.98%   |
| 12     | 2         | 0.98%   |
| 10     | 2         | 0.98%   |
| 14     | 1         | 0.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 202       | 99.51%  |
| 2      | 1         | 0.49%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 171       | 83.82%  |
| 1      | 33        | 16.18%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 203       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 94        | 45.41%  |
| 0x906ea    | 8         | 3.86%   |
| 0x806c1    | 7         | 3.38%   |
| 0x806ec    | 6         | 2.9%    |
| 0x306a9    | 6         | 2.9%    |
| 0x806e9    | 5         | 2.42%   |
| 0x506e3    | 5         | 2.42%   |
| 0x08701021 | 5         | 2.42%   |
| 0x906e9    | 4         | 1.93%   |
| 0x0a201016 | 4         | 1.93%   |
| 0x08108109 | 4         | 1.93%   |
| 0x806eb    | 3         | 1.45%   |
| 0x306c3    | 3         | 1.45%   |
| 0x206a7    | 3         | 1.45%   |
| 0x0a404102 | 3         | 1.45%   |
| 0x906ed    | 2         | 0.97%   |
| 0x906eb    | 2         | 0.97%   |
| 0x706a8    | 2         | 0.97%   |
| 0x40651    | 2         | 0.97%   |
| 0x106e5    | 2         | 0.97%   |
| 0x1067a    | 2         | 0.97%   |
| 0x0a50000c | 2         | 0.97%   |
| 0x0a20120a | 2         | 0.97%   |
| 0x08701030 | 2         | 0.97%   |
| 0x08108102 | 2         | 0.97%   |
| 0x0810100b | 2         | 0.97%   |
| 0xa0653    | 1         | 0.48%   |
| 0xa0652    | 1         | 0.48%   |
| 0x906a3    | 1         | 0.48%   |
| 0x806d1    | 1         | 0.48%   |
| 0x706e5    | 1         | 0.48%   |
| 0x406e3    | 1         | 0.48%   |
| 0x40661    | 1         | 0.48%   |
| 0x306f2    | 1         | 0.48%   |
| 0x306d4    | 1         | 0.48%   |
| 0x20655    | 1         | 0.48%   |
| 0x20652    | 1         | 0.48%   |
| 0x0a50000d | 1         | 0.48%   |
| 0x0a50000b | 1         | 0.48%   |
| 0x0a404101 | 1         | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 50        | 24.51%  |
| Haswell          | 18        | 8.82%   |
| Zen 3            | 14        | 6.86%   |
| IvyBridge        | 13        | 6.37%   |
| Zen 2            | 12        | 5.88%   |
| TigerLake        | 11        | 5.39%   |
| Skylake          | 11        | 5.39%   |
| Zen+             | 10        | 4.9%    |
| Icelake          | 9         | 4.41%   |
| Broadwell        | 9         | 4.41%   |
| SandyBridge      | 8         | 3.92%   |
| Penryn           | 7         | 3.43%   |
| Unknown          | 7         | 3.43%   |
| CometLake        | 5         | 2.45%   |
| Zen              | 4         | 1.96%   |
| Goldmont plus    | 4         | 1.96%   |
| Westmere         | 3         | 1.47%   |
| Nehalem          | 3         | 1.47%   |
| Excavator        | 2         | 0.98%   |
| Piledriver       | 1         | 0.49%   |
| K10 Llano        | 1         | 0.49%   |
| Bobcat           | 1         | 0.49%   |
| Alderlake Hybrid | 1         | 0.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 119       | 45.25%  |
| Nvidia            | 91        | 34.6%   |
| AMD               | 52        | 19.77%  |
| ASPEED Technology | 1         | 0.38%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                      | 8         | 3.02%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 7         | 2.64%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 7         | 2.64%   |
| Intel HD Graphics 620                                                       | 7         | 2.64%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 7         | 2.64%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 7         | 2.64%   |
| Intel HD Graphics 5500                                                      | 6         | 2.26%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 6         | 2.26%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 6         | 2.26%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6         | 2.26%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 6         | 2.26%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 5         | 1.89%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 5         | 1.89%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 5         | 1.89%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 4         | 1.51%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4         | 1.51%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 4         | 1.51%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                   | 4         | 1.51%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 4         | 1.51%   |
| Intel HD Graphics 630                                                       | 4         | 1.51%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 4         | 1.51%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 4         | 1.51%   |
| AMD Rembrandt [Radeon 680M]                                                 | 4         | 1.51%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 3         | 1.13%   |
| Nvidia GP108M [GeForce MX250]                                               | 3         | 1.13%   |
| Nvidia GP108M [GeForce MX150]                                               | 3         | 1.13%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 3         | 1.13%   |
| Nvidia GM108M [GeForce 940MX]                                               | 3         | 1.13%   |
| Nvidia GK107GLM [Quadro K1100M]                                             | 3         | 1.13%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3         | 1.13%   |
| Intel Core Processor Integrated Graphics Controller                         | 3         | 1.13%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3         | 1.13%   |
| AMD Renoir                                                                  | 3         | 1.13%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 2         | 0.75%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2         | 0.75%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2         | 0.75%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2         | 0.75%   |
| Nvidia GF108GLM [NVS 5200M]                                                 | 2         | 0.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 0.75%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 2         | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 66        | 32.35%  |
| Intel + Nvidia  | 45        | 22.06%  |
| 1 x AMD         | 39        | 19.12%  |
| 1 x Nvidia      | 36        | 17.65%  |
| AMD + Nvidia    | 8         | 3.92%   |
| Intel + AMD     | 4         | 1.96%   |
| 2 x Intel       | 3         | 1.47%   |
| 2 x Nvidia      | 1         | 0.49%   |
| 2 x AMD         | 1         | 0.49%   |
| Nvidia + ASPEED | 1         | 0.49%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 150       | 72.82%  |
| Proprietary | 54        | 26.21%  |
| Unknown     | 2         | 0.97%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 115       | 56.1%   |
| 1.01-2.0   | 27        | 13.17%  |
| 7.01-8.0   | 15        | 7.32%   |
| 0.01-0.5   | 14        | 6.83%   |
| 3.01-4.0   | 13        | 6.34%   |
| 5.01-6.0   | 11        | 5.37%   |
| 8.01-16.0  | 4         | 1.95%   |
| 2.01-3.0   | 3         | 1.46%   |
| 0.51-1.0   | 2         | 0.98%   |
| 16.01-24.0 | 1         | 0.49%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 32        | 14.29%  |
| BOE                  | 31        | 13.84%  |
| AU Optronics         | 29        | 12.95%  |
| LG Display           | 22        | 9.82%   |
| Chimei Innolux       | 19        | 8.48%   |
| Hewlett-Packard      | 10        | 4.46%   |
| Apple                | 7         | 3.13%   |
| Acer                 | 7         | 3.13%   |
| Goldstar             | 6         | 2.68%   |
| Dell                 | 6         | 2.68%   |
| Sharp                | 5         | 2.23%   |
| BenQ                 | 5         | 2.23%   |
| AOC                  | 4         | 1.79%   |
| Ancor Communications | 4         | 1.79%   |
| PANDA                | 3         | 1.34%   |
| MSI                  | 3         | 1.34%   |
| Lenovo               | 3         | 1.34%   |
| TMX                  | 2         | 0.89%   |
| Philips              | 2         | 0.89%   |
| Iiyama               | 2         | 0.89%   |
| Gigabyte Technology  | 2         | 0.89%   |
| Unknown              | 2         | 0.89%   |
| Yeyian               | 1         | 0.45%   |
| Yamaha               | 1         | 0.45%   |
| Unknown              | 1         | 0.45%   |
| Toshiba              | 1         | 0.45%   |
| Sony                 | 1         | 0.45%   |
| Sceptre Tech         | 1         | 0.45%   |
| LGD                  | 1         | 0.45%   |
| Konka                | 1         | 0.45%   |
| Kogan                | 1         | 0.45%   |
| KOC                  | 1         | 0.45%   |
| JRY                  | 1         | 0.45%   |
| ITE                  | 1         | 0.45%   |
| Idek Iiyama          | 1         | 0.45%   |
| Hitachi              | 1         | 0.45%   |
| FOX                  | 1         | 0.45%   |
| CSO                  | 1         | 0.45%   |
| CHO                  | 1         | 0.45%   |
| ASUSTek Computer     | 1         | 0.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 3         | 1.3%    |
| Samsung Electronics S34J55x SAM0F70 3440x1440 800x330mm 34.1-inch       | 2         | 0.87%   |
| Samsung Electronics LCD Monitor SAM0F14 3840x2160 1872x1053mm 84.6-inch | 2         | 0.87%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 2         | 0.87%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch            | 2         | 0.87%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch            | 2         | 0.87%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 2         | 0.87%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                       | 2         | 0.87%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch         | 2         | 0.87%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch        | 2         | 0.87%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 2         | 0.87%   |
| BOE LCD Monitor BOE084E 1920x1080 382x215mm 17.3-inch                   | 2         | 0.87%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                   | 2         | 0.87%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch          | 2         | 0.87%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch           | 2         | 0.87%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch          | 2         | 0.87%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch          | 2         | 0.87%   |
| Unknown                                                                 | 2         | 0.87%   |
| Yeyian YMC-70102 YEY2700 1920x1080 698x393mm 31.5-inch                  | 1         | 0.43%   |
| Yamaha RX-V473 YMH3171 1920x540                                         | 1         | 0.43%   |
| Unknown LCD Monitor SAMSUNG 1360x768                                    | 1         | 0.43%   |
| Toshiba TV TSB0205 1360x768 886x498mm 40.0-inch                         | 1         | 0.43%   |
| TMX TL156VDXP0101 TMX1561 1920x1080 344x194mm 15.5-inch                 | 1         | 0.43%   |
| TMX TL156MDMP01-0 TMX1560 3200x2000 336x210mm 15.6-inch                 | 1         | 0.43%   |
| Sony LCD Monitor AVSYSTEM 1280x720                                      | 1         | 0.43%   |
| Sharp LQ134N1JW55 SHP1558 1920x1200 288x180mm 13.4-inch                 | 1         | 0.43%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch                 | 1         | 0.43%   |
| Sharp LCD Monitor SHP1463 3840x2160 346x194mm 15.6-inch                 | 1         | 0.43%   |
| Sharp LCD Monitor SHP1431 3840x2160 350x190mm 15.7-inch                 | 1         | 0.43%   |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch                 | 1         | 0.43%   |
| Sceptre Tech C27 SPT0ADD 1920x1080 598x336mm 27.0-inch                  | 1         | 0.43%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch       | 1         | 0.43%   |
| Samsung Electronics T27B300 SAM0933 1920x1080 598x336mm 27.0-inch       | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM0524 1920x1080 480x270mm 21.7-inch    | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM02FE 1680x1050 433x271mm 20.1-inch    | 1         | 0.43%   |
| Samsung Electronics SMS24A350H SAM07D6 1920x1080 531x299mm 24.0-inch    | 1         | 0.43%   |
| Samsung Electronics SMBX2450L SAM071F 1920x1080 521x293mm 23.5-inch     | 1         | 0.43%   |
| Samsung Electronics SMB2430H SAM064E 1920x1080                          | 1         | 0.43%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch       | 1         | 0.43%   |
| Samsung Electronics S27E510 SAM0C5F 1920x1080 598x336mm 27.0-inch       | 1         | 0.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 117       | 54.17%  |
| 1366x768 (WXGA)    | 26        | 12.04%  |
| 3840x2160 (4K)     | 17        | 7.87%   |
| 2560x1440 (QHD)    | 10        | 4.63%   |
| 1600x900 (HD+)     | 7         | 3.24%   |
| 3440x1440          | 6         | 2.78%   |
| 2560x1600          | 3         | 1.39%   |
| 2560x1080          | 3         | 1.39%   |
| 1920x1200 (WUXGA)  | 3         | 1.39%   |
| 1280x800 (WXGA)    | 3         | 1.39%   |
| 3840x1080          | 2         | 0.93%   |
| 3200x1800 (QHD+)   | 2         | 0.93%   |
| 2736x1824          | 2         | 0.93%   |
| 2160x1440          | 2         | 0.93%   |
| 1920x540           | 2         | 0.93%   |
| 1680x1050 (WSXGA+) | 2         | 0.93%   |
| 1360x768           | 2         | 0.93%   |
| 3840x2400          | 1         | 0.46%   |
| 3200x2000          | 1         | 0.46%   |
| 2880x1800          | 1         | 0.46%   |
| 1440x900 (WXGA+)   | 1         | 0.46%   |
| 1280x720 (HD)      | 1         | 0.46%   |
| 1280x1024 (SXGA)   | 1         | 0.46%   |
| Unknown            | 1         | 0.46%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 68        | 30.22%  |
| 13      | 24        | 10.67%  |
| 27      | 18        | 8%      |
| 14      | 18        | 8%      |
| 23      | 15        | 6.67%   |
| 21      | 13        | 5.78%   |
| 24      | 11        | 4.89%   |
| 17      | 9         | 4%      |
| Unknown | 9         | 4%      |
| 31      | 8         | 3.56%   |
| 34      | 7         | 3.11%   |
| 84      | 5         | 2.22%   |
| 12      | 3         | 1.33%   |
| 28      | 2         | 0.89%   |
| 20      | 2         | 0.89%   |
| 18      | 2         | 0.89%   |
| 16      | 2         | 0.89%   |
| 72      | 1         | 0.44%   |
| 63      | 1         | 0.44%   |
| 54      | 1         | 0.44%   |
| 52      | 1         | 0.44%   |
| 48      | 1         | 0.44%   |
| 40      | 1         | 0.44%   |
| 33      | 1         | 0.44%   |
| 29      | 1         | 0.44%   |
| 26      | 1         | 0.44%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 98        | 43.95%  |
| 501-600     | 41        | 18.39%  |
| 401-500     | 17        | 7.62%   |
| 201-300     | 16        | 7.17%   |
| 601-700     | 12        | 5.38%   |
| 351-400     | 11        | 4.93%   |
| Unknown     | 9         | 4.04%   |
| 701-800     | 8         | 3.59%   |
| 1501-2000   | 6         | 2.69%   |
| 1001-1500   | 4         | 1.79%   |
| 801-900     | 1         | 0.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 167       | 83.08%  |
| 16/10   | 13        | 6.47%   |
| 21/9    | 9         | 4.48%   |
| Unknown | 6         | 2.99%   |
| 3/2     | 3         | 1.49%   |
| 32/9    | 2         | 1%      |
| 5/4     | 1         | 0.5%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 69        | 31.08%  |
| 201-250        | 34        | 15.32%  |
| 81-90          | 33        | 14.86%  |
| 301-350        | 18        | 8.11%   |
| 351-500        | 17        | 7.66%   |
| 71-80          | 11        | 4.95%   |
| More than 1000 | 9         | 4.05%   |
| 121-130        | 9         | 4.05%   |
| Unknown        | 9         | 4.05%   |
| 151-200        | 5         | 2.25%   |
| 251-300        | 3         | 1.35%   |
| 501-1000       | 2         | 0.9%    |
| 61-70          | 1         | 0.45%   |
| 141-150        | 1         | 0.45%   |
| 111-120        | 1         | 0.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 78        | 36.11%  |
| 51-100        | 55        | 25.46%  |
| 101-120       | 51        | 23.61%  |
| 161-240       | 12        | 5.56%   |
| Unknown       | 9         | 4.17%   |
| More than 240 | 7         | 3.24%   |
| 1-50          | 4         | 1.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 167       | 81.86%  |
| 2     | 32        | 15.69%  |
| 3     | 3         | 1.47%   |
| 0     | 2         | 0.98%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 111       | 37.25%  |
| Intel                             | 108       | 36.24%  |
| Qualcomm Atheros                  | 18        | 6.04%   |
| Broadcom                          | 11        | 3.69%   |
| MediaTek                          | 9         | 3.02%   |
| Broadcom Limited                  | 8         | 2.68%   |
| TP-Link                           | 4         | 1.34%   |
| Ralink Technology                 | 3         | 1.01%   |
| Ralink                            | 3         | 1.01%   |
| Marvell Technology Group          | 3         | 1.01%   |
| ASIX Electronics                  | 3         | 1.01%   |
| Sierra Wireless                   | 2         | 0.67%   |
| Samsung Electronics               | 2         | 0.67%   |
| Qualcomm                          | 2         | 0.67%   |
| Nvidia                            | 2         | 0.67%   |
| Ericsson Business Mobile Networks | 2         | 0.67%   |
| Qualcomm Atheros Communications   | 1         | 0.34%   |
| NetGear                           | 1         | 0.34%   |
| Microsoft                         | 1         | 0.34%   |
| Huawei Technologies               | 1         | 0.34%   |
| DisplayLink                       | 1         | 0.34%   |
| Dell                              | 1         | 0.34%   |
| Aquantia                          | 1         | 0.34%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 79        | 22.01%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 11        | 3.06%   |
| Intel Wireless 8265 / 8275                                        | 11        | 3.06%   |
| Intel Wi-Fi 6 AX200                                               | 11        | 3.06%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 2.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 2.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 2.23%   |
| Intel Wi-Fi 6 AX201                                               | 8         | 2.23%   |
| Intel I211 Gigabit Network Connection                             | 7         | 1.95%   |
| Intel Ethernet Connection (2) I219-V                              | 7         | 1.95%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 1.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 1.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 6         | 1.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 1.67%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 5         | 1.39%   |
| Intel Wireless 7265                                               | 5         | 1.39%   |
| Intel Wireless 7260                                               | 5         | 1.39%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 1.11%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 1.11%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.11%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 0.84%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.84%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 3         | 0.84%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 0.84%   |
| Intel Centrino Wireless-N 2230                                    | 3         | 0.84%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 3         | 0.84%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter        | 3         | 0.84%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 3         | 0.84%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 0.84%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 2         | 0.56%   |
| Sierra Wireless EM7455                                            | 2         | 0.56%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2         | 0.56%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.56%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 0.56%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                 | 2         | 0.56%   |
| Intel Wireless-AC 9260                                            | 2         | 0.56%   |
| Intel Wireless 8260                                               | 2         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 87        | 49.43%  |
| Realtek Semiconductor           | 30        | 17.05%  |
| Qualcomm Atheros                | 16        | 9.09%   |
| MediaTek                        | 9         | 5.11%   |
| Broadcom                        | 9         | 5.11%   |
| Broadcom Limited                | 7         | 3.98%   |
| TP-Link                         | 4         | 2.27%   |
| Ralink Technology               | 3         | 1.7%    |
| Ralink                          | 3         | 1.7%    |
| Sierra Wireless                 | 2         | 1.14%   |
| Marvell Technology Group        | 2         | 1.14%   |
| Qualcomm Atheros Communications | 1         | 0.57%   |
| NetGear                         | 1         | 0.57%   |
| Microsoft                       | 1         | 0.57%   |
| Dell                            | 1         | 0.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 11        | 6.25%   |
| Intel Wireless 8265 / 8275                                     | 11        | 6.25%   |
| Intel Wi-Fi 6 AX200                                            | 11        | 6.25%   |
| Intel Wi-Fi 6 AX201                                            | 8         | 4.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 6         | 3.41%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 6         | 3.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 6         | 3.41%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 5         | 2.84%   |
| Intel Wireless 7265                                            | 5         | 2.84%   |
| Intel Wireless 7260                                            | 5         | 2.84%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 2.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 2.27%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 4         | 2.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 2.27%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 1.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 1.7%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 3         | 1.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 3         | 1.7%    |
| Intel Centrino Wireless-N 2230                                 | 3         | 1.7%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 3         | 1.7%    |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 3         | 1.7%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 3         | 1.7%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 2         | 1.14%   |
| Sierra Wireless EM7455                                         | 2         | 1.14%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 1.14%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 2         | 1.14%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 1.14%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 2         | 1.14%   |
| Intel Wireless-AC 9260                                         | 2         | 1.14%   |
| Intel Wireless 8260                                            | 2         | 1.14%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 1.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.14%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 1.14%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 1.14%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 1         | 0.57%   |
| TP-Link 802.11ac NIC                                           | 1         | 0.57%   |
| Realtek RTL8852AE WiFi 6 802.11ax PCIe Adapter                 | 1         | 0.57%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 0.57%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.57%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 99        | 56.9%   |
| Intel                    | 54        | 31.03%  |
| Broadcom                 | 5         | 2.87%   |
| Qualcomm Atheros         | 4         | 2.3%    |
| ASIX Electronics         | 3         | 1.72%   |
| Qualcomm                 | 2         | 1.15%   |
| Nvidia                   | 2         | 1.15%   |
| Marvell Technology Group | 1         | 0.57%   |
| Huawei Technologies      | 1         | 0.57%   |
| DisplayLink              | 1         | 0.57%   |
| Broadcom Limited         | 1         | 0.57%   |
| Aquantia                 | 1         | 0.57%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 79        | 44.13%  |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 5.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 5.03%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 4.47%   |
| Intel I211 Gigabit Network Connection                             | 7         | 3.91%   |
| Intel Ethernet Connection (2) I219-V                              | 7         | 3.91%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 3.35%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 2.23%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 1.68%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.12%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 1.12%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 1.12%   |
| Intel Ethernet Connection (3) I218-V                              | 2         | 1.12%   |
| Intel Ethernet Connection (11) I219-V                             | 2         | 1.12%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 1.12%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.56%   |
| Qualcomm SM6150-IDP _SN:488AC473                                  | 1         | 0.56%   |
| Qualcomm Redmi Note 8                                             | 1         | 0.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.56%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.56%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.56%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.56%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.56%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.56%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.56%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.56%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.56%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.56%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.56%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.56%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.56%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.56%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 0.56%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 0.56%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.56%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.56%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.56%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 167       | 49.85%  |
| Ethernet | 164       | 48.96%  |
| Modem    | 4         | 1.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 126       | 60.87%  |
| Ethernet | 81        | 39.13%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 106       | 51.96%  |
| 1     | 90        | 44.12%  |
| 3     | 5         | 2.45%   |
| 8     | 1         | 0.49%   |
| 4     | 1         | 0.49%   |
| 0     | 1         | 0.49%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 139       | 68.14%  |
| Yes  | 65        | 31.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 74        | 47.44%  |
| Realtek Semiconductor           | 19        | 12.18%  |
| IMC Networks                    | 10        | 6.41%   |
| Cambridge Silicon Radio         | 8         | 5.13%   |
| Broadcom                        | 8         | 5.13%   |
| Qualcomm Atheros Communications | 7         | 4.49%   |
| Apple                           | 7         | 4.49%   |
| Foxconn / Hon Hai               | 5         | 3.21%   |
| Lite-On Technology              | 4         | 2.56%   |
| ASUSTek Computer                | 4         | 2.56%   |
| MediaTek                        | 3         | 1.92%   |
| Marvell Semiconductor           | 2         | 1.28%   |
| TP-Link                         | 1         | 0.64%   |
| Toshiba                         | 1         | 0.64%   |
| Realtek                         | 1         | 0.64%   |
| Dell                            | 1         | 0.64%   |
| Alps Electric                   | 1         | 0.64%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 22        | 14.1%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 20        | 12.82%  |
| Realtek Bluetooth Radio                             | 11        | 7.05%   |
| Intel AX201 Bluetooth                               | 11        | 7.05%   |
| Intel AX200 Bluetooth                               | 11        | 7.05%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8         | 5.13%   |
| Realtek  Bluetooth 4.2 Adapter                      | 6         | 3.85%   |
| Qualcomm Atheros  Bluetooth Device                  | 6         | 3.85%   |
| IMC Networks Wireless_Device                        | 5         | 3.21%   |
| Apple Bluetooth Host Controller                     | 5         | 3.21%   |
| IMC Networks Bluetooth Radio                        | 4         | 2.56%   |
| MediaTek Wireless_Device                            | 3         | 1.92%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 1.92%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 1.28%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 1.28%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.28%   |
| Intel AX210 Bluetooth                               | 2         | 1.28%   |
| Broadcom BCM20702A0 Bluetooth                       | 2         | 1.28%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.28%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2         | 1.28%   |
| Apple Bluetooth USB Host Controller                 | 2         | 1.28%   |
| TP-Link UB500 Adapter                               | 1         | 0.64%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.64%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.64%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.64%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 0.64%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.64%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 0.64%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 0.64%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.64%   |
| Lite-On Bluetooth Device                            | 1         | 0.64%   |
| Intel Bluetooth Device                              | 1         | 0.64%   |
| IMC Networks BCM20702A0                             | 1         | 0.64%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.64%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 1         | 0.64%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 1         | 0.64%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.64%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 0.64%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 0.64%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 0.64%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 151       | 49.83%  |
| Nvidia                     | 61        | 20.13%  |
| AMD                        | 57        | 18.81%  |
| C-Media Electronics        | 4         | 1.32%   |
| GN Netcom                  | 3         | 0.99%   |
| Corsair                    | 3         | 0.99%   |
| Razer USA                  | 2         | 0.66%   |
| Kingston Technology        | 2         | 0.66%   |
| JMTek                      | 2         | 0.66%   |
| Generalplus Technology     | 2         | 0.66%   |
| Elgato Systems             | 2         | 0.66%   |
| Tenx Technology            | 1         | 0.33%   |
| Samsung Electronics        | 1         | 0.33%   |
| Realtek Semiconductor      | 1         | 0.33%   |
| PreSonus Audio Electronics | 1         | 0.33%   |
| Plantronics                | 1         | 0.33%   |
| Logitech                   | 1         | 0.33%   |
| Lenovo                     | 1         | 0.33%   |
| Jieli Technology           | 1         | 0.33%   |
| JBL                        | 1         | 0.33%   |
| Hewlett-Packard            | 1         | 0.33%   |
| ELMCU                      | 1         | 0.33%   |
| Barco Display Systems      | 1         | 0.33%   |
| ASUSTek Computer           | 1         | 0.33%   |
| Astro Gaming               | 1         | 0.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 25        | 6.87%   |
| Intel Sunrise Point-LP HD Audio                                            | 19        | 5.22%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 13        | 3.57%   |
| AMD Starship/Matisse HD Audio Controller                                   | 13        | 3.57%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 11        | 3.02%   |
| Intel Cannon Lake PCH cAVS                                                 | 11        | 3.02%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 10        | 2.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 9         | 2.47%   |
| Intel 200 Series PCH HD Audio                                              | 9         | 2.47%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 8         | 2.2%    |
| Intel Haswell-ULT HD Audio Controller                                      | 8         | 2.2%    |
| Intel Broadwell-U Audio Controller                                         | 8         | 2.2%    |
| Intel 8 Series HD Audio Controller                                         | 8         | 2.2%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8         | 2.2%    |
| Nvidia TU116 High Definition Audio Controller                              | 7         | 1.92%   |
| Nvidia GP107GL High Definition Audio Controller                            | 7         | 1.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7         | 1.92%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 7         | 1.92%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7         | 1.92%   |
| Nvidia TU106 High Definition Audio Controller                              | 6         | 1.65%   |
| Nvidia GP104 High Definition Audio Controller                              | 6         | 1.65%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 6         | 1.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 1.65%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 1.65%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 1.37%   |
| Nvidia GA106 High Definition Audio Controller                              | 5         | 1.37%   |
| AMD Navi 10 HDMI Audio                                                     | 5         | 1.37%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5         | 1.37%   |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 1.1%    |
| Intel Comet Lake PCH cAVS                                                  | 4         | 1.1%    |
| Intel CM238 HD Audio Controller                                            | 4         | 1.1%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 1.1%    |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 4         | 1.1%    |
| Nvidia GK107 HDMI Audio Controller                                         | 3         | 0.82%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 0.82%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 0.82%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3         | 0.82%   |
| AMD FCH Azalia Controller                                                  | 3         | 0.82%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3         | 0.82%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 47        | 22.38%  |
| SK hynix                     | 44        | 20.95%  |
| Micron Technology            | 25        | 11.9%   |
| Crucial                      | 17        | 8.1%    |
| Kingston                     | 16        | 7.62%   |
| Corsair                      | 14        | 6.67%   |
| Unknown                      | 10        | 4.76%   |
| G.Skill                      | 10        | 4.76%   |
| Ramaxel Technology           | 8         | 3.81%   |
| Team                         | 5         | 2.38%   |
| A-DATA Technology            | 3         | 1.43%   |
| Timetec                      | 2         | 0.95%   |
| Unifosa                      | 1         | 0.48%   |
| Transcend                    | 1         | 0.48%   |
| PNY                          | 1         | 0.48%   |
| Patriot Memory (PDP Systems) | 1         | 0.48%   |
| Nanya Technology             | 1         | 0.48%   |
| Kllisre                      | 1         | 0.48%   |
| KingFast                     | 1         | 0.48%   |
| GeIL                         | 1         | 0.48%   |
| Elpida                       | 1         | 0.48%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 5         | 2.25%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s       | 5         | 2.25%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s       | 4         | 1.8%    |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s       | 4         | 1.8%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s       | 3         | 1.35%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                | 2         | 0.9%    |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s      | 2         | 0.9%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 2         | 0.9%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 2         | 0.9%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 2         | 0.9%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 2         | 0.9%    |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 2         | 0.9%    |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s     | 2         | 0.9%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 2         | 0.9%    |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 2         | 0.9%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 2         | 0.9%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 2         | 0.9%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s       | 2         | 0.9%    |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s    | 2         | 0.9%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s       | 2         | 0.9%    |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s       | 2         | 0.9%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 2         | 0.9%    |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s   | 2         | 0.9%    |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s   | 2         | 0.9%    |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s | 2         | 0.9%    |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2667MT/s       | 2         | 0.9%    |
| Kingston RAM KHX2133C14/16G 16GB DIMM DDR4 2176MT/s         | 2         | 0.9%    |
| Crucial RAM CT8G4SFS824A.C8FHD1 8GB SODIMM DDR4 2667MT/s    | 2         | 0.9%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s       | 2         | 0.9%    |
| A-DATA RAM DDR4 3200 16GB DIMM DDR4 3600MT/s                | 2         | 0.9%    |
| Unknown RAM Module 8GB SODIMM DDR3 1067MT/s                 | 1         | 0.45%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                   | 1         | 0.45%   |
| Unknown RAM Module 4GB SODIMM LPDDR3 1600MT/s               | 1         | 0.45%   |
| Unknown RAM Module 4GB DIMM DDR4 2133MT/s                   | 1         | 0.45%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                    | 1         | 0.45%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                   | 1         | 0.45%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                 | 1         | 0.45%   |
| Unknown RAM Module 2GB SODIMM DDR2                          | 1         | 0.45%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                    | 1         | 0.45%   |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s                   | 1         | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 110       | 61.8%   |
| DDR3   | 45        | 25.28%  |
| LPDDR3 | 5         | 2.81%   |
| LPDDR4 | 4         | 2.25%   |
| DDR2   | 4         | 2.25%   |
| LPDDR5 | 3         | 1.69%   |
| DDR5   | 3         | 1.69%   |
| SDRAM  | 2         | 1.12%   |
| DDR    | 2         | 1.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 106       | 59.22%  |
| DIMM         | 57        | 31.84%  |
| Row Of Chips | 15        | 8.38%   |
| Chip         | 1         | 0.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 87        | 44.85%  |
| 4096  | 55        | 28.35%  |
| 16384 | 34        | 17.53%  |
| 2048  | 12        | 6.19%   |
| 32768 | 5         | 2.58%   |
| 1024  | 1         | 0.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 43        | 21.5%   |
| 3200    | 35        | 17.5%   |
| 1600    | 33        | 16.5%   |
| 2400    | 13        | 6.5%    |
| 1333    | 10        | 5%      |
| 3600    | 9         | 4.5%    |
| 2133    | 9         | 4.5%    |
| 3266    | 5         | 2.5%    |
| 1067    | 4         | 2%      |
| 6400    | 3         | 1.5%    |
| 4800    | 3         | 1.5%    |
| 3733    | 3         | 1.5%    |
| 2933    | 3         | 1.5%    |
| 1800    | 3         | 1.5%    |
| 800     | 3         | 1.5%    |
| 4267    | 2         | 1%      |
| 3400    | 2         | 1%      |
| 2176    | 2         | 1%      |
| 1867    | 2         | 1%      |
| Unknown | 2         | 1%      |
| 8400    | 1         | 0.5%    |
| 4400    | 1         | 0.5%    |
| 4199    | 1         | 0.5%    |
| 4133    | 1         | 0.5%    |
| 3800    | 1         | 0.5%    |
| 3467    | 1         | 0.5%    |
| 3000    | 1         | 0.5%    |
| 2747    | 1         | 0.5%    |
| 2666    | 1         | 0.5%    |
| 1450    | 1         | 0.5%    |
| 1334    | 1         | 0.5%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 200 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 29        | 22.31%  |
| IMC Networks                           | 26        | 20%     |
| Realtek Semiconductor                  | 13        | 10%     |
| Sunplus Innovation Technology          | 8         | 6.15%   |
| Microdia                               | 7         | 5.38%   |
| Syntek                                 | 6         | 4.62%   |
| Quanta                                 | 6         | 4.62%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 3.85%   |
| Bison Electronics                      | 5         | 3.85%   |
| Acer                                   | 4         | 3.08%   |
| Logitech                               | 3         | 2.31%   |
| Apple                                  | 3         | 2.31%   |
| Ricoh                                  | 2         | 1.54%   |
| Luxvisions Innotech Limited            | 2         | 1.54%   |
| Lite-On Technology                     | 2         | 1.54%   |
| Generalplus Technology                 | 2         | 1.54%   |
| Suyin                                  | 1         | 0.77%   |
| Sonix Technology                       | 1         | 0.77%   |
| Panasonic (Matsushita)                 | 1         | 0.77%   |
| Microsoft                              | 1         | 0.77%   |
| Creative Technology                    | 1         | 0.77%   |
| Alpha Imaging Technology               | 1         | 0.77%   |
| Alcor Micro                            | 1         | 0.77%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam      | 9         | 6.82%   |
| IMC Networks Integrated Camera         | 7         | 5.3%    |
| Syntek Integrated Camera               | 6         | 4.55%   |
| Realtek Integrated_Webcam_HD           | 6         | 4.55%   |
| Chicony integrated camera              | 6         | 4.55%   |
| Quanta HP TrueVision HD Camera         | 4         | 3.03%   |
| Microdia Integrated_Webcam_HD          | 3         | 2.27%   |
| IMC Networks USB2.0 VGA UVC WebCam     | 3         | 2.27%   |
| Chicony EasyCamera                     | 3         | 2.27%   |
| Acer Integrated Camera                 | 3         | 2.27%   |
| Realtek Integrated Webcam_HD           | 2         | 1.52%   |
| Lite-On Integrated Camera              | 2         | 1.52%   |
| Chicony HP Webcam                      | 2         | 1.52%   |
| Chicony HP TrueVision HD Camera        | 2         | 1.52%   |
| Chicony HP High Definition 1MP Webcam  | 2         | 1.52%   |
| Chicony HD WebCam                      | 2         | 1.52%   |
| Bison ThinkPad Integrated Camera       | 2         | 1.52%   |
| Apple Built-in iSight                  | 2         | 1.52%   |
| Suyin Asus Integrated Webcam           | 1         | 0.76%   |
| Sunplus XiaoMi USB 2.0 Webcam          | 1         | 0.76%   |
| Sunplus Lenovo EasyCamera              | 1         | 0.76%   |
| Sunplus Laptop_Integrated_Webcam_FHD   | 1         | 0.76%   |
| Sunplus Laptop Integrated Webcam FHD   | 1         | 0.76%   |
| Sunplus Integrated_Webcam_HD           | 1         | 0.76%   |
| Sunplus Integrated_Webcam_FHD          | 1         | 0.76%   |
| Sunplus HP Truevision HD               | 1         | 0.76%   |
| Sunplus 1080p FHD Camera               | 1         | 0.76%   |
| Sonix USB2.0 HD UVC WebCam             | 1         | 0.76%   |
| Ricoh Sony Visual Communication Camera | 1         | 0.76%   |
| Ricoh Integrated Webcam                | 1         | 0.76%   |
| Realtek USB2.0 HD UVC WebCam           | 1         | 0.76%   |
| Realtek Integrated Webcam              | 1         | 0.76%   |
| Realtek Integrated Camera              | 1         | 0.76%   |
| Realtek EasyCamera                     | 1         | 0.76%   |
| Realtek Built-In Video Camera          | 1         | 0.76%   |
| Quanta HP Wide Vision FHD Camera       | 1         | 0.76%   |
| Quanta HD User Facing                  | 1         | 0.76%   |
| Panasonic (Matsushita) TY-CC20W        | 1         | 0.76%   |
| Microsoft LifeCam Rear                 | 1         | 0.76%   |
| Microsoft LifeCam Front                | 1         | 0.76%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 36.84%  |
| Synaptics                  | 5         | 26.32%  |
| Shenzhen Goodix Technology | 3         | 15.79%  |
| Elan Microelectronics      | 2         | 10.53%  |
| LighTuning Technology      | 1         | 5.26%   |
| AuthenTec                  | 1         | 5.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                   | 3         | 15.79%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 2         | 10.53%  |
| Shenzhen Goodix  Fingerprint Device               | 2         | 10.53%  |
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 5.26%   |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 5.26%   |
| Synaptics WBDI                                    | 1         | 5.26%   |
| Synaptics UWP WBDI                                | 1         | 5.26%   |
| Synaptics  WBDI                                   | 1         | 5.26%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 5.26%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 5.26%   |
| Shenzhen Goodix Fingerprint Reader                | 1         | 5.26%   |
| LighTuning Fingerprint Reader                     | 1         | 5.26%   |
| Elan fingerprint sensor [FeinTech FPS00200]       | 1         | 5.26%   |
| Elan ELAN:Fingerprint                             | 1         | 5.26%   |
| AuthenTec Fingerprint Sensor                      | 1         | 5.26%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 5         | 38.46%  |
| Broadcom    | 4         | 30.77%  |
| Upek        | 2         | 15.38%  |
| Yubico.com  | 1         | 7.69%   |
| Clay Logic  | 1         | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 5         | 38.46%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 2         | 15.38%  |
| Broadcom BCM5880 Secure Applications Processor             | 2         | 15.38%  |
| Yubico.com Yubikey NEO(-N) OTP+CCID                        | 1         | 7.69%   |
| Clay Logic Nitrokey Pro                                    | 1         | 7.69%   |
| Broadcom 5880                                              | 1         | 7.69%   |
| Broadcom 58200                                             | 1         | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 151       | 74.02%  |
| 1     | 43        | 21.08%  |
| 2     | 9         | 4.41%   |
| 3     | 1         | 0.49%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 19        | 30.65%  |
| Graphics card            | 14        | 22.58%  |
| Chipcard                 | 11        | 17.74%  |
| Multimedia controller    | 6         | 9.68%   |
| Bluetooth                | 3         | 4.84%   |
| Unassigned class         | 2         | 3.23%   |
| Net/wireless             | 2         | 3.23%   |
| Camera                   | 2         | 3.23%   |
| Storage                  | 1         | 1.61%   |
| Network                  | 1         | 1.61%   |
| Communication controller | 1         | 1.61%   |

