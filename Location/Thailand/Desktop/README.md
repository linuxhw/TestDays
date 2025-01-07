Linux in Thailand - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Thailand.

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

Total: 420

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | B450 Steel Legend           | [5320a7c488](https://linux-hardware.org/?probe=5320a7c488) | Dec 27, 2024 |
| MiTAC         | PD10EHI                     | [0879837e1b](https://linux-hardware.org/?probe=0879837e1b) | Dec 24, 2024 |
| MiTAC         | PD10EHI                     | [677c9d3ee3](https://linux-hardware.org/?probe=677c9d3ee3) | Dec 18, 2024 |
| Intel         | X99                         | [1a147ad6e0](https://linux-hardware.org/?probe=1a147ad6e0) | Dec 16, 2024 |
| Gigabyte      | AB350-Gaming-CF             | [7aebeb376d](https://linux-hardware.org/?probe=7aebeb376d) | Dec 14, 2024 |
| ASUSTek       | M5A78L-M LX V2              | [94bf662079](https://linux-hardware.org/?probe=94bf662079) | Dec 11, 2024 |
| Gigabyte      | EP45-UD3R                   | [dbee87ee50](https://linux-hardware.org/?probe=dbee87ee50) | Dec 10, 2024 |
| ASRock        | A520M-HVS                   | [13eb428010](https://linux-hardware.org/?probe=13eb428010) | Dec 01, 2024 |
| ASRock        | X570 Phantom Gaming 4       | [74716c6624](https://linux-hardware.org/?probe=74716c6624) | Nov 28, 2024 |
| ASRock        | X570 Phantom Gaming 4       | [b5f2062c2c](https://linux-hardware.org/?probe=b5f2062c2c) | Nov 18, 2024 |
| MSI           | B365M PRO-VDH               | [82d0c85a4c](https://linux-hardware.org/?probe=82d0c85a4c) | Nov 12, 2024 |
| MiTAC         | PD10EHI                     | [378a9691e4](https://linux-hardware.org/?probe=378a9691e4) | Nov 09, 2024 |
| Lenovo        | 31900059 STD                | [eb4e9fd174](https://linux-hardware.org/?probe=eb4e9fd174) | Oct 31, 2024 |
| Gigabyte      | Z77X-D3H                    | [566d913cf0](https://linux-hardware.org/?probe=566d913cf0) | Oct 31, 2024 |
| ASRock        | X570 Pro4                   | [aeb453702e](https://linux-hardware.org/?probe=aeb453702e) | Oct 25, 2024 |
| HP            | 1497                        | [f60b700334](https://linux-hardware.org/?probe=f60b700334) | Oct 21, 2024 |
| ASRock        | B550 Steel Legend           | [c4ffd7734d](https://linux-hardware.org/?probe=c4ffd7734d) | Oct 19, 2024 |
| Gigabyte      | Z77X-D3H                    | [3113b0c26d](https://linux-hardware.org/?probe=3113b0c26d) | Oct 17, 2024 |
| ASUSTek       | PRIME A320M-K               | [627376d603](https://linux-hardware.org/?probe=627376d603) | Oct 17, 2024 |
| Dell          | 0C3YXR A01                  | [702872562a](https://linux-hardware.org/?probe=702872562a) | Oct 15, 2024 |
| HP            | 802F                        | [2678cdc4b4](https://linux-hardware.org/?probe=2678cdc4b4) | Oct 10, 2024 |
| MiTAC         | PD10EHI                     | [d3d62dd202](https://linux-hardware.org/?probe=d3d62dd202) | Oct 03, 2024 |
| ASUSTek       | PRIME A320M-K               | [4c14174367](https://linux-hardware.org/?probe=4c14174367) | Sep 29, 2024 |
| ASUSTek       | PRIME A320M-K               | [b5dd25d1cb](https://linux-hardware.org/?probe=b5dd25d1cb) | Sep 28, 2024 |
| ASRock        | B450 Steel Legend           | [2f3706f0c5](https://linux-hardware.org/?probe=2f3706f0c5) | Sep 21, 2024 |
| HP            | 802F                        | [8f5648baef](https://linux-hardware.org/?probe=8f5648baef) | Sep 20, 2024 |
| ASRock        | B450 Steel Legend           | [068811de2e](https://linux-hardware.org/?probe=068811de2e) | Sep 19, 2024 |
| HP            | 8298                        | [33696766f2](https://linux-hardware.org/?probe=33696766f2) | Sep 15, 2024 |
| ASUSTek       | PRIME H610M-E D4            | [c6d88ef79f](https://linux-hardware.org/?probe=c6d88ef79f) | Sep 13, 2024 |
| Gigabyte      | B650M DS3H                  | [2f3b657d09](https://linux-hardware.org/?probe=2f3b657d09) | Sep 09, 2024 |
| ASUSTek       | H61M-A/USB3                 | [727745c91c](https://linux-hardware.org/?probe=727745c91c) | Sep 09, 2024 |
| ASUSTek       | Maximus VI HERO             | [64da4e01a4](https://linux-hardware.org/?probe=64da4e01a4) | Sep 07, 2024 |
| Gigabyte      | B650M DS3H                  | [9214328551](https://linux-hardware.org/?probe=9214328551) | Sep 05, 2024 |
| JINGSHA       | B85M-I                      | [0ec5002083](https://linux-hardware.org/?probe=0ec5002083) | Aug 31, 2024 |
| JINGSHA       | B85M-I                      | [d7094aabed](https://linux-hardware.org/?probe=d7094aabed) | Aug 21, 2024 |
| ASUSTek       | M5A78L-M LE/USB3            | [90f8587ff4](https://linux-hardware.org/?probe=90f8587ff4) | Aug 09, 2024 |
| Lenovo        | 315F NO DPK                 | [f2ab02a574](https://linux-hardware.org/?probe=f2ab02a574) | Aug 04, 2024 |
| Lenovo        | 315F NO DPK                 | [f5da233c67](https://linux-hardware.org/?probe=f5da233c67) | Aug 04, 2024 |
| MSI           | Z270 GAMING M5              | [c094b9de0f](https://linux-hardware.org/?probe=c094b9de0f) | Aug 02, 2024 |
| Intel         | X99-P4 V5.1                 | [def260ec4e](https://linux-hardware.org/?probe=def260ec4e) | Jul 28, 2024 |
| Gigabyte      | H61M-DS2                    | [31381d6558](https://linux-hardware.org/?probe=31381d6558) | Jul 22, 2024 |
| Dell          | 0T7D40 A00                  | [bea004e3ba](https://linux-hardware.org/?probe=bea004e3ba) | Jul 20, 2024 |
| Lenovo        | 3168 SDK0J40697 WIN 3305... | [77d830aa2e](https://linux-hardware.org/?probe=77d830aa2e) | Jul 12, 2024 |
| HP            | 802F                        | [287eec5051](https://linux-hardware.org/?probe=287eec5051) | Jul 08, 2024 |
| ASUSTek       | H97-PRO GAMER               | [5cef5a4211](https://linux-hardware.org/?probe=5cef5a4211) | Jul 07, 2024 |
| Shenzhen M... | DRFXI                       | [d5d17b7674](https://linux-hardware.org/?probe=d5d17b7674) | Jul 03, 2024 |
| Acer          | Veriton N4640G              | [316499457a](https://linux-hardware.org/?probe=316499457a) | Jul 01, 2024 |
| AMI           | Intel                       | [aefdd71c5e](https://linux-hardware.org/?probe=aefdd71c5e) | May 18, 2024 |
| HP            | 1998                        | [7d652e5edc](https://linux-hardware.org/?probe=7d652e5edc) | May 13, 2024 |
| Gigabyte      | B450 AORUS ELITE V2         | [92d8a990de](https://linux-hardware.org/?probe=92d8a990de) | Apr 29, 2024 |
| Dell          | 088DT1 A01                  | [0d725519b9](https://linux-hardware.org/?probe=0d725519b9) | Apr 29, 2024 |
| ASRock        | B450 Steel Legend           | [eae63cf682](https://linux-hardware.org/?probe=eae63cf682) | Apr 15, 2024 |
| Lenovo        | 3168 SDK0J40697 WIN 3305... | [11963d204b](https://linux-hardware.org/?probe=11963d204b) | Mar 21, 2024 |
| Lenovo        | 3168 SDK0J40697 WIN 3305... | [908360069c](https://linux-hardware.org/?probe=908360069c) | Mar 21, 2024 |
| Gigabyte      | H81M-DS2                    | [dde5a90821](https://linux-hardware.org/?probe=dde5a90821) | Mar 12, 2024 |
| ASUSTek       | PRIME Z790-P WIFI           | [3890a0c9b5](https://linux-hardware.org/?probe=3890a0c9b5) | Mar 09, 2024 |
| Gigabyte      | H61M-DS2                    | [68d8ddbe50](https://linux-hardware.org/?probe=68d8ddbe50) | Mar 04, 2024 |
| ASRock        | X299 Taichi                 | [5a5309bb52](https://linux-hardware.org/?probe=5a5309bb52) | Mar 03, 2024 |
| ASUSTek       | P8Z77-V LX                  | [dae19ec723](https://linux-hardware.org/?probe=dae19ec723) | Feb 18, 2024 |
| Dell          | 08WKV3 A00                  | [5bff5d79c2](https://linux-hardware.org/?probe=5bff5d79c2) | Feb 16, 2024 |
| Gigabyte      | AB350-Gaming 3-CF           | [0fbc4b07a6](https://linux-hardware.org/?probe=0fbc4b07a6) | Feb 12, 2024 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [c7ad65ef28](https://linux-hardware.org/?probe=c7ad65ef28) | Feb 10, 2024 |
| Dell          | 0VFD52 A00                  | [cc2714d2cf](https://linux-hardware.org/?probe=cc2714d2cf) | Feb 07, 2024 |
| MSI           | X99A SLI PLUS               | [216026fc45](https://linux-hardware.org/?probe=216026fc45) | Jan 30, 2024 |
| ASRock        | H470 Phantom Gaming 4       | [dc402c3f43](https://linux-hardware.org/?probe=dc402c3f43) | Jan 27, 2024 |
| Gigabyte      | B560M AORUS PRO             | [93137ffd8d](https://linux-hardware.org/?probe=93137ffd8d) | Jan 21, 2024 |
| Gigabyte      | H310M DS2 x.x               | [dcbb993ea5](https://linux-hardware.org/?probe=dcbb993ea5) | Jan 18, 2024 |
| ASRock        | B450 Steel Legend           | [d01ee5a226](https://linux-hardware.org/?probe=d01ee5a226) | Jan 02, 2024 |
| Acer          | Aspire TC-885 V:1.1         | [19be3bdc5b](https://linux-hardware.org/?probe=19be3bdc5b) | Dec 31, 2023 |
| HP            | 82B4                        | [02bcf6a9d1](https://linux-hardware.org/?probe=02bcf6a9d1) | Dec 31, 2023 |
| Gigabyte      | H310M DS2 x.x               | [47c95a8cc5](https://linux-hardware.org/?probe=47c95a8cc5) | Dec 26, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [518e259c3c](https://linux-hardware.org/?probe=518e259c3c) | Dec 23, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [3dee3cb4bf](https://linux-hardware.org/?probe=3dee3cb4bf) | Dec 19, 2023 |
| ASRock        | B550M Pro4                  | [a32cb7798b](https://linux-hardware.org/?probe=a32cb7798b) | Dec 19, 2023 |
| Dell          | 0HD5W2 A01                  | [cf61f7b65b](https://linux-hardware.org/?probe=cf61f7b65b) | Dec 16, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [7866cd7449](https://linux-hardware.org/?probe=7866cd7449) | Dec 16, 2023 |
| MSI           | B450 TOMAHAWK               | [8e66dfbc28](https://linux-hardware.org/?probe=8e66dfbc28) | Dec 12, 2023 |
| Intel         | X99                         | [6988251bb1](https://linux-hardware.org/?probe=6988251bb1) | Dec 11, 2023 |
| ASRock        | B450 Steel Legend           | [18df358540](https://linux-hardware.org/?probe=18df358540) | Dec 11, 2023 |
| ASRock        | B550M Steel Legend          | [eac155f5e6](https://linux-hardware.org/?probe=eac155f5e6) | Dec 08, 2023 |
| MSI           | B450 TOMAHAWK               | [254b936002](https://linux-hardware.org/?probe=254b936002) | Dec 08, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [fa61806ea8](https://linux-hardware.org/?probe=fa61806ea8) | Dec 05, 2023 |
| Gigabyte      | B450M DS3H-CF               | [4552c13bb1](https://linux-hardware.org/?probe=4552c13bb1) | Nov 26, 2023 |
| Gigabyte      | B550M S2H                   | [284f7d2451](https://linux-hardware.org/?probe=284f7d2451) | Nov 26, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [420d9baddf](https://linux-hardware.org/?probe=420d9baddf) | Nov 21, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [ab7e55f5b9](https://linux-hardware.org/?probe=ab7e55f5b9) | Nov 19, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [9d8548f39a](https://linux-hardware.org/?probe=9d8548f39a) | Nov 15, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [36763f453f](https://linux-hardware.org/?probe=36763f453f) | Nov 13, 2023 |
| Google        | Panther                     | [bd2af6ba92](https://linux-hardware.org/?probe=bd2af6ba92) | Nov 13, 2023 |
| HP            | 802F                        | [e5d90a5987](https://linux-hardware.org/?probe=e5d90a5987) | Nov 09, 2023 |
| Gigabyte      | A520M S2H                   | [701d46485b](https://linux-hardware.org/?probe=701d46485b) | Nov 09, 2023 |
| ASRock        | B550M Steel Legend          | [f123c19bb4](https://linux-hardware.org/?probe=f123c19bb4) | Oct 30, 2023 |
| Gigabyte      | H61MA-D3V                   | [0c4d99e9dc](https://linux-hardware.org/?probe=0c4d99e9dc) | Oct 29, 2023 |
| HP            | 802F                        | [d01e0550a3](https://linux-hardware.org/?probe=d01e0550a3) | Oct 20, 2023 |
| ASUSTek       | PRIME A320M-K               | [e44d1b7e3c](https://linux-hardware.org/?probe=e44d1b7e3c) | Oct 14, 2023 |
| AMI           | Intel                       | [888a4e1a0f](https://linux-hardware.org/?probe=888a4e1a0f) | Oct 13, 2023 |
| ASRock        | H81M-DGS R2.0               | [4bb18fddab](https://linux-hardware.org/?probe=4bb18fddab) | Oct 09, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [423d2de75a](https://linux-hardware.org/?probe=423d2de75a) | Oct 06, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [cce7c03059](https://linux-hardware.org/?probe=cce7c03059) | Sep 29, 2023 |
| Dell          | 00V62H A01                  | [f46006f6ce](https://linux-hardware.org/?probe=f46006f6ce) | Sep 28, 2023 |
| MiTAC         | PD10EHI                     | [29716ecb18](https://linux-hardware.org/?probe=29716ecb18) | Sep 27, 2023 |
| Dell          | 0D4MD1 A04                  | [5e6e35397a](https://linux-hardware.org/?probe=5e6e35397a) | Sep 24, 2023 |
| Dell          | 0D4MD1 A04                  | [4d7943532f](https://linux-hardware.org/?probe=4d7943532f) | Sep 24, 2023 |
| Dell          | 0NW6H5 A00                  | [7df92bb8f5](https://linux-hardware.org/?probe=7df92bb8f5) | Sep 22, 2023 |
| Intel         | DN2820FYK H24582-204        | [bec0346d1d](https://linux-hardware.org/?probe=bec0346d1d) | Sep 20, 2023 |
| Gigabyte      | H110M-DS2-CF                | [b2519e8577](https://linux-hardware.org/?probe=b2519e8577) | Sep 20, 2023 |
| Acer          | Veriton N4640G              | [73af90ca23](https://linux-hardware.org/?probe=73af90ca23) | Sep 16, 2023 |
| Gigabyte      | GA-H81M-DS2-CF              | [3ebcf35cf2](https://linux-hardware.org/?probe=3ebcf35cf2) | Sep 15, 2023 |
| Gigabyte      | GA-H81M-DS2-CF              | [8e5f637ac0](https://linux-hardware.org/?probe=8e5f637ac0) | Sep 15, 2023 |
| Dell          | 048DY8 A00                  | [3cc67a5e62](https://linux-hardware.org/?probe=3cc67a5e62) | Sep 15, 2023 |
| Google        | Panther                     | [1adc816fcb](https://linux-hardware.org/?probe=1adc816fcb) | Sep 12, 2023 |
| Biostar       | TB360-BTC Expert            | [4ab8e8a944](https://linux-hardware.org/?probe=4ab8e8a944) | Sep 12, 2023 |
| Dell          | 088DT1 A00                  | [08eff7732c](https://linux-hardware.org/?probe=08eff7732c) | Sep 11, 2023 |
| Acer          | Veriton N4640G              | [4ad00f4c17](https://linux-hardware.org/?probe=4ad00f4c17) | Sep 10, 2023 |
| Lenovo        | SHARKBAY NOK                | [a09c6ad4a9](https://linux-hardware.org/?probe=a09c6ad4a9) | Sep 08, 2023 |
| Biostar       | TB360-BTC Expert            | [e392e78b0d](https://linux-hardware.org/?probe=e392e78b0d) | Sep 08, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [9d45d79cb0](https://linux-hardware.org/?probe=9d45d79cb0) | Sep 06, 2023 |
| Biostar       | TB360-BTC Expert            | [7bfb24d8e3](https://linux-hardware.org/?probe=7bfb24d8e3) | Sep 06, 2023 |
| Biostar       | TB360-BTC Expert            | [650e71b107](https://linux-hardware.org/?probe=650e71b107) | Sep 05, 2023 |
| ASRock        | NF6-GLAN                    | [80d9233886](https://linux-hardware.org/?probe=80d9233886) | Sep 04, 2023 |
| ViewSonic     | VPC14-WP                    | [a5476c92e7](https://linux-hardware.org/?probe=a5476c92e7) | Aug 31, 2023 |
| ECS           | A780GM-A                    | [12787b1e38](https://linux-hardware.org/?probe=12787b1e38) | Aug 31, 2023 |
| Gigabyte      | F2A88XM-HD3                 | [43cb5c7282](https://linux-hardware.org/?probe=43cb5c7282) | Aug 30, 2023 |
| HP            | 802F                        | [7d065f8fd1](https://linux-hardware.org/?probe=7d065f8fd1) | Aug 30, 2023 |
| Acer          | Veriton N4640G              | [914ba9937f](https://linux-hardware.org/?probe=914ba9937f) | Aug 25, 2023 |
| ASRock        | B450 Steel Legend           | [40660610aa](https://linux-hardware.org/?probe=40660610aa) | Aug 24, 2023 |
| MiTAC         | PD10EHI                     | [972fe64be0](https://linux-hardware.org/?probe=972fe64be0) | Aug 23, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [c711cf46d7](https://linux-hardware.org/?probe=c711cf46d7) | Aug 14, 2023 |
| Dell          | 0HY9JP A01                  | [48d92d85c7](https://linux-hardware.org/?probe=48d92d85c7) | Aug 11, 2023 |
| HP            | 304Ah                       | [81682ebb2d](https://linux-hardware.org/?probe=81682ebb2d) | Jul 20, 2023 |
| Gigabyte      | P75-D3P                     | [0a7c65caae](https://linux-hardware.org/?probe=0a7c65caae) | Jul 13, 2023 |
| Apple         | Mac-F221BEC8                | [83e08e8aca](https://linux-hardware.org/?probe=83e08e8aca) | Jul 12, 2023 |
| Lenovo        | SHARKBAY NOK                | [fbeae7b57e](https://linux-hardware.org/?probe=fbeae7b57e) | Jul 09, 2023 |
| HP            | 802F                        | [da2666b4b8](https://linux-hardware.org/?probe=da2666b4b8) | Jun 22, 2023 |
| Lenovo        | SHARKBAY NOK                | [c0f250b2f9](https://linux-hardware.org/?probe=c0f250b2f9) | Jun 22, 2023 |
| HP            | 802F                        | [96b020f763](https://linux-hardware.org/?probe=96b020f763) | Jun 21, 2023 |
| ASRock        | B450 Steel Legend           | [26d77cd5be](https://linux-hardware.org/?probe=26d77cd5be) | Jun 19, 2023 |
| Lenovo        | SHARKBAY NOK                | [73a438e6b8](https://linux-hardware.org/?probe=73a438e6b8) | Jun 18, 2023 |
| ASUSTek       | PRIME B450M-K II            | [0fe4687002](https://linux-hardware.org/?probe=0fe4687002) | Jun 12, 2023 |
| ASRock        | B450 Steel Legend           | [483ac7223f](https://linux-hardware.org/?probe=483ac7223f) | Jun 08, 2023 |
| Lenovo        | SHARKBAY NOK                | [cf560e91e7](https://linux-hardware.org/?probe=cf560e91e7) | Jun 07, 2023 |
| Lenovo        | SHARKBAY NOK                | [108cb2ce17](https://linux-hardware.org/?probe=108cb2ce17) | Jun 01, 2023 |
| Dell          | 07WP95 A01                  | [b9f3afed0c](https://linux-hardware.org/?probe=b9f3afed0c) | May 31, 2023 |
| ASRock        | B450M Steel Legend          | [87c3dbc5df](https://linux-hardware.org/?probe=87c3dbc5df) | May 30, 2023 |
| Dell          | 07WP95 A01                  | [a58adc500e](https://linux-hardware.org/?probe=a58adc500e) | May 30, 2023 |
| Lenovo        | SHARKBAY NOK                | [a199dc360d](https://linux-hardware.org/?probe=a199dc360d) | May 29, 2023 |
| Lenovo        | 313A NOK                    | [a1ffbc1e1e](https://linux-hardware.org/?probe=a1ffbc1e1e) | May 27, 2023 |
| Gigabyte      | P75-D3P                     | [c341cbff1b](https://linux-hardware.org/?probe=c341cbff1b) | May 26, 2023 |
| Gigabyte      | A520M S2H                   | [93074475ac](https://linux-hardware.org/?probe=93074475ac) | May 22, 2023 |
| Acer          | Veriton M2610G              | [001e547ddf](https://linux-hardware.org/?probe=001e547ddf) | May 18, 2023 |
| ASUSTek       | D320SF                      | [bbfd29fb88](https://linux-hardware.org/?probe=bbfd29fb88) | May 08, 2023 |
| ASUSTek       | D320SF                      | [fdb3953309](https://linux-hardware.org/?probe=fdb3953309) | May 08, 2023 |
| Lenovo        | SHARKBAY NOK                | [e35b234e43](https://linux-hardware.org/?probe=e35b234e43) | May 07, 2023 |
| Dell          | 0YXT71 A01                  | [bbe145a1a2](https://linux-hardware.org/?probe=bbe145a1a2) | May 05, 2023 |
| Lenovo        | SHARKBAY NOK                | [2ebe14f5d0](https://linux-hardware.org/?probe=2ebe14f5d0) | May 04, 2023 |
| ASRock        | B550M-HDV                   | [408cbd96c0](https://linux-hardware.org/?probe=408cbd96c0) | May 04, 2023 |
| Lenovo        | SHARKBAY NOK                | [71bf54960f](https://linux-hardware.org/?probe=71bf54960f) | May 02, 2023 |
| Dell          | 040DDP A01                  | [bb212aa105](https://linux-hardware.org/?probe=bb212aa105) | Apr 19, 2023 |
| Dell          | 040DDP A01                  | [2b839be032](https://linux-hardware.org/?probe=2b839be032) | Apr 19, 2023 |
| Lenovo        | No DPK                      | [7028629b85](https://linux-hardware.org/?probe=7028629b85) | Apr 08, 2023 |
| ASRock        | B450 Steel Legend           | [add0dfc4ca](https://linux-hardware.org/?probe=add0dfc4ca) | Apr 05, 2023 |
| Acer          | Veriton N4630G              | [fab3140b7b](https://linux-hardware.org/?probe=fab3140b7b) | Mar 29, 2023 |
| ASUSTek       | PRIME B550M-K               | [81dc7d8f53](https://linux-hardware.org/?probe=81dc7d8f53) | Mar 27, 2023 |
| HP            | 802F                        | [89dadeeea6](https://linux-hardware.org/?probe=89dadeeea6) | Mar 22, 2023 |
| ASUSTek       | PRIME A320M-K               | [fda0ab85e6](https://linux-hardware.org/?probe=fda0ab85e6) | Mar 18, 2023 |
| ASUSTek       | Z97-K R2.0                  | [8c266d3142](https://linux-hardware.org/?probe=8c266d3142) | Mar 16, 2023 |
| ASUSTek       | PRIME H610M-K D4            | [9f33a01f8d](https://linux-hardware.org/?probe=9f33a01f8d) | Mar 15, 2023 |
| ASUSTek       | PRIME A320M-K               | [2a40386fb8](https://linux-hardware.org/?probe=2a40386fb8) | Mar 11, 2023 |
| Lenovo        | SHARKBAY NOK                | [89194cffbe](https://linux-hardware.org/?probe=89194cffbe) | Mar 11, 2023 |
| Lenovo        | SHARKBAY NOK                | [d674283cb0](https://linux-hardware.org/?probe=d674283cb0) | Mar 11, 2023 |
| Acer          | Veriton X4620G v1.0         | [fc27bc474e](https://linux-hardware.org/?probe=fc27bc474e) | Mar 11, 2023 |
| Acer          | Aspire TC-390               | [2d092d008e](https://linux-hardware.org/?probe=2d092d008e) | Mar 06, 2023 |
| ASRock        | B450M Pro4 R2.0             | [31376d711e](https://linux-hardware.org/?probe=31376d711e) | Mar 06, 2023 |
| ASRock        | G41M-GS3                    | [388f28c258](https://linux-hardware.org/?probe=388f28c258) | Mar 04, 2023 |
| ASUSTek       | PRIME B550M-K               | [91fab60d63](https://linux-hardware.org/?probe=91fab60d63) | Mar 04, 2023 |
| ASUSTek       | PRIME B550M-K               | [8ef1c9b71d](https://linux-hardware.org/?probe=8ef1c9b71d) | Mar 02, 2023 |
| ASUSTek       | PRIME B550M-K               | [588ac214ef](https://linux-hardware.org/?probe=588ac214ef) | Mar 01, 2023 |
| Dell          | 088DT1 A01                  | [715d043ec7](https://linux-hardware.org/?probe=715d043ec7) | Mar 01, 2023 |
| HP            | 1998                        | [145c009f05](https://linux-hardware.org/?probe=145c009f05) | Feb 24, 2023 |
| Dell          | 088DT1 A01                  | [990ffa68f4](https://linux-hardware.org/?probe=990ffa68f4) | Feb 23, 2023 |
| Dell          | 088DT1 A01                  | [73dde5b3db](https://linux-hardware.org/?probe=73dde5b3db) | Feb 22, 2023 |
| Acer          | Veriton N4630G              | [eb6a551e75](https://linux-hardware.org/?probe=eb6a551e75) | Feb 22, 2023 |
| Supermicro    | X10DRiB                     | [8e6438214d](https://linux-hardware.org/?probe=8e6438214d) | Feb 20, 2023 |
| Dell          | 040DDP A01                  | [6094b799d7](https://linux-hardware.org/?probe=6094b799d7) | Jan 31, 2023 |
| Gigabyte      | F2A68HM-DS2                 | [0fc911e254](https://linux-hardware.org/?probe=0fc911e254) | Jan 19, 2023 |
| Gigabyte      | B550M DS3H                  | [d24e1142ef](https://linux-hardware.org/?probe=d24e1142ef) | Jan 16, 2023 |
| Gigabyte      | B550M DS3H                  | [84d86434e8](https://linux-hardware.org/?probe=84d86434e8) | Jan 16, 2023 |
| Dell          | 054KM3 A00                  | [4ea59c00f3](https://linux-hardware.org/?probe=4ea59c00f3) | Jan 11, 2023 |
| ASUSTek       | M5A78L-M LE/USB3            | [e6ecb9037e](https://linux-hardware.org/?probe=e6ecb9037e) | Jan 10, 2023 |
| Gigabyte      | B650M DS3H                  | [a6d6bf8d28](https://linux-hardware.org/?probe=a6d6bf8d28) | Jan 08, 2023 |
| ASUSTek       | PRIME B550M-K               | [0c4e0afd97](https://linux-hardware.org/?probe=0c4e0afd97) | Jan 04, 2023 |
| ASUSTek       | PRIME B550M-K               | [43ff03b36f](https://linux-hardware.org/?probe=43ff03b36f) | Jan 03, 2023 |
| HP            | 802F                        | [22444b4b2c](https://linux-hardware.org/?probe=22444b4b2c) | Dec 31, 2022 |
| Gigabyte      | H61M-DS2                    | [50149bf9e3](https://linux-hardware.org/?probe=50149bf9e3) | Dec 29, 2022 |
| Gigabyte      | H61M-DS2                    | [b0a40a3ac0](https://linux-hardware.org/?probe=b0a40a3ac0) | Dec 29, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [2e23d15c25](https://linux-hardware.org/?probe=2e23d15c25) | Dec 24, 2022 |
| BESSTAR Te... | HM90                        | [3672c73d5a](https://linux-hardware.org/?probe=3672c73d5a) | Dec 24, 2022 |
| Gigabyte      | P75-D3P                     | [ff2420e759](https://linux-hardware.org/?probe=ff2420e759) | Dec 19, 2022 |
| ASUSTek       | PRIME B550M-K               | [0c496cdb01](https://linux-hardware.org/?probe=0c496cdb01) | Dec 17, 2022 |
| ASUSTek       | PRIME B550M-K               | [5148fddbd1](https://linux-hardware.org/?probe=5148fddbd1) | Dec 15, 2022 |
| Dell          | 0T10XW A02                  | [1539e12262](https://linux-hardware.org/?probe=1539e12262) | Dec 13, 2022 |
| Gigabyte      | 970A-D3                     | [89287418e8](https://linux-hardware.org/?probe=89287418e8) | Nov 23, 2022 |
| ASUSTek       | H81M-C                      | [8b44a7deaa](https://linux-hardware.org/?probe=8b44a7deaa) | Nov 21, 2022 |
| ASUSTek       | H81M-C                      | [e60a1f8fc4](https://linux-hardware.org/?probe=e60a1f8fc4) | Nov 20, 2022 |
| HP            | 82F2 A01                    | [b6cb9447df](https://linux-hardware.org/?probe=b6cb9447df) | Nov 19, 2022 |
| ASUSTek       | STRIX X99 GAMING            | [f111078004](https://linux-hardware.org/?probe=f111078004) | Oct 29, 2022 |
| ASUSTek       | STRIX X99 GAMING            | [b683357ec4](https://linux-hardware.org/?probe=b683357ec4) | Oct 28, 2022 |
| Gigabyte      | F2A88XM-HD3P                | [b5c41a9fef](https://linux-hardware.org/?probe=b5c41a9fef) | Oct 16, 2022 |
| ASRock        | B450 Steel Legend           | [b1de0617da](https://linux-hardware.org/?probe=b1de0617da) | Oct 15, 2022 |
| ASRock        | B450 Gaming K4              | [4b0116a8c6](https://linux-hardware.org/?probe=4b0116a8c6) | Oct 12, 2022 |
| Gigabyte      | X570 GAMING X               | [07f9a5063e](https://linux-hardware.org/?probe=07f9a5063e) | Sep 23, 2022 |
| ASRock        | B550M-ITX/ac                | [685e484cbd](https://linux-hardware.org/?probe=685e484cbd) | Aug 31, 2022 |
| Dell          | 0773VG A00                  | [576dfabbf6](https://linux-hardware.org/?probe=576dfabbf6) | Aug 29, 2022 |
| OEM           | Intel H81                   | [8732ebea02](https://linux-hardware.org/?probe=8732ebea02) | Aug 29, 2022 |
| OEM           | Intel H81                   | [cbedace60c](https://linux-hardware.org/?probe=cbedace60c) | Aug 25, 2022 |
| Gigabyte      | H81M-DS2                    | [e0abb12052](https://linux-hardware.org/?probe=e0abb12052) | Aug 16, 2022 |
| Gigabyte      | H81M-DS2                    | [5ae2bc3c12](https://linux-hardware.org/?probe=5ae2bc3c12) | Aug 14, 2022 |
| HP            | 8062                        | [0f24b44d56](https://linux-hardware.org/?probe=0f24b44d56) | Aug 14, 2022 |
| Dell          | 088DT1 A01                  | [eab28163ce](https://linux-hardware.org/?probe=eab28163ce) | Aug 09, 2022 |
| SHARKBAY      | Unknown                     | [a35fff735f](https://linux-hardware.org/?probe=a35fff735f) | Aug 09, 2022 |
| ASUSTek       | ROG Maximus X APEX          | [e1fa4e4923](https://linux-hardware.org/?probe=e1fa4e4923) | Jul 06, 2022 |
| MSI           | Z97 XPOWER AC               | [b7324cb6ab](https://linux-hardware.org/?probe=b7324cb6ab) | Jul 05, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [334719e6a2](https://linux-hardware.org/?probe=334719e6a2) | Jun 30, 2022 |
| ASRock        | B450 Steel Legend           | [6f8f8a9df6](https://linux-hardware.org/?probe=6f8f8a9df6) | Jun 26, 2022 |
| ASRock        | B450 Steel Legend           | [547aab5039](https://linux-hardware.org/?probe=547aab5039) | Jun 26, 2022 |
| AFOX          | AF IH81-MA3 V1.0            | [4ce7ccc125](https://linux-hardware.org/?probe=4ce7ccc125) | Jun 24, 2022 |
| Dell          | 04YP6J A02                  | [11151bb62c](https://linux-hardware.org/?probe=11151bb62c) | Jun 22, 2022 |
| Dell          | 0YXT71 A03                  | [890e65c781](https://linux-hardware.org/?probe=890e65c781) | Jun 19, 2022 |
| Gigabyte      | H310M S2H x.x               | [1cc4490d99](https://linux-hardware.org/?probe=1cc4490d99) | Jun 17, 2022 |
| ASUSTek       | PRIME B450M-K               | [e3bb4dee4b](https://linux-hardware.org/?probe=e3bb4dee4b) | Jun 17, 2022 |
| ASRock        | B450 Steel Legend           | [136730f4ac](https://linux-hardware.org/?probe=136730f4ac) | May 31, 2022 |
| ASRock        | B450 Steel Legend           | [62b7e9aacd](https://linux-hardware.org/?probe=62b7e9aacd) | May 31, 2022 |
| ASRock        | B450 Steel Legend           | [5d47d967ba](https://linux-hardware.org/?probe=5d47d967ba) | May 28, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [3dbf1858d0](https://linux-hardware.org/?probe=3dbf1858d0) | May 27, 2022 |
| ASRock        | B450 Steel Legend           | [3c436952c7](https://linux-hardware.org/?probe=3c436952c7) | May 21, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [ec0ec5ea27](https://linux-hardware.org/?probe=ec0ec5ea27) | May 15, 2022 |
| Intel         | D54250WYK H13922-305        | [6d1745c79b](https://linux-hardware.org/?probe=6d1745c79b) | May 11, 2022 |
| Dell          | 00V62H A00                  | [e765b34181](https://linux-hardware.org/?probe=e765b34181) | May 11, 2022 |
| HP            | 18E7                        | [52a59840d8](https://linux-hardware.org/?probe=52a59840d8) | May 09, 2022 |
| ASRock        | H370 Pro4                   | [ccf085e9dc](https://linux-hardware.org/?probe=ccf085e9dc) | May 02, 2022 |
| ASRock        | B450 Steel Legend           | [ecc527cb4b](https://linux-hardware.org/?probe=ecc527cb4b) | May 01, 2022 |
| ASRock        | B450 Steel Legend           | [ca217fe968](https://linux-hardware.org/?probe=ca217fe968) | May 01, 2022 |
| ASUSTek       | H81M-E                      | [b485d8f932](https://linux-hardware.org/?probe=b485d8f932) | Apr 28, 2022 |
| MSI           | MEG X570 UNIFY              | [4f7c3fc75d](https://linux-hardware.org/?probe=4f7c3fc75d) | Apr 26, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [be1e468728](https://linux-hardware.org/?probe=be1e468728) | Apr 17, 2022 |
| ASRock        | B460M-ITX/ac                | [7e6604d785](https://linux-hardware.org/?probe=7e6604d785) | Apr 12, 2022 |
| Gigabyte      | GA-970A-DS3                 | [db31622d02](https://linux-hardware.org/?probe=db31622d02) | Mar 21, 2022 |
| Gigabyte      | B450M S2H                   | [1602a60580](https://linux-hardware.org/?probe=1602a60580) | Mar 18, 2022 |
| ASRock        | B450 Steel Legend           | [db613d4f60](https://linux-hardware.org/?probe=db613d4f60) | Mar 16, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2            | [7a484a0d61](https://linux-hardware.org/?probe=7a484a0d61) | Mar 11, 2022 |
| ASRock        | H410M-HDV R2.0              | [0c91f1563f](https://linux-hardware.org/?probe=0c91f1563f) | Feb 14, 2022 |
| Unknown       | Intel X79                   | [f0dd6357fe](https://linux-hardware.org/?probe=f0dd6357fe) | Feb 12, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [9544722d31](https://linux-hardware.org/?probe=9544722d31) | Feb 12, 2022 |
| ASUSTek       | Z170-K                      | [ad24d41607](https://linux-hardware.org/?probe=ad24d41607) | Feb 08, 2022 |
| Unknown       | Intel X79                   | [089b663f84](https://linux-hardware.org/?probe=089b663f84) | Feb 06, 2022 |
| HP            | 1998                        | [263c4b1a93](https://linux-hardware.org/?probe=263c4b1a93) | Feb 03, 2022 |
| MSI           | MEG X570 UNIFY              | [5e8f4aba70](https://linux-hardware.org/?probe=5e8f4aba70) | Feb 03, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [4151d78b0a](https://linux-hardware.org/?probe=4151d78b0a) | Jan 14, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [322291a7b1](https://linux-hardware.org/?probe=322291a7b1) | Jan 14, 2022 |
| ASUSTek       | M5A78L-M LX3                | [39f3687349](https://linux-hardware.org/?probe=39f3687349) | Jan 12, 2022 |
| HP            | 82B4                        | [363fec4fa2](https://linux-hardware.org/?probe=363fec4fa2) | Jan 03, 2022 |
| ASRock        | M3A770DE                    | [92b50bf0b6](https://linux-hardware.org/?probe=92b50bf0b6) | Dec 27, 2021 |
| ASRock        | M3A770DE                    | [47fa1e385d](https://linux-hardware.org/?probe=47fa1e385d) | Dec 26, 2021 |
| HP            | 82B4                        | [02f9952fa5](https://linux-hardware.org/?probe=02f9952fa5) | Dec 24, 2021 |
| ASRock        | H510M-HVS R2.0              | [99e3241324](https://linux-hardware.org/?probe=99e3241324) | Dec 18, 2021 |
| MiTAC         | PD14RI                      | [e4dc1c326a](https://linux-hardware.org/?probe=e4dc1c326a) | Dec 16, 2021 |
| ASUSTek       | M5A78L-M LX3                | [720cc7a45f](https://linux-hardware.org/?probe=720cc7a45f) | Dec 15, 2021 |
| MSI           | Boston                      | [760fa25b63](https://linux-hardware.org/?probe=760fa25b63) | Dec 15, 2021 |
| MSI           | Boston                      | [bc4405aa85](https://linux-hardware.org/?probe=bc4405aa85) | Dec 15, 2021 |
| ASRock        | M3A770DE                    | [15671c0dbe](https://linux-hardware.org/?probe=15671c0dbe) | Dec 14, 2021 |
| MiTAC         | PD14RI                      | [acf3343fe7](https://linux-hardware.org/?probe=acf3343fe7) | Dec 13, 2021 |
| Gigabyte      | GA-970A-DS3                 | [e22dd08488](https://linux-hardware.org/?probe=e22dd08488) | Dec 02, 2021 |
| Gigabyte      | M52L-S3                     | [16854f2502](https://linux-hardware.org/?probe=16854f2502) | Nov 29, 2021 |
| Gigabyte      | M52L-S3                     | [e6f3417028](https://linux-hardware.org/?probe=e6f3417028) | Nov 27, 2021 |
| ASRock        | B450M Pro4                  | [6043e86d2a](https://linux-hardware.org/?probe=6043e86d2a) | Nov 24, 2021 |
| Gigabyte      | H110M-DS2V-CF               | [63edfe6809](https://linux-hardware.org/?probe=63edfe6809) | Nov 24, 2021 |
| Gigabyte      | H110M-DS2V-CF               | [a4986016ca](https://linux-hardware.org/?probe=a4986016ca) | Nov 23, 2021 |
| MSI           | 3666h                       | [21f11d2850](https://linux-hardware.org/?probe=21f11d2850) | Nov 19, 2021 |
| MSI           | 3666h                       | [aad8cfbf76](https://linux-hardware.org/?probe=aad8cfbf76) | Nov 18, 2021 |
| Dell          | 0YXT71 A02                  | [ff477e5a71](https://linux-hardware.org/?probe=ff477e5a71) | Oct 10, 2021 |
| Dell          | 0YXT71 A02                  | [f467bc83ef](https://linux-hardware.org/?probe=f467bc83ef) | Oct 10, 2021 |
| ASUSTek       | F1A55-M LX PLUS             | [3bf6f778dc](https://linux-hardware.org/?probe=3bf6f778dc) | Oct 10, 2021 |
| ASUSTek       | F1A55-M LX PLUS             | [f873a240d5](https://linux-hardware.org/?probe=f873a240d5) | Oct 10, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | [26e5760e58](https://linux-hardware.org/?probe=26e5760e58) | Oct 08, 2021 |
| ASUSTek       | F1A55-M LX PLUS             | [26b0b41886](https://linux-hardware.org/?probe=26b0b41886) | Sep 24, 2021 |
| Acer          | Aspire TC-885 V:1.1         | [71820e1f85](https://linux-hardware.org/?probe=71820e1f85) | Sep 18, 2021 |
| Gigabyte      | F2A68HM-DS2                 | [8ab840927b](https://linux-hardware.org/?probe=8ab840927b) | Sep 17, 2021 |
| HP            | 1497                        | [311efc294a](https://linux-hardware.org/?probe=311efc294a) | Sep 16, 2021 |
| ASRock        | 880GM-LE FX                 | [022e5df6bd](https://linux-hardware.org/?probe=022e5df6bd) | Sep 12, 2021 |
| ASRock        | 880GM-LE FX                 | [f7706441f2](https://linux-hardware.org/?probe=f7706441f2) | Sep 12, 2021 |
| Acer          | Aspire TC-885 V:1.1         | [04e6db02f9](https://linux-hardware.org/?probe=04e6db02f9) | Sep 02, 2021 |
| ASUSTek       | M2N68-AM Plus               | [57b648bd45](https://linux-hardware.org/?probe=57b648bd45) | Aug 23, 2021 |
| VIA Techno... | EITX-3002                   | [db8b46aea5](https://linux-hardware.org/?probe=db8b46aea5) | Aug 21, 2021 |
| ASUSTek       | H81M-A                      | [ae7b04d5d3](https://linux-hardware.org/?probe=ae7b04d5d3) | Aug 12, 2021 |
| Dell          | 0D24M8 A00                  | [c56bb51edc](https://linux-hardware.org/?probe=c56bb51edc) | Aug 03, 2021 |
| ASRock        | B450M Steel Legend          | [73a47bf698](https://linux-hardware.org/?probe=73a47bf698) | Aug 02, 2021 |
| HP            | 0AECh D                     | [be8dfa216f](https://linux-hardware.org/?probe=be8dfa216f) | Jul 31, 2021 |
| MSI           | Z270 GAMING PRO CARBON      | [71aae9e020](https://linux-hardware.org/?probe=71aae9e020) | Jul 26, 2021 |
| Dell          | 0NK5PH A00                  | [3db5dd7ea0](https://linux-hardware.org/?probe=3db5dd7ea0) | Jul 26, 2021 |
| ASRock        | B450M Steel Legend          | [b1d25f1e88](https://linux-hardware.org/?probe=b1d25f1e88) | Jul 22, 2021 |
| MSI           | Z270 GAMING PRO CARBON      | [568a71080e](https://linux-hardware.org/?probe=568a71080e) | Jul 21, 2021 |
| MSI           | Z270 GAMING PRO CARBON      | [6bf04f98f6](https://linux-hardware.org/?probe=6bf04f98f6) | Jul 21, 2021 |
| MSI           | MEG X570 UNIFY              | [c503220e78](https://linux-hardware.org/?probe=c503220e78) | Jul 19, 2021 |
| ASRock        | H81M-HDS R2.0               | [e46886ce2d](https://linux-hardware.org/?probe=e46886ce2d) | Jul 12, 2021 |
| ASRock        | B450M Steel Legend          | [c298371b89](https://linux-hardware.org/?probe=c298371b89) | Jul 12, 2021 |
| ASRock        | H81M-HDS R2.0               | [f51a4f44b2](https://linux-hardware.org/?probe=f51a4f44b2) | Jul 12, 2021 |
| ASRock        | H110M-DVS R3.0              | [2c6fd223a1](https://linux-hardware.org/?probe=2c6fd223a1) | Jul 07, 2021 |
| ASRock        | H110M-DVS R3.0              | [1270256228](https://linux-hardware.org/?probe=1270256228) | Jul 07, 2021 |
| Gigabyte      | H370M D3H-CF                | [e8c3804e26](https://linux-hardware.org/?probe=e8c3804e26) | Jun 25, 2021 |
| MSI           | B450M MORTAR MAX            | [db886610f5](https://linux-hardware.org/?probe=db886610f5) | Jun 11, 2021 |
| MSI           | A320M-A PRO MAX             | [45b8d7ca02](https://linux-hardware.org/?probe=45b8d7ca02) | Jun 08, 2021 |
| Intel         | H61M S1                     | [f60c55c8c4](https://linux-hardware.org/?probe=f60c55c8c4) | May 27, 2021 |
| Acer          | Veriton X2665G              | [f23ed8abd1](https://linux-hardware.org/?probe=f23ed8abd1) | Apr 20, 2021 |
| Huanan        | X79 249PC V2.2              | [787866050a](https://linux-hardware.org/?probe=787866050a) | Apr 03, 2021 |
| ASRock        | G31M-S                      | [ee71002286](https://linux-hardware.org/?probe=ee71002286) | Mar 26, 2021 |
| Huanan        | X79 V6.11                   | [85cbe2c1ed](https://linux-hardware.org/?probe=85cbe2c1ed) | Mar 16, 2021 |
| ASRock        | M3A770DE                    | [bca1dbaafd](https://linux-hardware.org/?probe=bca1dbaafd) | Mar 10, 2021 |
| ASRock        | B450M Steel Legend          | [465d5f43f1](https://linux-hardware.org/?probe=465d5f43f1) | Mar 08, 2021 |
| ASUSTek       | P5KPL-AM/PS                 | [32e4837219](https://linux-hardware.org/?probe=32e4837219) | Mar 05, 2021 |
| Gigabyte      | Z490 UD                     | [ec3e24bbcc](https://linux-hardware.org/?probe=ec3e24bbcc) | Mar 02, 2021 |
| Gigabyte      | F2A75M-HD2                  | [d8037b520e](https://linux-hardware.org/?probe=d8037b520e) | Feb 26, 2021 |
| Gigabyte      | H110M-DS2-CF                | [f1e66dfcc2](https://linux-hardware.org/?probe=f1e66dfcc2) | Feb 22, 2021 |
| ASUSTek       | P7P55D EVO                  | [90a83f66fc](https://linux-hardware.org/?probe=90a83f66fc) | Feb 21, 2021 |
| HP            | 1998                        | [c415742b9e](https://linux-hardware.org/?probe=c415742b9e) | Feb 13, 2021 |
| Dell          | 0F8096                      | [d6748871e7](https://linux-hardware.org/?probe=d6748871e7) | Feb 13, 2021 |
| Gigabyte      | H67MA-USB3-B3               | [bd0fcefe9f](https://linux-hardware.org/?probe=bd0fcefe9f) | Feb 13, 2021 |
| ASUSTek       | P5KPL-AM/PS                 | [da10acb66c](https://linux-hardware.org/?probe=da10acb66c) | Feb 07, 2021 |
| Dell          | 0F8096                      | [d6ce430a08](https://linux-hardware.org/?probe=d6ce430a08) | Feb 04, 2021 |
| Gigabyte      | G41M-ES2H                   | [53c32c80a6](https://linux-hardware.org/?probe=53c32c80a6) | Feb 03, 2021 |
| Acer          | Aspire M1935                | [64d53ff0ad](https://linux-hardware.org/?probe=64d53ff0ad) | Jan 28, 2021 |
| Fujitsu       | JIM76YK3                    | [4c5225559f](https://linux-hardware.org/?probe=4c5225559f) | Jan 23, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [6ba43f198a](https://linux-hardware.org/?probe=6ba43f198a) | Jan 22, 2021 |
| Fujitsu       | JIM76YK3                    | [b33ad621e1](https://linux-hardware.org/?probe=b33ad621e1) | Jan 07, 2021 |
| Gigabyte      | G31M-ES2L                   | [26d33eb0de](https://linux-hardware.org/?probe=26d33eb0de) | Jan 06, 2021 |
| ASUSTek       | PRIME A320M-K               | [9bcae82db8](https://linux-hardware.org/?probe=9bcae82db8) | Dec 16, 2020 |
| ASUSTek       | PRIME A320M-K               | [039b541097](https://linux-hardware.org/?probe=039b541097) | Dec 16, 2020 |
| ASRock        | Z390 Pro4                   | [3befcf341c](https://linux-hardware.org/?probe=3befcf341c) | Dec 14, 2020 |
| ASUSTek       | Z87-PRO                     | [a5170be239](https://linux-hardware.org/?probe=a5170be239) | Dec 11, 2020 |
| ASUSTek       | P8H61-M LE                  | [86f61c5fce](https://linux-hardware.org/?probe=86f61c5fce) | Dec 11, 2020 |
| Acer          | Aspire TC-885 V:1.1         | [813b0a40eb](https://linux-hardware.org/?probe=813b0a40eb) | Dec 01, 2020 |
| Unknown       | Unknown                     | [65fba277e7](https://linux-hardware.org/?probe=65fba277e7) | Nov 11, 2020 |
| Unknown       | Unknown                     | [2a8118e258](https://linux-hardware.org/?probe=2a8118e258) | Nov 11, 2020 |
| ASRock        | Z270 Killer SLI             | [42e012b0e1](https://linux-hardware.org/?probe=42e012b0e1) | Oct 19, 2020 |
| Gigabyte      | F2A85XM-HD3                 | [4a8bc27a98](https://linux-hardware.org/?probe=4a8bc27a98) | Oct 06, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [924b361628](https://linux-hardware.org/?probe=924b361628) | Oct 04, 2020 |
| Gigabyte      | Z97X-UD3H-CF                | [cce759037c](https://linux-hardware.org/?probe=cce759037c) | Oct 01, 2020 |
| ASUSTek       | P8H61-M LE                  | [93a29298d7](https://linux-hardware.org/?probe=93a29298d7) | Sep 29, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [c9ece9190b](https://linux-hardware.org/?probe=c9ece9190b) | Sep 27, 2020 |
| ASRock        | B460M Steel Legend          | [5398b2247d](https://linux-hardware.org/?probe=5398b2247d) | Sep 12, 2020 |
| ASRock        | B460M Steel Legend          | [44abe999aa](https://linux-hardware.org/?probe=44abe999aa) | Sep 12, 2020 |
| ASUSTek       | H110M-E/M.2                 | [25c77e6927](https://linux-hardware.org/?probe=25c77e6927) | Sep 11, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [2b4fe70eaf](https://linux-hardware.org/?probe=2b4fe70eaf) | Sep 04, 2020 |
| ASRock        | B450M Steel Legend          | [2aa3eef6bd](https://linux-hardware.org/?probe=2aa3eef6bd) | Sep 02, 2020 |
| Dell          | 0X8DXD A01                  | [0c6362ecb0](https://linux-hardware.org/?probe=0c6362ecb0) | Aug 24, 2020 |
| Acer          | Aspire TC-885 V:1.1         | [c90b90e1a8](https://linux-hardware.org/?probe=c90b90e1a8) | Aug 21, 2020 |
| ASRock        | Z77 Extreme6                | [a23bd9e79b](https://linux-hardware.org/?probe=a23bd9e79b) | Aug 19, 2020 |
| Gigabyte      | 970A-DS3P                   | [211cb85a6f](https://linux-hardware.org/?probe=211cb85a6f) | Aug 08, 2020 |
| ASRock        | B450 Pro4                   | [c318976f19](https://linux-hardware.org/?probe=c318976f19) | Jul 26, 2020 |
| Gigabyte      | P67A-UD3P-B3                | [d68a3e43ab](https://linux-hardware.org/?probe=d68a3e43ab) | Jul 25, 2020 |
| ASUSTek       | H110M-E/M.2                 | [f395c86ea3](https://linux-hardware.org/?probe=f395c86ea3) | Jul 05, 2020 |
| ASUSTek       | H61M-D                      | [ef9bd4541a](https://linux-hardware.org/?probe=ef9bd4541a) | Jun 27, 2020 |
| ASUSTek       | H61M-D                      | [d9b6cb6c0b](https://linux-hardware.org/?probe=d9b6cb6c0b) | Jun 27, 2020 |
| ASUSTek       | S340MF                      | [e8b7344421](https://linux-hardware.org/?probe=e8b7344421) | Jun 24, 2020 |
| ASUSTek       | P5G41T-M LX                 | [262f40d535](https://linux-hardware.org/?probe=262f40d535) | Jun 20, 2020 |
| Gigabyte      | Z390 UD                     | [1bd38851f2](https://linux-hardware.org/?probe=1bd38851f2) | Jun 13, 2020 |
| Acer          | Aspire TC-885 V:1.1         | [79456b5994](https://linux-hardware.org/?probe=79456b5994) | Jun 05, 2020 |
| Acer          | Aspire TC-885 V:1.1         | [f839493f2c](https://linux-hardware.org/?probe=f839493f2c) | Jun 05, 2020 |
| ASUSTek       | Z170-P D3                   | [859b71baa9](https://linux-hardware.org/?probe=859b71baa9) | Jun 01, 2020 |
| ASUSTek       | Z170-P D3                   | [2c3fadf526](https://linux-hardware.org/?probe=2c3fadf526) | Jun 01, 2020 |
| ASUSTek       | M2N                         | [383651de63](https://linux-hardware.org/?probe=383651de63) | May 26, 2020 |
| ASUSTek       | Z170-P D3                   | [94ad6c90d4](https://linux-hardware.org/?probe=94ad6c90d4) | May 21, 2020 |
| Unknown       | Unknown                     | [6f211d004a](https://linux-hardware.org/?probe=6f211d004a) | May 10, 2020 |
| Unknown       | Unknown                     | [b3ddb6ef68](https://linux-hardware.org/?probe=b3ddb6ef68) | May 09, 2020 |
| Unknown       | Unknown                     | [0a74b9927c](https://linux-hardware.org/?probe=0a74b9927c) | May 09, 2020 |
| ASUSTek       | PRIME X470-PRO              | [1275e05c7b](https://linux-hardware.org/?probe=1275e05c7b) | Apr 20, 2020 |
| Pegatron      | 2A99                        | [f01c0c56e7](https://linux-hardware.org/?probe=f01c0c56e7) | Apr 08, 2020 |
| Gigabyte      | B250-HD3-CF                 | [8958ee3446](https://linux-hardware.org/?probe=8958ee3446) | Apr 07, 2020 |
| ASUSTek       | P5G41T-M LX                 | [4a07604dd5](https://linux-hardware.org/?probe=4a07604dd5) | Apr 06, 2020 |
| ASUSTek       | P5G41T-M LX                 | [c5b4596173](https://linux-hardware.org/?probe=c5b4596173) | Apr 06, 2020 |
| Packard Be... | IMEDIA S3720                | [04ba71e930](https://linux-hardware.org/?probe=04ba71e930) | Feb 25, 2020 |
| Acer          | Aspire XC-330               | [168e69a32d](https://linux-hardware.org/?probe=168e69a32d) | Feb 11, 2020 |
| Acer          | Aspire XC-330               | [f1cbd72914](https://linux-hardware.org/?probe=f1cbd72914) | Feb 10, 2020 |
| Acer          | Aspire XC-330               | [0e517066e2](https://linux-hardware.org/?probe=0e517066e2) | Feb 08, 2020 |
| Acer          | Aspire XC-330               | [687cbfa242](https://linux-hardware.org/?probe=687cbfa242) | Feb 08, 2020 |
| HP            | 3048h                       | [ff1cde7e50](https://linux-hardware.org/?probe=ff1cde7e50) | Feb 04, 2020 |
| HP            | 3048h                       | [398e00244e](https://linux-hardware.org/?probe=398e00244e) | Feb 04, 2020 |
| HP            | 3048h                       | [69ac011884](https://linux-hardware.org/?probe=69ac011884) | Feb 04, 2020 |
| Gigabyte      | B250-HD3-CF                 | [a79eea9131](https://linux-hardware.org/?probe=a79eea9131) | Jan 30, 2020 |
| Gigabyte      | B250-HD3-CF                 | [d47fbd4f5c](https://linux-hardware.org/?probe=d47fbd4f5c) | Jan 30, 2020 |
| Acer          | MCP73VE NVIDIA MCP73        | [00b99ed436](https://linux-hardware.org/?probe=00b99ed436) | Jan 20, 2020 |
| Acer          | MCP73VE NVIDIA MCP73        | [1c91ad30fd](https://linux-hardware.org/?probe=1c91ad30fd) | Jan 19, 2020 |
| ASUSTek       | PRIME X470-PRO              | [eb0d14b4ad](https://linux-hardware.org/?probe=eb0d14b4ad) | Jan 18, 2020 |
| MSI           | X370 GAMING PRO CARBON      | [8827da4dc1](https://linux-hardware.org/?probe=8827da4dc1) | Jan 15, 2020 |
| Gigabyte      | B250-HD3-CF                 | [c228f44226](https://linux-hardware.org/?probe=c228f44226) | Jan 14, 2020 |
| MSI           | X370 GAMING PRO CARBON      | [dd045a2aef](https://linux-hardware.org/?probe=dd045a2aef) | Jan 13, 2020 |
| MSI           | X370 GAMING PRO CARBON      | [3fb9d0e024](https://linux-hardware.org/?probe=3fb9d0e024) | Jan 11, 2020 |
| MSI           | X370 GAMING PRO CARBON      | [4fae95f520](https://linux-hardware.org/?probe=4fae95f520) | Jan 10, 2020 |
| ASUSTek       | H110M-E/M.2                 | [f78dc97f63](https://linux-hardware.org/?probe=f78dc97f63) | Jan 07, 2020 |
| ASUSTek       | H110M-E/M.2                 | [0e11277c74](https://linux-hardware.org/?probe=0e11277c74) | Jan 06, 2020 |
| HP            | 2B15A                       | [24dd32836d](https://linux-hardware.org/?probe=24dd32836d) | Dec 14, 2019 |
| Acer          | Aspire TC-885 V:1.1         | [6d7723d13c](https://linux-hardware.org/?probe=6d7723d13c) | Dec 08, 2019 |
| MSI           | 760GM-P23                   | [bbd22621aa](https://linux-hardware.org/?probe=bbd22621aa) | Dec 05, 2019 |
| MSI           | B450M PRO-VDH PLUS          | [9f6b248a62](https://linux-hardware.org/?probe=9f6b248a62) | Nov 22, 2019 |
| ASUSTek       | H110M-E/M.2                 | [6a6a0d614e](https://linux-hardware.org/?probe=6a6a0d614e) | Oct 29, 2019 |
| ASUSTek       | H110M-E/M.2                 | [3d932d77ba](https://linux-hardware.org/?probe=3d932d77ba) | Oct 29, 2019 |
| MSI           | H110M PRO-VD PLUS           | [73bfd283e5](https://linux-hardware.org/?probe=73bfd283e5) | Oct 25, 2019 |
| ASUSTek       | PRIME Z370-A                | [7da594325d](https://linux-hardware.org/?probe=7da594325d) | Oct 07, 2019 |
| ASUSTek       | H81M-CS                     | [577f91eb8a](https://linux-hardware.org/?probe=577f91eb8a) | Aug 18, 2019 |
| ASUSTek       | H81M-E                      | [18e73b61d9](https://linux-hardware.org/?probe=18e73b61d9) | Aug 02, 2019 |
| MSI           | H170 GAMING M3              | [8b7204fcba](https://linux-hardware.org/?probe=8b7204fcba) | Jul 23, 2019 |
| Gigabyte      | F2A88XM-HD3P                | [7136ff50b4](https://linux-hardware.org/?probe=7136ff50b4) | Jul 04, 2019 |
| MSI           | 2A9C                        | [e4de30c7e4](https://linux-hardware.org/?probe=e4de30c7e4) | Jun 25, 2019 |
| Biostar       | A10N-8800E                  | [e160dec9cf](https://linux-hardware.org/?probe=e160dec9cf) | Jun 08, 2019 |
| ASUSTek       | P7P55 LX                    | [349a68f1f0](https://linux-hardware.org/?probe=349a68f1f0) | May 20, 2019 |
| ASUSTek       | P7P55 LX                    | [7c9e75ec67](https://linux-hardware.org/?probe=7c9e75ec67) | May 20, 2019 |
| MSI           | 2A9C                        | [d810098335](https://linux-hardware.org/?probe=d810098335) | May 09, 2019 |
| ASRock        | Z77 Pro4                    | [f0f2be33be](https://linux-hardware.org/?probe=f0f2be33be) | Apr 04, 2019 |
| ASRock        | Z77 Pro4                    | [04a8af85b2](https://linux-hardware.org/?probe=04a8af85b2) | Apr 03, 2019 |
| ASUSTek       | P8H61-M LE                  | [31229ee6d4](https://linux-hardware.org/?probe=31229ee6d4) | Feb 04, 2019 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [64fa4eaf5e](https://linux-hardware.org/?probe=64fa4eaf5e) | Nov 30, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 31       | 10.95%  |
| Ubuntu 18.04                 | 23       | 8.13%   |
| Ubuntu 22.04                 | 21       | 7.42%   |
| Ubuntu 24.04                 | 9        | 3.18%   |
| OpenMandriva 4.3             | 9        | 3.18%   |
| Fedora 38                    | 8        | 2.83%   |
| Arch Rolling                 | 8        | 2.83%   |
| OpenMandriva 4.2             | 7        | 2.47%   |
| OpenMandriva 23.08           | 7        | 2.47%   |
| Manjaro                      | 7        | 2.47%   |
| Debian 12                    | 6        | 2.12%   |
| ArcoLinux Rolling            | 5        | 1.77%   |
| OpenMandriva 23.01           | 4        | 1.41%   |
| Fedora 39                    | 4        | 1.41%   |
| Fedora 37                    | 4        | 1.41%   |
| Zorin 16                     | 3        | 1.06%   |
| Xubuntu 20.04                | 3        | 1.06%   |
| Xubuntu 18.04                | 3        | 1.06%   |
| Ubuntu 22.10                 | 3        | 1.06%   |
| Pop!_OS 22.04                | 3        | 1.06%   |
| openSUSE Tumbleweed-XXXXXXXX | 3        | 1.06%   |
| OpenMandriva 5.0             | 3        | 1.06%   |
| KDE neon 20.04               | 3        | 1.06%   |
| Fedora 40                    | 3        | 1.06%   |
| Debian 11                    | 3        | 1.06%   |
| Zorin 17                     | 2        | 0.71%   |
| Zorin 15                     | 2        | 0.71%   |
| Ubuntu 23.04                 | 2        | 0.71%   |
| Ubuntu 21.10                 | 2        | 0.71%   |
| Ubuntu 21.04                 | 2        | 0.71%   |
| Ubuntu 19.10                 | 2        | 0.71%   |
| Reborn OS                    | 2        | 0.71%   |
| OpenMandriva 24.07           | 2        | 0.71%   |
| OpenMandriva 23.03           | 2        | 0.71%   |
| Linux Mint 21.2              | 2        | 0.71%   |
| Linux Mint 21                | 2        | 0.71%   |
| Linux Mint 20.3              | 2        | 0.71%   |
| Linux Mint 20                | 2        | 0.71%   |
| Linux Mint 19.3              | 2        | 0.71%   |
| Kubuntu 24.04                | 2        | 0.71%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 93       | 34.96%  |
| OpenMandriva  | 37       | 13.91%  |
| Fedora        | 22       | 8.27%   |
| Linux Mint    | 13       | 4.89%   |
| Debian        | 12       | 4.51%   |
| Arch          | 10       | 3.76%   |
| Zorin         | 7        | 2.63%   |
| Xubuntu       | 7        | 2.63%   |
| Pop!_OS       | 7        | 2.63%   |
| Manjaro       | 7        | 2.63%   |
| Endless       | 6        | 2.26%   |
| KDE neon      | 5        | 1.88%   |
| ArcoLinux     | 5        | 1.88%   |
| openSUSE      | 4        | 1.5%    |
| Kubuntu       | 4        | 1.5%    |
| Kali          | 3        | 1.13%   |
| Ubuntu MATE   | 2        | 0.75%   |
| Reborn OS     | 2        | 0.75%   |
| NixOS         | 2        | 0.75%   |
| Elementary    | 2        | 0.75%   |
| Clear Linux   | 2        | 0.75%   |
| CentOS        | 2        | 0.75%   |
| Xero          | 1        | 0.38%   |
| UbuntuDDE     | 1        | 0.38%   |
| Ubuntu Budgie | 1        | 0.38%   |
| TUXEDO OS     | 1        | 0.38%   |
| SteamOS       | 1        | 0.38%   |
| Solus         | 1        | 0.38%   |
| Nobara        | 1        | 0.38%   |
| Mageia        | 1        | 0.38%   |
| GNOME OS      | 1        | 0.38%   |
| Gentoo        | 1        | 0.38%   |
| BlackPanther  | 1        | 0.38%   |
| Archcraft     | 1        | 0.38%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 6.4.11-desktop-1omv2390  | 7        | 2.22%   |
| 5.16.7-desktop-1omv4003  | 7        | 2.22%   |
| 5.10.14-desktop-1omv4002 | 7        | 2.22%   |
| 6.1.1-desktop-1omv2290   | 4        | 1.27%   |
| 5.4.0-48-generic         | 4        | 1.27%   |
| 5.15.0-56-generic        | 4        | 1.27%   |
| 5.15.0-46-generic        | 4        | 1.27%   |
| 6.8.0-48-generic         | 3        | 0.95%   |
| 6.6.2-desktop-1omv2390   | 3        | 0.95%   |
| 6.2.0-32-generic         | 3        | 0.95%   |
| 5.8.0-14-generic         | 3        | 0.95%   |
| 5.4.0-42-generic         | 3        | 0.95%   |
| 5.15.0-43-generic        | 3        | 0.95%   |
| 6.8.0-49-generic         | 2        | 0.63%   |
| 6.8.0-47-generic         | 2        | 0.63%   |
| 6.8.0-45-generic         | 2        | 0.63%   |
| 6.8.0-44-generic         | 2        | 0.63%   |
| 6.8.0-40-generic         | 2        | 0.63%   |
| 6.4.15-200.fc38.x86_64   | 2        | 0.63%   |
| 6.2.6-desktop-1omv2390   | 2        | 0.63%   |
| 6.2.15-300.fc38.x86_64   | 2        | 0.63%   |
| 6.2.0-37-generic         | 2        | 0.63%   |
| 6.2.0-26-generic         | 2        | 0.63%   |
| 6.12.1-desktop-1omv2490  | 2        | 0.63%   |
| 6.1.0-kali5-amd64        | 2        | 0.63%   |
| 6.1.0-12-amd64           | 2        | 0.63%   |
| 5.8.0-63-generic         | 2        | 0.63%   |
| 5.4.0-77-generic         | 2        | 0.63%   |
| 5.4.0-66-generic         | 2        | 0.63%   |
| 5.4.0-65-generic         | 2        | 0.63%   |
| 5.4.0-59-generic         | 2        | 0.63%   |
| 5.4.0-45-generic         | 2        | 0.63%   |
| 5.4.0-37-generic         | 2        | 0.63%   |
| 5.3.0-23-generic         | 2        | 0.63%   |
| 5.19.0-76051900-generic  | 2        | 0.63%   |
| 5.19.0-35-generic        | 2        | 0.63%   |
| 5.17.5-76051705-generic  | 2        | 0.63%   |
| 5.17.3-arch1-1           | 2        | 0.63%   |
| 5.16.13-desktop-1omv4003 | 2        | 0.63%   |
| 5.15.0-71-generic        | 2        | 0.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 34       | 11.11%  |
| 5.15.0  | 22       | 7.19%   |
| 6.8.0   | 15       | 4.9%    |
| 5.8.0   | 12       | 3.92%   |
| 5.13.0  | 12       | 3.92%   |
| 4.15.0  | 11       | 3.59%   |
| 6.5.0   | 10       | 3.27%   |
| 6.2.0   | 10       | 3.27%   |
| 6.4.11  | 8        | 2.61%   |
| 5.3.0   | 8        | 2.61%   |
| 5.19.0  | 7        | 2.29%   |
| 5.16.7  | 7        | 2.29%   |
| 5.11.0  | 7        | 2.29%   |
| 5.10.14 | 7        | 2.29%   |
| 5.0.0   | 7        | 2.29%   |
| 6.1.0   | 6        | 1.96%   |
| 4.18.0  | 5        | 1.63%   |
| 6.1.1   | 4        | 1.31%   |
| 6.6.2   | 3        | 0.98%   |
| 6.2.6   | 3        | 0.98%   |
| 5.17.5  | 3        | 0.98%   |
| 5.10.0  | 3        | 0.98%   |
| 6.9.8   | 2        | 0.65%   |
| 6.6.1   | 2        | 0.65%   |
| 6.5.7   | 2        | 0.65%   |
| 6.5.5   | 2        | 0.65%   |
| 6.4.15  | 2        | 0.65%   |
| 6.2.15  | 2        | 0.65%   |
| 6.2.14  | 2        | 0.65%   |
| 6.12.1  | 2        | 0.65%   |
| 6.10.0  | 2        | 0.65%   |
| 6.0.12  | 2        | 0.65%   |
| 5.5.7   | 2        | 0.65%   |
| 5.17.3  | 2        | 0.65%   |
| 5.16.13 | 2        | 0.65%   |
| 6.9.7   | 1        | 0.33%   |
| 6.9.3   | 1        | 0.33%   |
| 6.9.12  | 1        | 0.33%   |
| 6.8.7   | 1        | 0.33%   |
| 6.8.11  | 1        | 0.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 37       | 12.21%  |
| 5.15    | 25       | 8.25%   |
| 6.2     | 20       | 6.6%    |
| 6.5     | 19       | 6.27%   |
| 6.8     | 17       | 5.61%   |
| 5.13    | 15       | 4.95%   |
| 6.1     | 14       | 4.62%   |
| 5.16    | 14       | 4.62%   |
| 5.8     | 13       | 4.29%   |
| 6.6     | 11       | 3.63%   |
| 6.4     | 11       | 3.63%   |
| 5.10    | 11       | 3.63%   |
| 4.15    | 11       | 3.63%   |
| 5.3     | 9        | 2.97%   |
| 5.19    | 8        | 2.64%   |
| 5.17    | 8        | 2.64%   |
| 5.0     | 8        | 2.64%   |
| 5.11    | 7        | 2.31%   |
| 6.3     | 6        | 1.98%   |
| 6.10    | 6        | 1.98%   |
| 6.9     | 5        | 1.65%   |
| 4.18    | 5        | 1.65%   |
| 6.7     | 3        | 0.99%   |
| 5.6     | 3        | 0.99%   |
| 6.12    | 2        | 0.66%   |
| 6.11    | 2        | 0.66%   |
| 6.0     | 2        | 0.66%   |
| 5.5     | 2        | 0.66%   |
| 5.14    | 2        | 0.66%   |
| 5.9     | 1        | 0.33%   |
| 5.7     | 1        | 0.33%   |
| 5.18    | 1        | 0.33%   |
| 5.12    | 1        | 0.33%   |
| 5.1     | 1        | 0.33%   |
| 4.4     | 1        | 0.33%   |
| 4.17    | 1        | 0.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 251      | 99.6%   |
| i686   | 1        | 0.4%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| GNOME            | 134      | 50%     |
| KDE5             | 46       | 17.16%  |
| Unknown          | 28       | 10.45%  |
| XFCE             | 17       | 6.34%   |
| X-Cinnamon       | 13       | 4.85%   |
| LXQt             | 5        | 1.87%   |
| KDE              | 5        | 1.87%   |
| MATE             | 4        | 1.49%   |
| KDE6             | 3        | 1.12%   |
| Cinnamon         | 3        | 1.12%   |
| Pantheon         | 2        | 0.75%   |
| Deepin           | 2        | 0.75%   |
| Budgie           | 2        | 0.75%   |
| sway             | 1        | 0.37%   |
| lightdm-xsession | 1        | 0.37%   |
| i3               | 1        | 0.37%   |
| bspwm            | 1        | 0.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 170      | 65.38%  |
| Wayland | 68       | 26.15%  |
| Unknown | 16       | 6.15%   |
| Tty     | 6        | 2.31%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 127      | 47.92%  |
| SDDM    | 52       | 19.62%  |
| GDM3    | 43       | 16.23%  |
| GDM     | 23       | 8.68%   |
| LightDM | 16       | 6.04%   |
| TDM     | 3        | 1.13%   |
| GREETD  | 1        | 0.38%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 183      | 70.93%  |
| th_TH   | 17       | 6.59%   |
| Unknown | 16       | 6.2%    |
| en_GB   | 12       | 4.65%   |
| de_DE   | 12       | 4.65%   |
| C       | 7        | 2.71%   |
| it_IT   | 5        | 1.94%   |
| fi_FI   | 2        | 0.78%   |
| sv_SE   | 1        | 0.39%   |
| fr_FR   | 1        | 0.39%   |
| de_CH   | 1        | 0.39%   |
| C.UTF8  | 1        | 0.39%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 147      | 56.32%  |
| EFI  | 114      | 43.68%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 171      | 64.77%  |
| Overlay | 29       | 10.98%  |
| Tmpfs   | 28       | 10.61%  |
| Btrfs   | 27       | 10.23%  |
| Xfs     | 4        | 1.52%   |
| Unknown | 4        | 1.52%   |
| Zfs     | 1        | 0.38%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 133      | 50.57%  |
| GPT     | 116      | 44.11%  |
| MBR     | 14       | 5.32%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 206      | 78.93%  |
| Yes       | 55       | 21.07%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 170      | 64.89%  |
| Yes       | 92       | 35.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| Gigabyte Technology                  | 52       | 20.63%  |
| ASUSTek Computer                     | 47       | 18.65%  |
| ASRock                               | 39       | 15.48%  |
| Dell                                 | 27       | 10.71%  |
| MSI                                  | 19       | 7.54%   |
| Hewlett-Packard                      | 16       | 6.35%   |
| Acer                                 | 13       | 5.16%   |
| Lenovo                               | 6        | 2.38%   |
| Intel                                | 6        | 2.38%   |
| Unknown                              | 3        | 1.19%   |
| MiTAC                                | 2        | 0.79%   |
| Huanan                               | 2        | 0.79%   |
| Biostar                              | 2        | 0.79%   |
| Apple                                | 2        | 0.79%   |
| AMI                                  | 2        | 0.79%   |
| ViewSonic                            | 1        | 0.4%    |
| VIA Technologies                     | 1        | 0.4%    |
| Supermicro                           | 1        | 0.4%    |
| Shenzhen Meigao Electronic Equipment | 1        | 0.4%    |
| SHARKBAY                             | 1        | 0.4%    |
| Pegatron                             | 1        | 0.4%    |
| Packard Bell                         | 1        | 0.4%    |
| OEM                                  | 1        | 0.4%    |
| JINGSHA                              | 1        | 0.4%    |
| Google                               | 1        | 0.4%    |
| Fujitsu                              | 1        | 0.4%    |
| ECS                                  | 1        | 0.4%    |
| BESSTAR Tech                         | 1        | 0.4%    |
| AFOX                                 | 1        | 0.4%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                               | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| ASUS All Series                                    | 9        | 3.57%   |
| Dell OptiPlex 7010                                 | 4        | 1.59%   |
| ASRock B450 Steel Legend                           | 4        | 1.59%   |
| Unknown                                            | 4        | 1.59%   |
| Dell Inspiron 3847                                 | 3        | 1.19%   |
| ASUS P8H61-M LE                                    | 3        | 1.19%   |
| Acer Veriton N4640G                                | 3        | 1.19%   |
| Intel X99                                          | 2        | 0.79%   |
| HP Z240 Tower Workstation                          | 2        | 0.79%   |
| HP EliteDesk 800 G1 SFF PC                         | 2        | 0.79%   |
| HP Compaq 6200 Pro SFF PC                          | 2        | 0.79%   |
| Gigabyte Z97X-UD3H-BK                              | 2        | 0.79%   |
| Gigabyte H81M-DS2                                  | 2        | 0.79%   |
| Gigabyte H61M-DS2                                  | 2        | 0.79%   |
| Gigabyte H110M-DS2                                 | 2        | 0.79%   |
| Gigabyte F2A88XM-HD3P                              | 2        | 0.79%   |
| Gigabyte F2A68HM-DS2                               | 2        | 0.79%   |
| Gigabyte B250-HD3                                  | 2        | 0.79%   |
| Dell OptiPlex 9020                                 | 2        | 0.79%   |
| Dell OptiPlex 7050                                 | 2        | 0.79%   |
| Dell OptiPlex 3020                                 | 2        | 0.79%   |
| ASUS TUF Gaming B550M-E                            | 2        | 0.79%   |
| ASUS H110M-E/M.2                                   | 2        | 0.79%   |
| ASRock X570 Phantom Gaming 4                       | 2        | 0.79%   |
| ASRock B450M Steel Legend                          | 2        | 0.79%   |
| AMI Intel                                          | 2        | 0.79%   |
| Acer Aspire TC-885                                 | 2        | 0.79%   |
| ViewSonic VPC14-WP                                 | 1        | 0.4%    |
| VIA VX900                                          | 1        | 0.4%    |
| Supermicro AT350 F3                                | 1        | 0.4%    |
| Shenzhen Meigao Electronic Equipment Uranus Series | 1        | 0.4%    |
| Pegatron CQ3476L                                   | 1        | 0.4%    |
| Packard Bell IMEDIA S3720                          | 1        | 0.4%    |
| OEM Intel H81                                      | 1        | 0.4%    |
| MSI Pro 3130 Microtower PC                         | 1        | 0.4%    |
| MSI Pro 2000/2080                                  | 1        | 0.4%    |
| MSI p6772l                                         | 1        | 0.4%    |
| MSI MS-7C52                                        | 1        | 0.4%    |
| MSI MS-7C39                                        | 1        | 0.4%    |
| MSI MS-7C35                                        | 1        | 0.4%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 17       | 6.75%   |
| ASUS PRIME             | 9        | 3.57%   |
| ASUS All               | 9        | 3.57%   |
| Acer Veriton           | 7        | 2.78%   |
| ASRock B450            | 6        | 2.38%   |
| Acer Aspire            | 6        | 2.38%   |
| Dell Precision         | 5        | 1.98%   |
| HP EliteDesk           | 4        | 1.59%   |
| HP Compaq              | 4        | 1.59%   |
| ASUS ROG               | 4        | 1.59%   |
| ASUS M5A78L-M          | 4        | 1.59%   |
| ASRock B450M           | 4        | 1.59%   |
| Unknown                | 4        | 1.59%   |
| Lenovo ThinkCentre     | 3        | 1.19%   |
| HP ProDesk             | 3        | 1.19%   |
| Dell Inspiron          | 3        | 1.19%   |
| ASUS P8H61-M           | 3        | 1.19%   |
| ASRock X570            | 3        | 1.19%   |
| MSI Pro                | 2        | 0.79%   |
| Intel X99              | 2        | 0.79%   |
| Huanan X79             | 2        | 0.79%   |
| HP Z240                | 2        | 0.79%   |
| Gigabyte Z97X-UD3H-BK  | 2        | 0.79%   |
| Gigabyte Z390          | 2        | 0.79%   |
| Gigabyte H81M-DS2      | 2        | 0.79%   |
| Gigabyte H61M-DS2      | 2        | 0.79%   |
| Gigabyte H310M         | 2        | 0.79%   |
| Gigabyte H110M-DS2     | 2        | 0.79%   |
| Gigabyte GA-78LMT-USB3 | 2        | 0.79%   |
| Gigabyte F2A88XM-HD3P  | 2        | 0.79%   |
| Gigabyte F2A68HM-DS2   | 2        | 0.79%   |
| Gigabyte B550M         | 2        | 0.79%   |
| Gigabyte B450M         | 2        | 0.79%   |
| Gigabyte B450          | 2        | 0.79%   |
| Gigabyte B250-HD3      | 2        | 0.79%   |
| Dell Vostro            | 2        | 0.79%   |
| ASUS TUF               | 2        | 0.79%   |
| ASUS H110M-E           | 2        | 0.79%   |
| ASRock Z77             | 2        | 0.79%   |
| ASRock B550M           | 2        | 0.79%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 27       | 10.71%  |
| 2013 | 27       | 10.71%  |
| 2020 | 23       | 9.13%   |
| 2019 | 22       | 8.73%   |
| 2016 | 22       | 8.73%   |
| 2014 | 21       | 8.33%   |
| 2012 | 19       | 7.54%   |
| 2017 | 17       | 6.75%   |
| 2011 | 14       | 5.56%   |
| 2021 | 11       | 4.37%   |
| 2009 | 10       | 3.97%   |
| 2023 | 8        | 3.17%   |
| 2015 | 8        | 3.17%   |
| 2008 | 8        | 3.17%   |
| 2010 | 7        | 2.78%   |
| 2024 | 2        | 0.79%   |
| 2022 | 2        | 0.79%   |
| 2006 | 2        | 0.79%   |
| 2007 | 1        | 0.4%    |
| 2005 | 1        | 0.4%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 252      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 247      | 96.86%  |
| Enabled  | 8        | 3.14%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 251      | 99.6%   |
| Yes  | 1        | 0.4%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 67       | 25.48%  |
| 4.01-8.0        | 51       | 19.39%  |
| 8.01-16.0       | 50       | 19.01%  |
| 32.01-64.0      | 37       | 14.07%  |
| 3.01-4.0        | 37       | 14.07%  |
| 1.01-2.0        | 8        | 3.04%   |
| 64.01-256.0     | 7        | 2.66%   |
| 24.01-32.0      | 4        | 1.52%   |
| More than 256.0 | 1        | 0.38%   |
| 0.51-1.0        | 1        | 0.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 101      | 34.83%  |
| 2.01-3.0   | 87       | 30%     |
| 3.01-4.0   | 37       | 12.76%  |
| 4.01-8.0   | 36       | 12.41%  |
| 0.51-1.0   | 14       | 4.83%   |
| 8.01-16.0  | 10       | 3.45%   |
| 16.01-24.0 | 3        | 1.03%   |
| 24.01-32.0 | 1        | 0.34%   |
| 0.01-0.5   | 1        | 0.34%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 104      | 38.24%  |
| 2      | 80       | 29.41%  |
| 3      | 45       | 16.54%  |
| 4      | 17       | 6.25%   |
| 5      | 9        | 3.31%   |
| 0      | 6        | 2.21%   |
| 6      | 5        | 1.84%   |
| 10     | 2        | 0.74%   |
| 7      | 2        | 0.74%   |
| 51     | 1        | 0.37%   |
| 32     | 1        | 0.37%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 168      | 65.63%  |
| Yes       | 88       | 34.38%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 244      | 96.83%  |
| No        | 8        | 3.17%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 140      | 54.05%  |
| No        | 119      | 45.95%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 159      | 61.15%  |
| Yes       | 101      | 38.85%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| Thailand | 252      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Bangkok             | 97       | 36.19%  |
| Chiang Mai          | 24       | 8.96%   |
| Khon Kaen           | 10       | 3.73%   |
| Nakhon Pathom       | 9        | 3.36%   |
| Phuket              | 8        | 2.99%   |
| Nakhon Ratchasima   | 7        | 2.61%   |
| Chon Buri           | 6        | 2.24%   |
| Bang Lamung         | 6        | 2.24%   |
| Songkhla            | 5        | 1.87%   |
| Mueang Samut Prakan | 5        | 1.87%   |
| Ban Nong Sala       | 5        | 1.87%   |
| Surin               | 3        | 1.12%   |
| Si Racha            | 3        | 1.12%   |
| Phitsanulok         | 3        | 1.12%   |
| Pattaya             | 3        | 1.12%   |
| Pathum Thani        | 3        | 1.12%   |
| Nonthaburi          | 3        | 1.12%   |
| Ban Du              | 3        | 1.12%   |
| Pak Kret            | 2        | 0.75%   |
| Lampang             | 2        | 0.75%   |
| Ko Samui            | 2        | 0.75%   |
| Hua Hin             | 2        | 0.75%   |
| Bang Khae           | 2        | 0.75%   |
| Ban Phan Don        | 2        | 0.75%   |
| Ban Chang           | 2        | 0.75%   |
| Ban Bang Tanot      | 2        | 0.75%   |
| Yarang              | 1        | 0.37%   |
| Wihan Daeng         | 1        | 0.37%   |
| Wichian Buri        | 1        | 0.37%   |
| Trat                | 1        | 0.37%   |
| Thung Song          | 1        | 0.37%   |
| Tha Tako            | 1        | 0.37%   |
| Surat Thani         | 1        | 0.37%   |
| Suan Luang          | 1        | 0.37%   |
| Si Sa Ket           | 1        | 0.37%   |
| Sawang Daen Din     | 1        | 0.37%   |
| Saraburi            | 1        | 0.37%   |
| San Sai             | 1        | 0.37%   |
| Samut Songkhram     | 1        | 0.37%   |
| Samphanthawong      | 1        | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 108      | 198    | 23.03%  |
| Seagate                     | 82       | 148    | 17.48%  |
| Samsung Electronics         | 45       | 74     | 9.59%   |
| SanDisk                     | 34       | 59     | 7.25%   |
| Kingston                    | 24       | 26     | 5.12%   |
| Toshiba                     | 20       | 66     | 4.26%   |
| HS-SSD-C100                 | 11       | 25     | 2.35%   |
| Hitachi                     | 10       | 10     | 2.13%   |
| Crucial                     | 10       | 11     | 2.13%   |
| China                       | 8        | 14     | 1.71%   |
| Apacer                      | 8        | 10     | 1.71%   |
| Unknown                     | 7        | 12     | 1.49%   |
| MAXIO Technology (Hangzhou) | 7        | 8      | 1.49%   |
| Hikvision                   | 7        | 7      | 1.49%   |
| Intel                       | 6        | 6      | 1.28%   |
| Silicon Motion              | 5        | 6      | 1.07%   |
| Phison                      | 5        | 10     | 1.07%   |
| Realtek Semiconductor       | 4        | 4      | 0.85%   |
| KingSpec                    | 4        | 6      | 0.85%   |
| A-DATA Technology           | 4        | 7      | 0.85%   |
| USB3.0                      | 3        | 3      | 0.64%   |
| TO Exter                    | 3        | 3      | 0.64%   |
| SPCC                        | 3        | 3      | 0.64%   |
| Phison Electronics          | 3        | 3      | 0.64%   |
| JMicron Technology          | 3        | 3      | 0.64%   |
| HGST                        | 3        | 11     | 0.64%   |
| GALAX                       | 3        | 3      | 0.64%   |
| Colorful                    | 3        | 4      | 0.64%   |
| walram                      | 2        | 3      | 0.43%   |
| Transcend                   | 2        | 2      | 0.43%   |
| SK hynix                    | 2        | 3      | 0.43%   |
| Plextor                     | 2        | 2      | 0.43%   |
| Micron Technology           | 2        | 2      | 0.43%   |
| Lexar                       | 2        | 3      | 0.43%   |
| Hewlett-Packard             | 2        | 4      | 0.43%   |
| External                    | 2        | 2      | 0.43%   |
| Corsair                     | 2        | 2      | 0.43%   |
| Acer                        | 2        | 6      | 0.43%   |
| Verbatim                    | 1        | 1      | 0.21%   |
| SPCC M.2                    | 1        | 1      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB                       | 10       | 1.82%   |
| Seagate ST1000DM010-2EP102 1TB                        | 9        | 1.64%   |
| Seagate ST1000DM003-1ER162 1TB                        | 9        | 1.64%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                      | 6        | 1.09%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 6        | 1.09%   |
| WDC WD10EZEX-00WN4A0 1TB                              | 6        | 1.09%   |
| Seagate ST2000VX008-2E3164 2TB                        | 6        | 1.09%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 512GB    | 6        | 1.09%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                      | 5        | 0.91%   |
| WDC WD20EZAZ-00GGJB0 2TB                              | 5        | 0.91%   |
| Toshiba DT01ACA100 1TB                                | 5        | 0.91%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                  | 5        | 0.91%   |
| SanDisk NVMe SSD Drive 1TB                            | 5        | 0.91%   |
| Samsung HD103SJ 1TB                                   | 5        | 0.91%   |
| Kingston SUV400S37120G 120GB SSD                      | 5        | 0.91%   |
| Kingston SA400S37240G 240GB SSD                       | 5        | 0.91%   |
| HS-SSD-C100 240G                                      | 5        | 0.91%   |
| HS-SSD-C100 120G                                      | 5        | 0.91%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 4        | 0.73%   |
| WDC WD5000AAKX-001CA0 500GB                           | 4        | 0.73%   |
| WDC WD10EZEX-60WN4A0 1TB                              | 4        | 0.73%   |
| Crucial CT500MX500SSD1 500GB                          | 4        | 0.73%   |
| WDC WD5000AAKX-00ERMA0 500GB                          | 3        | 0.55%   |
| WDC WD30EFRX-68EUZN0 3TB                              | 3        | 0.55%   |
| WDC WD2002FAEX-007BA0 2TB                             | 3        | 0.55%   |
| WDC WD10EZEX-00MFCA0 1TB                              | 3        | 0.55%   |
| WDC WD10EZEX-00BBHA0 1TB                              | 3        | 0.55%   |
| USB3.0 Super Speed 500GB SSD                          | 3        | 0.55%   |
| Unknown SD/MMC/MS PRO 128GB                           | 3        | 0.55%   |
| TO Exter nal USB 3.0 1024GB                           | 3        | 0.55%   |
| Seagate ST3500418AS 500GB                             | 3        | 0.55%   |
| Seagate ST2000DX002-2DV164 2TB                        | 3        | 0.55%   |
| Seagate ST2000DM006-2DM164 2TB                        | 3        | 0.55%   |
| Seagate ST1000DM003-1SB102 1TB                        | 3        | 0.55%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD 512GB | 3        | 0.55%   |
| SanDisk SDSSDA120G 120GB                              | 3        | 0.55%   |
| SanDisk NVMe SSD Drive 250GB                          | 3        | 0.55%   |
| Samsung SSD 850 EVO 250GB                             | 3        | 0.55%   |
| Samsung SSD 850 120GB                                 | 3        | 0.55%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB                | 3        | 0.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 86       | 146    | 38.39%  |
| Seagate             | 80       | 140    | 35.71%  |
| Toshiba             | 19       | 65     | 8.48%   |
| Samsung Electronics | 12       | 19     | 5.36%   |
| Hitachi             | 10       | 10     | 4.46%   |
| Unknown             | 4        | 9      | 1.79%   |
| TO Exter            | 3        | 3      | 1.34%   |
| HGST                | 3        | 11     | 1.34%   |
| JMicron Technology  | 2        | 2      | 0.89%   |
| External            | 2        | 2      | 0.89%   |
| Hewlett-Packard     | 1        | 3      | 0.45%   |
| Fujitsu             | 1        | 2      | 0.45%   |
| ASMedia             | 1        | 1      | 0.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 26       | 40     | 16.46%  |
| Samsung Electronics | 23       | 36     | 14.56%  |
| Kingston            | 18       | 19     | 11.39%  |
| SanDisk             | 12       | 21     | 7.59%   |
| Crucial             | 10       | 11     | 6.33%   |
| China               | 8        | 14     | 5.06%   |
| Apacer              | 8        | 10     | 5.06%   |
| Intel               | 5        | 5      | 3.16%   |
| Hikvision           | 5        | 5      | 3.16%   |
| KingSpec            | 4        | 6      | 2.53%   |
| USB3.0              | 3        | 3      | 1.9%    |
| SPCC                | 3        | 3      | 1.9%    |
| GALAX               | 3        | 3      | 1.9%    |
| A-DATA Technology   | 3        | 6      | 1.9%    |
| WALRAM              | 2        | 2      | 1.27%   |
| Plextor             | 2        | 2      | 1.27%   |
| Micron Technology   | 2        | 2      | 1.27%   |
| Lexar               | 2        | 3      | 1.27%   |
| Colorful            | 2        | 3      | 1.27%   |
| Acer                | 2        | 6      | 1.27%   |
| Verbatim            | 1        | 1      | 0.63%   |
| Transcend           | 1        | 1      | 0.63%   |
| SPCC M.2            | 1        | 1      | 0.63%   |
| SK hynix            | 1        | 2      | 0.63%   |
| PNY                 | 1        | 1      | 0.63%   |
| Pioneer             | 1        | 1      | 0.63%   |
| OCZ                 | 1        | 1      | 0.63%   |
| LITEON              | 1        | 1      | 0.63%   |
| Intenso             | 1        | 12     | 0.63%   |
| HS-SSD-E100         | 1        | 1      | 0.63%   |
| HS-SSD-C100         | 1        | 1      | 0.63%   |
| Hewlett-Packard     | 1        | 1      | 0.63%   |
| DGM                 | 1        | 1      | 0.63%   |
| Corsair             | 1        | 1      | 0.63%   |
| addlink             | 1        | 1      | 0.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 170      | 413    | 43.15%  |
| SSD     | 127      | 227    | 32.23%  |
| NVMe    | 76       | 117    | 19.29%  |
| Unknown | 21       | 40     | 5.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 231      | 632    | 68.75%  |
| NVMe | 76       | 117    | 22.62%  |
| SAS  | 29       | 48     | 8.63%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 163      | 292    | 47.8%   |
| 0.51-1.0   | 100      | 164    | 29.33%  |
| 1.01-2.0   | 47       | 73     | 13.78%  |
| 3.01-4.0   | 14       | 64     | 4.11%   |
| 2.01-3.0   | 8        | 17     | 2.35%   |
| 4.01-10.0  | 7        | 19     | 2.05%   |
| 10.01-20.0 | 2        | 11     | 0.59%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 73       | 26.74%  |
| 251-500        | 44       | 16.12%  |
| 501-1000       | 38       | 13.92%  |
| 1-20           | 31       | 11.36%  |
| 1001-2000      | 23       | 8.42%   |
| 2001-3000      | 19       | 6.96%   |
| More than 3000 | 16       | 5.86%   |
| 51-100         | 14       | 5.13%   |
| 21-50          | 10       | 3.66%   |
| Unknown        | 5        | 1.83%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 106      | 37.32%  |
| 21-50          | 48       | 16.9%   |
| 101-250        | 32       | 11.27%  |
| 51-100         | 31       | 10.92%  |
| 501-1000       | 20       | 7.04%   |
| 251-500        | 18       | 6.34%   |
| More than 3000 | 11       | 3.87%   |
| 1001-2000      | 10       | 3.52%   |
| Unknown        | 5        | 1.76%   |
| 2001-3000      | 3        | 1.06%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| WDC WD2002FAEX-007BA0 2TB                | 3        | 3      | 9.68%   |
| Seagate ST500DM002-1BD14 500GB           | 2        | 3      | 6.45%   |
| Samsung Electronics SSD 830 Series 128GB | 2        | 2      | 6.45%   |
| WDC WDS240G2G0A-00JH30 240GB SSD         | 1        | 1      | 3.23%   |
| WDC WD6402AAEX-00Y9A0 640GB              | 1        | 1      | 3.23%   |
| WDC WD20EZRX-00DC0B0 2TB                 | 1        | 1      | 3.23%   |
| WDC WD20EARS-00MVWB0 2TB                 | 1        | 1      | 3.23%   |
| WDC WD10PURX-64E5EY0 1TB                 | 1        | 1      | 3.23%   |
| WDC WD10EZEX-08WN4A0 1TB                 | 1        | 1      | 3.23%   |
| WDC WD10EZEX-00WN4A0 1TB                 | 1        | 1      | 3.23%   |
| WDC WD10EARX-00N0YB0 1TB                 | 1        | 1      | 3.23%   |
| WDC WD1002FAEX-00Y9A0 1TB                | 1        | 1      | 3.23%   |
| USB3.0 Super Speed 500GB SSD             | 1        | 1      | 3.23%   |
| Toshiba HDWL110 1TB                      | 1        | 1      | 3.23%   |
| Seagate ST9120822AS 120GB                | 1        | 1      | 3.23%   |
| Seagate ST500LT012-9WS142 500GB          | 1        | 1      | 3.23%   |
| Seagate ST500DM002-1BD142 500GB          | 1        | 1      | 3.23%   |
| Seagate ST4000DM004-2CV104 4TB           | 1        | 1      | 3.23%   |
| Seagate ST3500418AS 500GB                | 1        | 2      | 3.23%   |
| Seagate ST2000DM006-2DM164 2TB           | 1        | 1      | 3.23%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 1        | 1      | 3.23%   |
| Seagate ST1000LM014-1EJ164 1TB           | 1        | 1      | 3.23%   |
| Samsung Electronics HD322GJ 320GB        | 1        | 2      | 3.23%   |
| Samsung Electronics HD253GJ 250GB        | 1        | 2      | 3.23%   |
| Samsung Electronics HD103SJ 1TB          | 1        | 1      | 3.23%   |
| Kingston SV300S37A120G 120GB SSD         | 1        | 1      | 3.23%   |
| Hitachi HTS541612J9SA00 120GB            | 1        | 1      | 3.23%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 11       | 12     | 36.67%  |
| Seagate             | 10       | 12     | 33.33%  |
| Samsung Electronics | 5        | 7      | 16.67%  |
| USB3.0              | 1        | 1      | 3.33%   |
| Toshiba             | 1        | 1      | 3.33%   |
| Kingston            | 1        | 1      | 3.33%   |
| Hitachi             | 1        | 1      | 3.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 10       | 11     | 40%     |
| Seagate             | 10       | 12     | 40%     |
| Samsung Electronics | 3        | 5      | 12%     |
| Toshiba             | 1        | 1      | 4%      |
| Hitachi             | 1        | 1      | 4%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 24       | 30     | 82.76%  |
| SSD  | 5        | 5      | 17.24%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Samsung Electronics HD103SJ 1TB | 2        | 2      | 66.67%  |
| WDC WD30EFRX-68EUZN0 3TB        | 1        | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 2        | 2      | 66.67%  |
| WDC                 | 1        | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 175      | 468    | 59.73%  |
| Works    | 88       | 291    | 30.03%  |
| Malfunc  | 27       | 35     | 9.22%   |
| Failed   | 3        | 3      | 1.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 167      | 47.31%  |
| AMD                          | 73       | 20.68%  |
| SanDisk                      | 30       | 8.5%    |
| ASMedia Technology           | 15       | 4.25%   |
| Samsung Electronics          | 12       | 3.4%    |
| MAXIO Technology (Hangzhou)  | 10       | 2.83%   |
| Phison Electronics           | 9        | 2.55%   |
| Nvidia                       | 7        | 1.98%   |
| Kingston Technology Company  | 7        | 1.98%   |
| Silicon Motion               | 5        | 1.42%   |
| Realtek Semiconductor        | 4        | 1.13%   |
| Marvell Technology Group     | 3        | 0.85%   |
| VIA Technologies             | 2        | 0.57%   |
| JMicron Technology           | 2        | 0.57%   |
| Broadcom / LSI               | 2        | 0.57%   |
| Toshiba America Info Systems | 1        | 0.28%   |
| SK hynix                     | 1        | 0.28%   |
| Micron/Crucial Technology    | 1        | 0.28%   |
| LSI Logic / Symbios Logic    | 1        | 0.28%   |
| ADATA Technology             | 1        | 0.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 39       | 9.15%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 26       | 6.1%    |
| AMD 400 Series Chipset SATA Controller                                                  | 22       | 5.16%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 19       | 4.46%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 16       | 3.76%   |
| AMD 500 Series Chipset SATA Controller                                                  | 14       | 3.29%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 12       | 2.82%   |
| Intel SATA Controller [RAID Mode]                                                       | 11       | 2.58%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 11       | 2.58%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 11       | 2.58%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 10       | 2.35%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 10       | 2.35%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 10       | 2.35%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 9        | 2.11%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8        | 1.88%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 8        | 1.88%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 8        | 1.88%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                             | 6        | 1.41%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 6        | 1.41%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 6        | 1.41%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 5        | 1.17%   |
| Nvidia MCP61 SATA Controller                                                            | 5        | 1.17%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 5        | 1.17%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 1.17%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 1.17%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 1.17%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 5        | 1.17%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 1.17%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 4        | 0.94%   |
| Nvidia MCP61 IDE                                                                        | 4        | 0.94%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 4        | 0.94%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                 | 3        | 0.7%    |
| SanDisk PC SN735 / WD_BLACK SN750 SE NVMe SSD (DRAM-less)                               | 3        | 0.7%    |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                                       | 3        | 0.7%    |
| Phison E12 NVMe Controller                                                              | 3        | 0.7%    |
| Kingston Company A2000 NVMe SSD [SM2263EN]                                              | 3        | 0.7%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 3        | 0.7%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3        | 0.7%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3        | 0.7%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3        | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 212      | 60.23%  |
| NVMe | 77       | 21.88%  |
| IDE  | 45       | 12.78%  |
| RAID | 16       | 4.55%   |
| SAS  | 1        | 0.28%   |
| SCSI | 1        | 0.28%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 172      | 68.25%  |
| AMD          | 79       | 31.35%  |
| CentaurHauls | 1        | 0.4%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Core i3-2120 CPU @ 3.30GHz       | 7        | 2.75%   |
| AMD Ryzen 5 3600 6-Core Processor      | 7        | 2.75%   |
| Intel Core i5-6500 CPU @ 3.20GHz       | 6        | 2.35%   |
| Intel Core i7-6700 CPU @ 3.40GHz       | 5        | 1.96%   |
| Intel Core i7-4790 CPU @ 3.60GHz       | 5        | 1.96%   |
| Intel Core i7-4770 CPU @ 3.40GHz       | 4        | 1.57%   |
| Intel Core i5-8400 CPU @ 2.80GHz       | 4        | 1.57%   |
| AMD Ryzen 5 2600 Six-Core Processor    | 4        | 1.57%   |
| Intel Core i9-9900K CPU @ 3.60GHz      | 3        | 1.18%   |
| Intel Core i7-4770K CPU @ 3.50GHz      | 3        | 1.18%   |
| Intel Core i5-6400T CPU @ 2.20GHz      | 3        | 1.18%   |
| Intel Core i5-4590 CPU @ 3.30GHz       | 3        | 1.18%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 3        | 1.18%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 3        | 1.18%   |
| Intel Core i3-7100 CPU @ 3.90GHz       | 3        | 1.18%   |
| Intel Core i3-4160 CPU @ 3.60GHz       | 3        | 1.18%   |
| Intel Core i3-3220 CPU @ 3.30GHz       | 3        | 1.18%   |
| AMD Ryzen 7 2700X Eight-Core Processor | 3        | 1.18%   |
| AMD Ryzen 7 2700 Eight-Core Processor  | 3        | 1.18%   |
| AMD Ryzen 5 5600X 6-Core Processor     | 3        | 1.18%   |
| AMD Ryzen 5 5600G with Radeon Graphics | 3        | 1.18%   |
| AMD Ryzen 5 1600 Six-Core Processor    | 3        | 1.18%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz    | 2        | 0.78%   |
| Intel Core i7-7700 CPU @ 3.60GHz       | 2        | 0.78%   |
| Intel Core i7-3770K CPU @ 3.50GHz      | 2        | 0.78%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 2        | 0.78%   |
| Intel Core i7-10700 CPU @ 2.90GHz      | 2        | 0.78%   |
| Intel Core i5-9400 CPU @ 2.90GHz       | 2        | 0.78%   |
| Intel Core i5-7500 CPU @ 3.40GHz       | 2        | 0.78%   |
| Intel Core i5-6400 CPU @ 2.70GHz       | 2        | 0.78%   |
| Intel Core i5-4440 CPU @ 3.10GHz       | 2        | 0.78%   |
| Intel Core i5-3570 CPU @ 3.40GHz       | 2        | 0.78%   |
| Intel Core i5-3470 CPU @ 3.20GHz       | 2        | 0.78%   |
| Intel Core i5-2500K CPU @ 3.30GHz      | 2        | 0.78%   |
| Intel Core i5 CPU 750 @ 2.67GHz        | 2        | 0.78%   |
| Intel Core i3-6100 CPU @ 3.70GHz       | 2        | 0.78%   |
| Intel Core i3-4150 CPU @ 3.50GHz       | 2        | 0.78%   |
| Intel Core i3-4130 CPU @ 3.40GHz       | 2        | 0.78%   |
| Intel Core i3-3217U CPU @ 1.80GHz      | 2        | 0.78%   |
| Intel Core i3-10100F CPU @ 3.60GHz     | 2        | 0.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 54       | 21.26%  |
| Intel Core i3           | 38       | 14.96%  |
| Intel Core i7           | 35       | 13.78%  |
| AMD Ryzen 5             | 28       | 11.02%  |
| Intel Xeon              | 17       | 6.69%   |
| AMD Ryzen 7             | 10       | 3.94%   |
| AMD Ryzen 3             | 6        | 2.36%   |
| AMD FX                  | 6        | 2.36%   |
| Intel Pentium           | 5        | 1.97%   |
| Intel Core 2 Quad       | 5        | 1.97%   |
| AMD Ryzen 9             | 5        | 1.97%   |
| AMD Athlon II X2        | 5        | 1.97%   |
| Intel Core i9           | 4        | 1.57%   |
| AMD Athlon 64 X2        | 4        | 1.57%   |
| AMD A10                 | 4        | 1.57%   |
| Other                   | 3        | 1.18%   |
| Intel Pentium Dual-Core | 3        | 1.18%   |
| Intel Celeron           | 3        | 1.18%   |
| AMD A6                  | 3        | 1.18%   |
| Intel Core 2 Duo        | 2        | 0.79%   |
| AMD Phenom II X6        | 2        | 0.79%   |
| AMD Phenom II X4        | 2        | 0.79%   |
| AMD A4                  | 2        | 0.79%   |
| Intel Pentium Dual      | 1        | 0.39%   |
| Intel Pentium D         | 1        | 0.39%   |
| Intel Pentium 4         | 1        | 0.39%   |
| Intel Atom              | 1        | 0.39%   |
| CentaurHauls VIA Eden   | 1        | 0.39%   |
| AMD Ryzen 3 PRO         | 1        | 0.39%   |
| AMD Phenom II X3        | 1        | 0.39%   |
| AMD Athlon              | 1        | 0.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 102      | 40.16%  |
| 2      | 66       | 25.98%  |
| 6      | 43       | 16.93%  |
| 8      | 22       | 8.66%   |
| 12     | 7        | 2.76%   |
| 1      | 4        | 1.57%   |
| 14     | 2        | 0.79%   |
| 10     | 2        | 0.79%   |
| 3      | 2        | 0.79%   |
| 40     | 1        | 0.39%   |
| 28     | 1        | 0.39%   |
| 24     | 1        | 0.39%   |
| 16     | 1        | 0.39%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 246      | 97.62%  |
| 2      | 6        | 2.38%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 156      | 61.66%  |
| 1      | 97       | 38.34%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 252      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 118      | 43.7%   |
| 0x306c3    | 19       | 7.04%   |
| 0x206a7    | 11       | 4.07%   |
| 0x506e3    | 10       | 3.7%    |
| 0x906ea    | 7        | 2.59%   |
| 0x906e9    | 7        | 2.59%   |
| 0x306a9    | 7        | 2.59%   |
| 0x1067a    | 6        | 2.22%   |
| 0x0800820d | 6        | 2.22%   |
| 0x06001119 | 5        | 1.85%   |
| 0x08701021 | 4        | 1.48%   |
| 0x010000c8 | 4        | 1.48%   |
| 0xa0655    | 3        | 1.11%   |
| 0x906ec    | 3        | 1.11%   |
| 0x406f1    | 3        | 1.11%   |
| 0x20655    | 3        | 1.11%   |
| 0x08001138 | 3        | 1.11%   |
| 0x906eb    | 2        | 0.74%   |
| 0x40651    | 2        | 0.74%   |
| 0x106e5    | 2        | 0.74%   |
| 0x0a50000c | 2        | 0.74%   |
| 0x0a201009 | 2        | 0.74%   |
| 0x08600106 | 2        | 0.74%   |
| 0x08108109 | 2        | 0.74%   |
| 0x06003106 | 2        | 0.74%   |
| 0x06000852 | 2        | 0.74%   |
| 0xf65      | 1        | 0.37%   |
| 0xf49      | 1        | 0.37%   |
| 0xa0653    | 1        | 0.37%   |
| 0x906ed    | 1        | 0.37%   |
| 0x6fd      | 1        | 0.37%   |
| 0x6fb      | 1        | 0.37%   |
| 0x50654    | 1        | 0.37%   |
| 0x406c3    | 1        | 0.37%   |
| 0x306e4    | 1        | 0.37%   |
| 0x30678    | 1        | 0.37%   |
| 0x206c2    | 1        | 0.37%   |
| 0x106ca    | 1        | 0.37%   |
| 0x10677    | 1        | 0.37%   |
| 0x10676    | 1        | 0.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 39       | 15.42%  |
| KabyLake         | 28       | 11.07%  |
| Skylake          | 22       | 8.7%    |
| Zen 2            | 19       | 7.51%   |
| IvyBridge        | 19       | 7.51%   |
| SandyBridge      | 17       | 6.72%   |
| Zen+             | 13       | 5.14%   |
| Zen 3            | 10       | 3.95%   |
| Penryn           | 10       | 3.95%   |
| CometLake        | 10       | 3.95%   |
| Piledriver       | 9        | 3.56%   |
| K10              | 9        | 3.56%   |
| Zen              | 7        | 2.77%   |
| Westmere         | 6        | 2.37%   |
| Broadwell        | 5        | 1.98%   |
| Unknown          | 5        | 1.98%   |
| Silvermont       | 4        | 1.58%   |
| K8 Hammer        | 4        | 1.58%   |
| Steamroller      | 2        | 0.79%   |
| NetBurst         | 2        | 0.79%   |
| Nehalem          | 2        | 0.79%   |
| IceLake          | 2        | 0.79%   |
| Excavator        | 2        | 0.79%   |
| Core             | 2        | 0.79%   |
| Alderlake Hybrid | 2        | 0.79%   |
| K10 Llano        | 1        | 0.4%    |
| Bulldozer        | 1        | 0.4%    |
| Bonnell          | 1        | 0.4%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 104      | 37.28%  |
| Intel             | 95       | 34.05%  |
| AMD               | 78       | 27.96%  |
| VIA Technologies  | 1        | 0.36%   |
| ASPEED Technology | 1        | 0.36%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 17       | 5.88%   |
| Intel HD Graphics 530                                                       | 15       | 5.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 14       | 4.84%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 11       | 3.81%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 9        | 3.11%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 8        | 2.77%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 7        | 2.42%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 7        | 2.42%   |
| Nvidia GT218 [GeForce 210]                                                  | 6        | 2.08%   |
| Nvidia GK208B [GeForce GT 710]                                              | 6        | 2.08%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 6        | 2.08%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5        | 1.73%   |
| Intel HD Graphics 630                                                       | 5        | 1.73%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 5        | 1.73%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 5        | 1.73%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 1.38%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 4        | 1.38%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 4        | 1.38%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 4        | 1.38%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4        | 1.38%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 3        | 1.04%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 3        | 1.04%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 1.04%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 3        | 1.04%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 3        | 1.04%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 2        | 0.69%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 0.69%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 2        | 0.69%   |
| Nvidia GP107GL [Quadro P620]                                                | 2        | 0.69%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 2        | 0.69%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 0.69%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 0.69%   |
| Nvidia GK107GL [Quadro K2000]                                               | 2        | 0.69%   |
| Nvidia GF119 [GeForce GT 625 OEM]                                           | 2        | 0.69%   |
| Nvidia GF108 [GeForce GT 730]                                               | 2        | 0.69%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 2        | 0.69%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 2        | 0.69%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller              | 2        | 0.69%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 0.69%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2        | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 90       | 33.96%  |
| 1 x Intel            | 79       | 29.81%  |
| 1 x AMD              | 71       | 26.79%  |
| Intel + Nvidia       | 7        | 2.64%   |
| AMD + Nvidia         | 5        | 1.89%   |
| 2 x AMD              | 3        | 1.13%   |
| Intel + AMD          | 2        | 0.75%   |
| 3 x Nvidia           | 1        | 0.38%   |
| 2 x Nvidia           | 1        | 0.38%   |
| 2 x AMD + 2 x Nvidia | 1        | 0.38%   |
| 2 x AMD + 1 x Nvidia | 1        | 0.38%   |
| 1 x VIA              | 1        | 0.38%   |
| Intel + 2 x Nvidia   | 1        | 0.38%   |
| 1 x ASPEED           | 1        | 0.38%   |
| AMD + 2 x Nvidia     | 1        | 0.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 196      | 74.81%  |
| Proprietary | 55       | 20.99%  |
| Unknown     | 11       | 4.2%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 131      | 49.25%  |
| 1.01-2.0   | 34       | 12.78%  |
| 7.01-8.0   | 26       | 9.77%   |
| 3.01-4.0   | 23       | 8.65%   |
| 0.51-1.0   | 22       | 8.27%   |
| 0.01-0.5   | 17       | 6.39%   |
| 5.01-6.0   | 8        | 3.01%   |
| 2.01-3.0   | 2        | 0.75%   |
| 4.01-5.0   | 1        | 0.38%   |
| 16.01-24.0 | 1        | 0.38%   |
| 8.01-16.0  | 1        | 0.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 50       | 19.16%  |
| Acer                 | 46       | 17.62%  |
| Goldstar             | 35       | 13.41%  |
| Dell                 | 21       | 8.05%   |
| Hewlett-Packard      | 17       | 6.51%   |
| AOC                  | 16       | 6.13%   |
| Lenovo               | 8        | 3.07%   |
| BenQ                 | 8        | 3.07%   |
| ViewSonic            | 6        | 2.3%    |
| LG Electronics       | 6        | 2.3%    |
| Unknown (XXX)        | 4        | 1.53%   |
| MSI                  | 4        | 1.53%   |
| MStar                | 3        | 1.15%   |
| Ancor Communications | 3        | 1.15%   |
| Sharp                | 2        | 0.77%   |
| SGT                  | 2        | 0.77%   |
| Philips              | 2        | 0.77%   |
| Microstep            | 2        | 0.77%   |
| IOD                  | 2        | 0.77%   |
| Fujitsu              | 2        | 0.77%   |
| Apple                | 2        | 0.77%   |
| ___                  | 1        | 0.38%   |
| Unknown              | 1        | 0.38%   |
| Toshiba              | 1        | 0.38%   |
| Sony                 | 1        | 0.38%   |
| SKY                  | 1        | 0.38%   |
| RTK                  | 1        | 0.38%   |
| MIG                  | 1        | 0.38%   |
| JRY                  | 1        | 0.38%   |
| ITE                  | 1        | 0.38%   |
| Intehill             | 1        | 0.38%   |
| HUYINIUDA            | 1        | 0.38%   |
| HPN                  | 1        | 0.38%   |
| HJW                  | 1        | 0.38%   |
| Gateway              | 1        | 0.38%   |
| Fujitsu Siemens      | 1        | 0.38%   |
| Envision Peripherals | 1        | 0.38%   |
| CMT                  | 1        | 0.38%   |
| CHI                  | 1        | 0.38%   |
| ASUSTek Computer     | 1        | 0.38%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Acer VG220Q ACR06D8 1920x1080 476x268mm 21.5-inch                     | 4        | 1.43%   |
| Acer k222HQL ACR0512 1920x1080 477x268mm 21.5-inch                    | 4        | 1.43%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 3        | 1.07%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 3        | 1.07%   |
| Samsung Electronics LCD Monitor SAM0678 1360x768                      | 3        | 1.07%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                      | 3        | 1.07%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 3        | 1.07%   |
| Dell P2422H DELA1C4 1920x1080 527x296mm 23.8-inch                     | 3        | 1.07%   |
| Dell E2011H DEL406B 1600x900 443x249mm 20.0-inch                      | 3        | 1.07%   |
| AOC Q27G2WG4 AOC2702 2560x1440 597x336mm 27.0-inch                    | 3        | 1.07%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 3        | 1.07%   |
| AOC 2381 AOC2381 1920x1080 509x286mm 23.0-inch                        | 3        | 1.07%   |
| ViewSonic VG2448 VSC3B35 1920x1080 527x296mm 23.8-inch                | 2        | 0.71%   |
| Samsung Electronics SyncMaster SAM037B 1680x1050 474x296mm 22.0-inch  | 2        | 0.71%   |
| Samsung Electronics SME1920 SAM06B7 1366x768 410x230mm 18.5-inch      | 2        | 0.71%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch     | 2        | 0.71%   |
| Samsung Electronics S23B370 SAM089B 1920x1080 510x287mm 23.0-inch     | 2        | 0.71%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 2        | 0.71%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 2        | 0.71%   |
| Samsung Electronics LS24AG32x SAM71DA 1920x1080 527x296mm 23.8-inch   | 2        | 0.71%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 950x540mm 43.0-inch | 2        | 0.71%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 2        | 0.71%   |
| Philips 236V4 PHLC0B3 1920x1080 510x287mm 23.0-inch                   | 2        | 0.71%   |
| LG Electronics LCD Monitor LG IPS FULLHD 1920x1080                    | 2        | 0.71%   |
| Hewlett-Packard Z24n HWP320E 1920x1200 518x324mm 24.1-inch            | 2        | 0.71%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2        | 0.71%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 2        | 0.71%   |
| Goldstar FULL HD GSM5AB9 1920x1080 480x270mm 21.7-inch                | 2        | 0.71%   |
| Goldstar E1940 GSM4BD7 1360x768 406x229mm 18.4-inch                   | 2        | 0.71%   |
| Dell S2340L DELD058 1920x1080 509x286mm 23.0-inch                     | 2        | 0.71%   |
| Acer X193HQ ACR0067 1366x768 410x230mm 18.5-inch                      | 2        | 0.71%   |
| Acer S200HQL  ACR0359 1600x900 430x240mm 19.4-inch                    | 2        | 0.71%   |
| Acer P193W ACR000C 1440x900 410x256mm 19.0-inch                       | 2        | 0.71%   |
| Acer K242HQL ACR042E 1920x1080 509x286mm 23.0-inch                    | 2        | 0.71%   |
| Acer K242HL ACR03E3 1920x1080 531x299mm 24.0-inch                     | 2        | 0.71%   |
| ___ LCD TV ___9000 1360x768                                           | 1        | 0.36%   |
| ViewSonic VG1655 VSCD239 1920x1080 344x194mm 15.5-inch                | 1        | 0.36%   |
| ViewSonic VA1703wSERIES VSC121F 1440x900 367x230mm 17.1-inch          | 1        | 0.36%   |
| ViewSonic LCD Monitor VX3276-QHD 5120x1440                            | 1        | 0.36%   |
| ViewSonic IFP7550 VSC36CD 3840x2160 1660x930mm 74.9-inch              | 1        | 0.36%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 123      | 48.62%  |
| 1600x900 (HD+)     | 22       | 8.7%    |
| 3840x2160 (4K)     | 19       | 7.51%   |
| 1366x768 (WXGA)    | 18       | 7.11%   |
| 2560x1440 (QHD)    | 14       | 5.53%   |
| 1440x900 (WXGA+)   | 10       | 3.95%   |
| 1680x1050 (WSXGA+) | 8        | 3.16%   |
| 1360x768           | 8        | 3.16%   |
| Unknown            | 6        | 2.37%   |
| 2560x1080          | 5        | 1.98%   |
| 1280x1024 (SXGA)   | 5        | 1.98%   |
| 3840x1080          | 2        | 0.79%   |
| 3440x1440          | 2        | 0.79%   |
| 1920x1200 (WUXGA)  | 2        | 0.79%   |
| 1600x1200          | 2        | 0.79%   |
| 5120x1440          | 1        | 0.4%    |
| 3840x2400          | 1        | 0.4%    |
| 3520x1080          | 1        | 0.4%    |
| 2732x768           | 1        | 0.4%    |
| 2560x1600          | 1        | 0.4%    |
| 1280x960           | 1        | 0.4%    |
| 1280x720 (HD)      | 1        | 0.4%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 44       | 16.79%  |
| 24      | 32       | 12.21%  |
| 21      | 30       | 11.45%  |
| 27      | 25       | 9.54%   |
| Unknown | 25       | 9.54%   |
| 18      | 20       | 7.63%   |
| 20      | 19       | 7.25%   |
| 19      | 16       | 6.11%   |
| 34      | 7        | 2.67%   |
| 22      | 6        | 2.29%   |
| 54      | 4        | 1.53%   |
| 31      | 4        | 1.53%   |
| 17      | 4        | 1.53%   |
| 15      | 4        | 1.53%   |
| 84      | 3        | 1.15%   |
| 72      | 3        | 1.15%   |
| 52      | 3        | 1.15%   |
| 32      | 2        | 0.76%   |
| 26      | 2        | 0.76%   |
| 16      | 2        | 0.76%   |
| 74      | 1        | 0.38%   |
| 60      | 1        | 0.38%   |
| 46      | 1        | 0.38%   |
| 40      | 1        | 0.38%   |
| 39      | 1        | 0.38%   |
| 29      | 1        | 0.38%   |
| 13      | 1        | 0.38%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 92       | 36.95%  |
| 401-500     | 88       | 35.34%  |
| Unknown     | 25       | 10.04%  |
| 701-800     | 9        | 3.61%   |
| 1001-1500   | 9        | 3.61%   |
| 301-350     | 8        | 3.21%   |
| 1501-2000   | 6        | 2.41%   |
| 601-700     | 5        | 2.01%   |
| 351-400     | 4        | 1.61%   |
| 801-900     | 2        | 0.8%    |
| 201-300     | 1        | 0.4%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 177      | 74.06%  |
| 16/10   | 27       | 11.3%   |
| Unknown | 20       | 8.37%   |
| 21/9    | 7        | 2.93%   |
| 5/4     | 6        | 2.51%   |
| 4/3     | 1        | 0.42%   |
| 2.00    | 1        | 0.42%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 96       | 37.5%   |
| 151-200        | 41       | 16.02%  |
| 301-350        | 26       | 10.16%  |
| Unknown        | 25       | 9.77%   |
| 141-150        | 20       | 7.81%   |
| More than 1000 | 14       | 5.47%   |
| 351-500        | 14       | 5.47%   |
| 251-300        | 8        | 3.13%   |
| 101-110        | 4        | 1.56%   |
| 501-1000       | 3        | 1.17%   |
| 131-140        | 2        | 0.78%   |
| 71-80          | 1        | 0.39%   |
| 121-130        | 1        | 0.39%   |
| 111-120        | 1        | 0.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 148      | 62.18%  |
| 101-120       | 44       | 18.49%  |
| Unknown       | 25       | 10.5%   |
| 1-50          | 10       | 4.2%    |
| 121-160       | 6        | 2.52%   |
| 161-240       | 4        | 1.68%   |
| More than 240 | 1        | 0.42%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 207      | 78.11%  |
| 2     | 33       | 12.45%  |
| 0     | 18       | 6.79%   |
| 3     | 7        | 2.64%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 173      | 44.94%  |
| Intel                           | 99       | 25.71%  |
| Qualcomm Atheros                | 27       | 7.01%   |
| Ralink Technology               | 13       | 3.38%   |
| TP-Link                         | 10       | 2.6%    |
| D-Link                          | 10       | 2.6%    |
| Broadcom                        | 10       | 2.6%    |
| Nvidia                          | 6        | 1.56%   |
| MediaTek                        | 4        | 1.04%   |
| Edimax Technology               | 4        | 1.04%   |
| D-Link System                   | 4        | 1.04%   |
| Broadcom Limited                | 4        | 1.04%   |
| Ralink                          | 3        | 0.78%   |
| Mercucys                        | 3        | 0.78%   |
| Xiaomi                          | 2        | 0.52%   |
| Samsung Electronics             | 2        | 0.52%   |
| ASUSTek Computer                | 2        | 0.52%   |
| VIA Technologies                | 1        | 0.26%   |
| Qualcomm Atheros Communications | 1        | 0.26%   |
| OPPO Electronics                | 1        | 0.26%   |
| OnePlus Technology (Shenzhen)   | 1        | 0.26%   |
| Huawei Technologies             | 1        | 0.26%   |
| BUFFALO                         | 1        | 0.26%   |
| AVM                             | 1        | 0.26%   |
| Aquantia                        | 1        | 0.26%   |
| Adafruit                        | 1        | 0.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 143      | 33.1%   |
| Intel Wi-Fi 6 AX200                                                    | 11       | 2.55%   |
| Intel I211 Gigabit Network Connection                                  | 10       | 2.31%   |
| Intel Ethernet Connection I217-LM                                      | 10       | 2.31%   |
| Realtek RTL8125 2.5GbE Controller                                      | 8        | 1.85%   |
| Intel Ethernet Connection (2) I219-V                                   | 8        | 1.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8        | 1.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 7        | 1.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 7        | 1.62%   |
| Intel Ethernet Connection I217-V                                       | 6        | 1.39%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 5        | 1.16%   |
| Realtek 802.11ac NIC                                                   | 5        | 1.16%   |
| Ralink MT7601U Wireless Adapter                                        | 5        | 1.16%   |
| Intel Ethernet Connection (5) I219-LM                                  | 5        | 1.16%   |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]          | 5        | 1.16%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 4        | 0.93%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                        | 4        | 0.93%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 4        | 0.93%   |
| Nvidia MCP61 Ethernet                                                  | 4        | 0.93%   |
| Intel Wireless 7260                                                    | 4        | 0.93%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 4        | 0.93%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 4        | 0.93%   |
| Intel Ethernet Controller I225-V                                       | 4        | 0.93%   |
| Intel Ethernet Connection (7) I219-V                                   | 4        | 0.93%   |
| Intel Ethernet Connection (2) I219-LM                                  | 4        | 0.93%   |
| Intel Ethernet Connection (2) I218-V                                   | 4        | 0.93%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 3        | 0.69%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 3        | 0.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 3        | 0.69%   |
| Intel Wireless 7265                                                    | 3        | 0.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 3        | 0.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 3        | 0.69%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 3        | 0.69%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 2        | 0.46%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2        | 0.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2        | 0.46%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 2        | 0.46%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 2        | 0.46%   |
| Ralink RT2501/RT2573 Wireless Adapter                                  | 2        | 0.46%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                      | 2        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 38       | 23.9%   |
| Intel                           | 37       | 23.27%  |
| Qualcomm Atheros                | 22       | 13.84%  |
| Ralink Technology               | 13       | 8.18%   |
| TP-Link                         | 10       | 6.29%   |
| D-Link                          | 10       | 6.29%   |
| Broadcom                        | 5        | 3.14%   |
| MediaTek                        | 4        | 2.52%   |
| Edimax Technology               | 4        | 2.52%   |
| Ralink                          | 3        | 1.89%   |
| Mercucys                        | 3        | 1.89%   |
| Broadcom Limited                | 3        | 1.89%   |
| D-Link System                   | 2        | 1.26%   |
| ASUSTek Computer                | 2        | 1.26%   |
| Qualcomm Atheros Communications | 1        | 0.63%   |
| BUFFALO                         | 1        | 0.63%   |
| AVM                             | 1        | 0.63%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 11       | 6.83%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 7        | 4.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 7        | 4.35%   |
| Realtek 802.11ac NIC                                                 | 5        | 3.11%   |
| Ralink MT7601U Wireless Adapter                                      | 5        | 3.11%   |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]        | 5        | 3.11%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 4        | 2.48%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                      | 4        | 2.48%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 4        | 2.48%   |
| Intel Wireless 7260                                                  | 4        | 2.48%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 4        | 2.48%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 4        | 2.48%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 3        | 1.86%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 3        | 1.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 3        | 1.86%   |
| Intel Wireless 7265                                                  | 3        | 1.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 3        | 1.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 3        | 1.86%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 3        | 1.86%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 2        | 1.24%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 2        | 1.24%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 2        | 1.24%   |
| Ralink RT2501/RT2573 Wireless Adapter                                | 2        | 1.24%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                    | 2        | 1.24%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                 | 2        | 1.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2        | 1.24%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 2        | 1.24%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 2        | 1.24%   |
| Mercucys 802.11n NIC                                                 | 2        | 1.24%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 2        | 1.24%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]       | 2        | 1.24%   |
| D-Link 802.11 n WLAN                                                 | 2        | 1.24%   |
| Broadcom BCM43142 802.11b/g/n                                        | 2        | 1.24%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 1        | 0.62%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                | 1        | 0.62%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                           | 1        | 0.62%   |
| TP-Link Archer T4U ver.3                                             | 1        | 0.62%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                               | 1        | 0.62%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                  | 1        | 0.62%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 1        | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 158      | 60.31%  |
| Intel                         | 76       | 29.01%  |
| Qualcomm Atheros              | 6        | 2.29%   |
| Nvidia                        | 6        | 2.29%   |
| Broadcom                      | 5        | 1.91%   |
| Xiaomi                        | 2        | 0.76%   |
| Samsung Electronics           | 2        | 0.76%   |
| D-Link System                 | 2        | 0.76%   |
| VIA Technologies              | 1        | 0.38%   |
| OPPO Electronics              | 1        | 0.38%   |
| OnePlus Technology (Shenzhen) | 1        | 0.38%   |
| Broadcom Limited              | 1        | 0.38%   |
| Aquantia                      | 1        | 0.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 143      | 53.16%  |
| Intel I211 Gigabit Network Connection                                  | 10       | 3.72%   |
| Intel Ethernet Connection I217-LM                                      | 10       | 3.72%   |
| Realtek RTL8125 2.5GbE Controller                                      | 8        | 2.97%   |
| Intel Ethernet Connection (2) I219-V                                   | 8        | 2.97%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8        | 2.97%   |
| Intel Ethernet Connection I217-V                                       | 6        | 2.23%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 5        | 1.86%   |
| Intel Ethernet Connection (5) I219-LM                                  | 5        | 1.86%   |
| Nvidia MCP61 Ethernet                                                  | 4        | 1.49%   |
| Intel Ethernet Controller I225-V                                       | 4        | 1.49%   |
| Intel Ethernet Connection (7) I219-V                                   | 4        | 1.49%   |
| Intel Ethernet Connection (2) I219-LM                                  | 4        | 1.49%   |
| Intel Ethernet Connection (2) I218-V                                   | 4        | 1.49%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2        | 0.74%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 2        | 0.74%   |
| Nvidia MCP73 Ethernet                                                  | 2        | 0.74%   |
| Intel Ethernet Connection (12) I219-V                                  | 2        | 0.74%   |
| Intel Ethernet Connection (11) I219-V                                  | 2        | 0.74%   |
| Intel Ethernet Connection (11) I219-LM                                 | 2        | 0.74%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                        | 2        | 0.74%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1        | 0.37%   |
| Xiaomi 100Mbps Network Card Adapter                                    | 1        | 0.37%   |
| VIA VT6120/VT6121/VT6122/VT6130 Gigabit Ethernet Adapter               | 1        | 0.37%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1        | 0.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1        | 0.37%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1        | 0.37%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 0.37%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1        | 0.37%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1        | 0.37%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1        | 0.37%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 1        | 0.37%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1        | 0.37%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1        | 0.37%   |
| OPPO OnePlus Nord 4                                                    | 1        | 0.37%   |
| OnePlus (Shenzhen) OnePlus                                             | 1        | 0.37%   |
| Intel I350 Gigabit Network Connection                                  | 1        | 0.37%   |
| Intel I210 Gigabit Unprogrammed                                        | 1        | 0.37%   |
| Intel Ethernet Connection I218-V                                       | 1        | 0.37%   |
| Intel 82579V Gigabit Network Connection                                | 1        | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 244      | 63.38%  |
| WiFi     | 139      | 36.1%   |
| Modem    | 2        | 0.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 161      | 61.69%  |
| WiFi     | 100      | 38.31%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 155      | 60.78%  |
| 2     | 84       | 32.94%  |
| 3     | 7        | 2.75%   |
| 0     | 6        | 2.35%   |
| 4     | 2        | 0.78%   |
| 5     | 1        | 0.39%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 173      | 66.03%  |
| Yes  | 89       | 33.97%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 35       | 31.82%  |
| Intel                           | 34       | 30.91%  |
| Realtek Semiconductor           | 8        | 7.27%   |
| Qualcomm Atheros Communications | 6        | 5.45%   |
| Apple                           | 5        | 4.55%   |
| TP-Link                         | 4        | 3.64%   |
| ASUSTek Computer                | 4        | 3.64%   |
| MediaTek                        | 3        | 2.73%   |
| Lite-On Technology              | 2        | 1.82%   |
| IMC Networks                    | 2        | 1.82%   |
| Actions                         | 2        | 1.82%   |
| Unknown                         | 2        | 1.82%   |
| Toshiba                         | 1        | 0.91%   |
| Foxconn International           | 1        | 0.91%   |
| Broadcom                        | 1        | 0.91%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 35       | 31.82%  |
| Intel AX200 Bluetooth                               | 11       | 10%     |
| Intel Bluetooth wireless interface                  | 9        | 8.18%   |
| Realtek Bluetooth Radio                             | 7        | 6.36%   |
| TP-Link TP-Link Bluetooth USB Adapter               | 4        | 3.64%   |
| Qualcomm Atheros  Bluetooth Device                  | 4        | 3.64%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4        | 3.64%   |
| MediaTek Wireless_Device                            | 3        | 2.73%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3        | 2.73%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3        | 2.73%   |
| Intel AX210 Bluetooth                               | 3        | 2.73%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2        | 1.82%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2        | 1.82%   |
| IMC Networks Bluetooth Device                       | 2        | 1.82%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2        | 1.82%   |
| Apple Bluetooth USB Host Controller                 | 2        | 1.82%   |
| Actions general adapter                             | 2        | 1.82%   |
| Unknown                                             | 2        | 1.82%   |
| Toshiba Atheros AR3012 Bluetooth                    | 1        | 0.91%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 0.91%   |
| Intel AX201 Bluetooth                               | 1        | 0.91%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1        | 0.91%   |
| Broadcom HP Portable Valentine                      | 1        | 0.91%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1        | 0.91%   |
| ASUS Bluetooth Device                               | 1        | 0.91%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1        | 0.91%   |
| Apple Bluetooth Host Controller                     | 1        | 0.91%   |
| Apple Bluetooth HCI                                 | 1        | 0.91%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 170      | 39.72%  |
| AMD                                  | 104      | 24.3%   |
| Nvidia                               | 97       | 22.66%  |
| C-Media Electronics                  | 13       | 3.04%   |
| JMTek                                | 6        | 1.4%    |
| Generalplus Technology               | 5        | 1.17%   |
| Razer USA                            | 4        | 0.93%   |
| Elan Microelectronics                | 3        | 0.7%    |
| Creative Labs                        | 3        | 0.7%    |
| SAVITECH                             | 2        | 0.47%   |
| Logitech                             | 2        | 0.47%   |
| VIA Technologies                     | 1        | 0.23%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.23%   |
| Texas Instruments                    | 1        | 0.23%   |
| Syntek                               | 1        | 0.23%   |
| Nordic Semiconductor ASA             | 1        | 0.23%   |
| Kingston Technology                  | 1        | 0.23%   |
| Hewlett-Packard                      | 1        | 0.23%   |
| Focusrite-Novation                   | 1        | 0.23%   |
| ESS Technology                       | 1        | 0.23%   |
| Ensoniq                              | 1        | 0.23%   |
| Earth Computer Technologies          | 1        | 0.23%   |
| Creative Technology                  | 1        | 0.23%   |
| Corsair                              | 1        | 0.23%   |
| Blue Microphones                     | 1        | 0.23%   |
| Barco Display Systems                | 1        | 0.23%   |
| Audio-Technica                       | 1        | 0.23%   |
| Audient                              | 1        | 0.23%   |
| ASUSTek Computer                     | 1        | 0.23%   |
| Apple                                | 1        | 0.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 29       | 5.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 23       | 4.48%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 20       | 3.9%    |
| Intel 200 Series PCH HD Audio                                              | 19       | 3.7%    |
| AMD Starship/Matisse HD Audio Controller                                   | 18       | 3.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 17       | 3.31%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 17       | 3.31%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 16       | 3.12%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 15       | 2.92%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 14       | 2.73%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 13       | 2.53%   |
| Nvidia GP107GL High Definition Audio Controller                            | 12       | 2.34%   |
| Intel Cannon Lake PCH cAVS                                                 | 10       | 1.95%   |
| Nvidia High Definition Audio Controller                                    | 9        | 1.75%   |
| Nvidia GP106 High Definition Audio Controller                              | 9        | 1.75%   |
| Nvidia GP104 High Definition Audio Controller                              | 9        | 1.75%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 9        | 1.75%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 9        | 1.75%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 9        | 1.75%   |
| AMD Navi 10 HDMI Audio                                                     | 9        | 1.75%   |
| AMD FCH Azalia Controller                                                  | 8        | 1.56%   |
| Nvidia TU116 High Definition Audio Controller                              | 7        | 1.36%   |
| Nvidia GP108 High Definition Audio Controller                              | 7        | 1.36%   |
| Nvidia GF119 HDMI Audio Controller                                         | 6        | 1.17%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 6        | 1.17%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 6        | 1.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6        | 1.17%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 6        | 1.17%   |
| Nvidia GF108 High Definition Audio Controller                              | 5        | 0.97%   |
| Intel Comet Lake PCH cAVS                                                  | 5        | 0.97%   |
| Generalplus Technology USB Audio Device                                    | 5        | 0.97%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5        | 0.97%   |
| Nvidia MCP61 High Definition Audio                                         | 4        | 0.78%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4        | 0.78%   |
| JMTek USB PnP Audio Device                                                 | 4        | 0.78%   |
| C-Media Electronics USB Audio Device                                       | 4        | 0.78%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4        | 0.78%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 4        | 0.78%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 4        | 0.78%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 52       | 39.1%   |
| SK hynix            | 19       | 14.29%  |
| Unknown             | 14       | 10.53%  |
| Samsung Electronics | 14       | 10.53%  |
| Corsair             | 14       | 10.53%  |
| Team                | 4        | 3.01%   |
| Ramaxel Technology  | 2        | 1.5%    |
| Micron Technology   | 2        | 1.5%    |
| G.Skill             | 2        | 1.5%    |
| Apacer              | 2        | 1.5%    |
| A-DATA Technology   | 2        | 1.5%    |
| Unknown             | 2        | 1.5%    |
| Unknown (0x02BA)    | 1        | 0.75%   |
| Transcend           | 1        | 0.75%   |
| KingFast            | 1        | 0.75%   |
| Hikvision           | 1        | 0.75%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s    | 5        | 3.33%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s     | 4        | 2.67%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 3        | 2%      |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s    | 3        | 2%      |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s       | 3        | 2%      |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s   | 3        | 2%      |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s               | 2        | 1.33%   |
| SK hynix RAM HMT112U6TFR8C-H9 1GB DIMM DDR3 1333MT/s    | 2        | 1.33%   |
| SK hynix RAM HMA851U6AFR6N-UH 4GB DIMM DDR4 2400MT/s    | 2        | 1.33%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s  | 2        | 1.33%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s     | 2        | 1.33%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s     | 2        | 1.33%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s     | 2        | 1.33%   |
| Samsung RAM M378B5173DB0-CK0 4096MB DIMM DDR3 1600MT/s  | 2        | 1.33%   |
| Kingston RAM KP223C-ELD 2048MB DIMM DDR3 1600MT/s       | 2        | 1.33%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s     | 2        | 1.33%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s       | 2        | 1.33%   |
| Kingston RAM KF3600C17D4/8GX 8GB DIMM DDR4 3600MT/s     | 2        | 1.33%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s     | 2        | 1.33%   |
| Kingston RAM 99U5471-001.A01LF 2GB DIMM DDR3 1600MT/s   | 2        | 1.33%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1800MT/s     | 2        | 1.33%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s  | 2        | 1.33%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s   | 2        | 1.33%   |
| Unknown                                                 | 2        | 1.33%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s               | 1        | 0.67%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s               | 1        | 0.67%   |
| Unknown RAM Module 8192MB DIMM DDR4 2400MT/s            | 1        | 0.67%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s               | 1        | 0.67%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                 | 1        | 0.67%   |
| Unknown RAM Module 2GB DIMM DDR2 533MT/s                | 1        | 0.67%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                | 1        | 0.67%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                | 1        | 0.67%   |
| Unknown RAM Module 2048MB DIMM SDRAM                    | 1        | 0.67%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                | 1        | 0.67%   |
| Unknown RAM Module 1GB DIMM DDR2 333MT/s                | 1        | 0.67%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s             | 1        | 0.67%   |
| Unknown (0x02BA) RAM Module 2048MB FB-DIMM DDR2 800MT/s | 1        | 0.67%   |
| Transcend RAM TS256MLQ64V8U 2GB DIMM DDR 533MT/s        | 1        | 0.67%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s      | 1        | 0.67%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s      | 1        | 0.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 55       | 47.41%  |
| DDR3    | 40       | 34.48%  |
| SDRAM   | 6        | 5.17%   |
| DDR2    | 4        | 3.45%   |
| Unknown | 4        | 3.45%   |
| LPDDR4  | 2        | 1.72%   |
| DDR5    | 2        | 1.72%   |
| DDR     | 2        | 1.72%   |
| DRAM    | 1        | 0.86%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 99       | 89.19%  |
| SODIMM       | 9        | 8.11%   |
| Row Of Chips | 1        | 0.9%    |
| RIMM         | 1        | 0.9%    |
| FB-DIMM      | 1        | 0.9%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 50       | 40.32%  |
| 4096  | 36       | 29.03%  |
| 2048  | 14       | 11.29%  |
| 16384 | 13       | 10.48%  |
| 1024  | 6        | 4.84%   |
| 32768 | 5        | 4.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 22       | 16.54%  |
| 1333    | 20       | 15.04%  |
| 2400    | 12       | 9.02%   |
| 3200    | 11       | 8.27%   |
| 2133    | 9        | 6.77%   |
| 3733    | 6        | 4.51%   |
| 3600    | 6        | 4.51%   |
| 1867    | 6        | 4.51%   |
| 2667    | 5        | 3.76%   |
| 3400    | 4        | 3.01%   |
| 3466    | 3        | 2.26%   |
| 3000    | 3        | 2.26%   |
| 2666    | 3        | 2.26%   |
| 1866    | 3        | 2.26%   |
| 1800    | 3        | 2.26%   |
| 3534    | 2        | 1.5%    |
| 3151    | 2        | 1.5%    |
| 667     | 2        | 1.5%    |
| 533     | 2        | 1.5%    |
| 6800    | 1        | 0.75%   |
| 5808    | 1        | 0.75%   |
| 3800    | 1        | 0.75%   |
| 3333    | 1        | 0.75%   |
| 2800    | 1        | 0.75%   |
| 2000    | 1        | 0.75%   |
| 800     | 1        | 0.75%   |
| 333     | 1        | 0.75%   |
| Unknown | 1        | 0.75%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Brother Industries | 5        | 45.45%  |
| Seiko Epson        | 2        | 18.18%  |
| STMicroelectronics | 1        | 9.09%   |
| Pantum             | 1        | 9.09%   |
| Hewlett-Packard    | 1        | 9.09%   |
| Canon              | 1        | 9.09%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| STMicroelectronics USB Printer Port | 1        | 9.09%   |
| Seiko Epson LQ-310                  | 1        | 9.09%   |
| Seiko Epson L360 Series             | 1        | 9.09%   |
| Pantum P2500W series                | 1        | 9.09%   |
| HP HP LaserJet Pro M404-M405        | 1        | 9.09%   |
| Canon E4200 series                  | 1        | 9.09%   |
| Brother HL-1110 series              | 1        | 9.09%   |
| Brother DCP-T510W                   | 1        | 9.09%   |
| Brother DCP-T300                    | 1        | 9.09%   |
| Brother DCP-L3551CDW                | 1        | 9.09%   |
| Brother DCP-1510                    | 1        | 9.09%   |

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
| Logitech                      | 12       | 27.91%  |
| Microsoft                     | 5        | 11.63%  |
| Microdia                      | 5        | 11.63%  |
| Sunplus Innovation Technology | 3        | 6.98%   |
| Generalplus Technology        | 3        | 6.98%   |
| Aveo Technology               | 3        | 6.98%   |
| MacroSilicon                  | 2        | 4.65%   |
| Apple                         | 2        | 4.65%   |
| Z-Star Microelectronics       | 1        | 2.33%   |
| WCM_USB                       | 1        | 2.33%   |
| vivo                          | 1        | 2.33%   |
| Suyin                         | 1        | 2.33%   |
| Silicon Motion                | 1        | 2.33%   |
| Realtek Semiconductor         | 1        | 2.33%   |
| Owon                          | 1        | 2.33%   |
| Huawei Technologies           | 1        | 2.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Microsoft MicrosoftÂ LifeCam Cinema | 4        | 9.09%   |
| Microdia Camera                      | 3        | 6.82%   |
| Logitech Webcam C270                 | 3        | 6.82%   |
| Generalplus GENERAL WEBCAM           | 3        | 6.82%   |
| MacroSilicon USB Video               | 2        | 4.55%   |
| Logitech Webcam C310                 | 2        | 4.55%   |
| Logitech C922 Pro Stream Webcam      | 2        | 4.55%   |
| Aveo USB2.0 Camera                   | 2        | 4.55%   |
| Z-Star Venus USB2.0 Camera           | 1        | 2.27%   |
| WCM_USB WEB CAM                      | 1        | 2.27%   |
| vivo 1906                            | 1        | 2.27%   |
| Suyin HP Integrated Webcam           | 1        | 2.27%   |
| Sunplus SPCA2281 Web Camera          | 1        | 2.27%   |
| Sunplus HK 5M WebCAM                 | 1        | 2.27%   |
| Sunplus FULL HD webcam               | 1        | 2.27%   |
| Silicon Motion 300k Pixel Camera     | 1        | 2.27%   |
| Realtek USB Boot                     | 1        | 2.27%   |
| Owon USB CAMERA                      | 1        | 2.27%   |
| Microsoft LifeCam VX-2000            | 1        | 2.27%   |
| Microdia Sonix USB 2.0 Camera        | 1        | 2.27%   |
| Microdia Integrated Camera           | 1        | 2.27%   |
| Logitech Webcam C600                 | 1        | 2.27%   |
| Logitech Mic (Notebooks Pro)         | 1        | 2.27%   |
| Logitech HD Webcam C525              | 1        | 2.27%   |
| Logitech HD Webcam C510              | 1        | 2.27%   |
| Logitech HD Pro Webcam C920          | 1        | 2.27%   |
| Huawei HiCamera                      | 1        | 2.27%   |
| Generalplus WEB CAM                  | 1        | 2.27%   |
| Aveo UVC camera (Bresser microscope) | 1        | 2.27%   |
| Apple iSight in LED Cinema Display   | 1        | 2.27%   |
| Apple iPad 2 (3G; 64GB)              | 1        | 2.27%   |

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


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Alcor Micro | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 213      | 83.53%  |
| 1     | 38       | 14.9%   |
| 2     | 2        | 0.78%   |
| 7     | 1        | 0.39%   |
| 5     | 1        | 0.39%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 15       | 30%     |
| Graphics card            | 12       | 24%     |
| Unassigned class         | 7        | 14%     |
| Sound                    | 6        | 12%     |
| Communication controller | 4        | 8%      |
| Net/ethernet             | 2        | 4%      |
| Storage/raid             | 1        | 2%      |
| Network                  | 1        | 2%      |
| Chipcard                 | 1        | 2%      |
| Camera                   | 1        | 2%      |

