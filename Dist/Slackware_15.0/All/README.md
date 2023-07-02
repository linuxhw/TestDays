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

Total: 100

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.19           | 19        | 21.84%  |
| 5.19.17           | 6         | 6.9%    |
| 5.15.63           | 5         | 5.75%   |
| 5.15.27           | 4         | 4.6%    |
| 5.19.17-Unraid    | 3         | 3.45%   |
| 5.15.38           | 3         | 3.45%   |
| 5.17.2            | 2         | 2.3%    |
| 5.17.1            | 2         | 2.3%    |
| 5.16.13           | 2         | 2.3%    |
| 5.15.94           | 2         | 2.3%    |
| 5.15.80           | 2         | 2.3%    |
| 5.15.30-Unraid    | 2         | 2.3%    |
| 5.13.8            | 2         | 2.3%    |
| 6.1.27            | 1         | 1.15%   |
| 6.1.20            | 1         | 1.15%   |
| 6.1.13            | 1         | 1.15%   |
| 6.1.12            | 1         | 1.15%   |
| 6.1.1             | 1         | 1.15%   |
| 5.19.16           | 1         | 1.15%   |
| 5.17.5            | 1         | 1.15%   |
| 5.17.0-custom     | 1         | 1.15%   |
| 5.16.9-joe1       | 1         | 1.15%   |
| 5.16.18           | 1         | 1.15%   |
| 5.16.12           | 1         | 1.15%   |
| 5.16.11           | 1         | 1.15%   |
| 5.15.78.a         | 1         | 1.15%   |
| 5.15.6            | 1         | 1.15%   |
| 5.15.37.a         | 1         | 1.15%   |
| 5.15.33.kjh       | 1         | 1.15%   |
| 5.15.21-hardened1 | 1         | 1.15%   |
| 5.15.14           | 1         | 1.15%   |
| 5.15.13           | 1         | 1.15%   |
| 5.15.103          | 1         | 1.15%   |
| 5.15.1            | 1         | 1.15%   |
| 5.14.9            | 1         | 1.15%   |
| 5.14.8            | 1         | 1.15%   |
| 5.14.15-Unraid    | 1         | 1.15%   |
| 5.14.15           | 1         | 1.15%   |
| 5.14.12           | 1         | 1.15%   |
| 5.14.11           | 1         | 1.15%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.19  | 19        | 21.84%  |
| 5.19.17  | 9         | 10.34%  |
| 5.15.63  | 5         | 5.75%   |
| 5.15.27  | 4         | 4.6%    |
| 5.15.38  | 3         | 3.45%   |
| 5.17.2   | 2         | 2.3%    |
| 5.17.1   | 2         | 2.3%    |
| 5.16.13  | 2         | 2.3%    |
| 5.15.94  | 2         | 2.3%    |
| 5.15.80  | 2         | 2.3%    |
| 5.15.30  | 2         | 2.3%    |
| 5.14.15  | 2         | 2.3%    |
| 5.13.8   | 2         | 2.3%    |
| 6.1.27   | 1         | 1.15%   |
| 6.1.20   | 1         | 1.15%   |
| 6.1.13   | 1         | 1.15%   |
| 6.1.12   | 1         | 1.15%   |
| 6.1.1    | 1         | 1.15%   |
| 5.19.16  | 1         | 1.15%   |
| 5.17.5   | 1         | 1.15%   |
| 5.17.0   | 1         | 1.15%   |
| 5.16.9   | 1         | 1.15%   |
| 5.16.18  | 1         | 1.15%   |
| 5.16.12  | 1         | 1.15%   |
| 5.16.11  | 1         | 1.15%   |
| 5.15.78  | 1         | 1.15%   |
| 5.15.6   | 1         | 1.15%   |
| 5.15.37  | 1         | 1.15%   |
| 5.15.33  | 1         | 1.15%   |
| 5.15.21  | 1         | 1.15%   |
| 5.15.14  | 1         | 1.15%   |
| 5.15.13  | 1         | 1.15%   |
| 5.15.103 | 1         | 1.15%   |
| 5.15.1   | 1         | 1.15%   |
| 5.14.9   | 1         | 1.15%   |
| 5.14.8   | 1         | 1.15%   |
| 5.14.12  | 1         | 1.15%   |
| 5.14.11  | 1         | 1.15%   |
| 5.14.10  | 1         | 1.15%   |
| 5.14.0   | 1         | 1.15%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 46        | 54.12%  |
| 5.19    | 10        | 11.76%  |
| 5.14    | 7         | 8.24%   |
| 5.17    | 6         | 7.06%   |
| 5.16    | 6         | 7.06%   |
| 5.13    | 5         | 5.88%   |
| 6.1     | 4         | 4.71%   |
| 5.10    | 1         | 1.18%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 82        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE5       | 36        | 42.86%  |
| XFCE       | 22        | 26.19%  |
| Unknown    | 14        | 16.67%  |
| GNOME      | 3         | 3.57%   |
| xwmconfig  | 2         | 2.38%   |
| X-Generic  | 1         | 1.19%   |
| X-Cinnamon | 1         | 1.19%   |
| MATE       | 1         | 1.19%   |
| KDE        | 1         | 1.19%   |
| FVWM       | 1         | 1.19%   |
| awesome    | 1         | 1.19%   |
| 2bwm       | 1         | 1.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 46        | 53.49%  |
| Tty     | 29        | 33.72%  |
| Wayland | 6         | 6.98%   |
| Unknown | 5         | 5.81%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 44        | 52.38%  |
| Unknown | 24        | 28.57%  |
| XDM     | 10        | 11.9%   |
| LightDM | 4         | 4.76%   |
| SLiM    | 1         | 1.19%   |
| GDM     | 1         | 1.19%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 53        | 64.63%  |
| Unknown     | 10        | 12.2%   |
| pt_BR       | 3         | 3.66%   |
| it_IT       | 3         | 3.66%   |
| de_DE       | 3         | 3.66%   |
| ru_RU       | 2         | 2.44%   |
| fr_FR       | 2         | 2.44%   |
| en_GB       | 2         | 2.44%   |
| pt_PT       | 1         | 1.22%   |
| es_ES.UTF8  | 1         | 1.22%   |
| es_ES       | 1         | 1.22%   |
| en_US.ASCII | 1         | 1.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 45        | 54.88%  |
| BIOS | 37        | 45.12%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 58        | 70.73%  |
| Btrfs   | 9         | 10.98%  |
| Xfs     | 5         | 6.1%    |
| Overlay | 5         | 6.1%    |
| Zfs     | 1         | 1.22%   |
| Tmpfs   | 1         | 1.22%   |
| Rootfs  | 1         | 1.22%   |
| F2fs    | 1         | 1.22%   |
| Ext2    | 1         | 1.22%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 57        | 68.67%  |
| MBR     | 14        | 16.87%  |
| Unknown | 12        | 14.46%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 59        | 70.24%  |
| Yes       | 25        | 29.76%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 56        | 68.29%  |
| Yes       | 26        | 31.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 15        | 18.29%  |
| MSI                 | 12        | 14.63%  |
| Lenovo              | 10        | 12.2%   |
| ASUSTek Computer    | 10        | 12.2%   |
| Dell                | 8         | 9.76%   |
| ASRock              | 7         | 8.54%   |
| Acer                | 3         | 3.66%   |
| Gigabyte Technology | 2         | 2.44%   |
| Fujitsu             | 2         | 2.44%   |
| Apple               | 2         | 2.44%   |
| Valve               | 1         | 1.22%   |
| TYAN Computer       | 1         | 1.22%   |
| System76            | 1         | 1.22%   |
| Sony                | 1         | 1.22%   |
| Notebook            | 1         | 1.22%   |
| Microsoft           | 1         | 1.22%   |
| HEDYCOMPUTER        | 1         | 1.22%   |
| Framework           | 1         | 1.22%   |
| Dynabook            | 1         | 1.22%   |
| Biostar             | 1         | 1.22%   |
| Unknown             | 1         | 1.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| ASUS VivoBook_ASUSLaptop K6500ZE_K6500ZE | 2         | 2.44%   |
| ASRock N68-S3 FX                         | 2         | 2.44%   |
| Valve Jupiter                            | 1         | 1.22%   |
| TYAN S7012                               | 1         | 1.22%   |
| System76 Oryx Pro                        | 1         | 1.22%   |
| Sony SVE1713A1EW                         | 1         | 1.22%   |
| Notebook X170KM-G                        | 1         | 1.22%   |
| MSI MS-7C52                              | 1         | 1.22%   |
| MSI MS-7C02                              | 1         | 1.22%   |
| MSI MS-7996                              | 1         | 1.22%   |
| MSI MS-7885                              | 1         | 1.22%   |
| MSI MS-7788                              | 1         | 1.22%   |
| MSI MS-7693                              | 1         | 1.22%   |
| MSI MS-7529                              | 1         | 1.22%   |
| MSI MS-7365                              | 1         | 1.22%   |
| MSI Modern 14 B11MO                      | 1         | 1.22%   |
| MSI Modern 14 B10MW                      | 1         | 1.22%   |
| MSI GP76 Leopard 11UG                    | 1         | 1.22%   |
| MSI GE76 Raider 11UE                     | 1         | 1.22%   |
| Microsoft Surface Go 3                   | 1         | 1.22%   |
| Lenovo ThinkPad X230 2325P38             | 1         | 1.22%   |
| Lenovo ThinkPad X140e 20BMS03E00         | 1         | 1.22%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS04300 | 1         | 1.22%   |
| Lenovo ThinkPad T61 765912G              | 1         | 1.22%   |
| Lenovo ThinkPad T470p 20J60018MS         | 1         | 1.22%   |
| Lenovo ThinkPad T470 20JNS01R01          | 1         | 1.22%   |
| Lenovo ThinkPad T410 2518C3U             | 1         | 1.22%   |
| Lenovo ThinkPad Edge E530c 336669G       | 1         | 1.22%   |
| Lenovo IdeaPad 310-15ISK 80SM            | 1         | 1.22%   |
| Lenovo H50-05 90BH001WIX                 | 1         | 1.22%   |
| HP Z440 Workstation                      | 1         | 1.22%   |
| HP xw8400 Workstation                    | 1         | 1.22%   |
| HP ProBook 6570b                         | 1         | 1.22%   |
| HP Pavilion Gaming Laptop 16-a0xxx       | 1         | 1.22%   |
| HP Pavilion Gaming Laptop 15-ec1xxx      | 1         | 1.22%   |
| HP Pavilion Gaming Desktop TG01-2xxx     | 1         | 1.22%   |
| HP OMEN by Laptop 17-ck0xxx              | 1         | 1.22%   |
| HP OMEN by Laptop 16-b1xxx               | 1         | 1.22%   |
| HP Laptop 15-bs1xx                       | 1         | 1.22%   |
| HP ENVY Laptop 17-cr0xxx                 | 1         | 1.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 8         | 9.76%   |
| HP Pavilion            | 3         | 3.66%   |
| ASUS ROG               | 3         | 3.66%   |
| MSI Modern             | 2         | 2.44%   |
| HP OMEN                | 2         | 2.44%   |
| HP EliteBook           | 2         | 2.44%   |
| Dell Precision         | 2         | 2.44%   |
| Dell OptiPlex          | 2         | 2.44%   |
| ASUS VivoBook          | 2         | 2.44%   |
| ASUS TUF               | 2         | 2.44%   |
| ASUS PRIME             | 2         | 2.44%   |
| ASRock N68-S3          | 2         | 2.44%   |
| Valve Jupiter          | 1         | 1.22%   |
| TYAN S7012             | 1         | 1.22%   |
| System76 Oryx          | 1         | 1.22%   |
| Sony SVE1713A1EW       | 1         | 1.22%   |
| Notebook X170KM-G      | 1         | 1.22%   |
| MSI MS-7C52            | 1         | 1.22%   |
| MSI MS-7C02            | 1         | 1.22%   |
| MSI MS-7996            | 1         | 1.22%   |
| MSI MS-7885            | 1         | 1.22%   |
| MSI MS-7788            | 1         | 1.22%   |
| MSI MS-7693            | 1         | 1.22%   |
| MSI MS-7529            | 1         | 1.22%   |
| MSI MS-7365            | 1         | 1.22%   |
| MSI GP76               | 1         | 1.22%   |
| MSI GE76               | 1         | 1.22%   |
| Microsoft Surface      | 1         | 1.22%   |
| Lenovo IdeaPad         | 1         | 1.22%   |
| Lenovo H50-05          | 1         | 1.22%   |
| HP Z440                | 1         | 1.22%   |
| HP xw8400              | 1         | 1.22%   |
| HP ProBook             | 1         | 1.22%   |
| HP Laptop              | 1         | 1.22%   |
| HP ENVY                | 1         | 1.22%   |
| HP Compaq              | 1         | 1.22%   |
| HP 245                 | 1         | 1.22%   |
| HP 205                 | 1         | 1.22%   |
| HEDYCOMPUTER IH81MF-Q3 | 1         | 1.22%   |
| Gigabyte N3160TN       | 1         | 1.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 11        | 13.41%  |
| 2020 | 11        | 13.41%  |
| 2022 | 7         | 8.54%   |
| 2017 | 7         | 8.54%   |
| 2019 | 6         | 7.32%   |
| 2015 | 6         | 7.32%   |
| 2012 | 6         | 7.32%   |
| 2011 | 6         | 7.32%   |
| 2018 | 4         | 4.88%   |
| 2014 | 3         | 3.66%   |
| 2010 | 3         | 3.66%   |
| 2009 | 3         | 3.66%   |
| 2008 | 3         | 3.66%   |
| 2007 | 3         | 3.66%   |
| 2016 | 2         | 2.44%   |
| 2013 | 1         | 1.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 39        | 47.56%  |
| Desktop    | 37        | 45.12%  |
| All in one | 2         | 2.44%   |
| Server     | 2         | 2.44%   |
| Tablet     | 1         | 1.22%   |
| Mini pc    | 1         | 1.22%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 82        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 80        | 97.56%  |
| Yes  | 2         | 2.44%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 20        | 24.1%   |
| 3.01-4.0    | 14        | 16.87%  |
| 8.01-16.0   | 14        | 16.87%  |
| 4.01-8.0    | 12        | 14.46%  |
| 32.01-64.0  | 10        | 12.05%  |
| 64.01-256.0 | 6         | 7.23%   |
| 24.01-32.0  | 4         | 4.82%   |
| 1.01-2.0    | 3         | 3.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 23        | 26.74%  |
| 1.01-2.0   | 21        | 24.42%  |
| 4.01-8.0   | 18        | 20.93%  |
| 0.51-1.0   | 10        | 11.63%  |
| 3.01-4.0   | 5         | 5.81%   |
| 16.01-24.0 | 3         | 3.49%   |
| 0.01-0.5   | 3         | 3.49%   |
| 8.01-16.0  | 2         | 2.33%   |
| 32.01-64.0 | 1         | 1.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 41        | 48.81%  |
| 2      | 22        | 26.19%  |
| 3      | 9         | 10.71%  |
| 4      | 5         | 5.95%   |
| 6      | 4         | 4.76%   |
| 11     | 1         | 1.19%   |
| 9      | 1         | 1.19%   |
| 0      | 1         | 1.19%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 53        | 63.86%  |
| Yes       | 30        | 36.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 90.24%  |
| No        | 8         | 9.76%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 60        | 72.29%  |
| No        | 23        | 27.71%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 63.41%  |
| No        | 30        | 36.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 20        | 24.39%  |
| Kazakhstan   | 6         | 7.32%   |
| Italy        | 6         | 7.32%   |
| Brazil       | 6         | 7.32%   |
| Germany      | 5         | 6.1%    |
| UK           | 4         | 4.88%   |
| Japan        | 4         | 4.88%   |
| Spain        | 3         | 3.66%   |
| South Africa | 3         | 3.66%   |
| Russia       | 3         | 3.66%   |
| Portugal     | 3         | 3.66%   |
| Greece       | 3         | 3.66%   |
| Hong Kong    | 2         | 2.44%   |
| France       | 2         | 2.44%   |
| Canada       | 2         | 2.44%   |
| Switzerland  | 1         | 1.22%   |
| Sweden       | 1         | 1.22%   |
| Serbia       | 1         | 1.22%   |
| Netherlands  | 1         | 1.22%   |
| Mexico       | 1         | 1.22%   |
| India        | 1         | 1.22%   |
| China        | 1         | 1.22%   |
| Chile        | 1         | 1.22%   |
| Australia    | 1         | 1.22%   |
| Argentina    | 1         | 1.22%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Ust-Kamenogorsk   | 4         | 4.76%   |
| Tsukuba           | 3         | 3.57%   |
| Lisbon            | 3         | 3.57%   |
| Chania            | 3         | 3.57%   |
| Sun Prairie       | 2         | 2.38%   |
| Moscow            | 2         | 2.38%   |
| McKinney          | 2         | 2.38%   |
| Karaganda         | 2         | 2.38%   |
| Frignano          | 2         | 2.38%   |
| Fayetteville      | 2         | 2.38%   |
| Cape Town         | 2         | 2.38%   |
| Worpswede         | 1         | 1.19%   |
| Winter Springs    | 1         | 1.19%   |
| Toronto           | 1         | 1.19%   |
| Tatuí            | 1         | 1.19%   |
| St Petersburg     | 1         | 1.19%   |
| Springfield       | 1         | 1.19%   |
| Skövde           | 1         | 1.19%   |
| Sham Shui Po      | 1         | 1.19%   |
| Seville           | 1         | 1.19%   |
| Senhora da Hora   | 1         | 1.19%   |
| Sao Paulo         | 1         | 1.19%   |
| Santiago          | 1         | 1.19%   |
| Santa Cruz do Sul | 1         | 1.19%   |
| Saint Paul        | 1         | 1.19%   |
| Round Rock        | 1         | 1.19%   |
| Rome              | 1         | 1.19%   |
| Rock              | 1         | 1.19%   |
| Reno              | 1         | 1.19%   |
| Renazzo           | 1         | 1.19%   |
| Porto Alegre      | 1         | 1.19%   |
| Plainwell         | 1         | 1.19%   |
| Ōtsu             | 1         | 1.19%   |
| Oberstreit        | 1         | 1.19%   |
| Nanping           | 1         | 1.19%   |
| Naaldwijk         | 1         | 1.19%   |
| Montreal          | 1         | 1.19%   |
| Milwaukee         | 1         | 1.19%   |
| Milan             | 1         | 1.19%   |
| Mexico City       | 1         | 1.19%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 23        | 31     | 16.91%  |
| WDC                 | 21        | 39     | 15.44%  |
| Seagate             | 21        | 30     | 15.44%  |
| Toshiba             | 10        | 21     | 7.35%   |
| Kingston            | 7         | 9      | 5.15%   |
| Crucial             | 6         | 7      | 4.41%   |
| Hitachi             | 5         | 8      | 3.68%   |
| SK hynix            | 4         | 4      | 2.94%   |
| Intel               | 4         | 5      | 2.94%   |
| HGST                | 4         | 4      | 2.94%   |
| SanDisk             | 3         | 4      | 2.21%   |
| KIOXIA              | 3         | 3      | 2.21%   |
| Transcend           | 2         | 2      | 1.47%   |
| Micron Technology   | 2         | 2      | 1.47%   |
| Hewlett-Packard     | 2         | 3      | 1.47%   |
| Gigabyte Technology | 2         | 2      | 1.47%   |
| ZHITAI              | 1         | 2      | 0.74%   |
| Unknown             | 1         | 1      | 0.74%   |
| Silicon Motion      | 1         | 1      | 0.74%   |
| PNY                 | 1         | 1      | 0.74%   |
| Plextor             | 1         | 1      | 0.74%   |
| Phison Electronics  | 1         | 1      | 0.74%   |
| Patriot             | 1         | 1      | 0.74%   |
| Maxtor              | 1         | 1      | 0.74%   |
| Lexar               | 1         | 1      | 0.74%   |
| JMicron Technology  | 1         | 1      | 0.74%   |
| Intenso             | 1         | 1      | 0.74%   |
| GOODRAM             | 1         | 1      | 0.74%   |
| External            | 1         | 1      | 0.74%   |
| DUEX                | 1         | 1      | 0.74%   |
| China               | 1         | 1      | 0.74%   |
| Apple               | 1         | 1      | 0.74%   |
| A-DATA Technology   | 1         | 1      | 0.74%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| WDC WDS100T2B0A-00SM50 1TB SSD     | 2         | 1.27%   |
| WDC WD20EFRX-68EUZN0 2TB           | 2         | 1.27%   |
| WDC WD10SPZX-60Z10T0 1TB           | 2         | 1.27%   |
| WDC WD10EZEX-08WN4A0 1TB           | 2         | 1.27%   |
| Seagate ST2000DM008-2FR102 2TB     | 2         | 1.27%   |
| Seagate ST2000DL003-9VT166 2TB     | 2         | 1.27%   |
| Seagate ST1000DM003-1SB102 1TB     | 2         | 1.27%   |
| Seagate Expansion Desk 5TB         | 2         | 1.27%   |
| Samsung SSD 970 EVO 250GB          | 2         | 1.27%   |
| Kingston SA400S37240G 240GB SSD    | 2         | 1.27%   |
| Intel SSD 660P Series 512GB        | 2         | 1.27%   |
| HGST HTS725050A7E630 500GB         | 2         | 1.27%   |
| Crucial CT500MX500SSD1 500GB       | 2         | 1.27%   |
| ZHITAI SC001 Active 1TB SSD        | 1         | 0.64%   |
| ZHITAI PC005 Active 512GB          | 1         | 0.64%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 1         | 0.64%   |
| WDC WDS480G2G0A-00JH30 480GB SSD   | 1         | 0.64%   |
| WDC WDS100T2B0B-00YS70 1TB SSD     | 1         | 0.64%   |
| WDC WD5000AAKX-22ERMA0 500GB       | 1         | 0.64%   |
| WDC WD5000AAKS-007AA0 500GB        | 1         | 0.64%   |
| WDC WD5000AADS-00S9B0 500GB        | 1         | 0.64%   |
| WDC WD40EZRX-00SPEB0 4TB           | 1         | 0.64%   |
| WDC WD40EJRX-89T1XY0 4TB           | 1         | 0.64%   |
| WDC WD400BD-60LTA0 40GB            | 1         | 0.64%   |
| WDC WD3200AAJS-65B4A0 320GB        | 1         | 0.64%   |
| WDC WD30EZRX-00SPEB0 3TB           | 1         | 0.64%   |
| WDC WD30EZRX-00MMMB0 3TB           | 1         | 0.64%   |
| WDC WD20EZRZ-00Z5HB0 2TB           | 1         | 0.64%   |
| WDC WD20EZRX-00D8PB0 2TB           | 1         | 0.64%   |
| WDC WD20EARX-00PASB0 2TB           | 1         | 0.64%   |
| WDC WD10JPVX-75JC3T0 1TB           | 1         | 0.64%   |
| WDC WD10JPVT-08A1YT2 1TB           | 1         | 0.64%   |
| WDC WD10EZEX-00RKKA0 1TB           | 1         | 0.64%   |
| WDC WD10EZEX-00MFCA0 1TB           | 1         | 0.64%   |
| WDC WD Green 2.5 240GB             | 1         | 0.64%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB | 1         | 0.64%   |
| Unknown MMC Card  512GB            | 1         | 0.64%   |
| Transcend TS480GSSD220S 480GB      | 1         | 0.64%   |
| Transcend TS32GSSD370S 32GB        | 1         | 0.64%   |
| Toshiba THNSNH128GBST SSD          | 1         | 0.64%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 30     | 36.21%  |
| WDC                 | 17        | 32     | 29.31%  |
| Toshiba             | 9         | 16     | 15.52%  |
| Hitachi             | 5         | 8      | 8.62%   |
| HGST                | 4         | 4      | 6.9%    |
| Samsung Electronics | 1         | 1      | 1.72%   |
| Maxtor              | 1         | 1      | 1.72%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 13     | 20.45%  |
| Kingston            | 7         | 9      | 15.91%  |
| WDC                 | 4         | 6      | 9.09%   |
| Crucial             | 4         | 5      | 9.09%   |
| Transcend           | 2         | 2      | 4.55%   |
| SanDisk             | 2         | 2      | 4.55%   |
| ZHITAI              | 1         | 1      | 2.27%   |
| Toshiba             | 1         | 3      | 2.27%   |
| SK hynix            | 1         | 1      | 2.27%   |
| PNY                 | 1         | 1      | 2.27%   |
| Plextor             | 1         | 1      | 2.27%   |
| Patriot             | 1         | 1      | 2.27%   |
| Lexar               | 1         | 1      | 2.27%   |
| Intenso             | 1         | 1      | 2.27%   |
| Intel               | 1         | 2      | 2.27%   |
| Hewlett-Packard     | 1         | 1      | 2.27%   |
| GOODRAM             | 1         | 1      | 2.27%   |
| Gigabyte Technology | 1         | 1      | 2.27%   |
| External            | 1         | 1      | 2.27%   |
| DUEX                | 1         | 1      | 2.27%   |
| China               | 1         | 1      | 2.27%   |
| Apple               | 1         | 1      | 2.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 41        | 92     | 35.34%  |
| SSD  | 39        | 56     | 33.62%  |
| NVMe | 35        | 43     | 30.17%  |
| MMC  | 1         | 1      | 0.86%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 59        | 145    | 60.2%   |
| NVMe | 34        | 42     | 34.69%  |
| SAS  | 4         | 4      | 4.08%   |
| MMC  | 1         | 1      | 1.02%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 44        | 60     | 46.81%  |
| 0.51-1.0   | 22        | 41     | 23.4%   |
| 1.01-2.0   | 11        | 14     | 11.7%   |
| 3.01-4.0   | 8         | 15     | 8.51%   |
| 4.01-10.0  | 5         | 7      | 5.32%   |
| 2.01-3.0   | 4         | 11     | 4.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 19        | 22.35%  |
| 501-1000       | 18        | 21.18%  |
| 251-500        | 14        | 16.47%  |
| Unknown        | 8         | 9.41%   |
| 1001-2000      | 7         | 8.24%   |
| 1-20           | 7         | 8.24%   |
| 2001-3000      | 5         | 5.88%   |
| More than 3000 | 3         | 3.53%   |
| 21-50          | 2         | 2.35%   |
| 51-100         | 2         | 2.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 19        | 22.35%  |
| 1-20           | 16        | 18.82%  |
| 21-50          | 13        | 15.29%  |
| 251-500        | 10        | 11.76%  |
| 501-1000       | 8         | 9.41%   |
| Unknown        | 8         | 9.41%   |
| 1001-2000      | 5         | 5.88%   |
| 51-100         | 5         | 5.88%   |
| More than 3000 | 1         | 1.18%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


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

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


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

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 6      | 33.33%  |
| Seagate | 4         | 6      | 33.33%  |
| Hitachi | 2         | 2      | 16.67%  |
| HGST    | 2         | 2      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 64        | 126    | 65.31%  |
| Detected | 19        | 45     | 19.39%  |
| Malfunc  | 15        | 21     | 15.31%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 44        | 40%     |
| AMD                          | 20        | 18.18%  |
| Samsung Electronics          | 14        | 12.73%  |
| Nvidia                       | 4         | 3.64%   |
| SK hynix                     | 3         | 2.73%   |
| Marvell Technology Group     | 3         | 2.73%   |
| KIOXIA                       | 3         | 2.73%   |
| SanDisk                      | 2         | 1.82%   |
| Micron/Crucial Technology    | 2         | 1.82%   |
| Micron Technology            | 2         | 1.82%   |
| JMicron Technology           | 2         | 1.82%   |
| ASMedia Technology           | 2         | 1.82%   |
| Yangtze Memory Technologies  | 1         | 0.91%   |
| Toshiba America Info Systems | 1         | 0.91%   |
| Silicon Motion               | 1         | 0.91%   |
| Realtek Semiconductor        | 1         | 0.91%   |
| Phison Electronics           | 1         | 0.91%   |
| LSI Logic / Symbios Logic    | 1         | 0.91%   |
| Broadcom / LSI               | 1         | 0.91%   |
| Biwin Storage Technology     | 1         | 0.91%   |
| Adaptec                      | 1         | 0.91%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 12        | 8.76%   |
| AMD 400 Series Chipset SATA Controller                                           | 7         | 5.11%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 6         | 4.38%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 5         | 3.65%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 2.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 2.19%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 2.19%   |
| Nvidia MCP61 SATA Controller                                                     | 3         | 2.19%   |
| Nvidia MCP61 IDE                                                                 | 3         | 2.19%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 3         | 2.19%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 2.19%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 3         | 2.19%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 3         | 2.19%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 2.19%   |
| SK hynix BC511 NVMe SSD                                                          | 2         | 1.46%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 1.46%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 2         | 1.46%   |
| Micron NVMe Storage Controller                                                   | 2         | 1.46%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 2         | 1.46%   |
| JMicron JMB58x AHCI SATA controller                                              | 2         | 1.46%   |
| Intel SSD 660P Series                                                            | 2         | 1.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.46%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 2         | 1.46%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 1.46%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 1.46%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 1.46%   |
| Intel 631xESB/632xESB IDE Controller                                             | 2         | 1.46%   |
| Intel 4 Series Chipset PT IDER Controller                                        | 2         | 1.46%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 2         | 1.46%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 1.46%   |
| AMD 500 Series Chipset SATA Controller                                           | 2         | 1.46%   |
| Yangtze Memory Non-Volatile memory controller                                    | 1         | 0.73%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 1         | 0.73%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 1         | 0.73%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.73%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 0.73%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 0.73%   |
| Samsung Electronics SATA controller                                              | 1         | 0.73%   |
| Realtek NVMe Controller                                                          | 1         | 0.73%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 51        | 45.13%  |
| NVMe | 34        | 30.09%  |
| IDE  | 16        | 14.16%  |
| RAID | 9         | 7.96%   |
| SCSI | 3         | 2.65%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 58        | 70.73%  |
| AMD    | 24        | 29.27%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 4         | 4.82%   |
| Intel 12th Gen Core i7-12700H           | 3         | 3.61%   |
| Intel Core i7-5820K CPU @ 3.30GHz       | 2         | 2.41%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz    | 2         | 2.41%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 2         | 2.41%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 2.41%   |
| AMD Ryzen 5 3600 6-Core Processor       | 2         | 2.41%   |
| AMD Athlon II X2 250 Processor          | 2         | 2.41%   |
| Intel Xeon CPU X5680 @ 3.33GHz          | 1         | 1.2%    |
| Intel Xeon CPU X5355 @ 2.66GHz          | 1         | 1.2%    |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz     | 1         | 1.2%    |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz     | 1         | 1.2%    |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz     | 1         | 1.2%    |
| Intel Xeon CPU 5160 @ 3.00GHz           | 1         | 1.2%    |
| Intel Pentium Silver N6000 @ 1.10GHz    | 1         | 1.2%    |
| Intel Pentium Dual CPU E2140 @ 1.60GHz  | 1         | 1.2%    |
| Intel Pentium CPU GOLD 6500Y @ 1.10GHz  | 1         | 1.2%    |
| Intel Pentium CPU G3250 @ 3.20GHz       | 1         | 1.2%    |
| Intel Pentium CPU 2020M @ 2.40GHz       | 1         | 1.2%    |
| Intel Core i7-9750H CPU @ 2.60GHz       | 1         | 1.2%    |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 1.2%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 1         | 1.2%    |
| Intel Core i7-7700 CPU @ 3.60GHz        | 1         | 1.2%    |
| Intel Core i7-7600U CPU @ 2.80GHz       | 1         | 1.2%    |
| Intel Core i7-6700 CPU @ 3.40GHz        | 1         | 1.2%    |
| Intel Core i7-6500U CPU @ 2.50GHz       | 1         | 1.2%    |
| Intel Core i7-3840QM CPU @ 2.80GHz      | 1         | 1.2%    |
| Intel Core i7-3720QM CPU @ 2.60GHz      | 1         | 1.2%    |
| Intel Core i7-10870H CPU @ 2.20GHz      | 1         | 1.2%    |
| Intel Core i7-10510U CPU @ 1.80GHz      | 1         | 1.2%    |
| Intel Core i5-8600K CPU @ 3.60GHz       | 1         | 1.2%    |
| Intel Core i5-6300U CPU @ 2.40GHz       | 1         | 1.2%    |
| Intel Core i5-4590 CPU @ 3.30GHz        | 1         | 1.2%    |
| Intel Core i5-4310M CPU @ 2.70GHz       | 1         | 1.2%    |
| Intel Core i5-3360M CPU @ 2.80GHz       | 1         | 1.2%    |
| Intel Core i5-3330 CPU @ 3.00GHz        | 1         | 1.2%    |
| Intel Core i5-3320M CPU @ 2.60GHz       | 1         | 1.2%    |
| Intel Core i5-3230M CPU @ 2.60GHz       | 1         | 1.2%    |
| Intel Core i5-2400 CPU @ 3.10GHz        | 1         | 1.2%    |
| Intel Core i5-10210U CPU @ 1.60GHz      | 1         | 1.2%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Other                | 13        | 15.66%  |
| Intel Core i7        | 13        | 15.66%  |
| Intel Core i5        | 13        | 15.66%  |
| AMD Ryzen 5          | 7         | 8.43%   |
| Intel Xeon           | 6         | 7.23%   |
| Intel Core 2 Duo     | 5         | 6.02%   |
| Intel Pentium        | 3         | 3.61%   |
| AMD Ryzen 9          | 3         | 3.61%   |
| AMD FX               | 3         | 3.61%   |
| Intel Core i3        | 2         | 2.41%   |
| Intel Celeron        | 2         | 2.41%   |
| AMD Ryzen 7          | 2         | 2.41%   |
| AMD Athlon II X2     | 2         | 2.41%   |
| Intel Pentium Silver | 1         | 1.2%    |
| Intel Pentium Dual   | 1         | 1.2%    |
| Intel Atom           | 1         | 1.2%    |
| AMD Ryzen 7 PRO      | 1         | 1.2%    |
| AMD Ryzen 3          | 1         | 1.2%    |
| AMD EPYC             | 1         | 1.2%    |
| AMD E1               | 1         | 1.2%    |
| AMD Athlon           | 1         | 1.2%    |
| AMD A8               | 1         | 1.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 26        | 31.33%  |
| 2      | 26        | 31.33%  |
| 8      | 13        | 15.66%  |
| 6      | 8         | 9.64%   |
| 14     | 4         | 4.82%   |
| 12     | 2         | 2.41%   |
| 10     | 2         | 2.41%   |
| 16     | 1         | 1.2%    |
| 3      | 1         | 1.2%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 79        | 96.34%  |
| 2      | 3         | 3.66%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 59        | 71.95%  |
| 1      | 23        | 28.05%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 82        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 18        | 21.95%  |
| 0x306a9    | 7         | 8.54%   |
| 0x806d1    | 4         | 4.88%   |
| 0x906a3    | 3         | 3.66%   |
| 0x806c1    | 3         | 3.66%   |
| 0x306f2    | 3         | 3.66%   |
| 0x08701021 | 3         | 3.66%   |
| 0x406c4    | 2         | 2.44%   |
| 0x306c3    | 2         | 2.44%   |
| 0x1067a    | 2         | 2.44%   |
| 0x0a50000c | 2         | 2.44%   |
| 0x0a201016 | 2         | 2.44%   |
| 0x08108109 | 2         | 2.44%   |
| 0xa0671    | 1         | 1.22%   |
| 0xa0653    | 1         | 1.22%   |
| 0xa0652    | 1         | 1.22%   |
| 0x906ea    | 1         | 1.22%   |
| 0x906e9    | 1         | 1.22%   |
| 0x906c0    | 1         | 1.22%   |
| 0x906a4    | 1         | 1.22%   |
| 0x806ec    | 1         | 1.22%   |
| 0x806ea    | 1         | 1.22%   |
| 0x6fd      | 1         | 1.22%   |
| 0x6fb      | 1         | 1.22%   |
| 0x6fa      | 1         | 1.22%   |
| 0x506e3    | 1         | 1.22%   |
| 0x406e3    | 1         | 1.22%   |
| 0x306e4    | 1         | 1.22%   |
| 0x306d4    | 1         | 1.22%   |
| 0x206c2    | 1         | 1.22%   |
| 0x20655    | 1         | 1.22%   |
| 0x106c2    | 1         | 1.22%   |
| 0x08900201 | 1         | 1.22%   |
| 0x08600106 | 1         | 1.22%   |
| 0x0830104d | 1         | 1.22%   |
| 0x0810100b | 1         | 1.22%   |
| 0x08001126 | 1         | 1.22%   |
| 0x07030105 | 1         | 1.22%   |
| 0x07000106 | 1         | 1.22%   |
| 0x06000822 | 1         | 1.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 9         | 10.98%  |
| IvyBridge        | 8         | 9.76%   |
| Zen 2            | 7         | 8.54%   |
| Haswell          | 6         | 7.32%   |
| Icelake          | 5         | 6.1%    |
| Core             | 5         | 6.1%    |
| Zen 3            | 4         | 4.88%   |
| Westmere         | 4         | 4.88%   |
| Alderlake Hybrid | 4         | 4.88%   |
| Zen+             | 3         | 3.66%   |
| TigerLake        | 3         | 3.66%   |
| Skylake          | 3         | 3.66%   |
| Penryn           | 3         | 3.66%   |
| Zen              | 2         | 2.44%   |
| Silvermont       | 2         | 2.44%   |
| Piledriver       | 2         | 2.44%   |
| K10              | 2         | 2.44%   |
| CometLake        | 2         | 2.44%   |
| Tremont          | 1         | 1.22%   |
| SandyBridge      | 1         | 1.22%   |
| Puma             | 1         | 1.22%   |
| Jaguar           | 1         | 1.22%   |
| Bulldozer        | 1         | 1.22%   |
| Broadwell        | 1         | 1.22%   |
| Bonnell          | 1         | 1.22%   |
| Unknown          | 1         | 1.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 38        | 39.58%  |
| Nvidia                     | 35        | 36.46%  |
| AMD                        | 22        | 22.92%  |
| Matrox Electronics Systems | 1         | 1.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 4         | 4.08%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 3         | 3.06%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 3.06%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 3.06%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 3         | 3.06%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 3.06%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 3.06%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 3.06%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 2.04%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 2.04%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2         | 2.04%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2         | 2.04%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2         | 2.04%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 2         | 2.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 2.04%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 2.04%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 2.04%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 2.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 2.04%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 2.04%   |
| AMD Renoir                                                                               | 2         | 2.04%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 2         | 2.04%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 2         | 2.04%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 2.04%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.02%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 1         | 1.02%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 1.02%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 1.02%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 1.02%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 1.02%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.02%   |
| Nvidia GF108GL [Quadro 600]                                                              | 1         | 1.02%   |
| Nvidia GA107M [GeForce RTX 2050]                                                         | 1         | 1.02%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 1.02%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 1         | 1.02%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                                       | 1         | 1.02%   |
| Nvidia G96C [GeForce 9400 GT]                                                            | 1         | 1.02%   |
| Nvidia G84 [GeForce 8600 GT]                                                             | 1         | 1.02%   |
| Nvidia G71GL [Quadro FX 1500]                                                            | 1         | 1.02%   |
| Nvidia C79 [ION]                                                                         | 1         | 1.02%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 26        | 31.71%  |
| 1 x Nvidia     | 21        | 25.61%  |
| 1 x AMD        | 20        | 24.39%  |
| Intel + Nvidia | 12        | 14.63%  |
| 2 x AMD        | 1         | 1.22%   |
| 1 x Matrox     | 1         | 1.22%   |
| AMD + Nvidia   | 1         | 1.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 64        | 78.05%  |
| Proprietary | 15        | 18.29%  |
| Unknown     | 3         | 3.66%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 42        | 51.22%  |
| 0.51-1.0   | 9         | 10.98%  |
| 0.01-0.5   | 9         | 10.98%  |
| 7.01-8.0   | 7         | 8.54%   |
| 1.01-2.0   | 4         | 4.88%   |
| 5.01-6.0   | 3         | 3.66%   |
| 3.01-4.0   | 3         | 3.66%   |
| 8.01-16.0  | 3         | 3.66%   |
| 2.01-3.0   | 1         | 1.22%   |
| 16.01-24.0 | 1         | 1.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 11        | 13.1%   |
| BOE                     | 11        | 13.1%   |
| LG Display              | 7         | 8.33%   |
| Hewlett-Packard         | 7         | 8.33%   |
| Dell                    | 7         | 8.33%   |
| AU Optronics            | 7         | 8.33%   |
| Chimei Innolux          | 4         | 4.76%   |
| Lenovo                  | 3         | 3.57%   |
| BenQ                    | 3         | 3.57%   |
| Ancor Communications    | 3         | 3.57%   |
| Sharp                   | 2         | 2.38%   |
| Goldstar                | 2         | 2.38%   |
| AOC                     | 2         | 2.38%   |
| Acer                    | 2         | 2.38%   |
| Wacom                   | 1         | 1.19%   |
| Valve                   | 1         | 1.19%   |
| UGD                     | 1         | 1.19%   |
| Sony                    | 1         | 1.19%   |
| PANDA                   | 1         | 1.19%   |
| IOD                     | 1         | 1.19%   |
| Iiyama                  | 1         | 1.19%   |
| GDH                     | 1         | 1.19%   |
| CTC                     | 1         | 1.19%   |
| Chi Mei Optoelectronics | 1         | 1.19%   |
| ASUSTek Computer        | 1         | 1.19%   |
| Apple                   | 1         | 1.19%   |
| Unknown                 | 1         | 1.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC416E 2880x1620 344x194mm 15.5-inch | 2         | 2.33%   |
| Wacom Cintiq 22HDT WAC1037 1920x1080 476x268mm 21.5-inch              | 1         | 1.16%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 1.16%   |
| UGD LCD Monitor UGD1302 1920x1080 290x160mm 13.0-inch                 | 1         | 1.16%   |
| Sony TV SNY8102 1360x768                                              | 1         | 1.16%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 382x215mm 17.3-inch               | 1         | 1.16%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 1.16%   |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch   | 1         | 1.16%   |
| Samsung Electronics SyncMaster SAM03F2 1680x1050                      | 1         | 1.16%   |
| Samsung Electronics SyncMaster SAM03F0 1680x1050 433x271mm 20.1-inch  | 1         | 1.16%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 376x301mm 19.0-inch  | 1         | 1.16%   |
| Samsung Electronics SyncMaster SAM01AD 1600x1200 408x306mm 20.1-inch  | 1         | 1.16%   |
| Samsung Electronics SMS27A650 SAM082D 1920x1080 598x336mm 27.0-inch   | 1         | 1.16%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch    | 1         | 1.16%   |
| Samsung Electronics SM2333T SAM0736 1920x1080 477x268mm 21.5-inch     | 1         | 1.16%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch     | 1         | 1.16%   |
| Samsung Electronics LCD Monitor U28D590 3840x2160                     | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 1.16%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 1.16%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch          | 1         | 1.16%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch          | 1         | 1.16%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 1.16%   |
| LG Display LCD Monitor LGD0353 1366x768 345x194mm 15.6-inch           | 1         | 1.16%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch          | 1         | 1.16%   |
| LG Display LCD Monitor LGD028A 1366x768 344x194mm 15.5-inch           | 1         | 1.16%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch           | 1         | 1.16%   |
| Lenovo LEN L171 LEN24C9 1280x1024 337x270mm 17.0-inch                 | 1         | 1.16%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch               | 1         | 1.16%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch               | 1         | 1.16%   |
| IOD LCD-GL211X IOD151D 1920x1080 458x258mm 20.7-inch                  | 1         | 1.16%   |
| Iiyama PL2783Q IVM661F 2560x1440 597x336mm 27.0-inch                  | 1         | 1.16%   |
| Hewlett-Packard Z24i HWP309E 1920x1200 518x324mm 24.1-inch            | 1         | 1.16%   |
| Hewlett-Packard x23LED HWP2912 1920x1080 509x286mm 23.0-inch          | 1         | 1.16%   |
| Hewlett-Packard P223 HPN3392 1920x1080 477x268mm 21.5-inch            | 1         | 1.16%   |
| Hewlett-Packard ALL-in-One HPN4021 1920x1080 476x268mm 21.5-inch      | 1         | 1.16%   |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch             | 1         | 1.16%   |
| Hewlett-Packard 27m HPN3579 1920x1080 598x336mm 27.0-inch             | 1         | 1.16%   |
| Hewlett-Packard 22fw HPN3541 1920x1080 476x268mm 21.5-inch            | 1         | 1.16%   |
| Goldstar W1952 GSM4B77 1440x900 408x255mm 18.9-inch                   | 1         | 1.16%   |
| Goldstar E1641 GSM8B3E 1366x768 344x194mm 15.5-inch                   | 1         | 1.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 35        | 42.68%  |
| 1366x768 (WXGA)    | 12        | 14.63%  |
| 3840x2160 (4K)     | 4         | 4.88%   |
| 1680x1050 (WSXGA+) | 4         | 4.88%   |
| 1280x1024 (SXGA)   | 4         | 4.88%   |
| 2560x1440 (QHD)    | 3         | 3.66%   |
| 2880x1620          | 2         | 2.44%   |
| 1920x1200 (WUXGA)  | 2         | 2.44%   |
| 1600x900 (HD+)     | 2         | 2.44%   |
| 1440x900 (WXGA+)   | 2         | 2.44%   |
| 1360x768           | 2         | 2.44%   |
| 1280x800 (WXGA)    | 2         | 2.44%   |
| 800x1280           | 1         | 1.22%   |
| 3440x1440          | 1         | 1.22%   |
| 3200x1080          | 1         | 1.22%   |
| 2256x1504          | 1         | 1.22%   |
| 1920x1280          | 1         | 1.22%   |
| 1600x1200          | 1         | 1.22%   |
| 1024x768 (XGA)     | 1         | 1.22%   |
| Unknown            | 1         | 1.22%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 17        | 20.24%  |
| 27      | 8         | 9.52%   |
| 17      | 7         | 8.33%   |
| 14      | 7         | 8.33%   |
| 13      | 7         | 8.33%   |
| 24      | 6         | 7.14%   |
| 21      | 5         | 5.95%   |
| 23      | 3         | 3.57%   |
| 22      | 3         | 3.57%   |
| 20      | 3         | 3.57%   |
| 19      | 3         | 3.57%   |
| 18      | 3         | 3.57%   |
| Unknown | 3         | 3.57%   |
| 16      | 2         | 2.38%   |
| 72      | 1         | 1.19%   |
| 52      | 1         | 1.19%   |
| 34      | 1         | 1.19%   |
| 12      | 1         | 1.19%   |
| 11      | 1         | 1.19%   |
| 10      | 1         | 1.19%   |
| 7       | 1         | 1.19%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 31        | 37.35%  |
| 501-600     | 15        | 18.07%  |
| 401-500     | 15        | 18.07%  |
| 351-400     | 9         | 10.84%  |
| 201-300     | 5         | 6.02%   |
| Unknown     | 3         | 3.61%   |
| 701-800     | 1         | 1.2%    |
| 601-700     | 1         | 1.2%    |
| 1501-2000   | 1         | 1.2%    |
| 1001-1500   | 1         | 1.2%    |
| 1-100       | 1         | 1.2%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 53        | 69.74%  |
| 16/10   | 11        | 14.47%  |
| 5/4     | 4         | 5.26%   |
| 4/3     | 2         | 2.63%   |
| 3/2     | 2         | 2.63%   |
| Unknown | 2         | 2.63%   |
| 21/9    | 1         | 1.32%   |
| 0.67    | 1         | 1.32%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 19        | 22.89%  |
| 81-90          | 13        | 15.66%  |
| 201-250        | 11        | 13.25%  |
| 151-200        | 9         | 10.84%  |
| 301-350        | 8         | 9.64%   |
| 121-130        | 5         | 6.02%   |
| 141-150        | 4         | 4.82%   |
| 251-300        | 3         | 3.61%   |
| Unknown        | 3         | 3.61%   |
| More than 1000 | 2         | 2.41%   |
| 51-60          | 2         | 2.41%   |
| 71-80          | 1         | 1.2%    |
| 61-70          | 1         | 1.2%    |
| 351-500        | 1         | 1.2%    |
| 1-40           | 1         | 1.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 29        | 34.94%  |
| 121-160       | 22        | 26.51%  |
| 101-120       | 20        | 24.1%   |
| 161-240       | 6         | 7.23%   |
| Unknown       | 3         | 3.61%   |
| 1-50          | 2         | 2.41%   |
| More than 240 | 1         | 1.2%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 66        | 80.49%  |
| 2     | 8         | 9.76%   |
| 0     | 6         | 7.32%   |
| 4     | 1         | 1.22%   |
| 3     | 1         | 1.22%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 45        | 36.59%  |
| Realtek Semiconductor    | 44        | 35.77%  |
| Broadcom                 | 6         | 4.88%   |
| Qualcomm Atheros         | 5         | 4.07%   |
| Broadcom Limited         | 4         | 3.25%   |
| Ralink Technology        | 3         | 2.44%   |
| Nvidia                   | 3         | 2.44%   |
| MediaTek                 | 3         | 2.44%   |
| ASIX Electronics         | 2         | 1.63%   |
| TP-Link                  | 1         | 0.81%   |
| Sitecom Europe           | 1         | 0.81%   |
| Ralink                   | 1         | 0.81%   |
| Qualcomm                 | 1         | 0.81%   |
| Marvell Technology Group | 1         | 0.81%   |
| Huawei Technologies      | 1         | 0.81%   |
| Hewlett-Packard          | 1         | 0.81%   |
| Dell                     | 1         | 0.81%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 31        | 21.23%  |
| Intel Wi-Fi 6 AX200                                               | 6         | 4.11%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5         | 3.42%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 2.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 2.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 2.05%   |
| Ralink MT7601U Wireless Adapter                                   | 3         | 2.05%   |
| Intel Wireless 8265 / 8275                                        | 3         | 2.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 2.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.37%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 2         | 1.37%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.37%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 1.37%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 1.37%   |
| Nvidia MCP61 Ethernet                                             | 2         | 1.37%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 2         | 1.37%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.37%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 1.37%   |
| Intel Ethernet Controller I225-V                                  | 2         | 1.37%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.37%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.37%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 1.37%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 2         | 1.37%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                           | 2         | 1.37%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 0.68%   |
| Sitecom Europe WL-113 rev 2 Wireless Network USB Adapter          | 1         | 0.68%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.68%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.68%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.68%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.68%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 1         | 0.68%   |
| Qualcomm Nokia G400 5G                                            | 1         | 0.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 0.68%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1         | 0.68%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 0.68%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1         | 0.68%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.68%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 33        | 54.1%   |
| Realtek Semiconductor | 9         | 14.75%  |
| Qualcomm Atheros      | 4         | 6.56%   |
| Ralink Technology     | 3         | 4.92%   |
| MediaTek              | 3         | 4.92%   |
| Broadcom Limited      | 3         | 4.92%   |
| Broadcom              | 2         | 3.28%   |
| TP-Link               | 1         | 1.64%   |
| Sitecom Europe        | 1         | 1.64%   |
| Ralink                | 1         | 1.64%   |
| Dell                  | 1         | 1.64%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                   | 6         | 9.68%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                | 5         | 8.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter              | 3         | 4.84%   |
| Ralink MT7601U Wireless Adapter                                       | 3         | 4.84%   |
| Intel Wireless 8265 / 8275                                            | 3         | 4.84%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                          | 3         | 4.84%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter              | 2         | 3.23%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                               | 2         | 3.23%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter         | 2         | 3.23%   |
| Intel Wi-Fi 6 AX201                                                   | 2         | 3.23%   |
| Intel Tiger Lake PCH CNVi WiFi                                        | 2         | 3.23%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                               | 2         | 3.23%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                           | 1         | 1.61%   |
| Sitecom Europe WL-113 rev 2 Wireless Network USB Adapter              | 1         | 1.61%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                    | 1         | 1.61%   |
| Realtek RTL8723DE Wireless Network Adapter                            | 1         | 1.61%   |
| Realtek RTL8191SEvB Wireless LAN Controller                           | 1         | 1.61%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                             | 1         | 1.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                      | 1         | 1.61%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                      | 1         | 1.61%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)        | 1         | 1.61%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                      | 1         | 1.61%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter         | 1         | 1.61%   |
| Intel Wireless-AC 9260                                                | 1         | 1.61%   |
| Intel Wireless 8260                                                   | 1         | 1.61%   |
| Intel Wireless 7260                                                   | 1         | 1.61%   |
| Intel Wireless 3165                                                   | 1         | 1.61%   |
| Intel Wi-Fi 6 AX201 160MHz                                            | 1         | 1.61%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection         | 1         | 1.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                      | 1         | 1.61%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                       | 1         | 1.61%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                     | 1         | 1.61%   |
| Intel Comet Lake PCH CNVi WiFi                                        | 1         | 1.61%   |
| Intel Centrino Ultimate-N 6300                                        | 1         | 1.61%   |
| Intel Alder Lake-P PCH CNVi WiFi                                      | 1         | 1.61%   |
| Dell Wireless 1450 Dual-band (802.11a/b/g) Adapter [Intersil ISL3887] | 1         | 1.61%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                               | 1         | 1.61%   |
| Broadcom BCM4331 802.11a/b/g/n                                        | 1         | 1.61%   |
| Broadcom BCM4321 802.11a/b/g/n                                        | 1         | 1.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 41        | 50.62%  |
| Intel                    | 24        | 29.63%  |
| Broadcom                 | 5         | 6.17%   |
| Nvidia                   | 3         | 3.7%    |
| Qualcomm Atheros         | 2         | 2.47%   |
| ASIX Electronics         | 2         | 2.47%   |
| Qualcomm                 | 1         | 1.23%   |
| Marvell Technology Group | 1         | 1.23%   |
| Huawei Technologies      | 1         | 1.23%   |
| Broadcom Limited         | 1         | 1.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 31        | 37.35%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 4.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 4.82%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 2.41%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 2.41%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 2.41%   |
| Nvidia MCP61 Ethernet                                             | 2         | 2.41%   |
| Intel Ethernet Controller I225-V                                  | 2         | 2.41%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.41%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 2.41%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 2.41%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 2         | 2.41%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 1.2%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.2%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.2%    |
| Qualcomm Nokia G400 5G                                            | 1         | 1.2%    |
| Nvidia MCP79 Ethernet                                             | 1         | 1.2%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.2%    |
| Intel I350 Gigabit Network Connection                             | 1         | 1.2%    |
| Intel I211 Gigabit Network Connection                             | 1         | 1.2%    |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.2%    |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.2%    |
| Intel Ethernet Connection (5) I219-V                              | 1         | 1.2%    |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.2%    |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.2%    |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 1.2%    |
| Intel Ethernet Connection (12) I219-V                             | 1         | 1.2%    |
| Intel 82576 Gigabit Network Connection                            | 1         | 1.2%    |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.2%    |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.2%    |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1         | 1.2%    |
| Huawei E353/E3131                                                 | 1         | 1.2%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.2%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1         | 1.2%    |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 1         | 1.2%    |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 1         | 1.2%    |
| ASIX AX88772A Fast Ethernet                                       | 1         | 1.2%    |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.2%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 74        | 54.81%  |
| WiFi     | 60        | 44.44%  |
| Modem    | 1         | 0.74%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 45        | 51.72%  |
| Ethernet | 42        | 48.28%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 42        | 50.6%   |
| 1     | 36        | 43.37%  |
| 4     | 2         | 2.41%   |
| 3     | 2         | 2.41%   |
| 5     | 1         | 1.2%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 69        | 83.13%  |
| Yes  | 14        | 16.87%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 28        | 52.83%  |
| Realtek Semiconductor    | 5         | 9.43%   |
| Cambridge Silicon Radio  | 5         | 9.43%   |
| Broadcom                 | 5         | 9.43%   |
| IMC Networks             | 4         | 7.55%   |
| Apple                    | 2         | 3.77%   |
| TP-Link                  | 1         | 1.89%   |
| Micro Star International | 1         | 1.89%   |
| MediaTek                 | 1         | 1.89%   |
| Foxconn / Hon Hai        | 1         | 1.89%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 7         | 13.21%  |
| Intel AX201 Bluetooth                               | 6         | 11.32%  |
| Intel AX200 Bluetooth                               | 6         | 11.32%  |
| Intel AX210 Bluetooth                               | 5         | 9.43%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5         | 9.43%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 5.66%   |
| IMC Networks Wireless_Device                        | 3         | 5.66%   |
| Realtek Bluetooth Radio                             | 2         | 3.77%   |
| TP-Link UB500 Adapter                               | 1         | 1.89%   |
| Micro Star International Bluetooth Dongle           | 1         | 1.89%   |
| MediaTek Wireless_Device                            | 1         | 1.89%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.89%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.89%   |
| Intel Bluetooth Device                              | 1         | 1.89%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 1.89%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.89%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 1.89%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.89%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.89%   |
| Broadcom BCM20702A0                                 | 1         | 1.89%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.89%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 1.89%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.89%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 1         | 1.89%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 52        | 43.33%  |
| Nvidia                 | 30        | 25%     |
| AMD                    | 26        | 21.67%  |
| Creative Labs          | 4         | 3.33%   |
| C-Media Electronics    | 2         | 1.67%   |
| Texas Instruments      | 1         | 0.83%   |
| RME                    | 1         | 0.83%   |
| Kingston Technology    | 1         | 0.83%   |
| Holtek Semiconductor   | 1         | 0.83%   |
| Generalplus Technology | 1         | 0.83%   |
| ASUSTek Computer       | 1         | 0.83%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 5.07%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 4.35%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 6         | 4.35%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 3.62%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 3.62%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 2.9%    |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 2.9%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 4         | 2.9%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 2.9%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 2.17%   |
| Nvidia MCP61 High Definition Audio                                                                | 3         | 2.17%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 2.17%   |
| Nvidia Audio device                                                                               | 3         | 2.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 2.17%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 2.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 2.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 2.17%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 2.17%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 3         | 2.17%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 1.45%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 1.45%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 2         | 1.45%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.45%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.45%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2         | 1.45%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.45%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 1.45%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus]   | 2         | 1.45%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 1.45%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.45%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2         | 1.45%   |
| AMD Navi 10 HDMI Audio                                                                            | 2         | 1.45%   |
| AMD FCH Azalia Controller                                                                         | 2         | 1.45%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.72%   |
| RME ADI-2 DAC (58825307)                                                                          | 1         | 0.72%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.72%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.72%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.72%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Kingston            | 16        | 18.82%  |
| SK hynix            | 15        | 17.65%  |
| Samsung Electronics | 14        | 16.47%  |
| Corsair             | 7         | 8.24%   |
| Crucial             | 6         | 7.06%   |
| Micron Technology   | 4         | 4.71%   |
| Unknown             | 3         | 3.53%   |
| G.Skill             | 3         | 3.53%   |
| Team                | 2         | 2.35%   |
| A-DATA Technology   | 2         | 2.35%   |
| Unknown             | 2         | 2.35%   |
| Transcend           | 1         | 1.18%   |
| Strontium           | 1         | 1.18%   |
| Smart               | 1         | 1.18%   |
| Silicon Power       | 1         | 1.18%   |
| Patriot             | 1         | 1.18%   |
| Neo Forza           | 1         | 1.18%   |
| Nanya Technology    | 1         | 1.18%   |
| Goodram             | 1         | 1.18%   |
| GLOWAY              | 1         | 1.18%   |
| Essencore Limited   | 1         | 1.18%   |
| AMD                 | 1         | 1.18%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                             | 2         | 2.2%    |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 2         | 2.2%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 2.2%    |
| Unknown                                                          | 2         | 2.2%    |
| Unknown RAM Module 2GB DIMM DDR2 533MT/s                         | 1         | 1.1%    |
| Transcend RAM JM1600KLN-8GK 4096MB DIMM DDR3 1600MT/s            | 1         | 1.1%    |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3733MT/s               | 1         | 1.1%    |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s               | 1         | 1.1%    |
| Strontium RAM SRT4G86U1-P9H 4096MB DIMM DDR3 1333MT/s            | 1         | 1.1%    |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s              | 1         | 1.1%    |
| SK hynix RAM HYMP512F72CP8N3-Y5 1024MB FB-DIMM DDR2 667MT/s      | 1         | 1.1%    |
| SK hynix RAM HMT41GV7BMR4A-H9 16GB DIMM 1333MT/s                 | 1         | 1.1%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.1%    |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s             | 1         | 1.1%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.1%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 1.1%    |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.1%    |
| SK hynix RAM HMT31GR7BFR4A-H9 8192MB DIMM 1333MT/s               | 1         | 1.1%    |
| SK hynix RAM HMT125R7BFR8C-H9 2GB DIMM 1333MT/s                  | 1         | 1.1%    |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.1%    |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.1%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.1%    |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.1%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.1%    |
| SK hynix RAM HMA81GR7CJR8N-XN 8192MB DIMM DDR4 3200MT/s          | 1         | 1.1%    |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 1.1%    |
| Silicon Power RAM DCLT4GN568S V 4096MB DIMM DDR3 1600MT/s        | 1         | 1.1%    |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 1.1%    |
| Samsung RAM M471B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.1%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.1%    |
| Samsung RAM M471B5173BH0-CK0 4096MB SODIMM DDR3 1600MT/s         | 1         | 1.1%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 1.1%    |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s            | 1         | 1.1%    |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 1         | 1.1%    |
| Samsung RAM M395T5663QZ4-CE66 2048MB FB-DIMM DDR2 667MT/s        | 1         | 1.1%    |
| Samsung RAM M393A2G40DB0-CPB 16GB RIMM DDR4 2133MT/s             | 1         | 1.1%    |
| Samsung RAM M393A1K43BB0-CRC 8GB DIMM DDR4 2400MT/s              | 1         | 1.1%    |
| Samsung RAM M393A1G43EB1-CRC 8GB DIMM DDR4 2400MT/s              | 1         | 1.1%    |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s              | 1         | 1.1%    |
| Samsung RAM K3LK7K70BM-BGCP000 4GB SODIMM LPDDR5 4266MT/s        | 1         | 1.1%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 36        | 50.7%   |
| DDR3    | 22        | 30.99%  |
| DDR2    | 4         | 5.63%   |
| LPDDR5  | 3         | 4.23%   |
| SDRAM   | 2         | 2.82%   |
| LPDDR4  | 1         | 1.41%   |
| LPDDR3  | 1         | 1.41%   |
| DDR5    | 1         | 1.41%   |
| Unknown | 1         | 1.41%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 33        | 46.48%  |
| DIMM         | 32        | 45.07%  |
| Row Of Chips | 4         | 5.63%   |
| RIMM         | 1         | 1.41%   |
| FB-DIMM      | 1         | 1.41%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 31        | 39.24%  |
| 4096  | 25        | 31.65%  |
| 16384 | 11        | 13.92%  |
| 2048  | 6         | 7.59%   |
| 32768 | 4         | 5.06%   |
| 1024  | 2         | 2.53%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 17        | 21.52%  |
| 3200    | 16        | 20.25%  |
| 2667    | 6         | 7.59%   |
| 2400    | 6         | 7.59%   |
| 3600    | 4         | 5.06%   |
| 1333    | 4         | 5.06%   |
| 6400    | 2         | 2.53%   |
| 3800    | 2         | 2.53%   |
| 2133    | 2         | 2.53%   |
| 667     | 2         | 2.53%   |
| Unknown | 2         | 2.53%   |
| 65535   | 1         | 1.27%   |
| 4800    | 1         | 1.27%   |
| 4267    | 1         | 1.27%   |
| 4266    | 1         | 1.27%   |
| 3733    | 1         | 1.27%   |
| 3400    | 1         | 1.27%   |
| 2933    | 1         | 1.27%   |
| 2800    | 1         | 1.27%   |
| 2472    | 1         | 1.27%   |
| 2187    | 1         | 1.27%   |
| 1867    | 1         | 1.27%   |
| 1866    | 1         | 1.27%   |
| 1334    | 1         | 1.27%   |
| 975     | 1         | 1.27%   |
| 701     | 1         | 1.27%   |
| 533     | 1         | 1.27%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


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

