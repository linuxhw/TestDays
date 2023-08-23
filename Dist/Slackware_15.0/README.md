Slackware 15.0 - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Slackware 15.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Slackware_15.0/Desktop/README.md) and [notebooks](/Dist/Slackware_15.0/Notebook/README.md).

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

Total: 106

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Valve         | Jupiter                     | Notebook    | [eee501d93c](https://linux-hardware.org/?probe=eee501d93c) | Aug 09, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [eec04bec1d](https://linux-hardware.org/?probe=eec04bec1d) | Aug 08, 2023 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [0a7b2a3fcc](https://linux-hardware.org/?probe=0a7b2a3fcc) | Aug 03, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [3f7bed61a8](https://linux-hardware.org/?probe=3f7bed61a8) | Jul 26, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [6087b16809](https://linux-hardware.org/?probe=6087b16809) | Jul 15, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [dd63c138ad](https://linux-hardware.org/?probe=dd63c138ad) | Jul 15, 2023 |
| Fujitsu       | FujitsuTP7000 -1            | Desktop     | [231d7f8182](https://linux-hardware.org/?probe=231d7f8182) | Jun 18, 2023 |
| Acer          | Swift SF114-34              | Notebook    | [ec48f7a207](https://linux-hardware.org/?probe=ec48f7a207) | May 28, 2023 |
| MSI           | X99A GAMING 7               | Desktop     | [ec94d173a7](https://linux-hardware.org/?probe=ec94d173a7) | May 23, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [90b4889055](https://linux-hardware.org/?probe=90b4889055) | May 21, 2023 |
| ASRock        | N68-S3 FX                   | Desktop     | [0ed94fe810](https://linux-hardware.org/?probe=0ed94fe810) | May 10, 2023 |
| HEDYCOMPUT... | IH81MF-Q3                   | Desktop     | [3444236ed4](https://linux-hardware.org/?probe=3444236ed4) | Apr 30, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [941aa94750](https://linux-hardware.org/?probe=941aa94750) | Apr 13, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [7f052050d9](https://linux-hardware.org/?probe=7f052050d9) | Apr 10, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [70314c0c37](https://linux-hardware.org/?probe=70314c0c37) | Mar 23, 2023 |
| Dell          | 0MY171 A00                  | Desktop     | [47fd974afd](https://linux-hardware.org/?probe=47fd974afd) | Mar 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [e9844f7162](https://linux-hardware.org/?probe=e9844f7162) | Mar 13, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [053498458e](https://linux-hardware.org/?probe=053498458e) | Mar 03, 2023 |
| Dell          | 0MY171 A00                  | Desktop     | [795f707b1a](https://linux-hardware.org/?probe=795f707b1a) | Feb 25, 2023 |
| Dell          | 04YP6J A03                  | Desktop     | [696cc9b57a](https://linux-hardware.org/?probe=696cc9b57a) | Feb 19, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | Notebook    | [fde666c0ea](https://linux-hardware.org/?probe=fde666c0ea) | Feb 17, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | Notebook    | [5ce5272a93](https://linux-hardware.org/?probe=5ce5272a93) | Feb 17, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [7ce91f2b1e](https://linux-hardware.org/?probe=7ce91f2b1e) | Feb 16, 2023 |
| Lenovo        | ThinkPad X140e 20BMS03E0... | Notebook    | [fb4c4aebf9](https://linux-hardware.org/?probe=fb4c4aebf9) | Jan 31, 2023 |
| Lenovo        | ThinkPad T470p 20J60018M... | Notebook    | [9324b897c3](https://linux-hardware.org/?probe=9324b897c3) | Jan 19, 2023 |
| ASRock        | N68-S UCC                   | Desktop     | [cb4c89a390](https://linux-hardware.org/?probe=cb4c89a390) | Jan 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [1b50127412](https://linux-hardware.org/?probe=1b50127412) | Jan 14, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [9edc837033](https://linux-hardware.org/?probe=9edc837033) | Jan 13, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [1c9dc6792e](https://linux-hardware.org/?probe=1c9dc6792e) | Jan 13, 2023 |
| HP            | OMEN by Laptop 17-ck0xxx    | Notebook    | [9655429e71](https://linux-hardware.org/?probe=9655429e71) | Jan 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [4900ec9966](https://linux-hardware.org/?probe=4900ec9966) | Jan 05, 2023 |
| ASRock        | B550 Taichi                 | Desktop     | [469f9d71e2](https://linux-hardware.org/?probe=469f9d71e2) | Dec 29, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [5205b7c248](https://linux-hardware.org/?probe=5205b7c248) | Dec 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [1cf2ac2b8b](https://linux-hardware.org/?probe=1cf2ac2b8b) | Dec 27, 2022 |
| Dell          | 0MY171 A00                  | Desktop     | [055bc4ea78](https://linux-hardware.org/?probe=055bc4ea78) | Dec 13, 2022 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [c0bf1336d5](https://linux-hardware.org/?probe=c0bf1336d5) | Dec 12, 2022 |
| HP            | OMEN by Laptop 16-b1xxx     | Notebook    | [799470f1aa](https://linux-hardware.org/?probe=799470f1aa) | Dec 05, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [d000e4e926](https://linux-hardware.org/?probe=d000e4e926) | Dec 02, 2022 |
| HP            | OMEN by Laptop 16-b1xxx     | Notebook    | [0cd3005f69](https://linux-hardware.org/?probe=0cd3005f69) | Dec 01, 2022 |
| HP            | OMEN by Laptop 16-b1xxx     | Notebook    | [32b68762df](https://linux-hardware.org/?probe=32b68762df) | Nov 30, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [1408b2dc5f](https://linux-hardware.org/?probe=1408b2dc5f) | Nov 18, 2022 |
| Lenovo        | ThinkPad T470 20JNS01R01    | Notebook    | [abb8194196](https://linux-hardware.org/?probe=abb8194196) | Oct 21, 2022 |
| Lenovo        | ThinkPad T61 765912G        | Notebook    | [e7f2dc737e](https://linux-hardware.org/?probe=e7f2dc737e) | Oct 09, 2022 |
| Lenovo        | ThinkPad T410 2518C3U       | Notebook    | [4d250adf3b](https://linux-hardware.org/?probe=4d250adf3b) | Oct 04, 2022 |
| HP            | 3031h                       | Desktop     | [b6849a29a2](https://linux-hardware.org/?probe=b6849a29a2) | Sep 24, 2022 |
| Lenovo        | ThinkPad T61 765912G        | Notebook    | [bd04e564a0](https://linux-hardware.org/?probe=bd04e564a0) | Sep 24, 2022 |
| HP            | 3031h                       | Desktop     | [40160588bb](https://linux-hardware.org/?probe=40160588bb) | Sep 20, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [2299dc1786](https://linux-hardware.org/?probe=2299dc1786) | Sep 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [a954ba4e86](https://linux-hardware.org/?probe=a954ba4e86) | Aug 26, 2022 |
| Dell          | 0200DY A03                  | Desktop     | [e0e14cd1f2](https://linux-hardware.org/?probe=e0e14cd1f2) | Aug 19, 2022 |
| Fujitsu       | LIFEBOOK A544               | Notebook    | [e5785106f1](https://linux-hardware.org/?probe=e5785106f1) | Aug 09, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [b9cde08864](https://linux-hardware.org/?probe=b9cde08864) | Jul 25, 2022 |
| Gigabyte      | N3160TN                     | Desktop     | [e2f44a8274](https://linux-hardware.org/?probe=e2f44a8274) | May 31, 2022 |
| Sony          | SVE1713A1EW                 | Notebook    | [c3a65d695d](https://linux-hardware.org/?probe=c3a65d695d) | May 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [f837aaeb12](https://linux-hardware.org/?probe=f837aaeb12) | May 08, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [bd2dda1d8a](https://linux-hardware.org/?probe=bd2dda1d8a) | Apr 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [cfc9c5dbf7](https://linux-hardware.org/?probe=cfc9c5dbf7) | Apr 29, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [533b8a9f83](https://linux-hardware.org/?probe=533b8a9f83) | Apr 13, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [25d8968f19](https://linux-hardware.org/?probe=25d8968f19) | Apr 13, 2022 |
| MSI           | GP76 Leopard 11UG           | Notebook    | [aebd373a66](https://linux-hardware.org/?probe=aebd373a66) | Apr 12, 2022 |
| MSI           | GE76 Raider 11UE            | Notebook    | [3072e065a3](https://linux-hardware.org/?probe=3072e065a3) | Apr 12, 2022 |
| Notebook      | X170KM-G                    | Notebook    | [4ecba03d19](https://linux-hardware.org/?probe=4ecba03d19) | Apr 11, 2022 |
| ASRock        | N68-S3 FX                   | Desktop     | [ca818bd06d](https://linux-hardware.org/?probe=ca818bd06d) | Apr 08, 2022 |
| MSI           | MS-7365                     | Desktop     | [8948dea4de](https://linux-hardware.org/?probe=8948dea4de) | Apr 07, 2022 |
| Unknown       | X79-P3                      | Desktop     | [40e38e9a8d](https://linux-hardware.org/?probe=40e38e9a8d) | Apr 07, 2022 |
| Dell          | Latitude 3520               | Notebook    | [4398aa2a03](https://linux-hardware.org/?probe=4398aa2a03) | Apr 06, 2022 |
| HP            | ProBook 6570b               | Notebook    | [cf1305eacc](https://linux-hardware.org/?probe=cf1305eacc) | Apr 06, 2022 |
| HP            | 0A08h                       | Desktop     | [4df5b0832f](https://linux-hardware.org/?probe=4df5b0832f) | Apr 06, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [d406cb4819](https://linux-hardware.org/?probe=d406cb4819) | Apr 05, 2022 |
| Dell          | Precision M4700             | Notebook    | [ab99532bd5](https://linux-hardware.org/?probe=ab99532bd5) | Apr 04, 2022 |
| ASRock        | H410M-ITX/ac                | Desktop     | [ae936790c9](https://linux-hardware.org/?probe=ae936790c9) | Apr 03, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [5307aba2c3](https://linux-hardware.org/?probe=5307aba2c3) | Mar 30, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [c8289cd264](https://linux-hardware.org/?probe=c8289cd264) | Mar 26, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [5c6b1616fa](https://linux-hardware.org/?probe=5c6b1616fa) | Mar 21, 2022 |
| Acer          | FMCP7A-ION-LE               | Desktop     | [bbce73c6d6](https://linux-hardware.org/?probe=bbce73c6d6) | Mar 14, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [5f36bc3969](https://linux-hardware.org/?probe=5f36bc3969) | Mar 12, 2022 |
| ASRock        | H270 Pro4                   | Desktop     | [ae79ca8557](https://linux-hardware.org/?probe=ae79ca8557) | Mar 12, 2022 |
| HP            | 86F3 00100                  | All in one  | [7de0381db8](https://linux-hardware.org/?probe=7de0381db8) | Mar 11, 2022 |
| Lenovo        | ThinkPad X230 2325P38       | Notebook    | [1a0cab737b](https://linux-hardware.org/?probe=1a0cab737b) | Mar 10, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [0b0c1aca1b](https://linux-hardware.org/?probe=0b0c1aca1b) | Mar 10, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c7825c54fc](https://linux-hardware.org/?probe=c7825c54fc) | Mar 10, 2022 |
| Framework     | Laptop                      | Notebook    | [ae37705198](https://linux-hardware.org/?probe=ae37705198) | Mar 10, 2022 |
| Dell          | 068NXX A00                  | Server      | [85004f427a](https://linux-hardware.org/?probe=85004f427a) | Mar 09, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [bc59b862f4](https://linux-hardware.org/?probe=bc59b862f4) | Mar 02, 2022 |
| TYAN Compu... | S7012                       | Server      | [fec98b51da](https://linux-hardware.org/?probe=fec98b51da) | Feb 27, 2022 |
| TYAN Compu... | S7012                       | Server      | [81a490184b](https://linux-hardware.org/?probe=81a490184b) | Feb 26, 2022 |
| Biostar       | X470GTA                     | Desktop     | [8d400b49f8](https://linux-hardware.org/?probe=8d400b49f8) | Feb 13, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [8ce0419468](https://linux-hardware.org/?probe=8ce0419468) | Feb 13, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [dda6a57223](https://linux-hardware.org/?probe=dda6a57223) | Feb 07, 2022 |
| HP            | 212B                        | Desktop     | [353b0dde99](https://linux-hardware.org/?probe=353b0dde99) | Jan 29, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [85543358d3](https://linux-hardware.org/?probe=85543358d3) | Jan 14, 2022 |
| Dynabook      | P1-C7MP-BL                  | Notebook    | [268f94787e](https://linux-hardware.org/?probe=268f94787e) | Jan 14, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [25d668ee95](https://linux-hardware.org/?probe=25d668ee95) | Jan 10, 2022 |
| MSI           | H61M-P31                    | Desktop     | [58651bba67](https://linux-hardware.org/?probe=58651bba67) | Dec 07, 2021 |
| HP            | Laptop 15-bs1xx             | Notebook    | [b6c9f34c4c](https://linux-hardware.org/?probe=b6c9f34c4c) | Dec 07, 2021 |
| System76      | Oryx Pro                    | Notebook    | [3cd05d02a8](https://linux-hardware.org/?probe=3cd05d02a8) | Oct 27, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [b7df25ba5d](https://linux-hardware.org/?probe=b7df25ba5d) | Oct 25, 2021 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [64e5ee1691](https://linux-hardware.org/?probe=64e5ee1691) | Oct 13, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [17d37c5316](https://linux-hardware.org/?probe=17d37c5316) | Oct 12, 2021 |
| MSI           | Modern 14 B11MO             | Notebook    | [e8f13facfd](https://linux-hardware.org/?probe=e8f13facfd) | Oct 03, 2021 |
| MSI           | Modern 14 B11MO             | Notebook    | [9f5c2e0fde](https://linux-hardware.org/?probe=9f5c2e0fde) | Sep 27, 2021 |
| Dell          | Inspiron 15-3552            | Notebook    | [f76339b0af](https://linux-hardware.org/?probe=f76339b0af) | Aug 31, 2021 |
| HP            | 245 G7 Notebook PC          | Notebook    | [c0806e4955](https://linux-hardware.org/?probe=c0806e4955) | Aug 23, 2021 |
| HP            | 245 G7 Notebook PC          | Notebook    | [c409287d23](https://linux-hardware.org/?probe=c409287d23) | Aug 23, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [4c196e1abd](https://linux-hardware.org/?probe=4c196e1abd) | Aug 18, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [53a1179121](https://linux-hardware.org/?probe=53a1179121) | Aug 12, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.19           | 19        | 20.65%  |
| 5.19.17           | 6         | 6.52%   |
| 5.15.63           | 6         | 6.52%   |
| 5.15.27           | 4         | 4.35%   |
| 5.19.17-Unraid    | 3         | 3.26%   |
| 5.15.38           | 3         | 3.26%   |
| 5.15.117          | 3         | 3.26%   |
| 5.17.2            | 2         | 2.17%   |
| 5.17.1            | 2         | 2.17%   |
| 5.16.13           | 2         | 2.17%   |
| 5.15.94           | 2         | 2.17%   |
| 5.15.80           | 2         | 2.17%   |
| 5.15.30-Unraid    | 2         | 2.17%   |
| 5.13.8            | 2         | 2.17%   |
| 6.1.44            | 1         | 1.09%   |
| 6.1.27            | 1         | 1.09%   |
| 6.1.20            | 1         | 1.09%   |
| 6.1.13            | 1         | 1.09%   |
| 6.1.12            | 1         | 1.09%   |
| 6.1.1             | 1         | 1.09%   |
| 5.19.16           | 1         | 1.09%   |
| 5.17.5            | 1         | 1.09%   |
| 5.17.0-custom     | 1         | 1.09%   |
| 5.16.9-joe1       | 1         | 1.09%   |
| 5.16.18           | 1         | 1.09%   |
| 5.16.12           | 1         | 1.09%   |
| 5.16.11           | 1         | 1.09%   |
| 5.15.78.a         | 1         | 1.09%   |
| 5.15.6            | 1         | 1.09%   |
| 5.15.37.a         | 1         | 1.09%   |
| 5.15.33.kjh       | 1         | 1.09%   |
| 5.15.21-hardened1 | 1         | 1.09%   |
| 5.15.14           | 1         | 1.09%   |
| 5.15.13           | 1         | 1.09%   |
| 5.15.103          | 1         | 1.09%   |
| 5.15.1            | 1         | 1.09%   |
| 5.14.9            | 1         | 1.09%   |
| 5.14.8            | 1         | 1.09%   |
| 5.14.15-Unraid    | 1         | 1.09%   |
| 5.14.15           | 1         | 1.09%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.19  | 19        | 20.65%  |
| 5.19.17  | 9         | 9.78%   |
| 5.15.63  | 6         | 6.52%   |
| 5.15.27  | 4         | 4.35%   |
| 5.15.38  | 3         | 3.26%   |
| 5.15.117 | 3         | 3.26%   |
| 5.17.2   | 2         | 2.17%   |
| 5.17.1   | 2         | 2.17%   |
| 5.16.13  | 2         | 2.17%   |
| 5.15.94  | 2         | 2.17%   |
| 5.15.80  | 2         | 2.17%   |
| 5.15.30  | 2         | 2.17%   |
| 5.14.15  | 2         | 2.17%   |
| 5.13.8   | 2         | 2.17%   |
| 6.1.44   | 1         | 1.09%   |
| 6.1.27   | 1         | 1.09%   |
| 6.1.20   | 1         | 1.09%   |
| 6.1.13   | 1         | 1.09%   |
| 6.1.12   | 1         | 1.09%   |
| 6.1.1    | 1         | 1.09%   |
| 5.19.16  | 1         | 1.09%   |
| 5.17.5   | 1         | 1.09%   |
| 5.17.0   | 1         | 1.09%   |
| 5.16.9   | 1         | 1.09%   |
| 5.16.18  | 1         | 1.09%   |
| 5.16.12  | 1         | 1.09%   |
| 5.16.11  | 1         | 1.09%   |
| 5.15.78  | 1         | 1.09%   |
| 5.15.6   | 1         | 1.09%   |
| 5.15.37  | 1         | 1.09%   |
| 5.15.33  | 1         | 1.09%   |
| 5.15.21  | 1         | 1.09%   |
| 5.15.14  | 1         | 1.09%   |
| 5.15.13  | 1         | 1.09%   |
| 5.15.103 | 1         | 1.09%   |
| 5.15.1   | 1         | 1.09%   |
| 5.14.9   | 1         | 1.09%   |
| 5.14.8   | 1         | 1.09%   |
| 5.14.12  | 1         | 1.09%   |
| 5.14.11  | 1         | 1.09%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 50        | 55.56%  |
| 5.19    | 10        | 11.11%  |
| 5.14    | 7         | 7.78%   |
| 5.17    | 6         | 6.67%   |
| 5.16    | 6         | 6.67%   |
| 6.1     | 5         | 5.56%   |
| 5.13    | 5         | 5.56%   |
| 5.10    | 1         | 1.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 86        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE5       | 36        | 40.91%  |
| XFCE       | 25        | 28.41%  |
| Unknown    | 15        | 17.05%  |
| GNOME      | 3         | 3.41%   |
| xwmconfig  | 2         | 2.27%   |
| X-Generic  | 1         | 1.14%   |
| X-Cinnamon | 1         | 1.14%   |
| MATE       | 1         | 1.14%   |
| KDE        | 1         | 1.14%   |
| FVWM       | 1         | 1.14%   |
| awesome    | 1         | 1.14%   |
| 2bwm       | 1         | 1.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 49        | 53.85%  |
| Tty     | 31        | 34.07%  |
| Wayland | 6         | 6.59%   |
| Unknown | 5         | 5.49%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 44        | 49.44%  |
| Unknown | 24        | 26.97%  |
| XDM     | 14        | 15.73%  |
| LightDM | 5         | 5.62%   |
| SLiM    | 1         | 1.12%   |
| GDM     | 1         | 1.12%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 55        | 63.95%  |
| Unknown     | 10        | 11.63%  |
| it_IT       | 4         | 4.65%   |
| pt_BR       | 3         | 3.49%   |
| de_DE       | 3         | 3.49%   |
| ru_RU       | 2         | 2.33%   |
| fr_FR       | 2         | 2.33%   |
| en_GB       | 2         | 2.33%   |
| us          | 1         | 1.16%   |
| pt_PT       | 1         | 1.16%   |
| es_ES.UTF8  | 1         | 1.16%   |
| es_ES       | 1         | 1.16%   |
| en_US.ASCII | 1         | 1.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 48        | 55.81%  |
| BIOS | 38        | 44.19%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 62        | 71.26%  |
| Btrfs   | 10        | 11.49%  |
| Xfs     | 5         | 5.75%   |
| Overlay | 5         | 5.75%   |
| Zfs     | 1         | 1.15%   |
| Tmpfs   | 1         | 1.15%   |
| Rootfs  | 1         | 1.15%   |
| F2fs    | 1         | 1.15%   |
| Ext2    | 1         | 1.15%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 61        | 70.11%  |
| MBR     | 14        | 16.09%  |
| Unknown | 12        | 13.79%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 62        | 70.45%  |
| Yes       | 26        | 29.55%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 59        | 68.6%   |
| Yes       | 27        | 31.4%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 16        | 18.6%   |
| MSI                 | 12        | 13.95%  |
| Lenovo              | 11        | 12.79%  |
| ASUSTek Computer    | 11        | 12.79%  |
| Dell                | 8         | 9.3%    |
| ASRock              | 7         | 8.14%   |
| Gigabyte Technology | 3         | 3.49%   |
| Acer                | 3         | 3.49%   |
| Fujitsu             | 2         | 2.33%   |
| Apple               | 2         | 2.33%   |
| Valve               | 1         | 1.16%   |
| TYAN Computer       | 1         | 1.16%   |
| System76            | 1         | 1.16%   |
| Sony                | 1         | 1.16%   |
| Notebook            | 1         | 1.16%   |
| Microsoft           | 1         | 1.16%   |
| HEDYCOMPUTER        | 1         | 1.16%   |
| Framework           | 1         | 1.16%   |
| Dynabook            | 1         | 1.16%   |
| Biostar             | 1         | 1.16%   |
| Unknown             | 1         | 1.16%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| ASUS VivoBook_ASUSLaptop K6500ZE_K6500ZE | 2         | 2.33%   |
| ASRock N68-S3 FX                         | 2         | 2.33%   |
| Valve Jupiter                            | 1         | 1.16%   |
| TYAN S7012                               | 1         | 1.16%   |
| System76 Oryx Pro                        | 1         | 1.16%   |
| Sony SVE1713A1EW                         | 1         | 1.16%   |
| Notebook X170KM-G                        | 1         | 1.16%   |
| MSI MS-7C52                              | 1         | 1.16%   |
| MSI MS-7C02                              | 1         | 1.16%   |
| MSI MS-7996                              | 1         | 1.16%   |
| MSI MS-7885                              | 1         | 1.16%   |
| MSI MS-7788                              | 1         | 1.16%   |
| MSI MS-7693                              | 1         | 1.16%   |
| MSI MS-7529                              | 1         | 1.16%   |
| MSI MS-7365                              | 1         | 1.16%   |
| MSI Modern 14 B11MO                      | 1         | 1.16%   |
| MSI Modern 14 B10MW                      | 1         | 1.16%   |
| MSI GP76 Leopard 11UG                    | 1         | 1.16%   |
| MSI GE76 Raider 11UE                     | 1         | 1.16%   |
| Microsoft Surface Go 3                   | 1         | 1.16%   |
| Lenovo ThinkPad X230 2325P38             | 1         | 1.16%   |
| Lenovo ThinkPad X140e 20BMS03E00         | 1         | 1.16%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS04300 | 1         | 1.16%   |
| Lenovo ThinkPad T61 765912G              | 1         | 1.16%   |
| Lenovo ThinkPad T470p 20J60018MS         | 1         | 1.16%   |
| Lenovo ThinkPad T470 20JNS01R01          | 1         | 1.16%   |
| Lenovo ThinkPad T410 2518C3U             | 1         | 1.16%   |
| Lenovo ThinkPad Edge E530c 336669G       | 1         | 1.16%   |
| Lenovo IdeaPad 5 15ALC05 82LN            | 1         | 1.16%   |
| Lenovo IdeaPad 310-15ISK 80SM            | 1         | 1.16%   |
| Lenovo H50-05 90BH001WIX                 | 1         | 1.16%   |
| HP Z440 Workstation                      | 1         | 1.16%   |
| HP xw8400 Workstation                    | 1         | 1.16%   |
| HP ProBook 6570b                         | 1         | 1.16%   |
| HP Pavilion Gaming Laptop 16-a0xxx       | 1         | 1.16%   |
| HP Pavilion Gaming Laptop 15-ec1xxx      | 1         | 1.16%   |
| HP Pavilion Gaming Desktop TG01-2xxx     | 1         | 1.16%   |
| HP OMEN by Laptop 17-ck0xxx              | 1         | 1.16%   |
| HP OMEN by Laptop 16-b1xxx               | 1         | 1.16%   |
| HP Laptop 15-bs1xx                       | 1         | 1.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 8         | 9.3%    |
| HP Pavilion            | 3         | 3.49%   |
| ASUS ROG               | 3         | 3.49%   |
| ASUS PRIME             | 3         | 3.49%   |
| MSI Modern             | 2         | 2.33%   |
| Lenovo IdeaPad         | 2         | 2.33%   |
| HP OMEN                | 2         | 2.33%   |
| HP Laptop              | 2         | 2.33%   |
| HP EliteBook           | 2         | 2.33%   |
| Dell Precision         | 2         | 2.33%   |
| Dell OptiPlex          | 2         | 2.33%   |
| ASUS VivoBook          | 2         | 2.33%   |
| ASUS TUF               | 2         | 2.33%   |
| ASRock N68-S3          | 2         | 2.33%   |
| Valve Jupiter          | 1         | 1.16%   |
| TYAN S7012             | 1         | 1.16%   |
| System76 Oryx          | 1         | 1.16%   |
| Sony SVE1713A1EW       | 1         | 1.16%   |
| Notebook X170KM-G      | 1         | 1.16%   |
| MSI MS-7C52            | 1         | 1.16%   |
| MSI MS-7C02            | 1         | 1.16%   |
| MSI MS-7996            | 1         | 1.16%   |
| MSI MS-7885            | 1         | 1.16%   |
| MSI MS-7788            | 1         | 1.16%   |
| MSI MS-7693            | 1         | 1.16%   |
| MSI MS-7529            | 1         | 1.16%   |
| MSI MS-7365            | 1         | 1.16%   |
| MSI GP76               | 1         | 1.16%   |
| MSI GE76               | 1         | 1.16%   |
| Microsoft Surface      | 1         | 1.16%   |
| Lenovo H50-05          | 1         | 1.16%   |
| HP Z440                | 1         | 1.16%   |
| HP xw8400              | 1         | 1.16%   |
| HP ProBook             | 1         | 1.16%   |
| HP ENVY                | 1         | 1.16%   |
| HP Compaq              | 1         | 1.16%   |
| HP 245                 | 1         | 1.16%   |
| HP 205                 | 1         | 1.16%   |
| HEDYCOMPUTER IH81MF-Q3 | 1         | 1.16%   |
| Gigabyte N3160TN       | 1         | 1.16%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 13        | 15.12%  |
| 2021 | 12        | 13.95%  |
| 2017 | 8         | 9.3%    |
| 2022 | 7         | 8.14%   |
| 2015 | 7         | 8.14%   |
| 2012 | 6         | 6.98%   |
| 2011 | 6         | 6.98%   |
| 2019 | 5         | 5.81%   |
| 2018 | 4         | 4.65%   |
| 2014 | 3         | 3.49%   |
| 2010 | 3         | 3.49%   |
| 2009 | 3         | 3.49%   |
| 2008 | 3         | 3.49%   |
| 2007 | 3         | 3.49%   |
| 2016 | 2         | 2.33%   |
| 2013 | 1         | 1.16%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 41        | 47.67%  |
| Desktop    | 39        | 45.35%  |
| All in one | 2         | 2.33%   |
| Server     | 2         | 2.33%   |
| Tablet     | 1         | 1.16%   |
| Mini pc    | 1         | 1.16%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 86        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 84        | 97.67%  |
| Yes  | 2         | 2.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 21        | 24.14%  |
| 8.01-16.0   | 16        | 18.39%  |
| 3.01-4.0    | 14        | 16.09%  |
| 4.01-8.0    | 12        | 13.79%  |
| 32.01-64.0  | 11        | 12.64%  |
| 64.01-256.0 | 6         | 6.9%    |
| 24.01-32.0  | 4         | 4.6%    |
| 1.01-2.0    | 3         | 3.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 24        | 26.37%  |
| 1.01-2.0   | 22        | 24.18%  |
| 4.01-8.0   | 20        | 21.98%  |
| 0.51-1.0   | 10        | 10.99%  |
| 3.01-4.0   | 6         | 6.59%   |
| 16.01-24.0 | 3         | 3.3%    |
| 0.01-0.5   | 3         | 3.3%    |
| 8.01-16.0  | 2         | 2.2%    |
| 32.01-64.0 | 1         | 1.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 43        | 48.31%  |
| 2      | 24        | 26.97%  |
| 3      | 10        | 11.24%  |
| 4      | 5         | 5.62%   |
| 6      | 4         | 4.49%   |
| 11     | 1         | 1.12%   |
| 9      | 1         | 1.12%   |
| 0      | 1         | 1.12%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 57        | 65.52%  |
| Yes       | 30        | 34.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 77        | 89.53%  |
| No        | 9         | 10.47%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 63        | 72.41%  |
| No        | 24        | 27.59%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 55        | 63.95%  |
| No        | 31        | 36.05%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 20        | 23.26%  |
| Italy        | 7         | 8.14%   |
| Kazakhstan   | 6         | 6.98%   |
| Brazil       | 6         | 6.98%   |
| UK           | 5         | 5.81%   |
| Germany      | 5         | 5.81%   |
| Japan        | 4         | 4.65%   |
| Spain        | 3         | 3.49%   |
| South Africa | 3         | 3.49%   |
| Russia       | 3         | 3.49%   |
| Portugal     | 3         | 3.49%   |
| Greece       | 3         | 3.49%   |
| India        | 2         | 2.33%   |
| Hong Kong    | 2         | 2.33%   |
| France       | 2         | 2.33%   |
| Canada       | 2         | 2.33%   |
| Switzerland  | 1         | 1.16%   |
| Sweden       | 1         | 1.16%   |
| Serbia       | 1         | 1.16%   |
| Romania      | 1         | 1.16%   |
| Netherlands  | 1         | 1.16%   |
| Mexico       | 1         | 1.16%   |
| China        | 1         | 1.16%   |
| Chile        | 1         | 1.16%   |
| Australia    | 1         | 1.16%   |
| Argentina    | 1         | 1.16%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Ust-Kamenogorsk   | 4         | 4.55%   |
| Tsukuba           | 3         | 3.41%   |
| Lisbon            | 3         | 3.41%   |
| Chania            | 3         | 3.41%   |
| Sun Prairie       | 2         | 2.27%   |
| Rome              | 2         | 2.27%   |
| Moscow            | 2         | 2.27%   |
| McKinney          | 2         | 2.27%   |
| Karaganda         | 2         | 2.27%   |
| Greater Noida     | 2         | 2.27%   |
| Frignano          | 2         | 2.27%   |
| Fayetteville      | 2         | 2.27%   |
| Cape Town         | 2         | 2.27%   |
| Worpswede         | 1         | 1.14%   |
| Winter Springs    | 1         | 1.14%   |
| Toronto           | 1         | 1.14%   |
| Tatuí            | 1         | 1.14%   |
| St Petersburg     | 1         | 1.14%   |
| Springfield       | 1         | 1.14%   |
| Skövde           | 1         | 1.14%   |
| Sham Shui Po      | 1         | 1.14%   |
| Seville           | 1         | 1.14%   |
| Senhora da Hora   | 1         | 1.14%   |
| Sao Paulo         | 1         | 1.14%   |
| Santiago          | 1         | 1.14%   |
| Santa Cruz do Sul | 1         | 1.14%   |
| Saint Paul        | 1         | 1.14%   |
| Round Rock        | 1         | 1.14%   |
| Rock              | 1         | 1.14%   |
| Reno              | 1         | 1.14%   |
| Renazzo           | 1         | 1.14%   |
| Porto Alegre      | 1         | 1.14%   |
| Plainwell         | 1         | 1.14%   |
| Penrith           | 1         | 1.14%   |
| Ōtsu             | 1         | 1.14%   |
| Oberstreit        | 1         | 1.14%   |
| Nanping           | 1         | 1.14%   |
| Naaldwijk         | 1         | 1.14%   |
| Montreal          | 1         | 1.14%   |
| Milwaukee         | 1         | 1.14%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 24        | 32     | 16.67%  |
| WDC                 | 22        | 40     | 15.28%  |
| Seagate             | 21        | 30     | 14.58%  |
| Toshiba             | 11        | 22     | 7.64%   |
| Kingston            | 10        | 12     | 6.94%   |
| Crucial             | 6         | 7      | 4.17%   |
| Intel               | 5         | 6      | 3.47%   |
| Hitachi             | 5         | 8      | 3.47%   |
| SK hynix            | 4         | 4      | 2.78%   |
| HGST                | 4         | 4      | 2.78%   |
| Transcend           | 3         | 3      | 2.08%   |
| SanDisk             | 3         | 4      | 2.08%   |
| KIOXIA              | 3         | 3      | 2.08%   |
| Micron Technology   | 2         | 2      | 1.39%   |
| Hewlett-Packard     | 2         | 3      | 1.39%   |
| Gigabyte Technology | 2         | 2      | 1.39%   |
| ZHITAI              | 1         | 2      | 0.69%   |
| Unknown             | 1         | 2      | 0.69%   |
| Silicon Motion      | 1         | 1      | 0.69%   |
| PNY                 | 1         | 1      | 0.69%   |
| Plextor             | 1         | 1      | 0.69%   |
| Phison Electronics  | 1         | 1      | 0.69%   |
| Patriot             | 1         | 1      | 0.69%   |
| Maxtor              | 1         | 1      | 0.69%   |
| Lexar               | 1         | 1      | 0.69%   |
| JMicron Technology  | 1         | 1      | 0.69%   |
| Intenso             | 1         | 1      | 0.69%   |
| GOODRAM             | 1         | 1      | 0.69%   |
| External            | 1         | 1      | 0.69%   |
| DUEX                | 1         | 1      | 0.69%   |
| China               | 1         | 1      | 0.69%   |
| Apple               | 1         | 1      | 0.69%   |
| A-DATA Technology   | 1         | 1      | 0.69%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD      | 4         | 2.42%   |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 2         | 1.21%   |
| WDC WD20EFRX-68EUZN0 2TB             | 2         | 1.21%   |
| WDC WD10SPZX-60Z10T0 1TB             | 2         | 1.21%   |
| WDC WD10EZEX-08WN4A0 1TB             | 2         | 1.21%   |
| Seagate ST2000DM008-2FR102 2TB       | 2         | 1.21%   |
| Seagate ST2000DL003-9VT166 2TB       | 2         | 1.21%   |
| Seagate ST1000DM003-1SB102 1TB       | 2         | 1.21%   |
| Seagate Expansion Desk 8TB           | 2         | 1.21%   |
| Samsung SSD 970 EVO 250GB            | 2         | 1.21%   |
| Kingston SA400S37120G 120GB SSD      | 2         | 1.21%   |
| Intel SSD 660P Series 1024GB         | 2         | 1.21%   |
| HGST HTS725050A7E630 500GB           | 2         | 1.21%   |
| Crucial CT500MX500SSD1 500GB         | 2         | 1.21%   |
| ZHITAI SC001 Active 1TB SSD          | 1         | 0.61%   |
| ZHITAI PC005 Active 512GB            | 1         | 0.61%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1         | 0.61%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1         | 0.61%   |
| WDC WDS100T2B0B-00YS70 1TB SSD       | 1         | 0.61%   |
| WDC WD5000AAKX-22ERMA0 500GB         | 1         | 0.61%   |
| WDC WD5000AAKS-007AA0 500GB          | 1         | 0.61%   |
| WDC WD5000AADS-00S9B0 500GB          | 1         | 0.61%   |
| WDC WD40EZRX-00SPEB0 4TB             | 1         | 0.61%   |
| WDC WD40EJRX-89T1XY0 4TB             | 1         | 0.61%   |
| WDC WD400BD-60LTA0 40GB              | 1         | 0.61%   |
| WDC WD3200AAJS-65B4A0 320GB          | 1         | 0.61%   |
| WDC WD30EZRX-00SPEB0 3TB             | 1         | 0.61%   |
| WDC WD30EZRX-00MMMB0 3TB             | 1         | 0.61%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 1         | 0.61%   |
| WDC WD20EZRX-00D8PB0 2TB             | 1         | 0.61%   |
| WDC WD20EARX-00PASB0 2TB             | 1         | 0.61%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.61%   |
| WDC WD10JPVT-08A1YT2 1TB             | 1         | 0.61%   |
| WDC WD10EZEX-00RKKA0 1TB             | 1         | 0.61%   |
| WDC WD10EZEX-00MFCA0 1TB             | 1         | 0.61%   |
| WDC WD Green 2.5 240GB SSD           | 1         | 0.61%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB   | 1         | 0.61%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB | 1         | 0.61%   |
| Unknown MMC Card  512GB              | 1         | 0.61%   |
| Transcend TS480GSSD220S 480GB        | 1         | 0.61%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 30     | 34.43%  |
| WDC                 | 17        | 32     | 27.87%  |
| Toshiba             | 10        | 17     | 16.39%  |
| Hitachi             | 5         | 8      | 8.2%    |
| HGST                | 4         | 4      | 6.56%   |
| Samsung Electronics | 1         | 1      | 1.64%   |
| Maxtor              | 1         | 1      | 1.64%   |
| JMicron Technology  | 1         | 1      | 1.64%   |
| External            | 1         | 1      | 1.64%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 10        | 12     | 21.74%  |
| Samsung Electronics | 9         | 13     | 19.57%  |
| WDC                 | 4         | 6      | 8.7%    |
| Crucial             | 4         | 5      | 8.7%    |
| Transcend           | 2         | 2      | 4.35%   |
| SanDisk             | 2         | 2      | 4.35%   |
| ZHITAI              | 1         | 1      | 2.17%   |
| Toshiba             | 1         | 3      | 2.17%   |
| SK hynix            | 1         | 1      | 2.17%   |
| PNY                 | 1         | 1      | 2.17%   |
| Plextor             | 1         | 1      | 2.17%   |
| Patriot             | 1         | 1      | 2.17%   |
| Lexar               | 1         | 1      | 2.17%   |
| Intenso             | 1         | 1      | 2.17%   |
| Intel               | 1         | 2      | 2.17%   |
| Hewlett-Packard     | 1         | 1      | 2.17%   |
| GOODRAM             | 1         | 1      | 2.17%   |
| Gigabyte Technology | 1         | 1      | 2.17%   |
| DUEX                | 1         | 1      | 2.17%   |
| China               | 1         | 1      | 2.17%   |
| Apple               | 1         | 1      | 2.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 43        | 95     | 34.96%  |
| SSD  | 42        | 58     | 34.15%  |
| NVMe | 37        | 46     | 30.08%  |
| MMC  | 1         | 2      | 0.81%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 60        | 147    | 57.69%  |
| NVMe | 37        | 46     | 35.58%  |
| SAS  | 6         | 6      | 5.77%   |
| MMC  | 1         | 2      | 0.96%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 48        | 63     | 48%     |
| 0.51-1.0   | 24        | 43     | 24%     |
| 1.01-2.0   | 11        | 14     | 11%     |
| 3.01-4.0   | 8         | 15     | 8%      |
| 4.01-10.0  | 5         | 7      | 5%      |
| 2.01-3.0   | 4         | 11     | 4%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 22        | 24.44%  |
| 501-1000       | 19        | 21.11%  |
| 251-500        | 15        | 16.67%  |
| Unknown        | 8         | 8.89%   |
| 1001-2000      | 7         | 7.78%   |
| 1-20           | 7         | 7.78%   |
| 2001-3000      | 5         | 5.56%   |
| More than 3000 | 3         | 3.33%   |
| 21-50          | 2         | 2.22%   |
| 51-100         | 2         | 2.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 22        | 24.44%  |
| 1-20           | 17        | 18.89%  |
| 21-50          | 13        | 14.44%  |
| 251-500        | 10        | 11.11%  |
| 501-1000       | 8         | 8.89%   |
| Unknown        | 8         | 8.89%   |
| 51-100         | 6         | 6.67%   |
| 1001-2000      | 5         | 5.56%   |
| More than 3000 | 1         | 1.11%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1         | 1      | 5.26%   |
| WDC WD5000AAKX-22ERMA0 500GB          | 1         | 1      | 5.26%   |
| WDC WD3200AAJS-65B4A0 320GB           | 1         | 1      | 5.26%   |
| WDC WD30EZRX-00MMMB0 3TB              | 1         | 1      | 5.26%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1         | 2      | 5.26%   |
| WDC WD20EARX-00PASB0 2TB              | 1         | 1      | 5.26%   |
| Seagate ST380011A 80GB                | 1         | 1      | 5.26%   |
| Seagate ST3500630AS 500GB             | 1         | 1      | 5.26%   |
| Seagate ST3000VX006-1HH166 3TB        | 1         | 1      | 5.26%   |
| Seagate ST2000DL003-9VT166 2TB        | 1         | 1      | 5.26%   |
| Seagate ST1000DM003-1ER162 1TB        | 1         | 2      | 5.26%   |
| Samsung Electronics SSD 970 EVO 500GB | 1         | 1      | 5.26%   |
| Samsung Electronics SSD 870 EVO 1TB   | 1         | 1      | 5.26%   |
| Plextor PX-128M6S 128GB SSD           | 1         | 1      | 5.26%   |
| Hitachi HUA723030ALA640 3TB           | 1         | 1      | 5.26%   |
| Hitachi HDS721016CLA382 160GB         | 1         | 1      | 5.26%   |
| HGST HTS725050A7E630 500GB            | 1         | 1      | 5.26%   |
| HGST HTS545050A7E380 500GB            | 1         | 1      | 5.26%   |
| DUEX DX300256A5xnEMLC 256GB SSD       | 1         | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 7      | 29.41%  |
| Seagate             | 4         | 6      | 23.53%  |
| Samsung Electronics | 2         | 2      | 11.76%  |
| Hitachi             | 2         | 2      | 11.76%  |
| HGST                | 2         | 2      | 11.76%  |
| Plextor             | 1         | 1      | 5.88%   |
| DUEX                | 1         | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 6      | 33.33%  |
| Seagate | 4         | 6      | 33.33%  |
| Hitachi | 2         | 2      | 16.67%  |
| HGST    | 2         | 2      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 16     | 66.67%  |
| SSD  | 4         | 4      | 26.67%  |
| NVMe | 1         | 1      | 6.67%   |

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
| Works    | 68        | 132    | 66.02%  |
| Detected | 20        | 48     | 19.42%  |
| Malfunc  | 15        | 21     | 14.56%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 45        | 38.79%  |
| AMD                          | 23        | 19.83%  |
| Samsung Electronics          | 15        | 12.93%  |
| Nvidia                       | 4         | 3.45%   |
| SK hynix                     | 3         | 2.59%   |
| SanDisk                      | 3         | 2.59%   |
| Marvell Technology Group     | 3         | 2.59%   |
| KIOXIA                       | 3         | 2.59%   |
| Micron/Crucial Technology    | 2         | 1.72%   |
| Micron Technology            | 2         | 1.72%   |
| JMicron Technology           | 2         | 1.72%   |
| ASMedia Technology           | 2         | 1.72%   |
| Yangtze Memory Technologies  | 1         | 0.86%   |
| Toshiba America Info Systems | 1         | 0.86%   |
| Silicon Motion               | 1         | 0.86%   |
| Realtek Semiconductor        | 1         | 0.86%   |
| Phison Electronics           | 1         | 0.86%   |
| LSI Logic / Symbios Logic    | 1         | 0.86%   |
| Broadcom / LSI               | 1         | 0.86%   |
| Biwin Storage Technology     | 1         | 0.86%   |
| Adaptec                      | 1         | 0.86%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 14        | 9.72%   |
| AMD 400 Series Chipset SATA Controller                                           | 7         | 4.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 6         | 4.17%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 5         | 3.47%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 4         | 2.78%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 2.78%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 2.08%   |
| Nvidia MCP61 SATA Controller                                                     | 3         | 2.08%   |
| Nvidia MCP61 IDE                                                                 | 3         | 2.08%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 3         | 2.08%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 2.08%   |
| Intel SSD 660P Series                                                            | 3         | 2.08%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 3         | 2.08%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 3         | 2.08%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 2.08%   |
| SK hynix BC511 NVMe SSD                                                          | 2         | 1.39%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 1.39%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 2         | 1.39%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 2         | 1.39%   |
| JMicron JMB58x AHCI SATA controller                                              | 2         | 1.39%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.39%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 2         | 1.39%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 1.39%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 1.39%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 1.39%   |
| Intel 631xESB/632xESB IDE Controller                                             | 2         | 1.39%   |
| Intel 4 Series Chipset PT IDER Controller                                        | 2         | 1.39%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 2         | 1.39%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 1.39%   |
| AMD 500 Series Chipset SATA Controller                                           | 2         | 1.39%   |
| Yangtze Memory ZHITAI PC005 NVMe SSD                                             | 1         | 0.69%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 1         | 0.69%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 1         | 0.69%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 1         | 0.69%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 0.69%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 0.69%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                            | 1         | 0.69%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                       | 1         | 0.69%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                | 1         | 0.69%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 53        | 44.54%  |
| NVMe | 37        | 31.09%  |
| IDE  | 16        | 13.45%  |
| RAID | 10        | 8.4%    |
| SCSI | 3         | 2.52%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 58        | 67.44%  |
| AMD    | 28        | 32.56%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 4         | 4.6%    |
| Intel 12th Gen Core i7-12700H           | 3         | 3.45%   |
| Intel Core i7-5820K CPU @ 3.30GHz       | 2         | 2.3%    |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz    | 2         | 2.3%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 2         | 2.3%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 2.3%    |
| AMD Ryzen 9 5950X 16-Core Processor     | 2         | 2.3%    |
| AMD Ryzen 5 3600 6-Core Processor       | 2         | 2.3%    |
| AMD Athlon II X2 250 Processor          | 2         | 2.3%    |
| Intel Xeon CPU X5680 @ 3.33GHz          | 1         | 1.15%   |
| Intel Xeon CPU X5355 @ 2.66GHz          | 1         | 1.15%   |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz     | 1         | 1.15%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz     | 1         | 1.15%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz     | 1         | 1.15%   |
| Intel Xeon CPU 5160 @ 3.00GHz           | 1         | 1.15%   |
| Intel Pentium Silver N6000 @ 1.10GHz    | 1         | 1.15%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz  | 1         | 1.15%   |
| Intel Pentium CPU GOLD 6500Y @ 1.10GHz  | 1         | 1.15%   |
| Intel Pentium CPU G3250 @ 3.20GHz       | 1         | 1.15%   |
| Intel Pentium CPU 2020M @ 2.40GHz       | 1         | 1.15%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 1         | 1.15%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 1.15%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 1         | 1.15%   |
| Intel Core i7-7700 CPU @ 3.60GHz        | 1         | 1.15%   |
| Intel Core i7-7600U CPU @ 2.80GHz       | 1         | 1.15%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 1         | 1.15%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 1         | 1.15%   |
| Intel Core i7-3840QM CPU @ 2.80GHz      | 1         | 1.15%   |
| Intel Core i7-3720QM CPU @ 2.60GHz      | 1         | 1.15%   |
| Intel Core i7-10870H CPU @ 2.20GHz      | 1         | 1.15%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 1         | 1.15%   |
| Intel Core i5-8600K CPU @ 3.60GHz       | 1         | 1.15%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 1         | 1.15%   |
| Intel Core i5-4590 CPU @ 3.30GHz        | 1         | 1.15%   |
| Intel Core i5-4310M CPU @ 2.70GHz       | 1         | 1.15%   |
| Intel Core i5-3360M CPU @ 2.80GHz       | 1         | 1.15%   |
| Intel Core i5-3330 CPU @ 3.00GHz        | 1         | 1.15%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 1         | 1.15%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 1         | 1.15%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 1         | 1.15%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Other                | 13        | 14.94%  |
| Intel Core i7        | 13        | 14.94%  |
| Intel Core i5        | 13        | 14.94%  |
| AMD Ryzen 5          | 8         | 9.2%    |
| Intel Xeon           | 6         | 6.9%    |
| Intel Core 2 Duo     | 5         | 5.75%   |
| AMD Ryzen 9          | 4         | 4.6%    |
| AMD Ryzen 7          | 4         | 4.6%    |
| Intel Pentium        | 3         | 3.45%   |
| AMD FX               | 3         | 3.45%   |
| Intel Core i3        | 2         | 2.3%    |
| Intel Celeron        | 2         | 2.3%    |
| AMD Athlon II X2     | 2         | 2.3%    |
| Intel Pentium Silver | 1         | 1.15%   |
| Intel Pentium Dual   | 1         | 1.15%   |
| Intel Atom           | 1         | 1.15%   |
| AMD Ryzen 7 PRO      | 1         | 1.15%   |
| AMD Ryzen 3          | 1         | 1.15%   |
| AMD EPYC             | 1         | 1.15%   |
| AMD E1               | 1         | 1.15%   |
| AMD Athlon           | 1         | 1.15%   |
| AMD A8               | 1         | 1.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 27        | 31.03%  |
| 2      | 26        | 29.89%  |
| 8      | 15        | 17.24%  |
| 6      | 8         | 9.2%    |
| 14     | 4         | 4.6%    |
| 16     | 2         | 2.3%    |
| 12     | 2         | 2.3%    |
| 10     | 2         | 2.3%    |
| 3      | 1         | 1.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 83        | 96.51%  |
| 2      | 3         | 3.49%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 62        | 72.09%  |
| 1      | 24        | 27.91%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 86        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 18        | 20.93%  |
| 0x306a9    | 7         | 8.14%   |
| 0x806d1    | 4         | 4.65%   |
| 0x906a3    | 3         | 3.49%   |
| 0x806c1    | 3         | 3.49%   |
| 0x306f2    | 3         | 3.49%   |
| 0x08701021 | 3         | 3.49%   |
| 0x08108109 | 3         | 3.49%   |
| 0x406c4    | 2         | 2.33%   |
| 0x306c3    | 2         | 2.33%   |
| 0x1067a    | 2         | 2.33%   |
| 0x0a50000c | 2         | 2.33%   |
| 0x0a201016 | 2         | 2.33%   |
| 0x08600106 | 2         | 2.33%   |
| 0xa0671    | 1         | 1.16%   |
| 0xa0653    | 1         | 1.16%   |
| 0xa0652    | 1         | 1.16%   |
| 0x906ea    | 1         | 1.16%   |
| 0x906e9    | 1         | 1.16%   |
| 0x906c0    | 1         | 1.16%   |
| 0x906a4    | 1         | 1.16%   |
| 0x806ec    | 1         | 1.16%   |
| 0x806ea    | 1         | 1.16%   |
| 0x6fd      | 1         | 1.16%   |
| 0x6fb      | 1         | 1.16%   |
| 0x6fa      | 1         | 1.16%   |
| 0x506e3    | 1         | 1.16%   |
| 0x406e3    | 1         | 1.16%   |
| 0x306e4    | 1         | 1.16%   |
| 0x306d4    | 1         | 1.16%   |
| 0x206c2    | 1         | 1.16%   |
| 0x20655    | 1         | 1.16%   |
| 0x106c2    | 1         | 1.16%   |
| 0x0a20120a | 1         | 1.16%   |
| 0x08900201 | 1         | 1.16%   |
| 0x08608102 | 1         | 1.16%   |
| 0x0830104d | 1         | 1.16%   |
| 0x0810100b | 1         | 1.16%   |
| 0x08001126 | 1         | 1.16%   |
| 0x07030105 | 1         | 1.16%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 9         | 10.47%  |
| Zen 2            | 8         | 9.3%    |
| IvyBridge        | 8         | 9.3%    |
| Haswell          | 6         | 6.98%   |
| Zen 3            | 5         | 5.81%   |
| Icelake          | 5         | 5.81%   |
| Core             | 5         | 5.81%   |
| Zen+             | 4         | 4.65%   |
| Westmere         | 4         | 4.65%   |
| Alderlake Hybrid | 4         | 4.65%   |
| TigerLake        | 3         | 3.49%   |
| Skylake          | 3         | 3.49%   |
| Penryn           | 3         | 3.49%   |
| Zen              | 2         | 2.33%   |
| Silvermont       | 2         | 2.33%   |
| Piledriver       | 2         | 2.33%   |
| K10              | 2         | 2.33%   |
| CometLake        | 2         | 2.33%   |
| Unknown          | 2         | 2.33%   |
| Tremont          | 1         | 1.16%   |
| SandyBridge      | 1         | 1.16%   |
| Puma             | 1         | 1.16%   |
| Jaguar           | 1         | 1.16%   |
| Bulldozer        | 1         | 1.16%   |
| Broadwell        | 1         | 1.16%   |
| Bonnell          | 1         | 1.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 38        | 38%     |
| Nvidia                     | 35        | 35%     |
| AMD                        | 26        | 26%     |
| Matrox Electronics Systems | 1         | 1%      |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 4         | 3.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 3.92%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 3         | 2.94%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 2.94%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 2.94%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 3         | 2.94%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 2.94%   |
| AMD Renoir                                                                               | 3         | 2.94%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 3         | 2.94%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 2.94%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 1.96%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 1.96%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2         | 1.96%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2         | 1.96%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2         | 1.96%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 2         | 1.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 1.96%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 1.96%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.96%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.96%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 1.96%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 2         | 1.96%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 1.96%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.98%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 1         | 0.98%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.98%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.98%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.98%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 0.98%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.98%   |
| Nvidia GF108GL [Quadro 600]                                                              | 1         | 0.98%   |
| Nvidia GA107M [GeForce RTX 2050]                                                         | 1         | 0.98%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 0.98%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 1         | 0.98%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                                       | 1         | 0.98%   |
| Nvidia G96C [GeForce 9400 GT]                                                            | 1         | 0.98%   |
| Nvidia G84 [GeForce 8600 GT]                                                             | 1         | 0.98%   |
| Nvidia G71GL [Quadro FX 1500]                                                            | 1         | 0.98%   |
| Nvidia C79 [ION]                                                                         | 1         | 0.98%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 26        | 30.23%  |
| 1 x AMD        | 24        | 27.91%  |
| 1 x Nvidia     | 21        | 24.42%  |
| Intel + Nvidia | 12        | 13.95%  |
| 2 x AMD        | 1         | 1.16%   |
| 1 x Matrox     | 1         | 1.16%   |
| AMD + Nvidia   | 1         | 1.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 68        | 79.07%  |
| Proprietary | 15        | 17.44%  |
| Unknown     | 3         | 3.49%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 42        | 48.84%  |
| 0.01-0.5   | 10        | 11.63%  |
| 0.51-1.0   | 9         | 10.47%  |
| 7.01-8.0   | 7         | 8.14%   |
| 1.01-2.0   | 6         | 6.98%   |
| 8.01-16.0  | 4         | 4.65%   |
| 5.01-6.0   | 3         | 3.49%   |
| 3.01-4.0   | 3         | 3.49%   |
| 2.01-3.0   | 1         | 1.16%   |
| 16.01-24.0 | 1         | 1.16%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 11        | 12.22%  |
| BOE                     | 11        | 12.22%  |
| Hewlett-Packard         | 8         | 8.89%   |
| LG Display              | 7         | 7.78%   |
| Dell                    | 7         | 7.78%   |
| AU Optronics            | 7         | 7.78%   |
| Chimei Innolux          | 6         | 6.67%   |
| Goldstar                | 4         | 4.44%   |
| BenQ                    | 4         | 4.44%   |
| Lenovo                  | 3         | 3.33%   |
| Ancor Communications    | 3         | 3.33%   |
| Sharp                   | 2         | 2.22%   |
| AOC                     | 2         | 2.22%   |
| Acer                    | 2         | 2.22%   |
| Wacom                   | 1         | 1.11%   |
| Valve                   | 1         | 1.11%   |
| UGD                     | 1         | 1.11%   |
| Sony                    | 1         | 1.11%   |
| PANDA                   | 1         | 1.11%   |
| IOD                     | 1         | 1.11%   |
| Iiyama                  | 1         | 1.11%   |
| GDH                     | 1         | 1.11%   |
| CTC                     | 1         | 1.11%   |
| Chi Mei Optoelectronics | 1         | 1.11%   |
| ASUSTek Computer        | 1         | 1.11%   |
| Apple                   | 1         | 1.11%   |
| Unknown                 | 1         | 1.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC416E 2880x1620 344x194mm 15.5-inch | 2         | 2.17%   |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch             | 2         | 2.17%   |
| Goldstar ULTRAGEAR GSM7765 2560x1440 697x392mm 31.5-inch              | 2         | 2.17%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 2         | 2.17%   |
| Wacom Cintiq 22HDT WAC1037 1920x1080 476x268mm 21.5-inch              | 1         | 1.09%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 1.09%   |
| UGD LCD Monitor UGD1302 1920x1080 290x160mm 13.0-inch                 | 1         | 1.09%   |
| Sony TV SNY8102 1360x768                                              | 1         | 1.09%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 382x215mm 17.3-inch               | 1         | 1.09%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 1.09%   |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch   | 1         | 1.09%   |
| Samsung Electronics SyncMaster SAM03F2 1680x1050                      | 1         | 1.09%   |
| Samsung Electronics SyncMaster SAM03F0 1680x1050 433x271mm 20.1-inch  | 1         | 1.09%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 376x301mm 19.0-inch  | 1         | 1.09%   |
| Samsung Electronics SyncMaster SAM01AD 1600x1200 408x306mm 20.1-inch  | 1         | 1.09%   |
| Samsung Electronics SMS27A650 SAM082D 1920x1080 598x336mm 27.0-inch   | 1         | 1.09%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch    | 1         | 1.09%   |
| Samsung Electronics SM2333T SAM0736 1920x1080 477x268mm 21.5-inch     | 1         | 1.09%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch     | 1         | 1.09%   |
| Samsung Electronics LCD Monitor U28D590 3840x2160                     | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 1.09%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 1.09%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch          | 1         | 1.09%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch          | 1         | 1.09%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 1.09%   |
| LG Display LCD Monitor LGD0353 1366x768 345x194mm 15.6-inch           | 1         | 1.09%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch          | 1         | 1.09%   |
| LG Display LCD Monitor LGD028A 1366x768 344x194mm 15.5-inch           | 1         | 1.09%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch           | 1         | 1.09%   |
| Lenovo LEN L171 LEN24C9 1280x1024 337x270mm 17.0-inch                 | 1         | 1.09%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x189mm 14.1-inch               | 1         | 1.09%   |
| Lenovo LCD Monitor LEN4031 1280x800 303x190mm 14.1-inch               | 1         | 1.09%   |
| IOD LCD-GL211X IOD151D 1920x1080 458x258mm 20.7-inch                  | 1         | 1.09%   |
| Iiyama PL2783Q IVM661F 2560x1440 597x336mm 27.0-inch                  | 1         | 1.09%   |
| Hewlett-Packard Z24i HWP309E 1920x1200 518x324mm 24.1-inch            | 1         | 1.09%   |
| Hewlett-Packard x23LED HWP2912 1920x1080 509x286mm 23.0-inch          | 1         | 1.09%   |
| Hewlett-Packard P223 HPN3392 1920x1080 477x268mm 21.5-inch            | 1         | 1.09%   |
| Hewlett-Packard ALL-in-One HPN4021 1920x1080 476x268mm 21.5-inch      | 1         | 1.09%   |
| Hewlett-Packard 27m HPN3579 1920x1080 598x336mm 27.0-inch             | 1         | 1.09%   |
| Hewlett-Packard 22fw HPN3541 1920x1080 476x268mm 21.5-inch            | 1         | 1.09%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 39        | 44.32%  |
| 1366x768 (WXGA)    | 12        | 13.64%  |
| 2560x1440 (QHD)    | 5         | 5.68%   |
| 3840x2160 (4K)     | 4         | 4.55%   |
| 1680x1050 (WSXGA+) | 4         | 4.55%   |
| 1280x1024 (SXGA)   | 4         | 4.55%   |
| 2880x1620          | 2         | 2.27%   |
| 1920x1200 (WUXGA)  | 2         | 2.27%   |
| 1600x900 (HD+)     | 2         | 2.27%   |
| 1440x900 (WXGA+)   | 2         | 2.27%   |
| 1360x768           | 2         | 2.27%   |
| 1280x800 (WXGA)    | 2         | 2.27%   |
| 800x1280           | 1         | 1.14%   |
| 3440x1440          | 1         | 1.14%   |
| 3200x1080          | 1         | 1.14%   |
| 2256x1504          | 1         | 1.14%   |
| 1920x1280          | 1         | 1.14%   |
| 1600x1200          | 1         | 1.14%   |
| 1024x768 (XGA)     | 1         | 1.14%   |
| Unknown            | 1         | 1.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 18        | 20%     |
| 27      | 9         | 10%     |
| 13      | 8         | 8.89%   |
| 24      | 7         | 7.78%   |
| 17      | 7         | 7.78%   |
| 14      | 7         | 7.78%   |
| 21      | 5         | 5.56%   |
| 23      | 3         | 3.33%   |
| 22      | 3         | 3.33%   |
| 20      | 3         | 3.33%   |
| 19      | 3         | 3.33%   |
| 18      | 3         | 3.33%   |
| Unknown | 3         | 3.33%   |
| 31      | 2         | 2.22%   |
| 16      | 2         | 2.22%   |
| 72      | 1         | 1.11%   |
| 52      | 1         | 1.11%   |
| 34      | 1         | 1.11%   |
| 12      | 1         | 1.11%   |
| 11      | 1         | 1.11%   |
| 10      | 1         | 1.11%   |
| 7       | 1         | 1.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 33        | 37.08%  |
| 501-600     | 17        | 19.1%   |
| 401-500     | 15        | 16.85%  |
| 351-400     | 9         | 10.11%  |
| 201-300     | 5         | 5.62%   |
| 601-700     | 3         | 3.37%   |
| Unknown     | 3         | 3.37%   |
| 701-800     | 1         | 1.12%   |
| 1501-2000   | 1         | 1.12%   |
| 1001-1500   | 1         | 1.12%   |
| 1-100       | 1         | 1.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 57        | 71.25%  |
| 16/10   | 11        | 13.75%  |
| 5/4     | 4         | 5%      |
| 4/3     | 2         | 2.5%    |
| 3/2     | 2         | 2.5%    |
| Unknown | 2         | 2.5%    |
| 21/9    | 1         | 1.25%   |
| 0.67    | 1         | 1.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 20        | 22.47%  |
| 81-90          | 14        | 15.73%  |
| 201-250        | 12        | 13.48%  |
| 301-350        | 9         | 10.11%  |
| 151-200        | 9         | 10.11%  |
| 121-130        | 5         | 5.62%   |
| 141-150        | 4         | 4.49%   |
| 351-500        | 3         | 3.37%   |
| 251-300        | 3         | 3.37%   |
| Unknown        | 3         | 3.37%   |
| More than 1000 | 2         | 2.25%   |
| 51-60          | 2         | 2.25%   |
| 71-80          | 1         | 1.12%   |
| 61-70          | 1         | 1.12%   |
| 1-40           | 1         | 1.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 32        | 36.36%  |
| 121-160       | 24        | 27.27%  |
| 101-120       | 20        | 22.73%  |
| 161-240       | 6         | 6.82%   |
| Unknown       | 3         | 3.41%   |
| 1-50          | 2         | 2.27%   |
| More than 240 | 1         | 1.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 69        | 80.23%  |
| 2     | 9         | 10.47%  |
| 0     | 6         | 6.98%   |
| 4     | 1         | 1.16%   |
| 3     | 1         | 1.16%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 48        | 37.21%  |
| Intel                    | 45        | 34.88%  |
| Broadcom                 | 6         | 4.65%   |
| Qualcomm Atheros         | 5         | 3.88%   |
| MediaTek                 | 4         | 3.1%    |
| Broadcom Limited         | 4         | 3.1%    |
| Ralink Technology        | 3         | 2.33%   |
| Nvidia                   | 3         | 2.33%   |
| ASIX Electronics         | 3         | 2.33%   |
| TP-Link                  | 1         | 0.78%   |
| Sitecom Europe           | 1         | 0.78%   |
| Ralink                   | 1         | 0.78%   |
| Qualcomm                 | 1         | 0.78%   |
| Marvell Technology Group | 1         | 0.78%   |
| Huawei Technologies      | 1         | 0.78%   |
| Hewlett-Packard          | 1         | 0.78%   |
| Dell                     | 1         | 0.78%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32        | 21.05%  |
| Intel Wi-Fi 6 AX200                                               | 6         | 3.95%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5         | 3.29%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 2.63%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 2.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 2.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.97%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.97%   |
| Ralink MT7601U Wireless Adapter                                   | 3         | 1.97%   |
| Intel Wireless 8265 / 8275                                        | 3         | 1.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 1.97%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 2         | 1.32%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 1.32%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 1.32%   |
| Nvidia MCP61 Ethernet                                             | 2         | 1.32%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 2         | 1.32%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.32%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 1.32%   |
| Intel Ethernet Controller I225-V                                  | 2         | 1.32%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.32%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.32%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 1.32%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 2         | 1.32%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                           | 2         | 1.32%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.32%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 0.66%   |
| Sitecom Europe WL-113 rev 2 Wireless Network USB Adapter          | 1         | 0.66%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.66%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.66%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.66%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.66%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.66%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.66%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 1         | 0.66%   |
| Qualcomm Redmi Note 8                                             | 1         | 0.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 0.66%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1         | 0.66%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 0.66%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1         | 0.66%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.66%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 33        | 51.56%  |
| Realtek Semiconductor | 11        | 17.19%  |
| Qualcomm Atheros      | 4         | 6.25%   |
| MediaTek              | 4         | 6.25%   |
| Ralink Technology     | 3         | 4.69%   |
| Broadcom Limited      | 3         | 4.69%   |
| Broadcom              | 2         | 3.13%   |
| TP-Link               | 1         | 1.56%   |
| Sitecom Europe        | 1         | 1.56%   |
| Ralink                | 1         | 1.56%   |
| Dell                  | 1         | 1.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                   | 6         | 9.23%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                | 5         | 7.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter              | 4         | 6.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter              | 3         | 4.62%   |
| Ralink MT7601U Wireless Adapter                                       | 3         | 4.62%   |
| Intel Wireless 8265 / 8275                                            | 3         | 4.62%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                          | 3         | 4.62%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                               | 2         | 3.08%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter         | 2         | 3.08%   |
| Intel Wi-Fi 6 AX201                                                   | 2         | 3.08%   |
| Intel Tiger Lake PCH CNVi WiFi                                        | 2         | 3.08%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                               | 2         | 3.08%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                           | 1         | 1.54%   |
| Sitecom Europe WL-113 rev 2 Wireless Network USB Adapter              | 1         | 1.54%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                    | 1         | 1.54%   |
| Realtek RTL8723DE Wireless Network Adapter                            | 1         | 1.54%   |
| Realtek RTL8191SEvB Wireless LAN Controller                           | 1         | 1.54%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                             | 1         | 1.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                      | 1         | 1.54%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                      | 1         | 1.54%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)        | 1         | 1.54%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                      | 1         | 1.54%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                               | 1         | 1.54%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter         | 1         | 1.54%   |
| Intel Wireless-AC 9260                                                | 1         | 1.54%   |
| Intel Wireless 8260                                                   | 1         | 1.54%   |
| Intel Wireless 7260                                                   | 1         | 1.54%   |
| Intel Wireless 3165                                                   | 1         | 1.54%   |
| Intel Wi-Fi 6 AX201 160MHz                                            | 1         | 1.54%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection         | 1         | 1.54%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                      | 1         | 1.54%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                       | 1         | 1.54%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                     | 1         | 1.54%   |
| Intel Comet Lake PCH CNVi WiFi                                        | 1         | 1.54%   |
| Intel Centrino Ultimate-N 6300                                        | 1         | 1.54%   |
| Intel Alder Lake-P PCH CNVi WiFi                                      | 1         | 1.54%   |
| Dell Wireless 1450 Dual-band (802.11a/b/g) Adapter [Intersil ISL3887] | 1         | 1.54%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                               | 1         | 1.54%   |
| Broadcom BCM4331 802.11a/b/g/n                                        | 1         | 1.54%   |
| Broadcom BCM4321 802.11a/b/g/n                                        | 1         | 1.54%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 43        | 51.19%  |
| Intel                    | 24        | 28.57%  |
| Broadcom                 | 5         | 5.95%   |
| Nvidia                   | 3         | 3.57%   |
| ASIX Electronics         | 3         | 3.57%   |
| Qualcomm Atheros         | 2         | 2.38%   |
| Qualcomm                 | 1         | 1.19%   |
| Marvell Technology Group | 1         | 1.19%   |
| Huawei Technologies      | 1         | 1.19%   |
| Broadcom Limited         | 1         | 1.19%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32        | 37.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 4.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 4.65%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 3.49%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 2.33%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 2.33%   |
| Nvidia MCP61 Ethernet                                             | 2         | 2.33%   |
| Intel Ethernet Controller I225-V                                  | 2         | 2.33%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.33%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 2.33%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 2.33%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 2         | 2.33%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 2.33%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 1.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.16%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.16%   |
| Qualcomm Redmi Note 8                                             | 1         | 1.16%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.16%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.16%   |
| Intel I350 Gigabit Network Connection                             | 1         | 1.16%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.16%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.16%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.16%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 1.16%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.16%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.16%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 1.16%   |
| Intel Ethernet Connection (12) I219-V                             | 1         | 1.16%   |
| Intel 82576 Gigabit Network Connection                            | 1         | 1.16%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.16%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.16%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1         | 1.16%   |
| Huawei E353/E3131                                                 | 1         | 1.16%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.16%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1         | 1.16%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 1         | 1.16%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 1         | 1.16%   |
| ASIX AX88772A Fast Ethernet                                       | 1         | 1.16%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 77        | 54.61%  |
| WiFi     | 63        | 44.68%  |
| Modem    | 1         | 0.71%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 48        | 52.17%  |
| Ethernet | 44        | 47.83%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 43        | 49.43%  |
| 1     | 39        | 44.83%  |
| 4     | 2         | 2.3%    |
| 3     | 2         | 2.3%    |
| 5     | 1         | 1.15%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 73        | 83.91%  |
| Yes  | 14        | 16.09%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 28        | 50%     |
| Realtek Semiconductor    | 7         | 12.5%   |
| Cambridge Silicon Radio  | 5         | 8.93%   |
| Broadcom                 | 5         | 8.93%   |
| IMC Networks             | 4         | 7.14%   |
| MediaTek                 | 2         | 3.57%   |
| Apple                    | 2         | 3.57%   |
| TP-Link                  | 1         | 1.79%   |
| Micro Star International | 1         | 1.79%   |
| Foxconn / Hon Hai        | 1         | 1.79%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 7         | 12.5%   |
| Intel AX201 Bluetooth                               | 6         | 10.71%  |
| Intel AX200 Bluetooth                               | 6         | 10.71%  |
| Intel AX210 Bluetooth                               | 5         | 8.93%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5         | 8.93%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 7.14%   |
| Realtek Bluetooth Radio                             | 3         | 5.36%   |
| IMC Networks Wireless_Device                        | 3         | 5.36%   |
| MediaTek Wireless_Device                            | 2         | 3.57%   |
| TP-Link UB500 Adapter                               | 1         | 1.79%   |
| Micro Star International Bluetooth Dongle           | 1         | 1.79%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.79%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.79%   |
| Intel Bluetooth Device                              | 1         | 1.79%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 1.79%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.79%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 1.79%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.79%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.79%   |
| Broadcom BCM20702A0                                 | 1         | 1.79%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.79%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 1.79%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.79%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 1         | 1.79%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 52        | 41.94%  |
| Nvidia                 | 30        | 24.19%  |
| AMD                    | 30        | 24.19%  |
| Creative Labs          | 4         | 3.23%   |
| C-Media Electronics    | 2         | 1.61%   |
| Texas Instruments      | 1         | 0.81%   |
| RME                    | 1         | 0.81%   |
| Kingston Technology    | 1         | 0.81%   |
| Holtek Semiconductor   | 1         | 0.81%   |
| Generalplus Technology | 1         | 0.81%   |
| ASUSTek Computer       | 1         | 0.81%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 10        | 6.85%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 7         | 4.79%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 4.11%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 3.42%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 3.42%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 3.42%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 3.42%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 2.74%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 2.74%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 4         | 2.74%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 2.05%   |
| Nvidia MCP61 High Definition Audio                                                                | 3         | 2.05%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 2.05%   |
| Nvidia Audio device                                                                               | 3         | 2.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 2.05%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 2.05%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 2.05%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 2.05%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 3         | 2.05%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 3         | 2.05%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 1.37%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 1.37%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 2         | 1.37%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.37%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.37%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.37%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2         | 1.37%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 1.37%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus]   | 2         | 1.37%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 1.37%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.37%   |
| AMD Navi 10 HDMI Audio                                                                            | 2         | 1.37%   |
| AMD FCH Azalia Controller                                                                         | 2         | 1.37%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.68%   |
| RME ADI-2 DAC (58825307)                                                                          | 1         | 0.68%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.68%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.68%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.68%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Kingston            | 16        | 17.78%  |
| SK hynix            | 15        | 16.67%  |
| Samsung Electronics | 15        | 16.67%  |
| Corsair             | 8         | 8.89%   |
| Crucial             | 6         | 6.67%   |
| Micron Technology   | 5         | 5.56%   |
| Unknown             | 3         | 3.33%   |
| G.Skill             | 3         | 3.33%   |
| Team                | 2         | 2.22%   |
| Goodram             | 2         | 2.22%   |
| AMD                 | 2         | 2.22%   |
| A-DATA Technology   | 2         | 2.22%   |
| Unknown             | 2         | 2.22%   |
| Transcend           | 1         | 1.11%   |
| Strontium           | 1         | 1.11%   |
| Smart               | 1         | 1.11%   |
| Silicon Power       | 1         | 1.11%   |
| Patriot             | 1         | 1.11%   |
| Neo Forza           | 1         | 1.11%   |
| Nanya Technology    | 1         | 1.11%   |
| GLOWAY              | 1         | 1.11%   |
| Essencore Limited   | 1         | 1.11%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                             | 2         | 2.08%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips 6400MT/s        | 2         | 2.08%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 2.08%   |
| Unknown                                                          | 2         | 2.08%   |
| Unknown RAM Module 2GB DIMM DDR2 533MT/s                         | 1         | 1.04%   |
| Transcend RAM JM1600KLN-8GK 4096MB DIMM DDR3 1600MT/s            | 1         | 1.04%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3733MT/s               | 1         | 1.04%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s               | 1         | 1.04%   |
| Strontium RAM SRT4G86U1-P9H 4096MB DIMM DDR3 1333MT/s            | 1         | 1.04%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s              | 1         | 1.04%   |
| SK hynix RAM HYMP512F72CP8N3-Y5 1024MB FB-DIMM DDR2 667MT/s      | 1         | 1.04%   |
| SK hynix RAM HMT41GV7BMR4A-H9 16GB DIMM 1333MT/s                 | 1         | 1.04%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.04%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s             | 1         | 1.04%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.04%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 1.04%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.04%   |
| SK hynix RAM HMT31GR7BFR4A-H9 8192MB DIMM 1333MT/s               | 1         | 1.04%   |
| SK hynix RAM HMT125R7BFR8C-H9 2GB DIMM 1333MT/s                  | 1         | 1.04%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.04%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.04%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.04%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.04%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.04%   |
| SK hynix RAM HMA81GR7CJR8N-XN 8192MB DIMM DDR4 3200MT/s          | 1         | 1.04%   |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 1.04%   |
| Silicon Power RAM DCLT4GN568S V 4096MB DIMM DDR3 1600MT/s        | 1         | 1.04%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 1.04%   |
| Samsung RAM M471B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.04%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.04%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.04%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 1.04%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s            | 1         | 1.04%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.04%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 1         | 1.04%   |
| Samsung RAM M395T5663QZ4-CE66 2048MB FB-DIMM DDR2 667MT/s        | 1         | 1.04%   |
| Samsung RAM M393A2G40DB0-CPB 16GB RIMM DDR4 2133MT/s             | 1         | 1.04%   |
| Samsung RAM M393A1K43BB0-CRC 8GB DIMM DDR4 2400MT/s              | 1         | 1.04%   |
| Samsung RAM M393A1G43EB1-CRC 8GB DIMM DDR4 2400MT/s              | 1         | 1.04%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s              | 1         | 1.04%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 40        | 53.33%  |
| DDR3    | 22        | 29.33%  |
| DDR2    | 4         | 5.33%   |
| LPDDR5  | 3         | 4%      |
| SDRAM   | 2         | 2.67%   |
| LPDDR4  | 1         | 1.33%   |
| LPDDR3  | 1         | 1.33%   |
| DDR5    | 1         | 1.33%   |
| Unknown | 1         | 1.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 34        | 45.33%  |
| DIMM         | 34        | 45.33%  |
| Row Of Chips | 5         | 6.67%   |
| RIMM         | 1         | 1.33%   |
| FB-DIMM      | 1         | 1.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 35        | 41.67%  |
| 4096  | 24        | 28.57%  |
| 16384 | 13        | 15.48%  |
| 2048  | 6         | 7.14%   |
| 32768 | 4         | 4.76%   |
| 1024  | 2         | 2.38%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 18        | 21.43%  |
| 1600    | 17        | 20.24%  |
| 2667    | 7         | 8.33%   |
| 2400    | 7         | 8.33%   |
| 3600    | 4         | 4.76%   |
| 1333    | 4         | 4.76%   |
| 3800    | 3         | 3.57%   |
| 6400    | 2         | 2.38%   |
| 2133    | 2         | 2.38%   |
| 667     | 2         | 2.38%   |
| Unknown | 2         | 2.38%   |
| 65535   | 1         | 1.19%   |
| 4800    | 1         | 1.19%   |
| 4267    | 1         | 1.19%   |
| 4266    | 1         | 1.19%   |
| 3733    | 1         | 1.19%   |
| 3400    | 1         | 1.19%   |
| 2933    | 1         | 1.19%   |
| 2800    | 1         | 1.19%   |
| 2472    | 1         | 1.19%   |
| 2187    | 1         | 1.19%   |
| 1867    | 1         | 1.19%   |
| 1866    | 1         | 1.19%   |
| 1334    | 1         | 1.19%   |
| 975     | 1         | 1.19%   |
| 701     | 1         | 1.19%   |
| 533     | 1         | 1.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| QinHeng Electronics | 1         | 20%     |
| Hewlett-Packard     | 1         | 20%     |
| Dell                | 1         | 20%     |
| Canon               | 1         | 20%     |
| Brother Industries  | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                        | Computers | Percent |
|------------------------------|-----------|---------|
| QinHeng CH340S               | 1         | 20%     |
| HP OfficeJet Pro 9010 series | 1         | 20%     |
| Dell 2330d Laser Printer     | 1         | 20%     |
| Canon CanoScan LiDE 300      | 1         | 20%     |
| Brother HL-L5102DW           | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1         | 50%     |
| Canon CanoScan LIDE 25                        | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 11        | 21.57%  |
| Logitech                               | 8         | 15.69%  |
| Microdia                               | 5         | 9.8%    |
| Bison Electronics                      | 5         | 9.8%    |
| Realtek Semiconductor                  | 3         | 5.88%   |
| Luxvisions Innotech Limited            | 3         | 5.88%   |
| Syntek                                 | 2         | 3.92%   |
| Sonix Technology                       | 2         | 3.92%   |
| Samsung Electronics                    | 2         | 3.92%   |
| Quanta                                 | 2         | 3.92%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.92%   |
| Acer                                   | 2         | 3.92%   |
| Z-Star Microelectronics                | 1         | 1.96%   |
| Microsoft                              | 1         | 1.96%   |
| Lenovo                                 | 1         | 1.96%   |
| Apple                                  | 1         | 1.96%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Logitech Webcam C270                                           | 3         | 5.88%   |
| Bison HD Webcam                                                | 3         | 5.88%   |
| Sonix USB2.0 FHD UVC WebCam                                    | 2         | 3.92%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 2         | 3.92%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 2         | 3.92%   |
| Chicony Integrated Camera                                      | 2         | 3.92%   |
| Chicony HD User Facing                                         | 2         | 3.92%   |
| Acer BisonCam,NB Pro                                           | 2         | 3.92%   |
| Z-Star Vimicro USB2.0 Camera                                   | 1         | 1.96%   |
| Syntek USB2.0 Camera                                           | 1         | 1.96%   |
| Syntek Integrated Camera                                       | 1         | 1.96%   |
| Realtek Laptop Camera                                          | 1         | 1.96%   |
| Realtek Integrated Camera                                      | 1         | 1.96%   |
| Realtek EasyCamera                                             | 1         | 1.96%   |
| Quanta HP Wide Vision HD Camera                                | 1         | 1.96%   |
| Quanta HP Webcam                                               | 1         | 1.96%   |
| Microsoft LifeCam HD-3000                                      | 1         | 1.96%   |
| Microdia Laptop_Integrated_Webcam_2M                           | 1         | 1.96%   |
| Microdia Integrated_Webcam_HD                                  | 1         | 1.96%   |
| Microdia Integrated Webcam                                     | 1         | 1.96%   |
| Microdia Dell Integrated HD Webcam                             | 1         | 1.96%   |
| Microdia Camera                                                | 1         | 1.96%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 1         | 1.96%   |
| Logitech QuickCam Pro 9000                                     | 1         | 1.96%   |
| Logitech Logitech Webcam C160                                  | 1         | 1.96%   |
| Logitech HD Webcam C910                                        | 1         | 1.96%   |
| Logitech C922 Pro Stream Webcam                                | 1         | 1.96%   |
| Logitech C920 PRO HD Webcam                                    | 1         | 1.96%   |
| Lenovo Integrated Webcam [R5U877]                              | 1         | 1.96%   |
| Chicony Web Camera - FHD                                       | 1         | 1.96%   |
| Chicony Integrated Camera [ThinkPad]                           | 1         | 1.96%   |
| Chicony HP TrueVision HD Camera                                | 1         | 1.96%   |
| Chicony HP True Vision 5MP Camera                              | 1         | 1.96%   |
| Chicony HP HD Webcam [Fixed]                                   | 1         | 1.96%   |
| Chicony HP HD Camera                                           | 1         | 1.96%   |
| Chicony FJ Camera                                              | 1         | 1.96%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 1.96%   |
| Cheng Uei Precision Industry (Foxlink) HP 5M Camera            | 1         | 1.96%   |
| Bison ThinkPad Integrated Camera                               | 1         | 1.96%   |
| Bison Integrated Camera                                        | 1         | 1.96%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 5         | 41.67%  |
| Synaptics                          | 2         | 16.67%  |
| Realtek USB2.0 Finger Print Bridge | 2         | 16.67%  |
| STMicroelectronics                 | 1         | 8.33%   |
| Shenzhen Goodix Technology         | 1         | 8.33%   |
| Elan Microelectronics              | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                                 | 3         | 25%     |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 2         | 16.67%  |
| Validity Sensors VFS451 Fingerprint Reader                      | 1         | 8.33%   |
| Validity Sensors VFS300 Fingerprint Reader                      | 1         | 8.33%   |
| Synaptics UWP WBDI                                              | 1         | 8.33%   |
| STMicroelectronics Fingerprint Reader                           | 1         | 8.33%   |
| Shenzhen Goodix  FingerPrint Device                             | 1         | 8.33%   |
| Elan ELAN:ARM-M4                                                | 1         | 8.33%   |
| Unknown                                                         | 1         | 8.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 2         | 66.67%  |
| Lenovo      | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 2         | 66.67%  |
| Lenovo Integrated Smart Card Reader | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 54        | 62.07%  |
| 1     | 21        | 24.14%  |
| 2     | 8         | 9.2%    |
| 4     | 2         | 2.3%    |
| 5     | 1         | 1.15%   |
| 3     | 1         | 1.15%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 12        | 23.08%  |
| Sound                    | 8         | 15.38%  |
| Graphics card            | 7         | 13.46%  |
| Net/wireless             | 5         | 9.62%   |
| Multimedia controller    | 4         | 7.69%   |
| Unassigned class         | 3         | 5.77%   |
| Communication controller | 3         | 5.77%   |
| Chipcard                 | 3         | 5.77%   |
| Camera                   | 3         | 5.77%   |
| Storage/raid             | 1         | 1.92%   |
| Storage/ide              | 1         | 1.92%   |
| Net/ethernet             | 1         | 1.92%   |
| Bluetooth                | 1         | 1.92%   |

