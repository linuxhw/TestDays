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

Total: 117

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | P7P55D-E                    | Desktop     | [f16aeca403](https://linux-hardware.org/?probe=f16aeca403) | Nov 03, 2023 |
| Lenovo        | V330-14ARR 81B1             | Notebook    | [b80592c227](https://linux-hardware.org/?probe=b80592c227) | Oct 21, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [483998d7de](https://linux-hardware.org/?probe=483998d7de) | Oct 20, 2023 |
| HP            | OMEN by Laptop 16-b1xxx     | Notebook    | [aafdab7043](https://linux-hardware.org/?probe=aafdab7043) | Oct 13, 2023 |
| HP            | OMEN by Laptop 16-b1xxx     | Notebook    | [a1a64b6621](https://linux-hardware.org/?probe=a1a64b6621) | Oct 05, 2023 |
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
| 5.15.19           | 20        | 19.8%   |
| 5.19.17           | 7         | 6.93%   |
| 5.15.63           | 6         | 5.94%   |
| 5.15.117          | 5         | 4.95%   |
| 5.15.27           | 4         | 3.96%   |
| 5.19.17-Unraid    | 3         | 2.97%   |
| 5.15.94           | 3         | 2.97%   |
| 5.15.38           | 3         | 2.97%   |
| 6.1.44            | 2         | 1.98%   |
| 5.17.2            | 2         | 1.98%   |
| 5.17.1            | 2         | 1.98%   |
| 5.16.13           | 2         | 1.98%   |
| 5.15.80           | 2         | 1.98%   |
| 5.15.30-Unraid    | 2         | 1.98%   |
| 5.13.8            | 2         | 1.98%   |
| 6.5.5             | 1         | 0.99%   |
| 6.1.51            | 1         | 0.99%   |
| 6.1.27            | 1         | 0.99%   |
| 6.1.20            | 1         | 0.99%   |
| 6.1.13            | 1         | 0.99%   |
| 6.1.12            | 1         | 0.99%   |
| 6.1.1             | 1         | 0.99%   |
| 5.19.16           | 1         | 0.99%   |
| 5.17.5            | 1         | 0.99%   |
| 5.17.0-custom     | 1         | 0.99%   |
| 5.16.9-joe1       | 1         | 0.99%   |
| 5.16.18           | 1         | 0.99%   |
| 5.16.12           | 1         | 0.99%   |
| 5.16.11           | 1         | 0.99%   |
| 5.15.78.a         | 1         | 0.99%   |
| 5.15.6            | 1         | 0.99%   |
| 5.15.37.a         | 1         | 0.99%   |
| 5.15.33.kjh       | 1         | 0.99%   |
| 5.15.21-hardened1 | 1         | 0.99%   |
| 5.15.14           | 1         | 0.99%   |
| 5.15.13           | 1         | 0.99%   |
| 5.15.118          | 1         | 0.99%   |
| 5.15.103          | 1         | 0.99%   |
| 5.15.1            | 1         | 0.99%   |
| 5.14.9            | 1         | 0.99%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.19  | 20        | 19.8%   |
| 5.19.17  | 10        | 9.9%    |
| 5.15.63  | 6         | 5.94%   |
| 5.15.117 | 5         | 4.95%   |
| 5.15.27  | 4         | 3.96%   |
| 5.15.94  | 3         | 2.97%   |
| 5.15.38  | 3         | 2.97%   |
| 6.1.44   | 2         | 1.98%   |
| 5.17.2   | 2         | 1.98%   |
| 5.17.1   | 2         | 1.98%   |
| 5.16.13  | 2         | 1.98%   |
| 5.15.80  | 2         | 1.98%   |
| 5.15.30  | 2         | 1.98%   |
| 5.14.15  | 2         | 1.98%   |
| 5.13.8   | 2         | 1.98%   |
| 6.5.5    | 1         | 0.99%   |
| 6.1.51   | 1         | 0.99%   |
| 6.1.27   | 1         | 0.99%   |
| 6.1.20   | 1         | 0.99%   |
| 6.1.13   | 1         | 0.99%   |
| 6.1.12   | 1         | 0.99%   |
| 6.1.1    | 1         | 0.99%   |
| 5.19.16  | 1         | 0.99%   |
| 5.17.5   | 1         | 0.99%   |
| 5.17.0   | 1         | 0.99%   |
| 5.16.9   | 1         | 0.99%   |
| 5.16.18  | 1         | 0.99%   |
| 5.16.12  | 1         | 0.99%   |
| 5.16.11  | 1         | 0.99%   |
| 5.15.78  | 1         | 0.99%   |
| 5.15.6   | 1         | 0.99%   |
| 5.15.37  | 1         | 0.99%   |
| 5.15.33  | 1         | 0.99%   |
| 5.15.21  | 1         | 0.99%   |
| 5.15.14  | 1         | 0.99%   |
| 5.15.13  | 1         | 0.99%   |
| 5.15.118 | 1         | 0.99%   |
| 5.15.103 | 1         | 0.99%   |
| 5.15.1   | 1         | 0.99%   |
| 5.14.9   | 1         | 0.99%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 55        | 55.56%  |
| 5.19    | 11        | 11.11%  |
| 6.1     | 7         | 7.07%   |
| 5.14    | 7         | 7.07%   |
| 5.17    | 6         | 6.06%   |
| 5.16    | 6         | 6.06%   |
| 5.13    | 5         | 5.05%   |
| 6.5     | 1         | 1.01%   |
| 5.10    | 1         | 1.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 94        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE5       | 40        | 41.67%  |
| XFCE       | 28        | 29.17%  |
| Unknown    | 16        | 16.67%  |
| GNOME      | 3         | 3.13%   |
| xwmconfig  | 2         | 2.08%   |
| X-Generic  | 1         | 1.04%   |
| X-Cinnamon | 1         | 1.04%   |
| MATE       | 1         | 1.04%   |
| KDE        | 1         | 1.04%   |
| FVWM       | 1         | 1.04%   |
| awesome    | 1         | 1.04%   |
| 2bwm       | 1         | 1.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 53        | 53.54%  |
| Tty     | 35        | 35.35%  |
| Wayland | 6         | 6.06%   |
| Unknown | 5         | 5.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 47        | 47.96%  |
| Unknown | 27        | 27.55%  |
| XDM     | 17        | 17.35%  |
| LightDM | 5         | 5.1%    |
| SLiM    | 1         | 1.02%   |
| GDM     | 1         | 1.02%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 63        | 67.02%  |
| Unknown     | 10        | 10.64%  |
| it_IT       | 4         | 4.26%   |
| pt_BR       | 3         | 3.19%   |
| de_DE       | 3         | 3.19%   |
| ru_RU       | 2         | 2.13%   |
| fr_FR       | 2         | 2.13%   |
| en_GB       | 2         | 2.13%   |
| us          | 1         | 1.06%   |
| pt_PT       | 1         | 1.06%   |
| es_ES.UTF8  | 1         | 1.06%   |
| es_ES       | 1         | 1.06%   |
| en_US.ASCII | 1         | 1.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 52        | 54.74%  |
| BIOS | 43        | 45.26%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 70        | 72.92%  |
| Btrfs   | 11        | 11.46%  |
| Xfs     | 5         | 5.21%   |
| Overlay | 5         | 5.21%   |
| Zfs     | 1         | 1.04%   |
| Tmpfs   | 1         | 1.04%   |
| Rootfs  | 1         | 1.04%   |
| F2fs    | 1         | 1.04%   |
| Ext2    | 1         | 1.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 66        | 68.75%  |
| MBR     | 15        | 15.63%  |
| Unknown | 15        | 15.63%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 70        | 72.92%  |
| Yes       | 26        | 27.08%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 65        | 68.42%  |
| Yes       | 30        | 31.58%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 16        | 17.02%  |
| Lenovo              | 14        | 14.89%  |
| ASUSTek Computer    | 13        | 13.83%  |
| MSI                 | 12        | 12.77%  |
| Dell                | 9         | 9.57%   |
| ASRock              | 7         | 7.45%   |
| Gigabyte Technology | 3         | 3.19%   |
| Acer                | 3         | 3.19%   |
| Notebook            | 2         | 2.13%   |
| Fujitsu             | 2         | 2.13%   |
| Apple               | 2         | 2.13%   |
| Valve               | 1         | 1.06%   |
| TYAN Computer       | 1         | 1.06%   |
| Toshiba             | 1         | 1.06%   |
| System76            | 1         | 1.06%   |
| Sony                | 1         | 1.06%   |
| Microsoft           | 1         | 1.06%   |
| HEDYCOMPUTER        | 1         | 1.06%   |
| Framework           | 1         | 1.06%   |
| Dynabook            | 1         | 1.06%   |
| Biostar             | 1         | 1.06%   |
| Unknown             | 1         | 1.06%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| ASUS VivoBook_ASUSLaptop K6500ZE_K6500ZE | 2         | 2.13%   |
| ASRock N68-S3 FX                         | 2         | 2.13%   |
| Valve Jupiter                            | 1         | 1.06%   |
| TYAN S7012                               | 1         | 1.06%   |
| Toshiba Satellite C660                   | 1         | 1.06%   |
| System76 Oryx Pro                        | 1         | 1.06%   |
| Sony SVE1713A1EW                         | 1         | 1.06%   |
| Notebook X170KM-G                        | 1         | 1.06%   |
| Notebook P7xxTM                          | 1         | 1.06%   |
| MSI MS-7C52                              | 1         | 1.06%   |
| MSI MS-7C02                              | 1         | 1.06%   |
| MSI MS-7996                              | 1         | 1.06%   |
| MSI MS-7885                              | 1         | 1.06%   |
| MSI MS-7788                              | 1         | 1.06%   |
| MSI MS-7693                              | 1         | 1.06%   |
| MSI MS-7529                              | 1         | 1.06%   |
| MSI MS-7365                              | 1         | 1.06%   |
| MSI Modern 14 B11MO                      | 1         | 1.06%   |
| MSI Modern 14 B10MW                      | 1         | 1.06%   |
| MSI GP76 Leopard 11UG                    | 1         | 1.06%   |
| MSI GE76 Raider 11UE                     | 1         | 1.06%   |
| Microsoft Surface Go 3                   | 1         | 1.06%   |
| Lenovo V330-14ARR 81B1                   | 1         | 1.06%   |
| Lenovo ThinkPad X230 2325P38             | 1         | 1.06%   |
| Lenovo ThinkPad X140e 20BMS03E00         | 1         | 1.06%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS04300 | 1         | 1.06%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS2FT00 | 1         | 1.06%   |
| Lenovo ThinkPad T61 765912G              | 1         | 1.06%   |
| Lenovo ThinkPad T470p 20J60018MS         | 1         | 1.06%   |
| Lenovo ThinkPad T470 20JNS01R01          | 1         | 1.06%   |
| Lenovo ThinkPad T410 2518C3U             | 1         | 1.06%   |
| Lenovo ThinkPad Edge E530c 336669G       | 1         | 1.06%   |
| Lenovo ThinkPad E16 Gen 1 21JT000PJP     | 1         | 1.06%   |
| Lenovo IdeaPad 5 15ALC05 82LN            | 1         | 1.06%   |
| Lenovo IdeaPad 310-15ISK 80SM            | 1         | 1.06%   |
| Lenovo H50-05 90BH001WIX                 | 1         | 1.06%   |
| HP Z440 Workstation                      | 1         | 1.06%   |
| HP xw8400 Workstation                    | 1         | 1.06%   |
| HP ProBook 6570b                         | 1         | 1.06%   |
| HP Pavilion Gaming Laptop 16-a0xxx       | 1         | 1.06%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 10        | 10.64%  |
| HP Pavilion       | 3         | 3.19%   |
| ASUS ROG          | 3         | 3.19%   |
| ASUS PRIME        | 3         | 3.19%   |
| MSI Modern        | 2         | 2.13%   |
| Lenovo IdeaPad    | 2         | 2.13%   |
| HP OMEN           | 2         | 2.13%   |
| HP Laptop         | 2         | 2.13%   |
| HP EliteBook      | 2         | 2.13%   |
| Dell Vostro       | 2         | 2.13%   |
| Dell Precision    | 2         | 2.13%   |
| Dell OptiPlex     | 2         | 2.13%   |
| ASUS VivoBook     | 2         | 2.13%   |
| ASUS TUF          | 2         | 2.13%   |
| ASRock N68-S3     | 2         | 2.13%   |
| Valve Jupiter     | 1         | 1.06%   |
| TYAN S7012        | 1         | 1.06%   |
| Toshiba Satellite | 1         | 1.06%   |
| System76 Oryx     | 1         | 1.06%   |
| Sony SVE1713A1EW  | 1         | 1.06%   |
| Notebook X170KM-G | 1         | 1.06%   |
| Notebook P7xxTM   | 1         | 1.06%   |
| MSI MS-7C52       | 1         | 1.06%   |
| MSI MS-7C02       | 1         | 1.06%   |
| MSI MS-7996       | 1         | 1.06%   |
| MSI MS-7885       | 1         | 1.06%   |
| MSI MS-7788       | 1         | 1.06%   |
| MSI MS-7693       | 1         | 1.06%   |
| MSI MS-7529       | 1         | 1.06%   |
| MSI MS-7365       | 1         | 1.06%   |
| MSI GP76          | 1         | 1.06%   |
| MSI GE76          | 1         | 1.06%   |
| Microsoft Surface | 1         | 1.06%   |
| Lenovo V330-14ARR | 1         | 1.06%   |
| Lenovo H50-05     | 1         | 1.06%   |
| HP Z440           | 1         | 1.06%   |
| HP xw8400         | 1         | 1.06%   |
| HP ProBook        | 1         | 1.06%   |
| HP ENVY           | 1         | 1.06%   |
| HP Compaq         | 1         | 1.06%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 15        | 15.96%  |
| 2021 | 12        | 12.77%  |
| 2022 | 8         | 8.51%   |
| 2017 | 8         | 8.51%   |
| 2015 | 7         | 7.45%   |
| 2019 | 6         | 6.38%   |
| 2012 | 6         | 6.38%   |
| 2011 | 6         | 6.38%   |
| 2010 | 5         | 5.32%   |
| 2018 | 4         | 4.26%   |
| 2016 | 3         | 3.19%   |
| 2014 | 3         | 3.19%   |
| 2009 | 3         | 3.19%   |
| 2008 | 3         | 3.19%   |
| 2007 | 3         | 3.19%   |
| 2023 | 1         | 1.06%   |
| 2013 | 1         | 1.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 48        | 51.06%  |
| Desktop    | 40        | 42.55%  |
| All in one | 2         | 2.13%   |
| Server     | 2         | 2.13%   |
| Tablet     | 1         | 1.06%   |
| Mini pc    | 1         | 1.06%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 94        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 92        | 97.87%  |
| Yes  | 2         | 2.13%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 21        | 21.88%  |
| 8.01-16.0   | 21        | 21.88%  |
| 4.01-8.0    | 14        | 14.58%  |
| 3.01-4.0    | 14        | 14.58%  |
| 32.01-64.0  | 11        | 11.46%  |
| 64.01-256.0 | 8         | 8.33%   |
| 24.01-32.0  | 4         | 4.17%   |
| 1.01-2.0    | 3         | 3.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 26        | 26.26%  |
| 1.01-2.0   | 26        | 26.26%  |
| 4.01-8.0   | 21        | 21.21%  |
| 0.51-1.0   | 10        | 10.1%   |
| 3.01-4.0   | 7         | 7.07%   |
| 16.01-24.0 | 3         | 3.03%   |
| 0.01-0.5   | 3         | 3.03%   |
| 8.01-16.0  | 2         | 2.02%   |
| 32.01-64.0 | 1         | 1.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 47        | 48.45%  |
| 2      | 26        | 26.8%   |
| 3      | 10        | 10.31%  |
| 4      | 6         | 6.19%   |
| 6      | 4         | 4.12%   |
| 14     | 1         | 1.03%   |
| 11     | 1         | 1.03%   |
| 9      | 1         | 1.03%   |
| 0      | 1         | 1.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 64        | 67.37%  |
| Yes       | 31        | 32.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 85        | 90.43%  |
| No        | 9         | 9.57%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 70        | 74.47%  |
| No        | 24        | 25.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 60        | 63.83%  |
| No        | 34        | 36.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 20        | 21.28%  |
| Italy        | 8         | 8.51%   |
| UK           | 6         | 6.38%   |
| Kazakhstan   | 6         | 6.38%   |
| Brazil       | 6         | 6.38%   |
| Japan        | 5         | 5.32%   |
| Germany      | 5         | 5.32%   |
| Portugal     | 4         | 4.26%   |
| Spain        | 3         | 3.19%   |
| South Africa | 3         | 3.19%   |
| Russia       | 3         | 3.19%   |
| Greece       | 3         | 3.19%   |
| France       | 3         | 3.19%   |
| India        | 2         | 2.13%   |
| Hong Kong    | 2         | 2.13%   |
| China        | 2         | 2.13%   |
| Canada       | 2         | 2.13%   |
| Argentina    | 2         | 2.13%   |
| Switzerland  | 1         | 1.06%   |
| Sweden       | 1         | 1.06%   |
| Serbia       | 1         | 1.06%   |
| Romania      | 1         | 1.06%   |
| Netherlands  | 1         | 1.06%   |
| Mexico       | 1         | 1.06%   |
| Iran         | 1         | 1.06%   |
| Chile        | 1         | 1.06%   |
| Australia    | 1         | 1.06%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Ust-Kamenogorsk   | 4         | 4.17%   |
| Tsukuba           | 4         | 4.17%   |
| Lisbon            | 3         | 3.13%   |
| Chania            | 3         | 3.13%   |
| Sun Prairie       | 2         | 2.08%   |
| Rome              | 2         | 2.08%   |
| Moscow            | 2         | 2.08%   |
| Milan             | 2         | 2.08%   |
| McKinney          | 2         | 2.08%   |
| Karaganda         | 2         | 2.08%   |
| Greater Noida     | 2         | 2.08%   |
| Frignano          | 2         | 2.08%   |
| Fayetteville      | 2         | 2.08%   |
| Cape Town         | 2         | 2.08%   |
| Worpswede         | 1         | 1.04%   |
| Winter Springs    | 1         | 1.04%   |
| Villa Carlos Paz  | 1         | 1.04%   |
| Toronto           | 1         | 1.04%   |
| Tehran            | 1         | 1.04%   |
| Tatuí            | 1         | 1.04%   |
| St Petersburg     | 1         | 1.04%   |
| Springfield       | 1         | 1.04%   |
| Skövde           | 1         | 1.04%   |
| Sham Shui Po      | 1         | 1.04%   |
| Seville           | 1         | 1.04%   |
| Senhora da Hora   | 1         | 1.04%   |
| Sao Paulo         | 1         | 1.04%   |
| Santiago          | 1         | 1.04%   |
| Santa Cruz do Sul | 1         | 1.04%   |
| Saint Paul        | 1         | 1.04%   |
| Round Rock        | 1         | 1.04%   |
| Rock              | 1         | 1.04%   |
| Reno              | 1         | 1.04%   |
| Renazzo           | 1         | 1.04%   |
| Porto Alegre      | 1         | 1.04%   |
| Plainwell         | 1         | 1.04%   |
| Penrith           | 1         | 1.04%   |
| Ōtsu             | 1         | 1.04%   |
| Oberstreit        | 1         | 1.04%   |
| Nanping           | 1         | 1.04%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 27        | 36     | 17.09%  |
| WDC                         | 24        | 52     | 15.19%  |
| Seagate                     | 24        | 34     | 15.19%  |
| Toshiba                     | 11        | 22     | 6.96%   |
| Kingston                    | 11        | 13     | 6.96%   |
| Intel                       | 6         | 7      | 3.8%    |
| Crucial                     | 6         | 7      | 3.8%    |
| Hitachi                     | 5         | 8      | 3.16%   |
| SK hynix                    | 4         | 4      | 2.53%   |
| SanDisk                     | 4         | 6      | 2.53%   |
| HGST                        | 4         | 4      | 2.53%   |
| Transcend                   | 3         | 3      | 1.9%    |
| KIOXIA                      | 3         | 3      | 1.9%    |
| Micron Technology           | 2         | 2      | 1.27%   |
| Hewlett-Packard             | 2         | 3      | 1.27%   |
| Gigabyte Technology         | 2         | 2      | 1.27%   |
| External                    | 2         | 2      | 1.27%   |
| ZHITAI                      | 1         | 2      | 0.63%   |
| Unknown                     | 1         | 2      | 0.63%   |
| Silicon Motion              | 1         | 1      | 0.63%   |
| PNY                         | 1         | 1      | 0.63%   |
| Plextor                     | 1         | 1      | 0.63%   |
| Phison Electronics          | 1         | 1      | 0.63%   |
| Patriot                     | 1         | 1      | 0.63%   |
| Micron/Crucial Technology   | 1         | 1      | 0.63%   |
| Maxtor                      | 1         | 1      | 0.63%   |
| Lexar                       | 1         | 1      | 0.63%   |
| Kingston Technology Company | 1         | 1      | 0.63%   |
| JMicron Technology          | 1         | 1      | 0.63%   |
| Intenso                     | 1         | 1      | 0.63%   |
| GOODRAM                     | 1         | 1      | 0.63%   |
| DUEX                        | 1         | 1      | 0.63%   |
| China                       | 1         | 1      | 0.63%   |
| Apple                       | 1         | 1      | 0.63%   |
| A-DATA Technology           | 1         | 1      | 0.63%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD  | 5         | 2.67%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 2         | 1.07%   |
| WDC WD40EZRX-00SPEB0 4TB         | 2         | 1.07%   |
| WDC WD20EFRX-68EUZN0 2TB         | 2         | 1.07%   |
| WDC WD10SPZX-60Z10T0 1TB         | 2         | 1.07%   |
| WDC WD10EZEX-08WN4A0 1TB         | 2         | 1.07%   |
| Seagate ST2000DM008-2FR102 2TB   | 2         | 1.07%   |
| Seagate ST2000DL003-9VT166 2TB   | 2         | 1.07%   |
| Seagate ST1000DM003-1SB102 1TB   | 2         | 1.07%   |
| Seagate Expansion Desk 3TB       | 2         | 1.07%   |
| Samsung SSD 970 EVO Plus 500GB   | 2         | 1.07%   |
| Samsung SSD 970 EVO 250GB        | 2         | 1.07%   |
| Kingston SA400S37120G 120GB SSD  | 2         | 1.07%   |
| Intel SSD 660P Series 1024GB     | 2         | 1.07%   |
| HGST HTS725050A7E630 500GB       | 2         | 1.07%   |
| External USB3.0 2TB              | 2         | 1.07%   |
| Crucial CT500MX500SSD1 500GB     | 2         | 1.07%   |
| ZHITAI SC001 Active 1TB SSD      | 1         | 0.53%   |
| ZHITAI PC005 Active 512GB        | 1         | 0.53%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1         | 0.53%   |
| WDC WDS480G2G0A-00JH30 480GB SSD | 1         | 0.53%   |
| WDC WDS100T2B0B-00YS70 1TB SSD   | 1         | 0.53%   |
| WDC WD80EFZX-68UW8N0 8TB         | 1         | 0.53%   |
| WDC WD80EFBX-68AZZN0 8TB         | 1         | 0.53%   |
| WDC WD80EFAX-68LHPN0 8TB         | 1         | 0.53%   |
| WDC WD80EFAX-68KNBN0 8TB         | 1         | 0.53%   |
| WDC WD8003FFBX-68B9AN0 8TB       | 1         | 0.53%   |
| WDC WD6003FRYZ-01F0DB0 6TB       | 1         | 0.53%   |
| WDC WD5000BEKT-60KA9T0 500GB     | 1         | 0.53%   |
| WDC WD5000AAKX-22ERMA0 500GB     | 1         | 0.53%   |
| WDC WD5000AAKS-007AA0 500GB      | 1         | 0.53%   |
| WDC WD5000AADS-00S9B0 500GB      | 1         | 0.53%   |
| WDC WD40EJRX-89T1XY0 4TB         | 1         | 0.53%   |
| WDC WD400BD-60LTA0 40GB          | 1         | 0.53%   |
| WDC WD3200AAJS-65B4A0 320GB      | 1         | 0.53%   |
| WDC WD30EZRX-00SPEB0 3TB         | 1         | 0.53%   |
| WDC WD30EZRX-00MMMB0 3TB         | 1         | 0.53%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 1         | 0.53%   |
| WDC WD20EZRX-00D8PB0 2TB         | 1         | 0.53%   |
| WDC WD20EARX-00PASB0 2TB         | 1         | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 24        | 34     | 36.36%  |
| WDC                 | 19        | 44     | 28.79%  |
| Toshiba             | 10        | 17     | 15.15%  |
| Hitachi             | 5         | 8      | 7.58%   |
| HGST                | 4         | 4      | 6.06%   |
| External            | 2         | 2      | 3.03%   |
| Samsung Electronics | 1         | 1      | 1.52%   |
| Maxtor              | 1         | 1      | 1.52%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 15     | 22.45%  |
| Kingston            | 11        | 13     | 22.45%  |
| WDC                 | 4         | 6      | 8.16%   |
| Crucial             | 4         | 5      | 8.16%   |
| Transcend           | 2         | 2      | 4.08%   |
| SanDisk             | 2         | 2      | 4.08%   |
| ZHITAI              | 1         | 1      | 2.04%   |
| Toshiba             | 1         | 3      | 2.04%   |
| SK hynix            | 1         | 1      | 2.04%   |
| PNY                 | 1         | 1      | 2.04%   |
| Plextor             | 1         | 1      | 2.04%   |
| Patriot             | 1         | 1      | 2.04%   |
| Lexar               | 1         | 1      | 2.04%   |
| Intenso             | 1         | 1      | 2.04%   |
| Intel               | 1         | 2      | 2.04%   |
| Hewlett-Packard     | 1         | 1      | 2.04%   |
| GOODRAM             | 1         | 1      | 2.04%   |
| Gigabyte Technology | 1         | 1      | 2.04%   |
| DUEX                | 1         | 1      | 2.04%   |
| China               | 1         | 1      | 2.04%   |
| Apple               | 1         | 1      | 2.04%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 47        | 111    | 34.56%  |
| SSD  | 45        | 61     | 33.09%  |
| NVMe | 43        | 54     | 31.62%  |
| MMC  | 1         | 2      | 0.74%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 65        | 166    | 56.52%  |
| NVMe | 42        | 53     | 36.52%  |
| SAS  | 7         | 7      | 6.09%   |
| MMC  | 1         | 2      | 0.87%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 51        | 66     | 47.22%  |
| 0.51-1.0   | 24        | 43     | 22.22%  |
| 1.01-2.0   | 14        | 17     | 12.96%  |
| 3.01-4.0   | 9         | 16     | 8.33%   |
| 2.01-3.0   | 6         | 13     | 5.56%   |
| 4.01-10.0  | 4         | 17     | 3.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 24        | 24.24%  |
| 501-1000       | 22        | 22.22%  |
| 251-500        | 15        | 15.15%  |
| 1001-2000      | 9         | 9.09%   |
| Unknown        | 8         | 8.08%   |
| 1-20           | 7         | 7.07%   |
| 2001-3000      | 6         | 6.06%   |
| More than 3000 | 4         | 4.04%   |
| 21-50          | 2         | 2.02%   |
| 51-100         | 2         | 2.02%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 23        | 23.23%  |
| 1-20           | 17        | 17.17%  |
| 21-50          | 14        | 14.14%  |
| 251-500        | 12        | 12.12%  |
| 501-1000       | 10        | 10.1%   |
| Unknown        | 8         | 8.08%   |
| 51-100         | 7         | 7.07%   |
| 1001-2000      | 6         | 6.06%   |
| More than 3000 | 2         | 2.02%   |

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
| Works    | 75        | 156    | 66.96%  |
| Detected | 22        | 51     | 19.64%  |
| Malfunc  | 15        | 21     | 13.39%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 50        | 39.06%  |
| AMD                          | 24        | 18.75%  |
| Samsung Electronics          | 16        | 12.5%   |
| SanDisk                      | 4         | 3.13%   |
| Nvidia                       | 4         | 3.13%   |
| Marvell Technology Group     | 4         | 3.13%   |
| SK hynix                     | 3         | 2.34%   |
| Micron/Crucial Technology    | 3         | 2.34%   |
| KIOXIA                       | 3         | 2.34%   |
| JMicron Technology           | 3         | 2.34%   |
| Micron Technology            | 2         | 1.56%   |
| ASMedia Technology           | 2         | 1.56%   |
| Yangtze Memory Technologies  | 1         | 0.78%   |
| Toshiba America Info Systems | 1         | 0.78%   |
| Silicon Motion               | 1         | 0.78%   |
| Realtek Semiconductor        | 1         | 0.78%   |
| Phison Electronics           | 1         | 0.78%   |
| LSI Logic / Symbios Logic    | 1         | 0.78%   |
| Kingston Technology Company  | 1         | 0.78%   |
| Broadcom / LSI               | 1         | 0.78%   |
| Biwin Storage Technology     | 1         | 0.78%   |
| Adaptec                      | 1         | 0.78%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 15        | 9.43%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 7         | 4.4%    |
| AMD 400 Series Chipset SATA Controller                                           | 7         | 4.4%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 5         | 3.14%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 5         | 3.14%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 2.52%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 3         | 1.89%   |
| Nvidia MCP61 SATA Controller                                                     | 3         | 1.89%   |
| Nvidia MCP61 IDE                                                                 | 3         | 1.89%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 3         | 1.89%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 3         | 1.89%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 1.89%   |
| Intel SSD 660P Series                                                            | 3         | 1.89%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 3         | 1.89%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 3         | 1.89%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.89%   |
| SK hynix BC511 NVMe SSD                                                          | 2         | 1.26%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 1.26%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 2         | 1.26%   |
| JMicron JMB58x AHCI SATA controller                                              | 2         | 1.26%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 1.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.26%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 2         | 1.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 1.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 1.26%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 1.26%   |
| Intel 631xESB/632xESB IDE Controller                                             | 2         | 1.26%   |
| Intel 4 Series Chipset PT IDER Controller                                        | 2         | 1.26%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 2         | 1.26%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 2         | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 1.26%   |
| AMD 500 Series Chipset SATA Controller                                           | 2         | 1.26%   |
| Yangtze Memory ZHITAI PC005 NVMe SSD                                             | 1         | 0.63%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 1         | 0.63%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 1         | 0.63%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 1         | 0.63%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 0.63%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD          | 1         | 0.63%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 1         | 0.63%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                            | 1         | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 58        | 44.62%  |
| NVMe | 42        | 32.31%  |
| IDE  | 17        | 13.08%  |
| RAID | 10        | 7.69%   |
| SCSI | 3         | 2.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 63        | 67.02%  |
| AMD    | 31        | 32.98%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 4         | 4.21%   |
| Intel 12th Gen Core i7-12700H           | 3         | 3.16%   |
| Intel Core i7-5820K CPU @ 3.30GHz       | 2         | 2.11%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 2         | 2.11%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz    | 2         | 2.11%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 2         | 2.11%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 2.11%   |
| AMD Ryzen 9 5950X 16-Core Processor     | 2         | 2.11%   |
| AMD Ryzen 5 3600 6-Core Processor       | 2         | 2.11%   |
| AMD Athlon II X2 250 Processor          | 2         | 2.11%   |
| Intel Xeon CPU X5680 @ 3.33GHz          | 1         | 1.05%   |
| Intel Xeon CPU X5355 @ 2.66GHz          | 1         | 1.05%   |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz     | 1         | 1.05%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz     | 1         | 1.05%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz     | 1         | 1.05%   |
| Intel Xeon CPU 5160 @ 3.00GHz           | 1         | 1.05%   |
| Intel Pentium Silver N6000 @ 1.10GHz    | 1         | 1.05%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz  | 1         | 1.05%   |
| Intel Pentium CPU GOLD 6500Y @ 1.10GHz  | 1         | 1.05%   |
| Intel Pentium CPU G3250 @ 3.20GHz       | 1         | 1.05%   |
| Intel Pentium CPU 2020M @ 2.40GHz       | 1         | 1.05%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 1         | 1.05%   |
| Intel Core i7-8700K CPU @ 3.70GHz       | 1         | 1.05%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 1.05%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 1         | 1.05%   |
| Intel Core i7-7700 CPU @ 3.60GHz        | 1         | 1.05%   |
| Intel Core i7-7600U CPU @ 2.80GHz       | 1         | 1.05%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 1         | 1.05%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 1         | 1.05%   |
| Intel Core i7-3840QM CPU @ 2.80GHz      | 1         | 1.05%   |
| Intel Core i7-3720QM CPU @ 2.60GHz      | 1         | 1.05%   |
| Intel Core i7-10870H CPU @ 2.20GHz      | 1         | 1.05%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 1         | 1.05%   |
| Intel Core i5-8600K CPU @ 3.60GHz       | 1         | 1.05%   |
| Intel Core i5-4590 CPU @ 3.30GHz        | 1         | 1.05%   |
| Intel Core i5-4310M CPU @ 2.70GHz       | 1         | 1.05%   |
| Intel Core i5-3360M CPU @ 2.80GHz       | 1         | 1.05%   |
| Intel Core i5-3330 CPU @ 3.00GHz        | 1         | 1.05%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 1         | 1.05%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 1         | 1.05%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 15        | 15.79%  |
| Other                | 14        | 14.74%  |
| Intel Core i7        | 14        | 14.74%  |
| AMD Ryzen 5          | 10        | 10.53%  |
| Intel Xeon           | 6         | 6.32%   |
| Intel Core 2 Duo     | 5         | 5.26%   |
| AMD Ryzen 7          | 5         | 5.26%   |
| AMD Ryzen 9          | 4         | 4.21%   |
| Intel Pentium        | 3         | 3.16%   |
| Intel Core i3        | 3         | 3.16%   |
| AMD FX               | 3         | 3.16%   |
| Intel Celeron        | 2         | 2.11%   |
| AMD Athlon II X2     | 2         | 2.11%   |
| Intel Pentium Silver | 1         | 1.05%   |
| Intel Pentium Dual   | 1         | 1.05%   |
| Intel Atom           | 1         | 1.05%   |
| AMD Ryzen 7 PRO      | 1         | 1.05%   |
| AMD Ryzen 3          | 1         | 1.05%   |
| AMD EPYC             | 1         | 1.05%   |
| AMD E1               | 1         | 1.05%   |
| AMD Athlon           | 1         | 1.05%   |
| AMD A8               | 1         | 1.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 29        | 30.53%  |
| 2      | 29        | 30.53%  |
| 8      | 16        | 16.84%  |
| 6      | 9         | 9.47%   |
| 14     | 4         | 4.21%   |
| 10     | 3         | 3.16%   |
| 16     | 2         | 2.11%   |
| 12     | 2         | 2.11%   |
| 3      | 1         | 1.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 91        | 96.81%  |
| 2      | 3         | 3.19%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 70        | 74.47%  |
| 1      | 24        | 25.53%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 94        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 22.11%  |
| 0x306a9    | 7         | 7.37%   |
| 0x906a3    | 4         | 4.21%   |
| 0x806d1    | 4         | 4.21%   |
| 0x08108109 | 4         | 4.21%   |
| 0x806c1    | 3         | 3.16%   |
| 0x306f2    | 3         | 3.16%   |
| 0x20655    | 3         | 3.16%   |
| 0x08701021 | 3         | 3.16%   |
| 0x906ea    | 2         | 2.11%   |
| 0x406e3    | 2         | 2.11%   |
| 0x406c4    | 2         | 2.11%   |
| 0x306c3    | 2         | 2.11%   |
| 0x1067a    | 2         | 2.11%   |
| 0x0a50000c | 2         | 2.11%   |
| 0x0a201016 | 2         | 2.11%   |
| 0x08600106 | 2         | 2.11%   |
| 0xa0671    | 1         | 1.05%   |
| 0xa0653    | 1         | 1.05%   |
| 0xa0652    | 1         | 1.05%   |
| 0x906e9    | 1         | 1.05%   |
| 0x906c0    | 1         | 1.05%   |
| 0x906a4    | 1         | 1.05%   |
| 0x806ec    | 1         | 1.05%   |
| 0x806ea    | 1         | 1.05%   |
| 0x6fd      | 1         | 1.05%   |
| 0x6fb      | 1         | 1.05%   |
| 0x6fa      | 1         | 1.05%   |
| 0x506e3    | 1         | 1.05%   |
| 0x306e4    | 1         | 1.05%   |
| 0x306d4    | 1         | 1.05%   |
| 0x206c2    | 1         | 1.05%   |
| 0x106c2    | 1         | 1.05%   |
| 0x0a20120a | 1         | 1.05%   |
| 0x08900201 | 1         | 1.05%   |
| 0x08608102 | 1         | 1.05%   |
| 0x0830104d | 1         | 1.05%   |
| 0x0810100b | 1         | 1.05%   |
| 0x08001126 | 1         | 1.05%   |
| 0x07030105 | 1         | 1.05%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 10        | 10.53%  |
| Zen 2            | 8         | 8.42%   |
| IvyBridge        | 8         | 8.42%   |
| Zen 3            | 6         | 6.32%   |
| Westmere         | 6         | 6.32%   |
| Haswell          | 6         | 6.32%   |
| Zen+             | 5         | 5.26%   |
| Icelake          | 5         | 5.26%   |
| Core             | 5         | 5.26%   |
| Alderlake Hybrid | 5         | 5.26%   |
| Skylake          | 4         | 4.21%   |
| Zen              | 3         | 3.16%   |
| TigerLake        | 3         | 3.16%   |
| Penryn           | 3         | 3.16%   |
| Unknown          | 3         | 3.16%   |
| Silvermont       | 2         | 2.11%   |
| Piledriver       | 2         | 2.11%   |
| K10              | 2         | 2.11%   |
| CometLake        | 2         | 2.11%   |
| Tremont          | 1         | 1.05%   |
| SandyBridge      | 1         | 1.05%   |
| Puma             | 1         | 1.05%   |
| Jaguar           | 1         | 1.05%   |
| Bulldozer        | 1         | 1.05%   |
| Broadwell        | 1         | 1.05%   |
| Bonnell          | 1         | 1.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 40        | 36.7%   |
| Nvidia                     | 38        | 34.86%  |
| AMD                        | 30        | 27.52%  |
| Matrox Electronics Systems | 1         | 0.92%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 4.5%    |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 4         | 3.6%    |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 3         | 2.7%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 2.7%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 2.7%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 2.7%    |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 3         | 2.7%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 2.7%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 2.7%    |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 3         | 2.7%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 2.7%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 1.8%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 1.8%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2         | 1.8%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2         | 1.8%    |
| Nvidia GF108 [GeForce GT 630]                                                            | 2         | 1.8%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 1.8%    |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 2         | 1.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 1.8%    |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.8%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.8%    |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 1.8%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 1.8%    |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 2         | 1.8%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 1.8%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.9%    |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 1         | 0.9%    |
| Nvidia TU106BM [GeForce RTX 2070 Mobile / Max-Q]                                         | 1         | 0.9%    |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.9%    |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.9%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.9%    |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 0.9%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.9%    |
| Nvidia GF108GL [Quadro 600]                                                              | 1         | 0.9%    |
| Nvidia GA107M [GeForce RTX 2050]                                                         | 1         | 0.9%    |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 1         | 0.9%    |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                                       | 1         | 0.9%    |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                                      | 1         | 0.9%    |
| Nvidia G96C [GeForce 9400 GT]                                                            | 1         | 0.9%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 28        | 29.79%  |
| 1 x Intel      | 27        | 28.72%  |
| 1 x Nvidia     | 24        | 25.53%  |
| Intel + Nvidia | 12        | 12.77%  |
| 2 x AMD        | 1         | 1.06%   |
| 1 x Matrox     | 1         | 1.06%   |
| AMD + Nvidia   | 1         | 1.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 75        | 78.95%  |
| Proprietary | 17        | 17.89%  |
| Unknown     | 3         | 3.16%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 46        | 48.42%  |
| 0.01-0.5   | 11        | 11.58%  |
| 0.51-1.0   | 10        | 10.53%  |
| 7.01-8.0   | 8         | 8.42%   |
| 1.01-2.0   | 7         | 7.37%   |
| 5.01-6.0   | 4         | 4.21%   |
| 8.01-16.0  | 4         | 4.21%   |
| 3.01-4.0   | 3         | 3.16%   |
| 2.01-3.0   | 1         | 1.05%   |
| 16.01-24.0 | 1         | 1.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 13        | 13%     |
| Samsung Electronics     | 12        | 12%     |
| AU Optronics            | 9         | 9%      |
| Hewlett-Packard         | 8         | 8%      |
| LG Display              | 7         | 7%      |
| Dell                    | 7         | 7%      |
| Chimei Innolux          | 7         | 7%      |
| BenQ                    | 5         | 5%      |
| Goldstar                | 4         | 4%      |
| Lenovo                  | 3         | 3%      |
| AOC                     | 3         | 3%      |
| Ancor Communications    | 3         | 3%      |
| Sharp                   | 2         | 2%      |
| Acer                    | 2         | 2%      |
| Wacom                   | 1         | 1%      |
| Valve                   | 1         | 1%      |
| UGD                     | 1         | 1%      |
| Sony                    | 1         | 1%      |
| PANDA                   | 1         | 1%      |
| IOD                     | 1         | 1%      |
| Iiyama                  | 1         | 1%      |
| Hyundai ImageQuest      | 1         | 1%      |
| HKC                     | 1         | 1%      |
| GDH                     | 1         | 1%      |
| CTC                     | 1         | 1%      |
| Chi Mei Optoelectronics | 1         | 1%      |
| ASUSTek Computer        | 1         | 1%      |
| Apple                   | 1         | 1%      |
| Unknown                 | 1         | 1%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC416E 2880x1620 344x194mm 15.5-inch | 2         | 1.96%   |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch             | 2         | 1.96%   |
| Goldstar ULTRAGEAR GSM7765 2560x1440 697x392mm 31.5-inch              | 2         | 1.96%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 2         | 1.96%   |
| Wacom Cintiq 22HDT WAC1037 1920x1080 476x268mm 21.5-inch              | 1         | 0.98%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 0.98%   |
| UGD LCD Monitor UGD1302 1920x1080 290x160mm 13.0-inch                 | 1         | 0.98%   |
| Sony TV SNY8102 1360x768                                              | 1         | 0.98%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 382x215mm 17.3-inch               | 1         | 0.98%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 0.98%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch     | 1         | 0.98%   |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch   | 1         | 0.98%   |
| Samsung Electronics SyncMaster SAM03F2 1680x1050                      | 1         | 0.98%   |
| Samsung Electronics SyncMaster SAM03F0 1680x1050 433x271mm 20.1-inch  | 1         | 0.98%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 376x301mm 19.0-inch  | 1         | 0.98%   |
| Samsung Electronics SyncMaster SAM01AD 1600x1200 408x306mm 20.1-inch  | 1         | 0.98%   |
| Samsung Electronics SMS27A650 SAM082D 1920x1080 598x336mm 27.0-inch   | 1         | 0.98%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch    | 1         | 0.98%   |
| Samsung Electronics SM2333T SAM0736 1920x1080 477x268mm 21.5-inch     | 1         | 0.98%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch     | 1         | 0.98%   |
| Samsung Electronics LCD Monitor U28D590 3840x2160                     | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 0.98%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 0.98%   |
| LG Display LCD Monitor LGD0625 1920x1080 340x190mm 15.3-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD0353 1366x768 345x194mm 15.6-inch           | 1         | 0.98%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD028A 1366x768 344x194mm 15.5-inch           | 1         | 0.98%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch           | 1         | 0.98%   |
| Lenovo LEN L171p LEN24C9 1280x1024 338x270mm 17.0-inch                | 1         | 0.98%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x189mm 14.1-inch               | 1         | 0.98%   |
| Lenovo LCD Monitor LEN4031 1280x800 304x190mm 14.1-inch               | 1         | 0.98%   |
| IOD LCD-GL211X IOD151D 1920x1080 458x258mm 20.7-inch                  | 1         | 0.98%   |
| Iiyama PL2783Q IVM661F 2560x1440 597x336mm 27.0-inch                  | 1         | 0.98%   |
| Hyundai ImageQuest B70A HIQ5004 1280x1024 337x270mm 17.0-inch         | 1         | 0.98%   |
| HKC LCD Monitor HKC36B1 1366x768 309x174mm 14.0-inch                  | 1         | 0.98%   |
| Hewlett-Packard Z24i HWP309E 1920x1200 518x324mm 24.1-inch            | 1         | 0.98%   |
| Hewlett-Packard x23LED HWP2912 1920x1080 509x286mm 23.0-inch          | 1         | 0.98%   |
| Hewlett-Packard P223 HPN3392 1920x1080 477x268mm 21.5-inch            | 1         | 0.98%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 44        | 44.9%   |
| 1366x768 (WXGA)    | 13        | 13.27%  |
| 3840x2160 (4K)     | 6         | 6.12%   |
| 2560x1440 (QHD)    | 5         | 5.1%    |
| 1280x1024 (SXGA)   | 5         | 5.1%    |
| 1680x1050 (WSXGA+) | 4         | 4.08%   |
| 1920x1200 (WUXGA)  | 3         | 3.06%   |
| 2880x1620          | 2         | 2.04%   |
| 1600x900 (HD+)     | 2         | 2.04%   |
| 1440x900 (WXGA+)   | 2         | 2.04%   |
| 1360x768           | 2         | 2.04%   |
| 1280x800 (WXGA)    | 2         | 2.04%   |
| 800x1280           | 1         | 1.02%   |
| 3440x1440          | 1         | 1.02%   |
| 3200x1080          | 1         | 1.02%   |
| 2256x1504          | 1         | 1.02%   |
| 1920x1280          | 1         | 1.02%   |
| 1600x1200          | 1         | 1.02%   |
| 1024x768 (XGA)     | 1         | 1.02%   |
| Unknown            | 1         | 1.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 21        | 21%     |
| 27      | 11        | 11%     |
| 13      | 9         | 9%      |
| 17      | 8         | 8%      |
| 14      | 8         | 8%      |
| 24      | 7         | 7%      |
| 21      | 5         | 5%      |
| 31      | 3         | 3%      |
| 23      | 3         | 3%      |
| 22      | 3         | 3%      |
| 20      | 3         | 3%      |
| 19      | 3         | 3%      |
| 18      | 3         | 3%      |
| 16      | 3         | 3%      |
| Unknown | 3         | 3%      |
| 72      | 1         | 1%      |
| 52      | 1         | 1%      |
| 34      | 1         | 1%      |
| 12      | 1         | 1%      |
| 11      | 1         | 1%      |
| 10      | 1         | 1%      |
| 7       | 1         | 1%      |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 40        | 40.4%   |
| 501-600     | 19        | 19.19%  |
| 401-500     | 15        | 15.15%  |
| 351-400     | 9         | 9.09%   |
| 201-300     | 5         | 5.05%   |
| 601-700     | 4         | 4.04%   |
| Unknown     | 3         | 3.03%   |
| 701-800     | 1         | 1.01%   |
| 1501-2000   | 1         | 1.01%   |
| 1001-1500   | 1         | 1.01%   |
| 1-100       | 1         | 1.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 63        | 71.59%  |
| 16/10   | 12        | 13.64%  |
| 5/4     | 5         | 5.68%   |
| 4/3     | 2         | 2.27%   |
| 3/2     | 2         | 2.27%   |
| Unknown | 2         | 2.27%   |
| 21/9    | 1         | 1.14%   |
| 0.67    | 1         | 1.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 23        | 23.23%  |
| 81-90          | 16        | 16.16%  |
| 201-250        | 12        | 12.12%  |
| 301-350        | 11        | 11.11%  |
| 151-200        | 9         | 9.09%   |
| 141-150        | 5         | 5.05%   |
| 121-130        | 5         | 5.05%   |
| 351-500        | 4         | 4.04%   |
| 251-300        | 3         | 3.03%   |
| Unknown        | 3         | 3.03%   |
| More than 1000 | 2         | 2.02%   |
| 51-60          | 2         | 2.02%   |
| 71-80          | 1         | 1.01%   |
| 61-70          | 1         | 1.01%   |
| 1-40           | 1         | 1.01%   |
| 111-120        | 1         | 1.01%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 35        | 36.08%  |
| 121-160       | 29        | 29.9%   |
| 101-120       | 21        | 21.65%  |
| 161-240       | 6         | 6.19%   |
| Unknown       | 3         | 3.09%   |
| 1-50          | 2         | 2.06%   |
| More than 240 | 1         | 1.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 75        | 79.79%  |
| 2     | 11        | 11.7%   |
| 0     | 6         | 6.38%   |
| 4     | 1         | 1.06%   |
| 3     | 1         | 1.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 53        | 38.13%  |
| Intel                    | 48        | 34.53%  |
| Qualcomm Atheros         | 7         | 5.04%   |
| Broadcom                 | 6         | 4.32%   |
| MediaTek                 | 4         | 2.88%   |
| Broadcom Limited         | 4         | 2.88%   |
| Ralink Technology        | 3         | 2.16%   |
| Nvidia                   | 3         | 2.16%   |
| ASIX Electronics         | 3         | 2.16%   |
| TP-Link                  | 1         | 0.72%   |
| Sitecom Europe           | 1         | 0.72%   |
| Ralink                   | 1         | 0.72%   |
| Qualcomm                 | 1         | 0.72%   |
| Marvell Technology Group | 1         | 0.72%   |
| Huawei Technologies      | 1         | 0.72%   |
| Hewlett-Packard          | 1         | 0.72%   |
| Dell                     | 1         | 0.72%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35        | 20.96%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 3.59%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 3.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 2.99%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5         | 2.99%   |
| Intel Wireless 8265 / 8275                                        | 4         | 2.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 2.4%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.8%    |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.8%    |
| Ralink MT7601U Wireless Adapter                                   | 3         | 1.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 1.8%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 2         | 1.2%    |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 1.2%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 1.2%    |
| Nvidia MCP61 Ethernet                                             | 2         | 1.2%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 2         | 1.2%    |
| Intel Wireless 8260                                               | 2         | 1.2%    |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.2%    |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 1.2%    |
| Intel Ethernet Controller I225-V                                  | 2         | 1.2%    |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.2%    |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.2%    |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 1.2%    |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.2%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 1.2%    |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 2         | 1.2%    |
| Broadcom Limited BCM43228 802.11a/b/g/n                           | 2         | 1.2%    |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.2%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 0.6%    |
| Sitecom Europe WL-113 rev 2 Wireless Network USB Adapter          | 1         | 0.6%    |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.6%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.6%    |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.6%    |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.6%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.6%    |
| Realtek Realtek WLAN controller                                   | 1         | 0.6%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 1         | 0.6%    |
| Qualcomm SDM630-MTP _SN:0B9EB96E                                  | 1         | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 36        | 50.7%   |
| Realtek Semiconductor | 14        | 19.72%  |
| Qualcomm Atheros      | 5         | 7.04%   |
| MediaTek              | 4         | 5.63%   |
| Ralink Technology     | 3         | 4.23%   |
| Broadcom Limited      | 3         | 4.23%   |
| Broadcom              | 2         | 2.82%   |
| TP-Link               | 1         | 1.41%   |
| Sitecom Europe        | 1         | 1.41%   |
| Ralink                | 1         | 1.41%   |
| Dell                  | 1         | 1.41%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                   | 6         | 8.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter              | 5         | 6.94%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                | 5         | 6.94%   |
| Intel Wireless 8265 / 8275                                            | 4         | 5.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter              | 3         | 4.17%   |
| Ralink MT7601U Wireless Adapter                                       | 3         | 4.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                          | 3         | 4.17%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                               | 2         | 2.78%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter         | 2         | 2.78%   |
| Intel Wireless 8260                                                   | 2         | 2.78%   |
| Intel Wi-Fi 6 AX201                                                   | 2         | 2.78%   |
| Intel Tiger Lake PCH CNVi WiFi                                        | 2         | 2.78%   |
| Intel Alder Lake-P PCH CNVi WiFi                                      | 2         | 2.78%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                               | 2         | 2.78%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                           | 1         | 1.39%   |
| Sitecom Europe WL-113 rev 2 Wireless Network USB Adapter              | 1         | 1.39%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                    | 1         | 1.39%   |
| Realtek RTL8723DE Wireless Network Adapter                            | 1         | 1.39%   |
| Realtek RTL8191SEvB Wireless LAN Controller                           | 1         | 1.39%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                            | 1         | 1.39%   |
| Realtek Realtek WLAN controller                                       | 1         | 1.39%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                             | 1         | 1.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter            | 1         | 1.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                      | 1         | 1.39%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                      | 1         | 1.39%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)        | 1         | 1.39%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                      | 1         | 1.39%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                               | 1         | 1.39%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter         | 1         | 1.39%   |
| Intel Wireless-AC 9260                                                | 1         | 1.39%   |
| Intel Wireless 7260                                                   | 1         | 1.39%   |
| Intel Wireless 3165                                                   | 1         | 1.39%   |
| Intel Wi-Fi 6 AX201 160MHz                                            | 1         | 1.39%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection         | 1         | 1.39%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                      | 1         | 1.39%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                       | 1         | 1.39%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                     | 1         | 1.39%   |
| Intel Comet Lake PCH CNVi WiFi                                        | 1         | 1.39%   |
| Intel Centrino Ultimate-N 6300                                        | 1         | 1.39%   |
| Dell Wireless 1450 Dual-band (802.11a/b/g) Adapter [Intersil ISL3887] | 1         | 1.39%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 48        | 52.17%  |
| Intel                    | 26        | 28.26%  |
| Broadcom                 | 5         | 5.43%   |
| Qualcomm Atheros         | 3         | 3.26%   |
| Nvidia                   | 3         | 3.26%   |
| ASIX Electronics         | 3         | 3.26%   |
| Qualcomm                 | 1         | 1.09%   |
| Marvell Technology Group | 1         | 1.09%   |
| Huawei Technologies      | 1         | 1.09%   |
| Broadcom Limited         | 1         | 1.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35        | 37.23%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 6.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 4.26%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 3.19%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 2.13%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 2.13%   |
| Nvidia MCP61 Ethernet                                             | 2         | 2.13%   |
| Intel Ethernet Controller I225-V                                  | 2         | 2.13%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 2.13%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.13%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 2.13%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 2.13%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 2         | 2.13%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 2.13%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 1.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.06%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.06%   |
| Qualcomm SDM630-MTP _SN:0B9EB96E                                  | 1         | 1.06%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.06%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.06%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.06%   |
| Intel I350 Gigabit Network Connection                             | 1         | 1.06%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.06%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.06%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 1.06%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.06%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.06%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 1.06%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.06%   |
| Intel Ethernet Connection (12) I219-V                             | 1         | 1.06%   |
| Intel 82576 Gigabit Network Connection                            | 1         | 1.06%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.06%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.06%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1         | 1.06%   |
| Huawei E353/E3131                                                 | 1         | 1.06%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.06%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1         | 1.06%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 1         | 1.06%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 1         | 1.06%   |
| ASIX AX88772A Fast Ethernet                                       | 1         | 1.06%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 85        | 54.49%  |
| WiFi     | 70        | 44.87%  |
| Modem    | 1         | 0.64%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 53        | 52.48%  |
| Ethernet | 48        | 47.52%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 50        | 52.63%  |
| 1     | 40        | 42.11%  |
| 4     | 2         | 2.11%   |
| 3     | 2         | 2.11%   |
| 5     | 1         | 1.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 79        | 83.16%  |
| Yes  | 16        | 16.84%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 31        | 50.82%  |
| Realtek Semiconductor           | 8         | 13.11%  |
| Cambridge Silicon Radio         | 5         | 8.2%    |
| Broadcom                        | 5         | 8.2%    |
| IMC Networks                    | 4         | 6.56%   |
| MediaTek                        | 2         | 3.28%   |
| Apple                           | 2         | 3.28%   |
| TP-Link                         | 1         | 1.64%   |
| Qualcomm Atheros Communications | 1         | 1.64%   |
| Micro Star International        | 1         | 1.64%   |
| Foxconn / Hon Hai               | 1         | 1.64%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 9         | 14.75%  |
| Intel AX201 Bluetooth                               | 7         | 11.48%  |
| Intel AX200 Bluetooth                               | 6         | 9.84%   |
| Intel AX210 Bluetooth                               | 5         | 8.2%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5         | 8.2%    |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 6.56%   |
| Realtek Bluetooth Radio                             | 4         | 6.56%   |
| IMC Networks Wireless_Device                        | 3         | 4.92%   |
| MediaTek Wireless_Device                            | 2         | 3.28%   |
| TP-Link UB500 Adapter                               | 1         | 1.64%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 1.64%   |
| Micro Star International Bluetooth Dongle           | 1         | 1.64%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.64%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.64%   |
| Intel Bluetooth Device                              | 1         | 1.64%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 1.64%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.64%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 1.64%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.64%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.64%   |
| Broadcom BCM20702A0                                 | 1         | 1.64%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.64%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 1.64%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.64%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 1         | 1.64%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 57        | 42.22%  |
| AMD                    | 33        | 24.44%  |
| Nvidia                 | 32        | 23.7%   |
| Creative Labs          | 4         | 2.96%   |
| C-Media Electronics    | 2         | 1.48%   |
| ASUSTek Computer       | 2         | 1.48%   |
| Texas Instruments      | 1         | 0.74%   |
| RME                    | 1         | 0.74%   |
| Kingston Technology    | 1         | 0.74%   |
| Holtek Semiconductor   | 1         | 0.74%   |
| Generalplus Technology | 1         | 0.74%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 13        | 8.13%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 7         | 4.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 4.38%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 6         | 3.75%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 3.75%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 3.75%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 3.13%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 5         | 3.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 3.13%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 2.5%    |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 2.5%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.88%   |
| Nvidia MCP61 High Definition Audio                                                                | 3         | 1.88%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.88%   |
| Nvidia Audio device                                                                               | 3         | 1.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.88%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 1.88%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 3         | 1.88%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 3         | 1.88%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 1.25%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 1.25%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 1.25%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 1.25%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 2         | 1.25%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.25%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.25%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2         | 1.25%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.25%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 1.25%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus]   | 2         | 1.25%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 1.25%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.25%   |
| AMD Navi 10 HDMI Audio                                                                            | 2         | 1.25%   |
| AMD FCH Azalia Controller                                                                         | 2         | 1.25%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.63%   |
| RME ADI-2 DAC (58825307)                                                                          | 1         | 0.63%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.63%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 18        | 18.56%  |
| SK hynix            | 16        | 16.49%  |
| Kingston            | 16        | 16.49%  |
| Corsair             | 9         | 9.28%   |
| Crucial             | 6         | 6.19%   |
| Micron Technology   | 5         | 5.15%   |
| Unknown             | 4         | 4.12%   |
| G.Skill             | 3         | 3.09%   |
| Team                | 2         | 2.06%   |
| Goodram             | 2         | 2.06%   |
| AMD                 | 2         | 2.06%   |
| A-DATA Technology   | 2         | 2.06%   |
| Unknown             | 2         | 2.06%   |
| Transcend           | 1         | 1.03%   |
| Strontium           | 1         | 1.03%   |
| Smart               | 1         | 1.03%   |
| Silicon Power       | 1         | 1.03%   |
| Patriot             | 1         | 1.03%   |
| Neo Forza           | 1         | 1.03%   |
| Nanya Technology    | 1         | 1.03%   |
| Innodisk            | 1         | 1.03%   |
| GLOWAY              | 1         | 1.03%   |
| Essencore Limited   | 1         | 1.03%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                             | 2         | 1.89%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB Row Of Chips LPDDR5 6400MT/s | 2         | 1.89%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.89%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.89%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.89%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 2         | 1.89%   |
| Corsair RAM CMSX32GX4M2A2666C18 16GB SODIMM DDR4 2667MT/s        | 2         | 1.89%   |
| Unknown                                                          | 2         | 1.89%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                         | 1         | 0.94%   |
| Unknown RAM Module 2GB DIMM DDR2 533MT/s                         | 1         | 0.94%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                         | 1         | 0.94%   |
| Transcend RAM JM1600KLN-8GK 4096MB DIMM DDR3 1600MT/s            | 1         | 0.94%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3733MT/s               | 1         | 0.94%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s              | 1         | 0.94%   |
| Strontium RAM SRT4G86U1-P9H 4096MB DIMM DDR3 1333MT/s            | 1         | 0.94%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s              | 1         | 0.94%   |
| SK hynix RAM HYMP512F72CP8N3-Y5 1024MB FB-DIMM DDR2 667MT/s      | 1         | 0.94%   |
| SK hynix RAM HMT41GV7BMR4A-H9 16GB DIMM 1333MT/s                 | 1         | 0.94%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 0.94%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s             | 1         | 0.94%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.94%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.94%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.94%   |
| SK hynix RAM HMT31GR7BFR4A-H9 8192MB DIMM 1333MT/s               | 1         | 0.94%   |
| SK hynix RAM HMT125R7BFR8C-H9 2GB DIMM 1333MT/s                  | 1         | 0.94%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.94%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.94%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.94%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 0.94%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 0.94%   |
| SK hynix RAM HMA81GR7CJR8N-XN 8192MB DIMM DDR4 3200MT/s          | 1         | 0.94%   |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 0.94%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB SODIMM LPDDR3 1867MT/s           | 1         | 0.94%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB Chip LPDDR3 1867MT/s             | 1         | 0.94%   |
| Silicon Power RAM DCLT4GN568S V 4096MB DIMM DDR3 1600MT/s        | 1         | 0.94%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 0.94%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 1         | 0.94%   |
| Samsung RAM M471B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.94%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.94%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 0.94%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 42        | 51.85%  |
| DDR3    | 23        | 28.4%   |
| DDR2    | 4         | 4.94%   |
| LPDDR5  | 3         | 3.7%    |
| SDRAM   | 2         | 2.47%   |
| LPDDR3  | 2         | 2.47%   |
| DDR5    | 2         | 2.47%   |
| LPDDR4  | 1         | 1.23%   |
| DDR     | 1         | 1.23%   |
| Unknown | 1         | 1.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 39        | 47.56%  |
| DIMM         | 35        | 42.68%  |
| Row Of Chips | 5         | 6.1%    |
| RIMM         | 1         | 1.22%   |
| FB-DIMM      | 1         | 1.22%   |
| Chip         | 1         | 1.22%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 38        | 41.3%   |
| 4096  | 27        | 29.35%  |
| 16384 | 14        | 15.22%  |
| 2048  | 7         | 7.61%   |
| 32768 | 4         | 4.35%   |
| 1024  | 2         | 2.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 19        | 20.88%  |
| 1600    | 18        | 19.78%  |
| 2667    | 8         | 8.79%   |
| 2400    | 7         | 7.69%   |
| 1333    | 5         | 5.49%   |
| 3800    | 3         | 3.3%    |
| 3600    | 3         | 3.3%    |
| 6400    | 2         | 2.2%    |
| 4800    | 2         | 2.2%    |
| 3733    | 2         | 2.2%    |
| 2133    | 2         | 2.2%    |
| 1867    | 2         | 2.2%    |
| 1334    | 2         | 2.2%    |
| 667     | 2         | 2.2%    |
| Unknown | 2         | 2.2%    |
| 65535   | 1         | 1.1%    |
| 4267    | 1         | 1.1%    |
| 4266    | 1         | 1.1%    |
| 3400    | 1         | 1.1%    |
| 2933    | 1         | 1.1%    |
| 2800    | 1         | 1.1%    |
| 2472    | 1         | 1.1%    |
| 2187    | 1         | 1.1%    |
| 1866    | 1         | 1.1%    |
| 975     | 1         | 1.1%    |
| 701     | 1         | 1.1%    |
| 533     | 1         | 1.1%    |

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
| Chicony Electronics                    | 14        | 24.14%  |
| Logitech                               | 8         | 13.79%  |
| Bison Electronics                      | 7         | 12.07%  |
| Microdia                               | 5         | 8.62%   |
| Realtek Semiconductor                  | 4         | 6.9%    |
| Syntek                                 | 3         | 5.17%   |
| Sonix Technology                       | 3         | 5.17%   |
| Luxvisions Innotech Limited            | 3         | 5.17%   |
| Samsung Electronics                    | 2         | 3.45%   |
| Quanta                                 | 2         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.45%   |
| Z-Star Microelectronics                | 1         | 1.72%   |
| Sunplus Innovation Technology          | 1         | 1.72%   |
| Microsoft                              | 1         | 1.72%   |
| Lenovo                                 | 1         | 1.72%   |
| Apple                                  | 1         | 1.72%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Logitech Webcam C270                                 | 3         | 5.17%   |
| Chicony Integrated Camera                            | 3         | 5.17%   |
| Bison HD Webcam                                      | 3         | 5.17%   |
| Syntek Integrated Camera                             | 2         | 3.45%   |
| Sonix USB2.0 FHD UVC WebCam                          | 2         | 3.45%   |
| Samsung Galaxy series, misc. (MTP mode)              | 2         | 3.45%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 2         | 3.45%   |
| Chicony HD User Facing                               | 2         | 3.45%   |
| Bison BisonCam,NB Pro                                | 2         | 3.45%   |
| Z-Star Vimicro USB2.0 Camera                         | 1         | 1.72%   |
| Syntek USB2.0 Camera                                 | 1         | 1.72%   |
| Sunplus Integrated_Webcam_HD                         | 1         | 1.72%   |
| Sonix USB2.0 HD UVC WebCam                           | 1         | 1.72%   |
| Realtek Laptop Camera                                | 1         | 1.72%   |
| Realtek Integrated Camera                            | 1         | 1.72%   |
| Realtek EasyCamera                                   | 1         | 1.72%   |
| Realtek Bluetooth Radio                              | 1         | 1.72%   |
| Quanta HP Wide Vision HD Camera                      | 1         | 1.72%   |
| Quanta HP Webcam                                     | 1         | 1.72%   |
| Microsoft LifeCam HD-3000                            | 1         | 1.72%   |
| Microdia Laptop_Integrated_Webcam_2M                 | 1         | 1.72%   |
| Microdia Integrated_Webcam_HD                        | 1         | 1.72%   |
| Microdia Integrated Webcam                           | 1         | 1.72%   |
| Microdia Dell Integrated HD Webcam                   | 1         | 1.72%   |
| Microdia Camera                                      | 1         | 1.72%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.72%   |
| Logitech QuickCam Pro 9000                           | 1         | 1.72%   |
| Logitech Logitech Webcam C160                        | 1         | 1.72%   |
| Logitech HD Webcam C910                              | 1         | 1.72%   |
| Logitech C922 Pro Stream Webcam                      | 1         | 1.72%   |
| Logitech C920 PRO HD Webcam                          | 1         | 1.72%   |
| Lenovo Integrated Webcam [R5U877]                    | 1         | 1.72%   |
| Chicony Web Camera - FHD                             | 1         | 1.72%   |
| Chicony Integrated Camera [ThinkPad]                 | 1         | 1.72%   |
| Chicony Integrated Camera (1280x720@30)              | 1         | 1.72%   |
| Chicony HP TrueVision HD Camera                      | 1         | 1.72%   |
| Chicony HP True Vision 5MP Camera                    | 1         | 1.72%   |
| Chicony HP HD Webcam [Fixed]                         | 1         | 1.72%   |
| Chicony HP HD Camera                                 | 1         | 1.72%   |
| Chicony FJ Camera                                    | 1         | 1.72%   |

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
| Synaptics TouchPad                                              | 1         | 7.14%   |
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
| 0     | 59        | 62.11%  |
| 1     | 24        | 25.26%  |
| 2     | 8         | 8.42%   |
| 4     | 2         | 2.11%   |
| 5     | 1         | 1.05%   |
| 3     | 1         | 1.05%   |

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

