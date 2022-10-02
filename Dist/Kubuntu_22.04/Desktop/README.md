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

Total: 162

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo     | ThinkCentre M90p 5498A2U    | [ed9cd240cc](https://linux-hardware.org/?probe=ed9cd240cc) | Oct 01, 2022 |
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
| HP         | 8459                        | [9c53dae23e](https://linux-hardware.org/?probe=9c53dae23e) | Aug 10, 2022 |
| Gigabyte   | H370 AORUS GAMING 3 WIFI... | [6eac3041ec](https://linux-hardware.org/?probe=6eac3041ec) | Aug 07, 2022 |
| MSI        | B550-A PRO                  | [fb01882d07](https://linux-hardware.org/?probe=fb01882d07) | Aug 06, 2022 |
| MSI        | Z97 GAMING 7                | [01cf6a0897](https://linux-hardware.org/?probe=01cf6a0897) | Aug 06, 2022 |
| MSI        | MAG Z490 TOMAHAWK           | [1340311493](https://linux-hardware.org/?probe=1340311493) | Aug 06, 2022 |
| Gigabyte   | B450 I AORUS PRO WIFI-CF    | [6fa2b142e4](https://linux-hardware.org/?probe=6fa2b142e4) | Aug 06, 2022 |
| Gigabyte   | B450 I AORUS PRO WIFI-CF    | [e5e72c1264](https://linux-hardware.org/?probe=e5e72c1264) | Aug 05, 2022 |
| ASUSTek    | ROG Maximus XI HERO         | [d725206bff](https://linux-hardware.org/?probe=d725206bff) | Aug 04, 2022 |
| Lenovo     | SHARKBAY SDK0E50510 WIN     | [42469385bc](https://linux-hardware.org/?probe=42469385bc) | Aug 04, 2022 |
| ASUSTek    | P8H67                       | [b1b842e547](https://linux-hardware.org/?probe=b1b842e547) | Jul 29, 2022 |
| HP         | 8459                        | [a1d6ae45cb](https://linux-hardware.org/?probe=a1d6ae45cb) | Jul 28, 2022 |
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
| Shuttle    | NC01U V1.0                  | [1177e7dbe0](https://linux-hardware.org/?probe=1177e7dbe0) | Jul 21, 2022 |
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
| 5.15.0-46-generic          | 12       | 9.52%   |
| 5.15.0-43-generic          | 12       | 9.52%   |
| 5.15.0-27-generic          | 12       | 9.52%   |
| 5.15.0-47-generic          | 11       | 8.73%   |
| 5.15.0-40-generic          | 11       | 8.73%   |
| 5.15.0-41-generic          | 10       | 7.94%   |
| 5.15.0-48-generic          | 7        | 5.56%   |
| 5.15.0-30-generic          | 6        | 4.76%   |
| 5.15.0-25-generic          | 5        | 3.97%   |
| 5.15.0-37-generic          | 4        | 3.17%   |
| 5.15.0-33-generic          | 4        | 3.17%   |
| 5.15.0-48-lowlatency       | 3        | 2.38%   |
| 5.15.0-27-lowlatency       | 3        | 2.38%   |
| 5.15.0-47-lowlatency       | 2        | 1.59%   |
| 5.15.0-39-generic          | 2        | 1.59%   |
| 5.4.0-122-generic          | 1        | 0.79%   |
| 5.18.4-xanmod1             | 1        | 0.79%   |
| 5.18.4-vitodoc             | 1        | 0.79%   |
| 5.18.12-051812-generic     | 1        | 0.79%   |
| 5.18.10-051810-generic     | 1        | 0.79%   |
| 5.17.6-051706-generic      | 1        | 0.79%   |
| 5.17.14-xanmod1            | 1        | 0.79%   |
| 5.17.0-12.1-liquorix-amd64 | 1        | 0.79%   |
| 5.17.0-051700-generic      | 1        | 0.79%   |
| 5.16.0-051600rc3-generic   | 1        | 0.79%   |
| 5.15.13-051513-generic     | 1        | 0.79%   |
| 5.15.0-50-generic          | 1        | 0.79%   |
| 5.15.0-46-lowlatency       | 1        | 0.79%   |
| 5.15.0-43-lowlatency       | 1        | 0.79%   |
| 5.15.0-37-lowlatency       | 1        | 0.79%   |
| 5.15.0-35-lowlatency       | 1        | 0.79%   |
| 5.15.0-35-generic          | 1        | 0.79%   |
| 5.15.0-30-lowlatency       | 1        | 0.79%   |
| 5.15.0-22-generic          | 1        | 0.79%   |
| 5.15.0-18-generic          | 1        | 0.79%   |
| 5.15.0-13-generic          | 1        | 0.79%   |
| 5.13.0-19-generic          | 1        | 0.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 109      | 90.08%  |
| 5.18.4  | 2        | 1.65%   |
| 5.17.0  | 2        | 1.65%   |
| 5.4.0   | 1        | 0.83%   |
| 5.18.12 | 1        | 0.83%   |
| 5.18.10 | 1        | 0.83%   |
| 5.17.6  | 1        | 0.83%   |
| 5.17.14 | 1        | 0.83%   |
| 5.16.0  | 1        | 0.83%   |
| 5.15.13 | 1        | 0.83%   |
| 5.13.0  | 1        | 0.83%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 110      | 90.91%  |
| 5.18    | 4        | 3.31%   |
| 5.17    | 4        | 3.31%   |
| 5.4     | 1        | 0.83%   |
| 5.16    | 1        | 0.83%   |
| 5.13    | 1        | 0.83%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 119      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| KDE5 | 119      | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 113      | 94.96%  |
| Wayland | 4        | 3.36%   |
| Tty     | 2        | 1.68%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 86       | 71.07%  |
| Unknown | 27       | 22.31%  |
| GDM3    | 6        | 4.96%   |
| LightDM | 2        | 1.65%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 58       | 48.74%  |
| fr_FR | 8        | 6.72%   |
| en_GB | 7        | 5.88%   |
| ru_RU | 6        | 5.04%   |
| it_IT | 5        | 4.2%    |
| en_AU | 5        | 4.2%    |
| de_DE | 5        | 4.2%    |
| pt_BR | 4        | 3.36%   |
| pl_PL | 3        | 2.52%   |
| en_CA | 3        | 2.52%   |
| en_ZA | 2        | 1.68%   |
| sl_SI | 1        | 0.84%   |
| nl_NL | 1        | 0.84%   |
| es_ES | 1        | 0.84%   |
| es_CO | 1        | 0.84%   |
| es_AR | 1        | 0.84%   |
| en_IN | 1        | 0.84%   |
| en_IL | 1        | 0.84%   |
| en_AG | 1        | 0.84%   |
| el_GR | 1        | 0.84%   |
| de_CH | 1        | 0.84%   |
| de_AT | 1        | 0.84%   |
| cs_CZ | 1        | 0.84%   |
| C     | 1        | 0.84%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 71       | 59.17%  |
| EFI  | 49       | 40.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 102      | 85.71%  |
| Btrfs   | 9        | 7.56%   |
| Overlay | 6        | 5.04%   |
| Xfs     | 1        | 0.84%   |
| Ext3    | 1        | 0.84%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 59       | 48.76%  |
| Unknown | 57       | 47.11%  |
| MBR     | 5        | 4.13%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 103      | 85.12%  |
| Yes       | 18       | 14.88%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 65       | 54.62%  |
| Yes       | 54       | 45.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 31       | 26.05%  |
| Gigabyte Technology | 23       | 19.33%  |
| MSI                 | 19       | 15.97%  |
| ASRock              | 11       | 9.24%   |
| Dell                | 8        | 6.72%   |
| Lenovo              | 5        | 4.2%    |
| Hewlett-Packard     | 5        | 4.2%    |
| Supermicro          | 3        | 2.52%   |
| Fujitsu             | 2        | 1.68%   |
| Biostar             | 2        | 1.68%   |
| Acer                | 2        | 1.68%   |
| Shuttle             | 1        | 0.84%   |
| Positivo            | 1        | 0.84%   |
| Pegatron            | 1        | 0.84%   |
| OEM                 | 1        | 0.84%   |
| Huanan              | 1        | 0.84%   |
| AZW                 | 1        | 0.84%   |
| Apple               | 1        | 0.84%   |
| ABIT                | 1        | 0.84%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Desktops | Percent |
|-----------------------------------------|----------|---------|
| ASUS All Series                         | 5        | 4.2%    |
| Gigabyte B450M DS3H                     | 3        | 2.52%   |
| Supermicro SKAGIT09                     | 2        | 1.68%   |
| MSI MS-7C56                             | 2        | 1.68%   |
| MSI MS-7B86                             | 2        | 1.68%   |
| MSI MS-7B79                             | 2        | 1.68%   |
| Gigabyte X570 GAMING X                  | 2        | 1.68%   |
| Gigabyte B450 I AORUS PRO WIFI          | 2        | 1.68%   |
| ASUS ROG ZENITH EXTREME                 | 2        | 1.68%   |
| ASUS ROG STRIX B550-F GAMING            | 2        | 1.68%   |
| Supermicro X8ST3                        | 1        | 0.84%   |
| Shuttle NC01U                           | 1        | 0.84%   |
| Positivo POS-PARS760GCD                 | 1        | 0.84%   |
| Pegatron p6740la                        | 1        | 0.84%   |
| OEM G41 775 ICH7 8712                   | 1        | 0.84%   |
| MSI MS-7D54                             | 1        | 0.84%   |
| MSI MS-7D09                             | 1        | 0.84%   |
| MSI MS-7C95                             | 1        | 0.84%   |
| MSI MS-7C80                             | 1        | 0.84%   |
| MSI MS-7C37                             | 1        | 0.84%   |
| MSI MS-7B98                             | 1        | 0.84%   |
| MSI MS-7B89                             | 1        | 0.84%   |
| MSI MS-7B84                             | 1        | 0.84%   |
| MSI MS-7A78                             | 1        | 0.84%   |
| MSI MS-7A34                             | 1        | 0.84%   |
| MSI MS-7A21                             | 1        | 0.84%   |
| MSI MS-7916                             | 1        | 0.84%   |
| MSI MS-7693                             | 1        | 0.84%   |
| Lenovo ThinkCentre M90p 5498A2U         | 1        | 0.84%   |
| Lenovo ThinkCentre M83 10AM000UUS       | 1        | 0.84%   |
| Lenovo ThinkCentre M83 10AHS2XB00       | 1        | 0.84%   |
| Lenovo ThinkCentre M79 10JAS01500       | 1        | 0.84%   |
| Lenovo IdeaCentre 510S-08IKL 90GB00DLGE | 1        | 0.84%   |
| Huanan X99-F8 GAMING V5.0               | 1        | 0.84%   |
| HP Slim Desktop 290-a0xxx               | 1        | 0.84%   |
| HP ProDesk 600 G2 SFF                   | 1        | 0.84%   |
| HP ProDesk 400 G1 SFF                   | 1        | 0.84%   |
| HP EliteDesk 800 G1 SFF                 | 1        | 0.84%   |
| HP Compaq dc7800p Convertible Minitower | 1        | 0.84%   |
| Gigabyte Z77-D3H                        | 1        | 0.84%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUS ROG                | 9        | 7.56%   |
| ASUS All                | 5        | 4.2%    |
| Lenovo ThinkCentre      | 4        | 3.36%   |
| Dell OptiPlex           | 4        | 3.36%   |
| ASUS TUF                | 4        | 3.36%   |
| ASUS PRIME              | 4        | 3.36%   |
| Gigabyte X570           | 3        | 2.52%   |
| Gigabyte B450M          | 3        | 2.52%   |
| Supermicro SKAGIT09     | 2        | 1.68%   |
| MSI MS-7C56             | 2        | 1.68%   |
| MSI MS-7B86             | 2        | 1.68%   |
| MSI MS-7B79             | 2        | 1.68%   |
| HP ProDesk              | 2        | 1.68%   |
| Gigabyte H410M          | 2        | 1.68%   |
| Gigabyte B450           | 2        | 1.68%   |
| Fujitsu ESPRIMO         | 2        | 1.68%   |
| Dell Precision          | 2        | 1.68%   |
| ASRock B550             | 2        | 1.68%   |
| Supermicro X8ST3        | 1        | 0.84%   |
| Shuttle NC01U           | 1        | 0.84%   |
| Positivo POS-PARS760GCD | 1        | 0.84%   |
| Pegatron p6740la        | 1        | 0.84%   |
| OEM G41                 | 1        | 0.84%   |
| MSI MS-7D54             | 1        | 0.84%   |
| MSI MS-7D09             | 1        | 0.84%   |
| MSI MS-7C95             | 1        | 0.84%   |
| MSI MS-7C80             | 1        | 0.84%   |
| MSI MS-7C37             | 1        | 0.84%   |
| MSI MS-7B98             | 1        | 0.84%   |
| MSI MS-7B89             | 1        | 0.84%   |
| MSI MS-7B84             | 1        | 0.84%   |
| MSI MS-7A78             | 1        | 0.84%   |
| MSI MS-7A34             | 1        | 0.84%   |
| MSI MS-7A21             | 1        | 0.84%   |
| MSI MS-7916             | 1        | 0.84%   |
| MSI MS-7693             | 1        | 0.84%   |
| Lenovo IdeaCentre       | 1        | 0.84%   |
| Huanan X99-F8           | 1        | 0.84%   |
| HP Slim                 | 1        | 0.84%   |
| HP EliteDesk            | 1        | 0.84%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 18       | 15.13%  |
| 2020 | 16       | 13.45%  |
| 2019 | 16       | 13.45%  |
| 2021 | 11       | 9.24%   |
| 2017 | 9        | 7.56%   |
| 2013 | 9        | 7.56%   |
| 2014 | 8        | 6.72%   |
| 2016 | 6        | 5.04%   |
| 2015 | 6        | 5.04%   |
| 2012 | 5        | 4.2%    |
| 2011 | 5        | 4.2%    |
| 2010 | 4        | 3.36%   |
| 2008 | 2        | 1.68%   |
| 2007 | 2        | 1.68%   |
| 2022 | 1        | 0.84%   |
| 2009 | 1        | 0.84%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 119      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 118      | 99.16%  |
| Enabled  | 1        | 0.84%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 119      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 45       | 37.5%   |
| 32.01-64.0  | 31       | 25.83%  |
| 8.01-16.0   | 15       | 12.5%   |
| 4.01-8.0    | 11       | 9.17%   |
| 64.01-256.0 | 10       | 8.33%   |
| 3.01-4.0    | 4        | 3.33%   |
| 24.01-32.0  | 4        | 3.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 35       | 28%     |
| 4.01-8.0   | 31       | 24.8%   |
| 3.01-4.0   | 26       | 20.8%   |
| 1.01-2.0   | 21       | 16.8%   |
| 8.01-16.0  | 10       | 8%      |
| 32.01-64.0 | 1        | 0.8%    |
| 0.51-1.0   | 1        | 0.8%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 33       | 27.27%  |
| 1      | 30       | 24.79%  |
| 3      | 28       | 23.14%  |
| 4      | 12       | 9.92%   |
| 5      | 10       | 8.26%   |
| 6      | 5        | 4.13%   |
| 11     | 1        | 0.83%   |
| 9      | 1        | 0.83%   |
| 7      | 1        | 0.83%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 68       | 57.14%  |
| Yes       | 51       | 42.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 118      | 99.16%  |
| No        | 1        | 0.84%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 70       | 58.33%  |
| No        | 50       | 41.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 66       | 55.46%  |
| Yes       | 53       | 44.54%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 25       | 21.01%  |
| Germany      | 10       | 8.4%    |
| UK           | 8        | 6.72%   |
| Russia       | 8        | 6.72%   |
| France       | 8        | 6.72%   |
| Brazil       | 8        | 6.72%   |
| Poland       | 7        | 5.88%   |
| Italy        | 7        | 5.88%   |
| Australia    | 4        | 3.36%   |
| Netherlands  | 3        | 2.52%   |
| Switzerland  | 2        | 1.68%   |
| Spain        | 2        | 1.68%   |
| South Africa | 2        | 1.68%   |
| Slovenia     | 2        | 1.68%   |
| India        | 2        | 1.68%   |
| Canada       | 2        | 1.68%   |
| Bulgaria     | 2        | 1.68%   |
| Austria      | 2        | 1.68%   |
| Thailand     | 1        | 0.84%   |
| Sweden       | 1        | 0.84%   |
| Serbia       | 1        | 0.84%   |
| Portugal     | 1        | 0.84%   |
| New Zealand  | 1        | 0.84%   |
| Malta        | 1        | 0.84%   |
| Malaysia     | 1        | 0.84%   |
| Israel       | 1        | 0.84%   |
| Iran         | 1        | 0.84%   |
| Greece       | 1        | 0.84%   |
| Ecuador      | 1        | 0.84%   |
| Czechia      | 1        | 0.84%   |
| Colombia     | 1        | 0.84%   |
| Belgium      | 1        | 0.84%   |
| Argentina    | 1        | 0.84%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Moscow               | 3        | 2.48%   |
| Wroclaw              | 2        | 1.65%   |
| Washington           | 2        | 1.65%   |
| Vienna               | 2        | 1.65%   |
| Rio de Janeiro       | 2        | 1.65%   |
| Canberra             | 2        | 1.65%   |
| Brasília            | 2        | 1.65%   |
| Bougival             | 2        | 1.65%   |
| Berlin               | 2        | 1.65%   |
| Zaandam              | 1        | 0.83%   |
| Wembley              | 1        | 0.83%   |
| Waukee               | 1        | 0.83%   |
| Vrhnika              | 1        | 0.83%   |
| Vladivostok          | 1        | 0.83%   |
| Villa Nueva          | 1        | 0.83%   |
| Varna                | 1        | 0.83%   |
| Ustron               | 1        | 0.83%   |
| Union City           | 1        | 0.83%   |
| Turin                | 1        | 0.83%   |
| Torun                | 1        | 0.83%   |
| Therwil              | 1        | 0.83%   |
| Templeton            | 1        | 0.83%   |
| Tehran               | 1        | 0.83%   |
| Sydney               | 1        | 0.83%   |
| Sunbury-on-Thames    | 1        | 0.83%   |
| St Petersburg        | 1        | 0.83%   |
| Southport            | 1        | 0.83%   |
| Sofia                | 1        | 0.83%   |
| Sliema               | 1        | 0.83%   |
| Sedziszow Malopolski | 1        | 0.83%   |
| Saskatoon            | 1        | 0.83%   |
| Sao Paulo            | 1        | 0.83%   |
| San Bernardino       | 1        | 0.83%   |
| Rudolstadt           | 1        | 0.83%   |
| Rishon LeZiyyon      | 1        | 0.83%   |
| Rethymno             | 1        | 0.83%   |
| Reggio Emilia        | 1        | 0.83%   |
| Redditch             | 1        | 0.83%   |
| Pretoria             | 1        | 0.83%   |
| Prague               | 1        | 0.83%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Samsung Electronics       | 40       | 61     | 16.39%  |
| Seagate                   | 39       | 77     | 15.98%  |
| WDC                       | 38       | 60     | 15.57%  |
| Kingston                  | 20       | 24     | 8.2%    |
| Toshiba                   | 16       | 18     | 6.56%   |
| SanDisk                   | 13       | 14     | 5.33%   |
| Crucial                   | 12       | 15     | 4.92%   |
| Hitachi                   | 9        | 9      | 3.69%   |
| Patriot                   | 5        | 5      | 2.05%   |
| Intel                     | 5        | 5      | 2.05%   |
| Transcend                 | 3        | 4      | 1.23%   |
| HGST                      | 3        | 4      | 1.23%   |
| China                     | 3        | 4      | 1.23%   |
| A-DATA Technology         | 3        | 4      | 1.23%   |
| Unknown                   | 2        | 2      | 0.82%   |
| Phison Electronics        | 2        | 2      | 0.82%   |
| Phison                    | 2        | 2      | 0.82%   |
| KODAK                     | 2        | 2      | 0.82%   |
| XPG                       | 1        | 1      | 0.41%   |
| Verbatim                  | 1        | 1      | 0.41%   |
| USB3.0                    | 1        | 1      | 0.41%   |
| Smartbuy                  | 1        | 1      | 0.41%   |
| SK hynix                  | 1        | 2      | 0.41%   |
| Realtek Semiconductor     | 1        | 1      | 0.41%   |
| PNY                       | 1        | 1      | 0.41%   |
| Plextor                   | 1        | 1      | 0.41%   |
| OCZ                       | 1        | 1      | 0.41%   |
| Micron/Crucial Technology | 1        | 1      | 0.41%   |
| Micron Technology         | 1        | 1      | 0.41%   |
| Maxtor                    | 1        | 1      | 0.41%   |
| KIOXIA                    | 1        | 1      | 0.41%   |
| KingFast                  | 1        | 1      | 0.41%   |
| JMicron Technology        | 1        | 1      | 0.41%   |
| Intenso                   | 1        | 1      | 0.41%   |
| INNOVATION IT             | 1        | 1      | 0.41%   |
| INDMEM                    | 1        | 1      | 0.41%   |
| IET                       | 1        | 1      | 0.41%   |
| GOODRAM                   | 1        | 1      | 0.41%   |
| Gigabyte Technology       | 1        | 1      | 0.41%   |
| Emtec                     | 1        | 1      | 0.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST4000DM004-2CV104 4TB   | 6        | 2.05%   |
| Kingston SA400S37240G 240GB SSD  | 6        | 2.05%   |
| Toshiba DT01ACA100 1TB           | 4        | 1.37%   |
| SanDisk NVMe SSD Drive 500GB     | 4        | 1.37%   |
| Samsung NVMe SSD Drive 500GB     | 4        | 1.37%   |
| WDC WD10EZEX-22MFCA0 1TB         | 3        | 1.02%   |
| Samsung SSD 870 EVO 1TB          | 3        | 1.02%   |
| Samsung SSD 860 EVO 1TB          | 3        | 1.02%   |
| Crucial CT500MX500SSD1 500GB     | 3        | 1.02%   |
| Crucial CT240BX500SSD1 240GB     | 3        | 1.02%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 2        | 0.68%   |
| WDC WD5000AADS-00S9B0 500GB      | 2        | 0.68%   |
| WDC WD40EFAX-68JH4N1 4TB         | 2        | 0.68%   |
| WDC WD10EZEX-08WN4A0 1TB         | 2        | 0.68%   |
| Toshiba HDWD110 1TB              | 2        | 0.68%   |
| Seagate ST4000VN008-2DR166 4TB   | 2        | 0.68%   |
| Seagate ST2000DM008-2FR102 2TB   | 2        | 0.68%   |
| Seagate ST2000DM006-2DM164 2TB   | 2        | 0.68%   |
| Seagate ST1000DM003-1SB102 1TB   | 2        | 0.68%   |
| Seagate Expansion Desk 2TB       | 2        | 0.68%   |
| Samsung SSD 980 1TB              | 2        | 0.68%   |
| Samsung SSD 970 EVO Plus 2TB     | 2        | 0.68%   |
| Samsung SSD 860 EVO 500GB        | 2        | 0.68%   |
| Samsung SSD 850 EVO 500GB        | 2        | 0.68%   |
| Samsung SSD 850 EVO 120GB        | 2        | 0.68%   |
| Samsung SSD 840 PRO Series 128GB | 2        | 0.68%   |
| Samsung HD103SI 1TB              | 2        | 0.68%   |
| Phison PCIe SSD 240GB            | 2        | 0.68%   |
| Patriot Burst 120GB SSD          | 2        | 0.68%   |
| KODAK SSD X100 480GB             | 2        | 0.68%   |
| Kingston SV300S37A120G 120GB SSD | 2        | 0.68%   |
| Kingston SA2000M81000G 1TB       | 2        | 0.68%   |
| Kingston NVMe SSD Drive 500GB    | 2        | 0.68%   |
| Hitachi HTS547550A9E384 500GB    | 2        | 0.68%   |
| Hitachi HDS721010CLA332 1TB      | 2        | 0.68%   |
| Crucial CT500P2SSD8 500GB        | 2        | 0.68%   |
| XPG NVMe SSD Drive 1024GB        | 1        | 0.34%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1        | 0.34%   |
| WDC WDS500G1X0E-00AFY0 500GB     | 1        | 0.34%   |
| WDC WDS480G2G0A-00JH30 480GB SSD | 1        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 37       | 70     | 35.24%  |
| WDC                 | 34       | 47     | 32.38%  |
| Toshiba             | 13       | 15     | 12.38%  |
| Hitachi             | 9        | 9      | 8.57%   |
| Samsung Electronics | 6        | 6      | 5.71%   |
| HGST                | 3        | 4      | 2.86%   |
| USB3.0              | 1        | 1      | 0.95%   |
| JMicron Technology  | 1        | 1      | 0.95%   |
| IET                 | 1        | 1      | 0.95%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 24       | 31     | 23.76%  |
| Kingston            | 16       | 17     | 15.84%  |
| Crucial             | 10       | 11     | 9.9%    |
| WDC                 | 8        | 10     | 7.92%   |
| SanDisk             | 7        | 7      | 6.93%   |
| Patriot             | 5        | 5      | 4.95%   |
| Toshiba             | 3        | 3      | 2.97%   |
| Intel               | 3        | 3      | 2.97%   |
| China               | 3        | 4      | 2.97%   |
| Transcend           | 2        | 2      | 1.98%   |
| KODAK               | 2        | 2      | 1.98%   |
| A-DATA Technology   | 2        | 3      | 1.98%   |
| Verbatim            | 1        | 1      | 0.99%   |
| Smartbuy            | 1        | 1      | 0.99%   |
| PNY                 | 1        | 1      | 0.99%   |
| Plextor             | 1        | 1      | 0.99%   |
| OCZ                 | 1        | 1      | 0.99%   |
| Micron Technology   | 1        | 1      | 0.99%   |
| Maxtor              | 1        | 1      | 0.99%   |
| KingFast            | 1        | 1      | 0.99%   |
| Intenso             | 1        | 1      | 0.99%   |
| INNOVATION IT       | 1        | 1      | 0.99%   |
| INDMEM              | 1        | 1      | 0.99%   |
| GOODRAM             | 1        | 1      | 0.99%   |
| Drevo               | 1        | 1      | 0.99%   |
| Apple               | 1        | 1      | 0.99%   |
| Apacer              | 1        | 1      | 0.99%   |
| Aireye              | 1        | 1      | 0.99%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 84       | 114    | 40.58%  |
| HDD     | 80       | 154    | 38.65%  |
| NVMe    | 41       | 71     | 19.81%  |
| MMC     | 1        | 1      | 0.48%   |
| Unknown | 1        | 1      | 0.48%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 110      | 250    | 67.07%  |
| NVMe | 41       | 71     | 25%     |
| SAS  | 12       | 19     | 7.32%   |
| MMC  | 1        | 1      | 0.61%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 83       | 124    | 45.6%   |
| 0.51-1.0   | 48       | 68     | 26.37%  |
| 3.01-4.0   | 18       | 30     | 9.89%   |
| 1.01-2.0   | 18       | 24     | 9.89%   |
| 2.01-3.0   | 7        | 9      | 3.85%   |
| 4.01-10.0  | 6        | 11     | 3.3%    |
| 10.01-20.0 | 2        | 2      | 1.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 24       | 19.51%  |
| 1001-2000      | 23       | 18.7%   |
| More than 3000 | 22       | 17.89%  |
| 101-250        | 18       | 14.63%  |
| 2001-3000      | 16       | 13.01%  |
| 251-500        | 13       | 10.57%  |
| 1-20           | 4        | 3.25%   |
| 51-100         | 2        | 1.63%   |
| Unknown        | 1        | 0.81%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 19       | 15.32%  |
| 101-250        | 17       | 13.71%  |
| 1-20           | 17       | 13.71%  |
| 51-100         | 17       | 13.71%  |
| 251-500        | 15       | 12.1%   |
| More than 3000 | 10       | 8.06%   |
| 21-50          | 10       | 8.06%   |
| 1001-2000      | 10       | 8.06%   |
| 2001-3000      | 8        | 6.45%   |
| Unknown        | 1        | 0.81%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| WDC WD5000AVVS-63M8B0 500GB              | 1        | 1      | 6.25%   |
| WDC WD10EZEX-22MFCA0 1TB                 | 1        | 1      | 6.25%   |
| Seagate ST500LT012-9WS142 500GB          | 1        | 1      | 6.25%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 1        | 1      | 6.25%   |
| Seagate ST500DM002-1BD142 500GB          | 1        | 1      | 6.25%   |
| Seagate ST3160827AS 160GB                | 1        | 1      | 6.25%   |
| Seagate ST31500341AS 1TB                 | 1        | 1      | 6.25%   |
| Seagate ST31000524AS 1TB                 | 1        | 2      | 6.25%   |
| Seagate ST1000DM003-1SB102 1TB           | 1        | 1      | 6.25%   |
| Seagate ST1000DM003-1CH162 1TB           | 1        | 1      | 6.25%   |
| Samsung Electronics SSD 870 EVO 1TB      | 1        | 1      | 6.25%   |
| Samsung Electronics SSD 840 Series 250GB | 1        | 1      | 6.25%   |
| Samsung Electronics HM321HI 320GB        | 1        | 1      | 6.25%   |
| Samsung Electronics HD103SI 1TB          | 1        | 1      | 6.25%   |
| Hitachi HDP725050GLA360 500GB            | 1        | 1      | 6.25%   |
| Hitachi HCT721010SLA360 1TB              | 1        | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 7        | 9      | 46.67%  |
| Samsung Electronics | 4        | 4      | 26.67%  |
| WDC                 | 2        | 2      | 13.33%  |
| Hitachi             | 2        | 2      | 13.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 7        | 9      | 53.85%  |
| WDC                 | 2        | 2      | 15.38%  |
| Samsung Electronics | 2        | 2      | 15.38%  |
| Hitachi             | 2        | 2      | 15.38%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 12       | 15     | 85.71%  |
| SSD  | 2        | 2      | 14.29%  |

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
| Works    | 63       | 160    | 45.65%  |
| Detected | 60       | 162    | 43.48%  |
| Malfunc  | 14       | 17     | 10.14%  |
| Failed   | 1        | 2      | 0.72%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 64       | 34.04%  |
| AMD                         | 54       | 28.72%  |
| Samsung Electronics         | 18       | 9.57%   |
| ASMedia Technology          | 10       | 5.32%   |
| SanDisk                     | 8        | 4.26%   |
| Kingston Technology Company | 6        | 3.19%   |
| Phison Electronics          | 5        | 2.66%   |
| Micron/Crucial Technology   | 4        | 2.13%   |
| JMicron Technology          | 4        | 2.13%   |
| Seagate Technology          | 3        | 1.6%    |
| LSI Logic / Symbios Logic   | 2        | 1.06%   |
| ADATA Technology            | 2        | 1.06%   |
| VIA Technologies            | 1        | 0.53%   |
| Unknown                     | 1        | 0.53%   |
| SK hynix                    | 1        | 0.53%   |
| Silicon Motion              | 1        | 0.53%   |
| Silicon Image               | 1        | 0.53%   |
| Realtek Semiconductor       | 1        | 0.53%   |
| Marvell Technology Group    | 1        | 0.53%   |
| KIOXIA                      | 1        | 0.53%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 33       | 14.16%  |
| AMD 400 Series Chipset SATA Controller                                         | 15       | 6.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 11       | 4.72%   |
| AMD 500 Series Chipset SATA Controller                                         | 11       | 4.72%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 9        | 3.86%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 9        | 3.86%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 6        | 2.58%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 6        | 2.58%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 5        | 2.15%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 5        | 2.15%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4        | 1.72%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4        | 1.72%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4        | 1.72%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4        | 1.72%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 4        | 1.72%   |
| SanDisk Non-Volatile memory controller                                         | 3        | 1.29%   |
| Samsung NVMe SSD Controller 980                                                | 3        | 1.29%   |
| Phison E12 NVMe Controller                                                     | 3        | 1.29%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 3        | 1.29%   |
| Kingston Company Company Non-Volatile memory controller                        | 3        | 1.29%   |
| Kingston Company A2000 NVMe SSD                                                | 3        | 1.29%   |
| Intel SATA Controller [RAID mode]                                              | 3        | 1.29%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 3        | 1.29%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 3        | 1.29%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 3        | 1.29%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 3        | 1.29%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3        | 1.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3        | 1.29%   |
| AMD X399 Series Chipset SATA Controller                                        | 3        | 1.29%   |
| AMD 300 Series Chipset SATA Controller                                         | 3        | 1.29%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2        | 0.86%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2        | 0.86%   |
| LSI Logic / Symbios Logic MegaRAID SAS 1078                                    | 2        | 0.86%   |
| JMicron JMB368 IDE controller                                                  | 2        | 0.86%   |
| JMicron JMB363 SATA/IDE Controller                                             | 2        | 0.86%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2        | 0.86%   |
| Intel SSD 660P Series                                                          | 2        | 0.86%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2        | 0.86%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]            | 2        | 0.86%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2        | 0.86%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 111      | 63.43%  |
| NVMe | 41       | 23.43%  |
| IDE  | 15       | 8.57%   |
| RAID | 8        | 4.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 65       | 54.62%  |
| AMD    | 54       | 45.38%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor             | 5        | 4.2%    |
| Intel Core i7-4790K CPU @ 4.00GHz              | 3        | 2.52%   |
| Intel Core i5-10400F CPU @ 2.90GHz             | 3        | 2.52%   |
| AMD Ryzen 5 3600 6-Core Processor              | 3        | 2.52%   |
| Intel Core i7-6700 CPU @ 3.40GHz               | 2        | 1.68%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 2        | 1.68%   |
| Intel Core i3-4130 CPU @ 3.40GHz               | 2        | 1.68%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz           | 2        | 1.68%   |
| AMD Ryzen Threadripper 1950X 16-Core Processor | 2        | 1.68%   |
| AMD Ryzen 9 5950X 16-Core Processor            | 2        | 1.68%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 2        | 1.68%   |
| AMD Ryzen 7 5700G with Radeon Graphics         | 2        | 1.68%   |
| AMD Ryzen 7 3700X 8-Core Processor             | 2        | 1.68%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 2        | 1.68%   |
| AMD Ryzen 7 2700 Eight-Core Processor          | 2        | 1.68%   |
| AMD Ryzen 5 5600 6-Core Processor              | 2        | 1.68%   |
| AMD Ryzen 5 2600X Six-Core Processor           | 2        | 1.68%   |
| Intel Xeon CPU X3440 @ 2.53GHz                 | 1        | 0.84%   |
| Intel Xeon CPU E5-4627 v4 @ 2.60GHz            | 1        | 0.84%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz            | 1        | 0.84%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz            | 1        | 0.84%   |
| Intel Xeon CPU E5-1620 v2 @ 3.70GHz            | 1        | 0.84%   |
| Intel Xeon CPU E3-1275 V2 @ 3.50GHz            | 1        | 0.84%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz         | 1        | 0.84%   |
| Intel Pentium CPU J4205 @ 1.50GHz              | 1        | 0.84%   |
| Intel Pentium CPU G3430 @ 3.30GHz              | 1        | 0.84%   |
| Intel Pentium CPU G3220 @ 3.00GHz              | 1        | 0.84%   |
| Intel Core i9-9900 CPU @ 3.10GHz               | 1        | 0.84%   |
| Intel Core i9-10850K CPU @ 3.60GHz             | 1        | 0.84%   |
| Intel Core i7-8700K CPU @ 3.70GHz              | 1        | 0.84%   |
| Intel Core i7-7700K CPU @ 4.20GHz              | 1        | 0.84%   |
| Intel Core i7-6900K CPU @ 3.20GHz              | 1        | 0.84%   |
| Intel Core i7-6700K CPU @ 4.00GHz              | 1        | 0.84%   |
| Intel Core i7-5820K CPU @ 3.30GHz              | 1        | 0.84%   |
| Intel Core i7-4771 CPU @ 3.50GHz               | 1        | 0.84%   |
| Intel Core i7-4770S CPU @ 3.10GHz              | 1        | 0.84%   |
| Intel Core i7-4770 CPU @ 3.40GHz               | 1        | 0.84%   |
| Intel Core i7-3930K CPU @ 3.20GHz              | 1        | 0.84%   |
| Intel Core i7-3770K CPU @ 3.50GHz              | 1        | 0.84%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 1        | 0.84%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i7          | 20       | 16.81%  |
| AMD Ryzen 5            | 17       | 14.29%  |
| Intel Core i5          | 16       | 13.45%  |
| AMD Ryzen 7            | 11       | 9.24%   |
| Intel Xeon             | 6        | 5.04%   |
| Intel Core i3          | 6        | 5.04%   |
| AMD Ryzen 9            | 6        | 5.04%   |
| Other                  | 5        | 4.2%    |
| AMD Ryzen 3            | 4        | 3.36%   |
| Intel Pentium          | 3        | 2.52%   |
| Intel Core 2 Duo       | 3        | 2.52%   |
| AMD Ryzen Threadripper | 3        | 2.52%   |
| AMD FX                 | 3        | 2.52%   |
| Intel Core i9          | 2        | 1.68%   |
| Intel Core 2 Quad      | 2        | 1.68%   |
| AMD Phenom II X2       | 2        | 1.68%   |
| AMD Opteron            | 2        | 1.68%   |
| Intel Pentium Gold     | 1        | 0.84%   |
| Intel Celeron          | 1        | 0.84%   |
| AMD Ryzen 7 PRO        | 1        | 0.84%   |
| AMD Phenom II X4       | 1        | 0.84%   |
| AMD E1                 | 1        | 0.84%   |
| AMD A8                 | 1        | 0.84%   |
| AMD A6                 | 1        | 0.84%   |
| AMD A4                 | 1        | 0.84%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 45       | 37.82%  |
| 6      | 28       | 23.53%  |
| 8      | 17       | 14.29%  |
| 2      | 16       | 13.45%  |
| 16     | 6        | 5.04%   |
| 12     | 4        | 3.36%   |
| 10     | 2        | 1.68%   |
| 1      | 1        | 0.84%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 119      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 84       | 70.59%  |
| 1      | 35       | 29.41%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 119      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 54       | 44.63%  |
| 0x08701021 | 7        | 5.79%   |
| 0x306c3    | 6        | 4.96%   |
| 0x906e9    | 4        | 3.31%   |
| 0x0800820d | 4        | 3.31%   |
| 0xa0653    | 3        | 2.48%   |
| 0x0a201205 | 3        | 2.48%   |
| 0x010000c8 | 3        | 2.48%   |
| 0xa0655    | 2        | 1.65%   |
| 0x906ed    | 2        | 1.65%   |
| 0x90672    | 2        | 1.65%   |
| 0x406f1    | 2        | 1.65%   |
| 0x306a9    | 2        | 1.65%   |
| 0x0a50000c | 2        | 1.65%   |
| 0x0a201016 | 2        | 1.65%   |
| 0x0a201009 | 2        | 1.65%   |
| 0x08001138 | 2        | 1.65%   |
| 0x906ea    | 1        | 0.83%   |
| 0x6fb      | 1        | 0.83%   |
| 0x506e3    | 1        | 0.83%   |
| 0x306f2    | 1        | 0.83%   |
| 0x306e4    | 1        | 0.83%   |
| 0x206d6    | 1        | 0.83%   |
| 0x206a7    | 1        | 0.83%   |
| 0x106e5    | 1        | 0.83%   |
| 0x106a5    | 1        | 0.83%   |
| 0x1067a    | 1        | 0.83%   |
| 0x0a20120a | 1        | 0.83%   |
| 0x0a201204 | 1        | 0.83%   |
| 0x08701013 | 1        | 0.83%   |
| 0x08600106 | 1        | 0.83%   |
| 0x08001137 | 1        | 0.83%   |
| 0x08001136 | 1        | 0.83%   |
| 0x07030106 | 1        | 0.83%   |
| 0x06000852 | 1        | 0.83%   |
| 0x00000000 | 1        | 0.83%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 17       | 14.17%  |
| Zen 3            | 15       | 12.5%   |
| Zen 2            | 12       | 10%     |
| KabyLake         | 10       | 8.33%   |
| Zen+             | 9        | 7.5%    |
| Zen              | 6        | 5%      |
| Piledriver       | 6        | 5%      |
| IvyBridge        | 6        | 5%      |
| CometLake        | 6        | 5%      |
| Skylake          | 5        | 4.17%   |
| K10              | 4        | 3.33%   |
| Unknown          | 4        | 3.33%   |
| SandyBridge      | 3        | 2.5%    |
| Penryn           | 3        | 2.5%    |
| Nehalem          | 3        | 2.5%    |
| Broadwell        | 3        | 2.5%    |
| Core             | 2        | 1.67%   |
| Alderlake Hybrid | 2        | 1.67%   |
| Westmere         | 1        | 0.83%   |
| Puma             | 1        | 0.83%   |
| Goldmont         | 1        | 0.83%   |
| Excavator        | 1        | 0.83%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 65       | 50.39%  |
| AMD                        | 40       | 31.01%  |
| Intel                      | 22       | 17.05%  |
| Matrox Electronics Systems | 2        | 1.55%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 9        | 6.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7        | 5.43%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 6        | 4.65%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 4        | 3.1%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 3.1%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 2.33%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 2.33%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 3        | 2.33%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 2        | 1.55%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 1.55%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 2        | 1.55%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 1.55%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 1.55%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 1.55%   |
| Nvidia G92 [GeForce 9800 GT]                                                | 2        | 1.55%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 2        | 1.55%   |
| Intel HD Graphics 630                                                       | 2        | 1.55%   |
| Intel HD Graphics 530                                                       | 2        | 1.55%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 1.55%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.55%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                           | 2        | 1.55%   |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                           | 2        | 1.55%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 1.55%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 1.55%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 1.55%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 2        | 1.55%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 2        | 1.55%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.78%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.78%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.78%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 0.78%   |
| Nvidia TU106 [GeForce RTX 2060 12GB]                                        | 1        | 0.78%   |
| Nvidia TU104 [GeForce RTX 2080]                                             | 1        | 0.78%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                          | 1        | 0.78%   |
| Nvidia GP106GL [Quadro P2000]                                               | 1        | 0.78%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.78%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 0.78%   |
| Nvidia GP104 [GeForce GTX 1060 6GB]                                         | 1        | 0.78%   |
| Nvidia GM206 [GeForce GTX 750 v2]                                           | 1        | 0.78%   |
| Nvidia GM204GL [Quadro M4000]                                               | 1        | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 62       | 52.1%   |
| 1 x AMD                  | 35       | 29.41%  |
| 1 x Intel                | 16       | 13.45%  |
| 2 x Nvidia               | 1        | 0.84%   |
| 2 x AMD                  | 1        | 0.84%   |
| Nvidia + Matrox          | 1        | 0.84%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.84%   |
| Intel + AMD              | 1        | 0.84%   |
| AMD + Matrox             | 1        | 0.84%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 65       | 54.62%  |
| Proprietary | 51       | 42.86%  |
| Unknown     | 3        | 2.52%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 49       | 39.84%  |
| 7.01-8.0   | 18       | 14.63%  |
| 3.01-4.0   | 14       | 11.38%  |
| 5.01-6.0   | 10       | 8.13%   |
| 1.01-2.0   | 10       | 8.13%   |
| 0.51-1.0   | 10       | 8.13%   |
| 8.01-16.0  | 6        | 4.88%   |
| 0.01-0.5   | 3        | 2.44%   |
| 4.01-5.0   | 1        | 0.81%   |
| 2.01-3.0   | 1        | 0.81%   |
| 16.01-24.0 | 1        | 0.81%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 29       | 19.86%  |
| Dell                 | 18       | 12.33%  |
| Hewlett-Packard      | 14       | 9.59%   |
| Goldstar             | 12       | 8.22%   |
| AOC                  | 10       | 6.85%   |
| Acer                 | 10       | 6.85%   |
| BenQ                 | 8        | 5.48%   |
| Philips              | 6        | 4.11%   |
| Iiyama               | 6        | 4.11%   |
| Ancor Communications | 5        | 3.42%   |
| Sony                 | 4        | 2.74%   |
| ASUSTek Computer     | 3        | 2.05%   |
| NEC Computers        | 2        | 1.37%   |
| Idek Iiyama          | 2        | 1.37%   |
| Vizio                | 1        | 0.68%   |
| Vita                 | 1        | 0.68%   |
| Unknown              | 1        | 0.68%   |
| Sunplus              | 1        | 0.68%   |
| STD                  | 1        | 0.68%   |
| Sceptre Tech         | 1        | 0.68%   |
| RTK                  | 1        | 0.68%   |
| QUS                  | 1        | 0.68%   |
| Planar               | 1        | 0.68%   |
| Panasonic            | 1        | 0.68%   |
| LG Electronics       | 1        | 0.68%   |
| Lenovo               | 1        | 0.68%   |
| Fujitsu Siemens      | 1        | 0.68%   |
| Envision Peripherals | 1        | 0.68%   |
| Eizo                 | 1        | 0.68%   |
| Denver               | 1        | 0.68%   |
| CHD                  | 1        | 0.68%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 2        | 1.3%    |
| Hewlett-Packard 24w HPN3431 1920x1080 527x296mm 23.8-inch              | 2        | 1.3%    |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 2        | 1.3%    |
| Goldstar 22EA53 GSM59A5 1920x1080 477x268mm 21.5-inch                  | 2        | 1.3%    |
| Dell P2719H DEL4184 1920x1080 598x336mm 27.0-inch                      | 2        | 1.3%    |
| AOC U3277WB AOC3277 3840x2160 698x393mm 31.5-inch                      | 2        | 1.3%    |
| AOC 27G2G3 AOC2702 1920x1080 598x336mm 27.0-inch                       | 2        | 1.3%    |
| Acer VG240Y ACR06BF 1920x1080 527x296mm 23.8-inch                      | 2        | 1.3%    |
| Vizio E320-B0 VIZ1007 1366x768 697x392mm 31.5-inch                     | 1        | 0.65%   |
| Vita VT988 VIT03DC 1280x1024 376x301mm 19.0-inch                       | 1        | 0.65%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 1        | 0.65%   |
| Sunplus Monitor TV SPVFFFF 1920x1080 376x301mm 19.0-inch               | 1        | 0.65%   |
| STD LED STD0001 2560x1440 330x220mm 15.6-inch                          | 1        | 0.65%   |
| Sony TV SNYEE01 1920x1080                                              | 1        | 0.65%   |
| Sony TV SNYC901 1920x1080                                              | 1        | 0.65%   |
| Sony TV SNY7702 1920x1080 886x498mm 40.0-inch                          | 1        | 0.65%   |
| Sony TV *02 SNY9403 1920x1080 1218x685mm 55.0-inch                     | 1        | 0.65%   |
| Sceptre Tech E24 SPT099D 1920x1080 521x293mm 23.5-inch                 | 1        | 0.65%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch      | 1        | 0.65%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 607x345mm 27.5-inch      | 1        | 0.65%   |
| Samsung Electronics U28D590 SAM0B81 3840x2160 608x345mm 27.5-inch      | 1        | 0.65%   |
| Samsung Electronics U28D590 SAM0B80 3840x2160 610x350mm 27.7-inch      | 1        | 0.65%   |
| Samsung Electronics T19C300 SAM0A98 1366x768 410x230mm 18.5-inch       | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM05CC 1920x1080 530x300mm 24.0-inch   | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch   | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM04E6 1920x1080 477x268mm 21.5-inch   | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM0225 1440x900 410x257mm 19.1-inch    | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch   | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM01DA 1280x1024 376x301mm 19.0-inch   | 1        | 0.65%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 598x336mm 27.0-inch   | 1        | 0.65%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch    | 1        | 0.65%   |
| Samsung Electronics SMB1940 SAM06B9 1280x1024 376x301mm 19.0-inch      | 1        | 0.65%   |
| Samsung Electronics SM2333TN SAM06FC 1920x1080 477x268mm 21.5-inch     | 1        | 0.65%   |
| Samsung Electronics S27B350 SAM08DC 1920x1080 598x336mm 27.0-inch      | 1        | 0.65%   |
| Samsung Electronics S22D390 SAM0B63 1920x1080 477x268mm 21.5-inch      | 1        | 0.65%   |
| Samsung Electronics LCD Monitor SyncMaster 3600x1200                   | 1        | 0.65%   |
| Samsung Electronics LCD Monitor SAM7083 2560x1440 597x336mm 27.0-inch  | 1        | 0.65%   |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 1209x680mm 54.6-inch | 1        | 0.65%   |
| Samsung Electronics LCD Monitor SAM0A74 1280x720 949x543mm 43.0-inch   | 1        | 0.65%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 1020x570mm 46.0-inch | 1        | 0.65%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 68       | 49.64%  |
| 3840x2160 (4K)     | 17       | 12.41%  |
| 2560x1440 (QHD)    | 10       | 7.3%    |
| 1920x1200 (WUXGA)  | 7        | 5.11%   |
| 1680x1050 (WSXGA+) | 7        | 5.11%   |
| 1280x1024 (SXGA)   | 6        | 4.38%   |
| 1600x900 (HD+)     | 4        | 2.92%   |
| 3440x1440          | 3        | 2.19%   |
| 1440x900 (WXGA+)   | 3        | 2.19%   |
| 1366x768 (WXGA)    | 3        | 2.19%   |
| 2560x1080          | 2        | 1.46%   |
| 1280x720 (HD)      | 2        | 1.46%   |
| 3840x1080          | 1        | 0.73%   |
| 3600x1200          | 1        | 0.73%   |
| 2288x1287          | 1        | 0.73%   |
| 1360x768           | 1        | 0.73%   |
| Unknown            | 1        | 0.73%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 32       | 22.38%  |
| 27      | 22       | 15.38%  |
| 21      | 15       | 10.49%  |
| 23      | 13       | 9.09%   |
| 31      | 10       | 6.99%   |
| 19      | 10       | 6.99%   |
| 22      | 7        | 4.9%    |
| 34      | 5        | 3.5%    |
| Unknown | 4        | 2.8%    |
| 46      | 3        | 2.1%    |
| 32      | 3        | 2.1%    |
| 18      | 3        | 2.1%    |
| 72      | 2        | 1.4%    |
| 20      | 2        | 1.4%    |
| 142     | 1        | 0.7%    |
| 65      | 1        | 0.7%    |
| 60      | 1        | 0.7%    |
| 55      | 1        | 0.7%    |
| 54      | 1        | 0.7%    |
| 48      | 1        | 0.7%    |
| 43      | 1        | 0.7%    |
| 40      | 1        | 0.7%    |
| 36      | 1        | 0.7%    |
| 26      | 1        | 0.7%    |
| 25      | 1        | 0.7%    |
| 17      | 1        | 0.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 55       | 41.04%  |
| 401-500        | 32       | 23.88%  |
| 601-700        | 15       | 11.19%  |
| 701-800        | 9        | 6.72%   |
| 1001-1500      | 8        | 5.97%   |
| 351-400        | 5        | 3.73%   |
| Unknown        | 4        | 2.99%   |
| 1501-2000      | 2        | 1.49%   |
| More than 2000 | 1        | 0.75%   |
| 801-900        | 1        | 0.75%   |
| 301-350        | 1        | 0.75%   |
| 901-1000       | 1        | 0.75%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 92       | 72.44%  |
| 16/10   | 18       | 14.17%  |
| 5/4     | 6        | 4.72%   |
| 21/9    | 5        | 3.94%   |
| Unknown | 3        | 2.36%   |
| 32/9    | 1        | 0.79%   |
| 1.98    | 1        | 0.79%   |
| 1.00    | 1        | 0.79%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 48       | 35.29%  |
| 301-350        | 22       | 16.18%  |
| 351-500        | 18       | 13.24%  |
| 151-200        | 18       | 13.24%  |
| 251-300        | 9        | 6.62%   |
| More than 1000 | 7        | 5.15%   |
| 501-1000       | 7        | 5.15%   |
| Unknown        | 4        | 2.94%   |
| 141-150        | 3        | 2.21%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 76       | 60.32%  |
| 101-120 | 22       | 17.46%  |
| 1-50    | 12       | 9.52%   |
| 121-160 | 9        | 7.14%   |
| Unknown | 4        | 3.17%   |
| 161-240 | 3        | 2.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 75       | 62.5%   |
| 2     | 40       | 33.33%  |
| 3     | 2        | 1.67%   |
| 0     | 2        | 1.67%   |
| 4     | 1        | 0.83%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 70       | 37.04%  |
| Intel                           | 60       | 31.75%  |
| Qualcomm Atheros                | 11       | 5.82%   |
| Ralink Technology               | 8        | 4.23%   |
| Broadcom                        | 7        | 3.7%    |
| Aquantia                        | 5        | 2.65%   |
| TP-Link                         | 4        | 2.12%   |
| Ralink                          | 3        | 1.59%   |
| Xiaomi                          | 2        | 1.06%   |
| Samsung Electronics             | 2        | 1.06%   |
| Huawei Technologies             | 2        | 1.06%   |
| ASUSTek Computer                | 2        | 1.06%   |
| ZyXEL Communications            | 1        | 0.53%   |
| Wilocity                        | 1        | 0.53%   |
| VIA Technologies                | 1        | 0.53%   |
| Qualcomm Atheros Communications | 1        | 0.53%   |
| Microsoft                       | 1        | 0.53%   |
| Mercucys                        | 1        | 0.53%   |
| MediaTek                        | 1        | 0.53%   |
| Linksys                         | 1        | 0.53%   |
| Edimax Technology               | 1        | 0.53%   |
| DisplayLink                     | 1        | 0.53%   |
| D-Link System                   | 1        | 0.53%   |
| D-Link                          | 1        | 0.53%   |
| ASIX Electronics                | 1        | 0.53%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 52       | 24.19%  |
| Intel I211 Gigabit Network Connection                             | 8        | 3.72%   |
| Intel Ethernet Controller I225-V                                  | 8        | 3.72%   |
| Intel Ethernet Connection I217-LM                                 | 7        | 3.26%   |
| Intel Wi-Fi 6 AX200                                               | 6        | 2.79%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 2.33%   |
| Intel Ethernet Connection (7) I219-V                              | 5        | 2.33%   |
| Realtek 802.11ac NIC                                              | 4        | 1.86%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 1.86%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 4        | 1.86%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 4        | 1.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 1.4%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 1.4%    |
| Intel Ethernet Connection (2) I218-V                              | 3        | 1.4%    |
| Intel 82574L Gigabit Network Connection                           | 3        | 1.4%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 0.93%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.93%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.93%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 2        | 0.93%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2        | 0.93%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 0.93%   |
| Ralink RT5370 Wireless Adapter                                    | 2        | 0.93%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2        | 0.93%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 2        | 0.93%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 2        | 0.93%   |
| Intel Wireless-AC 9260                                            | 2        | 0.93%   |
| Intel Wireless 8260                                               | 2        | 0.93%   |
| Intel Wireless 7260                                               | 2        | 0.93%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 0.93%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.93%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 0.93%   |
| Huawei YAL-L21                                                    | 2        | 0.93%   |
| ZyXEL ZyAIR G-202 802.11bg                                        | 1        | 0.47%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                | 1        | 0.47%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1        | 0.47%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1        | 0.47%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                        | 1        | 0.47%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1        | 0.47%   |
| TP-Link 802.11ac NIC                                              | 1        | 0.47%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 22       | 29.73%  |
| Realtek Semiconductor           | 14       | 18.92%  |
| Ralink Technology               | 8        | 10.81%  |
| Broadcom                        | 7        | 9.46%   |
| Qualcomm Atheros                | 5        | 6.76%   |
| TP-Link                         | 4        | 5.41%   |
| Ralink                          | 3        | 4.05%   |
| ASUSTek Computer                | 2        | 2.7%    |
| ZyXEL Communications            | 1        | 1.35%   |
| Wilocity                        | 1        | 1.35%   |
| Qualcomm Atheros Communications | 1        | 1.35%   |
| Microsoft                       | 1        | 1.35%   |
| Mercucys                        | 1        | 1.35%   |
| Linksys                         | 1        | 1.35%   |
| Edimax Technology               | 1        | 1.35%   |
| D-Link System                   | 1        | 1.35%   |
| D-Link                          | 1        | 1.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 6        | 7.89%   |
| Realtek 802.11ac NIC                                           | 4        | 5.26%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 4        | 5.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2        | 2.63%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 2        | 2.63%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2        | 2.63%   |
| Ralink RT5370 Wireless Adapter                                 | 2        | 2.63%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 2        | 2.63%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 2        | 2.63%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 2        | 2.63%   |
| Intel Wireless-AC 9260                                         | 2        | 2.63%   |
| Intel Wireless 8260                                            | 2        | 2.63%   |
| Intel Wireless 7260                                            | 2        | 2.63%   |
| ZyXEL ZyAIR G-202 802.11bg                                     | 1        | 1.32%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter             | 1        | 1.32%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1        | 1.32%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                     | 1        | 1.32%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 1        | 1.32%   |
| TP-Link 802.11ac NIC                                           | 1        | 1.32%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1        | 1.32%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1        | 1.32%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 1        | 1.32%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)      | 1        | 1.32%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1        | 1.32%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1        | 1.32%   |
| Ralink RT5572 Wireless Adapter                                 | 1        | 1.32%   |
| Ralink RT3572 Wireless Adapter                                 | 1        | 1.32%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter              | 1        | 1.32%   |
| Ralink MT7601U Wireless Adapter                                | 1        | 1.32%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                           | 1        | 1.32%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1        | 1.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1        | 1.32%   |
| Qualcomm Atheros AR9271 802.11n                                | 1        | 1.32%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1        | 1.32%   |
| Microsoft Wireless XBox Controller Dongle                      | 1        | 1.32%   |
| Mercucys 802.11n NIC                                           | 1        | 1.32%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter            | 1        | 1.32%   |
| Intel Wireless 8265 / 8275                                     | 1        | 1.32%   |
| Intel Wireless 7265                                            | 1        | 1.32%   |
| Intel Wireless 3165                                            | 1        | 1.32%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 62       | 45.26%  |
| Intel                 | 52       | 37.96%  |
| Qualcomm Atheros      | 6        | 4.38%   |
| Aquantia              | 5        | 3.65%   |
| Xiaomi                | 2        | 1.46%   |
| Samsung Electronics   | 2        | 1.46%   |
| Huawei Technologies   | 2        | 1.46%   |
| Broadcom              | 2        | 1.46%   |
| VIA Technologies      | 1        | 0.73%   |
| MediaTek              | 1        | 0.73%   |
| DisplayLink           | 1        | 0.73%   |
| ASIX Electronics      | 1        | 0.73%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 52       | 37.41%  |
| Intel I211 Gigabit Network Connection                               | 8        | 5.76%   |
| Intel Ethernet Controller I225-V                                    | 8        | 5.76%   |
| Intel Ethernet Connection I217-LM                                   | 7        | 5.04%   |
| Realtek RTL8125 2.5GbE Controller                                   | 5        | 3.6%    |
| Intel Ethernet Connection (7) I219-V                                | 5        | 3.6%    |
| Intel Ethernet Connection (2) I219-V                                | 4        | 2.88%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 4        | 2.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 3        | 2.16%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 3        | 2.16%   |
| Intel Ethernet Connection (2) I218-V                                | 3        | 2.16%   |
| Intel 82574L Gigabit Network Connection                             | 3        | 2.16%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 2        | 1.44%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 2        | 1.44%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 2        | 1.44%   |
| Intel Ethernet Connection (14) I219-V                               | 2        | 1.44%   |
| Intel Ethernet Connection (11) I219-V                               | 2        | 1.44%   |
| Intel 82579V Gigabit Network Connection                             | 2        | 1.44%   |
| Huawei YAL-L21                                                      | 2        | 1.44%   |
| VIA VT6105/VT6106S [Rhine-III]                                      | 1        | 0.72%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                          | 1        | 0.72%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                    | 1        | 0.72%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller           | 1        | 0.72%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 1        | 0.72%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet      | 1        | 0.72%   |
| MediaTek Nokia 5.1 Plus                                             | 1        | 0.72%   |
| Intel I210 Gigabit Network Connection                               | 1        | 0.72%   |
| Intel Ethernet Connection I218-LM                                   | 1        | 0.72%   |
| Intel Ethernet Connection I217-V                                    | 1        | 0.72%   |
| Intel Ethernet Connection (7) I219-LM                               | 1        | 0.72%   |
| Intel 82583V Gigabit Network Connection                             | 1        | 0.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 1        | 0.72%   |
| Intel 82578DM Gigabit Network Connection                            | 1        | 0.72%   |
| Intel 82566DM-2 Gigabit Network Connection                          | 1        | 0.72%   |
| DisplayLink Dell Universal Dock D6000                               | 1        | 0.72%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                   | 1        | 0.72%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                     | 1        | 0.72%   |
| ASIX AX88179 Gigabit Ethernet                                       | 1        | 0.72%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.72%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 118      | 62.77%  |
| WiFi     | 70       | 37.23%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 86       | 71.07%  |
| WiFi     | 35       | 28.93%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 69       | 57.98%  |
| 2     | 43       | 36.13%  |
| 3     | 5        | 4.2%    |
| 6     | 1        | 0.84%   |
| 4     | 1        | 0.84%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 84       | 70%     |
| Yes  | 36       | 30%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 19       | 33.33%  |
| Cambridge Silicon Radio         | 17       | 29.82%  |
| Realtek Semiconductor           | 7        | 12.28%  |
| ASUSTek Computer                | 5        | 8.77%   |
| Broadcom                        | 3        | 5.26%   |
| Edimax Technology               | 2        | 3.51%   |
| TP-Link                         | 1        | 1.75%   |
| Qualcomm Atheros Communications | 1        | 1.75%   |
| IMC Networks                    | 1        | 1.75%   |
| Apple                           | 1        | 1.75%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 17       | 29.82%  |
| Realtek Bluetooth Radio                                 | 6        | 10.53%  |
| Intel AX200 Bluetooth                                   | 6        | 10.53%  |
| Intel Bluetooth wireless interface                      | 5        | 8.77%   |
| Broadcom BCM20702A0 Bluetooth 4.0                       | 3        | 5.26%   |
| ASUS ASUS USB-BT500                                     | 3        | 5.26%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 2        | 3.51%   |
| Intel AX201 Bluetooth                                   | 2        | 3.51%   |
| TP-Link UB500 Adapter                                   | 1        | 1.75%   |
| Realtek  Bluetooth 4.2 Adapter                          | 1        | 1.75%   |
| Qualcomm Atheros  Bluetooth Device                      | 1        | 1.75%   |
| Intel Wireless-AC 3168 Bluetooth                        | 1        | 1.75%   |
| Intel Bluetooth Device                                  | 1        | 1.75%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 1        | 1.75%   |
| Intel AX210 Bluetooth                                   | 1        | 1.75%   |
| IMC Networks Bluetooth Radio                            | 1        | 1.75%   |
| Edimax Wi-Fi AC600 Bluetooth4.0 USB Adapter             | 1        | 1.75%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter | 1        | 1.75%   |
| ASUS Bluetooth Device                                   | 1        | 1.75%   |
| ASUS Bluetooth Adapter                                  | 1        | 1.75%   |
| Apple Bluetooth USB Host Controller                     | 1        | 1.75%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| AMD                      | 70       | 28.34%  |
| Nvidia                   | 63       | 25.51%  |
| Intel                    | 61       | 24.7%   |
| GN Netcom                | 5        | 2.02%   |
| JMTek                    | 4        | 1.62%   |
| Creative Labs            | 4        | 1.62%   |
| C-Media Electronics      | 4        | 1.62%   |
| VIA Technologies         | 2        | 0.81%   |
| Texas Instruments        | 2        | 0.81%   |
| Kingston Technology      | 2        | 0.81%   |
| Generalplus Technology   | 2        | 0.81%   |
| BY EDIFIER               | 2        | 0.81%   |
| ASUSTek Computer         | 2        | 0.81%   |
| ZOOM                     | 1        | 0.4%    |
| Yamaha                   | 1        | 0.4%    |
| Unknown                  | 1        | 0.4%    |
| TerraTec Electronic      | 1        | 0.4%    |
| SteelSeries ApS          | 1        | 0.4%    |
| Samson Technologies      | 1        | 0.4%    |
| QinHeng Electronics      | 1        | 0.4%    |
| Philips (or NXP)         | 1        | 0.4%    |
| Nordic Semiconductor ASA | 1        | 0.4%    |
| Microdia                 | 1        | 0.4%    |
| Micro Star International | 1        | 0.4%    |
| M-Audio                  | 1        | 0.4%    |
| Logitech                 | 1        | 0.4%    |
| Lenovo                   | 1        | 0.4%    |
| KORG                     | 1        | 0.4%    |
| Hangzhou Worlde          | 1        | 0.4%    |
| Dell                     | 1        | 0.4%    |
| Corsair                  | 1        | 0.4%    |
| Bose                     | 1        | 0.4%    |
| Blue Microphones         | 1        | 0.4%    |
| BEHRINGER International  | 1        | 0.4%    |
| Barco Display Systems    | 1        | 0.4%    |
| Astro Gaming             | 1        | 0.4%    |
| Arturia                  | 1        | 0.4%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 21       | 7.58%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 12       | 4.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10       | 3.61%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9        | 3.25%   |
| AMD Family 17h/19h HD Audio Controller                                     | 7        | 2.53%   |
| Nvidia TU116 High Definition Audio Controller                              | 6        | 2.17%   |
| Nvidia GP106 High Definition Audio Controller                              | 6        | 2.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6        | 2.17%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6        | 2.17%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 6        | 2.17%   |
| Nvidia TU104 HD Audio Controller                                           | 5        | 1.81%   |
| Nvidia GP104 High Definition Audio Controller                              | 5        | 1.81%   |
| Intel Cannon Lake PCH cAVS                                                 | 5        | 1.81%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 5        | 1.81%   |
| Intel 200 Series PCH HD Audio                                              | 5        | 1.81%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5        | 1.81%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5        | 1.81%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5        | 1.81%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 5        | 1.81%   |
| Nvidia GA104 High Definition Audio Controller                              | 4        | 1.44%   |
| Intel Comet Lake PCH cAVS                                                  | 4        | 1.44%   |
| Nvidia TU102 High Definition Audio Controller                              | 3        | 1.08%   |
| Nvidia GP108 High Definition Audio Controller                              | 3        | 1.08%   |
| Nvidia GM206 High Definition Audio Controller                              | 3        | 1.08%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3        | 1.08%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 3        | 1.08%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 1.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3        | 1.08%   |
| AMD FCH Azalia Controller                                                  | 3        | 1.08%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 0.72%   |
| Nvidia High Definition Audio Controller                                    | 2        | 0.72%   |
| Nvidia GM204 High Definition Audio Controller                              | 2        | 0.72%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 0.72%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 0.72%   |
| Nvidia GA106 High Definition Audio Controller                              | 2        | 0.72%   |
| Kingston Technology HyperX 7.1 Audio                                       | 2        | 0.72%   |
| JMTek USB PnP Audio Device                                                 | 2        | 0.72%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2        | 0.72%   |
| Intel Audio device                                                         | 2        | 0.72%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2        | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 17       | 22.37%  |
| G.Skill             | 14       | 18.42%  |
| Kingston            | 13       | 17.11%  |
| Unknown             | 5        | 6.58%   |
| SK hynix            | 4        | 5.26%   |
| Samsung Electronics | 4        | 5.26%   |
| Micron Technology   | 4        | 5.26%   |
| Crucial             | 4        | 5.26%   |
| Team                | 2        | 2.63%   |
| Patriot             | 2        | 2.63%   |
| Unknown             | 2        | 2.63%   |
| Ramaxel Technology  | 1        | 1.32%   |
| PNY                 | 1        | 1.32%   |
| Kingmax             | 1        | 1.32%   |
| Atermiter           | 1        | 1.32%   |
| AMD                 | 1        | 1.32%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Micron RAM 8ATF1G64AZ-2G6E1 8192MB DIMM DDR4 2667MT/s  | 2        | 2.33%   |
| Corsair RAM CMK32GX4M2Z3600C18 16GB DIMM DDR4 3800MT/s | 2        | 2.33%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s  | 2        | 2.33%   |
| Unknown                                                | 2        | 2.33%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s              | 1        | 1.16%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 1        | 1.16%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 1        | 1.16%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s               | 1        | 1.16%   |
| Unknown RAM Module 16GB DIMM DDR4 2667MT/s             | 1        | 1.16%   |
| Unknown RAM 3600 C20 Series 32GB DIMM DDR4 3666MT/s    | 1        | 1.16%   |
| Team RAM TEAMGROUP-UD4-3600 32GB DIMM DDR4 3600MT/s    | 1        | 1.16%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3000MT/s     | 1        | 1.16%   |
| SK hynix RAM Module 8GB DIMM DDR4 2133MT/s             | 1        | 1.16%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s   | 1        | 1.16%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s   | 1        | 1.16%   |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s   | 1        | 1.16%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s    | 1        | 1.16%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s    | 1        | 1.16%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s    | 1        | 1.16%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s    | 1        | 1.16%   |
| Ramaxel RAM RMR5040ED58E9W1600 4GB DIMM DDR3 1600MT/s  | 1        | 1.16%   |
| PNY RAM 8GBF1X08QFHH38-135-K 8GB DIMM DDR4 3200MT/s    | 1        | 1.16%   |
| Patriot RAM PSD416G320081 16GB DIMM DDR4 3200MT/s      | 1        | 1.16%   |
| Patriot RAM PSD416G26662 16GB DIMM DDR4 2667MT/s       | 1        | 1.16%   |
| Micron RAM Module 4GB DIMM DDR3 1866MT/s               | 1        | 1.16%   |
| Micron RAM 9ASF51272PZ-2G3B1 4096MB RIMM DDR4 2400MT/s | 1        | 1.16%   |
| Micron RAM 36ASF4G72PZ-2G3B1 32GB RIMM DDR4 2400MT/s   | 1        | 1.16%   |
| Kingston RAM KHX3466C19D4/16G 16GB DIMM DDR4 3467MT/s  | 1        | 1.16%   |
| Kingston RAM KHX3200C18D4/8G 8GB DIMM DDR4 3333MT/s    | 1        | 1.16%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s      | 1        | 1.16%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3200MT/s  | 1        | 1.16%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s  | 1        | 1.16%   |
| Kingston RAM ACR32D4U2S8HD-8X 8GB DIMM DDR4 3200MT/s   | 1        | 1.16%   |
| Kingston RAM ACR16D3LU1KBG/4G 4GB DIMM DDR3 1600MT/s   | 1        | 1.16%   |
| Kingston RAM 99U5702-089.A00G 8GB DIMM DDR4 2666MT/s   | 1        | 1.16%   |
| Kingston RAM 9965639-002.A02G 8GB DIMM DDR4 2133MT/s   | 1        | 1.16%   |
| Kingston RAM 9965525-018.A00LF 4GB DIMM DDR3 1333MT/s  | 1        | 1.16%   |
| Kingston RAM 9905702-120.A00G 8GB DIMM DDR4 2667MT/s   | 1        | 1.16%   |
| Kingston RAM 9905471-079.A00LF 8GB DIMM DDR3 1600MT/s  | 1        | 1.16%   |
| Kingston RAM 9905316-174.A00LF 2GB DIMM DDR2 800MT/s   | 1        | 1.16%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 48       | 66.67%  |
| DDR3    | 17       | 23.61%  |
| SDRAM   | 2        | 2.78%   |
| DDR2    | 2        | 2.78%   |
| Unknown | 2        | 2.78%   |
| DDR5    | 1        | 1.39%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 70       | 98.59%  |
| RIMM | 1        | 1.41%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 34       | 44.16%  |
| 16384 | 20       | 25.97%  |
| 4096  | 13       | 16.88%  |
| 2048  | 5        | 6.49%   |
| 32768 | 4        | 5.19%   |
| 1024  | 1        | 1.3%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 12       | 15.38%  |
| 1600  | 10       | 12.82%  |
| 1333  | 8        | 10.26%  |
| 2667  | 7        | 8.97%   |
| 2133  | 6        | 7.69%   |
| 3600  | 5        | 6.41%   |
| 3000  | 4        | 5.13%   |
| 3066  | 3        | 3.85%   |
| 2666  | 3        | 3.85%   |
| 2400  | 3        | 3.85%   |
| 3800  | 2        | 2.56%   |
| 6000  | 1        | 1.28%   |
| 5800  | 1        | 1.28%   |
| 4000  | 1        | 1.28%   |
| 3666  | 1        | 1.28%   |
| 3467  | 1        | 1.28%   |
| 3466  | 1        | 1.28%   |
| 3333  | 1        | 1.28%   |
| 3266  | 1        | 1.28%   |
| 2933  | 1        | 1.28%   |
| 2800  | 1        | 1.28%   |
| 2448  | 1        | 1.28%   |
| 1867  | 1        | 1.28%   |
| 1866  | 1        | 1.28%   |
| 1066  | 1        | 1.28%   |
| 800   | 1        | 1.28%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 3        | 33.33%  |
| Xerox               | 1        | 11.11%  |
| Seiko Epson         | 1        | 11.11%  |
| Samsung Electronics | 1        | 11.11%  |
| Datamax-O'Neil      | 1        | 11.11%  |
| Canon               | 1        | 11.11%  |
| Brother Industries  | 1        | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Xerox Phaser 3140 and 3155    | 1        | 11.11%  |
| Seiko Epson L222 Series       | 1        | 11.11%  |
| Samsung M2070 Series          | 1        | 11.11%  |
| HP OfficeJet 5500 series      | 1        | 11.11%  |
| HP LaserJet 1022              | 1        | 11.11%  |
| HP ENVY 4500 series           | 1        | 11.11%  |
| Datamax-O'Neil Datamax E-4304 | 1        | 11.11%  |
| Canon PIXMA MX470 Series      | 1        | 11.11%  |
| Brother MFC-J460DW            | 1        | 11.11%  |

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
| Logitech                      | 12       | 40%     |
| Microdia                      | 4        | 13.33%  |
| Microsoft                     | 2        | 6.67%   |
| KYE Systems (Mouse Systems)   | 2        | 6.67%   |
| Jieli Technology              | 2        | 6.67%   |
| Generalplus Technology        | 2        | 6.67%   |
| Sunplus Innovation Technology | 1        | 3.33%   |
| Realtek Semiconductor         | 1        | 3.33%   |
| IMC Networks                  | 1        | 3.33%   |
| Hewlett-Packard               | 1        | 3.33%   |
| Asuscom Network               | 1        | 3.33%   |
| ARC International             | 1        | 3.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Logitech Webcam C270                       | 4        | 13.33%  |
| Logitech HD Pro Webcam C920                | 3        | 10%     |
| Microdia Webcam Vitade AF                  | 2        | 6.67%   |
| Microdia Integrated Camera                 | 2        | 6.67%   |
| Logitech C920 PRO HD Webcam                | 2        | 6.67%   |
| Jieli USB PHY 2.0                          | 2        | 6.67%   |
| Sunplus ezcap U3 capture-04                | 1        | 3.33%   |
| Realtek HK 2M CAM                          | 1        | 3.33%   |
| Microsoft LifeCam HD-3000                  | 1        | 3.33%   |
| Microsoft LifeCam Cinema                   | 1        | 3.33%   |
| Logitech Webcam C310                       | 1        | 3.33%   |
| Logitech C922 Pro Stream Webcam            | 1        | 3.33%   |
| Logitech BRIO Ultra HD Webcam              | 1        | 3.33%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera | 1        | 3.33%   |
| KYE Systems (Mouse Systems) eFace 2025     | 1        | 3.33%   |
| IMC Networks UVC VGA Webcam                | 1        | 3.33%   |
| HP Webcam 1300                             | 1        | 3.33%   |
| Generalplus GENERAL WEBCAM                 | 1        | 3.33%   |
| Generalplus 808 Camera #9 (web-cam mode)   | 1        | 3.33%   |
| Asuscom Network HD 1080P PC-Camera         | 1        | 3.33%   |
| ARC International Camera                   | 1        | 3.33%   |

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
| Gemalto (was Gemplus) | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 96       | 80%     |
| 1     | 21       | 17.5%   |
| 2     | 2        | 1.67%   |
| 3     | 1        | 0.83%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Net/wireless          | 9        | 36%     |
| Unassigned class      | 5        | 20%     |
| Multimedia controller | 3        | 12%     |
| Graphics card         | 3        | 12%     |
| Fingerprint reader    | 2        | 8%      |
| Sound                 | 1        | 4%      |
| Chipcard              | 1        | 4%      |
| Bluetooth             | 1        | 4%      |

