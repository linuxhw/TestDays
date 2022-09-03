Zorin 16 - Tested Hardware & Statistics (Desktops)
--------------------------------------------------

A project to collect tested hardware configurations for Zorin 16.

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

Total: 1026

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | MS-B9201                    | [7bbae05d63](https://linux-hardware.org/?probe=7bbae05d63) | Sep 01, 2022 |
| MSI           | MS-B9201                    | [0d04798699](https://linux-hardware.org/?probe=0d04798699) | Sep 01, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [f4d5b9fc69](https://linux-hardware.org/?probe=f4d5b9fc69) | Aug 31, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [82cda7dfe9](https://linux-hardware.org/?probe=82cda7dfe9) | Aug 31, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [194290f42c](https://linux-hardware.org/?probe=194290f42c) | Aug 31, 2022 |
| MSI           | H410M PRO                   | [e1184c4522](https://linux-hardware.org/?probe=e1184c4522) | Aug 31, 2022 |
| ASUSTek       | Benicia                     | [13454a57f9](https://linux-hardware.org/?probe=13454a57f9) | Aug 31, 2022 |
| Dell          | 0GXM1W A00                  | [b358b1d32b](https://linux-hardware.org/?probe=b358b1d32b) | Aug 31, 2022 |
| HP            | 2B38                        | [9170225d70](https://linux-hardware.org/?probe=9170225d70) | Aug 30, 2022 |
| JGINYUE       | B85M VH PLUS V1.0           | [8712171422](https://linux-hardware.org/?probe=8712171422) | Aug 30, 2022 |
| Gigabyte      | H61M-D2H-USB3               | [eb74fdbbbc](https://linux-hardware.org/?probe=eb74fdbbbc) | Aug 30, 2022 |
| Dell          | 0R092H                      | [85871600b3](https://linux-hardware.org/?probe=85871600b3) | Aug 30, 2022 |
| JGINYUE       | B85M VH PLUS V1.0           | [f065870080](https://linux-hardware.org/?probe=f065870080) | Aug 30, 2022 |
| MSI           | B250M PRO-VD                | [d462e3b9d0](https://linux-hardware.org/?probe=d462e3b9d0) | Aug 29, 2022 |
| ASRock        | Z170 Pro4                   | [eaa574481f](https://linux-hardware.org/?probe=eaa574481f) | Aug 29, 2022 |
| HP            | 339A                        | [7338bebb05](https://linux-hardware.org/?probe=7338bebb05) | Aug 28, 2022 |
| ASRock        | H61M-DGS                    | [023204fa1f](https://linux-hardware.org/?probe=023204fa1f) | Aug 28, 2022 |
| WIPRO         | G31T-M                      | [51cea718eb](https://linux-hardware.org/?probe=51cea718eb) | Aug 28, 2022 |
| BESSTAR Te... | HM90                        | [134adccc85](https://linux-hardware.org/?probe=134adccc85) | Aug 27, 2022 |
| ASRock        | B550M Pro4                  | [9a05044c38](https://linux-hardware.org/?probe=9a05044c38) | Aug 27, 2022 |
| Dell          | 0T656F A01                  | [d1bb410d06](https://linux-hardware.org/?probe=d1bb410d06) | Aug 26, 2022 |
| ASUSTek       | SABERTOOTH Z87              | [02072aee33](https://linux-hardware.org/?probe=02072aee33) | Aug 25, 2022 |
| Gigabyte      | 970-GAMING                  | [dad1ede2be](https://linux-hardware.org/?probe=dad1ede2be) | Aug 25, 2022 |
| BESSTAR Te... | HM90                        | [8f13ff6ebd](https://linux-hardware.org/?probe=8f13ff6ebd) | Aug 24, 2022 |
| Gigabyte      | 970-GAMING                  | [faa79b7d62](https://linux-hardware.org/?probe=faa79b7d62) | Aug 24, 2022 |
| HP            | 2AFB                        | [ea3ce3f8dd](https://linux-hardware.org/?probe=ea3ce3f8dd) | Aug 24, 2022 |
| ASUSTek       | H81M-A/BR                   | [b9ac5d4051](https://linux-hardware.org/?probe=b9ac5d4051) | Aug 23, 2022 |
| Gigabyte      | H61M-D2H-USB3               | [eae2c82e26](https://linux-hardware.org/?probe=eae2c82e26) | Aug 23, 2022 |
| MSI           | 2AE0                        | [beb918fbc9](https://linux-hardware.org/?probe=beb918fbc9) | Aug 23, 2022 |
| HP            | 2AF7                        | [29826a67d9](https://linux-hardware.org/?probe=29826a67d9) | Aug 22, 2022 |
| HP            | 2AF7                        | [fbc1710ad8](https://linux-hardware.org/?probe=fbc1710ad8) | Aug 22, 2022 |
| MSI           | X99S GAMING 7               | [f729654c4a](https://linux-hardware.org/?probe=f729654c4a) | Aug 22, 2022 |
| ASUSTek       | J1800I-C/BR                 | [f2f76737ad](https://linux-hardware.org/?probe=f2f76737ad) | Aug 22, 2022 |
| Dell          | 0C27VV A03                  | [4e894e1897](https://linux-hardware.org/?probe=4e894e1897) | Aug 21, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [4dc3a452d9](https://linux-hardware.org/?probe=4dc3a452d9) | Aug 19, 2022 |
| ASUSTek       | ProArt B660-CREATOR D4      | [0b9e6d6ad9](https://linux-hardware.org/?probe=0b9e6d6ad9) | Aug 19, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [6865f5ed0b](https://linux-hardware.org/?probe=6865f5ed0b) | Aug 19, 2022 |
| BESSTAR Te... | UM350                       | [c7bb6b56fb](https://linux-hardware.org/?probe=c7bb6b56fb) | Aug 18, 2022 |
| ASUSTek       | PRIME Z390-A                | [e03daeba5f](https://linux-hardware.org/?probe=e03daeba5f) | Aug 18, 2022 |
| ASRock        | H61M-DGS                    | [ffb9dcb065](https://linux-hardware.org/?probe=ffb9dcb065) | Aug 18, 2022 |
| ASUSTek       | P8B75-V                     | [a37b0b7e18](https://linux-hardware.org/?probe=a37b0b7e18) | Aug 18, 2022 |
| ASRock        | B550M Pro4                  | [ab3425dd99](https://linux-hardware.org/?probe=ab3425dd99) | Aug 17, 2022 |
| ASUSTek       | PRIME H370-A                | [da477254e7](https://linux-hardware.org/?probe=da477254e7) | Aug 16, 2022 |
| Gigabyte      | M4HM87P-00                  | [5bb7e42eae](https://linux-hardware.org/?probe=5bb7e42eae) | Aug 16, 2022 |
| ASUSTek       | J1800I-C/BR                 | [01beed2be8](https://linux-hardware.org/?probe=01beed2be8) | Aug 15, 2022 |
| HP            | 339A                        | [c3e5458c9a](https://linux-hardware.org/?probe=c3e5458c9a) | Aug 15, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [08fa90340d](https://linux-hardware.org/?probe=08fa90340d) | Aug 14, 2022 |
| MAXSUN        | MS-TZZ A520M                | [aa844d0dce](https://linux-hardware.org/?probe=aa844d0dce) | Aug 14, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [58d97fbc16](https://linux-hardware.org/?probe=58d97fbc16) | Aug 14, 2022 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | [0c80c167e4](https://linux-hardware.org/?probe=0c80c167e4) | Aug 13, 2022 |
| ASUSTek       | A88X-PRO                    | [399f7ec1da](https://linux-hardware.org/?probe=399f7ec1da) | Aug 12, 2022 |
| ASUSTek       | P5GC-MX                     | [346a48750b](https://linux-hardware.org/?probe=346a48750b) | Aug 12, 2022 |
| ASUSTek       | J1800I-C/BR                 | [41cd4b02f1](https://linux-hardware.org/?probe=41cd4b02f1) | Aug 11, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [687375ec7c](https://linux-hardware.org/?probe=687375ec7c) | Aug 11, 2022 |
| ASRock        | H61M-DGS                    | [7005dd1f5f](https://linux-hardware.org/?probe=7005dd1f5f) | Aug 09, 2022 |
| HP            | 1589                        | [0519e046d2](https://linux-hardware.org/?probe=0519e046d2) | Aug 08, 2022 |
| HP            | 18E7                        | [7dd119f85e](https://linux-hardware.org/?probe=7dd119f85e) | Aug 08, 2022 |
| MSI           | Z97 GAMING 5                | [7f1e38b57b](https://linux-hardware.org/?probe=7f1e38b57b) | Aug 07, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [ab0da3a7ec](https://linux-hardware.org/?probe=ab0da3a7ec) | Aug 07, 2022 |
| ASUSTek       | P9X79 LE                    | [f8a36826db](https://linux-hardware.org/?probe=f8a36826db) | Aug 07, 2022 |
| ASUSTek       | ET2701I-W8                  | [5f9c4b50db](https://linux-hardware.org/?probe=5f9c4b50db) | Aug 07, 2022 |
| MP            | MS-7848                     | [8d4402905d](https://linux-hardware.org/?probe=8d4402905d) | Aug 06, 2022 |
| Lenovo        | ThinkCentre M57 6087YD2     | [9ad2c07771](https://linux-hardware.org/?probe=9ad2c07771) | Aug 06, 2022 |
| Pegatron      | Benicia                     | [d67d37efce](https://linux-hardware.org/?probe=d67d37efce) | Aug 05, 2022 |
| HP            | 339A                        | [53a3b6e834](https://linux-hardware.org/?probe=53a3b6e834) | Aug 05, 2022 |
| HP            | 339A                        | [8883c2cb6c](https://linux-hardware.org/?probe=8883c2cb6c) | Aug 05, 2022 |
| Gigabyte      | Z77-D3H                     | [2fd7410925](https://linux-hardware.org/?probe=2fd7410925) | Aug 04, 2022 |
| Gigabyte      | G1.Sniper Z97               | [6e5ce364b3](https://linux-hardware.org/?probe=6e5ce364b3) | Aug 03, 2022 |
| LORD ELECT... | GM965 Series                | [b60dce21e7](https://linux-hardware.org/?probe=b60dce21e7) | Aug 03, 2022 |
| Lenovo        | SDK0J40700 WIN              | [299ac7a8ff](https://linux-hardware.org/?probe=299ac7a8ff) | Aug 03, 2022 |
| HP            | 1589                        | [738de77596](https://linux-hardware.org/?probe=738de77596) | Aug 03, 2022 |
| MSI           | Boston                      | [32021cecf7](https://linux-hardware.org/?probe=32021cecf7) | Aug 03, 2022 |
| ASUSTek       | P7H55-M LX                  | [ad8af5c718](https://linux-hardware.org/?probe=ad8af5c718) | Aug 02, 2022 |
| ASUSTek       | P7H55-M LX                  | [b4e172e88b](https://linux-hardware.org/?probe=b4e172e88b) | Aug 02, 2022 |
| ASRock        | B450 Pro4                   | [aacc138812](https://linux-hardware.org/?probe=aacc138812) | Aug 02, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [cc8b9aa8f6](https://linux-hardware.org/?probe=cc8b9aa8f6) | Aug 01, 2022 |
| ASUSTek       | PRIME X570-P                | [405a75cb1d](https://linux-hardware.org/?probe=405a75cb1d) | Aug 01, 2022 |
| Gigabyte      | B450M DS3H-CF               | [7c68dbe47e](https://linux-hardware.org/?probe=7c68dbe47e) | Aug 01, 2022 |
| Gigabyte      | B450M DS3H-CF               | [6532751d00](https://linux-hardware.org/?probe=6532751d00) | Aug 01, 2022 |
| Dell          | 0T656F A01                  | [02ae993867](https://linux-hardware.org/?probe=02ae993867) | Jul 31, 2022 |
| Gigabyte      | Z77-D3H                     | [a954bc2f31](https://linux-hardware.org/?probe=a954bc2f31) | Jul 31, 2022 |
| ASRock        | Z170 Pro4                   | [e8dba6ab7e](https://linux-hardware.org/?probe=e8dba6ab7e) | Jul 31, 2022 |
| HP            | 82F2                        | [0c2d091c2e](https://linux-hardware.org/?probe=0c2d091c2e) | Jul 31, 2022 |
| Supermicro    | C7Q67 V1.01                 | [15508d1eff](https://linux-hardware.org/?probe=15508d1eff) | Jul 30, 2022 |
| Lenovo        | SDK0J40700 WIN              | [f50872e350](https://linux-hardware.org/?probe=f50872e350) | Jul 29, 2022 |
| Packard Be... | H57M01                      | [55e1536ab6](https://linux-hardware.org/?probe=55e1536ab6) | Jul 29, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [2bc22894c8](https://linux-hardware.org/?probe=2bc22894c8) | Jul 29, 2022 |
| Packard Be... | H57M01                      | [4789405230](https://linux-hardware.org/?probe=4789405230) | Jul 29, 2022 |
| Lenovo        | SDK0J40700 WIN              | [6d95a05ee7](https://linux-hardware.org/?probe=6d95a05ee7) | Jul 28, 2022 |
| ASRock        | Z170 Pro4                   | [73c8bc2ae1](https://linux-hardware.org/?probe=73c8bc2ae1) | Jul 28, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [e214df8838](https://linux-hardware.org/?probe=e214df8838) | Jul 27, 2022 |
| Gigabyte      | B450 AORUS M                | [f9b0fe48d6](https://linux-hardware.org/?probe=f9b0fe48d6) | Jul 27, 2022 |
| ASUSTek       | PRIME A520M-K               | [cea12b9c9c](https://linux-hardware.org/?probe=cea12b9c9c) | Jul 27, 2022 |
| ASRock        | Z170 Pro4                   | [876c60188f](https://linux-hardware.org/?probe=876c60188f) | Jul 26, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [e33f8c0a93](https://linux-hardware.org/?probe=e33f8c0a93) | Jul 26, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [a059cf305d](https://linux-hardware.org/?probe=a059cf305d) | Jul 25, 2022 |
| Lenovo        | SDK0J40700 WIN              | [96d6480781](https://linux-hardware.org/?probe=96d6480781) | Jul 25, 2022 |
| ASUSTek       | A88X-PRO                    | [c8e578f98f](https://linux-hardware.org/?probe=c8e578f98f) | Jul 24, 2022 |
| ASUSTek       | A88X-PRO                    | [48e39039fc](https://linux-hardware.org/?probe=48e39039fc) | Jul 24, 2022 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | [aa952e11aa](https://linux-hardware.org/?probe=aa952e11aa) | Jul 24, 2022 |
| Dell          | 03NVJ6 A03                  | [9c0bb64bd9](https://linux-hardware.org/?probe=9c0bb64bd9) | Jul 24, 2022 |
| ASUSTek       | CROSSHAIR II FORMULA        | [aa2242c51f](https://linux-hardware.org/?probe=aa2242c51f) | Jul 23, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | [177a181771](https://linux-hardware.org/?probe=177a181771) | Jul 23, 2022 |
| Supermicro    | C7Q67 V1.01                 | [722f3df811](https://linux-hardware.org/?probe=722f3df811) | Jul 23, 2022 |
| Dell          | 0FDY5C A00                  | [f5d81fb635](https://linux-hardware.org/?probe=f5d81fb635) | Jul 23, 2022 |
| Dell          | 0FDY5C A00                  | [83cf5f7085](https://linux-hardware.org/?probe=83cf5f7085) | Jul 23, 2022 |
| Gigabyte      | M68M-S2P                    | [7d4ba4168a](https://linux-hardware.org/?probe=7d4ba4168a) | Jul 22, 2022 |
| MSI           | Z97 GAMING 5                | [89e0889e94](https://linux-hardware.org/?probe=89e0889e94) | Jul 21, 2022 |
| Dell          | 09KPNV A00                  | [711546ab63](https://linux-hardware.org/?probe=711546ab63) | Jul 21, 2022 |
| Foxconn       | 2AAF                        | [b97dc9fd47](https://linux-hardware.org/?probe=b97dc9fd47) | Jul 20, 2022 |
| MSI           | B75MA-P45                   | [89af63cf6f](https://linux-hardware.org/?probe=89af63cf6f) | Jul 19, 2022 |
| Gigabyte      | G1.Sniper Z97               | [75a19b4509](https://linux-hardware.org/?probe=75a19b4509) | Jul 17, 2022 |
| Dell          | 09KPNV A00                  | [c47ecbd03f](https://linux-hardware.org/?probe=c47ecbd03f) | Jul 16, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [0cf64c41f0](https://linux-hardware.org/?probe=0cf64c41f0) | Jul 16, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [e5fed36e22](https://linux-hardware.org/?probe=e5fed36e22) | Jul 15, 2022 |
| Dell          | 0C27VV A01                  | [56bd2a162b](https://linux-hardware.org/?probe=56bd2a162b) | Jul 15, 2022 |
| Dell          | 0C27VV A01                  | [ccc3bc2a39](https://linux-hardware.org/?probe=ccc3bc2a39) | Jul 15, 2022 |
| Intel         | X79 V2.72B                  | [f244f6157b](https://linux-hardware.org/?probe=f244f6157b) | Jul 15, 2022 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [66efd060ca](https://linux-hardware.org/?probe=66efd060ca) | Jul 14, 2022 |
| Unknown       | Intel X79                   | [b0bb64b9ea](https://linux-hardware.org/?probe=b0bb64b9ea) | Jul 13, 2022 |
| Gigabyte      | H87M-D3H                    | [5056c4f640](https://linux-hardware.org/?probe=5056c4f640) | Jul 13, 2022 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | [c90a0cbab7](https://linux-hardware.org/?probe=c90a0cbab7) | Jul 13, 2022 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | [87fa08ea59](https://linux-hardware.org/?probe=87fa08ea59) | Jul 13, 2022 |
| System76      | Thelio thelio-r2            | [2d990d7afe](https://linux-hardware.org/?probe=2d990d7afe) | Jul 12, 2022 |
| HP            | 3398                        | [1b964004d9](https://linux-hardware.org/?probe=1b964004d9) | Jul 12, 2022 |
| ASUSTek       | V-P8H61E                    | [f8e5b72d1c](https://linux-hardware.org/?probe=f8e5b72d1c) | Jul 12, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | [42b248f049](https://linux-hardware.org/?probe=42b248f049) | Jul 11, 2022 |
| Lenovo        | ThinkCentre M91 7516AD1     | [19660ae71a](https://linux-hardware.org/?probe=19660ae71a) | Jul 11, 2022 |
| OEM_MB        | NARRA3                      | [845bdfd72c](https://linux-hardware.org/?probe=845bdfd72c) | Jul 11, 2022 |
| Dell          | 0J3C2F A00                  | [36252f70d6](https://linux-hardware.org/?probe=36252f70d6) | Jul 10, 2022 |
| Dell          | 0J3C2F A00                  | [e3197762a9](https://linux-hardware.org/?probe=e3197762a9) | Jul 10, 2022 |
| Pegatron      | Benicia                     | [2360476ad3](https://linux-hardware.org/?probe=2360476ad3) | Jul 09, 2022 |
| Gigabyte      | H110M-A-CF                  | [42335e5c5c](https://linux-hardware.org/?probe=42335e5c5c) | Jul 09, 2022 |
| HP            | 18E4                        | [bf615fe0ae](https://linux-hardware.org/?probe=bf615fe0ae) | Jul 08, 2022 |
| Gigabyte      | Z97X-UD3H-CF                | [b7ed1ecdf2](https://linux-hardware.org/?probe=b7ed1ecdf2) | Jul 08, 2022 |
| Gigabyte      | EP45-UD3P                   | [9118f548bb](https://linux-hardware.org/?probe=9118f548bb) | Jul 08, 2022 |
| Acer          | E91M                        | [4e55aacdd7](https://linux-hardware.org/?probe=4e55aacdd7) | Jul 06, 2022 |
| MSI           | Boston                      | [3dfcd01115](https://linux-hardware.org/?probe=3dfcd01115) | Jul 06, 2022 |
| Gigabyte      | H77N-WIFI                   | [dc12f11117](https://linux-hardware.org/?probe=dc12f11117) | Jul 05, 2022 |
| Biostar       | P4M90-M7A Ver:1.0           | [0567d5e337](https://linux-hardware.org/?probe=0567d5e337) | Jul 05, 2022 |
| OEM           | G41 775 ICH7 8712           | [4f82c838cb](https://linux-hardware.org/?probe=4f82c838cb) | Jul 04, 2022 |
| HP            | 8350                        | [39a8a75ebe](https://linux-hardware.org/?probe=39a8a75ebe) | Jul 03, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [31a8bd72d6](https://linux-hardware.org/?probe=31a8bd72d6) | Jul 02, 2022 |
| Foxconn       | 2AB1                        | [83a3a5794d](https://linux-hardware.org/?probe=83a3a5794d) | Jul 02, 2022 |
| Foxconn       | 2AB1                        | [7b7c8244af](https://linux-hardware.org/?probe=7b7c8244af) | Jul 02, 2022 |
| Gigabyte      | B360M HD3                   | [b35e9f3e5c](https://linux-hardware.org/?probe=b35e9f3e5c) | Jun 28, 2022 |
| Dell          | 0U880P A00                  | [e14832f09c](https://linux-hardware.org/?probe=e14832f09c) | Jun 26, 2022 |
| Gigabyte      | B450 AORUS M                | [6262e08c1f](https://linux-hardware.org/?probe=6262e08c1f) | Jun 26, 2022 |
| Pegatron      | IPPSB-DB                    | [a63cdffc5b](https://linux-hardware.org/?probe=a63cdffc5b) | Jun 26, 2022 |
| Dell          | 08NPPY A00                  | [3dc935ecb1](https://linux-hardware.org/?probe=3dc935ecb1) | Jun 26, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [c78b132d02](https://linux-hardware.org/?probe=c78b132d02) | Jun 26, 2022 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | [b232a434fd](https://linux-hardware.org/?probe=b232a434fd) | Jun 26, 2022 |
| Gigabyte      | B450 AORUS M                | [0297d9c8c1](https://linux-hardware.org/?probe=0297d9c8c1) | Jun 25, 2022 |
| Gigabyte      | Z77-DS3H                    | [fbde5d214f](https://linux-hardware.org/?probe=fbde5d214f) | Jun 24, 2022 |
| Gigabyte      | EP45-UD3P                   | [05449d9e5c](https://linux-hardware.org/?probe=05449d9e5c) | Jun 24, 2022 |
| MSI           | A75A-G35                    | [9e3dd8051c](https://linux-hardware.org/?probe=9e3dd8051c) | Jun 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | [a24305d670](https://linux-hardware.org/?probe=a24305d670) | Jun 23, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [b21a0caebf](https://linux-hardware.org/?probe=b21a0caebf) | Jun 22, 2022 |
| ASUSTek       | PRIME X570-PRO              | [ecea2bb4ad](https://linux-hardware.org/?probe=ecea2bb4ad) | Jun 22, 2022 |
| Gigabyte      | EX58-UD3R                   | [4014366c8a](https://linux-hardware.org/?probe=4014366c8a) | Jun 21, 2022 |
| Lenovo        | SDK0J40700 WIN              | [82be38e941](https://linux-hardware.org/?probe=82be38e941) | Jun 17, 2022 |
| MSI           | B85M-E45                    | [58c2ff96e3](https://linux-hardware.org/?probe=58c2ff96e3) | Jun 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [85a022001e](https://linux-hardware.org/?probe=85a022001e) | Jun 16, 2022 |
| Dell          | 0X501H A02                  | [b9cb2a1e48](https://linux-hardware.org/?probe=b9cb2a1e48) | Jun 15, 2022 |
| Acer          | Aspire M3970                | [b966120966](https://linux-hardware.org/?probe=b966120966) | Jun 14, 2022 |
| Lenovo        | 3717 SDK0J40709 WIN 3259... | [aa63e13a60](https://linux-hardware.org/?probe=aa63e13a60) | Jun 13, 2022 |
| Lenovo        | 3717 SDK0J40709 WIN 3259... | [ba6786bbe8](https://linux-hardware.org/?probe=ba6786bbe8) | Jun 13, 2022 |
| ASUSTek       | P5GC-MX/1333                | [428eebd42f](https://linux-hardware.org/?probe=428eebd42f) | Jun 13, 2022 |
| MSI           | MEG Z690 UNIFY              | [4e227cff8b](https://linux-hardware.org/?probe=4e227cff8b) | Jun 12, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [2a772cecf4](https://linux-hardware.org/?probe=2a772cecf4) | Jun 12, 2022 |
| ASUSTek       | PRIME B550M-A               | [14b9e721b7](https://linux-hardware.org/?probe=14b9e721b7) | Jun 11, 2022 |
| Dell          | 0XFWHV A00                  | [4102e98034](https://linux-hardware.org/?probe=4102e98034) | Jun 09, 2022 |
| ASUSTek       | Benicia                     | [4b56f8a972](https://linux-hardware.org/?probe=4b56f8a972) | Jun 08, 2022 |
| Dell          | 0WR7PY A03                  | [902546cb45](https://linux-hardware.org/?probe=902546cb45) | Jun 06, 2022 |
| ASUSTek       | TUF Z270 MARK 2             | [e993e32a56](https://linux-hardware.org/?probe=e993e32a56) | Jun 06, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [07808a7cbf](https://linux-hardware.org/?probe=07808a7cbf) | Jun 05, 2022 |
| HP            | 8350                        | [63a9e40af6](https://linux-hardware.org/?probe=63a9e40af6) | Jun 05, 2022 |
| Biostar       | A68N-2100K                  | [480a4c12b1](https://linux-hardware.org/?probe=480a4c12b1) | Jun 05, 2022 |
| ASRock        | 970 Extreme3                | [d5648a1a95](https://linux-hardware.org/?probe=d5648a1a95) | Jun 04, 2022 |
| MSI           | B85M-G43                    | [097b308b60](https://linux-hardware.org/?probe=097b308b60) | Jun 04, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [94c2c3411a](https://linux-hardware.org/?probe=94c2c3411a) | Jun 04, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [9404638832](https://linux-hardware.org/?probe=9404638832) | Jun 03, 2022 |
| BESSTAR Te... | TL50                        | [0455aba8a3](https://linux-hardware.org/?probe=0455aba8a3) | Jun 03, 2022 |
| HP            | 3029h                       | [d536fb8e36](https://linux-hardware.org/?probe=d536fb8e36) | Jun 03, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [61b90c102c](https://linux-hardware.org/?probe=61b90c102c) | Jun 03, 2022 |
| ASUSTek       | P5E-VM DO                   | [935c03cd63](https://linux-hardware.org/?probe=935c03cd63) | Jun 03, 2022 |
| Biostar       | A78MD                       | [206b04b6d8](https://linux-hardware.org/?probe=206b04b6d8) | Jun 02, 2022 |
| ASUSTek       | P5QL-ASUS-SE                | [5c9f7b1ab9](https://linux-hardware.org/?probe=5c9f7b1ab9) | Jun 02, 2022 |
| ASUSTek       | P5QL-ASUS-SE                | [0e1e2765fc](https://linux-hardware.org/?probe=0e1e2765fc) | Jun 01, 2022 |
| Biostar       | A78MD                       | [49ea0bd0e4](https://linux-hardware.org/?probe=49ea0bd0e4) | Jun 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [951bd2ea8d](https://linux-hardware.org/?probe=951bd2ea8d) | May 31, 2022 |
| Positivo      | POS-PIG41BAG                | [7bfeaeb75b](https://linux-hardware.org/?probe=7bfeaeb75b) | May 31, 2022 |
| Positivo      | POS-PIG41BAG                | [3ca7484fcf](https://linux-hardware.org/?probe=3ca7484fcf) | May 31, 2022 |
| ASUSTek       | PRIME A320M-K               | [d078b8d5dd](https://linux-hardware.org/?probe=d078b8d5dd) | May 30, 2022 |
| Gigabyte      | H410M H V3                  | [1dbf357f4f](https://linux-hardware.org/?probe=1dbf357f4f) | May 30, 2022 |
| Gigabyte      | G1.Sniper Z97               | [2c3ba3123f](https://linux-hardware.org/?probe=2c3ba3123f) | May 29, 2022 |
| ASUSTek       | P7P55D DELUXE               | [ba2d55d308](https://linux-hardware.org/?probe=ba2d55d308) | May 29, 2022 |
| ASRock        | B450 Pro4                   | [fa0b4c98df](https://linux-hardware.org/?probe=fa0b4c98df) | May 29, 2022 |
| Dell          | 0HN7XN A01                  | [9ebd09a280](https://linux-hardware.org/?probe=9ebd09a280) | May 29, 2022 |
| Gigabyte      | F2A58M-DS2                  | [3b95da87e9](https://linux-hardware.org/?probe=3b95da87e9) | May 28, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [4e77d22694](https://linux-hardware.org/?probe=4e77d22694) | May 27, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [1137f80fcd](https://linux-hardware.org/?probe=1137f80fcd) | May 27, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [57dbc86807](https://linux-hardware.org/?probe=57dbc86807) | May 27, 2022 |
| ASUSTek       | H81M-A/BR                   | [5df43d2ecd](https://linux-hardware.org/?probe=5df43d2ecd) | May 26, 2022 |
| Dell          | 088DT1 A01                  | [19d760099e](https://linux-hardware.org/?probe=19d760099e) | May 25, 2022 |
| Dell          | 088DT1 A01                  | [3334efe1e7](https://linux-hardware.org/?probe=3334efe1e7) | May 25, 2022 |
| Intel         | D946GZIS AAD66165-301       | [24c058da74](https://linux-hardware.org/?probe=24c058da74) | May 25, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [6e45ae9f7c](https://linux-hardware.org/?probe=6e45ae9f7c) | May 24, 2022 |
| MSI           | MEG Z390 GODLIKE            | [4249d49f41](https://linux-hardware.org/?probe=4249d49f41) | May 22, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [dffc3ea80a](https://linux-hardware.org/?probe=dffc3ea80a) | May 21, 2022 |
| ASUSTek       | Z97-DELUXE                  | [084bacdad3](https://linux-hardware.org/?probe=084bacdad3) | May 21, 2022 |
| MSI           | Z170A GAMING PRO            | [3a9789ed8a](https://linux-hardware.org/?probe=3a9789ed8a) | May 20, 2022 |
| ASUSTek       | PRIME B550M-A               | [1d5fec86a8](https://linux-hardware.org/?probe=1d5fec86a8) | May 20, 2022 |
| MSI           | 760GM-P21                   | [b6b5e0738c](https://linux-hardware.org/?probe=b6b5e0738c) | May 19, 2022 |
| MSI           | B85M-G43                    | [ef33bf347c](https://linux-hardware.org/?probe=ef33bf347c) | May 18, 2022 |
| Foxconn       | 2AAF                        | [dd1193f7ab](https://linux-hardware.org/?probe=dd1193f7ab) | May 18, 2022 |
| ASUSTek       | H81M-K                      | [c5cdf9ba52](https://linux-hardware.org/?probe=c5cdf9ba52) | May 18, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [2b889fc85b](https://linux-hardware.org/?probe=2b889fc85b) | May 17, 2022 |
| ASUSTek       | G15DK                       | [1df44e40e2](https://linux-hardware.org/?probe=1df44e40e2) | May 17, 2022 |
| Gigabyte      | M61PME-S2P                  | [7ab57b617f](https://linux-hardware.org/?probe=7ab57b617f) | May 17, 2022 |
| Dell          | 0C27VV A01                  | [aea8e14bff](https://linux-hardware.org/?probe=aea8e14bff) | May 17, 2022 |
| Dell          | 0GTK4K A02                  | [fba6de28d9](https://linux-hardware.org/?probe=fba6de28d9) | May 16, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [ebbd363703](https://linux-hardware.org/?probe=ebbd363703) | May 16, 2022 |
| Intel         | D946GZIS AAD66165-301       | [4555cff448](https://linux-hardware.org/?probe=4555cff448) | May 16, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [7fcd8503ab](https://linux-hardware.org/?probe=7fcd8503ab) | May 16, 2022 |
| ASRock        | A88M-G                      | [81d094b2ec](https://linux-hardware.org/?probe=81d094b2ec) | May 15, 2022 |
| ASRock        | A88M-G                      | [8883591354](https://linux-hardware.org/?probe=8883591354) | May 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [0d9d6b919b](https://linux-hardware.org/?probe=0d9d6b919b) | May 15, 2022 |
| ASUSTek       | PRIME H310-PLUS             | [770fbfefd3](https://linux-hardware.org/?probe=770fbfefd3) | May 15, 2022 |
| ASUSTek       | PRIME H310-PLUS             | [8baee6f2e6](https://linux-hardware.org/?probe=8baee6f2e6) | May 14, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | [08ba1e652c](https://linux-hardware.org/?probe=08ba1e652c) | May 14, 2022 |
| Intel         | DH77EB AAG39073-304         | [f45bf21321](https://linux-hardware.org/?probe=f45bf21321) | May 12, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [86d60d0227](https://linux-hardware.org/?probe=86d60d0227) | May 12, 2022 |
| Pegatron      | 2A99h                       | [6a47713af6](https://linux-hardware.org/?probe=6a47713af6) | May 12, 2022 |
| AOpen         | i67QMx-DV R1.00BC1 55MP6... | [151db99970](https://linux-hardware.org/?probe=151db99970) | May 11, 2022 |
| Acer          | Aspire X3990                | [c6753ff37f](https://linux-hardware.org/?probe=c6753ff37f) | May 11, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [8f62053ddd](https://linux-hardware.org/?probe=8f62053ddd) | May 11, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [018c90008f](https://linux-hardware.org/?probe=018c90008f) | May 11, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [b1d977cd69](https://linux-hardware.org/?probe=b1d977cd69) | May 11, 2022 |
| Gigabyte      | EX58-EXTREME                | [b558000bcc](https://linux-hardware.org/?probe=b558000bcc) | May 10, 2022 |
| Dell          | 0DR845                      | [ab501b0efe](https://linux-hardware.org/?probe=ab501b0efe) | May 10, 2022 |
| Gigabyte      | X58A-UD3R                   | [838a99f17a](https://linux-hardware.org/?probe=838a99f17a) | May 10, 2022 |
| Gigabyte      | B365M GAMING HD             | [5590d9a0f3](https://linux-hardware.org/?probe=5590d9a0f3) | May 10, 2022 |
| Dell          | 0GXM1W A02                  | [1606b44e03](https://linux-hardware.org/?probe=1606b44e03) | May 09, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [485a4916ed](https://linux-hardware.org/?probe=485a4916ed) | May 09, 2022 |
| ASRock        | H87M                        | [9c031f1e71](https://linux-hardware.org/?probe=9c031f1e71) | May 09, 2022 |
| Dell          | 0GXM1W A02                  | [bf028580b1](https://linux-hardware.org/?probe=bf028580b1) | May 09, 2022 |
| Gateway       | SX2185                      | [ddb64bc283](https://linux-hardware.org/?probe=ddb64bc283) | May 09, 2022 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [be0cecd40a](https://linux-hardware.org/?probe=be0cecd40a) | May 09, 2022 |
| ASUSTek       | P8H61-M LX                  | [9a00d24f58](https://linux-hardware.org/?probe=9a00d24f58) | May 09, 2022 |
| ASUSTek       | P8H61-M LX                  | [3f3089216f](https://linux-hardware.org/?probe=3f3089216f) | May 09, 2022 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [5c2fec5833](https://linux-hardware.org/?probe=5c2fec5833) | May 08, 2022 |
| Gigabyte      | H410M H V3                  | [c401229392](https://linux-hardware.org/?probe=c401229392) | May 08, 2022 |
| Gigabyte      | X570 GAMING X               | [ffc6dac164](https://linux-hardware.org/?probe=ffc6dac164) | May 07, 2022 |
| Gigabyte      | H410M H V3                  | [4c6f4d04bb](https://linux-hardware.org/?probe=4c6f4d04bb) | May 07, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [79c87fe48c](https://linux-hardware.org/?probe=79c87fe48c) | May 07, 2022 |
| Gigabyte      | X570 GAMING X               | [816a78b4cd](https://linux-hardware.org/?probe=816a78b4cd) | May 06, 2022 |
| ASUSTek       | 2A73h                       | [458bf998ee](https://linux-hardware.org/?probe=458bf998ee) | May 06, 2022 |
| Intel         | H55                         | [138637d12c](https://linux-hardware.org/?probe=138637d12c) | May 06, 2022 |
| Gigabyte      | G41M-Combo                  | [9940073216](https://linux-hardware.org/?probe=9940073216) | May 05, 2022 |
| Gigabyte      | G41MT-S2                    | [fd9ed9a035](https://linux-hardware.org/?probe=fd9ed9a035) | May 05, 2022 |
| HP            | 1906                        | [6f7f0536a9](https://linux-hardware.org/?probe=6f7f0536a9) | May 05, 2022 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | [31eaff1b28](https://linux-hardware.org/?probe=31eaff1b28) | May 04, 2022 |
| MSI           | B85M-G43                    | [f5deeb2d19](https://linux-hardware.org/?probe=f5deeb2d19) | May 04, 2022 |
| MSI           | Z590 PRO WIFI               | [17aad0bb78](https://linux-hardware.org/?probe=17aad0bb78) | May 03, 2022 |
| HP            | 1906                        | [60ce09d82e](https://linux-hardware.org/?probe=60ce09d82e) | May 03, 2022 |
| Gigabyte      | B365M GAMING HD             | [637890bd75](https://linux-hardware.org/?probe=637890bd75) | May 03, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | [7f9e8dd9f6](https://linux-hardware.org/?probe=7f9e8dd9f6) | May 02, 2022 |
| ASUSTek       | H97I-PLUS                   | [c8e857524b](https://linux-hardware.org/?probe=c8e857524b) | May 01, 2022 |
| ASRock        | B365M-HDV                   | [51b0e7e57f](https://linux-hardware.org/?probe=51b0e7e57f) | May 01, 2022 |
| Dell          | 0M017G A01                  | [653212f53c](https://linux-hardware.org/?probe=653212f53c) | May 01, 2022 |
| HP            | 1791                        | [877270ede6](https://linux-hardware.org/?probe=877270ede6) | Apr 30, 2022 |
| Intel         | DCP847SKE G80890-105        | [45dc47c8aa](https://linux-hardware.org/?probe=45dc47c8aa) | Apr 30, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | [89323fb22d](https://linux-hardware.org/?probe=89323fb22d) | Apr 30, 2022 |
| Foxconn       | 2A92                        | [298326d530](https://linux-hardware.org/?probe=298326d530) | Apr 30, 2022 |
| Foxconn       | 2A92                        | [a710d4a58f](https://linux-hardware.org/?probe=a710d4a58f) | Apr 30, 2022 |
| Gigabyte      | Z68AP-D3                    | [af8b52acd3](https://linux-hardware.org/?probe=af8b52acd3) | Apr 29, 2022 |
| Gigabyte      | P31-ES3G                    | [dc8419dcb3](https://linux-hardware.org/?probe=dc8419dcb3) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [965985d6f4](https://linux-hardware.org/?probe=965985d6f4) | Apr 29, 2022 |
| Lenovo        | ThinkCentre M91p 7052A9G    | [277754d8c1](https://linux-hardware.org/?probe=277754d8c1) | Apr 29, 2022 |
| BESSTAR Te... | HM90                        | [814f90b822](https://linux-hardware.org/?probe=814f90b822) | Apr 28, 2022 |
| Gigabyte      | P31-ES3G                    | [c3df637d15](https://linux-hardware.org/?probe=c3df637d15) | Apr 27, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [97a2717eb9](https://linux-hardware.org/?probe=97a2717eb9) | Apr 27, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | [68fdd1e81a](https://linux-hardware.org/?probe=68fdd1e81a) | Apr 27, 2022 |
| ASUSTek       | Hematite                    | [a6eec927f0](https://linux-hardware.org/?probe=a6eec927f0) | Apr 26, 2022 |
| MSI           | B450 TOMAHAWK               | [148f1cc5e8](https://linux-hardware.org/?probe=148f1cc5e8) | Apr 25, 2022 |
| Dell          | 0HN7XN A01                  | [a282e15540](https://linux-hardware.org/?probe=a282e15540) | Apr 25, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | [392c7e4d0d](https://linux-hardware.org/?probe=392c7e4d0d) | Apr 25, 2022 |
| MSI           | 760GM-P21                   | [3582362347](https://linux-hardware.org/?probe=3582362347) | Apr 24, 2022 |
| ASUSTek       | H97I-PLUS                   | [1b392b96c3](https://linux-hardware.org/?probe=1b392b96c3) | Apr 24, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [b36aa38e8a](https://linux-hardware.org/?probe=b36aa38e8a) | Apr 24, 2022 |
| Gigabyte      | A320M-H-CF                  | [da2e3a603d](https://linux-hardware.org/?probe=da2e3a603d) | Apr 23, 2022 |
| Dell          | 0GDG8Y A00                  | [a0ab7e8078](https://linux-hardware.org/?probe=a0ab7e8078) | Apr 22, 2022 |
| Acer          | Nitro N50-600 V:1.1         | [15332404e6](https://linux-hardware.org/?probe=15332404e6) | Apr 21, 2022 |
| Acer          | Nitro N50-600 V:1.1         | [b272388aa6](https://linux-hardware.org/?probe=b272388aa6) | Apr 21, 2022 |
| ASUSTek       | P5GC-MX                     | [810607b312](https://linux-hardware.org/?probe=810607b312) | Apr 20, 2022 |
| ASUSTek       | M5A78L-M LX V2              | [f830e867e5](https://linux-hardware.org/?probe=f830e867e5) | Apr 20, 2022 |
| Gigabyte      | Z68AP-D3                    | [76d25fd5c1](https://linux-hardware.org/?probe=76d25fd5c1) | Apr 20, 2022 |
| MSI           | 2AE0                        | [da90dbf2f2](https://linux-hardware.org/?probe=da90dbf2f2) | Apr 19, 2022 |
| MSI           | B450M PRO-VDH MAX           | [73dbb7e52a](https://linux-hardware.org/?probe=73dbb7e52a) | Apr 19, 2022 |
| HP            | 8265                        | [6a7abd0db8](https://linux-hardware.org/?probe=6a7abd0db8) | Apr 19, 2022 |
| Huanan        | X79 249PC V2.2              | [209e881793](https://linux-hardware.org/?probe=209e881793) | Apr 18, 2022 |
| ASRock        | X570 Taichi Razer Editio... | [b3f2a146ea](https://linux-hardware.org/?probe=b3f2a146ea) | Apr 18, 2022 |
| ASRock        | X570 Taichi Razer Editio... | [d597e4df9c](https://linux-hardware.org/?probe=d597e4df9c) | Apr 18, 2022 |
| Acer          | Aspire TC-115               | [16d5411ae8](https://linux-hardware.org/?probe=16d5411ae8) | Apr 18, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [f20c2c3665](https://linux-hardware.org/?probe=f20c2c3665) | Apr 16, 2022 |
| HP            | 845A                        | [cc8c320581](https://linux-hardware.org/?probe=cc8c320581) | Apr 16, 2022 |
| MSI           | 2AE0                        | [b1059198e0](https://linux-hardware.org/?probe=b1059198e0) | Apr 15, 2022 |
| ASRock        | H170M Pro4                  | [0dd1b326c0](https://linux-hardware.org/?probe=0dd1b326c0) | Apr 15, 2022 |
| MSI           | MAG B460M MORTAR            | [eeccee9c29](https://linux-hardware.org/?probe=eeccee9c29) | Apr 15, 2022 |
| ASUSTek       | F2A85-V                     | [6200a8f946](https://linux-hardware.org/?probe=6200a8f946) | Apr 14, 2022 |
| Gigabyte      | Z77-D3H                     | [2ddb0d0765](https://linux-hardware.org/?probe=2ddb0d0765) | Apr 13, 2022 |
| ASRock        | B460M-ITX/ac                | [7e6604d785](https://linux-hardware.org/?probe=7e6604d785) | Apr 12, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [ba5d8c783b](https://linux-hardware.org/?probe=ba5d8c783b) | Apr 12, 2022 |
| Gigabyte      | A520 AORUS ELITE            | [a0ff638057](https://linux-hardware.org/?probe=a0ff638057) | Apr 11, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [cadff96ec0](https://linux-hardware.org/?probe=cadff96ec0) | Apr 11, 2022 |
| ASUSTek       | H81M-A                      | [89dfde5c28](https://linux-hardware.org/?probe=89dfde5c28) | Apr 11, 2022 |
| Lenovo        | ThinkCentre A62 7057A77     | [a751b63d6b](https://linux-hardware.org/?probe=a751b63d6b) | Apr 11, 2022 |
| Dell          | 0JP3NX A01                  | [266d7d3a62](https://linux-hardware.org/?probe=266d7d3a62) | Apr 11, 2022 |
| ASRock        | B450 Steel Legend           | [b9b9565fae](https://linux-hardware.org/?probe=b9b9565fae) | Apr 10, 2022 |
| ASUSTek       | P8B75-V                     | [218db09adf](https://linux-hardware.org/?probe=218db09adf) | Apr 10, 2022 |
| Medion        | MS-7366                     | [206ab01c63](https://linux-hardware.org/?probe=206ab01c63) | Apr 10, 2022 |
| Foxconn       | 2A92                        | [d7dc8e0a2b](https://linux-hardware.org/?probe=d7dc8e0a2b) | Apr 10, 2022 |
| ASUSTek       | PRIME Z390-A                | [9f3f45d840](https://linux-hardware.org/?probe=9f3f45d840) | Apr 09, 2022 |
| ASRock        | Z87 Pro4                    | [03ee27c2ea](https://linux-hardware.org/?probe=03ee27c2ea) | Apr 09, 2022 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [73628a9025](https://linux-hardware.org/?probe=73628a9025) | Apr 09, 2022 |
| Medion        | MS-7366                     | [86884e1cf1](https://linux-hardware.org/?probe=86884e1cf1) | Apr 09, 2022 |
| ASRock        | H61M-DGS                    | [1d08a53545](https://linux-hardware.org/?probe=1d08a53545) | Apr 08, 2022 |
| ASRock        | X399 Taichi                 | [2e37b66578](https://linux-hardware.org/?probe=2e37b66578) | Apr 08, 2022 |
| ASRock        | X399 Taichi                 | [e7b1a0df67](https://linux-hardware.org/?probe=e7b1a0df67) | Apr 08, 2022 |
| Lenovo        | ThinkCentre A62 7057A77     | [fe36e7827a](https://linux-hardware.org/?probe=fe36e7827a) | Apr 08, 2022 |
| ASUSTek       | PRIME Z390-A                | [8ac05d8917](https://linux-hardware.org/?probe=8ac05d8917) | Apr 07, 2022 |
| Gigabyte      | B365M GAMING HD             | [94b6fc5131](https://linux-hardware.org/?probe=94b6fc5131) | Apr 07, 2022 |
| Alienware     | 0H869M A00                  | [f6a1c02c3e](https://linux-hardware.org/?probe=f6a1c02c3e) | Apr 07, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [1592895310](https://linux-hardware.org/?probe=1592895310) | Apr 07, 2022 |
| ASUSTek       | ROG Maximus XIII HERO       | [f76a15be2a](https://linux-hardware.org/?probe=f76a15be2a) | Apr 06, 2022 |
| Gigabyte      | Z77-DS3H                    | [a3d3ff5ac5](https://linux-hardware.org/?probe=a3d3ff5ac5) | Apr 06, 2022 |
| Unknown       | Unknown                     | [c8049ac14a](https://linux-hardware.org/?probe=c8049ac14a) | Apr 06, 2022 |
| ASUSTek       | P5GC-MX                     | [ce2aaa12ab](https://linux-hardware.org/?probe=ce2aaa12ab) | Apr 06, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [55eda86e20](https://linux-hardware.org/?probe=55eda86e20) | Apr 05, 2022 |
| Dell          | 09KPNV A00                  | [0a06779a5a](https://linux-hardware.org/?probe=0a06779a5a) | Apr 05, 2022 |
| Foxconn       | 2A92                        | [dd802e925f](https://linux-hardware.org/?probe=dd802e925f) | Apr 05, 2022 |
| MSI           | MS-7204                     | [e04077c3ac](https://linux-hardware.org/?probe=e04077c3ac) | Apr 05, 2022 |
| MSI           | MS-7204                     | [817c6f06bf](https://linux-hardware.org/?probe=817c6f06bf) | Apr 05, 2022 |
| Dell          | 0DR845                      | [26a919fc82](https://linux-hardware.org/?probe=26a919fc82) | Apr 04, 2022 |
| MSI           | Z170A GAMING M5             | [26032ef606](https://linux-hardware.org/?probe=26032ef606) | Apr 04, 2022 |
| MSI           | Z170A GAMING M5             | [fed309fdf1](https://linux-hardware.org/?probe=fed309fdf1) | Apr 04, 2022 |
| MSI           | B75A-G41                    | [80ec6aed14](https://linux-hardware.org/?probe=80ec6aed14) | Apr 04, 2022 |
| Unknown       | Unknown                     | [f6bc1c6219](https://linux-hardware.org/?probe=f6bc1c6219) | Apr 03, 2022 |
| ASUSTek       | PRIME X570-P                | [e237e56d72](https://linux-hardware.org/?probe=e237e56d72) | Apr 02, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [2315db07e2](https://linux-hardware.org/?probe=2315db07e2) | Apr 02, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [448e59a9a6](https://linux-hardware.org/?probe=448e59a9a6) | Apr 02, 2022 |
| ASUSTek       | F2A85-V                     | [6056351804](https://linux-hardware.org/?probe=6056351804) | Apr 02, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [0d1d941941](https://linux-hardware.org/?probe=0d1d941941) | Apr 02, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [fc477a4cb4](https://linux-hardware.org/?probe=fc477a4cb4) | Apr 02, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [23b384fa80](https://linux-hardware.org/?probe=23b384fa80) | Apr 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | [e94a772f2b](https://linux-hardware.org/?probe=e94a772f2b) | Apr 02, 2022 |
| Biostar       | X370GT5                     | [efe58d6ab1](https://linux-hardware.org/?probe=efe58d6ab1) | Mar 31, 2022 |
| MSI           | P45 Neo2-FR                 | [23fa0ec187](https://linux-hardware.org/?probe=23fa0ec187) | Mar 31, 2022 |
| Google        | Panther                     | [b1af725b7c](https://linux-hardware.org/?probe=b1af725b7c) | Mar 30, 2022 |
| Google        | Panther                     | [98185ea5bc](https://linux-hardware.org/?probe=98185ea5bc) | Mar 30, 2022 |
| Gigabyte      | G1.Sniper B6-CF             | [17ea484809](https://linux-hardware.org/?probe=17ea484809) | Mar 29, 2022 |
| MSI           | MAG B660 TOMAHAWK WIFI D... | [99acee5d56](https://linux-hardware.org/?probe=99acee5d56) | Mar 29, 2022 |
| Intel         | DH55HC AAE70933-505         | [0a58762fd9](https://linux-hardware.org/?probe=0a58762fd9) | Mar 29, 2022 |
| HP            | 18E5                        | [39cb47db55](https://linux-hardware.org/?probe=39cb47db55) | Mar 28, 2022 |
| Dell          | 0JP3NX A01                  | [a50c8cdd0d](https://linux-hardware.org/?probe=a50c8cdd0d) | Mar 28, 2022 |
| Dell          | 0JP3NX A01                  | [5f779f4af0](https://linux-hardware.org/?probe=5f779f4af0) | Mar 27, 2022 |
| Pegatron      | Benicia                     | [cd70e5d6f6](https://linux-hardware.org/?probe=cd70e5d6f6) | Mar 27, 2022 |
| HP            | 18E5                        | [061d716ce1](https://linux-hardware.org/?probe=061d716ce1) | Mar 27, 2022 |
| ASRock        | H61M-HVS                    | [7ebb094ad8](https://linux-hardware.org/?probe=7ebb094ad8) | Mar 25, 2022 |
| Dell          | 0P096C A01                  | [fff71ec7de](https://linux-hardware.org/?probe=fff71ec7de) | Mar 24, 2022 |
| Gigabyte      | H67MA-USB3-B3               | [c5ad9a2c99](https://linux-hardware.org/?probe=c5ad9a2c99) | Mar 24, 2022 |
| ASUSTek       | H81M-A                      | [1c1b20796d](https://linux-hardware.org/?probe=1c1b20796d) | Mar 24, 2022 |
| ASUSTek       | H81M-CS/BR                  | [17a0a5394e](https://linux-hardware.org/?probe=17a0a5394e) | Mar 24, 2022 |
| Dell          | 0KWVT8 A00                  | [5e2b36f808](https://linux-hardware.org/?probe=5e2b36f808) | Mar 24, 2022 |
| ASRock        | B550 Steel Legend           | [5c1495ecf1](https://linux-hardware.org/?probe=5c1495ecf1) | Mar 21, 2022 |
| ASRock        | B550 Steel Legend           | [00ea7017ff](https://linux-hardware.org/?probe=00ea7017ff) | Mar 20, 2022 |
| Gigabyte      | Z690 UD DDR4                | [03bfb9a66b](https://linux-hardware.org/?probe=03bfb9a66b) | Mar 20, 2022 |
| ASUSTek       | NODUSM3                     | [14c35dc52c](https://linux-hardware.org/?probe=14c35dc52c) | Mar 20, 2022 |
| Dell          | 0GDG8Y A00                  | [1deed3b4bb](https://linux-hardware.org/?probe=1deed3b4bb) | Mar 20, 2022 |
| Biostar       | B460GTQ                     | [7c912f57c6](https://linux-hardware.org/?probe=7c912f57c6) | Mar 20, 2022 |
| HP            | 1497                        | [2aac5eaf08](https://linux-hardware.org/?probe=2aac5eaf08) | Mar 19, 2022 |
| HP            | 1497                        | [ec392b9979](https://linux-hardware.org/?probe=ec392b9979) | Mar 19, 2022 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [3ba6de8cdd](https://linux-hardware.org/?probe=3ba6de8cdd) | Mar 19, 2022 |
| Dell          | 09KPNV A00                  | [f71ac898a8](https://linux-hardware.org/?probe=f71ac898a8) | Mar 19, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [34fb0ae26f](https://linux-hardware.org/?probe=34fb0ae26f) | Mar 19, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [7cafe0766c](https://linux-hardware.org/?probe=7cafe0766c) | Mar 18, 2022 |
| ASUSTek       | Hematite                    | [e4258e3376](https://linux-hardware.org/?probe=e4258e3376) | Mar 17, 2022 |
| ASUSTek       | M2A-VM HDMI                 | [ea35877485](https://linux-hardware.org/?probe=ea35877485) | Mar 17, 2022 |
| ASRock        | H510M-HVS R2.0              | [0af153934b](https://linux-hardware.org/?probe=0af153934b) | Mar 17, 2022 |
| ASRock        | H510M-HVS R2.0              | [2071129adb](https://linux-hardware.org/?probe=2071129adb) | Mar 17, 2022 |
| Shuttle       | X50V2PLUS V1.00             | [0bd650dfff](https://linux-hardware.org/?probe=0bd650dfff) | Mar 16, 2022 |
| Dell          | 0WMJ54 A01                  | [fe21b2c644](https://linux-hardware.org/?probe=fe21b2c644) | Mar 15, 2022 |
| HP            | 1791                        | [f183c3d0f0](https://linux-hardware.org/?probe=f183c3d0f0) | Mar 15, 2022 |
| HP            | 1497                        | [0aaa7bf906](https://linux-hardware.org/?probe=0aaa7bf906) | Mar 15, 2022 |
| TYAN Compu... | D2568 S26361-D2568-A11      | [fd7cbc2300](https://linux-hardware.org/?probe=fd7cbc2300) | Mar 15, 2022 |
| Dell          | 0CU409                      | [2e684afab9](https://linux-hardware.org/?probe=2e684afab9) | Mar 14, 2022 |
| MSI           | B85M-G43                    | [3869d4fdc0](https://linux-hardware.org/?probe=3869d4fdc0) | Mar 14, 2022 |
| ASUSTek       | Maximus VIII GENE           | [f264de34b1](https://linux-hardware.org/?probe=f264de34b1) | Mar 13, 2022 |
| ASUSTek       | Crosshair IV Formula        | [fd7e52fdd3](https://linux-hardware.org/?probe=fd7e52fdd3) | Mar 13, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [a90ce91192](https://linux-hardware.org/?probe=a90ce91192) | Mar 12, 2022 |
| ASUSTek       | P8P67                       | [33bf33cb8d](https://linux-hardware.org/?probe=33bf33cb8d) | Mar 10, 2022 |
| ASUSTek       | M5A97 R2.0                  | [67ead34e9e](https://linux-hardware.org/?probe=67ead34e9e) | Mar 10, 2022 |
| Google        | Buddy                       | [848034437d](https://linux-hardware.org/?probe=848034437d) | Mar 09, 2022 |
| Google        | Buddy                       | [db18fd0c96](https://linux-hardware.org/?probe=db18fd0c96) | Mar 09, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | [798e5f6c43](https://linux-hardware.org/?probe=798e5f6c43) | Mar 09, 2022 |
| MSI           | H110M PRO-VH PLUS           | [fc3707d356](https://linux-hardware.org/?probe=fc3707d356) | Mar 09, 2022 |
| ASUSTek       | P5E-VM DO                   | [876e876df1](https://linux-hardware.org/?probe=876e876df1) | Mar 09, 2022 |
| MSI           | A75A-G35                    | [8dfa30cef5](https://linux-hardware.org/?probe=8dfa30cef5) | Mar 07, 2022 |
| ASUSTek       | Z97-DELUXE                  | [7ea271a455](https://linux-hardware.org/?probe=7ea271a455) | Mar 05, 2022 |
| MSI           | B85M-G43                    | [d5e3087569](https://linux-hardware.org/?probe=d5e3087569) | Mar 04, 2022 |
| Intel         | H61                         | [86f2038ab2](https://linux-hardware.org/?probe=86f2038ab2) | Mar 03, 2022 |
| ASUSTek       | PRIME X370-PRO              | [78089f6e8c](https://linux-hardware.org/?probe=78089f6e8c) | Mar 03, 2022 |
| Gigabyte      | Z77-DS3H                    | [16268a74aa](https://linux-hardware.org/?probe=16268a74aa) | Mar 03, 2022 |
| MSI           | A68HM-E33 V2                | [53dd60c906](https://linux-hardware.org/?probe=53dd60c906) | Mar 02, 2022 |
| ASUSTek       | PRIME X370-PRO              | [b74317d80e](https://linux-hardware.org/?probe=b74317d80e) | Mar 02, 2022 |
| ASRock        | H110M-DGS R3.0              | [d7b8815296](https://linux-hardware.org/?probe=d7b8815296) | Feb 28, 2022 |
| Gigabyte      | AX370-Gaming K5-CF          | [61f8410abd](https://linux-hardware.org/?probe=61f8410abd) | Feb 28, 2022 |
| BESSTAR Te... | TL50                        | [54383b0005](https://linux-hardware.org/?probe=54383b0005) | Feb 28, 2022 |
| HP            | 821D                        | [fdfcbe172a](https://linux-hardware.org/?probe=fdfcbe172a) | Feb 28, 2022 |
| Acer          | Aspire TC-875 V:1.0         | [47018f3ae4](https://linux-hardware.org/?probe=47018f3ae4) | Feb 28, 2022 |
| Gigabyte      | GA-790XTA-UD4               | [f455a7b7a5](https://linux-hardware.org/?probe=f455a7b7a5) | Feb 28, 2022 |
| ASRock        | H77M                        | [e49dce2077](https://linux-hardware.org/?probe=e49dce2077) | Feb 28, 2022 |
| ASUSTek       | M4A87TD/USB3                | [ac9099b0e4](https://linux-hardware.org/?probe=ac9099b0e4) | Feb 28, 2022 |
| ASUSTek       | PRIME X370-PRO              | [52c633564d](https://linux-hardware.org/?probe=52c633564d) | Feb 27, 2022 |
| Gigabyte      | GA-790XTA-UD4               | [74461b0659](https://linux-hardware.org/?probe=74461b0659) | Feb 27, 2022 |
| MSI           | B85M-E45                    | [42fba9424e](https://linux-hardware.org/?probe=42fba9424e) | Feb 27, 2022 |
| Gigabyte      | EP43T-UD3L                  | [e1ba37c64a](https://linux-hardware.org/?probe=e1ba37c64a) | Feb 27, 2022 |
| Gigabyte      | EP43T-UD3L                  | [5d56069677](https://linux-hardware.org/?probe=5d56069677) | Feb 27, 2022 |
| Gigabyte      | N3160TN                     | [f080ac90fa](https://linux-hardware.org/?probe=f080ac90fa) | Feb 26, 2022 |
| ASUSTek       | PRIME H510M-D               | [5e8e80fa4c](https://linux-hardware.org/?probe=5e8e80fa4c) | Feb 25, 2022 |
| Intel         | X79M-S                      | [a175e713d6](https://linux-hardware.org/?probe=a175e713d6) | Feb 25, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [c9447d244f](https://linux-hardware.org/?probe=c9447d244f) | Feb 24, 2022 |
| Gigabyte      | Z87-HD3                     | [d1fd917c74](https://linux-hardware.org/?probe=d1fd917c74) | Feb 24, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | [40de7f3fd4](https://linux-hardware.org/?probe=40de7f3fd4) | Feb 23, 2022 |
| Medion        | MS-7707                     | [563fc4ee5a](https://linux-hardware.org/?probe=563fc4ee5a) | Feb 23, 2022 |
| Medion        | MS-7707                     | [f3b9e8796b](https://linux-hardware.org/?probe=f3b9e8796b) | Feb 23, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [8efe63496f](https://linux-hardware.org/?probe=8efe63496f) | Feb 22, 2022 |
| ASUSTek       | P5KPL-AM EPU                | [979289afcb](https://linux-hardware.org/?probe=979289afcb) | Feb 21, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | [62fc974ec7](https://linux-hardware.org/?probe=62fc974ec7) | Feb 21, 2022 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [435006f81f](https://linux-hardware.org/?probe=435006f81f) | Feb 20, 2022 |
| Gigabyte      | B560M AORUS ELITE           | [9264e93f98](https://linux-hardware.org/?probe=9264e93f98) | Feb 20, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [1990e2040f](https://linux-hardware.org/?probe=1990e2040f) | Feb 19, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [c545739154](https://linux-hardware.org/?probe=c545739154) | Feb 18, 2022 |
| ASUSTek       | P5E-VM DO                   | [c204579cc4](https://linux-hardware.org/?probe=c204579cc4) | Feb 18, 2022 |
| Gigabyte      | H270M-DS3H-CF               | [bccc2f8988](https://linux-hardware.org/?probe=bccc2f8988) | Feb 18, 2022 |
| MSI           | B360M PRO-VDH               | [dfb03c38d4](https://linux-hardware.org/?probe=dfb03c38d4) | Feb 18, 2022 |
| Gigabyte      | GA-790XTA-UD4               | [b06467c5df](https://linux-hardware.org/?probe=b06467c5df) | Feb 16, 2022 |
| ASUSTek       | P8P67                       | [e52f9b0748](https://linux-hardware.org/?probe=e52f9b0748) | Feb 15, 2022 |
| HP            | 2B15A                       | [ca58e13d8f](https://linux-hardware.org/?probe=ca58e13d8f) | Feb 15, 2022 |
| Pegatron      | 2AC2                        | [092df404d4](https://linux-hardware.org/?probe=092df404d4) | Feb 15, 2022 |
| ASUSTek       | PRIME X370-PRO              | [54a56f3b09](https://linux-hardware.org/?probe=54a56f3b09) | Feb 15, 2022 |
| Intel         | X79M-S                      | [b655865606](https://linux-hardware.org/?probe=b655865606) | Feb 14, 2022 |
| IBM           | 81077AG                     | [934878ed63](https://linux-hardware.org/?probe=934878ed63) | Feb 14, 2022 |
| ASUSTek       | P8H61-M EVO                 | [40ed7abcc5](https://linux-hardware.org/?probe=40ed7abcc5) | Feb 14, 2022 |
| ASRock        | X299 Taichi                 | [cb4047cf07](https://linux-hardware.org/?probe=cb4047cf07) | Feb 13, 2022 |
| ASUSTek       | P8H61-M EVO                 | [94bcb91d02](https://linux-hardware.org/?probe=94bcb91d02) | Feb 13, 2022 |
| ASRock        | 970A-G                      | [7b3694013f](https://linux-hardware.org/?probe=7b3694013f) | Feb 13, 2022 |
| HP            | 0B54h D                     | [c9f9611ea4](https://linux-hardware.org/?probe=c9f9611ea4) | Feb 12, 2022 |
| ASUSTek       | M5A97 R2.0                  | [d97414cfe4](https://linux-hardware.org/?probe=d97414cfe4) | Feb 12, 2022 |
| Dell          | 0T10XW A01                  | [a9034f065e](https://linux-hardware.org/?probe=a9034f065e) | Feb 11, 2022 |
| Dell          | 0T10XW A01                  | [c0cce21524](https://linux-hardware.org/?probe=c0cce21524) | Feb 11, 2022 |
| Intel         | H61                         | [e06357425a](https://linux-hardware.org/?probe=e06357425a) | Feb 11, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | [b79b4aaf10](https://linux-hardware.org/?probe=b79b4aaf10) | Feb 11, 2022 |
| HP            | 198E                        | [f4781dd683](https://linux-hardware.org/?probe=f4781dd683) | Feb 10, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [0c13bfa27b](https://linux-hardware.org/?probe=0c13bfa27b) | Feb 10, 2022 |
| Dell          | 096JG8 A01                  | [c56c62ab01](https://linux-hardware.org/?probe=c56c62ab01) | Feb 10, 2022 |
| Gigabyte      | Z87N-WIFI                   | [e86fa9ee02](https://linux-hardware.org/?probe=e86fa9ee02) | Feb 09, 2022 |
| Gigabyte      | Z87N-WIFI                   | [1b6aa0ce08](https://linux-hardware.org/?probe=1b6aa0ce08) | Feb 09, 2022 |
| MSI           | MPG Z590 GAMING FORCE       | [961be2a608](https://linux-hardware.org/?probe=961be2a608) | Feb 09, 2022 |
| MSI           | MPG Z590 GAMING FORCE       | [4ab26645c2](https://linux-hardware.org/?probe=4ab26645c2) | Feb 09, 2022 |
| HP            | 8350                        | [31f2f10b25](https://linux-hardware.org/?probe=31f2f10b25) | Feb 08, 2022 |
| HP            | 1906                        | [c2107ad290](https://linux-hardware.org/?probe=c2107ad290) | Feb 08, 2022 |
| HP            | 1906                        | [9f08673e43](https://linux-hardware.org/?probe=9f08673e43) | Feb 08, 2022 |
| MSI           | 2AE0                        | [7026cf0c86](https://linux-hardware.org/?probe=7026cf0c86) | Feb 07, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [cec6148a23](https://linux-hardware.org/?probe=cec6148a23) | Feb 07, 2022 |
| MSI           | B85M-E45                    | [3653d29a0a](https://linux-hardware.org/?probe=3653d29a0a) | Feb 07, 2022 |
| Lenovo        | ThinkCentre M91p 4480B2G    | [c5db8c7811](https://linux-hardware.org/?probe=c5db8c7811) | Feb 06, 2022 |
| Lenovo        | ThinkCentre M91p 4480B2G    | [96e92c90a5](https://linux-hardware.org/?probe=96e92c90a5) | Feb 06, 2022 |
| Gigabyte      | G1.Sniper Z97               | [5ef683a8ed](https://linux-hardware.org/?probe=5ef683a8ed) | Feb 06, 2022 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | [81b3cfa233](https://linux-hardware.org/?probe=81b3cfa233) | Feb 06, 2022 |
| Acer          | Aspire TC-115               | [03188d20fc](https://linux-hardware.org/?probe=03188d20fc) | Feb 05, 2022 |
| Gigabyte      | GA-78LMT-S2                 | [80cf2c4065](https://linux-hardware.org/?probe=80cf2c4065) | Feb 04, 2022 |
| ASUSTek       | Maximus V GENE              | [749946734b](https://linux-hardware.org/?probe=749946734b) | Feb 03, 2022 |
| Dell          | 0HN7XN A01                  | [5bb62c21b7](https://linux-hardware.org/?probe=5bb62c21b7) | Feb 03, 2022 |
| ASUSTek       | M4A785-M                    | [421c016644](https://linux-hardware.org/?probe=421c016644) | Feb 02, 2022 |
| Gigabyte      | B450 AORUS M                | [b76b53bf53](https://linux-hardware.org/?probe=b76b53bf53) | Feb 01, 2022 |
| Gigabyte      | B450 AORUS M                | [45f03f7991](https://linux-hardware.org/?probe=45f03f7991) | Jan 31, 2022 |
| Gigabyte      | B450 AORUS M                | [690eba21e0](https://linux-hardware.org/?probe=690eba21e0) | Jan 30, 2022 |
| Dell          | 0HN7XN A01                  | [af1d1e8c47](https://linux-hardware.org/?probe=af1d1e8c47) | Jan 30, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | [7450ea2cad](https://linux-hardware.org/?probe=7450ea2cad) | Jan 30, 2022 |
| ASRock        | H81M-DGS                    | [05fc3bd63b](https://linux-hardware.org/?probe=05fc3bd63b) | Jan 29, 2022 |
| HP            | 3047h                       | [48f624cbea](https://linux-hardware.org/?probe=48f624cbea) | Jan 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [bcdcd2eeb6](https://linux-hardware.org/?probe=bcdcd2eeb6) | Jan 29, 2022 |
| ASUSTek       | M2A74-AM SE                 | [1a2d6520d3](https://linux-hardware.org/?probe=1a2d6520d3) | Jan 29, 2022 |
| MSI           | 2AE0                        | [1a55336eb9](https://linux-hardware.org/?probe=1a55336eb9) | Jan 28, 2022 |
| Gigabyte      | GA-MA790GP-DS4H             | [ef8894e69d](https://linux-hardware.org/?probe=ef8894e69d) | Jan 28, 2022 |
| Wortmann      | TERRA_PC                    | [4fea20e2bf](https://linux-hardware.org/?probe=4fea20e2bf) | Jan 28, 2022 |
| Dell          | 0Y2MRG A00                  | [1a1b794c06](https://linux-hardware.org/?probe=1a1b794c06) | Jan 28, 2022 |
| Gigabyte      | Z270N-WIFI-CF               | [78f310c42a](https://linux-hardware.org/?probe=78f310c42a) | Jan 27, 2022 |
| ASRock        | G31M-S                      | [e579ce1757](https://linux-hardware.org/?probe=e579ce1757) | Jan 26, 2022 |
| Intel         | DH55PJ AAE93812-303         | [2c70e74055](https://linux-hardware.org/?probe=2c70e74055) | Jan 26, 2022 |
| Intel         | DH55PJ AAE93812-303         | [6a692a4e11](https://linux-hardware.org/?probe=6a692a4e11) | Jan 26, 2022 |
| Foxconn       | nT-i1000 Series PCB         | [72374dc22c](https://linux-hardware.org/?probe=72374dc22c) | Jan 26, 2022 |
| Foxconn       | nT-i1000 Series PCB         | [78cdf0490a](https://linux-hardware.org/?probe=78cdf0490a) | Jan 26, 2022 |
| Dell          | 07KY25 A00                  | [102d10e806](https://linux-hardware.org/?probe=102d10e806) | Jan 26, 2022 |
| MSI           | H97 GAMING 3                | [75f4b47111](https://linux-hardware.org/?probe=75f4b47111) | Jan 26, 2022 |
| Dell          | 06NWYK A01                  | [dbc44c9f4a](https://linux-hardware.org/?probe=dbc44c9f4a) | Jan 25, 2022 |
| HP            | 1497                        | [a32eadf3ab](https://linux-hardware.org/?probe=a32eadf3ab) | Jan 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e521380180](https://linux-hardware.org/?probe=e521380180) | Jan 25, 2022 |
| ASUSTek       | Q87T                        | [1bcaa6dedf](https://linux-hardware.org/?probe=1bcaa6dedf) | Jan 24, 2022 |
| Foxconn       | 2ABF                        | [e5723eaa42](https://linux-hardware.org/?probe=e5723eaa42) | Jan 23, 2022 |
| Gigabyte      | B450M DS3H-CF               | [a0034083eb](https://linux-hardware.org/?probe=a0034083eb) | Jan 22, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [2a8b893eb6](https://linux-hardware.org/?probe=2a8b893eb6) | Jan 22, 2022 |
| Foxconn       | 2ABF                        | [af38735785](https://linux-hardware.org/?probe=af38735785) | Jan 22, 2022 |
| MSI           | A75A-G35                    | [e2148dff19](https://linux-hardware.org/?probe=e2148dff19) | Jan 22, 2022 |
| Dell          | 0CU409                      | [8fc6c3decf](https://linux-hardware.org/?probe=8fc6c3decf) | Jan 21, 2022 |
| Dell          | 0CU409                      | [953718318f](https://linux-hardware.org/?probe=953718318f) | Jan 21, 2022 |
| Gigabyte      | F2A58M-DS2                  | [a89dd04d3a](https://linux-hardware.org/?probe=a89dd04d3a) | Jan 20, 2022 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | [586012f45e](https://linux-hardware.org/?probe=586012f45e) | Jan 20, 2022 |
| Dell          | 09NY2R A00                  | [2ab8f0375c](https://linux-hardware.org/?probe=2ab8f0375c) | Jan 20, 2022 |
| Dell          | 09NY2R A00                  | [5308c77880](https://linux-hardware.org/?probe=5308c77880) | Jan 19, 2022 |
| ASUSTek       | H81M-K                      | [637ad5d9e4](https://linux-hardware.org/?probe=637ad5d9e4) | Jan 18, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [ffaca9cabf](https://linux-hardware.org/?probe=ffaca9cabf) | Jan 18, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [940b702411](https://linux-hardware.org/?probe=940b702411) | Jan 16, 2022 |
| MSI           | H61M-P25                    | [3433cb58a1](https://linux-hardware.org/?probe=3433cb58a1) | Jan 14, 2022 |
| MSI           | MS-7053                     | [8844db2984](https://linux-hardware.org/?probe=8844db2984) | Jan 13, 2022 |
| EVGA          | 152-HR-E979                 | [669c7a3ef6](https://linux-hardware.org/?probe=669c7a3ef6) | Jan 12, 2022 |
| EVGA          | 152-HR-E979                 | [075a31a3c5](https://linux-hardware.org/?probe=075a31a3c5) | Jan 12, 2022 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | [368df270dc](https://linux-hardware.org/?probe=368df270dc) | Jan 11, 2022 |
| Gigabyte      | F2A58M-DS2                  | [b7ee3c3e93](https://linux-hardware.org/?probe=b7ee3c3e93) | Jan 11, 2022 |
| ASUSTek       | P8H61-I R2.0                | [5b08de311b](https://linux-hardware.org/?probe=5b08de311b) | Jan 10, 2022 |
| Dell          | 06NWYK A01                  | [98c10ce544](https://linux-hardware.org/?probe=98c10ce544) | Jan 10, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [6759388aa1](https://linux-hardware.org/?probe=6759388aa1) | Jan 09, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [6a368aefbd](https://linux-hardware.org/?probe=6a368aefbd) | Jan 09, 2022 |
| ASUSTek       | PRIME H310M-K               | [3b4d6e5abd](https://linux-hardware.org/?probe=3b4d6e5abd) | Jan 08, 2022 |
| ASRock        | G31M-S                      | [b33a983889](https://linux-hardware.org/?probe=b33a983889) | Jan 08, 2022 |
| MSI           | H61M-P25                    | [5f095c2bf8](https://linux-hardware.org/?probe=5f095c2bf8) | Jan 08, 2022 |
| Dell          | 042P49 A02                  | [b2a3538121](https://linux-hardware.org/?probe=b2a3538121) | Jan 08, 2022 |
| ASRock        | AM1B-ITX                    | [c374329271](https://linux-hardware.org/?probe=c374329271) | Jan 07, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | [e51ad2ec06](https://linux-hardware.org/?probe=e51ad2ec06) | Jan 07, 2022 |
| Dell          | 0YXT71 A02                  | [682c40786b](https://linux-hardware.org/?probe=682c40786b) | Jan 07, 2022 |
| Gigabyte      | H61M-S2PV                   | [398f9ebe03](https://linux-hardware.org/?probe=398f9ebe03) | Jan 06, 2022 |
| ASUSTek       | Benicia                     | [5459dba29c](https://linux-hardware.org/?probe=5459dba29c) | Jan 06, 2022 |
| Dell          | 0GDG8Y A00                  | [e89e415451](https://linux-hardware.org/?probe=e89e415451) | Jan 05, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [fc860fdb7a](https://linux-hardware.org/?probe=fc860fdb7a) | Jan 05, 2022 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [dad1a9143d](https://linux-hardware.org/?probe=dad1a9143d) | Jan 05, 2022 |
| MSI           | H61MU-E35                   | [5694489e55](https://linux-hardware.org/?probe=5694489e55) | Jan 05, 2022 |
| Gigabyte      | H370M D3H-CF                | [ab12119d4f](https://linux-hardware.org/?probe=ab12119d4f) | Jan 05, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [32d0fda197](https://linux-hardware.org/?probe=32d0fda197) | Jan 05, 2022 |
| MSI           | H61MU-E35                   | [2c3f24c851](https://linux-hardware.org/?probe=2c3f24c851) | Jan 04, 2022 |
| MSI           | H61M-P25                    | [3679d16bdb](https://linux-hardware.org/?probe=3679d16bdb) | Jan 04, 2022 |
| HP            | 3047h                       | [8faa43060a](https://linux-hardware.org/?probe=8faa43060a) | Jan 04, 2022 |
| MSI           | H61M-P25                    | [004392f0ef](https://linux-hardware.org/?probe=004392f0ef) | Jan 04, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [b838b1e1cc](https://linux-hardware.org/?probe=b838b1e1cc) | Jan 04, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | [d2a528221c](https://linux-hardware.org/?probe=d2a528221c) | Jan 03, 2022 |
| ASRock        | B450M Steel Legend          | [81a98f588a](https://linux-hardware.org/?probe=81a98f588a) | Jan 02, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [a769ac4242](https://linux-hardware.org/?probe=a769ac4242) | Jan 01, 2022 |
| Gigabyte      | H110M-H-CF                  | [4754d83d04](https://linux-hardware.org/?probe=4754d83d04) | Jan 01, 2022 |
| Acer          | Aspire M3970                | [e10ce7d132](https://linux-hardware.org/?probe=e10ce7d132) | Dec 31, 2021 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [5b97adba13](https://linux-hardware.org/?probe=5b97adba13) | Dec 31, 2021 |
| ECS           | G31T-M7                     | [8cd5d79924](https://linux-hardware.org/?probe=8cd5d79924) | Dec 31, 2021 |
| ECS           | G31T-M7                     | [9ebfb53472](https://linux-hardware.org/?probe=9ebfb53472) | Dec 31, 2021 |
| HP            | 1998                        | [07bdd01c09](https://linux-hardware.org/?probe=07bdd01c09) | Dec 31, 2021 |
| Dell          | 088DT1 A01                  | [2599126547](https://linux-hardware.org/?probe=2599126547) | Dec 30, 2021 |
| Foxconn       | 2AB1                        | [1c32c6a027](https://linux-hardware.org/?probe=1c32c6a027) | Dec 30, 2021 |
| MSI           | H81M-P33                    | [0fb1d25a7d](https://linux-hardware.org/?probe=0fb1d25a7d) | Dec 30, 2021 |
| ASRock        | Z87 Pro4                    | [2a8588f61e](https://linux-hardware.org/?probe=2a8588f61e) | Dec 29, 2021 |
| Gigabyte      | Z97-HD3                     | [5536599b58](https://linux-hardware.org/?probe=5536599b58) | Dec 28, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [127916f66f](https://linux-hardware.org/?probe=127916f66f) | Dec 28, 2021 |
| ASUSTek       | H81-PLUS                    | [60ba71333c](https://linux-hardware.org/?probe=60ba71333c) | Dec 27, 2021 |
| Intel         | Cherry Trail CR H91596-3... | [cb83ad3d6c](https://linux-hardware.org/?probe=cb83ad3d6c) | Dec 27, 2021 |
| Intel         | Cherry Trail CR H91596-3... | [76e7cab82a](https://linux-hardware.org/?probe=76e7cab82a) | Dec 26, 2021 |
| MSI           | MPG Z390 GAMING PLUS        | [39f562f189](https://linux-hardware.org/?probe=39f562f189) | Dec 25, 2021 |
| Dell          | 0VNP2H A00                  | [e64f51e52a](https://linux-hardware.org/?probe=e64f51e52a) | Dec 24, 2021 |
| Gigabyte      | H57M-USB3                   | [ee70d6b4b4](https://linux-hardware.org/?probe=ee70d6b4b4) | Dec 24, 2021 |
| Gigabyte      | Z170X-Gaming 7              | [5c4ae9536f](https://linux-hardware.org/?probe=5c4ae9536f) | Dec 24, 2021 |
| Gigabyte      | EG41MFT-US2H                | [2bfb4702c3](https://linux-hardware.org/?probe=2bfb4702c3) | Dec 23, 2021 |
| Gigabyte      | EG41MFT-US2H                | [b29d64341c](https://linux-hardware.org/?probe=b29d64341c) | Dec 23, 2021 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | [69d74c89b4](https://linux-hardware.org/?probe=69d74c89b4) | Dec 23, 2021 |
| Gigabyte      | B450M DS3H-CF               | [4453e33b88](https://linux-hardware.org/?probe=4453e33b88) | Dec 22, 2021 |
| ASRock        | B450 Pro4                   | [0832f6d0fd](https://linux-hardware.org/?probe=0832f6d0fd) | Dec 22, 2021 |
| ASUSTek       | P8Z77-M                     | [667e676c78](https://linux-hardware.org/?probe=667e676c78) | Dec 21, 2021 |
| ASRock        | A320M-DVS R4.0              | [c38dcdb848](https://linux-hardware.org/?probe=c38dcdb848) | Dec 21, 2021 |
| Dell          | 03NVJ6 A02                  | [685819bc74](https://linux-hardware.org/?probe=685819bc74) | Dec 20, 2021 |
| ASRock        | B450M-HDV R4.0              | [210f1589c4](https://linux-hardware.org/?probe=210f1589c4) | Dec 20, 2021 |
| ASRock        | B450M Pro4                  | [b40c57df26](https://linux-hardware.org/?probe=b40c57df26) | Dec 20, 2021 |
| ASUSTek       | PRIME B350M-A               | [09d76b803c](https://linux-hardware.org/?probe=09d76b803c) | Dec 20, 2021 |
| Intel         | B75                         | [9178fa9053](https://linux-hardware.org/?probe=9178fa9053) | Dec 19, 2021 |
| ASRock        | B450M-HDV R4.0              | [35182a65bb](https://linux-hardware.org/?probe=35182a65bb) | Dec 19, 2021 |
| Lenovo        | SHARKBAY 31900058 STD       | [717b852409](https://linux-hardware.org/?probe=717b852409) | Dec 19, 2021 |
| Apple         | Mac-F4208DC8 PVT            | [38a4bbf8d3](https://linux-hardware.org/?probe=38a4bbf8d3) | Dec 19, 2021 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [f86ed2049c](https://linux-hardware.org/?probe=f86ed2049c) | Dec 19, 2021 |
| Dell          | 0HY9JP A02                  | [063c3ec5d2](https://linux-hardware.org/?probe=063c3ec5d2) | Dec 19, 2021 |
| ASUSTek       | P5Q PRO TURBO               | [4c845a464c](https://linux-hardware.org/?probe=4c845a464c) | Dec 19, 2021 |
| Acer          | Aspire XC-330               | [1803a4622c](https://linux-hardware.org/?probe=1803a4622c) | Dec 19, 2021 |
| ASUSTek       | Benicia                     | [e572d5ceff](https://linux-hardware.org/?probe=e572d5ceff) | Dec 19, 2021 |
| Shuttle       | FH61V                       | [39d341d8be](https://linux-hardware.org/?probe=39d341d8be) | Dec 19, 2021 |
| MSI           | MS-7053                     | [3e9330e811](https://linux-hardware.org/?probe=3e9330e811) | Dec 18, 2021 |
| MSI           | MS-7053                     | [b32db3cd18](https://linux-hardware.org/?probe=b32db3cd18) | Dec 18, 2021 |
| Unknown       | C51GM-M                     | [91386c4f7c](https://linux-hardware.org/?probe=91386c4f7c) | Dec 17, 2021 |
| Lenovo        | ThinkCentre M57e 9489W1U    | [ba5156ef68](https://linux-hardware.org/?probe=ba5156ef68) | Dec 17, 2021 |
| Dell          | 0Y2K8N A01                  | [2e29930670](https://linux-hardware.org/?probe=2e29930670) | Dec 17, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [dfbadf6708](https://linux-hardware.org/?probe=dfbadf6708) | Dec 17, 2021 |
| Unknown       | C51GM-M                     | [cd4d96fefa](https://linux-hardware.org/?probe=cd4d96fefa) | Dec 17, 2021 |
| Acer          | Aspire XC-330               | [61dd8de51b](https://linux-hardware.org/?probe=61dd8de51b) | Dec 16, 2021 |
| Dell          | 0D24M8 A01                  | [a306863279](https://linux-hardware.org/?probe=a306863279) | Dec 16, 2021 |
| Lenovo        | SHARKBAY NOK                | [2acaeac0de](https://linux-hardware.org/?probe=2acaeac0de) | Dec 14, 2021 |
| Lenovo        | SHARKBAY NOK                | [2c39bc3721](https://linux-hardware.org/?probe=2c39bc3721) | Dec 14, 2021 |
| HP            | 18E5                        | [88f87a7a1b](https://linux-hardware.org/?probe=88f87a7a1b) | Dec 14, 2021 |
| ASUSTek       | AM1M-A                      | [5113655631](https://linux-hardware.org/?probe=5113655631) | Dec 14, 2021 |
| HP            | 2179                        | [c2dd79384a](https://linux-hardware.org/?probe=c2dd79384a) | Dec 14, 2021 |
| ASUSTek       | VM40B                       | [c53952beab](https://linux-hardware.org/?probe=c53952beab) | Dec 14, 2021 |
| MSI           | MPG B550 GAMING PLUS        | [788c6b0550](https://linux-hardware.org/?probe=788c6b0550) | Dec 13, 2021 |
| ASUSTek       | P5QC                        | [b471a79340](https://linux-hardware.org/?probe=b471a79340) | Dec 13, 2021 |
| Dell          | 0M5DCD A00                  | [447bffefc3](https://linux-hardware.org/?probe=447bffefc3) | Dec 13, 2021 |
| Intel         | DQ87PG AAG74154-403         | [e2a6d57861](https://linux-hardware.org/?probe=e2a6d57861) | Dec 13, 2021 |
| Intel         | B75                         | [652828f7b9](https://linux-hardware.org/?probe=652828f7b9) | Dec 13, 2021 |
| MSI           | MPG Z390 GAMING PLUS        | [6b33adaacf](https://linux-hardware.org/?probe=6b33adaacf) | Dec 13, 2021 |
| ASUSTek       | PRIME B350M-A               | [aa92a82326](https://linux-hardware.org/?probe=aa92a82326) | Dec 13, 2021 |
| ASUSTek       | P5QC                        | [8e659f2b89](https://linux-hardware.org/?probe=8e659f2b89) | Dec 12, 2021 |
| ASUSTek       | PRIME B360M-K               | [abb6a94373](https://linux-hardware.org/?probe=abb6a94373) | Dec 12, 2021 |
| Gigabyte      | H97M-D3H                    | [d9e04ee743](https://linux-hardware.org/?probe=d9e04ee743) | Dec 12, 2021 |
| Gigabyte      | H97M-D3H                    | [1d768c3c63](https://linux-hardware.org/?probe=1d768c3c63) | Dec 12, 2021 |
| ASRock        | B450M Pro4                  | [6a8480268d](https://linux-hardware.org/?probe=6a8480268d) | Dec 12, 2021 |
| Dell          | 02YYK5 A01                  | [1301218290](https://linux-hardware.org/?probe=1301218290) | Dec 11, 2021 |
| HP            | 339A                        | [7081fc45a3](https://linux-hardware.org/?probe=7081fc45a3) | Dec 11, 2021 |
| HP            | 304Ah                       | [6d87535158](https://linux-hardware.org/?probe=6d87535158) | Dec 10, 2021 |
| eMachines     | EL1850G                     | [ccd7758cbe](https://linux-hardware.org/?probe=ccd7758cbe) | Dec 10, 2021 |
| ASUSTek       | NARRA3                      | [028ad01454](https://linux-hardware.org/?probe=028ad01454) | Dec 09, 2021 |
| Biostar       | A320MH                      | [fbbe7a436a](https://linux-hardware.org/?probe=fbbe7a436a) | Dec 09, 2021 |
| Biostar       | A320MH                      | [3870a17dfe](https://linux-hardware.org/?probe=3870a17dfe) | Dec 09, 2021 |
| MSI           | MAG B560M MORTAR WIFI       | [0e19f8e2ae](https://linux-hardware.org/?probe=0e19f8e2ae) | Dec 09, 2021 |
| MSI           | MAG B560M MORTAR WIFI       | [a37d2cc42f](https://linux-hardware.org/?probe=a37d2cc42f) | Dec 09, 2021 |
| MSI           | 970 GAMING                  | [1a5b0a8d39](https://linux-hardware.org/?probe=1a5b0a8d39) | Dec 09, 2021 |
| MSI           | 970 GAMING                  | [f4d8f580dc](https://linux-hardware.org/?probe=f4d8f580dc) | Dec 09, 2021 |
| ASUSTek       | NARRA3                      | [c64aed90a9](https://linux-hardware.org/?probe=c64aed90a9) | Dec 08, 2021 |
| ASUSTek       | M3A78-EM                    | [b041919f38](https://linux-hardware.org/?probe=b041919f38) | Dec 08, 2021 |
| HP            | 87C3                        | [16cc7e0bcb](https://linux-hardware.org/?probe=16cc7e0bcb) | Dec 07, 2021 |
| HP            | 81B4 01                     | [1477bd5a44](https://linux-hardware.org/?probe=1477bd5a44) | Dec 07, 2021 |
| Dell          | 0T656F A01                  | [552210319c](https://linux-hardware.org/?probe=552210319c) | Dec 06, 2021 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [2ce114a1c7](https://linux-hardware.org/?probe=2ce114a1c7) | Dec 06, 2021 |
| ASRock        | M3A770DE                    | [1a03b6e5c7](https://linux-hardware.org/?probe=1a03b6e5c7) | Dec 05, 2021 |
| ASRock        | M3A770DE                    | [bdf4260678](https://linux-hardware.org/?probe=bdf4260678) | Dec 05, 2021 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [ce3d88a2a2](https://linux-hardware.org/?probe=ce3d88a2a2) | Dec 05, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [49fe509dd2](https://linux-hardware.org/?probe=49fe509dd2) | Dec 04, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [e6b7b57ea7](https://linux-hardware.org/?probe=e6b7b57ea7) | Dec 04, 2021 |
| Dell          | 0G254H A00                  | [11897b38da](https://linux-hardware.org/?probe=11897b38da) | Dec 03, 2021 |
| HP            | 2B44                        | [b62df43777](https://linux-hardware.org/?probe=b62df43777) | Dec 03, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 PRO ... | [e39465a63b](https://linux-hardware.org/?probe=e39465a63b) | Dec 03, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [ad90caf60d](https://linux-hardware.org/?probe=ad90caf60d) | Dec 03, 2021 |
| Pegatron      | JESSE                       | [9091bacc33](https://linux-hardware.org/?probe=9091bacc33) | Dec 03, 2021 |
| ASUSTek       | LEONITE                     | [704345be69](https://linux-hardware.org/?probe=704345be69) | Dec 03, 2021 |
| Biostar       | A780L3C                     | [a50e3d0532](https://linux-hardware.org/?probe=a50e3d0532) | Dec 02, 2021 |
| Foxconn       | 2A8C                        | [8d24862bd6](https://linux-hardware.org/?probe=8d24862bd6) | Dec 02, 2021 |
| Biostar       | A780L3C                     | [497f29a343](https://linux-hardware.org/?probe=497f29a343) | Dec 02, 2021 |
| Dell          | 0WR7PY A02                  | [1255f30eea](https://linux-hardware.org/?probe=1255f30eea) | Dec 01, 2021 |
| Gigabyte      | GA-MA74GM-S2H               | [bd33efb6f7](https://linux-hardware.org/?probe=bd33efb6f7) | Dec 01, 2021 |
| HP            | 339A                        | [4a377796cf](https://linux-hardware.org/?probe=4a377796cf) | Dec 01, 2021 |
| Dell          | 0PU052                      | [a943d9f217](https://linux-hardware.org/?probe=a943d9f217) | Dec 01, 2021 |
| Dell          | 0WR7PY A02                  | [d51c794107](https://linux-hardware.org/?probe=d51c794107) | Nov 30, 2021 |
| Dell          | 0WMJ54 A01                  | [5fa96d5863](https://linux-hardware.org/?probe=5fa96d5863) | Nov 30, 2021 |
| HP            | 8299                        | [6eb5c6d54a](https://linux-hardware.org/?probe=6eb5c6d54a) | Nov 30, 2021 |
| Medion        | MS-7707                     | [3d0a46f2ef](https://linux-hardware.org/?probe=3d0a46f2ef) | Nov 30, 2021 |
| ASRock        | H67DE3                      | [d710784470](https://linux-hardware.org/?probe=d710784470) | Nov 30, 2021 |
| HP            | 8299                        | [7bd1df0e4d](https://linux-hardware.org/?probe=7bd1df0e4d) | Nov 29, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | [24b15affa6](https://linux-hardware.org/?probe=24b15affa6) | Nov 29, 2021 |
| ASUSTek       | P8Z77-V LX                  | [b153db375f](https://linux-hardware.org/?probe=b153db375f) | Nov 29, 2021 |
| ECS           | GeForce6100PM-M2            | [032a2baaca](https://linux-hardware.org/?probe=032a2baaca) | Nov 28, 2021 |
| Lenovo        | 36E7 SDK0J40700 WIN 3258... | [382bfc4a86](https://linux-hardware.org/?probe=382bfc4a86) | Nov 28, 2021 |
| Gigabyte      | G31M-ES2L                   | [cd296f933b](https://linux-hardware.org/?probe=cd296f933b) | Nov 28, 2021 |
| Gigabyte      | G31M-ES2L                   | [44c0cf428f](https://linux-hardware.org/?probe=44c0cf428f) | Nov 28, 2021 |
| MSI           | X370 GAMING PLUS            | [0b71d2652d](https://linux-hardware.org/?probe=0b71d2652d) | Nov 27, 2021 |
| Dell          | 0VNP2H A00                  | [803e55fd86](https://linux-hardware.org/?probe=803e55fd86) | Nov 27, 2021 |
| ASUSTek       | M4A78T-E                    | [df3010e1b8](https://linux-hardware.org/?probe=df3010e1b8) | Nov 27, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [ae57475767](https://linux-hardware.org/?probe=ae57475767) | Nov 27, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [3925ce16ae](https://linux-hardware.org/?probe=3925ce16ae) | Nov 27, 2021 |
| Lenovo        | 36E7 SDK0J40700 WIN 3258... | [cd58d98b6a](https://linux-hardware.org/?probe=cd58d98b6a) | Nov 27, 2021 |
| ASRock        | B450M Pro4                  | [bb642022a6](https://linux-hardware.org/?probe=bb642022a6) | Nov 27, 2021 |
| ASRock        | ALiveNF6G-DVI               | [2761f434e8](https://linux-hardware.org/?probe=2761f434e8) | Nov 26, 2021 |
| HP            | 2179                        | [121210497a](https://linux-hardware.org/?probe=121210497a) | Nov 25, 2021 |
| Dell          | 0VNP2H A00                  | [fe9de9a896](https://linux-hardware.org/?probe=fe9de9a896) | Nov 25, 2021 |
| HP            | 18E7                        | [7385ca30d4](https://linux-hardware.org/?probe=7385ca30d4) | Nov 23, 2021 |
| Pegatron      | 2A86E01                     | [b57d9ec4a4](https://linux-hardware.org/?probe=b57d9ec4a4) | Nov 23, 2021 |
| Gigabyte      | H61N-USB3                   | [83e388363c](https://linux-hardware.org/?probe=83e388363c) | Nov 23, 2021 |
| Dell          | 0PU052                      | [a41541bab5](https://linux-hardware.org/?probe=a41541bab5) | Nov 23, 2021 |
| Gigabyte      | G41MT-S2                    | [8031417427](https://linux-hardware.org/?probe=8031417427) | Nov 23, 2021 |
| Intel         | DB65AL AAG12530-309         | [44c8025eee](https://linux-hardware.org/?probe=44c8025eee) | Nov 23, 2021 |
| MSI           | B360M PRO-VD                | [e1f68c6698](https://linux-hardware.org/?probe=e1f68c6698) | Nov 22, 2021 |
| Gigabyte      | H77M-D3H                    | [2819a870a8](https://linux-hardware.org/?probe=2819a870a8) | Nov 22, 2021 |
| HP            | 0AA4h                       | [22c6e4fffd](https://linux-hardware.org/?probe=22c6e4fffd) | Nov 22, 2021 |
| ASRock        | P67 Extreme6                | [54cd91039c](https://linux-hardware.org/?probe=54cd91039c) | Nov 22, 2021 |
| ASUSTek       | PRIME Z590M-PLUS            | [fa922e6e20](https://linux-hardware.org/?probe=fa922e6e20) | Nov 22, 2021 |
| ASRock        | 775i945GZ                   | [8d3cfee95d](https://linux-hardware.org/?probe=8d3cfee95d) | Nov 22, 2021 |
| ASRock        | ALiveNF6G-DVI               | [23a839f917](https://linux-hardware.org/?probe=23a839f917) | Nov 21, 2021 |
| ASUSTek       | PRIME Z590M-PLUS            | [ae91e01910](https://linux-hardware.org/?probe=ae91e01910) | Nov 21, 2021 |
| Dell          | 03NVJ6 A02                  | [00a8a0ab87](https://linux-hardware.org/?probe=00a8a0ab87) | Nov 21, 2021 |
| Gigabyte      | B450M GAMING                | [2355c29da1](https://linux-hardware.org/?probe=2355c29da1) | Nov 21, 2021 |
| Gigabyte      | H55M-UD2H                   | [16e0d2d71a](https://linux-hardware.org/?probe=16e0d2d71a) | Nov 21, 2021 |
| Dell          | 0KWVT8 A00                  | [a6f003d198](https://linux-hardware.org/?probe=a6f003d198) | Nov 20, 2021 |
| LattePanda    | Alpha                       | [24c2fc6f7b](https://linux-hardware.org/?probe=24c2fc6f7b) | Nov 20, 2021 |
| LattePanda    | Alpha                       | [4aa879f7ac](https://linux-hardware.org/?probe=4aa879f7ac) | Nov 20, 2021 |
| ASRock        | B450M Pro4 R2.0             | [8a53d67102](https://linux-hardware.org/?probe=8a53d67102) | Nov 19, 2021 |
| MSI           | 970 GAMING                  | [ac8f38525e](https://linux-hardware.org/?probe=ac8f38525e) | Nov 19, 2021 |
| ASUSTek       | P8Z77-V LX                  | [6807e3fa8c](https://linux-hardware.org/?probe=6807e3fa8c) | Nov 18, 2021 |
| Dell          | 0KWVT8 A00                  | [93b90c3da4](https://linux-hardware.org/?probe=93b90c3da4) | Nov 18, 2021 |
| ASRock        | G31M-VS2                    | [8bc6042d3f](https://linux-hardware.org/?probe=8bc6042d3f) | Nov 17, 2021 |
| ASRock        | X370M-HDV                   | [a991fee412](https://linux-hardware.org/?probe=a991fee412) | Nov 17, 2021 |
| Dell          | 0GXM1W A01                  | [7e9f638277](https://linux-hardware.org/?probe=7e9f638277) | Nov 17, 2021 |
| ASUSTek       | P5KPL-AM                    | [0cae2ebf49](https://linux-hardware.org/?probe=0cae2ebf49) | Nov 16, 2021 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | [bb50b7d97c](https://linux-hardware.org/?probe=bb50b7d97c) | Nov 16, 2021 |
| MSI           | 2A9C                        | [80ef0caf18](https://linux-hardware.org/?probe=80ef0caf18) | Nov 15, 2021 |
| MSI           | 2A9C                        | [44e1dcea05](https://linux-hardware.org/?probe=44e1dcea05) | Nov 15, 2021 |
| Gigabyte      | H170-D3HP-CF                | [e90a1881c7](https://linux-hardware.org/?probe=e90a1881c7) | Nov 14, 2021 |
| Fujitsu       | D2950-A1 S26361-D2950-A1    | [a92c32b60a](https://linux-hardware.org/?probe=a92c32b60a) | Nov 14, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [542b1538bf](https://linux-hardware.org/?probe=542b1538bf) | Nov 14, 2021 |
| HP            | 8653 A                      | [88b53507c9](https://linux-hardware.org/?probe=88b53507c9) | Nov 13, 2021 |
| HP            | 3048h                       | [200317605d](https://linux-hardware.org/?probe=200317605d) | Nov 13, 2021 |
| Dell          | 0GXM1W A02                  | [d446993ec9](https://linux-hardware.org/?probe=d446993ec9) | Nov 13, 2021 |
| ASUSTek       | P5G41T-M LX3                | [8977322809](https://linux-hardware.org/?probe=8977322809) | Nov 13, 2021 |
| HP            | 1790                        | [e86cdf904a](https://linux-hardware.org/?probe=e86cdf904a) | Nov 12, 2021 |
| ASUSTek       | M5A78L LE                   | [d342b54224](https://linux-hardware.org/?probe=d342b54224) | Nov 12, 2021 |
| HP            | 339A                        | [6dc037bf1f](https://linux-hardware.org/?probe=6dc037bf1f) | Nov 11, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [d0eae9ef10](https://linux-hardware.org/?probe=d0eae9ef10) | Nov 11, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [7a2464824d](https://linux-hardware.org/?probe=7a2464824d) | Nov 11, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | [c8e4265515](https://linux-hardware.org/?probe=c8e4265515) | Nov 11, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [eece1d5528](https://linux-hardware.org/?probe=eece1d5528) | Nov 11, 2021 |
| ASUSTek       | H81M-P PLUS                 | [1841ab2aff](https://linux-hardware.org/?probe=1841ab2aff) | Nov 10, 2021 |
| ASUSTek       | A68HM-PLUS                  | [0e688f660f](https://linux-hardware.org/?probe=0e688f660f) | Nov 10, 2021 |
| ASUSTek       | M5A97                       | [20a705fd56](https://linux-hardware.org/?probe=20a705fd56) | Nov 10, 2021 |
| HP            | 8653 A                      | [f84c67582a](https://linux-hardware.org/?probe=f84c67582a) | Nov 09, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | [e7579f2fcf](https://linux-hardware.org/?probe=e7579f2fcf) | Nov 09, 2021 |
| HP            | 1790                        | [6030cabe49](https://linux-hardware.org/?probe=6030cabe49) | Nov 09, 2021 |
| HP            | 1825                        | [7cf6c3590a](https://linux-hardware.org/?probe=7cf6c3590a) | Nov 09, 2021 |
| Dell          | 0HD5W2 A00                  | [d4c15ae33a](https://linux-hardware.org/?probe=d4c15ae33a) | Nov 08, 2021 |
| MSI           | B450M MORTAR MAX            | [84c316ee57](https://linux-hardware.org/?probe=84c316ee57) | Nov 08, 2021 |
| Gigabyte      | B75M-D3H                    | [886c08185e](https://linux-hardware.org/?probe=886c08185e) | Nov 08, 2021 |
| Gigabyte      | B75M-D3H                    | [e141b2d36a](https://linux-hardware.org/?probe=e141b2d36a) | Nov 08, 2021 |
| Foxconn       | H61M/H61M-S                 | [62ae26dca0](https://linux-hardware.org/?probe=62ae26dca0) | Nov 07, 2021 |
| Dell          | 0HY9JP A00                  | [05c38bf92c](https://linux-hardware.org/?probe=05c38bf92c) | Nov 07, 2021 |
| ASUSTek       | A68HM-PLUS                  | [384fb31833](https://linux-hardware.org/?probe=384fb31833) | Nov 06, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [f57575ffaf](https://linux-hardware.org/?probe=f57575ffaf) | Nov 06, 2021 |
| Dell          | 0VNP2H A02                  | [5402226d98](https://linux-hardware.org/?probe=5402226d98) | Nov 06, 2021 |
| ASUSTek       | M5A78L-M LX                 | [e6e813115f](https://linux-hardware.org/?probe=e6e813115f) | Nov 06, 2021 |
| HP            | 0A98h                       | [110c37e799](https://linux-hardware.org/?probe=110c37e799) | Nov 06, 2021 |
| ASUSTek       | A68HM-PLUS                  | [7b21a0bc71](https://linux-hardware.org/?probe=7b21a0bc71) | Nov 06, 2021 |
| Dell          | 0NKW6Y A00                  | [82a09e132d](https://linux-hardware.org/?probe=82a09e132d) | Nov 05, 2021 |
| ASUSTek       | PRIME H410M-A               | [4be9b40ea1](https://linux-hardware.org/?probe=4be9b40ea1) | Nov 05, 2021 |
| ASUSTek       | PRIME H410M-A               | [173116149c](https://linux-hardware.org/?probe=173116149c) | Nov 05, 2021 |
| Gigabyte      | F2A78M-D3H                  | [43e09b8e80](https://linux-hardware.org/?probe=43e09b8e80) | Nov 05, 2021 |
| Gigabyte      | Z97X-UD7 TH-CF              | [1383828428](https://linux-hardware.org/?probe=1383828428) | Nov 05, 2021 |
| Gigabyte      | Z97X-UD7 TH-CF              | [f5ee7a26d5](https://linux-hardware.org/?probe=f5ee7a26d5) | Nov 05, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [3e4d5dd09d](https://linux-hardware.org/?probe=3e4d5dd09d) | Nov 05, 2021 |
| Foxconn       | H61M/H61M-S                 | [7f3894059d](https://linux-hardware.org/?probe=7f3894059d) | Nov 04, 2021 |
| HP            | 18E4                        | [3069846b25](https://linux-hardware.org/?probe=3069846b25) | Nov 04, 2021 |
| MSI           | G41M-P23                    | [82e51e3f78](https://linux-hardware.org/?probe=82e51e3f78) | Nov 04, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | [d7a405763d](https://linux-hardware.org/?probe=d7a405763d) | Nov 04, 2021 |
| ASUSTek       | P8Z77-V LX                  | [d59cc9fead](https://linux-hardware.org/?probe=d59cc9fead) | Nov 04, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [2d26d5b578](https://linux-hardware.org/?probe=2d26d5b578) | Nov 02, 2021 |
| ASUSTek       | P8Z77-V LX                  | [903ec63ceb](https://linux-hardware.org/?probe=903ec63ceb) | Nov 02, 2021 |
| ASUSTek       | M11AD                       | [0cb5032c53](https://linux-hardware.org/?probe=0cb5032c53) | Nov 02, 2021 |
| Gigabyte      | GA-E6010N                   | [3c81474040](https://linux-hardware.org/?probe=3c81474040) | Nov 01, 2021 |
| Gigabyte      | GA-E6010N                   | [2a2aaffd43](https://linux-hardware.org/?probe=2a2aaffd43) | Nov 01, 2021 |
| ASRock        | FM2A55M-HD+                 | [42cd4d28bd](https://linux-hardware.org/?probe=42cd4d28bd) | Nov 01, 2021 |
| eMachines     | EL1850G                     | [01dbf1b5ec](https://linux-hardware.org/?probe=01dbf1b5ec) | Oct 31, 2021 |
| MSI           | P55-CD53                    | [860bde5935](https://linux-hardware.org/?probe=860bde5935) | Oct 31, 2021 |
| Unknown       | Unknown                     | [75cc8a67e9](https://linux-hardware.org/?probe=75cc8a67e9) | Oct 31, 2021 |
| ASRock        | B85M-HDS                    | [111e98ddef](https://linux-hardware.org/?probe=111e98ddef) | Oct 31, 2021 |
| ASUSTek       | P8H61-M LE/CSM R2.0         | [6cee757cf0](https://linux-hardware.org/?probe=6cee757cf0) | Oct 31, 2021 |
| ASUSTek       | P8H61-M LE/CSM R2.0         | [96c9053284](https://linux-hardware.org/?probe=96c9053284) | Oct 31, 2021 |
| Dell          | 06NWYK A01                  | [497c824fd5](https://linux-hardware.org/?probe=497c824fd5) | Oct 31, 2021 |
| ASRock        | B85M-HDS                    | [69dd0cf598](https://linux-hardware.org/?probe=69dd0cf598) | Oct 30, 2021 |
| Dell          | 06NWYK A01                  | [1d0625eb89](https://linux-hardware.org/?probe=1d0625eb89) | Oct 30, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [867e533368](https://linux-hardware.org/?probe=867e533368) | Oct 30, 2021 |
| ASUSTek       | P5K SE/EPU                  | [80adff7646](https://linux-hardware.org/?probe=80adff7646) | Oct 30, 2021 |
| Dell          | 0GY6Y8 A02                  | [1a267b14d3](https://linux-hardware.org/?probe=1a267b14d3) | Oct 29, 2021 |
| Dell          | 0GY6Y8 A02                  | [5b4cea000b](https://linux-hardware.org/?probe=5b4cea000b) | Oct 29, 2021 |
| ASRock        | B450 Gaming K4              | [b67ec8af25](https://linux-hardware.org/?probe=b67ec8af25) | Oct 29, 2021 |
| Dell          | 0VNP2H A02                  | [4e19df8e3c](https://linux-hardware.org/?probe=4e19df8e3c) | Oct 29, 2021 |
| Dell          | 0VNP2H A02                  | [c220480b4c](https://linux-hardware.org/?probe=c220480b4c) | Oct 29, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [a73fabcd4c](https://linux-hardware.org/?probe=a73fabcd4c) | Oct 28, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [528cec41bc](https://linux-hardware.org/?probe=528cec41bc) | Oct 28, 2021 |
| Alienware     | 08PG26 A00                  | [bb2fd997ab](https://linux-hardware.org/?probe=bb2fd997ab) | Oct 28, 2021 |
| ASRock        | FM2A88X Extreme6+           | [b676d9030a](https://linux-hardware.org/?probe=b676d9030a) | Oct 28, 2021 |
| MSI           | MAG B550M MORTAR            | [08819513f2](https://linux-hardware.org/?probe=08819513f2) | Oct 27, 2021 |
| MSI           | MAG B550M MORTAR            | [4207c6eaac](https://linux-hardware.org/?probe=4207c6eaac) | Oct 27, 2021 |
| ASUSTek       | PRIME Z270-P                | [dfb2070b53](https://linux-hardware.org/?probe=dfb2070b53) | Oct 26, 2021 |
| Alienware     | 08PG26 A00                  | [7d6b559bf8](https://linux-hardware.org/?probe=7d6b559bf8) | Oct 26, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [3862cf57e0](https://linux-hardware.org/?probe=3862cf57e0) | Oct 25, 2021 |
| ASRock        | FM2A55M-HD+                 | [a1cf5282ba](https://linux-hardware.org/?probe=a1cf5282ba) | Oct 25, 2021 |
| ASRock        | H110M-HDS R3.0              | [718ad346b7](https://linux-hardware.org/?probe=718ad346b7) | Oct 25, 2021 |
| MSI           | 2AE0                        | [64a3b3ae41](https://linux-hardware.org/?probe=64a3b3ae41) | Oct 24, 2021 |
| Fujitsu       | D2950-A1 S26361-D2950-A1    | [cc46a59d6c](https://linux-hardware.org/?probe=cc46a59d6c) | Oct 24, 2021 |
| MSI           | P55-CD53                    | [c1c364dbc1](https://linux-hardware.org/?probe=c1c364dbc1) | Oct 24, 2021 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [fca2aa4310](https://linux-hardware.org/?probe=fca2aa4310) | Oct 23, 2021 |
| Dell          | 0VHXCD A00                  | [7c99a6ed29](https://linux-hardware.org/?probe=7c99a6ed29) | Oct 22, 2021 |
| ASRock        | 970 Pro3 R2.0               | [915961c057](https://linux-hardware.org/?probe=915961c057) | Oct 22, 2021 |
| Biostar       | A68N-5100                   | [bc5b7a2417](https://linux-hardware.org/?probe=bc5b7a2417) | Oct 22, 2021 |
| MSI           | Z68A-G43                    | [b781916d8e](https://linux-hardware.org/?probe=b781916d8e) | Oct 22, 2021 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [baee5192b6](https://linux-hardware.org/?probe=baee5192b6) | Oct 22, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [666f084a0f](https://linux-hardware.org/?probe=666f084a0f) | Oct 21, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [395d19ae36](https://linux-hardware.org/?probe=395d19ae36) | Oct 21, 2021 |
| HP            | 1589                        | [49c747efad](https://linux-hardware.org/?probe=49c747efad) | Oct 21, 2021 |
| Unknown       | Phitronics G41-M3           | [a6ccedb5bd](https://linux-hardware.org/?probe=a6ccedb5bd) | Oct 20, 2021 |
| Unknown       | Phitronics G41-M3           | [fbe886aee7](https://linux-hardware.org/?probe=fbe886aee7) | Oct 20, 2021 |
| Unknown       | Unknown                     | [8c412b3b5b](https://linux-hardware.org/?probe=8c412b3b5b) | Oct 20, 2021 |
| Gigabyte      | B75M-D2V                    | [9fc60b0ba8](https://linux-hardware.org/?probe=9fc60b0ba8) | Oct 19, 2021 |
| HP            | 2B38                        | [2cf327f158](https://linux-hardware.org/?probe=2cf327f158) | Oct 18, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [2f5f509752](https://linux-hardware.org/?probe=2f5f509752) | Oct 18, 2021 |
| Gigabyte      | Z490 AORUS ELITE            | [a7ea75f7c5](https://linux-hardware.org/?probe=a7ea75f7c5) | Oct 18, 2021 |
| ASUSTek       | 970 PRO GAMING/AURA         | [9f22e32d08](https://linux-hardware.org/?probe=9f22e32d08) | Oct 17, 2021 |
| ASUSTek       | P6T                         | [69397b40d4](https://linux-hardware.org/?probe=69397b40d4) | Oct 17, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [058d7e8e3e](https://linux-hardware.org/?probe=058d7e8e3e) | Oct 17, 2021 |
| ASUSTek       | H81M-PLUS                   | [ce2e0740c8](https://linux-hardware.org/?probe=ce2e0740c8) | Oct 17, 2021 |
| ASUSTek       | H81M-PLUS                   | [a3dbbf3c03](https://linux-hardware.org/?probe=a3dbbf3c03) | Oct 17, 2021 |
| Lenovo        | SHARKBAY NOK                | [5de4ff60b0](https://linux-hardware.org/?probe=5de4ff60b0) | Oct 16, 2021 |
| Gigabyte      | H61M-S2PV                   | [e3806f5c09](https://linux-hardware.org/?probe=e3806f5c09) | Oct 16, 2021 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | [a89127ff6a](https://linux-hardware.org/?probe=a89127ff6a) | Oct 15, 2021 |
| Gigabyte      | 970A-DS3P                   | [7de05cdbc3](https://linux-hardware.org/?probe=7de05cdbc3) | Oct 15, 2021 |
| Gigabyte      | 970A-DS3P                   | [66b0e77a10](https://linux-hardware.org/?probe=66b0e77a10) | Oct 15, 2021 |
| Dell          | 0VHXCD A00                  | [ccd75d2752](https://linux-hardware.org/?probe=ccd75d2752) | Oct 15, 2021 |
| Gigabyte      | B450M DS3H WIFI-CF          | [c0beced761](https://linux-hardware.org/?probe=c0beced761) | Oct 14, 2021 |
| ASUSTek       | M5A78L                      | [a027b0f5ba](https://linux-hardware.org/?probe=a027b0f5ba) | Oct 12, 2021 |
| HP            | 81C7 MVB 0C                 | [23d528f392](https://linux-hardware.org/?probe=23d528f392) | Oct 12, 2021 |
| ASUSTek       | M5A78L                      | [071d7e45a0](https://linux-hardware.org/?probe=071d7e45a0) | Oct 11, 2021 |
| Biostar       | G41-M7                      | [94efede651](https://linux-hardware.org/?probe=94efede651) | Oct 10, 2021 |
| ASUSTek       | P7H55-M PRO                 | [1892bf50b9](https://linux-hardware.org/?probe=1892bf50b9) | Oct 09, 2021 |
| HP            | 81C7 MVB 0C                 | [5bfcd88031](https://linux-hardware.org/?probe=5bfcd88031) | Oct 09, 2021 |
| Biostar       | G41-M7                      | [4f1889a1de](https://linux-hardware.org/?probe=4f1889a1de) | Oct 09, 2021 |
| Dell          | 0D28YY A02                  | [237a82041b](https://linux-hardware.org/?probe=237a82041b) | Oct 09, 2021 |
| ASUSTek       | H87M-PLUS                   | [f0a1062216](https://linux-hardware.org/?probe=f0a1062216) | Oct 09, 2021 |
| Dell          | 0VHXCD A00                  | [7a2b25ff42](https://linux-hardware.org/?probe=7a2b25ff42) | Oct 08, 2021 |
| Dell          | 04Y8V0 A01                  | [453beab8c3](https://linux-hardware.org/?probe=453beab8c3) | Oct 08, 2021 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [c9d3dce156](https://linux-hardware.org/?probe=c9d3dce156) | Oct 08, 2021 |
| ASUSTek       | CM5570                      | [75b8bca0fa](https://linux-hardware.org/?probe=75b8bca0fa) | Oct 07, 2021 |
| HP            | 8591                        | [22dca8a98c](https://linux-hardware.org/?probe=22dca8a98c) | Oct 07, 2021 |
| Dell          | 0VHXCD A00                  | [7f81996b23](https://linux-hardware.org/?probe=7f81996b23) | Oct 07, 2021 |
| Dell          | 0D6H9T A02                  | [42b9320d55](https://linux-hardware.org/?probe=42b9320d55) | Oct 06, 2021 |
| Gigabyte      | H61M-S2PV                   | [ed77d40eeb](https://linux-hardware.org/?probe=ed77d40eeb) | Oct 05, 2021 |
| ASUSTek       | STRIX Z270E GAMING          | [173104cfcf](https://linux-hardware.org/?probe=173104cfcf) | Oct 04, 2021 |
| ASUSTek       | PRIME B360M-K               | [163b47753d](https://linux-hardware.org/?probe=163b47753d) | Oct 03, 2021 |
| MSI           | B150M MORTAR                | [224b713b5c](https://linux-hardware.org/?probe=224b713b5c) | Oct 03, 2021 |
| Gigabyte      | B560M AORUS ELITE           | [2c73a09463](https://linux-hardware.org/?probe=2c73a09463) | Oct 03, 2021 |
| Gigabyte      | H81M-S2PV                   | [a02538183c](https://linux-hardware.org/?probe=a02538183c) | Oct 01, 2021 |
| Gigabyte      | 970A-UD3P                   | [10d8a84245](https://linux-hardware.org/?probe=10d8a84245) | Oct 01, 2021 |
| Gigabyte      | B550 AORUS ELITE V2         | [2a8da86d79](https://linux-hardware.org/?probe=2a8da86d79) | Oct 01, 2021 |
| Lenovo        | 102F SDK0J40697 WIN 3305... | [b6eca9083a](https://linux-hardware.org/?probe=b6eca9083a) | Oct 01, 2021 |
| Lenovo        | 102F SDK0J40697 WIN 3305... | [415f0d9244](https://linux-hardware.org/?probe=415f0d9244) | Oct 01, 2021 |
| Dell          | 0HN7XN A00                  | [cc8a68bbd6](https://linux-hardware.org/?probe=cc8a68bbd6) | Sep 30, 2021 |
| ASRock        | Z490 Extreme4               | [8137456421](https://linux-hardware.org/?probe=8137456421) | Sep 30, 2021 |
| ASRock        | Z490 Extreme4               | [3411428e31](https://linux-hardware.org/?probe=3411428e31) | Sep 30, 2021 |
| Dell          | 0HN7XN A00                  | [5f56956871](https://linux-hardware.org/?probe=5f56956871) | Sep 30, 2021 |
| ASRock        | H61M-VG4                    | [33c6d2d214](https://linux-hardware.org/?probe=33c6d2d214) | Sep 30, 2021 |
| Lenovo        | IdeaCentre K330             | [ed6e765fea](https://linux-hardware.org/?probe=ed6e765fea) | Sep 29, 2021 |
| Gigabyte      | J4005ND2P-CF                | [699985f9e6](https://linux-hardware.org/?probe=699985f9e6) | Sep 28, 2021 |
| Gigabyte      | J4005ND2P-CF                | [d82bdfcf17](https://linux-hardware.org/?probe=d82bdfcf17) | Sep 28, 2021 |
| ASUSTek       | PRIME B450M-A               | [d5b8eb94d7](https://linux-hardware.org/?probe=d5b8eb94d7) | Sep 28, 2021 |
| Dell          | 0TNXNR A01                  | [781c19cc33](https://linux-hardware.org/?probe=781c19cc33) | Sep 27, 2021 |
| Dell          | 0D6H9T A02                  | [30e914656e](https://linux-hardware.org/?probe=30e914656e) | Sep 27, 2021 |
| ASUSTek       | TUF Gaming X570-PRO         | [0625659706](https://linux-hardware.org/?probe=0625659706) | Sep 27, 2021 |
| Dell          | 0TP406                      | [39f9e67ae2](https://linux-hardware.org/?probe=39f9e67ae2) | Sep 26, 2021 |
| HP            | 18E7                        | [94f692683b](https://linux-hardware.org/?probe=94f692683b) | Sep 26, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | [4bc5eb3bbc](https://linux-hardware.org/?probe=4bc5eb3bbc) | Sep 25, 2021 |
| eMachines     | EL1850G                     | [f5b47069bb](https://linux-hardware.org/?probe=f5b47069bb) | Sep 25, 2021 |
| Lenovo        | ThinkCentre M58 3231W2Y     | [a2da2733ac](https://linux-hardware.org/?probe=a2da2733ac) | Sep 25, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [5cc1a01b2f](https://linux-hardware.org/?probe=5cc1a01b2f) | Sep 25, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [2b341862f1](https://linux-hardware.org/?probe=2b341862f1) | Sep 25, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | [65ebe53761](https://linux-hardware.org/?probe=65ebe53761) | Sep 25, 2021 |
| MSI           | B75MA-P45                   | [663af51c43](https://linux-hardware.org/?probe=663af51c43) | Sep 24, 2021 |
| MSI           | B75MA-P45                   | [4d4844cfbe](https://linux-hardware.org/?probe=4d4844cfbe) | Sep 24, 2021 |
| Lenovo        | ThinkCentre M81 0385AW6     | [dc87018670](https://linux-hardware.org/?probe=dc87018670) | Sep 24, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [8617cbbc27](https://linux-hardware.org/?probe=8617cbbc27) | Sep 24, 2021 |
| ASRock        | 775VM800                    | [e07158e4ab](https://linux-hardware.org/?probe=e07158e4ab) | Sep 24, 2021 |
| HP            | 18E7                        | [29fa39d7e9](https://linux-hardware.org/?probe=29fa39d7e9) | Sep 23, 2021 |
| ASRock        | 880GMH/U3S3                 | [ec55312287](https://linux-hardware.org/?probe=ec55312287) | Sep 23, 2021 |
| Gigabyte      | B75M-D3H                    | [cb23f25d7f](https://linux-hardware.org/?probe=cb23f25d7f) | Sep 23, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [74410f0d0c](https://linux-hardware.org/?probe=74410f0d0c) | Sep 23, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [ad81766325](https://linux-hardware.org/?probe=ad81766325) | Sep 23, 2021 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [bc7d0dc232](https://linux-hardware.org/?probe=bc7d0dc232) | Sep 22, 2021 |
| Lenovo        | ThinkCentre M81 0385AW6     | [529a9f4c74](https://linux-hardware.org/?probe=529a9f4c74) | Sep 22, 2021 |
| HP            | 213D A01                    | [8d4dd8359c](https://linux-hardware.org/?probe=8d4dd8359c) | Sep 21, 2021 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [3354edcb58](https://linux-hardware.org/?probe=3354edcb58) | Sep 21, 2021 |
| Gigabyte      | B75M-D3H                    | [3ef59689e6](https://linux-hardware.org/?probe=3ef59689e6) | Sep 21, 2021 |
| MSI           | H81M-E33                    | [5ef84c22e6](https://linux-hardware.org/?probe=5ef84c22e6) | Sep 20, 2021 |
| MSI           | H81M-E33                    | [db96085729](https://linux-hardware.org/?probe=db96085729) | Sep 20, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [a0b7d0cf25](https://linux-hardware.org/?probe=a0b7d0cf25) | Sep 20, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [c05636068f](https://linux-hardware.org/?probe=c05636068f) | Sep 20, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [1a012b3021](https://linux-hardware.org/?probe=1a012b3021) | Sep 20, 2021 |
| ASUSTek       | M5A78L-M LX V2              | [b9259e3604](https://linux-hardware.org/?probe=b9259e3604) | Sep 20, 2021 |
| ASUSTek       | M5A78L-M LX V2              | [9eb1254056](https://linux-hardware.org/?probe=9eb1254056) | Sep 19, 2021 |
| Gigabyte      | Z77-D3H                     | [c86625aa34](https://linux-hardware.org/?probe=c86625aa34) | Sep 19, 2021 |
| HP            | 2B28                        | [14681c925a](https://linux-hardware.org/?probe=14681c925a) | Sep 19, 2021 |
| Sapphire      | Pure Platinum 970A-PLUS     | [d64d86eced](https://linux-hardware.org/?probe=d64d86eced) | Sep 19, 2021 |
| ASRock        | FM2A58M-DG3+                | [183fc0dd5e](https://linux-hardware.org/?probe=183fc0dd5e) | Sep 18, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [bc3e2da7f3](https://linux-hardware.org/?probe=bc3e2da7f3) | Sep 18, 2021 |
| Gigabyte      | A320M-S2H-CF                | [e8f361170f](https://linux-hardware.org/?probe=e8f361170f) | Sep 18, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [30f36dc15d](https://linux-hardware.org/?probe=30f36dc15d) | Sep 17, 2021 |
| ASRock        | B450 Pro4                   | [042032eec7](https://linux-hardware.org/?probe=042032eec7) | Sep 16, 2021 |
| Intel         | X99                         | [814b3326d1](https://linux-hardware.org/?probe=814b3326d1) | Sep 15, 2021 |
| NCR           | Talladega                   | [95445fa221](https://linux-hardware.org/?probe=95445fa221) | Sep 14, 2021 |
| Foxconn       | 17A0                        | [06052023d3](https://linux-hardware.org/?probe=06052023d3) | Sep 14, 2021 |
| MSI           | B75MA-P45                   | [874dcada55](https://linux-hardware.org/?probe=874dcada55) | Sep 14, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [b3b1991c64](https://linux-hardware.org/?probe=b3b1991c64) | Sep 14, 2021 |
| ASUSTek       | NARRA3                      | [93db4618cc](https://linux-hardware.org/?probe=93db4618cc) | Sep 14, 2021 |
| ASUSTek       | Benicia                     | [2a764dd662](https://linux-hardware.org/?probe=2a764dd662) | Sep 13, 2021 |
| ASUSTek       | Maximus VIII RANGER         | [6928772253](https://linux-hardware.org/?probe=6928772253) | Sep 12, 2021 |
| ASUSTek       | Maximus VIII RANGER         | [93a0d7ac6a](https://linux-hardware.org/?probe=93a0d7ac6a) | Sep 12, 2021 |
| HP            | 339A                        | [9284a70a92](https://linux-hardware.org/?probe=9284a70a92) | Sep 12, 2021 |
| ASUSTek       | P5Q                         | [8693b86435](https://linux-hardware.org/?probe=8693b86435) | Sep 12, 2021 |
| NCR           | Talladega                   | [6de6d8c2a3](https://linux-hardware.org/?probe=6de6d8c2a3) | Sep 12, 2021 |
| Gigabyte      | 970A-DS3P                   | [8b0f703471](https://linux-hardware.org/?probe=8b0f703471) | Sep 11, 2021 |
| Lenovo        | SDK0E50519 WIN              | [7c58527193](https://linux-hardware.org/?probe=7c58527193) | Sep 11, 2021 |
| Intel         | X79M-S                      | [95d22f6e90](https://linux-hardware.org/?probe=95d22f6e90) | Sep 11, 2021 |
| ASUSTek       | P5GC-MX/1333                | [1ff7b16ce4](https://linux-hardware.org/?probe=1ff7b16ce4) | Sep 10, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [dab9a23b27](https://linux-hardware.org/?probe=dab9a23b27) | Sep 10, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [34e6b7697f](https://linux-hardware.org/?probe=34e6b7697f) | Sep 09, 2021 |
| ASUSTek       | ROG Maximus X HERO          | [5ce713a2f7](https://linux-hardware.org/?probe=5ce713a2f7) | Sep 09, 2021 |
| HP            | 2187 A01                    | [0c11e3b726](https://linux-hardware.org/?probe=0c11e3b726) | Sep 09, 2021 |
| MSI           | B450M MORTAR MAX            | [f40c6b596c](https://linux-hardware.org/?probe=f40c6b596c) | Sep 08, 2021 |
| Dell          | 09KPNV A01                  | [f3c9b271f1](https://linux-hardware.org/?probe=f3c9b271f1) | Sep 08, 2021 |
| MSI           | H81M-P33                    | [92b799f852](https://linux-hardware.org/?probe=92b799f852) | Sep 08, 2021 |
| MSI           | B450M MORTAR MAX            | [17c58396b6](https://linux-hardware.org/?probe=17c58396b6) | Sep 08, 2021 |
| MSI           | B450M MORTAR MAX            | [dfe73847d3](https://linux-hardware.org/?probe=dfe73847d3) | Sep 08, 2021 |
| Dell          | 0D28YY A03                  | [3eb7b9cb7b](https://linux-hardware.org/?probe=3eb7b9cb7b) | Sep 08, 2021 |
| ASUSTek       | P5G41T-M LX3                | [2f680da4b8](https://linux-hardware.org/?probe=2f680da4b8) | Sep 07, 2021 |
| Unknown       | Unknown                     | [b00795951c](https://linux-hardware.org/?probe=b00795951c) | Sep 07, 2021 |
| MSI           | B560M PRO-VDH               | [807eed7553](https://linux-hardware.org/?probe=807eed7553) | Sep 06, 2021 |
| ASRock        | Q1900M                      | [3f08533d5f](https://linux-hardware.org/?probe=3f08533d5f) | Sep 06, 2021 |
| ASRock        | Q1900M                      | [d342919044](https://linux-hardware.org/?probe=d342919044) | Sep 06, 2021 |
| Intel         | X79M-S                      | [e45160873d](https://linux-hardware.org/?probe=e45160873d) | Sep 06, 2021 |
| ASUSTek       | M5A97                       | [28754f0456](https://linux-hardware.org/?probe=28754f0456) | Sep 06, 2021 |
| Gigabyte      | G31M-ES2L                   | [d94c35ce11](https://linux-hardware.org/?probe=d94c35ce11) | Sep 05, 2021 |
| MSI           | IONA                        | [8a4454604a](https://linux-hardware.org/?probe=8a4454604a) | Sep 05, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [791768dfbd](https://linux-hardware.org/?probe=791768dfbd) | Sep 04, 2021 |
| MSI           | IONA                        | [b775cef84a](https://linux-hardware.org/?probe=b775cef84a) | Sep 04, 2021 |
| ASUSTek       | NARRA3                      | [920ab9b385](https://linux-hardware.org/?probe=920ab9b385) | Sep 04, 2021 |
| Gigabyte      | Z490 AORUS ELITE            | [149099265c](https://linux-hardware.org/?probe=149099265c) | Sep 04, 2021 |
| Intel         | DQ77MK AAG39642-500         | [391c101a92](https://linux-hardware.org/?probe=391c101a92) | Sep 04, 2021 |
| HP            | 2B4B                        | [d36296bddf](https://linux-hardware.org/?probe=d36296bddf) | Sep 04, 2021 |
| ASUSTek       | Z170I PRO GAMING            | [9e6ccaa1f3](https://linux-hardware.org/?probe=9e6ccaa1f3) | Sep 04, 2021 |
| Biostar       | X470NH                      | [f0449b9946](https://linux-hardware.org/?probe=f0449b9946) | Sep 04, 2021 |
| Gigabyte      | A320M-S2H-CF                | [126d9974b1](https://linux-hardware.org/?probe=126d9974b1) | Sep 03, 2021 |
| HP            | 1497                        | [fd4cf5c840](https://linux-hardware.org/?probe=fd4cf5c840) | Sep 01, 2021 |
| Gigabyte      | B460M DS3H                  | [ef23780b19](https://linux-hardware.org/?probe=ef23780b19) | Aug 31, 2021 |
| Positivo      | POS-PIH81DI                 | [baa289fe51](https://linux-hardware.org/?probe=baa289fe51) | Aug 31, 2021 |
| HP            | 339A                        | [5a5ab8d1c2](https://linux-hardware.org/?probe=5a5ab8d1c2) | Aug 31, 2021 |
| HP            | 339A                        | [c0043e4c4c](https://linux-hardware.org/?probe=c0043e4c4c) | Aug 31, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [4c711d446d](https://linux-hardware.org/?probe=4c711d446d) | Aug 31, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [efb9bccc60](https://linux-hardware.org/?probe=efb9bccc60) | Aug 31, 2021 |
| Intel         | DQ77MK AAG39642-500         | [000d760a55](https://linux-hardware.org/?probe=000d760a55) | Aug 30, 2021 |
| Positivo      | POS-PIH81DI                 | [3b05a7b317](https://linux-hardware.org/?probe=3b05a7b317) | Aug 30, 2021 |
| MSI           | Z87-G43                     | [a219ff197d](https://linux-hardware.org/?probe=a219ff197d) | Aug 29, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [01a43874df](https://linux-hardware.org/?probe=01a43874df) | Aug 28, 2021 |
| ASUSTek       | PRIME A320M-K               | [f7a948129f](https://linux-hardware.org/?probe=f7a948129f) | Aug 28, 2021 |
| ASUSTek       | P8H61-M LX2 R2.0            | [5cd3f43e28](https://linux-hardware.org/?probe=5cd3f43e28) | Aug 28, 2021 |
| Gigabyte      | A320M-S2H-CF                | [6ed5f8c32b](https://linux-hardware.org/?probe=6ed5f8c32b) | Aug 27, 2021 |
| ASRock        | Z390 Phantom Gaming 4-IB    | [b01269fbc1](https://linux-hardware.org/?probe=b01269fbc1) | Aug 27, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [51661e959e](https://linux-hardware.org/?probe=51661e959e) | Aug 26, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [3a7eb89cd8](https://linux-hardware.org/?probe=3a7eb89cd8) | Aug 25, 2021 |
| HP            | 802E                        | [3ee51e8a56](https://linux-hardware.org/?probe=3ee51e8a56) | Aug 25, 2021 |
| ASUSTek       | P8Z77-V LX                  | [314859d762](https://linux-hardware.org/?probe=314859d762) | Aug 25, 2021 |
| ASUSTek       | P8Z77-V LX                  | [faaf8bc158](https://linux-hardware.org/?probe=faaf8bc158) | Aug 25, 2021 |
| Dell          | 088DT1 A01                  | [8620323354](https://linux-hardware.org/?probe=8620323354) | Aug 25, 2021 |
| Dell          | 0TP406                      | [72a3d9ac12](https://linux-hardware.org/?probe=72a3d9ac12) | Aug 25, 2021 |
| HP            | 2B4B                        | [4c5411522b](https://linux-hardware.org/?probe=4c5411522b) | Aug 25, 2021 |
| Gigabyte      | B85M-D3H                    | [906a3e006c](https://linux-hardware.org/?probe=906a3e006c) | Aug 24, 2021 |
| Gigabyte      | B85M-D3H                    | [9f369218ff](https://linux-hardware.org/?probe=9f369218ff) | Aug 24, 2021 |
| ASUSTek       | P8Z77-V LE                  | [a720e3326a](https://linux-hardware.org/?probe=a720e3326a) | Aug 23, 2021 |
| MSI           | B450M PRO-M2 MAX            | [e6f053c5be](https://linux-hardware.org/?probe=e6f053c5be) | Aug 22, 2021 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [15175b4f4f](https://linux-hardware.org/?probe=15175b4f4f) | Aug 22, 2021 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [02ccc1eb70](https://linux-hardware.org/?probe=02ccc1eb70) | Aug 22, 2021 |
| ASUSTek       | M5A97 R2.0                  | [372a125910](https://linux-hardware.org/?probe=372a125910) | Aug 22, 2021 |
| Lenovo        | Unknown                     | [b4e9579228](https://linux-hardware.org/?probe=b4e9579228) | Aug 21, 2021 |
| Lenovo        | Unknown                     | [12088eed17](https://linux-hardware.org/?probe=12088eed17) | Aug 21, 2021 |
| MSI           | B450M PRO-M2 MAX            | [68c6a2734b](https://linux-hardware.org/?probe=68c6a2734b) | Aug 21, 2021 |
| Intel         | DB75EN AAG39650-303         | [4bbb9f60f9](https://linux-hardware.org/?probe=4bbb9f60f9) | Aug 20, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [63cbb9e7fd](https://linux-hardware.org/?probe=63cbb9e7fd) | Aug 19, 2021 |
| MSI           | Z97 XPOWER AC               | [c68138439d](https://linux-hardware.org/?probe=c68138439d) | Aug 19, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [d78450d852](https://linux-hardware.org/?probe=d78450d852) | Aug 19, 2021 |
| Acer          | Aspire XC-605G              | [8bb6f8ef72](https://linux-hardware.org/?probe=8bb6f8ef72) | Aug 18, 2021 |
| ASUSTek       | B85M-G R2.0                 | [daf6bf889f](https://linux-hardware.org/?probe=daf6bf889f) | Aug 18, 2021 |
| MSI           | Z270-A PRO                  | [3be5b7f90e](https://linux-hardware.org/?probe=3be5b7f90e) | Aug 18, 2021 |
| Gigabyte      | B550M DS3H                  | [4b687b4c17](https://linux-hardware.org/?probe=4b687b4c17) | Aug 16, 2021 |
| ASUSTek       | Z97-C                       | [97b71d18de](https://linux-hardware.org/?probe=97b71d18de) | Aug 16, 2021 |
| ASUSTek       | Z97-C                       | [a1f448c1f6](https://linux-hardware.org/?probe=a1f448c1f6) | Aug 15, 2021 |
| ASUSTek       | PRIME X570-PRO              | [fb7eb46b29](https://linux-hardware.org/?probe=fb7eb46b29) | Aug 11, 2021 |
| ASUSTek       | SABERTOOTH Z97 MARK 1       | [fb8a0b07d1](https://linux-hardware.org/?probe=fb8a0b07d1) | Aug 10, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [4d9eaaf5a8](https://linux-hardware.org/?probe=4d9eaaf5a8) | Aug 09, 2021 |
| Gigabyte      | B550M H                     | [b26c567912](https://linux-hardware.org/?probe=b26c567912) | Aug 03, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [9c841a04d6](https://linux-hardware.org/?probe=9c841a04d6) | Aug 01, 2021 |
| Gigabyte      | H61M-USB3-B3                | [3c2020fbb6](https://linux-hardware.org/?probe=3c2020fbb6) | Jul 30, 2021 |
| Gigabyte      | H61M-USB3-B3                | [b3bbc6d937](https://linux-hardware.org/?probe=b3bbc6d937) | Jul 30, 2021 |
| Dell          | 0V8WGR A00                  | [2cf38ffd15](https://linux-hardware.org/?probe=2cf38ffd15) | Jul 14, 2021 |
| ASUSTek       | P8H61-M LE                  | [b0270beb17](https://linux-hardware.org/?probe=b0270beb17) | Jul 11, 2021 |
| ASUSTek       | P8H61-M LE                  | [896e6feb8a](https://linux-hardware.org/?probe=896e6feb8a) | Jul 11, 2021 |
| Lenovo        | 36C5 SDK0J40700 WIN 3258... | [20bf622c31](https://linux-hardware.org/?probe=20bf622c31) | Jun 25, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [35605881d6](https://linux-hardware.org/?probe=35605881d6) | Jun 23, 2021 |
| MSI           | 2AE0                        | [bce75d51cd](https://linux-hardware.org/?probe=bce75d51cd) | Jun 23, 2021 |
| MSI           | 2AE0                        | [0412c710eb](https://linux-hardware.org/?probe=0412c710eb) | Jun 22, 2021 |
| ASUSTek       | PRIME X570-P                | [bca1e1b92f](https://linux-hardware.org/?probe=bca1e1b92f) | Jun 16, 2021 |
| ASUSTek       | PRIME X570-P                | [b3f6c76103](https://linux-hardware.org/?probe=b3f6c76103) | Jun 16, 2021 |
| Gigabyte      | B85-HD3                     | [c73931b3ff](https://linux-hardware.org/?probe=c73931b3ff) | Jun 13, 2021 |
| HP            | 843C                        | [ccff6e4f39](https://linux-hardware.org/?probe=ccff6e4f39) | Jun 08, 2021 |
| ASRock        | 990FX Extreme6              | [fc3b27abac](https://linux-hardware.org/?probe=fc3b27abac) | Jun 03, 2021 |
| HP            | 8591                        | [6f71430d88](https://linux-hardware.org/?probe=6f71430d88) | Jun 01, 2021 |
| HP            | 8591                        | [fc12c57885](https://linux-hardware.org/?probe=fc12c57885) | Jun 01, 2021 |
| ASRock        | 990FX Extreme6              | [0a228b18c1](https://linux-hardware.org/?probe=0a228b18c1) | May 30, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [0144616bb9](https://linux-hardware.org/?probe=0144616bb9) | May 27, 2021 |
| Gigabyte      | 945GCM-S2L                  | [9890da0efd](https://linux-hardware.org/?probe=9890da0efd) | May 27, 2021 |
| Gigabyte      | 945GCM-S2L                  | [61e1972b06](https://linux-hardware.org/?probe=61e1972b06) | May 27, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [887dbc1614](https://linux-hardware.org/?probe=887dbc1614) | May 24, 2021 |
| Biostar       | A320MH                      | [db3a18e1c3](https://linux-hardware.org/?probe=db3a18e1c3) | May 23, 2021 |
| Biostar       | A320MH                      | [ccb22fc057](https://linux-hardware.org/?probe=ccb22fc057) | May 23, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [0c314899c1](https://linux-hardware.org/?probe=0c314899c1) | May 23, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [ca773b28ee](https://linux-hardware.org/?probe=ca773b28ee) | May 19, 2021 |
| ASUSTek       | P8H61-I R2.0                | [c641f2aee4](https://linux-hardware.org/?probe=c641f2aee4) | May 16, 2021 |
| ASUSTek       | P8H61-I R2.0                | [500443b449](https://linux-hardware.org/?probe=500443b449) | May 16, 2021 |
| Lenovo        | Annapurna CRB NOK           | [7d4224df3f](https://linux-hardware.org/?probe=7d4224df3f) | May 13, 2021 |
| Lenovo        | Annapurna CRB NOK           | [adef2ac504](https://linux-hardware.org/?probe=adef2ac504) | May 13, 2021 |
| Dell          | 06D7TR A00                  | [1ccb5b0600](https://linux-hardware.org/?probe=1ccb5b0600) | May 01, 2021 |
| Pegatron      | Benicia                     | [df847c36d5](https://linux-hardware.org/?probe=df847c36d5) | Apr 25, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [7f46cdb7ab](https://linux-hardware.org/?probe=7f46cdb7ab) | Apr 24, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [b00e95f3db](https://linux-hardware.org/?probe=b00e95f3db) | Apr 22, 2021 |
| ASUSTek       | P5K                         | [0149b6c450](https://linux-hardware.org/?probe=0149b6c450) | Apr 22, 2021 |
| Dell          | 0PGKWF A02                  | [f963717b2c](https://linux-hardware.org/?probe=f963717b2c) | Apr 18, 2021 |
| Acer          | Aspire XC-605G              | [79d3d3a05e](https://linux-hardware.org/?probe=79d3d3a05e) | Mar 18, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 5.11.0-38-generic           | 62       | 8.08%   |
| 5.11.0-27-generic           | 56       | 7.3%    |
| 5.11.0-40-generic           | 50       | 6.52%   |
| 5.13.0-39-generic           | 48       | 6.26%   |
| 5.11.0-41-generic           | 41       | 5.35%   |
| 5.13.0-40-generic           | 38       | 4.95%   |
| 5.11.0-43-generic           | 36       | 4.69%   |
| 5.15.0-41-generic           | 35       | 4.56%   |
| 5.11.0-37-generic           | 35       | 4.56%   |
| 5.13.0-30-generic           | 32       | 4.17%   |
| 5.11.0-34-generic           | 31       | 4.04%   |
| 5.15.0-46-generic           | 29       | 3.78%   |
| 5.13.0-28-generic           | 29       | 3.78%   |
| 5.13.0-35-generic           | 28       | 3.65%   |
| 5.13.0-27-generic           | 26       | 3.39%   |
| 5.13.0-41-generic           | 25       | 3.26%   |
| 5.13.0-52-generic           | 22       | 2.87%   |
| 5.13.0-44-generic           | 22       | 2.87%   |
| 5.13.0-51-generic           | 17       | 2.22%   |
| 5.11.0-44-generic           | 14       | 1.83%   |
| 5.15.0-43-generic           | 13       | 1.69%   |
| 5.11.0-36-generic           | 12       | 1.56%   |
| 5.13.0-37-generic           | 11       | 1.43%   |
| 5.13.0-48-generic           | 8        | 1.04%   |
| 5.8.0-53-generic            | 7        | 0.91%   |
| 5.11.0-46-generic           | 6        | 0.78%   |
| 5.8.0-50-generic            | 5        | 0.65%   |
| 5.8.0-59-generic            | 4        | 0.52%   |
| 5.8.0-55-generic            | 4        | 0.52%   |
| 5.11.0-25-generic           | 4        | 0.52%   |
| 5.8.0-49-generic            | 3        | 0.39%   |
| 5.8.0-63-generic            | 2        | 0.26%   |
| 5.13.0-25-generic           | 2        | 0.26%   |
| 5.8.0-45-generic            | 1        | 0.13%   |
| 5.4.0-58-generic            | 1        | 0.13%   |
| 5.19.2-051902-generic       | 1        | 0.13%   |
| 5.17.9-051709-generic       | 1        | 0.13%   |
| 5.17.5-051705-generic       | 1        | 0.13%   |
| 5.17.1-051701-generic       | 1        | 0.13%   |
| 5.15.13-051513-generic      | 1        | 0.13%   |
| 5.15.0-10.2-liquorix-amd64  | 1        | 0.13%   |
| 5.14.0-1010-oem             | 1        | 0.13%   |
| 5.13.0-352203222222-generic | 1        | 0.13%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.0  | 333      | 46.12%  |
| 5.13.0  | 280      | 38.78%  |
| 5.15.0  | 77       | 10.66%  |
| 5.8.0   | 25       | 3.46%   |
| 5.4.0   | 1        | 0.14%   |
| 5.19.2  | 1        | 0.14%   |
| 5.17.9  | 1        | 0.14%   |
| 5.17.5  | 1        | 0.14%   |
| 5.17.1  | 1        | 0.14%   |
| 5.15.13 | 1        | 0.14%   |
| 5.14.0  | 1        | 0.14%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 333      | 46.12%  |
| 5.13    | 280      | 38.78%  |
| 5.15    | 78       | 10.8%   |
| 5.8     | 25       | 3.46%   |
| 5.17    | 3        | 0.42%   |
| 5.4     | 1        | 0.14%   |
| 5.19    | 1        | 0.14%   |
| 5.14    | 1        | 0.14%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 692      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 624      | 89.66%  |
| XFCE       | 65       | 9.34%   |
| Unknown    | 4        | 0.57%   |
| X-Cinnamon | 1        | 0.14%   |
| MATE       | 1        | 0.14%   |
| Cinnamon   | 1        | 0.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 689      | 99.14%  |
| Wayland | 4        | 0.58%   |
| Tty     | 1        | 0.14%   |
| Unknown | 1        | 0.14%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 589      | 84.38%  |
| GDM3    | 52       | 7.45%   |
| GDM     | 48       | 6.88%   |
| LightDM | 8        | 1.15%   |
| TDM     | 1        | 0.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 273      | 39.34%  |
| de_DE       | 76       | 10.95%  |
| en_GB       | 56       | 8.07%   |
| pt_BR       | 44       | 6.34%   |
| pl_PL       | 19       | 2.74%   |
| es_ES       | 18       | 2.59%   |
| it_IT       | 17       | 2.45%   |
| fr_FR       | 17       | 2.45%   |
| nl_NL       | 16       | 2.31%   |
| en_AU       | 16       | 2.31%   |
| en_IN       | 14       | 2.02%   |
| en_CA       | 14       | 2.02%   |
| ru_RU       | 10       | 1.44%   |
| es_MX       | 10       | 1.44%   |
| hu_HU       | 7        | 1.01%   |
| fr_CA       | 7        | 1.01%   |
| es_AR       | 7        | 1.01%   |
| en_ZA       | 6        | 0.86%   |
| cs_CZ       | 6        | 0.86%   |
| tr_TR       | 4        | 0.58%   |
| pt_PT       | 4        | 0.58%   |
| sv_SE       | 3        | 0.43%   |
| nl_BE       | 3        | 0.43%   |
| nb_NO       | 3        | 0.43%   |
| es_CL       | 3        | 0.43%   |
| en_NZ       | 3        | 0.43%   |
| el_GR       | 3        | 0.43%   |
| da_DK       | 3        | 0.43%   |
| sl_SI       | 2        | 0.29%   |
| sk_SK       | 2        | 0.29%   |
| ja_JP       | 2        | 0.29%   |
| es_VE       | 2        | 0.29%   |
| es_EC       | 2        | 0.29%   |
| de_CH       | 2        | 0.29%   |
| ar_EG       | 2        | 0.29%   |
| zh_TW       | 1        | 0.14%   |
| zh_CN       | 1        | 0.14%   |
| sr_RS@latin | 1        | 0.14%   |
| sr_RS       | 1        | 0.14%   |
| ru_UA       | 1        | 0.14%   |
| ko_KR       | 1        | 0.14%   |
| hr_HR       | 1        | 0.14%   |
| he_IL       | 1        | 0.14%   |
| fr_CH       | 1        | 0.14%   |
| fi_FI       | 1        | 0.14%   |
| es_US       | 1        | 0.14%   |
| es_PE       | 1        | 0.14%   |
| es_PA       | 1        | 0.14%   |
| es_NI       | 1        | 0.14%   |
| es_GT       | 1        | 0.14%   |
| en_SG       | 1        | 0.14%   |
| C           | 1        | 0.14%   |
| bg_BG       | 1        | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 392      | 56.24%  |
| EFI  | 305      | 43.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 650      | 93.93%  |
| Zfs      | 15       | 2.17%   |
| Overlay  | 11       | 1.59%   |
| Btrfs    | 8        | 1.16%   |
| Xfs      | 3        | 0.43%   |
| Ext3     | 2        | 0.29%   |
| Ext2     | 2        | 0.29%   |
| Reiserfs | 1        | 0.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 637      | 91.79%  |
| GPT     | 45       | 6.48%   |
| MBR     | 12       | 1.73%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 670      | 96.68%  |
| Yes       | 23       | 3.32%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 615      | 88.74%  |
| Yes       | 78       | 11.26%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 179      | 25.87%  |
| Gigabyte Technology | 117      | 16.91%  |
| MSI                 | 72       | 10.4%   |
| Dell                | 72       | 10.4%   |
| Hewlett-Packard     | 58       | 8.38%   |
| ASRock              | 56       | 8.09%   |
| Lenovo              | 30       | 4.34%   |
| Intel               | 20       | 2.89%   |
| Biostar             | 11       | 1.59%   |
| Foxconn             | 10       | 1.45%   |
| Acer                | 9        | 1.3%    |
| Fujitsu             | 8        | 1.16%   |
| Pegatron            | 7        | 1.01%   |
| Unknown             | 5        | 0.72%   |
| BESSTAR Tech        | 3        | 0.43%   |
| Shuttle             | 2        | 0.29%   |
| Positivo            | 2        | 0.29%   |
| Medion              | 2        | 0.29%   |
| Google              | 2        | 0.29%   |
| ECS                 | 2        | 0.29%   |
| Apple               | 2        | 0.29%   |
| Alienware           | 2        | 0.29%   |
| Wortmann AG         | 1        | 0.14%   |
| WIPRO               | 1        | 0.14%   |
| TYAN Computer       | 1        | 0.14%   |
| System76            | 1        | 0.14%   |
| Supermicro          | 1        | 0.14%   |
| Sapphire            | 1        | 0.14%   |
| Packard Bell        | 1        | 0.14%   |
| OEM_MB              | 1        | 0.14%   |
| OEM                 | 1        | 0.14%   |
| NCR                 | 1        | 0.14%   |
| MP                  | 1        | 0.14%   |
| MAXSUN              | 1        | 0.14%   |
| LORD ELECTRONICS    | 1        | 0.14%   |
| LattePanda          | 1        | 0.14%   |
| JGINYUE             | 1        | 0.14%   |
| IBM                 | 1        | 0.14%   |
| Huanan              | 1        | 0.14%   |
| Gateway             | 1        | 0.14%   |
| EVGA                | 1        | 0.14%   |
| eMachines           | 1        | 0.14%   |
| AOpen               | 1        | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 19       | 2.75%   |
| Dell OptiPlex 7010               | 8        | 1.16%   |
| Dell OptiPlex 790                | 6        | 0.87%   |
| Unknown                          | 6        | 0.87%   |
| MSI MS-7C02                      | 5        | 0.72%   |
| Dell OptiPlex 990                | 5        | 0.72%   |
| ASUS M5A78L-M/USB3               | 5        | 0.72%   |
| MSI MS-7817                      | 4        | 0.58%   |
| HP Compaq Pro 6300 SFF           | 4        | 0.58%   |
| Gigabyte B450 AORUS M            | 4        | 0.58%   |
| Dell Precision WorkStation T3500 | 4        | 0.58%   |
| Dell OptiPlex 780                | 4        | 0.58%   |
| ASUS TUF Gaming X570-PLUS        | 4        | 0.58%   |
| ASRock B450 Pro4                 | 4        | 0.58%   |
| Intel X79M-S                     | 3        | 0.43%   |
| HP ProDesk 600 G1 SFF            | 3        | 0.43%   |
| HP Compaq 6200 Pro SFF PC        | 3        | 0.43%   |
| Gigabyte X570 AORUS ELITE        | 3        | 0.43%   |
| Gigabyte A320M-S2H               | 3        | 0.43%   |
| Dell OptiPlex 360                | 3        | 0.43%   |
| Dell Inspiron 3847               | 3        | 0.43%   |
| ASUS PRIME X570-P                | 3        | 0.43%   |
| ASUS PRIME B450M-GAMING/BR       | 3        | 0.43%   |
| ASUS P8Z77-V LX                  | 3        | 0.43%   |
| ASUS M5A97 R2.0                  | 3        | 0.43%   |
| ASRock B450M Pro4                | 3        | 0.43%   |
| Pegatron NE502AV-ABA a6750t      | 2        | 0.29%   |
| MSI MS-7D19                      | 2        | 0.29%   |
| MSI MS-7C94                      | 2        | 0.29%   |
| MSI MS-7C37                      | 2        | 0.29%   |
| MSI MS-7B89                      | 2        | 0.29%   |
| MSI MS-7B85                      | 2        | 0.29%   |
| MSI MS-7798                      | 2        | 0.29%   |
| MSI MS-7693                      | 2        | 0.29%   |
| Intel H61                        | 2        | 0.29%   |
| Intel DQ77MK-R01                 | 2        | 0.29%   |
| HP Z420 Workstation              | 2        | 0.29%   |
| HP Z230 SFF Workstation          | 2        | 0.29%   |
| HP ProOne 400 G1 AiO             | 2        | 0.29%   |
| HP EliteDesk 800 G1 USDT         | 2        | 0.29%   |
| HP EliteDesk 800 G1 TWR          | 2        | 0.29%   |
| HP Compaq Pro 6300 MT            | 2        | 0.29%   |
| Gigabyte Z77-D3H                 | 2        | 0.29%   |
| Gigabyte X570 AORUS MASTER       | 2        | 0.29%   |
| Gigabyte H410M H V3              | 2        | 0.29%   |
| Gigabyte GA-78LMT-USB3 6.0       | 2        | 0.29%   |
| Gigabyte GA-78LMT-USB3           | 2        | 0.29%   |
| Gigabyte G31M-ES2L               | 2        | 0.29%   |
| Gigabyte B75M-D3H                | 2        | 0.29%   |
| Gigabyte B560M AORUS ELITE       | 2        | 0.29%   |
| Gigabyte B450M DS3H              | 2        | 0.29%   |
| Gigabyte B450 AORUS PRO WIFI     | 2        | 0.29%   |
| Gigabyte 970A-DS3P               | 2        | 0.29%   |
| Dell XPS420                      | 2        | 0.29%   |
| Dell Vostro 260                  | 2        | 0.29%   |
| Dell Vostro 200                  | 2        | 0.29%   |
| Dell Precision T1600             | 2        | 0.29%   |
| Dell OptiPlex 755                | 2        | 0.29%   |
| Dell OptiPlex 7040               | 2        | 0.29%   |
| Dell OptiPlex 380                | 2        | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 44       | 6.36%   |
| ASUS PRIME             | 29       | 4.19%   |
| ASUS ROG               | 20       | 2.89%   |
| ASUS All               | 19       | 2.75%   |
| Lenovo ThinkCentre     | 17       | 2.46%   |
| HP Compaq              | 16       | 2.31%   |
| ASUS TUF               | 15       | 2.17%   |
| HP EliteDesk           | 9        | 1.3%    |
| Gigabyte B450          | 9        | 1.3%    |
| ASUS M5A78L-M          | 8        | 1.16%   |
| Gigabyte X570          | 7        | 1.01%   |
| Dell Precision         | 7        | 1.01%   |
| ASRock B450            | 7        | 1.01%   |
| Acer Aspire            | 7        | 1.01%   |
| Fujitsu ESPRIMO        | 6        | 0.87%   |
| Dell Inspiron          | 6        | 0.87%   |
| ASUS M5A97             | 6        | 0.87%   |
| Unknown                | 6        | 0.87%   |
| MSI MS-7C02            | 5        | 0.72%   |
| Lenovo IdeaCentre      | 5        | 0.72%   |
| Gigabyte GA-78LMT-USB3 | 5        | 0.72%   |
| Dell Vostro            | 5        | 0.72%   |
| ASUS P8H61-M           | 5        | 0.72%   |
| ASRock B450M           | 5        | 0.72%   |
| MSI MS-7817            | 4        | 0.58%   |
| HP ProDesk             | 4        | 0.58%   |
| Gigabyte B450M         | 4        | 0.58%   |
| ASUS P8Z77-V           | 4        | 0.58%   |
| Intel X79M-S           | 3        | 0.43%   |
| Gigabyte G1.Sniper     | 3        | 0.43%   |
| Gigabyte A320M-S2H     | 3        | 0.43%   |
| Dell XPS               | 3        | 0.43%   |
| Dell Studio            | 3        | 0.43%   |
| ASUS P5KPL-AM          | 3        | 0.43%   |
| ASUS P5GC-MX           | 3        | 0.43%   |
| ASUS P5G41T-M          | 3        | 0.43%   |
| ASUS Maximus           | 3        | 0.43%   |
| Pegatron NE502AV-ABA   | 2        | 0.29%   |
| MSI MS-7D19            | 2        | 0.29%   |
| MSI MS-7C94            | 2        | 0.29%   |
| MSI MS-7C37            | 2        | 0.29%   |
| MSI MS-7B89            | 2        | 0.29%   |
| MSI MS-7B85            | 2        | 0.29%   |
| MSI MS-7798            | 2        | 0.29%   |
| MSI MS-7693            | 2        | 0.29%   |
| Lenovo ThinkStation    | 2        | 0.29%   |
| Lenovo Legion          | 2        | 0.29%   |
| Intel H61              | 2        | 0.29%   |
| Intel DQ77MK-R01       | 2        | 0.29%   |
| HP Z420                | 2        | 0.29%   |
| HP Z230                | 2        | 0.29%   |
| HP Z220                | 2        | 0.29%   |
| HP t620                | 2        | 0.29%   |
| HP ProOne              | 2        | 0.29%   |
| HP Pavilion            | 2        | 0.29%   |
| HP 290                 | 2        | 0.29%   |
| Gigabyte Z77-D3H       | 2        | 0.29%   |
| Gigabyte H410M         | 2        | 0.29%   |
| Gigabyte G31M-ES2L     | 2        | 0.29%   |
| Gigabyte B75M-D3H      | 2        | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2012    | 73       | 10.55%  |
| 2018    | 71       | 10.26%  |
| 2013    | 69       | 9.97%   |
| 2011    | 61       | 8.82%   |
| 2014    | 58       | 8.38%   |
| 2019    | 50       | 7.23%   |
| 2020    | 47       | 6.79%   |
| 2021    | 40       | 5.78%   |
| 2010    | 38       | 5.49%   |
| 2008    | 37       | 5.35%   |
| 2017    | 32       | 4.62%   |
| 2009    | 32       | 4.62%   |
| 2016    | 29       | 4.19%   |
| 2015    | 20       | 2.89%   |
| 2007    | 20       | 2.89%   |
| 2006    | 6        | 0.87%   |
| 2022    | 4        | 0.58%   |
| 2005    | 4        | 0.58%   |
| Unknown | 1        | 0.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 692      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 656      | 94.52%  |
| Enabled  | 38       | 5.48%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 690      | 99.71%  |
| Yes  | 2        | 0.29%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 180      | 25.75%  |
| 8.01-16.0   | 163      | 23.32%  |
| 32.01-64.0  | 100      | 14.31%  |
| 4.01-8.0    | 98       | 14.02%  |
| 3.01-4.0    | 97       | 13.88%  |
| 64.01-256.0 | 21       | 3%      |
| 1.01-2.0    | 18       | 2.58%   |
| 24.01-32.0  | 12       | 1.72%   |
| 2.01-3.0    | 9        | 1.29%   |
| 0.51-1.0    | 1        | 0.14%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 298      | 40.54%  |
| 2.01-3.0   | 226      | 30.75%  |
| 3.01-4.0   | 93       | 12.65%  |
| 4.01-8.0   | 88       | 11.97%  |
| 8.01-16.0  | 16       | 2.18%   |
| 0.51-1.0   | 9        | 1.22%   |
| 16.01-24.0 | 4        | 0.54%   |
| 0.01-0.5   | 1        | 0.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 294      | 41.64%  |
| 2      | 205      | 29.04%  |
| 3      | 93       | 13.17%  |
| 4      | 47       | 6.66%   |
| 5      | 28       | 3.97%   |
| 6      | 20       | 2.83%   |
| 7      | 7        | 0.99%   |
| 0      | 6        | 0.85%   |
| 8      | 5        | 0.71%   |
| 11     | 1        | 0.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 361      | 52.02%  |
| No        | 333      | 47.98%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 682      | 98.55%  |
| No        | 10       | 1.45%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 349      | 50.36%  |
| Yes       | 344      | 49.64%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 473      | 67.67%  |
| Yes       | 226      | 32.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country             | Desktops | Percent |
|---------------------|----------|---------|
| USA                 | 177      | 25.54%  |
| Germany             | 77       | 11.11%  |
| UK                  | 52       | 7.5%    |
| Brazil              | 47       | 6.78%   |
| Netherlands         | 24       | 3.46%   |
| Canada              | 24       | 3.46%   |
| Poland              | 20       | 2.89%   |
| Italy               | 20       | 2.89%   |
| Spain               | 19       | 2.74%   |
| Australia           | 17       | 2.45%   |
| France              | 15       | 2.16%   |
| India               | 14       | 2.02%   |
| Hungary             | 11       | 1.59%   |
| Mexico              | 10       | 1.44%   |
| Denmark             | 10       | 1.44%   |
| Russia              | 9        | 1.3%    |
| Norway              | 9        | 1.3%    |
| Argentina           | 9        | 1.3%    |
| Sweden              | 8        | 1.15%   |
| Switzerland         | 6        | 0.87%   |
| South Africa        | 6        | 0.87%   |
| Czechia             | 6        | 0.87%   |
| Turkey              | 5        | 0.72%   |
| Slovenia            | 5        | 0.72%   |
| Serbia              | 5        | 0.72%   |
| Greece              | 5        | 0.72%   |
| Portugal            | 4        | 0.58%   |
| Egypt               | 4        | 0.58%   |
| Croatia             | 4        | 0.58%   |
| Chile               | 4        | 0.58%   |
| Belgium             | 4        | 0.58%   |
| Ukraine             | 3        | 0.43%   |
| Slovakia            | 3        | 0.43%   |
| Romania             | 3        | 0.43%   |
| New Zealand         | 3        | 0.43%   |
| Malaysia            | 3        | 0.43%   |
| Japan               | 3        | 0.43%   |
| Austria             | 3        | 0.43%   |
| Vietnam             | 2        | 0.29%   |
| Venezuela           | 2        | 0.29%   |
| Taiwan              | 2        | 0.29%   |
| Lithuania           | 2        | 0.29%   |
| Indonesia           | 2        | 0.29%   |
| Finland             | 2        | 0.29%   |
| El Salvador         | 2        | 0.29%   |
| Ecuador             | 2        | 0.29%   |
| Cyprus              | 2        | 0.29%   |
| China               | 2        | 0.29%   |
| Bangladesh          | 2        | 0.29%   |
| Trinidad and Tobago | 1        | 0.14%   |
| Thailand            | 1        | 0.14%   |
| South Korea         | 1        | 0.14%   |
| Puerto Rico         | 1        | 0.14%   |
| Peru                | 1        | 0.14%   |
| Panama              | 1        | 0.14%   |
| Palestine           | 1        | 0.14%   |
| Nicaragua           | 1        | 0.14%   |
| Mozambique          | 1        | 0.14%   |
| Malta               | 1        | 0.14%   |
| Lebanon             | 1        | 0.14%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Berlin          | 7        | 1%      |
| Athens          | 5        | 0.71%   |
| Sao Paulo       | 4        | 0.57%   |
| Munich          | 4        | 0.57%   |
| Houston         | 4        | 0.57%   |
| Dallas          | 4        | 0.57%   |
| Copenhagen      | 4        | 0.57%   |
| Buenos Aires    | 4        | 0.57%   |
| Vienna          | 3        | 0.43%   |
| Sydney          | 3        | 0.43%   |
| Stuttgart       | 3        | 0.43%   |
| Rio de Janeiro  | 3        | 0.43%   |
| Richmond        | 3        | 0.43%   |
| Prague          | 3        | 0.43%   |
| Portland        | 3        | 0.43%   |
| Milwaukee       | 3        | 0.43%   |
| Milan           | 3        | 0.43%   |
| Mentor          | 3        | 0.43%   |
| Laval           | 3        | 0.43%   |
| Hamburg         | 3        | 0.43%   |
| Fortaleza       | 3        | 0.43%   |
| Dayton          | 3        | 0.43%   |
| Cape Town       | 3        | 0.43%   |
| Budapest        | 3        | 0.43%   |
| Brasília       | 3        | 0.43%   |
| Almería        | 3        | 0.43%   |
| Zurich          | 2        | 0.29%   |
| Zagreb          | 2        | 0.29%   |
| Wylie           | 2        | 0.29%   |
| Wuppertal       | 2        | 0.29%   |
| Warsaw          | 2        | 0.29%   |
| Vrhnika         | 2        | 0.29%   |
| Victoria        | 2        | 0.29%   |
| Vanse           | 2        | 0.29%   |
| Vadodara        | 2        | 0.29%   |
| Twickenham      | 2        | 0.29%   |
| The Hague       | 2        | 0.29%   |
| Stoke-on-Trent  | 2        | 0.29%   |
| Santo André    | 2        | 0.29%   |
| Santiago        | 2        | 0.29%   |
| Salt Lake City  | 2        | 0.29%   |
| Rotterdam       | 2        | 0.29%   |
| Roosendaal      | 2        | 0.29%   |
| Rome            | 2        | 0.29%   |
| Queens          | 2        | 0.29%   |
| Poznan          | 2        | 0.29%   |
| Porto Velho     | 2        | 0.29%   |
| Plano           | 2        | 0.29%   |
| Petaling Jaya   | 2        | 0.29%   |
| Perth           | 2        | 0.29%   |
| Oslo            | 2        | 0.29%   |
| Oscoda          | 2        | 0.29%   |
| Orlando         | 2        | 0.29%   |
| Oosterbeek      | 2        | 0.29%   |
| Neath           | 2        | 0.29%   |
| Mount Olive     | 2        | 0.29%   |
| Melbourne       | 2        | 0.29%   |
| Los Angeles     | 2        | 0.29%   |
| Lomas de Zamora | 2        | 0.29%   |
| Livingston      | 2        | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 256      | 392    | 20.66%  |
| WDC                         | 202      | 289    | 16.3%   |
| Samsung Electronics         | 164      | 258    | 13.24%  |
| Kingston                    | 86       | 112    | 6.94%   |
| SanDisk                     | 70       | 82     | 5.65%   |
| Toshiba                     | 64       | 76     | 5.17%   |
| Hitachi                     | 59       | 75     | 4.76%   |
| Crucial                     | 49       | 60     | 3.95%   |
| A-DATA Technology           | 19       | 23     | 1.53%   |
| Phison                      | 18       | 20     | 1.45%   |
| Silicon Motion              | 16       | 23     | 1.29%   |
| China                       | 15       | 17     | 1.21%   |
| Unknown                     | 14       | 27     | 1.13%   |
| Intel                       | 11       | 14     | 0.89%   |
| HGST                        | 10       | 15     | 0.81%   |
| SK hynix                    | 9        | 13     | 0.73%   |
| PNY                         | 8        | 10     | 0.65%   |
| OCZ                         | 8        | 9      | 0.65%   |
| Intenso                     | 8        | 9      | 0.65%   |
| Hewlett-Packard             | 8        | 12     | 0.65%   |
| Micron Technology           | 7        | 7      | 0.56%   |
| Gigabyte Technology         | 7        | 9      | 0.56%   |
| Maxtor                      | 6        | 7      | 0.48%   |
| Lexar                       | 6        | 6      | 0.48%   |
| XPG                         | 5        | 5      | 0.4%    |
| SPCC                        | 5        | 6      | 0.4%    |
| Realtek Semiconductor       | 5        | 5      | 0.4%    |
| Micron/Crucial Technology   | 5        | 5      | 0.4%    |
| JMicron Technology          | 5        | 6      | 0.4%    |
| GOODRAM                     | 5        | 5      | 0.4%    |
| Super Talent                | 4        | 5      | 0.32%   |
| SABRENT                     | 4        | 4      | 0.32%   |
| Netac                       | 4        | 5      | 0.32%   |
| KingSpec                    | 4        | 5      | 0.32%   |
| Corsair                     | 4        | 4      | 0.32%   |
| Team                        | 3        | 5      | 0.24%   |
| Patriot                     | 3        | 5      | 0.24%   |
| Leven                       | 3        | 4      | 0.24%   |
| Apple                       | 3        | 3      | 0.24%   |
| Apacer                      | 3        | 3      | 0.24%   |
| Unknown                     | 3        | 3      | 0.24%   |
| XrayDisk                    | 2        | 3      | 0.16%   |
| WD MediaMax                 | 2        | 4      | 0.16%   |
| Transcend                   | 2        | 2      | 0.16%   |
| Plextor                     | 2        | 3      | 0.16%   |
| Pioneer                     | 2        | 2      | 0.16%   |
| MAXIO Technology (Hangzhou) | 2        | 2      | 0.16%   |
| KIOXIA-EXCERIA              | 2        | 5      | 0.16%   |
| KingFast                    | 2        | 2      | 0.16%   |
| HS-SSD-C100                 | 2        | 2      | 0.16%   |
| Dogfish                     | 2        | 3      | 0.16%   |
| ADATA Technology            | 2        | 2      | 0.16%   |
| Zheino                      | 1        | 1      | 0.08%   |
| WALRAM                      | 1        | 1      | 0.08%   |
| Verbatim                    | 1        | 1      | 0.08%   |
| USB3.2                      | 1        | 1      | 0.08%   |
| USB3.0                      | 1        | 2      | 0.08%   |
| TwinMOS                     | 1        | 1      | 0.08%   |
| Teclast                     | 1        | 1      | 0.08%   |
| T-CREATE                    | 1        | 1      | 0.08%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB    | 29       | 2%      |
| Kingston SA400S37240G 240GB SSD    | 21       | 1.45%   |
| Samsung SSD 860 EVO 500GB          | 16       | 1.1%    |
| Samsung NVMe SSD Drive 1TB         | 16       | 1.1%    |
| Seagate ST1000DM010-2EP102 1TB     | 15       | 1.04%   |
| Crucial CT240BX500SSD1 240GB       | 15       | 1.04%   |
| WDC WD10EZEX-08WN4A0 1TB           | 14       | 0.97%   |
| Samsung SSD 850 EVO 250GB          | 14       | 0.97%   |
| Samsung NVMe SSD Drive 500GB       | 13       | 0.9%    |
| Seagate ST1000DM003-1CH162 1TB     | 12       | 0.83%   |
| Seagate ST3500418AS 500GB          | 11       | 0.76%   |
| Kingston SA400S37120G 120GB SSD    | 11       | 0.76%   |
| Seagate ST3500413AS 500GB          | 10       | 0.69%   |
| SanDisk NVMe SSD Drive 500GB       | 10       | 0.69%   |
| SanDisk NVMe SSD Drive 1TB         | 10       | 0.69%   |
| Toshiba HDWD110 1TB                | 9        | 0.62%   |
| Seagate ST3500312CS 500GB          | 9        | 0.62%   |
| Seagate ST1000DM003-1SB102 1TB     | 9        | 0.62%   |
| Samsung HD103SJ 1TB                | 9        | 0.62%   |
| Kingston SV300S37A120G 120GB SSD   | 9        | 0.62%   |
| Seagate ST2000DM008-2FR102 2TB     | 8        | 0.55%   |
| Samsung SSD 840 EVO 250GB          | 8        | 0.55%   |
| WDC WD10EZEX-00WN4A0 1TB           | 7        | 0.48%   |
| Toshiba DT01ACA100 1TB             | 7        | 0.48%   |
| Toshiba DT01ACA050 500GB           | 7        | 0.48%   |
| Seagate ST2000DM001-1CH164 2TB     | 7        | 0.48%   |
| Seagate ST1000DM003-1ER162 1TB     | 7        | 0.48%   |
| Seagate Expansion Desk 4TB         | 7        | 0.48%   |
| SanDisk SSD PLUS 240GB             | 7        | 0.48%   |
| Samsung SSD 870 EVO 1TB            | 7        | 0.48%   |
| Samsung SSD 850 EVO 500GB          | 7        | 0.48%   |
| Samsung SSD 840 EVO 120GB          | 7        | 0.48%   |
| Kingston SA400S37480G 480GB SSD    | 7        | 0.48%   |
| Crucial CT500MX500SSD1 500GB       | 7        | 0.48%   |
| Crucial CT1000MX500SSD1 1TB        | 7        | 0.48%   |
| Unknown SD/MMC/MS PRO 128GB        | 6        | 0.41%   |
| Seagate ST4000DM004-2CV104 4TB     | 6        | 0.41%   |
| Seagate ST4000DM000-1F2168 4TB     | 6        | 0.41%   |
| Seagate Expansion 500GB            | 6        | 0.41%   |
| Samsung HD103UJ 1TB                | 6        | 0.41%   |
| Phison NVMe SSD Drive 1TB          | 6        | 0.41%   |
| Hitachi HUA723020ALA641 2TB        | 6        | 0.41%   |
| WDC WDBNCE5000PNC 500GB SSD        | 5        | 0.35%   |
| Toshiba DT01ACA200 2TB             | 5        | 0.35%   |
| Seagate ST9500420AS 500GB          | 5        | 0.35%   |
| Seagate ST31000524AS 1TB           | 5        | 0.35%   |
| Seagate ST2000DM001-9YN164 2TB     | 5        | 0.35%   |
| Seagate ST2000DM001-1ER164 2TB     | 5        | 0.35%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 5        | 0.35%   |
| Samsung SSD 870 QVO 1TB            | 5        | 0.35%   |
| Samsung SSD 860 EVO 250GB          | 5        | 0.35%   |
| Samsung NVMe SSD Drive 256GB       | 5        | 0.35%   |
| Samsung NVMe SSD Drive 250GB       | 5        | 0.35%   |
| Phison NVMe SSD Drive 512GB        | 5        | 0.35%   |
| Kingston NVMe SSD Drive 500GB      | 5        | 0.35%   |
| Crucial CT480BX500SSD1 480GB       | 5        | 0.35%   |
| Crucial CT2000MX500SSD1 2TB        | 5        | 0.35%   |
| WDC WD5000AAKX-08U6AA0 500GB       | 4        | 0.28%   |
| WDC WD1600AAJS-75M0A0 160GB        | 4        | 0.28%   |
| WDC WD10EZEX-00BN5A0 1TB           | 4        | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 254      | 380    | 40.9%   |
| WDC                 | 188      | 262    | 30.27%  |
| Hitachi             | 59       | 75     | 9.5%    |
| Toshiba             | 54       | 66     | 8.7%    |
| Samsung Electronics | 34       | 44     | 5.48%   |
| HGST                | 10       | 15     | 1.61%   |
| Unknown             | 6        | 8      | 0.97%   |
| Maxtor              | 6        | 7      | 0.97%   |
| SABRENT             | 4        | 4      | 0.64%   |
| Hewlett-Packard     | 3        | 6      | 0.48%   |
| Apple               | 2        | 2      | 0.32%   |
| USB3.0              | 1        | 2      | 0.16%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 97       | 140    | 21.51%  |
| Kingston            | 69       | 89     | 15.3%   |
| Crucial             | 48       | 59     | 10.64%  |
| SanDisk             | 47       | 56     | 10.42%  |
| WDC                 | 20       | 24     | 4.43%   |
| A-DATA Technology   | 18       | 22     | 3.99%   |
| China               | 15       | 17     | 3.33%   |
| PNY                 | 8        | 10     | 1.77%   |
| OCZ                 | 8        | 9      | 1.77%   |
| Intel               | 8        | 10     | 1.77%   |
| Micron Technology   | 6        | 6      | 1.33%   |
| Lexar               | 6        | 6      | 1.33%   |
| Intenso             | 6        | 7      | 1.33%   |
| Gigabyte Technology | 6        | 7      | 1.33%   |
| Toshiba             | 5        | 5      | 1.11%   |
| SPCC                | 5        | 6      | 1.11%   |
| SK hynix            | 5        | 5      | 1.11%   |
| Hewlett-Packard     | 5        | 6      | 1.11%   |
| Super Talent        | 4        | 5      | 0.89%   |
| Netac               | 4        | 5      | 0.89%   |
| KingSpec            | 4        | 5      | 0.89%   |
| GOODRAM             | 4        | 4      | 0.89%   |
| Team                | 3        | 5      | 0.67%   |
| Seagate             | 3        | 4      | 0.67%   |
| Patriot             | 3        | 5      | 0.67%   |
| Leven               | 3        | 4      | 0.67%   |
| Apacer              | 3        | 3      | 0.67%   |
| Transcend           | 2        | 2      | 0.44%   |
| Plextor             | 2        | 3      | 0.44%   |
| Pioneer             | 2        | 2      | 0.44%   |
| KIOXIA-EXCERIA      | 2        | 5      | 0.44%   |
| JMicron Technology  | 2        | 2      | 0.44%   |
| Dogfish             | 2        | 3      | 0.44%   |
| Corsair             | 2        | 2      | 0.44%   |
| Verbatim            | 1        | 1      | 0.22%   |
| TwinMOS             | 1        | 1      | 0.22%   |
| Teclast             | 1        | 1      | 0.22%   |
| T-CREATE            | 1        | 1      | 0.22%   |
| SuperSSpeed         | 1        | 2      | 0.22%   |
| Smartbuy            | 1        | 1      | 0.22%   |
| Phison              | 1        | 1      | 0.22%   |
| OWC                 | 1        | 1      | 0.22%   |
| ORTIAL              | 1        | 1      | 0.22%   |
| OCZ-VERTEX          | 1        | 1      | 0.22%   |
| MyDigitalSSD        | 1        | 1      | 0.22%   |
| Mushkin             | 1        | 1      | 0.22%   |
| LITEON              | 1        | 1      | 0.22%   |
| LDLC                | 1        | 1      | 0.22%   |
| KingDian            | 1        | 1      | 0.22%   |
| INNOVATION IT       | 1        | 1      | 0.22%   |
| GALAX               | 1        | 1      | 0.22%   |
| FORESEE             | 1        | 1      | 0.22%   |
| Drevo               | 1        | 1      | 0.22%   |
| Apple               | 1        | 1      | 0.22%   |
| AFOX                | 1        | 2      | 0.22%   |
| addlink             | 1        | 1      | 0.22%   |
| Acer                | 1        | 2      | 0.22%   |
| Unknown             | 1        | 1      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 468      | 871    | 45.26%  |
| SSD     | 377      | 570    | 36.46%  |
| NVMe    | 153      | 213    | 14.8%   |
| Unknown | 33       | 49     | 3.19%   |
| MMC     | 3        | 4      | 0.29%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 644      | 1407   | 75.32%  |
| NVMe | 153      | 213    | 17.89%  |
| SAS  | 55       | 83     | 6.43%   |
| MMC  | 3        | 4      | 0.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 499      | 820    | 54.54%  |
| 0.51-1.0   | 243      | 366    | 26.56%  |
| 1.01-2.0   | 96       | 139    | 10.49%  |
| 3.01-4.0   | 36       | 53     | 3.93%   |
| 4.01-10.0  | 23       | 35     | 2.51%   |
| 2.01-3.0   | 17       | 27     | 1.86%   |
| 10.01-20.0 | 1        | 1      | 0.11%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 207      | 29.03%  |
| 251-500        | 158      | 22.16%  |
| 501-1000       | 113      | 15.85%  |
| More than 3000 | 59       | 8.27%   |
| 1001-2000      | 59       | 8.27%   |
| 51-100         | 49       | 6.87%   |
| 2001-3000      | 27       | 3.79%   |
| 21-50          | 16       | 2.24%   |
| 1-20           | 15       | 2.1%    |
| Unknown        | 10       | 1.4%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 260      | 34.9%   |
| 21-50          | 194      | 26.04%  |
| 51-100         | 85       | 11.41%  |
| 101-250        | 52       | 6.98%   |
| 251-500        | 45       | 6.04%   |
| 501-1000       | 34       | 4.56%   |
| More than 3000 | 32       | 4.3%    |
| 1001-2000      | 25       | 3.36%   |
| Unknown        | 10       | 1.34%   |
| 2001-3000      | 8        | 1.07%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Desktops | Drives | Percent |
|--------------------------------------|----------|--------|---------|
| WDC WD3200AAKS-22B3A0 320GB          | 1        | 1      | 4.76%   |
| WDC WD30EFRX-68EUZN0 3TB             | 1        | 1      | 4.76%   |
| WDC WD10EZEX-21M2NA0 1TB             | 1        | 2      | 4.76%   |
| WDC WD10EURX-63FH1Y0 1TB             | 1        | 1      | 4.76%   |
| Toshiba MK8046GSX 80GB               | 1        | 1      | 4.76%   |
| Toshiba MK3265GSX 320GB              | 1        | 1      | 4.76%   |
| Toshiba MG03ACA200 2TB               | 1        | 1      | 4.76%   |
| Silicon Motion Inland NVMe SSD 256GB | 1        | 1      | 4.76%   |
| Seagate ST9500420AS 500GB            | 1        | 1      | 4.76%   |
| Seagate ST500DM002-1BD142 500GB      | 1        | 1      | 4.76%   |
| Seagate ST4000DM004-2CV104 4TB       | 1        | 1      | 4.76%   |
| Seagate ST3500514NS 500GB            | 1        | 1      | 4.76%   |
| Seagate ST3500413AS 500GB            | 1        | 1      | 4.76%   |
| Seagate ST3320620AS 320GB            | 1        | 1      | 4.76%   |
| Seagate ST320LT012-1DG14C 320GB      | 1        | 1      | 4.76%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 1        | 1      | 4.76%   |
| Seagate ST2000DM001-9YN164 2TB       | 1        | 1      | 4.76%   |
| Seagate ST2000DL003-9VT166 2TB       | 1        | 1      | 4.76%   |
| OCZ VERTEX3 120GB SSD                | 1        | 1      | 4.76%   |
| Kingston SNS4151S316GD 16GB SSD      | 1        | 1      | 4.76%   |
| A-DATA Technology SX8200PNP 256GB    | 1        | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| Seagate           | 9        | 10     | 45%     |
| WDC               | 4        | 5      | 20%     |
| Toshiba           | 3        | 3      | 15%     |
| Silicon Motion    | 1        | 1      | 5%      |
| OCZ               | 1        | 1      | 5%      |
| Kingston          | 1        | 1      | 5%      |
| A-DATA Technology | 1        | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 9        | 10     | 56.25%  |
| WDC     | 4        | 5      | 25%     |
| Toshiba | 3        | 3      | 18.75%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 15       | 18     | 78.95%  |
| NVMe | 2        | 2      | 10.53%  |
| SSD  | 2        | 2      | 10.53%  |

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
| Detected | 637      | 1552   | 89.22%  |
| Works    | 58       | 133    | 8.12%   |
| Malfunc  | 19       | 22     | 2.66%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 461      | 49.73%  |
| AMD                          | 214      | 23.09%  |
| Samsung Electronics          | 51       | 5.5%    |
| ASMedia Technology           | 28       | 3.02%   |
| SanDisk                      | 24       | 2.59%   |
| Phison Electronics           | 20       | 2.16%   |
| Kingston Technology Company  | 19       | 2.05%   |
| JMicron Technology           | 19       | 2.05%   |
| Silicon Motion               | 17       | 1.83%   |
| Nvidia                       | 15       | 1.62%   |
| Marvell Technology Group     | 12       | 1.29%   |
| Silicon Image                | 7        | 0.76%   |
| ADATA Technology             | 7        | 0.76%   |
| Micron/Crucial Technology    | 6        | 0.65%   |
| VIA Technologies             | 5        | 0.54%   |
| Realtek Semiconductor        | 5        | 0.54%   |
| SK hynix                     | 4        | 0.43%   |
| Toshiba America Info Systems | 3        | 0.32%   |
| Seagate Technology           | 3        | 0.32%   |
| MAXIO Technology (Hangzhou)  | 2        | 0.22%   |
| KIOXIA                       | 2        | 0.22%   |
| Broadcom / LSI               | 2        | 0.22%   |
| Micron Technology            | 1        | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 115      | 9.75%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 67       | 5.68%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 48       | 4.07%   |
| AMD 400 Series Chipset SATA Controller                                                  | 47       | 3.99%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 40       | 3.39%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 39       | 3.31%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 38       | 3.22%   |
| Intel SATA Controller [RAID mode]                                                       | 34       | 2.88%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 32       | 2.71%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 32       | 2.71%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 28       | 2.37%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 26       | 2.21%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 26       | 2.21%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 25       | 2.12%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 22       | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 22       | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 21       | 1.78%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 21       | 1.78%   |
| AMD 500 Series Chipset SATA Controller                                                  | 20       | 1.7%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 16       | 1.36%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 14       | 1.19%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 14       | 1.19%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 13       | 1.1%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 13       | 1.1%    |
| Phison E12 NVMe Controller                                                              | 11       | 0.93%   |
| Kingston Company A2000 NVMe SSD                                                         | 11       | 0.93%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 9        | 0.76%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 9        | 0.76%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 9        | 0.76%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 9        | 0.76%   |
| AMD FCH SATA Controller D                                                               | 9        | 0.76%   |
| Nvidia MCP61 SATA Controller                                                            | 8        | 0.68%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 8        | 0.68%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 7        | 0.59%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 7        | 0.59%   |
| Nvidia MCP61 IDE                                                                        | 7        | 0.59%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 7        | 0.59%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 7        | 0.59%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 7        | 0.59%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 7        | 0.59%   |
| AMD X370 Series Chipset SATA Controller                                                 | 7        | 0.59%   |
| Samsung NVMe SSD Controller 980                                                         | 6        | 0.51%   |
| JMicron JMB368 IDE controller                                                           | 6        | 0.51%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 6        | 0.51%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 6        | 0.51%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 6        | 0.51%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 6        | 0.51%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 6        | 0.51%   |
| AMD FCH IDE Controller                                                                  | 6        | 0.51%   |
| SanDisk Non-Volatile memory controller                                                  | 5        | 0.42%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 5        | 0.42%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 5        | 0.42%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 5        | 0.42%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 5        | 0.42%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 5        | 0.42%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 4        | 0.34%   |
| Marvell Group 88SE9120 SATA 6Gb/s Controller                                            | 4        | 0.34%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 4        | 0.34%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 4        | 0.34%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 4        | 0.34%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 541      | 57.43%  |
| IDE  | 187      | 19.85%  |
| NVMe | 152      | 16.14%  |
| RAID | 57       | 6.05%   |
| SAS  | 3        | 0.32%   |
| SCSI | 2        | 0.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 465      | 67.2%   |
| AMD    | 227      | 32.8%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-2400 CPU @ 3.10GHz            | 17       | 2.45%   |
| AMD Ryzen 5 3600 6-Core Processor           | 16       | 2.31%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 13       | 1.88%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 11       | 1.59%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 9        | 1.3%    |
| Intel Core i3-3220 CPU @ 3.30GHz            | 9        | 1.3%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 9        | 1.3%    |
| Intel Core i7-3770 CPU @ 3.40GHz            | 8        | 1.15%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 8        | 1.15%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 8        | 1.15%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 8        | 1.15%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 7        | 1.01%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 7        | 1.01%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 7        | 1.01%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 6        | 0.87%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 6        | 0.87%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 6        | 0.87%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 6        | 0.87%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 6        | 0.87%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 6        | 0.87%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 6        | 0.87%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 5        | 0.72%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 5        | 0.72%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 5        | 0.72%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz      | 5        | 0.72%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 5        | 0.72%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 5        | 0.72%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 5        | 0.72%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 5        | 0.72%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 5        | 0.72%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 5        | 0.72%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 5        | 0.72%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 5        | 0.72%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 5        | 0.72%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 5        | 0.72%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 5        | 0.72%   |
| AMD FX-8350 Eight-Core Processor            | 5        | 0.72%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 4        | 0.58%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 4        | 0.58%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 4        | 0.58%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 4        | 0.58%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 4        | 0.58%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 4        | 0.58%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 4        | 0.58%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 4        | 0.58%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 4        | 0.58%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 4        | 0.58%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 4        | 0.58%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 4        | 0.58%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 4        | 0.58%   |
| AMD FX-8320E Eight-Core Processor           | 4        | 0.58%   |
| AMD FX-8320 Eight-Core Processor            | 4        | 0.58%   |
| AMD FX-6300 Six-Core Processor              | 4        | 0.58%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 3        | 0.43%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 3        | 0.43%   |
| Intel Core i7 CPU 870 @ 2.93GHz             | 3        | 0.43%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 3        | 0.43%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 3        | 0.43%   |
| Intel Core i5-6600 CPU @ 3.30GHz            | 3        | 0.43%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 3        | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 142      | 20.49%  |
| Intel Core i7           | 78       | 11.26%  |
| Intel Core i3           | 70       | 10.1%   |
| AMD Ryzen 5             | 57       | 8.23%   |
| Intel Xeon              | 35       | 5.05%   |
| AMD FX                  | 31       | 4.47%   |
| AMD Ryzen 7             | 30       | 4.33%   |
| Intel Core 2 Quad       | 21       | 3.03%   |
| Intel Core 2 Duo        | 19       | 2.74%   |
| Intel Celeron           | 18       | 2.6%    |
| Other                   | 17       | 2.45%   |
| Intel Pentium Dual-Core | 17       | 2.45%   |
| AMD Ryzen 9             | 17       | 2.45%   |
| Intel Pentium           | 14       | 2.02%   |
| Intel Pentium Dual      | 13       | 1.88%   |
| AMD Ryzen 3             | 11       | 1.59%   |
| AMD Phenom II X4        | 8        | 1.15%   |
| AMD Athlon II X2        | 8        | 1.15%   |
| AMD A10                 | 8        | 1.15%   |
| AMD Athlon II X4        | 7        | 1.01%   |
| AMD A6                  | 7        | 1.01%   |
| Intel Core i9           | 6        | 0.87%   |
| AMD A8                  | 6        | 0.87%   |
| AMD Phenom II X6        | 5        | 0.72%   |
| AMD Athlon 64 X2        | 5        | 0.72%   |
| Intel Pentium 4         | 4        | 0.58%   |
| Intel Pentium Gold      | 3        | 0.43%   |
| Intel Core 2            | 3        | 0.43%   |
| Intel Atom              | 3        | 0.43%   |
| AMD E1                  | 3        | 0.43%   |
| AMD Athlon II X3        | 3        | 0.43%   |
| AMD Athlon              | 3        | 0.43%   |
| Intel Pentium D         | 2        | 0.29%   |
| AMD PRO A10             | 2        | 0.29%   |
| AMD Phenom              | 2        | 0.29%   |
| AMD GX                  | 2        | 0.29%   |
| AMD Athlon X4           | 2        | 0.29%   |
| AMD Athlon 64           | 2        | 0.29%   |
| Intel Core m3           | 1        | 0.14%   |
| Intel Celeron D         | 1        | 0.14%   |
| AMD Sempron             | 1        | 0.14%   |
| AMD Ryzen Threadripper  | 1        | 0.14%   |
| AMD Ryzen 5 PRO         | 1        | 0.14%   |
| AMD Ryzen 3 PRO         | 1        | 0.14%   |
| AMD Opteron             | 1        | 0.14%   |
| AMD Athlon Dual Core    | 1        | 0.14%   |
| AMD A4                  | 1        | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 296      | 42.71%  |
| 2      | 195      | 28.14%  |
| 6      | 98       | 14.14%  |
| 8      | 51       | 7.36%   |
| 12     | 14       | 2.02%   |
| 1      | 14       | 2.02%   |
| 3      | 13       | 1.88%   |
| 16     | 7        | 1.01%   |
| 10     | 5        | 0.72%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 688      | 99.42%  |
| 2      | 4        | 0.58%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 356      | 51.45%  |
| 1      | 336      | 48.55%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 692      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 78       | 11.17%  |
| 0x306a9    | 63       | 9.03%   |
| 0x206a7    | 53       | 7.59%   |
| Unknown    | 50       | 7.16%   |
| 0x1067a    | 47       | 6.73%   |
| 0x08701021 | 31       | 4.44%   |
| 0x506e3    | 28       | 4.01%   |
| 0x06000852 | 23       | 3.3%    |
| 0x906ea    | 16       | 2.29%   |
| 0x0a201016 | 16       | 2.29%   |
| 0x906e9    | 14       | 2.01%   |
| 0x0800820d | 14       | 2.01%   |
| 0xa0653    | 13       | 1.86%   |
| 0x6fd      | 13       | 1.86%   |
| 0x06001119 | 12       | 1.72%   |
| 0x6fb      | 10       | 1.43%   |
| 0xa0655    | 9        | 1.29%   |
| 0x010000c8 | 9        | 1.29%   |
| 0x906ed    | 8        | 1.15%   |
| 0x906eb    | 8        | 1.15%   |
| 0x0600063e | 8        | 1.15%   |
| 0xa0671    | 7        | 1%      |
| 0x08701013 | 7        | 1%      |
| 0x08108109 | 7        | 1%      |
| 0x010000dc | 7        | 1%      |
| 0x010000db | 7        | 1%      |
| 0x90672    | 6        | 0.86%   |
| 0x206d7    | 6        | 0.86%   |
| 0x106a5    | 6        | 0.86%   |
| 0x08101016 | 6        | 0.86%   |
| 0x08001137 | 5        | 0.72%   |
| 0x0700010f | 5        | 0.72%   |
| 0x06003106 | 5        | 0.72%   |
| 0x306e4    | 4        | 0.57%   |
| 0x30678    | 4        | 0.57%   |
| 0x20655    | 4        | 0.57%   |
| 0x106e5    | 4        | 0.57%   |
| 0x10676    | 4        | 0.57%   |
| 0x0a201009 | 4        | 0.57%   |
| 0x08001138 | 4        | 0.57%   |
| 0x406c4    | 3        | 0.43%   |
| 0x40651    | 3        | 0.43%   |
| 0x20652    | 3        | 0.43%   |
| 0x0a50000c | 3        | 0.43%   |
| 0x0a50000b | 3        | 0.43%   |
| 0x06006705 | 3        | 0.43%   |
| 0x010000c7 | 3        | 0.43%   |
| 0xf47      | 2        | 0.29%   |
| 0xf43      | 2        | 0.29%   |
| 0x906ec    | 2        | 0.29%   |
| 0x6f6      | 2        | 0.29%   |
| 0x306f2    | 2        | 0.29%   |
| 0x206c2    | 2        | 0.29%   |
| 0x106a4    | 2        | 0.29%   |
| 0x10677    | 2        | 0.29%   |
| 0x0a201205 | 2        | 0.29%   |
| 0x08600106 | 2        | 0.29%   |
| 0x0810100b | 2        | 0.29%   |
| 0x07030106 | 2        | 0.29%   |
| 0x01000083 | 2        | 0.29%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 90       | 13.01%  |
| IvyBridge        | 67       | 9.68%   |
| SandyBridge      | 62       | 8.96%   |
| Penryn           | 54       | 7.8%    |
| KabyLake         | 52       | 7.51%   |
| Zen 2            | 43       | 6.21%   |
| Piledriver       | 36       | 5.2%    |
| Zen 3            | 33       | 4.77%   |
| K10              | 33       | 4.77%   |
| Skylake          | 29       | 4.19%   |
| Core             | 28       | 4.05%   |
| Zen+             | 23       | 3.32%   |
| CometLake        | 23       | 3.32%   |
| Zen              | 20       | 2.89%   |
| Nehalem          | 14       | 2.02%   |
| Westmere         | 9        | 1.3%    |
| K8 Hammer        | 9        | 1.3%    |
| Silvermont       | 8        | 1.16%   |
| Bulldozer        | 8        | 1.16%   |
| NetBurst         | 7        | 1.01%   |
| Icelake          | 7        | 1.01%   |
| Jaguar           | 6        | 0.87%   |
| Excavator        | 6        | 0.87%   |
| Alderlake Hybrid | 6        | 0.87%   |
| Steamroller      | 5        | 0.72%   |
| Puma             | 4        | 0.58%   |
| Broadwell        | 2        | 0.29%   |
| Bonnell          | 2        | 0.29%   |
| Unknown          | 2        | 0.29%   |
| TigerLake        | 1        | 0.14%   |
| K10 Llano        | 1        | 0.14%   |
| Goldmont plus    | 1        | 0.14%   |
| Goldmont         | 1        | 0.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Nvidia           | 293      | 39.7%   |
| Intel            | 235      | 31.84%  |
| AMD              | 208      | 28.18%  |
| VIA Technologies | 2        | 0.27%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 40       | 5.36%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 33       | 4.42%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 24       | 3.22%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 24       | 3.22%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 19       | 2.55%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 15       | 2.01%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 15       | 2.01%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 15       | 2.01%   |
| Intel HD Graphics 530                                                                    | 14       | 1.88%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 13       | 1.74%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 11       | 1.47%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 11       | 1.47%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 11       | 1.47%   |
| Intel HD Graphics 630                                                                    | 10       | 1.34%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 10       | 1.34%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 10       | 1.34%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 9        | 1.21%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 9        | 1.21%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 8        | 1.07%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 7        | 0.94%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 7        | 0.94%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 7        | 0.94%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 7        | 0.94%   |
| AMD RS780L [Radeon 3000]                                                                 | 7        | 0.94%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 7        | 0.94%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 6        | 0.8%    |
| Nvidia GT218 [GeForce 210]                                                               | 6        | 0.8%    |
| Nvidia GF108 [GeForce GT 730]                                                            | 6        | 0.8%    |
| Intel Core Processor Integrated Graphics Controller                                      | 6        | 0.8%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 6        | 0.8%    |
| AMD RS880 [Radeon HD 4200]                                                               | 6        | 0.8%    |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 6        | 0.8%    |
| AMD Cezanne                                                                              | 6        | 0.8%    |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 6        | 0.8%    |
| Nvidia GK106 [GeForce GTX 660]                                                           | 5        | 0.67%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                                        | 5        | 0.67%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 5        | 0.67%   |
| Intel AlderLake-S GT1                                                                    | 5        | 0.67%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 5        | 0.67%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 4        | 0.54%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 4        | 0.54%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 4        | 0.54%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 4        | 0.54%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 4        | 0.54%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 4        | 0.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4        | 0.54%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 4        | 0.54%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4        | 0.54%   |
| AMD Park [Mobility Radeon HD 5430]                                                       | 4        | 0.54%   |
| AMD Juniper XT [Radeon HD 5770]                                                          | 4        | 0.54%   |
| AMD Bonaire XTX [Radeon R7 260X/360]                                                     | 4        | 0.54%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 4        | 0.54%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 3        | 0.4%    |
| Nvidia TU106 [GeForce RTX 2070]                                                          | 3        | 0.4%    |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 3        | 0.4%    |
| Nvidia TU104 [GeForce RTX 2060]                                                          | 3        | 0.4%    |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 3        | 0.4%    |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                       | 3        | 0.4%    |
| Nvidia GM204 [GeForce GTX 980]                                                           | 3        | 0.4%    |
| Nvidia GK107GL [Quadro K600]                                                             | 3        | 0.4%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 278      | 39.89%  |
| 1 x Intel      | 202      | 28.98%  |
| 1 x AMD        | 194      | 27.83%  |
| Intel + Nvidia | 7        | 1%      |
| Intel + AMD    | 6        | 0.86%   |
| 2 x AMD        | 4        | 0.57%   |
| AMD + Nvidia   | 3        | 0.43%   |
| 1 x VIA        | 2        | 0.29%   |
| 2 x Nvidia     | 1        | 0.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 461      | 66.24%  |
| Proprietary | 195      | 28.02%  |
| Unknown     | 40       | 5.75%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 285      | 40.6%   |
| 1.01-2.0   | 96       | 13.68%  |
| 0.51-1.0   | 95       | 13.53%  |
| 0.01-0.5   | 65       | 9.26%   |
| 3.01-4.0   | 63       | 8.97%   |
| 7.01-8.0   | 49       | 6.98%   |
| 5.01-6.0   | 20       | 2.85%   |
| 8.01-16.0  | 18       | 2.56%   |
| 2.01-3.0   | 7        | 1%      |
| 16.01-24.0 | 4        | 0.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 112      | 16.26%  |
| Dell                 | 69       | 10.01%  |
| Goldstar             | 63       | 9.14%   |
| Hewlett-Packard      | 53       | 7.69%   |
| Acer                 | 42       | 6.1%    |
| Philips              | 40       | 5.81%   |
| AOC                  | 40       | 5.81%   |
| BenQ                 | 27       | 3.92%   |
| Ancor Communications | 26       | 3.77%   |
| LG Electronics       | 20       | 2.9%    |
| Unknown              | 14       | 2.03%   |
| ViewSonic            | 13       | 1.89%   |
| Sony                 | 10       | 1.45%   |
| Iiyama               | 10       | 1.45%   |
| Unknown              | 9        | 1.31%   |
| Sceptre Tech         | 9        | 1.31%   |
| NEC Computers        | 9        | 1.31%   |
| Lenovo               | 9        | 1.31%   |
| HPN                  | 9        | 1.31%   |
| ASUSTek Computer     | 7        | 1.02%   |
| Vizio                | 5        | 0.73%   |
| Fujitsu Siemens      | 5        | 0.73%   |
| Panasonic            | 4        | 0.58%   |
| Microstep            | 4        | 0.58%   |
| Medion               | 4        | 0.58%   |
| AUS                  | 4        | 0.58%   |
| Vestel               | 3        | 0.44%   |
| Sharp                | 3        | 0.44%   |
| PKB                  | 3        | 0.44%   |
| Eizo                 | 3        | 0.44%   |
| Toshiba              | 2        | 0.29%   |
| OOO                  | 2        | 0.29%   |
| ONN                  | 2        | 0.29%   |
| OEM                  | 2        | 0.29%   |
| MSI                  | 2        | 0.29%   |
| Lenovo Group Limited | 2        | 0.29%   |
| HannStar             | 2        | 0.29%   |
| Gigabyte Technology  | 2        | 0.29%   |
| GDH                  | 2        | 0.29%   |
| Gateway              | 2        | 0.29%   |
| FUS                  | 2        | 0.29%   |
| ___                  | 1        | 0.15%   |
| ZZZ                  | 1        | 0.15%   |
| Xiaomi               | 1        | 0.15%   |
| Westinghouse         | 1        | 0.15%   |
| WAN                  | 1        | 0.15%   |
| VOR                  | 1        | 0.15%   |
| VIZ                  | 1        | 0.15%   |
| Viotek               | 1        | 0.15%   |
| Vestel Elektronik    | 1        | 0.15%   |
| Unknown (AAA)        | 1        | 0.15%   |
| TFG                  | 1        | 0.15%   |
| STD                  | 1        | 0.15%   |
| SKY                  | 1        | 0.15%   |
| Seiki                | 1        | 0.15%   |
| Sceptre              | 1        | 0.15%   |
| SANYO                | 1        | 0.15%   |
| PRI                  | 1        | 0.15%   |
| Pixio                | 1        | 0.15%   |
| Packard Bell         | 1        | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Unknown                                                                 | 14       | 1.94%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 5        | 0.69%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch       | 4        | 0.55%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                | 4        | 0.55%   |
| Vestel LCD Monitor 48UHD_LCD_TV 3840x2160                               | 3        | 0.42%   |
| Samsung Electronics U28D590 SAM0B81 3840x2160 608x345mm 27.5-inch       | 3        | 0.42%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 890x500mm 40.2-inch   | 3        | 0.42%   |
| Philips LCD Monitor FTV 1920x1080                                       | 3        | 0.42%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                     | 3        | 0.42%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch               | 3        | 0.42%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                        | 3        | 0.42%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch   | 3        | 0.42%   |
| Vizio VO42LFHDTV10A VIZ0043 1920x1080 930x520mm 41.9-inch               | 2        | 0.28%   |
| Sceptre Tech H32 SPT0CB8 1920x1080 575x323mm 26.0-inch                  | 2        | 0.28%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch       | 2        | 0.28%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch    | 2        | 0.28%   |
| Samsung Electronics SMB1930N SAM0632 1360x768 410x230mm 18.5-inch       | 2        | 0.28%   |
| Samsung Electronics S24B350 SAM08DA 1920x1080 531x299mm 24.0-inch       | 2        | 0.28%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                    | 2        | 0.28%   |
| Samsung Electronics LCD Monitor SyncMaster                              | 2        | 0.28%   |
| Samsung Electronics LCD Monitor SAM0F9F 3840x2160 1872x1053mm 84.6-inch | 2        | 0.28%   |
| Samsung Electronics LCD Monitor SAM0D4F 1920x1080 1210x680mm 54.6-inch  | 2        | 0.28%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch    | 2        | 0.28%   |
| Samsung Electronics LCD Monitor SAM07BC 1360x768 700x390mm 31.5-inch    | 2        | 0.28%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                 | 2        | 0.28%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                 | 2        | 0.28%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                 | 2        | 0.28%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                      | 2        | 0.28%   |
| OEM 32_LCD_TV OEM3700 1920x540                                          | 2        | 0.28%   |
| NEC Computers LCD1715 NEC6618 1280x1024 338x270mm 17.0-inch             | 2        | 0.28%   |
| LG Electronics LCD Monitor LG TV SSCR2 3840x2160                        | 2        | 0.28%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                         | 2        | 0.28%   |
| Hewlett-Packard W2072a HWP3000 1600x900 443x249mm 20.0-inch             | 2        | 0.28%   |
| Hewlett-Packard LCD Monitor w1907 3120x1050                             | 2        | 0.28%   |
| Hewlett-Packard LA2205 HWP2847 1680x1050 470x300mm 22.0-inch            | 2        | 0.28%   |
| Hewlett-Packard 24f HPN3546 1920x1080 527x296mm 23.8-inch               | 2        | 0.28%   |
| Goldstar M2280D GSM57B9 1920x1080 480x270mm 21.7-inch                   | 2        | 0.28%   |
| Goldstar IPS225 GSM587B 1920x1080 510x290mm 23.1-inch                   | 2        | 0.28%   |
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                    | 2        | 0.28%   |
| GDH PHILCO GDH0030 1920x540 708x398mm 32.0-inch                         | 2        | 0.28%   |
| Dell SE198WFP DELF003 1440x900 408x255mm 18.9-inch                      | 2        | 0.28%   |
| Dell P2719H DEL4185 1920x1080 598x336mm 27.0-inch                       | 2        | 0.28%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                       | 2        | 0.28%   |
| Dell P190S DEL405B 1280x1024 376x301mm 19.0-inch                        | 2        | 0.28%   |
| Dell LCD Monitor E228WFP                                                | 2        | 0.28%   |
| Dell E2213 DELD04E 1680x1050 473x296mm 22.0-inch                        | 2        | 0.28%   |
| Dell E207WFP DELD010 1680x1050 430x270mm 20.0-inch                      | 2        | 0.28%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                      | 2        | 0.28%   |
| BenQ EW3270U BNQ7950 3840x2160 698x393mm 31.5-inch                      | 2        | 0.28%   |
| AOC LCD Monitor Q3279WG5B 2560x1440                                     | 2        | 0.28%   |
| AOC 2260W AOC2260 1920x1080 477x268mm 21.5-inch                         | 2        | 0.28%   |
| Ancor Communications LCD Monitor VE247 3840x1080                        | 2        | 0.28%   |
| Acer X223W ACR000D 1680x1050 474x296mm 22.0-inch                        | 2        | 0.28%   |
| Acer QG271 ACR06FA 1920x1080 597x336mm 27.0-inch                        | 2        | 0.28%   |
| ___ LCDTV16 ___0101 1920x1080                                           | 1        | 0.14%   |
| ZZZ HDMI ZZZE435 1600x900 442x240mm 19.8-inch                           | 1        | 0.14%   |
| Xiaomi Mi TV XMD00E2 1920x1080 708x398mm 32.0-inch                      | 1        | 0.14%   |
| Westinghouse SK-26H735S WDE6030 1366x768 576x324mm 26.0-inch            | 1        | 0.14%   |
| WAN 27MQ95FSHDRU WAN2700 2560x1440 600x330mm 27.0-inch                  | 1        | 0.14%   |
| VOR LED19204 VOR1950 1366x768 410x220mm 18.3-inch                       | 1        | 0.14%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 292      | 43.26%  |
| 3840x2160 (4K)     | 58       | 8.59%   |
| 1680x1050 (WSXGA+) | 39       | 5.78%   |
| 1280x1024 (SXGA)   | 39       | 5.78%   |
| Unknown            | 36       | 5.33%   |
| 1600x900 (HD+)     | 34       | 5.04%   |
| 1366x768 (WXGA)    | 28       | 4.15%   |
| 2560x1440 (QHD)    | 24       | 3.56%   |
| 1440x900 (WXGA+)   | 20       | 2.96%   |
| 1360x768           | 17       | 2.52%   |
| 3840x1080          | 15       | 2.22%   |
| 1920x1200 (WUXGA)  | 15       | 2.22%   |
| 3440x1440          | 12       | 1.78%   |
| 2560x1080          | 7        | 1.04%   |
| 1920x540           | 4        | 0.59%   |
| 1024x768 (XGA)     | 4        | 0.59%   |
| 4480x1440          | 3        | 0.44%   |
| 3840x1600          | 3        | 0.44%   |
| 5760x2160          | 2        | 0.3%    |
| 3360x1080          | 2        | 0.3%    |
| 3200x1200          | 2        | 0.3%    |
| 3120x1050          | 2        | 0.3%    |
| 2560x1600          | 2        | 0.3%    |
| 1600x1200          | 2        | 0.3%    |
| 6400x1440          | 1        | 0.15%   |
| 5440x1080          | 1        | 0.15%   |
| 4160x1440          | 1        | 0.15%   |
| 3780x2160          | 1        | 0.15%   |
| 3600x1080          | 1        | 0.15%   |
| 3360x1050          | 1        | 0.15%   |
| 3040x1050          | 1        | 0.15%   |
| 2944x1080          | 1        | 0.15%   |
| 2720x1024          | 1        | 0.15%   |
| 2464x900           | 1        | 0.15%   |
| 1850x1030          | 1        | 0.15%   |
| 1834x1031          | 1        | 0.15%   |
| 1280x720 (HD)      | 1        | 0.15%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 149      | 22.14%  |
| 24      | 69       | 10.25%  |
| 27      | 68       | 10.1%   |
| 23      | 57       | 8.47%   |
| 21      | 57       | 8.47%   |
| 19      | 42       | 6.24%   |
| 31      | 35       | 5.2%    |
| 20      | 31       | 4.61%   |
| 22      | 27       | 4.01%   |
| 18      | 27       | 4.01%   |
| 17      | 20       | 2.97%   |
| 34      | 12       | 1.78%   |
| 84      | 10       | 1.49%   |
| 32      | 8        | 1.19%   |
| 54      | 7        | 1.04%   |
| 40      | 7        | 1.04%   |
| 26      | 6        | 0.89%   |
| 15      | 6        | 0.89%   |
| 72      | 5        | 0.74%   |
| 25      | 5        | 0.74%   |
| 52      | 3        | 0.45%   |
| 36      | 3        | 0.45%   |
| 65      | 2        | 0.3%    |
| 48      | 2        | 0.3%    |
| 41      | 2        | 0.3%    |
| 37      | 2        | 0.3%    |
| 35      | 2        | 0.3%    |
| 33      | 2        | 0.3%    |
| 28      | 2        | 0.3%    |
| 75      | 1        | 0.15%   |
| 74      | 1        | 0.15%   |
| 43      | 1        | 0.15%   |
| 42      | 1        | 0.15%   |
| 29      | 1        | 0.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 179      | 27.54%  |
| 401-500     | 161      | 24.77%  |
| Unknown     | 149      | 22.92%  |
| 601-700     | 46       | 7.08%   |
| 701-800     | 25       | 3.85%   |
| 301-350     | 24       | 3.69%   |
| 351-400     | 20       | 3.08%   |
| 1501-2000   | 17       | 2.62%   |
| 1001-1500   | 14       | 2.15%   |
| 801-900     | 11       | 1.69%   |
| 901-1000    | 4        | 0.62%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 353      | 56.21%  |
| Unknown | 143      | 22.77%  |
| 16/10   | 70       | 11.15%  |
| 5/4     | 34       | 5.41%   |
| 21/9    | 17       | 2.71%   |
| 4/3     | 7        | 1.11%   |
| 6/5     | 2        | 0.32%   |
| 32/9    | 1        | 0.16%   |
| 3/2     | 1        | 0.16%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 169      | 25.41%  |
| Unknown        | 149      | 22.41%  |
| 151-200        | 94       | 14.14%  |
| 301-350        | 69       | 10.38%  |
| 351-500        | 62       | 9.32%   |
| 141-150        | 40       | 6.02%   |
| More than 1000 | 30       | 4.51%   |
| 251-300        | 28       | 4.21%   |
| 501-1000       | 16       | 2.41%   |
| 101-110        | 6        | 0.9%    |
| 131-140        | 1        | 0.15%   |
| 121-130        | 1        | 0.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 342      | 54.11%  |
| Unknown | 149      | 23.58%  |
| 101-120 | 83       | 13.13%  |
| 1-50    | 30       | 4.75%   |
| 121-160 | 21       | 3.32%   |
| 161-240 | 7        | 1.11%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 557      | 80.03%  |
| 2     | 91       | 13.07%  |
| 0     | 40       | 5.75%   |
| 3     | 8        | 1.15%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 433      | 42.45%  |
| Intel                                 | 273      | 26.76%  |
| Qualcomm Atheros                      | 69       | 6.76%   |
| Broadcom                              | 37       | 3.63%   |
| Ralink Technology                     | 33       | 3.24%   |
| TP-Link                               | 27       | 2.65%   |
| Ralink                                | 20       | 1.96%   |
| Nvidia                                | 14       | 1.37%   |
| NetGear                               | 10       | 0.98%   |
| Samsung Electronics                   | 9        | 0.88%   |
| MediaTek                              | 8        | 0.78%   |
| Microsoft                             | 7        | 0.69%   |
| Qualcomm Atheros Communications       | 6        | 0.59%   |
| D-Link                                | 6        | 0.59%   |
| Marvell Technology Group              | 5        | 0.49%   |
| Huawei Technologies                   | 5        | 0.49%   |
| D-Link System                         | 5        | 0.49%   |
| Xiaomi                                | 4        | 0.39%   |
| Motorola PCS                          | 4        | 0.39%   |
| Edimax Technology                     | 4        | 0.39%   |
| Broadcom Limited                      | 4        | 0.39%   |
| ASIX Electronics                      | 4        | 0.39%   |
| DisplayLink                           | 3        | 0.29%   |
| ASUSTek Computer                      | 3        | 0.29%   |
| Gemtek                                | 2        | 0.2%    |
| Aquantia                              | 2        | 0.2%    |
| ZyDAS                                 | 1        | 0.1%    |
| VIA Technologies                      | 1        | 0.1%    |
| TRENDnet                              | 1        | 0.1%    |
| T & A Mobile Phones                   | 1        | 0.1%    |
| Sundance Technology Inc / IC Plus     | 1        | 0.1%    |
| Research In Motion                    | 1        | 0.1%    |
| QinHeng Electronics                   | 1        | 0.1%    |
| Panasonic (Matsushita)                | 1        | 0.1%    |
| Padix (Rockfire)                      | 1        | 0.1%    |
| OPPO Electronics                      | 1        | 0.1%    |
| Motorola                              | 1        | 0.1%    |
| Linksys                               | 1        | 0.1%    |
| Lenovo                                | 1        | 0.1%    |
| JMicron Technology                    | 1        | 0.1%    |
| InterBiometrics                       | 1        | 0.1%    |
| HMD Global                            | 1        | 0.1%    |
| Google                                | 1        | 0.1%    |
| Exar                                  | 1        | 0.1%    |
| Belkin Components                     | 1        | 0.1%    |
| AVM                                   | 1        | 0.1%    |
| Arduino SA                            | 1        | 0.1%    |
| ADMtek                                | 1        | 0.1%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 331      | 28.56%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 48       | 4.14%   |
| Realtek RTL8125 2.5GbE Controller                                 | 33       | 2.85%   |
| Intel I211 Gigabit Network Connection                             | 33       | 2.85%   |
| Intel Wi-Fi 6 AX200                                               | 30       | 2.59%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 25       | 2.16%   |
| Intel Ethernet Connection (2) I219-V                              | 23       | 1.98%   |
| Intel Ethernet Connection I217-LM                                 | 20       | 1.73%   |
| Realtek 802.11ac NIC                                              | 18       | 1.55%   |
| Ralink MT7601U Wireless Adapter                                   | 15       | 1.29%   |
| Intel Ethernet Controller I225-V                                  | 15       | 1.29%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 14       | 1.21%   |
| Intel Ethernet Connection I217-V                                  | 12       | 1.04%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 11       | 0.95%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 10       | 0.86%   |
| Intel Wireless 7265                                               | 10       | 0.86%   |
| Intel Ethernet Connection (7) I219-V                              | 10       | 0.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 10       | 0.86%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 9        | 0.78%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 9        | 0.78%   |
| Intel Wireless-AC 9260                                            | 9        | 0.78%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 9        | 0.78%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 8        | 0.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 8        | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 8        | 0.69%   |
| Nvidia MCP61 Ethernet                                             | 8        | 0.69%   |
| Intel 82579V Gigabit Network Connection                           | 8        | 0.69%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 7        | 0.6%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 7        | 0.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7        | 0.6%    |
| Intel Ethernet Connection (2) I218-V                              | 7        | 0.6%    |
| Ralink RT5370 Wireless Adapter                                    | 6        | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6        | 0.52%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 6        | 0.52%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 5        | 0.43%   |
| TP-Link TL-WN722N v2                                              | 5        | 0.43%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 5        | 0.43%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 5        | 0.43%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5        | 0.43%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5        | 0.43%   |
| Qualcomm Atheros AR9271 802.11n                                   | 5        | 0.43%   |
| NetGear A6210                                                     | 5        | 0.43%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5        | 0.43%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 5        | 0.43%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 5        | 0.43%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 5        | 0.43%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 4        | 0.35%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 4        | 0.35%   |
| TP-Link 802.11ac WLAN Adapter                                     | 4        | 0.35%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4        | 0.35%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 4        | 0.35%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 4        | 0.35%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 4        | 0.35%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 4        | 0.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4        | 0.35%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 4        | 0.35%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 4        | 0.35%   |
| Intel Wireless 8260                                               | 4        | 0.35%   |
| Intel Ethernet Connection (14) I219-V                             | 4        | 0.35%   |
| Intel Ethernet Connection (12) I219-V                             | 4        | 0.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 100      | 25.91%  |
| Realtek Semiconductor                 | 97       | 25.13%  |
| Ralink Technology                     | 33       | 8.55%   |
| Qualcomm Atheros                      | 31       | 8.03%   |
| TP-Link                               | 26       | 6.74%   |
| Ralink                                | 20       | 5.18%   |
| Broadcom                              | 19       | 4.92%   |
| NetGear                               | 10       | 2.59%   |
| Microsoft                             | 7        | 1.81%   |
| Qualcomm Atheros Communications       | 6        | 1.55%   |
| MediaTek                              | 6        | 1.55%   |
| D-Link                                | 6        | 1.55%   |
| Edimax Technology                     | 4        | 1.04%   |
| D-Link System                         | 4        | 1.04%   |
| Broadcom Limited                      | 3        | 0.78%   |
| ASUSTek Computer                      | 3        | 0.78%   |
| Gemtek                                | 2        | 0.52%   |
| ZyDAS                                 | 1        | 0.26%   |
| Xiaomi                                | 1        | 0.26%   |
| TRENDnet                              | 1        | 0.26%   |
| Panasonic (Matsushita)                | 1        | 0.26%   |
| Linksys                               | 1        | 0.26%   |
| Belkin Components                     | 1        | 0.26%   |
| AVM                                   | 1        | 0.26%   |
| ADMtek                                | 1        | 0.26%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 30       | 7.69%   |
| Realtek 802.11ac NIC                                           | 18       | 4.62%   |
| Ralink MT7601U Wireless Adapter                                | 15       | 3.85%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 14       | 3.59%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 11       | 2.82%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 10       | 2.56%   |
| Intel Wireless 7265                                            | 10       | 2.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 10       | 2.56%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 9        | 2.31%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 9        | 2.31%   |
| Intel Wireless-AC 9260                                         | 9        | 2.31%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 9        | 2.31%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 8        | 2.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 7        | 1.79%   |
| Ralink RT5370 Wireless Adapter                                 | 6        | 1.54%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 5        | 1.28%   |
| TP-Link TL-WN722N v2                                           | 5        | 1.28%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 5        | 1.28%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 5        | 1.28%   |
| Qualcomm Atheros AR9271 802.11n                                | 5        | 1.28%   |
| NetGear A6210                                                  | 5        | 1.28%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 5        | 1.28%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 5        | 1.28%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 4        | 1.03%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 4        | 1.03%   |
| TP-Link 802.11ac WLAN Adapter                                  | 4        | 1.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4        | 1.03%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 4        | 1.03%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 4        | 1.03%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4        | 1.03%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 4        | 1.03%   |
| Intel Wireless 8260                                            | 4        | 1.03%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter        | 3        | 0.77%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 3        | 0.77%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 3        | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3        | 0.77%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 3        | 0.77%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]    | 3        | 0.77%   |
| Microsoft XBOX ACC                                             | 3        | 0.77%   |
| Microsoft Xbox 360 Wireless Adapter                            | 3        | 0.77%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 3        | 0.77%   |
| Intel Wireless 7260                                            | 3        | 0.77%   |
| D-Link 802.11n WLAN Adapter                                    | 3        | 0.77%   |
| Broadcom BCM43142 802.11b/g/n                                  | 3        | 0.77%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 2        | 0.51%   |
| TP-Link Archer T4U ver.3                                       | 2        | 0.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2        | 0.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2        | 0.51%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter            | 2        | 0.51%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 2        | 0.51%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 2        | 0.51%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2        | 0.51%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 2        | 0.51%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                      | 2        | 0.51%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 2        | 0.51%   |
| Ralink RT2500 Wireless 802.11bg                                | 2        | 0.51%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2        | 0.51%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter     | 2        | 0.51%   |
| MediaTek WiFi                                                  | 2        | 0.51%   |
| Intel Wireless 8265 / 8275                                     | 2        | 0.51%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 400      | 54.35%  |
| Intel                             | 220      | 29.89%  |
| Qualcomm Atheros                  | 40       | 5.43%   |
| Broadcom                          | 18       | 2.45%   |
| Nvidia                            | 14       | 1.9%    |
| Samsung Electronics               | 9        | 1.22%   |
| Marvell Technology Group          | 5        | 0.68%   |
| Huawei Technologies               | 4        | 0.54%   |
| ASIX Electronics                  | 4        | 0.54%   |
| Xiaomi                            | 3        | 0.41%   |
| DisplayLink                       | 3        | 0.41%   |
| Motorola PCS                      | 2        | 0.27%   |
| MediaTek                          | 2        | 0.27%   |
| Aquantia                          | 2        | 0.27%   |
| VIA Technologies                  | 1        | 0.14%   |
| TP-Link                           | 1        | 0.14%   |
| Sundance Technology Inc / IC Plus | 1        | 0.14%   |
| Research In Motion                | 1        | 0.14%   |
| OPPO Electronics                  | 1        | 0.14%   |
| JMicron Technology                | 1        | 0.14%   |
| HMD Global                        | 1        | 0.14%   |
| Google                            | 1        | 0.14%   |
| D-Link System                     | 1        | 0.14%   |
| Broadcom Limited                  | 1        | 0.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 331      | 43.67%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 48       | 6.33%   |
| Realtek RTL8125 2.5GbE Controller                                          | 33       | 4.35%   |
| Intel I211 Gigabit Network Connection                                      | 33       | 4.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 25       | 3.3%    |
| Intel Ethernet Connection (2) I219-V                                       | 23       | 3.03%   |
| Intel Ethernet Connection I217-LM                                          | 20       | 2.64%   |
| Intel Ethernet Controller I225-V                                           | 15       | 1.98%   |
| Intel Ethernet Connection I217-V                                           | 12       | 1.58%   |
| Intel Ethernet Connection (7) I219-V                                       | 10       | 1.32%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 8        | 1.06%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 8        | 1.06%   |
| Nvidia MCP61 Ethernet                                                      | 8        | 1.06%   |
| Intel 82579V Gigabit Network Connection                                    | 8        | 1.06%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 7        | 0.92%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 7        | 0.92%   |
| Intel Ethernet Connection (2) I218-V                                       | 7        | 0.92%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 6        | 0.79%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 6        | 0.79%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 5        | 0.66%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 5        | 0.66%   |
| Intel 82566DM-2 Gigabit Network Connection                                 | 5        | 0.66%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                           | 5        | 0.66%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 4        | 0.53%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                 | 4        | 0.53%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 4        | 0.53%   |
| Intel Ethernet Connection (14) I219-V                                      | 4        | 0.53%   |
| Intel Ethernet Connection (12) I219-V                                      | 4        | 0.53%   |
| Intel 82574L Gigabit Network Connection                                    | 4        | 0.53%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                            | 4        | 0.53%   |
| Nvidia MCP51 Ethernet Controller                                           | 3        | 0.4%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 3        | 0.4%    |
| Intel Ethernet Connection (7) I219-LM                                      | 3        | 0.4%    |
| Intel Ethernet Connection (2) I219-LM                                      | 3        | 0.4%    |
| Intel 82578DC Gigabit Network Connection                                   | 3        | 0.4%    |
| Intel 82566DC-2 Gigabit Network Connection                                 | 3        | 0.4%    |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)                     | 3        | 0.4%    |
| Huawei JNY-LX1                                                             | 3        | 0.4%    |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 2        | 0.26%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 2        | 0.26%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                  | 2        | 0.26%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                              | 2        | 0.26%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 2        | 0.26%   |
| Nvidia MCP73 Ethernet                                                      | 2        | 0.26%   |
| Motorola PCS Moto E (4) Plus                                               | 2        | 0.26%   |
| MediaTek moto e6s                                                          | 2        | 0.26%   |
| Intel I210 Gigabit Network Connection                                      | 2        | 0.26%   |
| Intel Ethernet Connection (5) I219-LM                                      | 2        | 0.26%   |
| Intel 82562V-2 10/100 Network Connection                                   | 2        | 0.26%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                            | 2        | 0.26%   |
| ASIX AX88772                                                               | 2        | 0.26%   |
| ASIX AX88179 Gigabit Ethernet                                              | 2        | 0.26%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 1        | 0.13%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 1        | 0.13%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]            | 1        | 0.13%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.13%   |
| Research In Motion BlackBerry                                              | 1        | 0.13%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 1        | 0.13%   |
| Realtek Killer E3000 2.5GbE Controller                                     | 1        | 0.13%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 1        | 0.13%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 682      | 65.64%  |
| WiFi     | 346      | 33.3%   |
| Modem    | 7        | 0.67%   |
| Unknown  | 4        | 0.38%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 515      | 71.23%  |
| WiFi     | 206      | 28.49%  |
| Modem    | 1        | 0.14%   |
| Unknown  | 1        | 0.14%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 449      | 64.6%   |
| 2     | 208      | 29.93%  |
| 3     | 27       | 3.88%   |
| 0     | 8        | 1.15%   |
| 7     | 1        | 0.14%   |
| 5     | 1        | 0.14%   |
| 4     | 1        | 0.14%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 479      | 68.33%  |
| Yes  | 222      | 31.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 80       | 34.63%  |
| Cambridge Silicon Radio         | 54       | 23.38%  |
| Realtek Semiconductor           | 31       | 13.42%  |
| Broadcom                        | 15       | 6.49%   |
| ASUSTek Computer                | 12       | 5.19%   |
| Qualcomm Atheros Communications | 10       | 4.33%   |
| IMC Networks                    | 6        | 2.6%    |
| Apple                           | 5        | 2.16%   |
| MediaTek                        | 3        | 1.3%    |
| Dynex                           | 3        | 1.3%    |
| TP-Link                         | 2        | 0.87%   |
| Dell                            | 2        | 0.87%   |
| National Semiconductor          | 1        | 0.43%   |
| Micro Star International        | 1        | 0.43%   |
| Lite-On Technology              | 1        | 0.43%   |
| Integrated System Solution      | 1        | 0.43%   |
| Foxconn / Hon Hai               | 1        | 0.43%   |
| Edimax Technology               | 1        | 0.43%   |
| D-Link System                   | 1        | 0.43%   |
| Belkin Components               | 1        | 0.43%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 54       | 23.38%  |
| Realtek Bluetooth Radio                                  | 27       | 11.69%  |
| Intel AX200 Bluetooth                                    | 21       | 9.09%   |
| Intel Bluetooth wireless interface                       | 20       | 8.66%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 10       | 4.33%   |
| Intel Wireless-AC 3168 Bluetooth                         | 9        | 3.9%    |
| Intel AX210 Bluetooth                                    | 9        | 3.9%    |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 6        | 2.6%    |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 6        | 2.6%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 5        | 2.16%   |
| Intel AX201 Bluetooth                                    | 4        | 1.73%   |
| IMC Networks Bluetooth Radio                             | 4        | 1.73%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 3        | 1.3%    |
| Qualcomm Atheros AR3011 Bluetooth                        | 3        | 1.3%    |
| MediaTek Wireless_Device                                 | 3        | 1.3%    |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 3        | 1.3%    |
| Broadcom BCM43142A0 Bluetooth 4.0                        | 3        | 1.3%    |
| Apple Bluetooth USB Host Controller                      | 3        | 1.3%    |
| TP-Link UB500 Adapter                                    | 2        | 0.87%   |
| Realtek RTL8821A Bluetooth                               | 2        | 0.87%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 2        | 0.87%   |
| Dell BT Mini-Receiver                                    | 2        | 0.87%   |
| Broadcom HP Portable Bumble Bee                          | 2        | 0.87%   |
| ASUS Qualcomm Bluetooth 4.1                              | 2        | 0.87%   |
| ASUS Bluetooth Radio                                     | 2        | 0.87%   |
| Realtek RTL8723B Bluetooth                               | 1        | 0.43%   |
| Realtek  Bluetooth 4.2 Adapter                           | 1        | 0.43%   |
| Qualcomm Atheros  Bluetooth Device                       | 1        | 0.43%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 1        | 0.43%   |
| Qualcomm Atheros Bluetooth                               | 1        | 0.43%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                    | 1        | 0.43%   |
| National Bluetooth Dongle                                | 1        | 0.43%   |
| Micro Star International Bluetooth Device                | 1        | 0.43%   |
| Lite-On Bluetooth Device                                 | 1        | 0.43%   |
| Integrated System Solution Bluetooth Device              | 1        | 0.43%   |
| IMC Networks Bluetooth Module                            | 1        | 0.43%   |
| IMC Networks Bluetooth Device                            | 1        | 0.43%   |
| Foxconn / Hon Hai Bluetooth Device                       | 1        | 0.43%   |
| Edimax Bluetooth Adapter                                 | 1        | 0.43%   |
| D-Link System DBT-122 Bluetooth                          | 1        | 0.43%   |
| Broadcom HP Bluetooth Module                             | 1        | 0.43%   |
| Broadcom Bluetooth Device                                | 1        | 0.43%   |
| Broadcom Bluetooth 2.0+EDR dongle                        | 1        | 0.43%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter         | 1        | 0.43%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter    | 1        | 0.43%   |
| ASUS BCM20702A0                                          | 1        | 0.43%   |
| ASUS ASUS USB-BT500                                      | 1        | 0.43%   |
| Apple Bluetooth Host Controller                          | 1        | 0.43%   |
| Apple Bluetooth HCI                                      | 1        | 0.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 452      | 38.93%  |
| AMD                                  | 293      | 25.24%  |
| Nvidia                               | 275      | 23.69%  |
| C-Media Electronics                  | 29       | 2.5%    |
| Creative Labs                        | 13       | 1.12%   |
| Kingston Technology                  | 9        | 0.78%   |
| Texas Instruments                    | 7        | 0.6%    |
| Logitech                             | 7        | 0.6%    |
| JMTek                                | 7        | 0.6%    |
| VIA Technologies                     | 5        | 0.43%   |
| Plantronics                          | 5        | 0.43%   |
| Razer USA                            | 4        | 0.34%   |
| GN Netcom                            | 4        | 0.34%   |
| ASUSTek Computer                     | 4        | 0.34%   |
| SteelSeries ApS                      | 2        | 0.17%   |
| Sennheiser Communications            | 2        | 0.17%   |
| Realtek Semiconductor                | 2        | 0.17%   |
| Micro Star International             | 2        | 0.17%   |
| Creative Technology                  | 2        | 0.17%   |
| XMOS                                 | 1        | 0.09%   |
| Valve Software                       | 1        | 0.09%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.09%   |
| Tenx Technology                      | 1        | 0.09%   |
| Swissonic                            | 1        | 0.09%   |
| Silicon Labs                         | 1        | 0.09%   |
| SAVITECH                             | 1        | 0.09%   |
| Samsung Electronics                  | 1        | 0.09%   |
| ROCCAT                               | 1        | 0.09%   |
| Qualcomm                             | 1        | 0.09%   |
| Philips (or NXP)                     | 1        | 0.09%   |
| Numark                               | 1        | 0.09%   |
| Microsoft                            | 1        | 0.09%   |
| Micronas                             | 1        | 0.09%   |
| Medeli Electronics                   | 1        | 0.09%   |
| LucidSound                           | 1        | 0.09%   |
| Klipsch Audio                        | 1        | 0.09%   |
| INSIGNIA                             | 1        | 0.09%   |
| iCreate Technologies                 | 1        | 0.09%   |
| iConnectivity                        | 1        | 0.09%   |
| Hangzhou Worlde                      | 1        | 0.09%   |
| Google                               | 1        | 0.09%   |
| Generalplus Technology               | 1        | 0.09%   |
| GEMBIRD                              | 1        | 0.09%   |
| Focusrite-Novation                   | 1        | 0.09%   |
| FIFINE Microphones                   | 1        | 0.09%   |
| Evolution Electronics                | 1        | 0.09%   |
| EGO SYStems                          | 1        | 0.09%   |
| DigiTech                             | 1        | 0.09%   |
| Corsair                              | 1        | 0.09%   |
| Cambridge Audio                      | 1        | 0.09%   |
| BR25                                 | 1        | 0.09%   |
| Blue Microphones                     | 1        | 0.09%   |
| AudioQuest                           | 1        | 0.09%   |
| Audio-Technica                       | 1        | 0.09%   |
| Asahi Kasei Microsystems             | 1        | 0.09%   |
| A4Tech                               | 1        | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 76       | 5.73%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 69       | 5.2%    |
| AMD Starship/Matisse HD Audio Controller                                          | 66       | 4.97%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 58       | 4.37%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 47       | 3.54%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 47       | 3.54%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 40       | 3.01%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 37       | 2.79%   |
| Intel Cannon Lake PCH cAVS                                                        | 28       | 2.11%   |
| AMD FCH Azalia Controller                                                         | 28       | 2.11%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 27       | 2.03%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 25       | 1.88%   |
| AMD Family 17h/19h HD Audio Controller                                            | 24       | 1.81%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 24       | 1.81%   |
| Intel 200 Series PCH HD Audio                                                     | 22       | 1.66%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 20       | 1.51%   |
| Nvidia GF119 HDMI Audio Controller                                                | 18       | 1.36%   |
| Nvidia TU116 High Definition Audio Controller                                     | 16       | 1.21%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 16       | 1.21%   |
| Nvidia GF108 High Definition Audio Controller                                     | 16       | 1.21%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 16       | 1.21%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 15       | 1.13%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 15       | 1.13%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 13       | 0.98%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 13       | 0.98%   |
| AMD Navi 10 HDMI Audio                                                            | 13       | 0.98%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 13       | 0.98%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 13       | 0.98%   |
| Nvidia High Definition Audio Controller                                           | 12       | 0.9%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 12       | 0.9%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 12       | 0.9%    |
| Nvidia TU106 High Definition Audio Controller                                     | 11       | 0.83%   |
| Nvidia GP106 High Definition Audio Controller                                     | 11       | 0.83%   |
| Nvidia GM204 High Definition Audio Controller                                     | 11       | 0.83%   |
| Nvidia GK107 HDMI Audio Controller                                                | 11       | 0.83%   |
| Intel Audio device                                                                | 11       | 0.83%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 11       | 0.83%   |
| Nvidia GP104 High Definition Audio Controller                                     | 9        | 0.68%   |
| Intel Comet Lake PCH-V cAVS                                                       | 9        | 0.68%   |
| AMD Kabini HDMI/DP Audio                                                          | 9        | 0.68%   |
| Nvidia MCP61 High Definition Audio                                                | 8        | 0.6%    |
| Nvidia GM206 High Definition Audio Controller                                     | 8        | 0.6%    |
| Nvidia GK104 HDMI Audio Controller                                                | 8        | 0.6%    |
| Intel Alder Lake-S HD Audio Controller                                            | 8        | 0.6%    |
| AMD Renoir Radeon High Definition Audio Controller                                | 8        | 0.6%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 7        | 0.53%   |
| Nvidia GP108 High Definition Audio Controller                                     | 7        | 0.53%   |
| Nvidia GA102 High Definition Audio Controller                                     | 7        | 0.53%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 7        | 0.53%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 7        | 0.53%   |
| Nvidia TU104 HD Audio Controller                                                  | 6        | 0.45%   |
| Nvidia GA106 High Definition Audio Controller                                     | 6        | 0.45%   |
| Nvidia GA104 High Definition Audio Controller                                     | 6        | 0.45%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 6        | 0.45%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                     | 6        | 0.45%   |
| AMD Trinity HDMI Audio Controller                                                 | 6        | 0.45%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                      | 6        | 0.45%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 6        | 0.45%   |
| Nvidia GK106 HDMI Audio Controller                                                | 5        | 0.38%   |
| Nvidia GF116 High Definition Audio Controller                                     | 5        | 0.38%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 16       | 16%     |
| Kingston            | 16       | 16%     |
| Samsung Electronics | 13       | 13%     |
| G.Skill             | 13       | 13%     |
| Corsair             | 10       | 10%     |
| SK hynix            | 8        | 8%      |
| Crucial             | 7        | 7%      |
| Micron Technology   | 5        | 5%      |
| Team                | 3        | 3%      |
| Ramaxel Technology  | 2        | 2%      |
| Unifosa             | 1        | 1%      |
| Patriot             | 1        | 1%      |
| Nanya Technology    | 1        | 1%      |
| Goldkey             | 1        | 1%      |
| F7852C80            | 1        | 1%      |
| Elpida              | 1        | 1%      |
| Unknown             | 1        | 1%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                   | 2        | 1.83%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3                    | 2        | 1.83%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s           | 2        | 1.83%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s         | 2        | 1.83%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s            | 2        | 1.83%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 2        | 1.83%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s            | 2        | 1.83%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s          | 2        | 1.83%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s            | 2        | 1.83%   |
| G.Skill RAM F4-3200C16-16GTZR 16384MB DIMM DDR4 3333MT/s       | 2        | 1.83%   |
| Unknown RAM TM44D18UD04MU-NUK 4096MB DIMM DDR4 2400MT/s        | 1        | 0.92%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                      | 1        | 0.92%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                           | 1        | 0.92%   |
| Unknown RAM Module 8192MB DIMM DDR4 2400MT/s                   | 1        | 0.92%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                   | 1        | 0.92%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                       | 1        | 0.92%   |
| Unknown RAM Module 4GB DIMM 400MT/s                            | 1        | 0.92%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                           | 1        | 0.92%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 1        | 0.92%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                   | 1        | 0.92%   |
| Unknown RAM Module 4096MB DIMM DDR 1600MT/s                    | 1        | 0.92%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                         | 1        | 0.92%   |
| Unknown RAM Module 2GB DIMM DDR2                               | 1        | 0.92%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                 | 1        | 0.92%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                   | 1        | 0.92%   |
| Unknown RAM Module 2048MB DIMM DDR2 1333MT/s                   | 1        | 0.92%   |
| Unknown RAM Module 1GB DIMM DDR2 333MT/s                       | 1        | 0.92%   |
| Unknown RAM Module 1GB DIMM 400MT/s                            | 1        | 0.92%   |
| Unknown RAM 04S2400CL17A 4096MB DIMM DDR4 2400MT/s             | 1        | 0.92%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s              | 1        | 0.92%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s            | 1        | 0.92%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 3000MT/s            | 1        | 0.92%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s             | 1        | 0.92%   |
| SK hynix RAM HMT41GU6AFR8A-PB 8192MB DIMM DDR3 1600MT/s        | 1        | 0.92%   |
| SK hynix RAM HMT351U6CFR8C-H9 4096MB DIMM DDR3 1600MT/s        | 1        | 0.92%   |
| SK hynix RAM HMT325U6EFR8C-PB 2GB DIMM DDR3 1600MT/s           | 1        | 0.92%   |
| SK hynix RAM HMA451U6AFR8N-TF 4096MB DIMM DDR4 2133MT/s        | 1        | 0.92%   |
| SK hynix RAM HKNNNFBMAVAR-NEH 2GB Row Of Chips LPDDR4 3200MT/s | 1        | 0.92%   |
| Samsung RAM Module 8192MB DIMM DDR4 2133MT/s                   | 1        | 0.92%   |
| Samsung RAM M471B5773DH0-CH9 2048MB DIMM DDR3 1333MT/s         | 1        | 0.92%   |
| Samsung RAM M471B5273CH0-CH9 4096MB DIMM DDR3 1333MT/s         | 1        | 0.92%   |
| Samsung RAM M393B2G70BH0 16GB DIMM DDR3 1866MT/s               | 1        | 0.92%   |
| Samsung RAM M393B1K70DH0 8192MB DIMM DDR3 1866MT/s             | 1        | 0.92%   |
| Samsung RAM M393B1K70BH1 8192MB DIMM DDR3 1333MT/s             | 1        | 0.92%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s            | 1        | 0.92%   |
| Samsung RAM M378B5173QH0-YK0 4096MB DIMM DDR3 1600MT/s         | 1        | 0.92%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1866MT/s            | 1        | 0.92%   |
| Samsung RAM M378B1G73EB0-CK0 8GB DIMM DDR3 1600MT/s            | 1        | 0.92%   |
| Ramaxel RAM RMUA5110ME78HAF-2666 8GB DIMM DDR4 2667MT/s        | 1        | 0.92%   |
| Ramaxel RAM RMR5030ED58E8W1600 2048MB DIMM DDR3 1600MT/s       | 1        | 0.92%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s             | 1        | 0.92%   |
| Nanya RAM Module 4096MB DIMM DDR4 2400MT/s                     | 1        | 0.92%   |
| Micron RAM Module 4096MB FB-DIMM DDR2 800MT/s                  | 1        | 0.92%   |
| Micron RAM 8KTF51264AZ-1G6E1 4096MB DIMM DDR3 1600MT/s         | 1        | 0.92%   |
| Micron RAM 36KSF1G72PZ-1 8192MB DIMM DDR3 1600MT/s             | 1        | 0.92%   |
| Micron RAM 36JSF2G72PZ-1 16384MB DIMM DDR3 1866MT/s            | 1        | 0.92%   |
| Micron RAM 16KTF1G64AZ-1G6P1 8GB DIMM DDR3 1600MT/s            | 1        | 0.92%   |
| Kingston RAM KP223C-ELD 2GB DIMM 1600MT/s                      | 1        | 0.92%   |
| Kingston RAM KHX2666C15D4/4G 4GB DIMM DDR4 3200MT/s            | 1        | 0.92%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s            | 1        | 0.92%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 37       | 42.05%  |
| DDR3    | 37       | 42.05%  |
| Unknown | 7        | 7.95%   |
| DDR2    | 4        | 4.55%   |
| DDR     | 2        | 2.27%   |
| LPDDR4  | 1        | 1.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 84       | 95.45%  |
| SODIMM       | 2        | 2.27%   |
| Row Of Chips | 1        | 1.14%   |
| FB-DIMM      | 1        | 1.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 41       | 41.84%  |
| 4096  | 29       | 29.59%  |
| 16384 | 11       | 11.22%  |
| 2048  | 11       | 11.22%  |
| 32768 | 4        | 4.08%   |
| 1024  | 2        | 2.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 20       | 20.62%  |
| 1333    | 14       | 14.43%  |
| 3600    | 10       | 10.31%  |
| 3200    | 10       | 10.31%  |
| 2133    | 6        | 6.19%   |
| 3466    | 4        | 4.12%   |
| 2400    | 4        | 4.12%   |
| 1866    | 4        | 4.12%   |
| 1800    | 4        | 4.12%   |
| 2667    | 3        | 3.09%   |
| 3333    | 2        | 2.06%   |
| 3000    | 2        | 2.06%   |
| 1867    | 2        | 2.06%   |
| 4000    | 1        | 1.03%   |
| 3666    | 1        | 1.03%   |
| 2800    | 1        | 1.03%   |
| 2666    | 1        | 1.03%   |
| 2200    | 1        | 1.03%   |
| 1400    | 1        | 1.03%   |
| 976     | 1        | 1.03%   |
| 800     | 1        | 1.03%   |
| 667     | 1        | 1.03%   |
| 400     | 1        | 1.03%   |
| 333     | 1        | 1.03%   |
| Unknown | 1        | 1.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 6        | 21.43%  |
| Canon               | 6        | 21.43%  |
| Brother Industries  | 6        | 21.43%  |
| Seiko Epson         | 5        | 17.86%  |
| Hewlett-Packard     | 5        | 17.86%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seiko Epson L3110 Series             | 2        | 7.14%   |
| Seiko Epson XP-7100 Series           | 1        | 3.57%   |
| Seiko Epson XP-202 203 206 Series    | 1        | 3.57%   |
| Seiko Epson ET-2820 Series           | 1        | 3.57%   |
| Samsung SCX-483x 5x3x Series         | 1        | 3.57%   |
| Samsung SCX-4200 series              | 1        | 3.57%   |
| Samsung SCX-3400 Series              | 1        | 3.57%   |
| Samsung ML-2950 Series               | 1        | 3.57%   |
| Samsung ML-216x Series Laser Printer | 1        | 3.57%   |
| Samsung C460 Series                  | 1        | 3.57%   |
| HP Smart Tank 510 series             | 1        | 3.57%   |
| HP OfficeJet 4650 series             | 1        | 3.57%   |
| HP LaserJet Professional P1102w      | 1        | 3.57%   |
| HP ENVY 4520 series                  | 1        | 3.57%   |
| HP DeskJet 2700 series               | 1        | 3.57%   |
| Canon TS3100 series                  | 1        | 3.57%   |
| Canon TR4500 series                  | 1        | 3.57%   |
| Canon PIXMA MG2500 Series            | 1        | 3.57%   |
| Canon LiDE 400                       | 1        | 3.57%   |
| Canon iP4200                         | 1        | 3.57%   |
| Canon G3010 series                   | 1        | 3.57%   |
| Brother MFC-J1010DW                  | 1        | 3.57%   |
| Brother MFC-9140CDN                  | 1        | 3.57%   |
| Brother MFC-1810                     | 1        | 3.57%   |
| Brother HL-3142CW series             | 1        | 3.57%   |
| Brother HL-2140 series               | 1        | 3.57%   |
| Brother DCP-L2540DW                  | 1        | 3.57%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 5        | 83.33%  |
| Hewlett-Packard | 1        | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| HP ScanJet 2400c        | 1        | 16.67%  |
| Canon CanoScan LiDE 60  | 1        | 16.67%  |
| Canon CanoScan LiDE 110 | 1        | 16.67%  |
| Canon CanoScan LiDE 100 | 1        | 16.67%  |
| Canon CanoScan D660U    | 1        | 16.67%  |
| Canon CanoScan 8800F    | 1        | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 30       | 27.52%  |
| Microdia                      | 14       | 12.84%  |
| Microsoft                     | 7        | 6.42%   |
| Sunplus Innovation Technology | 6        | 5.5%    |
| Samsung Electronics           | 6        | 5.5%    |
| ARC International             | 6        | 5.5%    |
| Generalplus Technology        | 5        | 4.59%   |
| Chicony Electronics           | 4        | 3.67%   |
| Jieli Technology              | 3        | 2.75%   |
| Xiongmai                      | 2        | 1.83%   |
| webcam                        | 2        | 1.83%   |
| Realtek Semiconductor         | 2        | 1.83%   |
| Razer USA                     | 2        | 1.83%   |
| Guillemot                     | 2        | 1.83%   |
| Creative Technology           | 2        | 1.83%   |
| Apple                         | 2        | 1.83%   |
| Unknown                       | 1        | 0.92%   |
| Teslong Camera                | 1        | 0.92%   |
| Suyin                         | 1        | 0.92%   |
| Sunplus Technology            | 1        | 0.92%   |
| Sonix Technology              | 1        | 0.92%   |
| lihappe8                      | 1        | 0.92%   |
| INOGENI                       | 1        | 0.92%   |
| IMC Networks                  | 1        | 0.92%   |
| Hewlett-Packard               | 1        | 0.92%   |
| Genesys Logic                 | 1        | 0.92%   |
| Cubeternet                    | 1        | 0.92%   |
| AVerMedia Technologies        | 1        | 0.92%   |
| Arkmicro Technologies         | 1        | 0.92%   |
| Alcor Micro                   | 1        | 0.92%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Logitech Webcam C270                     | 10       | 9.01%   |
| Samsung Galaxy series, misc. (MTP mode)  | 6        | 5.41%   |
| ARC International Camera                 | 6        | 5.41%   |
| Microsoft LifeCam HD-3000                | 5        | 4.5%    |
| Microdia USB 2.0 Camera                  | 4        | 3.6%    |
| Generalplus GENERAL WEBCAM               | 4        | 3.6%    |
| Sunplus HD 720P webcam                   | 3        | 2.7%    |
| Logitech HD Pro Webcam C920              | 3        | 2.7%    |
| Jieli USB PHY 2.0                        | 3        | 2.7%    |
| Chicony HP High Definition 1MP Webcam    | 3        | 2.7%    |
| Xiongmai web camera                      | 2        | 1.8%    |
| webcam webcam                            | 2        | 1.8%    |
| Razer USA Gaming Webcam [Kiyo]           | 2        | 1.8%    |
| Microdia Webcam Vitade AF                | 2        | 1.8%    |
| Microdia USB Live camera                 | 2        | 1.8%    |
| Microdia Integrated Camera               | 2        | 1.8%    |
| Logitech HD Webcam C910                  | 2        | 1.8%    |
| Logitech HD Webcam C615                  | 2        | 1.8%    |
| Logitech C922 Pro Stream Webcam          | 2        | 1.8%    |
| Logitech C920 PRO HD Webcam              | 2        | 1.8%    |
| Apple iPhone 5/5C/5S/6/SE                | 2        | 1.8%    |
| Unknown HD camera                        | 1        | 0.9%    |
| Teslong Camera Teslong Camera            | 1        | 0.9%    |
| Suyin HD WebCam                          | 1        | 0.9%    |
| Sunplus General Image Device             | 1        | 0.9%    |
| Sunplus Integrated Camera                | 1        | 0.9%    |
| Sunplus Depstech webcam MIC              | 1        | 0.9%    |
| Sunplus 5Mega Webcam                     | 1        | 0.9%    |
| Sonix USB 2.0 Camera                     | 1        | 0.9%    |
| Realtek NexiGo N660P FHD Webcam          | 1        | 0.9%    |
| Realtek HP High Definition 1MP Webcam    | 1        | 0.9%    |
| Microsoft MicrosoftÂ LifeCam Cinema     | 1        | 0.9%    |
| Microsoft LifeCam VX-2000                | 1        | 0.9%    |
| Microdia PC Camera (SN9C110)             | 1        | 0.9%    |
| Microdia NEXIGO HD Webcam                | 1        | 0.9%    |
| Microdia Camera                          | 1        | 0.9%    |
| Microdia AUKEY PC-W1                     | 1        | 0.9%    |
| Logitech Webcam Pro 9000                 | 1        | 0.9%    |
| Logitech Webcam C925e                    | 1        | 0.9%    |
| Logitech Webcam C310                     | 1        | 0.9%    |
| Logitech Webcam C260                     | 1        | 0.9%    |
| Logitech QuickCam Pro for Notebooks      | 1        | 0.9%    |
| Logitech QuickCam Pro 4000               | 1        | 0.9%    |
| Logitech QuickCam E 3500                 | 1        | 0.9%    |
| Logitech Portable Webcam C905            | 1        | 0.9%    |
| Logitech HD Webcam C525                  | 1        | 0.9%    |
| Logitech HD Webcam B990                  | 1        | 0.9%    |
| Logitech CrystalCam                      | 1        | 0.9%    |
| lihappe8 USB 2.0 Camera                  | 1        | 0.9%    |
| INOGENI 1C2F-INOGENI 4K2USB3             | 1        | 0.9%    |
| IMC Networks USB2.0 UVC 1.3M WebCam      | 1        | 0.9%    |
| HP Webcam HD 2300                        | 1        | 0.9%    |
| Guillemot Hercules HD Sunset             | 1        | 0.9%    |
| Guillemot Hercules HD Emotion            | 1        | 0.9%    |
| Genesys Logic Camera                     | 1        | 0.9%    |
| Generalplus 808 Camera #9 (web-cam mode) | 1        | 0.9%    |
| Cubeternet GL-UPC822 UVC WebCam          | 1        | 0.9%    |
| Creative Live! Cam Sync HD [VF0770]      | 1        | 0.9%    |
| Creative Live! Cam Chat HD [VF0700]      | 1        | 0.9%    |
| Chicony CNF8050 Webcam                   | 1        | 0.9%    |

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


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Reiner SCT Kartensysteme  | 1        | 20%     |
| Realtek Semiconductor     | 1        | 20%     |
| Fujitsu Siemens Computers | 1        | 20%     |
| Alcor Micro               | 1        | 20%     |
| Advanced Card Systems     | 1        | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Reiner SCT Kartensysteme cyberJack e-com/pinpad   | 1        | 20%     |
| Realtek Semiconductor Smart Card Reader Interface | 1        | 20%     |
| Fujitsu Siemens Computers SmartCard Reader 2A     | 1        | 20%     |
| Alcor Micro AU9540 Smartcard Reader               | 1        | 20%     |
| Advanced Card Systems ACR39U                      | 1        | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 573      | 81.97%  |
| 1     | 113      | 16.17%  |
| 2     | 12       | 1.72%   |
| 3     | 1        | 0.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 56       | 41.18%  |
| Graphics card            | 51       | 37.5%   |
| Communication controller | 8        | 5.88%   |
| Multimedia controller    | 5        | 3.68%   |
| Chipcard                 | 4        | 2.94%   |
| Unassigned class         | 3        | 2.21%   |
| Modem                    | 2        | 1.47%   |
| Camera                   | 2        | 1.47%   |
| Storage/raid             | 1        | 0.74%   |
| Storage/ide              | 1        | 0.74%   |
| Sound                    | 1        | 0.74%   |
| Dvb card                 | 1        | 0.74%   |
| Card reader              | 1        | 0.74%   |

