Fedora 36 - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Fedora 36.

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

Total: 401

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | H81M-E34                    | [c0be356e96](https://linux-hardware.org/?probe=c0be356e96) | Aug 01, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [dcccfd1beb](https://linux-hardware.org/?probe=dcccfd1beb) | Aug 01, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | [4956d72048](https://linux-hardware.org/?probe=4956d72048) | Aug 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [163affcbb8](https://linux-hardware.org/?probe=163affcbb8) | Aug 01, 2022 |
| ASUSTek       | M2N-MX SE Plus              | [7a0035ad18](https://linux-hardware.org/?probe=7a0035ad18) | Jul 31, 2022 |
| Gigabyte      | GA-880GM-UD2H               | [f6a106d6df](https://linux-hardware.org/?probe=f6a106d6df) | Jul 31, 2022 |
| ASUSTek       | PRIME X370-PRO              | [d8bfe4a00b](https://linux-hardware.org/?probe=d8bfe4a00b) | Jul 31, 2022 |
| ASUSTek       | PRIME X370-PRO              | [0f72d43717](https://linux-hardware.org/?probe=0f72d43717) | Jul 31, 2022 |
| ASRock        | X570 Steel Legend           | [f43e0c2c81](https://linux-hardware.org/?probe=f43e0c2c81) | Jul 31, 2022 |
| ASUSTek       | M4A77TD                     | [f10ef09086](https://linux-hardware.org/?probe=f10ef09086) | Jul 30, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [9258c864d5](https://linux-hardware.org/?probe=9258c864d5) | Jul 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [3b661517b1](https://linux-hardware.org/?probe=3b661517b1) | Jul 29, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [efa02942f2](https://linux-hardware.org/?probe=efa02942f2) | Jul 29, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [ebe9fe3b1a](https://linux-hardware.org/?probe=ebe9fe3b1a) | Jul 29, 2022 |
| ASUSTek       | PRIME B450M-K               | [25d688e258](https://linux-hardware.org/?probe=25d688e258) | Jul 29, 2022 |
| ASUSTek       | PRIME B450M-K               | [93caf82d7a](https://linux-hardware.org/?probe=93caf82d7a) | Jul 29, 2022 |
| Pegatron      | IPM41-D3                    | [ce24b0bab7](https://linux-hardware.org/?probe=ce24b0bab7) | Jul 28, 2022 |
| ASUSTek       | WS Z390 PRO                 | [256172b01e](https://linux-hardware.org/?probe=256172b01e) | Jul 28, 2022 |
| Lenovo        | 3717 SDK0R32862 WIN 3258... | [757ba0f252](https://linux-hardware.org/?probe=757ba0f252) | Jul 28, 2022 |
| ASRock        | B450M Pro4-F                | [af4d396115](https://linux-hardware.org/?probe=af4d396115) | Jul 27, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [32e82dc9ae](https://linux-hardware.org/?probe=32e82dc9ae) | Jul 27, 2022 |
| HP            | 1494                        | [6805afe809](https://linux-hardware.org/?probe=6805afe809) | Jul 27, 2022 |
| MSI           | B450M PRO-VDH MAX           | [d63a6f2607](https://linux-hardware.org/?probe=d63a6f2607) | Jul 26, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [a0e19ce405](https://linux-hardware.org/?probe=a0e19ce405) | Jul 26, 2022 |
| ASRock        | Z690 PG Riptide             | [87c499b088](https://linux-hardware.org/?probe=87c499b088) | Jul 26, 2022 |
| MSI           | B150M PRO-VD                | [8194e1dc19](https://linux-hardware.org/?probe=8194e1dc19) | Jul 26, 2022 |
| ASRock        | B450M Steel Legend          | [30fd52a2a5](https://linux-hardware.org/?probe=30fd52a2a5) | Jul 26, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [3a34e9c018](https://linux-hardware.org/?probe=3a34e9c018) | Jul 25, 2022 |
| ASUSTek       | H81M-K                      | [a3eeaecb07](https://linux-hardware.org/?probe=a3eeaecb07) | Jul 25, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [24fec424ff](https://linux-hardware.org/?probe=24fec424ff) | Jul 25, 2022 |
| Gigabyte      | X99-UD4-CF                  | [f00c831f5b](https://linux-hardware.org/?probe=f00c831f5b) | Jul 25, 2022 |
| MSI           | B365M PRO-VH                | [f254ee30b7](https://linux-hardware.org/?probe=f254ee30b7) | Jul 25, 2022 |
| Gigabyte      | X99-UD4-CF                  | [58f727d948](https://linux-hardware.org/?probe=58f727d948) | Jul 25, 2022 |
| Dell          | 0DF42J A00                  | [6a75ac249a](https://linux-hardware.org/?probe=6a75ac249a) | Jul 24, 2022 |
| ASUSTek       | Z170-P                      | [85e3fee140](https://linux-hardware.org/?probe=85e3fee140) | Jul 24, 2022 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [793c3d4e22](https://linux-hardware.org/?probe=793c3d4e22) | Jul 24, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [2ae14bcbc1](https://linux-hardware.org/?probe=2ae14bcbc1) | Jul 23, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [9c0899916c](https://linux-hardware.org/?probe=9c0899916c) | Jul 23, 2022 |
| ASUSTek       | SABERTOOTH X79              | [88c35211e1](https://linux-hardware.org/?probe=88c35211e1) | Jul 23, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [6889befce9](https://linux-hardware.org/?probe=6889befce9) | Jul 23, 2022 |
| MSI           | PRO Z690-A                  | [9264d3b652](https://linux-hardware.org/?probe=9264d3b652) | Jul 22, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [edcecb5e13](https://linux-hardware.org/?probe=edcecb5e13) | Jul 22, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [f90d74f5b5](https://linux-hardware.org/?probe=f90d74f5b5) | Jul 22, 2022 |
| Fujitsu       | D3643-H1 S26361-D3643-H1    | [cda18f8739](https://linux-hardware.org/?probe=cda18f8739) | Jul 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [6e4f170da9](https://linux-hardware.org/?probe=6e4f170da9) | Jul 22, 2022 |
| ASUSTek       | P7H55-M                     | [d7ba204d31](https://linux-hardware.org/?probe=d7ba204d31) | Jul 22, 2022 |
| Lenovo        | ThinkCentre M58p 7220A72    | [d57e35934f](https://linux-hardware.org/?probe=d57e35934f) | Jul 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [41dbccf7d9](https://linux-hardware.org/?probe=41dbccf7d9) | Jul 21, 2022 |
| Dell          | 0WMJ54 A01                  | [dace7a0b12](https://linux-hardware.org/?probe=dace7a0b12) | Jul 21, 2022 |
| Gigabyte      | X99-UD4-CF                  | [9c98b2fcd6](https://linux-hardware.org/?probe=9c98b2fcd6) | Jul 21, 2022 |
| ASRock        | H81M-HG4 R4.0               | [4628e310fd](https://linux-hardware.org/?probe=4628e310fd) | Jul 20, 2022 |
| Gigabyte      | X99-UD4-CF                  | [f42ed5053a](https://linux-hardware.org/?probe=f42ed5053a) | Jul 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [6e4fbc6688](https://linux-hardware.org/?probe=6e4fbc6688) | Jul 20, 2022 |
| ASUSTek       | PRIME X470-PRO              | [c763e49e7e](https://linux-hardware.org/?probe=c763e49e7e) | Jul 20, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [a04d18d87a](https://linux-hardware.org/?probe=a04d18d87a) | Jul 20, 2022 |
| NCR           | Pocono BIOS.6.0             | [3026f24fe3](https://linux-hardware.org/?probe=3026f24fe3) | Jul 19, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [190936df71](https://linux-hardware.org/?probe=190936df71) | Jul 19, 2022 |
| ASUSTek       | M11BB                       | [582292657c](https://linux-hardware.org/?probe=582292657c) | Jul 18, 2022 |
| MSI           | MEG B550 UNIFY              | [d6ecbbbfda](https://linux-hardware.org/?probe=d6ecbbbfda) | Jul 17, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [39fd39c3b0](https://linux-hardware.org/?probe=39fd39c3b0) | Jul 17, 2022 |
| ASRock        | AD2700-ITX                  | [870cda5796](https://linux-hardware.org/?probe=870cda5796) | Jul 17, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [aae1bec902](https://linux-hardware.org/?probe=aae1bec902) | Jul 17, 2022 |
| MSI           | X370 KRAIT GAMING           | [e74a442ccc](https://linux-hardware.org/?probe=e74a442ccc) | Jul 17, 2022 |
| Huanan        | B75                         | [0580a5a948](https://linux-hardware.org/?probe=0580a5a948) | Jul 17, 2022 |
| Huanan        | B75                         | [e1788853ec](https://linux-hardware.org/?probe=e1788853ec) | Jul 17, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [326c97ba50](https://linux-hardware.org/?probe=326c97ba50) | Jul 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [d60e6afc41](https://linux-hardware.org/?probe=d60e6afc41) | Jul 16, 2022 |
| Gigabyte      | GA-A55M-S2V                 | [713765e224](https://linux-hardware.org/?probe=713765e224) | Jul 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [41517adf39](https://linux-hardware.org/?probe=41517adf39) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX Z490-I GAMING     | [34a905d705](https://linux-hardware.org/?probe=34a905d705) | Jul 16, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [fc316a6331](https://linux-hardware.org/?probe=fc316a6331) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [86ac444b35](https://linux-hardware.org/?probe=86ac444b35) | Jul 15, 2022 |
| HP            | 88BF                        | [92b12df551](https://linux-hardware.org/?probe=92b12df551) | Jul 15, 2022 |
| MSI           | B450M PRO-VDH MAX           | [1338941bd0](https://linux-hardware.org/?probe=1338941bd0) | Jul 15, 2022 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | [7efe67fd9a](https://linux-hardware.org/?probe=7efe67fd9a) | Jul 15, 2022 |
| Gigabyte      | H77N-WIFI                   | [f655a34cc1](https://linux-hardware.org/?probe=f655a34cc1) | Jul 15, 2022 |
| ASUSTek       | M5A97 PRO                   | [e963ba85db](https://linux-hardware.org/?probe=e963ba85db) | Jul 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [165cdc7df2](https://linux-hardware.org/?probe=165cdc7df2) | Jul 14, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [ea3f033d93](https://linux-hardware.org/?probe=ea3f033d93) | Jul 14, 2022 |
| ASUSTek       | PRIME Z390-A                | [7486493ea1](https://linux-hardware.org/?probe=7486493ea1) | Jul 14, 2022 |
| Dell          | 0J3C2F A00                  | [e9be99b44d](https://linux-hardware.org/?probe=e9be99b44d) | Jul 14, 2022 |
| ASUSTek       | STRIX B250F GAMING          | [4355281f8e](https://linux-hardware.org/?probe=4355281f8e) | Jul 13, 2022 |
| ASUSTek       | STRIX B250F GAMING          | [36f96a4ef6](https://linux-hardware.org/?probe=36f96a4ef6) | Jul 13, 2022 |
| ASRock        | X570 Taichi                 | [98ffa2e8b0](https://linux-hardware.org/?probe=98ffa2e8b0) | Jul 13, 2022 |
| HP            | 1632                        | [d2582aff1d](https://linux-hardware.org/?probe=d2582aff1d) | Jul 12, 2022 |
| HP            | 8768 A                      | [f4afb80e18](https://linux-hardware.org/?probe=f4afb80e18) | Jul 12, 2022 |
| MSI           | Z370-OC PRO                 | [2c9d1d78df](https://linux-hardware.org/?probe=2c9d1d78df) | Jul 12, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [c69dd8da85](https://linux-hardware.org/?probe=c69dd8da85) | Jul 12, 2022 |
| MSI           | H97M-G43                    | [c8b2844540](https://linux-hardware.org/?probe=c8b2844540) | Jul 11, 2022 |
| HP            | 3646h                       | [88b38da161](https://linux-hardware.org/?probe=88b38da161) | Jul 11, 2022 |
| Dell          | 02YYK5 A00                  | [6592ae8873](https://linux-hardware.org/?probe=6592ae8873) | Jul 11, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [05b0102f01](https://linux-hardware.org/?probe=05b0102f01) | Jul 11, 2022 |
| Dell          | 0XCR8D A03                  | [b6771bbe08](https://linux-hardware.org/?probe=b6771bbe08) | Jul 11, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [8739a403bc](https://linux-hardware.org/?probe=8739a403bc) | Jul 11, 2022 |
| Dell          | 09WH54 A00                  | [8570e35470](https://linux-hardware.org/?probe=8570e35470) | Jul 11, 2022 |
| ASUSTek       | PRIME X470-PRO              | [314c3aaf0e](https://linux-hardware.org/?probe=314c3aaf0e) | Jul 10, 2022 |
| ASUSTek       | PRIME X470-PRO              | [d6f1e47bf5](https://linux-hardware.org/?probe=d6f1e47bf5) | Jul 10, 2022 |
| HP            | 8906 SMVB                   | [cf71ced9a0](https://linux-hardware.org/?probe=cf71ced9a0) | Jul 10, 2022 |
| HP            | 8906 SMVB                   | [cf470317b1](https://linux-hardware.org/?probe=cf470317b1) | Jul 10, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [45e46ac933](https://linux-hardware.org/?probe=45e46ac933) | Jul 10, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [cdf7b9a4d1](https://linux-hardware.org/?probe=cdf7b9a4d1) | Jul 10, 2022 |
| Intel         | DH61WW AAG23116-301         | [3b4120b3af](https://linux-hardware.org/?probe=3b4120b3af) | Jul 09, 2022 |
| MSI           | PRO B660M-A DDR4            | [65c661af95](https://linux-hardware.org/?probe=65c661af95) | Jul 09, 2022 |
| ZOTAC         | Unknown                     | [70105d0f43](https://linux-hardware.org/?probe=70105d0f43) | Jul 09, 2022 |
| ASRock        | Z170 Extreme4               | [34f14d654f](https://linux-hardware.org/?probe=34f14d654f) | Jul 09, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [6513be6d44](https://linux-hardware.org/?probe=6513be6d44) | Jul 09, 2022 |
| HP            | 8455                        | [62b146bca0](https://linux-hardware.org/?probe=62b146bca0) | Jul 08, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [44db6036ce](https://linux-hardware.org/?probe=44db6036ce) | Jul 08, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [546a26c882](https://linux-hardware.org/?probe=546a26c882) | Jul 07, 2022 |
| HP            | 8455                        | [9954a77308](https://linux-hardware.org/?probe=9954a77308) | Jul 07, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [4da61d3e61](https://linux-hardware.org/?probe=4da61d3e61) | Jul 07, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [234b2b0ee8](https://linux-hardware.org/?probe=234b2b0ee8) | Jul 07, 2022 |
| ECS           | H61H2-MV                    | [80e2fc79da](https://linux-hardware.org/?probe=80e2fc79da) | Jul 07, 2022 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | [342362a5f8](https://linux-hardware.org/?probe=342362a5f8) | Jul 06, 2022 |
| MSI           | G31TM-P21                   | [8c15268c47](https://linux-hardware.org/?probe=8c15268c47) | Jul 06, 2022 |
| Unknown       | Unknown                     | [c22b57692e](https://linux-hardware.org/?probe=c22b57692e) | Jul 06, 2022 |
| MSI           | G31TM-P21                   | [a0a2cd9568](https://linux-hardware.org/?probe=a0a2cd9568) | Jul 06, 2022 |
| Lenovo        | 3098 NOK                    | [0fb5f3cc66](https://linux-hardware.org/?probe=0fb5f3cc66) | Jul 06, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [699e033557](https://linux-hardware.org/?probe=699e033557) | Jul 06, 2022 |
| Gigabyte      | 970A-DS3P                   | [54f8e71da0](https://linux-hardware.org/?probe=54f8e71da0) | Jul 06, 2022 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [0954f0b44c](https://linux-hardware.org/?probe=0954f0b44c) | Jul 06, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [779bc20f77](https://linux-hardware.org/?probe=779bc20f77) | Jul 05, 2022 |
| MSI           | MEG X570 UNIFY              | [f1de99a0da](https://linux-hardware.org/?probe=f1de99a0da) | Jul 04, 2022 |
| MSI           | MS-B0A1                     | [9b53e39bad](https://linux-hardware.org/?probe=9b53e39bad) | Jul 04, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [729fab1a51](https://linux-hardware.org/?probe=729fab1a51) | Jul 04, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [58b8e08cf9](https://linux-hardware.org/?probe=58b8e08cf9) | Jul 04, 2022 |
| Gigabyte      | A320M-S2H-CF                | [7f4faab065](https://linux-hardware.org/?probe=7f4faab065) | Jul 04, 2022 |
| Gigabyte      | A320M-S2H-CF                | [24d32e73bd](https://linux-hardware.org/?probe=24d32e73bd) | Jul 03, 2022 |
| MSI           | MPG Z490 GAMING PLUS        | [963029db26](https://linux-hardware.org/?probe=963029db26) | Jul 02, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [2d22d14874](https://linux-hardware.org/?probe=2d22d14874) | Jul 02, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [8e6d23cf01](https://linux-hardware.org/?probe=8e6d23cf01) | Jul 01, 2022 |
| Gigabyte      | B85M-D3H                    | [a32cb9b3f1](https://linux-hardware.org/?probe=a32cb9b3f1) | Jul 01, 2022 |
| Gigabyte      | Z590I AORUS ULTRA           | [febb798e92](https://linux-hardware.org/?probe=febb798e92) | Jul 01, 2022 |
| Dell          | 0M9KCM A00                  | [e72232ee43](https://linux-hardware.org/?probe=e72232ee43) | Jul 01, 2022 |
| Gigabyte      | Z87-HD3                     | [c38c4e9cb9](https://linux-hardware.org/?probe=c38c4e9cb9) | Jun 30, 2022 |
| Dell          | 0M9KCM A00                  | [5e80242b43](https://linux-hardware.org/?probe=5e80242b43) | Jun 30, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7e14880c80](https://linux-hardware.org/?probe=7e14880c80) | Jun 30, 2022 |
| ASUSTek       | PRIME Z370-A                | [28479b3edf](https://linux-hardware.org/?probe=28479b3edf) | Jun 30, 2022 |
| Lenovo        | ThinkCentre M58p 7220A72    | [cea6c9ea52](https://linux-hardware.org/?probe=cea6c9ea52) | Jun 30, 2022 |
| Gigabyte      | B560M DS3H V2               | [85b8793585](https://linux-hardware.org/?probe=85b8793585) | Jun 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [01d9100427](https://linux-hardware.org/?probe=01d9100427) | Jun 29, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [392d5c7c12](https://linux-hardware.org/?probe=392d5c7c12) | Jun 29, 2022 |
| Gigabyte      | D525TUD                     | [b6cfc5d2df](https://linux-hardware.org/?probe=b6cfc5d2df) | Jun 28, 2022 |
| Gigabyte      | B85M-D3V-A                  | [3417dd6a9a](https://linux-hardware.org/?probe=3417dd6a9a) | Jun 28, 2022 |
| Gigabyte      | G41MT-D3                    | [20de16a046](https://linux-hardware.org/?probe=20de16a046) | Jun 28, 2022 |
| ASRock        | N68-VS3 UCC                 | [2c7959c607](https://linux-hardware.org/?probe=2c7959c607) | Jun 26, 2022 |
| ASUSTek       | PRIME H410M-E               | [3eb97735b3](https://linux-hardware.org/?probe=3eb97735b3) | Jun 26, 2022 |
| HP            | 3398                        | [4241fd0ba0](https://linux-hardware.org/?probe=4241fd0ba0) | Jun 26, 2022 |
| Gigabyte      | 990FXA-UD5 R5               | [9a853085ea](https://linux-hardware.org/?probe=9a853085ea) | Jun 26, 2022 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [519e378380](https://linux-hardware.org/?probe=519e378380) | Jun 25, 2022 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [6c6d94e4b7](https://linux-hardware.org/?probe=6c6d94e4b7) | Jun 25, 2022 |
| BESSTAR Te... | HM90                        | [e8a4e37cc6](https://linux-hardware.org/?probe=e8a4e37cc6) | Jun 25, 2022 |
| ASRock        | H87 Pro4                    | [47cf388077](https://linux-hardware.org/?probe=47cf388077) | Jun 25, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [c3c48bb18e](https://linux-hardware.org/?probe=c3c48bb18e) | Jun 25, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [c6c59e12b6](https://linux-hardware.org/?probe=c6c59e12b6) | Jun 25, 2022 |
| MSI           | B360M MORTAR                | [607f489961](https://linux-hardware.org/?probe=607f489961) | Jun 25, 2022 |
| ASRock        | H87 Pro4                    | [73eb3e0db6](https://linux-hardware.org/?probe=73eb3e0db6) | Jun 25, 2022 |
| HP            | 89D8 SMVB                   | [f92ff0c37f](https://linux-hardware.org/?probe=f92ff0c37f) | Jun 24, 2022 |
| MSI           | IONA                        | [9f4e8871a7](https://linux-hardware.org/?probe=9f4e8871a7) | Jun 24, 2022 |
| ASRock        | H77 Pro4/MVP                | [f022b1b430](https://linux-hardware.org/?probe=f022b1b430) | Jun 24, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [5129e4893a](https://linux-hardware.org/?probe=5129e4893a) | Jun 23, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [dbfad9b8fe](https://linux-hardware.org/?probe=dbfad9b8fe) | Jun 23, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [6f13e0f8a0](https://linux-hardware.org/?probe=6f13e0f8a0) | Jun 23, 2022 |
| Gigabyte      | Z690I AORUS ULTRA           | [eeac425783](https://linux-hardware.org/?probe=eeac425783) | Jun 23, 2022 |
| Unknown       | HX90                        | [837e70229a](https://linux-hardware.org/?probe=837e70229a) | Jun 23, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [167acd417b](https://linux-hardware.org/?probe=167acd417b) | Jun 23, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [d11995947a](https://linux-hardware.org/?probe=d11995947a) | Jun 23, 2022 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | [92944b1e97](https://linux-hardware.org/?probe=92944b1e97) | Jun 22, 2022 |
| HP            | 2B05                        | [677bb9d569](https://linux-hardware.org/?probe=677bb9d569) | Jun 22, 2022 |
| ASRock        | B550M Pro4                  | [45871f6d61](https://linux-hardware.org/?probe=45871f6d61) | Jun 22, 2022 |
| ASRock        | B450 Gaming K4              | [05c977bf65](https://linux-hardware.org/?probe=05c977bf65) | Jun 22, 2022 |
| Dell          | 02YYK5 A00                  | [7a571de1b9](https://linux-hardware.org/?probe=7a571de1b9) | Jun 22, 2022 |
| System76      | Thelio Mira thelio-mira-... | [58c9da7f20](https://linux-hardware.org/?probe=58c9da7f20) | Jun 22, 2022 |
| MSI           | B85M-E45                    | [f5e1312d31](https://linux-hardware.org/?probe=f5e1312d31) | Jun 22, 2022 |
| Gigabyte      | H61M-S2P                    | [ac99674975](https://linux-hardware.org/?probe=ac99674975) | Jun 22, 2022 |
| Dell          | 04YP6J A02                  | [11151bb62c](https://linux-hardware.org/?probe=11151bb62c) | Jun 22, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [04927da7b6](https://linux-hardware.org/?probe=04927da7b6) | Jun 22, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [f3176204c8](https://linux-hardware.org/?probe=f3176204c8) | Jun 21, 2022 |
| MSI           | B450-A PRO MAX              | [490076a383](https://linux-hardware.org/?probe=490076a383) | Jun 20, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [b7a6099e25](https://linux-hardware.org/?probe=b7a6099e25) | Jun 20, 2022 |
| MSI           | MS-B0A1                     | [3193cbe3fd](https://linux-hardware.org/?probe=3193cbe3fd) | Jun 20, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [a384703b5e](https://linux-hardware.org/?probe=a384703b5e) | Jun 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [560fa88cad](https://linux-hardware.org/?probe=560fa88cad) | Jun 19, 2022 |
| HP            | 2B05                        | [a49ebb4aed](https://linux-hardware.org/?probe=a49ebb4aed) | Jun 19, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [4fc1134f6d](https://linux-hardware.org/?probe=4fc1134f6d) | Jun 19, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [a59676f7be](https://linux-hardware.org/?probe=a59676f7be) | Jun 19, 2022 |
| ASUSTek       | M5A97 R2.0                  | [707f314c74](https://linux-hardware.org/?probe=707f314c74) | Jun 19, 2022 |
| MSI           | H510I PRO WIFI              | [b9d3cb4755](https://linux-hardware.org/?probe=b9d3cb4755) | Jun 18, 2022 |
| ASUSTek       | Q170M2                      | [76f5dd0027](https://linux-hardware.org/?probe=76f5dd0027) | Jun 18, 2022 |
| ASUSTek       | Q170M2                      | [32713d6759](https://linux-hardware.org/?probe=32713d6759) | Jun 18, 2022 |
| ASRock        | X370 Gaming-ITX/ac          | [292cc4bcab](https://linux-hardware.org/?probe=292cc4bcab) | Jun 17, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [f54dda344d](https://linux-hardware.org/?probe=f54dda344d) | Jun 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [6647ddd346](https://linux-hardware.org/?probe=6647ddd346) | Jun 17, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [dfed0867e1](https://linux-hardware.org/?probe=dfed0867e1) | Jun 17, 2022 |
| ASUSTek       | P8H67-M LE                  | [7205fff536](https://linux-hardware.org/?probe=7205fff536) | Jun 17, 2022 |
| MSI           | MAG B460M MORTAR            | [9074247e52](https://linux-hardware.org/?probe=9074247e52) | Jun 17, 2022 |
| Dell          | 0XC7MM A01                  | [8c8a1ef522](https://linux-hardware.org/?probe=8c8a1ef522) | Jun 16, 2022 |
| Gigabyte      | H87N-WIFI                   | [613bb8fe40](https://linux-hardware.org/?probe=613bb8fe40) | Jun 16, 2022 |
| ASUSTek       | PRIME B550M-A               | [527aea0d6e](https://linux-hardware.org/?probe=527aea0d6e) | Jun 16, 2022 |
| ASRock        | B550M-ITX/ac                | [42fd0dcad9](https://linux-hardware.org/?probe=42fd0dcad9) | Jun 16, 2022 |
| Gigabyte      | 990FXA-UD5 R5               | [08527d664b](https://linux-hardware.org/?probe=08527d664b) | Jun 16, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [8d106f8677](https://linux-hardware.org/?probe=8d106f8677) | Jun 16, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [701de0d7ad](https://linux-hardware.org/?probe=701de0d7ad) | Jun 15, 2022 |
| ASRock        | B450M Pro4                  | [041f94473b](https://linux-hardware.org/?probe=041f94473b) | Jun 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [131a938c5e](https://linux-hardware.org/?probe=131a938c5e) | Jun 14, 2022 |
| Foxconn       | nT-i1000 Series PCB         | [e61344b416](https://linux-hardware.org/?probe=e61344b416) | Jun 14, 2022 |
| Gigabyte      | H61M-S2PV                   | [cc88cec642](https://linux-hardware.org/?probe=cc88cec642) | Jun 14, 2022 |
| ASUSTek       | PRIME Z370-A                | [1bb2aa2c68](https://linux-hardware.org/?probe=1bb2aa2c68) | Jun 14, 2022 |
| Dell          | 00V62H A00                  | [dc89caf09f](https://linux-hardware.org/?probe=dc89caf09f) | Jun 13, 2022 |
| Gigabyte      | B560M DS3H V2               | [61d456c166](https://linux-hardware.org/?probe=61d456c166) | Jun 13, 2022 |
| ASUSTek       | H87-PLUS                    | [1c5488bdf7](https://linux-hardware.org/?probe=1c5488bdf7) | Jun 13, 2022 |
| ASUSTek       | H87-PLUS                    | [fd8af28ed5](https://linux-hardware.org/?probe=fd8af28ed5) | Jun 13, 2022 |
| HP            | 18E5                        | [275b8ca77c](https://linux-hardware.org/?probe=275b8ca77c) | Jun 12, 2022 |
| ASUSTek       | P5K Premium                 | [c7243df0c6](https://linux-hardware.org/?probe=c7243df0c6) | Jun 12, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | [0c0715a9b2](https://linux-hardware.org/?probe=0c0715a9b2) | Jun 12, 2022 |
| Gigabyte      | B75-D3V                     | [f0fe22dfe7](https://linux-hardware.org/?probe=f0fe22dfe7) | Jun 12, 2022 |
| ASUSTek       | P5G41T-M                    | [0fd96bfcf3](https://linux-hardware.org/?probe=0fd96bfcf3) | Jun 12, 2022 |
| MSI           | B450M MORTAR                | [18240b9552](https://linux-hardware.org/?probe=18240b9552) | Jun 11, 2022 |
| Gigabyte      | GA-MA69GM-S2H               | [a382b54934](https://linux-hardware.org/?probe=a382b54934) | Jun 11, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [661f4f701b](https://linux-hardware.org/?probe=661f4f701b) | Jun 10, 2022 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | [9c7b2faf2c](https://linux-hardware.org/?probe=9c7b2faf2c) | Jun 10, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [b771c75e31](https://linux-hardware.org/?probe=b771c75e31) | Jun 10, 2022 |
| ASUSTek       | PRIME B360M-A               | [272c6283d4](https://linux-hardware.org/?probe=272c6283d4) | Jun 10, 2022 |
| Gigabyte      | H55M-S2                     | [86b61f1ef6](https://linux-hardware.org/?probe=86b61f1ef6) | Jun 10, 2022 |
| ASUSTek       | PRIME B660-PLUS D4          | [4458c8a8ca](https://linux-hardware.org/?probe=4458c8a8ca) | Jun 09, 2022 |
| Intel         | X79 V2.4E                   | [12a530acde](https://linux-hardware.org/?probe=12a530acde) | Jun 09, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [35b29ccf1d](https://linux-hardware.org/?probe=35b29ccf1d) | Jun 08, 2022 |
| Gigabyte      | A520M DS3H                  | [e12c11bc94](https://linux-hardware.org/?probe=e12c11bc94) | Jun 08, 2022 |
| Gigabyte      | H410M S2H V3                | [feaff6859d](https://linux-hardware.org/?probe=feaff6859d) | Jun 07, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [c446ea33eb](https://linux-hardware.org/?probe=c446ea33eb) | Jun 07, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | [f23f59523b](https://linux-hardware.org/?probe=f23f59523b) | Jun 07, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | [2e5071518f](https://linux-hardware.org/?probe=2e5071518f) | Jun 07, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [9fe17edc24](https://linux-hardware.org/?probe=9fe17edc24) | Jun 06, 2022 |
| ASUSTek       | P8H67-M LE                  | [d1409ca910](https://linux-hardware.org/?probe=d1409ca910) | Jun 06, 2022 |
| Dell          | 0XC7MM A01                  | [ed376c819b](https://linux-hardware.org/?probe=ed376c819b) | Jun 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [0b042e37b3](https://linux-hardware.org/?probe=0b042e37b3) | Jun 06, 2022 |
| Dell          | 08K0X7 A00                  | [28a29e32c6](https://linux-hardware.org/?probe=28a29e32c6) | Jun 06, 2022 |
| Dell          | 06JWJY A00                  | [577bbe62e1](https://linux-hardware.org/?probe=577bbe62e1) | Jun 06, 2022 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | [8b87017c24](https://linux-hardware.org/?probe=8b87017c24) | Jun 05, 2022 |
| Gigabyte      | B460M DS3H V2               | [afb7427d61](https://linux-hardware.org/?probe=afb7427d61) | Jun 05, 2022 |
| Foxconn       | H81MXV FAB A                | [1f880ea008](https://linux-hardware.org/?probe=1f880ea008) | Jun 05, 2022 |
| Gigabyte      | B75M-HD3                    | [63a565a5e1](https://linux-hardware.org/?probe=63a565a5e1) | Jun 05, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [feec15b490](https://linux-hardware.org/?probe=feec15b490) | Jun 04, 2022 |
| Positivo      | POS-PIH55BO                 | [cffe8043b8](https://linux-hardware.org/?probe=cffe8043b8) | Jun 04, 2022 |
| ASUSTek       | PRIME B450M-A               | [1813b3a9a5](https://linux-hardware.org/?probe=1813b3a9a5) | Jun 04, 2022 |
| ASUSTek       | CROSSHAIR                   | [11834759e2](https://linux-hardware.org/?probe=11834759e2) | Jun 04, 2022 |
| MSI           | B450M PRO-VDH MAX           | [2e9cc784ac](https://linux-hardware.org/?probe=2e9cc784ac) | Jun 03, 2022 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | [68a1616b4a](https://linux-hardware.org/?probe=68a1616b4a) | Jun 03, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [909d9cb8d5](https://linux-hardware.org/?probe=909d9cb8d5) | Jun 03, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [9829bd8f60](https://linux-hardware.org/?probe=9829bd8f60) | Jun 03, 2022 |
| MSI           | B560M PRO-VDH               | [2e9996424a](https://linux-hardware.org/?probe=2e9996424a) | Jun 02, 2022 |
| ASRock        | H81M-HG4 R4.0               | [2a09c108e5](https://linux-hardware.org/?probe=2a09c108e5) | Jun 02, 2022 |
| Gigabyte      | B85M-D3V-A                  | [88d5e21b42](https://linux-hardware.org/?probe=88d5e21b42) | Jun 01, 2022 |
| ASUSTek       | Maximus VII IMPACT          | [8b0844f325](https://linux-hardware.org/?probe=8b0844f325) | Jun 01, 2022 |
| ASUSTek       | ROG STRIX Z490-H GAMING     | [0d91ffc3e9](https://linux-hardware.org/?probe=0d91ffc3e9) | Jun 01, 2022 |
| ASUSTek       | ROG STRIX Z490-H GAMING     | [6190087942](https://linux-hardware.org/?probe=6190087942) | Jun 01, 2022 |
| ASUSTek       | PRIME B560M-A               | [b68bcf6b84](https://linux-hardware.org/?probe=b68bcf6b84) | Jun 01, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [53dbc2fe14](https://linux-hardware.org/?probe=53dbc2fe14) | May 31, 2022 |
| MSI           | B450M PRO-VDH MAX           | [ece9950c65](https://linux-hardware.org/?probe=ece9950c65) | May 31, 2022 |
| MSI           | B450M PRO-VDH MAX           | [07a1bcfa9e](https://linux-hardware.org/?probe=07a1bcfa9e) | May 30, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [7b27373492](https://linux-hardware.org/?probe=7b27373492) | May 30, 2022 |
| ASUSTek       | P5Q SE                      | [386a88c2b6](https://linux-hardware.org/?probe=386a88c2b6) | May 30, 2022 |
| ASUSTek       | P5Q SE                      | [5a51cc8767](https://linux-hardware.org/?probe=5a51cc8767) | May 30, 2022 |
| Dell          | 0R6PCT A01                  | [23c83c37e6](https://linux-hardware.org/?probe=23c83c37e6) | May 29, 2022 |
| ASUSTek       | ROG Maximus X HERO          | [33a2de91a2](https://linux-hardware.org/?probe=33a2de91a2) | May 29, 2022 |
| ASUSTek       | H81M-A                      | [0aa77d107c](https://linux-hardware.org/?probe=0aa77d107c) | May 28, 2022 |
| ASUSTek       | TUF X299 MARK 2             | [8409764263](https://linux-hardware.org/?probe=8409764263) | May 27, 2022 |
| BESSTAR Te... | UM700                       | [f754f78f66](https://linux-hardware.org/?probe=f754f78f66) | May 25, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [c01e0f9ac4](https://linux-hardware.org/?probe=c01e0f9ac4) | May 25, 2022 |
| Gigabyte      | B450M DS3H-CF               | [06e3526c59](https://linux-hardware.org/?probe=06e3526c59) | May 25, 2022 |
| ASRock        | X99 Taichi                  | [18ec1a6a1a](https://linux-hardware.org/?probe=18ec1a6a1a) | May 25, 2022 |
| ASUSTek       | KCMA-D8                     | [2d8bea4f55](https://linux-hardware.org/?probe=2d8bea4f55) | May 24, 2022 |
| Dell          | 0PU052                      | [4e3e3cc0fd](https://linux-hardware.org/?probe=4e3e3cc0fd) | May 24, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [282c849b82](https://linux-hardware.org/?probe=282c849b82) | May 24, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [da5f6c9ba0](https://linux-hardware.org/?probe=da5f6c9ba0) | May 23, 2022 |
| MSI           | Z77A-G43                    | [7d35f08c28](https://linux-hardware.org/?probe=7d35f08c28) | May 23, 2022 |
| ASUSTek       | PRIME Z270-P                | [afb47f4860](https://linux-hardware.org/?probe=afb47f4860) | May 23, 2022 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | [2034bf506d](https://linux-hardware.org/?probe=2034bf506d) | May 23, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2bd8d64c3b](https://linux-hardware.org/?probe=2bd8d64c3b) | May 22, 2022 |
| ASUSTek       | P8P67-M                     | [83917315b7](https://linux-hardware.org/?probe=83917315b7) | May 22, 2022 |
| Gigabyte      | B550 GAMING X V2            | [a84132c514](https://linux-hardware.org/?probe=a84132c514) | May 22, 2022 |
| ASRock        | AB350 Pro4                  | [49223fe44b](https://linux-hardware.org/?probe=49223fe44b) | May 21, 2022 |
| ASRock        | AB350 Pro4                  | [40cb336486](https://linux-hardware.org/?probe=40cb336486) | May 21, 2022 |
| MSI           | B450M-A PRO MAX             | [fce678a9e8](https://linux-hardware.org/?probe=fce678a9e8) | May 21, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [01e2d063e8](https://linux-hardware.org/?probe=01e2d063e8) | May 21, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [f3986d7e7d](https://linux-hardware.org/?probe=f3986d7e7d) | May 21, 2022 |
| MSI           | B450M PRO-M2 MAX            | [1984313b19](https://linux-hardware.org/?probe=1984313b19) | May 20, 2022 |
| ASRock        | Z390 Taichi Ultimate        | [68d0cdd597](https://linux-hardware.org/?probe=68d0cdd597) | May 19, 2022 |
| HP            | 82A2                        | [56d6c8d749](https://linux-hardware.org/?probe=56d6c8d749) | May 19, 2022 |
| HP            | 82A2                        | [6e0efeba1d](https://linux-hardware.org/?probe=6e0efeba1d) | May 19, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [4a971be254](https://linux-hardware.org/?probe=4a971be254) | May 19, 2022 |
| Intel         | DH77EB AAG39073-304         | [dc2f9f56a5](https://linux-hardware.org/?probe=dc2f9f56a5) | May 18, 2022 |
| HP            | 8767 A                      | [0f564fe004](https://linux-hardware.org/?probe=0f564fe004) | May 18, 2022 |
| MSI           | B450M PRO-VDH MAX           | [9c3b90c60d](https://linux-hardware.org/?probe=9c3b90c60d) | May 18, 2022 |
| ASRock        | 970M Pro3                   | [d39e962536](https://linux-hardware.org/?probe=d39e962536) | May 18, 2022 |
| ASUSTek       | P8Z68-V PRO GEN3            | [8a6fc346c5](https://linux-hardware.org/?probe=8a6fc346c5) | May 18, 2022 |
| Dell          | 0DF42J A00                  | [ac9f539524](https://linux-hardware.org/?probe=ac9f539524) | May 18, 2022 |
| HP            | 8767 A                      | [caad4001f1](https://linux-hardware.org/?probe=caad4001f1) | May 18, 2022 |
| ASRock        | 970M Pro3                   | [6f48a71a87](https://linux-hardware.org/?probe=6f48a71a87) | May 17, 2022 |
| ASUSTek       | P8H67-M LE                  | [ef70fd2699](https://linux-hardware.org/?probe=ef70fd2699) | May 17, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [d831b6cb22](https://linux-hardware.org/?probe=d831b6cb22) | May 17, 2022 |
| Dell          | 0NKW6Y A02                  | [ffee0745b6](https://linux-hardware.org/?probe=ffee0745b6) | May 16, 2022 |
| Gigabyte      | X99-UD4-CF                  | [21b3b45491](https://linux-hardware.org/?probe=21b3b45491) | May 16, 2022 |
| Gigabyte      | X99-UD4-CF                  | [81e0a19eaa](https://linux-hardware.org/?probe=81e0a19eaa) | May 16, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [d1dbcd7651](https://linux-hardware.org/?probe=d1dbcd7651) | May 16, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [efe02f8593](https://linux-hardware.org/?probe=efe02f8593) | May 16, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [2f12c77058](https://linux-hardware.org/?probe=2f12c77058) | May 16, 2022 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [fa17134027](https://linux-hardware.org/?probe=fa17134027) | May 16, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [26f332bc9c](https://linux-hardware.org/?probe=26f332bc9c) | May 16, 2022 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [16bd9d3c6d](https://linux-hardware.org/?probe=16bd9d3c6d) | May 16, 2022 |
| Intel         | DH77EB AAG39073-304         | [22f5a0269f](https://linux-hardware.org/?probe=22f5a0269f) | May 15, 2022 |
| Intel         | DH77EB AAG39073-304         | [8b8bd9dead](https://linux-hardware.org/?probe=8b8bd9dead) | May 15, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [12d277d32c](https://linux-hardware.org/?probe=12d277d32c) | May 15, 2022 |
| ASRock        | 880GMH/U3S3                 | [57c85dd37a](https://linux-hardware.org/?probe=57c85dd37a) | May 15, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [ec0ec5ea27](https://linux-hardware.org/?probe=ec0ec5ea27) | May 15, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [a2ae5d95dd](https://linux-hardware.org/?probe=a2ae5d95dd) | May 15, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [6fc56522d6](https://linux-hardware.org/?probe=6fc56522d6) | May 14, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [1bde2ca3e7](https://linux-hardware.org/?probe=1bde2ca3e7) | May 14, 2022 |
| ASUSTek       | P8Z77-V LK                  | [70809098f6](https://linux-hardware.org/?probe=70809098f6) | May 14, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [3112931a28](https://linux-hardware.org/?probe=3112931a28) | May 14, 2022 |
| ASRock        | B560M-C                     | [b4946d836b](https://linux-hardware.org/?probe=b4946d836b) | May 13, 2022 |
| ASRock        | B560M-C                     | [16360de6cd](https://linux-hardware.org/?probe=16360de6cd) | May 13, 2022 |
| Gigabyte      | GA-K8NF-9                   | [f9d59e3770](https://linux-hardware.org/?probe=f9d59e3770) | May 13, 2022 |
| ASRock        | X570M Pro4                  | [fca86a854a](https://linux-hardware.org/?probe=fca86a854a) | May 13, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [ec4bd74f0b](https://linux-hardware.org/?probe=ec4bd74f0b) | May 13, 2022 |
| Gigabyte      | B85M-D3V-A                  | [46481247b1](https://linux-hardware.org/?probe=46481247b1) | May 12, 2022 |
| Acer          | Aspire M3985                | [e650ae1a26](https://linux-hardware.org/?probe=e650ae1a26) | May 11, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [927afa0c20](https://linux-hardware.org/?probe=927afa0c20) | May 11, 2022 |
| Gigabyte      | A320M-S2H-CF                | [c703872774](https://linux-hardware.org/?probe=c703872774) | May 11, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [b9766a94d7](https://linux-hardware.org/?probe=b9766a94d7) | May 11, 2022 |
| ASRock        | X470 Taichi                 | [9ead3d53b0](https://linux-hardware.org/?probe=9ead3d53b0) | May 11, 2022 |
| MSI           | X470 GAMING PLUS            | [565dfeea66](https://linux-hardware.org/?probe=565dfeea66) | May 11, 2022 |
| Gigabyte      | Q35M-S2                     | [784ac96428](https://linux-hardware.org/?probe=784ac96428) | May 11, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [173fac4f5b](https://linux-hardware.org/?probe=173fac4f5b) | May 11, 2022 |
| ASRock        | 880GMH/U3S3                 | [73e6cb3b6b](https://linux-hardware.org/?probe=73e6cb3b6b) | May 10, 2022 |
| ASRock        | X470 Taichi                 | [fb1d5703eb](https://linux-hardware.org/?probe=fb1d5703eb) | May 10, 2022 |
| MSI           | H110M PRO-VD                | [f43f2e2bee](https://linux-hardware.org/?probe=f43f2e2bee) | May 10, 2022 |
| MSI           | H110M PRO-VD                | [3d0c46dc84](https://linux-hardware.org/?probe=3d0c46dc84) | May 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [d7e92b0ac7](https://linux-hardware.org/?probe=d7e92b0ac7) | May 09, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [fbe61c70ff](https://linux-hardware.org/?probe=fbe61c70ff) | May 09, 2022 |
| Gigabyte      | EP45-DS3L                   | [76e67361ea](https://linux-hardware.org/?probe=76e67361ea) | May 08, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [d24bbea844](https://linux-hardware.org/?probe=d24bbea844) | May 08, 2022 |
| ASUSTek       | PRIME X570-PRO              | [f12944a9bd](https://linux-hardware.org/?probe=f12944a9bd) | May 07, 2022 |
| ASUSTek       | PRIME X470-PRO              | [be200c9e57](https://linux-hardware.org/?probe=be200c9e57) | May 06, 2022 |
| Huanan        | X99-BD4 V1.1, NALEX         | [e69b3ef962](https://linux-hardware.org/?probe=e69b3ef962) | May 06, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [52d956751f](https://linux-hardware.org/?probe=52d956751f) | May 06, 2022 |
| MSI           | B550M PRO-DASH              | [585987ecf7](https://linux-hardware.org/?probe=585987ecf7) | May 06, 2022 |
| Gigabyte      | H410M H V3                  | [ddc4d88d20](https://linux-hardware.org/?probe=ddc4d88d20) | May 05, 2022 |
| ASUSTek       | P8H67-M LE                  | [302e27b974](https://linux-hardware.org/?probe=302e27b974) | May 04, 2022 |
| ASUSTek       | P8H67-M LE                  | [a9cf3bc268](https://linux-hardware.org/?probe=a9cf3bc268) | May 04, 2022 |
| HP            | 1589                        | [79df2c00dc](https://linux-hardware.org/?probe=79df2c00dc) | May 03, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [cb6d49fe71](https://linux-hardware.org/?probe=cb6d49fe71) | Apr 30, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [83e47f9c91](https://linux-hardware.org/?probe=83e47f9c91) | Apr 30, 2022 |
| ASUSTek       | PRIME Z390-A                | [c4d7dc5e80](https://linux-hardware.org/?probe=c4d7dc5e80) | Apr 30, 2022 |
| MSI           | MAG B460M MORTAR            | [07cb268e5e](https://linux-hardware.org/?probe=07cb268e5e) | Apr 30, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | [2999ff1487](https://linux-hardware.org/?probe=2999ff1487) | Apr 28, 2022 |
| ASRock        | B450 Steel Legend           | [bf0a56358c](https://linux-hardware.org/?probe=bf0a56358c) | Apr 27, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [5456280ec0](https://linux-hardware.org/?probe=5456280ec0) | Apr 26, 2022 |
| Gigabyte      | X570 AORUS PRO              | [187db4f8e4](https://linux-hardware.org/?probe=187db4f8e4) | Apr 23, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [b9ea98672f](https://linux-hardware.org/?probe=b9ea98672f) | Apr 23, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [c3f809fc02](https://linux-hardware.org/?probe=c3f809fc02) | Apr 23, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [68a04098ec](https://linux-hardware.org/?probe=68a04098ec) | Apr 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [466f67adb3](https://linux-hardware.org/?probe=466f67adb3) | Apr 20, 2022 |
| Gigabyte      | H81M-S2H                    | [85082e6de6](https://linux-hardware.org/?probe=85082e6de6) | Apr 19, 2022 |
| Gigabyte      | H110M-H-CF                  | [66ef9c9e5f](https://linux-hardware.org/?probe=66ef9c9e5f) | Apr 16, 2022 |
| Acer          | Aspire TC-895 V:1.0         | [22a1a17a81](https://linux-hardware.org/?probe=22a1a17a81) | Apr 14, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [85b4ecf9d3](https://linux-hardware.org/?probe=85b4ecf9d3) | Apr 14, 2022 |
| ASUSTek       | P8P67 LE                    | [84abfd3112](https://linux-hardware.org/?probe=84abfd3112) | Apr 14, 2022 |
| MSI           | FM2-A75IA-E53               | [25ffe3d211](https://linux-hardware.org/?probe=25ffe3d211) | Apr 14, 2022 |
| Gigabyte      | Z170MX-Gaming 5             | [d1b267f496](https://linux-hardware.org/?probe=d1b267f496) | Apr 13, 2022 |
| Gigabyte      | B450 AORUS M                | [c1beed0e9b](https://linux-hardware.org/?probe=c1beed0e9b) | Apr 13, 2022 |
| Gigabyte      | B450 AORUS M                | [e5a9e99dbc](https://linux-hardware.org/?probe=e5a9e99dbc) | Apr 13, 2022 |
| Dell          | 0GWHMW A03                  | [ff312c5929](https://linux-hardware.org/?probe=ff312c5929) | Apr 13, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [8a1cecc21c](https://linux-hardware.org/?probe=8a1cecc21c) | Apr 11, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [5b861faffd](https://linux-hardware.org/?probe=5b861faffd) | Apr 09, 2022 |
| Gigabyte      | Z490 UD                     | [31ecc9c776](https://linux-hardware.org/?probe=31ecc9c776) | Apr 09, 2022 |
| Biostar       | B550MH                      | [abd373497b](https://linux-hardware.org/?probe=abd373497b) | Apr 09, 2022 |
| Gigabyte      | B450 AORUS M                | [1a4b90c894](https://linux-hardware.org/?probe=1a4b90c894) | Apr 08, 2022 |
| MSI           | Z170A XPOWER GAMING TITA... | [ffcbeed952](https://linux-hardware.org/?probe=ffcbeed952) | Apr 08, 2022 |
| Gigabyte      | Z170N-Gaming 5              | [f0472bcf0d](https://linux-hardware.org/?probe=f0472bcf0d) | Apr 05, 2022 |
| Gigabyte      | Z170N-Gaming 5              | [9ee2f76c12](https://linux-hardware.org/?probe=9ee2f76c12) | Apr 05, 2022 |
| ASUSTek       | B150M-K                     | [016a08bf47](https://linux-hardware.org/?probe=016a08bf47) | Apr 04, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [b697fd5f0a](https://linux-hardware.org/?probe=b697fd5f0a) | Apr 03, 2022 |
| Gigabyte      | 970A-DS3P                   | [5bbc4cbbf5](https://linux-hardware.org/?probe=5bbc4cbbf5) | Apr 03, 2022 |
| Dell          | 088DT1 A01                  | [718a7d42cc](https://linux-hardware.org/?probe=718a7d42cc) | Apr 02, 2022 |
| Gigabyte      | H81M-S2H                    | [8a810aa9f6](https://linux-hardware.org/?probe=8a810aa9f6) | Apr 02, 2022 |
| MSI           | MPG Z590 GAMING CARBON W... | [f7946783ea](https://linux-hardware.org/?probe=f7946783ea) | Mar 31, 2022 |
| Gigabyte      | H370M DS3H-CF               | [1110b2974c](https://linux-hardware.org/?probe=1110b2974c) | Mar 31, 2022 |
| Gigabyte      | EP45-DS3L                   | [c7d6879a86](https://linux-hardware.org/?probe=c7d6879a86) | Mar 26, 2022 |
| Gigabyte      | B85M-D3V-A                  | [b7679b78be](https://linux-hardware.org/?probe=b7679b78be) | Mar 25, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [7977e70f86](https://linux-hardware.org/?probe=7977e70f86) | Mar 22, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [97eedd34f4](https://linux-hardware.org/?probe=97eedd34f4) | Mar 05, 2022 |
| Gigabyte      | EP45-DS3L                   | [da3962a1da](https://linux-hardware.org/?probe=da3962a1da) | Mar 03, 2022 |
| Biostar       | H55 HD                      | [b0d5843b6e](https://linux-hardware.org/?probe=b0d5843b6e) | Feb 13, 2022 |
| Biostar       | H55 HD                      | [e08da3e685](https://linux-hardware.org/?probe=e08da3e685) | Feb 03, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [f1a1a21c56](https://linux-hardware.org/?probe=f1a1a21c56) | Oct 26, 2021 |
| Dell          | 0KC9NP A01                  | [ff356cba89](https://linux-hardware.org/?probe=ff356cba89) | Oct 22, 2021 |
| MSI           | FM2-A55M-E33                | [bcf7dcdd2c](https://linux-hardware.org/?probe=bcf7dcdd2c) | Oct 09, 2021 |
| MSI           | FM2-A55M-E33                | [0b3691d096](https://linux-hardware.org/?probe=0b3691d096) | Oct 09, 2021 |
| HP            | 304Ah                       | [047d1b0887](https://linux-hardware.org/?probe=047d1b0887) | Aug 18, 2021 |
| Dell          | 0KC9NP A01                  | [2ca8cc81b1](https://linux-hardware.org/?probe=2ca8cc81b1) | Aug 18, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                                       | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| 5.18.13-200.fc36.x86_64                                       | 29       | 8.63%   |
| 5.18.11-200.fc36.x86_64                                       | 29       | 8.63%   |
| 5.18.5-200.fc36.x86_64                                        | 28       | 8.33%   |
| 5.17.5-300.fc36.x86_64                                        | 26       | 7.74%   |
| 5.17.6-300.fc36.x86_64                                        | 23       | 6.85%   |
| 5.17.11-300.fc36.x86_64                                       | 20       | 5.95%   |
| 5.18.10-200.fc36.x86_64                                       | 18       | 5.36%   |
| 5.17.12-300.fc36.x86_64                                       | 16       | 4.76%   |
| 5.18.9-200.fc36.x86_64                                        | 15       | 4.46%   |
| 5.17.13-300.fc36.x86_64                                       | 15       | 4.46%   |
| 5.17.8-300.fc36.x86_64                                        | 13       | 3.87%   |
| 5.18.7-200.fc36.x86_64                                        | 12       | 3.57%   |
| 5.18.6-200.fc36.x86_64                                        | 11       | 3.27%   |
| 5.17.2-300.fc36.x86_64                                        | 11       | 3.27%   |
| 5.17.1-300.fc36.x86_64                                        | 10       | 2.98%   |
| 5.17.7-300.fc36.x86_64                                        | 9        | 2.68%   |
| 5.17.3-302.fc36.x86_64                                        | 6        | 1.79%   |
| 5.17.9-300.fc36.x86_64                                        | 5        | 1.49%   |
| 5.17.14-300.fc36.x86_64                                       | 3        | 0.89%   |
| 5.17.0-0.rc7.116.fc36.x86_64                                  | 3        | 0.89%   |
| 5.18.1-602.inttf.fc36.x86_64                                  | 2        | 0.6%    |
| 5.18.1-200.fc36.x86_64                                        | 2        | 0.6%    |
| 5.17.4-300.fc36.x86_64                                        | 2        | 0.6%    |
| 5.17.0-0.rc5.102.fc36.x86_64                                  | 2        | 0.6%    |
| 5.15.0-0.rc6.47.fc36.x86_64                                   | 2        | 0.6%    |
| 5.14.0-0.rc5.20210813gitf8e6dfc64f61.46.fc36.x86_64           | 2        | 0.6%    |
| 5.19.0-0.rc5.39.fc37.x86_64                                   | 1        | 0.3%    |
| 5.18.9-gnu                                                    | 1        | 0.3%    |
| 5.18.9-201.fsync.fc36.x86_64                                  | 1        | 0.3%    |
| 5.18.9-100.fc35.x86_64                                        | 1        | 0.3%    |
| 5.18.8-xm1.0.fc36.x86_64                                      | 1        | 0.3%    |
| 5.18.6-201.fsync.fc36.x86_64                                  | 1        | 0.3%    |
| 5.18.5-gnu                                                    | 1        | 0.3%    |
| 5.18.5-201.fsync.fc36.x86_64                                  | 1        | 0.3%    |
| 5.18.2-rc1_MY                                                 | 1        | 0.3%    |
| 5.18.10-201.fsync.fc36.x86_64                                 | 1        | 0.3%    |
| 5.18.0-0.rc4.20220428git8f4dd16603ce834.36.fc37.x86_64        | 1        | 0.3%    |
| 5.17.9-602.inttf.fc36.x86_64                                  | 1        | 0.3%    |
| 5.17.9-301.fsync.fc36.x86_64                                  | 1        | 0.3%    |
| 5.17.7-301.fsync.fc36.x86_64                                  | 1        | 0.3%    |
| 5.17.6-602.inttf.fc36.x86_64                                  | 1        | 0.3%    |
| 5.17.5-301.fsync.fc36.x86_64                                  | 1        | 0.3%    |
| 5.17.12-301.fsync.fc36.x86_64                                 | 1        | 0.3%    |
| 5.17.11-602.inttf.fc36.x86_64                                 | 1        | 0.3%    |
| 5.17.11-301.fsync.fc36.x86_64                                 | 1        | 0.3%    |
| 5.17.0-0.rc0.20220112gitdaadb3bd0e8d.63.fc36.x86_64           | 1        | 0.3%    |
| 5.16.17-200.fc35.x86_64                                       | 1        | 0.3%    |
| 5.15.0-0.rc4.20211008git1da38549dd64.36.vanilla.1.fc36.x86_64 | 1        | 0.3%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.18.5  | 30       | 8.93%   |
| 5.18.13 | 29       | 8.63%   |
| 5.18.11 | 29       | 8.63%   |
| 5.17.5  | 27       | 8.04%   |
| 5.17.6  | 24       | 7.14%   |
| 5.17.11 | 22       | 6.55%   |
| 5.18.10 | 19       | 5.65%   |
| 5.18.9  | 18       | 5.36%   |
| 5.17.12 | 17       | 5.06%   |
| 5.17.13 | 15       | 4.46%   |
| 5.17.8  | 13       | 3.87%   |
| 5.18.7  | 12       | 3.57%   |
| 5.18.6  | 12       | 3.57%   |
| 5.17.2  | 11       | 3.27%   |
| 5.17.7  | 10       | 2.98%   |
| 5.17.1  | 10       | 2.98%   |
| 5.17.9  | 7        | 2.08%   |
| 5.17.3  | 6        | 1.79%   |
| 5.17.0  | 6        | 1.79%   |
| 5.18.1  | 4        | 1.19%   |
| 5.17.14 | 3        | 0.89%   |
| 5.15.0  | 3        | 0.89%   |
| 5.17.4  | 2        | 0.6%    |
| 5.14.0  | 2        | 0.6%    |
| 5.19.0  | 1        | 0.3%    |
| 5.18.8  | 1        | 0.3%    |
| 5.18.2  | 1        | 0.3%    |
| 5.18.0  | 1        | 0.3%    |
| 5.16.17 | 1        | 0.3%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.17    | 165      | 50.93%  |
| 5.18    | 152      | 46.91%  |
| 5.15    | 3        | 0.93%   |
| 5.14    | 2        | 0.62%   |
| 5.19    | 1        | 0.31%   |
| 5.16    | 1        | 0.31%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 312      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 212      | 67.95%  |
| KDE5          | 62       | 19.87%  |
| XFCE          | 10       | 3.21%   |
| Cinnamon      | 10       | 3.21%   |
| X-Cinnamon    | 7        | 2.24%   |
| Unknown       | 6        | 1.92%   |
| MATE          | 3        | 0.96%   |
| LXQt          | 1        | 0.32%   |
| GNOME Classic | 1        | 0.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 192      | 60.76%  |
| X11     | 103      | 32.59%  |
| Tty     | 18       | 5.7%    |
| Web     | 2        | 0.63%   |
| Unknown | 1        | 0.32%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 185      | 59.11%  |
| GDM     | 75       | 23.96%  |
| SDDM    | 28       | 8.95%   |
| LightDM | 25       | 7.99%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 149      | 47.76%  |
| ru_RU | 28       | 8.97%   |
| pt_BR | 21       | 6.73%   |
| en_GB | 21       | 6.73%   |
| en_AU | 15       | 4.81%   |
| fr_FR | 9        | 2.88%   |
| de_DE | 9        | 2.88%   |
| pl_PL | 8        | 2.56%   |
| es_ES | 7        | 2.24%   |
| es_AR | 4        | 1.28%   |
| en_NZ | 4        | 1.28%   |
| cs_CZ | 4        | 1.28%   |
| zh_CN | 3        | 0.96%   |
| en_IN | 3        | 0.96%   |
| en_CA | 3        | 0.96%   |
| ja_JP | 2        | 0.64%   |
| it_IT | 2        | 0.64%   |
| fi_FI | 2        | 0.64%   |
| C     | 2        | 0.64%   |
| tr_TR | 1        | 0.32%   |
| sv_SE | 1        | 0.32%   |
| sr_RS | 1        | 0.32%   |
| sk_SK | 1        | 0.32%   |
| nl_NL | 1        | 0.32%   |
| nl_BE | 1        | 0.32%   |
| fr_BE | 1        | 0.32%   |
| es_MX | 1        | 0.32%   |
| es_EC | 1        | 0.32%   |
| en_ZA | 1        | 0.32%   |
| en_SG | 1        | 0.32%   |
| en_IE | 1        | 0.32%   |
| en_DK | 1        | 0.32%   |
| de_AT | 1        | 0.32%   |
| da_DK | 1        | 0.32%   |
| ar_SA | 1        | 0.32%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 226      | 72.2%   |
| BIOS | 87       | 27.8%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 256      | 82.05%  |
| Ext4  | 40       | 12.82%  |
| Xfs   | 16       | 5.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 182      | 58.15%  |
| GPT     | 103      | 32.91%  |
| MBR     | 28       | 8.95%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 273      | 86.94%  |
| Yes       | 41       | 13.06%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 240      | 76.68%  |
| Yes       | 73       | 23.32%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 106      | 33.97%  |
| Gigabyte Technology | 60       | 19.23%  |
| MSI                 | 57       | 18.27%  |
| ASRock              | 26       | 8.33%   |
| Dell                | 18       | 5.77%   |
| Hewlett-Packard     | 16       | 5.13%   |
| Lenovo              | 6        | 1.92%   |
| Intel               | 4        | 1.28%   |
| Huanan              | 2        | 0.64%   |
| Foxconn             | 2        | 0.64%   |
| Biostar             | 2        | 0.64%   |
| BESSTAR Tech        | 2        | 0.64%   |
| Acer                | 2        | 0.64%   |
| Unknown             | 2        | 0.64%   |
| ZOTAC               | 1        | 0.32%   |
| System76            | 1        | 0.32%   |
| Positivo            | 1        | 0.32%   |
| Pegatron            | 1        | 0.32%   |
| NCR                 | 1        | 0.32%   |
| Fujitsu             | 1        | 0.32%   |
| ECS                 | 1        | 0.32%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| MSI MS-7A38                     | 6        | 1.92%   |
| ASUS ROG STRIX B550-F GAMING    | 6        | 1.92%   |
| ASUS All Series                 | 6        | 1.92%   |
| MSI MS-7C95                     | 3        | 0.96%   |
| MSI MS-7C91                     | 3        | 0.96%   |
| MSI MS-7C37                     | 3        | 0.96%   |
| Dell OptiPlex 9020              | 3        | 0.96%   |
| ASUS TUF Gaming B550M-PLUS      | 3        | 0.96%   |
| ASUS ROG STRIX B550-I GAMING    | 3        | 0.96%   |
| ASUS PRIME X470-PRO             | 3        | 0.96%   |
| ASUS CROSSHAIR V FORMULA-Z      | 3        | 0.96%   |
| Unknown                         | 3        | 0.96%   |
| MSI MS-7D43                     | 2        | 0.64%   |
| MSI MS-7C92                     | 2        | 0.64%   |
| MSI MS-7C56                     | 2        | 0.64%   |
| MSI MS-7B86                     | 2        | 0.64%   |
| MSI MS-7B79                     | 2        | 0.64%   |
| MSI MS-7996                     | 2        | 0.64%   |
| MSI MS-7817                     | 2        | 0.64%   |
| Intel DH77EB AAG39073-304       | 2        | 0.64%   |
| HP Z2 Tower G4 Workstation      | 2        | 0.64%   |
| Gigabyte B450 AORUS M           | 2        | 0.64%   |
| Gigabyte 970A-DS3P              | 2        | 0.64%   |
| Dell OptiPlex 790               | 2        | 0.64%   |
| Dell OptiPlex 7020              | 2        | 0.64%   |
| ASUS TUF Gaming X570-PLUS       | 2        | 0.64%   |
| ASUS ROG STRIX X570-F GAMING    | 2        | 0.64%   |
| ASUS ROG STRIX X570-E GAMING    | 2        | 0.64%   |
| ASUS ROG STRIX B450-F GAMING II | 2        | 0.64%   |
| ASUS ROG CROSSHAIR VIII IMPACT  | 2        | 0.64%   |
| ASUS ProArt Z690-CREATOR WIFI   | 2        | 0.64%   |
| ASUS PRIME Z390-A               | 2        | 0.64%   |
| ASUS PRIME Z370-A               | 2        | 0.64%   |
| ASRock X470 Taichi              | 2        | 0.64%   |
| System76 Thelio Mira            | 1        | 0.32%   |
| Positivo POS-PIH55BO            | 1        | 0.32%   |
| Pegatron IPM41-D3               | 1        | 0.32%   |
| NCR 7606-1007-8801              | 1        | 0.32%   |
| MSI WC698AA-UUG p6320be         | 1        | 0.32%   |
| MSI MS-7D54                     | 1        | 0.32%   |
| MSI MS-7D25                     | 1        | 0.32%   |
| MSI MS-7D18                     | 1        | 0.32%   |
| MSI MS-7D16                     | 1        | 0.32%   |
| MSI MS-7D13                     | 1        | 0.32%   |
| MSI MS-7D06                     | 1        | 0.32%   |
| MSI MS-7C94                     | 1        | 0.32%   |
| MSI MS-7C84                     | 1        | 0.32%   |
| MSI MS-7C82                     | 1        | 0.32%   |
| MSI MS-7C75                     | 1        | 0.32%   |
| MSI MS-7C52                     | 1        | 0.32%   |
| MSI MS-7C35                     | 1        | 0.32%   |
| MSI MS-7C31                     | 1        | 0.32%   |
| MSI MS-7C02                     | 1        | 0.32%   |
| MSI MS-7B93                     | 1        | 0.32%   |
| MSI MS-7B89                     | 1        | 0.32%   |
| MSI MS-7B84                     | 1        | 0.32%   |
| MSI MS-7B48                     | 1        | 0.32%   |
| MSI MS-7B23                     | 1        | 0.32%   |
| MSI MS-7A33                     | 1        | 0.32%   |
| MSI MS-7968                     | 1        | 0.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS ROG             | 32       | 10.26%  |
| ASUS PRIME           | 23       | 7.37%   |
| ASUS TUF             | 13       | 4.17%   |
| Dell OptiPlex        | 10       | 3.21%   |
| MSI MS-7A38          | 6        | 1.92%   |
| ASUS All             | 6        | 1.92%   |
| Dell Precision       | 5        | 1.6%    |
| HP Compaq            | 4        | 1.28%   |
| ASUS CROSSHAIR       | 4        | 1.28%   |
| MSI MS-7C95          | 3        | 0.96%   |
| MSI MS-7C91          | 3        | 0.96%   |
| MSI MS-7C37          | 3        | 0.96%   |
| Lenovo ThinkCentre   | 3        | 0.96%   |
| HP Z2                | 3        | 0.96%   |
| Gigabyte B550        | 3        | 0.96%   |
| Gigabyte B450        | 3        | 0.96%   |
| ASUS ProArt          | 3        | 0.96%   |
| ASRock B450M         | 3        | 0.96%   |
| Unknown              | 3        | 0.96%   |
| MSI MS-7D43          | 2        | 0.64%   |
| MSI MS-7C92          | 2        | 0.64%   |
| MSI MS-7C56          | 2        | 0.64%   |
| MSI MS-7B86          | 2        | 0.64%   |
| MSI MS-7B79          | 2        | 0.64%   |
| MSI MS-7996          | 2        | 0.64%   |
| MSI MS-7817          | 2        | 0.64%   |
| Intel DH77EB         | 2        | 0.64%   |
| HP Pavilion          | 2        | 0.64%   |
| Gigabyte X570        | 2        | 0.64%   |
| Gigabyte H410M       | 2        | 0.64%   |
| Gigabyte 970A-DS3P   | 2        | 0.64%   |
| Dell XPS             | 2        | 0.64%   |
| ASUS M5A97           | 2        | 0.64%   |
| ASRock X570          | 2        | 0.64%   |
| ASRock X470          | 2        | 0.64%   |
| ASRock B450          | 2        | 0.64%   |
| Acer Aspire          | 2        | 0.64%   |
| System76 Thelio      | 1        | 0.32%   |
| Positivo POS-PIH55BO | 1        | 0.32%   |
| Pegatron IPM41-D3    | 1        | 0.32%   |
| NCR 7606-1007-8801   | 1        | 0.32%   |
| MSI WC698AA-UUG      | 1        | 0.32%   |
| MSI MS-7D54          | 1        | 0.32%   |
| MSI MS-7D25          | 1        | 0.32%   |
| MSI MS-7D18          | 1        | 0.32%   |
| MSI MS-7D16          | 1        | 0.32%   |
| MSI MS-7D13          | 1        | 0.32%   |
| MSI MS-7D06          | 1        | 0.32%   |
| MSI MS-7C94          | 1        | 0.32%   |
| MSI MS-7C84          | 1        | 0.32%   |
| MSI MS-7C82          | 1        | 0.32%   |
| MSI MS-7C75          | 1        | 0.32%   |
| MSI MS-7C52          | 1        | 0.32%   |
| MSI MS-7C35          | 1        | 0.32%   |
| MSI MS-7C31          | 1        | 0.32%   |
| MSI MS-7C02          | 1        | 0.32%   |
| MSI MS-7B93          | 1        | 0.32%   |
| MSI MS-7B89          | 1        | 0.32%   |
| MSI MS-7B84          | 1        | 0.32%   |
| MSI MS-7B48          | 1        | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 55       | 17.63%  |
| 2019 | 38       | 12.18%  |
| 2021 | 35       | 11.22%  |
| 2018 | 30       | 9.62%   |
| 2012 | 25       | 8.01%   |
| 2017 | 18       | 5.77%   |
| 2013 | 18       | 5.77%   |
| 2022 | 14       | 4.49%   |
| 2015 | 14       | 4.49%   |
| 2014 | 13       | 4.17%   |
| 2016 | 12       | 3.85%   |
| 2011 | 12       | 3.85%   |
| 2010 | 10       | 3.21%   |
| 2009 | 6        | 1.92%   |
| 2008 | 5        | 1.6%    |
| 2007 | 4        | 1.28%   |
| 2006 | 2        | 0.64%   |
| 2005 | 1        | 0.32%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 312      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 284      | 90.73%  |
| Enabled  | 29       | 9.27%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 312      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 98       | 31.31%  |
| 32.01-64.0  | 85       | 27.16%  |
| 8.01-16.0   | 42       | 13.42%  |
| 4.01-8.0    | 37       | 11.82%  |
| 64.01-256.0 | 28       | 8.95%   |
| 3.01-4.0    | 12       | 3.83%   |
| 24.01-32.0  | 7        | 2.24%   |
| 2.01-3.0    | 2        | 0.64%   |
| 1.01-2.0    | 2        | 0.64%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 99       | 30.46%  |
| 2.01-3.0   | 87       | 26.77%  |
| 3.01-4.0   | 63       | 19.38%  |
| 1.01-2.0   | 34       | 10.46%  |
| 8.01-16.0  | 28       | 8.62%   |
| 0.51-1.0   | 7        | 2.15%   |
| 16.01-24.0 | 5        | 1.54%   |
| 0.01-0.5   | 2        | 0.62%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 98       | 31.41%  |
| 1      | 79       | 25.32%  |
| 3      | 67       | 21.47%  |
| 4      | 44       | 14.1%   |
| 5      | 9        | 2.88%   |
| 6      | 8        | 2.56%   |
| 7      | 5        | 1.6%    |
| 10     | 2        | 0.64%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 227      | 72.76%  |
| Yes       | 85       | 27.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 309      | 99.04%  |
| No        | 3        | 0.96%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 171      | 54.81%  |
| No        | 141      | 45.19%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 167      | 53.35%  |
| Yes       | 146      | 46.65%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country         | Desktops | Percent |
|-----------------|----------|---------|
| USA             | 71       | 22.68%  |
| Russia          | 27       | 8.63%   |
| Brazil          | 26       | 8.31%   |
| Germany         | 16       | 5.11%   |
| Australia       | 15       | 4.79%   |
| Poland          | 13       | 4.15%   |
| UK              | 12       | 3.83%   |
| France          | 12       | 3.83%   |
| Spain           | 9        | 2.88%   |
| Sweden          | 6        | 1.92%   |
| India           | 6        | 1.92%   |
| Finland         | 6        | 1.92%   |
| Belgium         | 6        | 1.92%   |
| Netherlands     | 5        | 1.6%    |
| Argentina       | 5        | 1.6%    |
| Switzerland     | 4        | 1.28%   |
| Italy           | 4        | 1.28%   |
| Israel          | 4        | 1.28%   |
| Czechia         | 4        | 1.28%   |
| Canada          | 4        | 1.28%   |
| Turkey          | 3        | 0.96%   |
| Norway          | 3        | 0.96%   |
| New Zealand     | 3        | 0.96%   |
| Mexico          | 3        | 0.96%   |
| Greece          | 3        | 0.96%   |
| China           | 3        | 0.96%   |
| Belarus         | 3        | 0.96%   |
| Thailand        | 2        | 0.64%   |
| Slovakia        | 2        | 0.64%   |
| Japan           | 2        | 0.64%   |
| Ireland         | 2        | 0.64%   |
| Indonesia       | 2        | 0.64%   |
| Hungary         | 2        | 0.64%   |
| Estonia         | 2        | 0.64%   |
| Ecuador         | 2        | 0.64%   |
| Bulgaria        | 2        | 0.64%   |
| Vietnam         | 1        | 0.32%   |
| Uruguay         | 1        | 0.32%   |
| Ukraine         | 1        | 0.32%   |
| South Korea     | 1        | 0.32%   |
| South Africa    | 1        | 0.32%   |
| Singapore       | 1        | 0.32%   |
| Serbia          | 1        | 0.32%   |
| Saudi Arabia    | 1        | 0.32%   |
| Romania         | 1        | 0.32%   |
| Puerto Rico     | 1        | 0.32%   |
| Portugal        | 1        | 0.32%   |
| Philippines     | 1        | 0.32%   |
| Pakistan        | 1        | 0.32%   |
| North Macedonia | 1        | 0.32%   |
| Denmark         | 1        | 0.32%   |
| Colombia        | 1        | 0.32%   |
| Bangladesh      | 1        | 0.32%   |
| Austria         | 1        | 0.32%   |
| Albania         | 1        | 0.32%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Launceston     | 8        | 2.54%   |
| Moscow         | 5        | 1.59%   |
| Warsaw         | 4        | 1.27%   |
| Novosibirsk    | 4        | 1.27%   |
| Brisbane       | 4        | 1.27%   |
| Vitória       | 3        | 0.95%   |
| Pasco          | 3        | 0.95%   |
| Oulu           | 3        | 0.95%   |
| Minsk          | 3        | 0.95%   |
| Marietta       | 3        | 0.95%   |
| Los Angeles    | 3        | 0.95%   |
| Brussels       | 3        | 0.95%   |
| Auckland       | 3        | 0.95%   |
| Wroclaw        | 2        | 0.63%   |
| Tel Aviv       | 2        | 0.63%   |
| Tallinn        | 2        | 0.63%   |
| St Petersburg  | 2        | 0.63%   |
| Sao Paulo      | 2        | 0.63%   |
| San Jose       | 2        | 0.63%   |
| Porto Alegre   | 2        | 0.63%   |
| Paris          | 2        | 0.63%   |
| New York       | 2        | 0.63%   |
| Mexico City    | 2        | 0.63%   |
| Lane Cove      | 2        | 0.63%   |
| Kansas City    | 2        | 0.63%   |
| Jakarta        | 2        | 0.63%   |
| Houston        | 2        | 0.63%   |
| Goiânia       | 2        | 0.63%   |
| Burgas         | 2        | 0.63%   |
| Bonn           | 2        | 0.63%   |
| Berlin         | 2        | 0.63%   |
| Beijing        | 2        | 0.63%   |
| Athens         | 2        | 0.63%   |
| Allen          | 2        | 0.63%   |
| Zurich         | 1        | 0.32%   |
| Zaporizhzhya   | 1        | 0.32%   |
| Yekaterinburg  | 1        | 0.32%   |
| Yakutsk        | 1        | 0.32%   |
| Woodbine       | 1        | 0.32%   |
| Wetzikon       | 1        | 0.32%   |
| Westlake       | 1        | 0.32%   |
| Westerhoven    | 1        | 0.32%   |
| West Bromwich  | 1        | 0.32%   |
| Vladivostok    | 1        | 0.32%   |
| Villamanta     | 1        | 0.32%   |
| Vigodarzere    | 1        | 0.32%   |
| Vienna         | 1        | 0.32%   |
| Viamao         | 1        | 0.32%   |
| Vaxjo          | 1        | 0.32%   |
| Vancouver      | 1        | 0.32%   |
| Valencia       | 1        | 0.32%   |
| Turku          | 1        | 0.32%   |
| Tucson         | 1        | 0.32%   |
| Toyama         | 1        | 0.32%   |
| Tomsk          | 1        | 0.32%   |
| Tirana         | 1        | 0.32%   |
| Thornton Heath | 1        | 0.32%   |
| The Hague      | 1        | 0.32%   |
| Taytay         | 1        | 0.32%   |
| Tarragona      | 1        | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 120      | 190    | 18.6%   |
| WDC                         | 113      | 166    | 17.52%  |
| Seagate                     | 105      | 147    | 16.28%  |
| Kingston                    | 49       | 55     | 7.6%    |
| Toshiba                     | 36       | 39     | 5.58%   |
| SanDisk                     | 36       | 42     | 5.58%   |
| Crucial                     | 34       | 39     | 5.27%   |
| Phison                      | 16       | 18     | 2.48%   |
| Intel                       | 12       | 12     | 1.86%   |
| Hitachi                     | 9        | 10     | 1.4%    |
| China                       | 9        | 9      | 1.4%    |
| A-DATA Technology           | 9        | 10     | 1.4%    |
| Micron/Crucial Technology   | 8        | 9      | 1.24%   |
| Corsair                     | 6        | 7      | 0.93%   |
| XPG                         | 5        | 6      | 0.78%   |
| SPCC                        | 5        | 8      | 0.78%   |
| SK hynix                    | 4        | 4      | 0.62%   |
| PNY                         | 4        | 6      | 0.62%   |
| Patriot                     | 4        | 5      | 0.62%   |
| Micron Technology           | 4        | 5      | 0.62%   |
| HGST                        | 4        | 6      | 0.62%   |
| Unknown                     | 3        | 4      | 0.47%   |
| GOODRAM                     | 3        | 3      | 0.47%   |
| Gigabyte Technology         | 3        | 6      | 0.47%   |
| SABRENT                     | 2        | 4      | 0.31%   |
| Realtek Semiconductor       | 2        | 2      | 0.31%   |
| OCZ                         | 2        | 2      | 0.31%   |
| MAXIO Technology (Hangzhou) | 2        | 2      | 0.31%   |
| KingDian                    | 2        | 2      | 0.31%   |
| Intenso                     | 2        | 3      | 0.31%   |
| Unknown                     | 2        | 2      | 0.31%   |
| WXC-M3                      | 1        | 1      | 0.16%   |
| USB                         | 1        | 1      | 0.16%   |
| Transcend                   | 1        | 1      | 0.16%   |
| Timetec                     | 1        | 1      | 0.16%   |
| Team                        | 1        | 1      | 0.16%   |
| T-FORCE                     | 1        | 1      | 0.16%   |
| SSK                         | 1        | 2      | 0.16%   |
| Silicon Motion              | 1        | 1      | 0.16%   |
| Realtek                     | 1        | 1      | 0.16%   |
| Plextor                     | 1        | 1      | 0.16%   |
| Phison Electronics          | 1        | 1      | 0.16%   |
| N300                        | 1        | 1      | 0.16%   |
| MyDigitalSSD                | 1        | 1      | 0.16%   |
| Maxtor                      | 1        | 2      | 0.16%   |
| LITEONIT                    | 1        | 1      | 0.16%   |
| LITEON                      | 1        | 1      | 0.16%   |
| Lite-On                     | 1        | 1      | 0.16%   |
| KUIJIA                      | 1        | 1      | 0.16%   |
| KIOXIA-EXCERIA              | 1        | 1      | 0.16%   |
| KIOXIA                      | 1        | 2      | 0.16%   |
| KingSpec                    | 1        | 1      | 0.16%   |
| HP SSD S                    | 1        | 1      | 0.16%   |
| Hewlett-Packard             | 1        | 1      | 0.16%   |
| H/W                         | 1        | 3      | 0.16%   |
| Drevo                       | 1        | 1      | 0.16%   |
| Colorful                    | 1        | 1      | 0.16%   |
| ASMT106x                    | 1        | 1      | 0.16%   |
| ASMT                        | 1        | 1      | 0.16%   |
| Apacer                      | 1        | 1      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Samsung SSD 850 EVO 250GB           | 13       | 1.73%   |
| Samsung NVMe SSD Drive 1TB          | 13       | 1.73%   |
| Kingston SA400S37240G 240GB SSD     | 13       | 1.73%   |
| Seagate ST1000DM010-2EP102 1TB      | 12       | 1.6%    |
| Seagate ST500DM002-1BD142 500GB     | 10       | 1.33%   |
| SanDisk NVMe SSD Drive 500GB        | 9        | 1.2%    |
| Samsung NVMe SSD Drive 2TB          | 9        | 1.2%    |
| Samsung SSD 850 EVO 500GB           | 8        | 1.06%   |
| Samsung NVMe SSD Drive 500GB        | 8        | 1.06%   |
| WDC WD10EZEX-08WN4A0 1TB            | 7        | 0.93%   |
| Samsung SSD 860 EVO 500GB           | 7        | 0.93%   |
| Crucial CT240BX500SSD1 240GB        | 7        | 0.93%   |
| Crucial CT1000MX500SSD1 1TB         | 7        | 0.93%   |
| WDC WD40EFRX-68N32N0 4TB            | 6        | 0.8%    |
| Seagate ST2000DM008-2FR102 2TB      | 6        | 0.8%    |
| Kingston SA400S37120G 120GB SSD     | 6        | 0.8%    |
| Crucial CT500MX500SSD1 500GB        | 6        | 0.8%    |
| WDC WD10EZEX-00WN4A0 1TB            | 5        | 0.66%   |
| SanDisk NVMe SSD Drive 1TB          | 5        | 0.66%   |
| Samsung SSD 970 EVO Plus 500GB      | 5        | 0.66%   |
| Samsung SSD 870 QVO 2TB             | 5        | 0.66%   |
| Samsung SSD 850 EVO 1TB             | 5        | 0.66%   |
| Samsung SSD 840 EVO 250GB           | 5        | 0.66%   |
| Samsung NVMe SSD Drive 250GB        | 5        | 0.66%   |
| WDC WDS100T2B0A-00SM50 1TB SSD      | 4        | 0.53%   |
| WDC WD10EZEX-60M2NA0 1TB            | 4        | 0.53%   |
| Toshiba HDWD110 1TB                 | 4        | 0.53%   |
| Seagate ST2000DM001-1ER164 2TB      | 4        | 0.53%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 4        | 0.53%   |
| Seagate ST1000DM003-1ER162 1TB      | 4        | 0.53%   |
| Samsung SSD 970 EVO Plus 1TB        | 4        | 0.53%   |
| Samsung SSD 870 QVO 1TB             | 4        | 0.53%   |
| Samsung SSD 870 EVO 500GB           | 4        | 0.53%   |
| Phison NVMe SSD Drive 1024GB        | 4        | 0.53%   |
| Micron/Crucial NVMe SSD Drive 500GB | 4        | 0.53%   |
| Kingston NVMe SSD Drive 500GB       | 4        | 0.53%   |
| Crucial CT480BX500SSD1 480GB        | 4        | 0.53%   |
| Crucial CT2000MX500SSD1 2TB         | 4        | 0.53%   |
| WDC WDS500G2B0B-00YS70 500GB SSD    | 3        | 0.4%    |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 3        | 0.4%    |
| WDC WD40EZRZ-00WN9B0 4TB            | 3        | 0.4%    |
| WDC WD20EZRZ-00Z5HB0 2TB            | 3        | 0.4%    |
| Toshiba NVMe SSD Drive 256GB        | 3        | 0.4%    |
| Toshiba DT01ACA100 1TB              | 3        | 0.4%    |
| Seagate ST4000DM004-2CV104 4TB      | 3        | 0.4%    |
| Seagate ST4000DM000-1F2168 4TB      | 3        | 0.4%    |
| Seagate ST3500418AS 500GB           | 3        | 0.4%    |
| Seagate ST2000DM006-2DM164 2TB      | 3        | 0.4%    |
| Seagate ST1000DM003-1SB102 1TB      | 3        | 0.4%    |
| Seagate ST1000DM003-1CH162 1TB      | 3        | 0.4%    |
| Seagate Expansion 1TB               | 3        | 0.4%    |
| Samsung SSD 960 EVO 250GB           | 3        | 0.4%    |
| Samsung SSD 870 EVO 1TB             | 3        | 0.4%    |
| Samsung SSD 850 EVO 120GB           | 3        | 0.4%    |
| Samsung NVMe SSD Drive 512GB        | 3        | 0.4%    |
| PNY CS900 240GB SSD                 | 3        | 0.4%    |
| Phison NVMe SSD Drive 512GB         | 3        | 0.4%    |
| Micron/Crucial NVMe SSD Drive 1TB   | 3        | 0.4%    |
| Kingston SA400S37480G 480GB SSD     | 3        | 0.4%    |
| Kingston NVMe SSD Drive 1TB         | 3        | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 102      | 143    | 40.48%  |
| WDC                 | 95       | 139    | 37.7%   |
| Toshiba             | 28       | 30     | 11.11%  |
| Hitachi             | 9        | 10     | 3.57%   |
| Samsung Electronics | 6        | 7      | 2.38%   |
| HGST                | 4        | 6      | 1.59%   |
| SABRENT             | 2        | 4      | 0.79%   |
| USB                 | 1        | 1      | 0.4%    |
| Unknown             | 1        | 1      | 0.4%    |
| Maxtor              | 1        | 2      | 0.4%    |
| Intenso             | 1        | 1      | 0.4%    |
| ASMT106x            | 1        | 1      | 0.4%    |
| ASMT                | 1        | 1      | 0.4%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 70       | 99     | 29.79%  |
| Kingston            | 33       | 38     | 14.04%  |
| Crucial             | 31       | 36     | 13.19%  |
| WDC                 | 17       | 21     | 7.23%   |
| SanDisk             | 16       | 16     | 6.81%   |
| China               | 9        | 9      | 3.83%   |
| Intel               | 6        | 6      | 2.55%   |
| SPCC                | 5        | 8      | 2.13%   |
| A-DATA Technology   | 5        | 5      | 2.13%   |
| Toshiba             | 4        | 4      | 1.7%    |
| PNY                 | 4        | 6      | 1.7%    |
| Patriot             | 4        | 5      | 1.7%    |
| Corsair             | 4        | 4      | 1.7%    |
| Goodram             | 3        | 3      | 1.28%   |
| Gigabyte Technology | 3        | 6      | 1.28%   |
| Seagate             | 2        | 2      | 0.85%   |
| OCZ                 | 2        | 2      | 0.85%   |
| Micron Technology   | 2        | 2      | 0.85%   |
| KingDian            | 2        | 2      | 0.85%   |
| Transcend           | 1        | 1      | 0.43%   |
| Timetec             | 1        | 1      | 0.43%   |
| Team                | 1        | 1      | 0.43%   |
| SK hynix            | 1        | 1      | 0.43%   |
| Plextor             | 1        | 1      | 0.43%   |
| MyDigitalSSD        | 1        | 1      | 0.43%   |
| LITEONIT            | 1        | 1      | 0.43%   |
| LITEON              | 1        | 1      | 0.43%   |
| KUIJIA              | 1        | 1      | 0.43%   |
| KingSpec            | 1        | 1      | 0.43%   |
| Intenso             | 1        | 2      | 0.43%   |
| Drevo               | 1        | 1      | 0.43%   |
| Apacer              | 1        | 1      | 0.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 201      | 346    | 36.61%  |
| SSD     | 186      | 288    | 33.88%  |
| NVMe    | 152      | 210    | 27.69%  |
| Unknown | 10       | 14     | 1.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 274      | 617    | 61.57%  |
| NVMe | 152      | 209    | 34.16%  |
| SAS  | 19       | 32     | 4.27%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 186      | 296    | 43.26%  |
| 0.51-1.0   | 136      | 185    | 31.63%  |
| 1.01-2.0   | 54       | 75     | 12.56%  |
| 3.01-4.0   | 32       | 48     | 7.44%   |
| 2.01-3.0   | 11       | 11     | 2.56%   |
| 4.01-10.0  | 9        | 15     | 2.09%   |
| 10.01-20.0 | 2        | 4      | 0.47%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 61       | 19.12%  |
| 501-1000       | 61       | 19.12%  |
| More than 3000 | 56       | 17.55%  |
| 251-500        | 41       | 12.85%  |
| 2001-3000      | 33       | 10.34%  |
| 101-250        | 30       | 9.4%    |
| 1-20           | 12       | 3.76%   |
| Unknown        | 12       | 3.76%   |
| 51-100         | 9        | 2.82%   |
| 21-50          | 4        | 1.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 63       | 19.5%   |
| 21-50          | 46       | 14.24%  |
| 1001-2000      | 38       | 11.76%  |
| 101-250        | 37       | 11.46%  |
| 51-100         | 36       | 11.15%  |
| 251-500        | 35       | 10.84%  |
| 501-1000       | 28       | 8.67%   |
| More than 3000 | 19       | 5.88%   |
| Unknown        | 12       | 3.72%   |
| 2001-3000      | 9        | 2.79%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 3        | 3      | 8.11%   |
| Samsung Electronics SSD 870 EVO 1TB | 2        | 2      | 5.41%   |
| Samsung Electronics HD322HJ 320GB   | 2        | 2      | 5.41%   |
| Intel SSDSC2CT120A3 120GB           | 2        | 2      | 5.41%   |
| WDC WD5000AAKX-08ERMA0 500GB        | 1        | 1      | 2.7%    |
| WDC WD5000AAKX-003CA0 500GB         | 1        | 1      | 2.7%    |
| WDC WD3200AAKS-75B3A0 320GB         | 1        | 1      | 2.7%    |
| WDC WD30EZRX-00SPEB0 3TB            | 1        | 1      | 2.7%    |
| WDC WD2500AAKX-753CA1 250GB         | 1        | 1      | 2.7%    |
| WDC WD20EZRX-00D8PB0 2TB            | 1        | 1      | 2.7%    |
| WDC WD20EFRX-68EUZN0 2TB            | 1        | 1      | 2.7%    |
| WDC WD10EZEX-60ZF5A0 1TB            | 1        | 1      | 2.7%    |
| WDC WD10EARS-22Y5B1 1TB             | 1        | 1      | 2.7%    |
| WDC WD1003FBYX-01Y7B1 752GB         | 1        | 1      | 2.7%    |
| Toshiba MQ01ABD050 500GB            | 1        | 2      | 2.7%    |
| Toshiba MK3275GSX 320GB             | 1        | 1      | 2.7%    |
| Toshiba DT01ACA100 1TB              | 1        | 1      | 2.7%    |
| SPCC Solid State Disk 1TB           | 1        | 2      | 2.7%    |
| Seagate ST500LT012-1DG142 500GB     | 1        | 1      | 2.7%    |
| Seagate ST500LM030-2E717D 500GB     | 1        | 1      | 2.7%    |
| Seagate ST4000VN008-2DR166 4TB      | 1        | 1      | 2.7%    |
| Seagate ST3500418AS 500GB           | 1        | 1      | 2.7%    |
| Seagate ST32000542AS 2TB            | 1        | 2      | 2.7%    |
| Seagate ST31000528AS 1TB            | 1        | 1      | 2.7%    |
| Seagate ST2000DX001-1CM164 2TB      | 1        | 1      | 2.7%    |
| Seagate ST1000DM010-2EP102 1TB      | 1        | 1      | 2.7%    |
| Samsung Electronics SSD 870 EVO 2TB | 1        | 1      | 2.7%    |
| Samsung Electronics SSD 850 EVO 1TB | 1        | 1      | 2.7%    |
| Samsung Electronics HD502HJ 500GB   | 1        | 1      | 2.7%    |
| Samsung Electronics HD501LJ 500GB   | 1        | 2      | 2.7%    |
| Hitachi HTS725032A9A364 320GB       | 1        | 1      | 2.7%    |
| Hitachi HDS721010CLA332 1TB         | 1        | 1      | 2.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 10       | 12     | 28.57%  |
| WDC                 | 9        | 10     | 25.71%  |
| Samsung Electronics | 8        | 9      | 22.86%  |
| Toshiba             | 3        | 4      | 8.57%   |
| Intel               | 2        | 2      | 5.71%   |
| Hitachi             | 2        | 2      | 5.71%   |
| SPCC                | 1        | 2      | 2.86%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 10       | 12     | 35.71%  |
| WDC                 | 9        | 10     | 32.14%  |
| Samsung Electronics | 4        | 5      | 14.29%  |
| Toshiba             | 3        | 4      | 10.71%  |
| Hitachi             | 2        | 2      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 27       | 33     | 79.41%  |
| SSD  | 7        | 8      | 20.59%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Samsung Electronics SSD 980 500GB | 1        | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 1        | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 190      | 526    | 54.6%   |
| Works    | 123      | 289    | 35.34%  |
| Malfunc  | 34       | 41     | 9.77%   |
| Failed   | 1        | 2      | 0.29%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 168      | 32.25%  |
| AMD                          | 141      | 27.06%  |
| Samsung Electronics          | 65       | 12.48%  |
| SanDisk                      | 25       | 4.8%    |
| ASMedia Technology           | 23       | 4.41%   |
| Phison Electronics           | 20       | 3.84%   |
| Kingston Technology Company  | 16       | 3.07%   |
| Micron/Crucial Technology    | 11       | 2.11%   |
| ADATA Technology             | 8        | 1.54%   |
| Marvell Technology Group     | 7        | 1.34%   |
| JMicron Technology           | 7        | 1.34%   |
| Toshiba America Info Systems | 4        | 0.77%   |
| Nvidia                       | 4        | 0.77%   |
| SK hynix                     | 3        | 0.58%   |
| Realtek Semiconductor        | 3        | 0.58%   |
| Silicon Motion               | 2        | 0.38%   |
| Silicon Image                | 2        | 0.38%   |
| Micron Technology            | 2        | 0.38%   |
| MAXIO Technology (Hangzhou)  | 2        | 0.38%   |
| KIOXIA                       | 2        | 0.38%   |
| VIA Technologies             | 1        | 0.19%   |
| Unknown                      | 1        | 0.19%   |
| ULi Electronics              | 1        | 0.19%   |
| Seagate Technology           | 1        | 0.19%   |
| Lite-On Technology           | 1        | 0.19%   |
| Broadcom / LSI               | 1        | 0.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 75       | 12.21%  |
| AMD 400 Series Chipset SATA Controller                                                  | 40       | 6.51%   |
| AMD 500 Series Chipset SATA Controller                                                  | 36       | 5.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 30       | 4.89%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 24       | 3.91%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 22       | 3.58%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 16       | 2.61%   |
| Phison E12 NVMe Controller                                                              | 15       | 2.44%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 15       | 2.44%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 15       | 2.44%   |
| Intel SATA Controller [RAID mode]                                                       | 14       | 2.28%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 14       | 2.28%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 13       | 2.12%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 11       | 1.79%   |
| Samsung NVMe SSD Controller 980                                                         | 11       | 1.79%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 11       | 1.79%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 10       | 1.63%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 10       | 1.63%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 10       | 1.63%   |
| SanDisk Non-Volatile memory controller                                                  | 9        | 1.47%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 9        | 1.47%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 9        | 1.47%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 7        | 1.14%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 6        | 0.98%   |
| Kingston Company Company Non-Volatile memory controller                                 | 6        | 0.98%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 6        | 0.98%   |
| Intel SSD 660P Series                                                                   | 5        | 0.81%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 4        | 0.65%   |
| Micron/Crucial NVMe Controller                                                          | 4        | 0.65%   |
| Kingston Company A2000 NVMe SSD                                                         | 4        | 0.65%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4        | 0.65%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 0.65%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 4        | 0.65%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 4        | 0.65%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 4        | 0.65%   |
| SanDisk WD Blue SN570 NVMe SSD                                                          | 3        | 0.49%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 3        | 0.49%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 3        | 0.49%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 3        | 0.49%   |
| JMicron JMB368 IDE controller                                                           | 3        | 0.49%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 3        | 0.49%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3        | 0.49%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 0.49%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 0.49%   |
| AMD X370 Series Chipset SATA Controller                                                 | 3        | 0.49%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 0.49%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 0.49%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 2        | 0.33%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 2        | 0.33%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                    | 2        | 0.33%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 2        | 0.33%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 2        | 0.33%   |
| Realtek Realtek Non-Volatile memory controller                                          | 2        | 0.33%   |
| Phison PS5013 E13 NVMe Controller                                                       | 2        | 0.33%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 0.33%   |
| Micron Non-Volatile memory controller                                                   | 2        | 0.33%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 2        | 0.33%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 2        | 0.33%   |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 2        | 0.33%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 0.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 279      | 55.8%   |
| NVMe | 152      | 30.4%   |
| IDE  | 41       | 8.2%    |
| RAID | 26       | 5.2%    |
| SAS  | 2        | 0.4%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 165      | 52.88%  |
| AMD    | 147      | 47.12%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor          | 15       | 4.78%   |
| AMD Ryzen 5 3600 6-Core Processor           | 13       | 4.14%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 11       | 3.5%    |
| AMD Ryzen 5 5600G with Radeon Graphics      | 9        | 2.87%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 7        | 2.23%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 7        | 2.23%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 7        | 2.23%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 6        | 1.91%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 6        | 1.91%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 6        | 1.91%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 6        | 1.91%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 5        | 1.59%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 5        | 1.59%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 5        | 1.59%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 4        | 1.27%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 4        | 1.27%   |
| AMD FX-6300 Six-Core Processor              | 4        | 1.27%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 3        | 0.96%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 3        | 0.96%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 3        | 0.96%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 3        | 0.96%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 3        | 0.96%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 0.96%   |
| Intel 12th Gen Core i9-12900K               | 3        | 0.96%   |
| Intel 12th Gen Core i7-12700                | 3        | 0.96%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 3        | 0.96%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 3        | 0.96%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 2        | 0.64%   |
| Intel Core i7-8086K CPU @ 4.00GHz           | 2        | 0.64%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 2        | 0.64%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 2        | 0.64%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 2        | 0.64%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2        | 0.64%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 0.64%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 2        | 0.64%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 2        | 0.64%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 0.64%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 2        | 0.64%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 2        | 0.64%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 0.64%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 2        | 0.64%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 0.64%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 2        | 0.64%   |
| Intel 12th Gen Core i7-12700K               | 2        | 0.64%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz      | 2        | 0.64%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 2        | 0.64%   |
| AMD Ryzen 9 5900HX with Radeon Graphics     | 2        | 0.64%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 0.64%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 2        | 0.64%   |
| AMD Ryzen 5 5500                            | 2        | 0.64%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 2        | 0.64%   |
| AMD Ryzen 5 1600X Six-Core Processor        | 2        | 0.64%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2        | 0.64%   |
| AMD Phenom II X4 955 Processor              | 2        | 0.64%   |
| AMD Phenom II X2 570 Processor              | 2        | 0.64%   |
| AMD FX-8350 Eight-Core Processor            | 2        | 0.64%   |
| AMD FX-8120 Eight-Core Processor            | 2        | 0.64%   |
| AMD Athlon Dual Core Processor 4850e        | 2        | 0.64%   |
| Intel Xeon W-2225 CPU @ 4.10GHz             | 1        | 0.32%   |
| Intel Xeon CPU X5460 @ 3.16GHz              | 1        | 0.32%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD Ryzen 5             | 56       | 17.89%  |
| Intel Core i5           | 52       | 16.61%  |
| Intel Core i7           | 42       | 13.42%  |
| AMD Ryzen 7             | 31       | 9.9%    |
| AMD Ryzen 9             | 25       | 7.99%   |
| Other                   | 22       | 7.03%   |
| Intel Core i3           | 13       | 4.15%   |
| AMD FX                  | 12       | 3.83%   |
| Intel Xeon              | 10       | 3.19%   |
| Intel Core i9           | 8        | 2.56%   |
| Intel Core 2 Duo        | 6        | 1.92%   |
| Intel Atom              | 3        | 0.96%   |
| AMD Ryzen 3             | 3        | 0.96%   |
| AMD Phenom II X4        | 3        | 0.96%   |
| AMD Phenom II X2        | 3        | 0.96%   |
| Intel Pentium           | 2        | 0.64%   |
| Intel Core 2 Quad       | 2        | 0.64%   |
| Intel Celeron           | 2        | 0.64%   |
| AMD Athlon Dual Core    | 2        | 0.64%   |
| AMD Athlon 64 X2        | 2        | 0.64%   |
| AMD A8                  | 2        | 0.64%   |
| AMD A6                  | 2        | 0.64%   |
| AMD A10                 | 2        | 0.64%   |
| Intel Pentium Silver    | 1        | 0.32%   |
| Intel Pentium Gold      | 1        | 0.32%   |
| Intel Pentium Dual-Core | 1        | 0.32%   |
| Intel Genuine           | 1        | 0.32%   |
| AMD Ryzen 7 PRO         | 1        | 0.32%   |
| AMD Opteron             | 1        | 0.32%   |
| AMD Athlon X4           | 1        | 0.32%   |
| AMD Athlon 64           | 1        | 0.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 94       | 30.03%  |
| 6      | 86       | 27.48%  |
| 8      | 46       | 14.7%   |
| 2      | 40       | 12.78%  |
| 12     | 24       | 7.67%   |
| 16     | 10       | 3.19%   |
| 10     | 6        | 1.92%   |
| 3      | 5        | 1.6%    |
| 18     | 1        | 0.32%   |
| 1      | 1        | 0.32%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 310      | 99.36%  |
| 2      | 2        | 0.64%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 235      | 75.32%  |
| 1      | 77       | 24.68%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 312      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 27       | 8.63%   |
| 0x0a201016 | 24       | 7.67%   |
| 0x08701021 | 24       | 7.67%   |
| Unknown    | 17       | 5.43%   |
| 0x906ea    | 15       | 4.79%   |
| 0x306a9    | 15       | 4.79%   |
| 0x0800820d | 15       | 4.79%   |
| 0x0a50000c | 14       | 4.47%   |
| 0x506e3    | 12       | 3.83%   |
| 0x206a7    | 11       | 3.51%   |
| 0x90672    | 10       | 3.19%   |
| 0xa0671    | 8        | 2.56%   |
| 0xa0655    | 7        | 2.24%   |
| 0xa0653    | 7        | 2.24%   |
| 0x906e9    | 7        | 2.24%   |
| 0x0a201009 | 7        | 2.24%   |
| 0x06000822 | 7        | 2.24%   |
| 0x1067a    | 6        | 1.92%   |
| 0x906ed    | 5        | 1.6%    |
| 0x08701013 | 4        | 1.28%   |
| 0x6fb      | 3        | 0.96%   |
| 0x306f2    | 3        | 0.96%   |
| 0x206d7    | 3        | 0.96%   |
| 0x106e5    | 3        | 0.96%   |
| 0x0a50000d | 3        | 0.96%   |
| 0x0a20120a | 3        | 0.96%   |
| 0x0a201205 | 3        | 0.96%   |
| 0x08101016 | 3        | 0.96%   |
| 0x08001138 | 3        | 0.96%   |
| 0x08001137 | 3        | 0.96%   |
| 0x010000b6 | 3        | 0.96%   |
| 0x906ec    | 2        | 0.64%   |
| 0x906eb    | 2        | 0.64%   |
| 0x90675    | 2        | 0.64%   |
| 0x30661    | 2        | 0.64%   |
| 0x20655    | 2        | 0.64%   |
| 0x20652    | 2        | 0.64%   |
| 0x10676    | 2        | 0.64%   |
| 0x0a201204 | 2        | 0.64%   |
| 0x06001119 | 2        | 0.64%   |
| 0x06000817 | 2        | 0.64%   |
| 0x010000c6 | 2        | 0.64%   |
| 0x906c0    | 1        | 0.32%   |
| 0x50657    | 1        | 0.32%   |
| 0x40661    | 1        | 0.32%   |
| 0x106ca    | 1        | 0.32%   |
| 0x0a50000b | 1        | 0.32%   |
| 0x08600106 | 1        | 0.32%   |
| 0x08108109 | 1        | 0.32%   |
| 0x08008206 | 1        | 0.32%   |
| 0x0800111c | 1        | 0.32%   |
| 0x0700010b | 1        | 0.32%   |
| 0x06006705 | 1        | 0.32%   |
| 0x0600063d | 1        | 0.32%   |
| 0x06000626 | 1        | 0.32%   |
| 0x06000623 | 1        | 0.32%   |
| 0x03000027 | 1        | 0.32%   |
| 0x00000000 | 1        | 0.32%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 61       | 19.49%  |
| Haswell          | 33       | 10.54%  |
| KabyLake         | 31       | 9.9%    |
| Zen 2            | 29       | 9.27%   |
| Zen+             | 17       | 5.43%   |
| IvyBridge        | 15       | 4.79%   |
| CometLake        | 15       | 4.79%   |
| SandyBridge      | 14       | 4.47%   |
| Skylake          | 13       | 4.15%   |
| Piledriver       | 12       | 3.83%   |
| Alderlake Hybrid | 12       | 3.83%   |
| Zen              | 10       | 3.19%   |
| Penryn           | 8        | 2.56%   |
| Icelake          | 8        | 2.56%   |
| K10              | 7        | 2.24%   |
| K8 Hammer        | 5        | 1.6%    |
| Westmere         | 4        | 1.28%   |
| Nehalem          | 3        | 0.96%   |
| Core             | 3        | 0.96%   |
| Bulldozer        | 3        | 0.96%   |
| Bonnell          | 3        | 0.96%   |
| Unknown          | 2        | 0.64%   |
| Tremont          | 1        | 0.32%   |
| Steamroller      | 1        | 0.32%   |
| K10 Llano        | 1        | 0.32%   |
| Jaguar           | 1        | 0.32%   |
| Excavator        | 1        | 0.32%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 133      | 39.7%   |
| AMD               | 133      | 39.7%   |
| Intel             | 68       | 20.3%   |
| ASPEED Technology | 1        | 0.3%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 22       | 6.34%   |
| AMD Cezanne                                                                 | 14       | 4.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 13       | 3.75%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 13       | 3.75%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 12       | 3.46%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 11       | 3.17%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 10       | 2.88%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 9        | 2.59%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 6        | 1.73%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 6        | 1.73%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 6        | 1.73%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 6        | 1.73%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 5        | 1.44%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 5        | 1.44%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5        | 1.44%   |
| Intel AlderLake-S GT1                                                       | 5        | 1.44%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 1.44%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 5        | 1.44%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 4        | 1.15%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 4        | 1.15%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 1.15%   |
| Intel HD Graphics 530                                                       | 4        | 1.15%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 4        | 1.15%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 3        | 0.86%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 3        | 0.86%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 3        | 0.86%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 3        | 0.86%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 0.86%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 0.86%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 3        | 0.86%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 3        | 0.86%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 3        | 0.86%   |
| Intel Core Processor Integrated Graphics Controller                         | 3        | 0.86%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 3        | 0.86%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 0.86%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 0.86%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 3        | 0.86%   |
| AMD Bonaire XTX [Radeon R7 260X/360]                                        | 3        | 0.86%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 2        | 0.58%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 0.58%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 2        | 0.58%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 0.58%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 2        | 0.58%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 2        | 0.58%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 2        | 0.58%   |
| Nvidia GF108GL [Quadro 600]                                                 | 2        | 0.58%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 2        | 0.58%   |
| Nvidia GA106 [GeForce RTX 3060]                                             | 2        | 0.58%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 0.58%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 2        | 0.58%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 2        | 0.58%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 2        | 0.58%   |
| Intel VGA compatible controller                                             | 2        | 0.58%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 0.58%   |
| Intel HD Graphics 630                                                       | 2        | 0.58%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller             | 2        | 0.58%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 2        | 0.58%   |
| AMD RS880 [Radeon HD 4250]                                                  | 2        | 0.58%   |
| AMD RS780L [Radeon 3000]                                                    | 2        | 0.58%   |
| AMD Navi 24 [Radeon RX 6400 / 6500 XT]                                      | 2        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 122      | 39.1%   |
| 1 x AMD         | 118      | 37.82%  |
| 1 x Intel       | 48       | 15.38%  |
| 2 x AMD         | 8        | 2.56%   |
| Intel + Nvidia  | 7        | 2.24%   |
| Intel + AMD     | 3        | 0.96%   |
| AMD + Nvidia    | 3        | 0.96%   |
| 2 x Nvidia      | 1        | 0.32%   |
| Intel + 2 x AMD | 1        | 0.32%   |
| 1 x ASPEED      | 1        | 0.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 219      | 69.3%   |
| Proprietary | 84       | 26.58%  |
| Unknown     | 13       | 4.11%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 105      | 33.33%  |
| 7.01-8.0   | 50       | 15.87%  |
| 3.01-4.0   | 46       | 14.6%   |
| 1.01-2.0   | 35       | 11.11%  |
| 0.51-1.0   | 24       | 7.62%   |
| 8.01-16.0  | 23       | 7.3%    |
| 0.01-0.5   | 16       | 5.08%   |
| 5.01-6.0   | 13       | 4.13%   |
| 2.01-3.0   | 3        | 0.95%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 52       | 15.12%  |
| Samsung Electronics  | 50       | 14.53%  |
| Dell                 | 37       | 10.76%  |
| Philips              | 20       | 5.81%   |
| BenQ                 | 20       | 5.81%   |
| AOC                  | 19       | 5.52%   |
| Hewlett-Packard      | 18       | 5.23%   |
| Acer                 | 16       | 4.65%   |
| ViewSonic            | 12       | 3.49%   |
| Ancor Communications | 12       | 3.49%   |
| Lenovo               | 10       | 2.91%   |
| Iiyama               | 9        | 2.62%   |
| ASUSTek Computer     | 8        | 2.33%   |
| Gigabyte Technology  | 7        | 2.03%   |
| Sceptre Tech         | 5        | 1.45%   |
| MSI                  | 5        | 1.45%   |
| Sony                 | 3        | 0.87%   |
| NEC Computers        | 3        | 0.87%   |
| Mi                   | 3        | 0.87%   |
| Unknown              | 2        | 0.58%   |
| SGT                  | 2        | 0.58%   |
| RTK                  | 2        | 0.58%   |
| Mitsubishi           | 2        | 0.58%   |
| Marantz              | 2        | 0.58%   |
| HUAWEI               | 2        | 0.58%   |
| HannStar             | 2        | 0.58%   |
| Eizo                 | 2        | 0.58%   |
| Vizio                | 1        | 0.29%   |
| Pixio                | 1        | 0.29%   |
| Packard Bell         | 1        | 0.29%   |
| ONN                  | 1        | 0.29%   |
| Onkyo                | 1        | 0.29%   |
| NEX                  | 1        | 0.29%   |
| MIT                  | 1        | 0.29%   |
| Medion               | 1        | 0.29%   |
| Insignia             | 1        | 0.29%   |
| INS                  | 1        | 0.29%   |
| HVR                  | 1        | 0.29%   |
| Fujitsu Siemens      | 1        | 0.29%   |
| FOX                  | 1        | 0.29%   |
| Element              | 1        | 0.29%   |
| DSC                  | 1        | 0.29%   |
| DMG                  | 1        | 0.29%   |
| Denver               | 1        | 0.29%   |
| CHD                  | 1        | 0.29%   |
| AGO                  | 1        | 0.29%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 4        | 1.09%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 3        | 0.82%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 3        | 0.82%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                     | 3        | 0.82%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                  | 3        | 0.82%   |
| Goldstar LG ULTRAGEAR GSM774B 3440x1440 800x330mm 34.1-inch          | 3        | 0.82%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 3        | 0.82%   |
| Gigabyte Technology G32QC GBT3200 2560x1440 697x392mm 31.5-inch      | 3        | 0.82%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 2        | 0.55%   |
| Sceptre Tech Sceptre M25 SPT0A05 1920x1080 597x336mm 27.0-inch       | 2        | 0.55%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch    | 2        | 0.55%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch              | 2        | 0.55%   |
| Marantz AVR MJI0031 1920x1080 2210x1250mm 100.0-inch                 | 2        | 0.55%   |
| Lenovo LEN L1711pC LEN13B7 1280x1024 360x300mm 18.4-inch             | 2        | 0.55%   |
| Hewlett-Packard E243 HPN3468 1920x1080 527x296mm 23.8-inch           | 2        | 0.55%   |
| Goldstar W2442 GSM56D9 1920x1080 531x299mm 24.0-inch                 | 2        | 0.55%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 2        | 0.55%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                | 2        | 0.55%   |
| Dell U2414H DELA0A2 1920x1080 527x296mm 23.8-inch                    | 2        | 0.55%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                    | 2        | 0.55%   |
| AOC Q3277 AOC3277 2560x1440 708x399mm 32.0-inch                      | 2        | 0.55%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                   | 2        | 0.55%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch     | 2        | 0.55%   |
| Vizio V705-H3 VIZ1039 3840x2160 1538x865mm 69.5-inch                 | 1        | 0.27%   |
| ViewSonic XG2705-2K VSCD73A 2560x1440 597x336mm 27.0-inch            | 1        | 0.27%   |
| ViewSonic XG2401 SERIES VSCBB31 1920x1080 531x299mm 24.0-inch        | 1        | 0.27%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch           | 1        | 0.27%   |
| ViewSonic VX2703 SERIES VSCF62B 1920x1080 597x336mm 27.0-inch        | 1        | 0.27%   |
| ViewSonic VX2458-mhd VSC0437 1920x1080 521x293mm 23.5-inch           | 1        | 0.27%   |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch        | 1        | 0.27%   |
| ViewSonic VX2257 VSCB731 1920x1080 477x268mm 21.5-inch               | 1        | 0.27%   |
| ViewSonic VX2245wm VSCBB1E 1680x1050 474x296mm 22.0-inch             | 1        | 0.27%   |
| ViewSonic VA2465 SERIES VSCB730 1920x1080 521x293mm 23.5-inch        | 1        | 0.27%   |
| ViewSonic VA2445 SERIES VSC712E 1920x1080 521x293mm 23.5-inch        | 1        | 0.27%   |
| ViewSonic LCD Monitor VSC692F 1920x1080 480x270mm 21.7-inch          | 1        | 0.27%   |
| ViewSonic LCD Monitor VA2226w-3 1680x1050                            | 1        | 0.27%   |
| Sony TV SNY9402 1920x1080                                            | 1        | 0.27%   |
| Sony TV SNY6F02 1360x768                                             | 1        | 0.27%   |
| Sony TV *00 SNYF303 1920x1080 1218x685mm 55.0-inch                   | 1        | 0.27%   |
| SGT Monitor SGT2700 2560x1440 601x329mm 27.0-inch                    | 1        | 0.27%   |
| SGT LM156LCFL_03 SGT1560 1920x1080 345x194mm 15.6-inch               | 1        | 0.27%   |
| Sceptre Tech Sceptre E20 SPT080D 1600x900 410x280mm 19.5-inch        | 1        | 0.27%   |
| Sceptre Tech F27 SPT0ABF 1920x1080 409x230mm 18.5-inch               | 1        | 0.27%   |
| Sceptre Tech E225W-19206C SPT2261 1920x1080 521x293mm 23.5-inch      | 1        | 0.27%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch    | 1        | 0.27%   |
| Samsung Electronics U28D590 SAM0B80 3840x2160 607x345mm 27.5-inch    | 1        | 0.27%   |
| Samsung Electronics T27B550 SAM095C 1920x1080 598x336mm 27.0-inch    | 1        | 0.27%   |
| Samsung Electronics SyncMaster SAM0593 1920x1080 477x268mm 21.5-inch | 1        | 0.27%   |
| Samsung Electronics SyncMaster SAM049B 1920x1080 477x268mm 21.5-inch | 1        | 0.27%   |
| Samsung Electronics SyncMaster SAM0481 1680x1050 474x296mm 22.0-inch | 1        | 0.27%   |
| Samsung Electronics SyncMaster SAM041D 1920x1200 459x296mm 21.5-inch | 1        | 0.27%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 470x300mm 22.0-inch | 1        | 0.27%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch | 1        | 0.27%   |
| Samsung Electronics SyncMaster SAM01D3 1440x900 408x225mm 18.3-inch  | 1        | 0.27%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch | 1        | 0.27%   |
| Samsung Electronics SME1920N SAM06A3 1366x768 410x230mm 18.5-inch    | 1        | 0.27%   |
| Samsung Electronics SMBX2350 SAM071E 1920x1080 509x286mm 23.0-inch   | 1        | 0.27%   |
| Samsung Electronics SMB2030N SAM0634 1600x900 443x249mm 20.0-inch    | 1        | 0.27%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch    | 1        | 0.27%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch | 1        | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 156      | 46.85%  |
| 2560x1440 (QHD)    | 44       | 13.21%  |
| 3840x2160 (4K)     | 42       | 12.61%  |
| 3440x1440          | 19       | 5.71%   |
| 1366x768 (WXGA)    | 14       | 4.2%    |
| 1680x1050 (WSXGA+) | 9        | 2.7%    |
| 1280x1024 (SXGA)   | 9        | 2.7%    |
| 2560x1080          | 7        | 2.1%    |
| 1600x900 (HD+)     | 7        | 2.1%    |
| 1920x1200 (WUXGA)  | 5        | 1.5%    |
| 1440x900 (WXGA+)   | 4        | 1.2%    |
| 1920x540           | 3        | 0.9%    |
| 1360x768           | 3        | 0.9%    |
| 3840x1080          | 2        | 0.6%    |
| 2288x1287          | 2        | 0.6%    |
| 1600x1200          | 2        | 0.6%    |
| 3840x1600          | 1        | 0.3%    |
| 2560x1600          | 1        | 0.3%    |
| 2200x1650          | 1        | 0.3%    |
| 2160x1200          | 1        | 0.3%    |
| 1024x768 (XGA)     | 1        | 0.3%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 75       | 21.37%  |
| 24      | 53       | 15.1%   |
| 23      | 41       | 11.68%  |
| 21      | 41       | 11.68%  |
| 31      | 27       | 7.69%   |
| 34      | 20       | 5.7%    |
| 18      | 13       | 3.7%    |
| 22      | 9        | 2.56%   |
| 20      | 9        | 2.56%   |
| Unknown | 8        | 2.28%   |
| 32      | 7        | 1.99%   |
| 72      | 6        | 1.71%   |
| 19      | 5        | 1.42%   |
| 17      | 4        | 1.14%   |
| 48      | 3        | 0.85%   |
| 142     | 2        | 0.57%   |
| 100     | 2        | 0.57%   |
| 84      | 2        | 0.57%   |
| 54      | 2        | 0.57%   |
| 42      | 2        | 0.57%   |
| 40      | 2        | 0.57%   |
| 29      | 2        | 0.57%   |
| 25      | 2        | 0.57%   |
| 15      | 2        | 0.57%   |
| 75      | 1        | 0.28%   |
| 69      | 1        | 0.28%   |
| 49      | 1        | 0.28%   |
| 46      | 1        | 0.28%   |
| 39      | 1        | 0.28%   |
| 38      | 1        | 0.28%   |
| 37      | 1        | 0.28%   |
| 36      | 1        | 0.28%   |
| 35      | 1        | 0.28%   |
| 28      | 1        | 0.28%   |
| 26      | 1        | 0.28%   |
| 12      | 1        | 0.28%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 151      | 44.94%  |
| 401-500        | 70       | 20.83%  |
| 601-700        | 39       | 11.61%  |
| 701-800        | 28       | 8.33%   |
| 1501-2000      | 10       | 2.98%   |
| Unknown        | 8        | 2.38%   |
| 301-350        | 6        | 1.79%   |
| 1001-1500      | 6        | 1.79%   |
| 801-900        | 5        | 1.49%   |
| 351-400        | 5        | 1.49%   |
| More than 2000 | 4        | 1.19%   |
| 901-1000       | 3        | 0.89%   |
| 201-300        | 1        | 0.3%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 245      | 78.27%  |
| 21/9    | 24       | 7.67%   |
| 16/10   | 23       | 7.35%   |
| 5/4     | 7        | 2.24%   |
| 4/3     | 4        | 1.28%   |
| 6/5     | 2        | 0.64%   |
| 32/9    | 2        | 0.64%   |
| 1.00    | 2        | 0.64%   |
| Unknown | 2        | 0.64%   |
| 3/2     | 1        | 0.32%   |
| 1.96    | 1        | 0.32%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 108      | 31.58%  |
| 301-350        | 77       | 22.51%  |
| 351-500        | 57       | 16.67%  |
| 151-200        | 31       | 9.06%   |
| More than 1000 | 17       | 4.97%   |
| 251-300        | 16       | 4.68%   |
| 141-150        | 14       | 4.09%   |
| 501-1000       | 11       | 3.22%   |
| Unknown        | 8        | 2.34%   |
| 101-110        | 2        | 0.58%   |
| 71-80          | 1        | 0.29%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 186      | 56.88%  |
| 101-120 | 88       | 26.91%  |
| 121-160 | 18       | 5.5%    |
| 1-50    | 15       | 4.59%   |
| 161-240 | 12       | 3.67%   |
| Unknown | 8        | 2.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 230      | 73.48%  |
| 2     | 58       | 18.53%  |
| 0     | 13       | 4.15%   |
| 3     | 10       | 3.19%   |
| 4     | 2        | 0.64%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 193      | 41.42%  |
| Intel                           | 179      | 38.41%  |
| Qualcomm Atheros                | 15       | 3.22%   |
| TP-Link                         | 11       | 2.36%   |
| Broadcom                        | 8        | 1.72%   |
| Ralink Technology               | 6        | 1.29%   |
| MediaTek                        | 6        | 1.29%   |
| Qualcomm Atheros Communications | 5        | 1.07%   |
| Nvidia                          | 4        | 0.86%   |
| Microsoft                       | 4        | 0.86%   |
| Aquantia                        | 4        | 0.86%   |
| Xiaomi                          | 3        | 0.64%   |
| Ralink                          | 3        | 0.64%   |
| ASUSTek Computer                | 3        | 0.64%   |
| Mellanox Technologies           | 2        | 0.43%   |
| Marvell Technology Group        | 2        | 0.43%   |
| ASIX Electronics                | 2        | 0.43%   |
| Apple                           | 2        | 0.43%   |
| Sierra Wireless                 | 1        | 0.21%   |
| Samsung Electronics             | 1        | 0.21%   |
| QNAP System                     | 1        | 0.21%   |
| PLANEX                          | 1        | 0.21%   |
| NetGear                         | 1        | 0.21%   |
| MicroPython                     | 1        | 0.21%   |
| LSI                             | 1        | 0.21%   |
| Lenovo                          | 1        | 0.21%   |
| InterBiometrics                 | 1        | 0.21%   |
| Google                          | 1        | 0.21%   |
| Edimax Technology               | 1        | 0.21%   |
| Conexant Systems                | 1        | 0.21%   |
| Broadcom Limited                | 1        | 0.21%   |
| Belkin Components               | 1        | 0.21%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 130      | 23.9%   |
| Intel Wi-Fi 6 AX200                                                 | 44       | 8.09%   |
| Realtek RTL8125 2.5GbE Controller                                   | 35       | 6.43%   |
| Intel I211 Gigabit Network Connection                               | 31       | 5.7%    |
| Intel Ethernet Controller I225-V                                    | 29       | 5.33%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 13       | 2.39%   |
| Intel Ethernet Connection (2) I219-V                                | 13       | 2.39%   |
| Intel Ethernet Connection I217-LM                                   | 8        | 1.47%   |
| Intel Ethernet Connection (7) I219-V                                | 8        | 1.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 8        | 1.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 7        | 1.29%   |
| TP-Link 802.11ac NIC                                                | 6        | 1.1%    |
| Intel Alder Lake-S PCH CNVi WiFi                                    | 6        | 1.1%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 5        | 0.92%   |
| Intel Ethernet Connection (2) I218-V                                | 5        | 0.92%   |
| Intel 82579V Gigabit Network Connection                             | 5        | 0.92%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                  | 5        | 0.92%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 4        | 0.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 4        | 0.74%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 4        | 0.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 4        | 0.74%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 4        | 0.74%   |
| Ralink MT7601U Wireless Adapter                                     | 4        | 0.74%   |
| Qualcomm Atheros AR9271 802.11n                                     | 4        | 0.74%   |
| Intel Wireless 8265 / 8275                                          | 4        | 0.74%   |
| Intel Ethernet Connection (7) I219-LM                               | 4        | 0.74%   |
| Intel Ethernet Connection (2) I219-LM                               | 4        | 0.74%   |
| Intel 82574L Gigabit Network Connection                             | 4        | 0.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 3        | 0.55%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 3        | 0.55%   |
| Realtek 802.11ac NIC                                                | 3        | 0.55%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 3        | 0.55%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 3        | 0.55%   |
| Microsoft Xbox 360 Wireless Adapter                                 | 3        | 0.55%   |
| Intel Wireless-AC 9260                                              | 3        | 0.55%   |
| Intel Wireless 7265                                                 | 3        | 0.55%   |
| Intel Wireless 7260                                                 | 3        | 0.55%   |
| Intel Ethernet Connection I217-V                                    | 3        | 0.55%   |
| Intel 82583V Gigabit Network Connection                             | 3        | 0.55%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3        | 0.55%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                | 2        | 0.37%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                         | 2        | 0.37%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 2        | 0.37%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter            | 2        | 0.37%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                     | 2        | 0.37%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                          | 2        | 0.37%   |
| Realtek Killer E3000 2.5GbE Controller                              | 2        | 0.37%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 2        | 0.37%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 2        | 0.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 2        | 0.37%   |
| Nvidia MCP61 Ethernet                                               | 2        | 0.37%   |
| Mellanox MT27500 Family [ConnectX-3]                                | 2        | 0.37%   |
| Intel Wireless 3160                                                 | 2        | 0.37%   |
| Intel Tiger Lake PCH CNVi WiFi                                      | 2        | 0.37%   |
| Intel I210 Gigabit Network Connection                               | 2        | 0.37%   |
| Intel Ethernet Connection (11) I219-V                               | 2        | 0.37%   |
| Intel Cannon Lake PCH CNVi WiFi                                     | 2        | 0.37%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 2        | 0.37%   |
| Intel 82566DM-2 Gigabit Network Connection                          | 2        | 0.37%   |
| ASIX AX88179 Gigabit Ethernet                                       | 2        | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 94       | 51.93%  |
| Realtek Semiconductor           | 31       | 17.13%  |
| TP-Link                         | 11       | 6.08%   |
| Broadcom                        | 7        | 3.87%   |
| Ralink Technology               | 6        | 3.31%   |
| Qualcomm Atheros                | 6        | 3.31%   |
| MediaTek                        | 6        | 3.31%   |
| Qualcomm Atheros Communications | 5        | 2.76%   |
| Microsoft                       | 4        | 2.21%   |
| Ralink                          | 3        | 1.66%   |
| ASUSTek Computer                | 2        | 1.1%    |
| Sierra Wireless                 | 1        | 0.55%   |
| PLANEX                          | 1        | 0.55%   |
| NetGear                         | 1        | 0.55%   |
| Edimax Technology               | 1        | 0.55%   |
| Broadcom Limited                | 1        | 0.55%   |
| Belkin Components               | 1        | 0.55%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 44       | 24.31%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 13       | 7.18%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 7        | 3.87%   |
| TP-Link 802.11ac NIC                                           | 6        | 3.31%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 6        | 3.31%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 5        | 2.76%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 5        | 2.76%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 4        | 2.21%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 4        | 2.21%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 4        | 2.21%   |
| Ralink MT7601U Wireless Adapter                                | 4        | 2.21%   |
| Qualcomm Atheros AR9271 802.11n                                | 4        | 2.21%   |
| Intel Wireless 8265 / 8275                                     | 4        | 2.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 3        | 1.66%   |
| Realtek 802.11ac NIC                                           | 3        | 1.66%   |
| Microsoft Xbox 360 Wireless Adapter                            | 3        | 1.66%   |
| Intel Wireless-AC 9260                                         | 3        | 1.66%   |
| Intel Wireless 7265                                            | 3        | 1.66%   |
| Intel Wireless 7260                                            | 3        | 1.66%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 2        | 1.1%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2        | 1.1%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2        | 1.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2        | 1.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2        | 1.1%    |
| Intel Wireless 3160                                            | 2        | 1.1%    |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2        | 1.1%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 2        | 1.1%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1        | 0.55%   |
| Sierra Wireless MC7700                                         | 1        | 0.55%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1        | 0.55%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter            | 1        | 0.55%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1        | 0.55%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 1        | 0.55%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 1        | 0.55%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1        | 0.55%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1        | 0.55%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 1        | 0.55%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)      | 1        | 0.55%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1        | 0.55%   |
| Realtek RTL8187 Wireless Adapter                               | 1        | 0.55%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1        | 0.55%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter              | 1        | 0.55%   |
| Ralink RT5392 PCIe Wireless Network Adapter                    | 1        | 0.55%   |
| Ralink RT5362 PCI 802.11n Wireless Network Adapter             | 1        | 0.55%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                      | 1        | 0.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1        | 0.55%   |
| Qualcomm Atheros AR5523                                        | 1        | 0.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1        | 0.55%   |
| PLANEX GW-USNano                                               | 1        | 0.55%   |
| NetGear A6210                                                  | 1        | 0.55%   |
| Microsoft XBOX ACC                                             | 1        | 0.55%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1        | 0.55%   |
| Intel Wireless 8260                                            | 1        | 0.55%   |
| Intel Wireless 3165                                            | 1        | 0.55%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 1        | 0.55%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1        | 0.55%   |
| Intel Centrino Wireless-N 2230                                 | 1        | 0.55%   |
| Edimax 802.11ac WLAN Adapter                                   | 1        | 0.55%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 1        | 0.55%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 1        | 0.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 178      | 51.15%  |
| Intel                    | 135      | 38.79%  |
| Qualcomm Atheros         | 11       | 3.16%   |
| Nvidia                   | 4        | 1.15%   |
| Aquantia                 | 4        | 1.15%   |
| Xiaomi                   | 3        | 0.86%   |
| Marvell Technology Group | 2        | 0.57%   |
| ASIX Electronics         | 2        | 0.57%   |
| Apple                    | 2        | 0.57%   |
| Samsung Electronics      | 1        | 0.29%   |
| QNAP System              | 1        | 0.29%   |
| Mellanox Technologies    | 1        | 0.29%   |
| Lenovo                   | 1        | 0.29%   |
| Google                   | 1        | 0.29%   |
| Broadcom                 | 1        | 0.29%   |
| ASUSTek Computer         | 1        | 0.29%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 130      | 36.31%  |
| Realtek RTL8125 2.5GbE Controller                                   | 35       | 9.78%   |
| Intel I211 Gigabit Network Connection                               | 31       | 8.66%   |
| Intel Ethernet Controller I225-V                                    | 29       | 8.1%    |
| Intel Ethernet Connection (2) I219-V                                | 13       | 3.63%   |
| Intel Ethernet Connection I217-LM                                   | 8        | 2.23%   |
| Intel Ethernet Connection (7) I219-V                                | 8        | 2.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 8        | 2.23%   |
| Intel Ethernet Connection (2) I218-V                                | 5        | 1.4%    |
| Intel 82579V Gigabit Network Connection                             | 5        | 1.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 4        | 1.12%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 4        | 1.12%   |
| Intel Ethernet Connection (7) I219-LM                               | 4        | 1.12%   |
| Intel Ethernet Connection (2) I219-LM                               | 4        | 1.12%   |
| Intel 82574L Gigabit Network Connection                             | 4        | 1.12%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 3        | 0.84%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 3        | 0.84%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 3        | 0.84%   |
| Intel Ethernet Connection I217-V                                    | 3        | 0.84%   |
| Intel 82583V Gigabit Network Connection                             | 3        | 0.84%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3        | 0.84%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                | 2        | 0.56%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                     | 2        | 0.56%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                          | 2        | 0.56%   |
| Realtek Killer E3000 2.5GbE Controller                              | 2        | 0.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 2        | 0.56%   |
| Nvidia MCP61 Ethernet                                               | 2        | 0.56%   |
| Intel I210 Gigabit Network Connection                               | 2        | 0.56%   |
| Intel Ethernet Connection (11) I219-V                               | 2        | 0.56%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 2        | 0.56%   |
| Intel 82566DM-2 Gigabit Network Connection                          | 2        | 0.56%   |
| ASIX AX88179 Gigabit Ethernet                                       | 2        | 0.56%   |
| Apple iPad 4/Mini1                                                  | 2        | 0.56%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 1        | 0.28%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 1        | 0.28%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 1        | 0.28%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                            | 1        | 0.28%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet      | 1        | 0.28%   |
| QNAP System Pacific                                                 | 1        | 0.28%   |
| Nvidia MCP55 Ethernet                                               | 1        | 0.28%   |
| Nvidia CK804 Ethernet Controller                                    | 1        | 0.28%   |
| Mellanox MT27500 Family [ConnectX-3]                                | 1        | 0.28%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller             | 1        | 0.28%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller             | 1        | 0.28%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                   | 1        | 0.28%   |
| Lenovo ThinkPad TBT 3 Dock                                          | 1        | 0.28%   |
| Intel Ethernet Connection (5) I219-LM                               | 1        | 0.28%   |
| Intel Ethernet Connection (14) I219-V                               | 1        | 0.28%   |
| Intel Ethernet Connection (14) I219-LM                              | 1        | 0.28%   |
| Intel 82578DM Gigabit Network Connection                            | 1        | 0.28%   |
| Intel 82578DC Gigabit Network Connection                            | 1        | 0.28%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                | 1        | 0.28%   |
| Intel 82546EB Gigabit Ethernet Controller (Copper)                  | 1        | 0.28%   |
| Google Nexus/Pixel Device (tether)                                  | 1        | 0.28%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                     | 1        | 0.28%   |
| ASUS Zenfone GO (ZB500KL) (Debug, RNDIS mode)                       | 1        | 0.28%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 1        | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 308      | 63.51%  |
| WiFi     | 172      | 35.46%  |
| Modem    | 4        | 0.82%   |
| Unknown  | 1        | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 233      | 71.69%  |
| WiFi     | 92       | 28.31%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 167      | 53.35%  |
| 2     | 124      | 39.62%  |
| 3     | 20       | 6.39%   |
| 4     | 1        | 0.32%   |
| 0     | 1        | 0.32%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 222      | 70.7%   |
| Yes  | 92       | 29.3%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 87       | 57.62%  |
| Cambridge Silicon Radio         | 23       | 15.23%  |
| Realtek Semiconductor           | 14       | 9.27%   |
| ASUSTek Computer                | 10       | 6.62%   |
| MediaTek                        | 5        | 3.31%   |
| TP-Link                         | 3        | 1.99%   |
| Qualcomm Atheros Communications | 3        | 1.99%   |
| Apple                           | 3        | 1.99%   |
| IMC Networks                    | 1        | 0.66%   |
| HTC (High Tech Computer)        | 1        | 0.66%   |
| Broadcom                        | 1        | 0.66%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 41       | 27.15%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 23       | 15.23%  |
| Intel Bluetooth wireless interface                                   | 12       | 7.95%   |
| Intel AX210 Bluetooth                                                | 11       | 7.28%   |
| Realtek Bluetooth Radio                                              | 10       | 6.62%   |
| Intel AX201 Bluetooth                                                | 9        | 5.96%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 7        | 4.64%   |
| MediaTek Wireless_Device                                             | 5        | 3.31%   |
| ASUS ASUS USB-BT500                                                  | 4        | 2.65%   |
| TP-Link TP-hink UB500 Adapter                                        | 3        | 1.99%   |
| Intel Bluetooth Device                                               | 3        | 1.99%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 3        | 1.99%   |
| ASUS Bluetooth Radio                                                 | 3        | 1.99%   |
| Apple Bluetooth USB Host Controller                                  | 3        | 1.99%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 2        | 1.32%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 2        | 1.32%   |
| Realtek RTL8821A Bluetooth                                           | 1        | 0.66%   |
| Realtek Bluetooth 5.1 Radio                                          | 1        | 0.66%   |
| Qualcomm Atheros  Bluetooth Device                                   | 1        | 0.66%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 1        | 0.66%   |
| IMC Networks Bluetooth Radio                                         | 1        | 0.66%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 0.66%   |
| Broadcom Bluetooth 2.0+eDR dongle                                    | 1        | 0.66%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 1        | 0.66%   |
| ASUS Bluetooth Adapter                                               | 1        | 0.66%   |
| ASUS BCM20702A0                                                      | 1        | 0.66%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| AMD                         | 178      | 28.94%  |
| Intel                       | 163      | 26.5%   |
| Nvidia                      | 132      | 21.46%  |
| C-Media Electronics         | 18       | 2.93%   |
| Logitech                    | 11       | 1.79%   |
| Creative Labs               | 7        | 1.14%   |
| Corsair                     | 7        | 1.14%   |
| Texas Instruments           | 6        | 0.98%   |
| Plantronics                 | 5        | 0.81%   |
| Kingston Technology         | 5        | 0.81%   |
| Creative Technology         | 5        | 0.81%   |
| XMOS                        | 4        | 0.65%   |
| SteelSeries ApS             | 4        | 0.65%   |
| JMTek                       | 4        | 0.65%   |
| Focusrite-Novation          | 4        | 0.65%   |
| Blue Microphones            | 4        | 0.65%   |
| Razer USA                   | 3        | 0.49%   |
| GN Netcom                   | 3        | 0.49%   |
| Generalplus Technology      | 3        | 0.49%   |
| Tenx Technology             | 2        | 0.33%   |
| Sony                        | 2        | 0.33%   |
| Schiit Audio                | 2        | 0.33%   |
| Samson Technologies         | 2        | 0.33%   |
| Native Instruments          | 2        | 0.33%   |
| Micro Star International    | 2        | 0.33%   |
| Lenovo                      | 2        | 0.33%   |
| FiiO Electronics Technology | 2        | 0.33%   |
| Yamaha                      | 1        | 0.16%   |
| VIA Technologies            | 1        | 0.16%   |
| USB PnP Sound Device        | 1        | 0.16%   |
| USB MICROPHONE              | 1        | 0.16%   |
| Turtle Beach                | 1        | 0.16%   |
| Trust                       | 1        | 0.16%   |
| TerraTec Electronic         | 1        | 0.16%   |
| Samsung Electronics         | 1        | 0.16%   |
| RODE Microphones            | 1        | 0.16%   |
| ROCCAT                      | 1        | 0.16%   |
| Realtek Semiconductor       | 1        | 0.16%   |
| Microdia                    | 1        | 0.16%   |
| M-Audio                     | 1        | 0.16%   |
| KORG                        | 1        | 0.16%   |
| iRiver                      | 1        | 0.16%   |
| Hangzhou Worlde             | 1        | 0.16%   |
| GYROCOM C&C                 | 1        | 0.16%   |
| Goldvish                    | 1        | 0.16%   |
| Giga-Byte Technology        | 1        | 0.16%   |
| FIFINE Microphones          | 1        | 0.16%   |
| FIFINE 683 Microphone       | 1        | 0.16%   |
| Elgato Systems              | 1        | 0.16%   |
| DSEA A/S                    | 1        | 0.16%   |
| Dell                        | 1        | 0.16%   |
| DCMT Technology             | 1        | 0.16%   |
| Cambridge Silicon Radio     | 1        | 0.16%   |
| BY EDIFIER                  | 1        | 0.16%   |
| Bose                        | 1        | 0.16%   |
| Barco Display Systems       | 1        | 0.16%   |
| ASUSTek Computer            | 1        | 0.16%   |
| Astro Gaming                | 1        | 0.16%   |
| AGPTek                      | 1        | 0.16%   |
| A4Tech                      | 1        | 0.16%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 65       | 8.93%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 32       | 4.4%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 25       | 3.43%   |
| AMD Family 17h/19h HD Audio Controller                                     | 22       | 3.02%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 22       | 3.02%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 22       | 3.02%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 21       | 2.88%   |
| Intel 200 Series PCH HD Audio                                              | 17       | 2.34%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 17       | 2.34%   |
| Nvidia GP107GL High Definition Audio Controller                            | 16       | 2.2%    |
| Intel Alder Lake-S HD Audio Controller                                     | 14       | 1.92%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 14       | 1.92%   |
| Intel Cannon Lake PCH cAVS                                                 | 13       | 1.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 13       | 1.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 12       | 1.65%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 12       | 1.65%   |
| AMD Navi 10 HDMI Audio                                                     | 12       | 1.65%   |
| Nvidia TU116 High Definition Audio Controller                              | 10       | 1.37%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 10       | 1.37%   |
| Nvidia GP106 High Definition Audio Controller                              | 9        | 1.24%   |
| Nvidia GM206 High Definition Audio Controller                              | 9        | 1.24%   |
| Nvidia GA104 High Definition Audio Controller                              | 9        | 1.24%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 8        | 1.1%    |
| Nvidia GM204 High Definition Audio Controller                              | 7        | 0.96%   |
| Intel Comet Lake PCH cAVS                                                  | 7        | 0.96%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 7        | 0.96%   |
| Nvidia TU106 High Definition Audio Controller                              | 6        | 0.82%   |
| Nvidia GP104 High Definition Audio Controller                              | 6        | 0.82%   |
| Nvidia GA102 High Definition Audio Controller                              | 6        | 0.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6        | 0.82%   |
| C-Media Electronics USB Audio Device                                       | 6        | 0.82%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 6        | 0.82%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 6        | 0.82%   |
| AMD FCH Azalia Controller                                                  | 6        | 0.82%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 5        | 0.69%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 5        | 0.69%   |
| Nvidia GK104 HDMI Audio Controller                                         | 5        | 0.69%   |
| Intel Comet Lake PCH-V cAVS                                                | 5        | 0.69%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4        | 0.55%   |
| Nvidia TU104 HD Audio Controller                                           | 4        | 0.55%   |
| Nvidia GP108 High Definition Audio Controller                              | 4        | 0.55%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4        | 0.55%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 4        | 0.55%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                         | 4        | 0.55%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4        | 0.55%   |
| Texas Instruments PCM2902 Audio Codec                                      | 3        | 0.41%   |
| Nvidia High Definition Audio Controller                                    | 3        | 0.41%   |
| Nvidia GF119 HDMI Audio Controller                                         | 3        | 0.41%   |
| Nvidia GF108 High Definition Audio Controller                              | 3        | 0.41%   |
| Nvidia GA106 High Definition Audio Controller                              | 3        | 0.41%   |
| JMTek USB PnP Audio Device                                                 | 3        | 0.41%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 3        | 0.41%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 3        | 0.41%   |
| Intel Audio device                                                         | 3        | 0.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3        | 0.41%   |
| Generalplus Technology USB Audio Device                                    | 3        | 0.41%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 3        | 0.41%   |
| Blue Microphones Yeti Stereo Microphone                                    | 3        | 0.41%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 3        | 0.41%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 3        | 0.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 31       | 20.26%  |
| G.Skill             | 23       | 15.03%  |
| Corsair             | 20       | 13.07%  |
| Unknown             | 17       | 11.11%  |
| Crucial             | 15       | 9.8%    |
| SK hynix            | 11       | 7.19%   |
| Samsung Electronics | 10       | 6.54%   |
| Micron Technology   | 7        | 4.58%   |
| Unknown             | 3        | 1.96%   |
| Patriot             | 2        | 1.31%   |
| A-DATA Technology   | 2        | 1.31%   |
| V-GeN               | 1        | 0.65%   |
| Team                | 1        | 0.65%   |
| Smart               | 1        | 0.65%   |
| Silicon Power       | 1        | 0.65%   |
| Samsung 1           | 1        | 0.65%   |
| PUSKILL             | 1        | 0.65%   |
| PNY                 | 1        | 0.65%   |
| Nanya Technology    | 1        | 0.65%   |
| Mushkin             | 1        | 0.65%   |
| Goodram             | 1        | 0.65%   |
| AMD                 | 1        | 0.65%   |
| A-TECH              | 1        | 0.65%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s     | 4        | 2.47%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s        | 3        | 1.85%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s    | 3        | 1.85%   |
| Unknown                                                  | 3        | 1.85%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                     | 2        | 1.23%   |
| Unknown RAM Module 4GB DIMM 400MT/s                      | 2        | 1.23%   |
| Unknown RAM Module 2GB DIMM 800MT/s                      | 2        | 1.23%   |
| Unknown RAM Module 2GB DIMM 667MT/s                      | 2        | 1.23%   |
| Unknown RAM Module 2GB DIMM 400MT/s                      | 2        | 1.23%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s     | 2        | 1.23%   |
| Samsung RAM M378A1K43EB2-CWE 8GB DIMM DDR4 3200MT/s      | 2        | 1.23%   |
| Micron RAM 16ATF1G64AZ-2G1B1 8GB DIMM DDR4 2133MT/s      | 2        | 1.23%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s   | 2        | 1.23%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s        | 2        | 1.23%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s      | 2        | 1.23%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s    | 2        | 1.23%   |
| G.Skill RAM F4-3200C14-8GTZR 8GB DIMM DDR4 3200MT/s      | 2        | 1.23%   |
| G.Skill RAM F3-14900CL9-4GBSR 4GB DIMM DDR3 1867MT/s     | 2        | 1.23%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 2        | 1.23%   |
| V-GeN RAM D4H8GL32A8TS 8GB DIMM DDR4 3200MT/s            | 1        | 0.62%   |
| Unknown RAM Module 8GB DIMM DDR3 1066MT/s                | 1        | 0.62%   |
| Unknown RAM Module 4GB DIMM 800MT/s                      | 1        | 0.62%   |
| Unknown RAM Module 4GB DIMM                              | 1        | 0.62%   |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s                | 1        | 0.62%   |
| Unknown RAM Module 2GB DIMM DDR2                         | 1        | 0.62%   |
| Unknown RAM Module 2GB DIMM                              | 1        | 0.62%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                 | 1        | 0.62%   |
| Unknown RAM Module 1GB DIMM DDR 333MT/s                  | 1        | 0.62%   |
| Unknown RAM 3460-1664 8GB DIMM DDR3 1600MT/s             | 1        | 0.62%   |
| Unknown RAM 1866 CL10 Ser 8192MB DIMM DDR3 800MT/s       | 1        | 0.62%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s       | 1        | 0.62%   |
| Smart RAM SH5641G8FH8N6TNSQG 8GB DIMM DDR3 1600MT/s      | 1        | 0.62%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s               | 1        | 0.62%   |
| SK hynix RAM Module 16GB DIMM DDR4 2667MT/s              | 1        | 0.62%   |
| SK hynix RAM HMT451U6BFR8C-PB 4096MB DIMM DDR3 1600MT/s  | 1        | 0.62%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 1        | 0.62%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s     | 1        | 0.62%   |
| SK hynix RAM HMA82GR7AFR4N-UH 16GB RIMM DDR4 2133MT/s    | 1        | 0.62%   |
| SK hynix RAM HMA81GU6DJR8N-XN 8GB DIMM DDR4 3200MT/s     | 1        | 0.62%   |
| SK hynix RAM HMA81GR7CJR8N-WM 8GB DIMM DDR4 2933MT/s     | 1        | 0.62%   |
| SK hynix RAM HMA451R7MFR8N-TF 4GB RIMM 2133MT/s          | 1        | 0.62%   |
| Silicon Power RAM Module 8GB DIMM DDR4 3200MT/s          | 1        | 0.62%   |
| Samsung RAM Module 32GB DIMM DDR4 3200MT/s               | 1        | 0.62%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s    | 1        | 0.62%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s | 1        | 0.62%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s      | 1        | 0.62%   |
| Samsung RAM M378A4G43MB1-CTD 32GB DIMM DDR4 3466MT/s     | 1        | 0.62%   |
| Samsung RAM M378A2G43MX3-CTD 16GB DIMM DDR4 3466MT/s     | 1        | 0.62%   |
| Samsung RAM M378A1K43BB1-CPB 8192MB DIMM DDR4 2733MT/s   | 1        | 0.62%   |
| Samsung RAM M378A1G43DB0-CPB 8GB DIMM DDR4 2133MT/s      | 1        | 0.62%   |
| Samsung RAM M3 78T5663QZ3-CF7 2GB DIMM DDR2 1639MT/s     | 1        | 0.62%   |
| Samsung 1 RAM M378B1G73BH0-CK0 8GB DIMM DDR3 1600MT/s    | 1        | 0.62%   |
| PUSKILL RAM PJ16TFK512M8 8GB DIMM DDR3                   | 1        | 0.62%   |
| PNY RAM 8GBF1X08RHJJ40-135-K 8GB DIMM DDR4 3000MT/s      | 1        | 0.62%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s       | 1        | 0.62%   |
| Patriot RAM 2666 C16 Series 16384MB DIMM DDR4 2667MT/s   | 1        | 0.62%   |
| Nanya RAM NT2GC64B8HA0NF-CG 2GB DIMM DDR3 1333MT/s       | 1        | 0.62%   |
| Mushkin RAM MR[A/B]4U266GHHF8G 8GB DIMM DDR4 2133MT/s    | 1        | 0.62%   |
| Micron RAM 9ASF51272PZ-2G1A2 4096MB RIMM DDR4 2133MT/s   | 1        | 0.62%   |
| Micron RAM 8KTF51264AZ-1G6E1 4096MB DIMM DDR3 1600MT/s   | 1        | 0.62%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 81       | 60%     |
| DDR3    | 35       | 25.93%  |
| Unknown | 13       | 9.63%   |
| DDR2    | 4        | 2.96%   |
| SDRAM   | 1        | 0.74%   |
| DDR     | 1        | 0.74%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 127      | 95.49%  |
| SODIMM | 4        | 3.01%   |
| RIMM   | 2        | 1.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 62       | 43.36%  |
| 16384 | 30       | 20.98%  |
| 4096  | 24       | 16.78%  |
| 2048  | 15       | 10.49%  |
| 32768 | 8        | 5.59%   |
| 1024  | 4        | 2.8%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 27       | 18.75%  |
| 3200    | 26       | 18.06%  |
| 3600    | 15       | 10.42%  |
| 2133    | 14       | 9.72%   |
| 2667    | 6        | 4.17%   |
| 1333    | 5        | 3.47%   |
| 3466    | 4        | 2.78%   |
| 2933    | 4        | 2.78%   |
| 1867    | 4        | 2.78%   |
| 667     | 4        | 2.78%   |
| 3000    | 3        | 2.08%   |
| 800     | 3        | 2.08%   |
| 400     | 3        | 2.08%   |
| 3866    | 2        | 1.39%   |
| 3733    | 2        | 1.39%   |
| 3400    | 2        | 1.39%   |
| 2800    | 2        | 1.39%   |
| 2666    | 2        | 1.39%   |
| 2400    | 2        | 1.39%   |
| Unknown | 2        | 1.39%   |
| 5200    | 1        | 0.69%   |
| 4800    | 1        | 0.69%   |
| 3467    | 1        | 0.69%   |
| 3333    | 1        | 0.69%   |
| 2733    | 1        | 0.69%   |
| 2600    | 1        | 0.69%   |
| 2048    | 1        | 0.69%   |
| 1639    | 1        | 0.69%   |
| 1067    | 1        | 0.69%   |
| 1066    | 1        | 0.69%   |
| 333     | 1        | 0.69%   |
| 200     | 1        | 0.69%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 4        | 40%     |
| Brother Industries  | 2        | 20%     |
| Samsung Electronics | 1        | 10%     |
| Prolific Technology | 1        | 10%     |
| Kyocera             | 1        | 10%     |
| Graphtec America    | 1        | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Samsung M2070 Series              | 1        | 10%     |
| Prolific PL2305 Parallel Port     | 1        | 10%     |
| Kyocera ECOSYS M5521cdw           | 1        | 10%     |
| HP Neverstop Laser 100x           | 1        | 10%     |
| HP Ink Tank 310 series            | 1        | 10%     |
| HP DeskJet 3700 series            | 1        | 10%     |
| HP DeskJet 3630 series            | 1        | 10%     |
| Graphtec America Graphtec Printer | 1        | 10%     |
| Brother Printer                   | 1        | 10%     |
| Brother DCP-T510W                 | 1        | 10%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Canon       | 4        | 80%     |
| Seiko Epson | 1        | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Canon CanoScan LiDE 100               | 2        | 40%     |
| Seiko Epson GT-X770 [Perfection V500] | 1        | 20%     |
| Canon CanoScan LiDE 220               | 1        | 20%     |
| Canon CanoScan LiDE 200               | 1        | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 34       | 45.95%  |
| Sunplus Innovation Technology | 9        | 12.16%  |
| Microsoft                     | 7        | 9.46%   |
| Realtek Semiconductor         | 3        | 4.05%   |
| Lenovo                        | 3        | 4.05%   |
| KYE Systems (Mouse Systems)   | 3        | 4.05%   |
| Apple                         | 3        | 4.05%   |
| Microdia                      | 2        | 2.7%    |
| Hewlett-Packard               | 2        | 2.7%    |
| Creative Technology           | 2        | 2.7%    |
| Asuscom Network               | 2        | 2.7%    |
| Jieli Technology              | 1        | 1.35%   |
| Intel                         | 1        | 1.35%   |
| FPL-2053-191010               | 1        | 1.35%   |
| Aveo Technology               | 1        | 1.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Desktops | Percent |
|--------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                      | 13       | 17.33%  |
| Sunplus HD 720P webcam                           | 4        | 5.33%   |
| Logitech Webcam C270                             | 3        | 4%      |
| Logitech C920 PRO HD Webcam                      | 3        | 4%      |
| Apple iPhone 5/5C/5S/6/SE                        | 3        | 4%      |
| Realtek NYK NEMESIS                              | 2        | 2.67%   |
| Microsoft LifeCam HD-3000                        | 2        | 2.67%   |
| Microsoft LifeCam Cinema                         | 2        | 2.67%   |
| Logitech Webcam C310                             | 2        | 2.67%   |
| Logitech HD Webcam C615                          | 2        | 2.67%   |
| Logitech HD Webcam C525                          | 2        | 2.67%   |
| Logitech C922 Pro Stream Webcam                  | 2        | 2.67%   |
| Logitech BRIO Ultra HD Webcam                    | 2        | 2.67%   |
| KYE Systems (Mouse Systems) AUKEY PC-LM1E Camera | 2        | 2.67%   |
| Asuscom Network REDRAGON Live Camera             | 2        | 2.67%   |
| Sunplus Lihappe8 Webcam L0485A2SP                | 1        | 1.33%   |
| Sunplus Integrated_Webcam_HD                     | 1        | 1.33%   |
| Sunplus Full HD webcam                           | 1        | 1.33%   |
| Sunplus ezcap U3 capture-04                      | 1        | 1.33%   |
| Sunplus Aukey-PC-LM1E Camera                     | 1        | 1.33%   |
| Realtek Thronmax Webcam Mic                      | 1        | 1.33%   |
| Realtek Thronmax StreamGo Webcam                 | 1        | 1.33%   |
| Microsoft Xbox NUI Camera                        | 1        | 1.33%   |
| Microsoft LifeCam VX-5000                        | 1        | 1.33%   |
| Microsoft LifeCam VX-500 [1357]                  | 1        | 1.33%   |
| Microdia USB 2.0 Camera                          | 1        | 1.33%   |
| Microdia HDP Webcam USB                          | 1        | 1.33%   |
| Logitech Webcam C200                             | 1        | 1.33%   |
| Logitech Webcam B500                             | 1        | 1.33%   |
| Logitech QuickCam Pro 9000                       | 1        | 1.33%   |
| Logitech QuickCam Communicate Deluxe             | 1        | 1.33%   |
| Logitech B525 HD Webcam                          | 1        | 1.33%   |
| Lenovo FULL HD 1080P Webcam                      | 1        | 1.33%   |
| Lenovo FHD Webcam Audio                          | 1        | 1.33%   |
| Lenovo 500 RGB Camera                            | 1        | 1.33%   |
| KYE Systems (Mouse Systems) FaceCam 1000X        | 1        | 1.33%   |
| Jieli USB PHY 2.0                                | 1        | 1.33%   |
| Intel RealSense 3D Camera (Front F200)           | 1        | 1.33%   |
| HP Webcam HD 2300                                | 1        | 1.33%   |
| HP HD-4110 Webcam                                | 1        | 1.33%   |
| FPL-2053-191010 T2 Webcam                        | 1        | 1.33%   |
| Creative Live! Cam Sync 1080p V2                 | 1        | 1.33%   |
| Creative Live! Cam Sync 1080p                    | 1        | 1.33%   |
| Aveo USB2.0 UVC PC Camera                        | 1        | 1.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| DigitalPersona | 2        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| DigitalPersona Fingerprint Reader | 2        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| SCM Microsystems      | 1        | 33.33%  |
| Realtek Semiconductor | 1        | 33.33%  |
| OmniKey               | 1        | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1        | 33.33%  |
| Realtek Semiconductor Smart Card Reader Interface      | 1        | 33.33%  |
| OmniKey CardMan 1021                                   | 1        | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 260      | 83.33%  |
| 1     | 42       | 13.46%  |
| 2     | 8        | 2.56%   |
| 4     | 1        | 0.32%   |
| 3     | 1        | 0.32%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 21       | 36.21%  |
| Graphics card            | 16       | 27.59%  |
| Multimedia controller    | 5        | 8.62%   |
| Unassigned class         | 4        | 6.9%    |
| Sound                    | 3        | 5.17%   |
| Modem                    | 2        | 3.45%   |
| Fingerprint reader       | 2        | 3.45%   |
| Wireless                 | 1        | 1.72%   |
| Firewire controller      | 1        | 1.72%   |
| Communication controller | 1        | 1.72%   |
| Camera                   | 1        | 1.72%   |
| Bluetooth                | 1        | 1.72%   |

