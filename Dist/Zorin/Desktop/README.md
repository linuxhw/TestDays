Zorin - Tested Hardware & Statistics (Desktops)
-----------------------------------------------

A project to collect tested hardware configurations for Zorin.

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

Total: 2846

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 09CCh                       | [15bfdf7213](https://linux-hardware.org/?probe=15bfdf7213) | Aug 12, 2023 |
| Biostar       | A770 A2+                    | [d35bac0620](https://linux-hardware.org/?probe=d35bac0620) | Aug 12, 2023 |
| Biostar       | A770 A2+                    | [fb7d0009fd](https://linux-hardware.org/?probe=fb7d0009fd) | Aug 12, 2023 |
| HP            | 3032h                       | [1727f042cd](https://linux-hardware.org/?probe=1727f042cd) | Aug 11, 2023 |
| Intel         | DZ68BC AAG30742-401         | [9bf37df045](https://linux-hardware.org/?probe=9bf37df045) | Aug 10, 2023 |
| Dell          | 0WMJ54 A01                  | [6e9ca3c833](https://linux-hardware.org/?probe=6e9ca3c833) | Aug 09, 2023 |
| HP            | 3032h                       | [03a8cc31ea](https://linux-hardware.org/?probe=03a8cc31ea) | Aug 09, 2023 |
| Pegatron      | BOWIE                       | [6047747c8f](https://linux-hardware.org/?probe=6047747c8f) | Aug 09, 2023 |
| Pegatron      | BOWIE                       | [8a11b56d79](https://linux-hardware.org/?probe=8a11b56d79) | Aug 09, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [2e30c62b25](https://linux-hardware.org/?probe=2e30c62b25) | Aug 08, 2023 |
| Intel         | X79M-S                      | [8250cad3d6](https://linux-hardware.org/?probe=8250cad3d6) | Aug 08, 2023 |
| Gigabyte      | B450 AORUS M                | [965220ce86](https://linux-hardware.org/?probe=965220ce86) | Aug 07, 2023 |
| Pegatron      | IPMMB-MQ1                   | [70c450c395](https://linux-hardware.org/?probe=70c450c395) | Aug 06, 2023 |
| MSI           | Z170A GAMING PRO CARBON     | [6b22ae1f36](https://linux-hardware.org/?probe=6b22ae1f36) | Aug 06, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [1af709c14e](https://linux-hardware.org/?probe=1af709c14e) | Aug 05, 2023 |
| Gigabyte      | Z97X-UD5H                   | [3bc330734d](https://linux-hardware.org/?probe=3bc330734d) | Aug 05, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [3b5e9f52a2](https://linux-hardware.org/?probe=3b5e9f52a2) | Aug 05, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [5d998a099e](https://linux-hardware.org/?probe=5d998a099e) | Aug 05, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [e57d71e056](https://linux-hardware.org/?probe=e57d71e056) | Aug 05, 2023 |
| Unknown       | Unknown                     | [8ee9cccace](https://linux-hardware.org/?probe=8ee9cccace) | Aug 05, 2023 |
| ASRock        | N68-VS3 UCC                 | [3793d876eb](https://linux-hardware.org/?probe=3793d876eb) | Aug 04, 2023 |
| Gigabyte      | B550M DS3H AC               | [f27f9b2a7f](https://linux-hardware.org/?probe=f27f9b2a7f) | Aug 03, 2023 |
| Gigabyte      | B550M DS3H AC               | [8193f810ab](https://linux-hardware.org/?probe=8193f810ab) | Aug 03, 2023 |
| ASUSTek       | PRIME B450M-K II            | [35cf0fd859](https://linux-hardware.org/?probe=35cf0fd859) | Aug 03, 2023 |
| Intel         | X79M-S                      | [5a4d94f325](https://linux-hardware.org/?probe=5a4d94f325) | Aug 02, 2023 |
| HP            | 89B5 A                      | [cb6f36f32c](https://linux-hardware.org/?probe=cb6f36f32c) | Aug 02, 2023 |
| Pegatron      | BOWIE                       | [cfce53f1a3](https://linux-hardware.org/?probe=cfce53f1a3) | Aug 02, 2023 |
| Unknown       | Unknown                     | [731a8b0e31](https://linux-hardware.org/?probe=731a8b0e31) | Aug 02, 2023 |
| ASUSTek       | P8H61-M LX                  | [287740b630](https://linux-hardware.org/?probe=287740b630) | Aug 01, 2023 |
| HP            | 1496                        | [24863488f0](https://linux-hardware.org/?probe=24863488f0) | Aug 01, 2023 |
| Dell          | 0HJ054                      | [85ceb83c22](https://linux-hardware.org/?probe=85ceb83c22) | Jul 31, 2023 |
| ASUSTek       | M4N68T-M LE                 | [90dce7a9cf](https://linux-hardware.org/?probe=90dce7a9cf) | Jul 30, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [0ce1be51b9](https://linux-hardware.org/?probe=0ce1be51b9) | Jul 30, 2023 |
| Gigabyte      | M68MT-S2                    | [b1125cd76c](https://linux-hardware.org/?probe=b1125cd76c) | Jul 29, 2023 |
| ASUSTek       | H97-PRO GAMER               | [1771e4ca4b](https://linux-hardware.org/?probe=1771e4ca4b) | Jul 29, 2023 |
| ASUSTek       | H97-PRO GAMER               | [e668b29cf4](https://linux-hardware.org/?probe=e668b29cf4) | Jul 29, 2023 |
| ASUSTek       | P7H55-M LX                  | [bc92202f16](https://linux-hardware.org/?probe=bc92202f16) | Jul 29, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | [8c930cc5e4](https://linux-hardware.org/?probe=8c930cc5e4) | Jul 29, 2023 |
| MSI           | B75MA-E33                   | [310207e0fd](https://linux-hardware.org/?probe=310207e0fd) | Jul 29, 2023 |
| Pegatron      | BOWIE                       | [4d413cb864](https://linux-hardware.org/?probe=4d413cb864) | Jul 28, 2023 |
| HP            | 3397                        | [e61ccd6dbf](https://linux-hardware.org/?probe=e61ccd6dbf) | Jul 27, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [e7fdf45ff0](https://linux-hardware.org/?probe=e7fdf45ff0) | Jul 27, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [2f12124bed](https://linux-hardware.org/?probe=2f12124bed) | Jul 27, 2023 |
| MP            | MS-7848                     | [3dd9f22548](https://linux-hardware.org/?probe=3dd9f22548) | Jul 26, 2023 |
| Acer          | Elena                       | [78eff851f2](https://linux-hardware.org/?probe=78eff851f2) | Jul 26, 2023 |
| ASRock        | Z97M Pro4                   | [1b062f3c31](https://linux-hardware.org/?probe=1b062f3c31) | Jul 26, 2023 |
| ASRock        | Z97M Pro4                   | [bca4424b5d](https://linux-hardware.org/?probe=bca4424b5d) | Jul 26, 2023 |
| ASUSTek       | B250 MINING EXPERT          | [0236b3ce26](https://linux-hardware.org/?probe=0236b3ce26) | Jul 26, 2023 |
| Dell          | 088DT1 A01                  | [1355a4f2f4](https://linux-hardware.org/?probe=1355a4f2f4) | Jul 25, 2023 |
| HP            | 8350                        | [f17382c501](https://linux-hardware.org/?probe=f17382c501) | Jul 23, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [13bb65f561](https://linux-hardware.org/?probe=13bb65f561) | Jul 23, 2023 |
| Dell          | 0MN1TX A04                  | [4ff31f4185](https://linux-hardware.org/?probe=4ff31f4185) | Jul 22, 2023 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [b8cf03e7b7](https://linux-hardware.org/?probe=b8cf03e7b7) | Jul 22, 2023 |
| ASUSTek       | F1A55-M LX                  | [87b85c2e28](https://linux-hardware.org/?probe=87b85c2e28) | Jul 22, 2023 |
| ASRock        | B85M                        | [c4f0b0b1fa](https://linux-hardware.org/?probe=c4f0b0b1fa) | Jul 22, 2023 |
| HP            | 3048h                       | [1be902df43](https://linux-hardware.org/?probe=1be902df43) | Jul 21, 2023 |
| HP            | 3047h                       | [07de35877b](https://linux-hardware.org/?probe=07de35877b) | Jul 21, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | [9afd0f1d0f](https://linux-hardware.org/?probe=9afd0f1d0f) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [35c4e6ad97](https://linux-hardware.org/?probe=35c4e6ad97) | Jul 20, 2023 |
| HP            | 8767 A                      | [d5275f1025](https://linux-hardware.org/?probe=d5275f1025) | Jul 20, 2023 |
| Dell          | 0F5C5X A00                  | [3832c8f626](https://linux-hardware.org/?probe=3832c8f626) | Jul 20, 2023 |
| Dell          | 0C27VV A02                  | [da1c963814](https://linux-hardware.org/?probe=da1c963814) | Jul 19, 2023 |
| Dell          | 0C27VV A02                  | [02008985ce](https://linux-hardware.org/?probe=02008985ce) | Jul 19, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | [57b17e7ae1](https://linux-hardware.org/?probe=57b17e7ae1) | Jul 15, 2023 |
| Gigabyte      | Z370M AORUS Gaming-CF       | [64a0d52846](https://linux-hardware.org/?probe=64a0d52846) | Jul 15, 2023 |
| Gigabyte      | B450 AORUS M                | [2f5c2842c2](https://linux-hardware.org/?probe=2f5c2842c2) | Jul 14, 2023 |
| Dell          | 0FDY5C A00                  | [35399aae18](https://linux-hardware.org/?probe=35399aae18) | Jul 14, 2023 |
| Dell          | 0D441T A03                  | [622890c12a](https://linux-hardware.org/?probe=622890c12a) | Jul 14, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [b690698c10](https://linux-hardware.org/?probe=b690698c10) | Jul 12, 2023 |
| HP            | 8299                        | [763cebf303](https://linux-hardware.org/?probe=763cebf303) | Jul 12, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [7c6ad4407b](https://linux-hardware.org/?probe=7c6ad4407b) | Jul 11, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [c81c5855d4](https://linux-hardware.org/?probe=c81c5855d4) | Jul 11, 2023 |
| Acer          | EG31M R01-B1                | [dbc5e1d5db](https://linux-hardware.org/?probe=dbc5e1d5db) | Jul 11, 2023 |
| Acer          | EG31M R01-B1                | [12f533494b](https://linux-hardware.org/?probe=12f533494b) | Jul 11, 2023 |
| ASRock        | A320M-HDV R4.0              | [ab81f36697](https://linux-hardware.org/?probe=ab81f36697) | Jul 11, 2023 |
| Dell          | 09WH54 A00                  | [b118891f3d](https://linux-hardware.org/?probe=b118891f3d) | Jul 10, 2023 |
| ASRock        | B460M Pro4                  | [c972293107](https://linux-hardware.org/?probe=c972293107) | Jul 10, 2023 |
| ASUSTek       | GRYPHON Z87                 | [2ed1092e31](https://linux-hardware.org/?probe=2ed1092e31) | Jul 10, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [213c80bbee](https://linux-hardware.org/?probe=213c80bbee) | Jul 09, 2023 |
| ASUSTek       | PRIME B350M-A               | [be65f2aa45](https://linux-hardware.org/?probe=be65f2aa45) | Jul 08, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [2d342d7a37](https://linux-hardware.org/?probe=2d342d7a37) | Jul 07, 2023 |
| Dell          | 0HN7XN A01                  | [24a4044173](https://linux-hardware.org/?probe=24a4044173) | Jul 06, 2023 |
| Gigabyte      | B75M-D3H                    | [8a9c93e501](https://linux-hardware.org/?probe=8a9c93e501) | Jul 06, 2023 |
| ASRock        | FP6D4-P1                    | [42b5bdcdd7](https://linux-hardware.org/?probe=42b5bdcdd7) | Jul 05, 2023 |
| Positivo      | POS-EIH61CE SIM             | [48b35c757d](https://linux-hardware.org/?probe=48b35c757d) | Jul 05, 2023 |
| Intel         | H55                         | [8f8ff68380](https://linux-hardware.org/?probe=8f8ff68380) | Jul 04, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [9bca67bb40](https://linux-hardware.org/?probe=9bca67bb40) | Jul 04, 2023 |
| HP            | 21F5 0A                     | [bc7304ba1c](https://linux-hardware.org/?probe=bc7304ba1c) | Jul 04, 2023 |
| MSI           | 760GM-P23                   | [452fe27c46](https://linux-hardware.org/?probe=452fe27c46) | Jul 04, 2023 |
| MSI           | 760GM-P23                   | [168d5b0b7b](https://linux-hardware.org/?probe=168d5b0b7b) | Jul 04, 2023 |
| Foxconn       | G41S/G41S-K                 | [21adb87fbd](https://linux-hardware.org/?probe=21adb87fbd) | Jul 04, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [7672f159bf](https://linux-hardware.org/?probe=7672f159bf) | Jul 03, 2023 |
| Dell          | 0GY6Y8 A02                  | [729dbec695](https://linux-hardware.org/?probe=729dbec695) | Jul 02, 2023 |
| MSI           | MS-B9181                    | [fef890b931](https://linux-hardware.org/?probe=fef890b931) | Jul 02, 2023 |
| MSI           | MS-B9181                    | [47b3ce0c58](https://linux-hardware.org/?probe=47b3ce0c58) | Jul 02, 2023 |
| MSI           | PRO Z690-A WIFI             | [2bc4b36c94](https://linux-hardware.org/?probe=2bc4b36c94) | Jul 02, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS AC    | [c787bf91c3](https://linux-hardware.org/?probe=c787bf91c3) | Jul 02, 2023 |
| Win Elemen... | M9                          | [2e5ea821f1](https://linux-hardware.org/?probe=2e5ea821f1) | Jul 01, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS AC    | [a4e29f77e5](https://linux-hardware.org/?probe=a4e29f77e5) | Jul 01, 2023 |
| MSI           | H61M-P31                    | [9012219f61](https://linux-hardware.org/?probe=9012219f61) | Jun 29, 2023 |
| Gigabyte      | A320M-S2H-CF                | [bb1cb1ef13](https://linux-hardware.org/?probe=bb1cb1ef13) | Jun 29, 2023 |
| Gigabyte      | P31-DS3L                    | [0d32728bdf](https://linux-hardware.org/?probe=0d32728bdf) | Jun 28, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [0a35c3c750](https://linux-hardware.org/?probe=0a35c3c750) | Jun 27, 2023 |
| HP            | 8906 SMVB                   | [18ab778722](https://linux-hardware.org/?probe=18ab778722) | Jun 26, 2023 |
| Lenovo        | ThinkCentre M91p 4524WAP    | [85eeeb037b](https://linux-hardware.org/?probe=85eeeb037b) | Jun 26, 2023 |
| Gigabyte      | G31M-ES2L                   | [be14b80f2c](https://linux-hardware.org/?probe=be14b80f2c) | Jun 24, 2023 |
| Positivo      | POS-AG31AP                  | [bd3b3228c6](https://linux-hardware.org/?probe=bd3b3228c6) | Jun 24, 2023 |
| Intel         | D946GZIS AAD66165-301       | [dac65b1c2c](https://linux-hardware.org/?probe=dac65b1c2c) | Jun 24, 2023 |
| Dell          | 00V62H A01                  | [23134d6c71](https://linux-hardware.org/?probe=23134d6c71) | Jun 24, 2023 |
| ASUSTek       | P5B                         | [a62968d622](https://linux-hardware.org/?probe=a62968d622) | Jun 24, 2023 |
| ASUSTek       | F2A85-V PRO                 | [011552703c](https://linux-hardware.org/?probe=011552703c) | Jun 24, 2023 |
| Positivo      | POS-AG31AP                  | [1dd704fab9](https://linux-hardware.org/?probe=1dd704fab9) | Jun 22, 2023 |
| Dell          | 0G9322                      | [a742a26282](https://linux-hardware.org/?probe=a742a26282) | Jun 22, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [1e11366a3e](https://linux-hardware.org/?probe=1e11366a3e) | Jun 21, 2023 |
| Intel         | D34010WYK H14771-304        | [0d3af8114b](https://linux-hardware.org/?probe=0d3af8114b) | Jun 20, 2023 |
| AZW           | GTR V02                     | [f9bee18426](https://linux-hardware.org/?probe=f9bee18426) | Jun 19, 2023 |
| ASUSTek       | P5LD2                       | [7038963b77](https://linux-hardware.org/?probe=7038963b77) | Jun 18, 2023 |
| Lenovo        | ThinkCentre M91p 4524WAP    | [707e7d9862](https://linux-hardware.org/?probe=707e7d9862) | Jun 17, 2023 |
| Pegatron      | BOWIE                       | [a2bbc6abd3](https://linux-hardware.org/?probe=a2bbc6abd3) | Jun 17, 2023 |
| ASRock        | B85M                        | [19f8b16937](https://linux-hardware.org/?probe=19f8b16937) | Jun 15, 2023 |
| Dell          | 0KC9NP A01                  | [b00d413241](https://linux-hardware.org/?probe=b00d413241) | Jun 14, 2023 |
| Dell          | 0KC9NP A01                  | [1d487a1ed5](https://linux-hardware.org/?probe=1d487a1ed5) | Jun 14, 2023 |
| Dell          | 0WR7PY A02                  | [eab79964fb](https://linux-hardware.org/?probe=eab79964fb) | Jun 14, 2023 |
| Vorke         | V1 Plus                     | [a63988d437](https://linux-hardware.org/?probe=a63988d437) | Jun 14, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [c1992a1680](https://linux-hardware.org/?probe=c1992a1680) | Jun 13, 2023 |
| Pegatron      | BOWIE                       | [2794a5aa86](https://linux-hardware.org/?probe=2794a5aa86) | Jun 12, 2023 |
| ASUSTek       | P5B                         | [6308a1c633](https://linux-hardware.org/?probe=6308a1c633) | Jun 12, 2023 |
| Toshiba       | Mobile Intel 4 Series/IC... | [45696e1d1b](https://linux-hardware.org/?probe=45696e1d1b) | Jun 12, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [373e36422d](https://linux-hardware.org/?probe=373e36422d) | Jun 12, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | [9ea7188339](https://linux-hardware.org/?probe=9ea7188339) | Jun 11, 2023 |
| HP            | 8350                        | [8a40ff28c8](https://linux-hardware.org/?probe=8a40ff28c8) | Jun 11, 2023 |
| ASUSTek       | P5B                         | [794635cbea](https://linux-hardware.org/?probe=794635cbea) | Jun 10, 2023 |
| MP            | MS-7848                     | [cd63c98850](https://linux-hardware.org/?probe=cd63c98850) | Jun 10, 2023 |
| Nvidia        | MCP79                       | [8203509a77](https://linux-hardware.org/?probe=8203509a77) | Jun 09, 2023 |
| ASRock        | H81M-HDS                    | [e1ff6f4e2f](https://linux-hardware.org/?probe=e1ff6f4e2f) | Jun 08, 2023 |
| ASUSTek       | P5B                         | [32baec6c0f](https://linux-hardware.org/?probe=32baec6c0f) | Jun 08, 2023 |
| Shenzhen M... | F7BFD                       | [74cf1d0b63](https://linux-hardware.org/?probe=74cf1d0b63) | Jun 08, 2023 |
| Shenzhen M... | F7BFD                       | [88cbeea389](https://linux-hardware.org/?probe=88cbeea389) | Jun 08, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [20d28155d8](https://linux-hardware.org/?probe=20d28155d8) | Jun 08, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [517cbd7f48](https://linux-hardware.org/?probe=517cbd7f48) | Jun 08, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [2ad7aefc45](https://linux-hardware.org/?probe=2ad7aefc45) | Jun 07, 2023 |
| HP            | 8350                        | [113be26d4c](https://linux-hardware.org/?probe=113be26d4c) | Jun 07, 2023 |
| Dell          | 0G9322                      | [e81a7f788a](https://linux-hardware.org/?probe=e81a7f788a) | Jun 07, 2023 |
| Nvidia        | MCP79                       | [bf109ed28f](https://linux-hardware.org/?probe=bf109ed28f) | Jun 06, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [79f63dcf8e](https://linux-hardware.org/?probe=79f63dcf8e) | Jun 06, 2023 |
| ASUSTek       | CM1730,CM1830               | [2cc76d0cd9](https://linux-hardware.org/?probe=2cc76d0cd9) | Jun 05, 2023 |
| ASUSTek       | CM1730,CM1830               | [7dc46d923e](https://linux-hardware.org/?probe=7dc46d923e) | Jun 05, 2023 |
| ASUSTek       | P5Q                         | [85c6e06d3b](https://linux-hardware.org/?probe=85c6e06d3b) | Jun 05, 2023 |
| Dell          | 00010C A00                  | [fb12198605](https://linux-hardware.org/?probe=fb12198605) | Jun 05, 2023 |
| Dell          | 00010C A00                  | [d94442285c](https://linux-hardware.org/?probe=d94442285c) | Jun 05, 2023 |
| ASUSTek       | B75M-A                      | [55139a968d](https://linux-hardware.org/?probe=55139a968d) | Jun 04, 2023 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [413aba0d3f](https://linux-hardware.org/?probe=413aba0d3f) | Jun 04, 2023 |
| Dell          | 0G9322                      | [a1c5ec8909](https://linux-hardware.org/?probe=a1c5ec8909) | Jun 03, 2023 |
| Dell          | 0NW6H5 A00                  | [01387c3030](https://linux-hardware.org/?probe=01387c3030) | Jun 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [20260fb3b3](https://linux-hardware.org/?probe=20260fb3b3) | Jun 03, 2023 |
| HP            | 339A                        | [bb4619f4eb](https://linux-hardware.org/?probe=bb4619f4eb) | Jun 02, 2023 |
| Gateway       | SX2851                      | [262ddffda9](https://linux-hardware.org/?probe=262ddffda9) | Jun 02, 2023 |
| MSI           | H81M-E34                    | [26362cac22](https://linux-hardware.org/?probe=26362cac22) | Jun 02, 2023 |
| MSI           | H81M-E34                    | [9f04387a7c](https://linux-hardware.org/?probe=9f04387a7c) | Jun 01, 2023 |
| ASRock        | ALiveDual-eSATA2            | [0f490d3b39](https://linux-hardware.org/?probe=0f490d3b39) | Jun 01, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [abc4bba144](https://linux-hardware.org/?probe=abc4bba144) | Jun 01, 2023 |
| MSI           | 890FXA-GD70                 | [bcc4cd9597](https://linux-hardware.org/?probe=bcc4cd9597) | Jun 01, 2023 |
| Gigabyte      | B450M DS3H-CF               | [923c9a18ff](https://linux-hardware.org/?probe=923c9a18ff) | Jun 01, 2023 |
| MSI           | B450 TOMAHAWK               | [0ddd2982db](https://linux-hardware.org/?probe=0ddd2982db) | May 31, 2023 |
| MSI           | B450 TOMAHAWK               | [93d1ee7e2d](https://linux-hardware.org/?probe=93d1ee7e2d) | May 31, 2023 |
| Acer          | Predator G3-605             | [f33c170be3](https://linux-hardware.org/?probe=f33c170be3) | May 27, 2023 |
| ASUSTek       | M2V-MX SE                   | [be58596103](https://linux-hardware.org/?probe=be58596103) | May 27, 2023 |
| ASUSTek       | M2V-MX SE                   | [0eedc4211a](https://linux-hardware.org/?probe=0eedc4211a) | May 27, 2023 |
| Dell          | 0G9322                      | [4d1450ba3a](https://linux-hardware.org/?probe=4d1450ba3a) | May 27, 2023 |
| Dell          | 0G9322                      | [d742ccb0c4](https://linux-hardware.org/?probe=d742ccb0c4) | May 27, 2023 |
| HP            | 21D0                        | [7f83859a91](https://linux-hardware.org/?probe=7f83859a91) | May 27, 2023 |
| MSI           | H97 GUARD-PRO               | [3737e6c832](https://linux-hardware.org/?probe=3737e6c832) | May 27, 2023 |
| HP            | 18E5                        | [23e2edb1fe](https://linux-hardware.org/?probe=23e2edb1fe) | May 26, 2023 |
| Dell          | 0K095G A02                  | [f11b8418c9](https://linux-hardware.org/?probe=f11b8418c9) | May 26, 2023 |
| HP            | 21D0                        | [8e52c2613c](https://linux-hardware.org/?probe=8e52c2613c) | May 26, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [61dc4c5620](https://linux-hardware.org/?probe=61dc4c5620) | May 25, 2023 |
| ECS           | H510H6-M2                   | [eba710b3de](https://linux-hardware.org/?probe=eba710b3de) | May 24, 2023 |
| Vorke         | V1 Plus                     | [81c0b82d6c](https://linux-hardware.org/?probe=81c0b82d6c) | May 24, 2023 |
| ECS           | H510H6-M2                   | [b36784601b](https://linux-hardware.org/?probe=b36784601b) | May 24, 2023 |
| HP            | 8906 SMVB                   | [ca3ed99a5c](https://linux-hardware.org/?probe=ca3ed99a5c) | May 24, 2023 |
| Pegatron      | 2AC2A                       | [f9e504a430](https://linux-hardware.org/?probe=f9e504a430) | May 24, 2023 |
| HP            | 21EF                        | [f1d5c9381c](https://linux-hardware.org/?probe=f1d5c9381c) | May 23, 2023 |
| MSI           | H81M-E34                    | [4247f30888](https://linux-hardware.org/?probe=4247f30888) | May 23, 2023 |
| Unknown       | Unknown                     | [977cf42905](https://linux-hardware.org/?probe=977cf42905) | May 23, 2023 |
| HP            | 21EF                        | [3249975d27](https://linux-hardware.org/?probe=3249975d27) | May 22, 2023 |
| ASRock        | H77M                        | [7f173e0b75](https://linux-hardware.org/?probe=7f173e0b75) | May 22, 2023 |
| HP            | 18E5                        | [d1bc34770d](https://linux-hardware.org/?probe=d1bc34770d) | May 22, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [b6465d2950](https://linux-hardware.org/?probe=b6465d2950) | May 21, 2023 |
| Dell          | 02N3WF A01                  | [8d0096c040](https://linux-hardware.org/?probe=8d0096c040) | May 21, 2023 |
| Dell          | 0M5DCD A00                  | [4087cdd6cb](https://linux-hardware.org/?probe=4087cdd6cb) | May 20, 2023 |
| Dell          | 0M5DCD A00                  | [8db744994d](https://linux-hardware.org/?probe=8db744994d) | May 20, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [0bcd2c7244](https://linux-hardware.org/?probe=0bcd2c7244) | May 20, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [c1594f6dab](https://linux-hardware.org/?probe=c1594f6dab) | May 20, 2023 |
| Gigabyte      | X570 GAMING X               | [8a6ad6c590](https://linux-hardware.org/?probe=8a6ad6c590) | May 19, 2023 |
| Dell          | 0GDG8Y A00                  | [514fe06c9e](https://linux-hardware.org/?probe=514fe06c9e) | May 19, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [31568d83f7](https://linux-hardware.org/?probe=31568d83f7) | May 18, 2023 |
| Gigabyte      | H81M-DS2                    | [754dc9d1fc](https://linux-hardware.org/?probe=754dc9d1fc) | May 18, 2023 |
| ASUSTek       | PRIME H410M-R               | [ee37475637](https://linux-hardware.org/?probe=ee37475637) | May 18, 2023 |
| ASUSTek       | PRIME H410M-R               | [68406e2c40](https://linux-hardware.org/?probe=68406e2c40) | May 18, 2023 |
| Acer          | Revo 70                     | [6cbc11e75b](https://linux-hardware.org/?probe=6cbc11e75b) | May 17, 2023 |
| HP            | 2B02                        | [a6bf09d51c](https://linux-hardware.org/?probe=a6bf09d51c) | May 17, 2023 |
| Pegatron      | Benicia                     | [e6ee1c66f6](https://linux-hardware.org/?probe=e6ee1c66f6) | May 17, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [d3c3cc9f96](https://linux-hardware.org/?probe=d3c3cc9f96) | May 15, 2023 |
| Intel         | Tiger Hill                  | [fdbe67045c](https://linux-hardware.org/?probe=fdbe67045c) | May 15, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [dd8c6c3811](https://linux-hardware.org/?probe=dd8c6c3811) | May 15, 2023 |
| HP            | 18E5                        | [7d5ceb9f5d](https://linux-hardware.org/?probe=7d5ceb9f5d) | May 15, 2023 |
| Gigabyte      | GA-970A-UD3                 | [24c81ddf59](https://linux-hardware.org/?probe=24c81ddf59) | May 14, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [38b6dd7b3f](https://linux-hardware.org/?probe=38b6dd7b3f) | May 14, 2023 |
| ASUSTek       | K8N-DRE                     | [395dc0cfb3](https://linux-hardware.org/?probe=395dc0cfb3) | May 13, 2023 |
| ASUSTek       | K8N-DRE                     | [f55a0c735f](https://linux-hardware.org/?probe=f55a0c735f) | May 13, 2023 |
| Vorke         | V1 Plus                     | [19f095fc02](https://linux-hardware.org/?probe=19f095fc02) | May 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [e844f3a6fe](https://linux-hardware.org/?probe=e844f3a6fe) | May 13, 2023 |
| Acer          | Predator G3-605             | [2d1485d58b](https://linux-hardware.org/?probe=2d1485d58b) | May 13, 2023 |
| Gigabyte      | A520M DS3H                  | [e053d0d304](https://linux-hardware.org/?probe=e053d0d304) | May 13, 2023 |
| Acer          | Predator G3-605             | [d3fc5ad399](https://linux-hardware.org/?probe=d3fc5ad399) | May 13, 2023 |
| Gigabyte      | GA-970A-UD3                 | [080f1c13d8](https://linux-hardware.org/?probe=080f1c13d8) | May 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [e2c57c80fc](https://linux-hardware.org/?probe=e2c57c80fc) | May 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | [d041d35517](https://linux-hardware.org/?probe=d041d35517) | May 12, 2023 |
| ASUSTek       | PRIME X370-PRO              | [d3ab5dcb5d](https://linux-hardware.org/?probe=d3ab5dcb5d) | May 12, 2023 |
| Gigabyte      | H110M-H-CF                  | [89b8dfaad7](https://linux-hardware.org/?probe=89b8dfaad7) | May 12, 2023 |
| Gigabyte      | Z77-DS3H                    | [c86f346e1d](https://linux-hardware.org/?probe=c86f346e1d) | May 12, 2023 |
| 16280-BM-3... | BADWARE-335861024712484 ... | [8f3baa5ed5](https://linux-hardware.org/?probe=8f3baa5ed5) | May 10, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [719d80a236](https://linux-hardware.org/?probe=719d80a236) | May 10, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [b25b524237](https://linux-hardware.org/?probe=b25b524237) | May 10, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [22778449cc](https://linux-hardware.org/?probe=22778449cc) | May 10, 2023 |
| ASUSTek       | A55BM-E                     | [4b1cb4d8cf](https://linux-hardware.org/?probe=4b1cb4d8cf) | May 10, 2023 |
| Gigabyte      | GA-78LMT-S2                 | [ffd84ff48e](https://linux-hardware.org/?probe=ffd84ff48e) | May 09, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [abf6d2bf1d](https://linux-hardware.org/?probe=abf6d2bf1d) | May 09, 2023 |
| ASRock        | H61M-DGS                    | [0b1518261e](https://linux-hardware.org/?probe=0b1518261e) | May 09, 2023 |
| ASUSTek       | H81I-PLUS                   | [93d7a459be](https://linux-hardware.org/?probe=93d7a459be) | May 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d45b33c736](https://linux-hardware.org/?probe=d45b33c736) | May 09, 2023 |
| ASRock        | H61M-DGS                    | [96cfd64792](https://linux-hardware.org/?probe=96cfd64792) | May 07, 2023 |
| HP            | 339A                        | [8b646a0fa1](https://linux-hardware.org/?probe=8b646a0fa1) | May 07, 2023 |
| HP            | 339A                        | [e23aaae239](https://linux-hardware.org/?probe=e23aaae239) | May 07, 2023 |
| Intel         | D946GZIS AAD66165-301       | [c350f5ed12](https://linux-hardware.org/?probe=c350f5ed12) | May 06, 2023 |
| ASUSTek       | P8Z68 DELUXE/GEN3           | [288e495c16](https://linux-hardware.org/?probe=288e495c16) | May 06, 2023 |
| ASRockRack    | D1521D4I2                   | [136a9303c0](https://linux-hardware.org/?probe=136a9303c0) | May 06, 2023 |
| MSI           | MAG B550M BAZOOKA           | [7b0b45831c](https://linux-hardware.org/?probe=7b0b45831c) | May 06, 2023 |
| MSI           | X570-A PRO                  | [46894747b1](https://linux-hardware.org/?probe=46894747b1) | May 05, 2023 |
| MSI           | X570-A PRO                  | [2723e21a6e](https://linux-hardware.org/?probe=2723e21a6e) | May 05, 2023 |
| Gigabyte      | M68MT-S2                    | [d571b75547](https://linux-hardware.org/?probe=d571b75547) | May 05, 2023 |
| ASRock        | B550M-HDV                   | [408cbd96c0](https://linux-hardware.org/?probe=408cbd96c0) | May 04, 2023 |
| Unknown       | Unknown                     | [5b46ed614a](https://linux-hardware.org/?probe=5b46ed614a) | May 04, 2023 |
| ASUSTek       | P5N73-CM                    | [e64a3c2da5](https://linux-hardware.org/?probe=e64a3c2da5) | May 04, 2023 |
| Gigabyte      | Z590 VISION G               | [d37eb8bf49](https://linux-hardware.org/?probe=d37eb8bf49) | May 04, 2023 |
| ASRock        | H81M-HDS                    | [60e11bdf11](https://linux-hardware.org/?probe=60e11bdf11) | May 04, 2023 |
| Gigabyte      | MFLP5IP-00                  | [c9c14a6da2](https://linux-hardware.org/?probe=c9c14a6da2) | May 03, 2023 |
| Gigabyte      | P55A-UD3                    | [c338210639](https://linux-hardware.org/?probe=c338210639) | May 03, 2023 |
| Dell          | 09WH54 A00                  | [0afa4006cd](https://linux-hardware.org/?probe=0afa4006cd) | May 03, 2023 |
| ASUSTek       | PRIME X370-PRO              | [d3757c615f](https://linux-hardware.org/?probe=d3757c615f) | May 02, 2023 |
| Intel         | D946GZIS AAD66165-301       | [e61e22863f](https://linux-hardware.org/?probe=e61e22863f) | May 02, 2023 |
| ASRock        | G41M-GS                     | [0824a9c571](https://linux-hardware.org/?probe=0824a9c571) | May 01, 2023 |
| Intel         | H55                         | [04dd5e834e](https://linux-hardware.org/?probe=04dd5e834e) | May 01, 2023 |
| ASRock        | H61M-DGS                    | [f395109c45](https://linux-hardware.org/?probe=f395109c45) | May 01, 2023 |
| Dell          | 02YYK5 A01                  | [1a00a1321e](https://linux-hardware.org/?probe=1a00a1321e) | Apr 30, 2023 |
| MSI           | IONA                        | [966ec83038](https://linux-hardware.org/?probe=966ec83038) | Apr 30, 2023 |
| Foxconn       | G41S/G41S-K                 | [946a95c594](https://linux-hardware.org/?probe=946a95c594) | Apr 30, 2023 |
| Foxconn       | G41S/G41S-K                 | [58cebf39d1](https://linux-hardware.org/?probe=58cebf39d1) | Apr 30, 2023 |
| Unknown       | Unknown                     | [4b0542737c](https://linux-hardware.org/?probe=4b0542737c) | Apr 29, 2023 |
| Dell          | 08NPPY A00                  | [25bc3aa225](https://linux-hardware.org/?probe=25bc3aa225) | Apr 29, 2023 |
| Unknown       | Unknown                     | [c4941a5c16](https://linux-hardware.org/?probe=c4941a5c16) | Apr 27, 2023 |
| Pegatron      | IPM41-D3                    | [faf8704eb3](https://linux-hardware.org/?probe=faf8704eb3) | Apr 26, 2023 |
| Intel         | D34010WYK H14771-304        | [4fbbe6e603](https://linux-hardware.org/?probe=4fbbe6e603) | Apr 26, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | [07e9099105](https://linux-hardware.org/?probe=07e9099105) | Apr 26, 2023 |
| HP            | 1632                        | [0355cb4e69](https://linux-hardware.org/?probe=0355cb4e69) | Apr 25, 2023 |
| ASUSTek       | M5A97 R2.0                  | [4231d023e9](https://linux-hardware.org/?probe=4231d023e9) | Apr 25, 2023 |
| eMachines     | MCP61PM-GM                  | [ff00693839](https://linux-hardware.org/?probe=ff00693839) | Apr 25, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [9bab79728a](https://linux-hardware.org/?probe=9bab79728a) | Apr 24, 2023 |
| ASUSTek       | P5Q                         | [57e3cfa7dc](https://linux-hardware.org/?probe=57e3cfa7dc) | Apr 24, 2023 |
| Intel         | D946GZIS AAD66165-301       | [9d5ada0fc4](https://linux-hardware.org/?probe=9d5ada0fc4) | Apr 24, 2023 |
| ASRock        | H61M-DGS                    | [154380c27c](https://linux-hardware.org/?probe=154380c27c) | Apr 24, 2023 |
| Gigabyte      | B650M DS3H                  | [3d07651a47](https://linux-hardware.org/?probe=3d07651a47) | Apr 24, 2023 |
| Dell          | 03NVJ6 A01                  | [8db1376917](https://linux-hardware.org/?probe=8db1376917) | Apr 23, 2023 |
| Pegatron      | 2AB5                        | [5f771d8ee5](https://linux-hardware.org/?probe=5f771d8ee5) | Apr 23, 2023 |
| Unknown       | G41                         | [cbe978cc34](https://linux-hardware.org/?probe=cbe978cc34) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [25ee911879](https://linux-hardware.org/?probe=25ee911879) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [468824c4d9](https://linux-hardware.org/?probe=468824c4d9) | Apr 23, 2023 |
| Gigabyte      | B760M GAMING X AX DDR4      | [a68d32d442](https://linux-hardware.org/?probe=a68d32d442) | Apr 23, 2023 |
| Gigabyte      | GA-MA74GM-S2H               | [0cd5599131](https://linux-hardware.org/?probe=0cd5599131) | Apr 22, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [3c3719b07f](https://linux-hardware.org/?probe=3c3719b07f) | Apr 22, 2023 |
| Dell          | 0F373D A00                  | [206de0188d](https://linux-hardware.org/?probe=206de0188d) | Apr 22, 2023 |
| Dell          | 03NVJ6 A01                  | [e60b9070a6](https://linux-hardware.org/?probe=e60b9070a6) | Apr 22, 2023 |
| ASUSTek       | M5A78L LE                   | [b19724085f](https://linux-hardware.org/?probe=b19724085f) | Apr 21, 2023 |
| Gigabyte      | B650M DS3H                  | [de196a2cfa](https://linux-hardware.org/?probe=de196a2cfa) | Apr 21, 2023 |
| ASUSTek       | H110M-R                     | [d428839f7c](https://linux-hardware.org/?probe=d428839f7c) | Apr 20, 2023 |
| HP            | 2ADE                        | [1a3d108a58](https://linux-hardware.org/?probe=1a3d108a58) | Apr 20, 2023 |
| HP            | 8054                        | [0f2c12c877](https://linux-hardware.org/?probe=0f2c12c877) | Apr 20, 2023 |
| Lenovo        | SHARKBAY 31900058 STD or... | [1331c6ef06](https://linux-hardware.org/?probe=1331c6ef06) | Apr 19, 2023 |
| HP            | 8906 SMVB                   | [65eb0fa6be](https://linux-hardware.org/?probe=65eb0fa6be) | Apr 19, 2023 |
| Dell          | 0WMJ54 A01                  | [2a7fe6d74b](https://linux-hardware.org/?probe=2a7fe6d74b) | Apr 18, 2023 |
| Dell          | 0WMJ54 A01                  | [be92b53515](https://linux-hardware.org/?probe=be92b53515) | Apr 18, 2023 |
| ASL           | BayTrail JHS773             | [3a5977ad04](https://linux-hardware.org/?probe=3a5977ad04) | Apr 18, 2023 |
| Dell          | 0T656F A02                  | [0d291f14a1](https://linux-hardware.org/?probe=0d291f14a1) | Apr 18, 2023 |
| ASUSTek       | PRIME X370-PRO              | [119560d8db](https://linux-hardware.org/?probe=119560d8db) | Apr 17, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [307e22b0d6](https://linux-hardware.org/?probe=307e22b0d6) | Apr 17, 2023 |
| MSI           | MEG X570 UNIFY              | [b2311e7cac](https://linux-hardware.org/?probe=b2311e7cac) | Apr 17, 2023 |
| ASUSTek       | PRIME Z370-A                | [b9d869fe6b](https://linux-hardware.org/?probe=b9d869fe6b) | Apr 16, 2023 |
| ASRock        | H61M-DGS                    | [506ba2605a](https://linux-hardware.org/?probe=506ba2605a) | Apr 15, 2023 |
| Gigabyte      | GA-MA74GM-S2H               | [c7568482a9](https://linux-hardware.org/?probe=c7568482a9) | Apr 15, 2023 |
| Intel         | H61                         | [81c7094e68](https://linux-hardware.org/?probe=81c7094e68) | Apr 15, 2023 |
| MSI           | B75MA-E33                   | [d50de3a52c](https://linux-hardware.org/?probe=d50de3a52c) | Apr 14, 2023 |
| QIYIDA        | X99-H9 V2.0                 | [fcfa1ed488](https://linux-hardware.org/?probe=fcfa1ed488) | Apr 14, 2023 |
| Biostar       | TZ75B                       | [c6720e2db2](https://linux-hardware.org/?probe=c6720e2db2) | Apr 14, 2023 |
| Foxconn       | G31MVP FAB:1.0              | [41eac5ca2f](https://linux-hardware.org/?probe=41eac5ca2f) | Apr 14, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [e9c2f8d5ba](https://linux-hardware.org/?probe=e9c2f8d5ba) | Apr 14, 2023 |
| Intel         | H61                         | [8aeeb449f8](https://linux-hardware.org/?probe=8aeeb449f8) | Apr 14, 2023 |
| ASRock        | B550 Steel Legend           | [9da868694f](https://linux-hardware.org/?probe=9da868694f) | Apr 14, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [4267100894](https://linux-hardware.org/?probe=4267100894) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [5e9f89e556](https://linux-hardware.org/?probe=5e9f89e556) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [d72e78c1b0](https://linux-hardware.org/?probe=d72e78c1b0) | Apr 13, 2023 |
| Gigabyte      | M68MT-S2                    | [ac4059b403](https://linux-hardware.org/?probe=ac4059b403) | Apr 13, 2023 |
| MSI           | B450M PRO-M2 MAX            | [6f7e9a6bb2](https://linux-hardware.org/?probe=6f7e9a6bb2) | Apr 13, 2023 |
| ASUSTek       | B85M-G                      | [27bfaf568a](https://linux-hardware.org/?probe=27bfaf568a) | Apr 12, 2023 |
| Gigabyte      | EX58-EXTREME                | [82a946e356](https://linux-hardware.org/?probe=82a946e356) | Apr 12, 2023 |
| ASUSTek       | P8H67-M PRO                 | [1627e0654a](https://linux-hardware.org/?probe=1627e0654a) | Apr 11, 2023 |
| ASUSTek       | P8H67-M PRO                 | [57aa7d103d](https://linux-hardware.org/?probe=57aa7d103d) | Apr 11, 2023 |
| ASUSTek       | P5K                         | [36bc294c5b](https://linux-hardware.org/?probe=36bc294c5b) | Apr 11, 2023 |
| MSI           | B75MA-E33                   | [27e5e2df0d](https://linux-hardware.org/?probe=27e5e2df0d) | Apr 06, 2023 |
| Dell          | 0GY6Y8 A01                  | [ecba971f16](https://linux-hardware.org/?probe=ecba971f16) | Apr 06, 2023 |
| ASUSTek       | H87-PRO                     | [085dc66a77](https://linux-hardware.org/?probe=085dc66a77) | Apr 05, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [68d14e873f](https://linux-hardware.org/?probe=68d14e873f) | Apr 05, 2023 |
| eMachines     | MCP61PM-GM                  | [dc35ec4564](https://linux-hardware.org/?probe=dc35ec4564) | Apr 04, 2023 |
| Gigabyte      | H410M S2 V3                 | [fdff0f112e](https://linux-hardware.org/?probe=fdff0f112e) | Apr 04, 2023 |
| Medion        | MS-7707                     | [c490d9dc74](https://linux-hardware.org/?probe=c490d9dc74) | Apr 04, 2023 |
| eMachines     | MCP61PM-GM                  | [59f9325843](https://linux-hardware.org/?probe=59f9325843) | Apr 03, 2023 |
| ASRock        | H61M-DGS                    | [e05fcde338](https://linux-hardware.org/?probe=e05fcde338) | Apr 03, 2023 |
| Acer          | Veriton X4610G              | [49b3c45306](https://linux-hardware.org/?probe=49b3c45306) | Apr 03, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [ea4626fdcc](https://linux-hardware.org/?probe=ea4626fdcc) | Apr 02, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [118effffda](https://linux-hardware.org/?probe=118effffda) | Apr 02, 2023 |
| Dell          | 0D883F A04                  | [5bdaaa0d23](https://linux-hardware.org/?probe=5bdaaa0d23) | Apr 02, 2023 |
| HOUTER        | IPMIP-GS                    | [4ef0c7aaaa](https://linux-hardware.org/?probe=4ef0c7aaaa) | Apr 02, 2023 |
| Pegatron      | 2ACF                        | [c015b7fd50](https://linux-hardware.org/?probe=c015b7fd50) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | [1fb4c6ac6a](https://linux-hardware.org/?probe=1fb4c6ac6a) | Apr 01, 2023 |
| Acer          | Predator G3-605             | [eb21663788](https://linux-hardware.org/?probe=eb21663788) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | [80bb5bbf28](https://linux-hardware.org/?probe=80bb5bbf28) | Apr 01, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [1fa4ec7b05](https://linux-hardware.org/?probe=1fa4ec7b05) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | [2e79b95cb4](https://linux-hardware.org/?probe=2e79b95cb4) | Apr 01, 2023 |
| Dell          | 0K240Y A02                  | [ca6aacf14e](https://linux-hardware.org/?probe=ca6aacf14e) | Mar 31, 2023 |
| Dell          | 09M8Y8 A01                  | [2c13e40cd2](https://linux-hardware.org/?probe=2c13e40cd2) | Mar 30, 2023 |
| ASUSTek       | Benicia                     | [7332efabad](https://linux-hardware.org/?probe=7332efabad) | Mar 30, 2023 |
| HOUTER        | ORO-PC                      | [9547c4bdac](https://linux-hardware.org/?probe=9547c4bdac) | Mar 29, 2023 |
| Gigabyte      | H310M H x.x                 | [a927671ce2](https://linux-hardware.org/?probe=a927671ce2) | Mar 29, 2023 |
| MSI           | B560M-A PRO                 | [62bfea11fe](https://linux-hardware.org/?probe=62bfea11fe) | Mar 28, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [c97dbb0917](https://linux-hardware.org/?probe=c97dbb0917) | Mar 28, 2023 |
| Dell          | 06X1TJ A01                  | [7e99e3d73e](https://linux-hardware.org/?probe=7e99e3d73e) | Mar 28, 2023 |
| ASRock        | Z68 Pro3-M                  | [60f0809fbf](https://linux-hardware.org/?probe=60f0809fbf) | Mar 28, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [dcbcf69a04](https://linux-hardware.org/?probe=dcbcf69a04) | Mar 27, 2023 |
| Dell          | 0J8H4R A00                  | [63d85fd315](https://linux-hardware.org/?probe=63d85fd315) | Mar 27, 2023 |
| Lenovo        | 11061GG ThinkServer TS13... | [174e514c30](https://linux-hardware.org/?probe=174e514c30) | Mar 26, 2023 |
| Packard Be... | MCP73PV                     | [87d1fd7511](https://linux-hardware.org/?probe=87d1fd7511) | Mar 26, 2023 |
| Dell          | 0GU083 A00                  | [e577b0129c](https://linux-hardware.org/?probe=e577b0129c) | Mar 26, 2023 |
| ASRock        | H61M-DGS                    | [76fc7291a6](https://linux-hardware.org/?probe=76fc7291a6) | Mar 26, 2023 |
| AZW           | MINI S                      | [f3381963ae](https://linux-hardware.org/?probe=f3381963ae) | Mar 25, 2023 |
| ASRock        | AB350 Gaming K4             | [ecc09c1362](https://linux-hardware.org/?probe=ecc09c1362) | Mar 25, 2023 |
| Dell          | 0D28YY A01                  | [38b08369e7](https://linux-hardware.org/?probe=38b08369e7) | Mar 25, 2023 |
| QIYIDA        | X99-H9 V2.0                 | [ce9cdcc598](https://linux-hardware.org/?probe=ce9cdcc598) | Mar 24, 2023 |
| Dell          | 0HD5W2 A01                  | [e859e77bc7](https://linux-hardware.org/?probe=e859e77bc7) | Mar 24, 2023 |
| Dell          | 0HD5W2 A01                  | [ce7e17cb45](https://linux-hardware.org/?probe=ce7e17cb45) | Mar 24, 2023 |
| ASRock        | X570 Steel Legend           | [05d4059f59](https://linux-hardware.org/?probe=05d4059f59) | Mar 24, 2023 |
| MSI           | B450M PRO-VDH MAX           | [c83000783a](https://linux-hardware.org/?probe=c83000783a) | Mar 23, 2023 |
| ASRock        | B550M-ITX/ac                | [e8ad290196](https://linux-hardware.org/?probe=e8ad290196) | Mar 23, 2023 |
| Intel         | G41                         | [c9fccfc8c1](https://linux-hardware.org/?probe=c9fccfc8c1) | Mar 22, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [d0b0015eb2](https://linux-hardware.org/?probe=d0b0015eb2) | Mar 22, 2023 |
| ASUSTek       | PRIME X370-PRO              | [9409e4e133](https://linux-hardware.org/?probe=9409e4e133) | Mar 20, 2023 |
| Acer          | Revo RL80                   | [23ee51b834](https://linux-hardware.org/?probe=23ee51b834) | Mar 20, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [93ae4afbbc](https://linux-hardware.org/?probe=93ae4afbbc) | Mar 20, 2023 |
| MSI           | B75MA-E33                   | [cddf0b016f](https://linux-hardware.org/?probe=cddf0b016f) | Mar 20, 2023 |
| ASUSTek       | PRIME X370-PRO              | [75996f8bcf](https://linux-hardware.org/?probe=75996f8bcf) | Mar 19, 2023 |
| HP            | 158A                        | [61467de4d5](https://linux-hardware.org/?probe=61467de4d5) | Mar 19, 2023 |
| ASRock        | H61M-DGS                    | [2b86166550](https://linux-hardware.org/?probe=2b86166550) | Mar 19, 2023 |
| ASUSTek       | PRIME A320M-K               | [f0f20a06ef](https://linux-hardware.org/?probe=f0f20a06ef) | Mar 19, 2023 |
| HP            | 2B01                        | [1a096f9b36](https://linux-hardware.org/?probe=1a096f9b36) | Mar 19, 2023 |
| MSI           | B75MA-E33                   | [314245636a](https://linux-hardware.org/?probe=314245636a) | Mar 18, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | [5f4a932bcd](https://linux-hardware.org/?probe=5f4a932bcd) | Mar 18, 2023 |
| HP            | 83E1                        | [2a1ade4f84](https://linux-hardware.org/?probe=2a1ade4f84) | Mar 17, 2023 |
| Dell          | 0D28YY A01                  | [76b31023a4](https://linux-hardware.org/?probe=76b31023a4) | Mar 17, 2023 |
| HP            | 158A                        | [4a023a55d8](https://linux-hardware.org/?probe=4a023a55d8) | Mar 16, 2023 |
| Lenovo        | SHARKBAY NOK                | [3388dd991a](https://linux-hardware.org/?probe=3388dd991a) | Mar 15, 2023 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | [eb761f4a30](https://linux-hardware.org/?probe=eb761f4a30) | Mar 14, 2023 |
| Gigabyte      | H110M-H-CF                  | [cc372ccf7d](https://linux-hardware.org/?probe=cc372ccf7d) | Mar 14, 2023 |
| QIYIDA        | X99-H9 V2.0                 | [0f440670f2](https://linux-hardware.org/?probe=0f440670f2) | Mar 14, 2023 |
| Gigabyte      | H55M-S2H                    | [55d6288663](https://linux-hardware.org/?probe=55d6288663) | Mar 14, 2023 |
| HP            | 83E1                        | [d286798430](https://linux-hardware.org/?probe=d286798430) | Mar 13, 2023 |
| Soncview      | G41D3C                      | [877ff67a70](https://linux-hardware.org/?probe=877ff67a70) | Mar 13, 2023 |
| Gigabyte      | H97M-D3H                    | [178af6e35b](https://linux-hardware.org/?probe=178af6e35b) | Mar 12, 2023 |
| HP            | 18E7                        | [2042edf904](https://linux-hardware.org/?probe=2042edf904) | Mar 12, 2023 |
| HP            | 09CCh                       | [e122b11e42](https://linux-hardware.org/?probe=e122b11e42) | Mar 12, 2023 |
| Dell          | 0GM819                      | [1db4004d05](https://linux-hardware.org/?probe=1db4004d05) | Mar 12, 2023 |
| Medion        | MS-7707                     | [a0621e0cd1](https://linux-hardware.org/?probe=a0621e0cd1) | Mar 12, 2023 |
| Gigabyte      | EX58-EXTREME                | [f45a0d4c01](https://linux-hardware.org/?probe=f45a0d4c01) | Mar 12, 2023 |
| Medion        | MS-7707                     | [4c9432026b](https://linux-hardware.org/?probe=4c9432026b) | Mar 12, 2023 |
| Gigabyte      | H110M-H-CF                  | [91da2169aa](https://linux-hardware.org/?probe=91da2169aa) | Mar 12, 2023 |
| Gigabyte      | X670E AORUS XTREME          | [83cb566647](https://linux-hardware.org/?probe=83cb566647) | Mar 12, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [bd0c265909](https://linux-hardware.org/?probe=bd0c265909) | Mar 11, 2023 |
| Intel         | H61                         | [5650f6d211](https://linux-hardware.org/?probe=5650f6d211) | Mar 11, 2023 |
| Acer          | WG43M                       | [5858448536](https://linux-hardware.org/?probe=5858448536) | Mar 11, 2023 |
| Acer          | WG43M                       | [3d562885d0](https://linux-hardware.org/?probe=3d562885d0) | Mar 11, 2023 |
| HP            | 09CCh                       | [9421be2c59](https://linux-hardware.org/?probe=9421be2c59) | Mar 11, 2023 |
| Dell          | 0T10XW A00                  | [a47baaadde](https://linux-hardware.org/?probe=a47baaadde) | Mar 11, 2023 |
| ASUSTek       | H110M-R                     | [434a8e0e37](https://linux-hardware.org/?probe=434a8e0e37) | Mar 10, 2023 |
| Pegatron      | 2ACB                        | [1599d2a2ef](https://linux-hardware.org/?probe=1599d2a2ef) | Mar 09, 2023 |
| Unknown       | HX90                        | [21530c00a4](https://linux-hardware.org/?probe=21530c00a4) | Mar 09, 2023 |
| Gigabyte      | Z370 HD3P-CF                | [8115c702cb](https://linux-hardware.org/?probe=8115c702cb) | Mar 09, 2023 |
| MSI           | B450 GAMING PLUS            | [5fd5c7db62](https://linux-hardware.org/?probe=5fd5c7db62) | Mar 09, 2023 |
| Dell          | 0T10XW A00                  | [fd255666fc](https://linux-hardware.org/?probe=fd255666fc) | Mar 08, 2023 |
| Gigabyte      | B450 GAMING X               | [6f7b473b62](https://linux-hardware.org/?probe=6f7b473b62) | Mar 08, 2023 |
| ASRock        | B450M Pro4-F                | [5f93500136](https://linux-hardware.org/?probe=5f93500136) | Mar 08, 2023 |
| ASRock        | B450M Pro4-F                | [fdba382132](https://linux-hardware.org/?probe=fdba382132) | Mar 08, 2023 |
| Gigabyte      | A320M-S2H-CF                | [00ddbf4ad1](https://linux-hardware.org/?probe=00ddbf4ad1) | Mar 07, 2023 |
| ASUSTek       | H97M-PLUS                   | [10c9c37ebc](https://linux-hardware.org/?probe=10c9c37ebc) | Mar 07, 2023 |
| ASUSTek       | P5GC-MX                     | [c7ccf3de7b](https://linux-hardware.org/?probe=c7ccf3de7b) | Mar 07, 2023 |
| ASUSTek       | H97M-PLUS                   | [aa987a6626](https://linux-hardware.org/?probe=aa987a6626) | Mar 07, 2023 |
| Gigabyte      | H61M-S2P-B3                 | [83c569f727](https://linux-hardware.org/?probe=83c569f727) | Mar 06, 2023 |
| Gigabyte      | H61M-S2P-B3                 | [ca3531a813](https://linux-hardware.org/?probe=ca3531a813) | Mar 06, 2023 |
| Dell          | 0JC474                      | [90db9efd8d](https://linux-hardware.org/?probe=90db9efd8d) | Mar 06, 2023 |
| ASUSTek       | SABERTOOTH Z87              | [7c9b56f288](https://linux-hardware.org/?probe=7c9b56f288) | Mar 05, 2023 |
| Gigabyte      | B450M DS3H V2               | [d1a55c59a3](https://linux-hardware.org/?probe=d1a55c59a3) | Mar 05, 2023 |
| Apple         | Mac-F221BEC8                | [f3c06b377f](https://linux-hardware.org/?probe=f3c06b377f) | Mar 04, 2023 |
| ASUSTek       | H81M-K                      | [05507dab01](https://linux-hardware.org/?probe=05507dab01) | Mar 04, 2023 |
| ASUSTek       | PRIME H410M-R               | [240adbe154](https://linux-hardware.org/?probe=240adbe154) | Mar 04, 2023 |
| Gigabyte      | B460M AORUS PRO             | [829848b662](https://linux-hardware.org/?probe=829848b662) | Mar 04, 2023 |
| ASRock        | Wolfdale1333-D667           | [7dd4939e64](https://linux-hardware.org/?probe=7dd4939e64) | Mar 03, 2023 |
| Unknown       | Rev.00                      | [89ff2d84f4](https://linux-hardware.org/?probe=89ff2d84f4) | Mar 03, 2023 |
| ASUSTek       | P7H55-M LX                  | [80e66c5eac](https://linux-hardware.org/?probe=80e66c5eac) | Mar 03, 2023 |
| ASUSTek       | P5QPL-AM                    | [52b68672fc](https://linux-hardware.org/?probe=52b68672fc) | Mar 03, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [1e039a31d1](https://linux-hardware.org/?probe=1e039a31d1) | Mar 03, 2023 |
| HP            | 805D                        | [4638c85566](https://linux-hardware.org/?probe=4638c85566) | Mar 01, 2023 |
| ASUSTek       | SABERTOOTH P67              | [fa7df5da3b](https://linux-hardware.org/?probe=fa7df5da3b) | Mar 01, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [ca7d449be6](https://linux-hardware.org/?probe=ca7d449be6) | Feb 28, 2023 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | [75e0fb99ed](https://linux-hardware.org/?probe=75e0fb99ed) | Feb 28, 2023 |
| Google        | Buddy                       | [ac3d9aaed0](https://linux-hardware.org/?probe=ac3d9aaed0) | Feb 27, 2023 |
| Dell          | 0WMJ54 A01                  | [7f907fadb7](https://linux-hardware.org/?probe=7f907fadb7) | Feb 27, 2023 |
| Dell          | 0WMJ54 A01                  | [766991da5e](https://linux-hardware.org/?probe=766991da5e) | Feb 27, 2023 |
| Dell          | 0Y2MRG A00                  | [6c62bbbf3b](https://linux-hardware.org/?probe=6c62bbbf3b) | Feb 27, 2023 |
| Dell          | 0Y2MRG A00                  | [2479c3c245](https://linux-hardware.org/?probe=2479c3c245) | Feb 27, 2023 |
| HP            | 1998                        | [90794415e9](https://linux-hardware.org/?probe=90794415e9) | Feb 26, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [a21ea9613b](https://linux-hardware.org/?probe=a21ea9613b) | Feb 26, 2023 |
| MSI           | B75MA-E33                   | [57a009cdd4](https://linux-hardware.org/?probe=57a009cdd4) | Feb 25, 2023 |
| MSI           | B75MA-E33                   | [fc1a3d88ae](https://linux-hardware.org/?probe=fc1a3d88ae) | Feb 25, 2023 |
| MSI           | H81M-P33                    | [1bc1cedec6](https://linux-hardware.org/?probe=1bc1cedec6) | Feb 25, 2023 |
| ASUSTek       | PRIME B560M-A               | [7357439273](https://linux-hardware.org/?probe=7357439273) | Feb 25, 2023 |
| HP            | 2AF7                        | [a8eba0b0c4](https://linux-hardware.org/?probe=a8eba0b0c4) | Feb 25, 2023 |
| HP            | 2AF7                        | [3bf3afd1d5](https://linux-hardware.org/?probe=3bf3afd1d5) | Feb 25, 2023 |
| HP            | 2129                        | [5118eb06d4](https://linux-hardware.org/?probe=5118eb06d4) | Feb 24, 2023 |
| Dell          | 0HN7XN A01                  | [f283ae7cb2](https://linux-hardware.org/?probe=f283ae7cb2) | Feb 23, 2023 |
| ASUSTek       | P7H55-M/USB3                | [472721d72c](https://linux-hardware.org/?probe=472721d72c) | Feb 22, 2023 |
| HP            | 2129                        | [5a6b1e7169](https://linux-hardware.org/?probe=5a6b1e7169) | Feb 21, 2023 |
| ASUSTek       | SABERTOOTH Z87              | [e861797e74](https://linux-hardware.org/?probe=e861797e74) | Feb 21, 2023 |
| ASUSTek       | F2A55-M                     | [c9d150f24c](https://linux-hardware.org/?probe=c9d150f24c) | Feb 21, 2023 |
| ASUSTek       | SABERTOOTH Z87              | [40e2157901](https://linux-hardware.org/?probe=40e2157901) | Feb 21, 2023 |
| HP            | 1850                        | [f184ff6250](https://linux-hardware.org/?probe=f184ff6250) | Feb 21, 2023 |
| ASUSTek       | BM6630_BM6330_BP6230        | [e062475561](https://linux-hardware.org/?probe=e062475561) | Feb 20, 2023 |
| eMachines     | MCP61PM-GM                  | [aeafa2dbee](https://linux-hardware.org/?probe=aeafa2dbee) | Feb 19, 2023 |
| ASUSTek       | BM6630_BM6330_BP6230        | [5d6240bcc6](https://linux-hardware.org/?probe=5d6240bcc6) | Feb 19, 2023 |
| HOUTER        | ORO-PC                      | [09aad96389](https://linux-hardware.org/?probe=09aad96389) | Feb 19, 2023 |
| Gigabyte      | H97M-D3H                    | [be0f73193d](https://linux-hardware.org/?probe=be0f73193d) | Feb 19, 2023 |
| Gigabyte      | H97M-D3H                    | [c784a261d4](https://linux-hardware.org/?probe=c784a261d4) | Feb 19, 2023 |
| Gigabyte      | H81M-S2H                    | [d6f4d9d8df](https://linux-hardware.org/?probe=d6f4d9d8df) | Feb 19, 2023 |
| HOUTER        | ORO-PC                      | [af7ffdc7a9](https://linux-hardware.org/?probe=af7ffdc7a9) | Feb 18, 2023 |
| ASUSTek       | P5KC                        | [b2a9f21210](https://linux-hardware.org/?probe=b2a9f21210) | Feb 18, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [6cc82a744e](https://linux-hardware.org/?probe=6cc82a744e) | Feb 18, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [96c9f07207](https://linux-hardware.org/?probe=96c9f07207) | Feb 18, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [2734c1a2ae](https://linux-hardware.org/?probe=2734c1a2ae) | Feb 18, 2023 |
| MSI           | H270 PC MATE                | [6581748d54](https://linux-hardware.org/?probe=6581748d54) | Feb 17, 2023 |
| MSI           | 760GM-P23                   | [529e0929d2](https://linux-hardware.org/?probe=529e0929d2) | Feb 17, 2023 |
| Gigabyte      | 990FXA-UD3                  | [97e017594b](https://linux-hardware.org/?probe=97e017594b) | Feb 16, 2023 |
| Gigabyte      | 990FXA-UD3                  | [51b7c93a69](https://linux-hardware.org/?probe=51b7c93a69) | Feb 16, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [4275665066](https://linux-hardware.org/?probe=4275665066) | Feb 16, 2023 |
| MSI           | Z370M MORTAR                | [5ac9c9a924](https://linux-hardware.org/?probe=5ac9c9a924) | Feb 15, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [995da369f0](https://linux-hardware.org/?probe=995da369f0) | Feb 14, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | [b6b09f6455](https://linux-hardware.org/?probe=b6b09f6455) | Feb 14, 2023 |
| Gigabyte      | 945GZM-S2                   | [e271dc0c66](https://linux-hardware.org/?probe=e271dc0c66) | Feb 14, 2023 |
| Gigabyte      | B450M DS3H V2               | [92fc220243](https://linux-hardware.org/?probe=92fc220243) | Feb 14, 2023 |
| Google        | Teemo                       | [53bf6d19ca](https://linux-hardware.org/?probe=53bf6d19ca) | Feb 14, 2023 |
| MSI           | MS-B9181                    | [a155bc9fc3](https://linux-hardware.org/?probe=a155bc9fc3) | Feb 13, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [1e3c885566](https://linux-hardware.org/?probe=1e3c885566) | Feb 13, 2023 |
| Dell          | 0Y7WYT A00                  | [e289b5bb8d](https://linux-hardware.org/?probe=e289b5bb8d) | Feb 13, 2023 |
| ASRock        | X570 Phantom Gaming X       | [5efd07985b](https://linux-hardware.org/?probe=5efd07985b) | Feb 13, 2023 |
| Alienware     | 0N43JM A00                  | [ef1d9239ab](https://linux-hardware.org/?probe=ef1d9239ab) | Feb 12, 2023 |
| Lenovo        | ThinkServer TS140           | [59eeaafe59](https://linux-hardware.org/?probe=59eeaafe59) | Feb 12, 2023 |
| MSI           | H310M PRO-M2 PLUS           | [45f78c29cb](https://linux-hardware.org/?probe=45f78c29cb) | Feb 12, 2023 |
| Gigabyte      | B560 HD3                    | [498c449a46](https://linux-hardware.org/?probe=498c449a46) | Feb 12, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [43e0c40499](https://linux-hardware.org/?probe=43e0c40499) | Feb 11, 2023 |
| Unknown       | Unknown                     | [ce78e6cdb9](https://linux-hardware.org/?probe=ce78e6cdb9) | Feb 11, 2023 |
| Gigabyte      | H81M-S2H                    | [a789235fe3](https://linux-hardware.org/?probe=a789235fe3) | Feb 11, 2023 |
| HP            | 8054                        | [55c5642509](https://linux-hardware.org/?probe=55c5642509) | Feb 11, 2023 |
| Gigabyte      | H81M-S2H                    | [f3919f8d69](https://linux-hardware.org/?probe=f3919f8d69) | Feb 11, 2023 |
| IBM           | 819046G                     | [a43370bbbd](https://linux-hardware.org/?probe=a43370bbbd) | Feb 11, 2023 |
| Unknown       | Unknown                     | [f5e5e27e8e](https://linux-hardware.org/?probe=f5e5e27e8e) | Feb 11, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [7a6b34f58c](https://linux-hardware.org/?probe=7a6b34f58c) | Feb 11, 2023 |
| HP            | 8643 SMVB                   | [5e8a88b237](https://linux-hardware.org/?probe=5e8a88b237) | Feb 11, 2023 |
| ASUSTek       | P5K                         | [9f8790812d](https://linux-hardware.org/?probe=9f8790812d) | Feb 11, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [6d9d60d4b8](https://linux-hardware.org/?probe=6d9d60d4b8) | Feb 10, 2023 |
| Unknown       | Unknown                     | [cb0a834e1a](https://linux-hardware.org/?probe=cb0a834e1a) | Feb 10, 2023 |
| MSI           | GF615M-P31                  | [36dcd2e516](https://linux-hardware.org/?probe=36dcd2e516) | Feb 10, 2023 |
| Gigabyte      | X570 GAMING X               | [458744c54d](https://linux-hardware.org/?probe=458744c54d) | Feb 09, 2023 |
| Gigabyte      | B560 HD3                    | [628151aedd](https://linux-hardware.org/?probe=628151aedd) | Feb 09, 2023 |
| Gigabyte      | X570 GAMING X               | [dd9b71e8d2](https://linux-hardware.org/?probe=dd9b71e8d2) | Feb 09, 2023 |
| Gigabyte      | B660 DS3H AX DDR4           | [73ae27760d](https://linux-hardware.org/?probe=73ae27760d) | Feb 09, 2023 |
| ASUSTek       | PRIME B550M-A               | [dd76c764a1](https://linux-hardware.org/?probe=dd76c764a1) | Feb 08, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [37aec8a881](https://linux-hardware.org/?probe=37aec8a881) | Feb 08, 2023 |
| Gigabyte      | GA-MA74GM-S2H               | [e7ee51ecdd](https://linux-hardware.org/?probe=e7ee51ecdd) | Feb 08, 2023 |
| ASUSTek       | SABERTOOTH P67              | [1fdf18a3ed](https://linux-hardware.org/?probe=1fdf18a3ed) | Feb 08, 2023 |
| Foxconn       | NT-A2400&NT-A3500 FAB       | [000ed6c589](https://linux-hardware.org/?probe=000ed6c589) | Feb 07, 2023 |
| Intel         | CRESCENTBAY                 | [1830edf54c](https://linux-hardware.org/?probe=1830edf54c) | Feb 07, 2023 |
| Lenovo        | Myrtle CRB SDK0J40700 WI... | [96f24866e0](https://linux-hardware.org/?probe=96f24866e0) | Feb 06, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [05b252ac05](https://linux-hardware.org/?probe=05b252ac05) | Feb 05, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [0de7e3b318](https://linux-hardware.org/?probe=0de7e3b318) | Feb 05, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [e61bc21eaf](https://linux-hardware.org/?probe=e61bc21eaf) | Feb 05, 2023 |
| HP            | 2B47                        | [3db96ac186](https://linux-hardware.org/?probe=3db96ac186) | Feb 04, 2023 |
| Dell          | 0HN7XN A01                  | [0399613500](https://linux-hardware.org/?probe=0399613500) | Feb 04, 2023 |
| ASUSTek       | M5A97 R2.0                  | [e5a1cf7284](https://linux-hardware.org/?probe=e5a1cf7284) | Feb 03, 2023 |
| MSI           | B85M-E45                    | [13453f924e](https://linux-hardware.org/?probe=13453f924e) | Feb 03, 2023 |
| Intel         | X58                         | [55a6a5bd82](https://linux-hardware.org/?probe=55a6a5bd82) | Feb 03, 2023 |
| Unknown       | G41 Series                  | [69d4cb64a2](https://linux-hardware.org/?probe=69d4cb64a2) | Feb 03, 2023 |
| HP            | 1825                        | [fd942fd3ba](https://linux-hardware.org/?probe=fd942fd3ba) | Feb 02, 2023 |
| HP            | 09F8h                       | [19339c9512](https://linux-hardware.org/?probe=19339c9512) | Feb 02, 2023 |
| Dell          | 0D28YY A01                  | [51b04e5d58](https://linux-hardware.org/?probe=51b04e5d58) | Feb 01, 2023 |
| ASRock        | H87 Pro4                    | [8a53501060](https://linux-hardware.org/?probe=8a53501060) | Jan 31, 2023 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [2c021665e1](https://linux-hardware.org/?probe=2c021665e1) | Jan 31, 2023 |
| MSI           | H81M-P33                    | [63402c414d](https://linux-hardware.org/?probe=63402c414d) | Jan 30, 2023 |
| HP            | 1791                        | [0cb5402c68](https://linux-hardware.org/?probe=0cb5402c68) | Jan 29, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [bc4b6513bb](https://linux-hardware.org/?probe=bc4b6513bb) | Jan 28, 2023 |
| MSI           | 760GM-P23                   | [0da956ecde](https://linux-hardware.org/?probe=0da956ecde) | Jan 28, 2023 |
| MSI           | 760GM-P23                   | [e00bd18cc2](https://linux-hardware.org/?probe=e00bd18cc2) | Jan 28, 2023 |
| HP            | 843F                        | [5e9a5d2afd](https://linux-hardware.org/?probe=5e9a5d2afd) | Jan 28, 2023 |
| MSI           | PRO H610M-G DDR4            | [ad4f37d5a4](https://linux-hardware.org/?probe=ad4f37d5a4) | Jan 28, 2023 |
| HP            | 2B47                        | [cce5f9ec07](https://linux-hardware.org/?probe=cce5f9ec07) | Jan 27, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [e7b74c9ad4](https://linux-hardware.org/?probe=e7b74c9ad4) | Jan 27, 2023 |
| ASRock        | H61M-DGS                    | [825e70e660](https://linux-hardware.org/?probe=825e70e660) | Jan 27, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [9d3e931cc1](https://linux-hardware.org/?probe=9d3e931cc1) | Jan 27, 2023 |
| ASRock        | H87 Pro4                    | [c1427c9b7b](https://linux-hardware.org/?probe=c1427c9b7b) | Jan 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [951bfcd626](https://linux-hardware.org/?probe=951bfcd626) | Jan 26, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [c216d513a0](https://linux-hardware.org/?probe=c216d513a0) | Jan 25, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [06b972165b](https://linux-hardware.org/?probe=06b972165b) | Jan 25, 2023 |
| ASRock        | H61M-DGS                    | [5672937ec6](https://linux-hardware.org/?probe=5672937ec6) | Jan 25, 2023 |
| HP            | 2ADE                        | [b927cb3f98](https://linux-hardware.org/?probe=b927cb3f98) | Jan 24, 2023 |
| Acer          | RS880M05                    | [c7e3fe60e1](https://linux-hardware.org/?probe=c7e3fe60e1) | Jan 23, 2023 |
| ASRock        | H61M                        | [f5b1db73f7](https://linux-hardware.org/?probe=f5b1db73f7) | Jan 22, 2023 |
| ASUSTek       | P5Q                         | [9e3b6b7075](https://linux-hardware.org/?probe=9e3b6b7075) | Jan 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [90ad82dcac](https://linux-hardware.org/?probe=90ad82dcac) | Jan 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [9579ec96bc](https://linux-hardware.org/?probe=9579ec96bc) | Jan 21, 2023 |
| HP            | 89B5 A                      | [1b6e288840](https://linux-hardware.org/?probe=1b6e288840) | Jan 21, 2023 |
| HP            | 843F                        | [07f6efa703](https://linux-hardware.org/?probe=07f6efa703) | Jan 20, 2023 |
| ASUSTek       | M4A3000E                    | [650236c7cc](https://linux-hardware.org/?probe=650236c7cc) | Jan 19, 2023 |
| ASRock        | B450 Pro4                   | [8131194ea1](https://linux-hardware.org/?probe=8131194ea1) | Jan 19, 2023 |
| ASUSTek       | P7P55D-E                    | [6bc203c6fd](https://linux-hardware.org/?probe=6bc203c6fd) | Jan 19, 2023 |
| HP            | 843F                        | [83ca70ac2d](https://linux-hardware.org/?probe=83ca70ac2d) | Jan 19, 2023 |
| Dell          | 0D28YY A01                  | [82b540a137](https://linux-hardware.org/?probe=82b540a137) | Jan 19, 2023 |
| ASUSTek       | M4A3000E                    | [4f8a71f0c5](https://linux-hardware.org/?probe=4f8a71f0c5) | Jan 19, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [dfac4d4f79](https://linux-hardware.org/?probe=dfac4d4f79) | Jan 17, 2023 |
| HP            | 3397                        | [a58c9ac196](https://linux-hardware.org/?probe=a58c9ac196) | Jan 17, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [69b469a6fb](https://linux-hardware.org/?probe=69b469a6fb) | Jan 16, 2023 |
| Gigabyte      | EX58-EXTREME                | [bb62149054](https://linux-hardware.org/?probe=bb62149054) | Jan 16, 2023 |
| Medion        | MS-7707                     | [9665ceabf1](https://linux-hardware.org/?probe=9665ceabf1) | Jan 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [3677d8f4e7](https://linux-hardware.org/?probe=3677d8f4e7) | Jan 15, 2023 |
| Gigabyte      | M68MT-S2                    | [a728c46633](https://linux-hardware.org/?probe=a728c46633) | Jan 15, 2023 |
| Unknown       | Unknown                     | [a69d4b7b4f](https://linux-hardware.org/?probe=a69d4b7b4f) | Jan 15, 2023 |
| Alienware     | 2                           | [97c74c0c7b](https://linux-hardware.org/?probe=97c74c0c7b) | Jan 15, 2023 |
| Dell          | 0F0TGN A00                  | [38a44bb08b](https://linux-hardware.org/?probe=38a44bb08b) | Jan 14, 2023 |
| HP            | 18E7                        | [3acf05bf4e](https://linux-hardware.org/?probe=3acf05bf4e) | Jan 14, 2023 |
| Unknown       | Unknown                     | [9cb802849a](https://linux-hardware.org/?probe=9cb802849a) | Jan 14, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | [e00028a10c](https://linux-hardware.org/?probe=e00028a10c) | Jan 14, 2023 |
| HC            | HCAR357-MI V1.0             | [b5f80f8eac](https://linux-hardware.org/?probe=b5f80f8eac) | Jan 14, 2023 |
| HP            | 0B4Ch D                     | [c5edc9fbc7](https://linux-hardware.org/?probe=c5edc9fbc7) | Jan 14, 2023 |
| Dell          | 0F0TGN A00                  | [dc548d070e](https://linux-hardware.org/?probe=dc548d070e) | Jan 13, 2023 |
| HP            | 3397                        | [baae324548](https://linux-hardware.org/?probe=baae324548) | Jan 13, 2023 |
| Acer          | FRS690L                     | [5b27fe10aa](https://linux-hardware.org/?probe=5b27fe10aa) | Jan 13, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [07cedbf55a](https://linux-hardware.org/?probe=07cedbf55a) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [1706cf55cf](https://linux-hardware.org/?probe=1706cf55cf) | Jan 12, 2023 |
| ASUSTek       | H87-PRO                     | [4ac36f25a9](https://linux-hardware.org/?probe=4ac36f25a9) | Jan 11, 2023 |
| HP            | 843B                        | [ac14cee88f](https://linux-hardware.org/?probe=ac14cee88f) | Jan 10, 2023 |
| HP            | 843B                        | [e45a20a47f](https://linux-hardware.org/?probe=e45a20a47f) | Jan 10, 2023 |
| ASUSTek       | M4A88T-M                    | [4c3d063774](https://linux-hardware.org/?probe=4c3d063774) | Jan 09, 2023 |
| ASUSTek       | Z170 PRO GAMING/AURA        | [abc1a27105](https://linux-hardware.org/?probe=abc1a27105) | Jan 08, 2023 |
| HP            | 2129                        | [4d6113e60d](https://linux-hardware.org/?probe=4d6113e60d) | Jan 08, 2023 |
| ASRock        | X670E PG Lightning          | [2b3261504f](https://linux-hardware.org/?probe=2b3261504f) | Jan 08, 2023 |
| MAXSUN        | MS-TZZ A320M.2-VH           | [f3e00dc862](https://linux-hardware.org/?probe=f3e00dc862) | Jan 07, 2023 |
| Standard      | X50-V2                      | [69b7593670](https://linux-hardware.org/?probe=69b7593670) | Jan 07, 2023 |
| HP            | 2B47                        | [8ad8cb5e8f](https://linux-hardware.org/?probe=8ad8cb5e8f) | Jan 06, 2023 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [2df76bde47](https://linux-hardware.org/?probe=2df76bde47) | Jan 06, 2023 |
| Dell          | 0HN7XN A01                  | [e597f176c2](https://linux-hardware.org/?probe=e597f176c2) | Jan 03, 2023 |
| Dell          | 018D1Y A00                  | [9ba9bcee90](https://linux-hardware.org/?probe=9ba9bcee90) | Jan 03, 2023 |
| Foxconn       | H67S/H61SP                  | [c7684d1f93](https://linux-hardware.org/?probe=c7684d1f93) | Jan 03, 2023 |
| HP            | 8350                        | [3ab0d55a41](https://linux-hardware.org/?probe=3ab0d55a41) | Jan 02, 2023 |
| ASUSTek       | D300TA                      | [f522fa7b4d](https://linux-hardware.org/?probe=f522fa7b4d) | Jan 02, 2023 |
| ASUSTek       | H87-PRO                     | [f95906c714](https://linux-hardware.org/?probe=f95906c714) | Jan 01, 2023 |
| Dell          | 0T10XW A00                  | [21638e1dfe](https://linux-hardware.org/?probe=21638e1dfe) | Dec 31, 2022 |
| Gigabyte      | G31M-S2C                    | [39f08657f8](https://linux-hardware.org/?probe=39f08657f8) | Dec 31, 2022 |
| Gigabyte      | B550 AORUS PRO              | [c8da48f03c](https://linux-hardware.org/?probe=c8da48f03c) | Dec 30, 2022 |
| HOUTER        | IPMIP-GS                    | [6fddf7d035](https://linux-hardware.org/?probe=6fddf7d035) | Dec 30, 2022 |
| Biostar       | TA970                       | [6a55825894](https://linux-hardware.org/?probe=6a55825894) | Dec 30, 2022 |
| Gigabyte      | 970A-DS3P                   | [c841093094](https://linux-hardware.org/?probe=c841093094) | Dec 30, 2022 |
| MSI           | X99A RAIDER                 | [59f6170d5b](https://linux-hardware.org/?probe=59f6170d5b) | Dec 29, 2022 |
| MSI           | Z490-A PRO                  | [e4e5afd812](https://linux-hardware.org/?probe=e4e5afd812) | Dec 29, 2022 |
| ASUSTek       | P6T DELUXE V2               | [0d8d6061d7](https://linux-hardware.org/?probe=0d8d6061d7) | Dec 29, 2022 |
| ASUSTek       | P6T DELUXE V2               | [4bda137e99](https://linux-hardware.org/?probe=4bda137e99) | Dec 29, 2022 |
| Dell          | 0KWVT8 A03                  | [7ce6d4b3e3](https://linux-hardware.org/?probe=7ce6d4b3e3) | Dec 29, 2022 |
| Dell          | 0KWVT8 A03                  | [f828f74e07](https://linux-hardware.org/?probe=f828f74e07) | Dec 29, 2022 |
| PCWare        | IPMH61R1                    | [a221946f02](https://linux-hardware.org/?probe=a221946f02) | Dec 29, 2022 |
| Dell          | 03KWTV A02                  | [82612358ac](https://linux-hardware.org/?probe=82612358ac) | Dec 28, 2022 |
| HP            | 2AF7                        | [9663a281c1](https://linux-hardware.org/?probe=9663a281c1) | Dec 28, 2022 |
| Acer          | Aspire XC-780               | [0d90d1884c](https://linux-hardware.org/?probe=0d90d1884c) | Dec 27, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [5ce1ea886f](https://linux-hardware.org/?probe=5ce1ea886f) | Dec 26, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [f56ea263a2](https://linux-hardware.org/?probe=f56ea263a2) | Dec 26, 2022 |
| HP            | 2AF7                        | [287696b4fc](https://linux-hardware.org/?probe=287696b4fc) | Dec 25, 2022 |
| Gigabyte      | GA-770T-USB3                | [08d1b04754](https://linux-hardware.org/?probe=08d1b04754) | Dec 25, 2022 |
| ASRock        | 970 Extreme4                | [2655b3c6b6](https://linux-hardware.org/?probe=2655b3c6b6) | Dec 24, 2022 |
| Intel         | H61                         | [8d5eb236e1](https://linux-hardware.org/?probe=8d5eb236e1) | Dec 24, 2022 |
| HP            | 2AF7                        | [7b79dd8352](https://linux-hardware.org/?probe=7b79dd8352) | Dec 23, 2022 |
| HP            | 2AF7                        | [5ef9ce3357](https://linux-hardware.org/?probe=5ef9ce3357) | Dec 23, 2022 |
| Dell          | 0C2KJT A00                  | [08a8cc75ac](https://linux-hardware.org/?probe=08a8cc75ac) | Dec 23, 2022 |
| Dell          | 0C2KJT A00                  | [bd8a5003e8](https://linux-hardware.org/?probe=bd8a5003e8) | Dec 23, 2022 |
| ASRock        | G31M-S                      | [476c5ec563](https://linux-hardware.org/?probe=476c5ec563) | Dec 22, 2022 |
| MSI           | H61MU-E35                   | [cb9ec3d5ad](https://linux-hardware.org/?probe=cb9ec3d5ad) | Dec 22, 2022 |
| MSI           | H61MU-E35                   | [bfdc9d1e12](https://linux-hardware.org/?probe=bfdc9d1e12) | Dec 22, 2022 |
| ECS           | H110M4-C2H                  | [f349ed8914](https://linux-hardware.org/?probe=f349ed8914) | Dec 22, 2022 |
| MSI           | B450M MORTAR                | [2279954594](https://linux-hardware.org/?probe=2279954594) | Dec 22, 2022 |
| ASRock        | N68C-S UCC                  | [279e1eacf6](https://linux-hardware.org/?probe=279e1eacf6) | Dec 22, 2022 |
| ASRock        | G31M-S                      | [88d93da5a7](https://linux-hardware.org/?probe=88d93da5a7) | Dec 22, 2022 |
| ASRock        | N68C-S UCC                  | [8d8716cdca](https://linux-hardware.org/?probe=8d8716cdca) | Dec 21, 2022 |
| PCWare        | IPMH310 PRO 1.0             | [c4dea5edbb](https://linux-hardware.org/?probe=c4dea5edbb) | Dec 21, 2022 |
| HP            | 09CCh                       | [60d8cc87c7](https://linux-hardware.org/?probe=60d8cc87c7) | Dec 20, 2022 |
| Dell          | 0MGK50 A04                  | [931b01be38](https://linux-hardware.org/?probe=931b01be38) | Dec 20, 2022 |
| ASRock        | Z170 Pro4                   | [ca027f264a](https://linux-hardware.org/?probe=ca027f264a) | Dec 20, 2022 |
| ASRock        | B450M Pro4                  | [83df1364c8](https://linux-hardware.org/?probe=83df1364c8) | Dec 20, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [87907abff7](https://linux-hardware.org/?probe=87907abff7) | Dec 19, 2022 |
| ASUSTek       | PRIME H310M-A R2.0          | [08f3a88ab3](https://linux-hardware.org/?probe=08f3a88ab3) | Dec 19, 2022 |
| Lenovo        | ThinkCentre M91p 4524WAP    | [0d5c4254b7](https://linux-hardware.org/?probe=0d5c4254b7) | Dec 19, 2022 |
| ASRock        | N3150-NUC                   | [5e77ec1117](https://linux-hardware.org/?probe=5e77ec1117) | Dec 18, 2022 |
| Dell          | 0Y2MRG A00                  | [20b69069fa](https://linux-hardware.org/?probe=20b69069fa) | Dec 18, 2022 |
| ASRock        | N3150-NUC                   | [e497bf2ce3](https://linux-hardware.org/?probe=e497bf2ce3) | Dec 17, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [18d7dcfb19](https://linux-hardware.org/?probe=18d7dcfb19) | Dec 17, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [dec0d049f7](https://linux-hardware.org/?probe=dec0d049f7) | Dec 17, 2022 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | [d9ee8a9854](https://linux-hardware.org/?probe=d9ee8a9854) | Dec 16, 2022 |
| HP            | 8750                        | [a4911352d1](https://linux-hardware.org/?probe=a4911352d1) | Dec 16, 2022 |
| Fujitsu       | D3223-A1 S26361-D3223-A1    | [827fabbd5f](https://linux-hardware.org/?probe=827fabbd5f) | Dec 15, 2022 |
| ASUSTek       | PRIME H370-A                | [eeb913fa7c](https://linux-hardware.org/?probe=eeb913fa7c) | Dec 15, 2022 |
| ASUSTek       | PRIME H370-A                | [7a72cfa484](https://linux-hardware.org/?probe=7a72cfa484) | Dec 15, 2022 |
| Dell          | 018D1Y A00                  | [34611b96d0](https://linux-hardware.org/?probe=34611b96d0) | Dec 15, 2022 |
| ASUSTek       | P5PL2-E                     | [d304b202fc](https://linux-hardware.org/?probe=d304b202fc) | Dec 14, 2022 |
| ASUSTek       | M3A78-EM                    | [3339909881](https://linux-hardware.org/?probe=3339909881) | Dec 14, 2022 |
| MSI           | MS-B9071                    | [fc31fe11a2](https://linux-hardware.org/?probe=fc31fe11a2) | Dec 14, 2022 |
| HP            | 1905                        | [21f639657c](https://linux-hardware.org/?probe=21f639657c) | Dec 13, 2022 |
| Gigabyte      | H57M-USB3                   | [d4812cfdb6](https://linux-hardware.org/?probe=d4812cfdb6) | Dec 13, 2022 |
| Gigabyte      | H57M-USB3                   | [c48aaf8b29](https://linux-hardware.org/?probe=c48aaf8b29) | Dec 12, 2022 |
| Gigabyte      | H77N-WIFI                   | [9704c6b7c4](https://linux-hardware.org/?probe=9704c6b7c4) | Dec 12, 2022 |
| Biostar       | A520MH                      | [e1eff55b96](https://linux-hardware.org/?probe=e1eff55b96) | Dec 12, 2022 |
| Foxconn       | H55MXV-LE                   | [931837aeec](https://linux-hardware.org/?probe=931837aeec) | Dec 12, 2022 |
| Biostar       | A520MH                      | [2c6278e478](https://linux-hardware.org/?probe=2c6278e478) | Dec 11, 2022 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [80281a1e7b](https://linux-hardware.org/?probe=80281a1e7b) | Dec 11, 2022 |
| Unknown       | T3 MRD                      | [c2cb5ad16b](https://linux-hardware.org/?probe=c2cb5ad16b) | Dec 11, 2022 |
| ASUSTek       | TUF Gaming B550-PRO         | [e2a043a361](https://linux-hardware.org/?probe=e2a043a361) | Dec 10, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [9d7365bdd6](https://linux-hardware.org/?probe=9d7365bdd6) | Dec 10, 2022 |
| ASUSTek       | P5Q                         | [fbc5b65636](https://linux-hardware.org/?probe=fbc5b65636) | Dec 10, 2022 |
| ASUSTek       | M3N78-VM                    | [fa99389a1a](https://linux-hardware.org/?probe=fa99389a1a) | Dec 10, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [3e0d5dc490](https://linux-hardware.org/?probe=3e0d5dc490) | Dec 09, 2022 |
| ASUSTek       | P5Q                         | [415b325dd0](https://linux-hardware.org/?probe=415b325dd0) | Dec 09, 2022 |
| Unknown       | Unknown                     | [41ff90c88a](https://linux-hardware.org/?probe=41ff90c88a) | Dec 09, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [ead8cc9c0a](https://linux-hardware.org/?probe=ead8cc9c0a) | Dec 08, 2022 |
| HP            | 82FE 11                     | [6bf35b7005](https://linux-hardware.org/?probe=6bf35b7005) | Dec 08, 2022 |
| Dell          | 0478VN A00                  | [54eaa6d2f3](https://linux-hardware.org/?probe=54eaa6d2f3) | Dec 07, 2022 |
| Gigabyte      | H61M-S1                     | [8c8e80423c](https://linux-hardware.org/?probe=8c8e80423c) | Dec 07, 2022 |
| Gigabyte      | H61M-S1                     | [37283186c3](https://linux-hardware.org/?probe=37283186c3) | Dec 07, 2022 |
| MSI           | K9A2 Platinum               | [3ce727deb7](https://linux-hardware.org/?probe=3ce727deb7) | Dec 06, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [8442e3381c](https://linux-hardware.org/?probe=8442e3381c) | Dec 06, 2022 |
| Apple         | Mac-F221BEC8                | [5132e1aba1](https://linux-hardware.org/?probe=5132e1aba1) | Dec 05, 2022 |
| Dell          | 0T10XW A00                  | [d6f876fa52](https://linux-hardware.org/?probe=d6f876fa52) | Dec 05, 2022 |
| HP            | 8350                        | [f7768016d5](https://linux-hardware.org/?probe=f7768016d5) | Dec 05, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [101ea9ca8e](https://linux-hardware.org/?probe=101ea9ca8e) | Dec 04, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [8de52c0ea7](https://linux-hardware.org/?probe=8de52c0ea7) | Dec 04, 2022 |
| MACHINIST     | E5-MR9A PRO V1.0            | [67fa9fb5aa](https://linux-hardware.org/?probe=67fa9fb5aa) | Dec 03, 2022 |
| MSI           | K9A2 Platinum               | [79c823558a](https://linux-hardware.org/?probe=79c823558a) | Dec 03, 2022 |
| HP            | 2AE2                        | [549eacfc3d](https://linux-hardware.org/?probe=549eacfc3d) | Dec 03, 2022 |
| MSI           | B75A-G41                    | [cbf02bbd94](https://linux-hardware.org/?probe=cbf02bbd94) | Dec 03, 2022 |
| Biostar       | TPower X58                  | [320769fceb](https://linux-hardware.org/?probe=320769fceb) | Dec 02, 2022 |
| AZW           | U59                         | [6a7c9cb905](https://linux-hardware.org/?probe=6a7c9cb905) | Dec 02, 2022 |
| NZXT          | N7 Z590                     | [cc56e65209](https://linux-hardware.org/?probe=cc56e65209) | Dec 02, 2022 |
| Lenovo        | MAHOBAY NOK                 | [dfd11598ed](https://linux-hardware.org/?probe=dfd11598ed) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [c469225241](https://linux-hardware.org/?probe=c469225241) | Dec 01, 2022 |
| MSI           | G41M-S03                    | [763decb5d5](https://linux-hardware.org/?probe=763decb5d5) | Dec 01, 2022 |
| Apple         | Mac-F221BEC8                | [7f91a09589](https://linux-hardware.org/?probe=7f91a09589) | Dec 01, 2022 |
| HP            | 8433 11                     | [01f9a28da3](https://linux-hardware.org/?probe=01f9a28da3) | Dec 01, 2022 |
| OEM           | H110 Ver:2.21               | [ad7fffd9e3](https://linux-hardware.org/?probe=ad7fffd9e3) | Nov 30, 2022 |
| ASRock        | B450M Steel Legend          | [9d6aeff37c](https://linux-hardware.org/?probe=9d6aeff37c) | Nov 30, 2022 |
| OEM           | H110 Ver:2.21               | [2e7e420f42](https://linux-hardware.org/?probe=2e7e420f42) | Nov 29, 2022 |
| Gateway       | SX2851                      | [b408695def](https://linux-hardware.org/?probe=b408695def) | Nov 28, 2022 |
| ASUSTek       | M5A88-M                     | [f4b2035429](https://linux-hardware.org/?probe=f4b2035429) | Nov 28, 2022 |
| HOUTER        | IPMIP-GS                    | [cbc472e6df](https://linux-hardware.org/?probe=cbc472e6df) | Nov 28, 2022 |
| BESSTAR Te... | HM90                        | [eda49557ae](https://linux-hardware.org/?probe=eda49557ae) | Nov 27, 2022 |
| BESSTAR Te... | HM90                        | [6867d8eeaf](https://linux-hardware.org/?probe=6867d8eeaf) | Nov 27, 2022 |
| Megaware      | MW-NM70HD-MI 01/13/2013 ... | [95b48709fd](https://linux-hardware.org/?probe=95b48709fd) | Nov 26, 2022 |
| Huanan        | X99-8M-F V1.1               | [88db74df98](https://linux-hardware.org/?probe=88db74df98) | Nov 26, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | [5b531b7b41](https://linux-hardware.org/?probe=5b531b7b41) | Nov 26, 2022 |
| ASRock        | B450M Pro4                  | [def104dd7d](https://linux-hardware.org/?probe=def104dd7d) | Nov 26, 2022 |
| Huanan        | X99-8M-F V1.1               | [3ca25803b5](https://linux-hardware.org/?probe=3ca25803b5) | Nov 25, 2022 |
| Pegatron      | 2ACF                        | [dc9d24ac01](https://linux-hardware.org/?probe=dc9d24ac01) | Nov 25, 2022 |
| Pegatron      | 2ACF                        | [037b47ab43](https://linux-hardware.org/?probe=037b47ab43) | Nov 25, 2022 |
| HP            | 18E7                        | [048d4bd3ae](https://linux-hardware.org/?probe=048d4bd3ae) | Nov 25, 2022 |
| Dell          | 0T10XW A02                  | [83daa0cf15](https://linux-hardware.org/?probe=83daa0cf15) | Nov 25, 2022 |
| Gigabyte      | H110M-H-CF                  | [c43b60c09b](https://linux-hardware.org/?probe=c43b60c09b) | Nov 25, 2022 |
| Gigabyte      | B560 DS3H AC-Y1             | [6bcefa911d](https://linux-hardware.org/?probe=6bcefa911d) | Nov 24, 2022 |
| Gigabyte      | EG41MF-US2H                 | [07ac3ace2c](https://linux-hardware.org/?probe=07ac3ace2c) | Nov 24, 2022 |
| ASRock        | FP6D4-P1                    | [5e52f1b520](https://linux-hardware.org/?probe=5e52f1b520) | Nov 24, 2022 |
| MSI           | Z490-A PRO                  | [9154fdbc9e](https://linux-hardware.org/?probe=9154fdbc9e) | Nov 24, 2022 |
| Lenovo        | ThinkCentre M91p 4524WAP    | [51f3e71650](https://linux-hardware.org/?probe=51f3e71650) | Nov 24, 2022 |
| ASRock        | Z170 Pro4                   | [ac6ad8d54d](https://linux-hardware.org/?probe=ac6ad8d54d) | Nov 24, 2022 |
| Dell          | 0HN7XN A01                  | [5357d43f13](https://linux-hardware.org/?probe=5357d43f13) | Nov 23, 2022 |
| ASRock        | B450M-HDV R4.0              | [9dbd34c7bd](https://linux-hardware.org/?probe=9dbd34c7bd) | Nov 23, 2022 |
| ASRock        | B450M-HDV R4.0              | [5786af4776](https://linux-hardware.org/?probe=5786af4776) | Nov 23, 2022 |
| Intel         | D946GZAB AAD66610-302       | [5433ee5bc1](https://linux-hardware.org/?probe=5433ee5bc1) | Nov 22, 2022 |
| HP            | 8184 X4                     | [f38ad9d963](https://linux-hardware.org/?probe=f38ad9d963) | Nov 21, 2022 |
| HP            | 822A                        | [b464dc4cf0](https://linux-hardware.org/?probe=b464dc4cf0) | Nov 21, 2022 |
| Acer          | Veriton N4640G              | [a7984c4a95](https://linux-hardware.org/?probe=a7984c4a95) | Nov 20, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | [cd0f904ca4](https://linux-hardware.org/?probe=cd0f904ca4) | Nov 20, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | [c4bd142690](https://linux-hardware.org/?probe=c4bd142690) | Nov 20, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | [41cca3d850](https://linux-hardware.org/?probe=41cca3d850) | Nov 20, 2022 |
| MSI           | Z77A-G43                    | [2033b97419](https://linux-hardware.org/?probe=2033b97419) | Nov 19, 2022 |
| Acer          | FX58M                       | [837da7d885](https://linux-hardware.org/?probe=837da7d885) | Nov 19, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [b40e651ff2](https://linux-hardware.org/?probe=b40e651ff2) | Nov 18, 2022 |
| Dell          | 0HN7XN A00                  | [3e217adbf8](https://linux-hardware.org/?probe=3e217adbf8) | Nov 18, 2022 |
| ASUSTek       | PRIME H370-A                | [0c4442c160](https://linux-hardware.org/?probe=0c4442c160) | Nov 18, 2022 |
| Dell          | 0C27VV A02                  | [5f4b4b8571](https://linux-hardware.org/?probe=5f4b4b8571) | Nov 18, 2022 |
| MSI           | H81M-P33                    | [a535339292](https://linux-hardware.org/?probe=a535339292) | Nov 17, 2022 |
| MSI           | 2AE0                        | [c0d9e23faa](https://linux-hardware.org/?probe=c0d9e23faa) | Nov 16, 2022 |
| MSI           | H81M-P33                    | [246d594268](https://linux-hardware.org/?probe=246d594268) | Nov 16, 2022 |
| HP            | 0AA4h                       | [328259669b](https://linux-hardware.org/?probe=328259669b) | Nov 16, 2022 |
| ASUSTek       | PRIME H370-A                | [9a93c5f349](https://linux-hardware.org/?probe=9a93c5f349) | Nov 15, 2022 |
| ASUSTek       | H110M-A                     | [d1e60135e1](https://linux-hardware.org/?probe=d1e60135e1) | Nov 15, 2022 |
| HP            | 18E7                        | [7ecd6a2f37](https://linux-hardware.org/?probe=7ecd6a2f37) | Nov 15, 2022 |
| Dell          | 0478VN A00                  | [5d1cf4ca11](https://linux-hardware.org/?probe=5d1cf4ca11) | Nov 14, 2022 |
| Gigabyte      | H510M H                     | [97b0a5f239](https://linux-hardware.org/?probe=97b0a5f239) | Nov 14, 2022 |
| HP            | 1850                        | [0b5e36c27b](https://linux-hardware.org/?probe=0b5e36c27b) | Nov 13, 2022 |
| Mediacom      | M-AO241/64                  | [8c577b3d8f](https://linux-hardware.org/?probe=8c577b3d8f) | Nov 13, 2022 |
| ASUSTek       | H110M-A                     | [1c7b3f934d](https://linux-hardware.org/?probe=1c7b3f934d) | Nov 12, 2022 |
| Fujitsu Si... | MS-7304VP-A13               | [69b1471202](https://linux-hardware.org/?probe=69b1471202) | Nov 12, 2022 |
| JGINYUE       | X79M-PLUS V2.3              | [8dac2a9292](https://linux-hardware.org/?probe=8dac2a9292) | Nov 12, 2022 |
| Unknown       | 775i65G                     | [b872a779af](https://linux-hardware.org/?probe=b872a779af) | Nov 12, 2022 |
| Dell          | 018D1Y A00                  | [16247a3667](https://linux-hardware.org/?probe=16247a3667) | Nov 12, 2022 |
| Dell          | 018D1Y A00                  | [bc5562e288](https://linux-hardware.org/?probe=bc5562e288) | Nov 12, 2022 |
| Biostar       | TPower X58                  | [8662697d27](https://linux-hardware.org/?probe=8662697d27) | Nov 11, 2022 |
| Mediacom      | M-AO241/64                  | [d0cac7ee7b](https://linux-hardware.org/?probe=d0cac7ee7b) | Nov 10, 2022 |
| Mediacom      | M-AO241/64                  | [cf0ed7acab](https://linux-hardware.org/?probe=cf0ed7acab) | Nov 10, 2022 |
| Dell          | 0HN7XN A01                  | [bb4dff706b](https://linux-hardware.org/?probe=bb4dff706b) | Nov 10, 2022 |
| Gigabyte      | B75M-D3H                    | [b7619dbd72](https://linux-hardware.org/?probe=b7619dbd72) | Nov 10, 2022 |
| MSI           | A320M-A PRO MAX             | [c3aaf6eed2](https://linux-hardware.org/?probe=c3aaf6eed2) | Nov 09, 2022 |
| MSI           | A320M-A PRO MAX             | [5030ff83c2](https://linux-hardware.org/?probe=5030ff83c2) | Nov 08, 2022 |
| MSI           | H81M-P33                    | [2ef23ed4ac](https://linux-hardware.org/?probe=2ef23ed4ac) | Nov 07, 2022 |
| Acer          | H81H3-M4                    | [40c67913d8](https://linux-hardware.org/?probe=40c67913d8) | Nov 06, 2022 |
| ASRock        | B660M Steel Legend          | [708d98bf92](https://linux-hardware.org/?probe=708d98bf92) | Nov 06, 2022 |
| ASRock        | B660M Steel Legend          | [2fce0b247c](https://linux-hardware.org/?probe=2fce0b247c) | Nov 06, 2022 |
| Gigabyte      | 990XA-UD3                   | [a06275a0f2](https://linux-hardware.org/?probe=a06275a0f2) | Nov 05, 2022 |
| HP            | 1790                        | [8916928344](https://linux-hardware.org/?probe=8916928344) | Nov 05, 2022 |
| HP            | 1790                        | [1de8a8af0d](https://linux-hardware.org/?probe=1de8a8af0d) | Nov 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [507697b22f](https://linux-hardware.org/?probe=507697b22f) | Nov 04, 2022 |
| Dell          | 0C27VV A02                  | [fb4c1f85a2](https://linux-hardware.org/?probe=fb4c1f85a2) | Nov 04, 2022 |
| Dell          | 0HN7XN A01                  | [baf6b79b85](https://linux-hardware.org/?probe=baf6b79b85) | Nov 03, 2022 |
| MSI           | A320M PRO-VD/S              | [920c4567d3](https://linux-hardware.org/?probe=920c4567d3) | Nov 03, 2022 |
| ASUSTek       | P7H55-M LE                  | [383066ca1c](https://linux-hardware.org/?probe=383066ca1c) | Nov 02, 2022 |
| ASUSTek       | P7H55-M LE                  | [66acf8991e](https://linux-hardware.org/?probe=66acf8991e) | Nov 02, 2022 |
| Dell          | 0GDG8Y A00                  | [609ccd3204](https://linux-hardware.org/?probe=609ccd3204) | Nov 02, 2022 |
| Gigabyte      | P55-UD6                     | [2898ec20b3](https://linux-hardware.org/?probe=2898ec20b3) | Nov 01, 2022 |
| Lenovo        | ThinkCentre M55E 898578G    | [d025c115d8](https://linux-hardware.org/?probe=d025c115d8) | Nov 01, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [21213fdeec](https://linux-hardware.org/?probe=21213fdeec) | Oct 31, 2022 |
| HP            | 1790                        | [6dc2cef5ea](https://linux-hardware.org/?probe=6dc2cef5ea) | Oct 31, 2022 |
| Seco          | C40 C                       | [08509c30b6](https://linux-hardware.org/?probe=08509c30b6) | Oct 31, 2022 |
| ASUSTek       | PRIME H370-A                | [f7dd154c47](https://linux-hardware.org/?probe=f7dd154c47) | Oct 30, 2022 |
| Gigabyte      | B450M DS3H V2               | [97d7d8c2d9](https://linux-hardware.org/?probe=97d7d8c2d9) | Oct 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [ae6fd2de89](https://linux-hardware.org/?probe=ae6fd2de89) | Oct 29, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [068d4ec2e6](https://linux-hardware.org/?probe=068d4ec2e6) | Oct 29, 2022 |
| Dell          | 0T2HR0 A02                  | [e4b1137777](https://linux-hardware.org/?probe=e4b1137777) | Oct 29, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [2c57f9b6a3](https://linux-hardware.org/?probe=2c57f9b6a3) | Oct 29, 2022 |
| ASUSTek       | STRIX X99 GAMING            | [f111078004](https://linux-hardware.org/?probe=f111078004) | Oct 29, 2022 |
| MSI           | B560M PRO                   | [a84dc6f9cb](https://linux-hardware.org/?probe=a84dc6f9cb) | Oct 29, 2022 |
| ASUSTek       | STRIX X99 GAMING            | [b683357ec4](https://linux-hardware.org/?probe=b683357ec4) | Oct 28, 2022 |
| Gateway       | SX2851                      | [500b4bb8ec](https://linux-hardware.org/?probe=500b4bb8ec) | Oct 27, 2022 |
| ASUSTek       | P8H61/USB3                  | [c20c97e43e](https://linux-hardware.org/?probe=c20c97e43e) | Oct 27, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [7a0f5285f2](https://linux-hardware.org/?probe=7a0f5285f2) | Oct 26, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [5bc9d4bdc8](https://linux-hardware.org/?probe=5bc9d4bdc8) | Oct 26, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [bb655d6ea7](https://linux-hardware.org/?probe=bb655d6ea7) | Oct 25, 2022 |
| Lenovo        | MAHOBAY NOK                 | [91437ee9a7](https://linux-hardware.org/?probe=91437ee9a7) | Oct 25, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [aa82a1f3c9](https://linux-hardware.org/?probe=aa82a1f3c9) | Oct 24, 2022 |
| Gigabyte      | Z77-DS3H                    | [e894ec1b8d](https://linux-hardware.org/?probe=e894ec1b8d) | Oct 24, 2022 |
| Gigabyte      | Z390 UD                     | [17adb9ee1e](https://linux-hardware.org/?probe=17adb9ee1e) | Oct 23, 2022 |
| Gigabyte      | GA-78LMT-S2                 | [dad9e03a82](https://linux-hardware.org/?probe=dad9e03a82) | Oct 23, 2022 |
| OEM           | G41 775 ICH7 8712           | [1f3d807ceb](https://linux-hardware.org/?probe=1f3d807ceb) | Oct 23, 2022 |
| Dell          | 0JP3NX A01                  | [86365f2c05](https://linux-hardware.org/?probe=86365f2c05) | Oct 23, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [6a42097b41](https://linux-hardware.org/?probe=6a42097b41) | Oct 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | [9035fff7ea](https://linux-hardware.org/?probe=9035fff7ea) | Oct 23, 2022 |
| Dell          | 0200DY A02                  | [8fd4b48b80](https://linux-hardware.org/?probe=8fd4b48b80) | Oct 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | [3d2171b17e](https://linux-hardware.org/?probe=3d2171b17e) | Oct 23, 2022 |
| Dell          | 0HN7XN A01                  | [4e75c878a3](https://linux-hardware.org/?probe=4e75c878a3) | Oct 22, 2022 |
| OEM           | G41 775 ICH7 8712           | [f43a04f63f](https://linux-hardware.org/?probe=f43a04f63f) | Oct 21, 2022 |
| Gigabyte      | GA-78LMT-S2 sex             | [95ddb7c758](https://linux-hardware.org/?probe=95ddb7c758) | Oct 21, 2022 |
| OEM           | G41 775 ICH7 8712           | [354afbd4d8](https://linux-hardware.org/?probe=354afbd4d8) | Oct 20, 2022 |
| OEM           | G41 775 ICH7 8712           | [2991e146ce](https://linux-hardware.org/?probe=2991e146ce) | Oct 19, 2022 |
| ASRock        | 970 Extreme3                | [23f7ae20e3](https://linux-hardware.org/?probe=23f7ae20e3) | Oct 19, 2022 |
| Dell          | 0GTK4K A02                  | [f92314f74b](https://linux-hardware.org/?probe=f92314f74b) | Oct 18, 2022 |
| ASUSTek       | H97-PLUS                    | [0c025c3b68](https://linux-hardware.org/?probe=0c025c3b68) | Oct 16, 2022 |
| Gigabyte      | A320M-S2H-CF                | [c4a0f6af56](https://linux-hardware.org/?probe=c4a0f6af56) | Oct 16, 2022 |
| Gigabyte      | A320M-S2H-CF                | [cde8c87a3a](https://linux-hardware.org/?probe=cde8c87a3a) | Oct 16, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [732c7afd4c](https://linux-hardware.org/?probe=732c7afd4c) | Oct 16, 2022 |
| HP            | 1790                        | [5b9b2357c5](https://linux-hardware.org/?probe=5b9b2357c5) | Oct 16, 2022 |
| Intel         | H55                         | [ab27a6c8d9](https://linux-hardware.org/?probe=ab27a6c8d9) | Oct 15, 2022 |
| HP            | 18E7                        | [98b59ebfce](https://linux-hardware.org/?probe=98b59ebfce) | Oct 13, 2022 |
| HP            | 0AA0h                       | [f4a69ac6f5](https://linux-hardware.org/?probe=f4a69ac6f5) | Oct 13, 2022 |
| HP            | 2AF3                        | [f59df65c18](https://linux-hardware.org/?probe=f59df65c18) | Oct 12, 2022 |
| Unknown       | Unknown                     | [bfd4bad69d](https://linux-hardware.org/?probe=bfd4bad69d) | Oct 11, 2022 |
| HP            | 304Ah                       | [69f11e2008](https://linux-hardware.org/?probe=69f11e2008) | Oct 11, 2022 |
| MSI           | B550-A PRO                  | [5c2dd967f9](https://linux-hardware.org/?probe=5c2dd967f9) | Oct 11, 2022 |
| Standard      | X50-V2                      | [fbcfd56903](https://linux-hardware.org/?probe=fbcfd56903) | Oct 11, 2022 |
| Alienware     | 0NWN7M A00                  | [a7c3e67810](https://linux-hardware.org/?probe=a7c3e67810) | Oct 10, 2022 |
| Dell          | 0X9M3X A01                  | [b729cadad8](https://linux-hardware.org/?probe=b729cadad8) | Oct 10, 2022 |
| ASUSTek       | H81M-P                      | [907b7761d0](https://linux-hardware.org/?probe=907b7761d0) | Oct 09, 2022 |
| ASUSTek       | H81M-P                      | [f2d9df375d](https://linux-hardware.org/?probe=f2d9df375d) | Oct 09, 2022 |
| Unknown       | Unknown                     | [fef2c17618](https://linux-hardware.org/?probe=fef2c17618) | Oct 09, 2022 |
| Acer          | EM61SM/EM61PM               | [58d2cda88f](https://linux-hardware.org/?probe=58d2cda88f) | Oct 08, 2022 |
| ASUSTek       | CM1630                      | [dc63e03d48](https://linux-hardware.org/?probe=dc63e03d48) | Oct 08, 2022 |
| Gateway       | SX2851                      | [2cc7e399b2](https://linux-hardware.org/?probe=2cc7e399b2) | Oct 08, 2022 |
| HP            | 822A                        | [c893a1b314](https://linux-hardware.org/?probe=c893a1b314) | Oct 07, 2022 |
| Dell          | 0YP696 A00                  | [588d3a6132](https://linux-hardware.org/?probe=588d3a6132) | Oct 07, 2022 |
| HP            | 8265                        | [ddf5f03d86](https://linux-hardware.org/?probe=ddf5f03d86) | Oct 07, 2022 |
| HP            | 843B                        | [5a744e115f](https://linux-hardware.org/?probe=5a744e115f) | Oct 06, 2022 |
| Gigabyte      | B250M-D3H-CF                | [2e57f97484](https://linux-hardware.org/?probe=2e57f97484) | Oct 06, 2022 |
| HP            | 2B60 MVB                    | [092e063471](https://linux-hardware.org/?probe=092e063471) | Oct 05, 2022 |
| HP            | 3397                        | [eb6f8b5a56](https://linux-hardware.org/?probe=eb6f8b5a56) | Oct 03, 2022 |
| ASUSTek       | P7H55-USB3                  | [9f15eece8f](https://linux-hardware.org/?probe=9f15eece8f) | Oct 03, 2022 |
| ASUSTek       | M3A78-EM                    | [0c58d8b873](https://linux-hardware.org/?probe=0c58d8b873) | Oct 03, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [b8d65ced41](https://linux-hardware.org/?probe=b8d65ced41) | Oct 02, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [b5b057439d](https://linux-hardware.org/?probe=b5b057439d) | Oct 02, 2022 |
| ASRock        | 970 Pro3 R2.0               | [592adc6c9b](https://linux-hardware.org/?probe=592adc6c9b) | Oct 01, 2022 |
| HP            | 843B                        | [b683039e3b](https://linux-hardware.org/?probe=b683039e3b) | Oct 01, 2022 |
| HP            | 1632                        | [0f9387690b](https://linux-hardware.org/?probe=0f9387690b) | Oct 01, 2022 |
| Biostar       | B350ET2                     | [d7c5b1ad40](https://linux-hardware.org/?probe=d7c5b1ad40) | Oct 01, 2022 |
| Biostar       | B350ET2                     | [2b7bea0eda](https://linux-hardware.org/?probe=2b7bea0eda) | Sep 30, 2022 |
| MSI           | Z97 MPOWER                  | [f16a15a5b7](https://linux-hardware.org/?probe=f16a15a5b7) | Sep 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [8c116d30f9](https://linux-hardware.org/?probe=8c116d30f9) | Sep 30, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [7bffcb84c2](https://linux-hardware.org/?probe=7bffcb84c2) | Sep 29, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [e3e6ad5c35](https://linux-hardware.org/?probe=e3e6ad5c35) | Sep 29, 2022 |
| HP            | 8055                        | [aa3bd09485](https://linux-hardware.org/?probe=aa3bd09485) | Sep 29, 2022 |
| HP            | 843C                        | [e27595d303](https://linux-hardware.org/?probe=e27595d303) | Sep 29, 2022 |
| ASUSTek       | P5K                         | [2d278ddcdf](https://linux-hardware.org/?probe=2d278ddcdf) | Sep 28, 2022 |
| ASUSTek       | B85M-E/BR                   | [5116d1cae9](https://linux-hardware.org/?probe=5116d1cae9) | Sep 27, 2022 |
| Dell          | XPS 8700                    | [19fff8b508](https://linux-hardware.org/?probe=19fff8b508) | Sep 27, 2022 |
| Dell          | 0WN7Y6 A01                  | [356dc77824](https://linux-hardware.org/?probe=356dc77824) | Sep 27, 2022 |
| ASUSTek       | M3A78-EM                    | [34287ac52a](https://linux-hardware.org/?probe=34287ac52a) | Sep 27, 2022 |
| ASRock        | A75M-HVS                    | [75d51e6237](https://linux-hardware.org/?probe=75d51e6237) | Sep 26, 2022 |
| Gateway       | FMCP7AM                     | [0cb51f3e6f](https://linux-hardware.org/?probe=0cb51f3e6f) | Sep 25, 2022 |
| ASUSTek       | PRO A320M-R WI-FI           | [e760f06cef](https://linux-hardware.org/?probe=e760f06cef) | Sep 25, 2022 |
| Gigabyte      | GA-870A-UD3                 | [33a0b663ea](https://linux-hardware.org/?probe=33a0b663ea) | Sep 25, 2022 |
| ASRock        | QC5000M-ITX/PH              | [571b95c201](https://linux-hardware.org/?probe=571b95c201) | Sep 25, 2022 |
| HP            | 18E7                        | [71a12280de](https://linux-hardware.org/?probe=71a12280de) | Sep 24, 2022 |
| ASRock        | B85M Pro4                   | [cd75d968d7](https://linux-hardware.org/?probe=cd75d968d7) | Sep 23, 2022 |
| ASUSTek       | P5K                         | [0ddf0a48dd](https://linux-hardware.org/?probe=0ddf0a48dd) | Sep 22, 2022 |
| Pegatron      | 2ACD                        | [d6270f88cc](https://linux-hardware.org/?probe=d6270f88cc) | Sep 22, 2022 |
| HP            | 8055                        | [c72e0ed04b](https://linux-hardware.org/?probe=c72e0ed04b) | Sep 22, 2022 |
| ASUSTek       | Benicia                     | [22bf75699c](https://linux-hardware.org/?probe=22bf75699c) | Sep 21, 2022 |
| ASRock        | A75M-HVS                    | [0f81852612](https://linux-hardware.org/?probe=0f81852612) | Sep 21, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [f49e8d08ef](https://linux-hardware.org/?probe=f49e8d08ef) | Sep 20, 2022 |
| Dell          | 0D441T A01                  | [c315329853](https://linux-hardware.org/?probe=c315329853) | Sep 20, 2022 |
| MSI           | MS-7260                     | [52d2fa8c71](https://linux-hardware.org/?probe=52d2fa8c71) | Sep 20, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [37dbdb48dd](https://linux-hardware.org/?probe=37dbdb48dd) | Sep 20, 2022 |
| Lenovo        | ThinkCentre M71e 3157AE2    | [9022058466](https://linux-hardware.org/?probe=9022058466) | Sep 19, 2022 |
| HP            | 0AA8h                       | [c79bdb21ed](https://linux-hardware.org/?probe=c79bdb21ed) | Sep 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [a5d838868a](https://linux-hardware.org/?probe=a5d838868a) | Sep 18, 2022 |
| Lenovo        | ThinkCentre M58e 7298A76    | [4775ccd67f](https://linux-hardware.org/?probe=4775ccd67f) | Sep 18, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [875435f3f0](https://linux-hardware.org/?probe=875435f3f0) | Sep 15, 2022 |
| ASRock        | H61M-DGS                    | [aeac7cfb74](https://linux-hardware.org/?probe=aeac7cfb74) | Sep 14, 2022 |
| Dell          | 0TW904 A01                  | [141188a631](https://linux-hardware.org/?probe=141188a631) | Sep 14, 2022 |
| Gigabyte      | Z77-D3H                     | [b1b929517d](https://linux-hardware.org/?probe=b1b929517d) | Sep 13, 2022 |
| ASUSTek       | PRIME Z270-A                | [b404f51fbe](https://linux-hardware.org/?probe=b404f51fbe) | Sep 12, 2022 |
| Lenovo        | SDK0J40700 WIN              | [b8f3a58a03](https://linux-hardware.org/?probe=b8f3a58a03) | Sep 11, 2022 |
| Gigabyte      | G1.Sniper Z97               | [445e54016b](https://linux-hardware.org/?probe=445e54016b) | Sep 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [0701918099](https://linux-hardware.org/?probe=0701918099) | Sep 11, 2022 |
| ECS           | Iris8                       | [dcfb9e172d](https://linux-hardware.org/?probe=dcfb9e172d) | Sep 11, 2022 |
| HP            | 0A54h                       | [2c88c7fd30](https://linux-hardware.org/?probe=2c88c7fd30) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [d13cf99728](https://linux-hardware.org/?probe=d13cf99728) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [1e43753d7a](https://linux-hardware.org/?probe=1e43753d7a) | Sep 10, 2022 |
| MSI           | 2AE0                        | [a2b046dd4e](https://linux-hardware.org/?probe=a2b046dd4e) | Sep 10, 2022 |
| HP            | 3031h                       | [ea434d67b5](https://linux-hardware.org/?probe=ea434d67b5) | Sep 10, 2022 |
| HP            | 3031h                       | [feddf42c9f](https://linux-hardware.org/?probe=feddf42c9f) | Sep 10, 2022 |
| ECS           | Iris8                       | [29bc0560b4](https://linux-hardware.org/?probe=29bc0560b4) | Sep 10, 2022 |
| HP            | 0AA8h                       | [4e9a1e883c](https://linux-hardware.org/?probe=4e9a1e883c) | Sep 09, 2022 |
| Lenovo        | MAHOBAY                     | [2619e261d1](https://linux-hardware.org/?probe=2619e261d1) | Sep 07, 2022 |
| Intel         | SKYBAY                      | [b667cf66e8](https://linux-hardware.org/?probe=b667cf66e8) | Sep 07, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [dd20f0351c](https://linux-hardware.org/?probe=dd20f0351c) | Sep 06, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [3aca46f88b](https://linux-hardware.org/?probe=3aca46f88b) | Sep 06, 2022 |
| ASUSTek       | A88X-GAMER                  | [15fe45edd7](https://linux-hardware.org/?probe=15fe45edd7) | Sep 06, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [92ff48d462](https://linux-hardware.org/?probe=92ff48d462) | Sep 06, 2022 |
| HP            | 2AF7                        | [9b7ccd5aa0](https://linux-hardware.org/?probe=9b7ccd5aa0) | Sep 06, 2022 |
| Dell          | 0HY9JP A02                  | [7cbf141461](https://linux-hardware.org/?probe=7cbf141461) | Sep 05, 2022 |
| ASRock        | B550M/ac                    | [b8ccaa27ef](https://linux-hardware.org/?probe=b8ccaa27ef) | Sep 04, 2022 |
| HP            | 821D                        | [459bdd177e](https://linux-hardware.org/?probe=459bdd177e) | Sep 03, 2022 |
| ASUSTek       | P8B75-V                     | [2ae6d7c950](https://linux-hardware.org/?probe=2ae6d7c950) | Sep 03, 2022 |
| HP            | 87D6 SMVB                   | [e597d54472](https://linux-hardware.org/?probe=e597d54472) | Sep 03, 2022 |
| MSI           | H97 GAMING 3                | [a5fb8d7651](https://linux-hardware.org/?probe=a5fb8d7651) | Sep 02, 2022 |
| ASUSTek       | PRIME B450M-A II            | [63e2adf3a9](https://linux-hardware.org/?probe=63e2adf3a9) | Sep 02, 2022 |
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
| HP            | 2AF7                        | [fbc1710ad8](https://linux-hardware.org/?probe=fbc1710ad8) | Aug 22, 2022 |
| MSI           | X99S GAMING 7               | [f729654c4a](https://linux-hardware.org/?probe=f729654c4a) | Aug 22, 2022 |
| ASUSTek       | J1800I-C/BR                 | [f2f76737ad](https://linux-hardware.org/?probe=f2f76737ad) | Aug 22, 2022 |
| Dell          | 0C27VV A03                  | [4e894e1897](https://linux-hardware.org/?probe=4e894e1897) | Aug 21, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [4dc3a452d9](https://linux-hardware.org/?probe=4dc3a452d9) | Aug 19, 2022 |
| ASUSTek       | ProArt B660-CREATOR D4      | [0b9e6d6ad9](https://linux-hardware.org/?probe=0b9e6d6ad9) | Aug 19, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [6865f5ed0b](https://linux-hardware.org/?probe=6865f5ed0b) | Aug 19, 2022 |
| BESSTAR Te... | UM350                       | [c7bb6b56fb](https://linux-hardware.org/?probe=c7bb6b56fb) | Aug 18, 2022 |
| ASUSTek       | PRIME Z390-A                | [e03daeba5f](https://linux-hardware.org/?probe=e03daeba5f) | Aug 18, 2022 |
| ASRock        | B550M Pro4                  | [ab3425dd99](https://linux-hardware.org/?probe=ab3425dd99) | Aug 17, 2022 |
| ASUSTek       | PRIME H370-A                | [da477254e7](https://linux-hardware.org/?probe=da477254e7) | Aug 16, 2022 |
| Gigabyte      | M4HM87P-00                  | [5bb7e42eae](https://linux-hardware.org/?probe=5bb7e42eae) | Aug 16, 2022 |
| ASUSTek       | J1800I-C/BR                 | [01beed2be8](https://linux-hardware.org/?probe=01beed2be8) | Aug 15, 2022 |
| HP            | 339A                        | [c3e5458c9a](https://linux-hardware.org/?probe=c3e5458c9a) | Aug 15, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [08fa90340d](https://linux-hardware.org/?probe=08fa90340d) | Aug 14, 2022 |
| MAXSUN        | MS-TZZ A520M                | [aa844d0dce](https://linux-hardware.org/?probe=aa844d0dce) | Aug 14, 2022 |
| Gigabyte      | 970A-DS3P                   | [47632d043c](https://linux-hardware.org/?probe=47632d043c) | Aug 14, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [58d97fbc16](https://linux-hardware.org/?probe=58d97fbc16) | Aug 14, 2022 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | [0c80c167e4](https://linux-hardware.org/?probe=0c80c167e4) | Aug 13, 2022 |
| ASUSTek       | A88X-PRO                    | [399f7ec1da](https://linux-hardware.org/?probe=399f7ec1da) | Aug 12, 2022 |
| ASUSTek       | P5GC-MX                     | [346a48750b](https://linux-hardware.org/?probe=346a48750b) | Aug 12, 2022 |
| ASUSTek       | J1800I-C/BR                 | [41cd4b02f1](https://linux-hardware.org/?probe=41cd4b02f1) | Aug 11, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [687375ec7c](https://linux-hardware.org/?probe=687375ec7c) | Aug 11, 2022 |
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
| Dell          | 09KPNV A00                  | [c47ecbd03f](https://linux-hardware.org/?probe=c47ecbd03f) | Jul 16, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Zorin 16 | 1205     | 65.74%  |
| Zorin 15 | 552      | 30.11%  |
| Zorin 12 | 76       | 4.15%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| Zorin | 1829     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.15.0-56-generic | 72       | 3.39%   |
| 5.11.0-38-generic | 62       | 2.92%   |
| 5.15.0-67-generic | 57       | 2.69%   |
| 5.15.0-69-generic | 56       | 2.64%   |
| 5.11.0-27-generic | 56       | 2.64%   |
| 5.15.0-46-generic | 55       | 2.59%   |
| 5.11.0-40-generic | 50       | 2.36%   |
| 5.15.0-52-generic | 49       | 2.31%   |
| 5.13.0-39-generic | 49       | 2.31%   |
| 5.15.0-58-generic | 46       | 2.17%   |
| 5.15.0-60-generic | 45       | 2.12%   |
| 5.15.0-48-generic | 41       | 1.93%   |
| 5.11.0-41-generic | 41       | 1.93%   |
| 5.3.0-40-generic  | 40       | 1.89%   |
| 5.13.0-30-generic | 40       | 1.89%   |
| 5.15.0-71-generic | 39       | 1.84%   |
| 5.13.0-40-generic | 38       | 1.79%   |
| 5.15.0-76-generic | 36       | 1.7%    |
| 5.11.0-43-generic | 36       | 1.7%    |
| 5.15.0-41-generic | 35       | 1.65%   |
| 5.11.0-37-generic | 35       | 1.65%   |
| 5.4.0-42-generic  | 31       | 1.46%   |
| 5.13.0-28-generic | 31       | 1.46%   |
| 5.11.0-34-generic | 31       | 1.46%   |
| 5.15.0-78-generic | 30       | 1.41%   |
| 5.15.0-53-generic | 29       | 1.37%   |
| 5.13.0-35-generic | 28       | 1.32%   |
| 5.15.0-73-generic | 27       | 1.27%   |
| 5.0.0-37-generic  | 27       | 1.27%   |
| 5.13.0-27-generic | 26       | 1.23%   |
| 5.13.0-41-generic | 25       | 1.18%   |
| 5.13.0-52-generic | 24       | 1.13%   |
| 5.15.0-72-generic | 22       | 1.04%   |
| 5.13.0-44-generic | 21       | 0.99%   |
| 5.4.0-58-generic  | 20       | 0.94%   |
| 5.4.0-47-generic  | 20       | 0.94%   |
| 5.4.0-72-generic  | 19       | 0.9%    |
| 5.3.0-62-generic  | 17       | 0.8%    |
| 5.3.0-51-generic  | 17       | 0.8%    |
| 5.3.0-46-generic  | 17       | 0.8%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 594      | 31.13%  |
| 5.11.0  | 334      | 17.51%  |
| 5.4.0   | 325      | 17.03%  |
| 5.13.0  | 293      | 15.36%  |
| 5.3.0   | 158      | 8.28%   |
| 4.15.0  | 75       | 3.93%   |
| 5.0.0   | 58       | 3.04%   |
| 4.18.0  | 27       | 1.42%   |
| 5.8.0   | 26       | 1.36%   |
| 6.3.2   | 1        | 0.05%   |
| 6.2.7   | 1        | 0.05%   |
| 6.1.8   | 1        | 0.05%   |
| 6.1.7   | 1        | 0.05%   |
| 6.0.8   | 1        | 0.05%   |
| 5.8.5   | 1        | 0.05%   |
| 5.7.17  | 1        | 0.05%   |
| 5.7.1   | 1        | 0.05%   |
| 5.7.0   | 1        | 0.05%   |
| 5.19.6  | 1        | 0.05%   |
| 5.19.2  | 1        | 0.05%   |
| 5.19.12 | 1        | 0.05%   |
| 5.17.9  | 1        | 0.05%   |
| 5.17.5  | 1        | 0.05%   |
| 5.17.1  | 1        | 0.05%   |
| 5.15.13 | 1        | 0.05%   |
| 5.14.0  | 1        | 0.05%   |
| 4.4.0   | 1        | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 595      | 31.2%   |
| 5.11    | 334      | 17.51%  |
| 5.4     | 325      | 17.04%  |
| 5.13    | 293      | 15.36%  |
| 5.3     | 158      | 8.29%   |
| 4.15    | 75       | 3.93%   |
| 5.0     | 58       | 3.04%   |
| 5.8     | 27       | 1.42%   |
| 4.18    | 27       | 1.42%   |
| 5.7     | 3        | 0.16%   |
| 5.19    | 3        | 0.16%   |
| 5.17    | 3        | 0.16%   |
| 6.3     | 1        | 0.05%   |
| 6.2     | 1        | 0.05%   |
| 6.1     | 1        | 0.05%   |
| 6.0     | 1        | 0.05%   |
| 5.14    | 1        | 0.05%   |
| 4.4     | 1        | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 1718     | 93.93%  |
| i686   | 111      | 6.07%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 1395     | 75.16%  |
| XFCE       | 336      | 18.1%   |
| Unknown    | 118      | 6.36%   |
| KDE5       | 2        | 0.11%   |
| Cinnamon   | 2        | 0.11%   |
| X-Cinnamon | 1        | 0.05%   |
| MATE       | 1        | 0.05%   |
| KDE        | 1        | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 1756     | 95.28%  |
| Unknown | 67       | 3.64%   |
| Wayland | 19       | 1.03%   |
| Tty     | 1        | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1565     | 84.05%  |
| GDM3    | 122      | 6.55%   |
| GDM     | 93       | 4.99%   |
| LightDM | 77       | 4.14%   |
| TDM     | 4        | 0.21%   |
| SDDM    | 1        | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 679      | 36.88%  |
| de_DE       | 155      | 8.42%   |
| pt_BR       | 135      | 7.33%   |
| en_GB       | 122      | 6.63%   |
| Unknown     | 96       | 5.21%   |
| it_IT       | 52       | 2.82%   |
| fr_FR       | 52       | 2.82%   |
| en_CA       | 49       | 2.66%   |
| en_IN       | 40       | 2.17%   |
| pl_PL       | 37       | 2.01%   |
| es_ES       | 36       | 1.96%   |
| en_AU       | 34       | 1.85%   |
| nl_NL       | 32       | 1.74%   |
| es_AR       | 31       | 1.68%   |
| ru_RU       | 25       | 1.36%   |
| es_MX       | 21       | 1.14%   |
| en_ZA       | 19       | 1.03%   |
| hu_HU       | 18       | 0.98%   |
| sv_SE       | 12       | 0.65%   |
| pt_PT       | 12       | 0.65%   |
| cs_CZ       | 12       | 0.65%   |
| fr_CA       | 10       | 0.54%   |
| tr_TR       | 8        | 0.43%   |
| nl_BE       | 8        | 0.43%   |
| es_CO       | 8        | 0.43%   |
| C           | 8        | 0.43%   |
| nb_NO       | 7        | 0.38%   |
| es_CL       | 7        | 0.38%   |
| ja_JP       | 6        | 0.33%   |
| en_NZ       | 6        | 0.33%   |
| el_GR       | 6        | 0.33%   |
| fi_FI       | 5        | 0.27%   |
| es_VE       | 5        | 0.27%   |
| en_PH       | 5        | 0.27%   |
| de_CH       | 5        | 0.27%   |
| da_DK       | 5        | 0.27%   |
| sk_SK       | 4        | 0.22%   |
| es_PE       | 4        | 0.22%   |
| bg_BG       | 4        | 0.22%   |
| sr_RS@latin | 3        | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1137     | 61.59%  |
| EFI  | 709      | 38.41%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 1714     | 93.15%  |
| Overlay  | 34       | 1.85%   |
| Zfs      | 26       | 1.41%   |
| Tmpfs    | 20       | 1.09%   |
| Btrfs    | 15       | 0.82%   |
| Ext2     | 11       | 0.6%    |
| Unknown  | 10       | 0.54%   |
| Xfs      | 5        | 0.27%   |
| Ext3     | 4        | 0.22%   |
| Reiserfs | 1        | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1676     | 90.84%  |
| GPT     | 102      | 5.53%   |
| MBR     | 67       | 3.63%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1709     | 92.83%  |
| Yes       | 132      | 7.17%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1463     | 79.08%  |
| Yes       | 387      | 20.92%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 411      | 22.47%  |
| Gigabyte Technology | 281      | 15.36%  |
| Dell                | 196      | 10.72%  |
| Hewlett-Packard     | 166      | 9.08%   |
| MSI                 | 164      | 8.97%   |
| ASRock              | 142      | 7.76%   |
| Lenovo              | 82       | 4.48%   |
| Intel               | 56       | 3.06%   |
| Pegatron            | 34       | 1.86%   |
| Acer                | 33       | 1.8%    |
| Unknown             | 32       | 1.75%   |
| Foxconn             | 25       | 1.37%   |
| Biostar             | 25       | 1.37%   |
| Fujitsu             | 24       | 1.31%   |
| ECS                 | 18       | 0.98%   |
| Positivo            | 8        | 0.44%   |
| Medion              | 8        | 0.44%   |
| Alienware           | 7        | 0.38%   |
| Shuttle             | 6        | 0.33%   |
| Apple               | 6        | 0.33%   |
| Gateway             | 5        | 0.27%   |
| Packard Bell        | 4        | 0.22%   |
| OEM                 | 4        | 0.22%   |
| IBM                 | 4        | 0.22%   |
| Google              | 4        | 0.22%   |
| eMachines           | 4        | 0.22%   |
| BESSTAR Tech        | 4        | 0.22%   |
| Huanan              | 3        | 0.16%   |
| AZW                 | 3        | 0.16%   |
| ABIT                | 3        | 0.16%   |
| ZOTAC               | 2        | 0.11%   |
| WinFast             | 2        | 0.11%   |
| SiS Technology      | 2        | 0.11%   |
| Semp Toshiba        | 2        | 0.11%   |
| QIYIDA              | 2        | 0.11%   |
| PCWare              | 2        | 0.11%   |
| MAXSUN              | 2        | 0.11%   |
| JGINYUE             | 2        | 0.11%   |
| HOUTER              | 2        | 0.11%   |
| Xi3                 | 1        | 0.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 41       | 2.24%   |
| Unknown                          | 36       | 1.97%   |
| Dell OptiPlex 7010               | 15       | 0.82%   |
| Dell OptiPlex 780                | 11       | 0.6%    |
| Gigabyte A320M-S2H               | 10       | 0.55%   |
| Dell OptiPlex 790                | 10       | 0.55%   |
| MSI MS-7817                      | 9        | 0.49%   |
| Dell OptiPlex 380                | 9        | 0.49%   |
| MSI MS-7C02                      | 8        | 0.44%   |
| Dell OptiPlex 755                | 8        | 0.44%   |
| ASUS M5A97 R2.0                  | 8        | 0.44%   |
| ASUS M5A78L-M/USB3               | 8        | 0.44%   |
| Gigabyte GA-78LMT-USB3 6.0       | 7        | 0.38%   |
| Gigabyte B450 AORUS M            | 7        | 0.38%   |
| Gigabyte 970A-DS3P               | 7        | 0.38%   |
| Dell OptiPlex 990                | 7        | 0.38%   |
| HP ProDesk 600 G1 SFF            | 6        | 0.33%   |
| Dell Precision WorkStation T3500 | 6        | 0.33%   |
| Dell OptiPlex 7040               | 6        | 0.33%   |
| Dell OptiPlex 3010               | 6        | 0.33%   |
| Intel H61                        | 5        | 0.27%   |
| HP Compaq Pro 6300 SFF           | 5        | 0.27%   |
| HP Compaq Elite 8300 SFF         | 5        | 0.27%   |
| Gigabyte GA-78LMT-USB3           | 5        | 0.27%   |
| Gigabyte B450M DS3H              | 5        | 0.27%   |
| Dell OptiPlex 9020               | 5        | 0.27%   |
| Dell OptiPlex 3020               | 5        | 0.27%   |
| Dell Inspiron 3847               | 5        | 0.27%   |
| ASUS TUF Gaming X570-PLUS        | 5        | 0.27%   |
| ASRock N68C-S UCC                | 5        | 0.27%   |
| MSI MS-7C91                      | 4        | 0.22%   |
| MSI MS-7C37                      | 4        | 0.22%   |
| MSI MS-7B86                      | 4        | 0.22%   |
| MSI MS-7A38                      | 4        | 0.22%   |
| MSI MS-7721                      | 4        | 0.22%   |
| Intel X79M-S                     | 4        | 0.22%   |
| Intel H55                        | 4        | 0.22%   |
| Gigabyte X570 AORUS ELITE        | 4        | 0.22%   |
| Gigabyte M68MT-S2                | 4        | 0.22%   |
| Gigabyte GA-78LMT-S2             | 4        | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 122      | 6.67%   |
| HP Compaq              | 61       | 3.34%   |
| Lenovo ThinkCentre     | 53       | 2.9%    |
| ASUS PRIME             | 49       | 2.68%   |
| ASUS All               | 41       | 2.24%   |
| ASUS ROG               | 38       | 2.08%   |
| Unknown                | 36       | 1.97%   |
| ASUS TUF               | 33       | 1.8%    |
| Dell Precision         | 23       | 1.26%   |
| HP EliteDesk           | 20       | 1.09%   |
| Fujitsu ESPRIMO        | 19       | 1.04%   |
| Gigabyte B450          | 15       | 0.82%   |
| Dell Inspiron          | 15       | 0.82%   |
| HP ProDesk             | 14       | 0.77%   |
| ASUS M5A97             | 14       | 0.77%   |
| Acer Aspire            | 14       | 0.77%   |
| Gigabyte GA-78LMT-USB3 | 13       | 0.71%   |
| ASUS M5A78L-M          | 13       | 0.71%   |
| HP Pavilion            | 11       | 0.6%    |
| Gigabyte A320M-S2H     | 11       | 0.6%    |
| Dell Vostro            | 11       | 0.6%    |
| Gigabyte X570          | 10       | 0.55%   |
| Acer Veriton           | 10       | 0.55%   |
| MSI MS-7817            | 9        | 0.49%   |
| Lenovo IdeaCentre      | 9        | 0.49%   |
| Gigabyte B450M         | 9        | 0.49%   |
| MSI MS-7C02            | 8        | 0.44%   |
| Dell XPS               | 8        | 0.44%   |
| ASUS P8H61-M           | 8        | 0.44%   |
| ASRock B450M           | 8        | 0.44%   |
| ASRock B450            | 8        | 0.44%   |
| Gigabyte 970A-DS3P     | 7        | 0.38%   |
| ASUS P5G41T-M          | 7        | 0.38%   |
| ASRock X570            | 7        | 0.38%   |
| ASRock N68C-S          | 6        | 0.33%   |
| Intel H61              | 5        | 0.27%   |
| Gigabyte B550M         | 5        | 0.27%   |
| Gigabyte B550          | 5        | 0.27%   |
| ASUS P7H55-M           | 5        | 0.27%   |
| ASUS P5KPL-AM          | 5        | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2012    | 163      | 8.91%   |
| 2013    | 158      | 8.64%   |
| 2011    | 158      | 8.64%   |
| 2018    | 143      | 7.82%   |
| 2010    | 136      | 7.44%   |
| 2014    | 131      | 7.16%   |
| 2009    | 122      | 6.67%   |
| 2008    | 113      | 6.18%   |
| 2020    | 99       | 5.41%   |
| 2019    | 92       | 5.03%   |
| 2017    | 92       | 5.03%   |
| 2007    | 81       | 4.43%   |
| 2021    | 78       | 4.26%   |
| 2016    | 63       | 3.44%   |
| 2015    | 60       | 3.28%   |
| 2006    | 46       | 2.52%   |
| 2022    | 35       | 1.91%   |
| 2005    | 29       | 1.59%   |
| 2004    | 10       | 0.55%   |
| 2023    | 8        | 0.44%   |
| 2003    | 6        | 0.33%   |
| Unknown | 5        | 0.27%   |
| 2002    | 1        | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 1829     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 1742     | 94.88%  |
| Enabled  | 94       | 5.12%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1825     | 99.78%  |
| Yes  | 4        | 0.22%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 385      | 20.67%  |
| 8.01-16.0       | 375      | 20.13%  |
| 3.01-4.0        | 344      | 18.46%  |
| 4.01-8.0        | 291      | 15.62%  |
| 32.01-64.0      | 199      | 10.68%  |
| 1.01-2.0        | 110      | 5.9%    |
| 64.01-256.0     | 50       | 2.68%   |
| 2.01-3.0        | 49       | 2.63%   |
| 24.01-32.0      | 34       | 1.83%   |
| 0.51-1.0        | 25       | 1.34%   |
| More than 256.0 | 1        | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 807      | 40.47%  |
| 2.01-3.0   | 529      | 26.53%  |
| 3.01-4.0   | 237      | 11.89%  |
| 4.01-8.0   | 217      | 10.88%  |
| 0.51-1.0   | 136      | 6.82%   |
| 8.01-16.0  | 42       | 2.11%   |
| 0.01-0.5   | 16       | 0.8%    |
| 16.01-24.0 | 7        | 0.35%   |
| 32.01-64.0 | 2        | 0.1%    |
| 24.01-32.0 | 1        | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 920      | 48.78%  |
| 2      | 510      | 27.04%  |
| 3      | 223      | 11.82%  |
| 4      | 112      | 5.94%   |
| 5      | 58       | 3.08%   |
| 6      | 31       | 1.64%   |
| 7      | 12       | 0.64%   |
| 0      | 9        | 0.48%   |
| 8      | 8        | 0.42%   |
| 51     | 1        | 0.05%   |
| 11     | 1        | 0.05%   |
| 10     | 1        | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 998      | 54.21%  |
| No        | 843      | 45.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1807     | 98.8%   |
| No        | 22       | 1.2%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 940      | 50.84%  |
| Yes       | 909      | 49.16%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1325     | 71.7%   |
| Yes       | 523      | 28.3%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 457      | 24.92%  |
| Germany      | 171      | 9.32%   |
| Brazil       | 150      | 8.18%   |
| UK           | 123      | 6.71%   |
| Canada       | 69       | 3.76%   |
| Italy        | 64       | 3.49%   |
| Netherlands  | 56       | 3.05%   |
| France       | 51       | 2.78%   |
| India        | 42       | 2.29%   |
| Poland       | 41       | 2.24%   |
| Spain        | 40       | 2.18%   |
| Australia    | 37       | 2.02%   |
| Argentina    | 36       | 1.96%   |
| Mexico       | 26       | 1.42%   |
| Hungary      | 22       | 1.2%    |
| South Africa | 21       | 1.15%   |
| Russia       | 21       | 1.15%   |
| Sweden       | 18       | 0.98%   |
| Greece       | 18       | 0.98%   |
| Portugal     | 17       | 0.93%   |
| Denmark      | 17       | 0.93%   |
| Belgium      | 17       | 0.93%   |
| Indonesia    | 16       | 0.87%   |
| Czechia      | 16       | 0.87%   |
| Switzerland  | 15       | 0.82%   |
| Norway       | 15       | 0.82%   |
| Colombia     | 13       | 0.71%   |
| Chile        | 13       | 0.71%   |
| Serbia       | 11       | 0.6%    |
| Turkey       | 10       | 0.55%   |
| Romania      | 10       | 0.55%   |
| Malaysia     | 10       | 0.55%   |
| Egypt        | 10       | 0.55%   |
| Japan        | 9        | 0.49%   |
| Bulgaria     | 9        | 0.49%   |
| Venezuela    | 8        | 0.44%   |
| Slovakia     | 8        | 0.44%   |
| Philippines  | 8        | 0.44%   |
| Ukraine      | 7        | 0.38%   |
| New Zealand  | 7        | 0.38%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Sao Paulo      | 15       | 0.79%   |
| Berlin         | 15       | 0.79%   |
| Athens         | 15       | 0.79%   |
| Rio de Janeiro | 14       | 0.73%   |
| Munich         | 12       | 0.63%   |
| Milan          | 10       | 0.52%   |
| Cape Town      | 10       | 0.52%   |
| Perth          | 9        | 0.47%   |
| Denver         | 9        | 0.47%   |
| Houston        | 8        | 0.42%   |
| Copenhagen     | 8        | 0.42%   |
| Buenos Aires   | 8        | 0.42%   |
| Bogotá        | 8        | 0.42%   |
| Zurich         | 7        | 0.37%   |
| Toronto        | 7        | 0.37%   |
| Rome           | 7        | 0.37%   |
| Phoenix        | 7        | 0.37%   |
| London         | 7        | 0.37%   |
| Budapest       | 7        | 0.37%   |
| Bengaluru      | 7        | 0.37%   |
| Belgrade       | 7        | 0.37%   |
| Adelaide       | 7        | 0.37%   |
| Warsaw         | 6        | 0.31%   |
| Vienna         | 6        | 0.31%   |
| Sydney         | 6        | 0.31%   |
| Santiago       | 6        | 0.31%   |
| Las Vegas      | 6        | 0.31%   |
| Johannesburg   | 6        | 0.31%   |
| Dayton         | 6        | 0.31%   |
| Dallas         | 6        | 0.31%   |
| Calgary        | 6        | 0.31%   |
| Brasília      | 6        | 0.31%   |
| Yogyakarta     | 5        | 0.26%   |
| The Hague      | 5        | 0.26%   |
| San José      | 5        | 0.26%   |
| Richmond       | 5        | 0.26%   |
| Portland       | 5        | 0.26%   |
| Montreal       | 5        | 0.26%   |
| Melbourne      | 5        | 0.26%   |
| Dortmund       | 5        | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 641      | 966    | 20.82%  |
| WDC                       | 565      | 809    | 18.35%  |
| Samsung Electronics       | 388      | 587    | 12.6%   |
| Kingston                  | 185      | 254    | 6.01%   |
| Toshiba                   | 159      | 241    | 5.16%   |
| SanDisk                   | 150      | 192    | 4.87%   |
| Hitachi                   | 141      | 176    | 4.58%   |
| Crucial                   | 102      | 126    | 3.31%   |
| Maxtor                    | 46       | 64     | 1.49%   |
| China                     | 41       | 45     | 1.33%   |
| A-DATA Technology         | 40       | 50     | 1.3%    |
| Intel                     | 36       | 43     | 1.17%   |
| Unknown                   | 32       | 55     | 1.04%   |
| Phison                    | 32       | 41     | 1.04%   |
| Silicon Motion            | 27       | 36     | 0.88%   |
| PNY                       | 25       | 32     | 0.81%   |
| Intenso                   | 23       | 27     | 0.75%   |
| HGST                      | 21       | 29     | 0.68%   |
| Patriot                   | 18       | 30     | 0.58%   |
| OCZ                       | 18       | 21     | 0.58%   |
| SPCC                      | 17       | 21     | 0.55%   |
| SK hynix                  | 16       | 21     | 0.52%   |
| Micron/Crucial Technology | 16       | 18     | 0.52%   |
| Micron Technology         | 13       | 14     | 0.42%   |
| JMicron Technology        | 13       | 18     | 0.42%   |
| GOODRAM                   | 12       | 15     | 0.39%   |
| Lexar                     | 11       | 11     | 0.36%   |
| Gigabyte Technology       | 11       | 19     | 0.36%   |
| Hewlett-Packard           | 10       | 14     | 0.32%   |
| Corsair                   | 10       | 16     | 0.32%   |
| Phison Electronics        | 9        | 11     | 0.29%   |
| KingSpec                  | 9        | 11     | 0.29%   |
| Apple                     | 9        | 10     | 0.29%   |
| Realtek Semiconductor     | 8        | 8      | 0.26%   |
| Apacer                    | 8        | 10     | 0.26%   |
| XPG                       | 7        | 9      | 0.23%   |
| Transcend                 | 7        | 8      | 0.23%   |
| Leven                     | 7        | 8      | 0.23%   |
| HS-SSD-C100               | 7        | 7      | 0.23%   |
| Unknown                   | 7        | 8      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB                     | 60       | 1.72%   |
| Kingston SA400S37240G 240GB SSD                     | 49       | 1.4%    |
| Seagate ST1000DM010-2EP102 1TB                      | 40       | 1.15%   |
| Seagate ST3500418AS 500GB                           | 30       | 0.86%   |
| Samsung SSD 860 EVO 500GB                           | 29       | 0.83%   |
| Crucial CT240BX500SSD1 240GB                        | 26       | 0.74%   |
| Toshiba DT01ACA100 1TB                              | 25       | 0.72%   |
| Kingston SA400S37120G 120GB SSD                     | 25       | 0.72%   |
| Seagate ST1000DM003-1CH162 1TB                      | 24       | 0.69%   |
| Kingston SA400S37480G 480GB SSD                     | 24       | 0.69%   |
| Samsung SSD 850 EVO 250GB                           | 23       | 0.66%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 22       | 0.63%   |
| Toshiba HDWD110 1TB                                 | 22       | 0.63%   |
| Seagate ST1000DM003-1ER162 1TB                      | 22       | 0.63%   |
| Samsung NVMe SSD Drive 1TB                          | 21       | 0.6%    |
| Samsung NVMe SSD Drive 500GB                        | 20       | 0.57%   |
| Kingston SV300S37A120G 120GB SSD                    | 19       | 0.54%   |
| Seagate ST2000DM008-2FR102 2TB                      | 17       | 0.49%   |
| Seagate ST2000DM001-1ER164 2TB                      | 17       | 0.49%   |
| Samsung SSD 850 EVO 500GB                           | 17       | 0.49%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 17       | 0.49%   |
| Crucial CT500MX500SSD1 500GB                        | 16       | 0.46%   |
| Toshiba DT01ACA050 500GB                            | 15       | 0.43%   |
| Seagate ST3500413AS 500GB                           | 15       | 0.43%   |
| SanDisk NVMe SSD Drive 500GB                        | 15       | 0.43%   |
| Unknown SD/MMC/MS PRO 128GB                         | 14       | 0.4%    |
| Seagate ST31000528AS 1TB                            | 14       | 0.4%    |
| Seagate ST1000DM003-1SB102 1TB                      | 14       | 0.4%    |
| Seagate ST3500312CS 500GB                           | 13       | 0.37%   |
| Samsung SSD 840 EVO 250GB                           | 13       | 0.37%   |
| Crucial CT1000MX500SSD1 1TB                         | 13       | 0.37%   |
| Seagate ST4000DM004-2CV104 4TB                      | 12       | 0.34%   |
| Seagate ST3250310AS 250GB                           | 12       | 0.34%   |
| Seagate ST2000DM001-1CH164 2TB                      | 12       | 0.34%   |
| SanDisk NVMe SSD Drive 1TB                          | 12       | 0.34%   |
| Samsung HD103SJ 1TB                                 | 12       | 0.34%   |
| Toshiba DT01ACA200 2TB                              | 11       | 0.32%   |
| Seagate ST4000DM000-1F2168 4TB                      | 11       | 0.32%   |
| Seagate ST31000524AS 1TB                            | 11       | 0.32%   |
| SanDisk SSD PLUS 240GB                              | 11       | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 632      | 944    | 37.87%  |
| WDC                 | 523      | 739    | 31.34%  |
| Toshiba             | 141      | 220    | 8.45%   |
| Hitachi             | 141      | 176    | 8.45%   |
| Samsung Electronics | 117      | 157    | 7.01%   |
| Maxtor              | 45       | 63     | 2.7%    |
| HGST                | 21       | 29     | 1.26%   |
| Unknown             | 14       | 19     | 0.84%   |
| JMicron Technology  | 10       | 14     | 0.6%    |
| Apple               | 6        | 7      | 0.36%   |
| USB3.0              | 3        | 4      | 0.18%   |
| Super Talent        | 3        | 4      | 0.18%   |
| Hewlett-Packard     | 3        | 6      | 0.18%   |
| Quantum             | 2        | 2      | 0.12%   |
| External            | 2        | 2      | 0.12%   |
| Intenso             | 1        | 1      | 0.06%   |
| Fujitsu             | 1        | 1      | 0.06%   |
| ExcelStor           | 1        | 1      | 0.06%   |
| ASMT109x            | 1        | 2      | 0.06%   |
| ASMT                | 1        | 1      | 0.06%   |
| ACASIS              | 1        | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 197      | 281    | 19.45%  |
| Kingston            | 162      | 213    | 15.99%  |
| SanDisk             | 99       | 123    | 9.77%   |
| Crucial             | 98       | 122    | 9.67%   |
| WDC                 | 50       | 61     | 4.94%   |
| China               | 40       | 44     | 3.95%   |
| A-DATA Technology   | 38       | 48     | 3.75%   |
| PNY                 | 25       | 32     | 2.47%   |
| Intel               | 25       | 30     | 2.47%   |
| Intenso             | 18       | 22     | 1.78%   |
| Patriot             | 17       | 29     | 1.68%   |
| OCZ                 | 17       | 20     | 1.68%   |
| SPCC                | 16       | 20     | 1.58%   |
| Toshiba             | 13       | 15     | 1.28%   |
| Lexar               | 11       | 11     | 1.09%   |
| GOODRAM             | 11       | 14     | 1.09%   |
| Micron Technology   | 10       | 11     | 0.99%   |
| Gigabyte Technology | 9        | 16     | 0.89%   |
| KingSpec            | 8        | 10     | 0.79%   |
| Corsair             | 8        | 14     | 0.79%   |
| Apacer              | 8        | 10     | 0.79%   |
| Transcend           | 7        | 8      | 0.69%   |
| SK hynix            | 7        | 7      | 0.69%   |
| Leven               | 7        | 8      | 0.69%   |
| Hewlett-Packard     | 7        | 8      | 0.69%   |
| Team                | 6        | 8      | 0.59%   |
| Netac               | 6        | 8      | 0.59%   |
| LITEON              | 5        | 6      | 0.49%   |
| Unknown             | 4        | 5      | 0.39%   |
| Verbatim            | 3        | 3      | 0.3%    |
| Seagate             | 3        | 6      | 0.3%    |
| Plextor             | 3        | 4      | 0.3%    |
| Pioneer             | 3        | 3      | 0.3%    |
| KIOXIA-EXCERIA      | 3        | 7      | 0.3%    |
| Drevo               | 3        | 4      | 0.3%    |
| Acer                | 3        | 5      | 0.3%    |
| Zheino              | 2        | 2      | 0.2%    |
| TCSUNBOW            | 2        | 2      | 0.2%    |
| OWC                 | 2        | 2      | 0.2%    |
| NN                  | 2        | 3      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1307     | 2393   | 50.33%  |
| SSD     | 858      | 1312   | 33.04%  |
| NVMe    | 345      | 489    | 13.28%  |
| Unknown | 79       | 103    | 3.04%   |
| MMC     | 8        | 9      | 0.31%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 1716     | 3636   | 78.39%  |
| NVMe | 340      | 482    | 15.53%  |
| SAS  | 125      | 179    | 5.71%   |
| MMC  | 8        | 9      | 0.37%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1323     | 2181   | 57.67%  |
| 0.51-1.0   | 604      | 925    | 26.33%  |
| 1.01-2.0   | 212      | 309    | 9.24%   |
| 3.01-4.0   | 60       | 136    | 2.62%   |
| 4.01-10.0  | 52       | 76     | 2.27%   |
| 2.01-3.0   | 38       | 58     | 1.66%   |
| 10.01-20.0 | 5        | 20     | 0.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 571      | 29.83%  |
| 251-500        | 424      | 22.15%  |
| 501-1000       | 283      | 14.79%  |
| 1001-2000      | 170      | 8.88%   |
| 51-100         | 144      | 7.52%   |
| More than 3000 | 114      | 5.96%   |
| 21-50          | 75       | 3.92%   |
| 2001-3000      | 61       | 3.19%   |
| 1-20           | 54       | 2.82%   |
| Unknown        | 18       | 0.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 819      | 41.11%  |
| 21-50          | 426      | 21.39%  |
| 51-100         | 223      | 11.19%  |
| 101-250        | 181      | 9.09%   |
| 251-500        | 116      | 5.82%   |
| 501-1000       | 88       | 4.42%   |
| 1001-2000      | 56       | 2.81%   |
| More than 3000 | 48       | 2.41%   |
| Unknown        | 18       | 0.9%    |
| 2001-3000      | 17       | 0.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| HGST HTS541010A9E680 1TB                 | 2        | 2      | 4.76%   |
| WDC WD5000LPCX-60VHAT0 500GB             | 1        | 1      | 2.38%   |
| WDC WD5000AAKS-00V1A0 500GB              | 1        | 1      | 2.38%   |
| WDC WD3200AAKS-22B3A0 320GB              | 1        | 1      | 2.38%   |
| WDC WD30EFRX-68EUZN0 3TB                 | 1        | 1      | 2.38%   |
| WDC WD10EZEX-21M2NA0 1TB                 | 1        | 2      | 2.38%   |
| WDC WD10EURX-63FH1Y0 1TB                 | 1        | 1      | 2.38%   |
| WDC WD Green 2.5 1000GB                  | 1        | 1      | 2.38%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1        | 1      | 2.38%   |
| Toshiba MQ01ABD100 1TB                   | 1        | 1      | 2.38%   |
| Toshiba MK8046GSX 80GB                   | 1        | 1      | 2.38%   |
| Toshiba MK3265GSX 320GB                  | 1        | 1      | 2.38%   |
| Toshiba MG03ACA200 2TB                   | 1        | 1      | 2.38%   |
| Toshiba DT01ACA100 1TB                   | 1        | 1      | 2.38%   |
| Silicon Motion Inland NVMe SSD 256GB     | 1        | 1      | 2.38%   |
| Seagate ST9500420AS 500GB                | 1        | 1      | 2.38%   |
| Seagate ST8000DM004-2CX188 8TB           | 1        | 1      | 2.38%   |
| Seagate ST500DM002-1BD142 500GB          | 1        | 1      | 2.38%   |
| Seagate ST4000DM004-2CV104 4TB           | 1        | 1      | 2.38%   |
| Seagate ST3500514NS 500GB                | 1        | 1      | 2.38%   |
| Seagate ST3500413AS 500GB                | 1        | 1      | 2.38%   |
| Seagate ST3500312CS 500GB                | 1        | 1      | 2.38%   |
| Seagate ST3360320AS 360GB                | 1        | 1      | 2.38%   |
| Seagate ST3320620AS 320GB                | 1        | 1      | 2.38%   |
| Seagate ST3250318AS 250GB                | 1        | 1      | 2.38%   |
| Seagate ST320LT012-1DG14C 320GB          | 1        | 1      | 2.38%   |
| Seagate ST3160310CS 160GB                | 1        | 1      | 2.38%   |
| Seagate ST2000LM003 HN-M201RAD 2TB       | 1        | 1      | 2.38%   |
| Seagate ST2000DX002-2DV164 2TB           | 1        | 1      | 2.38%   |
| Seagate ST2000DM008-2FR102 2TB           | 1        | 1      | 2.38%   |
| Seagate ST2000DM001-9YN164 2TB           | 1        | 1      | 2.38%   |
| Seagate ST2000DL003-9VT166 2TB           | 1        | 1      | 2.38%   |
| Seagate ST1000DM003-1ER162 1TB           | 1        | 1      | 2.38%   |
| Samsung Electronics HD154UI 1TB          | 1        | 1      | 2.38%   |
| OCZ VERTEX3 120GB SSD                    | 1        | 1      | 2.38%   |
| Maxtor STM3320613AS 320GB                | 1        | 1      | 2.38%   |
| Kingston SV300S37A120G 120GB SSD         | 1        | 1      | 2.38%   |
| Kingston SNS4151S316GD 16GB SSD          | 1        | 1      | 2.38%   |
| Intel SSDSC2CW060A3 64GB                 | 1        | 1      | 2.38%   |
| A-DATA Technology SX8200PNP 256GB        | 1        | 1      | 2.38%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 17       | 18     | 41.46%  |
| WDC                 | 7        | 8      | 17.07%  |
| Toshiba             | 6        | 6      | 14.63%  |
| Kingston            | 2        | 2      | 4.88%   |
| HGST                | 2        | 2      | 4.88%   |
| A-DATA Technology   | 2        | 2      | 4.88%   |
| Silicon Motion      | 1        | 1      | 2.44%   |
| Samsung Electronics | 1        | 1      | 2.44%   |
| OCZ                 | 1        | 1      | 2.44%   |
| Maxtor              | 1        | 1      | 2.44%   |
| Intel               | 1        | 1      | 2.44%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 17       | 18     | 53.13%  |
| WDC                 | 6        | 7      | 18.75%  |
| Toshiba             | 5        | 5      | 15.63%  |
| HGST                | 2        | 2      | 6.25%   |
| Samsung Electronics | 1        | 1      | 3.13%   |
| Maxtor              | 1        | 1      | 3.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 28       | 34     | 75.68%  |
| SSD  | 7        | 7      | 18.92%  |
| NVMe | 2        | 2      | 5.41%   |

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
| Detected | 1723     | 3966   | 91.75%  |
| Works    | 118      | 297    | 6.28%   |
| Malfunc  | 37       | 43     | 1.97%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1175     | 49.35%  |
| AMD                              | 534      | 22.43%  |
| Samsung Electronics              | 111      | 4.66%   |
| Nvidia                           | 90       | 3.78%   |
| SanDisk                          | 61       | 2.56%   |
| ASMedia Technology               | 61       | 2.56%   |
| JMicron Technology               | 58       | 2.44%   |
| Phison Electronics               | 44       | 1.85%   |
| Marvell Technology Group         | 42       | 1.76%   |
| Kingston Technology Company      | 32       | 1.34%   |
| Silicon Motion                   | 29       | 1.22%   |
| VIA Technologies                 | 26       | 1.09%   |
| Micron/Crucial Technology        | 20       | 0.84%   |
| Silicon Image                    | 12       | 0.5%    |
| ADATA Technology                 | 12       | 0.5%    |
| SK hynix                         | 8        | 0.34%   |
| Realtek Semiconductor            | 8        | 0.34%   |
| Seagate Technology               | 7        | 0.29%   |
| Silicon Integrated Systems [SiS] | 6        | 0.25%   |
| MAXIO Technology (Hangzhou)      | 6        | 0.25%   |
| Broadcom / LSI                   | 6        | 0.25%   |
| KIOXIA                           | 5        | 0.21%   |
| Toshiba America Info Systems     | 4        | 0.17%   |
| Micron Technology                | 3        | 0.13%   |
| OCZ Technology Group             | 2        | 0.08%   |
| Integrated Technology Express    | 2        | 0.08%   |
| INNOGRIT                         | 2        | 0.08%   |
| Apple                            | 2        | 0.08%   |
| Union Memory (Shenzhen)          | 1        | 0.04%   |
| TenaFe                           | 1        | 0.04%   |
| Solid State Storage Technology   | 1        | 0.04%   |
| Shenzhen Longsys Electronics     | 1        | 0.04%   |
| Promise Technology               | 1        | 0.04%   |
| Netac Technology                 | 1        | 0.04%   |
| LSI Logic / Symbios Logic        | 1        | 0.04%   |
| Lite-On Technology               | 1        | 0.04%   |
| Lite-On IT Corp. / Plextor       | 1        | 0.04%   |
| HighPoint Technologies           | 1        | 0.04%   |
| Hewlett-Packard                  | 1        | 0.04%   |
| Beijing Starblaze Technology     | 1        | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 274      | 8.68%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 153      | 4.85%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 152      | 4.82%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 125      | 3.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 111      | 3.52%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 109      | 3.45%   |
| AMD 400 Series Chipset SATA Controller                                                  | 94       | 2.98%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 85       | 2.69%   |
| Intel SATA Controller [RAID mode]                                                       | 79       | 2.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 76       | 2.41%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 71       | 2.25%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 63       | 2%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 55       | 1.74%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 55       | 1.74%   |
| Nvidia MCP61 SATA Controller                                                            | 49       | 1.55%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 46       | 1.46%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 46       | 1.46%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 45       | 1.43%   |
| AMD 500 Series Chipset SATA Controller                                                  | 44       | 1.39%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 36       | 1.14%   |
| Nvidia MCP61 IDE                                                                        | 33       | 1.05%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 33       | 1.05%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 30       | 0.95%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 29       | 0.92%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 27       | 0.86%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 27       | 0.86%   |
| AMD FCH SATA Controller D                                                               | 27       | 0.86%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 25       | 0.79%   |
| AMD 300 Series Chipset SATA Controller                                                  | 25       | 0.79%   |
| Phison E12 NVMe Controller                                                              | 24       | 0.76%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 23       | 0.73%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 22       | 0.7%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 22       | 0.7%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 22       | 0.7%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 22       | 0.7%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 21       | 0.67%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 21       | 0.67%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 20       | 0.63%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 19       | 0.6%    |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 18       | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1304     | 53.12%  |
| IDE  | 660      | 26.88%  |
| NVMe | 339      | 13.81%  |
| RAID | 138      | 5.62%   |
| SAS  | 8        | 0.33%   |
| SCSI | 6        | 0.24%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 1213     | 66.32%  |
| AMD    | 616      | 33.68%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-2400 CPU @ 3.10GHz            | 36       | 1.96%   |
| AMD Ryzen 5 3600 6-Core Processor           | 31       | 1.69%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 27       | 1.47%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 23       | 1.25%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 22       | 1.2%    |
| Intel Pentium 4 CPU 3.00GHz                 | 18       | 0.98%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 17       | 0.93%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 17       | 0.93%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 16       | 0.87%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 16       | 0.87%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 15       | 0.82%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 15       | 0.82%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 15       | 0.82%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 15       | 0.82%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 14       | 0.76%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 14       | 0.76%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 14       | 0.76%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 14       | 0.76%   |
| AMD FX-6300 Six-Core Processor              | 14       | 0.76%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 13       | 0.71%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 13       | 0.71%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 13       | 0.71%   |
| AMD FX-8350 Eight-Core Processor            | 13       | 0.71%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 12       | 0.65%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 12       | 0.65%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 12       | 0.65%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 12       | 0.65%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 12       | 0.65%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 11       | 0.6%    |
| Intel Pentium Dual CPU E2140 @ 1.60GHz      | 11       | 0.6%    |
| Intel Core i5-4570 CPU @ 3.20GHz            | 11       | 0.6%    |
| AMD Ryzen 7 3700X 8-Core Processor          | 11       | 0.6%    |
| AMD Ryzen 5 5600G with Radeon Graphics      | 11       | 0.6%    |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 10       | 0.54%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 10       | 0.54%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 10       | 0.54%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 10       | 0.54%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 10       | 0.54%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 10       | 0.54%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 9        | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 318      | 17.34%  |
| Intel Core i7           | 179      | 9.76%   |
| Intel Core i3           | 143      | 7.8%    |
| AMD Ryzen 5             | 122      | 6.65%   |
| Intel Xeon              | 88       | 4.8%    |
| Intel Core 2 Duo        | 87       | 4.74%   |
| AMD FX                  | 73       | 3.98%   |
| AMD Ryzen 7             | 68       | 3.71%   |
| Intel Core 2 Quad       | 63       | 3.44%   |
| Intel Celeron           | 59       | 3.22%   |
| Intel Pentium Dual-Core | 53       | 2.89%   |
| Intel Pentium Dual      | 44       | 2.4%    |
| Intel Pentium           | 42       | 2.29%   |
| Other                   | 39       | 2.13%   |
| Intel Pentium 4         | 39       | 2.13%   |
| AMD Ryzen 9             | 38       | 2.07%   |
| AMD Athlon II X2        | 38       | 2.07%   |
| AMD Athlon 64 X2        | 33       | 1.8%    |
| AMD Ryzen 3             | 31       | 1.69%   |
| AMD Phenom II X4        | 23       | 1.25%   |
| AMD A8                  | 22       | 1.2%    |
| Intel Core 2            | 19       | 1.04%   |
| AMD A10                 | 17       | 0.93%   |
| AMD A4                  | 16       | 0.87%   |
| AMD Athlon              | 15       | 0.82%   |
| AMD A6                  | 15       | 0.82%   |
| Intel Core i9           | 14       | 0.76%   |
| AMD Sempron             | 14       | 0.76%   |
| AMD Phenom II X6        | 12       | 0.65%   |
| AMD Athlon II X4        | 12       | 0.65%   |
| Intel Pentium D         | 10       | 0.55%   |
| Intel Atom              | 9        | 0.49%   |
| AMD Athlon II X3        | 9        | 0.49%   |
| AMD Athlon 64           | 7        | 0.38%   |
| Intel Pentium Gold      | 6        | 0.33%   |
| AMD Phenom              | 6        | 0.33%   |
| AMD Phenom II X2        | 4        | 0.22%   |
| AMD E1                  | 4        | 0.22%   |
| AMD E                   | 4        | 0.22%   |
| AMD Athlon Dual Core    | 4        | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 700      | 38.13%  |
| 2      | 612      | 33.33%  |
| 6      | 199      | 10.84%  |
| 8      | 124      | 6.75%   |
| 1      | 102      | 5.56%   |
| 3      | 35       | 1.91%   |
| 12     | 29       | 1.58%   |
| 16     | 18       | 0.98%   |
| 10     | 13       | 0.71%   |
| 14     | 2        | 0.11%   |
| 28     | 1        | 0.05%   |
| 20     | 1        | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 1815     | 99.23%  |
| 2      | 14       | 0.77%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 969      | 52.95%  |
| 2      | 861      | 47.05%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 1800     | 98.41%  |
| 32-bit         | 28       | 1.53%   |
| Unknown        | 1        | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 182      | 9.77%   |
| Unknown    | 177      | 9.51%   |
| 0x1067a    | 143      | 7.68%   |
| 0x206a7    | 135      | 7.25%   |
| 0x306a9    | 113      | 6.07%   |
| 0x506e3    | 65       | 3.49%   |
| 0x6fd      | 54       | 2.9%    |
| 0x06000852 | 54       | 2.9%    |
| 0x08701021 | 52       | 2.79%   |
| 0x010000c8 | 44       | 2.36%   |
| 0x906ea    | 32       | 1.72%   |
| 0x6fb      | 32       | 1.72%   |
| 0x906e9    | 30       | 1.61%   |
| 0x0800820d | 30       | 1.61%   |
| 0x06001119 | 30       | 1.61%   |
| 0xa0653    | 22       | 1.18%   |
| 0xa0655    | 21       | 1.13%   |
| 0x20655    | 19       | 1.02%   |
| 0x10676    | 19       | 1.02%   |
| 0x010000db | 19       | 1.02%   |
| 0x0a201016 | 18       | 0.97%   |
| 0x0600063e | 18       | 0.97%   |
| 0x106e5    | 17       | 0.91%   |
| 0x08108109 | 17       | 0.91%   |
| 0x906ed    | 16       | 0.86%   |
| 0x08001138 | 16       | 0.86%   |
| 0xa0671    | 14       | 0.75%   |
| 0x906eb    | 14       | 0.75%   |
| 0x106a5    | 14       | 0.75%   |
| 0x06003106 | 14       | 0.75%   |
| 0x010000dc | 14       | 0.75%   |
| 0x6f6      | 13       | 0.7%    |
| 0x20652    | 13       | 0.7%    |
| 0x08701013 | 13       | 0.7%    |
| 0x206d7    | 12       | 0.64%   |
| 0xf43      | 11       | 0.59%   |
| 0x306f2    | 11       | 0.59%   |
| 0x03000027 | 11       | 0.59%   |
| 0xf41      | 10       | 0.54%   |
| 0x206c2    | 10       | 0.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 208      | 11.35%  |
| Penryn           | 173      | 9.44%   |
| SandyBridge      | 152      | 8.3%    |
| IvyBridge        | 125      | 6.82%   |
| Core             | 117      | 6.39%   |
| K10              | 110      | 6%      |
| KabyLake         | 104      | 5.68%   |
| Piledriver       | 88       | 4.8%    |
| Zen 2            | 83       | 4.53%   |
| Skylake          | 70       | 3.82%   |
| Zen 3            | 63       | 3.44%   |
| K8 Hammer        | 59       | 3.22%   |
| Zen+             | 58       | 3.17%   |
| Zen              | 57       | 3.11%   |
| NetBurst         | 57       | 3.11%   |
| CometLake        | 46       | 2.51%   |
| Westmere         | 43       | 2.35%   |
| Nehalem          | 37       | 2.02%   |
| Unknown          | 26       | 1.42%   |
| Silvermont       | 21       | 1.15%   |
| Bulldozer        | 18       | 0.98%   |
| Steamroller      | 14       | 0.76%   |
| Excavator        | 14       | 0.76%   |
| Alderlake Hybrid | 12       | 0.66%   |
| K10 Llano        | 11       | 0.6%    |
| Jaguar           | 11       | 0.6%    |
| Icelake          | 11       | 0.6%    |
| Bobcat           | 8        | 0.44%   |
| Puma             | 7        | 0.38%   |
| Broadwell        | 7        | 0.38%   |
| Bonnell          | 7        | 0.38%   |
| Goldmont plus    | 6        | 0.33%   |
| K6               | 3        | 0.16%   |
| Tremont          | 2        | 0.11%   |
| Goldmont         | 2        | 0.11%   |
| TigerLake        | 1        | 0.05%   |
| P6               | 1        | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Nvidia                           | 718      | 36.97%  |
| Intel                            | 618      | 31.82%  |
| AMD                              | 592      | 30.48%  |
| VIA Technologies                 | 8        | 0.41%   |
| Silicon Integrated Systems [SiS] | 2        | 0.1%    |
| Trident Microsystems             | 1        | 0.05%   |
| Silicon Motion                   | 1        | 0.05%   |
| Matrox Electronics Systems       | 1        | 0.05%   |
| ASPEED Technology                | 1        | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 98       | 4.92%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 76       | 3.82%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 64       | 3.21%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 64       | 3.21%   |
| Nvidia GK208B [GeForce GT 710]                                              | 53       | 2.66%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 49       | 2.46%   |
| Intel HD Graphics 530                                                       | 35       | 1.76%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 35       | 1.76%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 33       | 1.66%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 33       | 1.66%   |
| Nvidia GK208B [GeForce GT 730]                                              | 28       | 1.41%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 26       | 1.31%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 25       | 1.26%   |
| Nvidia GT218 [GeForce 210]                                                  | 24       | 1.2%    |
| AMD RS780L [Radeon 3000]                                                    | 23       | 1.15%   |
| Intel Core Processor Integrated Graphics Controller                         | 22       | 1.1%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 22       | 1.1%    |
| Intel HD Graphics 630                                                       | 20       | 1%      |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 20       | 1%      |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 20       | 1%      |
| Nvidia GF119 [GeForce GT 610]                                               | 19       | 0.95%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 18       | 0.9%    |
| Nvidia GF108 [GeForce GT 730]                                               | 16       | 0.8%    |
| Intel 82945G/GZ Integrated Graphics Controller                              | 16       | 0.8%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 15       | 0.75%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 15       | 0.75%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 15       | 0.75%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 14       | 0.7%    |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 14       | 0.7%    |
| Intel 82Q35 Express Integrated Graphics Controller                          | 14       | 0.7%    |
| Nvidia TU117 [GeForce GTX 1650]                                             | 13       | 0.65%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 13       | 0.65%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 13       | 0.65%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 12       | 0.6%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 12       | 0.6%    |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 12       | 0.6%    |
| Nvidia GF108 [GeForce GT 630]                                               | 11       | 0.55%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 11       | 0.55%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 11       | 0.55%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 11       | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 671      | 36.37%  |
| 1 x Intel                | 548      | 29.7%   |
| 1 x AMD                  | 531      | 28.78%  |
| 2 x AMD                  | 31       | 1.68%   |
| Intel + Nvidia           | 18       | 0.98%   |
| Intel + AMD              | 14       | 0.76%   |
| AMD + Nvidia             | 13       | 0.7%    |
| 1 x VIA                  | 8        | 0.43%   |
| 2 x Nvidia               | 4        | 0.22%   |
| 1 x SiS                  | 2        | 0.11%   |
| 2 x AMD + 1 x Nvidia     | 1        | 0.05%   |
| 1 x Trident Microsystems | 1        | 0.05%   |
| Nvidia + Silicon Motion  | 1        | 0.05%   |
| 1 x Matrox               | 1        | 0.05%   |
| 1 x ASPEED               | 1        | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1298     | 70.05%  |
| Proprietary | 423      | 22.83%  |
| Unknown     | 132      | 7.12%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 775      | 41.27%  |
| 0.01-0.5   | 271      | 14.43%  |
| 1.01-2.0   | 247      | 13.15%  |
| 0.51-1.0   | 239      | 12.73%  |
| 3.01-4.0   | 132      | 7.03%   |
| 7.01-8.0   | 114      | 6.07%   |
| 5.01-6.0   | 39       | 2.08%   |
| 8.01-16.0  | 37       | 1.97%   |
| 2.01-3.0   | 19       | 1.01%   |
| 16.01-24.0 | 4        | 0.21%   |
| 4.01-5.0   | 1        | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 267      | 15.14%  |
| Dell                 | 176      | 9.98%   |
| Goldstar             | 171      | 9.69%   |
| Hewlett-Packard      | 144      | 8.16%   |
| Acer                 | 122      | 6.92%   |
| AOC                  | 98       | 5.56%   |
| Philips              | 80       | 4.54%   |
| Ancor Communications | 71       | 4.02%   |
| BenQ                 | 66       | 3.74%   |
| LG Electronics       | 43       | 2.44%   |
| ViewSonic            | 38       | 2.15%   |
| Unknown              | 33       | 1.87%   |
| Lenovo               | 21       | 1.19%   |
| Sony                 | 19       | 1.08%   |
| Unknown              | 19       | 1.08%   |
| Iiyama               | 18       | 1.02%   |
| Fujitsu Siemens      | 16       | 0.91%   |
| Vizio                | 15       | 0.85%   |
| NEC Computers        | 15       | 0.85%   |
| ASUSTek Computer     | 15       | 0.85%   |
| Sceptre Tech         | 14       | 0.79%   |
| Eizo                 | 13       | 0.74%   |
| Toshiba              | 12       | 0.68%   |
| MSI                  | 10       | 0.57%   |
| HPN                  | 10       | 0.57%   |
| HannStar             | 8        | 0.45%   |
| Gateway              | 8        | 0.45%   |
| Idek Iiyama          | 7        | 0.4%    |
| FUS                  | 7        | 0.4%    |
| Envision             | 7        | 0.4%    |
| AUS                  | 7        | 0.4%    |
| Sharp                | 6        | 0.34%   |
| Microstep            | 6        | 0.34%   |
| Medion               | 6        | 0.34%   |
| Panasonic            | 5        | 0.28%   |
| KTC                  | 5        | 0.28%   |
| CVT                  | 5        | 0.28%   |
| ___                  | 4        | 0.23%   |
| VIZ                  | 4        | 0.23%   |
| Vestel               | 4        | 0.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown                                                               | 19       | 1.02%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 9        | 0.48%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 7        | 0.38%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                      | 7        | 0.38%   |
| Hewlett-Packard 2009 HWP2827 1600x900 443x250mm 20.0-inch             | 6        | 0.32%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 6        | 0.32%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                 | 5        | 0.27%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 5        | 0.27%   |
| Philips LCD Monitor FTV 1920x1080                                     | 5        | 0.27%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 5        | 0.27%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 4        | 0.21%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 700x390mm 31.5-inch | 4        | 0.21%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 4        | 0.21%   |
| Philips PHL 242M8 PHLC253 1920x1080 527x296mm 23.8-inch               | 4        | 0.21%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 4        | 0.21%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                   | 4        | 0.21%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch             | 4        | 0.21%   |
| Dell SE198WFP DELF003 1440x900 408x255mm 18.9-inch                    | 4        | 0.21%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                    | 4        | 0.21%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch      | 4        | 0.21%   |
| Vizio E221VA VIZ0070 1920x1080 476x268mm 21.5-inch                    | 3        | 0.16%   |
| Vestel LCD Monitor 48UHD_LCD_TV 3840x2160                             | 3        | 0.16%   |
| Unknown LCD Monitor SAMSUNG                                           | 3        | 0.16%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch        | 3        | 0.16%   |
| Toshiba TV TSB0206 1920x1080 1600x1000mm 74.3-inch                    | 3        | 0.16%   |
| Samsung Electronics U28D590 SAM0B81 3840x2160 608x345mm 27.5-inch     | 3        | 0.16%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch  | 3        | 0.16%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch     | 3        | 0.16%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1080                  | 3        | 0.16%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 3        | 0.16%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 950x540mm 43.0-inch | 3        | 0.16%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch  | 3        | 0.16%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 480x270mm 21.7-inch | 3        | 0.16%   |
| Samsung Electronics LCD Monitor SAM07BC 1360x768 700x390mm 31.5-inch  | 3        | 0.16%   |
| Philips PHL 277E6 PHLC0E6 1920x1080 598x336mm 27.0-inch               | 3        | 0.16%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 3        | 0.16%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                    | 3        | 0.16%   |
| OEM 32W_LCD_TV OEM3700 1920x540                                       | 3        | 0.16%   |
| MSI Optix G241VC MSI1462 1920x1080 521x294mm 23.6-inch                | 3        | 0.16%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                     | 3        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 705      | 40.35%  |
| 1280x1024 (SXGA)   | 138      | 7.9%    |
| 3840x2160 (4K)     | 124      | 7.1%    |
| 1680x1050 (WSXGA+) | 105      | 6.01%   |
| 1366x768 (WXGA)    | 90       | 5.15%   |
| 1600x900 (HD+)     | 87       | 4.98%   |
| 1440x900 (WXGA+)   | 77       | 4.41%   |
| Unknown            | 70       | 4.01%   |
| 2560x1440 (QHD)    | 68       | 3.89%   |
| 1360x768           | 52       | 2.98%   |
| 1920x1200 (WUXGA)  | 38       | 2.18%   |
| 3440x1440          | 32       | 1.83%   |
| 3840x1080          | 29       | 1.66%   |
| 1920x540           | 17       | 0.97%   |
| 1024x768 (XGA)     | 17       | 0.97%   |
| 2560x1080          | 16       | 0.92%   |
| 1600x1200          | 8        | 0.46%   |
| 5760x1080          | 6        | 0.34%   |
| 1280x720 (HD)      | 5        | 0.29%   |
| 4480x1440          | 4        | 0.23%   |
| 3840x1600          | 4        | 0.23%   |
| 5760x2160          | 3        | 0.17%   |
| 3600x1080          | 3        | 0.17%   |
| 2560x1600          | 3        | 0.17%   |
| 1152x864           | 3        | 0.17%   |
| 6400x1440          | 2        | 0.11%   |
| 5440x1080          | 2        | 0.11%   |
| 5120x1440          | 2        | 0.11%   |
| 4480x1080          | 2        | 0.11%   |
| 3360x1080          | 2        | 0.11%   |
| 3200x1200          | 2        | 0.11%   |
| 3200x1080          | 2        | 0.11%   |
| 3120x1050          | 2        | 0.11%   |
| 2944x1080          | 2        | 0.11%   |
| 2720x1024          | 2        | 0.11%   |
| 2048x1152          | 2        | 0.11%   |
| 1280x960           | 2        | 0.11%   |
| 7680x1080          | 1        | 0.06%   |
| 6400x1080          | 1        | 0.06%   |
| 5040x1050          | 1        | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 336      | 19.42%  |
| 24      | 155      | 8.96%   |
| 23      | 148      | 8.55%   |
| 27      | 147      | 8.5%    |
| 21      | 146      | 8.44%   |
| 19      | 137      | 7.92%   |
| 18      | 96       | 5.55%   |
| 20      | 94       | 5.43%   |
| 22      | 73       | 4.22%   |
| 31      | 71       | 4.1%    |
| 17      | 63       | 3.64%   |
| 34      | 32       | 1.85%   |
| 15      | 32       | 1.85%   |
| 40      | 24       | 1.39%   |
| 84      | 19       | 1.1%    |
| 72      | 16       | 0.92%   |
| 54      | 16       | 0.92%   |
| 32      | 16       | 0.92%   |
| 26      | 15       | 0.87%   |
| 65      | 7        | 0.4%    |
| 52      | 7        | 0.4%    |
| 36      | 7        | 0.4%    |
| 42      | 6        | 0.35%   |
| 28      | 6        | 0.35%   |
| 25      | 6        | 0.35%   |
| 49      | 4        | 0.23%   |
| 47      | 4        | 0.23%   |
| 35      | 4        | 0.23%   |
| 33      | 4        | 0.23%   |
| 74      | 3        | 0.17%   |
| 48      | 3        | 0.17%   |
| 46      | 3        | 0.17%   |
| 39      | 3        | 0.17%   |
| 37      | 3        | 0.17%   |
| 29      | 3        | 0.17%   |
| 60      | 2        | 0.12%   |
| 57      | 2        | 0.12%   |
| 41      | 2        | 0.12%   |
| 30      | 2        | 0.12%   |
| 16      | 2        | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 465      | 27.63%  |
| 501-600     | 422      | 25.07%  |
| Unknown     | 336      | 19.96%  |
| 601-700     | 95       | 5.64%   |
| 301-350     | 93       | 5.53%   |
| 351-400     | 76       | 4.52%   |
| 701-800     | 59       | 3.51%   |
| 1001-1500   | 50       | 2.97%   |
| 1501-2000   | 41       | 2.44%   |
| 801-900     | 34       | 2.02%   |
| 901-1000    | 10       | 0.59%   |
| 201-300     | 2        | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 890      | 54.8%   |
| Unknown | 307      | 18.9%   |
| 16/10   | 210      | 12.93%  |
| 5/4     | 122      | 7.51%   |
| 21/9    | 41       | 2.52%   |
| 4/3     | 32       | 1.97%   |
| 32/9    | 10       | 0.62%   |
| 6/5     | 7        | 0.43%   |
| 3/2     | 5        | 0.31%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 415      | 24.37%  |
| Unknown        | 336      | 19.73%  |
| 151-200        | 288      | 16.91%  |
| 301-350        | 150      | 8.81%   |
| 351-500        | 134      | 7.87%   |
| 141-150        | 132      | 7.75%   |
| More than 1000 | 79       | 4.64%   |
| 251-300        | 70       | 4.11%   |
| 501-1000       | 57       | 3.35%   |
| 101-110        | 25       | 1.47%   |
| 111-120        | 7        | 0.41%   |
| 131-140        | 6        | 0.35%   |
| 91-100         | 2        | 0.12%   |
| 81-90          | 1        | 0.06%   |
| 121-130        | 1        | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 944      | 57.74%  |
| Unknown | 336      | 20.55%  |
| 101-120 | 226      | 13.82%  |
| 1-50    | 80       | 4.89%   |
| 121-160 | 35       | 2.14%   |
| 161-240 | 14       | 0.86%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1500     | 80.52%  |
| 2     | 207      | 11.11%  |
| 0     | 131      | 7.03%   |
| 3     | 23       | 1.23%   |
| 4     | 2        | 0.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 1112     | 40.88%  |
| Intel                                 | 672      | 24.71%  |
| Qualcomm Atheros                      | 168      | 6.18%   |
| Ralink Technology                     | 107      | 3.93%   |
| Broadcom                              | 97       | 3.57%   |
| Nvidia                                | 76       | 2.79%   |
| TP-Link                               | 58       | 2.13%   |
| Ralink                                | 40       | 1.47%   |
| Broadcom Limited                      | 35       | 1.29%   |
| MediaTek                              | 32       | 1.18%   |
| Marvell Technology Group              | 27       | 0.99%   |
| D-Link                                | 23       | 0.85%   |
| NetGear                               | 22       | 0.81%   |
| VIA Technologies                      | 21       | 0.77%   |
| Samsung Electronics                   | 21       | 0.77%   |
| D-Link System                         | 19       | 0.7%    |
| Xiaomi                                | 17       | 0.63%   |
| Qualcomm Atheros Communications       | 14       | 0.51%   |
| Microsoft                             | 13       | 0.48%   |
| Huawei Technologies                   | 12       | 0.44%   |
| ASIX Electronics                      | 10       | 0.37%   |
| Edimax Technology                     | 9        | 0.33%   |
| ASUSTek Computer                      | 9        | 0.33%   |
| Aquantia                              | 8        | 0.29%   |
| Belkin Components                     | 7        | 0.26%   |
| OPPO Electronics                      | 6        | 0.22%   |
| Linksys                               | 6        | 0.22%   |
| Silicon Integrated Systems [SiS]      | 5        | 0.18%   |
| Qualcomm                              | 4        | 0.15%   |
| Motorola PCS                          | 4        | 0.15%   |
| Gemtek                                | 4        | 0.15%   |
| DisplayLink                           | 4        | 0.15%   |
| Sundance Technology Inc / IC Plus     | 3        | 0.11%   |
| Sitecom Europe                        | 3        | 0.11%   |
| Motorola                              | 3        | 0.11%   |
| JMicron Technology                    | 3        | 0.11%   |
| Apple                                 | 3        | 0.11%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3        | 0.11%   |
| ZTE WCDMA Technologies MSM            | 2        | 0.07%   |
| TRENDnet                              | 2        | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 825      | 27.07%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 98       | 3.22%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 79       | 2.59%   |
| Intel I211 Gigabit Network Connection                             | 67       | 2.2%    |
| Realtek RTL8125 2.5GbE Controller                                 | 65       | 2.13%   |
| Intel Wi-Fi 6 AX200                                               | 63       | 2.07%   |
| Intel Ethernet Connection I217-LM                                 | 53       | 1.74%   |
| Ralink MT7601U Wireless Adapter                                   | 47       | 1.54%   |
| Nvidia MCP61 Ethernet                                             | 46       | 1.51%   |
| Intel Ethernet Connection (2) I219-V                              | 46       | 1.51%   |
| Realtek 802.11ac NIC                                              | 35       | 1.15%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 34       | 1.12%   |
| Intel Ethernet Controller I225-V                                  | 32       | 1.05%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 29       | 0.95%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 28       | 0.92%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 27       | 0.89%   |
| Intel Ethernet Connection I217-V                                  | 26       | 0.85%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 25       | 0.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 23       | 0.75%   |
| Intel 82579V Gigabit Network Connection                           | 22       | 0.72%   |
| Intel Ethernet Connection (2) I218-V                              | 21       | 0.69%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 19       | 0.62%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 19       | 0.62%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 19       | 0.62%   |
| Ralink RT5370 Wireless Adapter                                    | 18       | 0.59%   |
| Intel Wireless 7265                                               | 18       | 0.59%   |
| Intel Ethernet Connection (2) I219-LM                             | 18       | 0.59%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 17       | 0.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 16       | 0.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 16       | 0.52%   |
| Intel Wireless-AC 9260                                            | 16       | 0.52%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 15       | 0.49%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 15       | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 15       | 0.49%   |
| Intel 82574L Gigabit Network Connection                           | 15       | 0.49%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 15       | 0.49%   |
| Intel Ethernet Connection (7) I219-V                              | 14       | 0.46%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 13       | 0.43%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 12       | 0.39%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 12       | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 267      | 26.59%  |
| Intel                                 | 229      | 22.81%  |
| Ralink Technology                     | 107      | 10.66%  |
| Qualcomm Atheros                      | 84       | 8.37%   |
| TP-Link                               | 55       | 5.48%   |
| Ralink                                | 40       | 3.98%   |
| Broadcom                              | 39       | 3.88%   |
| MediaTek                              | 24       | 2.39%   |
| D-Link                                | 23       | 2.29%   |
| NetGear                               | 22       | 2.19%   |
| D-Link System                         | 15       | 1.49%   |
| Qualcomm Atheros Communications       | 14       | 1.39%   |
| Microsoft                             | 13       | 1.29%   |
| Broadcom Limited                      | 11       | 1.1%    |
| Edimax Technology                     | 9        | 0.9%    |
| ASUSTek Computer                      | 8        | 0.8%    |
| Belkin Components                     | 7        | 0.7%    |
| Linksys                               | 6        | 0.6%    |
| Marvell Technology Group              | 4        | 0.4%    |
| Gemtek                                | 4        | 0.4%    |
| Sitecom Europe                        | 3        | 0.3%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3        | 0.3%    |
| TRENDnet                              | 2        | 0.2%    |
| Senao                                 | 2        | 0.2%    |
| Philips (or NXP)                      | 2        | 0.2%    |
| Micro Star International              | 2        | 0.2%    |
| AVM                                   | 2        | 0.2%    |
| ZyXEL Communications                  | 1        | 0.1%    |
| ZyDAS                                 | 1        | 0.1%    |
| Xiaomi                                | 1        | 0.1%    |
| Panasonic (Matsushita)                | 1        | 0.1%    |
| Ovislink                              | 1        | 0.1%    |
| IMC Networks                          | 1        | 0.1%    |
| ADMtek                                | 1        | 0.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 63       | 6.19%   |
| Ralink MT7601U Wireless Adapter                                | 47       | 4.62%   |
| Realtek 802.11ac NIC                                           | 35       | 3.44%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 34       | 3.34%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 29       | 2.85%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 27       | 2.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 23       | 2.26%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 19       | 1.87%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 19       | 1.87%   |
| Ralink RT5370 Wireless Adapter                                 | 18       | 1.77%   |
| Intel Wireless 7265                                            | 18       | 1.77%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 17       | 1.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 16       | 1.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 16       | 1.57%   |
| Intel Wireless-AC 9260                                         | 16       | 1.57%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 15       | 1.47%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 15       | 1.47%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 12       | 1.18%   |
| Intel Wireless 7260                                            | 12       | 1.18%   |
| Qualcomm Atheros AR9271 802.11n                                | 11       | 1.08%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 11       | 1.08%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 11       | 1.08%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 10       | 0.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 10       | 0.98%   |
| Intel Wireless 8260                                            | 10       | 0.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 10       | 0.98%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 9        | 0.88%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 9        | 0.88%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 9        | 0.88%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 9        | 0.88%   |
| Intel Wireless 3165                                            | 9        | 0.88%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 8        | 0.79%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 8        | 0.79%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 8        | 0.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 8        | 0.79%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 7        | 0.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 7        | 0.69%   |
| Ralink RT2501/RT2573 Wireless Adapter                          | 7        | 0.69%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter     | 7        | 0.69%   |
| Microsoft Xbox 360 Wireless Adapter                            | 7        | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 1009     | 51.61%  |
| Intel                             | 546      | 27.93%  |
| Qualcomm Atheros                  | 87       | 4.45%   |
| Nvidia                            | 76       | 3.89%   |
| Broadcom                          | 58       | 2.97%   |
| Broadcom Limited                  | 25       | 1.28%   |
| Marvell Technology Group          | 23       | 1.18%   |
| VIA Technologies                  | 21       | 1.07%   |
| Xiaomi                            | 16       | 0.82%   |
| Samsung Electronics               | 13       | 0.66%   |
| Huawei Technologies               | 11       | 0.56%   |
| ASIX Electronics                  | 10       | 0.51%   |
| MediaTek                          | 8        | 0.41%   |
| Aquantia                          | 8        | 0.41%   |
| OPPO Electronics                  | 6        | 0.31%   |
| Silicon Integrated Systems [SiS]  | 5        | 0.26%   |
| Qualcomm                          | 4        | 0.2%    |
| DisplayLink                       | 4        | 0.2%    |
| D-Link System                     | 4        | 0.2%    |
| TP-Link                           | 3        | 0.15%   |
| Sundance Technology Inc / IC Plus | 3        | 0.15%   |
| JMicron Technology                | 3        | 0.15%   |
| Apple                             | 3        | 0.15%   |
| Motorola PCS                      | 2        | 0.1%    |
| ZTE WCDMA Technologies MSM        | 1        | 0.05%   |
| Research In Motion                | 1        | 0.05%   |
| HMD Global                        | 1        | 0.05%   |
| Google                            | 1        | 0.05%   |
| GCT Semiconductor                 | 1        | 0.05%   |
| ASUSTek Computer                  | 1        | 0.05%   |
| 3Com                              | 1        | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 825      | 41.35%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 98       | 4.91%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 79       | 3.96%   |
| Intel I211 Gigabit Network Connection                             | 67       | 3.36%   |
| Realtek RTL8125 2.5GbE Controller                                 | 65       | 3.26%   |
| Intel Ethernet Connection I217-LM                                 | 53       | 2.66%   |
| Nvidia MCP61 Ethernet                                             | 46       | 2.31%   |
| Intel Ethernet Connection (2) I219-V                              | 46       | 2.31%   |
| Intel Ethernet Controller I225-V                                  | 32       | 1.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 28       | 1.4%    |
| Intel Ethernet Connection I217-V                                  | 26       | 1.3%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 25       | 1.25%   |
| Intel 82579V Gigabit Network Connection                           | 22       | 1.1%    |
| Intel Ethernet Connection (2) I218-V                              | 21       | 1.05%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 19       | 0.95%   |
| Intel Ethernet Connection (2) I219-LM                             | 18       | 0.9%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 15       | 0.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 15       | 0.75%   |
| Intel 82574L Gigabit Network Connection                           | 15       | 0.75%   |
| Intel Ethernet Connection (7) I219-V                              | 14       | 0.7%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 13       | 0.65%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 12       | 0.6%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 11       | 0.55%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 11       | 0.55%   |
| Nvidia MCP73 Ethernet                                             | 11       | 0.55%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 11       | 0.55%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 11       | 0.55%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 11       | 0.55%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 9        | 0.45%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 9        | 0.45%   |
| Intel 82578DC Gigabit Network Connection                          | 9        | 0.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8        | 0.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 8        | 0.4%    |
| Intel Ethernet Connection (12) I219-V                             | 8        | 0.4%    |
| Intel 82578DM Gigabit Network Connection                          | 8        | 0.4%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 7        | 0.35%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 7        | 0.35%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 7        | 0.35%   |
| Intel NM10/ICH7 Family LAN Controller                             | 7        | 0.35%   |
| Huawei WLZ-AN00                                                   | 7        | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1807     | 65.69%  |
| WiFi     | 910      | 33.08%  |
| Modem    | 29       | 1.05%   |
| Unknown  | 5        | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1350     | 70.94%  |
| WiFi     | 549      | 28.85%  |
| Modem    | 3        | 0.16%   |
| Unknown  | 1        | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1246     | 67.61%  |
| 2     | 528      | 28.65%  |
| 3     | 51       | 2.77%   |
| 0     | 12       | 0.65%   |
| 5     | 3        | 0.16%   |
| 4     | 2        | 0.11%   |
| 7     | 1        | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1392     | 74.92%  |
| Yes  | 466      | 25.08%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 190      | 35.58%  |
| Cambridge Silicon Radio         | 116      | 21.72%  |
| Realtek Semiconductor           | 63       | 11.8%   |
| Broadcom                        | 32       | 5.99%   |
| ASUSTek Computer                | 25       | 4.68%   |
| Qualcomm Atheros Communications | 20       | 3.75%   |
| IMC Networks                    | 15       | 2.81%   |
| MediaTek                        | 12       | 2.25%   |
| Apple                           | 10       | 1.87%   |
| TP-Link                         | 7        | 1.31%   |
| Dynex                           | 7        | 1.31%   |
| Integrated System Solution      | 5        | 0.94%   |
| Belkin Components               | 5        | 0.94%   |
| Micro Star International        | 4        | 0.75%   |
| Lite-On Technology              | 3        | 0.56%   |
| Foxconn / Hon Hai               | 3        | 0.56%   |
| ISSC                            | 2        | 0.37%   |
| Dell                            | 2        | 0.37%   |
| Actions                         | 2        | 0.37%   |
| Unknown                         | 2        | 0.37%   |
| Sitecom Europe                  | 1        | 0.19%   |
| Realtek                         | 1        | 0.19%   |
| National Semiconductor          | 1        | 0.19%   |
| Mobile Action Technology        | 1        | 0.19%   |
| Logitech                        | 1        | 0.19%   |
| Hewlett-Packard                 | 1        | 0.19%   |
| Fujitsu                         | 1        | 0.19%   |
| Edimax Technology               | 1        | 0.19%   |
| D-Link System                   | 1        | 0.19%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 116      | 21.72%  |
| Intel AX200 Bluetooth                                    | 50       | 9.36%   |
| Realtek Bluetooth Radio                                  | 48       | 8.99%   |
| Intel Bluetooth wireless interface                       | 45       | 8.43%   |
| Intel AX210 Bluetooth                                    | 24       | 4.49%   |
| Intel Wireless-AC 3168 Bluetooth                         | 22       | 4.12%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 17       | 3.18%   |
| Intel AX201 Bluetooth                                    | 14       | 2.62%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 13       | 2.43%   |
| MediaTek Wireless_Device                                 | 12       | 2.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 11       | 2.06%   |
| IMC Networks Bluetooth Radio                             | 11       | 2.06%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 11       | 2.06%   |
| TP-Link UB500 Adapter                                    | 7        | 1.31%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 7        | 1.31%   |
| ASUS Bluetooth Radio                                     | 6        | 1.12%   |
| Realtek RTL8821A Bluetooth                               | 5        | 0.94%   |
| Realtek  Bluetooth 4.2 Adapter                           | 5        | 0.94%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 5        | 0.94%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 5        | 0.94%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 5        | 0.94%   |
| Apple Bluetooth USB Host Controller                      | 5        | 0.94%   |
| Realtek Bluetooth 5.1 Radio                              | 4        | 0.75%   |
| Qualcomm Atheros  Bluetooth Device                       | 4        | 0.75%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter    | 4        | 0.75%   |
| Micro Star International Bluetooth Device                | 3        | 0.56%   |
| Lite-On Bluetooth Device                                 | 3        | 0.56%   |
| Integrated System Solution Bluetooth Device              | 3        | 0.56%   |
| Broadcom HP Portable Bumble Bee                          | 3        | 0.56%   |
| Broadcom BCM43142A0 Bluetooth 4.0                        | 3        | 0.56%   |
| ASUS Qualcomm Bluetooth 4.1                              | 3        | 0.56%   |
| ASUS ASUS USB-BT500                                      | 3        | 0.56%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 2        | 0.37%   |
| Qualcomm Atheros Bluetooth                               | 2        | 0.37%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                    | 2        | 0.37%   |
| ISSC Bluetooth Device                                    | 2        | 0.37%   |
| Intel Bluetooth Device                                   | 2        | 0.37%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter    | 2        | 0.37%   |
| IMC Networks Bluetooth Module                            | 2        | 0.37%   |
| Foxconn / Hon Hai Wireless_Device                        | 2        | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 1159     | 39.79%  |
| AMD                                          | 738      | 25.33%  |
| Nvidia                                       | 654      | 22.45%  |
| C-Media Electronics                          | 75       | 2.57%   |
| Creative Labs                                | 34       | 1.17%   |
| VIA Technologies                             | 24       | 0.82%   |
| Logitech                                     | 21       | 0.72%   |
| Kingston Technology                          | 14       | 0.48%   |
| JMTek                                        | 13       | 0.45%   |
| Generalplus Technology                       | 13       | 0.45%   |
| ASUSTek Computer                             | 13       | 0.45%   |
| Texas Instruments                            | 10       | 0.34%   |
| Razer USA                                    | 9        | 0.31%   |
| Plantronics                                  | 9        | 0.31%   |
| GN Netcom                                    | 8        | 0.27%   |
| Creative Technology                          | 8        | 0.27%   |
| Silicon Integrated Systems [SiS]             | 6        | 0.21%   |
| Tenx Technology                              | 5        | 0.17%   |
| Realtek Semiconductor                        | 4        | 0.14%   |
| Micro Star International                     | 4        | 0.14%   |
| Zoran Co. Personal Media Division (Nogatech) | 3        | 0.1%    |
| SteelSeries ApS                              | 3        | 0.1%    |
| RODE Microphones                             | 3        | 0.1%    |
| Focusrite-Novation                           | 3        | 0.1%    |
| Astro Gaming                                 | 3        | 0.1%    |
| Yamaha                                       | 2        | 0.07%   |
| Turtle Beach                                 | 2        | 0.07%   |
| Thesycon Systemsoftware & Consulting         | 2        | 0.07%   |
| Samsung Electronics                          | 2        | 0.07%   |
| Micronas                                     | 2        | 0.07%   |
| KTMicro                                      | 2        | 0.07%   |
| Jieli Technology                             | 2        | 0.07%   |
| FUXIN                                        | 2        | 0.07%   |
| Ensoniq                                      | 2        | 0.07%   |
| DSEA A/S                                     | 2        | 0.07%   |
| DigiTech                                     | 2        | 0.07%   |
| Corsair                                      | 2        | 0.07%   |
| Cambridge Audio                              | 2        | 0.07%   |
| Blue Microphones                             | 2        | 0.07%   |
| BEHRINGER International                      | 2        | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 167      | 4.94%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 167      | 4.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 159      | 4.71%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 157      | 4.65%   |
| AMD Starship/Matisse HD Audio Controller                                          | 117      | 3.46%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 111      | 3.29%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 93       | 2.75%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 87       | 2.58%   |
| AMD Family 17h/19h HD Audio Controller                                            | 79       | 2.34%   |
| AMD FCH Azalia Controller                                                         | 77       | 2.28%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 69       | 2.04%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 68       | 2.01%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 66       | 1.95%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 57       | 1.69%   |
| Intel 200 Series PCH HD Audio                                                     | 51       | 1.51%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 50       | 1.48%   |
| Nvidia MCP61 High Definition Audio                                                | 48       | 1.42%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 47       | 1.39%   |
| Intel Cannon Lake PCH cAVS                                                        | 45       | 1.33%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 43       | 1.27%   |
| Nvidia GF108 High Definition Audio Controller                                     | 42       | 1.24%   |
| Nvidia High Definition Audio Controller                                           | 39       | 1.15%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 38       | 1.12%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 37       | 1.1%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 36       | 1.07%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 34       | 1.01%   |
| Nvidia TU116 High Definition Audio Controller                                     | 32       | 0.95%   |
| Nvidia GF119 HDMI Audio Controller                                                | 32       | 0.95%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 31       | 0.92%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 30       | 0.89%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 29       | 0.86%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 27       | 0.8%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 26       | 0.77%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 26       | 0.77%   |
| AMD Navi 10 HDMI Audio                                                            | 26       | 0.77%   |
| Nvidia GK107 HDMI Audio Controller                                                | 23       | 0.68%   |
| AMD Kabini HDMI/DP Audio                                                          | 23       | 0.68%   |
| Nvidia TU106 High Definition Audio Controller                                     | 22       | 0.65%   |
| Nvidia GP106 High Definition Audio Controller                                     | 22       | 0.65%   |
| Nvidia GP104 High Definition Audio Controller                                     | 22       | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 66       | 22.76%  |
| Kingston            | 39       | 13.45%  |
| Samsung Electronics | 29       | 10%     |
| SK hynix            | 26       | 8.97%   |
| Corsair             | 25       | 8.62%   |
| G.Skill             | 23       | 7.93%   |
| Crucial             | 22       | 7.59%   |
| Micron Technology   | 11       | 3.79%   |
| Team                | 8        | 2.76%   |
| Elpida              | 6        | 2.07%   |
| Unknown             | 4        | 1.38%   |
| Ramaxel Technology  | 3        | 1.03%   |
| Patriot             | 3        | 1.03%   |
| Nanya Technology    | 3        | 1.03%   |
| A-DATA Technology   | 3        | 1.03%   |
| Wilk                | 2        | 0.69%   |
| Unifosa             | 2        | 0.69%   |
| Qimonda             | 2        | 0.69%   |
| Avant               | 2        | 0.69%   |
| Transcend           | 1        | 0.34%   |
| SUPER KINGSTEK      | 1        | 0.34%   |
| Ramos Technology    | 1        | 0.34%   |
| PNY                 | 1        | 0.34%   |
| Patriot Memory      | 1        | 0.34%   |
| Goldkey             | 1        | 0.34%   |
| Golden Empire       | 1        | 0.34%   |
| F7852C80            | 1        | 0.34%   |
| CSX                 | 1        | 0.34%   |
| ASint Technology    | 1        | 0.34%   |
| AMD                 | 1        | 0.34%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s            | 5        | 1.57%   |
| Unknown RAM Module 1GB DIMM SDRAM                       | 4        | 1.26%   |
| Unknown                                                 | 4        | 1.26%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s               | 3        | 0.94%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 3000MT/s      | 3        | 0.94%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s    | 3        | 0.94%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s     | 3        | 0.94%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s            | 2        | 0.63%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 2        | 0.63%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s            | 2        | 0.63%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                  | 2        | 0.63%   |
| Unknown RAM Module 4096MB DIMM                          | 2        | 0.63%   |
| Unknown RAM Module 2GB DIMM 800MT/s                     | 2        | 0.63%   |
| Unknown RAM Module 2GB DIMM 667MT/s                     | 2        | 0.63%   |
| Unknown RAM Module 2048MB DIMM SDRAM                    | 2        | 0.63%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                  | 2        | 0.63%   |
| Unknown RAM Module 1GB DIMM DDR2                        | 2        | 0.63%   |
| Unknown RAM Module 1024MB DIMM SDRAM                    | 2        | 0.63%   |
| Unknown RAM Module 1024MB DIMM DDR2 333MT/s             | 2        | 0.63%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                  | 2        | 0.63%   |
| Unknown RAM Module 1024MB DIMM                          | 2        | 0.63%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 2933MT/s     | 2        | 0.63%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s    | 2        | 0.63%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s    | 2        | 0.63%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s     | 2        | 0.63%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s     | 2        | 0.63%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s     | 2        | 0.63%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s     | 2        | 0.63%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s    | 2        | 0.63%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s       | 2        | 0.63%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s     | 2        | 0.63%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s   | 2        | 0.63%   |
| Kingston RAM KCM633-ELC 1GB DIMM DDR2 2048MT/s          | 2        | 0.63%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s   | 2        | 0.63%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s    | 2        | 0.63%   |
| G.Skill RAM F4-3200C16-16GTZR 16GB DIMM DDR4 3333MT/s   | 2        | 0.63%   |
| Elpida RAM EBJ20UF8BCF0-DJ-F 2GB DIMM DDR3 1333MT/s     | 2        | 0.63%   |
| Crucial RAM CT16G48C40S5.M8A1 16GB SODIMM DDR5 4800MT/s | 2        | 0.63%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s   | 2        | 0.63%   |
| Crucial RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3            | 2        | 0.63%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 93       | 35.77%  |
| DDR3    | 91       | 35%     |
| Unknown | 28       | 10.77%  |
| DDR2    | 21       | 8.08%   |
| SDRAM   | 19       | 7.31%   |
| DDR     | 4        | 1.54%   |
| DDR5    | 3        | 1.15%   |
| LPDDR4  | 1        | 0.38%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 240      | 94.86%  |
| SODIMM       | 11       | 4.35%   |
| Row Of Chips | 1        | 0.4%    |
| FB-DIMM      | 1        | 0.4%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 91       | 31.71%  |
| 4096  | 77       | 26.83%  |
| 2048  | 50       | 17.42%  |
| 16384 | 28       | 9.76%   |
| 1024  | 27       | 9.41%   |
| 32768 | 12       | 4.18%   |
| 512   | 2        | 0.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 47       | 16.73%  |
| 1333    | 41       | 14.59%  |
| 3200    | 20       | 7.12%   |
| 3600    | 17       | 6.05%   |
| 800     | 17       | 6.05%   |
| Unknown | 15       | 5.34%   |
| 2400    | 10       | 3.56%   |
| 2133    | 10       | 3.56%   |
| 2667    | 9        | 3.2%    |
| 667     | 9        | 3.2%    |
| 3000    | 7        | 2.49%   |
| 1866    | 7        | 2.49%   |
| 1800    | 6        | 2.14%   |
| 2933    | 4        | 1.42%   |
| 1066    | 4        | 1.42%   |
| 400     | 4        | 1.42%   |
| 333     | 4        | 1.42%   |
| 3866    | 3        | 1.07%   |
| 2800    | 3        | 1.07%   |
| 2666    | 3        | 1.07%   |
| 1867    | 3        | 1.07%   |
| 4800    | 2        | 0.71%   |
| 3800    | 2        | 0.71%   |
| 3733    | 2        | 0.71%   |
| 3666    | 2        | 0.71%   |
| 3466    | 2        | 0.71%   |
| 3400    | 2        | 0.71%   |
| 3333    | 2        | 0.71%   |
| 3266    | 2        | 0.71%   |
| 2048    | 2        | 0.71%   |
| 49926   | 1        | 0.36%   |
| 5354    | 1        | 0.36%   |
| 5200    | 1        | 0.36%   |
| 4400    | 1        | 0.36%   |
| 4266    | 1        | 0.36%   |
| 4000    | 1        | 0.36%   |
| 3933    | 1        | 0.36%   |
| 3533    | 1        | 0.36%   |
| 3500    | 1        | 0.36%   |
| 3467    | 1        | 0.36%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 26       | 25.74%  |
| Canon                 | 21       | 20.79%  |
| Brother Industries    | 19       | 18.81%  |
| Seiko Epson           | 14       | 13.86%  |
| Samsung Electronics   | 12       | 11.88%  |
| Ricoh                 | 2        | 1.98%   |
| Lexmark International | 2        | 1.98%   |
| Toshiba TEC           | 1        | 0.99%   |
| STMicroelectronics    | 1        | 0.99%   |
| QinHeng Electronics   | 1        | 0.99%   |
| Pantum                | 1        | 0.99%   |
| Konica Minolta        | 1        | 0.99%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Canon TS3100 series                                       | 3        | 2.97%   |
| Canon PIXMA MG2500 Series                                 | 3        | 2.97%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 2        | 1.98%   |
| Seiko Epson L3110 Series                                  | 2        | 1.98%   |
| Samsung ML-216x Series Laser Printer                      | 2        | 1.98%   |
| Samsung C460 Series                                       | 2        | 1.98%   |
| HP LaserJet Professional P1102w                           | 2        | 1.98%   |
| HP ENVY 5000 series                                       | 2        | 1.98%   |
| HP ENVY 4520 series                                       | 2        | 1.98%   |
| HP DeskJet 2130 series                                    | 2        | 1.98%   |
| Canon MF4010 series                                       | 2        | 1.98%   |
| Canon LiDE 400                                            | 2        | 1.98%   |
| Brother HL-2130 series                                    | 2        | 1.98%   |
| Toshiba TEC e-STD120 USB                                  | 1        | 0.99%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1        | 0.99%   |
| Seiko Epson XP-7100 Series                                | 1        | 0.99%   |
| Seiko Epson XP-225 Series                                 | 1        | 0.99%   |
| Seiko Epson XP-200 Series                                 | 1        | 0.99%   |
| Seiko Epson L805 Series                                   | 1        | 0.99%   |
| Seiko Epson L365 Series                                   | 1        | 0.99%   |
| Seiko Epson L360 Series                                   | 1        | 0.99%   |
| Seiko Epson L355 Series                                   | 1        | 0.99%   |
| Seiko Epson L120 Series                                   | 1        | 0.99%   |
| Seiko Epson ET-2820 Series                                | 1        | 0.99%   |
| Seiko Epson ET-2710 Series                                | 1        | 0.99%   |
| Samsung SCX-483x 5x3x Series                              | 1        | 0.99%   |
| Samsung SCX-4623 Series                                   | 1        | 0.99%   |
| Samsung SCX-4200 series                                   | 1        | 0.99%   |
| Samsung SCX-3400 Series                                   | 1        | 0.99%   |
| Samsung ML-2950 Series                                    | 1        | 0.99%   |
| Samsung ML-2010P Mono Laser Printer                       | 1        | 0.99%   |
| Samsung M2070 Series                                      | 1        | 0.99%   |
| Samsung CLX-3300 Series                                   | 1        | 0.99%   |
| Ricoh SP C250SF                                           | 1        | 0.99%   |
| Ricoh SP 112SU                                            | 1        | 0.99%   |
| QinHeng CH340S                                            | 1        | 0.99%   |
| Pantum P2500W series                                      | 1        | 0.99%   |
| Lexmark International MX317dn                             | 1        | 0.99%   |
| Lexmark International Laser Printer E232                  | 1        | 0.99%   |
| Konica Minolta PagePro 1380MF                             | 1        | 0.99%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 10       | 76.92%  |
| Hewlett-Packard | 2        | 15.38%  |
| Seiko Epson     | 1        | 7.69%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 3        | 21.43%  |
| Canon CanoScan LiDE 100            | 2        | 14.29%  |
| Seiko Epson Scanner                | 1        | 7.14%   |
| HP ScanJet 2400c                   | 1        | 7.14%   |
| HP PSC 1200                        | 1        | 7.14%   |
| Canon CanoScan LiDE 60             | 1        | 7.14%   |
| Canon CanoScan LIDE 25             | 1        | 7.14%   |
| Canon CanoScan LiDE 220            | 1        | 7.14%   |
| Canon CanoScan LiDE 110            | 1        | 7.14%   |
| Canon CanoScan D660U               | 1        | 7.14%   |
| Canon CanoScan 8800F               | 1        | 7.14%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 72       | 27.38%  |
| Microdia                      | 23       | 8.75%   |
| Microsoft                     | 22       | 8.37%   |
| Apple                         | 14       | 5.32%   |
| Sunplus Innovation Technology | 12       | 4.56%   |
| Samsung Electronics           | 11       | 4.18%   |
| Generalplus Technology        | 9        | 3.42%   |
| Chicony Electronics           | 9        | 3.42%   |
| ARC International             | 7        | 2.66%   |
| Cubeternet                    | 6        | 2.28%   |
| Z-Star Microelectronics       | 5        | 1.9%    |
| Jieli Technology              | 5        | 1.9%    |
| Realtek Semiconductor         | 4        | 1.52%   |
| Razer USA                     | 4        | 1.52%   |
| GEMBIRD                       | 4        | 1.52%   |
| Tobii Technology AB           | 3        | 1.14%   |
| IMC Networks                  | 3        | 1.14%   |
| Creative Technology           | 3        | 1.14%   |
| Aveo Technology               | 3        | 1.14%   |
| Arkmicro Technologies         | 3        | 1.14%   |
| Xiongmai                      | 2        | 0.76%   |
| Suyin                         | 2        | 0.76%   |
| Sonix Technology              | 2        | 0.76%   |
| Pixart Imaging                | 2        | 0.76%   |
| MacroSilicon                  | 2        | 0.76%   |
| lihappe8                      | 2        | 0.76%   |
| KYE Systems (Mouse Systems)   | 2        | 0.76%   |
| Guillemot                     | 2        | 0.76%   |
| Genesys Logic                 | 2        | 0.76%   |
| AVerMedia Technologies        | 2        | 0.76%   |
| Alcor Micro                   | 2        | 0.76%   |
| A4Tech                        | 2        | 0.76%   |
| 2M UVC CAMERA                 | 2        | 0.76%   |
| WaveRider Communications      | 1        | 0.38%   |
| Unknown                       | 1        | 0.38%   |
| Trust                         | 1        | 0.38%   |
| Teslong Camera                | 1        | 0.38%   |
| Sunplus Technology            | 1        | 0.38%   |
| Ruision                       | 1        | 0.38%   |
| Novatel Wireless              | 1        | 0.38%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Logitech Webcam C270                     | 19       | 7.17%   |
| Logitech HD Pro Webcam C920              | 14       | 5.28%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X          | 12       | 4.53%   |
| Samsung Galaxy series, misc. (MTP mode)  | 11       | 4.15%   |
| Microsoft LifeCam HD-3000                | 10       | 3.77%   |
| Microdia USB 2.0 Camera                  | 7        | 2.64%   |
| ARC International Camera                 | 7        | 2.64%   |
| Chicony HP High Definition 1MP Webcam    | 6        | 2.26%   |
| Sunplus 1080P Webcam                     | 5        | 1.89%   |
| Jieli USB PHY 2.0                        | 5        | 1.89%   |
| Sunplus HD 720P webcam                   | 4        | 1.51%   |
| Razer USA Gaming Webcam [Kiyo]           | 4        | 1.51%   |
| Microdia Webcam Vitade AF                | 4        | 1.51%   |
| Logitech HD Webcam C615                  | 4        | 1.51%   |
| Logitech C920 PRO HD Webcam              | 4        | 1.51%   |
| Generalplus GENERAL WEBCAM               | 4        | 1.51%   |
| Generalplus 808 Camera #9 (web-cam mode) | 4        | 1.51%   |
| Tobii AB EyeChip                         | 3        | 1.13%   |
| Microsoft LifeCam VX-500 [1357]          | 3        | 1.13%   |
| Microdia Integrated Camera               | 3        | 1.13%   |
| Logitech Webcam C925e                    | 3        | 1.13%   |
| Logitech Webcam C310                     | 3        | 1.13%   |
| Logitech HD Webcam C910                  | 3        | 1.13%   |
| Logitech C922 Pro Stream Webcam          | 3        | 1.13%   |
| Cubeternet GL-UPC822 UVC WebCam          | 3        | 1.13%   |
| Z-Star Venus USB2.0 Camera               | 2        | 0.75%   |
| Z-Star Integrated Camera                 | 2        | 0.75%   |
| Xiongmai web camera                      | 2        | 0.75%   |
| Suyin HD WebCam                          | 2        | 0.75%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro     | 2        | 0.75%   |
| Microsoft MicrosoftÂ LifeCam Cinema     | 2        | 0.75%   |
| Microsoft LifeCam VX-2000                | 2        | 0.75%   |
| Microsoft LifeCam HD-5000                | 2        | 0.75%   |
| Microdia USB Live camera                 | 2        | 0.75%   |
| Microdia Camera                          | 2        | 0.75%   |
| Logitech Webcam C250                     | 2        | 0.75%   |
| Logitech QuickCam Pro for Notebooks      | 2        | 0.75%   |
| Logitech QuickCam Pro 9000               | 2        | 0.75%   |
| Logitech HD Webcam C525                  | 2        | 0.75%   |
| lihappe8 USB 2.0 Camera                  | 2        | 0.75%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 2        | 66.67%  |
| AuthenTec             | 1        | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| LighTuning Fingerprint Sensor             | 1        | 33.33%  |
| LighTuning ES603 Swipe Fingerprint Sensor | 1        | 33.33%  |
| AuthenTec AES2501 Fingerprint Sensor      | 1        | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 2        | 15.38%  |
| Alcor Micro                       | 2        | 15.38%  |
| Advanced Card Systems             | 2        | 15.38%  |
| VASCO Data Security International | 1        | 7.69%   |
| SCM Microsystems                  | 1        | 7.69%   |
| Reiner SCT Kartensysteme          | 1        | 7.69%   |
| Kobil Systems                     | 1        | 7.69%   |
| Jing-Mold Enterprise              | 1        | 7.69%   |
| Fujitsu Siemens Computers         | 1        | 7.69%   |
| Chicony Electronics               | 1        | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface                 | 2        | 15.38%  |
| Alcor Micro AU9540 Smartcard Reader                               | 2        | 15.38%  |
| VASCO Data Security International Digipass 905 SmartCard Reader   | 1        | 7.69%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader            | 1        | 7.69%   |
| Reiner SCT Kartensysteme cyberJack e-com/pinpad                   | 1        | 7.69%   |
| Kobil Systems KOBIL Class 3 Reader                                | 1        | 7.69%   |
| Jing-Mold Enterprise HP USB Business Slim Smartcard CCID Keyboard | 1        | 7.69%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                     | 1        | 7.69%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard              | 1        | 7.69%   |
| Advanced Card Systems ACR39U                                      | 1        | 7.69%   |
| Advanced Card Systems ACR1281 1S Dual Reader                      | 1        | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1487     | 79.73%  |
| 1     | 327      | 17.53%  |
| 2     | 44       | 2.36%   |
| 3     | 5        | 0.27%   |
| 4     | 2        | 0.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 165      | 39.47%  |
| Net/wireless             | 145      | 34.69%  |
| Communication controller | 29       | 6.94%   |
| Multimedia controller    | 20       | 4.78%   |
| Unassigned class         | 13       | 3.11%   |
| Modem                    | 9        | 2.15%   |
| Chipcard                 | 9        | 2.15%   |
| Storage/raid             | 6        | 1.44%   |
| Sound                    | 5        | 1.2%    |
| Fingerprint reader       | 3        | 0.72%   |
| Bluetooth                | 3        | 0.72%   |
| Network                  | 2        | 0.48%   |
| Net/ethernet             | 2        | 0.48%   |
| Camera                   | 2        | 0.48%   |
| Storage/nvme             | 1        | 0.24%   |
| Storage/ide              | 1        | 0.24%   |
| Storage                  | 1        | 0.24%   |
| Dvb card                 | 1        | 0.24%   |
| Card reader              | 1        | 0.24%   |

