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

Total: 189

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
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
| 5.15.0-43-generic          | 14       | 9.03%   |
| 5.15.0-48-generic          | 13       | 8.39%   |
| 5.15.0-46-generic          | 12       | 7.74%   |
| 5.15.0-27-generic          | 12       | 7.74%   |
| 5.15.0-47-generic          | 11       | 7.1%    |
| 5.15.0-40-generic          | 11       | 7.1%    |
| 5.15.0-41-generic          | 10       | 6.45%   |
| 5.15.0-52-generic          | 7        | 4.52%   |
| 5.15.0-50-generic          | 7        | 4.52%   |
| 5.15.0-30-generic          | 6        | 3.87%   |
| 5.15.0-48-lowlatency       | 5        | 3.23%   |
| 5.15.0-25-generic          | 5        | 3.23%   |
| 5.15.0-37-generic          | 4        | 2.58%   |
| 5.15.0-33-generic          | 4        | 2.58%   |
| 5.15.0-27-lowlatency       | 3        | 1.94%   |
| 5.15.0-47-lowlatency       | 2        | 1.29%   |
| 5.15.0-39-generic          | 2        | 1.29%   |
| 6.0.1-060001-generic       | 1        | 0.65%   |
| 5.4.0-122-generic          | 1        | 0.65%   |
| 5.19.12-xanmod1            | 1        | 0.65%   |
| 5.18.4-xanmod1             | 1        | 0.65%   |
| 5.18.4-vitodoc             | 1        | 0.65%   |
| 5.18.12-051812-generic     | 1        | 0.65%   |
| 5.18.10-051810-generic     | 1        | 0.65%   |
| 5.17.6-051706-generic      | 1        | 0.65%   |
| 5.17.14-xanmod1            | 1        | 0.65%   |
| 5.17.0-12.1-liquorix-amd64 | 1        | 0.65%   |
| 5.17.0-1017-oem            | 1        | 0.65%   |
| 5.17.0-051700-generic      | 1        | 0.65%   |
| 5.16.0-051600rc3-generic   | 1        | 0.65%   |
| 5.15.13-051513-generic     | 1        | 0.65%   |
| 5.15.0-53-generic          | 1        | 0.65%   |
| 5.15.0-52-lowlatency       | 1        | 0.65%   |
| 5.15.0-50-lowlatency       | 1        | 0.65%   |
| 5.15.0-46-lowlatency       | 1        | 0.65%   |
| 5.15.0-43-lowlatency       | 1        | 0.65%   |
| 5.15.0-37-lowlatency       | 1        | 0.65%   |
| 5.15.0-35-lowlatency       | 1        | 0.65%   |
| 5.15.0-35-generic          | 1        | 0.65%   |
| 5.15.0-30-lowlatency       | 1        | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 132      | 89.8%   |
| 5.17.0  | 3        | 2.04%   |
| 5.18.4  | 2        | 1.36%   |
| 6.0.1   | 1        | 0.68%   |
| 5.4.0   | 1        | 0.68%   |
| 5.19.12 | 1        | 0.68%   |
| 5.18.12 | 1        | 0.68%   |
| 5.18.10 | 1        | 0.68%   |
| 5.17.6  | 1        | 0.68%   |
| 5.17.14 | 1        | 0.68%   |
| 5.16.0  | 1        | 0.68%   |
| 5.15.13 | 1        | 0.68%   |
| 5.13.0  | 1        | 0.68%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 133      | 90.48%  |
| 5.17    | 5        | 3.4%    |
| 5.18    | 4        | 2.72%   |
| 6.0     | 1        | 0.68%   |
| 5.4     | 1        | 0.68%   |
| 5.19    | 1        | 0.68%   |
| 5.16    | 1        | 0.68%   |
| 5.13    | 1        | 0.68%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 145      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| KDE5 | 145      | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 139      | 95.86%  |
| Wayland | 4        | 2.76%   |
| Tty     | 2        | 1.38%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 102      | 69.39%  |
| Unknown | 34       | 23.13%  |
| GDM3    | 7        | 4.76%   |
| LightDM | 4        | 2.72%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 65       | 44.83%  |
| it_IT | 9        | 6.21%   |
| fr_FR | 9        | 6.21%   |
| de_DE | 9        | 6.21%   |
| ru_RU | 8        | 5.52%   |
| en_GB | 7        | 4.83%   |
| pt_BR | 5        | 3.45%   |
| en_AU | 5        | 3.45%   |
| pl_PL | 3        | 2.07%   |
| en_CA | 3        | 2.07%   |
| nl_NL | 2        | 1.38%   |
| es_ES | 2        | 1.38%   |
| en_ZA | 2        | 1.38%   |
| en_PH | 2        | 1.38%   |
| sl_SI | 1        | 0.69%   |
| fr_BE | 1        | 0.69%   |
| es_CO | 1        | 0.69%   |
| es_AR | 1        | 0.69%   |
| en_NZ | 1        | 0.69%   |
| en_IN | 1        | 0.69%   |
| en_IL | 1        | 0.69%   |
| en_AG | 1        | 0.69%   |
| el_GR | 1        | 0.69%   |
| de_LU | 1        | 0.69%   |
| de_CH | 1        | 0.69%   |
| de_AT | 1        | 0.69%   |
| cs_CZ | 1        | 0.69%   |
| C     | 1        | 0.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 88       | 60.27%  |
| EFI  | 58       | 39.73%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 126      | 86.9%   |
| Btrfs   | 10       | 6.9%    |
| Overlay | 7        | 4.83%   |
| Xfs     | 1        | 0.69%   |
| Ext3    | 1        | 0.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 76       | 51.01%  |
| Unknown | 64       | 42.95%  |
| MBR     | 9        | 6.04%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 126      | 85.14%  |
| Yes       | 22       | 14.86%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 85       | 58.62%  |
| Yes       | 60       | 41.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 42       | 28.97%  |
| Gigabyte Technology | 26       | 17.93%  |
| MSI                 | 22       | 15.17%  |
| ASRock              | 13       | 8.97%   |
| Dell                | 9        | 6.21%   |
| Lenovo              | 7        | 4.83%   |
| Hewlett-Packard     | 6        | 4.14%   |
| Supermicro          | 3        | 2.07%   |
| Shuttle             | 2        | 1.38%   |
| Fujitsu             | 2        | 1.38%   |
| Biostar             | 2        | 1.38%   |
| Apple               | 2        | 1.38%   |
| Acer                | 2        | 1.38%   |
| Positivo            | 1        | 0.69%   |
| Pegatron            | 1        | 0.69%   |
| OEM                 | 1        | 0.69%   |
| JWIPC               | 1        | 0.69%   |
| Huanan              | 1        | 0.69%   |
| AZW                 | 1        | 0.69%   |
| ABIT                | 1        | 0.69%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Desktops | Percent |
|-----------------------------------------|----------|---------|
| ASUS All Series                         | 5        | 3.45%   |
| Gigabyte B450M DS3H                     | 3        | 2.07%   |
| ASUS ROG STRIX B550-F GAMING            | 3        | 2.07%   |
| Supermicro SKAGIT09                     | 2        | 1.38%   |
| MSI MS-7C56                             | 2        | 1.38%   |
| MSI MS-7B86                             | 2        | 1.38%   |
| MSI MS-7B84                             | 2        | 1.38%   |
| MSI MS-7B79                             | 2        | 1.38%   |
| Gigabyte X570 GAMING X                  | 2        | 1.38%   |
| Gigabyte B450 I AORUS PRO WIFI          | 2        | 1.38%   |
| ASUS ROG ZENITH EXTREME                 | 2        | 1.38%   |
| ASUS ROG STRIX B550-I GAMING            | 2        | 1.38%   |
| Supermicro X8ST3                        | 1        | 0.69%   |
| Shuttle SH61R                           | 1        | 0.69%   |
| Shuttle NC01U                           | 1        | 0.69%   |
| Positivo POS-PARS760GCD                 | 1        | 0.69%   |
| Pegatron p6740la                        | 1        | 0.69%   |
| OEM G41 775 ICH7 8712                   | 1        | 0.69%   |
| MSI MS-7D54                             | 1        | 0.69%   |
| MSI MS-7D09                             | 1        | 0.69%   |
| MSI MS-7C95                             | 1        | 0.69%   |
| MSI MS-7C80                             | 1        | 0.69%   |
| MSI MS-7C37                             | 1        | 0.69%   |
| MSI MS-7B98                             | 1        | 0.69%   |
| MSI MS-7B89                             | 1        | 0.69%   |
| MSI MS-7A78                             | 1        | 0.69%   |
| MSI MS-7A40                             | 1        | 0.69%   |
| MSI MS-7A34                             | 1        | 0.69%   |
| MSI MS-7A21                             | 1        | 0.69%   |
| MSI MS-7996                             | 1        | 0.69%   |
| MSI MS-7916                             | 1        | 0.69%   |
| MSI MS-7693                             | 1        | 0.69%   |
| Lenovo ThinkCentre M90p 5498A2U         | 1        | 0.69%   |
| Lenovo ThinkCentre M83 10AM000UUS       | 1        | 0.69%   |
| Lenovo ThinkCentre M83 10AHS2XB00       | 1        | 0.69%   |
| Lenovo ThinkCentre M79 10JAS01500       | 1        | 0.69%   |
| Lenovo ThinkCentre A70 7844H9G          | 1        | 0.69%   |
| Lenovo IdeaCentre 510S-08IKL 90GB00DLGE | 1        | 0.69%   |
| Lenovo H50-50 90B60068IX                | 1        | 0.69%   |
| JWIPC BF24                              | 1        | 0.69%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUS ROG                | 12       | 8.28%   |
| ASUS TUF                | 6        | 4.14%   |
| ASUS PRIME              | 6        | 4.14%   |
| Lenovo ThinkCentre      | 5        | 3.45%   |
| Dell OptiPlex           | 5        | 3.45%   |
| ASUS All                | 5        | 3.45%   |
| Gigabyte X570           | 3        | 2.07%   |
| Gigabyte B450M          | 3        | 2.07%   |
| ASUS M5A78L-M           | 3        | 2.07%   |
| Supermicro SKAGIT09     | 2        | 1.38%   |
| MSI MS-7C56             | 2        | 1.38%   |
| MSI MS-7B86             | 2        | 1.38%   |
| MSI MS-7B84             | 2        | 1.38%   |
| MSI MS-7B79             | 2        | 1.38%   |
| HP ProDesk              | 2        | 1.38%   |
| Gigabyte H410M          | 2        | 1.38%   |
| Gigabyte B450           | 2        | 1.38%   |
| Fujitsu ESPRIMO         | 2        | 1.38%   |
| Dell Precision          | 2        | 1.38%   |
| ASRock B550             | 2        | 1.38%   |
| ASRock A320M-HDV        | 2        | 1.38%   |
| Supermicro X8ST3        | 1        | 0.69%   |
| Shuttle SH61R           | 1        | 0.69%   |
| Shuttle NC01U           | 1        | 0.69%   |
| Positivo POS-PARS760GCD | 1        | 0.69%   |
| Pegatron p6740la        | 1        | 0.69%   |
| OEM G41                 | 1        | 0.69%   |
| MSI MS-7D54             | 1        | 0.69%   |
| MSI MS-7D09             | 1        | 0.69%   |
| MSI MS-7C95             | 1        | 0.69%   |
| MSI MS-7C80             | 1        | 0.69%   |
| MSI MS-7C37             | 1        | 0.69%   |
| MSI MS-7B98             | 1        | 0.69%   |
| MSI MS-7B89             | 1        | 0.69%   |
| MSI MS-7A78             | 1        | 0.69%   |
| MSI MS-7A40             | 1        | 0.69%   |
| MSI MS-7A34             | 1        | 0.69%   |
| MSI MS-7A21             | 1        | 0.69%   |
| MSI MS-7996             | 1        | 0.69%   |
| MSI MS-7916             | 1        | 0.69%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 23       | 15.86%  |
| 2020 | 21       | 14.48%  |
| 2019 | 18       | 12.41%  |
| 2021 | 11       | 7.59%   |
| 2013 | 10       | 6.9%    |
| 2017 | 9        | 6.21%   |
| 2014 | 9        | 6.21%   |
| 2016 | 8        | 5.52%   |
| 2012 | 8        | 5.52%   |
| 2011 | 8        | 5.52%   |
| 2015 | 6        | 4.14%   |
| 2010 | 6        | 4.14%   |
| 2022 | 2        | 1.38%   |
| 2009 | 2        | 1.38%   |
| 2008 | 2        | 1.38%   |
| 2007 | 2        | 1.38%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 145      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 144      | 99.31%  |
| Enabled  | 1        | 0.69%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 145      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 47       | 32.19%  |
| 32.01-64.0  | 43       | 29.45%  |
| 8.01-16.0   | 22       | 15.07%  |
| 4.01-8.0    | 11       | 7.53%   |
| 64.01-256.0 | 10       | 6.85%   |
| 3.01-4.0    | 9        | 6.16%   |
| 24.01-32.0  | 4        | 2.74%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 42       | 27.45%  |
| 4.01-8.0   | 36       | 23.53%  |
| 3.01-4.0   | 30       | 19.61%  |
| 1.01-2.0   | 27       | 17.65%  |
| 8.01-16.0  | 14       | 9.15%   |
| 0.51-1.0   | 3        | 1.96%   |
| 32.01-64.0 | 1        | 0.65%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 46       | 31.29%  |
| 1      | 38       | 25.85%  |
| 3      | 30       | 20.41%  |
| 4      | 14       | 9.52%   |
| 5      | 11       | 7.48%   |
| 6      | 5        | 3.4%    |
| 11     | 1        | 0.68%   |
| 9      | 1        | 0.68%   |
| 7      | 1        | 0.68%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 84       | 57.53%  |
| Yes       | 62       | 42.47%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 144      | 99.31%  |
| No        | 1        | 0.69%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 80       | 54.79%  |
| No        | 66       | 45.21%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 82       | 56.55%  |
| Yes       | 63       | 43.45%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 28       | 19.31%  |
| Germany      | 14       | 9.66%   |
| Italy        | 11       | 7.59%   |
| Brazil       | 10       | 6.9%    |
| France       | 9        | 6.21%   |
| UK           | 8        | 5.52%   |
| Russia       | 8        | 5.52%   |
| Poland       | 7        | 4.83%   |
| Netherlands  | 4        | 2.76%   |
| Australia    | 4        | 2.76%   |
| Spain        | 3        | 2.07%   |
| Switzerland  | 2        | 1.38%   |
| South Africa | 2        | 1.38%   |
| Slovenia     | 2        | 1.38%   |
| Philippines  | 2        | 1.38%   |
| New Zealand  | 2        | 1.38%   |
| India        | 2        | 1.38%   |
| Canada       | 2        | 1.38%   |
| Bulgaria     | 2        | 1.38%   |
| Belgium      | 2        | 1.38%   |
| Austria      | 2        | 1.38%   |
| Argentina    | 2        | 1.38%   |
| Ukraine      | 1        | 0.69%   |
| Turkey       | 1        | 0.69%   |
| Thailand     | 1        | 0.69%   |
| Sweden       | 1        | 0.69%   |
| Serbia       | 1        | 0.69%   |
| Portugal     | 1        | 0.69%   |
| Malta        | 1        | 0.69%   |
| Malaysia     | 1        | 0.69%   |
| Luxembourg   | 1        | 0.69%   |
| Israel       | 1        | 0.69%   |
| Iran         | 1        | 0.69%   |
| Greece       | 1        | 0.69%   |
| Ecuador      | 1        | 0.69%   |
| Czechia      | 1        | 0.69%   |
| Colombia     | 1        | 0.69%   |
| Belarus      | 1        | 0.69%   |
| Armenia      | 1        | 0.69%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Rio de Janeiro         | 3        | 2.04%   |
| Moscow                 | 3        | 2.04%   |
| Wroclaw                | 2        | 1.36%   |
| Washington             | 2        | 1.36%   |
| Vienna                 | 2        | 1.36%   |
| Milan                  | 2        | 1.36%   |
| Dallas                 | 2        | 1.36%   |
| Canberra               | 2        | 1.36%   |
| Brasília              | 2        | 1.36%   |
| Bougival               | 2        | 1.36%   |
| Berlin                 | 2        | 1.36%   |
| Zaandam                | 1        | 0.68%   |
| Yerevan                | 1        | 0.68%   |
| Whangarei              | 1        | 0.68%   |
| Wembley                | 1        | 0.68%   |
| Waukee                 | 1        | 0.68%   |
| Vrhnika                | 1        | 0.68%   |
| Vladivostok            | 1        | 0.68%   |
| Vitebsk                | 1        | 0.68%   |
| Villa Nueva            | 1        | 0.68%   |
| Varna                  | 1        | 0.68%   |
| Valencia               | 1        | 0.68%   |
| Ustron                 | 1        | 0.68%   |
| Union City             | 1        | 0.68%   |
| Turin                  | 1        | 0.68%   |
| Torun                  | 1        | 0.68%   |
| Tholey                 | 1        | 0.68%   |
| Therwil                | 1        | 0.68%   |
| Templeton              | 1        | 0.68%   |
| Tehran                 | 1        | 0.68%   |
| Syeverodonets'k        | 1        | 0.68%   |
| Sydney                 | 1        | 0.68%   |
| Sunbury-on-Thames      | 1        | 0.68%   |
| St Petersburg          | 1        | 0.68%   |
| Southport              | 1        | 0.68%   |
| Sofia                  | 1        | 0.68%   |
| Sliema                 | 1        | 0.68%   |
| Sedziszow Malopolski   | 1        | 0.68%   |
| Savignano sul Rubicone | 1        | 0.68%   |
| Saskatoon              | 1        | 0.68%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 47       | 89     | 16.15%  |
| Samsung Electronics         | 47       | 73     | 16.15%  |
| WDC                         | 46       | 70     | 15.81%  |
| Kingston                    | 25       | 31     | 8.59%   |
| Toshiba                     | 19       | 22     | 6.53%   |
| SanDisk                     | 13       | 14     | 4.47%   |
| Hitachi                     | 13       | 13     | 4.47%   |
| Crucial                     | 12       | 16     | 4.12%   |
| Patriot                     | 5        | 7      | 1.72%   |
| Intel                       | 5        | 5      | 1.72%   |
| A-DATA Technology           | 4        | 5      | 1.37%   |
| Transcend                   | 3        | 4      | 1.03%   |
| Phison                      | 3        | 3      | 1.03%   |
| Lexar                       | 3        | 3      | 1.03%   |
| HGST                        | 3        | 4      | 1.03%   |
| China                       | 3        | 4      | 1.03%   |
| Unknown                     | 2        | 2      | 0.69%   |
| PNY                         | 2        | 3      | 0.69%   |
| Phison Electronics          | 2        | 2      | 0.69%   |
| KODAK                       | 2        | 2      | 0.69%   |
| Intenso                     | 2        | 2      | 0.69%   |
| Emtec                       | 2        | 2      | 0.69%   |
| XPG                         | 1        | 1      | 0.34%   |
| Verbatim                    | 1        | 1      | 0.34%   |
| USB3.0                      | 1        | 1      | 0.34%   |
| Smartbuy                    | 1        | 1      | 0.34%   |
| SK hynix                    | 1        | 2      | 0.34%   |
| Realtek Semiconductor       | 1        | 1      | 0.34%   |
| Plextor                     | 1        | 1      | 0.34%   |
| OCZ                         | 1        | 1      | 0.34%   |
| Micron/Crucial Technology   | 1        | 1      | 0.34%   |
| Micron Technology           | 1        | 1      | 0.34%   |
| Maxtor                      | 1        | 1      | 0.34%   |
| KIOXIA-EXCERIA              | 1        | 1      | 0.34%   |
| KIOXIA                      | 1        | 1      | 0.34%   |
| Kingston Technology Company | 1        | 1      | 0.34%   |
| KingFast                    | 1        | 1      | 0.34%   |
| JMicron Technology          | 1        | 1      | 0.34%   |
| INNOVATION IT               | 1        | 1      | 0.34%   |
| INDMEM                      | 1        | 1      | 0.34%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 7        | 2.03%   |
| Seagate ST4000DM004-2CV104 4TB                      | 6        | 1.74%   |
| Toshiba DT01ACA100 1TB                              | 4        | 1.16%   |
| SanDisk NVMe SSD Drive 500GB                        | 4        | 1.16%   |
| Samsung NVMe SSD Drive 500GB                        | 4        | 1.16%   |
| WDC WD10EZEX-22MFCA0 1TB                            | 3        | 0.87%   |
| Samsung SSD 870 EVO 1TB                             | 3        | 0.87%   |
| Samsung SSD 860 EVO 1TB                             | 3        | 0.87%   |
| Samsung SSD 850 EVO 500GB                           | 3        | 0.87%   |
| Samsung HD103SI 1TB                                 | 3        | 0.87%   |
| Kingston SA2000M81000G 1TB                          | 3        | 0.87%   |
| Hitachi HTS547550A9E384 500GB                       | 3        | 0.87%   |
| Crucial CT500MX500SSD1 500GB                        | 3        | 0.87%   |
| Crucial CT240BX500SSD1 240GB                        | 3        | 0.87%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 2        | 0.58%   |
| WDC WD5000AADS-00S9B0 500GB                         | 2        | 0.58%   |
| WDC WD40EFAX-68JH4N1 4TB                            | 2        | 0.58%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 2        | 0.58%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 2        | 0.58%   |
| Toshiba HDWD130 3TB                                 | 2        | 0.58%   |
| Toshiba HDWD110 1TB                                 | 2        | 0.58%   |
| Seagate ST4000VN008-2DR166 4TB                      | 2        | 0.58%   |
| Seagate ST2000VM003-1CT164 2TB                      | 2        | 0.58%   |
| Seagate ST2000DM008-2FR102 2TB                      | 2        | 0.58%   |
| Seagate ST2000DM006-2DM164 2TB                      | 2        | 0.58%   |
| Seagate ST1000DM003-1SB102 1TB                      | 2        | 0.58%   |
| Seagate Expansion Desk 8TB                          | 2        | 0.58%   |
| Samsung SSD 980 500GB                               | 2        | 0.58%   |
| Samsung SSD 980 1TB                                 | 2        | 0.58%   |
| Samsung SSD 970 EVO Plus 2TB                        | 2        | 0.58%   |
| Samsung SSD 860 EVO 500GB                           | 2        | 0.58%   |
| Samsung SSD 850 EVO 120GB                           | 2        | 0.58%   |
| Samsung SSD 840 PRO Series 128GB                    | 2        | 0.58%   |
| Samsung PSSD T7 1TB                                 | 2        | 0.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 2        | 0.58%   |
| Phison PCIe SSD 512GB                               | 2        | 0.58%   |
| Patriot Burst 120GB SSD                             | 2        | 0.58%   |
| KODAK SSD X100 480GB                                | 2        | 0.58%   |
| Kingston SV300S37A120G 120GB SSD                    | 2        | 0.58%   |
| Kingston SA400S37120G 120GB SSD                     | 2        | 0.58%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 45       | 82     | 34.62%  |
| WDC                 | 42       | 56     | 32.31%  |
| Toshiba             | 16       | 18     | 12.31%  |
| Hitachi             | 13       | 13     | 10%     |
| Samsung Electronics | 8        | 9      | 6.15%   |
| HGST                | 3        | 4      | 2.31%   |
| USB3.0              | 1        | 1      | 0.77%   |
| JMicron Technology  | 1        | 1      | 0.77%   |
| IET                 | 1        | 1      | 0.77%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 27       | 36     | 23.68%  |
| Kingston            | 20       | 22     | 17.54%  |
| Crucial             | 10       | 12     | 8.77%   |
| WDC                 | 8        | 10     | 7.02%   |
| SanDisk             | 7        | 7      | 6.14%   |
| Patriot             | 5        | 7      | 4.39%   |
| Toshiba             | 3        | 3      | 2.63%   |
| Lexar               | 3        | 3      | 2.63%   |
| Intel               | 3        | 3      | 2.63%   |
| China               | 3        | 4      | 2.63%   |
| Transcend           | 2        | 2      | 1.75%   |
| PNY                 | 2        | 3      | 1.75%   |
| KODAK               | 2        | 2      | 1.75%   |
| A-DATA Technology   | 2        | 3      | 1.75%   |
| Verbatim            | 1        | 1      | 0.88%   |
| Smartbuy            | 1        | 1      | 0.88%   |
| Plextor             | 1        | 1      | 0.88%   |
| OCZ                 | 1        | 1      | 0.88%   |
| Micron Technology   | 1        | 1      | 0.88%   |
| Maxtor              | 1        | 1      | 0.88%   |
| KIOXIA-EXCERIA      | 1        | 1      | 0.88%   |
| KingFast            | 1        | 1      | 0.88%   |
| Intenso             | 1        | 1      | 0.88%   |
| INNOVATION IT       | 1        | 1      | 0.88%   |
| INDMEM              | 1        | 1      | 0.88%   |
| Hewlett-Packard     | 1        | 1      | 0.88%   |
| GOODRAM             | 1        | 1      | 0.88%   |
| Drevo               | 1        | 1      | 0.88%   |
| Apple               | 1        | 1      | 0.88%   |
| Apacer              | 1        | 1      | 0.88%   |
| Aireye              | 1        | 1      | 0.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 99       | 185    | 39.76%  |
| SSD     | 96       | 134    | 38.55%  |
| NVMe    | 49       | 82     | 19.68%  |
| Unknown | 4        | 4      | 1.61%   |
| MMC     | 1        | 1      | 0.4%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 133      | 303    | 67.86%  |
| NVMe | 49       | 82     | 25%     |
| SAS  | 13       | 20     | 6.63%   |
| MMC  | 1        | 1      | 0.51%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 98       | 150    | 45.37%  |
| 0.51-1.0   | 53       | 75     | 24.54%  |
| 1.01-2.0   | 25       | 32     | 11.57%  |
| 3.01-4.0   | 20       | 37     | 9.26%   |
| 2.01-3.0   | 9        | 11     | 4.17%   |
| 4.01-10.0  | 9        | 12     | 4.17%   |
| 10.01-20.0 | 2        | 2      | 0.93%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 28       | 18.67%  |
| 1001-2000      | 27       | 18%     |
| More than 3000 | 25       | 16.67%  |
| 2001-3000      | 22       | 14.67%  |
| 101-250        | 20       | 13.33%  |
| 251-500        | 18       | 12%     |
| 1-20           | 5        | 3.33%   |
| 51-100         | 4        | 2.67%   |
| Unknown        | 1        | 0.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 23       | 15.23%  |
| 1-20           | 22       | 14.57%  |
| 501-1000       | 21       | 13.91%  |
| 251-500        | 19       | 12.58%  |
| 51-100         | 18       | 11.92%  |
| 1001-2000      | 14       | 9.27%   |
| More than 3000 | 13       | 8.61%   |
| 21-50          | 12       | 7.95%   |
| 2001-3000      | 8        | 5.3%    |
| Unknown        | 1        | 0.66%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| WDC WD5000AVVS-63M8B0 500GB              | 1        | 1      | 5.56%   |
| WDC WD10EZEX-22MFCA0 1TB                 | 1        | 1      | 5.56%   |
| WDC WD10EZEX-08M2NA0 1TB                 | 1        | 1      | 5.56%   |
| Seagate ST500LT012-9WS142 500GB          | 1        | 1      | 5.56%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 1        | 1      | 5.56%   |
| Seagate ST500DM002-1BD142 500GB          | 1        | 1      | 5.56%   |
| Seagate ST3160827AS 160GB                | 1        | 1      | 5.56%   |
| Seagate ST31500341AS 1TB                 | 1        | 2      | 5.56%   |
| Seagate ST31000524AS 1TB                 | 1        | 2      | 5.56%   |
| Seagate ST1000DM003-1SB102 1TB           | 1        | 1      | 5.56%   |
| Seagate ST1000DM003-1CH162 1TB           | 1        | 1      | 5.56%   |
| Samsung Electronics SSD 870 EVO 1TB      | 1        | 1      | 5.56%   |
| Samsung Electronics SSD 840 Series 250GB | 1        | 1      | 5.56%   |
| Samsung Electronics HM321HI 320GB        | 1        | 1      | 5.56%   |
| Samsung Electronics HD103SI 1TB          | 1        | 1      | 5.56%   |
| Hitachi HTS547550A9E384 500GB            | 1        | 1      | 5.56%   |
| Hitachi HDP725050GLA360 500GB            | 1        | 1      | 5.56%   |
| Hitachi HCT721010SLA360 1TB              | 1        | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 7        | 10     | 41.18%  |
| Samsung Electronics | 4        | 4      | 23.53%  |
| WDC                 | 3        | 3      | 17.65%  |
| Hitachi             | 3        | 3      | 17.65%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 7        | 10     | 46.67%  |
| WDC                 | 3        | 3      | 20%     |
| Hitachi             | 3        | 3      | 20%     |
| Samsung Electronics | 2        | 2      | 13.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 14       | 18     | 87.5%   |
| SSD  | 2        | 2      | 12.5%   |

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
| Detected | 77       | 198    | 46.39%  |
| Works    | 72       | 186    | 43.37%  |
| Malfunc  | 16       | 20     | 9.64%   |
| Failed   | 1        | 2      | 0.6%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 77       | 34.22%  |
| AMD                         | 67       | 29.78%  |
| Samsung Electronics         | 21       | 9.33%   |
| ASMedia Technology          | 10       | 4.44%   |
| SanDisk                     | 9        | 4%      |
| Kingston Technology Company | 8        | 3.56%   |
| Phison Electronics          | 6        | 2.67%   |
| JMicron Technology          | 5        | 2.22%   |
| Micron/Crucial Technology   | 4        | 1.78%   |
| Seagate Technology          | 3        | 1.33%   |
| ADATA Technology            | 3        | 1.33%   |
| Marvell Technology Group    | 2        | 0.89%   |
| LSI Logic / Symbios Logic   | 2        | 0.89%   |
| KIOXIA                      | 2        | 0.89%   |
| VIA Technologies            | 1        | 0.44%   |
| Unknown                     | 1        | 0.44%   |
| SK hynix                    | 1        | 0.44%   |
| Silicon Motion              | 1        | 0.44%   |
| Silicon Image               | 1        | 0.44%   |
| Realtek Semiconductor       | 1        | 0.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 39       | 13.93%  |
| AMD 400 Series Chipset SATA Controller                                         | 19       | 6.79%   |
| AMD 500 Series Chipset SATA Controller                                         | 14       | 5%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 13       | 4.64%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 10       | 3.57%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 9        | 3.21%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 8        | 2.86%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 7        | 2.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 6        | 2.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 6        | 2.14%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5        | 1.79%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 5        | 1.79%   |
| AMD FCH SATA Controller D                                                      | 5        | 1.79%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4        | 1.43%   |
| Samsung NVMe SSD Controller 980                                                | 4        | 1.43%   |
| Phison E12 NVMe Controller                                                     | 4        | 1.43%   |
| Kingston Company A2000 NVMe SSD                                                | 4        | 1.43%   |
| Intel SATA Controller [RAID mode]                                              | 4        | 1.43%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4        | 1.43%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4        | 1.43%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 4        | 1.43%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 4        | 1.43%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 4        | 1.43%   |
| SanDisk Non-Volatile memory controller                                         | 3        | 1.07%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 3        | 1.07%   |
| Kingston Company Company Non-Volatile memory controller                        | 3        | 1.07%   |
| JMicron JMB363 SATA/IDE Controller                                             | 3        | 1.07%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 3        | 1.07%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 3        | 1.07%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 3        | 1.07%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3        | 1.07%   |
| AMD X399 Series Chipset SATA Controller                                        | 3        | 1.07%   |
| AMD 300 Series Chipset SATA Controller                                         | 3        | 1.07%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 3        | 1.07%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2        | 0.71%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2        | 0.71%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2        | 0.71%   |
| LSI Logic / Symbios Logic MegaRAID SAS 1078                                    | 2        | 0.71%   |
| JMicron JMB368 IDE controller                                                  | 2        | 0.71%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2        | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 132      | 62.56%  |
| NVMe | 49       | 23.22%  |
| IDE  | 21       | 9.95%   |
| RAID | 9        | 4.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 78       | 53.79%  |
| AMD    | 67       | 46.21%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor             | 6        | 4.14%   |
| Intel Core i7-4790K CPU @ 4.00GHz              | 3        | 2.07%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 3        | 2.07%   |
| Intel Core i5-10400F CPU @ 2.90GHz             | 3        | 2.07%   |
| AMD Ryzen 9 5950X 16-Core Processor            | 3        | 2.07%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 3        | 2.07%   |
| AMD Ryzen 7 5700G with Radeon Graphics         | 3        | 2.07%   |
| AMD Ryzen 7 3700X 8-Core Processor             | 3        | 2.07%   |
| AMD Ryzen 5 3600 6-Core Processor              | 3        | 2.07%   |
| AMD Ryzen 5 2600X Six-Core Processor           | 3        | 2.07%   |
| Intel Pentium CPU G2020 @ 2.90GHz              | 2        | 1.38%   |
| Intel Core i7-7700K CPU @ 4.20GHz              | 2        | 1.38%   |
| Intel Core i7-6700 CPU @ 3.40GHz               | 2        | 1.38%   |
| Intel Core i7-3770K CPU @ 3.50GHz              | 2        | 1.38%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 2        | 1.38%   |
| Intel Core i3-4130 CPU @ 3.40GHz               | 2        | 1.38%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz           | 2        | 1.38%   |
| AMD Ryzen Threadripper 1950X 16-Core Processor | 2        | 1.38%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 2        | 1.38%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics     | 2        | 1.38%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 2        | 1.38%   |
| AMD Ryzen 7 2700 Eight-Core Processor          | 2        | 1.38%   |
| AMD Ryzen 5 5600 6-Core Processor              | 2        | 1.38%   |
| AMD Ryzen 5 5500                               | 2        | 1.38%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics    | 2        | 1.38%   |
| Intel Xeon CPU X3440 @ 2.53GHz                 | 1        | 0.69%   |
| Intel Xeon CPU W3530 @ 2.80GHz                 | 1        | 0.69%   |
| Intel Xeon CPU E5-4627 v4 @ 2.60GHz            | 1        | 0.69%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz            | 1        | 0.69%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz            | 1        | 0.69%   |
| Intel Xeon CPU E5-1620 v2 @ 3.70GHz            | 1        | 0.69%   |
| Intel Xeon CPU E3-1275 V2 @ 3.50GHz            | 1        | 0.69%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz         | 1        | 0.69%   |
| Intel Pentium CPU J4205 @ 1.50GHz              | 1        | 0.69%   |
| Intel Pentium CPU G4600 @ 3.60GHz              | 1        | 0.69%   |
| Intel Pentium CPU G3430 @ 3.30GHz              | 1        | 0.69%   |
| Intel Pentium CPU G3220 @ 3.00GHz              | 1        | 0.69%   |
| Intel Core i9-9900 CPU @ 3.10GHz               | 1        | 0.69%   |
| Intel Core i9-10850K CPU @ 3.60GHz             | 1        | 0.69%   |
| Intel Core i7-9700 CPU @ 3.00GHz               | 1        | 0.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i7          | 26       | 17.93%  |
| AMD Ryzen 5            | 22       | 15.17%  |
| Intel Core i5          | 16       | 11.03%  |
| AMD Ryzen 7            | 13       | 8.97%   |
| AMD Ryzen 9            | 9        | 6.21%   |
| Intel Xeon             | 7        | 4.83%   |
| Intel Core i3          | 7        | 4.83%   |
| Intel Pentium          | 6        | 4.14%   |
| Other                  | 5        | 3.45%   |
| Intel Core 2 Duo       | 4        | 2.76%   |
| AMD Ryzen 3            | 4        | 2.76%   |
| AMD Ryzen Threadripper | 3        | 2.07%   |
| AMD FX                 | 3        | 2.07%   |
| Intel Core i9          | 2        | 1.38%   |
| Intel Core 2 Quad      | 2        | 1.38%   |
| Intel Celeron          | 2        | 1.38%   |
| AMD Ryzen 7 PRO        | 2        | 1.38%   |
| AMD Phenom II X2       | 2        | 1.38%   |
| AMD Opteron            | 2        | 1.38%   |
| Intel Pentium Gold     | 1        | 0.69%   |
| AMD Phenom II X6       | 1        | 0.69%   |
| AMD Phenom II X4       | 1        | 0.69%   |
| AMD E1                 | 1        | 0.69%   |
| AMD Athlon II X2       | 1        | 0.69%   |
| AMD A8                 | 1        | 0.69%   |
| AMD A6                 | 1        | 0.69%   |
| AMD A4                 | 1        | 0.69%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 51       | 35.17%  |
| 6      | 34       | 23.45%  |
| 2      | 23       | 15.86%  |
| 8      | 21       | 14.48%  |
| 16     | 7        | 4.83%   |
| 12     | 6        | 4.14%   |
| 10     | 2        | 1.38%   |
| 1      | 1        | 0.69%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 145      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 103      | 71.03%  |
| 1      | 42       | 28.97%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 145      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 70       | 47.62%  |
| 0x08701021 | 8        | 5.44%   |
| 0x306c3    | 6        | 4.08%   |
| 0x906e9    | 4        | 2.72%   |
| 0x0800820d | 4        | 2.72%   |
| 0x010000c8 | 4        | 2.72%   |
| 0xa0653    | 3        | 2.04%   |
| 0x906ed    | 3        | 2.04%   |
| 0x306a9    | 3        | 2.04%   |
| 0x0a50000c | 3        | 2.04%   |
| 0x0a201205 | 3        | 2.04%   |
| 0x0a201016 | 3        | 2.04%   |
| 0xa0655    | 2        | 1.36%   |
| 0x90672    | 2        | 1.36%   |
| 0x406f1    | 2        | 1.36%   |
| 0x0a20120a | 2        | 1.36%   |
| 0x0a201009 | 2        | 1.36%   |
| 0x08001138 | 2        | 1.36%   |
| 0x906ea    | 1        | 0.68%   |
| 0x6fb      | 1        | 0.68%   |
| 0x506e3    | 1        | 0.68%   |
| 0x306f2    | 1        | 0.68%   |
| 0x306e4    | 1        | 0.68%   |
| 0x206d6    | 1        | 0.68%   |
| 0x206a7    | 1        | 0.68%   |
| 0x106e5    | 1        | 0.68%   |
| 0x106a5    | 1        | 0.68%   |
| 0x1067a    | 1        | 0.68%   |
| 0x0a50000d | 1        | 0.68%   |
| 0x0a201204 | 1        | 0.68%   |
| 0x0a201005 | 1        | 0.68%   |
| 0x08701013 | 1        | 0.68%   |
| 0x08600106 | 1        | 0.68%   |
| 0x08600103 | 1        | 0.68%   |
| 0x08001137 | 1        | 0.68%   |
| 0x08001136 | 1        | 0.68%   |
| 0x07030106 | 1        | 0.68%   |
| 0x06000852 | 1        | 0.68%   |
| 0x00000000 | 1        | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 21       | 14.38%  |
| Haswell          | 18       | 12.33%  |
| Zen 2            | 14       | 9.59%   |
| KabyLake         | 14       | 9.59%   |
| Zen+             | 11       | 7.53%   |
| IvyBridge        | 10       | 6.85%   |
| Zen              | 7        | 4.79%   |
| Piledriver       | 6        | 4.11%   |
| K10              | 6        | 4.11%   |
| CometLake        | 6        | 4.11%   |
| Skylake          | 5        | 3.42%   |
| SandyBridge      | 4        | 2.74%   |
| Penryn           | 4        | 2.74%   |
| Nehalem          | 4        | 2.74%   |
| Unknown          | 4        | 2.74%   |
| Broadwell        | 3        | 2.05%   |
| Westmere         | 2        | 1.37%   |
| Core             | 2        | 1.37%   |
| Alderlake Hybrid | 2        | 1.37%   |
| Puma             | 1        | 0.68%   |
| Goldmont         | 1        | 0.68%   |
| Excavator        | 1        | 0.68%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 82       | 52.56%  |
| AMD                        | 49       | 31.41%  |
| Intel                      | 23       | 14.74%  |
| Matrox Electronics Systems | 2        | 1.28%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 11       | 7.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7        | 4.49%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7        | 4.49%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 4        | 2.56%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 2.56%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 1.92%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 1.92%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 1.92%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 3        | 1.92%   |
| Intel HD Graphics 630                                                       | 3        | 1.92%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 1.92%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 3        | 1.92%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 2        | 1.28%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 1.28%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 2        | 1.28%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 1.28%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 1.28%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 1.28%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 2        | 1.28%   |
| Nvidia G92 [GeForce 9800 GT]                                                | 2        | 1.28%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 2        | 1.28%   |
| Intel HD Graphics 530                                                       | 2        | 1.28%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 1.28%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.28%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                           | 2        | 1.28%   |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                           | 2        | 1.28%   |
| AMD Renoir                                                                  | 2        | 1.28%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 1.28%   |
| AMD Navi 24 [Radeon RX 6400 / 6500 XT]                                      | 2        | 1.28%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 1.28%   |
| AMD Cezanne                                                                 | 2        | 1.28%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 2        | 1.28%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.64%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.64%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.64%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1        | 0.64%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.64%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 0.64%   |
| Nvidia TU106 [GeForce RTX 2060 12GB]                                        | 1        | 0.64%   |
| Nvidia TU104 [GeForce RTX 2080]                                             | 1        | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 79       | 54.48%  |
| 1 x AMD                  | 44       | 30.34%  |
| 1 x Intel                | 16       | 11.03%  |
| 2 x Nvidia               | 1        | 0.69%   |
| 2 x AMD                  | 1        | 0.69%   |
| Nvidia + Matrox          | 1        | 0.69%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.69%   |
| Intel + AMD              | 1        | 0.69%   |
| AMD + Matrox             | 1        | 0.69%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 78       | 53.79%  |
| Proprietary | 62       | 42.76%  |
| Unknown     | 5        | 3.45%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 59       | 39.6%   |
| 7.01-8.0   | 19       | 12.75%  |
| 3.01-4.0   | 17       | 11.41%  |
| 1.01-2.0   | 17       | 11.41%  |
| 5.01-6.0   | 11       | 7.38%   |
| 0.51-1.0   | 11       | 7.38%   |
| 8.01-16.0  | 6        | 4.03%   |
| 0.01-0.5   | 5        | 3.36%   |
| 16.01-24.0 | 2        | 1.34%   |
| 4.01-5.0   | 1        | 0.67%   |
| 2.01-3.0   | 1        | 0.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 36       | 20.81%  |
| Dell                 | 19       | 10.98%  |
| Goldstar             | 16       | 9.25%   |
| Hewlett-Packard      | 14       | 8.09%   |
| AOC                  | 12       | 6.94%   |
| Acer                 | 11       | 6.36%   |
| BenQ                 | 9        | 5.2%    |
| Philips              | 8        | 4.62%   |
| Iiyama               | 6        | 3.47%   |
| Ancor Communications | 5        | 2.89%   |
| Sony                 | 4        | 2.31%   |
| ASUSTek Computer     | 3        | 1.73%   |
| NEC Computers        | 2        | 1.16%   |
| LG Electronics       | 2        | 1.16%   |
| Idek Iiyama          | 2        | 1.16%   |
| Denver               | 2        | 1.16%   |
| Xiaomi               | 1        | 0.58%   |
| Vizio                | 1        | 0.58%   |
| Vita                 | 1        | 0.58%   |
| Unknown              | 1        | 0.58%   |
| Sunplus              | 1        | 0.58%   |
| STD                  | 1        | 0.58%   |
| Sceptre Tech         | 1        | 0.58%   |
| RTK                  | 1        | 0.58%   |
| QUS                  | 1        | 0.58%   |
| Planar               | 1        | 0.58%   |
| PAR                  | 1        | 0.58%   |
| Panasonic            | 1        | 0.58%   |
| MSI                  | 1        | 0.58%   |
| Medion               | 1        | 0.58%   |
| Lenovo               | 1        | 0.58%   |
| HKC                  | 1        | 0.58%   |
| Gigabyte Technology  | 1        | 0.58%   |
| Fujitsu Siemens      | 1        | 0.58%   |
| Envision Peripherals | 1        | 0.58%   |
| Eizo                 | 1        | 0.58%   |
| CHD                  | 1        | 0.58%   |
| AIO                  | 1        | 0.58%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 3        | 1.63%   |
| AOC 27G2G3 AOC2702 1920x1080 598x336mm 27.0-inch                     | 3        | 1.63%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch  | 2        | 1.09%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 2        | 1.09%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch    | 2        | 1.09%   |
| Hewlett-Packard 24w HPN3431 1920x1080 527x296mm 23.8-inch            | 2        | 1.09%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 2        | 1.09%   |
| Goldstar 22EA53 GSM59A5 1920x1080 477x268mm 21.5-inch                | 2        | 1.09%   |
| Dell P2719H DEL4184 1920x1080 598x336mm 27.0-inch                    | 2        | 1.09%   |
| AOC U3277WB AOC3277 3840x2160 698x393mm 31.5-inch                    | 2        | 1.09%   |
| Acer VG240Y ACR06BF 1920x1080 527x296mm 23.8-inch                    | 2        | 1.09%   |
| Xiaomi Mi TV XMD00E2 3840x2160 800x450mm 36.1-inch                   | 1        | 0.54%   |
| Vizio E320-B0 VIZ1007 1366x768 697x392mm 31.5-inch                   | 1        | 0.54%   |
| Vita VT988 VIT03DC 1280x1024 376x301mm 19.0-inch                     | 1        | 0.54%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 1        | 0.54%   |
| Sunplus Monitor TV SPVFFFF 1920x1080 376x301mm 19.0-inch             | 1        | 0.54%   |
| STD LED STD0001 2560x1440 330x220mm 15.6-inch                        | 1        | 0.54%   |
| Sony TV SNYEE01 1920x1080                                            | 1        | 0.54%   |
| Sony TV SNYC901 1920x1080                                            | 1        | 0.54%   |
| Sony TV SNY7702 1920x1080 886x498mm 40.0-inch                        | 1        | 0.54%   |
| Sony TV *02 SNY9403 1920x1080 1218x685mm 55.0-inch                   | 1        | 0.54%   |
| Sceptre Tech E24 SPT099D 1920x1080 521x293mm 23.5-inch               | 1        | 0.54%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 700x390mm 31.5-inch    | 1        | 0.54%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch    | 1        | 0.54%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 607x345mm 27.5-inch    | 1        | 0.54%   |
| Samsung Electronics U28D590 SAM0B81 3840x2160 608x345mm 27.5-inch    | 1        | 0.54%   |
| Samsung Electronics U28D590 SAM0B80 3840x2160 607x345mm 27.5-inch    | 1        | 0.54%   |
| Samsung Electronics T19C300 SAM0A98 1366x768 410x230mm 18.5-inch     | 1        | 0.54%   |
| Samsung Electronics SyncMaster SAM05CC 1920x1080 530x300mm 24.0-inch | 1        | 0.54%   |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch | 1        | 0.54%   |
| Samsung Electronics SyncMaster SAM04E6 1920x1080 477x268mm 21.5-inch | 1        | 0.54%   |
| Samsung Electronics SyncMaster SAM0225 1440x900 410x257mm 19.1-inch  | 1        | 0.54%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch | 1        | 0.54%   |
| Samsung Electronics SyncMaster SAM01DA 1280x1024 376x301mm 19.0-inch | 1        | 0.54%   |
| Samsung Electronics SMT24A550 SAM07B5 1920x1080 531x299mm 24.0-inch  | 1        | 0.54%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 598x336mm 27.0-inch | 1        | 0.54%   |
| Samsung Electronics SMB1940 SAM06B9 1280x1024 376x301mm 19.0-inch    | 1        | 0.54%   |
| Samsung Electronics SM2333TN SAM06FC 1920x1080 477x268mm 21.5-inch   | 1        | 0.54%   |
| Samsung Electronics S27B350 SAM08DC 1920x1080 598x336mm 27.0-inch    | 1        | 0.54%   |
| Samsung Electronics S22D390 SAM0B63 1920x1080 477x268mm 21.5-inch    | 1        | 0.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 83       | 50.92%  |
| 3840x2160 (4K)     | 21       | 12.88%  |
| 2560x1440 (QHD)    | 12       | 7.36%   |
| 1920x1200 (WUXGA)  | 9        | 5.52%   |
| 1680x1050 (WSXGA+) | 7        | 4.29%   |
| 1280x1024 (SXGA)   | 7        | 4.29%   |
| 1600x900 (HD+)     | 4        | 2.45%   |
| 1366x768 (WXGA)    | 4        | 2.45%   |
| 3440x1440          | 3        | 1.84%   |
| 1440x900 (WXGA+)   | 3        | 1.84%   |
| 2560x1080          | 2        | 1.23%   |
| 1280x720 (HD)      | 2        | 1.23%   |
| 3840x1200          | 1        | 0.61%   |
| 3840x1080          | 1        | 0.61%   |
| 3600x1200          | 1        | 0.61%   |
| 2288x1287          | 1        | 0.61%   |
| 1360x768           | 1        | 0.61%   |
| Unknown            | 1        | 0.61%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 37       | 21.64%  |
| 27      | 29       | 16.96%  |
| 23      | 19       | 11.11%  |
| 21      | 17       | 9.94%   |
| 31      | 12       | 7.02%   |
| 19      | 11       | 6.43%   |
| 22      | 7        | 4.09%   |
| Unknown | 6        | 3.51%   |
| 34      | 5        | 2.92%   |
| 32      | 4        | 2.34%   |
| 18      | 4        | 2.34%   |
| 46      | 3        | 1.75%   |
| 72      | 2        | 1.17%   |
| 36      | 2        | 1.17%   |
| 20      | 2        | 1.17%   |
| 142     | 1        | 0.58%   |
| 65      | 1        | 0.58%   |
| 60      | 1        | 0.58%   |
| 55      | 1        | 0.58%   |
| 54      | 1        | 0.58%   |
| 48      | 1        | 0.58%   |
| 43      | 1        | 0.58%   |
| 40      | 1        | 0.58%   |
| 26      | 1        | 0.58%   |
| 25      | 1        | 0.58%   |
| 17      | 1        | 0.58%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 70       | 43.75%  |
| 401-500        | 35       | 21.88%  |
| 601-700        | 18       | 11.25%  |
| 701-800        | 11       | 6.88%   |
| 1001-1500      | 8        | 5%      |
| 351-400        | 6        | 3.75%   |
| Unknown        | 6        | 3.75%   |
| 1501-2000      | 2        | 1.25%   |
| More than 2000 | 1        | 0.63%   |
| 801-900        | 1        | 0.63%   |
| 301-350        | 1        | 0.63%   |
| 901-1000       | 1        | 0.63%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 111      | 73.51%  |
| 16/10   | 20       | 13.25%  |
| 5/4     | 7        | 4.64%   |
| 21/9    | 5        | 3.31%   |
| Unknown | 5        | 3.31%   |
| 32/9    | 1        | 0.66%   |
| 1.98    | 1        | 0.66%   |
| 1.00    | 1        | 0.66%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 58       | 35.58%  |
| 301-350        | 29       | 17.79%  |
| 351-500        | 21       | 12.88%  |
| 151-200        | 19       | 11.66%  |
| 251-300        | 11       | 6.75%   |
| 501-1000       | 8        | 4.91%   |
| More than 1000 | 7        | 4.29%   |
| Unknown        | 6        | 3.68%   |
| 141-150        | 4        | 2.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 93       | 61.18%  |
| 101-120 | 26       | 17.11%  |
| 1-50    | 12       | 7.89%   |
| 121-160 | 11       | 7.24%   |
| Unknown | 6        | 3.95%   |
| 161-240 | 4        | 2.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 92       | 63.01%  |
| 2     | 47       | 32.19%  |
| 0     | 4        | 2.74%   |
| 3     | 2        | 1.37%   |
| 4     | 1        | 0.68%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 92       | 41.63%  |
| Intel                           | 67       | 30.32%  |
| Qualcomm Atheros                | 12       | 5.43%   |
| Ralink Technology               | 8        | 3.62%   |
| Broadcom                        | 8        | 3.62%   |
| Aquantia                        | 5        | 2.26%   |
| TP-Link                         | 4        | 1.81%   |
| Ralink                          | 3        | 1.36%   |
| Xiaomi                          | 2        | 0.9%    |
| Samsung Electronics             | 2        | 0.9%    |
| Huawei Technologies             | 2        | 0.9%    |
| ASUSTek Computer                | 2        | 0.9%    |
| ZyXEL Communications            | 1        | 0.45%   |
| Wilocity                        | 1        | 0.45%   |
| VIA Technologies                | 1        | 0.45%   |
| Qualcomm Atheros Communications | 1        | 0.45%   |
| Microsoft                       | 1        | 0.45%   |
| Mercucys                        | 1        | 0.45%   |
| MediaTek                        | 1        | 0.45%   |
| Linksys                         | 1        | 0.45%   |
| Edimax Technology               | 1        | 0.45%   |
| DisplayLink                     | 1        | 0.45%   |
| D-Link System                   | 1        | 0.45%   |
| D-Link                          | 1        | 0.45%   |
| Bose                            | 1        | 0.45%   |
| ASIX Electronics                | 1        | 0.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 71       | 27.95%  |
| Intel Ethernet Controller I225-V                                  | 10       | 3.94%   |
| Intel I211 Gigabit Network Connection                             | 9        | 3.54%   |
| Intel Wi-Fi 6 AX200                                               | 8        | 3.15%   |
| Intel Ethernet Connection I217-LM                                 | 7        | 2.76%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6        | 2.36%   |
| Intel Ethernet Connection (7) I219-V                              | 5        | 1.97%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 1.97%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4        | 1.57%   |
| Realtek 802.11ac NIC                                              | 4        | 1.57%   |
| Intel 82574L Gigabit Network Connection                           | 4        | 1.57%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 4        | 1.57%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 4        | 1.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 1.18%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 1.18%   |
| Intel Wireless-AC 9260                                            | 3        | 1.18%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 1.18%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 0.79%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.79%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.79%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 2        | 0.79%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 2        | 0.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2        | 0.79%   |
| Ralink RT5370 Wireless Adapter                                    | 2        | 0.79%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2        | 0.79%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 2        | 0.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2        | 0.79%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 2        | 0.79%   |
| Intel Wireless 8260                                               | 2        | 0.79%   |
| Intel Wireless 7260                                               | 2        | 0.79%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 0.79%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2        | 0.79%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 0.79%   |
| Huawei LYA-L09                                                    | 2        | 0.79%   |
| ZyXEL ZyAIR G-202 802.11bg                                        | 1        | 0.39%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                | 1        | 0.39%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1        | 0.39%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1        | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 26       | 30.95%  |
| Realtek Semiconductor           | 18       | 21.43%  |
| Ralink Technology               | 8        | 9.52%   |
| Broadcom                        | 8        | 9.52%   |
| Qualcomm Atheros                | 6        | 7.14%   |
| TP-Link                         | 4        | 4.76%   |
| Ralink                          | 3        | 3.57%   |
| ASUSTek Computer                | 2        | 2.38%   |
| ZyXEL Communications            | 1        | 1.19%   |
| Wilocity                        | 1        | 1.19%   |
| Qualcomm Atheros Communications | 1        | 1.19%   |
| Microsoft                       | 1        | 1.19%   |
| Mercucys                        | 1        | 1.19%   |
| Linksys                         | 1        | 1.19%   |
| Edimax Technology               | 1        | 1.19%   |
| D-Link System                   | 1        | 1.19%   |
| D-Link                          | 1        | 1.19%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 8        | 9.3%    |
| Realtek 802.11ac NIC                                           | 4        | 4.65%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 4        | 4.65%   |
| Intel Wireless-AC 9260                                         | 3        | 3.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2        | 2.33%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2        | 2.33%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 2        | 2.33%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 2        | 2.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2        | 2.33%   |
| Ralink RT5370 Wireless Adapter                                 | 2        | 2.33%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 2        | 2.33%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 2        | 2.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2        | 2.33%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 2        | 2.33%   |
| Intel Wireless 8260                                            | 2        | 2.33%   |
| Intel Wireless 7260                                            | 2        | 2.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2        | 2.33%   |
| ZyXEL ZyAIR G-202 802.11bg                                     | 1        | 1.16%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter             | 1        | 1.16%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1        | 1.16%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                     | 1        | 1.16%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 1        | 1.16%   |
| TP-Link 802.11ac NIC                                           | 1        | 1.16%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1        | 1.16%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1        | 1.16%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1        | 1.16%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1        | 1.16%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1        | 1.16%   |
| Realtek 802.11n WLAN Adapter                                   | 1        | 1.16%   |
| Ralink RT5572 Wireless Adapter                                 | 1        | 1.16%   |
| Ralink RT3572 Wireless Adapter                                 | 1        | 1.16%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter              | 1        | 1.16%   |
| Ralink MT7601U Wireless Adapter                                | 1        | 1.16%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                           | 1        | 1.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1        | 1.16%   |
| Qualcomm Atheros AR9271 802.11n                                | 1        | 1.16%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1        | 1.16%   |
| Microsoft Wireless XBox Controller Dongle                      | 1        | 1.16%   |
| Mercucys 802.11n NIC                                           | 1        | 1.16%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter            | 1        | 1.16%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 83       | 50.92%  |
| Intel                 | 57       | 34.97%  |
| Qualcomm Atheros      | 6        | 3.68%   |
| Aquantia              | 5        | 3.07%   |
| Xiaomi                | 2        | 1.23%   |
| Samsung Electronics   | 2        | 1.23%   |
| Huawei Technologies   | 2        | 1.23%   |
| Broadcom              | 2        | 1.23%   |
| VIA Technologies      | 1        | 0.61%   |
| MediaTek              | 1        | 0.61%   |
| DisplayLink           | 1        | 0.61%   |
| ASIX Electronics      | 1        | 0.61%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 71       | 42.51%  |
| Intel Ethernet Controller I225-V                                    | 10       | 5.99%   |
| Intel I211 Gigabit Network Connection                               | 9        | 5.39%   |
| Intel Ethernet Connection I217-LM                                   | 7        | 4.19%   |
| Realtek RTL8125 2.5GbE Controller                                   | 6        | 3.59%   |
| Intel Ethernet Connection (7) I219-V                                | 5        | 2.99%   |
| Intel Ethernet Connection (2) I219-V                                | 5        | 2.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 4        | 2.4%    |
| Intel 82574L Gigabit Network Connection                             | 4        | 2.4%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 4        | 2.4%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 3        | 1.8%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 3        | 1.8%    |
| Intel Ethernet Connection (2) I218-V                                | 3        | 1.8%    |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 2        | 1.2%    |
| Samsung Galaxy series, misc. (tethering mode)                       | 2        | 1.2%    |
| Intel Ethernet Connection (14) I219-V                               | 2        | 1.2%    |
| Intel Ethernet Connection (11) I219-V                               | 2        | 1.2%    |
| Intel 82579V Gigabit Network Connection                             | 2        | 1.2%    |
| Huawei LYA-L09                                                      | 2        | 1.2%    |
| VIA VT6105/VT6106S [Rhine-III]                                      | 1        | 0.6%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                     | 1        | 0.6%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                          | 1        | 0.6%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                    | 1        | 0.6%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller           | 1        | 0.6%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 1        | 0.6%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet      | 1        | 0.6%    |
| MediaTek TECNO Pouvoir 3 Air                                        | 1        | 0.6%    |
| Intel I210 Gigabit Network Connection                               | 1        | 0.6%    |
| Intel Ethernet Connection I218-LM                                   | 1        | 0.6%    |
| Intel Ethernet Connection I217-V                                    | 1        | 0.6%    |
| Intel Ethernet Connection (7) I219-LM                               | 1        | 0.6%    |
| Intel 82583V Gigabit Network Connection                             | 1        | 0.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 1        | 0.6%    |
| Intel 82578DM Gigabit Network Connection                            | 1        | 0.6%    |
| Intel 82566DM-2 Gigabit Network Connection                          | 1        | 0.6%    |
| DisplayLink Dell Universal Dock D6000                               | 1        | 0.6%    |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                   | 1        | 0.6%    |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                     | 1        | 0.6%    |
| ASIX AX88179 Gigabit Ethernet                                       | 1        | 0.6%    |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.6%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 144      | 64%     |
| WiFi     | 80       | 35.56%  |
| Modem    | 1        | 0.44%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 107      | 72.79%  |
| WiFi     | 40       | 27.21%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 86       | 59.31%  |
| 2     | 51       | 35.17%  |
| 3     | 6        | 4.14%   |
| 6     | 1        | 0.69%   |
| 4     | 1        | 0.69%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 101      | 69.18%  |
| Yes  | 45       | 30.82%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 23       | 34.33%  |
| Cambridge Silicon Radio         | 20       | 29.85%  |
| Realtek Semiconductor           | 8        | 11.94%  |
| ASUSTek Computer                | 6        | 8.96%   |
| Broadcom                        | 3        | 4.48%   |
| IMC Networks                    | 2        | 2.99%   |
| Edimax Technology               | 2        | 2.99%   |
| TP-Link                         | 1        | 1.49%   |
| Qualcomm Atheros Communications | 1        | 1.49%   |
| Apple                           | 1        | 1.49%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 20       | 29.85%  |
| Intel AX200 Bluetooth                                   | 8        | 11.94%  |
| Realtek Bluetooth Radio                                 | 6        | 8.96%   |
| Intel Bluetooth wireless interface                      | 5        | 7.46%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 3        | 4.48%   |
| Broadcom BCM20702A0 Bluetooth 4.0                       | 3        | 4.48%   |
| ASUS ASUS USB-BT500                                     | 3        | 4.48%   |
| Realtek  Bluetooth 4.2 Adapter                          | 2        | 2.99%   |
| Intel Wireless-AC 3168 Bluetooth                        | 2        | 2.99%   |
| Intel AX201 Bluetooth                                   | 2        | 2.99%   |
| IMC Networks Bluetooth Radio                            | 2        | 2.99%   |
| TP-Link TPuLink UB500 Adapter                           | 1        | 1.49%   |
| Qualcomm Atheros  Bluetooth Device                      | 1        | 1.49%   |
| Intel Bluetooth Device                                  | 1        | 1.49%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 1        | 1.49%   |
| Intel AX210 Bluetooth                                   | 1        | 1.49%   |
| Edimax Wi-Fi AC600 Bluetooth4.0 USB Adapter             | 1        | 1.49%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter | 1        | 1.49%   |
| ASUS Qualcomm Bluetooth 4.1                             | 1        | 1.49%   |
| ASUS Bluetooth Device                                   | 1        | 1.49%   |
| ASUS Bluetooth Adapter                                  | 1        | 1.49%   |
| Apple Bluetooth USB Host Controller                     | 1        | 1.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| AMD                      | 86       | 28.76%  |
| Nvidia                   | 79       | 26.42%  |
| Intel                    | 74       | 24.75%  |
| C-Media Electronics      | 6        | 2.01%   |
| GN Netcom                | 5        | 1.67%   |
| JMTek                    | 4        | 1.34%   |
| Creative Labs            | 4        | 1.34%   |
| VIA Technologies         | 2        | 0.67%   |
| Texas Instruments        | 2        | 0.67%   |
| Razer USA                | 2        | 0.67%   |
| KORG                     | 2        | 0.67%   |
| Kingston Technology      | 2        | 0.67%   |
| Generalplus Technology   | 2        | 0.67%   |
| BY EDIFIER               | 2        | 0.67%   |
| Blue Microphones         | 2        | 0.67%   |
| ASUSTek Computer         | 2        | 0.67%   |
| ZOOM                     | 1        | 0.33%   |
| Yamaha                   | 1        | 0.33%   |
| Unknown                  | 1        | 0.33%   |
| TerraTec Electronic      | 1        | 0.33%   |
| Tenx Technology          | 1        | 0.33%   |
| SteelSeries ApS          | 1        | 0.33%   |
| Samson Technologies      | 1        | 0.33%   |
| QinHeng Electronics      | 1        | 0.33%   |
| Philips (or NXP)         | 1        | 0.33%   |
| Nordic Semiconductor ASA | 1        | 0.33%   |
| Microdia                 | 1        | 0.33%   |
| Micro Star International | 1        | 0.33%   |
| M-Audio                  | 1        | 0.33%   |
| Logitech                 | 1        | 0.33%   |
| Lenovo                   | 1        | 0.33%   |
| Hangzhou Worlde          | 1        | 0.33%   |
| Dell                     | 1        | 0.33%   |
| Corsair                  | 1        | 0.33%   |
| Bose                     | 1        | 0.33%   |
| BEHRINGER International  | 1        | 0.33%   |
| Barco Display Systems    | 1        | 0.33%   |
| Astro Gaming             | 1        | 0.33%   |
| Arturia                  | 1        | 0.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 26       | 7.74%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 14       | 4.17%   |
| Nvidia GP107GL High Definition Audio Controller                            | 12       | 3.57%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 11       | 3.27%   |
| AMD Family 17h/19h HD Audio Controller                                     | 11       | 3.27%   |
| Nvidia TU116 High Definition Audio Controller                              | 8        | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8        | 2.38%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 8        | 2.38%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 8        | 2.38%   |
| Intel 200 Series PCH HD Audio                                              | 7        | 2.08%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 7        | 2.08%   |
| Nvidia GP106 High Definition Audio Controller                              | 6        | 1.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6        | 1.79%   |
| Intel Cannon Lake PCH cAVS                                                 | 6        | 1.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 6        | 1.79%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 6        | 1.79%   |
| Nvidia TU104 HD Audio Controller                                           | 5        | 1.49%   |
| Nvidia GP104 High Definition Audio Controller                              | 5        | 1.49%   |
| Nvidia GA104 High Definition Audio Controller                              | 5        | 1.49%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 5        | 1.49%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 5        | 1.49%   |
| Nvidia High Definition Audio Controller                                    | 4        | 1.19%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4        | 1.19%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4        | 1.19%   |
| Intel Comet Lake PCH cAVS                                                  | 4        | 1.19%   |
| Nvidia TU102 High Definition Audio Controller                              | 3        | 0.89%   |
| Nvidia GP108 High Definition Audio Controller                              | 3        | 0.89%   |
| Nvidia GM206 High Definition Audio Controller                              | 3        | 0.89%   |
| JMTek USB PnP Audio Device                                                 | 3        | 0.89%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3        | 0.89%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 3        | 0.89%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 0.89%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 0.89%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 0.89%   |
| C-Media Electronics Blue Snowball                                          | 3        | 0.89%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3        | 0.89%   |
| AMD FCH Azalia Controller                                                  | 3        | 0.89%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3        | 0.89%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 0.6%    |
| Nvidia GM204 High Definition Audio Controller                              | 2        | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 18       | 20.69%  |
| Kingston            | 17       | 19.54%  |
| G.Skill             | 14       | 16.09%  |
| Crucial             | 7        | 8.05%   |
| Unknown             | 6        | 6.9%    |
| Micron Technology   | 5        | 5.75%   |
| SK hynix            | 4        | 4.6%    |
| Samsung Electronics | 4        | 4.6%    |
| Team                | 2        | 2.3%    |
| Patriot             | 2        | 2.3%    |
| Unknown             | 2        | 2.3%    |
| Ramaxel Technology  | 1        | 1.15%   |
| PNY                 | 1        | 1.15%   |
| Lexar               | 1        | 1.15%   |
| Kingmax             | 1        | 1.15%   |
| Atermiter           | 1        | 1.15%   |
| AMD                 | 1        | 1.15%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 2        | 2.06%   |
| Micron RAM 8ATF1G64AZ-2G6E1 8192MB DIMM DDR4 2667MT/s    | 2        | 2.06%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s    | 2        | 2.06%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s    | 2        | 2.06%   |
| Corsair RAM CMK32GX4M2Z3600C18 16GB DIMM DDR4 3800MT/s   | 2        | 2.06%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s    | 2        | 2.06%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s | 2        | 2.06%   |
| Unknown                                                  | 2        | 2.06%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                | 1        | 1.03%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                     | 1        | 1.03%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                 | 1        | 1.03%   |
| Unknown RAM Module 16GB DIMM DDR4 2667MT/s               | 1        | 1.03%   |
| Unknown RAM 3600 C20 Series 32GB DIMM DDR4 3666MT/s      | 1        | 1.03%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s      | 1        | 1.03%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3000MT/s       | 1        | 1.03%   |
| SK hynix RAM Module 8GB DIMM DDR4 2133MT/s               | 1        | 1.03%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s     | 1        | 1.03%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 1.03%   |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s     | 1        | 1.03%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s      | 1        | 1.03%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s      | 1        | 1.03%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s      | 1        | 1.03%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s      | 1        | 1.03%   |
| Ramaxel RAM RMR5040ED58E9W1600 4GB DIMM DDR3 1600MT/s    | 1        | 1.03%   |
| PNY RAM 8GBF1X08QFHH38-135-K 8GB DIMM DDR4 3200MT/s      | 1        | 1.03%   |
| Patriot RAM PSD416G320081 16GB DIMM DDR4 3200MT/s        | 1        | 1.03%   |
| Patriot RAM PSD416G26662 16GB DIMM DDR4 2667MT/s         | 1        | 1.03%   |
| Micron RAM Module 4GB DIMM DDR3 1866MT/s                 | 1        | 1.03%   |
| Micron RAM 9ASF51272PZ-2G3B1 4096MB RIMM DDR4 2400MT/s   | 1        | 1.03%   |
| Micron RAM 36ASF4G72PZ-2G3B1 32GB RIMM DDR4 2400MT/s     | 1        | 1.03%   |
| Micron RAM 16JTF1G64AZ-1G6E1 8GB DIMM DDR3 1600MT/s      | 1        | 1.03%   |
| Lexar RAM LD4AU016G-3200ST 16GB DIMM DDR4 3200MT/s       | 1        | 1.03%   |
| Kingston RAM KHX3466C19D4/16G 16GB DIMM DDR4 3467MT/s    | 1        | 1.03%   |
| Kingston RAM KHX3200C18D4/8G 8GB DIMM DDR4 3333MT/s      | 1        | 1.03%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s   | 1        | 1.03%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s        | 1        | 1.03%   |
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 3334MT/s      | 1        | 1.03%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3200MT/s    | 1        | 1.03%   |
| Kingston RAM ACR32D4U2S8HD-8X 8GB DIMM DDR4 3200MT/s     | 1        | 1.03%   |
| Kingston RAM ACR16D3LU1KBG/4G 4GB DIMM DDR3 1600MT/s     | 1        | 1.03%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 56       | 67.47%  |
| DDR3    | 18       | 21.69%  |
| SDRAM   | 3        | 3.61%   |
| Unknown | 3        | 3.61%   |
| DDR2    | 2        | 2.41%   |
| DDR5    | 1        | 1.2%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 80       | 97.56%  |
| SODIMM | 1        | 1.22%   |
| RIMM   | 1        | 1.22%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 38       | 43.18%  |
| 16384 | 26       | 29.55%  |
| 4096  | 14       | 15.91%  |
| 2048  | 5        | 5.68%   |
| 32768 | 4        | 4.55%   |
| 1024  | 1        | 1.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 16       | 17.98%  |
| 1600  | 12       | 13.48%  |
| 1333  | 9        | 10.11%  |
| 3600  | 7        | 7.87%   |
| 2667  | 7        | 7.87%   |
| 2133  | 6        | 6.74%   |
| 3000  | 4        | 4.49%   |
| 2400  | 4        | 4.49%   |
| 3066  | 3        | 3.37%   |
| 2666  | 3        | 3.37%   |
| 3800  | 2        | 2.25%   |
| 6000  | 1        | 1.12%   |
| 5800  | 1        | 1.12%   |
| 4000  | 1        | 1.12%   |
| 3866  | 1        | 1.12%   |
| 3666  | 1        | 1.12%   |
| 3467  | 1        | 1.12%   |
| 3400  | 1        | 1.12%   |
| 3334  | 1        | 1.12%   |
| 3333  | 1        | 1.12%   |
| 3266  | 1        | 1.12%   |
| 2800  | 1        | 1.12%   |
| 2448  | 1        | 1.12%   |
| 1867  | 1        | 1.12%   |
| 1866  | 1        | 1.12%   |
| 1066  | 1        | 1.12%   |
| 800   | 1        | 1.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 4        | 33.33%  |
| Seiko Epson         | 2        | 16.67%  |
| Canon               | 2        | 16.67%  |
| Xerox               | 1        | 8.33%   |
| Samsung Electronics | 1        | 8.33%   |
| Datamax-O'Neil      | 1        | 8.33%   |
| Brother Industries  | 1        | 8.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Xerox Phaser 3140 and 3155       | 1        | 8.33%   |
| Seiko Epson L3110 Series         | 1        | 8.33%   |
| Seiko Epson L222 Series          | 1        | 8.33%   |
| Samsung M2070 Series             | 1        | 8.33%   |
| HP OfficeJet 5500 series         | 1        | 8.33%   |
| HP LaserJet 1022                 | 1        | 8.33%   |
| HP ENVY 4500 series              | 1        | 8.33%   |
| HP DeskJet D2300                 | 1        | 8.33%   |
| Datamax-O'Neil Datamax E-4304    | 1        | 8.33%   |
| Canon PIXMA MX470 Series         | 1        | 8.33%   |
| Canon LaserShot LBP-1120 Printer | 1        | 8.33%   |
| Brother MFC-J460DW               | 1        | 8.33%   |

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
| Logitech                      | 15       | 39.47%  |
| Microdia                      | 4        | 10.53%  |
| Sunplus Innovation Technology | 2        | 5.26%   |
| Microsoft                     | 2        | 5.26%   |
| KYE Systems (Mouse Systems)   | 2        | 5.26%   |
| Jieli Technology              | 2        | 5.26%   |
| Generalplus Technology        | 2        | 5.26%   |
| Unknown                       | 1        | 2.63%   |
| Silicon Motion                | 1        | 2.63%   |
| Realtek Semiconductor         | 1        | 2.63%   |
| IMC Networks                  | 1        | 2.63%   |
| Hewlett-Packard               | 1        | 2.63%   |
| Cubeternet                    | 1        | 2.63%   |
| Asuscom Network               | 1        | 2.63%   |
| ARC International             | 1        | 2.63%   |
| Alcor Micro                   | 1        | 2.63%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Logitech Webcam C270                                                | 4        | 10.53%  |
| Logitech HD Pro Webcam C920                                         | 3        | 7.89%   |
| Microdia Webcam Vitade AF                                           | 2        | 5.26%   |
| Microdia Integrated Camera                                          | 2        | 5.26%   |
| Logitech C920 PRO HD Webcam                                         | 2        | 5.26%   |
| Jieli USB PHY 2.0                                                   | 2        | 5.26%   |
| Unknown HD camera                                                   | 1        | 2.63%   |
| Sunplus SPCA2281 Web Camera                                         | 1        | 2.63%   |
| Sunplus ezcap U3 capture-04                                         | 1        | 2.63%   |
| Silicon Motion 300k Pixel Camera                                    | 1        | 2.63%   |
| Realtek HK 2M CAM                                                   | 1        | 2.63%   |
| Microsoft LifeCam HD-3000                                           | 1        | 2.63%   |
| Microsoft LifeCam Cinema                                            | 1        | 2.63%   |
| Logitech Webcam C310                                                | 1        | 2.63%   |
| Logitech Webcam C170                                                | 1        | 2.63%   |
| Logitech QuickCam Pro for Notebooks                                 | 1        | 2.63%   |
| Logitech HD Webcam C910                                             | 1        | 2.63%   |
| Logitech C922 Pro Stream Webcam                                     | 1        | 2.63%   |
| Logitech BRIO Ultra HD Webcam                                       | 1        | 2.63%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera                          | 1        | 2.63%   |
| KYE Systems (Mouse Systems) eFace 2025                              | 1        | 2.63%   |
| IMC Networks UVC VGA Webcam                                         | 1        | 2.63%   |
| HP Webcam 1300                                                      | 1        | 2.63%   |
| Generalplus GENERAL WEBCAM                                          | 1        | 2.63%   |
| Generalplus 808 Camera                                              | 1        | 2.63%   |
| Cubeternet EtronTech CMOS based eSP570 WebCam [Onyx Titanium TC101] | 1        | 2.63%   |
| Asuscom Network HD 1080P PC-Camera                                  | 1        | 2.63%   |
| ARC International Camera                                            | 1        | 2.63%   |
| Alcor Micro USB2.0 Camera                                           | 1        | 2.63%   |

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
| Gemalto (was Gemplus) | 1        | 50%     |
| BIT4ID                | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1        | 50%     |
| BIT4ID miniLector EVO                             | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 118      | 80.82%  |
| 1     | 25       | 17.12%  |
| 2     | 2        | 1.37%   |
| 3     | 1        | 0.68%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Net/wireless          | 9        | 31.03%  |
| Graphics card         | 6        | 20.69%  |
| Unassigned class      | 5        | 17.24%  |
| Multimedia controller | 3        | 10.34%  |
| Fingerprint reader    | 2        | 6.9%    |
| Chipcard              | 2        | 6.9%    |
| Sound                 | 1        | 3.45%   |
| Bluetooth             | 1        | 3.45%   |

