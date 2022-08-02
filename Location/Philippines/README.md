Linux in Philippines - Tested Hardware & Statistics
---------------------------------------------------

A project to collect tested hardware configurations for Linux in Philippines.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Philippines/Desktop/README.md) and [notebooks](/Location/Philippines/Notebook/README.md).

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

Total: 602

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | H81M-D2V                    | Desktop     | [64da165357](https://linux-hardware.org/?probe=64da165357) | Aug 01, 2022 |
| Lenovo        | ThinkPad E590 20NB0032CD    | Notebook    | [502b0eeb39](https://linux-hardware.org/?probe=502b0eeb39) | Aug 01, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [0f38b878b5](https://linux-hardware.org/?probe=0f38b878b5) | Jul 31, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [8a472804e4](https://linux-hardware.org/?probe=8a472804e4) | Jul 30, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | Notebook    | [9c0b784d1d](https://linux-hardware.org/?probe=9c0b784d1d) | Jul 27, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [a0e19ce405](https://linux-hardware.org/?probe=a0e19ce405) | Jul 26, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [437ba53b68](https://linux-hardware.org/?probe=437ba53b68) | Jul 25, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [f47a0ecbf5](https://linux-hardware.org/?probe=f47a0ecbf5) | Jul 25, 2022 |
| MSI           | CX62 6QD                    | Notebook    | [d0c23fefca](https://linux-hardware.org/?probe=d0c23fefca) | Jul 24, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [d404840b57](https://linux-hardware.org/?probe=d404840b57) | Jul 24, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [37521f84c8](https://linux-hardware.org/?probe=37521f84c8) | Jul 20, 2022 |
| ASUSTek       | M4A88T-M                    | Desktop     | [57ed9f00c7](https://linux-hardware.org/?probe=57ed9f00c7) | Jul 18, 2022 |
| ASUSTek       | M4A88T-M                    | Desktop     | [f99189e2d0](https://linux-hardware.org/?probe=f99189e2d0) | Jul 18, 2022 |
| Unknown       | Unknown                     | Notebook    | [251f348fe5](https://linux-hardware.org/?probe=251f348fe5) | Jul 17, 2022 |
| Dell          | Vostro 3700                 | Notebook    | [2b7a37d662](https://linux-hardware.org/?probe=2b7a37d662) | Jul 16, 2022 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | Notebook    | [24c803a5fc](https://linux-hardware.org/?probe=24c803a5fc) | Jul 15, 2022 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [c1ed74053e](https://linux-hardware.org/?probe=c1ed74053e) | Jul 11, 2022 |
| YANYU         | EPIC-C19                    | Desktop     | [5bda78db57](https://linux-hardware.org/?probe=5bda78db57) | Jul 11, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [b6a7451086](https://linux-hardware.org/?probe=b6a7451086) | Jul 11, 2022 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | Notebook    | [b9c939b2e2](https://linux-hardware.org/?probe=b9c939b2e2) | Jul 09, 2022 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | Notebook    | [88cc242e02](https://linux-hardware.org/?probe=88cc242e02) | Jul 09, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [264b084b00](https://linux-hardware.org/?probe=264b084b00) | Jul 08, 2022 |
| Acer          | Aspire E5-473G              | Notebook    | [11b488a036](https://linux-hardware.org/?probe=11b488a036) | Jul 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [c9d2a76068](https://linux-hardware.org/?probe=c9d2a76068) | Jul 03, 2022 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [b7fedc25e4](https://linux-hardware.org/?probe=b7fedc25e4) | Jul 01, 2022 |
| Gigabyte      | A520M DS3H                  | Desktop     | [b56fe3beb3](https://linux-hardware.org/?probe=b56fe3beb3) | Jun 28, 2022 |
| Lenovo        | IdeaPad 320-14AST 80XU      | Notebook    | [78eaeff700](https://linux-hardware.org/?probe=78eaeff700) | Jun 27, 2022 |
| Acer          | Predator PH315-53           | Notebook    | [c23e943030](https://linux-hardware.org/?probe=c23e943030) | Jun 21, 2022 |
| MSI           | A320M PRO-VH                | Desktop     | [47f765c61f](https://linux-hardware.org/?probe=47f765c61f) | Jun 14, 2022 |
| MSI           | H81M-E33                    | Desktop     | [49191a1c98](https://linux-hardware.org/?probe=49191a1c98) | Jun 08, 2022 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [017e41e32c](https://linux-hardware.org/?probe=017e41e32c) | Jun 07, 2022 |
| MSI           | H81M-E33                    | Desktop     | [6a2d6cbe74](https://linux-hardware.org/?probe=6a2d6cbe74) | Jun 04, 2022 |
| Dell          | Inspiron 3531               | Notebook    | [c2d9f4b84b](https://linux-hardware.org/?probe=c2d9f4b84b) | Jun 02, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [512fb81a9b](https://linux-hardware.org/?probe=512fb81a9b) | May 31, 2022 |
| MSI           | Z97 XPOWER AC               | Desktop     | [dd5c7a981a](https://linux-hardware.org/?probe=dd5c7a981a) | May 29, 2022 |
| MSI           | MS-7717                     | Desktop     | [101b488b80](https://linux-hardware.org/?probe=101b488b80) | May 28, 2022 |
| MSI           | MS-7717                     | Desktop     | [9b0c2d0d8c](https://linux-hardware.org/?probe=9b0c2d0d8c) | May 28, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [0656adeb11](https://linux-hardware.org/?probe=0656adeb11) | May 24, 2022 |
| Dell          | Vostro 5515                 | Notebook    | [b884e51280](https://linux-hardware.org/?probe=b884e51280) | May 21, 2022 |
| ASUSTek       | TUF Gaming FX705DU_FX705... | Notebook    | [a3e1bf045d](https://linux-hardware.org/?probe=a3e1bf045d) | May 20, 2022 |
| ASUSTek       | ROG Strix G731GT_G731GT     | Notebook    | [5c20c841d1](https://linux-hardware.org/?probe=5c20c841d1) | May 18, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [0571b7cb83](https://linux-hardware.org/?probe=0571b7cb83) | May 18, 2022 |
| Acer          | TravelMate P249-G2-MG       | Notebook    | [e6f35b116a](https://linux-hardware.org/?probe=e6f35b116a) | May 15, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [debbc95647](https://linux-hardware.org/?probe=debbc95647) | May 12, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [915b95cae4](https://linux-hardware.org/?probe=915b95cae4) | May 11, 2022 |
| Unknown       | Unknown                     | Notebook    | [fac14402be](https://linux-hardware.org/?probe=fac14402be) | May 11, 2022 |
| Acer          | Aspire E5-576G              | Notebook    | [27f577ec86](https://linux-hardware.org/?probe=27f577ec86) | May 10, 2022 |
| ECS           | A68M-C4DL                   | Desktop     | [b8c60cf7a0](https://linux-hardware.org/?probe=b8c60cf7a0) | May 09, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [5b877349c1](https://linux-hardware.org/?probe=5b877349c1) | May 09, 2022 |
| HP            | 212A                        | Desktop     | [acd660910f](https://linux-hardware.org/?probe=acd660910f) | May 09, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [07ed7fd709](https://linux-hardware.org/?probe=07ed7fd709) | May 08, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [443d537d91](https://linux-hardware.org/?probe=443d537d91) | May 05, 2022 |
| Apple         | MacBookAir5,1               | Notebook    | [45c12c8fc4](https://linux-hardware.org/?probe=45c12c8fc4) | Apr 30, 2022 |
| Acer          | TravelMate P249-G2-MG       | Notebook    | [2e0bd790c6](https://linux-hardware.org/?probe=2e0bd790c6) | Apr 26, 2022 |
| Acer          | Aspire E5-551G              | Notebook    | [8dd5e105d1](https://linux-hardware.org/?probe=8dd5e105d1) | Apr 21, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [74323309f1](https://linux-hardware.org/?probe=74323309f1) | Apr 20, 2022 |
| Toshiba       | TECRA R940                  | Notebook    | [e7dc07a41c](https://linux-hardware.org/?probe=e7dc07a41c) | Apr 20, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [1f3827f38e](https://linux-hardware.org/?probe=1f3827f38e) | Apr 18, 2022 |
| Unknown       | Unknown                     | Notebook    | [cfd3bd53a8](https://linux-hardware.org/?probe=cfd3bd53a8) | Apr 18, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [b824b88050](https://linux-hardware.org/?probe=b824b88050) | Apr 15, 2022 |
| Toshiba       | Satellite E45t-A            | Notebook    | [3698a21b91](https://linux-hardware.org/?probe=3698a21b91) | Apr 15, 2022 |
| Toshiba       | dynabook B45/A              | Notebook    | [f430a05b2d](https://linux-hardware.org/?probe=f430a05b2d) | Apr 09, 2022 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [5a576e8488](https://linux-hardware.org/?probe=5a576e8488) | Apr 01, 2022 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [83800436e5](https://linux-hardware.org/?probe=83800436e5) | Mar 31, 2022 |
| Shenzhen B... | NBPC1078                    | Tablet      | [33e297566b](https://linux-hardware.org/?probe=33e297566b) | Mar 30, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [03b7f74d31](https://linux-hardware.org/?probe=03b7f74d31) | Mar 29, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [42e921877b](https://linux-hardware.org/?probe=42e921877b) | Mar 29, 2022 |
| HP            | 2B38                        | Desktop     | [99fd9bb200](https://linux-hardware.org/?probe=99fd9bb200) | Mar 27, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [8dbd85ced8](https://linux-hardware.org/?probe=8dbd85ced8) | Mar 25, 2022 |
| MSI           | MS-7619                     | Desktop     | [65c73f26b0](https://linux-hardware.org/?probe=65c73f26b0) | Mar 22, 2022 |
| MSI           | H510M PRO-E                 | Desktop     | [111cf21b7f](https://linux-hardware.org/?probe=111cf21b7f) | Mar 21, 2022 |
| ASUSTek       | ROG STRIX Z490-I GAMING     | Desktop     | [95373e24b7](https://linux-hardware.org/?probe=95373e24b7) | Mar 16, 2022 |
| MSI           | B560M PRO-VDH WIFI          | Desktop     | [c15007b668](https://linux-hardware.org/?probe=c15007b668) | Mar 15, 2022 |
| MSI           | H510M PRO-E                 | Desktop     | [ad5840ceb1](https://linux-hardware.org/?probe=ad5840ceb1) | Mar 14, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [1a9459872a](https://linux-hardware.org/?probe=1a9459872a) | Mar 13, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [bd9b6ec157](https://linux-hardware.org/?probe=bd9b6ec157) | Mar 11, 2022 |
| Lenovo        | ThinkPad E480 20KN002YPH    | Notebook    | [2f136d5bf5](https://linux-hardware.org/?probe=2f136d5bf5) | Mar 11, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [946300c067](https://linux-hardware.org/?probe=946300c067) | Mar 10, 2022 |
| Dell          | 0K9T56 A00                  | All in one  | [503d10d676](https://linux-hardware.org/?probe=503d10d676) | Mar 09, 2022 |
| Unknown       | Unknown                     | Notebook    | [23c7cd9c12](https://linux-hardware.org/?probe=23c7cd9c12) | Mar 09, 2022 |
| Dell          | 0K9T56 A00                  | All in one  | [206a6faf1c](https://linux-hardware.org/?probe=206a6faf1c) | Mar 09, 2022 |
| Unknown       | Unknown                     | Notebook    | [dc2ae12852](https://linux-hardware.org/?probe=dc2ae12852) | Mar 07, 2022 |
| Unknown       | Unknown                     | Notebook    | [1b5e705cf1](https://linux-hardware.org/?probe=1b5e705cf1) | Mar 07, 2022 |
| Lenovo        | ThinkPad Edge 0578BBA       | Notebook    | [cf314fb57a](https://linux-hardware.org/?probe=cf314fb57a) | Mar 07, 2022 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [a1b757e234](https://linux-hardware.org/?probe=a1b757e234) | Mar 05, 2022 |
| ASUSTek       | H81M-D                      | Desktop     | [4f6714e804](https://linux-hardware.org/?probe=4f6714e804) | Mar 01, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [809dad2888](https://linux-hardware.org/?probe=809dad2888) | Mar 01, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [70f59ecacf](https://linux-hardware.org/?probe=70f59ecacf) | Feb 28, 2022 |
| ASUSTek       | H81M-D                      | Desktop     | [2bc13ee0e2](https://linux-hardware.org/?probe=2bc13ee0e2) | Feb 28, 2022 |
| ASUSTek       | H81M-D                      | Desktop     | [a8334fb3c3](https://linux-hardware.org/?probe=a8334fb3c3) | Feb 28, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [02ea37a7a8](https://linux-hardware.org/?probe=02ea37a7a8) | Feb 28, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [f269ebd3a2](https://linux-hardware.org/?probe=f269ebd3a2) | Feb 28, 2022 |
| Acer          | AOD270                      | Notebook    | [491fbe6832](https://linux-hardware.org/?probe=491fbe6832) | Feb 21, 2022 |
| Acer          | AOD270                      | Notebook    | [90f9f56240](https://linux-hardware.org/?probe=90f9f56240) | Feb 21, 2022 |
| ASUSTek       | 900                         | Notebook    | [8373f78d4e](https://linux-hardware.org/?probe=8373f78d4e) | Feb 19, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [1e700d65ea](https://linux-hardware.org/?probe=1e700d65ea) | Feb 17, 2022 |
| ASUSTek       | A88XM-PLUS                  | Desktop     | [3a6147e5db](https://linux-hardware.org/?probe=3a6147e5db) | Feb 16, 2022 |
| HP            | Unknown                     | Notebook    | [2f4edd8b04](https://linux-hardware.org/?probe=2f4edd8b04) | Feb 13, 2022 |
| HP            | Unknown                     | Notebook    | [1284e8c58f](https://linux-hardware.org/?probe=1284e8c58f) | Feb 13, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [a25fea3795](https://linux-hardware.org/?probe=a25fea3795) | Feb 12, 2022 |
| Lenovo        | ThinkPad X220 4290MN4       | Notebook    | [c0c3368738](https://linux-hardware.org/?probe=c0c3368738) | Feb 08, 2022 |
| Acer          | Aspire V5-471               | Notebook    | [9bbd70f06c](https://linux-hardware.org/?probe=9bbd70f06c) | Feb 06, 2022 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [da8ce5d5b5](https://linux-hardware.org/?probe=da8ce5d5b5) | Feb 05, 2022 |
| Lenovo        | ThinkPad E480 20KN002YPH    | Notebook    | [c8f0deedbc](https://linux-hardware.org/?probe=c8f0deedbc) | Feb 03, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [ca4c953595](https://linux-hardware.org/?probe=ca4c953595) | Jan 27, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [e01afda31f](https://linux-hardware.org/?probe=e01afda31f) | Jan 22, 2022 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [56bbe3562f](https://linux-hardware.org/?probe=56bbe3562f) | Jan 15, 2022 |
| HP            | Notebook                    | Notebook    | [826345f64e](https://linux-hardware.org/?probe=826345f64e) | Jan 13, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [b04287afb1](https://linux-hardware.org/?probe=b04287afb1) | Jan 11, 2022 |
| Acer          | Aspire A315-41G             | Notebook    | [647b2f2da2](https://linux-hardware.org/?probe=647b2f2da2) | Jan 06, 2022 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [266128f234](https://linux-hardware.org/?probe=266128f234) | Jan 06, 2022 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [900b250e00](https://linux-hardware.org/?probe=900b250e00) | Jan 05, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [d770cc3fe5](https://linux-hardware.org/?probe=d770cc3fe5) | Jan 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | Notebook    | [0cf6f2102c](https://linux-hardware.org/?probe=0cf6f2102c) | Jan 03, 2022 |
| Dell          | Inspiron 5555               | Notebook    | [5f4e7a5f4b](https://linux-hardware.org/?probe=5f4e7a5f4b) | Dec 28, 2021 |
| HP            | Pavilion tx1000             | Notebook    | [a3639ffcd5](https://linux-hardware.org/?probe=a3639ffcd5) | Dec 21, 2021 |
| Unknown       | Unknown                     | Notebook    | [a1b24f9ab7](https://linux-hardware.org/?probe=a1b24f9ab7) | Dec 21, 2021 |
| Unknown       | Unknown                     | Notebook    | [0fb793d2a7](https://linux-hardware.org/?probe=0fb793d2a7) | Dec 21, 2021 |
| Gigabyte      | G41M-Combo                  | Desktop     | [e0b5bc37a4](https://linux-hardware.org/?probe=e0b5bc37a4) | Dec 18, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [60daadb8b0](https://linux-hardware.org/?probe=60daadb8b0) | Dec 18, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [448cdcb300](https://linux-hardware.org/?probe=448cdcb300) | Dec 17, 2021 |
| HP            | Pavilion tx1000             | Notebook    | [e568b07f70](https://linux-hardware.org/?probe=e568b07f70) | Dec 14, 2021 |
| EMAXX TECH... | EMX-A55GT-iCafe V1.0        | Desktop     | [d6d799c3d8](https://linux-hardware.org/?probe=d6d799c3d8) | Nov 28, 2021 |
| Dell          | MXG061                      | Notebook    | [72d7e58977](https://linux-hardware.org/?probe=72d7e58977) | Nov 28, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [31e306a09d](https://linux-hardware.org/?probe=31e306a09d) | Nov 26, 2021 |
| Sony          | SVT13115FGS                 | Notebook    | [a5821de326](https://linux-hardware.org/?probe=a5821de326) | Nov 22, 2021 |
| HP            | ProBook 4730s               | Notebook    | [ffaa64e329](https://linux-hardware.org/?probe=ffaa64e329) | Nov 19, 2021 |
| Acer          | TravelMate P249-G2-M        | Notebook    | [7dbc9e305c](https://linux-hardware.org/?probe=7dbc9e305c) | Nov 11, 2021 |
| Toshiba       | NB255                       | Notebook    | [3c30b0d7ad](https://linux-hardware.org/?probe=3c30b0d7ad) | Nov 09, 2021 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [bfd4d51591](https://linux-hardware.org/?probe=bfd4d51591) | Nov 09, 2021 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [2302fee654](https://linux-hardware.org/?probe=2302fee654) | Nov 09, 2021 |
| MSI           | Z97 GAMING 3                | Desktop     | [249f25308e](https://linux-hardware.org/?probe=249f25308e) | Nov 08, 2021 |
| MSI           | B350M PRO-VDH               | Desktop     | [7e77378fb3](https://linux-hardware.org/?probe=7e77378fb3) | Nov 07, 2021 |
| HP            | Unknown                     | Notebook    | [4ce778dffc](https://linux-hardware.org/?probe=4ce778dffc) | Nov 06, 2021 |
| HP            | Unknown                     | Notebook    | [285c5d9c85](https://linux-hardware.org/?probe=285c5d9c85) | Nov 06, 2021 |
| Acer          | Aspire E5-411               | Notebook    | [0155c64e23](https://linux-hardware.org/?probe=0155c64e23) | Nov 04, 2021 |
| PERSONA       | MYBOOK 14                   | Notebook    | [bf2929c7e3](https://linux-hardware.org/?probe=bf2929c7e3) | Nov 03, 2021 |
| Acer          | Aspire E5-411               | Notebook    | [63287ab4e6](https://linux-hardware.org/?probe=63287ab4e6) | Nov 02, 2021 |
| ECS           | G41T-R3                     | Desktop     | [892069341e](https://linux-hardware.org/?probe=892069341e) | Oct 31, 2021 |
| ASUSTek       | F2A85-M LE                  | Desktop     | [0ac8e061f1](https://linux-hardware.org/?probe=0ac8e061f1) | Oct 31, 2021 |
| ASUSTek       | F2A85-M LE                  | Desktop     | [655000678d](https://linux-hardware.org/?probe=655000678d) | Oct 30, 2021 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [fd3aefd54a](https://linux-hardware.org/?probe=fd3aefd54a) | Oct 27, 2021 |
| Dell          | Vostro 1400                 | Notebook    | [ba2e7123ba](https://linux-hardware.org/?probe=ba2e7123ba) | Oct 24, 2021 |
| Jumper        | EZbook                      | Notebook    | [557738cd7d](https://linux-hardware.org/?probe=557738cd7d) | Oct 23, 2021 |
| HASEE Comp... | HNX4S                       | Notebook    | [aba8e89b9a](https://linux-hardware.org/?probe=aba8e89b9a) | Oct 17, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [ec3329e68a](https://linux-hardware.org/?probe=ec3329e68a) | Oct 17, 2021 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [b8292ace4e](https://linux-hardware.org/?probe=b8292ace4e) | Oct 14, 2021 |
| EMAXX TECH... | EMX-MCP61D3-iCafe V2.0      | Desktop     | [cb279cfeaf](https://linux-hardware.org/?probe=cb279cfeaf) | Oct 09, 2021 |
| EMAXX TECH... | EMX-MCP61D3-iCafe V2.0      | Desktop     | [2444a742a8](https://linux-hardware.org/?probe=2444a742a8) | Oct 09, 2021 |
| HP            | Unknown                     | Notebook    | [c65be179d9](https://linux-hardware.org/?probe=c65be179d9) | Oct 08, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e584636758](https://linux-hardware.org/?probe=e584636758) | Oct 04, 2021 |
| HP            | 14                          | Notebook    | [71ed61e3e0](https://linux-hardware.org/?probe=71ed61e3e0) | Oct 02, 2021 |
| HP            | 14                          | Notebook    | [8fc4fceaa1](https://linux-hardware.org/?probe=8fc4fceaa1) | Oct 02, 2021 |
| HP            | EliteBook 745 G2            | Notebook    | [d80eb2d42c](https://linux-hardware.org/?probe=d80eb2d42c) | Sep 30, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [6e927dafdd](https://linux-hardware.org/?probe=6e927dafdd) | Sep 28, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [ccccaee5bb](https://linux-hardware.org/?probe=ccccaee5bb) | Sep 28, 2021 |
| ASUSTek       | GD30CI                      | Desktop     | [9782c6bff5](https://linux-hardware.org/?probe=9782c6bff5) | Sep 25, 2021 |
| ASUSTek       | EX-H310M-V3 R2.0            | Desktop     | [a9a92c303c](https://linux-hardware.org/?probe=a9a92c303c) | Sep 24, 2021 |
| HP            | G60                         | Notebook    | [36ad0dc4bc](https://linux-hardware.org/?probe=36ad0dc4bc) | Sep 22, 2021 |
| HP            | Unknown                     | Notebook    | [b0b3846ace](https://linux-hardware.org/?probe=b0b3846ace) | Sep 17, 2021 |
| JOOYON        | IPM41-D3G                   | Desktop     | [54cc0ff25b](https://linux-hardware.org/?probe=54cc0ff25b) | Sep 17, 2021 |
| ASUSTek       | X510UQ                      | Notebook    | [ffeab1f23c](https://linux-hardware.org/?probe=ffeab1f23c) | Sep 16, 2021 |
| Toshiba       | Satellite P845              | Notebook    | [27d8557047](https://linux-hardware.org/?probe=27d8557047) | Sep 12, 2021 |
| JOOYON        | IPM41-D3G                   | Desktop     | [4f8d90f8ef](https://linux-hardware.org/?probe=4f8d90f8ef) | Sep 12, 2021 |
| Toshiba       | Satellite C55D-B            | Notebook    | [e9f2b0ceda](https://linux-hardware.org/?probe=e9f2b0ceda) | Sep 11, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [9b620ade68](https://linux-hardware.org/?probe=9b620ade68) | Sep 08, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS            | Desktop     | [f6388fb1b0](https://linux-hardware.org/?probe=f6388fb1b0) | Sep 07, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS            | Desktop     | [a19fc44e26](https://linux-hardware.org/?probe=a19fc44e26) | Sep 07, 2021 |
| Dell          | Latitude E7450              | Notebook    | [531e888c8b](https://linux-hardware.org/?probe=531e888c8b) | Sep 04, 2021 |
| Lenovo        | ThinkPad X220 42863MJ       | Notebook    | [68cbfb3edb](https://linux-hardware.org/?probe=68cbfb3edb) | Sep 04, 2021 |
| Cubix         | Morph                       | Notebook    | [ffc9d93c9b](https://linux-hardware.org/?probe=ffc9d93c9b) | Aug 30, 2021 |
| Gigabyte      | F2A58M-DS2                  | Desktop     | [8ea19cfa9d](https://linux-hardware.org/?probe=8ea19cfa9d) | Aug 25, 2021 |
| Gigabyte      | Q2006                       | Notebook    | [754a3fc1b5](https://linux-hardware.org/?probe=754a3fc1b5) | Aug 23, 2021 |
| Gigabyte      | Q2006                       | Notebook    | [a384b10b00](https://linux-hardware.org/?probe=a384b10b00) | Aug 23, 2021 |
| Lenovo        | IdeaPadFlex 14 20308        | Notebook    | [54f7c9deec](https://linux-hardware.org/?probe=54f7c9deec) | Aug 14, 2021 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [07f3a8a2c9](https://linux-hardware.org/?probe=07f3a8a2c9) | Aug 13, 2021 |
| Acer          | Aspire V3-772G              | Notebook    | [58d92680bb](https://linux-hardware.org/?probe=58d92680bb) | Aug 13, 2021 |
| Unknown       | Ionics Carrier Board Adv... | Desktop     | [62a47a18c2](https://linux-hardware.org/?probe=62a47a18c2) | Aug 12, 2021 |
| Apple         | MacBookAir4,1               | Notebook    | [cc00e74712](https://linux-hardware.org/?probe=cc00e74712) | Aug 09, 2021 |
| ECS           | H81H3-M4                    | Desktop     | [a595ba80d3](https://linux-hardware.org/?probe=a595ba80d3) | Aug 08, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [90e7e1e008](https://linux-hardware.org/?probe=90e7e1e008) | Aug 05, 2021 |
| ASRock        | N68C-GS4 FX                 | Desktop     | [4bf2729f88](https://linux-hardware.org/?probe=4bf2729f88) | Aug 04, 2021 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [57f0c24236](https://linux-hardware.org/?probe=57f0c24236) | Aug 03, 2021 |
| Toshiba       | Satellite C650              | Notebook    | [3b5f090e84](https://linux-hardware.org/?probe=3b5f090e84) | Aug 01, 2021 |
| Gigabyte      | MZGLKCP-00                  | Desktop     | [4d9f134679](https://linux-hardware.org/?probe=4d9f134679) | Jul 30, 2021 |
| Biostar       | H110MHV3                    | Desktop     | [28344398db](https://linux-hardware.org/?probe=28344398db) | Jul 27, 2021 |
| Acer          | Aspire E3-111               | Notebook    | [29d6febd6e](https://linux-hardware.org/?probe=29d6febd6e) | Jul 24, 2021 |
| Acer          | Aspire E3-111               | Notebook    | [f9c8b1d3ff](https://linux-hardware.org/?probe=f9c8b1d3ff) | Jul 24, 2021 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [9576a81942](https://linux-hardware.org/?probe=9576a81942) | Jul 23, 2021 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [d86a6d7c9a](https://linux-hardware.org/?probe=d86a6d7c9a) | Jul 23, 2021 |
| Acer          | Aspire E5-551G              | Notebook    | [519515ce84](https://linux-hardware.org/?probe=519515ce84) | Jul 15, 2021 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [a5daecad1d](https://linux-hardware.org/?probe=a5daecad1d) | Jul 15, 2021 |
| Dell          | Inspiron 7373               | Convertible | [5514ed070a](https://linux-hardware.org/?probe=5514ed070a) | Jul 14, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [2151a0b75d](https://linux-hardware.org/?probe=2151a0b75d) | Jul 13, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [8165fc4d95](https://linux-hardware.org/?probe=8165fc4d95) | Jul 06, 2021 |
| Lenovo        | ThinkPad X220 4291LL6       | Notebook    | [3e8ed9be02](https://linux-hardware.org/?probe=3e8ed9be02) | Jul 02, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [ceedeef480](https://linux-hardware.org/?probe=ceedeef480) | Jul 01, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [63055a9c60](https://linux-hardware.org/?probe=63055a9c60) | Jun 29, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [5e0e7e2b80](https://linux-hardware.org/?probe=5e0e7e2b80) | Jun 25, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [00ef418c43](https://linux-hardware.org/?probe=00ef418c43) | Jun 24, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [ca6df82553](https://linux-hardware.org/?probe=ca6df82553) | Jun 22, 2021 |
| Biostar       | A320MH                      | Desktop     | [16e2552ccc](https://linux-hardware.org/?probe=16e2552ccc) | Jun 20, 2021 |
| Lenovo        | ThinkPad X220 4291LR8       | Notebook    | [69031eda12](https://linux-hardware.org/?probe=69031eda12) | Jun 18, 2021 |
| Lenovo        | ThinkPad X220 4291LR8       | Notebook    | [d7b3c8fc20](https://linux-hardware.org/?probe=d7b3c8fc20) | Jun 18, 2021 |
| Lenovo        | ThinkPad L530 24811K2       | Notebook    | [3517541065](https://linux-hardware.org/?probe=3517541065) | Jun 11, 2021 |
| Dell          | 040DDP A01                  | Desktop     | [8a9bdad1fd](https://linux-hardware.org/?probe=8a9bdad1fd) | Jun 10, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [cc3c9e3798](https://linux-hardware.org/?probe=cc3c9e3798) | Jun 08, 2021 |
| MSI           | A68HM-E33 V2                | Desktop     | [10ccc894a1](https://linux-hardware.org/?probe=10ccc894a1) | Jun 07, 2021 |
| Toshiba       | Satellite L515              | Notebook    | [72858b36e6](https://linux-hardware.org/?probe=72858b36e6) | Jun 02, 2021 |
| HP            | 82A5                        | Mini pc     | [08b98b6a88](https://linux-hardware.org/?probe=08b98b6a88) | May 29, 2021 |
| NEC Comput... | PC-VK25MXZCB                | Notebook    | [0a1b7b959f](https://linux-hardware.org/?probe=0a1b7b959f) | May 24, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [e31519274b](https://linux-hardware.org/?probe=e31519274b) | May 22, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [523ced455c](https://linux-hardware.org/?probe=523ced455c) | May 22, 2021 |
| Acer          | Aspire X1900                | Desktop     | [c4e0203ed9](https://linux-hardware.org/?probe=c4e0203ed9) | May 19, 2021 |
| MSI           | A68HM-E33 V2                | Desktop     | [a14cf2a48e](https://linux-hardware.org/?probe=a14cf2a48e) | May 18, 2021 |
| Dell          | Inspiron 7373               | Convertible | [e4ffc93c6a](https://linux-hardware.org/?probe=e4ffc93c6a) | May 16, 2021 |
| Lenovo        | ThinkPad E15 20RES0GF00     | Notebook    | [8722c3498e](https://linux-hardware.org/?probe=8722c3498e) | May 14, 2021 |
| Acer          | Aspire 4750                 | Notebook    | [5f6a294b7d](https://linux-hardware.org/?probe=5f6a294b7d) | May 12, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [ac4ce770fc](https://linux-hardware.org/?probe=ac4ce770fc) | May 10, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [cbe08b6f59](https://linux-hardware.org/?probe=cbe08b6f59) | May 09, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [b2e6deb92e](https://linux-hardware.org/?probe=b2e6deb92e) | May 09, 2021 |
| ASUSTek       | X450MD                      | Notebook    | [b77e4abcd8](https://linux-hardware.org/?probe=b77e4abcd8) | May 06, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [8467906058](https://linux-hardware.org/?probe=8467906058) | May 04, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [55bfc7d608](https://linux-hardware.org/?probe=55bfc7d608) | May 03, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [bb346e5b0c](https://linux-hardware.org/?probe=bb346e5b0c) | Apr 26, 2021 |
| ASUSTek       | EX-B365M-V5                 | Desktop     | [c169d54571](https://linux-hardware.org/?probe=c169d54571) | Apr 25, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [ff01911cb6](https://linux-hardware.org/?probe=ff01911cb6) | Apr 22, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [b866ec6925](https://linux-hardware.org/?probe=b866ec6925) | Apr 20, 2021 |
| Acer          | Aspire ES1-132              | Notebook    | [2e91d0c330](https://linux-hardware.org/?probe=2e91d0c330) | Apr 20, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [f8a3bc6b1d](https://linux-hardware.org/?probe=f8a3bc6b1d) | Apr 19, 2021 |
| Acer          | Nitro AN715-51              | Notebook    | [1cd3975ffa](https://linux-hardware.org/?probe=1cd3975ffa) | Apr 16, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [ef9ba18b59](https://linux-hardware.org/?probe=ef9ba18b59) | Apr 11, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [f66e7cbdfd](https://linux-hardware.org/?probe=f66e7cbdfd) | Apr 11, 2021 |
| HP            | Notebook                    | Notebook    | [023066c915](https://linux-hardware.org/?probe=023066c915) | Apr 08, 2021 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [b11b4274e4](https://linux-hardware.org/?probe=b11b4274e4) | Apr 08, 2021 |
| Dell          | OptiPlex 9010 AIO           | All in one  | [23fdbd4caa](https://linux-hardware.org/?probe=23fdbd4caa) | Apr 08, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YD      | Notebook    | [2870ee333f](https://linux-hardware.org/?probe=2870ee333f) | Apr 07, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YD      | Notebook    | [43b581a270](https://linux-hardware.org/?probe=43b581a270) | Apr 07, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [d1b688c0a9](https://linux-hardware.org/?probe=d1b688c0a9) | Mar 31, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [40b47343b7](https://linux-hardware.org/?probe=40b47343b7) | Mar 28, 2021 |
| Notebook      | NH5x_7xDCx_DDx              | Notebook    | [4f1b6f18bf](https://linux-hardware.org/?probe=4f1b6f18bf) | Mar 26, 2021 |
| Notebook      | NH5x_7xDCx_DDx              | Notebook    | [aec0de9a30](https://linux-hardware.org/?probe=aec0de9a30) | Mar 26, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [4c93424ea5](https://linux-hardware.org/?probe=4c93424ea5) | Mar 26, 2021 |
| Acer          | TravelMate B117-M           | Notebook    | [c205b164c5](https://linux-hardware.org/?probe=c205b164c5) | Mar 26, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [53f5f073d5](https://linux-hardware.org/?probe=53f5f073d5) | Mar 18, 2021 |
| MSI           | Z270 GAMING M7              | Desktop     | [b72439b299](https://linux-hardware.org/?probe=b72439b299) | Mar 17, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [d9ec96bf45](https://linux-hardware.org/?probe=d9ec96bf45) | Mar 15, 2021 |
| Gigabyte      | GA-MA78GM-US2H              | Desktop     | [0f6037a19e](https://linux-hardware.org/?probe=0f6037a19e) | Mar 14, 2021 |
| HP            | Pavilion Laptop 15-cc0xx    | Notebook    | [4b98fb1e80](https://linux-hardware.org/?probe=4b98fb1e80) | Mar 13, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [42dd14b17d](https://linux-hardware.org/?probe=42dd14b17d) | Mar 09, 2021 |
| MSI           | CX62 7QL                    | Notebook    | [8241c594e5](https://linux-hardware.org/?probe=8241c594e5) | Mar 07, 2021 |
| eMachines     | eM250                       | Notebook    | [e20e648698](https://linux-hardware.org/?probe=e20e648698) | Mar 04, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [ec866fbb40](https://linux-hardware.org/?probe=ec866fbb40) | Mar 04, 2021 |
| Lenovo        | ThinkPad T430 2349PS9       | Notebook    | [4f805206d4](https://linux-hardware.org/?probe=4f805206d4) | Mar 03, 2021 |
| Acer          | TravelMate B115-M           | Notebook    | [46b6080608](https://linux-hardware.org/?probe=46b6080608) | Mar 02, 2021 |
| Acer          | TravelMate B115-M           | Notebook    | [4567b99e4e](https://linux-hardware.org/?probe=4567b99e4e) | Mar 02, 2021 |
| HP            | 82A5                        | Mini pc     | [fa16fba963](https://linux-hardware.org/?probe=fa16fba963) | Feb 28, 2021 |
| MSI           | Z97 XPOWER AC               | Desktop     | [c627833398](https://linux-hardware.org/?probe=c627833398) | Feb 23, 2021 |
| Acer          | TravelMate B113             | Notebook    | [5ff9f9bb03](https://linux-hardware.org/?probe=5ff9f9bb03) | Feb 23, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [3582928f83](https://linux-hardware.org/?probe=3582928f83) | Feb 20, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [d392637e95](https://linux-hardware.org/?probe=d392637e95) | Feb 20, 2021 |
| Lenovo        | G450 20022                  | Notebook    | [a98aa9041e](https://linux-hardware.org/?probe=a98aa9041e) | Feb 17, 2021 |
| Sony          | VPCEA36FA                   | Notebook    | [050c395bd5](https://linux-hardware.org/?probe=050c395bd5) | Feb 16, 2021 |
| Lenovo        | ThinkPad L530 24812K6       | Notebook    | [d78f3099e4](https://linux-hardware.org/?probe=d78f3099e4) | Feb 14, 2021 |
| AMD           | A88                         | Desktop     | [11ecb6d298](https://linux-hardware.org/?probe=11ecb6d298) | Feb 14, 2021 |
| Dell          | 0JP3NX A00                  | Desktop     | [3e5d4f837a](https://linux-hardware.org/?probe=3e5d4f837a) | Feb 10, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [8b736da7f7](https://linux-hardware.org/?probe=8b736da7f7) | Feb 09, 2021 |
| JOOYON        | IPM41-D3G                   | Desktop     | [6feab903f8](https://linux-hardware.org/?probe=6feab903f8) | Feb 05, 2021 |
| JOOYON        | IPM41-D3G                   | Desktop     | [5fa1dabba9](https://linux-hardware.org/?probe=5fa1dabba9) | Feb 05, 2021 |
| Acer          | TravelMate B113             | Notebook    | [7e439b847d](https://linux-hardware.org/?probe=7e439b847d) | Feb 04, 2021 |
| Dell          | 0JP3NX A00                  | Desktop     | [1f5d53a4a2](https://linux-hardware.org/?probe=1f5d53a4a2) | Feb 03, 2021 |
| QTQD          | Unknown                     | Desktop     | [2912607416](https://linux-hardware.org/?probe=2912607416) | Jan 27, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YD      | Notebook    | [4c9b44d2d4](https://linux-hardware.org/?probe=4c9b44d2d4) | Jan 26, 2021 |
| Gigabyte      | H97M-D3H                    | Desktop     | [76f0201d14](https://linux-hardware.org/?probe=76f0201d14) | Jan 26, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [795b4f4c7b](https://linux-hardware.org/?probe=795b4f4c7b) | Jan 26, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [6e4545c96a](https://linux-hardware.org/?probe=6e4545c96a) | Jan 23, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [603bb5d8e4](https://linux-hardware.org/?probe=603bb5d8e4) | Jan 22, 2021 |
| ASUSTek       | H81M-C                      | Desktop     | [c108942b4e](https://linux-hardware.org/?probe=c108942b4e) | Jan 19, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [9d8720f796](https://linux-hardware.org/?probe=9d8720f796) | Jan 19, 2021 |
| Acer          | Aspire X1900                | Desktop     | [d0a0250e62](https://linux-hardware.org/?probe=d0a0250e62) | Jan 15, 2021 |
| Acer          | Aspire ES1-132              | Notebook    | [1e55ffedfe](https://linux-hardware.org/?probe=1e55ffedfe) | Jan 15, 2021 |
| Acer          | Aspire ES1-132              | Notebook    | [6f9868755e](https://linux-hardware.org/?probe=6f9868755e) | Jan 15, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [15b8546bd4](https://linux-hardware.org/?probe=15b8546bd4) | Jan 11, 2021 |
| Gigabyte      | AM1M-S2P                    | Desktop     | [433295603d](https://linux-hardware.org/?probe=433295603d) | Jan 09, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [3f75d5f2e1](https://linux-hardware.org/?probe=3f75d5f2e1) | Jan 07, 2021 |
| Gigabyte      | Z370M D3H-CF                | Desktop     | [e6533b7b24](https://linux-hardware.org/?probe=e6533b7b24) | Jan 07, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [91ccfb9b5a](https://linux-hardware.org/?probe=91ccfb9b5a) | Jan 06, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [b5fa895a91](https://linux-hardware.org/?probe=b5fa895a91) | Jan 05, 2021 |
| MSI           | A320M PRO-VD/S V2           | Desktop     | [5d05e8d607](https://linux-hardware.org/?probe=5d05e8d607) | Jan 04, 2021 |
| Toshiba       | dynabook R73/W              | Notebook    | [b84a72cace](https://linux-hardware.org/?probe=b84a72cace) | Jan 02, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [031ad52398](https://linux-hardware.org/?probe=031ad52398) | Jan 01, 2021 |
| ASUSTek       | EX-H310M-V3 R2.0            | Desktop     | [11a5fd5bae](https://linux-hardware.org/?probe=11a5fd5bae) | Dec 30, 2020 |
| MSI           | IONA                        | Desktop     | [bfb84589dd](https://linux-hardware.org/?probe=bfb84589dd) | Dec 28, 2020 |
| MSI           | IONA                        | Desktop     | [0ec5c79eb8](https://linux-hardware.org/?probe=0ec5c79eb8) | Dec 26, 2020 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [459afa05c1](https://linux-hardware.org/?probe=459afa05c1) | Dec 26, 2020 |
| ECS           | H110M-C3D/C3V               | Desktop     | [aa44a6674f](https://linux-hardware.org/?probe=aa44a6674f) | Dec 23, 2020 |
| ASRock        | N68-S3                      | Desktop     | [bfa6bd97d5](https://linux-hardware.org/?probe=bfa6bd97d5) | Dec 23, 2020 |
| MSI           | MS-7541                     | Desktop     | [a6e134920c](https://linux-hardware.org/?probe=a6e134920c) | Dec 22, 2020 |
| MSI           | MS-7541                     | Desktop     | [a44769cfd2](https://linux-hardware.org/?probe=a44769cfd2) | Dec 22, 2020 |
| HP            | ZBook Create G7 Notebook... | Notebook    | [e40ffb436c](https://linux-hardware.org/?probe=e40ffb436c) | Dec 20, 2020 |
| HP            | ZBook Create G7 Notebook... | Notebook    | [b1a2ee65e0](https://linux-hardware.org/?probe=b1a2ee65e0) | Dec 20, 2020 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [d186067403](https://linux-hardware.org/?probe=d186067403) | Dec 17, 2020 |
| ASRock        | N68-S3                      | Desktop     | [1d3067d8cb](https://linux-hardware.org/?probe=1d3067d8cb) | Dec 17, 2020 |
| Acer          | Aspire ES1-431              | Notebook    | [6a99509d25](https://linux-hardware.org/?probe=6a99509d25) | Dec 16, 2020 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [e315898f10](https://linux-hardware.org/?probe=e315898f10) | Dec 16, 2020 |
| Toshiba       | dynabook R73/W              | Notebook    | [96710da884](https://linux-hardware.org/?probe=96710da884) | Dec 14, 2020 |
| Intel         | NUC10i3FNB K61362-303       | Mini pc     | [d942ed05b5](https://linux-hardware.org/?probe=d942ed05b5) | Dec 13, 2020 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [db8ffa8342](https://linux-hardware.org/?probe=db8ffa8342) | Dec 06, 2020 |
| HP            | 8061                        | Desktop     | [0f0bc8b49a](https://linux-hardware.org/?probe=0f0bc8b49a) | Dec 04, 2020 |
| HP            | 8061                        | Desktop     | [a63c8237f1](https://linux-hardware.org/?probe=a63c8237f1) | Dec 04, 2020 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [2a35d394f9](https://linux-hardware.org/?probe=2a35d394f9) | Dec 04, 2020 |
| NEC Comput... | IS8XM                       | Desktop     | [57afeee773](https://linux-hardware.org/?probe=57afeee773) | Nov 30, 2020 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | Notebook    | [4dd4445d4d](https://linux-hardware.org/?probe=4dd4445d4d) | Nov 29, 2020 |
| Acer          | Aspire A315-53G             | Notebook    | [9498233954](https://linux-hardware.org/?probe=9498233954) | Nov 26, 2020 |
| eMachines     | eM350                       | Notebook    | [2bafdd62aa](https://linux-hardware.org/?probe=2bafdd62aa) | Nov 23, 2020 |
| eMachines     | eM350                       | Notebook    | [03b9a0de29](https://linux-hardware.org/?probe=03b9a0de29) | Nov 23, 2020 |
| Apple         | MacBookPro5,5               | Notebook    | [d63213adad](https://linux-hardware.org/?probe=d63213adad) | Nov 22, 2020 |
| ASUSTek       | K43SD                       | Notebook    | [869c3395e8](https://linux-hardware.org/?probe=869c3395e8) | Nov 20, 2020 |
| ASUSTek       | K43SD                       | Notebook    | [3ce330e163](https://linux-hardware.org/?probe=3ce330e163) | Nov 19, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | Desktop     | [354202e98e](https://linux-hardware.org/?probe=354202e98e) | Nov 19, 2020 |
| HP            | Unknown                     | Notebook    | [b525a6fdd2](https://linux-hardware.org/?probe=b525a6fdd2) | Nov 15, 2020 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [f86e0d2af5](https://linux-hardware.org/?probe=f86e0d2af5) | Nov 11, 2020 |
| HP            | 3031h                       | Desktop     | [fb54f48959](https://linux-hardware.org/?probe=fb54f48959) | Nov 10, 2020 |
| HP            | 8061                        | Desktop     | [7936b223e9](https://linux-hardware.org/?probe=7936b223e9) | Nov 10, 2020 |
| ASUSTek       | B85M-G                      | Desktop     | [2c9a8f0838](https://linux-hardware.org/?probe=2c9a8f0838) | Nov 08, 2020 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [c812c2b6f9](https://linux-hardware.org/?probe=c812c2b6f9) | Nov 07, 2020 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [e21be2124d](https://linux-hardware.org/?probe=e21be2124d) | Nov 04, 2020 |
| ASUSTek       | X540NA                      | Notebook    | [7c1cb4cac0](https://linux-hardware.org/?probe=7c1cb4cac0) | Nov 02, 2020 |
| HP            | 8061                        | Desktop     | [d11b92ef18](https://linux-hardware.org/?probe=d11b92ef18) | Nov 01, 2020 |
| Gigabyte      | H81M-DS2                    | Desktop     | [a3cdedf351](https://linux-hardware.org/?probe=a3cdedf351) | Oct 30, 2020 |
| Lenovo        | ThinkPad X220 4290MN4       | Notebook    | [f305f22059](https://linux-hardware.org/?probe=f305f22059) | Oct 29, 2020 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [80d72786c1](https://linux-hardware.org/?probe=80d72786c1) | Oct 26, 2020 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [3919d06624](https://linux-hardware.org/?probe=3919d06624) | Oct 25, 2020 |
| Acer          | Aspire SW3-016              | Notebook    | [e110233803](https://linux-hardware.org/?probe=e110233803) | Oct 24, 2020 |
| Acer          | Aspire ES1-132              | Notebook    | [ecf79444ac](https://linux-hardware.org/?probe=ecf79444ac) | Oct 21, 2020 |
| Pegatron      | IPMSB-H61                   | Desktop     | [c569d86fff](https://linux-hardware.org/?probe=c569d86fff) | Oct 19, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [bfe2deec18](https://linux-hardware.org/?probe=bfe2deec18) | Oct 17, 2020 |
| Acer          | Aspire SW3-016              | Notebook    | [2f0952fbb5](https://linux-hardware.org/?probe=2f0952fbb5) | Oct 15, 2020 |
| HP            | 8061                        | Desktop     | [b2cf684801](https://linux-hardware.org/?probe=b2cf684801) | Oct 13, 2020 |
| Lenovo        | ThinkPad X260 20F5S04206    | Notebook    | [147c40fe70](https://linux-hardware.org/?probe=147c40fe70) | Oct 12, 2020 |
| HP            | Notebook                    | Notebook    | [8cbf9133f7](https://linux-hardware.org/?probe=8cbf9133f7) | Oct 11, 2020 |
| MSI           | MAG B550M MORTAR            | Desktop     | [653a4a9f6e](https://linux-hardware.org/?probe=653a4a9f6e) | Oct 11, 2020 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [9c83568b79](https://linux-hardware.org/?probe=9c83568b79) | Oct 07, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [0053b1ef76](https://linux-hardware.org/?probe=0053b1ef76) | Oct 07, 2020 |
| HP            | 15                          | Notebook    | [c44a5eaea1](https://linux-hardware.org/?probe=c44a5eaea1) | Oct 07, 2020 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [11b8e32835](https://linux-hardware.org/?probe=11b8e32835) | Oct 06, 2020 |
| Lenovo        | ThinkPad X230 2325CTO       | Notebook    | [c1812f8ee0](https://linux-hardware.org/?probe=c1812f8ee0) | Oct 05, 2020 |
| Lenovo        | ThinkPad X230 2325CTO       | Notebook    | [4e98739f72](https://linux-hardware.org/?probe=4e98739f72) | Oct 05, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [73fd7565f6](https://linux-hardware.org/?probe=73fd7565f6) | Oct 05, 2020 |
| Unknown       | Generic RK322x TV Box       | Mini pc     | [2d6256e8c5](https://linux-hardware.org/?probe=2d6256e8c5) | Oct 05, 2020 |
| ASUSTek       | X540NA                      | Notebook    | [a2cee62097](https://linux-hardware.org/?probe=a2cee62097) | Oct 02, 2020 |
| Acer          | Aspire A314-32              | Notebook    | [a51d2f268d](https://linux-hardware.org/?probe=a51d2f268d) | Oct 02, 2020 |
| HP            | Pavilion Laptop 15-cc0xx    | Notebook    | [a8678813c5](https://linux-hardware.org/?probe=a8678813c5) | Oct 01, 2020 |
| ASUSTek       | K75DE                       | Notebook    | [b4cb493794](https://linux-hardware.org/?probe=b4cb493794) | Sep 28, 2020 |
| Dell          | OptiPlex 9010 AIO           | All in one  | [074fb7cc02](https://linux-hardware.org/?probe=074fb7cc02) | Sep 28, 2020 |
| MSI           | A88XM-E35                   | Desktop     | [32556e96bf](https://linux-hardware.org/?probe=32556e96bf) | Sep 27, 2020 |
| MSI           | A88XM-E35                   | Desktop     | [7176092b12](https://linux-hardware.org/?probe=7176092b12) | Sep 27, 2020 |
| HP            | 8061                        | Desktop     | [1d3e0a6b3d](https://linux-hardware.org/?probe=1d3e0a6b3d) | Sep 25, 2020 |
| Dell          | OptiPlex 9010 AIO           | All in one  | [bf1e06fe4f](https://linux-hardware.org/?probe=bf1e06fe4f) | Sep 23, 2020 |
| Dell          | OptiPlex 9010 AIO           | All in one  | [337ba51577](https://linux-hardware.org/?probe=337ba51577) | Sep 23, 2020 |
| ASUSTek       | TUF Gaming FA506IV_FA506... | Notebook    | [72f627fd0e](https://linux-hardware.org/?probe=72f627fd0e) | Sep 21, 2020 |
| Apple         | MacBookAir3,1               | Notebook    | [73e9128968](https://linux-hardware.org/?probe=73e9128968) | Sep 21, 2020 |
| Fujitsu       | FMVA05008                   | Notebook    | [36816f2b18](https://linux-hardware.org/?probe=36816f2b18) | Sep 18, 2020 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [546b3fec83](https://linux-hardware.org/?probe=546b3fec83) | Sep 16, 2020 |
| Lenovo        | V110-14IAP 80TF             | Notebook    | [f0ac65615d](https://linux-hardware.org/?probe=f0ac65615d) | Sep 14, 2020 |
| Lenovo        | V110-14IAP 80TF             | Notebook    | [5acf002102](https://linux-hardware.org/?probe=5acf002102) | Sep 14, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [1cf35a6180](https://linux-hardware.org/?probe=1cf35a6180) | Sep 13, 2020 |
| Lenovo        | V110-14IAP 80TF             | Notebook    | [d2fde2a21e](https://linux-hardware.org/?probe=d2fde2a21e) | Sep 13, 2020 |
| MSI           | CX61 0NC/CX61 0ND/CX61 0... | Notebook    | [5a3c4a23bb](https://linux-hardware.org/?probe=5a3c4a23bb) | Sep 12, 2020 |
| ASUSTek       | X441URK                     | Notebook    | [f883ed5e4b](https://linux-hardware.org/?probe=f883ed5e4b) | Sep 12, 2020 |
| Dell          | OptiPlex 9010 AIO           | All in one  | [a2e7991749](https://linux-hardware.org/?probe=a2e7991749) | Sep 11, 2020 |
| Dell          | Latitude E4300              | Notebook    | [8b163ddf1e](https://linux-hardware.org/?probe=8b163ddf1e) | Sep 09, 2020 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [eaff730455](https://linux-hardware.org/?probe=eaff730455) | Sep 09, 2020 |
| Apple         | MacBookAir2,1               | Notebook    | [c4b26d8019](https://linux-hardware.org/?probe=c4b26d8019) | Sep 08, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [809af585ab](https://linux-hardware.org/?probe=809af585ab) | Sep 08, 2020 |
| Lenovo        | ThinkPad E580 20KSA00UAU    | Notebook    | [becbbe530b](https://linux-hardware.org/?probe=becbbe530b) | Sep 07, 2020 |
| Acer          | Aspire 4752                 | Notebook    | [9c779dc588](https://linux-hardware.org/?probe=9c779dc588) | Sep 04, 2020 |
| Acer          | Aspire 4752                 | Notebook    | [efeb5dd920](https://linux-hardware.org/?probe=efeb5dd920) | Sep 04, 2020 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [9557e9d02c](https://linux-hardware.org/?probe=9557e9d02c) | Sep 04, 2020 |
| Acer          | Aspire A315-41G             | Notebook    | [ec1a232ba9](https://linux-hardware.org/?probe=ec1a232ba9) | Sep 03, 2020 |
| Acer          | Aspire A315-41G             | Notebook    | [3cff1527be](https://linux-hardware.org/?probe=3cff1527be) | Sep 03, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [0fda90e55c](https://linux-hardware.org/?probe=0fda90e55c) | Sep 03, 2020 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | Notebook    | [4a5f93ed76](https://linux-hardware.org/?probe=4a5f93ed76) | Sep 03, 2020 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | Notebook    | [e11793b02c](https://linux-hardware.org/?probe=e11793b02c) | Sep 02, 2020 |
| ASUSTek       | X441URK                     | Notebook    | [35b06d497e](https://linux-hardware.org/?probe=35b06d497e) | Sep 02, 2020 |
| Clevo         | M7x0S                       | Notebook    | [100fc7862e](https://linux-hardware.org/?probe=100fc7862e) | Sep 02, 2020 |
| Clevo         | M7x0S                       | Notebook    | [6d9f5403eb](https://linux-hardware.org/?probe=6d9f5403eb) | Sep 02, 2020 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [288f4f772c](https://linux-hardware.org/?probe=288f4f772c) | Sep 01, 2020 |
| Lenovo        | IdeaPad Z460 20059          | Notebook    | [9568d009c0](https://linux-hardware.org/?probe=9568d009c0) | Sep 01, 2020 |
| Lenovo        | ThinkPad X240 20AMS0SA0J    | Notebook    | [5e85d0fa0e](https://linux-hardware.org/?probe=5e85d0fa0e) | Aug 31, 2020 |
| Clevo         | M7x0S                       | Notebook    | [7efc902d33](https://linux-hardware.org/?probe=7efc902d33) | Aug 31, 2020 |
| Clevo         | M7x0S                       | Notebook    | [58b7846f61](https://linux-hardware.org/?probe=58b7846f61) | Aug 30, 2020 |
| Dell          | Latitude E7450              | Notebook    | [7b6b25e684](https://linux-hardware.org/?probe=7b6b25e684) | Aug 27, 2020 |
| Acer          | Swift SF314-41              | Notebook    | [290159761f](https://linux-hardware.org/?probe=290159761f) | Aug 27, 2020 |
| HP            | Pavilion g4                 | Notebook    | [55dec82070](https://linux-hardware.org/?probe=55dec82070) | Aug 26, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [de3f00fc50](https://linux-hardware.org/?probe=de3f00fc50) | Aug 26, 2020 |
| ASUSTek       | X540NA                      | Notebook    | [8747f9eb75](https://linux-hardware.org/?probe=8747f9eb75) | Aug 22, 2020 |
| ASUSTek       | X540NA                      | Notebook    | [b1d91b9932](https://linux-hardware.org/?probe=b1d91b9932) | Aug 21, 2020 |
| Biostar       | H81MHV3                     | Desktop     | [ecd87de5e0](https://linux-hardware.org/?probe=ecd87de5e0) | Aug 21, 2020 |
| Sony          | SVF14216SGP                 | Notebook    | [31495e375f](https://linux-hardware.org/?probe=31495e375f) | Aug 19, 2020 |
| Dell          | 0VRWRC A00                  | Desktop     | [b5e17b6229](https://linux-hardware.org/?probe=b5e17b6229) | Aug 16, 2020 |
| HP            | Pavilion dv6000 (RU700UA... | Notebook    | [56702de7d4](https://linux-hardware.org/?probe=56702de7d4) | Aug 15, 2020 |
| HP            | Pavilion dv6000 (RU700UA... | Notebook    | [d868e4a7f9](https://linux-hardware.org/?probe=d868e4a7f9) | Aug 15, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [eed0bce682](https://linux-hardware.org/?probe=eed0bce682) | Aug 14, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [532d54162a](https://linux-hardware.org/?probe=532d54162a) | Aug 14, 2020 |
| Lenovo        | ThinkPad T400 2768CC1       | Notebook    | [a5e0d02669](https://linux-hardware.org/?probe=a5e0d02669) | Aug 12, 2020 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [6b5b2287e0](https://linux-hardware.org/?probe=6b5b2287e0) | Aug 07, 2020 |
| Lenovo        | ThinkPad T400 2768CC1       | Notebook    | [aa6089eda7](https://linux-hardware.org/?probe=aa6089eda7) | Aug 06, 2020 |
| Lenovo        | ThinkPad T400 2768CC1       | Notebook    | [86ee9f7736](https://linux-hardware.org/?probe=86ee9f7736) | Aug 06, 2020 |
| MSI           | GV62 8RD                    | Notebook    | [0b6cd63268](https://linux-hardware.org/?probe=0b6cd63268) | Aug 04, 2020 |
| HP            | Pavilion g4                 | Notebook    | [4fc16d6e09](https://linux-hardware.org/?probe=4fc16d6e09) | Aug 02, 2020 |
| HP            | Pavilion g4                 | Notebook    | [0b9fc56cd1](https://linux-hardware.org/?probe=0b9fc56cd1) | Aug 02, 2020 |
| HP            | 805D                        | Desktop     | [b0f200fe77](https://linux-hardware.org/?probe=b0f200fe77) | Jul 29, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [3fd417f684](https://linux-hardware.org/?probe=3fd417f684) | Jul 29, 2020 |
| Acer          | Aspire ES1-521              | Notebook    | [64a762e6b8](https://linux-hardware.org/?probe=64a762e6b8) | Jul 26, 2020 |
| HP            | Notebook                    | Notebook    | [7dd7f12bb9](https://linux-hardware.org/?probe=7dd7f12bb9) | Jul 25, 2020 |
| HP            | Notebook                    | Notebook    | [55ab6c06c5](https://linux-hardware.org/?probe=55ab6c06c5) | Jul 25, 2020 |
| Acer          | Aspire ES1-521              | Notebook    | [23d8c2d2cf](https://linux-hardware.org/?probe=23d8c2d2cf) | Jul 25, 2020 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [ca9dc81053](https://linux-hardware.org/?probe=ca9dc81053) | Jul 25, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80YD      | Notebook    | [d486d4bc03](https://linux-hardware.org/?probe=d486d4bc03) | Jul 24, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80YD      | Notebook    | [f12d8d16e5](https://linux-hardware.org/?probe=f12d8d16e5) | Jul 16, 2020 |
| Acer          | Aspire ES1-132              | Notebook    | [d1bc3c3a8a](https://linux-hardware.org/?probe=d1bc3c3a8a) | Jul 10, 2020 |
| Acer          | Aspire ES1-132              | Notebook    | [cb26f9925f](https://linux-hardware.org/?probe=cb26f9925f) | Jul 09, 2020 |
| ASUSTek       | X540NA                      | Notebook    | [2e3aac14fe](https://linux-hardware.org/?probe=2e3aac14fe) | Jul 02, 2020 |
| Acer          | Aspire V5-431               | Notebook    | [0287b85983](https://linux-hardware.org/?probe=0287b85983) | Jun 30, 2020 |
| Lenovo        | ThinkPad T530 2429HC3       | Notebook    | [fb0a45d925](https://linux-hardware.org/?probe=fb0a45d925) | Jun 27, 2020 |
| Lenovo        | ThinkPad T530 2429HC3       | Notebook    | [99e750162d](https://linux-hardware.org/?probe=99e750162d) | Jun 27, 2020 |
| eMachines     | eM350                       | Notebook    | [b699bf9fb6](https://linux-hardware.org/?probe=b699bf9fb6) | Jun 25, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [1107791eab](https://linux-hardware.org/?probe=1107791eab) | Jun 22, 2020 |
| MSI           | Z170A GAMING M3             | Desktop     | [22963b821f](https://linux-hardware.org/?probe=22963b821f) | Jun 20, 2020 |
| MSI           | Z170A GAMING M3             | Desktop     | [c5779593cc](https://linux-hardware.org/?probe=c5779593cc) | Jun 20, 2020 |
| Acer          | Aspire ES1-132              | Notebook    | [7c1783588a](https://linux-hardware.org/?probe=7c1783588a) | Jun 12, 2020 |
| Acer          | Aspire ES1-132              | Notebook    | [cbbefff0a6](https://linux-hardware.org/?probe=cbbefff0a6) | Jun 12, 2020 |
| Biostar       | Hi-Fi A68U3P                | Desktop     | [ec653ae1fc](https://linux-hardware.org/?probe=ec653ae1fc) | Jun 11, 2020 |
| HP            | 15                          | Notebook    | [a4b90e7ad1](https://linux-hardware.org/?probe=a4b90e7ad1) | Jun 05, 2020 |
| ASUSTek       | X540UP                      | Notebook    | [2ec9f9c770](https://linux-hardware.org/?probe=2ec9f9c770) | Jun 05, 2020 |
| Dell          | Latitude 7490               | Notebook    | [b7b69c9cbf](https://linux-hardware.org/?probe=b7b69c9cbf) | Jun 05, 2020 |
| MSI           | MS-N014                     | Notebook    | [e9fd398a70](https://linux-hardware.org/?probe=e9fd398a70) | Jun 04, 2020 |
| Gigabyte      | X299 UD4 Pro-CF             | Desktop     | [5cde7141d6](https://linux-hardware.org/?probe=5cde7141d6) | Jun 02, 2020 |
| Google        | Caroline                    | Notebook    | [4e305a0551](https://linux-hardware.org/?probe=4e305a0551) | May 31, 2020 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [2a2f1b6680](https://linux-hardware.org/?probe=2a2f1b6680) | May 27, 2020 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [6bdc484d30](https://linux-hardware.org/?probe=6bdc484d30) | May 25, 2020 |
| ASUSTek       | N45SF                       | Notebook    | [a73c8a7057](https://linux-hardware.org/?probe=a73c8a7057) | May 24, 2020 |
| Acer          | Aspire A315-51              | Notebook    | [8d5860b41f](https://linux-hardware.org/?probe=8d5860b41f) | May 23, 2020 |
| Acer          | Aspire A315-51              | Notebook    | [931084ae9c](https://linux-hardware.org/?probe=931084ae9c) | May 23, 2020 |
| ASUSTek       | N45SF                       | Notebook    | [e35a078b83](https://linux-hardware.org/?probe=e35a078b83) | May 23, 2020 |
| HP            | 17E2                        | Mini pc     | [b62ca0352c](https://linux-hardware.org/?probe=b62ca0352c) | May 22, 2020 |
| HP            | EliteBook 745 G3            | Notebook    | [ebd5778f8c](https://linux-hardware.org/?probe=ebd5778f8c) | May 22, 2020 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [a36437dc35](https://linux-hardware.org/?probe=a36437dc35) | May 22, 2020 |
| Lenovo        | ThinkPad X280 20KES69A00    | Notebook    | [c1fc46e405](https://linux-hardware.org/?probe=c1fc46e405) | May 21, 2020 |
| Acer          | Aspire ES1-431              | Notebook    | [58ad8d0b01](https://linux-hardware.org/?probe=58ad8d0b01) | May 18, 2020 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [9e80b645d9](https://linux-hardware.org/?probe=9e80b645d9) | May 17, 2020 |
| Toshiba       | Satellite Pro U400          | Notebook    | [7114a6459c](https://linux-hardware.org/?probe=7114a6459c) | May 17, 2020 |
| Acer          | Aspire ES1-431              | Notebook    | [32fb20af11](https://linux-hardware.org/?probe=32fb20af11) | May 16, 2020 |
| Lenovo        | IdeaPad S540-15IML 81NG     | Notebook    | [89e361466e](https://linux-hardware.org/?probe=89e361466e) | May 14, 2020 |
| HP            | Notebook                    | Notebook    | [142457c9ea](https://linux-hardware.org/?probe=142457c9ea) | May 12, 2020 |
| Dell          | 0D28YY A03                  | Desktop     | [7ae56aa829](https://linux-hardware.org/?probe=7ae56aa829) | May 11, 2020 |
| Acer          | Aspire M5-481PT             | Notebook    | [772cc038ae](https://linux-hardware.org/?probe=772cc038ae) | May 09, 2020 |
| Acer          | Aspire M5-481PT             | Notebook    | [332e871ec3](https://linux-hardware.org/?probe=332e871ec3) | May 09, 2020 |
| Acer          | Aspire ES1-431              | Notebook    | [429d4a7720](https://linux-hardware.org/?probe=429d4a7720) | May 03, 2020 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [028f510367](https://linux-hardware.org/?probe=028f510367) | May 03, 2020 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [d4cbef0ab2](https://linux-hardware.org/?probe=d4cbef0ab2) | May 02, 2020 |
| HP            | EliteBook 745 G2            | Notebook    | [60ee09d8aa](https://linux-hardware.org/?probe=60ee09d8aa) | May 02, 2020 |
| Dell          | 0D28YY A03                  | Desktop     | [285c59f702](https://linux-hardware.org/?probe=285c59f702) | Apr 29, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | Desktop     | [36bb48017f](https://linux-hardware.org/?probe=36bb48017f) | Apr 29, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | Desktop     | [1f91672dce](https://linux-hardware.org/?probe=1f91672dce) | Apr 28, 2020 |
| ASRock        | 960GC-GS FX                 | Desktop     | [6b07754d1d](https://linux-hardware.org/?probe=6b07754d1d) | Apr 27, 2020 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [e487e06d2c](https://linux-hardware.org/?probe=e487e06d2c) | Apr 26, 2020 |
| ASRock        | 960GC-GS FX                 | Desktop     | [390a1cbbb3](https://linux-hardware.org/?probe=390a1cbbb3) | Apr 25, 2020 |
| Biostar       | H81MHV3                     | Desktop     | [252b646f8b](https://linux-hardware.org/?probe=252b646f8b) | Apr 25, 2020 |
| Biostar       | H81MHV3                     | Desktop     | [0fe6d54c09](https://linux-hardware.org/?probe=0fe6d54c09) | Apr 25, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | Desktop     | [eec2e1e90f](https://linux-hardware.org/?probe=eec2e1e90f) | Apr 24, 2020 |
| Dell          | 0D28YY A03                  | Desktop     | [cb0a381ca1](https://linux-hardware.org/?probe=cb0a381ca1) | Apr 22, 2020 |
| Lenovo        | ThinkPad T460s 20F9004FU... | Notebook    | [8eacfd828e](https://linux-hardware.org/?probe=8eacfd828e) | Apr 21, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | Desktop     | [dbe36dfd4f](https://linux-hardware.org/?probe=dbe36dfd4f) | Apr 21, 2020 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [06c5a92500](https://linux-hardware.org/?probe=06c5a92500) | Apr 18, 2020 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [b87b3feefd](https://linux-hardware.org/?probe=b87b3feefd) | Apr 18, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | Desktop     | [d092c3db85](https://linux-hardware.org/?probe=d092c3db85) | Apr 16, 2020 |
| Clevo         | M7x0S                       | Notebook    | [7ba28306d0](https://linux-hardware.org/?probe=7ba28306d0) | Apr 16, 2020 |
| Clevo         | M7x0S                       | Notebook    | [23aa6b7beb](https://linux-hardware.org/?probe=23aa6b7beb) | Apr 16, 2020 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [8eca04a69b](https://linux-hardware.org/?probe=8eca04a69b) | Apr 14, 2020 |
| Dell          | Inspiron 3442               | Notebook    | [4d48cc531a](https://linux-hardware.org/?probe=4d48cc531a) | Apr 13, 2020 |
| Dell          | Inspiron 3442               | Notebook    | [07a7a6e630](https://linux-hardware.org/?probe=07a7a6e630) | Apr 13, 2020 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [576c3b1853](https://linux-hardware.org/?probe=576c3b1853) | Apr 13, 2020 |
| TriGem Com... | DreamSys                    | Desktop     | [e5a22f4123](https://linux-hardware.org/?probe=e5a22f4123) | Apr 09, 2020 |
| Clevo         | E412X                       | Notebook    | [0cca012f20](https://linux-hardware.org/?probe=0cca012f20) | Apr 09, 2020 |
| Acer          | Aspire ES1-431              | Notebook    | [3bf24f9dd6](https://linux-hardware.org/?probe=3bf24f9dd6) | Apr 07, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [c00e4e1a0e](https://linux-hardware.org/?probe=c00e4e1a0e) | Apr 07, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [087a36a4bd](https://linux-hardware.org/?probe=087a36a4bd) | Apr 04, 2020 |
| Biostar       | Hi-Fi A68U3P                | Desktop     | [35b973ebbb](https://linux-hardware.org/?probe=35b973ebbb) | Apr 03, 2020 |
| HP            | EliteBook 745 G2            | Notebook    | [68ecbaa367](https://linux-hardware.org/?probe=68ecbaa367) | Apr 03, 2020 |
| Acer          | Aspire V3-772G              | Notebook    | [9e4c202def](https://linux-hardware.org/?probe=9e4c202def) | Apr 03, 2020 |
| Acer          | Aspire ES1-431              | Notebook    | [3959954db3](https://linux-hardware.org/?probe=3959954db3) | Apr 02, 2020 |
| NEC Comput... | PC-VY24GXZ7A                | Notebook    | [bc0996781f](https://linux-hardware.org/?probe=bc0996781f) | Apr 02, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [9355c0ff9e](https://linux-hardware.org/?probe=9355c0ff9e) | Apr 01, 2020 |
| HP            | 0A5Ch                       | Desktop     | [5f4bf573ad](https://linux-hardware.org/?probe=5f4bf573ad) | Mar 28, 2020 |
| HP            | 0A5Ch                       | Desktop     | [7411b1a819](https://linux-hardware.org/?probe=7411b1a819) | Mar 28, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [8c6dbdb971](https://linux-hardware.org/?probe=8c6dbdb971) | Mar 25, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [70b408e2f0](https://linux-hardware.org/?probe=70b408e2f0) | Mar 25, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [be10de1b16](https://linux-hardware.org/?probe=be10de1b16) | Mar 24, 2020 |
| Dell          | Latitude E6430              | Notebook    | [e38eb04918](https://linux-hardware.org/?probe=e38eb04918) | Mar 23, 2020 |
| ASUSTek       | N45SF                       | Notebook    | [17ec9504f1](https://linux-hardware.org/?probe=17ec9504f1) | Mar 22, 2020 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [92e778ba2a](https://linux-hardware.org/?probe=92e778ba2a) | Mar 21, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [f7cbec79e8](https://linux-hardware.org/?probe=f7cbec79e8) | Mar 15, 2020 |
| Gigabyte      | H310M DS2                   | Desktop     | [529f84f7d1](https://linux-hardware.org/?probe=529f84f7d1) | Mar 12, 2020 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [636f6029b4](https://linux-hardware.org/?probe=636f6029b4) | Mar 11, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [861919e59d](https://linux-hardware.org/?probe=861919e59d) | Mar 08, 2020 |
| MSI           | MS-7309                     | Desktop     | [dff3f373f6](https://linux-hardware.org/?probe=dff3f373f6) | Mar 08, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [2b1b62332c](https://linux-hardware.org/?probe=2b1b62332c) | Mar 08, 2020 |
| MSI           | MS-7309                     | Desktop     | [e52b770dff](https://linux-hardware.org/?probe=e52b770dff) | Mar 08, 2020 |
| MSI           | MS-7309                     | Desktop     | [a06909608c](https://linux-hardware.org/?probe=a06909608c) | Mar 08, 2020 |
| MSI           | MS-7309                     | Desktop     | [b3e1633a13](https://linux-hardware.org/?probe=b3e1633a13) | Mar 08, 2020 |
| Sony          | SVP13215CDB                 | Notebook    | [0aac039fdc](https://linux-hardware.org/?probe=0aac039fdc) | Mar 06, 2020 |
| Dell          | Precision 3540              | Notebook    | [b30c51350c](https://linux-hardware.org/?probe=b30c51350c) | Mar 05, 2020 |
| ASUSTek       | X441SA                      | Notebook    | [e06798387f](https://linux-hardware.org/?probe=e06798387f) | Mar 05, 2020 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [a1d3a510e8](https://linux-hardware.org/?probe=a1d3a510e8) | Mar 04, 2020 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [6e803cdc23](https://linux-hardware.org/?probe=6e803cdc23) | Mar 02, 2020 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [fb41a1d23f](https://linux-hardware.org/?probe=fb41a1d23f) | Mar 02, 2020 |
| Acer          | Aspire V3-772G              | Notebook    | [162a9b6da7](https://linux-hardware.org/?probe=162a9b6da7) | Feb 22, 2020 |
| Acer          | Aspire V5-471G              | Notebook    | [85eca92a3b](https://linux-hardware.org/?probe=85eca92a3b) | Feb 22, 2020 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [f5bb829dbb](https://linux-hardware.org/?probe=f5bb829dbb) | Feb 22, 2020 |
| Foxconn       | G31MX Series                | Desktop     | [e3c94b5684](https://linux-hardware.org/?probe=e3c94b5684) | Feb 22, 2020 |
| Foxconn       | G31MX Series                | Desktop     | [c549e93013](https://linux-hardware.org/?probe=c549e93013) | Feb 21, 2020 |
| Acer          | Aspire ES1-132              | Notebook    | [7994c923a0](https://linux-hardware.org/?probe=7994c923a0) | Feb 21, 2020 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [3dc258b050](https://linux-hardware.org/?probe=3dc258b050) | Feb 20, 2020 |
| Acer          | Aspire V3-772G              | Notebook    | [5cce680c2e](https://linux-hardware.org/?probe=5cce680c2e) | Feb 20, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | Desktop     | [75b9cc12a9](https://linux-hardware.org/?probe=75b9cc12a9) | Feb 20, 2020 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | Notebook    | [de6eba23f1](https://linux-hardware.org/?probe=de6eba23f1) | Feb 09, 2020 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [78d658fc64](https://linux-hardware.org/?probe=78d658fc64) | Feb 09, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | Desktop     | [4f64209449](https://linux-hardware.org/?probe=4f64209449) | Feb 07, 2020 |
| Lenovo        | IdeaPad Y460                | Notebook    | [ece975c659](https://linux-hardware.org/?probe=ece975c659) | Feb 01, 2020 |
| Foxconn       | G31MX Series                | Desktop     | [cb21aa111e](https://linux-hardware.org/?probe=cb21aa111e) | Jan 31, 2020 |
| Lenovo        | IdeaPad Y460                | Notebook    | [1a614a42a8](https://linux-hardware.org/?probe=1a614a42a8) | Jan 30, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [973270aee7](https://linux-hardware.org/?probe=973270aee7) | Jan 26, 2020 |
| Foxconn       | G31MX Series                | Desktop     | [459627eda2](https://linux-hardware.org/?probe=459627eda2) | Jan 26, 2020 |
| Foxconn       | G31MX Series                | Desktop     | [61dfac2df2](https://linux-hardware.org/?probe=61dfac2df2) | Jan 26, 2020 |
| Foxconn       | G31MX Series                | Desktop     | [880daf6c76](https://linux-hardware.org/?probe=880daf6c76) | Jan 26, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [0d020faa5c](https://linux-hardware.org/?probe=0d020faa5c) | Jan 24, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [e3389e7b39](https://linux-hardware.org/?probe=e3389e7b39) | Jan 23, 2020 |
| Lenovo        | ThinkPad T400 2768CC1       | Notebook    | [298e5dbad9](https://linux-hardware.org/?probe=298e5dbad9) | Jan 20, 2020 |
| Dell          | Inspiron N4030              | Notebook    | [f3d828d4b1](https://linux-hardware.org/?probe=f3d828d4b1) | Jan 11, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [600afa3fd4](https://linux-hardware.org/?probe=600afa3fd4) | Jan 11, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [57c3c5d09b](https://linux-hardware.org/?probe=57c3c5d09b) | Jan 11, 2020 |
| ASUSTek       | X540SAA                     | Notebook    | [1e5c712f0b](https://linux-hardware.org/?probe=1e5c712f0b) | Jan 05, 2020 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [d5df64e644](https://linux-hardware.org/?probe=d5df64e644) | Dec 29, 2019 |
| Acer          | Aspire A311-31              | Notebook    | [1db743caaf](https://linux-hardware.org/?probe=1db743caaf) | Dec 24, 2019 |
| Dell          | Inspiron 5567               | Notebook    | [eecdfa47b7](https://linux-hardware.org/?probe=eecdfa47b7) | Dec 15, 2019 |
| Acer          | Aspire A315-51              | Notebook    | [44ecc526a8](https://linux-hardware.org/?probe=44ecc526a8) | Dec 12, 2019 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [afe3135216](https://linux-hardware.org/?probe=afe3135216) | Dec 10, 2019 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [e4fecb44bc](https://linux-hardware.org/?probe=e4fecb44bc) | Dec 05, 2019 |
| HP            | ProBook 440 G6              | Notebook    | [20bcca591f](https://linux-hardware.org/?probe=20bcca591f) | Dec 03, 2019 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [777d549872](https://linux-hardware.org/?probe=777d549872) | Nov 22, 2019 |
| Acer          | Aspire A315-51              | Notebook    | [c5d4684f24](https://linux-hardware.org/?probe=c5d4684f24) | Nov 11, 2019 |
| Acer          | AO722                       | Notebook    | [a54b8c9315](https://linux-hardware.org/?probe=a54b8c9315) | Nov 08, 2019 |
| Pegatron      | IPMSB-H61                   | Desktop     | [857c9bddda](https://linux-hardware.org/?probe=857c9bddda) | Nov 07, 2019 |
| Pegatron      | IPMSB-H61                   | Desktop     | [55e7a33a87](https://linux-hardware.org/?probe=55e7a33a87) | Nov 07, 2019 |
| Acer          | Aspire A315-51              | Notebook    | [ac217a032c](https://linux-hardware.org/?probe=ac217a032c) | Nov 03, 2019 |
| Toshiba       | PORTEGE R30-A               | Notebook    | [619b0ce294](https://linux-hardware.org/?probe=619b0ce294) | Oct 09, 2019 |
| Acer          | Aspire A315-51              | Notebook    | [0f199af685](https://linux-hardware.org/?probe=0f199af685) | Sep 22, 2019 |
| Toshiba       | PORTEGE R30-A               | Notebook    | [8d497813d1](https://linux-hardware.org/?probe=8d497813d1) | Sep 19, 2019 |
| Acer          | TravelMate P249-G2-M        | Notebook    | [7c06f63670](https://linux-hardware.org/?probe=7c06f63670) | Sep 18, 2019 |
| ASUSTek       | X540NA                      | Notebook    | [36b5c905d1](https://linux-hardware.org/?probe=36b5c905d1) | Sep 16, 2019 |
| Gigabyte      | GA-78LMT-S2 R2 sex          | Desktop     | [e5d5c98452](https://linux-hardware.org/?probe=e5d5c98452) | Sep 11, 2019 |
| Wacom         | Citiq Companion             | Tablet      | [5a97b2a1a7](https://linux-hardware.org/?probe=5a97b2a1a7) | Sep 10, 2019 |
| Lenovo        | ThinkPad Edge E320 12982... | Notebook    | [35b92b56a8](https://linux-hardware.org/?probe=35b92b56a8) | Sep 03, 2019 |
| Acer          | Aspire A315-51              | Notebook    | [eaadda80df](https://linux-hardware.org/?probe=eaadda80df) | Aug 25, 2019 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [6674277b6a](https://linux-hardware.org/?probe=6674277b6a) | Aug 23, 2019 |
| ASRock        | A780GM-LE                   | Desktop     | [80fb7e01aa](https://linux-hardware.org/?probe=80fb7e01aa) | Aug 22, 2019 |
| Lenovo        | ThinkPad Edge E320 12982... | Notebook    | [e57d7bb95a](https://linux-hardware.org/?probe=e57d7bb95a) | Aug 14, 2019 |
| Wacom         | Citiq Companion             | Tablet      | [ac4803b894](https://linux-hardware.org/?probe=ac4803b894) | Aug 11, 2019 |
| HP            | Pavilion dm4                | Notebook    | [42df53b120](https://linux-hardware.org/?probe=42df53b120) | Jul 28, 2019 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | Notebook    | [7957c03703](https://linux-hardware.org/?probe=7957c03703) | Jul 28, 2019 |
| Gigabyte      | GA-78LMT-S2 R2 sex          | Desktop     | [1f7f86ed9e](https://linux-hardware.org/?probe=1f7f86ed9e) | Jul 13, 2019 |
| ASUSTek       | X540NA                      | Notebook    | [ac8f1708fb](https://linux-hardware.org/?probe=ac8f1708fb) | Jun 30, 2019 |
| Acer          | Aspire 3935                 | Notebook    | [2288125313](https://linux-hardware.org/?probe=2288125313) | Jun 27, 2019 |
| Acer          | Aspire 3935                 | Notebook    | [fbb934cec8](https://linux-hardware.org/?probe=fbb934cec8) | Jun 27, 2019 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [704346ee85](https://linux-hardware.org/?probe=704346ee85) | Jun 24, 2019 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [3fb0bfffca](https://linux-hardware.org/?probe=3fb0bfffca) | Jun 24, 2019 |
| Dell          | 01TKCC A01                  | Desktop     | [c133935d4f](https://linux-hardware.org/?probe=c133935d4f) | Jun 19, 2019 |
| Acer          | Aspire 5516                 | Notebook    | [92691e9024](https://linux-hardware.org/?probe=92691e9024) | Jun 13, 2019 |
| ASRock        | 960GC-GS FX                 | Desktop     | [db39b4023e](https://linux-hardware.org/?probe=db39b4023e) | Jun 03, 2019 |
| ASRock        | 960GC-GS FX                 | Desktop     | [833afc1cd1](https://linux-hardware.org/?probe=833afc1cd1) | May 12, 2019 |
| ASRock        | 960GC-GS FX                 | Desktop     | [04903c40d9](https://linux-hardware.org/?probe=04903c40d9) | May 10, 2019 |
| ASRock        | 960GC-GS FX                 | Desktop     | [1d29713c8b](https://linux-hardware.org/?probe=1d29713c8b) | May 02, 2019 |
| ASUSTek       | N550JK                      | Notebook    | [d3769c3f4d](https://linux-hardware.org/?probe=d3769c3f4d) | Apr 16, 2019 |
| ASUSTek       | N550JK                      | Notebook    | [31f0b418f9](https://linux-hardware.org/?probe=31f0b418f9) | Apr 16, 2019 |
| Dell          | 01TKCC A01                  | Desktop     | [3cfa230457](https://linux-hardware.org/?probe=3cfa230457) | Apr 12, 2019 |
| Dell          | 01TKCC A01                  | Desktop     | [94e2e60839](https://linux-hardware.org/?probe=94e2e60839) | Apr 11, 2019 |
| HP            | ENVY 4                      | Notebook    | [97135eda99](https://linux-hardware.org/?probe=97135eda99) | Mar 31, 2019 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [ac265b9b6d](https://linux-hardware.org/?probe=ac265b9b6d) | Mar 27, 2019 |
| Dell          | Inspiron 5567               | Notebook    | [18266bd48a](https://linux-hardware.org/?probe=18266bd48a) | Jan 06, 2019 |
| ASUSTek       | X540NA                      | Notebook    | [d3d3b75d21](https://linux-hardware.org/?probe=d3d3b75d21) | Jan 04, 2019 |
| ASUSTek       | X540NA                      | Notebook    | [6f63118ade](https://linux-hardware.org/?probe=6f63118ade) | Jan 04, 2019 |
| Acer          | TravelMate B113             | Notebook    | [fea3b127ea](https://linux-hardware.org/?probe=fea3b127ea) | Dec 25, 2018 |
| ASUSTek       | GL553VD                     | Notebook    | [d43361263c](https://linux-hardware.org/?probe=d43361263c) | Dec 24, 2018 |
| ASUSTek       | X540NA                      | Notebook    | [03eadbe056](https://linux-hardware.org/?probe=03eadbe056) | Nov 20, 2018 |
| ASUSTek       | X540NA                      | Notebook    | [f06d9e94e9](https://linux-hardware.org/?probe=f06d9e94e9) | Nov 20, 2018 |
| Lenovo        | No DPK                      | Desktop     | [02bdd4779e](https://linux-hardware.org/?probe=02bdd4779e) | Oct 21, 2018 |
| Lenovo        | No DPK                      | Desktop     | [d98528c04e](https://linux-hardware.org/?probe=d98528c04e) | Oct 21, 2018 |
| MSI           | A68HM-E33 V2                | Desktop     | [aee859c42b](https://linux-hardware.org/?probe=aee859c42b) | Jan 05, 2018 |
| MSI           | GT70 2PC                    | Notebook    | [020492bfa1](https://linux-hardware.org/?probe=020492bfa1) | Jul 04, 2017 |
| MSI           | GT70 2PC                    | Notebook    | [a5dafd1181](https://linux-hardware.org/?probe=a5dafd1181) | Jul 04, 2017 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 52        | 12.59%  |
| Ubuntu 18.04                 | 25        | 6.05%   |
| Pop!_OS 20.04                | 25        | 6.05%   |
| KDE neon 20.04               | 15        | 3.63%   |
| OpenMandriva 4.2             | 13        | 3.15%   |
| Zorin 15                     | 11        | 2.66%   |
| Pop!_OS 21.04                | 10        | 2.42%   |
| Ubuntu 22.04                 | 9         | 2.18%   |
| BlackPanther 18.1            | 8         | 1.94%   |
| Linux Mint 20.2              | 7         | 1.69%   |
| Pop!_OS 20.10                | 6         | 1.45%   |
| OpenMandriva 4.3             | 6         | 1.45%   |
| Manjaro                      | 6         | 1.45%   |
| Linux Mint 20.1              | 6         | 1.45%   |
| Fedora 33                    | 6         | 1.45%   |
| Endless 3.7.7                | 6         | 1.45%   |
| Arch                         | 6         | 1.45%   |
| Ubuntu 20.10                 | 5         | 1.21%   |
| Linux Mint 19.3              | 5         | 1.21%   |
| Fedora 36                    | 5         | 1.21%   |
| Fedora 35                    | 5         | 1.21%   |
| Fedora 32                    | 5         | 1.21%   |
| Endless 3.7.6                | 5         | 1.21%   |
| BlackPanther 16.2            | 5         | 1.21%   |
| Zorin 16                     | 4         | 0.97%   |
| Xubuntu 20.04                | 4         | 0.97%   |
| Pop!_OS 22.04                | 4         | 0.97%   |
| Pop!_OS 21.10                | 4         | 0.97%   |
| LMDE 4                       | 4         | 0.97%   |
| Linux Mint 20.3              | 4         | 0.97%   |
| Fedora 34                    | 4         | 0.97%   |
| Debian 11                    | 4         | 0.97%   |
| Ubuntu 21.10                 | 3         | 0.73%   |
| Ubuntu 19.10                 | 3         | 0.73%   |
| Linux Mint 20                | 3         | 0.73%   |
| Kubuntu 22.04                | 3         | 0.73%   |
| KDE neon 18.04               | 3         | 0.73%   |
| Fedora 31                    | 3         | 0.73%   |
| Endless 3.9.1                | 3         | 0.73%   |
| EndeavourOS Rolling          | 3         | 0.73%   |
| Debian 10                    | 3         | 0.73%   |
| Xubuntu 19.10                | 2         | 0.48%   |
| Xubuntu 18.04                | 2         | 0.48%   |
| Ubuntu MATE 20.04            | 2         | 0.48%   |
| Ubuntu MATE 18.04            | 2         | 0.48%   |
| Ubuntu 18.10                 | 2         | 0.48%   |
| Ubuntu 16.04                 | 2         | 0.48%   |
| Peppermint 10                | 2         | 0.48%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 0.48%   |
| Manjaro 21.3.1               | 2         | 0.48%   |
| Manjaro 21.2.3               | 2         | 0.48%   |
| Manjaro 20.1                 | 2         | 0.48%   |
| Linux Mint 19.2              | 2         | 0.48%   |
| Linux Mint 19.1              | 2         | 0.48%   |
| Kali 2021.4                  | 2         | 0.48%   |
| Endless 3.9.4                | 2         | 0.48%   |
| Endless 3.8.7                | 2         | 0.48%   |
| Endless 3.8.1                | 2         | 0.48%   |
| Endless 3.7.5                | 2         | 0.48%   |
| Endless 3.3.20               | 2         | 0.48%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 99        | 25.45%  |
| Pop!_OS       | 49        | 12.6%   |
| Linux Mint    | 30        | 7.71%   |
| Endless       | 29        | 7.46%   |
| Fedora        | 26        | 6.68%   |
| OpenMandriva  | 19        | 4.88%   |
| KDE neon      | 18        | 4.63%   |
| Zorin         | 15        | 3.86%   |
| Manjaro       | 15        | 3.86%   |
| BlackPanther  | 10        | 2.57%   |
| Debian        | 9         | 2.31%   |
| Xubuntu       | 8         | 2.06%   |
| Arch          | 8         | 2.06%   |
| Kubuntu       | 5         | 1.29%   |
| Kali          | 5         | 1.29%   |
| Elementary    | 5         | 1.29%   |
| Ubuntu MATE   | 4         | 1.03%   |
| LMDE          | 4         | 1.03%   |
| EndeavourOS   | 4         | 1.03%   |
| ROSA          | 3         | 0.77%   |
| openSUSE      | 3         | 0.77%   |
| Peppermint    | 2         | 0.51%   |
| MX            | 2         | 0.51%   |
| Gentoo        | 2         | 0.51%   |
| ArcoLinux     | 2         | 0.51%   |
| Ubuntu Budgie | 1         | 0.26%   |
| Sparky        | 1         | 0.26%   |
| Solus         | 1         | 0.26%   |
| Slackware     | 1         | 0.26%   |
| Reborn OS     | 1         | 0.26%   |
| Raspbian      | 1         | 0.26%   |
| Lubuntu       | 1         | 0.26%   |
| Linux Lite    | 1         | 0.26%   |
| Hash Linux    | 1         | 0.26%   |
| Garuda Linux  | 1         | 0.26%   |
| Clear Linux   | 1         | 0.26%   |
| BunsenLabs    | 1         | 0.26%   |
| Archcraft     | 1         | 0.26%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 18        | 4.04%   |
| 5.10.14-desktop-1omv4002 | 13        | 2.92%   |
| 5.3.0-28-generic         | 10        | 2.25%   |
| 5.4.0-7634-generic       | 8         | 1.8%    |
| 5.4.0-48-generic         | 8         | 1.8%    |
| 4.18.16-desktop-1bP      | 8         | 1.8%    |
| 5.3.0-23-generic         | 7         | 1.57%   |
| 5.8.0-7630-generic       | 6         | 1.35%   |
| 5.8.0-14-generic         | 6         | 1.35%   |
| 5.16.7-desktop-1omv4003  | 6         | 1.35%   |
| 5.4.0-58-generic         | 5         | 1.12%   |
| 5.4.0-47-generic         | 5         | 1.12%   |
| 5.15.0-41-generic        | 5         | 1.12%   |
| 5.11.0-7620-generic      | 5         | 1.12%   |
| 4.9.20-desktop-pae-1bP   | 5         | 1.12%   |
| 5.4.0-7642-generic       | 4         | 0.9%    |
| 5.4.0-73-generic         | 4         | 0.9%    |
| 5.4.0-19-generic         | 4         | 0.9%    |
| 5.13.0-7614-generic      | 4         | 0.9%    |
| 5.13.0-30-generic        | 4         | 0.9%    |
| 4.18.0-25-generic        | 4         | 0.9%    |
| 5.8.0-7642-generic       | 3         | 0.67%   |
| 5.4.0-80-generic         | 3         | 0.67%   |
| 5.4.0-52-generic         | 3         | 0.67%   |
| 5.4.0-45-generic         | 3         | 0.67%   |
| 5.4.0-31-generic         | 3         | 0.67%   |
| 5.3.0-46-generic         | 3         | 0.67%   |
| 5.17.5-76051705-generic  | 3         | 0.67%   |
| 5.15.0-40-generic        | 3         | 0.67%   |
| 5.13.0-40-generic        | 3         | 0.67%   |
| 5.13.0-35-generic        | 3         | 0.67%   |
| 5.13.0-28-generic        | 3         | 0.67%   |
| 5.11.0-7614-generic      | 3         | 0.67%   |
| 5.11.0-27-generic        | 3         | 0.67%   |
| 5.0.0-37-generic         | 3         | 0.67%   |
| 5.9.16-1-MANJARO         | 2         | 0.45%   |
| 5.8.0-59-generic         | 2         | 0.45%   |
| 5.8.0-43-generic         | 2         | 0.45%   |
| 5.8.0-36-generic         | 2         | 0.45%   |
| 5.8.0-1019-raspi         | 2         | 0.45%   |
| 5.4.20-200.fc31.x86_64   | 2         | 0.45%   |
| 5.4.0-90-generic         | 2         | 0.45%   |
| 5.4.0-81-generic         | 2         | 0.45%   |
| 5.4.0-7625-generic       | 2         | 0.45%   |
| 5.4.0-74-generic         | 2         | 0.45%   |
| 5.4.0-65-generic         | 2         | 0.45%   |
| 5.4.0-54-generic         | 2         | 0.45%   |
| 5.4.0-39-generic         | 2         | 0.45%   |
| 5.3.0-53-generic         | 2         | 0.45%   |
| 5.3.0-51-generic         | 2         | 0.45%   |
| 5.3.0-42-generic         | 2         | 0.45%   |
| 5.3.0-40-generic         | 2         | 0.45%   |
| 5.18.13-200.fc36.x86_64  | 2         | 0.45%   |
| 5.15.49-1-MANJARO        | 2         | 0.45%   |
| 5.15.21-1-MANJARO        | 2         | 0.45%   |
| 5.15.0-27-generic        | 2         | 0.45%   |
| 5.13.8-200.fc34.x86_64   | 2         | 0.45%   |
| 5.13.0-7620-generic      | 2         | 0.45%   |
| 5.13.0-41-generic        | 2         | 0.45%   |
| 5.11.16-arch1-1          | 2         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 95        | 22.41%  |
| 5.3.0   | 32        | 7.55%   |
| 5.8.0   | 31        | 7.31%   |
| 5.13.0  | 29        | 6.84%   |
| 5.11.0  | 23        | 5.42%   |
| 4.15.0  | 20        | 4.72%   |
| 5.15.0  | 15        | 3.54%   |
| 5.10.14 | 13        | 3.07%   |
| 5.0.0   | 11        | 2.59%   |
| 4.18.0  | 10        | 2.36%   |
| 4.19.0  | 8         | 1.89%   |
| 4.18.16 | 8         | 1.89%   |
| 5.16.7  | 6         | 1.42%   |
| 5.10.0  | 6         | 1.42%   |
| 4.9.20  | 6         | 1.42%   |
| 5.17.5  | 5         | 1.18%   |
| 5.9.16  | 3         | 0.71%   |
| 5.18.13 | 3         | 0.71%   |
| 5.11.16 | 3         | 0.71%   |
| 4.4.0   | 3         | 0.71%   |
| 5.9.11  | 2         | 0.47%   |
| 5.8.14  | 2         | 0.47%   |
| 5.4.20  | 2         | 0.47%   |
| 5.16.0  | 2         | 0.47%   |
| 5.15.49 | 2         | 0.47%   |
| 5.15.21 | 2         | 0.47%   |
| 5.15.10 | 2         | 0.47%   |
| 5.14.0  | 2         | 0.47%   |
| 5.13.8  | 2         | 0.47%   |
| 5.11.12 | 2         | 0.47%   |
| 4.13.0  | 2         | 0.47%   |
| 5.9.14  | 1         | 0.24%   |
| 5.9.13  | 1         | 0.24%   |
| 5.9.10  | 1         | 0.24%   |
| 5.8.8   | 1         | 0.24%   |
| 5.8.6   | 1         | 0.24%   |
| 5.8.4   | 1         | 0.24%   |
| 5.8.3   | 1         | 0.24%   |
| 5.8.18  | 1         | 0.24%   |
| 5.7.11  | 1         | 0.24%   |
| 5.7.1   | 1         | 0.24%   |
| 5.6.16  | 1         | 0.24%   |
| 5.6.10  | 1         | 0.24%   |
| 5.6.0   | 1         | 0.24%   |
| 5.4.96  | 1         | 0.24%   |
| 5.4.73  | 1         | 0.24%   |
| 5.4.70  | 1         | 0.24%   |
| 5.4.61  | 1         | 0.24%   |
| 5.4.60  | 1         | 0.24%   |
| 5.4.24  | 1         | 0.24%   |
| 5.4.23  | 1         | 0.24%   |
| 5.4.2   | 1         | 0.24%   |
| 5.4.105 | 1         | 0.24%   |
| 5.3.18  | 1         | 0.24%   |
| 5.3.12  | 1         | 0.24%   |
| 5.2.14  | 1         | 0.24%   |
| 5.18.11 | 1         | 0.24%   |
| 5.18.10 | 1         | 0.24%   |
| 5.17.15 | 1         | 0.24%   |
| 5.17.11 | 1         | 0.24%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 106       | 25.18%  |
| 5.8     | 38        | 9.03%   |
| 5.3     | 34        | 8.08%   |
| 5.13    | 32        | 7.6%    |
| 5.15    | 31        | 7.36%   |
| 5.10    | 31        | 7.36%   |
| 5.11    | 28        | 6.65%   |
| 4.15    | 20        | 4.75%   |
| 4.18    | 18        | 4.28%   |
| 5.16    | 16        | 3.8%    |
| 5.0     | 12        | 2.85%   |
| 4.9     | 8         | 1.9%    |
| 4.19    | 8         | 1.9%    |
| 5.9     | 7         | 1.66%   |
| 5.17    | 7         | 1.66%   |
| 5.18    | 5         | 1.19%   |
| 5.14    | 4         | 0.95%   |
| 4.4     | 4         | 0.95%   |
| 5.6     | 3         | 0.71%   |
| 5.7     | 2         | 0.48%   |
| 5.12    | 2         | 0.48%   |
| 4.13    | 2         | 0.48%   |
| 5.2     | 1         | 0.24%   |
| 5.1     | 1         | 0.24%   |
| 3.8     | 1         | 0.24%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 359       | 94.47%  |
| i686    | 14        | 3.68%   |
| armv7l  | 4         | 1.05%   |
| aarch64 | 3         | 0.79%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 187       | 47.58%  |
| KDE5            | 63        | 16.03%  |
| Unknown         | 35        | 8.91%   |
| XFCE            | 30        | 7.63%   |
| X-Cinnamon      | 26        | 6.62%   |
| KDE             | 17        | 4.33%   |
| MATE            | 8         | 2.04%   |
| Unity           | 5         | 1.27%   |
| Pantheon        | 4         | 1.02%   |
| LXQt            | 3         | 0.76%   |
| LXDE            | 3         | 0.76%   |
| Openbox         | 2         | 0.51%   |
| Cinnamon        | 2         | 0.51%   |
| Budgie          | 2         | 0.51%   |
| sway            | 1         | 0.25%   |
| river           | 1         | 0.25%   |
| GNOME Flashback | 1         | 0.25%   |
| default         | 1         | 0.25%   |
| Deepin          | 1         | 0.25%   |
| awesome         | 1         | 0.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 328       | 84.97%  |
| Wayland | 34        | 8.81%   |
| Unknown | 17        | 4.4%    |
| Tty     | 7         | 1.81%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 241       | 61.64%  |
| SDDM    | 52        | 13.3%   |
| GDM     | 41        | 10.49%  |
| LightDM | 25        | 6.39%   |
| GDM3    | 19        | 4.86%   |
| TDM     | 10        | 2.56%   |
| SLiM    | 1         | 0.26%   |
| MDM     | 1         | 0.26%   |
| LXDM    | 1         | 0.26%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_PH   | 180       | 46.39%  |
| en_US   | 142       | 36.6%   |
| Unknown | 43        | 11.08%  |
| C       | 8         | 2.06%   |
| en_GB   | 5         | 1.29%   |
| de_DE   | 4         | 1.03%   |
| zh_CN   | 2         | 0.52%   |
| zh_HK   | 1         | 0.26%   |
| fil_PH  | 1         | 0.26%   |
| en_NZ   | 1         | 0.26%   |
| da_DK   | 1         | 0.26%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 203       | 52.59%  |
| EFI  | 183       | 47.41%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 304       | 77.75%  |
| Overlay | 34        | 8.7%    |
| Btrfs   | 34        | 8.7%    |
| Unknown | 11        | 2.81%   |
| Xfs     | 4         | 1.02%   |
| Ext2    | 3         | 0.77%   |
| Zfs     | 1         | 0.26%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 250       | 64.1%   |
| GPT     | 98        | 25.13%  |
| MBR     | 42        | 10.77%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 339       | 87.15%  |
| Yes       | 50        | 12.85%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 289       | 74.1%   |
| Yes       | 101       | 25.9%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| Lenovo                    | 61        | 16.18%  |
| Acer                      | 48        | 12.73%  |
| ASUSTek Computer          | 47        | 12.47%  |
| Hewlett-Packard           | 36        | 9.55%   |
| MSI                       | 33        | 8.75%   |
| Dell                      | 32        | 8.49%   |
| Gigabyte Technology       | 31        | 8.22%   |
| Toshiba                   | 11        | 2.92%   |
| ASRock                    | 9         | 2.39%   |
| Apple                     | 8         | 2.12%   |
| Samsung Electronics       | 5         | 1.33%   |
| Foxconn                   | 5         | 1.33%   |
| Sony                      | 4         | 1.06%   |
| Raspberry Pi Foundation   | 4         | 1.06%   |
| ECS                       | 4         | 1.06%   |
| Clevo                     | 4         | 1.06%   |
| Biostar                   | 4         | 1.06%   |
| Unknown                   | 4         | 1.06%   |
| NEC Computers             | 3         | 0.8%    |
| EMAXX TECHNOLOGY          | 3         | 0.8%    |
| eMachines                 | 3         | 0.8%    |
| Pegatron                  | 2         | 0.53%   |
| YANYU                     | 1         | 0.27%   |
| Wacom                     | 1         | 0.27%   |
| TriGem Computer           | 1         | 0.27%   |
| Shenzhen Bmorn Technology | 1         | 0.27%   |
| QTQD                      | 1         | 0.27%   |
| PERSONA                   | 1         | 0.27%   |
| Notebook                  | 1         | 0.27%   |
| Microsoft                 | 1         | 0.27%   |
| Jumper                    | 1         | 0.27%   |
| JOOYON                    | 1         | 0.27%   |
| Intel                     | 1         | 0.27%   |
| HASEE Computer            | 1         | 0.27%   |
| Google                    | 1         | 0.27%   |
| Fujitsu                   | 1         | 0.27%   |
| Cubix                     | 1         | 0.27%   |
| AMD                       | 1         | 0.27%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 8         | 2.12%   |
| Acer Aspire ES1-132                      | 6         | 1.59%   |
| MSI MS-7721                              | 4         | 1.06%   |
| MSI MS-7309                              | 4         | 1.06%   |
| ASUS All Series                          | 4         | 1.06%   |
| RPi Raspberry Pi                         | 3         | 0.8%    |
| HP Notebook                              | 3         | 0.8%    |
| Gigabyte F2A68HM-S1                      | 3         | 0.8%    |
| Foxconn G31MX Series                     | 3         | 0.8%    |
| Clevo M7x0S                              | 3         | 0.8%    |
| ASUS P8H61-M LX3 PLUS R2.0               | 3         | 0.8%    |
| ASRock B450M Steel Legend                | 3         | 0.8%    |
| Pegatron IPMSB-H61                       | 2         | 0.53%   |
| Lenovo Yoga 520-14IKB 81C8               | 2         | 0.53%   |
| Lenovo V110-14IAP 80TF                   | 2         | 0.53%   |
| HP Pavilion Notebook                     | 2         | 0.53%   |
| Gigabyte Z590 AORUS ULTRA                | 2         | 0.53%   |
| Gigabyte A320M-S2H V2                    | 2         | 0.53%   |
| Foxconn 500B Microtower                  | 2         | 0.53%   |
| eMachines eM350                          | 2         | 0.53%   |
| Dell OptiPlex 9010 AIO                   | 2         | 0.53%   |
| Dell Latitude E7450                      | 2         | 0.53%   |
| Dell Inspiron 5567                       | 2         | 0.53%   |
| ASUS X540NA                              | 2         | 0.53%   |
| ASUS PRIME B250M-K                       | 2         | 0.53%   |
| ASUS EX-H310M-V3 R2.0                    | 2         | 0.53%   |
| Apple MacBookPro5,5                      | 2         | 0.53%   |
| Acer TravelMate P249-G2-M                | 2         | 0.53%   |
| Acer TravelMate B113                     | 2         | 0.53%   |
| Acer Aspire E5-551G                      | 2         | 0.53%   |
| Acer Aspire A315-51                      | 2         | 0.53%   |
| Acer Aspire A315-41G                     | 2         | 0.53%   |
| YANYU EPIC-C19                           | 1         | 0.27%   |
| Wacom Citiq Companion                    | 1         | 0.27%   |
| TriGem DreamSys                          | 1         | 0.27%   |
| Toshiba TECRA R940                       | 1         | 0.27%   |
| Toshiba Satellite Pro U400               | 1         | 0.27%   |
| Toshiba Satellite P845                   | 1         | 0.27%   |
| Toshiba Satellite L515                   | 1         | 0.27%   |
| Toshiba Satellite E45t-A                 | 1         | 0.27%   |
| Toshiba Satellite C650                   | 1         | 0.27%   |
| Toshiba Satellite C55D-B                 | 1         | 0.27%   |
| Toshiba PORTEGE R30-A                    | 1         | 0.27%   |
| Toshiba NB255                            | 1         | 0.27%   |
| Toshiba dynabook R73/W                   | 1         | 0.27%   |
| Toshiba dynabook B45/A                   | 1         | 0.27%   |
| Sony VPCEA36FA                           | 1         | 0.27%   |
| Sony SVT13115FGS                         | 1         | 0.27%   |
| Sony SVP13215CDB                         | 1         | 0.27%   |
| Sony SVF14216SGP                         | 1         | 0.27%   |
| Shenzhen Bmorn NBPC1078                  | 1         | 0.27%   |
| Samsung RF511/RF411/RF711                | 1         | 0.27%   |
| Samsung RC420/RC520/RC720                | 1         | 0.27%   |
| Samsung N150P/N210P/N220P                | 1         | 0.27%   |
| Samsung 905S3G/906S3G/915S3G/9305SG      | 1         | 0.27%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV | 1         | 0.27%   |
| RPi Raspberry Pi 4 Model B Rev 1.4       | 1         | 0.27%   |
| PERSONA MYBOOK 14                        | 1         | 0.27%   |
| Notebook NH5x_7xDCx_DDx                  | 1         | 0.27%   |
| NEC Computers PC-VY24GXZ7A               | 1         | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Acer Aspire             | 34        | 9.02%   |
| Lenovo ThinkPad         | 27        | 7.16%   |
| Lenovo IdeaPad          | 21        | 5.57%   |
| Dell Inspiron           | 11        | 2.92%   |
| HP Pavilion             | 8         | 2.12%   |
| Dell OptiPlex           | 8         | 2.12%   |
| Unknown                 | 8         | 2.12%   |
| Acer TravelMate         | 7         | 1.86%   |
| Toshiba Satellite       | 6         | 1.59%   |
| Dell Latitude           | 5         | 1.33%   |
| ASUS ROG                | 5         | 1.33%   |
| ASUS P8H61-M            | 5         | 1.33%   |
| RPi Raspberry           | 4         | 1.06%   |
| MSI MS-7721             | 4         | 1.06%   |
| MSI MS-7309             | 4         | 1.06%   |
| ASUS TUF                | 4         | 1.06%   |
| ASUS PRIME              | 4         | 1.06%   |
| ASUS All                | 4         | 1.06%   |
| Lenovo Legion           | 3         | 0.8%    |
| HP ProDesk              | 3         | 0.8%    |
| HP Notebook             | 3         | 0.8%    |
| HP EliteBook            | 3         | 0.8%    |
| Gigabyte F2A68HM-S1     | 3         | 0.8%    |
| Gigabyte A320M-S2H      | 3         | 0.8%    |
| Foxconn G31MX           | 3         | 0.8%    |
| Dell Vostro             | 3         | 0.8%    |
| Clevo M7x0S             | 3         | 0.8%    |
| ASRock B450M            | 3         | 0.8%    |
| Acer Nitro              | 3         | 0.8%    |
| Toshiba dynabook        | 2         | 0.53%   |
| Pegatron IPMSB-H61      | 2         | 0.53%   |
| MSI CX62                | 2         | 0.53%   |
| Lenovo Yoga             | 2         | 0.53%   |
| Lenovo V110-14IAP       | 2         | 0.53%   |
| Lenovo IdeaPadFlex      | 2         | 0.53%   |
| HP Stream               | 2         | 0.53%   |
| HP ProBook              | 2         | 0.53%   |
| HP Compaq               | 2         | 0.53%   |
| Gigabyte Z590           | 2         | 0.53%   |
| Gigabyte B450           | 2         | 0.53%   |
| Foxconn 500B            | 2         | 0.53%   |
| eMachines eM350         | 2         | 0.53%   |
| Dell XPS                | 2         | 0.53%   |
| ASUS X540NA             | 2         | 0.53%   |
| ASUS VivoBook           | 2         | 0.53%   |
| ASUS EX-H310M-V3        | 2         | 0.53%   |
| Apple MacBookPro5       | 2         | 0.53%   |
| YANYU EPIC-C19          | 1         | 0.27%   |
| Wacom Citiq             | 1         | 0.27%   |
| TriGem DreamSys         | 1         | 0.27%   |
| Toshiba TECRA           | 1         | 0.27%   |
| Toshiba PORTEGE         | 1         | 0.27%   |
| Toshiba NB255           | 1         | 0.27%   |
| Sony VPCEA36FA          | 1         | 0.27%   |
| Sony SVT13115FGS        | 1         | 0.27%   |
| Sony SVP13215CDB        | 1         | 0.27%   |
| Sony SVF14216SGP        | 1         | 0.27%   |
| Shenzhen Bmorn NBPC1078 | 1         | 0.27%   |
| Samsung RF511           | 1         | 0.27%   |
| Samsung RC420           | 1         | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2014    | 36        | 9.55%   |
| 2012    | 35        | 9.28%   |
| 2017    | 33        | 8.75%   |
| 2018    | 31        | 8.22%   |
| 2016    | 30        | 7.96%   |
| 2010    | 30        | 7.96%   |
| 2019    | 29        | 7.69%   |
| 2020    | 26        | 6.9%    |
| 2015    | 25        | 6.63%   |
| 2013    | 21        | 5.57%   |
| 2011    | 21        | 5.57%   |
| 2009    | 17        | 4.51%   |
| 2021    | 16        | 4.24%   |
| 2007    | 9         | 2.39%   |
| 2008    | 8         | 2.12%   |
| Unknown | 7         | 1.86%   |
| 2022    | 2         | 0.53%   |
| 2006    | 1         | 0.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 227       | 60.21%  |
| Desktop        | 129       | 34.22%  |
| Mini pc        | 6         | 1.59%   |
| System on chip | 4         | 1.06%   |
| Convertible    | 4         | 1.06%   |
| All in one     | 4         | 1.06%   |
| Tablet         | 3         | 0.8%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 336       | 89.12%  |
| Enabled  | 41        | 10.88%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 376       | 99.73%  |
| Yes  | 1         | 0.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 100       | 25.77%  |
| 4.01-8.0    | 81        | 20.88%  |
| 8.01-16.0   | 77        | 19.85%  |
| 16.01-24.0  | 49        | 12.63%  |
| 1.01-2.0    | 41        | 10.57%  |
| 32.01-64.0  | 15        | 3.87%   |
| 2.01-3.0    | 11        | 2.84%   |
| 64.01-256.0 | 5         | 1.29%   |
| 0.51-1.0    | 5         | 1.29%   |
| 24.01-32.0  | 4         | 1.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 159       | 37.77%  |
| 2.01-3.0  | 119       | 28.27%  |
| 4.01-8.0  | 43        | 10.21%  |
| 0.51-1.0  | 41        | 9.74%   |
| 3.01-4.0  | 38        | 9.03%   |
| 8.01-16.0 | 12        | 2.85%   |
| 0.01-0.5  | 8         | 1.9%    |
| Unknown   | 1         | 0.24%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 256       | 64.97%  |
| 2      | 97        | 24.62%  |
| 3      | 19        | 4.82%   |
| 4      | 12        | 3.05%   |
| 5      | 6         | 1.52%   |
| 0      | 3         | 0.76%   |
| 13     | 1         | 0.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 262       | 67.88%  |
| Yes       | 124       | 32.12%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 326       | 86.47%  |
| No        | 51        | 13.53%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 286       | 75.26%  |
| No        | 94        | 24.74%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 211       | 55.38%  |
| No        | 170       | 44.62%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Philippines | 377       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Quezon City         | 69        | 16.47%  |
| Cebu City           | 28        | 6.68%   |
| Davao City          | 22        | 5.25%   |
| Angeles City        | 21        | 5.01%   |
| Cagayan de Oro      | 18        | 4.3%    |
| Pasig               | 14        | 3.34%   |
| Manila              | 14        | 3.34%   |
| Paranaque City      | 12        | 2.86%   |
| San Miguel          | 10        | 2.39%   |
| San Jose del Monte  | 10        | 2.39%   |
| Manajao             | 10        | 2.39%   |
| Bacoor              | 10        | 2.39%   |
| Bacolod City        | 10        | 2.39%   |
| Santa Rosa          | 8         | 1.91%   |
| Mandaluyong City    | 8         | 1.91%   |
| Makati City         | 8         | 1.91%   |
| Iligan City         | 8         | 1.91%   |
| Caloocan City       | 8         | 1.91%   |
| Imus                | 7         | 1.67%   |
| San Fernando City   | 6         | 1.43%   |
| Las Pinas           | 6         | 1.43%   |
| Lahug               | 5         | 1.19%   |
| Zamboanga City      | 4         | 0.95%   |
| Tarlac City         | 4         | 0.95%   |
| Malolos             | 4         | 0.95%   |
| Lucena City         | 4         | 0.95%   |
| General Santos      | 4         | 0.95%   |
| City of Muntinglupa | 4         | 0.95%   |
| Antipolo City       | 4         | 0.95%   |
| Lipa City           | 3         | 0.72%   |
| Iloilo City         | 3         | 0.72%   |
| Dasmarinas          | 3         | 0.72%   |
| Baguio City         | 3         | 0.72%   |
| Tuguegarao City     | 2         | 0.48%   |
| Taytay              | 2         | 0.48%   |
| Taguig              | 2         | 0.48%   |
| San Pedro           | 2         | 0.48%   |
| Oroquieta           | 2         | 0.48%   |
| Naga                | 2         | 0.48%   |
| Marikina City       | 2         | 0.48%   |
| Mandaue City        | 2         | 0.48%   |
| Magugpo Poblacion   | 2         | 0.48%   |
| Lapu-Lapu City      | 2         | 0.48%   |
| Cabanatuan City     | 2         | 0.48%   |
| Agoo                | 2         | 0.48%   |
| Abaga               | 2         | 0.48%   |
| Talisay City        | 1         | 0.24%   |
| Sibulan             | 1         | 0.24%   |
| San Pablo City      | 1         | 0.24%   |
| San Juan            | 1         | 0.24%   |
| San Carlos          | 1         | 0.24%   |
| Roxas City          | 1         | 0.24%   |
| Rosario             | 1         | 0.24%   |
| Rizal               | 1         | 0.24%   |
| Pinagbuhatan        | 1         | 0.24%   |
| Pili                | 1         | 0.24%   |
| Pasay               | 1         | 0.24%   |
| Ormoc City          | 1         | 0.24%   |
| Naic                | 1         | 0.24%   |
| Nagkaisang Nayon    | 1         | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 103       | 153    | 19.62%  |
| WDC                       | 93        | 114    | 17.71%  |
| Toshiba                   | 61        | 80     | 11.62%  |
| Samsung Electronics       | 39        | 49     | 7.43%   |
| Hitachi                   | 29        | 48     | 5.52%   |
| Unknown                   | 24        | 31     | 4.57%   |
| Kingston                  | 24        | 30     | 4.57%   |
| SanDisk                   | 19        | 20     | 3.62%   |
| SK hynix                  | 12        | 25     | 2.29%   |
| HGST                      | 12        | 13     | 2.29%   |
| Intel                     | 8         | 9      | 1.52%   |
| Team                      | 7         | 10     | 1.33%   |
| A-DATA Technology         | 7         | 10     | 1.33%   |
| Micron Technology         | 6         | 7      | 1.14%   |
| Gigabyte Technology       | 6         | 7      | 1.14%   |
| Fujitsu                   | 6         | 7      | 1.14%   |
| Lexar                     | 5         | 6      | 0.95%   |
| Transcend                 | 4         | 4      | 0.76%   |
| Crucial                   | 4         | 6      | 0.76%   |
| Ramsta                    | 3         | 4      | 0.57%   |
| HS-SSD-E100               | 3         | 3      | 0.57%   |
| China                     | 3         | 3      | 0.57%   |
| Apple                     | 3         | 3      | 0.57%   |
| XPG                       | 2         | 2      | 0.38%   |
| WALRAM                    | 2         | 2      | 0.38%   |
| Silicon Motion            | 2         | 2      | 0.38%   |
| Phison                    | 2         | 2      | 0.38%   |
| LITEONIT                  | 2         | 3      | 0.38%   |
| Kingmax                   | 2         | 2      | 0.38%   |
| Indilinx                  | 2         | 2      | 0.38%   |
| ZOTAC                     | 1         | 1      | 0.19%   |
| XrayDisk                  | 1         | 1      | 0.19%   |
| Voyager                   | 1         | 1      | 0.19%   |
| UMIS                      | 1         | 1      | 0.19%   |
| Teclast                   | 1         | 4      | 0.19%   |
| TAMMUZ                    | 1         | 1      | 0.19%   |
| T-FORCE                   | 1         | 1      | 0.19%   |
| SPCC                      | 1         | 2      | 0.19%   |
| Solid State Storage       | 1         | 1      | 0.19%   |
| SAGE                      | 1         | 1      | 0.19%   |
| Realtek Semiconductor     | 1         | 1      | 0.19%   |
| QGeeM                     | 1         | 1      | 0.19%   |
| PNY                       | 1         | 1      | 0.19%   |
| Plextor                   | 1         | 1      | 0.19%   |
| OCZ                       | 1         | 1      | 0.19%   |
| Micron/Crucial Technology | 1         | 1      | 0.19%   |
| Lite-On                   | 1         | 3      | 0.19%   |
| Lenovo                    | 1         | 1      | 0.19%   |
| KIOXIA                    | 1         | 1      | 0.19%   |
| KingSpec                  | 1         | 1      | 0.19%   |
| Kimtigo                   | 1         | 2      | 0.19%   |
| JMicron Technology        | 1         | 4      | 0.19%   |
| JetDrive                  | 1         | 1      | 0.19%   |
| Hikvision                 | 1         | 2      | 0.19%   |
| GLOWAY                    | 1         | 1      | 0.19%   |
| FORESEE                   | 1         | 1      | 0.19%   |
| Colorful                  | 1         | 1      | 0.19%   |
| ASUS-PHISON               | 1         | 2      | 0.19%   |
| Argon                     | 1         | 2      | 0.19%   |
| 16GB SAT                  | 1         | 1      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB         | 13        | 2.29%   |
| Seagate ST500DM002-1BD142 500GB  | 11        | 1.94%   |
| Seagate ST1000DM010-2EP102 1TB   | 10        | 1.76%   |
| Toshiba MQ01ABD100 1TB           | 8         | 1.41%   |
| Seagate ST1000LM035-1RK172 1TB   | 8         | 1.41%   |
| WDC WD5000LPCX-21VHAT0 500GB     | 7         | 1.23%   |
| Toshiba DT01ACA050 500GB         | 7         | 1.23%   |
| Toshiba MQ04ABF100 1TB           | 6         | 1.06%   |
| Samsung SSD 860 EVO 500GB        | 6         | 1.06%   |
| Kingston SA400S37240G 240GB SSD  | 6         | 1.06%   |
| Kingston SA400S37120G 120GB SSD  | 6         | 1.06%   |
| WDC WD10JPVX-22JC3T0 1TB         | 5         | 0.88%   |
| Unknown MMC Card  32GB           | 5         | 0.88%   |
| Seagate ST500LT012-1DG142 500GB  | 5         | 0.88%   |
| Seagate ST4000DM004-2CV104 4TB   | 5         | 0.88%   |
| Samsung SSD 860 EVO 250GB        | 5         | 0.88%   |
| Hitachi HTS543232A7A384 320GB    | 5         | 0.88%   |
| Hitachi HDS721050CLA362 500GB    | 5         | 0.88%   |
| WDC WD10EZEX-08WN4A0 1TB         | 4         | 0.7%    |
| Unknown MMC Card  64GB           | 4         | 0.7%    |
| Seagate ST500LT012-9WS142 500GB  | 4         | 0.7%    |
| Seagate ST2000LM007-1R8174 2TB   | 4         | 0.7%    |
| Seagate BUP Slim 2TB             | 4         | 0.7%    |
| Hitachi HDS721616PLA380 160GB    | 4         | 0.7%    |
| HGST HTS725050A7E630 500GB       | 4         | 0.7%    |
| WDC WD5000LPVX-22V0TT0 500GB     | 3         | 0.53%   |
| WDC WD5000LPCX-60VHAT0 500GB     | 3         | 0.53%   |
| WDC WD5000LPCX-24VHAT0 500GB     | 3         | 0.53%   |
| WDC WD5000AZLX-60K2TA0 500GB     | 3         | 0.53%   |
| WDC WD10EZEX-22MFCA0 1TB         | 3         | 0.53%   |
| Toshiba DT01ACA100 1TB           | 3         | 0.53%   |
| SK hynix NVMe SSD Drive 512GB    | 3         | 0.53%   |
| Seagate ST500LM030-2E717D 500GB  | 3         | 0.53%   |
| Seagate ST500DM002-1ER14C 500GB  | 3         | 0.53%   |
| Seagate ST3160812AS 160GB        | 3         | 0.53%   |
| Seagate ST1000LM049-2GH172 1TB   | 3         | 0.53%   |
| Seagate ST1000LM048-2E7172 1TB   | 3         | 0.53%   |
| SanDisk SDSSDA240G 240GB         | 3         | 0.53%   |
| Lexar 128GB SSD                  | 3         | 0.53%   |
| Kingston SV300S37A120G 120GB SSD | 3         | 0.53%   |
| HS-SSD-E100 SSD 512G             | 3         | 0.53%   |
| HGST HTS541010A9E680 1TB         | 3         | 0.53%   |
| A-DATA SU800 256GB SSD           | 3         | 0.53%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 2         | 0.35%   |
| WDC WD5003ABYZ-011FA0 500GB      | 2         | 0.35%   |
| WDC WD5000LPCX-24C6HT0 500GB     | 2         | 0.35%   |
| WDC WD3200BEVT-22ZCT0 320GB      | 2         | 0.35%   |
| WDC WD20EARX-00ZUDB0 2TB         | 2         | 0.35%   |
| WDC WD1600BEVT-24A23T0 160GB     | 2         | 0.35%   |
| WDC WD10SPZX-24Z10T0 1TB         | 2         | 0.35%   |
| WDC WD10SPZX-24Z10 1TB           | 2         | 0.35%   |
| WDC WD10EZEX-08M2NA0 1TB         | 2         | 0.35%   |
| WDC WD10EZEX-00BN5A0 1TB         | 2         | 0.35%   |
| Unknown SD/MMC/MS PRO 64GB       | 2         | 0.35%   |
| Unknown MMC Card  7GB            | 2         | 0.35%   |
| Unknown MMC Card  128GB          | 2         | 0.35%   |
| Transcend TS128GSSD370S 128GB    | 2         | 0.35%   |
| Toshiba THNSNJ128G8NU 128GB SSD  | 2         | 0.35%   |
| Toshiba MK3265GSX 320GB          | 2         | 0.35%   |
| Toshiba MK2555GSX 250GB          | 2         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 103       | 152    | 34.92%  |
| WDC                 | 85        | 101    | 28.81%  |
| Toshiba             | 54        | 68     | 18.31%  |
| Hitachi             | 29        | 48     | 9.83%   |
| HGST                | 12        | 13     | 4.07%   |
| Fujitsu             | 6         | 7      | 2.03%   |
| Unknown             | 3         | 4      | 1.02%   |
| Samsung Electronics | 2         | 3      | 0.68%   |
| SAGE                | 1         | 1      | 0.34%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 26        | 34     | 18.06%  |
| Kingston            | 21        | 26     | 14.58%  |
| SanDisk             | 14        | 15     | 9.72%   |
| WDC                 | 7         | 9      | 4.86%   |
| Team                | 7         | 10     | 4.86%   |
| Toshiba             | 6         | 9      | 4.17%   |
| A-DATA Technology   | 6         | 9      | 4.17%   |
| Transcend           | 4         | 4      | 2.78%   |
| SK hynix            | 4         | 16     | 2.78%   |
| Lexar               | 4         | 5      | 2.78%   |
| Intel               | 4         | 5      | 2.78%   |
| Ramsta              | 3         | 4      | 2.08%   |
| Micron Technology   | 3         | 3      | 2.08%   |
| HS-SSD-E100         | 3         | 3      | 2.08%   |
| Gigabyte Technology | 3         | 3      | 2.08%   |
| China               | 3         | 3      | 2.08%   |
| Apple               | 3         | 3      | 2.08%   |
| LITEONIT            | 2         | 3      | 1.39%   |
| Kingmax             | 2         | 2      | 1.39%   |
| Crucial             | 2         | 3      | 1.39%   |
| ZOTAC               | 1         | 1      | 0.69%   |
| WALRAM              | 1         | 1      | 0.69%   |
| Unknown             | 1         | 2      | 0.69%   |
| Teclast             | 1         | 4      | 0.69%   |
| TAMMUZ              | 1         | 1      | 0.69%   |
| PNY                 | 1         | 1      | 0.69%   |
| Plextor             | 1         | 1      | 0.69%   |
| Phison              | 1         | 1      | 0.69%   |
| OCZ                 | 1         | 1      | 0.69%   |
| KingSpec            | 1         | 1      | 0.69%   |
| Kimtigo             | 1         | 2      | 0.69%   |
| Hikvision           | 1         | 2      | 0.69%   |
| GLOWAY              | 1         | 1      | 0.69%   |
| FORESEE             | 1         | 1      | 0.69%   |
| Colorful            | 1         | 1      | 0.69%   |
| ASUS-PHISON         | 1         | 2      | 0.69%   |
| Argon               | 1         | 2      | 0.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 259       | 397    | 54.3%   |
| SSD     | 127       | 194    | 26.62%  |
| NVMe    | 60        | 70     | 12.58%  |
| MMC     | 21        | 26     | 4.4%    |
| Unknown | 10        | 13     | 2.1%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 331       | 569    | 76.27%  |
| NVMe | 60        | 70     | 13.82%  |
| SAS  | 22        | 35     | 5.07%   |
| MMC  | 21        | 26     | 4.84%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 263       | 410    | 67.96%  |
| 0.51-1.0   | 94        | 142    | 24.29%  |
| 1.01-2.0   | 19        | 26     | 4.91%   |
| 3.01-4.0   | 9         | 11     | 2.33%   |
| 4.01-10.0  | 2         | 2      | 0.52%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 110       | 27.3%   |
| 251-500        | 109       | 27.05%  |
| 501-1000       | 51        | 12.66%  |
| 1-20           | 29        | 7.2%    |
| 51-100         | 29        | 7.2%    |
| 1001-2000      | 27        | 6.7%    |
| 21-50          | 16        | 3.97%   |
| Unknown        | 12        | 2.98%   |
| More than 3000 | 11        | 2.73%   |
| 2001-3000      | 9         | 2.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 170       | 40.57%  |
| 21-50          | 77        | 18.38%  |
| 51-100         | 56        | 13.37%  |
| 101-250        | 55        | 13.13%  |
| 251-500        | 21        | 5.01%   |
| 501-1000       | 15        | 3.58%   |
| Unknown        | 12        | 2.86%   |
| 1001-2000      | 6         | 1.43%   |
| 2001-3000      | 5         | 1.19%   |
| More than 3000 | 2         | 0.48%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Hitachi HDS721050CLA362 500GB                  | 5         | 10     | 11.11%  |
| Hitachi HTS543232A7A384 320GB                  | 3         | 5      | 6.67%   |
| Toshiba MQ01ABD100 1TB                         | 2         | 2      | 4.44%   |
| Seagate ST2000LM007-1R8174 2TB                 | 2         | 3      | 4.44%   |
| Seagate ST1000LM048-2E7172 1TB                 | 2         | 2      | 4.44%   |
| WDC WD5003ABYZ-011FA0 500GB                    | 1         | 1      | 2.22%   |
| WDC WD5000LPVT-75G33T0 500GB                   | 1         | 1      | 2.22%   |
| WDC WD5000LPVT-22G33T0 500GB                   | 1         | 1      | 2.22%   |
| WDC WD5000AAKX-603CA0 500GB                    | 1         | 1      | 2.22%   |
| WDC WD3200BEVT-22A23T0 320GB                   | 1         | 1      | 2.22%   |
| WDC WD3200AAJS-08L7A0 320GB                    | 1         | 1      | 2.22%   |
| WDC WD1600BEVT-24A23T0 160GB                   | 1         | 1      | 2.22%   |
| Unknown S050 Hard drive 500GB                  | 1         | 1      | 2.22%   |
| Toshiba MQ01ABF050 500GB                       | 1         | 1      | 2.22%   |
| Toshiba MK6465GSX 640GB                        | 1         | 1      | 2.22%   |
| Toshiba MK3259GSXP 320GB                       | 1         | 1      | 2.22%   |
| Toshiba DT01ACA100 1TB                         | 1         | 1      | 2.22%   |
| Toshiba DT01ACA050 500GB                       | 1         | 1      | 2.22%   |
| SK hynix HFS128G3AMNB-2200A 128GB SSD          | 1         | 1      | 2.22%   |
| Seagate ST9250315AS 250GB                      | 1         | 1      | 2.22%   |
| Seagate ST9120821AS 120GB                      | 1         | 1      | 2.22%   |
| Seagate ST500DM002-1BD142 500GB                | 1         | 2      | 2.22%   |
| Seagate ST380815AS 80GB                        | 1         | 1      | 2.22%   |
| Seagate ST3500514NS 500GB                      | 1         | 1      | 2.22%   |
| Seagate ST3500418AS 500GB                      | 1         | 1      | 2.22%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 2.22%   |
| Kingston SV300S37A120G 120GB SSD               | 1         | 1      | 2.22%   |
| Hitachi HTS723232A7A364 320GB                  | 1         | 2      | 2.22%   |
| Hitachi HTS545050B9SA00 500GB                  | 1         | 1      | 2.22%   |
| Hitachi HTS542525K9SA00 250GB                  | 1         | 1      | 2.22%   |
| Hitachi HDS721050CLA660 500GB                  | 1         | 1      | 2.22%   |
| HGST HTS721010A9E630 1TB                       | 1         | 1      | 2.22%   |
| HGST HTS541010A9E680 1TB                       | 1         | 1      | 2.22%   |
| Fujitsu MHY2120BH 120GB                        | 1         | 1      | 2.22%   |
| Colorful SL300 128GB SSD                       | 1         | 1      | 2.22%   |
| A-DATA Technology SX6000PNP 512GB              | 1         | 1      | 2.22%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 10        | 12     | 24.39%  |
| Hitachi           | 9         | 20     | 21.95%  |
| WDC               | 7         | 7      | 17.07%  |
| Toshiba           | 6         | 7      | 14.63%  |
| HGST              | 2         | 2      | 4.88%   |
| Unknown           | 1         | 1      | 2.44%   |
| SK hynix          | 1         | 1      | 2.44%   |
| Micron Technology | 1         | 1      | 2.44%   |
| Kingston          | 1         | 1      | 2.44%   |
| Fujitsu           | 1         | 1      | 2.44%   |
| Colorful          | 1         | 1      | 2.44%   |
| A-DATA Technology | 1         | 1      | 2.44%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 10        | 12     | 27.78%  |
| Hitachi | 9         | 20     | 25%     |
| WDC     | 7         | 7      | 19.44%  |
| Toshiba | 6         | 7      | 16.67%  |
| HGST    | 2         | 2      | 5.56%   |
| Unknown | 1         | 1      | 2.78%   |
| Fujitsu | 1         | 1      | 2.78%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 32        | 50     | 86.49%  |
| SSD  | 4         | 4      | 10.81%  |
| NVMe | 1         | 1      | 2.7%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                    | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| WDC WD10SPZX-21Z10T0 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 257       | 472    | 63.93%  |
| Works    | 108       | 172    | 26.87%  |
| Malfunc  | 36        | 55     | 8.96%   |
| Failed   | 1         | 1      | 0.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 266       | 64.41%  |
| AMD                              | 70        | 16.95%  |
| Nvidia                           | 14        | 3.39%   |
| Samsung Electronics              | 12        | 2.91%   |
| SK hynix                         | 8         | 1.94%   |
| Phison Electronics               | 6         | 1.45%   |
| SanDisk                          | 5         | 1.21%   |
| Toshiba America Info Systems     | 3         | 0.73%   |
| Silicon Motion                   | 3         | 0.73%   |
| Silicon Integrated Systems [SiS] | 3         | 0.73%   |
| Micron/Crucial Technology        | 3         | 0.73%   |
| Micron Technology                | 3         | 0.73%   |
| Kingston Technology Company      | 3         | 0.73%   |
| Solid State Storage Technology   | 2         | 0.48%   |
| Realtek Semiconductor            | 2         | 0.48%   |
| Marvell Technology Group         | 2         | 0.48%   |
| ADATA Technology                 | 2         | 0.48%   |
| Union Memory (Shenzhen)          | 1         | 0.24%   |
| Lite-On Technology               | 1         | 0.24%   |
| Lenovo                           | 1         | 0.24%   |
| KIOXIA                           | 1         | 0.24%   |
| Broadcom / LSI                   | 1         | 0.24%   |
| ASMedia Technology               | 1         | 0.24%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 48        | 9.82%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 29        | 5.93%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 23        | 4.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 19        | 3.89%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 16        | 3.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 16        | 3.27%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 13        | 2.66%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 13        | 2.66%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 13        | 2.66%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 10        | 2.04%   |
| AMD 400 Series Chipset SATA Controller                                                  | 9         | 1.84%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 8         | 1.64%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 8         | 1.64%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 8         | 1.64%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 8         | 1.64%   |
| Nvidia MCP61 SATA Controller                                                            | 7         | 1.43%   |
| Nvidia MCP61 IDE                                                                        | 7         | 1.43%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 7         | 1.43%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7         | 1.43%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7         | 1.43%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 7         | 1.43%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6         | 1.23%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 6         | 1.23%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 6         | 1.23%   |
| AMD FCH IDE Controller                                                                  | 6         | 1.23%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5         | 1.02%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 5         | 1.02%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 5         | 1.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 5         | 1.02%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 5         | 1.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 5         | 1.02%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5         | 1.02%   |
| AMD FCH SATA Controller D                                                               | 5         | 1.02%   |
| Samsung NVMe SSD Controller 980                                                         | 4         | 0.82%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 4         | 0.82%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4         | 0.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4         | 0.82%   |
| SK hynix Gold P31 SSD                                                                   | 3         | 0.61%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 3         | 0.61%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3         | 0.61%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 3         | 0.61%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 3         | 0.61%   |
| Nvidia MCP79 AHCI Controller                                                            | 3         | 0.61%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 3         | 0.61%   |
| Micron Non-Volatile memory controller                                                   | 3         | 0.61%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3         | 0.61%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3         | 0.61%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3         | 0.61%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3         | 0.61%   |
| Solid State Storage Non-Volatile memory controller                                      | 2         | 0.41%   |
| SK hynix Non-Volatile memory controller                                                 | 2         | 0.41%   |
| Silicon Integrated Systems [SiS] AHCI IDE Controller (0106)                             | 2         | 0.41%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 0.41%   |
| Realtek Realtek Non-Volatile memory controller                                          | 2         | 0.41%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 2         | 0.41%   |
| Intel SATA Controller [RAID mode]                                                       | 2         | 0.41%   |
| Intel Non-Volatile memory controller                                                    | 2         | 0.41%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 2         | 0.41%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 0.41%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                    | 2         | 0.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 291       | 67.21%  |
| NVMe | 60        | 13.86%  |
| IDE  | 58        | 13.39%  |
| RAID | 23        | 5.31%   |
| SAS  | 1         | 0.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 285       | 75.6%   |
| AMD    | 85        | 22.55%  |
| ARM    | 7         | 1.86%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-7500U CPU @ 2.70GHz             | 7         | 1.86%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 7         | 1.86%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 7         | 1.86%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 6         | 1.59%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.33%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 5         | 1.33%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 1.06%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 4         | 1.06%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 4         | 1.06%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 4         | 1.06%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 4         | 1.06%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 1.06%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 4         | 1.06%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 4         | 1.06%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 4         | 1.06%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 0.8%    |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 0.8%    |
| Intel Celeron N4000 CPU @ 1.10GHz             | 3         | 0.8%    |
| Intel Celeron CPU N3160 @ 1.60GHz             | 3         | 0.8%    |
| Intel Atom CPU N450 @ 1.66GHz                 | 3         | 0.8%    |
| ARM Processor                                 | 3         | 0.8%    |
| AMD Sempron Processor LE-1100                 | 3         | 0.8%    |
| AMD Ryzen 5 3600 6-Core Processor             | 3         | 0.8%    |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 3         | 0.8%    |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 3         | 0.8%    |
| AMD A8-7600 Radeon R7, 10 Compute Cores 4C+6G | 3         | 0.8%    |
| AMD A6-6400K APU with Radeon HD Graphics      | 3         | 0.8%    |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 2         | 0.53%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 2         | 0.53%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.53%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 2         | 0.53%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.53%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 2         | 0.53%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz            | 2         | 0.53%   |
| Intel Core i7-3770S CPU @ 3.10GHz             | 2         | 0.53%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 2         | 0.53%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 0.53%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.53%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 2         | 0.53%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.53%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 2         | 0.53%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 2         | 0.53%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.53%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2         | 0.53%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 0.53%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 0.53%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 0.53%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 2         | 0.53%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 2         | 0.53%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 0.53%   |
| Intel Core i3-4170 CPU @ 3.70GHz              | 2         | 0.53%   |
| Intel Core i3-3227U CPU @ 1.90GHz             | 2         | 0.53%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 2         | 0.53%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 0.53%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 2         | 0.53%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 2         | 0.53%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 0.53%   |
| Intel Core i3 CPU M 350 @ 2.27GHz             | 2         | 0.53%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz         | 2         | 0.53%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz          | 2         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 90        | 23.87%  |
| Intel Core i7           | 55        | 14.59%  |
| Intel Core i3           | 37        | 9.81%   |
| Intel Celeron           | 37        | 9.81%   |
| AMD Ryzen 5             | 20        | 5.31%   |
| Intel Core 2 Duo        | 17        | 4.51%   |
| Other                   | 16        | 4.24%   |
| Intel Atom              | 11        | 2.92%   |
| AMD Ryzen 7             | 10        | 2.65%   |
| Intel Pentium Dual-Core | 8         | 2.12%   |
| Intel Pentium           | 8         | 2.12%   |
| AMD A8                  | 8         | 2.12%   |
| AMD A6                  | 8         | 2.12%   |
| AMD Ryzen 3             | 5         | 1.33%   |
| AMD A10                 | 5         | 1.33%   |
| AMD FX                  | 4         | 1.06%   |
| AMD Athlon              | 4         | 1.06%   |
| Intel Core 2 Quad       | 3         | 0.8%    |
| AMD Sempron             | 3         | 0.8%    |
| Intel Pentium Gold      | 2         | 0.53%   |
| AMD Turion 64 X2 Mobile | 2         | 0.53%   |
| AMD Phenom II X4        | 2         | 0.53%   |
| AMD Athlon II X2        | 2         | 0.53%   |
| AMD A4                  | 2         | 0.53%   |
| Intel Xeon              | 1         | 0.27%   |
| Intel Pentium Silver    | 1         | 0.27%   |
| Intel Pentium Dual      | 1         | 0.27%   |
| Intel Genuine           | 1         | 0.27%   |
| Intel Core m3           | 1         | 0.27%   |
| Intel Core i9           | 1         | 0.27%   |
| Intel Core 2            | 1         | 0.27%   |
| Intel Celeron M         | 1         | 0.27%   |
| ARM BCM                 | 1         | 0.27%   |
| AMD Ryzen 9             | 1         | 0.27%   |
| AMD Quad-Core           | 1         | 0.27%   |
| AMD PRO A10             | 1         | 0.27%   |
| AMD Phenom II X2        | 1         | 0.27%   |
| AMD G                   | 1         | 0.27%   |
| AMD E2                  | 1         | 0.27%   |
| AMD E1                  | 1         | 0.27%   |
| AMD C-60                | 1         | 0.27%   |
| AMD Athlon 64 X2        | 1         | 0.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 184       | 48.81%  |
| 4      | 131       | 34.75%  |
| 6      | 25        | 6.63%   |
| 1      | 20        | 5.31%   |
| 8      | 13        | 3.45%   |
| 16     | 1         | 0.27%   |
| 14     | 1         | 0.27%   |
| 10     | 1         | 0.27%   |
| 3      | 1         | 0.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 376       | 99.73%  |
| 2      | 1         | 0.27%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 235       | 62.33%  |
| 1      | 142       | 37.67%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 362       | 95.26%  |
| Unknown        | 14        | 3.68%   |
| 32-bit         | 3         | 0.79%   |
| 64-bit         | 1         | 0.26%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 90        | 23.38%  |
| 0x306a9    | 27        | 7.01%   |
| 0x206a7    | 22        | 5.71%   |
| 0x1067a    | 20        | 5.19%   |
| 0x306c3    | 17        | 4.42%   |
| 0x806ea    | 11        | 2.86%   |
| 0x506c9    | 11        | 2.86%   |
| 0x906ea    | 9         | 2.34%   |
| 0x406e3    | 9         | 2.34%   |
| 0x806e9    | 8         | 2.08%   |
| 0x30678    | 8         | 2.08%   |
| 0x806ec    | 7         | 1.82%   |
| 0x40651    | 7         | 1.82%   |
| 0x306d4    | 7         | 1.82%   |
| 0x06003106 | 7         | 1.82%   |
| 0x06001119 | 7         | 1.82%   |
| 0x906e9    | 6         | 1.56%   |
| 0x506e3    | 6         | 1.56%   |
| 0x10676    | 6         | 1.56%   |
| 0x706a1    | 5         | 1.3%    |
| 0x406c4    | 5         | 1.3%    |
| 0x08701021 | 5         | 1.3%    |
| 0x0800820d | 5         | 1.3%    |
| 0xa0652    | 4         | 1.04%   |
| 0x20655    | 4         | 1.04%   |
| 0x106ca    | 4         | 1.04%   |
| 0xa0671    | 3         | 0.78%   |
| 0x806c1    | 3         | 0.78%   |
| 0x406c3    | 3         | 0.78%   |
| 0x20652    | 3         | 0.78%   |
| 0x0a50000c | 3         | 0.78%   |
| 0x08600106 | 3         | 0.78%   |
| 0x0810100b | 3         | 0.78%   |
| 0x07030105 | 3         | 0.78%   |
| 0x0700010f | 3         | 0.78%   |
| 0x6fb      | 2         | 0.52%   |
| 0x30661    | 2         | 0.52%   |
| 0x08608103 | 2         | 0.52%   |
| 0x08108109 | 2         | 0.52%   |
| 0x0600611a | 2         | 0.52%   |
| 0x010000c8 | 2         | 0.52%   |
| 0xa0660    | 1         | 0.26%   |
| 0xa0655    | 1         | 0.26%   |
| 0xa0653    | 1         | 0.26%   |
| 0x906ed    | 1         | 0.26%   |
| 0x906a3    | 1         | 0.26%   |
| 0x90675    | 1         | 0.26%   |
| 0x806eb    | 1         | 0.26%   |
| 0x706e5    | 1         | 0.26%   |
| 0x706a8    | 1         | 0.26%   |
| 0x6fd      | 1         | 0.26%   |
| 0x6f6      | 1         | 0.26%   |
| 0x6ec      | 1         | 0.26%   |
| 0x6d8      | 1         | 0.26%   |
| 0x50654    | 1         | 0.26%   |
| 0x406f1    | 1         | 0.26%   |
| 0x30679    | 1         | 0.26%   |
| 0x106e5    | 1         | 0.26%   |
| 0x106c2    | 1         | 0.26%   |
| 0x08600104 | 1         | 0.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 56        | 14.85%  |
| IvyBridge        | 34        | 9.02%   |
| Haswell          | 31        | 8.22%   |
| Penryn           | 28        | 7.43%   |
| SandyBridge      | 24        | 6.37%   |
| Skylake          | 20        | 5.31%   |
| Silvermont       | 17        | 4.51%   |
| Zen+             | 14        | 3.71%   |
| Piledriver       | 13        | 3.45%   |
| Goldmont         | 13        | 3.45%   |
| CometLake        | 11        | 2.92%   |
| Unknown          | 11        | 2.92%   |
| Zen 2            | 10        | 2.65%   |
| Broadwell        | 10        | 2.65%   |
| Westmere         | 9         | 2.39%   |
| Zen              | 8         | 2.12%   |
| Steamroller      | 8         | 2.12%   |
| Bonnell          | 8         | 2.12%   |
| K8 Hammer        | 7         | 1.86%   |
| Goldmont plus    | 6         | 1.59%   |
| K10              | 5         | 1.33%   |
| Puma             | 4         | 1.06%   |
| Excavator        | 4         | 1.06%   |
| Core             | 4         | 1.06%   |
| Zen 3            | 3         | 0.8%    |
| TigerLake        | 3         | 0.8%    |
| Jaguar           | 3         | 0.8%    |
| Icelake          | 3         | 0.8%    |
| P6               | 2         | 0.53%   |
| Nehalem          | 2         | 0.53%   |
| Bobcat           | 2         | 0.53%   |
| Alderlake Hybrid | 2         | 0.53%   |
| K8 & K10 hybrid  | 1         | 0.27%   |
| K10 Llano        | 1         | 0.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 240       | 52.98%  |
| Nvidia                           | 116       | 25.61%  |
| AMD                              | 94        | 20.75%  |
| Silicon Integrated Systems [SiS] | 3         | 0.66%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 25        | 5.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 22        | 4.71%   |
| Intel UHD Graphics 620                                                                   | 13        | 2.78%   |
| Intel HD Graphics 500                                                                    | 13        | 2.78%   |
| Intel HD Graphics 620                                                                    | 12        | 2.57%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 1.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 1.93%   |
| Intel HD Graphics 5500                                                                   | 8         | 1.71%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 1.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 1.71%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 7         | 1.5%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 1.5%    |
| Intel HD Graphics 630                                                                    | 7         | 1.5%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 1.5%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 7         | 1.5%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 1.5%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 6         | 1.28%   |
| Nvidia G72 [GeForce 7200 GS / 7300 SE]                                                   | 6         | 1.28%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6         | 1.28%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 1.28%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 1.28%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 1.28%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 6         | 1.28%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6         | 1.28%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 5         | 1.07%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.07%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 1.07%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 5         | 1.07%   |
| AMD Renoir                                                                               | 5         | 1.07%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.86%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 4         | 0.86%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 0.86%   |
| Intel HD Graphics 530                                                                    | 4         | 0.86%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 4         | 0.86%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 4         | 0.86%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 4         | 0.86%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 4         | 0.86%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 3         | 0.64%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 0.64%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 0.64%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 0.64%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 0.64%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.64%   |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 0.64%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 3         | 0.64%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 3         | 0.64%   |
| Nvidia C79 [GeForce 9400M]                                                               | 3         | 0.64%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 0.64%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 0.64%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 3         | 0.64%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 0.64%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 3         | 0.64%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 0.64%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 0.64%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 3         | 0.64%   |
| AMD Richland [Radeon HD 8470D]                                                           | 3         | 0.64%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 0.64%   |
| AMD Cezanne                                                                              | 3         | 0.64%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 3         | 0.64%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 2         | 0.43%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 170       | 44.39%  |
| 1 x AMD        | 67        | 17.49%  |
| 1 x Nvidia     | 57        | 14.88%  |
| Intel + Nvidia | 50        | 13.05%  |
| Intel + AMD    | 14        | 3.66%   |
| Other          | 7         | 1.83%   |
| 2 x AMD        | 7         | 1.83%   |
| AMD + Nvidia   | 6         | 1.57%   |
| 1 x SiS        | 3         | 0.78%   |
| 2 x Nvidia     | 2         | 0.52%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 296       | 77.49%  |
| Proprietary | 65        | 17.02%  |
| Unknown     | 21        | 5.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 235       | 60.26%  |
| 1.01-2.0   | 46        | 11.79%  |
| 0.01-0.5   | 36        | 9.23%   |
| 0.51-1.0   | 30        | 7.69%   |
| 3.01-4.0   | 24        | 6.15%   |
| 5.01-6.0   | 8         | 2.05%   |
| 7.01-8.0   | 6         | 1.54%   |
| 8.01-16.0  | 3         | 0.77%   |
| 2.01-3.0   | 2         | 0.51%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 51        | 12.91%  |
| Chimei Innolux          | 45        | 11.39%  |
| AU Optronics            | 45        | 11.39%  |
| BOE                     | 36        | 9.11%   |
| LG Display              | 27        | 6.84%   |
| Dell                    | 25        | 6.33%   |
| Acer                    | 17        | 4.3%    |
| AOC                     | 16        | 4.05%   |
| Lenovo                  | 14        | 3.54%   |
| Hewlett-Packard         | 9         | 2.28%   |
| Goldstar                | 9         | 2.28%   |
| Ancor Communications    | 9         | 2.28%   |
| ASUSTek Computer        | 7         | 1.77%   |
| Sony                    | 6         | 1.52%   |
| InfoVision              | 6         | 1.52%   |
| BenQ                    | 6         | 1.52%   |
| Apple                   | 6         | 1.52%   |
| Sharp                   | 5         | 1.27%   |
| Philips                 | 5         | 1.27%   |
| ViewSonic               | 4         | 1.01%   |
| IPS                     | 3         | 0.76%   |
| VIE                     | 2         | 0.51%   |
| Unknown                 | 2         | 0.51%   |
| RTK                     | 2         | 0.51%   |
| PANDA                   | 2         | 0.51%   |
| MStar                   | 2         | 0.51%   |
| Mi                      | 2         | 0.51%   |
| LG Philips              | 2         | 0.51%   |
| InnoLux Display         | 2         | 0.51%   |
| eMachines               | 2         | 0.51%   |
| Eizo                    | 2         | 0.51%   |
| CTV                     | 2         | 0.51%   |
| Unknown                 | 2         | 0.51%   |
| ___                     | 1         | 0.25%   |
| Toshiba                 | 1         | 0.25%   |
| TMX                     | 1         | 0.25%   |
| SMC                     | 1         | 0.25%   |
| SGT                     | 1         | 0.25%   |
| Pixio                   | 1         | 0.25%   |
| Panasonic               | 1         | 0.25%   |
| NVISION                 | 1         | 0.25%   |
| NVI                     | 1         | 0.25%   |
| NEX                     | 1         | 0.25%   |
| MSI                     | 1         | 0.25%   |
| KTC                     | 1         | 0.25%   |
| HON                     | 1         | 0.25%   |
| HannStar                | 1         | 0.25%   |
| GDH                     | 1         | 0.25%   |
| ELSA International      | 1         | 0.25%   |
| CSO                     | 1         | 0.25%   |
| COS                     | 1         | 0.25%   |
| Chi Mei Optoelectronics | 1         | 0.25%   |
| AUS                     | 1         | 0.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 7         | 1.73%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 5         | 1.23%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 5         | 1.23%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                        | 5         | 1.23%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 4         | 0.99%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 4         | 0.99%   |
| Dell SE177FP DELF001 1280x1024 338x270mm 17.0-inch                    | 4         | 0.99%   |
| AOC 2060W3 AOC2060 1920x1080 435x239mm 19.5-inch                      | 4         | 0.99%   |
| Ancor Communications ASUS VC239 ACI23C4 1920x1080 509x286mm 23.0-inch | 4         | 0.99%   |
| Lenovo LT1952p Wide LEN0990 1440x900 408x255mm 18.9-inch              | 3         | 0.74%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch               | 3         | 0.74%   |
| Dell P170S DEL4058 1280x1024 338x270mm 17.0-inch                      | 3         | 0.74%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 3         | 0.74%   |
| BOE LCD Monitor BOE06BD 1366x768 309x173mm 13.9-inch                  | 3         | 0.74%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 0.74%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 3         | 0.74%   |
| VIE A/G1956 VIE1850 1366x768 414x257mm 19.2-inch                      | 2         | 0.49%   |
| Sony TV SNYAB03 1920x1080                                             | 2         | 0.49%   |
| Sony TV SNYA301 1920x1080                                             | 2         | 0.49%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 2         | 0.49%   |
| Samsung Electronics LCD Monitor SEC3549 1366x768 309x174mm 14.0-inch  | 2         | 0.49%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x193mm 15.5-inch  | 2         | 0.49%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 2         | 0.49%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 309x174mm 14.0-inch | 2         | 0.49%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2         | 0.49%   |
| RTK 32V3H-H6A RTK4C54 1440x900 697x392mm 31.5-inch                    | 2         | 0.49%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                        | 2         | 0.49%   |
| Mi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                      | 2         | 0.49%   |
| LG Display LP101WSA-TLN1 LGD0295 1024x600 224x126mm 10.1-inch         | 2         | 0.49%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch           | 2         | 0.49%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch           | 2         | 0.49%   |
| Lenovo LCD Monitor LEN40A0 1366x768 309x174mm 14.0-inch               | 2         | 0.49%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                      | 2         | 0.49%   |
| Dell P2214H DELA097 1920x1080 477x268mm 21.5-inch                     | 2         | 0.49%   |
| Dell OptiPlex 9010 DEL1111 1920x1080 510x286mm 23.0-inch              | 2         | 0.49%   |
| Dell E207WFP DELD010 1680x1050 430x270mm 20.0-inch                    | 2         | 0.49%   |
| Dell E198FP DELA028 1280x1024 376x301mm 19.0-inch                     | 2         | 0.49%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 0.49%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 0.49%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 2         | 0.49%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch       | 2         | 0.49%   |
| BOE LCD Monitor BOE08B3 1920x1080 344x193mm 15.5-inch                 | 2         | 0.49%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                 | 2         | 0.49%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 2         | 0.49%   |
| BenQ GW2780 BNQ78E6 1920x1080 598x336mm 27.0-inch                     | 2         | 0.49%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch         | 2         | 0.49%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.49%   |
| AU Optronics LCD Monitor AUO30D2 1024x600 223x125mm 10.1-inch         | 2         | 0.49%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch         | 2         | 0.49%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 2         | 0.49%   |
| ASUSTek Computer VG27AQL1A AUS2705 2560x1440 600x340mm 27.2-inch      | 2         | 0.49%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                  | 2         | 0.49%   |
| Acer R230H ACR046E 1920x1080 509x286mm 23.0-inch                      | 2         | 0.49%   |
| Acer EB192Q ACR0517 1366x768 410x230mm 18.5-inch                      | 2         | 0.49%   |
| Unknown                                                               | 2         | 0.49%   |
| ___ LCD TV ___9000 1360x768                                           | 1         | 0.25%   |
| ViewSonic XG2705 VSC0E39 1920x1080 598x336mm 27.0-inch                | 1         | 0.25%   |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch         | 1         | 0.25%   |
| ViewSonic VA1917 SERIES VSCAD30 1366x768 410x230mm 18.5-inch          | 1         | 0.25%   |
| ViewSonic VA1601W-LED VSC1A25 1366x768 344x193mm 15.5-inch            | 1         | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 140       | 37.23%  |
| 1920x1080 (FHD)    | 137       | 36.44%  |
| 1600x900 (HD+)     | 23        | 6.12%   |
| 1280x1024 (SXGA)   | 19        | 5.05%   |
| 3840x2160 (4K)     | 13        | 3.46%   |
| 1440x900 (WXGA+)   | 8         | 2.13%   |
| 1280x800 (WXGA)    | 6         | 1.6%    |
| 1024x600           | 6         | 1.6%    |
| 1920x1200 (WUXGA)  | 5         | 1.33%   |
| 2560x1440 (QHD)    | 4         | 1.06%   |
| 1360x768           | 4         | 1.06%   |
| 3440x1440          | 2         | 0.53%   |
| 1680x1050 (WSXGA+) | 2         | 0.53%   |
| 3200x1080          | 1         | 0.27%   |
| 2560x1600          | 1         | 0.27%   |
| 2400x1600          | 1         | 0.27%   |
| 2160x1440          | 1         | 0.27%   |
| 1920x540           | 1         | 0.27%   |
| 1600x1200          | 1         | 0.27%   |
| Unknown            | 1         | 0.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 90        | 22.67%  |
| 13      | 47        | 11.84%  |
| 18      | 31        | 7.81%   |
| 14      | 31        | 7.81%   |
| 23      | 30        | 7.56%   |
| 17      | 28        | 7.05%   |
| 21      | 17        | 4.28%   |
| 11      | 17        | 4.28%   |
| 27      | 14        | 3.53%   |
| 20      | 14        | 3.53%   |
| Unknown | 14        | 3.53%   |
| 24      | 12        | 3.02%   |
| 19      | 12        | 3.02%   |
| 12      | 9         | 2.27%   |
| 72      | 7         | 1.76%   |
| 31      | 6         | 1.51%   |
| 10      | 6         | 1.51%   |
| 52      | 3         | 0.76%   |
| 32      | 3         | 0.76%   |
| 40      | 2         | 0.5%    |
| 47      | 1         | 0.25%   |
| 34      | 1         | 0.25%   |
| 22      | 1         | 0.25%   |
| 16      | 1         | 0.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 166       | 42.78%  |
| 401-500     | 68        | 17.53%  |
| 501-600     | 53        | 13.66%  |
| 201-300     | 46        | 11.86%  |
| 351-400     | 17        | 4.38%   |
| Unknown     | 14        | 3.61%   |
| 601-700     | 7         | 1.8%    |
| 1501-2000   | 7         | 1.8%    |
| 701-800     | 4         | 1.03%   |
| 1001-1500   | 4         | 1.03%   |
| 801-900     | 2         | 0.52%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 301       | 83.84%  |
| 16/10   | 25        | 6.96%   |
| 5/4     | 17        | 4.74%   |
| Unknown | 13        | 3.62%   |
| 6/5     | 1         | 0.28%   |
| 3/2     | 1         | 0.28%   |
| 21/9    | 1         | 0.28%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 87        | 22.31%  |
| 81-90          | 65        | 16.67%  |
| 201-250        | 47        | 12.05%  |
| 141-150        | 44        | 11.28%  |
| 151-200        | 31        | 7.95%   |
| 51-60          | 17        | 4.36%   |
| 301-350        | 14        | 3.59%   |
| Unknown        | 14        | 3.59%   |
| 71-80          | 13        | 3.33%   |
| 121-130        | 12        | 3.08%   |
| More than 1000 | 10        | 2.56%   |
| 351-500        | 10        | 2.56%   |
| 61-70          | 9         | 2.31%   |
| 41-50          | 6         | 1.54%   |
| 251-300        | 3         | 0.77%   |
| 501-1000       | 3         | 0.77%   |
| 91-100         | 3         | 0.77%   |
| 131-140        | 1         | 0.26%   |
| 111-120        | 1         | 0.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 133       | 34.73%  |
| 51-100        | 120       | 31.33%  |
| 121-160       | 92        | 24.02%  |
| Unknown       | 14        | 3.66%   |
| 1-50          | 12        | 3.13%   |
| 161-240       | 9         | 2.35%   |
| More than 240 | 3         | 0.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 316       | 81.87%  |
| 2     | 46        | 11.92%  |
| 0     | 21        | 5.44%   |
| 3     | 3         | 0.78%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 226       | 40.57%  |
| Intel                                 | 134       | 24.06%  |
| Qualcomm Atheros                      | 81        | 14.54%  |
| Broadcom                              | 39        | 7%      |
| Ralink Technology                     | 18        | 3.23%   |
| Nvidia                                | 10        | 1.8%    |
| TP-Link                               | 6         | 1.08%   |
| Broadcom Limited                      | 5         | 0.9%    |
| Marvell Technology Group              | 4         | 0.72%   |
| Silicon Integrated Systems [SiS]      | 3         | 0.54%   |
| Samsung Electronics                   | 3         | 0.54%   |
| JMicron Technology                    | 3         | 0.54%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.54%   |
| Xiaomi                                | 2         | 0.36%   |
| Qualcomm Atheros Communications       | 2         | 0.36%   |
| OPPO Electronics                      | 2         | 0.36%   |
| Huawei Technologies                   | 2         | 0.36%   |
| D-Link                                | 2         | 0.36%   |
| Sundance Technology Inc / IC Plus     | 1         | 0.18%   |
| Realtek                               | 1         | 0.18%   |
| Qualcomm                              | 1         | 0.18%   |
| NetGear                               | 1         | 0.18%   |
| MediaTek                              | 1         | 0.18%   |
| ICS Advent                            | 1         | 0.18%   |
| Hewlett-Packard                       | 1         | 0.18%   |
| Encore Electronics                    | 1         | 0.18%   |
| Dell                                  | 1         | 0.18%   |
| D-Link System                         | 1         | 0.18%   |
| BUFFALO                               | 1         | 0.18%   |
| ASIX Electronics                      | 1         | 0.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                                  | Computers | Percent |
|--------------------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                                      | 169       | 26.16%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                                  | 35        | 5.42%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                             | 15        | 2.32%   |
| Intel Wireless 7265                                                                                    | 15        | 2.32%   |
| Ralink MT7601U Wireless Adapter                                                                        | 12        | 1.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                             | 12        | 1.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                                  | 12        | 1.86%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                                        | 11        | 1.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                                       | 11        | 1.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                         | 10        | 1.55%   |
| Intel Wireless 3165                                                                                    | 10        | 1.55%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                                    | 9         | 1.39%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                                       | 8         | 1.24%   |
| Intel Wi-Fi 6 AX200                                                                                    | 8         | 1.24%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                           | 8         | 1.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                                       | 7         | 1.08%   |
| Intel Wireless 7260                                                                                    | 6         | 0.93%   |
| Intel Comet Lake PCH CNVi WiFi                                                                         | 6         | 0.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                                                        | 6         | 0.93%   |
| Broadcom BCM43142 802.11b/g/n                                                                          | 6         | 0.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                               | 5         | 0.77%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                               | 5         | 0.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                             | 5         | 0.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                                          | 5         | 0.77%   |
| Nvidia MCP61 Ethernet                                                                                  | 5         | 0.77%   |
| Realtek RTL8125 2.5GbE Controller                                                                      | 4         | 0.62%   |
| Realtek 802.11ac NIC                                                                                   | 4         | 0.62%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                                              | 4         | 0.62%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                                             | 4         | 0.62%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                                                  | 4         | 0.62%   |
| Intel Wireless 8265 / 8275                                                                             | 4         | 0.62%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                                      | 4         | 0.62%   |
| Intel Centrino Advanced-N 6235                                                                         | 4         | 0.62%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                                        | 4         | 0.62%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                                          | 3         | 0.46%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                                        | 3         | 0.46%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                                    | 3         | 0.46%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                                               | 3         | 0.46%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                                                       | 3         | 0.46%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                                | 3         | 0.46%   |
| Intel Wireless 8260                                                                                    | 3         | 0.46%   |
| Intel Wi-Fi 6 AX201                                                                                    | 3         | 0.46%   |
| Intel I211 Gigabit Network Connection                                                                  | 3         | 0.46%   |
| Intel Ethernet Controller I225-V                                                                       | 3         | 0.46%   |
| Intel Ethernet Connection I217-V                                                                       | 3         | 0.46%   |
| Intel Ethernet Connection (3) I218-LM                                                                  | 3         | 0.46%   |
| Intel Ethernet Connection (10) I219-V                                                                  | 3         | 0.46%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                                        | 3         | 0.46%   |
| Intel Centrino Wireless-N 2200                                                                         | 3         | 0.46%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                               | 3         | 0.46%   |
| Intel 82579V Gigabit Network Connection                                                                | 3         | 0.46%   |
| Broadcom BCM43228 802.11a/b/g/n                                                                        | 3         | 0.46%   |
| Broadcom BCM43224 802.11a/b/g/n                                                                        | 3         | 0.46%   |
| 802.11g Adapter [Linksys WUSB54GC v3] WUSB600N v1 Dual-Band Wireless-N Network Adapter [Ralink RT2870] | 3         | 0.46%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                            | 2         | 0.31%   |
| Samsung E2530 Phone (Samsung Kies mode)                                                                | 2         | 0.31%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                                     | 2         | 0.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                               | 2         | 0.31%   |
| Realtek RTL8188EE Wireless Network Adapter                                                             | 2         | 0.31%   |
| Realtek RTL8152 Fast Ethernet Adapter                                                                  | 2         | 0.31%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 115       | 38.59%  |
| Qualcomm Atheros                      | 63        | 21.14%  |
| Realtek Semiconductor                 | 51        | 17.11%  |
| Broadcom                              | 27        | 9.06%   |
| Ralink Technology                     | 18        | 6.04%   |
| TP-Link                               | 6         | 2.01%   |
| Broadcom Limited                      | 3         | 1.01%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 1.01%   |
| Qualcomm Atheros Communications       | 2         | 0.67%   |
| D-Link                                | 2         | 0.67%   |
| Samsung Electronics                   | 1         | 0.34%   |
| Realtek                               | 1         | 0.34%   |
| NetGear                               | 1         | 0.34%   |
| MediaTek                              | 1         | 0.34%   |
| Marvell Technology Group              | 1         | 0.34%   |
| Encore Electronics                    | 1         | 0.34%   |
| Dell                                  | 1         | 0.34%   |
| BUFFALO                               | 1         | 0.34%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                                  | Computers | Percent |
|--------------------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                             | 15        | 5%      |
| Intel Wireless 7265                                                                                    | 15        | 5%      |
| Ralink MT7601U Wireless Adapter                                                                        | 12        | 4%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                             | 12        | 4%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                                        | 11        | 3.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                                       | 11        | 3.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                         | 10        | 3.33%   |
| Intel Wireless 3165                                                                                    | 10        | 3.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                                    | 9         | 3%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                                       | 8         | 2.67%   |
| Intel Wi-Fi 6 AX200                                                                                    | 8         | 2.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                           | 8         | 2.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                                       | 7         | 2.33%   |
| Intel Wireless 7260                                                                                    | 6         | 2%      |
| Intel Comet Lake PCH CNVi WiFi                                                                         | 6         | 2%      |
| Intel Cannon Lake PCH CNVi WiFi                                                                        | 6         | 2%      |
| Broadcom BCM43142 802.11b/g/n                                                                          | 6         | 2%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                               | 5         | 1.67%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                               | 5         | 1.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                             | 5         | 1.67%   |
| Realtek 802.11ac NIC                                                                                   | 4         | 1.33%   |
| Intel Wireless 8265 / 8275                                                                             | 4         | 1.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                                      | 4         | 1.33%   |
| Intel Centrino Advanced-N 6235                                                                         | 4         | 1.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                                        | 3         | 1%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                                    | 3         | 1%      |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                                               | 3         | 1%      |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                                | 3         | 1%      |
| Intel Wireless 8260                                                                                    | 3         | 1%      |
| Intel Wi-Fi 6 AX201                                                                                    | 3         | 1%      |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                                        | 3         | 1%      |
| Intel Centrino Wireless-N 2200                                                                         | 3         | 1%      |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                               | 3         | 1%      |
| Broadcom BCM43228 802.11a/b/g/n                                                                        | 3         | 1%      |
| Broadcom BCM43224 802.11a/b/g/n                                                                        | 3         | 1%      |
| 802.11g Adapter [Linksys WUSB54GC v3] WUSB600N v1 Dual-Band Wireless-N Network Adapter [Ralink RT2870] | 3         | 1%      |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                            | 2         | 0.67%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                                     | 2         | 0.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                               | 2         | 0.67%   |
| Realtek RTL8188EE Wireless Network Adapter                                                             | 2         | 0.67%   |
| Ralink RT5370 Wireless Adapter                                                                         | 2         | 0.67%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                                  | 2         | 0.67%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                                      | 2         | 0.67%   |
| Qualcomm Atheros AR9271 802.11n                                                                        | 2         | 0.67%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                         | 2         | 0.67%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                         | 2         | 0.67%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                                           | 2         | 0.67%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                                 | 2         | 0.67%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                           | 1         | 0.33%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                                    | 1         | 0.33%   |
| TP-Link 802.11ac WLAN Adapter                                                                          | 1         | 0.33%   |
| TP-Link 802.11ac NIC                                                                                   | 1         | 0.33%   |
| Samsung WIS09ABGN LinkStick Wireless LAN Adapter                                                       | 1         | 0.33%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                                               | 1         | 0.33%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                                             | 1         | 0.33%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                                        | 1         | 0.33%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                             | 1         | 0.33%   |
| Realtek RTL8192E/RTL8192SE Wireless LAN Controller                                                     | 1         | 0.33%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                                 | 1         | 0.33%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                                            | 1         | 0.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 214       | 62.94%  |
| Intel                             | 54        | 15.88%  |
| Qualcomm Atheros                  | 26        | 7.65%   |
| Broadcom                          | 14        | 4.12%   |
| Nvidia                            | 10        | 2.94%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.88%   |
| Marvell Technology Group          | 3         | 0.88%   |
| JMicron Technology                | 3         | 0.88%   |
| Xiaomi                            | 2         | 0.59%   |
| OPPO Electronics                  | 2         | 0.59%   |
| Huawei Technologies               | 2         | 0.59%   |
| Broadcom Limited                  | 2         | 0.59%   |
| Sundance Technology Inc / IC Plus | 1         | 0.29%   |
| Qualcomm                          | 1         | 0.29%   |
| ICS Advent                        | 1         | 0.29%   |
| D-Link System                     | 1         | 0.29%   |
| ASIX Electronics                  | 1         | 0.29%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 169       | 49.27%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 35        | 10.2%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 12        | 3.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 5         | 1.46%   |
| Nvidia MCP61 Ethernet                                                          | 5         | 1.46%   |
| Realtek RTL8125 2.5GbE Controller                                              | 4         | 1.17%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 4         | 1.17%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 4         | 1.17%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 4         | 1.17%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 4         | 1.17%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 3         | 0.87%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 3         | 0.87%   |
| Intel I211 Gigabit Network Connection                                          | 3         | 0.87%   |
| Intel Ethernet Controller I225-V                                               | 3         | 0.87%   |
| Intel Ethernet Connection I217-V                                               | 3         | 0.87%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 0.87%   |
| Intel Ethernet Connection (10) I219-V                                          | 3         | 0.87%   |
| Intel 82579V Gigabit Network Connection                                        | 3         | 0.87%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 0.58%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 0.58%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2         | 0.58%   |
| OPPO SDM720G-IDP _SN:B922E265                                                  | 2         | 0.58%   |
| Nvidia MCP79 Ethernet                                                          | 2         | 0.58%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 2         | 0.58%   |
| Intel Ethernet Connection I219-V                                               | 2         | 0.58%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 0.58%   |
| Intel Ethernet Connection (6) I219-LM                                          | 2         | 0.58%   |
| Intel Ethernet Connection (2) I219-V                                           | 2         | 0.58%   |
| Intel 82577LC Gigabit Network Connection                                       | 2         | 0.58%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 0.58%   |
| Huawei LYA-L09                                                                 | 2         | 0.58%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 0.58%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 2         | 0.58%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 2         | 0.58%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 0.58%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.29%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.29%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY     | 1         | 0.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 0.29%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.29%   |
| Qualcomm BENGAL-QRD _SN:C5464635                                               | 1         | 0.29%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.29%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                     | 1         | 0.29%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.29%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.29%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 0.29%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.29%   |
| Nvidia MCP67 Ethernet                                                          | 1         | 0.29%   |
| Nvidia MCP51 Ethernet Controller                                               | 1         | 0.29%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.29%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 1         | 0.29%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.29%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.29%   |
| Intel PRO/100 VE Network Connection                                            | 1         | 0.29%   |
| Intel I210 Gigabit Network Connection                                          | 1         | 0.29%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.29%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 0.29%   |
| Intel Ethernet Connection (7) I219-V                                           | 1         | 0.29%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.29%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 326       | 53.01%  |
| WiFi     | 286       | 46.5%   |
| Modem    | 3         | 0.49%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 231       | 60.31%  |
| Ethernet | 152       | 39.69%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 201       | 53.17%  |
| 1     | 160       | 42.33%  |
| 0     | 11        | 2.91%   |
| 3     | 6         | 1.59%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 352       | 92.39%  |
| Yes  | 29        | 7.61%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 85        | 40.09%  |
| Realtek Semiconductor           | 21        | 9.91%   |
| Broadcom                        | 18        | 8.49%   |
| Lite-On Technology              | 17        | 8.02%   |
| Qualcomm Atheros Communications | 16        | 7.55%   |
| Foxconn / Hon Hai               | 13        | 6.13%   |
| IMC Networks                    | 12        | 5.66%   |
| Cambridge Silicon Radio         | 10        | 4.72%   |
| Apple                           | 8         | 3.77%   |
| Toshiba                         | 3         | 1.42%   |
| Hewlett-Packard                 | 3         | 1.42%   |
| Dell                            | 2         | 0.94%   |
| Chicony Electronics             | 2         | 0.94%   |
| Marvell Semiconductor           | 1         | 0.47%   |
| Integrated System Solution      | 1         | 0.47%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 37        | 17.45%  |
| Intel AX201 Bluetooth                                                               | 14        | 6.6%    |
| Realtek Bluetooth Radio                                                             | 12        | 5.66%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 12        | 5.66%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 10        | 4.72%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 9         | 4.25%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 7         | 3.3%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 7         | 3.3%    |
| Intel AX200 Bluetooth                                                               | 7         | 3.3%    |
| IMC Networks Bluetooth Device                                                       | 7         | 3.3%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 4         | 1.89%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 1.89%   |
| IMC Networks Bluetooth Radio                                                        | 4         | 1.89%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 1.89%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 1.89%   |
| Realtek RTL8821A Bluetooth                                                          | 3         | 1.42%   |
| Realtek RTL8723B Bluetooth                                                          | 3         | 1.42%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 1.42%   |
| Lite-On Bluetooth Device                                                            | 3         | 1.42%   |
| Intel Bluetooth Device                                                              | 3         | 1.42%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 3         | 1.42%   |
| Apple Bluetooth Host Controller                                                     | 3         | 1.42%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 0.94%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 0.94%   |
| Lite-On BCM43142A0                                                                  | 2         | 0.94%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 0.94%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 0.94%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 2         | 0.94%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 2         | 0.94%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 2         | 0.94%   |
| Chicony Bluetooth (RTL8723BE)                                                       | 2         | 0.94%   |
| Broadcom HP Portable Valentine                                                      | 2         | 0.94%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 0.94%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 0.94%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 2         | 0.94%   |
| Broadcom BCM2035 Bluetooth                                                          | 2         | 0.94%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 0.94%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.47%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)                                          | 1         | 0.47%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.47%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.47%   |
| Marvell Bluetooth and Wireless LAN Composite Device                                 | 1         | 0.47%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 1         | 0.47%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.47%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                               | 1         | 0.47%   |
| IMC Networks Bluetooth USB Host Controller                                          | 1         | 0.47%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.47%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.47%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.47%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 1         | 0.47%   |
| Dell Wireless 365 Bluetooth                                                         | 1         | 0.47%   |
| Dell Wireless 355 Bluetooth                                                         | 1         | 0.47%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.47%   |
| Broadcom BCM20702A0                                                                 | 1         | 0.47%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 0.47%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 0.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 273       | 56.4%   |
| AMD                              | 90        | 18.6%   |
| Nvidia                           | 81        | 16.74%  |
| Logitech                         | 4         | 0.83%   |
| Generalplus Technology           | 4         | 0.83%   |
| C-Media Electronics              | 4         | 0.83%   |
| SteelSeries ApS                  | 3         | 0.62%   |
| Silicon Integrated Systems [SiS] | 3         | 0.62%   |
| Realtek Semiconductor            | 2         | 0.41%   |
| Plantronics                      | 2         | 0.41%   |
| JMTek                            | 2         | 0.41%   |
| GN Netcom                        | 2         | 0.41%   |
| DCMT Technology                  | 2         | 0.41%   |
| XMOS                             | 1         | 0.21%   |
| OPPO Electronics                 | 1         | 0.21%   |
| Kingston Technology              | 1         | 0.21%   |
| Giga-Byte Technology             | 1         | 0.21%   |
| Focusrite-Novation               | 1         | 0.21%   |
| FiiO Electronics Technology      | 1         | 0.21%   |
| FIFINE 683 Microphone            | 1         | 0.21%   |
| Elgato Systems                   | 1         | 0.21%   |
| DEXP BK-20                       | 1         | 0.21%   |
| Creative Technology              | 1         | 0.21%   |
| Corsair                          | 1         | 0.21%   |
| Cooler Master                    | 1         | 0.21%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 37        | 6.39%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 30        | 5.18%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 28        | 4.84%   |
| AMD FCH Azalia Controller                                                                         | 27        | 4.66%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 25        | 4.32%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 23        | 3.97%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 19        | 3.28%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 15        | 2.59%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 13        | 2.25%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 11        | 1.9%    |
| Intel 200 Series PCH HD Audio                                                                     | 11        | 1.9%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 11        | 1.9%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 10        | 1.73%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 1.55%   |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 1.55%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 1.55%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 9         | 1.55%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 8         | 1.38%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 1.38%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 8         | 1.38%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 1.38%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 8         | 1.38%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 8         | 1.38%   |
| AMD Kabini HDMI/DP Audio                                                                          | 8         | 1.38%   |
| Nvidia MCP61 High Definition Audio                                                                | 7         | 1.21%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 7         | 1.21%   |
| Intel Comet Lake PCH cAVS                                                                         | 7         | 1.21%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 1.21%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 7         | 1.21%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 6         | 1.04%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 1.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 1.04%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6         | 1.04%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 6         | 1.04%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 0.86%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 5         | 0.86%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 0.86%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 0.86%   |
| AMD Trinity HDMI Audio Controller                                                                 | 5         | 0.86%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 5         | 0.86%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 5         | 0.86%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 5         | 0.86%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 4         | 0.69%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 4         | 0.69%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 4         | 0.69%   |
| Generalplus Technology USB Audio Device                                                           | 4         | 0.69%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 3         | 0.52%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.52%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 3         | 0.52%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.52%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 0.52%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.52%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.52%   |
| Intel Audio device                                                                                | 3         | 0.52%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 0.52%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 0.52%   |
| SteelSeries ApS SteelSeries Arctis 5                                                              | 2         | 0.35%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 0.35%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 0.35%   |
| Nvidia Audio device                                                                               | 2         | 0.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Kingston            | 42        | 21.43%  |
| Samsung Electronics | 37        | 18.88%  |
| SK hynix            | 32        | 16.33%  |
| Unknown             | 20        | 10.2%   |
| Micron Technology   | 12        | 6.12%   |
| Team                | 11        | 5.61%   |
| Ramaxel Technology  | 8         | 4.08%   |
| G.Skill             | 6         | 3.06%   |
| Crucial             | 5         | 2.55%   |
| Unknown (ABCD)      | 2         | 1.02%   |
| Transcend           | 2         | 1.02%   |
| Patriot             | 2         | 1.02%   |
| Nanya Technology    | 2         | 1.02%   |
| Kingmax             | 2         | 1.02%   |
| Elpida              | 2         | 1.02%   |
| Corsair             | 2         | 1.02%   |
| Unknown             | 2         | 1.02%   |
| Uroad               | 1         | 0.51%   |
| Silicon Power       | 1         | 0.51%   |
| PNY                 | 1         | 0.51%   |
| Mitsubishi          | 1         | 0.51%   |
| Carry               | 1         | 0.51%   |
| ASint Technology    | 1         | 0.51%   |
| A-DATA Technology   | 1         | 0.51%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 2.43%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 1.94%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 3         | 1.46%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 1.46%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.46%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 3         | 1.46%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s              | 3         | 1.46%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s          | 3         | 1.46%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 2         | 0.97%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 2         | 0.97%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s              | 2         | 0.97%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s            | 2         | 0.97%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.97%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.97%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.97%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 2         | 0.97%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.97%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.97%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.97%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 2         | 0.97%   |
| Patriot RAM PSD34G160081 4GB DIMM DDR3 1600MT/s                  | 2         | 0.97%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.97%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 0.97%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s             | 2         | 0.97%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s           | 2         | 0.97%   |
| Kingston RAM 99U5428-101.A00LF 8GB SODIMM DDR3 1600MT/s          | 2         | 0.97%   |
| Kingston RAM 9905700-025.A00G 8192MB SODIMM DDR4 2667MT/s        | 2         | 0.97%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s              | 2         | 0.97%   |
| Corsair RAM CMT128GX4M4C3200C16 32GB DIMM DDR4 3200MT/s          | 2         | 0.97%   |
| Unknown                                                          | 2         | 0.97%   |
| Uroad RAM WJD8G4M16P12800 8192MB DIMM DDR3 1600MT/s              | 1         | 0.49%   |
| Unknown RAM Module 8192MB DIMM                                   | 1         | 0.49%   |
| Unknown RAM Module 4GB SODIMM DDR4 2133MT/s                      | 1         | 0.49%   |
| Unknown RAM Module 4GB DIMM DDR4 2133MT/s                        | 1         | 0.49%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 0.49%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                             | 1         | 0.49%   |
| Unknown RAM Module 4096MB DIMM DDR2                              | 1         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.49%   |
| Unknown RAM Module 2048MB SODIMM DRAM 667MT/s                    | 1         | 0.49%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 1         | 0.49%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 1         | 0.49%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.49%   |
| Unknown RAM Module 2048MB SODIMM 667MT/s                         | 1         | 0.49%   |
| Unknown RAM Module 1GB DIMM DDR2                                 | 1         | 0.49%   |
| Unknown RAM Module 16384MB DIMM DDR4 2666MT/s                    | 1         | 0.49%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 1         | 0.49%   |
| Unknown RAM Module 1024MB SODIMM DDR2 400MT/s                    | 1         | 0.49%   |
| Unknown RAM Module 1024MB SODIMM 667MT/s                         | 1         | 0.49%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                      | 1         | 0.49%   |
| Unknown RAM Module 1024MB DIMM DDR2                              | 1         | 0.49%   |
| Unknown RAM KZ24UE5116HAR8 8192MB DIMM DDR4 2400MT/s             | 1         | 0.49%   |
| Transcend RAM TS2GLH64V4B 16384MB DIMM DDR4 2400MT/s             | 1         | 0.49%   |
| Transcend RAM JM1333KSN-4G 4096MB SODIMM DDR3 1334MT/s           | 1         | 0.49%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s               | 1         | 0.49%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s               | 1         | 0.49%   |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 2400MT/s               | 1         | 0.49%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s               | 1         | 0.49%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s             | 1         | 0.49%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s             | 1         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 77        | 47.83%  |
| DDR3    | 61        | 37.89%  |
| DDR2    | 10        | 6.21%   |
| Unknown | 5         | 3.11%   |
| LPDDR4  | 4         | 2.48%   |
| SDRAM   | 2         | 1.24%   |
| LPDDR3  | 1         | 0.62%   |
| DRAM    | 1         | 0.62%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 104       | 65%     |
| DIMM         | 52        | 32.5%   |
| Row Of Chips | 4         | 2.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 67        | 37.22%  |
| 4096  | 57        | 31.67%  |
| 2048  | 21        | 11.67%  |
| 16384 | 17        | 9.44%   |
| 1024  | 10        | 5.56%   |
| 32768 | 8         | 4.44%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 45        | 25.28%  |
| 2667    | 30        | 16.85%  |
| 3200    | 21        | 11.8%   |
| 2400    | 19        | 10.67%  |
| 2133    | 10        | 5.62%   |
| 1333    | 9         | 5.06%   |
| 667     | 9         | 5.06%   |
| 1334    | 7         | 3.93%   |
| 3600    | 5         | 2.81%   |
| Unknown | 4         | 2.25%   |
| 8400    | 2         | 1.12%   |
| 3466    | 2         | 1.12%   |
| 1800    | 2         | 1.12%   |
| 800     | 2         | 1.12%   |
| 4800    | 1         | 0.56%   |
| 4266    | 1         | 0.56%   |
| 3733    | 1         | 0.56%   |
| 3500    | 1         | 0.56%   |
| 3266    | 1         | 0.56%   |
| 2666    | 1         | 0.56%   |
| 2048    | 1         | 0.56%   |
| 1067    | 1         | 0.56%   |
| 1066    | 1         | 0.56%   |
| 533     | 1         | 0.56%   |
| 400     | 1         | 0.56%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Brother Industries | 3         | 42.86%  |
| Seiko Epson        | 2         | 28.57%  |
| Canon              | 2         | 28.57%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                     | Computers | Percent |
|---------------------------|-----------|---------|
| Seiko Epson L220 Series   | 1         | 14.29%  |
| Seiko Epson L120 Series   | 1         | 14.29%  |
| Canon PIXMA MG2500 Series | 1         | 14.29%  |
| Canon G2010 series        | 1         | 14.29%  |
| Brother DCP-T710W         | 1         | 14.29%  |
| Brother DCP-T700W         | 1         | 14.29%  |
| Brother DCP-T310          | 1         | 14.29%  |

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
| Canon CanoScan LiDE 110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 61        | 25.63%  |
| Realtek Semiconductor                  | 22        | 9.24%   |
| Microdia                               | 19        | 7.98%   |
| Acer                                   | 15        | 6.3%    |
| IMC Networks                           | 14        | 5.88%   |
| Quanta                                 | 13        | 5.46%   |
| Sunplus Innovation Technology          | 10        | 4.2%    |
| Apple                                  | 8         | 3.36%   |
| Lite-On Technology                     | 7         | 2.94%   |
| Suyin                                  | 6         | 2.52%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 2.52%   |
| Z-Star Microelectronics                | 5         | 2.1%    |
| Syntek                                 | 5         | 2.1%    |
| Silicon Motion                         | 5         | 2.1%    |
| Logitech                               | 5         | 2.1%    |
| Alcor Micro                            | 5         | 2.1%    |
| Samsung Electronics                    | 4         | 1.68%   |
| Jieli Technology                       | 4         | 1.68%   |
| Pixart Imaging                         | 3         | 1.26%   |
| Luxvisions Innotech Limited            | 2         | 0.84%   |
| Cubeternet                             | 2         | 0.84%   |
| Alpha Imaging Technology               | 2         | 0.84%   |
| ALi                                    | 2         | 0.84%   |
| A4Tech                                 | 2         | 0.84%   |
| Ricoh                                  | 1         | 0.42%   |
| Razer USA                              | 1         | 0.42%   |
| OmniVision Technologies                | 1         | 0.42%   |
| Microsoft                              | 1         | 0.42%   |
| Lenovo                                 | 1         | 0.42%   |
| KYE Systems (Mouse Systems)            | 1         | 0.42%   |
| Importek                               | 1         | 0.42%   |
| Goertek Electronics                    | 1         | 0.42%   |
| Generalplus Technology                 | 1         | 0.42%   |
| GEMBIRD                                | 1         | 0.42%   |
| DigiTech                               | 1         | 0.42%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 15        | 6.28%   |
| Chicony HD WebCam                                               | 11        | 4.6%    |
| Realtek Acer 640 x 480 laptop camera                            | 6         | 2.51%   |
| Quanta HD WebCam                                                | 5         | 2.09%   |
| Quanta VGA WebCam                                               | 4         | 1.67%   |
| Microdia Integrated_Webcam_HD                                   | 4         | 1.67%   |
| Jieli USB PHY 2.0                                               | 4         | 1.67%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 4         | 1.67%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 4         | 1.67%   |
| Z-Star Venus USB2.0 Camera                                      | 3         | 1.26%   |
| Samsung Galaxy A5 (MTP)                                         | 3         | 1.26%   |
| Realtek Integrated_Webcam_HD                                    | 3         | 1.26%   |
| Quanta HD User Facing                                           | 3         | 1.26%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                            | 3         | 1.26%   |
| Microdia Laptop_Integrated_Webcam_HD                            | 3         | 1.26%   |
| Lite-On Integrated Camera                                       | 3         | 1.26%   |
| Chicony VGA WebCam                                              | 3         | 1.26%   |
| Chicony Lenovo EasyCamera                                       | 3         | 1.26%   |
| Chicony HP Truevision HD                                        | 3         | 1.26%   |
| Chicony EasyCamera                                              | 3         | 1.26%   |
| Apple Built-in iSight                                           | 3         | 1.26%   |
| Acer Lenovo EasyCamera                                          | 3         | 1.26%   |
| Acer EasyCamera                                                 | 3         | 1.26%   |
| Syntek Lenovo EasyCamera                                        | 2         | 0.84%   |
| Syntek Integrated Camera                                        | 2         | 0.84%   |
| Suyin HP Webcam                                                 | 2         | 0.84%   |
| Sunplus Laptop Integrated WebCam HD                             | 2         | 0.84%   |
| Sunplus Integrated Webcam                                       | 2         | 0.84%   |
| Sunplus HD WebCam                                               | 2         | 0.84%   |
| Realtek USB2.0 VGA UVC WebCam                                   | 2         | 0.84%   |
| Microdia Sonix USB 2.0 Camera                                   | 2         | 0.84%   |
| Microdia Integrated Camera                                      | 2         | 0.84%   |
| Logitech HD Webcam C910                                         | 2         | 0.84%   |
| Lite-On TOSHIBA Web Camera - HD                                 | 2         | 0.84%   |
| Lite-On HP HD Camera                                            | 2         | 0.84%   |
| IMC Networks Integrated Camera                                  | 2         | 0.84%   |
| IMC Networks EasyCamera                                         | 2         | 0.84%   |
| Chicony USB 2.0 Camera                                          | 2         | 0.84%   |
| Chicony TOSHIBA Web Camera - HD                                 | 2         | 0.84%   |
| Chicony Lenovo Integrated Camera (0.3MP)                        | 2         | 0.84%   |
| Chicony Integrated Camera (1280x720@30)                         | 2         | 0.84%   |
| Chicony HP Wide Vision HD Camera                                | 2         | 0.84%   |
| Chicony HP HD Camera                                            | 2         | 0.84%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 2         | 0.84%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD         | 2         | 0.84%   |
| Apple FaceTime HD Camera (Built-in)                             | 2         | 0.84%   |
| Apple FaceTime Camera                                           | 2         | 0.84%   |
| ALi WebCam                                                      | 2         | 0.84%   |
| Alcor Micro USB 2.0 PC cam                                      | 2         | 0.84%   |
| Alcor Micro HD WebCam                                           | 2         | 0.84%   |
| Acer SunplusIT Integrated Camera                                | 2         | 0.84%   |
| Acer Integrated Camera                                          | 2         | 0.84%   |
| A4Tech FHD 1080P PC Camera                                      | 2         | 0.84%   |
| Z-Star Webcam                                                   | 1         | 0.42%   |
| Z-Star A4 TECH USB2.0 PC Camera J                               | 1         | 0.42%   |
| Syntek EasyCamera                                               | 1         | 0.42%   |
| Suyin UVC HD Webcam                                             | 1         | 0.42%   |
| Suyin USB 2.0 Camera                                            | 1         | 0.42%   |
| Suyin HP Truevision HD                                          | 1         | 0.42%   |
| Suyin Acer/Lenovo Webcam [CN0316]                               | 1         | 0.42%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 10        | 35.71%  |
| Synaptics                  | 7         | 25%     |
| Shenzhen Goodix Technology | 5         | 17.86%  |
| Upek                       | 3         | 10.71%  |
| AuthenTec                  | 2         | 7.14%   |
| LighTuning Technology      | 1         | 3.57%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 3         | 10.71%  |
| Validity Sensors VFS495 Fingerprint Reader                 | 2         | 7.14%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 2         | 7.14%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 2         | 7.14%   |
| Synaptics  WBDI                                            | 2         | 7.14%   |
| Shenzhen Goodix  FingerPrint Device                        | 2         | 7.14%   |
| Shenzhen Goodix Fingerprint Reader                         | 2         | 7.14%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 3.57%   |
| Validity Sensors VFS300 Fingerprint Reader                 | 1         | 3.57%   |
| Validity Sensors VFS101 Fingerprint Reader                 | 1         | 3.57%   |
| Validity Sensors Synaptics WBDI                            | 1         | 3.57%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.57%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 3.57%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 1         | 3.57%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 3.57%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 1         | 3.57%   |
| Shenzhen Goodix FingerPrint                                | 1         | 3.57%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 1         | 3.57%   |
| AuthenTec Fingerprint Sensor                               | 1         | 3.57%   |
| AuthenTec AES1600                                          | 1         | 3.57%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Broadcom         | 3         | 37.5%   |
| Upek             | 2         | 25%     |
| SCM Microsystems | 1         | 12.5%   |
| O2 Micro         | 1         | 12.5%   |
| Alcor Micro      | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 25%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 25%     |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 12.5%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 12.5%   |
| Broadcom 5880                                                                | 1         | 12.5%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 302       | 78.65%  |
| 1     | 72        | 18.75%  |
| 2     | 9         | 2.34%   |
| 3     | 1         | 0.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 27        | 29.67%  |
| Graphics card            | 24        | 26.37%  |
| Net/wireless             | 15        | 16.48%  |
| Chipcard                 | 8         | 8.79%   |
| Net/ethernet             | 4         | 4.4%    |
| Camera                   | 3         | 3.3%    |
| Multimedia controller    | 2         | 2.2%    |
| Communication controller | 2         | 2.2%    |
| Unassigned class         | 1         | 1.1%    |
| Storage/raid             | 1         | 1.1%    |
| Storage                  | 1         | 1.1%    |
| Sound                    | 1         | 1.1%    |
| Network                  | 1         | 1.1%    |
| Modem                    | 1         | 1.1%    |

