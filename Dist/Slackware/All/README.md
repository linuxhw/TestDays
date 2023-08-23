Slackware - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Slackware.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Slackware/Desktop/README.md) and [notebooks](/Dist/Slackware/Notebook/README.md).

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

Total: 193

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
| Acer          | Extensa 5220                | Notebook    | [30ca0c3efa](https://linux-hardware.org/?probe=30ca0c3efa) | Dec 06, 2022 |
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
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [9bfc03d98e](https://linux-hardware.org/?probe=9bfc03d98e) | Aug 20, 2022 |
| Dell          | 0200DY A03                  | Desktop     | [e0e14cd1f2](https://linux-hardware.org/?probe=e0e14cd1f2) | Aug 19, 2022 |
| Fujitsu       | LIFEBOOK A544               | Notebook    | [e5785106f1](https://linux-hardware.org/?probe=e5785106f1) | Aug 09, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [b9cde08864](https://linux-hardware.org/?probe=b9cde08864) | Jul 25, 2022 |
| Dell          | 072XWF A03                  | Server      | [d083ad669a](https://linux-hardware.org/?probe=d083ad669a) | Jun 29, 2022 |
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
| HP            | Laptop 15-bs2xx             | Notebook    | [bf53c3c878](https://linux-hardware.org/?probe=bf53c3c878) | Jan 02, 2022 |
| MSI           | H61M-P31                    | Desktop     | [58651bba67](https://linux-hardware.org/?probe=58651bba67) | Dec 07, 2021 |
| HP            | Laptop 15-bs1xx             | Notebook    | [b6c9f34c4c](https://linux-hardware.org/?probe=b6c9f34c4c) | Dec 07, 2021 |
| HP            | 21B4 A01                    | Desktop     | [871b196cc2](https://linux-hardware.org/?probe=871b196cc2) | Nov 21, 2021 |
| HP            | 21B4 A01                    | Desktop     | [259232d98b](https://linux-hardware.org/?probe=259232d98b) | Nov 21, 2021 |
| Supermicro    | X9DA7/E                     | Desktop     | [3fc1ef2b58](https://linux-hardware.org/?probe=3fc1ef2b58) | Nov 09, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [2e3e23fb54](https://linux-hardware.org/?probe=2e3e23fb54) | Nov 01, 2021 |
| System76      | Oryx Pro                    | Notebook    | [3cd05d02a8](https://linux-hardware.org/?probe=3cd05d02a8) | Oct 27, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [b7df25ba5d](https://linux-hardware.org/?probe=b7df25ba5d) | Oct 25, 2021 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [64e5ee1691](https://linux-hardware.org/?probe=64e5ee1691) | Oct 13, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [17d37c5316](https://linux-hardware.org/?probe=17d37c5316) | Oct 12, 2021 |
| MSI           | Modern 14 B11MO             | Notebook    | [e8f13facfd](https://linux-hardware.org/?probe=e8f13facfd) | Oct 03, 2021 |
| MSI           | Modern 14 B11MO             | Notebook    | [9f5c2e0fde](https://linux-hardware.org/?probe=9f5c2e0fde) | Sep 27, 2021 |
| Intel         | DZ77RE-75K AAG39010-302     | Desktop     | [069c508e80](https://linux-hardware.org/?probe=069c508e80) | Sep 25, 2021 |
| Shuttle       | NC03U                       | Desktop     | [c5f76c4400](https://linux-hardware.org/?probe=c5f76c4400) | Sep 22, 2021 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [13b9ce0773](https://linux-hardware.org/?probe=13b9ce0773) | Sep 22, 2021 |
| Dynabook      | PORTEGE X50-G               | Notebook    | [da8279a7a9](https://linux-hardware.org/?probe=da8279a7a9) | Sep 22, 2021 |
| Dell          | Inspiron 15-3552            | Notebook    | [f76339b0af](https://linux-hardware.org/?probe=f76339b0af) | Aug 31, 2021 |
| HP            | 245 G7 Notebook PC          | Notebook    | [c0806e4955](https://linux-hardware.org/?probe=c0806e4955) | Aug 23, 2021 |
| HP            | 245 G7 Notebook PC          | Notebook    | [c409287d23](https://linux-hardware.org/?probe=c409287d23) | Aug 23, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [4c196e1abd](https://linux-hardware.org/?probe=4c196e1abd) | Aug 18, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [53a1179121](https://linux-hardware.org/?probe=53a1179121) | Aug 12, 2021 |
| HP            | EliteBook Folio 1020 G1 ... | Notebook    | [32e6ec699f](https://linux-hardware.org/?probe=32e6ec699f) | Aug 09, 2021 |
| HP            | EliteBook Folio 1020 G1 ... | Notebook    | [7facd0568b](https://linux-hardware.org/?probe=7facd0568b) | Aug 09, 2021 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [5d6732e14c](https://linux-hardware.org/?probe=5d6732e14c) | Aug 09, 2021 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [9ac798b737](https://linux-hardware.org/?probe=9ac798b737) | Aug 05, 2021 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [095745e5fb](https://linux-hardware.org/?probe=095745e5fb) | Jul 06, 2021 |
| HP            | 158A                        | Desktop     | [d612124939](https://linux-hardware.org/?probe=d612124939) | Jun 21, 2021 |
| ASRock        | H310CM-HDV                  | Desktop     | [3291e5d2de](https://linux-hardware.org/?probe=3291e5d2de) | Jun 19, 2021 |
| ASRock        | H87M Pro4                   | Desktop     | [8d4b7f121d](https://linux-hardware.org/?probe=8d4b7f121d) | Jun 02, 2021 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [6e60025ac5](https://linux-hardware.org/?probe=6e60025ac5) | May 25, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [3e5f76719a](https://linux-hardware.org/?probe=3e5f76719a) | May 24, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [c75f9d5c0d](https://linux-hardware.org/?probe=c75f9d5c0d) | May 23, 2021 |
| Dell          | 0PTTT9 A00                  | Desktop     | [e5b81a0da1](https://linux-hardware.org/?probe=e5b81a0da1) | May 20, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [cabba2c402](https://linux-hardware.org/?probe=cabba2c402) | May 19, 2021 |
| Gigabyte      | N3160TN                     | Desktop     | [2fd537312f](https://linux-hardware.org/?probe=2fd537312f) | May 14, 2021 |
| MSI           | G31TM-P21                   | Desktop     | [91c11ae82e](https://linux-hardware.org/?probe=91c11ae82e) | May 07, 2021 |
| HP            | 15 Notebook PC              | Notebook    | [bec2fe2e78](https://linux-hardware.org/?probe=bec2fe2e78) | Mar 21, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [5189fbc4c9](https://linux-hardware.org/?probe=5189fbc4c9) | Mar 10, 2021 |
| Foxconn       | 2ADA                        | Desktop     | [425d15a5ce](https://linux-hardware.org/?probe=425d15a5ce) | Mar 09, 2021 |
| Samsung       | 300E5M/300E5L               | Notebook    | [bda4ee984f](https://linux-hardware.org/?probe=bda4ee984f) | Mar 05, 2021 |
| Dell          | Latitude E5500              | Notebook    | [a8e17b79ce](https://linux-hardware.org/?probe=a8e17b79ce) | Feb 26, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [45dfe3c2b1](https://linux-hardware.org/?probe=45dfe3c2b1) | Feb 24, 2021 |
| Lenovo        | ThinkPad L440 20ASS05K00    | Notebook    | [aecef5c789](https://linux-hardware.org/?probe=aecef5c789) | Jan 22, 2021 |
| Dell          | 0TP412                      | Desktop     | [f0e56aacff](https://linux-hardware.org/?probe=f0e56aacff) | Jan 05, 2021 |
| Lenovo        | ThinkPad L440 20ASS05K00    | Notebook    | [7a6a06bb55](https://linux-hardware.org/?probe=7a6a06bb55) | Jan 04, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [e1424f6de3](https://linux-hardware.org/?probe=e1424f6de3) | Dec 31, 2020 |
| Dell          | Precision M4600             | Notebook    | [71bb8e2e9a](https://linux-hardware.org/?probe=71bb8e2e9a) | Dec 28, 2020 |
| Lenovo        | ThinkPad L440 20ASS05K00    | Notebook    | [b330b2d38a](https://linux-hardware.org/?probe=b330b2d38a) | Nov 19, 2020 |
| NetGear       | ReadyDATA 5200              | Desktop     | [96607f4270](https://linux-hardware.org/?probe=96607f4270) | Nov 12, 2020 |
| MSI           | GL73 8RC                    | Notebook    | [44f82bfc01](https://linux-hardware.org/?probe=44f82bfc01) | Nov 09, 2020 |
| Lenovo        | ThinkPad L440 20ASS05K00    | Notebook    | [a4cb1ecf16](https://linux-hardware.org/?probe=a4cb1ecf16) | Nov 08, 2020 |
| HP            | 8523 A01                    | Mini pc     | [bab721d52e](https://linux-hardware.org/?probe=bab721d52e) | Oct 30, 2020 |
| ASRock        | Z390M-ITX/ac                | Desktop     | [06eb8afdbc](https://linux-hardware.org/?probe=06eb8afdbc) | Oct 19, 2020 |
| Samsung       | 300E5M/300E5L               | Notebook    | [270b65ced8](https://linux-hardware.org/?probe=270b65ced8) | Jul 24, 2020 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [d42d44dd82](https://linux-hardware.org/?probe=d42d44dd82) | Jul 23, 2020 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [888f105221](https://linux-hardware.org/?probe=888f105221) | Jul 23, 2020 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [2eb600bb96](https://linux-hardware.org/?probe=2eb600bb96) | Jul 10, 2020 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [232221bf45](https://linux-hardware.org/?probe=232221bf45) | Jul 10, 2020 |
| Notebook      | NL40_50CU                   | Notebook    | [941073da73](https://linux-hardware.org/?probe=941073da73) | Jun 27, 2020 |
| Lenovo        | V330-14ARR 81B1             | Notebook    | [5089cbcf84](https://linux-hardware.org/?probe=5089cbcf84) | Jun 24, 2020 |
| Lenovo        | V330-14ARR 81B1             | Notebook    | [cb63994f94](https://linux-hardware.org/?probe=cb63994f94) | Jun 22, 2020 |
| Notebook      | NL40_50CU                   | Notebook    | [9a1c09c6e1](https://linux-hardware.org/?probe=9a1c09c6e1) | Mar 28, 2020 |
| Notebook      | NL40_50CU                   | Notebook    | [bc5ed8dea4](https://linux-hardware.org/?probe=bc5ed8dea4) | Mar 24, 2020 |
| Notebook      | NL40_50CU                   | Notebook    | [ae7070b067](https://linux-hardware.org/?probe=ae7070b067) | Mar 21, 2020 |
| Notebook      | NL40_50CU                   | Notebook    | [320dada481](https://linux-hardware.org/?probe=320dada481) | Mar 20, 2020 |
| Toshiba       | Satellite P50-A-12Z         | Notebook    | [96927db16b](https://linux-hardware.org/?probe=96927db16b) | Mar 17, 2020 |
| Radxa         | ROCK Pi 4                   | Soc         | [abf599e14a](https://linux-hardware.org/?probe=abf599e14a) | Jan 27, 2020 |
| Huanan        | X79-8D VAA31                | Desktop     | [bbfc99d048](https://linux-hardware.org/?probe=bbfc99d048) | Jan 22, 2020 |
| Unknown       | Unknown                     | Soc         | [62347dfd8d](https://linux-hardware.org/?probe=62347dfd8d) | Jan 01, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [afe3135216](https://linux-hardware.org/?probe=afe3135216) | Dec 10, 2019 |
| ASUSTek       | P53E                        | Notebook    | [e9dcced0f7](https://linux-hardware.org/?probe=e9dcced0f7) | Oct 28, 2019 |
| Lenovo        | ThinkPad T400 6474BV7       | Notebook    | [825bdb9fd0](https://linux-hardware.org/?probe=825bdb9fd0) | Oct 28, 2019 |
| ASUSTek       | 1000H                       | Notebook    | [50da35c0d0](https://linux-hardware.org/?probe=50da35c0d0) | Oct 28, 2019 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [505df04abc](https://linux-hardware.org/?probe=505df04abc) | Oct 27, 2019 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [0b246f9623](https://linux-hardware.org/?probe=0b246f9623) | Oct 27, 2019 |
| Acer          | Aspire E1-572               | Notebook    | [0fe80f5758](https://linux-hardware.org/?probe=0fe80f5758) | Oct 23, 2019 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [21d76cde28](https://linux-hardware.org/?probe=21d76cde28) | Oct 22, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [ecca7bced0](https://linux-hardware.org/?probe=ecca7bced0) | Oct 22, 2019 |
| Lenovo        | IdeaPad P500 20210          | Notebook    | [3d09c5e38d](https://linux-hardware.org/?probe=3d09c5e38d) | Oct 22, 2019 |
| ASUSTek       | Z97-A                       | Desktop     | [482c60ec21](https://linux-hardware.org/?probe=482c60ec21) | Oct 21, 2019 |
| Acer          | Swift SF314-52              | Notebook    | [05f880ecec](https://linux-hardware.org/?probe=05f880ecec) | Oct 21, 2019 |
| Lenovo        | ThinkPad P70 20ERCTO1WW     | Notebook    | [0ceeb50e5e](https://linux-hardware.org/?probe=0ceeb50e5e) | Oct 21, 2019 |
| Gigabyte      | M61SME-S2                   | Desktop     | [10469f1659](https://linux-hardware.org/?probe=10469f1659) | Oct 21, 2019 |
| Lenovo        | ThinkPad T450s 20BW000EU... | Notebook    | [41ca8d1a20](https://linux-hardware.org/?probe=41ca8d1a20) | Oct 21, 2019 |
| HP            | 2B35                        | Desktop     | [45c5e4afbe](https://linux-hardware.org/?probe=45c5e4afbe) | Oct 21, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [c2fd6acb71](https://linux-hardware.org/?probe=c2fd6acb71) | Oct 21, 2019 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [70ea4f97bf](https://linux-hardware.org/?probe=70ea4f97bf) | Oct 21, 2019 |
| Dell          | Latitude E7270              | Notebook    | [859e021e2f](https://linux-hardware.org/?probe=859e021e2f) | Oct 20, 2019 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [4751f76aa2](https://linux-hardware.org/?probe=4751f76aa2) | Oct 20, 2019 |
| ASUSTek       | Maximus VII RANGER          | Desktop     | [71121ccd6f](https://linux-hardware.org/?probe=71121ccd6f) | Oct 20, 2019 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [e0c6729d5b](https://linux-hardware.org/?probe=e0c6729d5b) | Oct 20, 2019 |
| ASUSTek       | P5QLD PRO                   | Desktop     | [dabc1ee203](https://linux-hardware.org/?probe=dabc1ee203) | Oct 20, 2019 |
| Lenovo        | ThinkPad T470 20HDCTO1WW    | Notebook    | [0f9287651d](https://linux-hardware.org/?probe=0f9287651d) | Jul 24, 2019 |
| Lenovo        | ThinkPad T470 20HDCTO1WW    | Notebook    | [67672ef038](https://linux-hardware.org/?probe=67672ef038) | Jul 23, 2019 |
| Gigabyte      | X150M-PRO ECC-CF            | Desktop     | [39987c5d8e](https://linux-hardware.org/?probe=39987c5d8e) | Oct 10, 2018 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [63c120aa28](https://linux-hardware.org/?probe=63c120aa28) | Aug 19, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Slackware 15.0  | 86        | 55.48%  |
| Slackware 14.2  | 63        | 40.65%  |
| Slackware 14.2+ | 6         | 3.87%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Slackware | 153       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.19           | 19        | 11.52%  |
| 4.19.80           | 8         | 4.85%   |
| 5.19.17           | 6         | 3.64%   |
| 5.15.63           | 6         | 3.64%   |
| 5.10.28-Unraid    | 6         | 3.64%   |
| 5.15.27           | 4         | 2.42%   |
| 4.4.190           | 4         | 2.42%   |
| 5.19.17-Unraid    | 3         | 1.82%   |
| 5.15.38           | 3         | 1.82%   |
| 5.15.117          | 3         | 1.82%   |
| 4.4.240           | 3         | 1.82%   |
| 5.3.7             | 2         | 1.21%   |
| 5.17.2            | 2         | 1.21%   |
| 5.17.1            | 2         | 1.21%   |
| 5.16.13           | 2         | 1.21%   |
| 5.15.94           | 2         | 1.21%   |
| 5.15.80           | 2         | 1.21%   |
| 5.15.30-Unraid    | 2         | 1.21%   |
| 5.13.8            | 2         | 1.21%   |
| 5.10.3            | 2         | 1.21%   |
| 4.4.276           | 2         | 1.21%   |
| 6.1.44            | 1         | 0.61%   |
| 6.1.27            | 1         | 0.61%   |
| 6.1.20            | 1         | 0.61%   |
| 6.1.13            | 1         | 0.61%   |
| 6.1.12            | 1         | 0.61%   |
| 6.1.1             | 1         | 0.61%   |
| 5.7.0             | 1         | 0.61%   |
| 5.5.10            | 1         | 0.61%   |
| 5.4.77            | 1         | 0.61%   |
| 5.4.75            | 1         | 0.61%   |
| 5.4.62            | 1         | 0.61%   |
| 5.4.53-APRL       | 1         | 0.61%   |
| 5.4.50            | 1         | 0.61%   |
| 5.4.47            | 1         | 0.61%   |
| 5.4.43            | 1         | 0.61%   |
| 5.4.24toshiba-new | 1         | 0.61%   |
| 5.4.2             | 1         | 0.61%   |
| 5.4.139-jw        | 1         | 0.61%   |
| 5.4.13            | 1         | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.19  | 19        | 11.52%  |
| 5.19.17  | 9         | 5.45%   |
| 4.19.80  | 8         | 4.85%   |
| 5.15.63  | 6         | 3.64%   |
| 5.10.28  | 6         | 3.64%   |
| 4.4.190  | 5         | 3.03%   |
| 5.15.27  | 4         | 2.42%   |
| 5.15.38  | 3         | 1.82%   |
| 5.15.117 | 3         | 1.82%   |
| 4.4.240  | 3         | 1.82%   |
| 5.3.7    | 2         | 1.21%   |
| 5.17.2   | 2         | 1.21%   |
| 5.17.1   | 2         | 1.21%   |
| 5.16.13  | 2         | 1.21%   |
| 5.15.94  | 2         | 1.21%   |
| 5.15.80  | 2         | 1.21%   |
| 5.15.30  | 2         | 1.21%   |
| 5.14.15  | 2         | 1.21%   |
| 5.13.8   | 2         | 1.21%   |
| 5.10.3   | 2         | 1.21%   |
| 4.4.276  | 2         | 1.21%   |
| 6.1.44   | 1         | 0.61%   |
| 6.1.27   | 1         | 0.61%   |
| 6.1.20   | 1         | 0.61%   |
| 6.1.13   | 1         | 0.61%   |
| 6.1.12   | 1         | 0.61%   |
| 6.1.1    | 1         | 0.61%   |
| 5.7.0    | 1         | 0.61%   |
| 5.5.10   | 1         | 0.61%   |
| 5.4.77   | 1         | 0.61%   |
| 5.4.75   | 1         | 0.61%   |
| 5.4.62   | 1         | 0.61%   |
| 5.4.53   | 1         | 0.61%   |
| 5.4.50   | 1         | 0.61%   |
| 5.4.47   | 1         | 0.61%   |
| 5.4.43   | 1         | 0.61%   |
| 5.4.24   | 1         | 0.61%   |
| 5.4.2    | 1         | 0.61%   |
| 5.4.139  | 1         | 0.61%   |
| 5.4.13   | 1         | 0.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 52        | 31.9%   |
| 4.4     | 17        | 10.43%  |
| 5.10    | 15        | 9.2%    |
| 4.19    | 15        | 9.2%    |
| 5.4     | 13        | 7.98%   |
| 5.19    | 10        | 6.13%   |
| 5.14    | 7         | 4.29%   |
| 5.13    | 7         | 4.29%   |
| 5.17    | 6         | 3.68%   |
| 5.16    | 6         | 3.68%   |
| 6.1     | 5         | 3.07%   |
| 5.3     | 2         | 1.23%   |
| 4.9     | 2         | 1.23%   |
| 5.7     | 1         | 0.61%   |
| 5.5     | 1         | 0.61%   |
| 5.2     | 1         | 0.61%   |
| 5.12    | 1         | 0.61%   |
| 4.20    | 1         | 0.61%   |
| 4.16    | 1         | 0.61%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 150       | 98.04%  |
| aarch64 | 2         | 1.31%   |
| i686    | 1         | 0.65%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 49        | 31.41%  |
| XFCE          | 47        | 30.13%  |
| KDE5          | 40        | 25.64%  |
| KDE           | 5         | 3.21%   |
| GNOME         | 3         | 1.92%   |
| xwmconfig     | 2         | 1.28%   |
| MATE          | 2         | 1.28%   |
| fvwm          | 2         | 1.28%   |
| X-Generic     | 1         | 0.64%   |
| X-Cinnamon    | 1         | 0.64%   |
| LXQt          | 1         | 0.64%   |
| Enlightenment | 1         | 0.64%   |
| awesome       | 1         | 0.64%   |
| 2bwm          | 1         | 0.64%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 102       | 64.56%  |
| Tty     | 37        | 23.42%  |
| Unknown | 12        | 7.59%   |
| Wayland | 7         | 4.43%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 62        | 39.24%  |
| SDDM    | 51        | 32.28%  |
| XDM     | 36        | 22.78%  |
| LightDM | 5         | 3.16%   |
| SLiM    | 3         | 1.9%    |
| GDM     | 1         | 0.63%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 79        | 51.63%  |
| Unknown     | 43        | 28.1%   |
| it_IT       | 5         | 3.27%   |
| ru_RU       | 4         | 2.61%   |
| pt_BR       | 4         | 2.61%   |
| fr_FR       | 3         | 1.96%   |
| en_GB       | 3         | 1.96%   |
| de_DE       | 3         | 1.96%   |
| us          | 1         | 0.65%   |
| sr_RS@latin | 1         | 0.65%   |
| pt_PT       | 1         | 0.65%   |
| pl_PL       | 1         | 0.65%   |
| es_ES.UTF8  | 1         | 0.65%   |
| es_ES       | 1         | 0.65%   |
| en_US.ASCII | 1         | 0.65%   |
| en_AU       | 1         | 0.65%   |
| C           | 1         | 0.65%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 80        | 51.95%  |
| EFI  | 74        | 48.05%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 112       | 72.73%  |
| Btrfs    | 17        | 11.04%  |
| Xfs      | 7         | 4.55%   |
| Overlay  | 7         | 4.55%   |
| Rootfs   | 4         | 2.6%    |
| Zfs      | 1         | 0.65%   |
| Tmpfs    | 1         | 0.65%   |
| Reiserfs | 1         | 0.65%   |
| Jfs      | 1         | 0.65%   |
| F2fs     | 1         | 0.65%   |
| Ext3     | 1         | 0.65%   |
| Ext2     | 1         | 0.65%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 104       | 66.67%  |
| MBR     | 37        | 23.72%  |
| Unknown | 15        | 9.62%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 103       | 66.03%  |
| Yes       | 53        | 33.97%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 104       | 67.97%  |
| Yes       | 49        | 32.03%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 26        | 16.99%  |
| Hewlett-Packard     | 25        | 16.34%  |
| Lenovo              | 19        | 12.42%  |
| Dell                | 14        | 9.15%   |
| MSI                 | 13        | 8.5%    |
| ASRock              | 11        | 7.19%   |
| Gigabyte Technology | 7         | 4.58%   |
| Acer                | 6         | 3.92%   |
| Toshiba             | 3         | 1.96%   |
| Fujitsu             | 3         | 1.96%   |
| Notebook            | 2         | 1.31%   |
| Dynabook            | 2         | 1.31%   |
| Apple               | 2         | 1.31%   |
| Unknown             | 2         | 1.31%   |
| Valve               | 1         | 0.65%   |
| TYAN Computer       | 1         | 0.65%   |
| System76            | 1         | 0.65%   |
| Supermicro          | 1         | 0.65%   |
| Sony                | 1         | 0.65%   |
| Shuttle             | 1         | 0.65%   |
| Samsung Electronics | 1         | 0.65%   |
| Radxa               | 1         | 0.65%   |
| NetGear             | 1         | 0.65%   |
| Microsoft           | 1         | 0.65%   |
| Intel               | 1         | 0.65%   |
| Huanan              | 1         | 0.65%   |
| HPE                 | 1         | 0.65%   |
| HEDYCOMPUTER        | 1         | 0.65%   |
| Framework           | 1         | 0.65%   |
| Foxconn             | 1         | 0.65%   |
| Biostar             | 1         | 0.65%   |
| AMI                 | 1         | 0.65%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| ASUS All Series                          | 4         | 2.61%   |
| ASUS VivoBook_ASUSLaptop K6500ZE_K6500ZE | 2         | 1.31%   |
| ASRock N68-S3 FX                         | 2         | 1.31%   |
| Unknown                                  | 2         | 1.31%   |
| Valve Jupiter                            | 1         | 0.65%   |
| TYAN S7012                               | 1         | 0.65%   |
| Toshiba Satellite P50-A-12Z              | 1         | 0.65%   |
| Toshiba Satellite C660                   | 1         | 0.65%   |
| Toshiba PORTEGE Z30-A                    | 1         | 0.65%   |
| System76 Oryx Pro                        | 1         | 0.65%   |
| Supermicro X9DA7/E                       | 1         | 0.65%   |
| Sony SVE1713A1EW                         | 1         | 0.65%   |
| Shuttle NC03U                            | 1         | 0.65%   |
| Samsung 300E5M/300E5L                    | 1         | 0.65%   |
| Radxa ROCK Pi 4                          | 1         | 0.65%   |
| Notebook X170KM-G                        | 1         | 0.65%   |
| Notebook NL40_50CU                       | 1         | 0.65%   |
| NetGear ReadyDATA 5200                   | 1         | 0.65%   |
| MSI MS-7C52                              | 1         | 0.65%   |
| MSI MS-7C02                              | 1         | 0.65%   |
| MSI MS-7996                              | 1         | 0.65%   |
| MSI MS-7885                              | 1         | 0.65%   |
| MSI MS-7788                              | 1         | 0.65%   |
| MSI MS-7693                              | 1         | 0.65%   |
| MSI MS-7529                              | 1         | 0.65%   |
| MSI MS-7365                              | 1         | 0.65%   |
| MSI Modern 14 B11MO                      | 1         | 0.65%   |
| MSI Modern 14 B10MW                      | 1         | 0.65%   |
| MSI GP76 Leopard 11UG                    | 1         | 0.65%   |
| MSI GL73 8RC                             | 1         | 0.65%   |
| MSI GE76 Raider 11UE                     | 1         | 0.65%   |
| Microsoft Surface Go 3                   | 1         | 0.65%   |
| Lenovo V330-14ARR 81B1                   | 1         | 0.65%   |
| Lenovo ThinkPad X230 2325P38             | 1         | 0.65%   |
| Lenovo ThinkPad X140e 20BMS03E00         | 1         | 0.65%   |
| Lenovo ThinkPad X1 Carbon 7th 20R10015US | 1         | 0.65%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS04300 | 1         | 0.65%   |
| Lenovo ThinkPad T61 765912G              | 1         | 0.65%   |
| Lenovo ThinkPad T470p 20J60018MS         | 1         | 0.65%   |
| Lenovo ThinkPad T470 20JNS01R01          | 1         | 0.65%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 14        | 9.15%   |
| ASUS PRIME        | 6         | 3.92%   |
| Dell Precision    | 5         | 3.27%   |
| HP Pavilion       | 4         | 2.61%   |
| HP Laptop         | 4         | 2.61%   |
| ASUS ROG          | 4         | 2.61%   |
| ASUS All          | 4         | 2.61%   |
| Lenovo IdeaPad    | 3         | 1.96%   |
| HP EliteBook      | 3         | 1.96%   |
| Dell Latitude     | 3         | 1.96%   |
| ASUS VivoBook     | 3         | 1.96%   |
| Toshiba Satellite | 2         | 1.31%   |
| MSI Modern        | 2         | 1.31%   |
| HP OMEN           | 2         | 1.31%   |
| Fujitsu LIFEBOOK  | 2         | 1.31%   |
| Dell PowerEdge    | 2         | 1.31%   |
| Dell OptiPlex     | 2         | 1.31%   |
| ASUS TUF          | 2         | 1.31%   |
| ASRock N68-S3     | 2         | 1.31%   |
| Acer Swift        | 2         | 1.31%   |
| Acer Aspire       | 2         | 1.31%   |
| Unknown           | 2         | 1.31%   |
| Valve Jupiter     | 1         | 0.65%   |
| TYAN S7012        | 1         | 0.65%   |
| Toshiba PORTEGE   | 1         | 0.65%   |
| System76 Oryx     | 1         | 0.65%   |
| Supermicro X9DA7  | 1         | 0.65%   |
| Sony SVE1713A1EW  | 1         | 0.65%   |
| Shuttle NC03U     | 1         | 0.65%   |
| Samsung 300E5M    | 1         | 0.65%   |
| Radxa ROCK        | 1         | 0.65%   |
| Notebook X170KM-G | 1         | 0.65%   |
| Notebook NL40     | 1         | 0.65%   |
| NetGear ReadyDATA | 1         | 0.65%   |
| MSI MS-7C52       | 1         | 0.65%   |
| MSI MS-7C02       | 1         | 0.65%   |
| MSI MS-7996       | 1         | 0.65%   |
| MSI MS-7885       | 1         | 0.65%   |
| MSI MS-7788       | 1         | 0.65%   |
| MSI MS-7693       | 1         | 0.65%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 16        | 10.46%  |
| 2019    | 16        | 10.46%  |
| 2017    | 14        | 9.15%   |
| 2015    | 13        | 8.5%    |
| 2012    | 13        | 8.5%    |
| 2021    | 12        | 7.84%   |
| 2018    | 11        | 7.19%   |
| 2014    | 9         | 5.88%   |
| 2011    | 9         | 5.88%   |
| 2022    | 7         | 4.58%   |
| 2016    | 7         | 4.58%   |
| 2008    | 7         | 4.58%   |
| 2007    | 5         | 3.27%   |
| 2013    | 4         | 2.61%   |
| 2010    | 4         | 2.61%   |
| 2009    | 4         | 2.61%   |
| Unknown | 2         | 1.31%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 71        | 46.41%  |
| Notebook       | 71        | 46.41%  |
| Mini pc        | 3         | 1.96%   |
| Server         | 3         | 1.96%   |
| System on chip | 2         | 1.31%   |
| All in one     | 2         | 1.31%   |
| Tablet         | 1         | 0.65%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 153       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 150       | 98.04%  |
| Yes  | 3         | 1.96%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 34        | 22.08%  |
| 8.01-16.0   | 29        | 18.83%  |
| 4.01-8.0    | 27        | 17.53%  |
| 3.01-4.0    | 24        | 15.58%  |
| 32.01-64.0  | 17        | 11.04%  |
| 64.01-256.0 | 10        | 6.49%   |
| 24.01-32.0  | 7         | 4.55%   |
| 1.01-2.0    | 5         | 3.25%   |
| 0.51-1.0    | 1         | 0.65%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 44        | 27.33%  |
| 2.01-3.0    | 38        | 23.6%   |
| 4.01-8.0    | 29        | 18.01%  |
| 3.01-4.0    | 17        | 10.56%  |
| 0.51-1.0    | 13        | 8.07%   |
| 8.01-16.0   | 6         | 3.73%   |
| 0.01-0.5    | 6         | 3.73%   |
| 16.01-24.0  | 4         | 2.48%   |
| 24.01-32.0  | 2         | 1.24%   |
| 32.01-64.0  | 1         | 0.62%   |
| 64.01-256.0 | 1         | 0.62%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 75        | 47.47%  |
| 2      | 36        | 22.78%  |
| 3      | 18        | 11.39%  |
| 4      | 10        | 6.33%   |
| 6      | 6         | 3.8%    |
| 5      | 5         | 3.16%   |
| 0      | 3         | 1.9%    |
| 13     | 1         | 0.63%   |
| 11     | 1         | 0.63%   |
| 9      | 1         | 0.63%   |
| 8      | 1         | 0.63%   |
| 7      | 1         | 0.63%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 94        | 61.04%  |
| Yes       | 60        | 38.96%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 140       | 91.5%   |
| No        | 13        | 8.5%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 104       | 67.53%  |
| No        | 50        | 32.47%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 93        | 60.78%  |
| No        | 60        | 39.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 34        | 22.22%  |
| UK           | 13        | 8.5%    |
| Germany      | 10        | 6.54%   |
| Brazil       | 10        | 6.54%   |
| Italy        | 9         | 5.88%   |
| Russia       | 7         | 4.58%   |
| Portugal     | 7         | 4.58%   |
| Kazakhstan   | 6         | 3.92%   |
| Japan        | 6         | 3.92%   |
| India        | 6         | 3.92%   |
| Canada       | 6         | 3.92%   |
| France       | 5         | 3.27%   |
| Sweden       | 4         | 2.61%   |
| Spain        | 4         | 2.61%   |
| South Africa | 3         | 1.96%   |
| Hong Kong    | 3         | 1.96%   |
| Greece       | 3         | 1.96%   |
| Serbia       | 2         | 1.31%   |
| Poland       | 2         | 1.31%   |
| Chile        | 2         | 1.31%   |
| Australia    | 2         | 1.31%   |
| Switzerland  | 1         | 0.65%   |
| Romania      | 1         | 0.65%   |
| Philippines  | 1         | 0.65%   |
| Netherlands  | 1         | 0.65%   |
| Mexico       | 1         | 0.65%   |
| Finland      | 1         | 0.65%   |
| China        | 1         | 0.65%   |
| Bulgaria     | 1         | 0.65%   |
| Argentina    | 1         | 0.65%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Lisbon                 | 6         | 3.8%    |
| Ust-Kamenogorsk        | 4         | 2.53%   |
| Yekaterinburg          | 3         | 1.9%    |
| Tsukuba                | 3         | 1.9%    |
| Paris                  | 3         | 1.9%    |
| Chania                 | 3         | 1.9%    |
| Warsaw                 | 2         | 1.27%   |
| Tendo                  | 2         | 1.27%   |
| Sun Prairie            | 2         | 1.27%   |
| Springfield            | 2         | 1.27%   |
| Rome                   | 2         | 1.27%   |
| New Delhi              | 2         | 1.27%   |
| Moscow                 | 2         | 1.27%   |
| Milan                  | 2         | 1.27%   |
| McKinney               | 2         | 1.27%   |
| Karaganda              | 2         | 1.27%   |
| Greater Noida          | 2         | 1.27%   |
| Frignano               | 2         | 1.27%   |
| Fayetteville           | 2         | 1.27%   |
| Carrollton             | 2         | 1.27%   |
| Cape Town              | 2         | 1.27%   |
| Belgrade               | 2         | 1.27%   |
| Barry                  | 2         | 1.27%   |
| Barrie                 | 2         | 1.27%   |
| Worpswede              | 1         | 0.63%   |
| Wokingham              | 1         | 0.63%   |
| Winter Springs         | 1         | 0.63%   |
| Winnipeg               | 1         | 0.63%   |
| Weilheim               | 1         | 0.63%   |
| Voskresensk            | 1         | 0.63%   |
| Visconde do Rio Branco | 1         | 0.63%   |
| Toronto                | 1         | 0.63%   |
| Tiffin                 | 1         | 0.63%   |
| Tatuí                 | 1         | 0.63%   |
| Stockholm              | 1         | 0.63%   |
| St Petersburg          | 1         | 0.63%   |
| St Louis               | 1         | 0.63%   |
| Southend-on-Sea        | 1         | 0.63%   |
| Skövde                | 1         | 0.63%   |
| Shrewsbury             | 1         | 0.63%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 46        | 90     | 18.7%   |
| Samsung Electronics | 41        | 60     | 16.67%  |
| Seagate             | 36        | 66     | 14.63%  |
| Toshiba             | 19        | 36     | 7.72%   |
| Kingston            | 14        | 17     | 5.69%   |
| Crucial             | 10        | 12     | 4.07%   |
| Intel               | 8         | 9      | 3.25%   |
| Hitachi             | 8         | 11     | 3.25%   |
| HGST                | 6         | 6      | 2.44%   |
| Unknown             | 5         | 6      | 2.03%   |
| SK hynix            | 5         | 5      | 2.03%   |
| SanDisk             | 5         | 6      | 2.03%   |
| A-DATA Technology   | 4         | 4      | 1.63%   |
| Transcend           | 3         | 3      | 1.22%   |
| Micron Technology   | 3         | 3      | 1.22%   |
| KIOXIA              | 3         | 3      | 1.22%   |
| Hewlett-Packard     | 3         | 4      | 1.22%   |
| Gigabyte Technology | 3         | 3      | 1.22%   |
| Patriot             | 2         | 3      | 0.81%   |
| Maxtor              | 2         | 2      | 0.81%   |
| China               | 2         | 3      | 0.81%   |
| Apple               | 2         | 3      | 0.81%   |
| ZHITAI              | 1         | 2      | 0.41%   |
| TO Exter            | 1         | 1      | 0.41%   |
| Team                | 1         | 1      | 0.41%   |
| Silicon Motion      | 1         | 1      | 0.41%   |
| PNY                 | 1         | 1      | 0.41%   |
| Plextor             | 1         | 1      | 0.41%   |
| Phison Electronics  | 1         | 1      | 0.41%   |
| Netac               | 1         | 1      | 0.41%   |
| Lexar               | 1         | 1      | 0.41%   |
| JMicron Technology  | 1         | 1      | 0.41%   |
| Intenso             | 1         | 1      | 0.41%   |
| GOODRAM             | 1         | 1      | 0.41%   |
| Fujitsu             | 1         | 1      | 0.41%   |
| External            | 1         | 1      | 0.41%   |
| DUEX                | 1         | 1      | 0.41%   |
| Dogfish             | 1         | 1      | 0.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD  | 6         | 2.01%   |
| WDC WD20EFRX-68EUZN0 2TB         | 3         | 1.01%   |
| WDC WD1003FZEX-00MK2A0 1TB       | 3         | 1.01%   |
| Seagate ST2000DM008-2FR102 2TB   | 3         | 1.01%   |
| Samsung SSD 970 EVO 250GB        | 3         | 1.01%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 2         | 0.67%   |
| WDC WD30EZRX-00SPEB0 3TB         | 2         | 0.67%   |
| WDC WD10SPZX-60Z10T0 1TB         | 2         | 0.67%   |
| WDC WD10EZEX-08WN4A0 1TB         | 2         | 0.67%   |
| WDC WD10EZEX-00RKKA0 1TB         | 2         | 0.67%   |
| Toshiba MQ04ABF100 1TB           | 2         | 0.67%   |
| Toshiba MQ01ABD100 1TB           | 2         | 0.67%   |
| Toshiba HDWD110 1TB              | 2         | 0.67%   |
| Seagate ST500DM002-1BD142 500GB  | 2         | 0.67%   |
| Seagate ST4000VN008-2DR166 4TB   | 2         | 0.67%   |
| Seagate ST4000DM004-2CV104 4TB   | 2         | 0.67%   |
| Seagate ST31000524AS 1TB         | 2         | 0.67%   |
| Seagate ST2000DM001-1CH164 2TB   | 2         | 0.67%   |
| Seagate ST2000DL003-9VT166 2TB   | 2         | 0.67%   |
| Seagate ST1000DM010-2EP102 1TB   | 2         | 0.67%   |
| Seagate ST1000DM003-1SB102 1TB   | 2         | 0.67%   |
| Seagate ST1000DM003-1ER162 1TB   | 2         | 0.67%   |
| Seagate Expansion Desk 8TB       | 2         | 0.67%   |
| Samsung SSD 970 EVO Plus 1TB     | 2         | 0.67%   |
| Samsung SSD 860 QVO 2TB          | 2         | 0.67%   |
| Kingston SA400S37120G 120GB SSD  | 2         | 0.67%   |
| Intel SSD 660P Series 1024GB     | 2         | 0.67%   |
| HGST HTS725050A7E630 500GB       | 2         | 0.67%   |
| Crucial CT500MX500SSD1 500GB     | 2         | 0.67%   |
| ZHITAI SC001 Active 1TB SSD      | 1         | 0.34%   |
| ZHITAI PC005 Active 512GB        | 1         | 0.34%   |
| WDC WDS500G2B0B-00YS70 500GB SSD | 1         | 0.34%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1         | 0.34%   |
| WDC WDS480G2G0A-00JH30 480GB SSD | 1         | 0.34%   |
| WDC WDS100T2B0C-00PXH0 1TB       | 1         | 0.34%   |
| WDC WDS100T2B0B-00YS70 1TB SSD   | 1         | 0.34%   |
| WDC WD7500BPVT-24HXZT3 752GB     | 1         | 0.34%   |
| WDC WD5003ABYX-18WERA0 500GB     | 1         | 0.34%   |
| WDC WD5000LPCX-60VHAT1 500GB     | 1         | 0.34%   |
| WDC WD5000BPVT-2 500GB           | 1         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 39        | 79     | 33.33%  |
| Seagate             | 36        | 62     | 30.77%  |
| Toshiba             | 18        | 31     | 15.38%  |
| Hitachi             | 8         | 11     | 6.84%   |
| HGST                | 6         | 6      | 5.13%   |
| Samsung Electronics | 4         | 4      | 3.42%   |
| Maxtor              | 2         | 2      | 1.71%   |
| JMicron Technology  | 1         | 1      | 0.85%   |
| Hewlett-Packard     | 1         | 1      | 0.85%   |
| Fujitsu             | 1         | 1      | 0.85%   |
| External            | 1         | 1      | 0.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 29     | 24.68%  |
| Kingston            | 13        | 16     | 16.88%  |
| Crucial             | 8         | 10     | 10.39%  |
| WDC                 | 5         | 7      | 6.49%   |
| SanDisk             | 4         | 4      | 5.19%   |
| Transcend           | 2         | 2      | 2.6%    |
| Patriot             | 2         | 3      | 2.6%    |
| Intel               | 2         | 3      | 2.6%    |
| China               | 2         | 3      | 2.6%    |
| Apple               | 2         | 3      | 2.6%    |
| A-DATA Technology   | 2         | 2      | 2.6%    |
| ZHITAI              | 1         | 1      | 1.3%    |
| Toshiba             | 1         | 3      | 1.3%    |
| TO Exter            | 1         | 1      | 1.3%    |
| Team                | 1         | 1      | 1.3%    |
| SK hynix            | 1         | 1      | 1.3%    |
| PNY                 | 1         | 1      | 1.3%    |
| Plextor             | 1         | 1      | 1.3%    |
| Netac               | 1         | 1      | 1.3%    |
| Micron Technology   | 1         | 1      | 1.3%    |
| Lexar               | 1         | 1      | 1.3%    |
| Intenso             | 1         | 1      | 1.3%    |
| Hewlett-Packard     | 1         | 1      | 1.3%    |
| GOODRAM             | 1         | 1      | 1.3%    |
| Gigabyte Technology | 1         | 1      | 1.3%    |
| DUEX                | 1         | 1      | 1.3%    |
| Dogfish             | 1         | 1      | 1.3%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 84        | 199    | 39.44%  |
| SSD     | 71        | 100    | 33.33%  |
| NVMe    | 52        | 63     | 24.41%  |
| MMC     | 5         | 6      | 2.35%   |
| Unknown | 1         | 4      | 0.47%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 115       | 288    | 63.89%  |
| NVMe | 52        | 63     | 28.89%  |
| SAS  | 8         | 15     | 4.44%   |
| MMC  | 5         | 6      | 2.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 86        | 125    | 47.51%  |
| 0.51-1.0   | 48        | 90     | 26.52%  |
| 1.01-2.0   | 19        | 26     | 10.5%   |
| 3.01-4.0   | 12        | 26     | 6.63%   |
| 2.01-3.0   | 8         | 19     | 4.42%   |
| 4.01-10.0  | 6         | 8      | 3.31%   |
| 10.01-20.0 | 2         | 5      | 1.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 37        | 23.57%  |
| 501-1000       | 33        | 21.02%  |
| 251-500        | 25        | 15.92%  |
| Unknown        | 18        | 11.46%  |
| 1001-2000      | 15        | 9.55%   |
| 1-20           | 9         | 5.73%   |
| 2001-3000      | 8         | 5.1%    |
| More than 3000 | 5         | 3.18%   |
| 51-100         | 4         | 2.55%   |
| 21-50          | 3         | 1.91%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 31        | 19.38%  |
| 1-20           | 27        | 16.88%  |
| 21-50          | 22        | 13.75%  |
| 501-1000       | 19        | 11.88%  |
| Unknown        | 18        | 11.25%  |
| 51-100         | 17        | 10.63%  |
| 251-500        | 16        | 10%     |
| 1001-2000      | 7         | 4.38%   |
| More than 3000 | 3         | 1.88%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1         | 1      | 2.38%   |
| WDC WD5003ABYX-18WERA0 500GB          | 1         | 2      | 2.38%   |
| WDC WD5000LPCX-60VHAT1 500GB          | 1         | 1      | 2.38%   |
| WDC WD5000BPKX-60HPJT0 500GB          | 1         | 1      | 2.38%   |
| WDC WD5000AAKX-22ERMA0 500GB          | 1         | 1      | 2.38%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 1         | 1      | 2.38%   |
| WDC WD5000AAKS-00A7B2 500GB           | 1         | 1      | 2.38%   |
| WDC WD40EFRX-68WT0N0 4TB              | 1         | 2      | 2.38%   |
| WDC WD3200AAJS-65B4A0 320GB           | 1         | 1      | 2.38%   |
| WDC WD30EZRX-00MMMB0 3TB              | 1         | 1      | 2.38%   |
| WDC WD30EZRX-00M                      | 1         | 1      | 2.38%   |
| WDC WD30EFRX-68AX9N0 3TB              | 1         | 4      | 2.38%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1         | 2      | 2.38%   |
| WDC WD20EARX-00PASB0 2TB              | 1         | 1      | 2.38%   |
| WDC WD10JPLX-00MBPT0 1TB              | 1         | 1      | 2.38%   |
| WDC WD10EZEX-00RKKA0 1TB              | 1         | 1      | 2.38%   |
| WDC WD10EALS-00Z8A0 1TB               | 1         | 2      | 2.38%   |
| WDC WD1003FZEX-00MK2A0 1TB            | 1         | 2      | 2.38%   |
| Toshiba MK2565GSXN 250GB              | 1         | 1      | 2.38%   |
| Seagate ST380011A 80GB                | 1         | 2      | 2.38%   |
| Seagate ST3500630AS 500GB             | 1         | 1      | 2.38%   |
| Seagate ST3500418AS 500GB             | 1         | 1      | 2.38%   |
| Seagate ST3500410AS 500GB             | 1         | 1      | 2.38%   |
| Seagate ST31000524AS 1TB              | 1         | 1      | 2.38%   |
| Seagate ST3000VX006-1HH166 3TB        | 1         | 1      | 2.38%   |
| Seagate ST2000DL003-9VT166 2TB        | 1         | 1      | 2.38%   |
| Seagate ST1000VM002-1SD102 1TB        | 1         | 1      | 2.38%   |
| Seagate ST1000NM0011 1TB              | 1         | 2      | 2.38%   |
| Seagate ST1000DM003-1ER162 1TB        | 1         | 2      | 2.38%   |
| SanDisk SDSA6MM-016G-1006 16GB SSD    | 1         | 1      | 2.38%   |
| Samsung Electronics SSD 970 EVO 500GB | 1         | 1      | 2.38%   |
| Samsung Electronics SSD 870 EVO 1TB   | 1         | 1      | 2.38%   |
| Plextor PX-128M6S 128GB SSD           | 1         | 1      | 2.38%   |
| Maxtor 4G120J6 128GB                  | 1         | 1      | 2.38%   |
| Intel SSDSA2M080G2GC 80GB             | 1         | 1      | 2.38%   |
| Hitachi HUA723030ALA640 3TB           | 1         | 1      | 2.38%   |
| Hitachi HDS721050CLA660 500GB         | 1         | 1      | 2.38%   |
| Hitachi HDS721016CLA382 160GB         | 1         | 1      | 2.38%   |
| HGST HTS725050A7E630 500GB            | 1         | 1      | 2.38%   |
| HGST HTS545050A7E380 500GB            | 1         | 1      | 2.38%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 15        | 26     | 39.47%  |
| Seagate             | 9         | 13     | 23.68%  |
| Hitachi             | 3         | 3      | 7.89%   |
| HGST                | 3         | 3      | 7.89%   |
| Samsung Electronics | 2         | 2      | 5.26%   |
| Toshiba             | 1         | 1      | 2.63%   |
| SanDisk             | 1         | 1      | 2.63%   |
| Plextor             | 1         | 1      | 2.63%   |
| Maxtor              | 1         | 1      | 2.63%   |
| Intel               | 1         | 1      | 2.63%   |
| DUEX                | 1         | 1      | 2.63%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 14        | 25     | 45.16%  |
| Seagate | 9         | 13     | 29.03%  |
| Hitachi | 3         | 3      | 9.68%   |
| HGST    | 3         | 3      | 9.68%   |
| Toshiba | 1         | 1      | 3.23%   |
| Maxtor  | 1         | 1      | 3.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 28        | 46     | 80%     |
| SSD  | 6         | 6      | 17.14%  |
| NVMe | 1         | 1      | 2.86%   |

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
| Works    | 121       | 254    | 65.41%  |
| Malfunc  | 35        | 53     | 18.92%  |
| Detected | 29        | 65     | 15.68%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 92        | 44.66%  |
| AMD                          | 38        | 18.45%  |
| Samsung Electronics          | 23        | 11.17%  |
| Marvell Technology Group     | 6         | 2.91%   |
| ASMedia Technology           | 6         | 2.91%   |
| SanDisk                      | 5         | 2.43%   |
| Nvidia                       | 5         | 2.43%   |
| SK hynix                     | 4         | 1.94%   |
| KIOXIA                       | 3         | 1.46%   |
| JMicron Technology           | 3         | 1.46%   |
| Broadcom / LSI               | 3         | 1.46%   |
| Realtek Semiconductor        | 2         | 0.97%   |
| Phison Electronics           | 2         | 0.97%   |
| Micron/Crucial Technology    | 2         | 0.97%   |
| Micron Technology            | 2         | 0.97%   |
| LSI Logic / Symbios Logic    | 2         | 0.97%   |
| Yangtze Memory Technologies  | 1         | 0.49%   |
| Toshiba America Info Systems | 1         | 0.49%   |
| Silicon Motion               | 1         | 0.49%   |
| Silicon Image                | 1         | 0.49%   |
| Kingston Technology Company  | 1         | 0.49%   |
| Biwin Storage Technology     | 1         | 0.49%   |
| Adaptec                      | 1         | 0.49%   |
| 3ware                        | 1         | 0.49%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 27        | 10.8%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 12        | 4.8%    |
| AMD 400 Series Chipset SATA Controller                                           | 10        | 4%      |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 7         | 2.8%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 2.4%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 6         | 2.4%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 5         | 2%      |
| ASMedia ASM1062 Serial ATA Controller                                            | 5         | 2%      |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 4         | 1.6%    |
| Nvidia MCP61 SATA Controller                                                     | 4         | 1.6%    |
| Nvidia MCP61 IDE                                                                 | 4         | 1.6%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 1.6%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 1.6%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 1.6%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 4         | 1.6%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 1.2%    |
| Samsung NVMe SSD Controller 980                                                  | 3         | 1.2%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 3         | 1.2%    |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 1.2%    |
| Intel SSD 660P Series                                                            | 3         | 1.2%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 1.2%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 3         | 1.2%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 3         | 1.2%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 3         | 1.2%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 1.2%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 1.2%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.2%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 2         | 0.8%    |
| SK hynix BC511 NVMe SSD                                                          | 2         | 0.8%    |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 0.8%    |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                | 2         | 0.8%    |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 2         | 0.8%    |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 2         | 0.8%    |
| JMicron JMB58x AHCI SATA controller                                              | 2         | 0.8%    |
| Intel SSD 600P Series                                                            | 2         | 0.8%    |
| Intel SATA Controller [RAID mode]                                                | 2         | 0.8%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2         | 0.8%    |
| Intel C602 chipset 4-Port SATA Storage Control Unit                              | 2         | 0.8%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 2         | 0.8%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 2         | 0.8%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 109       | 52.66%  |
| NVMe | 52        | 25.12%  |
| IDE  | 23        | 11.11%  |
| RAID | 16        | 7.73%   |
| SAS  | 4         | 1.93%   |
| SCSI | 3         | 1.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 107       | 69.93%  |
| AMD    | 44        | 28.76%  |
| ARM    | 2         | 1.31%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 4         | 2.6%    |
| AMD Ryzen 5 3600 6-Core Processor             | 4         | 2.6%    |
| Intel 12th Gen Core i7-12700H                 | 3         | 1.95%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz            | 2         | 1.3%    |
| Intel Core i7-5820K CPU @ 3.30GHz             | 2         | 1.3%    |
| Intel Core i7-4790K CPU @ 4.00GHz             | 2         | 1.3%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.3%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 1.3%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.3%    |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1.3%    |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 2         | 1.3%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 2         | 1.3%    |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 1.3%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.3%    |
| ARM Processor                                 | 2         | 1.3%    |
| AMD Ryzen 9 5950X 16-Core Processor           | 2         | 1.3%    |
| AMD Ryzen 7 3800X 8-Core Processor            | 2         | 1.3%    |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 2         | 1.3%    |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 1.3%    |
| AMD FX-8350 Eight-Core Processor              | 2         | 1.3%    |
| AMD Athlon II X2 250 Processor                | 2         | 1.3%    |
| Intel Xeon CPU X5680 @ 3.33GHz                | 1         | 0.65%   |
| Intel Xeon CPU X5355 @ 2.66GHz                | 1         | 0.65%   |
| Intel Xeon CPU X3450 @ 2.67GHz                | 1         | 0.65%   |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz           | 1         | 0.65%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz           | 1         | 0.65%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz           | 1         | 0.65%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz            | 1         | 0.65%   |
| Intel Xeon CPU E5-2407 0 @ 2.20GHz            | 1         | 0.65%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz            | 1         | 0.65%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz           | 1         | 0.65%   |
| Intel Xeon CPU 5160 @ 3.00GHz                 | 1         | 0.65%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 0.65%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz        | 1         | 0.65%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz        | 1         | 0.65%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 1         | 0.65%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.65%   |
| Intel Pentium CPU GOLD 6500Y @ 1.10GHz        | 1         | 0.65%   |
| Intel Pentium CPU G640 @ 2.80GHz              | 1         | 0.65%   |
| Intel Pentium CPU G4560 @ 3.50GHz             | 1         | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 26        | 16.88%  |
| Intel Core i7        | 23        | 14.94%  |
| Other                | 16        | 10.39%  |
| Intel Xeon           | 13        | 8.44%   |
| AMD Ryzen 5          | 13        | 8.44%   |
| Intel Pentium        | 7         | 4.55%   |
| Intel Core i3        | 7         | 4.55%   |
| Intel Core 2 Duo     | 6         | 3.9%    |
| AMD Ryzen 9          | 6         | 3.9%    |
| AMD Ryzen 7          | 6         | 3.9%    |
| AMD FX               | 5         | 3.25%   |
| Intel Celeron        | 4         | 2.6%    |
| Intel Core 2 Quad    | 2         | 1.3%    |
| Intel Atom           | 2         | 1.3%    |
| AMD Athlon II X2     | 2         | 1.3%    |
| Intel Pentium Silver | 1         | 0.65%   |
| Intel Pentium Gold   | 1         | 0.65%   |
| Intel Pentium Dual   | 1         | 0.65%   |
| Intel Core M         | 1         | 0.65%   |
| Intel Core 2         | 1         | 0.65%   |
| AMD Ryzen Embedded   | 1         | 0.65%   |
| AMD Ryzen 7 PRO      | 1         | 0.65%   |
| AMD Ryzen 3          | 1         | 0.65%   |
| AMD GX               | 1         | 0.65%   |
| AMD EPYC             | 1         | 0.65%   |
| AMD E1               | 1         | 0.65%   |
| AMD Athlon 64 X2     | 1         | 0.65%   |
| AMD Athlon           | 1         | 0.65%   |
| AMD A8               | 1         | 0.65%   |
| AMD A4               | 1         | 0.65%   |
| AMD A10              | 1         | 0.65%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 51        | 33.12%  |
| 4      | 50        | 32.47%  |
| 8      | 18        | 11.69%  |
| 6      | 16        | 10.39%  |
| 16     | 5         | 3.25%   |
| 14     | 4         | 2.6%    |
| 12     | 4         | 2.6%    |
| 1      | 3         | 1.95%   |
| 10     | 2         | 1.3%    |
| 3      | 1         | 0.65%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 145       | 94.77%  |
| 2      | 8         | 5.23%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 110       | 71.9%   |
| 1      | 43        | 28.1%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 150       | 98.04%  |
| Unknown        | 2         | 1.31%   |
| 32-bit         | 1         | 0.65%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 34        | 22.22%  |
| 0x306a9    | 9         | 5.88%   |
| 0x306c3    | 6         | 3.92%   |
| 0x206d7    | 5         | 3.27%   |
| 0x806d1    | 4         | 2.61%   |
| 0x306d4    | 4         | 2.61%   |
| 0x1067a    | 4         | 2.61%   |
| 0x08701021 | 4         | 2.61%   |
| 0x08108109 | 4         | 2.61%   |
| 0x906a3    | 3         | 1.96%   |
| 0x806ec    | 3         | 1.96%   |
| 0x806ea    | 3         | 1.96%   |
| 0x806c1    | 3         | 1.96%   |
| 0x406e3    | 3         | 1.96%   |
| 0x406c4    | 3         | 1.96%   |
| 0x306f2    | 3         | 1.96%   |
| 0x206a7    | 3         | 1.96%   |
| 0x08701013 | 3         | 1.96%   |
| 0x906ed    | 2         | 1.31%   |
| 0x906ea    | 2         | 1.31%   |
| 0x6fd      | 2         | 1.31%   |
| 0x506e3    | 2         | 1.31%   |
| 0x20655    | 2         | 1.31%   |
| 0x106c2    | 2         | 1.31%   |
| 0x0a50000c | 2         | 1.31%   |
| 0x0a201016 | 2         | 1.31%   |
| 0x08600106 | 2         | 1.31%   |
| 0x0810100b | 2         | 1.31%   |
| 0x06001119 | 2         | 1.31%   |
| 0x06000822 | 2         | 1.31%   |
| 0xa0671    | 1         | 0.65%   |
| 0xa0660    | 1         | 0.65%   |
| 0xa0653    | 1         | 0.65%   |
| 0xa0652    | 1         | 0.65%   |
| 0x906e9    | 1         | 0.65%   |
| 0x906c0    | 1         | 0.65%   |
| 0x906a4    | 1         | 0.65%   |
| 0x806e9    | 1         | 0.65%   |
| 0x706a1    | 1         | 0.65%   |
| 0x6fb      | 1         | 0.65%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 20        | 13.07%  |
| Haswell          | 14        | 9.15%   |
| Zen 2            | 13        | 8.5%    |
| SandyBridge      | 10        | 6.54%   |
| IvyBridge        | 10        | 6.54%   |
| Core             | 8         | 5.23%   |
| Skylake          | 7         | 4.58%   |
| Zen+             | 6         | 3.92%   |
| Piledriver       | 6         | 3.92%   |
| Zen 3            | 5         | 3.27%   |
| Zen              | 5         | 3.27%   |
| Westmere         | 5         | 3.27%   |
| Penryn           | 5         | 3.27%   |
| Icelake          | 5         | 3.27%   |
| Silvermont       | 4         | 2.61%   |
| Broadwell        | 4         | 2.61%   |
| Alderlake Hybrid | 4         | 2.61%   |
| Unknown          | 4         | 2.61%   |
| TigerLake        | 3         | 1.96%   |
| CometLake        | 3         | 1.96%   |
| K10              | 2         | 1.31%   |
| Jaguar           | 2         | 1.31%   |
| Bonnell          | 2         | 1.31%   |
| Tremont          | 1         | 0.65%   |
| Puma             | 1         | 0.65%   |
| Nehalem          | 1         | 0.65%   |
| K8 Hammer        | 1         | 0.65%   |
| Goldmont plus    | 1         | 0.65%   |
| Bulldozer        | 1         | 0.65%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 72        | 42.86%  |
| Nvidia                     | 50        | 29.76%  |
| AMD                        | 42        | 25%     |
| Matrox Electronics Systems | 4         | 2.38%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 3.45%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6         | 3.45%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 2.87%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 4         | 2.3%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 2.3%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 2.3%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 2.3%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 3         | 1.72%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 3         | 1.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 1.72%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.72%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.72%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 1.72%   |
| Intel HD Graphics 620                                                                    | 3         | 1.72%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.72%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.72%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 3         | 1.72%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.72%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 1.72%   |
| AMD Renoir                                                                               | 3         | 1.72%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 1.72%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 3         | 1.72%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 1.15%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 1.15%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 1.15%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2         | 1.15%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2         | 1.15%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2         | 1.15%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 2         | 1.15%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.15%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.15%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.15%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 1.15%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 1.15%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.15%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 1.15%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 2         | 1.15%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 1.15%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.57%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 57        | 37.25%  |
| 1 x AMD        | 39        | 25.49%  |
| 1 x Nvidia     | 31        | 20.26%  |
| Intel + Nvidia | 15        | 9.8%    |
| 1 x Matrox     | 4         | 2.61%   |
| Other          | 3         | 1.96%   |
| AMD + Nvidia   | 2         | 1.31%   |
| 2 x Nvidia     | 1         | 0.65%   |
| 2 x AMD        | 1         | 0.65%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 116       | 75.82%  |
| Proprietary | 25        | 16.34%  |
| Unknown     | 12        | 7.84%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 82        | 53.25%  |
| 1.01-2.0   | 15        | 9.74%   |
| 0.51-1.0   | 15        | 9.74%   |
| 0.01-0.5   | 12        | 7.79%   |
| 3.01-4.0   | 11        | 7.14%   |
| 7.01-8.0   | 9         | 5.84%   |
| 5.01-6.0   | 4         | 2.6%    |
| 8.01-16.0  | 4         | 2.6%    |
| 2.01-3.0   | 1         | 0.65%   |
| 16.01-24.0 | 1         | 0.65%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 17        | 10.83%  |
| BOE                     | 15        | 9.55%   |
| Chimei Innolux          | 14        | 8.92%   |
| LG Display              | 13        | 8.28%   |
| Dell                    | 12        | 7.64%   |
| AU Optronics            | 12        | 7.64%   |
| Hewlett-Packard         | 11        | 7.01%   |
| Goldstar                | 8         | 5.1%    |
| BenQ                    | 8         | 5.1%    |
| Lenovo                  | 5         | 3.18%   |
| Sharp                   | 4         | 2.55%   |
| Ancor Communications    | 4         | 2.55%   |
| Acer                    | 4         | 2.55%   |
| ASUSTek Computer        | 3         | 1.91%   |
| ViewSonic               | 2         | 1.27%   |
| Iiyama                  | 2         | 1.27%   |
| AOC                     | 2         | 1.27%   |
| Xiaomi                  | 1         | 0.64%   |
| Wacom                   | 1         | 0.64%   |
| Valve                   | 1         | 0.64%   |
| Unknown                 | 1         | 0.64%   |
| UGD                     | 1         | 0.64%   |
| Toshiba                 | 1         | 0.64%   |
| Sony                    | 1         | 0.64%   |
| PANDA                   | 1         | 0.64%   |
| Panasonic               | 1         | 0.64%   |
| ONN                     | 1         | 0.64%   |
| NEC Computers           | 1         | 0.64%   |
| JVC                     | 1         | 0.64%   |
| IOD                     | 1         | 0.64%   |
| Gigabyte Technology     | 1         | 0.64%   |
| GDH                     | 1         | 0.64%   |
| Eizo                    | 1         | 0.64%   |
| DPC                     | 1         | 0.64%   |
| CTC                     | 1         | 0.64%   |
| Chi Mei Optoelectronics | 1         | 0.64%   |
| Apple                   | 1         | 0.64%   |
| Unknown                 | 1         | 0.64%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 3         | 1.86%   |
| Samsung Electronics LCD Monitor SDC416E 2880x1620 344x194mm 15.5-inch | 2         | 1.24%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 2         | 1.24%   |
| LG Display LCD Monitor LGD0353 1366x768 345x194mm 15.6-inch           | 2         | 1.24%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x189mm 14.1-inch               | 2         | 1.24%   |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch             | 2         | 1.24%   |
| Goldstar ULTRAGEAR GSM7765 2560x1440 697x392mm 31.5-inch              | 2         | 1.24%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 2         | 1.24%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 2         | 1.24%   |
| Xiaomi Mi TV XMD009A 3440x1440 480x270mm 21.7-inch                    | 1         | 0.62%   |
| Wacom Cintiq 22HDT WAC1037 1920x1080 476x268mm 21.5-inch              | 1         | 0.62%   |
| ViewSonic LCD Monitor VX2276 Series 1920x1080                         | 1         | 0.62%   |
| ViewSonic LCD Monitor VA2448 SERIES 1920x1080                         | 1         | 0.62%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 0.62%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1         | 0.62%   |
| UGD LCD Monitor UGD1302 1920x1080 290x160mm 13.0-inch                 | 1         | 0.62%   |
| Toshiba TV TSB0206 1920x1080 1600x1000mm 74.3-inch                    | 1         | 0.62%   |
| Sony TV SNY8102 1360x768                                              | 1         | 0.62%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 382x215mm 17.3-inch               | 1         | 0.62%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 0.62%   |
| Sharp LQ125T1JW02 SHP142F 2560x1440 277x155mm 12.5-inch               | 1         | 0.62%   |
| Sharp LCD Monitor SHP14C4 1920x1080 344x194mm 15.5-inch               | 1         | 0.62%   |
| Samsung Electronics SyncMaster SAM0578 1920x1080 476x268mm 21.5-inch  | 1         | 0.62%   |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch   | 1         | 0.62%   |
| Samsung Electronics SyncMaster SAM0428 1680x1050 459x296mm 21.5-inch  | 1         | 0.62%   |
| Samsung Electronics SyncMaster SAM03F2 1680x1050                      | 1         | 0.62%   |
| Samsung Electronics SyncMaster SAM03F0 1680x1050 433x271mm 20.1-inch  | 1         | 0.62%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 376x301mm 19.0-inch  | 1         | 0.62%   |
| Samsung Electronics SyncMaster SAM01AD 1600x1200 408x306mm 20.1-inch  | 1         | 0.62%   |
| Samsung Electronics SMS27A650 SAM082D 1920x1080 598x336mm 27.0-inch   | 1         | 0.62%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch    | 1         | 0.62%   |
| Samsung Electronics SM2333T SAM0736 1920x1080 477x268mm 21.5-inch     | 1         | 0.62%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 521x293mm 23.5-inch     | 1         | 0.62%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch     | 1         | 0.62%   |
| Samsung Electronics LCD Monitor U28D590 3840x2160                     | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 0.62%   |
| Samsung Electronics B2430L SAM0644 1920x1080 521x293mm 23.5-inch      | 1         | 0.62%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 0.62%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 70        | 45.45%  |
| 1366x768 (WXGA)    | 26        | 16.88%  |
| 2560x1440 (QHD)    | 9         | 5.84%   |
| 1680x1050 (WSXGA+) | 7         | 4.55%   |
| 1280x1024 (SXGA)   | 7         | 4.55%   |
| 3840x2160 (4K)     | 6         | 3.9%    |
| 1920x1200 (WUXGA)  | 4         | 2.6%    |
| 1600x900 (HD+)     | 4         | 2.6%    |
| 1280x800 (WXGA)    | 4         | 2.6%    |
| 3440x1440          | 2         | 1.3%    |
| 2880x1620          | 2         | 1.3%    |
| 1440x900 (WXGA+)   | 2         | 1.3%    |
| 1360x768           | 2         | 1.3%    |
| 800x1280           | 1         | 0.65%   |
| 3200x1080          | 1         | 0.65%   |
| 2288x1287          | 1         | 0.65%   |
| 2256x1504          | 1         | 0.65%   |
| 1920x540           | 1         | 0.65%   |
| 1920x1280          | 1         | 0.65%   |
| 1600x1200          | 1         | 0.65%   |
| 1024x768 (XGA)     | 1         | 0.65%   |
| Unknown            | 1         | 0.65%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 34        | 21.52%  |
| 24      | 14        | 8.86%   |
| 27      | 13        | 8.23%   |
| 21      | 13        | 8.23%   |
| 14      | 13        | 8.23%   |
| 13      | 12        | 7.59%   |
| 17      | 11        | 6.96%   |
| 23      | 9         | 5.7%    |
| Unknown | 7         | 4.43%   |
| 22      | 4         | 2.53%   |
| 20      | 4         | 2.53%   |
| 19      | 4         | 2.53%   |
| 18      | 4         | 2.53%   |
| 12      | 3         | 1.9%    |
| 31      | 2         | 1.27%   |
| 16      | 2         | 1.27%   |
| 142     | 1         | 0.63%   |
| 74      | 1         | 0.63%   |
| 72      | 1         | 0.63%   |
| 52      | 1         | 0.63%   |
| 34      | 1         | 0.63%   |
| 32      | 1         | 0.63%   |
| 11      | 1         | 0.63%   |
| 10      | 1         | 0.63%   |
| 7       | 1         | 0.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 59        | 37.58%  |
| 501-600        | 33        | 21.02%  |
| 401-500        | 27        | 17.2%   |
| 351-400        | 13        | 8.28%   |
| 201-300        | 8         | 5.1%    |
| Unknown        | 7         | 4.46%   |
| 601-700        | 3         | 1.91%   |
| 701-800        | 2         | 1.27%   |
| 1501-2000      | 2         | 1.27%   |
| More than 2000 | 1         | 0.64%   |
| 1001-1500      | 1         | 0.64%   |
| 1-100          | 1         | 0.64%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 104       | 72.22%  |
| 16/10   | 18        | 12.5%   |
| 5/4     | 5         | 3.47%   |
| Unknown | 5         | 3.47%   |
| 3/2     | 4         | 2.78%   |
| 6/5     | 2         | 1.39%   |
| 4/3     | 2         | 1.39%   |
| 32/9    | 1         | 0.69%   |
| 21/9    | 1         | 0.69%   |
| 1.00    | 1         | 0.69%   |
| 0.67    | 1         | 0.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 36        | 23.08%  |
| 201-250        | 30        | 19.23%  |
| 81-90          | 23        | 14.74%  |
| 301-350        | 13        | 8.33%   |
| 151-200        | 11        | 7.05%   |
| 141-150        | 7         | 4.49%   |
| 121-130        | 7         | 4.49%   |
| Unknown        | 7         | 4.49%   |
| 251-300        | 6         | 3.85%   |
| More than 1000 | 4         | 2.56%   |
| 351-500        | 4         | 2.56%   |
| 61-70          | 3         | 1.92%   |
| 71-80          | 2         | 1.28%   |
| 51-60          | 2         | 1.28%   |
| 1-40           | 1         | 0.64%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 56        | 35.9%   |
| 101-120       | 40        | 25.64%  |
| 121-160       | 39        | 25%     |
| 161-240       | 7         | 4.49%   |
| Unknown       | 7         | 4.49%   |
| 1-50          | 4         | 2.56%   |
| More than 240 | 3         | 1.92%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 119       | 77.78%  |
| 2     | 17        | 11.11%  |
| 0     | 13        | 8.5%    |
| 3     | 3         | 1.96%   |
| 4     | 1         | 0.65%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 87        | 38.16%  |
| Realtek Semiconductor    | 77        | 33.77%  |
| Qualcomm Atheros         | 14        | 6.14%   |
| Broadcom                 | 11        | 4.82%   |
| Ralink Technology        | 5         | 2.19%   |
| Broadcom Limited         | 5         | 2.19%   |
| ASIX Electronics         | 5         | 2.19%   |
| Nvidia                   | 4         | 1.75%   |
| MediaTek                 | 4         | 1.75%   |
| TP-Link                  | 3         | 1.32%   |
| Dell                     | 2         | 0.88%   |
| VIA Technologies         | 1         | 0.44%   |
| Sitecom Europe           | 1         | 0.44%   |
| Sierra Wireless          | 1         | 0.44%   |
| Ralink                   | 1         | 0.44%   |
| Qualcomm                 | 1         | 0.44%   |
| Micro Star International | 1         | 0.44%   |
| Mellanox Technologies    | 1         | 0.44%   |
| Marvell Technology Group | 1         | 0.44%   |
| Huawei Technologies      | 1         | 0.44%   |
| Hewlett-Packard          | 1         | 0.44%   |
| Chelsio Communications   | 1         | 0.44%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 52        | 19.05%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 3.3%    |
| Intel Wi-Fi 6 AX200                                               | 7         | 2.56%   |
| Intel I211 Gigabit Network Connection                             | 7         | 2.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 2.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.83%   |
| Ralink MT7601U Wireless Adapter                                   | 5         | 1.83%   |
| Intel Wireless 8265 / 8275                                        | 5         | 1.83%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5         | 1.83%   |
| Intel 82574L Gigabit Network Connection                           | 5         | 1.83%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 1.47%   |
| Intel Wireless-AC 9260                                            | 4         | 1.47%   |
| Intel Wireless 7260                                               | 4         | 1.47%   |
| Intel Ethernet Connection (2) I218-V                              | 4         | 1.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.1%    |
| Realtek RTL8188EE Wireless Network Adapter                        | 3         | 1.1%    |
| Nvidia MCP61 Ethernet                                             | 3         | 1.1%    |
| Intel Wireless 8260                                               | 3         | 1.1%    |
| Intel Wireless 7265                                               | 3         | 1.1%    |
| Intel I350 Gigabit Network Connection                             | 3         | 1.1%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 1.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 1.1%    |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 1.1%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 2         | 0.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.73%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 0.73%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.73%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.73%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 2         | 0.73%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 0.73%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.73%   |
| Intel Wireless 3160                                               | 2         | 0.73%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 0.73%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 0.73%   |
| Intel Ethernet Controller I225-V                                  | 2         | 0.73%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.73%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.73%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.73%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.73%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 57        | 52.78%  |
| Realtek Semiconductor    | 17        | 15.74%  |
| Qualcomm Atheros         | 10        | 9.26%   |
| Ralink Technology        | 5         | 4.63%   |
| MediaTek                 | 4         | 3.7%    |
| TP-Link                  | 3         | 2.78%   |
| Broadcom Limited         | 3         | 2.78%   |
| Broadcom                 | 3         | 2.78%   |
| Dell                     | 2         | 1.85%   |
| Sitecom Europe           | 1         | 0.93%   |
| Sierra Wireless          | 1         | 0.93%   |
| Ralink                   | 1         | 0.93%   |
| Micro Star International | 1         | 0.93%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                                   | 7         | 6.42%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 5         | 4.59%   |
| Ralink MT7601U Wireless Adapter                                                       | 5         | 4.59%   |
| Intel Wireless 8265 / 8275                                                            | 5         | 4.59%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 5         | 4.59%   |
| Intel Wireless-AC 9260                                                                | 4         | 3.67%   |
| Intel Wireless 7260                                                                   | 4         | 3.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 3         | 2.75%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 3         | 2.75%   |
| Intel Wireless 8260                                                                   | 3         | 2.75%   |
| Intel Wireless 7265                                                                   | 3         | 2.75%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 3         | 2.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 3         | 2.75%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 2         | 1.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 1.83%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 2         | 1.83%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                         | 2         | 1.83%   |
| Intel Wireless 3160                                                                   | 2         | 1.83%   |
| Intel Wi-Fi 6 AX201                                                                   | 2         | 1.83%   |
| Intel Tiger Lake PCH CNVi WiFi                                                        | 2         | 1.83%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 2         | 1.83%   |
| Intel Centrino Ultimate-N 6300                                                        | 2         | 1.83%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                                               | 2         | 1.83%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                           | 1         | 0.92%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                                 | 1         | 0.92%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                            | 1         | 0.92%   |
| Sitecom Europe WL-113 rev 2 Wireless Network USB Adapter                              | 1         | 0.92%   |
| Sierra Wireless EM7305                                                                | 1         | 0.92%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                    | 1         | 0.92%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 1         | 0.92%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1         | 0.92%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                           | 1         | 0.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 0.92%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1         | 0.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1         | 0.92%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 1         | 0.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 0.92%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                      | 1         | 0.92%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.92%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 0.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 69        | 44.81%  |
| Intel                    | 52        | 33.77%  |
| Broadcom                 | 9         | 5.84%   |
| Qualcomm Atheros         | 7         | 4.55%   |
| ASIX Electronics         | 5         | 3.25%   |
| Nvidia                   | 4         | 2.6%    |
| Broadcom Limited         | 2         | 1.3%    |
| VIA Technologies         | 1         | 0.65%   |
| Qualcomm                 | 1         | 0.65%   |
| Mellanox Technologies    | 1         | 0.65%   |
| Marvell Technology Group | 1         | 0.65%   |
| Huawei Technologies      | 1         | 0.65%   |
| Chelsio Communications   | 1         | 0.65%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 52        | 31.9%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 5.52%   |
| Intel I211 Gigabit Network Connection                             | 7         | 4.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 4.29%   |
| Intel 82574L Gigabit Network Connection                           | 5         | 3.07%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 2.45%   |
| Intel Ethernet Connection (2) I218-V                              | 4         | 2.45%   |
| Nvidia MCP61 Ethernet                                             | 3         | 1.84%   |
| Intel I350 Gigabit Network Connection                             | 3         | 1.84%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 1.84%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.23%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 1.23%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.23%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 1.23%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 1.23%   |
| Intel Ethernet Controller I225-V                                  | 2         | 1.23%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.23%   |
| Intel Ethernet Connection I217-V                                  | 2         | 1.23%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 1.23%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.23%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.23%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.23%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.23%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.23%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 1.23%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 2         | 1.23%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 2         | 1.23%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 0.61%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.61%   |
| Qualcomm Redmi Note 8                                             | 1         | 0.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.61%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.61%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]             | 1         | 0.61%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.61%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.61%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 0.61%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.61%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 0.61%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 0.61%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 140       | 57.14%  |
| WiFi     | 104       | 42.45%  |
| Modem    | 1         | 0.41%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 83        | 54.25%  |
| WiFi     | 70        | 45.75%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 79        | 50.97%  |
| 1     | 58        | 37.42%  |
| 3     | 6         | 3.87%   |
| 4     | 5         | 3.23%   |
| 0     | 5         | 3.23%   |
| 5     | 2         | 1.29%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 136       | 87.74%  |
| Yes  | 19        | 12.26%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 50        | 53.19%  |
| Cambridge Silicon Radio         | 13        | 13.83%  |
| Realtek Semiconductor           | 9         | 9.57%   |
| Broadcom                        | 6         | 6.38%   |
| IMC Networks                    | 4         | 4.26%   |
| Qualcomm Atheros Communications | 3         | 3.19%   |
| Micro Star International        | 2         | 2.13%   |
| MediaTek                        | 2         | 2.13%   |
| Apple                           | 2         | 2.13%   |
| TP-Link                         | 1         | 1.06%   |
| Toshiba                         | 1         | 1.06%   |
| Foxconn / Hon Hai               | 1         | 1.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 19        | 20.21%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 13        | 13.83%  |
| Intel AX201 Bluetooth                               | 7         | 7.45%   |
| Intel AX200 Bluetooth                               | 7         | 7.45%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 5.32%   |
| Intel AX210 Bluetooth                               | 5         | 5.32%   |
| Realtek Bluetooth Radio                             | 4         | 4.26%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 4.26%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 4.26%   |
| IMC Networks Wireless_Device                        | 3         | 3.19%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 2.13%   |
| MediaTek Wireless_Device                            | 2         | 2.13%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 2.13%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 2.13%   |
| TP-Link UB500 Adapter                               | 1         | 1.06%   |
| Toshiba Askey Bluetooth Module                      | 1         | 1.06%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.06%   |
| Micro Star International Bluetooth Dongle           | 1         | 1.06%   |
| Micro Star International Bluetooth Device           | 1         | 1.06%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.06%   |
| Intel Bluetooth Device                              | 1         | 1.06%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.06%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 1.06%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.06%   |
| Broadcom BCM20702A0                                 | 1         | 1.06%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.06%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 1.06%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.06%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 1         | 1.06%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 98        | 47.12%  |
| AMD                    | 48        | 23.08%  |
| Nvidia                 | 41        | 19.71%  |
| Creative Labs          | 7         | 3.37%   |
| C-Media Electronics    | 4         | 1.92%   |
| Texas Instruments      | 2         | 0.96%   |
| VIA Technologies       | 1         | 0.48%   |
| RME                    | 1         | 0.48%   |
| M-Audio                | 1         | 0.48%   |
| Kingston Technology    | 1         | 0.48%   |
| Holtek Semiconductor   | 1         | 0.48%   |
| Generalplus Technology | 1         | 0.48%   |
| EGO SYStems            | 1         | 0.48%   |
| ASUSTek Computer       | 1         | 0.48%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 14        | 5.53%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 12        | 4.74%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 12        | 4.74%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 9         | 3.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 3.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 2.77%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 6         | 2.37%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 6         | 2.37%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 5         | 1.98%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 1.98%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 1.98%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 1.98%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 1.98%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 1.98%   |
| AMD FCH Azalia Controller                                                                         | 5         | 1.98%   |
| Nvidia MCP61 High Definition Audio                                                                | 4         | 1.58%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 1.58%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.58%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 1.58%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 1.58%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.58%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 4         | 1.58%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.58%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 1.58%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 4         | 1.58%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.19%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.19%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.19%   |
| Nvidia Audio device                                                                               | 3         | 1.19%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.19%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3         | 1.19%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.19%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.19%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus]   | 3         | 1.19%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.19%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 3         | 1.19%   |
| AMD Navi 10 HDMI Audio                                                                            | 3         | 1.19%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 3         | 1.19%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 2         | 0.79%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 30        | 19.11%  |
| Samsung Electronics | 25        | 15.92%  |
| Kingston            | 25        | 15.92%  |
| Corsair             | 15        | 9.55%   |
| Crucial             | 12        | 7.64%   |
| Unknown             | 9         | 5.73%   |
| Micron Technology   | 9         | 5.73%   |
| Team                | 4         | 2.55%   |
| G.Skill             | 3         | 1.91%   |
| Transcend           | 2         | 1.27%   |
| Smart               | 2         | 1.27%   |
| Ramaxel Technology  | 2         | 1.27%   |
| GOODRAM             | 2         | 1.27%   |
| AMD                 | 2         | 1.27%   |
| A-DATA Technology   | 2         | 1.27%   |
| Unknown             | 2         | 1.27%   |
| Strontium           | 1         | 0.64%   |
| Silicon Power       | 1         | 0.64%   |
| Patriot             | 1         | 0.64%   |
| Neo Forza           | 1         | 0.64%   |
| Nanya Technology    | 1         | 0.64%   |
| HPE                 | 1         | 0.64%   |
| GLOWAY              | 1         | 0.64%   |
| Essencore Limited   | 1         | 0.64%   |
| Elpida              | 1         | 0.64%   |
| Avant               | 1         | 0.64%   |
| A Force             | 1         | 0.64%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                        | 2         | 1.18%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s          | 2         | 1.18%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 2         | 1.18%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s   | 2         | 1.18%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 2         | 1.18%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips 6400MT/s   | 2         | 1.18%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s       | 2         | 1.18%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s       | 2         | 1.18%   |
| Corsair RAM CMZ32GX3M4X1600C10 8GB DIMM DDR3 1600MT/s       | 2         | 1.18%   |
| Unknown                                                     | 2         | 1.18%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                   | 1         | 0.59%   |
| Unknown RAM Module 4096MB DIMM DDR3 65535MT/s               | 1         | 0.59%   |
| Unknown RAM Module 2GB DIMM DDR2 533MT/s                    | 1         | 0.59%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                  | 1         | 0.59%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                      | 1         | 0.59%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                      | 1         | 0.59%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s               | 1         | 0.59%   |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s                  | 1         | 0.59%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                      | 1         | 0.59%   |
| Transcend RAM TS256MLQ72V6U 2GB DIMM DDR2 667MT/s           | 1         | 0.59%   |
| Transcend RAM JM1600KLN-8GK 4096MB DIMM DDR3 1600MT/s       | 1         | 0.59%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3733MT/s          | 1         | 0.59%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s          | 1         | 0.59%   |
| Strontium RAM SRT4G86U1-P9H 4096MB DIMM DDR3 1333MT/s       | 1         | 0.59%   |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s       | 1         | 0.59%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s         | 1         | 0.59%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s     | 1         | 0.59%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s             | 1         | 0.59%   |
| SK hynix RAM HYMP512F72CP8N3-Y5 1024MB FB-DIMM DDR2 667MT/s | 1         | 0.59%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s        | 1         | 0.59%   |
| SK hynix RAM HMT41GV7BMR4A-H9 16GB DIMM 1333MT/s            | 1         | 0.59%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 2000MT/s        | 1         | 0.59%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s      | 1         | 0.59%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 1         | 0.59%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s        | 1         | 0.59%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.59%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB DIMM DDR3 1600MT/s        | 1         | 0.59%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s      | 1         | 0.59%   |
| SK hynix RAM HMT351R7CFR8A-H9 4GB DIMM DDR3 1333MT/s        | 1         | 0.59%   |
| SK hynix RAM HMT31GR7EFR4A 8192MB DIMM DDR3 1600MT/s        | 1         | 0.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 63        | 46.32%  |
| DDR3    | 49        | 36.03%  |
| DDR2    | 7         | 5.15%   |
| SDRAM   | 4         | 2.94%   |
| LPDDR5  | 3         | 2.21%   |
| LPDDR4  | 3         | 2.21%   |
| LPDDR3  | 3         | 2.21%   |
| Unknown | 2         | 1.47%   |
| DDR5    | 1         | 0.74%   |
| DDR     | 1         | 0.74%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 66        | 48.53%  |
| SODIMM       | 62        | 45.59%  |
| Row Of Chips | 6         | 4.41%   |
| RIMM         | 1         | 0.74%   |
| FB-DIMM      | 1         | 0.74%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 61        | 40.67%  |
| 4096  | 44        | 29.33%  |
| 16384 | 20        | 13.33%  |
| 2048  | 12        | 8%      |
| 32768 | 7         | 4.67%   |
| 1024  | 6         | 4%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 35        | 23.65%  |
| 3200    | 20        | 13.51%  |
| 2667    | 16        | 10.81%  |
| 2400    | 13        | 8.78%   |
| 3600    | 8         | 5.41%   |
| 1333    | 8         | 5.41%   |
| 2133    | 5         | 3.38%   |
| 667     | 5         | 3.38%   |
| 3800    | 4         | 2.7%    |
| 1867    | 3         | 2.03%   |
| Unknown | 3         | 2.03%   |
| 6400    | 2         | 1.35%   |
| 2800    | 2         | 1.35%   |
| 2666    | 2         | 1.35%   |
| 1866    | 2         | 1.35%   |
| 1334    | 2         | 1.35%   |
| 975     | 2         | 1.35%   |
| 533     | 2         | 1.35%   |
| 65535   | 1         | 0.68%   |
| 4800    | 1         | 0.68%   |
| 4267    | 1         | 0.68%   |
| 4266    | 1         | 0.68%   |
| 4199    | 1         | 0.68%   |
| 3733    | 1         | 0.68%   |
| 3400    | 1         | 0.68%   |
| 2933    | 1         | 0.68%   |
| 2472    | 1         | 0.68%   |
| 2187    | 1         | 0.68%   |
| 2000    | 1         | 0.68%   |
| 1066    | 1         | 0.68%   |
| 800     | 1         | 0.68%   |
| 701     | 1         | 0.68%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 33.33%  |
| Brother Industries  | 3         | 33.33%  |
| QinHeng Electronics | 1         | 11.11%  |
| Dell                | 1         | 11.11%  |
| Canon               | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                        | Computers | Percent |
|------------------------------|-----------|---------|
| QinHeng CH340S               | 1         | 11.11%  |
| HP OfficeJet Pro 9010 series | 1         | 11.11%  |
| HP ENVY 4520 series          | 1         | 11.11%  |
| HP ENVY 4500 series          | 1         | 11.11%  |
| Dell 2330d Laser Printer     | 1         | 11.11%  |
| Canon CanoScan LiDE 300      | 1         | 11.11%  |
| Brother Printer              | 1         | 11.11%  |
| Brother HL-L5102DW           | 1         | 11.11%  |
| Brother HL-L2320D series     | 1         | 11.11%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 1         | 33.33%  |
| Hewlett-Packard | 1         | 33.33%  |
| Canon           | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1         | 33.33%  |
| HP ScanJet 5590                               | 1         | 33.33%  |
| Canon CanoScan LIDE 25                        | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 20        | 24.39%  |
| Logitech                               | 13        | 15.85%  |
| Realtek Semiconductor                  | 5         | 6.1%    |
| Microdia                               | 5         | 6.1%    |
| Bison Electronics                      | 5         | 6.1%    |
| IMC Networks                           | 4         | 4.88%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 4.88%   |
| Quanta                                 | 3         | 3.66%   |
| Luxvisions Innotech Limited            | 3         | 3.66%   |
| Lite-On Technology                     | 3         | 3.66%   |
| Acer                                   | 3         | 3.66%   |
| Syntek                                 | 2         | 2.44%   |
| Sunplus Innovation Technology          | 2         | 2.44%   |
| Sonix Technology                       | 2         | 2.44%   |
| Samsung Electronics                    | 2         | 2.44%   |
| Z-Star Microelectronics                | 1         | 1.22%   |
| Silicon Motion                         | 1         | 1.22%   |
| Motorola PCS                           | 1         | 1.22%   |
| Microsoft                              | 1         | 1.22%   |
| Lenovo                                 | 1         | 1.22%   |
| Apple                                  | 1         | 1.22%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 4         | 4.88%   |
| Logitech Webcam C270                                 | 3         | 3.66%   |
| Bison HD Webcam                                      | 3         | 3.66%   |
| Acer BisonCam,NB Pro                                 | 3         | 3.66%   |
| Sonix USB2.0 FHD UVC WebCam                          | 2         | 2.44%   |
| Samsung Galaxy series, misc. (MTP mode)              | 2         | 2.44%   |
| Quanta HP Webcam                                     | 2         | 2.44%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 2         | 2.44%   |
| Chicony HD User Facing                               | 2         | 2.44%   |
| Chicony FJ Camera                                    | 2         | 2.44%   |
| Z-Star Vimicro USB2.0 Camera                         | 1         | 1.22%   |
| Syntek USB2.0 Camera                                 | 1         | 1.22%   |
| Syntek Integrated Camera                             | 1         | 1.22%   |
| Sunplus Laptop_Integrated_Webcam_FHD                 | 1         | 1.22%   |
| Sunplus Integrated_Webcam_HD                         | 1         | 1.22%   |
| Silicon Motion Web Camera                            | 1         | 1.22%   |
| Realtek USB Camera                                   | 1         | 1.22%   |
| Realtek Laptop Camera                                | 1         | 1.22%   |
| Realtek Integrated Camera                            | 1         | 1.22%   |
| Realtek EasyCamera                                   | 1         | 1.22%   |
| Realtek 2SF022                                       | 1         | 1.22%   |
| Quanta HP Wide Vision HD Camera                      | 1         | 1.22%   |
| Motorola PCS XT1033 [Moto G], PTP mode               | 1         | 1.22%   |
| Microsoft LifeCam HD-3000                            | 1         | 1.22%   |
| Microdia Laptop_Integrated_Webcam_2M                 | 1         | 1.22%   |
| Microdia Integrated_Webcam_HD                        | 1         | 1.22%   |
| Microdia Integrated Webcam                           | 1         | 1.22%   |
| Microdia Dell Integrated HD Webcam                   | 1         | 1.22%   |
| Microdia Camera                                      | 1         | 1.22%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.22%   |
| Logitech Webcam C310                                 | 1         | 1.22%   |
| Logitech Webcam C300                                 | 1         | 1.22%   |
| Logitech Webcam C170                                 | 1         | 1.22%   |
| Logitech QuickCam Pro 9000                           | 1         | 1.22%   |
| Logitech Logitech Webcam C160                        | 1         | 1.22%   |
| Logitech HD Webcam C910                              | 1         | 1.22%   |
| Logitech HD Webcam C525                              | 1         | 1.22%   |
| Logitech HD Pro Webcam C920                          | 1         | 1.22%   |
| Logitech C922 Pro Stream Webcam                      | 1         | 1.22%   |
| Logitech C920 PRO HD Webcam                          | 1         | 1.22%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 9         | 45%     |
| Synaptics                          | 3         | 15%     |
| STMicroelectronics                 | 2         | 10%     |
| Realtek USB2.0 Finger Print Bridge | 2         | 10%     |
| Elan Microelectronics              | 2         | 10%     |
| Shenzhen Goodix Technology         | 1         | 5%      |
| LighTuning Technology              | 1         | 5%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                                 | 3         | 15%     |
| STMicroelectronics Fingerprint Reader                           | 2         | 10%     |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 2         | 10%     |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 1         | 5%      |
| Validity Sensors VFS495 Fingerprint Reader                      | 1         | 5%      |
| Validity Sensors VFS451 Fingerprint Reader                      | 1         | 5%      |
| Validity Sensors VFS300 Fingerprint Reader                      | 1         | 5%      |
| Validity Sensors VFS Fingerprint sensor                         | 1         | 5%      |
| Validity Sensors VFS 5011 fingerprint sensor                    | 1         | 5%      |
| Synaptics UWP WBDI                                              | 1         | 5%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 1         | 5%      |
| Shenzhen Goodix  FingerPrint Device                             | 1         | 5%      |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 1         | 5%      |
| Elan ELAN:Fingerprint                                           | 1         | 5%      |
| Elan ELAN:ARM-M4                                                | 1         | 5%      |
| Unknown                                                         | 1         | 5%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 4         | 44.44%  |
| Broadcom              | 2         | 22.22%  |
| O2 Micro              | 1         | 11.11%  |
| Lenovo                | 1         | 11.11%  |
| Gemalto (was Gemplus) | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                    | 4         | 44.44%  |
| O2 Micro OZ776 CCID Smartcard Reader                   | 1         | 11.11%  |
| Lenovo Integrated Smart Card Reader                    | 1         | 11.11%  |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor         | 1         | 11.11%  |
| Broadcom 5880                                          | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 91        | 58.33%  |
| 1     | 36        | 23.08%  |
| 2     | 17        | 10.9%   |
| 3     | 6         | 3.85%   |
| 4     | 5         | 3.21%   |
| 5     | 1         | 0.64%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 19        | 17.92%  |
| Graphics card            | 18        | 16.98%  |
| Sound                    | 15        | 14.15%  |
| Net/wireless             | 10        | 9.43%   |
| Communication controller | 9         | 8.49%   |
| Chipcard                 | 9         | 8.49%   |
| Unassigned class         | 4         | 3.77%   |
| Multimedia controller    | 4         | 3.77%   |
| Card reader              | 4         | 3.77%   |
| Camera                   | 4         | 3.77%   |
| Bluetooth                | 3         | 2.83%   |
| Net/ethernet             | 2         | 1.89%   |
| Storage/raid             | 1         | 0.94%   |
| Storage/ide              | 1         | 0.94%   |
| Storage/ata              | 1         | 0.94%   |
| Storage                  | 1         | 0.94%   |
| Firewire controller      | 1         | 0.94%   |

