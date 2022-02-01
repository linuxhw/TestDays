Gentoo 2.8 - Tested Hardware & Statistics
-----------------------------------------

A project to collect tested hardware configurations for Gentoo 2.8.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Gentoo_2.8/Desktop/README.md) and [notebooks](/Dist/Gentoo_2.8/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | GS63VR 6RF                  | Notebook    | [4873365af6](https://linux-hardware.org/?probe=4873365af6) | Jan 30, 2022 |
| ASRock        | AB350M Pro4                 | Desktop     | [6b7cf2d570](https://linux-hardware.org/?probe=6b7cf2d570) | Jan 27, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [9082dd553a](https://linux-hardware.org/?probe=9082dd553a) | Jan 27, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [c021622ad4](https://linux-hardware.org/?probe=c021622ad4) | Jan 27, 2022 |
| Timi          | RedmiBook 13                | Notebook    | [e20538f56a](https://linux-hardware.org/?probe=e20538f56a) | Jan 26, 2022 |
| Timi          | RedmiBook 13                | Notebook    | [b424ef43c2](https://linux-hardware.org/?probe=b424ef43c2) | Jan 25, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [656da02110](https://linux-hardware.org/?probe=656da02110) | Jan 24, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [a4f6a4a38e](https://linux-hardware.org/?probe=a4f6a4a38e) | Jan 24, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [9e4f498056](https://linux-hardware.org/?probe=9e4f498056) | Jan 24, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [1721bed3e1](https://linux-hardware.org/?probe=1721bed3e1) | Jan 24, 2022 |
| Gigabyte      | Z490 UD                     | Desktop     | [eac4639ad2](https://linux-hardware.org/?probe=eac4639ad2) | Jan 22, 2022 |
| MSI           | GE73 Raider RGB 8RF         | Notebook    | [a5a825a072](https://linux-hardware.org/?probe=a5a825a072) | Jan 22, 2022 |
| Lenovo        | ThinkPad 20FMCT01WW         | Notebook    | [4bd81196a0](https://linux-hardware.org/?probe=4bd81196a0) | Jan 21, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [c85ff3d537](https://linux-hardware.org/?probe=c85ff3d537) | Jan 20, 2022 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [65ce2eb070](https://linux-hardware.org/?probe=65ce2eb070) | Jan 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [d786a0b993](https://linux-hardware.org/?probe=d786a0b993) | Jan 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [6af6121c33](https://linux-hardware.org/?probe=6af6121c33) | Jan 17, 2022 |
| Dell          | Precision 3561              | Notebook    | [f5417a1852](https://linux-hardware.org/?probe=f5417a1852) | Jan 16, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [2aa146518a](https://linux-hardware.org/?probe=2aa146518a) | Jan 16, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [52494cf0b0](https://linux-hardware.org/?probe=52494cf0b0) | Jan 13, 2022 |
| TYAN Compu... | S7025                       | Server      | [c5f294d367](https://linux-hardware.org/?probe=c5f294d367) | Jan 12, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [5f92f3376e](https://linux-hardware.org/?probe=5f92f3376e) | Jan 11, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [d46da820e0](https://linux-hardware.org/?probe=d46da820e0) | Jan 10, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [dcf0799dd1](https://linux-hardware.org/?probe=dcf0799dd1) | Jan 10, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [fb3838c0db](https://linux-hardware.org/?probe=fb3838c0db) | Jan 10, 2022 |
| ASRock        | X370 Gaming X               | Desktop     | [e233d7c495](https://linux-hardware.org/?probe=e233d7c495) | Jan 09, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [8406d08f2e](https://linux-hardware.org/?probe=8406d08f2e) | Jan 06, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | Notebook    | [0cf6f2102c](https://linux-hardware.org/?probe=0cf6f2102c) | Jan 03, 2022 |
| Timi          | RedmiBook 13                | Notebook    | [528d0d32b4](https://linux-hardware.org/?probe=528d0d32b4) | Jan 01, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [eba53a3d91](https://linux-hardware.org/?probe=eba53a3d91) | Dec 30, 2021 |
| TYAN Compu... | S7025                       | Server      | [4a4fe05b48](https://linux-hardware.org/?probe=4a4fe05b48) | Dec 27, 2021 |
| EVGA          | Z390 DARK                   | Desktop     | [7672395a1c](https://linux-hardware.org/?probe=7672395a1c) | Dec 24, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [1695a19b52](https://linux-hardware.org/?probe=1695a19b52) | Dec 24, 2021 |
| Intel         | S1200RP G62251-406          | Server      | [986c6d1f51](https://linux-hardware.org/?probe=986c6d1f51) | Dec 24, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [429df0480e](https://linux-hardware.org/?probe=429df0480e) | Dec 23, 2021 |
| Framework     | Laptop                      | Notebook    | [33bb6590a6](https://linux-hardware.org/?probe=33bb6590a6) | Dec 21, 2021 |
| TYAN Compu... | S7025                       | Server      | [88ee246f4e](https://linux-hardware.org/?probe=88ee246f4e) | Dec 21, 2021 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [36ad5ef96a](https://linux-hardware.org/?probe=36ad5ef96a) | Dec 16, 2021 |
| BESSTAR Te... | ATB15                       | Server      | [783d1d7b6f](https://linux-hardware.org/?probe=783d1d7b6f) | Dec 16, 2021 |
| ASUSTek       | P5LD2-Deluxe                | Desktop     | [a2ee48eeb1](https://linux-hardware.org/?probe=a2ee48eeb1) | Dec 16, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [0ec288fb32](https://linux-hardware.org/?probe=0ec288fb32) | Dec 16, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [ee63a84605](https://linux-hardware.org/?probe=ee63a84605) | Dec 11, 2021 |
| Toshiba       | Satellite C850D-118         | Notebook    | [b15f2e2c92](https://linux-hardware.org/?probe=b15f2e2c92) | Dec 09, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [d1c651b135](https://linux-hardware.org/?probe=d1c651b135) | Dec 09, 2021 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | Desktop     | [b92f432637](https://linux-hardware.org/?probe=b92f432637) | Dec 07, 2021 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | Desktop     | [d8f50aaa2e](https://linux-hardware.org/?probe=d8f50aaa2e) | Dec 07, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [6649bea1f8](https://linux-hardware.org/?probe=6649bea1f8) | Dec 04, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [723e2a158a](https://linux-hardware.org/?probe=723e2a158a) | Dec 03, 2021 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [e155882ffa](https://linux-hardware.org/?probe=e155882ffa) | Dec 02, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [41b1b4ce39](https://linux-hardware.org/?probe=41b1b4ce39) | Dec 02, 2021 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [86f5c0bc34](https://linux-hardware.org/?probe=86f5c0bc34) | Nov 30, 2021 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [e06c73ada9](https://linux-hardware.org/?probe=e06c73ada9) | Nov 29, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [ad15be0510](https://linux-hardware.org/?probe=ad15be0510) | Nov 29, 2021 |
| Lenovo        | ThinkPad T470p 20J7S06Q0... | Notebook    | [6eca4a1be2](https://linux-hardware.org/?probe=6eca4a1be2) | Nov 22, 2021 |
| Lenovo        | ThinkPad T470p 20J7S06Q0... | Notebook    | [6c92c6ecbb](https://linux-hardware.org/?probe=6c92c6ecbb) | Nov 22, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [e2c087b9c7](https://linux-hardware.org/?probe=e2c087b9c7) | Nov 21, 2021 |
| Acer          | Aspire A715-42G             | Notebook    | [3ea389d8ff](https://linux-hardware.org/?probe=3ea389d8ff) | Nov 21, 2021 |
| Acer          | Aspire A715-42G             | Notebook    | [19f48288ec](https://linux-hardware.org/?probe=19f48288ec) | Nov 20, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [40748c60b0](https://linux-hardware.org/?probe=40748c60b0) | Nov 18, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [eafa22145d](https://linux-hardware.org/?probe=eafa22145d) | Nov 15, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [2900821ed3](https://linux-hardware.org/?probe=2900821ed3) | Nov 14, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4cfb74fb42](https://linux-hardware.org/?probe=4cfb74fb42) | Nov 14, 2021 |
| Lenovo        | ThinkPad E495 20NE000BGE    | Notebook    | [871e0a8d36](https://linux-hardware.org/?probe=871e0a8d36) | Nov 11, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [3aeb2b6565](https://linux-hardware.org/?probe=3aeb2b6565) | Nov 11, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | Desktop     | [6f308039a8](https://linux-hardware.org/?probe=6f308039a8) | Nov 06, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [ced6e2a8c2](https://linux-hardware.org/?probe=ced6e2a8c2) | Nov 04, 2021 |
| Intel         | S1200RP G62251-405          | Server      | [798cf3cc96](https://linux-hardware.org/?probe=798cf3cc96) | Nov 02, 2021 |
| MSI           | H110M PRO-D                 | Desktop     | [cb3dcdd186](https://linux-hardware.org/?probe=cb3dcdd186) | Nov 02, 2021 |
| MSI           | H110M PRO-D                 | Desktop     | [b53420c26a](https://linux-hardware.org/?probe=b53420c26a) | Nov 02, 2021 |
| Dell          | Latitude 7490               | Notebook    | [ea64667f2c](https://linux-hardware.org/?probe=ea64667f2c) | Nov 01, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [161865edb0](https://linux-hardware.org/?probe=161865edb0) | Oct 30, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a4806aa50f](https://linux-hardware.org/?probe=a4806aa50f) | Oct 30, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [aea7d9561e](https://linux-hardware.org/?probe=aea7d9561e) | Oct 29, 2021 |
| ASRock        | X370 Gaming X               | Desktop     | [0f4ae74d8e](https://linux-hardware.org/?probe=0f4ae74d8e) | Oct 29, 2021 |
| ASRock        | X370 Gaming X               | Desktop     | [f3f75352e4](https://linux-hardware.org/?probe=f3f75352e4) | Oct 29, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [e9cc487951](https://linux-hardware.org/?probe=e9cc487951) | Oct 28, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [1a6eea194f](https://linux-hardware.org/?probe=1a6eea194f) | Oct 28, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [6105164e23](https://linux-hardware.org/?probe=6105164e23) | Oct 26, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [cb6d9e548b](https://linux-hardware.org/?probe=cb6d9e548b) | Oct 26, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [8a34d739fd](https://linux-hardware.org/?probe=8a34d739fd) | Oct 25, 2021 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [5b06944051](https://linux-hardware.org/?probe=5b06944051) | Oct 25, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [58e3f9c07f](https://linux-hardware.org/?probe=58e3f9c07f) | Oct 23, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [5d0fc3aa0e](https://linux-hardware.org/?probe=5d0fc3aa0e) | Oct 21, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [eb02a6d4d5](https://linux-hardware.org/?probe=eb02a6d4d5) | Oct 20, 2021 |
| ASRock        | X370 Killer SLI/ac          | Desktop     | [2e4c1c4527](https://linux-hardware.org/?probe=2e4c1c4527) | Oct 17, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [243e5becca](https://linux-hardware.org/?probe=243e5becca) | Oct 14, 2021 |
| Acer          | Aspire A515-55              | Notebook    | [437c8fb96b](https://linux-hardware.org/?probe=437c8fb96b) | Oct 12, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [95cd0c0751](https://linux-hardware.org/?probe=95cd0c0751) | Oct 07, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [3ad4e11bac](https://linux-hardware.org/?probe=3ad4e11bac) | Oct 06, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [18a2385458](https://linux-hardware.org/?probe=18a2385458) | Oct 06, 2021 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [9901023f19](https://linux-hardware.org/?probe=9901023f19) | Oct 03, 2021 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [e2057e68dd](https://linux-hardware.org/?probe=e2057e68dd) | Oct 03, 2021 |
| Dell          | Inspiron 5415               | Notebook    | [a265f8ea5c](https://linux-hardware.org/?probe=a265f8ea5c) | Oct 01, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 5.15.10-gentoo               | 4         | 6.45%   |
| 5.15.10-gentoo-x86_64        | 3         | 4.84%   |
| 5.14.9-gentoo-x86_64         | 3         | 4.84%   |
| 5.16.2-gentoo                | 2         | 3.23%   |
| 5.16.0-gentoo-x86_64         | 2         | 3.23%   |
| 5.15.6-gentoo                | 2         | 3.23%   |
| 5.15.1-gentoo-x86_64         | 2         | 3.23%   |
| 5.14.14-gentoo-x86_64        | 2         | 3.23%   |
| 5.14.14-gentoo-dist          | 2         | 3.23%   |
| 5.14.12-gentoo               | 2         | 3.23%   |
| 6.0.0-Phaco-g8f10ff49057f    | 1         | 1.61%   |
| 5.16.2-gentoo-x86_64         | 1         | 1.61%   |
| 5.16.1-gentoo-x86_64         | 1         | 1.61%   |
| 5.16.1-gentoo                | 1         | 1.61%   |
| 5.16.0-xanmod1               | 1         | 1.61%   |
| 5.16.0-gentoo-gentoo-dist    | 1         | 1.61%   |
| 5.16.0-gentoo                | 1         | 1.61%   |
| 5.15.7-gentoo                | 1         | 1.61%   |
| 5.15.5-gentoo-x86_64         | 1         | 1.61%   |
| 5.15.5-gentoo-dist           | 1         | 1.61%   |
| 5.15.5-gentoo                | 1         | 1.61%   |
| 5.15.4-gentoo.8i7HVK         | 1         | 1.61%   |
| 5.15.4-gentoo-deimos         | 1         | 1.61%   |
| 5.15.3-gentoo.4650G          | 1         | 1.61%   |
| 5.15.2-gentoo20210917        | 1         | 1.61%   |
| 5.15.2-gentoo-x86_64         | 1         | 1.61%   |
| 5.15.16-gentoo-dist          | 1         | 1.61%   |
| 5.15.13-gentoo-dist          | 1         | 1.61%   |
| 5.15.13-gentoo               | 1         | 1.61%   |
| 5.15.12-gentoo-x86_64        | 1         | 1.61%   |
| 5.15.12-gentoo-dist          | 1         | 1.61%   |
| 5.15.12-gentoo               | 1         | 1.61%   |
| 5.15.0-gentoo-x86_64         | 1         | 1.61%   |
| 5.15.0-gentoo                | 1         | 1.61%   |
| 5.14.9-gentoo                | 1         | 1.61%   |
| 5.14.7-gentoo-x86_64         | 1         | 1.61%   |
| 5.14.6                       | 1         | 1.61%   |
| 5.14.15-gentoo20210917       | 1         | 1.61%   |
| 5.14.14-gentoo               | 1         | 1.61%   |
| 5.14.13-gentoo               | 1         | 1.61%   |
| 5.14.11-zen1                 | 1         | 1.61%   |
| 5.10.84-gentoo-112-overlayfs | 1         | 1.61%   |
| 5.10.83-gentoo-dist          | 1         | 1.61%   |
| 5.10.76-gentoo-r1            | 1         | 1.61%   |
| 5.10.74-gentoo-x86_64        | 1         | 1.61%   |
| 5.10.70-1-lts                | 1         | 1.61%   |
| 5.10.63-v8                   | 1         | 1.61%   |
| 5.10.11-v8                   | 1         | 1.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.10 | 7         | 11.29%  |
| 5.16.0  | 5         | 8.06%   |
| 5.14.14 | 5         | 8.06%   |
| 5.14.9  | 4         | 6.45%   |
| 5.16.2  | 3         | 4.84%   |
| 5.15.5  | 3         | 4.84%   |
| 5.15.12 | 3         | 4.84%   |
| 5.16.1  | 2         | 3.23%   |
| 5.15.6  | 2         | 3.23%   |
| 5.15.4  | 2         | 3.23%   |
| 5.15.2  | 2         | 3.23%   |
| 5.15.13 | 2         | 3.23%   |
| 5.15.1  | 2         | 3.23%   |
| 5.15.0  | 2         | 3.23%   |
| 5.14.12 | 2         | 3.23%   |
| 6.0.0   | 1         | 1.61%   |
| 5.15.7  | 1         | 1.61%   |
| 5.15.3  | 1         | 1.61%   |
| 5.15.16 | 1         | 1.61%   |
| 5.14.7  | 1         | 1.61%   |
| 5.14.6  | 1         | 1.61%   |
| 5.14.15 | 1         | 1.61%   |
| 5.14.13 | 1         | 1.61%   |
| 5.14.11 | 1         | 1.61%   |
| 5.10.84 | 1         | 1.61%   |
| 5.10.83 | 1         | 1.61%   |
| 5.10.76 | 1         | 1.61%   |
| 5.10.74 | 1         | 1.61%   |
| 5.10.70 | 1         | 1.61%   |
| 5.10.63 | 1         | 1.61%   |
| 5.10.11 | 1         | 1.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 27        | 45%     |
| 5.14    | 16        | 26.67%  |
| 5.16    | 10        | 16.67%  |
| 5.10    | 6         | 10%     |
| 6.0     | 1         | 1.67%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 55        | 98.21%  |
| aarch64 | 1         | 1.79%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KDE5          | 20        | 34.48%  |
| Unknown       | 17        | 29.31%  |
| GNOME         | 8         | 13.79%  |
| XFCE          | 5         | 8.62%   |
| Enlightenment | 2         | 3.45%   |
| sway          | 1         | 1.72%   |
| LXQt          | 1         | 1.72%   |
| i3            | 1         | 1.72%   |
| fvwm          | 1         | 1.72%   |
| DWM           | 1         | 1.72%   |
| Cinnamon      | 1         | 1.72%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 24        | 40.68%  |
| Wayland | 17        | 28.81%  |
| Tty     | 10        | 16.95%  |
| Unknown | 8         | 13.56%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 27        | 46.55%  |
| SDDM    | 19        | 32.76%  |
| GDM     | 6         | 10.34%  |
| LightDM | 4         | 6.9%    |
| SLiM    | 1         | 1.72%   |
| GREETD  | 1         | 1.72%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 22        | 39.29%  |
| en_GB      | 7         | 12.5%   |
| ru_RU      | 4         | 7.14%   |
| C.UTF8     | 3         | 5.36%   |
| Unknown    | 3         | 5.36%   |
| pl_PL      | 2         | 3.57%   |
| de_DE      | 2         | 3.57%   |
| C          | 2         | 3.57%   |
| tr_TR      | 1         | 1.79%   |
| sl_SI      | 1         | 1.79%   |
| pt_BR      | 1         | 1.79%   |
| it_IT      | 1         | 1.79%   |
| es_ES      | 1         | 1.79%   |
| es_AR      | 1         | 1.79%   |
| en_US.UTF8 | 1         | 1.79%   |
| en_NZ      | 1         | 1.79%   |
| en_AU      | 1         | 1.79%   |
| el_GR      | 1         | 1.79%   |
| de_CH      | 1         | 1.79%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 47        | 81.03%  |
| BIOS | 11        | 18.97%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 29        | 51.79%  |
| Btrfs | 22        | 39.29%  |
| F2fs  | 3         | 5.36%   |
| Zfs   | 1         | 1.79%   |
| Xtrfs | 1         | 1.79%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 52        | 89.66%  |
| Unknown | 4         | 6.9%    |
| MBR     | 2         | 3.45%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 42        | 72.41%  |
| Yes       | 16        | 27.59%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 40        | 71.43%  |
| Yes       | 16        | 28.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 13        | 23.21%  |
| ASUSTek Computer        | 11        | 19.64%  |
| MSI                     | 4         | 7.14%   |
| Gigabyte Technology     | 4         | 7.14%   |
| Dell                    | 4         | 7.14%   |
| ASRock                  | 4         | 7.14%   |
| Intel                   | 3         | 5.36%   |
| Acer                    | 3         | 5.36%   |
| Timi                    | 2         | 3.57%   |
| Hewlett-Packard         | 2         | 3.57%   |
| TYAN Computer           | 1         | 1.79%   |
| Toshiba                 | 1         | 1.79%   |
| Raspberry Pi Foundation | 1         | 1.79%   |
| Framework               | 1         | 1.79%   |
| EVGA                    | 1         | 1.79%   |
| BESSTAR Tech            | 1         | 1.79%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel S1200RP                            | 2         | 3.57%   |
| HP Laptop 15s-eq0xxx                     | 2         | 3.57%   |
| TYAN S7025                               | 1         | 1.79%   |
| Toshiba Satellite C850D-118              | 1         | 1.79%   |
| Timi RedmiBook 13                        | 1         | 1.79%   |
| Timi Mi Laptop Pro 15                    | 1         | 1.79%   |
| RPi Raspberry Pi                         | 1         | 1.79%   |
| MSI MS-7D31                              | 1         | 1.79%   |
| MSI MS-7996                              | 1         | 1.79%   |
| MSI GS63VR 6RF                           | 1         | 1.79%   |
| MSI GE73 Raider RGB 8RF                  | 1         | 1.79%   |
| Lenovo Yoga S740-14IIL 81RS              | 1         | 1.79%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD0039RI | 1         | 1.79%   |
| Lenovo ThinkPad T470p 20J7S06Q00         | 1         | 1.79%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F437      | 1         | 1.79%   |
| Lenovo ThinkPad E495 20NE000BGE          | 1         | 1.79%   |
| Lenovo ThinkPad E15 Gen 2 20T8001STX     | 1         | 1.79%   |
| Lenovo ThinkPad 20FMCT01WW               | 1         | 1.79%   |
| Lenovo ThinkBook 14 G3 ACL 21A2          | 1         | 1.79%   |
| Lenovo Legion R7000 2020 82B6            | 1         | 1.79%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ         | 1         | 1.79%   |
| Lenovo IdeaPadFlex 5 14ITL05 82LT        | 1         | 1.79%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5         | 1         | 1.79%   |
| Lenovo IdeaPad 5 15ITL05 82FG            | 1         | 1.79%   |
| Intel NUC8i7HVK                          | 1         | 1.79%   |
| Gigabyte Z87X-UD3H                       | 1         | 1.79%   |
| Gigabyte Z490 UD                         | 1         | 1.79%   |
| Gigabyte X570 AORUS MASTER               | 1         | 1.79%   |
| Gigabyte B450M S2H                       | 1         | 1.79%   |
| Framework Laptop                         | 1         | 1.79%   |
| EVGA Z390 DARK                           | 1         | 1.79%   |
| Dell XPS 15 9570                         | 1         | 1.79%   |
| Dell Precision 3561                      | 1         | 1.79%   |
| Dell Latitude 7490                       | 1         | 1.79%   |
| Dell Inspiron 5415                       | 1         | 1.79%   |
| BESSTAR Tech X400                        | 1         | 1.79%   |
| ASUS Z170-A                              | 1         | 1.79%   |
| ASUS TUF GAMING B550-PLUS                | 1         | 1.79%   |
| ASUS TUF B450-PLUS GAMING                | 1         | 1.79%   |
| ASUS ROG Zephyrus G14 GA401QE_GA401QE    | 1         | 1.79%   |
| ASUS ROG ZENITH II EXTREME               | 1         | 1.79%   |
| ASUS ROG STRIX X570-E GAMING             | 1         | 1.79%   |
| ASUS ROG Strix G513QY_G513QY             | 1         | 1.79%   |
| ASUS ROG STRIX B550-F GAMING             | 1         | 1.79%   |
| ASUS ROG CROSSHAIR VIII HERO             | 1         | 1.79%   |
| ASUS PRIME X570-P                        | 1         | 1.79%   |
| ASUS P5LD2-Deluxe                        | 1         | 1.79%   |
| ASRock X370 Killer SLI/ac                | 1         | 1.79%   |
| ASRock X370 Gaming X                     | 1         | 1.79%   |
| ASRock H110M-HDV R3.0                    | 1         | 1.79%   |
| ASRock AB350M Pro4                       | 1         | 1.79%   |
| Acer Nitro AN515-54                      | 1         | 1.79%   |
| Acer Aspire A715-42G                     | 1         | 1.79%   |
| Acer Aspire A515-55                      | 1         | 1.79%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 6         | 10.71%  |
| ASUS ROG           | 6         | 10.71%  |
| Lenovo Legion      | 2         | 3.57%   |
| Lenovo IdeaPad     | 2         | 3.57%   |
| Intel S1200RP      | 2         | 3.57%   |
| HP Laptop          | 2         | 3.57%   |
| ASUS TUF           | 2         | 3.57%   |
| ASRock X370        | 2         | 3.57%   |
| Acer Aspire        | 2         | 3.57%   |
| TYAN S7025         | 1         | 1.79%   |
| Toshiba Satellite  | 1         | 1.79%   |
| Timi RedmiBook     | 1         | 1.79%   |
| Timi Mi            | 1         | 1.79%   |
| RPi Raspberry      | 1         | 1.79%   |
| MSI MS-7D31        | 1         | 1.79%   |
| MSI MS-7996        | 1         | 1.79%   |
| MSI GS63VR         | 1         | 1.79%   |
| MSI GE73           | 1         | 1.79%   |
| Lenovo Yoga        | 1         | 1.79%   |
| Lenovo ThinkBook   | 1         | 1.79%   |
| Lenovo IdeaPadFlex | 1         | 1.79%   |
| Intel NUC8i7HVK    | 1         | 1.79%   |
| Gigabyte Z87X-UD3H | 1         | 1.79%   |
| Gigabyte Z490      | 1         | 1.79%   |
| Gigabyte X570      | 1         | 1.79%   |
| Gigabyte B450M     | 1         | 1.79%   |
| Framework Laptop   | 1         | 1.79%   |
| EVGA Z390          | 1         | 1.79%   |
| Dell XPS           | 1         | 1.79%   |
| Dell Precision     | 1         | 1.79%   |
| Dell Latitude      | 1         | 1.79%   |
| Dell Inspiron      | 1         | 1.79%   |
| BESSTAR Tech X400  | 1         | 1.79%   |
| ASUS Z170-A        | 1         | 1.79%   |
| ASUS PRIME         | 1         | 1.79%   |
| ASUS P5LD2-Deluxe  | 1         | 1.79%   |
| ASRock H110M-HDV   | 1         | 1.79%   |
| ASRock AB350M      | 1         | 1.79%   |
| Acer Nitro         | 1         | 1.79%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 13        | 23.21%  |
| 2019    | 12        | 21.43%  |
| 2020    | 10        | 17.86%  |
| 2018    | 7         | 12.5%   |
| 2017    | 4         | 7.14%   |
| 2016    | 3         | 5.36%   |
| 2012    | 2         | 3.57%   |
| 2015    | 1         | 1.79%   |
| 2014    | 1         | 1.79%   |
| 2013    | 1         | 1.79%   |
| 2005    | 1         | 1.79%   |
| Unknown | 1         | 1.79%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 29        | 51.79%  |
| Desktop        | 20        | 35.71%  |
| Server         | 4         | 7.14%   |
| System on chip | 1         | 1.79%   |
| Convertible    | 1         | 1.79%   |
| Mini pc        | 1         | 1.79%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 53        | 94.64%  |
| Enabled  | 3         | 5.36%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 56        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 16        | 28.57%  |
| 16.01-24.0  | 10        | 17.86%  |
| 8.01-16.0   | 10        | 17.86%  |
| 64.01-256.0 | 8         | 14.29%  |
| 4.01-8.0    | 5         | 8.93%   |
| 24.01-32.0  | 4         | 7.14%   |
| 3.01-4.0    | 1         | 1.79%   |
| 2.01-3.0    | 1         | 1.79%   |
| 1.01-2.0    | 1         | 1.79%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 19        | 30.65%  |
| 1.01-2.0   | 13        | 20.97%  |
| 8.01-16.0  | 8         | 12.9%   |
| 3.01-4.0   | 7         | 11.29%  |
| 2.01-3.0   | 7         | 11.29%  |
| 0.51-1.0   | 4         | 6.45%   |
| 16.01-24.0 | 2         | 3.23%   |
| 24.01-32.0 | 1         | 1.61%   |
| 0.01-0.5   | 1         | 1.61%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 27        | 47.37%  |
| 3      | 9         | 15.79%  |
| 2      | 9         | 15.79%  |
| 4      | 7         | 12.28%  |
| 5      | 4         | 7.02%   |
| 7      | 1         | 1.75%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 50        | 87.72%  |
| Yes       | 7         | 12.28%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 42        | 75%     |
| No        | 14        | 25%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 41        | 73.21%  |
| No        | 15        | 26.79%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 42        | 72.41%  |
| No        | 16        | 27.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 8         | 14.29%  |
| Russia      | 7         | 12.5%   |
| Germany     | 7         | 12.5%   |
| Poland      | 5         | 8.93%   |
| Spain       | 4         | 7.14%   |
| UK          | 2         | 3.57%   |
| Greece      | 2         | 3.57%   |
| Finland     | 2         | 3.57%   |
| Czechia     | 2         | 3.57%   |
| Uruguay     | 1         | 1.79%   |
| Turkey      | 1         | 1.79%   |
| Switzerland | 1         | 1.79%   |
| Sweden      | 1         | 1.79%   |
| Slovenia    | 1         | 1.79%   |
| Romania     | 1         | 1.79%   |
| Philippines | 1         | 1.79%   |
| New Zealand | 1         | 1.79%   |
| Mexico      | 1         | 1.79%   |
| Italy       | 1         | 1.79%   |
| India       | 1         | 1.79%   |
| Hong Kong   | 1         | 1.79%   |
| China       | 1         | 1.79%   |
| Brazil      | 1         | 1.79%   |
| Belarus     | 1         | 1.79%   |
| Bangladesh  | 1         | 1.79%   |
| Australia   | 1         | 1.79%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Swansea          | 2         | 3.45%   |
| Moscow           | 2         | 3.45%   |
| Kulmbach         | 2         | 3.45%   |
| Helsinki         | 2         | 3.45%   |
| Barcelona        | 2         | 3.45%   |
| Athens           | 2         | 3.45%   |
| Zurich           | 1         | 1.72%   |
| Zebulon          | 1         | 1.72%   |
| Yekaterinburg    | 1         | 1.72%   |
| West Orange      | 1         | 1.72%   |
| Warsaw           | 1         | 1.72%   |
| Vigo             | 1         | 1.72%   |
| Ufa              | 1         | 1.72%   |
| Szczecin         | 1         | 1.72%   |
| Sydney           | 1         | 1.72%   |
| Sestao           | 1         | 1.72%   |
| S??o Paulo       | 1         | 1.72%   |
| Rzesz??w         | 1         | 1.72%   |
| Redmond          | 1         | 1.72%   |
| Ratingen         | 1         | 1.72%   |
| Prague           | 1         | 1.72%   |
| Nyk?¶ping        | 1         | 1.72%   |
| Nuremberg        | 1         | 1.72%   |
| Novosibirsk      | 1         | 1.72%   |
| Nizhniy Novgorod | 1         | 1.72%   |
| Niederdorla      | 1         | 1.72%   |
| Monroe           | 1         | 1.72%   |
| Minsk            | 1         | 1.72%   |
| Milan            | 1         | 1.72%   |
| Maldonado        | 1         | 1.72%   |
| Laziska Gorne    | 1         | 1.72%   |
| Krakow           | 1         | 1.72%   |
| Ivan??na Gorica  | 1         | 1.72%   |
| Hyderabad        | 1         | 1.72%   |
| Harsum           | 1         | 1.72%   |
| Guangzhou        | 1         | 1.72%   |
| Glen Ellyn       | 1         | 1.72%   |
| Foshan           | 1         | 1.72%   |
| Everett          | 1         | 1.72%   |
| Dhaka            | 1         | 1.72%   |
| Ciudad Ju??rez   | 1         | 1.72%   |
| Cieszyn          | 1         | 1.72%   |
| Chicago          | 1         | 1.72%   |
| Cerritos         | 1         | 1.72%   |
| Central          | 1         | 1.72%   |
| Calamba          | 1         | 1.72%   |
| Brno             | 1         | 1.72%   |
| Brasov           | 1         | 1.72%   |
| Blagoveshchensk  | 1         | 1.72%   |
| Berlin           | 1         | 1.72%   |
| Auckland         | 1         | 1.72%   |
| Ankara           | 1         | 1.72%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 21        | 31     | 21.65%  |
| Samsung Electronics            | 18        | 26     | 18.56%  |
| Seagate                        | 11        | 20     | 11.34%  |
| Intel                          | 8         | 9      | 8.25%   |
| Toshiba                        | 5         | 5      | 5.15%   |
| SK Hynix                       | 5         | 5      | 5.15%   |
| Crucial                        | 4         | 10     | 4.12%   |
| Hitachi                        | 3         | 4      | 3.09%   |
| Unknown                        | 2         | 7      | 2.06%   |
| Team                           | 2         | 4      | 2.06%   |
| SanDisk                        | 2         | 2      | 2.06%   |
| KIOXIA-EXCERIA                 | 2         | 3      | 2.06%   |
| Kingston                       | 2         | 2      | 2.06%   |
| Corsair                        | 2         | 2      | 2.06%   |
| Solid State Storage Technology | 1         | 1      | 1.03%   |
| PLEXTOR                        | 1         | 1      | 1.03%   |
| Phison                         | 1         | 1      | 1.03%   |
| OCZ-VERTEX                     | 1         | 1      | 1.03%   |
| Netac                          | 1         | 1      | 1.03%   |
| KIOXIA                         | 1         | 1      | 1.03%   |
| Kingchuxing                    | 1         | 2      | 1.03%   |
| HGST                           | 1         | 1      | 1.03%   |
| GOODRAM                        | 1         | 1      | 1.03%   |
| A-DATA Technology              | 1         | 1      | 1.03%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| WDC WD30EFRX-68EUZN0 3TB                   | 2         | 1.8%    |
| Toshiba DT01ACA100 1TB                     | 2         | 1.8%    |
| Samsung SSD 970 EVO 500GB                  | 2         | 1.8%    |
| Samsung MZVLB512HBJQ-000L2 512GB           | 2         | 1.8%    |
| Intel SSDPEKNW010T8 1TB                    | 2         | 1.8%    |
| Intel SSDPEKNU512GZ 512GB                  | 2         | 1.8%    |
| Crucial CT1000P1SSD8 1TB                   | 2         | 1.8%    |
| WDC WDS500G2X0C-00L350 500GB               | 1         | 0.9%    |
| WDC WDS500G2B0B-00YS70 500GB SSD           | 1         | 0.9%    |
| WDC WDS500G2B0A-00SM50 500GB SSD           | 1         | 0.9%    |
| WDC WDS250G2X0C-00L350 250GB               | 1         | 0.9%    |
| WDC WDS240G2G0A 240GB SSD                  | 1         | 0.9%    |
| WDC WDS100T2B0C-00PXH0 1TB                 | 1         | 0.9%    |
| WDC WD60EFRX-68L0BN1 6TB                   | 1         | 0.9%    |
| WDC WD5000AZLX-00JKKA0 500GB               | 1         | 0.9%    |
| WDC WD30EFRX-68AX9N0 3TB                   | 1         | 0.9%    |
| WDC WD2500BEVS-22UST0 250GB                | 1         | 0.9%    |
| WDC WD20EZRX-00D8PB0 2TB                   | 1         | 0.9%    |
| WDC WD20EFRX-68EUZN0 2TB                   | 1         | 0.9%    |
| WDC WD10PURX-64E5EY0 1TB                   | 1         | 0.9%    |
| WDC WD10EZEX-60WN4A1 1TB                   | 1         | 0.9%    |
| WDC WD10EZEX-22M                           | 1         | 0.9%    |
| WDC WD10EZEX-08WN4A0 1TB                   | 1         | 0.9%    |
| WDC WD10EZEX-08M2NA0 1TB                   | 1         | 0.9%    |
| WDC WD10EARS-00MVWB0 1TB                   | 1         | 0.9%    |
| WDC WD10EADS-00L5B1 1TB                    | 1         | 0.9%    |
| WDC WD1002FBYS-18W8B0 1TB                  | 1         | 0.9%    |
| WDC PC SN730 SDBPNTY-512G-1006 512GB       | 1         | 0.9%    |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB       | 1         | 0.9%    |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB       | 1         | 0.9%    |
| WDC PC SN520 SDAPNUW-512G-1014 512GB       | 1         | 0.9%    |
| Unknown USB DISK 3.2 1TB                   | 1         | 0.9%    |
| Unknown MMC Card  32GB                     | 1         | 0.9%    |
| Toshiba THNSN5512GPUK NVMe 512GB           | 1         | 0.9%    |
| Toshiba KXG6AZNV512G 512GB                 | 1         | 0.9%    |
| Toshiba KSG60ZMV512G M.2 2280 512GB SSD    | 1         | 0.9%    |
| Team TM8PS7256G 256GB SSD                  | 1         | 0.9%    |
| Team TM8FP2240G 240GB                      | 1         | 0.9%    |
| Solid State Storage NVMe SSD Drive 256GB   | 1         | 0.9%    |
| SK Hynix SKHynix_HFS001TDE9X084N 1TB       | 1         | 0.9%    |
| SK Hynix PC711 NVMe 512GB                  | 1         | 0.9%    |
| SK Hynix HFM512GDHTNG-8710B 512GB          | 1         | 0.9%    |
| SK Hynix HFM512GD3JX016N 512GB             | 1         | 0.9%    |
| SK Hynix BC711 NVMe 512GB                  | 1         | 0.9%    |
| Seagate ST4000DM005-2DP166 4TB             | 1         | 0.9%    |
| Seagate ST4000DM004-2CV104 4TB             | 1         | 0.9%    |
| Seagate ST3500630AS 500GB                  | 1         | 0.9%    |
| Seagate ST3250318AS 250GB                  | 1         | 0.9%    |
| Seagate ST3160023AS 160GB                  | 1         | 0.9%    |
| Seagate ST2000DM001-1ER164 2TB             | 1         | 0.9%    |
| Seagate ST1000LM049-2GH172 1TB             | 1         | 0.9%    |
| Seagate ST1000LM035-1RK172 1TB             | 1         | 0.9%    |
| Seagate ST1000LM035-1RK1 1TB               | 1         | 0.9%    |
| Seagate ST10000NM0568-2H5110 10TB          | 1         | 0.9%    |
| Seagate ST10000NM0156-2AA111 10TB          | 1         | 0.9%    |
| Seagate FireCuda 530 ZP4000GM30013 4TB     | 1         | 0.9%    |
| Seagate FireCuda 520 SSD ZP2000GM30002 2TB | 1         | 0.9%    |
| SanDisk SSD PLUS 1000GB                    | 1         | 0.9%    |
| SanDisk SDSSDHII480G 480GB                 | 1         | 0.9%    |
| Samsung SSD 980 PRO 2TB                    | 1         | 0.9%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 13        | 21     | 46.43%  |
| Seagate | 9         | 18     | 32.14%  |
| Hitachi | 3         | 4      | 10.71%  |
| Toshiba | 2         | 2      | 7.14%   |
| HGST    | 1         | 1      | 3.57%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 8      | 35%     |
| WDC                 | 3         | 3      | 15%     |
| SanDisk             | 2         | 2      | 10%     |
| Toshiba             | 1         | 1      | 5%      |
| Team                | 1         | 2      | 5%      |
| OCZ-VERTEX          | 1         | 1      | 5%      |
| Kingston            | 1         | 1      | 5%      |
| Intel               | 1         | 1      | 5%      |
| GOODRAM             | 1         | 1      | 5%      |
| Crucial             | 1         | 6      | 5%      |
| Corsair             | 1         | 1      | 5%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 42        | 61     | 50.6%   |
| HDD     | 21        | 46     | 25.3%   |
| SSD     | 18        | 27     | 21.69%  |
| MMC     | 1         | 4      | 1.2%    |
| Unknown | 1         | 3      | 1.2%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 42        | 61     | 56.76%  |
| SATA | 30        | 73     | 40.54%  |
| SAS  | 1         | 3      | 1.35%   |
| MMC  | 1         | 4      | 1.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 17        | 21     | 41.46%  |
| 0.01-0.5   | 12        | 24     | 29.27%  |
| 1.01-2.0   | 5         | 8      | 12.2%   |
| 4.01-10.0  | 3         | 11     | 7.32%   |
| 3.01-4.0   | 2         | 4      | 4.88%   |
| 2.01-3.0   | 2         | 5      | 4.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 17        | 29.31%  |
| 501-1000       | 12        | 20.69%  |
| 1001-2000      | 9         | 15.52%  |
| More than 3000 | 5         | 8.62%   |
| 101-250        | 5         | 8.62%   |
| 1-20           | 4         | 6.9%    |
| 2001-3000      | 2         | 3.45%   |
| Unknown        | 2         | 3.45%   |
| 21-50          | 1         | 1.72%   |
| 51-100         | 1         | 1.72%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 10        | 17.54%  |
| 1-20           | 10        | 17.54%  |
| 251-500        | 9         | 15.79%  |
| 21-50          | 6         | 10.53%  |
| 501-1000       | 6         | 10.53%  |
| 1001-2000      | 5         | 8.77%   |
| 51-100         | 5         | 8.77%   |
| More than 3000 | 4         | 7.02%   |
| Unknown        | 2         | 3.51%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC WD60EFRX-68L0BN1 6TB       | 1         | 3      | 8.33%   |
| WDC WD30EFRX-68AX9N0 3TB       | 1         | 2      | 8.33%   |
| WDC WD20EZRX-00D8PB0 2TB       | 1         | 1      | 8.33%   |
| WDC WD1002FBYS-18W8B0 1TB      | 1         | 1      | 8.33%   |
| Seagate ST3160023AS 160GB      | 1         | 1      | 8.33%   |
| Seagate ST1000LM049-2GH172 1TB | 1         | 1      | 8.33%   |
| Seagate ST1000LM035-1RK172 1TB | 1         | 1      | 8.33%   |
| SanDisk SSD PLUS 1000GB        | 1         | 1      | 8.33%   |
| Intel SSDPEKKF256G8L 256GB     | 1         | 1      | 8.33%   |
| Hitachi HUA721010KLA330 1TB    | 1         | 1      | 8.33%   |
| Hitachi HDS722020ALA330 2TB    | 1         | 2      | 8.33%   |
| Crucial CT1000P1SSD8 1TB       | 1         | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 7      | 33.33%  |
| Seagate | 3         | 3      | 25%     |
| Hitachi | 2         | 3      | 16.67%  |
| SanDisk | 1         | 1      | 8.33%   |
| Intel   | 1         | 1      | 8.33%   |
| Crucial | 1         | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 7      | 44.44%  |
| Seagate | 3         | 3      | 33.33%  |
| Hitachi | 2         | 3      | 22.22%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 13     | 70%     |
| NVMe | 2         | 2      | 20%     |
| SSD  | 1         | 1      | 10%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Toshiba THNSN5512GPUK NVMe 512GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 51        | 108    | 75%     |
| Malfunc  | 10        | 16     | 14.71%  |
| Detected | 6         | 16     | 8.82%   |
| Failed   | 1         | 1      | 1.47%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 27        | 27.84%  |
| AMD                            | 19        | 19.59%  |
| Samsung Electronics            | 14        | 14.43%  |
| Sandisk                        | 7         | 7.22%   |
| SK Hynix                       | 5         | 5.15%   |
| ASMedia Technology             | 4         | 4.12%   |
| Toshiba America Info Systems   | 3         | 3.09%   |
| Phison Electronics             | 3         | 3.09%   |
| Solid State Storage Technology | 2         | 2.06%   |
| Silicon Motion                 | 2         | 2.06%   |
| Seagate Technology             | 2         | 2.06%   |
| Micron/Crucial Technology      | 2         | 2.06%   |
| KIOXIA                         | 2         | 2.06%   |
| Silicon Image                  | 1         | 1.03%   |
| Micron Technology              | 1         | 1.03%   |
| Marvell Technology Group       | 1         | 1.03%   |
| Kingston Technology Company    | 1         | 1.03%   |
| ADATA Technology               | 1         | 1.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 17        | 16.19%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 9         | 8.57%   |
| SK Hynix Gold P31 SSD                                                          | 4         | 3.81%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 4         | 3.81%   |
| Intel SSD 660P Series                                                          | 3         | 2.86%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 2.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 2.86%   |
| Solid State Storage Non-Volatile memory controller                             | 2         | 1.9%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 2         | 1.9%    |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 1.9%    |
| Sandisk Non-Volatile memory controller                                         | 2         | 1.9%    |
| Samsung NVMe SSD Controller 980                                                | 2         | 1.9%    |
| Phison E16 PCIe4 NVMe Controller                                               | 2         | 1.9%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 2         | 1.9%    |
| Intel Non-Volatile memory controller                                           | 2         | 1.9%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 1.9%    |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 1.9%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 1.9%    |
| AMD X370 Series Chipset SATA Controller                                        | 2         | 1.9%    |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                       | 2         | 1.9%    |
| AMD 400 Series Chipset SATA Controller                                         | 2         | 1.9%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.95%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 0.95%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 1         | 0.95%   |
| SK Hynix BC501 NVMe Solid State Drive                                          | 1         | 0.95%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1         | 0.95%   |
| Seagate FireCuda 530 SSD                                                       | 1         | 0.95%   |
| Seagate FireCuda 520 SSD                                                       | 1         | 0.95%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 1         | 0.95%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 0.95%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 0.95%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.95%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 0.95%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 0.95%   |
| Phison E7 NVMe Controller                                                      | 1         | 0.95%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1         | 0.95%   |
| Micron/Crucial NVMe Controller                                                 | 1         | 0.95%   |
| Micron Non-Volatile memory controller                                          | 1         | 0.95%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1         | 0.95%   |
| KIOXIA NVMe SSD                                                                | 1         | 0.95%   |
| KIOXIA Non-Volatile memory controller                                          | 1         | 0.95%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 0.95%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 0.95%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                | 1         | 0.95%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 1         | 0.95%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1         | 0.95%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 0.95%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1         | 0.95%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 1         | 0.95%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 1         | 0.95%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 1         | 0.95%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 1         | 0.95%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1         | 0.95%   |
| AMD 300 Series Chipset SATA Controller                                         | 1         | 0.95%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 1         | 0.95%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 42        | 50%     |
| SATA | 38        | 45.24%  |
| RAID | 2         | 2.38%   |
| IDE  | 2         | 2.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 29        | 51.79%  |
| AMD    | 26        | 46.43%  |
| ARM    | 1         | 1.79%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz              | 3         | 5.36%   |
| AMD Ryzen 9 3950X 16-Core Processor            | 3         | 5.36%   |
| Intel Xeon CPU E3-1270 v3 @ 3.50GHz            | 2         | 3.57%   |
| AMD Ryzen 7 5700U with Radeon Graphics         | 2         | 3.57%   |
| AMD Ryzen 5 1600 Six-Core Processor            | 2         | 3.57%   |
| Intel Xeon CPU X5680 @ 3.33GHz                 | 1         | 1.79%   |
| Intel Pentium 4 CPU 3.20GHz                    | 1         | 1.79%   |
| Intel Core i9-9900K CPU @ 3.60GHz              | 1         | 1.79%   |
| Intel Core i7-8809G CPU @ 3.10GHz              | 1         | 1.79%   |
| Intel Core i7-8650U CPU @ 1.90GHz              | 1         | 1.79%   |
| Intel Core i7-8565U CPU @ 1.80GHz              | 1         | 1.79%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz             | 1         | 1.79%   |
| Intel Core i7-6700K CPU @ 4.00GHz              | 1         | 1.79%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz             | 1         | 1.79%   |
| Intel Core i7-10850H CPU @ 2.70GHz             | 1         | 1.79%   |
| Intel Core i7-10700F CPU @ 2.90GHz             | 1         | 1.79%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz             | 1         | 1.79%   |
| Intel Core i7-10510U CPU @ 1.80GHz             | 1         | 1.79%   |
| Intel Core i5-9300H CPU @ 2.40GHz              | 1         | 1.79%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 1         | 1.79%   |
| Intel Core i5-6400 CPU @ 2.70GHz               | 1         | 1.79%   |
| Intel Core i5-4670K CPU @ 3.40GHz              | 1         | 1.79%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz             | 1         | 1.79%   |
| Intel Core i5-10210U CPU @ 1.60GHz             | 1         | 1.79%   |
| Intel 12th Gen Core i7-12700K                  | 1         | 1.79%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz        | 1         | 1.79%   |
| Intel 11th Gen Core i7-11850H @ 2.50GHz        | 1         | 1.79%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz        | 1         | 1.79%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 1         | 1.79%   |
| ARM Processor                                  | 1         | 1.79%   |
| AMD Ryzen Threadripper 3960X 24-Core Processor | 1         | 1.79%   |
| AMD Ryzen 9 5950X 16-Core Processor            | 1         | 1.79%   |
| AMD Ryzen 9 5900HX with Radeon Graphics        | 1         | 1.79%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 1         | 1.79%   |
| AMD Ryzen 7 PRO 5750G with Radeon Graphics     | 1         | 1.79%   |
| AMD Ryzen 7 5800HS with Radeon Graphics        | 1         | 1.79%   |
| AMD Ryzen 7 5800H with Radeon Graphics         | 1         | 1.79%   |
| AMD Ryzen 7 4800H with Radeon Graphics         | 1         | 1.79%   |
| AMD Ryzen 7 4700U with Radeon Graphics         | 1         | 1.79%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx  | 1         | 1.79%   |
| AMD Ryzen 7 1700X Eight-Core Processor         | 1         | 1.79%   |
| AMD Ryzen 5 PRO 4650G with Radeon Graphics     | 1         | 1.79%   |
| AMD Ryzen 5 5600H with Radeon Graphics         | 1         | 1.79%   |
| AMD Ryzen 5 5500U with Radeon Graphics         | 1         | 1.79%   |
| AMD Ryzen 5 3600 6-Core Processor              | 1         | 1.79%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx  | 1         | 1.79%   |
| AMD Ryzen 5 2600 Six-Core Processor            | 1         | 1.79%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx  | 1         | 1.79%   |
| AMD E1-1200 APU with Radeon HD Graphics        | 1         | 1.79%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 13        | 23.21%  |
| AMD Ryzen 7            | 8         | 14.29%  |
| AMD Ryzen 5            | 7         | 12.5%   |
| Other                  | 6         | 10.71%  |
| Intel Core i5          | 6         | 10.71%  |
| AMD Ryzen 9            | 6         | 10.71%  |
| Intel Xeon             | 3         | 5.36%   |
| Intel Pentium 4        | 1         | 1.79%   |
| Intel Core i9          | 1         | 1.79%   |
| AMD Ryzen Threadripper | 1         | 1.79%   |
| AMD Ryzen 7 PRO        | 1         | 1.79%   |
| AMD Ryzen 5 PRO        | 1         | 1.79%   |
| AMD Ryzen 3            | 1         | 1.79%   |
| AMD E1                 | 1         | 1.79%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 21        | 37.5%   |
| 8       | 12        | 21.43%  |
| 6       | 11        | 19.64%  |
| 16      | 4         | 7.14%   |
| 12      | 3         | 5.36%   |
| 2       | 2         | 3.57%   |
| 24      | 1         | 1.79%   |
| 1       | 1         | 1.79%   |
| Unknown | 1         | 1.79%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 54        | 96.43%  |
| 2       | 1         | 1.79%   |
| Unknown | 1         | 1.79%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 49        | 87.5%   |
| 1       | 6         | 10.71%  |
| Unknown | 1         | 1.79%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 56        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 7         | 12.5%   |
| 0x906ea    | 4         | 7.14%   |
| 0x0a50000c | 4         | 7.14%   |
| 0x906e9    | 3         | 5.36%   |
| 0x806ec    | 3         | 5.36%   |
| 0x08701021 | 3         | 5.36%   |
| 0x08001138 | 3         | 5.36%   |
| 0x806c1    | 2         | 3.57%   |
| 0x706e5    | 2         | 3.57%   |
| 0x506e3    | 2         | 3.57%   |
| 0x306c3    | 2         | 3.57%   |
| 0x08608103 | 2         | 3.57%   |
| 0x08600103 | 2         | 3.57%   |
| 0x08108109 | 2         | 3.57%   |
| 0xf43      | 1         | 1.79%   |
| 0xa0655    | 1         | 1.79%   |
| 0xa0652    | 1         | 1.79%   |
| 0x906ed    | 1         | 1.79%   |
| 0x90672    | 1         | 1.79%   |
| 0x806d1    | 1         | 1.79%   |
| 0x206c2    | 1         | 1.79%   |
| 0x0a50000b | 1         | 1.79%   |
| 0x0a201016 | 1         | 1.79%   |
| 0x08608102 | 1         | 1.79%   |
| 0x08600106 | 1         | 1.79%   |
| 0x08301039 | 1         | 1.79%   |
| 0x08108102 | 1         | 1.79%   |
| 0x0800820d | 1         | 1.79%   |
| 0x05000119 | 1         | 1.79%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 12        | 21.43%  |
| Zen 2            | 9         | 16.07%  |
| Zen 3            | 6         | 10.71%  |
| Zen+             | 4         | 7.14%   |
| Unknown          | 4         | 7.14%   |
| Zen              | 3         | 5.36%   |
| TigerLake        | 3         | 5.36%   |
| Skylake          | 3         | 5.36%   |
| IceLake          | 3         | 5.36%   |
| Haswell          | 3         | 5.36%   |
| CometLake        | 2         | 3.57%   |
| Westmere         | 1         | 1.79%   |
| NetBurst         | 1         | 1.79%   |
| Bobcat           | 1         | 1.79%   |
| Alderlake Hybrid | 1         | 1.79%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| AMD                        | 25        | 34.72%  |
| Nvidia                     | 23        | 31.94%  |
| Intel                      | 22        | 30.56%  |
| Matrox Electronics Systems | 2         | 2.78%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]              | 5         | 6.76%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                            | 4         | 5.41%   |
| AMD Cezanne                                                          | 4         | 5.41%   |
| Nvidia GP108M [GeForce MX250]                                        | 3         | 4.05%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                            | 3         | 4.05%   |
| Intel HD Graphics 630                                                | 3         | 4.05%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series] | 3         | 4.05%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                       | 3         | 4.05%   |
| AMD Lucienne                                                         | 3         | 4.05%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                      | 2         | 2.7%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                           | 2         | 2.7%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                  | 2         | 2.7%    |
| Nvidia GM206 [GeForce GTX 960]                                       | 2         | 2.7%    |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)    | 2         | 2.7%    |
| Intel HD Graphics 530                                                | 2         | 2.7%    |
| Intel CometLake-U GT2 [UHD Graphics]                                 | 2         | 2.7%    |
| AMD Renoir                                                           | 2         | 2.7%    |
| AMD Navi 22 [Radeon RX 6700/6700 XT / 6800M]                         | 2         | 2.7%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                           | 1         | 1.35%   |
| Nvidia TU117GLM [T600 Mobile]                                        | 1         | 1.35%   |
| Nvidia TU116 [GeForce GTX 1650]                                      | 1         | 1.35%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                            | 1         | 1.35%   |
| Nvidia GP108 [GeForce GT 1030]                                       | 1         | 1.35%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                              | 1         | 1.35%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                              | 1         | 1.35%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                   | 1         | 1.35%   |
| Nvidia GM204 [GeForce GTX 970]                                       | 1         | 1.35%   |
| Nvidia GM108M [GeForce 940MX]                                        | 1         | 1.35%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                           | 1         | 1.35%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                      | 1         | 1.35%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                           | 1         | 1.35%   |
| Intel UHD Graphics 620                                               | 1         | 1.35%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                 | 1         | 1.35%   |
| Intel Iris Plus Graphics G7                                          | 1         | 1.35%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                               | 1         | 1.35%   |
| Intel CometLake-H GT2 [UHD Graphics]                                 | 1         | 1.35%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                            | 1         | 1.35%   |
| Intel AlderLake-S GT1                                                | 1         | 1.35%   |
| AMD Wrestler [Radeon HD 7310]                                        | 1         | 1.35%   |
| AMD Polaris 22 XT [Radeon RX Vega M GH]                              | 1         | 1.35%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                       | 1         | 1.35%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                       | 1         | 1.35%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]  | 1         | 1.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 18        | 32.14%  |
| Intel + Nvidia | 11        | 19.64%  |
| 1 x Intel      | 9         | 16.07%  |
| 1 x Nvidia     | 7         | 12.5%   |
| AMD + Nvidia   | 5         | 8.93%   |
| Other          | 2         | 3.57%   |
| 2 x AMD        | 2         | 3.57%   |
| 1 x Matrox     | 2         | 3.57%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 34        | 60.71%  |
| Proprietary | 17        | 30.36%  |
| Unknown     | 5         | 8.93%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 42.11%  |
| 3.01-4.0   | 9         | 15.79%  |
| 1.01-2.0   | 8         | 14.04%  |
| 8.01-16.0  | 6         | 10.53%  |
| 0.01-0.5   | 4         | 7.02%   |
| 0.51-1.0   | 3         | 5.26%   |
| 7.01-8.0   | 2         | 3.51%   |
| 5.01-6.0   | 1         | 1.75%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 10        | 14.71%  |
| AU Optronics            | 8         | 11.76%  |
| Chimei Innolux          | 5         | 7.35%   |
| Sharp                   | 3         | 4.41%   |
| Lenovo                  | 3         | 4.41%   |
| Goldstar                | 3         | 4.41%   |
| Dell                    | 3         | 4.41%   |
| BenQ                    | 3         | 4.41%   |
| AOC                     | 3         | 4.41%   |
| Acer                    | 3         | 4.41%   |
| Samsung Electronics     | 2         | 2.94%   |
| Hewlett-Packard         | 2         | 2.94%   |
| ASUSTek Computer        | 2         | 2.94%   |
| Toshiba                 | 1         | 1.47%   |
| Sceptre Tech            | 1         | 1.47%   |
| Sceptre                 | 1         | 1.47%   |
| Philips                 | 1         | 1.47%   |
| PANDA                   | 1         | 1.47%   |
| NEC Computers           | 1         | 1.47%   |
| MXX                     | 1         | 1.47%   |
| MStar                   | 1         | 1.47%   |
| Mi                      | 1         | 1.47%   |
| LG Display              | 1         | 1.47%   |
| Iiyama                  | 1         | 1.47%   |
| HannStar                | 1         | 1.47%   |
| Gigabyte Technology     | 1         | 1.47%   |
| Gateway                 | 1         | 1.47%   |
| CSO                     | 1         | 1.47%   |
| Chi Mei Optoelectronics | 1         | 1.47%   |
| Belinea                 | 1         | 1.47%   |
| Ancor Communications    | 1         | 1.47%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                  | 2         | 2.74%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch         | 2         | 2.74%   |
| Toshiba PA3552 TOS501C 1680x1050 433x270mm 20.1-inch                   | 1         | 1.37%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                | 1         | 1.37%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch                | 1         | 1.37%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                | 1         | 1.37%   |
| Sceptre Tech C305W-2560UN SPT0C0D 2560x1080 690x291mm 29.5-inch        | 1         | 1.37%   |
| Sceptre LCD Monitor C305W-2560UN                                       | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch   | 1         | 1.37%   |
| Samsung Electronics C49HG9x SAM0E5E 3840x1080 1200x340mm 49.1-inch     | 1         | 1.37%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 1         | 1.37%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                | 1         | 1.37%   |
| NEC Computers EA274WMi NEC6960 2560x1440 597x336mm 27.0-inch           | 1         | 1.37%   |
| MXX O-3-H MXX0001 3840x2160 1872x1053mm 84.6-inch                      | 1         | 1.37%   |
| MStar DP MST2380 2560x1440 597x336mm 27.0-inch                         | 1         | 1.37%   |
| Mi Monitor XMI3444 3440x1440 800x330mm 34.1-inch                       | 1         | 1.37%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch           | 1         | 1.37%   |
| Lenovo Q27q-10 LEN65F4 2560x1440 597x336mm 27.0-inch                   | 1         | 1.37%   |
| Lenovo P24h-10 LEN61AE 2560x1440 527x296mm 23.8-inch                   | 1         | 1.37%   |
| Lenovo LEN P27h-10 LEN61AF 2560x1440 597x336mm 27.0-inch               | 1         | 1.37%   |
| Iiyama PL2792Q IVM6630 2560x1440 597x336mm 27.0-inch                   | 1         | 1.37%   |
| Hewlett-Packard LV1561w HWP2837 1366x768 344x194mm 15.5-inch           | 1         | 1.37%   |
| Hewlett-Packard LP2475w HWP26F9 1920x1200 546x352mm 25.6-inch          | 1         | 1.37%   |
| Hewlett-Packard 22f HPN3541 1920x1080 476x268mm 21.5-inch              | 1         | 1.37%   |
| HannStar JC198D HSD0CC6 1280x1024 376x301mm 19.0-inch                  | 1         | 1.37%   |
| Goldstar ULTRAWIDE GSM76E4 3440x1440 800x335mm 34.1-inch               | 1         | 1.37%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch               | 1         | 1.37%   |
| Gigabyte Technology AORUS AD27QD GBT2701 2560x1440 610x350mm 27.7-inch | 1         | 1.37%   |
| Gateway FPD1765 GWY06E9 1280x1024 338x270mm 17.0-inch                  | 1         | 1.37%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                      | 1         | 1.37%   |
| Dell U2515H DELD070 2560x1440 553x311mm 25.0-inch                      | 1         | 1.37%   |
| Dell S3221QS DELD107 3840x2160 697x392mm 31.5-inch                     | 1         | 1.37%   |
| Dell P2219HC DELA11A 1920x1080 476x267mm 21.5-inch                     | 1         | 1.37%   |
| CSO LCD Monitor CSO1609 2560x1600 345x215mm 16.0-inch                  | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 380x210mm 17.1-inch       | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN14E7 1920x1080 309x173mm 13.9-inch       | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN14D3 1920x1080 309x173mm 13.9-inch       | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch       | 1         | 1.37%   |
| Chi Mei Optoelectronics CMC 19AW CMO2198 1440x900 408x255mm 18.9-inch  | 1         | 1.37%   |
| BOE LCD Monitor BOE09B6 2560x1600 345x215mm 16.0-inch                  | 1         | 1.37%   |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                  | 1         | 1.37%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                  | 1         | 1.37%   |
| BOE LCD Monitor BOE0928 1920x1080 344x194mm 15.5-inch                  | 1         | 1.37%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                  | 1         | 1.37%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                  | 1         | 1.37%   |
| BOE LCD Monitor BOE08D6 1920x1080 309x174mm 14.0-inch                  | 1         | 1.37%   |
| BOE LCD Monitor BOE0898 1920x1080 294x165mm 13.3-inch                  | 1         | 1.37%   |
| BOE LCD Monitor BOE086E 1920x1080 344x194mm 15.5-inch                  | 1         | 1.37%   |
| BOE LCD Monitor BOE0821 3840x2160 309x174mm 14.0-inch                  | 1         | 1.37%   |
| BenQ G2420HD BNQ7840 1920x1080 531x299mm 24.0-inch                     | 1         | 1.37%   |
| BenQ EX2780Q BNQ7F76 2560x1440 597x336mm 27.0-inch                     | 1         | 1.37%   |
| BenQ E2200HD BNQ790C 1920x1080 477x268mm 21.5-inch                     | 1         | 1.37%   |
| Belinea Belinea101735 MAX06B2 1280x1024 338x270mm 17.0-inch            | 1         | 1.37%   |
| AU Optronics LCD Monitor AUODF87 1920x1080 344x193mm 15.5-inch         | 1         | 1.37%   |
| AU Optronics LCD Monitor AUO32EB 3840x2160 344x193mm 15.5-inch         | 1         | 1.37%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch         | 1         | 1.37%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch         | 1         | 1.37%   |
| AU Optronics LCD Monitor AUO233D 1920x1080 309x174mm 14.0-inch         | 1         | 1.37%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch         | 1         | 1.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 30        | 44.12%  |
| 2560x1440 (QHD)    | 13        | 19.12%  |
| 3840x2160 (4K)     | 7         | 10.29%  |
| 3440x1440          | 3         | 4.41%   |
| 2560x1600          | 2         | 2.94%   |
| 2560x1080          | 2         | 2.94%   |
| 1366x768 (WXGA)    | 2         | 2.94%   |
| 1280x1024 (SXGA)   | 2         | 2.94%   |
| 6400x1080          | 1         | 1.47%   |
| 3840x1080          | 1         | 1.47%   |
| 2256x1504          | 1         | 1.47%   |
| 1920x1200 (WUXGA)  | 1         | 1.47%   |
| 1680x1050 (WSXGA+) | 1         | 1.47%   |
| 1440x900 (WXGA+)   | 1         | 1.47%   |
| Unknown            | 1         | 1.47%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 17        | 24.29%  |
| 27      | 14        | 20%     |
| 13      | 6         | 8.57%   |
| 14      | 5         | 7.14%   |
| 34      | 4         | 5.71%   |
| 21      | 4         | 5.71%   |
| 23      | 3         | 4.29%   |
| 17      | 3         | 4.29%   |
| 25      | 2         | 2.86%   |
| 24      | 2         | 2.86%   |
| 19      | 2         | 2.86%   |
| 16      | 2         | 2.86%   |
| 84      | 1         | 1.43%   |
| 49      | 1         | 1.43%   |
| 31      | 1         | 1.43%   |
| 29      | 1         | 1.43%   |
| 20      | 1         | 1.43%   |
| Unknown | 1         | 1.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 30        | 45.45%  |
| 501-600     | 16        | 24.24%  |
| 401-500     | 6         | 9.09%   |
| 701-800     | 4         | 6.06%   |
| 601-700     | 3         | 4.55%   |
| 351-400     | 2         | 3.03%   |
| 201-300     | 2         | 3.03%   |
| 1501-2000   | 1         | 1.52%   |
| 1001-1500   | 1         | 1.52%   |
| Unknown     | 1         | 1.52%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 46        | 75.41%  |
| 21/9    | 5         | 8.2%    |
| 16/10   | 5         | 8.2%    |
| 5/4     | 2         | 3.28%   |
| 32/9    | 1         | 1.64%   |
| 3/2     | 1         | 1.64%   |
| Unknown | 1         | 1.64%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inchÂ² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 17        | 25%     |
| 301-350        | 14        | 20.59%  |
| 81-90          | 10        | 14.71%  |
| 201-250        | 7         | 10.29%  |
| 351-500        | 5         | 7.35%   |
| 151-200        | 4         | 5.88%   |
| 251-300        | 2         | 2.94%   |
| 141-150        | 2         | 2.94%   |
| 111-120        | 2         | 2.94%   |
| More than 1000 | 1         | 1.47%   |
| 71-80          | 1         | 1.47%   |
| 121-130        | 1         | 1.47%   |
| 501-1000       | 1         | 1.47%   |
| Unknown        | 1         | 1.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 22        | 34.92%  |
| 101-120       | 18        | 28.57%  |
| 51-100        | 11        | 17.46%  |
| 161-240       | 7         | 11.11%  |
| More than 240 | 3         | 4.76%   |
| 1-50          | 1         | 1.59%   |
| Unknown       | 1         | 1.59%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 37        | 66.07%  |
| 2     | 12        | 21.43%  |
| 0     | 4         | 7.14%   |
| 3     | 3         | 5.36%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 40        | 51.95%  |
| Realtek Semiconductor    | 24        | 31.17%  |
| Qualcomm Atheros         | 3         | 3.9%    |
| MEDIATEK                 | 2         | 2.6%    |
| Aquantia                 | 2         | 2.6%    |
| Samsung Electronics      | 1         | 1.3%    |
| Raspberry Pi             | 1         | 1.3%    |
| Ralink Technology        | 1         | 1.3%    |
| Microsoft                | 1         | 1.3%    |
| Marvell Technology Group | 1         | 1.3%    |
| ICS Advent               | 1         | 1.3%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 16.84%  |
| Intel Wi-Fi 6 AX200                                               | 11        | 11.58%  |
| Intel I211 Gigabit Network Connection                             | 5         | 5.26%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 4.21%   |
| Intel I210 Gigabit Network Connection                             | 4         | 4.21%   |
| Intel Wireless 8265 / 8275                                        | 3         | 3.16%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 3.16%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 2.11%   |
| Intel Wireless-AC 9260                                            | 2         | 2.11%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 2.11%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 2.11%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 2.11%   |
| Intel Ethernet Controller I225-V                                  | 2         | 2.11%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 2.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 2.11%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2         | 2.11%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.05%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 1.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.05%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 1.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.05%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.05%   |
| Raspberry Pi Pico                                                 | 1         | 1.05%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 1.05%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.05%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.05%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1         | 1.05%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 1         | 1.05%   |
| Microsoft XBOX ACC                                                | 1         | 1.05%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 1.05%   |
| Intel Wireless 8260                                               | 1         | 1.05%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 1.05%   |
| Intel I350 Gigabit Network Connection                             | 1         | 1.05%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.05%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.05%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 1.05%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.05%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.05%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.05%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 1.05%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1         | 1.05%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 1.05%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 1         | 1.05%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.05%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1         | 1.05%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 33        | 78.57%  |
| Realtek Semiconductor | 4         | 9.52%   |
| MEDIATEK              | 2         | 4.76%   |
| Ralink Technology     | 1         | 2.38%   |
| Qualcomm Atheros      | 1         | 2.38%   |
| Microsoft             | 1         | 2.38%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 11        | 25.58%  |
| Intel Wireless 8265 / 8275                                    | 3         | 6.98%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 3         | 6.98%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter | 2         | 4.65%   |
| Intel Wireless-AC 9260                                        | 2         | 4.65%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 2         | 4.65%   |
| Intel Wi-Fi 6 AX201                                           | 2         | 4.65%   |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 2         | 4.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 2         | 4.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 1         | 2.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 1         | 2.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1         | 2.33%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter               | 1         | 2.33%   |
| Ralink RT2870/RT3070 Wireless Adapter                         | 1         | 2.33%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter              | 1         | 2.33%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter    | 1         | 2.33%   |
| Microsoft XBOX ACC                                            | 1         | 2.33%   |
| Intel Wireless 8260                                           | 1         | 2.33%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 1         | 2.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 1         | 2.33%   |
| Intel Comet Lake PCH CNVi WiFi                                | 1         | 2.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 1         | 2.33%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 1         | 2.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 22        | 45.83%  |
| Intel                    | 19        | 39.58%  |
| Qualcomm Atheros         | 2         | 4.17%   |
| Aquantia                 | 2         | 4.17%   |
| Samsung Electronics      | 1         | 2.08%   |
| Marvell Technology Group | 1         | 2.08%   |
| ICS Advent               | 1         | 2.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 31.37%  |
| Intel I211 Gigabit Network Connection                             | 5         | 9.8%    |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 7.84%   |
| Intel I210 Gigabit Network Connection                             | 4         | 7.84%   |
| Intel Ethernet Controller I225-V                                  | 2         | 3.92%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 3.92%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2         | 3.92%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.96%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.96%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.96%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 1.96%   |
| Intel I350 Gigabit Network Connection                             | 1         | 1.96%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.96%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.96%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 1.96%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.96%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.96%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.96%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 1.96%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.96%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1         | 1.96%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 42        | 50%     |
| WiFi     | 41        | 48.81%  |
| Modem    | 1         | 1.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 34        | 53.13%  |
| Ethernet | 30        | 46.88%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 24        | 42.86%  |
| 2     | 23        | 41.07%  |
| 3     | 5         | 8.93%   |
| 0     | 2         | 3.57%   |
| 6     | 1         | 1.79%   |
| 4     | 1         | 1.79%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 42        | 73.68%  |
| Yes  | 15        | 26.32%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 31        | 72.09%  |
| Realtek Semiconductor   | 4         | 9.3%    |
| Cambridge Silicon Radio | 3         | 6.98%   |
| Toshiba                 | 1         | 2.33%   |
| IMC Networks            | 1         | 2.33%   |
| Foxconn / Hon Hai       | 1         | 2.33%   |
| Edimax Technology       | 1         | 2.33%   |
| ASUSTek Computer        | 1         | 2.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 17        | 39.53%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 6         | 13.95%  |
| Intel Bluetooth wireless interface                  | 3         | 6.98%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 6.98%   |
| Realtek Bluetooth Radio                             | 2         | 4.65%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 4.65%   |
| Intel AX210 Bluetooth                               | 2         | 4.65%   |
| Toshiba RT Bluetooth Radio                          | 1         | 2.33%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 2.33%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 2.33%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.33%   |
| IMC Networks Wireless_Device                        | 1         | 2.33%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 2.33%   |
| Edimax Bluetooth Adapter                            | 1         | 2.33%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 2.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| AMD                                  | 30        | 34.09%  |
| Intel                                | 26        | 29.55%  |
| Nvidia                               | 15        | 17.05%  |
| Thesycon Systemsoftware & Consulting | 2         | 2.27%   |
| SteelSeries ApS                      | 2         | 2.27%   |
| Logitech                             | 2         | 2.27%   |
| C-Media Electronics                  | 2         | 2.27%   |
| ASUSTek Computer                     | 2         | 2.27%   |
| Texas Instruments                    | 1         | 1.14%   |
| SAVITECH                             | 1         | 1.14%   |
| RODE Microphones                     | 1         | 1.14%   |
| Creative Technology                  | 1         | 1.14%   |
| Creative Labs                        | 1         | 1.14%   |
| AudioQuest                           | 1         | 1.14%   |
| ACTIONS                              | 1         | 1.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                     | 14        | 12.61%  |
| AMD Renoir Radeon High Definition Audio Controller                      | 9         | 8.11%   |
| AMD Starship/Matisse HD Audio Controller                                | 7         | 6.31%   |
| Intel Cannon Lake PCH cAVS                                              | 5         | 4.5%    |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]               | 5         | 4.5%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]              | 5         | 4.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller         | 4         | 3.6%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                     | 4         | 3.6%    |
| Nvidia GP106 High Definition Audio Controller                           | 3         | 2.7%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller             | 3         | 2.7%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                     | 3         | 2.7%    |
| Thesycon Systemsoftware & Consulting E30                                | 2         | 1.8%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller          | 2         | 1.8%    |
| Nvidia GM206 High Definition Audio Controller                           | 2         | 1.8%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller               | 2         | 1.8%    |
| Intel Comet Lake PCH-LP cAVS                                            | 2         | 1.8%    |
| Intel Comet Lake PCH cAVS                                               | 2         | 1.8%    |
| Intel CM238 HD Audio Controller                                         | 2         | 1.8%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]            | 2         | 1.8%    |
| Texas Instruments PCM2912A Audio Codec                                  | 1         | 0.9%    |
| SteelSeries ApS SteelSeries Arctis 5                                    | 1         | 0.9%    |
| SteelSeries ApS Arctis 7 wireless adapter                               | 1         | 0.9%    |
| SAVITECH SA9023 audio controller                                        | 1         | 0.9%    |
| RODE Microphones RODE VideoMic NTG                                      | 1         | 0.9%    |
| Nvidia TU116 High Definition Audio Controller                           | 1         | 0.9%    |
| Nvidia TU102 High Definition Audio Controller                           | 1         | 0.9%    |
| Nvidia GP108 High Definition Audio Controller                           | 1         | 0.9%    |
| Nvidia GP107GL High Definition Audio Controller                         | 1         | 0.9%    |
| Nvidia GP104 High Definition Audio Controller                           | 1         | 0.9%    |
| Nvidia GP102 HDMI Audio Controller                                      | 1         | 0.9%    |
| Nvidia GM204 High Definition Audio Controller                           | 1         | 0.9%    |
| Nvidia Audio device                                                     | 1         | 0.9%    |
| Logitech Z-5 Speakers                                                   | 1         | 0.9%    |
| Logitech Yeti X                                                         | 1         | 0.9%    |
| Intel Tiger Lake-H HD Audio Controller                                  | 1         | 0.9%    |
| Intel Sunrise Point-LP HD Audio                                         | 1         | 0.9%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                 | 1         | 0.9%    |
| Intel Cannon Point-LP High Definition Audio Controller                  | 1         | 0.9%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                        | 1         | 0.9%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 1         | 0.9%    |
| Creative Technology Sound BlasterX G6                                   | 1         | 0.9%    |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]           | 1         | 0.9%    |
| C-Media Electronics USB Advanced Audio Device                           | 1         | 0.9%    |
| C-Media Electronics CM108 Audio Controller                              | 1         | 0.9%    |
| AudioQuest SDAC                                                         | 1         | 0.9%    |
| ASUSTek Computer Xonar U1 Audio Station                                 | 1         | 0.9%    |
| ASUSTek Computer USB Audio                                              | 1         | 0.9%    |
| AMD Wrestler HDMI Audio                                                 | 1         | 0.9%    |
| AMD Polaris 22 HDMI Audio                                               | 1         | 0.9%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 1         | 0.9%    |
| AMD FCH Azalia Controller                                               | 1         | 0.9%    |
| ACTIONS EDIFIER M380                                                    | 1         | 0.9%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 21        | 33.33%  |
| Kingston            | 10        | 15.87%  |
| SK Hynix            | 9         | 14.29%  |
| Crucial             | 7         | 11.11%  |
| G.Skill             | 5         | 7.94%   |
| Micron Technology   | 4         | 6.35%   |
| Patriot             | 2         | 3.17%   |
| Unknown             | 1         | 1.59%   |
| Transcend           | 1         | 1.59%   |
| Team                | 1         | 1.59%   |
| Corsair             | 1         | 1.59%   |
| A-DATA Technology   | 1         | 1.59%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 3         | 4.55%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 2667MT/s        | 2         | 3.03%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 3.03%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 2         | 3.03%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 3.03%   |
| Unknown RAM Module 512MB DIMM SDRAM                              | 1         | 1.52%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 1         | 1.52%   |
| Transcend RAM JM3200HSE-32G 32GB SODIMM DDR4 3200MT/s            | 1         | 1.52%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s               | 1         | 1.52%   |
| SK Hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 1         | 1.52%   |
| SK Hynix RAM HMAA2GS6AJR8N-XN 16384MB SODIMM DDR4 3200MT/s       | 1         | 1.52%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.52%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 1.52%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.52%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 1.52%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.52%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.52%   |
| SK Hynix RAM H9HCNNNCPMALHR-NEE 8GB Row Of Chips LPDDR4 4267MT/s | 1         | 1.52%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s              | 1         | 1.52%   |
| Samsung RAM M471B5773CHS-CK0 2048MB SODIMM DDR3 1600MT/s         | 1         | 1.52%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 1.52%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 1.52%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 1.52%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.52%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.52%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.52%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 1.52%   |
| Samsung RAM M378A2G43MX3-CTD 16GB DIMM DDR4 2666MT/s             | 1         | 1.52%   |
| Patriot RAM PSD416G24002S 16GB SODIMM DDR4 2667MT/s              | 1         | 1.52%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3200MT/s              | 1         | 1.52%   |
| Micron RAM Module 16GB SODIMM DDR4 2667MT/s                      | 1         | 1.52%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.52%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 1         | 1.52%   |
| Micron RAM 18KSF1G72AZ-1G6E1 8GB DIMM DDR3 1600MT/s              | 1         | 1.52%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s           | 1         | 1.52%   |
| Kingston RAM KHX1866C10D3/8G 8192MB DIMM DDR3 1867MT/s           | 1         | 1.52%   |
| Kingston RAM KF3200C20S4/32GX 32GB SODIMM DDR4 3200MT/s          | 1         | 1.52%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s            | 1         | 1.52%   |
| Kingston RAM HP26D4S9S8HJ-8 8GB SODIMM DDR4 2667MT/s             | 1         | 1.52%   |
| Kingston RAM 99U5624-013.A00G 8GB SODIMM DDR4 2400MT/s           | 1         | 1.52%   |
| Kingston RAM 9965525-055.A00LF 8GB DIMM DDR3 1600MT/s            | 1         | 1.52%   |
| Kingston RAM 9965487-004.A00LF 4GB DIMM 1066MT/s                 | 1         | 1.52%   |
| Kingston RAM 9905700-053.A00G 8192MB SODIMM DDR4 3200MT/s        | 1         | 1.52%   |
| Kingston RAM 9905625-062.A00G 8192MB DIMM DDR4 2133MT/s          | 1         | 1.52%   |
| G.Skill RAM F4-3600C17-16GTZR 16GB DIMM DDR4 3666MT/s            | 1         | 1.52%   |
| G.Skill RAM F4-3600C17-16GTZKW 16GB DIMM DDR4 3600MT/s           | 1         | 1.52%   |
| G.Skill RAM F4-3600C16-16GVKC 16384MB DIMM DDR4 3866MT/s         | 1         | 1.52%   |
| G.Skill RAM F4-3000C15-8GVRB 8GB DIMM DDR4 2133MT/s              | 1         | 1.52%   |
| G.Skill RAM F3-14900CL9-4GBSR 4GB DIMM DDR3 1800MT/s             | 1         | 1.52%   |
| Crucial RAM CT8G4DFD824A.C16FF 8GB DIMM DDR4 2733MT/s            | 1         | 1.52%   |
| Crucial RAM CT8G4DFD824A.C16FBD1 8GB DIMM DDR4 2400MT/s          | 1         | 1.52%   |
| Crucial RAM CT32G4SFD832A.C16FE 32GB SODIMM DDR4 3200MT/s        | 1         | 1.52%   |
| Crucial RAM CT16G4DFD8213.C16FAD 16GB DIMM DDR4 2133MT/s         | 1         | 1.52%   |
| Crucial RAM BLS4G4D26BFSE.8FE 4GB DIMM DDR4 2667MT/s             | 1         | 1.52%   |
| Crucial RAM BL32G36C16U4B.M16FB1 32GB DIMM DDR4                  | 1         | 1.52%   |
| Crucial RAM BL16G36C16U4RL.M8FB1 16GB DIMM DDR4 4000MT/s         | 1         | 1.52%   |
| Crucial RAM BL16G32C16U4B.M16FE1 16384MB DIMM DDR4 3200MT/s      | 1         | 1.52%   |
| Crucial RAM BL16G32C16U4B.M16FE 16GB DIMM DDR4 3200MT/s          | 1         | 1.52%   |
| Corsair RAM CMK32GX4M2B3200C16 16384MB DIMM DDR4 3400MT/s        | 1         | 1.52%   |
| A-DATA RAM DDR4 3000 2OZ 16GB DIMM DDR4 3000MT/s                 | 1         | 1.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 45        | 84.91%  |
| DDR3    | 4         | 7.55%   |
| SDRAM   | 1         | 1.89%   |
| LPDDR4  | 1         | 1.89%   |
| LPDDR3  | 1         | 1.89%   |
| Unknown | 1         | 1.89%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 28        | 52.83%  |
| DIMM         | 21        | 39.62%  |
| Row Of Chips | 4         | 7.55%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 25        | 43.1%   |
| 16384 | 19        | 32.76%  |
| 32768 | 6         | 10.34%  |
| 4096  | 5         | 8.62%   |
| 2048  | 1         | 1.72%   |
| 1024  | 1         | 1.72%   |
| 512   | 1         | 1.72%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 18        | 31.03%  |
| 2667    | 15        | 25.86%  |
| 2133    | 5         | 8.62%   |
| 3600    | 4         | 6.9%    |
| 1600    | 3         | 5.17%   |
| 2400    | 2         | 3.45%   |
| 4267    | 1         | 1.72%   |
| 4000    | 1         | 1.72%   |
| 3866    | 1         | 1.72%   |
| 3666    | 1         | 1.72%   |
| 3400    | 1         | 1.72%   |
| 3000    | 1         | 1.72%   |
| 2733    | 1         | 1.72%   |
| 2666    | 1         | 1.72%   |
| 1800    | 1         | 1.72%   |
| 1066    | 1         | 1.72%   |
| Unknown | 1         | 1.72%   |

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


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 6         | 18.18%  |
| IMC Networks                  | 5         | 15.15%  |
| Sunplus Innovation Technology | 3         | 9.09%   |
| Logitech                      | 3         | 9.09%   |
| Acer                          | 3         | 9.09%   |
| Realtek Semiconductor         | 2         | 6.06%   |
| Quanta                        | 2         | 6.06%   |
| Luxvisions Innotech Limited   | 2         | 6.06%   |
| Syntek                        | 1         | 3.03%   |
| SunplusIT                     | 1         | 3.03%   |
| Microdia                      | 1         | 3.03%   |
| Lite-On Technology            | 1         | 3.03%   |
| KYE Systems (Mouse Systems)   | 1         | 3.03%   |
| Generalplus Technology        | 1         | 3.03%   |
| Creative Technology           | 1         | 3.03%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                      | 5         | 15.15%  |
| Chicony Integrated Camera                           | 3         | 9.09%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 6.06%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 6.06%   |
| Chicony HD User Facing                              | 2         | 6.06%   |
| Syntek Integrated Camera                            | 1         | 3.03%   |
| SunplusIT AUKEY PC???ˆ?”LM4                         | 1         | 3.03%   |
| Sunplus Full HD webcam                              | 1         | 3.03%   |
| Realtek Integrated Webcam HD                        | 1         | 3.03%   |
| Realtek Integrated Camera                           | 1         | 3.03%   |
| Quanta RGB-IR Camera                                | 1         | 3.03%   |
| Quanta HD Webcam                                    | 1         | 3.03%   |
| Microdia Integrated_Webcam_HD                       | 1         | 3.03%   |
| Logitech Webcam C270                                | 1         | 3.03%   |
| Logitech StreamCam                                  | 1         | 3.03%   |
| Logitech QuickCam Orbit/Sphere AF                   | 1         | 3.03%   |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 3.03%   |
| KYE Systems (Mouse Systems) Genius Webcam           | 1         | 3.03%   |
| Generalplus GENERAL WEBCAM                          | 1         | 3.03%   |
| Creative Live! Cam Sync 1080p                       | 1         | 3.03%   |
| Chicony XiaoMi USB 2.0 Webcam                       | 1         | 3.03%   |
| Acer NEC HD WebCam                                  | 1         | 3.03%   |
| Acer Integrated Camera                              | 1         | 3.03%   |
| Acer HD Webcam                                      | 1         | 3.03%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 2         | 40%     |
| Validity Sensors           | 1         | 20%     |
| Shenzhen Goodix Technology | 1         | 20%     |
| Elan Microelectronics      | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                   | 1         | 20%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 20%     |
| Shenzhen Goodix  FingerPrint Device               | 1         | 20%     |
| Elan ELAN:Fingerprint                             | 1         | 20%     |
| Unknown                                           | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 66.67%  |
| Alcor Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Broadcom 5880                       | 1         | 33.33%  |
| Broadcom 58200                      | 1         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 35        | 60.34%  |
| 1     | 14        | 24.14%  |
| 2     | 5         | 8.62%   |
| 3     | 3         | 5.17%   |
| 4     | 1         | 1.72%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 6         | 17.14%  |
| Graphics card            | 5         | 14.29%  |
| Fingerprint reader       | 5         | 14.29%  |
| Camera                   | 5         | 14.29%  |
| Multimedia controller    | 3         | 8.57%   |
| Chipcard                 | 3         | 8.57%   |
| Bluetooth                | 3         | 8.57%   |
| Net/wireless             | 2         | 5.71%   |
| Storage/ata              | 1         | 2.86%   |
| Modem                    | 1         | 2.86%   |
| Card reader              | 1         | 2.86%   |

