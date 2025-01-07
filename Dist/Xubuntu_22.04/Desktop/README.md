Xubuntu 22.04 - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for Xubuntu 22.04.

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

Total: 450

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | M5A78L-M LX PLUS            | [83a10df0af](https://linux-hardware.org/?probe=83a10df0af) | Dec 16, 2024 |
| Gigabyte      | H110M-S2-CF                 | [61e673309f](https://linux-hardware.org/?probe=61e673309f) | Nov 27, 2024 |
| Gigabyte      | H110M-S2-CF                 | [0d40b44d15](https://linux-hardware.org/?probe=0d40b44d15) | Nov 27, 2024 |
| Pegatron      | 2AC2                        | [24efcbf074](https://linux-hardware.org/?probe=24efcbf074) | Nov 23, 2024 |
| Dell          | 051FJ8 A02                  | [66b7975345](https://linux-hardware.org/?probe=66b7975345) | Nov 20, 2024 |
| Gigabyte      | B660M DS3H DDR4             | [07bf1053a6](https://linux-hardware.org/?probe=07bf1053a6) | Nov 12, 2024 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [09bd105ca4](https://linux-hardware.org/?probe=09bd105ca4) | Nov 09, 2024 |
| HP            | 3029h                       | [83bfbe4bbe](https://linux-hardware.org/?probe=83bfbe4bbe) | Oct 28, 2024 |
| ASRock        | Z370 Pro4                   | [8be5788f0f](https://linux-hardware.org/?probe=8be5788f0f) | Oct 14, 2024 |
| ASUSTek       | P5E                         | [cdbc95990e](https://linux-hardware.org/?probe=cdbc95990e) | Oct 11, 2024 |
| Dell          | 0RY007                      | [aef3641a97](https://linux-hardware.org/?probe=aef3641a97) | Oct 03, 2024 |
| ASRock        | H510 Pro BTC+               | [a1ae1e84a3](https://linux-hardware.org/?probe=a1ae1e84a3) | Sep 18, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [12bdde9ebc](https://linux-hardware.org/?probe=12bdde9ebc) | Sep 11, 2024 |
| Gigabyte      | Z87-HD3                     | [5ce754d8ac](https://linux-hardware.org/?probe=5ce754d8ac) | Sep 08, 2024 |
| Unknown       | Unknown                     | [76a130d405](https://linux-hardware.org/?probe=76a130d405) | Sep 07, 2024 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [f896396077](https://linux-hardware.org/?probe=f896396077) | Sep 04, 2024 |
| Packard Be... | IMEDIA S2185                | [2881d2dd1c](https://linux-hardware.org/?probe=2881d2dd1c) | Sep 04, 2024 |
| MSI           | H81M-P33                    | [e042807dc2](https://linux-hardware.org/?probe=e042807dc2) | Sep 01, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [89910d636e](https://linux-hardware.org/?probe=89910d636e) | Aug 31, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [af2f92a36b](https://linux-hardware.org/?probe=af2f92a36b) | Aug 31, 2024 |
| MSI           | A520M-A PRO                 | [bea9bcf4a7](https://linux-hardware.org/?probe=bea9bcf4a7) | Aug 29, 2024 |
| Biostar       | B350ET2                     | [435502bdae](https://linux-hardware.org/?probe=435502bdae) | Aug 17, 2024 |
| Biostar       | B350ET2                     | [1c9548b133](https://linux-hardware.org/?probe=1c9548b133) | Aug 17, 2024 |
| Gigabyte      | F2A88XM-D3H                 | [326191891a](https://linux-hardware.org/?probe=326191891a) | Aug 17, 2024 |
| ASUSTek       | H87-PRO                     | [2df8b23618](https://linux-hardware.org/?probe=2df8b23618) | Aug 15, 2024 |
| MSI           | Z77A-G41                    | [85eb1d0f02](https://linux-hardware.org/?probe=85eb1d0f02) | Aug 09, 2024 |
| HP            | 1790                        | [8104bc2455](https://linux-hardware.org/?probe=8104bc2455) | Aug 03, 2024 |
| ASRock        | N68-S3 UCC                  | [cc2c1f8fd5](https://linux-hardware.org/?probe=cc2c1f8fd5) | Jul 27, 2024 |
| ASRock        | B550 Phantom Gaming 4       | [475f183aa6](https://linux-hardware.org/?probe=475f183aa6) | Jul 27, 2024 |
| ASRock        | N68-S3 UCC                  | [ebee0b577f](https://linux-hardware.org/?probe=ebee0b577f) | Jul 23, 2024 |
| Dell          | 0F5C5X A00                  | [006ce103a9](https://linux-hardware.org/?probe=006ce103a9) | Jul 18, 2024 |
| ASUSTek       | M2N68-AM SE2                | [54c2bc8ab6](https://linux-hardware.org/?probe=54c2bc8ab6) | Jul 17, 2024 |
| ASUSTek       | ROG STRIX B760-I GAMING ... | [75dbf5b437](https://linux-hardware.org/?probe=75dbf5b437) | Jul 16, 2024 |
| Dell          | 0XKH0D A02                  | [0781f0c28d](https://linux-hardware.org/?probe=0781f0c28d) | Jul 12, 2024 |
| Dell          | 0XKH0D A02                  | [c2611748dd](https://linux-hardware.org/?probe=c2611748dd) | Jul 12, 2024 |
| Gigabyte      | B550M K                     | [ea2aa30897](https://linux-hardware.org/?probe=ea2aa30897) | Jul 11, 2024 |
| Gigabyte      | B85-HD3                     | [ce9e0e79fb](https://linux-hardware.org/?probe=ce9e0e79fb) | Jul 10, 2024 |
| HP            | 3029h                       | [5be522cd78](https://linux-hardware.org/?probe=5be522cd78) | Jun 28, 2024 |
| Dell          | 088DT1 A00                  | [63c22aab38](https://linux-hardware.org/?probe=63c22aab38) | Jun 22, 2024 |
| MSI           | MS-B1831                    | [8e56f848ac](https://linux-hardware.org/?probe=8e56f848ac) | Jun 16, 2024 |
| HP            | 8643 SMVB                   | [21b770ac23](https://linux-hardware.org/?probe=21b770ac23) | Jun 15, 2024 |
| ASUSTek       | H110M-PLUS                  | [a13acdf786](https://linux-hardware.org/?probe=a13acdf786) | Jun 14, 2024 |
| ASUSTek       | H110M-PLUS                  | [fffccdaea1](https://linux-hardware.org/?probe=fffccdaea1) | Jun 14, 2024 |
| ASUSTek       | ROG ZENITH EXTREME          | [23f82615a3](https://linux-hardware.org/?probe=23f82615a3) | Jun 12, 2024 |
| Dell          | 0M3F6C A01                  | [d9355d53f8](https://linux-hardware.org/?probe=d9355d53f8) | Jun 07, 2024 |
| ASUSTek       | M51AC                       | [8b39e8a250](https://linux-hardware.org/?probe=8b39e8a250) | Jun 06, 2024 |
| ASUSTek       | ET1612I                     | [589954115c](https://linux-hardware.org/?probe=589954115c) | Jun 03, 2024 |
| Dell          | 0FM586                      | [480574c2be](https://linux-hardware.org/?probe=480574c2be) | Jun 03, 2024 |
| Dell          | 0FM586                      | [c192f1ab3d](https://linux-hardware.org/?probe=c192f1ab3d) | May 30, 2024 |
| ASUSTek       | PRIME B550-PLUS             | [4fb3692ff1](https://linux-hardware.org/?probe=4fb3692ff1) | May 27, 2024 |
| Dell          | 0CRH6C A01                  | [9d92d084e8](https://linux-hardware.org/?probe=9d92d084e8) | May 27, 2024 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [2851cf1093](https://linux-hardware.org/?probe=2851cf1093) | May 17, 2024 |
| Dell          | 088DT1 A00                  | [5fdb3e7792](https://linux-hardware.org/?probe=5fdb3e7792) | May 15, 2024 |
| Dell          | 088DT1 A00                  | [edb955bd5e](https://linux-hardware.org/?probe=edb955bd5e) | May 07, 2024 |
| Dell          | 0N867P A02                  | [7b2f6946b9](https://linux-hardware.org/?probe=7b2f6946b9) | May 01, 2024 |
| Gigabyte      | H110M-S2-CF                 | [e55bcf23cf](https://linux-hardware.org/?probe=e55bcf23cf) | Apr 30, 2024 |
| AZW           | EQ                          | [dc09b0ecbc](https://linux-hardware.org/?probe=dc09b0ecbc) | Apr 29, 2024 |
| AZW           | EQ                          | [9e4f615d36](https://linux-hardware.org/?probe=9e4f615d36) | Apr 29, 2024 |
| Dell          | 0MN1TX A02                  | [2aa151f159](https://linux-hardware.org/?probe=2aa151f159) | Apr 20, 2024 |
| Dell          | 0MN1TX A02                  | [cfac7f54ed](https://linux-hardware.org/?probe=cfac7f54ed) | Apr 20, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [5e4c324298](https://linux-hardware.org/?probe=5e4c324298) | Apr 18, 2024 |
| Dell          | 0FF3FN A00                  | [b1bddc88aa](https://linux-hardware.org/?probe=b1bddc88aa) | Apr 15, 2024 |
| Dell          | 0WG864                      | [b430ed12b5](https://linux-hardware.org/?probe=b430ed12b5) | Apr 15, 2024 |
| ASRock        | A75M-HVS                    | [fc26a8b5fa](https://linux-hardware.org/?probe=fc26a8b5fa) | Apr 12, 2024 |
| Fujitsu       | FujitsuTP7000 -1            | [1d3918f13c](https://linux-hardware.org/?probe=1d3918f13c) | Apr 11, 2024 |
| Dell          | 0FF3FN A00                  | [979d51faa5](https://linux-hardware.org/?probe=979d51faa5) | Apr 10, 2024 |
| Shenzhen M... | F7BFD                       | [98e43e8de4](https://linux-hardware.org/?probe=98e43e8de4) | Apr 09, 2024 |
| Dell          | 02YYK5 A01                  | [cee98f0931](https://linux-hardware.org/?probe=cee98f0931) | Apr 09, 2024 |
| Dell          | 02YYK5 A01                  | [ed8a461ca7](https://linux-hardware.org/?probe=ed8a461ca7) | Apr 09, 2024 |
| Dell          | 088DT1 A00                  | [c11b83e86b](https://linux-hardware.org/?probe=c11b83e86b) | Apr 08, 2024 |
| Hardkernel    | ODROID-H2                   | [64075f354e](https://linux-hardware.org/?probe=64075f354e) | Apr 07, 2024 |
| Gigabyte      | M68M-S2P                    | [2711aee181](https://linux-hardware.org/?probe=2711aee181) | Apr 05, 2024 |
| MSI           | X58 Pro                     | [9b0fab5acc](https://linux-hardware.org/?probe=9b0fab5acc) | Apr 02, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [84ed1b3cc5](https://linux-hardware.org/?probe=84ed1b3cc5) | Apr 01, 2024 |
| ASUSTek       | PRIME A320M-K               | [0bd97f775d](https://linux-hardware.org/?probe=0bd97f775d) | Apr 01, 2024 |
| ASUSTek       | PRIME A320M-K               | [d952efad38](https://linux-hardware.org/?probe=d952efad38) | Apr 01, 2024 |
| MSI           | MPG X570S EDGE MAX WIFI     | [a09b8ab7cc](https://linux-hardware.org/?probe=a09b8ab7cc) | Mar 29, 2024 |
| ASUSTek       | PRIME A320M-K/BR            | [62ff739b8b](https://linux-hardware.org/?probe=62ff739b8b) | Mar 27, 2024 |
| ASUSTek       | PRIME A320M-K/BR            | [15137ac3a5](https://linux-hardware.org/?probe=15137ac3a5) | Mar 27, 2024 |
| MSI           | MPG X570S EDGE MAX WIFI     | [ee2674fe55](https://linux-hardware.org/?probe=ee2674fe55) | Mar 26, 2024 |
| Intel         | X99                         | [2479fc825c](https://linux-hardware.org/?probe=2479fc825c) | Mar 25, 2024 |
| Shenzhen M... | F7BFD                       | [64942ccf25](https://linux-hardware.org/?probe=64942ccf25) | Mar 24, 2024 |
| MACHINIST     | E5-MR9A V1.0                | [24cd2954c5](https://linux-hardware.org/?probe=24cd2954c5) | Mar 24, 2024 |
| ASUSTek       | PRIME A320M-K               | [052a56e30a](https://linux-hardware.org/?probe=052a56e30a) | Mar 23, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [e18375e687](https://linux-hardware.org/?probe=e18375e687) | Mar 23, 2024 |
| MSI           | 760GM-P21                   | [9ea00e6ebb](https://linux-hardware.org/?probe=9ea00e6ebb) | Mar 22, 2024 |
| Intel         | H81                         | [9faff0c332](https://linux-hardware.org/?probe=9faff0c332) | Mar 21, 2024 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [9df4721239](https://linux-hardware.org/?probe=9df4721239) | Mar 20, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [62f6992f05](https://linux-hardware.org/?probe=62f6992f05) | Mar 20, 2024 |
| ASUSTek       | M5A78L-M/USB3               | [aff15cce95](https://linux-hardware.org/?probe=aff15cce95) | Mar 17, 2024 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [8f589013b1](https://linux-hardware.org/?probe=8f589013b1) | Mar 15, 2024 |
| HP            | 2175                        | [f43124076c](https://linux-hardware.org/?probe=f43124076c) | Mar 14, 2024 |
| Dell          | 088DT1 A00                  | [8eb20f3ee6](https://linux-hardware.org/?probe=8eb20f3ee6) | Mar 12, 2024 |
| Dell          | 0J3C2F A02                  | [bebba9cf4a](https://linux-hardware.org/?probe=bebba9cf4a) | Mar 12, 2024 |
| Dell          | 0FF3FN A00                  | [78dd6f891e](https://linux-hardware.org/?probe=78dd6f891e) | Mar 11, 2024 |
| Dell          | 0VHXCD A03                  | [4ea894ca73](https://linux-hardware.org/?probe=4ea894ca73) | Mar 10, 2024 |
| HP            | 3397                        | [571ec29e07](https://linux-hardware.org/?probe=571ec29e07) | Mar 07, 2024 |
| HP            | 2129                        | [c06e16031f](https://linux-hardware.org/?probe=c06e16031f) | Mar 07, 2024 |
| HP            | 2129                        | [5f2414ecf8](https://linux-hardware.org/?probe=5f2414ecf8) | Mar 07, 2024 |
| HP            | 1998                        | [bd3e35eb3f](https://linux-hardware.org/?probe=bd3e35eb3f) | Mar 06, 2024 |
| ASUSTek       | P5Q-PRO                     | [4d165bc18c](https://linux-hardware.org/?probe=4d165bc18c) | Mar 05, 2024 |
| Gigabyte      | M61PME-S2P                  | [3a3676f133](https://linux-hardware.org/?probe=3a3676f133) | Mar 04, 2024 |
| Lenovo        | SHARKBAY NOK                | [abfba381b6](https://linux-hardware.org/?probe=abfba381b6) | Mar 02, 2024 |
| Lenovo        | SHARKBAY NOK                | [5d03e50172](https://linux-hardware.org/?probe=5d03e50172) | Mar 02, 2024 |
| HP            | 212A                        | [688db14d79](https://linux-hardware.org/?probe=688db14d79) | Feb 29, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [6b541baebc](https://linux-hardware.org/?probe=6b541baebc) | Feb 28, 2024 |
| ASUSTek       | Z170-K                      | [790bcad6c3](https://linux-hardware.org/?probe=790bcad6c3) | Feb 23, 2024 |
| Dell          | 088DT1 A00                  | [688b84c15c](https://linux-hardware.org/?probe=688b84c15c) | Feb 23, 2024 |
| Shenzhen M... | F7BFD                       | [ed5d36c89f](https://linux-hardware.org/?probe=ed5d36c89f) | Feb 22, 2024 |
| ASUSTek       | P6T SE                      | [19014495ef](https://linux-hardware.org/?probe=19014495ef) | Feb 18, 2024 |
| Dell          | 088DT1 A00                  | [1442765491](https://linux-hardware.org/?probe=1442765491) | Feb 17, 2024 |
| Dell          | 088DT1 A00                  | [90fc76d5f0](https://linux-hardware.org/?probe=90fc76d5f0) | Feb 17, 2024 |
| Intel         | DB75EN                      | [d2fb5b9c49](https://linux-hardware.org/?probe=d2fb5b9c49) | Feb 15, 2024 |
| Intel         | D54250WYK H13922-303        | [2c7d744bc7](https://linux-hardware.org/?probe=2c7d744bc7) | Feb 14, 2024 |
| Lenovo        | NOK                         | [ee3d0a6048](https://linux-hardware.org/?probe=ee3d0a6048) | Feb 11, 2024 |
| Lenovo        | NOK                         | [24ed0846b2](https://linux-hardware.org/?probe=24ed0846b2) | Feb 05, 2024 |
| Intel         | DB75EN                      | [0ec38bc63a](https://linux-hardware.org/?probe=0ec38bc63a) | Feb 04, 2024 |
| Fujitsu       | D2990-A1 S26361-D2990-A1    | [a87f78b559](https://linux-hardware.org/?probe=a87f78b559) | Feb 03, 2024 |
| Intel         | DB75EN                      | [41cea41d1e](https://linux-hardware.org/?probe=41cea41d1e) | Jan 26, 2024 |
| Dell          | 0K240Y A01                  | [fe08501f76](https://linux-hardware.org/?probe=fe08501f76) | Jan 24, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [d11d529522](https://linux-hardware.org/?probe=d11d529522) | Jan 23, 2024 |
| ASUSTek       | P8P67 DELUXE                | [545e0a6896](https://linux-hardware.org/?probe=545e0a6896) | Jan 23, 2024 |
| AOpen         | D2644 S26361-D2644          | [f45673bd59](https://linux-hardware.org/?probe=f45673bd59) | Jan 22, 2024 |
| ASUSTek       | TUF B450-PLUS GAMING        | [4254242157](https://linux-hardware.org/?probe=4254242157) | Jan 21, 2024 |
| Intel         | DB75EN                      | [f639799c41](https://linux-hardware.org/?probe=f639799c41) | Jan 21, 2024 |
| Dell          | 0F5C5X A00                  | [f320dddb34](https://linux-hardware.org/?probe=f320dddb34) | Jan 19, 2024 |
| ASUSTek       | H81M-C                      | [bcbb9c099f](https://linux-hardware.org/?probe=bcbb9c099f) | Jan 16, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [77032de9df](https://linux-hardware.org/?probe=77032de9df) | Jan 14, 2024 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | [b6d8783c20](https://linux-hardware.org/?probe=b6d8783c20) | Jan 12, 2024 |
| Dell          | 0T0MHW A03                  | [2ad439d95f](https://linux-hardware.org/?probe=2ad439d95f) | Jan 11, 2024 |
| MSI           | B550 GAMING GEN3            | [511526bcf7](https://linux-hardware.org/?probe=511526bcf7) | Jan 08, 2024 |
| Gigabyte      | P55-UD3R                    | [44658131d3](https://linux-hardware.org/?probe=44658131d3) | Jan 05, 2024 |
| Unknown       | Unknown                     | [1f73670f10](https://linux-hardware.org/?probe=1f73670f10) | Dec 27, 2023 |
| Intel         | DB75EN                      | [c2c820f0d9](https://linux-hardware.org/?probe=c2c820f0d9) | Dec 25, 2023 |
| Intel         | DB75EN                      | [6ec790f3fc](https://linux-hardware.org/?probe=6ec790f3fc) | Dec 24, 2023 |
| Gigabyte      | P35-DS3R                    | [741ad16651](https://linux-hardware.org/?probe=741ad16651) | Dec 22, 2023 |
| MSI           | X570-A PRO                  | [07a7762b25](https://linux-hardware.org/?probe=07a7762b25) | Dec 21, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [ee1a222677](https://linux-hardware.org/?probe=ee1a222677) | Dec 20, 2023 |
| HP            | 212B                        | [1ce8b8d929](https://linux-hardware.org/?probe=1ce8b8d929) | Dec 14, 2023 |
| Intel         | H310 Series                 | [9565b22822](https://linux-hardware.org/?probe=9565b22822) | Dec 13, 2023 |
| Lenovo        | NO DPK                      | [2204183295](https://linux-hardware.org/?probe=2204183295) | Dec 12, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [e223660e23](https://linux-hardware.org/?probe=e223660e23) | Dec 11, 2023 |
| ASUSTek       | PRIME H510M-A WIFI          | [ba43863b29](https://linux-hardware.org/?probe=ba43863b29) | Dec 09, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [74440ebfad](https://linux-hardware.org/?probe=74440ebfad) | Dec 07, 2023 |
| Intel         | DB75EN                      | [15f11719b5](https://linux-hardware.org/?probe=15f11719b5) | Dec 02, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [c8e6af0346](https://linux-hardware.org/?probe=c8e6af0346) | Nov 30, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [4b14c830c0](https://linux-hardware.org/?probe=4b14c830c0) | Nov 26, 2023 |
| MSI           | B250M PRO-VD                | [d3697eee2c](https://linux-hardware.org/?probe=d3697eee2c) | Nov 24, 2023 |
| Dell          | 0M5DCD A00                  | [78748bcf50](https://linux-hardware.org/?probe=78748bcf50) | Nov 24, 2023 |
| Intel         | DH55TC AAG26116-302         | [0edf2befff](https://linux-hardware.org/?probe=0edf2befff) | Nov 21, 2023 |
| Gigabyte      | H81M-DS2                    | [9701d268e8](https://linux-hardware.org/?probe=9701d268e8) | Nov 21, 2023 |
| HP            | 21B4 A01                    | [73a4740b8f](https://linux-hardware.org/?probe=73a4740b8f) | Nov 18, 2023 |
| Intel         | DH55TC AAG26116-302         | [8a23e4f586](https://linux-hardware.org/?probe=8a23e4f586) | Nov 16, 2023 |
| Intel         | DH55TC AAG26116-302         | [7fabbf9cb1](https://linux-hardware.org/?probe=7fabbf9cb1) | Nov 16, 2023 |
| ASRock        | Z590M-ITX/ax                | [238b7326f1](https://linux-hardware.org/?probe=238b7326f1) | Nov 10, 2023 |
| ASRock        | Z590M-ITX/ax                | [c1a263f3b5](https://linux-hardware.org/?probe=c1a263f3b5) | Nov 08, 2023 |
| ASUSTek       | P5K                         | [4870e13f93](https://linux-hardware.org/?probe=4870e13f93) | Nov 08, 2023 |
| Pegatron      | 2AF0                        | [d918aae63e](https://linux-hardware.org/?probe=d918aae63e) | Nov 06, 2023 |
| Pegatron      | 2AF0                        | [de892702f8](https://linux-hardware.org/?probe=de892702f8) | Nov 05, 2023 |
| Gigabyte      | B450M DS3H-CF               | [fefb7e12d2](https://linux-hardware.org/?probe=fefb7e12d2) | Nov 05, 2023 |
| Acer          | Aspire TC-885 V:1.1         | [a871f012a2](https://linux-hardware.org/?probe=a871f012a2) | Nov 02, 2023 |
| Gigabyte      | H77M-D3H                    | [1d3f58a610](https://linux-hardware.org/?probe=1d3f58a610) | Oct 25, 2023 |
| Dell          | 0XKH0D A02                  | [bba36c01cf](https://linux-hardware.org/?probe=bba36c01cf) | Oct 19, 2023 |
| MSI           | B550 GAMING GEN3            | [e657535210](https://linux-hardware.org/?probe=e657535210) | Oct 17, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d519c10989](https://linux-hardware.org/?probe=d519c10989) | Oct 16, 2023 |
| Unknown       | Unknown                     | [626c7e1591](https://linux-hardware.org/?probe=626c7e1591) | Oct 16, 2023 |
| HP            | 18E5                        | [d869fcd6dc](https://linux-hardware.org/?probe=d869fcd6dc) | Oct 16, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [18922baf01](https://linux-hardware.org/?probe=18922baf01) | Oct 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [430df05ea3](https://linux-hardware.org/?probe=430df05ea3) | Oct 14, 2023 |
| HP            | 339A                        | [188e7d023e](https://linux-hardware.org/?probe=188e7d023e) | Oct 14, 2023 |
| HP            | 18E5                        | [653e855c90](https://linux-hardware.org/?probe=653e855c90) | Oct 05, 2023 |
| MSI           | B550 GAMING GEN3            | [870556d425](https://linux-hardware.org/?probe=870556d425) | Oct 04, 2023 |
| HP            | 09F8h                       | [996f1179ba](https://linux-hardware.org/?probe=996f1179ba) | Oct 02, 2023 |
| ASUSTek       | P5Q SE2                     | [df644adbab](https://linux-hardware.org/?probe=df644adbab) | Oct 01, 2023 |
| ASUSTek       | P5Q SE2                     | [2ccade9ad8](https://linux-hardware.org/?probe=2ccade9ad8) | Oct 01, 2023 |
| HP            | 18E5                        | [1f3e02bd3e](https://linux-hardware.org/?probe=1f3e02bd3e) | Oct 01, 2023 |
| Medion        | B660M DS3H AX DDR4          | [1dbbeda8cd](https://linux-hardware.org/?probe=1dbbeda8cd) | Sep 30, 2023 |
| Medion        | B660M DS3H AX DDR4          | [57a42b9ccf](https://linux-hardware.org/?probe=57a42b9ccf) | Sep 30, 2023 |
| Dell          | 0YJPT1 A00                  | [27b01f468d](https://linux-hardware.org/?probe=27b01f468d) | Sep 30, 2023 |
| Lenovo        | NOK                         | [95ba956749](https://linux-hardware.org/?probe=95ba956749) | Sep 28, 2023 |
| Gigabyte      | EX58-UD5                    | [060deb4c88](https://linux-hardware.org/?probe=060deb4c88) | Sep 26, 2023 |
| ASUSTek       | M5A97 R2.0                  | [275018a17e](https://linux-hardware.org/?probe=275018a17e) | Sep 26, 2023 |
| Gigabyte      | F2A68HM-H                   | [f3b7fdc0c1](https://linux-hardware.org/?probe=f3b7fdc0c1) | Sep 26, 2023 |
| Medion        | MS-7848                     | [5ce2a07d18](https://linux-hardware.org/?probe=5ce2a07d18) | Sep 25, 2023 |
| Fujitsu       | D3432-A1 S26361-D3432-A1    | [c3043092b9](https://linux-hardware.org/?probe=c3043092b9) | Sep 22, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [d2fe3f1d44](https://linux-hardware.org/?probe=d2fe3f1d44) | Sep 19, 2023 |
| Gigabyte      | F2A68HM-H                   | [08e19ba183](https://linux-hardware.org/?probe=08e19ba183) | Sep 13, 2023 |
| ASUSTek       | P9X79 PRO                   | [1056a6ebb4](https://linux-hardware.org/?probe=1056a6ebb4) | Sep 06, 2023 |
| Dell          | 042P49 A00                  | [b9dddc1ef8](https://linux-hardware.org/?probe=b9dddc1ef8) | Sep 06, 2023 |
| Dell          | 0GY6Y8 A03                  | [da9dc1f5d9](https://linux-hardware.org/?probe=da9dc1f5d9) | Sep 05, 2023 |
| HP            | 198E                        | [7f57cfbacc](https://linux-hardware.org/?probe=7f57cfbacc) | Sep 04, 2023 |
| AMD           | A88K                        | [d58c29d4ad](https://linux-hardware.org/?probe=d58c29d4ad) | Sep 03, 2023 |
| HP            | 2B2C                        | [a24d61a0f4](https://linux-hardware.org/?probe=a24d61a0f4) | Sep 02, 2023 |
| HP            | 198E                        | [3f3cb2e64c](https://linux-hardware.org/?probe=3f3cb2e64c) | Sep 02, 2023 |
| AMD           | A88K                        | [08a455504f](https://linux-hardware.org/?probe=08a455504f) | Sep 01, 2023 |
| Gigabyte      | H97N-WIFI                   | [6edcb45992](https://linux-hardware.org/?probe=6edcb45992) | Aug 26, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [4d01543131](https://linux-hardware.org/?probe=4d01543131) | Aug 24, 2023 |
| ASUSTek       | P8Z68-V GEN3                | [aad70f30d7](https://linux-hardware.org/?probe=aad70f30d7) | Aug 21, 2023 |
| ASUSTek       | PRIME B550M-K               | [60de8d6d38](https://linux-hardware.org/?probe=60de8d6d38) | Aug 11, 2023 |
| Acer          | Aspire TC-885 V:1.1         | [63f0153cfe](https://linux-hardware.org/?probe=63f0153cfe) | Aug 10, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | [150d68269d](https://linux-hardware.org/?probe=150d68269d) | Aug 08, 2023 |
| MSI           | A68HM-E33 V2                | [047ae922f7](https://linux-hardware.org/?probe=047ae922f7) | Aug 07, 2023 |
| MSI           | A68HM-E33 V2                | [341fecf811](https://linux-hardware.org/?probe=341fecf811) | Aug 06, 2023 |
| ASUSTek       | PRIME Z790-P WIFI D4        | [13f47a5399](https://linux-hardware.org/?probe=13f47a5399) | Aug 06, 2023 |
| ASUSTek       | M5A78L-M LX3                | [0ffd23b534](https://linux-hardware.org/?probe=0ffd23b534) | Aug 04, 2023 |
| ASUSTek       | P5B-Deluxe                  | [122ba504c1](https://linux-hardware.org/?probe=122ba504c1) | Aug 04, 2023 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | [a61b8168b7](https://linux-hardware.org/?probe=a61b8168b7) | Aug 02, 2023 |
| ASUSTek       | H97-PLUS                    | [485793f801](https://linux-hardware.org/?probe=485793f801) | Aug 02, 2023 |
| ASRock        | Z490M-ITX/ac                | [80558a1dcd](https://linux-hardware.org/?probe=80558a1dcd) | Aug 02, 2023 |
| MSI           | H310M PRO-M2 PLUS           | [136cb11fa2](https://linux-hardware.org/?probe=136cb11fa2) | Jul 28, 2023 |
| Foxconn       | nT-iBT18/nT-iBT19/nT-iBT... | [23633cafce](https://linux-hardware.org/?probe=23633cafce) | Jul 27, 2023 |
| Toshiba       | STI 005492G                 | [6e73cad7e4](https://linux-hardware.org/?probe=6e73cad7e4) | Jul 27, 2023 |
| MSI           | A520M-A PRO                 | [6a1aa5fbc8](https://linux-hardware.org/?probe=6a1aa5fbc8) | Jul 26, 2023 |
| ASRock        | 960GC-GS FX                 | [187cbf1010](https://linux-hardware.org/?probe=187cbf1010) | Jul 21, 2023 |
| MSI           | H310M PRO-M2 PLUS           | [287298e199](https://linux-hardware.org/?probe=287298e199) | Jul 21, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [0bd37865ac](https://linux-hardware.org/?probe=0bd37865ac) | Jul 15, 2023 |
| Dell          | 09M8Y8 A01                  | [8807f705d0](https://linux-hardware.org/?probe=8807f705d0) | Jul 12, 2023 |
| ASRock        | A320M-HD                    | [5477254db4](https://linux-hardware.org/?probe=5477254db4) | Jul 10, 2023 |
| ASRock        | Z170 Extreme4               | [abc4554a51](https://linux-hardware.org/?probe=abc4554a51) | Jul 04, 2023 |
| ASUSTek       | PRIME H610M-K D4            | [196daaa768](https://linux-hardware.org/?probe=196daaa768) | Jun 30, 2023 |
| ASUSTek       | PRIME H610M-K D4            | [8e7db66929](https://linux-hardware.org/?probe=8e7db66929) | Jun 30, 2023 |
| ASUSTek       | H61M-CS                     | [2878c06857](https://linux-hardware.org/?probe=2878c06857) | Jun 26, 2023 |
| HP            | 339A                        | [ff38f43250](https://linux-hardware.org/?probe=ff38f43250) | Jun 25, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [a39abe1278](https://linux-hardware.org/?probe=a39abe1278) | Jun 24, 2023 |
| Hardkernel    | ODROID-H2                   | [8f879f5566](https://linux-hardware.org/?probe=8f879f5566) | Jun 21, 2023 |
| ASUSTek       | PRIME Z270-K                | [66736b8fbb](https://linux-hardware.org/?probe=66736b8fbb) | Jun 21, 2023 |
| Intel         | H61                         | [d8de2bb1a7](https://linux-hardware.org/?probe=d8de2bb1a7) | Jun 20, 2023 |
| Dell          | 0N4YC8 A00                  | [154f9809e6](https://linux-hardware.org/?probe=154f9809e6) | Jun 18, 2023 |
| Dell          | 0N4YC8 A00                  | [66ce1a98a8](https://linux-hardware.org/?probe=66ce1a98a8) | Jun 18, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [10b3b517f3](https://linux-hardware.org/?probe=10b3b517f3) | Jun 18, 2023 |
| Biostar       | TPower I45                  | [b88767bce0](https://linux-hardware.org/?probe=b88767bce0) | Jun 11, 2023 |
| MSI           | A55M-E35                    | [7800efb785](https://linux-hardware.org/?probe=7800efb785) | Jun 08, 2023 |
| ASUSTek       | PRIME H410I-PLUS            | [83988ad739](https://linux-hardware.org/?probe=83988ad739) | Jun 06, 2023 |
| HP            | 8768 A                      | [17d0560a85](https://linux-hardware.org/?probe=17d0560a85) | Jun 05, 2023 |
| HP            | 21B4 A01                    | [5d394c52ed](https://linux-hardware.org/?probe=5d394c52ed) | Jun 04, 2023 |
| Gigabyte      | Z690 AORUS ELITE DDR4       | [c716b12ee2](https://linux-hardware.org/?probe=c716b12ee2) | Jun 02, 2023 |
| Gigabyte      | H270-HD3-CF                 | [d2912dfb69](https://linux-hardware.org/?probe=d2912dfb69) | May 31, 2023 |
| Acer          | Veriton N4620G              | [4f2cc019b8](https://linux-hardware.org/?probe=4f2cc019b8) | May 26, 2023 |
| Unknown       | 1.0                         | [54d3a069a4](https://linux-hardware.org/?probe=54d3a069a4) | May 22, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | [9419d4d25c](https://linux-hardware.org/?probe=9419d4d25c) | May 19, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [584948af65](https://linux-hardware.org/?probe=584948af65) | May 19, 2023 |
| MSI           | H310M PRO-M2 PLUS           | [0b802ad297](https://linux-hardware.org/?probe=0b802ad297) | May 19, 2023 |
| Gigabyte      | M68MT-S2                    | [bd7e95bf66](https://linux-hardware.org/?probe=bd7e95bf66) | May 18, 2023 |
| Pegatron      | Benicia                     | [8d49889e39](https://linux-hardware.org/?probe=8d49889e39) | May 18, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [3a7b647f0b](https://linux-hardware.org/?probe=3a7b647f0b) | May 17, 2023 |
| HP            | 09F8h                       | [380bbcda71](https://linux-hardware.org/?probe=380bbcda71) | May 17, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | [f48dba1e04](https://linux-hardware.org/?probe=f48dba1e04) | May 16, 2023 |
| ASUSTek       | P5B-Deluxe                  | [87edc3a632](https://linux-hardware.org/?probe=87edc3a632) | May 12, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [d5bd5c8930](https://linux-hardware.org/?probe=d5bd5c8930) | May 12, 2023 |
| ASRock        | Z590M-ITX/ax                | [2d3692d380](https://linux-hardware.org/?probe=2d3692d380) | May 11, 2023 |
| ASRock        | Z590M-ITX/ax                | [3c43bfe7bc](https://linux-hardware.org/?probe=3c43bfe7bc) | May 11, 2023 |
| ASUSTek       | P5Q SE2                     | [c7d1eac585](https://linux-hardware.org/?probe=c7d1eac585) | May 07, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [307dfb1c46](https://linux-hardware.org/?probe=307dfb1c46) | May 05, 2023 |
| MSI           | A68HM-E33 V2                | [bbac197d5d](https://linux-hardware.org/?probe=bbac197d5d) | May 04, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [11e132041b](https://linux-hardware.org/?probe=11e132041b) | May 04, 2023 |
| Dell          | 0GY6Y8 A03                  | [b735e1019b](https://linux-hardware.org/?probe=b735e1019b) | May 03, 2023 |
| Gigabyte      | X58A-UD3R                   | [36f4134c6b](https://linux-hardware.org/?probe=36f4134c6b) | May 01, 2023 |
| ASRock        | Z170 Extreme4               | [b2c012c1e2](https://linux-hardware.org/?probe=b2c012c1e2) | Apr 27, 2023 |
| HP            | 1632                        | [b818834691](https://linux-hardware.org/?probe=b818834691) | Apr 26, 2023 |
| HP            | 1632                        | [caae9b5992](https://linux-hardware.org/?probe=caae9b5992) | Apr 26, 2023 |
| HP            | 0AECh D                     | [827246f901](https://linux-hardware.org/?probe=827246f901) | Apr 22, 2023 |
| ASRock        | N3700-ITX                   | [849679b442](https://linux-hardware.org/?probe=849679b442) | Apr 17, 2023 |
| ASRock        | X370 Killer SLI             | [912a7f830b](https://linux-hardware.org/?probe=912a7f830b) | Apr 16, 2023 |
| Gigabyte      | M68MT-S2                    | [7b5363bc3e](https://linux-hardware.org/?probe=7b5363bc3e) | Apr 16, 2023 |
| MSI           | Z77A-G43                    | [f44505b54b](https://linux-hardware.org/?probe=f44505b54b) | Apr 12, 2023 |
| Medion        | MS-7848                     | [40e46961a4](https://linux-hardware.org/?probe=40e46961a4) | Apr 08, 2023 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [8bc61e0fcd](https://linux-hardware.org/?probe=8bc61e0fcd) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [0f26b74917](https://linux-hardware.org/?probe=0f26b74917) | Mar 30, 2023 |
| Dell          | 0KWVT8 A02                  | [a46eb24b2a](https://linux-hardware.org/?probe=a46eb24b2a) | Mar 29, 2023 |
| MSI           | H110M PRO-D                 | [a822425dcf](https://linux-hardware.org/?probe=a822425dcf) | Mar 25, 2023 |
| ASUSTek       | P5B-Deluxe                  | [3d8b7a6d89](https://linux-hardware.org/?probe=3d8b7a6d89) | Mar 25, 2023 |
| MSI           | H81M-E33                    | [47f031e68c](https://linux-hardware.org/?probe=47f031e68c) | Mar 25, 2023 |
| Dell          | 00V62H A00                  | [34d3fc12b2](https://linux-hardware.org/?probe=34d3fc12b2) | Mar 25, 2023 |
| Dell          | 00V62H A00                  | [f7aaf1dcd0](https://linux-hardware.org/?probe=f7aaf1dcd0) | Mar 25, 2023 |
| ASRock        | FM2A68M-DG3+                | [204b7c3324](https://linux-hardware.org/?probe=204b7c3324) | Mar 23, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [bbd16627c2](https://linux-hardware.org/?probe=bbd16627c2) | Mar 22, 2023 |
| ASRock        | H270 Pro4                   | [01eb4c8ba5](https://linux-hardware.org/?probe=01eb4c8ba5) | Mar 22, 2023 |
| ASRock        | Z390M-ITX/ac                | [5c07e530e9](https://linux-hardware.org/?probe=5c07e530e9) | Mar 21, 2023 |
| ASRock        | FM2A68M-DG3+                | [00b550c606](https://linux-hardware.org/?probe=00b550c606) | Mar 18, 2023 |
| MSI           | H81M-E34                    | [4cad3cfe12](https://linux-hardware.org/?probe=4cad3cfe12) | Mar 14, 2023 |
| HP            | 0A64h                       | [d5b197e7f2](https://linux-hardware.org/?probe=d5b197e7f2) | Mar 12, 2023 |
| HP            | 0A64h                       | [14de22ae05](https://linux-hardware.org/?probe=14de22ae05) | Mar 11, 2023 |
| Foxconn       | ETON                        | [3a087bc020](https://linux-hardware.org/?probe=3a087bc020) | Mar 10, 2023 |
| Gigabyte      | H81M-H                      | [6f915814dd](https://linux-hardware.org/?probe=6f915814dd) | Mar 08, 2023 |
| Gigabyte      | H81M-H                      | [5fdd1701df](https://linux-hardware.org/?probe=5fdd1701df) | Mar 08, 2023 |
| Foxconn       | ETON                        | [2afed9b076](https://linux-hardware.org/?probe=2afed9b076) | Mar 08, 2023 |
| Lenovo        | 313C SDK0J40697 WIN 3305... | [44509323b0](https://linux-hardware.org/?probe=44509323b0) | Mar 08, 2023 |
| HP            | ProLiant MicroServer        | [32dedf99a8](https://linux-hardware.org/?probe=32dedf99a8) | Mar 07, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [5bd9a1c0d2](https://linux-hardware.org/?probe=5bd9a1c0d2) | Mar 07, 2023 |
| MSI           | PRO Z790-A WIFI             | [439ec46914](https://linux-hardware.org/?probe=439ec46914) | Mar 05, 2023 |
| ASUSTek       | PRIME Z270-A                | [ec9c2f21a5](https://linux-hardware.org/?probe=ec9c2f21a5) | Mar 05, 2023 |
| OEM           | Unknown                     | [d0f1ae246c](https://linux-hardware.org/?probe=d0f1ae246c) | Mar 03, 2023 |
| ASUSTek       | PRIME Z270-A                | [e367c45f3b](https://linux-hardware.org/?probe=e367c45f3b) | Mar 03, 2023 |
| Fujitsu       | D3223-A1 S26361-D3223-A1    | [c803be2765](https://linux-hardware.org/?probe=c803be2765) | Mar 02, 2023 |
| ASUSTek       | P5KC                        | [45f781ee3a](https://linux-hardware.org/?probe=45f781ee3a) | Feb 28, 2023 |
| Gigabyte      | MZBSWBP-00                  | [525ac20362](https://linux-hardware.org/?probe=525ac20362) | Feb 26, 2023 |
| MSI           | C847MS-E33                  | [698d950f05](https://linux-hardware.org/?probe=698d950f05) | Feb 24, 2023 |
| Dell          | 0YC03K A03                  | [0101ef8ce7](https://linux-hardware.org/?probe=0101ef8ce7) | Feb 23, 2023 |
| Intel         | X79                         | [28c9b2590c](https://linux-hardware.org/?probe=28c9b2590c) | Feb 18, 2023 |
| Intel         | X79                         | [89c51847f9](https://linux-hardware.org/?probe=89c51847f9) | Feb 18, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | [8338ee5a0d](https://linux-hardware.org/?probe=8338ee5a0d) | Feb 17, 2023 |
| Gigabyte      | H410M S2 V3                 | [0dbeeea38c](https://linux-hardware.org/?probe=0dbeeea38c) | Feb 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [e1bbf14222](https://linux-hardware.org/?probe=e1bbf14222) | Feb 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [ba96494c0f](https://linux-hardware.org/?probe=ba96494c0f) | Feb 16, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | [40c415883e](https://linux-hardware.org/?probe=40c415883e) | Feb 16, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [21ad600245](https://linux-hardware.org/?probe=21ad600245) | Feb 14, 2023 |
| ASRock        | AOD790GX/128M               | [693f4f40f8](https://linux-hardware.org/?probe=693f4f40f8) | Feb 13, 2023 |
| Gigabyte      | GA-A75-UD4H                 | [eb4302c6dd](https://linux-hardware.org/?probe=eb4302c6dd) | Feb 10, 2023 |
| Gigabyte      | MZBSWMP-00                  | [894f632950](https://linux-hardware.org/?probe=894f632950) | Feb 01, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [3fac03d01d](https://linux-hardware.org/?probe=3fac03d01d) | Jan 30, 2023 |
| MSI           | PRO B660M-A DDR4            | [0f2037dcd8](https://linux-hardware.org/?probe=0f2037dcd8) | Jan 30, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | [0e28b954b4](https://linux-hardware.org/?probe=0e28b954b4) | Jan 30, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | [10421fe598](https://linux-hardware.org/?probe=10421fe598) | Jan 30, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [6444a93633](https://linux-hardware.org/?probe=6444a93633) | Jan 29, 2023 |
| Gigabyte      | B450M S2H                   | [058de08b2b](https://linux-hardware.org/?probe=058de08b2b) | Jan 24, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [7e91e49912](https://linux-hardware.org/?probe=7e91e49912) | Jan 23, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [3324fafe5a](https://linux-hardware.org/?probe=3324fafe5a) | Jan 23, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [b5e6a74fcb](https://linux-hardware.org/?probe=b5e6a74fcb) | Jan 22, 2023 |
| Gigabyte      | 8I945GMF                    | [2971006e43](https://linux-hardware.org/?probe=2971006e43) | Jan 21, 2023 |
| MSI           | B450 TOMAHAWK               | [d5ad4c9486](https://linux-hardware.org/?probe=d5ad4c9486) | Jan 17, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [a49a3ddeaa](https://linux-hardware.org/?probe=a49a3ddeaa) | Jan 17, 2023 |
| Gigabyte      | B550M DS3H                  | [d667bf6bb2](https://linux-hardware.org/?probe=d667bf6bb2) | Jan 15, 2023 |
| Gigabyte      | X670 GAMING X AX            | [0277ea7e50](https://linux-hardware.org/?probe=0277ea7e50) | Jan 15, 2023 |
| Lenovo        | ThinkCentre M58 7373A5G     | [07a6ffe405](https://linux-hardware.org/?probe=07a6ffe405) | Jan 11, 2023 |
| Acer          | Veriton N2620G              | [6345424cff](https://linux-hardware.org/?probe=6345424cff) | Jan 07, 2023 |
| Gigabyte      | Z87N-WIFI                   | [ef5e737fd6](https://linux-hardware.org/?probe=ef5e737fd6) | Jan 04, 2023 |
| Gigabyte      | J1800N-D2H                  | [f809473b20](https://linux-hardware.org/?probe=f809473b20) | Jan 03, 2023 |
| Gigabyte      | B550 GAMING X V2            | [da1db1e278](https://linux-hardware.org/?probe=da1db1e278) | Jan 02, 2023 |
| Unknown       | Intel X79                   | [f26c05e261](https://linux-hardware.org/?probe=f26c05e261) | Dec 31, 2022 |
| ASUSTek       | PRIME B450M-K               | [cc1d0776d5](https://linux-hardware.org/?probe=cc1d0776d5) | Dec 30, 2022 |
| Lenovo        | ChiefRiver                  | [847a9e86cd](https://linux-hardware.org/?probe=847a9e86cd) | Dec 30, 2022 |
| HP            | 1998                        | [c3404205e3](https://linux-hardware.org/?probe=c3404205e3) | Dec 29, 2022 |
| Dell          | 040DDP A01                  | [3548fd618d](https://linux-hardware.org/?probe=3548fd618d) | Dec 28, 2022 |
| Acer          | Veriton NBU                 | [cca454d1bd](https://linux-hardware.org/?probe=cca454d1bd) | Dec 26, 2022 |
| MSI           | Z390-A PRO                  | [9bfeb5727a](https://linux-hardware.org/?probe=9bfeb5727a) | Dec 26, 2022 |
| ASRock        | N3700-ITX                   | [dc3f0d5062](https://linux-hardware.org/?probe=dc3f0d5062) | Dec 25, 2022 |
| ASRock        | A320M-HDV R4.0              | [41ec48c0e5](https://linux-hardware.org/?probe=41ec48c0e5) | Dec 23, 2022 |
| HP            | 81C9                        | [cb40ddba01](https://linux-hardware.org/?probe=cb40ddba01) | Dec 22, 2022 |
| HP            | 8594                        | [de0b36257e](https://linux-hardware.org/?probe=de0b36257e) | Dec 21, 2022 |
| PCWare        | IPMH81G1                    | [3dc25592eb](https://linux-hardware.org/?probe=3dc25592eb) | Dec 20, 2022 |
| ASUSTek       | M4A88T-M/USB3               | [52b5b53173](https://linux-hardware.org/?probe=52b5b53173) | Dec 19, 2022 |
| ASUSTek       | M4A88T-M/USB3               | [64972eb902](https://linux-hardware.org/?probe=64972eb902) | Dec 19, 2022 |
| Packard Be... | PT890-8237A                 | [bb9e8d2cd7](https://linux-hardware.org/?probe=bb9e8d2cd7) | Dec 17, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [fdb9e278dd](https://linux-hardware.org/?probe=fdb9e278dd) | Dec 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [c62c8e69b0](https://linux-hardware.org/?probe=c62c8e69b0) | Dec 12, 2022 |
| HP            | 1497                        | [475049bb79](https://linux-hardware.org/?probe=475049bb79) | Dec 10, 2022 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | [ef403a3962](https://linux-hardware.org/?probe=ef403a3962) | Dec 10, 2022 |
| ASUSTek       | PRIME A320M-K               | [ce802653d4](https://linux-hardware.org/?probe=ce802653d4) | Dec 07, 2022 |
| ASUSTek       | PRIME A320M-K               | [e2e47d2d43](https://linux-hardware.org/?probe=e2e47d2d43) | Dec 06, 2022 |
| ASUSTek       | P8H61-M LX3                 | [87d3950072](https://linux-hardware.org/?probe=87d3950072) | Nov 30, 2022 |
| MSI           | PRO Z690-A DDR4             | [bd30397e24](https://linux-hardware.org/?probe=bd30397e24) | Nov 29, 2022 |
| MSI           | PRO Z690-A DDR4             | [3b4f834c63](https://linux-hardware.org/?probe=3b4f834c63) | Nov 29, 2022 |
| ASRock        | H270M-ITX/ac                | [dfc381d411](https://linux-hardware.org/?probe=dfc381d411) | Nov 29, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [472530d650](https://linux-hardware.org/?probe=472530d650) | Nov 29, 2022 |
| Gigabyte      | A320M-S2H-CF                | [452417fa68](https://linux-hardware.org/?probe=452417fa68) | Nov 21, 2022 |
| ASUSTek       | M4A88TD-M/USB3              | [8ff2384625](https://linux-hardware.org/?probe=8ff2384625) | Nov 16, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [c9a4863d1f](https://linux-hardware.org/?probe=c9a4863d1f) | Nov 15, 2022 |
| MSI           | PRO H610M-B DDR4            | [5ffe9844bd](https://linux-hardware.org/?probe=5ffe9844bd) | Nov 15, 2022 |
| HP            | 1495                        | [e29c423a17](https://linux-hardware.org/?probe=e29c423a17) | Nov 15, 2022 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | [b042e75495](https://linux-hardware.org/?probe=b042e75495) | Nov 11, 2022 |
| Dell          | 0M5DCD A00                  | [ac93b84c08](https://linux-hardware.org/?probe=ac93b84c08) | Nov 10, 2022 |
| MSI           | A320M PRO-VH                | [70ba1bf558](https://linux-hardware.org/?probe=70ba1bf558) | Nov 08, 2022 |
| MSI           | PRO H610M-B DDR4            | [377df38ed7](https://linux-hardware.org/?probe=377df38ed7) | Nov 08, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [2796faab6c](https://linux-hardware.org/?probe=2796faab6c) | Nov 08, 2022 |
| Intel         | D525MW AAE93082-401         | [d37fe5f0b4](https://linux-hardware.org/?probe=d37fe5f0b4) | Nov 06, 2022 |
| Gigabyte      | Z77-DS3H                    | [e97900160b](https://linux-hardware.org/?probe=e97900160b) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M90p 3282A9G    | [f60040c1b7](https://linux-hardware.org/?probe=f60040c1b7) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M90p 3282A9G    | [cd87b011a0](https://linux-hardware.org/?probe=cd87b011a0) | Nov 05, 2022 |
| HP            | 8054                        | [0f1371d133](https://linux-hardware.org/?probe=0f1371d133) | Nov 03, 2022 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | [423d3158cd](https://linux-hardware.org/?probe=423d3158cd) | Nov 03, 2022 |
| Gigabyte      | 970A-DS3P                   | [65231808f8](https://linux-hardware.org/?probe=65231808f8) | Nov 02, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [3c65639aad](https://linux-hardware.org/?probe=3c65639aad) | Oct 25, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [7027921568](https://linux-hardware.org/?probe=7027921568) | Oct 25, 2022 |
| Intel         | DH61AG AAG23736-507         | [7fa3b3bc6a](https://linux-hardware.org/?probe=7fa3b3bc6a) | Oct 25, 2022 |
| Hardkernel    | ODROID-H2                   | [6398e45c99](https://linux-hardware.org/?probe=6398e45c99) | Oct 24, 2022 |
| MSI           | A320M PRO-VH                | [5f1aeaf170](https://linux-hardware.org/?probe=5f1aeaf170) | Oct 22, 2022 |
| ASUSTek       | Z97-P                       | [f5b8282e1f](https://linux-hardware.org/?probe=f5b8282e1f) | Oct 21, 2022 |
| Itautec       | ST 4273 ST-4273 Padrao 0... | [8c4af1707c](https://linux-hardware.org/?probe=8c4af1707c) | Oct 17, 2022 |
| MSI           | MS-7309                     | [9d4f0daf60](https://linux-hardware.org/?probe=9d4f0daf60) | Oct 16, 2022 |
| ASUSTek       | P8H67                       | [4f03e84827](https://linux-hardware.org/?probe=4f03e84827) | Oct 16, 2022 |
| Lenovo        | ThinkCentre M58 7373A5G     | [ed6ebf5f98](https://linux-hardware.org/?probe=ed6ebf5f98) | Oct 16, 2022 |
| HP            | 198E                        | [47439edd0e](https://linux-hardware.org/?probe=47439edd0e) | Oct 15, 2022 |
| Gigabyte      | G33M-DS2R                   | [a14ced18eb](https://linux-hardware.org/?probe=a14ced18eb) | Oct 15, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [c3513de476](https://linux-hardware.org/?probe=c3513de476) | Oct 11, 2022 |
| Dell          | 0WR7PY A03                  | [3598f82c1e](https://linux-hardware.org/?probe=3598f82c1e) | Oct 10, 2022 |
| HP            | 1589                        | [d50afd3db1](https://linux-hardware.org/?probe=d50afd3db1) | Oct 08, 2022 |
| ASUSTek       | ET1612I                     | [91fea00cbf](https://linux-hardware.org/?probe=91fea00cbf) | Oct 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [10e3123558](https://linux-hardware.org/?probe=10e3123558) | Oct 03, 2022 |
| MSI           | H170M PRO-VDH               | [f7254adff2](https://linux-hardware.org/?probe=f7254adff2) | Sep 25, 2022 |
| ASUSTek       | PRIME A320M-K               | [5588f73920](https://linux-hardware.org/?probe=5588f73920) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | [a83e57d8c1](https://linux-hardware.org/?probe=a83e57d8c1) | Sep 23, 2022 |
| ASUSTek       | A68HM-K                     | [966ae734c2](https://linux-hardware.org/?probe=966ae734c2) | Sep 20, 2022 |
| ASRock        | 960GC-GS FX                 | [3e40742ff0](https://linux-hardware.org/?probe=3e40742ff0) | Sep 18, 2022 |
| ASUSTek       | ET1612I                     | [0ddd9554cc](https://linux-hardware.org/?probe=0ddd9554cc) | Sep 16, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | [588c189149](https://linux-hardware.org/?probe=588c189149) | Sep 16, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | [4b94d21772](https://linux-hardware.org/?probe=4b94d21772) | Sep 16, 2022 |
| ASUSTek       | Maximus VII HERO            | [6d40add21a](https://linux-hardware.org/?probe=6d40add21a) | Sep 15, 2022 |
| Dell          | 0DR845                      | [158b3832bc](https://linux-hardware.org/?probe=158b3832bc) | Sep 13, 2022 |
| ASUSTek       | K30BD                       | [d6daf0e1f8](https://linux-hardware.org/?probe=d6daf0e1f8) | Sep 13, 2022 |
| ASUSTek       | H61M-C                      | [bb07dfab63](https://linux-hardware.org/?probe=bb07dfab63) | Sep 13, 2022 |
| ASRock        | N68-S3 UCC                  | [e59aa2e1d5](https://linux-hardware.org/?probe=e59aa2e1d5) | Sep 13, 2022 |
| ASRock        | N68-S3 UCC                  | [930da2e105](https://linux-hardware.org/?probe=930da2e105) | Sep 13, 2022 |
| Dell          | 0DR845                      | [f65bf44380](https://linux-hardware.org/?probe=f65bf44380) | Sep 13, 2022 |
| ASUSTek       | PRIME A320M-K               | [7b7a1cfeb9](https://linux-hardware.org/?probe=7b7a1cfeb9) | Sep 11, 2022 |
| Dell          | 03NVJ6 A01                  | [3f51b6da48](https://linux-hardware.org/?probe=3f51b6da48) | Sep 10, 2022 |
| ASUSTek       | PRIME A320M-C R2.0          | [7649a53341](https://linux-hardware.org/?probe=7649a53341) | Sep 06, 2022 |
| ASUSTek       | PRIME B560-PLUS             | [989e0d5d57](https://linux-hardware.org/?probe=989e0d5d57) | Sep 06, 2022 |
| ASUSTek       | PRIME B560-PLUS             | [f51b1f139e](https://linux-hardware.org/?probe=f51b1f139e) | Sep 06, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | [668995f3ff](https://linux-hardware.org/?probe=668995f3ff) | Sep 04, 2022 |
| ASUSTek       | K30BD                       | [6042bda5d7](https://linux-hardware.org/?probe=6042bda5d7) | Sep 03, 2022 |
| HP            | 8433 11                     | [00868f25c6](https://linux-hardware.org/?probe=00868f25c6) | Aug 31, 2022 |
| ASUSTek       | Z97-C                       | [9bdae9239f](https://linux-hardware.org/?probe=9bdae9239f) | Aug 29, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | [e692fe97cb](https://linux-hardware.org/?probe=e692fe97cb) | Aug 28, 2022 |
| ASUSTek       | P8H67-M LE                  | [7bf3626764](https://linux-hardware.org/?probe=7bf3626764) | Aug 25, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [c37bc2a345](https://linux-hardware.org/?probe=c37bc2a345) | Aug 24, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [5dabf74b7f](https://linux-hardware.org/?probe=5dabf74b7f) | Aug 21, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [ed1f055157](https://linux-hardware.org/?probe=ed1f055157) | Aug 19, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [764eaea2ba](https://linux-hardware.org/?probe=764eaea2ba) | Aug 19, 2022 |
| eMachines     | ET1350                      | [96e9f7aba7](https://linux-hardware.org/?probe=96e9f7aba7) | Aug 18, 2022 |
| Foxconn       | 2ADA                        | [015ccc4b06](https://linux-hardware.org/?probe=015ccc4b06) | Aug 18, 2022 |
| HP            | 8591                        | [4235eb97c1](https://linux-hardware.org/?probe=4235eb97c1) | Aug 18, 2022 |
| Dell          | 0YXT71 A00                  | [def7e10c65](https://linux-hardware.org/?probe=def7e10c65) | Aug 17, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [b98fcab3a6](https://linux-hardware.org/?probe=b98fcab3a6) | Aug 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [fd06db829d](https://linux-hardware.org/?probe=fd06db829d) | Aug 14, 2022 |
| MSI           | H310M PRO-M2 PLUS           | [0fadd2421f](https://linux-hardware.org/?probe=0fadd2421f) | Aug 08, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [01bcafef3c](https://linux-hardware.org/?probe=01bcafef3c) | Jul 30, 2022 |
| ASUSTek       | PRIME A320M-K               | [9a97caa028](https://linux-hardware.org/?probe=9a97caa028) | Jul 28, 2022 |
| ASUSTek       | PRIME A320M-K               | [d00325cd68](https://linux-hardware.org/?probe=d00325cd68) | Jul 28, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [da54317b9a](https://linux-hardware.org/?probe=da54317b9a) | Jul 27, 2022 |
| ASUSTek       | P8H67-M LE                  | [a27a0707b8](https://linux-hardware.org/?probe=a27a0707b8) | Jul 25, 2022 |
| PCWare        | IPX1800E2                   | [4426727633](https://linux-hardware.org/?probe=4426727633) | Jul 24, 2022 |
| MSI           | PRO B660M-A DDR4            | [ba0058e96e](https://linux-hardware.org/?probe=ba0058e96e) | Jul 20, 2022 |
| ASUSTek       | PRIME B450M-A               | [d5a64d7baa](https://linux-hardware.org/?probe=d5a64d7baa) | Jul 16, 2022 |
| MSI           | A320M PRO-E                 | [d16a812a12](https://linux-hardware.org/?probe=d16a812a12) | Jul 10, 2022 |
| MSI           | PRO B660M-A DDR4            | [7b470f27d3](https://linux-hardware.org/?probe=7b470f27d3) | Jul 03, 2022 |
| Dell          | 0GXM1W A00                  | [d48eb55102](https://linux-hardware.org/?probe=d48eb55102) | Jul 01, 2022 |
| MSI           | B450M-A PRO MAX             | [db4763808b](https://linux-hardware.org/?probe=db4763808b) | Jun 22, 2022 |
| MSI           | G31TM-P21                   | [824dc8a1c9](https://linux-hardware.org/?probe=824dc8a1c9) | Jun 11, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [33dbe3e5db](https://linux-hardware.org/?probe=33dbe3e5db) | Jun 08, 2022 |
| ASUSTek       | PRIME X470-PRO              | [496399846f](https://linux-hardware.org/?probe=496399846f) | May 26, 2022 |
| Lenovo        | MAHOBAY NOK                 | [aa8d9cb3b9](https://linux-hardware.org/?probe=aa8d9cb3b9) | May 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [a22a5ebbff](https://linux-hardware.org/?probe=a22a5ebbff) | May 25, 2022 |
| ASUSTek       | X99-A II                    | [288a6b3b20](https://linux-hardware.org/?probe=288a6b3b20) | May 23, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [3e34ce179d](https://linux-hardware.org/?probe=3e34ce179d) | May 22, 2022 |
| Fujitsu       | D2917-A1 S26361-D2917-A1    | [6f58937bed](https://linux-hardware.org/?probe=6f58937bed) | May 13, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | [bd94a8145a](https://linux-hardware.org/?probe=bd94a8145a) | May 08, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [e7ad5ed098](https://linux-hardware.org/?probe=e7ad5ed098) | May 06, 2022 |
| Acer          | Veriton M490G               | [f55983d536](https://linux-hardware.org/?probe=f55983d536) | May 04, 2022 |
| ASRock        | P55 Pro                     | [e626676348](https://linux-hardware.org/?probe=e626676348) | May 02, 2022 |
| HP            | 09F8h                       | [8605181df9](https://linux-hardware.org/?probe=8605181df9) | Apr 26, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Desktops | Percent |
|--------------------|----------|---------|
| 5.15.0-56-generic  | 18       | 4.93%   |
| 5.15.0-52-generic  | 16       | 4.38%   |
| 6.5.0-26-generic   | 12       | 3.29%   |
| 5.15.0-58-generic  | 9        | 2.47%   |
| 5.15.0-47-generic  | 9        | 2.47%   |
| 5.15.0-46-generic  | 9        | 2.47%   |
| 5.15.0-67-generic  | 8        | 2.19%   |
| 5.15.0-60-generic  | 8        | 2.19%   |
| 6.5.0-35-generic   | 6        | 1.64%   |
| 6.5.0-14-generic   | 6        | 1.64%   |
| 6.2.0-36-generic   | 6        | 1.64%   |
| 5.19.0-35-generic  | 6        | 1.64%   |
| 5.15.0-48-generic  | 6        | 1.64%   |
| 5.15.0-43-generic  | 6        | 1.64%   |
| 5.15.0-27-generic  | 6        | 1.64%   |
| 5.15.0-25-generic  | 6        | 1.64%   |
| 6.5.0-25-generic   | 5        | 1.37%   |
| 6.5.0-15-generic   | 5        | 1.37%   |
| 6.2.0-39-generic   | 5        | 1.37%   |
| 6.2.0-37-generic   | 5        | 1.37%   |
| 5.19.0-50-generic  | 5        | 1.37%   |
| 5.19.0-41-generic  | 5        | 1.37%   |
| 5.15.0-97-generic  | 5        | 1.37%   |
| 5.15.0-41-generic  | 5        | 1.37%   |
| 6.8.0-40-generic   | 4        | 1.1%    |
| 6.5.0-41-generic   | 4        | 1.1%    |
| 6.2.0-33-generic   | 4        | 1.1%    |
| 6.2.0-26-generic   | 4        | 1.1%    |
| 5.19.0-43-generic  | 4        | 1.1%    |
| 5.15.0-91-generic  | 4        | 1.1%    |
| 5.15.0-84-generic  | 4        | 1.1%    |
| 5.15.0-78-generic  | 4        | 1.1%    |
| 5.15.0-69-generic  | 4        | 1.1%    |
| 5.15.0-57-generic  | 4        | 1.1%    |
| 5.15.0-53-generic  | 4        | 1.1%    |
| 5.15.0-50-generic  | 4        | 1.1%    |
| 5.15.0-112-generic | 4        | 1.1%    |
| 6.5.0-44-generic   | 3        | 0.82%   |
| 6.5.0-21-generic   | 3        | 0.82%   |
| 6.5.0-18-generic   | 3        | 0.82%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.15.0   | 190      | 58.28%  |
| 6.5.0    | 47       | 14.42%  |
| 6.2.0    | 33       | 10.12%  |
| 5.19.0   | 28       | 8.59%   |
| 6.8.0    | 6        | 1.84%   |
| 6.1.0    | 3        | 0.92%   |
| 6.2.7    | 2        | 0.61%   |
| 5.17.0   | 2        | 0.61%   |
| 5.13.0   | 2        | 0.61%   |
| 6.4.8    | 1        | 0.31%   |
| 6.3.3    | 1        | 0.31%   |
| 6.3.12   | 1        | 0.31%   |
| 6.2.2    | 1        | 0.31%   |
| 6.2.10   | 1        | 0.31%   |
| 6.1.10   | 1        | 0.31%   |
| 6.0.0    | 1        | 0.31%   |
| 5.4.0    | 1        | 0.31%   |
| 5.19.13  | 1        | 0.31%   |
| 5.19.1   | 1        | 0.31%   |
| 5.18.0   | 1        | 0.31%   |
| 5.17.5   | 1        | 0.31%   |
| 5.10.110 | 1        | 0.31%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 190      | 58.28%  |
| 6.5     | 47       | 14.42%  |
| 6.2     | 37       | 11.35%  |
| 5.19    | 30       | 9.2%    |
| 6.8     | 6        | 1.84%   |
| 6.1     | 4        | 1.23%   |
| 5.17    | 3        | 0.92%   |
| 6.3     | 2        | 0.61%   |
| 5.13    | 2        | 0.61%   |
| 6.4     | 1        | 0.31%   |
| 6.0     | 1        | 0.31%   |
| 5.4     | 1        | 0.31%   |
| 5.18    | 1        | 0.31%   |
| 5.10    | 1        | 0.31%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 315      | 99.68%  |
| armv7l | 1        | 0.32%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| XFCE            | 305      | 95.91%  |
| GNOME           | 7        | 2.2%    |
| X-Cinnamon      | 2        | 0.63%   |
| i3              | 2        | 0.63%   |
| KDE5            | 1        | 0.31%   |
| GNOME Flashback | 1        | 0.31%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 301      | 93.77%  |
| Tty     | 16       | 4.98%   |
| Wayland | 3        | 0.93%   |
| Unknown | 1        | 0.31%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 258      | 81.39%  |
| Unknown | 31       | 9.78%   |
| GDM3    | 25       | 7.89%   |
| SDDM    | 2        | 0.63%   |
| GDM     | 1        | 0.32%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 117      | 37.03%  |
| fr_FR   | 44       | 13.92%  |
| de_DE   | 33       | 10.44%  |
| it_IT   | 22       | 6.96%   |
| pt_BR   | 19       | 6.01%   |
| en_CA   | 10       | 3.16%   |
| ru_RU   | 9        | 2.85%   |
| en_GB   | 8        | 2.53%   |
| en_AU   | 6        | 1.9%    |
| C       | 5        | 1.58%   |
| pl_PL   | 4        | 1.27%   |
| es_ES   | 4        | 1.27%   |
| es_AR   | 3        | 0.95%   |
| nl_NL   | 2        | 0.63%   |
| hu_HU   | 2        | 0.63%   |
| fr_CA   | 2        | 0.63%   |
| fi_FI   | 2        | 0.63%   |
| es_CO   | 2        | 0.63%   |
| en_IN   | 2        | 0.63%   |
| cs_CZ   | 2        | 0.63%   |
| Unknown | 2        | 0.63%   |
| tr_TR   | 1        | 0.32%   |
| sv_SE   | 1        | 0.32%   |
| ru_UA   | 1        | 0.32%   |
| nl_BE   | 1        | 0.32%   |
| ja_JP   | 1        | 0.32%   |
| fr_CH   | 1        | 0.32%   |
| fr_BE   | 1        | 0.32%   |
| es_VE   | 1        | 0.32%   |
| es_NI   | 1        | 0.32%   |
| es_MX   | 1        | 0.32%   |
| es_CR   | 1        | 0.32%   |
| eo      | 1        | 0.32%   |
| en_ZA   | 1        | 0.32%   |
| en_NZ   | 1        | 0.32%   |
| en_IE   | 1        | 0.32%   |
| de_CH   | 1        | 0.32%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 182      | 57.23%  |
| EFI  | 136      | 42.77%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 260      | 81.25%  |
| Tmpfs   | 41       | 12.81%  |
| Overlay | 8        | 2.5%    |
| Btrfs   | 7        | 2.19%   |
| Zfs     | 3        | 0.94%   |
| Ext3    | 1        | 0.31%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 216      | 67.08%  |
| MBR     | 59       | 18.32%  |
| Unknown | 47       | 14.6%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 252      | 78.02%  |
| Yes       | 71       | 21.98%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 205      | 64.47%  |
| Yes       | 113      | 35.53%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 82       | 25.95%  |
| Gigabyte Technology                  | 44       | 13.92%  |
| MSI                                  | 39       | 12.34%  |
| Dell                                 | 33       | 10.44%  |
| Hewlett-Packard                      | 31       | 9.81%   |
| ASRock                               | 21       | 6.65%   |
| Lenovo                               | 16       | 5.06%   |
| Intel                                | 10       | 3.16%   |
| Fujitsu                              | 5        | 1.58%   |
| Acer                                 | 5        | 1.58%   |
| Unknown                              | 5        | 1.58%   |
| Pegatron                             | 3        | 0.95%   |
| Foxconn                              | 3        | 0.95%   |
| PCWare                               | 2        | 0.63%   |
| Packard Bell                         | 2        | 0.63%   |
| Medion                               | 2        | 0.63%   |
| MACHINIST                            | 2        | 0.63%   |
| Biostar                              | 2        | 0.63%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.32%   |
| Semp Toshiba                         | 1        | 0.32%   |
| OEM                                  | 1        | 0.32%   |
| Itautec                              | 1        | 0.32%   |
| Hardkernel                           | 1        | 0.32%   |
| eMachines                            | 1        | 0.32%   |
| AZW                                  | 1        | 0.32%   |
| AOpen                                | 1        | 0.32%   |
| AMD                                  | 1        | 0.32%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                            | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| ASUS All Series                                 | 7        | 2.22%   |
| Unknown                                         | 6        | 1.9%    |
| Dell OptiPlex 7010                              | 5        | 1.58%   |
| MSI MS-7D43                                     | 3        | 0.95%   |
| MSI MS-7721                                     | 3        | 0.95%   |
| Lenovo ThinkCentre M83z 10C20003FR              | 3        | 0.95%   |
| ASUS PRIME A320M-K                              | 3        | 0.95%   |
| ASUS K30AD_M31AD_M51AD                          | 3        | 0.95%   |
| MSI MS-7D46                                     | 2        | 0.63%   |
| MSI MS-7D25                                     | 2        | 0.63%   |
| MSI MS-7C52                                     | 2        | 0.63%   |
| MSI MS-7817                                     | 2        | 0.63%   |
| MSI MS-7758                                     | 2        | 0.63%   |
| Lenovo V530S-07ICB 10TX0010PB                   | 2        | 0.63%   |
| HP t620 Quad Core TC                            | 2        | 0.63%   |
| HP EliteDesk 800 G1 SFF                         | 2        | 0.63%   |
| Dell OptiPlex 9020                              | 2        | 0.63%   |
| Dell OptiPlex 7020                              | 2        | 0.63%   |
| Dell OptiPlex 390                               | 2        | 0.63%   |
| Dell Inspiron 530                               | 2        | 0.63%   |
| ASUS TUF Gaming B550M-PLUS                      | 2        | 0.63%   |
| ASUS ROG STRIX B450-F GAMING II                 | 2        | 0.63%   |
| ASRock N68-S3 UCC                               | 2        | 0.63%   |
| Shenzhen Meigao Electronic Equipment UM773 Lite | 1        | 0.32%   |
| Semp Toshiba STI                                | 1        | 0.32%   |
| Pegatron p7-1170t                               | 1        | 0.32%   |
| Pegatron FZ132AA-ABF m9456fr                    | 1        | 0.32%   |
| Pegatron 20-b010                                | 1        | 0.32%   |
| PCWare IPX1800E2                                | 1        | 0.32%   |
| PCWare IPMH81G1                                 | 1        | 0.32%   |
| Packard Bell IMEDIA X9305                       | 1        | 0.32%   |
| Packard Bell IMEDIA S2185                       | 1        | 0.32%   |
| MSI Pentino H-Series                            | 1        | 0.32%   |
| MSI MS-7E07                                     | 1        | 0.32%   |
| MSI MS-7D53                                     | 1        | 0.32%   |
| MSI MS-7D40                                     | 1        | 0.32%   |
| MSI MS-7C91                                     | 1        | 0.32%   |
| MSI MS-7C84                                     | 1        | 0.32%   |
| MSI MS-7C56                                     | 1        | 0.32%   |
| MSI MS-7C37                                     | 1        | 0.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Dell OptiPlex                              | 20       | 6.33%   |
| ASUS PRIME                                 | 20       | 6.33%   |
| Lenovo ThinkCentre                         | 11       | 3.48%   |
| ASUS ROG                                   | 11       | 3.48%   |
| HP Compaq                                  | 7        | 2.22%   |
| ASUS TUF                                   | 7        | 2.22%   |
| ASUS All                                   | 7        | 2.22%   |
| Unknown                                    | 6        | 1.9%    |
| HP EliteDesk                               | 5        | 1.58%   |
| Dell Inspiron                              | 4        | 1.27%   |
| Acer Veriton                               | 4        | 1.27%   |
| MSI MS-7D43                                | 3        | 0.95%   |
| MSI MS-7721                                | 3        | 0.95%   |
| Gigabyte B550                              | 3        | 0.95%   |
| Fujitsu ESPRIMO                            | 3        | 0.95%   |
| Dell XPS                                   | 3        | 0.95%   |
| Dell Precision                             | 3        | 0.95%   |
| ASUS M5A78L-M                              | 3        | 0.95%   |
| ASUS K30AD                                 | 3        | 0.95%   |
| Packard Bell IMEDIA                        | 2        | 0.63%   |
| MSI MS-7D46                                | 2        | 0.63%   |
| MSI MS-7D25                                | 2        | 0.63%   |
| MSI MS-7C52                                | 2        | 0.63%   |
| MSI MS-7817                                | 2        | 0.63%   |
| MSI MS-7758                                | 2        | 0.63%   |
| Lenovo V530S-07ICB                         | 2        | 0.63%   |
| HP t620                                    | 2        | 0.63%   |
| HP ProDesk                                 | 2        | 0.63%   |
| HP Pavilion                                | 2        | 0.63%   |
| HP Desktop                                 | 2        | 0.63%   |
| Gigabyte B550M                             | 2        | 0.63%   |
| Gigabyte B450M                             | 2        | 0.63%   |
| ASUS P8H61-M                               | 2        | 0.63%   |
| ASUS M5A97                                 | 2        | 0.63%   |
| ASRock N68-S3                              | 2        | 0.63%   |
| Shenzhen Meigao Electronic Equipment UM773 | 1        | 0.32%   |
| Semp Toshiba STI                           | 1        | 0.32%   |
| Pegatron p7-1170t                          | 1        | 0.32%   |
| Pegatron FZ132AA-ABF                       | 1        | 0.32%   |
| Pegatron 20-b010                           | 1        | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2013    | 34       | 10.76%  |
| 2014    | 30       | 9.49%   |
| 2018    | 26       | 8.23%   |
| 2012    | 24       | 7.59%   |
| 2015    | 22       | 6.96%   |
| 2021    | 20       | 6.33%   |
| 2020    | 19       | 6.01%   |
| 2011    | 19       | 6.01%   |
| 2010    | 19       | 6.01%   |
| 2017    | 16       | 5.06%   |
| 2019    | 15       | 4.75%   |
| 2022    | 14       | 4.43%   |
| 2016    | 13       | 4.11%   |
| 2009    | 13       | 4.11%   |
| 2007    | 10       | 3.16%   |
| 2023    | 8        | 2.53%   |
| 2008    | 8        | 2.53%   |
| 2006    | 3        | 0.95%   |
| 2005    | 2        | 0.63%   |
| Unknown | 1        | 0.32%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 316      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 299      | 94.03%  |
| Enabled  | 19       | 5.97%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 316      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 72       | 22.57%  |
| 4.01-8.0        | 62       | 19.44%  |
| 3.01-4.0        | 53       | 16.61%  |
| 8.01-16.0       | 47       | 14.73%  |
| 32.01-64.0      | 44       | 13.79%  |
| 64.01-256.0     | 17       | 5.33%   |
| 24.01-32.0      | 11       | 3.45%   |
| 1.01-2.0        | 7        | 2.19%   |
| 2.01-3.0        | 4        | 1.25%   |
| More than 256.0 | 1        | 0.31%   |
| 0.01-0.5        | 1        | 0.31%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 120      | 34.48%  |
| 2.01-3.0   | 75       | 21.55%  |
| 4.01-8.0   | 54       | 15.52%  |
| 3.01-4.0   | 51       | 14.66%  |
| 0.51-1.0   | 22       | 6.32%   |
| 8.01-16.0  | 17       | 4.89%   |
| 16.01-24.0 | 4        | 1.15%   |
| 0.01-0.5   | 3        | 0.86%   |
| 32.01-64.0 | 1        | 0.29%   |
| 24.01-32.0 | 1        | 0.29%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 128      | 39.38%  |
| 2      | 98       | 30.15%  |
| 3      | 47       | 14.46%  |
| 4      | 23       | 7.08%   |
| 5      | 13       | 4%      |
| 6      | 7        | 2.15%   |
| 7      | 4        | 1.23%   |
| 0      | 3        | 0.92%   |
| 10     | 1        | 0.31%   |
| 9      | 1        | 0.31%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 166      | 52.2%   |
| Yes       | 152      | 47.8%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 312      | 98.73%  |
| No        | 4        | 1.27%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 183      | 57.19%  |
| Yes       | 137      | 42.81%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 224      | 70.44%  |
| Yes       | 94       | 29.56%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country         | Desktops | Percent |
|-----------------|----------|---------|
| USA             | 60       | 18.93%  |
| France          | 42       | 13.25%  |
| Germany         | 38       | 11.99%  |
| Brazil          | 23       | 7.26%   |
| Italy           | 21       | 6.62%   |
| Canada          | 14       | 4.42%   |
| Russia          | 12       | 3.79%   |
| Poland          | 7        | 2.21%   |
| Sweden          | 6        | 1.89%   |
| Spain           | 6        | 1.89%   |
| Netherlands     | 6        | 1.89%   |
| Belgium         | 6        | 1.89%   |
| Australia       | 6        | 1.89%   |
| UK              | 5        | 1.58%   |
| Switzerland     | 4        | 1.26%   |
| Colombia        | 4        | 1.26%   |
| Argentina       | 4        | 1.26%   |
| Serbia          | 3        | 0.95%   |
| Mexico          | 3        | 0.95%   |
| Greece          | 3        | 0.95%   |
| Finland         | 3        | 0.95%   |
| Czechia         | 3        | 0.95%   |
| Portugal        | 2        | 0.63%   |
| Norway          | 2        | 0.63%   |
| Ireland         | 2        | 0.63%   |
| Iran            | 2        | 0.63%   |
| India           | 2        | 0.63%   |
| Hungary         | 2        | 0.63%   |
| Costa Rica      | 2        | 0.63%   |
| China           | 2        | 0.63%   |
| Belarus         | 2        | 0.63%   |
| Austria         | 2        | 0.63%   |
| Turkey          | 1        | 0.32%   |
| The Netherlands | 1        | 0.32%   |
| Taiwan          | 1        | 0.32%   |
| South Africa    | 1        | 0.32%   |
| Slovenia        | 1        | 0.32%   |
| Slovakia        | 1        | 0.32%   |
| Romania         | 1        | 0.32%   |
| Pakistan        | 1        | 0.32%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Paris            | 6        | 1.82%   |
| Berlin           | 6        | 1.82%   |
| Springfield      | 4        | 1.22%   |
| Rio de Janeiro   | 4        | 1.22%   |
| Moscow           | 4        | 1.22%   |
| Harrisonburg     | 4        | 1.22%   |
| Amsterdam        | 4        | 1.22%   |
| Sydney           | 3        | 0.91%   |
| Santiago de Cali | 3        | 0.91%   |
| Milan            | 3        | 0.91%   |
| Helsinki         | 3        | 0.91%   |
| Zrenjanin        | 2        | 0.61%   |
| Valenciennes     | 2        | 0.61%   |
| Toul             | 2        | 0.61%   |
| Toronto          | 2        | 0.61%   |
| Tehran           | 2        | 0.61%   |
| Stuttgart        | 2        | 0.61%   |
| Schwerte         | 2        | 0.61%   |
| Rome             | 2        | 0.61%   |
| Rho              | 2        | 0.61%   |
| Peterborough     | 2        | 0.61%   |
| Munich           | 2        | 0.61%   |
| Melbourne        | 2        | 0.61%   |
| Mason            | 2        | 0.61%   |
| Lisbon           | 2        | 0.61%   |
| Lake Placid      | 2        | 0.61%   |
| Hanover          | 2        | 0.61%   |
| Gdansk           | 2        | 0.61%   |
| Dublin           | 2        | 0.61%   |
| Denain           | 2        | 0.61%   |
| Clermont-Ferrand | 2        | 0.61%   |
| Budapest         | 2        | 0.61%   |
| Biella           | 2        | 0.61%   |
| Żywiec          | 1        | 0.3%    |
| Yvoir            | 1        | 0.3%    |
| Yangon           | 1        | 0.3%    |
| Wusterhausen     | 1        | 0.3%    |
| Wojnicz          | 1        | 0.3%    |
| Winkelhaid       | 1        | 0.3%    |
| Winfield         | 1        | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 111      | 184    | 19.34%  |
| Seagate                     | 84       | 124    | 14.63%  |
| Samsung Electronics         | 83       | 118    | 14.46%  |
| Kingston                    | 46       | 66     | 8.01%   |
| Toshiba                     | 28       | 31     | 4.88%   |
| SanDisk                     | 26       | 32     | 4.53%   |
| Hitachi                     | 25       | 37     | 4.36%   |
| Crucial                     | 22       | 28     | 3.83%   |
| Unknown                     | 11       | 16     | 1.92%   |
| Intel                       | 11       | 13     | 1.92%   |
| PNY                         | 10       | 16     | 1.74%   |
| China                       | 10       | 11     | 1.74%   |
| HGST                        | 8        | 12     | 1.39%   |
| A-DATA Technology           | 8        | 8      | 1.39%   |
| SPCC                        | 5        | 7      | 0.87%   |
| Gigabyte Technology         | 5        | 8      | 0.87%   |
| Phison Electronics          | 4        | 7      | 0.7%    |
| Kingston Technology Company | 4        | 8      | 0.7%    |
| Intenso                     | 4        | 4      | 0.7%    |
| Hewlett-Packard             | 4        | 5      | 0.7%    |
| ASMT                        | 4        | 7      | 0.7%    |
| PHD 3.0                     | 3        | 4      | 0.52%   |
| Patriot                     | 3        | 3      | 0.52%   |
| Maxtor                      | 3        | 3      | 0.52%   |
| Lexar                       | 3        | 3      | 0.52%   |
| TEXTORM                     | 2        | 2      | 0.35%   |
| SK hynix                    | 2        | 2      | 0.35%   |
| Realtek Semiconductor       | 2        | 2      | 0.35%   |
| OCZ                         | 2        | 2      | 0.35%   |
| Micron Technology           | 2        | 2      | 0.35%   |
| KIOXIA                      | 2        | 4      | 0.35%   |
| Corsair                     | 2        | 2      | 0.35%   |
| ADATA Technology            | 2        | 2      | 0.35%   |
| XPG                         | 1        | 1      | 0.17%   |
| Veno                        | 1        | 1      | 0.17%   |
| Vaseky                      | 1        | 1      | 0.17%   |
| USB3.0                      | 1        | 2      | 0.17%   |
| Transcend                   | 1        | 2      | 0.17%   |
| TO Exter                    | 1        | 2      | 0.17%   |
| Timetec                     | 1        | 1      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Samsung SSD 860 EVO 500GB                            | 13       | 1.96%   |
| Kingston SA400S37240G 240GB SSD                      | 12       | 1.81%   |
| Toshiba DT01ACA100 1TB                               | 8        | 1.2%    |
| Crucial CT480BX500SSD1 480GB                         | 8        | 1.2%    |
| Seagate ST1000DM003-1ER162 1TB                       | 7        | 1.05%   |
| Kingston SA400S37480G 480GB SSD                      | 7        | 1.05%   |
| Seagate ST500DM002-1BD142 500GB                      | 6        | 0.9%    |
| WDC WD5000AAKX-08U6AA0 500GB                         | 5        | 0.75%   |
| Seagate ST2000DM008-2FR102 2TB                       | 5        | 0.75%   |
| Seagate ST1000DM003-1CH162 1TB                       | 5        | 0.75%   |
| Kingston SV300S37A120G 120GB SSD                     | 5        | 0.75%   |
| Unknown SD/MMC/MS PRO 128GB                          | 4        | 0.6%    |
| Toshiba HDWD110 1TB                                  | 4        | 0.6%    |
| Toshiba DT01ACA200 2TB                               | 4        | 0.6%    |
| Seagate ST1000DM003-1SB102 1TB                       | 4        | 0.6%    |
| SanDisk SDSSDA240G 240GB                             | 4        | 0.6%    |
| Samsung SSD 970 EVO Plus 1TB                         | 4        | 0.6%    |
| Samsung SSD 870 QVO 1TB                              | 4        | 0.6%    |
| WDC WDS500G2B0A-00SM50 500GB SSD                     | 3        | 0.45%   |
| WDC WD4000AAJS-00YFA0 400GB                          | 3        | 0.45%   |
| WDC WD10EZEX-08M2NA0 1TB                             | 3        | 0.45%   |
| Seagate ST4000DM004-2CV104 4TB                       | 3        | 0.45%   |
| Seagate ST3500413AS 500GB                            | 3        | 0.45%   |
| Seagate ST2000DM001-1ER164 2TB                       | 3        | 0.45%   |
| Seagate ST1000DM010-2EP102 1TB                       | 3        | 0.45%   |
| Seagate Expansion HDD 14TB                           | 3        | 0.45%   |
| SanDisk NVMe SSD Drive 1TB                           | 3        | 0.45%   |
| Samsung SSD 860 EVO 1TB                              | 3        | 0.45%   |
| Samsung SSD 850 EVO 500GB                            | 3        | 0.45%   |
| Samsung SSD 850 EVO 250GB                            | 3        | 0.45%   |
| Samsung SSD 840 Series 120GB                         | 3        | 0.45%   |
| Samsung SSD 840 EVO 250GB                            | 3        | 0.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 3        | 0.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 3        | 0.45%   |
| Samsung HD250HJ 250GB                                | 3        | 0.45%   |
| PHD 3.0 Silicon-Power 4TB                            | 3        | 0.45%   |
| Kingston SUV400S37120G 120GB SSD                     | 3        | 0.45%   |
| Kingston SA2000M81000G 1TB                           | 3        | 0.45%   |
| Hitachi HDS721010CLA332 1TB                          | 3        | 0.45%   |
| Hitachi HDP725050GLA360 500GB                        | 3        | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 101      | 170    | 36.86%  |
| Seagate             | 84       | 122    | 30.66%  |
| Toshiba             | 25       | 28     | 9.12%   |
| Hitachi             | 25       | 37     | 9.12%   |
| Samsung Electronics | 13       | 17     | 4.74%   |
| HGST                | 8        | 12     | 2.92%   |
| Unknown             | 4        | 5      | 1.46%   |
| Maxtor              | 2        | 2      | 0.73%   |
| Hewlett-Packard     | 2        | 2      | 0.73%   |
| ASMT                | 2        | 5      | 0.73%   |
| USB3.0              | 1        | 2      | 0.36%   |
| TO Exter            | 1        | 2      | 0.36%   |
| MaxDigital          | 1        | 1      | 0.36%   |
| MARVELL             | 1        | 1      | 0.36%   |
| LaCie               | 1        | 1      | 0.36%   |
| ICY BOX             | 1        | 1      | 0.36%   |
| ASMedia             | 1        | 1      | 0.36%   |
| Apple               | 1        | 1      | 0.36%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 49       | 61     | 22.9%   |
| Kingston            | 38       | 51     | 17.76%  |
| Crucial             | 20       | 26     | 9.35%   |
| SanDisk             | 18       | 22     | 8.41%   |
| WDC                 | 11       | 12     | 5.14%   |
| China               | 10       | 11     | 4.67%   |
| PNY                 | 9        | 15     | 4.21%   |
| A-DATA Technology   | 7        | 7      | 3.27%   |
| SPCC                | 5        | 7      | 2.34%   |
| Intel               | 5        | 5      | 2.34%   |
| Intenso             | 4        | 4      | 1.87%   |
| Toshiba             | 3        | 3      | 1.4%    |
| PHD 3.0             | 3        | 4      | 1.4%    |
| Patriot             | 3        | 3      | 1.4%    |
| TEXTORM             | 2        | 2      | 0.93%   |
| OCZ                 | 2        | 2      | 0.93%   |
| Lexar               | 2        | 2      | 0.93%   |
| Hewlett-Packard     | 2        | 3      | 0.93%   |
| Gigabyte Technology | 2        | 2      | 0.93%   |
| ASMT                | 2        | 2      | 0.93%   |
| Veno                | 1        | 1      | 0.47%   |
| Vaseky              | 1        | 1      | 0.47%   |
| Transcend           | 1        | 2      | 0.47%   |
| Timetec             | 1        | 1      | 0.47%   |
| Team                | 1        | 1      | 0.47%   |
| NT-512              | 1        | 1      | 0.47%   |
| Micron Technology   | 1        | 1      | 0.47%   |
| Maxtor              | 1        | 1      | 0.47%   |
| LITEONIT            | 1        | 1      | 0.47%   |
| LITEON              | 1        | 1      | 0.47%   |
| Linux               | 1        | 1      | 0.47%   |
| KIOXIA-EXCERIA      | 1        | 1      | 0.47%   |
| KingFast            | 1        | 1      | 0.47%   |
| KingDian            | 1        | 1      | 0.47%   |
| Fanxiang            | 1        | 1      | 0.47%   |
| Dogfish             | 1        | 1      | 0.47%   |
| Corsair             | 1        | 1      | 0.47%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 214      | 410    | 44.58%  |
| SSD     | 183      | 262    | 38.13%  |
| NVMe    | 72       | 129    | 15%     |
| Unknown | 7        | 9      | 1.46%   |
| MMC     | 4        | 6      | 0.83%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 290      | 629    | 73.42%  |
| NVMe | 72       | 128    | 18.23%  |
| SAS  | 29       | 53     | 7.34%   |
| MMC  | 4        | 6      | 1.01%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 232      | 377    | 54.21%  |
| 0.51-1.0   | 104      | 158    | 24.3%   |
| 1.01-2.0   | 44       | 62     | 10.28%  |
| 3.01-4.0   | 24       | 41     | 5.61%   |
| 10.01-20.0 | 9        | 13     | 2.1%    |
| 4.01-10.0  | 8        | 12     | 1.87%   |
| 2.01-3.0   | 7        | 9      | 1.64%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 78       | 23.93%  |
| 251-500        | 71       | 21.78%  |
| 501-1000       | 51       | 15.64%  |
| 1001-2000      | 47       | 14.42%  |
| More than 3000 | 33       | 10.12%  |
| 2001-3000      | 20       | 6.13%   |
| 51-100         | 11       | 3.37%   |
| 1-20           | 8        | 2.45%   |
| 21-50          | 7        | 2.15%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 70       | 20.9%   |
| 251-500        | 55       | 16.42%  |
| 21-50          | 48       | 14.33%  |
| 101-250        | 45       | 13.43%  |
| 51-100         | 40       | 11.94%  |
| 501-1000       | 26       | 7.76%   |
| 1001-2000      | 24       | 7.16%   |
| 2001-3000      | 15       | 4.48%   |
| More than 3000 | 12       | 3.58%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Toshiba DT01ACA100 1TB              | 2        | 2      | 3.23%   |
| Seagate ST1000DM003-1ER162 1TB      | 2        | 2      | 3.23%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 1        | 1      | 1.61%   |
| WDC WD5000LPLX-75ZNTT1 500GB        | 1        | 1      | 1.61%   |
| WDC WD5000BEVT-22A0RT0 500GB        | 1        | 1      | 1.61%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 1        | 1      | 1.61%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 1        | 1      | 1.61%   |
| WDC WD3200AVJS-63N9A0 320GB         | 1        | 1      | 1.61%   |
| WDC WD3200AAKS-75B3A0 320GB         | 1        | 2      | 1.61%   |
| WDC WD3200AAKS-00L9A0 320GB         | 1        | 1      | 1.61%   |
| WDC WD2500AAKS-00VSA0 250GB         | 1        | 1      | 1.61%   |
| WDC WD20EFRX-68AX9N0 2TB            | 1        | 1      | 1.61%   |
| WDC WD20EARS-00MVWB0 2TB            | 1        | 1      | 1.61%   |
| WDC WD2002FYPS-02W3B0 2TB           | 1        | 1      | 1.61%   |
| WDC WD10EZEX-60ZF5A0 1TB            | 1        | 1      | 1.61%   |
| WDC WD10EAVS-00D7B1 1TB             | 1        | 1      | 1.61%   |
| WDC WD10EARS-00Y5B1 1TB             | 1        | 1      | 1.61%   |
| WDC WD10EARS-003BB1 1TB             | 1        | 1      | 1.61%   |
| WDC WD1003FBYX-01Y7B1 1TB           | 1        | 1      | 1.61%   |
| Seagate ST9250410AS 250GB           | 1        | 1      | 1.61%   |
| Seagate ST500DM002-1BD142 500GB     | 1        | 1      | 1.61%   |
| Seagate ST4000DX001-1CE168 4TB      | 1        | 1      | 1.61%   |
| Seagate ST3750840AS 752GB           | 1        | 1      | 1.61%   |
| Seagate ST3500630AS 500GB           | 1        | 1      | 1.61%   |
| Seagate ST3500414CS 500GB           | 1        | 1      | 1.61%   |
| Seagate ST3250318AS 250GB           | 1        | 2      | 1.61%   |
| Seagate ST3250310AS 250GB           | 1        | 1      | 1.61%   |
| Seagate ST2000DM001-1ER164 2TB      | 1        | 1      | 1.61%   |
| Seagate ST2000DM001-1CH164 2TB      | 1        | 1      | 1.61%   |
| Seagate ST18000NM000J-2TV103 18TB   | 1        | 1      | 1.61%   |
| Seagate ST1000DM010-2EP102 1TB      | 1        | 1      | 1.61%   |
| Seagate ST1000DM003-1CH162 1TB      | 1        | 1      | 1.61%   |
| Samsung Electronics SSD 980 PRO 2TB | 1        | 1      | 1.61%   |
| Samsung Electronics SP2514N 250GB   | 1        | 1      | 1.61%   |
| Samsung Electronics HM321HI 320GB   | 1        | 2      | 1.61%   |
| Samsung Electronics HD753LJ 752GB   | 1        | 1      | 1.61%   |
| Samsung Electronics HD502HJ 500GB   | 1        | 1      | 1.61%   |
| Samsung Electronics HD250HJ 250GB   | 1        | 1      | 1.61%   |
| Samsung Electronics HD103SJ 1TB     | 1        | 1      | 1.61%   |
| PNY 69D03094-T 40GB SSD             | 1        | 1      | 1.61%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 16       | 18     | 26.67%  |
| Seagate             | 15       | 16     | 25%     |
| Hitachi             | 7        | 9      | 11.67%  |
| Samsung Electronics | 6        | 8      | 10%     |
| Kingston            | 4        | 4      | 6.67%   |
| Toshiba             | 2        | 2      | 3.33%   |
| PNY                 | 1        | 1      | 1.67%   |
| Maxtor              | 1        | 1      | 1.67%   |
| Intel               | 1        | 1      | 1.67%   |
| ICY BOX             | 1        | 1      | 1.67%   |
| HGST                | 1        | 3      | 1.67%   |
| Hewlett-Packard     | 1        | 1      | 1.67%   |
| Crucial             | 1        | 1      | 1.67%   |
| China               | 1        | 1      | 1.67%   |
| ASMT                | 1        | 4      | 1.67%   |
| A-DATA Technology   | 1        | 1      | 1.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 15       | 17     | 30.61%  |
| Seagate             | 15       | 16     | 30.61%  |
| Hitachi             | 7        | 9      | 14.29%  |
| Samsung Electronics | 5        | 7      | 10.2%   |
| Toshiba             | 2        | 2      | 4.08%   |
| Maxtor              | 1        | 1      | 2.04%   |
| ICY BOX             | 1        | 1      | 2.04%   |
| HGST                | 1        | 3      | 2.04%   |
| Hewlett-Packard     | 1        | 1      | 2.04%   |
| ASMT                | 1        | 4      | 2.04%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 44       | 61     | 81.48%  |
| SSD  | 8        | 9      | 14.81%  |
| NVMe | 2        | 2      | 3.7%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB | 1        | 3      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 3      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 191      | 417    | 51.21%  |
| Detected | 128      | 324    | 34.32%  |
| Malfunc  | 53       | 72     | 14.21%  |
| Failed   | 1        | 3      | 0.27%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 206      | 47.69%  |
| AMD                              | 95       | 21.99%  |
| Samsung Electronics              | 26       | 6.02%   |
| JMicron Technology               | 15       | 3.47%   |
| Kingston Technology Company      | 13       | 3.01%   |
| Phison Electronics               | 11       | 2.55%   |
| ASMedia Technology               | 10       | 2.31%   |
| SanDisk                          | 9        | 2.08%   |
| Nvidia                           | 8        | 1.85%   |
| Marvell Technology Group         | 8        | 1.85%   |
| Realtek Semiconductor            | 4        | 0.93%   |
| VIA Technologies                 | 3        | 0.69%   |
| Silicon Image                    | 3        | 0.69%   |
| Broadcom / LSI                   | 3        | 0.69%   |
| SK hynix                         | 2        | 0.46%   |
| Silicon Motion                   | 2        | 0.46%   |
| Micron/Crucial Technology        | 2        | 0.46%   |
| MAXIO Technology (Hangzhou)      | 2        | 0.46%   |
| KIOXIA                           | 2        | 0.46%   |
| ADATA Technology                 | 2        | 0.46%   |
| Silicon Integrated Systems [SiS] | 1        | 0.23%   |
| Shenzhen Longsys Electronics     | 1        | 0.23%   |
| Micron Technology                | 1        | 0.23%   |
| LSI Logic / Symbios Logic        | 1        | 0.23%   |
| INNOGRIT                         | 1        | 0.23%   |
| Adaptec                          | 1        | 0.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 53       | 9.69%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 38       | 6.95%   |
| AMD 500 Series Chipset SATA Controller                                                  | 17       | 3.11%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 16       | 2.93%   |
| Intel SATA Controller [RAID mode]                                                       | 15       | 2.74%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 15       | 2.74%   |
| AMD 400 Series Chipset SATA Controller                                                  | 15       | 2.74%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 14       | 2.56%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 13       | 2.38%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 12       | 2.19%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 11       | 2.01%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 11       | 2.01%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 11       | 2.01%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 10       | 1.83%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 10       | 1.83%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 9        | 1.65%   |
| Nvidia MCP61 SATA Controller                                                            | 8        | 1.46%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 8        | 1.46%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 8        | 1.46%   |
| Nvidia MCP61 IDE                                                                        | 7        | 1.28%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7        | 1.28%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 6        | 1.1%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 6        | 1.1%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 6        | 1.1%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 5        | 0.91%   |
| Kingston Company A2000 NVMe SSD [SM2263EN]                                              | 5        | 0.91%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 5        | 0.91%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 0.91%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 5        | 0.91%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 0.91%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 0.91%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 5        | 0.91%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 4        | 0.73%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 4        | 0.73%   |
| Intel SSD 670p Series [Keystone Harbor]                                                 | 4        | 0.73%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 4        | 0.73%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 4        | 0.73%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 4        | 0.73%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 4        | 0.73%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 4        | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 258      | 60.28%  |
| NVMe | 72       | 16.82%  |
| IDE  | 66       | 15.42%  |
| RAID | 26       | 6.07%   |
| SAS  | 5        | 1.17%   |
| SCSI | 1        | 0.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 210      | 66.46%  |
| AMD    | 105      | 33.23%  |
| ARM    | 1        | 0.32%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 7        | 2.21%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 6        | 1.89%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 5        | 1.58%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 5        | 1.58%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 5        | 1.58%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 4        | 1.26%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 4        | 1.26%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 4        | 1.26%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 4        | 1.26%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 3        | 0.95%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 3        | 0.95%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 3        | 0.95%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 3        | 0.95%   |
| Intel Core i5-4590S CPU @ 3.00GHz           | 3        | 0.95%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 3        | 0.95%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 3        | 0.95%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 0.95%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 0.95%   |
| Intel Celeron CPU J1800 @ 2.41GHz           | 3        | 0.95%   |
| Intel Celeron CPU 847 @ 1.10GHz             | 3        | 0.95%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 3        | 0.95%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 3        | 0.95%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 3        | 0.95%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 3        | 0.95%   |
| AMD Phenom II X4 955 Processor              | 3        | 0.95%   |
| AMD FX-6300 Six-Core Processor              | 3        | 0.95%   |
| AMD Athlon II X2 270 Processor              | 3        | 0.95%   |
| Intel Xeon CPU E5-1607 v2 @ 3.00GHz         | 2        | 0.63%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 2        | 0.63%   |
| Intel Pentium 4 CPU 3.00GHz                 | 2        | 0.63%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2        | 0.63%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 2        | 0.63%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 0.63%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 2        | 0.63%   |
| Intel Core i5-8500 CPU @ 3.00GHz            | 2        | 0.63%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 2        | 0.63%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 2        | 0.63%   |
| Intel Core i5-4570S CPU @ 2.90GHz           | 2        | 0.63%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 2        | 0.63%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 2        | 0.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 61       | 19.24%  |
| Intel Core i7           | 39       | 12.3%   |
| Intel Core i3           | 30       | 9.46%   |
| AMD Ryzen 5             | 28       | 8.83%   |
| Other                   | 20       | 6.31%   |
| Intel Xeon              | 16       | 5.05%   |
| AMD Ryzen 7             | 16       | 5.05%   |
| Intel Celeron           | 15       | 4.73%   |
| Intel Core 2 Duo        | 10       | 3.15%   |
| Intel Core 2 Quad       | 7        | 2.21%   |
| AMD Ryzen 9             | 7        | 2.21%   |
| AMD FX                  | 7        | 2.21%   |
| AMD Athlon II X2        | 7        | 2.21%   |
| Intel Pentium           | 5        | 1.58%   |
| AMD A8                  | 5        | 1.58%   |
| AMD Ryzen 3             | 4        | 1.26%   |
| AMD Phenom II X4        | 4        | 1.26%   |
| Intel Pentium Dual-Core | 3        | 0.95%   |
| AMD Athlon 64 X2        | 3        | 0.95%   |
| AMD Athlon              | 3        | 0.95%   |
| Intel Pentium 4         | 2        | 0.63%   |
| Intel Atom              | 2        | 0.63%   |
| AMD Ryzen 5 PRO         | 2        | 0.63%   |
| AMD Phenom II X6        | 2        | 0.63%   |
| AMD GX                  | 2        | 0.63%   |
| AMD E1                  | 2        | 0.63%   |
| AMD A6                  | 2        | 0.63%   |
| AMD A10                 | 2        | 0.63%   |
| Intel Pentium Dual      | 1        | 0.32%   |
| Intel Pentium D         | 1        | 0.32%   |
| AMD Turion II Neo       | 1        | 0.32%   |
| AMD Sempron             | 1        | 0.32%   |
| AMD Ryzen Threadripper  | 1        | 0.32%   |
| AMD Ryzen 7 PRO         | 1        | 0.32%   |
| AMD Phenom              | 1        | 0.32%   |
| AMD Athlon X4           | 1        | 0.32%   |
| AMD Athlon II X4        | 1        | 0.32%   |
| AMD Athlon II           | 1        | 0.32%   |
| AMD A4                  | 1        | 0.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 130      | 40.88%  |
| 2      | 83       | 26.1%   |
| 6      | 47       | 14.78%  |
| 8      | 22       | 6.92%   |
| 1      | 8        | 2.52%   |
| 16     | 7        | 2.2%    |
| 12     | 6        | 1.89%   |
| 10     | 4        | 1.26%   |
| 3      | 4        | 1.26%   |
| 24     | 2        | 0.63%   |
| 18     | 2        | 0.63%   |
| 14     | 2        | 0.63%   |
| 20     | 1        | 0.31%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 314      | 99.37%  |
| 2      | 2        | 0.63%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 179      | 56.65%  |
| 1      | 137      | 43.35%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 315      | 99.68%  |
| Unknown        | 1        | 0.32%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 160      | 49.54%  |
| 0x306c3    | 18       | 5.57%   |
| 0x306a9    | 10       | 3.1%    |
| 0x206a7    | 9        | 2.79%   |
| 0x010000c8 | 9        | 2.79%   |
| 0x506e3    | 6        | 1.86%   |
| 0x08701021 | 6        | 1.86%   |
| 0x0800820d | 6        | 1.86%   |
| 0x906ea    | 5        | 1.55%   |
| 0x1067a    | 5        | 1.55%   |
| 0x06000852 | 5        | 1.55%   |
| 0x90672    | 4        | 1.24%   |
| 0x08108109 | 4        | 1.24%   |
| 0xb0671    | 3        | 0.93%   |
| 0x306e4    | 3        | 0.93%   |
| 0x106e5    | 3        | 0.93%   |
| 0x0700010f | 3        | 0.93%   |
| 0xa0653    | 2        | 0.62%   |
| 0x906e9    | 2        | 0.62%   |
| 0x406c3    | 2        | 0.62%   |
| 0x306f2    | 2        | 0.62%   |
| 0x206d7    | 2        | 0.62%   |
| 0x10676    | 2        | 0.62%   |
| 0x0a50000f | 2        | 0.62%   |
| 0x0a20102b | 2        | 0.62%   |
| 0x0a201016 | 2        | 0.62%   |
| 0x08701030 | 2        | 0.62%   |
| 0x08701013 | 2        | 0.62%   |
| 0x08600109 | 2        | 0.62%   |
| 0x010000c7 | 2        | 0.62%   |
| 0xb06e0    | 1        | 0.31%   |
| 0xa0671    | 1        | 0.31%   |
| 0xa0655    | 1        | 0.31%   |
| 0x906ed    | 1        | 0.31%   |
| 0x906eb    | 1        | 0.31%   |
| 0x706a1    | 1        | 0.31%   |
| 0x6fb      | 1        | 0.31%   |
| 0x506c9    | 1        | 0.31%   |
| 0x406c4    | 1        | 0.31%   |
| 0x40651    | 1        | 0.31%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 50       | 15.72%  |
| SandyBridge      | 26       | 8.18%   |
| KabyLake         | 25       | 7.86%   |
| IvyBridge        | 23       | 7.23%   |
| Zen 2            | 21       | 6.6%    |
| K10              | 17       | 5.35%   |
| Zen 3            | 16       | 5.03%   |
| Zen+             | 14       | 4.4%    |
| Penryn           | 14       | 4.4%    |
| Unknown          | 14       | 4.4%    |
| Piledriver       | 12       | 3.77%   |
| Skylake          | 10       | 3.14%   |
| Alderlake Hybrid | 9        | 2.83%   |
| Core             | 8        | 2.52%   |
| CometLake        | 8        | 2.52%   |
| Zen              | 7        | 2.2%    |
| Nehalem          | 7        | 2.2%    |
| Silvermont       | 6        | 1.89%   |
| Westmere         | 5        | 1.57%   |
| Jaguar           | 4        | 1.26%   |
| NetBurst         | 3        | 0.94%   |
| K8 Hammer        | 3        | 0.94%   |
| Excavator        | 3        | 0.94%   |
| Broadwell        | 3        | 0.94%   |
| Steamroller      | 2        | 0.63%   |
| K10 Llano        | 2        | 0.63%   |
| Bonnell          | 2        | 0.63%   |
| Icelake          | 1        | 0.31%   |
| Goldmont plus    | 1        | 0.31%   |
| Goldmont         | 1        | 0.31%   |
| Bobcat           | 1        | 0.31%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 129      | 37.94%  |
| Nvidia                           | 119      | 35%     |
| AMD                              | 91       | 26.76%  |
| Silicon Integrated Systems [SiS] | 1        | 0.29%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 24       | 6.82%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 16       | 4.55%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 14       | 3.98%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 11       | 3.13%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 9        | 2.56%   |
| Intel HD Graphics 530                                                                    | 8        | 2.27%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 7        | 1.99%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 7        | 1.99%   |
| Intel HD Graphics 630                                                                    | 6        | 1.7%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 6        | 1.7%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 6        | 1.7%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 5        | 1.42%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 5        | 1.42%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                                | 5        | 1.42%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 4        | 1.14%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 4        | 1.14%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4        | 1.14%   |
| AMD RS780L [Radeon 3000]                                                                 | 4        | 1.14%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4        | 1.14%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4        | 1.14%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 3        | 0.85%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 3        | 0.85%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 3        | 0.85%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 3        | 0.85%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 3        | 0.85%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 3        | 0.85%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 3        | 0.85%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                               | 3        | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3        | 0.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3        | 0.85%   |
| Intel AlderLake-S GT1                                                                    | 3        | 0.85%   |
| AMD RV620 LE [Radeon HD 3450]                                                            | 3        | 0.85%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 3        | 0.85%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 3        | 0.85%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3        | 0.85%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                                       | 3        | 0.85%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 3        | 0.85%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 3        | 0.85%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 2        | 0.57%   |
| Nvidia GT218 [GeForce 210]                                                               | 2        | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Intel          | 109      | 34.38%  |
| 1 x Nvidia         | 105      | 33.12%  |
| 1 x AMD            | 79       | 24.92%  |
| Intel + Nvidia     | 6        | 1.89%   |
| 2 x AMD            | 5        | 1.58%   |
| AMD + Nvidia       | 5        | 1.58%   |
| Intel + AMD        | 3        | 0.95%   |
| Intel + 2 x Nvidia | 2        | 0.63%   |
| Other              | 1        | 0.32%   |
| 2 x Nvidia         | 1        | 0.32%   |
| 1 x SiS            | 1        | 0.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 227      | 71.38%  |
| Proprietary | 77       | 24.21%  |
| Unknown     | 14       | 4.4%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 182      | 56.7%   |
| 1.01-2.0   | 34       | 10.59%  |
| 0.51-1.0   | 30       | 9.35%   |
| 0.01-0.5   | 26       | 8.1%    |
| 3.01-4.0   | 17       | 5.3%    |
| 7.01-8.0   | 12       | 3.74%   |
| 5.01-6.0   | 10       | 3.12%   |
| 8.01-16.0  | 8        | 2.49%   |
| 2.01-3.0   | 2        | 0.62%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 50       | 15.11%  |
| Samsung Electronics  | 42       | 12.69%  |
| Hewlett-Packard      | 36       | 10.88%  |
| Goldstar             | 28       | 8.46%   |
| AOC                  | 25       | 7.55%   |
| Acer                 | 20       | 6.04%   |
| Ancor Communications | 15       | 4.53%   |
| Philips              | 12       | 3.63%   |
| BenQ                 | 11       | 3.32%   |
| ViewSonic            | 9        | 2.72%   |
| Iiyama               | 9        | 2.72%   |
| Fujitsu Siemens      | 7        | 2.11%   |
| Lenovo               | 6        | 1.81%   |
| Sceptre Tech         | 4        | 1.21%   |
| Eizo                 | 4        | 1.21%   |
| ASUSTek Computer     | 4        | 1.21%   |
| Unknown              | 2        | 0.6%    |
| RTK                  | 2        | 0.6%    |
| NEC Computers        | 2        | 0.6%    |
| Mi                   | 2        | 0.6%    |
| LG Electronics       | 2        | 0.6%    |
| HannStar             | 2        | 0.6%    |
| Denver               | 2        | 0.6%    |
| Unknown              | 2        | 0.6%    |
| ___                  | 1        | 0.3%    |
| YSP                  | 1        | 0.3%    |
| Vestel Elektronik    | 1        | 0.3%    |
| Unknown (AAA)        | 1        | 0.3%    |
| UGD                  | 1        | 0.3%    |
| Toshiba              | 1        | 0.3%    |
| TEO                  | 1        | 0.3%    |
| Tech Concepts        | 1        | 0.3%    |
| TCL                  | 1        | 0.3%    |
| Sony                 | 1        | 0.3%    |
| SNC                  | 1        | 0.3%    |
| Sharp                | 1        | 0.3%    |
| RGT                  | 1        | 0.3%    |
| Pixio                | 1        | 0.3%    |
| Packard Bell         | 1        | 0.3%    |
| OEM                  | 1        | 0.3%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 3        | 0.85%   |
| Lenovo LEN-M82-C LEN00A2 1920x1080 476x268mm 21.5-inch                | 3        | 0.85%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch              | 3        | 0.85%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 3        | 0.85%   |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                    | 3        | 0.85%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                | 2        | 0.56%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                | 2        | 0.56%   |
| Philips 170S PHL082B 1280x1024 338x270mm 17.0-inch                    | 2        | 0.56%   |
| Iiyama PL2377 IVM561D 1920x1080 510x287mm 23.0-inch                   | 2        | 0.56%   |
| Hewlett-Packard w19b/w19e HWP26A1 1440x900 410x256mm 19.0-inch        | 2        | 0.56%   |
| Hewlett-Packard V24i HPN36AC 1920x1080 527x296mm 23.8-inch            | 2        | 0.56%   |
| Hewlett-Packard 2309 HWP2821 1920x1080 510x287mm 23.0-inch            | 2        | 0.56%   |
| HannStar HL205DPB HSD62E0 1600x900 430x240mm 19.4-inch                | 2        | 0.56%   |
| Dell U3011 DEL4065 2560x1600 641x401mm 29.8-inch                      | 2        | 0.56%   |
| Dell S199WFP DELF00A 1440x900 408x255mm 18.9-inch                     | 2        | 0.56%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                     | 2        | 0.56%   |
| Dell 2001FP DELA008 1600x1200 367x275mm 18.1-inch                     | 2        | 0.56%   |
| AOC 24G2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 2        | 0.56%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                       | 2        | 0.56%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                       | 2        | 0.56%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                        | 2        | 0.56%   |
| AOC 1950W AOC1950 1366x768 410x230mm 18.5-inch                        | 2        | 0.56%   |
| Ancor Communications VE228 ACI22FA 1920x1080 477x268mm 21.5-inch      | 2        | 0.56%   |
| Ancor Communications ASUS VS229 ACI22C2 1920x1080 477x268mm 21.5-inch | 2        | 0.56%   |
| Unknown                                                               | 2        | 0.56%   |
| ___ LCD Monitor ___1BBC 1920x540 140x90mm 6.6-inch                    | 1        | 0.28%   |
| YSP MF215BH YSP2150 1920x1080 340x255mm 16.7-inch                     | 1        | 0.28%   |
| ViewSonic XG2401 SERIES VSCBB31 1920x1080 531x299mm 24.0-inch         | 1        | 0.28%   |
| ViewSonic VX3276-UHD VSC5138 3840x2160 697x392mm 31.5-inch            | 1        | 0.28%   |
| ViewSonic VX2476 Series VSCD332 1920x1080 527x296mm 23.8-inch         | 1        | 0.28%   |
| ViewSonic VX2452 Series VSCDE2E 1920x1080 521x293mm 23.5-inch         | 1        | 0.28%   |
| ViewSonic VP2365 SERIES VSC7C28 1920x1080 509x286mm 23.0-inch         | 1        | 0.28%   |
| ViewSonic VE710b-2 VSC3919 1280x1024 338x270mm 17.0-inch              | 1        | 0.28%   |
| ViewSonic VA1948 SERIES VSCE827 1440x900 408x255mm 18.9-inch          | 1        | 0.28%   |
| Vestel Elektronik 49FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch | 1        | 0.28%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 1        | 0.28%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1        | 0.28%   |
| Unknown (AAA) LCDTV AAA3393 1360x768 890x500mm 40.2-inch              | 1        | 0.28%   |
| UGD CD220F (H) UGD2210 1920x1080 527x296mm 23.8-inch                  | 1        | 0.28%   |
| Toshiba TV TSB0109 1920x1080 1594x900mm 72.1-inch                     | 1        | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 149      | 45.29%  |
| 1280x1024 (SXGA)   | 26       | 7.9%    |
| 1366x768 (WXGA)    | 21       | 6.38%   |
| 2560x1440 (QHD)    | 19       | 5.78%   |
| 3840x2160 (4K)     | 18       | 5.47%   |
| 1600x900 (HD+)     | 16       | 4.86%   |
| 1680x1050 (WSXGA+) | 15       | 4.56%   |
| 1440x900 (WXGA+)   | 15       | 4.56%   |
| 1024x768 (XGA)     | 7        | 2.13%   |
| 1920x1200 (WUXGA)  | 6        | 1.82%   |
| 1600x1200          | 5        | 1.52%   |
| 1360x768           | 5        | 1.52%   |
| 3440x1440          | 4        | 1.22%   |
| 2560x1600          | 4        | 1.22%   |
| 2560x1080          | 4        | 1.22%   |
| 3840x1080          | 3        | 0.91%   |
| Unknown            | 3        | 0.91%   |
| 3840x1600          | 2        | 0.61%   |
| 1280x720 (HD)      | 2        | 0.61%   |
| 7680x1080          | 1        | 0.3%    |
| 2288x1287          | 1        | 0.3%    |
| 2256x1504          | 1        | 0.3%    |
| 1920x540           | 1        | 0.3%    |
| 1280x960           | 1        | 0.3%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 56       | 16.67%  |
| 23      | 39       | 11.61%  |
| 27      | 32       | 9.52%   |
| 21      | 32       | 9.52%   |
| 19      | 30       | 8.93%   |
| 18      | 21       | 6.25%   |
| 20      | 18       | 5.36%   |
| 17      | 15       | 4.46%   |
| Unknown | 15       | 4.46%   |
| 31      | 14       | 4.17%   |
| 22      | 10       | 2.98%   |
| 15      | 10       | 2.98%   |
| 34      | 8        | 2.38%   |
| 40      | 5        | 1.49%   |
| 37      | 3        | 0.89%   |
| 32      | 3        | 0.89%   |
| 29      | 3        | 0.89%   |
| 26      | 3        | 0.89%   |
| 25      | 3        | 0.89%   |
| 72      | 2        | 0.6%    |
| 49      | 2        | 0.6%    |
| 28      | 2        | 0.6%    |
| 16      | 2        | 0.6%    |
| 142     | 1        | 0.3%    |
| 84      | 1        | 0.3%    |
| 54      | 1        | 0.3%    |
| 48      | 1        | 0.3%    |
| 42      | 1        | 0.3%    |
| 30      | 1        | 0.3%    |
| 14      | 1        | 0.3%    |
| 6       | 1        | 0.3%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 124      | 37.8%   |
| 401-500        | 100      | 30.49%  |
| 301-350        | 26       | 7.93%   |
| 601-700        | 22       | 6.71%   |
| Unknown        | 15       | 4.57%   |
| 701-800        | 11       | 3.35%   |
| 351-400        | 11       | 3.35%   |
| 801-900        | 8        | 2.44%   |
| 1001-1500      | 4        | 1.22%   |
| 1501-2000      | 3        | 0.91%   |
| More than 2000 | 1        | 0.3%    |
| 201-300        | 1        | 0.3%    |
| 101-200        | 1        | 0.3%    |
| 901-1000       | 1        | 0.3%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 204      | 66.02%  |
| 16/10   | 42       | 13.59%  |
| 5/4     | 24       | 7.77%   |
| 4/3     | 12       | 3.88%   |
| Unknown | 12       | 3.88%   |
| 21/9    | 10       | 3.24%   |
| 32/9    | 2        | 0.65%   |
| 6/5     | 1        | 0.32%   |
| 3/2     | 1        | 0.32%   |
| 1.00    | 1        | 0.32%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 108      | 32.83%  |
| 151-200        | 64       | 19.45%  |
| 141-150        | 35       | 10.64%  |
| 301-350        | 34       | 10.33%  |
| 351-500        | 29       | 8.81%   |
| Unknown        | 15       | 4.56%   |
| 251-300        | 14       | 4.26%   |
| 101-110        | 10       | 3.04%   |
| 501-1000       | 10       | 3.04%   |
| More than 1000 | 6        | 1.82%   |
| 1-40           | 1        | 0.3%    |
| 131-140        | 1        | 0.3%    |
| 111-120        | 1        | 0.3%    |
| 91-100         | 1        | 0.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 215      | 69.35%  |
| 101-120       | 58       | 18.71%  |
| Unknown       | 15       | 4.84%   |
| 121-160       | 12       | 3.87%   |
| 1-50          | 8        | 2.58%   |
| More than 240 | 1        | 0.32%   |
| 161-240       | 1        | 0.32%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 243      | 75.47%  |
| 2     | 54       | 16.77%  |
| 0     | 18       | 5.59%   |
| 3     | 7        | 2.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 204      | 45.43%  |
| Intel                           | 133      | 29.62%  |
| Qualcomm Atheros                | 27       | 6.01%   |
| Ralink Technology               | 13       | 2.9%    |
| Nvidia                          | 8        | 1.78%   |
| Broadcom                        | 7        | 1.56%   |
| TP-Link                         | 5        | 1.11%   |
| Ralink                          | 5        | 1.11%   |
| Broadcom Limited                | 5        | 1.11%   |
| MediaTek                        | 4        | 0.89%   |
| D-Link System                   | 4        | 0.89%   |
| Samsung Electronics             | 3        | 0.67%   |
| NetGear                         | 3        | 0.67%   |
| Marvell Technology Group        | 3        | 0.67%   |
| Qualcomm Atheros Communications | 2        | 0.45%   |
| Microchip Technology            | 2        | 0.45%   |
| D-Link                          | 2        | 0.45%   |
| Belkin Components               | 2        | 0.45%   |
| ASIX Electronics                | 2        | 0.45%   |
| ZyDAS                           | 1        | 0.22%   |
| Zoom Telephonics                | 1        | 0.22%   |
| Xiaomi                          | 1        | 0.22%   |
| Wilocity                        | 1        | 0.22%   |
| TRENDnet                        | 1        | 0.22%   |
| OPPO Electronics                | 1        | 0.22%   |
| Microsoft                       | 1        | 0.22%   |
| MicroPython                     | 1        | 0.22%   |
| Mellanox Technologies           | 1        | 0.22%   |
| Linksys                         | 1        | 0.22%   |
| ICS Advent                      | 1        | 0.22%   |
| Hyperkin                        | 1        | 0.22%   |
| Dell                            | 1        | 0.22%   |
| ASUSTek Computer                | 1        | 0.22%   |
| Aquantia                        | 1        | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 155      | 30.45%  |
| Realtek RTL8125 2.5GbE Controller                                      | 24       | 4.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 17       | 3.34%   |
| Intel I211 Gigabit Network Connection                                  | 13       | 2.55%   |
| Intel Ethernet Connection I217-LM                                      | 13       | 2.55%   |
| Ralink MT7601U Wireless Adapter                                        | 10       | 1.96%   |
| Intel Wi-Fi 6 AX200                                                    | 10       | 1.96%   |
| Intel Ethernet Controller I225-V                                       | 10       | 1.96%   |
| Intel Ethernet Connection (2) I219-V                                   | 10       | 1.96%   |
| Intel Ethernet Connection I217-V                                       | 9        | 1.77%   |
| Nvidia MCP61 Ethernet                                                  | 8        | 1.57%   |
| Realtek 802.11ac NIC                                                   | 7        | 1.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 6        | 1.18%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 6        | 1.18%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 6        | 1.18%   |
| Intel 82579V Gigabit Network Connection                                | 6        | 1.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 5        | 0.98%   |
| Intel Wireless 7260                                                    | 5        | 0.98%   |
| Intel Ethernet Connection (7) I219-V                                   | 5        | 0.98%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 4        | 0.79%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 4        | 0.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 4        | 0.79%   |
| Intel Ethernet Connection (14) I219-V                                  | 4        | 0.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 4        | 0.79%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 3        | 0.59%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 3        | 0.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3        | 0.59%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3        | 0.59%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 3        | 0.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 3        | 0.59%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 3        | 0.59%   |
| Intel Ethernet Connection (2) I218-V                                   | 3        | 0.59%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2        | 0.39%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 2        | 0.39%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter               | 2        | 0.39%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                              | 2        | 0.39%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 2        | 0.39%   |
| Qualcomm Atheros AR9271 802.11n                                        | 2        | 0.39%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 2        | 0.39%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                       | 2        | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 42       | 28.77%  |
| Intel                           | 38       | 26.03%  |
| Qualcomm Atheros                | 21       | 14.38%  |
| Ralink Technology               | 13       | 8.9%    |
| TP-Link                         | 5        | 3.42%   |
| Ralink                          | 5        | 3.42%   |
| NetGear                         | 3        | 2.05%   |
| MediaTek                        | 3        | 2.05%   |
| Qualcomm Atheros Communications | 2        | 1.37%   |
| D-Link System                   | 2        | 1.37%   |
| D-Link                          | 2        | 1.37%   |
| Broadcom                        | 2        | 1.37%   |
| Belkin Components               | 2        | 1.37%   |
| ZyDAS                           | 1        | 0.68%   |
| Wilocity                        | 1        | 0.68%   |
| TRENDnet                        | 1        | 0.68%   |
| Dell                            | 1        | 0.68%   |
| Broadcom Limited                | 1        | 0.68%   |
| ASUSTek Computer                | 1        | 0.68%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                                       | 10       | 6.85%   |
| Intel Wi-Fi 6 AX200                                                                   | 10       | 6.85%   |
| Realtek 802.11ac NIC                                                                  | 7        | 4.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 6        | 4.11%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                             | 6        | 4.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 5        | 3.42%   |
| Intel Wireless 7260                                                                   | 5        | 3.42%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 4        | 2.74%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 4        | 2.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 4        | 2.74%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 4        | 2.74%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                              | 3        | 2.05%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                            | 3        | 2.05%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 3        | 2.05%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                                     | 3        | 2.05%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                              | 2        | 1.37%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 2        | 1.37%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 2        | 1.37%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 2        | 1.37%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 2        | 1.37%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 2        | 1.37%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                      | 2        | 1.37%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                            | 2        | 1.37%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                               | 2        | 1.37%   |
| Intel Wireless 7265                                                                   | 2        | 1.37%   |
| Intel Wireless 3160                                                                   | 2        | 1.37%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                      | 2        | 1.37%   |
| D-Link System DWA-131 802.11n Wireless N Nano Adapter(rev.A1) [Realtek RTL8192SU]     | 2        | 1.37%   |
| Belkin Components F7D1102 N150/Surf Micro Wireless Adapter v1000 [Realtek RTL8188CUS] | 2        | 1.37%   |
| ZyDAS ZD1211B 802.11g                                                                 | 1        | 0.68%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                                    | 1        | 0.68%   |
| TRENDnet TEW-805UB 300Mbps+867Mbps Wireless AC Adapter [Realtek RTL8812AU]            | 1        | 0.68%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                   | 1        | 0.68%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                          | 1        | 0.68%   |
| TP-Link Archer T4U ver.3                                                              | 1        | 0.68%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                | 1        | 0.68%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                            | 1        | 0.68%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                           | 1        | 0.68%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                               | 1        | 0.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1        | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 188      | 54.49%  |
| Intel                    | 115      | 33.33%  |
| Qualcomm Atheros         | 8        | 2.32%   |
| Nvidia                   | 8        | 2.32%   |
| Broadcom                 | 5        | 1.45%   |
| Broadcom Limited         | 4        | 1.16%   |
| Marvell Technology Group | 3        | 0.87%   |
| Samsung Electronics      | 2        | 0.58%   |
| D-Link System            | 2        | 0.58%   |
| ASIX Electronics         | 2        | 0.58%   |
| Xiaomi                   | 1        | 0.29%   |
| OPPO Electronics         | 1        | 0.29%   |
| Microsoft                | 1        | 0.29%   |
| Microchip Technology     | 1        | 0.29%   |
| MediaTek                 | 1        | 0.29%   |
| Linksys                  | 1        | 0.29%   |
| ICS Advent               | 1        | 0.29%   |
| Aquantia                 | 1        | 0.29%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 155      | 43.42%  |
| Realtek RTL8125 2.5GbE Controller                                      | 24       | 6.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 17       | 4.76%   |
| Intel I211 Gigabit Network Connection                                  | 13       | 3.64%   |
| Intel Ethernet Connection I217-LM                                      | 13       | 3.64%   |
| Intel Ethernet Controller I225-V                                       | 10       | 2.8%    |
| Intel Ethernet Connection (2) I219-V                                   | 10       | 2.8%    |
| Intel Ethernet Connection I217-V                                       | 9        | 2.52%   |
| Nvidia MCP61 Ethernet                                                  | 8        | 2.24%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 6        | 1.68%   |
| Intel 82579V Gigabit Network Connection                                | 6        | 1.68%   |
| Intel Ethernet Connection (7) I219-V                                   | 5        | 1.4%    |
| Intel Ethernet Connection (14) I219-V                                  | 4        | 1.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3        | 0.84%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3        | 0.84%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 3        | 0.84%   |
| Intel Ethernet Connection (2) I218-V                                   | 3        | 0.84%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2        | 0.56%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 2        | 0.56%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 2        | 0.56%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2        | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2        | 0.56%   |
| Intel Ethernet Connection (2) I218-LM                                  | 2        | 0.56%   |
| Intel Ethernet Connection (17) I219-V                                  | 2        | 0.56%   |
| Intel 82578DM Gigabit Network Connection                               | 2        | 0.56%   |
| Intel 82578DC Gigabit Network Connection                               | 2        | 0.56%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 2        | 0.56%   |
| Intel 82562V-2 10/100 Network Connection                               | 2        | 0.56%   |
| Intel 82541PI Gigabit Ethernet Controller                              | 2        | 0.56%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                        | 2        | 0.56%   |
| ASIX AX88179 Gigabit Ethernet                                          | 2        | 0.56%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1        | 0.28%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 1        | 0.28%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1        | 0.28%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1        | 0.28%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1        | 0.28%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 1        | 0.28%   |
| OPPO OnePlus Nord 4                                                    | 1        | 0.28%   |
| Microsoft RTL8153 GigE [Surface Ethernet Adapter]                      | 1        | 0.28%   |
| Microchip LAN7500 Ethernet 10/100/1000 Adapter                         | 1        | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 312      | 68.72%  |
| WiFi     | 136      | 29.96%  |
| Modem    | 4        | 0.88%   |
| Unknown  | 2        | 0.44%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 245      | 73.8%   |
| WiFi     | 87       | 26.2%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 204      | 64.15%  |
| 2     | 95       | 29.87%  |
| 3     | 13       | 4.09%   |
| 0     | 4        | 1.26%   |
| 4     | 2        | 0.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 215      | 67.19%  |
| Yes  | 105      | 32.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 35       | 36.08%  |
| Cambridge Silicon Radio         | 23       | 23.71%  |
| Realtek Semiconductor           | 13       | 13.4%   |
| Qualcomm Atheros Communications | 6        | 6.19%   |
| Broadcom                        | 6        | 6.19%   |
| MediaTek                        | 3        | 3.09%   |
| IMC Networks                    | 3        | 3.09%   |
| ASUSTek Computer                | 3        | 3.09%   |
| TP-Link                         | 2        | 2.06%   |
| Lite-On Technology              | 1        | 1.03%   |
| Fujitsu                         | 1        | 1.03%   |
| Foxconn / Hon Hai               | 1        | 1.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 23       | 23.71%  |
| Intel Bluetooth wireless interface                  | 10       | 10.31%  |
| Realtek Bluetooth Radio                             | 9        | 9.28%   |
| Intel AX200 Bluetooth                               | 9        | 9.28%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4        | 4.12%   |
| Intel AX201 Bluetooth                               | 4        | 4.12%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3        | 3.09%   |
| MediaTek Wireless_Device                            | 3        | 3.09%   |
| Intel AX211 Bluetooth                               | 3        | 3.09%   |
| Intel AX210 Bluetooth                               | 3        | 3.09%   |
| IMC Networks Bluetooth Radio                        | 3        | 3.09%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 3        | 3.09%   |
| TP-Link TP-Link Bluetooth USB Adapter               | 2        | 2.06%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 2        | 2.06%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2        | 2.06%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2        | 2.06%   |
| ASUS ASUS USB-BT500                                 | 2        | 2.06%   |
| Realtek RTL8821A Bluetooth                          | 1        | 1.03%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 1.03%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1        | 1.03%   |
| Lite-On Bluetooth Device                            | 1        | 1.03%   |
| Fujitsu Bluetooth Device                            | 1        | 1.03%   |
| Foxconn / Hon Hai Wireless_Device                   | 1        | 1.03%   |
| Broadcom HP Portable Bumble Bee                     | 1        | 1.03%   |
| Broadcom BCM2210 Bluetooth                          | 1        | 1.03%   |
| Broadcom BCM20702A0                                 | 1        | 1.03%   |
| ASUS Bluetooth Device                               | 1        | 1.03%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 209      | 42.48%  |
| AMD                                          | 116      | 23.58%  |
| Nvidia                                       | 107      | 21.75%  |
| Creative Labs                                | 10       | 2.03%   |
| C-Media Electronics                          | 6        | 1.22%   |
| Texas Instruments                            | 3        | 0.61%   |
| Tenx Technology                              | 3        | 0.61%   |
| Logitech                                     | 3        | 0.61%   |
| SAVITECH                                     | 2        | 0.41%   |
| Micro Star International                     | 2        | 0.41%   |
| Medeli Electronics                           | 2        | 0.41%   |
| Focusrite-Novation                           | 2        | 0.41%   |
| Corsair                                      | 2        | 0.41%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.2%    |
| XMOS                                         | 1        | 0.2%    |
| VIA Technologies                             | 1        | 0.2%    |
| STMicroelectronics                           | 1        | 0.2%    |
| Silicon Integrated Systems [SiS]             | 1        | 0.2%    |
| Sennheiser Communications                    | 1        | 0.2%    |
| Samson Technologies                          | 1        | 0.2%    |
| Roland                                       | 1        | 0.2%    |
| Reloop                                       | 1        | 0.2%    |
| Razer USA                                    | 1        | 0.2%    |
| PreSonus Audio Electronics                   | 1        | 0.2%    |
| MAG Technology                               | 1        | 0.2%    |
| M-Audio                                      | 1        | 0.2%    |
| Lenovo                                       | 1        | 0.2%    |
| Kingston Technology                          | 1        | 0.2%    |
| JMTek                                        | 1        | 0.2%    |
| Jieli Technology                             | 1        | 0.2%    |
| Hewlett-Packard                              | 1        | 0.2%    |
| GN Netcom                                    | 1        | 0.2%    |
| Generalplus Technology                       | 1        | 0.2%    |
| FiiO Electronics Technology                  | 1        | 0.2%    |
| DSEA A/S                                     | 1        | 0.2%    |
| Creative Technology                          | 1        | 0.2%    |
| BEHRINGER International                      | 1        | 0.2%    |
| ASUSTek Computer                             | 1        | 0.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 41       | 7.09%   |
| AMD Starship/Matisse HD Audio Controller                                   | 24       | 4.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 23       | 3.98%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 23       | 3.98%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 22       | 3.81%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 21       | 3.63%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 19       | 3.29%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 18       | 3.11%   |
| AMD FCH Azalia Controller                                                  | 16       | 2.77%   |
| Intel 200 Series PCH HD Audio                                              | 12       | 2.08%   |
| Intel Cannon Lake PCH cAVS                                                 | 11       | 1.9%    |
| Intel Alder Lake-S HD Audio Controller                                     | 11       | 1.9%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 11       | 1.9%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 11       | 1.9%    |
| Nvidia GP107GL High Definition Audio Controller                            | 10       | 1.73%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 9        | 1.56%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 9        | 1.56%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9        | 1.56%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 9        | 1.56%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 9        | 1.56%   |
| Nvidia MCP61 High Definition Audio                                         | 8        | 1.38%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 8        | 1.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8        | 1.38%   |
| Nvidia TU116 High Definition Audio Controller                              | 7        | 1.21%   |
| Nvidia GP106 High Definition Audio Controller                              | 6        | 1.04%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 6        | 1.04%   |
| Nvidia GK107 HDMI Audio Controller                                         | 6        | 1.04%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6        | 1.04%   |
| AMD Kabini HDMI/DP Audio                                                   | 6        | 1.04%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 6        | 1.04%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 5        | 0.87%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 5        | 0.87%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 5        | 0.87%   |
| Nvidia GM206 High Definition Audio Controller                              | 4        | 0.69%   |
| Nvidia GF108 High Definition Audio Controller                              | 4        | 0.69%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 4        | 0.69%   |
| Intel Raptor Lake High Definition Audio Controller                         | 4        | 0.69%   |
| AMD Navi 10 HDMI Audio                                                     | 4        | 0.69%   |
| Tenx Technology USB AUDIO                                                  | 3        | 0.52%   |
| Nvidia TU106 High Definition Audio Controller                              | 3        | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 45       | 16.61%  |
| Unknown             | 37       | 13.65%  |
| Samsung Electronics | 37       | 13.65%  |
| SK hynix            | 32       | 11.81%  |
| Corsair             | 27       | 9.96%   |
| Crucial             | 25       | 9.23%   |
| G.Skill             | 15       | 5.54%   |
| Nanya Technology    | 7        | 2.58%   |
| Unknown             | 7        | 2.58%   |
| Micron Technology   | 6        | 2.21%   |
| Ramaxel Technology  | 5        | 1.85%   |
| Elpida              | 5        | 1.85%   |
| A-DATA Technology   | 4        | 1.48%   |
| Unknown (ABCD)      | 2        | 0.74%   |
| V-Color             | 1        | 0.37%   |
| Unknown (AB)        | 1        | 0.37%   |
| Unknown (0x0B15)    | 1        | 0.37%   |
| Transcend           | 1        | 0.37%   |
| Timetec             | 1        | 0.37%   |
| Smart               | 1        | 0.37%   |
| Silicon Power       | 1        | 0.37%   |
| Ramos Technology    | 1        | 0.37%   |
| Qumo                | 1        | 0.37%   |
| PNY                 | 1        | 0.37%   |
| Mushkin             | 1        | 0.37%   |
| Melco               | 1        | 0.37%   |
| KETECH              | 1        | 0.37%   |
| GLOWAY              | 1        | 0.37%   |
| GIGA-BYTE           | 1        | 0.37%   |
| GeIL                | 1        | 0.37%   |
| ASint Technology    | 1        | 0.37%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Unknown                                                      | 7        | 2.4%    |
| Unknown RAM Module 2GB DIMM SDRAM                            | 4        | 1.37%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 4        | 1.37%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 4        | 1.37%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 3        | 1.03%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s         | 3        | 1.03%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 2000MT/s         | 3        | 1.03%   |
| Nanya RAM NT4GC64B8HG0NF-DI 4GB DIMM DDR3 1600MT/s           | 3        | 1.03%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s        | 3        | 1.03%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 2        | 0.68%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                         | 2        | 0.68%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                         | 2        | 0.68%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 2        | 0.68%   |
| Unknown RAM Module 1GB DIMM 800MT/s                          | 2        | 0.68%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM DDR3 2400MT/s | 2        | 0.68%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s         | 2        | 0.68%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s         | 2        | 0.68%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s         | 2        | 0.68%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 2000MT/s          | 2        | 0.68%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s          | 2        | 0.68%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s          | 2        | 0.68%   |
| Samsung RAM M378B5173DB0-CK0 4096MB DIMM DDR3 1600MT/s       | 2        | 0.68%   |
| Samsung RAM M3 78T5663QZ3-CF7 2GB DIMM DDR2 800MT/s          | 2        | 0.68%   |
| Ramaxel RAM RMUA5120ME86H9F-2666 4GB DIMM DDR4 2667MT/s      | 2        | 0.68%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s            | 2        | 0.68%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s          | 2        | 0.68%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s          | 2        | 0.68%   |
| Kingston RAM 9905713-026.A00G 4GB DIMM DDR4 2667MT/s         | 2        | 0.68%   |
| Crucial RAM BLS8G4D26BFSEK.8FBD 8GB DIMM DDR4 2666MT/s       | 2        | 0.68%   |
| Crucial RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3 1600MT/s        | 2        | 0.68%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1800MT/s          | 2        | 0.68%   |
| Corsair RAM CML16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s        | 2        | 0.68%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s        | 2        | 0.68%   |
| V-Color RAM TN4G8C11-H11 4GB DIMM DDR3 1600MT/s              | 1        | 0.34%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                    | 1        | 0.34%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                         | 1        | 0.34%   |
| Unknown RAM Module 4GB DIMM SDRAM                            | 1        | 0.34%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                         | 1        | 0.34%   |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                     | 1        | 0.34%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                    | 1        | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 93       | 39.91%  |
| DDR4    | 89       | 38.2%   |
| Unknown | 14       | 6.01%   |
| DDR2    | 12       | 5.15%   |
| SDRAM   | 11       | 4.72%   |
| DDR5    | 7        | 3%      |
| DRAM    | 3        | 1.29%   |
| LPDDR4  | 2        | 0.86%   |
| LPDDR3  | 1        | 0.43%   |
| DDR     | 1        | 0.43%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 207      | 92%     |
| SODIMM | 18       | 8%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 78       | 31.71%  |
| 4096  | 74       | 30.08%  |
| 16384 | 45       | 18.29%  |
| 2048  | 31       | 12.6%   |
| 1024  | 9        | 3.66%   |
| 32768 | 7        | 2.85%   |
| 512   | 2        | 0.81%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 59       | 23.05%  |
| 1333    | 29       | 11.33%  |
| 3200    | 23       | 8.98%   |
| 2667    | 18       | 7.03%   |
| 2400    | 18       | 7.03%   |
| 3600    | 13       | 5.08%   |
| 800     | 8        | 3.13%   |
| 2666    | 7        | 2.73%   |
| 2133    | 7        | 2.73%   |
| Unknown | 7        | 2.73%   |
| 2000    | 5        | 1.95%   |
| 1867    | 5        | 1.95%   |
| 1866    | 5        | 1.95%   |
| 1800    | 5        | 1.95%   |
| 667     | 5        | 1.95%   |
| 3466    | 3        | 1.17%   |
| 3000    | 3        | 1.17%   |
| 1066    | 3        | 1.17%   |
| 6000    | 2        | 0.78%   |
| 5600    | 2        | 0.78%   |
| 4800    | 2        | 0.78%   |
| 4000    | 2        | 0.78%   |
| 3800    | 2        | 0.78%   |
| 3733    | 2        | 0.78%   |
| 3400    | 2        | 0.78%   |
| 1639    | 2        | 0.78%   |
| 1067    | 2        | 0.78%   |
| 55438   | 1        | 0.39%   |
| 52217   | 1        | 0.39%   |
| 5354    | 1        | 0.39%   |
| 5200    | 1        | 0.39%   |
| 3333    | 1        | 0.39%   |
| 3266    | 1        | 0.39%   |
| 3020    | 1        | 0.39%   |
| 2800    | 1        | 0.39%   |
| 2733    | 1        | 0.39%   |
| 2200    | 1        | 0.39%   |
| 2134    | 1        | 0.39%   |
| 1648    | 1        | 0.39%   |
| 1632    | 1        | 0.39%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 7        | 36.84%  |
| Samsung Electronics | 3        | 15.79%  |
| Brother Industries  | 3        | 15.79%  |
| Seiko Epson         | 2        | 10.53%  |
| Zebra               | 1        | 5.26%   |
| Kyocera             | 1        | 5.26%   |
| Canon               | 1        | 5.26%   |
| Belkin Components   | 1        | 5.26%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Zebra ZTC ZP 500 (ZPL)                 | 1        | 5.26%   |
| Seiko Epson L3150 Series               | 1        | 5.26%   |
| Seiko Epson L120 Series                | 1        | 5.26%   |
| Samsung SF-760 Series                  | 1        | 5.26%   |
| Samsung ML-1865                        | 1        | 5.26%   |
| Samsung ML-1630 Series                 | 1        | 5.26%   |
| Kyocera FS-1300D                       | 1        | 5.26%   |
| HP LaserJet P1102                      | 1        | 5.26%   |
| HP LaserJet 400 M401n                  | 1        | 5.26%   |
| HP DeskJet F4100 Printer series        | 1        | 5.26%   |
| HP DeskJet D1360                       | 1        | 5.26%   |
| HP DeskJet 840c                        | 1        | 5.26%   |
| HP DeskJet 810c/812c                   | 1        | 5.26%   |
| HP Deskjet 3070 B611 series            | 1        | 5.26%   |
| Canon TS3500 series                    | 1        | 5.26%   |
| Brother QL-560 Label Printer           | 1        | 5.26%   |
| Brother HL-2030 Laser Printer          | 1        | 5.26%   |
| Brother DCP-7040                       | 1        | 5.26%   |
| Belkin Components IEEE-1284 Controller | 1        | 5.26%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 4        | 66.67%  |
| Seiko Epson     | 1        | 16.67%  |
| Hewlett-Packard | 1        | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Canon CanoScan LiDE 100                | 2        | 33.33%  |
| Seiko Epson GT-9800F [Perfection 3200] | 1        | 16.67%  |
| HP ScanJet 7400c                       | 1        | 16.67%  |
| Canon CanoScan LIDE 25                 | 1        | 16.67%  |
| Canon CanoScan LiDE 110                | 1        | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech                    | 21       | 37.5%   |
| Microdia                    | 6        | 10.71%  |
| Microsoft                   | 3        | 5.36%   |
| Chicony Electronics         | 3        | 5.36%   |
| Z-Star Microelectronics     | 2        | 3.57%   |
| Samsung Electronics         | 2        | 3.57%   |
| Realtek Semiconductor       | 2        | 3.57%   |
| KYE Systems (Mouse Systems) | 2        | 3.57%   |
| Jieli Technology            | 2        | 3.57%   |
| Xiaomi                      | 1        | 1.79%   |
| Web Camera                  | 1        | 1.79%   |
| Silicon Motion              | 1        | 1.79%   |
| Ruision                     | 1        | 1.79%   |
| Quanta                      | 1        | 1.79%   |
| MacroSilicon                | 1        | 1.79%   |
| IMC Networks                | 1        | 1.79%   |
| Guillemot                   | 1        | 1.79%   |
| GenesysLogic Technology     | 1        | 1.79%   |
| Generalplus Technology      | 1        | 1.79%   |
| Creative Technology         | 1        | 1.79%   |
| Apple                       | 1        | 1.79%   |
| AME Optimedia Technology    | 1        | 1.79%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Logitech Webcam C270                           | 5        | 8.93%   |
| Logitech HD Pro Webcam C920                    | 3        | 5.36%   |
| Logitech C922 Pro Stream Webcam                | 3        | 5.36%   |
| Samsung Galaxy series, misc. (MTP mode)        | 2        | 3.57%   |
| Realtek FULL HD 1080P Webcam                   | 2        | 3.57%   |
| Microdia Webcam Vitade AF                      | 2        | 3.57%   |
| Microdia USB 2.0 Camera                        | 2        | 3.57%   |
| Logitech HD Webcam C525                        | 2        | 3.57%   |
| Logitech BRIO Ultra HD Webcam                  | 2        | 3.57%   |
| Z-Star Vimicro USB2.0 Camera                   | 1        | 1.79%   |
| Z-Star Vimicro USB Camera (Altair)             | 1        | 1.79%   |
| Xiaomi Mi/Redmi series (PTP)                   | 1        | 1.79%   |
| Web Camera Web Camera                          | 1        | 1.79%   |
| Silicon Motion 300k Pixel Camera               | 1        | 1.79%   |
| Ruision UVC Camera                             | 1        | 1.79%   |
| Quanta HP HD Camera                            | 1        | 1.79%   |
| Microsoft MicrosoftÂ LifeCam Studio           | 1        | 1.79%   |
| Microsoft LifeCam VX-800                       | 1        | 1.79%   |
| Microsoft LifeCam VX-2000                      | 1        | 1.79%   |
| Microdia Sonix USB 2.0 Camera                  | 1        | 1.79%   |
| Microdia Camera                                | 1        | 1.79%   |
| MacroSilicon MS210x Video Grabber [EasierCAP]  | 1        | 1.79%   |
| Logitech Webcam C310                           | 1        | 1.79%   |
| Logitech Webcam C300                           | 1        | 1.79%   |
| Logitech Webcam C170                           | 1        | 1.79%   |
| Logitech Webcam C110                           | 1        | 1.79%   |
| Logitech Webcam B500                           | 1        | 1.79%   |
| Logitech QuickCam Pro 5000                     | 1        | 1.79%   |
| KYE Systems (Mouse Systems) iSlim 2020AF       | 1        | 1.79%   |
| KYE Systems (Mouse Systems) Genius FaceCam 320 | 1        | 1.79%   |
| Jieli USB PHY 2.0                              | 1        | 1.79%   |
| Jieli USB Composite Device                     | 1        | 1.79%   |
| IMC Networks USB2.0 UVC HD Webcam              | 1        | 1.79%   |
| Guillemot Hercules Dualpix Exchange            | 1        | 1.79%   |
| GenesysLogic USB2.0 UVC PC Camera              | 1        | 1.79%   |
| Generalplus GENERAL WEBCAM                     | 1        | 1.79%   |
| Creative Live! Cam Sync 1080p                  | 1        | 1.79%   |
| Chicony Integrated_Webcam_1.3M                 | 1        | 1.79%   |
| Chicony Integrated Camera                      | 1        | 1.79%   |
| Chicony HP High Definition 1MP Webcam          | 1        | 1.79%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Reiner SCT Kartensysteme | 1        | 50%     |
| In Focus Systems         | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Reiner SCT Kartensysteme cyberJack one | 1        | 50%     |
| In Focus Systems EMV Smartcard Reader  | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 268      | 83.49%  |
| 1     | 46       | 14.33%  |
| 2     | 5        | 1.56%   |
| 3     | 2        | 0.62%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 26       | 44.83%  |
| Unassigned class         | 6        | 10.34%  |
| Net/wireless             | 5        | 8.62%   |
| Camera                   | 4        | 6.9%    |
| Network                  | 3        | 5.17%   |
| Net/ethernet             | 3        | 5.17%   |
| Sound                    | 2        | 3.45%   |
| Multimedia controller    | 2        | 3.45%   |
| Communication controller | 2        | 3.45%   |
| Chipcard                 | 2        | 3.45%   |
| Storage                  | 1        | 1.72%   |
| Dvb card                 | 1        | 1.72%   |
| Bluetooth                | 1        | 1.72%   |

