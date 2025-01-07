OpenMandriva 5.0 - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for OpenMandriva 5.0.

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

Total: 631

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | K30BF_M32BF_A_F_K31BF_6     | [0b29006a62](https://linux-hardware.org/?probe=0b29006a62) | Jan 06, 2025 |
| MAXSUN        | MS-A86FX FS M.3             | [778b3689c2](https://linux-hardware.org/?probe=778b3689c2) | Jan 05, 2025 |
| MSI           | B450M MORTAR MAX            | [46e01ddb23](https://linux-hardware.org/?probe=46e01ddb23) | Jan 05, 2025 |
| Gigabyte      | B560M AORUS PRO             | [f43945b8dd](https://linux-hardware.org/?probe=f43945b8dd) | Jan 05, 2025 |
| Gigabyte      | 965GM-S2                    | [7d033b5974](https://linux-hardware.org/?probe=7d033b5974) | Jan 04, 2025 |
| HP            | 339A                        | [7fc68e979e](https://linux-hardware.org/?probe=7fc68e979e) | Jan 03, 2025 |
| Gigabyte      | B365M DS3H                  | [a49fde4df3](https://linux-hardware.org/?probe=a49fde4df3) | Jan 02, 2025 |
| Dell          | 02YYK5 A01                  | [97f04c0b58](https://linux-hardware.org/?probe=97f04c0b58) | Jan 01, 2025 |
| Dell          | 00V62H A01                  | [0133ba1278](https://linux-hardware.org/?probe=0133ba1278) | Jan 01, 2025 |
| Gigabyte      | H81M-S2PH                   | [8e18f9641a](https://linux-hardware.org/?probe=8e18f9641a) | Dec 31, 2024 |
| ASRock        | B450M-HDV R4.0              | [c996300bbf](https://linux-hardware.org/?probe=c996300bbf) | Dec 31, 2024 |
| Lenovo        | MAHOBAY                     | [3e28e8ad9e](https://linux-hardware.org/?probe=3e28e8ad9e) | Dec 31, 2024 |
| HP            | 8054                        | [c48b0d78c7](https://linux-hardware.org/?probe=c48b0d78c7) | Dec 30, 2024 |
| Gateway       | DX4860                      | [8fada96b83](https://linux-hardware.org/?probe=8fada96b83) | Dec 30, 2024 |
| ASRock        | H110M-ITX                   | [c76e007602](https://linux-hardware.org/?probe=c76e007602) | Dec 30, 2024 |
| Dell          | 0G261D A00                  | [8fb7d29eda](https://linux-hardware.org/?probe=8fb7d29eda) | Dec 30, 2024 |
| ASUSTek       | PRIME A320M-K               | [dae8bf9671](https://linux-hardware.org/?probe=dae8bf9671) | Dec 29, 2024 |
| HP            | 2B47                        | [1415963334](https://linux-hardware.org/?probe=1415963334) | Dec 28, 2024 |
| Gigabyte      | P55-UD3L                    | [1d3d66f3ac](https://linux-hardware.org/?probe=1d3d66f3ac) | Dec 27, 2024 |
| HP            | 212B                        | [0f306fdade](https://linux-hardware.org/?probe=0f306fdade) | Dec 26, 2024 |
| Dell          | 0GM819                      | [bb31438b8d](https://linux-hardware.org/?probe=bb31438b8d) | Dec 25, 2024 |
| ASUSTek       | M5A78L LE                   | [0705f8159c](https://linux-hardware.org/?probe=0705f8159c) | Dec 25, 2024 |
| Biostar       | H61MGC                      | [41e894b300](https://linux-hardware.org/?probe=41e894b300) | Dec 24, 2024 |
| ASUSTek       | GL10DH                      | [4d95f402c4](https://linux-hardware.org/?probe=4d95f402c4) | Dec 24, 2024 |
| Wistron       | ProLiant ML110 G6           | [1609625a37](https://linux-hardware.org/?probe=1609625a37) | Dec 24, 2024 |
| Acer          | RS780HVF                    | [bbc9e843db](https://linux-hardware.org/?probe=bbc9e843db) | Dec 23, 2024 |
| Lenovo        | Bantry CRB 31900002 WIN ... | [2a9d2d981b](https://linux-hardware.org/?probe=2a9d2d981b) | Dec 23, 2024 |
| Acer          | Extensa X2610G              | [b056768ca1](https://linux-hardware.org/?probe=b056768ca1) | Dec 23, 2024 |
| Intel         | X99-P4 V8.2                 | [a590e5197c](https://linux-hardware.org/?probe=a590e5197c) | Dec 21, 2024 |
| Gigabyte      | B560M DS3H                  | [f28c3f8b25](https://linux-hardware.org/?probe=f28c3f8b25) | Dec 20, 2024 |
| SZMZ          | B75-MS V1.0                 | [ab711506a2](https://linux-hardware.org/?probe=ab711506a2) | Dec 19, 2024 |
| Gigabyte      | Q87M-D2H                    | [b99f7b8080](https://linux-hardware.org/?probe=b99f7b8080) | Dec 18, 2024 |
| ASUSTek       | M4A79XTD EVO                | [94308b304f](https://linux-hardware.org/?probe=94308b304f) | Dec 18, 2024 |
| ASUSTek       | PRIME A320M-K               | [348937254f](https://linux-hardware.org/?probe=348937254f) | Dec 18, 2024 |
| Unknown       | Unknown                     | [deb145f9f9](https://linux-hardware.org/?probe=deb145f9f9) | Dec 18, 2024 |
| HP            | 83F2                        | [d6f68a1e91](https://linux-hardware.org/?probe=d6f68a1e91) | Dec 16, 2024 |
| MSI           | A320M-A PRO MAX             | [9c3b938ad7](https://linux-hardware.org/?probe=9c3b938ad7) | Dec 15, 2024 |
| Gigabyte      | B85M-D3H                    | [835a4f4d23](https://linux-hardware.org/?probe=835a4f4d23) | Dec 12, 2024 |
| MSI           | B550M-A PRO                 | [0ca583089a](https://linux-hardware.org/?probe=0ca583089a) | Dec 12, 2024 |
| MSI           | MS-7250                     | [2b89ec0eee](https://linux-hardware.org/?probe=2b89ec0eee) | Dec 09, 2024 |
| MSI           | X299 SLI PLUS               | [e487fc8054](https://linux-hardware.org/?probe=e487fc8054) | Dec 01, 2024 |
| ASUSTek       | P5G41-M LE                  | [d31490c125](https://linux-hardware.org/?probe=d31490c125) | Nov 28, 2024 |
| MSI           | MPG X570 GAMING PLUS        | [8bc7c644b4](https://linux-hardware.org/?probe=8bc7c644b4) | Nov 23, 2024 |
| ASRock Ind... | 4X4-8000 Series             | [0220306c05](https://linux-hardware.org/?probe=0220306c05) | Nov 23, 2024 |
| ASUSTek       | H110M-R                     | [852cf08f03](https://linux-hardware.org/?probe=852cf08f03) | Nov 23, 2024 |
| OEM           | X79-Turbo                   | [8e35c4675c](https://linux-hardware.org/?probe=8e35c4675c) | Nov 23, 2024 |
| Gigabyte      | M720-US3                    | [09009152d8](https://linux-hardware.org/?probe=09009152d8) | Nov 18, 2024 |
| ASRock        | H170 Pro4/D3                | [cd8e37a1c5](https://linux-hardware.org/?probe=cd8e37a1c5) | Nov 11, 2024 |
| Gigabyte      | B450M K-CF                  | [bad8781caa](https://linux-hardware.org/?probe=bad8781caa) | Nov 10, 2024 |
| Gigabyte      | AX370M-DS3H-CF              | [d80efa6fb0](https://linux-hardware.org/?probe=d80efa6fb0) | Nov 10, 2024 |
| ASRock        | N68C-S UCC                  | [181eb8f901](https://linux-hardware.org/?probe=181eb8f901) | Nov 08, 2024 |
| ASRock        | A520M Pro4                  | [c2076fe2ce](https://linux-hardware.org/?probe=c2076fe2ce) | Nov 08, 2024 |
| Dell          | 0WMJ54 A00                  | [7ad5566418](https://linux-hardware.org/?probe=7ad5566418) | Nov 08, 2024 |
| MSI           | MAG B550M MORTAR            | [c39a0e36fe](https://linux-hardware.org/?probe=c39a0e36fe) | Nov 04, 2024 |
| Gigabyte      | B450M DS3H V2               | [dddde83055](https://linux-hardware.org/?probe=dddde83055) | Nov 02, 2024 |
| Acer          | EM61SM/EM61PM               | [7dcd4deccd](https://linux-hardware.org/?probe=7dcd4deccd) | Nov 01, 2024 |
| Acer          | Veriton X6610G              | [3d2a3caadd](https://linux-hardware.org/?probe=3d2a3caadd) | Oct 31, 2024 |
| ASUSTek       | P6T DELUXE V2               | [038496f9e0](https://linux-hardware.org/?probe=038496f9e0) | Oct 28, 2024 |
| ASRock        | Z370 Pro4-IB                | [5d075536f8](https://linux-hardware.org/?probe=5d075536f8) | Oct 27, 2024 |
| Gigabyte      | Z390 GAMING X-CF            | [2d60c3fa69](https://linux-hardware.org/?probe=2d60c3fa69) | Oct 27, 2024 |
| Gigabyte      | EP31-DS3L                   | [28ab5fd5e9](https://linux-hardware.org/?probe=28ab5fd5e9) | Oct 26, 2024 |
| ASUSTek       | PRIME A320I-K               | [d7c1bb04df](https://linux-hardware.org/?probe=d7c1bb04df) | Oct 20, 2024 |
| ASUSTek       | A55BM-E                     | [48d05db7e4](https://linux-hardware.org/?probe=48d05db7e4) | Oct 20, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6767d35492](https://linux-hardware.org/?probe=6767d35492) | Oct 20, 2024 |
| HP            | 1905                        | [688122fc21](https://linux-hardware.org/?probe=688122fc21) | Oct 19, 2024 |
| HP            | 339A                        | [d5dbdecdd0](https://linux-hardware.org/?probe=d5dbdecdd0) | Oct 17, 2024 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [1ca706b171](https://linux-hardware.org/?probe=1ca706b171) | Oct 15, 2024 |
| Gigabyte      | B650I AX                    | [be7d845a8d](https://linux-hardware.org/?probe=be7d845a8d) | Oct 12, 2024 |
| HP            | 8054                        | [95774e5362](https://linux-hardware.org/?probe=95774e5362) | Oct 12, 2024 |
| ASRock        | Z77 Pro3                    | [be3976b747](https://linux-hardware.org/?probe=be3976b747) | Oct 10, 2024 |
| Lenovo        | ThinkCentre M57 6069Y4H     | [fea31ccd67](https://linux-hardware.org/?probe=fea31ccd67) | Oct 10, 2024 |
| Lenovo        | 0B98401 WIN                 | [63f829198f](https://linux-hardware.org/?probe=63f829198f) | Oct 08, 2024 |
| Lenovo        | ThinkCentre M57 6069Y4H     | [3a12eafd87](https://linux-hardware.org/?probe=3a12eafd87) | Oct 07, 2024 |
| Gigabyte      | B360M DS3H                  | [0c7e673d03](https://linux-hardware.org/?probe=0c7e673d03) | Oct 07, 2024 |
| Gigabyte      | Z370 HD3P-CF                | [96b432256b](https://linux-hardware.org/?probe=96b432256b) | Oct 05, 2024 |
| DFI           | SD106                       | [0c28fd0268](https://linux-hardware.org/?probe=0c28fd0268) | Oct 04, 2024 |
| Acer          | FIH57                       | [b5f488ca02](https://linux-hardware.org/?probe=b5f488ca02) | Oct 02, 2024 |
| Gigabyte      | H170-HD3 DDR3-CF            | [921f2aac12](https://linux-hardware.org/?probe=921f2aac12) | Sep 28, 2024 |
| MSI           | P45-C51                     | [1e87c16a46](https://linux-hardware.org/?probe=1e87c16a46) | Sep 24, 2024 |
| ASUSTek       | P5G41T-M LX2/GB             | [199c1cb792](https://linux-hardware.org/?probe=199c1cb792) | Sep 23, 2024 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [2b4b738285](https://linux-hardware.org/?probe=2b4b738285) | Sep 23, 2024 |
| Gigabyte      | G31M-ES2L                   | [d621fa79d7](https://linux-hardware.org/?probe=d621fa79d7) | Sep 20, 2024 |
| Firebat_Co... | ZY-AK2PLUS                  | [65773994a2](https://linux-hardware.org/?probe=65773994a2) | Sep 18, 2024 |
| Gigabyte      | Z170X-Gaming 3              | [5d2671c2f6](https://linux-hardware.org/?probe=5d2671c2f6) | Sep 15, 2024 |
| Fujitsu       | D3513-A1 S26361-D3513-A1    | [a4c4092a6f](https://linux-hardware.org/?probe=a4c4092a6f) | Sep 13, 2024 |
| ASRock        | FM2A88M Extreme4+           | [ee49152981](https://linux-hardware.org/?probe=ee49152981) | Sep 09, 2024 |
| ASUSTek       | PRIME A320M-K               | [f5282e45ee](https://linux-hardware.org/?probe=f5282e45ee) | Sep 09, 2024 |
| MSI           | B450M PRO-VDH MAX           | [6b2d7ca861](https://linux-hardware.org/?probe=6b2d7ca861) | Sep 07, 2024 |
| Dell          | 018D1Y A00                  | [cf1677f7f7](https://linux-hardware.org/?probe=cf1677f7f7) | Sep 07, 2024 |
| Dell          | 0R230R A00                  | [3525ce2b96](https://linux-hardware.org/?probe=3525ce2b96) | Sep 06, 2024 |
| ASUSTek       | PRIME B550-PLUS             | [7e6092a977](https://linux-hardware.org/?probe=7e6092a977) | Sep 06, 2024 |
| Intel         | H61                         | [d7173c0b12](https://linux-hardware.org/?probe=d7173c0b12) | Sep 05, 2024 |
| Packard Be... | IMEDIA S3840                | [ba0ee15e44](https://linux-hardware.org/?probe=ba0ee15e44) | Sep 04, 2024 |
| Acer          | Aspire TC-875 V:1.0         | [8e531f4882](https://linux-hardware.org/?probe=8e531f4882) | Sep 03, 2024 |
| HP            | 1497                        | [f54853d48f](https://linux-hardware.org/?probe=f54853d48f) | Sep 01, 2024 |
| Dell          | 0HD5W2 A01                  | [30b7ef985d](https://linux-hardware.org/?probe=30b7ef985d) | Aug 30, 2024 |
| Lenovo        | 313C SDK0J40697 WIN 3305... | [ac60f3ecf3](https://linux-hardware.org/?probe=ac60f3ecf3) | Aug 26, 2024 |
| Dell          | 042P49 A02                  | [e4528b878c](https://linux-hardware.org/?probe=e4528b878c) | Aug 26, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [3a90d721bf](https://linux-hardware.org/?probe=3a90d721bf) | Aug 25, 2024 |
| Gigabyte      | X570 AORUS ELITE            | [c8330e7c0f](https://linux-hardware.org/?probe=c8330e7c0f) | Aug 23, 2024 |
| ASRock        | B85M-HDS                    | [82de0e3b0a](https://linux-hardware.org/?probe=82de0e3b0a) | Aug 23, 2024 |
| HP            | 18E4                        | [d92f2ebee9](https://linux-hardware.org/?probe=d92f2ebee9) | Aug 22, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [f3fd3bd856](https://linux-hardware.org/?probe=f3fd3bd856) | Aug 20, 2024 |
| ASUSTek       | D642MF                      | [30e5e46f4b](https://linux-hardware.org/?probe=30e5e46f4b) | Aug 19, 2024 |
| MSI           | B350M MORTAR ARCTIC         | [0fe457c6a4](https://linux-hardware.org/?probe=0fe457c6a4) | Aug 16, 2024 |
| Intel         | H81                         | [4ffb92b8e5](https://linux-hardware.org/?probe=4ffb92b8e5) | Aug 15, 2024 |
| HP            | 1998                        | [3cdfbce6b7](https://linux-hardware.org/?probe=3cdfbce6b7) | Aug 14, 2024 |
| Gigabyte      | EP35C-DS3R                  | [9854603e00](https://linux-hardware.org/?probe=9854603e00) | Aug 12, 2024 |
| ASRock        | H81 Pro BTC R2.0            | [1c832af752](https://linux-hardware.org/?probe=1c832af752) | Aug 12, 2024 |
| Gigabyte      | EG41MF-US2H                 | [703ff72f1d](https://linux-hardware.org/?probe=703ff72f1d) | Aug 12, 2024 |
| ASUSTek       | M5A78L-M/USB3               | [b38807dffb](https://linux-hardware.org/?probe=b38807dffb) | Aug 10, 2024 |
| ASRock        | H77 Pro4-M                  | [5b61f3dffc](https://linux-hardware.org/?probe=5b61f3dffc) | Aug 10, 2024 |
| ASUSTek       | M5A78L-M LE/USB3            | [90f8587ff4](https://linux-hardware.org/?probe=90f8587ff4) | Aug 09, 2024 |
| Gigabyte      | P55A-UD3                    | [8d8e6b5219](https://linux-hardware.org/?probe=8d8e6b5219) | Aug 09, 2024 |
| Foxconn       | 2A8C                        | [1dce202e4a](https://linux-hardware.org/?probe=1dce202e4a) | Aug 08, 2024 |
| ASUSTek       | H81M-K                      | [417f0bdccc](https://linux-hardware.org/?probe=417f0bdccc) | Aug 07, 2024 |
| Dell          | 0GY6Y8 A01                  | [7ae6be0f1e](https://linux-hardware.org/?probe=7ae6be0f1e) | Aug 06, 2024 |
| Intel         | JSL MRD                     | [3652164504](https://linux-hardware.org/?probe=3652164504) | Aug 06, 2024 |
| MSI           | MS-7235                     | [72c632bab9](https://linux-hardware.org/?probe=72c632bab9) | Aug 05, 2024 |
| MSI           | PRESTIGE X570 CREATION      | [c2b5e93b29](https://linux-hardware.org/?probe=c2b5e93b29) | Aug 05, 2024 |
| ASRock        | X570 Taichi Razer Editio... | [519a8e1780](https://linux-hardware.org/?probe=519a8e1780) | Aug 04, 2024 |
| Gigabyte      | Z97-HD3                     | [26f6cd5e45](https://linux-hardware.org/?probe=26f6cd5e45) | Aug 04, 2024 |
| Gigabyte      | F2A55M-DS2                  | [9b683f9ad3](https://linux-hardware.org/?probe=9b683f9ad3) | Aug 04, 2024 |
| Gigabyte      | Z87X-UD3H-CF                | [c54ee32bf7](https://linux-hardware.org/?probe=c54ee32bf7) | Aug 04, 2024 |
| Gigabyte      | GA-H110M-H-CF               | [fcfc6212cd](https://linux-hardware.org/?probe=fcfc6212cd) | Aug 04, 2024 |
| Fujitsu       | D3164-A1 S26361-D3164-A1    | [3529471433](https://linux-hardware.org/?probe=3529471433) | Aug 03, 2024 |
| MSI           | PRO B650M-A WIFI            | [170f7898e7](https://linux-hardware.org/?probe=170f7898e7) | Aug 03, 2024 |
| MSI           | H310M PRO-D                 | [4cf9553370](https://linux-hardware.org/?probe=4cf9553370) | Aug 02, 2024 |
| Intel         | DH61WW AAG23116-204         | [1c61147d91](https://linux-hardware.org/?probe=1c61147d91) | Aug 01, 2024 |
| ASUSTek       | PRIME Z390M-PLUS            | [338e3a6bf5](https://linux-hardware.org/?probe=338e3a6bf5) | Aug 01, 2024 |
| Gigabyte      | X570S AORUS ELITE AX        | [b03694ae0c](https://linux-hardware.org/?probe=b03694ae0c) | Aug 01, 2024 |
| Gigabyte      | MZAPLBP-00                  | [f1eff3cdc0](https://linux-hardware.org/?probe=f1eff3cdc0) | Aug 01, 2024 |
| Gigabyte      | H170-Gaming 3               | [e364531174](https://linux-hardware.org/?probe=e364531174) | Jul 31, 2024 |
| MSI           | MS-7093                     | [ce4d1dc712](https://linux-hardware.org/?probe=ce4d1dc712) | Jul 29, 2024 |
| ASUSTek       | H110M-D                     | [71029ad9d3](https://linux-hardware.org/?probe=71029ad9d3) | Jul 28, 2024 |
| Gigabyte      | B550 GAMING X V2            | [e0f75fffaf](https://linux-hardware.org/?probe=e0f75fffaf) | Jul 27, 2024 |
| MSI           | B350M PRO-VDH               | [0f95697403](https://linux-hardware.org/?probe=0f95697403) | Jul 25, 2024 |
| MSI           | B450M-A PRO MAX II          | [50bdc69d96](https://linux-hardware.org/?probe=50bdc69d96) | Jul 25, 2024 |
| MSI           | B85M-P33                    | [69883afb1e](https://linux-hardware.org/?probe=69883afb1e) | Jul 25, 2024 |
| TYAN Compu... | S5191                       | [0b5e3bafb8](https://linux-hardware.org/?probe=0b5e3bafb8) | Jul 24, 2024 |
| ASRock        | 970 Extreme3                | [f509a3c5a9](https://linux-hardware.org/?probe=f509a3c5a9) | Jul 23, 2024 |
| Gigabyte      | B150M-D3H-CF                | [b07abe2d37](https://linux-hardware.org/?probe=b07abe2d37) | Jul 23, 2024 |
| OEM           | B75 Ver:1.41                | [face0b323d](https://linux-hardware.org/?probe=face0b323d) | Jul 23, 2024 |
| HP            | 18E7                        | [fd11953bea](https://linux-hardware.org/?probe=fd11953bea) | Jul 23, 2024 |
| Gigabyte      | B85-D3V-A                   | [3a623faece](https://linux-hardware.org/?probe=3a623faece) | Jul 23, 2024 |
| Lenovo        | 3102 SDK0J40705 WIN 3425... | [f73b9ac9df](https://linux-hardware.org/?probe=f73b9ac9df) | Jul 22, 2024 |
| Unknown       | Unknown                     | [a39981a23c](https://linux-hardware.org/?probe=a39981a23c) | Jul 21, 2024 |
| Dell          | 0JP3NX A00                  | [f260580df5](https://linux-hardware.org/?probe=f260580df5) | Jul 21, 2024 |
| Gigabyte      | Z270X-UD3-CF                | [5886254d87](https://linux-hardware.org/?probe=5886254d87) | Jul 21, 2024 |
| HP            | 83EE                        | [3c6cbd6943](https://linux-hardware.org/?probe=3c6cbd6943) | Jul 17, 2024 |
| Acer          | FI946GZG                    | [6cf80479b6](https://linux-hardware.org/?probe=6cf80479b6) | Jul 16, 2024 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | [ba1b9e364a](https://linux-hardware.org/?probe=ba1b9e364a) | Jul 15, 2024 |
| ASUSTek       | P8Z68-V LX                  | [cea2e41904](https://linux-hardware.org/?probe=cea2e41904) | Jul 15, 2024 |
| Sapphire      | PI-AM3RS760G2               | [34be774c07](https://linux-hardware.org/?probe=34be774c07) | Jul 15, 2024 |
| Gigabyte      | P55A-UD3                    | [5d392f6fff](https://linux-hardware.org/?probe=5d392f6fff) | Jul 13, 2024 |
| Gigabyte      | GA-870A-UD3                 | [44f606eb68](https://linux-hardware.org/?probe=44f606eb68) | Jul 09, 2024 |
| ASUSTek       | PRIME B450-PLUS             | [61f8183abc](https://linux-hardware.org/?probe=61f8183abc) | Jul 08, 2024 |
| ASUSTek       | PRIME H410M-E               | [0b0d915254](https://linux-hardware.org/?probe=0b0d915254) | Jul 08, 2024 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [bbd165776b](https://linux-hardware.org/?probe=bbd165776b) | Jul 07, 2024 |
| Gigabyte      | F2A88XM-D3H                 | [e000ecb4a7](https://linux-hardware.org/?probe=e000ecb4a7) | Jul 07, 2024 |
| ASRock        | A320M-HDV R3.0              | [42bd7d220b](https://linux-hardware.org/?probe=42bd7d220b) | Jul 07, 2024 |
| Dell          | 0CRH6C A02                  | [c983ea9227](https://linux-hardware.org/?probe=c983ea9227) | Jul 07, 2024 |
| Gigabyte      | MZBSWBP-00                  | [962c250436](https://linux-hardware.org/?probe=962c250436) | Jul 06, 2024 |
| ASUSTek       | B85M-K                      | [8e139cdbe5](https://linux-hardware.org/?probe=8e139cdbe5) | Jul 06, 2024 |
| ASRock        | Z790 PG Lightning           | [80c301b6f6](https://linux-hardware.org/?probe=80c301b6f6) | Jul 06, 2024 |
| Dell          | 0D441T A00                  | [f9ff9838a5](https://linux-hardware.org/?probe=f9ff9838a5) | Jul 06, 2024 |
| Dell          | 0WR7PY A02                  | [4f1e5cca7f](https://linux-hardware.org/?probe=4f1e5cca7f) | Jul 05, 2024 |
| MSI           | H87-G41 PC Mate             | [f8955d264a](https://linux-hardware.org/?probe=f8955d264a) | Jul 05, 2024 |
| Gigabyte      | 970A-D3P                    | [1aba817d5d](https://linux-hardware.org/?probe=1aba817d5d) | Jul 05, 2024 |
| Shenzhen M... | AHBAA OEM                   | [1976e0a587](https://linux-hardware.org/?probe=1976e0a587) | Jul 05, 2024 |
| MSI           | Indio                       | [ea5758d9fe](https://linux-hardware.org/?probe=ea5758d9fe) | Jul 05, 2024 |
| ASUSTek       | H110M-K                     | [91f540bb48](https://linux-hardware.org/?probe=91f540bb48) | Jul 05, 2024 |
| ASUSTek       | P8H61 PRO                   | [fa1250d324](https://linux-hardware.org/?probe=fa1250d324) | Jul 05, 2024 |
| Dell          | 0XC7MM A01                  | [1f31de5afd](https://linux-hardware.org/?probe=1f31de5afd) | Jul 04, 2024 |
| HP            | 8169                        | [c45572c08d](https://linux-hardware.org/?probe=c45572c08d) | Jul 04, 2024 |
| Unknown       | Unknown                     | [cc53303081](https://linux-hardware.org/?probe=cc53303081) | Jul 03, 2024 |
| ASUSTek       | H81M-PLUS                   | [ce1e7e565b](https://linux-hardware.org/?probe=ce1e7e565b) | Jul 03, 2024 |
| HP            | 0B54h D                     | [ddfbf7f597](https://linux-hardware.org/?probe=ddfbf7f597) | Jul 03, 2024 |
| ASUSTek       | H170-PRO                    | [4931bb2d2b](https://linux-hardware.org/?probe=4931bb2d2b) | Jul 02, 2024 |
| ASUSTek       | P5P43TD/USB3                | [89f6fd984f](https://linux-hardware.org/?probe=89f6fd984f) | Jul 01, 2024 |
| ASUSTek       | CS-B                        | [365939e38a](https://linux-hardware.org/?probe=365939e38a) | Jun 30, 2024 |
| Intel         | DQ965GF AAD41676-305        | [87f45fdd4f](https://linux-hardware.org/?probe=87f45fdd4f) | Jun 30, 2024 |
| Dell          | 0Y2MRG A00                  | [cab50448b9](https://linux-hardware.org/?probe=cab50448b9) | Jun 30, 2024 |
| Dell          | 0PU052                      | [6f7f59e0f8](https://linux-hardware.org/?probe=6f7f59e0f8) | Jun 27, 2024 |
| Dell          | 04Y8V0 A02                  | [0fc812d222](https://linux-hardware.org/?probe=0fc812d222) | Jun 27, 2024 |
| Gigabyte      | GA-MA790XT-UD4P             | [03dfe9e290](https://linux-hardware.org/?probe=03dfe9e290) | Jun 26, 2024 |
| MSI           | B450 GAMING PRO CARBON A... | [23590b5a8b](https://linux-hardware.org/?probe=23590b5a8b) | Jun 23, 2024 |
| Gigabyte      | GA-78LMT-S2PV               | [f5eace5b65](https://linux-hardware.org/?probe=f5eace5b65) | Jun 22, 2024 |
| HP            | 1496                        | [05cd12bc4d](https://linux-hardware.org/?probe=05cd12bc4d) | Jun 17, 2024 |
| MSI           | H61M-P20/W8                 | [eac1d8e94f](https://linux-hardware.org/?probe=eac1d8e94f) | Jun 17, 2024 |
| ASUSTek       | P8Z77-V LX                  | [d0f5698025](https://linux-hardware.org/?probe=d0f5698025) | Jun 16, 2024 |
| Unknown       | Unknown                     | [49bcc43bb3](https://linux-hardware.org/?probe=49bcc43bb3) | Jun 16, 2024 |
| MSI           | H110M PRO-VD                | [ba3dedbfbc](https://linux-hardware.org/?probe=ba3dedbfbc) | Jun 12, 2024 |
| MACHINIST     | E5-MR9A PRO V1.2            | [decba51c01](https://linux-hardware.org/?probe=decba51c01) | Jun 08, 2024 |
| Unknown       | G41 Series                  | [f9b4dbc607](https://linux-hardware.org/?probe=f9b4dbc607) | Jun 05, 2024 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [e94f8155f8](https://linux-hardware.org/?probe=e94f8155f8) | Jun 03, 2024 |
| Acer          | Veriton X2660G              | [5513cb5cb4](https://linux-hardware.org/?probe=5513cb5cb4) | Jun 03, 2024 |
| ASUSTek       | M5A78L-M LX3                | [9ce17e3dbf](https://linux-hardware.org/?probe=9ce17e3dbf) | Jun 02, 2024 |
| Intel         | H61                         | [4fd06e29f4](https://linux-hardware.org/?probe=4fd06e29f4) | Jun 02, 2024 |
| ASRock        | 960GM-VGS3 FX               | [238dab9e16](https://linux-hardware.org/?probe=238dab9e16) | Jun 01, 2024 |
| Acer          | Aspire TC-605               | [d713ebb2e5](https://linux-hardware.org/?probe=d713ebb2e5) | Jun 01, 2024 |
| Gigabyte      | F2A78M-HD2                  | [2ef2740e8e](https://linux-hardware.org/?probe=2ef2740e8e) | May 30, 2024 |
| Dell          | 0WMJ54 A01                  | [5066e01efe](https://linux-hardware.org/?probe=5066e01efe) | May 29, 2024 |
| Dell          | 0WMJ54 A01                  | [0313deb91f](https://linux-hardware.org/?probe=0313deb91f) | May 28, 2024 |
| Acer          | Aspire X1430                | [81afd0737e](https://linux-hardware.org/?probe=81afd0737e) | May 27, 2024 |
| Fujitsu       | D3009-A1 S26361-D3009-A1    | [fe8fd21c09](https://linux-hardware.org/?probe=fe8fd21c09) | May 27, 2024 |
| MSI           | PRO H610M-E DDR4            | [45ed7dced5](https://linux-hardware.org/?probe=45ed7dced5) | May 26, 2024 |
| Gigabyte      | H61M-S2PV                   | [f3a8d37051](https://linux-hardware.org/?probe=f3a8d37051) | May 26, 2024 |
| Biostar       | A58ML                       | [76f7150035](https://linux-hardware.org/?probe=76f7150035) | May 22, 2024 |
| ASRock        | B550M Steel Legend          | [8e8f62fc2c](https://linux-hardware.org/?probe=8e8f62fc2c) | May 20, 2024 |
| Gigabyte      | F2A68HM-DS2                 | [0c62b9f67c](https://linux-hardware.org/?probe=0c62b9f67c) | May 20, 2024 |
| Gigabyte      | Z170-HD3P-CF                | [3661609a9a](https://linux-hardware.org/?probe=3661609a9a) | May 18, 2024 |
| Supermicro    | X7DB8                       | [ae698b2086](https://linux-hardware.org/?probe=ae698b2086) | May 17, 2024 |
| Dell          | 0MN1TX A03                  | [54ecdd12b2](https://linux-hardware.org/?probe=54ecdd12b2) | May 13, 2024 |
| Radiant Sy... | P1230 FAB1                  | [0284fe839c](https://linux-hardware.org/?probe=0284fe839c) | May 12, 2024 |
| Lenovo        | MAHOBAY Win8 MM DPK IPG     | [3320c26914](https://linux-hardware.org/?probe=3320c26914) | May 12, 2024 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [a01c9d654b](https://linux-hardware.org/?probe=a01c9d654b) | May 11, 2024 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [7cbecfab77](https://linux-hardware.org/?probe=7cbecfab77) | May 10, 2024 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [53dc445161](https://linux-hardware.org/?probe=53dc445161) | May 10, 2024 |
| MSI           | PRO B650M-A WIFI            | [c5f27e5e7b](https://linux-hardware.org/?probe=c5f27e5e7b) | May 09, 2024 |
| ASUSTek       | PRIME A320M-E               | [d97bbebd45](https://linux-hardware.org/?probe=d97bbebd45) | May 07, 2024 |
| HP            | 8299                        | [6024274be6](https://linux-hardware.org/?probe=6024274be6) | May 06, 2024 |
| Intel         | DG45ID AAE27729-312         | [9610cedb7b](https://linux-hardware.org/?probe=9610cedb7b) | May 05, 2024 |
| HP            | 1850                        | [5bab4e9f9b](https://linux-hardware.org/?probe=5bab4e9f9b) | May 05, 2024 |
| Acer          | EQ45LM                      | [52563cbf82](https://linux-hardware.org/?probe=52563cbf82) | May 04, 2024 |
| MouseCompu... | H61MU-S01                   | [9ab7d4b6e9](https://linux-hardware.org/?probe=9ab7d4b6e9) | May 04, 2024 |
| Gigabyte      | GA-78LMT-S2                 | [6a9fd41a39](https://linux-hardware.org/?probe=6a9fd41a39) | May 04, 2024 |
| Gigabyte      | 970A-DS3P                   | [0cf6542a99](https://linux-hardware.org/?probe=0cf6542a99) | May 04, 2024 |
| Unknown       | G41 A01                     | [537cc137bd](https://linux-hardware.org/?probe=537cc137bd) | May 04, 2024 |
| Centerm       | C92                         | [beaeac18bc](https://linux-hardware.org/?probe=beaeac18bc) | May 04, 2024 |
| Gigabyte      | B450M DS3H V2               | [87b5a4320e](https://linux-hardware.org/?probe=87b5a4320e) | May 03, 2024 |
| ASRock        | X300M-STX                   | [58d58080cd](https://linux-hardware.org/?probe=58d58080cd) | May 03, 2024 |
| Acer          | FIH57                       | [8e4b02facb](https://linux-hardware.org/?probe=8e4b02facb) | May 02, 2024 |
| HP            | 2129                        | [3a5c2b8ae5](https://linux-hardware.org/?probe=3a5c2b8ae5) | May 02, 2024 |
| Acer          | EM61SM/EM61PM               | [3b2c0bd5f6](https://linux-hardware.org/?probe=3b2c0bd5f6) | May 01, 2024 |
| Dell          | 0KRC95 A00                  | [72ba135dda](https://linux-hardware.org/?probe=72ba135dda) | May 01, 2024 |
| Gigabyte      | H81M-HD3                    | [adcbc97b26](https://linux-hardware.org/?probe=adcbc97b26) | May 01, 2024 |
| MSI           | B450M MORTAR MAX            | [527f3123a6](https://linux-hardware.org/?probe=527f3123a6) | May 01, 2024 |
| Lenovo        | H410                        | [d16690b0c4](https://linux-hardware.org/?probe=d16690b0c4) | May 01, 2024 |
| Gigabyte      | B85M-D2V                    | [40ae77d112](https://linux-hardware.org/?probe=40ae77d112) | May 01, 2024 |
| MSI           | A68HM-E33                   | [abf75e8321](https://linux-hardware.org/?probe=abf75e8321) | Apr 29, 2024 |
| MSI           | PRO H610M-G DDR4            | [1492484deb](https://linux-hardware.org/?probe=1492484deb) | Apr 29, 2024 |
| Fujitsu       | D3433-S2 S26361-D3433-S2    | [ed1d2dac2d](https://linux-hardware.org/?probe=ed1d2dac2d) | Apr 28, 2024 |
| ASUSTek       | A8NE-FM                     | [dbabd85077](https://linux-hardware.org/?probe=dbabd85077) | Apr 28, 2024 |
| Dell          | 096JG8 A01                  | [5848ea3def](https://linux-hardware.org/?probe=5848ea3def) | Apr 27, 2024 |
| MSI           | PRO Z690-P DDR4             | [c43d04d511](https://linux-hardware.org/?probe=c43d04d511) | Apr 27, 2024 |
| Acer          | Revo M2-601 A01             | [54a18aaccb](https://linux-hardware.org/?probe=54a18aaccb) | Apr 24, 2024 |
| ASUSTek       | PRIME B550M-A               | [b662ccf901](https://linux-hardware.org/?probe=b662ccf901) | Apr 22, 2024 |
| ASUSTek       | M5A99X EVO                  | [afb6abad8d](https://linux-hardware.org/?probe=afb6abad8d) | Apr 21, 2024 |
| ASUSTek       | Amberine                    | [618eece8ca](https://linux-hardware.org/?probe=618eece8ca) | Apr 21, 2024 |
| ASUSTek       | PRIME H410M-A               | [41da917e67](https://linux-hardware.org/?probe=41da917e67) | Apr 21, 2024 |
| ASUSTek       | A88XM-E                     | [6ff101f38c](https://linux-hardware.org/?probe=6ff101f38c) | Apr 19, 2024 |
| Gigabyte      | H170M-D3H DDR3-CF           | [f7a78f85d8](https://linux-hardware.org/?probe=f7a78f85d8) | Apr 18, 2024 |
| ASUSTek       | P5N72-T PREMIUM             | [067b12dd29](https://linux-hardware.org/?probe=067b12dd29) | Apr 16, 2024 |
| Dell          | 0D28YY A03                  | [0332c27e2c](https://linux-hardware.org/?probe=0332c27e2c) | Apr 16, 2024 |
| ASUSTek       | P8H61-MX R2.0               | [53a06e22d4](https://linux-hardware.org/?probe=53a06e22d4) | Apr 16, 2024 |
| MSI           | H81M-E34                    | [61891eff16](https://linux-hardware.org/?probe=61891eff16) | Apr 15, 2024 |
| HP            | 805D                        | [f3b0ef4a3b](https://linux-hardware.org/?probe=f3b0ef4a3b) | Apr 14, 2024 |
| Gigabyte      | H110M-DS2V-CF               | [40fe788bf0](https://linux-hardware.org/?probe=40fe788bf0) | Apr 14, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [a829e68e1f](https://linux-hardware.org/?probe=a829e68e1f) | Apr 14, 2024 |
| MAXSUN        | MS-Terminator B760M D4 V... | [5a0687cb6d](https://linux-hardware.org/?probe=5a0687cb6d) | Apr 13, 2024 |
| ASRock        | H510M-HDV R2.0              | [5b213df28c](https://linux-hardware.org/?probe=5b213df28c) | Apr 12, 2024 |
| Gigabyte      | GA-970A-D3                  | [1a6e8ab59b](https://linux-hardware.org/?probe=1a6e8ab59b) | Apr 12, 2024 |
| ASUSTek       | P5Q                         | [05d54173b4](https://linux-hardware.org/?probe=05d54173b4) | Apr 08, 2024 |
| ASUSTek       | P8H77-V                     | [721926ded3](https://linux-hardware.org/?probe=721926ded3) | Apr 08, 2024 |
| Daten Tecn... | DA75PRO                     | [aaf78d3f34](https://linux-hardware.org/?probe=aaf78d3f34) | Apr 07, 2024 |
| HP            | 8054                        | [55c6935be9](https://linux-hardware.org/?probe=55c6935be9) | Apr 07, 2024 |
| ASRock        | 970A-G                      | [e1e0f99df4](https://linux-hardware.org/?probe=e1e0f99df4) | Apr 06, 2024 |
| Gigabyte      | B85M-D3H                    | [69a0e2f77d](https://linux-hardware.org/?probe=69a0e2f77d) | Apr 06, 2024 |
| ASRock        | B150M Pro4                  | [75a5d3af57](https://linux-hardware.org/?probe=75a5d3af57) | Apr 06, 2024 |
| HP            | 8653 A                      | [1ab035c8c7](https://linux-hardware.org/?probe=1ab035c8c7) | Apr 06, 2024 |
| ASUSTek       | P5KPL-CM                    | [7fb2e983ef](https://linux-hardware.org/?probe=7fb2e983ef) | Apr 06, 2024 |
| Gigabyte      | GA-880GM-USB3               | [2ad3b3efa3](https://linux-hardware.org/?probe=2ad3b3efa3) | Apr 06, 2024 |
| Gigabyte      | B85M-HD3                    | [3d81eb0d82](https://linux-hardware.org/?probe=3d81eb0d82) | Apr 05, 2024 |
| ASUSTek       | PRIME Z590-P                | [9ef1b07dc2](https://linux-hardware.org/?probe=9ef1b07dc2) | Apr 05, 2024 |
| MSI           | Z590 PRO WIFI               | [b4b9cef6a6](https://linux-hardware.org/?probe=b4b9cef6a6) | Apr 05, 2024 |
| ASUSTek       | PRIME X470-PRO              | [e16e4757cf](https://linux-hardware.org/?probe=e16e4757cf) | Apr 04, 2024 |
| MSI           | H310M PRO-VDH               | [98d131eacb](https://linux-hardware.org/?probe=98d131eacb) | Apr 04, 2024 |
| ASUSTek       | PRIME H570-PLUS             | [69279a9792](https://linux-hardware.org/?probe=69279a9792) | Apr 04, 2024 |
| ASRock        | A520M Pro4                  | [dd6acd4be2](https://linux-hardware.org/?probe=dd6acd4be2) | Apr 04, 2024 |
| ASRock        | B450 Pro4 R2.0              | [60056839c9](https://linux-hardware.org/?probe=60056839c9) | Apr 03, 2024 |
| Gigabyte      | MFLP5IP-00                  | [aedb7d1450](https://linux-hardware.org/?probe=aedb7d1450) | Apr 03, 2024 |
| Gigabyte      | F2A68HM-H                   | [e9bf1ed29d](https://linux-hardware.org/?probe=e9bf1ed29d) | Apr 01, 2024 |
| ASUSTek       | PRIME A320I-K               | [463d13b7df](https://linux-hardware.org/?probe=463d13b7df) | Apr 01, 2024 |
| ASUSTek       | PRIME Z390M-PLUS            | [2f1c067d48](https://linux-hardware.org/?probe=2f1c067d48) | Apr 01, 2024 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [939cfeb31e](https://linux-hardware.org/?probe=939cfeb31e) | Apr 01, 2024 |
| ASRock        | FM2A88X Extreme6+           | [1f8ed16982](https://linux-hardware.org/?probe=1f8ed16982) | Apr 01, 2024 |
| Gigabyte      | B250M-Gaming5-CF            | [47d0634e2a](https://linux-hardware.org/?probe=47d0634e2a) | Mar 31, 2024 |
| MSI           | H310M PRO-M2                | [b2753ac794](https://linux-hardware.org/?probe=b2753ac794) | Mar 31, 2024 |
| ASUSTek       | PRIME H310M-D R2.0          | [b251cdc4d6](https://linux-hardware.org/?probe=b251cdc4d6) | Mar 31, 2024 |
| MouseCompu... | B85H3-M4/2.0                | [0318e0dbfb](https://linux-hardware.org/?probe=0318e0dbfb) | Mar 31, 2024 |
| ASUSTek       | H81M-K                      | [483eaeb53c](https://linux-hardware.org/?probe=483eaeb53c) | Mar 30, 2024 |
| ASRock        | G31M-S                      | [7df654f75f](https://linux-hardware.org/?probe=7df654f75f) | Mar 30, 2024 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [1fb5102d8c](https://linux-hardware.org/?probe=1fb5102d8c) | Mar 30, 2024 |
| Gigabyte      | H87-HD3                     | [2dc48c8319](https://linux-hardware.org/?probe=2dc48c8319) | Mar 30, 2024 |
| Gigabyte      | B450M DS3H V2               | [e239e5305b](https://linux-hardware.org/?probe=e239e5305b) | Mar 30, 2024 |
| Dell          | 0GDG8Y A00                  | [70199cb1ec](https://linux-hardware.org/?probe=70199cb1ec) | Mar 29, 2024 |
| ASRock        | Z87 Extreme6                | [a7ffff15ff](https://linux-hardware.org/?probe=a7ffff15ff) | Mar 28, 2024 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [697b22a027](https://linux-hardware.org/?probe=697b22a027) | Mar 28, 2024 |
| ASUSTek       | P8Z77-V LX                  | [af967ddbdc](https://linux-hardware.org/?probe=af967ddbdc) | Mar 26, 2024 |
| Dell          | 0JP3NX A01                  | [01246bca4d](https://linux-hardware.org/?probe=01246bca4d) | Mar 26, 2024 |
| ASUSTek       | P5K SE                      | [2391cf9f32](https://linux-hardware.org/?probe=2391cf9f32) | Mar 26, 2024 |
| AFOX          | IH61-MA5                    | [a5418cfc92](https://linux-hardware.org/?probe=a5418cfc92) | Mar 24, 2024 |
| Acer          | Veriton M4620G v1.0         | [d6f6ee455f](https://linux-hardware.org/?probe=d6f6ee455f) | Mar 23, 2024 |
| Unknown       | Unknown                     | [52255354d1](https://linux-hardware.org/?probe=52255354d1) | Mar 21, 2024 |
| Dell          | 0K240Y A02                  | [8c345dca31](https://linux-hardware.org/?probe=8c345dca31) | Mar 21, 2024 |
| ASRock        | E35LM1                      | [d67fe2fd09](https://linux-hardware.org/?probe=d67fe2fd09) | Mar 21, 2024 |
| Lenovo        | 367D SDK0J40709 WIN         | [178bf2c5e4](https://linux-hardware.org/?probe=178bf2c5e4) | Mar 19, 2024 |
| Dell          | 0D6H9T A01                  | [c3691d0e66](https://linux-hardware.org/?probe=c3691d0e66) | Mar 19, 2024 |
| MSI           | MS-B0A21                    | [e4301d435b](https://linux-hardware.org/?probe=e4301d435b) | Mar 18, 2024 |
| Lenovo        | 3752 NOK                    | [346e8ecb30](https://linux-hardware.org/?probe=346e8ecb30) | Mar 13, 2024 |
| Lenovo        | 3176 SDK0K17763 WIN 1801... | [51143831ed](https://linux-hardware.org/?probe=51143831ed) | Mar 12, 2024 |
| HP            | 2171                        | [83cba3a447](https://linux-hardware.org/?probe=83cba3a447) | Mar 11, 2024 |
| ASUSTek       | PRIME B450M-A II            | [c37a273452](https://linux-hardware.org/?probe=c37a273452) | Mar 11, 2024 |
| ASUSTek       | H110M-K                     | [321f393354](https://linux-hardware.org/?probe=321f393354) | Mar 10, 2024 |
| Intel         | DG31PR AAE39516-300         | [787913150f](https://linux-hardware.org/?probe=787913150f) | Mar 10, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [7bd68b9029](https://linux-hardware.org/?probe=7bd68b9029) | Mar 10, 2024 |
| ASUSTek       | TUF Gaming A520M-PLUS II    | [32f4bd1301](https://linux-hardware.org/?probe=32f4bd1301) | Mar 10, 2024 |
| Unknown       | Intel X79                   | [221191b973](https://linux-hardware.org/?probe=221191b973) | Mar 09, 2024 |
| Gigabyte      | B75-D3V                     | [52cebe0303](https://linux-hardware.org/?probe=52cebe0303) | Mar 08, 2024 |
| ASUSTek       | P7P55D                      | [21057a4ccd](https://linux-hardware.org/?probe=21057a4ccd) | Mar 08, 2024 |
| HP            | 212B                        | [781ec8e8f8](https://linux-hardware.org/?probe=781ec8e8f8) | Mar 07, 2024 |
| Dell          | 0NC2VH A01                  | [3b3cdc41db](https://linux-hardware.org/?probe=3b3cdc41db) | Mar 07, 2024 |
| MSI           | B450 GAMING PRO CARBON A... | [a04cc41ec5](https://linux-hardware.org/?probe=a04cc41ec5) | Mar 07, 2024 |
| Biostar       | H310MHC2                    | [29b173907b](https://linux-hardware.org/?probe=29b173907b) | Mar 06, 2024 |
| MSI           | X570-A PRO                  | [551069870d](https://linux-hardware.org/?probe=551069870d) | Mar 05, 2024 |
| MSI           | B350 PC MATE                | [8e5587f137](https://linux-hardware.org/?probe=8e5587f137) | Mar 05, 2024 |
| Acer          | EQ45LM                      | [876c209627](https://linux-hardware.org/?probe=876c209627) | Mar 04, 2024 |
| ASUSTek       | PRIME B550M-A               | [406bdeb1e8](https://linux-hardware.org/?probe=406bdeb1e8) | Mar 04, 2024 |
| Pegatron      | BYT-X1                      | [2e817a0b80](https://linux-hardware.org/?probe=2e817a0b80) | Mar 03, 2024 |
| ASUSTek       | P5Q                         | [93b54d8b77](https://linux-hardware.org/?probe=93b54d8b77) | Mar 02, 2024 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | [a87711bf87](https://linux-hardware.org/?probe=a87711bf87) | Mar 01, 2024 |
| Fujitsu       | D3432-A1 S26361-D3432-A1    | [cbc637aa6a](https://linux-hardware.org/?probe=cbc637aa6a) | Mar 01, 2024 |
| Lenovo        | 3642 SDK0J40700 WIN 3258... | [29c944d669](https://linux-hardware.org/?probe=29c944d669) | Feb 29, 2024 |
| ASUSTek       | P5LD2                       | [db694867b8](https://linux-hardware.org/?probe=db694867b8) | Feb 25, 2024 |
| ASUSTek       | A88XM-A                     | [0213a33c8b](https://linux-hardware.org/?probe=0213a33c8b) | Feb 25, 2024 |
| ASUSTek       | PRIME B450M-A II            | [2ee09e9d30](https://linux-hardware.org/?probe=2ee09e9d30) | Feb 24, 2024 |
| Dell          | 014GRG A03                  | [17454c7fbf](https://linux-hardware.org/?probe=17454c7fbf) | Feb 22, 2024 |
| ASUSTek       | TUF B450M-PRO GAMING        | [346ff4be29](https://linux-hardware.org/?probe=346ff4be29) | Feb 21, 2024 |
| Gigabyte      | Z390 UD                     | [81ce4601b2](https://linux-hardware.org/?probe=81ce4601b2) | Feb 21, 2024 |
| ASUSTek       | M4N68T-M-LE-V2              | [5ff0972f57](https://linux-hardware.org/?probe=5ff0972f57) | Feb 20, 2024 |
| Acer          | EQ45LM                      | [295ed7c12d](https://linux-hardware.org/?probe=295ed7c12d) | Feb 19, 2024 |
| ASUSTek       | P5KPL-AM EPU                | [2049db8150](https://linux-hardware.org/?probe=2049db8150) | Feb 19, 2024 |
| ASUSTek       | PRIME Z390M-PLUS            | [522f55db74](https://linux-hardware.org/?probe=522f55db74) | Feb 18, 2024 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [93992c9687](https://linux-hardware.org/?probe=93992c9687) | Feb 18, 2024 |
| ASUSTek       | TUF Gaming B760M-PLUS D4    | [f9c4c79116](https://linux-hardware.org/?probe=f9c4c79116) | Feb 18, 2024 |
| ASUSTek       | PRIME X370-PRO              | [98c654fd9c](https://linux-hardware.org/?probe=98c654fd9c) | Feb 18, 2024 |
| ASRock        | 970 Pro3 R2.0               | [bb647c01d4](https://linux-hardware.org/?probe=bb647c01d4) | Feb 18, 2024 |
| HP            | 339B                        | [4f6aa657ef](https://linux-hardware.org/?probe=4f6aa657ef) | Feb 18, 2024 |
| Gigabyte      | Z690 AORUS PRO              | [6b11953f07](https://linux-hardware.org/?probe=6b11953f07) | Feb 18, 2024 |
| HP            | 2215                        | [dcdc271971](https://linux-hardware.org/?probe=dcdc271971) | Feb 18, 2024 |
| HP            | Compaq 6005 Pro SFF PC      | [16de46e6cf](https://linux-hardware.org/?probe=16de46e6cf) | Feb 18, 2024 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [966e0998a7](https://linux-hardware.org/?probe=966e0998a7) | Feb 15, 2024 |
| Gigabyte      | G41MT-ES2L                  | [60cdce8ae3](https://linux-hardware.org/?probe=60cdce8ae3) | Feb 14, 2024 |
| HP            | 8055                        | [c9502cd080](https://linux-hardware.org/?probe=c9502cd080) | Feb 13, 2024 |
| ASUSTek       | P5G41-M LE                  | [bb4aa86fa0](https://linux-hardware.org/?probe=bb4aa86fa0) | Feb 13, 2024 |
| ASUSTek       | P5G41-M LE                  | [16ea131211](https://linux-hardware.org/?probe=16ea131211) | Feb 10, 2024 |
| ASUSTek       | ROG STRIX Z370-I GAMING     | [437af6a442](https://linux-hardware.org/?probe=437af6a442) | Feb 10, 2024 |
| MSI           | B450 GAMING PLUS MAX        | [b60ad9d7c8](https://linux-hardware.org/?probe=b60ad9d7c8) | Feb 09, 2024 |
| ASUSTek       | SABERTOOTH X58              | [2eda41290c](https://linux-hardware.org/?probe=2eda41290c) | Feb 09, 2024 |
| Acer          | EQ45LM                      | [0f040d7ea3](https://linux-hardware.org/?probe=0f040d7ea3) | Feb 09, 2024 |
| HP            | 3646h                       | [458c563fc1](https://linux-hardware.org/?probe=458c563fc1) | Feb 07, 2024 |
| Gigabyte      | F2A55M-S1                   | [527a67ba4f](https://linux-hardware.org/?probe=527a67ba4f) | Feb 07, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [82733ca802](https://linux-hardware.org/?probe=82733ca802) | Feb 05, 2024 |
| MSI           | 2AE0                        | [dd1f107447](https://linux-hardware.org/?probe=dd1f107447) | Feb 04, 2024 |
| Medion        | Z170H4-EA                   | [17c714c6b5](https://linux-hardware.org/?probe=17c714c6b5) | Feb 02, 2024 |
| HP            | 8055                        | [1eec2a37ce](https://linux-hardware.org/?probe=1eec2a37ce) | Feb 02, 2024 |
| Foxconn       | 2ADA                        | [e92639ba10](https://linux-hardware.org/?probe=e92639ba10) | Feb 02, 2024 |
| ASUSTek       | F2A85-M LE                  | [680ba020e2](https://linux-hardware.org/?probe=680ba020e2) | Feb 02, 2024 |
| ASRock        | H77 Pro4-M                  | [794e5341d9](https://linux-hardware.org/?probe=794e5341d9) | Feb 01, 2024 |
| ASRock        | A320M-HDV R4.0              | [9262af6ace](https://linux-hardware.org/?probe=9262af6ace) | Jan 31, 2024 |
| ASUSTek       | P8Z77-V LX                  | [011fd25549](https://linux-hardware.org/?probe=011fd25549) | Jan 31, 2024 |
| Intel         | DH55PJ AAE93812-302         | [acc04ef6ef](https://linux-hardware.org/?probe=acc04ef6ef) | Jan 31, 2024 |
| Biostar       | H610MH                      | [fb0234d450](https://linux-hardware.org/?probe=fb0234d450) | Jan 31, 2024 |
| Biostar       | NF61S-M2A                   | [4b42e5cd37](https://linux-hardware.org/?probe=4b42e5cd37) | Jan 31, 2024 |
| MSI           | PRO X670-P WIFI             | [2640847c88](https://linux-hardware.org/?probe=2640847c88) | Jan 31, 2024 |
| Dell          | 0FM586                      | [a66d080473](https://linux-hardware.org/?probe=a66d080473) | Jan 31, 2024 |
| Acer          | Aspire TC-780               | [00c699c62c](https://linux-hardware.org/?probe=00c699c62c) | Jan 28, 2024 |
| ASRock        | B75M R2.0                   | [7a7e12dca2](https://linux-hardware.org/?probe=7a7e12dca2) | Jan 27, 2024 |
| Gigabyte      | H97-HD3                     | [92984a124e](https://linux-hardware.org/?probe=92984a124e) | Jan 27, 2024 |
| Gigabyte      | H410M H V3                  | [018db3f12a](https://linux-hardware.org/?probe=018db3f12a) | Jan 26, 2024 |
| Gigabyte      | H470M K                     | [644982a46f](https://linux-hardware.org/?probe=644982a46f) | Jan 26, 2024 |
| Gigabyte      | H81M-S1                     | [b727252ca9](https://linux-hardware.org/?probe=b727252ca9) | Jan 25, 2024 |
| Gigabyte      | EG41MF-US2H                 | [882d3605ed](https://linux-hardware.org/?probe=882d3605ed) | Jan 25, 2024 |
| Gigabyte      | GA-78LMT-S2P                | [066f355824](https://linux-hardware.org/?probe=066f355824) | Jan 25, 2024 |
| ASUSTek       | PRIME H510M-E               | [ea518cb09d](https://linux-hardware.org/?probe=ea518cb09d) | Jan 24, 2024 |
| ASRock        | B650M Pro RS                | [2d706981c5](https://linux-hardware.org/?probe=2d706981c5) | Jan 24, 2024 |
| Pegatron      | Benicia                     | [9a4be691fc](https://linux-hardware.org/?probe=9a4be691fc) | Jan 23, 2024 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [f2919e84e4](https://linux-hardware.org/?probe=f2919e84e4) | Jan 22, 2024 |
| HP            | 82B4                        | [0eca4196b3](https://linux-hardware.org/?probe=0eca4196b3) | Jan 21, 2024 |
| ASRock        | FM2A85X-ITX                 | [30f6aa7ead](https://linux-hardware.org/?probe=30f6aa7ead) | Jan 20, 2024 |
| ASUSTek       | H81M-K                      | [5b51e88413](https://linux-hardware.org/?probe=5b51e88413) | Jan 20, 2024 |
| Dell          | 042P49 A01                  | [e164f495e7](https://linux-hardware.org/?probe=e164f495e7) | Jan 19, 2024 |
| Gigabyte      | B460 AORUS PRO AC           | [276a0b5785](https://linux-hardware.org/?probe=276a0b5785) | Jan 19, 2024 |
| HP            | 81B4 01                     | [967d9af55c](https://linux-hardware.org/?probe=967d9af55c) | Jan 19, 2024 |
| Gigabyte      | H610M K DDR4                | [5c9e5ec7aa](https://linux-hardware.org/?probe=5c9e5ec7aa) | Jan 18, 2024 |
| ASUSTek       | TUF Gaming B460-PLUS        | [344b6767cd](https://linux-hardware.org/?probe=344b6767cd) | Jan 17, 2024 |
| MACHINIST     | E5-RS9 V1.11                | [2b48345368](https://linux-hardware.org/?probe=2b48345368) | Jan 17, 2024 |
| Gigabyte      | H61M-S2PV                   | [3baca805c4](https://linux-hardware.org/?probe=3baca805c4) | Jan 17, 2024 |
| EPoX Compu... | NF6100 + NF410 DDR2: MGF... | [ba08d6e05c](https://linux-hardware.org/?probe=ba08d6e05c) | Jan 17, 2024 |
| MSI           | A68HM-E33 V2                | [da97b5c9f5](https://linux-hardware.org/?probe=da97b5c9f5) | Jan 17, 2024 |
| Gigabyte      | EP35-DS3                    | [18f8b43855](https://linux-hardware.org/?probe=18f8b43855) | Jan 16, 2024 |
| ASRock        | Z390 Taichi                 | [84a79a7e97](https://linux-hardware.org/?probe=84a79a7e97) | Jan 16, 2024 |
| ASUSTek       | UN65U                       | [0c9b6c61f2](https://linux-hardware.org/?probe=0c9b6c61f2) | Jan 16, 2024 |
| Gigabyte      | H270M-D3H-CF                | [636ad953ab](https://linux-hardware.org/?probe=636ad953ab) | Jan 16, 2024 |
| ASRock        | H81M-VG4 R2.0               | [4854968095](https://linux-hardware.org/?probe=4854968095) | Jan 15, 2024 |
| ASUSTek       | M5A97 R2.0                  | [122b72e9f2](https://linux-hardware.org/?probe=122b72e9f2) | Jan 15, 2024 |
| Dell          | 0KC9NP A01                  | [71596d8f5f](https://linux-hardware.org/?probe=71596d8f5f) | Jan 12, 2024 |
| ASRock        | H110M-HDV                   | [5f7f485a15](https://linux-hardware.org/?probe=5f7f485a15) | Jan 12, 2024 |
| Gigabyte      | H310M M.2 x.x               | [f67cc2282f](https://linux-hardware.org/?probe=f67cc2282f) | Jan 12, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [febf87bf81](https://linux-hardware.org/?probe=febf87bf81) | Jan 11, 2024 |
| GEEKOM        | Mini IT 8                   | [16b759767e](https://linux-hardware.org/?probe=16b759767e) | Jan 11, 2024 |
| MSI           | Z87I                        | [35114b37dd](https://linux-hardware.org/?probe=35114b37dd) | Jan 10, 2024 |
| Pegatron      | NARRA3                      | [08c60d9c7a](https://linux-hardware.org/?probe=08c60d9c7a) | Jan 10, 2024 |
| ASUSTek       | P8P67 EVO                   | [d54cf27190](https://linux-hardware.org/?probe=d54cf27190) | Jan 09, 2024 |
| Gigabyte      | GA-E350N-USB3               | [222f3e6908](https://linux-hardware.org/?probe=222f3e6908) | Jan 08, 2024 |
| ALDO          | C2016-BSWI-D2               | [1e3d4c2e55](https://linux-hardware.org/?probe=1e3d4c2e55) | Jan 08, 2024 |
| ASUSTek       | A4320A6420                  | [5df0f2025e](https://linux-hardware.org/?probe=5df0f2025e) | Jan 04, 2024 |
| Acer          | Veriton N4620G              | [f438d41562](https://linux-hardware.org/?probe=f438d41562) | Jan 03, 2024 |
| Acer          | WMCP78M                     | [5e254245ae](https://linux-hardware.org/?probe=5e254245ae) | Jan 03, 2024 |
| ASUSTek       | P7P55D                      | [23a30b2497](https://linux-hardware.org/?probe=23a30b2497) | Jan 01, 2024 |
| HP            | 8054                        | [5389720de6](https://linux-hardware.org/?probe=5389720de6) | Dec 31, 2023 |
| HP            | 339A                        | [f109c46a8a](https://linux-hardware.org/?probe=f109c46a8a) | Dec 31, 2023 |
| Dell          | 0GY6Y8 A02                  | [81e91658c9](https://linux-hardware.org/?probe=81e91658c9) | Dec 30, 2023 |
| Intel         | Thurley                     | [2ad7d27607](https://linux-hardware.org/?probe=2ad7d27607) | Dec 29, 2023 |
| HP            | 3029h                       | [de537af4ba](https://linux-hardware.org/?probe=de537af4ba) | Dec 28, 2023 |
| Dell          | 0DF42J A00                  | [2b8f841667](https://linux-hardware.org/?probe=2b8f841667) | Dec 27, 2023 |
| eMachines     | MCP61PM-GM                  | [08b1aaf187](https://linux-hardware.org/?probe=08b1aaf187) | Dec 27, 2023 |
| Lenovo        | Annapurna CRB NO DPK        | [7d003c702a](https://linux-hardware.org/?probe=7d003c702a) | Dec 27, 2023 |
| ASUSTek       | P5K Premium                 | [b1c8bc2127](https://linux-hardware.org/?probe=b1c8bc2127) | Dec 26, 2023 |
| Gigabyte      | GA-880GM-UD2H               | [0516914d99](https://linux-hardware.org/?probe=0516914d99) | Dec 26, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [0535c48b0a](https://linux-hardware.org/?probe=0535c48b0a) | Dec 26, 2023 |
| HP            | 1495                        | [c8b50e17f9](https://linux-hardware.org/?probe=c8b50e17f9) | Dec 26, 2023 |
| Pegatron      | Eureka3                     | [0dfc8b6795](https://linux-hardware.org/?probe=0dfc8b6795) | Dec 25, 2023 |
| ASUSTek       | M5A97 R2.0                  | [5775a72a93](https://linux-hardware.org/?probe=5775a72a93) | Dec 25, 2023 |
| Lenovo        | MAHOBAY NOK                 | [f85a8a3b68](https://linux-hardware.org/?probe=f85a8a3b68) | Dec 25, 2023 |
| ASUSTek       | PRIME H410M-A               | [d6257b5255](https://linux-hardware.org/?probe=d6257b5255) | Dec 25, 2023 |
| Biostar       | A320MH                      | [0898691249](https://linux-hardware.org/?probe=0898691249) | Dec 24, 2023 |
| Lenovo        | ThinkCentre M81 5049RK4     | [9ea1bc22a1](https://linux-hardware.org/?probe=9ea1bc22a1) | Dec 24, 2023 |
| Intel         | H61                         | [a10f481c10](https://linux-hardware.org/?probe=a10f481c10) | Dec 24, 2023 |
| Dell          | 0WMJ54 A01                  | [ac0b6ab055](https://linux-hardware.org/?probe=ac0b6ab055) | Dec 23, 2023 |
| ASUSTek       | P7P55D-E                    | [dc2914021f](https://linux-hardware.org/?probe=dc2914021f) | Dec 23, 2023 |
| HP            | 18E7                        | [71f34bba13](https://linux-hardware.org/?probe=71f34bba13) | Dec 21, 2023 |
| ASUSTek       | PRIME Z690-P                | [72187eb090](https://linux-hardware.org/?probe=72187eb090) | Dec 21, 2023 |
| Intel         | H61                         | [01b739e240](https://linux-hardware.org/?probe=01b739e240) | Dec 20, 2023 |
| Gigabyte      | B450 GAMING X               | [28f3e414e2](https://linux-hardware.org/?probe=28f3e414e2) | Dec 17, 2023 |
| MSI           | MS-7255                     | [efdf3ede47](https://linux-hardware.org/?probe=efdf3ede47) | Dec 17, 2023 |
| Dell          | 053CWD A00                  | [6cee8cbfd7](https://linux-hardware.org/?probe=6cee8cbfd7) | Dec 17, 2023 |
| Gigabyte      | B75M-D3H                    | [f306ab4590](https://linux-hardware.org/?probe=f306ab4590) | Dec 17, 2023 |
| Intel         | H81                         | [9aaa6b2ab6](https://linux-hardware.org/?probe=9aaa6b2ab6) | Dec 16, 2023 |
| Dell          | 0HD5W2 A01                  | [cf61f7b65b](https://linux-hardware.org/?probe=cf61f7b65b) | Dec 16, 2023 |
| HP            | 8653 A                      | [186fc771e8](https://linux-hardware.org/?probe=186fc771e8) | Dec 16, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [45900bcfb2](https://linux-hardware.org/?probe=45900bcfb2) | Dec 16, 2023 |
| Dell          | 0C27VV A02                  | [94560c4ce8](https://linux-hardware.org/?probe=94560c4ce8) | Dec 15, 2023 |
| ASUSTek       | M4A78T-E                    | [f34b148b2e](https://linux-hardware.org/?probe=f34b148b2e) | Dec 14, 2023 |
| HP            | 1496                        | [a89ca6e62d](https://linux-hardware.org/?probe=a89ca6e62d) | Dec 14, 2023 |
| ASUSTek       | P8H61                       | [00f636bb09](https://linux-hardware.org/?probe=00f636bb09) | Dec 14, 2023 |
| HP            | 212B                        | [18d100b09c](https://linux-hardware.org/?probe=18d100b09c) | Dec 14, 2023 |
| ASUSTek       | P9X79-E WS                  | [5dd7c998ce](https://linux-hardware.org/?probe=5dd7c998ce) | Dec 14, 2023 |
| HP            | 18E4                        | [1dd0e805dc](https://linux-hardware.org/?probe=1dd0e805dc) | Dec 13, 2023 |
| Dell          | 0R790T A00                  | [8a72b2a4ce](https://linux-hardware.org/?probe=8a72b2a4ce) | Dec 13, 2023 |
| Dell          | 0HN7XN A00                  | [c85fd96dcb](https://linux-hardware.org/?probe=c85fd96dcb) | Dec 13, 2023 |
| Lenovo        | Unknown                     | [d49ddc416f](https://linux-hardware.org/?probe=d49ddc416f) | Dec 12, 2023 |
| ASRock        | G41M-VS3                    | [894c4cf9fb](https://linux-hardware.org/?probe=894c4cf9fb) | Dec 12, 2023 |
| Unknown       | Unknown                     | [c9eae3e15f](https://linux-hardware.org/?probe=c9eae3e15f) | Dec 12, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | [2a6159034b](https://linux-hardware.org/?probe=2a6159034b) | Dec 12, 2023 |
| MSI           | H61M-E33                    | [6123a79100](https://linux-hardware.org/?probe=6123a79100) | Dec 12, 2023 |
| Gigabyte      | B150M-D3H-CF                | [a46aa4d97c](https://linux-hardware.org/?probe=a46aa4d97c) | Dec 11, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [0343e0a98e](https://linux-hardware.org/?probe=0343e0a98e) | Dec 11, 2023 |
| ASUSTek       | P8Z77-V LX                  | [9e23503add](https://linux-hardware.org/?probe=9e23503add) | Dec 11, 2023 |
| Intel         | DQ57TM AAE70931-402         | [fa57e6edd3](https://linux-hardware.org/?probe=fa57e6edd3) | Dec 10, 2023 |
| HP            | 3032h                       | [ca8902be00](https://linux-hardware.org/?probe=ca8902be00) | Dec 10, 2023 |
| MSI           | 970A-G46                    | [86bd084c44](https://linux-hardware.org/?probe=86bd084c44) | Dec 10, 2023 |
| MSI           | B550-A PRO                  | [43b1cafae8](https://linux-hardware.org/?probe=43b1cafae8) | Dec 10, 2023 |
| ASUSTek       | B150M-A/M.2                 | [dd4ad4373b](https://linux-hardware.org/?probe=dd4ad4373b) | Dec 10, 2023 |
| MSI           | PRO X670-P WIFI             | [be0d6f2f74](https://linux-hardware.org/?probe=be0d6f2f74) | Dec 10, 2023 |
| HP            | 8433 11                     | [65bca719f6](https://linux-hardware.org/?probe=65bca719f6) | Dec 09, 2023 |
| HP            | 0B4Ch D                     | [d129c3b01f](https://linux-hardware.org/?probe=d129c3b01f) | Dec 09, 2023 |
| Intel         | DH61CR AAG14064-204         | [a319465535](https://linux-hardware.org/?probe=a319465535) | Dec 09, 2023 |
| ASUSTek       | F1A55-M LE R2.0             | [83885aa02c](https://linux-hardware.org/?probe=83885aa02c) | Dec 09, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [4202011d88](https://linux-hardware.org/?probe=4202011d88) | Dec 09, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [beb5466523](https://linux-hardware.org/?probe=beb5466523) | Dec 08, 2023 |
| Pegatron      | 3580                        | [580355d3da](https://linux-hardware.org/?probe=580355d3da) | Dec 08, 2023 |
| Dell          | 00V62H A00                  | [f26cee0fe0](https://linux-hardware.org/?probe=f26cee0fe0) | Dec 08, 2023 |
| Intel         | DG965SS AAD41678-304        | [186a397074](https://linux-hardware.org/?probe=186a397074) | Dec 08, 2023 |
| Dell          | 02YYK5 A01                  | [1989264cba](https://linux-hardware.org/?probe=1989264cba) | Dec 08, 2023 |
| Dell          | 0GM819                      | [5c9ffb0977](https://linux-hardware.org/?probe=5c9ffb0977) | Dec 07, 2023 |
| FIC           | K2MCP61P PCB                | [fe4889cc68](https://linux-hardware.org/?probe=fe4889cc68) | Dec 07, 2023 |
| AMI           | Intel                       | [d2e7be0ff3](https://linux-hardware.org/?probe=d2e7be0ff3) | Dec 07, 2023 |
| MSI           | B350M BAZOOKA               | [4b67bc0273](https://linux-hardware.org/?probe=4b67bc0273) | Dec 07, 2023 |
| Dell          | 0YXT71 A03                  | [a3080a2577](https://linux-hardware.org/?probe=a3080a2577) | Dec 06, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | [0ab3c62102](https://linux-hardware.org/?probe=0ab3c62102) | Dec 06, 2023 |
| ASUSTek       | PRIME B550M-A               | [9960314986](https://linux-hardware.org/?probe=9960314986) | Dec 06, 2023 |
| AMI           | Intel                       | [8649d088c6](https://linux-hardware.org/?probe=8649d088c6) | Dec 06, 2023 |
| ASUSTek       | PRIME B250-PLUS             | [8c397afeca](https://linux-hardware.org/?probe=8c397afeca) | Dec 05, 2023 |
| MSI           | 2A9C                        | [2ae992c0d5](https://linux-hardware.org/?probe=2ae992c0d5) | Dec 05, 2023 |
| Gigabyte      | GA-970A-UD3                 | [08a2ed40a1](https://linux-hardware.org/?probe=08a2ed40a1) | Dec 05, 2023 |
| Lenovo        | ThinkCentre M81 0267A38     | [a9f041fc10](https://linux-hardware.org/?probe=a9f041fc10) | Dec 05, 2023 |
| Fujitsu       | JIH61Y3                     | [8aa3f5fa84](https://linux-hardware.org/?probe=8aa3f5fa84) | Dec 05, 2023 |
| Dell          | 0WMJ54 A01                  | [76f6609343](https://linux-hardware.org/?probe=76f6609343) | Dec 05, 2023 |
| Acer          | Aspire XC-704G              | [44c713b05d](https://linux-hardware.org/?probe=44c713b05d) | Dec 05, 2023 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | [d28a7f3ad6](https://linux-hardware.org/?probe=d28a7f3ad6) | Dec 04, 2023 |
| ASUSTek       | Z87M-PLUS                   | [be471e354a](https://linux-hardware.org/?probe=be471e354a) | Dec 04, 2023 |
| ASUSTek       | P5P800-VM                   | [dff0c991af](https://linux-hardware.org/?probe=dff0c991af) | Dec 04, 2023 |
| Lenovo        | 3178 SDK0J40700 WIN 3258... | [e215f304c3](https://linux-hardware.org/?probe=e215f304c3) | Dec 03, 2023 |
| HP            | 1998                        | [14cb2b69d2](https://linux-hardware.org/?probe=14cb2b69d2) | Dec 03, 2023 |
| Gigabyte      | H77-DS3H                    | [4c97431f16](https://linux-hardware.org/?probe=4c97431f16) | Dec 03, 2023 |
| Dell          | 03NVJ6 A02                  | [7f9b2fa7e0](https://linux-hardware.org/?probe=7f9b2fa7e0) | Dec 03, 2023 |
| Dell          | 0C2XKD A01                  | [e946c07f76](https://linux-hardware.org/?probe=e946c07f76) | Dec 03, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [388cf45c84](https://linux-hardware.org/?probe=388cf45c84) | Dec 03, 2023 |
| Acer          | IPXHW-RL                    | [aa0f30e67f](https://linux-hardware.org/?probe=aa0f30e67f) | Dec 02, 2023 |
| HP            | 8299                        | [fb5b226159](https://linux-hardware.org/?probe=fb5b226159) | Dec 02, 2023 |
| Dell          | 07N90W A01                  | [53c34cdf7d](https://linux-hardware.org/?probe=53c34cdf7d) | Dec 02, 2023 |
| MSI           | B350 GAMING PLUS            | [883665fb17](https://linux-hardware.org/?probe=883665fb17) | Dec 02, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [5ea999f7bc](https://linux-hardware.org/?probe=5ea999f7bc) | Dec 02, 2023 |
| Gigabyte      | Z690 UD AX DDR4             | [00159f1b41](https://linux-hardware.org/?probe=00159f1b41) | Dec 01, 2023 |
| ASUSTek       | H97M-E                      | [9e60faee5f](https://linux-hardware.org/?probe=9e60faee5f) | Dec 01, 2023 |
| Intel         | H61 V1.5                    | [45487af3d7](https://linux-hardware.org/?probe=45487af3d7) | Dec 01, 2023 |
| Gigabyte      | GA-870A-UD3                 | [0ae66633bc](https://linux-hardware.org/?probe=0ae66633bc) | Dec 01, 2023 |
| Gigabyte      | B460M D3H                   | [b83f7a31ff](https://linux-hardware.org/?probe=b83f7a31ff) | Dec 01, 2023 |
| ASRock        | H310CM-HDV/M.2              | [4b91971e62](https://linux-hardware.org/?probe=4b91971e62) | Dec 01, 2023 |
| Dell          | 014GRG A03                  | [581d6ec42f](https://linux-hardware.org/?probe=581d6ec42f) | Nov 30, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [aa1896b627](https://linux-hardware.org/?probe=aa1896b627) | Nov 30, 2023 |
| Dell          | 0WK833                      | [f363206bab](https://linux-hardware.org/?probe=f363206bab) | Nov 30, 2023 |
| MSI           | A88X-G45 GAMING             | [c3ad03c61d](https://linux-hardware.org/?probe=c3ad03c61d) | Nov 30, 2023 |
| Gigabyte      | A320M-S2H-CF                | [5cfd0eb0f5](https://linux-hardware.org/?probe=5cfd0eb0f5) | Nov 30, 2023 |
| HP            | 843B                        | [5a69492f49](https://linux-hardware.org/?probe=5a69492f49) | Nov 30, 2023 |
| ASRock        | B450 Pro4 R2.0              | [53fc7f6723](https://linux-hardware.org/?probe=53fc7f6723) | Nov 30, 2023 |
| ASUSTek       | PRIME B550-PLUS AC-HES      | [4747b76126](https://linux-hardware.org/?probe=4747b76126) | Nov 30, 2023 |
| Gigabyte      | A320M-S2H-CF                | [01105932ac](https://linux-hardware.org/?probe=01105932ac) | Nov 30, 2023 |
| MSI           | B250M PRO-VD                | [e0dead14ab](https://linux-hardware.org/?probe=e0dead14ab) | Nov 29, 2023 |
| Gigabyte      | GA-A55M-DS2                 | [bf1caf0dae](https://linux-hardware.org/?probe=bf1caf0dae) | Nov 29, 2023 |
| HP            | 8298                        | [f66cb29dd1](https://linux-hardware.org/?probe=f66cb29dd1) | Nov 29, 2023 |
| Unknown       | N15                         | [a968ec315f](https://linux-hardware.org/?probe=a968ec315f) | Nov 29, 2023 |
| ASRock        | J3355M                      | [a767ff37ed](https://linux-hardware.org/?probe=a767ff37ed) | Nov 29, 2023 |
| ASUSTek       | PRIME A520M-K               | [cd63a4710a](https://linux-hardware.org/?probe=cd63a4710a) | Nov 29, 2023 |
| Lenovo        | 317E SDK0K17763 WIN 1801... | [8bc25c47be](https://linux-hardware.org/?probe=8bc25c47be) | Nov 29, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [655dc71f64](https://linux-hardware.org/?probe=655dc71f64) | Nov 29, 2023 |
| Acer          | Aspire TC-885 V:1.1         | [a97b3bd106](https://linux-hardware.org/?probe=a97b3bd106) | Nov 29, 2023 |
| HP            | 805D                        | [997f828456](https://linux-hardware.org/?probe=997f828456) | Nov 29, 2023 |
| MSI           | Z170A PC MATE               | [913553eac4](https://linux-hardware.org/?probe=913553eac4) | Nov 29, 2023 |
| Red Hat       | RHEL RHEL-9.2.0 PC          | [c70f79dd89](https://linux-hardware.org/?probe=c70f79dd89) | Nov 29, 2023 |
| Gigabyte      | H310M S2                    | [4cd53ef516](https://linux-hardware.org/?probe=4cd53ef516) | Nov 29, 2023 |
| Founder       | Q87H3-AM V:1.0              | [56a7ef0f8a](https://linux-hardware.org/?probe=56a7ef0f8a) | Nov 29, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [bd474c263c](https://linux-hardware.org/?probe=bd474c263c) | Nov 29, 2023 |
| HP            | 8648                        | [f6804eecf5](https://linux-hardware.org/?probe=f6804eecf5) | Nov 29, 2023 |
| HP            | 8906 SMVB                   | [a94fe27744](https://linux-hardware.org/?probe=a94fe27744) | Nov 28, 2023 |
| MSI           | KA790GX                     | [5bc35f82f6](https://linux-hardware.org/?probe=5bc35f82f6) | Nov 28, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [c93b09ccf3](https://linux-hardware.org/?probe=c93b09ccf3) | Nov 28, 2023 |
| Unknown       | Unknown                     | [b4e8fd1ac2](https://linux-hardware.org/?probe=b4e8fd1ac2) | Nov 28, 2023 |
| Dell          | 0HD5W2 A01                  | [2627da2538](https://linux-hardware.org/?probe=2627da2538) | Nov 28, 2023 |
| HP            | 304Bh                       | [3cb20d232f](https://linux-hardware.org/?probe=3cb20d232f) | Nov 28, 2023 |
| ECS           | G31T-M9                     | [535a19c400](https://linux-hardware.org/?probe=535a19c400) | Nov 28, 2023 |
| Lenovo        | SDK0F82993 WIN              | [d9bc93a89f](https://linux-hardware.org/?probe=d9bc93a89f) | Nov 28, 2023 |
| Gigabyte      | 945GZM-S2                   | [0a673a3528](https://linux-hardware.org/?probe=0a673a3528) | Nov 28, 2023 |
| Dell          | 0T7D40 A01                  | [6c16a6716b](https://linux-hardware.org/?probe=6c16a6716b) | Nov 28, 2023 |
| Medion        | MS-7621                     | [18f32a871d](https://linux-hardware.org/?probe=18f32a871d) | Nov 28, 2023 |
| ASRock        | H81M-DGS R2.0               | [2196f5ec5e](https://linux-hardware.org/?probe=2196f5ec5e) | Nov 28, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [2df2a6f5d8](https://linux-hardware.org/?probe=2df2a6f5d8) | Nov 28, 2023 |
| Dell          | 07KY25 A01                  | [f1905255d0](https://linux-hardware.org/?probe=f1905255d0) | Nov 28, 2023 |
| Dell          | 03NVJ6 A03                  | [2eae8e704b](https://linux-hardware.org/?probe=2eae8e704b) | Nov 28, 2023 |
| ASUSTek       | Z170-A                      | [d4488776c4](https://linux-hardware.org/?probe=d4488776c4) | Nov 27, 2023 |
| ASUSTek       | CM1435                      | [deceba2322](https://linux-hardware.org/?probe=deceba2322) | Nov 27, 2023 |
| ASUSTek       | F2A85-M                     | [0c272521ab](https://linux-hardware.org/?probe=0c272521ab) | Nov 27, 2023 |
| Acer          | Veriton X2632G V:1.0        | [0c50fc3c6f](https://linux-hardware.org/?probe=0c50fc3c6f) | Nov 27, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [a82d950345](https://linux-hardware.org/?probe=a82d950345) | Nov 27, 2023 |
| ASUSTek       | A68HM-PLUS                  | [d848c8ed0e](https://linux-hardware.org/?probe=d848c8ed0e) | Nov 27, 2023 |
| ASRock        | H61M-VG3                    | [8b7f6c2f5f](https://linux-hardware.org/?probe=8b7f6c2f5f) | Nov 27, 2023 |
| Foxconn       | H67MP-S/-V/H67MP            | [c5f3edc9d1](https://linux-hardware.org/?probe=c5f3edc9d1) | Nov 27, 2023 |
| ASUSTek       | PRIME X370-PRO              | [cd7362b85e](https://linux-hardware.org/?probe=cd7362b85e) | Nov 27, 2023 |
| Dell          | 0F3KHR A00                  | [c744967be3](https://linux-hardware.org/?probe=c744967be3) | Nov 27, 2023 |
| ASUSTek       | PRIME A320M-K               | [ee22e39495](https://linux-hardware.org/?probe=ee22e39495) | Nov 27, 2023 |
| Gigabyte      | B75M-D3V                    | [142a3240d4](https://linux-hardware.org/?probe=142a3240d4) | Nov 27, 2023 |
| Foxconn       | 2ABF                        | [a5016a519f](https://linux-hardware.org/?probe=a5016a519f) | Nov 27, 2023 |
| ASUSTek       | H81M-K                      | [121db7e081](https://linux-hardware.org/?probe=121db7e081) | Nov 27, 2023 |
| HP            | 8056                        | [9972a0e20f](https://linux-hardware.org/?probe=9972a0e20f) | Nov 27, 2023 |
| HP            | 8184 X4                     | [0813228fc1](https://linux-hardware.org/?probe=0813228fc1) | Nov 27, 2023 |
| Gigabyte      | G31M-ES2L                   | [f3e5b85b92](https://linux-hardware.org/?probe=f3e5b85b92) | Nov 27, 2023 |
| ASUSTek       | PRIME J4005I-C              | [23f26e0c45](https://linux-hardware.org/?probe=23f26e0c45) | Nov 27, 2023 |
| Dell          | 00VTMF A01                  | [bb1a93e07b](https://linux-hardware.org/?probe=bb1a93e07b) | Nov 27, 2023 |
| HP            | 82F2 A01                    | [21ece36869](https://linux-hardware.org/?probe=21ece36869) | Nov 27, 2023 |
| HP            | 2AF7                        | [a366a85d8c](https://linux-hardware.org/?probe=a366a85d8c) | Nov 27, 2023 |
| AZW           | MINI S 10                   | [c0fda6103a](https://linux-hardware.org/?probe=c0fda6103a) | Nov 26, 2023 |
| Dell          | 0YP806 A01                  | [078d014e70](https://linux-hardware.org/?probe=078d014e70) | Nov 26, 2023 |
| ASRock        | B550M-ITX/ac                | [c28cfb7cd7](https://linux-hardware.org/?probe=c28cfb7cd7) | Nov 26, 2023 |
| HP            | 8704                        | [594422dbde](https://linux-hardware.org/?probe=594422dbde) | Nov 26, 2023 |
| HP            | 1497                        | [5922e57d93](https://linux-hardware.org/?probe=5922e57d93) | Nov 26, 2023 |
| Gigabyte      | P55-US3L                    | [fdb0f32546](https://linux-hardware.org/?probe=fdb0f32546) | Nov 26, 2023 |
| Gigabyte      | G41M-ES2L                   | [f2856297d6](https://linux-hardware.org/?probe=f2856297d6) | Nov 26, 2023 |
| Shenzhen M... | F7BAA                       | [a48bfbc481](https://linux-hardware.org/?probe=a48bfbc481) | Nov 26, 2023 |
| Dell          | 0200DY A02                  | [7d5df62892](https://linux-hardware.org/?probe=7d5df62892) | Nov 26, 2023 |
| MSI           | A68HM-E33 V2                | [9247159905](https://linux-hardware.org/?probe=9247159905) | Nov 26, 2023 |
| HP            | 0B54h D                     | [0fccef5d79](https://linux-hardware.org/?probe=0fccef5d79) | Nov 26, 2023 |
| Gigabyte      | B450M DS3H-CF               | [4552c13bb1](https://linux-hardware.org/?probe=4552c13bb1) | Nov 26, 2023 |
| Acer          | Veriton M290                | [30dd8ffe84](https://linux-hardware.org/?probe=30dd8ffe84) | Nov 26, 2023 |
| ASUSTek       | PRIME Z490-P                | [b25d830579](https://linux-hardware.org/?probe=b25d830579) | Nov 26, 2023 |
| ASRock        | G41M-GS3                    | [0e679ecab4](https://linux-hardware.org/?probe=0e679ecab4) | Nov 26, 2023 |
| HP            | 8055                        | [88122b7512](https://linux-hardware.org/?probe=88122b7512) | Nov 26, 2023 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | [d384af59f3](https://linux-hardware.org/?probe=d384af59f3) | Nov 26, 2023 |
| Huanan        | X99-BD4 V1.1, NALEX         | [751dbeae2c](https://linux-hardware.org/?probe=751dbeae2c) | Nov 26, 2023 |
| Medion        | MS-7728                     | [1e13c1a36d](https://linux-hardware.org/?probe=1e13c1a36d) | Nov 26, 2023 |
| Red Hat       | RHEL RHEL-9.2.0 PC          | [33dabf03ca](https://linux-hardware.org/?probe=33dabf03ca) | Nov 26, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [66dac22b5a](https://linux-hardware.org/?probe=66dac22b5a) | Nov 26, 2023 |
| HP            | 3397                        | [a846952acf](https://linux-hardware.org/?probe=a846952acf) | Nov 26, 2023 |
| MSI           | H310M PRO-VH PLUS           | [f21d57f728](https://linux-hardware.org/?probe=f21d57f728) | Nov 26, 2023 |
| Acer          | Aspire X1920                | [c97acbf5df](https://linux-hardware.org/?probe=c97acbf5df) | Nov 26, 2023 |
| Biostar       | H61MLV2                     | [1e2b4c3878](https://linux-hardware.org/?probe=1e2b4c3878) | Nov 26, 2023 |
| ASUSTek       | PRIME A320M-K               | [aa7fb6a279](https://linux-hardware.org/?probe=aa7fb6a279) | Nov 26, 2023 |
| ASUSTek       | A55BM-E                     | [28fe1a1fe1](https://linux-hardware.org/?probe=28fe1a1fe1) | Nov 26, 2023 |
| Gigabyte      | B560M DS3H AC               | [906f471cf6](https://linux-hardware.org/?probe=906f471cf6) | Nov 26, 2023 |
| HP            | 339A                        | [5cad333081](https://linux-hardware.org/?probe=5cad333081) | Nov 26, 2023 |
| Gigabyte      | Z370 HD3-CF                 | [4f4c868c9a](https://linux-hardware.org/?probe=4f4c868c9a) | Nov 26, 2023 |
| ASUSTek       | PRIME B760M-A D4            | [ef4ad69c79](https://linux-hardware.org/?probe=ef4ad69c79) | Nov 26, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [6cdf6e663e](https://linux-hardware.org/?probe=6cdf6e663e) | Nov 26, 2023 |
| Intel         | H61 V124A                   | [eaa125b476](https://linux-hardware.org/?probe=eaa125b476) | Nov 26, 2023 |
| Gigabyte      | AM1M-S2H                    | [c3bdc08988](https://linux-hardware.org/?probe=c3bdc08988) | Nov 26, 2023 |
| ASUSTek       | PRIME B550M-A               | [15da0b054a](https://linux-hardware.org/?probe=15da0b054a) | Nov 26, 2023 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | [1f874b5293](https://linux-hardware.org/?probe=1f874b5293) | Nov 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | [a3f4bbe816](https://linux-hardware.org/?probe=a3f4bbe816) | Nov 25, 2023 |
| Gigabyte      | Z390 GAMING X-CF            | [5c990c2d29](https://linux-hardware.org/?probe=5c990c2d29) | Nov 25, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | [af8e097b69](https://linux-hardware.org/?probe=af8e097b69) | Nov 25, 2023 |
| ASUSTek       | PRIME A520M-K               | [7514ce50b9](https://linux-hardware.org/?probe=7514ce50b9) | Nov 25, 2023 |
| ASRock        | H470M-ITX/ac                | [5b558c30c8](https://linux-hardware.org/?probe=5b558c30c8) | Nov 25, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [9c4c337fe9](https://linux-hardware.org/?probe=9c4c337fe9) | Nov 25, 2023 |
| ASRock        | FM2A88X Extreme6+           | [381486f3da](https://linux-hardware.org/?probe=381486f3da) | Nov 25, 2023 |
| MSI           | PRO B760M-P DDR4            | [462b5c65a7](https://linux-hardware.org/?probe=462b5c65a7) | Nov 25, 2023 |
| HP            | 339A                        | [35c70dde9e](https://linux-hardware.org/?probe=35c70dde9e) | Nov 25, 2023 |
| ASRock        | B550M-ITX/ac                | [fd893be7c7](https://linux-hardware.org/?probe=fd893be7c7) | Nov 25, 2023 |
| Dell          | OptiPlex 745                | [1abbad3f94](https://linux-hardware.org/?probe=1abbad3f94) | Nov 23, 2023 |
| Gigabyte      | B85M-HD3                    | [5992237ea5](https://linux-hardware.org/?probe=5992237ea5) | Nov 15, 2023 |
| MSI           | A520M PRO                   | [b83b272494](https://linux-hardware.org/?probe=b83b272494) | Nov 06, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva_5.0/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Desktops | Percent |
|--------------------------------|----------|---------|
| 6.6.2-desktop-1omv2390         | 606      | 98.54%  |
| 6.6.1-desktop-1omv2390         | 3        | 0.49%   |
| 6.7.0-desktop-0.rc2.1omv2390   | 2        | 0.33%   |
| 6.6.2-desktop-gcc-1omv2390     | 1        | 0.16%   |
| 6.6.0-desktop-1omv2390         | 1        | 0.16%   |
| 5.16.13-desktop-clang-1omv4003 | 1        | 0.16%   |
| 5.16.13-desktop-1omv4003       | 1        | 0.16%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.6.2   | 607      | 98.7%   |
| 6.6.1   | 3        | 0.49%   |
| 6.7.0   | 2        | 0.33%   |
| 5.16.13 | 2        | 0.33%   |
| 6.6.0   | 1        | 0.16%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.6     | 611      | 99.35%  |
| 6.7     | 2        | 0.33%   |
| 5.16    | 2        | 0.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 615      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| KDE5     | 441      | 71.71%  |
| LXQt     | 121      | 19.67%  |
| GNOME    | 49       | 7.97%   |
| Cinnamon | 2        | 0.33%   |
| Budgie   | 1        | 0.16%   |
| Unknown  | 1        | 0.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 595      | 96.75%  |
| X11     | 20       | 3.25%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 565      | 91.87%  |
| GDM     | 49       | 7.97%   |
| LightDM | 1        | 0.16%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 320      | 52.03%  |
| ru_RU | 50       | 8.13%   |
| de_DE | 39       | 6.34%   |
| pl_PL | 38       | 6.18%   |
| fr_FR | 26       | 4.23%   |
| it_IT | 23       | 3.74%   |
| en_GB | 18       | 2.93%   |
| pt_BR | 13       | 2.11%   |
| es_ES | 11       | 1.79%   |
| fr_CA | 7        | 1.14%   |
| es_MX | 6        | 0.98%   |
| en_CA | 6        | 0.98%   |
| en_AU | 6        | 0.98%   |
| es_AR | 5        | 0.81%   |
| en_IN | 4        | 0.65%   |
| en_IL | 4        | 0.65%   |
| de_AT | 4        | 0.65%   |
| ja_JP | 3        | 0.49%   |
| hu_HU | 3        | 0.49%   |
| UTF-8 | 2        | 0.33%   |
| ru_UA | 2        | 0.33%   |
| nl_NL | 2        | 0.33%   |
| nl_BE | 2        | 0.33%   |
| nb_NO | 2        | 0.33%   |
| en_ZA | 2        | 0.33%   |
| de_CH | 2        | 0.33%   |
| cs_CZ | 2        | 0.33%   |
| tr_TR | 1        | 0.16%   |
| ro_RO | 1        | 0.16%   |
| pt_PT | 1        | 0.16%   |
| fr_CH | 1        | 0.16%   |
| fr_BE | 1        | 0.16%   |
| es_VE | 1        | 0.16%   |
| es_HN | 1        | 0.16%   |
| es_EC | 1        | 0.16%   |
| es_DO | 1        | 0.16%   |
| es_CR | 1        | 0.16%   |
| es_CO | 1        | 0.16%   |
| en_SG | 1        | 0.16%   |
| en_NZ | 1        | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 326      | 53.01%  |
| BIOS | 289      | 46.99%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Overlay | 330      | 53.57%  |
| Ext4    | 266      | 43.18%  |
| Btrfs   | 12       | 1.95%   |
| Xfs     | 5        | 0.81%   |
| F2fs    | 2        | 0.32%   |
| Ext3    | 1        | 0.16%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 471      | 76.59%  |
| MBR  | 144      | 23.41%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 333      | 54.06%  |
| No        | 283      | 45.94%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 332      | 53.81%  |
| Yes       | 285      | 46.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 137      | 22.28%  |
| Gigabyte Technology                  | 108      | 17.56%  |
| Dell                                 | 60       | 9.76%   |
| MSI                                  | 59       | 9.59%   |
| Hewlett-Packard                      | 59       | 9.59%   |
| ASRock                               | 47       | 7.64%   |
| Acer                                 | 25       | 4.07%   |
| Lenovo                               | 22       | 3.58%   |
| Intel                                | 19       | 3.09%   |
| Fujitsu                              | 12       | 1.95%   |
| Unknown                              | 11       | 1.79%   |
| Biostar                              | 7        | 1.14%   |
| Pegatron                             | 5        | 0.81%   |
| Foxconn                              | 4        | 0.65%   |
| Medion                               | 3        | 0.49%   |
| Shenzhen Meigao Electronic Equipment | 2        | 0.33%   |
| Red Hat                              | 2        | 0.33%   |
| OEM                                  | 2        | 0.33%   |
| MouseComputer                        | 2        | 0.33%   |
| MAXSUN                               | 2        | 0.33%   |
| MACHINIST                            | 2        | 0.33%   |
| AMI                                  | 2        | 0.33%   |
| Wistron                              | 1        | 0.16%   |
| TYAN Computer                        | 1        | 0.16%   |
| SZMZ                                 | 1        | 0.16%   |
| Supermicro                           | 1        | 0.16%   |
| Radiant Systems                      | 1        | 0.16%   |
| Packard Bell                         | 1        | 0.16%   |
| Lenovo Product                       | 1        | 0.16%   |
| Huanan                               | 1        | 0.16%   |
| GEEKOM                               | 1        | 0.16%   |
| Gateway                              | 1        | 0.16%   |
| Founder                              | 1        | 0.16%   |
| Firebat_Computer                     | 1        | 0.16%   |
| FIC                                  | 1        | 0.16%   |
| EPoX Computer                        | 1        | 0.16%   |
| eMachines                            | 1        | 0.16%   |
| ECS                                  | 1        | 0.16%   |
| DFI                                  | 1        | 0.16%   |
| Daten Tecnologia                     | 1        | 0.16%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Unknown                        | 12       | 1.95%   |
| ASUS All Series                | 8        | 1.3%    |
| Dell OptiPlex 7010             | 6        | 0.98%   |
| Dell OptiPlex 9020             | 5        | 0.81%   |
| Dell OptiPlex 3020             | 5        | 0.81%   |
| ASUS PRIME A320M-K             | 5        | 0.81%   |
| Intel H61                      | 4        | 0.65%   |
| Dell OptiPlex 780              | 4        | 0.65%   |
| Dell OptiPlex 7040             | 4        | 0.65%   |
| ASUS PRIME B550M-A             | 4        | 0.65%   |
| ASUS P8Z77-V LX                | 4        | 0.65%   |
| Acer Veriton L670G             | 4        | 0.65%   |
| MSI MS-7A38                    | 3        | 0.49%   |
| MSI MS-7721                    | 3        | 0.49%   |
| HP Z440 Workstation            | 3        | 0.49%   |
| HP EliteDesk 800 G2 SFF        | 3        | 0.49%   |
| HP EliteDesk 800 G2 DM 35W     | 3        | 0.49%   |
| HP Compaq Pro 6300 MT          | 3        | 0.49%   |
| Gigabyte B450M DS3H V2         | 3        | 0.49%   |
| Dell OptiPlex 755              | 3        | 0.49%   |
| ASUS PRIME Z390M-PLUS          | 3        | 0.49%   |
| ASUS P5G41-M LE                | 3        | 0.49%   |
| ASRock FM2A88X Extreme6+       | 3        | 0.49%   |
| Red Hat KVM                    | 2        | 0.33%   |
| MSI MS-7D77                    | 2        | 0.33%   |
| MSI MS-7D67                    | 2        | 0.33%   |
| MSI MS-7C52                    | 2        | 0.33%   |
| MSI MS-7C37                    | 2        | 0.33%   |
| MSI MS-7B89                    | 2        | 0.33%   |
| MSI MS-7B85                    | 2        | 0.33%   |
| MSI MS-7A34                    | 2        | 0.33%   |
| MSI MS-7817                    | 2        | 0.33%   |
| Lenovo ThinkCentre M57 6069Y4H | 2        | 0.33%   |
| Intel H81                      | 2        | 0.33%   |
| HP Z600 Workstation            | 2        | 0.33%   |
| HP ProDesk 600 G2 SFF          | 2        | 0.33%   |
| HP Pavilion Desktop 590-p0xxx  | 2        | 0.33%   |
| HP EliteDesk 800 G3 SFF        | 2        | 0.33%   |
| HP EliteDesk 800 G1 SFF        | 2        | 0.33%   |
| HP Compaq Pro 6300 SFF         | 2        | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Dell OptiPlex      | 48       | 7.8%    |
| ASUS PRIME         | 38       | 6.18%   |
| HP Compaq          | 17       | 2.76%   |
| HP EliteDesk       | 14       | 2.28%   |
| ASUS ROG           | 14       | 2.28%   |
| Unknown            | 12       | 1.95%   |
| Lenovo ThinkCentre | 11       | 1.79%   |
| Acer Aspire        | 11       | 1.79%   |
| Acer Veriton       | 10       | 1.63%   |
| HP ProDesk         | 9        | 1.46%   |
| Fujitsu ESPRIMO    | 9        | 1.46%   |
| ASUS TUF           | 8        | 1.3%    |
| ASUS All           | 8        | 1.3%    |
| Intel H61          | 6        | 0.98%   |
| HP Pavilion        | 5        | 0.81%   |
| Gigabyte B450M     | 5        | 0.81%   |
| Dell Inspiron      | 5        | 0.81%   |
| ASUS M5A78L-M      | 5        | 0.81%   |
| Gigabyte B450      | 4        | 0.65%   |
| ASUS P8Z77-V       | 4        | 0.65%   |
| MSI MS-7A38        | 3        | 0.49%   |
| MSI MS-7721        | 3        | 0.49%   |
| Lenovo IdeaCentre  | 3        | 0.49%   |
| HP Z440            | 3        | 0.49%   |
| Gigabyte Z390      | 3        | 0.49%   |
| Gigabyte X570      | 3        | 0.49%   |
| Gigabyte B560M     | 3        | 0.49%   |
| Dell Vostro        | 3        | 0.49%   |
| Dell Precision     | 3        | 0.49%   |
| ASUS P5G41-M       | 3        | 0.49%   |
| ASRock FM2A88X     | 3        | 0.49%   |
| Red Hat KVM        | 2        | 0.33%   |
| MSI Pro            | 2        | 0.33%   |
| MSI MS-7D77        | 2        | 0.33%   |
| MSI MS-7D67        | 2        | 0.33%   |
| MSI MS-7C52        | 2        | 0.33%   |
| MSI MS-7C37        | 2        | 0.33%   |
| MSI MS-7B89        | 2        | 0.33%   |
| MSI MS-7B85        | 2        | 0.33%   |
| MSI MS-7A34        | 2        | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 57       | 9.27%   |
| 2013 | 56       | 9.11%   |
| 2018 | 55       | 8.94%   |
| 2014 | 45       | 7.32%   |
| 2015 | 44       | 7.15%   |
| 2020 | 39       | 6.34%   |
| 2017 | 39       | 6.34%   |
| 2011 | 37       | 6.02%   |
| 2021 | 35       | 5.69%   |
| 2009 | 35       | 5.69%   |
| 2010 | 27       | 4.39%   |
| 2016 | 24       | 3.9%    |
| 2019 | 23       | 3.74%   |
| 2023 | 22       | 3.58%   |
| 2022 | 22       | 3.58%   |
| 2008 | 22       | 3.58%   |
| 2007 | 14       | 2.28%   |
| 2006 | 11       | 1.79%   |
| 2024 | 5        | 0.81%   |
| 2005 | 3        | 0.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 615      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 615      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 615      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 146      | 23.7%   |
| 8.01-16.0   | 138      | 22.4%   |
| 4.01-8.0    | 127      | 20.62%  |
| 3.01-4.0    | 95       | 15.42%  |
| 32.01-64.0  | 68       | 11.04%  |
| 24.01-32.0  | 16       | 2.6%    |
| 64.01-256.0 | 11       | 1.79%   |
| 1.01-2.0    | 9        | 1.46%   |
| 2.01-3.0    | 5        | 0.81%   |
| 0.51-1.0    | 1        | 0.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1.01-2.0 | 372      | 60%     |
| 2.01-3.0 | 115      | 18.55%  |
| 0.51-1.0 | 105      | 16.94%  |
| 0.01-0.5 | 12       | 1.94%   |
| 3.01-4.0 | 11       | 1.77%   |
| 4.01-8.0 | 5        | 0.81%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 291      | 47.09%  |
| 2      | 151      | 24.43%  |
| 3      | 91       | 14.72%  |
| 4      | 36       | 5.83%   |
| 5      | 16       | 2.59%   |
| 0      | 13       | 2.1%    |
| 6      | 9        | 1.46%   |
| 7      | 6        | 0.97%   |
| 9      | 3        | 0.49%   |
| 13     | 1        | 0.16%   |
| 8      | 1        | 0.16%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 338      | 54.78%  |
| No        | 279      | 45.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 603      | 98.05%  |
| No        | 12       | 1.95%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 371      | 60.13%  |
| Yes       | 246      | 39.87%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 443      | 72.03%  |
| Yes       | 172      | 27.97%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 91       | 14.8%   |
| Russia       | 78       | 12.68%  |
| Poland       | 60       | 9.76%   |
| Germany      | 51       | 8.29%   |
| France       | 33       | 5.37%   |
| Italy        | 32       | 5.2%    |
| Brazil       | 24       | 3.9%    |
| UK           | 23       | 3.74%   |
| Canada       | 22       | 3.58%   |
| Spain        | 12       | 1.95%   |
| Romania      | 11       | 1.79%   |
| Australia    | 11       | 1.79%   |
| Hungary      | 10       | 1.63%   |
| China        | 9        | 1.46%   |
| Argentina    | 9        | 1.46%   |
| Sweden       | 8        | 1.3%    |
| Japan        | 8        | 1.3%    |
| Mexico       | 7        | 1.14%   |
| Israel       | 6        | 0.98%   |
| Indonesia    | 6        | 0.98%   |
| Belgium      | 6        | 0.98%   |
| Netherlands  | 5        | 0.81%   |
| India        | 5        | 0.81%   |
| Greece       | 5        | 0.81%   |
| Ukraine      | 4        | 0.65%   |
| Turkey       | 4        | 0.65%   |
| New Zealand  | 4        | 0.65%   |
| Czechia      | 4        | 0.65%   |
| Thailand     | 3        | 0.49%   |
| Switzerland  | 3        | 0.49%   |
| South Africa | 3        | 0.49%   |
| Singapore    | 3        | 0.49%   |
| Serbia       | 3        | 0.49%   |
| Malaysia     | 3        | 0.49%   |
| Kazakhstan   | 3        | 0.49%   |
| Austria      | 3        | 0.49%   |
| Uruguay      | 2        | 0.33%   |
| South Korea  | 2        | 0.33%   |
| Slovakia     | 2        | 0.33%   |
| Philippines  | 2        | 0.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Moscow         | 16       | 2.59%   |
| Warsaw         | 10       | 1.62%   |
| St Petersburg  | 7        | 1.13%   |
| Citrus Heights | 6        | 0.97%   |
| Wroclaw        | 5        | 0.81%   |
| Toulouse       | 5        | 0.81%   |
| Rio de Janeiro | 5        | 0.81%   |
| Berlin         | 5        | 0.81%   |
| Tucson         | 4        | 0.65%   |
| Tel Aviv       | 4        | 0.65%   |
| Târgu Mureş  | 4        | 0.65%   |
| Rostov-on-Don  | 4        | 0.65%   |
| Rome           | 4        | 0.65%   |
| Novosibirsk    | 4        | 0.65%   |
| Montreal       | 4        | 0.65%   |
| Ulyanovsk      | 3        | 0.49%   |
| Sydney         | 3        | 0.49%   |
| Singapore      | 3        | 0.49%   |
| Sao Paulo      | 3        | 0.49%   |
| Poznan         | 3        | 0.49%   |
| Paris          | 3        | 0.49%   |
| Munich         | 3        | 0.49%   |
| Milan          | 3        | 0.49%   |
| Madrid         | 3        | 0.49%   |
| Kronberg       | 3        | 0.49%   |
| Krasnodar      | 3        | 0.49%   |
| Hemet          | 3        | 0.49%   |
| Heemskerk      | 3        | 0.49%   |
| Christchurch   | 3        | 0.49%   |
| Almaty         | 3        | 0.49%   |
| Wiesloch       | 2        | 0.32%   |
| Volgograd      | 2        | 0.32%   |
| Verona         | 2        | 0.32%   |
| Szczecin       | 2        | 0.32%   |
| Spring Valley  | 2        | 0.32%   |
| Saratov        | 2        | 0.32%   |
| Santiago       | 2        | 0.32%   |
| Samara         | 2        | 0.32%   |
| Portland       | 2        | 0.32%   |
| Perm           | 2        | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 184      | 226    | 17.23%  |
| Seagate                     | 167      | 222    | 15.64%  |
| Samsung Electronics         | 100      | 119    | 9.36%   |
| Kingston                    | 80       | 88     | 7.49%   |
| Toshiba                     | 57       | 63     | 5.34%   |
| Crucial                     | 43       | 48     | 4.03%   |
| SanDisk                     | 37       | 42     | 3.46%   |
| Hitachi                     | 35       | 39     | 3.28%   |
| China                       | 27       | 29     | 2.53%   |
| A-DATA Technology           | 24       | 26     | 2.25%   |
| GOODRAM                     | 20       | 21     | 1.87%   |
| Intel                       | 19       | 19     | 1.78%   |
| Patriot                     | 18       | 20     | 1.69%   |
| Intenso                     | 17       | 19     | 1.59%   |
| Unknown                     | 16       | 16     | 1.5%    |
| SPCC                        | 16       | 20     | 1.5%    |
| JMicron Technology          | 11       | 11     | 1.03%   |
| PNY                         | 9        | 10     | 0.84%   |
| HGST                        | 9        | 9      | 0.84%   |
| SK hynix                    | 8        | 9      | 0.75%   |
| Maxtor                      | 6        | 6      | 0.56%   |
| Unknown                     | 6        | 6      | 0.56%   |
| Netac                       | 5        | 5      | 0.47%   |
| Micron Technology           | 5        | 6      | 0.47%   |
| Lexar                       | 5        | 5      | 0.47%   |
| HPQ                         | 5        | 5      | 0.47%   |
| ASMT                        | 5        | 6      | 0.47%   |
| Apacer                      | 5        | 5      | 0.47%   |
| Transcend                   | 4        | 4      | 0.37%   |
| Team                        | 4        | 4      | 0.37%   |
| Silicon Motion              | 4        | 6      | 0.37%   |
| OCZ                         | 4        | 4      | 0.37%   |
| Kingston Technology Company | 4        | 4      | 0.37%   |
| KingDian                    | 4        | 5      | 0.37%   |
| Fujitsu                     | 4        | 14     | 0.37%   |
| Vaseky                      | 3        | 3      | 0.28%   |
| Smartbuy                    | 3        | 3      | 0.28%   |
| Phison                      | 3        | 4      | 0.28%   |
| MSI                         | 3        | 3      | 0.28%   |
| KIOXIA-EXCERIA              | 3        | 3      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 22       | 1.86%   |
| Kingston SA400S37240G 240GB SSD  | 15       | 1.27%   |
| Toshiba DT01ACA100 1TB           | 12       | 1.02%   |
| Seagate ST1000DM010-2EP102 1TB   | 10       | 0.85%   |
| Kingston SA400S37120G 120GB SSD  | 10       | 0.85%   |
| Kingston SA400S37480G 480GB SSD  | 9        | 0.76%   |
| Unknown SD/MMC/MS PRO 128GB      | 8        | 0.68%   |
| Toshiba DT01ACA050 500GB         | 8        | 0.68%   |
| WDC WD10EZEX-08WN4A0 1TB         | 7        | 0.59%   |
| Seagate ST3500418AS 500GB        | 7        | 0.59%   |
| SanDisk NVMe SSD Drive 1TB       | 7        | 0.59%   |
| Crucial CT240BX500SSD1 240GB     | 7        | 0.59%   |
| Seagate ST2000DM008-2FR102 2TB   | 6        | 0.51%   |
| Seagate ST2000DM001-1ER164 2TB   | 6        | 0.51%   |
| Seagate ST1000DM003-1ER162 1TB   | 6        | 0.51%   |
| JMicron Generic 500GB            | 6        | 0.51%   |
| Unknown                          | 6        | 0.51%   |
| WDC WD10EZEX-22MFCA0 1TB         | 5        | 0.42%   |
| SanDisk SSD PLUS 240GB           | 5        | 0.42%   |
| Kingston SUV400S37120G 120GB SSD | 5        | 0.42%   |
| HPQ BF450DASTK 450GB             | 5        | 0.42%   |
| Crucial CT120BX500SSD1 120GB     | 5        | 0.42%   |
| WDC WD5000AAKX-001CA0 500GB      | 4        | 0.34%   |
| WDC WD10EZEX-00BBHA0 1TB         | 4        | 0.34%   |
| Toshiba HDWD130 3TB              | 4        | 0.34%   |
| Toshiba HDWD110 1TB              | 4        | 0.34%   |
| Toshiba DT01ACA200 2TB           | 4        | 0.34%   |
| SPCC Solid State Disk 512GB      | 4        | 0.34%   |
| SPCC Solid State Disk 256GB      | 4        | 0.34%   |
| Seagate ST2000DM001-1CH164 2TB   | 4        | 0.34%   |
| Seagate Expansion 1TB            | 4        | 0.34%   |
| Samsung SSD 870 EVO 500GB        | 4        | 0.34%   |
| Samsung SSD 860 QVO 1TB          | 4        | 0.34%   |
| Samsung SSD 860 EVO 250GB        | 4        | 0.34%   |
| Samsung SSD 850 EVO 250GB        | 4        | 0.34%   |
| Kingston Company SNV2S1000G 1TB  | 4        | 0.34%   |
| Kingston SNV2S500G 500GB         | 4        | 0.34%   |
| JMicron Tech 250GB               | 4        | 0.34%   |
| Hitachi HDS721010CLA332 1TB      | 4        | 0.34%   |
| Crucial CT275MX300SSD1 275GB     | 4        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 165      | 215    | 33.2%   |
| WDC                 | 164      | 193    | 33%     |
| Toshiba             | 53       | 59     | 10.66%  |
| Hitachi             | 33       | 37     | 6.64%   |
| Samsung Electronics | 26       | 31     | 5.23%   |
| Unknown             | 9        | 9      | 1.81%   |
| HGST                | 9        | 9      | 1.81%   |
| JMicron Technology  | 7        | 7      | 1.41%   |
| Maxtor              | 6        | 6      | 1.21%   |
| HPQ                 | 5        | 5      | 1.01%   |
| ASMT                | 4        | 5      | 0.8%    |
| Fujitsu             | 3        | 13     | 0.6%    |
| TO Exter            | 2        | 2      | 0.4%    |
| WD MediaMax         | 1        | 1      | 0.2%    |
| StoreJet            | 1        | 1      | 0.2%    |
| SABRENT             | 1        | 1      | 0.2%    |
| MaxDigital          | 1        | 1      | 0.2%    |
| KESU                | 1        | 1      | 0.2%    |
| Intenso             | 1        | 1      | 0.2%    |
| Inateck             | 1        | 1      | 0.2%    |
| HGST HTS            | 1        | 1      | 0.2%    |
| Hewlett-Packard     | 1        | 1      | 0.2%    |
| CIRAGO              | 1        | 1      | 0.2%    |
| Apple               | 1        | 1      | 0.2%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 56       | 59     | 13.59%  |
| Samsung Electronics | 47       | 51     | 11.41%  |
| Crucial             | 36       | 40     | 8.74%   |
| China               | 27       | 29     | 6.55%   |
| SanDisk             | 23       | 26     | 5.58%   |
| GOODRAM             | 19       | 20     | 4.61%   |
| WDC                 | 17       | 17     | 4.13%   |
| A-DATA Technology   | 16       | 17     | 3.88%   |
| Intenso             | 15       | 16     | 3.64%   |
| SPCC                | 14       | 17     | 3.4%    |
| Patriot             | 13       | 15     | 3.16%   |
| Intel               | 13       | 13     | 3.16%   |
| PNY                 | 7        | 8      | 1.7%    |
| Unknown             | 6        | 6      | 1.46%   |
| Apacer              | 5        | 5      | 1.21%   |
| Transcend           | 4        | 4      | 0.97%   |
| OCZ                 | 4        | 4      | 0.97%   |
| Netac               | 4        | 4      | 0.97%   |
| Micron Technology   | 4        | 5      | 0.97%   |
| KingDian            | 4        | 5      | 0.97%   |
| Vaseky              | 3        | 3      | 0.73%   |
| SK hynix            | 3        | 3      | 0.73%   |
| KIOXIA-EXCERIA      | 3        | 3      | 0.73%   |
| KingFast            | 3        | 3      | 0.73%   |
| DEXP                | 3        | 3      | 0.73%   |
| Toshiba             | 2        | 2      | 0.49%   |
| Team                | 2        | 2      | 0.49%   |
| Smartbuy            | 2        | 2      | 0.49%   |
| Reeinno             | 2        | 2      | 0.49%   |
| PNY USB             | 2        | 2      | 0.49%   |
| LITEON              | 2        | 2      | 0.49%   |
| KingSpec            | 2        | 2      | 0.49%   |
| Inland              | 2        | 2      | 0.49%   |
| Hitachi             | 2        | 2      | 0.49%   |
| Gigabyte Technology | 2        | 2      | 0.49%   |
| Fanxiang            | 2        | 2      | 0.49%   |
| Dogfish             | 2        | 2      | 0.49%   |
| AMD                 | 2        | 2      | 0.49%   |
| YHJC                | 1        | 1      | 0.24%   |
| XrayDisk            | 1        | 2      | 0.24%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 388      | 602    | 44.5%   |
| SSD     | 322      | 440    | 36.93%  |
| NVMe    | 149      | 187    | 17.09%  |
| Unknown | 11       | 13     | 1.26%   |
| MMC     | 2        | 2      | 0.23%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 545      | 969    | 71.9%   |
| NVMe | 146      | 183    | 19.26%  |
| SAS  | 65       | 90     | 8.58%   |
| MMC  | 2        | 2      | 0.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 430      | 660    | 57.95%  |
| 0.51-1.0   | 203      | 249    | 27.36%  |
| 1.01-2.0   | 64       | 81     | 8.63%   |
| 2.01-3.0   | 17       | 19     | 2.29%   |
| 3.01-4.0   | 15       | 18     | 2.02%   |
| 4.01-10.0  | 8        | 10     | 1.08%   |
| 10.01-20.0 | 5        | 5      | 0.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 203      | 32.9%   |
| 101-250        | 127      | 20.58%  |
| 251-500        | 88       | 14.26%  |
| Unknown        | 46       | 7.46%   |
| 501-1000       | 38       | 6.16%   |
| 21-50          | 35       | 5.67%   |
| 51-100         | 35       | 5.67%   |
| 1001-2000      | 26       | 4.21%   |
| More than 3000 | 14       | 2.27%   |
| 2001-3000      | 5        | 0.81%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 429      | 69.08%  |
| 21-50          | 46       | 7.41%   |
| Unknown        | 46       | 7.41%   |
| 0              | 23       | 3.7%    |
| 101-250        | 20       | 3.22%   |
| 251-500        | 18       | 2.9%    |
| 51-100         | 16       | 2.58%   |
| 1001-2000      | 7        | 1.13%   |
| 501-1000       | 7        | 1.13%   |
| More than 3000 | 6        | 0.97%   |
| 2001-3000      | 3        | 0.48%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 9        | 9      | 3.98%   |
| Seagate ST3500418AS 500GB             | 6        | 7      | 2.65%   |
| WDC WD5000AAKX-001CA0 500GB           | 3        | 3      | 1.33%   |
| Toshiba DT01ACA100 1TB                | 3        | 3      | 1.33%   |
| Samsung Electronics SP2504C 250GB     | 3        | 3      | 1.33%   |
| Hitachi HDS721010CLA332 1TB           | 3        | 3      | 1.33%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 2        | 2      | 0.88%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 2        | 2      | 0.88%   |
| WDC WD3200BPVT-80JJ5T0 320GB          | 2        | 2      | 0.88%   |
| WDC WD3200AAKS-00L9A0 320GB           | 2        | 2      | 0.88%   |
| WDC WD10EARS-22Y5B1 1TB               | 2        | 2      | 0.88%   |
| WDC WD10EARS-00Y5B1 1TB               | 2        | 2      | 0.88%   |
| WDC WD10EADS-00L5B1 1TB               | 2        | 2      | 0.88%   |
| Toshiba MQ01ABD050V 500GB             | 2        | 2      | 0.88%   |
| Seagate ST9500325AS 500GB             | 2        | 2      | 0.88%   |
| Seagate ST380815AS 80GB               | 2        | 2      | 0.88%   |
| Seagate ST3320613AS 320GB             | 2        | 3      | 0.88%   |
| Seagate ST3250620AS 250GB             | 2        | 2      | 0.88%   |
| Seagate ST2000DM001-1CH164 2TB        | 2        | 3      | 0.88%   |
| Seagate ST1000DM003-1ER162 1TB        | 2        | 2      | 0.88%   |
| SanDisk SSD PLUS 240GB                | 2        | 2      | 0.88%   |
| Samsung Electronics SSD 970 EVO 500GB | 2        | 2      | 0.88%   |
| Samsung Electronics HD321KJ 320GB     | 2        | 3      | 0.88%   |
| HGST HTS721010A9E630 1TB              | 2        | 2      | 0.88%   |
| Crucial CT275MX300SSD1 275GB          | 2        | 2      | 0.88%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD      | 1        | 1      | 0.44%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 1        | 1      | 0.44%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 1        | 1      | 0.44%   |
| WDC WD800JB-32JJC0 80GB               | 1        | 1      | 0.44%   |
| WDC WD800JB-00JJC0 80GB               | 1        | 1      | 0.44%   |
| WDC WD800JB-00CRA1 80GB               | 1        | 1      | 0.44%   |
| WDC WD7500BPVT-22HXZT1 752GB          | 1        | 1      | 0.44%   |
| WDC WD7500AARS-00Y5B1 752GB           | 1        | 1      | 0.44%   |
| WDC WD6401AALS-00L3B2 640GB           | 1        | 1      | 0.44%   |
| WDC WD6400AAKS-65Z7B0 640GB           | 1        | 1      | 0.44%   |
| WDC WD6400AAKS-22A7B2 640GB           | 1        | 1      | 0.44%   |
| WDC WD5000HHTZ-04N21V0 500GB          | 1        | 1      | 0.44%   |
| WDC WD5000AVVS-63H0B1 500GB           | 1        | 1      | 0.44%   |
| WDC WD5000AAKX-221CA1 500GB           | 1        | 1      | 0.44%   |
| WDC WD5000AAKX-08U6AA0 500GB          | 1        | 1      | 0.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 71       | 76     | 33.18%  |
| Seagate             | 60       | 72     | 28.04%  |
| Samsung Electronics | 16       | 19     | 7.48%   |
| Hitachi             | 12       | 12     | 5.61%   |
| Toshiba             | 10       | 10     | 4.67%   |
| Kingston            | 5        | 5      | 2.34%   |
| HGST                | 5        | 5      | 2.34%   |
| Maxtor              | 4        | 4      | 1.87%   |
| A-DATA Technology   | 4        | 4      | 1.87%   |
| SanDisk             | 3        | 3      | 1.4%    |
| Crucial             | 3        | 3      | 1.4%    |
| China               | 3        | 3      | 1.4%    |
| Micron Technology   | 2        | 3      | 0.93%   |
| Intel               | 2        | 2      | 0.93%   |
| Fujitsu             | 2        | 2      | 0.93%   |
| WD MediaMax         | 1        | 1      | 0.47%   |
| Unknown             | 1        | 1      | 0.47%   |
| StoreJet            | 1        | 1      | 0.47%   |
| SPCC                | 1        | 1      | 0.47%   |
| SK hynix            | 1        | 1      | 0.47%   |
| Saichi              | 1        | 1      | 0.47%   |
| Reeinno             | 1        | 1      | 0.47%   |
| Patriot             | 1        | 1      | 0.47%   |
| Intenso             | 1        | 1      | 0.47%   |
| HUSKY               | 1        | 1      | 0.47%   |
| Apple               | 1        | 1      | 0.47%   |
| AMD                 | 1        | 1      | 0.47%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 65       | 70     | 37.14%  |
| Seagate             | 60       | 72     | 34.29%  |
| Samsung Electronics | 14       | 16     | 8%      |
| Hitachi             | 12       | 12     | 6.86%   |
| Toshiba             | 10       | 10     | 5.71%   |
| HGST                | 5        | 5      | 2.86%   |
| Maxtor              | 4        | 4      | 2.29%   |
| WD MediaMax         | 1        | 1      | 0.57%   |
| Unknown             | 1        | 1      | 0.57%   |
| StoreJet            | 1        | 1      | 0.57%   |
| Fujitsu             | 1        | 1      | 0.57%   |
| Apple               | 1        | 1      | 0.57%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 157      | 194    | 79.7%   |
| SSD  | 37       | 38     | 18.78%  |
| NVMe | 3        | 3      | 1.52%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD20EARS-00MVWB0 2TB        | 1        | 1      | 33.33%  |
| Toshiba DT01ACA100 1TB          | 1        | 1      | 33.33%  |
| Samsung Electronics HD103SJ 1TB | 1        | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 1        | 1      | 33.33%  |
| Toshiba             | 1        | 1      | 33.33%  |
| Samsung Electronics | 1        | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 519      | 923    | 67.14%  |
| Malfunc  | 188      | 235    | 24.32%  |
| Detected | 63       | 83     | 8.15%   |
| Failed   | 3        | 3      | 0.39%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 415      | 48.94%  |
| AMD                           | 179      | 21.11%  |
| Samsung Electronics           | 32       | 3.77%   |
| Kingston Technology Company   | 31       | 3.66%   |
| SanDisk                       | 29       | 3.42%   |
| ASMedia Technology            | 28       | 3.3%    |
| JMicron Technology            | 22       | 2.59%   |
| Marvell Technology Group      | 16       | 1.89%   |
| Phison Electronics            | 15       | 1.77%   |
| Nvidia                        | 15       | 1.77%   |
| Silicon Motion                | 12       | 1.42%   |
| MAXIO Technology (Hangzhou)   | 9        | 1.06%   |
| SK hynix                      | 6        | 0.71%   |
| Micron/Crucial Technology     | 6        | 0.71%   |
| ADATA Technology              | 5        | 0.59%   |
| Realtek Semiconductor         | 4        | 0.47%   |
| Adaptec                       | 4        | 0.47%   |
| Micron Technology             | 3        | 0.35%   |
| KIOXIA                        | 3        | 0.35%   |
| Broadcom / LSI                | 3        | 0.35%   |
| VIA Technologies              | 2        | 0.24%   |
| Shenzhen Longsys Electronics  | 2        | 0.24%   |
| Seagate Technology            | 2        | 0.24%   |
| Toshiba America Info Systems  | 1        | 0.12%   |
| TenaFe                        | 1        | 0.12%   |
| Silicon Image                 | 1        | 0.12%   |
| Integrated Technology Express | 1        | 0.12%   |
| Hosin Global Electronics      | 1        | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 85       | 8.24%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 51       | 4.95%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 43       | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 39       | 3.78%   |
| AMD 400 Series Chipset SATA Controller                                                  | 32       | 3.1%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 31       | 3.01%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 30       | 2.91%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 28       | 2.72%   |
| AMD 500 Series Chipset SATA Controller                                                  | 26       | 2.52%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 25       | 2.42%   |
| Intel SATA Controller [RAID mode]                                                       | 24       | 2.33%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 23       | 2.23%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 22       | 2.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 21       | 2.04%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 19       | 1.84%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 18       | 1.75%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 14       | 1.36%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 13       | 1.26%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 12       | 1.16%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 11       | 1.07%   |
| AMD FCH IDE Controller                                                                  | 11       | 1.07%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 10       | 0.97%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 10       | 0.97%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 9        | 0.87%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 9        | 0.87%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 9        | 0.87%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 9        | 0.87%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 9        | 0.87%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 8        | 0.78%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD [E18]                                    | 8        | 0.78%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 8        | 0.78%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 7        | 0.68%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 7        | 0.68%   |
| Phison E12 NVMe Controller                                                              | 7        | 0.68%   |
| Nvidia MCP61 SATA Controller                                                            | 7        | 0.68%   |
| Nvidia MCP61 IDE                                                                        | 7        | 0.68%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 7        | 0.68%   |
| AMD 600 Series Chipset SATA Controller                                                  | 7        | 0.68%   |
| AMD 300 Series Chipset SATA Controller                                                  | 7        | 0.68%   |
| Intel Alder Lake-N SATA AHCI Controller                                                 | 6        | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 498      | 60.73%  |
| NVMe | 144      | 17.56%  |
| IDE  | 141      | 17.2%   |
| RAID | 33       | 4.02%   |
| SAS  | 2        | 0.24%   |
| SCSI | 2        | 0.24%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 420      | 68.29%  |
| AMD    | 195      | 31.71%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| AMD Ryzen 5 5600G with Radeon Graphics        | 12       | 1.95%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 11       | 1.79%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 10       | 1.63%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 10       | 1.63%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 9        | 1.46%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 9        | 1.46%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 8        | 1.3%    |
| Intel Core i5-6500 CPU @ 3.20GHz              | 8        | 1.3%    |
| AMD Ryzen 5 3600 6-Core Processor             | 8        | 1.3%    |
| Intel Core i7-8700 CPU @ 3.20GHz              | 6        | 0.98%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz          | 6        | 0.98%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 5        | 0.81%   |
| Intel Core i5-7500 CPU @ 3.40GHz              | 5        | 0.81%   |
| Intel Core i5-6400 CPU @ 2.70GHz              | 5        | 0.81%   |
| Intel Core i3-4170 CPU @ 3.70GHz              | 5        | 0.81%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 5        | 0.81%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 5        | 0.81%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 5        | 0.81%   |
| AMD Ryzen 7 5700X 8-Core Processor            | 5        | 0.81%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 5        | 0.81%   |
| AMD Ryzen 5 5500                              | 5        | 0.81%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 5        | 0.81%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 5        | 0.81%   |
| Intel Core i7-9700 CPU @ 3.00GHz              | 4        | 0.65%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 4        | 0.65%   |
| Intel Core i5-3570 CPU @ 3.40GHz              | 4        | 0.65%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 4        | 0.65%   |
| Intel Core i5 CPU 750 @ 2.67GHz               | 4        | 0.65%   |
| Intel Core i3-6100 CPU @ 3.70GHz              | 4        | 0.65%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 4        | 0.65%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 4        | 0.65%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 4        | 0.65%   |
| AMD Athlon 3000G with Radeon Vega Graphics    | 4        | 0.65%   |
| AMD A8-7600 Radeon R7, 10 Compute Cores 4C+6G | 4        | 0.65%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz        | 3        | 0.49%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz   | 3        | 0.49%   |
| Intel N100                                    | 3        | 0.49%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 3        | 0.49%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 3        | 0.49%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 3        | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 134      | 21.79%  |
| Intel Core i7           | 55       | 8.94%   |
| Intel Core i3           | 51       | 8.29%   |
| AMD Ryzen 5             | 50       | 8.13%   |
| Intel Core 2 Duo        | 29       | 4.72%   |
| Other                   | 27       | 4.39%   |
| Intel Celeron           | 26       | 4.23%   |
| Intel Xeon              | 25       | 4.07%   |
| AMD Ryzen 7             | 25       | 4.07%   |
| Intel Pentium           | 24       | 3.9%    |
| AMD FX                  | 18       | 2.93%   |
| Intel Core 2 Quad       | 13       | 2.11%   |
| AMD A8                  | 13       | 2.11%   |
| Intel Pentium Dual-Core | 11       | 1.79%   |
| AMD A10                 | 10       | 1.63%   |
| AMD Ryzen 3             | 9        | 1.46%   |
| AMD Ryzen 9             | 8        | 1.3%    |
| AMD Athlon              | 8        | 1.3%    |
| Intel Core 2            | 7        | 1.14%   |
| AMD Athlon 64 X2        | 7        | 1.14%   |
| AMD A4                  | 7        | 1.14%   |
| Intel Pentium Gold      | 5        | 0.81%   |
| Intel Core i9           | 5        | 0.81%   |
| AMD Phenom II X4        | 5        | 0.81%   |
| AMD Phenom II X2        | 4        | 0.65%   |
| Intel Pentium Dual      | 3        | 0.49%   |
| AMD Ryzen 3 PRO         | 3        | 0.49%   |
| AMD Phenom II X6        | 3        | 0.49%   |
| AMD E                   | 3        | 0.49%   |
| AMD Athlon II X4        | 3        | 0.49%   |
| AMD Athlon II X2        | 3        | 0.49%   |
| AMD Athlon 64           | 3        | 0.49%   |
| AMD A6                  | 3        | 0.49%   |
| AMD PRO A10             | 2        | 0.33%   |
| AMD Phenom              | 2        | 0.33%   |
| AMD Athlon X4           | 2        | 0.33%   |
| AMD Athlon Dual Core    | 2        | 0.33%   |
| Intel Pentium Silver    | 1        | 0.16%   |
| Intel Pentium D         | 1        | 0.16%   |
| Intel Pentium 4         | 1        | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 237      | 38.54%  |
| 2      | 207      | 33.66%  |
| 6      | 89       | 14.47%  |
| 8      | 44       | 7.15%   |
| 1      | 13       | 2.11%   |
| 12     | 8        | 1.3%    |
| 10     | 7        | 1.14%   |
| 16     | 3        | 0.49%   |
| 14     | 3        | 0.49%   |
| 3      | 3        | 0.49%   |
| 18     | 1        | 0.16%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 610      | 99.19%  |
| 2      | 3        | 0.49%   |
| 6      | 1        | 0.16%   |
| 4      | 1        | 0.16%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 310      | 50.41%  |
| 2      | 305      | 49.59%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 615      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 435      | 70.73%  |
| 0x06001119 | 14       | 2.28%   |
| 0x06003106 | 13       | 2.11%   |
| 0x08701021 | 11       | 1.79%   |
| 0x0800820d | 10       | 1.63%   |
| 0x0a50000c | 8        | 1.3%    |
| 0x0a20120a | 8        | 1.3%    |
| 0x0a50000f | 7        | 1.14%   |
| 0x0a50000d | 7        | 1.14%   |
| 0x08108109 | 7        | 1.14%   |
| 0x08101016 | 7        | 1.14%   |
| 0x08001138 | 6        | 0.98%   |
| 0x06000822 | 6        | 0.98%   |
| 0x010000c8 | 5        | 0.81%   |
| 0x010000b6 | 5        | 0.81%   |
| 0x0a601206 | 4        | 0.65%   |
| 0x08701030 | 4        | 0.65%   |
| 0x010000bf | 4        | 0.65%   |
| 0x0810100b | 3        | 0.49%   |
| 0x06001116 | 3        | 0.49%   |
| 0x06000817 | 3        | 0.49%   |
| 0x0a601203 | 2        | 0.33%   |
| 0x0a20120e | 2        | 0.33%   |
| 0x0a20102b | 2        | 0.33%   |
| 0x08600109 | 2        | 0.33%   |
| 0x08600106 | 2        | 0.33%   |
| 0x0700010b | 2        | 0.33%   |
| 0x0600611a | 2        | 0.33%   |
| 0x0600081c | 2        | 0.33%   |
| 0x06000626 | 2        | 0.33%   |
| 0x06000613 | 2        | 0.33%   |
| 0x05000028 | 2        | 0.33%   |
| 0x03000027 | 2        | 0.33%   |
| 0x010000c6 | 2        | 0.33%   |
| 0x6fd      | 1        | 0.16%   |
| 0x206a7    | 1        | 0.16%   |
| 0x0a705206 | 1        | 0.16%   |
| 0x0a705203 | 1        | 0.16%   |
| 0x0a404102 | 1        | 0.16%   |
| 0x0a201205 | 1        | 0.16%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 65       | 10.57%  |
| KabyLake         | 63       | 10.24%  |
| IvyBridge        | 50       | 8.13%   |
| Penryn           | 48       | 7.8%    |
| Skylake          | 46       | 7.48%   |
| Zen 3            | 37       | 6.02%   |
| SandyBridge      | 35       | 5.69%   |
| Piledriver       | 28       | 4.55%   |
| Zen 2            | 21       | 3.41%   |
| K10              | 21       | 3.41%   |
| Core             | 19       | 3.09%   |
| Zen              | 18       | 2.93%   |
| CometLake        | 18       | 2.93%   |
| Zen+             | 17       | 2.76%   |
| Westmere         | 15       | 2.44%   |
| Steamroller      | 15       | 2.44%   |
| Alderlake Hybrid | 15       | 2.44%   |
| K8 Hammer        | 12       | 1.95%   |
| Nehalem          | 10       | 1.63%   |
| Unknown          | 10       | 1.63%   |
| Bulldozer        | 7        | 1.14%   |
| Silvermont       | 6        | 0.98%   |
| Icelake          | 6        | 0.98%   |
| Gracemont        | 6        | 0.98%   |
| Broadwell        | 5        | 0.81%   |
| Tremont          | 3        | 0.49%   |
| Goldmont plus    | 3        | 0.49%   |
| Goldmont         | 3        | 0.49%   |
| Bobcat           | 3        | 0.49%   |
| NetBurst         | 2        | 0.33%   |
| K10 Llano        | 2        | 0.33%   |
| Jaguar           | 2        | 0.33%   |
| Excavator        | 2        | 0.33%   |
| Puma             | 1        | 0.16%   |
| Bonnell          | 1        | 0.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 242      | 37.87%  |
| Nvidia                                       | 198      | 30.99%  |
| AMD                                          | 192      | 30.05%  |
| Red Hat                                      | 2        | 0.31%   |
| NVidia / SGS Thomson (Joint Venture)         | 2        | 0.31%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.16%   |
| Matrox Electronics Systems                   | 1        | 0.16%   |
| ATI Technologies                             | 1        | 0.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 36       | 5.52%   |
| Intel HD Graphics 530                                                       | 27       | 4.14%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 24       | 3.68%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 23       | 3.53%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 19       | 2.91%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 18       | 2.76%   |
| Intel HD Graphics 630                                                       | 16       | 2.45%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 14       | 2.15%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 13       | 1.99%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 13       | 1.99%   |
| Nvidia GT218 [GeForce 210]                                                  | 12       | 1.84%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 10       | 1.53%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 10       | 1.53%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 9        | 1.38%   |
| Nvidia GK208B [GeForce GT 710]                                              | 9        | 1.38%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 8        | 1.23%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 7        | 1.07%   |
| Nvidia GK208B [GeForce GT 730]                                              | 7        | 1.07%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 7        | 1.07%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 7        | 1.07%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 6        | 0.92%   |
| Intel Alder Lake-N [UHD Graphics]                                           | 6        | 0.92%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 6        | 0.92%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 6        | 0.92%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 6        | 0.92%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 5        | 0.77%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 5        | 0.77%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 5        | 0.77%   |
| Nvidia GF119 [GeForce GT 610]                                               | 5        | 0.77%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 5        | 0.77%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 5        | 0.77%   |
| AMD Navi 32 [Radeon RX 7700 XT / 7800 XT]                                   | 5        | 0.77%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 5        | 0.77%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 5        | 0.77%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 4        | 0.61%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 0.61%   |
| Nvidia GM107GL [Quadro K2200]                                               | 4        | 0.61%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 4        | 0.61%   |
| Nvidia GF119 [GeForce GT 520]                                               | 4        | 0.61%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 4        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                                          | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| 1 x Intel                                     | 204      | 33.17%  |
| 1 x Nvidia                                    | 179      | 29.11%  |
| 1 x AMD                                       | 172      | 27.97%  |
| 2 x Intel                                     | 19       | 3.09%   |
| Intel + Nvidia                                | 14       | 2.28%   |
| 2 x AMD                                       | 12       | 1.95%   |
| Intel + AMD                                   | 5        | 0.81%   |
| AMD + Nvidia                                  | 4        | 0.65%   |
| 1 x Red Hat                                   | 2        | 0.33%   |
| 1 x XGI                                       | 1        | 0.16%   |
| 1 x NVidia / SGS Thomson (Joint Venture)      | 1        | 0.16%   |
| Nvidia + NVidia / SGS Thomson (Joint Venture) | 1        | 0.16%   |
| 1 x Matrox                                    | 1        | 0.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 593      | 96.27%  |
| Unknown     | 13       | 2.11%   |
| Proprietary | 10       | 1.62%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 238      | 38.7%   |
| 1.01-2.0   | 91       | 14.8%   |
| 0.51-1.0   | 82       | 13.33%  |
| 0.01-0.5   | 77       | 12.52%  |
| 3.01-4.0   | 56       | 9.11%   |
| 7.01-8.0   | 25       | 4.07%   |
| 5.01-6.0   | 19       | 3.09%   |
| 8.01-16.0  | 16       | 2.6%    |
| 2.01-3.0   | 8        | 1.3%    |
| 16.01-24.0 | 2        | 0.33%   |
| 4.01-5.0   | 1        | 0.16%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 107      | 17.83%  |
| Goldstar             | 63       | 10.5%   |
| Dell                 | 57       | 9.5%    |
| Hewlett-Packard      | 56       | 9.33%   |
| Acer                 | 39       | 6.5%    |
| Philips              | 34       | 5.67%   |
| AOC                  | 29       | 4.83%   |
| Ancor Communications | 28       | 4.67%   |
| Lenovo               | 17       | 2.83%   |
| Iiyama               | 16       | 2.67%   |
| BenQ                 | 15       | 2.5%    |
| ASUSTek Computer     | 15       | 2.5%    |
| ViewSonic            | 14       | 2.33%   |
| Sony                 | 11       | 1.83%   |
| NEC Computers        | 7        | 1.17%   |
| Fujitsu Siemens      | 4        | 0.67%   |
| Eizo                 | 4        | 0.67%   |
| SKY                  | 3        | 0.5%    |
| Sceptre Tech         | 3        | 0.5%    |
| Packard Bell         | 3        | 0.5%    |
| MSI                  | 3        | 0.5%    |
| HannStar             | 3        | 0.5%    |
| GDH                  | 3        | 0.5%    |
| Gateway              | 3        | 0.5%    |
| Unknown              | 2        | 0.33%   |
| Sharp                | 2        | 0.33%   |
| RTK                  | 2        | 0.33%   |
| RHT                  | 2        | 0.33%   |
| PRI                  | 2        | 0.33%   |
| MGW                  | 2        | 0.33%   |
| LG Electronics       | 2        | 0.33%   |
| HUAWEI               | 2        | 0.33%   |
| HKC                  | 2        | 0.33%   |
| Denver               | 2        | 0.33%   |
| AOD                  | 2        | 0.33%   |
| ___                  | 1        | 0.17%   |
| Wacom                | 1        | 0.17%   |
| Vizio                | 1        | 0.17%   |
| Vestel Elektronik    | 1        | 0.17%   |
| Toshiba              | 1        | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 7        | 1.16%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 5        | 0.83%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 5        | 0.83%   |
| AOC Q27G2WG4 AOC2702 2560x1440 597x336mm 27.0-inch                    | 5        | 0.83%   |
| Iiyama PL2792H IVM664F 1920x1080 598x336mm 27.0-inch                  | 4        | 0.66%   |
| Goldstar E2250 GSM578D 1920x1080 477x268mm 21.5-inch                  | 4        | 0.66%   |
| AOC 2460G4 AOC2460 1920x1080 531x299mm 24.0-inch                      | 4        | 0.66%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch               | 3        | 0.5%    |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch            | 3        | 0.5%    |
| Goldstar L1953S GSM4B3E 1280x1024 338x270mm 17.0-inch                 | 3        | 0.5%    |
| GDH TV PHILCO GDH0030 1920x540                                        | 3        | 0.5%    |
| Dell E196FP DELA015 1280x1024 338x270mm 17.0-inch                     | 3        | 0.5%    |
| AOC 2250W AOC2250 1920x1080 477x268mm 21.5-inch                       | 3        | 0.5%    |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch         | 2        | 0.33%   |
| ViewSonic VA2216w-2 VSC2920 1680x1050 495x291mm 22.6-inch             | 2        | 0.33%   |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 526x296mm 23.8-inch        | 2        | 0.33%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 2        | 0.33%   |
| Samsung Electronics SMBX2331 SAM076E 1920x1080 509x286mm 23.0-inch    | 2        | 0.33%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 2        | 0.33%   |
| Samsung Electronics S22E450 SAM0C7C 1680x1050 473x291mm 21.9-inch     | 2        | 0.33%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 2        | 0.33%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 480x270mm 21.7-inch | 2        | 0.33%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                | 2        | 0.33%   |
| RHT QEMU Monitor RHT1234 2048x1152 325x203mm 15.1-inch                | 2        | 0.33%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 2        | 0.33%   |
| Philips PHL 271V8 PHLC213 1920x1080 598x336mm 27.0-inch               | 2        | 0.33%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                | 2        | 0.33%   |
| MGW USB Capture MGW0206 1920x1200 708x398mm 32.0-inch                 | 2        | 0.33%   |
| Lenovo LEN LT2252pwA LEN0A0C 1680x1050 474x296mm 22.0-inch            | 2        | 0.33%   |
| Lenovo LEN L171 LEN240B 1280x1024 340x270mm 17.1-inch                 | 2        | 0.33%   |
| Iiyama PL2492H IVM612F 1920x1080 527x296mm 23.8-inch                  | 2        | 0.33%   |
| Hewlett-Packard w2207 HWP26A8 1680x1050 473x296mm 22.0-inch           | 2        | 0.33%   |
| Hewlett-Packard LE2002x HWP2963 1600x900 443x249mm 20.0-inch          | 2        | 0.33%   |
| Hewlett-Packard LA2405 HWP284B 1920x1200 518x324mm 24.1-inch          | 2        | 0.33%   |
| Hewlett-Packard 24y HPN3504 1920x1080 528x297mm 23.9-inch             | 2        | 0.33%   |
| Goldstar W2252 GSM567D 1680x1050 474x296mm 22.0-inch                  | 2        | 0.33%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                  | 2        | 0.33%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 2        | 0.33%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 2        | 0.33%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 2        | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 315      | 53.48%  |
| 1280x1024 (SXGA)   | 51       | 8.66%   |
| 3840x2160 (4K)     | 49       | 8.32%   |
| 1680x1050 (WSXGA+) | 35       | 5.94%   |
| 2560x1440 (QHD)    | 30       | 5.09%   |
| 1366x768 (WXGA)    | 25       | 4.24%   |
| 1440x900 (WXGA+)   | 20       | 3.4%    |
| 1920x1200 (WUXGA)  | 18       | 3.06%   |
| 1600x900 (HD+)     | 15       | 2.55%   |
| 2560x1080          | 5        | 0.85%   |
| 1360x768           | 5        | 0.85%   |
| 1920x540           | 4        | 0.68%   |
| 1600x1200          | 4        | 0.68%   |
| 1024x768 (XGA)     | 4        | 0.68%   |
| 3440x1440          | 3        | 0.51%   |
| 2048x1152          | 2        | 0.34%   |
| 3840x1600          | 1        | 0.17%   |
| 3520x1080          | 1        | 0.17%   |
| 2288x1287          | 1        | 0.17%   |
| 1280x960           | 1        | 0.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 85       | 14.19%  |
| 27      | 83       | 13.86%  |
| 24      | 82       | 13.69%  |
| 21      | 77       | 12.85%  |
| 19      | 50       | 8.35%   |
| 18      | 27       | 4.51%   |
| 17      | 25       | 4.17%   |
| 22      | 23       | 3.84%   |
| 31      | 22       | 3.67%   |
| 20      | 21       | 3.51%   |
| Unknown | 15       | 2.5%    |
| 40      | 11       | 1.84%   |
| 84      | 10       | 1.67%   |
| 54      | 9        | 1.5%    |
| 32      | 8        | 1.34%   |
| 72      | 5        | 0.83%   |
| 34      | 4        | 0.67%   |
| 52      | 3        | 0.5%    |
| 46      | 3        | 0.5%    |
| 36      | 3        | 0.5%    |
| 29      | 3        | 0.5%    |
| 26      | 3        | 0.5%    |
| 25      | 3        | 0.5%    |
| 15      | 3        | 0.5%    |
| 60      | 2        | 0.33%   |
| 49      | 2        | 0.33%   |
| 37      | 2        | 0.33%   |
| 28      | 2        | 0.33%   |
| 13      | 2        | 0.33%   |
| 142     | 1        | 0.17%   |
| 85      | 1        | 0.17%   |
| 65      | 1        | 0.17%   |
| 64      | 1        | 0.17%   |
| 48      | 1        | 0.17%   |
| 43      | 1        | 0.17%   |
| 42      | 1        | 0.17%   |
| 41      | 1        | 0.17%   |
| 39      | 1        | 0.17%   |
| 33      | 1        | 0.17%   |
| 12      | 1        | 0.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 244      | 41.15%  |
| 401-500        | 173      | 29.17%  |
| 601-700        | 32       | 5.4%    |
| 301-350        | 28       | 4.72%   |
| 351-400        | 26       | 4.38%   |
| 1001-1500      | 22       | 3.71%   |
| 701-800        | 16       | 2.7%    |
| 1501-2000      | 16       | 2.7%    |
| Unknown        | 15       | 2.53%   |
| 801-900        | 13       | 2.19%   |
| 901-1000       | 4        | 0.67%   |
| 201-300        | 3        | 0.51%   |
| More than 2000 | 1        | 0.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 422      | 71.89%  |
| 16/10   | 79       | 13.46%  |
| 5/4     | 51       | 8.69%   |
| 4/3     | 10       | 1.7%    |
| Unknown | 9        | 1.53%   |
| 21/9    | 8        | 1.36%   |
| 3/2     | 4        | 0.68%   |
| 32/9    | 3        | 0.51%   |
| 1.00    | 1        | 0.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 217      | 36.47%  |
| 151-200        | 91       | 15.29%  |
| 301-350        | 88       | 14.79%  |
| 141-150        | 49       | 8.24%   |
| 351-500        | 37       | 6.22%   |
| More than 1000 | 35       | 5.88%   |
| 251-300        | 33       | 5.55%   |
| 501-1000       | 24       | 4.03%   |
| Unknown        | 15       | 2.52%   |
| 81-90          | 2        | 0.34%   |
| 111-120        | 2        | 0.34%   |
| 71-80          | 1        | 0.17%   |
| 101-110        | 1        | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 432      | 73.47%  |
| 101-120 | 97       | 16.5%   |
| 1-50    | 27       | 4.59%   |
| Unknown | 15       | 2.55%   |
| 121-160 | 11       | 1.87%   |
| 161-240 | 6        | 1.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 573      | 93.02%  |
| 2     | 24       | 3.9%    |
| 0     | 19       | 3.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 398      | 48.77%  |
| Intel                           | 222      | 27.21%  |
| Qualcomm Atheros                | 47       | 5.76%   |
| TP-Link                         | 20       | 2.45%   |
| Ralink Technology               | 20       | 2.45%   |
| Broadcom                        | 18       | 2.21%   |
| Ralink                          | 13       | 1.59%   |
| Nvidia                          | 11       | 1.35%   |
| MediaTek                        | 11       | 1.35%   |
| Marvell Technology Group        | 6        | 0.74%   |
| Qualcomm Atheros Communications | 4        | 0.49%   |
| D-Link                          | 4        | 0.49%   |
| Xiaomi                          | 3        | 0.37%   |
| NetGear                         | 3        | 0.37%   |
| Broadcom Limited                | 3        | 0.37%   |
| VIA Technologies                | 2        | 0.25%   |
| Samsung Electronics             | 2        | 0.25%   |
| OPPO Electronics                | 2        | 0.25%   |
| Huawei Technologies             | 2        | 0.25%   |
| D-Link System                   | 2        | 0.25%   |
| Belkin Components               | 2        | 0.25%   |
| ASIX Electronics                | 2        | 0.25%   |
| ZyXEL Communications            | 1        | 0.12%   |
| ZTE WCDMA Technologies MSM      | 1        | 0.12%   |
| U.S. Robotics                   | 1        | 0.12%   |
| Senao                           | 1        | 0.12%   |
| RedOctane                       | 1        | 0.12%   |
| Padix (Rockfire)                | 1        | 0.12%   |
| Motorola PCS                    | 1        | 0.12%   |
| Microsoft                       | 1        | 0.12%   |
| Interlogix.                     | 1        | 0.12%   |
| IMC Networks                    | 1        | 0.12%   |
| ICS Advent                      | 1        | 0.12%   |
| HMD Global                      | 1        | 0.12%   |
| Google                          | 1        | 0.12%   |
| Emtec                           | 1        | 0.12%   |
| DisplayLink                     | 1        | 0.12%   |
| ASUSTek Computer                | 1        | 0.12%   |
| Arduino SA                      | 1        | 0.12%   |
| Aquantia                        | 1        | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 319      | 35.02%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 27       | 2.96%   |
| Realtek RTL8125 2.5GbE Controller                                      | 24       | 2.63%   |
| Intel I211 Gigabit Network Connection                                  | 22       | 2.41%   |
| Intel Ethernet Connection (2) I219-LM                                  | 19       | 2.09%   |
| Intel Ethernet Connection I217-LM                                      | 18       | 1.98%   |
| Intel Ethernet Connection (2) I219-V                                   | 18       | 1.98%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 15       | 1.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 12       | 1.32%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 12       | 1.32%   |
| Ralink MT7601U Wireless Adapter                                        | 12       | 1.32%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 12       | 1.32%   |
| Realtek 802.11ac NIC                                                   | 11       | 1.21%   |
| Intel Wi-Fi 6 AX200                                                    | 11       | 1.21%   |
| Intel Ethernet Controller I225-V                                       | 11       | 1.21%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 10       | 1.1%    |
| Intel Ethernet Connection (7) I219-V                                   | 9        | 0.99%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 7        | 0.77%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 7        | 0.77%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 7        | 0.77%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 6        | 0.66%   |
| Nvidia MCP61 Ethernet                                                  | 6        | 0.66%   |
| Intel Wireless 7265                                                    | 6        | 0.66%   |
| Intel Wireless 7260                                                    | 6        | 0.66%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 6        | 0.66%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 5        | 0.55%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 5        | 0.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 5        | 0.55%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 5        | 0.55%   |
| Intel 82579V Gigabit Network Connection                                | 5        | 0.55%   |
| Intel 82574L Gigabit Network Connection                                | 5        | 0.55%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 5        | 0.55%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                    | 4        | 0.44%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 4        | 0.44%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 4        | 0.44%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 4        | 0.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 4        | 0.44%   |
| Qualcomm Atheros AR9271 802.11n                                        | 4        | 0.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 4        | 0.44%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 4        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 79       | 31.85%  |
| Intel                           | 60       | 24.19%  |
| Qualcomm Atheros                | 24       | 9.68%   |
| Ralink Technology               | 20       | 8.06%   |
| TP-Link                         | 19       | 7.66%   |
| Ralink                          | 13       | 5.24%   |
| MediaTek                        | 10       | 4.03%   |
| Qualcomm Atheros Communications | 4        | 1.61%   |
| D-Link                          | 4        | 1.61%   |
| Broadcom                        | 4        | 1.61%   |
| NetGear                         | 3        | 1.21%   |
| Belkin Components               | 2        | 0.81%   |
| ZyXEL Communications            | 1        | 0.4%    |
| Senao                           | 1        | 0.4%    |
| Microsoft                       | 1        | 0.4%    |
| IMC Networks                    | 1        | 0.4%    |
| D-Link System                   | 1        | 0.4%    |
| ASUSTek Computer                | 1        | 0.4%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 12       | 4.8%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 12       | 4.8%    |
| Ralink MT7601U Wireless Adapter                                | 12       | 4.8%    |
| Realtek 802.11ac NIC                                           | 11       | 4.4%    |
| Intel Wi-Fi 6 AX200                                            | 11       | 4.4%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 10       | 4%      |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 7        | 2.8%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 7        | 2.8%    |
| Intel Wireless 7265                                            | 6        | 2.4%    |
| Intel Wireless 7260                                            | 6        | 2.4%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 6        | 2.4%    |
| Ralink RT2870/RT3070 Wireless Adapter                          | 5        | 2%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 5        | 2%      |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 5        | 2%      |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 4        | 1.6%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 4        | 1.6%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 4        | 1.6%    |
| Qualcomm Atheros AR9271 802.11n                                | 4        | 1.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4        | 1.6%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 3        | 1.2%    |
| TP-Link 802.11ac NIC                                           | 3        | 1.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3        | 1.2%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 3        | 1.2%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3        | 1.2%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 3        | 1.2%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 3        | 1.2%    |
| Ralink RT3062 Wireless 802.11n 2T/2R                           | 3        | 1.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3        | 1.2%    |
| Qualcomm Atheros AR922X Wireless Network Adapter               | 3        | 1.2%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 3        | 1.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 3        | 1.2%    |
| TP-Link Archer T4U ver.3                                       | 2        | 0.8%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 2        | 0.8%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2        | 0.8%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 2        | 0.8%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 2        | 0.8%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 2        | 0.8%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 2        | 0.8%    |
| Realtek RTL8187 Wireless Adapter                               | 2        | 0.8%    |
| Realtek 802.11n WLAN Adapter                                   | 2        | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 372      | 58.4%   |
| Intel                    | 182      | 28.57%  |
| Qualcomm Atheros         | 26       | 4.08%   |
| Broadcom                 | 14       | 2.2%    |
| Nvidia                   | 11       | 1.73%   |
| Marvell Technology Group | 6        | 0.94%   |
| Xiaomi                   | 3        | 0.47%   |
| Broadcom Limited         | 3        | 0.47%   |
| VIA Technologies         | 2        | 0.31%   |
| Samsung Electronics      | 2        | 0.31%   |
| OPPO Electronics         | 2        | 0.31%   |
| Huawei Technologies      | 2        | 0.31%   |
| ASIX Electronics         | 2        | 0.31%   |
| TP-Link                  | 1        | 0.16%   |
| Motorola PCS             | 1        | 0.16%   |
| MediaTek                 | 1        | 0.16%   |
| ICS Advent               | 1        | 0.16%   |
| HMD Global               | 1        | 0.16%   |
| Google                   | 1        | 0.16%   |
| DisplayLink              | 1        | 0.16%   |
| D-Link System            | 1        | 0.16%   |
| Aquantia                 | 1        | 0.16%   |
| 3Com                     | 1        | 0.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 319      | 48.85%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 27       | 4.13%   |
| Realtek RTL8125 2.5GbE Controller                                      | 24       | 3.68%   |
| Intel I211 Gigabit Network Connection                                  | 22       | 3.37%   |
| Intel Ethernet Connection (2) I219-LM                                  | 19       | 2.91%   |
| Intel Ethernet Connection I217-LM                                      | 18       | 2.76%   |
| Intel Ethernet Connection (2) I219-V                                   | 18       | 2.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 15       | 2.3%    |
| Intel 82567LM-3 Gigabit Network Connection                             | 12       | 1.84%   |
| Intel Ethernet Controller I225-V                                       | 11       | 1.68%   |
| Intel Ethernet Connection (7) I219-V                                   | 9        | 1.38%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 7        | 1.07%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 6        | 0.92%   |
| Nvidia MCP61 Ethernet                                                  | 6        | 0.92%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 5        | 0.77%   |
| Intel 82579V Gigabit Network Connection                                | 5        | 0.77%   |
| Intel 82574L Gigabit Network Connection                                | 5        | 0.77%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 5        | 0.77%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 4        | 0.61%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 4        | 0.61%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 4        | 0.61%   |
| Intel Ethernet Connection (5) I219-LM                                  | 4        | 0.61%   |
| Intel Ethernet Connection (2) I218-LM                                  | 4        | 0.61%   |
| Intel 82578DM Gigabit Network Connection                               | 4        | 0.61%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 3        | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 3        | 0.46%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3        | 0.46%   |
| Intel I210 Gigabit Network Connection                                  | 3        | 0.46%   |
| Intel Ethernet Connection I217-V                                       | 3        | 0.46%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 3        | 0.46%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                | 3        | 0.46%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2        | 0.31%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2        | 0.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2        | 0.31%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 2        | 0.31%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2        | 0.31%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2        | 0.31%   |
| OPPO OnePlus Nord 4                                                    | 2        | 0.31%   |
| Nvidia MCP55 Ethernet                                                  | 2        | 0.31%   |
| Intel Ethernet Connection (6) I219-V                                   | 2        | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 603      | 70.61%  |
| WiFi     | 244      | 28.57%  |
| Modem    | 4        | 0.47%   |
| Unknown  | 3        | 0.35%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 481      | 78.85%  |
| WiFi     | 129      | 21.15%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 438      | 71.22%  |
| 2     | 156      | 25.37%  |
| 3     | 14       | 2.28%   |
| 0     | 7        | 1.14%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 418      | 67.86%  |
| Yes  | 198      | 32.14%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 53       | 30.64%  |
| Cambridge Silicon Radio         | 44       | 25.43%  |
| Realtek Semiconductor           | 27       | 15.61%  |
| ASUSTek Computer                | 10       | 5.78%   |
| MediaTek                        | 8        | 4.62%   |
| Qualcomm Atheros Communications | 6        | 3.47%   |
| IMC Networks                    | 6        | 3.47%   |
| Broadcom                        | 6        | 3.47%   |
| TP-Link                         | 2        | 1.16%   |
| Realtek                         | 2        | 1.16%   |
| Lite-On Technology              | 2        | 1.16%   |
| Actions                         | 2        | 1.16%   |
| Ralink                          | 1        | 0.58%   |
| Integrated System Solution      | 1        | 0.58%   |
| Foxconn / Hon Hai               | 1        | 0.58%   |
| Apple                           | 1        | 0.58%   |
| Unknown                         | 1        | 0.58%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 44       | 25.43%  |
| Realtek Bluetooth Radio                             | 20       | 11.56%  |
| Intel Bluetooth wireless interface                  | 15       | 8.67%   |
| Intel Wireless-AC 3168 Bluetooth                    | 10       | 5.78%   |
| Intel AX200 Bluetooth                               | 10       | 5.78%   |
| MediaTek Wireless_Device                            | 8        | 4.62%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 6        | 3.47%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4        | 2.31%   |
| Intel AX210 Bluetooth                               | 4        | 2.31%   |
| IMC Networks Bluetooth Radio                        | 4        | 2.31%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3        | 1.73%   |
| Qualcomm Atheros  Bluetooth Device                  | 3        | 1.73%   |
| Intel AX201 Bluetooth                               | 3        | 1.73%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 3        | 1.73%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 3        | 1.73%   |
| ASUS Bluetooth Radio                                | 3        | 1.73%   |
| ASUS ASUS USB-BT500                                 | 3        | 1.73%   |
| TP-Link TP-Link Bluetooth USB Adapter               | 2        | 1.16%   |
| Realtek Bluetooth 5.3 Radio                         | 2        | 1.16%   |
| Realtek Bluetooth Radio                             | 2        | 1.16%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2        | 1.16%   |
| IMC Networks Bluetooth Device                       | 2        | 1.16%   |
| Broadcom Bluetooth 3.0 Device                       | 2        | 1.16%   |
| Actions general adapter                             | 2        | 1.16%   |
| Realtek RTL8821A Bluetooth                          | 1        | 0.58%   |
| Realtek RTL8723B Bluetooth                          | 1        | 0.58%   |
| Ralink RT3290 Bluetooth                             | 1        | 0.58%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1        | 0.58%   |
| Lite-On Bluetooth Device                            | 1        | 0.58%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1        | 0.58%   |
| Intel AX211 Bluetooth                               | 1        | 0.58%   |
| Integrated System Solution Bluetooth Device         | 1        | 0.58%   |
| Foxconn / Hon Hai Wireless_Device                   | 1        | 0.58%   |
| Broadcom Bluetooth 2.1 Device                       | 1        | 0.58%   |
| ASUS Bluetooth Adapter                              | 1        | 0.58%   |
| Apple Bluetooth Host Controller                     | 1        | 0.58%   |
| Unknown                                             | 1        | 0.58%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 400      | 44.99%  |
| AMD                                          | 226      | 25.42%  |
| Nvidia                                       | 178      | 20.02%  |
| C-Media Electronics                          | 19       | 2.14%   |
| Creative Labs                                | 14       | 1.57%   |
| Zoran Co. Personal Media Division (Nogatech) | 6        | 0.67%   |
| Logitech                                     | 4        | 0.45%   |
| Texas Instruments                            | 3        | 0.34%   |
| Tenx Technology                              | 3        | 0.34%   |
| Generalplus Technology                       | 3        | 0.34%   |
| ASUSTek Computer                             | 3        | 0.34%   |
| VIA Technologies                             | 2        | 0.22%   |
| Razer USA                                    | 2        | 0.22%   |
| Micro Star International                     | 2        | 0.22%   |
| Medeli Electronics                           | 2        | 0.22%   |
| Jieli Technology                             | 2        | 0.22%   |
| GN Netcom                                    | 2        | 0.22%   |
| Ensoniq                                      | 2        | 0.22%   |
| Creative Technology                          | 2        | 0.22%   |
| Yamaha                                       | 1        | 0.11%   |
| XMOS                                         | 1        | 0.11%   |
| Plantronics                                  | 1        | 0.11%   |
| Megawin Technology                           | 1        | 0.11%   |
| JMTek                                        | 1        | 0.11%   |
| Giga-Byte Technology                         | 1        | 0.11%   |
| FiiO Electronics Technology                  | 1        | 0.11%   |
| eMPIA Technology                             | 1        | 0.11%   |
| Emotiva                                      | 1        | 0.11%   |
| Dell                                         | 1        | 0.11%   |
| Corsair                                      | 1        | 0.11%   |
| BY EDIFIER                                   | 1        | 0.11%   |
| ATI Technologies                             | 1        | 0.11%   |
| Unknown                                      | 1        | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 59       | 5.47%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 53       | 4.91%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 47       | 4.36%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 47       | 4.36%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 41       | 3.8%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 38       | 3.52%   |
| AMD FCH Azalia Controller                                                  | 36       | 3.34%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 35       | 3.24%   |
| Intel 200 Series PCH HD Audio                                              | 32       | 2.97%   |
| AMD Starship/Matisse HD Audio Controller                                   | 27       | 2.5%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 27       | 2.5%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 26       | 2.41%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 22       | 2.04%   |
| Intel Cannon Lake PCH cAVS                                                 | 22       | 2.04%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 19       | 1.76%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 18       | 1.67%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 18       | 1.67%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 17       | 1.58%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 17       | 1.58%   |
| Nvidia High Definition Audio Controller                                    | 16       | 1.48%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 16       | 1.48%   |
| Nvidia TU116 High Definition Audio Controller                              | 15       | 1.39%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 14       | 1.3%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 13       | 1.2%    |
| AMD Kaveri HDMI/DP Audio Controller                                        | 13       | 1.2%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 13       | 1.2%    |
| Nvidia GP106 High Definition Audio Controller                              | 12       | 1.11%   |
| Nvidia GF119 HDMI Audio Controller                                         | 12       | 1.11%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 12       | 1.11%   |
| AMD Trinity HDMI Audio Controller                                          | 12       | 1.11%   |
| Nvidia GP107GL High Definition Audio Controller                            | 11       | 1.02%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 11       | 1.02%   |
| Intel Comet Lake PCH-V cAVS                                                | 9        | 0.83%   |
| Nvidia GF108 High Definition Audio Controller                              | 8        | 0.74%   |
| Intel Alder Lake-S HD Audio Controller                                     | 8        | 0.74%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 8        | 0.74%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 8        | 0.74%   |
| Nvidia MCP61 High Definition Audio                                         | 7        | 0.65%   |
| Nvidia GM206 High Definition Audio Controller                              | 7        | 0.65%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID             | 6        | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 122      | 16.92%  |
| Unknown                      | 100      | 13.87%  |
| Samsung Electronics          | 84       | 11.65%  |
| SK hynix                     | 79       | 10.96%  |
| Crucial                      | 48       | 6.66%   |
| Corsair                      | 47       | 6.52%   |
| Micron Technology            | 39       | 5.41%   |
| G.Skill                      | 33       | 4.58%   |
| Nanya Technology             | 17       | 2.36%   |
| A-DATA Technology            | 15       | 2.08%   |
| Team                         | 12       | 1.66%   |
| Unknown                      | 12       | 1.66%   |
| Ramaxel Technology           | 10       | 1.39%   |
| Patriot                      | 10       | 1.39%   |
| GOODRAM                      | 8        | 1.11%   |
| AMD                          | 8        | 1.11%   |
| Transcend                    | 5        | 0.69%   |
| Unknown (0x0E9D)             | 4        | 0.55%   |
| Silicon Power                | 4        | 0.55%   |
| Elpida                       | 4        | 0.55%   |
| Patriot Memory (PDP Systems) | 3        | 0.42%   |
| Golden Empire                | 3        | 0.42%   |
| Wilk                         | 2        | 0.28%   |
| Unknown (ABCD)               | 2        | 0.28%   |
| Unifosa                      | 2        | 0.28%   |
| Teikon                       | 2        | 0.28%   |
| Red Hat                      | 2        | 0.28%   |
| Qimonda                      | 2        | 0.28%   |
| PNY                          | 2        | 0.28%   |
| Kingmax                      | 2        | 0.28%   |
| GeIL                         | 2        | 0.28%   |
| Essencore                    | 2        | 0.28%   |
| Apacer                       | 2        | 0.28%   |
| Unknown (89F7)               | 1        | 0.14%   |
| Unknown (0x7FFF)             | 1        | 0.14%   |
| Unknown (0x0B45)             | 1        | 0.14%   |
| Toshiba                      | 1        | 0.14%   |
| Timetec                      | 1        | 0.14%   |
| Teclast                      | 1        | 0.14%   |
| TakeMS                       | 1        | 0.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Unknown                                                            | 12       | 1.48%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                               | 9        | 1.11%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                               | 8        | 0.99%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                           | 7        | 0.86%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM 1600MT/s                     | 7        | 0.86%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s                 | 7        | 0.86%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                | 6        | 0.74%   |
| Unknown RAM Module 1GB DIMM                                        | 6        | 0.74%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                          | 6        | 0.74%   |
| Unknown RAM Module 2GB DIMM SDRAM                                  | 5        | 0.62%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s               | 5        | 0.62%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1800MT/s                | 5        | 0.62%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s                | 5        | 0.62%   |
| Unknown RAM Module 4GB DIMM SDRAM                                  | 4        | 0.49%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                          | 4        | 0.49%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                          | 4        | 0.49%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                               | 4        | 0.49%   |
| Unknown (0x0E9D) RAM KINSOTIN16GB2666MHZ 16GB SODIMM DDR4 2667MT/s | 4        | 0.49%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s               | 4        | 0.49%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s               | 4        | 0.49%   |
| SK hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2667MT/s               | 4        | 0.49%   |
| Samsung RAM M4 70T5663RZ3-CE6 2GB SODIMM DDR 667MT/s               | 4        | 0.49%   |
| Samsung RAM M378B5773DH0-CH9 2048MB DIMM DDR3 1333MT/s             | 4        | 0.49%   |
| Samsung RAM M378B5173DB0-CK0 4096MB DIMM DDR3 1600MT/s             | 4        | 0.49%   |
| Samsung RAM M378B1G73EB0-CK0 8GB DIMM DDR3 1600MT/s                | 4        | 0.49%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                  | 4        | 0.49%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                          | 3        | 0.37%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                           | 3        | 0.37%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                               | 3        | 0.37%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                          | 3        | 0.37%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s                 | 3        | 0.37%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s               | 3        | 0.37%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s               | 3        | 0.37%   |
| SK hynix RAM HMA851U6AFR6N-UH 4GB DIMM DDR4 2400MT/s               | 3        | 0.37%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s               | 3        | 0.37%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s                | 3        | 0.37%   |
| Samsung RAM M378B5273DH0-CK0 4096MB DIMM DDR3 2200MT/s             | 3        | 0.37%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s                | 3        | 0.37%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s                | 3        | 0.37%   |
| Kingston RAM 99P5474-013.A00LF 4GB DIMM DDR3 1600MT/s              | 3        | 0.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 251      | 40.55%  |
| DDR3    | 227      | 36.67%  |
| Unknown | 45       | 7.27%   |
| DDR2    | 36       | 5.82%   |
| SDRAM   | 29       | 4.68%   |
| DDR5    | 12       | 1.94%   |
| DDR     | 11       | 1.78%   |
| LPDDR4  | 4        | 0.65%   |
| RAM     | 2        | 0.32%   |
| DRAM    | 2        | 0.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 558      | 92.08%  |
| SODIMM       | 46       | 7.59%   |
| Row Of Chips | 1        | 0.17%   |
| RIMM         | 1        | 0.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 245      | 35.66%  |
| 4096  | 200      | 29.11%  |
| 2048  | 107      | 15.57%  |
| 16384 | 74       | 10.77%  |
| 1024  | 35       | 5.09%   |
| 32768 | 20       | 2.91%   |
| 512   | 4        | 0.58%   |
| 49152 | 1        | 0.15%   |
| 12536 | 1        | 0.15%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 144      | 20.84%  |
| 1333    | 96       | 13.89%  |
| 3200    | 56       | 8.1%    |
| 2400    | 45       | 6.51%   |
| 2667    | 44       | 6.37%   |
| 2133    | 32       | 4.63%   |
| 800     | 29       | 4.2%    |
| 3600    | 25       | 3.62%   |
| 667     | 24       | 3.47%   |
| Unknown | 24       | 3.47%   |
| 1800    | 13       | 1.88%   |
| 3400    | 11       | 1.59%   |
| 2666    | 10       | 1.45%   |
| 3733    | 9        | 1.3%    |
| 3000    | 9        | 1.3%    |
| 1866    | 9        | 1.3%    |
| 2933    | 7        | 1.01%   |
| 1867    | 7        | 1.01%   |
| 4000    | 5        | 0.72%   |
| 3800    | 5        | 0.72%   |
| 3466    | 5        | 0.72%   |
| 1066    | 5        | 0.72%   |
| 5200    | 4        | 0.58%   |
| 3266    | 4        | 0.58%   |
| 3066    | 4        | 0.58%   |
| 400     | 4        | 0.58%   |
| 333     | 4        | 0.58%   |
| 6000    | 3        | 0.43%   |
| 5600    | 3        | 0.43%   |
| 3500    | 3        | 0.43%   |
| 2200    | 3        | 0.43%   |
| 2000    | 3        | 0.43%   |
| 1334    | 3        | 0.43%   |
| 3933    | 2        | 0.29%   |
| 3666    | 2        | 0.29%   |
| 3534    | 2        | 0.29%   |
| 3333    | 2        | 0.29%   |
| 3133    | 2        | 0.29%   |
| 2800    | 2        | 0.29%   |
| 2048    | 2        | 0.29%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 12       | 32.43%  |
| Canon               | 8        | 21.62%  |
| Brother Industries  | 8        | 21.62%  |
| Seiko Epson         | 4        | 10.81%  |
| Samsung Electronics | 1        | 2.7%    |
| Prolific Technology | 1        | 2.7%    |
| Pantum              | 1        | 2.7%    |
| Kyocera             | 1        | 2.7%    |
| Apple               | 1        | 2.7%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Seiko Epson ET-2820 Series         | 2        | 5.41%   |
| HP LaserJet 1018                   | 2        | 5.41%   |
| Canon PIXMA MX490 Series           | 2        | 5.41%   |
| Canon CanoScan LiDE 300            | 2        | 5.41%   |
| Seiko Epson L6270 Series           | 1        | 2.7%    |
| Seiko Epson L3150 Series           | 1        | 2.7%    |
| Samsung M2070 Series               | 1        | 2.7%    |
| Prolific PL2305 Parallel Port      | 1        | 2.7%    |
| Pantum M7100DN series              | 1        | 2.7%    |
| Kyocera FS-1116MFP                 | 1        | 2.7%    |
| HP LaserJet M402dn                 | 1        | 2.7%    |
| HP HP Laser 107w                   | 1        | 2.7%    |
| HP ENVY 4520 series                | 1        | 2.7%    |
| HP DeskJet F4200 series            | 1        | 2.7%    |
| HP DeskJet 6940 series             | 1        | 2.7%    |
| HP DeskJet 4670 series             | 1        | 2.7%    |
| HP DeskJet 3700 series             | 1        | 2.7%    |
| HP DeskJet 2700 series             | 1        | 2.7%    |
| HP DeskJet 2620 All-in-One Printer | 1        | 2.7%    |
| HP Deskjet 1050 J410               | 1        | 2.7%    |
| Canon TS6400 series                | 1        | 2.7%    |
| Canon Pro9000II series             | 1        | 2.7%    |
| Canon PRO-100 series               | 1        | 2.7%    |
| Canon PIXMA MG3600 Series          | 1        | 2.7%    |
| Brother MFC-J480DW                 | 1        | 2.7%    |
| Brother MFC-J1010DW                | 1        | 2.7%    |
| Brother HL-L2375DW series          | 1        | 2.7%    |
| Brother HL-2270DW Laser Printer    | 1        | 2.7%    |
| Brother HL-2140 series             | 1        | 2.7%    |
| Brother HL-1110 series             | 1        | 2.7%    |
| Brother DCP-L2510D series          | 1        | 2.7%    |
| Brother DCP-1610W                  | 1        | 2.7%    |
| Apple Gamesir-G3v 1.00             | 1        | 2.7%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 3        | 75%     |
| Ultima Electronics | 1        | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 110                                                               | 2        | 50%     |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1        | 25%     |
| Canon CanoScan LiDE 210                                                               | 1        | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 29       | 41.43%  |
| Realtek Semiconductor         | 5        | 7.14%   |
| Microsoft                     | 5        | 7.14%   |
| Microdia                      | 4        | 5.71%   |
| Sunplus Innovation Technology | 3        | 4.29%   |
| Chicony Electronics           | 3        | 4.29%   |
| Samsung Electronics           | 2        | 2.86%   |
| Linux Foundation              | 2        | 2.86%   |
| Lenovo                        | 2        | 2.86%   |
| Jieli Technology              | 2        | 2.86%   |
| GEMBIRD                       | 2        | 2.86%   |
| eMeet                         | 2        | 2.86%   |
| Z-Star Microelectronics       | 1        | 1.43%   |
| Novatek Microelectronics      | 1        | 1.43%   |
| Netchip Technology            | 1        | 1.43%   |
| Generalplus Technology        | 1        | 1.43%   |
| Cubeternet                    | 1        | 1.43%   |
| Creative Technology           | 1        | 1.43%   |
| Aveo Technology               | 1        | 1.43%   |
| Asuscom Network               | 1        | 1.43%   |
| Alcor Micro                   | 1        | 1.43%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Logitech Webcam C270                       | 9        | 12.68%  |
| Logitech HD Pro Webcam C920                | 7        | 9.86%   |
| Samsung Galaxy series, misc. (MTP mode)    | 2        | 2.82%   |
| Realtek USB Camera                         | 2        | 2.82%   |
| Microsoft LifeCam VX-5000                  | 2        | 2.82%   |
| Logitech Webcam C310                       | 2        | 2.82%   |
| Linux Foundation EEM Gadget                | 2        | 2.82%   |
| Jieli USB PHY 2.0                          | 2        | 2.82%   |
| Z-Star Lenovo ThinkCentre Web Camera       | 1        | 1.41%   |
| Sunplus USB Camera                         | 1        | 1.41%   |
| Sunplus Full HD webcam                     | 1        | 1.41%   |
| Sunplus DICOTA 4K                          | 1        | 1.41%   |
| Realtek Webcam                             | 1        | 1.41%   |
| Realtek Thronmax Webcam Mic                | 1        | 1.41%   |
| Realtek Lanseyaoji                         | 1        | 1.41%   |
| Realtek FULL HD 1080P Webcam               | 1        | 1.41%   |
| Novatek HP High Definition 2MP Webcam      | 1        | 1.41%   |
| Netchip Nuroum V11                         | 1        | 1.41%   |
| Microsoft Xbox NUI Camera                  | 1        | 1.41%   |
| Microsoft LifeCam VX-700                   | 1        | 1.41%   |
| Microsoft LifeCam Cinema                   | 1        | 1.41%   |
| Microdia Streaming Camera W8GS             | 1        | 1.41%   |
| Microdia Sonix USB 2.0 Camera              | 1        | 1.41%   |
| Microdia NEXIGO HD Webcam                  | 1        | 1.41%   |
| Microdia Integrated Camera                 | 1        | 1.41%   |
| Logitech Webcam C200                       | 1        | 1.41%   |
| Logitech Webcam C170                       | 1        | 1.41%   |
| Logitech Webcam C110                       | 1        | 1.41%   |
| Logitech StreamCam                         | 1        | 1.41%   |
| Logitech QuickCam Pro for Notebooks        | 1        | 1.41%   |
| Logitech QuickCam Pro 9000                 | 1        | 1.41%   |
| Logitech QuickCam E 3500                   | 1        | 1.41%   |
| Logitech QuickCam Communicate Deluxe/S7500 | 1        | 1.41%   |
| Logitech HD Webcam C510                    | 1        | 1.41%   |
| Logitech CrystalCam                        | 1        | 1.41%   |
| Logitech BRIO Ultra HD Webcam              | 1        | 1.41%   |
| Lenovo Lenovo FHD Webcam Audio             | 1        | 1.41%   |
| Lenovo Lenovo 500 RGB Camera               | 1        | 1.41%   |
| Generalplus GENERAL WEBCAM                 | 1        | 1.41%   |
| GEMBIRD USB2.0 PC CAMERA                   | 1        | 1.41%   |

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
| 0     | 565      | 91.72%  |
| 1     | 48       | 7.79%   |
| 2     | 2        | 0.32%   |
| 3     | 1        | 0.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 35       | 66.04%  |
| Multimedia controller    | 6        | 11.32%  |
| Unassigned class         | 5        | 9.43%   |
| Net/wireless             | 2        | 3.77%   |
| Communication controller | 2        | 3.77%   |
| Network                  | 1        | 1.89%   |
| Camera                   | 1        | 1.89%   |
| Bluetooth                | 1        | 1.89%   |

