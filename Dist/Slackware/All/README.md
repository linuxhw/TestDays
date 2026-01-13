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

Total: 268

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | B450M PRO-M2 MAX            | Desktop     | [9028b6c4b3](https://linux-hardware.org/?probe=9028b6c4b3) | Dec 03, 2025 |
| Loongson      | LS3A6000-7A2000-1w-V0.1-... | Desktop     | [8d642f41ea](https://linux-hardware.org/?probe=8d642f41ea) | Oct 15, 2025 |
| Lenovo        | ThinkPad T60 8744HDG        | Notebook    | [397feea269](https://linux-hardware.org/?probe=397feea269) | Aug 03, 2025 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [467e71b4b5](https://linux-hardware.org/?probe=467e71b4b5) | Jun 11, 2025 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [6d7c7e541d](https://linux-hardware.org/?probe=6d7c7e541d) | May 07, 2025 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [7c949afa7d](https://linux-hardware.org/?probe=7c949afa7d) | Mar 31, 2025 |
| ASUSTek       | P8H61-M PRO                 | Desktop     | [17eb905e70](https://linux-hardware.org/?probe=17eb905e70) | Feb 11, 2025 |
| Acer          | Nitro ANV15-41              | Notebook    | [103ad43d8e](https://linux-hardware.org/?probe=103ad43d8e) | Jan 13, 2025 |
| Dell          | 0HGFJM A00                  | Desktop     | [10a1898523](https://linux-hardware.org/?probe=10a1898523) | Jan 13, 2025 |
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

![OS](./images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Slackware 15.0  | 138       | 64.79%  |
| Slackware 14.2  | 63        | 29.58%  |
| Slackware 14.2+ | 8         | 3.76%   |
| Slackware 15.0+ | 3         | 1.41%   |
| Slackware 14.1  | 1         | 0.47%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Slackware | 210       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 5.15.19                     | 22        | 9.52%   |
| 4.19.80                     | 8         | 3.46%   |
| 5.19.17                     | 7         | 3.03%   |
| 5.15.63                     | 7         | 3.03%   |
| 5.15.145                    | 6         | 2.6%    |
| 5.10.28-Unraid              | 6         | 2.6%    |
| 5.19.17-Unraid              | 4         | 1.73%   |
| 5.15.27                     | 4         | 1.73%   |
| 5.15.161                    | 4         | 1.73%   |
| 5.15.117                    | 4         | 1.73%   |
| 4.4.190                     | 4         | 1.73%   |
| 5.15.94                     | 3         | 1.3%    |
| 5.15.38                     | 3         | 1.3%    |
| 4.4.240                     | 3         | 1.3%    |
| 6.6.22                      | 2         | 0.87%   |
| 6.6.18                      | 2         | 0.87%   |
| 6.12.7                      | 2         | 0.87%   |
| 6.12.1                      | 2         | 0.87%   |
| 6.11.0-8-generic            | 2         | 0.87%   |
| 6.1.79-Unraid               | 2         | 0.87%   |
| 6.1.64-Unraid               | 2         | 0.87%   |
| 6.1.44                      | 2         | 0.87%   |
| 5.3.7                       | 2         | 0.87%   |
| 5.17.2                      | 2         | 0.87%   |
| 5.17.1                      | 2         | 0.87%   |
| 5.16.13                     | 2         | 0.87%   |
| 5.15.80                     | 2         | 0.87%   |
| 5.15.30-Unraid              | 2         | 0.87%   |
| 5.15.118                    | 2         | 0.87%   |
| 5.13.8                      | 2         | 0.87%   |
| 5.10.3                      | 2         | 0.87%   |
| 4.4.276                     | 2         | 0.87%   |
| 6.9.12                      | 1         | 0.43%   |
| 6.9.1                       | 1         | 0.43%   |
| 6.8.8                       | 1         | 0.43%   |
| 6.7.5-gsh-clevo-NL51NU-SW15 | 1         | 0.43%   |
| 6.7.4-cometdust             | 1         | 0.43%   |
| 6.6.8                       | 1         | 0.43%   |
| 6.6.7                       | 1         | 0.43%   |
| 6.6.28                      | 1         | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.19  | 22        | 9.52%   |
| 5.19.17  | 11        | 4.76%   |
| 4.19.80  | 8         | 3.46%   |
| 5.15.63  | 7         | 3.03%   |
| 5.15.145 | 6         | 2.6%    |
| 5.10.28  | 6         | 2.6%    |
| 4.4.190  | 5         | 2.16%   |
| 5.15.27  | 4         | 1.73%   |
| 5.15.161 | 4         | 1.73%   |
| 5.15.117 | 4         | 1.73%   |
| 5.15.94  | 3         | 1.3%    |
| 5.15.38  | 3         | 1.3%    |
| 4.4.240  | 3         | 1.3%    |
| 6.6.22   | 2         | 0.87%   |
| 6.6.18   | 2         | 0.87%   |
| 6.12.7   | 2         | 0.87%   |
| 6.12.1   | 2         | 0.87%   |
| 6.11.0   | 2         | 0.87%   |
| 6.1.79   | 2         | 0.87%   |
| 6.1.64   | 2         | 0.87%   |
| 6.1.44   | 2         | 0.87%   |
| 5.3.7    | 2         | 0.87%   |
| 5.17.2   | 2         | 0.87%   |
| 5.17.1   | 2         | 0.87%   |
| 5.16.13  | 2         | 0.87%   |
| 5.15.80  | 2         | 0.87%   |
| 5.15.30  | 2         | 0.87%   |
| 5.15.118 | 2         | 0.87%   |
| 5.14.15  | 2         | 0.87%   |
| 5.13.8   | 2         | 0.87%   |
| 5.10.3   | 2         | 0.87%   |
| 4.4.276  | 2         | 0.87%   |
| 6.9.12   | 1         | 0.43%   |
| 6.9.1    | 1         | 0.43%   |
| 6.8.8    | 1         | 0.43%   |
| 6.7.5    | 1         | 0.43%   |
| 6.7.4    | 1         | 0.43%   |
| 6.6.8    | 1         | 0.43%   |
| 6.6.7    | 1         | 0.43%   |
| 6.6.28   | 1         | 0.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 72        | 31.72%  |
| 4.4     | 17        | 7.49%   |
| 5.10    | 15        | 6.61%   |
| 4.19    | 15        | 6.61%   |
| 6.1     | 13        | 5.73%   |
| 5.4     | 13        | 5.73%   |
| 5.19    | 12        | 5.29%   |
| 6.6     | 10        | 4.41%   |
| 6.12    | 8         | 3.52%   |
| 5.14    | 7         | 3.08%   |
| 5.13    | 7         | 3.08%   |
| 5.17    | 6         | 2.64%   |
| 5.16    | 6         | 2.64%   |
| 6.10    | 5         | 2.2%    |
| 6.11    | 3         | 1.32%   |
| 6.9     | 2         | 0.88%   |
| 6.7     | 2         | 0.88%   |
| 5.3     | 2         | 0.88%   |
| 4.9     | 2         | 0.88%   |
| 6.8     | 1         | 0.44%   |
| 6.5     | 1         | 0.44%   |
| 6.4     | 1         | 0.44%   |
| 5.7     | 1         | 0.44%   |
| 5.5     | 1         | 0.44%   |
| 5.2     | 1         | 0.44%   |
| 5.12    | 1         | 0.44%   |
| 4.20    | 1         | 0.44%   |
| 4.16    | 1         | 0.44%   |
| 3.10    | 1         | 0.44%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| x86_64      | 206       | 98.1%   |
| aarch64     | 2         | 0.95%   |
| loongarch64 | 1         | 0.48%   |
| i686        | 1         | 0.48%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KDE5          | 64        | 29.77%  |
| XFCE          | 63        | 29.3%   |
| Unknown       | 62        | 28.84%  |
| KDE           | 5         | 2.33%   |
| MATE          | 4         | 1.86%   |
| GNOME         | 4         | 1.86%   |
| xwmconfig     | 2         | 0.93%   |
| FVWM          | 2         | 0.93%   |
| X-Generic     | 1         | 0.47%   |
| X-Cinnamon    | 1         | 0.47%   |
| weston        | 1         | 0.47%   |
| LXQt          | 1         | 0.47%   |
| Enlightenment | 1         | 0.47%   |
| DWM           | 1         | 0.47%   |
| Cinnamon      | 1         | 0.47%   |
| awesome       | 1         | 0.47%   |
| 2bwm          | 1         | 0.47%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 123       | 56.42%  |
| Tty     | 64        | 29.36%  |
| Unknown | 19        | 8.72%   |
| Wayland | 12        | 5.5%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 79        | 36.41%  |
| SDDM    | 76        | 35.02%  |
| XDM     | 48        | 22.12%  |
| LightDM | 6         | 2.76%   |
| SLiM    | 5         | 2.3%    |
| GDM     | 2         | 0.92%   |
| TDM     | 1         | 0.46%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 120       | 56.87%  |
| Unknown     | 47        | 22.27%  |
| it_IT       | 9         | 4.27%   |
| ru_RU       | 5         | 2.37%   |
| pt_BR       | 4         | 1.9%    |
| en_GB       | 4         | 1.9%    |
| fr_FR       | 3         | 1.42%   |
| de_DE       | 3         | 1.42%   |
| cs_CZ       | 2         | 0.95%   |
| zh_TW       | 1         | 0.47%   |
| zh_CN       | 1         | 0.47%   |
| us          | 1         | 0.47%   |
| sr_RS@latin | 1         | 0.47%   |
| pt_PT       | 1         | 0.47%   |
| pl_PL       | 1         | 0.47%   |
| ja_JP       | 1         | 0.47%   |
| es_ES.UTF8  | 1         | 0.47%   |
| es_ES       | 1         | 0.47%   |
| es_AR       | 1         | 0.47%   |
| en_US.ASCII | 1         | 0.47%   |
| en_SE       | 1         | 0.47%   |
| en_AU       | 1         | 0.47%   |
| C           | 1         | 0.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 111       | 52.36%  |
| BIOS | 101       | 47.64%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 155       | 73.11%  |
| Btrfs    | 21        | 9.91%   |
| Xfs      | 10        | 4.72%   |
| Overlay  | 9         | 4.25%   |
| Rootfs   | 7         | 3.3%    |
| Tmpfs    | 2         | 0.94%   |
| Reiserfs | 2         | 0.94%   |
| Jfs      | 2         | 0.94%   |
| Zfs      | 1         | 0.47%   |
| F2fs     | 1         | 0.47%   |
| Ext3     | 1         | 0.47%   |
| Ext2     | 1         | 0.47%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 141       | 65.89%  |
| MBR     | 49        | 22.9%   |
| Unknown | 24        | 11.21%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 147       | 68.69%  |
| Yes       | 67        | 31.31%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 144       | 68.25%  |
| Yes       | 67        | 31.75%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 36        | 17.14%  |
| Hewlett-Packard     | 33        | 15.71%  |
| Lenovo              | 29        | 13.81%  |
| Dell                | 22        | 10.48%  |
| MSI                 | 20        | 9.52%   |
| ASRock              | 13        | 6.19%   |
| Gigabyte Technology | 9         | 4.29%   |
| Acer                | 8         | 3.81%   |
| Toshiba             | 4         | 1.9%    |
| Notebook            | 4         | 1.9%    |
| Fujitsu             | 3         | 1.43%   |
| Apple               | 3         | 1.43%   |
| Supermicro          | 2         | 0.95%   |
| Dynabook            | 2         | 0.95%   |
| Unknown             | 2         | 0.95%   |
| Valve               | 1         | 0.48%   |
| TYAN Computer       | 1         | 0.48%   |
| System76            | 1         | 0.48%   |
| Sony                | 1         | 0.48%   |
| Shuttle             | 1         | 0.48%   |
| Samsung Electronics | 1         | 0.48%   |
| Radxa               | 1         | 0.48%   |
| NetGear             | 1         | 0.48%   |
| Microsoft           | 1         | 0.48%   |
| Loongson            | 1         | 0.48%   |
| Intel               | 1         | 0.48%   |
| Huanan              | 1         | 0.48%   |
| HPE                 | 1         | 0.48%   |
| HEDYCOMPUTER        | 1         | 0.48%   |
| Framework           | 1         | 0.48%   |
| Foxconn             | 1         | 0.48%   |
| Chuwi               | 1         | 0.48%   |
| Biostar             | 1         | 0.48%   |
| BESSTAR Tech        | 1         | 0.48%   |
| AMI                 | 1         | 0.48%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| ASUS All Series                          | 4         | 1.9%    |
| Toshiba Satellite C660                   | 2         | 0.95%   |
| MSI MS-7D76                              | 2         | 0.95%   |
| Lenovo V330-14ARR 81B1                   | 2         | 0.95%   |
| ASUS VivoBook_ASUSLaptop K6500ZE_K6500ZE | 2         | 0.95%   |
| ASRock N68-S3 FX                         | 2         | 0.95%   |
| Unknown                                  | 2         | 0.95%   |
| Valve Jupiter                            | 1         | 0.48%   |
| TYAN S7012                               | 1         | 0.48%   |
| Toshiba Satellite P50-A-12Z              | 1         | 0.48%   |
| Toshiba PORTEGE Z30-A                    | 1         | 0.48%   |
| System76 Oryx Pro                        | 1         | 0.48%   |
| Supermicro X9DRD-7LN4F(-JBOD)/X9DRD-EF   | 1         | 0.48%   |
| Supermicro X9DA7/E                       | 1         | 0.48%   |
| Sony SVE1713A1EW                         | 1         | 0.48%   |
| Shuttle NC03U                            | 1         | 0.48%   |
| Samsung 300E5M/300E5L                    | 1         | 0.48%   |
| Radxa ROCK Pi 4                          | 1         | 0.48%   |
| Notebook X170KM-G                        | 1         | 0.48%   |
| Notebook P7xxTM                          | 1         | 0.48%   |
| Notebook NL5xNU                          | 1         | 0.48%   |
| Notebook NL40_50CU                       | 1         | 0.48%   |
| NetGear ReadyDATA 5200                   | 1         | 0.48%   |
| MSI MS-7D67                              | 1         | 0.48%   |
| MSI MS-7C87                              | 1         | 0.48%   |
| MSI MS-7C52                              | 1         | 0.48%   |
| MSI MS-7C02                              | 1         | 0.48%   |
| MSI MS-7B84                              | 1         | 0.48%   |
| MSI MS-7B79                              | 1         | 0.48%   |
| MSI MS-7996                              | 1         | 0.48%   |
| MSI MS-7885                              | 1         | 0.48%   |
| MSI MS-7788                              | 1         | 0.48%   |
| MSI MS-7693                              | 1         | 0.48%   |
| MSI MS-7529                              | 1         | 0.48%   |
| MSI MS-7365                              | 1         | 0.48%   |
| MSI Modern 14 B5M                        | 1         | 0.48%   |
| MSI Modern 14 B11MO                      | 1         | 0.48%   |
| MSI Modern 14 B10MW                      | 1         | 0.48%   |
| MSI GP76 Leopard 11UG                    | 1         | 0.48%   |
| MSI GL73 8RC                             | 1         | 0.48%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 20        | 9.52%   |
| Dell Precision                | 8         | 3.81%   |
| ASUS PRIME                    | 8         | 3.81%   |
| HP Pavilion                   | 5         | 2.38%   |
| HP Laptop                     | 5         | 2.38%   |
| ASUS ROG                      | 5         | 2.38%   |
| Lenovo IdeaPad                | 4         | 1.9%    |
| ASUS All                      | 4         | 1.9%    |
| Toshiba Satellite             | 3         | 1.43%   |
| MSI Modern                    | 3         | 1.43%   |
| HP EliteBook                  | 3         | 1.43%   |
| Dell OptiPlex                 | 3         | 1.43%   |
| Dell Latitude                 | 3         | 1.43%   |
| ASUS VivoBook                 | 3         | 1.43%   |
| ASUS TUF                      | 3         | 1.43%   |
| Acer Aspire                   | 3         | 1.43%   |
| MSI MS-7D76                   | 2         | 0.95%   |
| Lenovo V330-14ARR             | 2         | 0.95%   |
| HP OMEN                       | 2         | 0.95%   |
| HP ENVY                       | 2         | 0.95%   |
| HP Compaq                     | 2         | 0.95%   |
| Gigabyte X570                 | 2         | 0.95%   |
| Fujitsu LIFEBOOK              | 2         | 0.95%   |
| Dell XPS                      | 2         | 0.95%   |
| Dell Vostro                   | 2         | 0.95%   |
| Dell PowerEdge                | 2         | 0.95%   |
| Dell Inspiron                 | 2         | 0.95%   |
| ASUS SABERTOOTH               | 2         | 0.95%   |
| ASRock N68-S3                 | 2         | 0.95%   |
| Acer Swift                    | 2         | 0.95%   |
| Acer Nitro                    | 2         | 0.95%   |
| Unknown                       | 2         | 0.95%   |
| Valve Jupiter                 | 1         | 0.48%   |
| TYAN S7012                    | 1         | 0.48%   |
| Toshiba PORTEGE               | 1         | 0.48%   |
| System76 Oryx                 | 1         | 0.48%   |
| Supermicro X9DRD-7LN4F(-JBOD) | 1         | 0.48%   |
| Supermicro X9DA7              | 1         | 0.48%   |
| Sony SVE1713A1EW              | 1         | 0.48%   |
| Shuttle NC03U                 | 1         | 0.48%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 24        | 11.43%  |
| 2019    | 20        | 9.52%   |
| 2012    | 18        | 8.57%   |
| 2021    | 17        | 8.1%    |
| 2022    | 15        | 7.14%   |
| 2018    | 15        | 7.14%   |
| 2015    | 15        | 7.14%   |
| 2017    | 14        | 6.67%   |
| 2014    | 12        | 5.71%   |
| 2011    | 11        | 5.24%   |
| 2016    | 9         | 4.29%   |
| 2008    | 8         | 3.81%   |
| 2010    | 7         | 3.33%   |
| 2013    | 5         | 2.38%   |
| 2009    | 5         | 2.38%   |
| 2007    | 5         | 2.38%   |
| 2024    | 4         | 1.9%    |
| 2023    | 3         | 1.43%   |
| Unknown | 2         | 0.95%   |
| 2006    | 1         | 0.48%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 97        | 46.19%  |
| Notebook       | 94        | 44.76%  |
| Mini pc        | 6         | 2.86%   |
| Server         | 4         | 1.9%    |
| Convertible    | 3         | 1.43%   |
| All in one     | 3         | 1.43%   |
| System on chip | 2         | 0.95%   |
| Tablet         | 1         | 0.48%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 210       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 207       | 98.57%  |
| Yes  | 3         | 1.43%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 45        | 21.03%  |
| 16.01-24.0      | 40        | 18.69%  |
| 4.01-8.0        | 37        | 17.29%  |
| 32.01-64.0      | 32        | 14.95%  |
| 3.01-4.0        | 24        | 11.21%  |
| 64.01-256.0     | 16        | 7.48%   |
| 24.01-32.0      | 10        | 4.67%   |
| 1.01-2.0        | 6         | 2.8%    |
| 2.01-3.0        | 2         | 0.93%   |
| More than 256.0 | 1         | 0.47%   |
| 0.51-1.0        | 1         | 0.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 54        | 23.79%  |
| 2.01-3.0    | 51        | 22.47%  |
| 4.01-8.0    | 46        | 20.26%  |
| 3.01-4.0    | 23        | 10.13%  |
| 0.51-1.0    | 22        | 9.69%   |
| 8.01-16.0   | 12        | 5.29%   |
| 0.01-0.5    | 6         | 2.64%   |
| 24.01-32.0  | 5         | 2.2%    |
| 16.01-24.0  | 5         | 2.2%    |
| 32.01-64.0  | 1         | 0.44%   |
| 64.01-256.0 | 1         | 0.44%   |
| Unknown     | 1         | 0.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 100       | 46.3%   |
| 2      | 51        | 23.61%  |
| 3      | 20        | 9.26%   |
| 4      | 16        | 7.41%   |
| 5      | 7         | 3.24%   |
| 6      | 6         | 2.78%   |
| 0      | 6         | 2.78%   |
| 10     | 2         | 0.93%   |
| 9      | 2         | 0.93%   |
| 29     | 1         | 0.46%   |
| 14     | 1         | 0.46%   |
| 13     | 1         | 0.46%   |
| 11     | 1         | 0.46%   |
| 8      | 1         | 0.46%   |
| 7      | 1         | 0.46%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 138       | 65.4%   |
| Yes       | 73        | 34.6%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 194       | 91.51%  |
| No        | 18        | 8.49%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 141       | 67.14%  |
| No        | 69        | 32.86%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 131       | 62.09%  |
| No        | 80        | 37.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 48        | 22.86%  |
| UK           | 17        | 8.1%    |
| Italy        | 13        | 6.19%   |
| Japan        | 12        | 5.71%   |
| Germany      | 12        | 5.71%   |
| Brazil       | 11        | 5.24%   |
| Russia       | 8         | 3.81%   |
| Portugal     | 8         | 3.81%   |
| Canada       | 8         | 3.81%   |
| France       | 7         | 3.33%   |
| Kazakhstan   | 6         | 2.86%   |
| India        | 6         | 2.86%   |
| Spain        | 5         | 2.38%   |
| Argentina    | 5         | 2.38%   |
| Sweden       | 4         | 1.9%    |
| South Africa | 3         | 1.43%   |
| Poland       | 3         | 1.43%   |
| Hong Kong    | 3         | 1.43%   |
| Greece       | 3         | 1.43%   |
| China        | 3         | 1.43%   |
| Serbia       | 2         | 0.95%   |
| Romania      | 2         | 0.95%   |
| Netherlands  | 2         | 0.95%   |
| Hungary      | 2         | 0.95%   |
| Czechia      | 2         | 0.95%   |
| Chile        | 2         | 0.95%   |
| Australia    | 2         | 0.95%   |
| Taiwan       | 1         | 0.48%   |
| Switzerland  | 1         | 0.48%   |
| Philippines  | 1         | 0.48%   |
| Paraguay     | 1         | 0.48%   |
| Mexico       | 1         | 0.48%   |
| Malaysia     | 1         | 0.48%   |
| Lithuania    | 1         | 0.48%   |
| Iran         | 1         | 0.48%   |
| Finland      | 1         | 0.48%   |
| Bulgaria     | 1         | 0.48%   |
| Belgium      | 1         | 0.48%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Tsukuba                | 7         | 3.23%   |
| Lisbon                 | 6         | 2.76%   |
| Ust-Kamenogorsk        | 4         | 1.84%   |
| Yekaterinburg          | 3         | 1.38%   |
| Warsaw                 | 3         | 1.38%   |
| Rome                   | 3         | 1.38%   |
| Paris                  | 3         | 1.38%   |
| New Delhi              | 3         | 1.38%   |
| Milan                  | 3         | 1.38%   |
| Chania                 | 3         | 1.38%   |
| Tokyo                  | 2         | 0.92%   |
| Tendo                  | 2         | 0.92%   |
| Sun Prairie            | 2         | 0.92%   |
| Springfield            | 2         | 0.92%   |
| Seattle                | 2         | 0.92%   |
| San Elizario           | 2         | 0.92%   |
| Moscow                 | 2         | 0.92%   |
| McKinney               | 2         | 0.92%   |
| Karcsa                 | 2         | 0.92%   |
| Karaganda              | 2         | 0.92%   |
| Greater Noida          | 2         | 0.92%   |
| Gainesville            | 2         | 0.92%   |
| Frignano               | 2         | 0.92%   |
| Fayetteville           | 2         | 0.92%   |
| Dallas                 | 2         | 0.92%   |
| Carrollton             | 2         | 0.92%   |
| Cape Town              | 2         | 0.92%   |
| Buenos Aires           | 2         | 0.92%   |
| Bucharest              | 2         | 0.92%   |
| Belgrade               | 2         | 0.92%   |
| Barry                  | 2         | 0.92%   |
| Barrie                 | 2         | 0.92%   |
| Amsterdam              | 2         | 0.92%   |
| Worpswede              | 1         | 0.46%   |
| Wokingham              | 1         | 0.46%   |
| Winter Springs         | 1         | 0.46%   |
| Winnipeg               | 1         | 0.46%   |
| Weilheim               | 1         | 0.46%   |
| Voskresensk            | 1         | 0.46%   |
| Visconde do Rio Branco | 1         | 0.46%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 60        | 133    | 16.95%  |
| Samsung Electronics         | 57        | 82     | 16.1%   |
| Seagate                     | 54        | 106    | 15.25%  |
| Kingston                    | 22        | 27     | 6.21%   |
| Toshiba                     | 20        | 37     | 5.65%   |
| Crucial                     | 14        | 16     | 3.95%   |
| Sandisk                     | 12        | 18     | 3.39%   |
| Intel                       | 10        | 12     | 2.82%   |
| SK hynix                    | 8         | 8      | 2.26%   |
| Hitachi                     | 8         | 11     | 2.26%   |
| Unknown                     | 7         | 10     | 1.98%   |
| HGST                        | 7         | 7      | 1.98%   |
| Hewlett-Packard             | 5         | 6      | 1.41%   |
| A-DATA Technology           | 5         | 5      | 1.41%   |
| Transcend                   | 4         | 4      | 1.13%   |
| Micron Technology           | 4         | 4      | 1.13%   |
| Team                        | 3         | 3      | 0.85%   |
| Patriot                     | 3         | 4      | 0.85%   |
| Micron/Crucial Technology   | 3         | 3      | 0.85%   |
| KIOXIA                      | 3         | 4      | 0.85%   |
| Gigabyte Technology         | 3         | 3      | 0.85%   |
| Apple                       | 3         | 4      | 0.85%   |
| Silicon Motion              | 2         | 3      | 0.56%   |
| Realtek Semiconductor       | 2         | 2      | 0.56%   |
| Maxtor                      | 2         | 2      | 0.56%   |
| LITEON                      | 2         | 2      | 0.56%   |
| Kingston Technology Company | 2         | 3      | 0.56%   |
| JMicron Technology          | 2         | 2      | 0.56%   |
| Fujitsu                     | 2         | 2      | 0.56%   |
| External                    | 2         | 2      | 0.56%   |
| China                       | 2         | 3      | 0.56%   |
| Unknown                     | 2         | 3      | 0.56%   |
| ZHITAI                      | 1         | 2      | 0.28%   |
| Verbatim                    | 1         | 2      | 0.28%   |
| TO Exter                    | 1         | 1      | 0.28%   |
| SSSTC                       | 1         | 1      | 0.28%   |
| PNY                         | 1         | 2      | 0.28%   |
| Plextor                     | 1         | 1      | 0.28%   |
| Pioneer                     | 1         | 1      | 0.28%   |
| Phison Electronics          | 1         | 1      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 7         | 1.61%   |
| Kingston SA400S37240G 240GB SSD                       | 7         | 1.61%   |
| Seagate ST4000DM004-2CV104 4TB                        | 5         | 1.15%   |
| WDC WD20EFRX-68EUZN0 2TB                              | 4         | 0.92%   |
| Seagate ST1000LM048-2E7172 1TB                        | 4         | 0.92%   |
| WDC WD40EZRX-00SPEB0 4TB                              | 3         | 0.69%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 3         | 0.69%   |
| WDC WD1003FZEX-00MK2A0 1TB                            | 3         | 0.69%   |
| Seagate ST4000VN006-3CW104 4TB                        | 3         | 0.69%   |
| Seagate ST2000DM008-2FR102 2TB                        | 3         | 0.69%   |
| Seagate ST1000DM010-2EP102 1TB                        | 3         | 0.69%   |
| Samsung SSD 970 EVO 250GB                             | 3         | 0.69%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 3         | 0.69%   |
| Intel SSD 660P Series 512GB                           | 3         | 0.69%   |
| Crucial CT500MX500SSD1 500GB                          | 3         | 0.69%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                        | 2         | 0.46%   |
| WDC WD5000AAKX-00ERMA0 500GB                          | 2         | 0.46%   |
| WDC WD40EFRX-68N32N0 4TB                              | 2         | 0.46%   |
| WDC WD30EZRX-00SPEB0 3TB                              | 2         | 0.46%   |
| WDC WD10SPZX-60Z10T0 1TB                              | 2         | 0.46%   |
| WDC WD10EZEX-00RKKA0 1TB                              | 2         | 0.46%   |
| WDC WD100EMAZ-00WJTA0 10TB                            | 2         | 0.46%   |
| Toshiba MQ04ABF100 1TB                                | 2         | 0.46%   |
| Toshiba MQ01ABD100 1TB                                | 2         | 0.46%   |
| Toshiba HDWD110 1TB                                   | 2         | 0.46%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB | 2         | 0.46%   |
| Seagate ST8000VN0022-2EL112 8TB                       | 2         | 0.46%   |
| Seagate ST500DM002-1BD142 500GB                       | 2         | 0.46%   |
| Seagate ST4000VN008-2DR166 4TB                        | 2         | 0.46%   |
| Seagate ST31000524AS 1TB                              | 2         | 0.46%   |
| Seagate ST2000DX001-1NS164 2TB                        | 2         | 0.46%   |
| Seagate ST2000DM001-1CH164 2TB                        | 2         | 0.46%   |
| Seagate ST2000DL003-9VT166 2TB                        | 2         | 0.46%   |
| Seagate ST1000DM003-1SB102 1TB                        | 2         | 0.46%   |
| Seagate ST1000DM003-1ER162 1TB                        | 2         | 0.46%   |
| Seagate Expansion Desk 4TB                            | 2         | 0.46%   |
| Samsung SSD 970 EVO Plus 500GB                        | 2         | 0.46%   |
| Samsung SSD 970 EVO Plus 1TB                          | 2         | 0.46%   |
| Samsung SSD 860 QVO 2TB                               | 2         | 0.46%   |
| Samsung SSD 850 PRO 256GB                             | 2         | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 54        | 102    | 33.96%  |
| WDC                 | 52        | 119    | 32.7%   |
| Toshiba             | 19        | 32     | 11.95%  |
| Hitachi             | 8         | 11     | 5.03%   |
| HGST                | 7         | 7      | 4.4%    |
| Samsung Electronics | 5         | 5      | 3.14%   |
| Maxtor              | 2         | 2      | 1.26%   |
| JMicron Technology  | 2         | 2      | 1.26%   |
| Hewlett-Packard     | 2         | 2      | 1.26%   |
| Fujitsu             | 2         | 2      | 1.26%   |
| External            | 2         | 2      | 1.26%   |
| Unknown             | 2         | 3      | 1.26%   |
| TO Exter            | 1         | 1      | 0.63%   |
| Apple               | 1         | 1      | 0.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 23        | 34     | 22.33%  |
| Kingston            | 19        | 23     | 18.45%  |
| Crucial             | 11        | 13     | 10.68%  |
| WDC                 | 6         | 8      | 5.83%   |
| SanDisk             | 6         | 7      | 5.83%   |
| Transcend           | 3         | 3      | 2.91%   |
| Team                | 2         | 2      | 1.94%   |
| Patriot             | 2         | 3      | 1.94%   |
| Micron Technology   | 2         | 2      | 1.94%   |
| Intel               | 2         | 3      | 1.94%   |
| Hewlett-Packard     | 2         | 2      | 1.94%   |
| China               | 2         | 3      | 1.94%   |
| Apple               | 2         | 3      | 1.94%   |
| A-DATA Technology   | 2         | 2      | 1.94%   |
| ZHITAI              | 1         | 1      | 0.97%   |
| Verbatim            | 1         | 2      | 0.97%   |
| Toshiba             | 1         | 3      | 0.97%   |
| SSSTC               | 1         | 1      | 0.97%   |
| SK hynix            | 1         | 1      | 0.97%   |
| PNY                 | 1         | 2      | 0.97%   |
| Plextor             | 1         | 1      | 0.97%   |
| Pioneer             | 1         | 1      | 0.97%   |
| Netac               | 1         | 1      | 0.97%   |
| LITEON              | 1         | 1      | 0.97%   |
| Lexar               | 1         | 1      | 0.97%   |
| KingSpec            | 1         | 1      | 0.97%   |
| Intenso             | 1         | 1      | 0.97%   |
| HS-SSD-C100         | 1         | 1      | 0.97%   |
| GOODRAM             | 1         | 1      | 0.97%   |
| Gigabyte Technology | 1         | 1      | 0.97%   |
| DUEX                | 1         | 1      | 0.97%   |
| Dogfish             | 1         | 1      | 0.97%   |
| AirDisk             | 1         | 1      | 0.97%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 113       | 291    | 37.67%  |
| SSD     | 93        | 131    | 31%     |
| NVMe    | 87        | 119    | 29%     |
| MMC     | 6         | 8      | 2%      |
| Unknown | 1         | 4      | 0.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 154       | 405    | 59.23%  |
| NVMe | 87        | 119    | 33.46%  |
| SAS  | 13        | 21     | 5%      |
| MMC  | 6         | 8      | 2.31%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 105       | 152    | 43.39%  |
| 0.51-1.0   | 63        | 113    | 26.03%  |
| 1.01-2.0   | 26        | 33     | 10.74%  |
| 3.01-4.0   | 23        | 47     | 9.5%    |
| 4.01-10.0  | 12        | 44     | 4.96%   |
| 2.01-3.0   | 9         | 21     | 3.72%   |
| 10.01-20.0 | 4         | 12     | 1.65%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 47        | 21.76%  |
| 101-250        | 45        | 20.83%  |
| 251-500        | 32        | 14.81%  |
| 1001-2000      | 26        | 12.04%  |
| Unknown        | 23        | 10.65%  |
| More than 3000 | 12        | 5.56%   |
| 2001-3000      | 11        | 5.09%   |
| 1-20           | 10        | 4.63%   |
| 51-100         | 7         | 3.24%   |
| 21-50          | 3         | 1.39%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 41        | 18.55%  |
| 1-20           | 31        | 14.03%  |
| 251-500        | 30        | 13.57%  |
| 21-50          | 27        | 12.22%  |
| 501-1000       | 26        | 11.76%  |
| Unknown        | 23        | 10.41%  |
| 51-100         | 22        | 9.95%   |
| 1001-2000      | 12        | 5.43%   |
| More than 3000 | 5         | 2.26%   |
| 2001-3000      | 4         | 1.81%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD20EFRX-68EUZN0 2TB              | 2         | 3      | 3.92%   |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1         | 1      | 1.96%   |
| WDC WD5003ABYX-18WERA0 500GB          | 1         | 2      | 1.96%   |
| WDC WD5003ABYX-01WERA0 500GB          | 1         | 1      | 1.96%   |
| WDC WD5000LPCX-60VHAT1 500GB          | 1         | 1      | 1.96%   |
| WDC WD5000BPKX-60HPJT0 500GB          | 1         | 1      | 1.96%   |
| WDC WD5000AAKX-22ERMA0 500GB          | 1         | 1      | 1.96%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 1         | 1      | 1.96%   |
| WDC WD5000AAKS-00A7B2 500GB           | 1         | 1      | 1.96%   |
| WDC WD40EFRX-68WT0N0 4TB              | 1         | 2      | 1.96%   |
| WDC WD40EFAX-68JH4N1 4TB              | 1         | 4      | 1.96%   |
| WDC WD3200AAJS-65B4A0 320GB           | 1         | 1      | 1.96%   |
| WDC WD30EZRX-00MMMB0 3TB              | 1         | 1      | 1.96%   |
| WDC WD30EZRX-00M                      | 1         | 1      | 1.96%   |
| WDC WD30EZRX-00D8PB0 3TB              | 1         | 1      | 1.96%   |
| WDC WD30EFRX-68AX9N0 3TB              | 1         | 4      | 1.96%   |
| WDC WD20PURZ-85GU6Y0 2TB              | 1         | 1      | 1.96%   |
| WDC WD20EARX-00PASB0 2TB              | 1         | 1      | 1.96%   |
| WDC WD10JPLX-00MBPT0 1TB              | 1         | 1      | 1.96%   |
| WDC WD10EZEX-00RKKA0 1TB              | 1         | 1      | 1.96%   |
| WDC WD10EALS-00Z8A0 1TB               | 1         | 2      | 1.96%   |
| WDC WD1003FZEX-00MK2A0 1TB            | 1         | 2      | 1.96%   |
| Toshiba MK2565GSXN 250GB              | 1         | 1      | 1.96%   |
| SSSTC CVB-8D128-HP 128GB              | 1         | 1      | 1.96%   |
| Seagate ST380011A 80GB                | 1         | 2      | 1.96%   |
| Seagate ST3500630AS 500GB             | 1         | 1      | 1.96%   |
| Seagate ST3500418AS 500GB             | 1         | 1      | 1.96%   |
| Seagate ST3500410AS 500GB             | 1         | 1      | 1.96%   |
| Seagate ST31000524AS 1TB              | 1         | 1      | 1.96%   |
| Seagate ST3000VX006-1HH166 3TB        | 1         | 1      | 1.96%   |
| Seagate ST2000DL003-9VT166 2TB        | 1         | 1      | 1.96%   |
| Seagate ST1000VM002-1SD102 1TB        | 1         | 1      | 1.96%   |
| Seagate ST1000NM0011 1TB              | 1         | 2      | 1.96%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 1.96%   |
| Seagate ST1000LM014-1EJ164 1TB        | 1         | 1      | 1.96%   |
| Seagate ST1000DM003-1ER162 1TB        | 1         | 2      | 1.96%   |
| SanDisk SDSA6MM-016G-1006 16GB SSD    | 1         | 1      | 1.96%   |
| Samsung Electronics SSD 970 EVO 500GB | 1         | 1      | 1.96%   |
| Samsung Electronics SSD 870 EVO 1TB   | 1         | 1      | 1.96%   |
| Plextor PX-128M6S 128GB SSD           | 1         | 1      | 1.96%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 20        | 34     | 42.55%  |
| Seagate             | 11        | 15     | 23.4%   |
| Hitachi             | 3         | 3      | 6.38%   |
| HGST                | 3         | 3      | 6.38%   |
| Samsung Electronics | 2         | 2      | 4.26%   |
| Toshiba             | 1         | 1      | 2.13%   |
| SSSTC               | 1         | 1      | 2.13%   |
| SanDisk             | 1         | 1      | 2.13%   |
| Plextor             | 1         | 1      | 2.13%   |
| Maxtor              | 1         | 1      | 2.13%   |
| Intel               | 1         | 1      | 2.13%   |
| DUEX                | 1         | 1      | 2.13%   |
| Unknown             | 1         | 1      | 2.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 19        | 33     | 48.72%  |
| Seagate | 11        | 15     | 28.21%  |
| Hitachi | 3         | 3      | 7.69%   |
| HGST    | 3         | 3      | 7.69%   |
| Toshiba | 1         | 1      | 2.56%   |
| Maxtor  | 1         | 1      | 2.56%   |
| Unknown | 1         | 1      | 2.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 36        | 57     | 81.82%  |
| SSD  | 7         | 7      | 15.91%  |
| NVMe | 1         | 1      | 2.27%   |

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
| Works    | 167       | 400    | 65.49%  |
| Detected | 44        | 88     | 17.25%  |
| Malfunc  | 44        | 65     | 17.25%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 120       | 39.22%  |
| AMD                             | 56        | 18.3%   |
| Samsung Electronics             | 34        | 11.11%  |
| ASMedia Technology              | 15        | 4.9%    |
| SanDisk                         | 11        | 3.59%   |
| Marvell Technology Group        | 8         | 2.61%   |
| SK hynix                        | 7         | 2.29%   |
| Micron/Crucial Technology       | 6         | 1.96%   |
| Kingston Technology Company     | 6         | 1.96%   |
| Realtek Semiconductor           | 5         | 1.63%   |
| Nvidia                          | 5         | 1.63%   |
| JMicron Technology              | 4         | 1.31%   |
| Broadcom / LSI                  | 4         | 1.31%   |
| Phison Electronics              | 3         | 0.98%   |
| KIOXIA                          | 3         | 0.98%   |
| Silicon Motion                  | 2         | 0.65%   |
| Micron Technology               | 2         | 0.65%   |
| MAXIO Technology (Hangzhou)     | 2         | 0.65%   |
| LSI Logic / Symbios Logic       | 2         | 0.65%   |
| Lite-On Technology              | 2         | 0.65%   |
| Yangtze Memory Technologies     | 1         | 0.33%   |
| Toshiba America Info Systems    | 1         | 0.33%   |
| Silicon Image                   | 1         | 0.33%   |
| Nextorage                       | 1         | 0.33%   |
| Loongson Technology             | 1         | 0.33%   |
| Hefei DATANG Storage Technology | 1         | 0.33%   |
| Biwin Storage Technology        | 1         | 0.33%   |
| Adaptec                         | 1         | 0.33%   |
| 3ware                           | 1         | 0.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 35        | 9.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 18        | 5%      |
| AMD 400 Series Chipset SATA Controller                                           | 14        | 3.89%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                    | 11        | 3.06%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 8         | 2.22%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 8         | 2.22%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 8         | 2.22%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 1.94%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 7         | 1.94%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 6         | 1.67%   |
| AMD 500 Series Chipset SATA Controller                                           | 6         | 1.67%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 5         | 1.39%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 1.39%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 4         | 1.11%   |
| Nvidia MCP61 SATA Controller                                                     | 4         | 1.11%   |
| Nvidia MCP61 IDE                                                                 | 4         | 1.11%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 1.11%   |
| Intel Volume Management Device NVMe RAID Controller                              | 4         | 1.11%   |
| Intel SATA Controller [RAID mode]                                                | 4         | 1.11%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 4         | 1.11%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 4         | 1.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 1.11%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 4         | 1.11%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 1.11%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 3         | 0.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 0.83%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 3         | 0.83%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 3         | 0.83%   |
| Intel SSD 660P Series                                                            | 3         | 0.83%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 0.83%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 3         | 0.83%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 3         | 0.83%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 0.83%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 3         | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 3         | 0.83%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 3         | 0.83%   |
| AMD 600 Series Chipset SATA Controller                                           | 3         | 0.83%   |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                                | 2         | 0.56%   |
| SK hynix BC511 NVMe SSD                                                          | 2         | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 150       | 50.85%  |
| NVMe | 88        | 29.83%  |
| IDE  | 26        | 8.81%   |
| RAID | 23        | 7.8%    |
| SAS  | 5         | 1.69%   |
| SCSI | 3         | 1.02%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 138       | 65.71%  |
| AMD      | 69        | 32.86%  |
| ARM      | 2         | 0.95%   |
| Loongson | 1         | 0.48%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 5         | 2.37%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 4         | 1.9%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.42%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 1.42%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.42%   |
| Intel 12th Gen Core i7-12700H                 | 3         | 1.42%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 3         | 1.42%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 3         | 1.42%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 3         | 1.42%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz            | 2         | 0.95%   |
| Intel Pentium CPU G4560 @ 3.50GHz             | 2         | 0.95%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 0.95%   |
| Intel Core i7-5820K CPU @ 3.30GHz             | 2         | 0.95%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 2         | 0.95%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 0.95%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 0.95%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 0.95%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 2         | 0.95%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 2         | 0.95%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 0.95%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 2         | 0.95%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 2         | 0.95%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 0.95%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 0.95%   |
| ARM Processor                                 | 2         | 0.95%   |
| AMD Ryzen 9 7900 12-Core Processor            | 2         | 0.95%   |
| AMD Ryzen 7 7730U with Radeon Graphics        | 2         | 0.95%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 2         | 0.95%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 2         | 0.95%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 2         | 0.95%   |
| AMD FX-8350 Eight-Core Processor              | 2         | 0.95%   |
| AMD Athlon II X2 250 Processor                | 2         | 0.95%   |
| Loongson Loongson 3A                          | 1         | 0.47%   |
| Intel Xeon CPU X5680 @ 3.33GHz                | 1         | 0.47%   |
| Intel Xeon CPU X5355 @ 2.66GHz                | 1         | 0.47%   |
| Intel Xeon CPU X3450 @ 2.67GHz                | 1         | 0.47%   |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz           | 1         | 0.47%   |
| Intel Xeon CPU E5-2695 v2 @ 2.40GHz           | 1         | 0.47%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz           | 1         | 0.47%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz           | 1         | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 37        | 17.54%  |
| Intel Core i7        | 30        | 14.22%  |
| Other                | 21        | 9.95%   |
| AMD Ryzen 5          | 21        | 9.95%   |
| Intel Xeon           | 15        | 7.11%   |
| AMD Ryzen 7          | 13        | 6.16%   |
| AMD Ryzen 9          | 10        | 4.74%   |
| Intel Pentium        | 8         | 3.79%   |
| Intel Core i3        | 8         | 3.79%   |
| Intel Core 2 Duo     | 6         | 2.84%   |
| AMD FX               | 6         | 2.84%   |
| Intel Celeron        | 4         | 1.9%    |
| Intel Atom           | 3         | 1.42%   |
| AMD Ryzen 3          | 3         | 1.42%   |
| Intel Core i9        | 2         | 0.95%   |
| Intel Core 2 Quad    | 2         | 0.95%   |
| Intel Core 2         | 2         | 0.95%   |
| AMD Ryzen 7 PRO      | 2         | 0.95%   |
| AMD Athlon II X2     | 2         | 0.95%   |
| Intel Pentium Silver | 1         | 0.47%   |
| Intel Pentium Gold   | 1         | 0.47%   |
| Intel Pentium Dual   | 1         | 0.47%   |
| Intel Core M         | 1         | 0.47%   |
| Intel Core           | 1         | 0.47%   |
| AMD Ryzen Embedded   | 1         | 0.47%   |
| AMD Ryzen 3 PRO      | 1         | 0.47%   |
| AMD GX               | 1         | 0.47%   |
| AMD G                | 1         | 0.47%   |
| AMD EPYC             | 1         | 0.47%   |
| AMD E1               | 1         | 0.47%   |
| AMD Athlon 64 X2     | 1         | 0.47%   |
| AMD Athlon           | 1         | 0.47%   |
| AMD A8               | 1         | 0.47%   |
| AMD A4               | 1         | 0.47%   |
| AMD A10              | 1         | 0.47%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 69        | 32.7%   |
| 2      | 61        | 28.91%  |
| 8      | 27        | 12.8%   |
| 6      | 25        | 11.85%  |
| 12     | 8         | 3.79%   |
| 16     | 7         | 3.32%   |
| 14     | 5         | 2.37%   |
| 10     | 4         | 1.9%    |
| 1      | 3         | 1.42%   |
| 24     | 1         | 0.47%   |
| 3      | 1         | 0.47%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 201       | 95.71%  |
| 2      | 9         | 4.29%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 157       | 74.76%  |
| 1      | 53        | 25.24%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 206       | 98.1%   |
| Unknown        | 2         | 0.95%   |
| 64-bit         | 1         | 0.48%   |
| 32-bit         | 1         | 0.48%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 71        | 33.18%  |
| 0x306a9    | 10        | 4.67%   |
| 0x306c3    | 7         | 3.27%   |
| 0x08701021 | 7         | 3.27%   |
| 0x206d7    | 5         | 2.34%   |
| 0x206a7    | 5         | 2.34%   |
| 0x20655    | 5         | 2.34%   |
| 0x08108109 | 5         | 2.34%   |
| 0x906a3    | 4         | 1.87%   |
| 0x806ea    | 4         | 1.87%   |
| 0x806d1    | 4         | 1.87%   |
| 0x406e3    | 4         | 1.87%   |
| 0x306d4    | 4         | 1.87%   |
| 0x1067a    | 4         | 1.87%   |
| 0x906ed    | 3         | 1.4%    |
| 0x906ea    | 3         | 1.4%    |
| 0x806ec    | 3         | 1.4%    |
| 0x806c1    | 3         | 1.4%    |
| 0x406c4    | 3         | 1.4%    |
| 0x306f2    | 3         | 1.4%    |
| 0x08701013 | 3         | 1.4%    |
| 0x0810100b | 3         | 1.4%    |
| 0x6fd      | 2         | 0.93%   |
| 0x506e3    | 2         | 0.93%   |
| 0x106c2    | 2         | 0.93%   |
| 0x0a50000c | 2         | 0.93%   |
| 0x0a201016 | 2         | 0.93%   |
| 0x08600106 | 2         | 0.93%   |
| 0x06001119 | 2         | 0.93%   |
| 0x06000822 | 2         | 0.93%   |
| 0xa0671    | 1         | 0.47%   |
| 0xa0660    | 1         | 0.47%   |
| 0xa0653    | 1         | 0.47%   |
| 0xa0652    | 1         | 0.47%   |
| 0x906e9    | 1         | 0.47%   |
| 0x906c0    | 1         | 0.47%   |
| 0x906a4    | 1         | 0.47%   |
| 0x806e9    | 1         | 0.47%   |
| 0x706a1    | 1         | 0.47%   |
| 0x6fb      | 1         | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 28        | 13.27%  |
| Zen 2            | 17        | 8.06%   |
| Haswell          | 17        | 8.06%   |
| Unknown          | 14        | 6.64%   |
| SandyBridge      | 13        | 6.16%   |
| IvyBridge        | 13        | 6.16%   |
| Zen 3            | 11        | 5.21%   |
| Zen+             | 10        | 4.74%   |
| Skylake          | 9         | 4.27%   |
| Core             | 9         | 4.27%   |
| Zen              | 8         | 3.79%   |
| Westmere         | 8         | 3.79%   |
| Alderlake Hybrid | 7         | 3.32%   |
| Piledriver       | 6         | 2.84%   |
| Silvermont       | 5         | 2.37%   |
| Penryn           | 5         | 2.37%   |
| Icelake          | 5         | 2.37%   |
| CometLake        | 5         | 2.37%   |
| Broadwell        | 4         | 1.9%    |
| TigerLake        | 3         | 1.42%   |
| K10              | 2         | 0.95%   |
| Jaguar           | 2         | 0.95%   |
| Bulldozer        | 2         | 0.95%   |
| Bonnell          | 2         | 0.95%   |
| Tremont          | 1         | 0.47%   |
| Puma             | 1         | 0.47%   |
| Nehalem          | 1         | 0.47%   |
| K8 Hammer        | 1         | 0.47%   |
| Goldmont plus    | 1         | 0.47%   |
| Bobcat           | 1         | 0.47%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 94        | 40.69%  |
| AMD                        | 68        | 29.44%  |
| Nvidia                     | 62        | 26.84%  |
| Matrox Electronics Systems | 6         | 2.6%    |
| Loongson Technology        | 1         | 0.43%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 9         | 3.75%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 7         | 2.92%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 6         | 2.5%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 2.5%    |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 5         | 2.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 2.08%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 2.08%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5         | 2.08%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 4         | 1.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 1.67%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.67%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 4         | 1.67%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 3         | 1.25%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 3         | 1.25%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.25%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 1.25%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 3         | 1.25%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3         | 1.25%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 3         | 1.25%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.25%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 3         | 1.25%   |
| AMD Raphael                                                                              | 3         | 1.25%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 3         | 1.25%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 1.25%   |
| AMD Barcelo                                                                              | 3         | 1.25%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.83%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.83%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.83%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 0.83%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2         | 0.83%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2         | 0.83%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.83%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2         | 0.83%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 0.83%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 2         | 0.83%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 2         | 0.83%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.83%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.83%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.83%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 75        | 35.71%  |
| 1 x AMD                 | 57        | 27.14%  |
| 1 x Nvidia              | 40        | 19.05%  |
| Intel + Nvidia          | 15        | 7.14%   |
| 1 x Matrox              | 6         | 2.86%   |
| AMD + Nvidia            | 5         | 2.38%   |
| Other                   | 4         | 1.9%    |
| 2 x AMD                 | 4         | 1.9%    |
| Intel + AMD             | 2         | 0.95%   |
| 2 x Nvidia              | 1         | 0.48%   |
| 1 x Loongson Technology | 1         | 0.48%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 164       | 77.73%  |
| Proprietary | 29        | 13.74%  |
| Unknown     | 18        | 8.53%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 113       | 53.05%  |
| 1.01-2.0   | 21        | 9.86%   |
| 0.51-1.0   | 21        | 9.86%   |
| 0.01-0.5   | 18        | 8.45%   |
| 3.01-4.0   | 15        | 7.04%   |
| 7.01-8.0   | 12        | 5.63%   |
| 8.01-16.0  | 6         | 2.82%   |
| 5.01-6.0   | 5         | 2.35%   |
| 2.01-3.0   | 1         | 0.47%   |
| 16.01-24.0 | 1         | 0.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 24        | 11.16%  |
| BOE                  | 22        | 10.23%  |
| Dell                 | 19        | 8.84%   |
| Chimei Innolux       | 17        | 7.91%   |
| AU Optronics         | 17        | 7.91%   |
| LG Display           | 15        | 6.98%   |
| Hewlett-Packard      | 14        | 6.51%   |
| Goldstar             | 11        | 5.12%   |
| BenQ                 | 11        | 5.12%   |
| Lenovo               | 6         | 2.79%   |
| Sharp                | 5         | 2.33%   |
| Ancor Communications | 5         | 2.33%   |
| Acer                 | 5         | 2.33%   |
| ViewSonic            | 3         | 1.4%    |
| ASUSTek Computer     | 3         | 1.4%    |
| AOC                  | 3         | 1.4%    |
| Toshiba              | 2         | 0.93%   |
| Iiyama               | 2         | 0.93%   |
| Apple                | 2         | 0.93%   |
| Xiaomi               | 1         | 0.47%   |
| Wacom                | 1         | 0.47%   |
| Valve                | 1         | 0.47%   |
| Unknown              | 1         | 0.47%   |
| UGD                  | 1         | 0.47%   |
| TopView              | 1         | 0.47%   |
| SZS                  | 1         | 0.47%   |
| Sony                 | 1         | 0.47%   |
| RTK                  | 1         | 0.47%   |
| Philips              | 1         | 0.47%   |
| PANDA                | 1         | 0.47%   |
| Panasonic            | 1         | 0.47%   |
| ONN                  | 1         | 0.47%   |
| NEC Computers        | 1         | 0.47%   |
| MSI                  | 1         | 0.47%   |
| JVC                  | 1         | 0.47%   |
| IOD                  | 1         | 0.47%   |
| InnoLux Display      | 1         | 0.47%   |
| IBM                  | 1         | 0.47%   |
| Hyundai ImageQuest   | 1         | 0.47%   |
| HKC                  | 1         | 0.47%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 3         | 1.36%   |
| Samsung Electronics LCD Monitor SDC416E 2880x1620 344x194mm 15.5-inch | 2         | 0.9%    |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 2         | 0.9%    |
| LG Display LCD Monitor LGD0353 1366x768 345x194mm 15.6-inch           | 2         | 0.9%    |
| Lenovo LCD Monitor LEN4035 1280x800 304x190mm 14.1-inch               | 2         | 0.9%    |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch             | 2         | 0.9%    |
| Goldstar ULTRAGEAR GSM7765 2560x1440 697x392mm 31.5-inch              | 2         | 0.9%    |
| Goldstar HDR WQHD GSM7756 3440x1440 820x346mm 35.0-inch               | 2         | 0.9%    |
| Dell G2724D DELD175 2560x1440 596x335mm 26.9-inch                     | 2         | 0.9%    |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 2         | 0.9%    |
| BenQ GW2283 BNQ78E9 1920x1080 476x268mm 21.5-inch                     | 2         | 0.9%    |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 2         | 0.9%    |
| Xiaomi Mi TV XMD009A 2880x1800 480x270mm 21.7-inch                    | 1         | 0.45%   |
| Wacom Cintiq 22HDT WAC1037 1920x1080 476x268mm 21.5-inch              | 1         | 0.45%   |
| ViewSonic VX3276-FHD VSCE735 1920x1080 698x393mm 31.5-inch            | 1         | 0.45%   |
| ViewSonic LCD Monitor VX2276 Series 1920x1080                         | 1         | 0.45%   |
| ViewSonic LCD Monitor VA2448 SERIES 1920x1080                         | 1         | 0.45%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 0.45%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1         | 0.45%   |
| UGD Artist13.3pro UGD1302 1920x1080 290x160mm 13.0-inch               | 1         | 0.45%   |
| Toshiba TV TSB0206 1920x1080                                          | 1         | 0.45%   |
| Toshiba TV TSB0108 1920x1080 698x393mm 31.5-inch                      | 1         | 0.45%   |
| TopView HDMI TOP0814 1600x900 430x270mm 20.0-inch                     | 1         | 0.45%   |
| SZS MR124A SZS1240 1920x1080 527x296mm 23.8-inch                      | 1         | 0.45%   |
| Sony TV SNY8102 1360x768                                              | 1         | 0.45%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 382x215mm 17.3-inch               | 1         | 0.45%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 0.45%   |
| Sharp LQ125T1JW02 SHP142F 2560x1440 277x155mm 12.5-inch               | 1         | 0.45%   |
| Sharp LCD Monitor SHP14C4 1920x1080 344x194mm 15.5-inch               | 1         | 0.45%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 1         | 0.45%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch     | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM0578 1920x1080 476x268mm 21.5-inch  | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch   | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM0428 1680x1050 459x296mm 21.5-inch  | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM03F2 1680x1050                      | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM03F0 1680x1050 433x271mm 20.1-inch  | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 376x301mm 19.0-inch  | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM01AD 1600x1200 408x306mm 20.1-inch  | 1         | 0.45%   |
| Samsung Electronics SMS27A650 SAM082D 1920x1080 598x336mm 27.0-inch   | 1         | 0.45%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch    | 1         | 0.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 97        | 46.63%  |
| 1366x768 (WXGA)    | 30        | 14.42%  |
| 3840x2160 (4K)     | 11        | 5.29%   |
| 2560x1440 (QHD)    | 11        | 5.29%   |
| 1920x1200 (WUXGA)  | 9         | 4.33%   |
| 1680x1050 (WSXGA+) | 9         | 4.33%   |
| 1280x1024 (SXGA)   | 9         | 4.33%   |
| 1600x900 (HD+)     | 5         | 2.4%    |
| 1280x800 (WXGA)    | 5         | 2.4%    |
| 3440x1440          | 4         | 1.92%   |
| 1920x540           | 3         | 1.44%   |
| 2880x1620          | 2         | 0.96%   |
| 1440x900 (WXGA+)   | 2         | 0.96%   |
| 1360x768           | 2         | 0.96%   |
| 800x1280           | 1         | 0.48%   |
| 3200x1080          | 1         | 0.48%   |
| 2288x1287          | 1         | 0.48%   |
| 2256x1504          | 1         | 0.48%   |
| 2160x1440          | 1         | 0.48%   |
| 1920x1280          | 1         | 0.48%   |
| 1600x1200          | 1         | 0.48%   |
| 1024x768 (XGA)     | 1         | 0.48%   |
| Unknown            | 1         | 0.48%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 46        | 21.2%   |
| 21      | 20        | 9.22%   |
| 27      | 19        | 8.76%   |
| 24      | 19        | 8.76%   |
| 14      | 16        | 7.37%   |
| 13      | 15        | 6.91%   |
| 23      | 11        | 5.07%   |
| 17      | 11        | 5.07%   |
| Unknown | 7         | 3.23%   |
| 31      | 6         | 2.76%   |
| 12      | 6         | 2.76%   |
| 22      | 5         | 2.3%    |
| 20      | 5         | 2.3%    |
| 18      | 5         | 2.3%    |
| 16      | 5         | 2.3%    |
| 19      | 4         | 1.84%   |
| 72      | 2         | 0.92%   |
| 35      | 2         | 0.92%   |
| 34      | 2         | 0.92%   |
| 142     | 1         | 0.46%   |
| 84      | 1         | 0.46%   |
| 74      | 1         | 0.46%   |
| 52      | 1         | 0.46%   |
| 48      | 1         | 0.46%   |
| 46      | 1         | 0.46%   |
| 43      | 1         | 0.46%   |
| 32      | 1         | 0.46%   |
| 11      | 1         | 0.46%   |
| 10      | 1         | 0.46%   |
| 7       | 1         | 0.46%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 78        | 36.28%  |
| 501-600        | 45        | 20.93%  |
| 401-500        | 37        | 17.21%  |
| 351-400        | 13        | 6.05%   |
| 201-300        | 13        | 6.05%   |
| 601-700        | 7         | 3.26%   |
| Unknown        | 7         | 3.26%   |
| 1501-2000      | 4         | 1.86%   |
| 701-800        | 3         | 1.4%    |
| 1001-1500      | 3         | 1.4%    |
| 801-900        | 2         | 0.93%   |
| More than 2000 | 1         | 0.47%   |
| 901-1000       | 1         | 0.47%   |
| 1-100          | 1         | 0.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 139       | 71.28%  |
| 16/10   | 26        | 13.33%  |
| 5/4     | 6         | 3.08%   |
| 3/2     | 6         | 3.08%   |
| Unknown | 5         | 2.56%   |
| 21/9    | 4         | 2.05%   |
| 4/3     | 3         | 1.54%   |
| 6/5     | 2         | 1.03%   |
| 32/9    | 1         | 0.51%   |
| 1.96    | 1         | 0.51%   |
| 1.00    | 1         | 0.51%   |
| 0.67    | 1         | 0.51%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 47        | 21.96%  |
| 201-250        | 42        | 19.63%  |
| 81-90          | 27        | 12.62%  |
| 301-350        | 19        | 8.88%   |
| 151-200        | 13        | 6.07%   |
| 351-500        | 11        | 5.14%   |
| 141-150        | 9         | 4.21%   |
| 251-300        | 7         | 3.27%   |
| Unknown        | 7         | 3.27%   |
| More than 1000 | 6         | 2.8%    |
| 121-130        | 6         | 2.8%    |
| 71-80          | 5         | 2.34%   |
| 61-70          | 5         | 2.34%   |
| 111-120        | 4         | 1.87%   |
| 501-1000       | 3         | 1.4%    |
| 51-60          | 2         | 0.93%   |
| 1-40           | 1         | 0.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 73        | 34.76%  |
| 121-160       | 56        | 26.67%  |
| 101-120       | 55        | 26.19%  |
| 161-240       | 10        | 4.76%   |
| 1-50          | 7         | 3.33%   |
| Unknown       | 7         | 3.33%   |
| More than 240 | 2         | 0.95%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 163       | 77.62%  |
| 2     | 25        | 11.9%   |
| 0     | 18        | 8.57%   |
| 3     | 3         | 1.43%   |
| 4     | 1         | 0.48%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 112       | 36.36%  |
| Intel                           | 110       | 35.71%  |
| Qualcomm Atheros                | 18        | 5.84%   |
| Broadcom                        | 15        | 4.87%   |
| MediaTek                        | 11        | 3.57%   |
| Ralink Technology               | 7         | 2.27%   |
| ASIX Electronics                | 6         | 1.95%   |
| Broadcom Limited                | 5         | 1.62%   |
| TP-Link                         | 4         | 1.3%    |
| Nvidia                          | 4         | 1.3%    |
| Qualcomm                        | 2         | 0.65%   |
| Dell                            | 2         | 0.65%   |
| VIA Technologies                | 1         | 0.32%   |
| Sitecom Europe                  | 1         | 0.32%   |
| Sierra Wireless                 | 1         | 0.32%   |
| Shenzhen Goodix Technology      | 1         | 0.32%   |
| Ralink                          | 1         | 0.32%   |
| Qualcomm Atheros Communications | 1         | 0.32%   |
| Micro Star International        | 1         | 0.32%   |
| Mellanox Technologies           | 1         | 0.32%   |
| Marvell Technology Group        | 1         | 0.32%   |
| Huawei Technologies             | 1         | 0.32%   |
| Hewlett-Packard                 | 1         | 0.32%   |
| Chelsio Communications          | 1         | 0.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 75        | 20.27%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 13        | 3.51%   |
| Intel Wi-Fi 6 AX200                                                    | 10        | 2.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 10        | 2.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 8         | 2.16%   |
| Realtek RTL8125 2.5GbE Controller                                      | 8         | 2.16%   |
| Intel I211 Gigabit Network Connection                                  | 8         | 2.16%   |
| Intel Wireless 8265 / 8275                                             | 6         | 1.62%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 1.35%   |
| Ralink MT7601U Wireless Adapter                                        | 5         | 1.35%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 5         | 1.35%   |
| Intel Wireless 8260                                                    | 5         | 1.35%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 5         | 1.35%   |
| Intel 82574L Gigabit Network Connection                                | 5         | 1.35%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 4         | 1.08%   |
| Intel Wireless 7260                                                    | 4         | 1.08%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 4         | 1.08%   |
| Intel I350 Gigabit Network Connection                                  | 4         | 1.08%   |
| Intel Ethernet Controller I225-V                                       | 4         | 1.08%   |
| Intel Ethernet Connection (2) I218-V                                   | 4         | 1.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 4         | 1.08%   |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 1.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 3         | 0.81%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 3         | 0.81%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 3         | 0.81%   |
| Nvidia MCP61 Ethernet                                                  | 3         | 0.81%   |
| Intel Wireless 7265                                                    | 3         | 0.81%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 0.81%   |
| Intel Ethernet Connection (7) I219-V                                   | 3         | 0.81%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3         | 0.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 3         | 0.81%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 3         | 0.81%   |
| Intel Centrino Ultimate-N 6300                                         | 3         | 0.81%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 3         | 0.81%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 3         | 0.81%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 0.81%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 2         | 0.54%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 2         | 0.54%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 0.54%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 73        | 50.69%  |
| Realtek Semiconductor           | 22        | 15.28%  |
| Qualcomm Atheros                | 13        | 9.03%   |
| MediaTek                        | 9         | 6.25%   |
| Ralink Technology               | 7         | 4.86%   |
| Broadcom                        | 5         | 3.47%   |
| TP-Link                         | 4         | 2.78%   |
| Broadcom Limited                | 3         | 2.08%   |
| Dell                            | 2         | 1.39%   |
| Sitecom Europe                  | 1         | 0.69%   |
| Sierra Wireless                 | 1         | 0.69%   |
| Ralink                          | 1         | 0.69%   |
| Qualcomm Atheros Communications | 1         | 0.69%   |
| Qualcomm                        | 1         | 0.69%   |
| Micro Star International        | 1         | 0.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 10        | 6.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 8         | 5.52%   |
| Intel Wireless 8265 / 8275                                           | 6         | 4.14%   |
| Ralink MT7601U Wireless Adapter                                      | 5         | 3.45%   |
| Intel Wireless 8260                                                  | 5         | 3.45%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 5         | 3.45%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 4         | 2.76%   |
| Intel Wireless 7260                                                  | 4         | 2.76%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 4         | 2.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 4         | 2.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 3         | 2.07%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 3         | 2.07%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 3         | 2.07%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 3         | 2.07%   |
| Intel Wireless 7265                                                  | 3         | 2.07%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 3         | 2.07%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 3         | 2.07%   |
| Intel Centrino Ultimate-N 6300                                       | 3         | 2.07%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 3         | 2.07%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                              | 2         | 1.38%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                     | 2         | 1.38%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 2         | 1.38%   |
| Intel Wireless 3165                                                  | 2         | 1.38%   |
| Intel Wireless 3160                                                  | 2         | 1.38%   |
| Intel Wi-Fi 6 AX201                                                  | 2         | 1.38%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 2         | 1.38%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 2         | 1.38%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                              | 2         | 1.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 2         | 1.38%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 1         | 0.69%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                | 1         | 0.69%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 1         | 0.69%   |
| TP-Link 802.11ac NIC                                                 | 1         | 0.69%   |
| Sitecom Europe WL-113 rev 2 Wireless Network USB Adapter             | 1         | 0.69%   |
| Sierra Wireless EM7305                                               | 1         | 0.69%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 1         | 0.69%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 1         | 0.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 1         | 0.69%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 1         | 0.69%   |
| Realtek RTL8191SEvB Wireless LAN Controller                          | 1         | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 103       | 48.82%  |
| Intel                    | 68        | 32.23%  |
| Broadcom                 | 12        | 5.69%   |
| Qualcomm Atheros         | 8         | 3.79%   |
| ASIX Electronics         | 6         | 2.84%   |
| Nvidia                   | 4         | 1.9%    |
| MediaTek                 | 2         | 0.95%   |
| Broadcom Limited         | 2         | 0.95%   |
| VIA Technologies         | 1         | 0.47%   |
| Qualcomm                 | 1         | 0.47%   |
| Mellanox Technologies    | 1         | 0.47%   |
| Marvell Technology Group | 1         | 0.47%   |
| Huawei Technologies      | 1         | 0.47%   |
| Chelsio Communications   | 1         | 0.47%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 75        | 33.63%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 13        | 5.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 10        | 4.48%   |
| Realtek RTL8125 2.5GbE Controller                                      | 8         | 3.59%   |
| Intel I211 Gigabit Network Connection                                  | 8         | 3.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 2.24%   |
| Intel 82574L Gigabit Network Connection                                | 5         | 2.24%   |
| Intel I350 Gigabit Network Connection                                  | 4         | 1.79%   |
| Intel Ethernet Controller I225-V                                       | 4         | 1.79%   |
| Intel Ethernet Connection (2) I218-V                                   | 4         | 1.79%   |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 1.79%   |
| Nvidia MCP61 Ethernet                                                  | 3         | 1.35%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 1.35%   |
| Intel Ethernet Connection (7) I219-V                                   | 3         | 1.35%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3         | 1.35%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 1.35%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 2         | 0.9%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 0.9%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2         | 0.9%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 2         | 0.9%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 2         | 0.9%    |
| Intel Ethernet Connection I217-V                                       | 2         | 0.9%    |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 0.9%    |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 0.9%    |
| Intel Ethernet Connection (2) I219-V                                   | 2         | 0.9%    |
| Intel 82579V Gigabit Network Connection                                | 2         | 0.9%    |
| Intel 82567LM-3 Gigabit Network Connection                             | 2         | 0.9%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 2         | 0.9%    |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 2         | 0.9%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 2         | 0.9%    |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                        | 2         | 0.9%    |
| VIA VT6105/VT6106S [Rhine-III]                                         | 1         | 0.45%   |
| Realtek USB 10/100/1G/2.5 LAN                                          | 1         | 0.45%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller            | 1         | 0.45%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.45%   |
| Qualcomm Nokia X30 5G                                                  | 1         | 0.45%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.45%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.45%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                  | 1         | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 194       | 57.74%  |
| WiFi     | 140       | 41.67%  |
| Modem    | 2         | 0.6%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 118       | 56.19%  |
| WiFi     | 92        | 43.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 107       | 50.47%  |
| 1     | 79        | 37.26%  |
| 3     | 9         | 4.25%   |
| 0     | 9         | 4.25%   |
| 4     | 5         | 2.36%   |
| 5     | 2         | 0.94%   |
| 6     | 1         | 0.47%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 180       | 84.51%  |
| Yes  | 33        | 15.49%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 63        | 48.09%  |
| Cambridge Silicon Radio         | 15        | 11.45%  |
| Realtek Semiconductor           | 13        | 9.92%   |
| Broadcom                        | 11        | 8.4%    |
| MediaTek                        | 6         | 4.58%   |
| IMC Networks                    | 6         | 4.58%   |
| Qualcomm Atheros Communications | 5         | 3.82%   |
| Foxconn / Hon Hai               | 3         | 2.29%   |
| Apple                           | 3         | 2.29%   |
| Micro Star International        | 2         | 1.53%   |
| USI                             | 1         | 0.76%   |
| TP-Link                         | 1         | 0.76%   |
| Toshiba                         | 1         | 0.76%   |
| ASUSTek Computer                | 1         | 0.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                   | 23        | 17.56%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)  | 15        | 11.45%  |
| Intel AX201 Bluetooth                                | 9         | 6.87%   |
| Intel AX200 Bluetooth                                | 9         | 6.87%   |
| Realtek  Bluetooth 4.2 Adapter                       | 6         | 4.58%   |
| Realtek Bluetooth Radio                              | 6         | 4.58%   |
| MediaTek Wireless_Device                             | 6         | 4.58%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)       | 6         | 4.58%   |
| Intel AX210 Bluetooth                                | 5         | 3.82%   |
| IMC Networks Wireless_Device                         | 5         | 3.82%   |
| Intel Wireless-AC 9260 Bluetooth Adapter             | 4         | 3.05%   |
| Qualcomm Atheros  Bluetooth Device                   | 3         | 2.29%   |
| Intel Wireless-AC 3168 Bluetooth                     | 3         | 2.29%   |
| Intel Bluetooth Device                               | 3         | 2.29%   |
| Broadcom BCM20702A0 Bluetooth 4.0                    | 3         | 2.29%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]           | 2         | 1.53%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]     | 2         | 1.53%   |
| USI Bluetooth Device                                 | 1         | 0.76%   |
| TP-Link TP-T@- UB500 Adapter                         | 1         | 0.76%   |
| Toshiba Askey Bluetooth Module                       | 1         | 0.76%   |
| Realtek RTL8723B Bluetooth                           | 1         | 0.76%   |
| Qualcomm Atheros Dell Wireless 1802 Bluetooth 4.0 LE | 1         | 0.76%   |
| Qualcomm Atheros AR3011 Bluetooth                    | 1         | 0.76%   |
| Micro Star International Bluetooth Dongle            | 1         | 0.76%   |
| Micro Star International Bluetooth Device            | 1         | 0.76%   |
| Intel Centrino Bluetooth Wireless Transceiver        | 1         | 0.76%   |
| IMC Networks Bluetooth Radio                         | 1         | 0.76%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter         | 1         | 0.76%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller      | 1         | 0.76%   |
| Foxconn / Hon Hai Bluetooth Device                   | 1         | 0.76%   |
| Broadcom HP Portable Valentine                       | 1         | 0.76%   |
| Broadcom HP Portable SoftSailing                     | 1         | 0.76%   |
| Broadcom BCM20702A0                                  | 1         | 0.76%   |
| Broadcom BCM2045B (BDC-2.1)                          | 1         | 0.76%   |
| ASUS ASUS USB-BT500                                  | 1         | 0.76%   |
| Apple Bluetooth USB Host Controller                  | 1         | 0.76%   |
| Apple Bluetooth Host Controller                      | 1         | 0.76%   |
| Apple Bluetooth HCI MacBookPro (HID mode)            | 1         | 0.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 126       | 43.75%  |
| AMD                      | 74        | 25.69%  |
| Nvidia                   | 52        | 18.06%  |
| Creative Labs            | 9         | 3.13%   |
| C-Media Electronics      | 5         | 1.74%   |
| Texas Instruments        | 3         | 1.04%   |
| Micro Star International | 3         | 1.04%   |
| Kingston Technology      | 2         | 0.69%   |
| ASUSTek Computer         | 2         | 0.69%   |
| VIA Technologies         | 1         | 0.35%   |
| RME                      | 1         | 0.35%   |
| M-Audio                  | 1         | 0.35%   |
| Loongson Technology      | 1         | 0.35%   |
| Jieli Technology         | 1         | 0.35%   |
| Holtek Semiconductor     | 1         | 0.35%   |
| Generalplus Technology   | 1         | 0.35%   |
| EGO SYStems              | 1         | 0.35%   |
| DSEA A/S                 | 1         | 0.35%   |
| Creative Technology      | 1         | 0.35%   |
| Corsair                  | 1         | 0.35%   |
| AlfaPlus Semiconductor   | 1         | 0.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                                                     | 29        | 8.06%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 18        | 5%      |
| Intel Sunrise Point-LP HD Audio                                                                   | 16        | 4.44%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 14        | 3.89%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10        | 2.78%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 10        | 2.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8         | 2.22%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 2.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 1.94%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 7         | 1.94%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 1.67%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 1.67%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 6         | 1.67%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 6         | 1.67%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 1.67%   |
| AMD Radeon High Definition Audio Controller                                                       | 6         | 1.67%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 5         | 1.39%   |
| Nvidia GA107 High Definition Audio Controller                                                     | 5         | 1.39%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 1.39%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.39%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 5         | 1.39%   |
| AMD FCH Azalia Controller                                                                         | 5         | 1.39%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 5         | 1.39%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.11%   |
| Nvidia MCP61 High Definition Audio                                                                | 4         | 1.11%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 1.11%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.11%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 1.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.11%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 4         | 1.11%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.11%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus]   | 4         | 1.11%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 1.11%   |
| AMD Navi 31 HDMI/DP Audio                                                                         | 4         | 1.11%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 4         | 1.11%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 4         | 1.11%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 0.83%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.83%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.83%   |
| Micro Star International USB Audio                                                                | 3         | 0.83%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 38        | 17.67%  |
| Samsung Electronics | 35        | 16.28%  |
| Kingston            | 32        | 14.88%  |
| Corsair             | 20        | 9.3%    |
| Micron Technology   | 16        | 7.44%   |
| Crucial             | 16        | 7.44%   |
| Unknown             | 14        | 6.51%   |
| G.Skill             | 7         | 3.26%   |
| Team                | 4         | 1.86%   |
| A-DATA Technology   | 4         | 1.86%   |
| Unknown             | 3         | 1.4%    |
| Transcend           | 2         | 0.93%   |
| Smart               | 2         | 0.93%   |
| Silicon Power       | 2         | 0.93%   |
| Ramaxel Technology  | 2         | 0.93%   |
| GOODRAM             | 2         | 0.93%   |
| Elpida              | 2         | 0.93%   |
| AMD                 | 2         | 0.93%   |
| Strontium           | 1         | 0.47%   |
| Patriot             | 1         | 0.47%   |
| Neo Forza           | 1         | 0.47%   |
| Nanya Technology    | 1         | 0.47%   |
| Innodisk            | 1         | 0.47%   |
| HPE                 | 1         | 0.47%   |
| Hewlett-Packard     | 1         | 0.47%   |
| GLOWAY              | 1         | 0.47%   |
| Essencore Limited   | 1         | 0.47%   |
| CXMT                | 1         | 0.47%   |
| Avant               | 1         | 0.47%   |
| A Force             | 1         | 0.47%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s            | 4         | 1.69%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.27%   |
| Unknown                                                          | 3         | 1.27%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 2         | 0.85%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 2         | 0.85%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s               | 2         | 0.85%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.85%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 0.85%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 0.85%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 2         | 0.85%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.85%   |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s           | 2         | 0.85%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 2         | 0.85%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 2133MT/s              | 2         | 0.85%   |
| Kingston RAM KF2666C15S4/16G 16GB SODIMM DDR4 2667MT/s           | 2         | 0.85%   |
| Corsair RAM CMZ32GX3M4X1600C10 8GB DIMM DDR3 1600MT/s            | 2         | 0.85%   |
| Corsair RAM CMSX32GX4M2A2666C18 16GB SODIMM DDR4 2667MT/s        | 2         | 0.85%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3800MT/s           | 2         | 0.85%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 2         | 0.85%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                        | 1         | 0.42%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                         | 1         | 0.42%   |
| Unknown RAM Module 4096MB DIMM DDR3 65535MT/s                    | 1         | 0.42%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.42%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.42%   |
| Unknown RAM Module 2GB DIMM DDR2 533MT/s                         | 1         | 0.42%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                         | 1         | 0.42%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                       | 1         | 0.42%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                           | 1         | 0.42%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                           | 1         | 0.42%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                    | 1         | 0.42%   |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s                       | 1         | 0.42%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                           | 1         | 0.42%   |
| Transcend RAM TS256MLQ72V6U 2GB DIMM DDR2 667MT/s                | 1         | 0.42%   |
| Transcend RAM JM1600KLN-8GK 4096MB DIMM DDR3 1600MT/s            | 1         | 0.42%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 4000MT/s              | 1         | 0.42%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s              | 1         | 0.42%   |
| Strontium RAM SRT4G86U1-P9H 4GB DIMM DDR3 1333MT/s               | 1         | 0.42%   |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s            | 1         | 0.42%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s              | 1         | 0.42%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s          | 1         | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 89        | 47.85%  |
| DDR3    | 62        | 33.33%  |
| DDR2    | 8         | 4.3%    |
| DDR5    | 6         | 3.23%   |
| LPDDR3  | 5         | 2.69%   |
| SDRAM   | 4         | 2.15%   |
| LPDDR5  | 4         | 2.15%   |
| LPDDR4  | 4         | 2.15%   |
| DDR     | 2         | 1.08%   |
| Unknown | 2         | 1.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 91        | 48.66%  |
| SODIMM       | 84        | 44.92%  |
| Row Of Chips | 9         | 4.81%   |
| RIMM         | 1         | 0.53%   |
| FB-DIMM      | 1         | 0.53%   |
| Chip         | 1         | 0.53%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 85        | 41.06%  |
| 4096  | 50        | 24.15%  |
| 16384 | 39        | 18.84%  |
| 2048  | 16        | 7.73%   |
| 32768 | 11        | 5.31%   |
| 1024  | 6         | 2.9%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 41        | 19.9%   |
| 3200    | 34        | 16.5%   |
| 2667    | 19        | 9.22%   |
| 2400    | 14        | 6.8%    |
| 2133    | 12        | 5.83%   |
| 1333    | 12        | 5.83%   |
| 3600    | 11        | 5.34%   |
| 3800    | 5         | 2.43%   |
| 667     | 5         | 2.43%   |
| 4800    | 4         | 1.94%   |
| Unknown | 4         | 1.94%   |
| 2800    | 3         | 1.46%   |
| 2666    | 3         | 1.46%   |
| 1867    | 3         | 1.46%   |
| 1866    | 3         | 1.46%   |
| 533     | 3         | 1.46%   |
| 6400    | 2         | 0.97%   |
| 4267    | 2         | 0.97%   |
| 4000    | 2         | 0.97%   |
| 3000    | 2         | 0.97%   |
| 2000    | 2         | 0.97%   |
| 1334    | 2         | 0.97%   |
| 975     | 2         | 0.97%   |
| 800     | 2         | 0.97%   |
| 65535   | 1         | 0.49%   |
| 8600    | 1         | 0.49%   |
| 6000    | 1         | 0.49%   |
| 5600    | 1         | 0.49%   |
| 4266    | 1         | 0.49%   |
| 4199    | 1         | 0.49%   |
| 3733    | 1         | 0.49%   |
| 3666    | 1         | 0.49%   |
| 3400    | 1         | 0.49%   |
| 2933    | 1         | 0.49%   |
| 2733    | 1         | 0.49%   |
| 2200    | 1         | 0.49%   |
| 1066    | 1         | 0.49%   |
| 701     | 1         | 0.49%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 33.33%  |
| Brother Industries  | 3         | 25%     |
| QinHeng Electronics | 2         | 16.67%  |
| Prolific Technology | 1         | 8.33%   |
| Dell                | 1         | 8.33%   |
| Canon               | 1         | 8.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| QinHeng CH340S                | 2         | 16.67%  |
| Prolific PL2305 Parallel Port | 1         | 8.33%   |
| HP OfficeJet Pro 9010 series  | 1         | 8.33%   |
| HP LaserJet P1006             | 1         | 8.33%   |
| HP ENVY 4520 series           | 1         | 8.33%   |
| HP ENVY 4500 series           | 1         | 8.33%   |
| Dell 2330d Laser Printer      | 1         | 8.33%   |
| Canon LiDE 300                | 1         | 8.33%   |
| Brother Printer               | 1         | 8.33%   |
| Brother HL-L5102DW            | 1         | 8.33%   |
| Brother HL-L2320D series      | 1         | 8.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 2         | 50%     |
| Seiko Epson     | 1         | 25%     |
| Hewlett-Packard | 1         | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 25        | 23.58%  |
| Logitech                               | 13        | 12.26%  |
| Bison Electronics                      | 13        | 12.26%  |
| Realtek Semiconductor                  | 8         | 7.55%   |
| Microdia                               | 6         | 5.66%   |
| Sunplus Innovation Technology          | 5         | 4.72%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 4.72%   |
| Quanta                                 | 4         | 3.77%   |
| Luxvisions Innotech Limited            | 4         | 3.77%   |
| Lite-On Technology                     | 4         | 3.77%   |
| IMC Networks                           | 4         | 3.77%   |
| Syntek                                 | 3         | 2.83%   |
| Sonix Technology                       | 3         | 2.83%   |
| Samsung Electronics                    | 2         | 1.89%   |
| Apple                                  | 2         | 1.89%   |
| Z-Star Microelectronics                | 1         | 0.94%   |
| Silicon Motion                         | 1         | 0.94%   |
| Motorola PCS                           | 1         | 0.94%   |
| Microsoft                              | 1         | 0.94%   |
| Lenovo                                 | 1         | 0.94%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 5         | 4.72%   |
| Bison HD Webcam                                      | 4         | 3.77%   |
| Bison BisonCam,NB Pro                                | 4         | 3.77%   |
| Logitech Webcam C270                                 | 3         | 2.83%   |
| Bison Integrated Camera                              | 3         | 2.83%   |
| Syntek Integrated Camera                             | 2         | 1.89%   |
| Sunplus Integrated_Webcam_HD                         | 2         | 1.89%   |
| Sonix USB2.0 FHD UVC WebCam                          | 2         | 1.89%   |
| Samsung Galaxy series, misc. (MTP mode)              | 2         | 1.89%   |
| Microdia Integrated_Webcam_HD                        | 2         | 1.89%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 2         | 1.89%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 2         | 1.89%   |
| Lite-On Integrated Camera                            | 2         | 1.89%   |
| Chicony Integrated Camera (1280x720@30)              | 2         | 1.89%   |
| Chicony HP TrueVision HD Camera                      | 2         | 1.89%   |
| Chicony HD User Facing                               | 2         | 1.89%   |
| Chicony FJ Camera                                    | 2         | 1.89%   |
| Z-Star Vimicro USB2.0 Camera                         | 1         | 0.94%   |
| Syntek USB2.0 Camera                                 | 1         | 0.94%   |
| Sunplus Laptop_Integrated_Webcam_FHD                 | 1         | 0.94%   |
| Sunplus Integrated Camera                            | 1         | 0.94%   |
| Sunplus Full HD webcam                               | 1         | 0.94%   |
| Sonix USB2.0 HD UVC WebCam                           | 1         | 0.94%   |
| Silicon Motion Web Camera                            | 1         | 0.94%   |
| Realtek USB Camera                                   | 1         | 0.94%   |
| Realtek Laptop Camera                                | 1         | 0.94%   |
| Realtek Integrated_Webcam_HD                         | 1         | 0.94%   |
| Realtek Integrated Webcam                            | 1         | 0.94%   |
| Realtek Integrated Camera                            | 1         | 0.94%   |
| Realtek HP Webcam-101                                | 1         | 0.94%   |
| Realtek EasyCamera                                   | 1         | 0.94%   |
| Realtek Bluetooth Radio                              | 1         | 0.94%   |
| Quanta HP Wide Vision HD Camera                      | 1         | 0.94%   |
| Quanta HP Webcam                                     | 1         | 0.94%   |
| Quanta HP Integrated Webcam                          | 1         | 0.94%   |
| Quanta ACER HD User Facing                           | 1         | 0.94%   |
| Motorola PCS XT1033 [Moto G], PTP mode               | 1         | 0.94%   |
| Microsoft LifeCam HD-3000                            | 1         | 0.94%   |
| Microdia Laptop_Integrated_Webcam_2M                 | 1         | 0.94%   |
| Microdia Integrated Webcam                           | 1         | 0.94%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 10        | 40%     |
| Synaptics                          | 4         | 16%     |
| STMicroelectronics                 | 3         | 12%     |
| Shenzhen Goodix Technology         | 2         | 8%      |
| Realtek USB2.0 Finger Print Bridge | 2         | 8%      |
| Elan Microelectronics              | 2         | 8%      |
| Upek                               | 1         | 4%      |
| LighTuning Technology              | 1         | 4%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                                 | 3         | 12%     |
| STMicroelectronics Fingerprint Reader                           | 3         | 12%     |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 2         | 8%      |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 2         | 8%      |
| Validity Sensors VFS495 Fingerprint Reader                      | 1         | 4%      |
| Validity Sensors VFS451 Fingerprint Reader                      | 1         | 4%      |
| Validity Sensors VFS300 Fingerprint Reader                      | 1         | 4%      |
| Validity Sensors VFS Fingerprint sensor                         | 1         | 4%      |
| Validity Sensors VFS 5011 fingerprint sensor                    | 1         | 4%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 1         | 4%      |
| Synaptics WBDI Device                                           | 1         | 4%      |
| Synaptics TouchPad                                              | 1         | 4%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 1         | 4%      |
| Shenzhen Goodix  FingerPrint Device                             | 1         | 4%      |
| Shenzhen Goodix Fingerprint Reader                              | 1         | 4%      |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 1         | 4%      |
| Elan ELAN:Fingerprint                                           | 1         | 4%      |
| Elan ELAN:ARM-M4                                                | 1         | 4%      |
| Unknown                                                         | 1         | 4%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


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

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 127       | 58.8%   |
| 1     | 54        | 25%     |
| 2     | 21        | 9.72%   |
| 3     | 7         | 3.24%   |
| 4     | 6         | 2.78%   |
| 5     | 1         | 0.46%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 27        | 20%     |
| Fingerprint reader       | 24        | 17.78%  |
| Sound                    | 19        | 14.07%  |
| Net/wireless             | 15        | 11.11%  |
| Communication controller | 10        | 7.41%   |
| Chipcard                 | 10        | 7.41%   |
| Multimedia controller    | 6         | 4.44%   |
| Unassigned class         | 5         | 3.7%    |
| Card reader              | 4         | 2.96%   |
| Camera                   | 4         | 2.96%   |
| Bluetooth                | 4         | 2.96%   |
| Net/ethernet             | 2         | 1.48%   |
| Storage/raid             | 1         | 0.74%   |
| Storage/ide              | 1         | 0.74%   |
| Storage/ata              | 1         | 0.74%   |
| Storage                  | 1         | 0.74%   |
| Firewire controller      | 1         | 0.74%   |

