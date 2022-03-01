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
| Gigabyte      | Z590 UD                     | Desktop     | [a5242ed058](https://linux-hardware.org/?probe=a5242ed058) | Feb 26, 2022 |
| Lenovo        | Yoga Slim 7 14IIL05 82A1    | Notebook    | [0022f4a8cc](https://linux-hardware.org/?probe=0022f4a8cc) | Feb 26, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [06b438f37a](https://linux-hardware.org/?probe=06b438f37a) | Feb 24, 2022 |
| Gigabyte      | Z590 UD                     | Desktop     | [06d8d67698](https://linux-hardware.org/?probe=06d8d67698) | Feb 24, 2022 |
| Gigabyte      | Z590 UD                     | Desktop     | [071dd25266](https://linux-hardware.org/?probe=071dd25266) | Feb 24, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [cde7566ecb](https://linux-hardware.org/?probe=cde7566ecb) | Feb 22, 2022 |
| ASUSTek       | UX430UAR                    | Notebook    | [c7cd5ce50d](https://linux-hardware.org/?probe=c7cd5ce50d) | Feb 21, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [5dea4207b1](https://linux-hardware.org/?probe=5dea4207b1) | Feb 20, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [62010933e5](https://linux-hardware.org/?probe=62010933e5) | Feb 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [5836ccecc2](https://linux-hardware.org/?probe=5836ccecc2) | Feb 10, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [62bf8e7e99](https://linux-hardware.org/?probe=62bf8e7e99) | Feb 10, 2022 |
| MSI           | GS63VR 6RF                  | Notebook    | [c20c87027e](https://linux-hardware.org/?probe=c20c87027e) | Feb 10, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [8f79e4d763](https://linux-hardware.org/?probe=8f79e4d763) | Feb 06, 2022 |
| Lenovo        | Legion Y7000 2019 PG0 81... | Notebook    | [f79196e39c](https://linux-hardware.org/?probe=f79196e39c) | Feb 05, 2022 |
| Gigabyte      | Z490 UD                     | Desktop     | [b571c22d4f](https://linux-hardware.org/?probe=b571c22d4f) | Feb 04, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [a558bb9d2c](https://linux-hardware.org/?probe=a558bb9d2c) | Feb 03, 2022 |
| Neousys Te... | NVS-8208 Rev. A1            | Server      | [4a717f6348](https://linux-hardware.org/?probe=4a717f6348) | Feb 02, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [d424a8e145](https://linux-hardware.org/?probe=d424a8e145) | Feb 01, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [89dbe92caf](https://linux-hardware.org/?probe=89dbe92caf) | Feb 01, 2022 |
| Neousys Te... | NVS-8208 Rev. A1            | Server      | [7f7720253e](https://linux-hardware.org/?probe=7f7720253e) | Feb 01, 2022 |
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
| 5.15.10-gentoo               | 4         | 5.48%   |
| 5.15.10-gentoo-x86_64        | 3         | 4.11%   |
| 5.14.9-gentoo-x86_64         | 3         | 4.11%   |
| 5.16.4-gentoo                | 2         | 2.74%   |
| 5.16.2-gentoo                | 2         | 2.74%   |
| 5.16.0-gentoo-x86_64         | 2         | 2.74%   |
| 5.15.6-gentoo                | 2         | 2.74%   |
| 5.15.1-gentoo-x86_64         | 2         | 2.74%   |
| 5.14.14-gentoo-x86_64        | 2         | 2.74%   |
| 5.14.14-gentoo-dist          | 2         | 2.74%   |
| 5.14.12-gentoo               | 2         | 2.74%   |
| 6.0.0-Phaco-g8f10ff49057f    | 1         | 1.37%   |
| 5.16.9-gentoo                | 1         | 1.37%   |
| 5.16.8-gentoo-gentoo-dist    | 1         | 1.37%   |
| 5.16.7-tkg-cacule            | 1         | 1.37%   |
| 5.16.5-gentoo-x86_64         | 1         | 1.37%   |
| 5.16.5-gentoo-dist           | 1         | 1.37%   |
| 5.16.2-gentoo-x86_64         | 1         | 1.37%   |
| 5.16.10-gentoo-x86_64        | 1         | 1.37%   |
| 5.16.10-gentoo--20-feb-2022  | 1         | 1.37%   |
| 5.16.10-gentoo               | 1         | 1.37%   |
| 5.16.1-gentoo-x86_64         | 1         | 1.37%   |
| 5.16.1-gentoo                | 1         | 1.37%   |
| 5.16.0-xanmod1               | 1         | 1.37%   |
| 5.16.0-gentoo-gentoo-dist    | 1         | 1.37%   |
| 5.16.0-gentoo                | 1         | 1.37%   |
| 5.15.7-gentoo                | 1         | 1.37%   |
| 5.15.5-gentoo-x86_64         | 1         | 1.37%   |
| 5.15.5-gentoo-dist           | 1         | 1.37%   |
| 5.15.5-gentoo                | 1         | 1.37%   |
| 5.15.4-gentoo.8i7HVK         | 1         | 1.37%   |
| 5.15.4-gentoo-deimos         | 1         | 1.37%   |
| 5.15.3-gentoo.4650G          | 1         | 1.37%   |
| 5.15.2-gentoo20210917        | 1         | 1.37%   |
| 5.15.2-gentoo-x86_64         | 1         | 1.37%   |
| 5.15.19-gentoo-112-overlayfs | 1         | 1.37%   |
| 5.15.16-gentoo-dist          | 1         | 1.37%   |
| 5.15.13-gentoo-dist          | 1         | 1.37%   |
| 5.15.13-gentoo               | 1         | 1.37%   |
| 5.15.12-gentoo-x86_64        | 1         | 1.37%   |
| 5.15.12-gentoo-dist          | 1         | 1.37%   |
| 5.15.12-gentoo               | 1         | 1.37%   |
| 5.15.0-gentoo-x86_64         | 1         | 1.37%   |
| 5.15.0-gentoo                | 1         | 1.37%   |
| 5.14.9-gentoo                | 1         | 1.37%   |
| 5.14.7-gentoo-x86_64         | 1         | 1.37%   |
| 5.14.6                       | 1         | 1.37%   |
| 5.14.15-gentoo20210917       | 1         | 1.37%   |
| 5.14.14-gentoo               | 1         | 1.37%   |
| 5.14.13-gentoo               | 1         | 1.37%   |
| 5.14.11-zen1                 | 1         | 1.37%   |
| 5.10.84-gentoo-112-overlayfs | 1         | 1.37%   |
| 5.10.83-gentoo-dist          | 1         | 1.37%   |
| 5.10.76-gentoo-r1            | 1         | 1.37%   |
| 5.10.74-gentoo-x86_64        | 1         | 1.37%   |
| 5.10.70-1-lts                | 1         | 1.37%   |
| 5.10.63-v8                   | 1         | 1.37%   |
| 5.10.11-v8                   | 1         | 1.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.10 | 7         | 9.59%   |
| 5.16.0  | 5         | 6.85%   |
| 5.14.14 | 5         | 6.85%   |
| 5.14.9  | 4         | 5.48%   |
| 5.16.2  | 3         | 4.11%   |
| 5.16.10 | 3         | 4.11%   |
| 5.15.5  | 3         | 4.11%   |
| 5.15.12 | 3         | 4.11%   |
| 5.16.5  | 2         | 2.74%   |
| 5.16.4  | 2         | 2.74%   |
| 5.16.1  | 2         | 2.74%   |
| 5.15.6  | 2         | 2.74%   |
| 5.15.4  | 2         | 2.74%   |
| 5.15.2  | 2         | 2.74%   |
| 5.15.13 | 2         | 2.74%   |
| 5.15.1  | 2         | 2.74%   |
| 5.15.0  | 2         | 2.74%   |
| 5.14.12 | 2         | 2.74%   |
| 6.0.0   | 1         | 1.37%   |
| 5.16.9  | 1         | 1.37%   |
| 5.16.8  | 1         | 1.37%   |
| 5.16.7  | 1         | 1.37%   |
| 5.15.7  | 1         | 1.37%   |
| 5.15.3  | 1         | 1.37%   |
| 5.15.19 | 1         | 1.37%   |
| 5.15.16 | 1         | 1.37%   |
| 5.14.7  | 1         | 1.37%   |
| 5.14.6  | 1         | 1.37%   |
| 5.14.15 | 1         | 1.37%   |
| 5.14.13 | 1         | 1.37%   |
| 5.14.11 | 1         | 1.37%   |
| 5.10.84 | 1         | 1.37%   |
| 5.10.83 | 1         | 1.37%   |
| 5.10.76 | 1         | 1.37%   |
| 5.10.74 | 1         | 1.37%   |
| 5.10.70 | 1         | 1.37%   |
| 5.10.63 | 1         | 1.37%   |
| 5.10.11 | 1         | 1.37%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 28        | 40%     |
| 5.16    | 19        | 27.14%  |
| 5.14    | 16        | 22.86%  |
| 5.10    | 6         | 8.57%   |
| 6.0     | 1         | 1.43%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 64        | 98.46%  |
| aarch64 | 1         | 1.54%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KDE5          | 24        | 35.82%  |
| Unknown       | 22        | 32.84%  |
| GNOME         | 8         | 11.94%  |
| XFCE          | 5         | 7.46%   |
| Enlightenment | 2         | 2.99%   |
| sway          | 1         | 1.49%   |
| LXQt          | 1         | 1.49%   |
| i3            | 1         | 1.49%   |
| fvwm          | 1         | 1.49%   |
| DWM           | 1         | 1.49%   |
| Cinnamon      | 1         | 1.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 28        | 41.18%  |
| Wayland | 19        | 27.94%  |
| Tty     | 12        | 17.65%  |
| Unknown | 9         | 13.24%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 31        | 46.27%  |
| SDDM    | 23        | 34.33%  |
| GDM     | 6         | 8.96%   |
| LightDM | 5         | 7.46%   |
| SLiM    | 1         | 1.49%   |
| GREETD  | 1         | 1.49%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 26        | 40%     |
| en_GB      | 8         | 12.31%  |
| ru_RU      | 4         | 6.15%   |
| de_DE      | 3         | 4.62%   |
| C.UTF8     | 3         | 4.62%   |
| Unknown    | 3         | 4.62%   |
| pl_PL      | 2         | 3.08%   |
| fr_FR      | 2         | 3.08%   |
| el_GR      | 2         | 3.08%   |
| C          | 2         | 3.08%   |
| tr_TR      | 1         | 1.54%   |
| sl_SI      | 1         | 1.54%   |
| pt_BR      | 1         | 1.54%   |
| it_IT      | 1         | 1.54%   |
| es_ES      | 1         | 1.54%   |
| es_AR      | 1         | 1.54%   |
| en_US.UTF8 | 1         | 1.54%   |
| en_NZ      | 1         | 1.54%   |
| en_AU      | 1         | 1.54%   |
| de_CH      | 1         | 1.54%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 56        | 83.58%  |
| BIOS | 11        | 16.42%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 35        | 53.85%  |
| Btrfs | 25        | 38.46%  |
| F2fs  | 3         | 4.62%   |
| Zfs   | 1         | 1.54%   |
| Xtrfs | 1         | 1.54%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 61        | 91.04%  |
| Unknown | 4         | 5.97%   |
| MBR     | 2         | 2.99%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 50        | 74.63%  |
| Yes       | 17        | 25.37%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 48        | 73.85%  |
| Yes       | 17        | 26.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 15        | 23.08%  |
| ASUSTek Computer        | 13        | 20%     |
| MSI                     | 5         | 7.69%   |
| Gigabyte Technology     | 5         | 7.69%   |
| Dell                    | 5         | 7.69%   |
| ASRock                  | 4         | 6.15%   |
| Intel                   | 3         | 4.62%   |
| Hewlett-Packard         | 3         | 4.62%   |
| Acer                    | 3         | 4.62%   |
| Timi                    | 2         | 3.08%   |
| TYAN Computer           | 1         | 1.54%   |
| Toshiba                 | 1         | 1.54%   |
| Raspberry Pi Foundation | 1         | 1.54%   |
| Neousys Technology      | 1         | 1.54%   |
| Framework               | 1         | 1.54%   |
| EVGA                    | 1         | 1.54%   |
| BESSTAR Tech            | 1         | 1.54%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel S1200RP                            | 2         | 3.08%   |
| HP Laptop 15s-eq0xxx                     | 2         | 3.08%   |
| TYAN S7025                               | 1         | 1.54%   |
| Toshiba Satellite C850D-118              | 1         | 1.54%   |
| Timi RedmiBook 13                        | 1         | 1.54%   |
| Timi Mi Laptop Pro 15                    | 1         | 1.54%   |
| RPi Raspberry Pi                         | 1         | 1.54%   |
| Neousys Nuvo-8208GC Series               | 1         | 1.54%   |
| MSI MS-7D31                              | 1         | 1.54%   |
| MSI MS-7C56                              | 1         | 1.54%   |
| MSI MS-7996                              | 1         | 1.54%   |
| MSI GS63VR 6RF                           | 1         | 1.54%   |
| MSI GE73 Raider RGB 8RF                  | 1         | 1.54%   |
| Lenovo Yoga Slim 7 14IIL05 82A1          | 1         | 1.54%   |
| Lenovo Yoga S740-14IIL 81RS              | 1         | 1.54%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD0039RI | 1         | 1.54%   |
| Lenovo ThinkPad T470p 20J7S06Q00         | 1         | 1.54%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F437      | 1         | 1.54%   |
| Lenovo ThinkPad E495 20NE000BGE          | 1         | 1.54%   |
| Lenovo ThinkPad E15 Gen 2 20T8001STX     | 1         | 1.54%   |
| Lenovo ThinkPad 20FMCT01WW               | 1         | 1.54%   |
| Lenovo ThinkBook 14 G3 ACL 21A2          | 1         | 1.54%   |
| Lenovo Legion Y7000 2019 PG0 81T0        | 1         | 1.54%   |
| Lenovo Legion R7000 2020 82B6            | 1         | 1.54%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ         | 1         | 1.54%   |
| Lenovo IdeaPadFlex 5 14ITL05 82LT        | 1         | 1.54%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5         | 1         | 1.54%   |
| Lenovo IdeaPad 5 15ITL05 82FG            | 1         | 1.54%   |
| Intel NUC8i7HVK                          | 1         | 1.54%   |
| HP Pavilion Notebook                     | 1         | 1.54%   |
| Gigabyte Z87X-UD3H                       | 1         | 1.54%   |
| Gigabyte Z590 UD                         | 1         | 1.54%   |
| Gigabyte Z490 UD                         | 1         | 1.54%   |
| Gigabyte X570 AORUS MASTER               | 1         | 1.54%   |
| Gigabyte B450M S2H                       | 1         | 1.54%   |
| Framework Laptop                         | 1         | 1.54%   |
| EVGA Z390 DARK                           | 1         | 1.54%   |
| Dell XPS 15 9570                         | 1         | 1.54%   |
| Dell XPS 13 9365                         | 1         | 1.54%   |
| Dell Precision 3561                      | 1         | 1.54%   |
| Dell Latitude 7490                       | 1         | 1.54%   |
| Dell Inspiron 5415                       | 1         | 1.54%   |
| BESSTAR Tech X400                        | 1         | 1.54%   |
| ASUS Z170-A                              | 1         | 1.54%   |
| ASUS UX430UAR                            | 1         | 1.54%   |
| ASUS TUF GAMING B550-PLUS                | 1         | 1.54%   |
| ASUS TUF B450-PLUS GAMING                | 1         | 1.54%   |
| ASUS ROG Zephyrus G14 GA401QE_GA401QE    | 1         | 1.54%   |
| ASUS ROG ZENITH II EXTREME               | 1         | 1.54%   |
| ASUS ROG STRIX X570-E GAMING             | 1         | 1.54%   |
| ASUS ROG Strix G513QY_G513QY             | 1         | 1.54%   |
| ASUS ROG STRIX B550-F GAMING             | 1         | 1.54%   |
| ASUS ROG CROSSHAIR VIII HERO             | 1         | 1.54%   |
| ASUS ROG CROSSHAIR VIII DARK HERO        | 1         | 1.54%   |
| ASUS PRIME X570-P                        | 1         | 1.54%   |
| ASUS P5LD2-Deluxe                        | 1         | 1.54%   |
| ASRock X370 Killer SLI/ac                | 1         | 1.54%   |
| ASRock X370 Gaming X                     | 1         | 1.54%   |
| ASRock H110M-HDV R3.0                    | 1         | 1.54%   |
| ASRock AB350M Pro4                       | 1         | 1.54%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUS ROG            | 7         | 10.77%  |
| Lenovo ThinkPad     | 6         | 9.23%   |
| Lenovo Legion       | 3         | 4.62%   |
| Lenovo Yoga         | 2         | 3.08%   |
| Lenovo IdeaPad      | 2         | 3.08%   |
| Intel S1200RP       | 2         | 3.08%   |
| HP Laptop           | 2         | 3.08%   |
| Dell XPS            | 2         | 3.08%   |
| ASUS TUF            | 2         | 3.08%   |
| ASRock X370         | 2         | 3.08%   |
| Acer Aspire         | 2         | 3.08%   |
| TYAN S7025          | 1         | 1.54%   |
| Toshiba Satellite   | 1         | 1.54%   |
| Timi RedmiBook      | 1         | 1.54%   |
| Timi Mi             | 1         | 1.54%   |
| RPi Raspberry       | 1         | 1.54%   |
| Neousys Nuvo-8208GC | 1         | 1.54%   |
| MSI MS-7D31         | 1         | 1.54%   |
| MSI MS-7C56         | 1         | 1.54%   |
| MSI MS-7996         | 1         | 1.54%   |
| MSI GS63VR          | 1         | 1.54%   |
| MSI GE73            | 1         | 1.54%   |
| Lenovo ThinkBook    | 1         | 1.54%   |
| Lenovo IdeaPadFlex  | 1         | 1.54%   |
| Intel NUC8i7HVK     | 1         | 1.54%   |
| HP Pavilion         | 1         | 1.54%   |
| Gigabyte Z87X-UD3H  | 1         | 1.54%   |
| Gigabyte Z590       | 1         | 1.54%   |
| Gigabyte Z490       | 1         | 1.54%   |
| Gigabyte X570       | 1         | 1.54%   |
| Gigabyte B450M      | 1         | 1.54%   |
| Framework Laptop    | 1         | 1.54%   |
| EVGA Z390           | 1         | 1.54%   |
| Dell Precision      | 1         | 1.54%   |
| Dell Latitude       | 1         | 1.54%   |
| Dell Inspiron       | 1         | 1.54%   |
| BESSTAR Tech X400   | 1         | 1.54%   |
| ASUS Z170-A         | 1         | 1.54%   |
| ASUS UX430UAR       | 1         | 1.54%   |
| ASUS PRIME          | 1         | 1.54%   |
| ASUS P5LD2-Deluxe   | 1         | 1.54%   |
| ASRock H110M-HDV    | 1         | 1.54%   |
| ASRock AB350M       | 1         | 1.54%   |
| Acer Nitro          | 1         | 1.54%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 15        | 23.08%  |
| 2021    | 14        | 21.54%  |
| 2020    | 12        | 18.46%  |
| 2018    | 7         | 10.77%  |
| 2017    | 5         | 7.69%   |
| 2016    | 4         | 6.15%   |
| 2012    | 2         | 3.08%   |
| 2022    | 1         | 1.54%   |
| 2015    | 1         | 1.54%   |
| 2014    | 1         | 1.54%   |
| 2013    | 1         | 1.54%   |
| 2005    | 1         | 1.54%   |
| Unknown | 1         | 1.54%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 33        | 50.77%  |
| Desktop        | 23        | 35.38%  |
| Server         | 5         | 7.69%   |
| Convertible    | 2         | 3.08%   |
| System on chip | 1         | 1.54%   |
| Mini pc        | 1         | 1.54%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 62        | 95.38%  |
| Enabled  | 3         | 4.62%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 65        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 18        | 27.69%  |
| 16.01-24.0  | 11        | 16.92%  |
| 8.01-16.0   | 11        | 16.92%  |
| 64.01-256.0 | 10        | 15.38%  |
| 4.01-8.0    | 8         | 12.31%  |
| 24.01-32.0  | 4         | 6.15%   |
| 3.01-4.0    | 1         | 1.54%   |
| 2.01-3.0    | 1         | 1.54%   |
| 1.01-2.0    | 1         | 1.54%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 20        | 27.78%  |
| 1.01-2.0   | 18        | 25%     |
| 8.01-16.0  | 10        | 13.89%  |
| 3.01-4.0   | 9         | 12.5%   |
| 2.01-3.0   | 7         | 9.72%   |
| 0.51-1.0   | 4         | 5.56%   |
| 16.01-24.0 | 2         | 2.78%   |
| 24.01-32.0 | 1         | 1.39%   |
| 0.01-0.5   | 1         | 1.39%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 30        | 45.45%  |
| 2      | 13        | 19.7%   |
| 3      | 9         | 13.64%  |
| 4      | 7         | 10.61%  |
| 5      | 5         | 7.58%   |
| 7      | 1         | 1.52%   |
| 6      | 1         | 1.52%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 57        | 87.69%  |
| Yes       | 8         | 12.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 48        | 73.85%  |
| No        | 17        | 26.15%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 72.31%  |
| No        | 18        | 27.69%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 49        | 73.13%  |
| No        | 18        | 26.87%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 9         | 13.64%  |
| Germany     | 8         | 12.12%  |
| Russia      | 7         | 10.61%  |
| Poland      | 6         | 9.09%   |
| Spain       | 4         | 6.06%   |
| Greece      | 3         | 4.55%   |
| UK          | 2         | 3.03%   |
| India       | 2         | 3.03%   |
| France      | 2         | 3.03%   |
| Finland     | 2         | 3.03%   |
| Czechia     | 2         | 3.03%   |
| China       | 2         | 3.03%   |
| Uruguay     | 1         | 1.52%   |
| Turkey      | 1         | 1.52%   |
| Switzerland | 1         | 1.52%   |
| Sweden      | 1         | 1.52%   |
| Slovenia    | 1         | 1.52%   |
| Romania     | 1         | 1.52%   |
| Philippines | 1         | 1.52%   |
| Norway      | 1         | 1.52%   |
| New Zealand | 1         | 1.52%   |
| Mexico      | 1         | 1.52%   |
| Italy       | 1         | 1.52%   |
| Hong Kong   | 1         | 1.52%   |
| Brazil      | 1         | 1.52%   |
| Belarus     | 1         | 1.52%   |
| Bangladesh  | 1         | 1.52%   |
| Australia   | 1         | 1.52%   |
| Argentina   | 1         | 1.52%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Athens                        | 3         | 4.35%   |
| Swansea                       | 2         | 2.9%    |
| Moscow                        | 2         | 2.9%    |
| Kulmbach                      | 2         | 2.9%    |
| Helsinki                      | 2         | 2.9%    |
| Barcelona                     | 2         | 2.9%    |
| Zurich                        | 1         | 1.45%   |
| Zebulon                       | 1         | 1.45%   |
| Yekaterinburg                 | 1         | 1.45%   |
| West Orange                   | 1         | 1.45%   |
| Warsaw                        | 1         | 1.45%   |
| Vigo                          | 1         | 1.45%   |
| Ufa                           | 1         | 1.45%   |
| Szczecin                      | 1         | 1.45%   |
| Sydney                        | 1         | 1.45%   |
| Svobodnyy                     | 1         | 1.45%   |
| Storsteinnes                  | 1         | 1.45%   |
| Sestao                        | 1         | 1.45%   |
| SÃ£o Paulo                  | 1         | 1.45%   |
| RzeszÃ³w                    | 1         | 1.45%   |
| Redmond                       | 1         | 1.45%   |
| Ratingen                      | 1         | 1.45%   |
| Prague                        | 1         | 1.45%   |
| Paris                         | 1         | 1.45%   |
| Orange                        | 1         | 1.45%   |
| NykÃ¶ping                   | 1         | 1.45%   |
| Nuremberg                     | 1         | 1.45%   |
| Novosibirsk                   | 1         | 1.45%   |
| Nizhniy Novgorod              | 1         | 1.45%   |
| Niederdorla                   | 1         | 1.45%   |
| Morcenx                       | 1         | 1.45%   |
| Monroe                        | 1         | 1.45%   |
| Minsk                         | 1         | 1.45%   |
| Milan                         | 1         | 1.45%   |
| Maldonado                     | 1         | 1.45%   |
| Laziska Gorne                 | 1         | 1.45%   |
| Krakow                        | 1         | 1.45%   |
| IvanÄna Gorica             | 1         | 1.45%   |
| Hyderabad                     | 1         | 1.45%   |
| Harsum                        | 1         | 1.45%   |
| Guangzhou                     | 1         | 1.45%   |
| Gmina LwÃ³wek ÅšlÄ…ski | 1         | 1.45%   |
| Glen Ellyn                    | 1         | 1.45%   |
| Fuzhou                        | 1         | 1.45%   |
| Foshan                        | 1         | 1.45%   |
| Everett                       | 1         | 1.45%   |
| Essen                         | 1         | 1.45%   |
| Dhaka                         | 1         | 1.45%   |
| Ciudad JuÃ¡rez              | 1         | 1.45%   |
| Cieszyn                       | 1         | 1.45%   |
| Chicago                       | 1         | 1.45%   |
| Cerritos                      | 1         | 1.45%   |
| Central                       | 1         | 1.45%   |
| CÃ³rdoba                    | 1         | 1.45%   |
| Calamba                       | 1         | 1.45%   |
| Brno                          | 1         | 1.45%   |
| Brasov                        | 1         | 1.45%   |
| Blagoveshchensk               | 1         | 1.45%   |
| Bhavnagar                     | 1         | 1.45%   |
| Berlin                        | 1         | 1.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 24        | 36     | 21.62%  |
| Samsung Electronics            | 23        | 34     | 20.72%  |
| Seagate                        | 12        | 22     | 10.81%  |
| Intel                          | 8         | 10     | 7.21%   |
| Toshiba                        | 5         | 5      | 4.5%    |
| SK Hynix                       | 5         | 5      | 4.5%    |
| Crucial                        | 5         | 14     | 4.5%    |
| SanDisk                        | 3         | 4      | 2.7%    |
| Hitachi                        | 3         | 4      | 2.7%    |
| Unknown                        | 2         | 8      | 1.8%    |
| Team                           | 2         | 4      | 1.8%    |
| KIOXIA-EXCERIA                 | 2         | 3      | 1.8%    |
| Kingston                       | 2         | 2      | 1.8%    |
| Corsair                        | 2         | 2      | 1.8%    |
| Solid State Storage Technology | 1         | 1      | 0.9%    |
| Silicon Motion                 | 1         | 1      | 0.9%    |
| PLEXTOR                        | 1         | 2      | 0.9%    |
| Phison                         | 1         | 1      | 0.9%    |
| OCZ-VERTEX                     | 1         | 1      | 0.9%    |
| Netac                          | 1         | 1      | 0.9%    |
| Micron Technology              | 1         | 1      | 0.9%    |
| KIOXIA                         | 1         | 1      | 0.9%    |
| Kingchuxing                    | 1         | 2      | 0.9%    |
| HGST                           | 1         | 1      | 0.9%    |
| GOODRAM                        | 1         | 1      | 0.9%    |
| A-DATA Technology              | 1         | 1      | 0.9%    |
| 2.5"                           | 1         | 1      | 0.9%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| WDC WD30EFRX-68EUZN0 3TB                 | 2         | 1.53%   |
| Toshiba DT01ACA100 1TB                   | 2         | 1.53%   |
| Samsung SSD 970 EVO Plus 250GB           | 2         | 1.53%   |
| Samsung SSD 970 EVO 500GB                | 2         | 1.53%   |
| Samsung MZVLB512HBJQ-000L2 512GB         | 2         | 1.53%   |
| Intel SSDPEKNW010T8 1TB                  | 2         | 1.53%   |
| Intel SSDPEKNU512GZ 512GB                | 2         | 1.53%   |
| Crucial CT1000P1SSD8 1TB                 | 2         | 1.53%   |
| WDC WDS500G2X0C-00L350 500GB             | 1         | 0.76%   |
| WDC WDS500G2B0B-00YS70 500GB SSD         | 1         | 0.76%   |
| WDC WDS500G2B0A-00SM50 500GB SSD         | 1         | 0.76%   |
| WDC WDS250G2X0C-00L350 250GB             | 1         | 0.76%   |
| WDC WDS240G2G0A-00JH30 240GB SSD         | 1         | 0.76%   |
| WDC WDS240G2G0A 240GB SSD                | 1         | 0.76%   |
| WDC WDS100T2B0C-00PXH0 1TB               | 1         | 0.76%   |
| WDC WD8003FFBX-68B9AN0 8TB               | 1         | 0.76%   |
| WDC WD60EZRX-00MVLB1 6TB                 | 1         | 0.76%   |
| WDC WD60EFRX-68L0BN1 6TB                 | 1         | 0.76%   |
| WDC WD5000AZLX-00JKKA0 500GB             | 1         | 0.76%   |
| WDC WD30EFRX-68AX9N0 3TB                 | 1         | 0.76%   |
| WDC WD2500BEVS-22UST0 250GB              | 1         | 0.76%   |
| WDC WD20EZRX-00D8PB0 2TB                 | 1         | 0.76%   |
| WDC WD20EFRX-68EUZN0 2TB                 | 1         | 0.76%   |
| WDC WD10SPSX-08A6W 1TB                   | 1         | 0.76%   |
| WDC WD10PURX-64E5EY0 1TB                 | 1         | 0.76%   |
| WDC WD10EZEX-60WN4A1 1TB                 | 1         | 0.76%   |
| WDC WD10EZEX-22M                         | 1         | 0.76%   |
| WDC WD10EZEX-08WN4A0 1TB                 | 1         | 0.76%   |
| WDC WD10EZEX-08M2NA0 1TB                 | 1         | 0.76%   |
| WDC WD10EARS-00MVWB0 1TB                 | 1         | 0.76%   |
| WDC WD10EADS-00L5B1 1TB                  | 1         | 0.76%   |
| WDC WD1002FBYS-18W8B0 1TB                | 1         | 0.76%   |
| WDC PC SN730 SDBPNTY-512G-1006 512GB     | 1         | 0.76%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB     | 1         | 0.76%   |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB     | 1         | 0.76%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB     | 1         | 0.76%   |
| Unknown USB DISK 3.2 500GB               | 1         | 0.76%   |
| Unknown MMC Card  32GB                   | 1         | 0.76%   |
| Toshiba THNSN5512GPUK NVMe 512GB         | 1         | 0.76%   |
| Toshiba KXG6AZNV512G 512GB               | 1         | 0.76%   |
| Toshiba KSG60ZMV512G M.2 2280 512GB SSD  | 1         | 0.76%   |
| Team TM8PS7256G 256GB SSD                | 1         | 0.76%   |
| Team TM8FP2240G 240GB                    | 1         | 0.76%   |
| Solid State Storage NVMe SSD Drive 256GB | 1         | 0.76%   |
| SK Hynix SKHynix_HFS001TDE9X084N 1TB     | 1         | 0.76%   |
| SK Hynix PC711 NVMe 512GB                | 1         | 0.76%   |
| SK Hynix HFM512GDHTNG-8710B 512GB        | 1         | 0.76%   |
| SK Hynix HFM512GD3JX016N 512GB           | 1         | 0.76%   |
| SK Hynix BC711 NVMe 512GB                | 1         | 0.76%   |
| Silicon Motion M.2 (P80) 3TG3-P 1TB      | 1         | 0.76%   |
| Seagate ST8000DM004-2CX188 8TB           | 1         | 0.76%   |
| Seagate ST4000DM005-2DP166 4TB           | 1         | 0.76%   |
| Seagate ST4000DM004-2CV104 4TB           | 1         | 0.76%   |
| Seagate ST3500630AS 500GB                | 1         | 0.76%   |
| Seagate ST3250318AS 250GB                | 1         | 0.76%   |
| Seagate ST3160023AS 160GB                | 1         | 0.76%   |
| Seagate ST2000DM001-1ER164 2TB           | 1         | 0.76%   |
| Seagate ST1000LM049-2GH172 1TB           | 1         | 0.76%   |
| Seagate ST1000LM035-1RK172 1TB           | 1         | 0.76%   |
| Seagate ST1000LM035-1RK1 1TB             | 1         | 0.76%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 15        | 24     | 48.39%  |
| Seagate | 10        | 20     | 32.26%  |
| Hitachi | 3         | 4      | 9.68%   |
| Toshiba | 2         | 2      | 6.45%   |
| HGST    | 1         | 1      | 3.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 10     | 34.62%  |
| WDC                 | 4         | 4      | 15.38%  |
| SanDisk             | 3         | 4      | 11.54%  |
| Crucial             | 2         | 10     | 7.69%   |
| Toshiba             | 1         | 1      | 3.85%   |
| Team                | 1         | 2      | 3.85%   |
| OCZ-VERTEX          | 1         | 1      | 3.85%   |
| Kingston            | 1         | 1      | 3.85%   |
| Intel               | 1         | 1      | 3.85%   |
| GOODRAM             | 1         | 1      | 3.85%   |
| Corsair             | 1         | 1      | 3.85%   |
| 2.5"                | 1         | 1      | 3.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 49        | 72     | 50%     |
| SSD     | 24        | 37     | 24.49%  |
| HDD     | 23        | 51     | 23.47%  |
| MMC     | 1         | 5      | 1.02%   |
| Unknown | 1         | 3      | 1.02%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 49        | 72     | 55.68%  |
| SATA | 37        | 88     | 42.05%  |
| SAS  | 1         | 3      | 1.14%   |
| MMC  | 1         | 5      | 1.14%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 19        | 27     | 38%     |
| 0.01-0.5   | 17        | 29     | 34%     |
| 1.01-2.0   | 6         | 9      | 12%     |
| 4.01-10.0  | 4         | 14     | 8%      |
| 3.01-4.0   | 2         | 4      | 4%      |
| 2.01-3.0   | 2         | 5      | 4%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 17        | 25.37%  |
| 501-1000       | 14        | 20.9%   |
| 1001-2000      | 11        | 16.42%  |
| 101-250        | 8         | 11.94%  |
| More than 3000 | 7         | 10.45%  |
| 1-20           | 4         | 5.97%   |
| 2001-3000      | 2         | 2.99%   |
| Unknown        | 2         | 2.99%   |
| 21-50          | 1         | 1.49%   |
| 51-100         | 1         | 1.49%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 12        | 18.18%  |
| 101-250        | 12        | 18.18%  |
| 1-20           | 10        | 15.15%  |
| 21-50          | 7         | 10.61%  |
| 501-1000       | 6         | 9.09%   |
| 51-100         | 6         | 9.09%   |
| More than 3000 | 5         | 7.58%   |
| 1001-2000      | 5         | 7.58%   |
| Unknown        | 2         | 3.03%   |
| 2001-3000      | 1         | 1.52%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC WD60EFRX-68L0BN1 6TB       | 1         | 3      | 7.14%   |
| WDC WD30EFRX-68AX9N0 3TB       | 1         | 2      | 7.14%   |
| WDC WD20EZRX-00D8PB0 2TB       | 1         | 1      | 7.14%   |
| WDC WD1002FBYS-18W8B0 1TB      | 1         | 1      | 7.14%   |
| Seagate ST3160023AS 160GB      | 1         | 1      | 7.14%   |
| Seagate ST1000LM049-2GH172 1TB | 1         | 1      | 7.14%   |
| Seagate ST1000LM035-1RK172 1TB | 1         | 2      | 7.14%   |
| SanDisk SSD PLUS 1000GB        | 1         | 1      | 7.14%   |
| Intel SSDPEKKF256G8L 256GB     | 1         | 1      | 7.14%   |
| Hitachi HUA721010KLA330 1TB    | 1         | 1      | 7.14%   |
| Hitachi HDS722020ALA330 2TB    | 1         | 2      | 7.14%   |
| Crucial CT525MX300SSD1 528GB   | 1         | 1      | 7.14%   |
| Crucial CT1000P1SSD8 1TB       | 1         | 1      | 7.14%   |
| 2.5" SATA SSD 3TG6-P 480GB     | 1         | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 7      | 28.57%  |
| Seagate | 3         | 4      | 21.43%  |
| Hitachi | 2         | 3      | 14.29%  |
| Crucial | 2         | 2      | 14.29%  |
| SanDisk | 1         | 1      | 7.14%   |
| Intel   | 1         | 1      | 7.14%   |
| 2.5"    | 1         | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 7      | 44.44%  |
| Seagate | 3         | 4      | 33.33%  |
| Hitachi | 2         | 3      | 22.22%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 14     | 58.33%  |
| SSD  | 3         | 3      | 25%     |
| NVMe | 2         | 2      | 16.67%  |

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
| Works    | 60        | 131    | 75.95%  |
| Malfunc  | 12        | 19     | 15.19%  |
| Detected | 6         | 17     | 7.59%   |
| Failed   | 1         | 1      | 1.27%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 32        | 28.83%  |
| AMD                            | 21        | 18.92%  |
| Samsung Electronics            | 19        | 17.12%  |
| Sandisk                        | 7         | 6.31%   |
| SK Hynix                       | 5         | 4.5%    |
| ASMedia Technology             | 4         | 3.6%    |
| Toshiba America Info Systems   | 3         | 2.7%    |
| Silicon Motion                 | 3         | 2.7%    |
| Phison Electronics             | 3         | 2.7%    |
| Solid State Storage Technology | 2         | 1.8%    |
| Seagate Technology             | 2         | 1.8%    |
| Micron/Crucial Technology      | 2         | 1.8%    |
| Micron Technology              | 2         | 1.8%    |
| KIOXIA                         | 2         | 1.8%    |
| Silicon Image                  | 1         | 0.9%    |
| Marvell Technology Group       | 1         | 0.9%    |
| Kingston Technology Company    | 1         | 0.9%    |
| ADATA Technology               | 1         | 0.9%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 18        | 15%     |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 12        | 10%     |
| SK Hynix Gold P31 SSD                                                          | 4         | 3.33%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 4         | 3.33%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 2.5%    |
| Intel SSD 660P Series                                                          | 3         | 2.5%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 2.5%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 2.5%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 2.5%    |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                       | 3         | 2.5%    |
| Solid State Storage Non-Volatile memory controller                             | 2         | 1.67%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 2         | 1.67%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 1.67%   |
| Sandisk Non-Volatile memory controller                                         | 2         | 1.67%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2         | 1.67%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 1.67%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2         | 1.67%   |
| Micron Non-Volatile memory controller                                          | 2         | 1.67%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 1.67%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 2         | 1.67%   |
| Intel Non-Volatile memory controller                                           | 2         | 1.67%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 1.67%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 1.67%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 1.67%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 1.67%   |
| AMD X370 Series Chipset SATA Controller                                        | 2         | 1.67%   |
| AMD 400 Series Chipset SATA Controller                                         | 2         | 1.67%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.83%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 0.83%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 1         | 0.83%   |
| SK Hynix BC501 NVMe Solid State Drive                                          | 1         | 0.83%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 0.83%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1         | 0.83%   |
| Seagate FireCuda 530 SSD                                                       | 1         | 0.83%   |
| Seagate FireCuda 520 SSD                                                       | 1         | 0.83%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 1         | 0.83%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 0.83%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 0.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.83%   |
| Phison E7 NVMe Controller                                                      | 1         | 0.83%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1         | 0.83%   |
| Micron/Crucial NVMe Controller                                                 | 1         | 0.83%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1         | 0.83%   |
| KIOXIA NVMe SSD                                                                | 1         | 0.83%   |
| KIOXIA Non-Volatile memory controller                                          | 1         | 0.83%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 0.83%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 0.83%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 0.83%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                | 1         | 0.83%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1         | 0.83%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 0.83%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 1         | 0.83%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 1         | 0.83%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 1         | 0.83%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 1         | 0.83%   |
| AMD 300 Series Chipset SATA Controller                                         | 1         | 0.83%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 1         | 0.83%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 49        | 50%     |
| SATA | 44        | 44.9%   |
| RAID | 3         | 3.06%   |
| IDE  | 2         | 2.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 36        | 55.38%  |
| AMD    | 28        | 43.08%  |
| ARM    | 1         | 1.54%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz              | 3         | 4.62%   |
| AMD Ryzen 9 3950X 16-Core Processor            | 3         | 4.62%   |
| Intel Xeon CPU E3-1270 v3 @ 3.50GHz            | 2         | 3.08%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz             | 2         | 3.08%   |
| Intel Core i5-9300H CPU @ 2.40GHz              | 2         | 3.08%   |
| AMD Ryzen 7 5700U with Radeon Graphics         | 2         | 3.08%   |
| AMD Ryzen 5 1600 Six-Core Processor            | 2         | 3.08%   |
| Intel Xeon CPU X5680 @ 3.33GHz                 | 1         | 1.54%   |
| Intel Pentium 4 CPU 3.20GHz                    | 1         | 1.54%   |
| Intel Core i9-9900K CPU @ 3.60GHz              | 1         | 1.54%   |
| Intel Core i7-9700 CPU @ 3.00GHz               | 1         | 1.54%   |
| Intel Core i7-8809G CPU @ 3.10GHz              | 1         | 1.54%   |
| Intel Core i7-8650U CPU @ 1.90GHz              | 1         | 1.54%   |
| Intel Core i7-8565U CPU @ 1.80GHz              | 1         | 1.54%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz             | 1         | 1.54%   |
| Intel Core i7-6700K CPU @ 4.00GHz              | 1         | 1.54%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz             | 1         | 1.54%   |
| Intel Core i7-10850H CPU @ 2.70GHz             | 1         | 1.54%   |
| Intel Core i7-10700F CPU @ 2.90GHz             | 1         | 1.54%   |
| Intel Core i7-10510U CPU @ 1.80GHz             | 1         | 1.54%   |
| Intel Core i5-8250U CPU @ 1.60GHz              | 1         | 1.54%   |
| Intel Core i5-8200Y CPU @ 1.30GHz              | 1         | 1.54%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 1         | 1.54%   |
| Intel Core i5-6400 CPU @ 2.70GHz               | 1         | 1.54%   |
| Intel Core i5-5200U CPU @ 2.20GHz              | 1         | 1.54%   |
| Intel Core i5-4670K CPU @ 3.40GHz              | 1         | 1.54%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz             | 1         | 1.54%   |
| Intel Core i5-10210U CPU @ 1.60GHz             | 1         | 1.54%   |
| Intel 12th Gen Core i7-12700K                  | 1         | 1.54%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz        | 1         | 1.54%   |
| Intel 11th Gen Core i7-11850H @ 2.50GHz        | 1         | 1.54%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz        | 1         | 1.54%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz        | 1         | 1.54%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 1         | 1.54%   |
| ARM Processor                                  | 1         | 1.54%   |
| AMD Ryzen Threadripper 3960X 24-Core Processor | 1         | 1.54%   |
| AMD Ryzen 9 5950X 16-Core Processor            | 1         | 1.54%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 1         | 1.54%   |
| AMD Ryzen 9 5900HX with Radeon Graphics        | 1         | 1.54%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 1         | 1.54%   |
| AMD Ryzen 7 PRO 5750G with Radeon Graphics     | 1         | 1.54%   |
| AMD Ryzen 7 5800HS with Radeon Graphics        | 1         | 1.54%   |
| AMD Ryzen 7 5800H with Radeon Graphics         | 1         | 1.54%   |
| AMD Ryzen 7 4800H with Radeon Graphics         | 1         | 1.54%   |
| AMD Ryzen 7 4700U with Radeon Graphics         | 1         | 1.54%   |
| AMD Ryzen 7 3700X 8-Core Processor             | 1         | 1.54%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx  | 1         | 1.54%   |
| AMD Ryzen 7 1700X Eight-Core Processor         | 1         | 1.54%   |
| AMD Ryzen 5 PRO 4650G with Radeon Graphics     | 1         | 1.54%   |
| AMD Ryzen 5 5600H with Radeon Graphics         | 1         | 1.54%   |
| AMD Ryzen 5 5500U with Radeon Graphics         | 1         | 1.54%   |
| AMD Ryzen 5 3600 6-Core Processor              | 1         | 1.54%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx  | 1         | 1.54%   |
| AMD Ryzen 5 2600 Six-Core Processor            | 1         | 1.54%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx  | 1         | 1.54%   |
| AMD E1-1200 APU with Radeon HD Graphics        | 1         | 1.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 15        | 23.08%  |
| Intel Core i5          | 10        | 15.38%  |
| AMD Ryzen 7            | 9         | 13.85%  |
| Other                  | 7         | 10.77%  |
| AMD Ryzen 9            | 7         | 10.77%  |
| AMD Ryzen 5            | 7         | 10.77%  |
| Intel Xeon             | 3         | 4.62%   |
| Intel Pentium 4        | 1         | 1.54%   |
| Intel Core i9          | 1         | 1.54%   |
| AMD Ryzen Threadripper | 1         | 1.54%   |
| AMD Ryzen 7 PRO        | 1         | 1.54%   |
| AMD Ryzen 5 PRO        | 1         | 1.54%   |
| AMD Ryzen 3            | 1         | 1.54%   |
| AMD E1                 | 1         | 1.54%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 24        | 36.92%  |
| 8       | 15        | 23.08%  |
| 6       | 11        | 16.92%  |
| 16      | 4         | 6.15%   |
| 12      | 4         | 6.15%   |
| 2       | 4         | 6.15%   |
| 24      | 1         | 1.54%   |
| 1       | 1         | 1.54%   |
| Unknown | 1         | 1.54%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 63        | 96.92%  |
| 2       | 1         | 1.54%   |
| Unknown | 1         | 1.54%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 57        | 87.69%  |
| 1       | 7         | 10.77%  |
| Unknown | 1         | 1.54%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 65        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 8         | 12.31%  |
| 0x906ea    | 5         | 7.69%   |
| 0x0a50000c | 4         | 6.15%   |
| 0x08701021 | 4         | 6.15%   |
| 0x906e9    | 3         | 4.62%   |
| 0x806ec    | 3         | 4.62%   |
| 0x08001138 | 3         | 4.62%   |
| 0x906ed    | 2         | 3.08%   |
| 0x806c1    | 2         | 3.08%   |
| 0x706e5    | 2         | 3.08%   |
| 0x506e3    | 2         | 3.08%   |
| 0x306c3    | 2         | 3.08%   |
| 0x0a201016 | 2         | 3.08%   |
| 0x08608103 | 2         | 3.08%   |
| 0x08600103 | 2         | 3.08%   |
| 0x08108109 | 2         | 3.08%   |
| 0xf43      | 1         | 1.54%   |
| 0xa0671    | 1         | 1.54%   |
| 0xa0655    | 1         | 1.54%   |
| 0xa0652    | 1         | 1.54%   |
| 0x90672    | 1         | 1.54%   |
| 0x806ea    | 1         | 1.54%   |
| 0x806e9    | 1         | 1.54%   |
| 0x806d1    | 1         | 1.54%   |
| 0x306d4    | 1         | 1.54%   |
| 0x206c2    | 1         | 1.54%   |
| 0x0a50000b | 1         | 1.54%   |
| 0x08608102 | 1         | 1.54%   |
| 0x08600106 | 1         | 1.54%   |
| 0x08301039 | 1         | 1.54%   |
| 0x08108102 | 1         | 1.54%   |
| 0x0800820d | 1         | 1.54%   |
| 0x05000119 | 1         | 1.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 16        | 24.62%  |
| Zen 2            | 10        | 15.38%  |
| Zen 3            | 7         | 10.77%  |
| IceLake          | 5         | 7.69%   |
| Zen+             | 4         | 6.15%   |
| Unknown          | 4         | 6.15%   |
| Zen              | 3         | 4.62%   |
| TigerLake        | 3         | 4.62%   |
| Skylake          | 3         | 4.62%   |
| Haswell          | 3         | 4.62%   |
| CometLake        | 2         | 3.08%   |
| Westmere         | 1         | 1.54%   |
| NetBurst         | 1         | 1.54%   |
| Broadwell        | 1         | 1.54%   |
| Bobcat           | 1         | 1.54%   |
| Alderlake Hybrid | 1         | 1.54%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Nvidia                     | 28        | 33.73%  |
| Intel                      | 27        | 32.53%  |
| AMD                        | 26        | 31.33%  |
| Matrox Electronics Systems | 2         | 2.41%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                            | 5         | 5.88%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]              | 5         | 5.88%   |
| AMD Cezanne                                                          | 4         | 4.71%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                      | 3         | 3.53%   |
| Nvidia GP108M [GeForce MX250]                                        | 3         | 3.53%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                            | 3         | 3.53%   |
| Intel HD Graphics 630                                                | 3         | 3.53%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series] | 3         | 3.53%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                       | 3         | 3.53%   |
| AMD Lucienne                                                         | 3         | 3.53%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                            | 2         | 2.35%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                           | 2         | 2.35%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                  | 2         | 2.35%   |
| Nvidia GM206 [GeForce GTX 960]                                       | 2         | 2.35%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)    | 2         | 2.35%   |
| Intel UHD Graphics 620                                               | 2         | 2.35%   |
| Intel Iris Plus Graphics G7                                          | 2         | 2.35%   |
| Intel HD Graphics 530                                                | 2         | 2.35%   |
| Intel CometLake-U GT2 [UHD Graphics]                                 | 2         | 2.35%   |
| AMD Renoir                                                           | 2         | 2.35%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT / 6800M]                         | 2         | 2.35%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                           | 1         | 1.18%   |
| Nvidia TU117GLM [T600 Mobile]                                        | 1         | 1.18%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                   | 1         | 1.18%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                | 1         | 1.18%   |
| Nvidia TU116 [GeForce GTX 1650]                                      | 1         | 1.18%   |
| Nvidia GP108 [GeForce GT 1030]                                       | 1         | 1.18%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                              | 1         | 1.18%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                              | 1         | 1.18%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                   | 1         | 1.18%   |
| Nvidia GM204 [GeForce GTX 970]                                       | 1         | 1.18%   |
| Nvidia GM108M [GeForce 940M]                                         | 1         | 1.18%   |
| Nvidia GM108M [GeForce 940MX]                                        | 1         | 1.18%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                           | 1         | 1.18%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                      | 1         | 1.18%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                           | 1         | 1.18%   |
| Intel UHD Graphics 615                                               | 1         | 1.18%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                 | 1         | 1.18%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                               | 1         | 1.18%   |
| Intel HD Graphics 5500                                               | 1         | 1.18%   |
| Intel CometLake-H GT2 [UHD Graphics]                                 | 1         | 1.18%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                            | 1         | 1.18%   |
| Intel AlderLake-S GT1                                                | 1         | 1.18%   |
| AMD Wrestler [Radeon HD 7310]                                        | 1         | 1.18%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                             | 1         | 1.18%   |
| AMD Polaris 22 XT [Radeon RX Vega M GH]                              | 1         | 1.18%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                       | 1         | 1.18%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                       | 1         | 1.18%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]  | 1         | 1.18%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 19        | 29.23%  |
| Intel + Nvidia | 13        | 20%     |
| 1 x Intel      | 12        | 18.46%  |
| 1 x Nvidia     | 10        | 15.38%  |
| AMD + Nvidia   | 5         | 7.69%   |
| Other          | 2         | 3.08%   |
| 2 x AMD        | 2         | 3.08%   |
| 1 x Matrox     | 2         | 3.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 38        | 58.46%  |
| Proprietary | 22        | 33.85%  |
| Unknown     | 5         | 7.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 29        | 43.94%  |
| 3.01-4.0   | 9         | 13.64%  |
| 1.01-2.0   | 8         | 12.12%  |
| 8.01-16.0  | 7         | 10.61%  |
| 0.01-0.5   | 4         | 6.06%   |
| 7.01-8.0   | 3         | 4.55%   |
| 5.01-6.0   | 3         | 4.55%   |
| 0.51-1.0   | 3         | 4.55%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 12        | 14.63%  |
| AU Optronics            | 9         | 10.98%  |
| Samsung Electronics     | 6         | 7.32%   |
| Chimei Innolux          | 5         | 6.1%    |
| Goldstar                | 4         | 4.88%   |
| Sharp                   | 3         | 3.66%   |
| Lenovo                  | 3         | 3.66%   |
| Hewlett-Packard         | 3         | 3.66%   |
| Dell                    | 3         | 3.66%   |
| BenQ                    | 3         | 3.66%   |
| ASUSTek Computer        | 3         | 3.66%   |
| AOC                     | 3         | 3.66%   |
| Acer                    | 3         | 3.66%   |
| LG Display              | 2         | 2.44%   |
| Iiyama                  | 2         | 2.44%   |
| Ancor Communications    | 2         | 2.44%   |
| Valve                   | 1         | 1.22%   |
| Toshiba                 | 1         | 1.22%   |
| Sceptre Tech            | 1         | 1.22%   |
| Sceptre                 | 1         | 1.22%   |
| Philips                 | 1         | 1.22%   |
| PANDA                   | 1         | 1.22%   |
| NEC Computers           | 1         | 1.22%   |
| MXX                     | 1         | 1.22%   |
| MStar                   | 1         | 1.22%   |
| Mi                      | 1         | 1.22%   |
| HannStar                | 1         | 1.22%   |
| Gigabyte Technology     | 1         | 1.22%   |
| Gateway                 | 1         | 1.22%   |
| CSO                     | 1         | 1.22%   |
| Chi Mei Optoelectronics | 1         | 1.22%   |
| Belinea                 | 1         | 1.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                  | 2         | 2.3%    |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch         | 2         | 2.3%    |
| Valve Index HMD VLV91A8                                                | 1         | 1.15%   |
| Toshiba PA3552 TOS501C 1680x1050 433x270mm 20.1-inch                   | 1         | 1.15%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                | 1         | 1.15%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch                | 1         | 1.15%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                | 1         | 1.15%   |
| Sceptre Tech C305W-2560UN SPT0C0D 2560x1080 690x291mm 29.5-inch        | 1         | 1.15%   |
| Sceptre LCD Monitor C305W-2560UN                                       | 1         | 1.15%   |
| Samsung Electronics SMS27A850 SAM083D 2560x1440 518x324mm 24.1-inch    | 1         | 1.15%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch      | 1         | 1.15%   |
| Samsung Electronics LF24T450F SAM7096 1920x1080 527x296mm 23.8-inch    | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch   | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch   | 1         | 1.15%   |
| Samsung Electronics C49HG9x SAM0E5E 3840x1080 1196x336mm 48.9-inch     | 1         | 1.15%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch                | 1         | 1.15%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                | 1         | 1.15%   |
| NEC Computers EA274WMi NEC6960 2560x1440 597x336mm 27.0-inch           | 1         | 1.15%   |
| MXX O-3-H MXX0001 3840x2160 1872x1053mm 84.6-inch                      | 1         | 1.15%   |
| MStar DP MST2380 2560x1440 597x336mm 27.0-inch                         | 1         | 1.15%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                       | 1         | 1.15%   |
| LG Display LCD Monitor LGD0536 1920x1080 294x165mm 13.3-inch           | 1         | 1.15%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch           | 1         | 1.15%   |
| Lenovo Q27q-10 LEN65F4 2560x1440 597x336mm 27.0-inch                   | 1         | 1.15%   |
| Lenovo P24h-10 LEN61AE 2560x1440 527x296mm 23.8-inch                   | 1         | 1.15%   |
| Lenovo LEN P27h-10 LEN61AF 2560x1440 597x336mm 27.0-inch               | 1         | 1.15%   |
| Iiyama PL3288UH IVM7610 3840x2160 698x393mm 31.5-inch                  | 1         | 1.15%   |
| Iiyama PL2792Q IVM6630 2560x1440 600x340mm 27.2-inch                   | 1         | 1.15%   |
| Hewlett-Packard LV1561w HWP2837 1366x768 344x194mm 15.5-inch           | 1         | 1.15%   |
| Hewlett-Packard LP2475w HWP26F9 1920x1200 546x352mm 25.6-inch          | 1         | 1.15%   |
| Hewlett-Packard E273q HPN3473 2560x1440 597x336mm 27.0-inch            | 1         | 1.15%   |
| Hewlett-Packard 22fw HPN3541 1920x1080 476x268mm 21.5-inch             | 1         | 1.15%   |
| HannStar JC198D HSD0CC6 1280x1024 376x301mm 19.0-inch                  | 1         | 1.15%   |
| Goldstar ULTRAWIDE GSM76E4 3440x1440 800x335mm 34.1-inch               | 1         | 1.15%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 1         | 1.15%   |
| Goldstar 23EA53 GSM59A9 1920x1080 510x290mm 23.1-inch                  | 1         | 1.15%   |
| Gigabyte Technology AORUS AD27QD GBT2701 2560x1440 609x355mm 27.8-inch | 1         | 1.15%   |
| Gateway FPD1765 GWY06E9 1280x1024 338x270mm 17.0-inch                  | 1         | 1.15%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                      | 1         | 1.15%   |
| Dell U2515H DELD070 2560x1440 553x311mm 25.0-inch                      | 1         | 1.15%   |
| Dell S3221QS DELD107 3840x2160 697x392mm 31.5-inch                     | 1         | 1.15%   |
| Dell P2219HC DELA11A 1920x1080 476x267mm 21.5-inch                     | 1         | 1.15%   |
| CSO LCD Monitor CSO1609 2560x1600 345x215mm 16.0-inch                  | 1         | 1.15%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch       | 1         | 1.15%   |
| Chimei Innolux LCD Monitor CMN14E7 1920x1080 309x173mm 13.9-inch       | 1         | 1.15%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 1         | 1.15%   |
| Chimei Innolux LCD Monitor CMN14D3 1920x1080 309x173mm 13.9-inch       | 1         | 1.15%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch       | 1         | 1.15%   |
| Chi Mei Optoelectronics CMC 19AW CMO2198 1440x900 408x255mm 18.9-inch  | 1         | 1.15%   |
| BOE LCD Monitor BOE09B6 2560x1600 345x215mm 16.0-inch                  | 1         | 1.15%   |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                  | 1         | 1.15%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                  | 1         | 1.15%   |
| BOE LCD Monitor BOE0928 1920x1080 344x194mm 15.5-inch                  | 1         | 1.15%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                  | 1         | 1.15%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                  | 1         | 1.15%   |
| BOE LCD Monitor BOE08D6 1920x1080 309x174mm 14.0-inch                  | 1         | 1.15%   |
| BOE LCD Monitor BOE0898 1920x1080 294x165mm 13.3-inch                  | 1         | 1.15%   |
| BOE LCD Monitor BOE086E 1920x1080 344x194mm 15.5-inch                  | 1         | 1.15%   |
| BOE LCD Monitor BOE0821 3840x2160 309x174mm 14.0-inch                  | 1         | 1.15%   |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                  | 1         | 1.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 36        | 44.44%  |
| 2560x1440 (QHD)    | 16        | 19.75%  |
| 3840x2160 (4K)     | 9         | 11.11%  |
| 3440x1440          | 3         | 3.7%    |
| 1366x768 (WXGA)    | 3         | 3.7%    |
| 2560x1600          | 2         | 2.47%   |
| 2560x1080          | 2         | 2.47%   |
| 1280x1024 (SXGA)   | 2         | 2.47%   |
| Unknown            | 2         | 2.47%   |
| 6400x1080          | 1         | 1.23%   |
| 3840x1080          | 1         | 1.23%   |
| 2256x1504          | 1         | 1.23%   |
| 1920x1200 (WUXGA)  | 1         | 1.23%   |
| 1680x1050 (WSXGA+) | 1         | 1.23%   |
| 1440x900 (WXGA+)   | 1         | 1.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 19        | 22.89%  |
| 27      | 16        | 19.28%  |
| 13      | 8         | 9.64%   |
| 14      | 6         | 7.23%   |
| 23      | 5         | 6.02%   |
| 34      | 4         | 4.82%   |
| 21      | 4         | 4.82%   |
| 24      | 3         | 3.61%   |
| 17      | 3         | 3.61%   |
| 31      | 2         | 2.41%   |
| 25      | 2         | 2.41%   |
| 19      | 2         | 2.41%   |
| 16      | 2         | 2.41%   |
| Unknown | 2         | 2.41%   |
| 84      | 1         | 1.2%    |
| 49      | 1         | 1.2%    |
| 29      | 1         | 1.2%    |
| 28      | 1         | 1.2%    |
| 20      | 1         | 1.2%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 34        | 43.59%  |
| 501-600     | 20        | 25.64%  |
| 401-500     | 6         | 7.69%   |
| 601-700     | 5         | 6.41%   |
| 701-800     | 4         | 5.13%   |
| 201-300     | 3         | 3.85%   |
| 351-400     | 2         | 2.56%   |
| Unknown     | 2         | 2.56%   |
| 1501-2000   | 1         | 1.28%   |
| 1001-1500   | 1         | 1.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 54        | 76.06%  |
| 16/10   | 6         | 8.45%   |
| 21/9    | 5         | 7.04%   |
| 5/4     | 2         | 2.82%   |
| Unknown | 2         | 2.82%   |
| 32/9    | 1         | 1.41%   |
| 3/2     | 1         | 1.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 19        | 23.46%  |
| 301-350        | 16        | 19.75%  |
| 81-90          | 12        | 14.81%  |
| 201-250        | 9         | 11.11%  |
| 351-500        | 7         | 8.64%   |
| 151-200        | 4         | 4.94%   |
| 251-300        | 3         | 3.7%    |
| 71-80          | 2         | 2.47%   |
| 141-150        | 2         | 2.47%   |
| 111-120        | 2         | 2.47%   |
| Unknown        | 2         | 2.47%   |
| More than 1000 | 1         | 1.23%   |
| 121-130        | 1         | 1.23%   |
| 501-1000       | 1         | 1.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 27        | 35.06%  |
| 101-120       | 21        | 27.27%  |
| 51-100        | 15        | 19.48%  |
| 161-240       | 8         | 10.39%  |
| More than 240 | 3         | 3.9%    |
| Unknown       | 2         | 2.6%    |
| 1-50          | 1         | 1.3%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 45        | 68.18%  |
| 2     | 12        | 18.18%  |
| 3     | 4         | 6.06%   |
| 0     | 4         | 6.06%   |
| 4     | 1         | 1.52%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 47        | 52.22%  |
| Realtek Semiconductor    | 28        | 31.11%  |
| Qualcomm Atheros         | 3         | 3.33%   |
| Aquantia                 | 3         | 3.33%   |
| MEDIATEK                 | 2         | 2.22%   |
| Samsung Electronics      | 1         | 1.11%   |
| Raspberry Pi             | 1         | 1.11%   |
| Ralink Technology        | 1         | 1.11%   |
| Microsoft                | 1         | 1.11%   |
| Marvell Technology Group | 1         | 1.11%   |
| ICS Advent               | 1         | 1.11%   |
| Google                   | 1         | 1.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 18        | 16.22%  |
| Intel Wi-Fi 6 AX200                                               | 12        | 10.81%  |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 4.5%    |
| Intel Wireless 8265 / 8275                                        | 5         | 4.5%    |
| Intel I211 Gigabit Network Connection                             | 5         | 4.5%    |
| Intel I210 Gigabit Network Connection                             | 5         | 4.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 3.6%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 2.7%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3         | 2.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 1.8%    |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 1.8%    |
| Intel Wireless-AC 9260                                            | 2         | 1.8%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 1.8%    |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.8%    |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                  | 2         | 1.8%    |
| Intel Ethernet Controller I225-V                                  | 2         | 1.8%    |
| Intel Ethernet Connection (7) I219-V                              | 2         | 1.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 1.8%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.9%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.9%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.9%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 0.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.9%    |
| Raspberry Pi Pico                                                 | 1         | 0.9%    |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 0.9%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.9%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.9%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1         | 0.9%    |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 1         | 0.9%    |
| Microsoft XBOX ACC                                                | 1         | 0.9%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.9%    |
| Intel Wireless 8260                                               | 1         | 0.9%    |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 0.9%    |
| Intel I350 Gigabit Network Connection                             | 1         | 0.9%    |
| Intel Ethernet Connection I217-V                                  | 1         | 0.9%    |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.9%    |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.9%    |
| Intel Ethernet Connection (5) I219-V                              | 1         | 0.9%    |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.9%    |
| Intel Ethernet Connection (2) I219-V                              | 1         | 0.9%    |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.9%    |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 0.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1         | 0.9%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 0.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 0.9%    |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 1         | 0.9%    |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.9%    |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1         | 0.9%    |
| Google Nexus/Pixel Device (tether)                                | 1         | 0.9%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 38        | 79.17%  |
| Realtek Semiconductor | 5         | 10.42%  |
| MEDIATEK              | 2         | 4.17%   |
| Ralink Technology     | 1         | 2.08%   |
| Qualcomm Atheros      | 1         | 2.08%   |
| Microsoft             | 1         | 2.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 12        | 24.49%  |
| Intel Wireless 8265 / 8275                                    | 5         | 10.2%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 4         | 8.16%   |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 3         | 6.12%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter | 2         | 4.08%   |
| Intel Wireless-AC 9260                                        | 2         | 4.08%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 2         | 4.08%   |
| Intel Wi-Fi 6 AX201                                           | 2         | 4.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 2         | 4.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 1         | 2.04%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 1         | 2.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1         | 2.04%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 1         | 2.04%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter               | 1         | 2.04%   |
| Ralink RT2870/RT3070 Wireless Adapter                         | 1         | 2.04%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter              | 1         | 2.04%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter    | 1         | 2.04%   |
| Microsoft XBOX ACC                                            | 1         | 2.04%   |
| Intel Wireless 8260                                           | 1         | 2.04%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 1         | 2.04%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 1         | 2.04%   |
| Intel Comet Lake PCH CNVi WiFi                                | 1         | 2.04%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 1         | 2.04%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 1         | 2.04%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 26        | 46.43%  |
| Intel                    | 21        | 37.5%   |
| Aquantia                 | 3         | 5.36%   |
| Qualcomm Atheros         | 2         | 3.57%   |
| Samsung Electronics      | 1         | 1.79%   |
| Marvell Technology Group | 1         | 1.79%   |
| ICS Advent               | 1         | 1.79%   |
| Google                   | 1         | 1.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 18        | 29.51%  |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 8.2%    |
| Intel I211 Gigabit Network Connection                             | 5         | 8.2%    |
| Intel I210 Gigabit Network Connection                             | 5         | 8.2%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3         | 4.92%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 3.28%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                  | 2         | 3.28%   |
| Intel Ethernet Controller I225-V                                  | 2         | 3.28%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 3.28%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.64%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.64%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.64%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 1.64%   |
| Intel I350 Gigabit Network Connection                             | 1         | 1.64%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.64%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.64%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.64%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 1.64%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.64%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.64%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.64%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 1.64%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.64%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1         | 1.64%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 1.64%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 48        | 50%     |
| WiFi     | 47        | 48.96%  |
| Modem    | 1         | 1.04%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 39        | 52.7%   |
| Ethernet | 35        | 47.3%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 28        | 43.08%  |
| 2     | 26        | 40%     |
| 3     | 6         | 9.23%   |
| 4     | 2         | 3.08%   |
| 0     | 2         | 3.08%   |
| 6     | 1         | 1.54%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 49        | 73.13%  |
| Yes  | 18        | 26.87%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 36        | 72%     |
| Realtek Semiconductor   | 5         | 10%     |
| Cambridge Silicon Radio | 4         | 8%      |
| Toshiba                 | 1         | 2%      |
| IMC Networks            | 1         | 2%      |
| Foxconn / Hon Hai       | 1         | 2%      |
| Edimax Technology       | 1         | 2%      |
| ASUSTek Computer        | 1         | 2%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 14        | 28%     |
| Intel AX200 Bluetooth                               | 12        | 24%     |
| Intel AX201 Bluetooth                               | 7         | 14%     |
| Realtek Bluetooth Radio                             | 4         | 8%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 8%      |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 4%      |
| Toshiba RT Bluetooth Radio                          | 1         | 2%      |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 2%      |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2%      |
| IMC Networks Wireless_Device                        | 1         | 2%      |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 2%      |
| Edimax Bluetooth Adapter                            | 1         | 2%      |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 2%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 33        | 31.73%  |
| AMD                                  | 32        | 30.77%  |
| Nvidia                               | 18        | 17.31%  |
| Thesycon Systemsoftware & Consulting | 2         | 1.92%   |
| SteelSeries ApS                      | 2         | 1.92%   |
| Logitech                             | 2         | 1.92%   |
| Creative Labs                        | 2         | 1.92%   |
| C-Media Electronics                  | 2         | 1.92%   |
| AudioQuest                           | 2         | 1.92%   |
| ASUSTek Computer                     | 2         | 1.92%   |
| Yamaha                               | 1         | 0.96%   |
| Valve Software                       | 1         | 0.96%   |
| Texas Instruments                    | 1         | 0.96%   |
| SAVITECH                             | 1         | 0.96%   |
| RODE Microphones                     | 1         | 0.96%   |
| Creative Technology                  | 1         | 0.96%   |
| ACTIONS                              | 1         | 0.96%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                  | 14        | 10.85%  |
| AMD Renoir Radeon High Definition Audio Controller                      | 9         | 6.98%   |
| AMD Starship/Matisse HD Audio Controller                                | 8         | 6.2%    |
| Intel Cannon Lake PCH cAVS                                              | 7         | 5.43%   |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]               | 5         | 3.88%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]              | 5         | 3.88%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller         | 4         | 3.1%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                     | 4         | 3.1%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller          | 3         | 2.33%   |
| Nvidia GP106 High Definition Audio Controller                           | 3         | 2.33%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller             | 3         | 2.33%   |
| Intel Sunrise Point-LP HD Audio                                         | 3         | 2.33%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller               | 3         | 2.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                     | 3         | 2.33%   |
| Thesycon Systemsoftware & Consulting E30                                | 2         | 1.55%   |
| Nvidia TU116 High Definition Audio Controller                           | 2         | 1.55%   |
| Nvidia TU102 High Definition Audio Controller                           | 2         | 1.55%   |
| Nvidia GM206 High Definition Audio Controller                           | 2         | 1.55%   |
| Intel Tiger Lake-H HD Audio Controller                                  | 2         | 1.55%   |
| Intel Comet Lake PCH-LP cAVS                                            | 2         | 1.55%   |
| Intel Comet Lake PCH cAVS                                               | 2         | 1.55%   |
| Intel CM238 HD Audio Controller                                         | 2         | 1.55%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]           | 2         | 1.55%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]            | 2         | 1.55%   |
| Yamaha Steinberg UR22mkII                                               | 1         | 0.78%   |
| Valve Software Valve VR Radio & HMD Mic                                 | 1         | 0.78%   |
| Texas Instruments PCM2912A Audio Codec                                  | 1         | 0.78%   |
| SteelSeries ApS SteelSeries Arctis 5                                    | 1         | 0.78%   |
| SteelSeries ApS Arctis 7 wireless adapter                               | 1         | 0.78%   |
| SAVITECH SA9023 audio controller                                        | 1         | 0.78%   |
| RODE Microphones RODE VideoMic NTG                                      | 1         | 0.78%   |
| Nvidia GP108 High Definition Audio Controller                           | 1         | 0.78%   |
| Nvidia GP107GL High Definition Audio Controller                         | 1         | 0.78%   |
| Nvidia GP104 High Definition Audio Controller                           | 1         | 0.78%   |
| Nvidia GP102 HDMI Audio Controller                                      | 1         | 0.78%   |
| Nvidia GM204 High Definition Audio Controller                           | 1         | 0.78%   |
| Nvidia Audio device                                                     | 1         | 0.78%   |
| Logitech Z-5 Speakers                                                   | 1         | 0.78%   |
| Logitech Yeti X                                                         | 1         | 0.78%   |
| Intel Wildcat Point-LP High Definition Audio Controller                 | 1         | 0.78%   |
| Intel USB PnP Sound Device                                              | 1         | 0.78%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                 | 1         | 0.78%   |
| Intel Cannon Point-LP High Definition Audio Controller                  | 1         | 0.78%   |
| Intel Broadwell-U Audio Controller                                      | 1         | 0.78%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                        | 1         | 0.78%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 1         | 0.78%   |
| Creative Technology Sound BlasterX G6                                   | 1         | 0.78%   |
| C-Media Electronics USB Advanced Audio Device                           | 1         | 0.78%   |
| C-Media Electronics CM108 Audio Controller                              | 1         | 0.78%   |
| AudioQuest SDAC                                                         | 1         | 0.78%   |
| AudioQuest DragonFly Red                                                | 1         | 0.78%   |
| ASUSTek Computer Xonar U1 Audio Station                                 | 1         | 0.78%   |
| ASUSTek Computer USB Audio                                              | 1         | 0.78%   |
| AMD Wrestler HDMI Audio                                                 | 1         | 0.78%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                              | 1         | 0.78%   |
| AMD Polaris 22 HDMI Audio                                               | 1         | 0.78%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 1         | 0.78%   |
| AMD FCH Azalia Controller                                               | 1         | 0.78%   |
| ACTIONS EDIFIER M380                                                    | 1         | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 24        | 33.33%  |
| SK Hynix            | 11        | 15.28%  |
| Kingston            | 11        | 15.28%  |
| Crucial             | 8         | 11.11%  |
| G.Skill             | 6         | 8.33%   |
| Micron Technology   | 4         | 5.56%   |
| Patriot             | 2         | 2.78%   |
| Unknown             | 1         | 1.39%   |
| Transcend           | 1         | 1.39%   |
| Team                | 1         | 1.39%   |
| Innodisk            | 1         | 1.39%   |
| Corsair             | 1         | 1.39%   |
| A-DATA Technology   | 1         | 1.39%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 3.95%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 2.63%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 2.63%   |
| SK Hynix RAM H9HCNNNCPMALHR-NEE 8GB Row Of Chips LPDDR4 4267MT/s | 2         | 2.63%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s           | 2         | 2.63%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 2         | 2.63%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 2         | 2.63%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 2.63%   |
| Unknown RAM Module 512MB DIMM SDRAM                              | 1         | 1.32%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 1         | 1.32%   |
| Transcend RAM JM3200HSE-32G 32GB SODIMM DDR4 3200MT/s            | 1         | 1.32%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s               | 1         | 1.32%   |
| SK Hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 1         | 1.32%   |
| SK Hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.32%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.32%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 1.32%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.32%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s              | 1         | 1.32%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 1.32%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.32%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 2667MT/s            | 1         | 1.32%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 1.32%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 1.32%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 1.32%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.32%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.32%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.32%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 1.32%   |
| Samsung RAM M378A2G43MX3-CTD 16GB DIMM DDR4 2666MT/s             | 1         | 1.32%   |
| Samsung RAM K4E6E304EB-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 1         | 1.32%   |
| Samsung RAM K4E6E304EB-EGCF 4GB Row Of Chips LPDDR3 1867MT/s     | 1         | 1.32%   |
| Patriot RAM PSD416G24002S 16GB SODIMM DDR4 2667MT/s              | 1         | 1.32%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s               | 1         | 1.32%   |
| Micron RAM Module 16GB SODIMM DDR4 2667MT/s                      | 1         | 1.32%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8192MB SODIMM DDR4 3200MT/s          | 1         | 1.32%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 1         | 1.32%   |
| Micron RAM 18KSF1G72AZ-1G6E1 8GB DIMM DDR3 1600MT/s              | 1         | 1.32%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3533MT/s             | 1         | 1.32%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s           | 1         | 1.32%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s              | 1         | 1.32%   |
| Kingston RAM KF3200C20S4/32GX 32GB SODIMM DDR4 3200MT/s          | 1         | 1.32%   |
| Kingston RAM KF3200C16D4/16GX 16384MB DIMM DDR4 3200MT/s         | 1         | 1.32%   |
| Kingston RAM HP26D4S9S8HJ-8 8GB SODIMM DDR4 2667MT/s             | 1         | 1.32%   |
| Kingston RAM 99U5624-013.A00G 8GB SODIMM DDR4 2400MT/s           | 1         | 1.32%   |
| Kingston RAM 9965525-055.A00LF 8GB DIMM DDR3 1600MT/s            | 1         | 1.32%   |
| Kingston RAM 9965487-004.A00LF 4GB DIMM 1066MT/s                 | 1         | 1.32%   |
| Kingston RAM 9905700-053.A00G 8192MB SODIMM DDR4 3200MT/s        | 1         | 1.32%   |
| Kingston RAM 9905625-062.A00G 8GB DIMM DDR4 2133MT/s             | 1         | 1.32%   |
| Innodisk RAM M4SI-AGS1OC0K-C 16GB SODIMM DDR4 2667MT/s           | 1         | 1.32%   |
| G.Skill RAM F4-3600C17-16GTZR 16GB DIMM DDR4 3666MT/s            | 1         | 1.32%   |
| G.Skill RAM F4-3600C17-16GTZKW 16GB DIMM DDR4 3600MT/s           | 1         | 1.32%   |
| G.Skill RAM F4-3600C16-8GTZN 8GB DIMM DDR4 3666MT/s              | 1         | 1.32%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s            | 1         | 1.32%   |
| G.Skill RAM F4-3000C15-8GVRB 8GB DIMM DDR4 2133MT/s              | 1         | 1.32%   |
| G.Skill RAM F3-14900CL9-4GBSR 4GB DIMM DDR3 1800MT/s             | 1         | 1.32%   |
| Crucial RAM CT8G4DFD824A.C16FF 8GB DIMM DDR4 2733MT/s            | 1         | 1.32%   |
| Crucial RAM CT8G4DFD824A.C16FBD1 8GB DIMM DDR4 2400MT/s          | 1         | 1.32%   |
| Crucial RAM CT32G4SFD832A.C16FE 32GB SODIMM DDR4 3200MT/s        | 1         | 1.32%   |
| Crucial RAM CT16G4DFD8213.C16FAD 16GB DIMM DDR4 2133MT/s         | 1         | 1.32%   |
| Crucial RAM BLS4G4D26BFSE.8FE 4GB DIMM DDR4 2667MT/s             | 1         | 1.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 50        | 80.65%  |
| DDR3    | 5         | 8.06%   |
| LPDDR3  | 3         | 4.84%   |
| LPDDR4  | 2         | 3.23%   |
| SDRAM   | 1         | 1.61%   |
| Unknown | 1         | 1.61%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 31        | 50%     |
| DIMM         | 24        | 38.71%  |
| Row Of Chips | 7         | 11.29%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 30        | 44.12%  |
| 16384 | 20        | 29.41%  |
| 4096  | 8         | 11.76%  |
| 32768 | 7         | 10.29%  |
| 2048  | 1         | 1.47%   |
| 1024  | 1         | 1.47%   |
| 512   | 1         | 1.47%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 19        | 27.94%  |
| 2667    | 18        | 26.47%  |
| 2133    | 6         | 8.82%   |
| 3600    | 4         | 5.88%   |
| 1600    | 4         | 5.88%   |
| 4267    | 2         | 2.94%   |
| 3666    | 2         | 2.94%   |
| 2400    | 2         | 2.94%   |
| 4000    | 1         | 1.47%   |
| 3866    | 1         | 1.47%   |
| 3533    | 1         | 1.47%   |
| 3400    | 1         | 1.47%   |
| 3000    | 1         | 1.47%   |
| 2733    | 1         | 1.47%   |
| 2666    | 1         | 1.47%   |
| 1867    | 1         | 1.47%   |
| 1800    | 1         | 1.47%   |
| 1066    | 1         | 1.47%   |
| Unknown | 1         | 1.47%   |

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
| IMC Networks                  | 7         | 17.5%   |
| Chicony Electronics           | 7         | 17.5%   |
| Logitech                      | 4         | 10%     |
| Sunplus Innovation Technology | 3         | 7.5%    |
| Realtek Semiconductor         | 3         | 7.5%    |
| Acer                          | 3         | 7.5%    |
| Quanta                        | 2         | 5%      |
| Luxvisions Innotech Limited   | 2         | 5%      |
| Lite-On Technology            | 2         | 5%      |
| Valve Software                | 1         | 2.5%    |
| Syntek                        | 1         | 2.5%    |
| SunplusIT                     | 1         | 2.5%    |
| Microdia                      | 1         | 2.5%    |
| KYE Systems (Mouse Systems)   | 1         | 2.5%    |
| Generalplus Technology        | 1         | 2.5%    |
| Creative Technology           | 1         | 2.5%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                      | 6         | 15%     |
| Chicony Integrated Camera                           | 3         | 7.5%    |
| Sunplus Integrated_Webcam_HD                        | 2         | 5%      |
| Realtek Integrated Webcam HD                        | 2         | 5%      |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 5%      |
| Chicony HD User Facing                              | 2         | 5%      |
| Valve Software 3D Camera                            | 1         | 2.5%    |
| Syntek Integrated Camera                            | 1         | 2.5%    |
| SunplusIT AUKEY PCÃ¢Â€Â”LM4                 | 1         | 2.5%    |
| Sunplus Full HD webcam                              | 1         | 2.5%    |
| Realtek Integrated Camera                           | 1         | 2.5%    |
| Quanta RGB-IR Camera                                | 1         | 2.5%    |
| Quanta HD Webcam                                    | 1         | 2.5%    |
| Microdia Integrated_Webcam_HD                       | 1         | 2.5%    |
| Logitech Webcam C270                                | 1         | 2.5%    |
| Logitech StreamCam                                  | 1         | 2.5%    |
| Logitech QuickCam Orbit/Sphere AF                   | 1         | 2.5%    |
| Logitech BRIO Ultra HD Webcam                       | 1         | 2.5%    |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 2.5%    |
| Lite-On Integrated Camera                           | 1         | 2.5%    |
| KYE Systems (Mouse Systems) PC-LM1E Camera          | 1         | 2.5%    |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 2.5%    |
| Generalplus GENERAL WEBCAM                          | 1         | 2.5%    |
| Creative Live! Cam Sync 1080p                       | 1         | 2.5%    |
| Chicony XiaoMi USB 2.0 Webcam                       | 1         | 2.5%    |
| Chicony HP Truevision HD                            | 1         | 2.5%    |
| Acer NEC HD WebCam                                  | 1         | 2.5%    |
| Acer Integrated Camera                              | 1         | 2.5%    |
| Acer HD Webcam                                      | 1         | 2.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 2         | 28.57%  |
| Synaptics                  | 2         | 28.57%  |
| Elan Microelectronics      | 2         | 28.57%  |
| Shenzhen Goodix Technology | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Elan ELAN:Fingerprint                             | 2         | 28.57%  |
| Validity Sensors VFS7552 Touch Fingerprint Sensor | 1         | 14.29%  |
| Validity Sensors Synaptics WBDI                   | 1         | 14.29%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 14.29%  |
| Shenzhen Goodix  FingerPrint Device               | 1         | 14.29%  |
| Unknown                                           | 1         | 14.29%  |

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
| 0     | 40        | 59.7%   |
| 1     | 17        | 25.37%  |
| 2     | 6         | 8.96%   |
| 3     | 3         | 4.48%   |
| 4     | 1         | 1.49%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 7         | 17.95%  |
| Communication controller | 7         | 17.95%  |
| Graphics card            | 5         | 12.82%  |
| Camera                   | 5         | 12.82%  |
| Bluetooth                | 4         | 10.26%  |
| Multimedia controller    | 3         | 7.69%   |
| Chipcard                 | 3         | 7.69%   |
| Net/wireless             | 2         | 5.13%   |
| Storage/ata              | 1         | 2.56%   |
| Modem                    | 1         | 2.56%   |
| Card reader              | 1         | 2.56%   |

