Kubuntu 22.04 - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for Kubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 245

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | 0PTTT9 A00                  | [7f2851fcf5](https://linux-hardware.org/?probe=7f2851fcf5) | Dec 31, 2022 |
| HP            | 8399                        | [204c8c0a3f](https://linux-hardware.org/?probe=204c8c0a3f) | Dec 29, 2022 |
| Acer          | Aspire X3960                | [f045d61192](https://linux-hardware.org/?probe=f045d61192) | Dec 29, 2022 |
| Acer          | Aspire X3960                | [75e053c90f](https://linux-hardware.org/?probe=75e053c90f) | Dec 29, 2022 |
| Dell          | 0KWVT8 A03                  | [9d2542cf36](https://linux-hardware.org/?probe=9d2542cf36) | Dec 27, 2022 |
| Dell          | 0KWVT8 A03                  | [f2998cdede](https://linux-hardware.org/?probe=f2998cdede) | Dec 27, 2022 |
| Gigabyte      | 970-GAMING                  | [4a2d0b56d6](https://linux-hardware.org/?probe=4a2d0b56d6) | Dec 27, 2022 |
| Gigabyte      | 970-GAMING                  | [9df04c213d](https://linux-hardware.org/?probe=9df04c213d) | Dec 26, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [8d9b11c617](https://linux-hardware.org/?probe=8d9b11c617) | Dec 25, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [d66772a936](https://linux-hardware.org/?probe=d66772a936) | Dec 25, 2022 |
| Gigabyte      | 970-GAMING                  | [ef0c06d132](https://linux-hardware.org/?probe=ef0c06d132) | Dec 25, 2022 |
| Gigabyte      | 970-GAMING                  | [9de3d146ff](https://linux-hardware.org/?probe=9de3d146ff) | Dec 25, 2022 |
| ASUSTek       | X99-DELUXE                  | [3d538213fc](https://linux-hardware.org/?probe=3d538213fc) | Dec 25, 2022 |
| BESSTAR Te... | HM90                        | [3672c73d5a](https://linux-hardware.org/?probe=3672c73d5a) | Dec 24, 2022 |
| ASRock        | X570 Steel Legend           | [7b79249b18](https://linux-hardware.org/?probe=7b79249b18) | Dec 23, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [841b610817](https://linux-hardware.org/?probe=841b610817) | Dec 23, 2022 |
| Gigabyte      | Z97M-DS3H                   | [dca79c9d6d](https://linux-hardware.org/?probe=dca79c9d6d) | Dec 21, 2022 |
| MSI           | X470 GAMING PLUS            | [44cdfa03bf](https://linux-hardware.org/?probe=44cdfa03bf) | Dec 19, 2022 |
| MSI           | B450M PRO-VDH MAX           | [d5d8eaf2b9](https://linux-hardware.org/?probe=d5d8eaf2b9) | Dec 19, 2022 |
| Dell          | 084J0R A00                  | [dabf78159d](https://linux-hardware.org/?probe=dabf78159d) | Dec 15, 2022 |
| Lenovo        | NOK                         | [01d1b7fdb7](https://linux-hardware.org/?probe=01d1b7fdb7) | Dec 15, 2022 |
| MSI           | A320M PRO-VD/S              | [9e9573c0c5](https://linux-hardware.org/?probe=9e9573c0c5) | Dec 14, 2022 |
| Lenovo        | ThinkCentre A70 7844H9G     | [aad5a91184](https://linux-hardware.org/?probe=aad5a91184) | Dec 14, 2022 |
| MSI           | A320M PRO-VD/S              | [c428800285](https://linux-hardware.org/?probe=c428800285) | Dec 14, 2022 |
| ASUSTek       | H170-PRO                    | [0a28fbd557](https://linux-hardware.org/?probe=0a28fbd557) | Dec 12, 2022 |
| Gigabyte      | B550M DS3H                  | [13434876df](https://linux-hardware.org/?probe=13434876df) | Dec 11, 2022 |
| ASRock        | B450M Pro4                  | [36ef5b0deb](https://linux-hardware.org/?probe=36ef5b0deb) | Dec 04, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [23f903a61d](https://linux-hardware.org/?probe=23f903a61d) | Dec 03, 2022 |
| Dell          | 084J0R A00                  | [57b5a73c5d](https://linux-hardware.org/?probe=57b5a73c5d) | Dec 01, 2022 |
| System76      | Thelio thelio-r1            | [76343aa234](https://linux-hardware.org/?probe=76343aa234) | Dec 01, 2022 |
| ASRock        | B75M-DGS                    | [ca277bb16c](https://linux-hardware.org/?probe=ca277bb16c) | Nov 30, 2022 |
| MSI           | Z370 GAMING PLUS            | [bd1c91dba9](https://linux-hardware.org/?probe=bd1c91dba9) | Nov 30, 2022 |
| ASRock        | A320M-HDV R4.0              | [3a64631617](https://linux-hardware.org/?probe=3a64631617) | Nov 30, 2022 |
| ASRock        | A320M-HDV R4.0              | [12492cb99a](https://linux-hardware.org/?probe=12492cb99a) | Nov 29, 2022 |
| Gigabyte      | H97-HD3                     | [7c2db201dc](https://linux-hardware.org/?probe=7c2db201dc) | Nov 24, 2022 |
| MSI           | B350 PC MATE                | [601fd47da1](https://linux-hardware.org/?probe=601fd47da1) | Nov 24, 2022 |
| Gigabyte      | H110M-S2H-CF                | [87c95f019e](https://linux-hardware.org/?probe=87c95f019e) | Nov 20, 2022 |
| Unknown       | Unknown                     | [554da2ef73](https://linux-hardware.org/?probe=554da2ef73) | Nov 18, 2022 |
| ASUSTek       | PRIME H510M-D               | [3491c5eef1](https://linux-hardware.org/?probe=3491c5eef1) | Nov 17, 2022 |
| ASRock        | B560M-ITX/ac                | [c8f725f9cd](https://linux-hardware.org/?probe=c8f725f9cd) | Nov 17, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | [8e4ab9c969](https://linux-hardware.org/?probe=8e4ab9c969) | Nov 16, 2022 |
| Gigabyte      | H97-HD3                     | [b99ae215e4](https://linux-hardware.org/?probe=b99ae215e4) | Nov 14, 2022 |
| Gigabyte      | BOLD E3032                  | [9d013ae9aa](https://linux-hardware.org/?probe=9d013ae9aa) | Nov 14, 2022 |
| Gigabyte      | B660M GAMING DDR4           | [d22c86a486](https://linux-hardware.org/?probe=d22c86a486) | Nov 14, 2022 |
| Gigabyte      | GA-MA790FX-DS5              | [63bba2efec](https://linux-hardware.org/?probe=63bba2efec) | Nov 14, 2022 |
| Supermicro    | X9DAL                       | [56d4bd9f26](https://linux-hardware.org/?probe=56d4bd9f26) | Nov 13, 2022 |
| Foxconn       | 2ADA                        | [4ddae3c3a0](https://linux-hardware.org/?probe=4ddae3c3a0) | Nov 13, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [733739e049](https://linux-hardware.org/?probe=733739e049) | Nov 12, 2022 |
| Dell          | 0HY9JP A00                  | [fed46e3161](https://linux-hardware.org/?probe=fed46e3161) | Nov 12, 2022 |
| ASRock        | B75M                        | [7da4910326](https://linux-hardware.org/?probe=7da4910326) | Nov 12, 2022 |
| ASRock        | X99 Extreme4                | [00da120cde](https://linux-hardware.org/?probe=00da120cde) | Nov 11, 2022 |
| Dell          | 0773VG A00                  | [2ffe6c18f7](https://linux-hardware.org/?probe=2ffe6c18f7) | Nov 10, 2022 |
| Gigabyte      | B660M D3H DDR4              | [64aed4564c](https://linux-hardware.org/?probe=64aed4564c) | Nov 07, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [8ef47e1adb](https://linux-hardware.org/?probe=8ef47e1adb) | Nov 06, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [40a3de202d](https://linux-hardware.org/?probe=40a3de202d) | Nov 03, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [db852ba394](https://linux-hardware.org/?probe=db852ba394) | Nov 03, 2022 |
| ASUSTek       | M5A78L-M LX V2              | [50bd7a7436](https://linux-hardware.org/?probe=50bd7a7436) | Nov 01, 2022 |
| Shuttle       | FH61R                       | [26f86947ef](https://linux-hardware.org/?probe=26f86947ef) | Oct 30, 2022 |
| ASRock        | H61M-VS                     | [9a48b2a679](https://linux-hardware.org/?probe=9a48b2a679) | Oct 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [ac3b0eaf36](https://linux-hardware.org/?probe=ac3b0eaf36) | Oct 28, 2022 |
| HP            | 844C                        | [7e994c50c9](https://linux-hardware.org/?probe=7e994c50c9) | Oct 27, 2022 |
| ASUSTek       | M5A78L-M LE                 | [6954f669c5](https://linux-hardware.org/?probe=6954f669c5) | Oct 27, 2022 |
| ASUSTek       | PRIME X570-P                | [7910e04e13](https://linux-hardware.org/?probe=7910e04e13) | Oct 25, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [bd3a8063b3](https://linux-hardware.org/?probe=bd3a8063b3) | Oct 25, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [285e8cd1a5](https://linux-hardware.org/?probe=285e8cd1a5) | Oct 25, 2022 |
| Gigabyte      | B365M D2V                   | [c852b8f3f7](https://linux-hardware.org/?probe=c852b8f3f7) | Oct 24, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [638c72b105](https://linux-hardware.org/?probe=638c72b105) | Oct 24, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | [ca0e86eb6b](https://linux-hardware.org/?probe=ca0e86eb6b) | Oct 22, 2022 |
| MSI           | A320M PRO-M2 V2             | [7524f39579](https://linux-hardware.org/?probe=7524f39579) | Oct 19, 2022 |
| MSI           | H110M PRO-D                 | [d0580b46f2](https://linux-hardware.org/?probe=d0580b46f2) | Oct 18, 2022 |
| Lenovo        | ThinkCentre A70 7844H9G     | [1b0e52eddb](https://linux-hardware.org/?probe=1b0e52eddb) | Oct 18, 2022 |
| JWIPC         | A320I S1                    | [44689a88d8](https://linux-hardware.org/?probe=44689a88d8) | Oct 16, 2022 |
| Gigabyte      | Z68XP-UD3                   | [b36220c65b](https://linux-hardware.org/?probe=b36220c65b) | Oct 13, 2022 |
| ASRock        | A320M-HDV R4.0              | [20eebb7b05](https://linux-hardware.org/?probe=20eebb7b05) | Oct 12, 2022 |
| Gigabyte      | P55-US3L                    | [59843156e8](https://linux-hardware.org/?probe=59843156e8) | Oct 11, 2022 |
| ASRock        | Z170 Extreme4               | [b88e8a8b49](https://linux-hardware.org/?probe=b88e8a8b49) | Oct 11, 2022 |
| Gigabyte      | Z370P D3-CF                 | [71c916389e](https://linux-hardware.org/?probe=71c916389e) | Oct 09, 2022 |
| Acer          | Aspire G7750                | [bd21d9c12b](https://linux-hardware.org/?probe=bd21d9c12b) | Oct 09, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | [691aa10e89](https://linux-hardware.org/?probe=691aa10e89) | Oct 09, 2022 |
| Apple         | Mac-F221BEC8                | [51442982cd](https://linux-hardware.org/?probe=51442982cd) | Oct 07, 2022 |
| ASUSTek       | PRIME B450M-K II            | [1bf20fe68c](https://linux-hardware.org/?probe=1bf20fe68c) | Oct 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [99ed468a82](https://linux-hardware.org/?probe=99ed468a82) | Oct 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [e8b8141f03](https://linux-hardware.org/?probe=e8b8141f03) | Oct 05, 2022 |
| Dell          | 042P49 A02                  | [1ba8422c66](https://linux-hardware.org/?probe=1ba8422c66) | Oct 04, 2022 |
| MSI           | B450I GAMING PLUS AC        | [e857a28ed2](https://linux-hardware.org/?probe=e857a28ed2) | Oct 04, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [bc03e42377](https://linux-hardware.org/?probe=bc03e42377) | Oct 03, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | [61d1e2102b](https://linux-hardware.org/?probe=61d1e2102b) | Oct 03, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | [f05b832b90](https://linux-hardware.org/?probe=f05b832b90) | Oct 01, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | [d638b38369](https://linux-hardware.org/?probe=d638b38369) | Sep 30, 2022 |
| Dell          | 0GY6Y8 A02                  | [dad71b5547](https://linux-hardware.org/?probe=dad71b5547) | Sep 28, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [19fe9ebfb6](https://linux-hardware.org/?probe=19fe9ebfb6) | Sep 27, 2022 |
| ASRock        | 990FX Extreme9              | [c7522b70ba](https://linux-hardware.org/?probe=c7522b70ba) | Sep 27, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [3e14df6c26](https://linux-hardware.org/?probe=3e14df6c26) | Sep 27, 2022 |
| Gigabyte      | X399 AORUS XTREME-CF        | [762ad6e460](https://linux-hardware.org/?probe=762ad6e460) | Sep 26, 2022 |
| MSI           | Z590-A PRO                  | [72bd6750e5](https://linux-hardware.org/?probe=72bd6750e5) | Sep 25, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [60635ca9bc](https://linux-hardware.org/?probe=60635ca9bc) | Sep 24, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [2a7c09d404](https://linux-hardware.org/?probe=2a7c09d404) | Sep 24, 2022 |
| Gigabyte      | X570 GAMING X               | [07f9a5063e](https://linux-hardware.org/?probe=07f9a5063e) | Sep 23, 2022 |
| Biostar       | TA75MH2                     | [e76fb13311](https://linux-hardware.org/?probe=e76fb13311) | Sep 23, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [384ab44e0a](https://linux-hardware.org/?probe=384ab44e0a) | Sep 23, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [24c7d626c8](https://linux-hardware.org/?probe=24c7d626c8) | Sep 23, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [f6e7ad269e](https://linux-hardware.org/?probe=f6e7ad269e) | Sep 22, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [256ff04106](https://linux-hardware.org/?probe=256ff04106) | Sep 20, 2022 |
| MSI           | Z390-A PRO                  | [9b0dd73d61](https://linux-hardware.org/?probe=9b0dd73d61) | Sep 20, 2022 |
| Supermicro    | SKAGIT09                    | [b7dcf8a06c](https://linux-hardware.org/?probe=b7dcf8a06c) | Sep 20, 2022 |
| Acer          | Aspire G7750                | [c54e28dc84](https://linux-hardware.org/?probe=c54e28dc84) | Sep 18, 2022 |
| Gigabyte      | B560M D3H                   | [515d75e6b7](https://linux-hardware.org/?probe=515d75e6b7) | Sep 17, 2022 |
| ASUSTek       | Z97-K                       | [3f362093da](https://linux-hardware.org/?probe=3f362093da) | Sep 16, 2022 |
| Gigabyte      | B450M DS3H-CF               | [ea2264656c](https://linux-hardware.org/?probe=ea2264656c) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [d79d03b7ef](https://linux-hardware.org/?probe=d79d03b7ef) | Sep 11, 2022 |
| ASRock        | H470M-HVS                   | [17e4855f90](https://linux-hardware.org/?probe=17e4855f90) | Sep 09, 2022 |
| Supermicro    | SKAGIT09                    | [d3f42d0c24](https://linux-hardware.org/?probe=d3f42d0c24) | Sep 08, 2022 |
| Gigabyte      | B450M DS3H-CF               | [557860ffbd](https://linux-hardware.org/?probe=557860ffbd) | Sep 07, 2022 |
| MSI           | B350 PC MATE                | [1f4f30c013](https://linux-hardware.org/?probe=1f4f30c013) | Sep 06, 2022 |
| MSI           | B450-A PRO MAX              | [0c89daf254](https://linux-hardware.org/?probe=0c89daf254) | Sep 03, 2022 |
| ASRock        | A320M-HDV                   | [5a9342d8e9](https://linux-hardware.org/?probe=5a9342d8e9) | Sep 03, 2022 |
| Dell          | 02YYK5 A00                  | [742579c33d](https://linux-hardware.org/?probe=742579c33d) | Sep 03, 2022 |
| OEM           | G41 775 ICH7 8712           | [4c9041cf15](https://linux-hardware.org/?probe=4c9041cf15) | Sep 03, 2022 |
| MSI           | 970 GAMING                  | [296c04b276](https://linux-hardware.org/?probe=296c04b276) | Sep 02, 2022 |
| MSI           | MAG B550M BAZOOKA           | [a1b5555512](https://linux-hardware.org/?probe=a1b5555512) | Sep 02, 2022 |
| Gigabyte      | B85M-HD3                    | [dcb5e7a20c](https://linux-hardware.org/?probe=dcb5e7a20c) | Aug 29, 2022 |
| Supermicro    | SKAGIT09                    | [3f4c6a4d48](https://linux-hardware.org/?probe=3f4c6a4d48) | Aug 29, 2022 |
| Pegatron      | 2AB6                        | [93af020634](https://linux-hardware.org/?probe=93af020634) | Aug 27, 2022 |
| ASRock        | B450M/ac R2.0               | [ede2f61f08](https://linux-hardware.org/?probe=ede2f61f08) | Aug 26, 2022 |
| MSI           | B450-A PRO                  | [36f10ad555](https://linux-hardware.org/?probe=36f10ad555) | Aug 24, 2022 |
| ASUSTek       | B85-PLUS                    | [1eba4b558d](https://linux-hardware.org/?probe=1eba4b558d) | Aug 23, 2022 |
| Gigabyte      | BOLD E3032                  | [4b70fe47a2](https://linux-hardware.org/?probe=4b70fe47a2) | Aug 23, 2022 |
| Gigabyte      | H410M S2 V2                 | [cb43b7a4cf](https://linux-hardware.org/?probe=cb43b7a4cf) | Aug 22, 2022 |
| Gigabyte      | H97-Gaming 3                | [c084ff3123](https://linux-hardware.org/?probe=c084ff3123) | Aug 22, 2022 |
| Supermicro    | SKAGIT09                    | [1ae2767db3](https://linux-hardware.org/?probe=1ae2767db3) | Aug 22, 2022 |
| MSI           | B350 PC MATE                | [e058dec94d](https://linux-hardware.org/?probe=e058dec94d) | Aug 19, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [dd98185972](https://linux-hardware.org/?probe=dd98185972) | Aug 16, 2022 |
| ASUSTek       | H170M-PLUS/BR               | [feb4e50ec5](https://linux-hardware.org/?probe=feb4e50ec5) | Aug 16, 2022 |
| Lenovo        | Bantry CRB SDK0J40700 WI... | [792eb4143f](https://linux-hardware.org/?probe=792eb4143f) | Aug 16, 2022 |
| MSI           | B350 PC MATE                | [646d091037](https://linux-hardware.org/?probe=646d091037) | Aug 15, 2022 |
| HP            | 805D                        | [54f4e0fdb0](https://linux-hardware.org/?probe=54f4e0fdb0) | Aug 14, 2022 |
| Dell          | 0C2XKD A01                  | [cfad241ca0](https://linux-hardware.org/?probe=cfad241ca0) | Aug 12, 2022 |
| Positivo      | POS-PARS760GCD POSITIVO     | [dc6e65929f](https://linux-hardware.org/?probe=dc6e65929f) | Aug 12, 2022 |
| HP            | 8459                        | [677ca01f4f](https://linux-hardware.org/?probe=677ca01f4f) | Aug 11, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [d2f7a86fd8](https://linux-hardware.org/?probe=d2f7a86fd8) | Aug 11, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [6eac3041ec](https://linux-hardware.org/?probe=6eac3041ec) | Aug 07, 2022 |
| MSI           | B550-A PRO                  | [fb01882d07](https://linux-hardware.org/?probe=fb01882d07) | Aug 06, 2022 |
| MSI           | Z97 GAMING 7                | [01cf6a0897](https://linux-hardware.org/?probe=01cf6a0897) | Aug 06, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | [1340311493](https://linux-hardware.org/?probe=1340311493) | Aug 06, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [6fa2b142e4](https://linux-hardware.org/?probe=6fa2b142e4) | Aug 06, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [e5e72c1264](https://linux-hardware.org/?probe=e5e72c1264) | Aug 05, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [d725206bff](https://linux-hardware.org/?probe=d725206bff) | Aug 04, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [42469385bc](https://linux-hardware.org/?probe=42469385bc) | Aug 04, 2022 |
| ASUSTek       | P8H67                       | [b1b842e547](https://linux-hardware.org/?probe=b1b842e547) | Jul 29, 2022 |
| ASUSTek       | GRYPHON Z87                 | [73b9d340d2](https://linux-hardware.org/?probe=73b9d340d2) | Jul 28, 2022 |
| ASUSTek       | PRIME X370-PRO              | [ee8688ecdb](https://linux-hardware.org/?probe=ee8688ecdb) | Jul 26, 2022 |
| ASRock        | Z270 Gaming K4              | [63612e20b4](https://linux-hardware.org/?probe=63612e20b4) | Jul 26, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [5658129aa4](https://linux-hardware.org/?probe=5658129aa4) | Jul 24, 2022 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | [ba1841221c](https://linux-hardware.org/?probe=ba1841221c) | Jul 24, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [021e469888](https://linux-hardware.org/?probe=021e469888) | Jul 23, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [ea90d78c53](https://linux-hardware.org/?probe=ea90d78c53) | Jul 23, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [6e6e65c711](https://linux-hardware.org/?probe=6e6e65c711) | Jul 23, 2022 |
| Gigabyte      | P35-DS3L                    | [4ae76fafc9](https://linux-hardware.org/?probe=4ae76fafc9) | Jul 22, 2022 |
| Shuttle       | NC01U V1.0                  | [827d6c81ae](https://linux-hardware.org/?probe=827d6c81ae) | Jul 22, 2022 |
| Shuttle       | NC01U V1.0                  | [fecfaf6008](https://linux-hardware.org/?probe=fecfaf6008) | Jul 21, 2022 |
| HP            | 18E9                        | [f15b2671b0](https://linux-hardware.org/?probe=f15b2671b0) | Jul 21, 2022 |
| ASRock        | B550 Extreme4               | [226924706f](https://linux-hardware.org/?probe=226924706f) | Jul 20, 2022 |
| Gigabyte      | P35-DS3L                    | [cabd591648](https://linux-hardware.org/?probe=cabd591648) | Jul 20, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | [0e3950303c](https://linux-hardware.org/?probe=0e3950303c) | Jul 18, 2022 |
| ASRock        | Z170 Extreme4               | [4f4b63a026](https://linux-hardware.org/?probe=4f4b63a026) | Jul 18, 2022 |
| Acer          | Predator PO3-620            | [f3e22c0e6d](https://linux-hardware.org/?probe=f3e22c0e6d) | Jul 18, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [01d595926f](https://linux-hardware.org/?probe=01d595926f) | Jul 15, 2022 |
| MSI           | X99A XPOWER GAMING TITAN... | [e764729eeb](https://linux-hardware.org/?probe=e764729eeb) | Jul 13, 2022 |
| ASRock        | Z170 Extreme4               | [7ecf3ad1b7](https://linux-hardware.org/?probe=7ecf3ad1b7) | Jul 13, 2022 |
| ASRock        | B550 Extreme4               | [6106db3d9a](https://linux-hardware.org/?probe=6106db3d9a) | Jul 12, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | [fafb6deae6](https://linux-hardware.org/?probe=fafb6deae6) | Jul 12, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | [d6531258d0](https://linux-hardware.org/?probe=d6531258d0) | Jul 11, 2022 |
| ASRock        | B550 Taichi                 | [61fe809791](https://linux-hardware.org/?probe=61fe809791) | Jul 10, 2022 |
| Gigabyte      | Z77-D3H                     | [f9e15346d3](https://linux-hardware.org/?probe=f9e15346d3) | Jul 10, 2022 |
| ASUSTek       | P9X79 PRO                   | [d7e1136386](https://linux-hardware.org/?probe=d7e1136386) | Jul 07, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | [7d5d5c1a7e](https://linux-hardware.org/?probe=7d5d5c1a7e) | Jul 02, 2022 |
| HP            | 8459                        | [f43fdff127](https://linux-hardware.org/?probe=f43fdff127) | Jul 01, 2022 |
| ASUSTek       | ET2400A                     | [8801791f80](https://linux-hardware.org/?probe=8801791f80) | Jul 01, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [33c8a42a4d](https://linux-hardware.org/?probe=33c8a42a4d) | Jun 29, 2022 |
| Gigabyte      | X570 AORUS PRO              | [757741fe0d](https://linux-hardware.org/?probe=757741fe0d) | Jun 29, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [efb8cff806](https://linux-hardware.org/?probe=efb8cff806) | Jun 28, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [a6555d107c](https://linux-hardware.org/?probe=a6555d107c) | Jun 27, 2022 |
| ASRock        | A320M Pro4                  | [e1918d8aab](https://linux-hardware.org/?probe=e1918d8aab) | Jun 25, 2022 |
| Huanan        | X99-F8 GAMING V5.0          | [2688876fc9](https://linux-hardware.org/?probe=2688876fc9) | Jun 25, 2022 |
| ASRock        | A320M Pro4                  | [f4f2e68e79](https://linux-hardware.org/?probe=f4f2e68e79) | Jun 24, 2022 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [04e6f0ee4a](https://linux-hardware.org/?probe=04e6f0ee4a) | Jun 24, 2022 |
| ABIT          | IP35 Pro                    | [a5f262c233](https://linux-hardware.org/?probe=a5f262c233) | Jun 23, 2022 |
| ASUSTek       | P8P67 LE                    | [8e1bc37281](https://linux-hardware.org/?probe=8e1bc37281) | Jun 19, 2022 |
| ASRock        | X570M Pro4                  | [bbb784f2df](https://linux-hardware.org/?probe=bbb784f2df) | Jun 18, 2022 |
| Dell          | 0YNVJG A01                  | [b75bebfda2](https://linux-hardware.org/?probe=b75bebfda2) | Jun 18, 2022 |
| ASUSTek       | X99-A/USB                   | [3ad17f6d78](https://linux-hardware.org/?probe=3ad17f6d78) | Jun 16, 2022 |
| ASUSTek       | P5QC                        | [b9a53514e1](https://linux-hardware.org/?probe=b9a53514e1) | Jun 16, 2022 |
| MSI           | Z270 GAMING M5              | [d5f742022e](https://linux-hardware.org/?probe=d5f742022e) | Jun 16, 2022 |
| MSI           | Z270 GAMING M5              | [6c352cf792](https://linux-hardware.org/?probe=6c352cf792) | Jun 16, 2022 |
| Gigabyte      | B450M DS3H-CF               | [2b307211cd](https://linux-hardware.org/?probe=2b307211cd) | Jun 14, 2022 |
| Dell          | 0KC9NP A01                  | [c573376df6](https://linux-hardware.org/?probe=c573376df6) | Jun 11, 2022 |
| Gigabyte      | Z270-HD3P-CF                | [317ae1383a](https://linux-hardware.org/?probe=317ae1383a) | Jun 10, 2022 |
| ASRock        | X570M Pro4                  | [4f6d06171b](https://linux-hardware.org/?probe=4f6d06171b) | Jun 10, 2022 |
| AZW           | Gemini J45                  | [f4d7238f95](https://linux-hardware.org/?probe=f4d7238f95) | Jun 08, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [15f48b1e64](https://linux-hardware.org/?probe=15f48b1e64) | Jun 08, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [9bc79127f3](https://linux-hardware.org/?probe=9bc79127f3) | Jun 06, 2022 |
| Dell          | 0Y2MRG A00                  | [11bba01e79](https://linux-hardware.org/?probe=11bba01e79) | Jun 06, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | [70f49afd95](https://linux-hardware.org/?probe=70f49afd95) | Jun 04, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | [95173b9d90](https://linux-hardware.org/?probe=95173b9d90) | Jun 04, 2022 |
| ASUSTek       | M5A78L LE                   | [8eda28a8d4](https://linux-hardware.org/?probe=8eda28a8d4) | May 30, 2022 |
| ASUSTek       | P7H55-M LE                  | [4f55b87c44](https://linux-hardware.org/?probe=4f55b87c44) | May 28, 2022 |
| Gigabyte      | B85M-D2V                    | [2bc6293c6a](https://linux-hardware.org/?probe=2bc6293c6a) | May 19, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [93b08c2d75](https://linux-hardware.org/?probe=93b08c2d75) | May 19, 2022 |
| ASRock        | B560M Pro4                  | [ba3b29db98](https://linux-hardware.org/?probe=ba3b29db98) | May 18, 2022 |
| Gigabyte      | B85M-D2V                    | [da9da96cda](https://linux-hardware.org/?probe=da9da96cda) | May 17, 2022 |
| ASUSTek       | M5A78L LE                   | [697a89162e](https://linux-hardware.org/?probe=697a89162e) | May 16, 2022 |
| Dell          | 0KJCC5 A00                  | [bb68e24835](https://linux-hardware.org/?probe=bb68e24835) | May 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [0ec606b729](https://linux-hardware.org/?probe=0ec606b729) | May 14, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [6fdf1cd28c](https://linux-hardware.org/?probe=6fdf1cd28c) | May 14, 2022 |
| MSI           | B450M PRO-M2                | [0bb720a248](https://linux-hardware.org/?probe=0bb720a248) | May 14, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [fb2a9c9ddf](https://linux-hardware.org/?probe=fb2a9c9ddf) | May 13, 2022 |
| MSI           | B450M MORTAR TITANIUM       | [b03899e10b](https://linux-hardware.org/?probe=b03899e10b) | May 13, 2022 |
| Lenovo        | SHARKBAY NOK                | [7923c29010](https://linux-hardware.org/?probe=7923c29010) | May 11, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | [76cc09b228](https://linux-hardware.org/?probe=76cc09b228) | May 10, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | [6500cb78c3](https://linux-hardware.org/?probe=6500cb78c3) | May 10, 2022 |
| HP            | 1998                        | [7f82a04d73](https://linux-hardware.org/?probe=7f82a04d73) | May 10, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [5f90cb38d2](https://linux-hardware.org/?probe=5f90cb38d2) | May 07, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [0b27354c9c](https://linux-hardware.org/?probe=0b27354c9c) | May 05, 2022 |
| Gigabyte      | Z370P D3-CF                 | [8a561e2442](https://linux-hardware.org/?probe=8a561e2442) | May 05, 2022 |
| Gigabyte      | X570 GAMING X               | [53a75b2d5c](https://linux-hardware.org/?probe=53a75b2d5c) | May 04, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [62f9f79f7c](https://linux-hardware.org/?probe=62f9f79f7c) | May 03, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [afce1937fe](https://linux-hardware.org/?probe=afce1937fe) | May 03, 2022 |
| ASUSTek       | P8B75-M                     | [dadde1bbc0](https://linux-hardware.org/?probe=dadde1bbc0) | May 02, 2022 |
| Supermicro    | X8ST3                       | [a94462f4b5](https://linux-hardware.org/?probe=a94462f4b5) | May 02, 2022 |
| ASUSTek       | PRIME B550M-K               | [92c09fc927](https://linux-hardware.org/?probe=92c09fc927) | Apr 30, 2022 |
| ASRock        | B550 Extreme4               | [7a90a198f5](https://linux-hardware.org/?probe=7a90a198f5) | Apr 30, 2022 |
| ASUSTek       | M5A78L LE                   | [9328531b5a](https://linux-hardware.org/?probe=9328531b5a) | Apr 30, 2022 |
| Lenovo        | 36C5 SDK0J40700 WIN 3258... | [d9ac32b17d](https://linux-hardware.org/?probe=d9ac32b17d) | Apr 30, 2022 |
| Biostar       | A68N-2100K                  | [db9760ae3a](https://linux-hardware.org/?probe=db9760ae3a) | Apr 27, 2022 |
| Biostar       | A68N-2100K                  | [87d629883f](https://linux-hardware.org/?probe=87d629883f) | Apr 27, 2022 |
| HP            | 0AACh                       | [f9e511945d](https://linux-hardware.org/?probe=f9e511945d) | Apr 25, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [4b41ff5fb9](https://linux-hardware.org/?probe=4b41ff5fb9) | Apr 24, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [3d513e3c6c](https://linux-hardware.org/?probe=3d513e3c6c) | Mar 24, 2022 |
| Dell          | 0K240Y A02                  | [b5783c7fa0](https://linux-hardware.org/?probe=b5783c7fa0) | Mar 03, 2022 |
| Gigabyte      | H410M S2H V3                | [e5da146c8e](https://linux-hardware.org/?probe=e5da146c8e) | Feb 27, 2022 |
| Gigabyte      | B550M DS3H                  | [21a8a676d1](https://linux-hardware.org/?probe=21a8a676d1) | Dec 28, 2021 |
| Gigabyte      | B550M DS3H                  | [61561f50ba](https://linux-hardware.org/?probe=61561f50ba) | Dec 28, 2021 |
| Gigabyte      | P35-DS3L                    | [e13fea24e4](https://linux-hardware.org/?probe=e13fea24e4) | Dec 27, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [1c12810a81](https://linux-hardware.org/?probe=1c12810a81) | Dec 06, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [acadafa3aa](https://linux-hardware.org/?probe=acadafa3aa) | Nov 30, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Desktops | Percent |
|----------------------------|----------|---------|
| 5.15.0-52-generic          | 19       | 9.5%    |
| 5.15.0-43-generic          | 16       | 8%      |
| 5.15.0-56-generic          | 14       | 7%      |
| 5.15.0-48-generic          | 14       | 7%      |
| 5.15.0-47-generic          | 12       | 6%      |
| 5.15.0-46-generic          | 12       | 6%      |
| 5.15.0-27-generic          | 12       | 6%      |
| 5.15.0-40-generic          | 11       | 5.5%    |
| 5.15.0-41-generic          | 10       | 5%      |
| 5.15.0-53-generic          | 9        | 4.5%    |
| 5.15.0-50-generic          | 7        | 3.5%    |
| 5.15.0-30-generic          | 6        | 3%      |
| 5.15.0-48-lowlatency       | 5        | 2.5%    |
| 5.15.0-25-generic          | 5        | 2.5%    |
| 5.15.0-56-lowlatency       | 4        | 2%      |
| 5.15.0-37-generic          | 4        | 2%      |
| 5.15.0-33-generic          | 4        | 2%      |
| 5.15.0-27-lowlatency       | 3        | 1.5%    |
| 5.15.0-52-lowlatency       | 2        | 1%      |
| 5.15.0-47-lowlatency       | 2        | 1%      |
| 5.15.0-43-lowlatency       | 2        | 1%      |
| 5.15.0-39-generic          | 2        | 1%      |
| 6.0.1-060001-generic       | 1        | 0.5%    |
| 5.4.0-122-generic          | 1        | 0.5%    |
| 5.19.12-xanmod1            | 1        | 0.5%    |
| 5.18.4-xanmod1             | 1        | 0.5%    |
| 5.18.4-vitodoc             | 1        | 0.5%    |
| 5.18.12-051812-generic     | 1        | 0.5%    |
| 5.18.10-051810-generic     | 1        | 0.5%    |
| 5.17.6-051706-generic      | 1        | 0.5%    |
| 5.17.14-xanmod1            | 1        | 0.5%    |
| 5.17.0-12.1-liquorix-amd64 | 1        | 0.5%    |
| 5.17.0-1021-oem            | 1        | 0.5%    |
| 5.17.0-1017-oem            | 1        | 0.5%    |
| 5.17.0-051700-generic      | 1        | 0.5%    |
| 5.16.0-051600rc3-generic   | 1        | 0.5%    |
| 5.15.13-051513-generic     | 1        | 0.5%    |
| 5.15.0-50-lowlatency       | 1        | 0.5%    |
| 5.15.0-46-lowlatency       | 1        | 0.5%    |
| 5.15.0-37-lowlatency       | 1        | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 173      | 91.53%  |
| 5.17.0  | 4        | 2.12%   |
| 5.18.4  | 2        | 1.06%   |
| 6.0.1   | 1        | 0.53%   |
| 5.4.0   | 1        | 0.53%   |
| 5.19.12 | 1        | 0.53%   |
| 5.18.12 | 1        | 0.53%   |
| 5.18.10 | 1        | 0.53%   |
| 5.17.6  | 1        | 0.53%   |
| 5.17.14 | 1        | 0.53%   |
| 5.16.0  | 1        | 0.53%   |
| 5.15.13 | 1        | 0.53%   |
| 5.13.0  | 1        | 0.53%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 174      | 92.06%  |
| 5.17    | 6        | 3.17%   |
| 5.18    | 4        | 2.12%   |
| 6.0     | 1        | 0.53%   |
| 5.4     | 1        | 0.53%   |
| 5.19    | 1        | 0.53%   |
| 5.16    | 1        | 0.53%   |
| 5.13    | 1        | 0.53%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 187      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| KDE5  | 186      | 99.47%  |
| GNOME | 1        | 0.53%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 180      | 96.26%  |
| Wayland | 4        | 2.14%   |
| Tty     | 2        | 1.07%   |
| Web     | 1        | 0.53%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 129      | 68.25%  |
| Unknown | 42       | 22.22%  |
| GDM3    | 13       | 6.88%   |
| LightDM | 5        | 2.65%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 84       | 44.92%  |
| fr_FR | 16       | 8.56%   |
| de_DE | 13       | 6.95%   |
| it_IT | 11       | 5.88%   |
| en_GB | 9        | 4.81%   |
| ru_RU | 8        | 4.28%   |
| en_AU | 8        | 4.28%   |
| pt_BR | 5        | 2.67%   |
| pl_PL | 3        | 1.6%    |
| en_CA | 3        | 1.6%    |
| nl_NL | 2        | 1.07%   |
| es_ES | 2        | 1.07%   |
| es_AR | 2        | 1.07%   |
| en_ZA | 2        | 1.07%   |
| en_PH | 2        | 1.07%   |
| en_IN | 2        | 1.07%   |
| cs_CZ | 2        | 1.07%   |
| C     | 2        | 1.07%   |
| sl_SI | 1        | 0.53%   |
| fr_BE | 1        | 0.53%   |
| fi_FI | 1        | 0.53%   |
| es_CO | 1        | 0.53%   |
| en_NZ | 1        | 0.53%   |
| en_IL | 1        | 0.53%   |
| en_AG | 1        | 0.53%   |
| el_GR | 1        | 0.53%   |
| de_LU | 1        | 0.53%   |
| de_CH | 1        | 0.53%   |
| de_AT | 1        | 0.53%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 113      | 60.11%  |
| EFI  | 75       | 39.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 164      | 87.7%   |
| Btrfs   | 12       | 6.42%   |
| Overlay | 9        | 4.81%   |
| Xfs     | 1        | 0.53%   |
| Ext3    | 1        | 0.53%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 103      | 53.93%  |
| Unknown | 72       | 37.7%   |
| MBR     | 16       | 8.38%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 160      | 84.21%  |
| Yes       | 30       | 15.79%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 110      | 58.82%  |
| Yes       | 77       | 41.18%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 49       | 26.2%   |
| Gigabyte Technology | 37       | 19.79%  |
| MSI                 | 28       | 14.97%  |
| ASRock              | 19       | 10.16%  |
| Dell                | 14       | 7.49%   |
| Lenovo              | 8        | 4.28%   |
| Hewlett-Packard     | 7        | 3.74%   |
| Supermicro          | 4        | 2.14%   |
| Acer                | 3        | 1.6%    |
| Shuttle             | 2        | 1.07%   |
| Fujitsu             | 2        | 1.07%   |
| Biostar             | 2        | 1.07%   |
| Apple               | 2        | 1.07%   |
| Positivo            | 1        | 0.53%   |
| Pegatron            | 1        | 0.53%   |
| OEM                 | 1        | 0.53%   |
| JWIPC               | 1        | 0.53%   |
| Huanan              | 1        | 0.53%   |
| Foxconn             | 1        | 0.53%   |
| BESSTAR Tech        | 1        | 0.53%   |
| AZW                 | 1        | 0.53%   |
| ABIT                | 1        | 0.53%   |
| Unknown             | 1        | 0.53%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| ASUS All Series                | 6        | 3.21%   |
| MSI MS-7B79                    | 4        | 2.14%   |
| ASUS ROG STRIX B550-F GAMING   | 4        | 2.14%   |
| Gigabyte B450M DS3H            | 3        | 1.6%    |
| Supermicro SKAGIT09            | 2        | 1.07%   |
| MSI MS-7C56                    | 2        | 1.07%   |
| MSI MS-7B86                    | 2        | 1.07%   |
| MSI MS-7B84                    | 2        | 1.07%   |
| Gigabyte X570 GAMING X         | 2        | 1.07%   |
| Gigabyte B450 I AORUS PRO WIFI | 2        | 1.07%   |
| Dell OptiPlex 7010             | 2        | 1.07%   |
| ASUS STRIX Z270E GAMING        | 2        | 1.07%   |
| ASUS ROG ZENITH EXTREME        | 2        | 1.07%   |
| ASUS ROG STRIX X570-E GAMING   | 2        | 1.07%   |
| ASUS ROG STRIX B550-I GAMING   | 2        | 1.07%   |
| Supermicro X9DAL               | 1        | 0.53%   |
| Supermicro X8ST3               | 1        | 0.53%   |
| Shuttle SH61R                  | 1        | 0.53%   |
| Shuttle NC01U                  | 1        | 0.53%   |
| Positivo POS-PARS760GCD        | 1        | 0.53%   |
| Pegatron p6740la               | 1        | 0.53%   |
| OEM G41 775 ICH7 8712          | 1        | 0.53%   |
| MSI MS-7D54                    | 1        | 0.53%   |
| MSI MS-7D09                    | 1        | 0.53%   |
| MSI MS-7C95                    | 1        | 0.53%   |
| MSI MS-7C80                    | 1        | 0.53%   |
| MSI MS-7C37                    | 1        | 0.53%   |
| MSI MS-7B98                    | 1        | 0.53%   |
| MSI MS-7B89                    | 1        | 0.53%   |
| MSI MS-7B61                    | 1        | 0.53%   |
| MSI MS-7B17                    | 1        | 0.53%   |
| MSI MS-7A78                    | 1        | 0.53%   |
| MSI MS-7A40                    | 1        | 0.53%   |
| MSI MS-7A38                    | 1        | 0.53%   |
| MSI MS-7A34                    | 1        | 0.53%   |
| MSI MS-7A21                    | 1        | 0.53%   |
| MSI MS-7996                    | 1        | 0.53%   |
| MSI MS-7916                    | 1        | 0.53%   |
| MSI MS-7693                    | 1        | 0.53%   |
| MSI A0000001                   | 1        | 0.53%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUS ROG                | 15       | 8.02%   |
| Dell OptiPlex           | 7        | 3.74%   |
| ASUS PRIME              | 7        | 3.74%   |
| Lenovo ThinkCentre      | 6        | 3.21%   |
| ASUS TUF                | 6        | 3.21%   |
| ASUS All                | 6        | 3.21%   |
| MSI MS-7B79             | 4        | 2.14%   |
| Gigabyte X570           | 4        | 2.14%   |
| Gigabyte B450M          | 3        | 1.6%    |
| Gigabyte B450           | 3        | 1.6%    |
| Dell Precision          | 3        | 1.6%    |
| ASUS M5A78L-M           | 3        | 1.6%    |
| Supermicro SKAGIT09     | 2        | 1.07%   |
| MSI MS-7C56             | 2        | 1.07%   |
| MSI MS-7B86             | 2        | 1.07%   |
| MSI MS-7B84             | 2        | 1.07%   |
| HP ProDesk              | 2        | 1.07%   |
| Gigabyte H410M          | 2        | 1.07%   |
| Gigabyte B660M          | 2        | 1.07%   |
| Fujitsu ESPRIMO         | 2        | 1.07%   |
| Dell XPS                | 2        | 1.07%   |
| Dell Inspiron           | 2        | 1.07%   |
| ASUS STRIX              | 2        | 1.07%   |
| ASRock B550             | 2        | 1.07%   |
| ASRock B450M            | 2        | 1.07%   |
| ASRock A320M-HDV        | 2        | 1.07%   |
| Acer Aspire             | 2        | 1.07%   |
| Supermicro X9DAL        | 1        | 0.53%   |
| Supermicro X8ST3        | 1        | 0.53%   |
| Shuttle SH61R           | 1        | 0.53%   |
| Shuttle NC01U           | 1        | 0.53%   |
| Positivo POS-PARS760GCD | 1        | 0.53%   |
| Pegatron p6740la        | 1        | 0.53%   |
| OEM G41                 | 1        | 0.53%   |
| MSI MS-7D54             | 1        | 0.53%   |
| MSI MS-7D09             | 1        | 0.53%   |
| MSI MS-7C95             | 1        | 0.53%   |
| MSI MS-7C80             | 1        | 0.53%   |
| MSI MS-7C37             | 1        | 0.53%   |
| MSI MS-7B98             | 1        | 0.53%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 30       | 16.04%  |
| 2019 | 25       | 13.37%  |
| 2020 | 23       | 12.3%   |
| 2021 | 15       | 8.02%   |
| 2014 | 14       | 7.49%   |
| 2012 | 12       | 6.42%   |
| 2017 | 11       | 5.88%   |
| 2013 | 11       | 5.88%   |
| 2016 | 10       | 5.35%   |
| 2015 | 10       | 5.35%   |
| 2011 | 9        | 4.81%   |
| 2010 | 7        | 3.74%   |
| 2022 | 3        | 1.6%    |
| 2007 | 3        | 1.6%    |
| 2009 | 2        | 1.07%   |
| 2008 | 2        | 1.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 187      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 184      | 98.4%   |
| Enabled  | 3        | 1.6%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 187      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 58       | 30.85%  |
| 32.01-64.0  | 55       | 29.26%  |
| 8.01-16.0   | 30       | 15.96%  |
| 4.01-8.0    | 15       | 7.98%   |
| 64.01-256.0 | 14       | 7.45%   |
| 3.01-4.0    | 11       | 5.85%   |
| 24.01-32.0  | 5        | 2.66%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 54       | 27.69%  |
| 4.01-8.0   | 44       | 22.56%  |
| 3.01-4.0   | 36       | 18.46%  |
| 1.01-2.0   | 33       | 16.92%  |
| 8.01-16.0  | 19       | 9.74%   |
| 16.01-24.0 | 5        | 2.56%   |
| 0.51-1.0   | 3        | 1.54%   |
| 32.01-64.0 | 1        | 0.51%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 57       | 30.16%  |
| 1      | 48       | 25.4%   |
| 3      | 41       | 21.69%  |
| 4      | 17       | 8.99%   |
| 5      | 13       | 6.88%   |
| 6      | 8        | 4.23%   |
| 7      | 2        | 1.06%   |
| 11     | 1        | 0.53%   |
| 9      | 1        | 0.53%   |
| 8      | 1        | 0.53%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 109      | 57.98%  |
| Yes       | 79       | 42.02%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 186      | 99.47%  |
| No        | 1        | 0.53%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 106      | 56.38%  |
| No        | 82       | 43.62%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 105      | 56.15%  |
| Yes       | 82       | 43.85%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 38       | 20.32%  |
| Germany      | 19       | 10.16%  |
| France       | 16       | 8.56%   |
| Italy        | 14       | 7.49%   |
| UK           | 10       | 5.35%   |
| Brazil       | 10       | 5.35%   |
| Russia       | 8        | 4.28%   |
| Poland       | 7        | 3.74%   |
| Australia    | 7        | 3.74%   |
| Netherlands  | 5        | 2.67%   |
| Spain        | 3        | 1.6%    |
| India        | 3        | 1.6%    |
| Canada       | 3        | 1.6%    |
| Argentina    | 3        | 1.6%    |
| Thailand     | 2        | 1.07%   |
| Switzerland  | 2        | 1.07%   |
| South Africa | 2        | 1.07%   |
| Slovenia     | 2        | 1.07%   |
| Serbia       | 2        | 1.07%   |
| Philippines  | 2        | 1.07%   |
| New Zealand  | 2        | 1.07%   |
| Finland      | 2        | 1.07%   |
| Czechia      | 2        | 1.07%   |
| Bulgaria     | 2        | 1.07%   |
| Belgium      | 2        | 1.07%   |
| Austria      | 2        | 1.07%   |
| Vietnam      | 1        | 0.53%   |
| Ukraine      | 1        | 0.53%   |
| Turkey       | 1        | 0.53%   |
| Sweden       | 1        | 0.53%   |
| Romania      | 1        | 0.53%   |
| Portugal     | 1        | 0.53%   |
| Malta        | 1        | 0.53%   |
| Malaysia     | 1        | 0.53%   |
| Luxembourg   | 1        | 0.53%   |
| Kazakhstan   | 1        | 0.53%   |
| Israel       | 1        | 0.53%   |
| Iran         | 1        | 0.53%   |
| Greece       | 1        | 0.53%   |
| Ecuador      | 1        | 0.53%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Munich         | 4        | 2.11%   |
| Rio de Janeiro | 3        | 1.58%   |
| Moscow         | 3        | 1.58%   |
| Milan          | 3        | 1.58%   |
| Berlin         | 3        | 1.58%   |
| Wroclaw        | 2        | 1.05%   |
| Washington     | 2        | 1.05%   |
| Vienna         | 2        | 1.05%   |
| Sydney         | 2        | 1.05%   |
| Prague         | 2        | 1.05%   |
| New York       | 2        | 1.05%   |
| Melbourne      | 2        | 1.05%   |
| London         | 2        | 1.05%   |
| Dallas         | 2        | 1.05%   |
| Canberra       | 2        | 1.05%   |
| Brasília      | 2        | 1.05%   |
| Bougival       | 2        | 1.05%   |
| Belgrade       | 2        | 1.05%   |
| Amsterdam      | 2        | 1.05%   |
| Zaandam        | 1        | 0.53%   |
| Yerevan        | 1        | 0.53%   |
| Wheaton        | 1        | 0.53%   |
| Whangarei      | 1        | 0.53%   |
| Wembley        | 1        | 0.53%   |
| Waukee         | 1        | 0.53%   |
| Vrhnika        | 1        | 0.53%   |
| Vladivostok    | 1        | 0.53%   |
| Vitebsk        | 1        | 0.53%   |
| Villa Nueva    | 1        | 0.53%   |
| Varna          | 1        | 0.53%   |
| Valencia       | 1        | 0.53%   |
| Ustron         | 1        | 0.53%   |
| Union City     | 1        | 0.53%   |
| Turku          | 1        | 0.53%   |
| Turin          | 1        | 0.53%   |
| Torun          | 1        | 0.53%   |
| Tholey         | 1        | 0.53%   |
| Therwil        | 1        | 0.53%   |
| Thai Nguyen    | 1        | 0.53%   |
| Templeton      | 1        | 0.53%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 67       | 106    | 17.45%  |
| WDC                         | 62       | 93     | 16.15%  |
| Seagate                     | 58       | 103    | 15.1%   |
| Kingston                    | 29       | 35     | 7.55%   |
| Toshiba                     | 23       | 27     | 5.99%   |
| SanDisk                     | 18       | 19     | 4.69%   |
| Crucial                     | 17       | 21     | 4.43%   |
| Hitachi                     | 16       | 16     | 4.17%   |
| Intel                       | 7        | 7      | 1.82%   |
| Phison                      | 5        | 5      | 1.3%    |
| Patriot                     | 5        | 7      | 1.3%    |
| HGST                        | 5        | 9      | 1.3%    |
| A-DATA Technology           | 5        | 6      | 1.3%    |
| Unknown                     | 4        | 5      | 1.04%   |
| China                       | 4        | 5      | 1.04%   |
| Transcend                   | 3        | 4      | 0.78%   |
| PNY                         | 3        | 4      | 0.78%   |
| Micron Technology           | 3        | 3      | 0.78%   |
| Lexar                       | 3        | 3      | 0.78%   |
| Intenso                     | 3        | 4      | 0.78%   |
| Phison Electronics          | 2        | 2      | 0.52%   |
| OCZ                         | 2        | 2      | 0.52%   |
| Micron/Crucial Technology   | 2        | 2      | 0.52%   |
| Maxtor                      | 2        | 2      | 0.52%   |
| KODAK                       | 2        | 2      | 0.52%   |
| Kingston Technology Company | 2        | 2      | 0.52%   |
| Emtec                       | 2        | 2      | 0.52%   |
| Corsair                     | 2        | 3      | 0.52%   |
| XPG                         | 1        | 1      | 0.26%   |
| Verbatim                    | 1        | 1      | 0.26%   |
| USB3.0                      | 1        | 1      | 0.26%   |
| T-FORCE                     | 1        | 1      | 0.26%   |
| Smartbuy                    | 1        | 1      | 0.26%   |
| SK hynix                    | 1        | 3      | 0.26%   |
| SABRENT                     | 1        | 1      | 0.26%   |
| Realtek Semiconductor       | 1        | 1      | 0.26%   |
| Plextor                     | 1        | 1      | 0.26%   |
| O2 Micro                    | 1        | 1      | 0.26%   |
| Mushkin                     | 1        | 2      | 0.26%   |
| KIOXIA-EXCERIA              | 1        | 2      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 8        | 1.77%   |
| Seagate ST4000DM004-2CV104 4TB                      | 7        | 1.55%   |
| Toshiba DT01ACA100 1TB                              | 5        | 1.11%   |
| SanDisk NVMe SSD Drive 500GB                        | 5        | 1.11%   |
| Samsung SSD 850 EVO 500GB                           | 5        | 1.11%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 5        | 1.11%   |
| Toshiba HDWD110 1TB                                 | 4        | 0.89%   |
| Samsung SSD 860 EVO 1TB                             | 4        | 0.89%   |
| Samsung NVMe SSD Drive 500GB                        | 4        | 0.89%   |
| Kingston SA2000M81000G 1TB                          | 4        | 0.89%   |
| WDC WD10EZEX-22MFCA0 1TB                            | 3        | 0.67%   |
| Samsung SSD 980 500GB                               | 3        | 0.67%   |
| Samsung SSD 980 1TB                                 | 3        | 0.67%   |
| Samsung SSD 870 EVO 1TB                             | 3        | 0.67%   |
| Samsung SSD 860 EVO 500GB                           | 3        | 0.67%   |
| Samsung SSD 840 PRO Series 128GB                    | 3        | 0.67%   |
| Samsung HD103SI 1TB                                 | 3        | 0.67%   |
| Hitachi HTS547550A9E384 500GB                       | 3        | 0.67%   |
| Crucial CT500MX500SSD1 500GB                        | 3        | 0.67%   |
| Crucial CT240BX500SSD1 240GB                        | 3        | 0.67%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 2        | 0.44%   |
| WDC WD5000AAKX-753CA1 500GB                         | 2        | 0.44%   |
| WDC WD5000AADS-00S9B0 500GB                         | 2        | 0.44%   |
| WDC WD40EZRZ-00GXCB0 4TB                            | 2        | 0.44%   |
| WDC WD40EFAX-68JH4N1 4TB                            | 2        | 0.44%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 2        | 0.44%   |
| WDC WD20EZRX-00D8PB0 2TB                            | 2        | 0.44%   |
| WDC WD20EZBX-00AYRA0 2TB                            | 2        | 0.44%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 2        | 0.44%   |
| Toshiba HDWD130 3TB                                 | 2        | 0.44%   |
| Toshiba HDWD120 2TB                                 | 2        | 0.44%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 2        | 0.44%   |
| Seagate ST4000VN008-2DR166 4TB                      | 2        | 0.44%   |
| Seagate ST31000524AS 1TB                            | 2        | 0.44%   |
| Seagate ST2000VM003-1CT164 2TB                      | 2        | 0.44%   |
| Seagate ST2000DM008-2FR102 2TB                      | 2        | 0.44%   |
| Seagate ST2000DM006-2DM164 2TB                      | 2        | 0.44%   |
| Seagate ST1000DM003-1SB102 1TB                      | 2        | 0.44%   |
| Seagate Expansion Desk 5TB                          | 2        | 0.44%   |
| Seagate Expansion 4TB                               | 2        | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 57       | 78     | 33.53%  |
| Seagate             | 54       | 94     | 31.76%  |
| Toshiba             | 20       | 23     | 11.76%  |
| Hitachi             | 16       | 16     | 9.41%   |
| Samsung Electronics | 13       | 14     | 7.65%   |
| HGST                | 5        | 9      | 2.94%   |
| USB3.0              | 1        | 1      | 0.59%   |
| Unknown             | 1        | 1      | 0.59%   |
| Maxtor              | 1        | 1      | 0.59%   |
| JMicron Technology  | 1        | 1      | 0.59%   |
| IET                 | 1        | 1      | 0.59%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 38       | 57     | 26.21%  |
| Kingston            | 23       | 25     | 15.86%  |
| Crucial             | 14       | 16     | 9.66%   |
| SanDisk             | 10       | 10     | 6.9%    |
| WDC                 | 8        | 10     | 5.52%   |
| Patriot             | 5        | 7      | 3.45%   |
| Intel               | 4        | 4      | 2.76%   |
| China               | 4        | 5      | 2.76%   |
| Toshiba             | 3        | 3      | 2.07%   |
| PNY                 | 3        | 4      | 2.07%   |
| Micron Technology   | 3        | 3      | 2.07%   |
| Lexar               | 3        | 3      | 2.07%   |
| A-DATA Technology   | 3        | 4      | 2.07%   |
| Transcend           | 2        | 2      | 1.38%   |
| OCZ                 | 2        | 2      | 1.38%   |
| KODAK               | 2        | 2      | 1.38%   |
| Intenso             | 2        | 2      | 1.38%   |
| Verbatim            | 1        | 1      | 0.69%   |
| Smartbuy            | 1        | 1      | 0.69%   |
| Plextor             | 1        | 1      | 0.69%   |
| Mushkin             | 1        | 2      | 0.69%   |
| Maxtor              | 1        | 1      | 0.69%   |
| KIOXIA-EXCERIA      | 1        | 2      | 0.69%   |
| KingFast            | 1        | 1      | 0.69%   |
| INNOVATION IT       | 1        | 1      | 0.69%   |
| INDMEM              | 1        | 1      | 0.69%   |
| Hewlett-Packard     | 1        | 1      | 0.69%   |
| GOODRAM             | 1        | 1      | 0.69%   |
| Drevo               | 1        | 1      | 0.69%   |
| Apple               | 1        | 1      | 0.69%   |
| Apacer              | 1        | 1      | 0.69%   |
| Aireye              | 1        | 1      | 0.69%   |
| ADATA SU            | 1        | 1      | 0.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 127      | 239    | 38.96%  |
| SSD     | 121      | 177    | 37.12%  |
| NVMe    | 69       | 104    | 21.17%  |
| Unknown | 8        | 10     | 2.45%   |
| MMC     | 1        | 1      | 0.31%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 171      | 395    | 65.52%  |
| NVMe | 68       | 103    | 26.05%  |
| SAS  | 21       | 32     | 8.05%   |
| MMC  | 1        | 1      | 0.38%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 124      | 193    | 44.77%  |
| 0.51-1.0   | 70       | 98     | 25.27%  |
| 1.01-2.0   | 34       | 43     | 12.27%  |
| 3.01-4.0   | 26       | 47     | 9.39%   |
| 4.01-10.0  | 12       | 22     | 4.33%   |
| 2.01-3.0   | 9        | 11     | 3.25%   |
| 10.01-20.0 | 2        | 2      | 0.72%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 37       | 19.27%  |
| 1001-2000      | 34       | 17.71%  |
| More than 3000 | 32       | 16.67%  |
| 2001-3000      | 27       | 14.06%  |
| 251-500        | 26       | 13.54%  |
| 101-250        | 24       | 12.5%   |
| 1-20           | 7        | 3.65%   |
| 51-100         | 4        | 2.08%   |
| Unknown        | 1        | 0.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 29       | 15.03%  |
| 251-500        | 28       | 14.51%  |
| 501-1000       | 28       | 14.51%  |
| 1-20           | 26       | 13.47%  |
| 1001-2000      | 20       | 10.36%  |
| 51-100         | 20       | 10.36%  |
| More than 3000 | 17       | 8.81%   |
| 21-50          | 15       | 7.77%   |
| 2001-3000      | 9        | 4.66%   |
| Unknown        | 1        | 0.52%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Desktops | Drives | Percent |
|------------------------------------------------|----------|--------|---------|
| WDC WD5000AVVS-63M8B0 500GB                    | 1        | 1      | 4%      |
| WDC WD10EZEX-22MFCA0 1TB                       | 1        | 1      | 4%      |
| WDC WD10EZEX-08M2NA0 1TB                       | 1        | 1      | 4%      |
| Seagate ST500LT012-9WS142 500GB                | 1        | 1      | 4%      |
| Seagate ST500LM012 HN-M500MBB 500GB            | 1        | 1      | 4%      |
| Seagate ST500DM002-1BD142 500GB                | 1        | 1      | 4%      |
| Seagate ST3160827AS 160GB                      | 1        | 1      | 4%      |
| Seagate ST31500341AS 1TB                       | 1        | 1      | 4%      |
| Seagate ST31000524AS 1TB                       | 1        | 2      | 4%      |
| Seagate ST1000DM003-1SB102 1TB                 | 1        | 1      | 4%      |
| Seagate ST1000DM003-1CH162 1TB                 | 1        | 1      | 4%      |
| SanDisk SDSSDX240GG25 240GB                    | 1        | 1      | 4%      |
| Samsung Electronics SSD 870 EVO 1TB            | 1        | 1      | 4%      |
| Samsung Electronics SSD 840 Series 250GB       | 1        | 1      | 4%      |
| Samsung Electronics SSD 840 Series 120GB       | 1        | 1      | 4%      |
| Samsung Electronics HM321HI 320GB              | 1        | 1      | 4%      |
| Samsung Electronics HD103SI 1TB                | 1        | 1      | 4%      |
| Micron Technology 5100_MTFDDAV960TCB 960GB SSD | 1        | 1      | 4%      |
| Hitachi HTS547550A9E384 500GB                  | 1        | 1      | 4%      |
| Hitachi HDS721010CLA630 1TB                    | 1        | 1      | 4%      |
| Hitachi HDP725050GLA360 500GB                  | 1        | 1      | 4%      |
| Hitachi HCT721010SLA360 1TB                    | 1        | 1      | 4%      |
| HGST HUH728080ALE600 8TB                       | 1        | 1      | 4%      |
| Crucial CT525MX300SSD1 528GB                   | 1        | 1      | 4%      |
| Crucial CT240M500SSD1 240GB                    | 1        | 1      | 4%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 7        | 9      | 29.17%  |
| Samsung Electronics | 5        | 5      | 20.83%  |
| Hitachi             | 4        | 4      | 16.67%  |
| WDC                 | 3        | 3      | 12.5%   |
| Crucial             | 2        | 2      | 8.33%   |
| SanDisk             | 1        | 1      | 4.17%   |
| Micron Technology   | 1        | 1      | 4.17%   |
| HGST                | 1        | 1      | 4.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 7        | 9      | 41.18%  |
| Hitachi             | 4        | 4      | 23.53%  |
| WDC                 | 3        | 3      | 17.65%  |
| Samsung Electronics | 2        | 2      | 11.76%  |
| HGST                | 1        | 1      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 16       | 19     | 69.57%  |
| SSD  | 7        | 7      | 30.43%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Samsung Electronics HD502IJ 500GB | 1        | 1      | 50%     |
| Hitachi HTS547550A9E384 500GB     | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 1        | 1      | 50%     |
| Hitachi             | 1        | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 102      | 258    | 46.36%  |
| Works    | 95       | 245    | 43.18%  |
| Malfunc  | 22       | 26     | 10%     |
| Failed   | 1        | 2      | 0.45%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 104      | 35.74%  |
| AMD                         | 83       | 28.52%  |
| Samsung Electronics         | 27       | 9.28%   |
| ASMedia Technology          | 13       | 4.47%   |
| SanDisk                     | 12       | 4.12%   |
| Kingston Technology Company | 10       | 3.44%   |
| Phison Electronics          | 9        | 3.09%   |
| Micron/Crucial Technology   | 6        | 2.06%   |
| JMicron Technology          | 6        | 2.06%   |
| ADATA Technology            | 4        | 1.37%   |
| Seagate Technology          | 3        | 1.03%   |
| Marvell Technology Group    | 2        | 0.69%   |
| LSI Logic / Symbios Logic   | 2        | 0.69%   |
| KIOXIA                      | 2        | 0.69%   |
| VIA Technologies            | 1        | 0.34%   |
| SK hynix                    | 1        | 0.34%   |
| Silicon Motion              | 1        | 0.34%   |
| Silicon Image               | 1        | 0.34%   |
| Realtek Semiconductor       | 1        | 0.34%   |
| O2 Micro                    | 1        | 0.34%   |
| INNOGRIT                    | 1        | 0.34%   |
| Broadcom / LSI              | 1        | 0.34%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 51       | 14.29%  |
| AMD 400 Series Chipset SATA Controller                                         | 25       | 7%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 15       | 4.2%    |
| AMD 500 Series Chipset SATA Controller                                         | 15       | 4.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 12       | 3.36%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 11       | 3.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 9        | 2.52%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 9        | 2.52%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 8        | 2.24%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 7        | 1.96%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 7        | 1.96%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 7        | 1.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 7        | 1.96%   |
| Samsung NVMe SSD Controller 980                                                | 6        | 1.68%   |
| Phison E12 NVMe Controller                                                     | 6        | 1.68%   |
| Kingston Company A2000 NVMe SSD                                                | 6        | 1.68%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 6        | 1.68%   |
| AMD FCH SATA Controller D                                                      | 6        | 1.68%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 5        | 1.4%    |
| Intel SATA Controller [RAID mode]                                              | 5        | 1.4%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 5        | 1.4%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 5        | 1.4%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 5        | 1.4%    |
| SanDisk Non-Volatile memory controller                                         | 4        | 1.12%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4        | 1.12%   |
| JMicron JMB363 SATA/IDE Controller                                             | 4        | 1.12%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4        | 1.12%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 4        | 1.12%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 4        | 1.12%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 4        | 1.12%   |
| AMD 300 Series Chipset SATA Controller                                         | 4        | 1.12%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3        | 0.84%   |
| Kingston Company Company Non-Volatile memory controller                        | 3        | 0.84%   |
| Intel SSD 660P Series                                                          | 3        | 0.84%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 3        | 0.84%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 3        | 0.84%   |
| AMD X399 Series Chipset SATA Controller                                        | 3        | 0.84%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 3        | 0.84%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2        | 0.56%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 2        | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 173      | 63.14%  |
| NVMe | 67       | 24.45%  |
| IDE  | 22       | 8.03%   |
| RAID | 11       | 4.01%   |
| SAS  | 1        | 0.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 104      | 55.61%  |
| AMD    | 83       | 44.39%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor             | 8        | 4.28%   |
| AMD Ryzen 5 2600X Six-Core Processor           | 5        | 2.67%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 4        | 2.14%   |
| Intel Core i5-10400F CPU @ 2.90GHz             | 4        | 2.14%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 4        | 2.14%   |
| Intel Core i7-6700 CPU @ 3.40GHz               | 3        | 1.6%    |
| Intel Core i7-4790K CPU @ 4.00GHz              | 3        | 1.6%    |
| AMD Ryzen 9 5950X 16-Core Processor            | 3        | 1.6%    |
| AMD Ryzen 7 5700G with Radeon Graphics         | 3        | 1.6%    |
| AMD Ryzen 7 3700X 8-Core Processor             | 3        | 1.6%    |
| AMD Ryzen 7 2700X Eight-Core Processor         | 3        | 1.6%    |
| AMD Ryzen 7 2700 Eight-Core Processor          | 3        | 1.6%    |
| AMD Ryzen 5 3600 6-Core Processor              | 3        | 1.6%    |
| Intel Pentium CPU G2020 @ 2.90GHz              | 2        | 1.07%   |
| Intel Core i7-7700K CPU @ 4.20GHz              | 2        | 1.07%   |
| Intel Core i7-5820K CPU @ 3.30GHz              | 2        | 1.07%   |
| Intel Core i7-3770K CPU @ 3.50GHz              | 2        | 1.07%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 2        | 1.07%   |
| Intel Core i5-9600K CPU @ 3.70GHz              | 2        | 1.07%   |
| Intel Core i5-8400 CPU @ 2.80GHz               | 2        | 1.07%   |
| Intel Core i5-7500 CPU @ 3.40GHz               | 2        | 1.07%   |
| Intel Core i5-4590 CPU @ 3.30GHz               | 2        | 1.07%   |
| Intel Core i3-4130 CPU @ 3.40GHz               | 2        | 1.07%   |
| Intel Core i3-10100F CPU @ 3.60GHz             | 2        | 1.07%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz           | 2        | 1.07%   |
| AMD Ryzen Threadripper 1950X 16-Core Processor | 2        | 1.07%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 2        | 1.07%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics     | 2        | 1.07%   |
| AMD Ryzen 7 5700X 8-Core Processor             | 2        | 1.07%   |
| AMD Ryzen 5 5600G with Radeon Graphics         | 2        | 1.07%   |
| AMD Ryzen 5 5600 6-Core Processor              | 2        | 1.07%   |
| AMD Ryzen 5 5500                               | 2        | 1.07%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics    | 2        | 1.07%   |
| AMD Ryzen 5 1600 Six-Core Processor            | 2        | 1.07%   |
| AMD FX-8350 Eight-Core Processor               | 2        | 1.07%   |
| Intel Xeon CPU X3440 @ 2.53GHz                 | 1        | 0.53%   |
| Intel Xeon CPU W3530 @ 2.80GHz                 | 1        | 0.53%   |
| Intel Xeon CPU E5-4627 v4 @ 2.60GHz            | 1        | 0.53%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz            | 1        | 0.53%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz            | 1        | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i7          | 32       | 17.11%  |
| AMD Ryzen 5            | 28       | 14.97%  |
| Intel Core i5          | 27       | 14.44%  |
| AMD Ryzen 7            | 18       | 9.63%   |
| AMD Ryzen 9            | 12       | 6.42%   |
| Intel Xeon             | 10       | 5.35%   |
| Intel Core i3          | 10       | 5.35%   |
| Other                  | 7        | 3.74%   |
| Intel Pentium          | 7        | 3.74%   |
| Intel Core 2 Duo       | 4        | 2.14%   |
| AMD Ryzen 3            | 4        | 2.14%   |
| AMD FX                 | 4        | 2.14%   |
| AMD Ryzen Threadripper | 3        | 1.6%    |
| Intel Core i9          | 2        | 1.07%   |
| Intel Core 2 Quad      | 2        | 1.07%   |
| Intel Celeron          | 2        | 1.07%   |
| AMD Ryzen 7 PRO        | 2        | 1.07%   |
| AMD Phenom II X2       | 2        | 1.07%   |
| AMD Opteron            | 2        | 1.07%   |
| Intel Pentium Gold     | 1        | 0.53%   |
| AMD Phenom II X6       | 1        | 0.53%   |
| AMD Phenom II X4       | 1        | 0.53%   |
| AMD E1                 | 1        | 0.53%   |
| AMD Athlon II X2       | 1        | 0.53%   |
| AMD Athlon 64 X2       | 1        | 0.53%   |
| AMD A8                 | 1        | 0.53%   |
| AMD A6                 | 1        | 0.53%   |
| AMD A4                 | 1        | 0.53%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 68       | 36.36%  |
| 6      | 46       | 24.6%   |
| 8      | 27       | 14.44%  |
| 2      | 27       | 14.44%  |
| 16     | 8        | 4.28%   |
| 12     | 7        | 3.74%   |
| 10     | 3        | 1.6%    |
| 1      | 1        | 0.53%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 187      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 132      | 70.59%  |
| 1      | 55       | 29.41%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 187      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 88       | 46.32%  |
| 0x306c3    | 9        | 4.74%   |
| 0x08701021 | 8        | 4.21%   |
| 0x0800820d | 7        | 3.68%   |
| 0x906e9    | 5        | 2.63%   |
| 0xa0653    | 4        | 2.11%   |
| 0x906ed    | 4        | 2.11%   |
| 0x306a9    | 4        | 2.11%   |
| 0x0a50000c | 4        | 2.11%   |
| 0x010000c8 | 4        | 2.11%   |
| 0x90672    | 3        | 1.58%   |
| 0x506e3    | 3        | 1.58%   |
| 0x206a7    | 3        | 1.58%   |
| 0x0a201205 | 3        | 1.58%   |
| 0x0a201016 | 3        | 1.58%   |
| 0xa0655    | 2        | 1.05%   |
| 0x906ea    | 2        | 1.05%   |
| 0x406f1    | 2        | 1.05%   |
| 0x306f2    | 2        | 1.05%   |
| 0x206d7    | 2        | 1.05%   |
| 0x1067a    | 2        | 1.05%   |
| 0x0a20120a | 2        | 1.05%   |
| 0x0a201204 | 2        | 1.05%   |
| 0x0a201009 | 2        | 1.05%   |
| 0x08001138 | 2        | 1.05%   |
| 0x806ea    | 1        | 0.53%   |
| 0x6fb      | 1        | 0.53%   |
| 0x306e4    | 1        | 0.53%   |
| 0x206d6    | 1        | 0.53%   |
| 0x106e5    | 1        | 0.53%   |
| 0x106a5    | 1        | 0.53%   |
| 0x0a50000d | 1        | 0.53%   |
| 0x0a201005 | 1        | 0.53%   |
| 0x08701013 | 1        | 0.53%   |
| 0x08600106 | 1        | 0.53%   |
| 0x08600103 | 1        | 0.53%   |
| 0x08001137 | 1        | 0.53%   |
| 0x08001136 | 1        | 0.53%   |
| 0x08001126 | 1        | 0.53%   |
| 0x07030106 | 1        | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 27       | 14.36%  |
| Haswell          | 24       | 12.77%  |
| KabyLake         | 19       | 10.11%  |
| Zen 2            | 16       | 8.51%   |
| Zen+             | 15       | 7.98%   |
| IvyBridge        | 14       | 7.45%   |
| Zen              | 9        | 4.79%   |
| SandyBridge      | 9        | 4.79%   |
| CometLake        | 8        | 4.26%   |
| Skylake          | 7        | 3.72%   |
| Piledriver       | 7        | 3.72%   |
| K10              | 6        | 3.19%   |
| Unknown          | 5        | 2.66%   |
| Penryn           | 4        | 2.13%   |
| Nehalem          | 4        | 2.13%   |
| Broadwell        | 3        | 1.6%    |
| Alderlake Hybrid | 3        | 1.6%    |
| Westmere         | 2        | 1.06%   |
| Core             | 2        | 1.06%   |
| Puma             | 1        | 0.53%   |
| K8 Hammer        | 1        | 0.53%   |
| Goldmont         | 1        | 0.53%   |
| Excavator        | 1        | 0.53%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 100      | 50%     |
| AMD                        | 65       | 32.5%   |
| Intel                      | 33       | 16.5%   |
| Matrox Electronics Systems | 2        | 1%      |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 11       | 5.5%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 9        | 4.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 8        | 4%      |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 5        | 2.5%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 4        | 2%      |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 2%      |
| Nvidia GP104 [GeForce GTX 1070]                                             | 4        | 2%      |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 2%      |
| Intel HD Graphics 630                                                       | 4        | 2%      |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 4        | 2%      |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 4        | 2%      |
| Nvidia TU117 [GeForce GTX 1650]                                             | 3        | 1.5%    |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 1.5%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 3        | 1.5%    |
| Intel HD Graphics 530                                                       | 3        | 1.5%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 1.5%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.5%    |
| AMD Renoir                                                                  | 3        | 1.5%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3        | 1.5%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 1.5%    |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 3        | 1.5%    |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 2        | 1%      |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 1%      |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 2        | 1%      |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 1%      |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 1%      |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 1%      |
| Nvidia GM107 [GeForce GTX 745]                                              | 2        | 1%      |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 1%      |
| Nvidia GK208B [GeForce GT 720]                                              | 2        | 1%      |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 2        | 1%      |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 1%      |
| Nvidia GA104 [GeForce RTX 3060]                                             | 2        | 1%      |
| Nvidia GA102 [GeForce RTX 3090]                                             | 2        | 1%      |
| Nvidia G92 [GeForce 9800 GT]                                                | 2        | 1%      |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 2        | 1%      |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 1%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 1%      |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 2        | 1%      |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                           | 2        | 1%      |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 96       | 51.34%  |
| 1 x AMD                  | 59       | 31.55%  |
| 1 x Intel                | 24       | 12.83%  |
| Intel + AMD              | 2        | 1.07%   |
| 2 x Nvidia               | 1        | 0.53%   |
| 2 x AMD                  | 1        | 0.53%   |
| Nvidia + Matrox          | 1        | 0.53%   |
| Intel + Nvidia           | 1        | 0.53%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.53%   |
| AMD + Matrox             | 1        | 0.53%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 106      | 56.68%  |
| Proprietary | 75       | 40.11%  |
| Unknown     | 6        | 3.21%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 85       | 44.5%   |
| 1.01-2.0   | 22       | 11.52%  |
| 7.01-8.0   | 21       | 10.99%  |
| 3.01-4.0   | 20       | 10.47%  |
| 0.51-1.0   | 14       | 7.33%   |
| 5.01-6.0   | 12       | 6.28%   |
| 8.01-16.0  | 7        | 3.66%   |
| 0.01-0.5   | 6        | 3.14%   |
| 16.01-24.0 | 2        | 1.05%   |
| 4.01-5.0   | 1        | 0.52%   |
| 2.01-3.0   | 1        | 0.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 43       | 19.37%  |
| Dell                 | 27       | 12.16%  |
| Goldstar             | 23       | 10.36%  |
| Hewlett-Packard      | 19       | 8.56%   |
| AOC                  | 13       | 5.86%   |
| Acer                 | 13       | 5.86%   |
| Philips              | 11       | 4.95%   |
| BenQ                 | 10       | 4.5%    |
| Ancor Communications | 9        | 4.05%   |
| Iiyama               | 8        | 3.6%    |
| Sony                 | 4        | 1.8%    |
| ViewSonic            | 3        | 1.35%   |
| NEC Computers        | 3        | 1.35%   |
| ASUSTek Computer     | 3        | 1.35%   |
| Vizio                | 2        | 0.9%    |
| LG Electronics       | 2        | 0.9%    |
| Idek Iiyama          | 2        | 0.9%    |
| Gigabyte Technology  | 2        | 0.9%    |
| Denver               | 2        | 0.9%    |
| Xiaomi               | 1        | 0.45%   |
| Vita                 | 1        | 0.45%   |
| Vestel Elektronik    | 1        | 0.45%   |
| Unknown              | 1        | 0.45%   |
| Sunplus              | 1        | 0.45%   |
| STD                  | 1        | 0.45%   |
| Sceptre Tech         | 1        | 0.45%   |
| RTK                  | 1        | 0.45%   |
| QUS                  | 1        | 0.45%   |
| Planar               | 1        | 0.45%   |
| PAR                  | 1        | 0.45%   |
| Panasonic            | 1        | 0.45%   |
| MVD                  | 1        | 0.45%   |
| MSI                  | 1        | 0.45%   |
| Medion               | 1        | 0.45%   |
| Lenovo               | 1        | 0.45%   |
| HKC                  | 1        | 0.45%   |
| Fujitsu Siemens      | 1        | 0.45%   |
| Envision Peripherals | 1        | 0.45%   |
| Eizo                 | 1        | 0.45%   |
| CLB                  | 1        | 0.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 3        | 1.28%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 3        | 1.28%   |
| AOC 27V2G5 AOC2702 1920x1080 598x336mm 27.0-inch                     | 3        | 1.28%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch  | 2        | 0.85%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch    | 2        | 0.85%   |
| Samsung Electronics LC27G5xT SAM7079 2560x1440 597x336mm 27.0-inch   | 2        | 0.85%   |
| Hewlett-Packard 24w HPN3431 1920x1080 527x296mm 23.8-inch            | 2        | 0.85%   |
| Hewlett-Packard 2311 HWP2939 1920x1080 509x286mm 23.0-inch           | 2        | 0.85%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch             | 2        | 0.85%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 2        | 0.85%   |
| Goldstar 22EA53 GSM59A5 1920x1080 477x268mm 21.5-inch                | 2        | 0.85%   |
| Dell S3422DW DELD102 3440x1440 797x334mm 34.0-inch                   | 2        | 0.85%   |
| Dell P2719H DEL4184 1920x1080 600x340mm 27.2-inch                    | 2        | 0.85%   |
| AOC Q3277 AOC3277 2560x1440 708x399mm 32.0-inch                      | 2        | 0.85%   |
| Acer VG240Y ACR06BF 1920x1080 527x296mm 23.8-inch                    | 2        | 0.85%   |
| Xiaomi Mi TV XMD00E2 3840x2160 800x450mm 36.1-inch                   | 1        | 0.43%   |
| Vizio M65Q6-J09 VIZ1039 3840x2160 1428x803mm 64.5-inch               | 1        | 0.43%   |
| Vizio E320-B0 VIZ1007 1366x768 697x392mm 31.5-inch                   | 1        | 0.43%   |
| Vita VT988 VIT03DC 1280x1024 376x301mm 19.0-inch                     | 1        | 0.43%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch           | 1        | 0.43%   |
| ViewSonic VX2439wm VSC3D24 1920x1080 520x290mm 23.4-inch             | 1        | 0.43%   |
| ViewSonic LCD Monitor VSCD62F 1920x1080 620x340mm 27.8-inch          | 1        | 0.43%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch | 1        | 0.43%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 1        | 0.43%   |
| Sunplus Monitor TV SPVFFFF 1920x1080 376x301mm 19.0-inch             | 1        | 0.43%   |
| STD LCD Monitor STD0001 1920x1080                                    | 1        | 0.43%   |
| Sony TV SNYEE01 1920x1080                                            | 1        | 0.43%   |
| Sony TV SNYC901 1920x1080                                            | 1        | 0.43%   |
| Sony TV SNY7702 1920x1080 708x398mm 32.0-inch                        | 1        | 0.43%   |
| Sony TV *02 SNY9403 1920x1080 1218x685mm 55.0-inch                   | 1        | 0.43%   |
| Sceptre Tech Sceptre E24 SPT099D 1920x1080 521x293mm 23.5-inch       | 1        | 0.43%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch    | 1        | 0.43%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch    | 1        | 0.43%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 607x345mm 27.5-inch    | 1        | 0.43%   |
| Samsung Electronics U28D590 SAM0B81 3840x2160 608x345mm 27.5-inch    | 1        | 0.43%   |
| Samsung Electronics U28D590 SAM0B80 3840x2160 607x345mm 27.5-inch    | 1        | 0.43%   |
| Samsung Electronics T19C300 SAM0A98 1366x768 410x230mm 18.5-inch     | 1        | 0.43%   |
| Samsung Electronics SyncMaster SAM05CC 1920x1080 530x300mm 24.0-inch | 1        | 0.43%   |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch | 1        | 0.43%   |
| Samsung Electronics SyncMaster SAM04E6 1920x1080 477x268mm 21.5-inch | 1        | 0.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 105      | 50.24%  |
| 3840x2160 (4K)     | 27       | 12.92%  |
| 2560x1440 (QHD)    | 15       | 7.18%   |
| 1680x1050 (WSXGA+) | 11       | 5.26%   |
| 1920x1200 (WUXGA)  | 10       | 4.78%   |
| 1280x1024 (SXGA)   | 10       | 4.78%   |
| 3440x1440          | 7        | 3.35%   |
| 2560x1080          | 4        | 1.91%   |
| 1600x900 (HD+)     | 4        | 1.91%   |
| 1366x768 (WXGA)    | 4        | 1.91%   |
| 1440x900 (WXGA+)   | 3        | 1.44%   |
| 3840x1080          | 2        | 0.96%   |
| 1280x720 (HD)      | 2        | 0.96%   |
| 3840x1200          | 1        | 0.48%   |
| 3600x1200          | 1        | 0.48%   |
| 2288x1287          | 1        | 0.48%   |
| 1360x768           | 1        | 0.48%   |
| Unknown            | 1        | 0.48%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 41       | 18.55%  |
| 27      | 36       | 16.29%  |
| 23      | 29       | 13.12%  |
| 21      | 22       | 9.95%   |
| 31      | 16       | 7.24%   |
| 19      | 12       | 5.43%   |
| 34      | 11       | 4.98%   |
| 22      | 9        | 4.07%   |
| Unknown | 7        | 3.17%   |
| 32      | 4        | 1.81%   |
| 18      | 4        | 1.81%   |
| 72      | 3        | 1.36%   |
| 46      | 3        | 1.36%   |
| 25      | 3        | 1.36%   |
| 20      | 3        | 1.36%   |
| 17      | 3        | 1.36%   |
| 36      | 2        | 0.9%    |
| 26      | 2        | 0.9%    |
| 142     | 1        | 0.45%   |
| 84      | 1        | 0.45%   |
| 69      | 1        | 0.45%   |
| 65      | 1        | 0.45%   |
| 60      | 1        | 0.45%   |
| 55      | 1        | 0.45%   |
| 54      | 1        | 0.45%   |
| 49      | 1        | 0.45%   |
| 48      | 1        | 0.45%   |
| 43      | 1        | 0.45%   |
| 40      | 1        | 0.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 87       | 42.23%  |
| 401-500        | 44       | 21.36%  |
| 601-700        | 24       | 11.65%  |
| 701-800        | 17       | 8.25%   |
| 1001-1500      | 9        | 4.37%   |
| 351-400        | 7        | 3.4%    |
| Unknown        | 7        | 3.4%    |
| 1501-2000      | 5        | 2.43%   |
| 301-350        | 3        | 1.46%   |
| More than 2000 | 1        | 0.49%   |
| 801-900        | 1        | 0.49%   |
| 901-1000       | 1        | 0.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 140      | 71.79%  |
| 16/10   | 24       | 12.31%  |
| 21/9    | 11       | 5.64%   |
| 5/4     | 10       | 5.13%   |
| Unknown | 5        | 2.56%   |
| 32/9    | 2        | 1.03%   |
| 3/2     | 1        | 0.51%   |
| 1.98    | 1        | 0.51%   |
| 1.00    | 1        | 0.51%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 75       | 35.38%  |
| 301-350        | 36       | 16.98%  |
| 351-500        | 31       | 14.62%  |
| 151-200        | 22       | 10.38%  |
| 251-300        | 16       | 7.55%   |
| More than 1000 | 10       | 4.72%   |
| 501-1000       | 9        | 4.25%   |
| Unknown        | 7        | 3.3%    |
| 141-150        | 6        | 2.83%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 121      | 62.69%  |
| 101-120 | 36       | 18.65%  |
| 121-160 | 13       | 6.74%   |
| 1-50    | 12       | 6.22%   |
| Unknown | 7        | 3.63%   |
| 161-240 | 4        | 2.07%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 122      | 64.89%  |
| 2     | 55       | 29.26%  |
| 0     | 7        | 3.72%   |
| 3     | 3        | 1.6%    |
| 4     | 1        | 0.53%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 119      | 41.46%  |
| Intel                           | 88       | 30.66%  |
| Qualcomm Atheros                | 16       | 5.57%   |
| Broadcom                        | 11       | 3.83%   |
| Ralink Technology               | 8        | 2.79%   |
| TP-Link                         | 6        | 2.09%   |
| Aquantia                        | 5        | 1.74%   |
| Ralink                          | 4        | 1.39%   |
| Huawei Technologies             | 4        | 1.39%   |
| MediaTek                        | 3        | 1.05%   |
| Xiaomi                          | 2        | 0.7%    |
| Samsung Electronics             | 2        | 0.7%    |
| ASUSTek Computer                | 2        | 0.7%    |
| ASIX Electronics                | 2        | 0.7%    |
| ZyXEL Communications            | 1        | 0.35%   |
| Wilocity                        | 1        | 0.35%   |
| VIA Technologies                | 1        | 0.35%   |
| U-Blox                          | 1        | 0.35%   |
| Qualcomm Atheros Communications | 1        | 0.35%   |
| NetGear                         | 1        | 0.35%   |
| Microsoft                       | 1        | 0.35%   |
| Mercucys                        | 1        | 0.35%   |
| Linksys                         | 1        | 0.35%   |
| LG Electronics                  | 1        | 0.35%   |
| Edimax Technology               | 1        | 0.35%   |
| DisplayLink                     | 1        | 0.35%   |
| D-Link System                   | 1        | 0.35%   |
| D-Link                          | 1        | 0.35%   |
| Bose                            | 1        | 0.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 93       | 27.93%  |
| Intel I211 Gigabit Network Connection                             | 15       | 4.5%    |
| Intel Wi-Fi 6 AX200                                               | 13       | 3.9%    |
| Intel Ethernet Controller I225-V                                  | 13       | 3.9%    |
| Realtek RTL8125 2.5GbE Controller                                 | 8        | 2.4%    |
| Intel Ethernet Connection I217-LM                                 | 7        | 2.1%    |
| Intel Ethernet Connection (2) I219-V                              | 7        | 2.1%    |
| Intel Ethernet Connection (7) I219-V                              | 6        | 1.8%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 6        | 1.8%    |
| Intel 82574L Gigabit Network Connection                           | 5        | 1.5%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4        | 1.2%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4        | 1.2%    |
| Realtek 802.11ac NIC                                              | 4        | 1.2%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4        | 1.2%    |
| Intel Ethernet Connection (2) I218-V                              | 4        | 1.2%    |
| Intel Ethernet Connection (14) I219-V                             | 4        | 1.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 1.2%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 4        | 1.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3        | 0.9%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 3        | 0.9%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 0.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3        | 0.9%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 3        | 0.9%    |
| Intel Wireless-AC 9260                                            | 3        | 0.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 0.9%    |
| Intel 82579V Gigabit Network Connection                           | 3        | 0.9%    |
| Huawei STK-L21                                                    | 3        | 0.9%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 0.6%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 2        | 0.6%    |
| TP-Link 802.11ac NIC                                              | 2        | 0.6%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.6%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.6%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 2        | 0.6%    |
| Ralink RT5370 Wireless Adapter                                    | 2        | 0.6%    |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2        | 0.6%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 2        | 0.6%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 2        | 0.6%    |
| Intel Wireless 8260                                               | 2        | 0.6%    |
| Intel Wireless 7260                                               | 2        | 0.6%    |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 34       | 30.09%  |
| Realtek Semiconductor           | 26       | 23.01%  |
| Broadcom                        | 11       | 9.73%   |
| Qualcomm Atheros                | 9        | 7.96%   |
| Ralink Technology               | 8        | 7.08%   |
| TP-Link                         | 6        | 5.31%   |
| Ralink                          | 4        | 3.54%   |
| MediaTek                        | 2        | 1.77%   |
| ASUSTek Computer                | 2        | 1.77%   |
| ZyXEL Communications            | 1        | 0.88%   |
| Wilocity                        | 1        | 0.88%   |
| Qualcomm Atheros Communications | 1        | 0.88%   |
| NetGear                         | 1        | 0.88%   |
| Microsoft                       | 1        | 0.88%   |
| Mercucys                        | 1        | 0.88%   |
| Linksys                         | 1        | 0.88%   |
| LG Electronics                  | 1        | 0.88%   |
| Edimax Technology               | 1        | 0.88%   |
| D-Link System                   | 1        | 0.88%   |
| D-Link                          | 1        | 0.88%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                        | 13       | 11.3%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter         | 6        | 5.22%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 4        | 3.48%   |
| Realtek 802.11ac NIC                                       | 4        | 3.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 3        | 2.61%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter            | 3        | 2.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 3        | 2.61%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter           | 3        | 2.61%   |
| Intel Wireless-AC 9260                                     | 3        | 2.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 3        | 2.61%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                     | 2        | 1.74%   |
| TP-Link 802.11ac NIC                                       | 2        | 1.74%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter   | 2        | 1.74%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                 | 2        | 1.74%   |
| Ralink RT5370 Wireless Adapter                             | 2        | 1.74%   |
| Ralink RT2870/RT3070 Wireless Adapter                      | 2        | 1.74%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                  | 2        | 1.74%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                    | 2        | 1.74%   |
| Intel Wireless 8260                                        | 2        | 1.74%   |
| Intel Wireless 7260                                        | 2        | 1.74%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 2        | 1.74%   |
| ZyXEL ZyAIR G-202 802.11bg                                 | 1        | 0.87%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter         | 1        | 0.87%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                | 1        | 0.87%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                 | 1        | 0.87%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 1        | 0.87%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1        | 0.87%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter    | 1        | 0.87%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 1        | 0.87%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)  | 1        | 0.87%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter      | 1        | 0.87%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                    | 1        | 0.87%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                 | 1        | 0.87%   |
| Realtek 802.11n WLAN Adapter                               | 1        | 0.87%   |
| Realtek 802.11ac+Bluetooth 5.0 Adapter                     | 1        | 0.87%   |
| Ralink RT5572 Wireless Adapter                             | 1        | 0.87%   |
| Ralink RT3572 Wireless Adapter                             | 1        | 0.87%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter          | 1        | 0.87%   |
| Ralink MT7601U Wireless Adapter                            | 1        | 0.87%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter     | 1        | 0.87%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 107      | 50.71%  |
| Intel                 | 77       | 36.49%  |
| Qualcomm Atheros      | 7        | 3.32%   |
| Aquantia              | 5        | 2.37%   |
| Huawei Technologies   | 4        | 1.9%    |
| Xiaomi                | 2        | 0.95%   |
| Samsung Electronics   | 2        | 0.95%   |
| Broadcom              | 2        | 0.95%   |
| ASIX Electronics      | 2        | 0.95%   |
| VIA Technologies      | 1        | 0.47%   |
| MediaTek              | 1        | 0.47%   |
| DisplayLink           | 1        | 0.47%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 93       | 43.06%  |
| Intel I211 Gigabit Network Connection                             | 15       | 6.94%   |
| Intel Ethernet Controller I225-V                                  | 13       | 6.02%   |
| Realtek RTL8125 2.5GbE Controller                                 | 8        | 3.7%    |
| Intel Ethernet Connection I217-LM                                 | 7        | 3.24%   |
| Intel Ethernet Connection (2) I219-V                              | 7        | 3.24%   |
| Intel Ethernet Connection (7) I219-V                              | 6        | 2.78%   |
| Intel 82574L Gigabit Network Connection                           | 5        | 2.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4        | 1.85%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4        | 1.85%   |
| Intel Ethernet Connection (2) I218-V                              | 4        | 1.85%   |
| Intel Ethernet Connection (14) I219-V                             | 4        | 1.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 1.85%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 4        | 1.85%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 1.39%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 1.39%   |
| Huawei STK-L21                                                    | 3        | 1.39%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 0.93%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.93%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.93%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2        | 0.93%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1        | 0.46%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.46%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.46%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1        | 0.46%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.46%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.46%   |
| MediaTek Infinix NOTE 11                                          | 1        | 0.46%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.46%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.46%   |
| Intel Ethernet Connection I218-LM                                 | 1        | 0.46%   |
| Intel Ethernet Connection I217-V                                  | 1        | 0.46%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.46%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.46%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 0.46%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.46%   |
| Huawei E353/E3131                                                 | 1        | 0.46%   |
| DisplayLink Dell Universal Dock D6000                             | 1        | 0.46%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1        | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 186      | 63.27%  |
| WiFi     | 106      | 36.05%  |
| Modem    | 2        | 0.68%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 137      | 71.73%  |
| WiFi     | 54       | 28.27%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 108      | 57.75%  |
| 2     | 66       | 35.29%  |
| 3     | 11       | 5.88%   |
| 6     | 1        | 0.53%   |
| 4     | 1        | 0.53%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 126      | 67.02%  |
| Yes  | 62       | 32.98%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 30       | 34.48%  |
| Cambridge Silicon Radio         | 26       | 29.89%  |
| Realtek Semiconductor           | 9        | 10.34%  |
| ASUSTek Computer                | 9        | 10.34%  |
| Broadcom                        | 4        | 4.6%    |
| MediaTek                        | 2        | 2.3%    |
| IMC Networks                    | 2        | 2.3%    |
| Edimax Technology               | 2        | 2.3%    |
| TP-Link                         | 1        | 1.15%   |
| Qualcomm Atheros Communications | 1        | 1.15%   |
| Apple                           | 1        | 1.15%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 26       | 29.89%  |
| Intel AX200 Bluetooth                                   | 13       | 14.94%  |
| Realtek Bluetooth Radio                                 | 6        | 6.9%    |
| Intel Bluetooth wireless interface                      | 5        | 5.75%   |
| ASUS Bluetooth Device                                   | 5        | 5.75%   |
| Realtek  Bluetooth 4.2 Adapter                          | 3        | 3.45%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 3        | 3.45%   |
| Intel Wireless-AC 3168 Bluetooth                        | 3        | 3.45%   |
| Broadcom BCM20702A0 Bluetooth 4.0                       | 3        | 3.45%   |
| MediaTek Wireless_Device                                | 2        | 2.3%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 2        | 2.3%    |
| Intel AX201 Bluetooth                                   | 2        | 2.3%    |
| IMC Networks Bluetooth Radio                            | 2        | 2.3%    |
| ASUS Qualcomm Bluetooth 4.1                             | 2        | 2.3%    |
| TP-Link UB500 Adapter                                   | 1        | 1.15%   |
| Qualcomm Atheros  Bluetooth Device                      | 1        | 1.15%   |
| Intel Bluetooth Device                                  | 1        | 1.15%   |
| Intel AX210 Bluetooth                                   | 1        | 1.15%   |
| Edimax Wi-Fi AC600 Bluetooth4.0 USB Adapter             | 1        | 1.15%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter | 1        | 1.15%   |
| Broadcom BCM43142 Bluetooth 4.0                         | 1        | 1.15%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE   | 1        | 1.15%   |
| ASUS Bluetooth Adapter                                  | 1        | 1.15%   |
| Apple Bluetooth USB Host Controller                     | 1        | 1.15%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| AMD                      | 106      | 28.27%  |
| Intel                    | 100      | 26.67%  |
| Nvidia                   | 97       | 25.87%  |
| C-Media Electronics      | 9        | 2.4%    |
| GN Netcom                | 5        | 1.33%   |
| JMTek                    | 4        | 1.07%   |
| Creative Labs            | 4        | 1.07%   |
| Texas Instruments        | 3        | 0.8%    |
| Kingston Technology      | 3        | 0.8%    |
| Generalplus Technology   | 3        | 0.8%    |
| Blue Microphones         | 3        | 0.8%    |
| VIA Technologies         | 2        | 0.53%   |
| Tenx Technology          | 2        | 0.53%   |
| Razer USA                | 2        | 0.53%   |
| M-Audio                  | 2        | 0.53%   |
| KORG                     | 2        | 0.53%   |
| BY EDIFIER               | 2        | 0.53%   |
| ASUSTek Computer         | 2        | 0.53%   |
| ZOOM                     | 1        | 0.27%   |
| Yamaha                   | 1        | 0.27%   |
| Veho                     | 1        | 0.27%   |
| Unknown (ABC)            | 1        | 0.27%   |
| Unknown                  | 1        | 0.27%   |
| TerraTec Electronic      | 1        | 0.27%   |
| SteelSeries ApS          | 1        | 0.27%   |
| Samson Technologies      | 1        | 0.27%   |
| Roland                   | 1        | 0.27%   |
| QinHeng Electronics      | 1        | 0.27%   |
| Philips (or NXP)         | 1        | 0.27%   |
| Nordic Semiconductor ASA | 1        | 0.27%   |
| Microdia                 | 1        | 0.27%   |
| Micro Star International | 1        | 0.27%   |
| Logitech                 | 1        | 0.27%   |
| Lenovo                   | 1        | 0.27%   |
| Hangzhou Worlde          | 1        | 0.27%   |
| Dell                     | 1        | 0.27%   |
| Corsair                  | 1        | 0.27%   |
| Bose                     | 1        | 0.27%   |
| BEHRINGER International  | 1        | 0.27%   |
| Barco Display Systems    | 1        | 0.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 32       | 7.49%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 20       | 4.68%   |
| Nvidia GP107GL High Definition Audio Controller                            | 13       | 3.04%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13       | 3.04%   |
| AMD Family 17h/19h HD Audio Controller                                     | 13       | 3.04%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11       | 2.58%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 10       | 2.34%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 10       | 2.34%   |
| Nvidia TU116 High Definition Audio Controller                              | 9        | 2.11%   |
| Intel 200 Series PCH HD Audio                                              | 9        | 2.11%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9        | 2.11%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 9        | 2.11%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 8        | 1.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8        | 1.87%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 8        | 1.87%   |
| Intel Cannon Lake PCH cAVS                                                 | 7        | 1.64%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 7        | 1.64%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7        | 1.64%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 7        | 1.64%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 7        | 1.64%   |
| Nvidia GP106 High Definition Audio Controller                              | 6        | 1.41%   |
| Nvidia GP104 High Definition Audio Controller                              | 6        | 1.41%   |
| Nvidia GA104 High Definition Audio Controller                              | 6        | 1.41%   |
| Nvidia TU104 HD Audio Controller                                           | 5        | 1.17%   |
| Nvidia High Definition Audio Controller                                    | 5        | 1.17%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 5        | 1.17%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 5        | 1.17%   |
| Nvidia GP108 High Definition Audio Controller                              | 4        | 0.94%   |
| Intel Comet Lake PCH cAVS                                                  | 4        | 0.94%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4        | 0.94%   |
| Intel Audio device                                                         | 4        | 0.94%   |
| Intel Alder Lake-S HD Audio Controller                                     | 4        | 0.94%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3        | 0.7%    |
| Nvidia TU102 High Definition Audio Controller                              | 3        | 0.7%    |
| Nvidia GM206 High Definition Audio Controller                              | 3        | 0.7%    |
| Nvidia GF116 High Definition Audio Controller                              | 3        | 0.7%    |
| Nvidia GA106 High Definition Audio Controller                              | 3        | 0.7%    |
| Kingston Technology HyperX 7.1 Audio                                       | 3        | 0.7%    |
| JMTek USB PnP Audio Device                                                 | 3        | 0.7%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 3        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 25       | 21.74%  |
| Corsair             | 23       | 20%     |
| G.Skill             | 15       | 13.04%  |
| Crucial             | 10       | 8.7%    |
| Unknown             | 7        | 6.09%   |
| SK hynix            | 7        | 6.09%   |
| Micron Technology   | 6        | 5.22%   |
| Team                | 4        | 3.48%   |
| Samsung Electronics | 4        | 3.48%   |
| Patriot             | 3        | 2.61%   |
| Ramaxel Technology  | 2        | 1.74%   |
| PNY                 | 2        | 1.74%   |
| Unknown             | 2        | 1.74%   |
| Unifosa             | 1        | 0.87%   |
| Lexar               | 1        | 0.87%   |
| Kingmax             | 1        | 0.87%   |
| Atermiter           | 1        | 0.87%   |
| AMD                 | 1        | 0.87%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 3        | 2.36%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 2        | 1.57%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s    | 2        | 1.57%   |
| Ramaxel RAM RMR5040ED58E9W1600 4GB DIMM DDR3 1600MT/s  | 2        | 1.57%   |
| Micron RAM 8ATF1G64AZ-2G6E1 8GB DIMM DDR4 2667MT/s     | 2        | 1.57%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s | 2        | 1.57%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s  | 2        | 1.57%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s  | 2        | 1.57%   |
| Corsair RAM CMK32GX4M2Z3600C18 16GB DIMM DDR4 3800MT/s | 2        | 1.57%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s  | 2        | 1.57%   |
| Unknown                                                | 2        | 1.57%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s              | 1        | 0.79%   |
| Unknown RAM Module 2GB DIMM SDRAM 1066MT/s             | 1        | 0.79%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 1        | 0.79%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s               | 1        | 0.79%   |
| Unknown RAM Module 16GB DIMM DDR4 2667MT/s             | 1        | 0.79%   |
| Unknown RAM 3600 C20 Series 32GB DIMM DDR4 3666MT/s    | 1        | 0.79%   |
| Unifosa RAM Module 2GB DIMM DDR3 1333MT/s              | 1        | 0.79%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s    | 1        | 0.79%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3000MT/s     | 1        | 0.79%   |
| SK hynix RAM Module 8GB DIMM DDR4 2133MT/s             | 1        | 0.79%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s   | 1        | 0.79%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1648MT/s   | 1        | 0.79%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s   | 1        | 0.79%   |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s   | 1        | 0.79%   |
| SK hynix RAM HMT351R7CFR8C-PB 4GB DIMM DDR3 1600MT/s   | 1        | 0.79%   |
| SK hynix RAM HMA81GU6MFR8N-UH 8GB DIMM DDR4 2400MT/s   | 1        | 0.79%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s    | 1        | 0.79%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s    | 1        | 0.79%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s    | 1        | 0.79%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s    | 1        | 0.79%   |
| PNY RAM 8GBF1X08QFHH38-135-K 8GB DIMM DDR4 3200MT/s    | 1        | 0.79%   |
| PNY RAM 8GBF1X08LIII43-12-K 8GB DIMM DDR4 2667MT/s     | 1        | 0.79%   |
| Patriot RAM PSD416G320081 16GB DIMM DDR4 3200MT/s      | 1        | 0.79%   |
| Patriot RAM PSD416G26662 16GB DIMM DDR4 2667MT/s       | 1        | 0.79%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s         | 1        | 0.79%   |
| Micron RAM Module 4GB DIMM DDR3 1866MT/s               | 1        | 0.79%   |
| Micron RAM 9ASF51272PZ-2G3B1 4GB RIMM DDR4 2400MT/s    | 1        | 0.79%   |
| Micron RAM 8JTF25664AZ-1G4M1 2GB DIMM DDR3 1333MT/s    | 1        | 0.79%   |
| Micron RAM 36ASF4G72PZ-2G3B1 32GB RIMM DDR4 2400MT/s   | 1        | 0.79%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 73       | 66.36%  |
| DDR3    | 27       | 24.55%  |
| SDRAM   | 4        | 3.64%   |
| DDR5    | 2        | 1.82%   |
| DDR2    | 2        | 1.82%   |
| Unknown | 2        | 1.82%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 105      | 96.33%  |
| SODIMM | 3        | 2.75%   |
| RIMM   | 1        | 0.92%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 51       | 43.97%  |
| 16384 | 32       | 27.59%  |
| 4096  | 18       | 15.52%  |
| 2048  | 8        | 6.9%    |
| 32768 | 6        | 5.17%   |
| 1024  | 1        | 0.86%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 17       | 14.41%  |
| 1600  | 17       | 14.41%  |
| 3600  | 12       | 10.17%  |
| 2667  | 11       | 9.32%   |
| 1333  | 11       | 9.32%   |
| 2400  | 6        | 5.08%   |
| 2133  | 6        | 5.08%   |
| 3000  | 5        | 4.24%   |
| 3800  | 4        | 3.39%   |
| 3066  | 3        | 2.54%   |
| 2666  | 3        | 2.54%   |
| 1066  | 3        | 2.54%   |
| 1867  | 2        | 1.69%   |
| 6000  | 1        | 0.85%   |
| 5800  | 1        | 0.85%   |
| 4000  | 1        | 0.85%   |
| 3866  | 1        | 0.85%   |
| 3666  | 1        | 0.85%   |
| 3467  | 1        | 0.85%   |
| 3466  | 1        | 0.85%   |
| 3400  | 1        | 0.85%   |
| 3334  | 1        | 0.85%   |
| 3333  | 1        | 0.85%   |
| 3266  | 1        | 0.85%   |
| 2933  | 1        | 0.85%   |
| 2800  | 1        | 0.85%   |
| 2448  | 1        | 0.85%   |
| 2134  | 1        | 0.85%   |
| 1866  | 1        | 0.85%   |
| 1648  | 1        | 0.85%   |
| 800   | 1        | 0.85%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 5        | 29.41%  |
| Seiko Epson         | 3        | 17.65%  |
| Samsung Electronics | 2        | 11.76%  |
| Canon               | 2        | 11.76%  |
| Xerox               | 1        | 5.88%   |
| Kyocera             | 1        | 5.88%   |
| Dymo-CoStar         | 1        | 5.88%   |
| Datamax-O'Neil      | 1        | 5.88%   |
| Brother Industries  | 1        | 5.88%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Samsung M2070 Series             | 2        | 11.76%  |
| Xerox Phaser 3140 and 3155       | 1        | 5.88%   |
| Seiko Epson XP-3100 Series       | 1        | 5.88%   |
| Seiko Epson L3110 Series         | 1        | 5.88%   |
| Seiko Epson L220 Series          | 1        | 5.88%   |
| Kyocera Mita FS-820              | 1        | 5.88%   |
| HP OfficeJet 5500 series         | 1        | 5.88%   |
| HP LaserJet 1022                 | 1        | 5.88%   |
| HP ENVY 4500 series              | 1        | 5.88%   |
| HP DeskJet D2300                 | 1        | 5.88%   |
| HP DeskJet 3630 series           | 1        | 5.88%   |
| Dymo-CoStar LabelWriter 450      | 1        | 5.88%   |
| Datamax-O'Neil Datamax E-4304    | 1        | 5.88%   |
| Canon PIXMA MX470 Series         | 1        | 5.88%   |
| Canon LaserShot LBP-1120 Printer | 1        | 5.88%   |
| Brother MFC-J460DW               | 1        | 5.88%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| Canon          | 5        | 71.43%  |
| Seiko Epson    | 1        | 14.29%  |
| Mustek Systems | 1        | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40      | 2        | 28.57%  |
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1        | 14.29%  |
| Mustek Systems ScanExpress A3 USB 1200 PRO  | 1        | 14.29%  |
| Canon CanoScan N670U/N676U/LiDE 20          | 1        | 14.29%  |
| Canon CanoScan LiDE 220                     | 1        | 14.29%  |
| Canon CanoScan LiDE 210                     | 1        | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 21       | 42%     |
| Microdia                      | 5        | 10%     |
| Sunplus Innovation Technology | 3        | 6%      |
| Microsoft                     | 3        | 6%      |
| KYE Systems (Mouse Systems)   | 2        | 4%      |
| Jieli Technology              | 2        | 4%      |
| Generalplus Technology        | 2        | 4%      |
| Alcor Micro                   | 2        | 4%      |
| YGTek                         | 1        | 2%      |
| Unknown                       | 1        | 2%      |
| Silicon Motion                | 1        | 2%      |
| Samsung Electronics           | 1        | 2%      |
| Realtek Semiconductor         | 1        | 2%      |
| IMC Networks                  | 1        | 2%      |
| Hewlett-Packard               | 1        | 2%      |
| Cubeternet                    | 1        | 2%      |
| Asuscom Network               | 1        | 2%      |
| ARC International             | 1        | 2%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Logitech Webcam C270                                                | 5        | 10%     |
| Logitech HD Pro Webcam C920                                         | 4        | 8%      |
| Logitech C920 PRO HD Webcam                                         | 3        | 6%      |
| Microdia Webcam Vitade AF                                           | 2        | 4%      |
| Microdia Integrated Camera                                          | 2        | 4%      |
| Logitech Webcam C170                                                | 2        | 4%      |
| Logitech HD Webcam C910                                             | 2        | 4%      |
| Jieli USB PHY 2.0                                                   | 2        | 4%      |
| Alcor Micro USB 2.0 PC Camera                                       | 2        | 4%      |
| YGTek Webcam                                                        | 1        | 2%      |
| Unknown HD camera                                                   | 1        | 2%      |
| Sunplus UC40M Audio                                                 | 1        | 2%      |
| Sunplus SPCA2281 Web Camera                                         | 1        | 2%      |
| Sunplus ezcap U3 capture-04                                         | 1        | 2%      |
| Silicon Motion 300k Pixel Camera                                    | 1        | 2%      |
| Samsung Galaxy A5 (MTP)                                             | 1        | 2%      |
| Realtek HK 2M CAM                                                   | 1        | 2%      |
| Microsoft MicrosoftÂ LifeCam Studio                                | 1        | 2%      |
| Microsoft LifeCam HD-3000                                           | 1        | 2%      |
| Microsoft LifeCam Cinema                                            | 1        | 2%      |
| Microdia PC Microscope camera                                       | 1        | 2%      |
| Logitech Webcam C310                                                | 1        | 2%      |
| Logitech QuickCam Pro for Notebooks                                 | 1        | 2%      |
| Logitech HD Webcam C615                                             | 1        | 2%      |
| Logitech C922 Pro Stream Webcam                                     | 1        | 2%      |
| Logitech BRIO Ultra HD Webcam                                       | 1        | 2%      |
| KYE Systems (Mouse Systems) PC-LM1E Camera                          | 1        | 2%      |
| KYE Systems (Mouse Systems) eFace 2025                              | 1        | 2%      |
| IMC Networks UVC VGA Webcam                                         | 1        | 2%      |
| HP Webcam 1300                                                      | 1        | 2%      |
| Generalplus 808 Camera #9 (web-cam mode)                            | 1        | 2%      |
| Generalplus 2K HD Camera                                            | 1        | 2%      |
| Cubeternet EtronTech CMOS based eSP570 WebCam [Onyx Titanium TC101] | 1        | 2%      |
| Asuscom Network Depstech webcam                                     | 1        | 2%      |
| ARC International Camera                                            | 1        | 2%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| Synaptics | 2        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Synaptics  WBDI Fingerprint Reader - USB 052 | 2        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| SCM Microsystems      | 1        | 25%     |
| OmniKey               | 1        | 25%     |
| Gemalto (was Gemplus) | 1        | 25%     |
| BIT4ID                | 1        | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| SCM Microsystems SCR331 SmartCard Reader          | 1        | 25%     |
| OmniKey CardMan 1021                              | 1        | 25%     |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1        | 25%     |
| BIT4ID miniLector EVO                             | 1        | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 152      | 80.85%  |
| 1     | 30       | 15.96%  |
| 2     | 5        | 2.66%   |
| 3     | 1        | 0.53%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 12       | 30%     |
| Graphics card            | 8        | 20%     |
| Unassigned class         | 7        | 17.5%   |
| Multimedia controller    | 3        | 7.5%    |
| Chipcard                 | 3        | 7.5%    |
| Fingerprint reader       | 2        | 5%      |
| Bluetooth                | 2        | 5%      |
| Sound                    | 1        | 2.5%    |
| Net/ethernet             | 1        | 2.5%    |
| Communication controller | 1        | 2.5%    |

