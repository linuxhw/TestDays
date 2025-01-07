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

Total: 259

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [7ab225644f](https://linux-hardware.org/?probe=7ab225644f) | Dec 29, 2024 |
| HP            | 8643 SMVB                   | Desktop     | [3e1d8b1c0f](https://linux-hardware.org/?probe=3e1d8b1c0f) | Dec 29, 2024 |
| HP            | 8906 SMVB                   | Desktop     | [f52f996dd7](https://linux-hardware.org/?probe=f52f996dd7) | Dec 29, 2024 |
| HP            | 1495                        | Desktop     | [0accce2a1a](https://linux-hardware.org/?probe=0accce2a1a) | Dec 29, 2024 |
| Dell          | 0X4N41 A01                  | Desktop     | [3aca8429ec](https://linux-hardware.org/?probe=3aca8429ec) | Dec 28, 2024 |
| HP            | 1495                        | Desktop     | [309b63cf7b](https://linux-hardware.org/?probe=309b63cf7b) | Dec 28, 2024 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [2e065da895](https://linux-hardware.org/?probe=2e065da895) | Dec 26, 2024 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [22428153ea](https://linux-hardware.org/?probe=22428153ea) | Dec 19, 2024 |
| ASUSTek       | TUF Gaming H770-PRO WIFI    | Desktop     | [8e7f03f349](https://linux-hardware.org/?probe=8e7f03f349) | Dec 07, 2024 |
| BESSTAR Te... | CB9                         | Mini pc     | [0bee319571](https://linux-hardware.org/?probe=0bee319571) | Dec 02, 2024 |
| Supermicro    | X9DRD-7LN4F                 | Server      | [18e84eac28](https://linux-hardware.org/?probe=18e84eac28) | Oct 11, 2024 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [302ff2daa0](https://linux-hardware.org/?probe=302ff2daa0) | Sep 11, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [ba32f5b55e](https://linux-hardware.org/?probe=ba32f5b55e) | Aug 26, 2024 |
| MSI           | B450M BAZOOKA MAX WIFI      | Desktop     | [fffa528570](https://linux-hardware.org/?probe=fffa528570) | Aug 07, 2024 |
| HP            | Pavilion g6                 | Notebook    | [8d4cd1cce3](https://linux-hardware.org/?probe=8d4cd1cce3) | Jul 25, 2024 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [f7b2ff4d05](https://linux-hardware.org/?probe=f7b2ff4d05) | Jul 17, 2024 |
| ASUSTek       | PRIME B760M-A D4            | Desktop     | [23f34741b6](https://linux-hardware.org/?probe=23f34741b6) | Jun 17, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [66de5464ad](https://linux-hardware.org/?probe=66de5464ad) | Jun 07, 2024 |
| Lenovo        | Yoga 6 13ABR8 83B2          | Convertible | [db24ee42b0](https://linux-hardware.org/?probe=db24ee42b0) | May 25, 2024 |
| HP            | OMEN by Laptop 16-b1xxx     | Notebook    | [63bafff3a1](https://linux-hardware.org/?probe=63bafff3a1) | May 25, 2024 |
| Dynabook      | PORTEGE X50-G               | Notebook    | [995067b4e8](https://linux-hardware.org/?probe=995067b4e8) | May 22, 2024 |
| ASRock        | B550M-HDV                   | Desktop     | [eb41f5c32d](https://linux-hardware.org/?probe=eb41f5c32d) | May 15, 2024 |
| Dell          | 0X9M3X A04                  | Desktop     | [4b6904a00b](https://linux-hardware.org/?probe=4b6904a00b) | May 13, 2024 |
| Lenovo        | ThinkPad X201 3626F7U       | Notebook    | [40e1a8f2e0](https://linux-hardware.org/?probe=40e1a8f2e0) | May 10, 2024 |
| Lenovo        | ThinkPad X201 3626F7U       | Notebook    | [44b7fec8f8](https://linux-hardware.org/?probe=44b7fec8f8) | May 10, 2024 |
| Lenovo        | ThinkPad T430s 2355CL4      | Notebook    | [b90ab4a6e2](https://linux-hardware.org/?probe=b90ab4a6e2) | May 07, 2024 |
| Lenovo        | ThinkPad T16 Gen 2 21K7C... | Notebook    | [29f2579a02](https://linux-hardware.org/?probe=29f2579a02) | Apr 27, 2024 |
| Dell          | Precision 7510              | Notebook    | [23916f1909](https://linux-hardware.org/?probe=23916f1909) | Apr 22, 2024 |
| BESSTAR Te... | CB9                         | Mini pc     | [ddd433c51c](https://linux-hardware.org/?probe=ddd433c51c) | Apr 21, 2024 |
| Chuwi         | UBook X                     | Convertible | [1b5a7adcb3](https://linux-hardware.org/?probe=1b5a7adcb3) | Apr 20, 2024 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [37bd870888](https://linux-hardware.org/?probe=37bd870888) | Apr 19, 2024 |
| Lenovo        | 3130 SDK0J40700 WIN 3258... | Mini pc     | [5256952fc5](https://linux-hardware.org/?probe=5256952fc5) | Apr 17, 2024 |
| Lenovo        | ThinkPad T430s 2355CL4      | Notebook    | [e680816d8a](https://linux-hardware.org/?probe=e680816d8a) | Mar 13, 2024 |
| Dell          | XPS 15 9520                 | Notebook    | [2b4c310e2d](https://linux-hardware.org/?probe=2b4c310e2d) | Mar 08, 2024 |
| MSI           | Modern 14 B5M               | Notebook    | [585c473256](https://linux-hardware.org/?probe=585c473256) | Mar 08, 2024 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [7204492392](https://linux-hardware.org/?probe=7204492392) | Mar 05, 2024 |
| MSI           | PRO X670-P WIFI             | Desktop     | [0ef39f433d](https://linux-hardware.org/?probe=0ef39f433d) | Feb 27, 2024 |
| Dell          | Inspiron 5570               | Notebook    | [a16622f44c](https://linux-hardware.org/?probe=a16622f44c) | Feb 25, 2024 |
| Dell          | XPS 13 9370                 | Notebook    | [e94228e06b](https://linux-hardware.org/?probe=e94228e06b) | Feb 22, 2024 |
| Notebook      | NL5xNU                      | Notebook    | [e83f0b4085](https://linux-hardware.org/?probe=e83f0b4085) | Feb 18, 2024 |
| Dell          | XPS 15 9520                 | Notebook    | [d29869043d](https://linux-hardware.org/?probe=d29869043d) | Feb 17, 2024 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [2ed279c40d](https://linux-hardware.org/?probe=2ed279c40d) | Feb 16, 2024 |
| ASRock        | B550M-ITX/ac                | Desktop     | [27015117d0](https://linux-hardware.org/?probe=27015117d0) | Feb 13, 2024 |
| Dell          | XPS 13 9370                 | Notebook    | [11b5a42b88](https://linux-hardware.org/?probe=11b5a42b88) | Feb 11, 2024 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [6ae9e4d70e](https://linux-hardware.org/?probe=6ae9e4d70e) | Feb 06, 2024 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [f536b283c6](https://linux-hardware.org/?probe=f536b283c6) | Jan 27, 2024 |
| HP            | 17E2                        | Mini pc     | [d382ed2027](https://linux-hardware.org/?probe=d382ed2027) | Jan 22, 2024 |
| HP            | ProLiant ML110 Gen9         | Desktop     | [ec93a55951](https://linux-hardware.org/?probe=ec93a55951) | Jan 19, 2024 |
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

![OS](./All/images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Slackware 15.0  | 130       | 63.73%  |
| Slackware 14.2  | 63        | 30.88%  |
| Slackware 14.2+ | 7         | 3.43%   |
| Slackware 15.0+ | 3         | 1.47%   |
| Slackware 14.1  | 1         | 0.49%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Slackware | 201       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 5.15.19                     | 22        | 9.91%   |
| 4.19.80                     | 8         | 3.6%    |
| 5.19.17                     | 7         | 3.15%   |
| 5.15.63                     | 7         | 3.15%   |
| 5.15.145                    | 6         | 2.7%    |
| 5.10.28-Unraid              | 6         | 2.7%    |
| 5.19.17-Unraid              | 4         | 1.8%    |
| 5.15.27                     | 4         | 1.8%    |
| 5.15.117                    | 4         | 1.8%    |
| 4.4.190                     | 4         | 1.8%    |
| 5.15.94                     | 3         | 1.35%   |
| 5.15.38                     | 3         | 1.35%   |
| 4.4.240                     | 3         | 1.35%   |
| 6.6.22                      | 2         | 0.9%    |
| 6.6.18                      | 2         | 0.9%    |
| 6.12.7                      | 2         | 0.9%    |
| 6.12.1                      | 2         | 0.9%    |
| 6.1.79-Unraid               | 2         | 0.9%    |
| 6.1.64-Unraid               | 2         | 0.9%    |
| 6.1.44                      | 2         | 0.9%    |
| 5.3.7                       | 2         | 0.9%    |
| 5.17.2                      | 2         | 0.9%    |
| 5.17.1                      | 2         | 0.9%    |
| 5.16.13                     | 2         | 0.9%    |
| 5.15.80                     | 2         | 0.9%    |
| 5.15.30-Unraid              | 2         | 0.9%    |
| 5.15.118                    | 2         | 0.9%    |
| 5.13.8                      | 2         | 0.9%    |
| 5.10.3                      | 2         | 0.9%    |
| 4.4.276                     | 2         | 0.9%    |
| 6.9.12                      | 1         | 0.45%   |
| 6.9.1                       | 1         | 0.45%   |
| 6.8.8                       | 1         | 0.45%   |
| 6.7.5-gsh-clevo-NL51NU-SW15 | 1         | 0.45%   |
| 6.7.4-cometdust             | 1         | 0.45%   |
| 6.6.8                       | 1         | 0.45%   |
| 6.6.7                       | 1         | 0.45%   |
| 6.6.28                      | 1         | 0.45%   |
| 6.6.26                      | 1         | 0.45%   |
| 6.6.21                      | 1         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.19  | 22        | 9.91%   |
| 5.19.17  | 11        | 4.95%   |
| 4.19.80  | 8         | 3.6%    |
| 5.15.63  | 7         | 3.15%   |
| 5.15.145 | 6         | 2.7%    |
| 5.10.28  | 6         | 2.7%    |
| 4.4.190  | 5         | 2.25%   |
| 5.15.27  | 4         | 1.8%    |
| 5.15.117 | 4         | 1.8%    |
| 5.15.94  | 3         | 1.35%   |
| 5.15.38  | 3         | 1.35%   |
| 4.4.240  | 3         | 1.35%   |
| 6.6.22   | 2         | 0.9%    |
| 6.6.18   | 2         | 0.9%    |
| 6.12.7   | 2         | 0.9%    |
| 6.12.1   | 2         | 0.9%    |
| 6.1.79   | 2         | 0.9%    |
| 6.1.64   | 2         | 0.9%    |
| 6.1.44   | 2         | 0.9%    |
| 5.3.7    | 2         | 0.9%    |
| 5.17.2   | 2         | 0.9%    |
| 5.17.1   | 2         | 0.9%    |
| 5.16.13  | 2         | 0.9%    |
| 5.15.80  | 2         | 0.9%    |
| 5.15.30  | 2         | 0.9%    |
| 5.15.118 | 2         | 0.9%    |
| 5.14.15  | 2         | 0.9%    |
| 5.13.8   | 2         | 0.9%    |
| 5.10.3   | 2         | 0.9%    |
| 4.4.276  | 2         | 0.9%    |
| 6.9.12   | 1         | 0.45%   |
| 6.9.1    | 1         | 0.45%   |
| 6.8.8    | 1         | 0.45%   |
| 6.7.5    | 1         | 0.45%   |
| 6.7.4    | 1         | 0.45%   |
| 6.6.8    | 1         | 0.45%   |
| 6.6.7    | 1         | 0.45%   |
| 6.6.28   | 1         | 0.45%   |
| 6.6.26   | 1         | 0.45%   |
| 6.6.21   | 1         | 0.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 68        | 31.19%  |
| 4.4     | 17        | 7.8%    |
| 5.10    | 15        | 6.88%   |
| 4.19    | 15        | 6.88%   |
| 6.1     | 13        | 5.96%   |
| 5.4     | 13        | 5.96%   |
| 5.19    | 12        | 5.5%    |
| 6.6     | 10        | 4.59%   |
| 5.14    | 7         | 3.21%   |
| 5.13    | 7         | 3.21%   |
| 5.17    | 6         | 2.75%   |
| 5.16    | 6         | 2.75%   |
| 6.12    | 5         | 2.29%   |
| 6.10    | 4         | 1.83%   |
| 6.9     | 2         | 0.92%   |
| 6.7     | 2         | 0.92%   |
| 6.11    | 2         | 0.92%   |
| 5.3     | 2         | 0.92%   |
| 4.9     | 2         | 0.92%   |
| 6.8     | 1         | 0.46%   |
| 6.5     | 1         | 0.46%   |
| 6.4     | 1         | 0.46%   |
| 5.7     | 1         | 0.46%   |
| 5.5     | 1         | 0.46%   |
| 5.2     | 1         | 0.46%   |
| 5.12    | 1         | 0.46%   |
| 4.20    | 1         | 0.46%   |
| 4.16    | 1         | 0.46%   |
| 3.10    | 1         | 0.46%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 198       | 98.51%  |
| aarch64 | 2         | 1%      |
| i686    | 1         | 0.5%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 62        | 30.1%   |
| XFCE          | 61        | 29.61%  |
| KDE5          | 58        | 28.16%  |
| KDE           | 5         | 2.43%   |
| MATE          | 4         | 1.94%   |
| GNOME         | 4         | 1.94%   |
| xwmconfig     | 2         | 0.97%   |
| FVWM          | 2         | 0.97%   |
| X-Generic     | 1         | 0.49%   |
| X-Cinnamon    | 1         | 0.49%   |
| LXQt          | 1         | 0.49%   |
| Enlightenment | 1         | 0.49%   |
| DWM           | 1         | 0.49%   |
| Cinnamon      | 1         | 0.49%   |
| awesome       | 1         | 0.49%   |
| 2bwm          | 1         | 0.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 120       | 57.42%  |
| Tty     | 59        | 28.23%  |
| Unknown | 19        | 9.09%   |
| Wayland | 11        | 5.26%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 78        | 37.5%   |
| SDDM    | 68        | 32.69%  |
| XDM     | 48        | 23.08%  |
| LightDM | 6         | 2.88%   |
| SLiM    | 5         | 2.4%    |
| GDM     | 2         | 0.96%   |
| TDM     | 1         | 0.48%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 115       | 56.93%  |
| Unknown     | 46        | 22.77%  |
| it_IT       | 8         | 3.96%   |
| ru_RU       | 5         | 2.48%   |
| pt_BR       | 4         | 1.98%   |
| en_GB       | 4         | 1.98%   |
| fr_FR       | 3         | 1.49%   |
| de_DE       | 3         | 1.49%   |
| cs_CZ       | 2         | 0.99%   |
| zh_TW       | 1         | 0.5%    |
| us          | 1         | 0.5%    |
| sr_RS@latin | 1         | 0.5%    |
| pt_PT       | 1         | 0.5%    |
| pl_PL       | 1         | 0.5%    |
| ja_JP       | 1         | 0.5%    |
| es_ES.UTF8  | 1         | 0.5%    |
| es_ES       | 1         | 0.5%    |
| en_US.ASCII | 1         | 0.5%    |
| en_SE       | 1         | 0.5%    |
| en_AU       | 1         | 0.5%    |
| C           | 1         | 0.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 104       | 51.23%  |
| BIOS | 99        | 48.77%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 149       | 73.4%   |
| Btrfs    | 21        | 10.34%  |
| Xfs      | 8         | 3.94%   |
| Overlay  | 8         | 3.94%   |
| Rootfs   | 7         | 3.45%   |
| Tmpfs    | 2         | 0.99%   |
| Reiserfs | 2         | 0.99%   |
| Jfs      | 2         | 0.99%   |
| Zfs      | 1         | 0.49%   |
| F2fs     | 1         | 0.49%   |
| Ext3     | 1         | 0.49%   |
| Ext2     | 1         | 0.49%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 134       | 65.37%  |
| MBR     | 47        | 22.93%  |
| Unknown | 24        | 11.71%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 141       | 68.78%  |
| Yes       | 64        | 31.22%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 140       | 69.31%  |
| Yes       | 62        | 30.69%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 34        | 16.92%  |
| Hewlett-Packard     | 33        | 16.42%  |
| Lenovo              | 27        | 13.43%  |
| Dell                | 21        | 10.45%  |
| MSI                 | 19        | 9.45%   |
| ASRock              | 13        | 6.47%   |
| Gigabyte Technology | 9         | 4.48%   |
| Acer                | 7         | 3.48%   |
| Toshiba             | 4         | 1.99%   |
| Notebook            | 4         | 1.99%   |
| Fujitsu             | 3         | 1.49%   |
| Supermicro          | 2         | 1%      |
| Dynabook            | 2         | 1%      |
| Apple               | 2         | 1%      |
| Unknown             | 2         | 1%      |
| Valve               | 1         | 0.5%    |
| TYAN Computer       | 1         | 0.5%    |
| System76            | 1         | 0.5%    |
| Sony                | 1         | 0.5%    |
| Shuttle             | 1         | 0.5%    |
| Samsung Electronics | 1         | 0.5%    |
| Radxa               | 1         | 0.5%    |
| NetGear             | 1         | 0.5%    |
| Microsoft           | 1         | 0.5%    |
| Intel               | 1         | 0.5%    |
| Huanan              | 1         | 0.5%    |
| HPE                 | 1         | 0.5%    |
| HEDYCOMPUTER        | 1         | 0.5%    |
| Framework           | 1         | 0.5%    |
| Foxconn             | 1         | 0.5%    |
| Chuwi               | 1         | 0.5%    |
| Biostar             | 1         | 0.5%    |
| BESSTAR Tech        | 1         | 0.5%    |
| AMI                 | 1         | 0.5%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| ASUS All Series                          | 4         | 1.99%   |
| Toshiba Satellite C660                   | 2         | 1%      |
| MSI MS-7D76                              | 2         | 1%      |
| Lenovo V330-14ARR 81B1                   | 2         | 1%      |
| ASUS VivoBook_ASUSLaptop K6500ZE_K6500ZE | 2         | 1%      |
| ASRock N68-S3 FX                         | 2         | 1%      |
| Unknown                                  | 2         | 1%      |
| Valve Jupiter                            | 1         | 0.5%    |
| TYAN S7012                               | 1         | 0.5%    |
| Toshiba Satellite P50-A-12Z              | 1         | 0.5%    |
| Toshiba PORTEGE Z30-A                    | 1         | 0.5%    |
| System76 Oryx Pro                        | 1         | 0.5%    |
| Supermicro X9DRD-7LN4F(-JBOD)/X9DRD-EF   | 1         | 0.5%    |
| Supermicro X9DA7/E                       | 1         | 0.5%    |
| Sony SVE1713A1EW                         | 1         | 0.5%    |
| Shuttle NC03U                            | 1         | 0.5%    |
| Samsung 300E5M/300E5L                    | 1         | 0.5%    |
| Radxa ROCK Pi 4                          | 1         | 0.5%    |
| Notebook X170KM-G                        | 1         | 0.5%    |
| Notebook P7xxTM                          | 1         | 0.5%    |
| Notebook NL5xNU                          | 1         | 0.5%    |
| Notebook NL40_50CU                       | 1         | 0.5%    |
| NetGear ReadyDATA 5200                   | 1         | 0.5%    |
| MSI MS-7D67                              | 1         | 0.5%    |
| MSI MS-7C87                              | 1         | 0.5%    |
| MSI MS-7C52                              | 1         | 0.5%    |
| MSI MS-7C02                              | 1         | 0.5%    |
| MSI MS-7B79                              | 1         | 0.5%    |
| MSI MS-7996                              | 1         | 0.5%    |
| MSI MS-7885                              | 1         | 0.5%    |
| MSI MS-7788                              | 1         | 0.5%    |
| MSI MS-7693                              | 1         | 0.5%    |
| MSI MS-7529                              | 1         | 0.5%    |
| MSI MS-7365                              | 1         | 0.5%    |
| MSI Modern 14 B5M                        | 1         | 0.5%    |
| MSI Modern 14 B11MO                      | 1         | 0.5%    |
| MSI Modern 14 B10MW                      | 1         | 0.5%    |
| MSI GP76 Leopard 11UG                    | 1         | 0.5%    |
| MSI GL73 8RC                             | 1         | 0.5%    |
| MSI GE76 Raider 11UE                     | 1         | 0.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 19        | 9.45%   |
| Dell Precision                | 8         | 3.98%   |
| ASUS PRIME                    | 8         | 3.98%   |
| HP Pavilion                   | 5         | 2.49%   |
| HP Laptop                     | 5         | 2.49%   |
| ASUS ROG                      | 4         | 1.99%   |
| ASUS All                      | 4         | 1.99%   |
| Toshiba Satellite             | 3         | 1.49%   |
| MSI Modern                    | 3         | 1.49%   |
| Lenovo IdeaPad                | 3         | 1.49%   |
| HP EliteBook                  | 3         | 1.49%   |
| Dell Latitude                 | 3         | 1.49%   |
| ASUS VivoBook                 | 3         | 1.49%   |
| ASUS TUF                      | 3         | 1.49%   |
| Acer Aspire                   | 3         | 1.49%   |
| MSI MS-7D76                   | 2         | 1%      |
| Lenovo V330-14ARR             | 2         | 1%      |
| HP OMEN                       | 2         | 1%      |
| HP ENVY                       | 2         | 1%      |
| HP Compaq                     | 2         | 1%      |
| Gigabyte X570                 | 2         | 1%      |
| Fujitsu LIFEBOOK              | 2         | 1%      |
| Dell XPS                      | 2         | 1%      |
| Dell Vostro                   | 2         | 1%      |
| Dell PowerEdge                | 2         | 1%      |
| Dell OptiPlex                 | 2         | 1%      |
| Dell Inspiron                 | 2         | 1%      |
| ASUS SABERTOOTH               | 2         | 1%      |
| ASRock N68-S3                 | 2         | 1%      |
| Acer Swift                    | 2         | 1%      |
| Unknown                       | 2         | 1%      |
| Valve Jupiter                 | 1         | 0.5%    |
| TYAN S7012                    | 1         | 0.5%    |
| Toshiba PORTEGE               | 1         | 0.5%    |
| System76 Oryx                 | 1         | 0.5%    |
| Supermicro X9DRD-7LN4F(-JBOD) | 1         | 0.5%    |
| Supermicro X9DA7              | 1         | 0.5%    |
| Sony SVE1713A1EW              | 1         | 0.5%    |
| Shuttle NC03U                 | 1         | 0.5%    |
| Samsung 300E5M                | 1         | 0.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 24        | 11.94%  |
| 2019    | 19        | 9.45%   |
| 2012    | 17        | 8.46%   |
| 2022    | 15        | 7.46%   |
| 2021    | 15        | 7.46%   |
| 2018    | 15        | 7.46%   |
| 2017    | 15        | 7.46%   |
| 2015    | 14        | 6.97%   |
| 2014    | 13        | 6.47%   |
| 2011    | 11        | 5.47%   |
| 2016    | 8         | 3.98%   |
| 2008    | 8         | 3.98%   |
| 2010    | 7         | 3.48%   |
| 2007    | 5         | 2.49%   |
| 2013    | 4         | 1.99%   |
| 2009    | 4         | 1.99%   |
| 2023    | 3         | 1.49%   |
| 2024    | 2         | 1%      |
| Unknown | 2         | 1%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 92        | 45.77%  |
| Notebook       | 91        | 45.27%  |
| Mini pc        | 6         | 2.99%   |
| Server         | 4         | 1.99%   |
| Convertible    | 3         | 1.49%   |
| System on chip | 2         | 1%      |
| All in one     | 2         | 1%      |
| Tablet         | 1         | 0.5%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 201       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 198       | 98.51%  |
| Yes  | 3         | 1.49%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 42        | 20.49%  |
| 16.01-24.0      | 38        | 18.54%  |
| 4.01-8.0        | 37        | 18.05%  |
| 32.01-64.0      | 30        | 14.63%  |
| 3.01-4.0        | 24        | 11.71%  |
| 64.01-256.0     | 15        | 7.32%   |
| 24.01-32.0      | 10        | 4.88%   |
| 1.01-2.0        | 6         | 2.93%   |
| More than 256.0 | 1         | 0.49%   |
| 2.01-3.0        | 1         | 0.49%   |
| 0.51-1.0        | 1         | 0.49%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 54        | 24.77%  |
| 2.01-3.0    | 49        | 22.48%  |
| 4.01-8.0    | 42        | 19.27%  |
| 3.01-4.0    | 22        | 10.09%  |
| 0.51-1.0    | 22        | 10.09%  |
| 8.01-16.0   | 11        | 5.05%   |
| 0.01-0.5    | 6         | 2.75%   |
| 16.01-24.0  | 5         | 2.29%   |
| 24.01-32.0  | 4         | 1.83%   |
| 32.01-64.0  | 1         | 0.46%   |
| 64.01-256.0 | 1         | 0.46%   |
| Unknown     | 1         | 0.46%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 95        | 45.89%  |
| 2      | 48        | 23.19%  |
| 3      | 20        | 9.66%   |
| 4      | 16        | 7.73%   |
| 6      | 6         | 2.9%    |
| 5      | 6         | 2.9%    |
| 0      | 6         | 2.9%    |
| 10     | 2         | 0.97%   |
| 9      | 2         | 0.97%   |
| 29     | 1         | 0.48%   |
| 14     | 1         | 0.48%   |
| 13     | 1         | 0.48%   |
| 11     | 1         | 0.48%   |
| 8      | 1         | 0.48%   |
| 7      | 1         | 0.48%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 132       | 65.35%  |
| Yes       | 70        | 34.65%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 183       | 90.15%  |
| No        | 20        | 9.85%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 137       | 68.16%  |
| No        | 64        | 31.84%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 124       | 61.39%  |
| No        | 78        | 38.61%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 46        | 22.89%  |
| UK           | 17        | 8.46%   |
| Japan        | 12        | 5.97%   |
| Italy        | 12        | 5.97%   |
| Germany      | 12        | 5.97%   |
| Brazil       | 11        | 5.47%   |
| Russia       | 8         | 3.98%   |
| Portugal     | 8         | 3.98%   |
| Canada       | 8         | 3.98%   |
| France       | 7         | 3.48%   |
| Kazakhstan   | 6         | 2.99%   |
| India        | 6         | 2.99%   |
| Spain        | 5         | 2.49%   |
| Sweden       | 4         | 1.99%   |
| South Africa | 3         | 1.49%   |
| Poland       | 3         | 1.49%   |
| Hong Kong    | 3         | 1.49%   |
| Greece       | 3         | 1.49%   |
| Serbia       | 2         | 1%      |
| Romania      | 2         | 1%      |
| Netherlands  | 2         | 1%      |
| Czechia      | 2         | 1%      |
| China        | 2         | 1%      |
| Chile        | 2         | 1%      |
| Australia    | 2         | 1%      |
| Argentina    | 2         | 1%      |
| Taiwan       | 1         | 0.5%    |
| Switzerland  | 1         | 0.5%    |
| Philippines  | 1         | 0.5%    |
| Paraguay     | 1         | 0.5%    |
| Mexico       | 1         | 0.5%    |
| Malaysia     | 1         | 0.5%    |
| Lithuania    | 1         | 0.5%    |
| Iran         | 1         | 0.5%    |
| Hungary      | 1         | 0.5%    |
| Finland      | 1         | 0.5%    |
| Bulgaria     | 1         | 0.5%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Tsukuba                | 7         | 3.37%   |
| Lisbon                 | 6         | 2.88%   |
| Ust-Kamenogorsk        | 4         | 1.92%   |
| Yekaterinburg          | 3         | 1.44%   |
| Warsaw                 | 3         | 1.44%   |
| Paris                  | 3         | 1.44%   |
| New Delhi              | 3         | 1.44%   |
| Milan                  | 3         | 1.44%   |
| Chania                 | 3         | 1.44%   |
| Tokyo                  | 2         | 0.96%   |
| Tendo                  | 2         | 0.96%   |
| Sun Prairie            | 2         | 0.96%   |
| Springfield            | 2         | 0.96%   |
| Seattle                | 2         | 0.96%   |
| San Elizario           | 2         | 0.96%   |
| Rome                   | 2         | 0.96%   |
| Moscow                 | 2         | 0.96%   |
| McKinney               | 2         | 0.96%   |
| Karaganda              | 2         | 0.96%   |
| Greater Noida          | 2         | 0.96%   |
| Gainesville            | 2         | 0.96%   |
| Frignano               | 2         | 0.96%   |
| Fayetteville           | 2         | 0.96%   |
| Dallas                 | 2         | 0.96%   |
| Carrollton             | 2         | 0.96%   |
| Cape Town              | 2         | 0.96%   |
| Bucharest              | 2         | 0.96%   |
| Belgrade               | 2         | 0.96%   |
| Barry                  | 2         | 0.96%   |
| Barrie                 | 2         | 0.96%   |
| Amsterdam              | 2         | 0.96%   |
| Worpswede              | 1         | 0.48%   |
| Wokingham              | 1         | 0.48%   |
| Winter Springs         | 1         | 0.48%   |
| Winnipeg               | 1         | 0.48%   |
| Weilheim               | 1         | 0.48%   |
| Voskresensk            | 1         | 0.48%   |
| Visconde do Rio Branco | 1         | 0.48%   |
| Vilnius                | 1         | 0.48%   |
| Villaputzu             | 1         | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 57        | 130    | 16.91%  |
| Samsung Electronics         | 57        | 82     | 16.91%  |
| Seagate                     | 53        | 105    | 15.73%  |
| Toshiba                     | 20        | 37     | 5.93%   |
| Kingston                    | 19        | 23     | 5.64%   |
| Crucial                     | 13        | 15     | 3.86%   |
| Sandisk                     | 12        | 18     | 3.56%   |
| Intel                       | 10        | 12     | 2.97%   |
| Hitachi                     | 8         | 11     | 2.37%   |
| Unknown                     | 7         | 10     | 2.08%   |
| SK hynix                    | 7         | 7      | 2.08%   |
| HGST                        | 7         | 7      | 2.08%   |
| A-DATA Technology           | 5         | 5      | 1.48%   |
| Transcend                   | 4         | 4      | 1.19%   |
| Micron Technology           | 4         | 4      | 1.19%   |
| Hewlett-Packard             | 4         | 5      | 1.19%   |
| Team                        | 3         | 3      | 0.89%   |
| Patriot                     | 3         | 4      | 0.89%   |
| KIOXIA                      | 3         | 4      | 0.89%   |
| Gigabyte Technology         | 3         | 3      | 0.89%   |
| Silicon Motion              | 2         | 3      | 0.59%   |
| Micron/Crucial Technology   | 2         | 2      | 0.59%   |
| Maxtor                      | 2         | 2      | 0.59%   |
| Kingston Technology Company | 2         | 3      | 0.59%   |
| JMicron Technology          | 2         | 2      | 0.59%   |
| Fujitsu                     | 2         | 2      | 0.59%   |
| External                    | 2         | 2      | 0.59%   |
| China                       | 2         | 3      | 0.59%   |
| Apple                       | 2         | 3      | 0.59%   |
| Unknown                     | 2         | 3      | 0.59%   |
| ZHITAI                      | 1         | 2      | 0.3%    |
| Verbatim                    | 1         | 2      | 0.3%    |
| TO Exter                    | 1         | 1      | 0.3%    |
| SSSTC                       | 1         | 1      | 0.3%    |
| Realtek Semiconductor       | 1         | 1      | 0.3%    |
| PNY                         | 1         | 2      | 0.3%    |
| Plextor                     | 1         | 1      | 0.3%    |
| Pioneer                     | 1         | 1      | 0.3%    |
| Phison Electronics          | 1         | 1      | 0.3%    |
| Netac                       | 1         | 1      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB   | 7         | 1.67%   |
| Kingston SA400S37240G 240GB SSD                       | 7         | 1.67%   |
| Seagate ST4000DM004-2CV104 4TB                        | 5         | 1.2%    |
| WDC WD20EFRX-68EUZN0 2TB                              | 4         | 0.96%   |
| Seagate ST1000LM048-2E7172 1TB                        | 4         | 0.96%   |
| WDC WD40EZRX-00SPEB0 4TB                              | 3         | 0.72%   |
| WDC WD1003FZEX-00MK2A0 1TB                            | 3         | 0.72%   |
| Seagate ST4000VN006-3CW104 4TB                        | 3         | 0.72%   |
| Seagate ST2000DM008-2FR102 2TB                        | 3         | 0.72%   |
| Samsung SSD 970 EVO 250GB                             | 3         | 0.72%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB  | 3         | 0.72%   |
| Intel SSD 660P Series 1024GB                          | 3         | 0.72%   |
| Crucial CT500MX500SSD1 500GB                          | 3         | 0.72%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                        | 2         | 0.48%   |
| WDC WD5000AAKX-00ERMA0 500GB                          | 2         | 0.48%   |
| WDC WD40EFRX-68N32N0 4TB                              | 2         | 0.48%   |
| WDC WD30EZRX-00SPEB0 3TB                              | 2         | 0.48%   |
| WDC WD10SPZX-60Z10T0 1TB                              | 2         | 0.48%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 2         | 0.48%   |
| WDC WD10EZEX-00RKKA0 1TB                              | 2         | 0.48%   |
| WDC WD100EMAZ-00WJTA0 10TB                            | 2         | 0.48%   |
| Toshiba MQ04ABF100 1TB                                | 2         | 0.48%   |
| Toshiba MQ01ABD100 1TB                                | 2         | 0.48%   |
| Toshiba HDWD110 1TB                                   | 2         | 0.48%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 2         | 0.48%   |
| Seagate ST8000VN0022-2EL112 8TB                       | 2         | 0.48%   |
| Seagate ST500DM002-1BD142 500GB                       | 2         | 0.48%   |
| Seagate ST4000VN008-2DR166 4TB                        | 2         | 0.48%   |
| Seagate ST31000524AS 1TB                              | 2         | 0.48%   |
| Seagate ST2000DX001-1NS164 2TB                        | 2         | 0.48%   |
| Seagate ST2000DM001-1CH164 2TB                        | 2         | 0.48%   |
| Seagate ST2000DL003-9VT166 2TB                        | 2         | 0.48%   |
| Seagate ST1000DM010-2EP102 1TB                        | 2         | 0.48%   |
| Seagate ST1000DM003-1SB102 1TB                        | 2         | 0.48%   |
| Seagate ST1000DM003-1ER162 1TB                        | 2         | 0.48%   |
| Seagate Expansion Desk 5TB                            | 2         | 0.48%   |
| Samsung SSD 970 EVO Plus 500GB                        | 2         | 0.48%   |
| Samsung SSD 970 EVO Plus 1TB                          | 2         | 0.48%   |
| Samsung SSD 860 QVO 2TB                               | 2         | 0.48%   |
| Samsung SSD 850 PRO 256GB                             | 2         | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 53        | 101    | 34.19%  |
| WDC                 | 50        | 117    | 32.26%  |
| Toshiba             | 19        | 32     | 12.26%  |
| Hitachi             | 8         | 11     | 5.16%   |
| HGST                | 7         | 7      | 4.52%   |
| Samsung Electronics | 5         | 5      | 3.23%   |
| Maxtor              | 2         | 2      | 1.29%   |
| JMicron Technology  | 2         | 2      | 1.29%   |
| Hewlett-Packard     | 2         | 2      | 1.29%   |
| Fujitsu             | 2         | 2      | 1.29%   |
| External            | 2         | 2      | 1.29%   |
| Unknown             | 2         | 3      | 1.29%   |
| TO Exter            | 1         | 1      | 0.65%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 23        | 34     | 23.96%  |
| Kingston            | 17        | 21     | 17.71%  |
| Crucial             | 10        | 12     | 10.42%  |
| SanDisk             | 6         | 7      | 6.25%   |
| WDC                 | 5         | 7      | 5.21%   |
| Transcend           | 3         | 3      | 3.13%   |
| Team                | 2         | 2      | 2.08%   |
| Patriot             | 2         | 3      | 2.08%   |
| Micron Technology   | 2         | 2      | 2.08%   |
| Intel               | 2         | 3      | 2.08%   |
| China               | 2         | 3      | 2.08%   |
| Apple               | 2         | 3      | 2.08%   |
| A-DATA Technology   | 2         | 2      | 2.08%   |
| ZHITAI              | 1         | 1      | 1.04%   |
| Verbatim            | 1         | 2      | 1.04%   |
| Toshiba             | 1         | 3      | 1.04%   |
| SSSTC               | 1         | 1      | 1.04%   |
| SK hynix            | 1         | 1      | 1.04%   |
| PNY                 | 1         | 2      | 1.04%   |
| Plextor             | 1         | 1      | 1.04%   |
| Pioneer             | 1         | 1      | 1.04%   |
| Netac               | 1         | 1      | 1.04%   |
| LITEON              | 1         | 1      | 1.04%   |
| Lexar               | 1         | 1      | 1.04%   |
| Intenso             | 1         | 1      | 1.04%   |
| Hewlett-Packard     | 1         | 1      | 1.04%   |
| GOODRAM             | 1         | 1      | 1.04%   |
| Gigabyte Technology | 1         | 1      | 1.04%   |
| DUEX                | 1         | 1      | 1.04%   |
| Dogfish             | 1         | 1      | 1.04%   |
| AirDisk             | 1         | 1      | 1.04%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 109       | 287    | 38.11%  |
| SSD     | 89        | 124    | 31.12%  |
| NVMe    | 81        | 112    | 28.32%  |
| MMC     | 6         | 8      | 2.1%    |
| Unknown | 1         | 4      | 0.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 147       | 395    | 59.76%  |
| NVMe | 81        | 112    | 32.93%  |
| SAS  | 12        | 20     | 4.88%   |
| MMC  | 6         | 8      | 2.44%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 102       | 147    | 43.4%   |
| 0.51-1.0   | 60        | 108    | 25.53%  |
| 1.01-2.0   | 25        | 32     | 10.64%  |
| 3.01-4.0   | 22        | 46     | 9.36%   |
| 4.01-10.0  | 13        | 45     | 5.53%   |
| 2.01-3.0   | 9         | 21     | 3.83%   |
| 10.01-20.0 | 4         | 12     | 1.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 45        | 21.74%  |
| 101-250        | 44        | 21.26%  |
| 251-500        | 30        | 14.49%  |
| 1001-2000      | 25        | 12.08%  |
| Unknown        | 22        | 10.63%  |
| 2001-3000      | 11        | 5.31%   |
| More than 3000 | 10        | 4.83%   |
| 1-20           | 10        | 4.83%   |
| 51-100         | 7         | 3.38%   |
| 21-50          | 3         | 1.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 40        | 18.87%  |
| 1-20           | 31        | 14.62%  |
| 251-500        | 29        | 13.68%  |
| 21-50          | 26        | 12.26%  |
| 501-1000       | 24        | 11.32%  |
| Unknown        | 22        | 10.38%  |
| 51-100         | 21        | 9.91%   |
| 1001-2000      | 11        | 5.19%   |
| More than 3000 | 5         | 2.36%   |
| 2001-3000      | 3         | 1.42%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD20EFRX-68EUZN0 2TB              | 2         | 3      | 4%      |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1         | 1      | 2%      |
| WDC WD5003ABYX-18WERA0 500GB          | 1         | 2      | 2%      |
| WDC WD5003ABYX-01WERA0 500GB          | 1         | 1      | 2%      |
| WDC WD5000LPCX-60VHAT1 500GB          | 1         | 1      | 2%      |
| WDC WD5000BPKX-60HPJT0 500GB          | 1         | 1      | 2%      |
| WDC WD5000AAKX-22ERMA0 500GB          | 1         | 1      | 2%      |
| WDC WD5000AAKX-00ERMA0 500GB          | 1         | 1      | 2%      |
| WDC WD5000AAKS-00A7B2 500GB           | 1         | 1      | 2%      |
| WDC WD40EFRX-68WT0N0 4TB              | 1         | 2      | 2%      |
| WDC WD40EFAX-68JH4N1 4TB              | 1         | 4      | 2%      |
| WDC WD3200AAJS-65B4A0 320GB           | 1         | 1      | 2%      |
| WDC WD30EZRX-00MMMB0 3TB              | 1         | 1      | 2%      |
| WDC WD30EZRX-00M                      | 1         | 1      | 2%      |
| WDC WD30EZRX-00D8PB0 3TB              | 1         | 1      | 2%      |
| WDC WD30EFRX-68AX9N0 3TB              | 1         | 4      | 2%      |
| WDC WD20EARX-00PASB0 2TB              | 1         | 1      | 2%      |
| WDC WD10JPLX-00MBPT0 1TB              | 1         | 1      | 2%      |
| WDC WD10EZEX-00RKKA0 1TB              | 1         | 1      | 2%      |
| WDC WD10EALS-00Z8A0 1TB               | 1         | 2      | 2%      |
| WDC WD1003FZEX-00MK2A0 1TB            | 1         | 2      | 2%      |
| Toshiba MK2565GSXN 250GB              | 1         | 1      | 2%      |
| SSSTC CVB-8D128-HP 128GB SSD          | 1         | 1      | 2%      |
| Seagate ST380011A 80GB                | 1         | 2      | 2%      |
| Seagate ST3500630AS 500GB             | 1         | 1      | 2%      |
| Seagate ST3500418AS 500GB             | 1         | 1      | 2%      |
| Seagate ST3500410AS 500GB             | 1         | 1      | 2%      |
| Seagate ST31000524AS 1TB              | 1         | 1      | 2%      |
| Seagate ST3000VX006-1HH166 3TB        | 1         | 1      | 2%      |
| Seagate ST2000DL003-9VT166 2TB        | 1         | 1      | 2%      |
| Seagate ST1000VM002-1SD102 1TB        | 1         | 1      | 2%      |
| Seagate ST1000NM0011 1TB              | 1         | 2      | 2%      |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 2%      |
| Seagate ST1000LM014-1EJ164 1TB        | 1         | 1      | 2%      |
| Seagate ST1000DM003-1ER162 1TB        | 1         | 2      | 2%      |
| SanDisk SDSA6MM-016G-1006 16GB SSD    | 1         | 1      | 2%      |
| Samsung Electronics SSD 970 EVO 500GB | 1         | 1      | 2%      |
| Samsung Electronics SSD 870 EVO 1TB   | 1         | 1      | 2%      |
| Plextor PX-128M6S 128GB SSD           | 1         | 1      | 2%      |
| Maxtor 4G120J6 128GB                  | 1         | 1      | 2%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 19        | 33     | 41.3%   |
| Seagate             | 11        | 15     | 23.91%  |
| Hitachi             | 3         | 3      | 6.52%   |
| HGST                | 3         | 3      | 6.52%   |
| Samsung Electronics | 2         | 2      | 4.35%   |
| Toshiba             | 1         | 1      | 2.17%   |
| SSSTC               | 1         | 1      | 2.17%   |
| SanDisk             | 1         | 1      | 2.17%   |
| Plextor             | 1         | 1      | 2.17%   |
| Maxtor              | 1         | 1      | 2.17%   |
| Intel               | 1         | 1      | 2.17%   |
| DUEX                | 1         | 1      | 2.17%   |
| Unknown             | 1         | 1      | 2.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 18        | 32     | 47.37%  |
| Seagate | 11        | 15     | 28.95%  |
| Hitachi | 3         | 3      | 7.89%   |
| HGST    | 3         | 3      | 7.89%   |
| Toshiba | 1         | 1      | 2.63%   |
| Maxtor  | 1         | 1      | 2.63%   |
| Unknown | 1         | 1      | 2.63%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 35        | 56     | 81.4%   |
| SSD  | 7         | 7      | 16.28%  |
| NVMe | 1         | 1      | 2.33%   |

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
| Works    | 158       | 384    | 64.75%  |
| Detected | 43        | 87     | 17.62%  |
| Malfunc  | 43        | 64     | 17.62%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 114       | 39.31%  |
| AMD                          | 55        | 18.97%  |
| Samsung Electronics          | 34        | 11.72%  |
| ASMedia Technology           | 14        | 4.83%   |
| SanDisk                      | 11        | 3.79%   |
| Marvell Technology Group     | 8         | 2.76%   |
| SK hynix                     | 6         | 2.07%   |
| Nvidia                       | 5         | 1.72%   |
| Micron/Crucial Technology    | 5         | 1.72%   |
| Realtek Semiconductor        | 4         | 1.38%   |
| Kingston Technology Company  | 4         | 1.38%   |
| JMicron Technology           | 4         | 1.38%   |
| Broadcom / LSI               | 4         | 1.38%   |
| Phison Electronics           | 3         | 1.03%   |
| KIOXIA                       | 3         | 1.03%   |
| Silicon Motion               | 2         | 0.69%   |
| Micron Technology            | 2         | 0.69%   |
| MAXIO Technology (Hangzhou)  | 2         | 0.69%   |
| LSI Logic / Symbios Logic    | 2         | 0.69%   |
| Yangtze Memory Technologies  | 1         | 0.34%   |
| Toshiba America Info Systems | 1         | 0.34%   |
| Silicon Image                | 1         | 0.34%   |
| Nextorage                    | 1         | 0.34%   |
| Lite-On Technology           | 1         | 0.34%   |
| Biwin Storage Technology     | 1         | 0.34%   |
| Adaptec                      | 1         | 0.34%   |
| 3ware                        | 1         | 0.34%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 35        | 10.2%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 18        | 5.25%   |
| AMD 400 Series Chipset SATA Controller                                           | 13        | 3.79%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                    | 10        | 2.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 8         | 2.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 8         | 2.33%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 8         | 2.33%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 2.04%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 7         | 2.04%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 6         | 1.75%   |
| AMD 500 Series Chipset SATA Controller                                           | 6         | 1.75%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 4         | 1.17%   |
| Nvidia MCP61 SATA Controller                                                     | 4         | 1.17%   |
| Nvidia MCP61 IDE                                                                 | 4         | 1.17%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 4         | 1.17%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 1.17%   |
| Intel Volume Management Device NVMe RAID Controller                              | 4         | 1.17%   |
| Intel SATA Controller [RAID mode]                                                | 4         | 1.17%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 4         | 1.17%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 4         | 1.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 1.17%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 4         | 1.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 1.17%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 1.17%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 3         | 0.87%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 0.87%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 3         | 0.87%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 3         | 0.87%   |
| Intel SSD 660P Series                                                            | 3         | 0.87%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 0.87%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 3         | 0.87%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 0.87%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 0.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 3         | 0.87%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 3         | 0.87%   |
| AMD 600 Series Chipset SATA Controller                                           | 3         | 0.87%   |
| SK hynix BC511 NVMe SSD                                                          | 2         | 0.58%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 2         | 0.58%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 2         | 0.58%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD          | 2         | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 143       | 51.07%  |
| NVMe | 82        | 29.29%  |
| IDE  | 25        | 8.93%   |
| RAID | 22        | 7.86%   |
| SAS  | 5         | 1.79%   |
| SCSI | 3         | 1.07%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 132       | 65.67%  |
| AMD    | 67        | 33.33%  |
| ARM    | 2         | 1%      |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 4         | 1.98%   |
| AMD Ryzen 5 3600 6-Core Processor             | 4         | 1.98%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.49%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 1.49%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.49%   |
| Intel 12th Gen Core i7-12700H                 | 3         | 1.49%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 3         | 1.49%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 3         | 1.49%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 3         | 1.49%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz            | 2         | 0.99%   |
| Intel Pentium CPU G4560 @ 3.50GHz             | 2         | 0.99%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 0.99%   |
| Intel Core i7-5820K CPU @ 3.30GHz             | 2         | 0.99%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 2         | 0.99%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 0.99%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 0.99%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 0.99%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 2         | 0.99%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 0.99%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 2         | 0.99%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 2         | 0.99%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 0.99%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 0.99%   |
| ARM Processor                                 | 2         | 0.99%   |
| AMD Ryzen 9 7900 12-Core Processor            | 2         | 0.99%   |
| AMD Ryzen 7 7730U with Radeon Graphics        | 2         | 0.99%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 2         | 0.99%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 2         | 0.99%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 2         | 0.99%   |
| AMD FX-8350 Eight-Core Processor              | 2         | 0.99%   |
| AMD Athlon II X2 250 Processor                | 2         | 0.99%   |
| Intel Xeon CPU X5680 @ 3.33GHz                | 1         | 0.5%    |
| Intel Xeon CPU X5355 @ 2.66GHz                | 1         | 0.5%    |
| Intel Xeon CPU X3450 @ 2.67GHz                | 1         | 0.5%    |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz           | 1         | 0.5%    |
| Intel Xeon CPU E5-2695 v2 @ 2.40GHz           | 1         | 0.5%    |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz           | 1         | 0.5%    |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz           | 1         | 0.5%    |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz            | 1         | 0.5%    |
| Intel Xeon CPU E5-2407 0 @ 2.20GHz            | 1         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 33        | 16.34%  |
| Intel Core i7        | 30        | 14.85%  |
| Other                | 20        | 9.9%    |
| AMD Ryzen 5          | 19        | 9.41%   |
| Intel Xeon           | 15        | 7.43%   |
| AMD Ryzen 7          | 13        | 6.44%   |
| AMD Ryzen 9          | 10        | 4.95%   |
| Intel Pentium        | 8         | 3.96%   |
| Intel Core i3        | 8         | 3.96%   |
| Intel Core 2 Duo     | 6         | 2.97%   |
| AMD FX               | 6         | 2.97%   |
| Intel Celeron        | 4         | 1.98%   |
| Intel Atom           | 3         | 1.49%   |
| AMD Ryzen 3          | 3         | 1.49%   |
| Intel Core 2 Quad    | 2         | 0.99%   |
| AMD Ryzen 7 PRO      | 2         | 0.99%   |
| AMD Athlon II X2     | 2         | 0.99%   |
| Intel Pentium Silver | 1         | 0.5%    |
| Intel Pentium Gold   | 1         | 0.5%    |
| Intel Pentium Dual   | 1         | 0.5%    |
| Intel Core M         | 1         | 0.5%    |
| Intel Core i9        | 1         | 0.5%    |
| Intel Core 2         | 1         | 0.5%    |
| Intel Core           | 1         | 0.5%    |
| AMD Ryzen Embedded   | 1         | 0.5%    |
| AMD Ryzen 3 PRO      | 1         | 0.5%    |
| AMD GX               | 1         | 0.5%    |
| AMD G                | 1         | 0.5%    |
| AMD EPYC             | 1         | 0.5%    |
| AMD E1               | 1         | 0.5%    |
| AMD Athlon 64 X2     | 1         | 0.5%    |
| AMD Athlon           | 1         | 0.5%    |
| AMD A8               | 1         | 0.5%    |
| AMD A4               | 1         | 0.5%    |
| AMD A10              | 1         | 0.5%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 65        | 32.18%  |
| 2      | 60        | 29.7%   |
| 8      | 26        | 12.87%  |
| 6      | 22        | 10.89%  |
| 12     | 8         | 3.96%   |
| 16     | 7         | 3.47%   |
| 14     | 5         | 2.48%   |
| 10     | 4         | 1.98%   |
| 1      | 3         | 1.49%   |
| 24     | 1         | 0.5%    |
| 3      | 1         | 0.5%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 192       | 95.52%  |
| 2      | 9         | 4.48%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 151       | 75.12%  |
| 1      | 50        | 24.88%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 198       | 98.51%  |
| Unknown        | 2         | 1%      |
| 32-bit         | 1         | 0.5%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 66        | 32.2%   |
| 0x306a9    | 10        | 4.88%   |
| 0x306c3    | 7         | 3.41%   |
| 0x08701021 | 7         | 3.41%   |
| 0x206d7    | 5         | 2.44%   |
| 0x20655    | 5         | 2.44%   |
| 0x08108109 | 5         | 2.44%   |
| 0x906a3    | 4         | 1.95%   |
| 0x806ea    | 4         | 1.95%   |
| 0x806d1    | 4         | 1.95%   |
| 0x406e3    | 4         | 1.95%   |
| 0x306d4    | 4         | 1.95%   |
| 0x206a7    | 4         | 1.95%   |
| 0x1067a    | 4         | 1.95%   |
| 0x906ea    | 3         | 1.46%   |
| 0x806ec    | 3         | 1.46%   |
| 0x806c1    | 3         | 1.46%   |
| 0x406c4    | 3         | 1.46%   |
| 0x306f2    | 3         | 1.46%   |
| 0x08701013 | 3         | 1.46%   |
| 0x0810100b | 3         | 1.46%   |
| 0x906ed    | 2         | 0.98%   |
| 0x6fd      | 2         | 0.98%   |
| 0x506e3    | 2         | 0.98%   |
| 0x106c2    | 2         | 0.98%   |
| 0x0a50000c | 2         | 0.98%   |
| 0x0a201016 | 2         | 0.98%   |
| 0x08600106 | 2         | 0.98%   |
| 0x06001119 | 2         | 0.98%   |
| 0x06000822 | 2         | 0.98%   |
| 0xa0671    | 1         | 0.49%   |
| 0xa0660    | 1         | 0.49%   |
| 0xa0653    | 1         | 0.49%   |
| 0xa0652    | 1         | 0.49%   |
| 0x906e9    | 1         | 0.49%   |
| 0x906c0    | 1         | 0.49%   |
| 0x906a4    | 1         | 0.49%   |
| 0x806e9    | 1         | 0.49%   |
| 0x706a1    | 1         | 0.49%   |
| 0x6fb      | 1         | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 26        | 12.87%  |
| Zen 2            | 16        | 7.92%   |
| Haswell          | 16        | 7.92%   |
| IvyBridge        | 13        | 6.44%   |
| SandyBridge      | 12        | 5.94%   |
| Unknown          | 12        | 5.94%   |
| Zen 3            | 11        | 5.45%   |
| Zen+             | 10        | 4.95%   |
| Skylake          | 9         | 4.46%   |
| Zen              | 8         | 3.96%   |
| Westmere         | 8         | 3.96%   |
| Core             | 8         | 3.96%   |
| Alderlake Hybrid | 7         | 3.47%   |
| Piledriver       | 6         | 2.97%   |
| Silvermont       | 5         | 2.48%   |
| Penryn           | 5         | 2.48%   |
| Icelake          | 5         | 2.48%   |
| CometLake        | 4         | 1.98%   |
| Broadwell        | 4         | 1.98%   |
| TigerLake        | 3         | 1.49%   |
| K10              | 2         | 0.99%   |
| Jaguar           | 2         | 0.99%   |
| Bulldozer        | 2         | 0.99%   |
| Bonnell          | 2         | 0.99%   |
| Tremont          | 1         | 0.5%    |
| Puma             | 1         | 0.5%    |
| Nehalem          | 1         | 0.5%    |
| K8 Hammer        | 1         | 0.5%    |
| Goldmont plus    | 1         | 0.5%    |
| Bobcat           | 1         | 0.5%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 91        | 41.36%  |
| AMD                        | 64        | 29.09%  |
| Nvidia                     | 59        | 26.82%  |
| Matrox Electronics Systems | 6         | 2.73%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 9         | 3.93%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 7         | 3.06%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 2.62%   |
| Intel UHD Graphics 620                                                                   | 5         | 2.18%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 2.18%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 2.18%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 2.18%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5         | 2.18%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 4         | 1.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 1.75%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.75%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 4         | 1.75%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 3         | 1.31%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 3         | 1.31%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.31%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 1.31%   |
| Intel HD Graphics 620                                                                    | 3         | 1.31%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.31%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.31%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 3         | 1.31%   |
| AMD Raphael                                                                              | 3         | 1.31%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 3         | 1.31%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 1.31%   |
| AMD Barcelo                                                                              | 3         | 1.31%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.87%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.87%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 0.87%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2         | 0.87%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2         | 0.87%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.87%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2         | 0.87%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 0.87%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 2         | 0.87%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 2         | 0.87%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.87%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.87%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.87%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 0.87%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 0.87%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 72        | 35.82%  |
| 1 x AMD        | 55        | 27.36%  |
| 1 x Nvidia     | 39        | 19.4%   |
| Intel + Nvidia | 15        | 7.46%   |
| 1 x Matrox     | 6         | 2.99%   |
| Other          | 4         | 1.99%   |
| 2 x AMD        | 4         | 1.99%   |
| AMD + Nvidia   | 3         | 1.49%   |
| Intel + AMD    | 2         | 1%      |
| 2 x Nvidia     | 1         | 0.5%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 154       | 76.24%  |
| Proprietary | 31        | 15.35%  |
| Unknown     | 17        | 8.42%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 109       | 53.43%  |
| 1.01-2.0   | 21        | 10.29%  |
| 0.51-1.0   | 20        | 9.8%    |
| 0.01-0.5   | 16        | 7.84%   |
| 3.01-4.0   | 14        | 6.86%   |
| 7.01-8.0   | 12        | 5.88%   |
| 5.01-6.0   | 5         | 2.45%   |
| 8.01-16.0  | 5         | 2.45%   |
| 2.01-3.0   | 1         | 0.49%   |
| 16.01-24.0 | 1         | 0.49%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 22        | 10.73%  |
| BOE                  | 21        | 10.24%  |
| Dell                 | 17        | 8.29%   |
| AU Optronics         | 17        | 8.29%   |
| Chimei Innolux       | 16        | 7.8%    |
| LG Display           | 15        | 7.32%   |
| Hewlett-Packard      | 14        | 6.83%   |
| Goldstar             | 11        | 5.37%   |
| BenQ                 | 11        | 5.37%   |
| Lenovo               | 6         | 2.93%   |
| Sharp                | 5         | 2.44%   |
| Ancor Communications | 5         | 2.44%   |
| Acer                 | 5         | 2.44%   |
| ViewSonic            | 3         | 1.46%   |
| ASUSTek Computer     | 3         | 1.46%   |
| AOC                  | 3         | 1.46%   |
| Toshiba              | 2         | 0.98%   |
| Iiyama               | 2         | 0.98%   |
| Xiaomi               | 1         | 0.49%   |
| Wacom                | 1         | 0.49%   |
| Valve                | 1         | 0.49%   |
| Unknown              | 1         | 0.49%   |
| UGD                  | 1         | 0.49%   |
| TopView              | 1         | 0.49%   |
| Sony                 | 1         | 0.49%   |
| RTK                  | 1         | 0.49%   |
| Philips              | 1         | 0.49%   |
| PANDA                | 1         | 0.49%   |
| Panasonic            | 1         | 0.49%   |
| ONN                  | 1         | 0.49%   |
| NEC Computers        | 1         | 0.49%   |
| MSI                  | 1         | 0.49%   |
| JVC                  | 1         | 0.49%   |
| IOD                  | 1         | 0.49%   |
| InnoLux Display      | 1         | 0.49%   |
| Hyundai ImageQuest   | 1         | 0.49%   |
| HKC                  | 1         | 0.49%   |
| Gigabyte Technology  | 1         | 0.49%   |
| GDH                  | 1         | 0.49%   |
| Eizo                 | 1         | 0.49%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 3         | 1.43%   |
| Samsung Electronics LCD Monitor SDC416E 2880x1620 344x194mm 15.5-inch | 2         | 0.95%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 2         | 0.95%   |
| LG Display LCD Monitor LGD0353 1366x768 345x194mm 15.6-inch           | 2         | 0.95%   |
| Lenovo LCD Monitor LEN4035 1280x800 304x190mm 14.1-inch               | 2         | 0.95%   |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch             | 2         | 0.95%   |
| Goldstar ULTRAGEAR GSM7765 2560x1440 697x392mm 31.5-inch              | 2         | 0.95%   |
| Goldstar LG HDR WQHD GSM7756 3440x1440 820x340mm 34.9-inch            | 2         | 0.95%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 2         | 0.95%   |
| BenQ GW2283 BNQ78E9 1920x1080 476x268mm 21.5-inch                     | 2         | 0.95%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 2         | 0.95%   |
| Xiaomi Mi TV XMD009A 2880x1800 480x270mm 21.7-inch                    | 1         | 0.48%   |
| Wacom Cintiq 22HDT WAC1037 1920x1080 476x268mm 21.5-inch              | 1         | 0.48%   |
| ViewSonic VX3276-FHD VSCE735 1920x1080 698x393mm 31.5-inch            | 1         | 0.48%   |
| ViewSonic LCD Monitor VX2276 Series 1920x1080                         | 1         | 0.48%   |
| ViewSonic LCD Monitor VA2448 SERIES 1920x1080                         | 1         | 0.48%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 0.48%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1         | 0.48%   |
| UGD LCD Monitor UGD1302 1920x1080 290x160mm 13.0-inch                 | 1         | 0.48%   |
| Toshiba TV TSB0206 1920x1080 1600x1000mm 74.3-inch                    | 1         | 0.48%   |
| Toshiba TV TSB0108 1920x540                                           | 1         | 0.48%   |
| TopView HDMI TOP0814 1600x900 430x270mm 20.0-inch                     | 1         | 0.48%   |
| Sony TV SNY8102 1360x768                                              | 1         | 0.48%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 382x215mm 17.3-inch               | 1         | 0.48%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 0.48%   |
| Sharp LQ125T1JW02 SHP142F 2560x1440 277x155mm 12.5-inch               | 1         | 0.48%   |
| Sharp LCD Monitor SHP14C4 1920x1080 344x194mm 15.5-inch               | 1         | 0.48%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 1         | 0.48%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch     | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM0578 1920x1080 476x268mm 21.5-inch  | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch   | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM0428 1680x1050 459x296mm 21.5-inch  | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM03F2 1680x1050                      | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM03F0 1680x1050 433x271mm 20.1-inch  | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 376x301mm 19.0-inch  | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM01AD 1600x1200 408x306mm 20.1-inch  | 1         | 0.48%   |
| Samsung Electronics SMS27A650 SAM082D 1920x1080 598x336mm 27.0-inch   | 1         | 0.48%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch    | 1         | 0.48%   |
| Samsung Electronics SMEX2220 SAM0686 1920x1080 477x268mm 21.5-inch    | 1         | 0.48%   |
| Samsung Electronics SM2333T SAM0736 1920x1080 477x268mm 21.5-inch     | 1         | 0.48%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 92        | 46.46%  |
| 1366x768 (WXGA)    | 30        | 15.15%  |
| 3840x2160 (4K)     | 10        | 5.05%   |
| 2560x1440 (QHD)    | 9         | 4.55%   |
| 1920x1200 (WUXGA)  | 9         | 4.55%   |
| 1680x1050 (WSXGA+) | 8         | 4.04%   |
| 1280x1024 (SXGA)   | 8         | 4.04%   |
| 3440x1440          | 5         | 2.53%   |
| 1600x900 (HD+)     | 5         | 2.53%   |
| 1280x800 (WXGA)    | 5         | 2.53%   |
| 2880x1620          | 2         | 1.01%   |
| 1920x540           | 2         | 1.01%   |
| 1440x900 (WXGA+)   | 2         | 1.01%   |
| 1360x768           | 2         | 1.01%   |
| 800x1280           | 1         | 0.51%   |
| 3200x1080          | 1         | 0.51%   |
| 2288x1287          | 1         | 0.51%   |
| 2256x1504          | 1         | 0.51%   |
| 2160x1440          | 1         | 0.51%   |
| 1920x1280          | 1         | 0.51%   |
| 1600x1200          | 1         | 0.51%   |
| 1024x768 (XGA)     | 1         | 0.51%   |
| Unknown            | 1         | 0.51%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 43        | 20.87%  |
| 27      | 19        | 9.22%   |
| 21      | 19        | 9.22%   |
| 24      | 18        | 8.74%   |
| 14      | 16        | 7.77%   |
| 13      | 15        | 7.28%   |
| 17      | 11        | 5.34%   |
| 23      | 9         | 4.37%   |
| Unknown | 7         | 3.4%    |
| 31      | 5         | 2.43%   |
| 22      | 5         | 2.43%   |
| 20      | 5         | 2.43%   |
| 18      | 5         | 2.43%   |
| 16      | 5         | 2.43%   |
| 12      | 5         | 2.43%   |
| 19      | 4         | 1.94%   |
| 72      | 2         | 0.97%   |
| 35      | 2         | 0.97%   |
| 34      | 2         | 0.97%   |
| 142     | 1         | 0.49%   |
| 84      | 1         | 0.49%   |
| 74      | 1         | 0.49%   |
| 52      | 1         | 0.49%   |
| 46      | 1         | 0.49%   |
| 32      | 1         | 0.49%   |
| 11      | 1         | 0.49%   |
| 10      | 1         | 0.49%   |
| 7       | 1         | 0.49%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 75        | 36.76%  |
| 501-600        | 42        | 20.59%  |
| 401-500        | 36        | 17.65%  |
| 351-400        | 13        | 6.37%   |
| 201-300        | 12        | 5.88%   |
| Unknown        | 7         | 3.43%   |
| 601-700        | 6         | 2.94%   |
| 1501-2000      | 4         | 1.96%   |
| 701-800        | 3         | 1.47%   |
| 801-900        | 2         | 0.98%   |
| 1001-1500      | 2         | 0.98%   |
| More than 2000 | 1         | 0.49%   |
| 1-100          | 1         | 0.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 133       | 71.51%  |
| 16/10   | 25        | 13.44%  |
| 5/4     | 6         | 3.23%   |
| 3/2     | 6         | 3.23%   |
| Unknown | 5         | 2.69%   |
| 21/9    | 4         | 2.15%   |
| 6/5     | 2         | 1.08%   |
| 4/3     | 2         | 1.08%   |
| 32/9    | 1         | 0.54%   |
| 1.00    | 1         | 0.54%   |
| 0.67    | 1         | 0.54%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 45        | 22.17%  |
| 201-250        | 38        | 18.72%  |
| 81-90          | 27        | 13.3%   |
| 301-350        | 19        | 9.36%   |
| 151-200        | 13        | 6.4%    |
| 351-500        | 10        | 4.93%   |
| 141-150        | 9         | 4.43%   |
| 251-300        | 7         | 3.45%   |
| Unknown        | 7         | 3.45%   |
| More than 1000 | 6         | 2.96%   |
| 121-130        | 6         | 2.96%   |
| 61-70          | 5         | 2.46%   |
| 71-80          | 4         | 1.97%   |
| 111-120        | 3         | 1.48%   |
| 51-60          | 2         | 0.99%   |
| 1-40           | 1         | 0.49%   |
| 501-1000       | 1         | 0.49%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 70        | 35%     |
| 121-160       | 53        | 26.5%   |
| 101-120       | 52        | 26%     |
| 161-240       | 10        | 5%      |
| Unknown       | 7         | 3.5%    |
| 1-50          | 6         | 3%      |
| More than 240 | 2         | 1%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 156       | 77.61%  |
| 2     | 23        | 11.44%  |
| 0     | 18        | 8.96%   |
| 3     | 3         | 1.49%   |
| 4     | 1         | 0.5%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 107       | 36.15%  |
| Realtek Semiconductor           | 106       | 35.81%  |
| Qualcomm Atheros                | 18        | 6.08%   |
| Broadcom                        | 14        | 4.73%   |
| MediaTek                        | 10        | 3.38%   |
| Ralink Technology               | 7         | 2.36%   |
| ASIX Electronics                | 6         | 2.03%   |
| Broadcom Limited                | 5         | 1.69%   |
| TP-Link                         | 4         | 1.35%   |
| Nvidia                          | 4         | 1.35%   |
| Qualcomm                        | 2         | 0.68%   |
| Dell                            | 2         | 0.68%   |
| VIA Technologies                | 1         | 0.34%   |
| Sitecom Europe                  | 1         | 0.34%   |
| Sierra Wireless                 | 1         | 0.34%   |
| Ralink                          | 1         | 0.34%   |
| Qualcomm Atheros Communications | 1         | 0.34%   |
| Micro Star International        | 1         | 0.34%   |
| Mellanox Technologies           | 1         | 0.34%   |
| Marvell Technology Group        | 1         | 0.34%   |
| Huawei Technologies             | 1         | 0.34%   |
| Hewlett-Packard                 | 1         | 0.34%   |
| Chelsio Communications          | 1         | 0.34%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 69        | 19.44%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 13        | 3.66%   |
| Intel Wi-Fi 6 AX200                                                    | 10        | 2.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 10        | 2.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 8         | 2.25%   |
| Realtek RTL8125 2.5GbE Controller                                      | 8         | 2.25%   |
| Intel I211 Gigabit Network Connection                                  | 8         | 2.25%   |
| Intel Wireless 8265 / 8275                                             | 6         | 1.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 1.41%   |
| Ralink MT7601U Wireless Adapter                                        | 5         | 1.41%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 5         | 1.41%   |
| Intel Wireless 8260                                                    | 5         | 1.41%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 5         | 1.41%   |
| Intel 82574L Gigabit Network Connection                                | 5         | 1.41%   |
| Intel Wireless 7260                                                    | 4         | 1.13%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 4         | 1.13%   |
| Intel I350 Gigabit Network Connection                                  | 4         | 1.13%   |
| Intel Ethernet Controller I225-V                                       | 4         | 1.13%   |
| Intel Ethernet Connection (2) I218-V                                   | 4         | 1.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 4         | 1.13%   |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 1.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 3         | 0.85%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 3         | 0.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 3         | 0.85%   |
| Nvidia MCP61 Ethernet                                                  | 3         | 0.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 3         | 0.85%   |
| Intel Wireless 7265                                                    | 3         | 0.85%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 0.85%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3         | 0.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 3         | 0.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 3         | 0.85%   |
| Intel Centrino Ultimate-N 6300                                         | 3         | 0.85%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 3         | 0.85%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 0.85%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 2         | 0.56%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 2         | 0.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 0.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2         | 0.56%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                       | 2         | 0.56%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 2         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 71        | 50%     |
| Realtek Semiconductor           | 22        | 15.49%  |
| Qualcomm Atheros                | 13        | 9.15%   |
| MediaTek                        | 10        | 7.04%   |
| Ralink Technology               | 7         | 4.93%   |
| TP-Link                         | 4         | 2.82%   |
| Broadcom                        | 4         | 2.82%   |
| Broadcom Limited                | 3         | 2.11%   |
| Dell                            | 2         | 1.41%   |
| Sitecom Europe                  | 1         | 0.7%    |
| Sierra Wireless                 | 1         | 0.7%    |
| Ralink                          | 1         | 0.7%    |
| Qualcomm Atheros Communications | 1         | 0.7%    |
| Qualcomm                        | 1         | 0.7%    |
| Micro Star International        | 1         | 0.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 10        | 6.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 8         | 5.59%   |
| Intel Wireless 8265 / 8275                                    | 6         | 4.2%    |
| Ralink MT7601U Wireless Adapter                               | 5         | 3.5%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 5         | 3.5%    |
| Intel Wireless 8260                                           | 5         | 3.5%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]     | 5         | 3.5%    |
| Intel Wireless 7260                                           | 4         | 2.8%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]       | 4         | 2.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 4         | 2.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 3         | 2.1%    |
| Realtek RTL8188EE Wireless Network Adapter                    | 3         | 2.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 3         | 2.1%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 3         | 2.1%    |
| Intel Wireless 7265                                           | 3         | 2.1%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 3         | 2.1%    |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 3         | 2.1%    |
| Intel Centrino Ultimate-N 6300                                | 3         | 2.1%    |
| Intel Alder Lake-P PCH CNVi WiFi                              | 3         | 2.1%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                       | 2         | 1.4%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter              | 2         | 1.4%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 2         | 1.4%    |
| Intel Wireless 3165                                           | 2         | 1.4%    |
| Intel Wireless 3160                                           | 2         | 1.4%    |
| Intel Wi-Fi 6 AX201                                           | 2         | 1.4%    |
| Intel Tiger Lake PCH CNVi WiFi                                | 2         | 1.4%    |
| Broadcom Limited BCM43228 802.11a/b/g/n                       | 2         | 1.4%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 2         | 1.4%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 1         | 0.7%    |
| TP-Link RTL8812AU Archer T4U 802.11ac                         | 1         | 0.7%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]    | 1         | 0.7%    |
| TP-Link 802.11ac NIC                                          | 1         | 0.7%    |
| Sitecom Europe WL-113 rev 2 Wireless Network USB Adapter      | 1         | 0.7%    |
| Sierra Wireless EM7305                                        | 1         | 0.7%    |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 1         | 0.7%    |
| Realtek RTL8723DE Wireless Network Adapter                    | 1         | 0.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 1         | 0.7%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter               | 1         | 0.7%    |
| Realtek RTL8191SEvB Wireless LAN Controller                   | 1         | 0.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 1         | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 97        | 48.5%   |
| Intel                    | 66        | 33%     |
| Broadcom                 | 11        | 5.5%    |
| Qualcomm Atheros         | 8         | 4%      |
| ASIX Electronics         | 6         | 3%      |
| Nvidia                   | 4         | 2%      |
| Broadcom Limited         | 2         | 1%      |
| VIA Technologies         | 1         | 0.5%    |
| Qualcomm                 | 1         | 0.5%    |
| Mellanox Technologies    | 1         | 0.5%    |
| Marvell Technology Group | 1         | 0.5%    |
| Huawei Technologies      | 1         | 0.5%    |
| Chelsio Communications   | 1         | 0.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 69        | 32.7%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 13        | 6.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 10        | 4.74%   |
| Realtek RTL8125 2.5GbE Controller                                      | 8         | 3.79%   |
| Intel I211 Gigabit Network Connection                                  | 8         | 3.79%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 2.37%   |
| Intel 82574L Gigabit Network Connection                                | 5         | 2.37%   |
| Intel I350 Gigabit Network Connection                                  | 4         | 1.9%    |
| Intel Ethernet Controller I225-V                                       | 4         | 1.9%    |
| Intel Ethernet Connection (2) I218-V                                   | 4         | 1.9%    |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 1.9%    |
| Nvidia MCP61 Ethernet                                                  | 3         | 1.42%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 1.42%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3         | 1.42%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 1.42%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 2         | 0.95%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 0.95%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2         | 0.95%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 2         | 0.95%   |
| Intel Ethernet Connection I217-V                                       | 2         | 0.95%   |
| Intel Ethernet Connection (7) I219-V                                   | 2         | 0.95%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 0.95%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 0.95%   |
| Intel Ethernet Connection (2) I219-V                                   | 2         | 0.95%   |
| Intel 82579V Gigabit Network Connection                                | 2         | 0.95%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 2         | 0.95%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 2         | 0.95%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 2         | 0.95%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                        | 2         | 0.95%   |
| VIA VT6105/VT6106S [Rhine-III]                                         | 1         | 0.47%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 1         | 0.47%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller            | 1         | 0.47%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.47%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.47%   |
| Qualcomm Airtel 4G                                                     | 1         | 0.47%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.47%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                  | 1         | 0.47%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 1         | 0.47%   |
| Intel Ethernet Controller I226-V                                       | 1         | 0.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 183       | 57.01%  |
| WiFi     | 137       | 42.68%  |
| Modem    | 1         | 0.31%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 108       | 54%     |
| WiFi     | 92        | 46%     |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 102       | 50.25%  |
| 1     | 75        | 36.95%  |
| 3     | 9         | 4.43%   |
| 0     | 9         | 4.43%   |
| 4     | 5         | 2.46%   |
| 5     | 2         | 0.99%   |
| 6     | 1         | 0.49%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 172       | 84.31%  |
| Yes  | 32        | 15.69%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 61        | 48.8%   |
| Cambridge Silicon Radio         | 14        | 11.2%   |
| Realtek Semiconductor           | 13        | 10.4%   |
| Broadcom                        | 10        | 8%      |
| MediaTek                        | 6         | 4.8%    |
| Qualcomm Atheros Communications | 5         | 4%      |
| IMC Networks                    | 5         | 4%      |
| Foxconn / Hon Hai               | 3         | 2.4%    |
| Micro Star International        | 2         | 1.6%    |
| Apple                           | 2         | 1.6%    |
| USI                             | 1         | 0.8%    |
| TP-Link                         | 1         | 0.8%    |
| Toshiba                         | 1         | 0.8%    |
| ASUSTek Computer                | 1         | 0.8%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                   | 23        | 18.4%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)  | 14        | 11.2%   |
| Intel AX201 Bluetooth                                | 9         | 7.2%    |
| Intel AX200 Bluetooth                                | 9         | 7.2%    |
| Realtek  Bluetooth 4.2 Adapter                       | 6         | 4.8%    |
| MediaTek Wireless_Device                             | 6         | 4.8%    |
| Realtek Bluetooth Radio                              | 5         | 4%      |
| Intel AX210 Bluetooth                                | 5         | 4%      |
| Intel Wireless-AC 9260 Bluetooth Adapter             | 4         | 3.2%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)       | 4         | 3.2%    |
| IMC Networks Wireless_Device                         | 4         | 3.2%    |
| Qualcomm Atheros  Bluetooth Device                   | 3         | 2.4%    |
| Intel Wireless-AC 3168 Bluetooth                     | 3         | 2.4%    |
| Intel AX211 Bluetooth                                | 3         | 2.4%    |
| Broadcom BCM20702A0 Bluetooth 4.0                    | 3         | 2.4%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]           | 2         | 1.6%    |
| USI Bluetooth Device                                 | 1         | 0.8%    |
| TP-Link TP-Link Bluetooth USB Adapter                | 1         | 0.8%    |
| Toshiba Askey Bluetooth Module                       | 1         | 0.8%    |
| Realtek RTL8723B Bluetooth                           | 1         | 0.8%    |
| Realtek 802.11ac WLAN Adapter                        | 1         | 0.8%    |
| Qualcomm Atheros Dell Wireless 1802 Bluetooth 4.0 LE | 1         | 0.8%    |
| Qualcomm Atheros AR3011 Bluetooth                    | 1         | 0.8%    |
| Micro Star International Bluetooth Dongle            | 1         | 0.8%    |
| Micro Star International Bluetooth Device            | 1         | 0.8%    |
| Intel Centrino Bluetooth Wireless Transceiver        | 1         | 0.8%    |
| IMC Networks Bluetooth Radio                         | 1         | 0.8%    |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter         | 1         | 0.8%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller      | 1         | 0.8%    |
| Foxconn / Hon Hai Bluetooth Device                   | 1         | 0.8%    |
| Broadcom HP Portable Valentine                       | 1         | 0.8%    |
| Broadcom HP Portable SoftSailing                     | 1         | 0.8%    |
| Broadcom BCM20702A0                                  | 1         | 0.8%    |
| Broadcom BCM2045B (BDC-2.1)                          | 1         | 0.8%    |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]     | 1         | 0.8%    |
| ASUS ASUS USB-BT500                                  | 1         | 0.8%    |
| Apple Bluetooth USB Host Controller                  | 1         | 0.8%    |
| Apple Bluetooth HCI MacBookPro (HID mode)            | 1         | 0.8%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 120       | 43.8%   |
| AMD                      | 71        | 25.91%  |
| Nvidia                   | 49        | 17.88%  |
| Creative Labs            | 9         | 3.28%   |
| C-Media Electronics      | 5         | 1.82%   |
| Micro Star International | 3         | 1.09%   |
| Texas Instruments        | 2         | 0.73%   |
| Kingston Technology      | 2         | 0.73%   |
| ASUSTek Computer         | 2         | 0.73%   |
| VIA Technologies         | 1         | 0.36%   |
| RME                      | 1         | 0.36%   |
| M-Audio                  | 1         | 0.36%   |
| Jieli Technology         | 1         | 0.36%   |
| Holtek Semiconductor     | 1         | 0.36%   |
| Generalplus Technology   | 1         | 0.36%   |
| EGO SYStems              | 1         | 0.36%   |
| DSEA A/S                 | 1         | 0.36%   |
| Creative Technology      | 1         | 0.36%   |
| Corsair                  | 1         | 0.36%   |
| AlfaPlus Semiconductor   | 1         | 0.36%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 28        | 8.19%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 17        | 4.97%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 16        | 4.68%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 14        | 4.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10        | 2.92%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 10        | 2.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8         | 2.34%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 2.05%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 2.05%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 7         | 2.05%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 1.75%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 6         | 1.75%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 6         | 1.75%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 5         | 1.46%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 1.46%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 1.46%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.46%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 5         | 1.46%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 5         | 1.46%   |
| AMD FCH Azalia Controller                                                                         | 5         | 1.46%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 5         | 1.46%   |
| Nvidia MCP61 High Definition Audio                                                                | 4         | 1.17%   |
| Nvidia GA107 High Definition Audio Controller                                                     | 4         | 1.17%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 1.17%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.17%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 1.17%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 1.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.17%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 4         | 1.17%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.17%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus]   | 4         | 1.17%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 1.17%   |
| AMD Navi 31 HDMI/DP Audio                                                                         | 4         | 1.17%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 4         | 1.17%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.88%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 0.88%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.88%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.88%   |
| Micro Star International USB Audio                                                                | 3         | 0.88%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 0.88%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 36        | 17.65%  |
| Samsung Electronics | 34        | 16.67%  |
| Kingston            | 30        | 14.71%  |
| Corsair             | 19        | 9.31%   |
| Micron Technology   | 16        | 7.84%   |
| Crucial             | 15        | 7.35%   |
| Unknown             | 12        | 5.88%   |
| G.Skill             | 7         | 3.43%   |
| Team                | 4         | 1.96%   |
| A-DATA Technology   | 4         | 1.96%   |
| Unknown             | 3         | 1.47%   |
| Transcend           | 2         | 0.98%   |
| Smart               | 2         | 0.98%   |
| Ramaxel Technology  | 2         | 0.98%   |
| GOODRAM             | 2         | 0.98%   |
| Elpida              | 2         | 0.98%   |
| AMD                 | 2         | 0.98%   |
| Strontium           | 1         | 0.49%   |
| Silicon Power       | 1         | 0.49%   |
| Patriot             | 1         | 0.49%   |
| Neo Forza           | 1         | 0.49%   |
| Nanya Technology    | 1         | 0.49%   |
| Innodisk            | 1         | 0.49%   |
| HPE                 | 1         | 0.49%   |
| Hewlett-Packard     | 1         | 0.49%   |
| GLOWAY              | 1         | 0.49%   |
| Essencore Limited   | 1         | 0.49%   |
| Avant               | 1         | 0.49%   |
| A Force             | 1         | 0.49%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 1.78%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.33%   |
| Unknown                                                          | 3         | 1.33%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 2         | 0.89%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s               | 2         | 0.89%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.89%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 0.89%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 0.89%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 2         | 0.89%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 2         | 0.89%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.89%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 2         | 0.89%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s              | 2         | 0.89%   |
| Kingston RAM KF2666C15S4/16G 16GB SODIMM DDR4 2667MT/s           | 2         | 0.89%   |
| Corsair RAM CMZ32GX3M4X1600C10 8GB DIMM DDR3 1600MT/s            | 2         | 0.89%   |
| Corsair RAM CMSX32GX4M2A2666C18 16GB SODIMM DDR4 2667MT/s        | 2         | 0.89%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 2         | 0.89%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 0.44%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                        | 1         | 0.44%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                         | 1         | 0.44%   |
| Unknown RAM Module 4096MB DIMM DDR3 65535MT/s                    | 1         | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.44%   |
| Unknown RAM Module 2GB DIMM DDR2 533MT/s                         | 1         | 0.44%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                         | 1         | 0.44%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                       | 1         | 0.44%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                           | 1         | 0.44%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                           | 1         | 0.44%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                    | 1         | 0.44%   |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s                       | 1         | 0.44%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                           | 1         | 0.44%   |
| Transcend RAM TS256MLQ72V6U 2GB DIMM DDR2 667MT/s                | 1         | 0.44%   |
| Transcend RAM JM1600KLN-8GK 4096MB DIMM DDR3 1600MT/s            | 1         | 0.44%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3733MT/s               | 1         | 0.44%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s              | 1         | 0.44%   |
| Strontium RAM SRT4G86U1-P9H 4GB DIMM DDR3 1333MT/s               | 1         | 0.44%   |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s            | 1         | 0.44%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s              | 1         | 0.44%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s          | 1         | 0.44%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 0.44%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2400MT/s                    | 1         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 84        | 47.46%  |
| DDR3    | 60        | 33.9%   |
| DDR2    | 7         | 3.95%   |
| LPDDR3  | 5         | 2.82%   |
| DDR5    | 5         | 2.82%   |
| SDRAM   | 4         | 2.26%   |
| LPDDR5  | 4         | 2.26%   |
| LPDDR4  | 4         | 2.26%   |
| DDR     | 2         | 1.13%   |
| Unknown | 2         | 1.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 87        | 48.88%  |
| SODIMM       | 79        | 44.38%  |
| Row Of Chips | 9         | 5.06%   |
| RIMM         | 1         | 0.56%   |
| FB-DIMM      | 1         | 0.56%   |
| Chip         | 1         | 0.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 82        | 41.41%  |
| 4096  | 49        | 24.75%  |
| 16384 | 34        | 17.17%  |
| 2048  | 16        | 8.08%   |
| 32768 | 11        | 5.56%   |
| 1024  | 6         | 3.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 38        | 19.29%  |
| 3200    | 29        | 14.72%  |
| 2667    | 18        | 9.14%   |
| 2400    | 15        | 7.61%   |
| 1333    | 11        | 5.58%   |
| 3600    | 10        | 5.08%   |
| 2133    | 10        | 5.08%   |
| 1334    | 6         | 3.05%   |
| 1867    | 5         | 2.54%   |
| 667     | 5         | 2.54%   |
| 4800    | 4         | 2.03%   |
| 3800    | 4         | 2.03%   |
| 2800    | 3         | 1.52%   |
| 2666    | 3         | 1.52%   |
| 1866    | 3         | 1.52%   |
| 533     | 3         | 1.52%   |
| Unknown | 3         | 1.52%   |
| 6400    | 2         | 1.02%   |
| 4267    | 2         | 1.02%   |
| 3733    | 2         | 1.02%   |
| 3000    | 2         | 1.02%   |
| 2000    | 2         | 1.02%   |
| 975     | 2         | 1.02%   |
| 800     | 2         | 1.02%   |
| 65535   | 1         | 0.51%   |
| 8600    | 1         | 0.51%   |
| 6000    | 1         | 0.51%   |
| 4266    | 1         | 0.51%   |
| 4199    | 1         | 0.51%   |
| 4000    | 1         | 0.51%   |
| 3666    | 1         | 0.51%   |
| 3400    | 1         | 0.51%   |
| 2933    | 1         | 0.51%   |
| 2733    | 1         | 0.51%   |
| 2200    | 1         | 0.51%   |
| 1066    | 1         | 0.51%   |
| 701     | 1         | 0.51%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 27.27%  |
| Brother Industries  | 3         | 27.27%  |
| QinHeng Electronics | 2         | 18.18%  |
| Prolific Technology | 1         | 9.09%   |
| Dell                | 1         | 9.09%   |
| Canon               | 1         | 9.09%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| QinHeng CH340S                | 2         | 18.18%  |
| Prolific PL2305 Parallel Port | 1         | 9.09%   |
| HP OfficeJet Pro 9010 series  | 1         | 9.09%   |
| HP ENVY 4520 series           | 1         | 9.09%   |
| HP ENVY 4500 series           | 1         | 9.09%   |
| Dell 2330d Laser Printer      | 1         | 9.09%   |
| Canon CanoScan LiDE 300       | 1         | 9.09%   |
| Brother Printer               | 1         | 9.09%   |
| Brother HL-L5102DW            | 1         | 9.09%   |
| Brother HL-L2320D series      | 1         | 9.09%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 2         | 50%     |
| Seiko Epson     | 1         | 25%     |
| Hewlett-Packard | 1         | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1         | 25%     |
| HP ScanJet 5590                               | 1         | 25%     |
| Canon CanoScan N670U/N676U/LiDE 20            | 1         | 25%     |
| Canon CanoScan LIDE 25                        | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 25        | 24.27%  |
| Logitech                               | 13        | 12.62%  |
| Realtek Semiconductor                  | 8         | 7.77%   |
| Bison Electronics                      | 7         | 6.8%    |
| Microdia                               | 6         | 5.83%   |
| Acer                                   | 6         | 5.83%   |
| Sunplus Innovation Technology          | 5         | 4.85%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 4.85%   |
| Luxvisions Innotech Limited            | 4         | 3.88%   |
| IMC Networks                           | 4         | 3.88%   |
| Syntek                                 | 3         | 2.91%   |
| Sonix Technology                       | 3         | 2.91%   |
| Quanta                                 | 3         | 2.91%   |
| Lite-On Technology                     | 3         | 2.91%   |
| Samsung Electronics                    | 2         | 1.94%   |
| Z-Star Microelectronics                | 1         | 0.97%   |
| Silicon Motion                         | 1         | 0.97%   |
| Motorola PCS                           | 1         | 0.97%   |
| Microsoft                              | 1         | 0.97%   |
| Lenovo                                 | 1         | 0.97%   |
| Apple                                  | 1         | 0.97%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 5         | 4.85%   |
| Bison HD Webcam                                      | 4         | 3.88%   |
| Acer BisonCam,NB Pro                                 | 4         | 3.88%   |
| Logitech Webcam C270                                 | 3         | 2.91%   |
| Syntek Integrated Camera                             | 2         | 1.94%   |
| Sunplus Integrated_Webcam_HD                         | 2         | 1.94%   |
| Sonix USB2.0 FHD UVC WebCam                          | 2         | 1.94%   |
| Samsung Galaxy series, misc. (MTP mode)              | 2         | 1.94%   |
| Quanta HP Webcam                                     | 2         | 1.94%   |
| Microdia Integrated_Webcam_HD                        | 2         | 1.94%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 2         | 1.94%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 2         | 1.94%   |
| Logitech HD Pro Webcam C920                          | 2         | 1.94%   |
| Chicony Integrated Camera (1280x720@30)              | 2         | 1.94%   |
| Chicony HP TrueVision HD Camera                      | 2         | 1.94%   |
| Chicony HD User Facing                               | 2         | 1.94%   |
| Chicony FJ Camera                                    | 2         | 1.94%   |
| Bison Integrated Camera                              | 2         | 1.94%   |
| Z-Star Vimicro USB2.0 Camera                         | 1         | 0.97%   |
| Syntek USB2.0 Camera                                 | 1         | 0.97%   |
| Sunplus Laptop_Integrated_Webcam_FHD                 | 1         | 0.97%   |
| Sunplus Full HD webcam                               | 1         | 0.97%   |
| Sunplus DICOTA 4K                                    | 1         | 0.97%   |
| Sonix USB2.0 HD UVC WebCam                           | 1         | 0.97%   |
| Silicon Motion Web Camera                            | 1         | 0.97%   |
| Realtek USB Camera                                   | 1         | 0.97%   |
| Realtek Laptop Camera                                | 1         | 0.97%   |
| Realtek Integrated_Webcam_HD                         | 1         | 0.97%   |
| Realtek Integrated Webcam                            | 1         | 0.97%   |
| Realtek Integrated Camera                            | 1         | 0.97%   |
| Realtek EasyCamera                                   | 1         | 0.97%   |
| Realtek Bluetooth Radio                              | 1         | 0.97%   |
| Realtek 2SF022                                       | 1         | 0.97%   |
| Quanta HP Wide Vision HD Camera                      | 1         | 0.97%   |
| Motorola PCS XT1033 [Moto G], PTP mode               | 1         | 0.97%   |
| Microsoft LifeCam HD-3000                            | 1         | 0.97%   |
| Microdia Laptop_Integrated_Webcam_2M                 | 1         | 0.97%   |
| Microdia Integrated Webcam                           | 1         | 0.97%   |
| Microdia Dell Integrated HD Webcam                   | 1         | 0.97%   |
| Microdia Camera                                      | 1         | 0.97%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 10        | 41.67%  |
| Synaptics                          | 4         | 16.67%  |
| STMicroelectronics                 | 2         | 8.33%   |
| Shenzhen Goodix Technology         | 2         | 8.33%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 8.33%   |
| Elan Microelectronics              | 2         | 8.33%   |
| Upek                               | 1         | 4.17%   |
| LighTuning Technology              | 1         | 4.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                                 | 3         | 12.5%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 2         | 8.33%   |
| STMicroelectronics Fingerprint Reader                           | 2         | 8.33%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 2         | 8.33%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 1         | 4.17%   |
| Validity Sensors VFS451 Fingerprint Reader                      | 1         | 4.17%   |
| Validity Sensors VFS300 Fingerprint Reader                      | 1         | 4.17%   |
| Validity Sensors VFS Fingerprint sensor                         | 1         | 4.17%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 1         | 4.17%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 1         | 4.17%   |
| Synaptics WBDI Device                                           | 1         | 4.17%   |
| Synaptics TouchPad                                              | 1         | 4.17%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 1         | 4.17%   |
| Shenzhen Goodix  FingerPrint Device                             | 1         | 4.17%   |
| Shenzhen Goodix Fingerprint Reader                              | 1         | 4.17%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 1         | 4.17%   |
| Elan ELAN:Fingerprint                                           | 1         | 4.17%   |
| Elan ELAN:ARM-M4                                                | 1         | 4.17%   |
| Unknown                                                         | 1         | 4.17%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 4         | 36.36%  |
| Broadcom              | 3         | 27.27%  |
| Upek                  | 1         | 9.09%   |
| O2 Micro              | 1         | 9.09%   |
| Lenovo                | 1         | 9.09%   |
| Gemalto (was Gemplus) | 1         | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 4         | 36.36%  |
| Broadcom 5880                                              | 2         | 18.18%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 9.09%   |
| O2 Micro OZ776 CCID Smartcard Reader                       | 1         | 9.09%   |
| Lenovo Integrated Smart Card Reader                        | 1         | 9.09%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer     | 1         | 9.09%   |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 120       | 57.97%  |
| 1     | 51        | 24.64%  |
| 2     | 22        | 10.63%  |
| 3     | 7         | 3.38%   |
| 4     | 6         | 2.9%    |
| 5     | 1         | 0.48%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 27        | 20.15%  |
| Fingerprint reader       | 23        | 17.16%  |
| Sound                    | 19        | 14.18%  |
| Net/wireless             | 15        | 11.19%  |
| Communication controller | 10        | 7.46%   |
| Chipcard                 | 10        | 7.46%   |
| Multimedia controller    | 6         | 4.48%   |
| Unassigned class         | 5         | 3.73%   |
| Card reader              | 4         | 2.99%   |
| Camera                   | 4         | 2.99%   |
| Bluetooth                | 4         | 2.99%   |
| Net/ethernet             | 2         | 1.49%   |
| Storage/raid             | 1         | 0.75%   |
| Storage/ide              | 1         | 0.75%   |
| Storage/ata              | 1         | 0.75%   |
| Storage                  | 1         | 0.75%   |
| Firewire controller      | 1         | 0.75%   |

