Xero - Tested Hardware & Statistics (Desktops)
----------------------------------------------

A project to collect tested hardware configurations for Xero.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 189

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | P8Z77-V PRO                 | [4f8558438f](https://linux-hardware.org/?probe=4f8558438f) | Dec 23, 2023 |
| Dell          | 06X1TJ A00                  | [eac468f369](https://linux-hardware.org/?probe=eac468f369) | Dec 20, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [cd04b1b3df](https://linux-hardware.org/?probe=cd04b1b3df) | Dec 17, 2023 |
| ASRock        | A620M Pro RS WiFi           | [069de62879](https://linux-hardware.org/?probe=069de62879) | Dec 13, 2023 |
| Huanan        | X99-F8                      | [8c534cb0a4](https://linux-hardware.org/?probe=8c534cb0a4) | Dec 09, 2023 |
| Huanan        | X99-F8                      | [6d1bdd1b81](https://linux-hardware.org/?probe=6d1bdd1b81) | Dec 09, 2023 |
| Dell          | 00V62H A01                  | [3a19753377](https://linux-hardware.org/?probe=3a19753377) | Dec 05, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [4d788fb96c](https://linux-hardware.org/?probe=4d788fb96c) | Dec 04, 2023 |
| Gigabyte      | B450M S2H                   | [5dcf20cb88](https://linux-hardware.org/?probe=5dcf20cb88) | Dec 04, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [c6454cb058](https://linux-hardware.org/?probe=c6454cb058) | Dec 04, 2023 |
| Gigabyte      | B450M S2H                   | [2f07094763](https://linux-hardware.org/?probe=2f07094763) | Dec 04, 2023 |
| MSI           | Z97-GD65 GAMING             | [86230be0a7](https://linux-hardware.org/?probe=86230be0a7) | Nov 27, 2023 |
| ECS           | H81H3-M3                    | [e3473e64c5](https://linux-hardware.org/?probe=e3473e64c5) | Nov 27, 2023 |
| ECS           | H81H3-M3                    | [c9b79740d2](https://linux-hardware.org/?probe=c9b79740d2) | Nov 27, 2023 |
| Gigabyte      | H81M-H                      | [bfb937c0c0](https://linux-hardware.org/?probe=bfb937c0c0) | Nov 26, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | [a18b2f2c3e](https://linux-hardware.org/?probe=a18b2f2c3e) | Nov 25, 2023 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [b9b8e57c7c](https://linux-hardware.org/?probe=b9b8e57c7c) | Nov 25, 2023 |
| ASUSTek       | PRIME A520M-K               | [83c2b87d3c](https://linux-hardware.org/?probe=83c2b87d3c) | Nov 24, 2023 |
| Gigabyte      | B450M DS3H-CF               | [56c19073cb](https://linux-hardware.org/?probe=56c19073cb) | Nov 20, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [49139037ec](https://linux-hardware.org/?probe=49139037ec) | Nov 20, 2023 |
| Dell          | 0HY9JP A02                  | [c97b664653](https://linux-hardware.org/?probe=c97b664653) | Nov 18, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [6525548dab](https://linux-hardware.org/?probe=6525548dab) | Nov 12, 2023 |
| Intel         | X99                         | [5c6225ea2d](https://linux-hardware.org/?probe=5c6225ea2d) | Nov 11, 2023 |
| ASRock        | B250M-HDV                   | [c8521456ad](https://linux-hardware.org/?probe=c8521456ad) | Nov 04, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [1da3521ff2](https://linux-hardware.org/?probe=1da3521ff2) | Nov 04, 2023 |
| ASUSTek       | PRIME H510M-D               | [d6749e3f8b](https://linux-hardware.org/?probe=d6749e3f8b) | Nov 01, 2023 |
| ASUSTek       | H170M-PLUS                  | [90b5515582](https://linux-hardware.org/?probe=90b5515582) | Oct 31, 2023 |
| Dell          | 0R849J A01                  | [3891d2fd80](https://linux-hardware.org/?probe=3891d2fd80) | Oct 31, 2023 |
| Huanan        | X99-F8                      | [0bcf4adaf6](https://linux-hardware.org/?probe=0bcf4adaf6) | Oct 31, 2023 |
| Gigabyte      | B760 AORUS ELITE AX DDR4    | [53ff42384c](https://linux-hardware.org/?probe=53ff42384c) | Oct 29, 2023 |
| Huanan        | X99-F8                      | [69329218c9](https://linux-hardware.org/?probe=69329218c9) | Oct 25, 2023 |
| ASUSTek       | H61M-K                      | [150a11b476](https://linux-hardware.org/?probe=150a11b476) | Oct 21, 2023 |
| MSI           | B85M-E45                    | [8c3f253c5e](https://linux-hardware.org/?probe=8c3f253c5e) | Oct 19, 2023 |
| Dell          | 0T568R A00                  | [ef9aa5b89c](https://linux-hardware.org/?probe=ef9aa5b89c) | Oct 14, 2023 |
| ASUSTek       | P5QD TURBO                  | [63c82d8692](https://linux-hardware.org/?probe=63c82d8692) | Oct 13, 2023 |
| Lenovo        | MAHOBAY                     | [9ced54f630](https://linux-hardware.org/?probe=9ced54f630) | Oct 01, 2023 |
| Dell          | 0MN1TX A02                  | [3f0eee5de0](https://linux-hardware.org/?probe=3f0eee5de0) | Oct 01, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [e26d1b1ae4](https://linux-hardware.org/?probe=e26d1b1ae4) | Sep 30, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [074ab86d60](https://linux-hardware.org/?probe=074ab86d60) | Sep 29, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [fee2fdb49a](https://linux-hardware.org/?probe=fee2fdb49a) | Sep 25, 2023 |
| Huanan        | X99-TF V1.1                 | [694b4ab1f2](https://linux-hardware.org/?probe=694b4ab1f2) | Sep 24, 2023 |
| HP            | 2B2C                        | [79ccf62c55](https://linux-hardware.org/?probe=79ccf62c55) | Sep 23, 2023 |
| ASRock        | A300M-STX                   | [2fc60c03c3](https://linux-hardware.org/?probe=2fc60c03c3) | Sep 22, 2023 |
| MSI           | PRO H610M-B DDR4            | [ee0a21be07](https://linux-hardware.org/?probe=ee0a21be07) | Sep 21, 2023 |
| Dell          | 0WR7PY A02                  | [5e059c90e1](https://linux-hardware.org/?probe=5e059c90e1) | Sep 21, 2023 |
| ECS           | H61H2-M2                    | [fe16b7a5a1](https://linux-hardware.org/?probe=fe16b7a5a1) | Sep 19, 2023 |
| Dell          | 0T568R A00                  | [675cec7d95](https://linux-hardware.org/?probe=675cec7d95) | Sep 17, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [eb2fcff0f3](https://linux-hardware.org/?probe=eb2fcff0f3) | Sep 16, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [c95eedf70e](https://linux-hardware.org/?probe=c95eedf70e) | Sep 16, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [966d90cbc8](https://linux-hardware.org/?probe=966d90cbc8) | Sep 14, 2023 |
| Huanan        | X99-TF V1.1                 | [a5acc6026f](https://linux-hardware.org/?probe=a5acc6026f) | Sep 14, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [a68551130a](https://linux-hardware.org/?probe=a68551130a) | Sep 13, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [3edc89267d](https://linux-hardware.org/?probe=3edc89267d) | Sep 13, 2023 |
| ASUSTek       | M5A99X EVO                  | [82125c27c9](https://linux-hardware.org/?probe=82125c27c9) | Sep 12, 2023 |
| Gigabyte      | Z790 UD                     | [bcfc38f6da](https://linux-hardware.org/?probe=bcfc38f6da) | Sep 11, 2023 |
| ASUSTek       | M5A99X EVO                  | [3bc292a4ce](https://linux-hardware.org/?probe=3bc292a4ce) | Sep 10, 2023 |
| Pegatron      | 2AB6                        | [5b2fda7ad6](https://linux-hardware.org/?probe=5b2fda7ad6) | Sep 09, 2023 |
| HP            | 2B18                        | [9c8753a19e](https://linux-hardware.org/?probe=9c8753a19e) | Sep 09, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [bb02ef5cc7](https://linux-hardware.org/?probe=bb02ef5cc7) | Sep 08, 2023 |
| HP            | 2B3C                        | [471f0f283b](https://linux-hardware.org/?probe=471f0f283b) | Sep 06, 2023 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | [b1329d0cc1](https://linux-hardware.org/?probe=b1329d0cc1) | Sep 05, 2023 |
| ASUSTek       | PRIME A320M-K               | [7263435dde](https://linux-hardware.org/?probe=7263435dde) | Sep 05, 2023 |
| ASUSTek       | PRIME X299-A II             | [80a93a9457](https://linux-hardware.org/?probe=80a93a9457) | Sep 02, 2023 |
| HP            | 18E9                        | [fd1f6decb2](https://linux-hardware.org/?probe=fd1f6decb2) | Sep 01, 2023 |
| MSI           | Z97 GAMING 7                | [ea78ba2d46](https://linux-hardware.org/?probe=ea78ba2d46) | Aug 29, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [5b896ea45c](https://linux-hardware.org/?probe=5b896ea45c) | Aug 29, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [6b6ec006aa](https://linux-hardware.org/?probe=6b6ec006aa) | Aug 28, 2023 |
| Gigabyte      | H110M-H-CF                  | [cc89933ff1](https://linux-hardware.org/?probe=cc89933ff1) | Aug 28, 2023 |
| ASUSTek       | PRIME H510M-R               | [c6614846b5](https://linux-hardware.org/?probe=c6614846b5) | Aug 28, 2023 |
| HP            | 2B18                        | [891ce74167](https://linux-hardware.org/?probe=891ce74167) | Aug 27, 2023 |
| Dell          | 06X1TJ A00                  | [450512bee1](https://linux-hardware.org/?probe=450512bee1) | Aug 27, 2023 |
| MSI           | A520M-A PRO                 | [7423f83594](https://linux-hardware.org/?probe=7423f83594) | Aug 27, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [dd4626de1b](https://linux-hardware.org/?probe=dd4626de1b) | Aug 27, 2023 |
| Gigabyte      | Z370M DS3H-CF               | [6ae200367f](https://linux-hardware.org/?probe=6ae200367f) | Aug 27, 2023 |
| Gigabyte      | Z490 GAMING X               | [ee07c69165](https://linux-hardware.org/?probe=ee07c69165) | Aug 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [17a7fc84be](https://linux-hardware.org/?probe=17a7fc84be) | Aug 26, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [d4cf1916d2](https://linux-hardware.org/?probe=d4cf1916d2) | Aug 26, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [16790cbb5f](https://linux-hardware.org/?probe=16790cbb5f) | Aug 26, 2023 |
| BESSTAR Te... | UM700                       | [bca12d1c12](https://linux-hardware.org/?probe=bca12d1c12) | Aug 24, 2023 |
| Gigabyte      | Z790 AORUS MASTER           | [202017a190](https://linux-hardware.org/?probe=202017a190) | Aug 23, 2023 |
| Win Elemen... | M9                          | [f161447dfc](https://linux-hardware.org/?probe=f161447dfc) | Aug 22, 2023 |
| Acer          | Predator PO3-630            | [b7c9c3e0c4](https://linux-hardware.org/?probe=b7c9c3e0c4) | Aug 22, 2023 |
| ASRock        | A320M-DVS R4.0              | [5a9badb376](https://linux-hardware.org/?probe=5a9badb376) | Aug 22, 2023 |
| MSI           | MEG Z390 ACE                | [5ab219fbd1](https://linux-hardware.org/?probe=5ab219fbd1) | Aug 20, 2023 |
| MSI           | H270M BAZOOKA               | [f51f1ce129](https://linux-hardware.org/?probe=f51f1ce129) | Aug 19, 2023 |
| MSI           | Z87 MPOWER MAX              | [6bda9908df](https://linux-hardware.org/?probe=6bda9908df) | Aug 16, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [11dafc79e8](https://linux-hardware.org/?probe=11dafc79e8) | Aug 15, 2023 |
| MSI           | 760GM-P33                   | [878209b83a](https://linux-hardware.org/?probe=878209b83a) | Aug 13, 2023 |
| ASUSTek       | PRIME H510M-R               | [38ab435feb](https://linux-hardware.org/?probe=38ab435feb) | Aug 08, 2023 |
| MSI           | B350 GAMING PLUS            | [951597859a](https://linux-hardware.org/?probe=951597859a) | Aug 08, 2023 |
| ASRock        | X300M-STX                   | [e642e8e489](https://linux-hardware.org/?probe=e642e8e489) | Aug 08, 2023 |
| ECS           | H61H2-CM                    | [e2b9ff65d7](https://linux-hardware.org/?probe=e2b9ff65d7) | Aug 06, 2023 |
| ASRock        | Z77 Professional            | [2f0bc369b4](https://linux-hardware.org/?probe=2f0bc369b4) | Aug 03, 2023 |
| Gigabyte      | Z490 GAMING X               | [f710ad8b96](https://linux-hardware.org/?probe=f710ad8b96) | Jul 31, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [2c6149347b](https://linux-hardware.org/?probe=2c6149347b) | Jul 30, 2023 |
| MSI           | H510M-A PRO                 | [20d5d0a3ad](https://linux-hardware.org/?probe=20d5d0a3ad) | Jul 30, 2023 |
| Intel         | B75                         | [492fa4fc25](https://linux-hardware.org/?probe=492fa4fc25) | Jul 26, 2023 |
| Lenovo        | ThinkCentre M58 3231W2Y     | [72f09cd320](https://linux-hardware.org/?probe=72f09cd320) | Jul 26, 2023 |
| ASUSTek       | PRIME X570-P                | [96f5f9ffdc](https://linux-hardware.org/?probe=96f5f9ffdc) | Jul 19, 2023 |
| ASRock        | B450 Pro4                   | [c10ecff0f6](https://linux-hardware.org/?probe=c10ecff0f6) | Jul 19, 2023 |
| ASUSTek       | PRIME X299-A II             | [54f9bd2050](https://linux-hardware.org/?probe=54f9bd2050) | Jul 18, 2023 |
| Gigabyte      | X79-UD3                     | [d688be2c92](https://linux-hardware.org/?probe=d688be2c92) | Jul 18, 2023 |
| Gigabyte      | Z490 GAMING X               | [866bc45d05](https://linux-hardware.org/?probe=866bc45d05) | Jul 18, 2023 |
| MSI           | B450M-A PRO MAX             | [4c8b8b5a8a](https://linux-hardware.org/?probe=4c8b8b5a8a) | Jul 18, 2023 |
| ASUSTek       | TUF Z270 MARK 2             | [d23b7166b1](https://linux-hardware.org/?probe=d23b7166b1) | Jul 18, 2023 |
| Gigabyte      | Z490 GAMING X               | [3c5ef629e4](https://linux-hardware.org/?probe=3c5ef629e4) | Jul 18, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [4d00148664](https://linux-hardware.org/?probe=4d00148664) | Jul 16, 2023 |
| Gigabyte      | X399 AORUS XTREME-CF        | [59bf614ae2](https://linux-hardware.org/?probe=59bf614ae2) | Jul 14, 2023 |
| MSI           | B450M-A PRO MAX             | [9ec51bc7eb](https://linux-hardware.org/?probe=9ec51bc7eb) | Jul 14, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [75d40e5a2b](https://linux-hardware.org/?probe=75d40e5a2b) | Jul 14, 2023 |
| MSI           | H510M-A PRO                 | [995e13dee9](https://linux-hardware.org/?probe=995e13dee9) | Jul 11, 2023 |
| Gigabyte      | Z490 GAMING X               | [27e600a93b](https://linux-hardware.org/?probe=27e600a93b) | Jul 07, 2023 |
| ASUSTek       | Rampage V EDITION 10        | [c945bae843](https://linux-hardware.org/?probe=c945bae843) | Jul 05, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [ca637a5884](https://linux-hardware.org/?probe=ca637a5884) | Jul 05, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [407e00921f](https://linux-hardware.org/?probe=407e00921f) | Jul 04, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [fc70411ea4](https://linux-hardware.org/?probe=fc70411ea4) | Jul 03, 2023 |
| Gigabyte      | Z490 GAMING X               | [107fe61a53](https://linux-hardware.org/?probe=107fe61a53) | Jul 02, 2023 |
| ASUSTek       | H110M-A                     | [c3118a3d89](https://linux-hardware.org/?probe=c3118a3d89) | Jun 29, 2023 |
| ASRock        | X570 Taichi                 | [895760e7db](https://linux-hardware.org/?probe=895760e7db) | Jun 27, 2023 |
| ASUSTek       | A68HM-PLUS                  | [fa162784e0](https://linux-hardware.org/?probe=fa162784e0) | Jun 24, 2023 |
| MSI           | Z77A-G41                    | [e7e4924bda](https://linux-hardware.org/?probe=e7e4924bda) | Jun 20, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [284344e775](https://linux-hardware.org/?probe=284344e775) | Jun 14, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [859f1b3a88](https://linux-hardware.org/?probe=859f1b3a88) | Jun 13, 2023 |
| ASUSTek       | PRIME B450M-A II            | [95bc101c80](https://linux-hardware.org/?probe=95bc101c80) | Jun 09, 2023 |
| Dell          | 00V62H A01                  | [89d6a4edd2](https://linux-hardware.org/?probe=89d6a4edd2) | May 13, 2023 |
| Unknown       | Intel X79                   | [6b1ddbd923](https://linux-hardware.org/?probe=6b1ddbd923) | May 03, 2023 |
| Biostar       | H110MHV3                    | [95b25ba480](https://linux-hardware.org/?probe=95b25ba480) | Apr 29, 2023 |
| ASUSTek       | A68HM-PLUS                  | [520ad2ca86](https://linux-hardware.org/?probe=520ad2ca86) | Mar 31, 2023 |
| HP            | 8437                        | [cdc32d8d8b](https://linux-hardware.org/?probe=cdc32d8d8b) | Mar 25, 2023 |
| HP            | 8437                        | [6fbb459a03](https://linux-hardware.org/?probe=6fbb459a03) | Mar 25, 2023 |
| ASUSTek       | A68HM-PLUS                  | [5d307f2d26](https://linux-hardware.org/?probe=5d307f2d26) | Mar 18, 2023 |
| Acer          | Aspire GX-281               | [d318df6931](https://linux-hardware.org/?probe=d318df6931) | Mar 04, 2023 |
| JINGSHA       | Unknown                     | [c8bd846b63](https://linux-hardware.org/?probe=c8bd846b63) | Feb 26, 2023 |
| Dell          | 0G3HR7 A00                  | [33723c8b80](https://linux-hardware.org/?probe=33723c8b80) | Feb 25, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [503fe663b4](https://linux-hardware.org/?probe=503fe663b4) | Feb 20, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [d76b048134](https://linux-hardware.org/?probe=d76b048134) | Feb 17, 2023 |
| HP            | 828A                        | [5f430ba8d1](https://linux-hardware.org/?probe=5f430ba8d1) | Jan 19, 2023 |
| Pegatron      | 2AF0                        | [77768feff6](https://linux-hardware.org/?probe=77768feff6) | Jan 01, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [f074ef2e7c](https://linux-hardware.org/?probe=f074ef2e7c) | Nov 15, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [711e95b72e](https://linux-hardware.org/?probe=711e95b72e) | Nov 02, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [ff0c19c661](https://linux-hardware.org/?probe=ff0c19c661) | Nov 02, 2022 |
| Gigabyte      | A320M-S2H-CF                | [bcf4fa1baf](https://linux-hardware.org/?probe=bcf4fa1baf) | Oct 18, 2022 |
| Dell          | 0GY6Y8 A02                  | [07b256f333](https://linux-hardware.org/?probe=07b256f333) | Oct 17, 2022 |
| Dell          | 0GY6Y8 A02                  | [fc1ec464bf](https://linux-hardware.org/?probe=fc1ec464bf) | Oct 17, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [bf0e112f9a](https://linux-hardware.org/?probe=bf0e112f9a) | Oct 16, 2022 |
| ASUSTek       | PRIME B250-PLUS             | [00ab764924](https://linux-hardware.org/?probe=00ab764924) | Oct 15, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [e037086b30](https://linux-hardware.org/?probe=e037086b30) | Oct 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [9931b35717](https://linux-hardware.org/?probe=9931b35717) | Sep 24, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [4c95b1bccf](https://linux-hardware.org/?probe=4c95b1bccf) | Aug 22, 2022 |
| Gigabyte      | B460M DS3H V2               | [2522ff1530](https://linux-hardware.org/?probe=2522ff1530) | Aug 13, 2022 |
| ASUSTek       | P7P55 LX                    | [8211ccc6cc](https://linux-hardware.org/?probe=8211ccc6cc) | Aug 11, 2022 |
| Unknown       | Unknown                     | [b73e5f9cbf](https://linux-hardware.org/?probe=b73e5f9cbf) | Aug 08, 2022 |
| Unknown       | Unknown                     | [f483092edf](https://linux-hardware.org/?probe=f483092edf) | Aug 07, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [a0507fae02](https://linux-hardware.org/?probe=a0507fae02) | Jul 31, 2022 |
| ASRock        | AB350 Pro4                  | [7049f819f0](https://linux-hardware.org/?probe=7049f819f0) | Jun 30, 2022 |
| HP            | 3396                        | [00782afa06](https://linux-hardware.org/?probe=00782afa06) | Jun 22, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [8109a04ffa](https://linux-hardware.org/?probe=8109a04ffa) | Jun 12, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [8a7401e54a](https://linux-hardware.org/?probe=8a7401e54a) | Jun 11, 2022 |
| Acer          | Aspire XC-886 V:2.0         | [2fe8cdaf93](https://linux-hardware.org/?probe=2fe8cdaf93) | May 31, 2022 |
| ASUSTek       | ROG Maximus X HERO          | [3ddad532a9](https://linux-hardware.org/?probe=3ddad532a9) | May 08, 2022 |
| MSI           | Z170-A PRO                  | [db5ab86328](https://linux-hardware.org/?probe=db5ab86328) | Apr 11, 2022 |
| MSI           | Z170-A PRO                  | [3bd5bb8d08](https://linux-hardware.org/?probe=3bd5bb8d08) | Apr 10, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [8d251b1b2a](https://linux-hardware.org/?probe=8d251b1b2a) | Apr 03, 2022 |
| HP            | 843B                        | [a88ff7cf5c](https://linux-hardware.org/?probe=a88ff7cf5c) | Mar 27, 2022 |
| Pegatron      | 2AC2                        | [d3c82e973b](https://linux-hardware.org/?probe=d3c82e973b) | Mar 25, 2022 |
| ASUSTek       | Maximus IX HERO             | [745cc1d638](https://linux-hardware.org/?probe=745cc1d638) | Mar 25, 2022 |
| ASUSTek       | Maximus IX HERO             | [8eb98db533](https://linux-hardware.org/?probe=8eb98db533) | Mar 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [13cdf54c81](https://linux-hardware.org/?probe=13cdf54c81) | Mar 21, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [639e7361ef](https://linux-hardware.org/?probe=639e7361ef) | Mar 12, 2022 |
| MSI           | Z170A PC MATE               | [181e014823](https://linux-hardware.org/?probe=181e014823) | Mar 08, 2022 |
| Gigabyte      | Z170X-UD3-CF                | [3ec7a7f643](https://linux-hardware.org/?probe=3ec7a7f643) | Mar 06, 2022 |
| ASUSTek       | P5Q PRO TURBO               | [83ca29c9c8](https://linux-hardware.org/?probe=83ca29c9c8) | Jan 28, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [230373b3ff](https://linux-hardware.org/?probe=230373b3ff) | Jan 09, 2022 |
| HP            | 1906                        | [5f8fe7cb20](https://linux-hardware.org/?probe=5f8fe7cb20) | Jan 06, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [793bfa4f40](https://linux-hardware.org/?probe=793bfa4f40) | Jan 04, 2022 |
| HP            | 2179                        | [79bac7ce1b](https://linux-hardware.org/?probe=79bac7ce1b) | Jan 01, 2022 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | [512091cd1c](https://linux-hardware.org/?probe=512091cd1c) | Dec 30, 2021 |
| HP            | 2179                        | [9b6358ce37](https://linux-hardware.org/?probe=9b6358ce37) | Dec 30, 2021 |
| ASRock        | X570 Taichi                 | [5c2c86f287](https://linux-hardware.org/?probe=5c2c86f287) | Dec 23, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [728b23aa46](https://linux-hardware.org/?probe=728b23aa46) | Nov 26, 2021 |
| ASUSTek       | PRIME A320M-K               | [9e9b6fd944](https://linux-hardware.org/?probe=9e9b6fd944) | Nov 21, 2021 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [4877535f8b](https://linux-hardware.org/?probe=4877535f8b) | Nov 03, 2021 |
| MSI           | Z370 GAMING PLUS            | [8dd5924480](https://linux-hardware.org/?probe=8dd5924480) | Oct 31, 2021 |
| Dell          | 0XC7MM A01                  | [390c5408b2](https://linux-hardware.org/?probe=390c5408b2) | Oct 05, 2021 |
| ASRock        | B450M Pro4                  | [a198e8517a](https://linux-hardware.org/?probe=a198e8517a) | Oct 01, 2021 |
| ASRock        | X570 Taichi                 | [50fd919991](https://linux-hardware.org/?probe=50fd919991) | Aug 29, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [a3c6fe4037](https://linux-hardware.org/?probe=a3c6fe4037) | Jul 24, 2021 |
| ASRock        | X570 Taichi                 | [57d19e2c3a](https://linux-hardware.org/?probe=57d19e2c3a) | May 19, 2021 |
| Acer          | FIH57                       | [9c3e383ea5](https://linux-hardware.org/?probe=9c3e383ea5) | Apr 30, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Xero Rolling | 134      | 96.4%   |
| Xero         | 5        | 3.6%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| Xero | 139      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Desktops | Percent |
|----------------------------|----------|---------|
| 6.4.12-arch1-1             | 19       | 12.5%   |
| 6.4.9-arch1-1              | 13       | 8.55%   |
| 6.4.3-arch1-2              | 11       | 7.24%   |
| 6.5.9-arch2-1              | 6        | 3.95%   |
| 6.6.2-arch1-1              | 5        | 3.29%   |
| 6.6.4-arch1-1              | 4        | 2.63%   |
| 6.4.10-arch1-1             | 4        | 2.63%   |
| 6.1.12-arch1-1             | 4        | 2.63%   |
| 6.6.1-arch1-1              | 3        | 1.97%   |
| 6.5.5-arch1-1              | 3        | 1.97%   |
| 6.6.3-arch1-1              | 2        | 1.32%   |
| 6.5.3-arch1-1              | 2        | 1.32%   |
| 6.4.3-arch1-1              | 2        | 1.32%   |
| 6.4.12-zen1-1-zen          | 2        | 1.32%   |
| 6.3.9-arch1-1              | 2        | 1.32%   |
| 6.2.12-arch1-1             | 2        | 1.32%   |
| 5.18.16-arch1-1            | 2        | 1.32%   |
| 5.16.15-arch1-1            | 2        | 1.32%   |
| 5.16.12-arch1-1            | 2        | 1.32%   |
| 6.6.7-arch1-1              | 1        | 0.66%   |
| 6.6.4-273-tkg-bore         | 1        | 0.66%   |
| 6.5.9-zen2-1-zen           | 1        | 0.66%   |
| 6.5.7-arch1-1              | 1        | 0.66%   |
| 6.5.4-arch2-1              | 1        | 0.66%   |
| 6.5.2-arch1-1              | 1        | 0.66%   |
| 6.5.2-273-tkg-bore-eevdf   | 1        | 0.66%   |
| 6.4.8-arch1-1              | 1        | 0.66%   |
| 6.4.7-zen1-1-zen           | 1        | 0.66%   |
| 6.4.7-arch1-2              | 1        | 0.66%   |
| 6.4.7-arch1-1              | 1        | 0.66%   |
| 6.4.4-hardened1-1-hardened | 1        | 0.66%   |
| 6.4.3-zen1-2-zen           | 1        | 0.66%   |
| 6.4.11-arch2-1             | 1        | 0.66%   |
| 6.4.1-arch2-1              | 1        | 0.66%   |
| 6.4.1-arch1-1              | 1        | 0.66%   |
| 6.3.9-lqx1-1-lqx           | 1        | 0.66%   |
| 6.3.8-zen1-1-zen           | 1        | 0.66%   |
| 6.3.7-arch1-1              | 1        | 0.66%   |
| 6.3.6-arch1-1              | 1        | 0.66%   |
| 6.2.8-arch1-1              | 1        | 0.66%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.4.12  | 21       | 13.82%  |
| 6.4.3   | 14       | 9.21%   |
| 6.4.9   | 13       | 8.55%   |
| 6.5.9   | 7        | 4.61%   |
| 6.6.4   | 5        | 3.29%   |
| 6.6.2   | 5        | 3.29%   |
| 6.4.10  | 4        | 2.63%   |
| 6.1.12  | 4        | 2.63%   |
| 6.6.1   | 3        | 1.97%   |
| 6.5.5   | 3        | 1.97%   |
| 6.4.7   | 3        | 1.97%   |
| 6.3.9   | 3        | 1.97%   |
| 5.15.12 | 3        | 1.97%   |
| 6.6.3   | 2        | 1.32%   |
| 6.5.3   | 2        | 1.32%   |
| 6.5.2   | 2        | 1.32%   |
| 6.4.1   | 2        | 1.32%   |
| 6.2.12  | 2        | 1.32%   |
| 5.19.13 | 2        | 1.32%   |
| 5.18.16 | 2        | 1.32%   |
| 5.16.16 | 2        | 1.32%   |
| 5.16.15 | 2        | 1.32%   |
| 5.16.12 | 2        | 1.32%   |
| 6.6.7   | 1        | 0.66%   |
| 6.5.7   | 1        | 0.66%   |
| 6.5.4   | 1        | 0.66%   |
| 6.4.8   | 1        | 0.66%   |
| 6.4.4   | 1        | 0.66%   |
| 6.4.11  | 1        | 0.66%   |
| 6.3.8   | 1        | 0.66%   |
| 6.3.7   | 1        | 0.66%   |
| 6.3.6   | 1        | 0.66%   |
| 6.2.8   | 1        | 0.66%   |
| 6.2.6   | 1        | 0.66%   |
| 6.2.13  | 1        | 0.66%   |
| 6.2.1   | 1        | 0.66%   |
| 6.1.6   | 1        | 0.66%   |
| 6.1.49  | 1        | 0.66%   |
| 6.0.6   | 1        | 0.66%   |
| 6.0.2   | 1        | 0.66%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.4     | 57       | 38.51%  |
| 6.6     | 16       | 10.81%  |
| 6.5     | 16       | 10.81%  |
| 5.15    | 9        | 6.08%   |
| 5.16    | 8        | 5.41%   |
| 6.3     | 6        | 4.05%   |
| 6.2     | 6        | 4.05%   |
| 6.1     | 6        | 4.05%   |
| 5.18    | 6        | 4.05%   |
| 5.19    | 5        | 3.38%   |
| 5.14    | 4        | 2.7%    |
| 6.0     | 3        | 2.03%   |
| 5.17    | 2        | 1.35%   |
| 5.13    | 2        | 1.35%   |
| 5.12    | 1        | 0.68%   |
| 5.11    | 1        | 0.68%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 139      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| KDE5  | 136      | 97.14%  |
| XFCE  | 2        | 1.43%   |
| GNOME | 2        | 1.43%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 122      | 87.14%  |
| Wayland | 16       | 11.43%  |
| Tty     | 2        | 1.43%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 119      | 83.22%  |
| Unknown | 13       | 9.09%   |
| LightDM | 8        | 5.59%   |
| GDM     | 2        | 1.4%    |
| TDM     | 1        | 0.7%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 55       | 39.01%  |
| de_DE      | 14       | 9.93%   |
| en_GB      | 9        | 6.38%   |
| ru_RU      | 6        | 4.26%   |
| pt_BR      | 6        | 4.26%   |
| it_IT      | 5        | 3.55%   |
| en_CA      | 5        | 3.55%   |
| C          | 5        | 3.55%   |
| tr_TR      | 4        | 2.84%   |
| pl_PL      | 4        | 2.84%   |
| es_MX      | 4        | 2.84%   |
| en_IN      | 4        | 2.84%   |
| fr_FR      | 3        | 2.13%   |
| de_AT      | 3        | 2.13%   |
| es_ES      | 2        | 1.42%   |
| en_AU      | 2        | 1.42%   |
| sv_SE      | 1        | 0.71%   |
| hu_HU      | 1        | 0.71%   |
| es_PE      | 1        | 0.71%   |
| es_AR      | 1        | 0.71%   |
| en_ZA      | 1        | 0.71%   |
| el_GR@euro | 1        | 0.71%   |
| el_GR      | 1        | 0.71%   |
| cs_CZ      | 1        | 0.71%   |
| bg_BG      | 1        | 0.71%   |
| ba_RU      | 1        | 0.71%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 100      | 71.43%  |
| BIOS | 40       | 28.57%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Btrfs   | 59       | 41.84%  |
| Ext4    | 51       | 36.17%  |
| Xfs     | 24       | 17.02%  |
| Overlay | 6        | 4.26%   |
| Nilfs2  | 1        | 0.71%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 111      | 79.29%  |
| MBR     | 16       | 11.43%  |
| Unknown | 13       | 9.29%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 90       | 63.38%  |
| Yes       | 52       | 36.62%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 77       | 55.4%   |
| Yes       | 62       | 44.6%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 46       | 33.09%  |
| MSI                 | 21       | 15.11%  |
| Gigabyte Technology | 18       | 12.95%  |
| Dell                | 12       | 8.63%   |
| Hewlett-Packard     | 10       | 7.19%   |
| ASRock              | 10       | 7.19%   |
| Acer                | 4        | 2.88%   |
| Pegatron            | 3        | 2.16%   |
| ECS                 | 3        | 2.16%   |
| Lenovo              | 2        | 1.44%   |
| Intel               | 2        | 1.44%   |
| Huanan              | 2        | 1.44%   |
| Unknown             | 2        | 1.44%   |
| Win Element         | 1        | 0.72%   |
| JINGSHA             | 1        | 0.72%   |
| Biostar             | 1        | 0.72%   |
| BESSTAR Tech        | 1        | 0.72%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| Dell OptiPlex 9020                | 4        | 2.88%   |
| MSI MS-7C37                       | 3        | 2.16%   |
| Dell OptiPlex 7010                | 3        | 2.16%   |
| Unknown                           | 3        | 2.16%   |
| MSI MS-7971                       | 2        | 1.44%   |
| Dell Studio XPS 8100              | 2        | 1.44%   |
| ASUS TUF Gaming X570-PLUS         | 2        | 1.44%   |
| ASUS PRIME A320M-K                | 2        | 1.44%   |
| Win Element M9                    | 1        | 0.72%   |
| Pegatron p7-1010a                 | 1        | 0.72%   |
| Pegatron p6-2026                  | 1        | 0.72%   |
| Pegatron 20-b010                  | 1        | 0.72%   |
| MSI MS-7D22                       | 1        | 0.72%   |
| MSI MS-7C96                       | 1        | 0.72%   |
| MSI MS-7C94                       | 1        | 0.72%   |
| MSI MS-7C91                       | 1        | 0.72%   |
| MSI MS-7C52                       | 1        | 0.72%   |
| MSI MS-7B61                       | 1        | 0.72%   |
| MSI MS-7B12                       | 1        | 0.72%   |
| MSI MS-7A70                       | 1        | 0.72%   |
| MSI MS-7A34                       | 1        | 0.72%   |
| MSI MS-7916                       | 1        | 0.72%   |
| MSI MS-7845                       | 1        | 0.72%   |
| MSI MS-7817                       | 1        | 0.72%   |
| MSI MS-7815                       | 1        | 0.72%   |
| MSI MS-7758                       | 1        | 0.72%   |
| MSI MS-7623                       | 1        | 0.72%   |
| MSI Gaming                        | 1        | 0.72%   |
| Lenovo ThinkCentre M58 3231W2Y    | 1        | 0.72%   |
| Lenovo 3302F3U                    | 1        | 0.72%   |
| Intel X99                         | 1        | 0.72%   |
| Intel B75                         | 1        | 0.72%   |
| Huanan X99-TF                     | 1        | 0.72%   |
| Huanan X99-F8                     | 1        | 0.72%   |
| HP Z230 SFF Workstation           | 1        | 0.72%   |
| HP ProOne 400 G1 AiO              | 1        | 0.72%   |
| HP ProDesk 400 G1 SFF             | 1        | 0.72%   |
| HP Pavilion Power Desktop 580-1xx | 1        | 0.72%   |
| HP Pavilion Desktop 590-p0xxx     | 1        | 0.72%   |
| HP Compaq Elite 8300 CMT          | 1        | 0.72%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS ROG           | 14       | 10.07%  |
| ASUS TUF           | 10       | 7.19%   |
| ASUS PRIME         | 9        | 6.47%   |
| Dell OptiPlex      | 8        | 5.76%   |
| MSI MS-7C37        | 3        | 2.16%   |
| Dell Studio        | 3        | 2.16%   |
| Acer Aspire        | 3        | 2.16%   |
| Unknown            | 3        | 2.16%   |
| MSI MS-7971        | 2        | 1.44%   |
| HP Pavilion        | 2        | 1.44%   |
| Gigabyte Z790      | 2        | 1.44%   |
| Gigabyte X570      | 2        | 1.44%   |
| Gigabyte B450M     | 2        | 1.44%   |
| ASUS M5A99X        | 2        | 1.44%   |
| Win Element M9     | 1        | 0.72%   |
| Pegatron p7-1010a  | 1        | 0.72%   |
| Pegatron p6-2026   | 1        | 0.72%   |
| Pegatron 20-b010   | 1        | 0.72%   |
| MSI MS-7D22        | 1        | 0.72%   |
| MSI MS-7C96        | 1        | 0.72%   |
| MSI MS-7C94        | 1        | 0.72%   |
| MSI MS-7C91        | 1        | 0.72%   |
| MSI MS-7C52        | 1        | 0.72%   |
| MSI MS-7B61        | 1        | 0.72%   |
| MSI MS-7B12        | 1        | 0.72%   |
| MSI MS-7A70        | 1        | 0.72%   |
| MSI MS-7A34        | 1        | 0.72%   |
| MSI MS-7916        | 1        | 0.72%   |
| MSI MS-7845        | 1        | 0.72%   |
| MSI MS-7817        | 1        | 0.72%   |
| MSI MS-7815        | 1        | 0.72%   |
| MSI MS-7758        | 1        | 0.72%   |
| MSI MS-7623        | 1        | 0.72%   |
| MSI Gaming         | 1        | 0.72%   |
| Lenovo ThinkCentre | 1        | 0.72%   |
| Lenovo 3302F3U     | 1        | 0.72%   |
| Intel X99          | 1        | 0.72%   |
| Intel B75          | 1        | 0.72%   |
| Huanan X99-TF      | 1        | 0.72%   |
| Huanan X99-F8      | 1        | 0.72%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 18       | 12.95%  |
| 2018 | 17       | 12.23%  |
| 2020 | 16       | 11.51%  |
| 2021 | 14       | 10.07%  |
| 2017 | 13       | 9.35%   |
| 2014 | 11       | 7.91%   |
| 2013 | 8        | 5.76%   |
| 2015 | 7        | 5.04%   |
| 2011 | 7        | 5.04%   |
| 2012 | 6        | 4.32%   |
| 2023 | 5        | 3.6%    |
| 2009 | 5        | 3.6%    |
| 2016 | 4        | 2.88%   |
| 2010 | 4        | 2.88%   |
| 2022 | 3        | 2.16%   |
| 2008 | 1        | 0.72%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 139      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 139      | 99.29%  |
| Enabled  | 1        | 0.71%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 139      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 50       | 35.97%  |
| 32.01-64.0  | 35       | 25.18%  |
| 8.01-16.0   | 22       | 15.83%  |
| 4.01-8.0    | 16       | 11.51%  |
| 3.01-4.0    | 6        | 4.32%   |
| 64.01-256.0 | 6        | 4.32%   |
| 24.01-32.0  | 4        | 2.88%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 47       | 30.92%  |
| 2.01-3.0   | 43       | 28.29%  |
| 4.01-8.0   | 26       | 17.11%  |
| 3.01-4.0   | 20       | 13.16%  |
| 8.01-16.0  | 7        | 4.61%   |
| 16.01-24.0 | 6        | 3.95%   |
| 0.01-0.5   | 2        | 1.32%   |
| 0.51-1.0   | 1        | 0.66%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 43       | 30.28%  |
| 2      | 38       | 26.76%  |
| 3      | 31       | 21.83%  |
| 4      | 12       | 8.45%   |
| 5      | 10       | 7.04%   |
| 6      | 4        | 2.82%   |
| 8      | 2        | 1.41%   |
| 7      | 2        | 1.41%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 98       | 70.5%   |
| Yes       | 41       | 29.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 138      | 99.28%  |
| No        | 1        | 0.72%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 76       | 53.9%   |
| No        | 65       | 46.1%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 76       | 53.9%   |
| Yes       | 65       | 46.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country        | Desktops | Percent |
|----------------|----------|---------|
| USA            | 31       | 22.14%  |
| Germany        | 16       | 11.43%  |
| Brazil         | 8        | 5.71%   |
| Russia         | 7        | 5%      |
| Canada         | 7        | 5%      |
| Poland         | 6        | 4.29%   |
| UK             | 5        | 3.57%   |
| Italy          | 5        | 3.57%   |
| Turkey         | 4        | 2.86%   |
| Mexico         | 4        | 2.86%   |
| India          | 4        | 2.86%   |
| Spain          | 3        | 2.14%   |
| France         | 3        | 2.14%   |
| Austria        | 3        | 2.14%   |
| Argentina      | 3        | 2.14%   |
| Romania        | 2        | 1.43%   |
| Pakistan       | 2        | 1.43%   |
| Netherlands    | 2        | 1.43%   |
| Greece         | 2        | 1.43%   |
| Czechia        | 2        | 1.43%   |
| Bulgaria       | 2        | 1.43%   |
| Bahrain        | 2        | 1.43%   |
| Australia      | 2        | 1.43%   |
| Venezuela      | 1        | 0.71%   |
| Switzerland    | 1        | 0.71%   |
| Sweden         | 1        | 0.71%   |
| South Africa   | 1        | 0.71%   |
| Portugal       | 1        | 0.71%   |
| Philippines    | 1        | 0.71%   |
| Peru           | 1        | 0.71%   |
| Lebanon        | 1        | 0.71%   |
| Iran           | 1        | 0.71%   |
| Hungary        | 1        | 0.71%   |
| Cyprus         | 1        | 0.71%   |
| Colombia       | 1        | 0.71%   |
| Belarus        | 1        | 0.71%   |
| Algeria        | 1        | 0.71%   |
| Åland Islands | 1        | 0.71%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Warsaw                 | 3        | 2.11%   |
| Red Lake               | 3        | 2.11%   |
| St Petersburg          | 2        | 1.41%   |
| Portland               | 2        | 1.41%   |
| Niterói               | 2        | 1.41%   |
| Mexico City            | 2        | 1.41%   |
| Hamburg                | 2        | 1.41%   |
| Cumming                | 2        | 1.41%   |
| Berlin                 | 2        | 1.41%   |
| Zell am See            | 1        | 0.7%    |
| York                   | 1        | 0.7%    |
| Wroclaw                | 1        | 0.7%    |
| Wrexham                | 1        | 0.7%    |
| Wolfville              | 1        | 0.7%    |
| Wesel                  | 1        | 0.7%    |
| Wells                  | 1        | 0.7%    |
| Vredenburg             | 1        | 0.7%    |
| Voronezh               | 1        | 0.7%    |
| Valparaiso de Goias    | 1        | 0.7%    |
| Termas de Rio Hondo    | 1        | 0.7%    |
| Teresina               | 1        | 0.7%    |
| Tehran                 | 1        | 0.7%    |
| Stow                   | 1        | 0.7%    |
| St Louis               | 1        | 0.7%    |
| Springfield            | 1        | 0.7%    |
| Sonora                 | 1        | 0.7%    |
| Sofia                  | 1        | 0.7%    |
| Shadrinsk              | 1        | 0.7%    |
| Sarcelles              | 1        | 0.7%    |
| Sao Paulo              | 1        | 0.7%    |
| Santiago de Compostela | 1        | 0.7%    |
| Santa Rosa             | 1        | 0.7%    |
| Sant Boi de Llobregat  | 1        | 0.7%    |
| Sankt Florian am Inn   | 1        | 0.7%    |
| Salt Lake City         | 1        | 0.7%    |
| Sacile                 | 1        | 0.7%    |
| Rosenheim              | 1        | 0.7%    |
| Rome                   | 1        | 0.7%    |
| Recreo                 | 1        | 0.7%    |
| Recklinghausen         | 1        | 0.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| WDC                          | 47       | 66     | 15.82%  |
| Seagate                      | 44       | 64     | 14.81%  |
| Samsung Electronics          | 44       | 75     | 14.81%  |
| Sandisk                      | 21       | 29     | 7.07%   |
| Kingston                     | 21       | 26     | 7.07%   |
| Crucial                      | 15       | 22     | 5.05%   |
| Toshiba                      | 12       | 15     | 4.04%   |
| Micron/Crucial Technology    | 8        | 10     | 2.69%   |
| Unknown                      | 6        | 7      | 2.02%   |
| Hitachi                      | 5        | 5      | 1.68%   |
| HGST                         | 5        | 5      | 1.68%   |
| ADATA Technology             | 5        | 5      | 1.68%   |
| SK hynix                     | 4        | 5      | 1.35%   |
| Phison Electronics           | 4        | 6      | 1.35%   |
| China                        | 4        | 4      | 1.35%   |
| Realtek Semiconductor        | 3        | 3      | 1.01%   |
| MAXIO Technology (Hangzhou)  | 3        | 3      | 1.01%   |
| Intenso                      | 3        | 5      | 1.01%   |
| Intel                        | 3        | 5      | 1.01%   |
| A-DATA Technology            | 3        | 3      | 1.01%   |
| Silicon Motion               | 2        | 3      | 0.67%   |
| PNY                          | 2        | 2      | 0.67%   |
| Phison                       | 2        | 2      | 0.67%   |
| Micron Technology            | 2        | 3      | 0.67%   |
| KingSpec                     | 2        | 2      | 0.67%   |
| ASMedia                      | 2        | 2      | 0.67%   |
| XrayDisk                     | 1        | 2      | 0.34%   |
| XPG                          | 1        | 1      | 0.34%   |
| Transcend                    | 1        | 1      | 0.34%   |
| Team                         | 1        | 1      | 0.34%   |
| SSK                          | 1        | 1      | 0.34%   |
| SPCC                         | 1        | 1      | 0.34%   |
| Shenzhen Longsys Electronics | 1        | 1      | 0.34%   |
| SABRENT                      | 1        | 1      | 0.34%   |
| Patriot                      | 1        | 1      | 0.34%   |
| Mushkin                      | 1        | 1      | 0.34%   |
| Maxtor                       | 1        | 1      | 0.34%   |
| Maxone                       | 1        | 1      | 0.34%   |
| LITEONIT                     | 1        | 1      | 0.34%   |
| LITEON                       | 1        | 1      | 0.34%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB             | 8        | 2.34%   |
| Crucial CT500MX500SSD1 500GB                                    | 8        | 2.34%   |
| Samsung SSD 860 EVO 500GB                                       | 5        | 1.46%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB              | 5        | 1.46%   |
| Kingston SA400S37960G 960GB SSD                                 | 5        | 1.46%   |
| Unknown SD/MMC/MS PRO 128GB                                     | 4        | 1.17%   |
| Seagate ST1000DM010-2EP102 1TB                                  | 4        | 1.17%   |
| Seagate ST1000DM003-1SB102 1TB                                  | 4        | 1.17%   |
| Kingston SA400S37240G 240GB SSD                                 | 4        | 1.17%   |
| WDC WD20EZBX-00AYRA0 2TB                                        | 3        | 0.88%   |
| Toshiba DT01ACA300 3TB                                          | 3        | 0.88%   |
| Seagate ST2000DM006-2DM164 2TB                                  | 3        | 0.88%   |
| Sandisk WD Blue SN570 500GB                                     | 3        | 0.88%   |
| Samsung SSD 850 EVO 250GB                                       | 3        | 0.88%   |
| Realtek RTS5763DL NVMe SSD Controller 512GB                     | 3        | 0.88%   |
| Micron/Crucial CT2000P5PSSD8 2TB                                | 3        | 0.88%   |
| Crucial CT1000MX500SSD1 1TB                                     | 3        | 0.88%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 1TB | 3        | 0.88%   |
| WDC WD10EZEX-60WN4A0 1TB                                        | 2        | 0.58%   |
| WDC WD10EZEX-60M2NA0 1TB                                        | 2        | 0.58%   |
| WDC WD10EZEX-22MFCA0 1TB                                        | 2        | 0.58%   |
| WDC WD10EZEX-08WN4A0 1TB                                        | 2        | 0.58%   |
| Toshiba MQ01ABD100 1TB                                          | 2        | 0.58%   |
| SK hynix SHPP41-2000GM 2TB                                      | 2        | 0.58%   |
| Seagate ST500DM002-1BD142 500GB                                 | 2        | 0.58%   |
| Seagate ST250DM000-1BD141 250GB                                 | 2        | 0.58%   |
| Seagate ST2000DM008-2FR102 2TB                                  | 2        | 0.58%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                              | 2        | 0.58%   |
| Seagate ST1000DM003-1ER162 1TB                                  | 2        | 0.58%   |
| Seagate ST1000DM003-1CH162 1TB                                  | 2        | 0.58%   |
| Seagate Expansion HDD 2TB                                       | 2        | 0.58%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                            | 2        | 0.58%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB                | 2        | 0.58%   |
| SanDisk NVMe SSD Drive 500GB                                    | 2        | 0.58%   |
| Samsung SSD 970 EVO 1TB                                         | 2        | 0.58%   |
| Samsung SSD 870 QVO 2TB                                         | 2        | 0.58%   |
| Samsung SSD 870 EVO 1TB                                         | 2        | 0.58%   |
| Samsung SSD 860 EVO 1TB                                         | 2        | 0.58%   |
| Phison PS5013 E13 NVMe Controller 512GB                         | 2        | 0.58%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                             | 2        | 0.58%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 44       | 64     | 36.07%  |
| WDC                 | 40       | 55     | 32.79%  |
| Toshiba             | 12       | 15     | 9.84%   |
| Hitachi             | 5        | 5      | 4.1%    |
| HGST                | 5        | 5      | 4.1%    |
| Unknown             | 4        | 4      | 3.28%   |
| Samsung Electronics | 4        | 4      | 3.28%   |
| Intenso             | 3        | 5      | 2.46%   |
| ASMedia             | 2        | 2      | 1.64%   |
| SSK                 | 1        | 1      | 0.82%   |
| Maxtor              | 1        | 1      | 0.82%   |
| Maxone              | 1        | 1      | 0.82%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 23       | 29     | 23%     |
| Kingston            | 18       | 23     | 18%     |
| Crucial             | 15       | 22     | 15%     |
| WDC                 | 8        | 8      | 8%      |
| SanDisk             | 8        | 8      | 8%      |
| China               | 4        | 4      | 4%      |
| PNY                 | 2        | 2      | 2%      |
| KingSpec            | 2        | 2      | 2%      |
| A-DATA Technology   | 2        | 2      | 2%      |
| XrayDisk            | 1        | 2      | 1%      |
| Transcend           | 1        | 1      | 1%      |
| Team                | 1        | 1      | 1%      |
| SPCC                | 1        | 1      | 1%      |
| Patriot             | 1        | 1      | 1%      |
| Mushkin             | 1        | 1      | 1%      |
| Micron Technology   | 1        | 1      | 1%      |
| LITEONIT            | 1        | 1      | 1%      |
| LITEON              | 1        | 1      | 1%      |
| Lexar               | 1        | 1      | 1%      |
| Leven               | 1        | 1      | 1%      |
| JMicron Technology  | 1        | 1      | 1%      |
| Hewlett-Packard     | 1        | 1      | 1%      |
| Gigabyte Technology | 1        | 1      | 1%      |
| Emtec               | 1        | 1      | 1%      |
| Corsair             | 1        | 1      | 1%      |
| ASMT                | 1        | 1      | 1%      |
| 2-Power             | 1        | 1      | 1%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 93       | 162    | 38.11%  |
| SSD  | 79       | 119    | 32.38%  |
| NVMe | 70       | 120    | 28.69%  |
| MMC  | 2        | 3      | 0.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 121      | 256    | 57.62%  |
| NVMe | 69       | 119    | 32.86%  |
| SAS  | 18       | 26     | 8.57%   |
| MMC  | 2        | 3      | 0.95%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 85       | 125    | 43.81%  |
| 0.51-1.0   | 58       | 84     | 29.9%   |
| 1.01-2.0   | 28       | 40     | 14.43%  |
| 3.01-4.0   | 9        | 12     | 4.64%   |
| 4.01-10.0  | 8        | 13     | 4.12%   |
| 2.01-3.0   | 6        | 7      | 3.09%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 32       | 22.07%  |
| 1001-2000      | 25       | 17.24%  |
| 251-500        | 24       | 16.55%  |
| 101-250        | 22       | 15.17%  |
| 501-1000       | 22       | 15.17%  |
| 2001-3000      | 5        | 3.45%   |
| 1-20           | 4        | 2.76%   |
| 51-100         | 4        | 2.76%   |
| Unknown        | 4        | 2.76%   |
| 21-50          | 3        | 2.07%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 49       | 33.33%  |
| 21-50          | 23       | 15.65%  |
| 101-250        | 20       | 13.61%  |
| 51-100         | 19       | 12.93%  |
| 251-500        | 10       | 6.8%    |
| 501-1000       | 8        | 5.44%   |
| More than 3000 | 6        | 4.08%   |
| 1001-2000      | 5        | 3.4%    |
| Unknown        | 4        | 2.72%   |
| 2001-3000      | 3        | 2.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                                      | Desktops | Drives | Percent |
|----------------------------------------------------------------------------|----------|--------|---------|
| Seagate ST1000DM010-2EP102 1TB                                             | 2        | 2      | 4.76%   |
| Seagate ST1000DM003-1ER162 1TB                                             | 2        | 3      | 4.76%   |
| ASMedia AS2115 8TB                                                         | 2        | 2      | 4.76%   |
| WDC WD5000AAKX-60U6AA0 500GB                                               | 1        | 1      | 2.38%   |
| WDC WD3200AAJS-08L7A0 320GB                                                | 1        | 1      | 2.38%   |
| WDC WD20EARX-00PASB0 2TB                                                   | 1        | 1      | 2.38%   |
| WDC WD1600AAJS-00L7A0 160GB                                                | 1        | 1      | 2.38%   |
| WDC WD10EZEX-60M2NA0 1TB                                                   | 1        | 1      | 2.38%   |
| WDC WD10EZEX-08WN4A0 1TB                                                   | 1        | 1      | 2.38%   |
| WDC WD10EADS-00M2B0 1TB                                                    | 1        | 1      | 2.38%   |
| WDC WD1002FAEX-00Z3A0 1TB                                                  | 1        | 2      | 2.38%   |
| Toshiba MQ01ABD100 1TB                                                     | 1        | 1      | 2.38%   |
| Toshiba MK4058GSX 400GB                                                    | 1        | 1      | 2.38%   |
| Seagate ST9500420AS 500GB                                                  | 1        | 1      | 2.38%   |
| Seagate ST9500325AS 500GB                                                  | 1        | 1      | 2.38%   |
| Seagate ST500DM009-2F110A 500GB                                            | 1        | 1      | 2.38%   |
| Seagate ST500DM002-1BD142 500GB                                            | 1        | 1      | 2.38%   |
| Seagate ST3320418AS 320GB                                                  | 1        | 1      | 2.38%   |
| Seagate ST320LT012-9WS14C 320GB                                            | 1        | 2      | 2.38%   |
| Seagate ST31000524AS 1TB                                                   | 1        | 1      | 2.38%   |
| Seagate ST2000VX000-1CU164 2TB                                             | 1        | 1      | 2.38%   |
| Seagate ST2000DM006-2DM164 2TB                                             | 1        | 1      | 2.38%   |
| Seagate ST2000DL003-9VT166 2TB                                             | 1        | 1      | 2.38%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                                         | 1        | 1      | 2.38%   |
| Seagate ST1000DM003-1SB10C 1TB                                             | 1        | 1      | 2.38%   |
| Samsung Electronics HD103SJ 1TB                                            | 1        | 1      | 2.38%   |
| SABRENT Disk 500GB                                                         | 1        | 1      | 2.38%   |
| Maxtor STM3160215AS 160GB                                                  | 1        | 1      | 2.38%   |
| Kingston SV300S37A120G 120GB SSD                                           | 1        | 1      | 2.38%   |
| Kingston SUV400S37240G 240GB SSD                                           | 1        | 1      | 2.38%   |
| Kingston SA400S37480G 480GB SSD                                            | 1        | 1      | 2.38%   |
| Hitachi HTS725050A9A364 500GB                                              | 1        | 1      | 2.38%   |
| Hitachi HDS721010CLA330 1TB                                                | 1        | 1      | 2.38%   |
| Hitachi HCP725050GLA380 500GB                                              | 1        | 1      | 2.38%   |
| HGST HDS724040ALE640 4TB                                                   | 1        | 1      | 2.38%   |
| Crucial CT1050MX300SSD1 1050GB                                             | 1        | 1      | 2.38%   |
| Corsair Force GT 240GB SSD                                                 | 1        | 1      | 2.38%   |
| China SATA3 240GB SSD                                                      | 1        | 1      | 2.38%   |
| ADATA Technology XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 1TB | 1        | 1      | 2.38%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 16       | 18     | 39.02%  |
| WDC                 | 8        | 9      | 19.51%  |
| Kingston            | 3        | 3      | 7.32%   |
| Hitachi             | 3        | 3      | 7.32%   |
| ASMedia             | 2        | 2      | 4.88%   |
| Toshiba             | 1        | 2      | 2.44%   |
| Samsung Electronics | 1        | 1      | 2.44%   |
| SABRENT             | 1        | 1      | 2.44%   |
| Maxtor              | 1        | 1      | 2.44%   |
| HGST                | 1        | 1      | 2.44%   |
| Crucial             | 1        | 1      | 2.44%   |
| Corsair             | 1        | 1      | 2.44%   |
| China               | 1        | 1      | 2.44%   |
| ADATA Technology    | 1        | 1      | 2.44%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 16       | 18     | 48.48%  |
| WDC                 | 8        | 9      | 24.24%  |
| Hitachi             | 3        | 3      | 9.09%   |
| ASMedia             | 2        | 2      | 6.06%   |
| Toshiba             | 1        | 2      | 3.03%   |
| Samsung Electronics | 1        | 1      | 3.03%   |
| Maxtor              | 1        | 1      | 3.03%   |
| HGST                | 1        | 1      | 3.03%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 32       | 37     | 80%     |
| SSD  | 6        | 6      | 15%     |
| NVMe | 2        | 2      | 5%      |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 118      | 296    | 64.13%  |
| Malfunc  | 39       | 45     | 21.2%   |
| Detected | 27       | 63     | 14.67%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 85       | 36.17%  |
| AMD                          | 55       | 23.4%   |
| Samsung Electronics          | 20       | 8.51%   |
| SanDisk                      | 17       | 7.23%   |
| ASMedia Technology           | 13       | 5.53%   |
| Micron/Crucial Technology    | 8        | 3.4%    |
| Phison Electronics           | 6        | 2.55%   |
| ADATA Technology             | 6        | 2.55%   |
| SK hynix                     | 4        | 1.7%    |
| Realtek Semiconductor        | 4        | 1.7%    |
| Kingston Technology Company  | 4        | 1.7%    |
| MAXIO Technology (Hangzhou)  | 3        | 1.28%   |
| Silicon Motion               | 2        | 0.85%   |
| Micron Technology            | 2        | 0.85%   |
| JMicron Technology           | 2        | 0.85%   |
| VIA Technologies             | 1        | 0.43%   |
| Shenzhen Longsys Electronics | 1        | 0.43%   |
| Marvell Technology Group     | 1        | 0.43%   |
| KIOXIA                       | 1        | 0.43%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 36       | 13.43%  |
| ASMedia ASM1062 Serial ATA Controller                                          | 13       | 4.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 12       | 4.48%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 11       | 4.1%    |
| AMD 500 Series Chipset SATA Controller                                         | 11       | 4.1%    |
| AMD 400 Series Chipset SATA Controller                                         | 11       | 4.1%    |
| Intel SATA Controller [RAID mode]                                              | 9        | 3.36%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 9        | 3.36%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 8        | 2.99%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 7        | 2.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7        | 2.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5        | 1.87%   |
| AMD FCH SATA Controller D                                                      | 5        | 1.87%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4        | 1.49%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 4        | 1.49%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 3        | 1.12%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 3        | 1.12%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3        | 1.12%   |
| Realtek RTS5762 NVMe SSD Controller                                            | 3        | 1.12%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 3        | 1.12%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 3        | 1.12%   |
| Intel 700 Series Chipset Family SATA AHCI Controller                           | 3        | 1.12%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3        | 1.12%   |
| AMD 300 Series Chipset SATA Controller                                         | 3        | 1.12%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 3        | 1.12%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 2        | 0.75%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                     | 2        | 0.75%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 2        | 0.75%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 2        | 0.75%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 2        | 0.75%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 2        | 0.75%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 2        | 0.75%   |
| Phison E12 NVMe Controller                                                     | 2        | 0.75%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2        | 0.75%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                      | 2        | 0.75%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 2        | 0.75%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2        | 0.75%   |
| Intel SSD 660P Series                                                          | 2        | 0.75%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 2        | 0.75%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 2        | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 123      | 57.75%  |
| NVMe | 69       | 32.39%  |
| RAID | 11       | 5.16%   |
| IDE  | 10       | 4.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 84       | 60.43%  |
| AMD    | 55       | 39.57%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor          | 6        | 4.29%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 4        | 2.86%   |
| AMD Ryzen 5 3600 6-Core Processor           | 4        | 2.86%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 3        | 2.14%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 3        | 2.14%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 2.14%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 3        | 2.14%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 3        | 2.14%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 3        | 2.14%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 3        | 2.14%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 3        | 2.14%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz         | 2        | 1.43%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2        | 1.43%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 1.43%   |
| Intel Core i7 CPU 870 @ 2.93GHz             | 2        | 1.43%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 2        | 1.43%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 1.43%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 1.43%   |
| Intel 12th Gen Core i9-12900K               | 2        | 1.43%   |
| AMD Ryzen 7 5800X3D 8-Core Processor        | 2        | 1.43%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 2        | 1.43%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 2        | 1.43%   |
| AMD Ryzen 5 5500                            | 2        | 1.43%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2        | 1.43%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 2        | 1.43%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1        | 0.71%   |
| Intel Xeon CPU E5-2695 v3 @ 2.30GHz         | 1        | 0.71%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz          | 1        | 0.71%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz          | 1        | 0.71%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz         | 1        | 0.71%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 1        | 0.71%   |
| Intel Pentium CPU G3260T @ 2.90GHz          | 1        | 0.71%   |
| Intel N100                                  | 1        | 0.71%   |
| Intel Genuine CPU 0000 @ 2.10GHz            | 1        | 0.71%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1        | 0.71%   |
| Intel Core i9-10900X CPU @ 3.70GHz          | 1        | 0.71%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 0.71%   |
| Intel Core i7-6950X CPU @ 3.00GHz           | 1        | 0.71%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 0.71%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 0.71%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i7          | 25       | 17.86%  |
| AMD Ryzen 5            | 25       | 17.86%  |
| Intel Core i5          | 24       | 17.14%  |
| AMD Ryzen 7            | 16       | 11.43%  |
| Intel Core i3          | 11       | 7.86%   |
| Other                  | 9        | 6.43%   |
| Intel Xeon             | 7        | 5%      |
| AMD Ryzen 3            | 3        | 2.14%   |
| AMD FX                 | 3        | 2.14%   |
| Intel Pentium          | 2        | 1.43%   |
| Intel Core i9          | 2        | 1.43%   |
| AMD Ryzen 9            | 2        | 1.43%   |
| AMD A8                 | 2        | 1.43%   |
| Intel Genuine          | 1        | 0.71%   |
| Intel Core 2 Quad      | 1        | 0.71%   |
| Intel Core 2 Duo       | 1        | 0.71%   |
| Intel Celeron          | 1        | 0.71%   |
| AMD Ryzen Threadripper | 1        | 0.71%   |
| AMD E1                 | 1        | 0.71%   |
| AMD Athlon II X3       | 1        | 0.71%   |
| AMD Athlon             | 1        | 0.71%   |
| AMD A4                 | 1        | 0.71%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 54       | 38.57%  |
| 6      | 34       | 24.29%  |
| 8      | 21       | 15%     |
| 2      | 15       | 10.71%  |
| 16     | 5        | 3.57%   |
| 12     | 4        | 2.86%   |
| 3      | 3        | 2.14%   |
| 10     | 2        | 1.43%   |
| 28     | 1        | 0.71%   |
| 24     | 1        | 0.71%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 137      | 98.56%  |
| 2      | 2        | 1.44%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 100      | 71.94%  |
| 1      | 39       | 28.06%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 139      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 67       | 46.53%  |
| 0x08701021 | 8        | 5.56%   |
| 0x506e3    | 5        | 3.47%   |
| 0x906ea    | 4        | 2.78%   |
| 0x0a50000c | 4        | 2.78%   |
| 0x0a201025 | 4        | 2.78%   |
| 0x0a201016 | 4        | 2.78%   |
| 0x08701030 | 4        | 2.78%   |
| 0x306c3    | 3        | 2.08%   |
| 0x0a20120a | 3        | 2.08%   |
| 0x08108109 | 3        | 2.08%   |
| 0x0800820d | 3        | 2.08%   |
| 0x306a9    | 2        | 1.39%   |
| 0x106e5    | 2        | 1.39%   |
| 0x0a50000d | 2        | 1.39%   |
| 0x0a201204 | 2        | 1.39%   |
| 0x0810100b | 2        | 1.39%   |
| 0xa0653    | 1        | 0.69%   |
| 0x906ed    | 1        | 0.69%   |
| 0x906eb    | 1        | 0.69%   |
| 0x906e9    | 1        | 0.69%   |
| 0x306f2    | 1        | 0.69%   |
| 0x20655    | 1        | 0.69%   |
| 0x1067a    | 1        | 0.69%   |
| 0x0a601206 | 1        | 0.69%   |
| 0x0a601203 | 1        | 0.69%   |
| 0x0a50000f | 1        | 0.69%   |
| 0x08701013 | 1        | 0.69%   |
| 0x08600106 | 1        | 0.69%   |
| 0x08101013 | 1        | 0.69%   |
| 0x08001138 | 1        | 0.69%   |
| 0x0700010f | 1        | 0.69%   |
| 0x0700010b | 1        | 0.69%   |
| 0x0600611a | 1        | 0.69%   |
| 0x06000852 | 1        | 0.69%   |
| 0x06000822 | 1        | 0.69%   |
| 0x0600081c | 1        | 0.69%   |
| 0x0500010d | 1        | 0.69%   |
| 0x010000c8 | 1        | 0.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 19       | 13.57%  |
| Haswell          | 18       | 12.86%  |
| KabyLake         | 15       | 10.71%  |
| Zen 2            | 14       | 10%     |
| IvyBridge        | 11       | 7.86%   |
| Skylake          | 10       | 7.14%   |
| Zen+             | 8        | 5.71%   |
| SandyBridge      | 6        | 4.29%   |
| Alderlake Hybrid | 6        | 4.29%   |
| Zen              | 5        | 3.57%   |
| Nehalem          | 5        | 3.57%   |
| Piledriver       | 4        | 2.86%   |
| CometLake        | 4        | 2.86%   |
| Penryn           | 3        | 2.14%   |
| Icelake          | 2        | 1.43%   |
| Unknown          | 2        | 1.43%   |
| Westmere         | 1        | 0.71%   |
| K10              | 1        | 0.71%   |
| Jaguar           | 1        | 0.71%   |
| Gracemont        | 1        | 0.71%   |
| Goldmont plus    | 1        | 0.71%   |
| Excavator        | 1        | 0.71%   |
| Broadwell        | 1        | 0.71%   |
| Bobcat           | 1        | 0.71%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 70       | 47.62%  |
| AMD               | 49       | 33.33%  |
| Intel             | 27       | 18.37%  |
| ASPEED Technology | 1        | 0.68%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7        | 4.7%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 7        | 4.7%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 6        | 4.03%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 6        | 4.03%   |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                    | 6        | 4.03%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 5        | 3.36%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 4        | 2.68%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 2.68%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4        | 2.68%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 3        | 2.01%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 2.01%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 3        | 2.01%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 2.01%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 3        | 2.01%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 2.01%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 3        | 2.01%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 1.34%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 1.34%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 1.34%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 1.34%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 1.34%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 1.34%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 1.34%   |
| Nvidia GF108 [GeForce GT 730]                                               | 2        | 1.34%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 1.34%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 2        | 1.34%   |
| Nvidia AD102 [GeForce RTX 4090]                                             | 2        | 1.34%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 1.34%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.34%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 1.34%   |
| AMD Raphael                                                                 | 2        | 1.34%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2        | 1.34%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 2        | 1.34%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 1.34%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.67%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.67%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.67%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 1        | 0.67%   |
| Nvidia GT200 [GeForce GTX 260]                                              | 1        | 0.67%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 62       | 44.29%  |
| 1 x AMD         | 48       | 34.29%  |
| 1 x Intel       | 21       | 15%     |
| Intel + Nvidia  | 4        | 2.86%   |
| 2 x Nvidia      | 2        | 1.43%   |
| 2 x Intel       | 1        | 0.71%   |
| Nvidia + ASPEED | 1        | 0.71%   |
| AMD + Nvidia    | 1        | 0.71%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 103      | 73.57%  |
| Proprietary | 34       | 24.29%  |
| Unknown     | 3        | 2.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 7.01-8.0   | 36       | 25.35%  |
| Unknown    | 36       | 25.35%  |
| 1.01-2.0   | 25       | 17.61%  |
| 3.01-4.0   | 15       | 10.56%  |
| 5.01-6.0   | 10       | 7.04%   |
| 8.01-16.0  | 8        | 5.63%   |
| 0.01-0.5   | 8        | 5.63%   |
| 16.01-24.0 | 2        | 1.41%   |
| 2.01-3.0   | 1        | 0.7%    |
| 0.51-1.0   | 1        | 0.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 33       | 22%     |
| Goldstar             | 16       | 10.67%  |
| Hewlett-Packard      | 15       | 10%     |
| Acer                 | 10       | 6.67%   |
| Dell                 | 8        | 5.33%   |
| Ancor Communications | 8        | 5.33%   |
| AOC                  | 7        | 4.67%   |
| Unknown              | 6        | 4%      |
| BenQ                 | 6        | 4%      |
| ASUSTek Computer     | 6        | 4%      |
| MSI                  | 4        | 2.67%   |
| Iiyama               | 4        | 2.67%   |
| Lenovo               | 3        | 2%      |
| Philips              | 2        | 1.33%   |
| Gigabyte Technology  | 2        | 1.33%   |
| Fujitsu Siemens      | 2        | 1.33%   |
| Unknown              | 2        | 1.33%   |
| Yeyian               | 1        | 0.67%   |
| Westinghouse         | 1        | 0.67%   |
| Vizio                | 1        | 0.67%   |
| ViewSonic            | 1        | 0.67%   |
| UTV                  | 1        | 0.67%   |
| Sony                 | 1        | 0.67%   |
| QIA                  | 1        | 0.67%   |
| Konka                | 1        | 0.67%   |
| Kogan                | 1        | 0.67%   |
| KOC                  | 1        | 0.67%   |
| JRY                  | 1        | 0.67%   |
| Idek Iiyama          | 1        | 0.67%   |
| HKC                  | 1        | 0.67%   |
| Hitachi              | 1        | 0.67%   |
| FOX                  | 1        | 0.67%   |
| Eizo                 | 1        | 0.67%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch               | 5        | 3.14%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch       | 3        | 1.89%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch       | 2        | 1.26%   |
| Samsung Electronics LCD Monitor SAM0B7C 1920x1080 886x498mm 40.0-inch   | 2        | 1.26%   |
| Goldstar ULTRAWIDE GSM76FA 2560x1080 798x334mm 34.1-inch                | 2        | 1.26%   |
| Goldstar LG ULTRAGEAR GSM7766 2560x1440 700x390mm 31.5-inch             | 2        | 1.26%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                   | 2        | 1.26%   |
| Goldstar FULL HD GSM5BDE 1920x1080 480x270mm 21.7-inch                  | 2        | 1.26%   |
| Dell S3221QS DELD107 3840x2160 697x392mm 31.5-inch                      | 2        | 1.26%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                       | 2        | 1.26%   |
| AOC Q2963 AOC2963 2560x1080 673x284mm 28.8-inch                         | 2        | 1.26%   |
| Ancor Communications ROG PG348Q ACI3433 3440x1440 798x335mm 34.1-inch   | 2        | 1.26%   |
| Unknown                                                                 | 2        | 1.26%   |
| Yeyian YMG-4K27-01 YEY2700 3840x2160 600x330mm 27.0-inch                | 1        | 0.63%   |
| Westinghouse SK-32H640G WDE6040 1366x768 709x399mm 32.0-inch            | 1        | 0.63%   |
| Vizio E320-B1 VIZ0095 1360x768 697x392mm 31.5-inch                      | 1        | 0.63%   |
| ViewSonic VX3211 SERIES VSCF534 1920x1080 698x392mm 31.5-inch           | 1        | 0.63%   |
| UTV Monitor UTV002F 3840x2160 1872x1053mm 84.6-inch                     | 1        | 0.63%   |
| Unknown LCD Monitor SAMSUNG 1360x768                                    | 1        | 0.63%   |
| Sony LCD Monitor AVSYSTEM 1280x720                                      | 1        | 0.63%   |
| Samsung Electronics T27B300 SAM0933 1920x1080 598x336mm 27.0-inch       | 1        | 0.63%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch     | 1        | 0.63%   |
| Samsung Electronics SyncMaster SAM0524 1920x1080 477x268mm 21.5-inch    | 1        | 0.63%   |
| Samsung Electronics SyncMaster SAM0484 1920x1080 520x320mm 24.0-inch    | 1        | 0.63%   |
| Samsung Electronics SyncMaster SAM02FE 1680x1050 433x271mm 20.1-inch    | 1        | 0.63%   |
| Samsung Electronics SMB2430H SAM064E 1920x1080                          | 1        | 0.63%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch      | 1        | 0.63%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch       | 1        | 0.63%   |
| Samsung Electronics SA300/350/360 SAM07D6 1920x1080 531x299mm 24.0-inch | 1        | 0.63%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 800x330mm 34.1-inch       | 1        | 0.63%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch       | 1        | 0.63%   |
| Samsung Electronics S27E510 SAM0C5F 1920x1080 598x336mm 27.0-inch       | 1        | 0.63%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1        | 0.63%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch       | 1        | 0.63%   |
| Samsung Electronics S22B350 SAM08D4 1920x1080 477x268mm 21.5-inch       | 1        | 0.63%   |
| Samsung Electronics LU28R55 SAM1019 3840x2160 632x360mm 28.6-inch       | 1        | 0.63%   |
| Samsung Electronics LCD Monitor SAM0DFA 3840x2160 890x500mm 40.2-inch   | 1        | 0.63%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 480x270mm 21.7-inch   | 1        | 0.63%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 700x390mm 31.5-inch   | 1        | 0.63%   |
| Samsung Electronics LCD Monitor SAM02EB 1920x540                        | 1        | 0.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 69       | 47.26%  |
| 2560x1440 (QHD)    | 18       | 12.33%  |
| 3840x2160 (4K)     | 16       | 10.96%  |
| 3440x1440          | 10       | 6.85%   |
| 2560x1080          | 5        | 3.42%   |
| 2288x1287          | 5        | 3.42%   |
| 1366x768 (WXGA)    | 4        | 2.74%   |
| 1360x768           | 4        | 2.74%   |
| 1680x1050 (WSXGA+) | 3        | 2.05%   |
| 1280x1024 (SXGA)   | 3        | 2.05%   |
| 3840x1080          | 2        | 1.37%   |
| 2560x1600          | 1        | 0.68%   |
| 1920x540           | 1        | 0.68%   |
| 1920x1200 (WUXGA)  | 1        | 0.68%   |
| 1600x900 (HD+)     | 1        | 0.68%   |
| 1440x900 (WXGA+)   | 1        | 0.68%   |
| 1280x720 (HD)      | 1        | 0.68%   |
| Unknown            | 1        | 0.68%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 27       | 17.53%  |
| 24      | 27       | 17.53%  |
| 23      | 17       | 11.04%  |
| 31      | 15       | 9.74%   |
| 21      | 14       | 9.09%   |
| 34      | 11       | 7.14%   |
| Unknown | 7        | 4.55%   |
| 142     | 5        | 3.25%   |
| 84      | 3        | 1.95%   |
| 28      | 3        | 1.95%   |
| 18      | 3        | 1.95%   |
| 58      | 2        | 1.3%    |
| 54      | 2        | 1.3%    |
| 40      | 2        | 1.3%    |
| 29      | 2        | 1.3%    |
| 20      | 2        | 1.3%    |
| 19      | 2        | 1.3%    |
| 52      | 1        | 0.65%   |
| 48      | 1        | 0.65%   |
| 39      | 1        | 0.65%   |
| 35      | 1        | 0.65%   |
| 33      | 1        | 0.65%   |
| 32      | 1        | 0.65%   |
| 26      | 1        | 0.65%   |
| 22      | 1        | 0.65%   |
| 17      | 1        | 0.65%   |
| 16      | 1        | 0.65%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 62       | 41.89%  |
| 601-700        | 23       | 15.54%  |
| 401-500        | 20       | 13.51%  |
| 701-800        | 13       | 8.78%   |
| Unknown        | 7        | 4.73%   |
| 1001-1500      | 6        | 4.05%   |
| More than 2000 | 5        | 3.38%   |
| 351-400        | 5        | 3.38%   |
| 801-900        | 4        | 2.7%    |
| 1501-2000      | 3        | 2.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 104      | 74.29%  |
| 21/9    | 15       | 10.71%  |
| 16/10   | 6        | 4.29%   |
| 1.00    | 5        | 3.57%   |
| Unknown | 5        | 3.57%   |
| 5/4     | 3        | 2.14%   |
| 32/9    | 1        | 0.71%   |
| 3/2     | 1        | 0.71%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 51       | 33.77%  |
| 351-500        | 31       | 20.53%  |
| 301-350        | 28       | 18.54%  |
| More than 1000 | 13       | 8.61%   |
| 251-300        | 7        | 4.64%   |
| Unknown        | 7        | 4.64%   |
| 151-200        | 6        | 3.97%   |
| 501-1000       | 4        | 2.65%   |
| 141-150        | 2        | 1.32%   |
| 131-140        | 1        | 0.66%   |
| 111-120        | 1        | 0.66%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 79       | 55.24%  |
| 101-120 | 30       | 20.98%  |
| 1-50    | 14       | 9.79%   |
| 121-160 | 10       | 6.99%   |
| Unknown | 7        | 4.9%    |
| 161-240 | 3        | 2.1%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 111      | 78.17%  |
| 2     | 25       | 17.61%  |
| 3     | 3        | 2.11%   |
| 0     | 3        | 2.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 92       | 44.23%  |
| Intel                           | 68       | 32.69%  |
| Qualcomm Atheros                | 11       | 5.29%   |
| Broadcom                        | 7        | 3.37%   |
| MediaTek                        | 5        | 2.4%    |
| TP-Link                         | 3        | 1.44%   |
| Ralink Technology               | 3        | 1.44%   |
| Ralink                          | 3        | 1.44%   |
| Aquantia                        | 3        | 1.44%   |
| Qualcomm Atheros Communications | 2        | 0.96%   |
| Qualcomm                        | 2        | 0.96%   |
| OPPO Electronics                | 2        | 0.96%   |
| Microsoft                       | 2        | 0.96%   |
| T & A Mobile Phones             | 1        | 0.48%   |
| QinHeng Electronics             | 1        | 0.48%   |
| NetGear                         | 1        | 0.48%   |
| Broadcom Limited                | 1        | 0.48%   |
| ASUSTek Computer                | 1        | 0.48%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 68       | 28.33%  |
| Realtek RTL8125 2.5GbE Controller                                 | 14       | 5.83%   |
| Intel I211 Gigabit Network Connection                             | 10       | 4.17%   |
| Intel Wi-Fi 6 AX200                                               | 9        | 3.75%   |
| Intel Ethernet Connection (2) I219-V                              | 9        | 3.75%   |
| Intel Ethernet Controller I225-V                                  | 7        | 2.92%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 6        | 2.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 2.5%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 5        | 2.08%   |
| Intel Ethernet Connection I217-LM                                 | 5        | 2.08%   |
| Intel Wireless-AC 9260                                            | 3        | 1.25%   |
| Intel Wireless 7265                                               | 3        | 1.25%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 1.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 1.25%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3        | 1.25%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter      | 3        | 1.25%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 2        | 0.83%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2        | 0.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.83%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 0.83%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 0.83%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.83%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2        | 0.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2        | 0.83%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 2        | 0.83%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2        | 0.83%   |
| OPPO RMX3623                                                      | 2        | 0.83%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 2        | 0.83%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2        | 0.83%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2        | 0.83%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 0.83%   |
| Intel 700 Series Chipset Family Wi-Fi                             | 2        | 0.83%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 0.42%   |
| T & A Mobile Phones TCL 30 Z                                      | 1        | 0.42%   |
| Realtek RTL8821CE PCIe 802.11ac Wireless Network Controller       | 1        | 0.42%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1        | 0.42%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1        | 0.42%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 0.42%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 34       | 41.98%  |
| Realtek Semiconductor           | 16       | 19.75%  |
| Qualcomm Atheros                | 5        | 6.17%   |
| MediaTek                        | 5        | 6.17%   |
| Broadcom                        | 5        | 6.17%   |
| TP-Link                         | 3        | 3.7%    |
| Ralink Technology               | 3        | 3.7%    |
| Ralink                          | 3        | 3.7%    |
| Qualcomm Atheros Communications | 2        | 2.47%   |
| Microsoft                       | 2        | 2.47%   |
| NetGear                         | 1        | 1.23%   |
| Broadcom Limited                | 1        | 1.23%   |
| ASUSTek Computer                | 1        | 1.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                       | 9        | 10.98%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                    | 6        | 7.32%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 5        | 6.1%    |
| Intel Wireless-AC 9260                                                    | 3        | 3.66%   |
| Intel Wireless 7265                                                       | 3        | 3.66%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 3        | 3.66%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter              | 3        | 3.66%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                       | 2        | 2.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 2        | 2.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 2        | 2.44%   |
| Qualcomm Atheros AR9271 802.11n                                           | 2        | 2.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                          | 2        | 2.44%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                          | 2        | 2.44%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                   | 2        | 2.44%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter             | 2        | 2.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 2        | 2.44%   |
| Intel 700 Series Chipset Family Wi-Fi                                     | 2        | 2.44%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                | 1        | 1.22%   |
| Realtek RTL8821CE PCIe 802.11ac Wireless Network Controller               | 1        | 1.22%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                   | 1        | 1.22%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                           | 1        | 1.22%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                     | 1        | 1.22%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                       | 1        | 1.22%   |
| Realtek RTL8188EE Wireless Network Adapter                                | 1        | 1.22%   |
| Realtek 802.11ac NIC                                                      | 1        | 1.22%   |
| Ralink RT5370 Wireless Adapter                                            | 1        | 1.22%   |
| Ralink RT2501/RT2573 Wireless Adapter                                     | 1        | 1.22%   |
| Ralink MT7601U Wireless Adapter                                           | 1        | 1.22%   |
| Ralink RT5392 PCIe Wireless Network Adapter                               | 1        | 1.22%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                    | 1        | 1.22%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                 | 1        | 1.22%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                          | 1        | 1.22%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)            | 1        | 1.22%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1        | 1.22%   |
| Microsoft XBOX ACC                                                        | 1        | 1.22%   |
| Microsoft Xbox 360 Wireless Adapter                                       | 1        | 1.22%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter             | 1        | 1.22%   |
| Intel Wireless 8265 / 8275                                                | 1        | 1.22%   |
| Intel Wireless 7260                                                       | 1        | 1.22%   |
| Intel Tiger Lake PCH CNVi WiFi                                            | 1        | 1.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 85       | 55.56%  |
| Intel                 | 50       | 32.68%  |
| Qualcomm Atheros      | 7        | 4.58%   |
| Broadcom              | 4        | 2.61%   |
| Aquantia              | 3        | 1.96%   |
| Qualcomm              | 2        | 1.31%   |
| OPPO Electronics      | 2        | 1.31%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 68       | 43.59%  |
| Realtek RTL8125 2.5GbE Controller                                   | 14       | 8.97%   |
| Intel I211 Gigabit Network Connection                               | 10       | 6.41%   |
| Intel Ethernet Connection (2) I219-V                                | 9        | 5.77%   |
| Intel Ethernet Controller I225-V                                    | 7        | 4.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 6        | 3.85%   |
| Intel Ethernet Connection I217-LM                                   | 5        | 3.21%   |
| Intel Ethernet Connection (7) I219-V                                | 3        | 1.92%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                     | 3        | 1.92%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 2        | 1.28%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 2        | 1.28%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 2        | 1.28%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet      | 2        | 1.28%   |
| OPPO RMX3623                                                        | 2        | 1.28%   |
| Intel Ethernet Connection (11) I219-V                               | 2        | 1.28%   |
| Intel 82579V Gigabit Network Connection                             | 2        | 1.28%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                    | 1        | 0.64%   |
| Qualcomm Redmi 9T                                                   | 1        | 0.64%   |
| Qualcomm Fairphone 4 5G                                             | 1        | 0.64%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller           | 1        | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 1        | 0.64%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                            | 1        | 0.64%   |
| Intel I210 Gigabit Network Connection                               | 1        | 0.64%   |
| Intel Ethernet Connection (2) I218-V                                | 1        | 0.64%   |
| Intel Ethernet Connection (17) I219-V                               | 1        | 0.64%   |
| Intel Ethernet Connection (14) I219-V                               | 1        | 0.64%   |
| Intel Ethernet Connection (10) I219-V                               | 1        | 0.64%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 1        | 0.64%   |
| Intel 82567LF-2 Gigabit Network Connection                          | 1        | 0.64%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                     | 1        | 0.64%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.64%   |
| Aquantia AQC113C NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]  | 1        | 0.64%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 1        | 0.64%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 138      | 63.89%  |
| WiFi     | 76       | 35.19%  |
| Modem    | 2        | 0.93%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 111      | 77.08%  |
| WiFi     | 33       | 22.92%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 76       | 53.9%   |
| 2     | 55       | 39.01%  |
| 3     | 7        | 4.96%   |
| 8     | 1        | 0.71%   |
| 4     | 1        | 0.71%   |
| 0     | 1        | 0.71%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 99       | 70.71%  |
| Yes  | 41       | 29.29%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 33       | 49.25%  |
| Cambridge Silicon Radio | 11       | 16.42%  |
| ASUSTek Computer        | 6        | 8.96%   |
| Realtek Semiconductor   | 5        | 7.46%   |
| TP-Link                 | 3        | 4.48%   |
| MediaTek                | 2        | 2.99%   |
| Foxconn / Hon Hai       | 2        | 2.99%   |
| Broadcom                | 2        | 2.99%   |
| Apple                   | 2        | 2.99%   |
| IMC Networks            | 1        | 1.49%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 11       | 16.42%  |
| Intel AX200 Bluetooth                                 | 9        | 13.43%  |
| Intel AX210 Bluetooth                                 | 6        | 8.96%   |
| Intel Bluetooth wireless interface                    | 5        | 7.46%   |
| TP-Link TP-Cdj+ UB5A Adapter                          | 3        | 4.48%   |
| Realtek Bluetooth Radio                               | 3        | 4.48%   |
| Intel Wireless-AC 3168 Bluetooth                      | 3        | 4.48%   |
| Intel Bluetooth Device                                | 3        | 4.48%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 3        | 4.48%   |
| Realtek  Bluetooth 4.2 Adapter                        | 2        | 2.99%   |
| MediaTek Wireless_Device                              | 2        | 2.99%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 2        | 2.99%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 2        | 2.99%   |
| Intel AX201 Bluetooth                                 | 2        | 2.99%   |
| ASUS Bluetooth Radio                                  | 2        | 2.99%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1        | 1.49%   |
| IMC Networks Wireless_Device                          | 1        | 1.49%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter          | 1        | 1.49%   |
| Foxconn / Hon Hai Bluetooth Device                    | 1        | 1.49%   |
| Broadcom HP Portable Bumble Bee                       | 1        | 1.49%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1        | 1.49%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 1.49%   |
| Apple Bluetooth USB Host Controller                   | 1        | 1.49%   |
| Apple Bluetooth Host Controller                       | 1        | 1.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 85       | 31.14%  |
| Nvidia                                       | 69       | 25.27%  |
| AMD                                          | 69       | 25.27%  |
| C-Media Electronics                          | 10       | 3.66%   |
| Corsair                                      | 4        | 1.47%   |
| Razer USA                                    | 3        | 1.1%    |
| Kingston Technology                          | 3        | 1.1%    |
| Generalplus Technology                       | 3        | 1.1%    |
| ASUSTek Computer                             | 3        | 1.1%    |
| Logitech                                     | 2        | 0.73%   |
| Elgato Systems                               | 2        | 0.73%   |
| BR25                                         | 2        | 0.73%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.37%   |
| Trust                                        | 1        | 0.37%   |
| Tenx Technology                              | 1        | 0.37%   |
| TC Electronic                                | 1        | 0.37%   |
| Soundprese                                   | 1        | 0.37%   |
| Shenzhen Riitek Technology                   | 1        | 0.37%   |
| PreSonus Audio Electronics                   | 1        | 0.37%   |
| Plantronics                                  | 1        | 0.37%   |
| Mark of the Unicorn                          | 1        | 0.37%   |
| JMTek                                        | 1        | 0.37%   |
| JBL                                          | 1        | 0.37%   |
| Hewlett-Packard                              | 1        | 0.37%   |
| GN Netcom                                    | 1        | 0.37%   |
| fifine Microphone                            | 1        | 0.37%   |
| ELMCU                                        | 1        | 0.37%   |
| Barco Display Systems                        | 1        | 0.37%   |
| Astro Gaming                                 | 1        | 0.37%   |
| Arturia                                      | 1        | 0.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 24       | 7.57%   |
| AMD Family 17h/19h HD Audio Controller                                     | 14       | 4.42%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 12       | 3.79%   |
| Intel 200 Series PCH HD Audio                                              | 12       | 3.79%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 10       | 3.15%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9        | 2.84%   |
| Nvidia GP104 High Definition Audio Controller                              | 9        | 2.84%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9        | 2.84%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8        | 2.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7        | 2.21%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7        | 2.21%   |
| AMD Navi 10 HDMI Audio                                                     | 7        | 2.21%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 7        | 2.21%   |
| Nvidia GA104 High Definition Audio Controller                              | 6        | 1.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6        | 1.89%   |
| Nvidia TU116 High Definition Audio Controller                              | 5        | 1.58%   |
| Nvidia TU106 High Definition Audio Controller                              | 5        | 1.58%   |
| Intel Cannon Lake PCH cAVS                                                 | 5        | 1.58%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 5        | 1.58%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5        | 1.58%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5        | 1.58%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 5        | 1.58%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4        | 1.26%   |
| Nvidia TU104 HD Audio Controller                                           | 3        | 0.95%   |
| Nvidia GP108 High Definition Audio Controller                              | 3        | 0.95%   |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 0.95%   |
| Nvidia GM204 High Definition Audio Controller                              | 3        | 0.95%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 0.95%   |
| Nvidia GA102 High Definition Audio Controller                              | 3        | 0.95%   |
| Intel Alder Lake-S HD Audio Controller                                     | 3        | 0.95%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 0.95%   |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1           | 3        | 0.95%   |
| Generalplus Technology USB Audio Device                                    | 3        | 0.95%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 3        | 0.95%   |
| ASUSTek Computer USB Audio                                                 | 3        | 0.95%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 0.95%   |
| AMD FCH Azalia Controller                                                  | 3        | 0.95%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2        | 0.63%   |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 0.63%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| G.Skill                      | 24       | 15.79%  |
| Corsair                      | 23       | 15.13%  |
| Kingston                     | 18       | 11.84%  |
| Samsung Electronics          | 13       | 8.55%   |
| SK hynix                     | 11       | 7.24%   |
| Crucial                      | 11       | 7.24%   |
| Unknown                      | 9        | 5.92%   |
| Team                         | 7        | 4.61%   |
| Micron Technology            | 7        | 4.61%   |
| A-DATA Technology            | 4        | 2.63%   |
| Unknown                      | 3        | 1.97%   |
| Ramaxel Technology           | 2        | 1.32%   |
| Patriot Memory (PDP Systems) | 2        | 1.32%   |
| Patriot                      | 2        | 1.32%   |
| GeIL                         | 2        | 1.32%   |
| Unifosa                      | 1        | 0.66%   |
| Transcend                    | 1        | 0.66%   |
| Timetec                      | 1        | 0.66%   |
| Silicon Power                | 1        | 0.66%   |
| Ramos Technology             | 1        | 0.66%   |
| PNY                          | 1        | 0.66%   |
| Nanya Technology             | 1        | 0.66%   |
| Kllisre                      | 1        | 0.66%   |
| KingFast                     | 1        | 0.66%   |
| Juhor                        | 1        | 0.66%   |
| Heoriady                     | 1        | 0.66%   |
| GOODRAM                      | 1        | 0.66%   |
| Goldkey                      | 1        | 0.66%   |
| Golden Empire                | 1        | 0.66%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 4        | 2.42%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s    | 3        | 1.82%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s    | 3        | 1.82%   |
| Unknown                                                | 3        | 1.82%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 2        | 1.21%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s     | 2        | 1.21%   |
| Team RAM TEAMGROUP-UD4-3000 8192MB DIMM DDR4 3200MT/s  | 2        | 1.21%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s   | 2        | 1.21%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s | 2        | 1.21%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s    | 2        | 1.21%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s    | 2        | 1.21%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s    | 2        | 1.21%   |
| Kingston RAM KHX2133C14/16G 16GB DIMM DDR4 2176MT/s    | 2        | 1.21%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1600MT/s    | 2        | 1.21%   |
| G.Skill RAM F4-3200C16-8GIS 8192MB DIMM DDR4 3200MT/s  | 2        | 1.21%   |
| G.Skill RAM F4-2666C15-4GVR 4GB DIMM DDR4 2933MT/s     | 2        | 1.21%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s            | 2        | 1.21%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s              | 1        | 0.61%   |
| Unknown RAM Module 4GB DIMM DDR4 2133MT/s              | 1        | 0.61%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s              | 1        | 0.61%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s              | 1        | 0.61%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s               | 1        | 0.61%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 1        | 0.61%   |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s              | 1        | 0.61%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s               | 1        | 0.61%   |
| Unknown RAM Module 16GB DIMM DDR4 2667MT/s             | 1        | 0.61%   |
| Unifosa RAM GU512303EP0202 2048MB DIMM DDR3 1333MT/s   | 1        | 0.61%   |
| Transcend RAM TS1GLK64V6H 8GB DIMM DDR3 1600MT/s       | 1        | 0.61%   |
| Timetec RAM Module 16GB SODIMM DDR4 3200MT/s           | 1        | 0.61%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3733MT/s     | 1        | 0.61%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s     | 1        | 0.61%   |
| Team RAM Elite-1600 4GB DIMM DDR3 1600MT/s             | 1        | 0.61%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s   | 1        | 0.61%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s   | 1        | 0.61%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s | 1        | 0.61%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 2000MT/s   | 1        | 0.61%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s | 1        | 0.61%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s   | 1        | 0.61%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1450MT/s   | 1        | 0.61%   |
| SK hynix RAM HMT125U6BFR8C-G7 2GB DIMM 1066MT/s        | 1        | 0.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 79       | 58.96%  |
| DDR3    | 40       | 29.85%  |
| DDR5    | 6        | 4.48%   |
| SDRAM   | 3        | 2.24%   |
| DDR2    | 3        | 2.24%   |
| Unknown | 2        | 1.49%   |
| DDR     | 1        | 0.75%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 123      | 94.62%  |
| SODIMM | 7        | 5.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 56       | 38.89%  |
| 16384 | 35       | 24.31%  |
| 4096  | 33       | 22.92%  |
| 2048  | 10       | 6.94%   |
| 32768 | 9        | 6.25%   |
| 1024  | 1        | 0.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 22       | 14.57%  |
| 3200  | 18       | 11.92%  |
| 3600  | 17       | 11.26%  |
| 2400  | 9        | 5.96%   |
| 1333  | 9        | 5.96%   |
| 2667  | 8        | 5.3%    |
| 2133  | 8        | 5.3%    |
| 2933  | 6        | 3.97%   |
| 1866  | 5        | 3.31%   |
| 3400  | 4        | 2.65%   |
| 1867  | 4        | 2.65%   |
| 1800  | 4        | 2.65%   |
| 3733  | 3        | 1.99%   |
| 3000  | 3        | 1.99%   |
| 2666  | 3        | 1.99%   |
| 4400  | 2        | 1.32%   |
| 3800  | 2        | 1.32%   |
| 2176  | 2        | 1.32%   |
| 2134  | 2        | 1.32%   |
| 1400  | 2        | 1.32%   |
| 1066  | 2        | 1.32%   |
| 800   | 2        | 1.32%   |
| 7000  | 1        | 0.66%   |
| 6400  | 1        | 0.66%   |
| 6000  | 1        | 0.66%   |
| 5800  | 1        | 0.66%   |
| 5600  | 1        | 0.66%   |
| 4800  | 1        | 0.66%   |
| 4133  | 1        | 0.66%   |
| 3666  | 1        | 0.66%   |
| 3467  | 1        | 0.66%   |
| 2747  | 1        | 0.66%   |
| 2000  | 1        | 0.66%   |
| 1648  | 1        | 0.66%   |
| 1450  | 1        | 0.66%   |
| 1067  | 1        | 0.66%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 2        | 40%     |
| Seiko Epson         | 1        | 20%     |
| Samsung Electronics | 1        | 20%     |
| Brother Industries  | 1        | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seiko Epson WF-2870 Series           | 1        | 20%     |
| Samsung ML-1640 Series Laser Printer | 1        | 20%     |
| HP LaserJet CP1525nw/x               | 1        | 20%     |
| HP Deskjet 2050 J510                 | 1        | 20%     |
| Brother HL-5250DN Printer            | 1        | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| Mustek Systems | 1        | 50%     |
| Canon          | 1        | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Mustek Systems BearPaw 2448 TA Plus | 1        | 50%     |
| Canon CanoScan LiDE 110             | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 8        | 27.59%  |
| Microdia                               | 6        | 20.69%  |
| Generalplus Technology                 | 3        | 10.34%  |
| Chicony Electronics                    | 3        | 10.34%  |
| Creative Technology                    | 2        | 6.9%    |
| Z-Star Microelectronics                | 1        | 3.45%   |
| Sunplus Innovation Technology          | 1        | 3.45%   |
| Samsung Electronics                    | 1        | 3.45%   |
| Panasonic (Matsushita)                 | 1        | 3.45%   |
| Jieli Technology                       | 1        | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) | 1        | 3.45%   |
| Aveo Technology                        | 1        | 3.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Microdia Webcam Vitade AF                                            | 3        | 10.34%  |
| Microdia USB 2.0 Camera                                              | 2        | 6.9%    |
| Logitech BRIO Ultra HD Webcam                                        | 2        | 6.9%    |
| Generalplus GENERAL WEBCAM                                           | 2        | 6.9%    |
| Creative Live! Cam Sync 1080p V2                                     | 2        | 6.9%    |
| Chicony HP High Definition 1MP Webcam                                | 2        | 6.9%    |
| Z-Star A4 TECH USB2.0 PC Camera E                                    | 1        | 3.45%   |
| Sunplus NexiGo N930AF FHD Webcam                                     | 1        | 3.45%   |
| Samsung Galaxy series, misc. (MTP mode)                              | 1        | 3.45%   |
| Panasonic (Matsushita) TY-CC20W                                      | 1        | 3.45%   |
| Microdia Camera                                                      | 1        | 3.45%   |
| Logitech Webcam Pro 9000                                             | 1        | 3.45%   |
| Logitech Webcam C930e                                                | 1        | 3.45%   |
| Logitech Webcam C600                                                 | 1        | 3.45%   |
| Logitech Portable Webcam C905                                        | 1        | 3.45%   |
| Logitech Logi Webcam C920e                                           | 1        | 3.45%   |
| Logitech HD Webcam C615                                              | 1        | 3.45%   |
| Jieli USB PHY 2.0                                                    | 1        | 3.45%   |
| Generalplus campark PC04                                             | 1        | 3.45%   |
| Chicony HP Integrated Webcam                                         | 1        | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) HP High Definition 1MP Webcam | 1        | 3.45%   |
| Aveo Camera                                                          | 1        | 3.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Elan Microelectronics | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200] | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 121      | 86.43%  |
| 1     | 19       | 13.57%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Desktops | Percent |
|--------------------|----------|---------|
| Net/wireless       | 6        | 33.33%  |
| Unassigned class   | 5        | 27.78%  |
| Graphics card      | 3        | 16.67%  |
| Bluetooth          | 3        | 16.67%  |
| Fingerprint reader | 1        | 5.56%   |

