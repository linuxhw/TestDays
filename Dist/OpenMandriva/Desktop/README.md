OpenMandriva - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for OpenMandriva.

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

Total: 7906

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | SHARKBAY NOK                | [26332591d7](https://linux-hardware.org/?probe=26332591d7) | Nov 06, 2023 |
| ASUSTek       | PRIME Z270-A                | [725ce23e28](https://linux-hardware.org/?probe=725ce23e28) | Nov 06, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [77a31d50ce](https://linux-hardware.org/?probe=77a31d50ce) | Nov 06, 2023 |
| MSI           | A520M PRO                   | [b83b272494](https://linux-hardware.org/?probe=b83b272494) | Nov 06, 2023 |
| Gigabyte      | B550M S2H                   | [b58de33b7d](https://linux-hardware.org/?probe=b58de33b7d) | Nov 06, 2023 |
| ASUSTek       | A68HM-K                     | [c3e5415128](https://linux-hardware.org/?probe=c3e5415128) | Nov 06, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [ff199303a2](https://linux-hardware.org/?probe=ff199303a2) | Nov 06, 2023 |
| Gigabyte      | A320M-H-CF                  | [105d51f329](https://linux-hardware.org/?probe=105d51f329) | Nov 05, 2023 |
| MSI           | A55M-E33                    | [d1def05873](https://linux-hardware.org/?probe=d1def05873) | Nov 05, 2023 |
| HP            | 802F                        | [8fe557cc85](https://linux-hardware.org/?probe=8fe557cc85) | Nov 05, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [2710dfedf4](https://linux-hardware.org/?probe=2710dfedf4) | Nov 05, 2023 |
| ASUSTek       | G11CD                       | [8fcbd49e37](https://linux-hardware.org/?probe=8fcbd49e37) | Nov 05, 2023 |
| ASRock        | 970 Pro3 R2.0               | [f070e73453](https://linux-hardware.org/?probe=f070e73453) | Nov 05, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [459eb3cd2a](https://linux-hardware.org/?probe=459eb3cd2a) | Nov 04, 2023 |
| Acer          | Aspire M1920                | [f6ffcb0c41](https://linux-hardware.org/?probe=f6ffcb0c41) | Nov 04, 2023 |
| Gigabyte      | GA-870A-USB3L               | [d2412dfd7c](https://linux-hardware.org/?probe=d2412dfd7c) | Nov 04, 2023 |
| ASRock        | FM2A68M-HD+                 | [2b5c984cd8](https://linux-hardware.org/?probe=2b5c984cd8) | Nov 04, 2023 |
| Dell          | 0W0CHX A00                  | [3ed37b3d70](https://linux-hardware.org/?probe=3ed37b3d70) | Nov 04, 2023 |
| ASUSTek       | H110M-D                     | [03303fa6ed](https://linux-hardware.org/?probe=03303fa6ed) | Nov 04, 2023 |
| ASRock        | B450M Steel Legend          | [ea9a865ed2](https://linux-hardware.org/?probe=ea9a865ed2) | Nov 03, 2023 |
| Dell          | 0MGK50 A02                  | [ca062f44be](https://linux-hardware.org/?probe=ca062f44be) | Nov 03, 2023 |
| HP            | 2215                        | [6acbe1a873](https://linux-hardware.org/?probe=6acbe1a873) | Nov 03, 2023 |
| Biostar       | B250MHC                     | [528c04a30a](https://linux-hardware.org/?probe=528c04a30a) | Nov 02, 2023 |
| MSI           | H110M PRO-D                 | [da5c3ffb7e](https://linux-hardware.org/?probe=da5c3ffb7e) | Nov 02, 2023 |
| ASRock        | H81M-HG4 R4.0               | [0f5f162498](https://linux-hardware.org/?probe=0f5f162498) | Nov 02, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | [801d83a570](https://linux-hardware.org/?probe=801d83a570) | Nov 01, 2023 |
| Foxconn       | 2ADA                        | [18271c13c3](https://linux-hardware.org/?probe=18271c13c3) | Nov 01, 2023 |
| ASUSTek       | M3A32-MVP DELUXE            | [fecdf24435](https://linux-hardware.org/?probe=fecdf24435) | Nov 01, 2023 |
| AMI           | Intel                       | [c4587092bf](https://linux-hardware.org/?probe=c4587092bf) | Nov 01, 2023 |
| HP            | ProLiant ML310e Gen8 v2     | [27d8415c88](https://linux-hardware.org/?probe=27d8415c88) | Nov 01, 2023 |
| Gigabyte      | B75M-HD3                    | [e27c813285](https://linux-hardware.org/?probe=e27c813285) | Oct 31, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [763630b66c](https://linux-hardware.org/?probe=763630b66c) | Oct 31, 2023 |
| Acer          | Veriton M480                | [fb5c756319](https://linux-hardware.org/?probe=fb5c756319) | Oct 30, 2023 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [4d9e5a7157](https://linux-hardware.org/?probe=4d9e5a7157) | Oct 30, 2023 |
| Gigabyte      | H81M-HD3                    | [1be6955dfc](https://linux-hardware.org/?probe=1be6955dfc) | Oct 30, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [09d5186c37](https://linux-hardware.org/?probe=09d5186c37) | Oct 30, 2023 |
| ASUSTek       | P5E Deluxe                  | [5601096ffc](https://linux-hardware.org/?probe=5601096ffc) | Oct 29, 2023 |
| Intel         | B75                         | [a46db29108](https://linux-hardware.org/?probe=a46db29108) | Oct 29, 2023 |
| Gigabyte      | X570 GAMING X               | [1addefe3fc](https://linux-hardware.org/?probe=1addefe3fc) | Oct 29, 2023 |
| ASUSTek       | PRIME B250-PRO              | [ac060a5eb6](https://linux-hardware.org/?probe=ac060a5eb6) | Oct 29, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | [0be3861a6a](https://linux-hardware.org/?probe=0be3861a6a) | Oct 29, 2023 |
| ASUSTek       | P5B                         | [aa136c9e44](https://linux-hardware.org/?probe=aa136c9e44) | Oct 29, 2023 |
| Dell          | 03NVJ6 A01                  | [09d76f025a](https://linux-hardware.org/?probe=09d76f025a) | Oct 29, 2023 |
| Gigabyte      | H61MA-D3V                   | [0c4d99e9dc](https://linux-hardware.org/?probe=0c4d99e9dc) | Oct 29, 2023 |
| Gigabyte      | 970A-DS3P                   | [31d6b19c8d](https://linux-hardware.org/?probe=31d6b19c8d) | Oct 29, 2023 |
| HP            | 339A                        | [a1ef9b1cd4](https://linux-hardware.org/?probe=a1ef9b1cd4) | Oct 29, 2023 |
| Koloe         | X58                         | [91fbabe04c](https://linux-hardware.org/?probe=91fbabe04c) | Oct 29, 2023 |
| Dell          | 0JP3NX A00                  | [434961d005](https://linux-hardware.org/?probe=434961d005) | Oct 28, 2023 |
| ASRock        | B450 Steel Legend           | [21beb00969](https://linux-hardware.org/?probe=21beb00969) | Oct 28, 2023 |
| Unknown       | Phitronics G31VS-M          | [10bcfab3cb](https://linux-hardware.org/?probe=10bcfab3cb) | Oct 28, 2023 |
| Gigabyte      | Z370M D3H-CF                | [80b6c027b0](https://linux-hardware.org/?probe=80b6c027b0) | Oct 27, 2023 |
| ASUSTek       | A68HM-PLUS                  | [9d662bd187](https://linux-hardware.org/?probe=9d662bd187) | Oct 27, 2023 |
| Foxconn       | 17A0                        | [ce8f3561ee](https://linux-hardware.org/?probe=ce8f3561ee) | Oct 27, 2023 |
| HP            | 8054                        | [3f9ecca91a](https://linux-hardware.org/?probe=3f9ecca91a) | Oct 26, 2023 |
| Acer          | EG31M R01-C3                | [8a4232c8f0](https://linux-hardware.org/?probe=8a4232c8f0) | Oct 26, 2023 |
| ECS           | H81H3-M3S                   | [6f4c530a93](https://linux-hardware.org/?probe=6f4c530a93) | Oct 26, 2023 |
| ASUSTek       | P5E-VM HDMI                 | [4491bc9ec0](https://linux-hardware.org/?probe=4491bc9ec0) | Oct 26, 2023 |
| Pegatron      | 2AC3                        | [1508d1c2f7](https://linux-hardware.org/?probe=1508d1c2f7) | Oct 26, 2023 |
| ASUSTek       | M5A78L-M LX3                | [d3dacafdc2](https://linux-hardware.org/?probe=d3dacafdc2) | Oct 26, 2023 |
| Dell          | 03NJH0 A01                  | [dbb152a219](https://linux-hardware.org/?probe=dbb152a219) | Oct 26, 2023 |
| ASUSTek       | H170M-PLUS                  | [a108993a7e](https://linux-hardware.org/?probe=a108993a7e) | Oct 25, 2023 |
| MSI           | H110M PRO-VD                | [b62701c032](https://linux-hardware.org/?probe=b62701c032) | Oct 25, 2023 |
| HP            | 198E                        | [3102593d74](https://linux-hardware.org/?probe=3102593d74) | Oct 25, 2023 |
| MSI           | GF615M-P33                  | [364be0dfae](https://linux-hardware.org/?probe=364be0dfae) | Oct 24, 2023 |
| Lenovo        | ThinkCentre M90 5485W2L     | [0fcc4fe794](https://linux-hardware.org/?probe=0fcc4fe794) | Oct 24, 2023 |
| MSI           | Z490-A PRO                  | [011bfdd699](https://linux-hardware.org/?probe=011bfdd699) | Oct 24, 2023 |
| EPSON DIRE... | AT992E                      | [b61468f9c5](https://linux-hardware.org/?probe=b61468f9c5) | Oct 24, 2023 |
| Fujitsu       | D2778-C1 S26361-D2778-C1    | [e22a3baeb9](https://linux-hardware.org/?probe=e22a3baeb9) | Oct 23, 2023 |
| Lenovo        | 30C7 SDK0J40709 WIN 3259... | [71fd7dde1d](https://linux-hardware.org/?probe=71fd7dde1d) | Oct 23, 2023 |
| MSI           | PRO Z690-P DDR4             | [35e54833e8](https://linux-hardware.org/?probe=35e54833e8) | Oct 23, 2023 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | [1e4819e6d1](https://linux-hardware.org/?probe=1e4819e6d1) | Oct 23, 2023 |
| HP            | 3397                        | [3f8e8810c1](https://linux-hardware.org/?probe=3f8e8810c1) | Oct 23, 2023 |
| ASUSTek       | P5G41T-M LX                 | [6f72e3839d](https://linux-hardware.org/?probe=6f72e3839d) | Oct 23, 2023 |
| Gigabyte      | EX38-DS5                    | [79e9d5669a](https://linux-hardware.org/?probe=79e9d5669a) | Oct 23, 2023 |
| Gigabyte      | G41MT-S2                    | [3df6a3e3e4](https://linux-hardware.org/?probe=3df6a3e3e4) | Oct 23, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [3e46064143](https://linux-hardware.org/?probe=3e46064143) | Oct 22, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [9d3213958f](https://linux-hardware.org/?probe=9d3213958f) | Oct 21, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [91318c1cf1](https://linux-hardware.org/?probe=91318c1cf1) | Oct 21, 2023 |
| WinFast       | 761GXK8MC                   | [7b4f49eda5](https://linux-hardware.org/?probe=7b4f49eda5) | Oct 21, 2023 |
| HP            | 09F0h                       | [97710d8f02](https://linux-hardware.org/?probe=97710d8f02) | Oct 21, 2023 |
| MSI           | B350M MORTAR                | [8dce4bcd71](https://linux-hardware.org/?probe=8dce4bcd71) | Oct 21, 2023 |
| ASUSTek       | H170 PRO GAMING             | [859edb18bd](https://linux-hardware.org/?probe=859edb18bd) | Oct 21, 2023 |
| ASUSTek       | PRIME B250M-A               | [ff0d8bbab4](https://linux-hardware.org/?probe=ff0d8bbab4) | Oct 21, 2023 |
| Biostar       | H61MH                       | [996528ed4e](https://linux-hardware.org/?probe=996528ed4e) | Oct 21, 2023 |
| Gigabyte      | H370 AORUS GAMING 3-CF      | [1303e88b7c](https://linux-hardware.org/?probe=1303e88b7c) | Oct 21, 2023 |
| ASUSTek       | P5KPL-AM                    | [b5bf9b7639](https://linux-hardware.org/?probe=b5bf9b7639) | Oct 21, 2023 |
| MACHINIST     | X99-RS9 V2.0                | [2fb0ec8fa2](https://linux-hardware.org/?probe=2fb0ec8fa2) | Oct 21, 2023 |
| HP            | 802F                        | [d01e0550a3](https://linux-hardware.org/?probe=d01e0550a3) | Oct 20, 2023 |
| Biostar       | B450MH                      | [cc72642215](https://linux-hardware.org/?probe=cc72642215) | Oct 20, 2023 |
| MSI           | G41TM-P31                   | [3ed69770a6](https://linux-hardware.org/?probe=3ed69770a6) | Oct 20, 2023 |
| ASUSTek       | P8H77-M PRO                 | [968efc7996](https://linux-hardware.org/?probe=968efc7996) | Oct 20, 2023 |
| Lenovo        | 30D0 NOK                    | [e67eff74dc](https://linux-hardware.org/?probe=e67eff74dc) | Oct 20, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [3fd9b0b53f](https://linux-hardware.org/?probe=3fd9b0b53f) | Oct 20, 2023 |
| Biostar       | TA970                       | [afb4cf630f](https://linux-hardware.org/?probe=afb4cf630f) | Oct 20, 2023 |
| ASUSTek       | M5A78L-M LE                 | [3f5646fdfb](https://linux-hardware.org/?probe=3f5646fdfb) | Oct 19, 2023 |
| Intel         | DH55HC AAE70933-505         | [f1bc373847](https://linux-hardware.org/?probe=f1bc373847) | Oct 19, 2023 |
| ASRock        | H510M-HVS                   | [0766c5afbd](https://linux-hardware.org/?probe=0766c5afbd) | Oct 19, 2023 |
| ASRock        | H110M-HDV R3.0              | [491538303f](https://linux-hardware.org/?probe=491538303f) | Oct 19, 2023 |
| ASRock        | A88M-G                      | [05d17c88b7](https://linux-hardware.org/?probe=05d17c88b7) | Oct 18, 2023 |
| Gigabyte      | Z370 HD3P-CF                | [0994d6d9a2](https://linux-hardware.org/?probe=0994d6d9a2) | Oct 18, 2023 |
| ASUSTek       | PRIME H510M-A               | [04e9833b48](https://linux-hardware.org/?probe=04e9833b48) | Oct 18, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [6e81d4f878](https://linux-hardware.org/?probe=6e81d4f878) | Oct 18, 2023 |
| Fujitsu       | D3603-A1 S26361-D3603-A1    | [793ba23be0](https://linux-hardware.org/?probe=793ba23be0) | Oct 18, 2023 |
| ASRock        | N68-VGS3 FX                 | [2a39f005cb](https://linux-hardware.org/?probe=2a39f005cb) | Oct 17, 2023 |
| Foxconn       | 2ABF                        | [5d936f030f](https://linux-hardware.org/?probe=5d936f030f) | Oct 17, 2023 |
| MSI           | MAG B460 TOMAHAWK           | [37b97d2dd2](https://linux-hardware.org/?probe=37b97d2dd2) | Oct 17, 2023 |
| HP            | 212B                        | [f3793f3e05](https://linux-hardware.org/?probe=f3793f3e05) | Oct 17, 2023 |
| Acer          | Veriton X2660G              | [d122988e18](https://linux-hardware.org/?probe=d122988e18) | Oct 17, 2023 |
| Acer          | EG31M P01-A0                | [1e500b6b4a](https://linux-hardware.org/?probe=1e500b6b4a) | Oct 17, 2023 |
| ASRock        | B460M Pro4                  | [bc01f51395](https://linux-hardware.org/?probe=bc01f51395) | Oct 17, 2023 |
| ASRock        | X470 Master SLI/ac          | [9258f94300](https://linux-hardware.org/?probe=9258f94300) | Oct 17, 2023 |
| Fujitsu Si... | D2312-A3 S26361-D2312-A3    | [eb657acc28](https://linux-hardware.org/?probe=eb657acc28) | Oct 16, 2023 |
| Acer          | Aspire GX-281               | [17fad55365](https://linux-hardware.org/?probe=17fad55365) | Oct 16, 2023 |
| Shenzhen M... | F7BSC                       | [8522bfdadd](https://linux-hardware.org/?probe=8522bfdadd) | Oct 16, 2023 |
| MSI           | Z97A GAMING 7               | [8af7152ba5](https://linux-hardware.org/?probe=8af7152ba5) | Oct 16, 2023 |
| ASRock        | N68-S3 FX                   | [b1a36d42aa](https://linux-hardware.org/?probe=b1a36d42aa) | Oct 16, 2023 |
| Gigabyte      | GA-E350N-USB3               | [62f5ab12ea](https://linux-hardware.org/?probe=62f5ab12ea) | Oct 15, 2023 |
| Shenzhen M... | F7BSC                       | [e41e92379e](https://linux-hardware.org/?probe=e41e92379e) | Oct 15, 2023 |
| HP            | 3397                        | [d45da2936e](https://linux-hardware.org/?probe=d45da2936e) | Oct 15, 2023 |
| Gigabyte      | GA-78LMT-S2 R2              | [038f59eb24](https://linux-hardware.org/?probe=038f59eb24) | Oct 15, 2023 |
| Intel         | DG41RQ AAE54511-203         | [64738e1724](https://linux-hardware.org/?probe=64738e1724) | Oct 15, 2023 |
| ACTION        | M5A78L-M lX V2              | [fe141a8a31](https://linux-hardware.org/?probe=fe141a8a31) | Oct 15, 2023 |
| Dell          | 0F5C5X A00                  | [78e96592c1](https://linux-hardware.org/?probe=78e96592c1) | Oct 14, 2023 |
| PCWare        | IPMH61R1                    | [145dc39d14](https://linux-hardware.org/?probe=145dc39d14) | Oct 14, 2023 |
| Gigabyte      | 970A-UD3P                   | [1d90e142fd](https://linux-hardware.org/?probe=1d90e142fd) | Oct 14, 2023 |
| ASUSTek       | P8Q77-M                     | [ed4ca29c66](https://linux-hardware.org/?probe=ed4ca29c66) | Oct 14, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [babe25d4ce](https://linux-hardware.org/?probe=babe25d4ce) | Oct 14, 2023 |
| ASRock        | A320M-HD                    | [2b45321310](https://linux-hardware.org/?probe=2b45321310) | Oct 13, 2023 |
| HP            | 1495                        | [e524318d58](https://linux-hardware.org/?probe=e524318d58) | Oct 13, 2023 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | [eed28015b6](https://linux-hardware.org/?probe=eed28015b6) | Oct 12, 2023 |
| Gigabyte      | B550M S2H                   | [fdcf79df44](https://linux-hardware.org/?probe=fdcf79df44) | Oct 12, 2023 |
| ASUSTek       | P5Q3 DELUXE                 | [29bb46e198](https://linux-hardware.org/?probe=29bb46e198) | Oct 12, 2023 |
| ASUSTek       | M2N68-AM SE2                | [398c921a7c](https://linux-hardware.org/?probe=398c921a7c) | Oct 11, 2023 |
| ASUSTek       | P5QL-ASUS-SE                | [6edb73b1b7](https://linux-hardware.org/?probe=6edb73b1b7) | Oct 11, 2023 |
| Lenovo        | 30D2 NOK                    | [e81b1e1e21](https://linux-hardware.org/?probe=e81b1e1e21) | Oct 10, 2023 |
| ASUSTek       | M5A88-M                     | [e73165d1b3](https://linux-hardware.org/?probe=e73165d1b3) | Oct 10, 2023 |
| MSI           | B450M BAZOOKA V2            | [3b598550c2](https://linux-hardware.org/?probe=3b598550c2) | Oct 10, 2023 |
| HP            | 158A                        | [9e43d14a8e](https://linux-hardware.org/?probe=9e43d14a8e) | Oct 10, 2023 |
| ASRock        | A320M-HDV R4.0              | [d1d30ae371](https://linux-hardware.org/?probe=d1d30ae371) | Oct 10, 2023 |
| Gigabyte      | H270-HD3-CF                 | [8c6732798b](https://linux-hardware.org/?probe=8c6732798b) | Oct 09, 2023 |
| Lenovo        | ThinkCentre M90p 5536W67    | [3e075f72d8](https://linux-hardware.org/?probe=3e075f72d8) | Oct 09, 2023 |
| ASUSTek       | PRIME B450M-K II            | [a3401cc125](https://linux-hardware.org/?probe=a3401cc125) | Oct 09, 2023 |
| Itautec       | SM 3321 SM-3321 Padrao 0... | [923cec3568](https://linux-hardware.org/?probe=923cec3568) | Oct 08, 2023 |
| Pegatron      | Benicia                     | [895d65cd9b](https://linux-hardware.org/?probe=895d65cd9b) | Oct 08, 2023 |
| ASUSTek       | P5KR                        | [641c856c71](https://linux-hardware.org/?probe=641c856c71) | Oct 08, 2023 |
| Biostar       | A320MH                      | [73bce2d7a8](https://linux-hardware.org/?probe=73bce2d7a8) | Oct 08, 2023 |
| Gigabyte      | A520M AORUS ELITE           | [bd385e5c4d](https://linux-hardware.org/?probe=bd385e5c4d) | Oct 08, 2023 |
| ASUSTek       | PRIME Z690-P D4             | [e7634ed6fe](https://linux-hardware.org/?probe=e7634ed6fe) | Oct 07, 2023 |
| HP            | 0A58h                       | [f55b84ff65](https://linux-hardware.org/?probe=f55b84ff65) | Oct 07, 2023 |
| Lenovo        | 3141 SDK0K17763 WIN 1801... | [da32e6e356](https://linux-hardware.org/?probe=da32e6e356) | Oct 07, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [0bf2deeb16](https://linux-hardware.org/?probe=0bf2deeb16) | Oct 07, 2023 |
| Dell          | 0M5DCD A00                  | [30d2522c95](https://linux-hardware.org/?probe=30d2522c95) | Oct 07, 2023 |
| Intel         | H61                         | [a37805d0d3](https://linux-hardware.org/?probe=a37805d0d3) | Oct 07, 2023 |
| ASRock        | N68C-GS FX                  | [cfafd2008d](https://linux-hardware.org/?probe=cfafd2008d) | Oct 07, 2023 |
| Biostar       | B760MZ-E PRO                | [ba4b48ac1b](https://linux-hardware.org/?probe=ba4b48ac1b) | Oct 07, 2023 |
| MSI           | 09AC                        | [f70ac0139f](https://linux-hardware.org/?probe=f70ac0139f) | Oct 07, 2023 |
| MSI           | MS-7235                     | [afb00bf553](https://linux-hardware.org/?probe=afb00bf553) | Oct 07, 2023 |
| Gigabyte      | GA-K8NE                     | [8cb50a99b7](https://linux-hardware.org/?probe=8cb50a99b7) | Oct 07, 2023 |
| Gigabyte      | F2A55M-DS2                  | [75d90cf644](https://linux-hardware.org/?probe=75d90cf644) | Oct 07, 2023 |
| AZW           | Green G4 10                 | [d8fb758dec](https://linux-hardware.org/?probe=d8fb758dec) | Oct 07, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [2ee56e1ee0](https://linux-hardware.org/?probe=2ee56e1ee0) | Oct 07, 2023 |
| MACHINIST     | E5-MR9A PRO V1.2            | [668d09e797](https://linux-hardware.org/?probe=668d09e797) | Oct 07, 2023 |
| Lenovo        | ThinkCentre xxx 7090A17     | [669bc2a016](https://linux-hardware.org/?probe=669bc2a016) | Oct 06, 2023 |
| ASUSTek       | M5A99X EVO                  | [6347be6a54](https://linux-hardware.org/?probe=6347be6a54) | Oct 06, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [bc448fbb82](https://linux-hardware.org/?probe=bc448fbb82) | Oct 05, 2023 |
| Pegatron      | Benicia                     | [b70dfb3fc8](https://linux-hardware.org/?probe=b70dfb3fc8) | Oct 05, 2023 |
| MSI           | B450-A PRO MAX              | [6e8b2e49f0](https://linux-hardware.org/?probe=6e8b2e49f0) | Oct 05, 2023 |
| ASUSTek       | M5A97 R2.0                  | [1220b29312](https://linux-hardware.org/?probe=1220b29312) | Oct 05, 2023 |
| ASRock        | B450 Pro4 R2.0              | [cef2fbcb68](https://linux-hardware.org/?probe=cef2fbcb68) | Oct 05, 2023 |
| HP            | 8433 11                     | [7540fc930b](https://linux-hardware.org/?probe=7540fc930b) | Oct 05, 2023 |
| eMachines     | EL1352                      | [741a66b428](https://linux-hardware.org/?probe=741a66b428) | Oct 05, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [377e8e1994](https://linux-hardware.org/?probe=377e8e1994) | Oct 05, 2023 |
| Dell          | 0G785M A00                  | [8edd52e89c](https://linux-hardware.org/?probe=8edd52e89c) | Oct 04, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | [a3ea9b4b56](https://linux-hardware.org/?probe=a3ea9b4b56) | Oct 04, 2023 |
| HP            | 3397                        | [e77e1b6391](https://linux-hardware.org/?probe=e77e1b6391) | Oct 04, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [a72a2ee89e](https://linux-hardware.org/?probe=a72a2ee89e) | Oct 04, 2023 |
| HP            | 1825                        | [d326bc59ff](https://linux-hardware.org/?probe=d326bc59ff) | Oct 04, 2023 |
| ECS           | H61H2-MV                    | [51ec04551f](https://linux-hardware.org/?probe=51ec04551f) | Oct 04, 2023 |
| Gigabyte      | F2A88X-D3H                  | [6ea97d511f](https://linux-hardware.org/?probe=6ea97d511f) | Oct 04, 2023 |
| Lenovo        | NOK                         | [dd6bffed79](https://linux-hardware.org/?probe=dd6bffed79) | Oct 04, 2023 |
| HP            | 3646h                       | [f39e9c8741](https://linux-hardware.org/?probe=f39e9c8741) | Oct 04, 2023 |
| MSI           | G31TM-P21                   | [84d68335c3](https://linux-hardware.org/?probe=84d68335c3) | Oct 03, 2023 |
| Intel         | JSL MRD                     | [5a4bfcaba3](https://linux-hardware.org/?probe=5a4bfcaba3) | Oct 03, 2023 |
| Intel         | DG41RQ AAE54511-202         | [5d2ec27525](https://linux-hardware.org/?probe=5d2ec27525) | Oct 03, 2023 |
| Lenovo        | ThinkCentre M58p 7484ANU    | [edc20561a3](https://linux-hardware.org/?probe=edc20561a3) | Oct 03, 2023 |
| Dell          | 0Y3R3K A03                  | [0675277f70](https://linux-hardware.org/?probe=0675277f70) | Oct 03, 2023 |
| HP            | 18E4                        | [6707337e0c](https://linux-hardware.org/?probe=6707337e0c) | Oct 03, 2023 |
| Dell          | 0GXM1W A00                  | [fe83d524fb](https://linux-hardware.org/?probe=fe83d524fb) | Oct 02, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [244c548d7e](https://linux-hardware.org/?probe=244c548d7e) | Oct 02, 2023 |
| MSI           | 970 GAMING                  | [c095e62997](https://linux-hardware.org/?probe=c095e62997) | Oct 02, 2023 |
| HP            | 8433 11                     | [0fcfc69a01](https://linux-hardware.org/?probe=0fcfc69a01) | Oct 02, 2023 |
| Biostar       | A960D+V2                    | [61b27d4d00](https://linux-hardware.org/?probe=61b27d4d00) | Oct 01, 2023 |
| HP            | 8298                        | [0f73d73d00](https://linux-hardware.org/?probe=0f73d73d00) | Oct 01, 2023 |
| MSI           | B450-A PRO MAX              | [546e058777](https://linux-hardware.org/?probe=546e058777) | Oct 01, 2023 |
| MSI           | B350M PRO-VD PLUS           | [a8c796cebf](https://linux-hardware.org/?probe=a8c796cebf) | Oct 01, 2023 |
| AZW           | MINI S 10                   | [13e3a733fd](https://linux-hardware.org/?probe=13e3a733fd) | Oct 01, 2023 |
| HP            | 0A50h                       | [e2082963e9](https://linux-hardware.org/?probe=e2082963e9) | Oct 01, 2023 |
| MSI           | Z370-A PRO                  | [7c1fdcfb70](https://linux-hardware.org/?probe=7c1fdcfb70) | Oct 01, 2023 |
| Gigabyte      | Z77X-UD5H                   | [def4633785](https://linux-hardware.org/?probe=def4633785) | Oct 01, 2023 |
| Gigabyte      | 970A-DS3P                   | [5d6115a057](https://linux-hardware.org/?probe=5d6115a057) | Oct 01, 2023 |
| ASUSTek       | B85M-G                      | [0166816d1b](https://linux-hardware.org/?probe=0166816d1b) | Oct 01, 2023 |
| ASRock        | A88M-G                      | [a918b08771](https://linux-hardware.org/?probe=a918b08771) | Sep 30, 2023 |
| Toshiba       | STI 009169                  | [0b76bae8f3](https://linux-hardware.org/?probe=0b76bae8f3) | Sep 30, 2023 |
| Lenovo        | ThinkCentre M55p 8811ZD4    | [710dea5f88](https://linux-hardware.org/?probe=710dea5f88) | Sep 30, 2023 |
| Gigabyte      | H61M-S1                     | [64e8a0bcc2](https://linux-hardware.org/?probe=64e8a0bcc2) | Sep 30, 2023 |
| ASUSTek       | H110M-R                     | [b8aadf6823](https://linux-hardware.org/?probe=b8aadf6823) | Sep 30, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [34e5bf82de](https://linux-hardware.org/?probe=34e5bf82de) | Sep 30, 2023 |
| ASUSTek       | P5B-E Plus                  | [78c413cac5](https://linux-hardware.org/?probe=78c413cac5) | Sep 30, 2023 |
| Gigabyte      | P31-ES3G                    | [bee14e504c](https://linux-hardware.org/?probe=bee14e504c) | Sep 30, 2023 |
| AZW           | MINI S 10                   | [e065b9c701](https://linux-hardware.org/?probe=e065b9c701) | Sep 30, 2023 |
| Dell          | 0Y958C A00                  | [95bf9d14db](https://linux-hardware.org/?probe=95bf9d14db) | Sep 30, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | [5705bf79ad](https://linux-hardware.org/?probe=5705bf79ad) | Sep 30, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | [c602f8fba9](https://linux-hardware.org/?probe=c602f8fba9) | Sep 29, 2023 |
| HP            | 3398                        | [13aa132a7d](https://linux-hardware.org/?probe=13aa132a7d) | Sep 29, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [d0fea1d86b](https://linux-hardware.org/?probe=d0fea1d86b) | Sep 29, 2023 |
| WesternDig... | BBC 0001                    | [b31e10d01b](https://linux-hardware.org/?probe=b31e10d01b) | Sep 29, 2023 |
| WesternDig... | BBC 0001                    | [ba340393f7](https://linux-hardware.org/?probe=ba340393f7) | Sep 29, 2023 |
| Intel         | H110D4-P1                   | [ccedaaab02](https://linux-hardware.org/?probe=ccedaaab02) | Sep 29, 2023 |
| HP            | 1589                        | [c42e75cdd8](https://linux-hardware.org/?probe=c42e75cdd8) | Sep 29, 2023 |
| Pegatron      | Benicia                     | [840b02e356](https://linux-hardware.org/?probe=840b02e356) | Sep 29, 2023 |
| ASUSTek       | PRIME B450M-A               | [6bce0e41d9](https://linux-hardware.org/?probe=6bce0e41d9) | Sep 28, 2023 |
| MSI           | B450M BAZOOKA V2            | [c815d636ce](https://linux-hardware.org/?probe=c815d636ce) | Sep 28, 2023 |
| Lenovo        | H410                        | [f49a6ce32f](https://linux-hardware.org/?probe=f49a6ce32f) | Sep 28, 2023 |
| ASUSTek       | M2N-E SLI                   | [2a5937c5e5](https://linux-hardware.org/?probe=2a5937c5e5) | Sep 28, 2023 |
| Unknown       | Unknown                     | [995b6fba4d](https://linux-hardware.org/?probe=995b6fba4d) | Sep 28, 2023 |
| Intel         | H61                         | [f41171114f](https://linux-hardware.org/?probe=f41171114f) | Sep 28, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [a1ef1eb6e6](https://linux-hardware.org/?probe=a1ef1eb6e6) | Sep 28, 2023 |
| MSI           | Z97-G45 GAMING              | [19c07d0fca](https://linux-hardware.org/?probe=19c07d0fca) | Sep 27, 2023 |
| ASUSTek       | PRIME B360M-A               | [7943462da1](https://linux-hardware.org/?probe=7943462da1) | Sep 27, 2023 |
| ASUSTek       | D700MD                      | [91740e63b9](https://linux-hardware.org/?probe=91740e63b9) | Sep 27, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [1d8c54163d](https://linux-hardware.org/?probe=1d8c54163d) | Sep 27, 2023 |
| Dell          | 00F82W A01                  | [ac93742033](https://linux-hardware.org/?probe=ac93742033) | Sep 27, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [9c9070da5f](https://linux-hardware.org/?probe=9c9070da5f) | Sep 26, 2023 |
| MSI           | B450M-A PRO MAX             | [41f2aab706](https://linux-hardware.org/?probe=41f2aab706) | Sep 26, 2023 |
| ASUSTek       | TUF B360-PRO GAMING WIFI    | [16c22d9ead](https://linux-hardware.org/?probe=16c22d9ead) | Sep 25, 2023 |
| Acer          | Aspire M5910                | [5b44d1de35](https://linux-hardware.org/?probe=5b44d1de35) | Sep 25, 2023 |
| Gigabyte      | GA-MA770T-UD3               | [85663cb9a6](https://linux-hardware.org/?probe=85663cb9a6) | Sep 25, 2023 |
| Dell          | 0773VG A02                  | [83390c3986](https://linux-hardware.org/?probe=83390c3986) | Sep 25, 2023 |
| Pegatron      | EVANS                       | [b9347254b0](https://linux-hardware.org/?probe=b9347254b0) | Sep 25, 2023 |
| ASRock        | X370 Pro4                   | [1939307392](https://linux-hardware.org/?probe=1939307392) | Sep 25, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [78eceb519c](https://linux-hardware.org/?probe=78eceb519c) | Sep 25, 2023 |
| ASRock        | FM2A85X Extreme4-M          | [bef6ef227b](https://linux-hardware.org/?probe=bef6ef227b) | Sep 25, 2023 |
| HP            | 3397                        | [cc6f1cc8ba](https://linux-hardware.org/?probe=cc6f1cc8ba) | Sep 24, 2023 |
| Biostar       | B550MH                      | [4ef9bbad17](https://linux-hardware.org/?probe=4ef9bbad17) | Sep 24, 2023 |
| MSI           | 990FXA-GD80                 | [0648a13752](https://linux-hardware.org/?probe=0648a13752) | Sep 24, 2023 |
| Gigabyte      | X299 AORUS Gaming-CF        | [4c6071b20c](https://linux-hardware.org/?probe=4c6071b20c) | Sep 24, 2023 |
| Lenovo        | ThinkCentre A70z 0401B7P    | [21a635940f](https://linux-hardware.org/?probe=21a635940f) | Sep 24, 2023 |
| ASUSTek       | P5G41T-M LX                 | [a1ced3b0bd](https://linux-hardware.org/?probe=a1ced3b0bd) | Sep 24, 2023 |
| MSI           | H61MA-E35                   | [888c822527](https://linux-hardware.org/?probe=888c822527) | Sep 24, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [c0e3bef058](https://linux-hardware.org/?probe=c0e3bef058) | Sep 24, 2023 |
| PCWare        | APM-A320G                   | [64080404a6](https://linux-hardware.org/?probe=64080404a6) | Sep 24, 2023 |
| Gigabyte      | 945GCM-S2C                  | [9f17460970](https://linux-hardware.org/?probe=9f17460970) | Sep 24, 2023 |
| Dell          | 02YRK5 A02                  | [b738e4741b](https://linux-hardware.org/?probe=b738e4741b) | Sep 23, 2023 |
| ASUSTek       | Z97-C                       | [e4c1f075b9](https://linux-hardware.org/?probe=e4c1f075b9) | Sep 23, 2023 |
| ASUSTek       | A88XM-A                     | [c2cb8052f9](https://linux-hardware.org/?probe=c2cb8052f9) | Sep 23, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [46a99bb50a](https://linux-hardware.org/?probe=46a99bb50a) | Sep 23, 2023 |
| Gigabyte      | Z68X-UD3H-B3                | [92e5dde8b3](https://linux-hardware.org/?probe=92e5dde8b3) | Sep 23, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS        | [5783da9442](https://linux-hardware.org/?probe=5783da9442) | Sep 23, 2023 |
| Dell          | 0WR7PY A01                  | [64e4102978](https://linux-hardware.org/?probe=64e4102978) | Sep 23, 2023 |
| Shuttle       | XS36V                       | [dbcb5658e4](https://linux-hardware.org/?probe=dbcb5658e4) | Sep 23, 2023 |
| Gigabyte      | 990FXA-UD3 R5               | [2a62bbc302](https://linux-hardware.org/?probe=2a62bbc302) | Sep 22, 2023 |
| ASUSTek       | P7P55-M                     | [f5b912e122](https://linux-hardware.org/?probe=f5b912e122) | Sep 22, 2023 |
| Lenovo        | ThinkCentre M58p 6137B28    | [25c3f2b6f8](https://linux-hardware.org/?probe=25c3f2b6f8) | Sep 22, 2023 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | [43d9a8a827](https://linux-hardware.org/?probe=43d9a8a827) | Sep 22, 2023 |
| ASUSTek       | P5K                         | [4d67ad50cf](https://linux-hardware.org/?probe=4d67ad50cf) | Sep 22, 2023 |
| Biostar       | A68N-2100                   | [c035c2e73b](https://linux-hardware.org/?probe=c035c2e73b) | Sep 22, 2023 |
| HP            | 8643 SMVB                   | [913927a01a](https://linux-hardware.org/?probe=913927a01a) | Sep 22, 2023 |
| ASUSTek       | M5A78L-M LX3                | [80928b2dc9](https://linux-hardware.org/?probe=80928b2dc9) | Sep 21, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [3d3b14f0f9](https://linux-hardware.org/?probe=3d3b14f0f9) | Sep 21, 2023 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [6c9da4e4fa](https://linux-hardware.org/?probe=6c9da4e4fa) | Sep 21, 2023 |
| Acer          | Revo RN86                   | [315559ee42](https://linux-hardware.org/?probe=315559ee42) | Sep 21, 2023 |
| Positivo      | POS-AG31AP                  | [2e2072e3ca](https://linux-hardware.org/?probe=2e2072e3ca) | Sep 21, 2023 |
| Megaware      | MW-HDC-M 02/24/2012 - ME... | [d3c9063140](https://linux-hardware.org/?probe=d3c9063140) | Sep 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [4269a04f31](https://linux-hardware.org/?probe=4269a04f31) | Sep 21, 2023 |
| Gigabyte      | B450 AORUS M                | [e2dda8ebb1](https://linux-hardware.org/?probe=e2dda8ebb1) | Sep 21, 2023 |
| Dell          | 0KRC95 A00                  | [61ae2b85c5](https://linux-hardware.org/?probe=61ae2b85c5) | Sep 21, 2023 |
| Gigabyte      | B560M DS3H V2               | [182384fdaa](https://linux-hardware.org/?probe=182384fdaa) | Sep 20, 2023 |
| Unknown       | Unknown                     | [742bffa5fe](https://linux-hardware.org/?probe=742bffa5fe) | Sep 20, 2023 |
| MSI           | Indio                       | [330a2c9640](https://linux-hardware.org/?probe=330a2c9640) | Sep 20, 2023 |
| Intel         | DN2820FYK H24582-204        | [bec0346d1d](https://linux-hardware.org/?probe=bec0346d1d) | Sep 20, 2023 |
| Gigabyte      | B760M GAMING X AX DDR4      | [07f641459d](https://linux-hardware.org/?probe=07f641459d) | Sep 20, 2023 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | [c3525c54c3](https://linux-hardware.org/?probe=c3525c54c3) | Sep 20, 2023 |
| ASUSTek       | B150M-C D3                  | [179a66ec43](https://linux-hardware.org/?probe=179a66ec43) | Sep 19, 2023 |
| HP            | 83E1                        | [c00bed1d53](https://linux-hardware.org/?probe=c00bed1d53) | Sep 19, 2023 |
| Biostar       | B550GTQ                     | [5478c7bc91](https://linux-hardware.org/?probe=5478c7bc91) | Sep 19, 2023 |
| ASUSTek       | P9X79                       | [d663285ae0](https://linux-hardware.org/?probe=d663285ae0) | Sep 19, 2023 |
| Pegatron      | 2AB5                        | [b21eddb040](https://linux-hardware.org/?probe=b21eddb040) | Sep 19, 2023 |
| Foxconn       | G31MXP FAB:1.1              | [5c72d9c9a4](https://linux-hardware.org/?probe=5c72d9c9a4) | Sep 19, 2023 |
| HP            | 8298                        | [006592d87f](https://linux-hardware.org/?probe=006592d87f) | Sep 19, 2023 |
| ASUSTek       | M5A78L-M LX3                | [25d66d7f8a](https://linux-hardware.org/?probe=25d66d7f8a) | Sep 19, 2023 |
| Pegatron      | 2AB5                        | [6f4fafb23f](https://linux-hardware.org/?probe=6f4fafb23f) | Sep 19, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [f40bb3790e](https://linux-hardware.org/?probe=f40bb3790e) | Sep 18, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [0a5f29963e](https://linux-hardware.org/?probe=0a5f29963e) | Sep 18, 2023 |
| Gigabyte      | B85M-D3H                    | [7b51f6f455](https://linux-hardware.org/?probe=7b51f6f455) | Sep 18, 2023 |
| ASUSTek       | A88XM-PLUS                  | [ab79a26993](https://linux-hardware.org/?probe=ab79a26993) | Sep 18, 2023 |
| ASUSTek       | PRIME H270M-PLUS            | [fa9b30f699](https://linux-hardware.org/?probe=fa9b30f699) | Sep 18, 2023 |
| ASUSTek       | PRIME A320M-K               | [9c94944d56](https://linux-hardware.org/?probe=9c94944d56) | Sep 18, 2023 |
| ASUSTek       | P5GC-MX/1333                | [232bd09926](https://linux-hardware.org/?probe=232bd09926) | Sep 17, 2023 |
| Dell          | 0M863N A01                  | [ef0a92ec76](https://linux-hardware.org/?probe=ef0a92ec76) | Sep 17, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [e73adff0b5](https://linux-hardware.org/?probe=e73adff0b5) | Sep 17, 2023 |
| MSI           | B450M MORTAR MAX            | [beaa4e5554](https://linux-hardware.org/?probe=beaa4e5554) | Sep 17, 2023 |
| Gigabyte      | A520M H                     | [24efefc447](https://linux-hardware.org/?probe=24efefc447) | Sep 17, 2023 |
| Dell          | 0KWVT8 A03                  | [cd0090bea7](https://linux-hardware.org/?probe=cd0090bea7) | Sep 16, 2023 |
| Intel         | H310                        | [7bbb817440](https://linux-hardware.org/?probe=7bbb817440) | Sep 16, 2023 |
| ASRock        | AB350 Pro4                  | [700c5f2d7d](https://linux-hardware.org/?probe=700c5f2d7d) | Sep 16, 2023 |
| Gigabyte      | H55M-UD2H                   | [a95113f868](https://linux-hardware.org/?probe=a95113f868) | Sep 16, 2023 |
| Intel         | DX79SI AAG28808-602         | [2ccc7fc308](https://linux-hardware.org/?probe=2ccc7fc308) | Sep 16, 2023 |
| ASRock        | 960GC-GS FX                 | [513b6982f2](https://linux-hardware.org/?probe=513b6982f2) | Sep 16, 2023 |
| ASUSTek       | PRIME A320M-K               | [bef465f035](https://linux-hardware.org/?probe=bef465f035) | Sep 16, 2023 |
| Intel         | DH61CR AAG14064-204         | [e28e555058](https://linux-hardware.org/?probe=e28e555058) | Sep 16, 2023 |
| Lenovo        | ThinkCentre M58 7360BB6     | [cb32849dcc](https://linux-hardware.org/?probe=cb32849dcc) | Sep 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [18820f4980](https://linux-hardware.org/?probe=18820f4980) | Sep 15, 2023 |
| HP            | 339A                        | [5808e19d94](https://linux-hardware.org/?probe=5808e19d94) | Sep 15, 2023 |
| Gigabyte      | P35-DS3                     | [7cf209e4c1](https://linux-hardware.org/?probe=7cf209e4c1) | Sep 15, 2023 |
| MSI           | H310M PRO-VDH               | [100f789658](https://linux-hardware.org/?probe=100f789658) | Sep 15, 2023 |
| HP            | 18E7                        | [e5b07fa901](https://linux-hardware.org/?probe=e5b07fa901) | Sep 15, 2023 |
| Gigabyte      | B450M DS3H-CF               | [b4dcc89eae](https://linux-hardware.org/?probe=b4dcc89eae) | Sep 15, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [dd369f3c60](https://linux-hardware.org/?probe=dd369f3c60) | Sep 15, 2023 |
| ASRock        | H570M Pro4                  | [22dd926ff4](https://linux-hardware.org/?probe=22dd926ff4) | Sep 15, 2023 |
| Dell          | 073MMW A03                  | [b0fc15849b](https://linux-hardware.org/?probe=b0fc15849b) | Sep 15, 2023 |
| Dell          | 048DY8 A00                  | [3cc67a5e62](https://linux-hardware.org/?probe=3cc67a5e62) | Sep 15, 2023 |
| Gigabyte      | A55M-DS2                    | [6bc7d0b74c](https://linux-hardware.org/?probe=6bc7d0b74c) | Sep 15, 2023 |
| Foxconn       | 45GM/45CM/45CM-S            | [135712cd9e](https://linux-hardware.org/?probe=135712cd9e) | Sep 14, 2023 |
| Gigabyte      | H61M-S1                     | [40ffb44424](https://linux-hardware.org/?probe=40ffb44424) | Sep 14, 2023 |
| Gigabyte      | B450 AORUS M                | [9b3fc9218b](https://linux-hardware.org/?probe=9b3fc9218b) | Sep 14, 2023 |
| Intel         | H81                         | [34f1a336e3](https://linux-hardware.org/?probe=34f1a336e3) | Sep 14, 2023 |
| Gigabyte      | Z97X-SOC-CF                 | [9c86fc8235](https://linux-hardware.org/?probe=9c86fc8235) | Sep 14, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [33b3749fc5](https://linux-hardware.org/?probe=33b3749fc5) | Sep 14, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [9fde2c205d](https://linux-hardware.org/?probe=9fde2c205d) | Sep 14, 2023 |
| BESSTAR Te... | UM700                       | [e839857a74](https://linux-hardware.org/?probe=e839857a74) | Sep 14, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | [b8e5214540](https://linux-hardware.org/?probe=b8e5214540) | Sep 14, 2023 |
| ASUSTek       | NAGAMI2                     | [c0e4ce344f](https://linux-hardware.org/?probe=c0e4ce344f) | Sep 14, 2023 |
| MSI           | B85M-E45                    | [d454b67226](https://linux-hardware.org/?probe=d454b67226) | Sep 13, 2023 |
| Packard Be... | MCP73                       | [b47efcac04](https://linux-hardware.org/?probe=b47efcac04) | Sep 13, 2023 |
| Acer          | Veriton N4640G              | [df814b2a84](https://linux-hardware.org/?probe=df814b2a84) | Sep 13, 2023 |
| ASUSTek       | P5N72-T PREMIUM             | [e5afd4ceda](https://linux-hardware.org/?probe=e5afd4ceda) | Sep 13, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [0c8393b2d4](https://linux-hardware.org/?probe=0c8393b2d4) | Sep 13, 2023 |
| HP            | 339A                        | [1b8a467d98](https://linux-hardware.org/?probe=1b8a467d98) | Sep 13, 2023 |
| Google        | Panther                     | [4bfbab5ff5](https://linux-hardware.org/?probe=4bfbab5ff5) | Sep 13, 2023 |
| Pegatron      | 2AC3                        | [4cee44e8ac](https://linux-hardware.org/?probe=4cee44e8ac) | Sep 13, 2023 |
| ASUSTek       | PRIME B550M-K               | [3b15d88a26](https://linux-hardware.org/?probe=3b15d88a26) | Sep 13, 2023 |
| MSI           | A88XM GAMING                | [0b0a88f781](https://linux-hardware.org/?probe=0b0a88f781) | Sep 13, 2023 |
| Pegatron      | 2ACF                        | [2b7e16f244](https://linux-hardware.org/?probe=2b7e16f244) | Sep 12, 2023 |
| MSI           | Z170A GAMING M9 ACK         | [49cc8ea6d2](https://linux-hardware.org/?probe=49cc8ea6d2) | Sep 12, 2023 |
| MSI           | B450M PRO-VDH               | [c06182cc86](https://linux-hardware.org/?probe=c06182cc86) | Sep 12, 2023 |
| Intel         | H61                         | [fec08a2214](https://linux-hardware.org/?probe=fec08a2214) | Sep 12, 2023 |
| ASRock        | AB350M Pro4                 | [dbbb941ae1](https://linux-hardware.org/?probe=dbbb941ae1) | Sep 12, 2023 |
| ASUSTek       | PRIME B550-PLUS AC-HES      | [243a7e547a](https://linux-hardware.org/?probe=243a7e547a) | Sep 12, 2023 |
| Dell          | 0G254H A00                  | [b41d69b7e2](https://linux-hardware.org/?probe=b41d69b7e2) | Sep 12, 2023 |
| HP            | 82A1                        | [8a68160c22](https://linux-hardware.org/?probe=8a68160c22) | Sep 12, 2023 |
| ASUSTek       | P8Z77-V LE PLUS             | [ef6f0ae453](https://linux-hardware.org/?probe=ef6f0ae453) | Sep 11, 2023 |
| Dell          | 0G3HR7 A00                  | [ae2dfec1af](https://linux-hardware.org/?probe=ae2dfec1af) | Sep 11, 2023 |
| Dell          | OptiPlex 3020               | [12428f0a31](https://linux-hardware.org/?probe=12428f0a31) | Sep 11, 2023 |
| Unknown       | Unknown                     | [7c32a84014](https://linux-hardware.org/?probe=7c32a84014) | Sep 11, 2023 |
| Intel         | JSL MRD                     | [b360f71c3d](https://linux-hardware.org/?probe=b360f71c3d) | Sep 11, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [9c4e42b171](https://linux-hardware.org/?probe=9c4e42b171) | Sep 11, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [3716cce5f9](https://linux-hardware.org/?probe=3716cce5f9) | Sep 11, 2023 |
| HP            | 304Ah                       | [fe71b825fd](https://linux-hardware.org/?probe=fe71b825fd) | Sep 11, 2023 |
| Intel         | H81 V2.3                    | [0673e1f5ed](https://linux-hardware.org/?probe=0673e1f5ed) | Sep 11, 2023 |
| ASUSTek       | P5KPL-AM                    | [3f55a69040](https://linux-hardware.org/?probe=3f55a69040) | Sep 11, 2023 |
| Dell          | 088DT1 A00                  | [08eff7732c](https://linux-hardware.org/?probe=08eff7732c) | Sep 11, 2023 |
| Philco        | DTC-A55                     | [30cdd25bb0](https://linux-hardware.org/?probe=30cdd25bb0) | Sep 11, 2023 |
| ASUSTek       | PRIME H410M-R               | [962fd46c5c](https://linux-hardware.org/?probe=962fd46c5c) | Sep 11, 2023 |
| MSI           | PRO Z690-A                  | [2c892b26d1](https://linux-hardware.org/?probe=2c892b26d1) | Sep 11, 2023 |
| ECS           | A960M-M3                    | [70ee5683a4](https://linux-hardware.org/?probe=70ee5683a4) | Sep 11, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | [36feb258a8](https://linux-hardware.org/?probe=36feb258a8) | Sep 10, 2023 |
| ASUSTek       | PRIME Z390M-PLUS            | [515cb66794](https://linux-hardware.org/?probe=515cb66794) | Sep 10, 2023 |
| Gigabyte      | H110M-S2PT-CF               | [83ff674ae7](https://linux-hardware.org/?probe=83ff674ae7) | Sep 10, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [5cb754a533](https://linux-hardware.org/?probe=5cb754a533) | Sep 10, 2023 |
| Daten Tecn... | DA75PRO                     | [343cbab6e9](https://linux-hardware.org/?probe=343cbab6e9) | Sep 10, 2023 |
| ASRock        | A300M-STX                   | [923e3060e8](https://linux-hardware.org/?probe=923e3060e8) | Sep 10, 2023 |
| Dell          | 0782GW A00                  | [e763eb02b7](https://linux-hardware.org/?probe=e763eb02b7) | Sep 10, 2023 |
| Foxconn       | H61MXL/H61MXL-K             | [b5b49fefb3](https://linux-hardware.org/?probe=b5b49fefb3) | Sep 09, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [91b6565880](https://linux-hardware.org/?probe=91b6565880) | Sep 09, 2023 |
| HP            | 8266                        | [fed6cc89fe](https://linux-hardware.org/?probe=fed6cc89fe) | Sep 09, 2023 |
| ASUSTek       | H110M-R                     | [043800bfdc](https://linux-hardware.org/?probe=043800bfdc) | Sep 09, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [8723b09478](https://linux-hardware.org/?probe=8723b09478) | Sep 09, 2023 |
| ASUSTek       | P10S-C Series               | [67829cd702](https://linux-hardware.org/?probe=67829cd702) | Sep 09, 2023 |
| ASRock        | FM2A68M-HD+                 | [a08c0789c1](https://linux-hardware.org/?probe=a08c0789c1) | Sep 09, 2023 |
| Lenovo        | Annapurna CRB NOK           | [dc4bc20437](https://linux-hardware.org/?probe=dc4bc20437) | Sep 09, 2023 |
| ASUSTek       | P8H61-M LE/CSM R2.0         | [59ac0cb01a](https://linux-hardware.org/?probe=59ac0cb01a) | Sep 09, 2023 |
| Dell          | 0WK833                      | [5ec8a9e552](https://linux-hardware.org/?probe=5ec8a9e552) | Sep 09, 2023 |
| Acer          | EQ45LM                      | [015ea66c32](https://linux-hardware.org/?probe=015ea66c32) | Sep 09, 2023 |
| Dell          | 0YJPT1 A00                  | [b16e6f8c25](https://linux-hardware.org/?probe=b16e6f8c25) | Sep 08, 2023 |
| MSI           | H61MA-E35                   | [e64c5d24b0](https://linux-hardware.org/?probe=e64c5d24b0) | Sep 08, 2023 |
| Dell          | 0J37VM A01                  | [cfd16871a7](https://linux-hardware.org/?probe=cfd16871a7) | Sep 08, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [c06ee9858a](https://linux-hardware.org/?probe=c06ee9858a) | Sep 08, 2023 |
| Intel         | H81                         | [52fa5b7a15](https://linux-hardware.org/?probe=52fa5b7a15) | Sep 08, 2023 |
| ASUSTek       | PRIME B450M-A               | [0db457cc0b](https://linux-hardware.org/?probe=0db457cc0b) | Sep 08, 2023 |
| MSI           | 760GA-P43                   | [b067d69499](https://linux-hardware.org/?probe=b067d69499) | Sep 08, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [7a0e6bd16c](https://linux-hardware.org/?probe=7a0e6bd16c) | Sep 07, 2023 |
| Medion        | H110H4-CM2                  | [184f133a7d](https://linux-hardware.org/?probe=184f133a7d) | Sep 07, 2023 |
| ASRock        | H310CM-HDV                  | [7aa11cd98f](https://linux-hardware.org/?probe=7aa11cd98f) | Sep 07, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [7bdd695dc3](https://linux-hardware.org/?probe=7bdd695dc3) | Sep 07, 2023 |
| ASUSTek       | P8H77-V LE                  | [38ebaae5c3](https://linux-hardware.org/?probe=38ebaae5c3) | Sep 07, 2023 |
| Gigabyte      | H610M S2 V2 DDR4            | [7323821425](https://linux-hardware.org/?probe=7323821425) | Sep 07, 2023 |
| Gigabyte      | Z87X-UD3H-CF                | [43f205483a](https://linux-hardware.org/?probe=43f205483a) | Sep 07, 2023 |
| ASRock        | A68M-ITX                    | [f995094d6b](https://linux-hardware.org/?probe=f995094d6b) | Sep 07, 2023 |
| ASUSTek       | ProArt B550-CREATOR         | [5b276b13a8](https://linux-hardware.org/?probe=5b276b13a8) | Sep 07, 2023 |
| ASUSTek       | PRIME H510M-E               | [0be77d9ece](https://linux-hardware.org/?probe=0be77d9ece) | Sep 07, 2023 |
| Toshiba       | STI 006998G                 | [d34aadcc92](https://linux-hardware.org/?probe=d34aadcc92) | Sep 07, 2023 |
| ASUSTek       | ROG STRIX B560-E GAMING ... | [498958a11d](https://linux-hardware.org/?probe=498958a11d) | Sep 07, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [96d3b5db5c](https://linux-hardware.org/?probe=96d3b5db5c) | Sep 07, 2023 |
| ASUSTek       | PRIME Z390M-PLUS            | [f98e7f20ca](https://linux-hardware.org/?probe=f98e7f20ca) | Sep 06, 2023 |
| HC Technol... | HCAR5000-MI                 | [3f98176bb7](https://linux-hardware.org/?probe=3f98176bb7) | Sep 06, 2023 |
| Gigabyte      | H61M-S2PV                   | [29d9f2566a](https://linux-hardware.org/?probe=29d9f2566a) | Sep 06, 2023 |
| ASUSTek       | Z97-K                       | [849ecb3c82](https://linux-hardware.org/?probe=849ecb3c82) | Sep 06, 2023 |
| ASRock        | Z68 Pro3                    | [757ebbe056](https://linux-hardware.org/?probe=757ebbe056) | Sep 06, 2023 |
| Acer          | EQ45LM                      | [22af76a0b6](https://linux-hardware.org/?probe=22af76a0b6) | Sep 06, 2023 |
| MSI           | PRO B650-P WIFI             | [507d1bd39c](https://linux-hardware.org/?probe=507d1bd39c) | Sep 06, 2023 |
| Gigabyte      | B75M-D3H                    | [2285c5c493](https://linux-hardware.org/?probe=2285c5c493) | Sep 06, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | [a738df6114](https://linux-hardware.org/?probe=a738df6114) | Sep 06, 2023 |
| Intel         | DQ67SW AAG12527-310         | [774ca51623](https://linux-hardware.org/?probe=774ca51623) | Sep 06, 2023 |
| MSI           | Boston                      | [f4749c6ef7](https://linux-hardware.org/?probe=f4749c6ef7) | Sep 06, 2023 |
| Gigabyte      | A320M-S2H-CF                | [03e260aff4](https://linux-hardware.org/?probe=03e260aff4) | Sep 06, 2023 |
| ASRock        | H77 Pro4/MVP                | [9e650e7107](https://linux-hardware.org/?probe=9e650e7107) | Sep 06, 2023 |
| Lenovo        | IdeaCentre K330B            | [a53977eb83](https://linux-hardware.org/?probe=a53977eb83) | Sep 06, 2023 |
| Lenovo        | H420                        | [f84aae6411](https://linux-hardware.org/?probe=f84aae6411) | Sep 06, 2023 |
| Dell          | 0PC5F7 A00                  | [9ffb575d81](https://linux-hardware.org/?probe=9ffb575d81) | Sep 06, 2023 |
| Shenzhen M... | F7BFD                       | [3f1c2a5cfa](https://linux-hardware.org/?probe=3f1c2a5cfa) | Sep 06, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [c43f7a6e53](https://linux-hardware.org/?probe=c43f7a6e53) | Sep 06, 2023 |
| Lenovo        | SDK0E50510 WIN              | [4e04252ac1](https://linux-hardware.org/?probe=4e04252ac1) | Sep 06, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [5ba13c092c](https://linux-hardware.org/?probe=5ba13c092c) | Sep 06, 2023 |
| Dell          | 0CU409                      | [f5ae8200cf](https://linux-hardware.org/?probe=f5ae8200cf) | Sep 06, 2023 |
| ASUSTek       | PRIME B450M-A II            | [07f51e668b](https://linux-hardware.org/?probe=07f51e668b) | Sep 06, 2023 |
| ASRock        | B550M Pro4                  | [afba6fc1eb](https://linux-hardware.org/?probe=afba6fc1eb) | Sep 06, 2023 |
| Unknown       | HX90                        | [928ebd5aa7](https://linux-hardware.org/?probe=928ebd5aa7) | Sep 06, 2023 |
| HP            | 0B54h D                     | [978ff127e9](https://linux-hardware.org/?probe=978ff127e9) | Sep 05, 2023 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | [4a055a6f9c](https://linux-hardware.org/?probe=4a055a6f9c) | Sep 05, 2023 |
| MSI           | H270 GAMING M3              | [1c93682de6](https://linux-hardware.org/?probe=1c93682de6) | Sep 05, 2023 |
| ASRock        | 970 Pro3 R2.0               | [01ede034b7](https://linux-hardware.org/?probe=01ede034b7) | Sep 05, 2023 |
| Intel         | H61                         | [d749d1595f](https://linux-hardware.org/?probe=d749d1595f) | Sep 05, 2023 |
| Dell          | 0T1D10 A01                  | [97ac9f9de8](https://linux-hardware.org/?probe=97ac9f9de8) | Sep 05, 2023 |
| ASRock        | H470M-STX                   | [97e43e20d7](https://linux-hardware.org/?probe=97e43e20d7) | Sep 05, 2023 |
| HP            | 0B4Ch D                     | [25b4eff820](https://linux-hardware.org/?probe=25b4eff820) | Sep 05, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | [4823d1487d](https://linux-hardware.org/?probe=4823d1487d) | Sep 05, 2023 |
| ASRock        | E35LM1                      | [663d9ac1e1](https://linux-hardware.org/?probe=663d9ac1e1) | Sep 04, 2023 |
| Lenovo        | Dory CRB                    | [4c136b6049](https://linux-hardware.org/?probe=4c136b6049) | Sep 04, 2023 |
| Gigabyte      | H55M-S2HP                   | [f2ac0f8904](https://linux-hardware.org/?probe=f2ac0f8904) | Sep 04, 2023 |
| ASRock        | A55M-HVS                    | [eaa27d1ba6](https://linux-hardware.org/?probe=eaa27d1ba6) | Sep 04, 2023 |
| Fujitsu       | D2990-A3 S26361-D2990-A3    | [59b9a21678](https://linux-hardware.org/?probe=59b9a21678) | Sep 04, 2023 |
| ASRock        | X570M Pro4                  | [46627e6392](https://linux-hardware.org/?probe=46627e6392) | Sep 04, 2023 |
| ASUSTek       | P5P43TD/USB3                | [619032e1d0](https://linux-hardware.org/?probe=619032e1d0) | Sep 04, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [c4334a53b6](https://linux-hardware.org/?probe=c4334a53b6) | Sep 04, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [66dedbf64b](https://linux-hardware.org/?probe=66dedbf64b) | Sep 04, 2023 |
| Dell          | 0J8G6F A03                  | [490dd7a710](https://linux-hardware.org/?probe=490dd7a710) | Sep 04, 2023 |
| ASRock        | B460M-HDV                   | [2380eeae30](https://linux-hardware.org/?probe=2380eeae30) | Sep 04, 2023 |
| ASRock        | N68-S3 FX                   | [2b503dd2b6](https://linux-hardware.org/?probe=2b503dd2b6) | Sep 04, 2023 |
| HP            | 8055                        | [2ed2e99af3](https://linux-hardware.org/?probe=2ed2e99af3) | Sep 04, 2023 |
| ASRock        | B450M-HDV R4.0              | [b87e106b6b](https://linux-hardware.org/?probe=b87e106b6b) | Sep 04, 2023 |
| Dell          | 06D7TR A00                  | [ce82ba5660](https://linux-hardware.org/?probe=ce82ba5660) | Sep 04, 2023 |
| ASRock        | NF6-GLAN                    | [80d9233886](https://linux-hardware.org/?probe=80d9233886) | Sep 04, 2023 |
| Gigabyte      | EP31-DS3L                   | [bce72e53fa](https://linux-hardware.org/?probe=bce72e53fa) | Sep 04, 2023 |
| Gigabyte      | H310M S2H x.x               | [7c39e7227e](https://linux-hardware.org/?probe=7c39e7227e) | Sep 04, 2023 |
| MSI           | H61M-P20                    | [cdf64232fc](https://linux-hardware.org/?probe=cdf64232fc) | Sep 04, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [dcb565d513](https://linux-hardware.org/?probe=dcb565d513) | Sep 04, 2023 |
| HP            | 8526 MVB, A                 | [3133ab688e](https://linux-hardware.org/?probe=3133ab688e) | Sep 04, 2023 |
| Lenovo        | ThinkCentre A58 77057FG     | [b96c23b77b](https://linux-hardware.org/?probe=b96c23b77b) | Sep 04, 2023 |
| Intel         | DG41RQ AAE54511-203         | [46aeab1365](https://linux-hardware.org/?probe=46aeab1365) | Sep 04, 2023 |
| OEM           | Intel H81                   | [649a092684](https://linux-hardware.org/?probe=649a092684) | Sep 04, 2023 |
| ASRock        | 960GM-VGS3 FX               | [c3059a2ebc](https://linux-hardware.org/?probe=c3059a2ebc) | Sep 04, 2023 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [2ba34b459a](https://linux-hardware.org/?probe=2ba34b459a) | Sep 04, 2023 |
| MSI           | B360M MORTAR                | [d023a05e0b](https://linux-hardware.org/?probe=d023a05e0b) | Sep 04, 2023 |
| AZW           | MINI S 10                   | [54967a6b36](https://linux-hardware.org/?probe=54967a6b36) | Sep 04, 2023 |
| MSI           | PRO Z690-A DDR4             | [09e7a8c91b](https://linux-hardware.org/?probe=09e7a8c91b) | Sep 04, 2023 |
| ASRock        | H510M-HDV R2.0              | [27684bd06d](https://linux-hardware.org/?probe=27684bd06d) | Sep 04, 2023 |
| ASUSTek       | PRIME B250M-A               | [02160fded0](https://linux-hardware.org/?probe=02160fded0) | Sep 04, 2023 |
| Gigabyte      | H87-D3H-CF                  | [9918661e50](https://linux-hardware.org/?probe=9918661e50) | Sep 04, 2023 |
| Fujitsu       | D3603-A1 S26361-D3603-A1    | [caa794eff8](https://linux-hardware.org/?probe=caa794eff8) | Sep 04, 2023 |
| Foxconn       | G31MX Series                | [4b4c5fb5f8](https://linux-hardware.org/?probe=4b4c5fb5f8) | Sep 04, 2023 |
| Dell          | 0GWHMW A00                  | [b02b2cb5f0](https://linux-hardware.org/?probe=b02b2cb5f0) | Sep 04, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [08a80ee482](https://linux-hardware.org/?probe=08a80ee482) | Sep 04, 2023 |
| ASUSTek       | PRIME X570-P                | [922ff6eddb](https://linux-hardware.org/?probe=922ff6eddb) | Sep 04, 2023 |
| Lenovo        | SHARKBAY NOK                | [1cc4b106a4](https://linux-hardware.org/?probe=1cc4b106a4) | Sep 04, 2023 |
| Gigabyte      | H510M H                     | [f235f2e7ef](https://linux-hardware.org/?probe=f235f2e7ef) | Sep 04, 2023 |
| Gigabyte      | H510M S2H                   | [82f3e710d9](https://linux-hardware.org/?probe=82f3e710d9) | Sep 04, 2023 |
| Gigabyte      | A320M-H-CF                  | [8d171f78bf](https://linux-hardware.org/?probe=8d171f78bf) | Sep 04, 2023 |
| ASUSTek       | PRIME B550M-A AC            | [6ca26976b6](https://linux-hardware.org/?probe=6ca26976b6) | Sep 04, 2023 |
| MSI           | B360M MORTAR ILYA MUROME... | [0899e4058a](https://linux-hardware.org/?probe=0899e4058a) | Sep 04, 2023 |
| ASUSTek       | Maximus VIII RANGER         | [0faa734044](https://linux-hardware.org/?probe=0faa734044) | Sep 04, 2023 |
| Lenovo        | Dory CRB                    | [9bacefd984](https://linux-hardware.org/?probe=9bacefd984) | Sep 04, 2023 |
| Acer          | Aspire XC-830               | [a3356b9a91](https://linux-hardware.org/?probe=a3356b9a91) | Sep 03, 2023 |
| Dell          | 0D441T A03                  | [3ba5173eb2](https://linux-hardware.org/?probe=3ba5173eb2) | Sep 03, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [c5ffec4746](https://linux-hardware.org/?probe=c5ffec4746) | Sep 03, 2023 |
| ASUSTek       | P5E-VM SE                   | [6ce264a945](https://linux-hardware.org/?probe=6ce264a945) | Sep 03, 2023 |
| Gigabyte      | X79-UD3                     | [58ff81abf2](https://linux-hardware.org/?probe=58ff81abf2) | Sep 03, 2023 |
| Intel         | H61                         | [209644dbc2](https://linux-hardware.org/?probe=209644dbc2) | Sep 03, 2023 |
| HP            | 1825                        | [ea5da3d446](https://linux-hardware.org/?probe=ea5da3d446) | Sep 03, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | [70172e3461](https://linux-hardware.org/?probe=70172e3461) | Sep 03, 2023 |
| Gigabyte      | G41M-Combo                  | [26c9b8cc2c](https://linux-hardware.org/?probe=26c9b8cc2c) | Sep 03, 2023 |
| ASUSTek       | M2N-MX SE Plus              | [5656c8fd0b](https://linux-hardware.org/?probe=5656c8fd0b) | Sep 03, 2023 |
| ASUSTek       | STRIKER II EXTREME          | [eafb53342a](https://linux-hardware.org/?probe=eafb53342a) | Sep 03, 2023 |
| BESSTAR Te... | Cherry Trail CR             | [3ad034200f](https://linux-hardware.org/?probe=3ad034200f) | Sep 03, 2023 |
| ASUSTek       | PRIME B365M-A               | [b44e37eec5](https://linux-hardware.org/?probe=b44e37eec5) | Sep 03, 2023 |
| ASRock        | FM2A78M-HD+                 | [a2d8c14a71](https://linux-hardware.org/?probe=a2d8c14a71) | Sep 03, 2023 |
| Gigabyte      | B450M DS3H V2               | [e0b3a3a55b](https://linux-hardware.org/?probe=e0b3a3a55b) | Sep 03, 2023 |
| ASRock        | A320D4-P1                   | [244c92966f](https://linux-hardware.org/?probe=244c92966f) | Sep 03, 2023 |
| NEC Comput... | MS-7451MA                   | [963dde730a](https://linux-hardware.org/?probe=963dde730a) | Sep 03, 2023 |
| HP            | 828A                        | [13126d5ce1](https://linux-hardware.org/?probe=13126d5ce1) | Sep 03, 2023 |
| ASUSTek       | M5A78L-M LX V2              | [92b5ca6639](https://linux-hardware.org/?probe=92b5ca6639) | Sep 03, 2023 |
| HP            | 843B                        | [d0cef21578](https://linux-hardware.org/?probe=d0cef21578) | Sep 03, 2023 |
| ASUSTek       | PRIME X470-PRO              | [976846f5c4](https://linux-hardware.org/?probe=976846f5c4) | Sep 03, 2023 |
| Pegatron      | IPMSB-GS                    | [35b8f645a7](https://linux-hardware.org/?probe=35b8f645a7) | Sep 03, 2023 |
| Gigabyte      | B450 AORUS M                | [2f09a79291](https://linux-hardware.org/?probe=2f09a79291) | Sep 03, 2023 |
| BESSTAR Te... | UM350                       | [9e80502e5d](https://linux-hardware.org/?probe=9e80502e5d) | Sep 03, 2023 |
| MSI           | Z390-A PRO                  | [16b96480a2](https://linux-hardware.org/?probe=16b96480a2) | Sep 03, 2023 |
| ASRock        | B450 Gaming K4              | [96dbf56986](https://linux-hardware.org/?probe=96dbf56986) | Sep 03, 2023 |
| Intel         | H81                         | [98f445e831](https://linux-hardware.org/?probe=98f445e831) | Sep 03, 2023 |
| Intel         | H81                         | [75aabbccf5](https://linux-hardware.org/?probe=75aabbccf5) | Sep 03, 2023 |
| ASUSTek       | M2N                         | [1df62dde56](https://linux-hardware.org/?probe=1df62dde56) | Sep 03, 2023 |
| Gigabyte      | F2A88X-UP4                  | [37bfab5442](https://linux-hardware.org/?probe=37bfab5442) | Sep 02, 2023 |
| Intel         | DQ77KB AAG40294-401         | [656df7cddd](https://linux-hardware.org/?probe=656df7cddd) | Sep 02, 2023 |
| HP            | 3646h                       | [cd226fee15](https://linux-hardware.org/?probe=cd226fee15) | Sep 02, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [4fa68712c5](https://linux-hardware.org/?probe=4fa68712c5) | Sep 02, 2023 |
| MSI           | B450M MORTAR MAX            | [b161a13302](https://linux-hardware.org/?probe=b161a13302) | Sep 02, 2023 |
| HP            | 1497                        | [43c8de838b](https://linux-hardware.org/?probe=43c8de838b) | Sep 02, 2023 |
| ASRock        | N68-S3 UCC                  | [53cd38e0c5](https://linux-hardware.org/?probe=53cd38e0c5) | Sep 02, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | [d25c5d75c1](https://linux-hardware.org/?probe=d25c5d75c1) | Sep 02, 2023 |
| ASRock        | B660M Pro RS                | [f24f7fb5bf](https://linux-hardware.org/?probe=f24f7fb5bf) | Sep 02, 2023 |
| Biostar       | H81MHV3 5.0                 | [8e05d94e36](https://linux-hardware.org/?probe=8e05d94e36) | Sep 02, 2023 |
| Dell          | 088DT1 A01                  | [2df9675af1](https://linux-hardware.org/?probe=2df9675af1) | Sep 02, 2023 |
| ASRock        | FM2A55M-VG3+                | [df01a7432c](https://linux-hardware.org/?probe=df01a7432c) | Sep 02, 2023 |
| Dell          | 04YP6J A02                  | [02c6b100f0](https://linux-hardware.org/?probe=02c6b100f0) | Sep 02, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [7907301c2f](https://linux-hardware.org/?probe=7907301c2f) | Sep 02, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [5590e2e8d6](https://linux-hardware.org/?probe=5590e2e8d6) | Sep 02, 2023 |
| MSI           | H81M-P33                    | [266b226035](https://linux-hardware.org/?probe=266b226035) | Sep 02, 2023 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | [8533d021f8](https://linux-hardware.org/?probe=8533d021f8) | Sep 02, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [c03e79d6e1](https://linux-hardware.org/?probe=c03e79d6e1) | Sep 02, 2023 |
| ASRock        | A620M-HDV/M.2+              | [674da4ba95](https://linux-hardware.org/?probe=674da4ba95) | Sep 02, 2023 |
| Acer          | Aspire TC-875 V:1.0         | [a25ba0bd0c](https://linux-hardware.org/?probe=a25ba0bd0c) | Sep 02, 2023 |
| ASRock        | H570 Steel Legend           | [192d8ebfa3](https://linux-hardware.org/?probe=192d8ebfa3) | Sep 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [2a9211117f](https://linux-hardware.org/?probe=2a9211117f) | Sep 02, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | [c972b65ed6](https://linux-hardware.org/?probe=c972b65ed6) | Sep 02, 2023 |
| Biostar       | N68S3B                      | [fc063709f7](https://linux-hardware.org/?probe=fc063709f7) | Sep 02, 2023 |
| Medion        | B460H6-EM                   | [ec8f0bbb13](https://linux-hardware.org/?probe=ec8f0bbb13) | Sep 02, 2023 |
| Foxconn       | 2ABF                        | [f3655da9eb](https://linux-hardware.org/?probe=f3655da9eb) | Sep 01, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | [ba40b3b859](https://linux-hardware.org/?probe=ba40b3b859) | Sep 01, 2023 |
| Dell          | 0XT4CY A01                  | [26665d2c19](https://linux-hardware.org/?probe=26665d2c19) | Sep 01, 2023 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | [f11dacb362](https://linux-hardware.org/?probe=f11dacb362) | Sep 01, 2023 |
| Intel         | DP67DE AAG10217-300         | [4d0db0b964](https://linux-hardware.org/?probe=4d0db0b964) | Sep 01, 2023 |
| MSI           | PRO Z690-P DDR4             | [6cd52cad83](https://linux-hardware.org/?probe=6cd52cad83) | Sep 01, 2023 |
| Acer          | Veriton M4610G              | [a5e1bdfce5](https://linux-hardware.org/?probe=a5e1bdfce5) | Sep 01, 2023 |
| Dell          | 00V62H A01                  | [5b976d122b](https://linux-hardware.org/?probe=5b976d122b) | Sep 01, 2023 |
| ASRock        | AB350M Pro4                 | [0f9de0fdf4](https://linux-hardware.org/?probe=0f9de0fdf4) | Sep 01, 2023 |
| HP            | 3032h                       | [7dfc9fa7a0](https://linux-hardware.org/?probe=7dfc9fa7a0) | Sep 01, 2023 |
| HP            | 1632                        | [a36b07aeda](https://linux-hardware.org/?probe=a36b07aeda) | Sep 01, 2023 |
| Foxconn       | A6VMX 0A                    | [338cdb7d40](https://linux-hardware.org/?probe=338cdb7d40) | Sep 01, 2023 |
| Gigabyte      | GA-MA770T-UD3               | [d5d9154715](https://linux-hardware.org/?probe=d5d9154715) | Sep 01, 2023 |
| Gigabyte      | B75M-D3H                    | [9e7e8b4fbd](https://linux-hardware.org/?probe=9e7e8b4fbd) | Sep 01, 2023 |
| Intel         | H110                        | [05970c6811](https://linux-hardware.org/?probe=05970c6811) | Sep 01, 2023 |
| AZW           | U59                         | [4cca42eeb3](https://linux-hardware.org/?probe=4cca42eeb3) | Sep 01, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [73147203ca](https://linux-hardware.org/?probe=73147203ca) | Sep 01, 2023 |
| ASUSTek       | PRIME B450M-K               | [8cc90dd6b0](https://linux-hardware.org/?probe=8cc90dd6b0) | Sep 01, 2023 |
| ASUSTek       | H81M2                       | [55dd352412](https://linux-hardware.org/?probe=55dd352412) | Sep 01, 2023 |
| Gigabyte      | M5NM1AI-GB                  | [2b2efe00dd](https://linux-hardware.org/?probe=2b2efe00dd) | Sep 01, 2023 |
| ASUSTek       | P9X79                       | [905ee212e5](https://linux-hardware.org/?probe=905ee212e5) | Sep 01, 2023 |
| Gigabyte      | B85M-D3H                    | [4660dc9f99](https://linux-hardware.org/?probe=4660dc9f99) | Sep 01, 2023 |
| AOpen         | i65HMx-D R1.04AL            | [aef1de4c53](https://linux-hardware.org/?probe=aef1de4c53) | Sep 01, 2023 |
| ASRock        | H97M Pro4                   | [ff1be33f8e](https://linux-hardware.org/?probe=ff1be33f8e) | Sep 01, 2023 |
| Medion        | B250H4-EM                   | [c2e1f2eb0b](https://linux-hardware.org/?probe=c2e1f2eb0b) | Sep 01, 2023 |
| Gigabyte      | X58A-UD3R                   | [8ee240ba0b](https://linux-hardware.org/?probe=8ee240ba0b) | Sep 01, 2023 |
| Intel         | SHARKBAY                    | [cc7fea9c3a](https://linux-hardware.org/?probe=cc7fea9c3a) | Sep 01, 2023 |
| ASUSTek       | H110M-A/M.2                 | [6010a74736](https://linux-hardware.org/?probe=6010a74736) | Sep 01, 2023 |
| ASUSTek       | N3050T                      | [fa4b0cbf08](https://linux-hardware.org/?probe=fa4b0cbf08) | Sep 01, 2023 |
| Foxconn       | G31MXP FAB:1.1              | [4fc2089efc](https://linux-hardware.org/?probe=4fc2089efc) | Sep 01, 2023 |
| ASUSTek       | M4A78LT-M-LE                | [d3d5887ff3](https://linux-hardware.org/?probe=d3d5887ff3) | Sep 01, 2023 |
| ASUSTek       | H110M-D                     | [b0127b4bff](https://linux-hardware.org/?probe=b0127b4bff) | Sep 01, 2023 |
| ASRock        | A320M-HD                    | [7fd4c8ad9c](https://linux-hardware.org/?probe=7fd4c8ad9c) | Sep 01, 2023 |
| MSI           | MS-7390                     | [7115ad031a](https://linux-hardware.org/?probe=7115ad031a) | Sep 01, 2023 |
| Fujitsu       | D3410-B2 S26361-D3410-B2    | [924293e07f](https://linux-hardware.org/?probe=924293e07f) | Sep 01, 2023 |
| MSI           | X99A WORKSTATION            | [46d1af7083](https://linux-hardware.org/?probe=46d1af7083) | Sep 01, 2023 |
| HP            | 1632                        | [13de11f1ff](https://linux-hardware.org/?probe=13de11f1ff) | Sep 01, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [d728ff01da](https://linux-hardware.org/?probe=d728ff01da) | Sep 01, 2023 |
| MSI           | PRO B660M-A DDR4            | [b6a24176aa](https://linux-hardware.org/?probe=b6a24176aa) | Aug 31, 2023 |
| ASUSTek       | WS X299 SAGE                | [a01568da7d](https://linux-hardware.org/?probe=a01568da7d) | Aug 31, 2023 |
| HP            | 18E5                        | [75c3b34f87](https://linux-hardware.org/?probe=75c3b34f87) | Aug 31, 2023 |
| HP            | 3397                        | [b9dabe8514](https://linux-hardware.org/?probe=b9dabe8514) | Aug 31, 2023 |
| Positivo      | ONE500                      | [1e84a5bf44](https://linux-hardware.org/?probe=1e84a5bf44) | Aug 31, 2023 |
| PCWare        | IPX1800E1                   | [bfe03f751b](https://linux-hardware.org/?probe=bfe03f751b) | Aug 31, 2023 |
| Shenzhen M... | F6BFC                       | [c5fc2337ec](https://linux-hardware.org/?probe=c5fc2337ec) | Aug 31, 2023 |
| Foxconn       | G41S/G41S-K                 | [8ad8098315](https://linux-hardware.org/?probe=8ad8098315) | Aug 31, 2023 |
| Intel         | H61                         | [d0bd2f4cfa](https://linux-hardware.org/?probe=d0bd2f4cfa) | Aug 31, 2023 |
| Intel         | B75                         | [d8367a0977](https://linux-hardware.org/?probe=d8367a0977) | Aug 31, 2023 |
| MSI           | H61M-P20/W8                 | [c35045d386](https://linux-hardware.org/?probe=c35045d386) | Aug 31, 2023 |
| HP            | 339A                        | [1ac5cd4af8](https://linux-hardware.org/?probe=1ac5cd4af8) | Aug 31, 2023 |
| HP            | 8768 A                      | [99787646c5](https://linux-hardware.org/?probe=99787646c5) | Aug 31, 2023 |
| HP            | 2215                        | [3b3b45d0ce](https://linux-hardware.org/?probe=3b3b45d0ce) | Aug 31, 2023 |
| Intel         | HM570                       | [d7c97890f9](https://linux-hardware.org/?probe=d7c97890f9) | Aug 31, 2023 |
| Red Hat       | RHEL RHEL-9.2.0 PC          | [ee06e81f13](https://linux-hardware.org/?probe=ee06e81f13) | Aug 31, 2023 |
| Intel         | H55                         | [955198ab64](https://linux-hardware.org/?probe=955198ab64) | Aug 31, 2023 |
| Gigabyte      | MTGU5AB-00                  | [2501ea0755](https://linux-hardware.org/?probe=2501ea0755) | Aug 31, 2023 |
| Dell          | 0GDG8Y A00                  | [b9c66b93e7](https://linux-hardware.org/?probe=b9c66b93e7) | Aug 31, 2023 |
| Gigabyte      | GA-73PVM-S2H                | [4abb2ab82b](https://linux-hardware.org/?probe=4abb2ab82b) | Aug 31, 2023 |
| Acer          | Veriton N4660G              | [25339d5009](https://linux-hardware.org/?probe=25339d5009) | Aug 31, 2023 |
| MSI           | X99A RAIDER                 | [5b79d93d0a](https://linux-hardware.org/?probe=5b79d93d0a) | Aug 31, 2023 |
| ASUSTek       | PRIME B550M-A               | [19cb61cbf6](https://linux-hardware.org/?probe=19cb61cbf6) | Aug 31, 2023 |
| Gigabyte      | B450M K-CF                  | [2086d348b2](https://linux-hardware.org/?probe=2086d348b2) | Aug 31, 2023 |
| Biostar       | G41D3                       | [0d4f48c335](https://linux-hardware.org/?probe=0d4f48c335) | Aug 31, 2023 |
| ASUSTek       | PRIME B550M-A               | [06860111ba](https://linux-hardware.org/?probe=06860111ba) | Aug 31, 2023 |
| MSI           | MS-B1421                    | [65d24e365e](https://linux-hardware.org/?probe=65d24e365e) | Aug 31, 2023 |
| MSI           | A88X-G41 PC Mate            | [13724b9cc2](https://linux-hardware.org/?probe=13724b9cc2) | Aug 31, 2023 |
| MSI           | A320M PRO-E                 | [92c4032614](https://linux-hardware.org/?probe=92c4032614) | Aug 31, 2023 |
| Lenovo        | SDK0J40700 WIN              | [12785fd41a](https://linux-hardware.org/?probe=12785fd41a) | Aug 31, 2023 |
| HP            | 1587h                       | [fe659d3db6](https://linux-hardware.org/?probe=fe659d3db6) | Aug 31, 2023 |
| HP            | 806A                        | [638dfe4edc](https://linux-hardware.org/?probe=638dfe4edc) | Aug 31, 2023 |
| MSI           | A520M-A PRO                 | [d672293a11](https://linux-hardware.org/?probe=d672293a11) | Aug 31, 2023 |
| ASUSTek       | PRIME X570-P                | [f0f4af9185](https://linux-hardware.org/?probe=f0f4af9185) | Aug 31, 2023 |
| MSI           | Z370-A PRO                  | [56e3937602](https://linux-hardware.org/?probe=56e3937602) | Aug 31, 2023 |
| ViewSonic     | VPC14-WP                    | [a5476c92e7](https://linux-hardware.org/?probe=a5476c92e7) | Aug 31, 2023 |
| Fujitsu       | D2679-B1 S26361-D2679-Bx... | [81ae698cf8](https://linux-hardware.org/?probe=81ae698cf8) | Aug 31, 2023 |
| HP            | 8768 A                      | [3b19eaee36](https://linux-hardware.org/?probe=3b19eaee36) | Aug 31, 2023 |
| Lenovo        | 1030 SDK0J40697 WIN 3305... | [e180d8d91b](https://linux-hardware.org/?probe=e180d8d91b) | Aug 31, 2023 |
| Gigabyte      | H110M-H-CF                  | [faf094d2ca](https://linux-hardware.org/?probe=faf094d2ca) | Aug 31, 2023 |
| Gigabyte      | Z590 AORUS ELITE AX         | [dc63902a68](https://linux-hardware.org/?probe=dc63902a68) | Aug 31, 2023 |
| MSI           | 880G-E45                    | [f10edf60fd](https://linux-hardware.org/?probe=f10edf60fd) | Aug 31, 2023 |
| MSI           | 2A78h                       | [78b5a663f2](https://linux-hardware.org/?probe=78b5a663f2) | Aug 31, 2023 |
| Dell          | 0KRC95 A02                  | [9173d00240](https://linux-hardware.org/?probe=9173d00240) | Aug 31, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [1a3fdd076f](https://linux-hardware.org/?probe=1a3fdd076f) | Aug 31, 2023 |
| MSI           | Boston                      | [f43cd6df24](https://linux-hardware.org/?probe=f43cd6df24) | Aug 31, 2023 |
| ECS           | A780GM-A                    | [12787b1e38](https://linux-hardware.org/?probe=12787b1e38) | Aug 31, 2023 |
| Megaware      | MW-NM70HD-MI 06/11/2012 ... | [7b8812491c](https://linux-hardware.org/?probe=7b8812491c) | Aug 31, 2023 |
| ASUSTek       | P5G41T-M LX                 | [bdae370995](https://linux-hardware.org/?probe=bdae370995) | Aug 30, 2023 |
| ASUSTek       | P8Q77-M                     | [d9760de265](https://linux-hardware.org/?probe=d9760de265) | Aug 30, 2023 |
| ASUSTek       | P8Z68-V LX                  | [7de2ff1052](https://linux-hardware.org/?probe=7de2ff1052) | Aug 30, 2023 |
| HP            | 3647h                       | [50ac4e01a4](https://linux-hardware.org/?probe=50ac4e01a4) | Aug 30, 2023 |
| MSI           | 970 GAMING                  | [f468606e38](https://linux-hardware.org/?probe=f468606e38) | Aug 30, 2023 |
| Dell          | OptiPlex 7050               | [a35a9d7d8a](https://linux-hardware.org/?probe=a35a9d7d8a) | Aug 30, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [79783b33ff](https://linux-hardware.org/?probe=79783b33ff) | Aug 30, 2023 |
| ASUSTek       | A8N-E                       | [84578c86e7](https://linux-hardware.org/?probe=84578c86e7) | Aug 30, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [42f87cb09b](https://linux-hardware.org/?probe=42f87cb09b) | Aug 30, 2023 |
| MSI           | H61MA-E35                   | [5eee145629](https://linux-hardware.org/?probe=5eee145629) | Aug 30, 2023 |
| Dell          | 0Y5DDC A00                  | [21ec7587ed](https://linux-hardware.org/?probe=21ec7587ed) | Aug 30, 2023 |
| ASUSTek       | P8H61 EVO                   | [facd465366](https://linux-hardware.org/?probe=facd465366) | Aug 30, 2023 |
| ASRock        | H470M-STX                   | [8ba058add5](https://linux-hardware.org/?probe=8ba058add5) | Aug 30, 2023 |
| HP            | 3047h                       | [5a35a1ebd1](https://linux-hardware.org/?probe=5a35a1ebd1) | Aug 30, 2023 |
| Gigabyte      | B450M H                     | [cd7bf0b2db](https://linux-hardware.org/?probe=cd7bf0b2db) | Aug 30, 2023 |
| Acer          | Aspire XC-330               | [2e1b103708](https://linux-hardware.org/?probe=2e1b103708) | Aug 30, 2023 |
| Intel         | DH55TC AAE70932-205         | [5e3be336db](https://linux-hardware.org/?probe=5e3be336db) | Aug 30, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [a65c8bb631](https://linux-hardware.org/?probe=a65c8bb631) | Aug 30, 2023 |
| Medion        | B460H6-EM                   | [fac263bf1a](https://linux-hardware.org/?probe=fac263bf1a) | Aug 30, 2023 |
| ASUSTek       | P6T                         | [69879aca23](https://linux-hardware.org/?probe=69879aca23) | Aug 30, 2023 |
| HP            | 0B4Ch D                     | [362ee070d7](https://linux-hardware.org/?probe=362ee070d7) | Aug 30, 2023 |
| ASRock        | M3A UCC                     | [b46f15b2d2](https://linux-hardware.org/?probe=b46f15b2d2) | Aug 30, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [a2f37c4111](https://linux-hardware.org/?probe=a2f37c4111) | Aug 30, 2023 |
| ASUSTek       | A88XM-E/USB                 | [376615315b](https://linux-hardware.org/?probe=376615315b) | Aug 30, 2023 |
| ASUSTek       | P5Q SE PLUS                 | [311596a316](https://linux-hardware.org/?probe=311596a316) | Aug 30, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [f040a85f2f](https://linux-hardware.org/?probe=f040a85f2f) | Aug 30, 2023 |
| ASUSTek       | P8H67-V                     | [24b196c99a](https://linux-hardware.org/?probe=24b196c99a) | Aug 30, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [c95eb85e58](https://linux-hardware.org/?probe=c95eb85e58) | Aug 30, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [9ed00c6987](https://linux-hardware.org/?probe=9ed00c6987) | Aug 30, 2023 |
| Foxconn       | H55MXV Series               | [af9d0ad662](https://linux-hardware.org/?probe=af9d0ad662) | Aug 30, 2023 |
| HP            | 876C SMVB                   | [25176eb482](https://linux-hardware.org/?probe=25176eb482) | Aug 30, 2023 |
| Gigabyte      | F2A88XM-HD3                 | [43cb5c7282](https://linux-hardware.org/?probe=43cb5c7282) | Aug 30, 2023 |
| HP            | 876C SMVB                   | [246cb7a1ca](https://linux-hardware.org/?probe=246cb7a1ca) | Aug 30, 2023 |
| ASRock        | H170M-ITX/ac                | [7921e28c6b](https://linux-hardware.org/?probe=7921e28c6b) | Aug 30, 2023 |
| OEM           | Intel H81                   | [7d179cb8e9](https://linux-hardware.org/?probe=7d179cb8e9) | Aug 30, 2023 |
| Dell          | 0DR845                      | [2b4ff07956](https://linux-hardware.org/?probe=2b4ff07956) | Aug 30, 2023 |
| ASRock        | 970 Pro3 R2.0               | [f59364572a](https://linux-hardware.org/?probe=f59364572a) | Aug 30, 2023 |
| Itautec       | ST 4254 ST-4254 Padrao 0... | [fbbbe0087a](https://linux-hardware.org/?probe=fbbbe0087a) | Aug 30, 2023 |
| Apple         | Mac-F221BEC8                | [13b77d8273](https://linux-hardware.org/?probe=13b77d8273) | Aug 30, 2023 |
| Acer          | Aspire TC-895 V:1.0         | [20bd10b5f4](https://linux-hardware.org/?probe=20bd10b5f4) | Aug 30, 2023 |
| Foxconn       | D180S/D190S/D290S Series... | [5f6030cb69](https://linux-hardware.org/?probe=5f6030cb69) | Aug 30, 2023 |
| Foxconn       | Lucknow                     | [eece5a84ae](https://linux-hardware.org/?probe=eece5a84ae) | Aug 30, 2023 |
| MSI           | A320M PRO-VD PLUS           | [1782829fec](https://linux-hardware.org/?probe=1782829fec) | Aug 29, 2023 |
| MSI           | H61M-E22/W8                 | [2439d2ed95](https://linux-hardware.org/?probe=2439d2ed95) | Aug 29, 2023 |
| HP            | 1589                        | [047e0158e8](https://linux-hardware.org/?probe=047e0158e8) | Aug 29, 2023 |
| ASUSTek       | PRIME Z270-P                | [c4bec90c4e](https://linux-hardware.org/?probe=c4bec90c4e) | Aug 29, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [567a59e1bc](https://linux-hardware.org/?probe=567a59e1bc) | Aug 29, 2023 |
| Gigabyte      | G31M-ES2L                   | [7094317c17](https://linux-hardware.org/?probe=7094317c17) | Aug 29, 2023 |
| Pegatron      | 2A73h                       | [390b033780](https://linux-hardware.org/?probe=390b033780) | Aug 29, 2023 |
| MSI           | PH61-SP35                   | [590f47f3fd](https://linux-hardware.org/?probe=590f47f3fd) | Aug 29, 2023 |
| Intel         | DG45ID AAE27729-312         | [add370815d](https://linux-hardware.org/?probe=add370815d) | Aug 29, 2023 |
| MSI           | Z97 GAMING 5                | [36cc5803b3](https://linux-hardware.org/?probe=36cc5803b3) | Aug 29, 2023 |
| Kobian        | PI945GCM ECS                | [85683b5fa3](https://linux-hardware.org/?probe=85683b5fa3) | Aug 29, 2023 |
| HP            | 885F A                      | [d665bb8939](https://linux-hardware.org/?probe=d665bb8939) | Aug 29, 2023 |
| Gigabyte      | X58A-UD7                    | [9d47465c31](https://linux-hardware.org/?probe=9d47465c31) | Aug 29, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [5222737445](https://linux-hardware.org/?probe=5222737445) | Aug 29, 2023 |
| Gigabyte      | A320M-HD2-CF                | [7d9c3aa2ad](https://linux-hardware.org/?probe=7d9c3aa2ad) | Aug 29, 2023 |
| MSI           | B550-A PRO                  | [b5ee83c5af](https://linux-hardware.org/?probe=b5ee83c5af) | Aug 29, 2023 |
| Lenovo        | ThinkCentre M91p 4518B84    | [e2fd5511ee](https://linux-hardware.org/?probe=e2fd5511ee) | Aug 29, 2023 |
| HP            | 89B4 A                      | [e70b3a2352](https://linux-hardware.org/?probe=e70b3a2352) | Aug 29, 2023 |
| ASUSTek       | M3N78-EH                    | [c0fb869905](https://linux-hardware.org/?probe=c0fb869905) | Aug 29, 2023 |
| HC Technol... | HCAR5000-MI                 | [50b9b4c466](https://linux-hardware.org/?probe=50b9b4c466) | Aug 28, 2023 |
| MSI           | MAG B550 TORPEDO            | [7ac77b7bac](https://linux-hardware.org/?probe=7ac77b7bac) | Aug 28, 2023 |
| MSI           | G41M-P33 Combo              | [23712e9380](https://linux-hardware.org/?probe=23712e9380) | Aug 28, 2023 |
| Intel         | H81                         | [9b70a28b25](https://linux-hardware.org/?probe=9b70a28b25) | Aug 28, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [6d4609efa2](https://linux-hardware.org/?probe=6d4609efa2) | Aug 28, 2023 |
| HP            | 21D0                        | [8978dfd3bf](https://linux-hardware.org/?probe=8978dfd3bf) | Aug 28, 2023 |
| ASUSTek       | M4N68T-M-V2                 | [409ccc747c](https://linux-hardware.org/?probe=409ccc747c) | Aug 28, 2023 |
| MSI           | B450M PRO-VDH MAX           | [844b4e4dc2](https://linux-hardware.org/?probe=844b4e4dc2) | Aug 28, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [22d4876142](https://linux-hardware.org/?probe=22d4876142) | Aug 28, 2023 |
| Gigabyte      | B550M DS3H                  | [90b8d2cb66](https://linux-hardware.org/?probe=90b8d2cb66) | Aug 28, 2023 |
| Dell          | 0C0YYY A00                  | [1ac938e884](https://linux-hardware.org/?probe=1ac938e884) | Aug 28, 2023 |
| Positivo      | POS-PQ45AU                  | [aba45a4f14](https://linux-hardware.org/?probe=aba45a4f14) | Aug 27, 2023 |
| ASUSTek       | PRIME B450M-A               | [b4411a9169](https://linux-hardware.org/?probe=b4411a9169) | Aug 27, 2023 |
| MSI           | A68HM-E33 V2                | [bf483bc8d3](https://linux-hardware.org/?probe=bf483bc8d3) | Aug 27, 2023 |
| MSI           | B85M-G43                    | [96fd52d530](https://linux-hardware.org/?probe=96fd52d530) | Aug 27, 2023 |
| ASRock        | Z490M-ITX/ac                | [d3a4f92f62](https://linux-hardware.org/?probe=d3a4f92f62) | Aug 27, 2023 |
| ASUSTek       | P5KPL-AM                    | [a139f22d59](https://linux-hardware.org/?probe=a139f22d59) | Aug 27, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [248f2a9745](https://linux-hardware.org/?probe=248f2a9745) | Aug 27, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [713e62f936](https://linux-hardware.org/?probe=713e62f936) | Aug 27, 2023 |
| Foxconn       | 2ABF                        | [b0a8f65bca](https://linux-hardware.org/?probe=b0a8f65bca) | Aug 27, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [883d4fbfeb](https://linux-hardware.org/?probe=883d4fbfeb) | Aug 27, 2023 |
| HP            | 87D6 SMVB                   | [a2cf3918b7](https://linux-hardware.org/?probe=a2cf3918b7) | Aug 27, 2023 |
| Dell          | 0HR330                      | [700643ac0e](https://linux-hardware.org/?probe=700643ac0e) | Aug 27, 2023 |
| ASUSTek       | PRIME A520M-K               | [ea6d90ba09](https://linux-hardware.org/?probe=ea6d90ba09) | Aug 27, 2023 |
| Dell          | 0JCTF8 A00                  | [af55d05855](https://linux-hardware.org/?probe=af55d05855) | Aug 26, 2023 |
| ASUSTek       | Z77-A                       | [1aa1747b87](https://linux-hardware.org/?probe=1aa1747b87) | Aug 26, 2023 |
| Pegatron      | IPM41-D3                    | [b67fbfb529](https://linux-hardware.org/?probe=b67fbfb529) | Aug 26, 2023 |
| HP            | 1998                        | [2c6c07a7d3](https://linux-hardware.org/?probe=2c6c07a7d3) | Aug 26, 2023 |
| ASRock        | Wolfdale1333-D667           | [7dfa16eab4](https://linux-hardware.org/?probe=7dfa16eab4) | Aug 26, 2023 |
| Intel         | D33217CK G76541-301         | [24b3b7aac4](https://linux-hardware.org/?probe=24b3b7aac4) | Aug 26, 2023 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | [9bde22726b](https://linux-hardware.org/?probe=9bde22726b) | Aug 26, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | [7db44bc8af](https://linux-hardware.org/?probe=7db44bc8af) | Aug 26, 2023 |
| Positivo      | POS-PIG41BA POSITIVO        | [05dc1d19de](https://linux-hardware.org/?probe=05dc1d19de) | Aug 26, 2023 |
| Dell          | 00V62H A01                  | [69824bbd6d](https://linux-hardware.org/?probe=69824bbd6d) | Aug 26, 2023 |
| ASUSTek       | H97M-E                      | [ff832aca4a](https://linux-hardware.org/?probe=ff832aca4a) | Aug 26, 2023 |
| Dell          | 0XCR8D A02                  | [1f5f734faa](https://linux-hardware.org/?probe=1f5f734faa) | Aug 26, 2023 |
| ASUSTek       | AT5NM10-I                   | [15edd1ec31](https://linux-hardware.org/?probe=15edd1ec31) | Aug 26, 2023 |
| ASUSTek       | P8Z77-V LX                  | [9f1872b5e9](https://linux-hardware.org/?probe=9f1872b5e9) | Aug 26, 2023 |
| MSI           | H81M-P33                    | [e86c3faf2e](https://linux-hardware.org/?probe=e86c3faf2e) | Aug 26, 2023 |
| Dell          | 0Y2MRG A00                  | [451af13730](https://linux-hardware.org/?probe=451af13730) | Aug 26, 2023 |
| ASUSTek       | H110M-K                     | [9cf3912874](https://linux-hardware.org/?probe=9cf3912874) | Aug 26, 2023 |
| MSI           | H510M-A PRO                 | [0620b43b6a](https://linux-hardware.org/?probe=0620b43b6a) | Aug 26, 2023 |
| ASUSTek       | P5K-E                       | [aa48da4e34](https://linux-hardware.org/?probe=aa48da4e34) | Aug 26, 2023 |
| Gigabyte      | Z97X-UD3H-CF                | [78df724503](https://linux-hardware.org/?probe=78df724503) | Aug 26, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [5febb12d66](https://linux-hardware.org/?probe=5febb12d66) | Aug 26, 2023 |
| Biostar       | G41D3C                      | [5e2c852104](https://linux-hardware.org/?probe=5e2c852104) | Aug 26, 2023 |
| ASUSTek       | EX-A320M-GAMING             | [6fc7c35bc9](https://linux-hardware.org/?probe=6fc7c35bc9) | Aug 26, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [baa3bc61e9](https://linux-hardware.org/?probe=baa3bc61e9) | Aug 25, 2023 |
| Gigabyte      | Z77X-UD5H                   | [98a1dbe051](https://linux-hardware.org/?probe=98a1dbe051) | Aug 25, 2023 |
| HP            | 89D8 SMVB                   | [d9898111f8](https://linux-hardware.org/?probe=d9898111f8) | Aug 25, 2023 |
| ASUSTek       | P8H77-V LE                  | [03740cd24c](https://linux-hardware.org/?probe=03740cd24c) | Aug 25, 2023 |
| ASUSTek       | P8Z68-V LE                  | [5457261ab6](https://linux-hardware.org/?probe=5457261ab6) | Aug 25, 2023 |
| ASRock        | B250M-HDV                   | [1bc8a402b3](https://linux-hardware.org/?probe=1bc8a402b3) | Aug 25, 2023 |
| MSI           | A320M-A PRO                 | [0145505cea](https://linux-hardware.org/?probe=0145505cea) | Aug 25, 2023 |
| ASUSTek       | P8Q77-M                     | [8445b944a5](https://linux-hardware.org/?probe=8445b944a5) | Aug 25, 2023 |
| ASUSTek       | PRIME B450M-A II            | [255eeb3d65](https://linux-hardware.org/?probe=255eeb3d65) | Aug 25, 2023 |
| MSI           | B450M MORTAR MAX            | [b328603445](https://linux-hardware.org/?probe=b328603445) | Aug 25, 2023 |
| ASUSTek       | M4A87TD EVO                 | [70a6d20dbf](https://linux-hardware.org/?probe=70a6d20dbf) | Aug 25, 2023 |
| ASRock        | B450M Pro4                  | [8237cf85b3](https://linux-hardware.org/?probe=8237cf85b3) | Aug 25, 2023 |
| Gigabyte      | H81M-H                      | [7da367fdec](https://linux-hardware.org/?probe=7da367fdec) | Aug 25, 2023 |
| Lenovo        | SKYBAY NOK                  | [38448389ce](https://linux-hardware.org/?probe=38448389ce) | Aug 25, 2023 |
| MSI           | Z97S SLI Krait Edition      | [037e041959](https://linux-hardware.org/?probe=037e041959) | Aug 25, 2023 |
| HP            | 21F5 0A                     | [812718f3e7](https://linux-hardware.org/?probe=812718f3e7) | Aug 25, 2023 |
| Gigabyte      | GA-MA770T-UD3P              | [d1e0d41982](https://linux-hardware.org/?probe=d1e0d41982) | Aug 24, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [85984e2830](https://linux-hardware.org/?probe=85984e2830) | Aug 24, 2023 |
| Pegatron      | EVANS                       | [1b32c5d271](https://linux-hardware.org/?probe=1b32c5d271) | Aug 24, 2023 |
| Lenovo        | 3141 SDK0J40697 WIN 3305... | [088ba21947](https://linux-hardware.org/?probe=088ba21947) | Aug 24, 2023 |
| Acer          | Aspire TC-115               | [1c22aff012](https://linux-hardware.org/?probe=1c22aff012) | Aug 24, 2023 |
| Lenovo        | ThinkCentre M72e 3597A56    | [6b6d2e95f9](https://linux-hardware.org/?probe=6b6d2e95f9) | Aug 24, 2023 |
| Acer          | EQ45LM                      | [aa8ea529f7](https://linux-hardware.org/?probe=aa8ea529f7) | Aug 24, 2023 |
| ASUSTek       | P8H77-M PRO                 | [4953513629](https://linux-hardware.org/?probe=4953513629) | Aug 24, 2023 |
| Acer          | Aspire TC-605               | [03cff37b1a](https://linux-hardware.org/?probe=03cff37b1a) | Aug 24, 2023 |
| ASUSTek       | P7H55-M BR                  | [820b86d560](https://linux-hardware.org/?probe=820b86d560) | Aug 24, 2023 |
| Lenovo        | 312A NOK                    | [88533268cf](https://linux-hardware.org/?probe=88533268cf) | Aug 23, 2023 |
| ASUSTek       | H110M-A/M.2                 | [e45572b49a](https://linux-hardware.org/?probe=e45572b49a) | Aug 23, 2023 |
| Intel         | DZ77BH-55K AAG39008-400     | [30c81f585a](https://linux-hardware.org/?probe=30c81f585a) | Aug 23, 2023 |
| MSI           | A320M-A PRO                 | [c5ea9af7cd](https://linux-hardware.org/?probe=c5ea9af7cd) | Aug 23, 2023 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [aa959925b8](https://linux-hardware.org/?probe=aa959925b8) | Aug 23, 2023 |
| Gigabyte      | GA-970A-UD3                 | [796925bf51](https://linux-hardware.org/?probe=796925bf51) | Aug 23, 2023 |
| GEEKOM        | GM08i3T                     | [36ea06968d](https://linux-hardware.org/?probe=36ea06968d) | Aug 23, 2023 |
| ASUSTek       | PRIME B450M-A II            | [618b994ac1](https://linux-hardware.org/?probe=618b994ac1) | Aug 23, 2023 |
| Medion        | B460H6-EM                   | [7da77cb4d7](https://linux-hardware.org/?probe=7da77cb4d7) | Aug 22, 2023 |
| Intel         | H81                         | [fe1e95123d](https://linux-hardware.org/?probe=fe1e95123d) | Aug 22, 2023 |
| Gigabyte      | X299 AORUS Gaming-CF        | [e99aa2e4d7](https://linux-hardware.org/?probe=e99aa2e4d7) | Aug 22, 2023 |
| MSI           | G31TM-P21                   | [c8aa8973a4](https://linux-hardware.org/?probe=c8aa8973a4) | Aug 22, 2023 |
| Gigabyte      | X299 AORUS Gaming-CF        | [d39f8430ac](https://linux-hardware.org/?probe=d39f8430ac) | Aug 22, 2023 |
| HP            | 1850                        | [d9b3f59f97](https://linux-hardware.org/?probe=d9b3f59f97) | Aug 22, 2023 |
| Red Hat       | RHEL RHEL-9.2.0 PC          | [48f65a86aa](https://linux-hardware.org/?probe=48f65a86aa) | Aug 22, 2023 |
| MSI           | B450M BAZOOKA MAX WIFI      | [3bdb30f543](https://linux-hardware.org/?probe=3bdb30f543) | Aug 22, 2023 |
| ASUSTek       | PRIME H270-PRO              | [05eae6c877](https://linux-hardware.org/?probe=05eae6c877) | Aug 22, 2023 |
| Lenovo        | H415                        | [e6277f1ab8](https://linux-hardware.org/?probe=e6277f1ab8) | Aug 22, 2023 |
| ASRock        | 890GX Pro3                  | [c36b43c52a](https://linux-hardware.org/?probe=c36b43c52a) | Aug 21, 2023 |
| MSI           | X470 GAMING PLUS            | [191c724d49](https://linux-hardware.org/?probe=191c724d49) | Aug 21, 2023 |
| Intel         | H61                         | [4d6bf88f48](https://linux-hardware.org/?probe=4d6bf88f48) | Aug 21, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [e9c7a12d52](https://linux-hardware.org/?probe=e9c7a12d52) | Aug 21, 2023 |
| AMD           | Inagua CRB                  | [9455337239](https://linux-hardware.org/?probe=9455337239) | Aug 21, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [33ad1ac951](https://linux-hardware.org/?probe=33ad1ac951) | Aug 21, 2023 |
| ASRock        | H510M-HVS R2.0              | [7993a53688](https://linux-hardware.org/?probe=7993a53688) | Aug 21, 2023 |
| HP            | 2B52                        | [ed7526d18f](https://linux-hardware.org/?probe=ed7526d18f) | Aug 20, 2023 |
| Gigabyte      | B75M-D2V                    | [8c805fa379](https://linux-hardware.org/?probe=8c805fa379) | Aug 20, 2023 |
| Dell          | 06D7TR A02                  | [dac6078c1b](https://linux-hardware.org/?probe=dac6078c1b) | Aug 20, 2023 |
| ASUSTek       | PRIME X570-P                | [6c5abd788f](https://linux-hardware.org/?probe=6c5abd788f) | Aug 20, 2023 |
| Intel         | X99                         | [e16fe5b0f3](https://linux-hardware.org/?probe=e16fe5b0f3) | Aug 19, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [1824f3c712](https://linux-hardware.org/?probe=1824f3c712) | Aug 19, 2023 |
| Gigabyte      | GA-N680SLI-DQ6              | [0838a31aaf](https://linux-hardware.org/?probe=0838a31aaf) | Aug 19, 2023 |
| Gigabyte      | G31M-S2L                    | [5768055184](https://linux-hardware.org/?probe=5768055184) | Aug 19, 2023 |
| Gigabyte      | M68MT-S2P                   | [bbf0f31c1b](https://linux-hardware.org/?probe=bbf0f31c1b) | Aug 19, 2023 |
| Gigabyte      | F2A68HM-HD2                 | [8735b5577b](https://linux-hardware.org/?probe=8735b5577b) | Aug 18, 2023 |
| ASRock        | Z370 Pro4                   | [9b7cf0384c](https://linux-hardware.org/?probe=9b7cf0384c) | Aug 18, 2023 |
| ASUSTek       | B85M-G                      | [c8eaccabf2](https://linux-hardware.org/?probe=c8eaccabf2) | Aug 18, 2023 |
| AZW           | EQ                          | [6fda99ad46](https://linux-hardware.org/?probe=6fda99ad46) | Aug 18, 2023 |
| ASUSTek       | H61M-E                      | [d4849fe5f4](https://linux-hardware.org/?probe=d4849fe5f4) | Aug 18, 2023 |
| ECS           | A55F-M4                     | [93a5944754](https://linux-hardware.org/?probe=93a5944754) | Aug 18, 2023 |
| ASUSTek       | PRIME H410M-E               | [ae37d9f640](https://linux-hardware.org/?probe=ae37d9f640) | Aug 18, 2023 |
| Gigabyte      | Z77M-D3H                    | [154e2db6b7](https://linux-hardware.org/?probe=154e2db6b7) | Aug 18, 2023 |
| Dell          | 0200DY A00                  | [9b94c2313c](https://linux-hardware.org/?probe=9b94c2313c) | Aug 18, 2023 |
| Gigabyte      | G31M-ES2L                   | [d84596d3c1](https://linux-hardware.org/?probe=d84596d3c1) | Aug 18, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [7658411c87](https://linux-hardware.org/?probe=7658411c87) | Aug 17, 2023 |
| ASUSTek       | PRIME H410M-R               | [809590bdb0](https://linux-hardware.org/?probe=809590bdb0) | Aug 17, 2023 |
| ASUSTek       | TUF Gaming B760M-PLUS WI... | [c956862ccd](https://linux-hardware.org/?probe=c956862ccd) | Aug 17, 2023 |
| HP            | 8768 A                      | [a2b7f6905c](https://linux-hardware.org/?probe=a2b7f6905c) | Aug 17, 2023 |
| Intel         | DE3815TYKH H26998-402       | [a2a8c567a3](https://linux-hardware.org/?probe=a2a8c567a3) | Aug 17, 2023 |
| Dell          | 0XFWHV A00                  | [0ddde115f9](https://linux-hardware.org/?probe=0ddde115f9) | Aug 17, 2023 |
| Lenovo        | SDK0E50510 WIN              | [0a48b003bb](https://linux-hardware.org/?probe=0a48b003bb) | Aug 17, 2023 |
| Shuttle       | DS20U                       | [3a1ceb6021](https://linux-hardware.org/?probe=3a1ceb6021) | Aug 17, 2023 |
| Gigabyte      | B85M-D3H                    | [fe8d01fa26](https://linux-hardware.org/?probe=fe8d01fa26) | Aug 17, 2023 |
| Unknown       | Unknown                     | [6b82ccd639](https://linux-hardware.org/?probe=6b82ccd639) | Aug 17, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | [83e6c3323d](https://linux-hardware.org/?probe=83e6c3323d) | Aug 16, 2023 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [945643bffa](https://linux-hardware.org/?probe=945643bffa) | Aug 16, 2023 |
| Gigabyte      | 965P-S3                     | [d9557da16c](https://linux-hardware.org/?probe=d9557da16c) | Aug 16, 2023 |
| ASUSTek       | H110M-R                     | [3151636f73](https://linux-hardware.org/?probe=3151636f73) | Aug 16, 2023 |
| MSI           | PRO H610M-G DDR4            | [bd75f21361](https://linux-hardware.org/?probe=bd75f21361) | Aug 16, 2023 |
| HP            | 0B4Ch D                     | [abb0a09230](https://linux-hardware.org/?probe=abb0a09230) | Aug 16, 2023 |
| Gigabyte      | P55-USB3                    | [4e25d8ef9f](https://linux-hardware.org/?probe=4e25d8ef9f) | Aug 16, 2023 |
| ASUSTek       | P8B75-V                     | [78a5205783](https://linux-hardware.org/?probe=78a5205783) | Aug 16, 2023 |
| Gigabyte      | B550M DS3H AC               | [881b50cb6f](https://linux-hardware.org/?probe=881b50cb6f) | Aug 16, 2023 |
| MSI           | A320M-A PRO MAX             | [57a2ddf4a7](https://linux-hardware.org/?probe=57a2ddf4a7) | Aug 16, 2023 |
| Acer          | EM61SM/EM61PM               | [428f134de7](https://linux-hardware.org/?probe=428f134de7) | Aug 15, 2023 |
| ASUSTek       | H97-PLUS                    | [166b18583b](https://linux-hardware.org/?probe=166b18583b) | Aug 15, 2023 |
| Dell          | 0NW6H5 A00                  | [8f1803298d](https://linux-hardware.org/?probe=8f1803298d) | Aug 15, 2023 |
| ASUSTek       | P5K SE                      | [8d6a3e990c](https://linux-hardware.org/?probe=8d6a3e990c) | Aug 15, 2023 |
| MSI           | H310M PRO-VDH               | [fe173bc6ed](https://linux-hardware.org/?probe=fe173bc6ed) | Aug 15, 2023 |
| ASUSTek       | H170-PRO                    | [a5086e207e](https://linux-hardware.org/?probe=a5086e207e) | Aug 15, 2023 |
| ASUSTek       | P8H61-M LE R2.0             | [ac6dd63085](https://linux-hardware.org/?probe=ac6dd63085) | Aug 15, 2023 |
| ASRock        | A320M/ac                    | [5012358457](https://linux-hardware.org/?probe=5012358457) | Aug 15, 2023 |
| Gigabyte      | H61M-DS2                    | [2a753fd907](https://linux-hardware.org/?probe=2a753fd907) | Aug 14, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | [1bb822c058](https://linux-hardware.org/?probe=1bb822c058) | Aug 13, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | [c24273512e](https://linux-hardware.org/?probe=c24273512e) | Aug 13, 2023 |
| HP            | 3031h                       | [2f9084013a](https://linux-hardware.org/?probe=2f9084013a) | Aug 13, 2023 |
| Huanan        | X99-F8 V2.0                 | [60746f5bad](https://linux-hardware.org/?probe=60746f5bad) | Aug 13, 2023 |
| ASUSTek       | P7P55D DELUXE               | [f900ebabde](https://linux-hardware.org/?probe=f900ebabde) | Aug 13, 2023 |
| MSI           | B450M-A PRO MAX             | [61908d704c](https://linux-hardware.org/?probe=61908d704c) | Aug 13, 2023 |
| ASUSTek       | Z170-P                      | [a32f4633c2](https://linux-hardware.org/?probe=a32f4633c2) | Aug 12, 2023 |
| ASUSTek       | Rampage IV GENE             | [2a494a04b5](https://linux-hardware.org/?probe=2a494a04b5) | Aug 12, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [0c0df32662](https://linux-hardware.org/?probe=0c0df32662) | Aug 12, 2023 |
| ASRock        | 970A-G                      | [5a2b77eaee](https://linux-hardware.org/?probe=5a2b77eaee) | Aug 12, 2023 |
| ASUSTek       | ROG STRIX Z590-I GAMING ... | [8903899ce9](https://linux-hardware.org/?probe=8903899ce9) | Aug 11, 2023 |
| Biostar       | B660GTQ                     | [520d57cadc](https://linux-hardware.org/?probe=520d57cadc) | Aug 11, 2023 |
| MSI           | H410M-A PRO                 | [de3739c2a5](https://linux-hardware.org/?probe=de3739c2a5) | Aug 11, 2023 |
| HP            | ProLiant ML115 G5           | [305ccefd04](https://linux-hardware.org/?probe=305ccefd04) | Aug 10, 2023 |
| Gigabyte      | B450M DS3H-CF               | [ee14fdafcf](https://linux-hardware.org/?probe=ee14fdafcf) | Aug 10, 2023 |
| HP            | 18E7                        | [ff27f888f0](https://linux-hardware.org/?probe=ff27f888f0) | Aug 10, 2023 |
| HP            | 2215                        | [40ace58487](https://linux-hardware.org/?probe=40ace58487) | Aug 10, 2023 |
| Dell          | OptiPlex 755                | [279ed1e2d5](https://linux-hardware.org/?probe=279ed1e2d5) | Aug 10, 2023 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | [7acbd56a40](https://linux-hardware.org/?probe=7acbd56a40) | Aug 10, 2023 |
| MSI           | A68HM-E33                   | [be692e44b5](https://linux-hardware.org/?probe=be692e44b5) | Aug 10, 2023 |
| Dell          | 040DDP A00                  | [13d99d66da](https://linux-hardware.org/?probe=13d99d66da) | Aug 09, 2023 |
| MSI           | B360M PRO-VDH               | [e3cf4cec26](https://linux-hardware.org/?probe=e3cf4cec26) | Aug 09, 2023 |
| Foxconn       | 2A8Ch                       | [a936584caa](https://linux-hardware.org/?probe=a936584caa) | Aug 09, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [d073a53c85](https://linux-hardware.org/?probe=d073a53c85) | Aug 08, 2023 |
| Dell          | 0P301D A00                  | [e5091194fb](https://linux-hardware.org/?probe=e5091194fb) | Aug 08, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [c04ac90ce8](https://linux-hardware.org/?probe=c04ac90ce8) | Aug 07, 2023 |
| Digiboard     | NM70-I                      | [280ee6d8fe](https://linux-hardware.org/?probe=280ee6d8fe) | Aug 07, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [497623fdfd](https://linux-hardware.org/?probe=497623fdfd) | Aug 07, 2023 |
| Dell          | 0M9KCM A02                  | [a854d04706](https://linux-hardware.org/?probe=a854d04706) | Aug 07, 2023 |
| Dell          | 0WR7PY A03                  | [becf318878](https://linux-hardware.org/?probe=becf318878) | Aug 07, 2023 |
| ASUSTek       | M4A77TD                     | [667b258dd5](https://linux-hardware.org/?probe=667b258dd5) | Aug 06, 2023 |
| ASUSTek       | P5GDC                       | [82fefe395d](https://linux-hardware.org/?probe=82fefe395d) | Aug 06, 2023 |
| MSI           | H310M PRO-D                 | [201844f73e](https://linux-hardware.org/?probe=201844f73e) | Aug 06, 2023 |
| ASUSTek       | TUF Z390M-PRO GAMING        | [a5eb82b4f9](https://linux-hardware.org/?probe=a5eb82b4f9) | Aug 06, 2023 |
| Gigabyte      | EP45-UD3LR                  | [0f3d20a423](https://linux-hardware.org/?probe=0f3d20a423) | Aug 06, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [27792f16e2](https://linux-hardware.org/?probe=27792f16e2) | Aug 06, 2023 |
| Gigabyte      | 970A-UD3P                   | [dcd061dff8](https://linux-hardware.org/?probe=dcd061dff8) | Aug 05, 2023 |
| Medion        | B550A4-EM                   | [f1bf2b93c1](https://linux-hardware.org/?probe=f1bf2b93c1) | Aug 05, 2023 |
| ASRock        | B550M-HDV                   | [83ee40459a](https://linux-hardware.org/?probe=83ee40459a) | Aug 05, 2023 |
| Acer          | EQ45LM                      | [b9be16315e](https://linux-hardware.org/?probe=b9be16315e) | Aug 05, 2023 |
| Intel         | H81                         | [4441a1a1ca](https://linux-hardware.org/?probe=4441a1a1ca) | Aug 05, 2023 |
| ASRock        | G31M-S                      | [02bb341cc9](https://linux-hardware.org/?probe=02bb341cc9) | Aug 04, 2023 |
| MANCER        | A320M-DA 1006               | [573affec7b](https://linux-hardware.org/?probe=573affec7b) | Aug 04, 2023 |
| Dell          | 09M8Y8 A02                  | [4b57bbf30e](https://linux-hardware.org/?probe=4b57bbf30e) | Aug 04, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [e0b5eb8809](https://linux-hardware.org/?probe=e0b5eb8809) | Aug 04, 2023 |
| HP            | 844C                        | [36185008dc](https://linux-hardware.org/?probe=36185008dc) | Aug 03, 2023 |
| Gigabyte      | B450M S2H V2                | [a01412b320](https://linux-hardware.org/?probe=a01412b320) | Aug 03, 2023 |
| HP            | 8767 A                      | [2cf5a8cce4](https://linux-hardware.org/?probe=2cf5a8cce4) | Aug 03, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [221b0f2db2](https://linux-hardware.org/?probe=221b0f2db2) | Aug 02, 2023 |
| MSI           | 760GM-P23                   | [c9e70623fc](https://linux-hardware.org/?probe=c9e70623fc) | Aug 02, 2023 |
| Dell          | 0WR7PY A01                  | [522acc7a8e](https://linux-hardware.org/?probe=522acc7a8e) | Aug 02, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c94a18b924](https://linux-hardware.org/?probe=c94a18b924) | Aug 02, 2023 |
| Dell          | 0GY6Y8 A02                  | [e1d2deb748](https://linux-hardware.org/?probe=e1d2deb748) | Aug 02, 2023 |
| ASRock        | Z77 Extreme4                | [52c54dc66e](https://linux-hardware.org/?probe=52c54dc66e) | Aug 02, 2023 |
| Fujitsu       | D3402-A1 S26361-D3402-A1    | [5cbdefa7c5](https://linux-hardware.org/?probe=5cbdefa7c5) | Aug 02, 2023 |
| Gigabyte      | H61M-S2PV                   | [70c8bcf589](https://linux-hardware.org/?probe=70c8bcf589) | Aug 02, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [4cafb5721e](https://linux-hardware.org/?probe=4cafb5721e) | Aug 02, 2023 |
| ASRock        | H410M-HDV/M.2               | [71a11bdffd](https://linux-hardware.org/?probe=71a11bdffd) | Aug 02, 2023 |
| ASRock        | Z170 Extreme4               | [7ef89d48d6](https://linux-hardware.org/?probe=7ef89d48d6) | Aug 01, 2023 |
| ASRock        | A320M-DVS R4.0              | [648421ac0a](https://linux-hardware.org/?probe=648421ac0a) | Aug 01, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [b298625640](https://linux-hardware.org/?probe=b298625640) | Aug 01, 2023 |
| HP            | 18E7                        | [339050cd65](https://linux-hardware.org/?probe=339050cd65) | Aug 01, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [3a500cdb55](https://linux-hardware.org/?probe=3a500cdb55) | Aug 01, 2023 |
| MSI           | B560M PRO-VDH WIFI          | [0d26da86c7](https://linux-hardware.org/?probe=0d26da86c7) | Jul 31, 2023 |
| Foxconn       | H61MXL/H61MXL-K             | [e51e841817](https://linux-hardware.org/?probe=e51e841817) | Jul 31, 2023 |
| Dell          | 0C27VV A03                  | [75ff82774b](https://linux-hardware.org/?probe=75ff82774b) | Jul 31, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [2191e17d89](https://linux-hardware.org/?probe=2191e17d89) | Jul 31, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [e11390bc86](https://linux-hardware.org/?probe=e11390bc86) | Jul 31, 2023 |
| MSI           | A320M-A PRO                 | [a0394c8f0b](https://linux-hardware.org/?probe=a0394c8f0b) | Jul 30, 2023 |
| MSI           | MS-B1591                    | [9bdfd87437](https://linux-hardware.org/?probe=9bdfd87437) | Jul 30, 2023 |
| ASRock        | B650M PG Riptide            | [9f95c471d0](https://linux-hardware.org/?probe=9f95c471d0) | Jul 30, 2023 |
| ASRock        | Z68 Pro3 Gen3               | [7d262746c9](https://linux-hardware.org/?probe=7d262746c9) | Jul 30, 2023 |
| ASUSTek       | P5G41C-M LX                 | [18f28e3fb6](https://linux-hardware.org/?probe=18f28e3fb6) | Jul 29, 2023 |
| Pegatron      | EVANS                       | [323d6a7283](https://linux-hardware.org/?probe=323d6a7283) | Jul 29, 2023 |
| Dell          | 0N4YC8 A00                  | [be08c309d2](https://linux-hardware.org/?probe=be08c309d2) | Jul 29, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [ac8aab1d26](https://linux-hardware.org/?probe=ac8aab1d26) | Jul 29, 2023 |
| Lenovo        | 3111 NOK                    | [bced6fb88a](https://linux-hardware.org/?probe=bced6fb88a) | Jul 29, 2023 |
| MSI           | B450M PRO-M2 MAX            | [e4587af8ce](https://linux-hardware.org/?probe=e4587af8ce) | Jul 28, 2023 |
| ASRock        | H270 Pro4                   | [52cefaf6dd](https://linux-hardware.org/?probe=52cefaf6dd) | Jul 28, 2023 |
| PCWare        | IPX1800E2                   | [ee17cd82e7](https://linux-hardware.org/?probe=ee17cd82e7) | Jul 27, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | [1d4e6c23cf](https://linux-hardware.org/?probe=1d4e6c23cf) | Jul 27, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [55102fad5b](https://linux-hardware.org/?probe=55102fad5b) | Jul 26, 2023 |
| Gigabyte      | G31M-S2L                    | [5af2ea35ee](https://linux-hardware.org/?probe=5af2ea35ee) | Jul 26, 2023 |
| Acer          | EQ45LM                      | [29e2f587cd](https://linux-hardware.org/?probe=29e2f587cd) | Jul 26, 2023 |
| ASRock        | B85M                        | [d69487eb8d](https://linux-hardware.org/?probe=d69487eb8d) | Jul 26, 2023 |
| ASUSTek       | M5A78L-M LE                 | [3cb7454711](https://linux-hardware.org/?probe=3cb7454711) | Jul 25, 2023 |
| AZW           | U59                         | [fcf46a9025](https://linux-hardware.org/?probe=fcf46a9025) | Jul 25, 2023 |
| Dell          | 0RY206                      | [5f16b7ecda](https://linux-hardware.org/?probe=5f16b7ecda) | Jul 25, 2023 |
| ASRock        | B450M Steel Legend          | [4b9680f094](https://linux-hardware.org/?probe=4b9680f094) | Jul 25, 2023 |
| HP            | 1495                        | [99072e94e8](https://linux-hardware.org/?probe=99072e94e8) | Jul 25, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [0e029ddc2d](https://linux-hardware.org/?probe=0e029ddc2d) | Jul 25, 2023 |
| MSI           | 2A9C                        | [83e6501c96](https://linux-hardware.org/?probe=83e6501c96) | Jul 25, 2023 |
| Acer          | EQ45LM                      | [37f6c76c11](https://linux-hardware.org/?probe=37f6c76c11) | Jul 25, 2023 |
| Gigabyte      | MJPLNBB-00                  | [8f4eb83f05](https://linux-hardware.org/?probe=8f4eb83f05) | Jul 25, 2023 |
| Intel         | DH61WW AAG23116-206         | [64595670db](https://linux-hardware.org/?probe=64595670db) | Jul 25, 2023 |
| ECS           | P43T-A2                     | [a25280247b](https://linux-hardware.org/?probe=a25280247b) | Jul 25, 2023 |
| HP            | 8350                        | [51c4120395](https://linux-hardware.org/?probe=51c4120395) | Jul 25, 2023 |
| HP            | 339A                        | [573fb08afb](https://linux-hardware.org/?probe=573fb08afb) | Jul 25, 2023 |
| HP            | 212B                        | [8e6a290d51](https://linux-hardware.org/?probe=8e6a290d51) | Jul 25, 2023 |
| ASRock        | B450 Pro4                   | [a68492f27e](https://linux-hardware.org/?probe=a68492f27e) | Jul 25, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [5ec24ea9ad](https://linux-hardware.org/?probe=5ec24ea9ad) | Jul 25, 2023 |
| ASUSTek       | P8H61-M LX                  | [9ffd99b082](https://linux-hardware.org/?probe=9ffd99b082) | Jul 25, 2023 |
| HP            | 212A                        | [bd9d43276f](https://linux-hardware.org/?probe=bd9d43276f) | Jul 25, 2023 |
| ASRock        | B450M Pro4 R2.0             | [305e0c0700](https://linux-hardware.org/?probe=305e0c0700) | Jul 25, 2023 |
| HP            | 8719                        | [68870aa596](https://linux-hardware.org/?probe=68870aa596) | Jul 24, 2023 |
| PCWare        | IPMH61R3 8MB                | [dcbde0a01d](https://linux-hardware.org/?probe=dcbde0a01d) | Jul 24, 2023 |
| HP            | 198E                        | [c2f7b19d13](https://linux-hardware.org/?probe=c2f7b19d13) | Jul 24, 2023 |
| Biostar       | H81MHV3 5.0                 | [06e3fae658](https://linux-hardware.org/?probe=06e3fae658) | Jul 24, 2023 |
| HP            | 212B                        | [3e033bf376](https://linux-hardware.org/?probe=3e033bf376) | Jul 24, 2023 |
| MSI           | Z87-G45 GAMING              | [41246e91c0](https://linux-hardware.org/?probe=41246e91c0) | Jul 24, 2023 |
| Biostar       | A68MDE                      | [8ab5498633](https://linux-hardware.org/?probe=8ab5498633) | Jul 24, 2023 |
| Dell          | 0F5C5X A00                  | [e382c4d40c](https://linux-hardware.org/?probe=e382c4d40c) | Jul 23, 2023 |
| Gigabyte      | H61M-DS2                    | [c78c35de44](https://linux-hardware.org/?probe=c78c35de44) | Jul 23, 2023 |
| ASRock        | X670E Steel Legend          | [8744428bf6](https://linux-hardware.org/?probe=8744428bf6) | Jul 23, 2023 |
| ASUSTek       | M5A78L-M LX3                | [8982fa467c](https://linux-hardware.org/?probe=8982fa467c) | Jul 23, 2023 |
| ASUSTek       | NARRA                       | [2c0dc7397a](https://linux-hardware.org/?probe=2c0dc7397a) | Jul 23, 2023 |
| MSI           | Z87-G43                     | [f153badd8c](https://linux-hardware.org/?probe=f153badd8c) | Jul 23, 2023 |
| Dell          | 0VHWTR A02                  | [c5fe12dadd](https://linux-hardware.org/?probe=c5fe12dadd) | Jul 23, 2023 |
| Dell          | 0VD92X A00                  | [675e646d05](https://linux-hardware.org/?probe=675e646d05) | Jul 23, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [5072be5d0f](https://linux-hardware.org/?probe=5072be5d0f) | Jul 22, 2023 |
| ASRock        | B650E Steel Legend WiFi     | [550c33b909](https://linux-hardware.org/?probe=550c33b909) | Jul 22, 2023 |
| ASUSTek       | PRIME Z270-K                | [97aa2f7158](https://linux-hardware.org/?probe=97aa2f7158) | Jul 22, 2023 |
| Gigabyte      | H81M-DS2V                   | [f27670217e](https://linux-hardware.org/?probe=f27670217e) | Jul 22, 2023 |
| ASRock        | 970M Pro3                   | [e359256b4f](https://linux-hardware.org/?probe=e359256b4f) | Jul 22, 2023 |
| MSI           | B85M ECO                    | [d37630f7df](https://linux-hardware.org/?probe=d37630f7df) | Jul 22, 2023 |
| Gigabyte      | B560M DS3H AC               | [326a94245b](https://linux-hardware.org/?probe=326a94245b) | Jul 22, 2023 |
| Intel         | JSL MRD                     | [4c9c765884](https://linux-hardware.org/?probe=4c9c765884) | Jul 21, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [55f5c5bd48](https://linux-hardware.org/?probe=55f5c5bd48) | Jul 21, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [4f00ba88de](https://linux-hardware.org/?probe=4f00ba88de) | Jul 21, 2023 |
| Foxconn       | 2ABF                        | [6a048ba2cc](https://linux-hardware.org/?probe=6a048ba2cc) | Jul 21, 2023 |
| ASUSTek       | H110S2                      | [3e43d97432](https://linux-hardware.org/?probe=3e43d97432) | Jul 21, 2023 |
| MSI           | Z97 PC Mate                 | [a131a7a5fb](https://linux-hardware.org/?probe=a131a7a5fb) | Jul 21, 2023 |
| Gigabyte      | B450M DS3H-CF               | [556e4cd2c9](https://linux-hardware.org/?probe=556e4cd2c9) | Jul 21, 2023 |
| Lenovo        | MAHOBAY NOK                 | [9b6d9b3e96](https://linux-hardware.org/?probe=9b6d9b3e96) | Jul 21, 2023 |
| Acer          | Aspire TC-780               | [c058e8c58e](https://linux-hardware.org/?probe=c058e8c58e) | Jul 20, 2023 |
| Dell          | 0M863N A01                  | [682fc212b6](https://linux-hardware.org/?probe=682fc212b6) | Jul 20, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [08fccc55c8](https://linux-hardware.org/?probe=08fccc55c8) | Jul 20, 2023 |
| ASUSTek       | M11AD                       | [8a8cb2c3e4](https://linux-hardware.org/?probe=8a8cb2c3e4) | Jul 20, 2023 |
| ASRock        | G41C-GS R2.0                | [3ed4a6a897](https://linux-hardware.org/?probe=3ed4a6a897) | Jul 19, 2023 |
| HP            | 8055                        | [5f74df3997](https://linux-hardware.org/?probe=5f74df3997) | Jul 19, 2023 |
| Intel X79     | Unknown                     | [360facd1fb](https://linux-hardware.org/?probe=360facd1fb) | Jul 19, 2023 |
| ASRock        | H510M-HDV R2.0              | [cacf2d88c9](https://linux-hardware.org/?probe=cacf2d88c9) | Jul 19, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [49a085a451](https://linux-hardware.org/?probe=49a085a451) | Jul 18, 2023 |
| ASUSTek       | NARRA2                      | [4d18b60338](https://linux-hardware.org/?probe=4d18b60338) | Jul 18, 2023 |
| ASRock        | X99M Extreme4               | [f799654e45](https://linux-hardware.org/?probe=f799654e45) | Jul 18, 2023 |
| AZW           | Gemini J45                  | [0ed36a4286](https://linux-hardware.org/?probe=0ed36a4286) | Jul 18, 2023 |
| Dell          | 0HD5W2 A00                  | [f4bc253638](https://linux-hardware.org/?probe=f4bc253638) | Jul 17, 2023 |
| Gigabyte      | J1800N-D2H                  | [a62fb79aac](https://linux-hardware.org/?probe=a62fb79aac) | Jul 17, 2023 |
| ASUSTek       | M4A785-M                    | [082165532b](https://linux-hardware.org/?probe=082165532b) | Jul 17, 2023 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | [c527cf56ad](https://linux-hardware.org/?probe=c527cf56ad) | Jul 17, 2023 |
| HP            | 18E8                        | [606aa1f34d](https://linux-hardware.org/?probe=606aa1f34d) | Jul 16, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [fb1a31ec95](https://linux-hardware.org/?probe=fb1a31ec95) | Jul 16, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [87763ca861](https://linux-hardware.org/?probe=87763ca861) | Jul 16, 2023 |
| Gigabyte      | Z490 AORUS PRO AX           | [1b32b611bf](https://linux-hardware.org/?probe=1b32b611bf) | Jul 16, 2023 |
| Dell          | 073MMW A03                  | [f76738403e](https://linux-hardware.org/?probe=f76738403e) | Jul 15, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [81d6c4c3bd](https://linux-hardware.org/?probe=81d6c4c3bd) | Jul 15, 2023 |
| Foxconn       | 2ABF                        | [e302c823fc](https://linux-hardware.org/?probe=e302c823fc) | Jul 13, 2023 |
| MSI           | H510I PRO WIFI              | [23fef6418b](https://linux-hardware.org/?probe=23fef6418b) | Jul 13, 2023 |
| Acer          | Veriton E430G               | [f52d631cce](https://linux-hardware.org/?probe=f52d631cce) | Jul 13, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [6c08fefa24](https://linux-hardware.org/?probe=6c08fefa24) | Jul 13, 2023 |
| ASUSTek       | A55BM-E                     | [4e99483733](https://linux-hardware.org/?probe=4e99483733) | Jul 13, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [e241cdbe45](https://linux-hardware.org/?probe=e241cdbe45) | Jul 12, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [4875c100c1](https://linux-hardware.org/?probe=4875c100c1) | Jul 12, 2023 |
| HP            | 18E8                        | [b892f0dd28](https://linux-hardware.org/?probe=b892f0dd28) | Jul 12, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI      | [d7abb793a4](https://linux-hardware.org/?probe=d7abb793a4) | Jul 12, 2023 |
| ASUSTek       | M5A78L-M LX V2              | [ce55d97846](https://linux-hardware.org/?probe=ce55d97846) | Jul 12, 2023 |
| Dell          | 048DY8 A00                  | [66c586dfe4](https://linux-hardware.org/?probe=66c586dfe4) | Jul 11, 2023 |
| HP            | 89D8 SMVB                   | [68ee3dff51](https://linux-hardware.org/?probe=68ee3dff51) | Jul 11, 2023 |
| Dell          | 0T7D40 A01                  | [1ed238ea9b](https://linux-hardware.org/?probe=1ed238ea9b) | Jul 11, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [7a8f3c985f](https://linux-hardware.org/?probe=7a8f3c985f) | Jul 11, 2023 |
| Gigabyte      | GA-MA770-ES3                | [9af789d1d2](https://linux-hardware.org/?probe=9af789d1d2) | Jul 10, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [b7d5b7b224](https://linux-hardware.org/?probe=b7d5b7b224) | Jul 10, 2023 |
| Unknown       | 1.0                         | [dcf11d8f40](https://linux-hardware.org/?probe=dcf11d8f40) | Jul 10, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| OpenMandriva 4.2    | 2286     | 29.9%   |
| OpenMandriva 4.3    | 2137     | 27.95%  |
| OpenMandriva 23.01  | 917      | 11.99%  |
| OpenMandriva 23.03  | 851      | 11.13%  |
| OpenMandriva 23.08  | 498      | 6.51%   |
| OpenMandriva 4.50   | 409      | 5.35%   |
| OpenMandriva 4.90   | 160      | 2.09%   |
| OpenMandriva 23.09  | 103      | 1.35%   |
| OpenMandriva 23.07  | 58       | 0.76%   |
| OpenMandriva 23.10  | 54       | 0.71%   |
| OpenMandriva 23.90  | 51       | 0.67%   |
| OpenMandriva 23.06  | 49       | 0.64%   |
| OpenMandriva 22.12  | 43       | 0.56%   |
| OpenMandriva 4.1    | 10       | 0.13%   |
| OpenMandriva 23.11  | 7        | 0.09%   |
| OpenMandriva 22.11  | 5        | 0.07%   |
| OpenMandriva 2014.0 | 3        | 0.04%   |
| OpenMandriva 4.0    | 2        | 0.03%   |
| OpenMandriva 5.0    | 1        | 0.01%   |
| OpenMandriva 4.0.1  | 1        | 0.01%   |
| OpenMandriva 22.90  | 1        | 0.01%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| OpenMandriva | 7084     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Desktops | Percent |
|-------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002      | 2219     | 28.73%  |
| 5.16.7-desktop-1omv4003       | 1989     | 25.75%  |
| 6.1.1-desktop-1omv2290        | 832      | 10.77%  |
| 6.2.6-desktop-1omv2390        | 825      | 10.68%  |
| 6.4.11-desktop-1omv2390       | 398      | 5.15%   |
| 5.12.4-desktop-1omv4050       | 206      | 2.67%   |
| 5.16.13-desktop-1omv4003      | 176      | 2.28%   |
| 5.18.12-desktop-3omv4090      | 149      | 1.93%   |
| 6.4.8-desktop-2omv2390        | 117      | 1.51%   |
| 6.3.5-desktop-3omv2390        | 96       | 1.24%   |
| 5.11.12-desktop-1omv4002      | 93       | 1.2%    |
| 5.19.5-desktop-1omv4090       | 81       | 1.05%   |
| 6.1.4-desktop-1omv2301        | 77       | 1%      |
| 6.5.5-desktop-1omv2390        | 57       | 0.74%   |
| 5.19.12-desktop-2omv4090      | 54       | 0.7%    |
| 6.0.10-desktop-2omv22090      | 42       | 0.54%   |
| 6.5.3-desktop-1omv2390        | 34       | 0.44%   |
| 6.5.0-desktop-1omv2390        | 32       | 0.41%   |
| 5.14.7-desktop-1omv4050       | 22       | 0.28%   |
| 6.2.2-desktop-1omv2390        | 20       | 0.26%   |
| 6.5.1-desktop-1omv2390        | 16       | 0.21%   |
| 6.5.2-desktop-1omv2390        | 15       | 0.19%   |
| 6.2.1-desktop-1omv2390        | 11       | 0.14%   |
| 5.19.11-desktop-2omv4090      | 10       | 0.13%   |
| 5.12.7-desktop-1omv4003       | 10       | 0.13%   |
| 5.5.12-desktop-1omv4001       | 9        | 0.12%   |
| 6.1.2-desktop-1omv2301        | 8        | 0.1%    |
| 5.14.14-desktop-1omv4050      | 8        | 0.1%    |
| 6.6.0-desktop-1omv2390        | 7        | 0.09%   |
| 6.2.0-desktop-0.rc2.1omv2301  | 5        | 0.06%   |
| 6.1.11-desktop-1omv2390       | 5        | 0.06%   |
| 5.11.0-desktop-clang-1omv4002 | 5        | 0.06%   |
| 5.10.13-desktop-1omv4002      | 5        | 0.06%   |
| 5.17.1-desktop-2omv4050       | 4        | 0.05%   |
| 5.16.3-desktop-2omv4050       | 4        | 0.05%   |
| 6.3.3-desktop-2omv2390        | 3        | 0.04%   |
| 6.2.8-desktop-1omv2390        | 3        | 0.04%   |
| 6.1.9-desktop-1omv2390        | 3        | 0.04%   |
| 5.19.0-desktop-1omv4090       | 3        | 0.04%   |
| 6.6.0-desktop-0.rc3.1omv2390  | 2        | 0.03%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.14 | 2219     | 28.73%  |
| 5.16.7  | 1990     | 25.77%  |
| 6.1.1   | 832      | 10.77%  |
| 6.2.6   | 825      | 10.68%  |
| 6.4.11  | 398      | 5.15%   |
| 5.12.4  | 206      | 2.67%   |
| 5.16.13 | 177      | 2.29%   |
| 5.18.12 | 149      | 1.93%   |
| 6.4.8   | 117      | 1.51%   |
| 6.3.5   | 96       | 1.24%   |
| 5.11.12 | 93       | 1.2%    |
| 5.19.5  | 81       | 1.05%   |
| 6.1.4   | 79       | 1.02%   |
| 6.5.5   | 58       | 0.75%   |
| 5.19.12 | 55       | 0.71%   |
| 6.0.10  | 42       | 0.54%   |
| 6.5.3   | 34       | 0.44%   |
| 6.5.0   | 33       | 0.43%   |
| 5.14.7  | 22       | 0.28%   |
| 6.2.2   | 20       | 0.26%   |
| 6.5.1   | 16       | 0.21%   |
| 6.5.2   | 15       | 0.19%   |
| 5.12.7  | 12       | 0.16%   |
| 6.2.1   | 11       | 0.14%   |
| 5.19.11 | 11       | 0.14%   |
| 6.6.0   | 9        | 0.12%   |
| 5.5.12  | 9        | 0.12%   |
| 6.1.2   | 8        | 0.1%    |
| 5.14.14 | 8        | 0.1%    |
| 6.2.0   | 6        | 0.08%   |
| 6.1.11  | 5        | 0.06%   |
| 5.11.0  | 5        | 0.06%   |
| 5.10.13 | 5        | 0.06%   |
| 5.17.1  | 4        | 0.05%   |
| 5.16.3  | 4        | 0.05%   |
| 6.3.3   | 3        | 0.04%   |
| 6.3.0   | 3        | 0.04%   |
| 6.2.8   | 3        | 0.04%   |
| 6.1.9   | 3        | 0.04%   |
| 6.0.9   | 3        | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 2228     | 29.01%  |
| 5.16    | 2137     | 27.82%  |
| 6.1     | 927      | 12.07%  |
| 6.2     | 866      | 11.27%  |
| 6.4     | 519      | 6.76%   |
| 5.12    | 222      | 2.89%   |
| 6.5     | 157      | 2.04%   |
| 5.18    | 154      | 2%      |
| 5.19    | 152      | 1.98%   |
| 6.3     | 103      | 1.34%   |
| 5.11    | 100      | 1.3%    |
| 6.0     | 50       | 0.65%   |
| 5.14    | 31       | 0.4%    |
| 5.5     | 10       | 0.13%   |
| 6.6     | 9        | 0.12%   |
| 5.17    | 6        | 0.08%   |
| 5.13    | 3        | 0.04%   |
| 4.1     | 3        | 0.04%   |
| 5.1     | 2        | 0.03%   |
| 5.8     | 1        | 0.01%   |
| 5.3     | 1        | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 7084     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| KDE5     | 6703     | 93.54%  |
| GNOME    | 282      | 3.94%   |
| LXQt     | 123      | 1.72%   |
| Unknown  | 32       | 0.45%   |
| Cinnamon | 10       | 0.14%   |
| Budgie   | 10       | 0.14%   |
| XFCE     | 4        | 0.06%   |
| KDE4     | 1        | 0.01%   |
| KDE      | 1        | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 6329     | 87.34%  |
| Wayland | 914      | 12.61%  |
| Unknown | 3        | 0.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 6828     | 95.8%   |
| GDM     | 283      | 3.97%   |
| LightDM | 9        | 0.13%   |
| Unknown | 6        | 0.08%   |
| KDM     | 1        | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 3802     | 52.18%  |
| de_DE   | 567      | 7.78%   |
| ru_RU   | 520      | 7.14%   |
| fr_FR   | 411      | 5.64%   |
| pt_BR   | 330      | 4.53%   |
| pl_PL   | 224      | 3.07%   |
| it_IT   | 198      | 2.72%   |
| en_GB   | 174      | 2.39%   |
| es_ES   | 160      | 2.2%    |
| cs_CZ   | 80       | 1.1%    |
| es_MX   | 70       | 0.96%   |
| hu_HU   | 64       | 0.88%   |
| es_AR   | 64       | 0.88%   |
| de_AT   | 59       | 0.81%   |
| en_CA   | 56       | 0.77%   |
| en_AU   | 43       | 0.59%   |
| nl_NL   | 39       | 0.54%   |
| fr_CA   | 32       | 0.44%   |
| en_IN   | 30       | 0.41%   |
| de_CH   | 29       | 0.4%    |
| es_VE   | 27       | 0.37%   |
| es_CO   | 22       | 0.3%    |
| tr_TR   | 21       | 0.29%   |
| ru_UA   | 19       | 0.26%   |
| pt_PT   | 19       | 0.26%   |
| fr_BE   | 18       | 0.25%   |
| da_DK   | 16       | 0.22%   |
| es_CL   | 15       | 0.21%   |
| Unknown | 13       | 0.18%   |
| ro_RO   | 11       | 0.15%   |
| nl_BE   | 11       | 0.15%   |
| en_ZA   | 10       | 0.14%   |
| en_HK   | 10       | 0.14%   |
| es_UY   | 9        | 0.12%   |
| uk_UA   | 8        | 0.11%   |
| ja_JP   | 8        | 0.11%   |
| es_PE   | 8        | 0.11%   |
| en_IL   | 8        | 0.11%   |
| nb_NO   | 5        | 0.07%   |
| es_SV   | 5        | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 3960     | 55.32%  |
| EFI  | 3198     | 44.68%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Overlay  | 5307     | 71.03%  |
| Ext4     | 1966     | 26.31%  |
| Btrfs    | 120      | 1.61%   |
| Xfs      | 32       | 0.43%   |
| F2fs     | 15       | 0.2%    |
| Jfs      | 9        | 0.12%   |
| Ext3     | 9        | 0.12%   |
| Reiserfs | 6        | 0.08%   |
| Unknown  | 4        | 0.05%   |
| Ext2     | 3        | 0.04%   |
| Tmpfs    | 1        | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 4629     | 64.21%  |
| MBR     | 2550     | 35.37%  |
| Unknown | 30       | 0.42%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 4376     | 60.23%  |
| No        | 2889     | 39.77%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 3825     | 53.15%  |
| No        | 3372     | 46.85%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 1682     | 23.74%  |
| Gigabyte Technology                  | 1237     | 17.46%  |
| MSI                                  | 772      | 10.9%   |
| ASRock                               | 652      | 9.2%    |
| Hewlett-Packard                      | 596      | 8.41%   |
| Dell                                 | 557      | 7.86%   |
| Lenovo                               | 281      | 3.97%   |
| Intel                                | 215      | 3.04%   |
| Acer                                 | 178      | 2.51%   |
| Fujitsu                              | 102      | 1.44%   |
| Foxconn                              | 98       | 1.38%   |
| Biostar                              | 93       | 1.31%   |
| Pegatron                             | 85       | 1.2%    |
| ECS                                  | 60       | 0.85%   |
| Unknown                              | 55       | 0.78%   |
| Medion                               | 52       | 0.73%   |
| Positivo                             | 25       | 0.35%   |
| AZW                                  | 22       | 0.31%   |
| BESSTAR Tech                         | 20       | 0.28%   |
| Fujitsu Siemens                      | 19       | 0.27%   |
| PCWare                               | 17       | 0.24%   |
| Shuttle                              | 15       | 0.21%   |
| Packard Bell                         | 13       | 0.18%   |
| MACHINIST                            | 10       | 0.14%   |
| Alienware                            | 10       | 0.14%   |
| Supermicro                           | 9        | 0.13%   |
| OEM                                  | 9        | 0.13%   |
| Huanan                               | 9        | 0.13%   |
| Gateway                              | 9        | 0.13%   |
| Apple                                | 8        | 0.11%   |
| Semp Toshiba                         | 7        | 0.1%    |
| Itautec                              | 7        | 0.1%    |
| Inventec                             | 7        | 0.1%    |
| Shenzhen Meigao Electronic Equipment | 6        | 0.08%   |
| eMachines                            | 6        | 0.08%   |
| AMD                                  | 5        | 0.07%   |
| Wistron                              | 4        | 0.06%   |
| Philco                               | 4        | 0.06%   |
| MouseComputer                        | 4        | 0.06%   |
| ABIT                                 | 4        | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| ASUS All Series             | 138      | 1.95%   |
| Unknown                     | 62       | 0.88%   |
| Dell OptiPlex 7010          | 54       | 0.76%   |
| Dell OptiPlex 780           | 40       | 0.56%   |
| ASUS PRIME A320M-K          | 33       | 0.47%   |
| Intel H61                   | 32       | 0.45%   |
| Dell OptiPlex 9020          | 28       | 0.4%    |
| Gigabyte H410M H V3         | 27       | 0.38%   |
| Dell OptiPlex 3020          | 26       | 0.37%   |
| HP EliteDesk 800 G1 SFF     | 25       | 0.35%   |
| MSI MS-7817                 | 24       | 0.34%   |
| Gigabyte B450M DS3H         | 24       | 0.34%   |
| Gigabyte 970A-DS3P          | 24       | 0.34%   |
| MSI MS-7721                 | 23       | 0.32%   |
| HP Compaq Pro 6300 SFF      | 23       | 0.32%   |
| ASUS TUF Gaming X570-PLUS   | 22       | 0.31%   |
| ASUS PRIME B450M-A          | 22       | 0.31%   |
| MSI MS-7C37                 | 21       | 0.3%    |
| MSI MS-7C02                 | 21       | 0.3%    |
| ASUS SABERTOOTH Z77         | 21       | 0.3%    |
| ASUS M5A78L-M/USB3          | 21       | 0.3%    |
| Gigabyte A320M-S2H          | 20       | 0.28%   |
| Dell OptiPlex 790           | 20       | 0.28%   |
| MSI MS-7C91                 | 19       | 0.27%   |
| HP Compaq 8200 Elite SFF PC | 19       | 0.27%   |
| MSI MS-7C56                 | 17       | 0.24%   |
| MSI MS-7B86                 | 17       | 0.24%   |
| Dell OptiPlex 380           | 17       | 0.24%   |
| ASUS TUF Gaming B550-PLUS   | 17       | 0.24%   |
| ASUS PRIME B450M-A II       | 17       | 0.24%   |
| MSI MS-7C52                 | 16       | 0.23%   |
| MSI MS-7B79                 | 16       | 0.23%   |
| MSI MS-7A38                 | 16       | 0.23%   |
| MSI MS-7693                 | 16       | 0.23%   |
| Gigabyte GA-78LMT-USB3 6.0  | 16       | 0.23%   |
| Gigabyte G31M-ES2L          | 16       | 0.23%   |
| ASUS M5A97 R2.0             | 16       | 0.23%   |
| ASRock B450M Pro4           | 16       | 0.23%   |
| HP Compaq Elite 8300 SFF    | 15       | 0.21%   |
| Gigabyte B75M-D3H           | 15       | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 378      | 5.34%   |
| ASUS PRIME             | 321      | 4.53%   |
| HP Compaq              | 210      | 2.96%   |
| Lenovo ThinkCentre     | 180      | 2.54%   |
| ASUS All               | 138      | 1.95%   |
| ASUS ROG               | 121      | 1.71%   |
| ASUS TUF               | 112      | 1.58%   |
| Acer Aspire            | 109      | 1.54%   |
| HP EliteDesk           | 99       | 1.4%    |
| Fujitsu ESPRIMO        | 87       | 1.23%   |
| ASUS M5A78L-M          | 75       | 1.06%   |
| HP ProDesk             | 71       | 1%      |
| Unknown                | 62       | 0.88%   |
| Gigabyte B450M         | 56       | 0.79%   |
| Dell Precision         | 54       | 0.76%   |
| Acer Veriton           | 54       | 0.76%   |
| Dell Inspiron          | 48       | 0.68%   |
| ASUS P8H61-M           | 46       | 0.65%   |
| Dell Vostro            | 42       | 0.59%   |
| HP Pavilion            | 41       | 0.58%   |
| ASUS SABERTOOTH        | 40       | 0.56%   |
| Lenovo IdeaCentre      | 39       | 0.55%   |
| Gigabyte B450          | 39       | 0.55%   |
| Gigabyte X570          | 38       | 0.54%   |
| Gigabyte H410M         | 38       | 0.54%   |
| ASUS M5A97             | 36       | 0.51%   |
| Intel H61              | 34       | 0.48%   |
| Gigabyte GA-78LMT-USB3 | 33       | 0.47%   |
| ASRock B450M           | 33       | 0.47%   |
| ASUS P8Z77-V           | 32       | 0.45%   |
| Gigabyte A320M-S2H     | 27       | 0.38%   |
| Gigabyte B550          | 26       | 0.37%   |
| ASUS P5G41T-M          | 26       | 0.37%   |
| MSI MS-7817            | 24       | 0.34%   |
| Gigabyte 970A-DS3P     | 24       | 0.34%   |
| ASUS P5K               | 24       | 0.34%   |
| MSI MS-7721            | 23       | 0.32%   |
| Gigabyte B550M         | 23       | 0.32%   |
| ASRock B450            | 23       | 0.32%   |
| MSI MS-7C37            | 21       | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 774      | 10.93%  |
| 2013 | 636      | 8.98%   |
| 2018 | 626      | 8.84%   |
| 2011 | 546      | 7.71%   |
| 2014 | 503      | 7.1%    |
| 2020 | 457      | 6.45%   |
| 2010 | 448      | 6.32%   |
| 2009 | 428      | 6.04%   |
| 2019 | 409      | 5.77%   |
| 2017 | 396      | 5.59%   |
| 2021 | 363      | 5.12%   |
| 2008 | 341      | 4.81%   |
| 2015 | 308      | 4.35%   |
| 2016 | 292      | 4.12%   |
| 2007 | 224      | 3.16%   |
| 2006 | 141      | 1.99%   |
| 2022 | 126      | 1.78%   |
| 2023 | 36       | 0.51%   |
| 2005 | 25       | 0.35%   |
| 2004 | 5        | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 7084     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 7084     | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 7082     | 99.97%  |
| Yes  | 2        | 0.03%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 1610     | 22.39%  |
| 16.01-24.0      | 1542     | 21.45%  |
| 4.01-8.0        | 1413     | 19.65%  |
| 3.01-4.0        | 1326     | 18.44%  |
| 32.01-64.0      | 678      | 9.43%   |
| 1.01-2.0        | 221      | 3.07%   |
| 24.01-32.0      | 154      | 2.14%   |
| 64.01-256.0     | 150      | 2.09%   |
| 2.01-3.0        | 77       | 1.07%   |
| 0.51-1.0        | 13       | 0.18%   |
| More than 256.0 | 6        | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 5001     | 67.36%  |
| 0.51-1.0   | 1026     | 13.82%  |
| 2.01-3.0   | 996      | 13.42%  |
| 0.01-0.5   | 189      | 2.55%   |
| 3.01-4.0   | 140      | 1.89%   |
| 4.01-8.0   | 53       | 0.71%   |
| 8.01-16.0  | 15       | 0.2%    |
| 16.01-24.0 | 2        | 0.03%   |
| 32.01-64.0 | 1        | 0.01%   |
| 24.01-32.0 | 1        | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 3104     | 42.64%  |
| 2      | 1949     | 26.78%  |
| 3      | 1027     | 14.11%  |
| 4      | 578      | 7.94%   |
| 5      | 256      | 3.52%   |
| 0      | 146      | 2.01%   |
| 6      | 111      | 1.52%   |
| 7      | 45       | 0.62%   |
| 8      | 32       | 0.44%   |
| 9      | 10       | 0.14%   |
| 10     | 7        | 0.1%    |
| 13     | 4        | 0.05%   |
| 12     | 3        | 0.04%   |
| 11     | 3        | 0.04%   |
| 15     | 2        | 0.03%   |
| 18     | 1        | 0.01%   |
| 17     | 1        | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 4090     | 57.27%  |
| No        | 3051     | 42.73%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 7009     | 98.94%  |
| No        | 75       | 1.06%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 4581     | 64.11%  |
| Yes       | 2564     | 35.89%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 5462     | 76.52%  |
| Yes       | 1676     | 23.48%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 901      | 12.7%   |
| Germany     | 801      | 11.29%  |
| Russia      | 644      | 9.08%   |
| France      | 507      | 7.15%   |
| Brazil      | 505      | 7.12%   |
| Poland      | 333      | 4.69%   |
| Italy       | 313      | 4.41%   |
| UK          | 226      | 3.19%   |
| Canada      | 226      | 3.19%   |
| Spain       | 219      | 3.09%   |
| Australia   | 126      | 1.78%   |
| Mexico      | 108      | 1.52%   |
| Hungary     | 101      | 1.42%   |
| Netherlands | 99       | 1.4%    |
| Czechia     | 98       | 1.38%   |
| Japan       | 92       | 1.3%    |
| India       | 88       | 1.24%   |
| Argentina   | 84       | 1.18%   |
| Ukraine     | 82       | 1.16%   |
| Austria     | 82       | 1.16%   |
| Finland     | 78       | 1.1%    |
| Romania     | 69       | 0.97%   |
| Switzerland | 56       | 0.79%   |
| Belgium     | 52       | 0.73%   |
| Serbia      | 51       | 0.72%   |
| Sweden      | 50       | 0.7%    |
| Greece      | 47       | 0.66%   |
| Portugal    | 46       | 0.65%   |
| Indonesia   | 44       | 0.62%   |
| Slovakia    | 43       | 0.61%   |
| Turkey      | 38       | 0.54%   |
| Venezuela   | 37       | 0.52%   |
| Israel      | 34       | 0.48%   |
| Bulgaria    | 34       | 0.48%   |
| Malaysia    | 32       | 0.45%   |
| Colombia    | 32       | 0.45%   |
| Denmark     | 31       | 0.44%   |
| Norway      | 29       | 0.41%   |
| China       | 29       | 0.41%   |
| Thailand    | 28       | 0.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Moscow           | 119      | 1.61%   |
| Sao Paulo        | 60       | 0.81%   |
| Berlin           | 55       | 0.75%   |
| Warsaw           | 48       | 0.65%   |
| St Petersburg    | 43       | 0.58%   |
| Milan            | 43       | 0.58%   |
| Rio de Janeiro   | 41       | 0.56%   |
| Vienna           | 39       | 0.53%   |
| Paris            | 39       | 0.53%   |
| Mexico City      | 34       | 0.46%   |
| Rome             | 32       | 0.43%   |
| Helsinki         | 31       | 0.42%   |
| Melbourne        | 29       | 0.39%   |
| Sydney           | 28       | 0.38%   |
| Hamburg          | 27       | 0.37%   |
| Budapest         | 27       | 0.37%   |
| Nizhniy Novgorod | 25       | 0.34%   |
| Madrid           | 25       | 0.34%   |
| Munich           | 22       | 0.3%    |
| Montreal         | 22       | 0.3%    |
| Gonikoppal       | 22       | 0.3%    |
| Athens           | 22       | 0.3%    |
| Yekaterinburg    | 21       | 0.28%   |
| Belgrade         | 21       | 0.28%   |
| Prague           | 20       | 0.27%   |
| Porto Alegre     | 20       | 0.27%   |
| Novosibirsk      | 19       | 0.26%   |
| Strzyzow         | 18       | 0.24%   |
| Brisbane         | 18       | 0.24%   |
| Nuremberg        | 17       | 0.23%   |
| Krakow           | 17       | 0.23%   |
| Cairo            | 17       | 0.23%   |
| San Jose         | 16       | 0.22%   |
| Buenos Aires     | 16       | 0.22%   |
| Perm             | 15       | 0.2%    |
| Chelyabinsk      | 15       | 0.2%    |
| Barcelona        | 15       | 0.2%    |
| Stuttgart        | 14       | 0.19%   |
| Montevideo       | 14       | 0.19%   |
| Marseille        | 14       | 0.19%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2488     | 3519   | 19.91%  |
| Seagate             | 2326     | 3159   | 18.62%  |
| Samsung Electronics | 1509     | 2175   | 12.08%  |
| Kingston            | 798      | 974    | 6.39%   |
| Toshiba             | 712      | 867    | 5.7%    |
| Crucial             | 617      | 785    | 4.94%   |
| Hitachi             | 459      | 532    | 3.67%   |
| SanDisk             | 437      | 533    | 3.5%    |
| A-DATA Technology   | 286      | 330    | 2.29%   |
| China               | 191      | 219    | 1.53%   |
| Unknown             | 162      | 217    | 1.3%    |
| SPCC                | 128      | 153    | 1.02%   |
| Intel               | 128      | 148    | 1.02%   |
| Maxtor              | 123      | 148    | 0.98%   |
| PNY                 | 120      | 145    | 0.96%   |
| Patriot             | 109      | 120    | 0.87%   |
| Intenso             | 94       | 110    | 0.75%   |
| HGST                | 92       | 126    | 0.74%   |
| GOODRAM             | 87       | 105    | 0.7%    |
| Apacer              | 73       | 82     | 0.58%   |
| OCZ                 | 68       | 74     | 0.54%   |
| Phison              | 64       | 86     | 0.51%   |
| Corsair             | 59       | 64     | 0.47%   |
| Transcend           | 56       | 63     | 0.45%   |
| Team                | 51       | 54     | 0.41%   |
| Gigabyte Technology | 50       | 59     | 0.4%    |
| Netac               | 49       | 54     | 0.39%   |
| JMicron Technology  | 46       | 50     | 0.37%   |
| SK hynix            | 45       | 50     | 0.36%   |
| Unknown             | 45       | 47     | 0.36%   |
| Micron Technology   | 44       | 49     | 0.35%   |
| Hewlett-Packard     | 43       | 50     | 0.34%   |
| Silicon Motion      | 41       | 44     | 0.33%   |
| KingSpec            | 33       | 34     | 0.26%   |
| XPG                 | 32       | 44     | 0.26%   |
| Lexar               | 32       | 33     | 0.26%   |
| ASMT                | 29       | 31     | 0.23%   |
| KIOXIA-EXCERIA      | 26       | 29     | 0.21%   |
| Plextor             | 22       | 27     | 0.18%   |
| Fujitsu             | 21       | 23     | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 227      | 1.58%   |
| Kingston SA400S37240G 240GB SSD  | 187      | 1.3%    |
| Seagate ST1000DM010-2EP102 1TB   | 186      | 1.3%    |
| Toshiba DT01ACA100 1TB           | 144      | 1%      |
| Seagate ST2000DM008-2FR102 2TB   | 121      | 0.84%   |
| WDC WD10EZEX-08WN4A0 1TB         | 107      | 0.75%   |
| Toshiba DT01ACA050 500GB         | 103      | 0.72%   |
| Kingston SA400S37480G 480GB SSD  | 96       | 0.67%   |
| Seagate ST3500418AS 500GB        | 93       | 0.65%   |
| Samsung SSD 860 EVO 500GB        | 92       | 0.64%   |
| Crucial CT500MX500SSD1 500GB     | 91       | 0.63%   |
| Kingston SA400S37120G 120GB SSD  | 87       | 0.61%   |
| Kingston SV300S37A120G 120GB SSD | 85       | 0.59%   |
| Crucial CT240BX500SSD1 240GB     | 83       | 0.58%   |
| Seagate ST1000DM003-1ER162 1TB   | 81       | 0.56%   |
| Unknown SD/MMC/MS PRO 16GB       | 77       | 0.54%   |
| Samsung SSD 850 EVO 250GB        | 76       | 0.53%   |
| Samsung SSD 860 EVO 250GB        | 75       | 0.52%   |
| Toshiba HDWD110 1TB              | 72       | 0.5%    |
| Crucial CT1000MX500SSD1 1TB      | 67       | 0.47%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 62       | 0.43%   |
| Seagate ST1000DM003-1CH162 1TB   | 61       | 0.42%   |
| WDC WD10EZEX-00BN5A0 1TB         | 60       | 0.42%   |
| Samsung SSD 850 EVO 500GB        | 59       | 0.41%   |
| Samsung SSD 970 EVO Plus 500GB   | 58       | 0.4%    |
| Toshiba DT01ACA200 2TB           | 57       | 0.4%    |
| Seagate ST3500413AS 500GB        | 55       | 0.38%   |
| Seagate ST1000DM003-1SB102 1TB   | 55       | 0.38%   |
| Crucial CT480BX500SSD1 480GB     | 55       | 0.38%   |
| Seagate ST2000DM001-1ER164 2TB   | 54       | 0.38%   |
| Seagate ST2000DM001-1CH164 2TB   | 48       | 0.33%   |
| Samsung SSD 970 EVO Plus 1TB     | 47       | 0.33%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 46       | 0.32%   |
| Samsung SSD 860 EVO 1TB          | 46       | 0.32%   |
| Unknown                          | 45       | 0.31%   |
| Seagate ST31000528AS 1TB         | 44       | 0.31%   |
| Samsung HD502HJ 500GB            | 44       | 0.31%   |
| Seagate ST2000DM006-2DM164 2TB   | 42       | 0.29%   |
| Samsung HD103SJ 1TB              | 41       | 0.29%   |
| SanDisk SSD PLUS 1000GB          | 40       | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 2297     | 3103   | 35.38%  |
| WDC                 | 2162     | 2942   | 33.3%   |
| Toshiba             | 651      | 791    | 10.03%  |
| Samsung Electronics | 469      | 553    | 7.22%   |
| Hitachi             | 459      | 532    | 7.07%   |
| Maxtor              | 120      | 144    | 1.85%   |
| HGST                | 92       | 126    | 1.42%   |
| Unknown             | 81       | 86     | 1.25%   |
| Fujitsu             | 20       | 22     | 0.31%   |
| Hewlett-Packard     | 14       | 15     | 0.22%   |
| Intenso             | 11       | 11     | 0.17%   |
| Apple               | 11       | 11     | 0.17%   |
| USB3.0              | 10       | 10     | 0.15%   |
| External            | 9        | 9      | 0.14%   |
| WD MediaMax         | 8        | 13     | 0.12%   |
| ExcelStor           | 7        | 7      | 0.11%   |
| IBM/Hitachi         | 6        | 7      | 0.09%   |
| Quantum             | 5        | 5      | 0.08%   |
| HPE                 | 5        | 7      | 0.08%   |
| Unknown             | 5        | 5      | 0.08%   |
| Initio              | 4        | 4      | 0.06%   |
| USB                 | 3        | 4      | 0.05%   |
| StoreJet            | 3        | 3      | 0.05%   |
| SSK                 | 3        | 4      | 0.05%   |
| Min Yi U            | 3        | 3      | 0.05%   |
| Magnetic Data       | 3        | 3      | 0.05%   |
| HGST HTS            | 3        | 3      | 0.05%   |
| ASMT                | 3        | 4      | 0.05%   |
| SABRENT             | 2        | 4      | 0.03%   |
| RSH-319             | 2        | 2      | 0.03%   |
| MDT                 | 2        | 2      | 0.03%   |
| JMicron Technology  | 2        | 2      | 0.03%   |
| China               | 2        | 3      | 0.03%   |
| ASMedia             | 2        | 2      | 0.03%   |
| USB 3.0             | 1        | 2      | 0.02%   |
| TPH00800640GB       | 1        | 1      | 0.02%   |
| SAGE                | 1        | 1      | 0.02%   |
| RSH-339             | 1        | 1      | 0.02%   |
| Promise             | 1        | 1      | 0.02%   |
| MaxDigital          | 1        | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 753      | 1043   | 16.26%  |
| Kingston            | 665      | 800    | 14.36%  |
| Crucial             | 506      | 630    | 10.93%  |
| SanDisk             | 371      | 451    | 8.01%   |
| WDC                 | 310      | 378    | 6.69%   |
| A-DATA Technology   | 242      | 273    | 5.23%   |
| China               | 189      | 216    | 4.08%   |
| PNY                 | 110      | 133    | 2.38%   |
| SPCC                | 102      | 121    | 2.2%    |
| Patriot             | 92       | 103    | 1.99%   |
| GOODRAM             | 84       | 99     | 1.81%   |
| Intenso             | 81       | 95     | 1.75%   |
| Intel               | 72       | 79     | 1.55%   |
| OCZ                 | 68       | 74     | 1.47%   |
| Apacer              | 63       | 69     | 1.36%   |
| Toshiba             | 54       | 60     | 1.17%   |
| Transcend           | 48       | 54     | 1.04%   |
| Team                | 43       | 45     | 0.93%   |
| Micron Technology   | 38       | 43     | 0.82%   |
| Netac               | 36       | 40     | 0.78%   |
| Unknown             | 36       | 38     | 0.78%   |
| KingSpec            | 32       | 33     | 0.69%   |
| Gigabyte Technology | 30       | 32     | 0.65%   |
| Corsair             | 27       | 29     | 0.58%   |
| ASMT                | 26       | 27     | 0.56%   |
| Lexar               | 19       | 20     | 0.41%   |
| Hewlett-Packard     | 19       | 22     | 0.41%   |
| XrayDisk            | 18       | 18     | 0.39%   |
| KIOXIA-EXCERIA      | 18       | 19     | 0.39%   |
| SK hynix            | 17       | 18     | 0.37%   |
| LITEON              | 17       | 17     | 0.37%   |
| SABRENT             | 16       | 19     | 0.35%   |
| KingFast            | 16       | 18     | 0.35%   |
| Unknown             | 15       | 16     | 0.32%   |
| Plextor             | 15       | 17     | 0.32%   |
| Leven               | 13       | 13     | 0.28%   |
| Emtec               | 13       | 14     | 0.28%   |
| Verbatim            | 12       | 12     | 0.26%   |
| TO Exter            | 11       | 11     | 0.24%   |
| Seagate             | 11       | 14     | 0.24%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 5018     | 8462   | 49.49%  |
| SSD     | 3607     | 5565   | 35.57%  |
| NVMe    | 1365     | 1950   | 13.46%  |
| Unknown | 123      | 174    | 1.21%   |
| MMC     | 27       | 29     | 0.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 6589     | 13499  | 77.33%  |
| NVMe | 1335     | 1898   | 15.67%  |
| SAS  | 570      | 754    | 6.69%   |
| MMC  | 27       | 29     | 0.32%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| 0.01-0.5        | 5201     | 8327   | 56.05%  |
| 0.51-1.0        | 2577     | 3675   | 27.77%  |
| 1.01-2.0        | 876      | 1148   | 9.44%   |
| 2.01-3.0        | 235      | 314    | 2.53%   |
| 3.01-4.0        | 207      | 296    | 2.23%   |
| 4.01-10.0       | 140      | 216    | 1.51%   |
| 10.01-20.0      | 41       | 48     | 0.44%   |
| More than 100.0 | 1        | 2      | 0.01%   |
| 20.01-50.0      | 1        | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 3265     | 43.22%  |
| 101-250        | 1077     | 14.26%  |
| Unknown        | 1015     | 13.44%  |
| 251-500        | 722      | 9.56%   |
| 501-1000       | 453      | 6%      |
| 51-100         | 357      | 4.73%   |
| 21-50          | 306      | 4.05%   |
| 1001-2000      | 205      | 2.71%   |
| More than 3000 | 82       | 1.09%   |
| 2001-3000      | 72       | 0.95%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 5423     | 73.28%  |
| Unknown        | 1015     | 13.72%  |
| 21-50          | 239      | 3.23%   |
| 101-250        | 192      | 2.59%   |
| 51-100         | 159      | 2.15%   |
| 251-500        | 148      | 2%      |
| 501-1000       | 122      | 1.65%   |
| 1001-2000      | 54       | 0.73%   |
| More than 3000 | 26       | 0.35%   |
| 2001-3000      | 21       | 0.28%   |
| 0              | 1        | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 97       | 106    | 3.61%   |
| Seagate ST3500418AS 500GB         | 44       | 51     | 1.64%   |
| Toshiba DT01ACA100 1TB            | 24       | 29     | 0.89%   |
| Kingston SV300S37A120G 120GB SSD  | 24       | 26     | 0.89%   |
| Seagate ST1000DM010-2EP102 1TB    | 22       | 26     | 0.82%   |
| WDC WD5000AAKX-75U6AA0 500GB      | 21       | 21     | 0.78%   |
| WDC WD5000AAKX-001CA0 500GB       | 21       | 24     | 0.78%   |
| Toshiba DT01ACA050 500GB          | 21       | 23     | 0.78%   |
| Seagate ST31000528AS 1TB          | 21       | 23     | 0.78%   |
| Seagate ST31000524AS 1TB          | 21       | 21     | 0.78%   |
| Seagate ST3500413AS 500GB         | 19       | 21     | 0.71%   |
| Samsung Electronics HD322HJ 320GB | 19       | 21     | 0.71%   |
| Seagate ST9500325AS 500GB         | 18       | 19     | 0.67%   |
| Samsung Electronics HD161HJ 160GB | 17       | 17     | 0.63%   |
| Hitachi HDS721050CLA362 500GB     | 17       | 20     | 0.63%   |
| Seagate ST2000DM001-1CH164 2TB    | 16       | 16     | 0.6%    |
| Seagate ST1000DM003-9YN162 1TB    | 16       | 17     | 0.6%    |
| Samsung Electronics HD502HJ 500GB | 16       | 16     | 0.6%    |
| Samsung Electronics HD103SJ 1TB   | 16       | 17     | 0.6%    |
| Seagate ST3320418AS 320GB         | 15       | 18     | 0.56%   |
| Samsung Electronics HD103SI 1TB   | 14       | 14     | 0.52%   |
| Hitachi HDS721010CLA332 1TB       | 14       | 14     | 0.52%   |
| WDC WD10EARS-00Y5B1 1TB           | 13       | 16     | 0.48%   |
| Samsung Electronics HD103UJ 1TB   | 13       | 16     | 0.48%   |
| Maxtor STM3250310AS 250GB         | 13       | 13     | 0.48%   |
| Seagate ST3250318AS 250GB         | 12       | 12     | 0.45%   |
| Seagate ST250DM000-1BD141 250GB   | 12       | 12     | 0.45%   |
| Seagate ST1000DM003-1CH162 1TB    | 12       | 14     | 0.45%   |
| WDC WD5000AAKS-00V1A0 500GB       | 11       | 12     | 0.41%   |
| WDC WD5000AADS-00S9B0 500GB       | 11       | 12     | 0.41%   |
| WDC WD3200AAJS-00L7A0 320GB       | 11       | 11     | 0.41%   |
| Seagate ST2000DL003-9VT166 2TB    | 11       | 13     | 0.41%   |
| Hitachi HDS721680PLA380 82GB      | 11       | 13     | 0.41%   |
| WDC WDS240G2G0A-00JH30 240GB SSD  | 10       | 12     | 0.37%   |
| WDC WD5000AAKX-003CA0 500GB       | 10       | 10     | 0.37%   |
| WDC WD20EZRZ-00Z5HB0 2TB          | 10       | 11     | 0.37%   |
| WDC WD20EARS-00MVWB0 2TB          | 10       | 13     | 0.37%   |
| WDC WD10EALX-009BA0 1TB           | 10       | 12     | 0.37%   |
| Seagate ST500LT012-9WS142 500GB   | 10       | 11     | 0.37%   |
| Seagate ST3250310AS 250GB         | 10       | 12     | 0.37%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 764      | 880    | 29.88%  |
| WDC                 | 741      | 882    | 28.98%  |
| Samsung Electronics | 262      | 302    | 10.25%  |
| Hitachi             | 206      | 232    | 8.06%   |
| Toshiba             | 111      | 120    | 4.34%   |
| Maxtor              | 80       | 90     | 3.13%   |
| Kingston            | 73       | 82     | 2.85%   |
| SanDisk             | 39       | 42     | 1.53%   |
| HGST                | 26       | 35     | 1.02%   |
| A-DATA Technology   | 24       | 26     | 0.94%   |
| Crucial             | 23       | 25     | 0.9%    |
| China               | 22       | 23     | 0.86%   |
| Intel               | 18       | 18     | 0.7%    |
| Hewlett-Packard     | 10       | 11     | 0.39%   |
| SPCC                | 9        | 9      | 0.35%   |
| OCZ                 | 9        | 9      | 0.35%   |
| Netac               | 7        | 7      | 0.27%   |
| Micron Technology   | 7        | 8      | 0.27%   |
| GOODRAM             | 7        | 7      | 0.27%   |
| Fujitsu             | 7        | 7      | 0.27%   |
| ASMT                | 7        | 7      | 0.27%   |
| Unknown             | 7        | 7      | 0.27%   |
| SK hynix            | 5        | 5      | 0.2%    |
| Patriot             | 5        | 5      | 0.2%    |
| Corsair             | 5        | 5      | 0.2%    |
| Intenso             | 4        | 5      | 0.16%   |
| IBM/Hitachi         | 4        | 5      | 0.16%   |
| XPG                 | 3        | 3      | 0.12%   |
| WD MediaMax         | 3        | 3      | 0.12%   |
| LITEON              | 3        | 3      | 0.12%   |
| KingSpec            | 3        | 3      | 0.12%   |
| JMicron Technology  | 3        | 4      | 0.12%   |
| ExcelStor           | 3        | 3      | 0.12%   |
| USB3.0              | 2        | 2      | 0.08%   |
| Team                | 2        | 2      | 0.08%   |
| Quantum             | 2        | 2      | 0.08%   |
| Plextor             | 2        | 2      | 0.08%   |
| Initio              | 2        | 2      | 0.08%   |
| HPE                 | 2        | 3      | 0.08%   |
| ASMedia             | 2        | 2      | 0.08%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 764      | 880    | 35.26%  |
| WDC                 | 710      | 840    | 32.76%  |
| Samsung Electronics | 227      | 256    | 10.48%  |
| Hitachi             | 206      | 232    | 9.51%   |
| Toshiba             | 110      | 119    | 5.08%   |
| Maxtor              | 80       | 90     | 3.69%   |
| HGST                | 26       | 35     | 1.2%    |
| Hewlett-Packard     | 8        | 9      | 0.37%   |
| Fujitsu             | 7        | 7      | 0.32%   |
| IBM/Hitachi         | 4        | 5      | 0.18%   |
| WD MediaMax         | 3        | 3      | 0.14%   |
| ExcelStor           | 3        | 3      | 0.14%   |
| USB3.0              | 2        | 2      | 0.09%   |
| Quantum             | 2        | 2      | 0.09%   |
| Initio              | 2        | 2      | 0.09%   |
| HPE                 | 2        | 3      | 0.09%   |
| ASMedia             | 2        | 2      | 0.09%   |
| Unknown             | 2        | 2      | 0.09%   |
| SAGE                | 1        | 1      | 0.05%   |
| RSH-339             | 1        | 1      | 0.05%   |
| RSH-319             | 1        | 1      | 0.05%   |
| Magnetic Data       | 1        | 1      | 0.05%   |
| IB                  | 1        | 1      | 0.05%   |
| China               | 1        | 1      | 0.05%   |
| ASMT                | 1        | 1      | 0.05%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1908     | 2499   | 83.14%  |
| SSD     | 352      | 400    | 15.34%  |
| NVMe    | 34       | 35     | 1.48%   |
| Unknown | 1        | 2      | 0.04%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST3250318AS 250GB         | 4        | 4      | 5.8%    |
| Seagate ST3500418AS 500GB         | 3        | 5      | 4.35%   |
| Samsung Electronics HD502HJ 500GB | 3        | 3      | 4.35%   |
| Samsung Electronics HD103SJ 1TB   | 3        | 3      | 4.35%   |
| Apple HDD HTS541010A9E662 1TB     | 3        | 3      | 4.35%   |
| WDC WD800JD-00LSA0 80GB           | 2        | 3      | 2.9%    |
| WDC WD20EZRX-00D8PB0 2TB          | 2        | 2      | 2.9%    |
| Seagate ST500DM002-1BD142 500GB   | 2        | 2      | 2.9%    |
| Seagate ST31000528AS 1TB          | 2        | 2      | 2.9%    |
| Samsung Electronics HD103UJ 1TB   | 2        | 4      | 2.9%    |
| WDC WD800JD-75MSA3 80GB           | 1        | 1      | 1.45%   |
| WDC WD800JD-00MSA1 80GB           | 1        | 1      | 1.45%   |
| WDC WD7501AALS-00J7B0 752GB       | 1        | 1      | 1.45%   |
| WDC WD7500BPVT-22HXZT3 752GB      | 1        | 1      | 1.45%   |
| WDC WD5000AAKS-00C8A0 500GB       | 1        | 1      | 1.45%   |
| WDC WD3200BPVT-22JJ5T0 320GB      | 1        | 1      | 1.45%   |
| WDC WD3200BPVT-00JJ5T0 320GB      | 1        | 1      | 1.45%   |
| WDC WD3200AAJS-60Z0A0 320GB       | 1        | 1      | 1.45%   |
| WDC WD20EARS-00MVWB0 2TB          | 1        | 1      | 1.45%   |
| WDC WD1600YS-23SHB0 160GB         | 1        | 1      | 1.45%   |
| WDC WD10JPVT-75A1YT0 1TB          | 1        | 1      | 1.45%   |
| WDC WD10EZEX-00BN5A0 1TB          | 1        | 1      | 1.45%   |
| WDC WD10EALX-759BA1 1TB           | 1        | 1      | 1.45%   |
| WDC WD1002FAEX-00Z3A0 1TB         | 1        | 1      | 1.45%   |
| TPH00800640GB 640GB               | 1        | 1      | 1.45%   |
| Toshiba MQ01ABD050 500GB          | 1        | 1      | 1.45%   |
| Toshiba MK3256GSY 320GB           | 1        | 1      | 1.45%   |
| Toshiba DT01ACA100 1TB            | 1        | 1      | 1.45%   |
| Toshiba DT01ACA050 500GB          | 1        | 1      | 1.45%   |
| Seagate STM3250318AS 250GB        | 1        | 1      | 1.45%   |
| Seagate STM31000528AS 1TB         | 1        | 1      | 1.45%   |
| Seagate ST980811AS 80GB           | 1        | 1      | 1.45%   |
| Seagate ST9320423AS 320GB         | 1        | 1      | 1.45%   |
| Seagate ST3750640NS 752GB         | 1        | 1      | 1.45%   |
| Seagate ST3320613AS 320GB         | 1        | 1      | 1.45%   |
| Seagate ST3320418AS 320GB         | 1        | 1      | 1.45%   |
| Seagate ST3250820AS 250GB         | 1        | 1      | 1.45%   |
| Seagate ST3160215A 160GB          | 1        | 1      | 1.45%   |
| Samsung Electronics SSD 980 500GB | 1        | 1      | 1.45%   |
| Samsung Electronics SSD 980 1TB   | 1        | 1      | 1.45%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 20       | 22     | 28.99%  |
| WDC                 | 18       | 19     | 26.09%  |
| Samsung Electronics | 16       | 18     | 23.19%  |
| Toshiba             | 4        | 4      | 5.8%    |
| Hitachi             | 4        | 4      | 5.8%    |
| Apple               | 3        | 3      | 4.35%   |
| TPH00800640GB       | 1        | 1      | 1.45%   |
| Maxtor              | 1        | 1      | 1.45%   |
| Kingston            | 1        | 1      | 1.45%   |
| GOODRAM             | 1        | 1      | 1.45%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 5763     | 12113  | 65.38%  |
| Malfunc  | 2216     | 2936   | 25.14%  |
| Detected | 769      | 1057   | 8.72%   |
| Failed   | 67       | 74     | 0.76%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 4544     | 48.34%  |
| AMD                              | 2268     | 24.13%  |
| Samsung Electronics              | 438      | 4.66%   |
| ASMedia Technology               | 274      | 2.91%   |
| JMicron Technology               | 252      | 2.68%   |
| Nvidia                           | 235      | 2.5%    |
| SanDisk                          | 225      | 2.39%   |
| Marvell Technology Group         | 202      | 2.15%   |
| Phison Electronics               | 179      | 1.9%    |
| Kingston Technology Company      | 168      | 1.79%   |
| Micron/Crucial Technology        | 122      | 1.3%    |
| Silicon Motion                   | 112      | 1.19%   |
| VIA Technologies                 | 64       | 0.68%   |
| ADATA Technology                 | 49       | 0.52%   |
| MAXIO Technology (Hangzhou)      | 35       | 0.37%   |
| Realtek Semiconductor            | 32       | 0.34%   |
| SK hynix                         | 25       | 0.27%   |
| Seagate Technology               | 18       | 0.19%   |
| Toshiba America Info Systems     | 17       | 0.18%   |
| Micron Technology                | 16       | 0.17%   |
| Silicon Image                    | 14       | 0.15%   |
| Broadcom / LSI                   | 14       | 0.15%   |
| KIOXIA                           | 12       | 0.13%   |
| LSI Logic / Symbios Logic        | 10       | 0.11%   |
| Integrated Technology Express    | 10       | 0.11%   |
| Shenzhen Longsys Electronics     | 9        | 0.1%    |
| Lite-On Technology               | 9        | 0.1%    |
| Netac Technology                 | 7        | 0.07%   |
| Promise Technology               | 5        | 0.05%   |
| INNOGRIT                         | 5        | 0.05%   |
| Adaptec                          | 5        | 0.05%   |
| Silicon Integrated Systems [SiS] | 4        | 0.04%   |
| Lite-On IT Corp. / Plextor       | 4        | 0.04%   |
| Union Memory (Shenzhen)          | 3        | 0.03%   |
| Hewlett-Packard                  | 3        | 0.03%   |
| Biwin Storage Technology         | 3        | 0.03%   |
| 3ware                            | 2        | 0.02%   |
| Yangtze Memory Technologies      | 1        | 0.01%   |
| Solidigm                         | 1        | 0.01%   |
| Solid State Storage Technology   | 1        | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 1188     | 9.74%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 596      | 4.89%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 444      | 3.64%   |
| AMD 400 Series Chipset SATA Controller                                                  | 430      | 3.53%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 422      | 3.46%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 392      | 3.21%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 352      | 2.89%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 331      | 2.71%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 317      | 2.6%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 314      | 2.58%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 293      | 2.4%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 259      | 2.12%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 248      | 2.03%   |
| AMD 500 Series Chipset SATA Controller                                                  | 248      | 2.03%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 247      | 2.03%   |
| Intel SATA Controller [RAID mode]                                                       | 218      | 1.79%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 212      | 1.74%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 210      | 1.72%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 193      | 1.58%   |
| AMD FCH SATA Controller D                                                               | 162      | 1.33%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 148      | 1.21%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 136      | 1.12%   |
| Nvidia MCP61 SATA Controller                                                            | 133      | 1.09%   |
| Nvidia MCP61 IDE                                                                        | 121      | 0.99%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 113      | 0.93%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 109      | 0.89%   |
| AMD 300 Series Chipset SATA Controller                                                  | 109      | 0.89%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 108      | 0.89%   |
| AMD FCH IDE Controller                                                                  | 95       | 0.78%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 94       | 0.77%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 85       | 0.7%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 84       | 0.69%   |
| Phison E12 NVMe Controller                                                              | 82       | 0.67%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 82       | 0.67%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 79       | 0.65%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 78       | 0.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 77       | 0.63%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 75       | 0.62%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 71       | 0.58%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 70       | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 5443     | 58.35%  |
| IDE  | 2188     | 23.46%  |
| NVMe | 1325     | 14.2%   |
| RAID | 332      | 3.56%   |
| SAS  | 26       | 0.28%   |
| SCSI | 14       | 0.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 4606     | 65.02%  |
| AMD    | 2478     | 34.98%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 115      | 1.62%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 106      | 1.49%   |
| AMD Ryzen 5 3600 6-Core Processor           | 97       | 1.36%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 83       | 1.17%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 78       | 1.1%    |
| Intel Core i3-3220 CPU @ 3.30GHz            | 73       | 1.03%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 73       | 1.03%   |
| AMD FX-8350 Eight-Core Processor            | 73       | 1.03%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 68       | 0.96%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 68       | 0.96%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 67       | 0.94%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 66       | 0.93%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 65       | 0.91%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 65       | 0.91%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 64       | 0.9%    |
| AMD Ryzen 5 2600 Six-Core Processor         | 60       | 0.84%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 58       | 0.82%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 58       | 0.82%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 52       | 0.73%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 52       | 0.73%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 52       | 0.73%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 51       | 0.72%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 50       | 0.7%    |
| Intel Core i5-4460 CPU @ 3.20GHz            | 48       | 0.67%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 47       | 0.66%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 45       | 0.63%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 44       | 0.62%   |
| AMD FX-6300 Six-Core Processor              | 44       | 0.62%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 43       | 0.6%    |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 43       | 0.6%    |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 41       | 0.58%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 40       | 0.56%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 39       | 0.55%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 39       | 0.55%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 38       | 0.53%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 38       | 0.53%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 38       | 0.53%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 38       | 0.53%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 37       | 0.52%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 36       | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 1321     | 18.6%   |
| Intel Core i3           | 699      | 9.84%   |
| Intel Core i7           | 669      | 9.42%   |
| AMD Ryzen 5             | 557      | 7.84%   |
| Intel Core 2 Duo        | 347      | 4.88%   |
| AMD FX                  | 294      | 4.14%   |
| AMD Ryzen 7             | 291      | 4.1%    |
| Intel Pentium           | 264      | 3.72%   |
| Intel Celeron           | 256      | 3.6%    |
| Intel Xeon              | 215      | 3.03%   |
| Intel Core 2 Quad       | 208      | 2.93%   |
| Intel Pentium Dual-Core | 174      | 2.45%   |
| Other                   | 158      | 2.22%   |
| AMD Ryzen 3             | 148      | 2.08%   |
| AMD A8                  | 124      | 1.75%   |
| AMD Athlon II X2        | 108      | 1.52%   |
| AMD Ryzen 9             | 104      | 1.46%   |
| AMD Phenom II X4        | 99       | 1.39%   |
| AMD Athlon 64 X2        | 85       | 1.2%    |
| AMD A10                 | 82       | 1.15%   |
| Intel Core 2            | 74       | 1.04%   |
| AMD A4                  | 73       | 1.03%   |
| AMD Athlon              | 62       | 0.87%   |
| AMD A6                  | 60       | 0.84%   |
| Intel Pentium Dual      | 55       | 0.77%   |
| AMD Athlon II X4        | 45       | 0.63%   |
| AMD Phenom II X6        | 39       | 0.55%   |
| Intel Atom              | 37       | 0.52%   |
| Intel Pentium Gold      | 34       | 0.48%   |
| Intel Core i9           | 34       | 0.48%   |
| AMD Phenom              | 34       | 0.48%   |
| Intel Pentium 4         | 33       | 0.46%   |
| Intel Pentium D         | 29       | 0.41%   |
| AMD Athlon II X3        | 28       | 0.39%   |
| AMD Sempron             | 25       | 0.35%   |
| AMD Ryzen 5 PRO         | 25       | 0.35%   |
| AMD Athlon X4           | 25       | 0.35%   |
| AMD Athlon 64           | 20       | 0.28%   |
| AMD Phenom II X2        | 17       | 0.24%   |
| AMD E                   | 14       | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 2772     | 39%     |
| 2       | 2455     | 34.54%  |
| 6       | 897      | 12.62%  |
| 8       | 436      | 6.13%   |
| 1       | 218      | 3.07%   |
| 3       | 121      | 1.7%    |
| 12      | 95       | 1.34%   |
| 16      | 55       | 0.77%   |
| 10      | 27       | 0.38%   |
| 14      | 15       | 0.21%   |
| 24      | 7        | 0.1%    |
| 28      | 3        | 0.04%   |
| 32      | 2        | 0.03%   |
| 20      | 2        | 0.03%   |
| 44      | 1        | 0.01%   |
| 5       | 1        | 0.01%   |
| Unknown | 1        | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 7045     | 99.45%  |
| 2      | 37       | 0.52%   |
| 16     | 1        | 0.01%   |
| 14     | 1        | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 3544     | 49.92%  |
| 2       | 3536     | 49.81%  |
| 4       | 9        | 0.13%   |
| 12      | 4        | 0.06%   |
| 8       | 4        | 0.06%   |
| 6       | 1        | 0.01%   |
| Unknown | 1        | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 7082     | 99.96%  |
| Unknown        | 3        | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1298     | 17.64%  |
| 0x306c3    | 619      | 8.41%   |
| 0x306a9    | 475      | 6.46%   |
| 0x1067a    | 444      | 6.03%   |
| 0x206a7    | 407      | 5.53%   |
| 0x08701021 | 241      | 3.28%   |
| 0x506e3    | 200      | 2.72%   |
| 0x906ea    | 159      | 2.16%   |
| 0x906e9    | 150      | 2.04%   |
| 0x06001119 | 143      | 1.94%   |
| 0x010000c8 | 142      | 1.93%   |
| 0x0800820d | 137      | 1.86%   |
| 0x08108109 | 112      | 1.52%   |
| 0x08101016 | 102      | 1.39%   |
| 0x06000822 | 98       | 1.33%   |
| 0xa0653    | 89       | 1.21%   |
| 0x6fb      | 81       | 1.1%    |
| 0x06003106 | 81       | 1.1%    |
| 0x6fd      | 78       | 1.06%   |
| 0xa0655    | 73       | 0.99%   |
| 0x0a50000d | 69       | 0.94%   |
| 0x08001138 | 68       | 0.92%   |
| 0x10676    | 65       | 0.88%   |
| 0x106e5    | 61       | 0.83%   |
| 0x0a50000c | 56       | 0.76%   |
| 0x0a201016 | 56       | 0.76%   |
| 0x0600081c | 55       | 0.75%   |
| 0x010000b6 | 55       | 0.75%   |
| 0x20655    | 52       | 0.71%   |
| 0x906eb    | 51       | 0.69%   |
| 0xa0671    | 43       | 0.58%   |
| 0x08600106 | 41       | 0.56%   |
| 0x0600611a | 41       | 0.56%   |
| 0x906ed    | 39       | 0.53%   |
| 0x0a20120a | 39       | 0.53%   |
| 0x106a5    | 37       | 0.5%    |
| 0x6f6      | 35       | 0.48%   |
| 0x010000bf | 35       | 0.48%   |
| 0x10677    | 34       | 0.46%   |
| 0x08701013 | 34       | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 808      | 11.39%  |
| Penryn           | 659      | 9.29%   |
| IvyBridge        | 610      | 8.6%    |
| KabyLake         | 564      | 7.95%   |
| SandyBridge      | 524      | 7.39%   |
| K10              | 397      | 5.6%    |
| Piledriver       | 395      | 5.57%   |
| Zen 2            | 354      | 4.99%   |
| Zen+             | 298      | 4.2%    |
| Skylake          | 288      | 4.06%   |
| Zen 3            | 278      | 3.92%   |
| Core             | 278      | 3.92%   |
| Zen              | 257      | 3.62%   |
| CometLake        | 213      | 3%      |
| K8 Hammer        | 129      | 1.82%   |
| Nehalem          | 119      | 1.68%   |
| Westmere         | 117      | 1.65%   |
| Steamroller      | 99       | 1.4%    |
| Silvermont       | 82       | 1.16%   |
| NetBurst         | 70       | 0.99%   |
| Alderlake Hybrid | 68       | 0.96%   |
| Excavator        | 65       | 0.92%   |
| Bulldozer        | 59       | 0.83%   |
| Icelake          | 53       | 0.75%   |
| K10 Llano        | 46       | 0.65%   |
| Goldmont plus    | 39       | 0.55%   |
| Jaguar           | 35       | 0.49%   |
| Unknown          | 34       | 0.48%   |
| Bonnell          | 30       | 0.42%   |
| Puma             | 26       | 0.37%   |
| Bobcat           | 26       | 0.37%   |
| Broadwell        | 25       | 0.35%   |
| Goldmont         | 21       | 0.3%    |
| Tremont          | 20       | 0.28%   |
| Gracemont        | 7        | 0.1%    |
| TigerLake        | 2        | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Nvidia                               | 2583     | 35.07%  |
| Intel                                | 2494     | 33.86%  |
| AMD                                  | 2260     | 30.68%  |
| Matrox Electronics Systems           | 12       | 0.16%   |
| VIA Technologies                     | 6        | 0.08%   |
| ATI Technologies                     | 4        | 0.05%   |
| Red Hat                              | 2        | 0.03%   |
| ASPEED Technology                    | 2        | 0.03%   |
| S3 Graphics                          | 1        | 0.01%   |
| NVidia / SGS Thomson (Joint Venture) | 1        | 0.01%   |
| Conexant Systems                     | 1        | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 402      | 5.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 295      | 3.92%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 267      | 3.55%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 257      | 3.42%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 215      | 2.86%   |
| Nvidia GK208B [GeForce GT 710]                                              | 191      | 2.54%   |
| Intel HD Graphics 530                                                       | 154      | 2.05%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 150      | 1.99%   |
| Nvidia GT218 [GeForce 210]                                                  | 145      | 1.93%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 139      | 1.85%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 121      | 1.61%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 116      | 1.54%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 110      | 1.46%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 109      | 1.45%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 107      | 1.42%   |
| Nvidia GK208B [GeForce GT 730]                                              | 103      | 1.37%   |
| Intel HD Graphics 630                                                       | 99       | 1.32%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 95       | 1.26%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 85       | 1.13%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 74       | 0.98%   |
| AMD RS780L [Radeon 3000]                                                    | 73       | 0.97%   |
| Nvidia GF119 [GeForce GT 610]                                               | 67       | 0.89%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 66       | 0.88%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 65       | 0.86%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 64       | 0.85%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 62       | 0.82%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 61       | 0.81%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 61       | 0.81%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 60       | 0.8%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 54       | 0.72%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 52       | 0.69%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 52       | 0.69%   |
| Nvidia GF108 [GeForce GT 630]                                               | 51       | 0.68%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 50       | 0.66%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 49       | 0.65%   |
| Intel Core Processor Integrated Graphics Controller                         | 47       | 0.63%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 45       | 0.6%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 42       | 0.56%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 42       | 0.56%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 42       | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| 1 x Nvidia                               | 2442     | 34.13%  |
| 1 x Intel                                | 2242     | 31.33%  |
| 1 x AMD                                  | 2098     | 29.32%  |
| 2 x AMD                                  | 98       | 1.37%   |
| Intel + Nvidia                           | 90       | 1.26%   |
| 2 x Intel                                | 68       | 0.95%   |
| AMD + Nvidia                             | 36       | 0.5%    |
| Intel + AMD                              | 33       | 0.46%   |
| 2 x Nvidia                               | 16       | 0.22%   |
| 1 x Matrox                               | 11       | 0.15%   |
| 1 x VIA                                  | 6        | 0.08%   |
| 1 x Red Hat                              | 2        | 0.03%   |
| Nvidia + ASPEED                          | 2        | 0.03%   |
| Intel + 2 x Nvidia                       | 2        | 0.03%   |
| Intel + AMD + 1 x Nvidia                 | 2        | 0.03%   |
| 3 x AMD                                  | 1        | 0.01%   |
| 2 x Intel + 1 x Nvidia                   | 1        | 0.01%   |
| 1 x S3 Graphics                          | 1        | 0.01%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1        | 0.01%   |
| Nvidia + Matrox                          | 1        | 0.01%   |
| Intel + Conexant Systems                 | 1        | 0.01%   |
| AMD + Matrox                             | 1        | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 6816     | 95.66%  |
| Unknown     | 240      | 3.37%   |
| Proprietary | 69       | 0.97%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 2495     | 34.8%   |
| 1.01-2.0   | 1253     | 17.48%  |
| 0.51-1.0   | 1084     | 15.12%  |
| 0.01-0.5   | 945      | 13.18%  |
| 3.01-4.0   | 538      | 7.5%    |
| 7.01-8.0   | 463      | 6.46%   |
| 5.01-6.0   | 202      | 2.82%   |
| 8.01-16.0  | 107      | 1.49%   |
| 2.01-3.0   | 66       | 0.92%   |
| 16.01-24.0 | 13       | 0.18%   |
| 4.01-5.0   | 4        | 0.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 1228     | 17.47%  |
| Goldstar             | 838      | 11.92%  |
| Dell                 | 604      | 8.59%   |
| Hewlett-Packard      | 595      | 8.47%   |
| Acer                 | 540      | 7.68%   |
| Philips              | 418      | 5.95%   |
| AOC                  | 408      | 5.81%   |
| BenQ                 | 320      | 4.55%   |
| Ancor Communications | 273      | 3.88%   |
| ViewSonic            | 183      | 2.6%    |
| Iiyama               | 156      | 2.22%   |
| ASUSTek Computer     | 112      | 1.59%   |
| Lenovo               | 91       | 1.29%   |
| Sony                 | 75       | 1.07%   |
| Fujitsu Siemens      | 68       | 0.97%   |
| Eizo                 | 64       | 0.91%   |
| NEC Computers        | 60       | 0.85%   |
| HannStar             | 43       | 0.61%   |
| Panasonic            | 32       | 0.46%   |
| MSI                  | 32       | 0.46%   |
| Medion               | 32       | 0.46%   |
| Unknown              | 31       | 0.44%   |
| Sceptre Tech         | 31       | 0.44%   |
| Toshiba              | 28       | 0.4%    |
| Vizio                | 25       | 0.36%   |
| Vestel Elektronik    | 23       | 0.33%   |
| Sharp                | 21       | 0.3%    |
| Hitachi              | 20       | 0.28%   |
| Belinea              | 17       | 0.24%   |
| MStar                | 16       | 0.23%   |
| Gigabyte Technology  | 16       | 0.23%   |
| Packard Bell         | 15       | 0.21%   |
| Insignia             | 14       | 0.2%    |
| ___                  | 13       | 0.18%   |
| Unknown (XXX)        | 13       | 0.18%   |
| HKC                  | 13       | 0.18%   |
| RTK                  | 12       | 0.17%   |
| Mi                   | 12       | 0.17%   |
| IOD                  | 12       | 0.17%   |
| CVT                  | 11       | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 46       | 0.64%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 32       | 0.44%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 31       | 0.43%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                       | 26       | 0.36%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 25       | 0.35%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch           | 25       | 0.35%   |
| AOC Q27P2W AOC2702 2560x1440 597x336mm 27.0-inch                      | 24       | 0.33%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                      | 23       | 0.32%   |
| Dell D1918H DEL2005 1366x768 410x230mm 18.5-inch                      | 22       | 0.31%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch               | 21       | 0.29%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 20       | 0.28%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 20       | 0.28%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 18       | 0.25%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 18       | 0.25%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                    | 17       | 0.24%   |
| AOC G2460 AOC2460 1920x1080 531x299mm 24.0-inch                       | 17       | 0.24%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch     | 16       | 0.22%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch            | 16       | 0.22%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 15       | 0.21%   |
| Acer G246HL ACR02FF 1920x1080 531x299mm 24.0-inch                     | 15       | 0.21%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch     | 14       | 0.19%   |
| Philips 273PQPY PHLC096 1920x1080 597x336mm 27.0-inch                 | 14       | 0.19%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                      | 14       | 0.19%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 14       | 0.19%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 14       | 0.19%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 14       | 0.19%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 14       | 0.19%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 13       | 0.18%   |
| Goldstar W2243 GSM56FE 1920x1080 477x269mm 21.6-inch                  | 13       | 0.18%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 13       | 0.18%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 13       | 0.18%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                     | 13       | 0.18%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch  | 11       | 0.15%   |
| Goldstar E2250 GSM578D 1920x1080 477x268mm 21.5-inch                  | 11       | 0.15%   |
| AOC 936W AOC1936 1366x768 410x230mm 18.5-inch                         | 11       | 0.15%   |
| Unknown                                                               | 11       | 0.15%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 10       | 0.14%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 10       | 0.14%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch  | 10       | 0.14%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch     | 10       | 0.14%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 3420     | 49.62%  |
| 1280x1024 (SXGA)   | 613      | 8.89%   |
| 3840x2160 (4K)     | 510      | 7.4%    |
| 1680x1050 (WSXGA+) | 448      | 6.5%    |
| 1366x768 (WXGA)    | 365      | 5.3%    |
| 2560x1440 (QHD)    | 349      | 5.06%   |
| 1440x900 (WXGA+)   | 304      | 4.41%   |
| 1600x900 (HD+)     | 233      | 3.38%   |
| 1920x1200 (WUXGA)  | 180      | 2.61%   |
| 1360x768           | 130      | 1.89%   |
| 3440x1440          | 68       | 0.99%   |
| 2560x1080          | 59       | 0.86%   |
| 1920x540           | 42       | 0.61%   |
| 1024x768 (XGA)     | 36       | 0.52%   |
| 1600x1200          | 29       | 0.42%   |
| 1280x720 (HD)      | 21       | 0.3%    |
| 1280x960           | 13       | 0.19%   |
| 2560x1600          | 12       | 0.17%   |
| 2288x1287          | 11       | 0.16%   |
| 2048x1152          | 9        | 0.13%   |
| Unknown            | 9        | 0.13%   |
| 3840x1080          | 8        | 0.12%   |
| 1280x768           | 5        | 0.07%   |
| 3840x1600          | 4        | 0.06%   |
| 1400x1050          | 2        | 0.03%   |
| 1152x864           | 2        | 0.03%   |
| 8320x1440          | 1        | 0.01%   |
| 6000x1440          | 1        | 0.01%   |
| 5760x2160          | 1        | 0.01%   |
| 5120x1440          | 1        | 0.01%   |
| 4480x2023          | 1        | 0.01%   |
| 3840x1200          | 1        | 0.01%   |
| 3200x1080          | 1        | 0.01%   |
| 2048x1536          | 1        | 0.01%   |
| 1536x2048          | 1        | 0.01%   |
| 1024x600           | 1        | 0.01%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 1026     | 14.58%  |
| 21      | 975      | 13.85%  |
| 24      | 847      | 12.03%  |
| 27      | 844      | 11.99%  |
| 19      | 590      | 8.38%   |
| 18      | 406      | 5.77%   |
| 22      | 336      | 4.77%   |
| 17      | 325      | 4.62%   |
| 31      | 289      | 4.11%   |
| 20      | 268      | 3.81%   |
| Unknown | 141      | 2%      |
| 34      | 114      | 1.62%   |
| 15      | 110      | 1.56%   |
| 84      | 106      | 1.51%   |
| 32      | 72       | 1.02%   |
| 72      | 65       | 0.92%   |
| 40      | 63       | 0.9%    |
| 54      | 61       | 0.87%   |
| 25      | 43       | 0.61%   |
| 26      | 34       | 0.48%   |
| 52      | 28       | 0.4%    |
| 28      | 28       | 0.4%    |
| 48      | 20       | 0.28%   |
| 37      | 19       | 0.27%   |
| 33      | 19       | 0.27%   |
| 65      | 18       | 0.26%   |
| 46      | 17       | 0.24%   |
| 39      | 16       | 0.23%   |
| 12      | 14       | 0.2%    |
| 42      | 13       | 0.18%   |
| 29      | 13       | 0.18%   |
| 35      | 12       | 0.17%   |
| 16      | 12       | 0.17%   |
| 142     | 9        | 0.13%   |
| 43      | 9        | 0.13%   |
| 36      | 9        | 0.13%   |
| 74      | 7        | 0.1%    |
| 60      | 7        | 0.1%    |
| 55      | 7        | 0.1%    |
| 49      | 7        | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 2568     | 37.27%  |
| 401-500        | 2253     | 32.7%   |
| 301-350        | 417      | 6.05%   |
| 601-700        | 415      | 6.02%   |
| 351-400        | 351      | 5.09%   |
| 701-800        | 215      | 3.12%   |
| 1501-2000      | 182      | 2.64%   |
| 1001-1500      | 182      | 2.64%   |
| Unknown        | 141      | 2.05%   |
| 801-900        | 112      | 1.63%   |
| 901-1000       | 24       | 0.35%   |
| 201-300        | 21       | 0.3%    |
| More than 2000 | 9        | 0.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 4775     | 70.59%  |
| 16/10   | 977      | 14.44%  |
| 5/4     | 601      | 8.89%   |
| 21/9    | 131      | 1.94%   |
| 4/3     | 118      | 1.74%   |
| Unknown | 60       | 0.89%   |
| 3/2     | 54       | 0.8%    |
| 6/5     | 14       | 0.21%   |
| 32/9    | 13       | 0.19%   |
| 1.00    | 9        | 0.13%   |
| 1.96    | 4        | 0.06%   |
| 2.12    | 2        | 0.03%   |
| 2.00    | 2        | 0.03%   |
| 3.20    | 1        | 0.01%   |
| 2.01    | 1        | 0.01%   |
| 0.75    | 1        | 0.01%   |
| 0.56    | 1        | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 2596     | 37.37%  |
| 151-200        | 1177     | 16.95%  |
| 301-350        | 865      | 12.45%  |
| 141-150        | 627      | 9.03%   |
| 351-500        | 515      | 7.41%   |
| 251-300        | 344      | 4.95%   |
| More than 1000 | 342      | 4.92%   |
| 501-1000       | 173      | 2.49%   |
| Unknown        | 141      | 2.03%   |
| 101-110        | 83       | 1.19%   |
| 111-120        | 25       | 0.36%   |
| 131-140        | 24       | 0.35%   |
| 71-80          | 13       | 0.19%   |
| 121-130        | 7        | 0.1%    |
| 91-100         | 7        | 0.1%    |
| 81-90          | 4        | 0.06%   |
| 61-70          | 1        | 0.01%   |
| 51-60          | 1        | 0.01%   |
| 41-50          | 1        | 0.01%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 4784     | 70.61%  |
| 101-120 | 1288     | 19.01%  |
| 1-50    | 301      | 4.44%   |
| 121-160 | 177      | 2.61%   |
| Unknown | 141      | 2.08%   |
| 161-240 | 84       | 1.24%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 6437     | 90.28%  |
| 2     | 508      | 7.12%   |
| 0     | 134      | 1.88%   |
| 3     | 44       | 0.62%   |
| 4     | 5        | 0.07%   |
| 7     | 1        | 0.01%   |
| 5     | 1        | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 4603     | 49.12%  |
| Intel                            | 2343     | 25%     |
| Qualcomm Atheros                 | 682      | 7.28%   |
| Ralink Technology                | 239      | 2.55%   |
| Broadcom                         | 219      | 2.34%   |
| Nvidia                           | 197      | 2.1%    |
| Ralink                           | 121      | 1.29%   |
| TP-Link                          | 114      | 1.22%   |
| Qualcomm Atheros Communications  | 82       | 0.88%   |
| Marvell Technology Group         | 73       | 0.78%   |
| Broadcom Limited                 | 64       | 0.68%   |
| MediaTek                         | 58       | 0.62%   |
| D-Link                           | 46       | 0.49%   |
| D-Link System                    | 40       | 0.43%   |
| NetGear                          | 35       | 0.37%   |
| Huawei Technologies              | 35       | 0.37%   |
| ASUSTek Computer                 | 35       | 0.37%   |
| VIA Technologies                 | 28       | 0.3%    |
| Samsung Electronics              | 25       | 0.27%   |
| Belkin Components                | 25       | 0.27%   |
| Microsoft                        | 23       | 0.25%   |
| Aquantia                         | 23       | 0.25%   |
| ASIX Electronics                 | 18       | 0.19%   |
| ZTE WCDMA Technologies MSM       | 16       | 0.17%   |
| Motorola PCS                     | 15       | 0.16%   |
| IMC Networks                     | 15       | 0.16%   |
| Edimax Technology                | 14       | 0.15%   |
| 3Com                             | 14       | 0.15%   |
| Xiaomi                           | 12       | 0.13%   |
| AVM                              | 12       | 0.13%   |
| Linksys                          | 11       | 0.12%   |
| OPPO Electronics                 | 8        | 0.09%   |
| JMicron Technology               | 7        | 0.07%   |
| DisplayLink                      | 6        | 0.06%   |
| Mercucys                         | 5        | 0.05%   |
| ZyDAS                            | 4        | 0.04%   |
| Wilocity                         | 4        | 0.04%   |
| T & A Mobile Phones              | 4        | 0.04%   |
| Silicon Integrated Systems [SiS] | 4        | 0.04%   |
| Qualcomm                         | 4        | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3829     | 36.98%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 284      | 2.74%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 228      | 2.2%    |
| Realtek RTL8125 2.5GbE Controller                                 | 225      | 2.17%   |
| Intel I211 Gigabit Network Connection                             | 210      | 2.03%   |
| Intel Ethernet Connection I217-LM                                 | 204      | 1.97%   |
| Intel Wi-Fi 6 AX200                                               | 185      | 1.79%   |
| Intel Ethernet Connection (2) I219-V                              | 181      | 1.75%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 137      | 1.32%   |
| Intel 82579V Gigabit Network Connection                           | 127      | 1.23%   |
| Ralink MT7601U Wireless Adapter                                   | 116      | 1.12%   |
| Nvidia MCP61 Ethernet                                             | 115      | 1.11%   |
| Intel Ethernet Controller I225-V                                  | 107      | 1.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 100      | 0.97%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 97       | 0.94%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 93       | 0.9%    |
| Intel Ethernet Connection (7) I219-V                              | 93       | 0.9%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 81       | 0.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 72       | 0.7%    |
| Qualcomm Atheros AR9271 802.11n                                   | 67       | 0.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 63       | 0.61%   |
| Intel Wireless-AC 9260                                            | 63       | 0.61%   |
| Intel Ethernet Connection I217-V                                  | 62       | 0.6%    |
| Intel Ethernet Connection (2) I219-LM                             | 57       | 0.55%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 53       | 0.51%   |
| Intel Wireless 7265                                               | 50       | 0.48%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 49       | 0.47%   |
| Ralink RT5370 Wireless Adapter                                    | 48       | 0.46%   |
| Intel Ethernet Connection (2) I218-V                              | 48       | 0.46%   |
| Intel 82574L Gigabit Network Connection                           | 48       | 0.46%   |
| Intel Wireless 3165                                               | 47       | 0.45%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 46       | 0.44%   |
| Intel Wireless 7260                                               | 46       | 0.44%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 44       | 0.42%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 41       | 0.4%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 40       | 0.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 40       | 0.39%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 39       | 0.38%   |
| Realtek 802.11ac NIC                                              | 38       | 0.37%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 38       | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 722      | 27.01%  |
| Realtek Semiconductor                 | 688      | 25.74%  |
| Qualcomm Atheros                      | 321      | 12.01%  |
| Ralink Technology                     | 239      | 8.94%   |
| Ralink                                | 121      | 4.53%   |
| TP-Link                               | 110      | 4.12%   |
| Qualcomm Atheros Communications       | 82       | 3.07%   |
| Broadcom                              | 54       | 2.02%   |
| MediaTek                              | 46       | 1.72%   |
| D-Link                                | 46       | 1.72%   |
| ASUSTek Computer                      | 35       | 1.31%   |
| NetGear                               | 33       | 1.23%   |
| Belkin Components                     | 25       | 0.94%   |
| Microsoft                             | 23       | 0.86%   |
| D-Link System                         | 19       | 0.71%   |
| IMC Networks                          | 15       | 0.56%   |
| Edimax Technology                     | 14       | 0.52%   |
| AVM                                   | 12       | 0.45%   |
| Linksys                               | 11       | 0.41%   |
| Broadcom Limited                      | 7        | 0.26%   |
| Mercucys                              | 5        | 0.19%   |
| ZyDAS                                 | 4        | 0.15%   |
| Wilocity                              | 4        | 0.15%   |
| BUFFALO                               | 4        | 0.15%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 4        | 0.15%   |
| Guillemot                             | 3        | 0.11%   |
| Gemtek                                | 3        | 0.11%   |
| ZyXEL Communications                  | 2        | 0.07%   |
| Wacom                                 | 2        | 0.07%   |
| Tenda                                 | 2        | 0.07%   |
| Sweex                                 | 2        | 0.07%   |
| PLANEX                                | 2        | 0.07%   |
| Philips (or NXP)                      | 2        | 0.07%   |
| Chu Yuen Enterprise                   | 2        | 0.07%   |
| VIA Technologies                      | 1        | 0.04%   |
| TRENDnet                              | 1        | 0.04%   |
| Sitecom Europe                        | 1        | 0.04%   |
| Senao                                 | 1        | 0.04%   |
| Micro Star International              | 1        | 0.04%   |
| Logitec                               | 1        | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 185      | 6.86%   |
| Ralink MT7601U Wireless Adapter                                | 116      | 4.3%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 100      | 3.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 97       | 3.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 72       | 2.67%   |
| Qualcomm Atheros AR9271 802.11n                                | 67       | 2.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 63       | 2.34%   |
| Intel Wireless-AC 9260                                         | 63       | 2.34%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 53       | 1.97%   |
| Intel Wireless 7265                                            | 50       | 1.85%   |
| Ralink RT5370 Wireless Adapter                                 | 48       | 1.78%   |
| Intel Wireless 3165                                            | 47       | 1.74%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 46       | 1.71%   |
| Intel Wireless 7260                                            | 46       | 1.71%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 44       | 1.63%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 40       | 1.48%   |
| Realtek 802.11ac NIC                                           | 38       | 1.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 38       | 1.41%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 37       | 1.37%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 36       | 1.33%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 34       | 1.26%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 33       | 1.22%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 33       | 1.22%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 32       | 1.19%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 31       | 1.15%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 29       | 1.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 28       | 1.04%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 26       | 0.96%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 25       | 0.93%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 23       | 0.85%   |
| Intel Wireless 8260                                            | 23       | 0.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 22       | 0.82%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 22       | 0.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 21       | 0.78%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 21       | 0.78%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 19       | 0.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 19       | 0.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 18       | 0.67%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter     | 18       | 0.67%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 18       | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 4378     | 58.84%  |
| Intel                             | 1904     | 25.59%  |
| Qualcomm Atheros                  | 386      | 5.19%   |
| Nvidia                            | 197      | 2.65%   |
| Broadcom                          | 167      | 2.24%   |
| Marvell Technology Group          | 73       | 0.98%   |
| Broadcom Limited                  | 57       | 0.77%   |
| Huawei Technologies               | 32       | 0.43%   |
| VIA Technologies                  | 25       | 0.34%   |
| Samsung Electronics               | 25       | 0.34%   |
| Aquantia                          | 23       | 0.31%   |
| D-Link System                     | 21       | 0.28%   |
| ASIX Electronics                  | 18       | 0.24%   |
| ZTE WCDMA Technologies MSM        | 15       | 0.2%    |
| 3Com                              | 14       | 0.19%   |
| Xiaomi                            | 12       | 0.16%   |
| MediaTek                          | 12       | 0.16%   |
| Motorola PCS                      | 9        | 0.12%   |
| OPPO Electronics                  | 8        | 0.11%   |
| JMicron Technology                | 7        | 0.09%   |
| TP-Link                           | 6        | 0.08%   |
| DisplayLink                       | 6        | 0.08%   |
| T & A Mobile Phones               | 4        | 0.05%   |
| Silicon Integrated Systems [SiS]  | 4        | 0.05%   |
| Qualcomm                          | 4        | 0.05%   |
| Sundance Technology Inc / IC Plus | 3        | 0.04%   |
| Mellanox Technologies             | 3        | 0.04%   |
| HTC (High Tech Computer)          | 3        | 0.04%   |
| Spreadtrum Communications         | 2        | 0.03%   |
| OnePlus Technology (Shenzhen)     | 2        | 0.03%   |
| NetGear                           | 2        | 0.03%   |
| LG Electronics                    | 2        | 0.03%   |
| ICS Advent                        | 2        | 0.03%   |
| HMD Global                        | 2        | 0.03%   |
| Apple                             | 2        | 0.03%   |
| vivo                              | 1        | 0.01%   |
| SysKonnect                        | 1        | 0.01%   |
| Netchip Technology                | 1        | 0.01%   |
| Lenovo                            | 1        | 0.01%   |
| IBM                               | 1        | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3829     | 50.22%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 284      | 3.72%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 228      | 2.99%   |
| Realtek RTL8125 2.5GbE Controller                                 | 225      | 2.95%   |
| Intel I211 Gigabit Network Connection                             | 210      | 2.75%   |
| Intel Ethernet Connection I217-LM                                 | 204      | 2.68%   |
| Intel Ethernet Connection (2) I219-V                              | 181      | 2.37%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 137      | 1.8%    |
| Intel 82579V Gigabit Network Connection                           | 127      | 1.67%   |
| Nvidia MCP61 Ethernet                                             | 115      | 1.51%   |
| Intel Ethernet Controller I225-V                                  | 107      | 1.4%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 93       | 1.22%   |
| Intel Ethernet Connection (7) I219-V                              | 93       | 1.22%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 81       | 1.06%   |
| Intel Ethernet Connection I217-V                                  | 62       | 0.81%   |
| Intel Ethernet Connection (2) I219-LM                             | 57       | 0.75%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 49       | 0.64%   |
| Intel Ethernet Connection (2) I218-V                              | 48       | 0.63%   |
| Intel 82574L Gigabit Network Connection                           | 48       | 0.63%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 41       | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 40       | 0.52%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 39       | 0.51%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 38       | 0.5%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 37       | 0.49%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 35       | 0.46%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 33       | 0.43%   |
| Intel 82578DM Gigabit Network Connection                          | 32       | 0.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 30       | 0.39%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 30       | 0.39%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 29       | 0.38%   |
| Intel Ethernet Connection (14) I219-V                             | 26       | 0.34%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 26       | 0.34%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 25       | 0.33%   |
| Intel 82578DC Gigabit Network Connection                          | 25       | 0.33%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 23       | 0.3%    |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 22       | 0.29%   |
| Intel Ethernet Connection (2) I218-LM                             | 21       | 0.28%   |
| Intel I210 Gigabit Network Connection                             | 20       | 0.26%   |
| Huawei E353/E3131                                                 | 19       | 0.25%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 18       | 0.24%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 7010     | 72.98%  |
| WiFi     | 2563     | 26.68%  |
| Modem    | 20       | 0.21%   |
| Unknown  | 13       | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 5897     | 83.86%  |
| WiFi     | 1135     | 16.14%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 5037     | 70.81%  |
| 2     | 1833     | 25.77%  |
| 3     | 162      | 2.28%   |
| 0     | 58       | 0.82%   |
| 4     | 18       | 0.25%   |
| 5     | 3        | 0.04%   |
| 7     | 1        | 0.01%   |
| 6     | 1        | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Desktops | Percent |
|---------|----------|---------|
| No      | 5150     | 71.58%  |
| Yes     | 2044     | 28.41%  |
| Unknown | 1        | 0.01%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 656      | 38.52%  |
| Cambridge Silicon Radio         | 466      | 27.36%  |
| Realtek Semiconductor           | 159      | 9.34%   |
| ASUSTek Computer                | 97       | 5.7%    |
| Broadcom                        | 78       | 4.58%   |
| Qualcomm Atheros Communications | 58       | 3.41%   |
| IMC Networks                    | 48       | 2.82%   |
| MediaTek                        | 32       | 1.88%   |
| TP-Link                         | 17       | 1%      |
| Lite-On Technology              | 14       | 0.82%   |
| Integrated System Solution      | 11       | 0.65%   |
| Apple                           | 11       | 0.65%   |
| Belkin Components               | 10       | 0.59%   |
| Dynex                           | 7        | 0.41%   |
| Primax Electronics              | 6        | 0.35%   |
| Ralink                          | 4        | 0.23%   |
| Foxconn / Hon Hai               | 4        | 0.23%   |
| Realtek                         | 3        | 0.18%   |
| ISSC                            | 3        | 0.18%   |
| Edimax Technology               | 3        | 0.18%   |
| Unknown                         | 3        | 0.18%   |
| Micro Star International        | 2        | 0.12%   |
| Hewlett-Packard                 | 2        | 0.12%   |
| Dell                            | 2        | 0.12%   |
| Accel Semiconductor             | 2        | 0.12%   |
| Unknown                         | 1        | 0.06%   |
| Toshiba                         | 1        | 0.06%   |
| SINO WEALTH                     | 1        | 0.06%   |
| Qcom                            | 1        | 0.06%   |
| i.Tech Dynamic Limited          | 1        | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 466      | 27.32%  |
| Intel Bluetooth wireless interface                       | 178      | 10.43%  |
| Intel AX200 Bluetooth                                    | 172      | 10.08%  |
| Realtek Bluetooth Radio                                  | 106      | 6.21%   |
| Intel Wireless-AC 3168 Bluetooth                         | 93       | 5.45%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 56       | 3.28%   |
| Intel AX210 Bluetooth                                    | 50       | 2.93%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 45       | 2.64%   |
| Intel AX201 Bluetooth                                    | 44       | 2.58%   |
| Realtek  Bluetooth 4.2 Adapter                           | 43       | 2.52%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 38       | 2.23%   |
| IMC Networks Bluetooth Radio                             | 35       | 2.05%   |
| MediaTek Wireless_Device                                 | 32       | 1.88%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 29       | 1.7%    |
| Qualcomm Atheros  Bluetooth Device                       | 26       | 1.52%   |
| ASUS ASUS USB-BT500                                      | 19       | 1.11%   |
| TP-Link UB500 Adapter                                    | 17       | 1%      |
| ASUS Bluetooth Radio                                     | 16       | 0.94%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 10       | 0.59%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 10       | 0.59%   |
| Lite-On Bluetooth Device                                 | 10       | 0.59%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 10       | 0.59%   |
| Intel Bluetooth Device                                   | 10       | 0.59%   |
| Broadcom BCM2045 Bluetooth                               | 9        | 0.53%   |
| Integrated System Solution Bluetooth Device              | 8        | 0.47%   |
| ASUS Qualcomm Bluetooth 4.1                              | 8        | 0.47%   |
| ASUS Bluetooth Adapter                                   | 8        | 0.47%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 7        | 0.41%   |
| Belkin Components Bluetooth Mini Dongle                  | 7        | 0.41%   |
| ASUS Bluetooth Device                                    | 7        | 0.41%   |
| Realtek RTL8821A Bluetooth                               | 6        | 0.35%   |
| Primax Rocketfish RF-FLBTAD Bluetooth Adapter            | 6        | 0.35%   |
| IMC Networks Wireless_Device                             | 6        | 0.35%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                   | 5        | 0.29%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE    | 5        | 0.29%   |
| ASUS BCM20702A0                                          | 5        | 0.29%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 5        | 0.29%   |
| Ralink RT3290 Bluetooth                                  | 4        | 0.23%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 4        | 0.23%   |
| IMC Networks Bluetooth Device                            | 4        | 0.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 4435     | 40.83%  |
| AMD                                          | 2901     | 26.71%  |
| Nvidia                                       | 2397     | 22.07%  |
| C-Media Electronics                          | 253      | 2.33%   |
| Creative Labs                                | 185      | 1.7%    |
| Logitech                                     | 72       | 0.66%   |
| Texas Instruments                            | 50       | 0.46%   |
| Generalplus Technology                       | 37       | 0.34%   |
| JMTek                                        | 35       | 0.32%   |
| Creative Technology                          | 33       | 0.3%    |
| VIA Technologies                             | 30       | 0.28%   |
| ASUSTek Computer                             | 29       | 0.27%   |
| Razer USA                                    | 18       | 0.17%   |
| Kingston Technology                          | 17       | 0.16%   |
| Tenx Technology                              | 16       | 0.15%   |
| GN Netcom                                    | 15       | 0.14%   |
| Micro Star International                     | 13       | 0.12%   |
| KTMicro                                      | 12       | 0.11%   |
| Focusrite-Novation                           | 12       | 0.11%   |
| SteelSeries ApS                              | 10       | 0.09%   |
| Plantronics                                  | 10       | 0.09%   |
| Ensoniq                                      | 9        | 0.08%   |
| Corsair                                      | 9        | 0.08%   |
| Yamaha                                       | 8        | 0.07%   |
| XMOS                                         | 8        | 0.07%   |
| Samson Technologies                          | 8        | 0.07%   |
| Giga-Byte Technology                         | 8        | 0.07%   |
| Thesycon Systemsoftware & Consulting         | 7        | 0.06%   |
| M-Audio                                      | 7        | 0.06%   |
| GYROCOM C&C                                  | 7        | 0.06%   |
| Dell                                         | 7        | 0.06%   |
| Blue Microphones                             | 7        | 0.06%   |
| BEHRINGER International                      | 7        | 0.06%   |
| SAVITECH                                     | 6        | 0.06%   |
| PreSonus Audio Electronics                   | 6        | 0.06%   |
| FiiO Electronics Technology                  | 6        | 0.06%   |
| Zoran Co. Personal Media Division (Nogatech) | 5        | 0.05%   |
| Sony                                         | 5        | 0.05%   |
| ROCCAT                                       | 5        | 0.05%   |
| Hewlett-Packard                              | 5        | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 628      | 4.87%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 609      | 4.73%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 604      | 4.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 456      | 3.54%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 454      | 3.52%   |
| AMD Family 17h/19h HD Audio Controller                                            | 449      | 3.49%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 446      | 3.46%   |
| AMD Starship/Matisse HD Audio Controller                                          | 421      | 3.27%   |
| AMD FCH Azalia Controller                                                         | 372      | 2.89%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 323      | 2.51%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 318      | 2.47%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 288      | 2.24%   |
| Intel 200 Series PCH HD Audio                                                     | 276      | 2.14%   |
| Nvidia High Definition Audio Controller                                           | 224      | 1.74%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 224      | 1.74%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 221      | 1.72%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 220      | 1.71%   |
| Intel Cannon Lake PCH cAVS                                                        | 207      | 1.61%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 185      | 1.44%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 180      | 1.4%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 180      | 1.4%    |
| Nvidia GF108 High Definition Audio Controller                                     | 169      | 1.31%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 160      | 1.24%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 150      | 1.16%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 139      | 1.08%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 132      | 1.02%   |
| Nvidia MCP61 High Definition Audio                                                | 127      | 0.99%   |
| Nvidia GF119 HDMI Audio Controller                                                | 127      | 0.99%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 126      | 0.98%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 124      | 0.96%   |
| Nvidia GP108 High Definition Audio Controller                                     | 121      | 0.94%   |
| Nvidia TU116 High Definition Audio Controller                                     | 114      | 0.88%   |
| Nvidia GP106 High Definition Audio Controller                                     | 111      | 0.86%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 111      | 0.86%   |
| Nvidia GK107 HDMI Audio Controller                                                | 105      | 0.82%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 97       | 0.75%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 96       | 0.75%   |
| Intel Smart Sound Technology (SST) Audio Controller                               | 86       | 0.67%   |
| AMD Trinity HDMI Audio Controller                                                 | 85       | 0.66%   |
| AMD Navi 10 HDMI Audio                                                            | 85       | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 1576     | 18.94%  |
| Kingston                     | 1483     | 17.82%  |
| Samsung Electronics          | 868      | 10.43%  |
| SK hynix                     | 668      | 8.03%   |
| Corsair                      | 666      | 8%      |
| Crucial                      | 601      | 7.22%   |
| G.Skill                      | 494      | 5.94%   |
| Micron Technology            | 431      | 5.18%   |
| A-DATA Technology            | 180      | 2.16%   |
| Nanya Technology             | 118      | 1.42%   |
| Unknown                      | 110      | 1.32%   |
| Team                         | 107      | 1.29%   |
| Patriot                      | 105      | 1.26%   |
| Ramaxel Technology           | 82       | 0.99%   |
| GOODRAM                      | 67       | 0.81%   |
| Elpida                       | 66       | 0.79%   |
| Transcend                    | 46       | 0.55%   |
| Smart                        | 39       | 0.47%   |
| Apacer                       | 37       | 0.44%   |
| AMD                          | 37       | 0.44%   |
| Kingmax                      | 27       | 0.32%   |
| Silicon Power                | 23       | 0.28%   |
| GeIL                         | 23       | 0.28%   |
| Unknown (ABCD)               | 22       | 0.26%   |
| Unifosa                      | 21       | 0.25%   |
| Qimonda                      | 16       | 0.19%   |
| PNY                          | 15       | 0.18%   |
| Avant                        | 15       | 0.18%   |
| Multilaser                   | 14       | 0.17%   |
| Teikon                       | 11       | 0.13%   |
| Atermiter                    | 11       | 0.13%   |
| CSX                          | 10       | 0.12%   |
| Patriot Memory (PDP Systems) | 9        | 0.11%   |
| Kllisre                      | 9        | 0.11%   |
| Toshiba                      | 8        | 0.1%    |
| Super Talent                 | 7        | 0.08%   |
| KLEVV                        | 7        | 0.08%   |
| Goldkey                      | 7        | 0.08%   |
| Timetec                      | 6        | 0.07%   |
| OCZ                          | 6        | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown                                                | 110      | 1.19%   |
| Unknown RAM Module 2GB DIMM 800MT/s                    | 108      | 1.17%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 107      | 1.16%   |
| Unknown RAM Module 2GB DIMM SDRAM                      | 106      | 1.14%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 104      | 1.12%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s              | 80       | 0.86%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 68       | 0.73%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 66       | 0.71%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s    | 60       | 0.65%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s               | 58       | 0.63%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s    | 58       | 0.63%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s    | 53       | 0.57%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                   | 51       | 0.55%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s    | 49       | 0.53%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s   | 48       | 0.52%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s              | 46       | 0.5%    |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM 1600MT/s         | 45       | 0.49%   |
| Unknown RAM Module 1GB DIMM SDRAM                      | 42       | 0.45%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s    | 40       | 0.43%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s               | 39       | 0.42%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s    | 39       | 0.42%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s      | 39       | 0.42%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s              | 36       | 0.39%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s               | 35       | 0.38%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s    | 35       | 0.38%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s      | 35       | 0.38%   |
| Unknown RAM Module 2GB DIMM 400MT/s                    | 34       | 0.37%   |
| Unknown RAM Module 1GB DIMM 667MT/s                    | 34       | 0.37%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s | 34       | 0.37%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s              | 33       | 0.36%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s              | 33       | 0.36%   |
| Unknown RAM Module 1GB DIMM 800MT/s                    | 33       | 0.36%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s    | 33       | 0.36%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s   | 32       | 0.35%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s    | 31       | 0.33%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s    | 31       | 0.33%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s  | 31       | 0.33%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                   | 30       | 0.32%   |
| Unknown RAM Module 4GB DIMM SDRAM                      | 29       | 0.31%   |
| Unknown RAM Module 2GB DIMM 667MT/s                    | 29       | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 2848     | 39.6%   |
| DDR4    | 2477     | 34.44%  |
| Unknown | 647      | 9%      |
| DDR2    | 558      | 7.76%   |
| SDRAM   | 482      | 6.7%    |
| DDR     | 104      | 1.45%   |
| DDR5    | 35       | 0.49%   |
| LPDDR4  | 27       | 0.38%   |
| DRAM    | 9        | 0.13%   |
| RAM     | 2        | 0.03%   |
| LPDDR3  | 2        | 0.03%   |
| LPDDR5  | 1        | 0.01%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 6545     | 93.5%   |
| SODIMM       | 434      | 6.2%    |
| RIMM         | 11       | 0.16%   |
| FB-DIMM      | 7        | 0.1%    |
| Row Of Chips | 3        | 0.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 2598     | 32.54%  |
| 4096  | 2400     | 30.06%  |
| 2048  | 1612     | 20.19%  |
| 16384 | 641      | 8.03%   |
| 1024  | 485      | 6.07%   |
| 32768 | 169      | 2.12%   |
| 512   | 71       | 0.89%   |
| 256   | 4        | 0.05%   |
| 15616 | 1        | 0.01%   |
| 12333 | 1        | 0.01%   |
| 3072  | 1        | 0.01%   |
| 64    | 1        | 0.01%   |
| 32    | 1        | 0.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 1670     | 20.65%  |
| 1333    | 1209     | 14.95%  |
| 800     | 468      | 5.79%   |
| 3200    | 453      | 5.6%    |
| 2400    | 434      | 5.37%   |
| 2667    | 378      | 4.67%   |
| 3600    | 336      | 4.15%   |
| 2133    | 334      | 4.13%   |
| 667     | 331      | 4.09%   |
| Unknown | 266      | 3.29%   |
| 1867    | 176      | 2.18%   |
| 1866    | 146      | 1.81%   |
| 2666    | 128      | 1.58%   |
| 1800    | 128      | 1.58%   |
| 2933    | 107      | 1.32%   |
| 1066    | 107      | 1.32%   |
| 3400    | 103      | 1.27%   |
| 3000    | 102      | 1.26%   |
| 400     | 88       | 1.09%   |
| 3733    | 79       | 0.98%   |
| 1067    | 73       | 0.9%    |
| 533     | 70       | 0.87%   |
| 3800    | 50       | 0.62%   |
| 2800    | 47       | 0.58%   |
| 3866    | 45       | 0.56%   |
| 1334    | 44       | 0.54%   |
| 3266    | 43       | 0.53%   |
| 3533    | 38       | 0.47%   |
| 3466    | 37       | 0.46%   |
| 2048    | 36       | 0.45%   |
| 3666    | 32       | 0.4%    |
| 2000    | 32       | 0.4%    |
| 1648    | 26       | 0.32%   |
| 333     | 24       | 0.3%    |
| 49926   | 22       | 0.27%   |
| 3066    | 22       | 0.27%   |
| 1639    | 22       | 0.27%   |
| 2733    | 20       | 0.25%   |
| 2200    | 20       | 0.25%   |
| 3151    | 16       | 0.2%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 177      | 39.86%  |
| Brother Industries    | 92       | 20.72%  |
| Canon                 | 60       | 13.51%  |
| Seiko Epson           | 40       | 9.01%   |
| Samsung Electronics   | 40       | 9.01%   |
| Lexmark International | 9        | 2.03%   |
| QinHeng Electronics   | 5        | 1.13%   |
| Prolific Technology   | 5        | 1.13%   |
| Xerox                 | 3        | 0.68%   |
| Kyocera               | 3        | 0.68%   |
| Dymo-CoStar           | 3        | 0.68%   |
| Ricoh                 | 2        | 0.45%   |
| Zebra                 | 1        | 0.23%   |
| Philips (or NXP)      | 1        | 0.23%   |
| Oki Data              | 1        | 0.23%   |
| NXP Semiconductors    | 1        | 0.23%   |
| Citizen               | 1        | 0.23%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| HP DeskJet 2600 series                 | 11       | 2.44%   |
| HP ENVY 4520 series                    | 7        | 1.55%   |
| HP DeskJet 2700 series                 | 7        | 1.55%   |
| Samsung M2020 Series                   | 6        | 1.33%   |
| Brother HL-L2390DW                     | 6        | 1.33%   |
| Samsung ML-1640 Series Laser Printer   | 5        | 1.11%   |
| Samsung M2070 Series                   | 5        | 1.11%   |
| QinHeng CH340S                         | 5        | 1.11%   |
| Prolific PL2305 Parallel Port          | 5        | 1.11%   |
| HP LaserJet 1020                       | 5        | 1.11%   |
| HP DeskJet 3630 series                 | 5        | 1.11%   |
| HP DeskJet 2130 series                 | 5        | 1.11%   |
| Seiko Epson ET-2710 Series             | 4        | 0.89%   |
| HP LaserJet P1006                      | 4        | 0.89%   |
| HP LaserJet P1005                      | 4        | 0.89%   |
| HP LaserJet 1018                       | 4        | 0.89%   |
| HP Ink Tank Wireless 410 series        | 4        | 0.89%   |
| Canon PIXMA MX920 Series               | 4        | 0.89%   |
| Canon PIXMA MG3600 Series              | 4        | 0.89%   |
| Canon LiDE 400                         | 4        | 0.89%   |
| Canon LiDE 300                         | 4        | 0.89%   |
| Brother Printer                        | 4        | 0.89%   |
| Brother HL-3140CW series               | 4        | 0.89%   |
| Seiko Epson L365 Series                | 3        | 0.67%   |
| Seiko Epson L120 Series                | 3        | 0.67%   |
| HP OfficeJet 3830 series               | 3        | 0.67%   |
| HP LaserJet Pro M148f-M149f            | 3        | 0.67%   |
| HP LaserJet 1010                       | 3        | 0.67%   |
| HP ENVY 5000 series                    | 3        | 0.67%   |
| HP DeskJet 4100 series                 | 3        | 0.67%   |
| HP Deskjet 1050 J410                   | 3        | 0.67%   |
| Canon TS5100 series                    | 3        | 0.67%   |
| Brother MFC-L2710DW series             | 3        | 0.67%   |
| Brother MFC-L2700DW                    | 3        | 0.67%   |
| Brother MFC-J470DW                     | 3        | 0.67%   |
| Brother HL-L2360D series               | 3        | 0.67%   |
| Brother DCP-T310                       | 3        | 0.67%   |
| Seiko Epson XP-240 Series              | 2        | 0.44%   |
| Seiko Epson WF-2510 Series             | 2        | 0.44%   |
| Seiko Epson Stylus NX230/SX235W Series | 2        | 0.44%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Canon                       | 50       | 56.82%  |
| Hewlett-Packard             | 13       | 14.77%  |
| Seiko Epson                 | 10       | 11.36%  |
| Mustek Systems              | 7        | 7.95%   |
| AGFA-Gevaert NV             | 3        | 3.41%   |
| KYE Systems (Mouse Systems) | 2        | 2.27%   |
| Plustek                     | 1        | 1.14%   |
| Fujitsu                     | 1        | 1.14%   |
| Acer Peripherals (now BenQ) | 1        | 1.14%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 210                                  | 7        | 7.95%   |
| Canon CanoScan LiDE 110                                  | 7        | 7.95%   |
| Canon CanoScan LiDE 100                                  | 6        | 6.82%   |
| Canon CanoScan LIDE 25                                   | 5        | 5.68%   |
| Canon CanoScan LiDE 120                                  | 4        | 4.55%   |
| Mustek Systems ScanExpress 1200 UB                       | 3        | 3.41%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 3        | 3.41%   |
| Canon CanoScan N1240U/LiDE 30                            | 3        | 3.41%   |
| Canon CanoScan LiDE 220                                  | 3        | 3.41%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]            | 2        | 2.27%   |
| HP ScanJet 4500C/5550C                                   | 2        | 2.27%   |
| HP ScanJet 2400c                                         | 2        | 2.27%   |
| Canon CanoScan LiDE 70                                   | 2        | 2.27%   |
| Canon CanoScan LiDE 60                                   | 2        | 2.27%   |
| Canon CanoScan LiDE 200                                  | 2        | 2.27%   |
| AGFA-Gevaert NV SnapScan e20                             | 2        | 2.27%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]              | 1        | 1.14%   |
| Seiko Epson GT-X770 [Perfection V500]                    | 1        | 1.14%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]  | 1        | 1.14%   |
| Seiko Epson GT-F700 [Perfection V350]                    | 1        | 1.14%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]        | 1        | 1.14%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1        | 1.14%   |
| Seiko Epson GT-9400UF [Perfection 3170]                  | 1        | 1.14%   |
| Seiko Epson GT-7400U [Perfection 1270]                   | 1        | 1.14%   |
| Plustek 600DPI USB Scanner                               | 1        | 1.14%   |
| Mustek Systems SNAPSCAN e22                              | 1        | 1.14%   |
| Mustek Systems ScanExpress 1200 CU                       | 1        | 1.14%   |
| Mustek Systems BearPaw 2448 CU Pro                       | 1        | 1.14%   |
| Mustek Systems BearPaw 1200 CU Plus                      | 1        | 1.14%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid4             | 1        | 1.14%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid 1200 XE      | 1        | 1.14%   |
| HP ScanJet G4010                                         | 1        | 1.14%   |
| HP Scanjet G2710                                         | 1        | 1.14%   |
| HP ScanJet 4570c                                         | 1        | 1.14%   |
| HP ScanJet 4370                                          | 1        | 1.14%   |
| HP ScanJet 3800c                                         | 1        | 1.14%   |
| HP ScanJet 3670                                          | 1        | 1.14%   |
| HP ScanJet 2300c                                         | 1        | 1.14%   |
| HP ScanJet 2200c                                         | 1        | 1.14%   |
| HP PSC 1200                                              | 1        | 1.14%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 338      | 36.15%  |
| Microdia                               | 81       | 8.66%   |
| Microsoft                              | 62       | 6.63%   |
| Z-Star Microelectronics                | 32       | 3.42%   |
| Chicony Electronics                    | 32       | 3.42%   |
| Generalplus Technology                 | 25       | 2.67%   |
| Sunplus Innovation Technology          | 22       | 2.35%   |
| Realtek Semiconductor                  | 21       | 2.25%   |
| GEMBIRD                                | 20       | 2.14%   |
| KYE Systems (Mouse Systems)            | 18       | 1.93%   |
| Samsung Electronics                    | 17       | 1.82%   |
| Aveo Technology                        | 17       | 1.82%   |
| Creative Technology                    | 16       | 1.71%   |
| ARC International                      | 15       | 1.6%    |
| Hewlett-Packard                        | 14       | 1.5%    |
| Cubeternet                             | 13       | 1.39%   |
| Apple                                  | 13       | 1.39%   |
| Jieli Technology                       | 12       | 1.28%   |
| Unknown                                | 9        | 0.96%   |
| Huawei Technologies                    | 9        | 0.96%   |
| Trust                                  | 8        | 0.86%   |
| Arkmicro Technologies                  | 8        | 0.86%   |
| Alcor Micro                            | 7        | 0.75%   |
| A4Tech                                 | 7        | 0.75%   |
| WaveRider Communications               | 6        | 0.64%   |
| Sonix Technology                       | 6        | 0.64%   |
| Pixart Imaging                         | 6        | 0.64%   |
| MacroSilicon                           | 6        | 0.64%   |
| HD 2MP WEBCAM                          | 6        | 0.64%   |
| Genesys Logic                          | 6        | 0.64%   |
| AVerMedia Technologies                 | 6        | 0.64%   |
| WCM_USB                                | 4        | 0.43%   |
| Razer USA                              | 4        | 0.43%   |
| IMC Networks                           | 4        | 0.43%   |
| Cheng Uei Precision Industry (Foxlink) | 4        | 0.43%   |
| Bison Electronics                      | 4        | 0.43%   |
| Silicon Motion                         | 3        | 0.32%   |
| LG Electronics                         | 3        | 0.32%   |
| Guillemot                              | 3        | 0.32%   |
| Valve Software                         | 2        | 0.21%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 82       | 8.76%   |
| Logitech HD Pro Webcam C920                       | 39       | 4.17%   |
| Logitech Webcam C310                              | 32       | 3.42%   |
| Logitech HD Webcam C525                           | 27       | 2.88%   |
| Microsoft LifeCam HD-3000                         | 22       | 2.35%   |
| Logitech Webcam C170                              | 21       | 2.24%   |
| Generalplus GENERAL WEBCAM                        | 21       | 2.24%   |
| Samsung Galaxy series, misc. (MTP mode)           | 17       | 1.82%   |
| Microdia Camera                                   | 17       | 1.82%   |
| Microdia Webcam Vitade AF                         | 15       | 1.6%    |
| Microdia USB 2.0 Camera                           | 15       | 1.6%    |
| ARC International Camera                          | 15       | 1.6%    |
| Aveo USB2.0 Camera                                | 13       | 1.39%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                   | 13       | 1.39%   |
| Sunplus Full HD webcam                            | 12       | 1.28%   |
| Logitech HD Webcam C615                           | 12       | 1.28%   |
| Logitech C922 Pro Stream Webcam                   | 12       | 1.28%   |
| Jieli USB PHY 2.0                                 | 12       | 1.28%   |
| Logitech QuickCam Pro 9000                        | 11       | 1.18%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 11       | 1.18%   |
| Microdia Sonix USB 2.0 Camera                     | 10       | 1.07%   |
| Microdia Integrated Camera                        | 9        | 0.96%   |
| Logitech HD Webcam C910                           | 9        | 0.96%   |
| Huawei UVC Camera                                 | 9        | 0.96%   |
| GEMBIRD USB2.0 PC CAMERA                          | 9        | 0.96%   |
| Z-Star Venus USB2.0 Camera                        | 8        | 0.85%   |
| Z-Star A4 TECH USB2.0 PC Camera E                 | 8        | 0.85%   |
| Unknown HD camera                                 | 8        | 0.85%   |
| Logitech HD Webcam C510                           | 8        | 0.85%   |
| Cubeternet USB2.0 Camera                          | 8        | 0.85%   |
| Microsoft LifeCam Cinema                          | 7        | 0.75%   |
| Logitech Webcam C930e                             | 7        | 0.75%   |
| HP Webcam HD 2300                                 | 7        | 0.75%   |
| Chicony HP High Definition 1MP Webcam             | 7        | 0.75%   |
| Z-Star A4 TECH USB2.0 PC Camera J                 | 6        | 0.64%   |
| Sunplus MTD Camera                                | 6        | 0.64%   |
| Realtek USB Camera                                | 6        | 0.64%   |
| Realtek Full HD webcam                            | 6        | 0.64%   |
| Microsoft LifeCam VX-5000                         | 6        | 0.64%   |
| Microsoft LifeCam Studio                          | 6        | 0.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| AuthenTec             | 3        | 37.5%   |
| Upek                  | 2        | 25%     |
| Validity Sensors      | 1        | 12.5%   |
| LighTuning Technology | 1        | 12.5%   |
| DigitalPersona        | 1        | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2        | 25%     |
| AuthenTec AES1600                                      | 2        | 25%     |
| Validity Sensors VFS 5011 fingerprint sensor           | 1        | 12.5%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1        | 12.5%   |
| DigitalPersona Fingerprint Reader                      | 1        | 12.5%   |
| AuthenTec Fingerprint Sensor                           | 1        | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Alcor Micro                       | 6        | 19.35%  |
| SCM Microsystems                  | 5        | 16.13%  |
| Gemalto (was Gemplus)             | 4        | 12.9%   |
| Realtek Semiconductor             | 3        | 9.68%   |
| BIT4ID                            | 3        | 9.68%   |
| Reiner SCT Kartensysteme          | 2        | 6.45%   |
| OmniKey                           | 2        | 6.45%   |
| Advanced Card Systems             | 2        | 6.45%   |
| VASCO Data Security International | 1        | 3.23%   |
| Fujitsu Siemens Computers         | 1        | 3.23%   |
| Cherry                            | 1        | 3.23%   |
| Castles Technology                | 1        | 3.23%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                        | 4        | 12.9%   |
| Realtek Semiconductor Smart Card Reader Interface                          | 3        | 9.68%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 3        | 9.68%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 2        | 6.45%   |
| Bit4id miniLector EVO                                                      | 2        | 6.45%   |
| Alcor Micro Watchdata W 1981                                               | 2        | 6.45%   |
| Advanced Card Systems ACR38 SmartCard Reader                               | 2        | 6.45%   |
| VASCO Data Security International Digipass 905 SmartCard Reader            | 1        | 3.23%   |
| SCM Microsystems uTrust 3700 F CL Reader                                   | 1        | 3.23%   |
| SCM Microsystems SCR335 SmartCard Reader                                   | 1        | 3.23%   |
| SCM Microsystems SCR333 SmartCard Reader                                   | 1        | 3.23%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                     | 1        | 3.23%   |
| SCM Microsystems CLOUD 2700 F Smart Card Reader                            | 1        | 3.23%   |
| OmniKey CardMan 3021 / 3121                                                | 1        | 3.23%   |
| OmniKey CardMan 1021                                                       | 1        | 3.23%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                           | 1        | 3.23%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                              | 1        | 3.23%   |
| Cherry Smart Terminal XX44                                                 | 1        | 3.23%   |
| Castles Technology EZCCID Smart Card Reader                                | 1        | 3.23%   |
| BIT4ID miniLector AIR NFC v3                                               | 1        | 3.23%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 6436     | 90.32%  |
| 1     | 642      | 9.01%   |
| 2     | 36       | 0.51%   |
| 3     | 9        | 0.13%   |
| 7     | 1        | 0.01%   |
| 6     | 1        | 0.01%   |
| 4     | 1        | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 347      | 47.28%  |
| Net/wireless             | 147      | 20.03%  |
| Unassigned class         | 56       | 7.63%   |
| Communication controller | 45       | 6.13%   |
| Multimedia controller    | 39       | 5.31%   |
| Chipcard                 | 30       | 4.09%   |
| Camera                   | 17       | 2.32%   |
| Bluetooth                | 13       | 1.77%   |
| Fingerprint reader       | 8        | 1.09%   |
| Card reader              | 7        | 0.95%   |
| Network                  | 6        | 0.82%   |
| Sound                    | 4        | 0.54%   |
| Wireless                 | 3        | 0.41%   |
| Net/ethernet             | 3        | 0.41%   |
| Modem                    | 3        | 0.41%   |
| Storage/raid             | 2        | 0.27%   |
| Storage/ata              | 2        | 0.27%   |
| Unclassified device      | 1        | 0.14%   |
| Dvb card                 | 1        | 0.14%   |

