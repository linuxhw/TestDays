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

Total: 1863

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Pegatron      | BOWIE                       | [a2bbc6abd3](https://linux-hardware.org/?probe=a2bbc6abd3) | Jun 17, 2023 |
| ASRock        | B85M                        | [19f8b16937](https://linux-hardware.org/?probe=19f8b16937) | Jun 15, 2023 |
| Dell          | 0KC9NP A01                  | [b00d413241](https://linux-hardware.org/?probe=b00d413241) | Jun 14, 2023 |
| Dell          | 0KC9NP A01                  | [1d487a1ed5](https://linux-hardware.org/?probe=1d487a1ed5) | Jun 14, 2023 |
| Dell          | 0WR7PY A02                  | [eab79964fb](https://linux-hardware.org/?probe=eab79964fb) | Jun 14, 2023 |
| Vorke         | V1 Plus                     | [a63988d437](https://linux-hardware.org/?probe=a63988d437) | Jun 14, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [c1992a1680](https://linux-hardware.org/?probe=c1992a1680) | Jun 13, 2023 |
| Pegatron      | BOWIE                       | [2794a5aa86](https://linux-hardware.org/?probe=2794a5aa86) | Jun 12, 2023 |
| ASUSTek       | P5B                         | [6308a1c633](https://linux-hardware.org/?probe=6308a1c633) | Jun 12, 2023 |
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
| Lenovo        | SHARKBAY SDK0E50512 STD     | [abc4bba144](https://linux-hardware.org/?probe=abc4bba144) | Jun 01, 2023 |
| MSI           | 890FXA-GD70                 | [bcc4cd9597](https://linux-hardware.org/?probe=bcc4cd9597) | Jun 01, 2023 |
| Gigabyte      | B450M DS3H-CF               | [923c9a18ff](https://linux-hardware.org/?probe=923c9a18ff) | Jun 01, 2023 |
| MSI           | B450 TOMAHAWK               | [0ddd2982db](https://linux-hardware.org/?probe=0ddd2982db) | May 31, 2023 |
| MSI           | B450 TOMAHAWK               | [93d1ee7e2d](https://linux-hardware.org/?probe=93d1ee7e2d) | May 31, 2023 |
| Acer          | Predator G3-605             | [f33c170be3](https://linux-hardware.org/?probe=f33c170be3) | May 27, 2023 |
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
| Gigabyte      | Z590 VISION G               | [d37eb8bf49](https://linux-hardware.org/?probe=d37eb8bf49) | May 04, 2023 |
| ASRock        | H81M-HDS                    | [60e11bdf11](https://linux-hardware.org/?probe=60e11bdf11) | May 04, 2023 |
| Gigabyte      | MFLP5IP-00                  | [c9c14a6da2](https://linux-hardware.org/?probe=c9c14a6da2) | May 03, 2023 |
| Gigabyte      | P55A-UD3                    | [c338210639](https://linux-hardware.org/?probe=c338210639) | May 03, 2023 |
| Dell          | 09WH54 A00                  | [0afa4006cd](https://linux-hardware.org/?probe=0afa4006cd) | May 03, 2023 |
| ASUSTek       | PRIME X370-PRO              | [d3757c615f](https://linux-hardware.org/?probe=d3757c615f) | May 02, 2023 |
| Intel         | D946GZIS AAD66165-301       | [e61e22863f](https://linux-hardware.org/?probe=e61e22863f) | May 02, 2023 |
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
| ASRock        | Z68 Pro3-M                  | [60f0809fbf](https://linux-hardware.org/?probe=60f0809fbf) | Mar 28, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [dcbcf69a04](https://linux-hardware.org/?probe=dcbcf69a04) | Mar 27, 2023 |
| Dell          | 0J8H4R A00                  | [63d85fd315](https://linux-hardware.org/?probe=63d85fd315) | Mar 27, 2023 |
| Lenovo        | 11061GG ThinkServer TS13... | [174e514c30](https://linux-hardware.org/?probe=174e514c30) | Mar 26, 2023 |
| Packard Be... | MCP73PV                     | [87d1fd7511](https://linux-hardware.org/?probe=87d1fd7511) | Mar 26, 2023 |
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
| Dell          | 0GM819                      | [1db4004d05](https://linux-hardware.org/?probe=1db4004d05) | Mar 12, 2023 |
| Medion        | MS-7707                     | [a0621e0cd1](https://linux-hardware.org/?probe=a0621e0cd1) | Mar 12, 2023 |
| Gigabyte      | EX58-EXTREME                | [f45a0d4c01](https://linux-hardware.org/?probe=f45a0d4c01) | Mar 12, 2023 |
| Medion        | MS-7707                     | [4c9432026b](https://linux-hardware.org/?probe=4c9432026b) | Mar 12, 2023 |
| Gigabyte      | H110M-H-CF                  | [91da2169aa](https://linux-hardware.org/?probe=91da2169aa) | Mar 12, 2023 |
| Gigabyte      | X670E AORUS XTREME          | [83cb566647](https://linux-hardware.org/?probe=83cb566647) | Mar 12, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [bd0c265909](https://linux-hardware.org/?probe=bd0c265909) | Mar 11, 2023 |
| Acer          | WG43M                       | [5858448536](https://linux-hardware.org/?probe=5858448536) | Mar 11, 2023 |
| Acer          | WG43M                       | [3d562885d0](https://linux-hardware.org/?probe=3d562885d0) | Mar 11, 2023 |
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
| Unknown       | Rev.00                      | [89ff2d84f4](https://linux-hardware.org/?probe=89ff2d84f4) | Mar 03, 2023 |
| ASUSTek       | P7H55-M LX                  | [80e66c5eac](https://linux-hardware.org/?probe=80e66c5eac) | Mar 03, 2023 |
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
| HP            | 1825                        | [fd942fd3ba](https://linux-hardware.org/?probe=fd942fd3ba) | Feb 02, 2023 |
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
| Unknown       | Unknown                     | [9cb802849a](https://linux-hardware.org/?probe=9cb802849a) | Jan 14, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | [e00028a10c](https://linux-hardware.org/?probe=e00028a10c) | Jan 14, 2023 |
| HC            | HCAR357-MI V1.0             | [b5f80f8eac](https://linux-hardware.org/?probe=b5f80f8eac) | Jan 14, 2023 |
| HP            | 0B4Ch D                     | [c5edc9fbc7](https://linux-hardware.org/?probe=c5edc9fbc7) | Jan 14, 2023 |
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
| Dell          | 0MGK50 A04                  | [931b01be38](https://linux-hardware.org/?probe=931b01be38) | Dec 20, 2022 |
| ASRock        | Z170 Pro4                   | [ca027f264a](https://linux-hardware.org/?probe=ca027f264a) | Dec 20, 2022 |
| ASRock        | B450M Pro4                  | [83df1364c8](https://linux-hardware.org/?probe=83df1364c8) | Dec 20, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [87907abff7](https://linux-hardware.org/?probe=87907abff7) | Dec 19, 2022 |
| ASUSTek       | PRIME H310M-A R2.0          | [08f3a88ab3](https://linux-hardware.org/?probe=08f3a88ab3) | Dec 19, 2022 |
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
| HP            | 0A54h                       | [2c88c7fd30](https://linux-hardware.org/?probe=2c88c7fd30) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [d13cf99728](https://linux-hardware.org/?probe=d13cf99728) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [1e43753d7a](https://linux-hardware.org/?probe=1e43753d7a) | Sep 10, 2022 |
| MSI           | 2AE0                        | [a2b046dd4e](https://linux-hardware.org/?probe=a2b046dd4e) | Sep 10, 2022 |
| HP            | 3031h                       | [ea434d67b5](https://linux-hardware.org/?probe=ea434d67b5) | Sep 10, 2022 |
| HP            | 3031h                       | [feddf42c9f](https://linux-hardware.org/?probe=feddf42c9f) | Sep 10, 2022 |
| HP            | 0AA8h                       | [4e9a1e883c](https://linux-hardware.org/?probe=4e9a1e883c) | Sep 09, 2022 |
| Lenovo        | MAHOBAY                     | [2619e261d1](https://linux-hardware.org/?probe=2619e261d1) | Sep 07, 2022 |
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

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin_16/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.15.0-56-generic | 72       | 5.17%   |
| 5.11.0-38-generic | 62       | 4.45%   |
| 5.15.0-67-generic | 57       | 4.09%   |
| 5.15.0-69-generic | 56       | 4.02%   |
| 5.11.0-27-generic | 56       | 4.02%   |
| 5.15.0-46-generic | 55       | 3.95%   |
| 5.11.0-40-generic | 50       | 3.59%   |
| 5.15.0-52-generic | 49       | 3.52%   |
| 5.13.0-39-generic | 49       | 3.52%   |
| 5.15.0-58-generic | 46       | 3.3%    |
| 5.15.0-60-generic | 45       | 3.23%   |
| 5.15.0-48-generic | 41       | 2.94%   |
| 5.11.0-41-generic | 41       | 2.94%   |
| 5.13.0-30-generic | 40       | 2.87%   |
| 5.15.0-71-generic | 39       | 2.8%    |
| 5.13.0-40-generic | 38       | 2.73%   |
| 5.15.0-76-generic | 36       | 2.58%   |
| 5.11.0-43-generic | 36       | 2.58%   |
| 5.15.0-41-generic | 35       | 2.51%   |
| 5.11.0-37-generic | 35       | 2.51%   |
| 5.13.0-28-generic | 31       | 2.23%   |
| 5.11.0-34-generic | 31       | 2.23%   |
| 5.15.0-78-generic | 30       | 2.15%   |
| 5.15.0-53-generic | 29       | 2.08%   |
| 5.13.0-35-generic | 28       | 2.01%   |
| 5.15.0-73-generic | 27       | 1.94%   |
| 5.13.0-27-generic | 26       | 1.87%   |
| 5.13.0-41-generic | 25       | 1.79%   |
| 5.13.0-52-generic | 24       | 1.72%   |
| 5.15.0-72-generic | 22       | 1.58%   |
| 5.13.0-44-generic | 21       | 1.51%   |
| 5.13.0-51-generic | 17       | 1.22%   |
| 5.15.0-75-generic | 13       | 0.93%   |
| 5.15.0-43-generic | 13       | 0.93%   |
| 5.11.0-44-generic | 13       | 0.93%   |
| 5.11.0-36-generic | 12       | 0.86%   |
| 5.15.0-57-generic | 11       | 0.79%   |
| 5.13.0-37-generic | 11       | 0.79%   |
| 5.13.0-48-generic | 8        | 0.57%   |
| 5.8.0-53-generic  | 7        | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 593      | 47.06%  |
| 5.11.0  | 334      | 26.51%  |
| 5.13.0  | 293      | 23.25%  |
| 5.8.0   | 25       | 1.98%   |
| 5.4.0   | 2        | 0.16%   |
| 6.3.2   | 1        | 0.08%   |
| 6.2.7   | 1        | 0.08%   |
| 6.1.8   | 1        | 0.08%   |
| 6.1.7   | 1        | 0.08%   |
| 6.0.8   | 1        | 0.08%   |
| 5.19.6  | 1        | 0.08%   |
| 5.19.2  | 1        | 0.08%   |
| 5.19.12 | 1        | 0.08%   |
| 5.17.9  | 1        | 0.08%   |
| 5.17.5  | 1        | 0.08%   |
| 5.17.1  | 1        | 0.08%   |
| 5.15.13 | 1        | 0.08%   |
| 5.14.0  | 1        | 0.08%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 594      | 47.18%  |
| 5.11    | 334      | 26.53%  |
| 5.13    | 293      | 23.27%  |
| 5.8     | 25       | 1.99%   |
| 5.19    | 3        | 0.24%   |
| 5.17    | 3        | 0.24%   |
| 5.4     | 2        | 0.16%   |
| 6.3     | 1        | 0.08%   |
| 6.2     | 1        | 0.08%   |
| 6.1     | 1        | 0.08%   |
| 6.0     | 1        | 0.08%   |
| 5.14    | 1        | 0.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 1205     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 1053     | 86.88%  |
| XFCE       | 149      | 12.29%  |
| Unknown    | 5        | 0.41%   |
| Cinnamon   | 2        | 0.17%   |
| X-Cinnamon | 1        | 0.08%   |
| MATE       | 1        | 0.08%   |
| KDE5       | 1        | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 1195     | 98.84%  |
| Wayland | 12       | 0.99%   |
| Tty     | 1        | 0.08%   |
| Unknown | 1        | 0.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1015     | 83.2%   |
| GDM3    | 88       | 7.21%   |
| GDM     | 86       | 7.05%   |
| LightDM | 30       | 2.46%   |
| TDM     | 1        | 0.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 490      | 40.56%  |
| de_DE | 119      | 9.85%   |
| en_GB | 88       | 7.28%   |
| pt_BR | 84       | 6.95%   |
| fr_FR | 37       | 3.06%   |
| it_IT | 31       | 2.57%   |
| en_CA | 31       | 2.57%   |
| pl_PL | 28       | 2.32%   |
| en_AU | 26       | 2.15%   |
| es_ES | 24       | 1.99%   |
| en_IN | 24       | 1.99%   |
| nl_NL | 21       | 1.74%   |
| es_AR | 18       | 1.49%   |
| ru_RU | 17       | 1.41%   |
| es_MX | 13       | 1.08%   |
| en_ZA | 13       | 1.08%   |
| hu_HU | 12       | 0.99%   |
| pt_PT | 9        | 0.75%   |
| cs_CZ | 9        | 0.75%   |
| nl_BE | 7        | 0.58%   |
| fr_CA | 7        | 0.58%   |
| tr_TR | 6        | 0.5%    |
| sv_SE | 6        | 0.5%    |
| nb_NO | 5        | 0.41%   |
| en_NZ | 5        | 0.41%   |
| sk_SK | 4        | 0.33%   |
| ja_JP | 4        | 0.33%   |
| fi_FI | 4        | 0.33%   |
| es_VE | 4        | 0.33%   |
| es_CL | 4        | 0.33%   |
| el_GR | 4        | 0.33%   |
| da_DK | 4        | 0.33%   |
| sl_SI | 3        | 0.25%   |
| en_PH | 3        | 0.25%   |
| de_CH | 3        | 0.25%   |
| ar_EG | 3        | 0.25%   |
| zh_CN | 2        | 0.17%   |
| fr_BE | 2        | 0.17%   |
| es_US | 2        | 0.17%   |
| es_GT | 2        | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 645      | 53.04%  |
| EFI  | 571      | 46.96%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 1131     | 93.47%  |
| Zfs      | 26       | 2.15%   |
| Overlay  | 17       | 1.4%    |
| Tmpfs    | 14       | 1.16%   |
| Btrfs    | 11       | 0.91%   |
| Xfs      | 5        | 0.41%   |
| Ext2     | 3        | 0.25%   |
| Ext3     | 2        | 0.17%   |
| Reiserfs | 1        | 0.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1067     | 87.67%  |
| GPT     | 95       | 7.81%   |
| MBR     | 55       | 4.52%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1169     | 96.77%  |
| Yes       | 39       | 3.23%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1087     | 89.91%  |
| Yes       | 122      | 10.09%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 281      | 23.32%  |
| Gigabyte Technology | 192      | 15.93%  |
| Dell                | 129      | 10.71%  |
| MSI                 | 126      | 10.46%  |
| Hewlett-Packard     | 120      | 9.96%   |
| ASRock              | 87       | 7.22%   |
| Lenovo              | 53       | 4.4%    |
| Intel               | 33       | 2.74%   |
| Acer                | 20       | 1.66%   |
| Biostar             | 18       | 1.49%   |
| Unknown             | 17       | 1.41%   |
| Fujitsu             | 16       | 1.33%   |
| Pegatron            | 15       | 1.24%   |
| Foxconn             | 15       | 1.24%   |
| Positivo            | 4        | 0.33%   |
| OEM                 | 4        | 0.33%   |
| Google              | 4        | 0.33%   |
| ECS                 | 4        | 0.33%   |
| BESSTAR Tech        | 4        | 0.33%   |
| Apple               | 4        | 0.33%   |
| Alienware           | 4        | 0.33%   |
| Medion              | 3        | 0.25%   |
| Huanan              | 3        | 0.25%   |
| Gateway             | 3        | 0.25%   |
| AZW                 | 3        | 0.25%   |
| Shuttle             | 2        | 0.17%   |
| QIYIDA              | 2        | 0.17%   |
| PCWare              | 2        | 0.17%   |
| Packard Bell        | 2        | 0.17%   |
| MAXSUN              | 2        | 0.17%   |
| JGINYUE             | 2        | 0.17%   |
| eMachines           | 2        | 0.17%   |
| Wortmann AG         | 1        | 0.08%   |
| WIPRO               | 1        | 0.08%   |
| Win Element         | 1        | 0.08%   |
| Vorke               | 1        | 0.08%   |
| TYAN Computer       | 1        | 0.08%   |
| System76            | 1        | 0.08%   |
| Supermicro          | 1        | 0.08%   |
| Soncview            | 1        | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 31       | 2.57%   |
| Unknown                          | 18       | 1.49%   |
| Dell OptiPlex 7010               | 12       | 1%      |
| MSI MS-7817                      | 8        | 0.66%   |
| Dell OptiPlex 790                | 8        | 0.66%   |
| Dell OptiPlex 780                | 7        | 0.58%   |
| MSI MS-7C02                      | 6        | 0.5%    |
| Gigabyte A320M-S2H               | 6        | 0.5%    |
| Dell OptiPlex 380                | 6        | 0.5%    |
| ASUS M5A78L-M/USB3               | 6        | 0.5%    |
| HP Compaq Pro 6300 SFF           | 5        | 0.41%   |
| Gigabyte B450 AORUS M            | 5        | 0.41%   |
| Dell Precision WorkStation T3500 | 5        | 0.41%   |
| Dell OptiPlex 990                | 5        | 0.41%   |
| Dell OptiPlex 3020               | 5        | 0.41%   |
| Dell OptiPlex 3010               | 5        | 0.41%   |
| ASUS M5A97 R2.0                  | 5        | 0.41%   |
| MSI MS-7C37                      | 4        | 0.33%   |
| MSI MS-7B86                      | 4        | 0.33%   |
| Intel X79M-S                     | 4        | 0.33%   |
| Intel H61                        | 4        | 0.33%   |
| Intel H55                        | 4        | 0.33%   |
| HP ProDesk 600 G1 SFF            | 4        | 0.33%   |
| HP Compaq Elite 8300 SFF         | 4        | 0.33%   |
| Gigabyte X570 AORUS ELITE        | 4        | 0.33%   |
| Gigabyte GA-78LMT-USB3 6.0       | 4        | 0.33%   |
| Gigabyte GA-78LMT-S2             | 4        | 0.33%   |
| Dell OptiPlex 7040               | 4        | 0.33%   |
| Dell OptiPlex 360                | 4        | 0.33%   |
| ASUS TUF Gaming X570-PLUS        | 4        | 0.33%   |
| ASUS PRIME X370-PRO              | 4        | 0.33%   |
| ASRock B450 Pro4                 | 4        | 0.33%   |
| OEM G41 775 ICH7 8712            | 3        | 0.25%   |
| MSI MS-7C91                      | 3        | 0.25%   |
| MSI MS-7B89                      | 3        | 0.25%   |
| HP ProDesk 600 G1 TWR            | 3        | 0.25%   |
| HP EliteDesk 800 G1 USDT         | 3        | 0.25%   |
| HP Compaq Pro 6300 MT            | 3        | 0.25%   |
| HP Compaq 6200 Pro SFF PC        | 3        | 0.25%   |
| Gigabyte M68MT-S2                | 3        | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 83       | 6.89%   |
| ASUS PRIME             | 43       | 3.57%   |
| ASUS ROG               | 36       | 2.99%   |
| Lenovo ThinkCentre     | 35       | 2.9%    |
| HP Compaq              | 33       | 2.74%   |
| ASUS All               | 31       | 2.57%   |
| ASUS TUF               | 28       | 2.32%   |
| Unknown                | 18       | 1.49%   |
| HP EliteDesk           | 17       | 1.41%   |
| Dell Precision         | 15       | 1.24%   |
| Gigabyte B450          | 12       | 1%      |
| Fujitsu ESPRIMO        | 12       | 1%      |
| HP ProDesk             | 11       | 0.91%   |
| HP Pavilion            | 11       | 0.91%   |
| Dell Inspiron          | 10       | 0.83%   |
| Gigabyte X570          | 9        | 0.75%   |
| ASUS M5A97             | 9        | 0.75%   |
| ASUS M5A78L-M          | 9        | 0.75%   |
| Acer Aspire            | 9        | 0.75%   |
| MSI MS-7817            | 8        | 0.66%   |
| Gigabyte GA-78LMT-USB3 | 7        | 0.58%   |
| Gigabyte B450M         | 7        | 0.58%   |
| Gigabyte A320M-S2H     | 7        | 0.58%   |
| ASRock B450M           | 7        | 0.58%   |
| ASRock B450            | 7        | 0.58%   |
| MSI MS-7C02            | 6        | 0.5%    |
| Lenovo IdeaCentre      | 6        | 0.5%    |
| Dell XPS               | 6        | 0.5%    |
| ASUS P8H61-M           | 6        | 0.5%    |
| Gigabyte B550M         | 5        | 0.41%   |
| Dell Vostro            | 5        | 0.41%   |
| MSI MS-7C37            | 4        | 0.33%   |
| MSI MS-7B86            | 4        | 0.33%   |
| Intel X79M-S           | 4        | 0.33%   |
| Intel H61              | 4        | 0.33%   |
| Intel H55              | 4        | 0.33%   |
| Gigabyte GA-78LMT-S2   | 4        | 0.33%   |
| Gigabyte B550          | 4        | 0.33%   |
| ASUS P8Z77-V           | 4        | 0.33%   |
| ASUS P5K               | 4        | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2013    | 116      | 9.63%   |
| 2012    | 116      | 9.63%   |
| 2018    | 109      | 9.05%   |
| 2011    | 100      | 8.3%    |
| 2014    | 93       | 7.72%   |
| 2020    | 85       | 7.05%   |
| 2019    | 81       | 6.72%   |
| 2021    | 74       | 6.14%   |
| 2010    | 70       | 5.81%   |
| 2017    | 68       | 5.64%   |
| 2008    | 56       | 4.65%   |
| 2009    | 55       | 4.56%   |
| 2016    | 48       | 3.98%   |
| 2015    | 40       | 3.32%   |
| 2022    | 35       | 2.9%    |
| 2007    | 30       | 2.49%   |
| 2006    | 12       | 1%      |
| 2023    | 8        | 0.66%   |
| 2005    | 6        | 0.5%    |
| Unknown | 3        | 0.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 1205     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 1130     | 93.39%  |
| Enabled  | 80       | 6.61%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1201     | 99.67%  |
| Yes  | 4        | 0.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 305      | 24.92%  |
| 8.01-16.0       | 268      | 21.9%   |
| 4.01-8.0        | 194      | 15.85%  |
| 3.01-4.0        | 172      | 14.05%  |
| 32.01-64.0      | 171      | 13.97%  |
| 64.01-256.0     | 42       | 3.43%   |
| 24.01-32.0      | 29       | 2.37%   |
| 1.01-2.0        | 26       | 2.12%   |
| 2.01-3.0        | 14       | 1.14%   |
| 0.51-1.0        | 2        | 0.16%   |
| More than 256.0 | 1        | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 477      | 36.38%  |
| 2.01-3.0   | 410      | 31.27%  |
| 3.01-4.0   | 183      | 13.96%  |
| 4.01-8.0   | 182      | 13.88%  |
| 8.01-16.0  | 31       | 2.36%   |
| 0.51-1.0   | 18       | 1.37%   |
| 16.01-24.0 | 6        | 0.46%   |
| 32.01-64.0 | 2        | 0.15%   |
| 24.01-32.0 | 1        | 0.08%   |
| 0.01-0.5   | 1        | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 551      | 44.4%   |
| 2      | 347      | 27.96%  |
| 3      | 156      | 12.57%  |
| 4      | 86       | 6.93%   |
| 5      | 47       | 3.79%   |
| 6      | 29       | 2.34%   |
| 7      | 10       | 0.81%   |
| 8      | 7        | 0.56%   |
| 0      | 6        | 0.48%   |
| 51     | 1        | 0.08%   |
| 11     | 1        | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 613      | 50.62%  |
| Yes       | 598      | 49.38%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1190     | 98.76%  |
| No        | 15       | 1.24%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 620      | 50.94%  |
| No        | 597      | 49.06%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 806      | 66.28%  |
| Yes       | 410      | 33.72%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 312      | 25.81%  |
| Germany      | 124      | 10.26%  |
| Brazil       | 91       | 7.53%   |
| UK           | 84       | 6.95%   |
| Canada       | 42       | 3.47%   |
| Italy        | 40       | 3.31%   |
| Netherlands  | 35       | 2.89%   |
| France       | 34       | 2.81%   |
| Poland       | 32       | 2.65%   |
| Australia    | 27       | 2.23%   |
| Spain        | 25       | 2.07%   |
| India        | 24       | 1.99%   |
| Argentina    | 20       | 1.65%   |
| Mexico       | 17       | 1.41%   |
| Hungary      | 16       | 1.32%   |
| Russia       | 15       | 1.24%   |
| Belgium      | 15       | 1.24%   |
| South Africa | 13       | 1.08%   |
| Denmark      | 13       | 1.08%   |
| Sweden       | 12       | 0.99%   |
| Portugal     | 12       | 0.99%   |
| Norway       | 11       | 0.91%   |
| Czechia      | 10       | 0.83%   |
| Switzerland  | 9        | 0.74%   |
| Greece       | 9        | 0.74%   |
| Egypt        | 9        | 0.74%   |
| Turkey       | 8        | 0.66%   |
| Malaysia     | 8        | 0.66%   |
| Chile        | 7        | 0.58%   |
| Venezuela    | 6        | 0.5%    |
| Slovenia     | 6        | 0.5%    |
| Slovakia     | 6        | 0.5%    |
| Serbia       | 6        | 0.5%    |
| Romania      | 6        | 0.5%    |
| New Zealand  | 6        | 0.5%    |
| Finland      | 6        | 0.5%    |
| Japan        | 5        | 0.41%   |
| Indonesia    | 5        | 0.41%   |
| Croatia      | 4        | 0.33%   |
| Colombia     | 4        | 0.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Berlin         | 11       | 0.88%   |
| Munich         | 10       | 0.8%    |
| Rio de Janeiro | 8        | 0.64%   |
| Milan          | 7        | 0.56%   |
| Cape Town      | 7        | 0.56%   |
| Athens         | 7        | 0.56%   |
| Sao Paulo      | 6        | 0.48%   |
| Houston        | 6        | 0.48%   |
| Denver         | 6        | 0.48%   |
| Phoenix        | 5        | 0.4%    |
| Perth          | 5        | 0.4%    |
| Dallas         | 5        | 0.4%    |
| Copenhagen     | 5        | 0.4%    |
| Buenos Aires   | 5        | 0.4%    |
| Adelaide       | 5        | 0.4%    |
| Sydney         | 4        | 0.32%   |
| Rome           | 4        | 0.32%   |
| Richmond       | 4        | 0.32%   |
| Prague         | 4        | 0.32%   |
| Portland       | 4        | 0.32%   |
| Melbourne      | 4        | 0.32%   |
| Johannesburg   | 4        | 0.32%   |
| Hamburg        | 4        | 0.32%   |
| Dayton         | 4        | 0.32%   |
| Calgary        | 4        | 0.32%   |
| Budapest       | 4        | 0.32%   |
| Brussels       | 4        | 0.32%   |
| Brasília      | 4        | 0.32%   |
| Bengaluru      | 4        | 0.32%   |
| Atlanta        | 4        | 0.32%   |
| Zurich         | 3        | 0.24%   |
| Warsaw         | 3        | 0.24%   |
| Vienna         | 3        | 0.24%   |
| Tijuana        | 3        | 0.24%   |
| The Hague      | 3        | 0.24%   |
| Stuttgart      | 3        | 0.24%   |
| Santo André   | 3        | 0.24%   |
| Santiago       | 3        | 0.24%   |
| Salt Lake City | 3        | 0.24%   |
| Recife         | 3        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 425      | 661    | 19.78%  |
| WDC                         | 352      | 520    | 16.38%  |
| Samsung Electronics         | 277      | 425    | 12.89%  |
| Kingston                    | 131      | 185    | 6.1%    |
| Toshiba                     | 121      | 186    | 5.63%   |
| Sandisk                     | 116      | 146    | 5.4%    |
| Crucial                     | 87       | 107    | 4.05%   |
| Hitachi                     | 84       | 109    | 3.91%   |
| A-DATA Technology           | 33       | 43     | 1.54%   |
| China                       | 31       | 33     | 1.44%   |
| Unknown                     | 25       | 42     | 1.16%   |
| Silicon Motion              | 24       | 32     | 1.12%   |
| Intel                       | 24       | 28     | 1.12%   |
| Phison                      | 20       | 22     | 0.93%   |
| Intenso                     | 17       | 19     | 0.79%   |
| HGST                        | 17       | 25     | 0.79%   |
| SK hynix                    | 16       | 21     | 0.74%   |
| PNY                         | 15       | 20     | 0.7%    |
| Patriot                     | 14       | 20     | 0.65%   |
| Micron/Crucial Technology   | 12       | 14     | 0.56%   |
| Maxtor                      | 12       | 16     | 0.56%   |
| SPCC                        | 11       | 14     | 0.51%   |
| OCZ                         | 11       | 13     | 0.51%   |
| Lexar                       | 11       | 11     | 0.51%   |
| JMicron Technology          | 11       | 13     | 0.51%   |
| GOODRAM                     | 11       | 14     | 0.51%   |
| Micron Technology           | 10       | 10     | 0.47%   |
| Phison Electronics          | 9        | 11     | 0.42%   |
| Gigabyte Technology         | 9        | 11     | 0.42%   |
| Realtek Semiconductor       | 8        | 8      | 0.37%   |
| KingSpec                    | 8        | 10     | 0.37%   |
| Hewlett-Packard             | 8        | 12     | 0.37%   |
| HS-SSD-C100                 | 7        | 7      | 0.33%   |
| Apple                       | 7        | 8      | 0.33%   |
| Unknown                     | 7        | 8      | 0.33%   |
| XPG                         | 6        | 7      | 0.28%   |
| Team                        | 6        | 8      | 0.28%   |
| Netac                       | 6        | 9      | 0.28%   |
| MAXIO Technology (Hangzhou) | 6        | 6      | 0.28%   |
| Apacer                      | 6        | 8      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB                     | 44       | 1.78%   |
| Kingston SA400S37240G 240GB SSD                     | 33       | 1.34%   |
| Seagate ST1000DM010-2EP102 1TB                      | 26       | 1.05%   |
| Samsung SSD 860 EVO 500GB                           | 22       | 0.89%   |
| Crucial CT240BX500SSD1 240GB                        | 22       | 0.89%   |
| Toshiba HDWD110 1TB                                 | 18       | 0.73%   |
| Seagate ST1000DM003-1CH162 1TB                      | 18       | 0.73%   |
| Samsung SSD 850 EVO 250GB                           | 18       | 0.73%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 17       | 0.69%   |
| Samsung NVMe SSD Drive 1TB                          | 17       | 0.69%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 17       | 0.69%   |
| Seagate ST2000DM008-2FR102 2TB                      | 16       | 0.65%   |
| Kingston SA400S37120G 120GB SSD                     | 16       | 0.65%   |
| Seagate ST3500418AS 500GB                           | 15       | 0.61%   |
| Kingston SA400S37480G 480GB SSD                     | 15       | 0.61%   |
| Toshiba DT01ACA100 1TB                              | 14       | 0.57%   |
| Samsung NVMe SSD Drive 500GB                        | 14       | 0.57%   |
| Seagate ST2000DM001-1ER164 2TB                      | 13       | 0.53%   |
| Toshiba DT01ACA050 500GB                            | 12       | 0.49%   |
| Seagate ST3500413AS 500GB                           | 12       | 0.49%   |
| Seagate ST1000DM003-1SB102 1TB                      | 12       | 0.49%   |
| Seagate ST1000DM003-1ER162 1TB                      | 12       | 0.49%   |
| Crucial CT500MX500SSD1 500GB                        | 12       | 0.49%   |
| Crucial CT1000MX500SSD1 1TB                         | 12       | 0.49%   |
| Unknown SD/MMC/MS PRO 128GB                         | 11       | 0.45%   |
| Seagate ST3500312CS 500GB                           | 11       | 0.45%   |
| SanDisk NVMe SSD Drive 500GB                        | 11       | 0.45%   |
| SanDisk NVMe SSD Drive 1TB                          | 11       | 0.45%   |
| Samsung SSD 870 EVO 1TB                             | 11       | 0.45%   |
| Samsung SSD 850 EVO 500GB                           | 11       | 0.45%   |
| Kingston SV300S37A120G 120GB SSD                    | 11       | 0.45%   |
| Seagate ST4000DM004-2CV104 4TB                      | 10       | 0.4%    |
| Seagate ST2000DM001-1CH164 2TB                      | 10       | 0.4%    |
| Samsung HD103SJ 1TB                                 | 10       | 0.4%    |
| SanDisk SSD PLUS 240GB                              | 9        | 0.36%   |
| Samsung SSD 840 EVO 250GB                           | 9        | 0.36%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 9        | 0.36%   |
| Crucial CT2000MX500SSD1 2TB                         | 9        | 0.36%   |
| WDC WD10EZEX-00WN4A0 1TB                            | 8        | 0.32%   |
| Toshiba MQ01ABD100 1TB                              | 8        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 419      | 642    | 39.72%  |
| WDC                 | 320      | 463    | 30.33%  |
| Toshiba             | 105      | 167    | 9.95%   |
| Hitachi             | 84       | 109    | 7.96%   |
| Samsung Electronics | 62       | 81     | 5.88%   |
| HGST                | 17       | 25     | 1.61%   |
| Maxtor              | 12       | 16     | 1.14%   |
| Unknown             | 11       | 15     | 1.04%   |
| JMicron Technology  | 8        | 9      | 0.76%   |
| Apple               | 5        | 6      | 0.47%   |
| Super Talent        | 3        | 4      | 0.28%   |
| Hewlett-Packard     | 3        | 6      | 0.28%   |
| USB3.0              | 2        | 3      | 0.19%   |
| QUANTUM             | 1        | 1      | 0.09%   |
| Intenso             | 1        | 1      | 0.09%   |
| External            | 1        | 1      | 0.09%   |
| ACASIS              | 1        | 1      | 0.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 150      | 214    | 19.84%  |
| Kingston            | 109      | 145    | 14.42%  |
| Crucial             | 83       | 103    | 10.98%  |
| SanDisk             | 71       | 87     | 9.39%   |
| WDC                 | 38       | 48     | 5.03%   |
| China               | 31       | 33     | 4.1%    |
| A-DATA Technology   | 31       | 41     | 4.1%    |
| PNY                 | 15       | 20     | 1.98%   |
| Intel               | 14       | 16     | 1.85%   |
| Patriot             | 13       | 19     | 1.72%   |
| Intenso             | 12       | 14     | 1.59%   |
| Toshiba             | 11       | 13     | 1.46%   |
| SPCC                | 11       | 14     | 1.46%   |
| OCZ                 | 11       | 13     | 1.46%   |
| Lexar               | 11       | 11     | 1.46%   |
| GOODRAM             | 10       | 13     | 1.32%   |
| SK hynix            | 7        | 7      | 0.93%   |
| Micron Technology   | 7        | 7      | 0.93%   |
| KingSpec            | 7        | 9      | 0.93%   |
| Gigabyte Technology | 7        | 8      | 0.93%   |
| Team                | 6        | 8      | 0.79%   |
| Netac               | 6        | 8      | 0.79%   |
| Apacer              | 6        | 8      | 0.79%   |
| Leven               | 5        | 6      | 0.66%   |
| Hewlett-Packard     | 5        | 6      | 0.66%   |
| Unknown             | 4        | 5      | 0.53%   |
| Transcend           | 3        | 3      | 0.4%    |
| Seagate             | 3        | 6      | 0.4%    |
| LITEON              | 3        | 3      | 0.4%    |
| KIOXIA-EXCERIA      | 3        | 7      | 0.4%    |
| Corsair             | 3        | 8      | 0.4%    |
| Acer                | 3        | 5      | 0.4%    |
| Verbatim            | 2        | 2      | 0.26%   |
| Plextor             | 2        | 3      | 0.26%   |
| Pioneer             | 2        | 2      | 0.26%   |
| NN                  | 2        | 3      | 0.26%   |
| Kimtigo             | 2        | 2      | 0.26%   |
| FORESEE             | 2        | 3      | 0.26%   |
| Drevo               | 2        | 3      | 0.26%   |
| Dogfish             | 2        | 3      | 0.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 817      | 1550   | 44.99%  |
| SSD     | 634      | 979    | 34.91%  |
| NVMe    | 297      | 422    | 16.35%  |
| Unknown | 61       | 80     | 3.36%   |
| MMC     | 7        | 8      | 0.39%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 1113     | 2473   | 73.76%  |
| NVMe | 294      | 417    | 19.48%  |
| SAS  | 95       | 141    | 6.3%    |
| MMC  | 7        | 8      | 0.46%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 825      | 1383   | 53.19%  |
| 0.51-1.0   | 438      | 675    | 28.24%  |
| 1.01-2.0   | 167      | 240    | 10.77%  |
| 3.01-4.0   | 47       | 105    | 3.03%   |
| 4.01-10.0  | 41       | 64     | 2.64%   |
| 2.01-3.0   | 29       | 43     | 1.87%   |
| 10.01-20.0 | 4        | 19     | 0.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 367      | 29.06%  |
| 251-500        | 285      | 22.57%  |
| 501-1000       | 207      | 16.39%  |
| 1001-2000      | 131      | 10.37%  |
| More than 3000 | 88       | 6.97%   |
| 51-100         | 70       | 5.54%   |
| 2001-3000      | 43       | 3.4%    |
| 1-20           | 29       | 2.3%    |
| 21-50          | 26       | 2.06%   |
| Unknown        | 17       | 1.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 436      | 33.13%  |
| 21-50          | 336      | 25.53%  |
| 51-100         | 161      | 12.23%  |
| 101-250        | 128      | 9.73%   |
| 251-500        | 82       | 6.23%   |
| 501-1000       | 66       | 5.02%   |
| More than 3000 | 44       | 3.34%   |
| 1001-2000      | 34       | 2.58%   |
| Unknown        | 17       | 1.29%   |
| 2001-3000      | 12       | 0.91%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| HGST HTS541010A9E680 1TB                 | 2        | 2      | 5%      |
| WDC WD5000LPCX-60VHAT0 500GB             | 1        | 1      | 2.5%    |
| WDC WD3200AAKS-22B3A0 320GB              | 1        | 1      | 2.5%    |
| WDC WD30EFRX-68EUZN0 3TB                 | 1        | 1      | 2.5%    |
| WDC WD10EZEX-21M2NA0 1TB                 | 1        | 2      | 2.5%    |
| WDC WD10EURX-63FH1Y0 1TB                 | 1        | 1      | 2.5%    |
| WDC WD Green 2.5 1000GB                  | 1        | 1      | 2.5%    |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1        | 1      | 2.5%    |
| Toshiba MQ01ABD100 1TB                   | 1        | 1      | 2.5%    |
| Toshiba MK8046GSX 80GB                   | 1        | 1      | 2.5%    |
| Toshiba MK3265GSX 320GB                  | 1        | 1      | 2.5%    |
| Toshiba MG03ACA200 2TB                   | 1        | 1      | 2.5%    |
| Toshiba DT01ACA100 1TB                   | 1        | 1      | 2.5%    |
| Silicon Motion Inland NVMe SSD 256GB     | 1        | 1      | 2.5%    |
| Seagate ST9500420AS 500GB                | 1        | 1      | 2.5%    |
| Seagate ST8000DM004-2CX188 8TB           | 1        | 1      | 2.5%    |
| Seagate ST500DM002-1BD142 500GB          | 1        | 1      | 2.5%    |
| Seagate ST4000DM004-2CV104 4TB           | 1        | 1      | 2.5%    |
| Seagate ST3500514NS 500GB                | 1        | 1      | 2.5%    |
| Seagate ST3500413AS 500GB                | 1        | 1      | 2.5%    |
| Seagate ST3500312CS 500GB                | 1        | 1      | 2.5%    |
| Seagate ST3360320AS 360GB                | 1        | 1      | 2.5%    |
| Seagate ST3320620AS 320GB                | 1        | 1      | 2.5%    |
| Seagate ST3250318AS 250GB                | 1        | 1      | 2.5%    |
| Seagate ST320LT012-1DG14C 320GB          | 1        | 1      | 2.5%    |
| Seagate ST3160310CS 160GB                | 1        | 1      | 2.5%    |
| Seagate ST2000LM003 HN-M201RAD 2TB       | 1        | 1      | 2.5%    |
| Seagate ST2000DX002-2DV164 2TB           | 1        | 1      | 2.5%    |
| Seagate ST2000DM008-2FR102 2TB           | 1        | 1      | 2.5%    |
| Seagate ST2000DM001-9YN164 2TB           | 1        | 1      | 2.5%    |
| Seagate ST2000DL003-9VT166 2TB           | 1        | 1      | 2.5%    |
| Samsung Electronics HD154UI 1TB          | 1        | 1      | 2.5%    |
| OCZ VERTEX3 120GB SSD                    | 1        | 1      | 2.5%    |
| Maxtor STM3320613AS 320GB                | 1        | 1      | 2.5%    |
| Kingston SV300S37A120G 120GB SSD         | 1        | 1      | 2.5%    |
| Kingston SNS4151S316GD 16GB SSD          | 1        | 1      | 2.5%    |
| Intel SSDSC2CW060A3 64GB                 | 1        | 1      | 2.5%    |
| A-DATA Technology SX8200PNP 256GB        | 1        | 1      | 2.5%    |
| A-DATA Technology SU630 240GB SSD        | 1        | 1      | 2.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 16       | 17     | 41.03%  |
| WDC                 | 6        | 7      | 15.38%  |
| Toshiba             | 6        | 6      | 15.38%  |
| Kingston            | 2        | 2      | 5.13%   |
| HGST                | 2        | 2      | 5.13%   |
| A-DATA Technology   | 2        | 2      | 5.13%   |
| Silicon Motion      | 1        | 1      | 2.56%   |
| Samsung Electronics | 1        | 1      | 2.56%   |
| OCZ                 | 1        | 1      | 2.56%   |
| Maxtor              | 1        | 1      | 2.56%   |
| Intel               | 1        | 1      | 2.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 16       | 17     | 53.33%  |
| WDC                 | 5        | 6      | 16.67%  |
| Toshiba             | 5        | 5      | 16.67%  |
| HGST                | 2        | 2      | 6.67%   |
| Samsung Electronics | 1        | 1      | 3.33%   |
| Maxtor              | 1        | 1      | 3.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 26       | 32     | 74.29%  |
| SSD  | 7        | 7      | 20%     |
| NVMe | 2        | 2      | 5.71%   |

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
| Detected | 1113     | 2721   | 88.76%  |
| Works    | 106      | 277    | 8.45%   |
| Malfunc  | 35       | 41     | 2.79%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 787      | 48.25%  |
| AMD                            | 382      | 23.42%  |
| Samsung Electronics            | 95       | 5.82%   |
| SanDisk                        | 54       | 3.31%   |
| ASMedia Technology             | 45       | 2.76%   |
| Phison Electronics             | 31       | 1.9%    |
| JMicron Technology             | 31       | 1.9%    |
| Nvidia                         | 30       | 1.84%   |
| Kingston Technology Company    | 30       | 1.84%   |
| Silicon Motion                 | 26       | 1.59%   |
| Marvell Technology Group       | 24       | 1.47%   |
| Micron/Crucial Technology      | 16       | 0.98%   |
| ADATA Technology               | 11       | 0.67%   |
| SK hynix                       | 8        | 0.49%   |
| Realtek Semiconductor          | 8        | 0.49%   |
| Silicon Image                  | 7        | 0.43%   |
| Seagate Technology             | 7        | 0.43%   |
| VIA Technologies               | 6        | 0.37%   |
| MAXIO Technology (Hangzhou)    | 6        | 0.37%   |
| KIOXIA                         | 5        | 0.31%   |
| Toshiba America Info Systems   | 4        | 0.25%   |
| Micron Technology              | 3        | 0.18%   |
| Broadcom / LSI                 | 3        | 0.18%   |
| INNOGRIT                       | 2        | 0.12%   |
| TenaFe                         | 1        | 0.06%   |
| Solid State Storage Technology | 1        | 0.06%   |
| Shenzhen Longsys Electronics   | 1        | 0.06%   |
| OCZ Technology Group           | 1        | 0.06%   |
| Netac Technology               | 1        | 0.06%   |
| Lite-On Technology             | 1        | 0.06%   |
| Integrated Technology Express  | 1        | 0.06%   |
| HighPoint Technologies         | 1        | 0.06%   |
| Beijing Starblaze Technology   | 1        | 0.06%   |
| Apple                          | 1        | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 207      | 10.06%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 120      | 5.83%   |
| AMD 400 Series Chipset SATA Controller                                                  | 78       | 3.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 76       | 3.69%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 67       | 3.26%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 66       | 3.21%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 61       | 2.96%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 55       | 2.67%   |
| Intel SATA Controller [RAID mode]                                                       | 54       | 2.62%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 52       | 2.53%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 48       | 2.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 44       | 2.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 44       | 2.14%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 41       | 1.99%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 41       | 1.99%   |
| AMD 500 Series Chipset SATA Controller                                                  | 40       | 1.94%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 31       | 1.51%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 30       | 1.46%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 29       | 1.41%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 28       | 1.36%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 24       | 1.17%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 21       | 1.02%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 21       | 1.02%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 20       | 0.97%   |
| AMD FCH SATA Controller D                                                               | 18       | 0.87%   |
| AMD 300 Series Chipset SATA Controller                                                  | 18       | 0.87%   |
| Nvidia MCP61 SATA Controller                                                            | 17       | 0.83%   |
| Phison E12 NVMe Controller                                                              | 16       | 0.78%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 16       | 0.78%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 15       | 0.73%   |
| Kingston Company A2000 NVMe SSD                                                         | 15       | 0.73%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 15       | 0.73%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 14       | 0.68%   |
| Samsung NVMe SSD Controller 980                                                         | 13       | 0.63%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 13       | 0.63%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 13       | 0.63%   |
| Nvidia MCP61 IDE                                                                        | 12       | 0.58%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 12       | 0.58%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 12       | 0.58%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 11       | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 963      | 57.84%  |
| IDE  | 310      | 18.62%  |
| NVMe | 293      | 17.6%   |
| RAID | 91       | 5.47%   |
| SAS  | 5        | 0.3%    |
| SCSI | 3        | 0.18%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 796      | 66.06%  |
| AMD    | 409      | 33.94%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 27       | 2.23%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 24       | 1.99%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 20       | 1.65%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 18       | 1.49%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 15       | 1.24%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 14       | 1.16%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 14       | 1.16%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 13       | 1.08%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 13       | 1.08%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 12       | 0.99%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 11       | 0.91%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 11       | 0.91%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 11       | 0.91%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 11       | 0.91%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 11       | 0.91%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 10       | 0.83%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 10       | 0.83%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 10       | 0.83%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 10       | 0.83%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 10       | 0.83%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 9        | 0.74%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 9        | 0.74%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 9        | 0.74%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 9        | 0.74%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 9        | 0.74%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 8        | 0.66%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 8        | 0.66%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 8        | 0.66%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 8        | 0.66%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 8        | 0.66%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz      | 7        | 0.58%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 7        | 0.58%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 7        | 0.58%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 7        | 0.58%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 7        | 0.58%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 7        | 0.58%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 7        | 0.58%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 7        | 0.58%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 7        | 0.58%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 7        | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 242      | 20.05%  |
| Intel Core i7           | 135      | 11.18%  |
| Intel Core i3           | 108      | 8.95%   |
| AMD Ryzen 5             | 108      | 8.95%   |
| Intel Xeon              | 64       | 5.3%    |
| AMD Ryzen 7             | 52       | 4.31%   |
| AMD FX                  | 47       | 3.89%   |
| Intel Core 2 Duo        | 39       | 3.23%   |
| AMD Ryzen 9             | 37       | 3.07%   |
| Other                   | 35       | 2.9%    |
| Intel Celeron           | 35       | 2.9%    |
| Intel Core 2 Quad       | 31       | 2.57%   |
| Intel Pentium Dual-Core | 27       | 2.24%   |
| Intel Pentium           | 25       | 2.07%   |
| AMD Ryzen 3             | 22       | 1.82%   |
| AMD Athlon II X2        | 20       | 1.66%   |
| Intel Pentium Dual      | 16       | 1.33%   |
| AMD Phenom II X4        | 13       | 1.08%   |
| AMD A10                 | 13       | 1.08%   |
| Intel Core i9           | 12       | 0.99%   |
| AMD A8                  | 11       | 0.91%   |
| AMD Phenom II X6        | 10       | 0.83%   |
| AMD A6                  | 10       | 0.83%   |
| AMD Athlon 64 X2        | 9        | 0.75%   |
| Intel Core 2            | 8        | 0.66%   |
| Intel Pentium 4         | 7        | 0.58%   |
| AMD Athlon II X4        | 7        | 0.58%   |
| Intel Atom              | 6        | 0.5%    |
| AMD Athlon              | 6        | 0.5%    |
| Intel Pentium Gold      | 5        | 0.41%   |
| AMD Athlon II X3        | 5        | 0.41%   |
| AMD E1                  | 4        | 0.33%   |
| AMD A4                  | 4        | 0.33%   |
| AMD Ryzen 5 PRO         | 3        | 0.25%   |
| AMD PRO A10             | 3        | 0.25%   |
| AMD Phenom              | 3        | 0.25%   |
| AMD GX                  | 3        | 0.25%   |
| Intel Pentium D         | 2        | 0.17%   |
| AMD Sempron             | 2        | 0.17%   |
| AMD E2                  | 2        | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 498      | 41.23%  |
| 2      | 337      | 27.9%   |
| 6      | 173      | 14.32%  |
| 8      | 97       | 8.03%   |
| 12     | 28       | 2.32%   |
| 1      | 24       | 1.99%   |
| 3      | 21       | 1.74%   |
| 16     | 16       | 1.32%   |
| 10     | 11       | 0.91%   |
| 14     | 2        | 0.17%   |
| 28     | 1        | 0.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 1197     | 99.34%  |
| 2      | 8        | 0.66%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 640      | 53.07%  |
| 1      | 566      | 46.93%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 1205     | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 137      | 11.22%  |
| 0x306a9    | 94       | 7.7%    |
| Unknown    | 89       | 7.29%   |
| 0x206a7    | 85       | 6.96%   |
| 0x1067a    | 73       | 5.98%   |
| 0x506e3    | 51       | 4.18%   |
| 0x08701021 | 49       | 4.01%   |
| 0x06000852 | 34       | 2.78%   |
| 0x906ea    | 28       | 2.29%   |
| 0x906e9    | 23       | 1.88%   |
| 0x0800820d | 22       | 1.8%    |
| 0x010000c8 | 22       | 1.8%    |
| 0xa0653    | 21       | 1.72%   |
| 0x6fd      | 19       | 1.56%   |
| 0x0a201016 | 18       | 1.47%   |
| 0xa0655    | 17       | 1.39%   |
| 0x06001119 | 16       | 1.31%   |
| 0x6fb      | 15       | 1.23%   |
| 0x08108109 | 15       | 1.23%   |
| 0x08001138 | 14       | 1.15%   |
| 0x906ed    | 13       | 1.06%   |
| 0x906eb    | 13       | 1.06%   |
| 0x0600063e | 12       | 0.98%   |
| 0x010000dc | 12       | 0.98%   |
| 0xa0671    | 11       | 0.9%    |
| 0x010000db | 11       | 0.9%    |
| 0x206d7    | 10       | 0.82%   |
| 0x20655    | 10       | 0.82%   |
| 0x106e5    | 10       | 0.82%   |
| 0x08701013 | 10       | 0.82%   |
| 0x90672    | 9        | 0.74%   |
| 0x106a5    | 9        | 0.74%   |
| 0x0a50000d | 9        | 0.74%   |
| 0x306f2    | 8        | 0.66%   |
| 0x20652    | 8        | 0.66%   |
| 0x10676    | 8        | 0.66%   |
| 0x0a601203 | 8        | 0.66%   |
| 0x0a201009 | 8        | 0.66%   |
| 0x306e4    | 7        | 0.57%   |
| 0x08101016 | 7        | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 158      | 13.1%   |
| IvyBridge        | 102      | 8.46%   |
| SandyBridge      | 99       | 8.21%   |
| KabyLake         | 88       | 7.3%    |
| Penryn           | 86       | 7.13%   |
| Zen 2            | 74       | 6.14%   |
| Zen 3            | 61       | 5.06%   |
| K10              | 60       | 4.98%   |
| Skylake          | 53       | 4.39%   |
| Piledriver       | 53       | 4.39%   |
| Core             | 46       | 3.81%   |
| Zen              | 41       | 3.4%    |
| CometLake        | 41       | 3.4%    |
| Zen+             | 40       | 3.32%   |
| Westmere         | 24       | 1.99%   |
| Nehalem          | 24       | 1.99%   |
| Unknown          | 23       | 1.91%   |
| K8 Hammer        | 15       | 1.24%   |
| Silvermont       | 13       | 1.08%   |
| Excavator        | 12       | 1%      |
| Bulldozer        | 12       | 1%      |
| Alderlake Hybrid | 12       | 1%      |
| Icelake          | 11       | 0.91%   |
| NetBurst         | 10       | 0.83%   |
| Steamroller      | 7        | 0.58%   |
| Jaguar           | 7        | 0.58%   |
| Puma             | 6        | 0.5%    |
| Broadwell        | 6        | 0.5%    |
| K10 Llano        | 5        | 0.41%   |
| Goldmont plus    | 4        | 0.33%   |
| Bonnell          | 4        | 0.33%   |
| Bobcat           | 4        | 0.33%   |
| Tremont          | 2        | 0.17%   |
| Goldmont         | 2        | 0.17%   |
| TigerLake        | 1        | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 482      | 37.39%  |
| Intel             | 415      | 32.2%   |
| AMD               | 389      | 30.18%  |
| VIA Technologies  | 2        | 0.16%   |
| ASPEED Technology | 1        | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 73       | 5.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 51       | 3.89%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 44       | 3.35%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 41       | 3.13%   |
| Nvidia GK208B [GeForce GT 710]                                              | 30       | 2.29%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 30       | 2.29%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 28       | 2.13%   |
| Intel HD Graphics 530                                                       | 28       | 2.13%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 24       | 1.83%   |
| Nvidia GK208B [GeForce GT 730]                                              | 21       | 1.6%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 20       | 1.52%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 18       | 1.37%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 17       | 1.3%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 17       | 1.3%    |
| Nvidia GF119 [GeForce GT 610]                                               | 16       | 1.22%   |
| Intel HD Graphics 630                                                       | 16       | 1.22%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 16       | 1.22%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 16       | 1.22%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 15       | 1.14%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 14       | 1.07%   |
| Intel Core Processor Integrated Graphics Controller                         | 14       | 1.07%   |
| AMD RS780L [Radeon 3000]                                                    | 13       | 0.99%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 13       | 0.99%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 12       | 0.91%   |
| Nvidia GT218 [GeForce 210]                                                  | 12       | 0.91%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 12       | 0.91%   |
| Nvidia GF108 [GeForce GT 730]                                               | 12       | 0.91%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 11       | 0.84%   |
| Nvidia GF108 [GeForce GT 630]                                               | 10       | 0.76%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 10       | 0.76%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 10       | 0.76%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 10       | 0.76%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 9        | 0.69%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 9        | 0.69%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 8        | 0.61%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 8        | 0.61%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 8        | 0.61%   |
| AMD Raphael                                                                 | 8        | 0.61%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 8        | 0.61%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 8        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 446      | 36.65%  |
| 1 x Intel            | 365      | 29.99%  |
| 1 x AMD              | 357      | 29.33%  |
| AMD + Nvidia         | 12       | 0.99%   |
| 2 x AMD              | 11       | 0.9%    |
| Intel + Nvidia       | 11       | 0.9%    |
| Intel + AMD          | 8        | 0.66%   |
| 2 x Nvidia           | 3        | 0.25%   |
| 1 x VIA              | 2        | 0.16%   |
| 2 x AMD + 1 x Nvidia | 1        | 0.08%   |
| 1 x ASPEED           | 1        | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 841      | 68.99%  |
| Proprietary | 311      | 25.51%  |
| Unknown     | 67       | 5.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 525      | 42.61%  |
| 1.01-2.0   | 154      | 12.5%   |
| 0.51-1.0   | 142      | 11.53%  |
| 0.01-0.5   | 123      | 9.98%   |
| 3.01-4.0   | 107      | 8.69%   |
| 7.01-8.0   | 92       | 7.47%   |
| 8.01-16.0  | 36       | 2.92%   |
| 5.01-6.0   | 32       | 2.6%    |
| 2.01-3.0   | 17       | 1.38%   |
| 16.01-24.0 | 4        | 0.32%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 175      | 14.81%  |
| Dell                 | 115      | 9.73%   |
| Goldstar             | 112      | 9.48%   |
| Hewlett-Packard      | 90       | 7.61%   |
| Acer                 | 79       | 6.68%   |
| AOC                  | 71       | 6.01%   |
| Philips              | 59       | 4.99%   |
| BenQ                 | 46       | 3.89%   |
| Ancor Communications | 43       | 3.64%   |
| LG Electronics       | 28       | 2.37%   |
| ViewSonic            | 23       | 1.95%   |
| Unknown              | 21       | 1.78%   |
| Unknown              | 19       | 1.61%   |
| Lenovo               | 18       | 1.52%   |
| Iiyama               | 15       | 1.27%   |
| Sony                 | 14       | 1.18%   |
| ASUSTek Computer     | 13       | 1.1%    |
| Fujitsu Siemens      | 12       | 1.02%   |
| Sceptre Tech         | 11       | 0.93%   |
| NEC Computers        | 10       | 0.85%   |
| HPN                  | 10       | 0.85%   |
| Eizo                 | 10       | 0.85%   |
| Vizio                | 9        | 0.76%   |
| MSI                  | 8        | 0.68%   |
| Toshiba              | 7        | 0.59%   |
| Microstep            | 6        | 0.51%   |
| FUS                  | 6        | 0.51%   |
| AUS                  | 6        | 0.51%   |
| Panasonic            | 5        | 0.42%   |
| Vestel               | 4        | 0.34%   |
| Medion               | 4        | 0.34%   |
| Lenovo Group Limited | 4        | 0.34%   |
| ITE                  | 4        | 0.34%   |
| Idek Iiyama          | 4        | 0.34%   |
| Envision             | 4        | 0.34%   |
| ___                  | 3        | 0.25%   |
| Unknown (XXX)        | 3        | 0.25%   |
| Sharp                | 3        | 0.25%   |
| Roku                 | 3        | 0.25%   |
| PKB                  | 3        | 0.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown                                                               | 19       | 1.52%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 9        | 0.72%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 6        | 0.48%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 6        | 0.48%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 5        | 0.4%    |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 4        | 0.32%   |
| Philips LCD Monitor FTV 1920x1080                                     | 4        | 0.32%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                   | 4        | 0.32%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                      | 4        | 0.32%   |
| Vestel LCD Monitor 48UHD_LCD_TV 3840x2160                             | 3        | 0.24%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                 | 3        | 0.24%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 3        | 0.24%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch        | 3        | 0.24%   |
| Samsung Electronics U28D590 SAM0B81 3840x2160 608x345mm 27.5-inch     | 3        | 0.24%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch     | 3        | 0.24%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 950x540mm 43.0-inch | 3        | 0.24%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 700x390mm 31.5-inch | 3        | 0.24%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3        | 0.24%   |
| Philips PHL 277E6 PHLC0E6 1920x1080 598x336mm 27.0-inch               | 3        | 0.24%   |
| LG Electronics LCD Monitor LG TV SSCR2 3840x2160                      | 3        | 0.24%   |
| Hewlett-Packard W2072a HWP3000 1600x900 443x249mm 20.0-inch           | 3        | 0.24%   |
| Hewlett-Packard 24f HPN3546 1920x1080 527x296mm 23.8-inch             | 3        | 0.24%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch             | 3        | 0.24%   |
| Dell SE198WFP DELF003 1440x900 408x255mm 18.9-inch                    | 3        | 0.24%   |
| Dell P2719H DEL4185 1920x1080 598x336mm 27.0-inch                     | 3        | 0.24%   |
| Dell LCD Monitor E228WFP                                              | 3        | 0.24%   |
| Dell 1905FP DEL400D 1280x1024 376x301mm 19.0-inch                     | 3        | 0.24%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                     | 3        | 0.24%   |
| BenQ EW3270U BNQ7950 3840x2160 698x393mm 31.5-inch                    | 3        | 0.24%   |
| ___ LCDTV16 ___9000 1360x768                                          | 2        | 0.16%   |
| Xiaomi Mi TV XMD00E2 3840x2160 800x450mm 36.1-inch                    | 2        | 0.16%   |
| Vizio VO42LFHDTV10A VIZ0043 1920x1080 930x520mm 41.9-inch             | 2        | 0.16%   |
| Unknown LCD Monitor SAMSUNG                                           | 2        | 0.16%   |
| Toshiba TV TSB0206 1920x1080 1600x1000mm 74.3-inch                    | 2        | 0.16%   |
| Toshiba LCD-MONITOR LCDE980 1440x900 408x255mm 18.9-inch              | 2        | 0.16%   |
| Sony LCD Monitor TV 1920x1080                                         | 2        | 0.16%   |
| Skyworth MATRIX6*2 SII9575 1920x1080 708x398mm 32.0-inch              | 2        | 0.16%   |
| Sceptre Tech E32 SPT0CB8 1366x768 575x323mm 26.0-inch                 | 2        | 0.16%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 2        | 0.16%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch  | 2        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 487      | 41.66%  |
| 3840x2160 (4K)     | 102      | 8.73%   |
| 1680x1050 (WSXGA+) | 68       | 5.82%   |
| 1280x1024 (SXGA)   | 65       | 5.56%   |
| 1600x900 (HD+)     | 57       | 4.88%   |
| 2560x1440 (QHD)    | 56       | 4.79%   |
| Unknown            | 53       | 4.53%   |
| 1366x768 (WXGA)    | 47       | 4.02%   |
| 1440x900 (WXGA+)   | 43       | 3.68%   |
| 1360x768           | 29       | 2.48%   |
| 1920x1200 (WUXGA)  | 28       | 2.4%    |
| 3440x1440          | 26       | 2.22%   |
| 3840x1080          | 24       | 2.05%   |
| 2560x1080          | 12       | 1.03%   |
| 1920x540           | 11       | 0.94%   |
| 1024x768 (XGA)     | 9        | 0.77%   |
| 1600x1200          | 6        | 0.51%   |
| 3840x1600          | 4        | 0.34%   |
| 4480x1440          | 3        | 0.26%   |
| 1280x720 (HD)      | 3        | 0.26%   |
| 5760x2160          | 2        | 0.17%   |
| 5760x1080          | 2        | 0.17%   |
| 5120x1440          | 2        | 0.17%   |
| 4480x1080          | 2        | 0.17%   |
| 3600x1080          | 2        | 0.17%   |
| 3360x1080          | 2        | 0.17%   |
| 3200x1200          | 2        | 0.17%   |
| 3120x1050          | 2        | 0.17%   |
| 2944x1080          | 2        | 0.17%   |
| 2560x1600          | 2        | 0.17%   |
| 6400x1440          | 1        | 0.09%   |
| 5440x1080          | 1        | 0.09%   |
| 5040x1050          | 1        | 0.09%   |
| 4480x1600          | 1        | 0.09%   |
| 4160x1440          | 1        | 0.09%   |
| 3780x2160          | 1        | 0.09%   |
| 3360x1050          | 1        | 0.09%   |
| 3040x1050          | 1        | 0.09%   |
| 2720x1024          | 1        | 0.09%   |
| 2464x900           | 1        | 0.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 225      | 19.45%  |
| 24      | 120      | 10.37%  |
| 27      | 116      | 10.03%  |
| 21      | 100      | 8.64%   |
| 23      | 99       | 8.56%   |
| 19      | 76       | 6.57%   |
| 20      | 61       | 5.27%   |
| 31      | 58       | 5.01%   |
| 22      | 51       | 4.41%   |
| 18      | 46       | 3.98%   |
| 17      | 29       | 2.51%   |
| 34      | 23       | 1.99%   |
| 40      | 17       | 1.47%   |
| 15      | 15       | 1.3%    |
| 84      | 14       | 1.21%   |
| 32      | 13       | 1.12%   |
| 54      | 11       | 0.95%   |
| 72      | 10       | 0.86%   |
| 26      | 9        | 0.78%   |
| 36      | 6        | 0.52%   |
| 25      | 6        | 0.52%   |
| 28      | 5        | 0.43%   |
| 52      | 4        | 0.35%   |
| 35      | 4        | 0.35%   |
| 65      | 3        | 0.26%   |
| 49      | 3        | 0.26%   |
| 48      | 3        | 0.26%   |
| 47      | 3        | 0.26%   |
| 33      | 3        | 0.26%   |
| 29      | 3        | 0.26%   |
| 74      | 2        | 0.17%   |
| 57      | 2        | 0.17%   |
| 42      | 2        | 0.17%   |
| 41      | 2        | 0.17%   |
| 37      | 2        | 0.17%   |
| 86      | 1        | 0.09%   |
| 75      | 1        | 0.09%   |
| 69      | 1        | 0.09%   |
| 60      | 1        | 0.09%   |
| 59      | 1        | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 310      | 27.73%  |
| 401-500     | 289      | 25.85%  |
| Unknown     | 225      | 20.13%  |
| 601-700     | 80       | 7.16%   |
| 701-800     | 45       | 4.03%   |
| 301-350     | 42       | 3.76%   |
| 351-400     | 36       | 3.22%   |
| 1001-1500   | 33       | 2.95%   |
| 1501-2000   | 29       | 2.59%   |
| 801-900     | 24       | 2.15%   |
| 901-1000    | 5        | 0.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 614      | 57.01%  |
| Unknown | 209      | 19.41%  |
| 16/10   | 135      | 12.53%  |
| 5/4     | 57       | 5.29%   |
| 21/9    | 32       | 2.97%   |
| 4/3     | 19       | 1.76%   |
| 32/9    | 6        | 0.56%   |
| 6/5     | 4        | 0.37%   |
| 3/2     | 1        | 0.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 295      | 25.88%  |
| Unknown        | 225      | 19.74%  |
| 151-200        | 172      | 15.09%  |
| 301-350        | 119      | 10.44%  |
| 351-500        | 107      | 9.39%   |
| 141-150        | 62       | 5.44%   |
| More than 1000 | 55       | 4.82%   |
| 251-300        | 51       | 4.47%   |
| 501-1000       | 37       | 3.25%   |
| 101-110        | 11       | 0.96%   |
| 111-120        | 4        | 0.35%   |
| 131-140        | 1        | 0.09%   |
| 121-130        | 1        | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 616      | 56.57%  |
| Unknown | 225      | 20.66%  |
| 101-120 | 153      | 14.05%  |
| 1-50    | 52       | 4.78%   |
| 121-160 | 32       | 2.94%   |
| 161-240 | 11       | 1.01%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 976      | 79.67%  |
| 2     | 161      | 13.14%  |
| 0     | 72       | 5.88%   |
| 3     | 15       | 1.22%   |
| 4     | 1        | 0.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 755      | 42.34%  |
| Intel                             | 494      | 27.71%  |
| Qualcomm Atheros                  | 107      | 6%      |
| Ralink Technology                 | 60       | 3.37%   |
| Broadcom                          | 59       | 3.31%   |
| TP-Link                           | 47       | 2.64%   |
| MediaTek                          | 27       | 1.51%   |
| Nvidia                            | 26       | 1.46%   |
| Ralink                            | 23       | 1.29%   |
| Samsung Electronics               | 15       | 0.84%   |
| NetGear                           | 15       | 0.84%   |
| Broadcom Limited                  | 12       | 0.67%   |
| Microsoft                         | 11       | 0.62%   |
| Xiaomi                            | 10       | 0.56%   |
| Qualcomm Atheros Communications   | 10       | 0.56%   |
| D-Link                            | 10       | 0.56%   |
| Marvell Technology Group          | 9        | 0.5%    |
| ASIX Electronics                  | 9        | 0.5%    |
| Huawei Technologies               | 7        | 0.39%   |
| D-Link System                     | 7        | 0.39%   |
| ASUSTek Computer                  | 6        | 0.34%   |
| Edimax Technology                 | 5        | 0.28%   |
| Aquantia                          | 5        | 0.28%   |
| OPPO Electronics                  | 4        | 0.22%   |
| Motorola PCS                      | 4        | 0.22%   |
| Linksys                           | 4        | 0.22%   |
| DisplayLink                       | 3        | 0.17%   |
| Belkin Components                 | 3        | 0.17%   |
| VIA Technologies                  | 2        | 0.11%   |
| Sundance Technology Inc / IC Plus | 2        | 0.11%   |
| Motorola                          | 2        | 0.11%   |
| Gemtek                            | 2        | 0.11%   |
| AVM                               | 2        | 0.11%   |
| Arduino SA                        | 2        | 0.11%   |
| ZyDAS                             | 1        | 0.06%   |
| U-Blox                            | 1        | 0.06%   |
| TRENDnet                          | 1        | 0.06%   |
| T & A Mobile Phones               | 1        | 0.06%   |
| Sigma Sport                       | 1        | 0.06%   |
| Research In Motion                | 1        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 572      | 28.23%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 75       | 3.7%    |
| Realtek RTL8125 2.5GbE Controller                                 | 61       | 3.01%   |
| Intel Wi-Fi 6 AX200                                               | 57       | 2.81%   |
| Intel I211 Gigabit Network Connection                             | 55       | 2.71%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 41       | 2.02%   |
| Intel Ethernet Connection I217-LM                                 | 40       | 1.97%   |
| Intel Ethernet Connection (2) I219-V                              | 39       | 1.92%   |
| Intel Ethernet Controller I225-V                                  | 30       | 1.48%   |
| Realtek 802.11ac NIC                                              | 28       | 1.38%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 27       | 1.33%   |
| Ralink MT7601U Wireless Adapter                                   | 27       | 1.33%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 27       | 1.33%   |
| Intel Ethernet Connection I217-V                                  | 21       | 1.04%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 19       | 0.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 18       | 0.89%   |
| Intel Wireless 7265                                               | 18       | 0.89%   |
| Nvidia MCP61 Ethernet                                             | 16       | 0.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 15       | 0.74%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 14       | 0.69%   |
| Ralink RT5370 Wireless Adapter                                    | 14       | 0.69%   |
| Intel 82579V Gigabit Network Connection                           | 14       | 0.69%   |
| Intel Ethernet Connection (2) I219-LM                             | 13       | 0.64%   |
| Intel Ethernet Connection (2) I218-V                              | 13       | 0.64%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 13       | 0.64%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 12       | 0.59%   |
| Intel Ethernet Connection (7) I219-V                              | 12       | 0.59%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 12       | 0.59%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 11       | 0.54%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 11       | 0.54%   |
| Intel Wireless-AC 9260                                            | 11       | 0.54%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 10       | 0.49%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 10       | 0.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 10       | 0.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 10       | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 10       | 0.49%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 9        | 0.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 9        | 0.44%   |
| Intel 82574L Gigabit Network Connection                           | 9        | 0.44%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 8        | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 187      | 27.18%  |
| Realtek Semiconductor                 | 184      | 26.74%  |
| Ralink Technology                     | 60       | 8.72%   |
| Qualcomm Atheros                      | 53       | 7.7%    |
| TP-Link                               | 45       | 6.54%   |
| Broadcom                              | 27       | 3.92%   |
| Ralink                                | 23       | 3.34%   |
| MediaTek                              | 23       | 3.34%   |
| NetGear                               | 15       | 2.18%   |
| Microsoft                             | 11       | 1.6%    |
| Qualcomm Atheros Communications       | 10       | 1.45%   |
| D-Link                                | 10       | 1.45%   |
| ASUSTek Computer                      | 6        | 0.87%   |
| Edimax Technology                     | 5        | 0.73%   |
| D-Link System                         | 5        | 0.73%   |
| Broadcom Limited                      | 5        | 0.73%   |
| Linksys                               | 4        | 0.58%   |
| Belkin Components                     | 3        | 0.44%   |
| Gemtek                                | 2        | 0.29%   |
| AVM                                   | 2        | 0.29%   |
| ZyDAS                                 | 1        | 0.15%   |
| Xiaomi                                | 1        | 0.15%   |
| TRENDnet                              | 1        | 0.15%   |
| Panasonic (Matsushita)                | 1        | 0.15%   |
| Ovislink                              | 1        | 0.15%   |
| Marvell Technology Group              | 1        | 0.15%   |
| ADMtek                                | 1        | 0.15%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.15%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 57       | 8.17%   |
| Realtek 802.11ac NIC                                           | 28       | 4.01%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 27       | 3.87%   |
| Ralink MT7601U Wireless Adapter                                | 27       | 3.87%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 27       | 3.87%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 19       | 2.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 18       | 2.58%   |
| Intel Wireless 7265                                            | 18       | 2.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 15       | 2.15%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 14       | 2.01%   |
| Ralink RT5370 Wireless Adapter                                 | 14       | 2.01%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 12       | 1.72%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 12       | 1.72%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 11       | 1.58%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 11       | 1.58%   |
| Intel Wireless-AC 9260                                         | 11       | 1.58%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 10       | 1.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 10       | 1.43%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 9        | 1.29%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 9        | 1.29%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 8        | 1.15%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 7        | 1%      |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 7        | 1%      |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 7        | 1%      |
| Realtek RTL8188EE Wireless Network Adapter                     | 7        | 1%      |
| Qualcomm Atheros AR9271 802.11n                                | 7        | 1%      |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 7        | 1%      |
| Intel Wireless 7260                                            | 7        | 1%      |
| Intel Wireless 3165                                            | 7        | 1%      |
| Intel Alder Lake-S PCH CNVi WiFi                               | 7        | 1%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6        | 0.86%   |
| Microsoft Xbox Wireless Adapter for Windows                    | 6        | 0.86%   |
| MediaTek WiFi                                                  | 6        | 0.86%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 5        | 0.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5        | 0.72%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 5        | 0.72%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 5        | 0.72%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 5        | 0.72%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 5        | 0.72%   |
| NetGear A6210                                                  | 5        | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 690      | 54.03%  |
| Intel                             | 392      | 30.7%   |
| Qualcomm Atheros                  | 56       | 4.39%   |
| Broadcom                          | 32       | 2.51%   |
| Nvidia                            | 26       | 2.04%   |
| Samsung Electronics               | 10       | 0.78%   |
| Xiaomi                            | 9        | 0.7%    |
| ASIX Electronics                  | 9        | 0.7%    |
| Marvell Technology Group          | 8        | 0.63%   |
| Broadcom Limited                  | 7        | 0.55%   |
| Huawei Technologies               | 6        | 0.47%   |
| Aquantia                          | 5        | 0.39%   |
| OPPO Electronics                  | 4        | 0.31%   |
| MediaTek                          | 4        | 0.31%   |
| DisplayLink                       | 3        | 0.23%   |
| VIA Technologies                  | 2        | 0.16%   |
| TP-Link                           | 2        | 0.16%   |
| Sundance Technology Inc / IC Plus | 2        | 0.16%   |
| Motorola PCS                      | 2        | 0.16%   |
| D-Link System                     | 2        | 0.16%   |
| Research In Motion                | 1        | 0.08%   |
| Qualcomm                          | 1        | 0.08%   |
| JMicron Technology                | 1        | 0.08%   |
| HMD Global                        | 1        | 0.08%   |
| Google                            | 1        | 0.08%   |
| Apple                             | 1        | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 572      | 43.87%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 75       | 5.75%   |
| Realtek RTL8125 2.5GbE Controller                                 | 61       | 4.68%   |
| Intel I211 Gigabit Network Connection                             | 55       | 4.22%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 41       | 3.14%   |
| Intel Ethernet Connection I217-LM                                 | 40       | 3.07%   |
| Intel Ethernet Connection (2) I219-V                              | 39       | 2.99%   |
| Intel Ethernet Controller I225-V                                  | 30       | 2.3%    |
| Intel Ethernet Connection I217-V                                  | 21       | 1.61%   |
| Nvidia MCP61 Ethernet                                             | 16       | 1.23%   |
| Intel 82579V Gigabit Network Connection                           | 14       | 1.07%   |
| Intel Ethernet Connection (2) I219-LM                             | 13       | 1%      |
| Intel Ethernet Connection (2) I218-V                              | 13       | 1%      |
| Intel 82567LM-3 Gigabit Network Connection                        | 13       | 1%      |
| Intel Ethernet Connection (7) I219-V                              | 12       | 0.92%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 10       | 0.77%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 10       | 0.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 10       | 0.77%   |
| Intel 82574L Gigabit Network Connection                           | 9        | 0.69%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 8        | 0.61%   |
| Intel Ethernet Connection (12) I219-V                             | 8        | 0.61%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 8        | 0.61%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 8        | 0.61%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 7        | 0.54%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7        | 0.54%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 6        | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6        | 0.46%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 6        | 0.46%   |
| ASIX AX88179 Gigabit Ethernet                                     | 6        | 0.46%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 5        | 0.38%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 5        | 0.38%   |
| Intel Ethernet Connection (7) I219-LM                             | 5        | 0.38%   |
| Intel Ethernet Connection (14) I219-V                             | 5        | 0.38%   |
| Huawei WLZ-AN00                                                   | 5        | 0.38%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 5        | 0.38%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 4        | 0.31%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4        | 0.31%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4        | 0.31%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 4        | 0.31%   |
| Intel I210 Gigabit Network Connection                             | 4        | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1190     | 64.89%  |
| WiFi     | 622      | 33.91%  |
| Modem    | 18       | 0.98%   |
| Unknown  | 4        | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 899      | 71.18%  |
| WiFi     | 361      | 28.58%  |
| Modem    | 2        | 0.16%   |
| Unknown  | 1        | 0.08%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 786      | 64.64%  |
| 2     | 377      | 31%     |
| 3     | 37       | 3.04%   |
| 0     | 11       | 0.9%    |
| 5     | 2        | 0.16%   |
| 4     | 2        | 0.16%   |
| 7     | 1        | 0.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 809      | 66.09%  |
| Yes  | 415      | 33.91%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 156      | 37.23%  |
| Cambridge Silicon Radio         | 82       | 19.57%  |
| Realtek Semiconductor           | 59       | 14.08%  |
| Broadcom                        | 22       | 5.25%   |
| ASUSTek Computer                | 22       | 5.25%   |
| Qualcomm Atheros Communications | 13       | 3.1%    |
| MediaTek                        | 12       | 2.86%   |
| IMC Networks                    | 10       | 2.39%   |
| TP-Link                         | 7        | 1.67%   |
| Apple                           | 7        | 1.67%   |
| Dynex                           | 5        | 1.19%   |
| Lite-On Technology              | 3        | 0.72%   |
| Integrated System Solution      | 3        | 0.72%   |
| Foxconn / Hon Hai               | 3        | 0.72%   |
| Belkin Components               | 3        | 0.72%   |
| Dell                            | 2        | 0.48%   |
| Actions                         | 2        | 0.48%   |
| Unknown                         | 2        | 0.48%   |
| Sitecom Europe                  | 1        | 0.24%   |
| Realtek                         | 1        | 0.24%   |
| National Semiconductor          | 1        | 0.24%   |
| Micro Star International        | 1        | 0.24%   |
| Edimax Technology               | 1        | 0.24%   |
| D-Link System                   | 1        | 0.24%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 82       | 19.57%  |
| Realtek Bluetooth Radio                                  | 46       | 10.98%  |
| Intel AX200 Bluetooth                                    | 45       | 10.74%  |
| Intel Bluetooth wireless interface                       | 35       | 8.35%   |
| Intel AX210 Bluetooth                                    | 24       | 5.73%   |
| Intel Wireless-AC 3168 Bluetooth                         | 18       | 4.3%    |
| MediaTek Wireless_Device                                 | 12       | 2.86%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 12       | 2.86%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 10       | 2.39%   |
| Intel AX201 Bluetooth                                    | 9        | 2.15%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 8        | 1.91%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 8        | 1.91%   |
| TP-Link UB500 Adapter                                    | 7        | 1.67%   |
| IMC Networks Bluetooth Radio                             | 7        | 1.67%   |
| Realtek  Bluetooth 4.2 Adapter                           | 5        | 1.19%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 5        | 1.19%   |
| Realtek Bluetooth 5.1 Radio                              | 4        | 0.95%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 4        | 0.95%   |
| ASUS Bluetooth Radio                                     | 4        | 0.95%   |
| Realtek RTL8821A Bluetooth                               | 3        | 0.72%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 3        | 0.72%   |
| Lite-On Bluetooth Device                                 | 3        | 0.72%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 3        | 0.72%   |
| Broadcom HP Portable Bumble Bee                          | 3        | 0.72%   |
| Broadcom BCM43142A0 Bluetooth 4.0                        | 3        | 0.72%   |
| ASUS Qualcomm Bluetooth 4.1                              | 3        | 0.72%   |
| ASUS ASUS USB-BT500                                      | 3        | 0.72%   |
| Apple Bluetooth USB Host Controller                      | 3        | 0.72%   |
| Qualcomm Atheros  Bluetooth Device                       | 2        | 0.48%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                    | 2        | 0.48%   |
| Intel Bluetooth Device                                   | 2        | 0.48%   |
| Integrated System Solution Bluetooth Device              | 2        | 0.48%   |
| Foxconn / Hon Hai Wireless_Device                        | 2        | 0.48%   |
| Dell BT Mini-Receiver                                    | 2        | 0.48%   |
| Broadcom Bluetooth 2.0+eDR dongle                        | 2        | 0.48%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter         | 2        | 0.48%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter    | 2        | 0.48%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 2        | 0.48%   |
| Actions general adapter                                  | 2        | 0.48%   |
| Unknown                                                  | 2        | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 774      | 38.64%  |
| AMD                                          | 515      | 25.71%  |
| Nvidia                                       | 453      | 22.62%  |
| C-Media Electronics                          | 47       | 2.35%   |
| Creative Labs                                | 20       | 1%      |
| Logitech                                     | 14       | 0.7%    |
| Kingston Technology                          | 14       | 0.7%    |
| ASUSTek Computer                             | 13       | 0.65%   |
| JMTek                                        | 10       | 0.5%    |
| Texas Instruments                            | 9        | 0.45%   |
| Generalplus Technology                       | 9        | 0.45%   |
| Razer USA                                    | 8        | 0.4%    |
| Plantronics                                  | 8        | 0.4%    |
| VIA Technologies                             | 7        | 0.35%   |
| Creative Technology                          | 7        | 0.35%   |
| GN Netcom                                    | 5        | 0.25%   |
| Realtek Semiconductor                        | 4        | 0.2%    |
| Micro Star International                     | 4        | 0.2%    |
| Zoran Co. Personal Media Division (Nogatech) | 3        | 0.15%   |
| Tenx Technology                              | 3        | 0.15%   |
| SteelSeries ApS                              | 3        | 0.15%   |
| RODE Microphones                             | 3        | 0.15%   |
| Focusrite-Novation                           | 3        | 0.15%   |
| Astro Gaming                                 | 3        | 0.15%   |
| Yamaha                                       | 2        | 0.1%    |
| KTMicro                                      | 2        | 0.1%    |
| Jieli Technology                             | 2        | 0.1%    |
| FUXIN                                        | 2        | 0.1%    |
| DSEA A/S                                     | 2        | 0.1%    |
| Cambridge Audio                              | 2        | 0.1%    |
| Blue Microphones                             | 2        | 0.1%    |
| BEHRINGER International                      | 2        | 0.1%    |
| Audio-Technica                               | 2        | 0.1%    |
| Asahi Kasei Microsystems                     | 2        | 0.1%    |
| XMOS                                         | 1        | 0.05%   |
| Valve Software                               | 1        | 0.05%   |
| Universal Audio                              | 1        | 0.05%   |
| Trust                                        | 1        | 0.05%   |
| Thesycon Systemsoftware & Consulting         | 1        | 0.05%   |
| Swissonic                                    | 1        | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 123      | 5.27%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 112      | 4.79%   |
| AMD Starship/Matisse HD Audio Controller                                          | 106      | 4.54%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 98       | 4.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 84       | 3.6%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 76       | 3.25%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 70       | 3%      |
| AMD Family 17h/19h HD Audio Controller                                            | 69       | 2.95%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 55       | 2.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 51       | 2.18%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 46       | 1.97%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 45       | 1.93%   |
| Intel 200 Series PCH HD Audio                                                     | 44       | 1.88%   |
| AMD FCH Azalia Controller                                                         | 44       | 1.88%   |
| Intel Cannon Lake PCH cAVS                                                        | 39       | 1.67%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 34       | 1.46%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 31       | 1.33%   |
| Nvidia GF108 High Definition Audio Controller                                     | 30       | 1.28%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 29       | 1.24%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 29       | 1.24%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 29       | 1.24%   |
| Nvidia TU116 High Definition Audio Controller                                     | 28       | 1.2%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 28       | 1.2%    |
| AMD Renoir Radeon High Definition Audio Controller                                | 26       | 1.11%   |
| Nvidia GF119 HDMI Audio Controller                                                | 24       | 1.03%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 23       | 0.98%   |
| AMD Navi 10 HDMI Audio                                                            | 23       | 0.98%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 23       | 0.98%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 22       | 0.94%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 21       | 0.9%    |
| Nvidia TU106 High Definition Audio Controller                                     | 20       | 0.86%   |
| Nvidia High Definition Audio Controller                                           | 20       | 0.86%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 20       | 0.86%   |
| Nvidia GP106 High Definition Audio Controller                                     | 19       | 0.81%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 19       | 0.81%   |
| Intel Smart Sound Technology (SST) Audio Controller                               | 18       | 0.77%   |
| Nvidia MCP61 High Definition Audio                                                | 17       | 0.73%   |
| Nvidia GP104 High Definition Audio Controller                                     | 17       | 0.73%   |
| Nvidia GK107 HDMI Audio Controller                                                | 17       | 0.73%   |
| AMD Kabini HDMI/DP Audio                                                          | 17       | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 32       | 17.58%  |
| Kingston            | 26       | 14.29%  |
| Samsung Electronics | 19       | 10.44%  |
| G.Skill             | 17       | 9.34%   |
| SK hynix            | 16       | 8.79%   |
| Corsair             | 16       | 8.79%   |
| Crucial             | 14       | 7.69%   |
| Team                | 8        | 4.4%    |
| Micron Technology   | 5        | 2.75%   |
| Unknown             | 4        | 2.2%    |
| Nanya Technology    | 3        | 1.65%   |
| A-DATA Technology   | 3        | 1.65%   |
| Wilk                | 2        | 1.1%    |
| Unifosa             | 2        | 1.1%    |
| Ramaxel Technology  | 2        | 1.1%    |
| Patriot             | 2        | 1.1%    |
| Avant               | 2        | 1.1%    |
| Transcend           | 1        | 0.55%   |
| SUPER KINGSTEK      | 1        | 0.55%   |
| Qimonda             | 1        | 0.55%   |
| Patriot Memory      | 1        | 0.55%   |
| Goldkey             | 1        | 0.55%   |
| Golden Empire       | 1        | 0.55%   |
| F7852C80            | 1        | 0.55%   |
| Elpida              | 1        | 0.55%   |
| AMD                 | 1        | 0.55%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s            | 4        | 1.98%   |
| Unknown                                                 | 4        | 1.98%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 3000MT/s      | 3        | 1.49%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s    | 3        | 1.49%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s            | 2        | 0.99%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s               | 2        | 0.99%   |
| Unknown RAM Module 2048MB DIMM SDRAM                    | 2        | 0.99%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 2933MT/s     | 2        | 0.99%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s    | 2        | 0.99%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s    | 2        | 0.99%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s     | 2        | 0.99%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s     | 2        | 0.99%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s     | 2        | 0.99%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s       | 2        | 0.99%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s     | 2        | 0.99%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s   | 2        | 0.99%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s     | 2        | 0.99%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s    | 2        | 0.99%   |
| G.Skill RAM F4-3200C16-16GTZR 16GB DIMM DDR4 3333MT/s   | 2        | 0.99%   |
| Crucial RAM CT16G48C40S5.M8A1 16GB SODIMM DDR5 4800MT/s | 2        | 0.99%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 2        | 0.99%   |
| Wilk RAM IRX3200D464L16A/16G 16384MB DIMM DDR4 3200MT/s | 1        | 0.5%    |
| Wilk RAM GX3236D464S/8GSBS1 8192MB DIMM DDR4 3467MT/s   | 1        | 0.5%    |
| Unknown RAM TM44D18UD04MU-NUK 4096MB DIMM DDR4 2400MT/s | 1        | 0.5%    |
| Unknown RAM Module 8GB DIMM SDRAM                       | 1        | 0.5%    |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s               | 1        | 0.5%    |
| Unknown RAM Module 8GB DIMM DDR3 1066MT/s               | 1        | 0.5%    |
| Unknown RAM Module 8GB DIMM 1333MT/s                    | 1        | 0.5%    |
| Unknown RAM Module 8192MB DIMM DDR4 2400MT/s            | 1        | 0.5%    |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s            | 1        | 0.5%    |
| Unknown RAM Module 8192MB DIMM 400MT/s                  | 1        | 0.5%    |
| Unknown RAM Module 512MB DIMM 667MT/s                   | 1        | 0.5%    |
| Unknown RAM Module 4GB DIMM SDRAM 1066MT/s              | 1        | 0.5%    |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                | 1        | 0.5%    |
| Unknown RAM Module 4GB DIMM 400MT/s                     | 1        | 0.5%    |
| Unknown RAM Module 4GB DIMM 1600MT/s                    | 1        | 0.5%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 1        | 0.5%    |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s            | 1        | 0.5%    |
| Unknown RAM Module 4096MB DIMM DDR 1600MT/s             | 1        | 0.5%    |
| Unknown RAM Module 4096MB DIMM 667MT/s                  | 1        | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 71       | 43.29%  |
| DDR3    | 59       | 35.98%  |
| Unknown | 11       | 6.71%   |
| SDRAM   | 8        | 4.88%   |
| DDR2    | 8        | 4.88%   |
| DDR5    | 3        | 1.83%   |
| DDR     | 3        | 1.83%   |
| LPDDR4  | 1        | 0.61%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 152      | 94.41%  |
| SODIMM       | 7        | 4.35%   |
| Row Of Chips | 1        | 0.62%   |
| FB-DIMM      | 1        | 0.62%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 67       | 36.81%  |
| 4096  | 49       | 26.92%  |
| 2048  | 25       | 13.74%  |
| 16384 | 23       | 12.64%  |
| 32768 | 11       | 6.04%   |
| 1024  | 6        | 3.3%    |
| 512   | 1        | 0.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 32       | 17.78%  |
| 1333    | 23       | 12.78%  |
| 3200    | 16       | 8.89%   |
| 3600    | 12       | 6.67%   |
| 2667    | 9        | 5%      |
| 2133    | 9        | 5%      |
| 2400    | 8        | 4.44%   |
| 3000    | 6        | 3.33%   |
| 800     | 6        | 3.33%   |
| 1866    | 5        | 2.78%   |
| 1800    | 5        | 2.78%   |
| Unknown | 4        | 2.22%   |
| 2933    | 3        | 1.67%   |
| 667     | 3        | 1.67%   |
| 4800    | 2        | 1.11%   |
| 3866    | 2        | 1.11%   |
| 3800    | 2        | 1.11%   |
| 3733    | 2        | 1.11%   |
| 3666    | 2        | 1.11%   |
| 3466    | 2        | 1.11%   |
| 3333    | 2        | 1.11%   |
| 2666    | 2        | 1.11%   |
| 1867    | 2        | 1.11%   |
| 1066    | 2        | 1.11%   |
| 400     | 2        | 1.11%   |
| 5354    | 1        | 0.56%   |
| 5200    | 1        | 0.56%   |
| 4266    | 1        | 0.56%   |
| 4000    | 1        | 0.56%   |
| 3933    | 1        | 0.56%   |
| 3500    | 1        | 0.56%   |
| 3467    | 1        | 0.56%   |
| 3400    | 1        | 0.56%   |
| 3266    | 1        | 0.56%   |
| 2800    | 1        | 0.56%   |
| 2465    | 1        | 0.56%   |
| 2200    | 1        | 0.56%   |
| 2000    | 1        | 0.56%   |
| 1400    | 1        | 0.56%   |
| 976     | 1        | 0.56%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 12       | 21.82%  |
| Brother Industries    | 11       | 20%     |
| Canon                 | 10       | 18.18%  |
| Seiko Epson           | 9        | 16.36%  |
| Samsung Electronics   | 8        | 14.55%  |
| Lexmark International | 2        | 3.64%   |
| Ricoh                 | 1        | 1.82%   |
| QinHeng Electronics   | 1        | 1.82%   |
| Konica Minolta        | 1        | 1.82%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Seiko Epson L3110 Series                     | 2        | 3.64%   |
| Samsung C460 Series                          | 2        | 3.64%   |
| HP LaserJet Professional P1102w              | 2        | 3.64%   |
| HP DeskJet 2130 series                       | 2        | 3.64%   |
| Canon LiDE 400                               | 2        | 3.64%   |
| Seiko Epson XP-7100 Series                   | 1        | 1.82%   |
| Seiko Epson XP-200 Series                    | 1        | 1.82%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1        | 1.82%   |
| Seiko Epson L805 Series                      | 1        | 1.82%   |
| Seiko Epson L355 Series                      | 1        | 1.82%   |
| Seiko Epson ET-2820 Series                   | 1        | 1.82%   |
| Seiko Epson ET-2710 Series                   | 1        | 1.82%   |
| Samsung SCX-483x 5x3x Series                 | 1        | 1.82%   |
| Samsung SCX-4623 Series                      | 1        | 1.82%   |
| Samsung SCX-4200 series                      | 1        | 1.82%   |
| Samsung SCX-3400 Series                      | 1        | 1.82%   |
| Samsung ML-2950 Series                       | 1        | 1.82%   |
| Samsung ML-216x Series Laser Printer         | 1        | 1.82%   |
| Ricoh SP 112SU                               | 1        | 1.82%   |
| QinHeng CH340S                               | 1        | 1.82%   |
| Lexmark International MX317dn                | 1        | 1.82%   |
| Lexmark International Laser Printer E232     | 1        | 1.82%   |
| Konica Minolta PagePro 1380MF                | 1        | 1.82%   |
| HP Smart Tank 510 series                     | 1        | 1.82%   |
| HP PSC 1100 series                           | 1        | 1.82%   |
| HP Officejet 6600                            | 1        | 1.82%   |
| HP OfficeJet 5600 (USBHUB)                   | 1        | 1.82%   |
| HP OfficeJet 4650 series                     | 1        | 1.82%   |
| HP ENVY Photo 7800 series                    | 1        | 1.82%   |
| HP ENVY 4520 series                          | 1        | 1.82%   |
| HP DeskJet 2700 series                       | 1        | 1.82%   |
| Canon TS3100 series                          | 1        | 1.82%   |
| Canon TR4500 series                          | 1        | 1.82%   |
| Canon PIXMA MG3200 Series                    | 1        | 1.82%   |
| Canon PIXMA MG2500 Series                    | 1        | 1.82%   |
| Canon MF240 Series UFRII LT                  | 1        | 1.82%   |
| Canon iP4200                                 | 1        | 1.82%   |
| Canon G3010 series                           | 1        | 1.82%   |
| Canon E410 series                            | 1        | 1.82%   |
| Brother VC-500W                              | 1        | 1.82%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 6        | 66.67%  |
| Hewlett-Packard | 2        | 22.22%  |
| Seiko Epson     | 1        | 11.11%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Seiko Epson Scanner                | 1        | 10%     |
| HP ScanJet 2400c                   | 1        | 10%     |
| HP PSC 1200                        | 1        | 10%     |
| Canon CanoScan N670U/N676U/LiDE 20 | 1        | 10%     |
| Canon CanoScan LiDE 60             | 1        | 10%     |
| Canon CanoScan LiDE 220            | 1        | 10%     |
| Canon CanoScan LiDE 110            | 1        | 10%     |
| Canon CanoScan LiDE 100            | 1        | 10%     |
| Canon CanoScan D660U               | 1        | 10%     |
| Canon CanoScan 8800F               | 1        | 10%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 57       | 28.5%   |
| Microdia                      | 19       | 9.5%    |
| Microsoft                     | 15       | 7.5%    |
| Sunplus Innovation Technology | 12       | 6%      |
| Generalplus Technology        | 9        | 4.5%    |
| Samsung Electronics           | 8        | 4%      |
| Apple                         | 8        | 4%      |
| ARC International             | 7        | 3.5%    |
| Chicony Electronics           | 5        | 2.5%    |
| Realtek Semiconductor         | 4        | 2%      |
| Razer USA                     | 4        | 2%      |
| Jieli Technology              | 4        | 2%      |
| Tobii Technology AB           | 3        | 1.5%    |
| GEMBIRD                       | 3        | 1.5%    |
| Creative Technology           | 3        | 1.5%    |
| Z-Star Microelectronics       | 2        | 1%      |
| Xiongmai                      | 2        | 1%      |
| Suyin                         | 2        | 1%      |
| MacroSilicon                  | 2        | 1%      |
| lihappe8                      | 2        | 1%      |
| Guillemot                     | 2        | 1%      |
| Cubeternet                    | 2        | 1%      |
| A4Tech                        | 2        | 1%      |
| 2M UVC CAMERA                 | 2        | 1%      |
| WaveRider Communications      | 1        | 0.5%    |
| Unknown                       | 1        | 0.5%    |
| Trust                         | 1        | 0.5%    |
| Teslong Camera                | 1        | 0.5%    |
| Sunplus Technology            | 1        | 0.5%    |
| Sonix Technology              | 1        | 0.5%    |
| Ruision                       | 1        | 0.5%    |
| Pixart Imaging                | 1        | 0.5%    |
| Lenovo                        | 1        | 0.5%    |
| KYE Systems (Mouse Systems)   | 1        | 0.5%    |
| Intel                         | 1        | 0.5%    |
| INOGENI                       | 1        | 0.5%    |
| IMC Networks                  | 1        | 0.5%    |
| Huawei Technologies           | 1        | 0.5%    |
| Hewlett-Packard               | 1        | 0.5%    |
| Genesys Logic                 | 1        | 0.5%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Logitech Webcam C270                     | 14       | 6.93%   |
| Logitech HD Pro Webcam C920              | 12       | 5.94%   |
| Samsung Galaxy series, misc. (MTP mode)  | 8        | 3.96%   |
| Microsoft LifeCam HD-3000                | 8        | 3.96%   |
| Microdia USB 2.0 Camera                  | 7        | 3.47%   |
| ARC International Camera                 | 7        | 3.47%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X          | 7        | 3.47%   |
| Sunplus 1080P Webcam                     | 5        | 2.48%   |
| Sunplus HD 720P webcam                   | 4        | 1.98%   |
| Razer USA Gaming Webcam [Kiyo]           | 4        | 1.98%   |
| Logitech HD Webcam C615                  | 4        | 1.98%   |
| Logitech C920 PRO HD Webcam              | 4        | 1.98%   |
| Jieli USB PHY 2.0                        | 4        | 1.98%   |
| Generalplus GENERAL WEBCAM               | 4        | 1.98%   |
| Generalplus 808 Camera #9 (web-cam mode) | 4        | 1.98%   |
| Chicony HP High Definition 1MP Webcam    | 4        | 1.98%   |
| Tobii AB EyeChip                         | 3        | 1.49%   |
| Microsoft LifeCam VX-500 [1357]          | 3        | 1.49%   |
| Microdia Webcam Vitade AF                | 3        | 1.49%   |
| Microdia Integrated Camera               | 3        | 1.49%   |
| Logitech Webcam C925e                    | 3        | 1.49%   |
| Logitech HD Webcam C910                  | 3        | 1.49%   |
| Xiongmai web camera                      | 2        | 0.99%   |
| Suyin HD WebCam                          | 2        | 0.99%   |
| Microsoft MicrosoftÂ LifeCam Cinema     | 2        | 0.99%   |
| Microdia USB Live camera                 | 2        | 0.99%   |
| Logitech Webcam C310                     | 2        | 0.99%   |
| Logitech QuickCam Pro for Notebooks      | 2        | 0.99%   |
| Logitech HD Webcam C525                  | 2        | 0.99%   |
| Logitech C922 Pro Stream Webcam          | 2        | 0.99%   |
| lihappe8 USB 2.0 Camera                  | 2        | 0.99%   |
| GEMBIRD USB2.0 PC CAMERA                 | 2        | 0.99%   |
| 2M UVC CAMERA Web Camera                 | 2        | 0.99%   |
| Z-Star Venus USB2.0 Camera               | 1        | 0.5%    |
| Z-Star Integrated Camera                 | 1        | 0.5%    |
| WaveRider USB 2.0 Camera                 | 1        | 0.5%    |
| Unknown HD camera                        | 1        | 0.5%    |
| Trust Webcam                             | 1        | 0.5%    |
| Teslong Camera Teslong Camera            | 1        | 0.5%    |
| Sunplus General Image Device             | 1        | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 1        | 50%     |
| AuthenTec             | 1        | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| LighTuning Fingerprint Sensor        | 1        | 50%     |
| AuthenTec AES2501 Fingerprint Sensor | 1        | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 2        | 18.18%  |
| Advanced Card Systems             | 2        | 18.18%  |
| VASCO Data Security International | 1        | 9.09%   |
| SCM Microsystems                  | 1        | 9.09%   |
| Reiner SCT Kartensysteme          | 1        | 9.09%   |
| Jing-Mold Enterprise              | 1        | 9.09%   |
| Fujitsu Siemens Computers         | 1        | 9.09%   |
| Chicony Electronics               | 1        | 9.09%   |
| Alcor Micro                       | 1        | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface                 | 2        | 18.18%  |
| VASCO Data Security International Digipass 905 SmartCard Reader   | 1        | 9.09%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader            | 1        | 9.09%   |
| Reiner SCT Kartensysteme cyberJack e-com/pinpad                   | 1        | 9.09%   |
| Jing-Mold Enterprise HP USB Business Slim Smartcard CCID Keyboard | 1        | 9.09%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                     | 1        | 9.09%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard              | 1        | 9.09%   |
| Alcor Micro AU9540 Smartcard Reader                               | 1        | 9.09%   |
| Advanced Card Systems ACR39U                                      | 1        | 9.09%   |
| Advanced Card Systems ACR1281 1S Dual Reader                      | 1        | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 996      | 80.91%  |
| 1     | 208      | 16.9%   |
| 2     | 24       | 1.95%   |
| 3     | 2        | 0.16%   |
| 4     | 1        | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 103      | 40.39%  |
| Graphics card            | 90       | 35.29%  |
| Communication controller | 12       | 4.71%   |
| Multimedia controller    | 10       | 3.92%   |
| Unassigned class         | 7        | 2.75%   |
| Chipcard                 | 7        | 2.75%   |
| Storage/raid             | 5        | 1.96%   |
| Modem                    | 4        | 1.57%   |
| Sound                    | 3        | 1.18%   |
| Bluetooth                | 3        | 1.18%   |
| Network                  | 2        | 0.78%   |
| Net/ethernet             | 2        | 0.78%   |
| Fingerprint reader       | 2        | 0.78%   |
| Camera                   | 2        | 0.78%   |
| Storage/ide              | 1        | 0.39%   |
| Dvb card                 | 1        | 0.39%   |
| Card reader              | 1        | 0.39%   |