![Printer Model](./images/pie_chart/printer_model.svg)


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

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1         | 50%     |
| Canon CanoScan LIDE 25                        | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 11        | 22.45%  |
| Logitech                               | 8         | 16.33%  |
| Microdia                               | 5         | 10.2%   |
| Bison Electronics                      | 4         | 8.16%   |
| Realtek Semiconductor                  | 3         | 6.12%   |
| Acer                                   | 3         | 6.12%   |
| Sonix Technology                       | 2         | 4.08%   |
| Samsung Electronics                    | 2         | 4.08%   |
| Quanta                                 | 2         | 4.08%   |
| Luxvisions Innotech Limited            | 2         | 4.08%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 4.08%   |
| Z-Star Microelectronics                | 1         | 2.04%   |
| Syntek                                 | 1         | 2.04%   |
| Microsoft                              | 1         | 2.04%   |
| Lenovo                                 | 1         | 2.04%   |
| Apple                                  | 1         | 2.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Logitech Webcam C270                                           | 3         | 6.12%   |
| Acer HD Webcam                                                 | 3         | 6.12%   |
| Sonix USB2.0 FHD UVC WebCam                                    | 2         | 4.08%   |
| Samsung Galaxy A5 (MTP)                                        | 2         | 4.08%   |
| Chicony Integrated Camera                                      | 2         | 4.08%   |
| Chicony HD User Facing                                         | 2         | 4.08%   |
| Bison BisonCam,NB Pro                                          | 2         | 4.08%   |
| Z-Star Vimicro USB2.0 Camera                                   | 1         | 2.04%   |
| Syntek USB2.0 Camera                                           | 1         | 2.04%   |
| Realtek Laptop Camera                                          | 1         | 2.04%   |
| Realtek Integrated Camera                                      | 1         | 2.04%   |
| Realtek EasyCamera                                             | 1         | 2.04%   |
| Quanta HP Wide Vision HD Camera                                | 1         | 2.04%   |
| Quanta HP Webcam                                               | 1         | 2.04%   |
| Microsoft LifeCam HD-3000                                      | 1         | 2.04%   |
| Microdia Laptop_Integrated_Webcam_2M                           | 1         | 2.04%   |
| Microdia Integrated_Webcam_HD                                  | 1         | 2.04%   |
| Microdia Integrated Webcam                                     | 1         | 2.04%   |
| Microdia Dell Integrated HD Webcam                             | 1         | 2.04%   |
| Microdia Camera                                                | 1         | 2.04%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 1         | 2.04%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 1         | 2.04%   |
| Logitech QuickCam Pro 9000                                     | 1         | 2.04%   |
| Logitech Logitech Webcam C160                                  | 1         | 2.04%   |
| Logitech HD Webcam C910                                        | 1         | 2.04%   |
| Logitech C922 Pro Stream Webcam                                | 1         | 2.04%   |
| Logitech C920 PRO HD Webcam                                    | 1         | 2.04%   |
| Lenovo Integrated Webcam [R5U877]                              | 1         | 2.04%   |
| Chicony Web Camera - FHD                                       | 1         | 2.04%   |
| Chicony Integrated Camera [ThinkPad]                           | 1         | 2.04%   |
| Chicony HP TrueVision HD Camera                                | 1         | 2.04%   |
| Chicony HP True Vision 5MP Camera                              | 1         | 2.04%   |
| Chicony HP HD Webcam [Fixed]                                   | 1         | 2.04%   |
| Chicony HP HD Camera                                           | 1         | 2.04%   |
| Chicony FJ Camera                                              | 1         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) HP 5M Camera            | 1         | 2.04%   |
| Bison ThinkPad Integrated Camera                               | 1         | 2.04%   |
| Bison Integrated Camera                                        | 1         | 2.04%   |
| Apple Built-in iSight                                          | 1         | 2.04%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 5         | 50%     |
| Synaptics                          | 2         | 20%     |
| Realtek USB2.0 Finger Print Bridge | 2         | 20%     |
| STMicroelectronics                 | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                                 | 3         | 30%     |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 2         | 20%     |
| Validity Sensors VFS451 Fingerprint Reader                      | 1         | 10%     |
| Validity Sensors VFS300 Fingerprint Reader                      | 1         | 10%     |
| Synaptics UWP WBDI                                              | 1         | 10%     |
| STMicroelectronics Fingerprint Reader                           | 1         | 10%     |
| Unknown                                                         | 1         | 10%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 2         | 66.67%  |
| Lenovo      | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 2         | 66.67%  |
| Lenovo Integrated Smart Card Reader | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 54        | 65.06%  |
| 1     | 20        | 24.1%   |
| 2     | 5         | 6.02%   |
| 4     | 2         | 2.41%   |
| 5     | 1         | 1.2%    |
| 3     | 1         | 1.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 10        | 21.74%  |
| Sound                    | 7         | 15.22%  |
| Graphics card            | 7         | 15.22%  |
| Net/wireless             | 4         | 8.7%    |
| Multimedia controller    | 4         | 8.7%    |
| Unassigned class         | 3         | 6.52%   |
| Communication controller | 3         | 6.52%   |
| Chipcard                 | 3         | 6.52%   |
| Camera                   | 2         | 4.35%   |
| Storage/ide              | 1         | 2.17%   |
| Net/ethernet             | 1         | 2.17%   |
| Bluetooth                | 1         | 2.17%   |

