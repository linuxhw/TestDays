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

Total: 165

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
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
| 5.15.59-gentoo               | 6        | 5.13%   |
| 5.15.52-gentoo-x86_64        | 5        | 4.27%   |
| 5.15.41-gentoo               | 5        | 4.27%   |
| 5.15.52-gentoo               | 4        | 3.42%   |
| 5.17.1-gentoo-r1             | 3        | 2.56%   |
| 5.15.41-gentoo-x86_64        | 3        | 2.56%   |
| 5.19.0-gentoo                | 2        | 1.71%   |
| 5.18.14-gentoo-x86_64        | 2        | 1.71%   |
| 5.18.10-gentoo               | 2        | 1.71%   |
| 5.17.0-gentoo                | 2        | 1.71%   |
| 5.16.11-gentoo-x86_64        | 2        | 1.71%   |
| 5.15.59-gentoo-x86_64        | 2        | 1.71%   |
| 5.15.52-gentoo-dist          | 2        | 1.71%   |
| 5.15.10-gentoo               | 2        | 1.71%   |
| 5.14.13-gentoo               | 2        | 1.71%   |
| 5.14.12-gentoo               | 2        | 1.71%   |
| 6.0.0-Phaco-g8f10ff49057f    | 1        | 0.85%   |
| 5.19.9-gentoo-x86_64         | 1        | 0.85%   |
| 5.19.9-gentoo                | 1        | 0.85%   |
| 5.19.8-xanmod1               | 1        | 0.85%   |
| 5.19.8-gentoo-clang-lto-prjc | 1        | 0.85%   |
| 5.19.7-gentoo-x86_64         | 1        | 0.85%   |
| 5.19.6-gentoo-x86_64         | 1        | 0.85%   |
| 5.19.11-renacuajo            | 1        | 0.85%   |
| 5.19.1-gentoo-a6             | 1        | 0.85%   |
| 5.19.0-xanmod1-x86_64        | 1        | 0.85%   |
| 5.19.0-gentoo-x86_64         | 1        | 0.85%   |
| 5.19.0-gentoo-carbon         | 1        | 0.85%   |
| 5.18.9-gentoo-x86_64         | 1        | 0.85%   |
| 5.18.9-gentoo                | 1        | 0.85%   |
| 5.18.7-gentoo                | 1        | 0.85%   |
| 5.18.6-gentoo-x86_64         | 1        | 0.85%   |
| 5.18.6-gentoo                | 1        | 0.85%   |
| 5.18.3-zen1                  | 1        | 0.85%   |
| 5.18.15-gentoo-x86_64        | 1        | 0.85%   |
| 5.18.15-gentoo               | 1        | 0.85%   |
| 5.18.14-gentoo               | 1        | 0.85%   |
| 5.18.10-k08                  | 1        | 0.85%   |
| 5.18.10-gentoo-x86_64        | 1        | 0.85%   |
| 5.18.1-gentoo-r2             | 1        | 0.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.52 | 12       | 10.26%  |
| 5.15.41 | 9        | 7.69%   |
| 5.15.59 | 8        | 6.84%   |
| 5.19.0  | 5        | 4.27%   |
| 5.18.10 | 4        | 3.42%   |
| 5.17.1  | 4        | 3.42%   |
| 5.18.14 | 3        | 2.56%   |
| 5.17.7  | 3        | 2.56%   |
| 5.17.0  | 3        | 2.56%   |
| 5.19.9  | 2        | 1.71%   |
| 5.19.8  | 2        | 1.71%   |
| 5.18.9  | 2        | 1.71%   |
| 5.18.6  | 2        | 1.71%   |
| 5.18.15 | 2        | 1.71%   |
| 5.17.9  | 2        | 1.71%   |
| 5.17.3  | 2        | 1.71%   |
| 5.17.2  | 2        | 1.71%   |
| 5.16.14 | 2        | 1.71%   |
| 5.16.11 | 2        | 1.71%   |
| 5.15.2  | 2        | 1.71%   |
| 5.15.10 | 2        | 1.71%   |
| 5.14.14 | 2        | 1.71%   |
| 5.14.13 | 2        | 1.71%   |
| 5.14.12 | 2        | 1.71%   |
| 6.0.0   | 1        | 0.85%   |
| 5.19.7  | 1        | 0.85%   |
| 5.19.6  | 1        | 0.85%   |
| 5.19.11 | 1        | 0.85%   |
| 5.19.1  | 1        | 0.85%   |
| 5.18.7  | 1        | 0.85%   |
| 5.18.3  | 1        | 0.85%   |
| 5.18.1  | 1        | 0.85%   |
| 5.18.0  | 1        | 0.85%   |
| 5.17.8  | 1        | 0.85%   |
| 5.17.6  | 1        | 0.85%   |
| 5.16.8  | 1        | 0.85%   |
| 5.16.7  | 1        | 0.85%   |
| 5.16.5  | 1        | 0.85%   |
| 5.16.4  | 1        | 0.85%   |
| 5.16.2  | 1        | 0.85%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 38       | 35.51%  |
| 5.18    | 16       | 14.95%  |
| 5.17    | 15       | 14.02%  |
| 5.19    | 13       | 12.15%  |
| 5.16    | 11       | 10.28%  |
| 5.14    | 9        | 8.41%   |
| 5.10    | 2        | 1.87%   |
| 6.0     | 1        | 0.93%   |
| 4.9     | 1        | 0.93%   |
| 4.14    | 1        | 0.93%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| x86_64   | 94       | 97.92%  |
| ppc      | 1        | 1.04%   |
| armv5tel | 1        | 1.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| KDE5     | 35       | 35.71%  |
| Unknown  | 29       | 29.59%  |
| GNOME    | 18       | 18.37%  |
| XFCE     | 7        | 7.14%   |
| MATE     | 3        | 3.06%   |
| DWM      | 2        | 2.04%   |
| LXQt     | 1        | 1.02%   |
| KDE      | 1        | 1.02%   |
| i3       | 1        | 1.02%   |
| Cinnamon | 1        | 1.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 48       | 48%     |
| Wayland | 20       | 20%     |
| Tty     | 19       | 19%     |
| Unknown | 13       | 13%     |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 38       | 38.78%  |
| SDDM    | 34       | 34.69%  |
| GDM     | 11       | 11.22%  |
| LightDM | 7        | 7.14%   |
| LXDM    | 4        | 4.08%   |
| XDM     | 2        | 2.04%   |
| SLiM    | 2        | 2.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 38       | 39.58%  |
| en_GB      | 13       | 13.54%  |
| Unknown    | 9        | 9.38%   |
| ru_RU      | 6        | 6.25%   |
| de_DE      | 6        | 6.25%   |
| C.UTF8     | 5        | 5.21%   |
| pl_PL      | 4        | 4.17%   |
| pt_BR      | 2        | 2.08%   |
| es_ES      | 2        | 2.08%   |
| C          | 2        | 2.08%   |
| zh_TW      | 1        | 1.04%   |
| sl_SI      | 1        | 1.04%   |
| ja_JP      | 1        | 1.04%   |
| fr_FR      | 1        | 1.04%   |
| en_US.UTF8 | 1        | 1.04%   |
| en_CA      | 1        | 1.04%   |
| el_GR      | 1        | 1.04%   |
| de_CH      | 1        | 1.04%   |
| cs_CZ      | 1        | 1.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 85       | 86.73%  |
| BIOS | 13       | 13.27%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 55       | 57.29%  |
| Btrfs   | 23       | 23.96%  |
| F2fs    | 9        | 9.38%   |
| Zfs     | 3        | 3.13%   |
| Xfs     | 3        | 3.13%   |
| XXXXXXX | 2        | 2.08%   |
| XXX     | 1        | 1.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 90       | 91.84%  |
| Unknown | 6        | 6.12%   |
| MBR     | 2        | 2.04%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 54       | 55.67%  |
| Yes       | 43       | 44.33%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 53       | 55.21%  |
| Yes       | 43       | 44.79%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 39       | 40.63%  |
| MSI                 | 17       | 17.71%  |
| Gigabyte Technology | 14       | 14.58%  |
| ASRock              | 14       | 14.58%  |
| Dell                | 3        | 3.13%   |
| Lenovo              | 2        | 2.08%   |
| Intel               | 2        | 2.08%   |
| Unknown             | 2        | 2.08%   |
| Pegatron            | 1        | 1.04%   |
| Fujitsu             | 1        | 1.04%   |
| EVGA                | 1        | 1.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUS ROG STRIX B550-F GAMING        | 3        | 3.13%   |
| MSI MS-7C02                         | 2        | 2.08%   |
| MSI MS-7B89                         | 2        | 2.08%   |
| ASUS Z170-A                         | 2        | 2.08%   |
| ASUS TUF Gaming X570-PLUS           | 2        | 2.08%   |
| ASUS TUF Gaming B550-PLUS           | 2        | 2.08%   |
| ASUS ROG STRIX X570-E GAMING        | 2        | 2.08%   |
| ASUS ROG STRIX B450-F GAMING        | 2        | 2.08%   |
| ASUS ROG CROSSHAIR VIII HERO        | 2        | 2.08%   |
| ASUS ROG CROSSHAIR VIII DARK HERO   | 2        | 2.08%   |
| Unknown                             | 2        | 2.08%   |
| Pegatron 810-170st                  | 1        | 1.04%   |
| MSI MS-7D31                         | 1        | 1.04%   |
| MSI MS-7D25                         | 1        | 1.04%   |
| MSI MS-7D09                         | 1        | 1.04%   |
| MSI MS-7C94                         | 1        | 1.04%   |
| MSI MS-7C56                         | 1        | 1.04%   |
| MSI MS-7C37                         | 1        | 1.04%   |
| MSI MS-7C35                         | 1        | 1.04%   |
| MSI MS-7B98                         | 1        | 1.04%   |
| MSI MS-7B86                         | 1        | 1.04%   |
| MSI MS-7B85                         | 1        | 1.04%   |
| MSI MS-7B17                         | 1        | 1.04%   |
| MSI MS-7996                         | 1        | 1.04%   |
| MSI MS-7821                         | 1        | 1.04%   |
| Lenovo ThinkStation P620 30E0001TGE | 1        | 1.04%   |
| Lenovo Legion T5 26AMR5 90RB0002US  | 1        | 1.04%   |
| Intel X79                           | 1        | 1.04%   |
| Intel D54250WYK H13922-303          | 1        | 1.04%   |
| Gigabyte Z87X-UD3H                  | 1        | 1.04%   |
| Gigabyte Z77X-D3H                   | 1        | 1.04%   |
| Gigabyte Z690 AORUS MASTER          | 1        | 1.04%   |
| Gigabyte Z590 UD                    | 1        | 1.04%   |
| Gigabyte Z490 UD                    | 1        | 1.04%   |
| Gigabyte X570 AORUS MASTER          | 1        | 1.04%   |
| Gigabyte H470 HD3                   | 1        | 1.04%   |
| Gigabyte B660 GAMING X AX DDR4      | 1        | 1.04%   |
| Gigabyte B550M DS3H                 | 1        | 1.04%   |
| Gigabyte B450M S2H                  | 1        | 1.04%   |
| Gigabyte B450 GAMING X              | 1        | 1.04%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS ROG              | 20       | 20.83%  |
| ASUS TUF              | 8        | 8.33%   |
| ASUS PRIME            | 4        | 4.17%   |
| MSI MS-7C02           | 2        | 2.08%   |
| MSI MS-7B89           | 2        | 2.08%   |
| Gigabyte B450         | 2        | 2.08%   |
| Dell OptiPlex         | 2        | 2.08%   |
| ASUS Z170-A           | 2        | 2.08%   |
| ASRock X370           | 2        | 2.08%   |
| Unknown               | 2        | 2.08%   |
| Pegatron 810-170st    | 1        | 1.04%   |
| MSI MS-7D31           | 1        | 1.04%   |
| MSI MS-7D25           | 1        | 1.04%   |
| MSI MS-7D09           | 1        | 1.04%   |
| MSI MS-7C94           | 1        | 1.04%   |
| MSI MS-7C56           | 1        | 1.04%   |
| MSI MS-7C37           | 1        | 1.04%   |
| MSI MS-7C35           | 1        | 1.04%   |
| MSI MS-7B98           | 1        | 1.04%   |
| MSI MS-7B86           | 1        | 1.04%   |
| MSI MS-7B85           | 1        | 1.04%   |
| MSI MS-7B17           | 1        | 1.04%   |
| MSI MS-7996           | 1        | 1.04%   |
| MSI MS-7821           | 1        | 1.04%   |
| Lenovo ThinkStation   | 1        | 1.04%   |
| Lenovo Legion         | 1        | 1.04%   |
| Intel X79             | 1        | 1.04%   |
| Intel D54250WYK       | 1        | 1.04%   |
| Gigabyte Z87X-UD3H    | 1        | 1.04%   |
| Gigabyte Z77X-D3H     | 1        | 1.04%   |
| Gigabyte Z690         | 1        | 1.04%   |
| Gigabyte Z590         | 1        | 1.04%   |
| Gigabyte Z490         | 1        | 1.04%   |
| Gigabyte X570         | 1        | 1.04%   |
| Gigabyte H470         | 1        | 1.04%   |
| Gigabyte B660         | 1        | 1.04%   |
| Gigabyte B550M        | 1        | 1.04%   |
| Gigabyte B450M        | 1        | 1.04%   |
| Gigabyte AB350-Gaming | 1        | 1.04%   |
| Gigabyte 970A-DS3     | 1        | 1.04%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2020    | 18       | 18.75%  |
| 2019    | 16       | 16.67%  |
| 2018    | 15       | 15.63%  |
| 2021    | 14       | 14.58%  |
| 2017    | 7        | 7.29%   |
| 2016    | 4        | 4.17%   |
| 2014    | 4        | 4.17%   |
| 2013    | 4        | 4.17%   |
| 2015    | 3        | 3.13%   |
| 2022    | 2        | 2.08%   |
| 2012    | 2        | 2.08%   |
| 2011    | 2        | 2.08%   |
| Unknown | 2        | 2.08%   |
| 2010    | 1        | 1.04%   |
| 2008    | 1        | 1.04%   |
| 2005    | 1        | 1.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 96       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 94       | 96.91%  |
| Enabled  | 3        | 3.09%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 96       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 43       | 44.79%  |
| 64.01-256.0 | 20       | 20.83%  |
| 16.01-24.0  | 16       | 16.67%  |
| 24.01-32.0  | 5        | 5.21%   |
| 8.01-16.0   | 5        | 5.21%   |
| 4.01-8.0    | 4        | 4.17%   |
| 0.51-1.0    | 2        | 2.08%   |
| 2.01-3.0    | 1        | 1.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 28       | 25.23%  |
| 8.01-16.0  | 20       | 18.02%  |
| 2.01-3.0   | 17       | 15.32%  |
| 1.01-2.0   | 14       | 12.61%  |
| 3.01-4.0   | 10       | 9.01%   |
| 16.01-24.0 | 8        | 7.21%   |
| 0.51-1.0   | 5        | 4.5%    |
| 0.01-0.5   | 4        | 3.6%    |
| 32.01-64.0 | 2        | 1.8%    |
| 24.01-32.0 | 2        | 1.8%    |
| 0          | 1        | 0.9%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 32       | 32.65%  |
| 3      | 23       | 23.47%  |
| 4      | 12       | 12.24%  |
| 5      | 10       | 10.2%   |
| 1      | 8        | 8.16%   |
| 6      | 7        | 7.14%   |
| 7      | 5        | 5.1%    |
| 12     | 1        | 1.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 79       | 80.61%  |
| Yes       | 19       | 19.39%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 94       | 97.92%  |
| No        | 2        | 2.08%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 49       | 50.52%  |
| No        | 48       | 49.48%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 53       | 54.64%  |
| No        | 44       | 45.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 25       | 26.04%  |
| Germany     | 15       | 15.63%  |
| Russia      | 9        | 9.38%   |
| Poland      | 9        | 9.38%   |
| UK          | 5        | 5.21%   |
| Switzerland | 3        | 3.13%   |
| Spain       | 3        | 3.13%   |
| Czechia     | 3        | 3.13%   |
| China       | 2        | 2.08%   |
| Canada      | 2        | 2.08%   |
| Brazil      | 2        | 2.08%   |
| Taiwan      | 1        | 1.04%   |
| Slovenia    | 1        | 1.04%   |
| Slovakia    | 1        | 1.04%   |
| Romania     | 1        | 1.04%   |
| Netherlands | 1        | 1.04%   |
| Mexico      | 1        | 1.04%   |
| Malaysia    | 1        | 1.04%   |
| Japan       | 1        | 1.04%   |
| Ireland     | 1        | 1.04%   |
| India       | 1        | 1.04%   |
| Hong Kong   | 1        | 1.04%   |
| Greece      | 1        | 1.04%   |
| France      | 1        | 1.04%   |
| Finland     | 1        | 1.04%   |
| Belarus     | 1        | 1.04%   |
| Bangladesh  | 1        | 1.04%   |
| Australia   | 1        | 1.04%   |
| Argentina   | 1        | 1.04%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Moscow                  | 4        | 4.08%   |
| Swansea                 | 3        | 3.06%   |
| Cieszyn                 | 3        | 3.06%   |
| Zurich                  | 2        | 2.04%   |
| Warsaw                  | 2        | 2.04%   |
| Seattle                 | 2        | 2.04%   |
| Los Angeles             | 2        | 2.04%   |
| Berlin                  | 2        | 2.04%   |
| Yekaterinburg           | 1        | 1.02%   |
| Wroclaw                 | 1        | 1.02%   |
| Wrentham                | 1        | 1.02%   |
| Warren                  | 1        | 1.02%   |
| Vladivostok             | 1        | 1.02%   |
| Villanueva del Pardillo | 1        | 1.02%   |
| Vigo                    | 1        | 1.02%   |
| Vancouver               | 1        | 1.02%   |
| Ufa                     | 1        | 1.02%   |
| Troisdorf               | 1        | 1.02%   |
| Trnava                  | 1        | 1.02%   |
| Tonbridge               | 1        | 1.02%   |
| Thibodaux               | 1        | 1.02%   |
| Texas City              | 1        | 1.02%   |
| Taichung City           | 1        | 1.02%   |
| Sydney                  | 1        | 1.02%   |
| Svobodnyy               | 1        | 1.02%   |
| Stuttgart               | 1        | 1.02%   |
| Sterling                | 1        | 1.02%   |
| Stasi Las               | 1        | 1.02%   |
| St. Cloud               | 1        | 1.02%   |
| St Louis                | 1        | 1.02%   |
| Schwieberdingen         | 1        | 1.02%   |
| Sao Paulo               | 1        | 1.02%   |
| Santa Teresinha         | 1        | 1.02%   |
| Sankt Wendel            | 1        | 1.02%   |
| Rostock                 | 1        | 1.02%   |
| Rosario                 | 1        | 1.02%   |
| Renens                  | 1        | 1.02%   |
| Redmond                 | 1        | 1.02%   |
| Radovljica              | 1        | 1.02%   |
| Prague                  | 1        | 1.02%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 52       | 119    | 23.64%  |
| WDC                 | 43       | 76     | 19.55%  |
| Seagate             | 29       | 65     | 13.18%  |
| Toshiba             | 17       | 27     | 7.73%   |
| Kingston            | 9        | 10     | 4.09%   |
| Hitachi             | 9        | 24     | 4.09%   |
| Crucial             | 8        | 16     | 3.64%   |
| SanDisk             | 7        | 9      | 3.18%   |
| Intel               | 5        | 6      | 2.27%   |
| HGST                | 5        | 6      | 2.27%   |
| A-DATA Technology   | 5        | 6      | 2.27%   |
| Phison              | 4        | 6      | 1.82%   |
| Corsair             | 4        | 5      | 1.82%   |
| OCZ                 | 3        | 3      | 1.36%   |
| GOODRAM             | 3        | 9      | 1.36%   |
| KIOXIA-EXCERIA      | 2        | 3      | 0.91%   |
| Kingchuxing         | 2        | 5      | 0.91%   |
| Unknown             | 1        | 1      | 0.45%   |
| Transcend           | 1        | 1      | 0.45%   |
| Team                | 1        | 3      | 0.45%   |
| SK hynix            | 1        | 2      | 0.45%   |
| Silicon Motion      | 1        | 2      | 0.45%   |
| PNY                 | 1        | 1      | 0.45%   |
| Plextor             | 1        | 2      | 0.45%   |
| Patriot             | 1        | 1      | 0.45%   |
| OCZ-VERTEX          | 1        | 1      | 0.45%   |
| LaCie               | 1        | 2      | 0.45%   |
| Fujitsu             | 1        | 1      | 0.45%   |
| Apacer              | 1        | 1      | 0.45%   |
| ADATA Technology    | 1        | 1      | 0.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Samsung SSD 970 EVO 500GB        | 5        | 1.7%    |
| Toshiba DT01ACA100 1TB           | 4        | 1.36%   |
| Samsung SSD 980 PRO 1TB          | 4        | 1.36%   |
| Samsung SSD 970 EVO Plus 500GB   | 4        | 1.36%   |
| WDC WD40EZRZ-00GXCB0 4TB         | 3        | 1.02%   |
| Seagate ST4000DM004-2CV104 4TB   | 3        | 1.02%   |
| Seagate ST2000DM006-2DM164 2TB   | 3        | 1.02%   |
| Samsung SSD 980 PRO 2TB          | 3        | 1.02%   |
| Samsung SSD 980 1TB              | 3        | 1.02%   |
| Samsung SSD 970 EVO Plus 2TB     | 3        | 1.02%   |
| Samsung SSD 870 EVO 1TB          | 3        | 1.02%   |
| Samsung SSD 860 EVO 1TB          | 3        | 1.02%   |
| Samsung SSD 850 EVO 500GB        | 3        | 1.02%   |
| Samsung SSD 850 EVO 250GB        | 3        | 1.02%   |
| Crucial CT2000MX500SSD1 2TB      | 3        | 1.02%   |
| Crucial CT1000MX500SSD1 1TB      | 3        | 1.02%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 2        | 0.68%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 2        | 0.68%   |
| WDC WD30EFRX-68EUZN0 3TB         | 2        | 0.68%   |
| WDC WD30EFRX-68AX9N0 3TB         | 2        | 0.68%   |
| WDC WD10EZEX-08M2NA0 1TB         | 2        | 0.68%   |
| Seagate ST4000DM005-2DP166 4TB   | 2        | 0.68%   |
| Seagate ST2000DM001-1ER164 2TB   | 2        | 0.68%   |
| Seagate ST2000DM001-1CH164 2TB   | 2        | 0.68%   |
| Samsung SSD 980 PRO 500GB        | 2        | 0.68%   |
| Samsung SSD 970 PRO 1TB          | 2        | 0.68%   |
| Samsung SSD 970 EVO Plus 250GB   | 2        | 0.68%   |
| Samsung SSD 970 EVO Plus 1TB     | 2        | 0.68%   |
| Samsung SSD 970 EVO 250GB        | 2        | 0.68%   |
| Samsung SSD 870 EVO 500GB        | 2        | 0.68%   |
| Samsung SSD 860 QVO 2TB          | 2        | 0.68%   |
| Samsung SSD 860 PRO 4TB          | 2        | 0.68%   |
| Samsung SSD 850 PRO 512GB        | 2        | 0.68%   |
| Samsung SSD 850 PRO 256GB        | 2        | 0.68%   |
| Samsung SSD 840 PRO Series 128GB | 2        | 0.68%   |
| Samsung NVMe SSD Drive 512GB     | 2        | 0.68%   |
| Samsung NVMe SSD Drive 500GB     | 2        | 0.68%   |
| Samsung NVMe SSD Drive 2TB       | 2        | 0.68%   |
| Samsung NVMe SSD Drive 1TB       | 2        | 0.68%   |
| Phison Sabrent Rocket 4.0 1TB    | 2        | 0.68%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 34       | 61     | 36.96%  |
| Seagate             | 27       | 62     | 29.35%  |
| Toshiba             | 14       | 22     | 15.22%  |
| Hitachi             | 9        | 24     | 9.78%   |
| HGST                | 5        | 6      | 5.43%   |
| Samsung Electronics | 1        | 1      | 1.09%   |
| LaCie               | 1        | 2      | 1.09%   |
| Fujitsu             | 1        | 1      | 1.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 30       | 49     | 38.96%  |
| Kingston            | 7        | 8      | 9.09%   |
| Crucial             | 7        | 13     | 9.09%   |
| WDC                 | 6        | 7      | 7.79%   |
| SanDisk             | 6        | 8      | 7.79%   |
| OCZ                 | 3        | 3      | 3.9%    |
| Intel               | 3        | 3      | 3.9%    |
| GOODRAM             | 3        | 9      | 3.9%    |
| Corsair             | 3        | 4      | 3.9%    |
| A-DATA Technology   | 2        | 2      | 2.6%    |
| Transcend           | 1        | 1      | 1.3%    |
| Toshiba             | 1        | 2      | 1.3%    |
| PNY                 | 1        | 1      | 1.3%    |
| Patriot             | 1        | 1      | 1.3%    |
| OCZ-VERTEX          | 1        | 1      | 1.3%    |
| Kingchuxing         | 1        | 1      | 1.3%    |
| Apacer              | 1        | 1      | 1.3%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 66       | 179    | 34.74%  |
| NVMe    | 62       | 120    | 32.63%  |
| SSD     | 61       | 114    | 32.11%  |
| Unknown | 1        | 1      | 0.53%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 89       | 289    | 58.17%  |
| NVMe | 62       | 120    | 40.52%  |
| SAS  | 2        | 5      | 1.31%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 46       | 86     | 29.3%   |
| 0.51-1.0   | 42       | 57     | 26.75%  |
| 1.01-2.0   | 30       | 49     | 19.11%  |
| 3.01-4.0   | 17       | 25     | 10.83%  |
| 4.01-10.0  | 12       | 47     | 7.64%   |
| 2.01-3.0   | 7        | 21     | 4.46%   |
| 10.01-20.0 | 3        | 8      | 1.91%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 22       | 22%     |
| 1001-2000      | 18       | 18%     |
| 501-1000       | 16       | 16%     |
| 251-500        | 13       | 13%     |
| 2001-3000      | 12       | 12%     |
| 101-250        | 7        | 7%      |
| 1-20           | 4        | 4%      |
| 51-100         | 3        | 3%      |
| Unknown        | 3        | 3%      |
| 21-50          | 2        | 2%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 16       | 15.84%  |
| 1001-2000      | 16       | 15.84%  |
| More than 3000 | 13       | 12.87%  |
| 1-20           | 13       | 12.87%  |
| 501-1000       | 12       | 11.88%  |
| 101-250        | 11       | 10.89%  |
| 21-50          | 7        | 6.93%   |
| 51-100         | 6        | 5.94%   |
| 2001-3000      | 4        | 3.96%   |
| Unknown        | 3        | 2.97%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Samsung Electronics SSD 870 EVO 500GB | 2        | 2      | 6.45%   |
| WDC WD60EFRX-68L0BN1 6TB              | 1        | 3      | 3.23%   |
| WDC WD40EFRX-68N32N0 4TB              | 1        | 1      | 3.23%   |
| WDC WD30EFRX-68AX9N0 3TB              | 1        | 2      | 3.23%   |
| WDC WD20EZRX-00D8PB0 2TB              | 1        | 1      | 3.23%   |
| WDC WD20EFRX-68AX9N0 2TB              | 1        | 1      | 3.23%   |
| WDC WD20EARS-00J2GB0 2TB              | 1        | 1      | 3.23%   |
| WDC WD1600AAJS-75B4A0 160GB           | 1        | 1      | 3.23%   |
| WDC WD10EFRX-68JCSN0 1TB              | 1        | 1      | 3.23%   |
| WDC WD1002FBYS-18W8B0 1TB             | 1        | 1      | 3.23%   |
| Transcend TS512GSSD720 512GB          | 1        | 1      | 3.23%   |
| Toshiba HDWA120 2TB                   | 1        | 1      | 3.23%   |
| Seagate ST3160023AS 160GB             | 1        | 1      | 3.23%   |
| Seagate ST3000DM001-9YN166 3TB        | 1        | 1      | 3.23%   |
| Seagate ST2000DX001-1CM164 2TB        | 1        | 1      | 3.23%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1        | 1      | 3.23%   |
| Seagate ST10000VN0004-1ZD101 10TB     | 1        | 4      | 3.23%   |
| SanDisk SSD PLUS 1000GB               | 1        | 1      | 3.23%   |
| Samsung Electronics SSD 980 PRO 2TB   | 1        | 1      | 3.23%   |
| Samsung Electronics SSD 980 1TB       | 1        | 1      | 3.23%   |
| Samsung Electronics SSD 970 EVO 1TB   | 1        | 2      | 3.23%   |
| Samsung Electronics SSD 870 EVO 1TB   | 1        | 1      | 3.23%   |
| Samsung Electronics SSD 850 PRO 256GB | 1        | 4      | 3.23%   |
| Samsung Electronics HD103SJ 1TB       | 1        | 1      | 3.23%   |
| OCZ VERTEX4 128GB SSD                 | 1        | 1      | 3.23%   |
| Kingston SV100S2128G 128GB SSD        | 1        | 1      | 3.23%   |
| Hitachi HUA721010KLA330 1TB           | 1        | 1      | 3.23%   |
| Hitachi HTS541680J9SA00 80GB          | 1        | 1      | 3.23%   |
| Hitachi HDS722020ALA330 2TB           | 1        | 2      | 3.23%   |
| Crucial CT525MX300SSD1 528GB          | 1        | 1      | 3.23%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 9        | 12     | 30%     |
| Samsung Electronics | 7        | 12     | 23.33%  |
| Seagate             | 5        | 8      | 16.67%  |
| Hitachi             | 3        | 4      | 10%     |
| Transcend           | 1        | 1      | 3.33%   |
| Toshiba             | 1        | 1      | 3.33%   |
| SanDisk             | 1        | 1      | 3.33%   |
| OCZ                 | 1        | 1      | 3.33%   |
| Kingston            | 1        | 1      | 3.33%   |
| Crucial             | 1        | 1      | 3.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 9        | 12     | 47.37%  |
| Seagate             | 5        | 8      | 26.32%  |
| Hitachi             | 3        | 4      | 15.79%  |
| Toshiba             | 1        | 1      | 5.26%   |
| Samsung Electronics | 1        | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 17       | 26     | 58.62%  |
| SSD  | 9        | 12     | 31.03%  |
| NVMe | 3        | 4      | 10.34%  |

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
| Works    | 88       | 337    | 70.97%  |
| Malfunc  | 26       | 42     | 20.97%  |
| Detected | 9        | 34     | 7.26%   |
| Failed   | 1        | 1      | 0.81%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| AMD                            | 51       | 28.02%  |
| Intel                          | 42       | 23.08%  |
| Samsung Electronics            | 38       | 20.88%  |
| ASMedia Technology             | 9        | 4.95%   |
| SanDisk                        | 8        | 4.4%    |
| Phison Electronics             | 6        | 3.3%    |
| ADATA Technology               | 4        | 2.2%    |
| Toshiba America Info Systems   | 3        | 1.65%   |
| Silicon Motion                 | 3        | 1.65%   |
| Marvell Technology Group       | 3        | 1.65%   |
| Seagate Technology             | 2        | 1.1%    |
| Micron/Crucial Technology      | 2        | 1.1%    |
| KIOXIA                         | 2        | 1.1%    |
| Kingston Technology Company    | 2        | 1.1%    |
| Broadcom / LSI                 | 2        | 1.1%    |
| Unknown                        | 1        | 0.55%   |
| Solid State Storage Technology | 1        | 0.55%   |
| SK hynix                       | 1        | 0.55%   |
| Silicon Image                  | 1        | 0.55%   |
| JMicron Technology             | 1        | 0.55%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 35       | 16.91%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 25       | 12.08%  |
| AMD 400 Series Chipset SATA Controller                                         | 14       | 6.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 11       | 5.31%   |
| AMD 500 Series Chipset SATA Controller                                         | 10       | 4.83%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 8        | 3.86%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 7        | 3.38%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 7        | 3.38%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 5        | 2.42%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 5        | 2.42%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 4        | 1.93%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 3        | 1.45%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 3        | 1.45%   |
| Samsung NVMe SSD Controller 980                                                | 3        | 1.45%   |
| Phison E16 PCIe4 NVMe Controller                                               | 3        | 1.45%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3        | 1.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3        | 1.45%   |
| Seagate FireCuda 520 SSD                                                       | 2        | 0.97%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2        | 0.97%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2        | 0.97%   |
| Phison E12 NVMe Controller                                                     | 2        | 0.97%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 2        | 0.97%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2        | 0.97%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 2        | 0.97%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2        | 0.97%   |
| AMD X370 Series Chipset SATA Controller                                        | 2        | 0.97%   |
| AMD 300 Series Chipset SATA Controller                                         | 2        | 0.97%   |
| Unknown Non-Volatile memory controller                                         | 1        | 0.48%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1        | 0.48%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1        | 0.48%   |
| Toshiba America Info Systems NVMe Controller                                   | 1        | 0.48%   |
| Solid State Storage Non-Volatile memory controller                             | 1        | 0.48%   |
| SK hynix Non-Volatile memory controller                                        | 1        | 0.48%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1        | 0.48%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1        | 0.48%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 1        | 0.48%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1        | 0.48%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1        | 0.48%   |
| Phison E7 NVMe Controller                                                      | 1        | 0.48%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1        | 0.48%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 91       | 56.17%  |
| NVMe | 62       | 38.27%  |
| RAID | 4        | 2.47%   |
| IDE  | 3        | 1.85%   |
| SAS  | 2        | 1.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| AMD                   | 51       | 53.13%  |
| Intel                 | 43       | 44.79%  |
| PowerBook6,7          | 1        | 1.04%   |
| Marvell Semiconductor | 1        | 1.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                                                    | Desktops | Percent |
|--------------------------------------------------------------------------|----------|---------|
| AMD Ryzen 9 5900X 12-Core Processor                                      | 6        | 6.25%   |
| AMD Ryzen 9 5950X 16-Core Processor                                      | 4        | 4.17%   |
| AMD Ryzen 9 3950X 16-Core Processor                                      | 4        | 4.17%   |
| AMD Ryzen 9 3900X 12-Core Processor                                      | 4        | 4.17%   |
| AMD Ryzen 5 3600 6-Core Processor                                        | 4        | 4.17%   |
| AMD Ryzen 5 2600 Six-Core Processor                                      | 4        | 4.17%   |
| Intel Core i7-6700K CPU @ 4.00GHz                                        | 3        | 3.13%   |
| AMD Ryzen 7 3700X 8-Core Processor                                       | 3        | 3.13%   |
| Intel Core i9-9900K CPU @ 3.60GHz                                        | 2        | 2.08%   |
| Intel Core i7-8700K CPU @ 3.70GHz                                        | 2        | 2.08%   |
| Intel Core i5-9600K CPU @ 3.70GHz                                        | 2        | 2.08%   |
| Intel 12th Gen Core i9-12900K                                            | 2        | 2.08%   |
| Intel 12th Gen Core i7-12700K                                            | 2        | 2.08%   |
| Intel 11th Gen Core i9-11900KF @ 3.50GHz                                 | 2        | 2.08%   |
| AMD Ryzen 7 3800X 8-Core Processor                                       | 2        | 2.08%   |
| AMD Ryzen 7 2700X Eight-Core Processor                                   | 2        | 2.08%   |
| AMD Ryzen 5 5600X 6-Core Processor                                       | 2        | 2.08%   |
| AMD Ryzen 5 1600 Six-Core Processor                                      | 2        | 2.08%   |
| PowerBook6,7 7447A, altivec supported                                    | 1        | 1.04%   |
| Marvell Semiconductor Marvell Kirkwood (Flattened Device Tree) Processor | 1        | 1.04%   |
| Intel Xeon CPU X5690 @ 3.47GHz                                           | 1        | 1.04%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz                                      | 1        | 1.04%   |
| Intel Xeon CPU E3-1275 v6 @ 3.80GHz                                      | 1        | 1.04%   |
| Intel Pentium 4 CPU 3.20GHz                                              | 1        | 1.04%   |
| Intel Core i7-9700F CPU @ 3.00GHz                                        | 1        | 1.04%   |
| Intel Core i7-8086K CPU @ 4.00GHz                                        | 1        | 1.04%   |
| Intel Core i7-4930K CPU @ 3.40GHz                                        | 1        | 1.04%   |
| Intel Core i7-4790K CPU @ 4.00GHz                                        | 1        | 1.04%   |
| Intel Core i7-4790 CPU @ 3.60GHz                                         | 1        | 1.04%   |
| Intel Core i7-10700F CPU @ 2.90GHz                                       | 1        | 1.04%   |
| Intel Core i7-10700 CPU @ 2.90GHz                                        | 1        | 1.04%   |
| Intel Core i5-7400 CPU @ 3.00GHz                                         | 1        | 1.04%   |
| Intel Core i5-6500 CPU @ 3.20GHz                                         | 1        | 1.04%   |
| Intel Core i5-6400 CPU @ 2.70GHz                                         | 1        | 1.04%   |
| Intel Core i5-4670K CPU @ 3.40GHz                                        | 1        | 1.04%   |
| Intel Core i5-4250U CPU @ 1.30GHz                                        | 1        | 1.04%   |
| Intel Core i5-3550 CPU @ 3.30GHz                                         | 1        | 1.04%   |
| Intel Core i5-2500S CPU @ 2.70GHz                                        | 1        | 1.04%   |
| Intel Core i5-2500K CPU @ 3.30GHz                                        | 1        | 1.04%   |
| Intel Core i5-2400 CPU @ 3.10GHz                                         | 1        | 1.04%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| AMD Ryzen 9            | 18       | 18.75%  |
| AMD Ryzen 5            | 14       | 14.58%  |
| Other                  | 13       | 13.54%  |
| Intel Core i5          | 13       | 13.54%  |
| Intel Core i7          | 12       | 12.5%   |
| AMD Ryzen 7            | 10       | 10.42%  |
| Intel Xeon             | 3        | 3.13%   |
| AMD Ryzen Threadripper | 3        | 3.13%   |
| Intel Core i9          | 2        | 2.08%   |
| Intel Pentium 4        | 1        | 1.04%   |
| Intel Celeron          | 1        | 1.04%   |
| AMD Sempron            | 1        | 1.04%   |
| AMD Ryzen 7 PRO        | 1        | 1.04%   |
| AMD Ryzen 3            | 1        | 1.04%   |
| AMD Phenom II X4       | 1        | 1.04%   |
| AMD FX                 | 1        | 1.04%   |
| AMD Athlon             | 1        | 1.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 24       | 25%     |
| 8      | 21       | 21.88%  |
| 4      | 19       | 19.79%  |
| 12     | 14       | 14.58%  |
| 16     | 11       | 11.46%  |
| 1      | 3        | 3.13%   |
| 2      | 2        | 2.08%   |
| 24     | 1        | 1.04%   |
| 10     | 1        | 1.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 96       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 77       | 80.21%  |
| 1      | 19       | 19.79%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 94       | 97.92%  |
| 32-bit         | 1        | 1.04%   |
| Unknown        | 1        | 1.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 15       | 15.46%  |
| 0x08701021 | 13       | 13.4%   |
| 0x0a201016 | 8        | 8.25%   |
| 0x90672    | 6        | 6.19%   |
| 0xa0671    | 5        | 5.15%   |
| 0x0800820d | 5        | 5.15%   |
| 0x906ed    | 4        | 4.12%   |
| 0x506e3    | 4        | 4.12%   |
| 0x08001138 | 3        | 3.09%   |
| 0xa0655    | 2        | 2.06%   |
| 0xa0653    | 2        | 2.06%   |
| 0x906ea    | 2        | 2.06%   |
| 0x906e9    | 2        | 2.06%   |
| 0x306e4    | 2        | 2.06%   |
| 0x306c3    | 2        | 2.06%   |
| 0x206a7    | 2        | 2.06%   |
| 0x0a201204 | 2        | 2.06%   |
| 0x08301039 | 2        | 2.06%   |
| 0xf43      | 1        | 1.03%   |
| 0x906ec    | 1        | 1.03%   |
| 0x40651    | 1        | 1.03%   |
| 0x306a9    | 1        | 1.03%   |
| 0x206c2    | 1        | 1.03%   |
| 0x0a50000c | 1        | 1.03%   |
| 0x0a50000b | 1        | 1.03%   |
| 0x0a201205 | 1        | 1.03%   |
| 0x0a201009 | 1        | 1.03%   |
| 0x08701013 | 1        | 1.03%   |
| 0x08600106 | 1        | 1.03%   |
| 0x08001137 | 1        | 1.03%   |
| 0x0700010f | 1        | 1.03%   |
| 0x0700010b | 1        | 1.03%   |
| 0x010000db | 1        | 1.03%   |
| 0x00000000 | 1        | 1.03%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 21       | 21.65%  |
| Zen 3            | 15       | 15.46%  |
| KabyLake         | 10       | 10.31%  |
| Zen+             | 7        | 7.22%   |
| Alderlake Hybrid | 6        | 6.19%   |
| Skylake          | 5        | 5.15%   |
| Icelake          | 5        | 5.15%   |
| Zen              | 4        | 4.12%   |
| Haswell          | 4        | 4.12%   |
| CometLake        | 4        | 4.12%   |
| SandyBridge      | 3        | 3.09%   |
| IvyBridge        | 3        | 3.09%   |
| Unknown          | 3        | 3.09%   |
| Jaguar           | 2        | 2.06%   |
| Westmere         | 1        | 1.03%   |
| Silvermont       | 1        | 1.03%   |
| Piledriver       | 1        | 1.03%   |
| NetBurst         | 1        | 1.03%   |
| K10              | 1        | 1.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 53       | 51.46%  |
| Nvidia | 37       | 35.92%  |
| Intel  | 13       | 12.62%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]             | 20       | 18.87%  |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                      | 5        | 4.72%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                           | 3        | 2.83%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                 | 3        | 2.83%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                  | 3        | 2.83%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                    | 3        | 2.83%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                               | 2        | 1.89%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                              | 2        | 1.89%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                              | 2        | 1.89%   |
| Nvidia GP104 [GeForce GTX 1080]                                     | 2        | 1.89%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                  | 2        | 1.89%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                            | 2        | 1.89%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                           | 2        | 1.89%   |
| Intel AlderLake-S GT1                                               | 2        | 1.89%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                            | 2        | 1.89%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                          | 2        | 1.89%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                | 2        | 1.89%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X] | 2        | 1.89%   |
| Nvidia TU116 [GeForce GTX 1650]                                     | 1        | 0.94%   |
| Nvidia TU106 [GeForce RTX 2070]                                     | 1        | 0.94%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                               | 1        | 0.94%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                               | 1        | 0.94%   |
| Nvidia GP108 [GeForce GT 1030]                                      | 1        | 0.94%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                 | 1        | 0.94%   |
| Nvidia GP104 [GeForce GTX 1070]                                     | 1        | 0.94%   |
| Nvidia GM206 [GeForce GTX 960]                                      | 1        | 0.94%   |
| Nvidia GM204 [GeForce GTX 970]                                      | 1        | 0.94%   |
| Nvidia GM107 [GeForce GTX 745]                                      | 1        | 0.94%   |
| Nvidia GK208B [GeForce GT 730]                                      | 1        | 0.94%   |
| Nvidia GK208B [GeForce GT 710]                                      | 1        | 0.94%   |
| Nvidia GK110B [GeForce GTX 780 Ti]                                  | 1        | 0.94%   |
| Nvidia GF119 [GeForce GT 610]                                       | 1        | 0.94%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                      | 1        | 0.94%   |
| Nvidia GA106 [Geforce RTX 3050]                                     | 1        | 0.94%   |
| Nvidia GA104 [GeForce RTX 3060]                                     | 1        | 0.94%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                  | 1        | 0.94%   |
| Nvidia GA102 [GeForce RTX 3090]                                     | 1        | 0.94%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller    | 1        | 0.94%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                           | 1        | 0.94%   |
| Intel HD Graphics P630                                              | 1        | 0.94%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 46       | 47.42%  |
| 1 x Nvidia     | 33       | 34.02%  |
| 1 x Intel      | 8        | 8.25%   |
| AMD + Nvidia   | 3        | 3.09%   |
| Other          | 2        | 2.06%   |
| 2 x AMD        | 2        | 2.06%   |
| Intel + AMD    | 2        | 2.06%   |
| Intel + Nvidia | 1        | 1.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 61       | 62.89%  |
| Proprietary | 30       | 30.93%  |
| Unknown     | 6        | 6.19%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 7.01-8.0   | 28       | 28%     |
| Unknown    | 27       | 27%     |
| 8.01-16.0  | 16       | 16%     |
| 3.01-4.0   | 9        | 9%      |
| 1.01-2.0   | 6        | 6%      |
| 0.51-1.0   | 6        | 6%      |
| 5.01-6.0   | 5        | 5%      |
| 0.01-0.5   | 2        | 2%      |
| 2.01-3.0   | 1        | 1%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 16       | 12.9%   |
| Goldstar                | 14       | 11.29%  |
| Dell                    | 10       | 8.06%   |
| AOC                     | 8        | 6.45%   |
| ViewSonic               | 7        | 5.65%   |
| Hewlett-Packard         | 6        | 4.84%   |
| BenQ                    | 5        | 4.03%   |
| Ancor Communications    | 5        | 4.03%   |
| Acer                    | 5        | 4.03%   |
| Philips                 | 4        | 3.23%   |
| Lenovo                  | 4        | 3.23%   |
| ASUSTek Computer        | 4        | 3.23%   |
| Iiyama                  | 3        | 2.42%   |
| Eizo                    | 3        | 2.42%   |
| Unknown                 | 3        | 2.42%   |
| Unknown                 | 2        | 1.61%   |
| Toshiba                 | 2        | 1.61%   |
| NEC Computers           | 2        | 1.61%   |
| MSI                     | 2        | 1.61%   |
| ___                     | 1        | 0.81%   |
| Valve                   | 1        | 0.81%   |
| Sony                    | 1        | 0.81%   |
| Sceptre Tech            | 1        | 0.81%   |
| PNP                     | 1        | 0.81%   |
| Onkyo                   | 1        | 0.81%   |
| MStar                   | 1        | 0.81%   |
| Microstep               | 1        | 0.81%   |
| Mi                      | 1        | 0.81%   |
| LYC                     | 1        | 0.81%   |
| LG Electronics          | 1        | 0.81%   |
| KTC                     | 1        | 0.81%   |
| HannStar                | 1        | 0.81%   |
| Gigabyte Technology     | 1        | 0.81%   |
| Gateway                 | 1        | 0.81%   |
| Chi Mei Optoelectronics | 1        | 0.81%   |
| Belinea                 | 1        | 0.81%   |
| AUS                     | 1        | 0.81%   |
| Apple                   | 1        | 0.81%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                   | 5        | 3.7%    |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch       | 3        | 2.22%   |
| Unknown                                                                 | 3        | 2.22%   |
| Philips PHL 242M8 PHLC214 1920x1080 527x296mm 23.8-inch                 | 2        | 1.48%   |
| Goldstar ULTRAWIDE GSM76E4 3440x1440 800x335mm 34.1-inch                | 2        | 1.48%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 600x340mm 27.2-inch                  | 2        | 1.48%   |
| Eizo CS2731 ENC3069 2560x1440 597x336mm 27.0-inch                       | 2        | 1.48%   |
| ___ TV ___9000 1360x768                                                 | 1        | 0.74%   |
| ViewSonic VX2458-mhd VSC0437 1920x1080 521x293mm 23.5-inch              | 1        | 0.74%   |
| ViewSonic VX2458 Series VSC36AF 1920x1080 521x293mm 23.5-inch           | 1        | 0.74%   |
| ViewSonic VX2363 Series VSC6B2F 1920x1080 509x286mm 23.0-inch           | 1        | 0.74%   |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 477x268mm 21.5-inch           | 1        | 0.74%   |
| ViewSonic VG1655 VSCD239 1920x1080 340x190mm 15.3-inch                  | 1        | 0.74%   |
| ViewSonic LCD Monitor VX3276-UHD 5760x2160                              | 1        | 0.74%   |
| ViewSonic LCD Monitor VSC2034 2560x1440 600x340mm 27.2-inch             | 1        | 0.74%   |
| Valve Index HMD VLV91A8                                                 | 1        | 0.74%   |
| Unknown LCDTV 9000 1360x768 1600x900mm 72.3-inch                        | 1        | 0.74%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch               | 1        | 0.74%   |
| Toshiba PA3552 TOS501C 1680x1050 433x270mm 20.1-inch                    | 1        | 0.74%   |
| Toshiba 32W_LCD_TV TSB3700 1920x1080 710x400mm 32.1-inch                | 1        | 0.74%   |
| Sony SDMU27M90*30 SNY075A 3840x2160 596x335mm 26.9-inch                 | 1        | 0.74%   |
| Sceptre Tech H32 SPT0CB8 1920x1080 575x323mm 26.0-inch                  | 1        | 0.74%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch       | 1        | 0.74%   |
| Samsung Electronics SyncMaster SAM05CC 1920x1080 530x300mm 24.0-inch    | 1        | 0.74%   |
| Samsung Electronics SyncMaster SAM0584 2048x1152 510x290mm 23.1-inch    | 1        | 0.74%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch    | 1        | 0.74%   |
| Samsung Electronics SyncMaster SAM0194 1280x1024 376x301mm 19.0-inch    | 1        | 0.74%   |
| Samsung Electronics SMS27A850 SAM083D 2560x1440 518x324mm 24.1-inch     | 1        | 0.74%   |
| Samsung Electronics S22B300 SAM08C8 1920x1080 477x268mm 21.5-inch       | 1        | 0.74%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch       | 1        | 0.74%   |
| Samsung Electronics LF24T450F SAM7096 1920x1080 527x296mm 23.8-inch     | 1        | 0.74%   |
| Samsung Electronics LCD Monitor SAM7002 3840x2160 1872x1053mm 84.6-inch | 1        | 0.74%   |
| Samsung Electronics LCD Monitor SAM0357 1920x1080                       | 1        | 0.74%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch      | 1        | 0.74%   |
| Samsung Electronics C49HG9x SAM0E5E 3840x1080 1196x336mm 48.9-inch      | 1        | 0.74%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 1        | 0.74%   |
| PNP LCD Monitor PNP0801 1280x960                                        | 1        | 0.74%   |
| Philips PHL 349X7 PHLC149 3440x1440 800x330mm 34.1-inch                 | 1        | 0.74%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                 | 1        | 0.74%   |
| Onkyo TX-NR535 ONK0E51 2560x1440 597x336mm 27.0-inch                    | 1        | 0.74%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 42       | 35.29%  |
| 2560x1440 (QHD)    | 27       | 22.69%  |
| 3840x2160 (4K)     | 14       | 11.76%  |
| 3440x1440          | 5        | 4.2%    |
| 1280x1024 (SXGA)   | 5        | 4.2%    |
| Unknown            | 5        | 4.2%    |
| 1920x1200 (WUXGA)  | 3        | 2.52%   |
| 3840x1080          | 2        | 1.68%   |
| 1680x1050 (WSXGA+) | 2        | 1.68%   |
| 1440x900 (WXGA+)   | 2        | 1.68%   |
| 1366x768 (WXGA)    | 2        | 1.68%   |
| 7680x2160          | 1        | 0.84%   |
| 5760x2160          | 1        | 0.84%   |
| 4000x2560          | 1        | 0.84%   |
| 2560x1080          | 1        | 0.84%   |
| 2288x1287          | 1        | 0.84%   |
| 2048x1152          | 1        | 0.84%   |
| 1600x900 (HD+)     | 1        | 0.84%   |
| 1360x768           | 1        | 0.84%   |
| 1280x960           | 1        | 0.84%   |
| 1024x768 (XGA)     | 1        | 0.84%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 35       | 28.46%  |
| 23      | 20       | 16.26%  |
| 24      | 12       | 9.76%   |
| 21      | 10       | 8.13%   |
| Unknown | 10       | 8.13%   |
| 34      | 6        | 4.88%   |
| 25      | 4        | 3.25%   |
| 19      | 4        | 3.25%   |
| 17      | 4        | 3.25%   |
| 84      | 2        | 1.63%   |
| 72      | 2        | 1.63%   |
| 49      | 2        | 1.63%   |
| 31      | 2        | 1.63%   |
| 15      | 2        | 1.63%   |
| 14      | 2        | 1.63%   |
| 142     | 1        | 0.81%   |
| 28      | 1        | 0.81%   |
| 26      | 1        | 0.81%   |
| 22      | 1        | 0.81%   |
| 20      | 1        | 0.81%   |
| 18      | 1        | 0.81%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 59       | 52.21%  |
| 401-500        | 14       | 12.39%  |
| Unknown        | 10       | 8.85%   |
| 601-700        | 7        | 6.19%   |
| 301-350        | 7        | 6.19%   |
| 701-800        | 6        | 5.31%   |
| 1501-2000      | 4        | 3.54%   |
| 351-400        | 2        | 1.77%   |
| 1001-1500      | 2        | 1.77%   |
| More than 2000 | 1        | 0.88%   |
| 201-300        | 1        | 0.88%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 71       | 70.3%   |
| 16/10   | 8        | 7.92%   |
| Unknown | 7        | 6.93%   |
| 21/9    | 6        | 5.94%   |
| 5/4     | 5        | 4.95%   |
| 4/3     | 2        | 1.98%   |
| 32/9    | 1        | 0.99%   |
| 1.00    | 1        | 0.99%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 301-350        | 35       | 29.66%  |
| 201-250        | 32       | 27.12%  |
| Unknown        | 10       | 8.47%   |
| 351-500        | 9        | 7.63%   |
| 251-300        | 8        | 6.78%   |
| 151-200        | 8        | 6.78%   |
| More than 1000 | 6        | 5.08%   |
| 141-150        | 5        | 4.24%   |
| 101-110        | 2        | 1.69%   |
| 81-90          | 1        | 0.85%   |
| 501-1000       | 1        | 0.85%   |
| 91-100         | 1        | 0.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 46       | 41.44%  |
| 101-120 | 37       | 33.33%  |
| Unknown | 10       | 9.01%   |
| 121-160 | 9        | 8.11%   |
| 161-240 | 6        | 5.41%   |
| 1-50    | 3        | 2.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 51       | 52.04%  |
| 2     | 31       | 31.63%  |
| 0     | 8        | 8.16%   |
| 3     | 5        | 5.1%    |
| 4     | 3        | 3.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 59       | 44.36%  |
| Realtek Semiconductor    | 47       | 35.34%  |
| Aquantia                 | 7        | 5.26%   |
| Qualcomm Atheros         | 5        | 3.76%   |
| Microsoft                | 2        | 1.5%    |
| MediaTek                 | 2        | 1.5%    |
| Marvell Technology Group | 2        | 1.5%    |
| Broadcom                 | 2        | 1.5%    |
| Raspberry Pi             | 1        | 0.75%   |
| Ralink Technology        | 1        | 0.75%   |
| NetGear                  | 1        | 0.75%   |
| Dresden Elektronik       | 1        | 0.75%   |
| DisplayLink              | 1        | 0.75%   |
| Broadcom Limited         | 1        | 0.75%   |
| Apple                    | 1        | 0.75%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 32       | 19.28%  |
| Intel Wi-Fi 6 AX200                                                 | 19       | 11.45%  |
| Intel I211 Gigabit Network Connection                               | 15       | 9.04%   |
| Realtek RTL8125 2.5GbE Controller                                   | 14       | 8.43%   |
| Intel Ethernet Controller I225-V                                    | 11       | 6.63%   |
| Intel Ethernet Connection (7) I219-V                                | 7        | 4.22%   |
| Intel Ethernet Connection (2) I219-V                                | 5        | 3.01%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 4        | 2.41%   |
| Intel Wireless-AC 9260                                              | 3        | 1.81%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 3        | 1.81%   |
| Intel Cannon Lake PCH CNVi WiFi                                     | 3        | 1.81%   |
| Intel Alder Lake-S PCH CNVi WiFi                                    | 3        | 1.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 2        | 1.2%    |
| Microsoft XBOX ACC                                                  | 2        | 1.2%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 2        | 1.2%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 2        | 1.2%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                | 2        | 1.2%    |
| Intel 82574L Gigabit Network Connection                             | 2        | 1.2%    |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 1.2%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1        | 0.6%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                     | 1        | 0.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 1        | 0.6%    |
| Raspberry Pi Pico                                                   | 1        | 0.6%    |
| Ralink RT2870/RT3070 Wireless Adapter                               | 1        | 0.6%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 1        | 0.6%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                    | 1        | 0.6%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                    | 1        | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 1        | 0.6%    |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter          | 1        | 0.6%    |
| NetGear A6210                                                       | 1        | 0.6%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller             | 1        | 0.6%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller             | 1        | 0.6%    |
| Intel Wireless 7265                                                 | 1        | 0.6%    |
| Intel Tiger Lake PCH CNVi WiFi                                      | 1        | 0.6%    |
| Intel I210 Gigabit Network Connection                               | 1        | 0.6%    |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                    | 1        | 0.6%    |
| Intel Ethernet Connection I218-V                                    | 1        | 0.6%    |
| Intel Ethernet Connection I217-V                                    | 1        | 0.6%    |
| Intel Ethernet Connection (2) I219-LM                               | 1        | 0.6%    |
| Intel Ethernet Connection (14) I219-V                               | 1        | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 36       | 70.59%  |
| Qualcomm Atheros      | 4        | 7.84%   |
| Realtek Semiconductor | 2        | 3.92%   |
| Microsoft             | 2        | 3.92%   |
| MediaTek              | 2        | 3.92%   |
| Broadcom              | 2        | 3.92%   |
| Ralink Technology     | 1        | 1.96%   |
| NetGear               | 1        | 1.96%   |
| Broadcom Limited      | 1        | 1.96%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                 | 19       | 36.54%  |
| Intel Wireless-AC 9260                                              | 3        | 5.77%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 3        | 5.77%   |
| Intel Cannon Lake PCH CNVi WiFi                                     | 3        | 5.77%   |
| Intel Alder Lake-S PCH CNVi WiFi                                    | 3        | 5.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 2        | 3.85%   |
| Microsoft XBOX ACC                                                  | 2        | 3.85%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 2        | 3.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 2        | 3.85%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1        | 1.92%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                     | 1        | 1.92%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 1        | 1.92%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                    | 1        | 1.92%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                    | 1        | 1.92%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter          | 1        | 1.92%   |
| NetGear A6210                                                       | 1        | 1.92%   |
| Intel Wireless 7265                                                 | 1        | 1.92%   |
| Intel Tiger Lake PCH CNVi WiFi                                      | 1        | 1.92%   |
| Intel Comet Lake PCH CNVi WiFi                                      | 1        | 1.92%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter          | 1        | 1.92%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                  | 1        | 1.92%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1        | 1.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 47       | 43.93%  |
| Intel                    | 47       | 43.93%  |
| Aquantia                 | 7        | 6.54%   |
| Qualcomm Atheros         | 2        | 1.87%   |
| Marvell Technology Group | 2        | 1.87%   |
| DisplayLink              | 1        | 0.93%   |
| Apple                    | 1        | 0.93%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 32       | 28.57%  |
| Intel I211 Gigabit Network Connection                               | 15       | 13.39%  |
| Realtek RTL8125 2.5GbE Controller                                   | 14       | 12.5%   |
| Intel Ethernet Controller I225-V                                    | 11       | 9.82%   |
| Intel Ethernet Connection (7) I219-V                                | 7        | 6.25%   |
| Intel Ethernet Connection (2) I219-V                                | 5        | 4.46%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 4        | 3.57%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                | 2        | 1.79%   |
| Intel 82574L Gigabit Network Connection                             | 2        | 1.79%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 1.79%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 1        | 0.89%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 1        | 0.89%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 1        | 0.89%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller             | 1        | 0.89%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller             | 1        | 0.89%   |
| Intel I210 Gigabit Network Connection                               | 1        | 0.89%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                    | 1        | 0.89%   |
| Intel Ethernet Connection I218-V                                    | 1        | 0.89%   |
| Intel Ethernet Connection I217-V                                    | 1        | 0.89%   |
| Intel Ethernet Connection (2) I219-LM                               | 1        | 0.89%   |
| Intel Ethernet Connection (14) I219-V                               | 1        | 0.89%   |
| Intel Ethernet Connection (11) I219-V                               | 1        | 0.89%   |
| Intel Ethernet Connection (11) I219-LM                              | 1        | 0.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 1        | 0.89%   |
| Intel 82575GB Gigabit Network Connection                            | 1        | 0.89%   |
| DisplayLink Dell D3100 Docking Station                              | 1        | 0.89%   |
| Aquantia Ethernet controller                                        | 1        | 0.89%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                     | 1        | 0.89%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 94       | 65.28%  |
| WiFi     | 48       | 33.33%  |
| Modem    | 2        | 1.39%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 81       | 82.65%  |
| WiFi     | 17       | 17.35%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 42       | 43.3%   |
| 2     | 40       | 41.24%  |
| 3     | 10       | 10.31%  |
| 4     | 2        | 2.06%   |
| 0     | 2        | 2.06%   |
| 5     | 1        | 1.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 66       | 68.75%  |
| Yes  | 30       | 31.25%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 37       | 69.81%  |
| Cambridge Silicon Radio         | 7        | 13.21%  |
| Realtek Semiconductor           | 2        | 3.77%   |
| MediaTek                        | 2        | 3.77%   |
| Qualcomm Atheros Communications | 1        | 1.89%   |
| Foxconn / Hon Hai               | 1        | 1.89%   |
| Broadcom                        | 1        | 1.89%   |
| ASUSTek Computer                | 1        | 1.89%   |
| Apple                           | 1        | 1.89%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 20       | 37.74%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7        | 13.21%  |
| Intel AX210 Bluetooth                               | 4        | 7.55%   |
| Intel AX201 Bluetooth                               | 4        | 7.55%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3        | 5.66%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3        | 5.66%   |
| Realtek Bluetooth Radio                             | 2        | 3.77%   |
| MediaTek Wireless_Device                            | 2        | 3.77%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1        | 1.89%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 1.89%   |
| Intel Bluetooth wireless interface                  | 1        | 1.89%   |
| Intel Bluetooth Device                              | 1        | 1.89%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1        | 1.89%   |
| Broadcom BCM20702A0                                 | 1        | 1.89%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 1.89%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 1        | 1.89%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 67       | 31.16%  |
| Intel                                | 40       | 18.6%   |
| Nvidia                               | 37       | 17.21%  |
| C-Media Electronics                  | 10       | 4.65%   |
| ASUSTek Computer                     | 5        | 2.33%   |
| Thesycon Systemsoftware & Consulting | 4        | 1.86%   |
| Logitech                             | 4        | 1.86%   |
| SteelSeries ApS                      | 3        | 1.4%    |
| Realtek Semiconductor                | 3        | 1.4%    |
| Creative Technology                  | 3        | 1.4%    |
| Creative Labs                        | 3        | 1.4%    |
| Yamaha                               | 2        | 0.93%   |
| Sony                                 | 2        | 0.93%   |
| RODE Microphones                     | 2        | 0.93%   |
| Razer USA                            | 2        | 0.93%   |
| Focusrite-Novation                   | 2        | 0.93%   |
| Corsair                              | 2        | 0.93%   |
| Blue Microphones                     | 2        | 0.93%   |
| AudioQuest                           | 2        | 0.93%   |
| Audio-Technica                       | 2        | 0.93%   |
| Valve Software                       | 1        | 0.47%   |
| Unknown                              | 1        | 0.47%   |
| TEAC                                 | 1        | 0.47%   |
| Sennheiser Communications            | 1        | 0.47%   |
| SAVITECH                             | 1        | 0.47%   |
| Samson Technologies                  | 1        | 0.47%   |
| Nektar                               | 1        | 0.47%   |
| MAG Technology                       | 1        | 0.47%   |
| JOUNIVO                              | 1        | 0.47%   |
| JMTek                                | 1        | 0.47%   |
| Huawei Technologies                  | 1        | 0.47%   |
| GN Netcom                            | 1        | 0.47%   |
| Generalplus Technology               | 1        | 0.47%   |
| FiiO Electronics Technology          | 1        | 0.47%   |
| FIFINE Microphones                   | 1        | 0.47%   |
| BEHRINGER International              | 1        | 0.47%   |
| Astro Gaming                         | 1        | 0.47%   |
| Actions Semiconductor                | 1        | 0.47%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 29       | 11.65%  |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 21       | 8.43%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 10       | 4.02%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10       | 4.02%   |
| Intel Cannon Lake PCH cAVS                                                 | 7        | 2.81%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7        | 2.81%   |
| Intel Alder Lake-S HD Audio Controller                                     | 5        | 2.01%   |
| Thesycon Systemsoftware & Consulting D50s                                  | 4        | 1.61%   |
| Nvidia TU104 HD Audio Controller                                           | 4        | 1.61%   |
| Nvidia GP106 High Definition Audio Controller                              | 4        | 1.61%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4        | 1.61%   |
| ASUSTek Computer USB Audio                                                 | 4        | 1.61%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4        | 1.61%   |
| Nvidia TU106 High Definition Audio Controller                              | 3        | 1.2%    |
| Nvidia TU102 High Definition Audio Controller                              | 3        | 1.2%    |
| Nvidia GP104 High Definition Audio Controller                              | 3        | 1.2%    |
| Nvidia GP102 HDMI Audio Controller                                         | 3        | 1.2%    |
| Nvidia GA102 High Definition Audio Controller                              | 3        | 1.2%    |
| Intel Comet Lake PCH cAVS                                                  | 3        | 1.2%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3        | 1.2%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 3        | 1.2%    |
| AMD Family 17h/19h HD Audio Controller                                     | 3        | 1.2%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3        | 1.2%    |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 2        | 0.8%    |
| Realtek Semiconductor TX-384Khz Hifi Type-C Audio                          | 2        | 0.8%    |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 0.8%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 0.8%    |
| Nvidia GA106 High Definition Audio Controller                              | 2        | 0.8%    |
| Nvidia GA104 High Definition Audio Controller                              | 2        | 0.8%    |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2        | 0.8%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 0.8%    |
| Focusrite-Novation Scarlett 2i2 Camera                                     | 2        | 0.8%    |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 2        | 0.8%    |
| C-Media Electronics CM108 Audio Controller                                 | 2        | 0.8%    |
| C-Media Electronics Blue Snowball                                          | 2        | 0.8%    |
| Blue Microphones Yeti Stereo Microphone                                    | 2        | 0.8%    |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 2        | 0.8%    |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                         | 2        | 0.8%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 0.8%    |
| AMD Navi 10 HDMI Audio                                                     | 2        | 0.8%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| G.Skill             | 21       | 20.79%  |
| Corsair             | 18       | 17.82%  |
| Kingston            | 16       | 15.84%  |
| Crucial             | 16       | 15.84%  |
| Unknown             | 6        | 5.94%   |
| Samsung Electronics | 6        | 5.94%   |
| Team                | 3        | 2.97%   |
| Patriot             | 3        | 2.97%   |
| Unknown             | 3        | 2.97%   |
| SK hynix            | 2        | 1.98%   |
| Micron Technology   | 2        | 1.98%   |
| A-DATA Technology   | 2        | 1.98%   |
| Patriot Memory      | 1        | 0.99%   |
| Nanya Technology    | 1        | 0.99%   |
| GOODRAM             | 1        | 0.99%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3200MT/s    | 3        | 2.75%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s     | 3        | 2.75%   |
| Unknown                                                   | 3        | 2.75%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s        | 2        | 1.83%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s      | 2        | 1.83%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s       | 2        | 1.83%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s     | 2        | 1.83%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s     | 2        | 1.83%   |
| Crucial RAM BL16G36C16U4RL.M8FB1 16GB DIMM DDR4 4000MT/s  | 2        | 1.83%   |
| Crucial RAM BL16G32C16U4B.M16FE1 16GB DIMM DDR4 3200MT/s  | 2        | 1.83%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s    | 2        | 1.83%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                 | 1        | 0.92%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                      | 1        | 0.92%   |
| Unknown RAM Module 512MB DIMM SDRAM                       | 1        | 0.92%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                  | 1        | 0.92%   |
| Unknown RAM Module 1GB DIMM SDRAM                         | 1        | 0.92%   |
| Unknown RAM Module 16GB DIMM DDR4 2133MT/s                | 1        | 0.92%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s     | 1        | 0.92%   |
| Team RAM TEAMGROUP-UD4-3600 32GB DIMM DDR4 3600MT/s       | 1        | 0.92%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s        | 1        | 0.92%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s        | 1        | 0.92%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s      | 1        | 0.92%   |
| SK hynix RAM HMT425U6AFR6C-PB 2GB DIMM DDR3 1600MT/s      | 1        | 0.92%   |
| SK hynix RAM HMA84GR7CJR4N-XN 32GB DIMM DDR4 3200MT/s     | 1        | 0.92%   |
| Samsung RAM M393B5170FH0 4GB DIMM DDR3 1333MT/s           | 1        | 0.92%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s      | 1        | 0.92%   |
| Samsung RAM M391A2K43BB1-CRC 16GB DIMM DDR4 2866MT/s      | 1        | 0.92%   |
| Samsung RAM M378B1G73DB0-CK0 8192MB DIMM DDR3 2133MT/s    | 1        | 0.92%   |
| Samsung RAM M378A2G43MX3-CTD 16GB DIMM DDR4 3466MT/s      | 1        | 0.92%   |
| Samsung RAM M378A1G44AB0-CWE 8GB DIMM DDR4 3200MT/s       | 1        | 0.92%   |
| Patriot RAM 1600 CL9 Series 8GB DIMM DDR3 1600MT/s        | 1        | 0.92%   |
| Patriot Memory RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s | 1        | 0.92%   |
| Nanya RAM M2F4G64CB88B7N-DI 4GB DIMM DDR3 1600MT/s        | 1        | 0.92%   |
| Micron RAM 8ATF1G64AZ-3G2J1 8GB DIMM DDR4 3200MT/s        | 1        | 0.92%   |
| Micron RAM 16JTF51264AZ-1G4D 4GB DIMM DDR3 1333MT/s       | 1        | 0.92%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s    | 1        | 0.92%   |
| Kingston RAM KHX2666C16/16G 16384MB DIMM DDR4 3200MT/s    | 1        | 0.92%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s       | 1        | 0.92%   |
| Kingston RAM KHX2133C14/8G 8192MB DIMM DDR4 2400MT/s      | 1        | 0.92%   |
| Kingston RAM HX426C16FB/8 8GB DIMM DDR4 2667MT/s          | 1        | 0.92%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 72       | 80.9%   |
| DDR3    | 13       | 14.61%  |
| SDRAM   | 1        | 1.12%   |
| DDR5    | 1        | 1.12%   |
| DDR2    | 1        | 1.12%   |
| Unknown | 1        | 1.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 89       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 37       | 37%     |
| 16384 | 33       | 33%     |
| 32768 | 16       | 16%     |
| 4096  | 9        | 9%      |
| 2048  | 3        | 3%      |
| 1024  | 1        | 1%      |
| 512   | 1        | 1%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 28       | 28%     |
| 3600    | 13       | 13%     |
| 2133    | 7        | 7%      |
| 1600    | 6        | 6%      |
| 3733    | 5        | 5%      |
| 3400    | 5        | 5%      |
| 2667    | 5        | 5%      |
| 1333    | 5        | 5%      |
| 3466    | 3        | 3%      |
| 3000    | 3        | 3%      |
| 4000    | 2        | 2%      |
| 3866    | 2        | 2%      |
| 3666    | 2        | 2%      |
| 2400    | 2        | 2%      |
| 4800    | 1        | 1%      |
| 3334    | 1        | 1%      |
| 2933    | 1        | 1%      |
| 2866    | 1        | 1%      |
| 2733    | 1        | 1%      |
| 2666    | 1        | 1%      |
| 2197    | 1        | 1%      |
| 1867    | 1        | 1%      |
| 1400    | 1        | 1%      |
| 800     | 1        | 1%      |
| 667     | 1        | 1%      |
| Unknown | 1        | 1%      |

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
| Logitech                      | 13       | 48.15%  |
| Sunplus Innovation Technology | 3        | 11.11%  |
| YGTek                         | 1        | 3.7%    |
| Xiaomi                        | 1        | 3.7%    |
| Valve Software                | 1        | 3.7%    |
| Samsung Electronics           | 1        | 3.7%    |
| Ruision                       | 1        | 3.7%    |
| Microdia                      | 1        | 3.7%    |
| MacroSilicon                  | 1        | 3.7%    |
| Generalplus Technology        | 1        | 3.7%    |
| Cubeternet                    | 1        | 3.7%    |
| Creative Technology           | 1        | 3.7%    |
| Chicony Electronics           | 1        | 3.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                                         | 3        | 11.11%  |
| Logitech BRIO Ultra HD Webcam                                       | 2        | 7.41%   |
| YGTek Webcam                                                        | 1        | 3.7%    |
| Xiaomi POCO X3 Pro                                                  | 1        | 3.7%    |
| Valve Software 3D Camera                                            | 1        | 3.7%    |
| Sunplus PAPALOOK_229AF                                              | 1        | 3.7%    |
| Sunplus NexiGo N940 2K Webcam                                       | 1        | 3.7%    |
| Sunplus Canyon CNS-CWC5 Webcam                                      | 1        | 3.7%    |
| Samsung Galaxy A5 (MTP)                                             | 1        | 3.7%    |
| Ruision UVC Camera                                                  | 1        | 3.7%    |
| Microdia CameraA                                                    | 1        | 3.7%    |
| MacroSilicon USB Video                                              | 1        | 3.7%    |
| Logitech Webcam C920-C                                              | 1        | 3.7%    |
| Logitech Webcam C270                                                | 1        | 3.7%    |
| Logitech Webcam C110                                                | 1        | 3.7%    |
| Logitech StreamCam                                                  | 1        | 3.7%    |
| Logitech QuickCam Orbit/Sphere AF                                   | 1        | 3.7%    |
| Logitech HD Webcam C615                                             | 1        | 3.7%    |
| Logitech HD Webcam C510                                             | 1        | 3.7%    |
| Logitech BRIO 4K Stream Edition                                     | 1        | 3.7%    |
| Generalplus GENERAL WEBCAM                                          | 1        | 3.7%    |
| Cubeternet EtronTech CMOS based eSP570 WebCam [Onyx Titanium TC101] | 1        | 3.7%    |
| Creative Live! Cam Sync 1080p                                       | 1        | 3.7%    |
| Chicony Gateway Webcam                                              | 1        | 3.7%    |

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


| Vendor     | Desktops | Percent |
|------------|----------|---------|
| Yubico.com | 1        | 50%     |
| Clay Logic | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Yubico.com Yubikey 4/5 U2F+CCID | 1        | 50%     |
| Clay Logic Nitrokey Pro         | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 67       | 67%     |
| 1     | 19       | 19%     |
| 2     | 8        | 8%      |
| 3     | 4        | 4%      |
| 4     | 2        | 2%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 12       | 26.09%  |
| Net/wireless             | 9        | 19.57%  |
| Sound                    | 6        | 13.04%  |
| Graphics card            | 5        | 10.87%  |
| Bluetooth                | 4        | 8.7%    |
| Multimedia controller    | 2        | 4.35%   |
| Modem                    | 2        | 4.35%   |
| Storage/raid             | 1        | 2.17%   |
| Storage/ide              | 1        | 2.17%   |
| Storage/ata              | 1        | 2.17%   |
| Network                  | 1        | 2.17%   |
| Fingerprint reader       | 1        | 2.17%   |
| Camera                   | 1        | 2.17%   |

