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

Total: 112

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Notebook      | P7xxTM                      | Notebook    | [e14cfa2f1f](https://linux-hardware.org/?probe=e14cfa2f1f) | Sep 22, 2023 |
| Notebook      | P7xxTM                      | Notebook    | [41b1348520](https://linux-hardware.org/?probe=41b1348520) | Sep 22, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | Notebook    | [586c1fab43](https://linux-hardware.org/?probe=586c1fab43) | Sep 06, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [10db09006a](https://linux-hardware.org/?probe=10db09006a) | Aug 31, 2023 |
| Dell          | Vostro 3405                 | Notebook    | [2ba4151315](https://linux-hardware.org/?probe=2ba4151315) | Aug 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [b8ceea98b8](https://linux-hardware.org/?probe=b8ceea98b8) | Aug 18, 2023 |
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
| 5.15.19           | 20        | 20.62%  |
| 5.19.17           | 7         | 7.22%   |
| 5.15.63           | 6         | 6.19%   |
| 5.15.27           | 4         | 4.12%   |
| 5.15.117          | 4         | 4.12%   |
| 5.19.17-Unraid    | 3         | 3.09%   |
| 5.15.38           | 3         | 3.09%   |
| 6.1.44            | 2         | 2.06%   |
| 5.17.2            | 2         | 2.06%   |
| 5.17.1            | 2         | 2.06%   |
| 5.16.13           | 2         | 2.06%   |
| 5.15.94           | 2         | 2.06%   |
| 5.15.80           | 2         | 2.06%   |
| 5.15.30-Unraid    | 2         | 2.06%   |
| 5.13.8            | 2         | 2.06%   |
| 6.1.51            | 1         | 1.03%   |
| 6.1.27            | 1         | 1.03%   |
| 6.1.20            | 1         | 1.03%   |
| 6.1.13            | 1         | 1.03%   |
| 6.1.12            | 1         | 1.03%   |
| 6.1.1             | 1         | 1.03%   |
| 5.19.16           | 1         | 1.03%   |
| 5.17.5            | 1         | 1.03%   |
| 5.17.0-custom     | 1         | 1.03%   |
| 5.16.9-joe1       | 1         | 1.03%   |
| 5.16.18           | 1         | 1.03%   |
| 5.16.12           | 1         | 1.03%   |
| 5.16.11           | 1         | 1.03%   |
| 5.15.78.a         | 1         | 1.03%   |
| 5.15.6            | 1         | 1.03%   |
| 5.15.37.a         | 1         | 1.03%   |
| 5.15.33.kjh       | 1         | 1.03%   |
| 5.15.21-hardened1 | 1         | 1.03%   |
| 5.15.14           | 1         | 1.03%   |
| 5.15.13           | 1         | 1.03%   |
| 5.15.103          | 1         | 1.03%   |
| 5.15.1            | 1         | 1.03%   |
| 5.14.9            | 1         | 1.03%   |
| 5.14.8            | 1         | 1.03%   |
| 5.14.15-Unraid    | 1         | 1.03%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.19  | 20        | 20.62%  |
| 5.19.17  | 10        | 10.31%  |
| 5.15.63  | 6         | 6.19%   |
| 5.15.27  | 4         | 4.12%   |
| 5.15.117 | 4         | 4.12%   |
| 5.15.38  | 3         | 3.09%   |
| 6.1.44   | 2         | 2.06%   |
| 5.17.2   | 2         | 2.06%   |
| 5.17.1   | 2         | 2.06%   |
| 5.16.13  | 2         | 2.06%   |
| 5.15.94  | 2         | 2.06%   |
| 5.15.80  | 2         | 2.06%   |
| 5.15.30  | 2         | 2.06%   |
| 5.14.15  | 2         | 2.06%   |
| 5.13.8   | 2         | 2.06%   |
| 6.1.51   | 1         | 1.03%   |
| 6.1.27   | 1         | 1.03%   |
| 6.1.20   | 1         | 1.03%   |
| 6.1.13   | 1         | 1.03%   |
| 6.1.12   | 1         | 1.03%   |
| 6.1.1    | 1         | 1.03%   |
| 5.19.16  | 1         | 1.03%   |
| 5.17.5   | 1         | 1.03%   |
| 5.17.0   | 1         | 1.03%   |
| 5.16.9   | 1         | 1.03%   |
| 5.16.18  | 1         | 1.03%   |
| 5.16.12  | 1         | 1.03%   |
| 5.16.11  | 1         | 1.03%   |
| 5.15.78  | 1         | 1.03%   |
| 5.15.6   | 1         | 1.03%   |
| 5.15.37  | 1         | 1.03%   |
| 5.15.33  | 1         | 1.03%   |
| 5.15.21  | 1         | 1.03%   |
| 5.15.14  | 1         | 1.03%   |
| 5.15.13  | 1         | 1.03%   |
| 5.15.103 | 1         | 1.03%   |
| 5.15.1   | 1         | 1.03%   |
| 5.14.9   | 1         | 1.03%   |
| 5.14.8   | 1         | 1.03%   |
| 5.14.12  | 1         | 1.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 52        | 54.74%  |
| 5.19    | 11        | 11.58%  |
| 6.1     | 7         | 7.37%   |
| 5.14    | 7         | 7.37%   |
| 5.17    | 6         | 6.32%   |
| 5.16    | 6         | 6.32%   |
| 5.13    | 5         | 5.26%   |
| 5.10    | 1         | 1.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 91        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE5       | 37        | 39.78%  |
| XFCE       | 28        | 30.11%  |
| Unknown    | 16        | 17.2%   |
| GNOME      | 3         | 3.23%   |
| xwmconfig  | 2         | 2.15%   |
| X-Generic  | 1         | 1.08%   |
| X-Cinnamon | 1         | 1.08%   |
| MATE       | 1         | 1.08%   |
| KDE        | 1         | 1.08%   |
| FVWM       | 1         | 1.08%   |
| awesome    | 1         | 1.08%   |
| 2bwm       | 1         | 1.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 51        | 53.13%  |
| Tty     | 34        | 35.42%  |
| Wayland | 6         | 6.25%   |
| Unknown | 5         | 5.21%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 45        | 47.87%  |
| Unknown | 25        | 26.6%   |
| XDM     | 17        | 18.09%  |
| LightDM | 5         | 5.32%   |
| SLiM    | 1         | 1.06%   |
| GDM     | 1         | 1.06%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 60        | 65.93%  |
| Unknown     | 10        | 10.99%  |
| it_IT       | 4         | 4.4%    |
| pt_BR       | 3         | 3.3%    |
| de_DE       | 3         | 3.3%    |
| ru_RU       | 2         | 2.2%    |
| fr_FR       | 2         | 2.2%    |
| en_GB       | 2         | 2.2%    |
| us          | 1         | 1.1%    |
| pt_PT       | 1         | 1.1%    |
| es_ES.UTF8  | 1         | 1.1%    |
| es_ES       | 1         | 1.1%    |
| en_US.ASCII | 1         | 1.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 52        | 57.14%  |
| BIOS | 39        | 42.86%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 67        | 72.83%  |
| Btrfs   | 10        | 10.87%  |
| Xfs     | 5         | 5.43%   |
| Overlay | 5         | 5.43%   |
| Zfs     | 1         | 1.09%   |
| Tmpfs   | 1         | 1.09%   |
| Rootfs  | 1         | 1.09%   |
| F2fs    | 1         | 1.09%   |
| Ext2    | 1         | 1.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 65        | 70.65%  |
| MBR     | 14        | 15.22%  |
| Unknown | 13        | 14.13%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 67        | 72.04%  |
| Yes       | 26        | 27.96%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 61        | 67.03%  |
| Yes       | 30        | 32.97%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 16        | 17.58%  |
| Lenovo              | 13        | 14.29%  |
| MSI                 | 12        | 13.19%  |
| ASUSTek Computer    | 12        | 13.19%  |
| Dell                | 9         | 9.89%   |
| ASRock              | 7         | 7.69%   |
| Gigabyte Technology | 3         | 3.3%    |
| Acer                | 3         | 3.3%    |
| Notebook            | 2         | 2.2%    |
| Fujitsu             | 2         | 2.2%    |
| Apple               | 2         | 2.2%    |
| Valve               | 1         | 1.1%    |
| TYAN Computer       | 1         | 1.1%    |
| System76            | 1         | 1.1%    |
| Sony                | 1         | 1.1%    |
| Microsoft           | 1         | 1.1%    |
| HEDYCOMPUTER        | 1         | 1.1%    |
| Framework           | 1         | 1.1%    |
| Dynabook            | 1         | 1.1%    |
| Biostar             | 1         | 1.1%    |
| Unknown             | 1         | 1.1%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| ASUS VivoBook_ASUSLaptop K6500ZE_K6500ZE | 2         | 2.2%    |
| ASRock N68-S3 FX                         | 2         | 2.2%    |
| Valve Jupiter                            | 1         | 1.1%    |
| TYAN S7012                               | 1         | 1.1%    |
| System76 Oryx Pro                        | 1         | 1.1%    |
| Sony SVE1713A1EW                         | 1         | 1.1%    |
| Notebook X170KM-G                        | 1         | 1.1%    |
| Notebook P7xxTM                          | 1         | 1.1%    |
| MSI MS-7C52                              | 1         | 1.1%    |
| MSI MS-7C02                              | 1         | 1.1%    |
| MSI MS-7996                              | 1         | 1.1%    |
| MSI MS-7885                              | 1         | 1.1%    |
| MSI MS-7788                              | 1         | 1.1%    |
| MSI MS-7693                              | 1         | 1.1%    |
| MSI MS-7529                              | 1         | 1.1%    |
| MSI MS-7365                              | 1         | 1.1%    |
| MSI Modern 14 B11MO                      | 1         | 1.1%    |
| MSI Modern 14 B10MW                      | 1         | 1.1%    |
| MSI GP76 Leopard 11UG                    | 1         | 1.1%    |
| MSI GE76 Raider 11UE                     | 1         | 1.1%    |
| Microsoft Surface Go 3                   | 1         | 1.1%    |
| Lenovo ThinkPad X230 2325P38             | 1         | 1.1%    |
| Lenovo ThinkPad X140e 20BMS03E00         | 1         | 1.1%    |
| Lenovo ThinkPad X1 Carbon 5th 20HQS04300 | 1         | 1.1%    |
| Lenovo ThinkPad X1 Carbon 4th 20FCS2FT00 | 1         | 1.1%    |
| Lenovo ThinkPad T61 765912G              | 1         | 1.1%    |
| Lenovo ThinkPad T470p 20J60018MS         | 1         | 1.1%    |
| Lenovo ThinkPad T470 20JNS01R01          | 1         | 1.1%    |
| Lenovo ThinkPad T410 2518C3U             | 1         | 1.1%    |
| Lenovo ThinkPad Edge E530c 336669G       | 1         | 1.1%    |
| Lenovo ThinkPad E16 Gen 1 21JT000PJP     | 1         | 1.1%    |
| Lenovo IdeaPad 5 15ALC05 82LN            | 1         | 1.1%    |
| Lenovo IdeaPad 310-15ISK 80SM            | 1         | 1.1%    |
| Lenovo H50-05 90BH001WIX                 | 1         | 1.1%    |
| HP Z440 Workstation                      | 1         | 1.1%    |
| HP xw8400 Workstation                    | 1         | 1.1%    |
| HP ProBook 6570b                         | 1         | 1.1%    |
| HP Pavilion Gaming Laptop 16-a0xxx       | 1         | 1.1%    |
| HP Pavilion Gaming Laptop 15-ec1xxx      | 1         | 1.1%    |
| HP Pavilion Gaming Desktop TG01-2xxx     | 1         | 1.1%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 10        | 10.99%  |
| HP Pavilion       | 3         | 3.3%    |
| ASUS ROG          | 3         | 3.3%    |
| ASUS PRIME        | 3         | 3.3%    |
| MSI Modern        | 2         | 2.2%    |
| Lenovo IdeaPad    | 2         | 2.2%    |
| HP OMEN           | 2         | 2.2%    |
| HP Laptop         | 2         | 2.2%    |
| HP EliteBook      | 2         | 2.2%    |
| Dell Vostro       | 2         | 2.2%    |
| Dell Precision    | 2         | 2.2%    |
| Dell OptiPlex     | 2         | 2.2%    |
| ASUS VivoBook     | 2         | 2.2%    |
| ASUS TUF          | 2         | 2.2%    |
| ASRock N68-S3     | 2         | 2.2%    |
| Valve Jupiter     | 1         | 1.1%    |
| TYAN S7012        | 1         | 1.1%    |
| System76 Oryx     | 1         | 1.1%    |
| Sony SVE1713A1EW  | 1         | 1.1%    |
| Notebook X170KM-G | 1         | 1.1%    |
| Notebook P7xxTM   | 1         | 1.1%    |
| MSI MS-7C52       | 1         | 1.1%    |
| MSI MS-7C02       | 1         | 1.1%    |
| MSI MS-7996       | 1         | 1.1%    |
| MSI MS-7885       | 1         | 1.1%    |
| MSI MS-7788       | 1         | 1.1%    |
| MSI MS-7693       | 1         | 1.1%    |
| MSI MS-7529       | 1         | 1.1%    |
| MSI MS-7365       | 1         | 1.1%    |
| MSI GP76          | 1         | 1.1%    |
| MSI GE76          | 1         | 1.1%    |
| Microsoft Surface | 1         | 1.1%    |
| Lenovo H50-05     | 1         | 1.1%    |
| HP Z440           | 1         | 1.1%    |
| HP xw8400         | 1         | 1.1%    |
| HP ProBook        | 1         | 1.1%    |
| HP ENVY           | 1         | 1.1%    |
| HP Compaq         | 1         | 1.1%    |
| HP 245            | 1         | 1.1%    |
| HP 205            | 1         | 1.1%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 15        | 16.48%  |
| 2021 | 12        | 13.19%  |
| 2022 | 8         | 8.79%   |
| 2017 | 8         | 8.79%   |
| 2015 | 7         | 7.69%   |
| 2012 | 6         | 6.59%   |
| 2011 | 6         | 6.59%   |
| 2019 | 5         | 5.49%   |
| 2018 | 4         | 4.4%    |
| 2016 | 3         | 3.3%    |
| 2014 | 3         | 3.3%    |
| 2010 | 3         | 3.3%    |
| 2009 | 3         | 3.3%    |
| 2008 | 3         | 3.3%    |
| 2007 | 3         | 3.3%    |
| 2023 | 1         | 1.1%    |
| 2013 | 1         | 1.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 46        | 50.55%  |
| Desktop    | 39        | 42.86%  |
| All in one | 2         | 2.2%    |
| Server     | 2         | 2.2%    |
| Tablet     | 1         | 1.1%    |
| Mini pc    | 1         | 1.1%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 91        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 89        | 97.8%   |
| Yes  | 2         | 2.2%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 21        | 22.83%  |
| 8.01-16.0   | 19        | 20.65%  |
| 3.01-4.0    | 14        | 15.22%  |
| 4.01-8.0    | 13        | 14.13%  |
| 32.01-64.0  | 11        | 11.96%  |
| 64.01-256.0 | 7         | 7.61%   |
| 24.01-32.0  | 4         | 4.35%   |
| 1.01-2.0    | 3         | 3.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 25        | 26.04%  |
| 1.01-2.0   | 24        | 25%     |
| 4.01-8.0   | 21        | 21.88%  |
| 0.51-1.0   | 10        | 10.42%  |
| 3.01-4.0   | 7         | 7.29%   |
| 16.01-24.0 | 3         | 3.13%   |
| 0.01-0.5   | 3         | 3.13%   |
| 8.01-16.0  | 2         | 2.08%   |
| 32.01-64.0 | 1         | 1.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 47        | 50%     |
| 2      | 24        | 25.53%  |
| 3      | 10        | 10.64%  |
| 4      | 6         | 6.38%   |
| 6      | 4         | 4.26%   |
| 11     | 1         | 1.06%   |
| 9      | 1         | 1.06%   |
| 0      | 1         | 1.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 62        | 67.39%  |
| Yes       | 30        | 32.61%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 82        | 90.11%  |
| No        | 9         | 9.89%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 68        | 73.91%  |
| No        | 24        | 26.09%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 59        | 64.84%  |
| No        | 32        | 35.16%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 20        | 21.98%  |
| Italy        | 7         | 7.69%   |
| Kazakhstan   | 6         | 6.59%   |
| Brazil       | 6         | 6.59%   |
| UK           | 5         | 5.49%   |
| Japan        | 5         | 5.49%   |
| Germany      | 5         | 5.49%   |
| Portugal     | 4         | 4.4%    |
| Spain        | 3         | 3.3%    |
| South Africa | 3         | 3.3%    |
| Russia       | 3         | 3.3%    |
| Greece       | 3         | 3.3%    |
| India        | 2         | 2.2%    |
| Hong Kong    | 2         | 2.2%    |
| France       | 2         | 2.2%    |
| China        | 2         | 2.2%    |
| Canada       | 2         | 2.2%    |
| Argentina    | 2         | 2.2%    |
| Switzerland  | 1         | 1.1%    |
| Sweden       | 1         | 1.1%    |
| Serbia       | 1         | 1.1%    |
| Romania      | 1         | 1.1%    |
| Netherlands  | 1         | 1.1%    |
| Mexico       | 1         | 1.1%    |
| Iran         | 1         | 1.1%    |
| Chile        | 1         | 1.1%    |
| Australia    | 1         | 1.1%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Ust-Kamenogorsk   | 4         | 4.3%    |
| Tsukuba           | 4         | 4.3%    |
| Lisbon            | 3         | 3.23%   |
| Chania            | 3         | 3.23%   |
| Sun Prairie       | 2         | 2.15%   |
| Rome              | 2         | 2.15%   |
| Moscow            | 2         | 2.15%   |
| McKinney          | 2         | 2.15%   |
| Karaganda         | 2         | 2.15%   |
| Greater Noida     | 2         | 2.15%   |
| Frignano          | 2         | 2.15%   |
| Fayetteville      | 2         | 2.15%   |
| Cape Town         | 2         | 2.15%   |
| Worpswede         | 1         | 1.08%   |
| Winter Springs    | 1         | 1.08%   |
| Villa Carlos Paz  | 1         | 1.08%   |
| Toronto           | 1         | 1.08%   |
| Tehran            | 1         | 1.08%   |
| Tatuí            | 1         | 1.08%   |
| St Petersburg     | 1         | 1.08%   |
| Springfield       | 1         | 1.08%   |
| Skövde           | 1         | 1.08%   |
| Sham Shui Po      | 1         | 1.08%   |
| Seville           | 1         | 1.08%   |
| Senhora da Hora   | 1         | 1.08%   |
| Sao Paulo         | 1         | 1.08%   |
| Santiago          | 1         | 1.08%   |
| Santa Cruz do Sul | 1         | 1.08%   |
| Saint Paul        | 1         | 1.08%   |
| Round Rock        | 1         | 1.08%   |
| Rock              | 1         | 1.08%   |
| Reno              | 1         | 1.08%   |
| Renazzo           | 1         | 1.08%   |
| Porto Alegre      | 1         | 1.08%   |
| Plainwell         | 1         | 1.08%   |
| Penrith           | 1         | 1.08%   |
| Ōtsu             | 1         | 1.08%   |
| Oberstreit        | 1         | 1.08%   |
| Nanping           | 1         | 1.08%   |
| Naaldwijk         | 1         | 1.08%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 26        | 35     | 17.22%  |
| WDC                         | 23        | 41     | 15.23%  |
| Seagate                     | 22        | 31     | 14.57%  |
| Toshiba                     | 11        | 22     | 7.28%   |
| Kingston                    | 10        | 12     | 6.62%   |
| Intel                       | 6         | 7      | 3.97%   |
| Crucial                     | 6         | 7      | 3.97%   |
| Hitachi                     | 5         | 8      | 3.31%   |
| SK hynix                    | 4         | 4      | 2.65%   |
| SanDisk                     | 4         | 5      | 2.65%   |
| HGST                        | 4         | 4      | 2.65%   |
| Transcend                   | 3         | 3      | 1.99%   |
| KIOXIA                      | 3         | 3      | 1.99%   |
| Micron Technology           | 2         | 2      | 1.32%   |
| Hewlett-Packard             | 2         | 3      | 1.32%   |
| Gigabyte Technology         | 2         | 2      | 1.32%   |
| ZHITAI                      | 1         | 2      | 0.66%   |
| Unknown                     | 1         | 2      | 0.66%   |
| Silicon Motion              | 1         | 1      | 0.66%   |
| PNY                         | 1         | 1      | 0.66%   |
| Plextor                     | 1         | 1      | 0.66%   |
| Phison Electronics          | 1         | 1      | 0.66%   |
| Patriot                     | 1         | 1      | 0.66%   |
| Maxtor                      | 1         | 1      | 0.66%   |
| Lexar                       | 1         | 1      | 0.66%   |
| Kingston Technology Company | 1         | 1      | 0.66%   |
| JMicron Technology          | 1         | 1      | 0.66%   |
| Intenso                     | 1         | 1      | 0.66%   |
| GOODRAM                     | 1         | 1      | 0.66%   |
| External                    | 1         | 1      | 0.66%   |
| DUEX                        | 1         | 1      | 0.66%   |
| China                       | 1         | 1      | 0.66%   |
| Apple                       | 1         | 1      | 0.66%   |
| A-DATA Technology           | 1         | 1      | 0.66%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD      | 4         | 2.31%   |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 2         | 1.16%   |
| WDC WD20EFRX-68EUZN0 2TB             | 2         | 1.16%   |
| WDC WD10SPZX-60Z10T0 1TB             | 2         | 1.16%   |
| WDC WD10EZEX-08WN4A0 1TB             | 2         | 1.16%   |
| Seagate ST2000DM008-2FR102 2TB       | 2         | 1.16%   |
| Seagate ST2000DL003-9VT166 2TB       | 2         | 1.16%   |
| Seagate ST1000DM003-1SB102 1TB       | 2         | 1.16%   |
| Seagate Expansion Desk 8TB           | 2         | 1.16%   |
| Samsung SSD 970 EVO Plus 500GB       | 2         | 1.16%   |
| Samsung SSD 970 EVO 250GB            | 2         | 1.16%   |
| Kingston SA400S37120G 120GB SSD      | 2         | 1.16%   |
| Intel SSD 660P Series 1024GB         | 2         | 1.16%   |
| HGST HTS725050A7E630 500GB           | 2         | 1.16%   |
| Crucial CT500MX500SSD1 500GB         | 2         | 1.16%   |
| ZHITAI SC001 Active 1TB SSD          | 1         | 0.58%   |
| ZHITAI PC005 Active 512GB            | 1         | 0.58%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1         | 0.58%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1         | 0.58%   |
| WDC WDS100T2B0B-00YS70 1TB SSD       | 1         | 0.58%   |
| WDC WD5000BEKT-60KA9T0 500GB         | 1         | 0.58%   |
| WDC WD5000AAKX-22ERMA0 500GB         | 1         | 0.58%   |
| WDC WD5000AAKS-007AA0 500GB          | 1         | 0.58%   |
| WDC WD5000AADS-00S9B0 500GB          | 1         | 0.58%   |
| WDC WD40EZRX-00SPEB0 4TB             | 1         | 0.58%   |
| WDC WD40EJRX-89T1XY0 4TB             | 1         | 0.58%   |
| WDC WD400BD-60LTA0 40GB              | 1         | 0.58%   |
| WDC WD3200AAJS-65B4A0 320GB          | 1         | 0.58%   |
| WDC WD30EZRX-00SPEB0 3TB             | 1         | 0.58%   |
| WDC WD30EZRX-00MMMB0 3TB             | 1         | 0.58%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 1         | 0.58%   |
| WDC WD20EZRX-00D8PB0 2TB             | 1         | 0.58%   |
| WDC WD20EARX-00PASB0 2TB             | 1         | 0.58%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.58%   |
| WDC WD10JPVT-08A1YT2 1TB             | 1         | 0.58%   |
| WDC WD10EZEX-00RKKA0 1TB             | 1         | 0.58%   |
| WDC WD10EZEX-00MFCA0 1TB             | 1         | 0.58%   |
| WDC WD Green 2.5 240GB               | 1         | 0.58%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB   | 1         | 0.58%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB | 1         | 0.58%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 22        | 31     | 35.48%  |
| WDC                 | 18        | 33     | 29.03%  |
| Toshiba             | 10        | 17     | 16.13%  |
| Hitachi             | 5         | 8      | 8.06%   |
| HGST                | 4         | 4      | 6.45%   |
| Samsung Electronics | 1         | 1      | 1.61%   |
| Maxtor              | 1         | 1      | 1.61%   |
| External            | 1         | 1      | 1.61%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 14     | 20.83%  |
| Kingston            | 10        | 12     | 20.83%  |
| WDC                 | 4         | 6      | 8.33%   |
| Crucial             | 4         | 5      | 8.33%   |
| Transcend           | 2         | 2      | 4.17%   |
| SanDisk             | 2         | 2      | 4.17%   |
| ZHITAI              | 1         | 1      | 2.08%   |
| Toshiba             | 1         | 3      | 2.08%   |
| SK hynix            | 1         | 1      | 2.08%   |
| PNY                 | 1         | 1      | 2.08%   |
| Plextor             | 1         | 1      | 2.08%   |
| Patriot             | 1         | 1      | 2.08%   |
| Lexar               | 1         | 1      | 2.08%   |
| JMicron Technology  | 1         | 1      | 2.08%   |
| Intenso             | 1         | 1      | 2.08%   |
| Intel               | 1         | 2      | 2.08%   |
| Hewlett-Packard     | 1         | 1      | 2.08%   |
| GOODRAM             | 1         | 1      | 2.08%   |
| Gigabyte Technology | 1         | 1      | 2.08%   |
| DUEX                | 1         | 1      | 2.08%   |
| China               | 1         | 1      | 2.08%   |
| Apple               | 1         | 1      | 2.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 44        | 96     | 34.11%  |
| SSD  | 43        | 60     | 33.33%  |
| NVMe | 41        | 51     | 31.78%  |
| MMC  | 1         | 2      | 0.78%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 62        | 150    | 56.36%  |
| NVMe | 41        | 51     | 37.27%  |
| SAS  | 6         | 6      | 5.45%   |
| MMC  | 1         | 2      | 0.91%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 50        | 67     | 49.5%   |
| 0.51-1.0   | 22        | 41     | 21.78%  |
| 1.01-2.0   | 12        | 15     | 11.88%  |
| 3.01-4.0   | 8         | 15     | 7.92%   |
| 4.01-10.0  | 5         | 7      | 4.95%   |
| 2.01-3.0   | 4         | 11     | 3.96%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 24        | 25.26%  |
| 501-1000       | 20        | 21.05%  |
| 251-500        | 15        | 15.79%  |
| 1001-2000      | 8         | 8.42%   |
| Unknown        | 8         | 8.42%   |
| 1-20           | 7         | 7.37%   |
| 2001-3000      | 6         | 6.32%   |
| More than 3000 | 3         | 3.16%   |
| 21-50          | 2         | 2.11%   |
| 51-100         | 2         | 2.11%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 22        | 23.16%  |
| 1-20           | 17        | 17.89%  |
| 21-50          | 14        | 14.74%  |
| 251-500        | 11        | 11.58%  |
| 501-1000       | 9         | 9.47%   |
| Unknown        | 8         | 8.42%   |
| 51-100         | 7         | 7.37%   |
| 1001-2000      | 6         | 6.32%   |
| More than 3000 | 1         | 1.05%   |

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
| Works    | 72        | 139    | 66.67%  |
| Detected | 21        | 49     | 19.44%  |
| Malfunc  | 15        | 21     | 13.89%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 48        | 39.34%  |
| AMD                          | 23        | 18.85%  |
| Samsung Electronics          | 16        | 13.11%  |
| SanDisk                      | 4         | 3.28%   |
| Nvidia                       | 4         | 3.28%   |
| SK hynix                     | 3         | 2.46%   |
| Marvell Technology Group     | 3         | 2.46%   |
| KIOXIA                       | 3         | 2.46%   |
| Micron/Crucial Technology    | 2         | 1.64%   |
| Micron Technology            | 2         | 1.64%   |
| JMicron Technology           | 2         | 1.64%   |
| ASMedia Technology           | 2         | 1.64%   |
| Yangtze Memory Technologies  | 1         | 0.82%   |
| Toshiba America Info Systems | 1         | 0.82%   |
| Silicon Motion               | 1         | 0.82%   |
| Realtek Semiconductor        | 1         | 0.82%   |
| Phison Electronics           | 1         | 0.82%   |
| LSI Logic / Symbios Logic    | 1         | 0.82%   |
| Kingston Technology Company  | 1         | 0.82%   |
| Broadcom / LSI               | 1         | 0.82%   |
| Biwin Storage Technology     | 1         | 0.82%   |
| Adaptec                      | 1         | 0.82%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 14        | 9.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 7         | 4.64%   |
| AMD 400 Series Chipset SATA Controller                                           | 7         | 4.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 5         | 3.31%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 5         | 3.31%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 2.65%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 1.99%   |
| Nvidia MCP61 SATA Controller                                                     | 3         | 1.99%   |
| Nvidia MCP61 IDE                                                                 | 3         | 1.99%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 3         | 1.99%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 1.99%   |
| Intel SSD 660P Series                                                            | 3         | 1.99%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 3         | 1.99%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 3         | 1.99%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.99%   |
| SK hynix BC511 NVMe SSD                                                          | 2         | 1.32%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 1.32%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 2         | 1.32%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 2         | 1.32%   |
| JMicron JMB58x AHCI SATA controller                                              | 2         | 1.32%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 1.32%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.32%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 2         | 1.32%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 1.32%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 1.32%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 1.32%   |
| Intel 631xESB/632xESB IDE Controller                                             | 2         | 1.32%   |
| Intel 4 Series Chipset PT IDER Controller                                        | 2         | 1.32%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 2         | 1.32%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 2         | 1.32%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 1.32%   |
| AMD 500 Series Chipset SATA Controller                                           | 2         | 1.32%   |
| Yangtze Memory ZHITAI PC005 NVMe SSD                                             | 1         | 0.66%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 1         | 0.66%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 1         | 0.66%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 1         | 0.66%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 0.66%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 0.66%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD          | 1         | 0.66%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                            | 1         | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 55        | 44%     |
| NVMe | 41        | 32.8%   |
| IDE  | 16        | 12.8%   |
| RAID | 10        | 8%      |
| SCSI | 3         | 2.4%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 61        | 67.03%  |
| AMD    | 30        | 32.97%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 4         | 4.35%   |
| Intel 12th Gen Core i7-12700H           | 3         | 3.26%   |
| Intel Core i7-5820K CPU @ 3.30GHz       | 2         | 2.17%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 2         | 2.17%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz    | 2         | 2.17%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 2         | 2.17%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 2.17%   |
| AMD Ryzen 9 5950X 16-Core Processor     | 2         | 2.17%   |
| AMD Ryzen 5 3600 6-Core Processor       | 2         | 2.17%   |
| AMD Athlon II X2 250 Processor          | 2         | 2.17%   |
| Intel Xeon CPU X5680 @ 3.33GHz          | 1         | 1.09%   |
| Intel Xeon CPU X5355 @ 2.66GHz          | 1         | 1.09%   |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz     | 1         | 1.09%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz     | 1         | 1.09%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz     | 1         | 1.09%   |
| Intel Xeon CPU 5160 @ 3.00GHz           | 1         | 1.09%   |
| Intel Pentium Silver N6000 @ 1.10GHz    | 1         | 1.09%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz  | 1         | 1.09%   |
| Intel Pentium CPU GOLD 6500Y @ 1.10GHz  | 1         | 1.09%   |
| Intel Pentium CPU G3250 @ 3.20GHz       | 1         | 1.09%   |
| Intel Pentium CPU 2020M @ 2.40GHz       | 1         | 1.09%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 1         | 1.09%   |
| Intel Core i7-8700K CPU @ 3.70GHz       | 1         | 1.09%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 1.09%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 1         | 1.09%   |
| Intel Core i7-7700 CPU @ 3.60GHz        | 1         | 1.09%   |
| Intel Core i7-7600U CPU @ 2.80GHz       | 1         | 1.09%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 1         | 1.09%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 1         | 1.09%   |
| Intel Core i7-3840QM CPU @ 2.80GHz      | 1         | 1.09%   |
| Intel Core i7-3720QM CPU @ 2.60GHz      | 1         | 1.09%   |
| Intel Core i7-10870H CPU @ 2.20GHz      | 1         | 1.09%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 1         | 1.09%   |
| Intel Core i5-8600K CPU @ 3.60GHz       | 1         | 1.09%   |
| Intel Core i5-4590 CPU @ 3.30GHz        | 1         | 1.09%   |
| Intel Core i5-4310M CPU @ 2.70GHz       | 1         | 1.09%   |
| Intel Core i5-3360M CPU @ 2.80GHz       | 1         | 1.09%   |
| Intel Core i5-3330 CPU @ 3.00GHz        | 1         | 1.09%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 1         | 1.09%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 1         | 1.09%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Other                | 14        | 15.22%  |
| Intel Core i7        | 14        | 15.22%  |
| Intel Core i5        | 14        | 15.22%  |
| AMD Ryzen 5          | 9         | 9.78%   |
| Intel Xeon           | 6         | 6.52%   |
| Intel Core 2 Duo     | 5         | 5.43%   |
| AMD Ryzen 7          | 5         | 5.43%   |
| AMD Ryzen 9          | 4         | 4.35%   |
| Intel Pentium        | 3         | 3.26%   |
| AMD FX               | 3         | 3.26%   |
| Intel Core i3        | 2         | 2.17%   |
| Intel Celeron        | 2         | 2.17%   |
| AMD Athlon II X2     | 2         | 2.17%   |
| Intel Pentium Silver | 1         | 1.09%   |
| Intel Pentium Dual   | 1         | 1.09%   |
| Intel Atom           | 1         | 1.09%   |
| AMD Ryzen 7 PRO      | 1         | 1.09%   |
| AMD Ryzen 3          | 1         | 1.09%   |
| AMD EPYC             | 1         | 1.09%   |
| AMD E1               | 1         | 1.09%   |
| AMD Athlon           | 1         | 1.09%   |
| AMD A8               | 1         | 1.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 28        | 30.43%  |
| 2      | 27        | 29.35%  |
| 8      | 16        | 17.39%  |
| 6      | 9         | 9.78%   |
| 14     | 4         | 4.35%   |
| 10     | 3         | 3.26%   |
| 16     | 2         | 2.17%   |
| 12     | 2         | 2.17%   |
| 3      | 1         | 1.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 88        | 96.7%   |
| 2      | 3         | 3.3%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 67        | 73.63%  |
| 1      | 24        | 26.37%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 91        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 19        | 20.88%  |
| 0x306a9    | 7         | 7.69%   |
| 0x906a3    | 4         | 4.4%    |
| 0x806d1    | 4         | 4.4%    |
| 0x08108109 | 4         | 4.4%    |
| 0x806c1    | 3         | 3.3%    |
| 0x306f2    | 3         | 3.3%    |
| 0x08701021 | 3         | 3.3%    |
| 0x906ea    | 2         | 2.2%    |
| 0x406e3    | 2         | 2.2%    |
| 0x406c4    | 2         | 2.2%    |
| 0x306c3    | 2         | 2.2%    |
| 0x1067a    | 2         | 2.2%    |
| 0x0a50000c | 2         | 2.2%    |
| 0x0a201016 | 2         | 2.2%    |
| 0x08600106 | 2         | 2.2%    |
| 0xa0671    | 1         | 1.1%    |
| 0xa0653    | 1         | 1.1%    |
| 0xa0652    | 1         | 1.1%    |
| 0x906e9    | 1         | 1.1%    |
| 0x906c0    | 1         | 1.1%    |
| 0x906a4    | 1         | 1.1%    |
| 0x806ec    | 1         | 1.1%    |
| 0x806ea    | 1         | 1.1%    |
| 0x6fd      | 1         | 1.1%    |
| 0x6fb      | 1         | 1.1%    |
| 0x6fa      | 1         | 1.1%    |
| 0x506e3    | 1         | 1.1%    |
| 0x306e4    | 1         | 1.1%    |
| 0x306d4    | 1         | 1.1%    |
| 0x206c2    | 1         | 1.1%    |
| 0x20655    | 1         | 1.1%    |
| 0x106c2    | 1         | 1.1%    |
| 0x0a20120a | 1         | 1.1%    |
| 0x08900201 | 1         | 1.1%    |
| 0x08608102 | 1         | 1.1%    |
| 0x0830104d | 1         | 1.1%    |
| 0x0810100b | 1         | 1.1%    |
| 0x08001126 | 1         | 1.1%    |
| 0x07030105 | 1         | 1.1%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 10        | 10.99%  |
| Zen 2            | 8         | 8.79%   |
| IvyBridge        | 8         | 8.79%   |
| Zen 3            | 6         | 6.59%   |
| Haswell          | 6         | 6.59%   |
| Zen+             | 5         | 5.49%   |
| Icelake          | 5         | 5.49%   |
| Core             | 5         | 5.49%   |
| Alderlake Hybrid | 5         | 5.49%   |
| Westmere         | 4         | 4.4%    |
| Skylake          | 4         | 4.4%    |
| TigerLake        | 3         | 3.3%    |
| Penryn           | 3         | 3.3%    |
| Zen              | 2         | 2.2%    |
| Silvermont       | 2         | 2.2%    |
| Piledriver       | 2         | 2.2%    |
| K10              | 2         | 2.2%    |
| CometLake        | 2         | 2.2%    |
| Unknown          | 2         | 2.2%    |
| Tremont          | 1         | 1.1%    |
| SandyBridge      | 1         | 1.1%    |
| Puma             | 1         | 1.1%    |
| Jaguar           | 1         | 1.1%    |
| Bulldozer        | 1         | 1.1%    |
| Broadwell        | 1         | 1.1%    |
| Bonnell          | 1         | 1.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 40        | 37.74%  |
| Nvidia                     | 37        | 34.91%  |
| AMD                        | 28        | 26.42%  |
| Matrox Electronics Systems | 1         | 0.94%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 4.63%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 4         | 3.7%    |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 3         | 2.78%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 2.78%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 2.78%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 2.78%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 3         | 2.78%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 2.78%   |
| AMD Renoir                                                                               | 3         | 2.78%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 3         | 2.78%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 2.78%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 1.85%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 1.85%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2         | 1.85%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2         | 1.85%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2         | 1.85%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 1.85%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 2         | 1.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 1.85%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.85%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.85%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 1.85%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 2         | 1.85%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 1.85%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.93%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 1         | 0.93%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile / Max-Q]                                         | 1         | 0.93%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.93%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.93%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.93%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 0.93%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.93%   |
| Nvidia GF108GL [Quadro 600]                                                              | 1         | 0.93%   |
| Nvidia GA107M [GeForce RTX 2050]                                                         | 1         | 0.93%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 1         | 0.93%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                                       | 1         | 0.93%   |
| Nvidia G96C [GeForce 9400 GT]                                                            | 1         | 0.93%   |
| Nvidia G84 [GeForce 8600 GT]                                                             | 1         | 0.93%   |
| Nvidia G71GL [Quadro FX 1500]                                                            | 1         | 0.93%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 27        | 29.67%  |
| 1 x AMD        | 26        | 28.57%  |
| 1 x Nvidia     | 23        | 25.27%  |
| Intel + Nvidia | 12        | 13.19%  |
| 2 x AMD        | 1         | 1.1%    |
| 1 x Matrox     | 1         | 1.1%    |
| AMD + Nvidia   | 1         | 1.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 72        | 79.12%  |
| Proprietary | 16        | 17.58%  |
| Unknown     | 3         | 3.3%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 44        | 48.35%  |
| 0.01-0.5   | 10        | 10.99%  |
| 0.51-1.0   | 9         | 9.89%   |
| 7.01-8.0   | 8         | 8.79%   |
| 1.01-2.0   | 7         | 7.69%   |
| 5.01-6.0   | 4         | 4.4%    |
| 8.01-16.0  | 4         | 4.4%    |
| 3.01-4.0   | 3         | 3.3%    |
| 2.01-3.0   | 1         | 1.1%    |
| 16.01-24.0 | 1         | 1.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 12        | 12.5%   |
| BOE                     | 12        | 12.5%   |
| AU Optronics            | 9         | 9.38%   |
| Hewlett-Packard         | 8         | 8.33%   |
| LG Display              | 7         | 7.29%   |
| Dell                    | 7         | 7.29%   |
| Chimei Innolux          | 7         | 7.29%   |
| Goldstar                | 4         | 4.17%   |
| BenQ                    | 4         | 4.17%   |
| Lenovo                  | 3         | 3.13%   |
| Ancor Communications    | 3         | 3.13%   |
| Sharp                   | 2         | 2.08%   |
| AOC                     | 2         | 2.08%   |
| Acer                    | 2         | 2.08%   |
| Wacom                   | 1         | 1.04%   |
| Valve                   | 1         | 1.04%   |
| UGD                     | 1         | 1.04%   |
| Sony                    | 1         | 1.04%   |
| PANDA                   | 1         | 1.04%   |
| IOD                     | 1         | 1.04%   |
| Iiyama                  | 1         | 1.04%   |
| HKC                     | 1         | 1.04%   |
| GDH                     | 1         | 1.04%   |
| CTC                     | 1         | 1.04%   |
| Chi Mei Optoelectronics | 1         | 1.04%   |
| ASUSTek Computer        | 1         | 1.04%   |
| Apple                   | 1         | 1.04%   |
| Unknown                 | 1         | 1.04%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC416E 2880x1620 344x194mm 15.5-inch | 2         | 2.04%   |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch             | 2         | 2.04%   |
| Goldstar ULTRAGEAR GSM7765 2560x1440 697x392mm 31.5-inch              | 2         | 2.04%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 2         | 2.04%   |
| Wacom Cintiq 22HDT WAC1037 1920x1080 476x268mm 21.5-inch              | 1         | 1.02%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 1.02%   |
| UGD LCD Monitor UGD1302 1920x1080 290x160mm 13.0-inch                 | 1         | 1.02%   |
| Sony TV SNY8102 1360x768                                              | 1         | 1.02%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 382x215mm 17.3-inch               | 1         | 1.02%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 1.02%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch     | 1         | 1.02%   |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch   | 1         | 1.02%   |
| Samsung Electronics SyncMaster SAM03F2 1680x1050                      | 1         | 1.02%   |
| Samsung Electronics SyncMaster SAM03F0 1680x1050 433x271mm 20.1-inch  | 1         | 1.02%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 376x301mm 19.0-inch  | 1         | 1.02%   |
| Samsung Electronics SyncMaster SAM01AD 1600x1200 408x306mm 20.1-inch  | 1         | 1.02%   |
| Samsung Electronics SMS27A650 SAM082D 1920x1080 598x336mm 27.0-inch   | 1         | 1.02%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch    | 1         | 1.02%   |
| Samsung Electronics SM2333T SAM0736 1920x1080 477x268mm 21.5-inch     | 1         | 1.02%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch     | 1         | 1.02%   |
| Samsung Electronics LCD Monitor U28D590 3840x2160                     | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 1.02%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 1.02%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch          | 1         | 1.02%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch          | 1         | 1.02%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 1.02%   |
| LG Display LCD Monitor LGD0353 1366x768 345x194mm 15.6-inch           | 1         | 1.02%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch          | 1         | 1.02%   |
| LG Display LCD Monitor LGD028A 1366x768 344x194mm 15.5-inch           | 1         | 1.02%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch           | 1         | 1.02%   |
| Lenovo LEN L171 LEN24C9 1280x1024 337x270mm 17.0-inch                 | 1         | 1.02%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch               | 1         | 1.02%   |
| Lenovo LCD Monitor LEN4031 1280x800 304x190mm 14.1-inch               | 1         | 1.02%   |
| IOD LCD-GL211X IOD151D 1920x1080 458x258mm 20.7-inch                  | 1         | 1.02%   |
| Iiyama PL2783Q IVM661F 2560x1440 597x336mm 27.0-inch                  | 1         | 1.02%   |
| HKC LCD Monitor HKC36B1 1366x768 309x174mm 14.0-inch                  | 1         | 1.02%   |
| Hewlett-Packard Z24i HWP309E 1920x1200 518x324mm 24.1-inch            | 1         | 1.02%   |
| Hewlett-Packard x23LED HWP2912 1920x1080 509x286mm 23.0-inch          | 1         | 1.02%   |
| Hewlett-Packard P223 HPN3392 1920x1080 477x268mm 21.5-inch            | 1         | 1.02%   |
| Hewlett-Packard ALL-in-One HPN4021 1920x1080 476x268mm 21.5-inch      | 1         | 1.02%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 42        | 44.68%  |
| 1366x768 (WXGA)    | 13        | 13.83%  |
| 3840x2160 (4K)     | 5         | 5.32%   |
| 2560x1440 (QHD)    | 5         | 5.32%   |
| 1680x1050 (WSXGA+) | 4         | 4.26%   |
| 1280x1024 (SXGA)   | 4         | 4.26%   |
| 1920x1200 (WUXGA)  | 3         | 3.19%   |
| 2880x1620          | 2         | 2.13%   |
| 1600x900 (HD+)     | 2         | 2.13%   |
| 1440x900 (WXGA+)   | 2         | 2.13%   |
| 1360x768           | 2         | 2.13%   |
| 1280x800 (WXGA)    | 2         | 2.13%   |
| 800x1280           | 1         | 1.06%   |
| 3440x1440          | 1         | 1.06%   |
| 3200x1080          | 1         | 1.06%   |
| 2256x1504          | 1         | 1.06%   |
| 1920x1280          | 1         | 1.06%   |
| 1600x1200          | 1         | 1.06%   |
| 1024x768 (XGA)     | 1         | 1.06%   |
| Unknown            | 1         | 1.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 20        | 20.83%  |
| 27      | 9         | 9.38%   |
| 13      | 9         | 9.38%   |
| 14      | 8         | 8.33%   |
| 24      | 7         | 7.29%   |
| 17      | 7         | 7.29%   |
| 21      | 5         | 5.21%   |
| 31      | 3         | 3.13%   |
| 23      | 3         | 3.13%   |
| 22      | 3         | 3.13%   |
| 20      | 3         | 3.13%   |
| 19      | 3         | 3.13%   |
| 18      | 3         | 3.13%   |
| 16      | 3         | 3.13%   |
| Unknown | 3         | 3.13%   |
| 72      | 1         | 1.04%   |
| 52      | 1         | 1.04%   |
| 34      | 1         | 1.04%   |
| 12      | 1         | 1.04%   |
| 11      | 1         | 1.04%   |
| 10      | 1         | 1.04%   |
| 7       | 1         | 1.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 38        | 40%     |
| 501-600     | 17        | 17.89%  |
| 401-500     | 15        | 15.79%  |
| 351-400     | 9         | 9.47%   |
| 201-300     | 5         | 5.26%   |
| 601-700     | 4         | 4.21%   |
| Unknown     | 3         | 3.16%   |
| 701-800     | 1         | 1.05%   |
| 1501-2000   | 1         | 1.05%   |
| 1001-1500   | 1         | 1.05%   |
| 1-100       | 1         | 1.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 61        | 71.76%  |
| 16/10   | 12        | 14.12%  |
| 5/4     | 4         | 4.71%   |
| 4/3     | 2         | 2.35%   |
| 3/2     | 2         | 2.35%   |
| Unknown | 2         | 2.35%   |
| 21/9    | 1         | 1.18%   |
| 0.67    | 1         | 1.18%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 22        | 23.16%  |
| 81-90          | 16        | 16.84%  |
| 201-250        | 12        | 12.63%  |
| 301-350        | 9         | 9.47%   |
| 151-200        | 9         | 9.47%   |
| 121-130        | 5         | 5.26%   |
| 351-500        | 4         | 4.21%   |
| 141-150        | 4         | 4.21%   |
| 251-300        | 3         | 3.16%   |
| Unknown        | 3         | 3.16%   |
| More than 1000 | 2         | 2.11%   |
| 51-60          | 2         | 2.11%   |
| 71-80          | 1         | 1.05%   |
| 61-70          | 1         | 1.05%   |
| 1-40           | 1         | 1.05%   |
| 111-120        | 1         | 1.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 32        | 34.41%  |
| 121-160       | 28        | 30.11%  |
| 101-120       | 21        | 22.58%  |
| 161-240       | 6         | 6.45%   |
| Unknown       | 3         | 3.23%   |
| 1-50          | 2         | 2.15%   |
| More than 240 | 1         | 1.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 73        | 80.22%  |
| 2     | 10        | 10.99%  |
| 0     | 6         | 6.59%   |
| 4     | 1         | 1.1%    |
| 3     | 1         | 1.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 50        | 37.04%  |
| Intel                    | 48        | 35.56%  |
| Qualcomm Atheros         | 6         | 4.44%   |
| Broadcom                 | 6         | 4.44%   |
| MediaTek                 | 4         | 2.96%   |
| Broadcom Limited         | 4         | 2.96%   |
| Ralink Technology        | 3         | 2.22%   |
| Nvidia                   | 3         | 2.22%   |
| ASIX Electronics         | 3         | 2.22%   |
| TP-Link                  | 1         | 0.74%   |
| Sitecom Europe           | 1         | 0.74%   |
| Ralink                   | 1         | 0.74%   |
| Qualcomm                 | 1         | 0.74%   |
| Marvell Technology Group | 1         | 0.74%   |
| Huawei Technologies      | 1         | 0.74%   |
| Hewlett-Packard          | 1         | 0.74%   |
| Dell                     | 1         | 0.74%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 33        | 20.37%  |
| Intel Wi-Fi 6 AX200                                               | 6         | 3.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 3.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 3.09%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5         | 3.09%   |
| Intel Wireless 8265 / 8275                                        | 4         | 2.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 2.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.85%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.85%   |
| Ralink MT7601U Wireless Adapter                                   | 3         | 1.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 1.85%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 2         | 1.23%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 1.23%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 1.23%   |
| Nvidia MCP61 Ethernet                                             | 2         | 1.23%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 2         | 1.23%   |
| Intel Wireless 8260                                               | 2         | 1.23%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.23%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 1.23%   |
| Intel Ethernet Controller I225-V                                  | 2         | 1.23%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.23%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.23%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 1.23%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.23%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 1.23%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 2         | 1.23%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                           | 2         | 1.23%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.23%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 0.62%   |
| Sitecom Europe WL-113 rev 2 Wireless Network USB Adapter          | 1         | 0.62%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.62%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.62%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.62%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.62%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.62%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.62%   |
| Realtek Realtek WLAN controller                                   | 1         | 0.62%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 1         | 0.62%   |
| Qualcomm Redmi Note 8                                             | 1         | 0.62%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 36        | 52.17%  |
| Realtek Semiconductor | 13        | 18.84%  |
| Qualcomm Atheros      | 4         | 5.8%    |
| MediaTek              | 4         | 5.8%    |
| Ralink Technology     | 3         | 4.35%   |
| Broadcom Limited      | 3         | 4.35%   |
| Broadcom              | 2         | 2.9%    |
| TP-Link               | 1         | 1.45%   |
| Sitecom Europe        | 1         | 1.45%   |
| Ralink                | 1         | 1.45%   |
| Dell                  | 1         | 1.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                   | 6         | 8.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter              | 5         | 7.14%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                | 5         | 7.14%   |
| Intel Wireless 8265 / 8275                                            | 4         | 5.71%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter              | 3         | 4.29%   |
| Ralink MT7601U Wireless Adapter                                       | 3         | 4.29%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                          | 3         | 4.29%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                               | 2         | 2.86%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter         | 2         | 2.86%   |
| Intel Wireless 8260                                                   | 2         | 2.86%   |
| Intel Wi-Fi 6 AX201                                                   | 2         | 2.86%   |
| Intel Tiger Lake PCH CNVi WiFi                                        | 2         | 2.86%   |
| Intel Alder Lake-P PCH CNVi WiFi                                      | 2         | 2.86%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                               | 2         | 2.86%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                           | 1         | 1.43%   |
| Sitecom Europe WL-113 rev 2 Wireless Network USB Adapter              | 1         | 1.43%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                    | 1         | 1.43%   |
| Realtek RTL8723DE Wireless Network Adapter                            | 1         | 1.43%   |
| Realtek RTL8191SEvB Wireless LAN Controller                           | 1         | 1.43%   |
| Realtek Realtek WLAN controller                                       | 1         | 1.43%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                             | 1         | 1.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                      | 1         | 1.43%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                      | 1         | 1.43%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)        | 1         | 1.43%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                      | 1         | 1.43%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                               | 1         | 1.43%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter         | 1         | 1.43%   |
| Intel Wireless-AC 9260                                                | 1         | 1.43%   |
| Intel Wireless 7260                                                   | 1         | 1.43%   |
| Intel Wireless 3165                                                   | 1         | 1.43%   |
| Intel Wi-Fi 6 AX201 160MHz                                            | 1         | 1.43%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection         | 1         | 1.43%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                      | 1         | 1.43%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                       | 1         | 1.43%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                     | 1         | 1.43%   |
| Intel Comet Lake PCH CNVi WiFi                                        | 1         | 1.43%   |
| Intel Centrino Ultimate-N 6300                                        | 1         | 1.43%   |
| Dell Wireless 1450 Dual-band (802.11a/b/g) Adapter [Intersil ISL3887] | 1         | 1.43%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                               | 1         | 1.43%   |
| Broadcom BCM4331 802.11a/b/g/n                                        | 1         | 1.43%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 45        | 50.56%  |
| Intel                    | 26        | 29.21%  |
| Broadcom                 | 5         | 5.62%   |
| Qualcomm Atheros         | 3         | 3.37%   |
| Nvidia                   | 3         | 3.37%   |
| ASIX Electronics         | 3         | 3.37%   |
| Qualcomm                 | 1         | 1.12%   |
| Marvell Technology Group | 1         | 1.12%   |
| Huawei Technologies      | 1         | 1.12%   |
| Broadcom Limited         | 1         | 1.12%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 33        | 36.26%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 5.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 4.4%    |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 3.3%    |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 2.2%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 2.2%    |
| Nvidia MCP61 Ethernet                                             | 2         | 2.2%    |
| Intel Ethernet Controller I225-V                                  | 2         | 2.2%    |
| Intel Ethernet Connection I219-LM                                 | 2         | 2.2%    |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.2%    |
| Intel 82577LM Gigabit Network Connection                          | 2         | 2.2%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 2.2%    |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 2         | 2.2%    |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 2.2%    |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 1.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.1%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.1%    |
| Qualcomm Redmi Note 8                                             | 1         | 1.1%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.1%    |
| Nvidia MCP79 Ethernet                                             | 1         | 1.1%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.1%    |
| Intel I350 Gigabit Network Connection                             | 1         | 1.1%    |
| Intel I211 Gigabit Network Connection                             | 1         | 1.1%    |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.1%    |
| Intel Ethernet Connection (5) I219-V                              | 1         | 1.1%    |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.1%    |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.1%    |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 1.1%    |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.1%    |
| Intel Ethernet Connection (12) I219-V                             | 1         | 1.1%    |
| Intel 82576 Gigabit Network Connection                            | 1         | 1.1%    |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.1%    |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.1%    |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1         | 1.1%    |
| Huawei E353/E3131                                                 | 1         | 1.1%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.1%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1         | 1.1%    |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 1         | 1.1%    |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 1         | 1.1%    |
| ASIX AX88772A Fast Ethernet                                       | 1         | 1.1%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 82        | 54.3%   |
| WiFi     | 68        | 45.03%  |
| Modem    | 1         | 0.66%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 52        | 53.06%  |
| Ethernet | 46        | 46.94%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 48        | 52.17%  |
| 1     | 39        | 42.39%  |
| 4     | 2         | 2.17%   |
| 3     | 2         | 2.17%   |
| 5     | 1         | 1.09%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 77        | 83.7%   |
| Yes  | 15        | 16.3%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 31        | 51.67%  |
| Realtek Semiconductor    | 8         | 13.33%  |
| Cambridge Silicon Radio  | 5         | 8.33%   |
| Broadcom                 | 5         | 8.33%   |
| IMC Networks             | 4         | 6.67%   |
| MediaTek                 | 2         | 3.33%   |
| Apple                    | 2         | 3.33%   |
| TP-Link                  | 1         | 1.67%   |
| Micro Star International | 1         | 1.67%   |
| Foxconn / Hon Hai        | 1         | 1.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 9         | 15%     |
| Intel AX201 Bluetooth                               | 7         | 11.67%  |
| Intel AX200 Bluetooth                               | 6         | 10%     |
| Intel AX210 Bluetooth                               | 5         | 8.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5         | 8.33%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 6.67%   |
| Realtek Bluetooth Radio                             | 4         | 6.67%   |
| IMC Networks Wireless_Device                        | 3         | 5%      |
| MediaTek Wireless_Device                            | 2         | 3.33%   |
| TP-Link UB5A Adapter                                | 1         | 1.67%   |
| Micro Star International Bluetooth Dongle           | 1         | 1.67%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.67%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.67%   |
| Intel Bluetooth Device                              | 1         | 1.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 1.67%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.67%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 1.67%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.67%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.67%   |
| Broadcom BCM20702A0                                 | 1         | 1.67%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.67%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 1.67%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.67%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 1         | 1.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 55        | 41.67%  |
| Nvidia                 | 32        | 24.24%  |
| AMD                    | 32        | 24.24%  |
| Creative Labs          | 4         | 3.03%   |
| C-Media Electronics    | 2         | 1.52%   |
| ASUSTek Computer       | 2         | 1.52%   |
| Texas Instruments      | 1         | 0.76%   |
| RME                    | 1         | 0.76%   |
| Kingston Technology    | 1         | 0.76%   |
| Holtek Semiconductor   | 1         | 0.76%   |
| Generalplus Technology | 1         | 0.76%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 12        | 7.69%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 7         | 4.49%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 6         | 3.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 3.85%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 3.85%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 3.85%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 3.21%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 5         | 3.21%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 2.56%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 2.56%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.92%   |
| Nvidia MCP61 High Definition Audio                                                                | 3         | 1.92%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.92%   |
| Nvidia Audio device                                                                               | 3         | 1.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.92%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.92%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 1.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.92%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 3         | 1.92%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 3         | 1.92%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 1.28%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 1.28%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 1.28%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 1.28%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 2         | 1.28%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.28%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.28%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2         | 1.28%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.28%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 1.28%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus]   | 2         | 1.28%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 1.28%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.28%   |
| AMD Navi 10 HDMI Audio                                                                            | 2         | 1.28%   |
| AMD FCH Azalia Controller                                                                         | 2         | 1.28%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.64%   |
| RME ADI-2 DAC (58825307)                                                                          | 1         | 0.64%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.64%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 17        | 17.89%  |
| SK hynix            | 16        | 16.84%  |
| Kingston            | 16        | 16.84%  |
| Corsair             | 9         | 9.47%   |
| Crucial             | 6         | 6.32%   |
| Micron Technology   | 5         | 5.26%   |
| Unknown             | 3         | 3.16%   |
| G.Skill             | 3         | 3.16%   |
| Team                | 2         | 2.11%   |
| GOODRAM             | 2         | 2.11%   |
| AMD                 | 2         | 2.11%   |
| A-DATA Technology   | 2         | 2.11%   |
| Unknown             | 2         | 2.11%   |
| Transcend           | 1         | 1.05%   |
| Strontium           | 1         | 1.05%   |
| Smart               | 1         | 1.05%   |
| Silicon Power       | 1         | 1.05%   |
| Patriot             | 1         | 1.05%   |
| Neo Forza           | 1         | 1.05%   |
| Nanya Technology    | 1         | 1.05%   |
| Innodisk            | 1         | 1.05%   |
| GLOWAY              | 1         | 1.05%   |
| Essencore Limited   | 1         | 1.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                             | 2         | 1.96%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 2         | 1.96%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.96%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.96%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 2         | 1.96%   |
| Corsair RAM CMSX32GX4M2A2666C18 16GB SODIMM DDR4 2667MT/s        | 2         | 1.96%   |
| Unknown                                                          | 2         | 1.96%   |
| Unknown RAM Module 2GB DIMM DDR2 533MT/s                         | 1         | 0.98%   |
| Transcend RAM JM1600KLN-8GK 4096MB DIMM DDR3 1600MT/s            | 1         | 0.98%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3733MT/s              | 1         | 0.98%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s               | 1         | 0.98%   |
| Strontium RAM SRT4G86U1-P9H 4096MB DIMM DDR3 1333MT/s            | 1         | 0.98%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s              | 1         | 0.98%   |
| SK hynix RAM HYMP512F72CP8N3-Y5 1024MB FB-DIMM DDR2 667MT/s      | 1         | 0.98%   |
| SK hynix RAM HMT41GV7BMR4A-H9 16GB DIMM 1333MT/s                 | 1         | 0.98%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.98%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s             | 1         | 0.98%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.98%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.98%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.98%   |
| SK hynix RAM HMT31GR7BFR4A-H9 8192MB DIMM 1333MT/s               | 1         | 0.98%   |
| SK hynix RAM HMT125R7BFR8C-H9 2GB DIMM 1333MT/s                  | 1         | 0.98%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.98%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.98%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 0.98%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.98%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 0.98%   |
| SK hynix RAM HMA81GR7CJR8N-XN 8192MB DIMM DDR4 3200MT/s          | 1         | 0.98%   |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 0.98%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB SODIMM LPDDR3 1867MT/s           | 1         | 0.98%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB Chip LPDDR3 1867MT/s             | 1         | 0.98%   |
| Silicon Power RAM DCLT4GN568S V 4096MB DIMM DDR3 1600MT/s        | 1         | 0.98%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 0.98%   |
| Samsung RAM M471B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.98%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 0.98%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.98%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 0.98%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s            | 1         | 0.98%   |
| Samsung RAM M395T5663QZ4-CE66 2048MB FB-DIMM DDR2 667MT/s        | 1         | 0.98%   |
| Samsung RAM M393A2G40DB0-CPB 16GB RIMM DDR4 2133MT/s             | 1         | 0.98%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 42        | 53.16%  |
| DDR3    | 22        | 27.85%  |
| DDR2    | 4         | 5.06%   |
| LPDDR5  | 3         | 3.8%    |
| SDRAM   | 2         | 2.53%   |
| LPDDR3  | 2         | 2.53%   |
| DDR5    | 2         | 2.53%   |
| LPDDR4  | 1         | 1.27%   |
| Unknown | 1         | 1.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 38        | 47.5%   |
| DIMM         | 34        | 42.5%   |
| Row Of Chips | 5         | 6.25%   |
| RIMM         | 1         | 1.25%   |
| FB-DIMM      | 1         | 1.25%   |
| Chip         | 1         | 1.25%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 37        | 42.05%  |
| 4096  | 25        | 28.41%  |
| 16384 | 14        | 15.91%  |
| 2048  | 6         | 6.82%   |
| 32768 | 4         | 4.55%   |
| 1024  | 2         | 2.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 19        | 21.59%  |
| 1600    | 17        | 19.32%  |
| 2667    | 8         | 9.09%   |
| 2400    | 7         | 7.95%   |
| 3600    | 4         | 4.55%   |
| 1333    | 4         | 4.55%   |
| 3800    | 3         | 3.41%   |
| 6400    | 2         | 2.27%   |
| 4800    | 2         | 2.27%   |
| 2133    | 2         | 2.27%   |
| 1867    | 2         | 2.27%   |
| 667     | 2         | 2.27%   |
| Unknown | 2         | 2.27%   |
| 65535   | 1         | 1.14%   |
| 4267    | 1         | 1.14%   |
| 4266    | 1         | 1.14%   |
| 3733    | 1         | 1.14%   |
| 3400    | 1         | 1.14%   |
| 2933    | 1         | 1.14%   |
| 2800    | 1         | 1.14%   |
| 2472    | 1         | 1.14%   |
| 2187    | 1         | 1.14%   |
| 1866    | 1         | 1.14%   |
| 1334    | 1         | 1.14%   |
| 975     | 1         | 1.14%   |
| 701     | 1         | 1.14%   |
| 533     | 1         | 1.14%   |

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
| Canon LiDE 300               | 1         | 20%     |
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
| Chicony Electronics                    | 13        | 22.81%  |
| Logitech                               | 8         | 14.04%  |
| Microdia                               | 5         | 8.77%   |
| Bison Electronics                      | 5         | 8.77%   |
| Realtek Semiconductor                  | 4         | 7.02%   |
| Syntek                                 | 3         | 5.26%   |
| Sonix Technology                       | 3         | 5.26%   |
| Luxvisions Innotech Limited            | 3         | 5.26%   |
| Samsung Electronics                    | 2         | 3.51%   |
| Quanta                                 | 2         | 3.51%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.51%   |
| Acer                                   | 2         | 3.51%   |
| Z-Star Microelectronics                | 1         | 1.75%   |
| Sunplus Innovation Technology          | 1         | 1.75%   |
| Microsoft                              | 1         | 1.75%   |
| Lenovo                                 | 1         | 1.75%   |
| Apple                                  | 1         | 1.75%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Logitech Webcam C270                                 | 3         | 5.26%   |
| Chicony Integrated Camera                            | 3         | 5.26%   |
| Bison HD Webcam                                      | 3         | 5.26%   |
| Syntek Integrated Camera                             | 2         | 3.51%   |
| Sonix USB2.0 FHD UVC WebCam                          | 2         | 3.51%   |
| Samsung Galaxy series, misc. (MTP mode)              | 2         | 3.51%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 2         | 3.51%   |
| Chicony HD User Facing                               | 2         | 3.51%   |
| Acer BisonCam,NB Pro                                 | 2         | 3.51%   |
| Z-Star Vimicro USB2.0 Camera                         | 1         | 1.75%   |
| Syntek USB2.0 Camera                                 | 1         | 1.75%   |
| Sunplus Integrated_Webcam_HD                         | 1         | 1.75%   |
| Sonix USB2.0 HD UVC WebCam                           | 1         | 1.75%   |
| Realtek Laptop Camera                                | 1         | 1.75%   |
| Realtek Integrated Camera                            | 1         | 1.75%   |
| Realtek EasyCamera                                   | 1         | 1.75%   |
| Realtek Bluetooth Radio                              | 1         | 1.75%   |
| Quanta HP Wide Vision HD Camera                      | 1         | 1.75%   |
| Quanta HP Webcam                                     | 1         | 1.75%   |
| Microsoft LifeCam HD-3000                            | 1         | 1.75%   |
| Microdia Laptop_Integrated_Webcam_2M                 | 1         | 1.75%   |
| Microdia Integrated_Webcam_HD                        | 1         | 1.75%   |
| Microdia Integrated Webcam                           | 1         | 1.75%   |
| Microdia Dell Integrated HD Webcam                   | 1         | 1.75%   |
| Microdia Camera                                      | 1         | 1.75%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.75%   |
| Logitech QuickCam Pro 9000                           | 1         | 1.75%   |
| Logitech Logitech Webcam C160                        | 1         | 1.75%   |
| Logitech HD Webcam C910                              | 1         | 1.75%   |
| Logitech HD Pro Webcam C920                          | 1         | 1.75%   |
| Logitech C922 Pro Stream Webcam                      | 1         | 1.75%   |
| Lenovo Integrated Webcam [R5U877]                    | 1         | 1.75%   |
| Chicony Web Camera - FHD                             | 1         | 1.75%   |
| Chicony USB 2.0 Camera                               | 1         | 1.75%   |
| Chicony Integrated Camera [ThinkPad]                 | 1         | 1.75%   |
| Chicony HP TrueVision HD Camera                      | 1         | 1.75%   |
| Chicony HP True Vision 5MP Camera                    | 1         | 1.75%   |
| Chicony HP HD Webcam [Fixed]                         | 1         | 1.75%   |
| Chicony HP HD Camera                                 | 1         | 1.75%   |
| Chicony FJ Camera                                    | 1         | 1.75%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 6         | 42.86%  |
| Synaptics                          | 3         | 21.43%  |
| Realtek USB2.0 Finger Print Bridge | 2         | 14.29%  |
| STMicroelectronics                 | 1         | 7.14%   |
| Shenzhen Goodix Technology         | 1         | 7.14%   |
| Elan Microelectronics              | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                                 | 3         | 21.43%  |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 2         | 14.29%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 1         | 7.14%   |
| Validity Sensors VFS451 Fingerprint Reader                      | 1         | 7.14%   |
| Validity Sensors VFS300 Fingerprint Reader                      | 1         | 7.14%   |
| Synaptics WBDI Device                                           | 1         | 7.14%   |
| Synaptics UWP WBDI                                              | 1         | 7.14%   |
| STMicroelectronics Fingerprint Reader                           | 1         | 7.14%   |
| Shenzhen Goodix  FingerPrint Device                             | 1         | 7.14%   |
| Elan ELAN:ARM-M4                                                | 1         | 7.14%   |
| Unknown                                                         | 1         | 7.14%   |

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
| 0     | 57        | 61.96%  |
| 1     | 23        | 25%     |
| 2     | 7         | 7.61%   |
| 4     | 2         | 2.17%   |
| 3     | 2         | 2.17%   |
| 5     | 1         | 1.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 14        | 25.45%  |
| Sound                    | 8         | 14.55%  |
| Graphics card            | 8         | 14.55%  |
| Net/wireless             | 5         | 9.09%   |
| Multimedia controller    | 4         | 7.27%   |
| Unassigned class         | 3         | 5.45%   |
| Communication controller | 3         | 5.45%   |
| Chipcard                 | 3         | 5.45%   |
| Camera                   | 3         | 5.45%   |
| Storage/raid             | 1         | 1.82%   |
| Storage/ide              | 1         | 1.82%   |
| Net/ethernet             | 1         | 1.82%   |
| Bluetooth                | 1         | 1.82%   |

