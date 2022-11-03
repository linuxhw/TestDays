Gentoo 2.8 - Tested Hardware & Statistics (Desktops)
----------------------------------------------------

A project to collect tested hardware configurations for Gentoo 2.8.

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

Total: 193

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock   | N68C-GS UCC                 | [9430ecf81c](https://linux-hardware.org/?probe=9430ecf81c) | Nov 02, 2022 |
| ASUSTek  | M3A78-CM                    | [5f81698e9a](https://linux-hardware.org/?probe=5f81698e9a) | Nov 02, 2022 |
| MSI      | MEG X570 UNIFY              | [1a88842782](https://linux-hardware.org/?probe=1a88842782) | Nov 01, 2022 |
| Gigabyte | X570 AORUS ELITE            | [966eb5bb18](https://linux-hardware.org/?probe=966eb5bb18) | Oct 31, 2022 |
| Gigabyte | X570 AORUS ELITE            | [860f45c4c1](https://linux-hardware.org/?probe=860f45c4c1) | Oct 31, 2022 |
| Gigabyte | AB350-Gaming-CF             | [c085788e44](https://linux-hardware.org/?probe=c085788e44) | Oct 31, 2022 |
| ASUSTek  | ROG STRIX X570-E GAMING     | [98fe919d0e](https://linux-hardware.org/?probe=98fe919d0e) | Oct 29, 2022 |
| ASUSTek  | ROG STRIX X570-E GAMING     | [9a6e9239e1](https://linux-hardware.org/?probe=9a6e9239e1) | Oct 29, 2022 |
| Gigabyte | X570 AORUS ELITE            | [836d9e4de1](https://linux-hardware.org/?probe=836d9e4de1) | Oct 29, 2022 |
| Gigabyte | X570 AORUS ELITE            | [b7b7481628](https://linux-hardware.org/?probe=b7b7481628) | Oct 29, 2022 |
| ASUSTek  | PRIME B550M-A               | [64e6199c96](https://linux-hardware.org/?probe=64e6199c96) | Oct 25, 2022 |
| ASUSTek  | ROG STRIX X670E-E GAMING... | [cc2fc1e863](https://linux-hardware.org/?probe=cc2fc1e863) | Oct 24, 2022 |
| ASUSTek  | M3A78-CM                    | [ce77ed764b](https://linux-hardware.org/?probe=ce77ed764b) | Oct 24, 2022 |
| Gigabyte | AB350-Gaming-CF             | [d18380bf4c](https://linux-hardware.org/?probe=d18380bf4c) | Oct 24, 2022 |
| Gigabyte | TRX40 DESIGNARE             | [16f90b14dc](https://linux-hardware.org/?probe=16f90b14dc) | Oct 22, 2022 |
| ASUSTek  | TUF Gaming X570-PLUS        | [b89b177dd7](https://linux-hardware.org/?probe=b89b177dd7) | Oct 22, 2022 |
| Gigabyte | F2A88XM-DS2                 | [d066cccd5a](https://linux-hardware.org/?probe=d066cccd5a) | Oct 19, 2022 |
| MSI      | B450M PRO-VDH MAX           | [71ab3d919c](https://linux-hardware.org/?probe=71ab3d919c) | Oct 18, 2022 |
| ASUSTek  | M3A78-CM                    | [e8377da07e](https://linux-hardware.org/?probe=e8377da07e) | Oct 17, 2022 |
| Gigabyte | Z370 AORUS Gaming 5-CF      | [843e47e886](https://linux-hardware.org/?probe=843e47e886) | Oct 14, 2022 |
| ASUSTek  | M4A89GTD-PRO/USB3           | [f57f16d11b](https://linux-hardware.org/?probe=f57f16d11b) | Oct 13, 2022 |
| ASUSTek  | M4A89GTD-PRO/USB3           | [55e6578ade](https://linux-hardware.org/?probe=55e6578ade) | Oct 13, 2022 |
| Gigabyte | H81M-H                      | [63731688d0](https://linux-hardware.org/?probe=63731688d0) | Oct 13, 2022 |
| ASUSTek  | ROG STRIX X670E-I GAMING... | [11fb952122](https://linux-hardware.org/?probe=11fb952122) | Oct 10, 2022 |
| ASUSTek  | M3A78-CM                    | [b04149c5ea](https://linux-hardware.org/?probe=b04149c5ea) | Oct 10, 2022 |
| Gigabyte | AB350-Gaming-CF             | [d7bcf0afa3](https://linux-hardware.org/?probe=d7bcf0afa3) | Oct 09, 2022 |
| ASUSTek  | M3A78-CM                    | [6437ed8b0e](https://linux-hardware.org/?probe=6437ed8b0e) | Oct 03, 2022 |
| Gigabyte | AB350-Gaming-CF             | [60bab6fe12](https://linux-hardware.org/?probe=60bab6fe12) | Oct 02, 2022 |
| ASUSTek  | ROG STRIX Z590-E GAMING ... | [b3b8d3e04f](https://linux-hardware.org/?probe=b3b8d3e04f) | Sep 26, 2022 |
| ASUSTek  | ROG STRIX Z590-E GAMING ... | [9795d4f9aa](https://linux-hardware.org/?probe=9795d4f9aa) | Sep 26, 2022 |
| ASUSTek  | M3A78-CM                    | [6d3f575c3d](https://linux-hardware.org/?probe=6d3f575c3d) | Sep 26, 2022 |
| Gigabyte | AB350-Gaming-CF             | [c447921f07](https://linux-hardware.org/?probe=c447921f07) | Sep 25, 2022 |
| ASRock   | J3160M                      | [c9cc54f48e](https://linux-hardware.org/?probe=c9cc54f48e) | Sep 25, 2022 |
| ASUSTek  | ROG STRIX X570-I GAMING     | [d22f082243](https://linux-hardware.org/?probe=d22f082243) | Sep 21, 2022 |
| ASUSTek  | ROG STRIX X570-I GAMING     | [e4f1a8245a](https://linux-hardware.org/?probe=e4f1a8245a) | Sep 21, 2022 |
| ASUSTek  | AM1M-A                      | [a6e61a9993](https://linux-hardware.org/?probe=a6e61a9993) | Sep 19, 2022 |
| ASUSTek  | M3A78-CM                    | [eb1c0556c3](https://linux-hardware.org/?probe=eb1c0556c3) | Sep 19, 2022 |
| Gigabyte | AB350-Gaming-CF             | [5a9ab0de04](https://linux-hardware.org/?probe=5a9ab0de04) | Sep 18, 2022 |
| ASUSTek  | ROG STRIX B550-F GAMING     | [d4d8cc3f34](https://linux-hardware.org/?probe=d4d8cc3f34) | Sep 16, 2022 |
| Gigabyte | Z590 UD                     | [475ed7f917](https://linux-hardware.org/?probe=475ed7f917) | Sep 15, 2022 |
| ASUSTek  | ROG STRIX B450-F GAMING     | [7ad1180946](https://linux-hardware.org/?probe=7ad1180946) | Sep 14, 2022 |
| ASUSTek  | M3A78-CM                    | [225bd59ba7](https://linux-hardware.org/?probe=225bd59ba7) | Sep 12, 2022 |
| Gigabyte | AB350-Gaming-CF             | [ed5273b278](https://linux-hardware.org/?probe=ed5273b278) | Sep 11, 2022 |
| Intel    | X79G V2.x                   | [3cb7aa6549](https://linux-hardware.org/?probe=3cb7aa6549) | Sep 11, 2022 |
| MSI      | B450M MORTAR                | [2e0d41f272](https://linux-hardware.org/?probe=2e0d41f272) | Sep 10, 2022 |
| MSI      | B450M MORTAR                | [06ee689632](https://linux-hardware.org/?probe=06ee689632) | Sep 10, 2022 |
| ASUSTek  | ROG CROSSHAIR VIII HERO     | [5cfe072b9c](https://linux-hardware.org/?probe=5cfe072b9c) | Sep 10, 2022 |
| ASRock   | Z390 Phantom Gaming 4S      | [146e7ebf49](https://linux-hardware.org/?probe=146e7ebf49) | Sep 08, 2022 |
| Gigabyte | B660 GAMING X AX DDR4       | [3d12a72937](https://linux-hardware.org/?probe=3d12a72937) | Sep 06, 2022 |
| MSI      | B450 TOMAHAWK MAX II        | [cc1fde17e8](https://linux-hardware.org/?probe=cc1fde17e8) | Sep 06, 2022 |
| Gigabyte | AB350-Gaming-CF             | [1d90e3b685](https://linux-hardware.org/?probe=1d90e3b685) | Sep 05, 2022 |
| ASUSTek  | M3A78-CM                    | [d146908413](https://linux-hardware.org/?probe=d146908413) | Aug 31, 2022 |
| ASRock   | X370 Gaming X               | [e915bb3a8c](https://linux-hardware.org/?probe=e915bb3a8c) | Aug 29, 2022 |
| Gigabyte | AB350-Gaming-CF             | [499889da7e](https://linux-hardware.org/?probe=499889da7e) | Aug 28, 2022 |
| ASRock   | X370 Gaming X               | [489691c2e3](https://linux-hardware.org/?probe=489691c2e3) | Aug 28, 2022 |
| Lenovo   | 3716 SDK0R32862 WIN 3258... | [7e810b23be](https://linux-hardware.org/?probe=7e810b23be) | Aug 26, 2022 |
| Gigabyte | Z77X-D3H                    | [294fe7d6c8](https://linux-hardware.org/?probe=294fe7d6c8) | Aug 24, 2022 |
| Gigabyte | Z77X-D3H                    | [2952e542e1](https://linux-hardware.org/?probe=2952e542e1) | Aug 24, 2022 |
| ASUSTek  | TUF Gaming X570-PLUS        | [0df091061c](https://linux-hardware.org/?probe=0df091061c) | Aug 24, 2022 |
| ASUSTek  | M3A78-CM                    | [d22f756c4c](https://linux-hardware.org/?probe=d22f756c4c) | Aug 24, 2022 |
| ASUSTek  | TUF Gaming X570-PLUS        | [0c80683e2a](https://linux-hardware.org/?probe=0c80683e2a) | Aug 23, 2022 |
| Gigabyte | AB350-Gaming-CF             | [f38202db0d](https://linux-hardware.org/?probe=f38202db0d) | Aug 21, 2022 |
| MSI      | Z590-A PRO                  | [8445aa0041](https://linux-hardware.org/?probe=8445aa0041) | Aug 20, 2022 |
| ASUSTek  | M3A78-CM                    | [1ea309e90c](https://linux-hardware.org/?probe=1ea309e90c) | Aug 17, 2022 |
| Gigabyte | B450 GAMING X               | [80760b8e4b](https://linux-hardware.org/?probe=80760b8e4b) | Aug 16, 2022 |
| Gigabyte | AB350-Gaming-CF             | [48637ddb10](https://linux-hardware.org/?probe=48637ddb10) | Aug 14, 2022 |
| MSI      | B450 TOMAHAWK               | [8d95c82a1d](https://linux-hardware.org/?probe=8d95c82a1d) | Aug 12, 2022 |
| MSI      | B450 GAMING PRO CARBON A... | [7d7ceef044](https://linux-hardware.org/?probe=7d7ceef044) | Aug 12, 2022 |
| Unknown  | QNAP TS-221                 | [8d3f7ca9cf](https://linux-hardware.org/?probe=8d3f7ca9cf) | Aug 10, 2022 |
| ASUSTek  | PRIME Z390-A                | [2781a13b80](https://linux-hardware.org/?probe=2781a13b80) | Aug 10, 2022 |
| ASRock   | P67 Extreme4 Gen3           | [b94e1be5ab](https://linux-hardware.org/?probe=b94e1be5ab) | Aug 09, 2022 |
| ASUSTek  | M3A78-CM                    | [1f10876798](https://linux-hardware.org/?probe=1f10876798) | Aug 08, 2022 |
| Gigabyte | AB350-Gaming-CF             | [ac538e23dc](https://linux-hardware.org/?probe=ac538e23dc) | Aug 07, 2022 |
| ASUSTek  | TUF B450M-PLUS GAMING       | [3e7a65077d](https://linux-hardware.org/?probe=3e7a65077d) | Aug 06, 2022 |
| Gigabyte | B450 GAMING X               | [b875ef6dbf](https://linux-hardware.org/?probe=b875ef6dbf) | Aug 04, 2022 |
| ASUSTek  | ROG STRIX X570-E GAMING     | [3db1e1ee37](https://linux-hardware.org/?probe=3db1e1ee37) | Aug 03, 2022 |
| Gigabyte | B550M DS3H                  | [69188053f5](https://linux-hardware.org/?probe=69188053f5) | Aug 02, 2022 |
| ASRock   | B75M-GL R2.0                | [eed9f05678](https://linux-hardware.org/?probe=eed9f05678) | Aug 01, 2022 |
| ASUSTek  | ROG Maximus Z690 EXTREME    | [effa59ed64](https://linux-hardware.org/?probe=effa59ed64) | Aug 01, 2022 |
| ASRock   | B550M Steel Legend          | [0ac4f27d0f](https://linux-hardware.org/?probe=0ac4f27d0f) | Jul 31, 2022 |
| ASUSTek  | TUF Gaming X570-PLUS        | [f22250f00c](https://linux-hardware.org/?probe=f22250f00c) | Jul 31, 2022 |
| ASUSTek  | M3A78-CM                    | [1051593809](https://linux-hardware.org/?probe=1051593809) | Jul 31, 2022 |
| Gigabyte | 970A-DS3                    | [78f00bd2aa](https://linux-hardware.org/?probe=78f00bd2aa) | Jul 30, 2022 |
| Lenovo   | 1046 SDK0T08861 WIN 3305... | [d3d824f468](https://linux-hardware.org/?probe=d3d824f468) | Jul 29, 2022 |
| MSI      | B450M MORTAR                | [29a26324b9](https://linux-hardware.org/?probe=29a26324b9) | Jul 29, 2022 |
| Intel    | D54250WYK H13922-303        | [5ff32931fa](https://linux-hardware.org/?probe=5ff32931fa) | Jul 27, 2022 |
| MSI      | MPG Z390 GAMING PRO CARB... | [dc7eff27cf](https://linux-hardware.org/?probe=dc7eff27cf) | Jul 26, 2022 |
| ASRock   | X399 Taichi                 | [d2eb8a032b](https://linux-hardware.org/?probe=d2eb8a032b) | Jul 26, 2022 |
| ASUSTek  | ROG Maximus XI HERO         | [c98fed5f84](https://linux-hardware.org/?probe=c98fed5f84) | Jul 25, 2022 |
| ASUSTek  | ROG Maximus Z690 EXTREME    | [dae325b47b](https://linux-hardware.org/?probe=dae325b47b) | Jul 25, 2022 |
| ASUSTek  | M3A78-CM                    | [e1e16aa154](https://linux-hardware.org/?probe=e1e16aa154) | Jul 25, 2022 |
| Gigabyte | AB350-Gaming-CF             | [153acd77c2](https://linux-hardware.org/?probe=153acd77c2) | Jul 24, 2022 |
| ASRock   | AM1H-ITX                    | [a15c82ba0c](https://linux-hardware.org/?probe=a15c82ba0c) | Jul 24, 2022 |
| Unknown  | QNAP TS-221                 | [fb3741faab](https://linux-hardware.org/?probe=fb3741faab) | Jul 21, 2022 |
| ASRock   | X570 Taichi                 | [56d5853243](https://linux-hardware.org/?probe=56d5853243) | Jul 19, 2022 |
| MSI      | MEG X570 UNIFY              | [d3d26541f1](https://linux-hardware.org/?probe=d3d26541f1) | Jul 19, 2022 |
| Gigabyte | AB350-Gaming-CF             | [8f2f1582e8](https://linux-hardware.org/?probe=8f2f1582e8) | Jul 17, 2022 |
| ASUSTek  | M3A78-CM                    | [056d74f1a9](https://linux-hardware.org/?probe=056d74f1a9) | Jul 17, 2022 |
| ASUSTek  | ROG STRIX B560-I GAMING ... | [e6b6d3b5e6](https://linux-hardware.org/?probe=e6b6d3b5e6) | Jul 16, 2022 |
| ASUSTek  | ROG STRIX B560-I GAMING ... | [93f8a4ce9f](https://linux-hardware.org/?probe=93f8a4ce9f) | Jul 16, 2022 |
| Gigabyte | Z590 UD                     | [e9e0b50bbb](https://linux-hardware.org/?probe=e9e0b50bbb) | Jul 15, 2022 |
| MSI      | Z87-G45 GAMING              | [8602f7246a](https://linux-hardware.org/?probe=8602f7246a) | Jul 12, 2022 |
| Gigabyte | B450 AORUS M                | [6d15b85193](https://linux-hardware.org/?probe=6d15b85193) | Jul 10, 2022 |
| Dell     | 0J3C2F A02                  | [dccb88852f](https://linux-hardware.org/?probe=dccb88852f) | Jul 10, 2022 |
| ASUSTek  | M3A78-CM                    | [0237c9df10](https://linux-hardware.org/?probe=0237c9df10) | Jul 10, 2022 |
| ASUSTek  | ROG STRIX B550-F GAMING     | [85dbd84c37](https://linux-hardware.org/?probe=85dbd84c37) | Jul 09, 2022 |
| Dell     | 0J3C2F A02                  | [aa87616696](https://linux-hardware.org/?probe=aa87616696) | Jul 09, 2022 |
| ASUSTek  | ROG CROSSHAIR VIII DARK ... | [685e3d36bc](https://linux-hardware.org/?probe=685e3d36bc) | Jul 04, 2022 |
| ASUSTek  | ROG CROSSHAIR VIII DARK ... | [b436712f17](https://linux-hardware.org/?probe=b436712f17) | Jul 04, 2022 |
| ASUSTek  | ROG Maximus XI HERO         | [d442c531e8](https://linux-hardware.org/?probe=d442c531e8) | Jul 03, 2022 |
| Gigabyte | Z690 AORUS MASTER           | [cf8784ac23](https://linux-hardware.org/?probe=cf8784ac23) | Jul 03, 2022 |
| ASUSTek  | PRIME Z390-A                | [1af80d1cdb](https://linux-hardware.org/?probe=1af80d1cdb) | Jul 01, 2022 |
| ASUSTek  | M3A78-CM                    | [4c0fa03f61](https://linux-hardware.org/?probe=4c0fa03f61) | Jun 28, 2022 |
| Gigabyte | AB350-Gaming-CF             | [79dca3a17c](https://linux-hardware.org/?probe=79dca3a17c) | Jun 26, 2022 |
| Fujitsu  | D3417-B2 S26361-D3417-B2    | [f03dcf744a](https://linux-hardware.org/?probe=f03dcf744a) | Jun 26, 2022 |
| Gigabyte | Z590 UD                     | [74060af6fc](https://linux-hardware.org/?probe=74060af6fc) | Jun 23, 2022 |
| Gigabyte | AB350-Gaming-CF             | [2028b239fc](https://linux-hardware.org/?probe=2028b239fc) | Jun 19, 2022 |
| ASUSTek  | M3A78-CM                    | [20c198dd50](https://linux-hardware.org/?probe=20c198dd50) | Jun 19, 2022 |
| ASUSTek  | TUF Gaming X570-PLUS        | [fe7fa5fe7a](https://linux-hardware.org/?probe=fe7fa5fe7a) | Jun 17, 2022 |
| ASUSTek  | M3A78-CM                    | [59350b295e](https://linux-hardware.org/?probe=59350b295e) | Jun 13, 2022 |
| Gigabyte | AB350-Gaming-CF             | [223b882103](https://linux-hardware.org/?probe=223b882103) | Jun 12, 2022 |
| ASUSTek  | ROG STRIX B450-F GAMING     | [80a6dc4a46](https://linux-hardware.org/?probe=80a6dc4a46) | Jun 09, 2022 |
| Pegatron | 2ACE                        | [838cad5bc2](https://linux-hardware.org/?probe=838cad5bc2) | Jun 06, 2022 |
| Dell     | 0KWVT8 A03                  | [5745c8b787](https://linux-hardware.org/?probe=5745c8b787) | Jun 06, 2022 |
| Gigabyte | AB350-Gaming-CF             | [cb81a60917](https://linux-hardware.org/?probe=cb81a60917) | Jun 05, 2022 |
| Unknown  | Unknown                     | [c6f9883076](https://linux-hardware.org/?probe=c6f9883076) | Jun 05, 2022 |
| Unknown  | Unknown                     | [4abb49be35](https://linux-hardware.org/?probe=4abb49be35) | Jun 04, 2022 |
| MSI      | X570-A PRO                  | [102ed915c5](https://linux-hardware.org/?probe=102ed915c5) | Jun 02, 2022 |
| ASUSTek  | TUF Gaming Z690-PLUS WIF... | [2c33cbbbe2](https://linux-hardware.org/?probe=2c33cbbbe2) | May 30, 2022 |
| ASUSTek  | Z170-A                      | [86021dcc38](https://linux-hardware.org/?probe=86021dcc38) | May 27, 2022 |
| ASUSTek  | Z170-A                      | [b8603fccc0](https://linux-hardware.org/?probe=b8603fccc0) | May 26, 2022 |
| MSI      | PRO Z690-A DDR4             | [38ac6de56d](https://linux-hardware.org/?probe=38ac6de56d) | May 25, 2022 |
| ASRock   | B450 Gaming K4              | [af256d7649](https://linux-hardware.org/?probe=af256d7649) | May 24, 2022 |
| ASUSTek  | PRIME X570-PRO              | [f7225b80ed](https://linux-hardware.org/?probe=f7225b80ed) | May 18, 2022 |
| ASUSTek  | PRIME X570-PRO              | [84a0dc5b83](https://linux-hardware.org/?probe=84a0dc5b83) | May 18, 2022 |
| ASUSTek  | ROG Maximus XIII APEX       | [56fb967887](https://linux-hardware.org/?probe=56fb967887) | May 16, 2022 |
| Dell     | 0J3C2F A02                  | [07e2cea31c](https://linux-hardware.org/?probe=07e2cea31c) | May 13, 2022 |
| Gigabyte | Z590 UD                     | [2fcf37c00a](https://linux-hardware.org/?probe=2fcf37c00a) | May 11, 2022 |
| Dell     | 0J3C2F A02                  | [bd6c3ca5b4](https://linux-hardware.org/?probe=bd6c3ca5b4) | May 09, 2022 |
| ASRock   | X370 Gaming X               | [b24677a908](https://linux-hardware.org/?probe=b24677a908) | May 01, 2022 |
| MSI      | MPG Z390 GAMING PRO CARB... | [07a115654d](https://linux-hardware.org/?probe=07a115654d) | Apr 30, 2022 |
| Dell     | 0J37VM A00                  | [76f13aa200](https://linux-hardware.org/?probe=76f13aa200) | Apr 28, 2022 |
| ASUSTek  | ROG STRIX B550-F GAMING     | [6af0b2a3c9](https://linux-hardware.org/?probe=6af0b2a3c9) | Apr 21, 2022 |
| MSI      | Z390-A PRO                  | [4121c8fcc2](https://linux-hardware.org/?probe=4121c8fcc2) | Apr 20, 2022 |
| ASUSTek  | PRIME H570M-PLUS            | [5e6ce90c93](https://linux-hardware.org/?probe=5e6ce90c93) | Apr 13, 2022 |
| MSI      | B450-A PRO MAX              | [cfd276f151](https://linux-hardware.org/?probe=cfd276f151) | Apr 13, 2022 |
| ASUSTek  | ROG Maximus XIII APEX       | [7a26d3fc81](https://linux-hardware.org/?probe=7a26d3fc81) | Apr 12, 2022 |
| Gigabyte | H470 HD3                    | [5ce5c54ecd](https://linux-hardware.org/?probe=5ce5c54ecd) | Apr 09, 2022 |
| ASUSTek  | P6X58D-E                    | [68be7a767a](https://linux-hardware.org/?probe=68be7a767a) | Apr 07, 2022 |
| ASUSTek  | TUF Gaming B550-PLUS        | [403a6830d9](https://linux-hardware.org/?probe=403a6830d9) | Apr 04, 2022 |
| ASRock   | Z170A-X1                    | [9e1cc71d24](https://linux-hardware.org/?probe=9e1cc71d24) | Mar 31, 2022 |
| MSI      | MAG B550M MORTAR            | [9ebb4c0fd3](https://linux-hardware.org/?probe=9ebb4c0fd3) | Mar 31, 2022 |
| Gigabyte | Z590 UD                     | [5cde1a4e83](https://linux-hardware.org/?probe=5cde1a4e83) | Mar 24, 2022 |
| ASUSTek  | ROG STRIX Z370-H GAMING     | [6dddf500c7](https://linux-hardware.org/?probe=6dddf500c7) | Mar 22, 2022 |
| MSI      | MAG B550M MORTAR            | [593bf6f937](https://linux-hardware.org/?probe=593bf6f937) | Mar 21, 2022 |
| ASUSTek  | Z170 PRO GAMING             | [6efb7791bb](https://linux-hardware.org/?probe=6efb7791bb) | Mar 19, 2022 |
| ASUSTek  | ROG STRIX Z390-E GAMING     | [70021af77a](https://linux-hardware.org/?probe=70021af77a) | Mar 15, 2022 |
| Dell     | 0J37VM A00                  | [a78d4c99e3](https://linux-hardware.org/?probe=a78d4c99e3) | Mar 09, 2022 |
| ASUSTek  | TUF Gaming X570-PRO         | [44656b1bd4](https://linux-hardware.org/?probe=44656b1bd4) | Mar 03, 2022 |
| Gigabyte | Z590 UD                     | [a5242ed058](https://linux-hardware.org/?probe=a5242ed058) | Feb 26, 2022 |
| Gigabyte | Z590 UD                     | [071dd25266](https://linux-hardware.org/?probe=071dd25266) | Feb 24, 2022 |
| ASUSTek  | ROG CROSSHAIR VIII DARK ... | [5836ccecc2](https://linux-hardware.org/?probe=5836ccecc2) | Feb 10, 2022 |
| Gigabyte | Z490 UD                     | [b571c22d4f](https://linux-hardware.org/?probe=b571c22d4f) | Feb 04, 2022 |
| MSI      | MPG B550 GAMING PLUS        | [d424a8e145](https://linux-hardware.org/?probe=d424a8e145) | Feb 01, 2022 |
| MSI      | MPG B550 GAMING PLUS        | [89dbe92caf](https://linux-hardware.org/?probe=89dbe92caf) | Feb 01, 2022 |
| ASRock   | AB350M Pro4                 | [6b7cf2d570](https://linux-hardware.org/?probe=6b7cf2d570) | Jan 27, 2022 |
| Gigabyte | B450M S2H                   | [656da02110](https://linux-hardware.org/?probe=656da02110) | Jan 24, 2022 |
| Gigabyte | B450M S2H                   | [1721bed3e1](https://linux-hardware.org/?probe=1721bed3e1) | Jan 24, 2022 |
| Gigabyte | Z490 UD                     | [eac4639ad2](https://linux-hardware.org/?probe=eac4639ad2) | Jan 22, 2022 |
| EVGA     | Z390 DARK                   | [7672395a1c](https://linux-hardware.org/?probe=7672395a1c) | Dec 24, 2021 |
| ASUSTek  | P5LD2-Deluxe                | [a2ee48eeb1](https://linux-hardware.org/?probe=a2ee48eeb1) | Dec 16, 2021 |
| MSI      | MPG Z690 EDGE WIFI DDR4     | [b92f432637](https://linux-hardware.org/?probe=b92f432637) | Dec 07, 2021 |
| MSI      | MPG Z690 EDGE WIFI DDR4     | [d8f50aaa2e](https://linux-hardware.org/?probe=d8f50aaa2e) | Dec 07, 2021 |
| ASUSTek  | TUF B450-PLUS GAMING        | [6649bea1f8](https://linux-hardware.org/?probe=6649bea1f8) | Dec 04, 2021 |
| ASUSTek  | TUF B450-PLUS GAMING        | [723e2a158a](https://linux-hardware.org/?probe=723e2a158a) | Dec 03, 2021 |
| ASRock   | H110M-HDV R3.0              | [e155882ffa](https://linux-hardware.org/?probe=e155882ffa) | Dec 02, 2021 |
| ASUSTek  | ROG STRIX X570-E GAMING     | [e2c087b9c7](https://linux-hardware.org/?probe=e2c087b9c7) | Nov 21, 2021 |
| ASUSTek  | PRIME X570-P                | [eafa22145d](https://linux-hardware.org/?probe=eafa22145d) | Nov 15, 2021 |
| ASUSTek  | TUF GAMING B550-PLUS        | [2900821ed3](https://linux-hardware.org/?probe=2900821ed3) | Nov 14, 2021 |
| ASUSTek  | ROG STRIX B550-F GAMING     | [4cfb74fb42](https://linux-hardware.org/?probe=4cfb74fb42) | Nov 14, 2021 |
| ASUSTek  | ROG ZENITH II EXTREME       | [6f308039a8](https://linux-hardware.org/?probe=6f308039a8) | Nov 06, 2021 |
| MSI      | H110M PRO-D                 | [cb3dcdd186](https://linux-hardware.org/?probe=cb3dcdd186) | Nov 02, 2021 |
| MSI      | H110M PRO-D                 | [b53420c26a](https://linux-hardware.org/?probe=b53420c26a) | Nov 02, 2021 |
| ASUSTek  | ROG STRIX B550-F GAMING     | [161865edb0](https://linux-hardware.org/?probe=161865edb0) | Oct 30, 2021 |
| ASUSTek  | ROG STRIX B550-F GAMING     | [a4806aa50f](https://linux-hardware.org/?probe=a4806aa50f) | Oct 30, 2021 |
| ASUSTek  | Z170-A                      | [aea7d9561e](https://linux-hardware.org/?probe=aea7d9561e) | Oct 29, 2021 |
| ASRock   | X370 Gaming X               | [0f4ae74d8e](https://linux-hardware.org/?probe=0f4ae74d8e) | Oct 29, 2021 |
| ASRock   | X370 Gaming X               | [f3f75352e4](https://linux-hardware.org/?probe=f3f75352e4) | Oct 29, 2021 |
| ASUSTek  | ROG CROSSHAIR VIII HERO     | [e9cc487951](https://linux-hardware.org/?probe=e9cc487951) | Oct 28, 2021 |
| Gigabyte | X570 AORUS MASTER           | [58e3f9c07f](https://linux-hardware.org/?probe=58e3f9c07f) | Oct 23, 2021 |
| ASUSTek  | ROG CROSSHAIR VIII HERO     | [eb02a6d4d5](https://linux-hardware.org/?probe=eb02a6d4d5) | Oct 20, 2021 |
| ASRock   | X370 Killer SLI/ac          | [2e4c1c4527](https://linux-hardware.org/?probe=2e4c1c4527) | Oct 17, 2021 |
| Gigabyte | Z87X-UD3H-CF                | [9901023f19](https://linux-hardware.org/?probe=9901023f19) | Oct 03, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 5.15.59-gentoo               | 6        | 4.48%   |
| 5.15.52-gentoo-x86_64        | 5        | 3.73%   |
| 5.15.41-gentoo               | 5        | 3.73%   |
| 5.15.52-gentoo               | 4        | 2.99%   |
| 5.17.1-gentoo-r1             | 3        | 2.24%   |
| 5.15.59-gentoo-x86_64        | 3        | 2.24%   |
| 5.15.41-gentoo-x86_64        | 3        | 2.24%   |
| 5.19.0-gentoo                | 2        | 1.49%   |
| 5.18.14-gentoo-x86_64        | 2        | 1.49%   |
| 5.18.10-gentoo               | 2        | 1.49%   |
| 5.17.0-gentoo                | 2        | 1.49%   |
| 5.16.11-gentoo-x86_64        | 2        | 1.49%   |
| 5.15.75-gentoo               | 2        | 1.49%   |
| 5.15.74-gentoo               | 2        | 1.49%   |
| 5.15.69-gentoo               | 2        | 1.49%   |
| 5.15.52-gentoo-dist          | 2        | 1.49%   |
| 5.15.10-gentoo               | 2        | 1.49%   |
| 5.14.13-gentoo               | 2        | 1.49%   |
| 5.14.12-gentoo               | 2        | 1.49%   |
| 6.0.6-gentoo_ap              | 1        | 0.75%   |
| 6.0.0-Phaco-g8f10ff49057f    | 1        | 0.75%   |
| 6.0.0                        | 1        | 0.75%   |
| 5.19.9-x86_64                | 1        | 0.75%   |
| 5.19.9-gentoo-x86_64         | 1        | 0.75%   |
| 5.19.9-gentoo                | 1        | 0.75%   |
| 5.19.8-xanmod1               | 1        | 0.75%   |
| 5.19.8-gentoo-clang-lto-prjc | 1        | 0.75%   |
| 5.19.7-gentoo-x86_64         | 1        | 0.75%   |
| 5.19.6-gentoo-x86_64         | 1        | 0.75%   |
| 5.19.16-lqx4-SPStudio        | 1        | 0.75%   |
| 5.19.16-gentoo               | 1        | 0.75%   |
| 5.19.11-renacuajo            | 1        | 0.75%   |
| 5.19.1-gentoo-a6             | 1        | 0.75%   |
| 5.19.0-xanmod1-x86_64        | 1        | 0.75%   |
| 5.19.0-gentoo-x86_64         | 1        | 0.75%   |
| 5.19.0-gentoo-carbon         | 1        | 0.75%   |
| 5.18.9-gentoo-x86_64         | 1        | 0.75%   |
| 5.18.9-gentoo                | 1        | 0.75%   |
| 5.18.7-gentoo                | 1        | 0.75%   |
| 5.18.6-gentoo-x86_64         | 1        | 0.75%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.52 | 12       | 8.96%   |
| 5.15.59 | 9        | 6.72%   |
| 5.15.41 | 9        | 6.72%   |
| 5.19.0  | 5        | 3.73%   |
| 5.18.10 | 4        | 2.99%   |
| 5.17.1  | 4        | 2.99%   |
| 5.15.74 | 4        | 2.99%   |
| 5.19.9  | 3        | 2.24%   |
| 5.18.14 | 3        | 2.24%   |
| 5.17.7  | 3        | 2.24%   |
| 5.17.0  | 3        | 2.24%   |
| 5.15.69 | 3        | 2.24%   |
| 6.0.0   | 2        | 1.49%   |
| 5.19.8  | 2        | 1.49%   |
| 5.19.16 | 2        | 1.49%   |
| 5.18.9  | 2        | 1.49%   |
| 5.18.6  | 2        | 1.49%   |
| 5.18.15 | 2        | 1.49%   |
| 5.17.9  | 2        | 1.49%   |
| 5.17.3  | 2        | 1.49%   |
| 5.17.2  | 2        | 1.49%   |
| 5.16.14 | 2        | 1.49%   |
| 5.16.11 | 2        | 1.49%   |
| 5.15.75 | 2        | 1.49%   |
| 5.15.72 | 2        | 1.49%   |
| 5.15.2  | 2        | 1.49%   |
| 5.15.10 | 2        | 1.49%   |
| 5.14.14 | 2        | 1.49%   |
| 5.14.13 | 2        | 1.49%   |
| 5.14.12 | 2        | 1.49%   |
| 6.0.6   | 1        | 0.75%   |
| 5.19.7  | 1        | 0.75%   |
| 5.19.6  | 1        | 0.75%   |
| 5.19.11 | 1        | 0.75%   |
| 5.19.1  | 1        | 0.75%   |
| 5.18.7  | 1        | 0.75%   |
| 5.18.3  | 1        | 0.75%   |
| 5.18.1  | 1        | 0.75%   |
| 5.18.0  | 1        | 0.75%   |
| 5.17.8  | 1        | 0.75%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 47       | 38.84%  |
| 5.19    | 16       | 13.22%  |
| 5.18    | 16       | 13.22%  |
| 5.17    | 15       | 12.4%   |
| 5.16    | 11       | 9.09%   |
| 5.14    | 9        | 7.44%   |
| 6.0     | 3        | 2.48%   |
| 5.10    | 2        | 1.65%   |
| 4.9     | 1        | 0.83%   |
| 4.14    | 1        | 0.83%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| x86_64   | 108      | 98.18%  |
| ppc      | 1        | 0.91%   |
| armv5tel | 1        | 0.91%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| KDE5     | 37       | 33.04%  |
| Unknown  | 34       | 30.36%  |
| GNOME    | 22       | 19.64%  |
| XFCE     | 7        | 6.25%   |
| MATE     | 4        | 3.57%   |
| DWM      | 2        | 1.79%   |
| Cinnamon | 2        | 1.79%   |
| LXQt     | 1        | 0.89%   |
| KDE      | 1        | 0.89%   |
| i3       | 1        | 0.89%   |
| Hyprland | 1        | 0.89%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 53       | 46.49%  |
| Wayland | 24       | 21.05%  |
| Tty     | 20       | 17.54%  |
| Unknown | 17       | 14.91%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 43       | 38.39%  |
| SDDM    | 35       | 31.25%  |
| GDM     | 14       | 12.5%   |
| LightDM | 12       | 10.71%  |
| LXDM    | 4        | 3.57%   |
| XDM     | 2        | 1.79%   |
| SLiM    | 2        | 1.79%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 41       | 37.27%  |
| en_GB      | 14       | 12.73%  |
| Unknown    | 12       | 10.91%  |
| de_DE      | 8        | 7.27%   |
| C.UTF8     | 7        | 6.36%   |
| ru_RU      | 6        | 5.45%   |
| pl_PL      | 4        | 3.64%   |
| pt_BR      | 2        | 1.82%   |
| es_ES      | 2        | 1.82%   |
| en_CA      | 2        | 1.82%   |
| C          | 2        | 1.82%   |
| zh_TW      | 1        | 0.91%   |
| sl_SI      | 1        | 0.91%   |
| ja_JP      | 1        | 0.91%   |
| it_IT      | 1        | 0.91%   |
| fr_FR      | 1        | 0.91%   |
| es_MX      | 1        | 0.91%   |
| en_US.UTF8 | 1        | 0.91%   |
| el_GR      | 1        | 0.91%   |
| de_CH      | 1        | 0.91%   |
| cs_CZ      | 1        | 0.91%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 96       | 85.71%  |
| BIOS | 16       | 14.29%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 62       | 56.36%  |
| Btrfs    | 27       | 24.55%  |
| F2fs     | 9        | 8.18%   |
| Zfs      | 4        | 3.64%   |
| Xfs      | 4        | 3.64%   |
| XXXXXXX  | 2        | 1.82%   |
| XXX      | 1        | 0.91%   |
| Reiserfs | 1        | 0.91%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 104      | 92.86%  |
| Unknown | 6        | 5.36%   |
| MBR     | 2        | 1.79%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 61       | 54.95%  |
| Yes       | 50       | 45.05%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 61       | 55.45%  |
| Yes       | 49       | 44.55%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 45       | 40.91%  |
| MSI                 | 19       | 17.27%  |
| Gigabyte Technology | 19       | 17.27%  |
| ASRock              | 15       | 13.64%  |
| Dell                | 3        | 2.73%   |
| Lenovo              | 2        | 1.82%   |
| Intel               | 2        | 1.82%   |
| Unknown             | 2        | 1.82%   |
| Pegatron            | 1        | 0.91%   |
| Fujitsu             | 1        | 0.91%   |
| EVGA                | 1        | 0.91%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUS TUF Gaming X570-PLUS           | 3        | 2.73%   |
| ASUS ROG STRIX X570-E GAMING        | 3        | 2.73%   |
| ASUS ROG STRIX B550-F GAMING        | 3        | 2.73%   |
| MSI MS-7C35                         | 2        | 1.82%   |
| MSI MS-7C02                         | 2        | 1.82%   |
| MSI MS-7B89                         | 2        | 1.82%   |
| ASUS Z170-A                         | 2        | 1.82%   |
| ASUS TUF Gaming B550-PLUS           | 2        | 1.82%   |
| ASUS ROG STRIX B450-F GAMING        | 2        | 1.82%   |
| ASUS ROG CROSSHAIR VIII HERO        | 2        | 1.82%   |
| ASUS ROG CROSSHAIR VIII DARK HERO   | 2        | 1.82%   |
| Unknown                             | 2        | 1.82%   |
| Pegatron 810-170st                  | 1        | 0.91%   |
| MSI MS-7D31                         | 1        | 0.91%   |
| MSI MS-7D25                         | 1        | 0.91%   |
| MSI MS-7D09                         | 1        | 0.91%   |
| MSI MS-7C94                         | 1        | 0.91%   |
| MSI MS-7C56                         | 1        | 0.91%   |
| MSI MS-7C37                         | 1        | 0.91%   |
| MSI MS-7B98                         | 1        | 0.91%   |
| MSI MS-7B86                         | 1        | 0.91%   |
| MSI MS-7B85                         | 1        | 0.91%   |
| MSI MS-7B17                         | 1        | 0.91%   |
| MSI MS-7A38                         | 1        | 0.91%   |
| MSI MS-7996                         | 1        | 0.91%   |
| MSI MS-7821                         | 1        | 0.91%   |
| Lenovo ThinkStation P620 30E0001TGE | 1        | 0.91%   |
| Lenovo Legion T5 26AMR5 90RB0002US  | 1        | 0.91%   |
| Intel X79                           | 1        | 0.91%   |
| Intel D54250WYK H13922-303          | 1        | 0.91%   |
| Gigabyte Z87X-UD3H                  | 1        | 0.91%   |
| Gigabyte Z77X-D3H                   | 1        | 0.91%   |
| Gigabyte Z690 AORUS MASTER          | 1        | 0.91%   |
| Gigabyte Z590 UD                    | 1        | 0.91%   |
| Gigabyte Z490 UD                    | 1        | 0.91%   |
| Gigabyte Z370 AORUS Gaming 5        | 1        | 0.91%   |
| Gigabyte X570 AORUS MASTER          | 1        | 0.91%   |
| Gigabyte X570 AORUS ELITE           | 1        | 0.91%   |
| Gigabyte TRX40 DESIGNARE            | 1        | 0.91%   |
| Gigabyte H81M-H                     | 1        | 0.91%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS ROG             | 23       | 20.91%  |
| ASUS TUF             | 9        | 8.18%   |
| ASUS PRIME           | 5        | 4.55%   |
| MSI MS-7C35          | 2        | 1.82%   |
| MSI MS-7C02          | 2        | 1.82%   |
| MSI MS-7B89          | 2        | 1.82%   |
| Gigabyte X570        | 2        | 1.82%   |
| Gigabyte B450        | 2        | 1.82%   |
| Dell OptiPlex        | 2        | 1.82%   |
| ASUS Z170-A          | 2        | 1.82%   |
| ASRock X370          | 2        | 1.82%   |
| Unknown              | 2        | 1.82%   |
| Pegatron 810-170st   | 1        | 0.91%   |
| MSI MS-7D31          | 1        | 0.91%   |
| MSI MS-7D25          | 1        | 0.91%   |
| MSI MS-7D09          | 1        | 0.91%   |
| MSI MS-7C94          | 1        | 0.91%   |
| MSI MS-7C56          | 1        | 0.91%   |
| MSI MS-7C37          | 1        | 0.91%   |
| MSI MS-7B98          | 1        | 0.91%   |
| MSI MS-7B86          | 1        | 0.91%   |
| MSI MS-7B85          | 1        | 0.91%   |
| MSI MS-7B17          | 1        | 0.91%   |
| MSI MS-7A38          | 1        | 0.91%   |
| MSI MS-7996          | 1        | 0.91%   |
| MSI MS-7821          | 1        | 0.91%   |
| Lenovo ThinkStation  | 1        | 0.91%   |
| Lenovo Legion        | 1        | 0.91%   |
| Intel X79            | 1        | 0.91%   |
| Intel D54250WYK      | 1        | 0.91%   |
| Gigabyte Z87X-UD3H   | 1        | 0.91%   |
| Gigabyte Z77X-D3H    | 1        | 0.91%   |
| Gigabyte Z690        | 1        | 0.91%   |
| Gigabyte Z590        | 1        | 0.91%   |
| Gigabyte Z490        | 1        | 0.91%   |
| Gigabyte Z370        | 1        | 0.91%   |
| Gigabyte TRX40       | 1        | 0.91%   |
| Gigabyte H81M-H      | 1        | 0.91%   |
| Gigabyte H470        | 1        | 0.91%   |
| Gigabyte F2A88XM-DS2 | 1        | 0.91%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2019    | 21       | 19.09%  |
| 2020    | 20       | 18.18%  |
| 2018    | 16       | 14.55%  |
| 2021    | 14       | 12.73%  |
| 2017    | 7        | 6.36%   |
| 2013    | 6        | 5.45%   |
| 2022    | 4        | 3.64%   |
| 2016    | 4        | 3.64%   |
| 2014    | 4        | 3.64%   |
| 2015    | 3        | 2.73%   |
| 2011    | 3        | 2.73%   |
| 2012    | 2        | 1.82%   |
| 2010    | 2        | 1.82%   |
| Unknown | 2        | 1.82%   |
| 2008    | 1        | 0.91%   |
| 2005    | 1        | 0.91%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 110      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 108      | 97.3%   |
| Enabled  | 3        | 2.7%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 110      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 47       | 42.73%  |
| 64.01-256.0 | 24       | 21.82%  |
| 16.01-24.0  | 18       | 16.36%  |
| 24.01-32.0  | 7        | 6.36%   |
| 8.01-16.0   | 6        | 5.45%   |
| 4.01-8.0    | 5        | 4.55%   |
| 0.51-1.0    | 2        | 1.82%   |
| 2.01-3.0    | 1        | 0.91%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 32       | 25.4%   |
| 8.01-16.0  | 22       | 17.46%  |
| 2.01-3.0   | 18       | 14.29%  |
| 1.01-2.0   | 17       | 13.49%  |
| 3.01-4.0   | 10       | 7.94%   |
| 16.01-24.0 | 9        | 7.14%   |
| 0.51-1.0   | 7        | 5.56%   |
| 0.01-0.5   | 5        | 3.97%   |
| 24.01-32.0 | 3        | 2.38%   |
| 32.01-64.0 | 2        | 1.59%   |
| 0          | 1        | 0.79%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 34       | 30.36%  |
| 3      | 27       | 24.11%  |
| 4      | 14       | 12.5%   |
| 5      | 13       | 11.61%  |
| 1      | 10       | 8.93%   |
| 6      | 7        | 6.25%   |
| 7      | 5        | 4.46%   |
| 12     | 1        | 0.89%   |
| 9      | 1        | 0.89%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 93       | 83.04%  |
| Yes       | 19       | 16.96%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 108      | 98.18%  |
| No        | 2        | 1.82%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 58       | 52.25%  |
| No        | 53       | 47.75%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 64       | 57.66%  |
| No        | 47       | 42.34%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 29       | 26.36%  |
| Germany     | 20       | 18.18%  |
| Russia      | 10       | 9.09%   |
| Poland      | 9        | 8.18%   |
| UK          | 6        | 5.45%   |
| Canada      | 4        | 3.64%   |
| Switzerland | 3        | 2.73%   |
| Spain       | 3        | 2.73%   |
| Czechia     | 3        | 2.73%   |
| Mexico      | 2        | 1.82%   |
| China       | 2        | 1.82%   |
| Brazil      | 2        | 1.82%   |
| Taiwan      | 1        | 0.91%   |
| Slovenia    | 1        | 0.91%   |
| Slovakia    | 1        | 0.91%   |
| Romania     | 1        | 0.91%   |
| Netherlands | 1        | 0.91%   |
| Malaysia    | 1        | 0.91%   |
| Japan       | 1        | 0.91%   |
| Ireland     | 1        | 0.91%   |
| India       | 1        | 0.91%   |
| Hong Kong   | 1        | 0.91%   |
| Greece      | 1        | 0.91%   |
| France      | 1        | 0.91%   |
| Finland     | 1        | 0.91%   |
| Belarus     | 1        | 0.91%   |
| Bangladesh  | 1        | 0.91%   |
| Australia   | 1        | 0.91%   |
| Argentina   | 1        | 0.91%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Moscow                  | 4        | 3.54%   |
| Swansea                 | 3        | 2.65%   |
| Cieszyn                 | 3        | 2.65%   |
| Berlin                  | 3        | 2.65%   |
| Zurich                  | 2        | 1.77%   |
| Warsaw                  | 2        | 1.77%   |
| Vancouver               | 2        | 1.77%   |
| Seattle                 | 2        | 1.77%   |
| Los Angeles             | 2        | 1.77%   |
| Yekaterinburg           | 1        | 0.88%   |
| Wyszków                | 1        | 0.88%   |
| Wroclaw                 | 1        | 0.88%   |
| Wrentham                | 1        | 0.88%   |
| Weatherford             | 1        | 0.88%   |
| Warren                  | 1        | 0.88%   |
| Vladivostok             | 1        | 0.88%   |
| Villanueva del Pardillo | 1        | 0.88%   |
| Vigo                    | 1        | 0.88%   |
| Ufa                     | 1        | 0.88%   |
| Troisdorf               | 1        | 0.88%   |
| Trnava                  | 1        | 0.88%   |
| Toronto                 | 1        | 0.88%   |
| Tonbridge               | 1        | 0.88%   |
| Thibodaux               | 1        | 0.88%   |
| Texas City              | 1        | 0.88%   |
| Taichung City           | 1        | 0.88%   |
| Sydney                  | 1        | 0.88%   |
| Svobodnyy               | 1        | 0.88%   |
| Stuttgart               | 1        | 0.88%   |
| Sterling                | 1        | 0.88%   |
| Stasi Las               | 1        | 0.88%   |
| St. Cloud               | 1        | 0.88%   |
| St Petersburg           | 1        | 0.88%   |
| St Louis                | 1        | 0.88%   |
| Schwieberdingen         | 1        | 0.88%   |
| Sao Paulo               | 1        | 0.88%   |
| Santa Teresinha         | 1        | 0.88%   |
| Sankt Wendel            | 1        | 0.88%   |
| San Antonio             | 1        | 0.88%   |
| Rostock                 | 1        | 0.88%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Samsung Electronics       | 60       | 129    | 23.17%  |
| WDC                       | 52       | 86     | 20.08%  |
| Seagate                   | 35       | 79     | 13.51%  |
| Toshiba                   | 18       | 29     | 6.95%   |
| SanDisk                   | 10       | 14     | 3.86%   |
| Hitachi                   | 10       | 28     | 3.86%   |
| Kingston                  | 9        | 10     | 3.47%   |
| Crucial                   | 9        | 17     | 3.47%   |
| Intel                     | 6        | 7      | 2.32%   |
| HGST                      | 5        | 6      | 1.93%   |
| Corsair                   | 5        | 6      | 1.93%   |
| A-DATA Technology         | 5        | 6      | 1.93%   |
| Phison                    | 4        | 6      | 1.54%   |
| OCZ                       | 4        | 4      | 1.54%   |
| GOODRAM                   | 3        | 12     | 1.16%   |
| Silicon Motion            | 2        | 4      | 0.77%   |
| KIOXIA-EXCERIA            | 2        | 3      | 0.77%   |
| Kingchuxing               | 2        | 5      | 0.77%   |
| ADATA Technology          | 2        | 2      | 0.77%   |
| Unknown                   | 1        | 1      | 0.39%   |
| Transcend                 | 1        | 1      | 0.39%   |
| Team                      | 1        | 3      | 0.39%   |
| SK hynix                  | 1        | 2      | 0.39%   |
| Seagate Technology        | 1        | 1      | 0.39%   |
| Realtek Semiconductor     | 1        | 1      | 0.39%   |
| PNY                       | 1        | 1      | 0.39%   |
| Plextor                   | 1        | 2      | 0.39%   |
| Phison Electronics        | 1        | 1      | 0.39%   |
| Patriot                   | 1        | 1      | 0.39%   |
| OCZ-VERTEX                | 1        | 1      | 0.39%   |
| Micron/Crucial Technology | 1        | 1      | 0.39%   |
| Maxtor                    | 1        | 1      | 0.39%   |
| LaCie                     | 1        | 2      | 0.39%   |
| Fujitsu                   | 1        | 1      | 0.39%   |
| Apacer                    | 1        | 1      | 0.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Samsung SSD 970 EVO 500GB                            | 5        | 1.47%   |
| Samsung SSD 860 EVO 1TB                              | 5        | 1.47%   |
| Toshiba DT01ACA100 1TB                               | 4        | 1.18%   |
| Samsung SSD 980 PRO 1TB                              | 4        | 1.18%   |
| Samsung SSD 970 EVO Plus 500GB                       | 4        | 1.18%   |
| Samsung SSD 870 EVO 1TB                              | 4        | 1.18%   |
| Samsung SSD 850 EVO 250GB                            | 4        | 1.18%   |
| WDC WD40EZRZ-00GXCB0 4TB                             | 3        | 0.88%   |
| WDC WD30EFRX-68EUZN0 3TB                             | 3        | 0.88%   |
| Seagate ST4000DM004-2CV104 4TB                       | 3        | 0.88%   |
| Seagate ST2000DM006-2DM164 2TB                       | 3        | 0.88%   |
| Samsung SSD 980 PRO 2TB                              | 3        | 0.88%   |
| Samsung SSD 980 1TB                                  | 3        | 0.88%   |
| Samsung SSD 970 EVO Plus 2TB                         | 3        | 0.88%   |
| Samsung SSD 850 EVO 500GB                            | 3        | 0.88%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 250GB | 3        | 0.88%   |
| Crucial CT2000MX500SSD1 2TB                          | 3        | 0.88%   |
| Crucial CT1000MX500SSD1 1TB                          | 3        | 0.88%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                     | 2        | 0.59%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                       | 2        | 0.59%   |
| WDC WD30EFRX-68AX9N0 3TB                             | 2        | 0.59%   |
| WDC WD2003FZEX-00SRLA0 2TB                           | 2        | 0.59%   |
| WDC WD10EZRZ-00HTKB0 1TB                             | 2        | 0.59%   |
| WDC WD10EZEX-08WN4A0 1TB                             | 2        | 0.59%   |
| WDC WD10EZEX-08M2NA0 1TB                             | 2        | 0.59%   |
| Seagate ST500DM002-1BD142 500GB                      | 2        | 0.59%   |
| Seagate ST4000DM005-2DP166 4TB                       | 2        | 0.59%   |
| Seagate ST4000DM000-1F2168 4TB                       | 2        | 0.59%   |
| Seagate ST3500630AS 500GB                            | 2        | 0.59%   |
| Seagate ST2000DM001-1ER164 2TB                       | 2        | 0.59%   |
| Seagate ST2000DM001-1CH164 2TB                       | 2        | 0.59%   |
| Samsung SSD 980 PRO 500GB                            | 2        | 0.59%   |
| Samsung SSD 970 PRO 1TB                              | 2        | 0.59%   |
| Samsung SSD 970 EVO Plus 250GB                       | 2        | 0.59%   |
| Samsung SSD 970 EVO Plus 1TB                         | 2        | 0.59%   |
| Samsung SSD 970 EVO 250GB                            | 2        | 0.59%   |
| Samsung SSD 870 EVO 500GB                            | 2        | 0.59%   |
| Samsung SSD 860 QVO 2TB                              | 2        | 0.59%   |
| Samsung SSD 860 PRO 4TB                              | 2        | 0.59%   |
| Samsung SSD 850 PRO 512GB                            | 2        | 0.59%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 42       | 70     | 38.53%  |
| Seagate             | 33       | 76     | 30.28%  |
| Toshiba             | 15       | 24     | 13.76%  |
| Hitachi             | 10       | 28     | 9.17%   |
| HGST                | 5        | 6      | 4.59%   |
| Samsung Electronics | 1        | 1      | 0.92%   |
| Maxtor              | 1        | 1      | 0.92%   |
| LaCie               | 1        | 2      | 0.92%   |
| Fujitsu             | 1        | 1      | 0.92%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 36       | 56     | 40.45%  |
| SanDisk             | 8        | 10     | 8.99%   |
| Crucial             | 8        | 14     | 8.99%   |
| WDC                 | 7        | 8      | 7.87%   |
| Kingston            | 7        | 8      | 7.87%   |
| OCZ                 | 4        | 4      | 4.49%   |
| Corsair             | 4        | 5      | 4.49%   |
| Intel               | 3        | 3      | 3.37%   |
| GOODRAM             | 3        | 12     | 3.37%   |
| A-DATA Technology   | 2        | 2      | 2.25%   |
| Transcend           | 1        | 1      | 1.12%   |
| Toshiba             | 1        | 2      | 1.12%   |
| PNY                 | 1        | 1      | 1.12%   |
| Patriot             | 1        | 1      | 1.12%   |
| OCZ-VERTEX          | 1        | 1      | 1.12%   |
| Kingchuxing         | 1        | 1      | 1.12%   |
| Apacer              | 1        | 1      | 1.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 75       | 209    | 35.05%  |
| NVMe    | 71       | 134    | 33.18%  |
| SSD     | 67       | 130    | 31.31%  |
| Unknown | 1        | 1      | 0.47%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 100      | 335    | 57.8%   |
| NVMe | 71       | 134    | 41.04%  |
| SAS  | 2        | 5      | 1.16%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 56       | 107    | 30.94%  |
| 0.51-1.0   | 50       | 69     | 27.62%  |
| 1.01-2.0   | 31       | 49     | 17.13%  |
| 3.01-4.0   | 19       | 30     | 10.5%   |
| 4.01-10.0  | 12       | 47     | 6.63%   |
| 2.01-3.0   | 10       | 28     | 5.52%   |
| 10.01-20.0 | 3        | 9      | 1.66%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 22       | 19.3%   |
| 1001-2000      | 22       | 19.3%   |
| 501-1000       | 20       | 17.54%  |
| 251-500        | 15       | 13.16%  |
| 2001-3000      | 13       | 11.4%   |
| 101-250        | 7        | 6.14%   |
| 1-20           | 5        | 4.39%   |
| 51-100         | 4        | 3.51%   |
| Unknown        | 4        | 3.51%   |
| 21-50          | 2        | 1.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 17       | 14.78%  |
| 1001-2000      | 17       | 14.78%  |
| 1-20           | 15       | 13.04%  |
| 501-1000       | 14       | 12.17%  |
| More than 3000 | 13       | 11.3%   |
| 101-250        | 13       | 11.3%   |
| 21-50          | 11       | 9.57%   |
| 51-100         | 7        | 6.09%   |
| 2001-3000      | 4        | 3.48%   |
| Unknown        | 4        | 3.48%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Samsung Electronics SSD 870 EVO 500GB | 2        | 2      | 5.71%   |
| WDC WD60EFRX-68L0BN1 6TB              | 1        | 3      | 2.86%   |
| WDC WD40EFRX-68N32N0 4TB              | 1        | 1      | 2.86%   |
| WDC WD30EFRX-68AX9N0 3TB              | 1        | 2      | 2.86%   |
| WDC WD20EZRX-00D8PB0 2TB              | 1        | 1      | 2.86%   |
| WDC WD20EFRX-68AX9N0 2TB              | 1        | 1      | 2.86%   |
| WDC WD20EARS-00J2GB0 2TB              | 1        | 1      | 2.86%   |
| WDC WD1600AAJS-75B4A0 160GB           | 1        | 1      | 2.86%   |
| WDC WD10EFRX-68JCSN0 1TB              | 1        | 1      | 2.86%   |
| WDC WD1002FBYS-18W8B0 1TB             | 1        | 1      | 2.86%   |
| Transcend TS512GSSD720 512GB          | 1        | 1      | 2.86%   |
| Toshiba HDWA120 2TB                   | 1        | 1      | 2.86%   |
| Seagate ST500DM002-1BD142 500GB       | 1        | 1      | 2.86%   |
| Seagate ST3250410AS 250GB             | 1        | 1      | 2.86%   |
| Seagate ST3160023AS 160GB             | 1        | 1      | 2.86%   |
| Seagate ST3000DM001-9YN166 3TB        | 1        | 1      | 2.86%   |
| Seagate ST2000DX001-1CM164 2TB        | 1        | 1      | 2.86%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1        | 1      | 2.86%   |
| Seagate ST10000VN0004-1ZD101 10TB     | 1        | 4      | 2.86%   |
| SanDisk SSD PLUS 1000GB               | 1        | 1      | 2.86%   |
| Samsung Electronics SSD 980 PRO 2TB   | 1        | 1      | 2.86%   |
| Samsung Electronics SSD 980 1TB       | 1        | 1      | 2.86%   |
| Samsung Electronics SSD 970 EVO 1TB   | 1        | 2      | 2.86%   |
| Samsung Electronics SSD 870 EVO 1TB   | 1        | 1      | 2.86%   |
| Samsung Electronics SSD 850 PRO 256GB | 1        | 4      | 2.86%   |
| Samsung Electronics HD103SJ 1TB       | 1        | 1      | 2.86%   |
| OCZ VERTEX4 128GB SSD                 | 1        | 1      | 2.86%   |
| Maxtor STM3160215A 160GB              | 1        | 1      | 2.86%   |
| Kingston SV100S2128G 128GB SSD        | 1        | 1      | 2.86%   |
| Hitachi HUA721010KLA330 1TB           | 1        | 1      | 2.86%   |
| Hitachi HTS541680J9SA00 80GB          | 1        | 1      | 2.86%   |
| Hitachi HDS722020ALA330 2TB           | 1        | 2      | 2.86%   |
| Crucial CT525MX300SSD1 528GB          | 1        | 1      | 2.86%   |
| Corsair Neutron GTX SSD 240GB         | 1        | 1      | 2.86%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 9        | 12     | 26.47%  |
| Seagate             | 7        | 10     | 20.59%  |
| Samsung Electronics | 7        | 12     | 20.59%  |
| Hitachi             | 3        | 4      | 8.82%   |
| Transcend           | 1        | 1      | 2.94%   |
| Toshiba             | 1        | 1      | 2.94%   |
| SanDisk             | 1        | 1      | 2.94%   |
| OCZ                 | 1        | 1      | 2.94%   |
| Maxtor              | 1        | 1      | 2.94%   |
| Kingston            | 1        | 1      | 2.94%   |
| Crucial             | 1        | 1      | 2.94%   |
| Corsair             | 1        | 1      | 2.94%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 9        | 12     | 40.91%  |
| Seagate             | 7        | 10     | 31.82%  |
| Hitachi             | 3        | 4      | 13.64%  |
| Toshiba             | 1        | 1      | 4.55%   |
| Samsung Electronics | 1        | 1      | 4.55%   |
| Maxtor              | 1        | 1      | 4.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 19       | 29     | 59.38%  |
| SSD  | 10       | 13     | 31.25%  |
| NVMe | 3        | 4      | 9.38%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Toshiba THNSN5512GPUK NVMe 512GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Toshiba | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 101      | 391    | 71.63%  |
| Malfunc  | 29       | 46     | 20.57%  |
| Detected | 10       | 36     | 7.09%   |
| Failed   | 1        | 1      | 0.71%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| AMD                            | 62       | 29.67%  |
| Intel                          | 45       | 21.53%  |
| Samsung Electronics            | 41       | 19.62%  |
| SanDisk                        | 10       | 4.78%   |
| ASMedia Technology             | 9        | 4.31%   |
| Phison Electronics             | 7        | 3.35%   |
| ADATA Technology               | 5        | 2.39%   |
| Silicon Motion                 | 4        | 1.91%   |
| Toshiba America Info Systems   | 3        | 1.44%   |
| Seagate Technology             | 3        | 1.44%   |
| Micron/Crucial Technology      | 3        | 1.44%   |
| Marvell Technology Group       | 3        | 1.44%   |
| KIOXIA                         | 2        | 0.96%   |
| Kingston Technology Company    | 2        | 0.96%   |
| JMicron Technology             | 2        | 0.96%   |
| Broadcom / LSI                 | 2        | 0.96%   |
| Unknown                        | 1        | 0.48%   |
| Solid State Storage Technology | 1        | 0.48%   |
| SK hynix                       | 1        | 0.48%   |
| Silicon Image                  | 1        | 0.48%   |
| Realtek Semiconductor          | 1        | 0.48%   |
| Nvidia                         | 1        | 0.48%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 41       | 17.45%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 25       | 10.64%  |
| AMD 400 Series Chipset SATA Controller                                         | 15       | 6.38%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 13       | 5.53%   |
| AMD 500 Series Chipset SATA Controller                                         | 11       | 4.68%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 8        | 3.4%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 7        | 2.98%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 7        | 2.98%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 5        | 2.13%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 5        | 2.13%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 4        | 1.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4        | 1.7%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 4        | 1.7%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 3        | 1.28%   |
| Seagate FireCuda 520 SSD                                                       | 3        | 1.28%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3        | 1.28%   |
| Samsung NVMe SSD Controller 980                                                | 3        | 1.28%   |
| Phison E16 PCIe4 NVMe Controller                                               | 3        | 1.28%   |
| Phison E12 NVMe Controller                                                     | 3        | 1.28%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3        | 1.28%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2        | 0.85%   |
| Micron/Crucial NVMe Controller                                                 | 2        | 0.85%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 2        | 0.85%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2        | 0.85%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 2        | 0.85%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 2        | 0.85%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2        | 0.85%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2        | 0.85%   |
| AMD X370 Series Chipset SATA Controller                                        | 2        | 0.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2        | 0.85%   |
| AMD SATA controller                                                            | 2        | 0.85%   |
| AMD 300 Series Chipset SATA Controller                                         | 2        | 0.85%   |
| Unknown Non-Volatile memory controller                                         | 1        | 0.43%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1        | 0.43%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1        | 0.43%   |
| Toshiba America Info Systems NVMe Controller                                   | 1        | 0.43%   |
| Solid State Storage Non-Volatile memory controller                             | 1        | 0.43%   |
| SK hynix Non-Volatile memory controller                                        | 1        | 0.43%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1        | 0.43%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1        | 0.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 103      | 55.38%  |
| NVMe | 71       | 38.17%  |
| IDE  | 6        | 3.23%   |
| RAID | 4        | 2.15%   |
| SAS  | 2        | 1.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| AMD                   | 63       | 57.27%  |
| Intel                 | 45       | 40.91%  |
| PowerBook6,7          | 1        | 0.91%   |
| Marvell Semiconductor | 1        | 0.91%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                                                    | Desktops | Percent |
|--------------------------------------------------------------------------|----------|---------|
| AMD Ryzen 9 5900X 12-Core Processor                                      | 8        | 7.27%   |
| AMD Ryzen 9 5950X 16-Core Processor                                      | 6        | 5.45%   |
| AMD Ryzen 9 3950X 16-Core Processor                                      | 4        | 3.64%   |
| AMD Ryzen 9 3900X 12-Core Processor                                      | 4        | 3.64%   |
| AMD Ryzen 5 3600 6-Core Processor                                        | 4        | 3.64%   |
| AMD Ryzen 5 2600 Six-Core Processor                                      | 4        | 3.64%   |
| Intel Core i7-8700K CPU @ 3.70GHz                                        | 3        | 2.73%   |
| Intel Core i7-6700K CPU @ 4.00GHz                                        | 3        | 2.73%   |
| AMD Ryzen 7 3700X 8-Core Processor                                       | 3        | 2.73%   |
| Intel Core i9-9900K CPU @ 3.60GHz                                        | 2        | 1.82%   |
| Intel Core i7-4790K CPU @ 4.00GHz                                        | 2        | 1.82%   |
| Intel Core i5-9600K CPU @ 3.70GHz                                        | 2        | 1.82%   |
| Intel 12th Gen Core i9-12900K                                            | 2        | 1.82%   |
| Intel 12th Gen Core i7-12700K                                            | 2        | 1.82%   |
| Intel 11th Gen Core i9-11900KF @ 3.50GHz                                 | 2        | 1.82%   |
| AMD Ryzen 7 PRO 5750G with Radeon Graphics                               | 2        | 1.82%   |
| AMD Ryzen 7 3800X 8-Core Processor                                       | 2        | 1.82%   |
| AMD Ryzen 7 2700X Eight-Core Processor                                   | 2        | 1.82%   |
| AMD Ryzen 5 5600X 6-Core Processor                                       | 2        | 1.82%   |
| AMD Ryzen 5 1600 Six-Core Processor                                      | 2        | 1.82%   |
| PowerBook6,7 7447A, altivec supported                                    | 1        | 0.91%   |
| Marvell Semiconductor Marvell Kirkwood (Flattened Device Tree) Processor | 1        | 0.91%   |
| Intel Xeon CPU X5690 @ 3.47GHz                                           | 1        | 0.91%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz                                      | 1        | 0.91%   |
| Intel Xeon CPU E3-1275 v6 @ 3.80GHz                                      | 1        | 0.91%   |
| Intel Pentium 4 CPU 3.20GHz                                              | 1        | 0.91%   |
| Intel Core i7-9700F CPU @ 3.00GHz                                        | 1        | 0.91%   |
| Intel Core i7-8086K CPU @ 4.00GHz                                        | 1        | 0.91%   |
| Intel Core i7-4930K CPU @ 3.40GHz                                        | 1        | 0.91%   |
| Intel Core i7-4790 CPU @ 3.60GHz                                         | 1        | 0.91%   |
| Intel Core i7-10700F CPU @ 2.90GHz                                       | 1        | 0.91%   |
| Intel Core i7-10700 CPU @ 2.90GHz                                        | 1        | 0.91%   |
| Intel Core i5-7400 CPU @ 3.00GHz                                         | 1        | 0.91%   |
| Intel Core i5-6500 CPU @ 3.20GHz                                         | 1        | 0.91%   |
| Intel Core i5-6400 CPU @ 2.70GHz                                         | 1        | 0.91%   |
| Intel Core i5-4670K CPU @ 3.40GHz                                        | 1        | 0.91%   |
| Intel Core i5-4250U CPU @ 1.30GHz                                        | 1        | 0.91%   |
| Intel Core i5-3550 CPU @ 3.30GHz                                         | 1        | 0.91%   |
| Intel Core i5-2500S CPU @ 2.70GHz                                        | 1        | 0.91%   |
| Intel Core i5-2500K CPU @ 3.30GHz                                        | 1        | 0.91%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| AMD Ryzen 9            | 24       | 21.82%  |
| Intel Core i7          | 14       | 12.73%  |
| AMD Ryzen 5            | 14       | 12.73%  |
| Other                  | 13       | 11.82%  |
| Intel Core i5          | 13       | 11.82%  |
| AMD Ryzen 7            | 11       | 10%     |
| AMD Ryzen Threadripper | 4        | 3.64%   |
| Intel Xeon             | 3        | 2.73%   |
| Intel Core i9          | 2        | 1.82%   |
| AMD Ryzen 7 PRO        | 2        | 1.82%   |
| AMD Phenom II X6       | 2        | 1.82%   |
| Intel Pentium 4        | 1        | 0.91%   |
| Intel Celeron          | 1        | 0.91%   |
| AMD Sempron            | 1        | 0.91%   |
| AMD Ryzen 3            | 1        | 0.91%   |
| AMD Phenom II X4       | 1        | 0.91%   |
| AMD FX                 | 1        | 0.91%   |
| AMD Athlon             | 1        | 0.91%   |
| AMD A6                 | 1        | 0.91%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 27       | 24.55%  |
| 8      | 23       | 20.91%  |
| 4      | 20       | 18.18%  |
| 12     | 17       | 15.45%  |
| 16     | 14       | 12.73%  |
| 1      | 4        | 3.64%   |
| 2      | 2        | 1.82%   |
| 32     | 1        | 0.91%   |
| 24     | 1        | 0.91%   |
| 10     | 1        | 0.91%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 110      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 89       | 80.91%  |
| 1      | 21       | 19.09%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 108      | 98.18%  |
| 32-bit         | 1        | 0.91%   |
| Unknown        | 1        | 0.91%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 16       | 14.41%  |
| 0x08701021 | 13       | 11.71%  |
| 0x0a201016 | 10       | 9.01%   |
| 0x90672    | 6        | 5.41%   |
| 0xa0671    | 5        | 4.5%    |
| 0x0800820d | 5        | 4.5%    |
| 0x906ed    | 4        | 3.6%    |
| 0x506e3    | 4        | 3.6%    |
| 0x306c3    | 3        | 2.7%    |
| 0x08301039 | 3        | 2.7%    |
| 0x08001138 | 3        | 2.7%    |
| 0xa0655    | 2        | 1.8%    |
| 0xa0653    | 2        | 1.8%    |
| 0x906ea    | 2        | 1.8%    |
| 0x906e9    | 2        | 1.8%    |
| 0x306e4    | 2        | 1.8%    |
| 0x206a7    | 2        | 1.8%    |
| 0x0a50000b | 2        | 1.8%    |
| 0x0a201205 | 2        | 1.8%    |
| 0x0a201204 | 2        | 1.8%    |
| 0x00000000 | 2        | 1.8%    |
| 0xf43      | 1        | 0.9%    |
| 0x906ec    | 1        | 0.9%    |
| 0x40651    | 1        | 0.9%    |
| 0x306a9    | 1        | 0.9%    |
| 0x206c2    | 1        | 0.9%    |
| 0x0a601203 | 1        | 0.9%    |
| 0x0a601201 | 1        | 0.9%    |
| 0x0a50000c | 1        | 0.9%    |
| 0x0a20120a | 1        | 0.9%    |
| 0x0a201009 | 1        | 0.9%    |
| 0x08701013 | 1        | 0.9%    |
| 0x08600106 | 1        | 0.9%    |
| 0x08001137 | 1        | 0.9%    |
| 0x0700010f | 1        | 0.9%    |
| 0x0700010b | 1        | 0.9%    |
| 0x06001119 | 1        | 0.9%    |
| 0x010000dc | 1        | 0.9%    |
| 0x010000db | 1        | 0.9%    |
| 0x010000bf | 1        | 0.9%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 22       | 19.82%  |
| Zen 3            | 21       | 18.92%  |
| KabyLake         | 11       | 9.91%   |
| Zen+             | 7        | 6.31%   |
| Alderlake Hybrid | 6        | 5.41%   |
| Skylake          | 5        | 4.5%    |
| Icelake          | 5        | 4.5%    |
| Haswell          | 5        | 4.5%    |
| Unknown          | 5        | 4.5%    |
| Zen              | 4        | 3.6%    |
| CometLake        | 4        | 3.6%    |
| SandyBridge      | 3        | 2.7%    |
| K10              | 3        | 2.7%    |
| IvyBridge        | 3        | 2.7%    |
| Piledriver       | 2        | 1.8%    |
| Jaguar           | 2        | 1.8%    |
| Westmere         | 1        | 0.9%    |
| Silvermont       | 1        | 0.9%    |
| NetBurst         | 1        | 0.9%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 62       | 52.1%   |
| Nvidia | 43       | 36.13%  |
| Intel  | 14       | 11.76%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]             | 21       | 17.21%  |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                      | 6        | 4.92%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                | 4        | 3.28%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                           | 3        | 2.46%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                 | 3        | 2.46%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                  | 3        | 2.46%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                      | 3        | 2.46%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                  | 3        | 2.46%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                          | 3        | 2.46%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                    | 3        | 2.46%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                               | 2        | 1.64%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                              | 2        | 1.64%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                              | 2        | 1.64%   |
| Nvidia GP104 [GeForce GTX 1080]                                     | 2        | 1.64%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                            | 2        | 1.64%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                           | 2        | 1.64%   |
| Intel AlderLake-S GT1                                               | 2        | 1.64%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                            | 2        | 1.64%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]             | 2        | 1.64%   |
| AMD Cezanne                                                         | 2        | 1.64%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X] | 2        | 1.64%   |
| Nvidia TU116 [GeForce GTX 1650]                                     | 1        | 0.82%   |
| Nvidia TU106 [GeForce RTX 2070]                                     | 1        | 0.82%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                               | 1        | 0.82%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                               | 1        | 0.82%   |
| Nvidia GT218 [GeForce 210]                                          | 1        | 0.82%   |
| Nvidia GP108 [GeForce GT 1030]                                      | 1        | 0.82%   |
| Nvidia GP106GL [Quadro P2000]                                       | 1        | 0.82%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                 | 1        | 0.82%   |
| Nvidia GP104 [GeForce GTX 1070]                                     | 1        | 0.82%   |
| Nvidia GM206 [GeForce GTX 960]                                      | 1        | 0.82%   |
| Nvidia GM204 [GeForce GTX 970]                                      | 1        | 0.82%   |
| Nvidia GM107 [GeForce GTX 745]                                      | 1        | 0.82%   |
| Nvidia GK208B [GeForce GT 730]                                      | 1        | 0.82%   |
| Nvidia GK208B [GeForce GT 710]                                      | 1        | 0.82%   |
| Nvidia GK110B [GeForce GTX 780 Ti]                                  | 1        | 0.82%   |
| Nvidia GK104 [GeForce GTX 670]                                      | 1        | 0.82%   |
| Nvidia GF119 [GeForce GT 610]                                       | 1        | 0.82%   |
| Nvidia GA106 [Geforce RTX 3050]                                     | 1        | 0.82%   |
| Nvidia GA104 [GeForce RTX 3060]                                     | 1        | 0.82%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 53       | 47.75%  |
| 1 x Nvidia     | 38       | 34.23%  |
| 1 x Intel      | 8        | 7.21%   |
| AMD + Nvidia   | 4        | 3.6%    |
| Intel + AMD    | 3        | 2.7%    |
| Other          | 2        | 1.8%    |
| 2 x AMD        | 2        | 1.8%    |
| Intel + Nvidia | 1        | 0.9%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 71       | 63.96%  |
| Proprietary | 33       | 29.73%  |
| Unknown     | 7        | 6.31%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 7.01-8.0   | 31       | 27.19%  |
| Unknown    | 29       | 25.44%  |
| 8.01-16.0  | 21       | 18.42%  |
| 3.01-4.0   | 9        | 7.89%   |
| 0.51-1.0   | 8        | 7.02%   |
| 1.01-2.0   | 7        | 6.14%   |
| 5.01-6.0   | 5        | 4.39%   |
| 0.01-0.5   | 2        | 1.75%   |
| 4.01-5.0   | 1        | 0.88%   |
| 2.01-3.0   | 1        | 0.88%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 17       | 11.89%  |
| Goldstar                | 17       | 11.89%  |
| Dell                    | 11       | 7.69%   |
| Acer                    | 11       | 7.69%   |
| AOC                     | 9        | 6.29%   |
| ViewSonic               | 7        | 4.9%    |
| Hewlett-Packard         | 7        | 4.9%    |
| ASUSTek Computer        | 6        | 4.2%    |
| Ancor Communications    | 6        | 4.2%    |
| BenQ                    | 5        | 3.5%    |
| Philips                 | 4        | 2.8%    |
| Lenovo                  | 4        | 2.8%    |
| Iiyama                  | 3        | 2.1%    |
| Eizo                    | 3        | 2.1%    |
| Unknown                 | 3        | 2.1%    |
| Unknown                 | 2        | 1.4%    |
| Toshiba                 | 2        | 1.4%    |
| NEC Computers           | 2        | 1.4%    |
| MSI                     | 2        | 1.4%    |
| HannStar                | 2        | 1.4%    |
| ___                     | 1        | 0.7%    |
| Valve                   | 1        | 0.7%    |
| Sony                    | 1        | 0.7%    |
| Sceptre Tech            | 1        | 0.7%    |
| PNP                     | 1        | 0.7%    |
| Onkyo                   | 1        | 0.7%    |
| MStar                   | 1        | 0.7%    |
| Microstep               | 1        | 0.7%    |
| Mi                      | 1        | 0.7%    |
| LYC                     | 1        | 0.7%    |
| LG Electronics          | 1        | 0.7%    |
| KTC                     | 1        | 0.7%    |
| Gigabyte Technology     | 1        | 0.7%    |
| Gateway                 | 1        | 0.7%    |
| Denver                  | 1        | 0.7%    |
| CVT                     | 1        | 0.7%    |
| Chi Mei Optoelectronics | 1        | 0.7%    |
| Belinea                 | 1        | 0.7%    |
| AUS                     | 1        | 0.7%    |
| Apple                   | 1        | 0.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Goldstar LG HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                | 5        | 3.25%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch       | 3        | 1.95%   |
| Unknown                                                                 | 3        | 1.95%   |
| Philips PHL 242M8 PHLC214 1920x1080 527x296mm 23.8-inch                 | 2        | 1.3%    |
| Goldstar ULTRAWIDE GSM76E4 3440x1440 800x335mm 34.1-inch                | 2        | 1.3%    |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                  | 2        | 1.3%    |
| Eizo CS2731 ENC3069 2560x1440 597x336mm 27.0-inch                       | 2        | 1.3%    |
| ___ LCD TV ___9000 1360x768                                             | 1        | 0.65%   |
| ViewSonic VX2458-mhd VSC0437 1920x1080 521x293mm 23.5-inch              | 1        | 0.65%   |
| ViewSonic VX2458 Series VSC36AF 1920x1080 521x293mm 23.5-inch           | 1        | 0.65%   |
| ViewSonic VX2363 Series VSC6B2F 1920x1080 509x286mm 23.0-inch           | 1        | 0.65%   |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 477x268mm 21.5-inch           | 1        | 0.65%   |
| ViewSonic VP2768 Series VSC2034 2560x1440 597x336mm 27.0-inch           | 1        | 0.65%   |
| ViewSonic VG1655 VSCD239 1920x1080 340x190mm 15.3-inch                  | 1        | 0.65%   |
| ViewSonic LCD Monitor VX3276-UHD 5760x2160                              | 1        | 0.65%   |
| Valve Index HMD VLV91A8                                                 | 1        | 0.65%   |
| Unknown LCDTV 9000 1360x768 1600x900mm 72.3-inch                        | 1        | 0.65%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch               | 1        | 0.65%   |
| Toshiba PA3552 TOS501C 1680x1050 433x270mm 20.1-inch                    | 1        | 0.65%   |
| Toshiba 55UHD_LCD_TV TSB3700 3840x2160 1100x620mm 49.7-inch             | 1        | 0.65%   |
| Sony SDMU27M90*30 SNY075A 3840x2160 596x335mm 26.9-inch                 | 1        | 0.65%   |
| Sceptre Tech H32 SPT0CB8 1920x1080 575x323mm 26.0-inch                  | 1        | 0.65%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch       | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM05CC 1920x1080 530x300mm 24.0-inch    | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM0584 2048x1152 510x290mm 23.1-inch    | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch    | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM0194 1280x1024 376x301mm 19.0-inch    | 1        | 0.65%   |
| Samsung Electronics SMS27A850 SAM083D 2560x1440 518x324mm 24.1-inch     | 1        | 0.65%   |
| Samsung Electronics S22B300 SAM08C8 1920x1080 477x268mm 21.5-inch       | 1        | 0.65%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch       | 1        | 0.65%   |
| Samsung Electronics LF24T450F SAM7096 1920x1080 527x296mm 23.8-inch     | 1        | 0.65%   |
| Samsung Electronics LCD Monitor SAM7002 3840x2160 1872x1053mm 84.6-inch | 1        | 0.65%   |
| Samsung Electronics LCD Monitor SAM0357 1920x1080                       | 1        | 0.65%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch      | 1        | 0.65%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch      | 1        | 0.65%   |
| Samsung Electronics C49HG9x SAM0E5E 3840x1080 1196x336mm 48.9-inch      | 1        | 0.65%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch       | 1        | 0.65%   |
| PNP LCD Monitor PNP0801 1280x960                                        | 1        | 0.65%   |
| Philips PHL 349X7 PHLC149 3440x1440 800x330mm 34.1-inch                 | 1        | 0.65%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                 | 1        | 0.65%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 49       | 36.3%   |
| 2560x1440 (QHD)    | 30       | 22.22%  |
| 3840x2160 (4K)     | 16       | 11.85%  |
| 3440x1440          | 6        | 4.44%   |
| 1280x1024 (SXGA)   | 6        | 4.44%   |
| Unknown            | 5        | 3.7%    |
| 3840x1080          | 3        | 2.22%   |
| 1920x1200 (WUXGA)  | 3        | 2.22%   |
| 1680x1050 (WSXGA+) | 3        | 2.22%   |
| 1440x900 (WXGA+)   | 2        | 1.48%   |
| 1366x768 (WXGA)    | 2        | 1.48%   |
| 7680x2160          | 1        | 0.74%   |
| 5760x2160          | 1        | 0.74%   |
| 4000x2560          | 1        | 0.74%   |
| 2560x1080          | 1        | 0.74%   |
| 2288x1287          | 1        | 0.74%   |
| 2048x1152          | 1        | 0.74%   |
| 1600x900 (HD+)     | 1        | 0.74%   |
| 1360x768           | 1        | 0.74%   |
| 1280x960           | 1        | 0.74%   |
| 1024x768 (XGA)     | 1        | 0.74%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 39       | 27.46%  |
| 23      | 22       | 15.49%  |
| 24      | 14       | 9.86%   |
| Unknown | 12       | 8.45%   |
| 21      | 11       | 7.75%   |
| 34      | 7        | 4.93%   |
| 17      | 5        | 3.52%   |
| 31      | 4        | 2.82%   |
| 25      | 4        | 2.82%   |
| 19      | 4        | 2.82%   |
| 84      | 2        | 1.41%   |
| 72      | 2        | 1.41%   |
| 49      | 2        | 1.41%   |
| 26      | 2        | 1.41%   |
| 22      | 2        | 1.41%   |
| 15      | 2        | 1.41%   |
| 14      | 2        | 1.41%   |
| 142     | 1        | 0.7%    |
| 48      | 1        | 0.7%    |
| 29      | 1        | 0.7%    |
| 28      | 1        | 0.7%    |
| 20      | 1        | 0.7%    |
| 18      | 1        | 0.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 67       | 51.15%  |
| 401-500        | 16       | 12.21%  |
| Unknown        | 12       | 9.16%   |
| 601-700        | 10       | 7.63%   |
| 301-350        | 8        | 6.11%   |
| 701-800        | 7        | 5.34%   |
| 1501-2000      | 4        | 3.05%   |
| 1001-1500      | 3        | 2.29%   |
| 351-400        | 2        | 1.53%   |
| More than 2000 | 1        | 0.76%   |
| 201-300        | 1        | 0.76%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 80       | 68.97%  |
| 16/10   | 9        | 7.76%   |
| 21/9    | 8        | 6.9%    |
| Unknown | 8        | 6.9%    |
| 5/4     | 6        | 5.17%   |
| 4/3     | 2        | 1.72%   |
| 32/9    | 2        | 1.72%   |
| 1.00    | 1        | 0.86%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 301-350        | 39       | 28.68%  |
| 201-250        | 37       | 27.21%  |
| 351-500        | 12       | 8.82%   |
| Unknown        | 12       | 8.82%   |
| 251-300        | 10       | 7.35%   |
| 151-200        | 8        | 5.88%   |
| More than 1000 | 6        | 4.41%   |
| 141-150        | 6        | 4.41%   |
| 101-110        | 2        | 1.47%   |
| 501-1000       | 2        | 1.47%   |
| 81-90          | 1        | 0.74%   |
| 91-100         | 1        | 0.74%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 55       | 43.65%  |
| 101-120 | 40       | 31.75%  |
| Unknown | 12       | 9.52%   |
| 121-160 | 10       | 7.94%   |
| 161-240 | 6        | 4.76%   |
| 1-50    | 3        | 2.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 59       | 52.68%  |
| 2     | 35       | 31.25%  |
| 0     | 9        | 8.04%   |
| 3     | 6        | 5.36%   |
| 4     | 3        | 2.68%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 67       | 43.51%  |
| Realtek Semiconductor    | 55       | 35.71%  |
| Aquantia                 | 7        | 4.55%   |
| Qualcomm Atheros         | 5        | 3.25%   |
| Microsoft                | 3        | 1.95%   |
| MediaTek                 | 3        | 1.95%   |
| Marvell Technology Group | 2        | 1.3%    |
| Dresden Elektronik       | 2        | 1.3%    |
| Broadcom                 | 2        | 1.3%    |
| Sigma Designs            | 1        | 0.65%   |
| Raspberry Pi             | 1        | 0.65%   |
| Ralink Technology        | 1        | 0.65%   |
| Nvidia                   | 1        | 0.65%   |
| NetGear                  | 1        | 0.65%   |
| DisplayLink              | 1        | 0.65%   |
| Broadcom Limited         | 1        | 0.65%   |
| Apple                    | 1        | 0.65%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 38       | 19.79%  |
| Intel Wi-Fi 6 AX200                                                 | 23       | 11.98%  |
| Intel I211 Gigabit Network Connection                               | 17       | 8.85%   |
| Realtek RTL8125 2.5GbE Controller                                   | 16       | 8.33%   |
| Intel Ethernet Controller I225-V                                    | 13       | 6.77%   |
| Intel Ethernet Connection (7) I219-V                                | 7        | 3.65%   |
| Intel Ethernet Connection (2) I219-V                                | 6        | 3.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 5        | 2.6%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 4        | 2.08%   |
| Intel Wireless-AC 9260                                              | 3        | 1.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                     | 3        | 1.56%   |
| Intel Alder Lake-S PCH CNVi WiFi                                    | 3        | 1.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 2        | 1.04%   |
| Microsoft XBOX ACC                                                  | 2        | 1.04%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 2        | 1.04%   |
| Intel I210 Gigabit Network Connection                               | 2        | 1.04%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 2        | 1.04%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                | 2        | 1.04%   |
| Intel 82574L Gigabit Network Connection                             | 2        | 1.04%   |
| Dresden Elektronik ZigBee gateway [ConBee II]                       | 2        | 1.04%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 1.04%   |
| Sigma Designs Aeotec Z-Stick Gen5 (ZW090) - UZB                     | 1        | 0.52%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1        | 0.52%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                     | 1        | 0.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 1        | 0.52%   |
| Raspberry Pi Pico                                                   | 1        | 0.52%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 1        | 0.52%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 1        | 0.52%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                    | 1        | 0.52%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                    | 1        | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 1        | 0.52%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter          | 1        | 0.52%   |
| Nvidia MCP61 Ethernet                                               | 1        | 0.52%   |
| NetGear A6210                                                       | 1        | 0.52%   |
| Microsoft Wireless XBox Controller Dongle                           | 1        | 0.52%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter       | 1        | 0.52%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller             | 1        | 0.52%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller             | 1        | 0.52%   |
| Intel Wireless 7265                                                 | 1        | 0.52%   |
| Intel Wireless 3165                                                 | 1        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 43       | 71.67%  |
| Qualcomm Atheros      | 4        | 6.67%   |
| Microsoft             | 3        | 5%      |
| MediaTek              | 3        | 5%      |
| Realtek Semiconductor | 2        | 3.33%   |
| Broadcom              | 2        | 3.33%   |
| Ralink Technology     | 1        | 1.67%   |
| NetGear               | 1        | 1.67%   |
| Broadcom Limited      | 1        | 1.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                 | 23       | 37.7%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 5        | 8.2%    |
| Intel Wireless-AC 9260                                              | 3        | 4.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                     | 3        | 4.92%   |
| Intel Alder Lake-S PCH CNVi WiFi                                    | 3        | 4.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 2        | 3.28%   |
| Microsoft XBOX ACC                                                  | 2        | 3.28%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 2        | 3.28%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 2        | 3.28%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1        | 1.64%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                     | 1        | 1.64%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 1        | 1.64%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                    | 1        | 1.64%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                    | 1        | 1.64%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter          | 1        | 1.64%   |
| NetGear A6210                                                       | 1        | 1.64%   |
| Microsoft Wireless XBox Controller Dongle                           | 1        | 1.64%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter       | 1        | 1.64%   |
| Intel Wireless 7265                                                 | 1        | 1.64%   |
| Intel Wireless 3165                                                 | 1        | 1.64%   |
| Intel Tiger Lake PCH CNVi WiFi                                      | 1        | 1.64%   |
| Intel Comet Lake PCH CNVi WiFi                                      | 1        | 1.64%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter          | 1        | 1.64%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                  | 1        | 1.64%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1        | 1.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 55       | 45.08%  |
| Intel                    | 53       | 43.44%  |
| Aquantia                 | 7        | 5.74%   |
| Qualcomm Atheros         | 2        | 1.64%   |
| Marvell Technology Group | 2        | 1.64%   |
| Nvidia                   | 1        | 0.82%   |
| DisplayLink              | 1        | 0.82%   |
| Apple                    | 1        | 0.82%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 38       | 29.92%  |
| Intel I211 Gigabit Network Connection                               | 17       | 13.39%  |
| Realtek RTL8125 2.5GbE Controller                                   | 16       | 12.6%   |
| Intel Ethernet Controller I225-V                                    | 13       | 10.24%  |
| Intel Ethernet Connection (7) I219-V                                | 7        | 5.51%   |
| Intel Ethernet Connection (2) I219-V                                | 6        | 4.72%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 4        | 3.15%   |
| Intel I210 Gigabit Network Connection                               | 2        | 1.57%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                | 2        | 1.57%   |
| Intel 82574L Gigabit Network Connection                             | 2        | 1.57%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 1.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 1        | 0.79%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 1        | 0.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 1        | 0.79%   |
| Nvidia MCP61 Ethernet                                               | 1        | 0.79%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller             | 1        | 0.79%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller             | 1        | 0.79%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                    | 1        | 0.79%   |
| Intel Ethernet Connection I218-V                                    | 1        | 0.79%   |
| Intel Ethernet Connection I217-V                                    | 1        | 0.79%   |
| Intel Ethernet Connection (2) I219-LM                               | 1        | 0.79%   |
| Intel Ethernet Connection (14) I219-V                               | 1        | 0.79%   |
| Intel Ethernet Connection (11) I219-V                               | 1        | 0.79%   |
| Intel Ethernet Connection (11) I219-LM                              | 1        | 0.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 1        | 0.79%   |
| Intel 82575GB Gigabit Network Connection                            | 1        | 0.79%   |
| DisplayLink Dell D3100 Docking Station                              | 1        | 0.79%   |
| Aquantia Ethernet controller                                        | 1        | 0.79%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                     | 1        | 0.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 108      | 64.29%  |
| WiFi     | 57       | 33.93%  |
| Modem    | 3        | 1.79%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 94       | 81.74%  |
| WiFi     | 21       | 18.26%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 49       | 44.14%  |
| 2     | 45       | 40.54%  |
| 3     | 12       | 10.81%  |
| 4     | 2        | 1.8%    |
| 0     | 2        | 1.8%    |
| 5     | 1        | 0.9%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 77       | 70%     |
| Yes  | 33       | 30%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 45       | 69.23%  |
| Cambridge Silicon Radio         | 10       | 15.38%  |
| Realtek Semiconductor           | 2        | 3.08%   |
| MediaTek                        | 2        | 3.08%   |
| Foxconn / Hon Hai               | 2        | 3.08%   |
| Qualcomm Atheros Communications | 1        | 1.54%   |
| Broadcom                        | 1        | 1.54%   |
| ASUSTek Computer                | 1        | 1.54%   |
| Apple                           | 1        | 1.54%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 24       | 36.92%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 10       | 15.38%  |
| Intel AX210 Bluetooth                               | 6        | 9.23%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4        | 6.15%   |
| Intel AX201 Bluetooth                               | 4        | 6.15%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3        | 4.62%   |
| Realtek Bluetooth Radio                             | 2        | 3.08%   |
| MediaTek Wireless_Device                            | 2        | 3.08%   |
| Intel Bluetooth wireless interface                  | 2        | 3.08%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1        | 1.54%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 1.54%   |
| Intel Bluetooth Device                              | 1        | 1.54%   |
| Foxconn / Hon Hai Wireless_Device                   | 1        | 1.54%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1        | 1.54%   |
| Broadcom BCM20702A0                                 | 1        | 1.54%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 1.54%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 1        | 1.54%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD                                             | 79       | 32.11%  |
| Nvidia                                          | 43       | 17.48%  |
| Intel                                           | 42       | 17.07%  |
| C-Media Electronics                             | 11       | 4.47%   |
| ASUSTek Computer                                | 7        | 2.85%   |
| Thesycon Systemsoftware & Consulting            | 4        | 1.63%   |
| SteelSeries ApS                                 | 4        | 1.63%   |
| Logitech                                        | 4        | 1.63%   |
| Creative Technology                             | 4        | 1.63%   |
| Realtek Semiconductor                           | 3        | 1.22%   |
| Creative Labs                                   | 3        | 1.22%   |
| Yamaha                                          | 2        | 0.81%   |
| Sony                                            | 2        | 0.81%   |
| RODE Microphones                                | 2        | 0.81%   |
| Razer USA                                       | 2        | 0.81%   |
| Focusrite-Novation                              | 2        | 0.81%   |
| Corsair                                         | 2        | 0.81%   |
| Blue Microphones                                | 2        | 0.81%   |
| AudioQuest                                      | 2        | 0.81%   |
| Audio-Technica                                  | 2        | 0.81%   |
| Valve Software                                  | 1        | 0.41%   |
| Unknown                                         | 1        | 0.41%   |
| Tenx Technology                                 | 1        | 0.41%   |
| TEAC                                            | 1        | 0.41%   |
| Sennheiser Communications                       | 1        | 0.41%   |
| SAVITECH                                        | 1        | 0.41%   |
| Samson Technologies                             | 1        | 0.41%   |
| Nektar                                          | 1        | 0.41%   |
| MAG Technology                                  | 1        | 0.41%   |
| M-Audio                                         | 1        | 0.41%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.41%   |
| Kingston Technology                             | 1        | 0.41%   |
| JOUNIVO                                         | 1        | 0.41%   |
| JMTek                                           | 1        | 0.41%   |
| Huawei Technologies                             | 1        | 0.41%   |
| GN Netcom                                       | 1        | 0.41%   |
| Giga-Byte Technology                            | 1        | 0.41%   |
| Generalplus Technology                          | 1        | 0.41%   |
| FiiO Electronics Technology                     | 1        | 0.41%   |
| FIFINE Microphones                              | 1        | 0.41%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 35       | 12.24%  |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 22       | 7.69%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 14       | 4.9%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10       | 3.5%    |
| Intel Cannon Lake PCH cAVS                                                 | 7        | 2.45%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7        | 2.45%   |
| ASUSTek Computer USB Audio                                                 | 6        | 2.1%    |
| Nvidia GP106 High Definition Audio Controller                              | 5        | 1.75%   |
| Intel Alder Lake-S HD Audio Controller                                     | 5        | 1.75%   |
| Thesycon Systemsoftware & Consulting D10s                                  | 4        | 1.4%    |
| Nvidia TU104 HD Audio Controller                                           | 4        | 1.4%    |
| Nvidia GA106 High Definition Audio Controller                              | 4        | 1.4%    |
| Nvidia GA102 High Definition Audio Controller                              | 4        | 1.4%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 4        | 1.4%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4        | 1.4%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 4        | 1.4%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4        | 1.4%    |
| Nvidia TU106 High Definition Audio Controller                              | 3        | 1.05%   |
| Nvidia TU102 High Definition Audio Controller                              | 3        | 1.05%   |
| Nvidia GP104 High Definition Audio Controller                              | 3        | 1.05%   |
| Nvidia GP102 HDMI Audio Controller                                         | 3        | 1.05%   |
| Intel Comet Lake PCH cAVS                                                  | 3        | 1.05%   |
| AMD Navi 10 HDMI Audio                                                     | 3        | 1.05%   |
| AMD FCH Azalia Controller                                                  | 3        | 1.05%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3        | 1.05%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3        | 1.05%   |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 2        | 0.7%    |
| Realtek Semiconductor TX-384Khz Hifi Type-C Audio                          | 2        | 0.7%    |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 0.7%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 0.7%    |
| Nvidia GA104 High Definition Audio Controller                              | 2        | 0.7%    |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2        | 0.7%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 0.7%    |
| Intel 200 Series PCH HD Audio                                              | 2        | 0.7%    |
| Focusrite-Novation Scarlett 2i2 Camera                                     | 2        | 0.7%    |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 2        | 0.7%    |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 2        | 0.7%    |
| C-Media Electronics CM108 Audio Controller                                 | 2        | 0.7%    |
| C-Media Electronics Blue Snowball                                          | 2        | 0.7%    |
| Blue Microphones Yeti Stereo Microphone                                    | 2        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| G.Skill             | 24       | 20.69%  |
| Corsair             | 22       | 18.97%  |
| Kingston            | 20       | 17.24%  |
| Crucial             | 17       | 14.66%  |
| Unknown             | 7        | 6.03%   |
| Samsung Electronics | 6        | 5.17%   |
| Unknown             | 4        | 3.45%   |
| Team                | 3        | 2.59%   |
| Patriot             | 3        | 2.59%   |
| SK hynix            | 2        | 1.72%   |
| Micron Technology   | 2        | 1.72%   |
| A-DATA Technology   | 2        | 1.72%   |
| Ramaxel Technology  | 1        | 0.86%   |
| Patriot Memory      | 1        | 0.86%   |
| Nanya Technology    | 1        | 0.86%   |
| GOODRAM             | 1        | 0.86%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Unknown                                                   | 4        | 3.2%    |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s     | 3        | 2.4%    |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s     | 3        | 2.4%    |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3200MT/s    | 3        | 2.4%    |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s  | 3        | 2.4%    |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s        | 2        | 1.6%    |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s      | 2        | 1.6%    |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s       | 2        | 1.6%    |
| G.Skill RAM F4-3600C17-16GTZKW 16GB DIMM DDR4 3600MT/s    | 2        | 1.6%    |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s        | 2        | 1.6%    |
| Crucial RAM BL16G36C16U4RL.M8FB1 16GB DIMM DDR4 4000MT/s  | 2        | 1.6%    |
| Crucial RAM BL16G32C16U4B.M16FE1 16GB DIMM DDR4 3200MT/s  | 2        | 1.6%    |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s    | 2        | 1.6%    |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s    | 2        | 1.6%    |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s     | 2        | 1.6%    |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                 | 1        | 0.8%    |
| Unknown RAM Module 8GB DIMM 400MT/s                       | 1        | 0.8%    |
| Unknown RAM Module 8GB DIMM 1333MT/s                      | 1        | 0.8%    |
| Unknown RAM Module 512MB DIMM SDRAM                       | 1        | 0.8%    |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                  | 1        | 0.8%    |
| Unknown RAM Module 1GB DIMM SDRAM                         | 1        | 0.8%    |
| Unknown RAM Module 16GB DIMM DDR4 2133MT/s                | 1        | 0.8%    |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s     | 1        | 0.8%    |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s       | 1        | 0.8%    |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s        | 1        | 0.8%    |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s       | 1        | 0.8%    |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s      | 1        | 0.8%    |
| SK hynix RAM HMT425U6AFR6C-PB 2GB DIMM DDR3 1600MT/s      | 1        | 0.8%    |
| SK hynix RAM HMA84GR7CJR4N-XN 32GB DIMM DDR4 3200MT/s     | 1        | 0.8%    |
| Samsung RAM M393B5170FH0 4096MB DIMM DDR3 1333MT/s        | 1        | 0.8%    |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s      | 1        | 0.8%    |
| Samsung RAM M391A2K43BB1-CRC 16GB DIMM DDR4 2866MT/s      | 1        | 0.8%    |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s       | 1        | 0.8%    |
| Samsung RAM M378A2G43MX3-CTD 16GB DIMM DDR4 3466MT/s      | 1        | 0.8%    |
| Samsung RAM M378A1G44AB0-CWE 8GB DIMM DDR4 3200MT/s       | 1        | 0.8%    |
| Ramaxel RAM RMUA5090KB78HAF2133 8GB DIMM DDR4 2133MT/s    | 1        | 0.8%    |
| Patriot RAM 1600 CL9 Series 4GB DIMM DDR3 1600MT/s        | 1        | 0.8%    |
| Patriot Memory RAM 3200 C16 Series 4GB DIMM DDR4 3200MT/s | 1        | 0.8%    |
| Nanya RAM M2F4G64CB88B7N-DI 4GB DIMM DDR3 1600MT/s        | 1        | 0.8%    |
| Micron RAM 8ATF1G64AZ-3G2J1 8GB DIMM DDR4 3200MT/s        | 1        | 0.8%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 80       | 77.67%  |
| DDR3    | 16       | 15.53%  |
| DDR5    | 3        | 2.91%   |
| Unknown | 2        | 1.94%   |
| SDRAM   | 1        | 0.97%   |
| DDR2    | 1        | 0.97%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 103      | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 43       | 37.72%  |
| 16384 | 37       | 32.46%  |
| 32768 | 19       | 16.67%  |
| 4096  | 10       | 8.77%   |
| 2048  | 3        | 2.63%   |
| 1024  | 1        | 0.88%   |
| 512   | 1        | 0.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 30       | 25.86%  |
| 3600    | 15       | 12.93%  |
| 2133    | 9        | 7.76%   |
| 1600    | 8        | 6.9%    |
| 1333    | 6        | 5.17%   |
| 3733    | 5        | 4.31%   |
| 3400    | 5        | 4.31%   |
| 2667    | 5        | 4.31%   |
| 3866    | 4        | 3.45%   |
| 3000    | 4        | 3.45%   |
| 4800    | 3        | 2.59%   |
| 3466    | 3        | 2.59%   |
| 2400    | 3        | 2.59%   |
| 4000    | 2        | 1.72%   |
| 3666    | 2        | 1.72%   |
| 3800    | 1        | 0.86%   |
| 3334    | 1        | 0.86%   |
| 2933    | 1        | 0.86%   |
| 2866    | 1        | 0.86%   |
| 2733    | 1        | 0.86%   |
| 2666    | 1        | 0.86%   |
| 2197    | 1        | 0.86%   |
| 1867    | 1        | 0.86%   |
| 800     | 1        | 0.86%   |
| 667     | 1        | 0.86%   |
| 400     | 1        | 0.86%   |
| Unknown | 1        | 0.86%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 50%     |
| Canon           | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model               | Desktops | Percent |
|---------------------|----------|---------|
| HP LaserJet M14-M17 | 1        | 50%     |
| Canon LiDE 400      | 1        | 50%     |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 14       | 48.28%  |
| Sunplus Innovation Technology | 3        | 10.34%  |
| MacroSilicon                  | 2        | 6.9%    |
| YGTek                         | 1        | 3.45%   |
| Xiaomi                        | 1        | 3.45%   |
| Valve Software                | 1        | 3.45%   |
| Samsung Electronics           | 1        | 3.45%   |
| Ruision                       | 1        | 3.45%   |
| Microdia                      | 1        | 3.45%   |
| Generalplus Technology        | 1        | 3.45%   |
| Cubeternet                    | 1        | 3.45%   |
| Creative Technology           | 1        | 3.45%   |
| Chicony Electronics           | 1        | 3.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                                         | 3        | 10%     |
| Sunplus Full HD webcam                                              | 2        | 6.67%   |
| MacroSilicon USB Video                                              | 2        | 6.67%   |
| Logitech BRIO Ultra HD Webcam                                       | 2        | 6.67%   |
| YGTek Webcam                                                        | 1        | 3.33%   |
| Xiaomi MI 9                                                         | 1        | 3.33%   |
| Valve Software 3D Camera                                            | 1        | 3.33%   |
| Sunplus NexiGo N940 2K Webcam                                       | 1        | 3.33%   |
| Samsung Galaxy series, misc. (MTP mode)                             | 1        | 3.33%   |
| Ruision UVC Camera                                                  | 1        | 3.33%   |
| Microdia USB Live camera                                            | 1        | 3.33%   |
| MacroSilicon ShadowCast                                             | 1        | 3.33%   |
| Logitech Webcam C920-C                                              | 1        | 3.33%   |
| Logitech Webcam C270                                                | 1        | 3.33%   |
| Logitech Webcam C110                                                | 1        | 3.33%   |
| Logitech StreamCam                                                  | 1        | 3.33%   |
| Logitech QuickCam Orbit/Sphere AF                                   | 1        | 3.33%   |
| Logitech Logi 4K Stream Edition                                     | 1        | 3.33%   |
| Logitech HD Webcam C615                                             | 1        | 3.33%   |
| Logitech HD Webcam C525                                             | 1        | 3.33%   |
| Logitech HD Webcam C510                                             | 1        | 3.33%   |
| Generalplus GENERAL WEBCAM                                          | 1        | 3.33%   |
| Cubeternet EtronTech CMOS based eSP570 WebCam [Onyx Titanium TC101] | 1        | 3.33%   |
| Creative Live! Cam Sync 1080p                                       | 1        | 3.33%   |
| Chicony Gateway Webcam                                              | 1        | 3.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| DigitalPersona | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| DigitalPersona Fingerprint Reader | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Yubico.com            | 1        | 20%     |
| SCM Microsystems      | 1        | 20%     |
| Clay Logic            | 1        | 20%     |
| Aktiv                 | 1        | 20%     |
| Advanced Card Systems | 1        | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Yubico.com Yubikey 4/5 U2F+CCID                        | 1        | 20%     |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1        | 20%     |
| Clay Logic Nitrokey Pro                                | 1        | 20%     |
| Aktiv Rutoken lite                                     | 1        | 20%     |
| Advanced Card Systems ACR122U                          | 1        | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 73       | 64.04%  |
| 1     | 24       | 21.05%  |
| 2     | 10       | 8.77%   |
| 3     | 5        | 4.39%   |
| 4     | 2        | 1.75%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 13       | 22.41%  |
| Net/wireless             | 11       | 18.97%  |
| Sound                    | 7        | 12.07%  |
| Graphics card            | 7        | 12.07%  |
| Bluetooth                | 6        | 10.34%  |
| Chipcard                 | 3        | 5.17%   |
| Network                  | 2        | 3.45%   |
| Multimedia controller    | 2        | 3.45%   |
| Modem                    | 2        | 3.45%   |
| Storage/raid             | 1        | 1.72%   |
| Storage/ide              | 1        | 1.72%   |
| Storage/ata              | 1        | 1.72%   |
| Fingerprint reader       | 1        | 1.72%   |
| Camera                   | 1        | 1.72%   |

