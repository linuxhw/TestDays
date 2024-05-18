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

Total: 143

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T430s 2355CL4      | Notebook    | [b90ab4a6e2](https://linux-hardware.org/?probe=b90ab4a6e2) | May 07, 2024 |
| Lenovo        | ThinkPad T16 Gen 2 21K7C... | Notebook    | [29f2579a02](https://linux-hardware.org/?probe=29f2579a02) | Apr 27, 2024 |
| Dell          | Precision 7510              | Notebook    | [23916f1909](https://linux-hardware.org/?probe=23916f1909) | Apr 22, 2024 |
| BESSTAR Te... | CB9                         | Mini pc     | [ddd433c51c](https://linux-hardware.org/?probe=ddd433c51c) | Apr 21, 2024 |
| Chuwi         | UBook X                     | Convertible | [1b5a7adcb3](https://linux-hardware.org/?probe=1b5a7adcb3) | Apr 20, 2024 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [37bd870888](https://linux-hardware.org/?probe=37bd870888) | Apr 19, 2024 |
| Lenovo        | 3130 SDK0J40700 WIN 3258... | Mini pc     | [5256952fc5](https://linux-hardware.org/?probe=5256952fc5) | Apr 17, 2024 |
| Lenovo        | ThinkPad T430s 2355CL4      | Notebook    | [e680816d8a](https://linux-hardware.org/?probe=e680816d8a) | Mar 13, 2024 |
| MSI           | Modern 14 B5M               | Notebook    | [585c473256](https://linux-hardware.org/?probe=585c473256) | Mar 08, 2024 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [7204492392](https://linux-hardware.org/?probe=7204492392) | Mar 05, 2024 |
| MSI           | PRO X670-P WIFI             | Desktop     | [0ef39f433d](https://linux-hardware.org/?probe=0ef39f433d) | Feb 27, 2024 |
| Dell          | XPS 13 9370                 | Notebook    | [e94228e06b](https://linux-hardware.org/?probe=e94228e06b) | Feb 22, 2024 |
| Notebook      | NL5xNU                      | Notebook    | [e83f0b4085](https://linux-hardware.org/?probe=e83f0b4085) | Feb 18, 2024 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [2ed279c40d](https://linux-hardware.org/?probe=2ed279c40d) | Feb 16, 2024 |
| ASRock        | B550M-ITX/ac                | Desktop     | [27015117d0](https://linux-hardware.org/?probe=27015117d0) | Feb 13, 2024 |
| Dell          | XPS 13 9370                 | Notebook    | [11b5a42b88](https://linux-hardware.org/?probe=11b5a42b88) | Feb 11, 2024 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [6ae9e4d70e](https://linux-hardware.org/?probe=6ae9e4d70e) | Feb 06, 2024 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [f536b283c6](https://linux-hardware.org/?probe=f536b283c6) | Jan 27, 2024 |
| HP            | 17E2                        | Mini pc     | [d382ed2027](https://linux-hardware.org/?probe=d382ed2027) | Jan 22, 2024 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [5dcf737641](https://linux-hardware.org/?probe=5dcf737641) | Jan 15, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [a2ec3f504c](https://linux-hardware.org/?probe=a2ec3f504c) | Jan 14, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [167fddc449](https://linux-hardware.org/?probe=167fddc449) | Jan 14, 2024 |
| Acer          | Aspire SW5-012              | Notebook    | [efc348dbe0](https://linux-hardware.org/?probe=efc348dbe0) | Dec 31, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [7e506254e0](https://linux-hardware.org/?probe=7e506254e0) | Dec 22, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [4fd5ba2289](https://linux-hardware.org/?probe=4fd5ba2289) | Dec 04, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [24ebfe35c8](https://linux-hardware.org/?probe=24ebfe35c8) | Nov 22, 2023 |
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


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 5.15.19                     | 21        | 17.21%  |
| 5.19.17                     | 7         | 5.74%   |
| 5.15.63                     | 7         | 5.74%   |
| 5.19.17-Unraid              | 4         | 3.28%   |
| 5.15.27                     | 4         | 3.28%   |
| 5.15.145                    | 4         | 3.28%   |
| 5.15.117                    | 4         | 3.28%   |
| 5.15.94                     | 3         | 2.46%   |
| 5.15.38                     | 3         | 2.46%   |
| 6.1.64-Unraid               | 2         | 1.64%   |
| 6.1.44                      | 2         | 1.64%   |
| 5.17.2                      | 2         | 1.64%   |
| 5.17.1                      | 2         | 1.64%   |
| 5.16.13                     | 2         | 1.64%   |
| 5.15.80                     | 2         | 1.64%   |
| 5.15.30-Unraid              | 2         | 1.64%   |
| 5.15.118                    | 2         | 1.64%   |
| 5.13.8                      | 2         | 1.64%   |
| 6.7.5-gsh-clevo-NL51NU-SW15 | 1         | 0.82%   |
| 6.7.4-cometdust             | 1         | 0.82%   |
| 6.6.8                       | 1         | 0.82%   |
| 6.6.7                       | 1         | 0.82%   |
| 6.6.28                      | 1         | 0.82%   |
| 6.6.22                      | 1         | 0.82%   |
| 6.6.18                      | 1         | 0.82%   |
| 6.6.11                      | 1         | 0.82%   |
| 6.5.5                       | 1         | 0.82%   |
| 6.4.8-zen1                  | 1         | 0.82%   |
| 6.1.79-Unraid               | 1         | 0.82%   |
| 6.1.61                      | 1         | 0.82%   |
| 6.1.51                      | 1         | 0.82%   |
| 6.1.38                      | 1         | 0.82%   |
| 6.1.27                      | 1         | 0.82%   |
| 6.1.20                      | 1         | 0.82%   |
| 6.1.13                      | 1         | 0.82%   |
| 6.1.12                      | 1         | 0.82%   |
| 6.1.1                       | 1         | 0.82%   |
| 5.19.16                     | 1         | 0.82%   |
| 5.17.5                      | 1         | 0.82%   |
| 5.17.0-custom               | 1         | 0.82%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.19  | 21        | 17.21%  |
| 5.19.17  | 11        | 9.02%   |
| 5.15.63  | 7         | 5.74%   |
| 5.15.27  | 4         | 3.28%   |
| 5.15.145 | 4         | 3.28%   |
| 5.15.117 | 4         | 3.28%   |
| 5.15.94  | 3         | 2.46%   |
| 5.15.38  | 3         | 2.46%   |
| 6.1.64   | 2         | 1.64%   |
| 6.1.44   | 2         | 1.64%   |
| 5.17.2   | 2         | 1.64%   |
| 5.17.1   | 2         | 1.64%   |
| 5.16.13  | 2         | 1.64%   |
| 5.15.80  | 2         | 1.64%   |
| 5.15.30  | 2         | 1.64%   |
| 5.15.118 | 2         | 1.64%   |
| 5.14.15  | 2         | 1.64%   |
| 5.13.8   | 2         | 1.64%   |
| 6.7.5    | 1         | 0.82%   |
| 6.7.4    | 1         | 0.82%   |
| 6.6.8    | 1         | 0.82%   |
| 6.6.7    | 1         | 0.82%   |
| 6.6.28   | 1         | 0.82%   |
| 6.6.22   | 1         | 0.82%   |
| 6.6.18   | 1         | 0.82%   |
| 6.6.11   | 1         | 0.82%   |
| 6.5.5    | 1         | 0.82%   |
| 6.4.8    | 1         | 0.82%   |
| 6.1.79   | 1         | 0.82%   |
| 6.1.61   | 1         | 0.82%   |
| 6.1.51   | 1         | 0.82%   |
| 6.1.38   | 1         | 0.82%   |
| 6.1.27   | 1         | 0.82%   |
| 6.1.20   | 1         | 0.82%   |
| 6.1.13   | 1         | 0.82%   |
| 6.1.12   | 1         | 0.82%   |
| 6.1.1    | 1         | 0.82%   |
| 5.19.16  | 1         | 0.82%   |
| 5.17.5   | 1         | 0.82%   |
| 5.17.0   | 1         | 0.82%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 61        | 51.26%  |
| 5.19    | 12        | 10.08%  |
| 6.1     | 11        | 9.24%   |
| 5.14    | 7         | 5.88%   |
| 6.6     | 6         | 5.04%   |
| 5.17    | 6         | 5.04%   |
| 5.16    | 6         | 5.04%   |
| 5.13    | 5         | 4.2%    |
| 6.7     | 2         | 1.68%   |
| 6.5     | 1         | 0.84%   |
| 6.4     | 1         | 0.84%   |
| 5.10    | 1         | 0.84%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 113       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE5       | 48        | 41.74%  |
| XFCE       | 31        | 26.96%  |
| Unknown    | 22        | 19.13%  |
| GNOME      | 3         | 2.61%   |
| xwmconfig  | 2         | 1.74%   |
| MATE       | 2         | 1.74%   |
| X-Generic  | 1         | 0.87%   |
| X-Cinnamon | 1         | 0.87%   |
| KDE        | 1         | 0.87%   |
| FVWM       | 1         | 0.87%   |
| DWM        | 1         | 0.87%   |
| awesome    | 1         | 0.87%   |
| 2bwm       | 1         | 0.87%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 61        | 51.26%  |
| Tty     | 41        | 34.45%  |
| Unknown | 9         | 7.56%   |
| Wayland | 8         | 6.72%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 52        | 44.44%  |
| Unknown | 35        | 29.91%  |
| XDM     | 21        | 17.95%  |
| LightDM | 6         | 5.13%   |
| SLiM    | 2         | 1.71%   |
| GDM     | 1         | 0.85%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 74        | 64.91%  |
| Unknown     | 12        | 10.53%  |
| it_IT       | 6         | 5.26%   |
| pt_BR       | 3         | 2.63%   |
| de_DE       | 3         | 2.63%   |
| ru_RU       | 2         | 1.75%   |
| fr_FR       | 2         | 1.75%   |
| en_GB       | 2         | 1.75%   |
| cs_CZ       | 2         | 1.75%   |
| zh_TW       | 1         | 0.88%   |
| us          | 1         | 0.88%   |
| pt_PT       | 1         | 0.88%   |
| ja_JP       | 1         | 0.88%   |
| es_ES.UTF8  | 1         | 0.88%   |
| es_ES       | 1         | 0.88%   |
| en_US.ASCII | 1         | 0.88%   |
| en_SE       | 1         | 0.88%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 64        | 56.14%  |
| BIOS | 50        | 43.86%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 83        | 72.17%  |
| Btrfs   | 12        | 10.43%  |
| Xfs     | 6         | 5.22%   |
| Overlay | 5         | 4.35%   |
| Rootfs  | 3         | 2.61%   |
| Tmpfs   | 2         | 1.74%   |
| Zfs     | 1         | 0.87%   |
| Jfs     | 1         | 0.87%   |
| F2fs    | 1         | 0.87%   |
| Ext2    | 1         | 0.87%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 76        | 66.09%  |
| Unknown | 20        | 17.39%  |
| MBR     | 19        | 16.52%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 84        | 73.04%  |
| Yes       | 31        | 26.96%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 80        | 70.18%  |
| Yes       | 34        | 29.82%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| MSI                 | 17        | 15.04%  |
| Lenovo              | 17        | 15.04%  |
| Hewlett-Packard     | 17        | 15.04%  |
| ASUSTek Computer    | 14        | 12.39%  |
| Dell                | 11        | 9.73%   |
| ASRock              | 8         | 7.08%   |
| Gigabyte Technology | 5         | 4.42%   |
| Acer                | 4         | 3.54%   |
| Notebook            | 3         | 2.65%   |
| Fujitsu             | 2         | 1.77%   |
| Apple               | 2         | 1.77%   |
| Valve               | 1         | 0.88%   |
| TYAN Computer       | 1         | 0.88%   |
| Toshiba             | 1         | 0.88%   |
| System76            | 1         | 0.88%   |
| Sony                | 1         | 0.88%   |
| Microsoft           | 1         | 0.88%   |
| HEDYCOMPUTER        | 1         | 0.88%   |
| Framework           | 1         | 0.88%   |
| Dynabook            | 1         | 0.88%   |
| Chuwi               | 1         | 0.88%   |
| Biostar             | 1         | 0.88%   |
| BESSTAR Tech        | 1         | 0.88%   |
| Unknown             | 1         | 0.88%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| MSI MS-7D76                              | 2         | 1.77%   |
| ASUS VivoBook_ASUSLaptop K6500ZE_K6500ZE | 2         | 1.77%   |
| ASRock N68-S3 FX                         | 2         | 1.77%   |
| Valve Jupiter                            | 1         | 0.88%   |
| TYAN S7012                               | 1         | 0.88%   |
| Toshiba Satellite C660                   | 1         | 0.88%   |
| System76 Oryx Pro                        | 1         | 0.88%   |
| Sony SVE1713A1EW                         | 1         | 0.88%   |
| Notebook X170KM-G                        | 1         | 0.88%   |
| Notebook P7xxTM                          | 1         | 0.88%   |
| Notebook NL5xNU                          | 1         | 0.88%   |
| MSI MS-7D67                              | 1         | 0.88%   |
| MSI MS-7C52                              | 1         | 0.88%   |
| MSI MS-7C02                              | 1         | 0.88%   |
| MSI MS-7B79                              | 1         | 0.88%   |
| MSI MS-7996                              | 1         | 0.88%   |
| MSI MS-7885                              | 1         | 0.88%   |
| MSI MS-7788                              | 1         | 0.88%   |
| MSI MS-7693                              | 1         | 0.88%   |
| MSI MS-7529                              | 1         | 0.88%   |
| MSI MS-7365                              | 1         | 0.88%   |
| MSI Modern 14 B5M                        | 1         | 0.88%   |
| MSI Modern 14 B11MO                      | 1         | 0.88%   |
| MSI Modern 14 B10MW                      | 1         | 0.88%   |
| MSI GP76 Leopard 11UG                    | 1         | 0.88%   |
| MSI GE76 Raider 11UE                     | 1         | 0.88%   |
| Microsoft Surface Go 3                   | 1         | 0.88%   |
| Lenovo V330-14ARR 81B1                   | 1         | 0.88%   |
| Lenovo ThinkPad X230 2325P38             | 1         | 0.88%   |
| Lenovo ThinkPad X140e 20BMS03E00         | 1         | 0.88%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS04300 | 1         | 0.88%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS2FT00 | 1         | 0.88%   |
| Lenovo ThinkPad T61 765912G              | 1         | 0.88%   |
| Lenovo ThinkPad T470p 20J60018MS         | 1         | 0.88%   |
| Lenovo ThinkPad T470 20JNS01R01          | 1         | 0.88%   |
| Lenovo ThinkPad T430s 2355CL4            | 1         | 0.88%   |
| Lenovo ThinkPad T410 2518C3U             | 1         | 0.88%   |
| Lenovo ThinkPad T16 Gen 2 21K7CTO1WW     | 1         | 0.88%   |
| Lenovo ThinkPad Edge E530c 336669G       | 1         | 0.88%   |
| Lenovo ThinkPad E16 Gen 1 21JT000PJP     | 1         | 0.88%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 12        | 10.62%  |
| MSI Modern         | 3         | 2.65%   |
| HP Pavilion        | 3         | 2.65%   |
| Dell Precision     | 3         | 2.65%   |
| ASUS ROG           | 3         | 2.65%   |
| ASUS PRIME         | 3         | 2.65%   |
| MSI MS-7D76        | 2         | 1.77%   |
| Lenovo IdeaPad     | 2         | 1.77%   |
| HP OMEN            | 2         | 1.77%   |
| HP Laptop          | 2         | 1.77%   |
| HP EliteBook       | 2         | 1.77%   |
| Dell Vostro        | 2         | 1.77%   |
| Dell OptiPlex      | 2         | 1.77%   |
| ASUS VivoBook      | 2         | 1.77%   |
| ASUS TUF           | 2         | 1.77%   |
| ASRock N68-S3      | 2         | 1.77%   |
| Acer Aspire        | 2         | 1.77%   |
| Valve Jupiter      | 1         | 0.88%   |
| TYAN S7012         | 1         | 0.88%   |
| Toshiba Satellite  | 1         | 0.88%   |
| System76 Oryx      | 1         | 0.88%   |
| Sony SVE1713A1EW   | 1         | 0.88%   |
| Notebook X170KM-G  | 1         | 0.88%   |
| Notebook P7xxTM    | 1         | 0.88%   |
| Notebook NL5xNU    | 1         | 0.88%   |
| MSI MS-7D67        | 1         | 0.88%   |
| MSI MS-7C52        | 1         | 0.88%   |
| MSI MS-7C02        | 1         | 0.88%   |
| MSI MS-7B79        | 1         | 0.88%   |
| MSI MS-7996        | 1         | 0.88%   |
| MSI MS-7885        | 1         | 0.88%   |
| MSI MS-7788        | 1         | 0.88%   |
| MSI MS-7693        | 1         | 0.88%   |
| MSI MS-7529        | 1         | 0.88%   |
| MSI MS-7365        | 1         | 0.88%   |
| MSI GP76           | 1         | 0.88%   |
| MSI GE76           | 1         | 0.88%   |
| Microsoft Surface  | 1         | 0.88%   |
| Lenovo V330-14ARR  | 1         | 0.88%   |
| Lenovo ThinkCentre | 1         | 0.88%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 16        | 14.16%  |
| 2021 | 15        | 13.27%  |
| 2022 | 11        | 9.73%   |
| 2019 | 9         | 7.96%   |
| 2017 | 8         | 7.08%   |
| 2012 | 8         | 7.08%   |
| 2015 | 7         | 6.19%   |
| 2018 | 6         | 5.31%   |
| 2011 | 6         | 5.31%   |
| 2014 | 5         | 4.42%   |
| 2010 | 5         | 4.42%   |
| 2008 | 4         | 3.54%   |
| 2016 | 3         | 2.65%   |
| 2009 | 3         | 2.65%   |
| 2007 | 3         | 2.65%   |
| 2023 | 2         | 1.77%   |
| 2024 | 1         | 0.88%   |
| 2013 | 1         | 0.88%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 55        | 48.67%  |
| Desktop     | 48        | 42.48%  |
| Mini pc     | 4         | 3.54%   |
| All in one  | 2         | 1.77%   |
| Server      | 2         | 1.77%   |
| Tablet      | 1         | 0.88%   |
| Convertible | 1         | 0.88%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 113       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 111       | 98.23%  |
| Yes  | 2         | 1.77%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 24        | 20.87%  |
| 16.01-24.0  | 23        | 20%     |
| 4.01-8.0    | 16        | 13.91%  |
| 32.01-64.0  | 15        | 13.04%  |
| 3.01-4.0    | 14        | 12.17%  |
| 64.01-256.0 | 11        | 9.57%   |
| 24.01-32.0  | 7         | 6.09%   |
| 1.01-2.0    | 4         | 3.48%   |
| 2.01-3.0    | 1         | 0.87%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 30        | 24.59%  |
| 1.01-2.0   | 29        | 23.77%  |
| 4.01-8.0   | 27        | 22.13%  |
| 0.51-1.0   | 13        | 10.66%  |
| 3.01-4.0   | 9         | 7.38%   |
| 8.01-16.0  | 5         | 4.1%    |
| 16.01-24.0 | 4         | 3.28%   |
| 0.01-0.5   | 3         | 2.46%   |
| 32.01-64.0 | 1         | 0.82%   |
| 24.01-32.0 | 1         | 0.82%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 55        | 47.41%  |
| 2      | 32        | 27.59%  |
| 3      | 10        | 8.62%   |
| 4      | 6         | 5.17%   |
| 6      | 4         | 3.45%   |
| 10     | 2         | 1.72%   |
| 9      | 2         | 1.72%   |
| 0      | 2         | 1.72%   |
| 14     | 1         | 0.86%   |
| 11     | 1         | 0.86%   |
| 5      | 1         | 0.86%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 82        | 71.93%  |
| Yes       | 32        | 28.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 102       | 89.47%  |
| No        | 12        | 10.53%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 85        | 75.22%  |
| No        | 28        | 24.78%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 75        | 65.79%  |
| No        | 39        | 34.21%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 24        | 21.24%  |
| Japan        | 9         | 7.96%   |
| Italy        | 9         | 7.96%   |
| UK           | 7         | 6.19%   |
| Kazakhstan   | 6         | 5.31%   |
| Germany      | 6         | 5.31%   |
| Brazil       | 6         | 5.31%   |
| Spain        | 4         | 3.54%   |
| Portugal     | 4         | 3.54%   |
| France       | 4         | 3.54%   |
| South Africa | 3         | 2.65%   |
| Russia       | 3         | 2.65%   |
| Greece       | 3         | 2.65%   |
| Canada       | 3         | 2.65%   |
| Romania      | 2         | 1.77%   |
| India        | 2         | 1.77%   |
| Hong Kong    | 2         | 1.77%   |
| Czechia      | 2         | 1.77%   |
| China        | 2         | 1.77%   |
| Argentina    | 2         | 1.77%   |
| Taiwan       | 1         | 0.88%   |
| Switzerland  | 1         | 0.88%   |
| Sweden       | 1         | 0.88%   |
| Serbia       | 1         | 0.88%   |
| Poland       | 1         | 0.88%   |
| Netherlands  | 1         | 0.88%   |
| Mexico       | 1         | 0.88%   |
| Iran         | 1         | 0.88%   |
| Chile        | 1         | 0.88%   |
| Australia    | 1         | 0.88%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Tsukuba            | 6         | 5.22%   |
| Ust-Kamenogorsk    | 4         | 3.48%   |
| Lisbon             | 3         | 2.61%   |
| Chania             | 3         | 2.61%   |
| Tokyo              | 2         | 1.74%   |
| Sun Prairie        | 2         | 1.74%   |
| Rome               | 2         | 1.74%   |
| Moscow             | 2         | 1.74%   |
| Milan              | 2         | 1.74%   |
| McKinney           | 2         | 1.74%   |
| Karaganda          | 2         | 1.74%   |
| Greater Noida      | 2         | 1.74%   |
| Frignano           | 2         | 1.74%   |
| Fayetteville       | 2         | 1.74%   |
| Cape Town          | 2         | 1.74%   |
| Bucharest          | 2         | 1.74%   |
| Worpswede          | 1         | 0.87%   |
| Winter Springs     | 1         | 0.87%   |
| Warsaw             | 1         | 0.87%   |
| Villa Carlos Paz   | 1         | 0.87%   |
| Toronto            | 1         | 0.87%   |
| Tehran             | 1         | 0.87%   |
| Tatuí             | 1         | 0.87%   |
| Taichung           | 1         | 0.87%   |
| St Petersburg      | 1         | 0.87%   |
| Springfield        | 1         | 0.87%   |
| Skövde            | 1         | 0.87%   |
| Sham Shui Po       | 1         | 0.87%   |
| Seville            | 1         | 0.87%   |
| Senhora da Hora    | 1         | 0.87%   |
| Seattle            | 1         | 0.87%   |
| Sao Paulo          | 1         | 0.87%   |
| Santiago           | 1         | 0.87%   |
| Santander          | 1         | 0.87%   |
| Santa Cruz do Sul  | 1         | 0.87%   |
| San Giuliano Terme | 1         | 0.87%   |
| Saint Paul         | 1         | 0.87%   |
| Round Rock         | 1         | 0.87%   |
| Roudnice nad Labem | 1         | 0.87%   |
| Rock               | 1         | 0.87%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 33        | 45     | 17.1%   |
| Seagate                     | 29        | 46     | 15.03%  |
| WDC                         | 28        | 65     | 14.51%  |
| Kingston                    | 12        | 14     | 6.22%   |
| Toshiba                     | 11        | 22     | 5.7%    |
| Crucial                     | 8         | 9      | 4.15%   |
| SanDisk                     | 6         | 8      | 3.11%   |
| Intel                       | 6         | 8      | 3.11%   |
| Hitachi                     | 5         | 8      | 2.59%   |
| SK hynix                    | 4         | 4      | 2.07%   |
| HGST                        | 4         | 4      | 2.07%   |
| Unknown                     | 3         | 6      | 1.55%   |
| Transcend                   | 3         | 3      | 1.55%   |
| Micron Technology           | 3         | 3      | 1.55%   |
| KIOXIA                      | 3         | 3      | 1.55%   |
| Silicon Motion              | 2         | 3      | 1.04%   |
| Patriot                     | 2         | 2      | 1.04%   |
| Micron/Crucial Technology   | 2         | 2      | 1.04%   |
| Kingston Technology Company | 2         | 2      | 1.04%   |
| JMicron Technology          | 2         | 2      | 1.04%   |
| Hewlett-Packard             | 2         | 3      | 1.04%   |
| Gigabyte Technology         | 2         | 2      | 1.04%   |
| External                    | 2         | 2      | 1.04%   |
| A-DATA Technology           | 2         | 2      | 1.04%   |
| ZHITAI                      | 1         | 2      | 0.52%   |
| Verbatim                    | 1         | 2      | 0.52%   |
| Team                        | 1         | 1      | 0.52%   |
| Realtek Semiconductor       | 1         | 1      | 0.52%   |
| PNY                         | 1         | 1      | 0.52%   |
| Plextor                     | 1         | 1      | 0.52%   |
| Phison Electronics          | 1         | 1      | 0.52%   |
| Maxtor                      | 1         | 1      | 0.52%   |
| LITEON                      | 1         | 1      | 0.52%   |
| Lexar                       | 1         | 1      | 0.52%   |
| Intenso                     | 1         | 1      | 0.52%   |
| GOODRAM                     | 1         | 1      | 0.52%   |
| Fujitsu                     | 1         | 1      | 0.52%   |
| DUEX                        | 1         | 1      | 0.52%   |
| China                       | 1         | 1      | 0.52%   |
| Apple                       | 1         | 1      | 0.52%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                       | 5         | 2.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 4         | 1.74%   |
| Intel SSD 660P Series 1024GB                          | 3         | 1.3%    |
| WDC WDS100T2B0A-00SM50 1TB SSD                        | 2         | 0.87%   |
| WDC WD40EZRX-00SPEB0 4TB                              | 2         | 0.87%   |
| WDC WD20EFRX-68EUZN0 2TB                              | 2         | 0.87%   |
| WDC WD10SPZX-60Z10T0 1TB                              | 2         | 0.87%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 2         | 0.87%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 2         | 0.87%   |
| Seagate ST4000VN006-3CW104 4TB                        | 2         | 0.87%   |
| Seagate ST4000DM004-2CV104 4TB                        | 2         | 0.87%   |
| Seagate ST2000DX001-1NS164 2TB                        | 2         | 0.87%   |
| Seagate ST2000DM008-2FR102 2TB                        | 2         | 0.87%   |
| Seagate ST2000DL003-9VT166 2TB                        | 2         | 0.87%   |
| Seagate ST1000LM048-2E7172 1TB                        | 2         | 0.87%   |
| Seagate ST1000DM003-1SB102 1TB                        | 2         | 0.87%   |
| Seagate Expansion+ Desk 4TB                           | 2         | 0.87%   |
| Samsung SSD 970 EVO Plus 500GB                        | 2         | 0.87%   |
| Samsung SSD 970 EVO 250GB                             | 2         | 0.87%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 2         | 0.87%   |
| Kingston Company OM3PDP3 NVMe SSD 512GB               | 2         | 0.87%   |
| Kingston SA400S37120G 120GB SSD                       | 2         | 0.87%   |
| JMicron Generic 320GB                                 | 2         | 0.87%   |
| HGST HTS725050A7E630 500GB                            | 2         | 0.87%   |
| External USB3.0 500GB                                 | 2         | 0.87%   |
| Crucial CT500MX500SSD1 500GB                          | 2         | 0.87%   |
| ZHITAI SC001 Active 1TB SSD                           | 1         | 0.43%   |
| ZHITAI PC005 Active 512GB                             | 1         | 0.43%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                      | 1         | 0.43%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                      | 1         | 0.43%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                        | 1         | 0.43%   |
| WDC WDS100T1X0E-00AFY0 1TB                            | 1         | 0.43%   |
| WDC WD80EFZZ-68BTXN0 8TB                              | 1         | 0.43%   |
| WDC WD80EFZX-68UW8N0 8TB                              | 1         | 0.43%   |
| WDC WD80EFBX-68AZZN0 8TB                              | 1         | 0.43%   |
| WDC WD80EFAX-68LHPN0 8TB                              | 1         | 0.43%   |
| WDC WD80EFAX-68KNBN0 8TB                              | 1         | 0.43%   |
| WDC WD8003FFBX-68B9AN0 8TB                            | 1         | 0.43%   |
| WDC WD6003FRYZ-01F0DB0 6TB                            | 1         | 0.43%   |
| WDC WD5000BEKT-60KA9T0 500GB                          | 1         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 46     | 38.16%  |
| WDC                 | 23        | 56     | 30.26%  |
| Toshiba             | 10        | 17     | 13.16%  |
| Hitachi             | 5         | 8      | 6.58%   |
| HGST                | 4         | 4      | 5.26%   |
| JMicron Technology  | 2         | 2      | 2.63%   |
| Samsung Electronics | 1         | 1      | 1.32%   |
| Maxtor              | 1         | 1      | 1.32%   |
| Fujitsu             | 1         | 1      | 1.32%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 17     | 20.69%  |
| Kingston            | 11        | 13     | 18.97%  |
| Crucial             | 5         | 6      | 8.62%   |
| WDC                 | 4         | 6      | 6.9%    |
| SanDisk             | 3         | 3      | 5.17%   |
| Transcend           | 2         | 2      | 3.45%   |
| External            | 2         | 2      | 3.45%   |
| ZHITAI              | 1         | 1      | 1.72%   |
| Verbatim            | 1         | 2      | 1.72%   |
| Toshiba             | 1         | 3      | 1.72%   |
| SK hynix            | 1         | 1      | 1.72%   |
| PNY                 | 1         | 1      | 1.72%   |
| Plextor             | 1         | 1      | 1.72%   |
| Patriot             | 1         | 1      | 1.72%   |
| Micron Technology   | 1         | 1      | 1.72%   |
| LITEON              | 1         | 1      | 1.72%   |
| Lexar               | 1         | 1      | 1.72%   |
| Intenso             | 1         | 1      | 1.72%   |
| Intel               | 1         | 2      | 1.72%   |
| Hewlett-Packard     | 1         | 1      | 1.72%   |
| GOODRAM             | 1         | 1      | 1.72%   |
| Gigabyte Technology | 1         | 1      | 1.72%   |
| DUEX                | 1         | 1      | 1.72%   |
| China               | 1         | 1      | 1.72%   |
| Apple               | 1         | 1      | 1.72%   |
| AirDisk             | 1         | 1      | 1.72%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 55        | 75     | 33.74%  |
| SSD  | 53        | 72     | 32.52%  |
| HDD  | 53        | 136    | 32.52%  |
| MMC  | 2         | 4      | 1.23%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 77        | 200    | 54.23%  |
| NVMe | 55        | 75     | 38.73%  |
| SAS  | 8         | 8      | 5.63%   |
| MMC  | 2         | 4      | 1.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 60        | 78     | 48%     |
| 0.51-1.0   | 26        | 48     | 20.8%   |
| 3.01-4.0   | 15        | 27     | 12%     |
| 1.01-2.0   | 13        | 16     | 10.4%   |
| 4.01-10.0  | 6         | 26     | 4.8%    |
| 2.01-3.0   | 5         | 13     | 4%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 27        | 22.88%  |
| 501-1000       | 26        | 22.03%  |
| 251-500        | 16        | 13.56%  |
| 1001-2000      | 13        | 11.02%  |
| Unknown        | 10        | 8.47%   |
| 1-20           | 8         | 6.78%   |
| 2001-3000      | 7         | 5.93%   |
| More than 3000 | 5         | 4.24%   |
| 51-100         | 4         | 3.39%   |
| 21-50          | 2         | 1.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 27        | 22.69%  |
| 1-20           | 21        | 17.65%  |
| 251-500        | 18        | 15.13%  |
| 21-50          | 16        | 13.45%  |
| 501-1000       | 11        | 9.24%   |
| Unknown        | 10        | 8.4%    |
| 1001-2000      | 7         | 5.88%   |
| 51-100         | 6         | 5.04%   |
| More than 3000 | 2         | 1.68%   |
| 2001-3000      | 1         | 0.84%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1         | 1      | 4.76%   |
| WDC WD5000AAKX-22ERMA0 500GB          | 1         | 1      | 4.76%   |
| WDC WD40EFAX-68JH4N1 4TB              | 1         | 4      | 4.76%   |
| WDC WD3200AAJS-65B4A0 320GB           | 1         | 1      | 4.76%   |
| WDC WD30EZRX-00MMMB0 3TB              | 1         | 1      | 4.76%   |
| WDC WD30EZRX-00D8PB0 3TB              | 1         | 1      | 4.76%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1         | 2      | 4.76%   |
| WDC WD20EARX-00PASB0 2TB              | 1         | 1      | 4.76%   |
| Seagate ST380011A 80GB                | 1         | 1      | 4.76%   |
| Seagate ST3500630AS 500GB             | 1         | 1      | 4.76%   |
| Seagate ST3000VX006-1HH166 3TB        | 1         | 1      | 4.76%   |
| Seagate ST2000DL003-9VT166 2TB        | 1         | 1      | 4.76%   |
| Seagate ST1000DM003-1ER162 1TB        | 1         | 2      | 4.76%   |
| Samsung Electronics SSD 970 EVO 500GB | 1         | 1      | 4.76%   |
| Samsung Electronics SSD 870 EVO 1TB   | 1         | 1      | 4.76%   |
| Plextor PX-128M6S 128GB SSD           | 1         | 1      | 4.76%   |
| Hitachi HUA723030ALA640 3TB           | 1         | 1      | 4.76%   |
| Hitachi HDS721016CLA382 160GB         | 1         | 1      | 4.76%   |
| HGST HTS725050A7E630 500GB            | 1         | 1      | 4.76%   |
| HGST HTS545050A7E380 500GB            | 1         | 1      | 4.76%   |
| DUEX DX300256A5xnEMLC 256GB SSD       | 1         | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 12     | 36.84%  |
| Seagate             | 4         | 6      | 21.05%  |
| Samsung Electronics | 2         | 2      | 10.53%  |
| Hitachi             | 2         | 2      | 10.53%  |
| HGST                | 2         | 2      | 10.53%  |
| Plextor             | 1         | 1      | 5.26%   |
| DUEX                | 1         | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 6         | 11     | 42.86%  |
| Seagate | 4         | 6      | 28.57%  |
| Hitachi | 2         | 2      | 14.29%  |
| HGST    | 2         | 2      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 21     | 70.59%  |
| SSD  | 4         | 4      | 23.53%  |
| NVMe | 1         | 1      | 5.88%   |

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
| Works    | 87        | 198    | 64.93%  |
| Detected | 30        | 63     | 22.39%  |
| Malfunc  | 17        | 26     | 12.69%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 56        | 33.33%  |
| AMD                          | 34        | 20.24%  |
| Samsung Electronics          | 21        | 12.5%   |
| ASMedia Technology           | 8         | 4.76%   |
| SanDisk                      | 6         | 3.57%   |
| Micron/Crucial Technology    | 5         | 2.98%   |
| Marvell Technology Group     | 5         | 2.98%   |
| Nvidia                       | 4         | 2.38%   |
| SK hynix                     | 3         | 1.79%   |
| Realtek Semiconductor        | 3         | 1.79%   |
| KIOXIA                       | 3         | 1.79%   |
| Kingston Technology Company  | 3         | 1.79%   |
| JMicron Technology           | 3         | 1.79%   |
| Silicon Motion               | 2         | 1.19%   |
| Phison Electronics           | 2         | 1.19%   |
| Micron Technology            | 2         | 1.19%   |
| Yangtze Memory Technologies  | 1         | 0.6%    |
| Toshiba America Info Systems | 1         | 0.6%    |
| Nextorage                    | 1         | 0.6%    |
| MAXIO Technology (Hangzhou)  | 1         | 0.6%    |
| LSI Logic / Symbios Logic    | 1         | 0.6%    |
| Broadcom / LSI               | 1         | 0.6%    |
| Biwin Storage Technology     | 1         | 0.6%    |
| Adaptec                      | 1         | 0.6%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 19        | 9.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 10        | 5%      |
| AMD 400 Series Chipset SATA Controller                                           | 8         | 4%      |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 6         | 3%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 6         | 3%      |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                    | 6         | 3%      |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 5         | 2.5%    |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 4         | 2%      |
| AMD 500 Series Chipset SATA Controller                                           | 4         | 2%      |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 3         | 1.5%    |
| Nvidia MCP61 SATA Controller                                                     | 3         | 1.5%    |
| Nvidia MCP61 IDE                                                                 | 3         | 1.5%    |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 3         | 1.5%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 3         | 1.5%    |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 1.5%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 3         | 1.5%    |
| Intel SSD 660P Series                                                            | 3         | 1.5%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 3         | 1.5%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 3         | 1.5%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 1.5%    |
| AMD 600 Series Chipset SATA Controller                                           | 3         | 1.5%    |
| SK hynix BC511 NVMe SSD                                                          | 2         | 1%      |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 2         | 1%      |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 2         | 1%      |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 1%      |
| Kingston Company OM3PDP3 NVMe SSD                                                | 2         | 1%      |
| JMicron JMB58x AHCI SATA controller                                              | 2         | 1%      |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 1%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1%      |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 2         | 1%      |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 1%      |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 1%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 1%      |
| Intel 631xESB/632xESB IDE Controller                                             | 2         | 1%      |
| Intel 4 Series Chipset PT IDER Controller                                        | 2         | 1%      |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 2         | 1%      |
| Yangtze Memory ZHITAI PC005 NVMe SSD                                             | 1         | 0.5%    |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 1         | 0.5%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 1         | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 72        | 45%     |
| NVMe | 55        | 34.38%  |
| IDE  | 18        | 11.25%  |
| RAID | 12        | 7.5%    |
| SCSI | 3         | 1.88%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 70        | 61.95%  |
| AMD    | 43        | 38.05%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 4         | 3.51%   |
| Intel 12th Gen Core i7-12700H           | 3         | 2.63%   |
| AMD Ryzen 9 5950X 16-Core Processor     | 3         | 2.63%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 2         | 1.75%   |
| Intel Core i7-5820K CPU @ 3.30GHz       | 2         | 1.75%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 2         | 1.75%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 2         | 1.75%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 2         | 1.75%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz    | 2         | 1.75%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 2         | 1.75%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 1.75%   |
| AMD Ryzen 9 7900 12-Core Processor      | 2         | 1.75%   |
| AMD Ryzen 7 3800X 8-Core Processor      | 2         | 1.75%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 2         | 1.75%   |
| AMD Ryzen 5 3600 6-Core Processor       | 2         | 1.75%   |
| AMD Athlon II X2 250 Processor          | 2         | 1.75%   |
| Intel Xeon CPU X5680 @ 3.33GHz          | 1         | 0.88%   |
| Intel Xeon CPU X5355 @ 2.66GHz          | 1         | 0.88%   |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz     | 1         | 0.88%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz     | 1         | 0.88%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz     | 1         | 0.88%   |
| Intel Xeon CPU 5160 @ 3.00GHz           | 1         | 0.88%   |
| Intel Pentium Silver N6000 @ 1.10GHz    | 1         | 0.88%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz  | 1         | 0.88%   |
| Intel Pentium CPU GOLD 6500Y @ 1.10GHz  | 1         | 0.88%   |
| Intel Pentium CPU G3250 @ 3.20GHz       | 1         | 0.88%   |
| Intel Pentium CPU 2020M @ 2.40GHz       | 1         | 0.88%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 1         | 0.88%   |
| Intel Core i7-8700K CPU @ 3.70GHz       | 1         | 0.88%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 1         | 0.88%   |
| Intel Core i7-7700 CPU @ 3.60GHz        | 1         | 0.88%   |
| Intel Core i7-7600U CPU @ 2.80GHz       | 1         | 0.88%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 1         | 0.88%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 1         | 0.88%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 1         | 0.88%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 1         | 0.88%   |
| Intel Core i7-3840QM CPU @ 2.80GHz      | 1         | 0.88%   |
| Intel Core i7-3720QM CPU @ 2.60GHz      | 1         | 0.88%   |
| Intel Core i7-10870H CPU @ 2.20GHz      | 1         | 0.88%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 1         | 0.88%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 18        | 15.79%  |
| Intel Core i7        | 17        | 14.91%  |
| Other                | 14        | 12.28%  |
| AMD Ryzen 5          | 11        | 9.65%   |
| AMD Ryzen 7          | 9         | 7.89%   |
| AMD Ryzen 9          | 8         | 7.02%   |
| Intel Xeon           | 6         | 5.26%   |
| Intel Core 2 Duo     | 5         | 4.39%   |
| Intel Pentium        | 3         | 2.63%   |
| Intel Core i3        | 3         | 2.63%   |
| AMD FX               | 3         | 2.63%   |
| Intel Celeron        | 2         | 1.75%   |
| Intel Atom           | 2         | 1.75%   |
| AMD Ryzen 7 PRO      | 2         | 1.75%   |
| AMD Athlon II X2     | 2         | 1.75%   |
| Intel Pentium Silver | 1         | 0.88%   |
| Intel Pentium Dual   | 1         | 0.88%   |
| AMD Ryzen 3 PRO      | 1         | 0.88%   |
| AMD Ryzen 3          | 1         | 0.88%   |
| AMD G                | 1         | 0.88%   |
| AMD EPYC             | 1         | 0.88%   |
| AMD E1               | 1         | 0.88%   |
| AMD Athlon           | 1         | 0.88%   |
| AMD A8               | 1         | 0.88%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 36        | 31.58%  |
| 2      | 31        | 27.19%  |
| 8      | 21        | 18.42%  |
| 6      | 10        | 8.77%   |
| 16     | 4         | 3.51%   |
| 14     | 4         | 3.51%   |
| 12     | 4         | 3.51%   |
| 10     | 3         | 2.63%   |
| 3      | 1         | 0.88%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 110       | 97.35%  |
| 2      | 3         | 2.65%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 86        | 76.11%  |
| 1      | 27        | 23.89%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 113       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 26.96%  |
| 0x306a9    | 7         | 6.09%   |
| 0x08701021 | 5         | 4.35%   |
| 0x906a3    | 4         | 3.48%   |
| 0x806d1    | 4         | 3.48%   |
| 0x08108109 | 4         | 3.48%   |
| 0x806c1    | 3         | 2.61%   |
| 0x306f2    | 3         | 2.61%   |
| 0x306c3    | 3         | 2.61%   |
| 0x20655    | 3         | 2.61%   |
| 0x906ea    | 2         | 1.74%   |
| 0x806ea    | 2         | 1.74%   |
| 0x406e3    | 2         | 1.74%   |
| 0x406c4    | 2         | 1.74%   |
| 0x1067a    | 2         | 1.74%   |
| 0x0a50000c | 2         | 1.74%   |
| 0x0a201016 | 2         | 1.74%   |
| 0x08600106 | 2         | 1.74%   |
| 0x0810100b | 2         | 1.74%   |
| 0xa0671    | 1         | 0.87%   |
| 0xa0653    | 1         | 0.87%   |
| 0xa0652    | 1         | 0.87%   |
| 0x906e9    | 1         | 0.87%   |
| 0x906c0    | 1         | 0.87%   |
| 0x906a4    | 1         | 0.87%   |
| 0x806ec    | 1         | 0.87%   |
| 0x6fd      | 1         | 0.87%   |
| 0x6fb      | 1         | 0.87%   |
| 0x6fa      | 1         | 0.87%   |
| 0x506e3    | 1         | 0.87%   |
| 0x306e4    | 1         | 0.87%   |
| 0x306d4    | 1         | 0.87%   |
| 0x30678    | 1         | 0.87%   |
| 0x206c2    | 1         | 0.87%   |
| 0x106c2    | 1         | 0.87%   |
| 0x0a20120a | 1         | 0.87%   |
| 0x0a20102b | 1         | 0.87%   |
| 0x08900201 | 1         | 0.87%   |
| 0x08608103 | 1         | 0.87%   |
| 0x08608102 | 1         | 0.87%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 13        | 11.4%   |
| Zen 2            | 10        | 8.77%   |
| IvyBridge        | 9         | 7.89%   |
| Zen 3            | 8         | 7.02%   |
| Unknown          | 8         | 7.02%   |
| Haswell          | 7         | 6.14%   |
| Zen+             | 6         | 5.26%   |
| Westmere         | 6         | 5.26%   |
| Skylake          | 5         | 4.39%   |
| Icelake          | 5         | 4.39%   |
| Core             | 5         | 4.39%   |
| Alderlake Hybrid | 5         | 4.39%   |
| Zen              | 4         | 3.51%   |
| TigerLake        | 3         | 2.63%   |
| Silvermont       | 3         | 2.63%   |
| Penryn           | 3         | 2.63%   |
| Piledriver       | 2         | 1.75%   |
| K10              | 2         | 1.75%   |
| CometLake        | 2         | 1.75%   |
| Tremont          | 1         | 0.88%   |
| SandyBridge      | 1         | 0.88%   |
| Puma             | 1         | 0.88%   |
| Jaguar           | 1         | 0.88%   |
| Bulldozer        | 1         | 0.88%   |
| Broadwell        | 1         | 0.88%   |
| Bonnell          | 1         | 0.88%   |
| Bobcat           | 1         | 0.88%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 46        | 36.22%  |
| AMD                        | 41        | 32.28%  |
| Nvidia                     | 39        | 30.71%  |
| Matrox Electronics Systems | 1         | 0.79%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 3.79%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 4         | 3.03%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 3.03%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 3.03%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 3         | 2.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 2.27%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 2.27%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 2.27%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 2.27%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 2.27%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 3         | 2.27%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 2.27%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 2.27%   |
| AMD Raphael                                                                              | 3         | 2.27%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 3         | 2.27%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 1.52%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 1.52%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2         | 1.52%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2         | 1.52%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2         | 1.52%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 1.52%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 2         | 1.52%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.52%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.52%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 1.52%   |
| AMD Navi 32 [Radeon RX 7700 XT / 7800 XT]                                                | 2         | 1.52%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 2         | 1.52%   |
| AMD Lucienne                                                                             | 2         | 1.52%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 1.52%   |
| AMD Barcelo                                                                              | 2         | 1.52%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.76%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 1         | 0.76%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile / Max-Q]                                         | 1         | 0.76%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.76%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.76%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.76%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 0.76%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.76%   |
| Nvidia GM107GLM [Quadro M2000M]                                                          | 1         | 0.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 36        | 31.86%  |
| 1 x Intel      | 33        | 29.2%   |
| 1 x Nvidia     | 25        | 22.12%  |
| Intel + Nvidia | 12        | 10.62%  |
| 2 x AMD        | 4         | 3.54%   |
| Other          | 1         | 0.88%   |
| 1 x Matrox     | 1         | 0.88%   |
| AMD + Nvidia   | 1         | 0.88%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 91        | 79.82%  |
| Proprietary | 18        | 15.79%  |
| Unknown     | 5         | 4.39%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 59        | 51.3%   |
| 0.51-1.0   | 13        | 11.3%   |
| 0.01-0.5   | 13        | 11.3%   |
| 7.01-8.0   | 9         | 7.83%   |
| 1.01-2.0   | 7         | 6.09%   |
| 5.01-6.0   | 4         | 3.48%   |
| 3.01-4.0   | 4         | 3.48%   |
| 8.01-16.0  | 4         | 3.48%   |
| 2.01-3.0   | 1         | 0.87%   |
| 16.01-24.0 | 1         | 0.87%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 15        | 12.71%  |
| BOE                     | 15        | 12.71%  |
| AU Optronics            | 10        | 8.47%   |
| Hewlett-Packard         | 9         | 7.63%   |
| Dell                    | 9         | 7.63%   |
| LG Display              | 8         | 6.78%   |
| Goldstar                | 7         | 5.93%   |
| Chimei Innolux          | 7         | 5.93%   |
| BenQ                    | 6         | 5.08%   |
| Sharp                   | 3         | 2.54%   |
| Lenovo                  | 3         | 2.54%   |
| AOC                     | 3         | 2.54%   |
| Ancor Communications    | 3         | 2.54%   |
| Acer                    | 2         | 1.69%   |
| Wacom                   | 1         | 0.85%   |
| Valve                   | 1         | 0.85%   |
| UGD                     | 1         | 0.85%   |
| Sony                    | 1         | 0.85%   |
| Philips                 | 1         | 0.85%   |
| PANDA                   | 1         | 0.85%   |
| MSI                     | 1         | 0.85%   |
| IOD                     | 1         | 0.85%   |
| InnoLux Display         | 1         | 0.85%   |
| Iiyama                  | 1         | 0.85%   |
| Hyundai ImageQuest      | 1         | 0.85%   |
| HKC                     | 1         | 0.85%   |
| GDH                     | 1         | 0.85%   |
| CTC                     | 1         | 0.85%   |
| Chi Mei Optoelectronics | 1         | 0.85%   |
| ASUSTek Computer        | 1         | 0.85%   |
| Apple                   | 1         | 0.85%   |
| Unknown                 | 1         | 0.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC416E 2880x1620 344x194mm 15.5-inch   | 2         | 1.67%   |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch               | 2         | 1.67%   |
| Goldstar ULTRAGEAR GSM7765 2560x1440 697x392mm 31.5-inch                | 2         | 1.67%   |
| Goldstar HDR WQHD GSM7756 3440x1440 820x346mm 35.0-inch                 | 2         | 1.67%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch        | 2         | 1.67%   |
| Wacom Cintiq 22HDT WAC1037 1920x1080 476x268mm 21.5-inch                | 1         | 0.83%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                     | 1         | 0.83%   |
| UGD LCD Monitor UGD1302 1920x1080 290x160mm 13.0-inch                   | 1         | 0.83%   |
| Sony TV SNY8102 1360x768                                                | 1         | 0.83%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 382x215mm 17.3-inch                 | 1         | 0.83%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                 | 1         | 0.83%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch                 | 1         | 0.83%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 700x390mm 31.5-inch       | 1         | 0.83%   |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch     | 1         | 0.83%   |
| Samsung Electronics SyncMaster SAM03F2 1680x1050                        | 1         | 0.83%   |
| Samsung Electronics SyncMaster SAM03F0 1680x1050 433x271mm 20.1-inch    | 1         | 0.83%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 376x301mm 19.0-inch    | 1         | 0.83%   |
| Samsung Electronics SyncMaster SAM01AD 1600x1200 408x306mm 20.1-inch    | 1         | 0.83%   |
| Samsung Electronics SMS27A650 SAM082D 1920x1080 600x340mm 27.2-inch     | 1         | 0.83%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch      | 1         | 0.83%   |
| Samsung Electronics SMEX2220 SAM0686 1920x1080 477x268mm 21.5-inch      | 1         | 0.83%   |
| Samsung Electronics SM2333T SAM0736 1920x1080 477x268mm 21.5-inch       | 1         | 0.83%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch       | 1         | 0.83%   |
| Samsung Electronics LCD Monitor U28D590 3840x2160                       | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch    | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch    | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SAM0FF0 3840x2160 1872x1053mm 84.6-inch | 1         | 0.83%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch                 | 1         | 0.83%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch                 | 1         | 0.83%   |
| MSI MAG342CQPV MSI4DB6 3440x1440 797x333mm 34.0-inch                    | 1         | 0.83%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch            | 1         | 0.83%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch            | 1         | 0.83%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch            | 1         | 0.83%   |
| LG Display LCD Monitor LGD04B9 1920x1080 340x190mm 15.3-inch            | 1         | 0.83%   |
| LG Display LCD Monitor LGD0353 1366x768 345x194mm 15.6-inch             | 1         | 0.83%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch            | 1         | 0.83%   |
| LG Display LCD Monitor LGD028A 1366x768 344x194mm 15.5-inch             | 1         | 0.83%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch             | 1         | 0.83%   |
| Lenovo LEN L171 LEN24C9 1280x1024 337x270mm 17.0-inch                   | 1         | 0.83%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch                 | 1         | 0.83%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 52        | 45.61%  |
| 1366x768 (WXGA)    | 13        | 11.4%   |
| 3840x2160 (4K)     | 7         | 6.14%   |
| 2560x1440 (QHD)    | 5         | 4.39%   |
| 1680x1050 (WSXGA+) | 5         | 4.39%   |
| 1280x1024 (SXGA)   | 5         | 4.39%   |
| 3440x1440          | 4         | 3.51%   |
| 1920x1200 (WUXGA)  | 4         | 3.51%   |
| 1600x900 (HD+)     | 3         | 2.63%   |
| 2880x1620          | 2         | 1.75%   |
| 1440x900 (WXGA+)   | 2         | 1.75%   |
| 1360x768           | 2         | 1.75%   |
| 1280x800 (WXGA)    | 2         | 1.75%   |
| 800x1280           | 1         | 0.88%   |
| 3200x1080          | 1         | 0.88%   |
| 2256x1504          | 1         | 0.88%   |
| 2160x1440          | 1         | 0.88%   |
| 1920x1280          | 1         | 0.88%   |
| 1600x1200          | 1         | 0.88%   |
| 1024x768 (XGA)     | 1         | 0.88%   |
| Unknown            | 1         | 0.88%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 24        | 20.34%  |
| 27      | 14        | 11.86%  |
| 13      | 10        | 8.47%   |
| 14      | 9         | 7.63%   |
| 21      | 8         | 6.78%   |
| 17      | 8         | 6.78%   |
| 24      | 7         | 5.93%   |
| 22      | 4         | 3.39%   |
| 16      | 4         | 3.39%   |
| 31      | 3         | 2.54%   |
| 23      | 3         | 2.54%   |
| 20      | 3         | 2.54%   |
| 19      | 3         | 2.54%   |
| 18      | 3         | 2.54%   |
| Unknown | 3         | 2.54%   |
| 35      | 2         | 1.69%   |
| 34      | 2         | 1.69%   |
| 12      | 2         | 1.69%   |
| 84      | 1         | 0.85%   |
| 72      | 1         | 0.85%   |
| 52      | 1         | 0.85%   |
| 11      | 1         | 0.85%   |
| 10      | 1         | 0.85%   |
| 7       | 1         | 0.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 44        | 37.61%  |
| 501-600     | 22        | 18.8%   |
| 401-500     | 19        | 16.24%  |
| 351-400     | 10        | 8.55%   |
| 201-300     | 7         | 5.98%   |
| 601-700     | 4         | 3.42%   |
| Unknown     | 3         | 2.56%   |
| 801-900     | 2         | 1.71%   |
| 701-800     | 2         | 1.71%   |
| 1501-2000   | 2         | 1.71%   |
| 1001-1500   | 1         | 0.85%   |
| 1-100       | 1         | 0.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 73        | 70.19%  |
| 16/10   | 14        | 13.46%  |
| 5/4     | 5         | 4.81%   |
| 21/9    | 4         | 3.85%   |
| 3/2     | 3         | 2.88%   |
| 4/3     | 2         | 1.92%   |
| Unknown | 2         | 1.92%   |
| 0.67    | 1         | 0.96%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 26        | 22.22%  |
| 81-90          | 17        | 14.53%  |
| 201-250        | 16        | 13.68%  |
| 301-350        | 14        | 11.97%  |
| 151-200        | 9         | 7.69%   |
| 351-500        | 7         | 5.98%   |
| 141-150        | 5         | 4.27%   |
| 121-130        | 5         | 4.27%   |
| More than 1000 | 3         | 2.56%   |
| 251-300        | 3         | 2.56%   |
| Unknown        | 3         | 2.56%   |
| 71-80          | 2         | 1.71%   |
| 61-70          | 2         | 1.71%   |
| 51-60          | 2         | 1.71%   |
| 111-120        | 2         | 1.71%   |
| 1-40           | 1         | 0.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 40        | 35.09%  |
| 121-160       | 33        | 28.95%  |
| 101-120       | 27        | 23.68%  |
| 161-240       | 8         | 7.02%   |
| Unknown       | 3         | 2.63%   |
| 1-50          | 2         | 1.75%   |
| More than 240 | 1         | 0.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 88        | 77.88%  |
| 2     | 14        | 12.39%  |
| 0     | 9         | 7.96%   |
| 4     | 1         | 0.88%   |
| 3     | 1         | 0.88%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 66        | 39.52%  |
| Intel                    | 55        | 32.93%  |
| Qualcomm Atheros         | 9         | 5.39%   |
| MediaTek                 | 8         | 4.79%   |
| Broadcom                 | 7         | 4.19%   |
| Broadcom Limited         | 4         | 2.4%    |
| Ralink Technology        | 3         | 1.8%    |
| Nvidia                   | 3         | 1.8%    |
| ASIX Electronics         | 3         | 1.8%    |
| Qualcomm                 | 2         | 1.2%    |
| TP-Link                  | 1         | 0.6%    |
| Sitecom Europe           | 1         | 0.6%    |
| Ralink                   | 1         | 0.6%    |
| Marvell Technology Group | 1         | 0.6%    |
| Huawei Technologies      | 1         | 0.6%    |
| Hewlett-Packard          | 1         | 0.6%    |
| Dell                     | 1         | 0.6%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 42        | 21%     |
| Intel Wi-Fi 6 AX200                                                    | 9         | 4.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 6         | 3%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 6         | 3%      |
| Realtek RTL8125 2.5GbE Controller                                      | 5         | 2.5%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 5         | 2.5%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 5         | 2.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 2.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4         | 2%      |
| Intel Wireless 8265 / 8275                                             | 4         | 2%      |
| Intel Ethernet Controller I225-V                                       | 4         | 2%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 4         | 2%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 3         | 1.5%    |
| Ralink MT7601U Wireless Adapter                                        | 3         | 1.5%    |
| Intel Wireless 8260                                                    | 3         | 1.5%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 2         | 1%      |
| Realtek Killer E3000 2.5GbE Controller                                 | 2         | 1%      |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2         | 1%      |
| Nvidia MCP61 Ethernet                                                  | 2         | 1%      |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 2         | 1%      |
| Intel Wi-Fi 6 AX201                                                    | 2         | 1%      |
| Intel Tiger Lake PCH CNVi WiFi                                         | 2         | 1%      |
| Intel I211 Gigabit Network Connection                                  | 2         | 1%      |
| Intel Ethernet Connection I219-LM                                      | 2         | 1%      |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 1%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 2         | 1%      |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 2         | 1%      |
| Intel 82577LM Gigabit Network Connection                               | 2         | 1%      |
| Intel 82567LM-3 Gigabit Network Connection                             | 2         | 1%      |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 2         | 1%      |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                        | 2         | 1%      |
| Broadcom Limited BCM43228 802.11a/b/g/n                                | 2         | 1%      |
| ASIX AX88179 Gigabit Ethernet                                          | 2         | 1%      |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 1         | 0.5%    |
| Sitecom Europe WL-113 rev 2 Wireless Network USB Adapter               | 1         | 0.5%    |
| Realtek USB 10/100/1G/2.5G LAN                                         | 1         | 0.5%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 1         | 0.5%    |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller            | 1         | 0.5%    |
| Realtek RTL8723DE Wireless Network Adapter                             | 1         | 0.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 42        | 48.84%  |
| Realtek Semiconductor | 16        | 18.6%   |
| MediaTek              | 8         | 9.3%    |
| Qualcomm Atheros      | 7         | 8.14%   |
| Ralink Technology     | 3         | 3.49%   |
| Broadcom Limited      | 3         | 3.49%   |
| Broadcom              | 2         | 2.33%   |
| TP-Link               | 1         | 1.16%   |
| Sitecom Europe        | 1         | 1.16%   |
| Ralink                | 1         | 1.16%   |
| Qualcomm              | 1         | 1.16%   |
| Dell                  | 1         | 1.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 9         | 10.34%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6         | 6.9%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 5         | 5.75%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 5         | 5.75%   |
| Intel Wireless 8265 / 8275                                     | 4         | 4.6%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 4.6%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 3.45%   |
| Ralink MT7601U Wireless Adapter                                | 3         | 3.45%   |
| Intel Wireless 8260                                            | 3         | 3.45%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 2         | 2.3%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 2         | 2.3%    |
| Intel Wi-Fi 6 AX201                                            | 2         | 2.3%    |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 2.3%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 2.3%    |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 2.3%    |
| Broadcom Limited BCM43228 802.11a/b/g/n                        | 2         | 2.3%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 1.15%   |
| Sitecom Europe WL-113 rev 2 Wireless Network USB Adapter       | 1         | 1.15%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 1.15%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller    | 1         | 1.15%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 1.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 1.15%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 1.15%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 1.15%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 1         | 1.15%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 1         | 1.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 1.15%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 1.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 1.15%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 1.15%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1         | 1.15%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 1.15%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 1         | 1.15%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 1.15%   |
| Intel Wireless 7260                                            | 1         | 1.15%   |
| Intel Wireless 3165                                            | 1         | 1.15%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 1         | 1.15%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 1         | 1.15%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 1         | 1.15%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 1.15%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 60        | 54.55%  |
| Intel                    | 31        | 28.18%  |
| Broadcom                 | 6         | 5.45%   |
| Qualcomm Atheros         | 3         | 2.73%   |
| Nvidia                   | 3         | 2.73%   |
| ASIX Electronics         | 3         | 2.73%   |
| Qualcomm                 | 1         | 0.91%   |
| Marvell Technology Group | 1         | 0.91%   |
| Huawei Technologies      | 1         | 0.91%   |
| Broadcom Limited         | 1         | 0.91%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 42        | 37.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 6         | 5.36%   |
| Realtek RTL8125 2.5GbE Controller                                      | 5         | 4.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 4.46%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4         | 3.57%   |
| Intel Ethernet Controller I225-V                                       | 4         | 3.57%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 2         | 1.79%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2         | 1.79%   |
| Nvidia MCP61 Ethernet                                                  | 2         | 1.79%   |
| Intel I211 Gigabit Network Connection                                  | 2         | 1.79%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 1.79%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 1.79%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 1.79%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 2         | 1.79%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 2         | 1.79%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                        | 2         | 1.79%   |
| ASIX AX88179 Gigabit Ethernet                                          | 2         | 1.79%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 1         | 0.89%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.89%   |
| Qualcomm Nokia G42 5G                                                  | 1         | 0.89%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.89%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.89%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 1         | 0.89%   |
| Intel I350 Gigabit Network Connection                                  | 1         | 0.89%   |
| Intel Ethernet Connection (7) I219-V                                   | 1         | 0.89%   |
| Intel Ethernet Connection (5) I219-V                                   | 1         | 0.89%   |
| Intel Ethernet Connection (2) I219-V                                   | 1         | 0.89%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 0.89%   |
| Intel Ethernet Connection (2) I218-V                                   | 1         | 0.89%   |
| Intel Ethernet Connection (2) I218-LM                                  | 1         | 0.89%   |
| Intel Ethernet Connection (16) I219-LM                                 | 1         | 0.89%   |
| Intel Ethernet Connection (12) I219-V                                  | 1         | 0.89%   |
| Intel 82576 Gigabit Network Connection                                 | 1         | 0.89%   |
| Intel 82574L Gigabit Network Connection                                | 1         | 0.89%   |
| Intel 82566MM Gigabit Network Connection                               | 1         | 0.89%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                   | 1         | 0.89%   |
| Huawei E353/E3131                                                      | 1         | 0.89%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 1         | 0.89%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 1         | 0.89%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express        | 1         | 0.89%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 102       | 54.26%  |
| WiFi     | 85        | 45.21%  |
| Modem    | 1         | 0.53%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 62        | 52.1%   |
| Ethernet | 57        | 47.9%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 61        | 53.51%  |
| 1     | 46        | 40.35%  |
| 3     | 3         | 2.63%   |
| 4     | 2         | 1.75%   |
| 5     | 1         | 0.88%   |
| 0     | 1         | 0.88%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 94        | 82.46%  |
| Yes  | 20        | 17.54%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 35        | 46.05%  |
| Realtek Semiconductor           | 10        | 13.16%  |
| MediaTek                        | 6         | 7.89%   |
| Cambridge Silicon Radio         | 6         | 7.89%   |
| Broadcom                        | 6         | 7.89%   |
| IMC Networks                    | 4         | 5.26%   |
| Qualcomm Atheros Communications | 2         | 2.63%   |
| Foxconn / Hon Hai               | 2         | 2.63%   |
| Apple                           | 2         | 2.63%   |
| USI                             | 1         | 1.32%   |
| TP-Link                         | 1         | 1.32%   |
| Micro Star International        | 1         | 1.32%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                                | 8         | 10.53%  |
| Intel Bluetooth Device                               | 7         | 9.21%   |
| Intel AX201 Bluetooth                                | 7         | 9.21%   |
| MediaTek Wireless_Device                             | 6         | 7.89%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)  | 6         | 7.89%   |
| Intel AX210 Bluetooth                                | 5         | 6.58%   |
| Realtek  Bluetooth 4.2 Adapter                       | 4         | 5.26%   |
| Realtek Bluetooth Radio                              | 4         | 5.26%   |
| Intel Bluetooth wireless interface                   | 3         | 3.95%   |
| IMC Networks Wireless_Device                         | 3         | 3.95%   |
| Intel Wireless-AC 3168 Bluetooth                     | 2         | 2.63%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]           | 2         | 2.63%   |
| USI Bluetooth Device                                 | 1         | 1.32%   |
| TP-Link UB500 Adapter                                | 1         | 1.32%   |
| Realtek RTL8723B Bluetooth                           | 1         | 1.32%   |
| Realtek 802.11ac WLAN Adapter                        | 1         | 1.32%   |
| Qualcomm Atheros  Bluetooth Device                   | 1         | 1.32%   |
| Qualcomm Atheros Dell Wireless 1802 Bluetooth 4.0 LE | 1         | 1.32%   |
| Micro Star International Bluetooth Dongle            | 1         | 1.32%   |
| Intel Wireless-AC 9260 Bluetooth Adapter             | 1         | 1.32%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)       | 1         | 1.32%   |
| Intel AX211 Bluetooth                                | 1         | 1.32%   |
| IMC Networks Bluetooth Radio                         | 1         | 1.32%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller      | 1         | 1.32%   |
| Foxconn / Hon Hai Bluetooth Device                   | 1         | 1.32%   |
| Broadcom HP Portable SoftSailing                     | 1         | 1.32%   |
| Broadcom BCM20702A0 Bluetooth 4.0                    | 1         | 1.32%   |
| Broadcom BCM20702A0                                  | 1         | 1.32%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]     | 1         | 1.32%   |
| Apple Bluetooth USB Host Controller                  | 1         | 1.32%   |
| Apple Bluetooth HCI MacBookPro (HID mode)            | 1         | 1.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 63        | 39.62%  |
| AMD                      | 45        | 28.3%   |
| Nvidia                   | 33        | 20.75%  |
| Creative Labs            | 5         | 3.14%   |
| Micro Star International | 3         | 1.89%   |
| C-Media Electronics      | 3         | 1.89%   |
| ASUSTek Computer         | 2         | 1.26%   |
| Texas Instruments        | 1         | 0.63%   |
| RME                      | 1         | 0.63%   |
| Kingston Technology      | 1         | 0.63%   |
| Holtek Semiconductor     | 1         | 0.63%   |
| Generalplus Technology   | 1         | 0.63%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 20        | 10.05%  |
| AMD Starship/Matisse HD Audio Controller                                                          | 10        | 5.03%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 4.02%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 4.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 4.02%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7         | 3.52%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 2.51%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 5         | 2.51%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 2.51%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 5         | 2.51%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 2.01%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 2.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 2.01%   |
| AMD Navi 31 HDMI/DP Audio                                                                         | 4         | 2.01%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 4         | 2.01%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.51%   |
| Nvidia MCP61 High Definition Audio                                                                | 3         | 1.51%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 1.51%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.51%   |
| Nvidia Audio device                                                                               | 3         | 1.51%   |
| Micro Star International USB Audio                                                                | 3         | 1.51%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.51%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1.51%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 1.51%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus]   | 3         | 1.51%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.51%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 3         | 1.51%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 1.01%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 1.01%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 1.01%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 2         | 1.01%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.01%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.01%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2         | 1.01%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.01%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 1.01%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.01%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 1.01%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 1.01%   |
| AMD Navi 10 HDMI Audio                                                                            | 2         | 1.01%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 20        | 18.02%  |
| Kingston            | 17        | 15.32%  |
| SK hynix            | 16        | 14.41%  |
| Corsair             | 11        | 9.91%   |
| Crucial             | 8         | 7.21%   |
| Micron Technology   | 7         | 6.31%   |
| Unknown             | 5         | 4.5%    |
| G.Skill             | 5         | 4.5%    |
| A-DATA Technology   | 3         | 2.7%    |
| Unknown             | 3         | 2.7%    |
| Team                | 2         | 1.8%    |
| GOODRAM             | 2         | 1.8%    |
| AMD                 | 2         | 1.8%    |
| Transcend           | 1         | 0.9%    |
| Strontium           | 1         | 0.9%    |
| Smart               | 1         | 0.9%    |
| Silicon Power       | 1         | 0.9%    |
| Patriot             | 1         | 0.9%    |
| Neo Forza           | 1         | 0.9%    |
| Nanya Technology    | 1         | 0.9%    |
| Innodisk            | 1         | 0.9%    |
| GLOWAY              | 1         | 0.9%    |
| Essencore Limited   | 1         | 0.9%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 2.44%   |
| Unknown                                                          | 3         | 2.44%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 2         | 1.63%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 2         | 1.63%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.63%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 2         | 1.63%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM 4800MT/s               | 2         | 1.63%   |
| Corsair RAM CMSX32GX4M2A2666C18 16GB SODIMM DDR4 2667MT/s        | 2         | 1.63%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 2         | 1.63%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                         | 1         | 0.81%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.81%   |
| Unknown RAM Module 2GB DIMM DDR2 533MT/s                         | 1         | 0.81%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                         | 1         | 0.81%   |
| Transcend RAM JM1600KLN-8GK 4096MB DIMM DDR3 1600MT/s            | 1         | 0.81%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3733MT/s              | 1         | 0.81%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s               | 1         | 0.81%   |
| Strontium RAM SRT4G86U1-P9H 4096MB DIMM DDR3 1333MT/s            | 1         | 0.81%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s              | 1         | 0.81%   |
| SK hynix RAM HYMP512F72CP8N3-Y5 1024MB FB-DIMM DDR2 667MT/s      | 1         | 0.81%   |
| SK hynix RAM HMT41GV7BMR4A-H9 8GB DIMM 1333MT/s                  | 1         | 0.81%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.81%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s             | 1         | 0.81%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.81%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.81%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.81%   |
| SK hynix RAM HMT31GR7BFR4A-H9 8192MB DIMM 1333MT/s               | 1         | 0.81%   |
| SK hynix RAM HMT125R7BFR8C-H9 2GB DIMM 1333MT/s                  | 1         | 0.81%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.81%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.81%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 0.81%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 0.81%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 0.81%   |
| SK hynix RAM HMA81GR7CJR8N-XN 8GB DIMM DDR4 3200MT/s             | 1         | 0.81%   |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 0.81%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB SODIMM LPDDR3 1867MT/s           | 1         | 0.81%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB Chip LPDDR3 1867MT/s             | 1         | 0.81%   |
| Silicon Power RAM DCLT4GN568S V 4096MB DIMM DDR3 1600MT/s        | 1         | 0.81%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 0.81%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 1         | 0.81%   |
| Samsung RAM M471B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.81%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 50        | 52.63%  |
| DDR3    | 27        | 28.42%  |
| DDR2    | 4         | 4.21%   |
| LPDDR5  | 3         | 3.16%   |
| LPDDR3  | 3         | 3.16%   |
| DDR5    | 3         | 3.16%   |
| SDRAM   | 2         | 2.11%   |
| LPDDR4  | 1         | 1.05%   |
| DDR     | 1         | 1.05%   |
| Unknown | 1         | 1.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 45        | 46.88%  |
| DIMM         | 42        | 43.75%  |
| Row Of Chips | 6         | 6.25%   |
| RIMM         | 1         | 1.04%   |
| FB-DIMM      | 1         | 1.04%   |
| Chip         | 1         | 1.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 44        | 41.12%  |
| 4096  | 27        | 25.23%  |
| 16384 | 19        | 17.76%  |
| 2048  | 9         | 8.41%   |
| 32768 | 6         | 5.61%   |
| 1024  | 2         | 1.87%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 22        | 20.56%  |
| 1600    | 19        | 17.76%  |
| 2667    | 8         | 7.48%   |
| 2400    | 8         | 7.48%   |
| 1333    | 6         | 5.61%   |
| 3600    | 5         | 4.67%   |
| 2133    | 4         | 3.74%   |
| 4800    | 3         | 2.8%    |
| 3800    | 3         | 2.8%    |
| 1867    | 3         | 2.8%    |
| 1334    | 3         | 2.8%    |
| 6400    | 2         | 1.87%   |
| 3733    | 2         | 1.87%   |
| 667     | 2         | 1.87%   |
| 533     | 2         | 1.87%   |
| Unknown | 2         | 1.87%   |
| 65535   | 1         | 0.93%   |
| 4267    | 1         | 0.93%   |
| 4266    | 1         | 0.93%   |
| 3666    | 1         | 0.93%   |
| 3400    | 1         | 0.93%   |
| 3000    | 1         | 0.93%   |
| 2933    | 1         | 0.93%   |
| 2800    | 1         | 0.93%   |
| 2472    | 1         | 0.93%   |
| 2187    | 1         | 0.93%   |
| 1866    | 1         | 0.93%   |
| 975     | 1         | 0.93%   |
| 701     | 1         | 0.93%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| QinHeng Electronics | 2         | 33.33%  |
| Hewlett-Packard     | 1         | 16.67%  |
| Dell                | 1         | 16.67%  |
| Canon               | 1         | 16.67%  |
| Brother Industries  | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                        | Computers | Percent |
|------------------------------|-----------|---------|
| QinHeng CH340S               | 2         | 33.33%  |
| HP OfficeJet Pro 9010 series | 1         | 16.67%  |
| Dell 2330d Laser Printer     | 1         | 16.67%  |
| Canon LiDE 300               | 1         | 16.67%  |
| Brother HL-L5102DW           | 1         | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Canon       | 2         | 66.67%  |
| Seiko Epson | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1         | 33.33%  |
| Canon CanoScan N670U/N676U/LiDE 20            | 1         | 33.33%  |
| Canon CanoScan LIDE 25                        | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 14        | 21.88%  |
| Bison Electronics                      | 9         | 14.06%  |
| Logitech                               | 8         | 12.5%   |
| Realtek Semiconductor                  | 5         | 7.81%   |
| Microdia                               | 5         | 7.81%   |
| Syntek                                 | 3         | 4.69%   |
| Sonix Technology                       | 3         | 4.69%   |
| Luxvisions Innotech Limited            | 3         | 4.69%   |
| Sunplus Innovation Technology          | 2         | 3.13%   |
| Samsung Electronics                    | 2         | 3.13%   |
| Quanta                                 | 2         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.13%   |
| Acer                                   | 2         | 3.13%   |
| Z-Star Microelectronics                | 1         | 1.56%   |
| Microsoft                              | 1         | 1.56%   |
| Lenovo                                 | 1         | 1.56%   |
| Apple                                  | 1         | 1.56%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Bison HD Webcam                                      | 4         | 6.25%   |
| Logitech Webcam C270                                 | 3         | 4.69%   |
| Chicony Integrated Camera                            | 3         | 4.69%   |
| Bison BisonCam,NB Pro                                | 3         | 4.69%   |
| Syntek Integrated Camera                             | 2         | 3.13%   |
| Sonix USB2.0 FHD UVC WebCam                          | 2         | 3.13%   |
| Samsung Galaxy series, misc. (MTP mode)              | 2         | 3.13%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 2         | 3.13%   |
| Chicony HD User Facing                               | 2         | 3.13%   |
| Acer Integrated Camera                               | 2         | 3.13%   |
| Z-Star Vimicro USB2.0 Camera                         | 1         | 1.56%   |
| Syntek USB2.0 Camera                                 | 1         | 1.56%   |
| Sunplus PC Camera                                    | 1         | 1.56%   |
| Sunplus Integrated_Webcam_HD                         | 1         | 1.56%   |
| Sonix USB2.0 HD UVC WebCam                           | 1         | 1.56%   |
| Realtek Laptop Camera                                | 1         | 1.56%   |
| Realtek Integrated_Webcam_HD                         | 1         | 1.56%   |
| Realtek Integrated Camera                            | 1         | 1.56%   |
| Realtek EasyCamera                                   | 1         | 1.56%   |
| Realtek Bluetooth Radio                              | 1         | 1.56%   |
| Quanta HP Wide Vision HD Camera                      | 1         | 1.56%   |
| Quanta HP Webcam                                     | 1         | 1.56%   |
| Microsoft LifeCam HD-3000                            | 1         | 1.56%   |
| Microdia Laptop_Integrated_Webcam_2M                 | 1         | 1.56%   |
| Microdia Integrated_Webcam_HD                        | 1         | 1.56%   |
| Microdia Integrated Webcam                           | 1         | 1.56%   |
| Microdia Dell Integrated HD Webcam                   | 1         | 1.56%   |
| Microdia Camera                                      | 1         | 1.56%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.56%   |
| Logitech QuickCam Pro 9000                           | 1         | 1.56%   |
| Logitech Logitech Webcam C160                        | 1         | 1.56%   |
| Logitech HD Webcam C910                              | 1         | 1.56%   |
| Logitech C922 Pro Stream Webcam                      | 1         | 1.56%   |
| Logitech C920 PRO HD Webcam                          | 1         | 1.56%   |
| Lenovo Integrated Webcam [R5U877]                    | 1         | 1.56%   |
| Chicony Web Camera - FHD                             | 1         | 1.56%   |
| Chicony Integrated Camera [ThinkPad]                 | 1         | 1.56%   |
| Chicony Integrated Camera (1280x720@30)              | 1         | 1.56%   |
| Chicony HP TrueVision HD Camera                      | 1         | 1.56%   |
| Chicony HP True Vision 5MP Camera                    | 1         | 1.56%   |

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
| Alcor Micro | 2         | 40%     |
| Upek        | 1         | 20%     |
| Lenovo      | 1         | 20%     |
| Broadcom    | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 2         | 40%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 20%     |
| Lenovo Integrated Smart Card Reader                        | 1         | 20%     |
| Broadcom 5880                                              | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 71        | 60.68%  |
| 1     | 30        | 25.64%  |
| 2     | 10        | 8.55%   |
| 4     | 3         | 2.56%   |
| 3     | 2         | 1.71%   |
| 5     | 1         | 0.85%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 14        | 20.59%  |
| Sound                    | 11        | 16.18%  |
| Graphics card            | 11        | 16.18%  |
| Net/wireless             | 9         | 13.24%  |
| Multimedia controller    | 5         | 7.35%   |
| Chipcard                 | 4         | 5.88%   |
| Unassigned class         | 3         | 4.41%   |
| Communication controller | 3         | 4.41%   |
| Camera                   | 3         | 4.41%   |
| Bluetooth                | 2         | 2.94%   |
| Storage/raid             | 1         | 1.47%   |
| Storage/ide              | 1         | 1.47%   |
| Net/ethernet             | 1         | 1.47%   |

