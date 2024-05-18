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

Total: 234

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
| Slackware 15.0  | 113       | 61.08%  |
| Slackware 14.2  | 63        | 34.05%  |
| Slackware 14.2+ | 6         | 3.24%   |
| Slackware 15.0+ | 2         | 1.08%   |
| Slackware 14.1  | 1         | 0.54%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Slackware | 183       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 5.15.19                     | 21        | 10.55%  |
| 4.19.80                     | 8         | 4.02%   |
| 5.19.17                     | 7         | 3.52%   |
| 5.15.63                     | 7         | 3.52%   |
| 5.10.28-Unraid              | 6         | 3.02%   |
| 5.19.17-Unraid              | 4         | 2.01%   |
| 5.15.27                     | 4         | 2.01%   |
| 5.15.145                    | 4         | 2.01%   |
| 5.15.117                    | 4         | 2.01%   |
| 4.4.190                     | 4         | 2.01%   |
| 5.15.94                     | 3         | 1.51%   |
| 5.15.38                     | 3         | 1.51%   |
| 4.4.240                     | 3         | 1.51%   |
| 6.6.18                      | 2         | 1.01%   |
| 6.1.64-Unraid               | 2         | 1.01%   |
| 6.1.44                      | 2         | 1.01%   |
| 5.3.7                       | 2         | 1.01%   |
| 5.17.2                      | 2         | 1.01%   |
| 5.17.1                      | 2         | 1.01%   |
| 5.16.13                     | 2         | 1.01%   |
| 5.15.80                     | 2         | 1.01%   |
| 5.15.30-Unraid              | 2         | 1.01%   |
| 5.15.118                    | 2         | 1.01%   |
| 5.13.8                      | 2         | 1.01%   |
| 5.10.3                      | 2         | 1.01%   |
| 4.4.276                     | 2         | 1.01%   |
| 6.7.5-gsh-clevo-NL51NU-SW15 | 1         | 0.5%    |
| 6.7.4-cometdust             | 1         | 0.5%    |
| 6.6.8                       | 1         | 0.5%    |
| 6.6.7                       | 1         | 0.5%    |
| 6.6.28                      | 1         | 0.5%    |
| 6.6.22                      | 1         | 0.5%    |
| 6.6.21                      | 1         | 0.5%    |
| 6.6.17                      | 1         | 0.5%    |
| 6.6.11                      | 1         | 0.5%    |
| 6.5.5                       | 1         | 0.5%    |
| 6.4.8-zen1                  | 1         | 0.5%    |
| 6.1.79-Unraid               | 1         | 0.5%    |
| 6.1.61                      | 1         | 0.5%    |
| 6.1.51                      | 1         | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.19  | 21        | 10.55%  |
| 5.19.17  | 11        | 5.53%   |
| 4.19.80  | 8         | 4.02%   |
| 5.15.63  | 7         | 3.52%   |
| 5.10.28  | 6         | 3.02%   |
| 4.4.190  | 5         | 2.51%   |
| 5.15.27  | 4         | 2.01%   |
| 5.15.145 | 4         | 2.01%   |
| 5.15.117 | 4         | 2.01%   |
| 5.15.94  | 3         | 1.51%   |
| 5.15.38  | 3         | 1.51%   |
| 4.4.240  | 3         | 1.51%   |
| 6.6.18   | 2         | 1.01%   |
| 6.1.64   | 2         | 1.01%   |
| 6.1.44   | 2         | 1.01%   |
| 5.3.7    | 2         | 1.01%   |
| 5.17.2   | 2         | 1.01%   |
| 5.17.1   | 2         | 1.01%   |
| 5.16.13  | 2         | 1.01%   |
| 5.15.80  | 2         | 1.01%   |
| 5.15.30  | 2         | 1.01%   |
| 5.15.118 | 2         | 1.01%   |
| 5.14.15  | 2         | 1.01%   |
| 5.13.8   | 2         | 1.01%   |
| 5.10.3   | 2         | 1.01%   |
| 4.4.276  | 2         | 1.01%   |
| 6.7.5    | 1         | 0.5%    |
| 6.7.4    | 1         | 0.5%    |
| 6.6.8    | 1         | 0.5%    |
| 6.6.7    | 1         | 0.5%    |
| 6.6.28   | 1         | 0.5%    |
| 6.6.22   | 1         | 0.5%    |
| 6.6.21   | 1         | 0.5%    |
| 6.6.17   | 1         | 0.5%    |
| 6.6.11   | 1         | 0.5%    |
| 6.5.5    | 1         | 0.5%    |
| 6.4.8    | 1         | 0.5%    |
| 6.1.79   | 1         | 0.5%    |
| 6.1.61   | 1         | 0.5%    |
| 6.1.51   | 1         | 0.5%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 63        | 32.31%  |
| 4.4     | 17        | 8.72%   |
| 5.10    | 15        | 7.69%   |
| 4.19    | 15        | 7.69%   |
| 5.4     | 13        | 6.67%   |
| 5.19    | 12        | 6.15%   |
| 6.1     | 11        | 5.64%   |
| 6.6     | 8         | 4.1%    |
| 5.14    | 7         | 3.59%   |
| 5.13    | 7         | 3.59%   |
| 5.17    | 6         | 3.08%   |
| 5.16    | 6         | 3.08%   |
| 6.7     | 2         | 1.03%   |
| 5.3     | 2         | 1.03%   |
| 4.9     | 2         | 1.03%   |
| 6.5     | 1         | 0.51%   |
| 6.4     | 1         | 0.51%   |
| 5.7     | 1         | 0.51%   |
| 5.5     | 1         | 0.51%   |
| 5.2     | 1         | 0.51%   |
| 5.12    | 1         | 0.51%   |
| 4.20    | 1         | 0.51%   |
| 4.16    | 1         | 0.51%   |
| 3.10    | 1         | 0.51%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 180       | 98.36%  |
| aarch64 | 2         | 1.09%   |
| i686    | 1         | 0.55%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 57        | 30.65%  |
| KDE5          | 54        | 29.03%  |
| XFCE          | 53        | 28.49%  |
| KDE           | 5         | 2.69%   |
| MATE          | 3         | 1.61%   |
| GNOME         | 3         | 1.61%   |
| xwmconfig     | 2         | 1.08%   |
| fvwm          | 2         | 1.08%   |
| X-Generic     | 1         | 0.54%   |
| X-Cinnamon    | 1         | 0.54%   |
| LXQt          | 1         | 0.54%   |
| Enlightenment | 1         | 0.54%   |
| DWM           | 1         | 0.54%   |
| awesome       | 1         | 0.54%   |
| 2bwm          | 1         | 0.54%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 115       | 60.85%  |
| Tty     | 47        | 24.87%  |
| Unknown | 17        | 8.99%   |
| Wayland | 10        | 5.29%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 74        | 39.15%  |
| SDDM    | 61        | 32.28%  |
| XDM     | 43        | 22.75%  |
| LightDM | 6         | 3.17%   |
| SLiM    | 4         | 2.12%   |
| GDM     | 1         | 0.53%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 101       | 54.89%  |
| Unknown     | 45        | 24.46%  |
| it_IT       | 7         | 3.8%    |
| ru_RU       | 4         | 2.17%   |
| pt_BR       | 4         | 2.17%   |
| fr_FR       | 3         | 1.63%   |
| en_GB       | 3         | 1.63%   |
| de_DE       | 3         | 1.63%   |
| cs_CZ       | 2         | 1.09%   |
| zh_TW       | 1         | 0.54%   |
| us          | 1         | 0.54%   |
| sr_RS@latin | 1         | 0.54%   |
| pt_PT       | 1         | 0.54%   |
| pl_PL       | 1         | 0.54%   |
| ja_JP       | 1         | 0.54%   |
| es_ES.UTF8  | 1         | 0.54%   |
| es_ES       | 1         | 0.54%   |
| en_US.ASCII | 1         | 0.54%   |
| en_SE       | 1         | 0.54%   |
| en_AU       | 1         | 0.54%   |
| C           | 1         | 0.54%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 93        | 50.27%  |
| EFI  | 92        | 49.73%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 136       | 73.51%  |
| Btrfs    | 19        | 10.27%  |
| Xfs      | 8         | 4.32%   |
| Overlay  | 7         | 3.78%   |
| Rootfs   | 6         | 3.24%   |
| Tmpfs    | 2         | 1.08%   |
| Jfs      | 2         | 1.08%   |
| Zfs      | 1         | 0.54%   |
| Reiserfs | 1         | 0.54%   |
| F2fs     | 1         | 0.54%   |
| Ext3     | 1         | 0.54%   |
| Ext2     | 1         | 0.54%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 121       | 64.71%  |
| MBR     | 42        | 22.46%  |
| Unknown | 24        | 12.83%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 128       | 68.82%  |
| Yes       | 58        | 31.18%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 127       | 69.02%  |
| Yes       | 57        | 30.98%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 29        | 15.85%  |
| Hewlett-Packard     | 27        | 14.75%  |
| Lenovo              | 25        | 13.66%  |
| Dell                | 19        | 10.38%  |
| MSI                 | 18        | 9.84%   |
| ASRock              | 12        | 6.56%   |
| Gigabyte Technology | 9         | 4.92%   |
| Acer                | 7         | 3.83%   |
| Toshiba             | 4         | 2.19%   |
| Notebook            | 4         | 2.19%   |
| Fujitsu             | 3         | 1.64%   |
| Dynabook            | 2         | 1.09%   |
| Apple               | 2         | 1.09%   |
| Unknown             | 2         | 1.09%   |
| Valve               | 1         | 0.55%   |
| TYAN Computer       | 1         | 0.55%   |
| System76            | 1         | 0.55%   |
| Supermicro          | 1         | 0.55%   |
| Sony                | 1         | 0.55%   |
| Shuttle             | 1         | 0.55%   |
| Samsung Electronics | 1         | 0.55%   |
| Radxa               | 1         | 0.55%   |
| NetGear             | 1         | 0.55%   |
| Microsoft           | 1         | 0.55%   |
| Intel               | 1         | 0.55%   |
| Huanan              | 1         | 0.55%   |
| HPE                 | 1         | 0.55%   |
| HEDYCOMPUTER        | 1         | 0.55%   |
| Framework           | 1         | 0.55%   |
| Foxconn             | 1         | 0.55%   |
| Chuwi               | 1         | 0.55%   |
| Biostar             | 1         | 0.55%   |
| BESSTAR Tech        | 1         | 0.55%   |
| AMI                 | 1         | 0.55%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| ASUS All Series                          | 4         | 2.19%   |
| Toshiba Satellite C660                   | 2         | 1.09%   |
| MSI MS-7D76                              | 2         | 1.09%   |
| Lenovo V330-14ARR 81B1                   | 2         | 1.09%   |
| ASUS VivoBook_ASUSLaptop K6500ZE_K6500ZE | 2         | 1.09%   |
| ASRock N68-S3 FX                         | 2         | 1.09%   |
| Unknown                                  | 2         | 1.09%   |
| Valve Jupiter                            | 1         | 0.55%   |
| TYAN S7012                               | 1         | 0.55%   |
| Toshiba Satellite P50-A-12Z              | 1         | 0.55%   |
| Toshiba PORTEGE Z30-A                    | 1         | 0.55%   |
| System76 Oryx Pro                        | 1         | 0.55%   |
| Supermicro X9DA7/E                       | 1         | 0.55%   |
| Sony SVE1713A1EW                         | 1         | 0.55%   |
| Shuttle NC03U                            | 1         | 0.55%   |
| Samsung 300E5M/300E5L                    | 1         | 0.55%   |
| Radxa ROCK Pi 4                          | 1         | 0.55%   |
| Notebook X170KM-G                        | 1         | 0.55%   |
| Notebook P7xxTM                          | 1         | 0.55%   |
| Notebook NL5xNU                          | 1         | 0.55%   |
| Notebook NL40_50CU                       | 1         | 0.55%   |
| NetGear ReadyDATA 5200                   | 1         | 0.55%   |
| MSI MS-7D67                              | 1         | 0.55%   |
| MSI MS-7C52                              | 1         | 0.55%   |
| MSI MS-7C02                              | 1         | 0.55%   |
| MSI MS-7B79                              | 1         | 0.55%   |
| MSI MS-7996                              | 1         | 0.55%   |
| MSI MS-7885                              | 1         | 0.55%   |
| MSI MS-7788                              | 1         | 0.55%   |
| MSI MS-7693                              | 1         | 0.55%   |
| MSI MS-7529                              | 1         | 0.55%   |
| MSI MS-7365                              | 1         | 0.55%   |
| MSI Modern 14 B5M                        | 1         | 0.55%   |
| MSI Modern 14 B11MO                      | 1         | 0.55%   |
| MSI Modern 14 B10MW                      | 1         | 0.55%   |
| MSI GP76 Leopard 11UG                    | 1         | 0.55%   |
| MSI GL73 8RC                             | 1         | 0.55%   |
| MSI GE76 Raider 11UE                     | 1         | 0.55%   |
| Microsoft Surface Go 3                   | 1         | 0.55%   |
| Lenovo ThinkPad X230 2325P38             | 1         | 0.55%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 18        | 9.84%   |
| Dell Precision    | 6         | 3.28%   |
| ASUS PRIME        | 6         | 3.28%   |
| HP Pavilion       | 4         | 2.19%   |
| HP Laptop         | 4         | 2.19%   |
| ASUS ROG          | 4         | 2.19%   |
| ASUS All          | 4         | 2.19%   |
| Toshiba Satellite | 3         | 1.64%   |
| MSI Modern        | 3         | 1.64%   |
| Lenovo IdeaPad    | 3         | 1.64%   |
| HP EliteBook      | 3         | 1.64%   |
| Dell Latitude     | 3         | 1.64%   |
| ASUS VivoBook     | 3         | 1.64%   |
| Acer Aspire       | 3         | 1.64%   |
| MSI MS-7D76       | 2         | 1.09%   |
| Lenovo V330-14ARR | 2         | 1.09%   |
| HP OMEN           | 2         | 1.09%   |
| Gigabyte X570     | 2         | 1.09%   |
| Fujitsu LIFEBOOK  | 2         | 1.09%   |
| Dell XPS          | 2         | 1.09%   |
| Dell Vostro       | 2         | 1.09%   |
| Dell PowerEdge    | 2         | 1.09%   |
| Dell OptiPlex     | 2         | 1.09%   |
| Dell Inspiron     | 2         | 1.09%   |
| ASUS TUF          | 2         | 1.09%   |
| ASRock N68-S3     | 2         | 1.09%   |
| Acer Swift        | 2         | 1.09%   |
| Unknown           | 2         | 1.09%   |
| Valve Jupiter     | 1         | 0.55%   |
| TYAN S7012        | 1         | 0.55%   |
| Toshiba PORTEGE   | 1         | 0.55%   |
| System76 Oryx     | 1         | 0.55%   |
| Supermicro X9DA7  | 1         | 0.55%   |
| Sony SVE1713A1EW  | 1         | 0.55%   |
| Shuttle NC03U     | 1         | 0.55%   |
| Samsung 300E5M    | 1         | 0.55%   |
| Radxa ROCK        | 1         | 0.55%   |
| Notebook X170KM-G | 1         | 0.55%   |
| Notebook P7xxTM   | 1         | 0.55%   |
| Notebook NL5xNU   | 1         | 0.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 20        | 10.93%  |
| 2020    | 19        | 10.38%  |
| 2021    | 15        | 8.2%    |
| 2017    | 15        | 8.2%    |
| 2012    | 15        | 8.2%    |
| 2018    | 13        | 7.1%    |
| 2015    | 13        | 7.1%    |
| 2022    | 12        | 6.56%   |
| 2014    | 12        | 6.56%   |
| 2011    | 9         | 4.92%   |
| 2016    | 8         | 4.37%   |
| 2008    | 8         | 4.37%   |
| 2010    | 6         | 3.28%   |
| 2007    | 5         | 2.73%   |
| 2013    | 4         | 2.19%   |
| 2009    | 4         | 2.19%   |
| 2023    | 2         | 1.09%   |
| Unknown | 2         | 1.09%   |
| 2024    | 1         | 0.55%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 87        | 47.54%  |
| Desktop        | 81        | 44.26%  |
| Mini pc        | 6         | 3.28%   |
| Server         | 3         | 1.64%   |
| System on chip | 2         | 1.09%   |
| All in one     | 2         | 1.09%   |
| Tablet         | 1         | 0.55%   |
| Convertible    | 1         | 0.55%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 183       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 180       | 98.36%  |
| Yes  | 3         | 1.64%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 37        | 20%     |
| 8.01-16.0   | 37        | 20%     |
| 4.01-8.0    | 32        | 17.3%   |
| 3.01-4.0    | 24        | 12.97%  |
| 32.01-64.0  | 22        | 11.89%  |
| 64.01-256.0 | 15        | 8.11%   |
| 24.01-32.0  | 10        | 5.41%   |
| 1.01-2.0    | 6         | 3.24%   |
| 2.01-3.0    | 1         | 0.54%   |
| 0.51-1.0    | 1         | 0.54%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 51        | 26.02%  |
| 2.01-3.0    | 44        | 22.45%  |
| 4.01-8.0    | 38        | 19.39%  |
| 3.01-4.0    | 21        | 10.71%  |
| 0.51-1.0    | 16        | 8.16%   |
| 8.01-16.0   | 9         | 4.59%   |
| 0.01-0.5    | 6         | 3.06%   |
| 16.01-24.0  | 5         | 2.55%   |
| 24.01-32.0  | 3         | 1.53%   |
| 32.01-64.0  | 1         | 0.51%   |
| 64.01-256.0 | 1         | 0.51%   |
| Unknown     | 1         | 0.51%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 89        | 47.34%  |
| 2      | 45        | 23.94%  |
| 3      | 18        | 9.57%   |
| 4      | 11        | 5.85%   |
| 6      | 6         | 3.19%   |
| 5      | 6         | 3.19%   |
| 0      | 4         | 2.13%   |
| 10     | 2         | 1.06%   |
| 9      | 2         | 1.06%   |
| 14     | 1         | 0.53%   |
| 13     | 1         | 0.53%   |
| 11     | 1         | 0.53%   |
| 8      | 1         | 0.53%   |
| 7      | 1         | 0.53%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 120       | 65.22%  |
| Yes       | 64        | 34.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 167       | 90.76%  |
| No        | 17        | 9.24%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 128       | 69.95%  |
| No        | 55        | 30.05%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 115       | 62.5%   |
| No        | 69        | 37.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 38        | 20.77%  |
| UK           | 16        | 8.74%   |
| Japan        | 11        | 6.01%   |
| Italy        | 11        | 6.01%   |
| Germany      | 11        | 6.01%   |
| Brazil       | 11        | 6.01%   |
| Portugal     | 8         | 4.37%   |
| Russia       | 7         | 3.83%   |
| France       | 7         | 3.83%   |
| Canada       | 7         | 3.83%   |
| Kazakhstan   | 6         | 3.28%   |
| India        | 6         | 3.28%   |
| Spain        | 5         | 2.73%   |
| Sweden       | 4         | 2.19%   |
| South Africa | 3         | 1.64%   |
| Poland       | 3         | 1.64%   |
| Hong Kong    | 3         | 1.64%   |
| Greece       | 3         | 1.64%   |
| Serbia       | 2         | 1.09%   |
| Romania      | 2         | 1.09%   |
| Czechia      | 2         | 1.09%   |
| China        | 2         | 1.09%   |
| Chile        | 2         | 1.09%   |
| Australia    | 2         | 1.09%   |
| Argentina    | 2         | 1.09%   |
| Taiwan       | 1         | 0.55%   |
| Switzerland  | 1         | 0.55%   |
| Philippines  | 1         | 0.55%   |
| Paraguay     | 1         | 0.55%   |
| Netherlands  | 1         | 0.55%   |
| Mexico       | 1         | 0.55%   |
| Iran         | 1         | 0.55%   |
| Finland      | 1         | 0.55%   |
| Bulgaria     | 1         | 0.55%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Tsukuba                | 6         | 3.19%   |
| Lisbon                 | 6         | 3.19%   |
| Ust-Kamenogorsk        | 4         | 2.13%   |
| Yekaterinburg          | 3         | 1.6%    |
| Warsaw                 | 3         | 1.6%    |
| Paris                  | 3         | 1.6%    |
| Milan                  | 3         | 1.6%    |
| Chania                 | 3         | 1.6%    |
| Tokyo                  | 2         | 1.06%   |
| Tendo                  | 2         | 1.06%   |
| Sun Prairie            | 2         | 1.06%   |
| Springfield            | 2         | 1.06%   |
| Rome                   | 2         | 1.06%   |
| New Delhi              | 2         | 1.06%   |
| Moscow                 | 2         | 1.06%   |
| McKinney               | 2         | 1.06%   |
| Karaganda              | 2         | 1.06%   |
| Greater Noida          | 2         | 1.06%   |
| Frignano               | 2         | 1.06%   |
| Fayetteville           | 2         | 1.06%   |
| Dallas                 | 2         | 1.06%   |
| Carrollton             | 2         | 1.06%   |
| Cape Town              | 2         | 1.06%   |
| Bucharest              | 2         | 1.06%   |
| Belgrade               | 2         | 1.06%   |
| Barry                  | 2         | 1.06%   |
| Barrie                 | 2         | 1.06%   |
| Worpswede              | 1         | 0.53%   |
| Wokingham              | 1         | 0.53%   |
| Winter Springs         | 1         | 0.53%   |
| Winnipeg               | 1         | 0.53%   |
| Weilheim               | 1         | 0.53%   |
| Voskresensk            | 1         | 0.53%   |
| Visconde do Rio Branco | 1         | 0.53%   |
| Villa Carlos Paz       | 1         | 0.53%   |
| Toronto                | 1         | 0.53%   |
| Tiffin                 | 1         | 0.53%   |
| Tehran                 | 1         | 0.53%   |
| Tatuí                 | 1         | 0.53%   |
| Taichung               | 1         | 0.53%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 52        | 115    | 17.39%  |
| Samsung Electronics         | 51        | 75     | 17.06%  |
| Seagate                     | 45        | 83     | 15.05%  |
| Toshiba                     | 19        | 36     | 6.35%   |
| Kingston                    | 16        | 19     | 5.35%   |
| Crucial                     | 12        | 14     | 4.01%   |
| Intel                       | 10        | 12     | 3.34%   |
| SanDisk                     | 8         | 10     | 2.68%   |
| Hitachi                     | 8         | 11     | 2.68%   |
| Unknown                     | 7         | 10     | 2.34%   |
| HGST                        | 6         | 6      | 2.01%   |
| SK hynix                    | 5         | 5      | 1.67%   |
| A-DATA Technology           | 5         | 5      | 1.67%   |
| Micron Technology           | 4         | 4      | 1.34%   |
| Hewlett-Packard             | 4         | 5      | 1.34%   |
| Transcend                   | 3         | 3      | 1%      |
| Patriot                     | 3         | 4      | 1%      |
| KIOXIA                      | 3         | 3      | 1%      |
| Gigabyte Technology         | 3         | 3      | 1%      |
| Team                        | 2         | 2      | 0.67%   |
| Silicon Motion              | 2         | 3      | 0.67%   |
| Micron/Crucial Technology   | 2         | 2      | 0.67%   |
| Maxtor                      | 2         | 2      | 0.67%   |
| Kingston Technology Company | 2         | 2      | 0.67%   |
| JMicron Technology          | 2         | 2      | 0.67%   |
| Fujitsu                     | 2         | 2      | 0.67%   |
| External                    | 2         | 2      | 0.67%   |
| China                       | 2         | 3      | 0.67%   |
| Apple                       | 2         | 3      | 0.67%   |
| ZHITAI                      | 1         | 2      | 0.33%   |
| Verbatim                    | 1         | 2      | 0.33%   |
| TO Exter                    | 1         | 1      | 0.33%   |
| Realtek Semiconductor       | 1         | 1      | 0.33%   |
| PNY                         | 1         | 1      | 0.33%   |
| Plextor                     | 1         | 1      | 0.33%   |
| Phison Electronics          | 1         | 1      | 0.33%   |
| Netac                       | 1         | 1      | 0.33%   |
| LITEON                      | 1         | 1      | 0.33%   |
| Lexar                       | 1         | 1      | 0.33%   |
| Intenso                     | 1         | 1      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                       | 7         | 1.91%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 4         | 1.09%   |
| WDC WD20EFRX-68EUZN0 2TB                              | 3         | 0.82%   |
| WDC WD1003FZEX-00MK2A0 1TB                            | 3         | 0.82%   |
| Seagate ST4000DM004-2CV104 4TB                        | 3         | 0.82%   |
| Seagate ST2000DM008-2FR102 2TB                        | 3         | 0.82%   |
| Seagate ST1000LM048-2E7172 1TB                        | 3         | 0.82%   |
| Samsung SSD 970 EVO 250GB                             | 3         | 0.82%   |
| Intel SSD 660P Series 1024GB                          | 3         | 0.82%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                        | 2         | 0.54%   |
| WDC WD40EZRX-00SPEB0 4TB                              | 2         | 0.54%   |
| WDC WD30EZRX-00SPEB0 3TB                              | 2         | 0.54%   |
| WDC WD10SPZX-60Z10T0 1TB                              | 2         | 0.54%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 2         | 0.54%   |
| WDC WD10EZEX-00RKKA0 1TB                              | 2         | 0.54%   |
| Toshiba MQ04ABF100 1TB                                | 2         | 0.54%   |
| Toshiba MQ01ABD100 1TB                                | 2         | 0.54%   |
| Toshiba HDWD110 1TB                                   | 2         | 0.54%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 2         | 0.54%   |
| Seagate ST500DM002-1BD142 500GB                       | 2         | 0.54%   |
| Seagate ST4000VN008-2DR166 4TB                        | 2         | 0.54%   |
| Seagate ST4000VN006-3CW104 4TB                        | 2         | 0.54%   |
| Seagate ST31000524AS 1TB                              | 2         | 0.54%   |
| Seagate ST2000DX001-1NS164 2TB                        | 2         | 0.54%   |
| Seagate ST2000DM001-1CH164 2TB                        | 2         | 0.54%   |
| Seagate ST2000DL003-9VT166 2TB                        | 2         | 0.54%   |
| Seagate ST1000DM010-2EP102 1TB                        | 2         | 0.54%   |
| Seagate ST1000DM003-1SB102 1TB                        | 2         | 0.54%   |
| Seagate ST1000DM003-1ER162 1TB                        | 2         | 0.54%   |
| Seagate Expansion+ Desk 4TB                           | 2         | 0.54%   |
| Samsung SSD 970 EVO Plus 500GB                        | 2         | 0.54%   |
| Samsung SSD 970 EVO Plus 1TB                          | 2         | 0.54%   |
| Samsung SSD 860 QVO 2TB                               | 2         | 0.54%   |
| Samsung SSD 850 PRO 256GB                             | 2         | 0.54%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 2         | 0.54%   |
| Kingston Company OM3PDP3 NVMe SSD 512GB               | 2         | 0.54%   |
| Kingston SA400S37120G 120GB SSD                       | 2         | 0.54%   |
| JMicron Generic 320GB                                 | 2         | 0.54%   |
| HGST HTS725050A7E630 500GB                            | 2         | 0.54%   |
| External USB3.0 500GB                                 | 2         | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 45        | 103    | 33.33%  |
| Seagate             | 45        | 79     | 33.33%  |
| Toshiba             | 18        | 31     | 13.33%  |
| Hitachi             | 8         | 11     | 5.93%   |
| HGST                | 6         | 6      | 4.44%   |
| Samsung Electronics | 4         | 4      | 2.96%   |
| Maxtor              | 2         | 2      | 1.48%   |
| JMicron Technology  | 2         | 2      | 1.48%   |
| Hewlett-Packard     | 2         | 2      | 1.48%   |
| Fujitsu             | 2         | 2      | 1.48%   |
| TO Exter            | 1         | 1      | 0.74%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 22        | 33     | 25%     |
| Kingston            | 14        | 17     | 15.91%  |
| Crucial             | 9         | 11     | 10.23%  |
| WDC                 | 5         | 7      | 5.68%   |
| SanDisk             | 5         | 5      | 5.68%   |
| Transcend           | 2         | 2      | 2.27%   |
| Patriot             | 2         | 3      | 2.27%   |
| Micron Technology   | 2         | 2      | 2.27%   |
| Intel               | 2         | 3      | 2.27%   |
| External            | 2         | 2      | 2.27%   |
| China               | 2         | 3      | 2.27%   |
| Apple               | 2         | 3      | 2.27%   |
| A-DATA Technology   | 2         | 2      | 2.27%   |
| ZHITAI              | 1         | 1      | 1.14%   |
| Verbatim            | 1         | 2      | 1.14%   |
| Toshiba             | 1         | 3      | 1.14%   |
| Team                | 1         | 1      | 1.14%   |
| SK hynix            | 1         | 1      | 1.14%   |
| PNY                 | 1         | 1      | 1.14%   |
| Plextor             | 1         | 1      | 1.14%   |
| Netac               | 1         | 1      | 1.14%   |
| LITEON              | 1         | 1      | 1.14%   |
| Lexar               | 1         | 1      | 1.14%   |
| Intenso             | 1         | 1      | 1.14%   |
| Hewlett-Packard     | 1         | 1      | 1.14%   |
| GOODRAM             | 1         | 1      | 1.14%   |
| Gigabyte Technology | 1         | 1      | 1.14%   |
| DUEX                | 1         | 1      | 1.14%   |
| Dogfish             | 1         | 1      | 1.14%   |
| AirDisk             | 1         | 1      | 1.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 97        | 243    | 37.74%  |
| SSD     | 81        | 113    | 31.52%  |
| NVMe    | 72        | 95     | 28.02%  |
| MMC     | 6         | 8      | 2.33%   |
| Unknown | 1         | 4      | 0.39%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 134       | 343    | 60.36%  |
| NVMe | 72        | 95     | 32.43%  |
| SAS  | 10        | 17     | 4.5%    |
| MMC  | 6         | 8      | 2.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 99        | 141    | 47.6%   |
| 0.51-1.0   | 51        | 96     | 24.52%  |
| 1.01-2.0   | 21        | 28     | 10.1%   |
| 3.01-4.0   | 19        | 38     | 9.13%   |
| 2.01-3.0   | 9         | 21     | 4.33%   |
| 4.01-10.0  | 7         | 27     | 3.37%   |
| 10.01-20.0 | 2         | 5      | 0.96%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 42        | 22.34%  |
| 501-1000       | 42        | 22.34%  |
| 251-500        | 26        | 13.83%  |
| 1001-2000      | 22        | 11.7%   |
| Unknown        | 20        | 10.64%  |
| 2001-3000      | 10        | 5.32%   |
| 1-20           | 10        | 5.32%   |
| More than 3000 | 7         | 3.72%   |
| 51-100         | 6         | 3.19%   |
| 21-50          | 3         | 1.6%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 38        | 19.79%  |
| 1-20           | 31        | 16.15%  |
| 21-50          | 25        | 13.02%  |
| 251-500        | 24        | 12.5%   |
| 501-1000       | 22        | 11.46%  |
| Unknown        | 20        | 10.42%  |
| 51-100         | 17        | 8.85%   |
| 1001-2000      | 10        | 5.21%   |
| More than 3000 | 4         | 2.08%   |
| 2001-3000      | 1         | 0.52%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1         | 1      | 2.22%   |
| WDC WD5003ABYX-18WERA0 500GB          | 1         | 2      | 2.22%   |
| WDC WD5000LPCX-60VHAT1 500GB          | 1         | 1      | 2.22%   |
| WDC WD5000BPKX-60HPJT0 500GB          | 1         | 1      | 2.22%   |
| WDC WD5000AAKX-22ERMA0 500GB          | 1         | 1      | 2.22%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 1         | 1      | 2.22%   |
| WDC WD5000AAKS-00A7B2 500GB           | 1         | 1      | 2.22%   |
| WDC WD40EFRX-68WT0N0 4TB              | 1         | 2      | 2.22%   |
| WDC WD40EFAX-68JH4N1 4TB              | 1         | 4      | 2.22%   |
| WDC WD3200AAJS-65B4A0 320GB           | 1         | 1      | 2.22%   |
| WDC WD30EZRX-00MMMB0 3TB              | 1         | 1      | 2.22%   |
| WDC WD30EZRX-00M                      | 1         | 1      | 2.22%   |
| WDC WD30EZRX-00D8PB0 3TB              | 1         | 1      | 2.22%   |
| WDC WD30EFRX-68AX9N0 3TB              | 1         | 4      | 2.22%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1         | 2      | 2.22%   |
| WDC WD20EARX-00PASB0 2TB              | 1         | 1      | 2.22%   |
| WDC WD10JPLX-00MBPT0 1TB              | 1         | 1      | 2.22%   |
| WDC WD10EZEX-00RKKA0 1TB              | 1         | 1      | 2.22%   |
| WDC WD10EALS-00Z8A0 1TB               | 1         | 2      | 2.22%   |
| WDC WD1003FZEX-00MK2A0 1TB            | 1         | 2      | 2.22%   |
| Toshiba MK2565GSXN 250GB              | 1         | 1      | 2.22%   |
| Seagate ST380011A 80GB                | 1         | 2      | 2.22%   |
| Seagate ST3500630AS 500GB             | 1         | 1      | 2.22%   |
| Seagate ST3500418AS 500GB             | 1         | 1      | 2.22%   |
| Seagate ST3500410AS 500GB             | 1         | 1      | 2.22%   |
| Seagate ST31000524AS 1TB              | 1         | 1      | 2.22%   |
| Seagate ST3000VX006-1HH166 3TB        | 1         | 1      | 2.22%   |
| Seagate ST2000DL003-9VT166 2TB        | 1         | 1      | 2.22%   |
| Seagate ST1000VM002-1SD102 1TB        | 1         | 1      | 2.22%   |
| Seagate ST1000NM0011 1TB              | 1         | 2      | 2.22%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 2.22%   |
| Seagate ST1000DM003-1ER162 1TB        | 1         | 2      | 2.22%   |
| SanDisk SDSA6MM-016G-1006 16GB SSD    | 1         | 1      | 2.22%   |
| Samsung Electronics SSD 970 EVO 500GB | 1         | 1      | 2.22%   |
| Samsung Electronics SSD 870 EVO 1TB   | 1         | 1      | 2.22%   |
| Plextor PX-128M6S 128GB SSD           | 1         | 1      | 2.22%   |
| Maxtor 4G120J6 128GB                  | 1         | 1      | 2.22%   |
| Intel SSDSA2M080G2GC 80GB             | 1         | 1      | 2.22%   |
| Hitachi HUA723030ALA640 3TB           | 1         | 1      | 2.22%   |
| Hitachi HDS721050CLA660 500GB         | 1         | 1      | 2.22%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 17        | 31     | 41.46%  |
| Seagate             | 10        | 14     | 24.39%  |
| Hitachi             | 3         | 3      | 7.32%   |
| HGST                | 3         | 3      | 7.32%   |
| Samsung Electronics | 2         | 2      | 4.88%   |
| Toshiba             | 1         | 1      | 2.44%   |
| SanDisk             | 1         | 1      | 2.44%   |
| Plextor             | 1         | 1      | 2.44%   |
| Maxtor              | 1         | 1      | 2.44%   |
| Intel               | 1         | 1      | 2.44%   |
| DUEX                | 1         | 1      | 2.44%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 16        | 30     | 47.06%  |
| Seagate | 10        | 14     | 29.41%  |
| Hitachi | 3         | 3      | 8.82%   |
| HGST    | 3         | 3      | 8.82%   |
| Toshiba | 1         | 1      | 2.94%   |
| Maxtor  | 1         | 1      | 2.94%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 31        | 52     | 81.58%  |
| SSD  | 6         | 6      | 15.79%  |
| NVMe | 1         | 1      | 2.63%   |

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
| Works    | 143       | 324    | 65%     |
| Detected | 39        | 80     | 17.73%  |
| Malfunc  | 38        | 59     | 17.27%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 105       | 40.23%  |
| AMD                          | 49        | 18.77%  |
| Samsung Electronics          | 30        | 11.49%  |
| ASMedia Technology           | 12        | 4.6%    |
| SanDisk                      | 8         | 3.07%   |
| Marvell Technology Group     | 8         | 3.07%   |
| Nvidia                       | 5         | 1.92%   |
| Micron/Crucial Technology    | 5         | 1.92%   |
| SK hynix                     | 4         | 1.53%   |
| Realtek Semiconductor        | 4         | 1.53%   |
| Kingston Technology Company  | 4         | 1.53%   |
| JMicron Technology           | 4         | 1.53%   |
| Phison Electronics           | 3         | 1.15%   |
| KIOXIA                       | 3         | 1.15%   |
| Broadcom / LSI               | 3         | 1.15%   |
| Silicon Motion               | 2         | 0.77%   |
| Micron Technology            | 2         | 0.77%   |
| LSI Logic / Symbios Logic    | 2         | 0.77%   |
| Yangtze Memory Technologies  | 1         | 0.38%   |
| Toshiba America Info Systems | 1         | 0.38%   |
| Silicon Image                | 1         | 0.38%   |
| Nextorage                    | 1         | 0.38%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.38%   |
| Biwin Storage Technology     | 1         | 0.38%   |
| Adaptec                      | 1         | 0.38%   |
| 3ware                        | 1         | 0.38%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 32        | 10.32%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 16        | 5.16%   |
| AMD 400 Series Chipset SATA Controller                                           | 11        | 3.55%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                    | 9         | 2.9%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 8         | 2.58%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 7         | 2.26%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 7         | 2.26%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 2.26%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 7         | 2.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 5         | 1.61%   |
| Nvidia MCP61 SATA Controller                                                     | 4         | 1.29%   |
| Nvidia MCP61 IDE                                                                 | 4         | 1.29%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 4         | 1.29%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 1.29%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 4         | 1.29%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 4         | 1.29%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 1.29%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 4         | 1.29%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 1.29%   |
| AMD 500 Series Chipset SATA Controller                                           | 4         | 1.29%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 0.97%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 3         | 0.97%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 3         | 0.97%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 3         | 0.97%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 0.97%   |
| Intel SSD 660P Series                                                            | 3         | 0.97%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 3         | 0.97%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 0.97%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 0.97%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 0.97%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 3         | 0.97%   |
| AMD 600 Series Chipset SATA Controller                                           | 3         | 0.97%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 2         | 0.65%   |
| SK hynix BC511 NVMe SSD                                                          | 2         | 0.65%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 2         | 0.65%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 2         | 0.65%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 2         | 0.65%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                | 2         | 0.65%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 2         | 0.65%   |
| JMicron JMB58x AHCI SATA controller                                              | 2         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 130       | 51.59%  |
| NVMe | 72        | 28.57%  |
| IDE  | 25        | 9.92%   |
| RAID | 18        | 7.14%   |
| SAS  | 4         | 1.59%   |
| SCSI | 3         | 1.19%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 122       | 66.67%  |
| AMD    | 59        | 32.24%  |
| ARM    | 2         | 1.09%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 4         | 2.17%   |
| AMD Ryzen 5 3600 6-Core Processor             | 4         | 2.17%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.63%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 1.63%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.63%   |
| Intel 12th Gen Core i7-12700H                 | 3         | 1.63%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 3         | 1.63%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 3         | 1.63%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 3         | 1.63%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz            | 2         | 1.09%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 1.09%   |
| Intel Core i7-5820K CPU @ 3.30GHz             | 2         | 1.09%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 2         | 1.09%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.09%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 1.09%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1.09%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 2         | 1.09%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 2         | 1.09%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 1.09%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.09%   |
| ARM Processor                                 | 2         | 1.09%   |
| AMD Ryzen 9 7900 12-Core Processor            | 2         | 1.09%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 2         | 1.09%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 2         | 1.09%   |
| AMD FX-8350 Eight-Core Processor              | 2         | 1.09%   |
| AMD Athlon II X2 250 Processor                | 2         | 1.09%   |
| Intel Xeon CPU X5680 @ 3.33GHz                | 1         | 0.54%   |
| Intel Xeon CPU X5355 @ 2.66GHz                | 1         | 0.54%   |
| Intel Xeon CPU X3450 @ 2.67GHz                | 1         | 0.54%   |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz           | 1         | 0.54%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz           | 1         | 0.54%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz           | 1         | 0.54%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz            | 1         | 0.54%   |
| Intel Xeon CPU E5-2407 0 @ 2.20GHz            | 1         | 0.54%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz            | 1         | 0.54%   |
| Intel Xeon CPU E5-1603 v3 @ 2.80GHz           | 1         | 0.54%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz           | 1         | 0.54%   |
| Intel Xeon CPU 5160 @ 3.00GHz                 | 1         | 0.54%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 0.54%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz        | 1         | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 31        | 16.85%  |
| Intel Core i7        | 28        | 15.22%  |
| Other                | 18        | 9.78%   |
| AMD Ryzen 5          | 16        | 8.7%    |
| Intel Xeon           | 14        | 7.61%   |
| AMD Ryzen 7          | 11        | 5.98%   |
| AMD Ryzen 9          | 10        | 5.43%   |
| Intel Core i3        | 8         | 4.35%   |
| Intel Pentium        | 7         | 3.8%    |
| Intel Core 2 Duo     | 6         | 3.26%   |
| AMD FX               | 5         | 2.72%   |
| Intel Celeron        | 4         | 2.17%   |
| Intel Atom           | 3         | 1.63%   |
| Intel Core 2 Quad    | 2         | 1.09%   |
| AMD Ryzen 7 PRO      | 2         | 1.09%   |
| AMD Athlon II X2     | 2         | 1.09%   |
| Intel Pentium Silver | 1         | 0.54%   |
| Intel Pentium Gold   | 1         | 0.54%   |
| Intel Pentium Dual   | 1         | 0.54%   |
| Intel Core M         | 1         | 0.54%   |
| Intel Core 2         | 1         | 0.54%   |
| AMD Ryzen Embedded   | 1         | 0.54%   |
| AMD Ryzen 3 PRO      | 1         | 0.54%   |
| AMD Ryzen 3          | 1         | 0.54%   |
| AMD GX               | 1         | 0.54%   |
| AMD G                | 1         | 0.54%   |
| AMD EPYC             | 1         | 0.54%   |
| AMD E1               | 1         | 0.54%   |
| AMD Athlon 64 X2     | 1         | 0.54%   |
| AMD Athlon           | 1         | 0.54%   |
| AMD A8               | 1         | 0.54%   |
| AMD A4               | 1         | 0.54%   |
| AMD A10              | 1         | 0.54%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 61        | 33.15%  |
| 2      | 56        | 30.43%  |
| 8      | 24        | 13.04%  |
| 6      | 18        | 9.78%   |
| 16     | 7         | 3.8%    |
| 12     | 7         | 3.8%    |
| 14     | 4         | 2.17%   |
| 10     | 3         | 1.63%   |
| 1      | 3         | 1.63%   |
| 3      | 1         | 0.54%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 175       | 95.63%  |
| 2      | 8         | 4.37%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 136       | 74.32%  |
| 1      | 47        | 25.68%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 180       | 98.36%  |
| Unknown        | 2         | 1.09%   |
| 32-bit         | 1         | 0.55%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 50        | 27.03%  |
| 0x306a9    | 9         | 4.86%   |
| 0x306c3    | 7         | 3.78%   |
| 0x08701021 | 6         | 3.24%   |
| 0x206d7    | 5         | 2.7%    |
| 0x08108109 | 5         | 2.7%    |
| 0x906a3    | 4         | 2.16%   |
| 0x806ea    | 4         | 2.16%   |
| 0x806d1    | 4         | 2.16%   |
| 0x406e3    | 4         | 2.16%   |
| 0x306d4    | 4         | 2.16%   |
| 0x20655    | 4         | 2.16%   |
| 0x1067a    | 4         | 2.16%   |
| 0x906ea    | 3         | 1.62%   |
| 0x806ec    | 3         | 1.62%   |
| 0x806c1    | 3         | 1.62%   |
| 0x406c4    | 3         | 1.62%   |
| 0x306f2    | 3         | 1.62%   |
| 0x206a7    | 3         | 1.62%   |
| 0x08701013 | 3         | 1.62%   |
| 0x0810100b | 3         | 1.62%   |
| 0x906ed    | 2         | 1.08%   |
| 0x6fd      | 2         | 1.08%   |
| 0x506e3    | 2         | 1.08%   |
| 0x106c2    | 2         | 1.08%   |
| 0x0a50000c | 2         | 1.08%   |
| 0x0a201016 | 2         | 1.08%   |
| 0x08600106 | 2         | 1.08%   |
| 0x06001119 | 2         | 1.08%   |
| 0x06000822 | 2         | 1.08%   |
| 0xa0671    | 1         | 0.54%   |
| 0xa0660    | 1         | 0.54%   |
| 0xa0653    | 1         | 0.54%   |
| 0xa0652    | 1         | 0.54%   |
| 0x906e9    | 1         | 0.54%   |
| 0x906c0    | 1         | 0.54%   |
| 0x906a4    | 1         | 0.54%   |
| 0x806e9    | 1         | 0.54%   |
| 0x706a1    | 1         | 0.54%   |
| 0x6fb      | 1         | 0.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 25        | 13.59%  |
| Haswell          | 16        | 8.7%    |
| Zen 2            | 15        | 8.15%   |
| IvyBridge        | 11        | 5.98%   |
| SandyBridge      | 10        | 5.43%   |
| Unknown          | 10        | 5.43%   |
| Skylake          | 9         | 4.89%   |
| Zen+             | 8         | 4.35%   |
| Zen 3            | 8         | 4.35%   |
| Core             | 8         | 4.35%   |
| Zen              | 7         | 3.8%    |
| Westmere         | 7         | 3.8%    |
| Piledriver       | 6         | 3.26%   |
| Alderlake Hybrid | 6         | 3.26%   |
| Silvermont       | 5         | 2.72%   |
| Penryn           | 5         | 2.72%   |
| Icelake          | 5         | 2.72%   |
| Broadwell        | 4         | 2.17%   |
| TigerLake        | 3         | 1.63%   |
| CometLake        | 3         | 1.63%   |
| K10              | 2         | 1.09%   |
| Jaguar           | 2         | 1.09%   |
| Bonnell          | 2         | 1.09%   |
| Tremont          | 1         | 0.54%   |
| Puma             | 1         | 0.54%   |
| Nehalem          | 1         | 0.54%   |
| K8 Hammer        | 1         | 0.54%   |
| Goldmont plus    | 1         | 0.54%   |
| Bulldozer        | 1         | 0.54%   |
| Bobcat           | 1         | 0.54%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 82        | 41.41%  |
| AMD                        | 57        | 28.79%  |
| Nvidia                     | 54        | 27.27%  |
| Matrox Electronics Systems | 5         | 2.53%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 3.38%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 7         | 3.38%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 2.9%    |
| Intel UHD Graphics 620                                                                   | 5         | 2.42%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 2.42%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 2.42%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5         | 2.42%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 4         | 1.93%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 1.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.93%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 4         | 1.93%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 3         | 1.45%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 3         | 1.45%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.45%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 1.45%   |
| Intel HD Graphics 620                                                                    | 3         | 1.45%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.45%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.45%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 1.45%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 1.45%   |
| AMD Raphael                                                                              | 3         | 1.45%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 3         | 1.45%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.97%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.97%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 0.97%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2         | 0.97%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2         | 0.97%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2         | 0.97%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 0.97%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 2         | 0.97%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.97%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.97%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.97%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 0.97%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 0.97%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 0.97%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 0.97%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 2         | 0.97%   |
| AMD Navi 32 [Radeon RX 7700 XT / 7800 XT]                                                | 2         | 0.97%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 66        | 36.07%  |
| 1 x AMD        | 51        | 27.87%  |
| 1 x Nvidia     | 35        | 19.13%  |
| Intel + Nvidia | 15        | 8.2%    |
| 1 x Matrox     | 5         | 2.73%   |
| Other          | 4         | 2.19%   |
| 2 x AMD        | 4         | 2.19%   |
| AMD + Nvidia   | 2         | 1.09%   |
| 2 x Nvidia     | 1         | 0.55%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 141       | 76.63%  |
| Proprietary | 28        | 15.22%  |
| Unknown     | 15        | 8.15%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 102       | 54.84%  |
| 0.51-1.0   | 19        | 10.22%  |
| 1.01-2.0   | 16        | 8.6%    |
| 0.01-0.5   | 15        | 8.06%   |
| 3.01-4.0   | 12        | 6.45%   |
| 7.01-8.0   | 11        | 5.91%   |
| 5.01-6.0   | 5         | 2.69%   |
| 8.01-16.0  | 4         | 2.15%   |
| 2.01-3.0   | 1         | 0.54%   |
| 16.01-24.0 | 1         | 0.54%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 21        | 11.17%  |
| BOE                  | 19        | 10.11%  |
| AU Optronics         | 16        | 8.51%   |
| LG Display           | 15        | 7.98%   |
| Chimei Innolux       | 15        | 7.98%   |
| Dell                 | 14        | 7.45%   |
| Hewlett-Packard      | 13        | 6.91%   |
| Goldstar             | 11        | 5.85%   |
| BenQ                 | 10        | 5.32%   |
| Sharp                | 5         | 2.66%   |
| Lenovo               | 5         | 2.66%   |
| Ancor Communications | 4         | 2.13%   |
| Acer                 | 4         | 2.13%   |
| ASUSTek Computer     | 3         | 1.6%    |
| AOC                  | 3         | 1.6%    |
| ViewSonic            | 2         | 1.06%   |
| Iiyama               | 2         | 1.06%   |
| Xiaomi               | 1         | 0.53%   |
| Wacom                | 1         | 0.53%   |
| Valve                | 1         | 0.53%   |
| Unknown              | 1         | 0.53%   |
| UGD                  | 1         | 0.53%   |
| Toshiba              | 1         | 0.53%   |
| Sony                 | 1         | 0.53%   |
| Philips              | 1         | 0.53%   |
| PANDA                | 1         | 0.53%   |
| Panasonic            | 1         | 0.53%   |
| ONN                  | 1         | 0.53%   |
| NEC Computers        | 1         | 0.53%   |
| MSI                  | 1         | 0.53%   |
| JVC                  | 1         | 0.53%   |
| IOD                  | 1         | 0.53%   |
| InnoLux Display      | 1         | 0.53%   |
| Hyundai ImageQuest   | 1         | 0.53%   |
| HKC                  | 1         | 0.53%   |
| Gigabyte Technology  | 1         | 0.53%   |
| GDH                  | 1         | 0.53%   |
| Eizo                 | 1         | 0.53%   |
| DPC                  | 1         | 0.53%   |
| CTC                  | 1         | 0.53%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 3         | 1.56%   |
| Samsung Electronics LCD Monitor SDC416E 2880x1620 344x194mm 15.5-inch | 2         | 1.04%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 2         | 1.04%   |
| LG Display LCD Monitor LGD0353 1366x768 345x194mm 15.6-inch           | 2         | 1.04%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch               | 2         | 1.04%   |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch             | 2         | 1.04%   |
| Goldstar ULTRAGEAR GSM7765 2560x1440 697x392mm 31.5-inch              | 2         | 1.04%   |
| Goldstar HDR WQHD GSM7756 3440x1440 820x346mm 35.0-inch               | 2         | 1.04%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 2         | 1.04%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 2         | 1.04%   |
| Xiaomi Mi TV XMD009A 2880x1800 480x270mm 21.7-inch                    | 1         | 0.52%   |
| Wacom Cintiq 22HDT WAC1037 1920x1080 476x268mm 21.5-inch              | 1         | 0.52%   |
| ViewSonic LCD Monitor VX2276 Series 1920x1080                         | 1         | 0.52%   |
| ViewSonic LCD Monitor VA2448 SERIES 1920x1080                         | 1         | 0.52%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 0.52%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1         | 0.52%   |
| UGD LCD Monitor UGD1302 1920x1080 290x160mm 13.0-inch                 | 1         | 0.52%   |
| Toshiba TV TSB0206 1920x1080                                          | 1         | 0.52%   |
| Sony TV SNY8102 1360x768                                              | 1         | 0.52%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 382x215mm 17.3-inch               | 1         | 0.52%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 0.52%   |
| Sharp LQ125T1JW02 SHP142F 2560x1440 277x155mm 12.5-inch               | 1         | 0.52%   |
| Sharp LCD Monitor SHP14C4 1920x1080 344x194mm 15.5-inch               | 1         | 0.52%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 1         | 0.52%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 700x390mm 31.5-inch     | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM0578 1920x1080 476x268mm 21.5-inch  | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch   | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM0428 1680x1050 459x296mm 21.5-inch  | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM03F2 1680x1050                      | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM03F0 1680x1050 433x271mm 20.1-inch  | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 376x301mm 19.0-inch  | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM01AD 1600x1200 408x306mm 20.1-inch  | 1         | 0.52%   |
| Samsung Electronics SMS27A650 SAM082D 1920x1080 600x340mm 27.2-inch   | 1         | 0.52%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch    | 1         | 0.52%   |
| Samsung Electronics SMEX2220 SAM0686 1920x1080 477x268mm 21.5-inch    | 1         | 0.52%   |
| Samsung Electronics SM2333T SAM0736 1920x1080 477x268mm 21.5-inch     | 1         | 0.52%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch     | 1         | 0.52%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch     | 1         | 0.52%   |
| Samsung Electronics LCD Monitor U28D590 3840x2160                     | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 1         | 0.52%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 84        | 45.9%   |
| 1366x768 (WXGA)    | 28        | 15.3%   |
| 3840x2160 (4K)     | 10        | 5.46%   |
| 2560x1440 (QHD)    | 8         | 4.37%   |
| 1680x1050 (WSXGA+) | 8         | 4.37%   |
| 1280x1024 (SXGA)   | 8         | 4.37%   |
| 1920x1200 (WUXGA)  | 7         | 3.83%   |
| 3440x1440          | 5         | 2.73%   |
| 1600x900 (HD+)     | 5         | 2.73%   |
| 1280x800 (WXGA)    | 4         | 2.19%   |
| 2880x1620          | 2         | 1.09%   |
| 1440x900 (WXGA+)   | 2         | 1.09%   |
| 1360x768           | 2         | 1.09%   |
| 800x1280           | 1         | 0.55%   |
| 3200x1080          | 1         | 0.55%   |
| 2288x1287          | 1         | 0.55%   |
| 2256x1504          | 1         | 0.55%   |
| 2160x1440          | 1         | 0.55%   |
| 1920x540           | 1         | 0.55%   |
| 1920x1280          | 1         | 0.55%   |
| 1600x1200          | 1         | 0.55%   |
| 1024x768 (XGA)     | 1         | 0.55%   |
| Unknown            | 1         | 0.55%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 42        | 22.22%  |
| 27      | 18        | 9.52%   |
| 21      | 16        | 8.47%   |
| 14      | 15        | 7.94%   |
| 24      | 14        | 7.41%   |
| 13      | 14        | 7.41%   |
| 17      | 12        | 6.35%   |
| 23      | 9         | 4.76%   |
| Unknown | 7         | 3.7%    |
| 22      | 5         | 2.65%   |
| 18      | 5         | 2.65%   |
| 20      | 4         | 2.12%   |
| 19      | 4         | 2.12%   |
| 16      | 4         | 2.12%   |
| 12      | 4         | 2.12%   |
| 31      | 3         | 1.59%   |
| 35      | 2         | 1.06%   |
| 34      | 2         | 1.06%   |
| 142     | 1         | 0.53%   |
| 84      | 1         | 0.53%   |
| 74      | 1         | 0.53%   |
| 72      | 1         | 0.53%   |
| 52      | 1         | 0.53%   |
| 32      | 1         | 0.53%   |
| 11      | 1         | 0.53%   |
| 10      | 1         | 0.53%   |
| 7       | 1         | 0.53%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 72        | 38.3%   |
| 501-600        | 38        | 20.21%  |
| 401-500        | 32        | 17.02%  |
| 351-400        | 14        | 7.45%   |
| 201-300        | 10        | 5.32%   |
| Unknown        | 7         | 3.72%   |
| 601-700        | 4         | 2.13%   |
| 701-800        | 3         | 1.6%    |
| 1501-2000      | 3         | 1.6%    |
| 801-900        | 2         | 1.06%   |
| More than 2000 | 1         | 0.53%   |
| 1001-1500      | 1         | 0.53%   |
| 1-100          | 1         | 0.53%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 122       | 71.35%  |
| 16/10   | 22        | 12.87%  |
| 5/4     | 6         | 3.51%   |
| 3/2     | 5         | 2.92%   |
| Unknown | 5         | 2.92%   |
| 21/9    | 4         | 2.34%   |
| 6/5     | 2         | 1.17%   |
| 4/3     | 2         | 1.17%   |
| 32/9    | 1         | 0.58%   |
| 1.00    | 1         | 0.58%   |
| 0.67    | 1         | 0.58%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 44        | 23.53%  |
| 201-250        | 34        | 18.18%  |
| 81-90          | 26        | 13.9%   |
| 301-350        | 18        | 9.63%   |
| 151-200        | 11        | 5.88%   |
| 141-150        | 9         | 4.81%   |
| 351-500        | 8         | 4.28%   |
| 121-130        | 7         | 3.74%   |
| Unknown        | 7         | 3.74%   |
| 251-300        | 6         | 3.21%   |
| More than 1000 | 5         | 2.67%   |
| 61-70          | 4         | 2.14%   |
| 71-80          | 3         | 1.6%    |
| 51-60          | 2         | 1.07%   |
| 111-120        | 2         | 1.07%   |
| 1-40           | 1         | 0.53%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 65        | 35.14%  |
| 121-160       | 50        | 27.03%  |
| 101-120       | 47        | 25.41%  |
| 161-240       | 9         | 4.86%   |
| Unknown       | 7         | 3.78%   |
| 1-50          | 4         | 2.16%   |
| More than 240 | 3         | 1.62%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 141       | 77.05%  |
| 2     | 22        | 12.02%  |
| 0     | 16        | 8.74%   |
| 3     | 3         | 1.64%   |
| 4     | 1         | 0.55%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 99        | 36.53%  |
| Realtek Semiconductor    | 97        | 35.79%  |
| Qualcomm Atheros         | 18        | 6.64%   |
| Broadcom                 | 13        | 4.8%    |
| MediaTek                 | 8         | 2.95%   |
| Ralink Technology        | 5         | 1.85%   |
| Broadcom Limited         | 5         | 1.85%   |
| ASIX Electronics         | 5         | 1.85%   |
| Nvidia                   | 4         | 1.48%   |
| TP-Link                  | 3         | 1.11%   |
| Qualcomm                 | 2         | 0.74%   |
| Dell                     | 2         | 0.74%   |
| VIA Technologies         | 1         | 0.37%   |
| Sitecom Europe           | 1         | 0.37%   |
| Sierra Wireless          | 1         | 0.37%   |
| Ralink                   | 1         | 0.37%   |
| Micro Star International | 1         | 0.37%   |
| Mellanox Technologies    | 1         | 0.37%   |
| Marvell Technology Group | 1         | 0.37%   |
| Huawei Technologies      | 1         | 0.37%   |
| Hewlett-Packard          | 1         | 0.37%   |
| Chelsio Communications   | 1         | 0.37%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 63        | 19.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 12        | 3.68%   |
| Intel Wi-Fi 6 AX200                                                    | 10        | 3.07%   |
| Intel I211 Gigabit Network Connection                                  | 8         | 2.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 2.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 7         | 2.15%   |
| Realtek RTL8125 2.5GbE Controller                                      | 6         | 1.84%   |
| Intel Wireless 8265 / 8275                                             | 6         | 1.84%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 1.53%   |
| Ralink MT7601U Wireless Adapter                                        | 5         | 1.53%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 5         | 1.53%   |
| Intel Wireless 8260                                                    | 5         | 1.53%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 5         | 1.53%   |
| Intel 82574L Gigabit Network Connection                                | 5         | 1.53%   |
| Intel Wireless 7260                                                    | 4         | 1.23%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 4         | 1.23%   |
| Intel Ethernet Controller I225-V                                       | 4         | 1.23%   |
| Intel Ethernet Connection (2) I218-V                                   | 4         | 1.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 4         | 1.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 3         | 0.92%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 3         | 0.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 3         | 0.92%   |
| Nvidia MCP61 Ethernet                                                  | 3         | 0.92%   |
| Intel Wireless 7265                                                    | 3         | 0.92%   |
| Intel I350 Gigabit Network Connection                                  | 3         | 0.92%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 0.92%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3         | 0.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 3         | 0.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 3         | 0.92%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 3         | 0.92%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 0.92%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 2         | 0.61%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 2         | 0.61%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 0.61%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2         | 0.61%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                       | 2         | 0.61%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 2         | 0.61%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 2         | 0.61%   |
| Intel Wireless 3165                                                    | 2         | 0.61%   |
| Intel Wireless 3160                                                    | 2         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 68        | 51.52%  |
| Realtek Semiconductor    | 22        | 16.67%  |
| Qualcomm Atheros         | 13        | 9.85%   |
| MediaTek                 | 8         | 6.06%   |
| Ralink Technology        | 5         | 3.79%   |
| TP-Link                  | 3         | 2.27%   |
| Broadcom Limited         | 3         | 2.27%   |
| Broadcom                 | 3         | 2.27%   |
| Dell                     | 2         | 1.52%   |
| Sitecom Europe           | 1         | 0.76%   |
| Sierra Wireless          | 1         | 0.76%   |
| Ralink                   | 1         | 0.76%   |
| Qualcomm                 | 1         | 0.76%   |
| Micro Star International | 1         | 0.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 10        | 7.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 7         | 5.26%   |
| Intel Wireless 8265 / 8275                                    | 6         | 4.51%   |
| Ralink MT7601U Wireless Adapter                               | 5         | 3.76%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 5         | 3.76%   |
| Intel Wireless 8260                                           | 5         | 3.76%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]     | 5         | 3.76%   |
| Intel Wireless 7260                                           | 4         | 3.01%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]       | 4         | 3.01%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 4         | 3.01%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 3         | 2.26%   |
| Realtek RTL8188EE Wireless Network Adapter                    | 3         | 2.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 3         | 2.26%   |
| Intel Wireless 7265                                           | 3         | 2.26%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 3         | 2.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 3         | 2.26%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 3         | 2.26%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                       | 2         | 1.5%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter              | 2         | 1.5%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 2         | 1.5%    |
| Intel Wireless 3165                                           | 2         | 1.5%    |
| Intel Wireless 3160                                           | 2         | 1.5%    |
| Intel Wi-Fi 6 AX201                                           | 2         | 1.5%    |
| Intel Tiger Lake PCH CNVi WiFi                                | 2         | 1.5%    |
| Intel Centrino Ultimate-N 6300                                | 2         | 1.5%    |
| Broadcom Limited BCM43228 802.11a/b/g/n                       | 2         | 1.5%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 1         | 0.75%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                         | 1         | 0.75%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]    | 1         | 0.75%   |
| Sitecom Europe WL-113 rev 2 Wireless Network USB Adapter      | 1         | 0.75%   |
| Sierra Wireless EM7305                                        | 1         | 0.75%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 1         | 0.75%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller   | 1         | 0.75%   |
| Realtek RTL8723DE Wireless Network Adapter                    | 1         | 0.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 1         | 0.75%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter               | 1         | 0.75%   |
| Realtek RTL8191SEvB Wireless LAN Controller                   | 1         | 0.75%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 1         | 0.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 1         | 0.75%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                     | 1         | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 88        | 48.09%  |
| Intel                    | 59        | 32.24%  |
| Broadcom                 | 11        | 6.01%   |
| Qualcomm Atheros         | 8         | 4.37%   |
| ASIX Electronics         | 5         | 2.73%   |
| Nvidia                   | 4         | 2.19%   |
| Broadcom Limited         | 2         | 1.09%   |
| VIA Technologies         | 1         | 0.55%   |
| Qualcomm                 | 1         | 0.55%   |
| Mellanox Technologies    | 1         | 0.55%   |
| Marvell Technology Group | 1         | 0.55%   |
| Huawei Technologies      | 1         | 0.55%   |
| Chelsio Communications   | 1         | 0.55%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 63        | 32.81%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 12        | 6.25%   |
| Intel I211 Gigabit Network Connection                                  | 8         | 4.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 4.17%   |
| Realtek RTL8125 2.5GbE Controller                                      | 6         | 3.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 2.6%    |
| Intel 82574L Gigabit Network Connection                                | 5         | 2.6%    |
| Intel Ethernet Controller I225-V                                       | 4         | 2.08%   |
| Intel Ethernet Connection (2) I218-V                                   | 4         | 2.08%   |
| Nvidia MCP61 Ethernet                                                  | 3         | 1.56%   |
| Intel I350 Gigabit Network Connection                                  | 3         | 1.56%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 1.56%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3         | 1.56%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 1.56%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 2         | 1.04%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 1.04%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2         | 1.04%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 2         | 1.04%   |
| Intel Ethernet Connection I217-V                                       | 2         | 1.04%   |
| Intel Ethernet Connection (7) I219-V                                   | 2         | 1.04%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 1.04%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 1.04%   |
| Intel 82579V Gigabit Network Connection                                | 2         | 1.04%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 1.04%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 2         | 1.04%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 2         | 1.04%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 2         | 1.04%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                        | 2         | 1.04%   |
| VIA VT6105/VT6106S [Rhine-III]                                         | 1         | 0.52%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 1         | 0.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.52%   |
| Qualcomm Nokia G42 5G                                                  | 1         | 0.52%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.52%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.52%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                  | 1         | 0.52%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 1         | 0.52%   |
| Intel Ethernet Connection I218-V                                       | 1         | 0.52%   |
| Intel Ethernet Connection (5) I219-V                                   | 1         | 0.52%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 0.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 167       | 56.42%  |
| WiFi     | 128       | 43.24%  |
| Modem    | 1         | 0.34%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 97        | 53.01%  |
| WiFi     | 86        | 46.99%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 98        | 52.97%  |
| 1     | 66        | 35.68%  |
| 3     | 8         | 4.32%   |
| 0     | 6         | 3.24%   |
| 4     | 5         | 2.7%    |
| 5     | 2         | 1.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 160       | 86.02%  |
| Yes  | 26        | 13.98%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 59        | 50.86%  |
| Cambridge Silicon Radio         | 14        | 12.07%  |
| Realtek Semiconductor           | 12        | 10.34%  |
| Broadcom                        | 7         | 6.03%   |
| MediaTek                        | 6         | 5.17%   |
| Qualcomm Atheros Communications | 5         | 4.31%   |
| IMC Networks                    | 4         | 3.45%   |
| Micro Star International        | 2         | 1.72%   |
| Foxconn / Hon Hai               | 2         | 1.72%   |
| Apple                           | 2         | 1.72%   |
| USI                             | 1         | 0.86%   |
| TP-Link                         | 1         | 0.86%   |
| Toshiba                         | 1         | 0.86%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)  | 14        | 12.07%  |
| Intel Bluetooth wireless interface                   | 12        | 10.34%  |
| Intel Bluetooth Device                               | 11        | 9.48%   |
| Intel AX200 Bluetooth                                | 9         | 7.76%   |
| Intel AX201 Bluetooth                                | 8         | 6.9%    |
| MediaTek Wireless_Device                             | 6         | 5.17%   |
| Realtek  Bluetooth 4.2 Adapter                       | 5         | 4.31%   |
| Realtek Bluetooth Radio                              | 5         | 4.31%   |
| Intel AX210 Bluetooth                                | 5         | 4.31%   |
| Intel Wireless-AC 9260 Bluetooth Adapter             | 4         | 3.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)       | 4         | 3.45%   |
| Qualcomm Atheros  Bluetooth Device                   | 3         | 2.59%   |
| Intel Wireless-AC 3168 Bluetooth                     | 3         | 2.59%   |
| IMC Networks Wireless_Device                         | 3         | 2.59%   |
| Intel AX211 Bluetooth                                | 2         | 1.72%   |
| Broadcom BCM20702A0 Bluetooth 4.0                    | 2         | 1.72%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]           | 2         | 1.72%   |
| USI Bluetooth Device                                 | 1         | 0.86%   |
| TP-Link UB500 Adapter                                | 1         | 0.86%   |
| Toshiba Askey Bluetooth Module                       | 1         | 0.86%   |
| Realtek RTL8723B Bluetooth                           | 1         | 0.86%   |
| Realtek 802.11ac WLAN Adapter                        | 1         | 0.86%   |
| Qualcomm Atheros Dell Wireless 1802 Bluetooth 4.0 LE | 1         | 0.86%   |
| Qualcomm Atheros AR3011 Bluetooth                    | 1         | 0.86%   |
| Micro Star International Bluetooth Dongle            | 1         | 0.86%   |
| Micro Star International Bluetooth Device            | 1         | 0.86%   |
| Intel Centrino Bluetooth Wireless Transceiver        | 1         | 0.86%   |
| IMC Networks Bluetooth Radio                         | 1         | 0.86%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller      | 1         | 0.86%   |
| Foxconn / Hon Hai Bluetooth Device                   | 1         | 0.86%   |
| Broadcom HP Portable SoftSailing                     | 1         | 0.86%   |
| Broadcom BCM20702A0                                  | 1         | 0.86%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]     | 1         | 0.86%   |
| Apple Bluetooth USB Host Controller                  | 1         | 0.86%   |
| Apple Bluetooth HCI MacBookPro (HID mode)            | 1         | 0.86%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 111       | 45.12%  |
| AMD                      | 63        | 25.61%  |
| Nvidia                   | 44        | 17.89%  |
| Creative Labs            | 8         | 3.25%   |
| C-Media Electronics      | 5         | 2.03%   |
| Micro Star International | 3         | 1.22%   |
| Texas Instruments        | 2         | 0.81%   |
| ASUSTek Computer         | 2         | 0.81%   |
| VIA Technologies         | 1         | 0.41%   |
| RME                      | 1         | 0.41%   |
| M-Audio                  | 1         | 0.41%   |
| Kingston Technology      | 1         | 0.41%   |
| Holtek Semiconductor     | 1         | 0.41%   |
| Generalplus Technology   | 1         | 0.41%   |
| EGO SYStems              | 1         | 0.41%   |
| Creative Technology      | 1         | 0.41%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 24        | 7.77%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 16        | 5.18%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 15        | 4.85%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 12        | 3.88%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9         | 2.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8         | 2.59%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 2.59%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 7         | 2.27%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 1.94%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 6         | 1.94%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 6         | 1.94%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 1.94%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 5         | 1.62%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 1.62%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 1.62%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 1.62%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 5         | 1.62%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 5         | 1.62%   |
| AMD FCH Azalia Controller                                                                         | 5         | 1.62%   |
| Nvidia MCP61 High Definition Audio                                                                | 4         | 1.29%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 1.29%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.29%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 1.29%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 1.29%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.29%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 4         | 1.29%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.29%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.29%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus]   | 4         | 1.29%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 1.29%   |
| AMD Navi 31 HDMI/DP Audio                                                                         | 4         | 1.29%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.97%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 0.97%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.97%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.97%   |
| Nvidia Audio device                                                                               | 3         | 0.97%   |
| Micro Star International USB Audio                                                                | 3         | 0.97%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 0.97%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 0.97%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 3         | 0.97%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 33        | 18.23%  |
| Samsung Electronics | 30        | 16.57%  |
| Kingston            | 26        | 14.36%  |
| Corsair             | 18        | 9.94%   |
| Crucial             | 14        | 7.73%   |
| Unknown             | 11        | 6.08%   |
| Micron Technology   | 11        | 6.08%   |
| G.Skill             | 5         | 2.76%   |
| Team                | 4         | 2.21%   |
| A-DATA Technology   | 3         | 1.66%   |
| Unknown             | 3         | 1.66%   |
| Transcend           | 2         | 1.1%    |
| Smart               | 2         | 1.1%    |
| Ramaxel Technology  | 2         | 1.1%    |
| GOODRAM             | 2         | 1.1%    |
| AMD                 | 2         | 1.1%    |
| Strontium           | 1         | 0.55%   |
| Silicon Power       | 1         | 0.55%   |
| Patriot             | 1         | 0.55%   |
| Neo Forza           | 1         | 0.55%   |
| Nanya Technology    | 1         | 0.55%   |
| Innodisk            | 1         | 0.55%   |
| HPE                 | 1         | 0.55%   |
| Hewlett-Packard     | 1         | 0.55%   |
| GLOWAY              | 1         | 0.55%   |
| Essencore Limited   | 1         | 0.55%   |
| Elpida              | 1         | 0.55%   |
| Avant               | 1         | 0.55%   |
| A Force             | 1         | 0.55%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.5%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.5%    |
| Unknown                                                          | 3         | 1.5%    |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 2         | 1%      |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s               | 2         | 1%      |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 1%      |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 1%      |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 1%      |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 2         | 1%      |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 2         | 1%      |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM 4800MT/s               | 2         | 1%      |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s              | 2         | 1%      |
| Corsair RAM CMZ32GX3M4X1600C10 8GB DIMM DDR3 1600MT/s            | 2         | 1%      |
| Corsair RAM CMSX32GX4M2A2666C18 16GB SODIMM DDR4 2667MT/s        | 2         | 1%      |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 2         | 1%      |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                        | 1         | 0.5%    |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                         | 1         | 0.5%    |
| Unknown RAM Module 4096MB DIMM DDR3 65535MT/s                    | 1         | 0.5%    |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.5%    |
| Unknown RAM Module 2GB DIMM DDR2 533MT/s                         | 1         | 0.5%    |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                         | 1         | 0.5%    |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                       | 1         | 0.5%    |
| Unknown RAM Module 2048MB DIMM 667MT/s                           | 1         | 0.5%    |
| Unknown RAM Module 1024MB SODIMM SDRAM                           | 1         | 0.5%    |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                    | 1         | 0.5%    |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s                       | 1         | 0.5%    |
| Unknown RAM Module 1024MB DIMM 667MT/s                           | 1         | 0.5%    |
| Transcend RAM TS256MLQ72V6U 2GB DIMM DDR2 667MT/s                | 1         | 0.5%    |
| Transcend RAM JM1600KLN-8GK 4096MB DIMM DDR3 1600MT/s            | 1         | 0.5%    |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3733MT/s              | 1         | 0.5%    |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s              | 1         | 0.5%    |
| Strontium RAM SRT4G86U1-P9H 4096MB DIMM DDR3 1333MT/s            | 1         | 0.5%    |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s            | 1         | 0.5%    |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s              | 1         | 0.5%    |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s          | 1         | 0.5%    |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 0.5%    |
| SK hynix RAM Module 16GB SODIMM DDR4 2400MT/s                    | 1         | 0.5%    |
| SK hynix RAM HYMP512F72CP8N3-Y5 1024MB FB-DIMM DDR2 667MT/s      | 1         | 0.5%    |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s            | 1         | 0.5%    |
| SK hynix RAM HMT41GV7BMR4A-H9 8GB DIMM 1333MT/s                  | 1         | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 75        | 47.17%  |
| DDR3    | 54        | 33.96%  |
| DDR2    | 7         | 4.4%    |
| LPDDR3  | 5         | 3.14%   |
| SDRAM   | 4         | 2.52%   |
| DDR5    | 4         | 2.52%   |
| LPDDR5  | 3         | 1.89%   |
| LPDDR4  | 3         | 1.89%   |
| DDR     | 2         | 1.26%   |
| Unknown | 2         | 1.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 75        | 46.88%  |
| DIMM         | 75        | 46.88%  |
| Row Of Chips | 7         | 4.38%   |
| RIMM         | 1         | 0.63%   |
| FB-DIMM      | 1         | 0.63%   |
| Chip         | 1         | 0.63%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 72        | 40.91%  |
| 4096  | 45        | 25.57%  |
| 16384 | 28        | 15.91%  |
| 2048  | 15        | 8.52%   |
| 32768 | 10        | 5.68%   |
| 1024  | 6         | 3.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 37        | 21.26%  |
| 3200    | 24        | 13.79%  |
| 2667    | 17        | 9.77%   |
| 2400    | 14        | 8.05%   |
| 3600    | 10        | 5.75%   |
| 1333    | 10        | 5.75%   |
| 2133    | 8         | 4.6%    |
| 1867    | 5         | 2.87%   |
| 667     | 5         | 2.87%   |
| 4800    | 4         | 2.3%    |
| 3800    | 4         | 2.3%    |
| 1334    | 4         | 2.3%    |
| 533     | 3         | 1.72%   |
| Unknown | 3         | 1.72%   |
| 6400    | 2         | 1.15%   |
| 3733    | 2         | 1.15%   |
| 2800    | 2         | 1.15%   |
| 2666    | 2         | 1.15%   |
| 1866    | 2         | 1.15%   |
| 975     | 2         | 1.15%   |
| 65535   | 1         | 0.57%   |
| 4267    | 1         | 0.57%   |
| 4266    | 1         | 0.57%   |
| 4199    | 1         | 0.57%   |
| 3666    | 1         | 0.57%   |
| 3400    | 1         | 0.57%   |
| 3000    | 1         | 0.57%   |
| 2933    | 1         | 0.57%   |
| 2472    | 1         | 0.57%   |
| 2187    | 1         | 0.57%   |
| 2000    | 1         | 0.57%   |
| 1066    | 1         | 0.57%   |
| 800     | 1         | 0.57%   |
| 701     | 1         | 0.57%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 30%     |
| Brother Industries  | 3         | 30%     |
| QinHeng Electronics | 2         | 20%     |
| Dell                | 1         | 10%     |
| Canon               | 1         | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                        | Computers | Percent |
|------------------------------|-----------|---------|
| QinHeng CH340S               | 2         | 20%     |
| HP OfficeJet Pro 9010 series | 1         | 10%     |
| HP ENVY 4520 series          | 1         | 10%     |
| HP ENVY 4500 series          | 1         | 10%     |
| Dell 2330d Laser Printer     | 1         | 10%     |
| Canon LiDE 300               | 1         | 10%     |
| Brother Printer              | 1         | 10%     |
| Brother HL-L5102DW           | 1         | 10%     |
| Brother HL-L2320D series     | 1         | 10%     |

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
| Chicony Electronics                    | 23        | 23.71%  |
| Logitech                               | 13        | 13.4%   |
| Bison Electronics                      | 10        | 10.31%  |
| Realtek Semiconductor                  | 8         | 8.25%   |
| Microdia                               | 6         | 6.19%   |
| Sunplus Innovation Technology          | 4         | 4.12%   |
| IMC Networks                           | 4         | 4.12%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 4.12%   |
| Syntek                                 | 3         | 3.09%   |
| Sonix Technology                       | 3         | 3.09%   |
| Quanta                                 | 3         | 3.09%   |
| Luxvisions Innotech Limited            | 3         | 3.09%   |
| Lite-On Technology                     | 3         | 3.09%   |
| Samsung Electronics                    | 2         | 2.06%   |
| Acer                                   | 2         | 2.06%   |
| Z-Star Microelectronics                | 1         | 1.03%   |
| Silicon Motion                         | 1         | 1.03%   |
| Motorola PCS                           | 1         | 1.03%   |
| Microsoft                              | 1         | 1.03%   |
| Lenovo                                 | 1         | 1.03%   |
| Apple                                  | 1         | 1.03%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 5         | 5.15%   |
| Bison HD Webcam                                      | 4         | 4.12%   |
| Bison BisonCam,NB Pro                                | 4         | 4.12%   |
| Logitech Webcam C270                                 | 3         | 3.09%   |
| Syntek Integrated Camera                             | 2         | 2.06%   |
| Sunplus Integrated_Webcam_HD                         | 2         | 2.06%   |
| Sonix USB2.0 FHD UVC WebCam                          | 2         | 2.06%   |
| Samsung Galaxy series, misc. (MTP mode)              | 2         | 2.06%   |
| Realtek USB Camera                                   | 2         | 2.06%   |
| Quanta HP Webcam                                     | 2         | 2.06%   |
| Microdia Integrated_Webcam_HD                        | 2         | 2.06%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 2         | 2.06%   |
| Chicony Integrated Camera (1280x720@30)              | 2         | 2.06%   |
| Chicony HD User Facing                               | 2         | 2.06%   |
| Chicony FJ Camera                                    | 2         | 2.06%   |
| Acer Integrated Camera                               | 2         | 2.06%   |
| Z-Star Vimicro USB2.0 Camera                         | 1         | 1.03%   |
| Syntek USB2.0 Camera                                 | 1         | 1.03%   |
| Sunplus PC Camera                                    | 1         | 1.03%   |
| Sunplus Laptop_Integrated_Webcam_FHD                 | 1         | 1.03%   |
| Sonix USB2.0 HD UVC WebCam                           | 1         | 1.03%   |
| Silicon Motion Web Camera                            | 1         | 1.03%   |
| Realtek Laptop Camera                                | 1         | 1.03%   |
| Realtek Integrated_Webcam_HD                         | 1         | 1.03%   |
| Realtek Integrated Webcam                            | 1         | 1.03%   |
| Realtek Integrated Camera                            | 1         | 1.03%   |
| Realtek EasyCamera                                   | 1         | 1.03%   |
| Realtek Bluetooth Radio                              | 1         | 1.03%   |
| Quanta HP Wide Vision HD Camera                      | 1         | 1.03%   |
| Motorola PCS XT1033 [Moto G], PTP mode               | 1         | 1.03%   |
| Microsoft LifeCam HD-3000                            | 1         | 1.03%   |
| Microdia Laptop_Integrated_Webcam_2M                 | 1         | 1.03%   |
| Microdia Integrated Webcam                           | 1         | 1.03%   |
| Microdia Dell Integrated HD Webcam                   | 1         | 1.03%   |
| Microdia Camera                                      | 1         | 1.03%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.03%   |
| Logitech Webcam C310                                 | 1         | 1.03%   |
| Logitech Webcam C300                                 | 1         | 1.03%   |
| Logitech Webcam C170                                 | 1         | 1.03%   |
| Logitech QuickCam Pro 9000                           | 1         | 1.03%   |

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
| 0     | 110       | 58.2%   |
| 1     | 45        | 23.81%  |
| 2     | 20        | 10.58%  |
| 3     | 8         | 4.23%   |
| 4     | 5         | 2.65%   |
| 5     | 1         | 0.53%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 22        | 17.89%  |
| Fingerprint reader       | 21        | 17.07%  |
| Sound                    | 18        | 14.63%  |
| Net/wireless             | 14        | 11.38%  |
| Chipcard                 | 10        | 8.13%   |
| Communication controller | 9         | 7.32%   |
| Unassigned class         | 5         | 4.07%   |
| Multimedia controller    | 5         | 4.07%   |
| Card reader              | 4         | 3.25%   |
| Camera                   | 4         | 3.25%   |
| Bluetooth                | 4         | 3.25%   |
| Net/ethernet             | 2         | 1.63%   |
| Storage/raid             | 1         | 0.81%   |
| Storage/ide              | 1         | 0.81%   |
| Storage/ata              | 1         | 0.81%   |
| Storage                  | 1         | 0.81%   |
| Firewire controller      | 1         | 0.81%   |

