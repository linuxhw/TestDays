Linux in South Africa - Tested Hardware & Statistics (Desktops)
---------------------------------------------------------------

A project to collect tested hardware configurations for Linux in South Africa.

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

Total: 757

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | PRO X670-P WIFI             | [a411b722e3](https://linux-hardware.org/?probe=a411b722e3) | May 05, 2024 |
| Dell          | 03NVJ6 A03                  | [fd0f0fad2d](https://linux-hardware.org/?probe=fd0f0fad2d) | May 04, 2024 |
| Gigabyte      | H61M-S2PV                   | [c3bf425427](https://linux-hardware.org/?probe=c3bf425427) | Apr 27, 2024 |
| MSI           | PRO B550M-VC WIFI           | [971ae6415a](https://linux-hardware.org/?probe=971ae6415a) | Apr 26, 2024 |
| Gigabyte      | B650I AORUS ULTRA se2       | [0fcc20ba38](https://linux-hardware.org/?probe=0fcc20ba38) | Apr 22, 2024 |
| Biostar       | H61MLV3                     | [a383411310](https://linux-hardware.org/?probe=a383411310) | Apr 21, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [9778349d4b](https://linux-hardware.org/?probe=9778349d4b) | Apr 18, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [c7e32d8f0c](https://linux-hardware.org/?probe=c7e32d8f0c) | Apr 18, 2024 |
| Pegatron      | IPMSB-H61                   | [8e8c4a6627](https://linux-hardware.org/?probe=8e8c4a6627) | Apr 17, 2024 |
| MSI           | B450 GAMING PRO CARBON A... | [d2060f0dcd](https://linux-hardware.org/?probe=d2060f0dcd) | Apr 14, 2024 |
| MSI           | B450 GAMING PRO CARBON A... | [37733a1209](https://linux-hardware.org/?probe=37733a1209) | Apr 09, 2024 |
| MSI           | X99S SLI PLUS               | [a61ed0e4eb](https://linux-hardware.org/?probe=a61ed0e4eb) | Apr 09, 2024 |
| ASUSTek       | P8B75-V                     | [366bbe1d9b](https://linux-hardware.org/?probe=366bbe1d9b) | Apr 08, 2024 |
| HP            | 1497                        | [7e1f82d39c](https://linux-hardware.org/?probe=7e1f82d39c) | Apr 05, 2024 |
| Lenovo        | ThinkCentre M58p 6234CL2    | [d2eea8b39c](https://linux-hardware.org/?probe=d2eea8b39c) | Apr 01, 2024 |
| Biostar       | Hi-Fi B85Z                  | [4b6b31177e](https://linux-hardware.org/?probe=4b6b31177e) | Mar 23, 2024 |
| Apple         | Mac-F42C88C8 Proto1         | [54f6a8451a](https://linux-hardware.org/?probe=54f6a8451a) | Mar 22, 2024 |
| ASRock        | Z97M Pro4                   | [d82ec98b2f](https://linux-hardware.org/?probe=d82ec98b2f) | Mar 14, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [d63b912feb](https://linux-hardware.org/?probe=d63b912feb) | Feb 19, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [710c281afe](https://linux-hardware.org/?probe=710c281afe) | Feb 19, 2024 |
| ASUSTek       | P5KPL-AM SE                 | [c0926b6944](https://linux-hardware.org/?probe=c0926b6944) | Jan 26, 2024 |
| ASUSTek       | P5KPL-AM SE                 | [fd8742e98a](https://linux-hardware.org/?probe=fd8742e98a) | Jan 26, 2024 |
| Foxconn       | H61MXE                      | [0a7a342b95](https://linux-hardware.org/?probe=0a7a342b95) | Jan 20, 2024 |
| MSI           | H310M PRO-VD                | [3cdbce90e0](https://linux-hardware.org/?probe=3cdbce90e0) | Jan 17, 2024 |
| ASUSTek       | PRIME A320M-K               | [ffe6ae701f](https://linux-hardware.org/?probe=ffe6ae701f) | Jan 15, 2024 |
| ASRock        | Z97M Pro4                   | [594754cd87](https://linux-hardware.org/?probe=594754cd87) | Jan 13, 2024 |
| Dell          | 0YXT71 A03                  | [3aa9c455f5](https://linux-hardware.org/?probe=3aa9c455f5) | Jan 13, 2024 |
| HP            | ProLiant ML150 G6           | [15df93ab9c](https://linux-hardware.org/?probe=15df93ab9c) | Jan 10, 2024 |
| Dell          | 0KV62T A00                  | [17aa442f24](https://linux-hardware.org/?probe=17aa442f24) | Jan 10, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [f618c2c6b8](https://linux-hardware.org/?probe=f618c2c6b8) | Jan 10, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [af4d83b40f](https://linux-hardware.org/?probe=af4d83b40f) | Jan 10, 2024 |
| ASUSTek       | PRIME X570-P                | [f7f3e0ddc9](https://linux-hardware.org/?probe=f7f3e0ddc9) | Jan 01, 2024 |
| ASUSTek       | PRIME Z690-A                | [faf34bf75f](https://linux-hardware.org/?probe=faf34bf75f) | Dec 30, 2023 |
| Gigabyte      | Z370 HD3-CF                 | [25e443386a](https://linux-hardware.org/?probe=25e443386a) | Dec 26, 2023 |
| Dell          | 0JP3NX A01                  | [706947928d](https://linux-hardware.org/?probe=706947928d) | Dec 21, 2023 |
| Dell          | 0KV62T A00                  | [b6ca701110](https://linux-hardware.org/?probe=b6ca701110) | Dec 18, 2023 |
| MSI           | B350 TOMAHAWK               | [18f6c41058](https://linux-hardware.org/?probe=18f6c41058) | Dec 10, 2023 |
| Dell          | 0KV62T A00                  | [df48d704bb](https://linux-hardware.org/?probe=df48d704bb) | Dec 09, 2023 |
| Foxconn       | 2A8Ch                       | [b15f912ae7](https://linux-hardware.org/?probe=b15f912ae7) | Dec 06, 2023 |
| Intel         | DQ67SW AAG12527-309         | [99293a328c](https://linux-hardware.org/?probe=99293a328c) | Dec 02, 2023 |
| Intel         | DQ67SW AAG12527-309         | [b8e3a992b3](https://linux-hardware.org/?probe=b8e3a992b3) | Dec 02, 2023 |
| Acer          | Veriton M290                | [30dd8ffe84](https://linux-hardware.org/?probe=30dd8ffe84) | Nov 26, 2023 |
| ASRock        | B250M-HDV                   | [1d8de35042](https://linux-hardware.org/?probe=1d8de35042) | Nov 21, 2023 |
| Foxconn       | 2A8Ch                       | [0b8966c181](https://linux-hardware.org/?probe=0b8966c181) | Nov 19, 2023 |
| Dell          | 0J3C2F A00                  | [28440e547a](https://linux-hardware.org/?probe=28440e547a) | Nov 18, 2023 |
| Foxconn       | 2ABF                        | [10abd64eac](https://linux-hardware.org/?probe=10abd64eac) | Nov 18, 2023 |
| Intel         | DH77KC AAG39641-400         | [9ac3245bda](https://linux-hardware.org/?probe=9ac3245bda) | Nov 16, 2023 |
| Intel         | DH77KC AAG39641-400         | [e66475e9e4](https://linux-hardware.org/?probe=e66475e9e4) | Nov 16, 2023 |
| MSI           | Z87-G43 GAMING              | [71786a484b](https://linux-hardware.org/?probe=71786a484b) | Nov 16, 2023 |
| MSI           | Z87-G43 GAMING              | [1cf432335c](https://linux-hardware.org/?probe=1cf432335c) | Nov 15, 2023 |
| Gigabyte      | Z370 HD3-CF                 | [f29ef35eec](https://linux-hardware.org/?probe=f29ef35eec) | Nov 13, 2023 |
| ASUSTek       | H81M-C                      | [b3c22e6ea8](https://linux-hardware.org/?probe=b3c22e6ea8) | Nov 13, 2023 |
| Intel         | DH61WW AAG23116-206         | [75735f5b69](https://linux-hardware.org/?probe=75735f5b69) | Nov 11, 2023 |
| Gigabyte      | G31M-ES2C                   | [6de52fa703](https://linux-hardware.org/?probe=6de52fa703) | Nov 11, 2023 |
| Gigabyte      | G31M-ES2C                   | [70755c93a9](https://linux-hardware.org/?probe=70755c93a9) | Nov 10, 2023 |
| Dell          | 04YP6J A02                  | [b7f860630b](https://linux-hardware.org/?probe=b7f860630b) | Nov 10, 2023 |
| MSI           | B550-A PRO                  | [13fbc97a18](https://linux-hardware.org/?probe=13fbc97a18) | Nov 08, 2023 |
| MSI           | B450M MORTAR TITANIUM       | [a22610f17c](https://linux-hardware.org/?probe=a22610f17c) | Nov 06, 2023 |
| MSI           | H110M PRO-VH PLUS           | [128a0a94c7](https://linux-hardware.org/?probe=128a0a94c7) | Nov 02, 2023 |
| ASUSTek       | PRIME Z690-A                | [e356c02979](https://linux-hardware.org/?probe=e356c02979) | Oct 30, 2023 |
| Gigabyte      | X58A-UD3R                   | [7c4b363241](https://linux-hardware.org/?probe=7c4b363241) | Oct 28, 2023 |
| MSI           | Z87-G43 GAMING              | [31129675c0](https://linux-hardware.org/?probe=31129675c0) | Oct 24, 2023 |
| Gigabyte      | H61M-DS2                    | [ff9e1d6c16](https://linux-hardware.org/?probe=ff9e1d6c16) | Oct 22, 2023 |
| Gigabyte      | H61M-DS2                    | [9999b4b89a](https://linux-hardware.org/?probe=9999b4b89a) | Oct 22, 2023 |
| MSI           | H510M-A PRO                 | [f927a69d11](https://linux-hardware.org/?probe=f927a69d11) | Oct 20, 2023 |
| Dell          | 0J3C2F A00                  | [eb391611f3](https://linux-hardware.org/?probe=eb391611f3) | Oct 19, 2023 |
| HP            | 3397                        | [555ad3c716](https://linux-hardware.org/?probe=555ad3c716) | Oct 19, 2023 |
| Dell          | 0J3C2F A00                  | [df408e2203](https://linux-hardware.org/?probe=df408e2203) | Oct 18, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [8d41cb80bf](https://linux-hardware.org/?probe=8d41cb80bf) | Oct 13, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [339d1c4a25](https://linux-hardware.org/?probe=339d1c4a25) | Oct 13, 2023 |
| Gigabyte      | A520M DS3H                  | [fa2c7e0da1](https://linux-hardware.org/?probe=fa2c7e0da1) | Oct 03, 2023 |
| Gigabyte      | A320M-H-CF                  | [10ebab5a3f](https://linux-hardware.org/?probe=10ebab5a3f) | Oct 02, 2023 |
| ASRock        | X670E Pro RS                | [da95378bd3](https://linux-hardware.org/?probe=da95378bd3) | Oct 02, 2023 |
| Gigabyte      | H77M-D3H                    | [1d1c00db51](https://linux-hardware.org/?probe=1d1c00db51) | Oct 02, 2023 |
| Intel         | DP45SG AAE27733-404         | [2b0868267b](https://linux-hardware.org/?probe=2b0868267b) | Oct 02, 2023 |
| Intel         | DP45SG AAE27733-404         | [d8e6101d6d](https://linux-hardware.org/?probe=d8e6101d6d) | Oct 02, 2023 |
| HP            | 0A50h                       | [e2082963e9](https://linux-hardware.org/?probe=e2082963e9) | Oct 01, 2023 |
| ASRock        | H81M-HG4                    | [7f2a420ea3](https://linux-hardware.org/?probe=7f2a420ea3) | Sep 29, 2023 |
| HP            | 3397                        | [e0396e65c6](https://linux-hardware.org/?probe=e0396e65c6) | Sep 26, 2023 |
| MSI           | Z370-A PRO                  | [77c3039fdc](https://linux-hardware.org/?probe=77c3039fdc) | Sep 24, 2023 |
| Gigabyte      | Z77X-UD3H                   | [f870f9e3ac](https://linux-hardware.org/?probe=f870f9e3ac) | Sep 21, 2023 |
| ASRock        | H81M-HG4                    | [7398d477e4](https://linux-hardware.org/?probe=7398d477e4) | Sep 10, 2023 |
| MSI           | Z370-A PRO                  | [b23d13eddc](https://linux-hardware.org/?probe=b23d13eddc) | Sep 10, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [08fd5b59f4](https://linux-hardware.org/?probe=08fd5b59f4) | Sep 10, 2023 |
| Intel         | DQ67SW AAG12527-310         | [774ca51623](https://linux-hardware.org/?probe=774ca51623) | Sep 06, 2023 |
| MSI           | Z370-A PRO                  | [19dc657d04](https://linux-hardware.org/?probe=19dc657d04) | Sep 06, 2023 |
| MSI           | Z370-A PRO                  | [8415f054e5](https://linux-hardware.org/?probe=8415f054e5) | Sep 05, 2023 |
| ASUSTek       | PRIME X570-P                | [08dd85e58d](https://linux-hardware.org/?probe=08dd85e58d) | Sep 05, 2023 |
| MSI           | Z370-A PRO                  | [b670e69634](https://linux-hardware.org/?probe=b670e69634) | Sep 04, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [99b1fcf2e9](https://linux-hardware.org/?probe=99b1fcf2e9) | Sep 03, 2023 |
| MSI           | H81M-P33                    | [266b226035](https://linux-hardware.org/?probe=266b226035) | Sep 02, 2023 |
| Gigabyte      | B75M-D3H                    | [9e7e8b4fbd](https://linux-hardware.org/?probe=9e7e8b4fbd) | Sep 01, 2023 |
| ASUSTek       | PRIME Z790-P D4             | [1cea30e36a](https://linux-hardware.org/?probe=1cea30e36a) | Aug 30, 2023 |
| ASUSTek       | PRIME Z790-P D4             | [20b35a5d4f](https://linux-hardware.org/?probe=20b35a5d4f) | Aug 30, 2023 |
| MSI           | A320M PRO-VD PLUS           | [1782829fec](https://linux-hardware.org/?probe=1782829fec) | Aug 29, 2023 |
| MSI           | G31M3-F V2                  | [fa4595b9f1](https://linux-hardware.org/?probe=fa4595b9f1) | Aug 21, 2023 |
| ASRock        | A520M-HDV                   | [cb333c6fae](https://linux-hardware.org/?probe=cb333c6fae) | Aug 20, 2023 |
| MSI           | G31M3-F V2                  | [3007f122d0](https://linux-hardware.org/?probe=3007f122d0) | Aug 19, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [64a1b8ad5d](https://linux-hardware.org/?probe=64a1b8ad5d) | Aug 14, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [9d7d216fc0](https://linux-hardware.org/?probe=9d7d216fc0) | Aug 14, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [3ea3856297](https://linux-hardware.org/?probe=3ea3856297) | Aug 12, 2023 |
| Gigabyte      | Z370 HD3-CF                 | [97505d521e](https://linux-hardware.org/?probe=97505d521e) | Aug 06, 2023 |
| ASUSTek       | Maximus V FORMULA           | [ee882ba789](https://linux-hardware.org/?probe=ee882ba789) | Aug 06, 2023 |
| Gigabyte      | H510M H                     | [51541062dc](https://linux-hardware.org/?probe=51541062dc) | Jul 31, 2023 |
| Gigabyte      | H97-Gaming 3                | [c15cd0e6c0](https://linux-hardware.org/?probe=c15cd0e6c0) | Jul 29, 2023 |
| Lenovo        | SDK0E50510 WIN              | [f375185ce4](https://linux-hardware.org/?probe=f375185ce4) | Jul 26, 2023 |
| ASRock        | Z97M Pro4                   | [1b062f3c31](https://linux-hardware.org/?probe=1b062f3c31) | Jul 26, 2023 |
| ASRock        | Z97M Pro4                   | [bca4424b5d](https://linux-hardware.org/?probe=bca4424b5d) | Jul 26, 2023 |
| Intel         | DQ965GF AAD41676-601        | [384577dee3](https://linux-hardware.org/?probe=384577dee3) | Jul 25, 2023 |
| Gigabyte      | Z77X-UD3H                   | [b75ed54995](https://linux-hardware.org/?probe=b75ed54995) | Jul 25, 2023 |
| Dell          | OptiPlex 755                | [9297c88bef](https://linux-hardware.org/?probe=9297c88bef) | Jul 23, 2023 |
| Dell          | OptiPlex 755                | [15827e6939](https://linux-hardware.org/?probe=15827e6939) | Jul 23, 2023 |
| MSI           | Z370-A PRO                  | [9a1d731109](https://linux-hardware.org/?probe=9a1d731109) | Jul 21, 2023 |
| Intel         | DH67BL AAG10189-209         | [8065e7b83a](https://linux-hardware.org/?probe=8065e7b83a) | Jul 20, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [3d605ad77f](https://linux-hardware.org/?probe=3d605ad77f) | Jul 19, 2023 |
| Gigabyte      | G31M-ES2C                   | [202ada5369](https://linux-hardware.org/?probe=202ada5369) | Jul 13, 2023 |
| Gigabyte      | G31M-ES2C                   | [88982c878a](https://linux-hardware.org/?probe=88982c878a) | Jul 13, 2023 |
| HP            | 1495                        | [8fa2ff9487](https://linux-hardware.org/?probe=8fa2ff9487) | Jul 12, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [7c6ad4407b](https://linux-hardware.org/?probe=7c6ad4407b) | Jul 11, 2023 |
| MSI           | Z170A PC MATE               | [39b5c3bb23](https://linux-hardware.org/?probe=39b5c3bb23) | Jul 11, 2023 |
| Gigabyte      | B75M-D3H                    | [8a9c93e501](https://linux-hardware.org/?probe=8a9c93e501) | Jul 06, 2023 |
| HP            | 0A50h                       | [125782672d](https://linux-hardware.org/?probe=125782672d) | Jul 06, 2023 |
| Gigabyte      | H61M-DS2                    | [b0c1a875c3](https://linux-hardware.org/?probe=b0c1a875c3) | Jul 06, 2023 |
| MSI           | Z390-A PRO                  | [36ca0aa203](https://linux-hardware.org/?probe=36ca0aa203) | Jul 03, 2023 |
| Unknown       | Unknown                     | [186a7eedb6](https://linux-hardware.org/?probe=186a7eedb6) | Jun 25, 2023 |
| ASUSTek       | PRIME X570-P                | [a243aaac72](https://linux-hardware.org/?probe=a243aaac72) | Jun 24, 2023 |
| Lenovo        | ThinkCentre M90p 5498R97    | [4a18635ad7](https://linux-hardware.org/?probe=4a18635ad7) | Jun 20, 2023 |
| Gigabyte      | H61M-DS2                    | [2310257292](https://linux-hardware.org/?probe=2310257292) | Jun 19, 2023 |
| Lenovo        | ThinkCentre M90p 5498R97    | [d2550efee5](https://linux-hardware.org/?probe=d2550efee5) | Jun 19, 2023 |
| Gigabyte      | H61M-DS2                    | [ee6f9906b5](https://linux-hardware.org/?probe=ee6f9906b5) | Jun 19, 2023 |
| MSI           | H81M-P33                    | [ce94354489](https://linux-hardware.org/?probe=ce94354489) | Jun 18, 2023 |
| MSI           | H81M-P33                    | [a581f2e058](https://linux-hardware.org/?probe=a581f2e058) | Jun 18, 2023 |
| MSI           | H67MA-E35                   | [8b37f91738](https://linux-hardware.org/?probe=8b37f91738) | Jun 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [b67a3f74c3](https://linux-hardware.org/?probe=b67a3f74c3) | Jun 15, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | [f92739d54b](https://linux-hardware.org/?probe=f92739d54b) | Jun 11, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | [07dac575d9](https://linux-hardware.org/?probe=07dac575d9) | Jun 10, 2023 |
| Intel         | DP45SG AAE27733-404         | [7abba8629e](https://linux-hardware.org/?probe=7abba8629e) | Jun 10, 2023 |
| Intel         | DP45SG AAE27733-404         | [afaced265f](https://linux-hardware.org/?probe=afaced265f) | Jun 10, 2023 |
| HP            | 1495                        | [32cfd162b8](https://linux-hardware.org/?probe=32cfd162b8) | Jun 05, 2023 |
| HP            | 1495                        | [f6c9f689ec](https://linux-hardware.org/?probe=f6c9f689ec) | Jun 05, 2023 |
| Dell          | 042P49 A01                  | [50f682ce84](https://linux-hardware.org/?probe=50f682ce84) | Jun 04, 2023 |
| Gigabyte      | H310M HD2                   | [b28787ecb7](https://linux-hardware.org/?probe=b28787ecb7) | Jun 04, 2023 |
| HP            | 1497                        | [5f1886622a](https://linux-hardware.org/?probe=5f1886622a) | May 29, 2023 |
| HP            | 1495                        | [15b94cba50](https://linux-hardware.org/?probe=15b94cba50) | May 28, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [aa7e36874d](https://linux-hardware.org/?probe=aa7e36874d) | May 17, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [e8dc0c0b41](https://linux-hardware.org/?probe=e8dc0c0b41) | May 17, 2023 |
| Intel         | Tiger Hill                  | [fdbe67045c](https://linux-hardware.org/?probe=fdbe67045c) | May 15, 2023 |
| Dell          | 06X1TJ A00                  | [d3107c9603](https://linux-hardware.org/?probe=d3107c9603) | May 14, 2023 |
| ASUSTek       | PRIME A520M-K               | [d266be713a](https://linux-hardware.org/?probe=d266be713a) | May 13, 2023 |
| Intel         | H61                         | [cd89c5b708](https://linux-hardware.org/?probe=cd89c5b708) | May 06, 2023 |
| Gigabyte      | P75-D3                      | [4f6987c722](https://linux-hardware.org/?probe=4f6987c722) | Apr 30, 2023 |
| Biostar       | H110MHV3                    | [95b25ba480](https://linux-hardware.org/?probe=95b25ba480) | Apr 29, 2023 |
| MSI           | H81M-P33                    | [2099cafe74](https://linux-hardware.org/?probe=2099cafe74) | Apr 27, 2023 |
| ASUSTek       | P5GC-VM/SI                  | [abf277ec59](https://linux-hardware.org/?probe=abf277ec59) | Apr 27, 2023 |
| ASRock        | G31M-S                      | [7c2bfcaeca](https://linux-hardware.org/?probe=7c2bfcaeca) | Apr 20, 2023 |
| Acer          | FQ965M MP                   | [9be9793747](https://linux-hardware.org/?probe=9be9793747) | Apr 18, 2023 |
| Gigabyte      | H55M-S2H                    | [f44b68cf93](https://linux-hardware.org/?probe=f44b68cf93) | Apr 16, 2023 |
| Intel         | DH67BL AAG10189-209         | [b8e206486d](https://linux-hardware.org/?probe=b8e206486d) | Apr 13, 2023 |
| HP            | 339A                        | [877e64e105](https://linux-hardware.org/?probe=877e64e105) | Apr 11, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [ef5829077e](https://linux-hardware.org/?probe=ef5829077e) | Apr 11, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [e0e2242a64](https://linux-hardware.org/?probe=e0e2242a64) | Apr 11, 2023 |
| HP            | 339A                        | [eb409991d2](https://linux-hardware.org/?probe=eb409991d2) | Apr 09, 2023 |
| HP            | 2AA2                        | [28c42fc95f](https://linux-hardware.org/?probe=28c42fc95f) | Apr 05, 2023 |
| ASUSTek       | P7P55D                      | [b50f27ad05](https://linux-hardware.org/?probe=b50f27ad05) | Mar 31, 2023 |
| ASUSTek       | P5GC-VM/SI                  | [b53d1202dc](https://linux-hardware.org/?probe=b53d1202dc) | Mar 28, 2023 |
| ASUSTek       | P5GC-VM/SI                  | [e5cef530ff](https://linux-hardware.org/?probe=e5cef530ff) | Mar 27, 2023 |
| Lenovo        | SHARKBAY No DPK             | [2941abc936](https://linux-hardware.org/?probe=2941abc936) | Mar 25, 2023 |
| HP            | 1495                        | [3fe89757bb](https://linux-hardware.org/?probe=3fe89757bb) | Mar 21, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [662d96a2ed](https://linux-hardware.org/?probe=662d96a2ed) | Mar 20, 2023 |
| ASUSTek       | PRIME B660M-K D4            | [77b68431f7](https://linux-hardware.org/?probe=77b68431f7) | Mar 14, 2023 |
| Gigabyte      | Z370 HD3-CF                 | [b53c65e6c9](https://linux-hardware.org/?probe=b53c65e6c9) | Mar 10, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [82551d929c](https://linux-hardware.org/?probe=82551d929c) | Mar 09, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [4f64764c75](https://linux-hardware.org/?probe=4f64764c75) | Mar 08, 2023 |
| ASUSTek       | TUF Gaming H470-PRO         | [769cd87ebd](https://linux-hardware.org/?probe=769cd87ebd) | Mar 07, 2023 |
| ASUSTek       | TUF Gaming H470-PRO         | [e1846f2a68](https://linux-hardware.org/?probe=e1846f2a68) | Mar 07, 2023 |
| Gigabyte      | H61M-S2P-B3                 | [83c569f727](https://linux-hardware.org/?probe=83c569f727) | Mar 06, 2023 |
| Gigabyte      | H61M-S2P-B3                 | [ca3531a813](https://linux-hardware.org/?probe=ca3531a813) | Mar 06, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [c2d6b5218e](https://linux-hardware.org/?probe=c2d6b5218e) | Mar 03, 2023 |
| ASUSTek       | P8H61-M LX                  | [01f7386d8c](https://linux-hardware.org/?probe=01f7386d8c) | Mar 02, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [f942bae731](https://linux-hardware.org/?probe=f942bae731) | Mar 02, 2023 |
| HP            | 1497                        | [c74b2b540e](https://linux-hardware.org/?probe=c74b2b540e) | Mar 02, 2023 |
| HP            | 805D                        | [4638c85566](https://linux-hardware.org/?probe=4638c85566) | Mar 01, 2023 |
| Biostar       | H81MLV3                     | [ccba1a8217](https://linux-hardware.org/?probe=ccba1a8217) | Feb 28, 2023 |
| MSI           | B450M MORTAR MAX            | [0335729036](https://linux-hardware.org/?probe=0335729036) | Feb 27, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [186b84313d](https://linux-hardware.org/?probe=186b84313d) | Feb 22, 2023 |
| ASUSTek       | PRIME X470-PRO              | [586653a4a6](https://linux-hardware.org/?probe=586653a4a6) | Feb 18, 2023 |
| ASUSTek       | P7P55D                      | [bcae3260be](https://linux-hardware.org/?probe=bcae3260be) | Feb 17, 2023 |
| Gigabyte      | 945GZM-S2                   | [8cd6645d36](https://linux-hardware.org/?probe=8cd6645d36) | Feb 16, 2023 |
| Biostar       | H61MHB                      | [c8d5686c80](https://linux-hardware.org/?probe=c8d5686c80) | Feb 15, 2023 |
| Biostar       | H61MHB                      | [565eeeb040](https://linux-hardware.org/?probe=565eeeb040) | Feb 15, 2023 |
| Gigabyte      | 945GZM-S2                   | [e271dc0c66](https://linux-hardware.org/?probe=e271dc0c66) | Feb 14, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [cbf6311f2c](https://linux-hardware.org/?probe=cbf6311f2c) | Feb 12, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [a545753206](https://linux-hardware.org/?probe=a545753206) | Feb 10, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [c7de2e3ca2](https://linux-hardware.org/?probe=c7de2e3ca2) | Feb 10, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [47c66d7783](https://linux-hardware.org/?probe=47c66d7783) | Feb 08, 2023 |
| ASUSTek       | P5G41T-M LX                 | [62882a0c3e](https://linux-hardware.org/?probe=62882a0c3e) | Feb 03, 2023 |
| Gigabyte      | G31M-ES2C                   | [135dcf2c12](https://linux-hardware.org/?probe=135dcf2c12) | Feb 02, 2023 |
| Gigabyte      | G31M-ES2C                   | [ec3d16bb4e](https://linux-hardware.org/?probe=ec3d16bb4e) | Feb 01, 2023 |
| Foxconn       | G41MXE/G41MXE-K             | [50c552026e](https://linux-hardware.org/?probe=50c552026e) | Feb 01, 2023 |
| ASUSTek       | P7P55D                      | [981ae95b2a](https://linux-hardware.org/?probe=981ae95b2a) | Jan 31, 2023 |
| Gigabyte      | G31M-ES2C                   | [8a5dee0d52](https://linux-hardware.org/?probe=8a5dee0d52) | Jan 27, 2023 |
| Gigabyte      | G31M-ES2C                   | [c49f3c0e92](https://linux-hardware.org/?probe=c49f3c0e92) | Jan 24, 2023 |
| Gigabyte      | G31M-ES2C                   | [0cff571f25](https://linux-hardware.org/?probe=0cff571f25) | Jan 24, 2023 |
| Gigabyte      | G31M-ES2C                   | [eac6804cbb](https://linux-hardware.org/?probe=eac6804cbb) | Jan 24, 2023 |
| ASRock        | G31M-S                      | [50bc0b52b3](https://linux-hardware.org/?probe=50bc0b52b3) | Jan 18, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [4589a3ea25](https://linux-hardware.org/?probe=4589a3ea25) | Jan 17, 2023 |
| ASUSTek       | PRIME Z690-A                | [d6e6c13962](https://linux-hardware.org/?probe=d6e6c13962) | Jan 08, 2023 |
| Gigabyte      | G31M-ES2C                   | [7076e737af](https://linux-hardware.org/?probe=7076e737af) | Jan 04, 2023 |
| MSI           | H81M-P33                    | [041ee2fde1](https://linux-hardware.org/?probe=041ee2fde1) | Jan 03, 2023 |
| HP            | ProLiant MicroServer        | [03b6f5a97d](https://linux-hardware.org/?probe=03b6f5a97d) | Dec 30, 2022 |
| MSI           | X570-A PRO                  | [7af9125172](https://linux-hardware.org/?probe=7af9125172) | Dec 29, 2022 |
| Gigabyte      | Z370 HD3-CF                 | [ac6571db76](https://linux-hardware.org/?probe=ac6571db76) | Dec 27, 2022 |
| Gigabyte      | H61M-S2PV                   | [4403153e04](https://linux-hardware.org/?probe=4403153e04) | Dec 27, 2022 |
| HP            | 1495                        | [b8e1dc67eb](https://linux-hardware.org/?probe=b8e1dc67eb) | Dec 26, 2022 |
| ASRock        | G31M-S                      | [476c5ec563](https://linux-hardware.org/?probe=476c5ec563) | Dec 22, 2022 |
| ASRock        | G31M-S                      | [88d93da5a7](https://linux-hardware.org/?probe=88d93da5a7) | Dec 22, 2022 |
| Gigabyte      | G31M-ES2C                   | [5de13fdffa](https://linux-hardware.org/?probe=5de13fdffa) | Dec 19, 2022 |
| Gigabyte      | G31M-ES2C                   | [98fe52d91e](https://linux-hardware.org/?probe=98fe52d91e) | Dec 17, 2022 |
| MSI           | PRO B660M-E DDR4            | [3f4e01746b](https://linux-hardware.org/?probe=3f4e01746b) | Dec 17, 2022 |
| IBM           | M97IP SIT                   | [c4041b26f3](https://linux-hardware.org/?probe=c4041b26f3) | Dec 11, 2022 |
| Gigabyte      | X58A-UD3R                   | [969406ce12](https://linux-hardware.org/?probe=969406ce12) | Dec 08, 2022 |
| ASUSTek       | P7P55D                      | [a1d27bfc48](https://linux-hardware.org/?probe=a1d27bfc48) | Dec 04, 2022 |
| HP            | 0B4Ch D                     | [07aa2d3665](https://linux-hardware.org/?probe=07aa2d3665) | Dec 02, 2022 |
| Gigabyte      | Z370 HD3-CF                 | [ece7618688](https://linux-hardware.org/?probe=ece7618688) | Nov 30, 2022 |
| Dell          | 0Y7WYT A00                  | [c0e4685d23](https://linux-hardware.org/?probe=c0e4685d23) | Nov 30, 2022 |
| MSI           | H510M-A PRO                 | [cbae74a53a](https://linux-hardware.org/?probe=cbae74a53a) | Nov 29, 2022 |
| Foxconn       | G41MXE/G41MXE-K             | [4f13d9a2cc](https://linux-hardware.org/?probe=4f13d9a2cc) | Nov 29, 2022 |
| MSI           | H410M-A PRO                 | [36716fb1f4](https://linux-hardware.org/?probe=36716fb1f4) | Nov 17, 2022 |
| Lenovo        | ThinkCentre M90p 5498R97    | [8104152607](https://linux-hardware.org/?probe=8104152607) | Nov 13, 2022 |
| Intel         | DG41WV AAE90316-102         | [7af4696c1b](https://linux-hardware.org/?probe=7af4696c1b) | Nov 12, 2022 |
| Lenovo        | ThinkCentre M90p 5498R97    | [29c3e37808](https://linux-hardware.org/?probe=29c3e37808) | Nov 06, 2022 |
| Lenovo        | ThinkCentre M90p 5498R97    | [cd2a716a60](https://linux-hardware.org/?probe=cd2a716a60) | Nov 06, 2022 |
| MSI           | H170 GAMING M3              | [b65108d66e](https://linux-hardware.org/?probe=b65108d66e) | Nov 04, 2022 |
| Gigabyte      | Z370 HD3-CF                 | [06cb3f01ba](https://linux-hardware.org/?probe=06cb3f01ba) | Oct 29, 2022 |
| Gigabyte      | X58A-UD3R                   | [560f96a33a](https://linux-hardware.org/?probe=560f96a33a) | Oct 28, 2022 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | [c3b1784ecc](https://linux-hardware.org/?probe=c3b1784ecc) | Oct 21, 2022 |
| HP            | 339A                        | [e168e3b75b](https://linux-hardware.org/?probe=e168e3b75b) | Oct 18, 2022 |
| Foxconn       | H61MXT1/F2/-S/-V            | [a5a47837e5](https://linux-hardware.org/?probe=a5a47837e5) | Oct 15, 2022 |
| Foxconn       | H61MXT1/F2/-S/-V            | [614d4b0dc3](https://linux-hardware.org/?probe=614d4b0dc3) | Oct 15, 2022 |
| HP            | 1495                        | [7125a7b95b](https://linux-hardware.org/?probe=7125a7b95b) | Oct 11, 2022 |
| Gigabyte      | X58A-UD3R                   | [22b023a49f](https://linux-hardware.org/?probe=22b023a49f) | Oct 10, 2022 |
| HP            | 1495                        | [bf20b30af3](https://linux-hardware.org/?probe=bf20b30af3) | Oct 08, 2022 |
| HP            | 1589                        | [d50afd3db1](https://linux-hardware.org/?probe=d50afd3db1) | Oct 08, 2022 |
| HP            | 0B4Ch D                     | [b95ff9d622](https://linux-hardware.org/?probe=b95ff9d622) | Oct 02, 2022 |
| ASUSTek       | P8H67-M                     | [583fe6d90d](https://linux-hardware.org/?probe=583fe6d90d) | Sep 30, 2022 |
| Gigabyte      | B560M DS3H V2               | [0612f13b64](https://linux-hardware.org/?probe=0612f13b64) | Sep 06, 2022 |
| Supermicro    | X9SCL/X9SCMA                | [fa0d296a6d](https://linux-hardware.org/?probe=fa0d296a6d) | Sep 01, 2022 |
| Gigabyte      | H97M-D3H                    | [a8100fcf41](https://linux-hardware.org/?probe=a8100fcf41) | Aug 29, 2022 |
| Gigabyte      | H97M-D3H                    | [f8f42b0857](https://linux-hardware.org/?probe=f8f42b0857) | Aug 29, 2022 |
| Lenovo        | ThinkCentre M58p 6234CL2    | [14449a705a](https://linux-hardware.org/?probe=14449a705a) | Aug 29, 2022 |
| Intel         | DQ965GF AAD41676-601        | [a163a7fc6d](https://linux-hardware.org/?probe=a163a7fc6d) | Aug 25, 2022 |
| Dell          | 0YXT71 A03                  | [176c458f3a](https://linux-hardware.org/?probe=176c458f3a) | Aug 25, 2022 |
| Gigabyte      | G41MT-S2                    | [42cd205688](https://linux-hardware.org/?probe=42cd205688) | Aug 25, 2022 |
| MSI           | Z370 TOMAHAWK               | [251d227686](https://linux-hardware.org/?probe=251d227686) | Aug 22, 2022 |
| MSI           | MS-7528                     | [723f567e19](https://linux-hardware.org/?probe=723f567e19) | Aug 19, 2022 |
| MSI           | MS-7528                     | [4d549f68ce](https://linux-hardware.org/?probe=4d549f68ce) | Aug 19, 2022 |
| HP            | 1497                        | [c0b6759020](https://linux-hardware.org/?probe=c0b6759020) | Aug 16, 2022 |
| Foxconn       | 45GM/45CM/45CM-S            | [a6b418356a](https://linux-hardware.org/?probe=a6b418356a) | Aug 11, 2022 |
| ASRock        | X570 Steel Legend           | [42f35776a6](https://linux-hardware.org/?probe=42f35776a6) | Aug 10, 2022 |
| Intel         | DP35DP AAD81073-207         | [3f55eb1ae4](https://linux-hardware.org/?probe=3f55eb1ae4) | Aug 10, 2022 |
| MSI           | H81M-P33                    | [f79c49386d](https://linux-hardware.org/?probe=f79c49386d) | Aug 08, 2022 |
| Foxconn       | 45GM/45CM/45CM-S            | [3d64e8f950](https://linux-hardware.org/?probe=3d64e8f950) | Aug 04, 2022 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | [85ae8afd7d](https://linux-hardware.org/?probe=85ae8afd7d) | Jul 21, 2022 |
| Acer          | Veriton M290                | [647393aa0c](https://linux-hardware.org/?probe=647393aa0c) | Jul 20, 2022 |
| Intel         | D946GZIS AAD66165-301       | [3d3076977a](https://linux-hardware.org/?probe=3d3076977a) | Jul 12, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [320a4240ce](https://linux-hardware.org/?probe=320a4240ce) | Jul 12, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | [d6531258d0](https://linux-hardware.org/?probe=d6531258d0) | Jul 11, 2022 |
| Gigabyte      | Z270-Gaming K3              | [25b5baa226](https://linux-hardware.org/?probe=25b5baa226) | Jul 10, 2022 |
| Gigabyte      | G41MT-S2PT                  | [48a83358b5](https://linux-hardware.org/?probe=48a83358b5) | Jul 06, 2022 |
| MSI           | H61M-P31/W8                 | [ae5c00cbd0](https://linux-hardware.org/?probe=ae5c00cbd0) | Jul 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [31a8bd72d6](https://linux-hardware.org/?probe=31a8bd72d6) | Jul 02, 2022 |
| MSI           | A320M PRO-M2 V2             | [a801c7c2ba](https://linux-hardware.org/?probe=a801c7c2ba) | Jun 27, 2022 |
| Foxconn       | G31MXP/G31MXP-K FAB:1.0     | [1faf7dc08f](https://linux-hardware.org/?probe=1faf7dc08f) | Jun 25, 2022 |
| Foxconn       | G31MXP/G31MXP-K FAB:1.0     | [87e5572caa](https://linux-hardware.org/?probe=87e5572caa) | Jun 24, 2022 |
| Intel         | DH77KC AAG39641-401         | [3d2faf0e14](https://linux-hardware.org/?probe=3d2faf0e14) | Jun 19, 2022 |
| Biostar       | H81MLV3                     | [d24427bbc8](https://linux-hardware.org/?probe=d24427bbc8) | Jun 18, 2022 |
| ASUSTek       | PRIME X570-P                | [4dc736e2b5](https://linux-hardware.org/?probe=4dc736e2b5) | Jun 16, 2022 |
| Nvidia        | MCP73                       | [4af86ef214](https://linux-hardware.org/?probe=4af86ef214) | Jun 15, 2022 |
| Nvidia        | MCP73                       | [bc4b2de5bc](https://linux-hardware.org/?probe=bc4b2de5bc) | Jun 15, 2022 |
| Supermicro    | X8STi                       | [d99d775afe](https://linux-hardware.org/?probe=d99d775afe) | Jun 12, 2022 |
| Intel         | DQ965GF AAD41676-601        | [13eadd3c2f](https://linux-hardware.org/?probe=13eadd3c2f) | Jun 10, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [9bc79127f3](https://linux-hardware.org/?probe=9bc79127f3) | Jun 06, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [ee38b0dd57](https://linux-hardware.org/?probe=ee38b0dd57) | Jun 02, 2022 |
| Intel         | DH55TC AAE70932-206         | [923699ceec](https://linux-hardware.org/?probe=923699ceec) | Jun 01, 2022 |
| Gigabyte      | B150M-D3H-CF                | [e5fdf1083f](https://linux-hardware.org/?probe=e5fdf1083f) | May 28, 2022 |
| Dell          | 040DDP A01                  | [925d3dce8d](https://linux-hardware.org/?probe=925d3dce8d) | May 28, 2022 |
| ASUSTek       | STRIKER II FORMULA          | [f10aecd449](https://linux-hardware.org/?probe=f10aecd449) | May 27, 2022 |
| ASUSTek       | STRIKER II FORMULA          | [df37e5c694](https://linux-hardware.org/?probe=df37e5c694) | May 27, 2022 |
| Mustek6376... | 945GZT-M ECS                | [0d5f40920b](https://linux-hardware.org/?probe=0d5f40920b) | May 14, 2022 |
| MSI           | H110M PRO-VD                | [f43f2e2bee](https://linux-hardware.org/?probe=f43f2e2bee) | May 10, 2022 |
| MSI           | H110M PRO-VD                | [3d0c46dc84](https://linux-hardware.org/?probe=3d0c46dc84) | May 10, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | [76cc09b228](https://linux-hardware.org/?probe=76cc09b228) | May 10, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | [6500cb78c3](https://linux-hardware.org/?probe=6500cb78c3) | May 10, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [473e906b63](https://linux-hardware.org/?probe=473e906b63) | May 03, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [9176b48887](https://linux-hardware.org/?probe=9176b48887) | May 03, 2022 |
| MSI           | B450M BAZOOKA PLUS          | [edc5f16866](https://linux-hardware.org/?probe=edc5f16866) | May 03, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [dec71580c4](https://linux-hardware.org/?probe=dec71580c4) | May 01, 2022 |
| Lenovo        | Win8 Pro DPK TPG            | [9b78e9af72](https://linux-hardware.org/?probe=9b78e9af72) | Apr 29, 2022 |
| Dell          | 040DDP A01                  | [6e37f18366](https://linux-hardware.org/?probe=6e37f18366) | Apr 21, 2022 |
| MSI           | B450M PRO-M2 MAX            | [4702e93a67](https://linux-hardware.org/?probe=4702e93a67) | Apr 16, 2022 |
| MSI           | X370 KRAIT GAMING           | [26be53ebd1](https://linux-hardware.org/?probe=26be53ebd1) | Apr 14, 2022 |
| MSI           | B450M PRO-M2 MAX            | [0fc2a352ab](https://linux-hardware.org/?probe=0fc2a352ab) | Apr 13, 2022 |
| Gigabyte      | H61M-DS2                    | [af56c63db4](https://linux-hardware.org/?probe=af56c63db4) | Apr 12, 2022 |
| Gigabyte      | B150M-D3H-CF                | [1aee3c0b22](https://linux-hardware.org/?probe=1aee3c0b22) | Apr 12, 2022 |
| NCR           | Pocono BIOS.5.1             | [ca175e1f0c](https://linux-hardware.org/?probe=ca175e1f0c) | Apr 09, 2022 |
| Intel         | DQ965GF AAD41676-601        | [61fca7acbc](https://linux-hardware.org/?probe=61fca7acbc) | Apr 07, 2022 |
| MSI           | X58M                        | [d4146d0724](https://linux-hardware.org/?probe=d4146d0724) | Apr 05, 2022 |
| Foxconn       | 2A8Ch                       | [6354cfe078](https://linux-hardware.org/?probe=6354cfe078) | Apr 04, 2022 |
| Dell          | 0FPP7F A00                  | [8e8bee474f](https://linux-hardware.org/?probe=8e8bee474f) | Apr 03, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [2a333a0767](https://linux-hardware.org/?probe=2a333a0767) | Mar 25, 2022 |
| Gigabyte      | H67MA-USB3-B3               | [c5ad9a2c99](https://linux-hardware.org/?probe=c5ad9a2c99) | Mar 24, 2022 |
| Biostar       | G41D3+                      | [8d6a4e54b1](https://linux-hardware.org/?probe=8d6a4e54b1) | Mar 20, 2022 |
| Biostar       | Hi-Fi H61S3                 | [469edf935f](https://linux-hardware.org/?probe=469edf935f) | Mar 14, 2022 |
| Foxconn       | H61MXE/-S/-V/-K             | [8aa740825f](https://linux-hardware.org/?probe=8aa740825f) | Mar 06, 2022 |
| MSI           | Z170A TOMAHAWK              | [e2956753b7](https://linux-hardware.org/?probe=e2956753b7) | Mar 02, 2022 |
| MSI           | Z170A TOMAHAWK              | [ccf1a5fa76](https://linux-hardware.org/?probe=ccf1a5fa76) | Mar 02, 2022 |
| HP            | 1494                        | [f2b67d46d0](https://linux-hardware.org/?probe=f2b67d46d0) | Feb 19, 2022 |
| Gigabyte      | B75M-D3H                    | [469ab361d5](https://linux-hardware.org/?probe=469ab361d5) | Feb 13, 2022 |
| Gigabyte      | B75M-D3H                    | [0d9d3a0b9b](https://linux-hardware.org/?probe=0d9d3a0b9b) | Feb 12, 2022 |
| MSI           | B360-A PRO                  | [1447e1f0e6](https://linux-hardware.org/?probe=1447e1f0e6) | Feb 11, 2022 |
| MSI           | A320M PRO-VD PLUS           | [078b45782e](https://linux-hardware.org/?probe=078b45782e) | Feb 11, 2022 |
| HP            | 1497                        | [3781103124](https://linux-hardware.org/?probe=3781103124) | Feb 09, 2022 |
| ASUSTek       | PRIME B550M-K               | [b4fe3a7a24](https://linux-hardware.org/?probe=b4fe3a7a24) | Feb 07, 2022 |
| MSI           | Z77A-G45                    | [ff87ac3184](https://linux-hardware.org/?probe=ff87ac3184) | Feb 07, 2022 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | [e514d0d302](https://linux-hardware.org/?probe=e514d0d302) | Feb 03, 2022 |
| Intel         | DH55TC AAE70932-302         | [d66879ebac](https://linux-hardware.org/?probe=d66879ebac) | Jan 27, 2022 |
| Intel         | H81                         | [1f7ff2e980](https://linux-hardware.org/?probe=1f7ff2e980) | Jan 26, 2022 |
| Dell          | 0Y7WYT A00                  | [80295dd814](https://linux-hardware.org/?probe=80295dd814) | Jan 26, 2022 |
| MSI           | B550-A PRO                  | [72d6b552aa](https://linux-hardware.org/?probe=72d6b552aa) | Jan 17, 2022 |
| ECS           | G31T-M7                     | [12ad49d909](https://linux-hardware.org/?probe=12ad49d909) | Jan 16, 2022 |
| ECS           | G31T-M7                     | [5c10976292](https://linux-hardware.org/?probe=5c10976292) | Jan 16, 2022 |
| MSI           | B450M PRO-M2 MAX            | [32cae94f00](https://linux-hardware.org/?probe=32cae94f00) | Jan 06, 2022 |
| MSI           | B450M PRO-M2 MAX            | [c103969fdf](https://linux-hardware.org/?probe=c103969fdf) | Jan 06, 2022 |
| Biostar       | Hi-Fi H61S3                 | [6d68cbf5a2](https://linux-hardware.org/?probe=6d68cbf5a2) | Dec 31, 2021 |
| ASRock        | B85M-HDS                    | [8806a9db07](https://linux-hardware.org/?probe=8806a9db07) | Dec 29, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | [783618fe4b](https://linux-hardware.org/?probe=783618fe4b) | Dec 23, 2021 |
| HP            | 0A58h                       | [2fce860bda](https://linux-hardware.org/?probe=2fce860bda) | Dec 19, 2021 |
| Unknown       | C51GM-M                     | [91386c4f7c](https://linux-hardware.org/?probe=91386c4f7c) | Dec 17, 2021 |
| Unknown       | C51GM-M                     | [cd4d96fefa](https://linux-hardware.org/?probe=cd4d96fefa) | Dec 17, 2021 |
| Biostar       | Hi-Fi H61S3                 | [e1362b0ad2](https://linux-hardware.org/?probe=e1362b0ad2) | Dec 14, 2021 |
| ASRock        | AB350 Pro4                  | [ebf80cd948](https://linux-hardware.org/?probe=ebf80cd948) | Dec 13, 2021 |
| MSI           | H61M-P31                    | [58651bba67](https://linux-hardware.org/?probe=58651bba67) | Dec 07, 2021 |
| ASUSTek       | H87M-E                      | [2b4abcf54f](https://linux-hardware.org/?probe=2b4abcf54f) | Dec 02, 2021 |
| ASUSTek       | H87M-E                      | [72cf0ed74d](https://linux-hardware.org/?probe=72cf0ed74d) | Dec 02, 2021 |
| Gigabyte      | XP-M5S661GX                 | [c452e6bdf7](https://linux-hardware.org/?probe=c452e6bdf7) | Nov 27, 2021 |
| HP            | 1497                        | [9a7d6ebc52](https://linux-hardware.org/?probe=9a7d6ebc52) | Nov 26, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [7d4b6453e9](https://linux-hardware.org/?probe=7d4b6453e9) | Nov 24, 2021 |
| MSI           | B450M MORTAR TITANIUM       | [ce783dccca](https://linux-hardware.org/?probe=ce783dccca) | Nov 24, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [e9b4b7ecba](https://linux-hardware.org/?probe=e9b4b7ecba) | Nov 24, 2021 |
| Intel         | DB65AL AAG12530-309         | [44c8025eee](https://linux-hardware.org/?probe=44c8025eee) | Nov 23, 2021 |
| Dell          | 0M9KCM A00                  | [e0f0471cee](https://linux-hardware.org/?probe=e0f0471cee) | Nov 20, 2021 |
| Gigabyte      | Z77-DS3H                    | [e8ef916c87](https://linux-hardware.org/?probe=e8ef916c87) | Nov 18, 2021 |
| MSI           | 970 GAMING                  | [1515779722](https://linux-hardware.org/?probe=1515779722) | Nov 15, 2021 |
| MSI           | 970 GAMING                  | [b74fb29b9b](https://linux-hardware.org/?probe=b74fb29b9b) | Nov 15, 2021 |
| Gigabyte      | H61M-S2PV                   | [c62a6022e8](https://linux-hardware.org/?probe=c62a6022e8) | Nov 14, 2021 |
| ASUSTek       | P8P67-M                     | [1cb5f14632](https://linux-hardware.org/?probe=1cb5f14632) | Nov 13, 2021 |
| Foxconn       | G41MXE/G41MXE-K             | [b7579cb355](https://linux-hardware.org/?probe=b7579cb355) | Nov 12, 2021 |
| Foxconn       | G41MXE/G41MXE-K             | [39e3c646ff](https://linux-hardware.org/?probe=39e3c646ff) | Nov 11, 2021 |
| ASUSTek       | P8P67-M                     | [701e60decc](https://linux-hardware.org/?probe=701e60decc) | Nov 11, 2021 |
| Lenovo        | MAHOBAY NOK                 | [62ba7df7ec](https://linux-hardware.org/?probe=62ba7df7ec) | Nov 11, 2021 |
| HP            | ProLiant MicroServer        | [383b7f1862](https://linux-hardware.org/?probe=383b7f1862) | Nov 11, 2021 |
| MSI           | H110M PRO-VH PLUS           | [02f1a55757](https://linux-hardware.org/?probe=02f1a55757) | Nov 08, 2021 |
| NCR           | Pocono BIOS.3.1             | [985620ce15](https://linux-hardware.org/?probe=985620ce15) | Nov 07, 2021 |
| MSI           | H110M PRO-VH PLUS           | [57417d57e3](https://linux-hardware.org/?probe=57417d57e3) | Nov 06, 2021 |
| HP            | 0B4Ch D                     | [f51fee36d1](https://linux-hardware.org/?probe=f51fee36d1) | Nov 04, 2021 |
| Gigabyte      | B150M-D3H-CF                | [dd22d96d07](https://linux-hardware.org/?probe=dd22d96d07) | Oct 30, 2021 |
| Biostar       | B350GTN                     | [53c5fd6db4](https://linux-hardware.org/?probe=53c5fd6db4) | Oct 26, 2021 |
| Gigabyte      | H61M-S2PV                   | [37ae9a9258](https://linux-hardware.org/?probe=37ae9a9258) | Oct 23, 2021 |
| Lenovo        | ThinkCentre M91p 4512A12    | [1ecb7a6910](https://linux-hardware.org/?probe=1ecb7a6910) | Oct 19, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | [fcc82222d9](https://linux-hardware.org/?probe=fcc82222d9) | Oct 17, 2021 |
| Dell          | 0M9KCM A00                  | [d837406f2a](https://linux-hardware.org/?probe=d837406f2a) | Oct 16, 2021 |
| NCR           | Pocono BIOS.3.1             | [53cafab8f3](https://linux-hardware.org/?probe=53cafab8f3) | Oct 15, 2021 |
| HP            | 81C3                        | [df2caaf484](https://linux-hardware.org/?probe=df2caaf484) | Oct 11, 2021 |
| MSI           | Z170A TOMAHAWK              | [e39ce9ade6](https://linux-hardware.org/?probe=e39ce9ade6) | Oct 09, 2021 |
| MSI           | Z170A TOMAHAWK              | [5a5c0c8f90](https://linux-hardware.org/?probe=5a5c0c8f90) | Oct 07, 2021 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | [42a76fbc95](https://linux-hardware.org/?probe=42a76fbc95) | Oct 05, 2021 |
| Nvidia        | MCP73                       | [7099e6ef4b](https://linux-hardware.org/?probe=7099e6ef4b) | Oct 02, 2021 |
| ASRock        | B550M Steel Legend          | [6b9d5f5444](https://linux-hardware.org/?probe=6b9d5f5444) | Oct 02, 2021 |
| Gigabyte      | B150M-D3H-CF                | [8fe1edb38b](https://linux-hardware.org/?probe=8fe1edb38b) | Sep 30, 2021 |
| HP            | 1497                        | [a792022089](https://linux-hardware.org/?probe=a792022089) | Sep 30, 2021 |
| Gigabyte      | G31M-S2L                    | [3255b4d143](https://linux-hardware.org/?probe=3255b4d143) | Sep 28, 2021 |
| Intel         | DQ77CP AAG67261-300         | [2da6abda17](https://linux-hardware.org/?probe=2da6abda17) | Sep 25, 2021 |
| Gigabyte      | H55M-S2H                    | [82fe8d569f](https://linux-hardware.org/?probe=82fe8d569f) | Sep 11, 2021 |
| MSI           | B450M MORTAR MAX            | [f40c6b596c](https://linux-hardware.org/?probe=f40c6b596c) | Sep 08, 2021 |
| MSI           | B450M MORTAR MAX            | [17c58396b6](https://linux-hardware.org/?probe=17c58396b6) | Sep 08, 2021 |
| MSI           | B450M MORTAR MAX            | [dfe73847d3](https://linux-hardware.org/?probe=dfe73847d3) | Sep 08, 2021 |
| MSI           | Z170A PC MATE               | [192a0d3f1a](https://linux-hardware.org/?probe=192a0d3f1a) | Sep 07, 2021 |
| Dell          | 0GM819                      | [f0cc146236](https://linux-hardware.org/?probe=f0cc146236) | Sep 04, 2021 |
| Intel         | D865GLC AAC28906-407        | [5936f5b3ba](https://linux-hardware.org/?probe=5936f5b3ba) | Sep 01, 2021 |
| Intel         | DH55HC AAE70933-504         | [2880661f42](https://linux-hardware.org/?probe=2880661f42) | Aug 30, 2021 |
| Gigabyte      | G33M-DS2R                   | [0b340c6818](https://linux-hardware.org/?probe=0b340c6818) | Aug 29, 2021 |
| HP            | 212B                        | [10646959ce](https://linux-hardware.org/?probe=10646959ce) | Aug 27, 2021 |
| Biostar       | H61MGV3                     | [fa2b470ff5](https://linux-hardware.org/?probe=fa2b470ff5) | Aug 26, 2021 |
| Biostar       | H61MGV3                     | [19eacc88f5](https://linux-hardware.org/?probe=19eacc88f5) | Aug 26, 2021 |
| ASUSTek       | P8Z77-V LX                  | [314859d762](https://linux-hardware.org/?probe=314859d762) | Aug 25, 2021 |
| ASUSTek       | P8Z77-V LX                  | [faaf8bc158](https://linux-hardware.org/?probe=faaf8bc158) | Aug 25, 2021 |
| Dell          | 0HH807                      | [fe3659d065](https://linux-hardware.org/?probe=fe3659d065) | Aug 24, 2021 |
| MSI           | B450M PRO-M2 MAX            | [b28b036f78](https://linux-hardware.org/?probe=b28b036f78) | Aug 22, 2021 |
| HP            | 0A50h                       | [f7ea4959d2](https://linux-hardware.org/?probe=f7ea4959d2) | Aug 21, 2021 |
| MSI           | G41M4                       | [c5c2a6945a](https://linux-hardware.org/?probe=c5c2a6945a) | Aug 20, 2021 |
| MSI           | G41M4                       | [3862c2333b](https://linux-hardware.org/?probe=3862c2333b) | Aug 20, 2021 |
| Intel         | DH61WW AAG23116-300         | [0a023d2778](https://linux-hardware.org/?probe=0a023d2778) | Aug 17, 2021 |
| MSI           | 970A-G46                    | [1d552fc481](https://linux-hardware.org/?probe=1d552fc481) | Aug 14, 2021 |
| MSI           | 970A-G46                    | [ee8d3d8ed0](https://linux-hardware.org/?probe=ee8d3d8ed0) | Aug 14, 2021 |
| HP            | 3031h                       | [201543483c](https://linux-hardware.org/?probe=201543483c) | Aug 13, 2021 |
| ASUSTek       | Rampage II GENE             | [ec056ad7c5](https://linux-hardware.org/?probe=ec056ad7c5) | Aug 12, 2021 |
| Intel         | DH61WW AAG23116-300         | [95ed07c904](https://linux-hardware.org/?probe=95ed07c904) | Aug 05, 2021 |
| Gigabyte      | G41MT-S2PT                  | [cf42c809f2](https://linux-hardware.org/?probe=cf42c809f2) | Aug 04, 2021 |
| MSI           | G31M3-F V2                  | [8f821ac3a7](https://linux-hardware.org/?probe=8f821ac3a7) | Aug 02, 2021 |
| Intel         | DH61WW AAG23116-300         | [886881e04d](https://linux-hardware.org/?probe=886881e04d) | Aug 01, 2021 |
| Dell          | 096JG8 A01                  | [b45d7e4f99](https://linux-hardware.org/?probe=b45d7e4f99) | Jul 29, 2021 |
| Dell          | 096JG8 A01                  | [290acd3514](https://linux-hardware.org/?probe=290acd3514) | Jul 28, 2021 |
| Intel         | DH55HC AAE70933-504         | [f3a838da1b](https://linux-hardware.org/?probe=f3a838da1b) | Jul 28, 2021 |
| MSI           | 990FXA-GD65                 | [6fe8efac3a](https://linux-hardware.org/?probe=6fe8efac3a) | Jul 25, 2021 |
| Gigabyte      | G41MT-S2PT                  | [7e37603df2](https://linux-hardware.org/?probe=7e37603df2) | Jul 23, 2021 |
| Intel         | DH61WW AAG23116-300         | [fd7862ecd9](https://linux-hardware.org/?probe=fd7862ecd9) | Jul 23, 2021 |
| HP            | 1494                        | [fe57b848c7](https://linux-hardware.org/?probe=fe57b848c7) | Jul 22, 2021 |
| Intel         | DP35DP AAD81073-207         | [7ff35da9be](https://linux-hardware.org/?probe=7ff35da9be) | Jul 22, 2021 |
| Intel         | DP35DP AAD81073-207         | [179a2a6dbb](https://linux-hardware.org/?probe=179a2a6dbb) | Jul 21, 2021 |
| Intel         | DP35DP AAD81073-207         | [9ab1130986](https://linux-hardware.org/?probe=9ab1130986) | Jul 21, 2021 |
| HP            | 1494                        | [2c30dc2cf3](https://linux-hardware.org/?probe=2c30dc2cf3) | Jul 19, 2021 |
| MSI           | TRX40 PRO 10G               | [a06646b4da](https://linux-hardware.org/?probe=a06646b4da) | Jul 19, 2021 |
| Intel         | DH61WW AAG23116-300         | [455abdf0c3](https://linux-hardware.org/?probe=455abdf0c3) | Jul 18, 2021 |
| Gigabyte      | G33M-DS2R                   | [04b5a9113c](https://linux-hardware.org/?probe=04b5a9113c) | Jul 17, 2021 |
| ASUSTek       | P5K                         | [8e28e97b01](https://linux-hardware.org/?probe=8e28e97b01) | Jul 16, 2021 |
| Intel         | DH61WW AAG23116-300         | [0de164a96d](https://linux-hardware.org/?probe=0de164a96d) | Jul 16, 2021 |
| Intel         | DH61WW AAG23116-300         | [d14aa75f4c](https://linux-hardware.org/?probe=d14aa75f4c) | Jul 14, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [1b156e0069](https://linux-hardware.org/?probe=1b156e0069) | Jul 12, 2021 |
| Intel         | DG31PR AAD97573-306         | [a81005ef0b](https://linux-hardware.org/?probe=a81005ef0b) | Jul 10, 2021 |
| MSI           | H81M-P33                    | [a03d8e33d2](https://linux-hardware.org/?probe=a03d8e33d2) | Jul 08, 2021 |
| MSI           | H81M-P33                    | [48a72375f0](https://linux-hardware.org/?probe=48a72375f0) | Jul 08, 2021 |
| Acer          | Aspire X3950                | [1ff3961dca](https://linux-hardware.org/?probe=1ff3961dca) | Jul 06, 2021 |
| Gigabyte      | G31M-S2C                    | [7756be5173](https://linux-hardware.org/?probe=7756be5173) | Jul 06, 2021 |
| Gigabyte      | G31M-S2C                    | [9282eabbef](https://linux-hardware.org/?probe=9282eabbef) | Jul 06, 2021 |
| Intel         | DQ77CP AAG67261-300         | [de63bf6b9c](https://linux-hardware.org/?probe=de63bf6b9c) | Jul 06, 2021 |
| Lenovo        | SDK0E50510 WIN              | [d37ee6f754](https://linux-hardware.org/?probe=d37ee6f754) | Jul 04, 2021 |
| Lenovo        | SDK0E50510 WIN              | [2d6120fa61](https://linux-hardware.org/?probe=2d6120fa61) | Jul 04, 2021 |
| ASRock        | H110M-DGS                   | [1439cc6a27](https://linux-hardware.org/?probe=1439cc6a27) | Jul 04, 2021 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | [ea982e9d39](https://linux-hardware.org/?probe=ea982e9d39) | Jul 03, 2021 |
| Foxconn       | 2ABF                        | [b54459c5ca](https://linux-hardware.org/?probe=b54459c5ca) | Jul 01, 2021 |
| MSI           | Z170A PC MATE               | [bd3c620117](https://linux-hardware.org/?probe=bd3c620117) | Jun 24, 2021 |
| Biostar       | TB250-BTC                   | [135a42fc66](https://linux-hardware.org/?probe=135a42fc66) | Jun 19, 2021 |
| Biostar       | TB250-BTC                   | [acdf9bed0d](https://linux-hardware.org/?probe=acdf9bed0d) | Jun 19, 2021 |
| Intel         | DH55HC AAE70933-505         | [7b2f77f8db](https://linux-hardware.org/?probe=7b2f77f8db) | Jun 17, 2021 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | [6a2ce38cb0](https://linux-hardware.org/?probe=6a2ce38cb0) | Jun 12, 2021 |
| Gigabyte      | Z370 HD3-CF                 | [77f9400e70](https://linux-hardware.org/?probe=77f9400e70) | Jun 11, 2021 |
| ASRock        | H61M-VS4                    | [4e96d5e81a](https://linux-hardware.org/?probe=4e96d5e81a) | Jun 10, 2021 |
| Intel         | DQ57TM AAE70931-400         | [d770d5673c](https://linux-hardware.org/?probe=d770d5673c) | Jun 04, 2021 |
| MSI           | B450M PRO-M2 MAX            | [71bd5e1a20](https://linux-hardware.org/?probe=71bd5e1a20) | Jun 04, 2021 |
| ASRock        | B550M Steel Legend          | [f39108e22f](https://linux-hardware.org/?probe=f39108e22f) | May 29, 2021 |
| ASUSTek       | M2NPV-MX                    | [37bc060302](https://linux-hardware.org/?probe=37bc060302) | May 27, 2021 |
| ASUSTek       | M2NPV-MX                    | [11cee33a59](https://linux-hardware.org/?probe=11cee33a59) | May 27, 2021 |
| Intel         | H81                         | [9107f9abe6](https://linux-hardware.org/?probe=9107f9abe6) | May 25, 2021 |
| ASUSTek       | PRIME B250M-A               | [2961088957](https://linux-hardware.org/?probe=2961088957) | May 24, 2021 |
| Gigabyte      | H97-Gaming 3                | [d8b0632698](https://linux-hardware.org/?probe=d8b0632698) | May 23, 2021 |
| Gigabyte      | G31M-ES2C                   | [98e3f46335](https://linux-hardware.org/?probe=98e3f46335) | May 21, 2021 |
| HP            | 802F                        | [88fa80f493](https://linux-hardware.org/?probe=88fa80f493) | May 20, 2021 |
| ASUSTek       | PRIME B250M-A               | [b646c2612a](https://linux-hardware.org/?probe=b646c2612a) | May 18, 2021 |
| Gigabyte      | A320M-S2H-CF                | [48f873b6de](https://linux-hardware.org/?probe=48f873b6de) | May 14, 2021 |
| ASUSTek       | PRIME X570-P                | [8d4f6e55dc](https://linux-hardware.org/?probe=8d4f6e55dc) | May 14, 2021 |
| Acer          | Veriton M4620G v1.0         | [bec2435c15](https://linux-hardware.org/?probe=bec2435c15) | May 12, 2021 |
| Gigabyte      | A320M-S2H-CF                | [a3f9e2334a](https://linux-hardware.org/?probe=a3f9e2334a) | May 11, 2021 |
| ASUSTek       | H110I-PLUS                  | [0f9c2db369](https://linux-hardware.org/?probe=0f9c2db369) | May 07, 2021 |
| Gigabyte      | H110-D3A-CF                 | [016d2f25a7](https://linux-hardware.org/?probe=016d2f25a7) | May 06, 2021 |
| Gigabyte      | H61M-S2V-B3                 | [9d01fac140](https://linux-hardware.org/?probe=9d01fac140) | May 06, 2021 |
| ASUSTek       | Z87-K                       | [6d9e2228c3](https://linux-hardware.org/?probe=6d9e2228c3) | May 05, 2021 |
| ASUSTek       | H110I-PLUS                  | [579414cef4](https://linux-hardware.org/?probe=579414cef4) | May 04, 2021 |
| Gigabyte      | A320M-S2H-CF                | [0deafa542c](https://linux-hardware.org/?probe=0deafa542c) | Apr 29, 2021 |
| Gigabyte      | A320M-S2H-CF                | [04d81bb2f6](https://linux-hardware.org/?probe=04d81bb2f6) | Apr 29, 2021 |
| MSI           | H110M PRO-VD PLUS           | [f9f1775d7a](https://linux-hardware.org/?probe=f9f1775d7a) | Apr 24, 2021 |
| MSI           | H110M PRO-VD PLUS           | [8356cbd097](https://linux-hardware.org/?probe=8356cbd097) | Apr 24, 2021 |
| Unknown       | NF-MCP61                    | [2ba92fa1b6](https://linux-hardware.org/?probe=2ba92fa1b6) | Apr 12, 2021 |
| Unknown       | NF-MCP61                    | [265d75e8f5](https://linux-hardware.org/?probe=265d75e8f5) | Apr 12, 2021 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [c49b7e8d5d](https://linux-hardware.org/?probe=c49b7e8d5d) | Apr 01, 2021 |
| ASRock        | H110M-DGS                   | [786c07faff](https://linux-hardware.org/?probe=786c07faff) | Mar 29, 2021 |
| ASRock        | H110M-DGS                   | [e47641b719](https://linux-hardware.org/?probe=e47641b719) | Mar 29, 2021 |
| HP            | 3397                        | [8bf9eb3e2b](https://linux-hardware.org/?probe=8bf9eb3e2b) | Mar 24, 2021 |
| MSI           | Z370 GAMING PRO CARBON A... | [19c2138c14](https://linux-hardware.org/?probe=19c2138c14) | Mar 21, 2021 |
| Intel         | H61M-DS2                    | [26d3b20dae](https://linux-hardware.org/?probe=26d3b20dae) | Mar 20, 2021 |
| Intel         | H61M-DS2                    | [d92567fa4b](https://linux-hardware.org/?probe=d92567fa4b) | Mar 20, 2021 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [863c61112e](https://linux-hardware.org/?probe=863c61112e) | Mar 15, 2021 |
| ASRock        | H110M-DGS                   | [fb02551d4b](https://linux-hardware.org/?probe=fb02551d4b) | Mar 09, 2021 |
| Acer          | Veriton M4620G v1.0         | [dd94f284a7](https://linux-hardware.org/?probe=dd94f284a7) | Mar 06, 2021 |
| Acer          | Veriton M4620G v1.0         | [3a6a85e270](https://linux-hardware.org/?probe=3a6a85e270) | Mar 06, 2021 |
| Intel         | DG31PR AAD97573-301         | [afbd63a295](https://linux-hardware.org/?probe=afbd63a295) | Mar 02, 2021 |
| Gigabyte      | Z370 HD3-CF                 | [7a590f917d](https://linux-hardware.org/?probe=7a590f917d) | Mar 01, 2021 |
| MSI           | H81M-P33                    | [0842ade22d](https://linux-hardware.org/?probe=0842ade22d) | Feb 28, 2021 |
| MSI           | H81M-P33                    | [4de126b116](https://linux-hardware.org/?probe=4de126b116) | Feb 28, 2021 |
| MSI           | X570-A PRO                  | [d49fa2b9b8](https://linux-hardware.org/?probe=d49fa2b9b8) | Feb 24, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [24edce07be](https://linux-hardware.org/?probe=24edce07be) | Feb 23, 2021 |
| Foxconn       | H61MXP                      | [048b9579b0](https://linux-hardware.org/?probe=048b9579b0) | Feb 23, 2021 |
| ASUSTek       | P8Z68-V                     | [af7b978365](https://linux-hardware.org/?probe=af7b978365) | Feb 22, 2021 |
| ASUSTek       | P8Z68-V                     | [8e7261c2a4](https://linux-hardware.org/?probe=8e7261c2a4) | Feb 22, 2021 |
| ASRock        | H110M-DVS R2.0              | [58d85cf78e](https://linux-hardware.org/?probe=58d85cf78e) | Feb 21, 2021 |
| ASUSTek       | SABERTOOTH Z170 S           | [8cee0d69e5](https://linux-hardware.org/?probe=8cee0d69e5) | Feb 18, 2021 |
| ASUSTek       | SABERTOOTH Z170 S           | [490d7048e7](https://linux-hardware.org/?probe=490d7048e7) | Feb 18, 2021 |
| Intel         | DH67CL AAG10212-210         | [5995dadf6e](https://linux-hardware.org/?probe=5995dadf6e) | Feb 18, 2021 |
| Foxconn       | H61MXP                      | [d4938b881d](https://linux-hardware.org/?probe=d4938b881d) | Feb 17, 2021 |
| MSI           | B250I GAMING PRO AC         | [e451c5c4c0](https://linux-hardware.org/?probe=e451c5c4c0) | Feb 17, 2021 |
| MSI           | X570-A PRO                  | [615e4e0a09](https://linux-hardware.org/?probe=615e4e0a09) | Feb 17, 2021 |
| ASRock        | H110M-DGS                   | [7f8d441dad](https://linux-hardware.org/?probe=7f8d441dad) | Feb 17, 2021 |
| MSI           | X99A SLI PLUS               | [db1e5dad24](https://linux-hardware.org/?probe=db1e5dad24) | Feb 16, 2021 |
| MSI           | X99A SLI PLUS               | [9dd966644d](https://linux-hardware.org/?probe=9dd966644d) | Feb 16, 2021 |
| Acer          | Aspire XC-830               | [9aa4fa465f](https://linux-hardware.org/?probe=9aa4fa465f) | Feb 07, 2021 |
| Acer          | Aspire XC-830               | [fd4af8dfa8](https://linux-hardware.org/?probe=fd4af8dfa8) | Feb 07, 2021 |
| Unknown       | NF-MCP61                    | [0025bae7bc](https://linux-hardware.org/?probe=0025bae7bc) | Feb 07, 2021 |
| Unknown       | NF-MCP61                    | [655941b24c](https://linux-hardware.org/?probe=655941b24c) | Feb 07, 2021 |
| MSI           | B350M GAMING PRO            | [c8bbdc9014](https://linux-hardware.org/?probe=c8bbdc9014) | Jan 31, 2021 |
| Lenovo        | ThinkCentre M57p 6073WB2    | [519a5dab13](https://linux-hardware.org/?probe=519a5dab13) | Jan 31, 2021 |
| Dell          | 0M9KCM A00                  | [bb2c2af939](https://linux-hardware.org/?probe=bb2c2af939) | Jan 30, 2021 |
| Lenovo        | ThinkCentre M57p 6073WB2    | [6845c1eca5](https://linux-hardware.org/?probe=6845c1eca5) | Jan 29, 2021 |
| Foxconn       | H61MXP                      | [9104fd06b9](https://linux-hardware.org/?probe=9104fd06b9) | Jan 24, 2021 |
| ASUSTek       | Q87M-E                      | [dc1ef1ca11](https://linux-hardware.org/?probe=dc1ef1ca11) | Jan 24, 2021 |
| ASUSTek       | P5KPL-AM SE                 | [073c824145](https://linux-hardware.org/?probe=073c824145) | Jan 22, 2021 |
| ASUSTek       | H81M-C                      | [ab6314ffcb](https://linux-hardware.org/?probe=ab6314ffcb) | Jan 21, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | [ceef024b73](https://linux-hardware.org/?probe=ceef024b73) | Jan 20, 2021 |
| MSI           | H77MA-G43                   | [d949ec9e22](https://linux-hardware.org/?probe=d949ec9e22) | Jan 20, 2021 |
| Biostar       | H61MGV                      | [41870b834e](https://linux-hardware.org/?probe=41870b834e) | Jan 19, 2021 |
| MSI           | B450M PRO-M2 MAX            | [ecbdfd2c54](https://linux-hardware.org/?probe=ecbdfd2c54) | Jan 17, 2021 |
| ASUSTek       | H110M-K                     | [475b3240df](https://linux-hardware.org/?probe=475b3240df) | Jan 15, 2021 |
| Intel         | DH55TC AAE70932-302         | [37fa6be89b](https://linux-hardware.org/?probe=37fa6be89b) | Jan 12, 2021 |
| HP            | 1497                        | [1983edaa9d](https://linux-hardware.org/?probe=1983edaa9d) | Jan 10, 2021 |
| Gigabyte      | B75M-D3H                    | [8b9b3a12bf](https://linux-hardware.org/?probe=8b9b3a12bf) | Jan 09, 2021 |
| Gigabyte      | B75M-D3H                    | [08608262c0](https://linux-hardware.org/?probe=08608262c0) | Jan 09, 2021 |
| MSI           | Z77A-GD55                   | [7a756f5970](https://linux-hardware.org/?probe=7a756f5970) | Jan 08, 2021 |
| Gigabyte      | X58A-UD3R                   | [860a73fabe](https://linux-hardware.org/?probe=860a73fabe) | Dec 31, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [0dd4ebf5b8](https://linux-hardware.org/?probe=0dd4ebf5b8) | Dec 29, 2020 |
| ASUSTek       | M4A78T-E                    | [cba05b27c4](https://linux-hardware.org/?probe=cba05b27c4) | Dec 26, 2020 |
| ASUSTek       | P8B75-V                     | [edb814f54a](https://linux-hardware.org/?probe=edb814f54a) | Dec 15, 2020 |
| Gigabyte      | EG31M-S2                    | [cf3ce9357e](https://linux-hardware.org/?probe=cf3ce9357e) | Dec 14, 2020 |
| Lenovo        | ThinkCentre M90p 3853W1B    | [2a0f16e160](https://linux-hardware.org/?probe=2a0f16e160) | Dec 08, 2020 |
| Gigabyte      | H81M-S2PH                   | [86bd640aaa](https://linux-hardware.org/?probe=86bd640aaa) | Dec 07, 2020 |
| Gigabyte      | Z370 HD3-CF                 | [7e191e6e88](https://linux-hardware.org/?probe=7e191e6e88) | Dec 07, 2020 |
| Dell          | OptiPlex 3010               | [41dabae1fc](https://linux-hardware.org/?probe=41dabae1fc) | Dec 07, 2020 |
| MSI           | NF980-G65                   | [905c03a3d4](https://linux-hardware.org/?probe=905c03a3d4) | Dec 02, 2020 |
| ASRock        | 970 Pro3 R2.0               | [0b92fa9e96](https://linux-hardware.org/?probe=0b92fa9e96) | Dec 01, 2020 |
| ASRock        | 970 Pro3 R2.0               | [1526683bfc](https://linux-hardware.org/?probe=1526683bfc) | Nov 30, 2020 |
| ASRock        | 970 Pro3 R2.0               | [4e0a5a0779](https://linux-hardware.org/?probe=4e0a5a0779) | Nov 25, 2020 |
| ASUSTek       | H110M-K                     | [b19f8914b4](https://linux-hardware.org/?probe=b19f8914b4) | Nov 20, 2020 |
| ASUSTek       | H110M-K                     | [c7bdefa142](https://linux-hardware.org/?probe=c7bdefa142) | Nov 20, 2020 |
| MSI           | H61M-P25                    | [d61bf84dc4](https://linux-hardware.org/?probe=d61bf84dc4) | Nov 20, 2020 |
| ASUSTek       | H110M-R                     | [c20406a1b5](https://linux-hardware.org/?probe=c20406a1b5) | Nov 20, 2020 |
| ASUSTek       | H81M-C                      | [aa50c863e9](https://linux-hardware.org/?probe=aa50c863e9) | Nov 20, 2020 |
| ASUSTek       | M4A78T-E                    | [503cfe38f0](https://linux-hardware.org/?probe=503cfe38f0) | Nov 18, 2020 |
| MSI           | MAG B550M MORTAR            | [61d2df9a57](https://linux-hardware.org/?probe=61d2df9a57) | Nov 17, 2020 |
| Intel         | DH67BL AAG10189-206         | [0762d1d1ce](https://linux-hardware.org/?probe=0762d1d1ce) | Nov 14, 2020 |
| Acer          | Aspire XC-705               | [143555ecdc](https://linux-hardware.org/?probe=143555ecdc) | Nov 09, 2020 |
| ASUSTek       | H110M-K D3                  | [114c634725](https://linux-hardware.org/?probe=114c634725) | Nov 09, 2020 |
| MSI           | NF980-G65                   | [91f0882001](https://linux-hardware.org/?probe=91f0882001) | Nov 04, 2020 |
| HP            | ProLiant MicroServer        | [cdc24d2269](https://linux-hardware.org/?probe=cdc24d2269) | Nov 02, 2020 |
| Gigabyte      | G41MT-ES2L                  | [c729daf76c](https://linux-hardware.org/?probe=c729daf76c) | Nov 02, 2020 |
| Acer          | Aspire XC-705               | [f306c95ded](https://linux-hardware.org/?probe=f306c95ded) | Nov 02, 2020 |
| Acer          | Aspire XC-705               | [8816461fc2](https://linux-hardware.org/?probe=8816461fc2) | Nov 02, 2020 |
| Gigabyte      | B250M-D3H-CF                | [547d1a4d87](https://linux-hardware.org/?probe=547d1a4d87) | Nov 01, 2020 |
| MSI           | B450M PRO-M2 MAX            | [192c993267](https://linux-hardware.org/?probe=192c993267) | Oct 26, 2020 |
| MSI           | NF980-G65                   | [b37787e43b](https://linux-hardware.org/?probe=b37787e43b) | Oct 24, 2020 |
| Dell          | 0V8F20 A01                  | [458ed5a803](https://linux-hardware.org/?probe=458ed5a803) | Oct 21, 2020 |
| Gigabyte      | G1.Sniper 2                 | [c4e2198b02](https://linux-hardware.org/?probe=c4e2198b02) | Oct 17, 2020 |
| Gigabyte      | G1.Sniper 2                 | [020c0aa748](https://linux-hardware.org/?probe=020c0aa748) | Oct 17, 2020 |
| Lenovo        | ThinkCentre A70 0889F4G     | [7fecbf8628](https://linux-hardware.org/?probe=7fecbf8628) | Oct 13, 2020 |
| Lenovo        | ThinkCentre A70 0889F4G     | [42fe628907](https://linux-hardware.org/?probe=42fe628907) | Oct 13, 2020 |
| Lenovo        | ThinkCentre A70 0889F4G     | [b166b30db3](https://linux-hardware.org/?probe=b166b30db3) | Oct 08, 2020 |
| Lenovo        | ThinkCentre A70 0889F4G     | [1e6d80b5da](https://linux-hardware.org/?probe=1e6d80b5da) | Oct 06, 2020 |
| ASUSTek       | P8H61-M LX R2.0             | [e161c96649](https://linux-hardware.org/?probe=e161c96649) | Sep 30, 2020 |
| ASUSTek       | P8H61-M LX R2.0             | [b21331d245](https://linux-hardware.org/?probe=b21331d245) | Sep 30, 2020 |
| ASUSTek       | Z170-E                      | [bebee961b4](https://linux-hardware.org/?probe=bebee961b4) | Sep 30, 2020 |
| MSI           | H77MA-G43                   | [bc6fb15e78](https://linux-hardware.org/?probe=bc6fb15e78) | Sep 29, 2020 |
| MSI           | H77MA-G43                   | [07f4ed634b](https://linux-hardware.org/?probe=07f4ed634b) | Sep 29, 2020 |
| ASRock        | H110M-ITX/ac                | [9c30ba348a](https://linux-hardware.org/?probe=9c30ba348a) | Sep 28, 2020 |
| ASUSTek       | Z170-E                      | [c5e88dea7d](https://linux-hardware.org/?probe=c5e88dea7d) | Sep 27, 2020 |
| ASUSTek       | Z170-E                      | [9c106c44cf](https://linux-hardware.org/?probe=9c106c44cf) | Sep 27, 2020 |
| Biostar       | H61MGV                      | [003204ad9f](https://linux-hardware.org/?probe=003204ad9f) | Sep 20, 2020 |
| Intel         | DH87MC AAG74242-401         | [640d76455f](https://linux-hardware.org/?probe=640d76455f) | Sep 20, 2020 |
| Biostar       | H61MLV3                     | [706ef154e2](https://linux-hardware.org/?probe=706ef154e2) | Sep 14, 2020 |
| Biostar       | H61MLV3                     | [837ad7626c](https://linux-hardware.org/?probe=837ad7626c) | Sep 14, 2020 |
| Gigabyte      | H61M-S2V-B3                 | [3a6da8abca](https://linux-hardware.org/?probe=3a6da8abca) | Sep 13, 2020 |
| Gigabyte      | H61M-S2V-B3                 | [e5854eb062](https://linux-hardware.org/?probe=e5854eb062) | Sep 12, 2020 |
| MSI           | X570-A PRO                  | [656188adb4](https://linux-hardware.org/?probe=656188adb4) | Sep 09, 2020 |
| MSI           | H81M-E33                    | [b95a7fc433](https://linux-hardware.org/?probe=b95a7fc433) | Sep 09, 2020 |
| Gigabyte      | G31M-S2L                    | [a70420ab80](https://linux-hardware.org/?probe=a70420ab80) | Sep 07, 2020 |
| MSI           | Z170A GAMING PRO            | [a23e1ab6f7](https://linux-hardware.org/?probe=a23e1ab6f7) | Sep 06, 2020 |
| MSI           | Z170A GAMING PRO            | [e12a573590](https://linux-hardware.org/?probe=e12a573590) | Sep 06, 2020 |
| Gigabyte      | 8VM800PMD-775               | [5556df1576](https://linux-hardware.org/?probe=5556df1576) | Sep 06, 2020 |
| Gigabyte      | 8VM800PMD-775               | [69d3d97213](https://linux-hardware.org/?probe=69d3d97213) | Sep 06, 2020 |
| Intel         | DQ77MK AAG39642-400         | [e44a1ed00a](https://linux-hardware.org/?probe=e44a1ed00a) | Sep 05, 2020 |
| MSI           | MPG Z390 GAMING EDGE AC     | [8b70f4c277](https://linux-hardware.org/?probe=8b70f4c277) | Sep 04, 2020 |
| ASRock        | B450M Pro4                  | [58a5d68d50](https://linux-hardware.org/?probe=58a5d68d50) | Sep 03, 2020 |
| MSI           | 0A48                        | [0b6b6f4e6c](https://linux-hardware.org/?probe=0b6b6f4e6c) | Sep 01, 2020 |
| MSI           | B350M MORTAR                | [95318ea3f4](https://linux-hardware.org/?probe=95318ea3f4) | Aug 31, 2020 |
| ASUSTek       | H110M-K D3                  | [5e4fc68354](https://linux-hardware.org/?probe=5e4fc68354) | Aug 28, 2020 |
| Biostar       | H61MGV                      | [6fc04609f6](https://linux-hardware.org/?probe=6fc04609f6) | Aug 26, 2020 |
| ASUSTek       | P8H67-M LX                  | [1b2d7271d9](https://linux-hardware.org/?probe=1b2d7271d9) | Aug 26, 2020 |
| ASUSTek       | P8H67-M LX                  | [839d7c2a46](https://linux-hardware.org/?probe=839d7c2a46) | Aug 26, 2020 |
| Intel         | E98683-352                  | [2cced3a630](https://linux-hardware.org/?probe=2cced3a630) | Aug 26, 2020 |
| Acer          | Aspire XC-705               | [a14063c53e](https://linux-hardware.org/?probe=a14063c53e) | Aug 25, 2020 |
| MSI           | 0A48                        | [ecc5cc9591](https://linux-hardware.org/?probe=ecc5cc9591) | Aug 24, 2020 |
| MSI           | 0A48                        | [6cd21feb7e](https://linux-hardware.org/?probe=6cd21feb7e) | Aug 23, 2020 |
| ASUSTek       | PRIME X470-PRO              | [0d285d0379](https://linux-hardware.org/?probe=0d285d0379) | Aug 22, 2020 |
| Intel         | DH67BL AAG10189-206         | [e160d14621](https://linux-hardware.org/?probe=e160d14621) | Aug 22, 2020 |
| MSI           | H310M PRO-VH PLUS           | [faecb20cfb](https://linux-hardware.org/?probe=faecb20cfb) | Aug 19, 2020 |
| HP            | 1495                        | [c801ac56c4](https://linux-hardware.org/?probe=c801ac56c4) | Aug 18, 2020 |
| ASRock        | G31M-S                      | [decbf99a87](https://linux-hardware.org/?probe=decbf99a87) | Aug 17, 2020 |
| ASRock        | G31M-S                      | [4915506e2e](https://linux-hardware.org/?probe=4915506e2e) | Aug 17, 2020 |
| Intel         | DH77EB AAG39073-304         | [ae001e48e0](https://linux-hardware.org/?probe=ae001e48e0) | Aug 16, 2020 |
| ASRock        | H61M-VS3                    | [d140a21b1c](https://linux-hardware.org/?probe=d140a21b1c) | Aug 16, 2020 |
| ASRock        | A320M                       | [e0c8cc0af2](https://linux-hardware.org/?probe=e0c8cc0af2) | Aug 14, 2020 |
| MSI           | 0A48                        | [24b38b5516](https://linux-hardware.org/?probe=24b38b5516) | Aug 12, 2020 |
| MSI           | 0A48                        | [a3f7719625](https://linux-hardware.org/?probe=a3f7719625) | Aug 12, 2020 |
| Dell          | 06D7TR A00                  | [71d3a723ab](https://linux-hardware.org/?probe=71d3a723ab) | Aug 11, 2020 |
| Gigabyte      | H61M-DS2                    | [218e35b46b](https://linux-hardware.org/?probe=218e35b46b) | Aug 10, 2020 |
| Gigabyte      | H61M-DS2                    | [4ff4ced1de](https://linux-hardware.org/?probe=4ff4ced1de) | Aug 10, 2020 |
| Intel         | DQ965GF AAD41676-402        | [c3ceaf788a](https://linux-hardware.org/?probe=c3ceaf788a) | Aug 10, 2020 |
| ASRock        | H61M-VS3                    | [ec2a94de5a](https://linux-hardware.org/?probe=ec2a94de5a) | Aug 09, 2020 |
| Gigabyte      | XP-M5S661GX                 | [5f94eae640](https://linux-hardware.org/?probe=5f94eae640) | Aug 07, 2020 |
| MSI           | H310M PRO-VH PLUS           | [2f79221a54](https://linux-hardware.org/?probe=2f79221a54) | Aug 02, 2020 |
| Nvidia        | MCP73                       | [51821b9a72](https://linux-hardware.org/?probe=51821b9a72) | Aug 01, 2020 |
| Acer          | Aspire XC-705               | [c17f70b052](https://linux-hardware.org/?probe=c17f70b052) | Aug 01, 2020 |
| MSI           | H81M-P33                    | [2b15f51554](https://linux-hardware.org/?probe=2b15f51554) | Jul 29, 2020 |
| Apple         | Mac-F42C88C8 Proto1         | [be59eae36f](https://linux-hardware.org/?probe=be59eae36f) | Jul 28, 2020 |
| Apple         | Mac-F42C88C8 Proto1         | [adb494dfce](https://linux-hardware.org/?probe=adb494dfce) | Jul 28, 2020 |
| Foxconn       | P4M890-8237A                | [c26157f6a1](https://linux-hardware.org/?probe=c26157f6a1) | Jul 23, 2020 |
| Intel         | DH87MC AAG74242-401         | [4a60cb40c9](https://linux-hardware.org/?probe=4a60cb40c9) | Jul 20, 2020 |
| Dell          | 06D7TR A00                  | [ba6562dccd](https://linux-hardware.org/?probe=ba6562dccd) | Jul 18, 2020 |
| Intel         | DP55WB AAE64798-206         | [f533450c99](https://linux-hardware.org/?probe=f533450c99) | Jul 16, 2020 |
| HP            | ProLiant ML110 G7           | [bb50bb3a46](https://linux-hardware.org/?probe=bb50bb3a46) | Jul 15, 2020 |
| Intel         | DH67BL AAG10189-206         | [4548f15388](https://linux-hardware.org/?probe=4548f15388) | Jul 12, 2020 |
| Lenovo        | MAHOBAY NOK                 | [c6660d16e0](https://linux-hardware.org/?probe=c6660d16e0) | Jul 08, 2020 |
| ASUSTek       | M5A99FX PRO R2.0            | [de85d7ecf6](https://linux-hardware.org/?probe=de85d7ecf6) | Jul 07, 2020 |
| ASRock        | AB350M-HDV                  | [db7ec5e511](https://linux-hardware.org/?probe=db7ec5e511) | Jun 29, 2020 |
| ECS           | G31T-M7                     | [95eaae406a](https://linux-hardware.org/?probe=95eaae406a) | Jun 27, 2020 |
| Intel         | DH67BL AAG10189-206         | [693e0bb2f6](https://linux-hardware.org/?probe=693e0bb2f6) | Jun 22, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [ddda4255d1](https://linux-hardware.org/?probe=ddda4255d1) | Jun 19, 2020 |
| Gigabyte      | H81M-S2PH                   | [871a6364d4](https://linux-hardware.org/?probe=871a6364d4) | Jun 19, 2020 |
| ASUSTek       | Q87M-E                      | [5b07966114](https://linux-hardware.org/?probe=5b07966114) | Jun 18, 2020 |
| MSI           | MS-7528                     | [dc65359d28](https://linux-hardware.org/?probe=dc65359d28) | Jun 11, 2020 |
| HP            | 805B                        | [442ee42078](https://linux-hardware.org/?probe=442ee42078) | Jun 10, 2020 |
| Biostar       | H61MLV2                     | [7c2d6cc69e](https://linux-hardware.org/?probe=7c2d6cc69e) | Jun 10, 2020 |
| Biostar       | H61MLV2                     | [707e32f26c](https://linux-hardware.org/?probe=707e32f26c) | Jun 09, 2020 |
| HP            | 83F3                        | [5338d0b301](https://linux-hardware.org/?probe=5338d0b301) | Jun 06, 2020 |
| Dell          | 0GDG8Y A00                  | [25d22f7216](https://linux-hardware.org/?probe=25d22f7216) | Jun 03, 2020 |
| Intel         | DG33FB AAD81072-306         | [e3bd459f84](https://linux-hardware.org/?probe=e3bd459f84) | Jun 01, 2020 |
| Intel         | DG33FB AAD81072-306         | [fcc918ad60](https://linux-hardware.org/?probe=fcc918ad60) | May 31, 2020 |
| Gigabyte      | B85M-HD3                    | [7cdfc70ee9](https://linux-hardware.org/?probe=7cdfc70ee9) | May 30, 2020 |
| Gigabyte      | B85M-HD3                    | [4b5ddc99c9](https://linux-hardware.org/?probe=4b5ddc99c9) | May 30, 2020 |
| Gigabyte      | H81M-S2PH                   | [45b32108e4](https://linux-hardware.org/?probe=45b32108e4) | May 27, 2020 |
| ASUSTek       | P8H61-M LX                  | [cb9d706df6](https://linux-hardware.org/?probe=cb9d706df6) | May 26, 2020 |
| ECS           | H55H-M                      | [077724dbf5](https://linux-hardware.org/?probe=077724dbf5) | May 20, 2020 |
| ECS           | H55H-M                      | [a1eede754f](https://linux-hardware.org/?probe=a1eede754f) | May 20, 2020 |
| Unknown       | P4M800Pro-8237              | [71f901a69f](https://linux-hardware.org/?probe=71f901a69f) | May 18, 2020 |
| Unknown       | P4M800Pro-8237              | [bce5724752](https://linux-hardware.org/?probe=bce5724752) | May 18, 2020 |
| Intel         | DQ57TM AAE70931-402         | [b8442a4625](https://linux-hardware.org/?probe=b8442a4625) | May 17, 2020 |
| Unknown       | P4M800Pro-8237              | [21d6bc116d](https://linux-hardware.org/?probe=21d6bc116d) | May 15, 2020 |
| ECS           | G41T-M                      | [6349e4f073](https://linux-hardware.org/?probe=6349e4f073) | May 13, 2020 |
| Gigabyte      | H77M-D3H                    | [de237bc9f1](https://linux-hardware.org/?probe=de237bc9f1) | May 12, 2020 |
| HP            | 1495                        | [6829e49d1b](https://linux-hardware.org/?probe=6829e49d1b) | May 12, 2020 |
| Biostar       | TB250-BTC PRO               | [7274c8e573](https://linux-hardware.org/?probe=7274c8e573) | May 12, 2020 |
| HP            | 1495                        | [bdada1df43](https://linux-hardware.org/?probe=bdada1df43) | May 11, 2020 |
| ASUSTek       | Q87M-E                      | [4aab40e3ef](https://linux-hardware.org/?probe=4aab40e3ef) | May 09, 2020 |
| ASUSTek       | P5N-D                       | [d77f4b93e4](https://linux-hardware.org/?probe=d77f4b93e4) | May 07, 2020 |
| Lenovo        | ThinkCentre M57 6075WAU     | [1ceade6e83](https://linux-hardware.org/?probe=1ceade6e83) | May 06, 2020 |
| ASUSTek       | P8H61-I R2.0                | [1cbb308058](https://linux-hardware.org/?probe=1cbb308058) | May 06, 2020 |
| Intel         | DQ57TM AAE70931-403         | [ea3398787c](https://linux-hardware.org/?probe=ea3398787c) | May 06, 2020 |
| Intel         | DQ57TM AAE70931-403         | [4771e12533](https://linux-hardware.org/?probe=4771e12533) | May 05, 2020 |
| ASUSTek       | P8H61-I R2.0                | [a90f974870](https://linux-hardware.org/?probe=a90f974870) | May 05, 2020 |
| Intel         | DG33FB AAD81072-306         | [2c0b3102ba](https://linux-hardware.org/?probe=2c0b3102ba) | May 01, 2020 |
| ASUSTek       | M3A79-T DELUXE              | [d70c0d15c6](https://linux-hardware.org/?probe=d70c0d15c6) | Apr 30, 2020 |
| Lenovo        | MAHOBAY                     | [a9fa20578e](https://linux-hardware.org/?probe=a9fa20578e) | Apr 28, 2020 |
| Lenovo        | MAHOBAY                     | [bd69f0db96](https://linux-hardware.org/?probe=bd69f0db96) | Apr 28, 2020 |
| Intel         | DQ57TM AAE70931-402         | [346f94096c](https://linux-hardware.org/?probe=346f94096c) | Apr 27, 2020 |
| Nvidia        | MCP73                       | [df5be54153](https://linux-hardware.org/?probe=df5be54153) | Apr 27, 2020 |
| Intel         | DQ57TM AAE70931-402         | [da9fd9a546](https://linux-hardware.org/?probe=da9fd9a546) | Apr 27, 2020 |
| ASUSTek       | Maximus IX HERO             | [184ef341c4](https://linux-hardware.org/?probe=184ef341c4) | Apr 23, 2020 |
| ASUSTek       | Maximus IX HERO             | [2b950abd55](https://linux-hardware.org/?probe=2b950abd55) | Apr 23, 2020 |
| ASUSTek       | Maximus IX HERO             | [7e34d139fc](https://linux-hardware.org/?probe=7e34d139fc) | Apr 23, 2020 |
| Lenovo        | ThinkCentre A55 963672G     | [f33142fc46](https://linux-hardware.org/?probe=f33142fc46) | Apr 17, 2020 |
| MSI           | MS-7388                     | [1bf85fec38](https://linux-hardware.org/?probe=1bf85fec38) | Apr 17, 2020 |
| MSI           | B150M BAZOOKA               | [2bda20adc0](https://linux-hardware.org/?probe=2bda20adc0) | Apr 16, 2020 |
| MSI           | B150M BAZOOKA               | [d2e90e08eb](https://linux-hardware.org/?probe=d2e90e08eb) | Apr 16, 2020 |
| ASUSTek       | Q87M-E                      | [9998ec29fd](https://linux-hardware.org/?probe=9998ec29fd) | Apr 11, 2020 |
| ASUSTek       | Q87M-E                      | [8300430118](https://linux-hardware.org/?probe=8300430118) | Apr 10, 2020 |
| ASUSTek       | Q87M-E                      | [6d6740d6e5](https://linux-hardware.org/?probe=6d6740d6e5) | Apr 10, 2020 |
| ASUSTek       | Q87M-E                      | [70b7d8282a](https://linux-hardware.org/?probe=70b7d8282a) | Apr 10, 2020 |
| ASUSTek       | P5G41T-M LX3                | [31c445f67f](https://linux-hardware.org/?probe=31c445f67f) | Apr 09, 2020 |
| Lite-On       | 08FCh E01                   | [e5a23af168](https://linux-hardware.org/?probe=e5a23af168) | Apr 05, 2020 |
| Lite-On       | 08FCh E01                   | [b2adb5c48e](https://linux-hardware.org/?probe=b2adb5c48e) | Apr 05, 2020 |
| HP            | 805B                        | [2fe00b7859](https://linux-hardware.org/?probe=2fe00b7859) | Apr 03, 2020 |
| Intel         | DH87MC AAG74242-401         | [d6fec3460a](https://linux-hardware.org/?probe=d6fec3460a) | Mar 22, 2020 |
| ASUSTek       | P5Q-PRO                     | [0fb21440b5](https://linux-hardware.org/?probe=0fb21440b5) | Mar 15, 2020 |
| ASRock        | G31M-VS                     | [3256f062c5](https://linux-hardware.org/?probe=3256f062c5) | Mar 11, 2020 |
| MSI           | X370 GAMING PRO CARBON      | [7668f2f550](https://linux-hardware.org/?probe=7668f2f550) | Mar 06, 2020 |
| MSI           | X370 GAMING PRO CARBON      | [ccaffec62a](https://linux-hardware.org/?probe=ccaffec62a) | Mar 06, 2020 |
| MSI           | X370 GAMING PRO CARBON      | [15b50d0d21](https://linux-hardware.org/?probe=15b50d0d21) | Mar 06, 2020 |
| Gigabyte      | Q270M-D3H                   | [8d63f92e6f](https://linux-hardware.org/?probe=8d63f92e6f) | Mar 03, 2020 |
| Gigabyte      | Q270M-D3H                   | [1a69b0489c](https://linux-hardware.org/?probe=1a69b0489c) | Mar 03, 2020 |
| Intel         | DH61WW AAG23116-303         | [fed0d77a30](https://linux-hardware.org/?probe=fed0d77a30) | Feb 04, 2020 |
| Gigabyte      | H81M-DS2                    | [2017ebe76b](https://linux-hardware.org/?probe=2017ebe76b) | Feb 02, 2020 |
| Biostar       | TPower X58                  | [94920b348a](https://linux-hardware.org/?probe=94920b348a) | Jan 28, 2020 |
| Gigabyte      | H81M-DS2                    | [f0fca4cc90](https://linux-hardware.org/?probe=f0fca4cc90) | Jan 28, 2020 |
| Gigabyte      | H81M-DS2                    | [d5427ab6fc](https://linux-hardware.org/?probe=d5427ab6fc) | Jan 27, 2020 |
| MSI           | Z97 PC Mate                 | [7b9527402d](https://linux-hardware.org/?probe=7b9527402d) | Jan 25, 2020 |
| MSI           | H77MA-G43                   | [5a0c6d2f14](https://linux-hardware.org/?probe=5a0c6d2f14) | Jan 24, 2020 |
| Gigabyte      | B75M-D3V                    | [c900d7a6e2](https://linux-hardware.org/?probe=c900d7a6e2) | Jan 20, 2020 |
| HP            | ML150 G3                    | [b4f5ff56bd](https://linux-hardware.org/?probe=b4f5ff56bd) | Jan 09, 2020 |
| ASUSTek       | P5Q-PRO                     | [9cd8c465bf](https://linux-hardware.org/?probe=9cd8c465bf) | Jan 03, 2020 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | [18674d7b06](https://linux-hardware.org/?probe=18674d7b06) | Dec 31, 2019 |
| Dell          | 0V8F20 A01                  | [0f87997cd1](https://linux-hardware.org/?probe=0f87997cd1) | Dec 18, 2019 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | [84669a36b5](https://linux-hardware.org/?probe=84669a36b5) | Dec 18, 2019 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | [e87c9c3d58](https://linux-hardware.org/?probe=e87c9c3d58) | Dec 18, 2019 |
| Biostar       | H110MHV3                    | [8ae0080096](https://linux-hardware.org/?probe=8ae0080096) | Dec 14, 2019 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | [688d57e1a1](https://linux-hardware.org/?probe=688d57e1a1) | Dec 06, 2019 |
| ASRock        | H61M-VS                     | [5da8f545aa](https://linux-hardware.org/?probe=5da8f545aa) | Nov 30, 2019 |
| Biostar       | H110MHV3                    | [7656b302ec](https://linux-hardware.org/?probe=7656b302ec) | Nov 26, 2019 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [5783b5888e](https://linux-hardware.org/?probe=5783b5888e) | Oct 31, 2019 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [32f516b0a3](https://linux-hardware.org/?probe=32f516b0a3) | Oct 31, 2019 |
| Gigabyte      | EP45T-UD3LR                 | [4565af098e](https://linux-hardware.org/?probe=4565af098e) | Oct 26, 2019 |
| Gigabyte      | H55M-S2H                    | [09b0e06bf9](https://linux-hardware.org/?probe=09b0e06bf9) | Oct 09, 2019 |
| MSI           | X99S SLI PLUS               | [5ef345d877](https://linux-hardware.org/?probe=5ef345d877) | Sep 27, 2019 |
| Dell          | 0200DY A01                  | [bfea104c20](https://linux-hardware.org/?probe=bfea104c20) | Sep 26, 2019 |
| MSI           | X99S SLI PLUS               | [9c67e3a660](https://linux-hardware.org/?probe=9c67e3a660) | Sep 18, 2019 |
| HP            | 1632                        | [3f5304647a](https://linux-hardware.org/?probe=3f5304647a) | Sep 07, 2019 |
| Intel         | DG33FB AAD81072-307         | [53195aa497](https://linux-hardware.org/?probe=53195aa497) | Sep 01, 2019 |
| Intel         | DG33FB AAD81072-307         | [51521e9703](https://linux-hardware.org/?probe=51521e9703) | Sep 01, 2019 |
| Intel         | DG33FB AAD81072-307         | [941dc4e852](https://linux-hardware.org/?probe=941dc4e852) | Sep 01, 2019 |
| Intel         | D946GZIS AAD83227-402       | [ec6430c030](https://linux-hardware.org/?probe=ec6430c030) | Aug 29, 2019 |
| Gigabyte      | H55M-S2H                    | [e106c00a0a](https://linux-hardware.org/?probe=e106c00a0a) | Aug 27, 2019 |
| HP            | 304Bh                       | [0e9912689f](https://linux-hardware.org/?probe=0e9912689f) | Aug 23, 2019 |
| ASUSTek       | PRIME A320M-K               | [31e1665c16](https://linux-hardware.org/?probe=31e1665c16) | Aug 22, 2019 |
| Intel         | D946GZIS AAD83227-402       | [8053ea70b7](https://linux-hardware.org/?probe=8053ea70b7) | Aug 11, 2019 |
| Foxconn       | 2ABF                        | [ec9d343037](https://linux-hardware.org/?probe=ec9d343037) | Aug 03, 2019 |
| Dell          | 0Y2MRG A00                  | [fed40374f1](https://linux-hardware.org/?probe=fed40374f1) | Jul 19, 2019 |
| Gigabyte      | B360M D3H-CF                | [b1e690fc69](https://linux-hardware.org/?probe=b1e690fc69) | Jul 14, 2019 |
| ASUSTek       | Z170-K                      | [4fc2e905b4](https://linux-hardware.org/?probe=4fc2e905b4) | Jul 04, 2019 |
| ASUSTek       | Z170-K                      | [7eecce410f](https://linux-hardware.org/?probe=7eecce410f) | Jul 04, 2019 |
| Gigabyte      | G31M-S2C                    | [b4020c7021](https://linux-hardware.org/?probe=b4020c7021) | Jun 20, 2019 |
| Gigabyte      | G31M-S2C                    | [83ef6f0482](https://linux-hardware.org/?probe=83ef6f0482) | Jun 20, 2019 |
| Foxconn       | nT-iBT18_nT-iBT19_nT-iBT... | [0c90b25a45](https://linux-hardware.org/?probe=0c90b25a45) | May 28, 2019 |
| Dell          | 0V8F20 A01                  | [29eca9d63c](https://linux-hardware.org/?probe=29eca9d63c) | May 20, 2019 |
| Gigabyte      | B85M-HD3                    | [d5af14209b](https://linux-hardware.org/?probe=d5af14209b) | May 10, 2019 |
| ASUSTek       | H61M-E                      | [758b0583b1](https://linux-hardware.org/?probe=758b0583b1) | May 04, 2019 |
| Intel         | DQ57TM AAE70931-402         | [3135496cc0](https://linux-hardware.org/?probe=3135496cc0) | Apr 29, 2019 |
| ASUSTek       | P5G41T-M LX                 | [16ecb5a13f](https://linux-hardware.org/?probe=16ecb5a13f) | Apr 19, 2019 |
| Dell          | 09KPNV A00                  | [bca2ebdbaf](https://linux-hardware.org/?probe=bca2ebdbaf) | Apr 03, 2019 |
| ASUSTek       | H81-GAMER                   | [27465fddb7](https://linux-hardware.org/?probe=27465fddb7) | Mar 28, 2019 |
| MSI           | Z370 SLI PLUS               | [ce19512cbb](https://linux-hardware.org/?probe=ce19512cbb) | Mar 18, 2019 |
| MSI           | Z370 SLI PLUS               | [38b37701fa](https://linux-hardware.org/?probe=38b37701fa) | Mar 18, 2019 |
| HP            | 1632                        | [8d82d4b75c](https://linux-hardware.org/?probe=8d82d4b75c) | Jan 30, 2019 |
| HP            | 1632                        | [24f2034cf5](https://linux-hardware.org/?probe=24f2034cf5) | Jan 26, 2019 |
| Lenovo        | ThinkCentre A57 97027LG     | [3f2f50064e](https://linux-hardware.org/?probe=3f2f50064e) | Dec 21, 2018 |
| Dell          | 0GDG8Y A00                  | [0491674dac](https://linux-hardware.org/?probe=0491674dac) | Nov 27, 2018 |
| Foxconn       | H55MXV Series               | [6b384caea8](https://linux-hardware.org/?probe=6b384caea8) | Nov 26, 2018 |
| Unknown       | NF-MCP61                    | [34b91208c5](https://linux-hardware.org/?probe=34b91208c5) | Oct 31, 2018 |
| HP            | ProLiant MicroServer        | [1dd894b330](https://linux-hardware.org/?probe=1dd894b330) | Oct 19, 2018 |
| HP            | ProLiant MicroServer        | [9d5778f932](https://linux-hardware.org/?probe=9d5778f932) | Oct 19, 2018 |
| ASUSTek       | P5QL-EM                     | [dcc6824dc1](https://linux-hardware.org/?probe=dcc6824dc1) | Feb 21, 2018 |
| MSI           | H81M-P33                    | [376a9193df](https://linux-hardware.org/?probe=376a9193df) | Jun 27, 2017 |
| Lenovo        | NO DPK                      | [21f98e8f6c](https://linux-hardware.org/?probe=21f98e8f6c) | May 07, 2017 |
| ASRock        | H61M-VS3                    | [c0b09d5096](https://linux-hardware.org/?probe=c0b09d5096) | Apr 29, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/South_Africa/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Ubuntu 20.04        | 75       | 15.06%  |
| Ubuntu 18.04        | 32       | 6.43%   |
| Ubuntu 22.04        | 30       | 6.02%   |
| Zorin 16            | 14       | 2.81%   |
| Linux Mint 19.3     | 12       | 2.41%   |
| Pop!_OS 20.10       | 11       | 2.21%   |
| Manjaro             | 11       | 2.21%   |
| ArcoLinux Rolling   | 11       | 2.21%   |
| Debian 12           | 10       | 2.01%   |
| Pop!_OS 22.04       | 9        | 1.81%   |
| Pop!_OS 21.04       | 9        | 1.81%   |
| Pop!_OS 20.04       | 9        | 1.81%   |
| KDE neon 20.04      | 9        | 1.81%   |
| Zorin 15            | 8        | 1.61%   |
| OpenMandriva 4.3    | 8        | 1.61%   |
| OpenMandriva 4.2    | 7        | 1.41%   |
| Linux Mint 20.1     | 7        | 1.41%   |
| Debian 11           | 7        | 1.41%   |
| Ubuntu 21.04        | 6        | 1.2%    |
| Ubuntu 19.10        | 6        | 1.2%    |
| BlackPanther 18.1   | 6        | 1.2%    |
| Ubuntu 16.04        | 5        | 1%      |
| OpenMandriva 23.03  | 5        | 1%      |
| Linux Mint 20.3     | 5        | 1%      |
| KDE neon 22.04      | 5        | 1%      |
| Zorin 17            | 4        | 0.8%    |
| Ubuntu Unity 16.04  | 4        | 0.8%    |
| Ubuntu 22.10        | 4        | 0.8%    |
| Pop!_OS 21.10       | 4        | 0.8%    |
| OpenMandriva 23.08  | 4        | 0.8%    |
| OpenMandriva 23.01  | 4        | 0.8%    |
| Linux Mint 21.2     | 4        | 0.8%    |
| Linux Mint 21.1     | 4        | 0.8%    |
| Linux Mint 19       | 4        | 0.8%    |
| Kubuntu 20.04       | 4        | 0.8%    |
| EndeavourOS Rolling | 4        | 0.8%    |
| Arch Rolling        | 4        | 0.8%    |
| Xubuntu 20.04       | 3        | 0.6%    |
| Ubuntu 23.04        | 3        | 0.6%    |
| Ubuntu 21.10        | 3        | 0.6%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 161      | 34.4%   |
| Linux Mint    | 43       | 9.19%   |
| Pop!_OS       | 41       | 8.76%   |
| Zorin         | 26       | 5.56%   |
| OpenMandriva  | 26       | 5.56%   |
| Debian        | 25       | 5.34%   |
| Manjaro       | 16       | 3.42%   |
| KDE neon      | 14       | 2.99%   |
| ArcoLinux     | 11       | 2.35%   |
| Fedora        | 9        | 1.92%   |
| Xubuntu       | 8        | 1.71%   |
| ROSA          | 7        | 1.5%    |
| Kubuntu       | 7        | 1.5%    |
| BlackPanther  | 6        | 1.28%   |
| Arch          | 6        | 1.28%   |
| Ubuntu Unity  | 5        | 1.07%   |
| openSUSE      | 4        | 0.85%   |
| EndeavourOS   | 4        | 0.85%   |
| SteamOS       | 3        | 0.64%   |
| Nobara        | 3        | 0.64%   |
| Lubuntu       | 3        | 0.64%   |
| LMDE          | 3        | 0.64%   |
| LinuxFX       | 3        | 0.64%   |
| Kali          | 3        | 0.64%   |
| Garuda Linux  | 3        | 0.64%   |
| TUXEDO OS     | 2        | 0.43%   |
| Rocky Linux   | 2        | 0.43%   |
| MX            | 2        | 0.43%   |
| Gentoo        | 2        | 0.43%   |
| Endless       | 2        | 0.43%   |
| Clear Linux   | 2        | 0.43%   |
| CentOS        | 2        | 0.43%   |
| Xero          | 1        | 0.21%   |
| Ubuntu MATE   | 1        | 0.21%   |
| Ubuntu Budgie | 1        | 0.21%   |
| Sparky        | 1        | 0.21%   |
| Slackware     | 1        | 0.21%   |
| RHEL          | 1        | 0.21%   |
| Q4OS          | 1        | 0.21%   |
| Parrot        | 1        | 0.21%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.4.0-42-generic         | 13       | 2.32%   |
| 5.16.7-desktop-1omv4003  | 8        | 1.43%   |
| 5.8.0-7642-generic       | 7        | 1.25%   |
| 5.4.0-58-generic         | 7        | 1.25%   |
| 5.4.0-52-generic         | 7        | 1.25%   |
| 5.15.0-56-generic        | 7        | 1.25%   |
| 5.13.0-7614-generic      | 6        | 1.07%   |
| 6.2.6-desktop-1omv2390   | 5        | 0.89%   |
| 6.1.0-13-amd64           | 5        | 0.89%   |
| 5.19.0-35-generic        | 5        | 0.89%   |
| 5.15.0-48-generic        | 5        | 0.89%   |
| 5.11.0-40-generic        | 5        | 0.89%   |
| 5.10.14-desktop-1omv4002 | 5        | 0.89%   |
| 4.18.16-desktop-1bP      | 5        | 0.89%   |
| 4.15.0-54-generic        | 5        | 0.89%   |
| 6.4.11-desktop-1omv2390  | 4        | 0.71%   |
| 6.1.1-desktop-1omv2290   | 4        | 0.71%   |
| 5.8.0-59-generic         | 4        | 0.71%   |
| 5.4.0-7634-generic       | 4        | 0.71%   |
| 5.4.0-72-generic         | 4        | 0.71%   |
| 5.4.0-54-generic         | 4        | 0.71%   |
| 5.3.0-46-generic         | 4        | 0.71%   |
| 5.11.0-41-generic        | 4        | 0.71%   |
| 5.11.0-27-generic        | 4        | 0.71%   |
| 5.11.0-25-generic        | 4        | 0.71%   |
| 6.5.0-27-generic         | 3        | 0.53%   |
| 6.2.6-76060206-generic   | 3        | 0.53%   |
| 6.1.0-11-amd64           | 3        | 0.53%   |
| 5.8.0-43-generic         | 3        | 0.53%   |
| 5.4.0-45-generic         | 3        | 0.53%   |
| 5.4.0-37-generic         | 3        | 0.53%   |
| 5.3.0-53-generic         | 3        | 0.53%   |
| 5.19.0-46-generic        | 3        | 0.53%   |
| 5.19.0-42-generic        | 3        | 0.53%   |
| 5.15.0-78-generic        | 3        | 0.53%   |
| 5.15.0-76-generic        | 3        | 0.53%   |
| 5.15.0-71-generic        | 3        | 0.53%   |
| 5.15.0-58-generic        | 3        | 0.53%   |
| 5.15.0-46-generic        | 3        | 0.53%   |
| 5.13.0-28-generic        | 3        | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 91       | 17.5%   |
| 5.15.0  | 48       | 9.23%   |
| 5.11.0  | 34       | 6.54%   |
| 4.15.0  | 31       | 5.96%   |
| 5.8.0   | 30       | 5.77%   |
| 5.13.0  | 22       | 4.23%   |
| 6.1.0   | 16       | 3.08%   |
| 5.3.0   | 16       | 3.08%   |
| 5.19.0  | 16       | 3.08%   |
| 4.18.0  | 12       | 2.31%   |
| 5.10.0  | 11       | 2.12%   |
| 6.2.0   | 10       | 1.92%   |
| 6.5.0   | 9        | 1.73%   |
| 6.2.6   | 9        | 1.73%   |
| 5.0.0   | 9        | 1.73%   |
| 5.16.7  | 8        | 1.54%   |
| 6.4.11  | 5        | 0.96%   |
| 6.1.1   | 5        | 0.96%   |
| 5.10.14 | 5        | 0.96%   |
| 4.4.0   | 5        | 0.96%   |
| 4.18.16 | 5        | 0.96%   |
| 6.4.12  | 3        | 0.58%   |
| 4.9.20  | 3        | 0.58%   |
| 6.6.6   | 2        | 0.38%   |
| 6.6.2   | 2        | 0.38%   |
| 6.1.31  | 2        | 0.38%   |
| 5.9.0   | 2        | 0.38%   |
| 5.6.0   | 2        | 0.38%   |
| 5.18.0  | 2        | 0.38%   |
| 5.17.5  | 2        | 0.38%   |
| 5.17.1  | 2        | 0.38%   |
| 5.16.19 | 2        | 0.38%   |
| 5.15.5  | 2        | 0.38%   |
| 5.15.32 | 2        | 0.38%   |
| 5.15.3  | 2        | 0.38%   |
| 5.15.15 | 2        | 0.38%   |
| 5.14.21 | 2        | 0.38%   |
| 5.14.0  | 2        | 0.38%   |
| 5.13.13 | 2        | 0.38%   |
| 5.11.12 | 2        | 0.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 99       | 19.26%  |
| 5.15    | 60       | 11.67%  |
| 5.11    | 38       | 7.39%   |
| 5.8     | 32       | 6.23%   |
| 4.15    | 31       | 6.03%   |
| 6.1     | 27       | 5.25%   |
| 5.13    | 25       | 4.86%   |
| 6.2     | 23       | 4.47%   |
| 5.10    | 22       | 4.28%   |
| 5.19    | 17       | 3.31%   |
| 4.18    | 17       | 3.31%   |
| 5.3     | 16       | 3.11%   |
| 6.4     | 12       | 2.33%   |
| 5.16    | 12       | 2.33%   |
| 6.5     | 11       | 2.14%   |
| 6.6     | 9        | 1.75%   |
| 5.0     | 9        | 1.75%   |
| 5.6     | 5        | 0.97%   |
| 5.17    | 5        | 0.97%   |
| 4.9     | 5        | 0.97%   |
| 4.4     | 5        | 0.97%   |
| 6.0     | 4        | 0.78%   |
| 5.18    | 4        | 0.78%   |
| 5.14    | 4        | 0.78%   |
| 5.12    | 4        | 0.78%   |
| 5.9     | 3        | 0.58%   |
| 4.19    | 3        | 0.58%   |
| 6.8     | 2        | 0.39%   |
| 6.7     | 2        | 0.39%   |
| 6.3     | 2        | 0.39%   |
| 5.5     | 2        | 0.39%   |
| 5.1     | 1        | 0.19%   |
| 3.16    | 1        | 0.19%   |
| 3.13    | 1        | 0.19%   |
| 3.10    | 1        | 0.19%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 439      | 97.12%  |
| i686   | 13       | 2.88%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 213      | 45.03%  |
| KDE5            | 85       | 17.97%  |
| Unknown         | 55       | 11.63%  |
| X-Cinnamon      | 37       | 7.82%   |
| XFCE            | 32       | 6.77%   |
| KDE             | 11       | 2.33%   |
| MATE            | 8        | 1.69%   |
| LXQt            | 6        | 1.27%   |
| Unity           | 5        | 1.06%   |
| LXDE            | 3        | 0.63%   |
| KDE4            | 3        | 0.63%   |
| i3              | 3        | 0.63%   |
| Cinnamon        | 3        | 0.63%   |
| KDE6            | 2        | 0.42%   |
| trinity         | 1        | 0.21%   |
| Pantheon        | 1        | 0.21%   |
| Hyprland        | 1        | 0.21%   |
| GNOME Flashback | 1        | 0.21%   |
| GNOME Classic   | 1        | 0.21%   |
| Budgie          | 1        | 0.21%   |
| awesome         | 1        | 0.21%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 364      | 77.61%  |
| Wayland | 66       | 14.07%  |
| Unknown | 23       | 4.9%    |
| Tty     | 15       | 3.2%    |
| Web     | 1        | 0.21%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 285      | 60.77%  |
| SDDM    | 65       | 13.86%  |
| GDM3    | 57       | 12.15%  |
| LightDM | 32       | 6.82%   |
| GDM     | 17       | 3.62%   |
| TDM     | 10       | 2.13%   |
| KDM     | 3        | 0.64%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_ZA   | 292      | 61.22%  |
| en_US   | 100      | 20.96%  |
| Unknown | 43       | 9.01%   |
| en_GB   | 22       | 4.61%   |
| C       | 10       | 2.1%    |
| en_ZW   | 6        | 1.26%   |
| af_ZA   | 2        | 0.42%   |
| en_BW   | 1        | 0.21%   |
| C.UTF8  | 1        | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 312      | 67.39%  |
| EFI  | 151      | 32.61%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 359      | 76.06%  |
| Btrfs   | 32       | 6.78%   |
| Overlay | 29       | 6.14%   |
| Tmpfs   | 21       | 4.45%   |
| Unknown | 15       | 3.18%   |
| Xfs     | 11       | 2.33%   |
| Zfs     | 3        | 0.64%   |
| Ext3    | 1        | 0.21%   |
| Ext2    | 1        | 0.21%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 291      | 62.85%  |
| GPT     | 126      | 27.21%  |
| MBR     | 46       | 9.94%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 385      | 82.8%   |
| Yes       | 80       | 17.2%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 320      | 69.57%  |
| Yes       | 140      | 30.43%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| MSI                 | 93       | 20.67%  |
| Gigabyte Technology | 74       | 16.44%  |
| ASUSTek Computer    | 74       | 16.44%  |
| Intel               | 46       | 10.22%  |
| Hewlett-Packard     | 30       | 6.67%   |
| Dell                | 27       | 6%      |
| ASRock              | 22       | 4.89%   |
| Lenovo              | 20       | 4.44%   |
| Biostar             | 17       | 3.78%   |
| Foxconn             | 16       | 3.56%   |
| Acer                | 6        | 1.33%   |
| Unknown             | 5        | 1.11%   |
| ECS                 | 4        | 0.89%   |
| Apple               | 4        | 0.89%   |
| Supermicro          | 3        | 0.67%   |
| NCR                 | 2        | 0.44%   |
| Fujitsu             | 2        | 0.44%   |
| Pegatron            | 1        | 0.22%   |
| Nvidia              | 1        | 0.22%   |
| Mustek6376 mst6376  | 1        | 0.22%   |
| Lite-On             | 1        | 0.22%   |
| IBM                 | 1        | 0.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| MSI MS-7817                 | 8        | 1.78%   |
| ASUS All Series             | 7        | 1.56%   |
| Gigabyte G31M-ES2C          | 6        | 1.33%   |
| Gigabyte H61M-DS2           | 5        | 1.11%   |
| Unknown                     | 5        | 1.11%   |
| MSI MS-7C37                 | 4        | 0.89%   |
| MSI MS-7B89                 | 4        | 0.89%   |
| MSI MS-7B84                 | 4        | 0.89%   |
| HP ProLiant MicroServer     | 4        | 0.89%   |
| Gigabyte B75M-D3H           | 4        | 0.89%   |
| ASUS TUF Gaming B550-PLUS   | 4        | 0.89%   |
| ASUS PRIME X570-P           | 4        | 0.89%   |
| Apple MacPro3,1             | 4        | 0.89%   |
| MSI MS-7B79                 | 3        | 0.67%   |
| MSI MS-7A15                 | 3        | 0.67%   |
| MSI MS-7756                 | 3        | 0.67%   |
| Intel Mecer_X102            | 3        | 0.67%   |
| HP Compaq 8200 Elite SFF PC | 3        | 0.67%   |
| Gigabyte X58A-UD3R          | 3        | 0.67%   |
| Gigabyte H61M-S2PV          | 3        | 0.67%   |
| Gigabyte G41MT-S2PT         | 3        | 0.67%   |
| Dell Vostro 3670            | 3        | 0.67%   |
| Dell OptiPlex 9010          | 3        | 0.67%   |
| Dell OptiPlex 7040          | 3        | 0.67%   |
| ASUS P5KPL-AM SE            | 3        | 0.67%   |
| MSI MS-7D22                 | 2        | 0.44%   |
| MSI MS-7C91                 | 2        | 0.44%   |
| MSI MS-7C56                 | 2        | 0.44%   |
| MSI MS-7B48                 | 2        | 0.44%   |
| MSI MS-7971                 | 2        | 0.44%   |
| MSI MS-7970                 | 2        | 0.44%   |
| MSI MS-7885                 | 2        | 0.44%   |
| MSI MS-7816                 | 2        | 0.44%   |
| MSI MS-7788                 | 2        | 0.44%   |
| MSI MS-7693                 | 2        | 0.44%   |
| MSI MS-7680                 | 2        | 0.44%   |
| MSI MS-7612                 | 2        | 0.44%   |
| MSI MS-7528                 | 2        | 0.44%   |
| Intel PROLINE               | 2        | 0.44%   |
| Intel H81                   | 2        | 0.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell OptiPlex       | 20       | 4.44%   |
| Lenovo ThinkCentre  | 19       | 4.22%   |
| ASUS PRIME          | 14       | 3.11%   |
| HP Compaq           | 13       | 2.89%   |
| MSI MS-7817         | 8        | 1.78%   |
| HP ProLiant         | 7        | 1.56%   |
| ASUS All            | 7        | 1.56%   |
| Gigabyte G31M-ES2C  | 6        | 1.33%   |
| ASUS TUF            | 6        | 1.33%   |
| Gigabyte H61M-DS2   | 5        | 1.11%   |
| Unknown             | 5        | 1.11%   |
| MSI MS-7C37         | 4        | 0.89%   |
| MSI MS-7B89         | 4        | 0.89%   |
| MSI MS-7B84         | 4        | 0.89%   |
| Intel Mecer         | 4        | 0.89%   |
| Intel DH61WW        | 4        | 0.89%   |
| Gigabyte B75M-D3H   | 4        | 0.89%   |
| Dell Vostro         | 4        | 0.89%   |
| ASUS ROG            | 4        | 0.89%   |
| Apple MacPro3       | 4        | 0.89%   |
| MSI MS-7B79         | 3        | 0.67%   |
| MSI MS-7A15         | 3        | 0.67%   |
| MSI MS-7756         | 3        | 0.67%   |
| Intel PROLINE       | 3        | 0.67%   |
| Intel DH55TC        | 3        | 0.67%   |
| Gigabyte X58A-UD3R  | 3        | 0.67%   |
| Gigabyte H61M-S2PV  | 3        | 0.67%   |
| Gigabyte G41MT-S2PT | 3        | 0.67%   |
| ASUS SABERTOOTH     | 3        | 0.67%   |
| ASUS P8H61-M        | 3        | 0.67%   |
| ASUS P5KPL-AM       | 3        | 0.67%   |
| ASUS P5G41T-M       | 3        | 0.67%   |
| ASUS H110M-K        | 3        | 0.67%   |
| Acer Veriton        | 3        | 0.67%   |
| Acer Aspire         | 3        | 0.67%   |
| MSI MS-7D22         | 2        | 0.44%   |
| MSI MS-7C91         | 2        | 0.44%   |
| MSI MS-7C56         | 2        | 0.44%   |
| MSI MS-7B48         | 2        | 0.44%   |
| MSI MS-7971         | 2        | 0.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 62       | 13.78%  |
| 2011 | 49       | 10.89%  |
| 2013 | 40       | 8.89%   |
| 2010 | 33       | 7.33%   |
| 2008 | 31       | 6.89%   |
| 2009 | 29       | 6.44%   |
| 2018 | 28       | 6.22%   |
| 2017 | 26       | 5.78%   |
| 2016 | 23       | 5.11%   |
| 2014 | 23       | 5.11%   |
| 2007 | 22       | 4.89%   |
| 2019 | 19       | 4.22%   |
| 2015 | 19       | 4.22%   |
| 2020 | 17       | 3.78%   |
| 2021 | 9        | 2%      |
| 2006 | 8        | 1.78%   |
| 2022 | 6        | 1.33%   |
| 2005 | 3        | 0.67%   |
| 2024 | 1        | 0.22%   |
| 2023 | 1        | 0.22%   |
| 2004 | 1        | 0.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 450      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 442      | 98%     |
| Enabled  | 9        | 2%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 450      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 103      | 22.39%  |
| 16.01-24.0  | 94       | 20.43%  |
| 3.01-4.0    | 90       | 19.57%  |
| 4.01-8.0    | 82       | 17.83%  |
| 32.01-64.0  | 37       | 8.04%   |
| 1.01-2.0    | 29       | 6.3%    |
| 24.01-32.0  | 10       | 2.17%   |
| 64.01-256.0 | 7        | 1.52%   |
| 2.01-3.0    | 4        | 0.87%   |
| 0.51-1.0    | 4        | 0.87%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 209      | 41.3%   |
| 2.01-3.0    | 105      | 20.75%  |
| 4.01-8.0    | 76       | 15.02%  |
| 3.01-4.0    | 47       | 9.29%   |
| 0.51-1.0    | 37       | 7.31%   |
| 8.01-16.0   | 17       | 3.36%   |
| 0.01-0.5    | 9        | 1.78%   |
| 16.01-24.0  | 3        | 0.59%   |
| 32.01-64.0  | 1        | 0.2%    |
| 64.01-256.0 | 1        | 0.2%    |
| Unknown     | 1        | 0.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 175      | 36.46%  |
| 2       | 142      | 29.58%  |
| 3       | 78       | 16.25%  |
| 4       | 52       | 10.83%  |
| 5       | 9        | 1.88%   |
| 7       | 8        | 1.67%   |
| 6       | 6        | 1.25%   |
| 8       | 4        | 0.83%   |
| 0       | 4        | 0.83%   |
| 14      | 1        | 0.21%   |
| Unknown | 1        | 0.21%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 272      | 58.87%  |
| Yes       | 190      | 41.13%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 441      | 98%     |
| No        | 9        | 2%      |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 289      | 63.24%  |
| Yes       | 168      | 36.76%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 380      | 81.72%  |
| Yes       | 85       | 18.28%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| South Africa | 450      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Johannesburg     | 120      | 25.26%  |
| Cape Town        | 110      | 23.16%  |
| Pretoria         | 64       | 13.47%  |
| Durban           | 29       | 6.11%   |
| Centurion        | 18       | 3.79%   |
| Benoni           | 8        | 1.68%   |
| Port Elizabeth   | 7        | 1.47%   |
| Kempton Park     | 7        | 1.47%   |
| Alberton         | 6        | 1.26%   |
| Bloemfontein     | 5        | 1.05%   |
| Sasolburg        | 4        | 0.84%   |
| Randburg         | 4        | 0.84%   |
| Pietermaritzburg | 4        | 0.84%   |
| Midrand          | 4        | 0.84%   |
| Bellville        | 4        | 0.84%   |
| Stellenbosch     | 3        | 0.63%   |
| Sandton          | 3        | 0.63%   |
| George           | 3        | 0.63%   |
| East London      | 3        | 0.63%   |
| Boksburg         | 3        | 0.63%   |
| Westville        | 2        | 0.42%   |
| Vanderbijlpark   | 2        | 0.42%   |
| Roodepoort       | 2        | 0.42%   |
| Plettenberg Bay  | 2        | 0.42%   |
| Paarl            | 2        | 0.42%   |
| Oudtshoorn       | 2        | 0.42%   |
| Nelspruit        | 2        | 0.42%   |
| Germiston        | 2        | 0.42%   |
| Edenvale         | 2        | 0.42%   |
| Durbanville      | 2        | 0.42%   |
| Zeerust          | 1        | 0.21%   |
| Welkom           | 1        | 0.21%   |
| Vredenburg       | 1        | 0.21%   |
| Vaalpark         | 1        | 0.21%   |
| Upington         | 1        | 0.21%   |
| Uitenhage        | 1        | 0.21%   |
| Thabazimbi       | 1        | 0.21%   |
| Struisbaai       | 1        | 0.21%   |
| Soweto           | 1        | 0.21%   |
| Somerset West    | 1        | 0.21%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| Seagate               | 244      | 468    | 29.79%  |
| WDC                   | 198      | 313    | 24.18%  |
| Samsung Electronics   | 97       | 149    | 11.84%  |
| Toshiba               | 39       | 52     | 4.76%   |
| Hitachi               | 33       | 51     | 4.03%   |
| Silicon Motion        | 15       | 19     | 1.83%   |
| Kingston              | 15       | 19     | 1.83%   |
| Crucial               | 15       | 17     | 1.83%   |
| Sandisk               | 13       | 15     | 1.59%   |
| Transcend             | 12       | 19     | 1.47%   |
| A-DATA Technology     | 12       | 15     | 1.47%   |
| Hewlett-Packard       | 11       | 19     | 1.34%   |
| Rogueware             | 7        | 10     | 0.85%   |
| HS-SSD-C100           | 7        | 10     | 0.85%   |
| TO Exter              | 6        | 7      | 0.73%   |
| Mushkin               | 6        | 6      | 0.73%   |
| Maxtor                | 6        | 7      | 0.73%   |
| HGST                  | 6        | 7      | 0.73%   |
| Kingmax               | 5        | 6      | 0.61%   |
| Hikvision             | 5        | 6      | 0.61%   |
| SK hynix              | 4        | 4      | 0.49%   |
| Phison                | 4        | 6      | 0.49%   |
| Intel                 | 4        | 5      | 0.49%   |
| HS-SSD-E100           | 4        | 6      | 0.49%   |
| Corsair               | 4        | 6      | 0.49%   |
| China                 | 4        | 5      | 0.49%   |
| OCZ                   | 3        | 5      | 0.37%   |
| Unknown               | 2        | 3      | 0.24%   |
| Realtek Semiconductor | 2        | 2      | 0.24%   |
| Phison Electronics    | 2        | 6      | 0.24%   |
| Patriot               | 2        | 2      | 0.24%   |
| Lexar                 | 2        | 3      | 0.24%   |
| Gigabyte Technology   | 2        | 2      | 0.24%   |
| External              | 2        | 3      | 0.24%   |
| XPG                   | 1        | 1      | 0.12%   |
| USB                   | 1        | 1      | 0.12%   |
| StoreJet              | 1        | 1      | 0.12%   |
| SOLIDATA              | 1        | 1      | 0.12%   |
| Seagate Technology    | 1        | 3      | 0.12%   |
| Plextor               | 1        | 2      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 35       | 3.53%   |
| Seagate ST3500418AS 500GB        | 22       | 2.22%   |
| WDC WD10EZEX-08WN4A0 1TB         | 12       | 1.21%   |
| Seagate ST380815AS 80GB          | 12       | 1.21%   |
| Seagate ST3500413AS 500GB        | 12       | 1.21%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 10       | 1.01%   |
| Seagate ST3250318AS 250GB        | 10       | 1.01%   |
| Samsung HD103SI 1TB              | 10       | 1.01%   |
| Seagate ST4000DM004-2CV104 4TB   | 9        | 0.91%   |
| Seagate ST4000DM000-1F2168 4TB   | 9        | 0.91%   |
| Seagate ST2000DM001-1CH164 2TB   | 9        | 0.91%   |
| Seagate ST1000DM010-2EP102 1TB   | 9        | 0.91%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 8        | 0.81%   |
| Seagate ST1000DM003-1CH162 1TB   | 8        | 0.81%   |
| Samsung HD502HI 500GB            | 8        | 0.81%   |
| WDC WD20EARX-00PASB0 2TB         | 7        | 0.71%   |
| Seagate ST3160815AS 160GB        | 7        | 0.71%   |
| Seagate ST31500341AS 1TB         | 7        | 0.71%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 6        | 0.61%   |
| WDC WD20EZRX-00D8PB0 2TB         | 6        | 0.61%   |
| WDC WD10EZEX-00BN5A0 1TB         | 6        | 0.61%   |
| Toshiba HDWD110 1TB              | 6        | 0.61%   |
| Toshiba DT01ACA100 1TB           | 6        | 0.61%   |
| TO Exter nal USB 3.0 500GB       | 6        | 0.61%   |
| Seagate ST31000528AS 1TB         | 6        | 0.61%   |
| Samsung SSD 850 EVO 250GB        | 6        | 0.61%   |
| Samsung SSD 750 EVO 250GB        | 6        | 0.61%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 5        | 0.5%    |
| WDC WD10EZEX-00WN4A0 1TB         | 5        | 0.5%    |
| WDC WD10EZEX-00MFCA0 1TB         | 5        | 0.5%    |
| Seagate ST3320620AS 320GB        | 5        | 0.5%    |
| Seagate ST3250310AS 250GB        | 5        | 0.5%    |
| Seagate ST31000524AS 1TB         | 5        | 0.5%    |
| Seagate ST1000DM003-1ER162 1TB   | 5        | 0.5%    |
| Seagate Expansion+ Desk 4TB      | 5        | 0.5%    |
| Samsung HM321HI 320GB            | 5        | 0.5%    |
| WDC WDS240G2G0A-00JH30 240GB SSD | 4        | 0.4%    |
| WDC WD5000AZRX-00A8LB0 500GB     | 4        | 0.4%    |
| WDC WD40EZRZ-00GXCB0 4TB         | 4        | 0.4%    |
| WDC WD30EZRZ-00Z5HB0 3TB         | 4        | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 239      | 454    | 41.86%  |
| WDC                 | 177      | 273    | 31%     |
| Samsung Electronics | 52       | 71     | 9.11%   |
| Toshiba             | 38       | 51     | 6.65%   |
| Hitachi             | 33       | 51     | 5.78%   |
| Hewlett-Packard     | 8        | 16     | 1.4%    |
| TO Exter            | 6        | 7      | 1.05%   |
| Maxtor              | 6        | 7      | 1.05%   |
| HGST                | 6        | 7      | 1.05%   |
| Unknown             | 2        | 3      | 0.35%   |
| USB                 | 1        | 1      | 0.18%   |
| StoreJet            | 1        | 1      | 0.18%   |
| HPE                 | 1        | 2      | 0.18%   |
| Fujitsu             | 1        | 1      | 0.18%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 33       | 49     | 18.97%  |
| WDC                 | 32       | 40     | 18.39%  |
| Crucial             | 15       | 17     | 8.62%   |
| Kingston            | 12       | 13     | 6.9%    |
| Transcend           | 11       | 17     | 6.32%   |
| A-DATA Technology   | 11       | 14     | 6.32%   |
| Rogueware           | 7        | 10     | 4.02%   |
| SanDisk             | 6        | 6      | 3.45%   |
| Kingmax             | 5        | 6      | 2.87%   |
| China               | 4        | 5      | 2.3%    |
| OCZ                 | 3        | 5      | 1.72%   |
| Mushkin             | 3        | 3      | 1.72%   |
| SK hynix            | 2        | 2      | 1.15%   |
| Patriot             | 2        | 2      | 1.15%   |
| HS-SSD-E100         | 2        | 2      | 1.15%   |
| HS-SSD-C100         | 2        | 2      | 1.15%   |
| External            | 2        | 3      | 1.15%   |
| Corsair             | 2        | 4      | 1.15%   |
| XPG                 | 1        | 1      | 0.57%   |
| Toshiba             | 1        | 1      | 0.57%   |
| SOLIDATA            | 1        | 1      | 0.57%   |
| Seagate             | 1        | 1      | 0.57%   |
| Plextor             | 1        | 2      | 0.57%   |
| Micron Technology   | 1        | 1      | 0.57%   |
| LITEON              | 1        | 1      | 0.57%   |
| Lexar               | 1        | 2      | 0.57%   |
| KingSpec            | 1        | 2      | 0.57%   |
| Kimtigo             | 1        | 1      | 0.57%   |
| Intel               | 1        | 1      | 0.57%   |
| Indilinx            | 1        | 1      | 0.57%   |
| Hewlett-Packard     | 1        | 1      | 0.57%   |
| Gigabyte Technology | 1        | 1      | 0.57%   |
| Biostar             | 1        | 1      | 0.57%   |
| ASMT                | 1        | 1      | 0.57%   |
| Apacer              | 1        | 2      | 0.57%   |
| AFOX                | 1        | 1      | 0.57%   |
| Acer                | 1        | 1      | 0.57%   |
| Unknown             | 1        | 1      | 0.57%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 381      | 945    | 63.18%  |
| SSD     | 142      | 224    | 23.55%  |
| NVMe    | 65       | 116    | 10.78%  |
| Unknown | 15       | 22     | 2.49%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 425      | 1130   | 81.57%  |
| NVMe | 65       | 116    | 12.48%  |
| SAS  | 31       | 61     | 5.95%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 340      | 624    | 51.28%  |
| 0.51-1.0   | 165      | 265    | 24.89%  |
| 1.01-2.0   | 82       | 132    | 12.37%  |
| 3.01-4.0   | 37       | 77     | 5.58%   |
| 2.01-3.0   | 23       | 31     | 3.47%   |
| 4.01-10.0  | 12       | 34     | 1.81%   |
| 10.01-20.0 | 4        | 6      | 0.6%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 109      | 22.15%  |
| 251-500        | 96       | 19.51%  |
| 501-1000       | 73       | 14.84%  |
| More than 3000 | 56       | 11.38%  |
| 1001-2000      | 51       | 10.37%  |
| 2001-3000      | 28       | 5.69%   |
| 1-20           | 28       | 5.69%   |
| 51-100         | 22       | 4.47%   |
| 21-50          | 15       | 3.05%   |
| Unknown        | 14       | 2.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 159      | 31.67%  |
| 21-50          | 79       | 15.74%  |
| 51-100         | 52       | 10.36%  |
| 101-250        | 49       | 9.76%   |
| 251-500        | 44       | 8.76%   |
| 501-1000       | 32       | 6.37%   |
| 1001-2000      | 31       | 6.18%   |
| More than 3000 | 29       | 5.78%   |
| Unknown        | 14       | 2.79%   |
| 2001-3000      | 13       | 2.59%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 6        | 6      | 8.45%   |
| Seagate ST3500418AS 500GB           | 5        | 6      | 7.04%   |
| WDC WD3200AAJS-00RYA0 320GB         | 2        | 2      | 2.82%   |
| WDC WD1600AAJS-08L7A0 160GB         | 2        | 2      | 2.82%   |
| WDC WD10EZEX-08WN4A0 1TB            | 2        | 2      | 2.82%   |
| Seagate ST4000DM004-2CV104 4TB      | 2        | 2      | 2.82%   |
| Seagate ST3000DM001-1CH166 3TB      | 2        | 2      | 2.82%   |
| WDC WD6400AAKS-75A7B0 640GB         | 1        | 1      | 1.41%   |
| WDC WD5000AVVS-63ZWB0 500GB         | 1        | 1      | 1.41%   |
| WDC WD5000AAKX-22ERMA0 500GB        | 1        | 1      | 1.41%   |
| WDC WD5000AAKX-221CA1 500GB         | 1        | 1      | 1.41%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 1        | 2      | 1.41%   |
| WDC WD3200AAJS-60Z0A0 320GB         | 1        | 1      | 1.41%   |
| WDC WD3200AAJS-60M0A1 320GB         | 1        | 1      | 1.41%   |
| WDC WD30PURX-64P6ZY0 3TB            | 1        | 1      | 1.41%   |
| WDC WD30EZRX-00MMMB0 3TB            | 1        | 3      | 1.41%   |
| WDC WD30EFRX-68EUZN0 3TB            | 1        | 1      | 1.41%   |
| WDC WD2500BEVS-60UST0 250GB         | 1        | 1      | 1.41%   |
| WDC WD2500AAKX-75U6AA0 250GB        | 1        | 1      | 1.41%   |
| WDC WD2500AAJS-75M0A0 250GB         | 1        | 1      | 1.41%   |
| WDC WD20EZRZ-00Z5HB0 2TB            | 1        | 1      | 1.41%   |
| WDC WD20EFRX-68EUZN0 2TB            | 1        | 2      | 1.41%   |
| WDC WD20EARX-00PASB0 2TB            | 1        | 1      | 1.41%   |
| WDC WD15EADS-00P8B0 1TB             | 1        | 1      | 1.41%   |
| WDC WD10EVDS-63N5B1 1TB             | 1        | 2      | 1.41%   |
| WDC WD10EFRX-68PJCN0 1TB            | 1        | 1      | 1.41%   |
| WDC WD10EADS-67M2B0 1TB             | 1        | 2      | 1.41%   |
| WDC WD10EACS-00ZJB0 1TB             | 1        | 1      | 1.41%   |
| Transcend TS64GSSD720 64GB          | 1        | 1      | 1.41%   |
| TO Exter nal USB 3.0 500GB          | 1        | 1      | 1.41%   |
| SOLIDATA SSD 120GB                  | 1        | 1      | 1.41%   |
| Seagate ST500LM021-1KJ152 500GB     | 1        | 1      | 1.41%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1        | 1      | 1.41%   |
| Seagate ST500DM002-1BC142 500GB     | 1        | 1      | 1.41%   |
| Seagate ST4000DM000-1F2168 4TB      | 1        | 9      | 1.41%   |
| Seagate ST3500413AS 500GB           | 1        | 1      | 1.41%   |
| Seagate ST3320418AS 320GB           | 1        | 3      | 1.41%   |
| Seagate ST3250310AS 250GB           | 1        | 1      | 1.41%   |
| Seagate ST320LT007-9ZV142 320GB     | 1        | 1      | 1.41%   |
| Seagate ST320LM010-1KJ15C 320GB     | 1        | 1      | 1.41%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 29       | 44     | 42.65%  |
| WDC                 | 26       | 33     | 38.24%  |
| Samsung Electronics | 3        | 4      | 4.41%   |
| Hitachi             | 3        | 3      | 4.41%   |
| Hewlett-Packard     | 2        | 2      | 2.94%   |
| Transcend           | 1        | 1      | 1.47%   |
| TO Exter            | 1        | 1      | 1.47%   |
| SOLIDATA            | 1        | 1      | 1.47%   |
| Indilinx            | 1        | 1      | 1.47%   |
| HGST                | 1        | 1      | 1.47%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 29       | 44     | 45.31%  |
| WDC                 | 26       | 33     | 40.63%  |
| Samsung Electronics | 3        | 4      | 4.69%   |
| Hitachi             | 3        | 3      | 4.69%   |
| TO Exter            | 1        | 1      | 1.56%   |
| HGST                | 1        | 1      | 1.56%   |
| Hewlett-Packard     | 1        | 1      | 1.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 51       | 87     | 92.73%  |
| SSD  | 3        | 3      | 5.45%   |
| NVMe | 1        | 1      | 1.82%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Desktops | Drives | Percent |
|--------------------------|----------|--------|---------|
| WDC WD20EZRX-00D8PB0 2TB | 2        | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 2        | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 326      | 908    | 64.81%  |
| Works    | 122      | 306    | 24.25%  |
| Malfunc  | 53       | 91     | 10.54%  |
| Failed   | 2        | 2      | 0.4%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 356      | 61.27%  |
| AMD                              | 82       | 14.11%  |
| Silicon Motion                   | 20       | 3.44%   |
| Samsung Electronics              | 19       | 3.27%   |
| Marvell Technology Group         | 15       | 2.58%   |
| ASMedia Technology               | 15       | 2.58%   |
| JMicron Technology               | 14       | 2.41%   |
| Phison Electronics               | 11       | 1.89%   |
| Nvidia                           | 9        | 1.55%   |
| SanDisk                          | 7        | 1.2%    |
| Kingston Technology Company      | 4        | 0.69%   |
| VIA Technologies                 | 3        | 0.52%   |
| Silicon Image                    | 3        | 0.52%   |
| Seagate Technology               | 3        | 0.52%   |
| SK hynix                         | 2        | 0.34%   |
| Silicon Integrated Systems [SiS] | 2        | 0.34%   |
| Realtek Semiconductor            | 2        | 0.34%   |
| INNOGRIT                         | 2        | 0.34%   |
| Broadcom / LSI                   | 2        | 0.34%   |
| Adaptec                          | 2        | 0.34%   |
| Micron/Crucial Technology        | 1        | 0.17%   |
| MAXIO Technology (Hangzhou)      | 1        | 0.17%   |
| LSI Logic / Symbios Logic        | 1        | 0.17%   |
| Lite-On Technology               | 1        | 0.17%   |
| KIOXIA                           | 1        | 0.17%   |
| HighPoint Technologies           | 1        | 0.17%   |
| Hewlett-Packard                  | 1        | 0.17%   |
| ADATA Technology                 | 1        | 0.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 50       | 6.31%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 43       | 5.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 42       | 5.3%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 37       | 4.67%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 37       | 4.67%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 33       | 4.17%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 32       | 4.04%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 30       | 3.79%   |
| Intel SATA Controller [RAID mode]                                                       | 24       | 3.03%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 22       | 2.78%   |
| AMD 400 Series Chipset SATA Controller                                                  | 18       | 2.27%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 17       | 2.15%   |
| AMD 500 Series Chipset SATA Controller                                                  | 16       | 2.02%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 13       | 1.64%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 13       | 1.64%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 13       | 1.64%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 12       | 1.52%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 11       | 1.39%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 11       | 1.39%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 9        | 1.14%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 9        | 1.14%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 9        | 1.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 9        | 1.14%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 9        | 1.14%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8        | 1.01%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 8        | 1.01%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 8        | 1.01%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 8        | 1.01%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 7        | 0.88%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 7        | 0.88%   |
| Phison E12 NVMe Controller                                                              | 7        | 0.88%   |
| AMD FCH SATA Controller D                                                               | 7        | 0.88%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 6        | 0.76%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 6        | 0.76%   |
| AMD 300 Series Chipset SATA Controller                                                  | 6        | 0.76%   |
| JMicron JMB368 IDE controller                                                           | 5        | 0.63%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 5        | 0.63%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 5        | 0.63%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 5        | 0.63%   |
| Intel 631xESB/632xESB SATA AHCI Controller                                              | 5        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 284      | 49.13%  |
| IDE  | 182      | 31.49%  |
| NVMe | 67       | 11.59%  |
| RAID | 39       | 6.75%   |
| SAS  | 3        | 0.52%   |
| SCSI | 3        | 0.52%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 363      | 80.67%  |
| AMD    | 87       | 19.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 19       | 4.2%    |
| Intel Core i7-3770 CPU @ 3.40GHz            | 11       | 2.43%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 11       | 2.43%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 10       | 2.21%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 8        | 1.77%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 8        | 1.77%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 7        | 1.55%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 7        | 1.55%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 6        | 1.33%   |
| Intel Pentium 4 CPU 3.00GHz                 | 5        | 1.11%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 5        | 1.11%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 5        | 1.11%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 5        | 1.11%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 5        | 1.11%   |
| Intel Xeon CPU E5462 @ 2.80GHz              | 4        | 0.88%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 4        | 0.88%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 4        | 0.88%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 4        | 0.88%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 4        | 0.88%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 4        | 0.88%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 4        | 0.88%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 4        | 0.88%   |
| Intel Core i3 CPU 530 @ 2.93GHz             | 4        | 0.88%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 4        | 0.88%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 4        | 0.88%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 4        | 0.88%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 4        | 0.88%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 4        | 0.88%   |
| AMD Ryzen 5 3600 6-Core Processor           | 4        | 0.88%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 3        | 0.66%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 3        | 0.66%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 3        | 0.66%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 3        | 0.66%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 3        | 0.66%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 3        | 0.66%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 3        | 0.66%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 3        | 0.66%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 3        | 0.66%   |
| Intel Core i7 CPU 870 @ 2.93GHz             | 3        | 0.66%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 3        | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 93       | 20.62%  |
| Intel Core i7           | 68       | 15.08%  |
| Intel Core i3           | 57       | 12.64%  |
| AMD Ryzen 5             | 31       | 6.87%   |
| Intel Core 2 Duo        | 30       | 6.65%   |
| Intel Pentium           | 24       | 5.32%   |
| Intel Celeron           | 19       | 4.21%   |
| Intel Xeon              | 17       | 3.77%   |
| Intel Core 2 Quad       | 14       | 3.1%    |
| AMD Ryzen 7             | 12       | 2.66%   |
| Intel Pentium Dual-Core | 11       | 2.44%   |
| AMD Ryzen 9             | 10       | 2.22%   |
| Other                   | 8        | 1.77%   |
| Intel Pentium Dual      | 7        | 1.55%   |
| Intel Pentium 4         | 7        | 1.55%   |
| AMD FX                  | 7        | 1.55%   |
| AMD Ryzen 3             | 6        | 1.33%   |
| AMD Turion II Neo       | 4        | 0.89%   |
| Intel Pentium D         | 3        | 0.67%   |
| Intel Core 2            | 3        | 0.67%   |
| AMD Athlon 64 X2        | 3        | 0.67%   |
| AMD Ryzen 7 PRO         | 2        | 0.44%   |
| AMD Ryzen 5 PRO         | 2        | 0.44%   |
| AMD Phenom II X4        | 2        | 0.44%   |
| AMD Phenom II X2        | 2        | 0.44%   |
| Intel Genuine           | 1        | 0.22%   |
| Intel Core 2 Extreme    | 1        | 0.22%   |
| Intel Celeron D         | 1        | 0.22%   |
| Intel Atom              | 1        | 0.22%   |
| AMD Ryzen Threadripper  | 1        | 0.22%   |
| AMD Phenom II X3        | 1        | 0.22%   |
| AMD Athlon 64           | 1        | 0.22%   |
| AMD A8                  | 1        | 0.22%   |
| AMD A12                 | 1        | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 184      | 40.8%   |
| 2      | 161      | 35.7%   |
| 6      | 48       | 10.64%  |
| 8      | 22       | 4.88%   |
| 1      | 17       | 3.77%   |
| 12     | 8        | 1.77%   |
| 16     | 7        | 1.55%   |
| 3      | 3        | 0.67%   |
| 24     | 1        | 0.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 443      | 98.44%  |
| 2      | 7        | 1.56%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 231      | 51.11%  |
| 2      | 221      | 48.89%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 442      | 97.79%  |
| Unknown        | 8        | 1.77%   |
| 32-bit         | 2        | 0.44%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 162      | 33.68%  |
| 0x306a9    | 45       | 9.36%   |
| 0x206a7    | 35       | 7.28%   |
| 0x306c3    | 29       | 6.03%   |
| 0x1067a    | 23       | 4.78%   |
| 0x506e3    | 21       | 4.37%   |
| 0x6fb      | 10       | 2.08%   |
| 0x10676    | 10       | 2.08%   |
| 0x906ea    | 9        | 1.87%   |
| 0x906e9    | 9        | 1.87%   |
| 0x6fd      | 9        | 1.87%   |
| 0x08701021 | 9        | 1.87%   |
| 0x20652    | 8        | 1.66%   |
| 0x106a5    | 7        | 1.46%   |
| 0x20655    | 5        | 1.04%   |
| 0x106e5    | 5        | 1.04%   |
| 0x0800820d | 5        | 1.04%   |
| 0x06000852 | 5        | 1.04%   |
| 0x010000db | 5        | 1.04%   |
| 0xa0653    | 4        | 0.83%   |
| 0x0a201016 | 4        | 0.83%   |
| 0x010000c8 | 4        | 0.83%   |
| 0x0a50000c | 3        | 0.62%   |
| 0x08600106 | 3        | 0.62%   |
| 0x08108109 | 3        | 0.62%   |
| 0x0600611a | 3        | 0.62%   |
| 0xf65      | 2        | 0.42%   |
| 0xf64      | 2        | 0.42%   |
| 0xf49      | 2        | 0.42%   |
| 0xf41      | 2        | 0.42%   |
| 0x906eb    | 2        | 0.42%   |
| 0x90672    | 2        | 0.42%   |
| 0x6f2      | 2        | 0.42%   |
| 0x206d7    | 2        | 0.42%   |
| 0x0a601203 | 2        | 0.42%   |
| 0x08001137 | 2        | 0.42%   |
| 0xf4a      | 1        | 0.21%   |
| 0xf47      | 1        | 0.21%   |
| 0xf43      | 1        | 0.21%   |
| 0xf33      | 1        | 0.21%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| IvyBridge        | 66       | 14.57%  |
| SandyBridge      | 55       | 12.14%  |
| Penryn           | 49       | 10.82%  |
| Haswell          | 45       | 9.93%   |
| KabyLake         | 33       | 7.28%   |
| Skylake          | 29       | 6.4%    |
| Core             | 29       | 6.4%    |
| Zen 2            | 20       | 4.42%   |
| Zen 3            | 18       | 3.97%   |
| Westmere         | 15       | 3.31%   |
| Nehalem          | 15       | 3.31%   |
| NetBurst         | 13       | 2.87%   |
| Zen+             | 11       | 2.43%   |
| Zen              | 11       | 2.43%   |
| K10              | 9        | 1.99%   |
| Unknown          | 9        | 1.99%   |
| Piledriver       | 7        | 1.55%   |
| CometLake        | 5        | 1.1%    |
| K8 Hammer        | 4        | 0.88%   |
| Alderlake Hybrid | 4        | 0.88%   |
| Excavator        | 3        | 0.66%   |
| Silvermont       | 1        | 0.22%   |
| Goldmont plus    | 1        | 0.22%   |
| Bonnell          | 1        | 0.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 192      | 40.25%  |
| Nvidia                           | 176      | 36.9%   |
| AMD                              | 100      | 20.96%  |
| Matrox Electronics Systems       | 6        | 1.26%   |
| VIA Technologies                 | 1        | 0.21%   |
| Silicon Motion                   | 1        | 0.21%   |
| Silicon Integrated Systems [SiS] | 1        | 0.21%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 33       | 6.82%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 29       | 5.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 26       | 5.37%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 23       | 4.75%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 20       | 4.13%   |
| Nvidia GT218 [GeForce 210]                                                  | 15       | 3.1%    |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 13       | 2.69%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 9        | 1.86%   |
| Intel Core Processor Integrated Graphics Controller                         | 9        | 1.86%   |
| Nvidia GF108 [GeForce GT 730]                                               | 8        | 1.65%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 7        | 1.45%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 6        | 1.24%   |
| Nvidia GK208B [GeForce GT 710]                                              | 6        | 1.24%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 6        | 1.24%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 6        | 1.24%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 5        | 1.03%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 5        | 1.03%   |
| Nvidia GF119 [GeForce GT 610]                                               | 5        | 1.03%   |
| Nvidia GF108 [GeForce GT 630]                                               | 5        | 1.03%   |
| Intel HD Graphics 630                                                       | 5        | 1.03%   |
| Intel HD Graphics 530                                                       | 5        | 1.03%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 5        | 1.03%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 5        | 1.03%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 4        | 0.83%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 0.83%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 4        | 0.83%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 4        | 0.83%   |
| Nvidia G96C [GeForce 9400 GT]                                               | 4        | 0.83%   |
| Nvidia G92 [GeForce GTS 250]                                                | 4        | 0.83%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4        | 0.83%   |
| Nvidia GT215 [GeForce GT 240]                                               | 3        | 0.62%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 3        | 0.62%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 3        | 0.62%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 3        | 0.62%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 3        | 0.62%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 3        | 0.62%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 3        | 0.62%   |
| Intel HD Graphics 610                                                       | 3        | 0.62%   |
| Intel HD Graphics 510                                                       | 3        | 0.62%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 3        | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Intel          | 168      | 37%     |
| 1 x Nvidia         | 162      | 35.68%  |
| 1 x AMD            | 87       | 19.16%  |
| Intel + Nvidia     | 10       | 2.2%    |
| 2 x AMD            | 6        | 1.32%   |
| 1 x Matrox         | 5        | 1.1%    |
| AMD + Nvidia       | 5        | 1.1%    |
| 2 x Intel          | 3        | 0.66%   |
| Other              | 2        | 0.44%   |
| Intel + AMD        | 2        | 0.44%   |
| 1 x VIA            | 1        | 0.22%   |
| 1 x SiS            | 1        | 0.22%   |
| 1 x Silicon Motion | 1        | 0.22%   |
| AMD + Matrox       | 1        | 0.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 345      | 74.84%  |
| Proprietary | 89       | 19.31%  |
| Unknown     | 27       | 5.86%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 255      | 53.8%   |
| 1.01-2.0   | 61       | 12.87%  |
| 0.51-1.0   | 46       | 9.7%    |
| 0.01-0.5   | 34       | 7.17%   |
| 3.01-4.0   | 32       | 6.75%   |
| 7.01-8.0   | 20       | 4.22%   |
| 5.01-6.0   | 13       | 2.74%   |
| 8.01-16.0  | 8        | 1.69%   |
| 2.01-3.0   | 3        | 0.63%   |
| 16.01-24.0 | 2        | 0.42%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 130      | 28.7%   |
| Dell                 | 89       | 19.65%  |
| Goldstar             | 65       | 14.35%  |
| Philips              | 14       | 3.09%   |
| Hewlett-Packard      | 14       | 3.09%   |
| AOC                  | 13       | 2.87%   |
| Unknown              | 11       | 2.43%   |
| BenQ                 | 11       | 2.43%   |
| Acer                 | 9        | 1.99%   |
| LG Electronics       | 8        | 1.77%   |
| VIE                  | 7        | 1.55%   |
| ViewSonic            | 5        | 1.1%    |
| Lenovo               | 5        | 1.1%    |
| Toshiba              | 4        | 0.88%   |
| Plain Tree Systems   | 4        | 0.88%   |
| Hitachi              | 4        | 0.88%   |
| Fujitsu Siemens      | 4        | 0.88%   |
| Ancor Communications | 4        | 0.88%   |
| SKY                  | 3        | 0.66%   |
| PRI                  | 3        | 0.66%   |
| MECER                | 3        | 0.66%   |
| Unknown              | 3        | 0.66%   |
| ___                  | 2        | 0.44%   |
| Sony                 | 2        | 0.44%   |
| Sampo                | 2        | 0.44%   |
| Panasonic            | 2        | 0.44%   |
| Onkyo                | 2        | 0.44%   |
| NEC Computers        | 2        | 0.44%   |
| CTV                  | 2        | 0.44%   |
| Wacom                | 1        | 0.22%   |
| TopView              | 1        | 0.22%   |
| TEO                  | 1        | 0.22%   |
| Tatung               | 1        | 0.22%   |
| STD                  | 1        | 0.22%   |
| SBI                  | 1        | 0.22%   |
| RXT                  | 1        | 0.22%   |
| RTK                  | 1        | 0.22%   |
| PKB                  | 1        | 0.22%   |
| Packard Bell         | 1        | 0.22%   |
| MStar                | 1        | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Dell SE2416H DELD081 1920x1080 527x296mm 23.8-inch                   | 8        | 1.63%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 6        | 1.22%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 6        | 1.22%   |
| Dell SE2416H DELD082 1920x1080 527x296mm 23.8-inch                   | 6        | 1.22%   |
| Dell SE2216H DELF071 1920x1080 476x268mm 21.5-inch                   | 5        | 1.02%   |
| Dell SE2717H/HX DELD0A1 1920x1080 598x336mm 27.0-inch                | 4        | 0.81%   |
| Dell S2340L DELD058 1920x1080 509x286mm 23.0-inch                    | 4        | 0.81%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch   | 3        | 0.61%   |
| Samsung Electronics SMBX2450 SAM0722 1920x1080 531x299mm 24.0-inch   | 3        | 0.61%   |
| Samsung Electronics SMBX2031 SAM076B 1600x900 443x249mm 20.0-inch    | 3        | 0.61%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch    | 3        | 0.61%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch     | 3        | 0.61%   |
| Samsung Electronics S19C150 SAM0AE6 1366x768 410x230mm 18.5-inch     | 3        | 0.61%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1080                 | 3        | 0.61%   |
| Goldstar W2443 GSM571B 1920x1080 474x296mm 22.0-inch                 | 3        | 0.61%   |
| Goldstar HD PLUS GSM5AC5 1600x900 440x250mm 19.9-inch                | 3        | 0.61%   |
| Goldstar E1951 GSM4BFD 1366x768 410x230mm 18.5-inch                  | 3        | 0.61%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                | 3        | 0.61%   |
| Dell SE2719H DELF10C 1920x1080 598x336mm 27.0-inch                   | 3        | 0.61%   |
| Dell E1916HV DELF06C 1366x768 409x230mm 18.5-inch                    | 3        | 0.61%   |
| Unknown                                                              | 3        | 0.61%   |
| ___ LCD Monitor ___A770 1280x1024 320x240mm 15.7-inch                | 2        | 0.41%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch               | 2        | 0.41%   |
| VIE S20W VIE2080 1600x900 443x249mm 20.0-inch                        | 2        | 0.41%   |
| Unknown LCD Monitor XXX AAA 1920x1080                                | 2        | 0.41%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                | 2        | 0.41%   |
| Toshiba LCD-MONITOR LCDEC80 1680x1050 470x300mm 22.0-inch            | 2        | 0.41%   |
| Samsung Electronics SyncMaster SAM058F 1920x1080 477x268mm 21.5-inch | 2        | 0.41%   |
| Samsung Electronics SyncMaster SAM058E 1920x1080 477x268mm 21.5-inch | 2        | 0.41%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch | 2        | 0.41%   |
| Samsung Electronics SyncMaster SAM0272 1280x1024 338x270mm 17.0-inch | 2        | 0.41%   |
| Samsung Electronics SyncMaster SAM0117 1280x1024 312x234mm 15.4-inch | 2        | 0.41%   |
| Samsung Electronics SMBX2031 SAM076A 1600x900 443x249mm 20.0-inch    | 2        | 0.41%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch   | 2        | 0.41%   |
| Samsung Electronics SMB2330H SAM0649 1920x1080 509x286mm 23.0-inch   | 2        | 0.41%   |
| Samsung Electronics SMB2230 SAM063F 1920x1080 477x268mm 21.5-inch    | 2        | 0.41%   |
| Samsung Electronics S27B550 SAM091A 1920x1080 598x336mm 27.0-inch    | 2        | 0.41%   |
| Samsung Electronics S23B370 SAM089B 1920x1080 510x287mm 23.0-inch    | 2        | 0.41%   |
| Samsung Electronics S23B300 SAM08AF 1920x1080 510x287mm 23.0-inch    | 2        | 0.41%   |
| Samsung Electronics S23B300 SAM08AE 1920x1080 510x287mm 23.0-inch    | 2        | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 181      | 40.31%  |
| 1600x900 (HD+)     | 42       | 9.35%   |
| 1280x1024 (SXGA)   | 37       | 8.24%   |
| 1366x768 (WXGA)    | 35       | 7.8%    |
| 3840x2160 (4K)     | 26       | 5.79%   |
| 1440x900 (WXGA+)   | 19       | 4.23%   |
| 1680x1050 (WSXGA+) | 18       | 4.01%   |
| 2560x1440 (QHD)    | 17       | 3.79%   |
| 1360x768           | 15       | 3.34%   |
| 1024x768 (XGA)     | 10       | 2.23%   |
| Unknown            | 10       | 2.23%   |
| 2560x1080          | 8        | 1.78%   |
| 1920x540           | 4        | 0.89%   |
| 1920x1200 (WUXGA)  | 4        | 0.89%   |
| 3840x1080          | 3        | 0.67%   |
| 1152x864           | 3        | 0.67%   |
| 5120x1080          | 2        | 0.45%   |
| 4480x1080          | 2        | 0.45%   |
| 3440x1440          | 2        | 0.45%   |
| 1600x1200          | 2        | 0.45%   |
| 720x480            | 1        | 0.22%   |
| 4880x1080          | 1        | 0.22%   |
| 4480x1440          | 1        | 0.22%   |
| 3360x1080          | 1        | 0.22%   |
| 3286x1080          | 1        | 0.22%   |
| 3280x1200          | 1        | 0.22%   |
| 2048x1536          | 1        | 0.22%   |
| 1400x1050          | 1        | 0.22%   |
| 1280x720 (HD)      | 1        | 0.22%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 55       | 12.09%  |
| 21      | 44       | 9.67%   |
| 24      | 43       | 9.45%   |
| 19      | 43       | 9.45%   |
| Unknown | 43       | 9.45%   |
| 18      | 37       | 8.13%   |
| 27      | 36       | 7.91%   |
| 20      | 32       | 7.03%   |
| 22      | 17       | 3.74%   |
| 17      | 17       | 3.74%   |
| 15      | 14       | 3.08%   |
| 31      | 13       | 2.86%   |
| 34      | 9        | 1.98%   |
| 84      | 6        | 1.32%   |
| 40      | 6        | 1.32%   |
| 52      | 5        | 1.1%    |
| 48      | 4        | 0.88%   |
| 32      | 4        | 0.88%   |
| 13      | 4        | 0.88%   |
| 72      | 3        | 0.66%   |
| 25      | 3        | 0.66%   |
| 63      | 2        | 0.44%   |
| 54      | 2        | 0.44%   |
| 46      | 2        | 0.44%   |
| 26      | 2        | 0.44%   |
| 97      | 1        | 0.22%   |
| 67      | 1        | 0.22%   |
| 64      | 1        | 0.22%   |
| 49      | 1        | 0.22%   |
| 44      | 1        | 0.22%   |
| 43      | 1        | 0.22%   |
| 39      | 1        | 0.22%   |
| 28      | 1        | 0.22%   |
| 14      | 1        | 0.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 151      | 34.71%  |
| 501-600        | 125      | 28.74%  |
| Unknown        | 43       | 9.89%   |
| 301-350        | 29       | 6.67%   |
| 601-700        | 17       | 3.91%   |
| 1001-1500      | 17       | 3.91%   |
| 351-400        | 16       | 3.68%   |
| 701-800        | 12       | 2.76%   |
| 1501-2000      | 9        | 2.07%   |
| 801-900        | 8        | 1.84%   |
| 201-300        | 5        | 1.15%   |
| 901-1000       | 2        | 0.46%   |
| More than 2000 | 1        | 0.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 262      | 63.75%  |
| 16/10   | 48       | 11.68%  |
| Unknown | 34       | 8.27%   |
| 5/4     | 29       | 7.06%   |
| 4/3     | 21       | 5.11%   |
| 21/9    | 9        | 2.19%   |
| 3/2     | 3        | 0.73%   |
| 1.96    | 3        | 0.73%   |
| 32/9    | 2        | 0.49%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 130      | 29.61%  |
| 151-200        | 89       | 20.27%  |
| 141-150        | 45       | 10.25%  |
| Unknown        | 43       | 9.79%   |
| 301-350        | 38       | 8.66%   |
| 351-500        | 26       | 5.92%   |
| More than 1000 | 22       | 5.01%   |
| 501-1000       | 14       | 3.19%   |
| 251-300        | 10       | 2.28%   |
| 111-120        | 8        | 1.82%   |
| 101-110        | 7        | 1.59%   |
| 81-90          | 3        | 0.68%   |
| 131-140        | 3        | 0.68%   |
| 71-80          | 1        | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 279      | 66.27%  |
| 101-120 | 66       | 15.68%  |
| Unknown | 43       | 10.21%  |
| 1-50    | 20       | 4.75%   |
| 121-160 | 8        | 1.9%    |
| 161-240 | 5        | 1.19%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 354      | 76.13%  |
| 2     | 69       | 14.84%  |
| 0     | 35       | 7.53%   |
| 3     | 5        | 1.08%   |
| 4     | 2        | 0.43%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 270      | 43.06%  |
| Intel                            | 151      | 24.08%  |
| Qualcomm Atheros                 | 44       | 7.02%   |
| TP-Link                          | 19       | 3.03%   |
| Ralink Technology                | 17       | 2.71%   |
| Broadcom                         | 16       | 2.55%   |
| Huawei Technologies              | 15       | 2.39%   |
| Samsung Electronics              | 12       | 1.91%   |
| D-Link                           | 9        | 1.44%   |
| Nvidia                           | 8        | 1.28%   |
| MediaTek                         | 8        | 1.28%   |
| D-Link System                    | 8        | 1.28%   |
| Ralink                           | 7        | 1.12%   |
| Microsoft                        | 5        | 0.8%    |
| Aquantia                         | 5        | 0.8%    |
| Marvell Technology Group         | 3        | 0.48%   |
| Broadcom Limited                 | 3        | 0.48%   |
| ZyXEL Communications             | 2        | 0.32%   |
| TRENDnet                         | 2        | 0.32%   |
| Tenda                            | 2        | 0.32%   |
| Spreadtrum Communications        | 2        | 0.32%   |
| Silicon Integrated Systems [SiS] | 2        | 0.32%   |
| NetGear                          | 2        | 0.32%   |
| ZTE WCDMA Technologies MSM       | 1        | 0.16%   |
| Xiaomi                           | 1        | 0.16%   |
| Smart Link                       | 1        | 0.16%   |
| Qualcomm Atheros Communications  | 1        | 0.16%   |
| Motorola                         | 1        | 0.16%   |
| Linux 2.6.31.6 with s3c-udc      | 1        | 0.16%   |
| IBM                              | 1        | 0.16%   |
| Foxconn / Hon Hai                | 1        | 0.16%   |
| Edimax Technology                | 1        | 0.16%   |
| DisplayLink                      | 1        | 0.16%   |
| CyberTAN Technology              | 1        | 0.16%   |
| Cal-Comp Electronic              | 1        | 0.16%   |
| Belkin Components                | 1        | 0.16%   |
| ASUSTek Computer                 | 1        | 0.16%   |
| Apple                            | 1        | 0.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 203      | 29.21%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 30       | 4.32%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 24       | 3.45%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 20       | 2.88%   |
| Intel 82579V Gigabit Network Connection                                | 15       | 2.16%   |
| Intel Ethernet Connection (2) I219-V                                   | 14       | 2.01%   |
| Ralink MT7601U Wireless Adapter                                        | 13       | 1.87%   |
| Realtek RTL8125 2.5GbE Controller                                      | 11       | 1.58%   |
| Intel I211 Gigabit Network Connection                                  | 10       | 1.44%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 8        | 1.15%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 8        | 1.15%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 8        | 1.15%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter             | 8        | 1.15%   |
| Intel Wi-Fi 6 AX200                                                    | 8        | 1.15%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 7        | 1.01%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 7        | 1.01%   |
| Intel Ethernet Connection (2) I219-LM                                  | 7        | 1.01%   |
| Intel 82578DM Gigabit Network Connection                               | 7        | 1.01%   |
| TP-Link 802.11ac WLAN Adapter                                          | 6        | 0.86%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 6        | 0.86%   |
| Intel Ethernet Controller I225-V                                       | 6        | 0.86%   |
| Intel 82578DC Gigabit Network Connection                               | 6        | 0.86%   |
| Huawei VTR-L09                                                         | 6        | 0.86%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                        | 6        | 0.86%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 5        | 0.72%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 5        | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 5        | 0.72%   |
| Microsoft Xbox 360 Wireless Adapter                                    | 5        | 0.72%   |
| Intel Ethernet Connection I217-LM                                      | 5        | 0.72%   |
| Intel 82574L Gigabit Network Connection                                | 5        | 0.72%   |
| Intel 82566DM Gigabit Network Connection                               | 5        | 0.72%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                       | 5        | 0.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4        | 0.58%   |
| Ralink RT5370 Wireless Adapter                                         | 4        | 0.58%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 4        | 0.58%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 4        | 0.58%   |
| Intel Ethernet Connection (7) I219-V                                   | 4        | 0.58%   |
| Intel Ethernet Connection (2) I218-V                                   | 4        | 0.58%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 4        | 0.58%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 4        | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 56       | 31.28%  |
| Qualcomm Atheros                | 22       | 12.29%  |
| Intel                           | 19       | 10.61%  |
| TP-Link                         | 18       | 10.06%  |
| Ralink Technology               | 17       | 9.5%    |
| D-Link                          | 9        | 5.03%   |
| Ralink                          | 7        | 3.91%   |
| MediaTek                        | 7        | 3.91%   |
| Microsoft                       | 5        | 2.79%   |
| Broadcom                        | 3        | 1.68%   |
| ZyXEL Communications            | 2        | 1.12%   |
| TRENDnet                        | 2        | 1.12%   |
| Tenda                           | 2        | 1.12%   |
| NetGear                         | 2        | 1.12%   |
| D-Link System                   | 2        | 1.12%   |
| ZTE WCDMA Technologies MSM      | 1        | 0.56%   |
| Qualcomm Atheros Communications | 1        | 0.56%   |
| Edimax Technology               | 1        | 0.56%   |
| CyberTAN Technology             | 1        | 0.56%   |
| Belkin Components               | 1        | 0.56%   |
| ASUSTek Computer                | 1        | 0.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                               | 20       | 10.75%  |
| Ralink MT7601U Wireless Adapter                                                   | 13       | 6.99%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                       | 8        | 4.3%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                    | 8        | 4.3%    |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                        | 8        | 4.3%    |
| Intel Wi-Fi 6 AX200                                                               | 8        | 4.3%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                             | 7        | 3.76%   |
| TP-Link 802.11ac WLAN Adapter                                                     | 6        | 3.23%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                            | 6        | 3.23%   |
| Microsoft Xbox 360 Wireless Adapter                                               | 5        | 2.69%   |
| Ralink RT5370 Wireless Adapter                                                    | 4        | 2.15%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                     | 4        | 2.15%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                           | 3        | 1.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                        | 3        | 1.61%   |
| TP-Link Archer T4U ver.3                                                          | 2        | 1.08%   |
| Tenda U12                                                                         | 2        | 1.08%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                               | 2        | 1.08%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                        | 2        | 1.08%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                   | 2        | 1.08%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                   | 2        | 1.08%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                            | 2        | 1.08%   |
| Realtek RTL8188EE Wireless Network Adapter                                        | 2        | 1.08%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                         | 2        | 1.08%   |
| Realtek 802.11ac NIC                                                              | 2        | 1.08%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                              | 2        | 1.08%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                  | 2        | 1.08%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                           | 2        | 1.08%   |
| Intel Wireless 8265 / 8275                                                        | 2        | 1.08%   |
| Intel Wireless 8260                                                               | 2        | 1.08%   |
| Intel Wireless 7265                                                               | 2        | 1.08%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                           | 2        | 1.08%   |
| D-Link DWM-156                                                                    | 2        | 1.08%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]              | 2        | 1.08%   |
| D-Link 802.11 n WLAN                                                              | 2        | 1.08%   |
| ZyXEL ZyAIR G-202 802.11bg                                                        | 1        | 0.54%   |
| ZyXEL NWD2105 802.11bgn Wireless Adapter [Ralink RT3070]                          | 1        | 0.54%   |
| ZTE WCDMA MSM K3772-Z                                                             | 1        | 0.54%   |
| TRENDnet TEW-648UBM 802.11n 150Mbps Micro Wireless N Adapter [Realtek RTL8188CUS] | 1        | 0.54%   |
| TRENDnet 802.11n WLAN Adapter                                                     | 1        | 0.54%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                        | 1        | 0.54%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 252      | 51.22%  |
| Intel                            | 143      | 29.07%  |
| Qualcomm Atheros                 | 25       | 5.08%   |
| Broadcom                         | 13       | 2.64%   |
| Samsung Electronics              | 12       | 2.44%   |
| Huawei Technologies              | 12       | 2.44%   |
| Nvidia                           | 8        | 1.63%   |
| D-Link System                    | 6        | 1.22%   |
| Aquantia                         | 5        | 1.02%   |
| Marvell Technology Group         | 3        | 0.61%   |
| Broadcom Limited                 | 3        | 0.61%   |
| Spreadtrum Communications        | 2        | 0.41%   |
| Silicon Integrated Systems [SiS] | 2        | 0.41%   |
| Xiaomi                           | 1        | 0.2%    |
| TP-Link                          | 1        | 0.2%    |
| MediaTek                         | 1        | 0.2%    |
| Foxconn / Hon Hai                | 1        | 0.2%    |
| DisplayLink                      | 1        | 0.2%    |
| Apple                            | 1        | 0.2%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 203      | 40.52%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 30       | 5.99%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 24       | 4.79%   |
| Intel 82579V Gigabit Network Connection                                        | 15       | 2.99%   |
| Intel Ethernet Connection (2) I219-V                                           | 14       | 2.79%   |
| Realtek RTL8125 2.5GbE Controller                                              | 11       | 2.2%    |
| Intel I211 Gigabit Network Connection                                          | 10       | 2%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 8        | 1.6%    |
| Samsung Galaxy series, misc. (tethering mode)                                  | 7        | 1.4%    |
| Intel Ethernet Connection (2) I219-LM                                          | 7        | 1.4%    |
| Intel 82578DM Gigabit Network Connection                                       | 7        | 1.4%    |
| Intel Ethernet Controller I225-V                                               | 6        | 1.2%    |
| Intel 82578DC Gigabit Network Connection                                       | 6        | 1.2%    |
| Huawei VTR-L09                                                                 | 6        | 1.2%    |
| D-Link System DGE-528T Gigabit Ethernet Adapter                                | 6        | 1.2%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 5        | 1%      |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 5        | 1%      |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 5        | 1%      |
| Intel Ethernet Connection I217-LM                                              | 5        | 1%      |
| Intel 82574L Gigabit Network Connection                                        | 5        | 1%      |
| Intel 82566DM Gigabit Network Connection                                       | 5        | 1%      |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                               | 5        | 1%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4        | 0.8%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 4        | 0.8%    |
| Intel Ethernet Connection (7) I219-V                                           | 4        | 0.8%    |
| Intel Ethernet Connection (2) I218-V                                           | 4        | 0.8%    |
| Intel 82567LM-3 Gigabit Network Connection                                     | 4        | 0.8%    |
| Intel 82566DM-2 Gigabit Network Connection                                     | 4        | 0.8%    |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)                         | 4        | 0.8%    |
| Huawei E353/E3131                                                              | 4        | 0.8%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 3        | 0.6%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 3        | 0.6%    |
| Nvidia MCP51 Ethernet Controller                                               | 3        | 0.6%    |
| Intel 82566DC-2 Gigabit Network Connection                                     | 3        | 0.6%    |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 3        | 0.6%    |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                      | 2        | 0.4%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 2        | 0.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2        | 0.4%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2        | 0.4%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 2        | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 441      | 71.94%  |
| WiFi     | 164      | 26.75%  |
| Modem    | 5        | 0.82%   |
| Unknown  | 3        | 0.49%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 347      | 76.26%  |
| WiFi     | 108      | 23.74%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 351      | 77.14%  |
| 2     | 85       | 18.68%  |
| 3     | 9        | 1.98%   |
| 0     | 9        | 1.98%   |
| 4     | 1        | 0.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 441      | 97.57%  |
| Yes  | 11       | 2.43%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 39       | 44.32%  |
| Intel                           | 17       | 19.32%  |
| Broadcom                        | 6        | 6.82%   |
| MediaTek                        | 5        | 5.68%   |
| Apple                           | 4        | 4.55%   |
| Realtek Semiconductor           | 3        | 3.41%   |
| Qualcomm Atheros Communications | 3        | 3.41%   |
| ASUSTek Computer                | 3        | 3.41%   |
| TP-Link                         | 2        | 2.27%   |
| Toshiba                         | 1        | 1.14%   |
| Micro Star International        | 1        | 1.14%   |
| Integrated System Solution      | 1        | 1.14%   |
| IMC Networks                    | 1        | 1.14%   |
| Foxconn / Hon Hai               | 1        | 1.14%   |
| Edimax Technology               | 1        | 1.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 39       | 44.32%  |
| Intel AX200 Bluetooth                                   | 7        | 7.95%   |
| MediaTek Wireless_Device                                | 5        | 5.68%   |
| Intel Bluetooth Device                                  | 4        | 4.55%   |
| Apple Bluetooth HCI                                     | 4        | 4.55%   |
| Realtek Bluetooth Radio                                 | 3        | 3.41%   |
| Qualcomm Atheros  Bluetooth Device                      | 3        | 3.41%   |
| Intel Bluetooth wireless interface                      | 3        | 3.41%   |
| Broadcom BCM20702A0 Bluetooth 4.0                       | 3        | 3.41%   |
| TP-Link UB500 Adapter                                   | 2        | 2.27%   |
| Toshiba Atheros AR3012 Bluetooth                        | 1        | 1.14%   |
| Micro Star International Bluetooth dongle               | 1        | 1.14%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 1        | 1.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 1        | 1.14%   |
| Intel AX211 Bluetooth                                   | 1        | 1.14%   |
| Integrated System Solution Bluetooth Device             | 1        | 1.14%   |
| IMC Networks Bluetooth Radio                            | 1        | 1.14%   |
| Foxconn / Hon Hai Wireless_Device                       | 1        | 1.14%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter | 1        | 1.14%   |
| Broadcom Bluetooth 2.0+eDR dongle                       | 1        | 1.14%   |
| Broadcom BCM920702 Bluetooth 4.0 Zero Touch Dongle      | 1        | 1.14%   |
| Broadcom BCM2035 Bluetooth dongle                       | 1        | 1.14%   |
| ASUS Bluetooth Adapter                                  | 1        | 1.14%   |
| ASUS BCM20702A0                                         | 1        | 1.14%   |
| ASUS ASUS USB-BT500                                     | 1        | 1.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 341      | 48.92%  |
| Nvidia                           | 154      | 22.09%  |
| AMD                              | 121      | 17.36%  |
| C-Media Electronics              | 18       | 2.58%   |
| Creative Labs                    | 8        | 1.15%   |
| Corsair                          | 6        | 0.86%   |
| Logitech                         | 5        | 0.72%   |
| DSEA A/S                         | 4        | 0.57%   |
| VIA Technologies                 | 3        | 0.43%   |
| JMTek                            | 3        | 0.43%   |
| ASUSTek Computer                 | 3        | 0.43%   |
| Sony                             | 2        | 0.29%   |
| Silicon Integrated Systems [SiS] | 2        | 0.29%   |
| Samson Technologies              | 2        | 0.29%   |
| Razer USA                        | 2        | 0.29%   |
| Plantronics                      | 2        | 0.29%   |
| Microsoft                        | 2        | 0.29%   |
| Micro Star International         | 2        | 0.29%   |
| Hewlett-Packard                  | 2        | 0.29%   |
| GN Netcom                        | 2        | 0.29%   |
| Trust                            | 1        | 0.14%   |
| Syntek                           | 1        | 0.14%   |
| Realtek Semiconductor            | 1        | 0.14%   |
| iPassion Technology              | 1        | 0.14%   |
| GYROCOM C&C                      | 1        | 0.14%   |
| Giga-Byte Technology             | 1        | 0.14%   |
| Generalplus Technology           | 1        | 0.14%   |
| FIFINE Microphones               | 1        | 0.14%   |
| Elgato Systems                   | 1        | 0.14%   |
| Cooler Master                    | 1        | 0.14%   |
| Cambridge Silicon Radio          | 1        | 0.14%   |
| Astro Gaming                     | 1        | 0.14%   |
| Asahi Kasei Microsystems         | 1        | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 77       | 9.88%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 49       | 6.29%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 38       | 4.88%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 37       | 4.75%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 33       | 4.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 26       | 3.34%   |
| AMD Starship/Matisse HD Audio Controller                                   | 26       | 3.34%   |
| AMD Family 17h/19h HD Audio Controller                                     | 22       | 2.82%   |
| Nvidia High Definition Audio Controller                                    | 20       | 2.57%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 20       | 2.57%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 19       | 2.44%   |
| Intel 200 Series PCH HD Audio                                              | 18       | 2.31%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 16       | 2.05%   |
| Nvidia GF108 High Definition Audio Controller                              | 15       | 1.93%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 12       | 1.54%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 12       | 1.54%   |
| Nvidia GP107GL High Definition Audio Controller                            | 11       | 1.41%   |
| Intel Cannon Lake PCH cAVS                                                 | 10       | 1.28%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 10       | 1.28%   |
| Nvidia GF119 HDMI Audio Controller                                         | 9        | 1.16%   |
| Nvidia GP104 High Definition Audio Controller                              | 8        | 1.03%   |
| Nvidia GK104 HDMI Audio Controller                                         | 8        | 1.03%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 8        | 1.03%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 8        | 1.03%   |
| Nvidia GP106 High Definition Audio Controller                              | 7        | 0.9%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 7        | 0.9%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 7        | 0.9%    |
| Nvidia TU116 High Definition Audio Controller                              | 6        | 0.77%   |
| Nvidia GK107 HDMI Audio Controller                                         | 6        | 0.77%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 6        | 0.77%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 5        | 0.64%   |
| Nvidia GA104 High Definition Audio Controller                              | 5        | 0.64%   |
| Intel Alder Lake-S HD Audio Controller                                     | 5        | 0.64%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5        | 0.64%   |
| C-Media Electronics USB Audio Device                                       | 5        | 0.64%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 5        | 0.64%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 5        | 0.64%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5        | 0.64%   |
| AMD Navi 10 HDMI Audio                                                     | 5        | 0.64%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 5        | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 32       | 14.61%  |
| Unknown             | 30       | 13.7%   |
| Kingston            | 30       | 13.7%   |
| Samsung Electronics | 19       | 8.68%   |
| SK hynix            | 17       | 7.76%   |
| Transcend           | 16       | 7.31%   |
| G.Skill             | 14       | 6.39%   |
| Crucial             | 11       | 5.02%   |
| Micron Technology   | 10       | 4.57%   |
| KLEVV               | 8        | 3.65%   |
| A-DATA Technology   | 8        | 3.65%   |
| Patriot             | 6        | 2.74%   |
| Strontium           | 3        | 1.37%   |
| Apacer              | 3        | 1.37%   |
| Team                | 2        | 0.91%   |
| Kingmax             | 2        | 0.91%   |
| Unknown             | 2        | 0.91%   |
| Silicon Power       | 1        | 0.46%   |
| Ramaxel Technology  | 1        | 0.46%   |
| Qimonda             | 1        | 0.46%   |
| Nanya Technology    | 1        | 0.46%   |
| KingFast            | 1        | 0.46%   |
| Elpida              | 1        | 0.46%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| KLEVV RAM KD4AGUA8A-26N1900 16GB DIMM DDR4 2667MT/s    | 5        | 2.06%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s   | 4        | 1.65%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s    | 4        | 1.65%   |
| Unknown RAM Module 4GB DIMM 400MT/s                    | 3        | 1.23%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                | 3        | 1.23%   |
| Transcend RAM TS512MLK64V6H 4GB DIMM DDR3 1600MT/s     | 3        | 1.23%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s   | 3        | 1.23%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s    | 3        | 1.23%   |
| Unknown RAM Module 512MB DIMM 400MT/s                  | 2        | 0.82%   |
| Unknown RAM Module 4GB DIMM 800MT/s                    | 2        | 0.82%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 2        | 0.82%   |
| Unknown RAM Module 2GB DIMM 800MT/s                    | 2        | 0.82%   |
| Transcend RAM TS1GLK64V6H 8GB DIMM DDR3 1600MT/s       | 2        | 0.82%   |
| Transcend RAM JM1600KLN-4G 4GB DIMM DDR3 1600MT/s      | 2        | 0.82%   |
| Transcend RAM JM1333KLN-2G 2GB DIMM DDR3 1333MT/s      | 2        | 0.82%   |
| Transcend RAM JM1333KLH-8G 8GB DIMM DDR3 1333MT/s      | 2        | 0.82%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s   | 2        | 0.82%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s    | 2        | 0.82%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s    | 2        | 0.82%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s        | 2        | 0.82%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s         | 2        | 0.82%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s    | 2        | 0.82%   |
| Kingston RAM 99U5474-028.A00LF 4GB DIMM DDR3 1333MT/s  | 2        | 0.82%   |
| Kingston RAM 99U5474-026.A00LF 4GB DIMM DDR3 1333MT/s  | 2        | 0.82%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s  | 2        | 0.82%   |
| Kingston RAM 9905678-023.A00G 8GB DIMM DDR4 2187MT/s   | 2        | 0.82%   |
| Crucial RAM BLS8G4D240FSE.16FBD 8GB DIMM DDR4 2448MT/s | 2        | 0.82%   |
| Corsair RAM CMZ8GX3M1A1600C10 8GB DIMM DDR3 1600MT/s   | 2        | 0.82%   |
| Corsair RAM CMZ4GX3M1A1600C9 4GB DIMM DDR3 1600MT/s    | 2        | 0.82%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3100MT/s | 2        | 0.82%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s  | 2        | 0.82%   |
| A-DATA RAM Module 8192MB DIMM DDR4 2133MT/s            | 2        | 0.82%   |
| Unknown                                                | 2        | 0.82%   |
| Unknown RAM Module 8GB DIMM DDR3 1866MT/s              | 1        | 0.41%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s              | 1        | 0.41%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                   | 1        | 0.41%   |
| Unknown RAM Module 512MB DIMM DDR2 266MT/s             | 1        | 0.41%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s              | 1        | 0.41%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s           | 1        | 0.41%   |
| Unknown RAM Module 4096MB DIMM                         | 1        | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 73       | 40.33%  |
| DDR4    | 68       | 37.57%  |
| Unknown | 18       | 9.94%   |
| DDR2    | 12       | 6.63%   |
| SDRAM   | 4        | 2.21%   |
| DDR5    | 4        | 2.21%   |
| DDR     | 2        | 1.1%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 170      | 94.97%  |
| SODIMM  | 8        | 4.47%   |
| FB-DIMM | 1        | 0.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 65       | 32.02%  |
| 4096  | 63       | 31.03%  |
| 2048  | 30       | 14.78%  |
| 16384 | 26       | 12.81%  |
| 1024  | 11       | 5.42%   |
| 512   | 4        | 1.97%   |
| 32768 | 3        | 1.48%   |
| 24576 | 1        | 0.49%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 45       | 21.84%  |
| 1333    | 34       | 16.5%   |
| 800     | 11       | 5.34%   |
| 3600    | 10       | 4.85%   |
| 2667    | 10       | 4.85%   |
| 3200    | 9        | 4.37%   |
| 2133    | 8        | 3.88%   |
| 667     | 7        | 3.4%    |
| 1867    | 5        | 2.43%   |
| 400     | 5        | 2.43%   |
| 3866    | 4        | 1.94%   |
| 2400    | 4        | 1.94%   |
| 3800    | 3        | 1.46%   |
| 3066    | 3        | 1.46%   |
| 2933    | 3        | 1.46%   |
| 2666    | 3        | 1.46%   |
| 1067    | 3        | 1.46%   |
| Unknown | 3        | 1.46%   |
| 6000    | 2        | 0.97%   |
| 3733    | 2        | 0.97%   |
| 3100    | 2        | 0.97%   |
| 3000    | 2        | 0.97%   |
| 2934    | 2        | 0.97%   |
| 2448    | 2        | 0.97%   |
| 2200    | 2        | 0.97%   |
| 2187    | 2        | 0.97%   |
| 1800    | 2        | 0.97%   |
| 1648    | 2        | 0.97%   |
| 41632   | 1        | 0.49%   |
| 5200    | 1        | 0.49%   |
| 4800    | 1        | 0.49%   |
| 4199    | 1        | 0.49%   |
| 3466    | 1        | 0.49%   |
| 3266    | 1        | 0.49%   |
| 2800    | 1        | 0.49%   |
| 2733    | 1        | 0.49%   |
| 2600    | 1        | 0.49%   |
| 2048    | 1        | 0.49%   |
| 2000    | 1        | 0.49%   |
| 1866    | 1        | 0.49%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 6        | 31.58%  |
| Canon               | 4        | 21.05%  |
| Pantum              | 3        | 15.79%  |
| Hewlett-Packard     | 3        | 15.79%  |
| Seiko Epson         | 1        | 5.26%   |
| Dell                | 1        | 5.26%   |
| Brother Industries  | 1        | 5.26%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| Pantum P2200 series          | 3        | 15.79%  |
| Seiko Epson L3110 Series     | 1        | 5.26%   |
| Samsung SCX-4623 Series      | 1        | 5.26%   |
| Samsung M267x 287x Series    | 1        | 5.26%   |
| Samsung M2070 Series         | 1        | 5.26%   |
| Samsung M2020 Series         | 1        | 5.26%   |
| Samsung Composite Device     | 1        | 5.26%   |
| Samsung C460 Series          | 1        | 5.26%   |
| HP OfficeJet Pro 9010 series | 1        | 5.26%   |
| HP OfficeJet 5600 (USBHUB)   | 1        | 5.26%   |
| HP LaserJet 1018             | 1        | 5.26%   |
| Dell 1250c Color Printer     | 1        | 5.26%   |
| Canon PIXMA MX410            | 1        | 5.26%   |
| Canon PIXMA MG3600 Series    | 1        | 5.26%   |
| Canon MG2400 series          | 1        | 5.26%   |
| Canon G3010 series           | 1        | 5.26%   |
| Brother HL-2130 series       | 1        | 5.26%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Seiko Epson     | 1        | 33.33%  |
| Hewlett-Packard | 1        | 33.33%  |
| Canon           | 1        | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO] | 1        | 33.33%  |
| HP OfficeJet 6110                                  | 1        | 33.33%  |
| Canon CanoScan N670U/N676U/LiDE 20                 | 1        | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 20       | 33.33%  |
| Microsoft                     | 8        | 13.33%  |
| Sunplus Innovation Technology | 6        | 10%     |
| Apple                         | 4        | 6.67%   |
| Samsung Electronics           | 3        | 5%      |
| Realtek Semiconductor         | 2        | 3.33%   |
| Microdia                      | 2        | 3.33%   |
| 04004000_P040200_SN0002       | 2        | 3.33%   |
| Z-Star Microelectronics       | 1        | 1.67%   |
| TASCORP                       | 1        | 1.67%   |
| Syntek                        | 1        | 1.67%   |
| Panasonic (Matsushita)        | 1        | 1.67%   |
| Owl Labs                      | 1        | 1.67%   |
| OmniVision Technologies       | 1        | 1.67%   |
| KYE Systems (Mouse Systems)   | 1        | 1.67%   |
| Insta360                      | 1        | 1.67%   |
| Hewlett-Packard               | 1        | 1.67%   |
| Google                        | 1        | 1.67%   |
| Chicony Electronics           | 1        | 1.67%   |
| Bison Electronics             | 1        | 1.67%   |
| Asuscom Network               | 1        | 1.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Desktops | Percent |
|--------------------------------------------------|----------|---------|
| Logitech Webcam C270                             | 5        | 8.2%    |
| Logitech Webcam C170                             | 4        | 6.56%   |
| Sunplus PC Camera                                | 3        | 4.92%   |
| Microsoft LifeCam VX-2000                        | 3        | 4.92%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                  | 3        | 4.92%   |
| Sunplus Full HD webcam                           | 2        | 3.28%   |
| Samsung Galaxy series, misc. (MTP mode)          | 2        | 3.28%   |
| Microsoft LifeCam VX-800                         | 2        | 3.28%   |
| Microsoft LifeCam HD-3000                        | 2        | 3.28%   |
| Logitech Webcam C210                             | 2        | 3.28%   |
| Logitech Webcam C200                             | 2        | 3.28%   |
| Logitech HD Webcam C615                          | 2        | 3.28%   |
| 04004000_P040200_SN0002 1080P Web Camera         | 2        | 3.28%   |
| Z-Star Venus USB2.0 Camera                       | 1        | 1.64%   |
| TASCORP USB2.0 WebCam                            | 1        | 1.64%   |
| Syntek XYZ printing cameraR2                     | 1        | 1.64%   |
| Syntek XYZ printing cameraL2                     | 1        | 1.64%   |
| Sunplus HD 720P webcam                           | 1        | 1.64%   |
| Samsung USB2.0 UVC HQ WebCam                     | 1        | 1.64%   |
| Realtek Streaming Webcam                         | 1        | 1.64%   |
| Realtek Integrated_Webcam_HD                     | 1        | 1.64%   |
| Panasonic (Matsushita) NV-GS11/230/250 (DV mode) | 1        | 1.64%   |
| Owl Labs Meeting Owl Pro                         | 1        | 1.64%   |
| OmniVision USB Camera-OV580                      | 1        | 1.64%   |
| Microsoft LifeCam Cinema                         | 1        | 1.64%   |
| Microdia HP Integrated Webcam                    | 1        | 1.64%   |
| Microdia Camera                                  | 1        | 1.64%   |
| Logitech QuickCam Sphere                         | 1        | 1.64%   |
| Logitech QuickCam Pro 9000                       | 1        | 1.64%   |
| Logitech HD Webcam C525                          | 1        | 1.64%   |
| Logitech C920 PRO HD Webcam                      | 1        | 1.64%   |
| Logitech BRIO Ultra HD Webcam                    | 1        | 1.64%   |
| KYE Systems (Mouse Systems) FaceCam 1000X        | 1        | 1.64%   |
| Insta360 Link                                    | 1        | 1.64%   |
| HP 320 FHD Webcam                                | 1        | 1.64%   |
| Google HD USB Camera                             | 1        | 1.64%   |
| Chicony HP Webcam                                | 1        | 1.64%   |
| Bison Integrated Camera                          | 1        | 1.64%   |
| Asuscom Network REDRAGON Live Camera             | 1        | 1.64%   |
| Apple iPod Touch 5.Gen [A1421]                   | 1        | 1.64%   |

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
| 0     | 382      | 83.22%  |
| 1     | 66       | 14.38%  |
| 2     | 8        | 1.74%   |
| 4     | 2        | 0.44%   |
| 3     | 1        | 0.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 34       | 40%     |
| Net/wireless             | 24       | 28.24%  |
| Communication controller | 8        | 9.41%   |
| Unassigned class         | 4        | 4.71%   |
| Sound                    | 3        | 3.53%   |
| Storage/raid             | 2        | 2.35%   |
| Network                  | 2        | 2.35%   |
| Net/ethernet             | 2        | 2.35%   |
| Modem                    | 2        | 2.35%   |
| Camera                   | 2        | 2.35%   |
| Storage/nvme             | 1        | 1.18%   |
| Multimedia controller    | 1        | 1.18%   |

