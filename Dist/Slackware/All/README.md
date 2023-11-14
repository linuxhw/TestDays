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

Total: 204

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
| Slackware 15.0  | 94        | 57.67%  |
| Slackware 14.2  | 63        | 38.65%  |
| Slackware 14.2+ | 6         | 3.68%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Slackware | 161       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.19           | 20        | 11.49%  |
| 4.19.80           | 8         | 4.6%    |
| 5.19.17           | 7         | 4.02%   |
| 5.15.63           | 6         | 3.45%   |
| 5.10.28-Unraid    | 6         | 3.45%   |
| 5.15.117          | 5         | 2.87%   |
| 5.15.27           | 4         | 2.3%    |
| 4.4.190           | 4         | 2.3%    |
| 5.19.17-Unraid    | 3         | 1.72%   |
| 5.15.94           | 3         | 1.72%   |
| 5.15.38           | 3         | 1.72%   |
| 4.4.240           | 3         | 1.72%   |
| 6.1.44            | 2         | 1.15%   |
| 5.3.7             | 2         | 1.15%   |
| 5.17.2            | 2         | 1.15%   |
| 5.17.1            | 2         | 1.15%   |
| 5.16.13           | 2         | 1.15%   |
| 5.15.80           | 2         | 1.15%   |
| 5.15.30-Unraid    | 2         | 1.15%   |
| 5.13.8            | 2         | 1.15%   |
| 5.10.3            | 2         | 1.15%   |
| 4.4.276           | 2         | 1.15%   |
| 6.5.5             | 1         | 0.57%   |
| 6.1.51            | 1         | 0.57%   |
| 6.1.27            | 1         | 0.57%   |
| 6.1.20            | 1         | 0.57%   |
| 6.1.13            | 1         | 0.57%   |
| 6.1.12            | 1         | 0.57%   |
| 6.1.1             | 1         | 0.57%   |
| 5.7.0             | 1         | 0.57%   |
| 5.5.10            | 1         | 0.57%   |
| 5.4.77            | 1         | 0.57%   |
| 5.4.75            | 1         | 0.57%   |
| 5.4.62            | 1         | 0.57%   |
| 5.4.53-APRL       | 1         | 0.57%   |
| 5.4.50            | 1         | 0.57%   |
| 5.4.47            | 1         | 0.57%   |
| 5.4.43            | 1         | 0.57%   |
| 5.4.24toshiba-new | 1         | 0.57%   |
| 5.4.2             | 1         | 0.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.19  | 20        | 11.49%  |
| 5.19.17  | 10        | 5.75%   |
| 4.19.80  | 8         | 4.6%    |
| 5.15.63  | 6         | 3.45%   |
| 5.10.28  | 6         | 3.45%   |
| 5.15.117 | 5         | 2.87%   |
| 4.4.190  | 5         | 2.87%   |
| 5.15.27  | 4         | 2.3%    |
| 5.15.94  | 3         | 1.72%   |
| 5.15.38  | 3         | 1.72%   |
| 4.4.240  | 3         | 1.72%   |
| 6.1.44   | 2         | 1.15%   |
| 5.3.7    | 2         | 1.15%   |
| 5.17.2   | 2         | 1.15%   |
| 5.17.1   | 2         | 1.15%   |
| 5.16.13  | 2         | 1.15%   |
| 5.15.80  | 2         | 1.15%   |
| 5.15.30  | 2         | 1.15%   |
| 5.14.15  | 2         | 1.15%   |
| 5.13.8   | 2         | 1.15%   |
| 5.10.3   | 2         | 1.15%   |
| 4.4.276  | 2         | 1.15%   |
| 6.5.5    | 1         | 0.57%   |
| 6.1.51   | 1         | 0.57%   |
| 6.1.27   | 1         | 0.57%   |
| 6.1.20   | 1         | 0.57%   |
| 6.1.13   | 1         | 0.57%   |
| 6.1.12   | 1         | 0.57%   |
| 6.1.1    | 1         | 0.57%   |
| 5.7.0    | 1         | 0.57%   |
| 5.5.10   | 1         | 0.57%   |
| 5.4.77   | 1         | 0.57%   |
| 5.4.75   | 1         | 0.57%   |
| 5.4.62   | 1         | 0.57%   |
| 5.4.53   | 1         | 0.57%   |
| 5.4.50   | 1         | 0.57%   |
| 5.4.47   | 1         | 0.57%   |
| 5.4.43   | 1         | 0.57%   |
| 5.4.24   | 1         | 0.57%   |
| 5.4.2    | 1         | 0.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 57        | 33.14%  |
| 4.4     | 17        | 9.88%   |
| 5.10    | 15        | 8.72%   |
| 4.19    | 15        | 8.72%   |
| 5.4     | 13        | 7.56%   |
| 5.19    | 11        | 6.4%    |
| 6.1     | 7         | 4.07%   |
| 5.14    | 7         | 4.07%   |
| 5.13    | 7         | 4.07%   |
| 5.17    | 6         | 3.49%   |
| 5.16    | 6         | 3.49%   |
| 5.3     | 2         | 1.16%   |
| 4.9     | 2         | 1.16%   |
| 6.5     | 1         | 0.58%   |
| 5.7     | 1         | 0.58%   |
| 5.5     | 1         | 0.58%   |
| 5.2     | 1         | 0.58%   |
| 5.12    | 1         | 0.58%   |
| 4.20    | 1         | 0.58%   |
| 4.16    | 1         | 0.58%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 158       | 98.14%  |
| aarch64 | 2         | 1.24%   |
| i686    | 1         | 0.62%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| XFCE          | 50        | 30.49%  |
| Unknown       | 50        | 30.49%  |
| KDE5          | 44        | 26.83%  |
| KDE           | 5         | 3.05%   |
| GNOME         | 3         | 1.83%   |
| xwmconfig     | 2         | 1.22%   |
| MATE          | 2         | 1.22%   |
| fvwm          | 2         | 1.22%   |
| X-Generic     | 1         | 0.61%   |
| X-Cinnamon    | 1         | 0.61%   |
| LXQt          | 1         | 0.61%   |
| Enlightenment | 1         | 0.61%   |
| awesome       | 1         | 0.61%   |
| 2bwm          | 1         | 0.61%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 106       | 63.86%  |
| Tty     | 41        | 24.7%   |
| Unknown | 12        | 7.23%   |
| Wayland | 7         | 4.22%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 65        | 38.92%  |
| SDDM    | 54        | 32.34%  |
| XDM     | 39        | 23.35%  |
| LightDM | 5         | 2.99%   |
| SLiM    | 3         | 1.8%    |
| GDM     | 1         | 0.6%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 87        | 54.04%  |
| Unknown     | 43        | 26.71%  |
| it_IT       | 5         | 3.11%   |
| ru_RU       | 4         | 2.48%   |
| pt_BR       | 4         | 2.48%   |
| fr_FR       | 3         | 1.86%   |
| en_GB       | 3         | 1.86%   |
| de_DE       | 3         | 1.86%   |
| us          | 1         | 0.62%   |
| sr_RS@latin | 1         | 0.62%   |
| pt_PT       | 1         | 0.62%   |
| pl_PL       | 1         | 0.62%   |
| es_ES.UTF8  | 1         | 0.62%   |
| es_ES       | 1         | 0.62%   |
| en_US.ASCII | 1         | 0.62%   |
| en_AU       | 1         | 0.62%   |
| C           | 1         | 0.62%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 85        | 52.15%  |
| EFI  | 78        | 47.85%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 120       | 73.62%  |
| Btrfs    | 18        | 11.04%  |
| Xfs      | 7         | 4.29%   |
| Overlay  | 7         | 4.29%   |
| Rootfs   | 4         | 2.45%   |
| Zfs      | 1         | 0.61%   |
| Tmpfs    | 1         | 0.61%   |
| Reiserfs | 1         | 0.61%   |
| Jfs      | 1         | 0.61%   |
| F2fs     | 1         | 0.61%   |
| Ext3     | 1         | 0.61%   |
| Ext2     | 1         | 0.61%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 109       | 66.06%  |
| MBR     | 38        | 23.03%  |
| Unknown | 18        | 10.91%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 111       | 67.68%  |
| Yes       | 53        | 32.32%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 110       | 67.9%   |
| Yes       | 52        | 32.1%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 28        | 17.39%  |
| Hewlett-Packard     | 25        | 15.53%  |
| Lenovo              | 22        | 13.66%  |
| Dell                | 15        | 9.32%   |
| MSI                 | 13        | 8.07%   |
| ASRock              | 11        | 6.83%   |
| Gigabyte Technology | 7         | 4.35%   |
| Acer                | 6         | 3.73%   |
| Toshiba             | 4         | 2.48%   |
| Notebook            | 3         | 1.86%   |
| Fujitsu             | 3         | 1.86%   |
| Dynabook            | 2         | 1.24%   |
| Apple               | 2         | 1.24%   |
| Unknown             | 2         | 1.24%   |
| Valve               | 1         | 0.62%   |
| TYAN Computer       | 1         | 0.62%   |
| System76            | 1         | 0.62%   |
| Supermicro          | 1         | 0.62%   |
| Sony                | 1         | 0.62%   |
| Shuttle             | 1         | 0.62%   |
| Samsung Electronics | 1         | 0.62%   |
| Radxa               | 1         | 0.62%   |
| NetGear             | 1         | 0.62%   |
| Microsoft           | 1         | 0.62%   |
| Intel               | 1         | 0.62%   |
| Huanan              | 1         | 0.62%   |
| HPE                 | 1         | 0.62%   |
| HEDYCOMPUTER        | 1         | 0.62%   |
| Framework           | 1         | 0.62%   |
| Foxconn             | 1         | 0.62%   |
| Biostar             | 1         | 0.62%   |
| AMI                 | 1         | 0.62%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| ASUS All Series                          | 4         | 2.48%   |
| Toshiba Satellite C660                   | 2         | 1.24%   |
| Lenovo V330-14ARR 81B1                   | 2         | 1.24%   |
| ASUS VivoBook_ASUSLaptop K6500ZE_K6500ZE | 2         | 1.24%   |
| ASRock N68-S3 FX                         | 2         | 1.24%   |
| Unknown                                  | 2         | 1.24%   |
| Valve Jupiter                            | 1         | 0.62%   |
| TYAN S7012                               | 1         | 0.62%   |
| Toshiba Satellite P50-A-12Z              | 1         | 0.62%   |
| Toshiba PORTEGE Z30-A                    | 1         | 0.62%   |
| System76 Oryx Pro                        | 1         | 0.62%   |
| Supermicro X9DA7/E                       | 1         | 0.62%   |
| Sony SVE1713A1EW                         | 1         | 0.62%   |
| Shuttle NC03U                            | 1         | 0.62%   |
| Samsung 300E5M/300E5L                    | 1         | 0.62%   |
| Radxa ROCK Pi 4                          | 1         | 0.62%   |
| Notebook X170KM-G                        | 1         | 0.62%   |
| Notebook P7xxTM                          | 1         | 0.62%   |
| Notebook NL40_50CU                       | 1         | 0.62%   |
| NetGear ReadyDATA 5200                   | 1         | 0.62%   |
| MSI MS-7C52                              | 1         | 0.62%   |
| MSI MS-7C02                              | 1         | 0.62%   |
| MSI MS-7996                              | 1         | 0.62%   |
| MSI MS-7885                              | 1         | 0.62%   |
| MSI MS-7788                              | 1         | 0.62%   |
| MSI MS-7693                              | 1         | 0.62%   |
| MSI MS-7529                              | 1         | 0.62%   |
| MSI MS-7365                              | 1         | 0.62%   |
| MSI Modern 14 B11MO                      | 1         | 0.62%   |
| MSI Modern 14 B10MW                      | 1         | 0.62%   |
| MSI GP76 Leopard 11UG                    | 1         | 0.62%   |
| MSI GL73 8RC                             | 1         | 0.62%   |
| MSI GE76 Raider 11UE                     | 1         | 0.62%   |
| Microsoft Surface Go 3                   | 1         | 0.62%   |
| Lenovo ThinkPad X230 2325P38             | 1         | 0.62%   |
| Lenovo ThinkPad X140e 20BMS03E00         | 1         | 0.62%   |
| Lenovo ThinkPad X1 Carbon 7th 20R10015US | 1         | 0.62%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS04300 | 1         | 0.62%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS2FT00 | 1         | 0.62%   |
| Lenovo ThinkPad T61 765912G              | 1         | 0.62%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 16        | 9.94%   |
| ASUS PRIME        | 6         | 3.73%   |
| Dell Precision    | 5         | 3.11%   |
| HP Pavilion       | 4         | 2.48%   |
| HP Laptop         | 4         | 2.48%   |
| ASUS ROG          | 4         | 2.48%   |
| ASUS All          | 4         | 2.48%   |
| Toshiba Satellite | 3         | 1.86%   |
| Lenovo IdeaPad    | 3         | 1.86%   |
| HP EliteBook      | 3         | 1.86%   |
| Dell Latitude     | 3         | 1.86%   |
| ASUS VivoBook     | 3         | 1.86%   |
| MSI Modern        | 2         | 1.24%   |
| Lenovo V330-14ARR | 2         | 1.24%   |
| HP OMEN           | 2         | 1.24%   |
| Fujitsu LIFEBOOK  | 2         | 1.24%   |
| Dell Vostro       | 2         | 1.24%   |
| Dell PowerEdge    | 2         | 1.24%   |
| Dell OptiPlex     | 2         | 1.24%   |
| ASUS TUF          | 2         | 1.24%   |
| ASRock N68-S3     | 2         | 1.24%   |
| Acer Swift        | 2         | 1.24%   |
| Acer Aspire       | 2         | 1.24%   |
| Unknown           | 2         | 1.24%   |
| Valve Jupiter     | 1         | 0.62%   |
| TYAN S7012        | 1         | 0.62%   |
| Toshiba PORTEGE   | 1         | 0.62%   |
| System76 Oryx     | 1         | 0.62%   |
| Supermicro X9DA7  | 1         | 0.62%   |
| Sony SVE1713A1EW  | 1         | 0.62%   |
| Shuttle NC03U     | 1         | 0.62%   |
| Samsung 300E5M    | 1         | 0.62%   |
| Radxa ROCK        | 1         | 0.62%   |
| Notebook X170KM-G | 1         | 0.62%   |
| Notebook P7xxTM   | 1         | 0.62%   |
| Notebook NL40     | 1         | 0.62%   |
| NetGear ReadyDATA | 1         | 0.62%   |
| MSI MS-7C52       | 1         | 0.62%   |
| MSI MS-7C02       | 1         | 0.62%   |
| MSI MS-7996       | 1         | 0.62%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 18        | 11.18%  |
| 2019    | 17        | 10.56%  |
| 2017    | 14        | 8.7%    |
| 2012    | 13        | 8.07%   |
| 2021    | 12        | 7.45%   |
| 2015    | 12        | 7.45%   |
| 2018    | 11        | 6.83%   |
| 2014    | 10        | 6.21%   |
| 2011    | 9         | 5.59%   |
| 2022    | 8         | 4.97%   |
| 2016    | 8         | 4.97%   |
| 2008    | 7         | 4.35%   |
| 2010    | 6         | 3.73%   |
| 2007    | 5         | 3.11%   |
| 2013    | 4         | 2.48%   |
| 2009    | 4         | 2.48%   |
| Unknown | 2         | 1.24%   |
| 2023    | 1         | 0.62%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 78        | 48.45%  |
| Desktop        | 72        | 44.72%  |
| Mini pc        | 3         | 1.86%   |
| Server         | 3         | 1.86%   |
| System on chip | 2         | 1.24%   |
| All in one     | 2         | 1.24%   |
| Tablet         | 1         | 0.62%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 161       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 158       | 98.14%  |
| Yes  | 3         | 1.86%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 34        | 20.86%  |
| 8.01-16.0   | 34        | 20.86%  |
| 4.01-8.0    | 29        | 17.79%  |
| 3.01-4.0    | 24        | 14.72%  |
| 32.01-64.0  | 17        | 10.43%  |
| 64.01-256.0 | 12        | 7.36%   |
| 24.01-32.0  | 7         | 4.29%   |
| 1.01-2.0    | 5         | 3.07%   |
| 0.51-1.0    | 1         | 0.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 48        | 28.4%   |
| 2.01-3.0    | 40        | 23.67%  |
| 4.01-8.0    | 30        | 17.75%  |
| 3.01-4.0    | 18        | 10.65%  |
| 0.51-1.0    | 13        | 7.69%   |
| 8.01-16.0   | 6         | 3.55%   |
| 0.01-0.5    | 6         | 3.55%   |
| 16.01-24.0  | 4         | 2.37%   |
| 24.01-32.0  | 2         | 1.18%   |
| 32.01-64.0  | 1         | 0.59%   |
| 64.01-256.0 | 1         | 0.59%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 79        | 47.59%  |
| 2      | 38        | 22.89%  |
| 3      | 18        | 10.84%  |
| 4      | 11        | 6.63%   |
| 6      | 6         | 3.61%   |
| 5      | 5         | 3.01%   |
| 0      | 3         | 1.81%   |
| 14     | 1         | 0.6%    |
| 13     | 1         | 0.6%    |
| 11     | 1         | 0.6%    |
| 9      | 1         | 0.6%    |
| 8      | 1         | 0.6%    |
| 7      | 1         | 0.6%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 101       | 62.35%  |
| Yes       | 61        | 37.65%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 148       | 91.93%  |
| No        | 13        | 8.07%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 111       | 68.94%  |
| No        | 50        | 31.06%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 98        | 60.87%  |
| No        | 63        | 39.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 34        | 21.12%  |
| UK           | 14        | 8.7%    |
| Italy        | 10        | 6.21%   |
| Germany      | 10        | 6.21%   |
| Brazil       | 10        | 6.21%   |
| Portugal     | 8         | 4.97%   |
| Russia       | 7         | 4.35%   |
| Japan        | 7         | 4.35%   |
| Kazakhstan   | 6         | 3.73%   |
| India        | 6         | 3.73%   |
| France       | 6         | 3.73%   |
| Canada       | 6         | 3.73%   |
| Sweden       | 4         | 2.48%   |
| Spain        | 4         | 2.48%   |
| South Africa | 3         | 1.86%   |
| Hong Kong    | 3         | 1.86%   |
| Greece       | 3         | 1.86%   |
| Serbia       | 2         | 1.24%   |
| Poland       | 2         | 1.24%   |
| China        | 2         | 1.24%   |
| Chile        | 2         | 1.24%   |
| Australia    | 2         | 1.24%   |
| Argentina    | 2         | 1.24%   |
| Switzerland  | 1         | 0.62%   |
| Romania      | 1         | 0.62%   |
| Philippines  | 1         | 0.62%   |
| Netherlands  | 1         | 0.62%   |
| Mexico       | 1         | 0.62%   |
| Iran         | 1         | 0.62%   |
| Finland      | 1         | 0.62%   |
| Bulgaria     | 1         | 0.62%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Lisbon                 | 6         | 3.61%   |
| Ust-Kamenogorsk        | 4         | 2.41%   |
| Tsukuba                | 4         | 2.41%   |
| Yekaterinburg          | 3         | 1.81%   |
| Paris                  | 3         | 1.81%   |
| Milan                  | 3         | 1.81%   |
| Chania                 | 3         | 1.81%   |
| Warsaw                 | 2         | 1.2%    |
| Tendo                  | 2         | 1.2%    |
| Sun Prairie            | 2         | 1.2%    |
| Springfield            | 2         | 1.2%    |
| Rome                   | 2         | 1.2%    |
| New Delhi              | 2         | 1.2%    |
| Moscow                 | 2         | 1.2%    |
| McKinney               | 2         | 1.2%    |
| Karaganda              | 2         | 1.2%    |
| Greater Noida          | 2         | 1.2%    |
| Frignano               | 2         | 1.2%    |
| Fayetteville           | 2         | 1.2%    |
| Carrollton             | 2         | 1.2%    |
| Cape Town              | 2         | 1.2%    |
| Belgrade               | 2         | 1.2%    |
| Barry                  | 2         | 1.2%    |
| Barrie                 | 2         | 1.2%    |
| Worpswede              | 1         | 0.6%    |
| Wokingham              | 1         | 0.6%    |
| Winter Springs         | 1         | 0.6%    |
| Winnipeg               | 1         | 0.6%    |
| Weilheim               | 1         | 0.6%    |
| Voskresensk            | 1         | 0.6%    |
| Visconde do Rio Branco | 1         | 0.6%    |
| Villa Carlos Paz       | 1         | 0.6%    |
| Toronto                | 1         | 0.6%    |
| Tiffin                 | 1         | 0.6%    |
| Tehran                 | 1         | 0.6%    |
| Tatuí                 | 1         | 0.6%    |
| Stockholm              | 1         | 0.6%    |
| St Petersburg          | 1         | 0.6%    |
| St Louis               | 1         | 0.6%    |
| Southend-on-Sea        | 1         | 0.6%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 48        | 102    | 18.46%  |
| Samsung Electronics         | 44        | 64     | 16.92%  |
| Seagate                     | 39        | 70     | 15%     |
| Toshiba                     | 19        | 36     | 7.31%   |
| Kingston                    | 15        | 18     | 5.77%   |
| Crucial                     | 10        | 12     | 3.85%   |
| Intel                       | 9         | 10     | 3.46%   |
| Hitachi                     | 8         | 11     | 3.08%   |
| SanDisk                     | 6         | 8      | 2.31%   |
| HGST                        | 6         | 6      | 2.31%   |
| Unknown                     | 5         | 6      | 1.92%   |
| SK hynix                    | 5         | 5      | 1.92%   |
| A-DATA Technology           | 4         | 4      | 1.54%   |
| Transcend                   | 3         | 3      | 1.15%   |
| Micron Technology           | 3         | 3      | 1.15%   |
| KIOXIA                      | 3         | 3      | 1.15%   |
| Hewlett-Packard             | 3         | 4      | 1.15%   |
| Gigabyte Technology         | 3         | 3      | 1.15%   |
| Patriot                     | 2         | 3      | 0.77%   |
| Maxtor                      | 2         | 2      | 0.77%   |
| External                    | 2         | 2      | 0.77%   |
| China                       | 2         | 3      | 0.77%   |
| Apple                       | 2         | 3      | 0.77%   |
| ZHITAI                      | 1         | 2      | 0.38%   |
| TO Exter                    | 1         | 1      | 0.38%   |
| Team                        | 1         | 1      | 0.38%   |
| Silicon Motion              | 1         | 1      | 0.38%   |
| PNY                         | 1         | 1      | 0.38%   |
| Plextor                     | 1         | 1      | 0.38%   |
| Phison Electronics          | 1         | 1      | 0.38%   |
| Netac                       | 1         | 1      | 0.38%   |
| Micron/Crucial Technology   | 1         | 1      | 0.38%   |
| Lexar                       | 1         | 1      | 0.38%   |
| Kingston Technology Company | 1         | 1      | 0.38%   |
| JMicron Technology          | 1         | 1      | 0.38%   |
| Intenso                     | 1         | 1      | 0.38%   |
| GOODRAM                     | 1         | 1      | 0.38%   |
| Fujitsu                     | 1         | 1      | 0.38%   |
| DUEX                        | 1         | 1      | 0.38%   |
| Dogfish                     | 1         | 1      | 0.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD  | 7         | 2.19%   |
| WDC WD20EFRX-68EUZN0 2TB         | 3         | 0.94%   |
| WDC WD1003FZEX-00MK2A0 1TB       | 3         | 0.94%   |
| Seagate ST2000DM008-2FR102 2TB   | 3         | 0.94%   |
| Samsung SSD 970 EVO 250GB        | 3         | 0.94%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 2         | 0.63%   |
| WDC WD40EZRX-00SPEB0 4TB         | 2         | 0.63%   |
| WDC WD30EZRX-00SPEB0 3TB         | 2         | 0.63%   |
| WDC WD10SPZX-60Z10T0 1TB         | 2         | 0.63%   |
| WDC WD10EZEX-08WN4A0 1TB         | 2         | 0.63%   |
| WDC WD10EZEX-00RKKA0 1TB         | 2         | 0.63%   |
| Toshiba MQ04ABF100 1TB           | 2         | 0.63%   |
| Toshiba MQ01ABD100 1TB           | 2         | 0.63%   |
| Toshiba HDWD110 1TB              | 2         | 0.63%   |
| Seagate ST500DM002-1BD142 500GB  | 2         | 0.63%   |
| Seagate ST4000VN008-2DR166 4TB   | 2         | 0.63%   |
| Seagate ST4000DM004-2CV104 4TB   | 2         | 0.63%   |
| Seagate ST31000524AS 1TB         | 2         | 0.63%   |
| Seagate ST2000DM001-1CH164 2TB   | 2         | 0.63%   |
| Seagate ST2000DL003-9VT166 2TB   | 2         | 0.63%   |
| Seagate ST1000LM048-2E7172 1TB   | 2         | 0.63%   |
| Seagate ST1000DM010-2EP102 1TB   | 2         | 0.63%   |
| Seagate ST1000DM003-1SB102 1TB   | 2         | 0.63%   |
| Seagate ST1000DM003-1ER162 1TB   | 2         | 0.63%   |
| Seagate Expansion Desk 3TB       | 2         | 0.63%   |
| Samsung SSD 970 EVO Plus 500GB   | 2         | 0.63%   |
| Samsung SSD 970 EVO Plus 1TB     | 2         | 0.63%   |
| Samsung SSD 860 QVO 2TB          | 2         | 0.63%   |
| Samsung SSD 850 PRO 256GB        | 2         | 0.63%   |
| Kingston SA400S37120G 120GB SSD  | 2         | 0.63%   |
| Intel SSD 660P Series 1024GB     | 2         | 0.63%   |
| HGST HTS725050A7E630 500GB       | 2         | 0.63%   |
| External USB3.0 2TB              | 2         | 0.63%   |
| Crucial CT500MX500SSD1 500GB     | 2         | 0.63%   |
| ZHITAI SC001 Active 1TB SSD      | 1         | 0.31%   |
| ZHITAI PC005 Active 512GB        | 1         | 0.31%   |
| WDC WDS500G2B0B-00YS70 500GB SSD | 1         | 0.31%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1         | 0.31%   |
| WDC WDS480G2G0A-00JH30 480GB SSD | 1         | 0.31%   |
| WDC WDS100T2B0C-00PXH0 1TB       | 1         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 41        | 91     | 33.61%  |
| Seagate             | 39        | 66     | 31.97%  |
| Toshiba             | 18        | 31     | 14.75%  |
| Hitachi             | 8         | 11     | 6.56%   |
| HGST                | 6         | 6      | 4.92%   |
| Samsung Electronics | 4         | 4      | 3.28%   |
| Maxtor              | 2         | 2      | 1.64%   |
| External            | 2         | 2      | 1.64%   |
| Hewlett-Packard     | 1         | 1      | 0.82%   |
| Fujitsu             | 1         | 1      | 0.82%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 21        | 31     | 26.25%  |
| Kingston            | 14        | 17     | 17.5%   |
| Crucial             | 8         | 10     | 10%     |
| WDC                 | 5         | 7      | 6.25%   |
| SanDisk             | 4         | 4      | 5%      |
| Transcend           | 2         | 2      | 2.5%    |
| Patriot             | 2         | 3      | 2.5%    |
| Intel               | 2         | 3      | 2.5%    |
| China               | 2         | 3      | 2.5%    |
| Apple               | 2         | 3      | 2.5%    |
| A-DATA Technology   | 2         | 2      | 2.5%    |
| ZHITAI              | 1         | 1      | 1.25%   |
| Toshiba             | 1         | 3      | 1.25%   |
| TO Exter            | 1         | 1      | 1.25%   |
| Team                | 1         | 1      | 1.25%   |
| SK hynix            | 1         | 1      | 1.25%   |
| PNY                 | 1         | 1      | 1.25%   |
| Plextor             | 1         | 1      | 1.25%   |
| Netac               | 1         | 1      | 1.25%   |
| Micron Technology   | 1         | 1      | 1.25%   |
| Lexar               | 1         | 1      | 1.25%   |
| Intenso             | 1         | 1      | 1.25%   |
| Hewlett-Packard     | 1         | 1      | 1.25%   |
| GOODRAM             | 1         | 1      | 1.25%   |
| Gigabyte Technology | 1         | 1      | 1.25%   |
| DUEX                | 1         | 1      | 1.25%   |
| Dogfish             | 1         | 1      | 1.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 88        | 215    | 38.94%  |
| SSD     | 74        | 103    | 32.74%  |
| NVMe    | 58        | 71     | 25.66%  |
| MMC     | 5         | 6      | 2.21%   |
| Unknown | 1         | 4      | 0.44%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 120       | 307    | 62.83%  |
| NVMe | 57        | 70     | 29.84%  |
| SAS  | 9         | 16     | 4.71%   |
| MMC  | 5         | 6      | 2.62%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 89        | 128    | 47.09%  |
| 0.51-1.0   | 47        | 89     | 24.87%  |
| 1.01-2.0   | 23        | 30     | 12.17%  |
| 3.01-4.0   | 13        | 27     | 6.88%   |
| 2.01-3.0   | 10        | 21     | 5.29%   |
| 4.01-10.0  | 5         | 18     | 2.65%   |
| 10.01-20.0 | 2         | 5      | 1.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 39        | 23.49%  |
| 501-1000       | 36        | 21.69%  |
| 251-500        | 25        | 15.06%  |
| Unknown        | 18        | 10.84%  |
| 1001-2000      | 17        | 10.24%  |
| 2001-3000      | 9         | 5.42%   |
| 1-20           | 9         | 5.42%   |
| More than 3000 | 6         | 3.61%   |
| 51-100         | 4         | 2.41%   |
| 21-50          | 3         | 1.81%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 32        | 18.93%  |
| 1-20           | 27        | 15.98%  |
| 21-50          | 23        | 13.61%  |
| 501-1000       | 21        | 12.43%  |
| 251-500        | 18        | 10.65%  |
| 51-100         | 18        | 10.65%  |
| Unknown        | 18        | 10.65%  |
| 1001-2000      | 8         | 4.73%   |
| More than 3000 | 4         | 2.37%   |

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
| Works    | 128       | 278    | 65.98%  |
| Malfunc  | 35        | 53     | 18.04%  |
| Detected | 31        | 68     | 15.98%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 97        | 44.5%   |
| AMD                          | 39        | 17.89%  |
| Samsung Electronics          | 24        | 11.01%  |
| Marvell Technology Group     | 7         | 3.21%   |
| SanDisk                      | 6         | 2.75%   |
| ASMedia Technology           | 6         | 2.75%   |
| Nvidia                       | 5         | 2.29%   |
| SK hynix                     | 4         | 1.83%   |
| JMicron Technology           | 4         | 1.83%   |
| Micron/Crucial Technology    | 3         | 1.38%   |
| KIOXIA                       | 3         | 1.38%   |
| Broadcom / LSI               | 3         | 1.38%   |
| Realtek Semiconductor        | 2         | 0.92%   |
| Phison Electronics           | 2         | 0.92%   |
| Micron Technology            | 2         | 0.92%   |
| LSI Logic / Symbios Logic    | 2         | 0.92%   |
| Kingston Technology Company  | 2         | 0.92%   |
| Yangtze Memory Technologies  | 1         | 0.46%   |
| Toshiba America Info Systems | 1         | 0.46%   |
| Silicon Motion               | 1         | 0.46%   |
| Silicon Image                | 1         | 0.46%   |
| Biwin Storage Technology     | 1         | 0.46%   |
| Adaptec                      | 1         | 0.46%   |
| 3ware                        | 1         | 0.46%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 28        | 10.57%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 13        | 4.91%   |
| AMD 400 Series Chipset SATA Controller                                           | 10        | 3.77%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 7         | 2.64%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 6         | 2.26%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 2.26%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 6         | 2.26%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 5         | 1.89%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 5         | 1.89%   |
| Nvidia MCP61 SATA Controller                                                     | 4         | 1.51%   |
| Nvidia MCP61 IDE                                                                 | 4         | 1.51%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 1.51%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 1.51%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 1.51%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 4         | 1.51%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 1.13%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 3         | 1.13%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 3         | 1.13%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 3         | 1.13%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 1.13%   |
| Intel SSD 660P Series                                                            | 3         | 1.13%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 1.13%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 3         | 1.13%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 3         | 1.13%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 3         | 1.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 1.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 1.13%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.13%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 3         | 1.13%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 2         | 0.75%   |
| SK hynix BC511 NVMe SSD                                                          | 2         | 0.75%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 2         | 0.75%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                | 2         | 0.75%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 2         | 0.75%   |
| JMicron JMB58x AHCI SATA controller                                              | 2         | 0.75%   |
| Intel SSD 600P Series                                                            | 2         | 0.75%   |
| Intel SATA Controller [RAID mode]                                                | 2         | 0.75%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2         | 0.75%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                              | 2         | 0.75%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 2         | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 115       | 52.75%  |
| NVMe | 56        | 25.69%  |
| IDE  | 24        | 11.01%  |
| RAID | 16        | 7.34%   |
| SAS  | 4         | 1.83%   |
| SCSI | 3         | 1.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 112       | 69.57%  |
| AMD    | 47        | 29.19%  |
| ARM    | 2         | 1.24%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 4         | 2.47%   |
| AMD Ryzen 5 3600 6-Core Processor             | 4         | 2.47%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 1.85%   |
| Intel 12th Gen Core i7-12700H                 | 3         | 1.85%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 3         | 1.85%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz            | 2         | 1.23%   |
| Intel Core i7-5820K CPU @ 3.30GHz             | 2         | 1.23%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 2         | 1.23%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.23%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.23%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1.23%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 2         | 1.23%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 2         | 1.23%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 1.23%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.23%   |
| ARM Processor                                 | 2         | 1.23%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 2         | 1.23%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 2         | 1.23%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 2         | 1.23%   |
| AMD FX-8350 Eight-Core Processor              | 2         | 1.23%   |
| AMD Athlon II X2 250 Processor                | 2         | 1.23%   |
| Intel Xeon CPU X5680 @ 3.33GHz                | 1         | 0.62%   |
| Intel Xeon CPU X5355 @ 2.66GHz                | 1         | 0.62%   |
| Intel Xeon CPU X3450 @ 2.67GHz                | 1         | 0.62%   |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz           | 1         | 0.62%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz           | 1         | 0.62%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz           | 1         | 0.62%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz            | 1         | 0.62%   |
| Intel Xeon CPU E5-2407 0 @ 2.20GHz            | 1         | 0.62%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz            | 1         | 0.62%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz           | 1         | 0.62%   |
| Intel Xeon CPU 5160 @ 3.00GHz                 | 1         | 0.62%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 0.62%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz        | 1         | 0.62%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz        | 1         | 0.62%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 1         | 0.62%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.62%   |
| Intel Pentium CPU GOLD 6500Y @ 1.10GHz        | 1         | 0.62%   |
| Intel Pentium CPU G640 @ 2.80GHz              | 1         | 0.62%   |
| Intel Pentium CPU G4560 @ 3.50GHz             | 1         | 0.62%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 28        | 17.28%  |
| Intel Core i7        | 24        | 14.81%  |
| Other                | 17        | 10.49%  |
| AMD Ryzen 5          | 15        | 9.26%   |
| Intel Xeon           | 13        | 8.02%   |
| Intel Core i3        | 8         | 4.94%   |
| Intel Pentium        | 7         | 4.32%   |
| AMD Ryzen 7          | 7         | 4.32%   |
| Intel Core 2 Duo     | 6         | 3.7%    |
| AMD Ryzen 9          | 6         | 3.7%    |
| AMD FX               | 5         | 3.09%   |
| Intel Celeron        | 4         | 2.47%   |
| Intel Core 2 Quad    | 2         | 1.23%   |
| Intel Atom           | 2         | 1.23%   |
| AMD Athlon II X2     | 2         | 1.23%   |
| Intel Pentium Silver | 1         | 0.62%   |
| Intel Pentium Gold   | 1         | 0.62%   |
| Intel Pentium Dual   | 1         | 0.62%   |
| Intel Core M         | 1         | 0.62%   |
| Intel Core 2         | 1         | 0.62%   |
| AMD Ryzen Embedded   | 1         | 0.62%   |
| AMD Ryzen 7 PRO      | 1         | 0.62%   |
| AMD Ryzen 3          | 1         | 0.62%   |
| AMD GX               | 1         | 0.62%   |
| AMD EPYC             | 1         | 0.62%   |
| AMD E1               | 1         | 0.62%   |
| AMD Athlon 64 X2     | 1         | 0.62%   |
| AMD Athlon           | 1         | 0.62%   |
| AMD A8               | 1         | 0.62%   |
| AMD A4               | 1         | 0.62%   |
| AMD A10              | 1         | 0.62%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 54        | 33.33%  |
| 4      | 52        | 32.1%   |
| 8      | 19        | 11.73%  |
| 6      | 17        | 10.49%  |
| 16     | 5         | 3.09%   |
| 14     | 4         | 2.47%   |
| 12     | 4         | 2.47%   |
| 10     | 3         | 1.85%   |
| 1      | 3         | 1.85%   |
| 3      | 1         | 0.62%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 153       | 95.03%  |
| 2      | 8         | 4.97%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 118       | 73.29%  |
| 1      | 43        | 26.71%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 158       | 98.14%  |
| Unknown        | 2         | 1.24%   |
| 32-bit         | 1         | 0.62%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 37        | 22.84%  |
| 0x306a9    | 9         | 5.56%   |
| 0x306c3    | 6         | 3.7%    |
| 0x206d7    | 5         | 3.09%   |
| 0x08108109 | 5         | 3.09%   |
| 0x906a3    | 4         | 2.47%   |
| 0x806d1    | 4         | 2.47%   |
| 0x406e3    | 4         | 2.47%   |
| 0x306d4    | 4         | 2.47%   |
| 0x20655    | 4         | 2.47%   |
| 0x1067a    | 4         | 2.47%   |
| 0x08701021 | 4         | 2.47%   |
| 0x906ea    | 3         | 1.85%   |
| 0x806ec    | 3         | 1.85%   |
| 0x806ea    | 3         | 1.85%   |
| 0x806c1    | 3         | 1.85%   |
| 0x406c4    | 3         | 1.85%   |
| 0x306f2    | 3         | 1.85%   |
| 0x206a7    | 3         | 1.85%   |
| 0x08701013 | 3         | 1.85%   |
| 0x906ed    | 2         | 1.23%   |
| 0x6fd      | 2         | 1.23%   |
| 0x506e3    | 2         | 1.23%   |
| 0x106c2    | 2         | 1.23%   |
| 0x0a50000c | 2         | 1.23%   |
| 0x0a201016 | 2         | 1.23%   |
| 0x08600106 | 2         | 1.23%   |
| 0x0810100b | 2         | 1.23%   |
| 0x06001119 | 2         | 1.23%   |
| 0x06000822 | 2         | 1.23%   |
| 0xa0671    | 1         | 0.62%   |
| 0xa0660    | 1         | 0.62%   |
| 0xa0653    | 1         | 0.62%   |
| 0xa0652    | 1         | 0.62%   |
| 0x906e9    | 1         | 0.62%   |
| 0x906c0    | 1         | 0.62%   |
| 0x906a4    | 1         | 0.62%   |
| 0x806e9    | 1         | 0.62%   |
| 0x706a1    | 1         | 0.62%   |
| 0x6fb      | 1         | 0.62%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 21        | 12.96%  |
| Haswell          | 14        | 8.64%   |
| Zen 2            | 13        | 8.02%   |
| SandyBridge      | 10        | 6.17%   |
| IvyBridge        | 10        | 6.17%   |
| Skylake          | 8         | 4.94%   |
| Core             | 8         | 4.94%   |
| Zen+             | 7         | 4.32%   |
| Westmere         | 7         | 4.32%   |
| Zen 3            | 6         | 3.7%    |
| Zen              | 6         | 3.7%    |
| Piledriver       | 6         | 3.7%    |
| Penryn           | 5         | 3.09%   |
| Icelake          | 5         | 3.09%   |
| Alderlake Hybrid | 5         | 3.09%   |
| Unknown          | 5         | 3.09%   |
| Silvermont       | 4         | 2.47%   |
| Broadwell        | 4         | 2.47%   |
| TigerLake        | 3         | 1.85%   |
| CometLake        | 3         | 1.85%   |
| K10              | 2         | 1.23%   |
| Jaguar           | 2         | 1.23%   |
| Bonnell          | 2         | 1.23%   |
| Tremont          | 1         | 0.62%   |
| Puma             | 1         | 0.62%   |
| Nehalem          | 1         | 0.62%   |
| K8 Hammer        | 1         | 0.62%   |
| Goldmont plus    | 1         | 0.62%   |
| Bulldozer        | 1         | 0.62%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 74        | 41.81%  |
| Nvidia                     | 53        | 29.94%  |
| AMD                        | 46        | 25.99%  |
| Matrox Electronics Systems | 4         | 2.26%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 3.83%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 3.28%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6         | 3.28%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 4         | 2.19%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 2.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 2.19%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 2.19%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 2.19%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 3         | 1.64%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 3         | 1.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 1.64%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.64%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.64%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 1.64%   |
| Intel HD Graphics 620                                                                    | 3         | 1.64%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.64%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.64%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 3         | 1.64%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.64%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 1.64%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 1.64%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 3         | 1.64%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 1.09%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 1.09%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 1.09%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2         | 1.09%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2         | 1.09%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2         | 1.09%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 1.09%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 2         | 1.09%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.09%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.09%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.09%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 1.09%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 1.09%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.09%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 1.09%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 2         | 1.09%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 1.09%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 58        | 36.02%  |
| 1 x AMD        | 43        | 26.71%  |
| 1 x Nvidia     | 34        | 21.12%  |
| Intel + Nvidia | 15        | 9.32%   |
| 1 x Matrox     | 4         | 2.48%   |
| Other          | 3         | 1.86%   |
| AMD + Nvidia   | 2         | 1.24%   |
| 2 x Nvidia     | 1         | 0.62%   |
| 2 x AMD        | 1         | 0.62%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 123       | 75.93%  |
| Proprietary | 27        | 16.67%  |
| Unknown     | 12        | 7.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 86        | 52.76%  |
| 1.01-2.0   | 16        | 9.82%   |
| 0.51-1.0   | 16        | 9.82%   |
| 0.01-0.5   | 13        | 7.98%   |
| 3.01-4.0   | 11        | 6.75%   |
| 7.01-8.0   | 10        | 6.13%   |
| 5.01-6.0   | 5         | 3.07%   |
| 8.01-16.0  | 4         | 2.45%   |
| 2.01-3.0   | 1         | 0.61%   |
| 16.01-24.0 | 1         | 0.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 18        | 10.78%  |
| BOE                     | 17        | 10.18%  |
| Chimei Innolux          | 15        | 8.98%   |
| AU Optronics            | 14        | 8.38%   |
| LG Display              | 13        | 7.78%   |
| Dell                    | 12        | 7.19%   |
| Hewlett-Packard         | 11        | 6.59%   |
| BenQ                    | 9         | 5.39%   |
| Goldstar                | 8         | 4.79%   |
| Lenovo                  | 5         | 2.99%   |
| Sharp                   | 4         | 2.4%    |
| Ancor Communications    | 4         | 2.4%    |
| Acer                    | 4         | 2.4%    |
| ASUSTek Computer        | 3         | 1.8%    |
| AOC                     | 3         | 1.8%    |
| ViewSonic               | 2         | 1.2%    |
| Iiyama                  | 2         | 1.2%    |
| Xiaomi                  | 1         | 0.6%    |
| Wacom                   | 1         | 0.6%    |
| Valve                   | 1         | 0.6%    |
| Unknown                 | 1         | 0.6%    |
| UGD                     | 1         | 0.6%    |
| Toshiba                 | 1         | 0.6%    |
| Sony                    | 1         | 0.6%    |
| PANDA                   | 1         | 0.6%    |
| Panasonic               | 1         | 0.6%    |
| ONN                     | 1         | 0.6%    |
| NEC Computers           | 1         | 0.6%    |
| JVC                     | 1         | 0.6%    |
| IOD                     | 1         | 0.6%    |
| Hyundai ImageQuest      | 1         | 0.6%    |
| HKC                     | 1         | 0.6%    |
| Gigabyte Technology     | 1         | 0.6%    |
| GDH                     | 1         | 0.6%    |
| Eizo                    | 1         | 0.6%    |
| DPC                     | 1         | 0.6%    |
| CTC                     | 1         | 0.6%    |
| Chi Mei Optoelectronics | 1         | 0.6%    |
| Apple                   | 1         | 0.6%    |
| Unknown                 | 1         | 0.6%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 3         | 1.75%   |
| Samsung Electronics LCD Monitor SDC416E 2880x1620 344x194mm 15.5-inch | 2         | 1.17%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 2         | 1.17%   |
| LG Display LCD Monitor LGD0353 1366x768 345x194mm 15.6-inch           | 2         | 1.17%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x189mm 14.1-inch               | 2         | 1.17%   |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch             | 2         | 1.17%   |
| Goldstar ULTRAGEAR GSM7765 2560x1440 697x392mm 31.5-inch              | 2         | 1.17%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 2         | 1.17%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 2         | 1.17%   |
| Xiaomi DPF90435 XMD009A 2224x1668 341x192mm 15.4-inch                 | 1         | 0.58%   |
| Wacom Cintiq 22HDT WAC1037 1920x1080 476x268mm 21.5-inch              | 1         | 0.58%   |
| ViewSonic LCD Monitor VX2276 Series 1920x1080                         | 1         | 0.58%   |
| ViewSonic LCD Monitor VA2448 SERIES 1920x1080                         | 1         | 0.58%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 0.58%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1         | 0.58%   |
| UGD LCD Monitor UGD1302 1920x1080 290x160mm 13.0-inch                 | 1         | 0.58%   |
| Toshiba TSB-TV TSB0206 1360x768 930x520mm 41.9-inch                   | 1         | 0.58%   |
| Sony TV SNY8102 1360x768                                              | 1         | 0.58%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 382x215mm 17.3-inch               | 1         | 0.58%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 0.58%   |
| Sharp LQ125T1JW02 SHP142F 2560x1440 277x155mm 12.5-inch               | 1         | 0.58%   |
| Sharp LCD Monitor SHP14C4 1920x1080 344x194mm 15.5-inch               | 1         | 0.58%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch     | 1         | 0.58%   |
| Samsung Electronics SyncMaster SAM0578 1920x1080 476x268mm 21.5-inch  | 1         | 0.58%   |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch   | 1         | 0.58%   |
| Samsung Electronics SyncMaster SAM0428 1680x1050 459x296mm 21.5-inch  | 1         | 0.58%   |
| Samsung Electronics SyncMaster SAM03F2 1680x1050                      | 1         | 0.58%   |
| Samsung Electronics SyncMaster SAM03F0 1680x1050 433x271mm 20.1-inch  | 1         | 0.58%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 376x301mm 19.0-inch  | 1         | 0.58%   |
| Samsung Electronics SyncMaster SAM01AD 1600x1200 408x306mm 20.1-inch  | 1         | 0.58%   |
| Samsung Electronics SMS27A650 SAM082D 1920x1080 598x336mm 27.0-inch   | 1         | 0.58%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch    | 1         | 0.58%   |
| Samsung Electronics SM2333T SAM0736 1920x1080 477x268mm 21.5-inch     | 1         | 0.58%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 521x293mm 23.5-inch     | 1         | 0.58%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch     | 1         | 0.58%   |
| Samsung Electronics LCD Monitor U28D590 3840x2160                     | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 0.58%   |
| Samsung Electronics B2430L SAM0644 1920x1080 521x293mm 23.5-inch      | 1         | 0.58%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 75        | 45.73%  |
| 1366x768 (WXGA)    | 27        | 16.46%  |
| 3840x2160 (4K)     | 9         | 5.49%   |
| 2560x1440 (QHD)    | 8         | 4.88%   |
| 1280x1024 (SXGA)   | 8         | 4.88%   |
| 1680x1050 (WSXGA+) | 7         | 4.27%   |
| 1920x1200 (WUXGA)  | 5         | 3.05%   |
| 1600x900 (HD+)     | 4         | 2.44%   |
| 1280x800 (WXGA)    | 4         | 2.44%   |
| 3440x1440          | 2         | 1.22%   |
| 2880x1620          | 2         | 1.22%   |
| 1440x900 (WXGA+)   | 2         | 1.22%   |
| 1360x768           | 2         | 1.22%   |
| 800x1280           | 1         | 0.61%   |
| 3200x1080          | 1         | 0.61%   |
| 2288x1287          | 1         | 0.61%   |
| 2256x1504          | 1         | 0.61%   |
| 1920x540           | 1         | 0.61%   |
| 1920x1280          | 1         | 0.61%   |
| 1600x1200          | 1         | 0.61%   |
| 1024x768 (XGA)     | 1         | 0.61%   |
| Unknown            | 1         | 0.61%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 37        | 22.02%  |
| 27      | 15        | 8.93%   |
| 24      | 14        | 8.33%   |
| 14      | 14        | 8.33%   |
| 21      | 13        | 7.74%   |
| 13      | 13        | 7.74%   |
| 17      | 12        | 7.14%   |
| 23      | 9         | 5.36%   |
| Unknown | 7         | 4.17%   |
| 22      | 4         | 2.38%   |
| 20      | 4         | 2.38%   |
| 19      | 4         | 2.38%   |
| 18      | 4         | 2.38%   |
| 31      | 3         | 1.79%   |
| 16      | 3         | 1.79%   |
| 12      | 3         | 1.79%   |
| 142     | 1         | 0.6%    |
| 74      | 1         | 0.6%    |
| 72      | 1         | 0.6%    |
| 52      | 1         | 0.6%    |
| 34      | 1         | 0.6%    |
| 32      | 1         | 0.6%    |
| 11      | 1         | 0.6%    |
| 10      | 1         | 0.6%    |
| 7       | 1         | 0.6%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 66        | 39.52%  |
| 501-600        | 35        | 20.96%  |
| 401-500        | 27        | 16.17%  |
| 351-400        | 13        | 7.78%   |
| 201-300        | 8         | 4.79%   |
| Unknown        | 7         | 4.19%   |
| 601-700        | 4         | 2.4%    |
| 701-800        | 2         | 1.2%    |
| 1501-2000      | 2         | 1.2%    |
| More than 2000 | 1         | 0.6%    |
| 1001-1500      | 1         | 0.6%    |
| 1-100          | 1         | 0.6%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 110       | 72.37%  |
| 16/10   | 19        | 12.5%   |
| 5/4     | 6         | 3.95%   |
| Unknown | 5         | 3.29%   |
| 3/2     | 4         | 2.63%   |
| 6/5     | 2         | 1.32%   |
| 4/3     | 2         | 1.32%   |
| 32/9    | 1         | 0.66%   |
| 21/9    | 1         | 0.66%   |
| 1.00    | 1         | 0.66%   |
| 0.67    | 1         | 0.66%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 39        | 23.49%  |
| 201-250        | 30        | 18.07%  |
| 81-90          | 25        | 15.06%  |
| 301-350        | 15        | 9.04%   |
| 151-200        | 11        | 6.63%   |
| 141-150        | 8         | 4.82%   |
| 121-130        | 7         | 4.22%   |
| Unknown        | 7         | 4.22%   |
| 251-300        | 6         | 3.61%   |
| 351-500        | 5         | 3.01%   |
| More than 1000 | 4         | 2.41%   |
| 61-70          | 3         | 1.81%   |
| 71-80          | 2         | 1.2%    |
| 51-60          | 2         | 1.2%    |
| 1-40           | 1         | 0.6%    |
| 111-120        | 1         | 0.6%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 59        | 35.76%  |
| 121-160       | 44        | 26.67%  |
| 101-120       | 41        | 24.85%  |
| 161-240       | 7         | 4.24%   |
| Unknown       | 7         | 4.24%   |
| 1-50          | 4         | 2.42%   |
| More than 240 | 3         | 1.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 125       | 77.64%  |
| 2     | 19        | 11.8%   |
| 0     | 13        | 8.07%   |
| 3     | 3         | 1.86%   |
| 4     | 1         | 0.62%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 90        | 37.82%  |
| Realtek Semiconductor    | 82        | 34.45%  |
| Qualcomm Atheros         | 16        | 6.72%   |
| Broadcom                 | 11        | 4.62%   |
| Ralink Technology        | 5         | 2.1%    |
| Broadcom Limited         | 5         | 2.1%    |
| ASIX Electronics         | 5         | 2.1%    |
| Nvidia                   | 4         | 1.68%   |
| MediaTek                 | 4         | 1.68%   |
| TP-Link                  | 3         | 1.26%   |
| Dell                     | 2         | 0.84%   |
| VIA Technologies         | 1         | 0.42%   |
| Sitecom Europe           | 1         | 0.42%   |
| Sierra Wireless          | 1         | 0.42%   |
| Ralink                   | 1         | 0.42%   |
| Qualcomm                 | 1         | 0.42%   |
| Micro Star International | 1         | 0.42%   |
| Mellanox Technologies    | 1         | 0.42%   |
| Marvell Technology Group | 1         | 0.42%   |
| Huawei Technologies      | 1         | 0.42%   |
| Hewlett-Packard          | 1         | 0.42%   |
| Chelsio Communications   | 1         | 0.42%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 55        | 19.1%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 3.82%   |
| Intel Wi-Fi 6 AX200                                               | 7         | 2.43%   |
| Intel I211 Gigabit Network Connection                             | 7         | 2.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 2.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 2.08%   |
| Intel Wireless 8265 / 8275                                        | 6         | 2.08%   |
| Ralink MT7601U Wireless Adapter                                   | 5         | 1.74%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5         | 1.74%   |
| Intel 82574L Gigabit Network Connection                           | 5         | 1.74%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 1.39%   |
| Intel Wireless-AC 9260                                            | 4         | 1.39%   |
| Intel Wireless 8260                                               | 4         | 1.39%   |
| Intel Wireless 7260                                               | 4         | 1.39%   |
| Intel Ethernet Connection (2) I218-V                              | 4         | 1.39%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.04%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 3         | 1.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 1.04%   |
| Nvidia MCP61 Ethernet                                             | 3         | 1.04%   |
| Intel Wireless 7265                                               | 3         | 1.04%   |
| Intel I350 Gigabit Network Connection                             | 3         | 1.04%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 1.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 1.04%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 1.04%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 2         | 0.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.69%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.69%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.69%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.69%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 2         | 0.69%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 0.69%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.69%   |
| Intel Wireless 3160                                               | 2         | 0.69%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 0.69%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 0.69%   |
| Intel Ethernet Controller I225-V                                  | 2         | 0.69%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.69%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.69%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.69%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 60        | 52.17%  |
| Realtek Semiconductor    | 20        | 17.39%  |
| Qualcomm Atheros         | 11        | 9.57%   |
| Ralink Technology        | 5         | 4.35%   |
| MediaTek                 | 4         | 3.48%   |
| TP-Link                  | 3         | 2.61%   |
| Broadcom Limited         | 3         | 2.61%   |
| Broadcom                 | 3         | 2.61%   |
| Dell                     | 2         | 1.74%   |
| Sitecom Europe           | 1         | 0.87%   |
| Sierra Wireless          | 1         | 0.87%   |
| Ralink                   | 1         | 0.87%   |
| Micro Star International | 1         | 0.87%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 7         | 6.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6         | 5.17%   |
| Intel Wireless 8265 / 8275                                     | 6         | 5.17%   |
| Ralink MT7601U Wireless Adapter                                | 5         | 4.31%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 5         | 4.31%   |
| Intel Wireless-AC 9260                                         | 4         | 3.45%   |
| Intel Wireless 8260                                            | 4         | 3.45%   |
| Intel Wireless 7260                                            | 4         | 3.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 2.59%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 3         | 2.59%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 3         | 2.59%   |
| Intel Wireless 7265                                            | 3         | 2.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 3         | 2.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 2.59%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 2         | 1.72%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 2         | 1.72%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.72%   |
| Intel Wireless 3160                                            | 2         | 1.72%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 1.72%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 1.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.72%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 1.72%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 1.72%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                        | 2         | 1.72%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 0.86%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                          | 1         | 0.86%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.86%   |
| Sitecom Europe WL-113 rev 2 Wireless Network USB Adapter       | 1         | 0.86%   |
| Sierra Wireless EM7305                                         | 1         | 0.86%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 0.86%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.86%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 0.86%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 0.86%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.86%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.86%   |
| Realtek Realtek WLAN controller                                | 1         | 0.86%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 1         | 0.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 0.86%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 0.86%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 0.86%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 74        | 45.68%  |
| Intel                    | 54        | 33.33%  |
| Broadcom                 | 9         | 5.56%   |
| Qualcomm Atheros         | 8         | 4.94%   |
| ASIX Electronics         | 5         | 3.09%   |
| Nvidia                   | 4         | 2.47%   |
| Broadcom Limited         | 2         | 1.23%   |
| VIA Technologies         | 1         | 0.62%   |
| Qualcomm                 | 1         | 0.62%   |
| Mellanox Technologies    | 1         | 0.62%   |
| Marvell Technology Group | 1         | 0.62%   |
| Huawei Technologies      | 1         | 0.62%   |
| Chelsio Communications   | 1         | 0.62%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 55        | 32.16%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 6.43%   |
| Intel I211 Gigabit Network Connection                             | 7         | 4.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 4.09%   |
| Intel 82574L Gigabit Network Connection                           | 5         | 2.92%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 2.34%   |
| Intel Ethernet Connection (2) I218-V                              | 4         | 2.34%   |
| Nvidia MCP61 Ethernet                                             | 3         | 1.75%   |
| Intel I350 Gigabit Network Connection                             | 3         | 1.75%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.75%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 1.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.17%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 1.17%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.17%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 1.17%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 1.17%   |
| Intel Ethernet Controller I225-V                                  | 2         | 1.17%   |
| Intel Ethernet Connection I217-V                                  | 2         | 1.17%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 1.17%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.17%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.17%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.17%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.17%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.17%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 1.17%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 2         | 1.17%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 2         | 1.17%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 0.58%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.58%   |
| Qualcomm SDM630-MTP _SN:0B9EB96E                                  | 1         | 0.58%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.58%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.58%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]             | 1         | 0.58%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.58%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.58%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 0.58%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.58%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 0.58%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 148       | 56.92%  |
| WiFi     | 111       | 42.69%  |
| Modem    | 1         | 0.38%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 87        | 53.7%   |
| WiFi     | 75        | 46.3%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 86        | 52.76%  |
| 1     | 59        | 36.2%   |
| 3     | 6         | 3.68%   |
| 4     | 5         | 3.07%   |
| 0     | 5         | 3.07%   |
| 5     | 2         | 1.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 142       | 87.12%  |
| Yes  | 21        | 12.88%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 53        | 53.54%  |
| Cambridge Silicon Radio         | 13        | 13.13%  |
| Realtek Semiconductor           | 10        | 10.1%   |
| Broadcom                        | 6         | 6.06%   |
| Qualcomm Atheros Communications | 4         | 4.04%   |
| IMC Networks                    | 4         | 4.04%   |
| Micro Star International        | 2         | 2.02%   |
| MediaTek                        | 2         | 2.02%   |
| Apple                           | 2         | 2.02%   |
| TP-Link                         | 1         | 1.01%   |
| Toshiba                         | 1         | 1.01%   |
| Foxconn / Hon Hai               | 1         | 1.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 21        | 21.21%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 13        | 13.13%  |
| Intel AX201 Bluetooth                               | 8         | 8.08%   |
| Intel AX200 Bluetooth                               | 7         | 7.07%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 5.05%   |
| Realtek Bluetooth Radio                             | 5         | 5.05%   |
| Intel AX210 Bluetooth                               | 5         | 5.05%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 4.04%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 4.04%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 3.03%   |
| IMC Networks Wireless_Device                        | 3         | 3.03%   |
| MediaTek Wireless_Device                            | 2         | 2.02%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 2.02%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 2.02%   |
| TP-Link UB500 Adapter                               | 1         | 1.01%   |
| Toshiba Askey Bluetooth Module                      | 1         | 1.01%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.01%   |
| Micro Star International Bluetooth Dongle           | 1         | 1.01%   |
| Micro Star International Bluetooth Device           | 1         | 1.01%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.01%   |
| Intel Bluetooth Device                              | 1         | 1.01%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.01%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 1.01%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.01%   |
| Broadcom BCM20702A0                                 | 1         | 1.01%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.01%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 1.01%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.01%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 1         | 1.01%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 103       | 47.03%  |
| AMD                    | 51        | 23.29%  |
| Nvidia                 | 43        | 19.63%  |
| Creative Labs          | 7         | 3.2%    |
| C-Media Electronics    | 4         | 1.83%   |
| Texas Instruments      | 2         | 0.91%   |
| ASUSTek Computer       | 2         | 0.91%   |
| VIA Technologies       | 1         | 0.46%   |
| RME                    | 1         | 0.46%   |
| M-Audio                | 1         | 0.46%   |
| Kingston Technology    | 1         | 0.46%   |
| Holtek Semiconductor   | 1         | 0.46%   |
| Generalplus Technology | 1         | 0.46%   |
| EGO SYStems            | 1         | 0.46%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 17        | 6.37%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 13        | 4.87%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 12        | 4.49%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 11        | 4.12%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 3%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 2.62%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 6         | 2.25%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 2.25%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 2.25%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 6         | 2.25%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 5         | 1.87%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 1.87%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 1.87%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 5         | 1.87%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 1.87%   |
| AMD FCH Azalia Controller                                                                         | 5         | 1.87%   |
| Nvidia MCP61 High Definition Audio                                                                | 4         | 1.5%    |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 1.5%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.5%    |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 1.5%    |
| Intel Broadwell-U Audio Controller                                                                | 4         | 1.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.5%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.5%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 4         | 1.5%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.12%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.12%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.12%   |
| Nvidia Audio device                                                                               | 3         | 1.12%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.12%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3         | 1.12%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.12%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.12%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus]   | 3         | 1.12%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.12%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 3         | 1.12%   |
| AMD Navi 10 HDMI Audio                                                                            | 3         | 1.12%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 3         | 1.12%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 2         | 0.75%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 31        | 18.9%   |
| Samsung Electronics | 28        | 17.07%  |
| Kingston            | 25        | 15.24%  |
| Corsair             | 16        | 9.76%   |
| Crucial             | 12        | 7.32%   |
| Unknown             | 10        | 6.1%    |
| Micron Technology   | 9         | 5.49%   |
| Team                | 4         | 2.44%   |
| G.Skill             | 3         | 1.83%   |
| Transcend           | 2         | 1.22%   |
| Smart               | 2         | 1.22%   |
| Ramaxel Technology  | 2         | 1.22%   |
| Goodram             | 2         | 1.22%   |
| AMD                 | 2         | 1.22%   |
| A-DATA Technology   | 2         | 1.22%   |
| Unknown             | 2         | 1.22%   |
| Strontium           | 1         | 0.61%   |
| Silicon Power       | 1         | 0.61%   |
| Patriot             | 1         | 0.61%   |
| Neo Forza           | 1         | 0.61%   |
| Nanya Technology    | 1         | 0.61%   |
| Innodisk            | 1         | 0.61%   |
| HPE                 | 1         | 0.61%   |
| GLOWAY              | 1         | 0.61%   |
| Essencore Limited   | 1         | 0.61%   |
| Elpida              | 1         | 0.61%   |
| Avant               | 1         | 0.61%   |
| A Force             | 1         | 0.61%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.67%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 2         | 1.11%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s              | 2         | 1.11%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.11%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 1.11%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 1.11%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB Row Of Chips LPDDR5 6400MT/s | 2         | 1.11%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.11%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.11%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 2         | 1.11%   |
| Corsair RAM CMZ32GX3M4X1600C10 8GB DIMM DDR3 1600MT/s            | 2         | 1.11%   |
| Corsair RAM CMSX32GX4M2A2666C18 16GB SODIMM DDR4 2667MT/s        | 2         | 1.11%   |
| Unknown                                                          | 2         | 1.11%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                        | 1         | 0.56%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                         | 1         | 0.56%   |
| Unknown RAM Module 4096MB DIMM DDR3 65535MT/s                    | 1         | 0.56%   |
| Unknown RAM Module 2GB DIMM DDR2 533MT/s                         | 1         | 0.56%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                         | 1         | 0.56%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                       | 1         | 0.56%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                           | 1         | 0.56%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                           | 1         | 0.56%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                    | 1         | 0.56%   |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s                       | 1         | 0.56%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                           | 1         | 0.56%   |
| Transcend RAM TS256MLQ72V6U 2GB DIMM DDR2 667MT/s                | 1         | 0.56%   |
| Transcend RAM JM1600KLN-8GK 4096MB DIMM DDR3 1600MT/s            | 1         | 0.56%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3733MT/s               | 1         | 0.56%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s               | 1         | 0.56%   |
| Strontium RAM SRT4G86U1-P9H 4096MB DIMM DDR3 1333MT/s            | 1         | 0.56%   |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s            | 1         | 0.56%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s              | 1         | 0.56%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s          | 1         | 0.56%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 0.56%   |
| SK hynix RAM HYMP512F72CP8N3-Y5 1024MB FB-DIMM DDR2 667MT/s      | 1         | 0.56%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR 975MT/s          | 1         | 0.56%   |
| SK hynix RAM HMT41GV7BMR4A-H9 16GB DIMM 1333MT/s                 | 1         | 0.56%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 2000MT/s             | 1         | 0.56%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.56%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 0.56%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s             | 1         | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 65        | 45.77%  |
| DDR3    | 50        | 35.21%  |
| DDR2    | 7         | 4.93%   |
| SDRAM   | 4         | 2.82%   |
| LPDDR3  | 4         | 2.82%   |
| LPDDR5  | 3         | 2.11%   |
| LPDDR4  | 3         | 2.11%   |
| DDR5    | 2         | 1.41%   |
| DDR     | 2         | 1.41%   |
| Unknown | 2         | 1.41%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 67        | 46.85%  |
| DIMM         | 67        | 46.85%  |
| Row Of Chips | 6         | 4.2%    |
| RIMM         | 1         | 0.7%    |
| FB-DIMM      | 1         | 0.7%    |
| Chip         | 1         | 0.7%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 64        | 40.51%  |
| 4096  | 46        | 29.11%  |
| 16384 | 21        | 13.29%  |
| 2048  | 13        | 8.23%   |
| 32768 | 8         | 5.06%   |
| 1024  | 6         | 3.8%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 36        | 23.23%  |
| 3200    | 22        | 14.19%  |
| 2667    | 17        | 10.97%  |
| 2400    | 12        | 7.74%   |
| 1333    | 9         | 5.81%   |
| 3600    | 7         | 4.52%   |
| 2133    | 5         | 3.23%   |
| 667     | 5         | 3.23%   |
| 3800    | 4         | 2.58%   |
| 1867    | 4         | 2.58%   |
| 1334    | 3         | 1.94%   |
| Unknown | 3         | 1.94%   |
| 6400    | 2         | 1.29%   |
| 4800    | 2         | 1.29%   |
| 3733    | 2         | 1.29%   |
| 2800    | 2         | 1.29%   |
| 2666    | 2         | 1.29%   |
| 1866    | 2         | 1.29%   |
| 975     | 2         | 1.29%   |
| 533     | 2         | 1.29%   |
| 65535   | 1         | 0.65%   |
| 4267    | 1         | 0.65%   |
| 4266    | 1         | 0.65%   |
| 4199    | 1         | 0.65%   |
| 3400    | 1         | 0.65%   |
| 2933    | 1         | 0.65%   |
| 2472    | 1         | 0.65%   |
| 2187    | 1         | 0.65%   |
| 2000    | 1         | 0.65%   |
| 1066    | 1         | 0.65%   |
| 800     | 1         | 0.65%   |
| 701     | 1         | 0.65%   |

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
| Canon LiDE 300               | 1         | 11.11%  |
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
| Chicony Electronics                    | 23        | 25.84%  |
| Logitech                               | 13        | 14.61%  |
| Bison Electronics                      | 8         | 8.99%   |
| Realtek Semiconductor                  | 6         | 6.74%   |
| Microdia                               | 5         | 5.62%   |
| IMC Networks                           | 4         | 4.49%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 4.49%   |
| Syntek                                 | 3         | 3.37%   |
| Sunplus Innovation Technology          | 3         | 3.37%   |
| Sonix Technology                       | 3         | 3.37%   |
| Quanta                                 | 3         | 3.37%   |
| Luxvisions Innotech Limited            | 3         | 3.37%   |
| Lite-On Technology                     | 3         | 3.37%   |
| Samsung Electronics                    | 2         | 2.25%   |
| Z-Star Microelectronics                | 1         | 1.12%   |
| Silicon Motion                         | 1         | 1.12%   |
| Motorola PCS                           | 1         | 1.12%   |
| Microsoft                              | 1         | 1.12%   |
| Lenovo                                 | 1         | 1.12%   |
| Apple                                  | 1         | 1.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 5         | 5.62%   |
| Logitech Webcam C270                                 | 3         | 3.37%   |
| Bison HD Webcam                                      | 3         | 3.37%   |
| Bison BisonCam,NB Pro                                | 3         | 3.37%   |
| Syntek Integrated Camera                             | 2         | 2.25%   |
| Sunplus Integrated_Webcam_HD                         | 2         | 2.25%   |
| Sonix USB2.0 FHD UVC WebCam                          | 2         | 2.25%   |
| Samsung Galaxy series, misc. (MTP mode)              | 2         | 2.25%   |
| Quanta HP Webcam                                     | 2         | 2.25%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 2         | 2.25%   |
| Chicony Integrated Camera (1280x720@30)              | 2         | 2.25%   |
| Chicony HD User Facing                               | 2         | 2.25%   |
| Chicony FJ Camera                                    | 2         | 2.25%   |
| Z-Star Vimicro USB2.0 Camera                         | 1         | 1.12%   |
| Syntek USB2.0 Camera                                 | 1         | 1.12%   |
| Sunplus Laptop_Integrated_Webcam_FHD                 | 1         | 1.12%   |
| Sonix USB2.0 HD UVC WebCam                           | 1         | 1.12%   |
| Silicon Motion Web Camera                            | 1         | 1.12%   |
| Realtek USB2.0-Camera                                | 1         | 1.12%   |
| Realtek USB Camera                                   | 1         | 1.12%   |
| Realtek Laptop Camera                                | 1         | 1.12%   |
| Realtek Integrated Camera                            | 1         | 1.12%   |
| Realtek EasyCamera                                   | 1         | 1.12%   |
| Realtek Bluetooth Radio                              | 1         | 1.12%   |
| Quanta HP Wide Vision HD Camera                      | 1         | 1.12%   |
| Motorola PCS XT1033 [Moto G], PTP mode               | 1         | 1.12%   |
| Microsoft LifeCam HD-3000                            | 1         | 1.12%   |
| Microdia Laptop_Integrated_Webcam_2M                 | 1         | 1.12%   |
| Microdia Integrated_Webcam_HD                        | 1         | 1.12%   |
| Microdia Integrated Webcam                           | 1         | 1.12%   |
| Microdia Dell Integrated HD Webcam                   | 1         | 1.12%   |
| Microdia Camera                                      | 1         | 1.12%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.12%   |
| Logitech Webcam C310                                 | 1         | 1.12%   |
| Logitech Webcam C300                                 | 1         | 1.12%   |
| Logitech Webcam C170                                 | 1         | 1.12%   |
| Logitech QuickCam Pro 9000                           | 1         | 1.12%   |
| Logitech Logitech Webcam C160                        | 1         | 1.12%   |
| Logitech HD Webcam C910                              | 1         | 1.12%   |
| Logitech HD Webcam C525                              | 1         | 1.12%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 10        | 45.45%  |
| Synaptics                          | 4         | 18.18%  |
| STMicroelectronics                 | 2         | 9.09%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 9.09%   |
| Elan Microelectronics              | 2         | 9.09%   |
| Shenzhen Goodix Technology         | 1         | 4.55%   |
| LighTuning Technology              | 1         | 4.55%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                                 | 3         | 13.64%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 2         | 9.09%   |
| STMicroelectronics Fingerprint Reader                           | 2         | 9.09%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 2         | 9.09%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 1         | 4.55%   |
| Validity Sensors VFS451 Fingerprint Reader                      | 1         | 4.55%   |
| Validity Sensors VFS300 Fingerprint Reader                      | 1         | 4.55%   |
| Validity Sensors VFS Fingerprint sensor                         | 1         | 4.55%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 1         | 4.55%   |
| Synaptics WBDI Device                                           | 1         | 4.55%   |
| Synaptics TouchPad                                              | 1         | 4.55%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 1         | 4.55%   |
| Shenzhen Goodix  FingerPrint Device                             | 1         | 4.55%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 1         | 4.55%   |
| Elan ELAN:Fingerprint                                           | 1         | 4.55%   |
| Elan ELAN:ARM-M4                                                | 1         | 4.55%   |
| Unknown                                                         | 1         | 4.55%   |

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
| 0     | 96        | 58.54%  |
| 1     | 39        | 23.78%  |
| 2     | 17        | 10.37%  |
| 3     | 6         | 3.66%   |
| 4     | 5         | 3.05%   |
| 5     | 1         | 0.61%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 21        | 19.27%  |
| Graphics card            | 19        | 17.43%  |
| Sound                    | 15        | 13.76%  |
| Net/wireless             | 10        | 9.17%   |
| Communication controller | 9         | 8.26%   |
| Chipcard                 | 9         | 8.26%   |
| Unassigned class         | 4         | 3.67%   |
| Multimedia controller    | 4         | 3.67%   |
| Card reader              | 4         | 3.67%   |
| Camera                   | 4         | 3.67%   |
| Bluetooth                | 3         | 2.75%   |
| Net/ethernet             | 2         | 1.83%   |
| Storage/raid             | 1         | 0.92%   |
| Storage/ide              | 1         | 0.92%   |
| Storage/ata              | 1         | 0.92%   |
| Storage                  | 1         | 0.92%   |
| Firewire controller      | 1         | 0.92%   |

