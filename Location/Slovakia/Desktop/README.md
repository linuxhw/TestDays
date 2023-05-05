Linux in Slovakia - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Slovakia.

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

Total: 467

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | ProLiant ML310e Gen8 v2     | [501d26e477](https://linux-hardware.org/?probe=501d26e477) | Apr 30, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [a2b832afa2](https://linux-hardware.org/?probe=a2b832afa2) | Apr 30, 2023 |
| HP            | 802F                        | [b314d41043](https://linux-hardware.org/?probe=b314d41043) | Apr 28, 2023 |
| ASRock        | H61M-VG4                    | [a8e7de2e0b](https://linux-hardware.org/?probe=a8e7de2e0b) | Apr 26, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [bb520ff82e](https://linux-hardware.org/?probe=bb520ff82e) | Apr 21, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [76db4c685b](https://linux-hardware.org/?probe=76db4c685b) | Apr 15, 2023 |
| ASUSTek       | M2N68-AM SE2                | [e9b6076df4](https://linux-hardware.org/?probe=e9b6076df4) | Apr 13, 2023 |
| ASUSTek       | PRIME B450M-A II            | [1a470a3b5a](https://linux-hardware.org/?probe=1a470a3b5a) | Apr 10, 2023 |
| Techvision    | TVI7309X B0                 | [d24ce5fa44](https://linux-hardware.org/?probe=d24ce5fa44) | Apr 09, 2023 |
| ASRock        | FM2A55M-VG3+                | [f7435e4d65](https://linux-hardware.org/?probe=f7435e4d65) | Apr 09, 2023 |
| ASRock        | FM2A55M-VG3+                | [53ed0bc068](https://linux-hardware.org/?probe=53ed0bc068) | Apr 09, 2023 |
| Lenovo        | 318E SDK0J40697 WIN 3305... | [436d55c73e](https://linux-hardware.org/?probe=436d55c73e) | Apr 09, 2023 |
| ASRock        | 960GC-GS FX                 | [90cb74d9f0](https://linux-hardware.org/?probe=90cb74d9f0) | Apr 08, 2023 |
| Techvision    | TVI7309X B0                 | [dbbe4bbbc5](https://linux-hardware.org/?probe=dbbe4bbbc5) | Apr 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [7c95c976a9](https://linux-hardware.org/?probe=7c95c976a9) | Apr 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [e45ad193f8](https://linux-hardware.org/?probe=e45ad193f8) | Apr 01, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | [e9fe5cb307](https://linux-hardware.org/?probe=e9fe5cb307) | Apr 01, 2023 |
| ASUSTek       | PRIME A320M-K               | [59c335754f](https://linux-hardware.org/?probe=59c335754f) | Apr 01, 2023 |
| ASUSTek       | P5E WS Pro                  | [6c70ac23df](https://linux-hardware.org/?probe=6c70ac23df) | Mar 30, 2023 |
| HP            | 0AACh                       | [43dbfddd1b](https://linux-hardware.org/?probe=43dbfddd1b) | Mar 28, 2023 |
| Pegatron      | 2AD5                        | [502ff745d4](https://linux-hardware.org/?probe=502ff745d4) | Mar 27, 2023 |
| Dell          | 0RN474                      | [1fb7cf06d1](https://linux-hardware.org/?probe=1fb7cf06d1) | Mar 25, 2023 |
| Dell          | 0RN474                      | [88b56f0530](https://linux-hardware.org/?probe=88b56f0530) | Mar 24, 2023 |
| HP            | 0AACh                       | [2a1f96ca8d](https://linux-hardware.org/?probe=2a1f96ca8d) | Mar 24, 2023 |
| ASUSTek       | M5A97 R2.0                  | [789ca3dc74](https://linux-hardware.org/?probe=789ca3dc74) | Mar 22, 2023 |
| Techvision    | TVI7309X B0                 | [468588ab96](https://linux-hardware.org/?probe=468588ab96) | Mar 21, 2023 |
| Gigabyte      | P43-ES3G                    | [60a7dc4c2e](https://linux-hardware.org/?probe=60a7dc4c2e) | Mar 20, 2023 |
| Techvision    | TVI7309X B0                 | [d1a16fdb17](https://linux-hardware.org/?probe=d1a16fdb17) | Mar 18, 2023 |
| Techvision    | TVI7309X B0                 | [08572d5e7c](https://linux-hardware.org/?probe=08572d5e7c) | Mar 18, 2023 |
| Techvision    | TVI7309X B0                 | [82914cf856](https://linux-hardware.org/?probe=82914cf856) | Mar 18, 2023 |
| Dell          | 0HN7XN A01                  | [4ce2092fe2](https://linux-hardware.org/?probe=4ce2092fe2) | Mar 17, 2023 |
| Intel         | DH77EB AAG39073-304         | [0b55f12ab3](https://linux-hardware.org/?probe=0b55f12ab3) | Mar 11, 2023 |
| ASRock        | A320M-DVS R4.0              | [8e02302d63](https://linux-hardware.org/?probe=8e02302d63) | Mar 09, 2023 |
| Gigabyte      | 970A-DS3P                   | [fc28c47011](https://linux-hardware.org/?probe=fc28c47011) | Mar 03, 2023 |
| ASUSTek       | F2A85-V PRO                 | [aa7d308d7e](https://linux-hardware.org/?probe=aa7d308d7e) | Mar 01, 2023 |
| ASUSTek       | PRIME X570-P                | [dda5eec4b9](https://linux-hardware.org/?probe=dda5eec4b9) | Feb 28, 2023 |
| Gigabyte      | X58A-UD5                    | [4cff35f888](https://linux-hardware.org/?probe=4cff35f888) | Feb 27, 2023 |
| HP            | 3397                        | [e714a7b19d](https://linux-hardware.org/?probe=e714a7b19d) | Feb 23, 2023 |
| ASRock        | B550 Extreme4               | [db2686086b](https://linux-hardware.org/?probe=db2686086b) | Feb 21, 2023 |
| ASRock        | B450M Pro4-F R2.0           | [f1082dcffa](https://linux-hardware.org/?probe=f1082dcffa) | Feb 17, 2023 |
| Gigabyte      | P43-ES3G                    | [528ffce1c7](https://linux-hardware.org/?probe=528ffce1c7) | Feb 15, 2023 |
| Gigabyte      | B250M-D3H-CF                | [8689383fea](https://linux-hardware.org/?probe=8689383fea) | Feb 15, 2023 |
| Gigabyte      | H81M-S2V                    | [09dff429cd](https://linux-hardware.org/?probe=09dff429cd) | Feb 12, 2023 |
| Gigabyte      | H61M-S1                     | [aef266643c](https://linux-hardware.org/?probe=aef266643c) | Feb 11, 2023 |
| Gigabyte      | H61M-S1                     | [a4791d2bc4](https://linux-hardware.org/?probe=a4791d2bc4) | Feb 11, 2023 |
| Gigabyte      | H61M-S1                     | [e6c7ea049a](https://linux-hardware.org/?probe=e6c7ea049a) | Feb 10, 2023 |
| Gigabyte      | H61M-S1                     | [9cbe5cf2b6](https://linux-hardware.org/?probe=9cbe5cf2b6) | Feb 10, 2023 |
| ASRock        | A520M-ITX/ac                | [a6e401a1d3](https://linux-hardware.org/?probe=a6e401a1d3) | Feb 09, 2023 |
| ASRock        | B550M Steel Legend          | [83b847229c](https://linux-hardware.org/?probe=83b847229c) | Feb 08, 2023 |
| MSI           | MS-7513                     | [3953f1b447](https://linux-hardware.org/?probe=3953f1b447) | Jan 28, 2023 |
| Gigabyte      | Z490M                       | [a53147a5e7](https://linux-hardware.org/?probe=a53147a5e7) | Jan 25, 2023 |
| Gigabyte      | H61M-S1                     | [7a3b58d6a7](https://linux-hardware.org/?probe=7a3b58d6a7) | Jan 24, 2023 |
| HP            | 3397                        | [03c53827b5](https://linux-hardware.org/?probe=03c53827b5) | Jan 17, 2023 |
| Gigabyte      | Z97MX-Gaming 5              | [8d5796c907](https://linux-hardware.org/?probe=8d5796c907) | Jan 15, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [b10c786457](https://linux-hardware.org/?probe=b10c786457) | Jan 14, 2023 |
| Gigabyte      | B75M-D3H                    | [cfa8ec5fcb](https://linux-hardware.org/?probe=cfa8ec5fcb) | Jan 13, 2023 |
| Gigabyte      | EP45-DS3                    | [5bf59df74c](https://linux-hardware.org/?probe=5bf59df74c) | Jan 10, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [b39213e4d0](https://linux-hardware.org/?probe=b39213e4d0) | Jan 09, 2023 |
| Dell          | 0654JC A01                  | [c3016e1823](https://linux-hardware.org/?probe=c3016e1823) | Jan 09, 2023 |
| Acer          | H57M01                      | [41ee28ae4b](https://linux-hardware.org/?probe=41ee28ae4b) | Jan 09, 2023 |
| MSI           | MS-7513                     | [6e63c2139f](https://linux-hardware.org/?probe=6e63c2139f) | Jan 08, 2023 |
| MSI           | PRO Z690-A DDR4             | [0b9a54a591](https://linux-hardware.org/?probe=0b9a54a591) | Jan 06, 2023 |
| Dell          | 00V62H A00                  | [dde339b7c9](https://linux-hardware.org/?probe=dde339b7c9) | Dec 26, 2022 |
| MSI           | G41M4                       | [b651925b13](https://linux-hardware.org/?probe=b651925b13) | Dec 21, 2022 |
| MSI           | 790GX-G65                   | [7ad3c8f807](https://linux-hardware.org/?probe=7ad3c8f807) | Dec 18, 2022 |
| ASRock        | N3150-NUC                   | [5e77ec1117](https://linux-hardware.org/?probe=5e77ec1117) | Dec 18, 2022 |
| ASRock        | N3150-NUC                   | [e497bf2ce3](https://linux-hardware.org/?probe=e497bf2ce3) | Dec 17, 2022 |
| HP            | 1905                        | [21f639657c](https://linux-hardware.org/?probe=21f639657c) | Dec 13, 2022 |
| ASUSTek       | PRIME B460M-K               | [ceff27eeef](https://linux-hardware.org/?probe=ceff27eeef) | Dec 07, 2022 |
| Gigabyte      | Z790 AERO G                 | [b779cd6c2f](https://linux-hardware.org/?probe=b779cd6c2f) | Dec 06, 2022 |
| ASUSTek       | P8H61-M LX                  | [cd75a3e13f](https://linux-hardware.org/?probe=cd75a3e13f) | Dec 03, 2022 |
| ASUSTek       | PRIME B460M-K               | [c8dd66d6de](https://linux-hardware.org/?probe=c8dd66d6de) | Dec 01, 2022 |
| ASUSTek       | PRIME B460M-K               | [7df334aaa0](https://linux-hardware.org/?probe=7df334aaa0) | Nov 26, 2022 |
| Shuttle       | FS61                        | [7a940c8fa3](https://linux-hardware.org/?probe=7a940c8fa3) | Nov 19, 2022 |
| ASUSTek       | PRIME B460M-K               | [19663894ff](https://linux-hardware.org/?probe=19663894ff) | Nov 18, 2022 |
| ASUSTek       | PRIME B460M-K               | [99a32a02ce](https://linux-hardware.org/?probe=99a32a02ce) | Nov 18, 2022 |
| MSI           | A78-G41 PC Mate             | [8487f5d19c](https://linux-hardware.org/?probe=8487f5d19c) | Nov 08, 2022 |
| MSI           | GF615M-P33                  | [8aec7634ab](https://linux-hardware.org/?probe=8aec7634ab) | Nov 05, 2022 |
| MSI           | Z77A-GD65                   | [a7bc380726](https://linux-hardware.org/?probe=a7bc380726) | Oct 30, 2022 |
| Gigabyte      | 970A-DS3P                   | [995f7abb0c](https://linux-hardware.org/?probe=995f7abb0c) | Oct 25, 2022 |
| MSI           | H310M PRO-VD                | [9ce99513bc](https://linux-hardware.org/?probe=9ce99513bc) | Oct 21, 2022 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [19d09fb082](https://linux-hardware.org/?probe=19d09fb082) | Oct 17, 2022 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [9f3307c5d0](https://linux-hardware.org/?probe=9f3307c5d0) | Oct 17, 2022 |
| ASRock        | X570 Taichi                 | [6b78ca11b4](https://linux-hardware.org/?probe=6b78ca11b4) | Oct 14, 2022 |
| Techvision    | TVI7309X B0                 | [a12d335502](https://linux-hardware.org/?probe=a12d335502) | Oct 06, 2022 |
| Techvision    | TVI7309X B0                 | [fd49fda31a](https://linux-hardware.org/?probe=fd49fda31a) | Oct 06, 2022 |
| ASUSTek       | P5E WS Pro                  | [241e42fa0a](https://linux-hardware.org/?probe=241e42fa0a) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [b0cc9bee74](https://linux-hardware.org/?probe=b0cc9bee74) | Oct 02, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [45d676584c](https://linux-hardware.org/?probe=45d676584c) | Oct 02, 2022 |
| ASUSTek       | Z170-P                      | [996d72bd1e](https://linux-hardware.org/?probe=996d72bd1e) | Sep 30, 2022 |
| ASUSTek       | Z170-P                      | [8394fca38a](https://linux-hardware.org/?probe=8394fca38a) | Sep 30, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [e35b86c3b7](https://linux-hardware.org/?probe=e35b86c3b7) | Sep 29, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [365d74f8e4](https://linux-hardware.org/?probe=365d74f8e4) | Sep 28, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [f9e71e7e05](https://linux-hardware.org/?probe=f9e71e7e05) | Sep 28, 2022 |
| MSI           | X570-A PRO                  | [345959e0ed](https://linux-hardware.org/?probe=345959e0ed) | Sep 28, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [cfd24b9e0a](https://linux-hardware.org/?probe=cfd24b9e0a) | Sep 27, 2022 |
| ASUSTek       | Z87-A                       | [3cdcc8b18d](https://linux-hardware.org/?probe=3cdcc8b18d) | Sep 26, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [d166d32749](https://linux-hardware.org/?probe=d166d32749) | Sep 26, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [bce9addcca](https://linux-hardware.org/?probe=bce9addcca) | Sep 26, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [98e8df2d3d](https://linux-hardware.org/?probe=98e8df2d3d) | Sep 21, 2022 |
| ASUSTek       | P5G41T-M LX                 | [50647a7656](https://linux-hardware.org/?probe=50647a7656) | Sep 17, 2022 |
| ASUSTek       | Z97-A                       | [9de0254ab0](https://linux-hardware.org/?probe=9de0254ab0) | Sep 13, 2022 |
| ASRock        | Z170 Gaming K6+             | [39027cdb44](https://linux-hardware.org/?probe=39027cdb44) | Sep 13, 2022 |
| ASUSTek       | Z170-P                      | [bec58f880f](https://linux-hardware.org/?probe=bec58f880f) | Sep 13, 2022 |
| ASUSTek       | Z170-P                      | [182bb36928](https://linux-hardware.org/?probe=182bb36928) | Sep 13, 2022 |
| ASUSTek       | Benicia                     | [13454a57f9](https://linux-hardware.org/?probe=13454a57f9) | Aug 31, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [a6d3642195](https://linux-hardware.org/?probe=a6d3642195) | Aug 24, 2022 |
| ASUSTek       | PRIME B460M-K               | [f5f3761418](https://linux-hardware.org/?probe=f5f3761418) | Aug 19, 2022 |
| Gigabyte      | P43-ES3G                    | [de6e02672c](https://linux-hardware.org/?probe=de6e02672c) | Aug 18, 2022 |
| Lenovo        | 3098 0B98401 WIN            | [769802c689](https://linux-hardware.org/?probe=769802c689) | Aug 15, 2022 |
| Gigabyte      | P43-ES3G                    | [2b0691bddd](https://linux-hardware.org/?probe=2b0691bddd) | Aug 15, 2022 |
| Packard Be... | P5N-E SLI                   | [6f2bf70c0b](https://linux-hardware.org/?probe=6f2bf70c0b) | Aug 09, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [93bd067b5d](https://linux-hardware.org/?probe=93bd067b5d) | Aug 09, 2022 |
| Packard Be... | P5N-E SLI                   | [cdc88569bc](https://linux-hardware.org/?probe=cdc88569bc) | Aug 07, 2022 |
| ASRock        | B550M Steel Legend          | [0ac4f27d0f](https://linux-hardware.org/?probe=0ac4f27d0f) | Jul 31, 2022 |
| ASRock        | FM2A55M-VG3+                | [5d4a26735e](https://linux-hardware.org/?probe=5d4a26735e) | Jul 28, 2022 |
| Gigabyte      | 970A-DS3P                   | [210b75c48e](https://linux-hardware.org/?probe=210b75c48e) | Jul 21, 2022 |
| Gigabyte      | 970A-DS3P                   | [17befc2dd5](https://linux-hardware.org/?probe=17befc2dd5) | Jul 20, 2022 |
| HP            | 8455                        | [9954a77308](https://linux-hardware.org/?probe=9954a77308) | Jul 07, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [779bc20f77](https://linux-hardware.org/?probe=779bc20f77) | Jul 05, 2022 |
| MSI           | A88XM-E35                   | [8767210da3](https://linux-hardware.org/?probe=8767210da3) | Jul 04, 2022 |
| Shuttle       | FH61V                       | [465dc41fdb](https://linux-hardware.org/?probe=465dc41fdb) | Jun 08, 2022 |
| MSI           | Z390-A PRO                  | [8baf319c52](https://linux-hardware.org/?probe=8baf319c52) | May 21, 2022 |
| Intel         | DG41KR AAE62839-304         | [d6fa39e82f](https://linux-hardware.org/?probe=d6fa39e82f) | May 16, 2022 |
| Foxconn       | 2ADA                        | [215ded6566](https://linux-hardware.org/?probe=215ded6566) | May 16, 2022 |
| Acer          | H57M01                      | [9116ecebcb](https://linux-hardware.org/?probe=9116ecebcb) | May 15, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [52c0b4a6e0](https://linux-hardware.org/?probe=52c0b4a6e0) | May 14, 2022 |
| Acer          | H57M01                      | [42100344af](https://linux-hardware.org/?probe=42100344af) | May 14, 2022 |
| Gigabyte      | H55M-S2H                    | [0b3c6ab0f7](https://linux-hardware.org/?probe=0b3c6ab0f7) | May 14, 2022 |
| ASRock        | H61M-VG4                    | [92f92ef4ee](https://linux-hardware.org/?probe=92f92ef4ee) | Apr 28, 2022 |
| ASRock        | H61M-VG4                    | [fff58f97e8](https://linux-hardware.org/?probe=fff58f97e8) | Apr 27, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [4b9faf4848](https://linux-hardware.org/?probe=4b9faf4848) | Apr 26, 2022 |
| Unknown       | RS780-SB700                 | [eb3aa5fa60](https://linux-hardware.org/?probe=eb3aa5fa60) | Apr 20, 2022 |
| Gigabyte      | Z490M                       | [2138ce9310](https://linux-hardware.org/?probe=2138ce9310) | Apr 18, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [e6aa0c6166](https://linux-hardware.org/?probe=e6aa0c6166) | Apr 09, 2022 |
| Acer          | Revo RL80                   | [414f1870b3](https://linux-hardware.org/?probe=414f1870b3) | Apr 04, 2022 |
| Gigabyte      | H61M-S1                     | [a10a00d2f1](https://linux-hardware.org/?probe=a10a00d2f1) | Apr 03, 2022 |
| Lenovo        | MAHOBAY NOK                 | [ba7b7abd34](https://linux-hardware.org/?probe=ba7b7abd34) | Apr 02, 2022 |
| HP            | 18E5                        | [39cb47db55](https://linux-hardware.org/?probe=39cb47db55) | Mar 28, 2022 |
| HP            | 18E5                        | [061d716ce1](https://linux-hardware.org/?probe=061d716ce1) | Mar 27, 2022 |
| Shuttle       | FH61V                       | [9b18d7b2ed](https://linux-hardware.org/?probe=9b18d7b2ed) | Mar 23, 2022 |
| VIA Techno... | KM266-8235                  | [ad3f9e9e12](https://linux-hardware.org/?probe=ad3f9e9e12) | Mar 20, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [e508dbbb0f](https://linux-hardware.org/?probe=e508dbbb0f) | Mar 05, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [455f94f1d3](https://linux-hardware.org/?probe=455f94f1d3) | Mar 04, 2022 |
| HP            | 339A                        | [820ebf5859](https://linux-hardware.org/?probe=820ebf5859) | Feb 26, 2022 |
| HP            | 339A                        | [118fee2993](https://linux-hardware.org/?probe=118fee2993) | Feb 26, 2022 |
| Dell          | 0773VG A00                  | [d24a3aebe9](https://linux-hardware.org/?probe=d24a3aebe9) | Feb 23, 2022 |
| Gigabyte      | H61M-S1                     | [e667cfc4cf](https://linux-hardware.org/?probe=e667cfc4cf) | Feb 20, 2022 |
| Gigabyte      | H55M-S2H                    | [3031d8a880](https://linux-hardware.org/?probe=3031d8a880) | Feb 20, 2022 |
| Fujitsu Si... | D1784 S26361-D1784          | [2734c5a939](https://linux-hardware.org/?probe=2734c5a939) | Feb 19, 2022 |
| Fujitsu Si... | D1784 S26361-D1784          | [7baecb9fce](https://linux-hardware.org/?probe=7baecb9fce) | Feb 19, 2022 |
| HP            | 339A                        | [d35aeac271](https://linux-hardware.org/?probe=d35aeac271) | Feb 16, 2022 |
| HP            | 339A                        | [aac8acdafe](https://linux-hardware.org/?probe=aac8acdafe) | Feb 16, 2022 |
| Gigabyte      | Z77-HD3                     | [c72849033f](https://linux-hardware.org/?probe=c72849033f) | Feb 15, 2022 |
| Dell          | 02YYK5 A01                  | [bfeed2f132](https://linux-hardware.org/?probe=bfeed2f132) | Feb 14, 2022 |
| ASUSTek       | P8H77-M                     | [b6851e2e2d](https://linux-hardware.org/?probe=b6851e2e2d) | Feb 13, 2022 |
| ASUSTek       | P6T                         | [5084dfc411](https://linux-hardware.org/?probe=5084dfc411) | Feb 12, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [4a136af33b](https://linux-hardware.org/?probe=4a136af33b) | Feb 12, 2022 |
| ASUSTek       | P6T                         | [10a6e04458](https://linux-hardware.org/?probe=10a6e04458) | Feb 10, 2022 |
| Fujitsu Si... | D1784 S26361-D1784          | [843210cfb0](https://linux-hardware.org/?probe=843210cfb0) | Feb 06, 2022 |
| Dell          | 0WR7PY A02                  | [2b3c148135](https://linux-hardware.org/?probe=2b3c148135) | Feb 06, 2022 |
| Gigabyte      | 970A-DS3P                   | [ed2a250420](https://linux-hardware.org/?probe=ed2a250420) | Feb 04, 2022 |
| Gigabyte      | 970A-DS3P                   | [d598fc04e1](https://linux-hardware.org/?probe=d598fc04e1) | Feb 04, 2022 |
| Lenovo        | 3176 NOK                    | [d3a3d5276b](https://linux-hardware.org/?probe=d3a3d5276b) | Feb 02, 2022 |
| Gigabyte      | B250M-D3H-CF                | [5b4a8e5bc4](https://linux-hardware.org/?probe=5b4a8e5bc4) | Jan 29, 2022 |
| Shuttle       | FH61V                       | [6d6980d0bb](https://linux-hardware.org/?probe=6d6980d0bb) | Jan 18, 2022 |
| ASUSTek       | H81M-K                      | [637ad5d9e4](https://linux-hardware.org/?probe=637ad5d9e4) | Jan 18, 2022 |
| ASRock        | AM1H-ITX                    | [0a01195a57](https://linux-hardware.org/?probe=0a01195a57) | Jan 16, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [9fab263b02](https://linux-hardware.org/?probe=9fab263b02) | Jan 11, 2022 |
| ASUSTek       | P5GC-MX                     | [2126180fa9](https://linux-hardware.org/?probe=2126180fa9) | Jan 06, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [3867022c38](https://linux-hardware.org/?probe=3867022c38) | Dec 25, 2021 |
| Gigabyte      | Z77-HD3                     | [a9eceeac28](https://linux-hardware.org/?probe=a9eceeac28) | Dec 14, 2021 |
| Shuttle       | FH61V                       | [b4c8a91d0f](https://linux-hardware.org/?probe=b4c8a91d0f) | Dec 13, 2021 |
| Dell          | 0HN7XN A01                  | [f17f39439e](https://linux-hardware.org/?probe=f17f39439e) | Dec 13, 2021 |
| Gigabyte      | Z77-HD3                     | [75755e4033](https://linux-hardware.org/?probe=75755e4033) | Dec 12, 2021 |
| Gigabyte      | Z77-HD3                     | [7d3626d44d](https://linux-hardware.org/?probe=7d3626d44d) | Dec 12, 2021 |
| ASUSTek       | Z170-K                      | [eb723f5cb0](https://linux-hardware.org/?probe=eb723f5cb0) | Dec 09, 2021 |
| Gigabyte      | H410M S2H                   | [8b917483ef](https://linux-hardware.org/?probe=8b917483ef) | Nov 30, 2021 |
| ASUSTek       | P5QL PRO                    | [ad0c0d07cf](https://linux-hardware.org/?probe=ad0c0d07cf) | Nov 28, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [77a39f82ff](https://linux-hardware.org/?probe=77a39f82ff) | Nov 28, 2021 |
| ASUSTek       | M4A77T/USB3                 | [e23dea02cf](https://linux-hardware.org/?probe=e23dea02cf) | Nov 26, 2021 |
| Gigabyte      | 970A-DS3P                   | [b718c829fa](https://linux-hardware.org/?probe=b718c829fa) | Nov 24, 2021 |
| Intel         | DH77EB AAG39073-304         | [bf7d34f5c1](https://linux-hardware.org/?probe=bf7d34f5c1) | Nov 15, 2021 |
| Intel         | DH77EB AAG39073-304         | [d1e04ead11](https://linux-hardware.org/?probe=d1e04ead11) | Nov 15, 2021 |
| Acer          | EM61SM/EM61PM               | [6a42469739](https://linux-hardware.org/?probe=6a42469739) | Nov 13, 2021 |
| ASRock        | B550M Steel Legend          | [fada2e4c02](https://linux-hardware.org/?probe=fada2e4c02) | Nov 06, 2021 |
| Gigabyte      | GA-M56S-S3                  | [d6285c81a2](https://linux-hardware.org/?probe=d6285c81a2) | Nov 05, 2021 |
| Gigabyte      | H61M-S1                     | [17d03d73f7](https://linux-hardware.org/?probe=17d03d73f7) | Oct 30, 2021 |
| ASRock        | N68C-S UCC                  | [c74421666a](https://linux-hardware.org/?probe=c74421666a) | Oct 20, 2021 |
| Lenovo        | SHARKBAY 31900058 STD       | [cdc6d847a7](https://linux-hardware.org/?probe=cdc6d847a7) | Oct 18, 2021 |
| Gigabyte      | H310M S2H x.x               | [d0b704d0ff](https://linux-hardware.org/?probe=d0b704d0ff) | Oct 06, 2021 |
| Gigabyte      | H81M-S2V                    | [ef8dfe0673](https://linux-hardware.org/?probe=ef8dfe0673) | Oct 02, 2021 |
| ASUSTek       | Maximus VIII HERO           | [1fce457ac6](https://linux-hardware.org/?probe=1fce457ac6) | Oct 01, 2021 |
| MSI           | E3M WORKSTATION V5          | [6924705831](https://linux-hardware.org/?probe=6924705831) | Sep 20, 2021 |
| Gigabyte      | H61M-S1                     | [6207dd28b2](https://linux-hardware.org/?probe=6207dd28b2) | Sep 09, 2021 |
| MSI           | E3M WORKSTATION V5          | [fa6adf65a6](https://linux-hardware.org/?probe=fa6adf65a6) | Aug 23, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [9bf7d4afd7](https://linux-hardware.org/?probe=9bf7d4afd7) | Aug 14, 2021 |
| Dell          | 08HPGT A01                  | [d827460e02](https://linux-hardware.org/?probe=d827460e02) | Aug 04, 2021 |
| ASUSTek       | PRIME B450M-A               | [dc8f396ad8](https://linux-hardware.org/?probe=dc8f396ad8) | Aug 02, 2021 |
| ASUSTek       | M4A88T-V EVO/USB3           | [30b94a4a43](https://linux-hardware.org/?probe=30b94a4a43) | Jul 27, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [925ddff018](https://linux-hardware.org/?probe=925ddff018) | Jul 25, 2021 |
| HP            | ProLiant MicroServer Gen... | [756bb76029](https://linux-hardware.org/?probe=756bb76029) | Jul 25, 2021 |
| ASUSTek       | Z87-K                       | [f548a06642](https://linux-hardware.org/?probe=f548a06642) | Jul 23, 2021 |
| MSI           | B450I GAMING PLUS AC        | [04bf0287f0](https://linux-hardware.org/?probe=04bf0287f0) | Jul 21, 2021 |
| ASUSTek       | PRIME A320M-K 2021-06-11    | [39037104b7](https://linux-hardware.org/?probe=39037104b7) | Jul 17, 2021 |
| ASUSTek       | PRIME A320M-K 2021-06-11    | [a82245240b](https://linux-hardware.org/?probe=a82245240b) | Jul 15, 2021 |
| Intel         | S3000AHLX D40858-208        | [2acfd9617b](https://linux-hardware.org/?probe=2acfd9617b) | Jul 10, 2021 |
| HP            | 843C                        | [01dc34eeb4](https://linux-hardware.org/?probe=01dc34eeb4) | Jul 07, 2021 |
| HP            | 0A54h                       | [10aa52cef5](https://linux-hardware.org/?probe=10aa52cef5) | Jul 06, 2021 |
| ASUSTek       | H81M-K                      | [9d12a5bba7](https://linux-hardware.org/?probe=9d12a5bba7) | Jul 05, 2021 |
| ASRock        | X570M Pro4                  | [a00aea4331](https://linux-hardware.org/?probe=a00aea4331) | Jul 03, 2021 |
| ASUSTek       | PRIME X470-PRO              | [e649a4f85c](https://linux-hardware.org/?probe=e649a4f85c) | Jun 30, 2021 |
| MSI           | H110M PRO-VD                | [83b2318c6a](https://linux-hardware.org/?probe=83b2318c6a) | Jun 26, 2021 |
| Foxconn       | 945 7AD Series              | [9a763d1e1e](https://linux-hardware.org/?probe=9a763d1e1e) | Jun 25, 2021 |
| MSI           | H110M PRO-VD                | [856b9bc825](https://linux-hardware.org/?probe=856b9bc825) | Jun 24, 2021 |
| Intel         | X99                         | [436dda258b](https://linux-hardware.org/?probe=436dda258b) | Jun 21, 2021 |
| Gigabyte      | GA-K8NF-9-RH                | [0cfd20f720](https://linux-hardware.org/?probe=0cfd20f720) | Jun 16, 2021 |
| Gigabyte      | GA-K8NF-9-RH                | [e33a8c0c69](https://linux-hardware.org/?probe=e33a8c0c69) | Jun 16, 2021 |
| ASUSTek       | B85M-G                      | [a390d934b1](https://linux-hardware.org/?probe=a390d934b1) | Jun 13, 2021 |
| Intel         | S3000AHLX D40858-208        | [ab61e363eb](https://linux-hardware.org/?probe=ab61e363eb) | Jun 12, 2021 |
| HP            | 3397                        | [e171bcda3f](https://linux-hardware.org/?probe=e171bcda3f) | Jun 11, 2021 |
| MSI           | B450I GAMING PLUS AC        | [74201da57b](https://linux-hardware.org/?probe=74201da57b) | Jun 11, 2021 |
| HP            | ProLiant ML350 G5           | [297ef6b999](https://linux-hardware.org/?probe=297ef6b999) | Jun 06, 2021 |
| ASRock        | B550 Phantom Gaming-ITX/... | [7c519c91ca](https://linux-hardware.org/?probe=7c519c91ca) | Jun 02, 2021 |
| ASUSTek       | F2A85-V PRO                 | [7950140465](https://linux-hardware.org/?probe=7950140465) | Jun 02, 2021 |
| ASUSTek       | PRIME A320M-K 2020-03-20    | [500976e7d1](https://linux-hardware.org/?probe=500976e7d1) | May 30, 2021 |
| Lenovo        | 0.1                         | [77d8358e26](https://linux-hardware.org/?probe=77d8358e26) | May 28, 2021 |
| Lenovo        | 0.1                         | [d0fbef90ca](https://linux-hardware.org/?probe=d0fbef90ca) | May 27, 2021 |
| Gigabyte      | X58A-UD3R                   | [0b27475327](https://linux-hardware.org/?probe=0b27475327) | May 26, 2021 |
| Pegatron      | 2AD5                        | [794531a511](https://linux-hardware.org/?probe=794531a511) | May 25, 2021 |
| Lenovo        | Tiger Hill                  | [3f61f1be35](https://linux-hardware.org/?probe=3f61f1be35) | May 25, 2021 |
| HP            | 3047h                       | [4fce80ed03](https://linux-hardware.org/?probe=4fce80ed03) | May 20, 2021 |
| MSI           | A75A-G55                    | [f9773bff22](https://linux-hardware.org/?probe=f9773bff22) | May 17, 2021 |
| Intel         | DH87RL AAG74240-402         | [cdb24d5d69](https://linux-hardware.org/?probe=cdb24d5d69) | May 16, 2021 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [e311ba55e3](https://linux-hardware.org/?probe=e311ba55e3) | May 13, 2021 |
| HP            | 843C                        | [e69ec57276](https://linux-hardware.org/?probe=e69ec57276) | May 10, 2021 |
| HP            | 3048h                       | [74f738bae1](https://linux-hardware.org/?probe=74f738bae1) | May 01, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | [b4ef2db7c1](https://linux-hardware.org/?probe=b4ef2db7c1) | May 01, 2021 |
| MSI           | E3M WORKSTATION V5          | [995ec93eb1](https://linux-hardware.org/?probe=995ec93eb1) | Apr 27, 2021 |
| MSI           | E3M WORKSTATION V5          | [228ac8147b](https://linux-hardware.org/?probe=228ac8147b) | Apr 24, 2021 |
| ASUSTek       | PRIME Z370-A                | [19b23587fa](https://linux-hardware.org/?probe=19b23587fa) | Apr 20, 2021 |
| ASUSTek       | PRIME Z370-A                | [80fac11897](https://linux-hardware.org/?probe=80fac11897) | Apr 20, 2021 |
| Foxconn       | G41MX/G41MX-K 2.0 1.0       | [c6ed3bc2f4](https://linux-hardware.org/?probe=c6ed3bc2f4) | Apr 18, 2021 |
| ASRock        | N68C-S UCC                  | [79c0025946](https://linux-hardware.org/?probe=79c0025946) | Apr 04, 2021 |
| MSI           | 760GM-P23                   | [aef62f4f18](https://linux-hardware.org/?probe=aef62f4f18) | Apr 02, 2021 |
| ASUSTek       | PRIME A320M-K 2020-03-20    | [19aaa9b56e](https://linux-hardware.org/?probe=19aaa9b56e) | Mar 30, 2021 |
| Foxconn       | G41MX/G41MX-K 2.0 1.0       | [b72dc7a1c6](https://linux-hardware.org/?probe=b72dc7a1c6) | Mar 29, 2021 |
| ASUSTek       | A8R-MVP                     | [43a7b44e3f](https://linux-hardware.org/?probe=43a7b44e3f) | Mar 27, 2021 |
| ASUSTek       | A8R-MVP                     | [6daa2a372c](https://linux-hardware.org/?probe=6daa2a372c) | Mar 27, 2021 |
| MSI           | E3M WORKSTATION V5          | [0ee0070622](https://linux-hardware.org/?probe=0ee0070622) | Mar 27, 2021 |
| ASUSTek       | P5Q SE2                     | [bcc4de28fb](https://linux-hardware.org/?probe=bcc4de28fb) | Mar 26, 2021 |
| ASRock        | K8A780LM                    | [b8f4c7c2cb](https://linux-hardware.org/?probe=b8f4c7c2cb) | Mar 22, 2021 |
| ASUSTek       | AM1M-A                      | [c3909a14fe](https://linux-hardware.org/?probe=c3909a14fe) | Mar 22, 2021 |
| Gigabyte      | B450M S2H                   | [285b5b2d08](https://linux-hardware.org/?probe=285b5b2d08) | Mar 17, 2021 |
| ASRock        | K8A780LM                    | [d95a56d80f](https://linux-hardware.org/?probe=d95a56d80f) | Mar 15, 2021 |
| Shuttle       | FH61V                       | [3e811ec55d](https://linux-hardware.org/?probe=3e811ec55d) | Mar 13, 2021 |
| ASRock        | H81M-ITX                    | [0f5f41e1ca](https://linux-hardware.org/?probe=0f5f41e1ca) | Mar 08, 2021 |
| ASRock        | H81M-ITX                    | [8599b883d6](https://linux-hardware.org/?probe=8599b883d6) | Mar 08, 2021 |
| ASRock        | FM2A68M-HD+                 | [a9a3d7da6f](https://linux-hardware.org/?probe=a9a3d7da6f) | Mar 05, 2021 |
| ASRock        | B550M Steel Legend          | [4c28c6d22c](https://linux-hardware.org/?probe=4c28c6d22c) | Mar 03, 2021 |
| Shuttle       | FH61V                       | [70d3424aad](https://linux-hardware.org/?probe=70d3424aad) | Mar 02, 2021 |
| ASUSTek       | Rampage II GENE             | [02ec8d4fff](https://linux-hardware.org/?probe=02ec8d4fff) | Mar 01, 2021 |
| Gigabyte      | X58A-UD3R                   | [323b7be7ea](https://linux-hardware.org/?probe=323b7be7ea) | Feb 27, 2021 |
| ASUSTek       | P5KPL-AM SE                 | [3c402e56a5](https://linux-hardware.org/?probe=3c402e56a5) | Feb 26, 2021 |
| Dell          | 0F8096                      | [307334b9d5](https://linux-hardware.org/?probe=307334b9d5) | Feb 24, 2021 |
| Shuttle       | FH61V                       | [f4fe921fe3](https://linux-hardware.org/?probe=f4fe921fe3) | Feb 24, 2021 |
| ASRock        | H81M-ITX                    | [d58331ce9b](https://linux-hardware.org/?probe=d58331ce9b) | Feb 23, 2021 |
| ASUSTek       | M2N-MX SE Plus              | [94f0202173](https://linux-hardware.org/?probe=94f0202173) | Feb 23, 2021 |
| ASUSTek       | A8R-MVP                     | [ce881d4659](https://linux-hardware.org/?probe=ce881d4659) | Feb 23, 2021 |
| ASRock        | K8A780LM                    | [6543fc448e](https://linux-hardware.org/?probe=6543fc448e) | Feb 23, 2021 |
| ASRock        | K8A780LM                    | [ce0076fd09](https://linux-hardware.org/?probe=ce0076fd09) | Feb 23, 2021 |
| ASUSTek       | PRIME B250M-A               | [e33b6a55d2](https://linux-hardware.org/?probe=e33b6a55d2) | Feb 20, 2021 |
| Intel         | D815EEA AAA45884-401        | [248565d49c](https://linux-hardware.org/?probe=248565d49c) | Feb 20, 2021 |
| Intel         | D815EEA AAA45884-401        | [3acc2f0b1e](https://linux-hardware.org/?probe=3acc2f0b1e) | Feb 20, 2021 |
| Gigabyte      | F2A78M-HD2                  | [b8e8be8f5e](https://linux-hardware.org/?probe=b8e8be8f5e) | Feb 20, 2021 |
| ASUSTek       | M4A88T-V EVO/USB3           | [bfbf37268c](https://linux-hardware.org/?probe=bfbf37268c) | Feb 17, 2021 |
| Gigabyte      | X58A-UD3R                   | [f16fabf13a](https://linux-hardware.org/?probe=f16fabf13a) | Feb 16, 2021 |
| MSI           | Z97S SLI Krait Edition      | [9f04601c65](https://linux-hardware.org/?probe=9f04601c65) | Feb 14, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | [abdd5f9208](https://linux-hardware.org/?probe=abdd5f9208) | Feb 14, 2021 |
| Gigabyte      | G31M-S2L                    | [b664ab9762](https://linux-hardware.org/?probe=b664ab9762) | Feb 11, 2021 |
| Gigabyte      | G31M-S2L                    | [aa7f6024cf](https://linux-hardware.org/?probe=aa7f6024cf) | Feb 10, 2021 |
| ASUSTek       | PRIME X470-PRO              | [715d706afe](https://linux-hardware.org/?probe=715d706afe) | Feb 10, 2021 |
| Dell          | 0PU052                      | [8e0d1be6bf](https://linux-hardware.org/?probe=8e0d1be6bf) | Feb 09, 2021 |
| ASUSTek       | M2N-MX SE Plus              | [a8985150bd](https://linux-hardware.org/?probe=a8985150bd) | Feb 08, 2021 |
| ASUSTek       | P5KPL-SE                    | [83be789e3c](https://linux-hardware.org/?probe=83be789e3c) | Feb 07, 2021 |
| ASUSTek       | P5KPL-SE                    | [ca67f71815](https://linux-hardware.org/?probe=ca67f71815) | Feb 06, 2021 |
| ASRock        | H81M-ITX                    | [7b2d6774c8](https://linux-hardware.org/?probe=7b2d6774c8) | Feb 05, 2021 |
| Dell          | 0PU052                      | [cc4b4c54d6](https://linux-hardware.org/?probe=cc4b4c54d6) | Feb 01, 2021 |
| MSI           | MS-7388                     | [6fc9a5690d](https://linux-hardware.org/?probe=6fc9a5690d) | Feb 01, 2021 |
| Gigabyte      | B360M H 2019-01-02          | [6b2b3ee651](https://linux-hardware.org/?probe=6b2b3ee651) | Jan 28, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [845de5bee0](https://linux-hardware.org/?probe=845de5bee0) | Jan 22, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [a875950ed5](https://linux-hardware.org/?probe=a875950ed5) | Jan 22, 2021 |
| ASUSTek       | PRIME X470-PRO              | [b28f7278cd](https://linux-hardware.org/?probe=b28f7278cd) | Jan 21, 2021 |
| Dell          | 0F8096                      | [27186bb8eb](https://linux-hardware.org/?probe=27186bb8eb) | Jan 18, 2021 |
| Intel         | DH87RL AAG74240-402         | [926473c2ac](https://linux-hardware.org/?probe=926473c2ac) | Jan 16, 2021 |
| Intel         | S3000AHLX D40858-208        | [8508696f16](https://linux-hardware.org/?probe=8508696f16) | Jan 16, 2021 |
| ASRock        | K8A780LM                    | [2e54aedb9e](https://linux-hardware.org/?probe=2e54aedb9e) | Jan 14, 2021 |
| ASRock        | H81M-ITX                    | [50e5d36672](https://linux-hardware.org/?probe=50e5d36672) | Jan 14, 2021 |
| ASUSTek       | A8R-MVP                     | [62ab746796](https://linux-hardware.org/?probe=62ab746796) | Jan 14, 2021 |
| ASUSTek       | M2N-MX SE Plus              | [f6a8e9eaf5](https://linux-hardware.org/?probe=f6a8e9eaf5) | Jan 14, 2021 |
| ASUSTek       | A8R-MVP                     | [00e4deffa2](https://linux-hardware.org/?probe=00e4deffa2) | Jan 14, 2021 |
| Intel         | DH87RL AAG74240-402         | [dcbc8e3b20](https://linux-hardware.org/?probe=dcbc8e3b20) | Jan 14, 2021 |
| Intel         | DH87RL AAG74240-402         | [4877506709](https://linux-hardware.org/?probe=4877506709) | Jan 14, 2021 |
| MSI           | E3M WORKSTATION V5          | [67805433c0](https://linux-hardware.org/?probe=67805433c0) | Jan 13, 2021 |
| Intel         | DH87RL AAG74240-402         | [5e67f36f68](https://linux-hardware.org/?probe=5e67f36f68) | Jan 12, 2021 |
| HP            | 1495                        | [ffb9d2f433](https://linux-hardware.org/?probe=ffb9d2f433) | Jan 08, 2021 |
| ASRock        | B550M Steel Legend          | [a6b6bbef69](https://linux-hardware.org/?probe=a6b6bbef69) | Jan 07, 2021 |
| ASUSTek       | B85M-G                      | [5e66fb7f43](https://linux-hardware.org/?probe=5e66fb7f43) | Jan 07, 2021 |
| ASUSTek       | B85M-G                      | [e7c1c02ce7](https://linux-hardware.org/?probe=e7c1c02ce7) | Jan 07, 2021 |
| Gigabyte      | 970A-DS3P                   | [fa54fc6400](https://linux-hardware.org/?probe=fa54fc6400) | Jan 05, 2021 |
| HP            | 843C                        | [e6c805f9dd](https://linux-hardware.org/?probe=e6c805f9dd) | Jan 04, 2021 |
| Gigabyte      | M4HM87P-00                  | [3523a7845f](https://linux-hardware.org/?probe=3523a7845f) | Jan 04, 2021 |
| Gigabyte      | P35-DS3R                    | [af4f72e797](https://linux-hardware.org/?probe=af4f72e797) | Jan 04, 2021 |
| ASUSTek       | Z170-K                      | [1cdae8bcc1](https://linux-hardware.org/?probe=1cdae8bcc1) | Jan 01, 2021 |
| Gigabyte      | B250M-D3H-CF                | [192fd63a7c](https://linux-hardware.org/?probe=192fd63a7c) | Dec 27, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [e9db8f5ca6](https://linux-hardware.org/?probe=e9db8f5ca6) | Dec 23, 2020 |
| ASRock        | B550M Steel Legend          | [a733d01196](https://linux-hardware.org/?probe=a733d01196) | Dec 22, 2020 |
| ASRock        | B550M Steel Legend          | [bd927d4e12](https://linux-hardware.org/?probe=bd927d4e12) | Dec 22, 2020 |
| ASRock        | B550M Steel Legend          | [a41b1e7e12](https://linux-hardware.org/?probe=a41b1e7e12) | Dec 22, 2020 |
| ASUSTek       | M4A88T-V EVO/USB3           | [7a5a80d939](https://linux-hardware.org/?probe=7a5a80d939) | Dec 20, 2020 |
| MSI           | B85-G43 GAMING              | [915d83d090](https://linux-hardware.org/?probe=915d83d090) | Dec 19, 2020 |
| Gigabyte      | F2A68HM-DS2                 | [7746ff0cda](https://linux-hardware.org/?probe=7746ff0cda) | Dec 15, 2020 |
| Gigabyte      | GA-MA78GM-US2H              | [0719c37bbd](https://linux-hardware.org/?probe=0719c37bbd) | Dec 13, 2020 |
| ASUSTek       | P5QL-E                      | [b74c06cc19](https://linux-hardware.org/?probe=b74c06cc19) | Dec 03, 2020 |
| ASUSTek       | P5QL-E                      | [c3770ada06](https://linux-hardware.org/?probe=c3770ada06) | Dec 03, 2020 |
| ASUSTek       | Rampage II GENE             | [53d482a443](https://linux-hardware.org/?probe=53d482a443) | Nov 17, 2020 |
| ASUSTek       | Rampage II GENE             | [1ab17cdc86](https://linux-hardware.org/?probe=1ab17cdc86) | Nov 15, 2020 |
| HP            | 3646h                       | [747ede17e0](https://linux-hardware.org/?probe=747ede17e0) | Nov 12, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [8a6ca29d49](https://linux-hardware.org/?probe=8a6ca29d49) | Nov 08, 2020 |
| ASUSTek       | P5LD2-X/1333                | [fec864df41](https://linux-hardware.org/?probe=fec864df41) | Nov 01, 2020 |
| HP            | 3396                        | [73bbba4a08](https://linux-hardware.org/?probe=73bbba4a08) | Oct 29, 2020 |
| HP            | 0AA8h                       | [49ed8250dd](https://linux-hardware.org/?probe=49ed8250dd) | Oct 27, 2020 |
| Gigabyte      | P67X-UD3-B3                 | [67dbb5a0d2](https://linux-hardware.org/?probe=67dbb5a0d2) | Oct 18, 2020 |
| Gigabyte      | P67X-UD3-B3                 | [9f49d2fb4f](https://linux-hardware.org/?probe=9f49d2fb4f) | Oct 18, 2020 |
| Dell          | 0RN474                      | [766ce09345](https://linux-hardware.org/?probe=766ce09345) | Oct 17, 2020 |
| ASUSTek       | F2A55-M LK2 PLUS            | [1457975a9b](https://linux-hardware.org/?probe=1457975a9b) | Oct 12, 2020 |
| Gigabyte      | Z270X-Gaming 5              | [152291e032](https://linux-hardware.org/?probe=152291e032) | Oct 07, 2020 |
| MSI           | B360 GAMING PLUS            | [a75b777bc2](https://linux-hardware.org/?probe=a75b777bc2) | Oct 04, 2020 |
| Insyde        | SugarBay                    | [ec1ec65380](https://linux-hardware.org/?probe=ec1ec65380) | Oct 01, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | [e77ec16bac](https://linux-hardware.org/?probe=e77ec16bac) | Sep 29, 2020 |
| Dell          | 0T10XW A00                  | [78018fdd06](https://linux-hardware.org/?probe=78018fdd06) | Sep 20, 2020 |
| HP            | 86FB MVB A                  | [71e7c31b65](https://linux-hardware.org/?probe=71e7c31b65) | Sep 15, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [cad15a6d4c](https://linux-hardware.org/?probe=cad15a6d4c) | Sep 04, 2020 |
| ASUSTek       | PRIME A320M-K               | [d968666b2d](https://linux-hardware.org/?probe=d968666b2d) | Sep 03, 2020 |
| Gigabyte      | H61M-S1                     | [afc3f83ad0](https://linux-hardware.org/?probe=afc3f83ad0) | Sep 02, 2020 |
| Gigabyte      | G31M-S2L                    | [b2fd45876a](https://linux-hardware.org/?probe=b2fd45876a) | Aug 30, 2020 |
| ASUSTek       | P5GC-MX/1333                | [566417bef1](https://linux-hardware.org/?probe=566417bef1) | Aug 30, 2020 |
| ASUSTek       | M5A78L-M LX                 | [2fbe460b8a](https://linux-hardware.org/?probe=2fbe460b8a) | Aug 16, 2020 |
| ASUSTek       | P8Z68-V PRO                 | [5ffffc7647](https://linux-hardware.org/?probe=5ffffc7647) | Aug 06, 2020 |
| Intel         | D945GCCR AAD78647-300       | [c0beab131f](https://linux-hardware.org/?probe=c0beab131f) | Jul 25, 2020 |
| Intel         | D945GCCR AAD78647-300       | [153c0aab66](https://linux-hardware.org/?probe=153c0aab66) | Jul 25, 2020 |
| Gigabyte      | GC330UD                     | [bdfbe25730](https://linux-hardware.org/?probe=bdfbe25730) | Jul 25, 2020 |
| ASUSTek       | H110M-A/M.2                 | [c570792811](https://linux-hardware.org/?probe=c570792811) | Jul 24, 2020 |
| ASUSTek       | H110M-A/M.2                 | [a3dc30f185](https://linux-hardware.org/?probe=a3dc30f185) | Jul 21, 2020 |
| ASUSTek       | H110M-A/M.2                 | [ef6922214a](https://linux-hardware.org/?probe=ef6922214a) | Jul 20, 2020 |
| ASUSTek       | M5A78L-M LX                 | [332ddc42d4](https://linux-hardware.org/?probe=332ddc42d4) | Jul 16, 2020 |
| ASUSTek       | PRIME Z270-A                | [dc205c9f7e](https://linux-hardware.org/?probe=dc205c9f7e) | Jul 13, 2020 |
| ASUSTek       | PRIME Z270-A                | [b02e3bb9e8](https://linux-hardware.org/?probe=b02e3bb9e8) | Jul 13, 2020 |
| ASRock        | H61M-VG4                    | [2f9520527b](https://linux-hardware.org/?probe=2f9520527b) | Jul 11, 2020 |
| ASRock        | H61M-VG4                    | [b36bc5f47e](https://linux-hardware.org/?probe=b36bc5f47e) | Jul 11, 2020 |
| ASUSTek       | F2A55-M LK2 PLUS            | [08f2adba8a](https://linux-hardware.org/?probe=08f2adba8a) | Jul 11, 2020 |
| ASUSTek       | F2A55-M LK2 PLUS            | [c6ed1cd30d](https://linux-hardware.org/?probe=c6ed1cd30d) | Jul 11, 2020 |
| ASUSTek       | P5KPL-AM EPU                | [6ab55c2cfa](https://linux-hardware.org/?probe=6ab55c2cfa) | Jul 03, 2020 |
| ASUSTek       | P5KPL-AM EPU                | [a4b6a8dfb6](https://linux-hardware.org/?probe=a4b6a8dfb6) | Jul 02, 2020 |
| ASUSTek       | M4N78-AM V2                 | [ce2c44ec00](https://linux-hardware.org/?probe=ce2c44ec00) | Jun 16, 2020 |
| ASUSTek       | P7P55D                      | [eeef655b1c](https://linux-hardware.org/?probe=eeef655b1c) | Jun 07, 2020 |
| ASUSTek       | P5P43TD PRO                 | [bdafad0c82](https://linux-hardware.org/?probe=bdafad0c82) | Jun 06, 2020 |
| MSI           | B150M MORTAR                | [7cdf6f047d](https://linux-hardware.org/?probe=7cdf6f047d) | Jun 01, 2020 |
| ASUSTek       | P5P43TD PRO                 | [38acad164f](https://linux-hardware.org/?probe=38acad164f) | May 25, 2020 |
| Pegatron      | 2A73h                       | [0161ecea31](https://linux-hardware.org/?probe=0161ecea31) | May 19, 2020 |
| Pegatron      | 2A73h                       | [42d74e715d](https://linux-hardware.org/?probe=42d74e715d) | May 15, 2020 |
| ASUSTek       | Maximus IX APEX             | [0725349aa7](https://linux-hardware.org/?probe=0725349aa7) | May 11, 2020 |
| Gigabyte      | H61M-S1                     | [b14767e270](https://linux-hardware.org/?probe=b14767e270) | May 07, 2020 |
| ASUSTek       | P5QL-E                      | [d1b8d74839](https://linux-hardware.org/?probe=d1b8d74839) | May 05, 2020 |
| ASUSTek       | M2N-CM DVI                  | [723d371342](https://linux-hardware.org/?probe=723d371342) | Apr 27, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [ebd71cc64d](https://linux-hardware.org/?probe=ebd71cc64d) | Apr 18, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [bbd20923db](https://linux-hardware.org/?probe=bbd20923db) | Apr 18, 2020 |
| Gigabyte      | EP35-DS3                    | [686cd298e3](https://linux-hardware.org/?probe=686cd298e3) | Apr 13, 2020 |
| HP            | 3646h                       | [96421cb602](https://linux-hardware.org/?probe=96421cb602) | Apr 06, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [e6c9f406df](https://linux-hardware.org/?probe=e6c9f406df) | Apr 04, 2020 |
| HP            | 86FB MVB A                  | [91e5642800](https://linux-hardware.org/?probe=91e5642800) | Apr 02, 2020 |
| HP            | 86FB MVB A                  | [95ece68ba4](https://linux-hardware.org/?probe=95ece68ba4) | Apr 02, 2020 |
| ASRock        | 960GC-GS FX                 | [a450257a10](https://linux-hardware.org/?probe=a450257a10) | Mar 31, 2020 |
| Lenovo        | SHARKBAY 31900058 STD       | [92917041c1](https://linux-hardware.org/?probe=92917041c1) | Mar 31, 2020 |
| MSI           | B150M MORTAR                | [99a354df1f](https://linux-hardware.org/?probe=99a354df1f) | Mar 31, 2020 |
| ASUSTek       | VM42                        | [29c87fb102](https://linux-hardware.org/?probe=29c87fb102) | Mar 25, 2020 |
| Intel         | DH87RL AAG74240-402         | [fce111bb71](https://linux-hardware.org/?probe=fce111bb71) | Mar 19, 2020 |
| ASUSTek       | P5LD2-X/1333                | [d278f46944](https://linux-hardware.org/?probe=d278f46944) | Mar 19, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [4af2951135](https://linux-hardware.org/?probe=4af2951135) | Mar 02, 2020 |
| Gigabyte      | X58A-UD3R                   | [58c69a16ec](https://linux-hardware.org/?probe=58c69a16ec) | Feb 29, 2020 |
| Gigabyte      | H61M-S1                     | [b5ef9a6442](https://linux-hardware.org/?probe=b5ef9a6442) | Feb 28, 2020 |
| Gigabyte      | X58A-UD3R                   | [4e592e37d9](https://linux-hardware.org/?probe=4e592e37d9) | Feb 28, 2020 |
| Gigabyte      | AB350-Gaming 3-CF           | [b0a4a95414](https://linux-hardware.org/?probe=b0a4a95414) | Feb 22, 2020 |
| ASUSTek       | M2N-CM DVI                  | [e808fea491](https://linux-hardware.org/?probe=e808fea491) | Feb 14, 2020 |
| MSI           | MS-6702                     | [86b96afa86](https://linux-hardware.org/?probe=86b96afa86) | Feb 07, 2020 |
| Lenovo        | ThinkCentre M58p 7484WHT    | [69debaef8a](https://linux-hardware.org/?probe=69debaef8a) | Feb 06, 2020 |
| MSI           | MS-6702                     | [16256584cd](https://linux-hardware.org/?probe=16256584cd) | Jan 29, 2020 |
| Gigabyte      | AB350-Gaming 3-CF           | [b839b04f7b](https://linux-hardware.org/?probe=b839b04f7b) | Jan 24, 2020 |
| Intel         | Bearlake Fab D              | [6c46de300b](https://linux-hardware.org/?probe=6c46de300b) | Jan 20, 2020 |
| ASRock        | K8A780LM                    | [e0d3030787](https://linux-hardware.org/?probe=e0d3030787) | Jan 18, 2020 |
| ASRock        | K8A780LM                    | [83dca94e72](https://linux-hardware.org/?probe=83dca94e72) | Jan 17, 2020 |
| ASRock        | K8A780LM                    | [a5e0479887](https://linux-hardware.org/?probe=a5e0479887) | Jan 16, 2020 |
| MSI           | MS-6702                     | [e78238313a](https://linux-hardware.org/?probe=e78238313a) | Jan 13, 2020 |
| Gigabyte      | P31-ES3G                    | [57ed00d8a8](https://linux-hardware.org/?probe=57ed00d8a8) | Jan 08, 2020 |
| ASUSTek       | P5QL-E                      | [6949452f0e](https://linux-hardware.org/?probe=6949452f0e) | Dec 25, 2019 |
| ASUSTek       | P5LD2-X/1333                | [e643b8ed58](https://linux-hardware.org/?probe=e643b8ed58) | Dec 25, 2019 |
| Unknown       | Unknown                     | [4050b2d0d1](https://linux-hardware.org/?probe=4050b2d0d1) | Dec 25, 2019 |
| Unknown       | Unknown                     | [ca23ab1ec8](https://linux-hardware.org/?probe=ca23ab1ec8) | Dec 25, 2019 |
| ASRock        | H81M-ITX                    | [c51735ee45](https://linux-hardware.org/?probe=c51735ee45) | Dec 21, 2019 |
| MSI           | MS-7199                     | [8fe7e9e6a6](https://linux-hardware.org/?probe=8fe7e9e6a6) | Dec 21, 2019 |
| ASUSTek       | VM42                        | [66ad05d5ab](https://linux-hardware.org/?probe=66ad05d5ab) | Dec 12, 2019 |
| Intel         | DZ77GA-70K AAG39009-401     | [44917a35a9](https://linux-hardware.org/?probe=44917a35a9) | Dec 12, 2019 |
| MSI           | MS-6702                     | [792cf869f8](https://linux-hardware.org/?probe=792cf869f8) | Nov 26, 2019 |
| MSI           | 09AC                        | [9188878c2a](https://linux-hardware.org/?probe=9188878c2a) | Nov 19, 2019 |
| ASUSTek       | M2N-E                       | [bb3948f168](https://linux-hardware.org/?probe=bb3948f168) | Nov 15, 2019 |
| ASUSTek       | M2N-E                       | [dc0d15703c](https://linux-hardware.org/?probe=dc0d15703c) | Nov 15, 2019 |
| ASUSTek       | M2N-E                       | [8a49a38575](https://linux-hardware.org/?probe=8a49a38575) | Nov 14, 2019 |
| ASUSTek       | M2N-E                       | [6522851ca9](https://linux-hardware.org/?probe=6522851ca9) | Nov 14, 2019 |
| MSI           | MS-6702                     | [05aa9bf00f](https://linux-hardware.org/?probe=05aa9bf00f) | Nov 13, 2019 |
| Gigabyte      | B360M D3H-CF                | [1c1d5c438a](https://linux-hardware.org/?probe=1c1d5c438a) | Nov 11, 2019 |
| Acer          | Aspire TC-705               | [b732ce4528](https://linux-hardware.org/?probe=b732ce4528) | Nov 04, 2019 |
| ASUSTek       | A8N-E                       | [16b128fafe](https://linux-hardware.org/?probe=16b128fafe) | Nov 04, 2019 |
| ASRock        | H81M-ITX                    | [431ea0cbed](https://linux-hardware.org/?probe=431ea0cbed) | Oct 25, 2019 |
| Dell          | 0F8096                      | [d1f6910c12](https://linux-hardware.org/?probe=d1f6910c12) | Oct 20, 2019 |
| ASUSTek       | M2N-MX SE Plus              | [f4fcd6e28c](https://linux-hardware.org/?probe=f4fcd6e28c) | Oct 20, 2019 |
| ASRock        | H81M-ITX                    | [c5f47f2f27](https://linux-hardware.org/?probe=c5f47f2f27) | Oct 20, 2019 |
| ASUSTek       | M2N-E                       | [96f3d49886](https://linux-hardware.org/?probe=96f3d49886) | Oct 11, 2019 |
| ASUSTek       | M2N-E                       | [5d2552d841](https://linux-hardware.org/?probe=5d2552d841) | Oct 11, 2019 |
| ASUSTek       | M2N-E                       | [c7128161ce](https://linux-hardware.org/?probe=c7128161ce) | Sep 22, 2019 |
| MSI           | MS-6702                     | [72a17e9871](https://linux-hardware.org/?probe=72a17e9871) | Sep 17, 2019 |
| ASUSTek       | H97-PLUS                    | [fc8496dd5a](https://linux-hardware.org/?probe=fc8496dd5a) | Sep 07, 2019 |
| MSI           | MS-6702                     | [3049044a80](https://linux-hardware.org/?probe=3049044a80) | Aug 26, 2019 |
| MSI           | MS-6702                     | [ab947df2c3](https://linux-hardware.org/?probe=ab947df2c3) | Aug 18, 2019 |
| MSI           | MS-6702                     | [3f6b808c8b](https://linux-hardware.org/?probe=3f6b808c8b) | Aug 14, 2019 |
| Dell          | 0DN075                      | [07c3b02228](https://linux-hardware.org/?probe=07c3b02228) | Aug 09, 2019 |
| ASUSTek       | H110M-C                     | [75e32af34d](https://linux-hardware.org/?probe=75e32af34d) | Jul 13, 2019 |
| ASUSTek       | P5L-MX                      | [0c62c4c191](https://linux-hardware.org/?probe=0c62c4c191) | Jun 23, 2019 |
| ASUSTek       | H81M-PLUS                   | [068460eef5](https://linux-hardware.org/?probe=068460eef5) | Jun 15, 2019 |
| MSI           | MS-7407 100                 | [245e00b979](https://linux-hardware.org/?probe=245e00b979) | May 31, 2019 |
| MSI           | MS-6702                     | [1ed53a3a07](https://linux-hardware.org/?probe=1ed53a3a07) | May 05, 2019 |
| ASUSTek       | H110M-C                     | [49d390f38b](https://linux-hardware.org/?probe=49d390f38b) | Apr 14, 2019 |
| ASUSTek       | H110M-C                     | [f48d00866d](https://linux-hardware.org/?probe=f48d00866d) | Apr 10, 2019 |
| Intel         | D925XECV2 AAC83685-205      | [8987ff9068](https://linux-hardware.org/?probe=8987ff9068) | Apr 06, 2019 |
| ASUSTek       | P8Z77-V LX2                 | [6266e950d1](https://linux-hardware.org/?probe=6266e950d1) | Apr 05, 2019 |
| ASUSTek       | M2N-E                       | [59375f9231](https://linux-hardware.org/?probe=59375f9231) | Apr 03, 2019 |
| MSI           | MS-6702                     | [dc92061311](https://linux-hardware.org/?probe=dc92061311) | Apr 02, 2019 |
| MSI           | MS-6702                     | [d62caac198](https://linux-hardware.org/?probe=d62caac198) | Apr 01, 2019 |
| Lenovo        | Tiger Hill                  | [edb984c4e6](https://linux-hardware.org/?probe=edb984c4e6) | Mar 05, 2019 |
| Gigabyte      | F2A68HM-DS2                 | [0ca153c41c](https://linux-hardware.org/?probe=0ca153c41c) | Feb 02, 2019 |
| Dell          | Precision WorkStation 39... | [6040d653c3](https://linux-hardware.org/?probe=6040d653c3) | Jan 09, 2019 |
| Gigabyte      | GA-MA78GM-US2H              | [505cff22f1](https://linux-hardware.org/?probe=505cff22f1) | Nov 11, 2018 |
| Gigabyte      | Z77X-D3H                    | [d9fcab9ba7](https://linux-hardware.org/?probe=d9fcab9ba7) | Nov 03, 2018 |
| HP            | 3047h                       | [bd13661f57](https://linux-hardware.org/?probe=bd13661f57) | Oct 26, 2018 |
| HP            | 3047h                       | [64f2865562](https://linux-hardware.org/?probe=64f2865562) | Oct 26, 2018 |
| Dell          | 0DN075                      | [2951e393ca](https://linux-hardware.org/?probe=2951e393ca) | Jun 02, 2018 |
| MSI           | G41TM-P33                   | [1622e88ef5](https://linux-hardware.org/?probe=1622e88ef5) | Apr 25, 2018 |
| MSI           | G41TM-P33                   | [e05768e40a](https://linux-hardware.org/?probe=e05768e40a) | Apr 12, 2018 |
| MSI           | A88X-G45 GAMING             | [985c8f6bb3](https://linux-hardware.org/?probe=985c8f6bb3) | Jan 25, 2018 |
| MSI           | G41TM-P33                   | [3175c5de11](https://linux-hardware.org/?probe=3175c5de11) | Nov 13, 2017 |
| Gigabyte      | P41-ES3G                    | [f6a2b721dc](https://linux-hardware.org/?probe=f6a2b721dc) | Oct 12, 2017 |
| ASUSTek       | N3700T                      | [175b0f5a5d](https://linux-hardware.org/?probe=175b0f5a5d) | Oct 01, 2017 |
| ASUSTek       | TUF Z270 MARK 1             | [2308897059](https://linux-hardware.org/?probe=2308897059) | Jul 03, 2017 |
| MSI           | G41TM-P33                   | [54f6608d0d](https://linux-hardware.org/?probe=54f6608d0d) | Mar 29, 2017 |
| Gigabyte      | P41-ES3G                    | [f2e7fc2411](https://linux-hardware.org/?probe=f2e7fc2411) | Mar 13, 2017 |
| MSI           | G41TM-P33                   | [f585f0a037](https://linux-hardware.org/?probe=f585f0a037) | Feb 22, 2017 |
| MSI           | G41TM-P33                   | [a14f2598e7](https://linux-hardware.org/?probe=a14f2598e7) | Feb 22, 2017 |
| Gigabyte      | M61PME-S2P                  | [f27dd0a73e](https://linux-hardware.org/?probe=f27dd0a73e) | Feb 15, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 20.04       | 38       | 12.71%  |
| Ubuntu 18.04       | 18       | 6.02%   |
| Ubuntu 22.04       | 15       | 5.02%   |
| OpenMandriva 4.2   | 13       | 4.35%   |
| BlackPanther 18.1  | 13       | 4.35%   |
| OpenMandriva 4.3   | 10       | 3.34%   |
| ROSA R10           | 6        | 2.01%   |
| Linux Mint 21.1    | 6        | 2.01%   |
| Linux Mint 20.1    | 6        | 2.01%   |
| Zorin 16           | 5        | 1.67%   |
| Ubuntu 19.10       | 5        | 1.67%   |
| ROSA R9            | 5        | 1.67%   |
| Linux Mint 20.2    | 5        | 1.67%   |
| Pop!_OS 22.04      | 4        | 1.34%   |
| OpenMandriva 4.50  | 4        | 1.34%   |
| OpenMandriva 23.01 | 4        | 1.34%   |
| MX 19              | 4        | 1.34%   |
| Linux Mint 21      | 4        | 1.34%   |
| Linux Mint 20.3    | 4        | 1.34%   |
| Linux Mint 20      | 4        | 1.34%   |
| Debian 11          | 4        | 1.34%   |
| Xubuntu 18.04      | 3        | 1%      |
| Ubuntu 18.10       | 3        | 1%      |
| ROSA R11           | 3        | 1%      |
| Pop!_OS 21.10      | 3        | 1%      |
| Pop!_OS 20.04      | 3        | 1%      |
| OpenMandriva 23.03 | 3        | 1%      |
| MX 18              | 3        | 1%      |
| Manjaro 20.1       | 3        | 1%      |
| Linux Mint 19.3    | 3        | 1%      |
| Fedora 34          | 3        | 1%      |
| Fedora 33          | 3        | 1%      |
| Debian 10          | 3        | 1%      |
| Arch Rolling       | 3        | 1%      |
| Ubuntu 20.10       | 2        | 0.67%   |
| ROSA R8            | 2        | 0.67%   |
| Pop!_OS 20.10      | 2        | 0.67%   |
| openSUSE Leap-15.3 | 2        | 0.67%   |
| OpenMandriva 4.90  | 2        | 0.67%   |
| OpenMandriva 22.12 | 2        | 0.67%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 80       | 29.09%  |
| OpenMandriva | 37       | 13.45%  |
| Linux Mint   | 32       | 11.64%  |
| ROSA         | 16       | 5.82%   |
| BlackPanther | 14       | 5.09%   |
| Pop!_OS      | 12       | 4.36%   |
| Fedora       | 12       | 4.36%   |
| Debian       | 9        | 3.27%   |
| MX           | 7        | 2.55%   |
| Manjaro      | 7        | 2.55%   |
| Xubuntu      | 6        | 2.18%   |
| Zorin        | 5        | 1.82%   |
| Arch         | 5        | 1.82%   |
| openSUSE     | 3        | 1.09%   |
| Kubuntu      | 3        | 1.09%   |
| Gentoo       | 3        | 1.09%   |
| Devuan       | 3        | 1.09%   |
| ArcoLinux    | 3        | 1.09%   |
| Ubuntu Unity | 2        | 0.73%   |
| Lubuntu      | 2        | 0.73%   |
| LMDE         | 2        | 0.73%   |
| KDE neon     | 2        | 0.73%   |
| Garuda Linux | 2        | 0.73%   |
| Q4OS         | 1        | 0.36%   |
| Nobara       | 1        | 0.36%   |
| Mageia       | 1        | 0.36%   |
| Endless      | 1        | 0.36%   |
| CentOS       | 1        | 0.36%   |
| BunsenLabs   | 1        | 0.36%   |
| Archcraft    | 1        | 0.36%   |
| antiX        | 1        | 0.36%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 4.18.16-desktop-1bP             | 13       | 3.76%   |
| 5.10.14-desktop-1omv4002        | 12       | 3.47%   |
| 5.16.7-desktop-1omv4003         | 9        | 2.6%    |
| 5.4.0-58-generic                | 6        | 1.73%   |
| 5.15.0-43-generic               | 6        | 1.73%   |
| 4.19.0-14-amd64                 | 5        | 1.45%   |
| 4.19.0-13-amd64                 | 5        | 1.45%   |
| 6.1.1-desktop-1omv2290          | 4        | 1.16%   |
| 5.8.0-44-generic                | 4        | 1.16%   |
| 5.19.0-38-generic               | 4        | 1.16%   |
| 6.2.6-desktop-1omv2390          | 3        | 0.87%   |
| 5.4.0-90-generic                | 3        | 0.87%   |
| 5.4.0-77-generic                | 3        | 0.87%   |
| 5.4.0-65-generic                | 3        | 0.87%   |
| 5.4.0-52-generic                | 3        | 0.87%   |
| 5.4.0-26-generic                | 3        | 0.87%   |
| 5.3.0-40-generic                | 3        | 0.87%   |
| 5.15.0-56-generic               | 3        | 0.87%   |
| 5.15.0-48-generic               | 3        | 0.87%   |
| 5.15.0-46-generic               | 3        | 0.87%   |
| 5.13.0-30-generic               | 3        | 0.87%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 3        | 0.87%   |
| 4.18.0-17-generic               | 3        | 0.87%   |
| 4.15.0-66-generic               | 3        | 0.87%   |
| 6.1.0-6-amd64                   | 2        | 0.58%   |
| 6.0.12-76060006-generic         | 2        | 0.58%   |
| 6.0.10-desktop-2omv22090        | 2        | 0.58%   |
| 5.8.0-43-generic                | 2        | 0.58%   |
| 5.8.0-41-generic                | 2        | 0.58%   |
| 5.4.0-7634-generic              | 2        | 0.58%   |
| 5.4.0-74-generic                | 2        | 0.58%   |
| 5.4.0-73-generic                | 2        | 0.58%   |
| 5.4.0-66-generic                | 2        | 0.58%   |
| 5.4.0-42-generic                | 2        | 0.58%   |
| 5.4.0-33-generic                | 2        | 0.58%   |
| 5.4.0-144-generic               | 2        | 0.58%   |
| 5.3.0-42-generic                | 2        | 0.58%   |
| 5.3.0-26-generic                | 2        | 0.58%   |
| 5.3.0-24-generic                | 2        | 0.58%   |
| 5.18.12-desktop-3omv4090        | 2        | 0.58%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 46       | 14.65%  |
| 5.15.0  | 28       | 8.92%   |
| 4.15.0  | 20       | 6.37%   |
| 5.8.0   | 17       | 5.41%   |
| 4.18.16 | 14       | 4.46%   |
| 5.3.0   | 13       | 4.14%   |
| 5.10.14 | 12       | 3.82%   |
| 5.13.0  | 10       | 3.18%   |
| 5.16.7  | 9        | 2.87%   |
| 5.11.0  | 9        | 2.87%   |
| 5.19.0  | 8        | 2.55%   |
| 4.18.0  | 8        | 2.55%   |
| 4.19.0  | 7        | 2.23%   |
| 5.10.0  | 5        | 1.59%   |
| 6.1.1   | 4        | 1.27%   |
| 6.2.6   | 3        | 0.96%   |
| 6.1.0   | 3        | 0.96%   |
| 4.9.60  | 3        | 0.96%   |
| 6.1.10  | 2        | 0.64%   |
| 6.0.12  | 2        | 0.64%   |
| 6.0.10  | 2        | 0.64%   |
| 5.9.16  | 2        | 0.64%   |
| 5.8.18  | 2        | 0.64%   |
| 5.3.18  | 2        | 0.64%   |
| 5.18.12 | 2        | 0.64%   |
| 5.16.11 | 2        | 0.64%   |
| 5.13.4  | 2        | 0.64%   |
| 5.12.4  | 2        | 0.64%   |
| 5.11.12 | 2        | 0.64%   |
| 5.0.0   | 2        | 0.64%   |
| 4.9.9   | 2        | 0.64%   |
| 4.9.20  | 2        | 0.64%   |
| 4.9.124 | 2        | 0.64%   |
| 4.9.0   | 2        | 0.64%   |
| 6.1.23  | 1        | 0.32%   |
| 6.1.20  | 1        | 0.32%   |
| 6.1.12  | 1        | 0.32%   |
| 6.1.11  | 1        | 0.32%   |
| 6.0.2   | 1        | 0.32%   |
| 6.0.15  | 1        | 0.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 49       | 16.01%  |
| 5.15    | 32       | 10.46%  |
| 4.18    | 22       | 7.19%   |
| 5.10    | 21       | 6.86%   |
| 5.8     | 20       | 6.54%   |
| 4.15    | 20       | 6.54%   |
| 5.3     | 16       | 5.23%   |
| 5.16    | 15       | 4.9%    |
| 6.1     | 13       | 4.25%   |
| 5.13    | 13       | 4.25%   |
| 5.11    | 12       | 3.92%   |
| 4.9     | 12       | 3.92%   |
| 5.19    | 10       | 3.27%   |
| 4.19    | 8        | 2.61%   |
| 6.0     | 6        | 1.96%   |
| 5.7     | 6        | 1.96%   |
| 5.18    | 5        | 1.63%   |
| 5.12    | 5        | 1.63%   |
| 6.2     | 3        | 0.98%   |
| 5.9     | 3        | 0.98%   |
| 5.14    | 3        | 0.98%   |
| 5.5     | 2        | 0.65%   |
| 5.0     | 2        | 0.65%   |
| 4.1     | 2        | 0.65%   |
| 5.6     | 1        | 0.33%   |
| 5.2     | 1        | 0.33%   |
| 5.1     | 1        | 0.33%   |
| 4.7     | 1        | 0.33%   |
| 4.4     | 1        | 0.33%   |
| 4.11    | 1        | 0.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 246      | 93.89%  |
| i686   | 16       | 6.11%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 99       | 36.4%   |
| KDE5       | 71       | 26.1%   |
| XFCE       | 26       | 9.56%   |
| Unknown    | 25       | 9.19%   |
| X-Cinnamon | 19       | 6.99%   |
| MATE       | 10       | 3.68%   |
| KDE4       | 6        | 2.21%   |
| KDE        | 4        | 1.47%   |
| LXQt       | 3        | 1.1%    |
| Cinnamon   | 3        | 1.1%    |
| Unity      | 2        | 0.74%   |
| LXDE       | 2        | 0.74%   |
| Trinity    | 1        | 0.37%   |
| bspwm      | 1        | 0.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 223      | 81.68%  |
| Wayland | 29       | 10.62%  |
| Unknown | 15       | 5.49%   |
| Tty     | 6        | 2.2%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 117      | 42.55%  |
| SDDM    | 72       | 26.18%  |
| GDM3    | 27       | 9.82%   |
| LightDM | 21       | 7.64%   |
| GDM     | 20       | 7.27%   |
| TDM     | 9        | 3.27%   |
| KDM     | 6        | 2.18%   |
| SLiM    | 3        | 1.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| sk_SK   | 100      | 36.76%  |
| en_US   | 91       | 33.46%  |
| Unknown | 56       | 20.59%  |
| cs_CZ   | 11       | 4.04%   |
| en_GB   | 5        | 1.84%   |
| C       | 5        | 1.84%   |
| hu_HU   | 2        | 0.74%   |
| POSIX   | 1        | 0.37%   |
| en_AU   | 1        | 0.37%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 194      | 73.76%  |
| EFI  | 69       | 26.24%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 186      | 67.64%  |
| Overlay | 48       | 17.45%  |
| Btrfs   | 24       | 8.73%   |
| Unknown | 10       | 3.64%   |
| Xfs     | 3        | 1.09%   |
| Zfs     | 2        | 0.73%   |
| Tmpfs   | 1        | 0.36%   |
| Ext2    | 1        | 0.36%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 131      | 47.99%  |
| MBR     | 76       | 27.84%  |
| GPT     | 66       | 24.18%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 214      | 76.43%  |
| Yes       | 66       | 23.57%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 176      | 65.43%  |
| Yes       | 93       | 34.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 85       | 32.69%  |
| Gigabyte Technology | 46       | 17.69%  |
| MSI                 | 30       | 11.54%  |
| Hewlett-Packard     | 23       | 8.85%   |
| ASRock              | 22       | 8.46%   |
| Dell                | 13       | 5%      |
| Intel               | 10       | 3.85%   |
| Lenovo              | 9        | 3.46%   |
| Acer                | 5        | 1.92%   |
| Foxconn             | 4        | 1.54%   |
| Techvision          | 2        | 0.77%   |
| Shuttle             | 2        | 0.77%   |
| Pegatron            | 2        | 0.77%   |
| Unknown             | 2        | 0.77%   |
| VIA Technologies    | 1        | 0.38%   |
| Samsung Electronics | 1        | 0.38%   |
| Packard Bell        | 1        | 0.38%   |
| Insyde              | 1        | 0.38%   |
| Fujitsu Siemens     | 1        | 0.38%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Desktops | Percent |
|-----------------------------------------|----------|---------|
| ASUS All Series                         | 11       | 4.23%   |
| ASUS TUF Gaming B550M-PLUS              | 4        | 1.54%   |
| Gigabyte F2A68HM-DS2                    | 3        | 1.15%   |
| Techvision TVI7309X                     | 2        | 0.77%   |
| MSI MS-7C02                             | 2        | 0.77%   |
| MSI MS-7592                             | 2        | 0.77%   |
| Lenovo IdeaCentre Q180 10087&3110       | 2        | 0.77%   |
| HP Compaq Elite 8300 SFF                | 2        | 0.77%   |
| HP Compaq dc7800p Convertible Minitower | 2        | 0.77%   |
| HP Compaq 8000 Elite SFF PC             | 2        | 0.77%   |
| HP Compaq 6005 Pro SFF PC               | 2        | 0.77%   |
| Gigabyte P43-ES3G                       | 2        | 0.77%   |
| Gigabyte H81M-S2V                       | 2        | 0.77%   |
| Gigabyte H61M-S1                        | 2        | 0.77%   |
| Gigabyte GA-MA78GM-US2H                 | 2        | 0.77%   |
| Gigabyte AB350-Gaming 3                 | 2        | 0.77%   |
| Gigabyte 970A-DS3P                      | 2        | 0.77%   |
| Foxconn G41MX/G41MX-K 2.0 1.0           | 2        | 0.77%   |
| Dell Precision WorkStation 390          | 2        | 0.77%   |
| Dell OptiPlex 7010                      | 2        | 0.77%   |
| ASUS ROG STRIX X570-E GAMING            | 2        | 0.77%   |
| ASUS PRIME A320M-K                      | 2        | 0.77%   |
| ASUS P5QL-E                             | 2        | 0.77%   |
| ASUS M5A78L-M/USB3                      | 2        | 0.77%   |
| ASUS M4A88T-V EVO/USB3                  | 2        | 0.77%   |
| ASUS F2A55-M LK2 PLUS                   | 2        | 0.77%   |
| ASRock N68C-S UCC                       | 2        | 0.77%   |
| ASRock K8A780LM                         | 2        | 0.77%   |
| ASRock 960GC-GS FX                      | 2        | 0.77%   |
| Acer Aspire M5811                       | 2        | 0.77%   |
| Unknown                                 | 2        | 0.77%   |
| VIA KM266-8235                          | 1        | 0.38%   |
| Shuttle XH61V                           | 1        | 0.38%   |
| Shuttle TERRA_PC                        | 1        | 0.38%   |
| Samsung DeskTop System                  | 1        | 0.38%   |
| Pegatron Elite 7500 Series MT           | 1        | 0.38%   |
| Pegatron Compaq dx2400 Microtower PC    | 1        | 0.38%   |
| Packard Bell IPOWER X9093               | 1        | 0.38%   |
| MSI MS-7D54                             | 1        | 0.38%   |
| MSI MS-7D25                             | 1        | 0.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| HP Compaq               | 14       | 5.38%   |
| ASUS All                | 11       | 4.23%   |
| ASUS PRIME              | 10       | 3.85%   |
| Dell OptiPlex           | 9        | 3.46%   |
| ASUS ROG                | 7        | 2.69%   |
| ASUS TUF                | 6        | 2.31%   |
| Lenovo ThinkCentre      | 4        | 1.54%   |
| Acer Aspire             | 4        | 1.54%   |
| HP ProLiant             | 3        | 1.15%   |
| Gigabyte F2A68HM-DS2    | 3        | 1.15%   |
| Dell Precision          | 3        | 1.15%   |
| ASUS M5A97              | 3        | 1.15%   |
| ASUS M5A78L-M           | 3        | 1.15%   |
| Techvision TVI7309X     | 2        | 0.77%   |
| MSI MS-7C02             | 2        | 0.77%   |
| MSI MS-7592             | 2        | 0.77%   |
| Lenovo IdeaCentre       | 2        | 0.77%   |
| Gigabyte P43-ES3G       | 2        | 0.77%   |
| Gigabyte H81M-S2V       | 2        | 0.77%   |
| Gigabyte H61M-S1        | 2        | 0.77%   |
| Gigabyte GA-MA78GM-US2H | 2        | 0.77%   |
| Gigabyte AB350-Gaming   | 2        | 0.77%   |
| Gigabyte 970A-DS3P      | 2        | 0.77%   |
| Foxconn G41MX           | 2        | 0.77%   |
| ASUS P5QL-E             | 2        | 0.77%   |
| ASUS P5KPL-AM           | 2        | 0.77%   |
| ASUS P5GC-MX            | 2        | 0.77%   |
| ASUS Maximus            | 2        | 0.77%   |
| ASUS M4A88T-V           | 2        | 0.77%   |
| ASUS F2A55-M            | 2        | 0.77%   |
| ASRock N68C-S           | 2        | 0.77%   |
| ASRock K8A780LM         | 2        | 0.77%   |
| ASRock B550             | 2        | 0.77%   |
| ASRock 960GC-GS         | 2        | 0.77%   |
| Unknown                 | 2        | 0.77%   |
| VIA KM266-8235          | 1        | 0.38%   |
| Shuttle XH61V           | 1        | 0.38%   |
| Shuttle TERRA           | 1        | 0.38%   |
| Samsung DeskTop         | 1        | 0.38%   |
| Pegatron Elite          | 1        | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 32       | 12.31%  |
| 2009 | 29       | 11.15%  |
| 2013 | 24       | 9.23%   |
| 2008 | 21       | 8.08%   |
| 2014 | 18       | 6.92%   |
| 2020 | 16       | 6.15%   |
| 2019 | 16       | 6.15%   |
| 2018 | 15       | 5.77%   |
| 2007 | 14       | 5.38%   |
| 2006 | 13       | 5%      |
| 2011 | 12       | 4.62%   |
| 2010 | 11       | 4.23%   |
| 2016 | 9        | 3.46%   |
| 2015 | 9        | 3.46%   |
| 2017 | 6        | 2.31%   |
| 2022 | 5        | 1.92%   |
| 2021 | 4        | 1.54%   |
| 2005 | 2        | 0.77%   |
| 2023 | 1        | 0.38%   |
| 2002 | 1        | 0.38%   |
| 2001 | 1        | 0.38%   |
| 2000 | 1        | 0.38%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 260      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 254      | 97.69%  |
| Enabled  | 6        | 2.31%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 260      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 60       | 22.06%  |
| 8.01-16.0   | 57       | 20.96%  |
| 4.01-8.0    | 51       | 18.75%  |
| 16.01-24.0  | 44       | 16.18%  |
| 32.01-64.0  | 25       | 9.19%   |
| 1.01-2.0    | 11       | 4.04%   |
| 64.01-256.0 | 8        | 2.94%   |
| 2.01-3.0    | 7        | 2.57%   |
| 24.01-32.0  | 4        | 1.47%   |
| 0.51-1.0    | 4        | 1.47%   |
| 0.01-0.5    | 1        | 0.37%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 112      | 36.6%   |
| 2.01-3.0   | 65       | 21.24%  |
| 0.51-1.0   | 36       | 11.76%  |
| 3.01-4.0   | 31       | 10.13%  |
| 0.01-0.5   | 23       | 7.52%   |
| 4.01-8.0   | 22       | 7.19%   |
| 8.01-16.0  | 15       | 4.9%    |
| 24.01-32.0 | 1        | 0.33%   |
| 16.01-24.0 | 1        | 0.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 118      | 40.97%  |
| 2      | 91       | 31.6%   |
| 3      | 36       | 12.5%   |
| 4      | 18       | 6.25%   |
| 5      | 14       | 4.86%   |
| 0      | 6        | 2.08%   |
| 6      | 3        | 1.04%   |
| 17     | 1        | 0.35%   |
| 7      | 1        | 0.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 146      | 54.68%  |
| No        | 121      | 45.32%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 254      | 97.32%  |
| No        | 7        | 2.68%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 185      | 70.08%  |
| Yes       | 79       | 29.92%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 219      | 82.95%  |
| Yes       | 45       | 17.05%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| Slovakia | 260      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Bratislava             | 82       | 28.08%  |
| Košice                | 31       | 10.62%  |
| Nitra                  | 13       | 4.45%   |
| Banská Bystrica       | 8        | 2.74%   |
| Nové Zámky           | 7        | 2.4%    |
| Poprad                 | 6        | 2.05%   |
| Žilina                | 5        | 1.71%   |
| Zvolen                 | 4        | 1.37%   |
| Rimavská Sobota       | 4        | 1.37%   |
| Prešov                | 4        | 1.37%   |
| Liptovský Mikuláš   | 4        | 1.37%   |
| Trnava                 | 3        | 1.03%   |
| Trenčín              | 3        | 1.03%   |
| Tornaľa               | 3        | 1.03%   |
| Ružomberok            | 3        | 1.03%   |
| Nitrianske Hrnciarovce | 3        | 1.03%   |
| Levice                 | 3        | 1.03%   |
| Dolny Ohaj             | 3        | 1.03%   |
| Ziar nad Hronom        | 2        | 0.68%   |
| Soblahov               | 2        | 0.68%   |
| Smizany                | 2        | 0.68%   |
| Skalica                | 2        | 0.68%   |
| Senica                 | 2        | 0.68%   |
| Šaľa                 | 2        | 0.68%   |
| PetrЕѕalka           | 2        | 0.68%   |
| Modra                  | 2        | 0.68%   |
| Miloslavov             | 2        | 0.68%   |
| Martin                 | 2        | 0.68%   |
| Malacky                | 2        | 0.68%   |
| Lučenec               | 2        | 0.68%   |
| Kostolne Kracany       | 2        | 0.68%   |
| Kmetovce               | 2        | 0.68%   |
| Kalna                  | 2        | 0.68%   |
| Humenné               | 2        | 0.68%   |
| Galanta                | 2        | 0.68%   |
| Cechynce               | 2        | 0.68%   |
| Bardejov               | 2        | 0.68%   |
| Zlate Moravce          | 1        | 0.34%   |
| Zahradne               | 1        | 0.34%   |
| Vysoké Tatry          | 1        | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 112      | 221    | 24.51%  |
| Seagate                   | 92       | 147    | 20.13%  |
| Samsung Electronics       | 73       | 130    | 15.97%  |
| Hitachi                   | 23       | 34     | 5.03%   |
| A-DATA Technology         | 19       | 28     | 4.16%   |
| Kingston                  | 18       | 20     | 3.94%   |
| Toshiba                   | 15       | 23     | 3.28%   |
| Patriot                   | 14       | 23     | 3.06%   |
| Intel                     | 11       | 19     | 2.41%   |
| Maxtor                    | 7        | 12     | 1.53%   |
| Sandisk                   | 6        | 8      | 1.31%   |
| Crucial                   | 6        | 7      | 1.31%   |
| HGST                      | 5        | 8      | 1.09%   |
| KingDian                  | 4        | 4      | 0.88%   |
| Gigabyte Technology       | 4        | 6      | 0.88%   |
| Unknown                   | 3        | 4      | 0.66%   |
| Phison                    | 3        | 3      | 0.66%   |
| OCZ                       | 3        | 3      | 0.66%   |
| Apacer                    | 3        | 3      | 0.66%   |
| XPG                       | 2        | 5      | 0.44%   |
| SK hynix                  | 2        | 2      | 0.44%   |
| Silicon Motion            | 2        | 3      | 0.44%   |
| Realtek Semiconductor     | 2        | 2      | 0.44%   |
| Micron Technology         | 2        | 3      | 0.44%   |
| IBM/Hitachi               | 2        | 2      | 0.44%   |
| GOODRAM                   | 2        | 4      | 0.44%   |
| Corsair                   | 2        | 3      | 0.44%   |
| China                     | 2        | 4      | 0.44%   |
| Verbatim                  | 1        | 1      | 0.22%   |
| USB3.0                    | 1        | 2      | 0.22%   |
| ULTIMATE                  | 1        | 2      | 0.22%   |
| Realtek                   | 1        | 1      | 0.22%   |
| PNY                       | 1        | 2      | 0.22%   |
| Phison Electronics        | 1        | 1      | 0.22%   |
| Micron/Crucial Technology | 1        | 1      | 0.22%   |
| LITEONIT                  | 1        | 1      | 0.22%   |
| Intenso                   | 1        | 3      | 0.22%   |
| HS-SSD-E100               | 1        | 1      | 0.22%   |
| HS-SSD-C100               | 1        | 3      | 0.22%   |
| HGST HTS                  | 1        | 1      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| WDC WD10EZEX-08WN4A0 1TB         | 6        | 1.11%   |
| Seagate ST2000DM008-2FR102 2TB   | 6        | 1.11%   |
| Samsung SSD 860 EVO 250GB        | 6        | 1.11%   |
| Samsung SSD 850 EVO 250GB        | 6        | 1.11%   |
| Patriot Burst 120GB SSD          | 6        | 1.11%   |
| Seagate ST3500418AS 500GB        | 5        | 0.92%   |
| Kingston SV300S37A120G 120GB SSD | 5        | 0.92%   |
| Toshiba DT01ACA100 1TB           | 4        | 0.74%   |
| Seagate ST500DM002-1BD142 500GB  | 4        | 0.74%   |
| Seagate ST3320311CS 320GB        | 4        | 0.74%   |
| Seagate ST2000DM001-1CH164 2TB   | 4        | 0.74%   |
| Seagate ST1000DM003-1CH162 1TB   | 4        | 0.74%   |
| Samsung SSD 860 EVO 500GB        | 4        | 0.74%   |
| Samsung SSD 850 EVO 500GB        | 4        | 0.74%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 3        | 0.55%   |
| WDC WD5000AAKX-75U6AA0 500GB     | 3        | 0.55%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 3        | 0.55%   |
| WDC WD10EZEX-00KUWA0 1TB         | 3        | 0.55%   |
| Seagate ST380815AS 80GB          | 3        | 0.55%   |
| Seagate ST3808110AS 80GB         | 3        | 0.55%   |
| Seagate ST1000DM003-1SB102 1TB   | 3        | 0.55%   |
| Samsung SSD 980 PRO 1TB          | 3        | 0.55%   |
| Samsung SSD 970 PRO 512GB        | 3        | 0.55%   |
| Samsung SSD 870 EVO 500GB        | 3        | 0.55%   |
| Samsung SSD 860 EVO 1TB          | 3        | 0.55%   |
| Patriot Burst 240GB SSD          | 3        | 0.55%   |
| Kingston SV300S37A60G 64GB SSD   | 3        | 0.55%   |
| Hitachi HTS543232A7A384 320GB    | 3        | 0.55%   |
| Hitachi HDS722020ALA330 2TB      | 3        | 0.55%   |
| Hitachi HDP725050GLA360 500GB    | 3        | 0.55%   |
| A-DATA SU700 120GB SSD           | 3        | 0.55%   |
| A-DATA SU650 120GB SSD           | 3        | 0.55%   |
| A-DATA SP600 32GB SSD            | 3        | 0.55%   |
| XPG GAMMIX S11 Pro 1TB           | 2        | 0.37%   |
| WDC WD6400AAKS-22A7B0 640GB      | 2        | 0.37%   |
| WDC WD5000AZRX-00L4HB0 500GB     | 2        | 0.37%   |
| WDC WD5000AAKX-22ERMA0 500GB     | 2        | 0.37%   |
| WDC WD5000AADS-00S9B0 500GB      | 2        | 0.37%   |
| WDC WD40EZRZ-00GXCB0 4TB         | 2        | 0.37%   |
| WDC WD400JB-00JJC0 40GB          | 2        | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 110      | 212    | 39.86%  |
| Seagate             | 90       | 144    | 32.61%  |
| Hitachi             | 23       | 34     | 8.33%   |
| Samsung Electronics | 20       | 32     | 7.25%   |
| Toshiba             | 13       | 19     | 4.71%   |
| Maxtor              | 7        | 12     | 2.54%   |
| HGST                | 5        | 8      | 1.81%   |
| IBM/Hitachi         | 2        | 2      | 0.72%   |
| USB3.0              | 1        | 2      | 0.36%   |
| Unknown             | 1        | 1      | 0.36%   |
| HGST HTS            | 1        | 1      | 0.36%   |
| Hewlett-Packard     | 1        | 3      | 0.36%   |
| Fujitsu             | 1        | 2      | 0.36%   |
| ExcelStor           | 1        | 1      | 0.36%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 38       | 54     | 28.57%  |
| A-DATA Technology   | 17       | 26     | 12.78%  |
| Kingston            | 14       | 16     | 10.53%  |
| Patriot             | 13       | 22     | 9.77%   |
| Intel               | 9        | 17     | 6.77%   |
| Crucial             | 6        | 7      | 4.51%   |
| WDC                 | 5        | 6      | 3.76%   |
| SanDisk             | 3        | 4      | 2.26%   |
| OCZ                 | 3        | 3      | 2.26%   |
| Gigabyte Technology | 3        | 5      | 2.26%   |
| SK hynix            | 2        | 2      | 1.5%    |
| Micron Technology   | 2        | 3      | 1.5%    |
| KingDian            | 2        | 2      | 1.5%    |
| GOODRAM             | 2        | 4      | 1.5%    |
| China               | 2        | 4      | 1.5%    |
| Apacer              | 2        | 2      | 1.5%    |
| Verbatim            | 1        | 1      | 0.75%   |
| ULTIMATE            | 1        | 2      | 0.75%   |
| Toshiba             | 1        | 1      | 0.75%   |
| PNY                 | 1        | 2      | 0.75%   |
| LITEONIT            | 1        | 1      | 0.75%   |
| Intenso             | 1        | 3      | 0.75%   |
| HS-SSD-C100         | 1        | 3      | 0.75%   |
| FORESEE             | 1        | 2      | 0.75%   |
| Corsair             | 1        | 1      | 0.75%   |
| AMD                 | 1        | 1      | 0.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 201      | 473    | 54.32%  |
| SSD     | 117      | 194    | 31.62%  |
| NVMe    | 46       | 86     | 12.43%  |
| Unknown | 6        | 7      | 1.62%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 239      | 661    | 81.29%  |
| NVMe | 46       | 85     | 15.65%  |
| SAS  | 9        | 14     | 3.06%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 207      | 420    | 59.65%  |
| 0.51-1.0   | 79       | 143    | 22.77%  |
| 1.01-2.0   | 35       | 55     | 10.09%  |
| 3.01-4.0   | 13       | 23     | 3.75%   |
| 2.01-3.0   | 9        | 17     | 2.59%   |
| 4.01-10.0  | 3        | 8      | 0.86%   |
| 10.01-20.0 | 1        | 1      | 0.29%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 67       | 22.26%  |
| 251-500        | 56       | 18.6%   |
| 1-20           | 43       | 14.29%  |
| 501-1000       | 39       | 12.96%  |
| Unknown        | 24       | 7.97%   |
| 1001-2000      | 22       | 7.31%   |
| 51-100         | 18       | 5.98%   |
| 21-50          | 13       | 4.32%   |
| More than 3000 | 11       | 3.65%   |
| 2001-3000      | 8        | 2.66%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 121      | 40.07%  |
| 21-50          | 46       | 15.23%  |
| 101-250        | 31       | 10.26%  |
| 51-100         | 24       | 7.95%   |
| Unknown        | 24       | 7.95%   |
| 501-1000       | 22       | 7.28%   |
| 251-500        | 20       | 6.62%   |
| 1001-2000      | 8        | 2.65%   |
| More than 3000 | 4        | 1.32%   |
| 2001-3000      | 2        | 0.66%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD10EZEX-75WN4A0 1TB              | 2        | 3      | 3.77%   |
| Seagate ST9500325AS 500GB             | 2        | 3      | 3.77%   |
| Seagate ST3320413CS 320GB             | 2        | 2      | 3.77%   |
| Kingston SV300S37A60G 64GB SSD        | 2        | 3      | 3.77%   |
| WDC WD800JD-60LSA0 80GB               | 1        | 1      | 1.89%   |
| WDC WD7500BPVT-24HXZT3 752GB          | 1        | 1      | 1.89%   |
| WDC WD7500AAVS-00D7B1 752GB           | 1        | 1      | 1.89%   |
| WDC WD3200AAKS-22L6A0 320GB           | 1        | 1      | 1.89%   |
| WDC WD3200AAJS-56B4A0 320GB           | 1        | 2      | 1.89%   |
| WDC WD2500AAKX-753CA1 250GB           | 1        | 2      | 1.89%   |
| WDC WD20EZRZ-00Z5HB0 2TB              | 1        | 1      | 1.89%   |
| WDC WD20EURS-63S48Y0 2TB              | 1        | 1      | 1.89%   |
| WDC WD1600JS-61MHB1 160GB             | 1        | 1      | 1.89%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1        | 1      | 1.89%   |
| WDC WD10EZEX-00RKKA0 1TB              | 1        | 1      | 1.89%   |
| WDC WD10EZEX-00KUWA0 1TB              | 1        | 1      | 1.89%   |
| WDC WD10EALX-009BA0 1TB               | 1        | 1      | 1.89%   |
| Toshiba MK7575GSX 752GB               | 1        | 2      | 1.89%   |
| SK hynix SC210 2.5 7MM 256GB SSD      | 1        | 1      | 1.89%   |
| Seagate ST980811AS 80GB               | 1        | 1      | 1.89%   |
| Seagate ST9250315AS 250GB             | 1        | 1      | 1.89%   |
| Seagate ST500DM002-1BD142 500GB       | 1        | 1      | 1.89%   |
| Seagate ST3500412AS 500GB             | 1        | 1      | 1.89%   |
| Seagate ST3500312CS 500GB             | 1        | 1      | 1.89%   |
| Seagate ST3402111A 40GB               | 1        | 1      | 1.89%   |
| Seagate ST320LT007-9ZV142 320GB       | 1        | 1      | 1.89%   |
| Seagate ST31000322CS 1TB              | 1        | 2      | 1.89%   |
| Seagate ST250DM000-1BD141 250GB       | 1        | 1      | 1.89%   |
| Seagate ST2000VX000-1CU164 2TB        | 1        | 1      | 1.89%   |
| Seagate ST1000LM035-1RK172 970GB      | 1        | 1      | 1.89%   |
| Samsung Electronics SSD 970 EVO 500GB | 1        | 1      | 1.89%   |
| Samsung Electronics HD753LJ 752GB     | 1        | 4      | 1.89%   |
| Samsung Electronics HD320KJ 320GB     | 1        | 1      | 1.89%   |
| Samsung Electronics HD154UI 1TB       | 1        | 1      | 1.89%   |
| OCZ VERTEX4 256GB SSD                 | 1        | 1      | 1.89%   |
| OCZ AGILITY3 240GB SSD                | 1        | 1      | 1.89%   |
| Maxtor 6L200M0 208GB                  | 1        | 1      | 1.89%   |
| Maxtor 6L080P0 81GB                   | 1        | 1      | 1.89%   |
| Maxtor 6E040L0 41GB                   | 1        | 1      | 1.89%   |
| Kingston SHPM2280P2H 240G SSD         | 1        | 1      | 1.89%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 15       | 17     | 28.85%  |
| WDC                 | 14       | 18     | 26.92%  |
| Samsung Electronics | 4        | 7      | 7.69%   |
| Maxtor              | 3        | 3      | 5.77%   |
| Kingston            | 3        | 4      | 5.77%   |
| Hitachi             | 3        | 3      | 5.77%   |
| OCZ                 | 2        | 2      | 3.85%   |
| Toshiba             | 1        | 2      | 1.92%   |
| SK hynix            | 1        | 1      | 1.92%   |
| IBM/Hitachi         | 1        | 1      | 1.92%   |
| HGST                | 1        | 3      | 1.92%   |
| Fujitsu             | 1        | 2      | 1.92%   |
| ExcelStor           | 1        | 1      | 1.92%   |
| Crucial             | 1        | 1      | 1.92%   |
| A-DATA Technology   | 1        | 1      | 1.92%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 15       | 17     | 34.88%  |
| WDC                 | 14       | 18     | 32.56%  |
| Samsung Electronics | 3        | 6      | 6.98%   |
| Maxtor              | 3        | 3      | 6.98%   |
| Hitachi             | 3        | 3      | 6.98%   |
| Toshiba             | 1        | 2      | 2.33%   |
| IBM/Hitachi         | 1        | 1      | 2.33%   |
| HGST                | 1        | 3      | 2.33%   |
| Fujitsu             | 1        | 2      | 2.33%   |
| ExcelStor           | 1        | 1      | 2.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 40       | 56     | 81.63%  |
| SSD  | 8        | 9      | 16.33%  |
| NVMe | 1        | 1      | 2.04%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Toshiba MK5065GSX 500GB           | 2        | 2      | 40%     |
| Seagate ST3500418AS 500GB         | 1        | 2      | 20%     |
| Seagate ST2000DM001-1CH164 2TB    | 1        | 1      | 20%     |
| Samsung Electronics HD321HJ 320GB | 1        | 2      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Toshiba             | 2        | 2      | 40%     |
| Seagate             | 2        | 3      | 40%     |
| Samsung Electronics | 1        | 2      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 136      | 358    | 44.59%  |
| Works    | 118      | 329    | 38.69%  |
| Malfunc  | 46       | 66     | 15.08%  |
| Failed   | 5        | 7      | 1.64%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 161      | 46%     |
| AMD                          | 79       | 22.57%  |
| Samsung Electronics          | 23       | 6.57%   |
| JMicron Technology           | 17       | 4.86%   |
| Nvidia                       | 14       | 4%      |
| ASMedia Technology           | 11       | 3.14%   |
| Phison Electronics           | 7        | 2%      |
| SanDisk                      | 6        | 1.71%   |
| Marvell Technology Group     | 6        | 1.71%   |
| VIA Technologies             | 5        | 1.43%   |
| Kingston Technology Company  | 5        | 1.43%   |
| ADATA Technology             | 4        | 1.14%   |
| Silicon Motion               | 2        | 0.57%   |
| Realtek Semiconductor        | 2        | 0.57%   |
| Promise Technology           | 2        | 0.57%   |
| Hewlett-Packard              | 2        | 0.57%   |
| ULi Electronics              | 1        | 0.29%   |
| Toshiba America Info Systems | 1        | 0.29%   |
| Micron/Crucial Technology    | 1        | 0.29%   |
| LSI Logic / Symbios Logic    | 1        | 0.29%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 37       | 7.81%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 26       | 5.49%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 23       | 4.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 18       | 3.8%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 18       | 3.8%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 15       | 3.16%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 14       | 2.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 13       | 2.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 12       | 2.53%   |
| AMD 400 Series Chipset SATA Controller                                         | 12       | 2.53%   |
| JMicron JMB363 SATA/IDE Controller                                             | 11       | 2.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 10       | 2.11%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 10       | 2.11%   |
| AMD 500 Series Chipset SATA Controller                                         | 10       | 2.11%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 9        | 1.9%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 9        | 1.9%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 8        | 1.69%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 8        | 1.69%   |
| Nvidia MCP61 SATA Controller                                                   | 7        | 1.48%   |
| Nvidia MCP61 IDE                                                               | 7        | 1.48%   |
| Intel SATA Controller [RAID mode]                                              | 7        | 1.48%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]            | 7        | 1.48%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 7        | 1.48%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 6        | 1.27%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 5        | 1.05%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 5        | 1.05%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 5        | 1.05%   |
| AMD FCH SATA Controller D                                                      | 5        | 1.05%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 4        | 0.84%   |
| Phison E12 NVMe Controller                                                     | 4        | 0.84%   |
| JMicron JMB368 IDE controller                                                  | 4        | 0.84%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 4        | 0.84%   |
| Intel 82Q35 Express PT IDER Controller                                         | 4        | 0.84%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 4        | 0.84%   |
| AMD FCH IDE Controller                                                         | 4        | 0.84%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 4        | 0.84%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 3        | 0.63%   |
| Phison E16 PCIe4 NVMe Controller                                               | 3        | 0.63%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 3        | 0.63%   |
| Kingston Company A2000 NVMe SSD                                                | 3        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 176      | 50.87%  |
| IDE  | 109      | 31.5%   |
| NVMe | 46       | 13.29%  |
| RAID | 14       | 4.05%   |
| SCSI | 1        | 0.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 163      | 62.69%  |
| AMD          | 96       | 36.92%  |
| CentaurHauls | 1        | 0.38%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz  | 7        | 2.66%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz  | 6        | 2.28%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 4        | 1.52%   |
| Intel Core i5-2500K CPU @ 3.30GHz      | 4        | 1.52%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz   | 4        | 1.52%   |
| AMD Ryzen 9 3900X 12-Core Processor    | 4        | 1.52%   |
| Intel Core i7-7700K CPU @ 4.20GHz      | 3        | 1.14%   |
| Intel Core i5-4590 CPU @ 3.30GHz       | 3        | 1.14%   |
| Intel Core i3-9100 CPU @ 3.60GHz       | 3        | 1.14%   |
| Intel Core i3-8100 CPU @ 3.60GHz       | 3        | 1.14%   |
| Intel Core i3-4170 CPU @ 3.70GHz       | 3        | 1.14%   |
| Intel Core i3-10100 CPU @ 3.60GHz      | 3        | 1.14%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz   | 3        | 1.14%   |
| Intel Core 2 Duo CPU E6750 @ 2.66GHz   | 3        | 1.14%   |
| AMD Ryzen 7 3700X 8-Core Processor     | 3        | 1.14%   |
| AMD Ryzen 5 5600X 6-Core Processor     | 3        | 1.14%   |
| Intel Xeon CPU X5450 @ 3.00GHz         | 2        | 0.76%   |
| Intel Pentium 4 CPU 3.00GHz            | 2        | 0.76%   |
| Intel Core i7-9700K CPU @ 3.60GHz      | 2        | 0.76%   |
| Intel Core i7-6700K CPU @ 4.00GHz      | 2        | 0.76%   |
| Intel Core i7-4790 CPU @ 3.60GHz       | 2        | 0.76%   |
| Intel Core i7 CPU 920 @ 2.67GHz        | 2        | 0.76%   |
| Intel Core i5-6600 CPU @ 3.30GHz       | 2        | 0.76%   |
| Intel Core i5-6400 CPU @ 2.70GHz       | 2        | 0.76%   |
| Intel Core i5-4670K CPU @ 3.40GHz      | 2        | 0.76%   |
| Intel Core i5-3570 CPU @ 3.40GHz       | 2        | 0.76%   |
| Intel Core i5-3470 CPU @ 3.20GHz       | 2        | 0.76%   |
| Intel Core i5 CPU 750 @ 2.67GHz        | 2        | 0.76%   |
| Intel Core i3-3225 CPU @ 3.30GHz       | 2        | 0.76%   |
| Intel Core i3-3220 CPU @ 3.30GHz       | 2        | 0.76%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz   | 2        | 0.76%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz   | 2        | 0.76%   |
| Intel Celeron N5105 @ 2.00GHz          | 2        | 0.76%   |
| Intel Celeron CPU G1610 @ 2.60GHz      | 2        | 0.76%   |
| AMD Ryzen 9 5950X 16-Core Processor    | 2        | 0.76%   |
| AMD Ryzen 9 5900X 12-Core Processor    | 2        | 0.76%   |
| AMD Ryzen 7 2700 Eight-Core Processor  | 2        | 0.76%   |
| AMD Ryzen 5 5600G with Radeon Graphics | 2        | 0.76%   |
| AMD Ryzen 5 3600 6-Core Processor      | 2        | 0.76%   |
| AMD Ryzen 5 1600 Six-Core Processor    | 2        | 0.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 38       | 14.45%  |
| Intel Core i3           | 22       | 8.37%   |
| Intel Core i7           | 20       | 7.6%    |
| Intel Core 2 Duo        | 19       | 7.22%   |
| Intel Core 2 Quad       | 16       | 6.08%   |
| AMD Ryzen 5             | 14       | 5.32%   |
| Intel Celeron           | 12       | 4.56%   |
| Intel Xeon              | 11       | 4.18%   |
| AMD Ryzen 9             | 9        | 3.42%   |
| AMD Ryzen 7             | 9        | 3.42%   |
| Intel Pentium           | 7        | 2.66%   |
| AMD Athlon 64 X2        | 7        | 2.66%   |
| AMD FX                  | 6        | 2.28%   |
| AMD Athlon II X2        | 6        | 2.28%   |
| AMD Sempron             | 4        | 1.52%   |
| AMD Ryzen 3             | 4        | 1.52%   |
| AMD Phenom II X4        | 4        | 1.52%   |
| AMD Phenom              | 4        | 1.52%   |
| AMD Athlon 64           | 4        | 1.52%   |
| Other                   | 3        | 1.14%   |
| Intel Pentium Dual-Core | 3        | 1.14%   |
| Intel Pentium 4         | 3        | 1.14%   |
| Intel Core 2            | 3        | 1.14%   |
| Intel Atom              | 3        | 1.14%   |
| AMD Athlon X4           | 3        | 1.14%   |
| AMD A8                  | 3        | 1.14%   |
| AMD A10                 | 3        | 1.14%   |
| Intel Pentium Dual      | 2        | 0.76%   |
| AMD Ryzen 5 PRO         | 2        | 0.76%   |
| AMD Phenom II X6        | 2        | 0.76%   |
| AMD Phenom II X2        | 2        | 0.76%   |
| AMD Athlon Dual Core    | 2        | 0.76%   |
| AMD Athlon              | 2        | 0.76%   |
| AMD A6                  | 2        | 0.76%   |
| AMD A4                  | 2        | 0.76%   |
| Intel Pentium D         | 1        | 0.38%   |
| Intel Genuine           | 1        | 0.38%   |
| Intel Core i9           | 1        | 0.38%   |
| CentaurHauls VIA Esther | 1        | 0.38%   |
| AMD Athlon XP           | 1        | 0.38%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 109      | 41.29%  |
| 2       | 89       | 33.71%  |
| 6       | 20       | 7.58%   |
| 1       | 16       | 6.06%   |
| 8       | 13       | 4.92%   |
| 12      | 6        | 2.27%   |
| 16      | 3        | 1.14%   |
| 3       | 3        | 1.14%   |
| Unknown | 2        | 0.76%   |
| 24      | 1        | 0.38%   |
| 20      | 1        | 0.38%   |
| 10      | 1        | 0.38%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 259      | 99.62%  |
| 2      | 1        | 0.38%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 156      | 59.77%  |
| 2       | 103      | 39.46%  |
| Unknown | 2        | 0.77%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 256      | 98.46%  |
| 32-bit         | 3        | 1.15%   |
| 64-bit         | 1        | 0.38%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 61       | 22.43%  |
| 0x1067a    | 21       | 7.72%   |
| 0x306c3    | 20       | 7.35%   |
| 0x306a9    | 19       | 6.99%   |
| 0x6fb      | 15       | 5.51%   |
| 0x906e9    | 7        | 2.57%   |
| 0x506e3    | 7        | 2.57%   |
| 0x206a7    | 7        | 2.57%   |
| 0x06001119 | 6        | 2.21%   |
| 0x010000c8 | 6        | 2.21%   |
| 0x6fd      | 5        | 1.84%   |
| 0x08701021 | 5        | 1.84%   |
| 0x906eb    | 4        | 1.47%   |
| 0x6f2      | 4        | 1.47%   |
| 0x0800820d | 4        | 1.47%   |
| 0xa0653    | 3        | 1.1%    |
| 0x906ea    | 3        | 1.1%    |
| 0x106a5    | 3        | 1.1%    |
| 0x0a201016 | 3        | 1.1%    |
| 0x08108109 | 3        | 1.1%    |
| 0x010000c7 | 3        | 1.1%    |
| 0x01000083 | 3        | 1.1%    |
| 0xf43      | 2        | 0.74%   |
| 0x906c0    | 2        | 0.74%   |
| 0x406c3    | 2        | 0.74%   |
| 0x30661    | 2        | 0.74%   |
| 0x20652    | 2        | 0.74%   |
| 0x0a201009 | 2        | 0.74%   |
| 0x08701013 | 2        | 0.74%   |
| 0x08001138 | 2        | 0.74%   |
| 0x0700010f | 2        | 0.74%   |
| 0x06003106 | 2        | 0.74%   |
| 0x06000852 | 2        | 0.74%   |
| 0x01000095 | 2        | 0.74%   |
| 0x01000086 | 2        | 0.74%   |
| 0xf64      | 1        | 0.37%   |
| 0xf4a      | 1        | 0.37%   |
| 0xb0671    | 1        | 0.37%   |
| 0x906ed    | 1        | 0.37%   |
| 0x906ec    | 1        | 0.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 26       | 9.96%   |
| Penryn           | 25       | 9.58%   |
| Core             | 25       | 9.58%   |
| K10              | 22       | 8.43%   |
| IvyBridge        | 22       | 8.43%   |
| KabyLake         | 20       | 7.66%   |
| K8 Hammer        | 15       | 5.75%   |
| Zen 2            | 13       | 4.98%   |
| Zen 3            | 11       | 4.21%   |
| Piledriver       | 11       | 4.21%   |
| SandyBridge      | 10       | 3.83%   |
| Zen+             | 9        | 3.45%   |
| Skylake          | 8        | 3.07%   |
| Zen              | 5        | 1.92%   |
| Steamroller      | 5        | 1.92%   |
| Nehalem          | 5        | 1.92%   |
| NetBurst         | 4        | 1.53%   |
| Westmere         | 3        | 1.15%   |
| CometLake        | 3        | 1.15%   |
| Bonnell          | 3        | 1.15%   |
| Unknown          | 3        | 1.15%   |
| Tremont          | 2        | 0.77%   |
| Silvermont       | 2        | 0.77%   |
| Jaguar           | 2        | 0.77%   |
| P6               | 1        | 0.38%   |
| K6               | 1        | 0.38%   |
| K10 Llano        | 1        | 0.38%   |
| Excavator        | 1        | 0.38%   |
| Bulldozer        | 1        | 0.38%   |
| Broadwell        | 1        | 0.38%   |
| Alderlake Hybrid | 1        | 0.38%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 105      | 37.1%   |
| AMD                        | 99       | 34.98%  |
| Intel                      | 75       | 26.5%   |
| Matrox Electronics Systems | 2        | 0.71%   |
| VIA Technologies           | 1        | 0.35%   |
| S3 Graphics                | 1        | 0.35%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 12       | 3.99%   |
| Nvidia GK208B [GeForce GT 710]                                              | 11       | 3.65%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 8        | 2.66%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7        | 2.33%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 7        | 2.33%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 7        | 2.33%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 6        | 1.99%   |
| Intel HD Graphics 530                                                       | 6        | 1.99%   |
| AMD RS780L [Radeon 3000]                                                    | 6        | 1.99%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 6        | 1.99%   |
| Nvidia GT218 [GeForce 210]                                                  | 5        | 1.66%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 1.33%   |
| Nvidia GF108 [GeForce GT 630]                                               | 4        | 1.33%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 4        | 1.33%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 4        | 1.33%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 4        | 1.33%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 4        | 1.33%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 3        | 1%      |
| Nvidia GT216 [GeForce GT 220]                                               | 3        | 1%      |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 3        | 1%      |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 1%      |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 1%      |
| Nvidia G96C [GeForce 9500 GT]                                               | 3        | 1%      |
| Intel HD Graphics 630                                                       | 3        | 1%      |
| Intel 82Q35 Express Integrated Graphics Controller                          | 3        | 1%      |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 3        | 1%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 1%      |
| AMD Kaveri [Radeon R7 Graphics]                                             | 3        | 1%      |
| AMD Juniper XT [Radeon HD 5770]                                             | 3        | 1%      |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3        | 1%      |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                          | 2        | 0.66%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 0.66%   |
| Nvidia GK208 [GeForce GT 630 Rev. 2]                                        | 2        | 0.66%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 0.66%   |
| Nvidia GF104 [GeForce GTX 460]                                              | 2        | 0.66%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 2        | 0.66%   |
| Nvidia G92 [GeForce 9800 GT]                                                | 2        | 0.66%   |
| Matrox Electronics Systems MGA G200EH                                       | 2        | 0.66%   |
| Intel JasperLake [UHD Graphics]                                             | 2        | 0.66%   |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 93       | 34.57%  |
| 1 x AMD         | 84       | 31.23%  |
| 1 x Intel       | 65       | 24.16%  |
| 2 x AMD         | 10       | 3.72%   |
| AMD + Nvidia    | 5        | 1.86%   |
| Intel + Nvidia  | 4        | 1.49%   |
| 2 x Nvidia      | 2        | 0.74%   |
| 1 x Matrox      | 2        | 0.74%   |
| 3 x AMD         | 1        | 0.37%   |
| 1 x VIA         | 1        | 0.37%   |
| 1 x S3 Graphics | 1        | 0.37%   |
| Intel + AMD     | 1        | 0.37%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 210      | 77.21%  |
| Proprietary | 47       | 17.28%  |
| Unknown     | 15       | 5.51%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 103      | 36.79%  |
| 0.01-0.5   | 51       | 18.21%  |
| 0.51-1.0   | 46       | 16.43%  |
| 1.01-2.0   | 32       | 11.43%  |
| 3.01-4.0   | 19       | 6.79%   |
| 7.01-8.0   | 12       | 4.29%   |
| 5.01-6.0   | 9        | 3.21%   |
| 2.01-3.0   | 3        | 1.07%   |
| 8.01-16.0  | 3        | 1.07%   |
| 16.01-24.0 | 2        | 0.71%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 39       | 14.61%  |
| BenQ                 | 27       | 10.11%  |
| Goldstar             | 26       | 9.74%   |
| Dell                 | 26       | 9.74%   |
| Philips              | 24       | 8.99%   |
| Hewlett-Packard      | 21       | 7.87%   |
| Ancor Communications | 16       | 5.99%   |
| AOC                  | 11       | 4.12%   |
| NEC Computers        | 10       | 3.75%   |
| Acer                 | 10       | 3.75%   |
| Iiyama               | 6        | 2.25%   |
| Fujitsu Siemens      | 6        | 2.25%   |
| LG Electronics       | 5        | 1.87%   |
| Unknown              | 4        | 1.5%    |
| Eizo                 | 4        | 1.5%    |
| Lenovo               | 3        | 1.12%   |
| Sony                 | 2        | 0.75%   |
| RTD                  | 2        | 0.75%   |
| MiTAC                | 2        | 0.75%   |
| FUS                  | 2        | 0.75%   |
| CVT                  | 2        | 0.75%   |
| Vestel Elektronik    | 1        | 0.37%   |
| Valve                | 1        | 0.37%   |
| S2-Tek               | 1        | 0.37%   |
| PTC                  | 1        | 0.37%   |
| Pioneer              | 1        | 0.37%   |
| Onkyo                | 1        | 0.37%   |
| MSI                  | 1        | 0.37%   |
| Lite-On              | 1        | 0.37%   |
| Jean                 | 1        | 0.37%   |
| InfoVision           | 1        | 0.37%   |
| Idek Iiyama          | 1        | 0.37%   |
| IBM                  | 1        | 0.37%   |
| FZC                  | 1        | 0.37%   |
| Elo Touch            | 1        | 0.37%   |
| DENON                | 1        | 0.37%   |
| D&T                  | 1        | 0.37%   |
| ASUSTek Computer     | 1        | 0.37%   |
| Arnos Instruments    | 1        | 0.37%   |
| ADV                  | 1        | 0.37%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch   | 6        | 2.08%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 6        | 2.08%   |
| NEC Computers LCD19WV NEC671C 1440x900 410x256mm 19.0-inch             | 4        | 1.39%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch      | 3        | 1.04%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 3        | 1.04%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 3        | 1.04%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch       | 3        | 1.04%   |
| Unknown 1780 07E7 1280x1024 337x270mm 17.0-inch                        | 2        | 0.69%   |
| Samsung Electronics SyncMaster SAM05CC 1920x1080 530x300mm 24.0-inch   | 2        | 0.69%   |
| Samsung Electronics SyncMaster SAM0420 1680x1050 474x296mm 22.0-inch   | 2        | 0.69%   |
| Samsung Electronics S27D390 SAM0B67 1920x1080 598x336mm 27.0-inch      | 2        | 0.69%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 2        | 0.69%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch | 2        | 0.69%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 890x500mm 40.2-inch  | 2        | 0.69%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 2        | 0.69%   |
| RTD LR762 RTD2023 1280x1024 307x230mm 15.1-inch                        | 2        | 0.69%   |
| Philips 241BLPY PHL08B3 1920x1080 531x299mm 24.0-inch                  | 2        | 0.69%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                     | 2        | 0.69%   |
| MiTAC CHHWJT SZM0308 1920x540 708x398mm 32.0-inch                      | 2        | 0.69%   |
| Lenovo T24v-10 LEN61BC 1920x1080 527x296mm 23.8-inch                   | 2        | 0.69%   |
| Hewlett-Packard LA1951 HWP285A 1280x1024 380x300mm 19.1-inch           | 2        | 0.69%   |
| Dell U2515H DELD06F 2560x1440 553x311mm 25.0-inch                      | 2        | 0.69%   |
| Dell 2209WA DELF011 1680x1050 474x296mm 22.0-inch                      | 2        | 0.69%   |
| CVT CVTE TV CVT0003 1360x768 575x323mm 26.0-inch                       | 2        | 0.69%   |
| BenQ GW2470 BNQ78E4 1920x1080 527x296mm 23.8-inch                      | 2        | 0.69%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                      | 2        | 0.69%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                       | 2        | 0.69%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                        | 2        | 0.69%   |
| Ancor Communications VE228 ACI22FA 1920x1080 477x268mm 21.5-inch       | 2        | 0.69%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch  | 2        | 0.69%   |
| Ancor Communications ASUS MK241 ACI24A1 1920x1200 518x324mm 24.1-inch  | 2        | 0.69%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 1        | 0.35%   |
| Valve LCD Monitor VLV91A8                                              | 1        | 0.35%   |
| Unknown LCD Monitor XXX Beyond TV 3840x2160                            | 1        | 0.35%   |
| Unknown LCD Monitor BenQG2222HDL 1920x1080                             | 1        | 0.35%   |
| Sony TV *00 SNY8404 3840x2160 1218x685mm 55.0-inch                     | 1        | 0.35%   |
| Sony TV *00 SNY4904 3840x2160                                          | 1        | 0.35%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch    | 1        | 0.35%   |
| Samsung Electronics SyncMaster SAM0589 1920x1080 521x293mm 23.5-inch   | 1        | 0.35%   |
| Samsung Electronics SyncMaster SAM049C 1920x1080 477x268mm 21.5-inch   | 1        | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 110      | 41.51%  |
| 1280x1024 (SXGA)   | 31       | 11.7%   |
| 1680x1050 (WSXGA+) | 19       | 7.17%   |
| 3840x2160 (4K)     | 18       | 6.79%   |
| 2560x1440 (QHD)    | 17       | 6.42%   |
| 1920x1200 (WUXGA)  | 17       | 6.42%   |
| 1440x900 (WXGA+)   | 15       | 5.66%   |
| 1366x768 (WXGA)    | 9        | 3.4%    |
| 1600x1200          | 7        | 2.64%   |
| 1600x900 (HD+)     | 6        | 2.26%   |
| 1360x768           | 4        | 1.51%   |
| 3440x1440          | 3        | 1.13%   |
| 1920x540           | 2        | 0.75%   |
| 1024x768 (XGA)     | 2        | 0.75%   |
| Unknown            | 2        | 0.75%   |
| 3200x1080          | 1        | 0.38%   |
| 1280x960           | 1        | 0.38%   |
| 1280x720 (HD)      | 1        | 0.38%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 43       | 15.75%  |
| 23      | 35       | 12.82%  |
| 21      | 29       | 10.62%  |
| 19      | 27       | 9.89%   |
| 27      | 26       | 9.52%   |
| Unknown | 23       | 8.42%   |
| 17      | 17       | 6.23%   |
| 22      | 10       | 3.66%   |
| 20      | 10       | 3.66%   |
| 18      | 10       | 3.66%   |
| 25      | 8        | 2.93%   |
| 84      | 4        | 1.47%   |
| 31      | 4        | 1.47%   |
| 26      | 4        | 1.47%   |
| 72      | 3        | 1.1%    |
| 65      | 2        | 0.73%   |
| 54      | 2        | 0.73%   |
| 48      | 2        | 0.73%   |
| 46      | 2        | 0.73%   |
| 39      | 2        | 0.73%   |
| 34      | 2        | 0.73%   |
| 32      | 2        | 0.73%   |
| 15      | 2        | 0.73%   |
| 42      | 1        | 0.37%   |
| 35      | 1        | 0.37%   |
| 14      | 1        | 0.37%   |
| 11      | 1        | 0.37%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 100      | 38.17%  |
| 401-500     | 77       | 29.39%  |
| Unknown     | 23       | 8.78%   |
| 301-350     | 19       | 7.25%   |
| 351-400     | 13       | 4.96%   |
| 1001-1500   | 8        | 3.05%   |
| 1501-2000   | 7        | 2.67%   |
| 601-700     | 5        | 1.91%   |
| 701-800     | 4        | 1.53%   |
| 801-900     | 3        | 1.15%   |
| 201-300     | 2        | 0.76%   |
| 901-1000    | 1        | 0.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 139      | 53.88%  |
| 16/10   | 51       | 19.77%  |
| 5/4     | 29       | 11.24%  |
| Unknown | 19       | 7.36%   |
| 4/3     | 12       | 4.65%   |
| 3/2     | 4        | 1.55%   |
| 21/9    | 3        | 1.16%   |
| 6/5     | 1        | 0.39%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 91       | 33.7%   |
| 151-200        | 47       | 17.41%  |
| 251-300        | 28       | 10.37%  |
| 301-350        | 26       | 9.63%   |
| 141-150        | 25       | 9.26%   |
| Unknown        | 23       | 8.52%   |
| More than 1000 | 12       | 4.44%   |
| 351-500        | 9        | 3.33%   |
| 501-1000       | 5        | 1.85%   |
| 101-110        | 2        | 0.74%   |
| 51-60          | 1        | 0.37%   |
| 111-120        | 1        | 0.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 177      | 69.41%  |
| 101-120 | 37       | 14.51%  |
| Unknown | 23       | 9.02%   |
| 1-50    | 9        | 3.53%   |
| 161-240 | 5        | 1.96%   |
| 121-160 | 4        | 1.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 218      | 80.74%  |
| 2     | 36       | 13.33%  |
| 0     | 13       | 4.81%   |
| 3     | 3        | 1.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 153      | 46.08%  |
| Intel                                  | 76       | 22.89%  |
| Qualcomm Atheros                       | 19       | 5.72%   |
| Ralink Technology                      | 14       | 4.22%   |
| Nvidia                                 | 12       | 3.61%   |
| TP-Link                                | 11       | 3.31%   |
| Qualcomm Atheros Communications        | 9        | 2.71%   |
| Broadcom                               | 9        | 2.71%   |
| Marvell Technology Group               | 5        | 1.51%   |
| Broadcom Limited                       | 4        | 1.2%    |
| Edimax Technology                      | 2        | 0.6%    |
| ASUSTek Computer                       | 2        | 0.6%    |
| WiseGroup                              | 1        | 0.3%    |
| VIA Technologies                       | 1        | 0.3%    |
| ULi Electronics                        | 1        | 0.3%    |
| Texas Instruments                      | 1        | 0.3%    |
| Sony Ericsson Mobile Communications AB | 1        | 0.3%    |
| Samsung Electronics                    | 1        | 0.3%    |
| Pulse-Eight                            | 1        | 0.3%    |
| Prestigio                              | 1        | 0.3%    |
| National Semiconductor                 | 1        | 0.3%    |
| Microsoft                              | 1        | 0.3%    |
| Micro Star International               | 1        | 0.3%    |
| MediaTek                               | 1        | 0.3%    |
| Huawei Technologies                    | 1        | 0.3%    |
| D-Link                                 | 1        | 0.3%    |
| ASIX Electronics                       | 1        | 0.3%    |
| Accton Technology                      | 1        | 0.3%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 126      | 34.71%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 11       | 3.03%   |
| Intel I211 Gigabit Network Connection                             | 11       | 3.03%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9        | 2.48%   |
| Qualcomm Atheros AR9271 802.11n                                   | 9        | 2.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9        | 2.48%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 8        | 2.2%    |
| Intel Wi-Fi 6 AX200                                               | 7        | 1.93%   |
| Intel Ethernet Connection (2) I219-V                              | 7        | 1.93%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 6        | 1.65%   |
| Nvidia MCP61 Ethernet                                             | 6        | 1.65%   |
| Intel Ethernet Controller I225-V                                  | 5        | 1.38%   |
| Intel 82579V Gigabit Network Connection                           | 5        | 1.38%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 4        | 1.1%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 1.1%    |
| Ralink MT7601U Wireless Adapter                                   | 4        | 1.1%    |
| Intel Ethernet Connection (7) I219-V                              | 4        | 1.1%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 1.1%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 4        | 1.1%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 3        | 0.83%   |
| Ralink RT5370 Wireless Adapter                                    | 3        | 0.83%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 0.83%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 3        | 0.83%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 3        | 0.83%   |
| Intel Wireless 8260                                               | 3        | 0.83%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 0.83%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 0.83%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                             | 2        | 0.55%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 2        | 0.55%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2        | 0.55%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 0.55%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 2        | 0.55%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.55%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2        | 0.55%   |
| Intel 82578DC Gigabit Network Connection                          | 2        | 0.55%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 0.55%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2        | 0.55%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 2        | 0.55%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 2        | 0.55%   |
| Broadcom Limited NetXtreme BCM5754 Gigabit Ethernet PCI Express   | 2        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 19       | 23.46%  |
| Ralink Technology               | 14       | 17.28%  |
| Realtek Semiconductor           | 13       | 16.05%  |
| TP-Link                         | 11       | 13.58%  |
| Qualcomm Atheros Communications | 9        | 11.11%  |
| Qualcomm Atheros                | 3        | 3.7%    |
| Edimax Technology               | 2        | 2.47%   |
| Broadcom                        | 2        | 2.47%   |
| ASUSTek Computer                | 2        | 2.47%   |
| Texas Instruments               | 1        | 1.23%   |
| Microsoft                       | 1        | 1.23%   |
| Micro Star International        | 1        | 1.23%   |
| MediaTek                        | 1        | 1.23%   |
| D-Link                          | 1        | 1.23%   |
| Accton Technology               | 1        | 1.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9271 802.11n                                               | 9        | 11.11%  |
| Intel Wi-Fi 6 AX200                                                           | 7        | 8.64%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 6        | 7.41%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 4        | 4.94%   |
| Ralink MT7601U Wireless Adapter                                               | 4        | 4.94%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 3        | 3.7%    |
| Ralink RT5370 Wireless Adapter                                                | 3        | 3.7%    |
| Intel Wireless 8260                                                           | 3        | 3.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 3        | 3.7%    |
| TP-Link TL-WN822N Version 4 RTL8192EU                                         | 2        | 2.47%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 2        | 2.47%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 2        | 2.47%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 2        | 2.47%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 2        | 2.47%   |
| ASUS USB-N14 802.11b/g/n (2x2) Wireless Adapter [Ralink RT5372]               | 2        | 2.47%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1        | 1.23%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                                     | 1        | 1.23%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1        | 1.23%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1        | 1.23%   |
| TP-Link 802.11ac NIC                                                          | 1        | 1.23%   |
| Texas Instruments ACX 111 54Mbps Wireless Interface                           | 1        | 1.23%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1        | 1.23%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1        | 1.23%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 1        | 1.23%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1        | 1.23%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                        | 1        | 1.23%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                      | 1        | 1.23%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                             | 1        | 1.23%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1        | 1.23%   |
| Microsoft Xbox 360 Wireless Adapter                                           | 1        | 1.23%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070]    | 1        | 1.23%   |
| MediaTek WiFi                                                                 | 1        | 1.23%   |
| Intel Wireless-AC 9260                                                        | 1        | 1.23%   |
| Intel Centrino Wireless-N 2230                                                | 1        | 1.23%   |
| Intel Centrino Advanced-N 6235                                                | 1        | 1.23%   |
| Intel 700 Series Chipset Family Wi-Fi                                         | 1        | 1.23%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT2870]                      | 1        | 1.23%   |
| Edimax AC600 USB                                                              | 1        | 1.23%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.A3) [Ralink RT5370]                 | 1        | 1.23%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 1        | 1.23%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 151      | 56.34%  |
| Intel                                  | 66       | 24.63%  |
| Qualcomm Atheros                       | 16       | 5.97%   |
| Nvidia                                 | 12       | 4.48%   |
| Broadcom                               | 7        | 2.61%   |
| Marvell Technology Group               | 5        | 1.87%   |
| Broadcom Limited                       | 4        | 1.49%   |
| VIA Technologies                       | 1        | 0.37%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.37%   |
| Samsung Electronics                    | 1        | 0.37%   |
| Prestigio                              | 1        | 0.37%   |
| National Semiconductor                 | 1        | 0.37%   |
| Huawei Technologies                    | 1        | 0.37%   |
| ASIX Electronics                       | 1        | 0.37%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 126      | 45.16%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 11       | 3.94%   |
| Intel I211 Gigabit Network Connection                             | 11       | 3.94%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9        | 3.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9        | 3.23%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 8        | 2.87%   |
| Intel Ethernet Connection (2) I219-V                              | 7        | 2.51%   |
| Nvidia MCP61 Ethernet                                             | 6        | 2.15%   |
| Intel Ethernet Controller I225-V                                  | 5        | 1.79%   |
| Intel 82579V Gigabit Network Connection                           | 5        | 1.79%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 1.43%   |
| Intel Ethernet Connection (7) I219-V                              | 4        | 1.43%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 1.43%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 4        | 1.43%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 1.08%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 3        | 1.08%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 3        | 1.08%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.08%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.72%   |
| Intel 82578DC Gigabit Network Connection                          | 2        | 0.72%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 0.72%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2        | 0.72%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 2        | 0.72%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 2        | 0.72%   |
| Broadcom Limited NetXtreme BCM5754 Gigabit Ethernet PCI Express   | 2        | 0.72%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.36%   |
| Sony Ericsson Mobile AB E5823                                     | 1        | 0.36%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.36%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.36%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.36%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.36%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.36%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.36%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.36%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.36%   |
| Prestigio PSP5453DUO                                              | 1        | 0.36%   |
| Nvidia MCP77 Ethernet                                             | 1        | 0.36%   |
| Nvidia MCP67 Ethernet                                             | 1        | 0.36%   |
| Nvidia MCP65 Ethernet                                             | 1        | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 254      | 75.6%   |
| WiFi     | 79       | 23.51%  |
| Modem    | 2        | 0.6%    |
| Unknown  | 1        | 0.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 216      | 83.08%  |
| WiFi     | 44       | 16.92%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 198      | 75%     |
| 2     | 48       | 18.18%  |
| 3     | 8        | 3.03%   |
| 0     | 6        | 2.27%   |
| 4     | 3        | 1.14%   |
| 5     | 1        | 0.38%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 252      | 96.18%  |
| Yes  | 10       | 3.82%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 20       | 44.44%  |
| Cambridge Silicon Radio         | 7        | 15.56%  |
| Realtek Semiconductor           | 4        | 8.89%   |
| ASUSTek Computer                | 4        | 8.89%   |
| Micro Star International        | 2        | 4.44%   |
| HTC (High Tech Computer)        | 2        | 4.44%   |
| TP-Link                         | 1        | 2.22%   |
| Qualcomm Atheros Communications | 1        | 2.22%   |
| Integrated System Solution      | 1        | 2.22%   |
| IMC Networks                    | 1        | 2.22%   |
| Broadcom                        | 1        | 2.22%   |
| Belkin Components               | 1        | 2.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 7        | 15.56%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 7        | 15.56%  |
| Intel Wireless-AC 3168 Bluetooth                                     | 3        | 6.67%   |
| Intel Bluetooth wireless interface                                   | 3        | 6.67%   |
| Intel AX210 Bluetooth                                                | 3        | 6.67%   |
| Realtek Bluetooth Radio                                              | 2        | 4.44%   |
| Micro Star International Bluetooth Device                            | 2        | 4.44%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 2        | 4.44%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 2        | 4.44%   |
| ASUS Bluetooth Radio                                                 | 2        | 4.44%   |
| TP-Link UB500 Adapter                                                | 1        | 2.22%   |
| Realtek RTL8821A Bluetooth                                           | 1        | 2.22%   |
| Realtek RTL8723B Bluetooth                                           | 1        | 2.22%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 1        | 2.22%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 1        | 2.22%   |
| Intel Bluetooth Device                                               | 1        | 2.22%   |
| Integrated System Solution Bluetooth Device                          | 1        | 2.22%   |
| IMC Networks Bluetooth Radio                                         | 1        | 2.22%   |
| Broadcom BCM2045 Bluetooth                                           | 1        | 2.22%   |
| Belkin Components Bluetooth Mini Dongle                              | 1        | 2.22%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 1        | 2.22%   |
| ASUS ASUS USB-BT500                                                  | 1        | 2.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 153      | 37.23%  |
| AMD                      | 113      | 27.49%  |
| Nvidia                   | 101      | 24.57%  |
| C-Media Electronics      | 10       | 2.43%   |
| Creative Labs            | 8        | 1.95%   |
| VIA Technologies         | 4        | 0.97%   |
| Creative Technology      | 4        | 0.97%   |
| Lenovo                   | 2        | 0.49%   |
| Blue Microphones         | 2        | 0.49%   |
| ASUSTek Computer         | 2        | 0.49%   |
| Yamaha                   | 1        | 0.24%   |
| Valve Software           | 1        | 0.24%   |
| ULi Electronics          | 1        | 0.24%   |
| SteelSeries ApS          | 1        | 0.24%   |
| Nordic Semiconductor ASA | 1        | 0.24%   |
| Micro Star International | 1        | 0.24%   |
| Logitech                 | 1        | 0.24%   |
| GN Netcom                | 1        | 0.24%   |
| Fortemedia               | 1        | 0.24%   |
| Barco Display Systems    | 1        | 0.24%   |
| AKAI Professional M.I.   | 1        | 0.24%   |
| A4Tech                   | 1        | 0.24%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                                                    | 25       | 5.2%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                         | 24       | 4.99%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 19       | 3.95%   |
| AMD Starship/Matisse HD Audio Controller                                                        | 18       | 3.74%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 17       | 3.53%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 16       | 3.33%   |
| AMD FCH Azalia Controller                                                                       | 15       | 3.12%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                | 13       | 2.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 12       | 2.49%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 11       | 2.29%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                  | 10       | 2.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 10       | 2.08%   |
| Intel 200 Series PCH HD Audio                                                                   | 9        | 1.87%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                             | 9        | 1.87%   |
| Nvidia High Definition Audio Controller                                                         | 8        | 1.66%   |
| Nvidia GP106 High Definition Audio Controller                                                   | 8        | 1.66%   |
| Intel Cannon Lake PCH cAVS                                                                      | 8        | 1.66%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 8        | 1.66%   |
| AMD Family 17h/19h HD Audio Controller                                                          | 8        | 1.66%   |
| Nvidia MCP61 High Definition Audio                                                              | 7        | 1.46%   |
| Nvidia GP108 High Definition Audio Controller                                                   | 6        | 1.25%   |
| Nvidia GF108 High Definition Audio Controller                                                   | 6        | 1.25%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                      | 6        | 1.25%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                    | 6        | 1.25%   |
| AMD Renoir Radeon High Definition Audio Controller                                              | 5        | 1.04%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                                  | 5        | 1.04%   |
| Nvidia GP107GL High Definition Audio Controller                                                 | 4        | 0.83%   |
| Nvidia GM206 High Definition Audio Controller                                                   | 4        | 0.83%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                   | 4        | 0.83%   |
| Nvidia GK107 HDMI Audio Controller                                                              | 4        | 0.83%   |
| Intel 9 Series Chipset Family HD Audio Controller                                               | 4        | 0.83%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                             | 4        | 0.83%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                        | 4        | 0.83%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 4        | 0.83%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                                   | 4        | 0.83%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                  | 4        | 0.83%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                             | 4        | 0.83%   |
| AMD Navi 10 HDMI Audio                                                                          | 4        | 0.83%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                          | 4        | 0.83%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]               | 4        | 0.83%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 47       | 29.75%  |
| Unknown             | 43       | 27.22%  |
| Crucial             | 12       | 7.59%   |
| Samsung Electronics | 10       | 6.33%   |
| SK hynix            | 9        | 5.7%    |
| Corsair             | 9        | 5.7%    |
| Patriot             | 6        | 3.8%    |
| G.Skill             | 6        | 3.8%    |
| Micron Technology   | 4        | 2.53%   |
| Elpida              | 4        | 2.53%   |
| Unknown             | 3        | 1.9%    |
| Hewlett-Packard     | 2        | 1.27%   |
| Unknown (8AC8)      | 1        | 0.63%   |
| Transcend           | 1        | 0.63%   |
| A-DATA Technology   | 1        | 0.63%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM 800MT/s                      | 4        | 2.12%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 4        | 2.12%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                   | 3        | 1.59%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s     | 3        | 1.59%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s        | 3        | 1.59%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s      | 3        | 1.59%   |
| Unknown                                                  | 3        | 1.59%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s             | 2        | 1.06%   |
| Unknown RAM Module 2048MB DIMM DDR2 333MT/s              | 2        | 1.06%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                  | 2        | 1.06%   |
| Unknown RAM Module 1024MB DIMM DDR 333MT/s               | 2        | 1.06%   |
| Unknown RAM Module 1024MB DIMM 533MT/s                   | 2        | 1.06%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s     | 2        | 1.06%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s      | 2        | 1.06%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s      | 2        | 1.06%   |
| Samsung RAM M378B2873EH1-CH9 1GB DIMM DDR3 1334MT/s      | 2        | 1.06%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s      | 2        | 1.06%   |
| Kingston RAM KHX1600C9D3/2GX 2GB DIMM DDR3 1600MT/s      | 2        | 1.06%   |
| Kingston RAM KHX1600C10D3/8GX 8GB DIMM DDR3 1600MT/s     | 2        | 1.06%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s      | 2        | 1.06%   |
| Kingston RAM KF2666C15S4/8G 8GB SODIMM DDR4 2667MT/s     | 2        | 1.06%   |
| Kingston RAM 99U5584-001.A00LF 4096MB DIMM DDR3 1600MT/s | 2        | 1.06%   |
| Kingston RAM 2G-UDIMM 2GB DIMM DDR2 800MT/s              | 2        | 1.06%   |
| Corsair RAM CML8GX3M2A1600C9 4096MB DIMM DDR3 1867MT/s   | 2        | 1.06%   |
| Unknown RAM Module 64MB DIMM DRAM 100MT/s                | 1        | 0.53%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s                | 1        | 0.53%   |
| Unknown RAM Module 512MB DIMM DDR 333MT/s                | 1        | 0.53%   |
| Unknown RAM Module 512MB DIMM DDR 200MT/s                | 1        | 0.53%   |
| Unknown RAM Module 512MB DIMM 533MT/s                    | 1        | 0.53%   |
| Unknown RAM Module 4GB FB-DIMM DDR2 667MT/s              | 1        | 0.53%   |
| Unknown RAM Module 4GB DIMM 400MT/s                      | 1        | 0.53%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s             | 1        | 0.53%   |
| Unknown RAM Module 4096MB DIMM 400MT/s                   | 1        | 0.53%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 1        | 0.53%   |
| Unknown RAM Module 4096MB DIMM 1066MT/s                  | 1        | 0.53%   |
| Unknown RAM Module 2GB FB-DIMM DDR2 667MT/s              | 1        | 0.53%   |
| Unknown RAM Module 2GB DIMM SDRAM 800MT/s                | 1        | 0.53%   |
| Unknown RAM Module 2GB DIMM SDRAM 667MT/s                | 1        | 0.53%   |
| Unknown RAM Module 2GB DIMM SDRAM                        | 1        | 0.53%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                | 1        | 0.53%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 46       | 31.94%  |
| DDR3    | 44       | 30.56%  |
| DDR2    | 18       | 12.5%   |
| Unknown | 17       | 11.81%  |
| SDRAM   | 12       | 8.33%   |
| DDR     | 5        | 3.47%   |
| DRAM    | 1        | 0.69%   |
| DDR5    | 1        | 0.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 133      | 95.68%  |
| SODIMM  | 5        | 3.6%    |
| FB-DIMM | 1        | 0.72%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 44       | 26.99%  |
| 2048  | 41       | 25.15%  |
| 4096  | 38       | 23.31%  |
| 1024  | 16       | 9.82%   |
| 16384 | 11       | 6.75%   |
| 512   | 5        | 3.07%   |
| 32768 | 4        | 2.45%   |
| 256   | 2        | 1.23%   |
| 128   | 1        | 0.61%   |
| 64    | 1        | 0.61%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 31       | 18.56%  |
| 800     | 16       | 9.58%   |
| 1333    | 15       | 8.98%   |
| 667     | 11       | 6.59%   |
| 3600    | 10       | 5.99%   |
| 2667    | 9        | 5.39%   |
| 3200    | 8        | 4.79%   |
| 2400    | 6        | 3.59%   |
| 2133    | 5        | 2.99%   |
| 1867    | 5        | 2.99%   |
| 333     | 5        | 2.99%   |
| 3466    | 4        | 2.4%    |
| 400     | 4        | 2.4%    |
| 1334    | 3        | 1.8%    |
| 533     | 3        | 1.8%    |
| Unknown | 3        | 1.8%    |
| 3800    | 2        | 1.2%    |
| 3733    | 2        | 1.2%    |
| 3266    | 2        | 1.2%    |
| 3000    | 2        | 1.2%    |
| 1866    | 2        | 1.2%    |
| 1800    | 2        | 1.2%    |
| 1066    | 2        | 1.2%    |
| 57535   | 1        | 0.6%    |
| 6400    | 1        | 0.6%    |
| 4400    | 1        | 0.6%    |
| 4266    | 1        | 0.6%    |
| 4000    | 1        | 0.6%    |
| 3933    | 1        | 0.6%    |
| 3666    | 1        | 0.6%    |
| 3400    | 1        | 0.6%    |
| 3333    | 1        | 0.6%    |
| 2666    | 1        | 0.6%    |
| 1639    | 1        | 0.6%    |
| 1067    | 1        | 0.6%    |
| 266     | 1        | 0.6%    |
| 200     | 1        | 0.6%    |
| 100     | 1        | 0.6%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 12       | 80%     |
| Star Micronics      | 1        | 6.67%   |
| Samsung Electronics | 1        | 6.67%   |
| Canon               | 1        | 6.67%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| HP LaserJet 1020                                | 4        | 26.67%  |
| HP Deskjet 1050 J410                            | 2        | 13.33%  |
| Star Micronics IP1000 Printer USB001            | 1        | 6.67%   |
| Samsung M262x/M282x Xpress Series Laser Printer | 1        | 6.67%   |
| HP OfficeJet 6950                               | 1        | 6.67%   |
| HP LaserJet M14-M17                             | 1        | 6.67%   |
| HP LaserJet M101-M106                           | 1        | 6.67%   |
| HP LaserJet 1150                                | 1        | 6.67%   |
| HP DeskJet 2700 series                          | 1        | 6.67%   |
| HP Deskjet 1510                                 | 1        | 6.67%   |
| Canon PIXMA MP230                               | 1        | 6.67%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 2        | 50%     |
| Minolta         | 1        | 25%     |
| Hewlett-Packard | 1        | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Minolta Dimage Scan Dual III AF-2840 (2889) | 1        | 25%     |
| HP ScanJet 3800c                            | 1        | 25%     |
| Canon CanoScan LiDE 90                      | 1        | 25%     |
| Canon CanoScan LIDE 25                      | 1        | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech                    | 8        | 21.62%  |
| Microsoft                   | 7        | 18.92%  |
| Microdia                    | 5        | 13.51%  |
| Creative Technology         | 3        | 8.11%   |
| Z-Star Microelectronics     | 2        | 5.41%   |
| Syntek                      | 2        | 5.41%   |
| Alcor Micro                 | 2        | 5.41%   |
| Valve Software              | 1        | 2.7%    |
| Unknown                     | 1        | 2.7%    |
| MacroSilicon                | 1        | 2.7%    |
| KYE Systems (Mouse Systems) | 1        | 2.7%    |
| GenesysLogic Technology     | 1        | 2.7%    |
| Generalplus Technology      | 1        | 2.7%    |
| Cubeternet                  | 1        | 2.7%    |
| Apple                       | 1        | 2.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Microdia Sonix USB 2.0 Camera              | 3        | 7.69%   |
| Syntek Integrated RGB Camera               | 2        | 5.13%   |
| Microsoft LifeCam Cinema                   | 2        | 5.13%   |
| Creative Live! Cam Sync HD [VF0770]        | 2        | 5.13%   |
| Alcor Micro USB 2.0 PC Camera              | 2        | 5.13%   |
| Z-Star Vega USB 2.0 Camera                 | 1        | 2.56%   |
| Z-Star A4 TECH HD PC Camera                | 1        | 2.56%   |
| Valve Software 3D Camera                   | 1        | 2.56%   |
| Unknown HD camera                          | 1        | 2.56%   |
| Microsoft MicrosoftÂ LifeCam VX-5500      | 1        | 2.56%   |
| Microsoft LifeCam VX-800                   | 1        | 2.56%   |
| Microsoft LifeCam VX-700                   | 1        | 2.56%   |
| Microsoft LifeCam VX-500 [1357]            | 1        | 2.56%   |
| Microsoft LifeCam HD-3000                  | 1        | 2.56%   |
| Microdia USB 2.0 Camera                    | 1        | 2.56%   |
| Microdia Camera                            | 1        | 2.56%   |
| MacroSilicon USB Video                     | 1        | 2.56%   |
| Logitech Webcam C930e                      | 1        | 2.56%   |
| Logitech Webcam C925e                      | 1        | 2.56%   |
| Logitech Webcam C270                       | 1        | 2.56%   |
| Logitech Webcam C200                       | 1        | 2.56%   |
| Logitech Webcam C110                       | 1        | 2.56%   |
| Logitech QuickCam Pro 9000                 | 1        | 2.56%   |
| Logitech HD Webcam C525                    | 1        | 2.56%   |
| Logitech HD Pro Webcam C920                | 1        | 2.56%   |
| Logitech C920 PRO HD Webcam                | 1        | 2.56%   |
| Logitech C505e HD Webcam                   | 1        | 2.56%   |
| KYE Systems (Mouse Systems) FaceCam 1000X  | 1        | 2.56%   |
| GenesysLogic USB2.0 UVC PC Camera          | 1        | 2.56%   |
| Generalplus 808 Camera                     | 1        | 2.56%   |
| Cubeternet HDMI to U3 capture              | 1        | 2.56%   |
| Creative Live! Cam Chat HD [VF0700/VF0790] | 1        | 2.56%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X            | 1        | 2.56%   |

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


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Gemalto (was Gemplus) | 2        | 50%     |
| OmniKey               | 1        | 25%     |
| Alcor Micro           | 1        | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 2        | 50%     |
| OmniKey CardMan 3121 (HID Technologies)           | 1        | 25%     |
| Alcor Micro AU9540 Smartcard Reader               | 1        | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 228      | 84.44%  |
| 1     | 38       | 14.07%  |
| 2     | 3        | 1.11%   |
| 3     | 1        | 0.37%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 22       | 48.89%  |
| Net/wireless             | 8        | 17.78%  |
| Chipcard                 | 4        | 8.89%   |
| Sound                    | 2        | 4.44%   |
| Communication controller | 2        | 4.44%   |
| Bluetooth                | 2        | 4.44%   |
| Unassigned class         | 1        | 2.22%   |
| Network                  | 1        | 2.22%   |
| Net/ethernet             | 1        | 2.22%   |
| Multimedia controller    | 1        | 2.22%   |
| Card reader              | 1        | 2.22%   |

