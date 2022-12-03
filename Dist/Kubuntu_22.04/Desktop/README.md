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

Total: 216

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| System76   | Thelio thelio-r1            | [76343aa234](https://linux-hardware.org/?probe=76343aa234) | Dec 01, 2022 |
| ASRock     | B75M-DGS                    | [ca277bb16c](https://linux-hardware.org/?probe=ca277bb16c) | Nov 30, 2022 |
| MSI        | Z370 GAMING PLUS            | [bd1c91dba9](https://linux-hardware.org/?probe=bd1c91dba9) | Nov 30, 2022 |
| ASRock     | A320M-HDV R4.0              | [3a64631617](https://linux-hardware.org/?probe=3a64631617) | Nov 30, 2022 |
| ASRock     | A320M-HDV R4.0              | [12492cb99a](https://linux-hardware.org/?probe=12492cb99a) | Nov 29, 2022 |
| Gigabyte   | H97-HD3                     | [7c2db201dc](https://linux-hardware.org/?probe=7c2db201dc) | Nov 24, 2022 |
| MSI        | B350 PC MATE                | [601fd47da1](https://linux-hardware.org/?probe=601fd47da1) | Nov 24, 2022 |
| Gigabyte   | H110M-S2H-CF                | [87c95f019e](https://linux-hardware.org/?probe=87c95f019e) | Nov 20, 2022 |
| Unknown    | Unknown                     | [554da2ef73](https://linux-hardware.org/?probe=554da2ef73) | Nov 18, 2022 |
| ASUSTek    | PRIME H510M-D               | [3491c5eef1](https://linux-hardware.org/?probe=3491c5eef1) | Nov 17, 2022 |
| ASRock     | B560M-ITX/ac                | [c8f725f9cd](https://linux-hardware.org/?probe=c8f725f9cd) | Nov 17, 2022 |
| ASUSTek    | STRIX Z270E GAMING          | [8e4ab9c969](https://linux-hardware.org/?probe=8e4ab9c969) | Nov 16, 2022 |
| Gigabyte   | H97-HD3                     | [b99ae215e4](https://linux-hardware.org/?probe=b99ae215e4) | Nov 14, 2022 |
| Gigabyte   | BOLD E3032                  | [9d013ae9aa](https://linux-hardware.org/?probe=9d013ae9aa) | Nov 14, 2022 |
| Gigabyte   | B660M GAMING DDR4           | [d22c86a486](https://linux-hardware.org/?probe=d22c86a486) | Nov 14, 2022 |
| Gigabyte   | GA-MA790FX-DS5              | [63bba2efec](https://linux-hardware.org/?probe=63bba2efec) | Nov 14, 2022 |
| Supermicro | X9DAL                       | [56d4bd9f26](https://linux-hardware.org/?probe=56d4bd9f26) | Nov 13, 2022 |
| Foxconn    | 2ADA                        | [4ddae3c3a0](https://linux-hardware.org/?probe=4ddae3c3a0) | Nov 13, 2022 |
| ASUSTek    | ROG STRIX X570-E GAMING     | [733739e049](https://linux-hardware.org/?probe=733739e049) | Nov 12, 2022 |
| Dell       | 0HY9JP A00                  | [fed46e3161](https://linux-hardware.org/?probe=fed46e3161) | Nov 12, 2022 |
| ASRock     | B75M                        | [7da4910326](https://linux-hardware.org/?probe=7da4910326) | Nov 12, 2022 |
| ASRock     | X99 Extreme4                | [00da120cde](https://linux-hardware.org/?probe=00da120cde) | Nov 11, 2022 |
| Dell       | 0773VG A00                  | [2ffe6c18f7](https://linux-hardware.org/?probe=2ffe6c18f7) | Nov 10, 2022 |
| Gigabyte   | B660M D3H DDR4              | [64aed4564c](https://linux-hardware.org/?probe=64aed4564c) | Nov 07, 2022 |
| ASUSTek    | ROG STRIX X570-I GAMING     | [8ef47e1adb](https://linux-hardware.org/?probe=8ef47e1adb) | Nov 06, 2022 |
| ASUSTek    | ROG STRIX B550-F GAMING     | [40a3de202d](https://linux-hardware.org/?probe=40a3de202d) | Nov 03, 2022 |
| MSI        | X470 GAMING PLUS MAX        | [db852ba394](https://linux-hardware.org/?probe=db852ba394) | Nov 03, 2022 |
| ASUSTek    | M5A78L-M LX V2              | [50bd7a7436](https://linux-hardware.org/?probe=50bd7a7436) | Nov 01, 2022 |
| Shuttle    | FH61R                       | [26f86947ef](https://linux-hardware.org/?probe=26f86947ef) | Oct 30, 2022 |
| ASRock     | H61M-VS                     | [9a48b2a679](https://linux-hardware.org/?probe=9a48b2a679) | Oct 28, 2022 |
| ASUSTek    | ROG CROSSHAIR VII HERO      | [ac3b0eaf36](https://linux-hardware.org/?probe=ac3b0eaf36) | Oct 28, 2022 |
| HP         | 844C                        | [7e994c50c9](https://linux-hardware.org/?probe=7e994c50c9) | Oct 27, 2022 |
| ASUSTek    | M5A78L-M LE                 | [6954f669c5](https://linux-hardware.org/?probe=6954f669c5) | Oct 27, 2022 |
| ASUSTek    | PRIME X570-P                | [7910e04e13](https://linux-hardware.org/?probe=7910e04e13) | Oct 25, 2022 |
| Lenovo     | SHARKBAY 31900058 STD       | [bd3a8063b3](https://linux-hardware.org/?probe=bd3a8063b3) | Oct 25, 2022 |
| ASUSTek    | P8H61-M LX3 PLUS R2.0       | [285e8cd1a5](https://linux-hardware.org/?probe=285e8cd1a5) | Oct 25, 2022 |
| Gigabyte   | B365M D2V                   | [c852b8f3f7](https://linux-hardware.org/?probe=c852b8f3f7) | Oct 24, 2022 |
| ASUSTek    | ROG STRIX B550-I GAMING     | [638c72b105](https://linux-hardware.org/?probe=638c72b105) | Oct 24, 2022 |
| ASUSTek    | STRIX Z270E GAMING          | [ca0e86eb6b](https://linux-hardware.org/?probe=ca0e86eb6b) | Oct 22, 2022 |
| MSI        | A320M PRO-M2 V2             | [7524f39579](https://linux-hardware.org/?probe=7524f39579) | Oct 19, 2022 |
| MSI        | H110M PRO-D                 | [d0580b46f2](https://linux-hardware.org/?probe=d0580b46f2) | Oct 18, 2022 |
| Lenovo     | ThinkCentre A70 7844H9G     | [1b0e52eddb](https://linux-hardware.org/?probe=1b0e52eddb) | Oct 18, 2022 |
| JWIPC      | A320I S1                    | [44689a88d8](https://linux-hardware.org/?probe=44689a88d8) | Oct 16, 2022 |
| Gigabyte   | Z68XP-UD3                   | [b36220c65b](https://linux-hardware.org/?probe=b36220c65b) | Oct 13, 2022 |
| ASRock     | A320M-HDV R4.0              | [20eebb7b05](https://linux-hardware.org/?probe=20eebb7b05) | Oct 12, 2022 |
| Gigabyte   | P55-US3L                    | [59843156e8](https://linux-hardware.org/?probe=59843156e8) | Oct 11, 2022 |
| ASRock     | Z170 Extreme4               | [b88e8a8b49](https://linux-hardware.org/?probe=b88e8a8b49) | Oct 11, 2022 |
| Gigabyte   | Z370P D3-CF                 | [71c916389e](https://linux-hardware.org/?probe=71c916389e) | Oct 09, 2022 |
| Acer       | Aspire G7750                | [bd21d9c12b](https://linux-hardware.org/?probe=bd21d9c12b) | Oct 09, 2022 |
| ASUSTek    | TUF X470-PLUS GAMING        | [691aa10e89](https://linux-hardware.org/?probe=691aa10e89) | Oct 09, 2022 |
| Apple      | Mac-F221BEC8                | [51442982cd](https://linux-hardware.org/?probe=51442982cd) | Oct 07, 2022 |
| ASUSTek    | PRIME B450M-K II            | [1bf20fe68c](https://linux-hardware.org/?probe=1bf20fe68c) | Oct 05, 2022 |
| ASUSTek    | TUF Gaming B550-PLUS        | [99ed468a82](https://linux-hardware.org/?probe=99ed468a82) | Oct 05, 2022 |
| ASUSTek    | TUF Gaming B550-PLUS        | [e8b8141f03](https://linux-hardware.org/?probe=e8b8141f03) | Oct 05, 2022 |
| Dell       | 042P49 A02                  | [1ba8422c66](https://linux-hardware.org/?probe=1ba8422c66) | Oct 04, 2022 |
| MSI        | B450I GAMING PLUS AC        | [e857a28ed2](https://linux-hardware.org/?probe=e857a28ed2) | Oct 04, 2022 |
| ASUSTek    | ROG STRIX B550-F GAMING     | [bc03e42377](https://linux-hardware.org/?probe=bc03e42377) | Oct 03, 2022 |
| Lenovo     | ThinkCentre M90p 5498A2U    | [61d1e2102b](https://linux-hardware.org/?probe=61d1e2102b) | Oct 03, 2022 |
| Lenovo     | ThinkCentre M90p 5498A2U    | [f05b832b90](https://linux-hardware.org/?probe=f05b832b90) | Oct 01, 2022 |
| Lenovo     | ThinkCentre M90p 5498A2U    | [d638b38369](https://linux-hardware.org/?probe=d638b38369) | Sep 30, 2022 |
| Dell       | 0GY6Y8 A02                  | [dad71b5547](https://linux-hardware.org/?probe=dad71b5547) | Sep 28, 2022 |
| Gigabyte   | B450 I AORUS PRO WIFI-CF    | [19fe9ebfb6](https://linux-hardware.org/?probe=19fe9ebfb6) | Sep 27, 2022 |
| ASRock     | 990FX Extreme9              | [c7522b70ba](https://linux-hardware.org/?probe=c7522b70ba) | Sep 27, 2022 |
| ASUSTek    | ROG ZENITH EXTREME          | [3e14df6c26](https://linux-hardware.org/?probe=3e14df6c26) | Sep 27, 2022 |
| Gigabyte   | X399 AORUS XTREME-CF        | [762ad6e460](https://linux-hardware.org/?probe=762ad6e460) | Sep 26, 2022 |
| MSI        | Z590-A PRO                  | [72bd6750e5](https://linux-hardware.org/?probe=72bd6750e5) | Sep 25, 2022 |
| ASUSTek    | ROG ZENITH EXTREME          | [60635ca9bc](https://linux-hardware.org/?probe=60635ca9bc) | Sep 24, 2022 |
| ASUSTek    | PRIME B450M-GAMING/BR       | [2a7c09d404](https://linux-hardware.org/?probe=2a7c09d404) | Sep 24, 2022 |
| Gigabyte   | X570 GAMING X               | [07f9a5063e](https://linux-hardware.org/?probe=07f9a5063e) | Sep 23, 2022 |
| Biostar    | TA75MH2                     | [e76fb13311](https://linux-hardware.org/?probe=e76fb13311) | Sep 23, 2022 |
| ASUSTek    | ROG ZENITH EXTREME          | [384ab44e0a](https://linux-hardware.org/?probe=384ab44e0a) | Sep 23, 2022 |
| ASUSTek    | ROG ZENITH EXTREME          | [24c7d626c8](https://linux-hardware.org/?probe=24c7d626c8) | Sep 23, 2022 |
| ASUSTek    | Z97-PRO GAMER               | [f6e7ad269e](https://linux-hardware.org/?probe=f6e7ad269e) | Sep 22, 2022 |
| ASUSTek    | ROG STRIX B550-F GAMING     | [256ff04106](https://linux-hardware.org/?probe=256ff04106) | Sep 20, 2022 |
| MSI        | Z390-A PRO                  | [9b0dd73d61](https://linux-hardware.org/?probe=9b0dd73d61) | Sep 20, 2022 |
| Supermicro | SKAGIT09                    | [b7dcf8a06c](https://linux-hardware.org/?probe=b7dcf8a06c) | Sep 20, 2022 |
| Acer       | Aspire G7750                | [c54e28dc84](https://linux-hardware.org/?probe=c54e28dc84) | Sep 18, 2022 |
| Gigabyte   | B560M D3H                   | [515d75e6b7](https://linux-hardware.org/?probe=515d75e6b7) | Sep 17, 2022 |
| ASUSTek    | Z97-K                       | [3f362093da](https://linux-hardware.org/?probe=3f362093da) | Sep 16, 2022 |
| Gigabyte   | B450M DS3H-CF               | [ea2264656c](https://linux-hardware.org/?probe=ea2264656c) | Sep 15, 2022 |
| ASUSTek    | TUF Gaming B550M-PLUS       | [d79d03b7ef](https://linux-hardware.org/?probe=d79d03b7ef) | Sep 11, 2022 |
| ASRock     | H470M-HVS                   | [17e4855f90](https://linux-hardware.org/?probe=17e4855f90) | Sep 09, 2022 |
| Supermicro | SKAGIT09                    | [d3f42d0c24](https://linux-hardware.org/?probe=d3f42d0c24) | Sep 08, 2022 |
| Gigabyte   | B450M DS3H-CF               | [557860ffbd](https://linux-hardware.org/?probe=557860ffbd) | Sep 07, 2022 |
| MSI        | B350 PC MATE                | [1f4f30c013](https://linux-hardware.org/?probe=1f4f30c013) | Sep 06, 2022 |
| MSI        | B450-A PRO MAX              | [0c89daf254](https://linux-hardware.org/?probe=0c89daf254) | Sep 03, 2022 |
| ASRock     | A320M-HDV                   | [5a9342d8e9](https://linux-hardware.org/?probe=5a9342d8e9) | Sep 03, 2022 |
| Dell       | 02YYK5 A00                  | [742579c33d](https://linux-hardware.org/?probe=742579c33d) | Sep 03, 2022 |
| OEM        | G41 775 ICH7 8712           | [4c9041cf15](https://linux-hardware.org/?probe=4c9041cf15) | Sep 03, 2022 |
| MSI        | 970 GAMING                  | [296c04b276](https://linux-hardware.org/?probe=296c04b276) | Sep 02, 2022 |
| MSI        | MAG B550M BAZOOKA           | [a1b5555512](https://linux-hardware.org/?probe=a1b5555512) | Sep 02, 2022 |
| Gigabyte   | B85M-HD3                    | [dcb5e7a20c](https://linux-hardware.org/?probe=dcb5e7a20c) | Aug 29, 2022 |
| Supermicro | SKAGIT09                    | [3f4c6a4d48](https://linux-hardware.org/?probe=3f4c6a4d48) | Aug 29, 2022 |
| Pegatron   | 2AB6                        | [93af020634](https://linux-hardware.org/?probe=93af020634) | Aug 27, 2022 |
| ASRock     | B450M/ac R2.0               | [ede2f61f08](https://linux-hardware.org/?probe=ede2f61f08) | Aug 26, 2022 |
| MSI        | B450-A PRO                  | [36f10ad555](https://linux-hardware.org/?probe=36f10ad555) | Aug 24, 2022 |
| ASUSTek    | B85-PLUS                    | [1eba4b558d](https://linux-hardware.org/?probe=1eba4b558d) | Aug 23, 2022 |
| Gigabyte   | BOLD E3032                  | [4b70fe47a2](https://linux-hardware.org/?probe=4b70fe47a2) | Aug 23, 2022 |
| Gigabyte   | H410M S2 V2                 | [cb43b7a4cf](https://linux-hardware.org/?probe=cb43b7a4cf) | Aug 22, 2022 |
| Gigabyte   | H97-Gaming 3                | [c084ff3123](https://linux-hardware.org/?probe=c084ff3123) | Aug 22, 2022 |
| Supermicro | SKAGIT09                    | [1ae2767db3](https://linux-hardware.org/?probe=1ae2767db3) | Aug 22, 2022 |
| MSI        | B350 PC MATE                | [e058dec94d](https://linux-hardware.org/?probe=e058dec94d) | Aug 19, 2022 |
| ASUSTek    | TUF Gaming B450-PLUS II     | [dd98185972](https://linux-hardware.org/?probe=dd98185972) | Aug 16, 2022 |
| ASUSTek    | H170M-PLUS/BR               | [feb4e50ec5](https://linux-hardware.org/?probe=feb4e50ec5) | Aug 16, 2022 |
| Lenovo     | Bantry CRB SDK0J40700 WI... | [792eb4143f](https://linux-hardware.org/?probe=792eb4143f) | Aug 16, 2022 |
| MSI        | B350 PC MATE                | [646d091037](https://linux-hardware.org/?probe=646d091037) | Aug 15, 2022 |
| HP         | 805D                        | [54f4e0fdb0](https://linux-hardware.org/?probe=54f4e0fdb0) | Aug 14, 2022 |
| Dell       | 0C2XKD A01                  | [cfad241ca0](https://linux-hardware.org/?probe=cfad241ca0) | Aug 12, 2022 |
| Positivo   | POS-PARS760GCD POSITIVO     | [dc6e65929f](https://linux-hardware.org/?probe=dc6e65929f) | Aug 12, 2022 |
| HP         | 8459                        | [677ca01f4f](https://linux-hardware.org/?probe=677ca01f4f) | Aug 11, 2022 |
| Gigabyte   | H370 AORUS GAMING 3 WIFI... | [d2f7a86fd8](https://linux-hardware.org/?probe=d2f7a86fd8) | Aug 11, 2022 |
| Gigabyte   | H370 AORUS GAMING 3 WIFI... | [6eac3041ec](https://linux-hardware.org/?probe=6eac3041ec) | Aug 07, 2022 |
| MSI        | B550-A PRO                  | [fb01882d07](https://linux-hardware.org/?probe=fb01882d07) | Aug 06, 2022 |
| MSI        | Z97 GAMING 7                | [01cf6a0897](https://linux-hardware.org/?probe=01cf6a0897) | Aug 06, 2022 |
| MSI        | MAG Z490 TOMAHAWK           | [1340311493](https://linux-hardware.org/?probe=1340311493) | Aug 06, 2022 |
| Gigabyte   | B450 I AORUS PRO WIFI-CF    | [6fa2b142e4](https://linux-hardware.org/?probe=6fa2b142e4) | Aug 06, 2022 |
| Gigabyte   | B450 I AORUS PRO WIFI-CF    | [e5e72c1264](https://linux-hardware.org/?probe=e5e72c1264) | Aug 05, 2022 |
| ASUSTek    | ROG Maximus XI HERO         | [d725206bff](https://linux-hardware.org/?probe=d725206bff) | Aug 04, 2022 |
| Lenovo     | SHARKBAY SDK0E50510 WIN     | [42469385bc](https://linux-hardware.org/?probe=42469385bc) | Aug 04, 2022 |
| ASUSTek    | P8H67                       | [b1b842e547](https://linux-hardware.org/?probe=b1b842e547) | Jul 29, 2022 |
| ASUSTek    | GRYPHON Z87                 | [73b9d340d2](https://linux-hardware.org/?probe=73b9d340d2) | Jul 28, 2022 |
| ASUSTek    | PRIME X370-PRO              | [ee8688ecdb](https://linux-hardware.org/?probe=ee8688ecdb) | Jul 26, 2022 |
| ASRock     | Z270 Gaming K4              | [63612e20b4](https://linux-hardware.org/?probe=63612e20b4) | Jul 26, 2022 |
| ASUSTek    | PRIME B350-PLUS             | [5658129aa4](https://linux-hardware.org/?probe=5658129aa4) | Jul 24, 2022 |
| Fujitsu    | D3500-A1 S26361-D3500-A1    | [ba1841221c](https://linux-hardware.org/?probe=ba1841221c) | Jul 24, 2022 |
| MSI        | MPG X570 GAMING PLUS        | [021e469888](https://linux-hardware.org/?probe=021e469888) | Jul 23, 2022 |
| MSI        | MPG X570 GAMING PLUS        | [ea90d78c53](https://linux-hardware.org/?probe=ea90d78c53) | Jul 23, 2022 |
| ASUSTek    | TUF Gaming Z590-PLUS WIF... | [6e6e65c711](https://linux-hardware.org/?probe=6e6e65c711) | Jul 23, 2022 |
| Gigabyte   | P35-DS3L                    | [4ae76fafc9](https://linux-hardware.org/?probe=4ae76fafc9) | Jul 22, 2022 |
| Shuttle    | NC01U V1.0                  | [827d6c81ae](https://linux-hardware.org/?probe=827d6c81ae) | Jul 22, 2022 |
| Shuttle    | NC01U V1.0                  | [fecfaf6008](https://linux-hardware.org/?probe=fecfaf6008) | Jul 21, 2022 |
| HP         | 18E9                        | [f15b2671b0](https://linux-hardware.org/?probe=f15b2671b0) | Jul 21, 2022 |
| ASRock     | B550 Extreme4               | [226924706f](https://linux-hardware.org/?probe=226924706f) | Jul 20, 2022 |
| Gigabyte   | P35-DS3L                    | [cabd591648](https://linux-hardware.org/?probe=cabd591648) | Jul 20, 2022 |
| Gigabyte   | Z390 GAMING X-CF            | [0e3950303c](https://linux-hardware.org/?probe=0e3950303c) | Jul 18, 2022 |
| ASRock     | Z170 Extreme4               | [4f4b63a026](https://linux-hardware.org/?probe=4f4b63a026) | Jul 18, 2022 |
| Acer       | Predator PO3-620            | [f3e22c0e6d](https://linux-hardware.org/?probe=f3e22c0e6d) | Jul 18, 2022 |
| Gigabyte   | X570 AORUS MASTER           | [01d595926f](https://linux-hardware.org/?probe=01d595926f) | Jul 15, 2022 |
| MSI        | X99A XPOWER GAMING TITAN... | [e764729eeb](https://linux-hardware.org/?probe=e764729eeb) | Jul 13, 2022 |
| ASRock     | Z170 Extreme4               | [7ecf3ad1b7](https://linux-hardware.org/?probe=7ecf3ad1b7) | Jul 13, 2022 |
| ASRock     | B550 Extreme4               | [6106db3d9a](https://linux-hardware.org/?probe=6106db3d9a) | Jul 12, 2022 |
| MSI        | MPG X570S EDGE MAX WIFI     | [fafb6deae6](https://linux-hardware.org/?probe=fafb6deae6) | Jul 12, 2022 |
| ASUSTek    | ROG Maximus Z690 EXTREME    | [d6531258d0](https://linux-hardware.org/?probe=d6531258d0) | Jul 11, 2022 |
| ASRock     | B550 Taichi                 | [61fe809791](https://linux-hardware.org/?probe=61fe809791) | Jul 10, 2022 |
| Gigabyte   | Z77-D3H                     | [f9e15346d3](https://linux-hardware.org/?probe=f9e15346d3) | Jul 10, 2022 |
| ASUSTek    | P9X79 PRO                   | [d7e1136386](https://linux-hardware.org/?probe=d7e1136386) | Jul 07, 2022 |
| MSI        | MPG X570S EDGE MAX WIFI     | [7d5d5c1a7e](https://linux-hardware.org/?probe=7d5d5c1a7e) | Jul 02, 2022 |
| HP         | 8459                        | [f43fdff127](https://linux-hardware.org/?probe=f43fdff127) | Jul 01, 2022 |
| ASUSTek    | ET2400A                     | [8801791f80](https://linux-hardware.org/?probe=8801791f80) | Jul 01, 2022 |
| ASUSTek    | ROG ZENITH EXTREME          | [33c8a42a4d](https://linux-hardware.org/?probe=33c8a42a4d) | Jun 29, 2022 |
| Gigabyte   | X570 AORUS PRO              | [757741fe0d](https://linux-hardware.org/?probe=757741fe0d) | Jun 29, 2022 |
| ASUSTek    | ROG ZENITH EXTREME          | [efb8cff806](https://linux-hardware.org/?probe=efb8cff806) | Jun 28, 2022 |
| MSI        | MAG X570S TOMAHAWK MAX W... | [a6555d107c](https://linux-hardware.org/?probe=a6555d107c) | Jun 27, 2022 |
| ASRock     | A320M Pro4                  | [e1918d8aab](https://linux-hardware.org/?probe=e1918d8aab) | Jun 25, 2022 |
| Huanan     | X99-F8 GAMING V5.0          | [2688876fc9](https://linux-hardware.org/?probe=2688876fc9) | Jun 25, 2022 |
| ASRock     | A320M Pro4                  | [f4f2e68e79](https://linux-hardware.org/?probe=f4f2e68e79) | Jun 24, 2022 |
| Apple      | Mac-F60DEB81FF30ACF6 Mac... | [04e6f0ee4a](https://linux-hardware.org/?probe=04e6f0ee4a) | Jun 24, 2022 |
| ABIT       | IP35 Pro                    | [a5f262c233](https://linux-hardware.org/?probe=a5f262c233) | Jun 23, 2022 |
| ASUSTek    | P8P67 LE                    | [8e1bc37281](https://linux-hardware.org/?probe=8e1bc37281) | Jun 19, 2022 |
| ASRock     | X570M Pro4                  | [bbb784f2df](https://linux-hardware.org/?probe=bbb784f2df) | Jun 18, 2022 |
| Dell       | 0YNVJG A01                  | [b75bebfda2](https://linux-hardware.org/?probe=b75bebfda2) | Jun 18, 2022 |
| ASUSTek    | X99-A/USB                   | [3ad17f6d78](https://linux-hardware.org/?probe=3ad17f6d78) | Jun 16, 2022 |
| ASUSTek    | P5QC                        | [b9a53514e1](https://linux-hardware.org/?probe=b9a53514e1) | Jun 16, 2022 |
| MSI        | Z270 GAMING M5              | [d5f742022e](https://linux-hardware.org/?probe=d5f742022e) | Jun 16, 2022 |
| MSI        | Z270 GAMING M5              | [6c352cf792](https://linux-hardware.org/?probe=6c352cf792) | Jun 16, 2022 |
| Gigabyte   | B450M DS3H-CF               | [2b307211cd](https://linux-hardware.org/?probe=2b307211cd) | Jun 14, 2022 |
| Dell       | 0KC9NP A01                  | [c573376df6](https://linux-hardware.org/?probe=c573376df6) | Jun 11, 2022 |
| Gigabyte   | Z270-HD3P-CF                | [317ae1383a](https://linux-hardware.org/?probe=317ae1383a) | Jun 10, 2022 |
| ASRock     | X570M Pro4                  | [4f6d06171b](https://linux-hardware.org/?probe=4f6d06171b) | Jun 10, 2022 |
| AZW        | Gemini J45                  | [f4d7238f95](https://linux-hardware.org/?probe=f4d7238f95) | Jun 08, 2022 |
| ASUSTek    | ROG STRIX X570-E GAMING     | [15f48b1e64](https://linux-hardware.org/?probe=15f48b1e64) | Jun 08, 2022 |
| MSI        | X470 GAMING PLUS MAX        | [9bc79127f3](https://linux-hardware.org/?probe=9bc79127f3) | Jun 06, 2022 |
| Dell       | 0Y2MRG A00                  | [11bba01e79](https://linux-hardware.org/?probe=11bba01e79) | Jun 06, 2022 |
| ASUSTek    | ROG Maximus Z690 HERO       | [70f49afd95](https://linux-hardware.org/?probe=70f49afd95) | Jun 04, 2022 |
| ASUSTek    | M5A78L-M LE/USB3            | [95173b9d90](https://linux-hardware.org/?probe=95173b9d90) | Jun 04, 2022 |
| ASUSTek    | M5A78L LE                   | [8eda28a8d4](https://linux-hardware.org/?probe=8eda28a8d4) | May 30, 2022 |
| ASUSTek    | P7H55-M LE                  | [4f55b87c44](https://linux-hardware.org/?probe=4f55b87c44) | May 28, 2022 |
| Gigabyte   | B85M-D2V                    | [2bc6293c6a](https://linux-hardware.org/?probe=2bc6293c6a) | May 19, 2022 |
| Fujitsu    | D3161-A1 S26361-D3161-A1    | [93b08c2d75](https://linux-hardware.org/?probe=93b08c2d75) | May 19, 2022 |
| ASRock     | B560M Pro4                  | [ba3b29db98](https://linux-hardware.org/?probe=ba3b29db98) | May 18, 2022 |
| Gigabyte   | B85M-D2V                    | [da9da96cda](https://linux-hardware.org/?probe=da9da96cda) | May 17, 2022 |
| ASUSTek    | M5A78L LE                   | [697a89162e](https://linux-hardware.org/?probe=697a89162e) | May 16, 2022 |
| Dell       | 0KJCC5 A00                  | [bb68e24835](https://linux-hardware.org/?probe=bb68e24835) | May 15, 2022 |
| ASUSTek    | ROG STRIX B550-I GAMING     | [0ec606b729](https://linux-hardware.org/?probe=0ec606b729) | May 14, 2022 |
| ASUSTek    | ROG STRIX B550-I GAMING     | [6fdf1cd28c](https://linux-hardware.org/?probe=6fdf1cd28c) | May 14, 2022 |
| MSI        | B450M PRO-M2                | [0bb720a248](https://linux-hardware.org/?probe=0bb720a248) | May 14, 2022 |
| ASUSTek    | TUF B450M-PLUS GAMING       | [fb2a9c9ddf](https://linux-hardware.org/?probe=fb2a9c9ddf) | May 13, 2022 |
| MSI        | B450M MORTAR TITANIUM       | [b03899e10b](https://linux-hardware.org/?probe=b03899e10b) | May 13, 2022 |
| Lenovo     | SHARKBAY NOK                | [7923c29010](https://linux-hardware.org/?probe=7923c29010) | May 11, 2022 |
| ASUSTek    | ROG Maximus Z690 EXTREME    | [76cc09b228](https://linux-hardware.org/?probe=76cc09b228) | May 10, 2022 |
| ASUSTek    | ROG Maximus Z690 EXTREME    | [6500cb78c3](https://linux-hardware.org/?probe=6500cb78c3) | May 10, 2022 |
| HP         | 1998                        | [7f82a04d73](https://linux-hardware.org/?probe=7f82a04d73) | May 10, 2022 |
| ASUSTek    | ROG ZENITH EXTREME          | [5f90cb38d2](https://linux-hardware.org/?probe=5f90cb38d2) | May 07, 2022 |
| MSI        | X470 GAMING PLUS MAX        | [0b27354c9c](https://linux-hardware.org/?probe=0b27354c9c) | May 05, 2022 |
| Gigabyte   | Z370P D3-CF                 | [8a561e2442](https://linux-hardware.org/?probe=8a561e2442) | May 05, 2022 |
| Gigabyte   | X570 GAMING X               | [53a75b2d5c](https://linux-hardware.org/?probe=53a75b2d5c) | May 04, 2022 |
| MSI        | MPG B550 GAMING PLUS        | [62f9f79f7c](https://linux-hardware.org/?probe=62f9f79f7c) | May 03, 2022 |
| MSI        | MPG B550 GAMING PLUS        | [afce1937fe](https://linux-hardware.org/?probe=afce1937fe) | May 03, 2022 |
| ASUSTek    | P8B75-M                     | [dadde1bbc0](https://linux-hardware.org/?probe=dadde1bbc0) | May 02, 2022 |
| Supermicro | X8ST3                       | [a94462f4b5](https://linux-hardware.org/?probe=a94462f4b5) | May 02, 2022 |
| ASUSTek    | PRIME B550M-K               | [92c09fc927](https://linux-hardware.org/?probe=92c09fc927) | Apr 30, 2022 |
| ASRock     | B550 Extreme4               | [7a90a198f5](https://linux-hardware.org/?probe=7a90a198f5) | Apr 30, 2022 |
| ASUSTek    | M5A78L LE                   | [9328531b5a](https://linux-hardware.org/?probe=9328531b5a) | Apr 30, 2022 |
| Lenovo     | 36C5 SDK0J40700 WIN 3258... | [d9ac32b17d](https://linux-hardware.org/?probe=d9ac32b17d) | Apr 30, 2022 |
| Biostar    | A68N-2100K                  | [db9760ae3a](https://linux-hardware.org/?probe=db9760ae3a) | Apr 27, 2022 |
| Biostar    | A68N-2100K                  | [87d629883f](https://linux-hardware.org/?probe=87d629883f) | Apr 27, 2022 |
| HP         | 0AACh                       | [f9e511945d](https://linux-hardware.org/?probe=f9e511945d) | Apr 25, 2022 |
| Gigabyte   | A320M-S2H V2-CF             | [4b41ff5fb9](https://linux-hardware.org/?probe=4b41ff5fb9) | Apr 24, 2022 |
| Gigabyte   | A320M-S2H V2-CF             | [3d513e3c6c](https://linux-hardware.org/?probe=3d513e3c6c) | Mar 24, 2022 |
| Dell       | 0K240Y A02                  | [b5783c7fa0](https://linux-hardware.org/?probe=b5783c7fa0) | Mar 03, 2022 |
| Gigabyte   | H410M S2H V3                | [e5da146c8e](https://linux-hardware.org/?probe=e5da146c8e) | Feb 27, 2022 |
| Gigabyte   | B550M DS3H                  | [21a8a676d1](https://linux-hardware.org/?probe=21a8a676d1) | Dec 28, 2021 |
| Gigabyte   | B550M DS3H                  | [61561f50ba](https://linux-hardware.org/?probe=61561f50ba) | Dec 28, 2021 |
| Gigabyte   | P35-DS3L                    | [e13fea24e4](https://linux-hardware.org/?probe=e13fea24e4) | Dec 27, 2021 |
| ASUSTek    | ROG STRIX B550-F GAMING     | [1c12810a81](https://linux-hardware.org/?probe=1c12810a81) | Dec 06, 2021 |
| ASUSTek    | ROG STRIX B550-F GAMING     | [acadafa3aa](https://linux-hardware.org/?probe=acadafa3aa) | Nov 30, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Desktops | Percent |
|----------------------------|----------|---------|
| 5.15.0-52-generic          | 19       | 10.61%  |
| 5.15.0-43-generic          | 16       | 8.94%   |
| 5.15.0-48-generic          | 13       | 7.26%   |
| 5.15.0-47-generic          | 12       | 6.7%    |
| 5.15.0-46-generic          | 12       | 6.7%    |
| 5.15.0-27-generic          | 12       | 6.7%    |
| 5.15.0-40-generic          | 11       | 6.15%   |
| 5.15.0-41-generic          | 10       | 5.59%   |
| 5.15.0-53-generic          | 9        | 5.03%   |
| 5.15.0-50-generic          | 7        | 3.91%   |
| 5.15.0-30-generic          | 6        | 3.35%   |
| 5.15.0-48-lowlatency       | 5        | 2.79%   |
| 5.15.0-25-generic          | 5        | 2.79%   |
| 5.15.0-37-generic          | 4        | 2.23%   |
| 5.15.0-33-generic          | 4        | 2.23%   |
| 5.15.0-27-lowlatency       | 3        | 1.68%   |
| 5.15.0-52-lowlatency       | 2        | 1.12%   |
| 5.15.0-47-lowlatency       | 2        | 1.12%   |
| 5.15.0-39-generic          | 2        | 1.12%   |
| 6.0.1-060001-generic       | 1        | 0.56%   |
| 5.4.0-122-generic          | 1        | 0.56%   |
| 5.19.12-xanmod1            | 1        | 0.56%   |
| 5.18.4-xanmod1             | 1        | 0.56%   |
| 5.18.4-vitodoc             | 1        | 0.56%   |
| 5.18.12-051812-generic     | 1        | 0.56%   |
| 5.18.10-051810-generic     | 1        | 0.56%   |
| 5.17.6-051706-generic      | 1        | 0.56%   |
| 5.17.14-xanmod1            | 1        | 0.56%   |
| 5.17.0-12.1-liquorix-amd64 | 1        | 0.56%   |
| 5.17.0-1017-oem            | 1        | 0.56%   |
| 5.17.0-051700-generic      | 1        | 0.56%   |
| 5.16.0-051600rc3-generic   | 1        | 0.56%   |
| 5.15.13-051513-generic     | 1        | 0.56%   |
| 5.15.0-50-lowlatency       | 1        | 0.56%   |
| 5.15.0-46-lowlatency       | 1        | 0.56%   |
| 5.15.0-43-lowlatency       | 1        | 0.56%   |
| 5.15.0-37-lowlatency       | 1        | 0.56%   |
| 5.15.0-35-lowlatency       | 1        | 0.56%   |
| 5.15.0-35-generic          | 1        | 0.56%   |
| 5.15.0-30-lowlatency       | 1        | 0.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 154      | 91.12%  |
| 5.17.0  | 3        | 1.78%   |
| 5.18.4  | 2        | 1.18%   |
| 6.0.1   | 1        | 0.59%   |
| 5.4.0   | 1        | 0.59%   |
| 5.19.12 | 1        | 0.59%   |
| 5.18.12 | 1        | 0.59%   |
| 5.18.10 | 1        | 0.59%   |
| 5.17.6  | 1        | 0.59%   |
| 5.17.14 | 1        | 0.59%   |
| 5.16.0  | 1        | 0.59%   |
| 5.15.13 | 1        | 0.59%   |
| 5.13.0  | 1        | 0.59%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 155      | 91.72%  |
| 5.17    | 5        | 2.96%   |
| 5.18    | 4        | 2.37%   |
| 6.0     | 1        | 0.59%   |
| 5.4     | 1        | 0.59%   |
| 5.19    | 1        | 0.59%   |
| 5.16    | 1        | 0.59%   |
| 5.13    | 1        | 0.59%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 167      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| KDE5  | 166      | 99.4%   |
| GNOME | 1        | 0.6%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 161      | 96.41%  |
| Wayland | 4        | 2.4%    |
| Tty     | 2        | 1.2%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 113      | 66.86%  |
| Unknown | 41       | 24.26%  |
| GDM3    | 10       | 5.92%   |
| LightDM | 5        | 2.96%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 76       | 45.51%  |
| fr_FR | 12       | 7.19%   |
| it_IT | 10       | 5.99%   |
| de_DE | 10       | 5.99%   |
| ru_RU | 8        | 4.79%   |
| en_GB | 8        | 4.79%   |
| en_AU | 7        | 4.19%   |
| pt_BR | 5        | 2.99%   |
| pl_PL | 3        | 1.8%    |
| en_CA | 3        | 1.8%    |
| nl_NL | 2        | 1.2%    |
| es_ES | 2        | 1.2%    |
| es_AR | 2        | 1.2%    |
| en_ZA | 2        | 1.2%    |
| en_PH | 2        | 1.2%    |
| en_IN | 2        | 1.2%    |
| cs_CZ | 2        | 1.2%    |
| sl_SI | 1        | 0.6%    |
| fr_BE | 1        | 0.6%    |
| es_CO | 1        | 0.6%    |
| en_NZ | 1        | 0.6%    |
| en_IL | 1        | 0.6%    |
| en_AG | 1        | 0.6%    |
| el_GR | 1        | 0.6%    |
| de_LU | 1        | 0.6%    |
| de_CH | 1        | 0.6%    |
| de_AT | 1        | 0.6%    |
| C     | 1        | 0.6%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 104      | 61.9%   |
| EFI  | 64       | 38.1%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 147      | 88.02%  |
| Btrfs   | 10       | 5.99%   |
| Overlay | 8        | 4.79%   |
| Xfs     | 1        | 0.6%    |
| Ext3    | 1        | 0.6%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 88       | 51.46%  |
| Unknown | 71       | 41.52%  |
| MBR     | 12       | 7.02%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 144      | 84.71%  |
| Yes       | 26       | 15.29%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 98       | 58.68%  |
| Yes       | 69       | 41.32%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 47       | 28.14%  |
| Gigabyte Technology | 32       | 19.16%  |
| MSI                 | 24       | 14.37%  |
| ASRock              | 17       | 10.18%  |
| Dell                | 11       | 6.59%   |
| Lenovo              | 7        | 4.19%   |
| Hewlett-Packard     | 6        | 3.59%   |
| Supermicro          | 4        | 2.4%    |
| Shuttle             | 2        | 1.2%    |
| Fujitsu             | 2        | 1.2%    |
| Biostar             | 2        | 1.2%    |
| Apple               | 2        | 1.2%    |
| Acer                | 2        | 1.2%    |
| Positivo            | 1        | 0.6%    |
| Pegatron            | 1        | 0.6%    |
| OEM                 | 1        | 0.6%    |
| JWIPC               | 1        | 0.6%    |
| Huanan              | 1        | 0.6%    |
| Foxconn             | 1        | 0.6%    |
| AZW                 | 1        | 0.6%    |
| ABIT                | 1        | 0.6%    |
| Unknown             | 1        | 0.6%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| ASUS All Series                   | 5        | 2.99%   |
| ASUS ROG STRIX B550-F GAMING      | 4        | 2.4%    |
| MSI MS-7B79                       | 3        | 1.8%    |
| Gigabyte B450M DS3H               | 3        | 1.8%    |
| Supermicro SKAGIT09               | 2        | 1.2%    |
| MSI MS-7C56                       | 2        | 1.2%    |
| MSI MS-7B86                       | 2        | 1.2%    |
| MSI MS-7B84                       | 2        | 1.2%    |
| Gigabyte X570 GAMING X            | 2        | 1.2%    |
| Gigabyte B450 I AORUS PRO WIFI    | 2        | 1.2%    |
| Dell OptiPlex 7010                | 2        | 1.2%    |
| ASUS STRIX Z270E GAMING           | 2        | 1.2%    |
| ASUS ROG ZENITH EXTREME           | 2        | 1.2%    |
| ASUS ROG STRIX X570-E GAMING      | 2        | 1.2%    |
| ASUS ROG STRIX B550-I GAMING      | 2        | 1.2%    |
| Supermicro X9DAL                  | 1        | 0.6%    |
| Supermicro X8ST3                  | 1        | 0.6%    |
| Shuttle SH61R                     | 1        | 0.6%    |
| Shuttle NC01U                     | 1        | 0.6%    |
| Positivo POS-PARS760GCD           | 1        | 0.6%    |
| Pegatron p6740la                  | 1        | 0.6%    |
| OEM G41 775 ICH7 8712             | 1        | 0.6%    |
| MSI MS-7D54                       | 1        | 0.6%    |
| MSI MS-7D09                       | 1        | 0.6%    |
| MSI MS-7C95                       | 1        | 0.6%    |
| MSI MS-7C80                       | 1        | 0.6%    |
| MSI MS-7C37                       | 1        | 0.6%    |
| MSI MS-7B98                       | 1        | 0.6%    |
| MSI MS-7B89                       | 1        | 0.6%    |
| MSI MS-7B61                       | 1        | 0.6%    |
| MSI MS-7A78                       | 1        | 0.6%    |
| MSI MS-7A40                       | 1        | 0.6%    |
| MSI MS-7A34                       | 1        | 0.6%    |
| MSI MS-7A21                       | 1        | 0.6%    |
| MSI MS-7996                       | 1        | 0.6%    |
| MSI MS-7916                       | 1        | 0.6%    |
| MSI MS-7693                       | 1        | 0.6%    |
| Lenovo ThinkCentre M90p 5498A2U   | 1        | 0.6%    |
| Lenovo ThinkCentre M83 10AM000UUS | 1        | 0.6%    |
| Lenovo ThinkCentre M83 10AHS2XB00 | 1        | 0.6%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUS ROG                | 15       | 8.98%   |
| Dell OptiPlex           | 7        | 4.19%   |
| ASUS PRIME              | 7        | 4.19%   |
| ASUS TUF                | 6        | 3.59%   |
| Lenovo ThinkCentre      | 5        | 2.99%   |
| ASUS All                | 5        | 2.99%   |
| MSI MS-7B79             | 3        | 1.8%    |
| Gigabyte X570           | 3        | 1.8%    |
| Gigabyte B450M          | 3        | 1.8%    |
| ASUS M5A78L-M           | 3        | 1.8%    |
| Supermicro SKAGIT09     | 2        | 1.2%    |
| MSI MS-7C56             | 2        | 1.2%    |
| MSI MS-7B86             | 2        | 1.2%    |
| MSI MS-7B84             | 2        | 1.2%    |
| HP ProDesk              | 2        | 1.2%    |
| Gigabyte H410M          | 2        | 1.2%    |
| Gigabyte B660M          | 2        | 1.2%    |
| Gigabyte B450           | 2        | 1.2%    |
| Fujitsu ESPRIMO         | 2        | 1.2%    |
| Dell Precision          | 2        | 1.2%    |
| ASUS STRIX              | 2        | 1.2%    |
| ASRock B550             | 2        | 1.2%    |
| ASRock A320M-HDV        | 2        | 1.2%    |
| Supermicro X9DAL        | 1        | 0.6%    |
| Supermicro X8ST3        | 1        | 0.6%    |
| Shuttle SH61R           | 1        | 0.6%    |
| Shuttle NC01U           | 1        | 0.6%    |
| Positivo POS-PARS760GCD | 1        | 0.6%    |
| Pegatron p6740la        | 1        | 0.6%    |
| OEM G41                 | 1        | 0.6%    |
| MSI MS-7D54             | 1        | 0.6%    |
| MSI MS-7D09             | 1        | 0.6%    |
| MSI MS-7C95             | 1        | 0.6%    |
| MSI MS-7C80             | 1        | 0.6%    |
| MSI MS-7C37             | 1        | 0.6%    |
| MSI MS-7B98             | 1        | 0.6%    |
| MSI MS-7B89             | 1        | 0.6%    |
| MSI MS-7B61             | 1        | 0.6%    |
| MSI MS-7A78             | 1        | 0.6%    |
| MSI MS-7A40             | 1        | 0.6%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 24       | 14.37%  |
| 2020 | 23       | 13.77%  |
| 2019 | 21       | 12.57%  |
| 2021 | 14       | 8.38%   |
| 2012 | 12       | 7.19%   |
| 2014 | 11       | 6.59%   |
| 2017 | 10       | 5.99%   |
| 2016 | 10       | 5.99%   |
| 2013 | 10       | 5.99%   |
| 2011 | 9        | 5.39%   |
| 2015 | 7        | 4.19%   |
| 2010 | 6        | 3.59%   |
| 2022 | 3        | 1.8%    |
| 2007 | 3        | 1.8%    |
| 2009 | 2        | 1.2%    |
| 2008 | 2        | 1.2%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 167      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 165      | 98.8%   |
| Enabled  | 2        | 1.2%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 167      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 51       | 30.36%  |
| 32.01-64.0  | 49       | 29.17%  |
| 8.01-16.0   | 28       | 16.67%  |
| 4.01-8.0    | 13       | 7.74%   |
| 64.01-256.0 | 13       | 7.74%   |
| 3.01-4.0    | 10       | 5.95%   |
| 24.01-32.0  | 4        | 2.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 49       | 28%     |
| 4.01-8.0   | 39       | 22.29%  |
| 3.01-4.0   | 34       | 19.43%  |
| 1.01-2.0   | 30       | 17.14%  |
| 8.01-16.0  | 17       | 9.71%   |
| 0.51-1.0   | 3        | 1.71%   |
| 16.01-24.0 | 2        | 1.14%   |
| 32.01-64.0 | 1        | 0.57%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 53       | 31.36%  |
| 1      | 44       | 26.04%  |
| 3      | 35       | 20.71%  |
| 4      | 15       | 8.88%   |
| 5      | 11       | 6.51%   |
| 6      | 6        | 3.55%   |
| 7      | 2        | 1.18%   |
| 11     | 1        | 0.59%   |
| 9      | 1        | 0.59%   |
| 8      | 1        | 0.59%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 99       | 58.93%  |
| Yes       | 69       | 41.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 166      | 99.4%   |
| No        | 1        | 0.6%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 96       | 57.14%  |
| No        | 72       | 42.86%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 95       | 56.89%  |
| Yes       | 72       | 43.11%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 34       | 20.36%  |
| Germany      | 15       | 8.98%   |
| Italy        | 12       | 7.19%   |
| France       | 12       | 7.19%   |
| Brazil       | 10       | 5.99%   |
| UK           | 9        | 5.39%   |
| Russia       | 8        | 4.79%   |
| Poland       | 7        | 4.19%   |
| Australia    | 6        | 3.59%   |
| Netherlands  | 5        | 2.99%   |
| Spain        | 3        | 1.8%    |
| India        | 3        | 1.8%    |
| Argentina    | 3        | 1.8%    |
| Switzerland  | 2        | 1.2%    |
| South Africa | 2        | 1.2%    |
| Slovenia     | 2        | 1.2%    |
| Serbia       | 2        | 1.2%    |
| Philippines  | 2        | 1.2%    |
| New Zealand  | 2        | 1.2%    |
| Czechia      | 2        | 1.2%    |
| Canada       | 2        | 1.2%    |
| Bulgaria     | 2        | 1.2%    |
| Belgium      | 2        | 1.2%    |
| Austria      | 2        | 1.2%    |
| Vietnam      | 1        | 0.6%    |
| Ukraine      | 1        | 0.6%    |
| Turkey       | 1        | 0.6%    |
| Thailand     | 1        | 0.6%    |
| Sweden       | 1        | 0.6%    |
| Romania      | 1        | 0.6%    |
| Portugal     | 1        | 0.6%    |
| Malta        | 1        | 0.6%    |
| Malaysia     | 1        | 0.6%    |
| Luxembourg   | 1        | 0.6%    |
| Israel       | 1        | 0.6%    |
| Iran         | 1        | 0.6%    |
| Greece       | 1        | 0.6%    |
| Finland      | 1        | 0.6%    |
| Ecuador      | 1        | 0.6%    |
| Colombia     | 1        | 0.6%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Rio de Janeiro  | 3        | 1.78%   |
| Moscow          | 3        | 1.78%   |
| Berlin          | 3        | 1.78%   |
| Wroclaw         | 2        | 1.18%   |
| Washington      | 2        | 1.18%   |
| Vienna          | 2        | 1.18%   |
| Prague          | 2        | 1.18%   |
| New York        | 2        | 1.18%   |
| Milan           | 2        | 1.18%   |
| Melbourne       | 2        | 1.18%   |
| Dallas          | 2        | 1.18%   |
| Canberra        | 2        | 1.18%   |
| Brasília       | 2        | 1.18%   |
| Bougival        | 2        | 1.18%   |
| Belgrade        | 2        | 1.18%   |
| Amsterdam       | 2        | 1.18%   |
| Zaandam         | 1        | 0.59%   |
| Yerevan         | 1        | 0.59%   |
| Wheaton         | 1        | 0.59%   |
| Whangarei       | 1        | 0.59%   |
| Wembley         | 1        | 0.59%   |
| Waukee          | 1        | 0.59%   |
| Vrhnika         | 1        | 0.59%   |
| Vladivostok     | 1        | 0.59%   |
| Vitebsk         | 1        | 0.59%   |
| Villa Nueva     | 1        | 0.59%   |
| Varna           | 1        | 0.59%   |
| Valencia        | 1        | 0.59%   |
| Ustron          | 1        | 0.59%   |
| Union City      | 1        | 0.59%   |
| Turku           | 1        | 0.59%   |
| Turin           | 1        | 0.59%   |
| Torun           | 1        | 0.59%   |
| Tholey          | 1        | 0.59%   |
| Therwil         | 1        | 0.59%   |
| Thai Nguyen     | 1        | 0.59%   |
| Templeton       | 1        | 0.59%   |
| Tehran          | 1        | 0.59%   |
| Syeverodonets'k | 1        | 0.59%   |
| Sydney          | 1        | 0.59%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 58       | 91     | 17.16%  |
| WDC                         | 55       | 82     | 16.27%  |
| Seagate                     | 54       | 99     | 15.98%  |
| Kingston                    | 25       | 31     | 7.4%    |
| Toshiba                     | 20       | 23     | 5.92%   |
| Crucial                     | 16       | 20     | 4.73%   |
| Hitachi                     | 15       | 15     | 4.44%   |
| SanDisk                     | 14       | 15     | 4.14%   |
| Patriot                     | 5        | 7      | 1.48%   |
| Intel                       | 5        | 5      | 1.48%   |
| HGST                        | 4        | 8      | 1.18%   |
| China                       | 4        | 5      | 1.18%   |
| A-DATA Technology           | 4        | 5      | 1.18%   |
| Transcend                   | 3        | 4      | 0.89%   |
| PNY                         | 3        | 4      | 0.89%   |
| Phison                      | 3        | 3      | 0.89%   |
| Lexar                       | 3        | 3      | 0.89%   |
| Unknown                     | 2        | 2      | 0.59%   |
| Phison Electronics          | 2        | 2      | 0.59%   |
| Micron/Crucial Technology   | 2        | 2      | 0.59%   |
| Micron Technology           | 2        | 2      | 0.59%   |
| Maxtor                      | 2        | 2      | 0.59%   |
| KODAK                       | 2        | 2      | 0.59%   |
| Kingston Technology Company | 2        | 2      | 0.59%   |
| Intenso                     | 2        | 2      | 0.59%   |
| Emtec                       | 2        | 2      | 0.59%   |
| XPG                         | 1        | 1      | 0.3%    |
| Verbatim                    | 1        | 1      | 0.3%    |
| USB3.0                      | 1        | 1      | 0.3%    |
| T-FORCE                     | 1        | 1      | 0.3%    |
| Smartbuy                    | 1        | 1      | 0.3%    |
| SK hynix                    | 1        | 3      | 0.3%    |
| Realtek Semiconductor       | 1        | 1      | 0.3%    |
| Plextor                     | 1        | 1      | 0.3%    |
| OCZ                         | 1        | 1      | 0.3%    |
| O2 Micro                    | 1        | 1      | 0.3%    |
| Mushkin                     | 1        | 2      | 0.3%    |
| KIOXIA-EXCERIA              | 1        | 2      | 0.3%    |
| KIOXIA                      | 1        | 1      | 0.3%    |
| KingFast                    | 1        | 1      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Seagate ST4000DM004-2CV104 4TB                    | 7        | 1.75%   |
| Kingston SA400S37240G 240GB SSD                   | 7        | 1.75%   |
| Toshiba DT01ACA100 1TB                            | 4        | 1%      |
| SanDisk NVMe SSD Drive 500GB                      | 4        | 1%      |
| Samsung SSD 850 EVO 500GB                         | 4        | 1%      |
| Samsung NVMe SSD Drive 500GB                      | 4        | 1%      |
| WDC WD10EZEX-22MFCA0 1TB                          | 3        | 0.75%   |
| Toshiba HDWD110 1TB                               | 3        | 0.75%   |
| Samsung SSD 980 500GB                             | 3        | 0.75%   |
| Samsung SSD 980 1TB                               | 3        | 0.75%   |
| Samsung SSD 870 EVO 1TB                           | 3        | 0.75%   |
| Samsung SSD 860 EVO 1TB                           | 3        | 0.75%   |
| Samsung SSD 840 PRO Series 128GB                  | 3        | 0.75%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 3        | 0.75%   |
| Samsung HD103SI 1TB                               | 3        | 0.75%   |
| Kingston SA2000M81000G 1TB                        | 3        | 0.75%   |
| Hitachi HTS547550A9E384 500GB                     | 3        | 0.75%   |
| Crucial CT500MX500SSD1 500GB                      | 3        | 0.75%   |
| Crucial CT240BX500SSD1 240GB                      | 3        | 0.75%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 2        | 0.5%    |
| WDC WD5000AAKX-753CA1 500GB                       | 2        | 0.5%    |
| WDC WD5000AADS-00S9B0 500GB                       | 2        | 0.5%    |
| WDC WD40EFAX-68JH4N1 4TB                          | 2        | 0.5%    |
| WDC WD20EZRZ-00Z5HB0 2TB                          | 2        | 0.5%    |
| WDC WD10EZEX-08WN4A0 1TB                          | 2        | 0.5%    |
| Toshiba HDWD130 3TB                               | 2        | 0.5%    |
| Seagate ST500LM012 HN-M500MBB 500GB               | 2        | 0.5%    |
| Seagate ST4000VN008-2DR166 4TB                    | 2        | 0.5%    |
| Seagate ST2000VM003-1CT164 2TB                    | 2        | 0.5%    |
| Seagate ST2000DM008-2FR102 2TB                    | 2        | 0.5%    |
| Seagate ST2000DM006-2DM164 2TB                    | 2        | 0.5%    |
| Seagate ST1000DM003-1SB102 1TB                    | 2        | 0.5%    |
| Seagate Expansion Desk 8TB                        | 2        | 0.5%    |
| Samsung SSD 970 EVO Plus 2TB                      | 2        | 0.5%    |
| Samsung SSD 860 EVO 500GB                         | 2        | 0.5%    |
| Samsung SSD 850 EVO 120GB                         | 2        | 0.5%    |
| Samsung PSSD T7 1TB                               | 2        | 0.5%    |
| Phison PCIe SSD 1TB                               | 2        | 0.5%    |
| Patriot Burst 120GB SSD                           | 2        | 0.5%    |
| Micron/Crucial P2 NVMe PCIe SSD 250GB             | 2        | 0.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 51       | 91     | 33.55%  |
| WDC                 | 50       | 67     | 32.89%  |
| Toshiba             | 17       | 19     | 11.18%  |
| Hitachi             | 15       | 15     | 9.87%   |
| Samsung Electronics | 12       | 13     | 7.89%   |
| HGST                | 4        | 8      | 2.63%   |
| Maxtor              | 1        | 1      | 0.66%   |
| JMicron Technology  | 1        | 1      | 0.66%   |
| IET                 | 1        | 1      | 0.66%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 29       | 44     | 23.02%  |
| Kingston            | 20       | 22     | 15.87%  |
| Crucial             | 13       | 15     | 10.32%  |
| WDC                 | 8        | 10     | 6.35%   |
| SanDisk             | 8        | 8      | 6.35%   |
| Patriot             | 5        | 7      | 3.97%   |
| China               | 4        | 5      | 3.17%   |
| Toshiba             | 3        | 3      | 2.38%   |
| PNY                 | 3        | 4      | 2.38%   |
| Lexar               | 3        | 3      | 2.38%   |
| Intel               | 3        | 3      | 2.38%   |
| Transcend           | 2        | 2      | 1.59%   |
| Micron Technology   | 2        | 2      | 1.59%   |
| KODAK               | 2        | 2      | 1.59%   |
| A-DATA Technology   | 2        | 3      | 1.59%   |
| Verbatim            | 1        | 1      | 0.79%   |
| USB3.0              | 1        | 1      | 0.79%   |
| Smartbuy            | 1        | 1      | 0.79%   |
| Plextor             | 1        | 1      | 0.79%   |
| OCZ                 | 1        | 1      | 0.79%   |
| Mushkin             | 1        | 2      | 0.79%   |
| Maxtor              | 1        | 1      | 0.79%   |
| KIOXIA-EXCERIA      | 1        | 2      | 0.79%   |
| KingFast            | 1        | 1      | 0.79%   |
| Intenso             | 1        | 1      | 0.79%   |
| INNOVATION IT       | 1        | 1      | 0.79%   |
| INDMEM              | 1        | 1      | 0.79%   |
| Hewlett-Packard     | 1        | 1      | 0.79%   |
| GOODRAM             | 1        | 1      | 0.79%   |
| Drevo               | 1        | 1      | 0.79%   |
| Apple               | 1        | 1      | 0.79%   |
| Apacer              | 1        | 1      | 0.79%   |
| Aireye              | 1        | 1      | 0.79%   |
| ADATA SU            | 1        | 1      | 0.79%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 114      | 216    | 39.86%  |
| SSD     | 104      | 154    | 36.36%  |
| NVMe    | 61       | 95     | 21.33%  |
| Unknown | 6        | 6      | 2.1%    |
| MMC     | 1        | 1      | 0.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 153      | 354    | 66.81%  |
| NVMe | 59       | 93     | 25.76%  |
| SAS  | 16       | 24     | 6.99%   |
| MMC  | 1        | 1      | 0.44%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 112      | 177    | 45.9%   |
| 0.51-1.0   | 62       | 90     | 25.41%  |
| 1.01-2.0   | 27       | 33     | 11.07%  |
| 3.01-4.0   | 22       | 40     | 9.02%   |
| 4.01-10.0  | 10       | 17     | 4.1%    |
| 2.01-3.0   | 9        | 11     | 3.69%   |
| 10.01-20.0 | 2        | 2      | 0.82%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 34       | 19.77%  |
| 1001-2000      | 32       | 18.6%   |
| More than 3000 | 27       | 15.7%   |
| 2001-3000      | 25       | 14.53%  |
| 101-250        | 23       | 13.37%  |
| 251-500        | 20       | 11.63%  |
| 1-20           | 6        | 3.49%   |
| 51-100         | 4        | 2.33%   |
| Unknown        | 1        | 0.58%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 26       | 15.03%  |
| 251-500        | 25       | 14.45%  |
| 501-1000       | 25       | 14.45%  |
| 1-20           | 24       | 13.87%  |
| 51-100         | 19       | 10.98%  |
| 1001-2000      | 17       | 9.83%   |
| More than 3000 | 15       | 8.67%   |
| 21-50          | 13       | 7.51%   |
| 2001-3000      | 8        | 4.62%   |
| Unknown        | 1        | 0.58%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Desktops | Drives | Percent |
|------------------------------------------------|----------|--------|---------|
| WDC WD5000AVVS-63M8B0 500GB                    | 1        | 1      | 4.35%   |
| WDC WD10EZEX-22MFCA0 1TB                       | 1        | 1      | 4.35%   |
| WDC WD10EZEX-08M2NA0 1TB                       | 1        | 1      | 4.35%   |
| Seagate ST500LT012-9WS142 500GB                | 1        | 1      | 4.35%   |
| Seagate ST500LM012 HN-M500MBB 500GB            | 1        | 1      | 4.35%   |
| Seagate ST500DM002-1BD142 500GB                | 1        | 1      | 4.35%   |
| Seagate ST3160827AS 160GB                      | 1        | 1      | 4.35%   |
| Seagate ST31500341AS 1TB                       | 1        | 1      | 4.35%   |
| Seagate ST31000524AS 1TB                       | 1        | 2      | 4.35%   |
| Seagate ST1000DM003-1SB102 1TB                 | 1        | 1      | 4.35%   |
| Seagate ST1000DM003-1CH162 1TB                 | 1        | 1      | 4.35%   |
| Samsung Electronics SSD 870 EVO 1TB            | 1        | 1      | 4.35%   |
| Samsung Electronics SSD 840 Series 250GB       | 1        | 1      | 4.35%   |
| Samsung Electronics HM321HI 320GB              | 1        | 1      | 4.35%   |
| Samsung Electronics HD103SI 1TB                | 1        | 1      | 4.35%   |
| Micron Technology 5100_MTFDDAV960TCB 960GB SSD | 1        | 1      | 4.35%   |
| Hitachi HTS547550A9E384 500GB                  | 1        | 1      | 4.35%   |
| Hitachi HDS721010CLA630 1TB                    | 1        | 1      | 4.35%   |
| Hitachi HDP725050GLA360 500GB                  | 1        | 1      | 4.35%   |
| Hitachi HCT721010SLA360 1TB                    | 1        | 1      | 4.35%   |
| HGST HUH728080ALE600 8TB                       | 1        | 1      | 4.35%   |
| Crucial CT525MX300SSD1 528GB                   | 1        | 1      | 4.35%   |
| Crucial CT240M500SSD1 240GB                    | 1        | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 7        | 9      | 31.82%  |
| Samsung Electronics | 4        | 4      | 18.18%  |
| Hitachi             | 4        | 4      | 18.18%  |
| WDC                 | 3        | 3      | 13.64%  |
| Crucial             | 2        | 2      | 9.09%   |
| Micron Technology   | 1        | 1      | 4.55%   |
| HGST                | 1        | 1      | 4.55%   |

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
| HDD  | 16       | 19     | 76.19%  |
| SSD  | 5        | 5      | 23.81%  |

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
| Detected | 91       | 238    | 46.91%  |
| Works    | 82       | 208    | 42.27%  |
| Malfunc  | 20       | 24     | 10.31%  |
| Failed   | 1        | 2      | 0.52%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 94       | 36.29%  |
| AMD                         | 72       | 27.8%   |
| Samsung Electronics         | 24       | 9.27%   |
| ASMedia Technology          | 11       | 4.25%   |
| SanDisk                     | 10       | 3.86%   |
| Kingston Technology Company | 9        | 3.47%   |
| Phison Electronics          | 6        | 2.32%   |
| Micron/Crucial Technology   | 6        | 2.32%   |
| JMicron Technology          | 6        | 2.32%   |
| ADATA Technology            | 4        | 1.54%   |
| Seagate Technology          | 3        | 1.16%   |
| Marvell Technology Group    | 2        | 0.77%   |
| LSI Logic / Symbios Logic   | 2        | 0.77%   |
| KIOXIA                      | 2        | 0.77%   |
| VIA Technologies            | 1        | 0.39%   |
| SK hynix                    | 1        | 0.39%   |
| Silicon Motion              | 1        | 0.39%   |
| Silicon Image               | 1        | 0.39%   |
| Realtek Semiconductor       | 1        | 0.39%   |
| O2 Micro                    | 1        | 0.39%   |
| INNOGRIT                    | 1        | 0.39%   |
| Broadcom / LSI              | 1        | 0.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 42       | 13.21%  |
| AMD 400 Series Chipset SATA Controller                                         | 20       | 6.29%   |
| AMD 500 Series Chipset SATA Controller                                         | 15       | 4.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 13       | 4.09%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 10       | 3.14%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 10       | 3.14%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 9        | 2.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 8        | 2.52%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 8        | 2.52%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 7        | 2.2%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 7        | 2.2%    |
| Samsung NVMe SSD Controller 980                                                | 6        | 1.89%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 6        | 1.89%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 6        | 1.89%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 5        | 1.57%   |
| Kingston Company A2000 NVMe SSD                                                | 5        | 1.57%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 5        | 1.57%   |
| AMD FCH SATA Controller D                                                      | 5        | 1.57%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4        | 1.26%   |
| Phison E12 NVMe Controller                                                     | 4        | 1.26%   |
| JMicron JMB363 SATA/IDE Controller                                             | 4        | 1.26%   |
| Intel SATA Controller [RAID mode]                                              | 4        | 1.26%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4        | 1.26%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4        | 1.26%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 4        | 1.26%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 4        | 1.26%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 4        | 1.26%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 4        | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 4        | 1.26%   |
| SanDisk Non-Volatile memory controller                                         | 3        | 0.94%   |
| Kingston Company Company Non-Volatile memory controller                        | 3        | 0.94%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 3        | 0.94%   |
| AMD X399 Series Chipset SATA Controller                                        | 3        | 0.94%   |
| AMD 300 Series Chipset SATA Controller                                         | 3        | 0.94%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 3        | 0.94%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2        | 0.63%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2        | 0.63%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2        | 0.63%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2        | 0.63%   |
| LSI Logic / Symbios Logic MegaRAID SAS 1078                                    | 2        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 154      | 62.86%  |
| NVMe | 58       | 23.67%  |
| IDE  | 22       | 8.98%   |
| RAID | 10       | 4.08%   |
| SAS  | 1        | 0.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 95       | 56.89%  |
| AMD    | 72       | 43.11%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor             | 7        | 4.19%   |
| Intel Core i5-10400F CPU @ 2.90GHz             | 4        | 2.4%    |
| AMD Ryzen 5 2600X Six-Core Processor           | 4        | 2.4%    |
| Intel Core i7-4790K CPU @ 4.00GHz              | 3        | 1.8%    |
| Intel Core i7-4790 CPU @ 3.60GHz               | 3        | 1.8%    |
| AMD Ryzen 9 5950X 16-Core Processor            | 3        | 1.8%    |
| AMD Ryzen 9 5900X 12-Core Processor            | 3        | 1.8%    |
| AMD Ryzen 7 5700G with Radeon Graphics         | 3        | 1.8%    |
| AMD Ryzen 7 3700X 8-Core Processor             | 3        | 1.8%    |
| AMD Ryzen 5 3600 6-Core Processor              | 3        | 1.8%    |
| Intel Pentium CPU G2020 @ 2.90GHz              | 2        | 1.2%    |
| Intel Core i7-7700K CPU @ 4.20GHz              | 2        | 1.2%    |
| Intel Core i7-6700 CPU @ 3.40GHz               | 2        | 1.2%    |
| Intel Core i7-3770K CPU @ 3.50GHz              | 2        | 1.2%    |
| Intel Core i7-3770 CPU @ 3.40GHz               | 2        | 1.2%    |
| Intel Core i5-8400 CPU @ 2.80GHz               | 2        | 1.2%    |
| Intel Core i5-7500 CPU @ 3.40GHz               | 2        | 1.2%    |
| Intel Core i3-4130 CPU @ 3.40GHz               | 2        | 1.2%    |
| Intel Core i3-10100F CPU @ 3.60GHz             | 2        | 1.2%    |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz           | 2        | 1.2%    |
| AMD Ryzen Threadripper 1950X 16-Core Processor | 2        | 1.2%    |
| AMD Ryzen 9 3900X 12-Core Processor            | 2        | 1.2%    |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics     | 2        | 1.2%    |
| AMD Ryzen 7 5700X 8-Core Processor             | 2        | 1.2%    |
| AMD Ryzen 7 2700X Eight-Core Processor         | 2        | 1.2%    |
| AMD Ryzen 7 2700 Eight-Core Processor          | 2        | 1.2%    |
| AMD Ryzen 5 5600 6-Core Processor              | 2        | 1.2%    |
| AMD Ryzen 5 5500                               | 2        | 1.2%    |
| AMD Ryzen 5 3400G with Radeon Vega Graphics    | 2        | 1.2%    |
| Intel Xeon CPU X3440 @ 2.53GHz                 | 1        | 0.6%    |
| Intel Xeon CPU W3530 @ 2.80GHz                 | 1        | 0.6%    |
| Intel Xeon CPU E5-4627 v4 @ 2.60GHz            | 1        | 0.6%    |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz            | 1        | 0.6%    |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz            | 1        | 0.6%    |
| Intel Xeon CPU E5-2403 0 @ 1.80GHz             | 1        | 0.6%    |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz            | 1        | 0.6%    |
| Intel Xeon CPU E5-1620 v2 @ 3.70GHz            | 1        | 0.6%    |
| Intel Xeon CPU E3-1275 V2 @ 3.50GHz            | 1        | 0.6%    |
| Intel Pentium Gold G5420 CPU @ 3.80GHz         | 1        | 0.6%    |
| Intel Pentium CPU J4205 @ 1.50GHz              | 1        | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i7          | 29       | 17.37%  |
| Intel Core i5          | 25       | 14.97%  |
| AMD Ryzen 5            | 24       | 14.37%  |
| AMD Ryzen 7            | 14       | 8.38%   |
| AMD Ryzen 9            | 10       | 5.99%   |
| Intel Xeon             | 9        | 5.39%   |
| Intel Core i3          | 8        | 4.79%   |
| Other                  | 7        | 4.19%   |
| Intel Pentium          | 6        | 3.59%   |
| Intel Core 2 Duo       | 4        | 2.4%    |
| AMD Ryzen 3            | 4        | 2.4%    |
| AMD Ryzen Threadripper | 3        | 1.8%    |
| AMD FX                 | 3        | 1.8%    |
| Intel Core i9          | 2        | 1.2%    |
| Intel Core 2 Quad      | 2        | 1.2%    |
| Intel Celeron          | 2        | 1.2%    |
| AMD Ryzen 7 PRO        | 2        | 1.2%    |
| AMD Phenom II X2       | 2        | 1.2%    |
| AMD Opteron            | 2        | 1.2%    |
| Intel Pentium Gold     | 1        | 0.6%    |
| AMD Phenom II X6       | 1        | 0.6%    |
| AMD Phenom II X4       | 1        | 0.6%    |
| AMD E1                 | 1        | 0.6%    |
| AMD Athlon II X2       | 1        | 0.6%    |
| AMD Athlon 64 X2       | 1        | 0.6%    |
| AMD A8                 | 1        | 0.6%    |
| AMD A6                 | 1        | 0.6%    |
| AMD A4                 | 1        | 0.6%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 63       | 37.72%  |
| 6      | 40       | 23.95%  |
| 2      | 24       | 14.37%  |
| 8      | 22       | 13.17%  |
| 16     | 8        | 4.79%   |
| 12     | 6        | 3.59%   |
| 10     | 3        | 1.8%    |
| 1      | 1        | 0.6%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 167      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 115      | 68.86%  |
| 1      | 52       | 31.14%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 167      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 81       | 47.93%  |
| 0x08701021 | 8        | 4.73%   |
| 0x306c3    | 7        | 4.14%   |
| 0x906e9    | 5        | 2.96%   |
| 0x0800820d | 5        | 2.96%   |
| 0xa0653    | 4        | 2.37%   |
| 0x306a9    | 4        | 2.37%   |
| 0x010000c8 | 4        | 2.37%   |
| 0x906ed    | 3        | 1.78%   |
| 0x90672    | 3        | 1.78%   |
| 0x0a50000c | 3        | 1.78%   |
| 0x0a201205 | 3        | 1.78%   |
| 0x0a201016 | 3        | 1.78%   |
| 0xa0655    | 2        | 1.18%   |
| 0x906ea    | 2        | 1.18%   |
| 0x506e3    | 2        | 1.18%   |
| 0x406f1    | 2        | 1.18%   |
| 0x206a7    | 2        | 1.18%   |
| 0x0a20120a | 2        | 1.18%   |
| 0x0a201009 | 2        | 1.18%   |
| 0x08001138 | 2        | 1.18%   |
| 0x806ea    | 1        | 0.59%   |
| 0x6fb      | 1        | 0.59%   |
| 0x306f2    | 1        | 0.59%   |
| 0x306e4    | 1        | 0.59%   |
| 0x206d7    | 1        | 0.59%   |
| 0x206d6    | 1        | 0.59%   |
| 0x106e5    | 1        | 0.59%   |
| 0x106a5    | 1        | 0.59%   |
| 0x1067a    | 1        | 0.59%   |
| 0x0a50000d | 1        | 0.59%   |
| 0x0a201204 | 1        | 0.59%   |
| 0x0a201005 | 1        | 0.59%   |
| 0x08701013 | 1        | 0.59%   |
| 0x08600106 | 1        | 0.59%   |
| 0x08600103 | 1        | 0.59%   |
| 0x08001137 | 1        | 0.59%   |
| 0x08001136 | 1        | 0.59%   |
| 0x07030106 | 1        | 0.59%   |
| 0x06000852 | 1        | 0.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 23       | 13.69%  |
| Haswell          | 20       | 11.9%   |
| KabyLake         | 18       | 10.71%  |
| Zen 2            | 15       | 8.93%   |
| IvyBridge        | 13       | 7.74%   |
| Zen+             | 12       | 7.14%   |
| CometLake        | 8        | 4.76%   |
| Zen              | 7        | 4.17%   |
| SandyBridge      | 7        | 4.17%   |
| Skylake          | 6        | 3.57%   |
| Piledriver       | 6        | 3.57%   |
| K10              | 6        | 3.57%   |
| Unknown          | 5        | 2.98%   |
| Penryn           | 4        | 2.38%   |
| Nehalem          | 4        | 2.38%   |
| Broadwell        | 3        | 1.79%   |
| Alderlake Hybrid | 3        | 1.79%   |
| Westmere         | 2        | 1.19%   |
| Core             | 2        | 1.19%   |
| Puma             | 1        | 0.6%    |
| K8 Hammer        | 1        | 0.6%    |
| Goldmont         | 1        | 0.6%    |
| Excavator        | 1        | 0.6%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 93       | 51.96%  |
| AMD                        | 55       | 30.73%  |
| Intel                      | 29       | 16.2%   |
| Matrox Electronics Systems | 2        | 1.12%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 11       | 6.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 8        | 4.47%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7        | 3.91%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 5        | 2.79%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 2.23%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 4        | 2.23%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 2.23%   |
| Intel HD Graphics 630                                                       | 4        | 2.23%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 1.68%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 1.68%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 3        | 1.68%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 3        | 1.68%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 1.68%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 3        | 1.68%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 1.12%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 2        | 1.12%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 1.12%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 2        | 1.12%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 1.12%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 1.12%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 1.12%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 2        | 1.12%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 1.12%   |
| Nvidia GA104 [GeForce RTX 3060]                                             | 2        | 1.12%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 2        | 1.12%   |
| Nvidia G92 [GeForce 9800 GT]                                                | 2        | 1.12%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 2        | 1.12%   |
| Intel HD Graphics 530                                                       | 2        | 1.12%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 1.12%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.12%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.12%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                           | 2        | 1.12%   |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                           | 2        | 1.12%   |
| AMD Renoir                                                                  | 2        | 1.12%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 1.12%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 2        | 1.12%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 1.12%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 1.12%   |
| AMD Caicos PRO [Radeon HD 7450]                                             | 2        | 1.12%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 2        | 1.12%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 89       | 53.29%  |
| 1 x AMD                  | 50       | 29.94%  |
| 1 x Intel                | 21       | 12.57%  |
| 2 x Nvidia               | 1        | 0.6%    |
| 2 x AMD                  | 1        | 0.6%    |
| Nvidia + Matrox          | 1        | 0.6%    |
| Intel + Nvidia           | 1        | 0.6%    |
| Intel + AMD + 1 x Nvidia | 1        | 0.6%    |
| Intel + AMD              | 1        | 0.6%    |
| AMD + Matrox             | 1        | 0.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 89       | 53.29%  |
| Proprietary | 72       | 43.11%  |
| Unknown     | 6        | 3.59%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 74       | 43.27%  |
| 7.01-8.0   | 20       | 11.7%   |
| 1.01-2.0   | 19       | 11.11%  |
| 3.01-4.0   | 17       | 9.94%   |
| 0.51-1.0   | 13       | 7.6%    |
| 5.01-6.0   | 12       | 7.02%   |
| 8.01-16.0  | 7        | 4.09%   |
| 0.01-0.5   | 5        | 2.92%   |
| 16.01-24.0 | 2        | 1.17%   |
| 4.01-5.0   | 1        | 0.58%   |
| 2.01-3.0   | 1        | 0.58%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 41       | 20.5%   |
| Dell                 | 23       | 11.5%   |
| Goldstar             | 18       | 9%      |
| Hewlett-Packard      | 17       | 8.5%    |
| AOC                  | 12       | 6%      |
| Acer                 | 12       | 6%      |
| Philips              | 11       | 5.5%    |
| BenQ                 | 9        | 4.5%    |
| Ancor Communications | 7        | 3.5%    |
| Iiyama               | 6        | 3%      |
| Sony                 | 4        | 2%      |
| ViewSonic            | 3        | 1.5%    |
| ASUSTek Computer     | 3        | 1.5%    |
| Vizio                | 2        | 1%      |
| NEC Computers        | 2        | 1%      |
| LG Electronics       | 2        | 1%      |
| Idek Iiyama          | 2        | 1%      |
| Denver               | 2        | 1%      |
| Xiaomi               | 1        | 0.5%    |
| Vita                 | 1        | 0.5%    |
| Vestel Elektronik    | 1        | 0.5%    |
| Unknown              | 1        | 0.5%    |
| Sunplus              | 1        | 0.5%    |
| STD                  | 1        | 0.5%    |
| Sceptre Tech         | 1        | 0.5%    |
| RTK                  | 1        | 0.5%    |
| QUS                  | 1        | 0.5%    |
| Planar               | 1        | 0.5%    |
| PAR                  | 1        | 0.5%    |
| Panasonic            | 1        | 0.5%    |
| MVD                  | 1        | 0.5%    |
| MSI                  | 1        | 0.5%    |
| Medion               | 1        | 0.5%    |
| Lenovo               | 1        | 0.5%    |
| HKC                  | 1        | 0.5%    |
| Gigabyte Technology  | 1        | 0.5%    |
| Fujitsu Siemens      | 1        | 0.5%    |
| Envision Peripherals | 1        | 0.5%    |
| Eizo                 | 1        | 0.5%    |
| CLB                  | 1        | 0.5%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 3        | 1.42%   |
| AOC Q27G2G4 AOC2702 2560x1440 597x336mm 27.0-inch                      | 3        | 1.42%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch    | 2        | 0.95%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 2        | 0.95%   |
| Samsung Electronics LC27G5xT SAM7079 2560x1440 597x336mm 27.0-inch     | 2        | 0.95%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch      | 2        | 0.95%   |
| Hewlett-Packard 24w HPN3431 1920x1080 527x296mm 23.8-inch              | 2        | 0.95%   |
| Hewlett-Packard 2311 HWP2939 1920x1080 509x286mm 23.0-inch             | 2        | 0.95%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch            | 2        | 0.95%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 2        | 0.95%   |
| Goldstar 22EA53 GSM59A5 1920x1080 477x268mm 21.5-inch                  | 2        | 0.95%   |
| Dell P2719H DEL4184 1920x1080 598x336mm 27.0-inch                      | 2        | 0.95%   |
| AOC Q3277 AOC3277 2560x1440 708x399mm 32.0-inch                        | 2        | 0.95%   |
| Acer VG240Y ACR06BF 1920x1080 527x296mm 23.8-inch                      | 2        | 0.95%   |
| Xiaomi Mi TV XMD00E2 3840x2160 800x450mm 36.1-inch                     | 1        | 0.47%   |
| Vizio V585x-H1 VIZ1039 3840x2160 941x529mm 42.5-inch                   | 1        | 0.47%   |
| Vizio E320-B0 VIZ1007 1366x768 697x392mm 31.5-inch                     | 1        | 0.47%   |
| Vita VT988 VIT03DC 1280x1024 376x301mm 19.0-inch                       | 1        | 0.47%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch             | 1        | 0.47%   |
| ViewSonic VX2439wm VSC3D24 1920x1080 520x290mm 23.4-inch               | 1        | 0.47%   |
| ViewSonic LCD Monitor VSCD62F 1920x1080 620x340mm 27.8-inch            | 1        | 0.47%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 1        | 0.47%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 1        | 0.47%   |
| Sunplus Monitor TV SPVFFFF 1920x1080 376x301mm 19.0-inch               | 1        | 0.47%   |
| STD LCD Monitor STD0001 1920x1080                                      | 1        | 0.47%   |
| Sony TV SNYEE01 1920x1080                                              | 1        | 0.47%   |
| Sony TV SNYC901 1920x1080                                              | 1        | 0.47%   |
| Sony TV SNY7702 1920x1080 708x398mm 32.0-inch                          | 1        | 0.47%   |
| Sony TV *02 SNY9403 1920x1080 1218x685mm 55.0-inch                     | 1        | 0.47%   |
| Sceptre Tech Sceptre E24 SPT099D 1920x1080 521x293mm 23.5-inch         | 1        | 0.47%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 700x390mm 31.5-inch      | 1        | 0.47%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch      | 1        | 0.47%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 607x345mm 27.5-inch      | 1        | 0.47%   |
| Samsung Electronics U28D590 SAM0B81 3840x2160 608x345mm 27.5-inch      | 1        | 0.47%   |
| Samsung Electronics U28D590 SAM0B80 3840x2160 607x345mm 27.5-inch      | 1        | 0.47%   |
| Samsung Electronics T19C300 SAM0A98 1366x768 410x230mm 18.5-inch       | 1        | 0.47%   |
| Samsung Electronics SyncMaster SAM05CC 1920x1080 530x300mm 24.0-inch   | 1        | 0.47%   |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch   | 1        | 0.47%   |
| Samsung Electronics SyncMaster SAM04E6 1920x1080 477x268mm 21.5-inch   | 1        | 0.47%   |
| Samsung Electronics SyncMaster SAM0225 1440x900 410x257mm 19.1-inch    | 1        | 0.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 96       | 50.79%  |
| 3840x2160 (4K)     | 23       | 12.17%  |
| 2560x1440 (QHD)    | 15       | 7.94%   |
| 1920x1200 (WUXGA)  | 10       | 5.29%   |
| 1280x1024 (SXGA)   | 9        | 4.76%   |
| 1680x1050 (WSXGA+) | 8        | 4.23%   |
| 3440x1440          | 4        | 2.12%   |
| 2560x1080          | 4        | 2.12%   |
| 1600x900 (HD+)     | 4        | 2.12%   |
| 1366x768 (WXGA)    | 4        | 2.12%   |
| 1440x900 (WXGA+)   | 3        | 1.59%   |
| 3840x1080          | 2        | 1.06%   |
| 1280x720 (HD)      | 2        | 1.06%   |
| 3840x1200          | 1        | 0.53%   |
| 3600x1200          | 1        | 0.53%   |
| 2288x1287          | 1        | 0.53%   |
| 1360x768           | 1        | 0.53%   |
| Unknown            | 1        | 0.53%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 40       | 20.2%   |
| 27      | 31       | 15.66%  |
| 23      | 24       | 12.12%  |
| 21      | 19       | 9.6%    |
| 31      | 14       | 7.07%   |
| 19      | 12       | 6.06%   |
| 34      | 8        | 4.04%   |
| 22      | 8        | 4.04%   |
| Unknown | 7        | 3.54%   |
| 32      | 4        | 2.02%   |
| 18      | 4        | 2.02%   |
| 46      | 3        | 1.52%   |
| 25      | 3        | 1.52%   |
| 72      | 2        | 1.01%   |
| 36      | 2        | 1.01%   |
| 26      | 2        | 1.01%   |
| 20      | 2        | 1.01%   |
| 17      | 2        | 1.01%   |
| 142     | 1        | 0.51%   |
| 84      | 1        | 0.51%   |
| 69      | 1        | 0.51%   |
| 65      | 1        | 0.51%   |
| 60      | 1        | 0.51%   |
| 55      | 1        | 0.51%   |
| 54      | 1        | 0.51%   |
| 49      | 1        | 0.51%   |
| 48      | 1        | 0.51%   |
| 43      | 1        | 0.51%   |
| 40      | 1        | 0.51%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 80       | 43.24%  |
| 401-500        | 38       | 20.54%  |
| 601-700        | 21       | 11.35%  |
| 701-800        | 14       | 7.57%   |
| 1001-1500      | 9        | 4.86%   |
| 351-400        | 7        | 3.78%   |
| Unknown        | 7        | 3.78%   |
| 1501-2000      | 4        | 2.16%   |
| 301-350        | 2        | 1.08%   |
| More than 2000 | 1        | 0.54%   |
| 801-900        | 1        | 0.54%   |
| 901-1000       | 1        | 0.54%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 127      | 72.57%  |
| 16/10   | 22       | 12.57%  |
| 5/4     | 9        | 5.14%   |
| 21/9    | 8        | 4.57%   |
| Unknown | 5        | 2.86%   |
| 32/9    | 2        | 1.14%   |
| 1.98    | 1        | 0.57%   |
| 1.00    | 1        | 0.57%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 67       | 35.45%  |
| 301-350        | 31       | 16.4%   |
| 351-500        | 26       | 13.76%  |
| 151-200        | 20       | 10.58%  |
| 251-300        | 15       | 7.94%   |
| More than 1000 | 9        | 4.76%   |
| 501-1000       | 9        | 4.76%   |
| Unknown        | 7        | 3.7%    |
| 141-150        | 5        | 2.65%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 110      | 63.22%  |
| 101-120 | 30       | 17.24%  |
| 1-50    | 12       | 6.9%    |
| 121-160 | 11       | 6.32%   |
| Unknown | 7        | 4.02%   |
| 161-240 | 4        | 2.3%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 106      | 63.1%   |
| 2     | 53       | 31.55%  |
| 0     | 6        | 3.57%   |
| 3     | 2        | 1.19%   |
| 4     | 1        | 0.6%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 106      | 41.25%  |
| Intel                           | 80       | 31.13%  |
| Qualcomm Atheros                | 13       | 5.06%   |
| Ralink Technology               | 8        | 3.11%   |
| Broadcom                        | 8        | 3.11%   |
| TP-Link                         | 6        | 2.33%   |
| Aquantia                        | 5        | 1.95%   |
| Ralink                          | 4        | 1.56%   |
| Huawei Technologies             | 4        | 1.56%   |
| Xiaomi                          | 2        | 0.78%   |
| Samsung Electronics             | 2        | 0.78%   |
| ASUSTek Computer                | 2        | 0.78%   |
| ZyXEL Communications            | 1        | 0.39%   |
| Wilocity                        | 1        | 0.39%   |
| VIA Technologies                | 1        | 0.39%   |
| U-Blox                          | 1        | 0.39%   |
| Qualcomm Atheros Communications | 1        | 0.39%   |
| NetGear                         | 1        | 0.39%   |
| Microsoft                       | 1        | 0.39%   |
| Mercucys                        | 1        | 0.39%   |
| MediaTek                        | 1        | 0.39%   |
| Linksys                         | 1        | 0.39%   |
| LG Electronics                  | 1        | 0.39%   |
| Edimax Technology               | 1        | 0.39%   |
| DisplayLink                     | 1        | 0.39%   |
| D-Link System                   | 1        | 0.39%   |
| D-Link                          | 1        | 0.39%   |
| Bose                            | 1        | 0.39%   |
| ASIX Electronics                | 1        | 0.39%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 80       | 26.94%  |
| Intel Ethernet Controller I225-V                                  | 12       | 4.04%   |
| Intel Wi-Fi 6 AX200                                               | 11       | 3.7%    |
| Intel I211 Gigabit Network Connection                             | 11       | 3.7%    |
| Realtek RTL8125 2.5GbE Controller                                 | 8        | 2.69%   |
| Intel Ethernet Connection I217-LM                                 | 7        | 2.36%   |
| Intel Ethernet Connection (2) I219-V                              | 7        | 2.36%   |
| Intel Ethernet Connection (7) I219-V                              | 5        | 1.68%   |
| Intel 82574L Gigabit Network Connection                           | 5        | 1.68%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4        | 1.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4        | 1.35%   |
| Realtek 802.11ac NIC                                              | 4        | 1.35%   |
| Intel Ethernet Connection (14) I219-V                             | 4        | 1.35%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 4        | 1.35%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 4        | 1.35%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 3        | 1.01%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 1.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3        | 1.01%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 1.01%   |
| Intel Wireless-AC 9260                                            | 3        | 1.01%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 1.01%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 1.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 1.01%   |
| Huawei SNE-LX1                                                    | 3        | 1.01%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 0.67%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 2        | 0.67%   |
| TP-Link 802.11ac NIC                                              | 2        | 0.67%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.67%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.67%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 2        | 0.67%   |
| Ralink RT5370 Wireless Adapter                                    | 2        | 0.67%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2        | 0.67%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 2        | 0.67%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 2        | 0.67%   |
| Intel Wireless 8260                                               | 2        | 0.67%   |
| Intel Wireless 7260                                               | 2        | 0.67%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.67%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 0.67%   |
| ZyXEL ZyAIR G-202 802.11bg                                        | 1        | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 31       | 30.69%  |
| Realtek Semiconductor           | 24       | 23.76%  |
| Ralink Technology               | 8        | 7.92%   |
| Broadcom                        | 8        | 7.92%   |
| Qualcomm Atheros                | 7        | 6.93%   |
| TP-Link                         | 6        | 5.94%   |
| Ralink                          | 4        | 3.96%   |
| ASUSTek Computer                | 2        | 1.98%   |
| ZyXEL Communications            | 1        | 0.99%   |
| Wilocity                        | 1        | 0.99%   |
| Qualcomm Atheros Communications | 1        | 0.99%   |
| NetGear                         | 1        | 0.99%   |
| Microsoft                       | 1        | 0.99%   |
| Mercucys                        | 1        | 0.99%   |
| Linksys                         | 1        | 0.99%   |
| LG Electronics                  | 1        | 0.99%   |
| Edimax Technology               | 1        | 0.99%   |
| D-Link System                   | 1        | 0.99%   |
| D-Link                          | 1        | 0.99%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                        | 11       | 10.68%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 4        | 3.88%   |
| Realtek 802.11ac NIC                                       | 4        | 3.88%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter         | 4        | 3.88%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter            | 3        | 2.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 3        | 2.91%   |
| Intel Wireless-AC 9260                                     | 3        | 2.91%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 3        | 2.91%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                     | 2        | 1.94%   |
| TP-Link 802.11ac NIC                                       | 2        | 1.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 2        | 1.94%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter   | 2        | 1.94%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                 | 2        | 1.94%   |
| Ralink RT5370 Wireless Adapter                             | 2        | 1.94%   |
| Ralink RT2870/RT3070 Wireless Adapter                      | 2        | 1.94%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                  | 2        | 1.94%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter           | 2        | 1.94%   |
| Intel Wireless 8260                                        | 2        | 1.94%   |
| Intel Wireless 7260                                        | 2        | 1.94%   |
| ZyXEL ZyAIR G-202 802.11bg                                 | 1        | 0.97%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter         | 1        | 0.97%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                | 1        | 0.97%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                 | 1        | 0.97%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 1        | 0.97%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1        | 0.97%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter    | 1        | 0.97%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                 | 1        | 0.97%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 1        | 0.97%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)  | 1        | 0.97%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                    | 1        | 0.97%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                 | 1        | 0.97%   |
| Realtek 802.11n                                            | 1        | 0.97%   |
| Ralink RT5572 Wireless Adapter                             | 1        | 0.97%   |
| Ralink RT3572 Wireless Adapter                             | 1        | 0.97%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter          | 1        | 0.97%   |
| Ralink MT7601U Wireless Adapter                            | 1        | 0.97%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter     | 1        | 0.97%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                       | 1        | 0.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1        | 0.97%   |
| Qualcomm Atheros AR9271 802.11n                            | 1        | 0.97%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 94       | 50%     |
| Intel                 | 69       | 36.7%   |
| Qualcomm Atheros      | 6        | 3.19%   |
| Aquantia              | 5        | 2.66%   |
| Huawei Technologies   | 4        | 2.13%   |
| Xiaomi                | 2        | 1.06%   |
| Samsung Electronics   | 2        | 1.06%   |
| Broadcom              | 2        | 1.06%   |
| VIA Technologies      | 1        | 0.53%   |
| MediaTek              | 1        | 0.53%   |
| DisplayLink           | 1        | 0.53%   |
| ASIX Electronics      | 1        | 0.53%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 80       | 41.67%  |
| Intel Ethernet Controller I225-V                                  | 12       | 6.25%   |
| Intel I211 Gigabit Network Connection                             | 11       | 5.73%   |
| Realtek RTL8125 2.5GbE Controller                                 | 8        | 4.17%   |
| Intel Ethernet Connection I217-LM                                 | 7        | 3.65%   |
| Intel Ethernet Connection (2) I219-V                              | 7        | 3.65%   |
| Intel Ethernet Connection (7) I219-V                              | 5        | 2.6%    |
| Intel 82574L Gigabit Network Connection                           | 5        | 2.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4        | 2.08%   |
| Intel Ethernet Connection (14) I219-V                             | 4        | 2.08%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 4        | 2.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 1.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 1.56%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 1.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 1.56%   |
| Huawei SNE-LX1                                                    | 3        | 1.56%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 1.04%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 1.04%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 1.04%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 1.04%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1        | 0.52%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.52%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.52%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1        | 0.52%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.52%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.52%   |
| MediaTek N152DL                                                   | 1        | 0.52%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.52%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.52%   |
| Intel Ethernet Connection I218-LM                                 | 1        | 0.52%   |
| Intel Ethernet Connection I217-V                                  | 1        | 0.52%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.52%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.52%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 0.52%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.52%   |
| Huawei E353/E3131                                                 | 1        | 0.52%   |
| DisplayLink Dell Universal Dock D6000                             | 1        | 0.52%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1        | 0.52%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 1        | 0.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 166      | 62.88%  |
| WiFi     | 96       | 36.36%  |
| Modem    | 2        | 0.76%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 120      | 71.01%  |
| WiFi     | 49       | 28.99%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 98       | 58.68%  |
| 2     | 60       | 35.93%  |
| 3     | 7        | 4.19%   |
| 6     | 1        | 0.6%    |
| 4     | 1        | 0.6%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 114      | 67.86%  |
| Yes  | 54       | 32.14%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 27       | 35.53%  |
| Cambridge Silicon Radio         | 23       | 30.26%  |
| Realtek Semiconductor           | 8        | 10.53%  |
| ASUSTek Computer                | 8        | 10.53%  |
| Broadcom                        | 3        | 3.95%   |
| IMC Networks                    | 2        | 2.63%   |
| Edimax Technology               | 2        | 2.63%   |
| TP-Link                         | 1        | 1.32%   |
| Qualcomm Atheros Communications | 1        | 1.32%   |
| Apple                           | 1        | 1.32%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 23       | 30.26%  |
| Intel AX200 Bluetooth                                   | 11       | 14.47%  |
| Realtek Bluetooth Radio                                 | 6        | 7.89%   |
| Intel Bluetooth wireless interface                      | 5        | 6.58%   |
| ASUS ASUS USB-BT500                                     | 4        | 5.26%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 3        | 3.95%   |
| Intel Wireless-AC 3168 Bluetooth                        | 3        | 3.95%   |
| Broadcom BCM20702A0 Bluetooth 4.0                       | 3        | 3.95%   |
| Realtek  Bluetooth 4.2 Adapter                          | 2        | 2.63%   |
| Intel AX201 Bluetooth                                   | 2        | 2.63%   |
| IMC Networks Bluetooth Radio                            | 2        | 2.63%   |
| ASUS Qualcomm Bluetooth 4.1                             | 2        | 2.63%   |
| TP-Link UB500 Adapter                                   | 1        | 1.32%   |
| Qualcomm Atheros  Bluetooth Device                      | 1        | 1.32%   |
| Intel Bluetooth Device                                  | 1        | 1.32%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 1        | 1.32%   |
| Intel AX210 Bluetooth                                   | 1        | 1.32%   |
| Edimax Wi-Fi AC600 Bluetooth4.0 USB Adapter             | 1        | 1.32%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter | 1        | 1.32%   |
| ASUS Bluetooth Device                                   | 1        | 1.32%   |
| ASUS Bluetooth Adapter                                  | 1        | 1.32%   |
| Apple Bluetooth USB Host Controller                     | 1        | 1.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| AMD                      | 94       | 27.81%  |
| Intel                    | 91       | 26.92%  |
| Nvidia                   | 90       | 26.63%  |
| C-Media Electronics      | 6        | 1.78%   |
| GN Netcom                | 5        | 1.48%   |
| JMTek                    | 4        | 1.18%   |
| Creative Labs            | 4        | 1.18%   |
| Kingston Technology      | 3        | 0.89%   |
| Generalplus Technology   | 3        | 0.89%   |
| VIA Technologies         | 2        | 0.59%   |
| Texas Instruments        | 2        | 0.59%   |
| Razer USA                | 2        | 0.59%   |
| M-Audio                  | 2        | 0.59%   |
| KORG                     | 2        | 0.59%   |
| BY EDIFIER               | 2        | 0.59%   |
| Blue Microphones         | 2        | 0.59%   |
| ASUSTek Computer         | 2        | 0.59%   |
| ZOOM                     | 1        | 0.3%    |
| Yamaha                   | 1        | 0.3%    |
| Unknown                  | 1        | 0.3%    |
| TerraTec Electronic      | 1        | 0.3%    |
| Tenx Technology          | 1        | 0.3%    |
| SteelSeries ApS          | 1        | 0.3%    |
| Samson Technologies      | 1        | 0.3%    |
| QinHeng Electronics      | 1        | 0.3%    |
| Philips (or NXP)         | 1        | 0.3%    |
| Nordic Semiconductor ASA | 1        | 0.3%    |
| Microdia                 | 1        | 0.3%    |
| Micro Star International | 1        | 0.3%    |
| Logitech                 | 1        | 0.3%    |
| Lenovo                   | 1        | 0.3%    |
| Hangzhou Worlde          | 1        | 0.3%    |
| Dell                     | 1        | 0.3%    |
| Corsair                  | 1        | 0.3%    |
| Bose                     | 1        | 0.3%    |
| BEHRINGER International  | 1        | 0.3%    |
| Barco Display Systems    | 1        | 0.3%    |
| Astro Gaming             | 1        | 0.3%    |
| Arturia                  | 1        | 0.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 29       | 7.65%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 15       | 3.96%   |
| Nvidia GP107GL High Definition Audio Controller                            | 13       | 3.43%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 11       | 2.9%    |
| AMD Family 17h/19h HD Audio Controller                                     | 11       | 2.9%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10       | 2.64%   |
| Nvidia TU116 High Definition Audio Controller                              | 9        | 2.37%   |
| Intel 200 Series PCH HD Audio                                              | 9        | 2.37%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 9        | 2.37%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8        | 2.11%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 8        | 2.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7        | 1.85%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 7        | 1.85%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 7        | 1.85%   |
| Nvidia GP106 High Definition Audio Controller                              | 6        | 1.58%   |
| Nvidia GP104 High Definition Audio Controller                              | 6        | 1.58%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6        | 1.58%   |
| Nvidia GA104 High Definition Audio Controller                              | 6        | 1.58%   |
| Intel Cannon Lake PCH cAVS                                                 | 6        | 1.58%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 6        | 1.58%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6        | 1.58%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 6        | 1.58%   |
| Nvidia TU104 HD Audio Controller                                           | 5        | 1.32%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 5        | 1.32%   |
| Nvidia High Definition Audio Controller                                    | 4        | 1.06%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4        | 1.06%   |
| Intel Comet Lake PCH cAVS                                                  | 4        | 1.06%   |
| Intel Audio device                                                         | 4        | 1.06%   |
| Intel Alder Lake-S HD Audio Controller                                     | 4        | 1.06%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 4        | 1.06%   |
| Nvidia TU102 High Definition Audio Controller                              | 3        | 0.79%   |
| Nvidia GP108 High Definition Audio Controller                              | 3        | 0.79%   |
| Nvidia GM206 High Definition Audio Controller                              | 3        | 0.79%   |
| Nvidia GF116 High Definition Audio Controller                              | 3        | 0.79%   |
| Nvidia GA106 High Definition Audio Controller                              | 3        | 0.79%   |
| Kingston Technology HyperX 7.1 Audio                                       | 3        | 0.79%   |
| JMTek USB PnP Audio Device                                                 | 3        | 0.79%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3        | 0.79%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 3        | 0.79%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 21       | 21.21%  |
| Corsair             | 20       | 20.2%   |
| G.Skill             | 14       | 14.14%  |
| Crucial             | 9        | 9.09%   |
| Unknown             | 6        | 6.06%   |
| Micron Technology   | 6        | 6.06%   |
| SK hynix            | 4        | 4.04%   |
| Samsung Electronics | 4        | 4.04%   |
| Team                | 3        | 3.03%   |
| Ramaxel Technology  | 2        | 2.02%   |
| PNY                 | 2        | 2.02%   |
| Patriot             | 2        | 2.02%   |
| Unknown             | 2        | 2.02%   |
| Lexar               | 1        | 1.01%   |
| Kingmax             | 1        | 1.01%   |
| Atermiter           | 1        | 1.01%   |
| AMD                 | 1        | 1.01%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 2        | 1.82%   |
| Ramaxel RAM RMR5040ED58E9W1600 4GB DIMM DDR3 1600MT/s    | 2        | 1.82%   |
| Micron RAM 8ATF1G64AZ-2G6E1 8GB DIMM DDR4 2667MT/s       | 2        | 1.82%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s    | 2        | 1.82%   |
| Crucial RAM CT102464BA160B.C16 8192MB DIMM DDR3 1600MT/s | 2        | 1.82%   |
| Corsair RAM CMK32GX4M2Z3600C18 16GB DIMM DDR4 3800MT/s   | 2        | 1.82%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s    | 2        | 1.82%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 2        | 1.82%   |
| Unknown                                                  | 2        | 1.82%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                | 1        | 0.91%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                     | 1        | 0.91%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                 | 1        | 0.91%   |
| Unknown RAM Module 16GB DIMM DDR4 2667MT/s               | 1        | 0.91%   |
| Unknown RAM 3600 C20 Series 32GB DIMM DDR4 3666MT/s      | 1        | 0.91%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s      | 1        | 0.91%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s      | 1        | 0.91%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3000MT/s       | 1        | 0.91%   |
| SK hynix RAM Module 8GB DIMM DDR4 2133MT/s               | 1        | 0.91%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1648MT/s     | 1        | 0.91%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 0.91%   |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s     | 1        | 0.91%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s      | 1        | 0.91%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s      | 1        | 0.91%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s      | 1        | 0.91%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s      | 1        | 0.91%   |
| PNY RAM 8GBF1X08QFHH38-135-K 8GB DIMM DDR4 3200MT/s      | 1        | 0.91%   |
| PNY RAM 8GBF1X08LIII43-12-K 8GB DIMM DDR4 2667MT/s       | 1        | 0.91%   |
| Patriot RAM PSD416G320081 16GB DIMM DDR4 3200MT/s        | 1        | 0.91%   |
| Patriot RAM PSD416G26662 16GB DIMM DDR4 2667MT/s         | 1        | 0.91%   |
| Micron RAM Module 4GB DIMM DDR3 1866MT/s                 | 1        | 0.91%   |
| Micron RAM 9ASF51272PZ-2G3B1 4096MB RIMM DDR4 2400MT/s   | 1        | 0.91%   |
| Micron RAM 8JTF25664AZ-1G4M1 2GB DIMM DDR3 1333MT/s      | 1        | 0.91%   |
| Micron RAM 36ASF4G72PZ-2G3B1 32GB RIMM DDR4 2400MT/s     | 1        | 0.91%   |
| Micron RAM 16JTF1G64AZ-1G6E1 8GB DIMM DDR3 1600MT/s      | 1        | 0.91%   |
| Lexar RAM LD4AU016G-3200ST 16GB DIMM DDR4 3200MT/s       | 1        | 0.91%   |
| Kingston RAM KHX3466C19D4/16G 16GB DIMM DDR4 3467MT/s    | 1        | 0.91%   |
| Kingston RAM KHX3200C18D4/8G 8GB DIMM DDR4 3333MT/s      | 1        | 0.91%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s   | 1        | 0.91%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s        | 1        | 0.91%   |
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 3334MT/s      | 1        | 0.91%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 63       | 67.02%  |
| DDR3    | 22       | 23.4%   |
| SDRAM   | 3        | 3.19%   |
| DDR5    | 2        | 2.13%   |
| DDR2    | 2        | 2.13%   |
| Unknown | 2        | 2.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 90       | 96.77%  |
| SODIMM | 2        | 2.15%   |
| RIMM   | 1        | 1.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 43       | 43%     |
| 16384 | 29       | 29%     |
| 4096  | 16       | 16%     |
| 2048  | 6        | 6%      |
| 32768 | 5        | 5%      |
| 1024  | 1        | 1%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 16       | 15.69%  |
| 1600  | 13       | 12.75%  |
| 2667  | 10       | 9.8%    |
| 1333  | 10       | 9.8%    |
| 3600  | 8        | 7.84%   |
| 2133  | 6        | 5.88%   |
| 2400  | 5        | 4.9%    |
| 3000  | 4        | 3.92%   |
| 3800  | 3        | 2.94%   |
| 3066  | 3        | 2.94%   |
| 2666  | 3        | 2.94%   |
| 1867  | 2        | 1.96%   |
| 1066  | 2        | 1.96%   |
| 6000  | 1        | 0.98%   |
| 5800  | 1        | 0.98%   |
| 4000  | 1        | 0.98%   |
| 3866  | 1        | 0.98%   |
| 3666  | 1        | 0.98%   |
| 3467  | 1        | 0.98%   |
| 3466  | 1        | 0.98%   |
| 3400  | 1        | 0.98%   |
| 3334  | 1        | 0.98%   |
| 3333  | 1        | 0.98%   |
| 3266  | 1        | 0.98%   |
| 2800  | 1        | 0.98%   |
| 2448  | 1        | 0.98%   |
| 2134  | 1        | 0.98%   |
| 1866  | 1        | 0.98%   |
| 1648  | 1        | 0.98%   |
| 800   | 1        | 0.98%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 5        | 35.71%  |
| Seiko Epson         | 2        | 14.29%  |
| Canon               | 2        | 14.29%  |
| Xerox               | 1        | 7.14%   |
| Samsung Electronics | 1        | 7.14%   |
| Kyocera             | 1        | 7.14%   |
| Datamax-O'Neil      | 1        | 7.14%   |
| Brother Industries  | 1        | 7.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Xerox Phaser 3140 and 3155       | 1        | 7.14%   |
| Seiko Epson L3110 Series         | 1        | 7.14%   |
| Seiko Epson L222 Series          | 1        | 7.14%   |
| Samsung M2070 Series             | 1        | 7.14%   |
| Kyocera Mita FS-820              | 1        | 7.14%   |
| HP OfficeJet 5500 series         | 1        | 7.14%   |
| HP LaserJet 1022                 | 1        | 7.14%   |
| HP ENVY 4500 series              | 1        | 7.14%   |
| HP DeskJet D2300                 | 1        | 7.14%   |
| HP DeskJet 3630 series           | 1        | 7.14%   |
| Datamax-O'Neil Datamax E-4304    | 1        | 7.14%   |
| Canon PIXMA MX470 Series         | 1        | 7.14%   |
| Canon LaserShot LBP-1120 Printer | 1        | 7.14%   |
| Brother MFC-J460DW               | 1        | 7.14%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| Canon          | 4        | 66.67%  |
| Seiko Epson    | 1        | 16.67%  |
| Mustek Systems | 1        | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1        | 16.67%  |
| Mustek Systems ScanExpress A3 USB 1200 PRO  | 1        | 16.67%  |
| Canon CanoScan N670U/N676U/LiDE 20          | 1        | 16.67%  |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40      | 1        | 16.67%  |
| Canon CanoScan LiDE 220                     | 1        | 16.67%  |
| Canon CanoScan LiDE 210                     | 1        | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 17       | 38.64%  |
| Microdia                      | 4        | 9.09%   |
| Microsoft                     | 3        | 6.82%   |
| Sunplus Innovation Technology | 2        | 4.55%   |
| KYE Systems (Mouse Systems)   | 2        | 4.55%   |
| Jieli Technology              | 2        | 4.55%   |
| Generalplus Technology        | 2        | 4.55%   |
| Alcor Micro                   | 2        | 4.55%   |
| YGTek                         | 1        | 2.27%   |
| Unknown                       | 1        | 2.27%   |
| Silicon Motion                | 1        | 2.27%   |
| Samsung Electronics           | 1        | 2.27%   |
| Realtek Semiconductor         | 1        | 2.27%   |
| IMC Networks                  | 1        | 2.27%   |
| Hewlett-Packard               | 1        | 2.27%   |
| Cubeternet                    | 1        | 2.27%   |
| Asuscom Network               | 1        | 2.27%   |
| ARC International             | 1        | 2.27%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Logitech Webcam C270                                                | 4        | 9.09%   |
| Logitech HD Pro Webcam C920                                         | 3        | 6.82%   |
| Logitech C920 PRO HD Webcam                                         | 3        | 6.82%   |
| Microdia Webcam Vitade AF                                           | 2        | 4.55%   |
| Microdia Integrated Camera                                          | 2        | 4.55%   |
| Logitech HD Webcam C910                                             | 2        | 4.55%   |
| Jieli USB PHY 2.0                                                   | 2        | 4.55%   |
| Alcor Micro USB 2.0 PC Camera                                       | 2        | 4.55%   |
| YGTek Webcam                                                        | 1        | 2.27%   |
| Unknown HD camera                                                   | 1        | 2.27%   |
| Sunplus SPCA2281 Web Camera                                         | 1        | 2.27%   |
| Sunplus ezcap U3 capture-04                                         | 1        | 2.27%   |
| Silicon Motion 300k Pixel Camera                                    | 1        | 2.27%   |
| Samsung Galaxy series, misc. (MTP mode)                             | 1        | 2.27%   |
| Realtek HK 2M CAM                                                   | 1        | 2.27%   |
| Microsoft MicrosoftÂ LifeCam Studio                                | 1        | 2.27%   |
| Microsoft LifeCam HD-3000                                           | 1        | 2.27%   |
| Microsoft LifeCam Cinema                                            | 1        | 2.27%   |
| Logitech Webcam C310                                                | 1        | 2.27%   |
| Logitech Webcam C170                                                | 1        | 2.27%   |
| Logitech QuickCam Pro for Notebooks                                 | 1        | 2.27%   |
| Logitech C922 Pro Stream Webcam                                     | 1        | 2.27%   |
| Logitech BRIO                                                       | 1        | 2.27%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera                          | 1        | 2.27%   |
| KYE Systems (Mouse Systems) eFace 2025                              | 1        | 2.27%   |
| IMC Networks UVC VGA Webcam                                         | 1        | 2.27%   |
| HP Webcam 1300                                                      | 1        | 2.27%   |
| Generalplus WEB CAM                                                 | 1        | 2.27%   |
| Generalplus 808 Camera                                              | 1        | 2.27%   |
| Cubeternet EtronTech CMOS based eSP570 WebCam [Onyx Titanium TC101] | 1        | 2.27%   |
| Asuscom Network Depstech webcam                                     | 1        | 2.27%   |
| ARC International Camera                                            | 1        | 2.27%   |

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
| 0     | 133      | 79.17%  |
| 1     | 30       | 17.86%  |
| 2     | 4        | 2.38%   |
| 3     | 1        | 0.6%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 12       | 31.58%  |
| Graphics card            | 8        | 21.05%  |
| Unassigned class         | 6        | 15.79%  |
| Multimedia controller    | 3        | 7.89%   |
| Chipcard                 | 3        | 7.89%   |
| Fingerprint reader       | 2        | 5.26%   |
| Sound                    | 1        | 2.63%   |
| Net/ethernet             | 1        | 2.63%   |
| Communication controller | 1        | 2.63%   |
| Bluetooth                | 1        | 2.63%   |

