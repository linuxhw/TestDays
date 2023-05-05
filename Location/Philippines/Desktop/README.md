Linux in Philippines - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Philippines.

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

Total: 285

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ECS           | G41T-R3                     | [fcbdd2737a](https://linux-hardware.org/?probe=fcbdd2737a) | Apr 26, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | [96f6b41a5c](https://linux-hardware.org/?probe=96f6b41a5c) | Apr 19, 2023 |
| ECS           | G41T-R3                     | [2c589a38f7](https://linux-hardware.org/?probe=2c589a38f7) | Apr 13, 2023 |
| HP            | 3397                        | [5a25984320](https://linux-hardware.org/?probe=5a25984320) | Mar 31, 2023 |
| ASRock        | H61M-HVS                    | [0672578da7](https://linux-hardware.org/?probe=0672578da7) | Mar 30, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [4eb8132fd2](https://linux-hardware.org/?probe=4eb8132fd2) | Mar 24, 2023 |
| EMAXX TECH... | EMX-B450M-GAMING            | [f147ee8484](https://linux-hardware.org/?probe=f147ee8484) | Mar 21, 2023 |
| ASRock        | B450M Steel Legend          | [ae258d05b1](https://linux-hardware.org/?probe=ae258d05b1) | Mar 16, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [26ecc0b7a2](https://linux-hardware.org/?probe=26ecc0b7a2) | Mar 10, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [ca7d449be6](https://linux-hardware.org/?probe=ca7d449be6) | Feb 28, 2023 |
| MSI           | A320M PRO-VH                | [e1266ebf79](https://linux-hardware.org/?probe=e1266ebf79) | Feb 27, 2023 |
| ASUSTek       | A68HM-K                     | [d6f5b00609](https://linux-hardware.org/?probe=d6f5b00609) | Feb 26, 2023 |
| ASUSTek       | A68HM-K                     | [89cd5d5c44](https://linux-hardware.org/?probe=89cd5d5c44) | Feb 26, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO II     | [99b1ae3224](https://linux-hardware.org/?probe=99b1ae3224) | Feb 25, 2023 |
| MSI           | K9N6PGM2-V2                 | [e88df81d6f](https://linux-hardware.org/?probe=e88df81d6f) | Feb 24, 2023 |
| Biostar       | A320MH                      | [b6f7ef6e4a](https://linux-hardware.org/?probe=b6f7ef6e4a) | Feb 23, 2023 |
| Biostar       | A320MH                      | [e80f86a0bf](https://linux-hardware.org/?probe=e80f86a0bf) | Feb 23, 2023 |
| Dell          | 0W2F8G A00                  | [aa7bf98168](https://linux-hardware.org/?probe=aa7bf98168) | Feb 16, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [eb8434e607](https://linux-hardware.org/?probe=eb8434e607) | Feb 15, 2023 |
| ASUSTek       | BM6630_BM6330_BP6230        | [abe1e578c0](https://linux-hardware.org/?probe=abe1e578c0) | Feb 12, 2023 |
| Dell          | 0W2F8G A00                  | [b0694cfc5c](https://linux-hardware.org/?probe=b0694cfc5c) | Feb 06, 2023 |
| Gigabyte      | H97M-D3H                    | [3ccdc4fa2b](https://linux-hardware.org/?probe=3ccdc4fa2b) | Jan 31, 2023 |
| MSI           | MAG B560M MORTAR WIFI       | [33f6781ba8](https://linux-hardware.org/?probe=33f6781ba8) | Jan 08, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [cfeb9545a3](https://linux-hardware.org/?probe=cfeb9545a3) | Dec 21, 2022 |
| Biostar       | A520MH                      | [b6c4fdd80b](https://linux-hardware.org/?probe=b6c4fdd80b) | Dec 11, 2022 |
| ASUSTek       | BM5242                      | [d37b75dc52](https://linux-hardware.org/?probe=d37b75dc52) | Dec 10, 2022 |
| ASUSTek       | BM5242                      | [7c17c8d773](https://linux-hardware.org/?probe=7c17c8d773) | Dec 10, 2022 |
| Intel         | D946GZAB AAD66610-302       | [5433ee5bc1](https://linux-hardware.org/?probe=5433ee5bc1) | Nov 22, 2022 |
| ASRock        | B450M Steel Legend          | [4792cdbba2](https://linux-hardware.org/?probe=4792cdbba2) | Nov 21, 2022 |
| MSI           | B450M BAZOOKA PLUS          | [f63b2757ea](https://linux-hardware.org/?probe=f63b2757ea) | Nov 12, 2022 |
| ASUSTek       | A68HM-K                     | [70daf967f2](https://linux-hardware.org/?probe=70daf967f2) | Nov 10, 2022 |
| Gigabyte      | B550 VISION D-P             | [c08b835f58](https://linux-hardware.org/?probe=c08b835f58) | Nov 07, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [7db5fcb7b0](https://linux-hardware.org/?probe=7db5fcb7b0) | Nov 05, 2022 |
| Gigabyte      | B450 AORUS M                | [e4dfd41fa4](https://linux-hardware.org/?probe=e4dfd41fa4) | Nov 02, 2022 |
| HP            | 3048h                       | [6ce1d2bf43](https://linux-hardware.org/?probe=6ce1d2bf43) | Oct 30, 2022 |
| ASRock        | H61M-VS                     | [9a48b2a679](https://linux-hardware.org/?probe=9a48b2a679) | Oct 28, 2022 |
| MSI           | MAG A520M VECTOR WIFI       | [91a8a52c4a](https://linux-hardware.org/?probe=91a8a52c4a) | Oct 25, 2022 |
| Gigabyte      | Z97N-WIFI                   | [dd5c78f136](https://linux-hardware.org/?probe=dd5c78f136) | Oct 24, 2022 |
| Gigabyte      | Z97N-WIFI                   | [10d8d16b6c](https://linux-hardware.org/?probe=10d8d16b6c) | Oct 24, 2022 |
| Gigabyte      | B550M DS3H                  | [d267c64062](https://linux-hardware.org/?probe=d267c64062) | Oct 19, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [fc0a9a6b24](https://linux-hardware.org/?probe=fc0a9a6b24) | Oct 18, 2022 |
| MSI           | H110M PRO-D                 | [d0580b46f2](https://linux-hardware.org/?probe=d0580b46f2) | Oct 18, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [9f52e46640](https://linux-hardware.org/?probe=9f52e46640) | Oct 11, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [aa7d067a6f](https://linux-hardware.org/?probe=aa7d067a6f) | Oct 11, 2022 |
| Gigabyte      | F2A68HM-S1                  | [379f85dfb3](https://linux-hardware.org/?probe=379f85dfb3) | Oct 09, 2022 |
| Gigabyte      | F2A68HM-S1                  | [f02be8db4c](https://linux-hardware.org/?probe=f02be8db4c) | Oct 09, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [700c5cc2bc](https://linux-hardware.org/?probe=700c5cc2bc) | Oct 05, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [37dbdb48dd](https://linux-hardware.org/?probe=37dbdb48dd) | Sep 20, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [4d460404c8](https://linux-hardware.org/?probe=4d460404c8) | Sep 16, 2022 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | [34c1beb103](https://linux-hardware.org/?probe=34c1beb103) | Sep 13, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [7ce5d8e865](https://linux-hardware.org/?probe=7ce5d8e865) | Sep 12, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [ec5f57ab65](https://linux-hardware.org/?probe=ec5f57ab65) | Sep 12, 2022 |
| Biostar       | A780L3B                     | [bc83f32ddf](https://linux-hardware.org/?probe=bc83f32ddf) | Sep 12, 2022 |
| Biostar       | A780L3B                     | [61057dc040](https://linux-hardware.org/?probe=61057dc040) | Sep 12, 2022 |
| Biostar       | A780L3B                     | [6463bcc136](https://linux-hardware.org/?probe=6463bcc136) | Sep 10, 2022 |
| Biostar       | A780L3B                     | [f65db263d7](https://linux-hardware.org/?probe=f65db263d7) | Sep 10, 2022 |
| Gigabyte      | GA-990FXA-UD5               | [b77aa249c8](https://linux-hardware.org/?probe=b77aa249c8) | Sep 09, 2022 |
| Gigabyte      | GA-990FXA-UD5               | [dc69b9dde6](https://linux-hardware.org/?probe=dc69b9dde6) | Sep 09, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | [051ea3b002](https://linux-hardware.org/?probe=051ea3b002) | Sep 08, 2022 |
| HP            | 83F3                        | [71d62174e2](https://linux-hardware.org/?probe=71d62174e2) | Aug 27, 2022 |
| HP            | 1850                        | [85b5eedc40](https://linux-hardware.org/?probe=85b5eedc40) | Aug 26, 2022 |
| ASUSTek       | PRIME B450M-A               | [bfdd1ab294](https://linux-hardware.org/?probe=bfdd1ab294) | Aug 23, 2022 |
| Gigabyte      | H77N-WIFI                   | [7a37d5e6a5](https://linux-hardware.org/?probe=7a37d5e6a5) | Aug 07, 2022 |
| Gigabyte      | H77N-WIFI                   | [db237c843c](https://linux-hardware.org/?probe=db237c843c) | Aug 06, 2022 |
| Gigabyte      | H77N-WIFI                   | [5251e7868a](https://linux-hardware.org/?probe=5251e7868a) | Aug 06, 2022 |
| Gigabyte      | H81M-D2V                    | [64da165357](https://linux-hardware.org/?probe=64da165357) | Aug 01, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [a0e19ce405](https://linux-hardware.org/?probe=a0e19ce405) | Jul 26, 2022 |
| Gigabyte      | H410M H V3                  | [37521f84c8](https://linux-hardware.org/?probe=37521f84c8) | Jul 20, 2022 |
| ASUSTek       | M4A88T-M                    | [57ed9f00c7](https://linux-hardware.org/?probe=57ed9f00c7) | Jul 18, 2022 |
| ASUSTek       | M4A88T-M                    | [f99189e2d0](https://linux-hardware.org/?probe=f99189e2d0) | Jul 18, 2022 |
| YANYU         | EPIC-C19                    | [5bda78db57](https://linux-hardware.org/?probe=5bda78db57) | Jul 11, 2022 |
| Gigabyte      | A520M DS3H                  | [b56fe3beb3](https://linux-hardware.org/?probe=b56fe3beb3) | Jun 28, 2022 |
| MSI           | A320M PRO-VH                | [47f765c61f](https://linux-hardware.org/?probe=47f765c61f) | Jun 14, 2022 |
| MSI           | H81M-E33                    | [49191a1c98](https://linux-hardware.org/?probe=49191a1c98) | Jun 08, 2022 |
| Gigabyte      | F2A68HM-S1                  | [017e41e32c](https://linux-hardware.org/?probe=017e41e32c) | Jun 07, 2022 |
| MSI           | H81M-E33                    | [6a2d6cbe74](https://linux-hardware.org/?probe=6a2d6cbe74) | Jun 04, 2022 |
| ASUSTek       | H81M-K                      | [512fb81a9b](https://linux-hardware.org/?probe=512fb81a9b) | May 31, 2022 |
| MSI           | Z97 XPOWER AC               | [dd5c7a981a](https://linux-hardware.org/?probe=dd5c7a981a) | May 29, 2022 |
| MSI           | MS-7717                     | [101b488b80](https://linux-hardware.org/?probe=101b488b80) | May 28, 2022 |
| MSI           | MS-7717                     | [9b0c2d0d8c](https://linux-hardware.org/?probe=9b0c2d0d8c) | May 28, 2022 |
| ECS           | A68M-C4DL                   | [b8c60cf7a0](https://linux-hardware.org/?probe=b8c60cf7a0) | May 09, 2022 |
| HP            | 212A                        | [acd660910f](https://linux-hardware.org/?probe=acd660910f) | May 09, 2022 |
| MSI           | B450M MORTAR                | [74323309f1](https://linux-hardware.org/?probe=74323309f1) | Apr 20, 2022 |
| MSI           | H510M-A PRO                 | [03b7f74d31](https://linux-hardware.org/?probe=03b7f74d31) | Mar 29, 2022 |
| MSI           | H510M-A PRO                 | [42e921877b](https://linux-hardware.org/?probe=42e921877b) | Mar 29, 2022 |
| HP            | 2B38                        | [99fd9bb200](https://linux-hardware.org/?probe=99fd9bb200) | Mar 27, 2022 |
| MSI           | MS-7619                     | [65c73f26b0](https://linux-hardware.org/?probe=65c73f26b0) | Mar 22, 2022 |
| MSI           | H510M PRO-E                 | [111cf21b7f](https://linux-hardware.org/?probe=111cf21b7f) | Mar 21, 2022 |
| ASUSTek       | ROG STRIX Z490-I GAMING     | [95373e24b7](https://linux-hardware.org/?probe=95373e24b7) | Mar 16, 2022 |
| MSI           | B560M PRO-VDH WIFI          | [c15007b668](https://linux-hardware.org/?probe=c15007b668) | Mar 15, 2022 |
| MSI           | H510M PRO-E                 | [ad5840ceb1](https://linux-hardware.org/?probe=ad5840ceb1) | Mar 14, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [bd9b6ec157](https://linux-hardware.org/?probe=bd9b6ec157) | Mar 11, 2022 |
| Gigabyte      | Z590 AORUS ULTRA            | [a1b757e234](https://linux-hardware.org/?probe=a1b757e234) | Mar 05, 2022 |
| ASUSTek       | H81M-D                      | [4f6714e804](https://linux-hardware.org/?probe=4f6714e804) | Mar 01, 2022 |
| Dell          | 00V62H A01                  | [70f59ecacf](https://linux-hardware.org/?probe=70f59ecacf) | Feb 28, 2022 |
| ASUSTek       | H81M-D                      | [2bc13ee0e2](https://linux-hardware.org/?probe=2bc13ee0e2) | Feb 28, 2022 |
| ASUSTek       | H81M-D                      | [a8334fb3c3](https://linux-hardware.org/?probe=a8334fb3c3) | Feb 28, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [f269ebd3a2](https://linux-hardware.org/?probe=f269ebd3a2) | Feb 28, 2022 |
| ASUSTek       | A88XM-PLUS                  | [3a6147e5db](https://linux-hardware.org/?probe=3a6147e5db) | Feb 16, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [a25fea3795](https://linux-hardware.org/?probe=a25fea3795) | Feb 12, 2022 |
| Gigabyte      | Z590 AORUS ULTRA            | [da8ce5d5b5](https://linux-hardware.org/?probe=da8ce5d5b5) | Feb 05, 2022 |
| Gigabyte      | Z590 AORUS ULTRA            | [56bbe3562f](https://linux-hardware.org/?probe=56bbe3562f) | Jan 15, 2022 |
| Gigabyte      | Z590 AORUS ULTRA            | [266128f234](https://linux-hardware.org/?probe=266128f234) | Jan 06, 2022 |
| Gigabyte      | Z590 AORUS ULTRA            | [900b250e00](https://linux-hardware.org/?probe=900b250e00) | Jan 05, 2022 |
| Gigabyte      | G41M-Combo                  | [e0b5bc37a4](https://linux-hardware.org/?probe=e0b5bc37a4) | Dec 18, 2021 |
| EMAXX TECH... | EMX-A55GT-iCafe V1.0        | [d6d799c3d8](https://linux-hardware.org/?probe=d6d799c3d8) | Nov 28, 2021 |
| ASUSTek       | P8B75-M                     | [31e306a09d](https://linux-hardware.org/?probe=31e306a09d) | Nov 26, 2021 |
| Gigabyte      | B450M DS3H V2               | [2302fee654](https://linux-hardware.org/?probe=2302fee654) | Nov 09, 2021 |
| MSI           | Z97 GAMING 3                | [249f25308e](https://linux-hardware.org/?probe=249f25308e) | Nov 08, 2021 |
| MSI           | B350M PRO-VDH               | [7e77378fb3](https://linux-hardware.org/?probe=7e77378fb3) | Nov 07, 2021 |
| ECS           | G41T-R3                     | [892069341e](https://linux-hardware.org/?probe=892069341e) | Oct 31, 2021 |
| ASUSTek       | F2A85-M LE                  | [0ac8e061f1](https://linux-hardware.org/?probe=0ac8e061f1) | Oct 31, 2021 |
| ASUSTek       | F2A85-M LE                  | [655000678d](https://linux-hardware.org/?probe=655000678d) | Oct 30, 2021 |
| EMAXX TECH... | EMX-MCP61D3-iCafe V2.0      | [cb279cfeaf](https://linux-hardware.org/?probe=cb279cfeaf) | Oct 09, 2021 |
| EMAXX TECH... | EMX-MCP61D3-iCafe V2.0      | [2444a742a8](https://linux-hardware.org/?probe=2444a742a8) | Oct 09, 2021 |
| ASUSTek       | GD30CI                      | [9782c6bff5](https://linux-hardware.org/?probe=9782c6bff5) | Sep 25, 2021 |
| ASUSTek       | EX-H310M-V3 R2.0            | [a9a92c303c](https://linux-hardware.org/?probe=a9a92c303c) | Sep 24, 2021 |
| JOOYON        | IPM41-D3G                   | [54cc0ff25b](https://linux-hardware.org/?probe=54cc0ff25b) | Sep 17, 2021 |
| JOOYON        | IPM41-D3G                   | [4f8d90f8ef](https://linux-hardware.org/?probe=4f8d90f8ef) | Sep 12, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS            | [f6388fb1b0](https://linux-hardware.org/?probe=f6388fb1b0) | Sep 07, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS            | [a19fc44e26](https://linux-hardware.org/?probe=a19fc44e26) | Sep 07, 2021 |
| Gigabyte      | F2A58M-DS2                  | [8ea19cfa9d](https://linux-hardware.org/?probe=8ea19cfa9d) | Aug 25, 2021 |
| Unknown       | Ionics Carrier Board Adv... | [62a47a18c2](https://linux-hardware.org/?probe=62a47a18c2) | Aug 12, 2021 |
| ECS           | H81H3-M4                    | [a595ba80d3](https://linux-hardware.org/?probe=a595ba80d3) | Aug 08, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [90e7e1e008](https://linux-hardware.org/?probe=90e7e1e008) | Aug 05, 2021 |
| ASRock        | N68C-GS4 FX                 | [4bf2729f88](https://linux-hardware.org/?probe=4bf2729f88) | Aug 04, 2021 |
| Gigabyte      | F2A68HM-S1                  | [57f0c24236](https://linux-hardware.org/?probe=57f0c24236) | Aug 03, 2021 |
| Gigabyte      | MZGLKCP-00                  | [4d9f134679](https://linux-hardware.org/?probe=4d9f134679) | Jul 30, 2021 |
| Biostar       | H110MHV3                    | [28344398db](https://linux-hardware.org/?probe=28344398db) | Jul 27, 2021 |
| ASRock        | B450M Steel Legend          | [8165fc4d95](https://linux-hardware.org/?probe=8165fc4d95) | Jul 06, 2021 |
| Biostar       | A320MH                      | [16e2552ccc](https://linux-hardware.org/?probe=16e2552ccc) | Jun 20, 2021 |
| Dell          | 040DDP A01                  | [8a9bdad1fd](https://linux-hardware.org/?probe=8a9bdad1fd) | Jun 10, 2021 |
| ASRock        | B450M Steel Legend          | [cc3c9e3798](https://linux-hardware.org/?probe=cc3c9e3798) | Jun 08, 2021 |
| MSI           | A68HM-E33 V2                | [10ccc894a1](https://linux-hardware.org/?probe=10ccc894a1) | Jun 07, 2021 |
| Gigabyte      | H61M-DS2                    | [e31519274b](https://linux-hardware.org/?probe=e31519274b) | May 22, 2021 |
| Gigabyte      | H61M-DS2                    | [523ced455c](https://linux-hardware.org/?probe=523ced455c) | May 22, 2021 |
| Acer          | Aspire X1900                | [c4e0203ed9](https://linux-hardware.org/?probe=c4e0203ed9) | May 19, 2021 |
| MSI           | A68HM-E33 V2                | [a14cf2a48e](https://linux-hardware.org/?probe=a14cf2a48e) | May 18, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | [ac4ce770fc](https://linux-hardware.org/?probe=ac4ce770fc) | May 10, 2021 |
| ASRock        | B450M Steel Legend          | [8467906058](https://linux-hardware.org/?probe=8467906058) | May 04, 2021 |
| ASRock        | B450M Steel Legend          | [55bfc7d608](https://linux-hardware.org/?probe=55bfc7d608) | May 03, 2021 |
| ASUSTek       | EX-B365M-V5                 | [c169d54571](https://linux-hardware.org/?probe=c169d54571) | Apr 25, 2021 |
| ASRock        | B450M Steel Legend          | [b866ec6925](https://linux-hardware.org/?probe=b866ec6925) | Apr 20, 2021 |
| Gigabyte      | H61M-DS2                    | [f66e7cbdfd](https://linux-hardware.org/?probe=f66e7cbdfd) | Apr 11, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | [4c93424ea5](https://linux-hardware.org/?probe=4c93424ea5) | Mar 26, 2021 |
| MSI           | Z270 GAMING M7              | [b72439b299](https://linux-hardware.org/?probe=b72439b299) | Mar 17, 2021 |
| Gigabyte      | GA-MA78GM-US2H              | [0f6037a19e](https://linux-hardware.org/?probe=0f6037a19e) | Mar 14, 2021 |
| MSI           | Z97 XPOWER AC               | [c627833398](https://linux-hardware.org/?probe=c627833398) | Feb 23, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [3582928f83](https://linux-hardware.org/?probe=3582928f83) | Feb 20, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [d392637e95](https://linux-hardware.org/?probe=d392637e95) | Feb 20, 2021 |
| AMD           | A88                         | [11ecb6d298](https://linux-hardware.org/?probe=11ecb6d298) | Feb 14, 2021 |
| Dell          | 0JP3NX A00                  | [3e5d4f837a](https://linux-hardware.org/?probe=3e5d4f837a) | Feb 10, 2021 |
| JOOYON        | IPM41-D3G                   | [6feab903f8](https://linux-hardware.org/?probe=6feab903f8) | Feb 05, 2021 |
| JOOYON        | IPM41-D3G                   | [5fa1dabba9](https://linux-hardware.org/?probe=5fa1dabba9) | Feb 05, 2021 |
| Dell          | 0JP3NX A00                  | [1f5d53a4a2](https://linux-hardware.org/?probe=1f5d53a4a2) | Feb 03, 2021 |
| QTQD          | Unknown                     | [2912607416](https://linux-hardware.org/?probe=2912607416) | Jan 27, 2021 |
| Gigabyte      | H97M-D3H                    | [76f0201d14](https://linux-hardware.org/?probe=76f0201d14) | Jan 26, 2021 |
| MSI           | B450 TOMAHAWK               | [795b4f4c7b](https://linux-hardware.org/?probe=795b4f4c7b) | Jan 26, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [6e4545c96a](https://linux-hardware.org/?probe=6e4545c96a) | Jan 23, 2021 |
| ASRock        | G41M-VS3                    | [603bb5d8e4](https://linux-hardware.org/?probe=603bb5d8e4) | Jan 22, 2021 |
| ASUSTek       | H81M-C                      | [c108942b4e](https://linux-hardware.org/?probe=c108942b4e) | Jan 19, 2021 |
| Acer          | Aspire X1900                | [d0a0250e62](https://linux-hardware.org/?probe=d0a0250e62) | Jan 15, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [15b8546bd4](https://linux-hardware.org/?probe=15b8546bd4) | Jan 11, 2021 |
| Gigabyte      | AM1M-S2P                    | [433295603d](https://linux-hardware.org/?probe=433295603d) | Jan 09, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [3f75d5f2e1](https://linux-hardware.org/?probe=3f75d5f2e1) | Jan 07, 2021 |
| Gigabyte      | Z370M D3H-CF                | [e6533b7b24](https://linux-hardware.org/?probe=e6533b7b24) | Jan 07, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [91ccfb9b5a](https://linux-hardware.org/?probe=91ccfb9b5a) | Jan 06, 2021 |
| MSI           | A320M PRO-VD/S V2           | [5d05e8d607](https://linux-hardware.org/?probe=5d05e8d607) | Jan 04, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | [031ad52398](https://linux-hardware.org/?probe=031ad52398) | Jan 01, 2021 |
| ASUSTek       | EX-H310M-V3 R2.0            | [11a5fd5bae](https://linux-hardware.org/?probe=11a5fd5bae) | Dec 30, 2020 |
| MSI           | IONA                        | [bfb84589dd](https://linux-hardware.org/?probe=bfb84589dd) | Dec 28, 2020 |
| MSI           | IONA                        | [0ec5c79eb8](https://linux-hardware.org/?probe=0ec5c79eb8) | Dec 26, 2020 |
| ECS           | H110M-C3D/C3V               | [aa44a6674f](https://linux-hardware.org/?probe=aa44a6674f) | Dec 23, 2020 |
| ASRock        | N68-S3                      | [bfa6bd97d5](https://linux-hardware.org/?probe=bfa6bd97d5) | Dec 23, 2020 |
| MSI           | MS-7541                     | [a6e134920c](https://linux-hardware.org/?probe=a6e134920c) | Dec 22, 2020 |
| MSI           | MS-7541                     | [a44769cfd2](https://linux-hardware.org/?probe=a44769cfd2) | Dec 22, 2020 |
| ASRock        | A320M-DVS R4.0              | [d186067403](https://linux-hardware.org/?probe=d186067403) | Dec 17, 2020 |
| ASRock        | N68-S3                      | [1d3067d8cb](https://linux-hardware.org/?probe=1d3067d8cb) | Dec 17, 2020 |
| HP            | 8061                        | [0f0bc8b49a](https://linux-hardware.org/?probe=0f0bc8b49a) | Dec 04, 2020 |
| HP            | 8061                        | [a63c8237f1](https://linux-hardware.org/?probe=a63c8237f1) | Dec 04, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [2a35d394f9](https://linux-hardware.org/?probe=2a35d394f9) | Dec 04, 2020 |
| NEC Comput... | IS8XM                       | [57afeee773](https://linux-hardware.org/?probe=57afeee773) | Nov 30, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | [354202e98e](https://linux-hardware.org/?probe=354202e98e) | Nov 19, 2020 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [f86e0d2af5](https://linux-hardware.org/?probe=f86e0d2af5) | Nov 11, 2020 |
| HP            | 3031h                       | [fb54f48959](https://linux-hardware.org/?probe=fb54f48959) | Nov 10, 2020 |
| HP            | 8061                        | [7936b223e9](https://linux-hardware.org/?probe=7936b223e9) | Nov 10, 2020 |
| ASUSTek       | B85M-G                      | [2c9a8f0838](https://linux-hardware.org/?probe=2c9a8f0838) | Nov 08, 2020 |
| Gigabyte      | Z97N-WIFI                   | [c812c2b6f9](https://linux-hardware.org/?probe=c812c2b6f9) | Nov 07, 2020 |
| Gigabyte      | Z97N-WIFI                   | [e21be2124d](https://linux-hardware.org/?probe=e21be2124d) | Nov 04, 2020 |
| HP            | 8061                        | [d11b92ef18](https://linux-hardware.org/?probe=d11b92ef18) | Nov 01, 2020 |
| Gigabyte      | H81M-DS2                    | [a3cdedf351](https://linux-hardware.org/?probe=a3cdedf351) | Oct 30, 2020 |
| Gigabyte      | F2A78M-HD2                  | [3919d06624](https://linux-hardware.org/?probe=3919d06624) | Oct 25, 2020 |
| Pegatron      | IPMSB-H61                   | [c569d86fff](https://linux-hardware.org/?probe=c569d86fff) | Oct 19, 2020 |
| HP            | 8061                        | [b2cf684801](https://linux-hardware.org/?probe=b2cf684801) | Oct 13, 2020 |
| MSI           | MAG B550M MORTAR            | [653a4a9f6e](https://linux-hardware.org/?probe=653a4a9f6e) | Oct 11, 2020 |
| ASUSTek       | PRIME B350-PLUS             | [11b8e32835](https://linux-hardware.org/?probe=11b8e32835) | Oct 06, 2020 |
| MSI           | A88XM-E35                   | [32556e96bf](https://linux-hardware.org/?probe=32556e96bf) | Sep 27, 2020 |
| MSI           | A88XM-E35                   | [7176092b12](https://linux-hardware.org/?probe=7176092b12) | Sep 27, 2020 |
| HP            | 8061                        | [1d3e0a6b3d](https://linux-hardware.org/?probe=1d3e0a6b3d) | Sep 25, 2020 |
| ASUSTek       | PRIME B250M-K               | [546b3fec83](https://linux-hardware.org/?probe=546b3fec83) | Sep 16, 2020 |
| ASRock        | A320M-DVS R4.0              | [eaff730455](https://linux-hardware.org/?probe=eaff730455) | Sep 09, 2020 |
| ASUSTek       | PRIME B350-PLUS             | [9557e9d02c](https://linux-hardware.org/?probe=9557e9d02c) | Sep 04, 2020 |
| ASRock        | A320M-DVS R4.0              | [288f4f772c](https://linux-hardware.org/?probe=288f4f772c) | Sep 01, 2020 |
| Biostar       | H81MHV3                     | [ecd87de5e0](https://linux-hardware.org/?probe=ecd87de5e0) | Aug 21, 2020 |
| Dell          | 0VRWRC A00                  | [b5e17b6229](https://linux-hardware.org/?probe=b5e17b6229) | Aug 16, 2020 |
| ASUSTek       | PRIME B250M-K               | [6b5b2287e0](https://linux-hardware.org/?probe=6b5b2287e0) | Aug 07, 2020 |
| HP            | 805D                        | [b0f200fe77](https://linux-hardware.org/?probe=b0f200fe77) | Jul 29, 2020 |
| MSI           | Z170A GAMING M3             | [22963b821f](https://linux-hardware.org/?probe=22963b821f) | Jun 20, 2020 |
| MSI           | Z170A GAMING M3             | [c5779593cc](https://linux-hardware.org/?probe=c5779593cc) | Jun 20, 2020 |
| Biostar       | Hi-Fi A68U3P                | [ec653ae1fc](https://linux-hardware.org/?probe=ec653ae1fc) | Jun 11, 2020 |
| Gigabyte      | X299 UD4 Pro-CF             | [5cde7141d6](https://linux-hardware.org/?probe=5cde7141d6) | Jun 02, 2020 |
| Gigabyte      | F2A78M-HD2                  | [6bdc484d30](https://linux-hardware.org/?probe=6bdc484d30) | May 25, 2020 |
| Dell          | 0D28YY A03                  | [7ae56aa829](https://linux-hardware.org/?probe=7ae56aa829) | May 11, 2020 |
| ASUSTek       | P5KPL-AM EPU                | [d4cbef0ab2](https://linux-hardware.org/?probe=d4cbef0ab2) | May 02, 2020 |
| Dell          | 0D28YY A03                  | [285c59f702](https://linux-hardware.org/?probe=285c59f702) | Apr 29, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | [36bb48017f](https://linux-hardware.org/?probe=36bb48017f) | Apr 29, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | [1f91672dce](https://linux-hardware.org/?probe=1f91672dce) | Apr 28, 2020 |
| ASRock        | 960GC-GS FX                 | [6b07754d1d](https://linux-hardware.org/?probe=6b07754d1d) | Apr 27, 2020 |
| MSI           | K9N6PGM2-V2                 | [e487e06d2c](https://linux-hardware.org/?probe=e487e06d2c) | Apr 26, 2020 |
| ASRock        | 960GC-GS FX                 | [390a1cbbb3](https://linux-hardware.org/?probe=390a1cbbb3) | Apr 25, 2020 |
| Biostar       | H81MHV3                     | [252b646f8b](https://linux-hardware.org/?probe=252b646f8b) | Apr 25, 2020 |
| Biostar       | H81MHV3                     | [0fe6d54c09](https://linux-hardware.org/?probe=0fe6d54c09) | Apr 25, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | [eec2e1e90f](https://linux-hardware.org/?probe=eec2e1e90f) | Apr 24, 2020 |
| Dell          | 0D28YY A03                  | [cb0a381ca1](https://linux-hardware.org/?probe=cb0a381ca1) | Apr 22, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | [dbe36dfd4f](https://linux-hardware.org/?probe=dbe36dfd4f) | Apr 21, 2020 |
| Gigabyte      | F2A68HM-S1                  | [06c5a92500](https://linux-hardware.org/?probe=06c5a92500) | Apr 18, 2020 |
| Gigabyte      | F2A68HM-S1                  | [b87b3feefd](https://linux-hardware.org/?probe=b87b3feefd) | Apr 18, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | [d092c3db85](https://linux-hardware.org/?probe=d092c3db85) | Apr 16, 2020 |
| MSI           | K9N6PGM2-V2                 | [8eca04a69b](https://linux-hardware.org/?probe=8eca04a69b) | Apr 14, 2020 |
| MSI           | K9N6PGM2-V2                 | [576c3b1853](https://linux-hardware.org/?probe=576c3b1853) | Apr 13, 2020 |
| TriGem Com... | DreamSys                    | [e5a22f4123](https://linux-hardware.org/?probe=e5a22f4123) | Apr 09, 2020 |
| Gigabyte      | H61M-DS2                    | [c00e4e1a0e](https://linux-hardware.org/?probe=c00e4e1a0e) | Apr 07, 2020 |
| Gigabyte      | H61M-DS2                    | [087a36a4bd](https://linux-hardware.org/?probe=087a36a4bd) | Apr 04, 2020 |
| Biostar       | Hi-Fi A68U3P                | [35b973ebbb](https://linux-hardware.org/?probe=35b973ebbb) | Apr 03, 2020 |
| Gigabyte      | H61M-DS2                    | [9355c0ff9e](https://linux-hardware.org/?probe=9355c0ff9e) | Apr 01, 2020 |
| HP            | 0A5Ch                       | [5f4bf573ad](https://linux-hardware.org/?probe=5f4bf573ad) | Mar 28, 2020 |
| HP            | 0A5Ch                       | [7411b1a819](https://linux-hardware.org/?probe=7411b1a819) | Mar 28, 2020 |
| Gigabyte      | H61M-DS2                    | [8c6dbdb971](https://linux-hardware.org/?probe=8c6dbdb971) | Mar 25, 2020 |
| Gigabyte      | H61M-DS2                    | [70b408e2f0](https://linux-hardware.org/?probe=70b408e2f0) | Mar 25, 2020 |
| Gigabyte      | H61M-DS2                    | [be10de1b16](https://linux-hardware.org/?probe=be10de1b16) | Mar 24, 2020 |
| Gigabyte      | Z77X-UD5H                   | [92e778ba2a](https://linux-hardware.org/?probe=92e778ba2a) | Mar 21, 2020 |
| Gigabyte      | H61M-DS2                    | [f7cbec79e8](https://linux-hardware.org/?probe=f7cbec79e8) | Mar 15, 2020 |
| Gigabyte      | H310M DS2                   | [529f84f7d1](https://linux-hardware.org/?probe=529f84f7d1) | Mar 12, 2020 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [636f6029b4](https://linux-hardware.org/?probe=636f6029b4) | Mar 11, 2020 |
| Gigabyte      | H61M-DS2                    | [861919e59d](https://linux-hardware.org/?probe=861919e59d) | Mar 08, 2020 |
| MSI           | MS-7309                     | [dff3f373f6](https://linux-hardware.org/?probe=dff3f373f6) | Mar 08, 2020 |
| Gigabyte      | H61M-DS2                    | [2b1b62332c](https://linux-hardware.org/?probe=2b1b62332c) | Mar 08, 2020 |
| MSI           | MS-7309                     | [e52b770dff](https://linux-hardware.org/?probe=e52b770dff) | Mar 08, 2020 |
| MSI           | MS-7309                     | [a06909608c](https://linux-hardware.org/?probe=a06909608c) | Mar 08, 2020 |
| MSI           | MS-7309                     | [b3e1633a13](https://linux-hardware.org/?probe=b3e1633a13) | Mar 08, 2020 |
| ASUSTek       | PRIME B250M-A               | [a1d3a510e8](https://linux-hardware.org/?probe=a1d3a510e8) | Mar 04, 2020 |
| ASUSTek       | PRIME B250M-A               | [6e803cdc23](https://linux-hardware.org/?probe=6e803cdc23) | Mar 02, 2020 |
| ASUSTek       | PRIME B250M-A               | [fb41a1d23f](https://linux-hardware.org/?probe=fb41a1d23f) | Mar 02, 2020 |
| Foxconn       | G31MX Series                | [e3c94b5684](https://linux-hardware.org/?probe=e3c94b5684) | Feb 22, 2020 |
| Foxconn       | G31MX Series                | [c549e93013](https://linux-hardware.org/?probe=c549e93013) | Feb 21, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | [75b9cc12a9](https://linux-hardware.org/?probe=75b9cc12a9) | Feb 20, 2020 |
| ASUSTek       | P8H61-M LE                  | [78d658fc64](https://linux-hardware.org/?probe=78d658fc64) | Feb 09, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | [4f64209449](https://linux-hardware.org/?probe=4f64209449) | Feb 07, 2020 |
| Foxconn       | G31MX Series                | [cb21aa111e](https://linux-hardware.org/?probe=cb21aa111e) | Jan 31, 2020 |
| Foxconn       | 2A8C                        | [973270aee7](https://linux-hardware.org/?probe=973270aee7) | Jan 26, 2020 |
| Foxconn       | G31MX Series                | [459627eda2](https://linux-hardware.org/?probe=459627eda2) | Jan 26, 2020 |
| Foxconn       | G31MX Series                | [61dfac2df2](https://linux-hardware.org/?probe=61dfac2df2) | Jan 26, 2020 |
| Foxconn       | G31MX Series                | [880daf6c76](https://linux-hardware.org/?probe=880daf6c76) | Jan 26, 2020 |
| Foxconn       | 2A8C                        | [0d020faa5c](https://linux-hardware.org/?probe=0d020faa5c) | Jan 24, 2020 |
| Foxconn       | 2A8C                        | [e3389e7b39](https://linux-hardware.org/?probe=e3389e7b39) | Jan 23, 2020 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [d5df64e644](https://linux-hardware.org/?probe=d5df64e644) | Dec 29, 2019 |
| ASUSTek       | PRIME B250M-A               | [e4fecb44bc](https://linux-hardware.org/?probe=e4fecb44bc) | Dec 05, 2019 |
| Pegatron      | IPMSB-H61                   | [857c9bddda](https://linux-hardware.org/?probe=857c9bddda) | Nov 07, 2019 |
| Pegatron      | IPMSB-H61                   | [55e7a33a87](https://linux-hardware.org/?probe=55e7a33a87) | Nov 07, 2019 |
| Gigabyte      | GA-78LMT-S2 R2 sex          | [e5d5c98452](https://linux-hardware.org/?probe=e5d5c98452) | Sep 11, 2019 |
| ASRock        | A780GM-LE                   | [80fb7e01aa](https://linux-hardware.org/?probe=80fb7e01aa) | Aug 22, 2019 |
| Gigabyte      | GA-78LMT-S2 R2 sex          | [1f7f86ed9e](https://linux-hardware.org/?probe=1f7f86ed9e) | Jul 13, 2019 |
| Gigabyte      | A320M-S2H-CF                | [704346ee85](https://linux-hardware.org/?probe=704346ee85) | Jun 24, 2019 |
| Gigabyte      | A320M-S2H-CF                | [3fb0bfffca](https://linux-hardware.org/?probe=3fb0bfffca) | Jun 24, 2019 |
| Dell          | 01TKCC A01                  | [c133935d4f](https://linux-hardware.org/?probe=c133935d4f) | Jun 19, 2019 |
| ASRock        | 960GC-GS FX                 | [db39b4023e](https://linux-hardware.org/?probe=db39b4023e) | Jun 03, 2019 |
| ASRock        | 960GC-GS FX                 | [833afc1cd1](https://linux-hardware.org/?probe=833afc1cd1) | May 12, 2019 |
| ASRock        | 960GC-GS FX                 | [04903c40d9](https://linux-hardware.org/?probe=04903c40d9) | May 10, 2019 |
| ASRock        | 960GC-GS FX                 | [1d29713c8b](https://linux-hardware.org/?probe=1d29713c8b) | May 02, 2019 |
| Dell          | 01TKCC A01                  | [3cfa230457](https://linux-hardware.org/?probe=3cfa230457) | Apr 12, 2019 |
| Dell          | 01TKCC A01                  | [94e2e60839](https://linux-hardware.org/?probe=94e2e60839) | Apr 11, 2019 |
| Gigabyte      | A320M-S2H-CF                | [ac265b9b6d](https://linux-hardware.org/?probe=ac265b9b6d) | Mar 27, 2019 |
| Lenovo        | No DPK                      | [02bdd4779e](https://linux-hardware.org/?probe=02bdd4779e) | Oct 21, 2018 |
| Lenovo        | No DPK                      | [d98528c04e](https://linux-hardware.org/?probe=d98528c04e) | Oct 21, 2018 |
| MSI           | A68HM-E33 V2                | [aee859c42b](https://linux-hardware.org/?probe=aee859c42b) | Jan 05, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 20.04       | 14       | 7.45%   |
| Ubuntu 22.04       | 9        | 4.79%   |
| Pop!_OS 20.04      | 9        | 4.79%   |
| Ubuntu 18.04       | 7        | 3.72%   |
| BlackPanther 18.1  | 7        | 3.72%   |
| Zorin 15           | 5        | 2.66%   |
| Manjaro            | 5        | 2.66%   |
| KDE neon 20.04     | 5        | 2.66%   |
| Fedora 36          | 5        | 2.66%   |
| Endless 3.7.7      | 5        | 2.66%   |
| Pop!_OS 21.04      | 4        | 2.13%   |
| Pop!_OS 20.10      | 4        | 2.13%   |
| OpenMandriva 4.3   | 4        | 2.13%   |
| Linux Mint 20.2    | 4        | 2.13%   |
| Endless 3.7.6      | 4        | 2.13%   |
| Zorin 16           | 3        | 1.6%    |
| Ubuntu Unity 18.04 | 3        | 1.6%    |
| Pop!_OS 22.04      | 3        | 1.6%    |
| OpenMandriva 4.2   | 3        | 1.6%    |
| Linux Mint 20.1    | 3        | 1.6%    |
| Fedora 32          | 3        | 1.6%    |
| BlackPanther 16.2  | 3        | 1.6%    |
| Arch Rolling       | 3        | 1.6%    |
| Ubuntu 21.10       | 2        | 1.06%   |
| Linux Mint 21      | 2        | 1.06%   |
| Linux Mint 19.3    | 2        | 1.06%   |
| Kubuntu 22.10      | 2        | 1.06%   |
| Kubuntu 22.04      | 2        | 1.06%   |
| KDE neon 22.04     | 2        | 1.06%   |
| Kali 2021.4        | 2        | 1.06%   |
| Fedora 33          | 2        | 1.06%   |
| Endless 3.9.4      | 2        | 1.06%   |
| Endless 3.3.20     | 2        | 1.06%   |
| Debian 10          | 2        | 1.06%   |
| ArcoLinux Rolling  | 2        | 1.06%   |
| Xubuntu 20.04      | 1        | 0.53%   |
| Xubuntu 19.10      | 1        | 0.53%   |
| Ubuntu MATE 18.04  | 1        | 0.53%   |
| Ubuntu 19.10       | 1        | 0.53%   |
| SteamOS 3.4        | 1        | 0.53%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 32       | 17.98%  |
| Pop!_OS      | 20       | 11.24%  |
| Endless      | 16       | 8.99%   |
| Fedora       | 14       | 7.87%   |
| Linux Mint   | 13       | 7.3%    |
| OpenMandriva | 9        | 5.06%   |
| Manjaro      | 9        | 5.06%   |
| Zorin        | 8        | 4.49%   |
| BlackPanther | 8        | 4.49%   |
| KDE neon     | 7        | 3.93%   |
| Kubuntu      | 5        | 2.81%   |
| Arch         | 4        | 2.25%   |
| Ubuntu Unity | 3        | 1.69%   |
| Kali         | 3        | 1.69%   |
| Debian       | 3        | 1.69%   |
| Xubuntu      | 2        | 1.12%   |
| ROSA         | 2        | 1.12%   |
| Nobara       | 2        | 1.12%   |
| Elementary   | 2        | 1.12%   |
| ArcoLinux    | 2        | 1.12%   |
| Ubuntu MATE  | 1        | 0.56%   |
| SteamOS      | 1        | 0.56%   |
| Solus        | 1        | 0.56%   |
| Reborn OS    | 1        | 0.56%   |
| Peppermint   | 1        | 0.56%   |
| Parrot       | 1        | 0.56%   |
| openSUSE     | 1        | 0.56%   |
| MX           | 1        | 0.56%   |
| LMDE         | 1        | 0.56%   |
| Hash Linux   | 1        | 0.56%   |
| Gentoo       | 1        | 0.56%   |
| Garuda Linux | 1        | 0.56%   |
| BunsenLabs   | 1        | 0.56%   |
| BuildRoot    | 1        | 0.56%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 4.18.16-desktop-1bP         | 7        | 3.5%    |
| 5.8.0-7630-generic          | 6        | 3%      |
| 5.3.0-28-generic            | 6        | 3%      |
| 5.3.0-23-generic            | 4        | 2%      |
| 5.16.7-desktop-1omv4003     | 4        | 2%      |
| 5.4.0-7634-generic          | 3        | 1.5%    |
| 5.4.0-58-generic            | 3        | 1.5%    |
| 5.10.14-desktop-1omv4002    | 3        | 1.5%    |
| 4.9.20-desktop-pae-1bP      | 3        | 1.5%    |
| 5.8.0-36-generic            | 2        | 1%      |
| 5.8.0-14-generic            | 2        | 1%      |
| 5.4.0-80-generic            | 2        | 1%      |
| 5.4.0-74-generic            | 2        | 1%      |
| 5.4.0-73-generic            | 2        | 1%      |
| 5.4.0-65-generic            | 2        | 1%      |
| 5.3.0-46-generic            | 2        | 1%      |
| 5.19.0-32-generic           | 2        | 1%      |
| 5.19.0-23-generic           | 2        | 1%      |
| 5.15.0-56-generic           | 2        | 1%      |
| 5.15.0-48-generic           | 2        | 1%      |
| 5.15.0-41-generic           | 2        | 1%      |
| 5.15.0-27-generic           | 2        | 1%      |
| 5.13.0-7620-generic         | 2        | 1%      |
| 5.13.0-35-generic           | 2        | 1%      |
| 5.13.0-30-generic           | 2        | 1%      |
| 5.11.0-35-generic           | 2        | 1%      |
| 4.18.0-18-generic           | 2        | 1%      |
| 4.13.0-32-generic           | 2        | 1%      |
| 6.2.7-arch1-1               | 1        | 0.5%    |
| 6.2.6-desktop-1omv2390      | 1        | 0.5%    |
| 6.2.6-arch1-1               | 1        | 0.5%    |
| 6.2.11-300.fc38.x86_64      | 1        | 0.5%    |
| 6.1.9-1-MANJARO             | 1        | 0.5%    |
| 6.1.8-200.fc37.x86_64       | 1        | 0.5%    |
| 6.1.6-arch1-3               | 1        | 0.5%    |
| 6.1.19-1-MANJARO            | 1        | 0.5%    |
| 6.1.12-arch1-1              | 1        | 0.5%    |
| 6.1.1-desktop-1omv2290      | 1        | 0.5%    |
| 6.1.0-kali5-amd64           | 1        | 0.5%    |
| 6.0.7-201.fsync.fc36.x86_64 | 1        | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 24       | 12.57%  |
| 5.15.0  | 16       | 8.38%   |
| 5.8.0   | 15       | 7.85%   |
| 5.3.0   | 15       | 7.85%   |
| 5.13.0  | 11       | 5.76%   |
| 4.15.0  | 8        | 4.19%   |
| 5.19.0  | 7        | 3.66%   |
| 5.11.0  | 7        | 3.66%   |
| 4.18.16 | 7        | 3.66%   |
| 5.16.7  | 4        | 2.09%   |
| 5.17.5  | 3        | 1.57%   |
| 5.10.14 | 3        | 1.57%   |
| 5.0.0   | 3        | 1.57%   |
| 4.9.20  | 3        | 1.57%   |
| 4.19.0  | 3        | 1.57%   |
| 4.18.0  | 3        | 1.57%   |
| 6.2.6   | 2        | 1.05%   |
| 6.0.7   | 2        | 1.05%   |
| 6.0.0   | 2        | 1.05%   |
| 5.16.0  | 2        | 1.05%   |
| 5.10.0  | 2        | 1.05%   |
| 4.13.0  | 2        | 1.05%   |
| 6.2.7   | 1        | 0.52%   |
| 6.2.11  | 1        | 0.52%   |
| 6.1.9   | 1        | 0.52%   |
| 6.1.8   | 1        | 0.52%   |
| 6.1.6   | 1        | 0.52%   |
| 6.1.19  | 1        | 0.52%   |
| 6.1.12  | 1        | 0.52%   |
| 6.1.1   | 1        | 0.52%   |
| 6.1.0   | 1        | 0.52%   |
| 6.0.2   | 1        | 0.52%   |
| 6.0.16  | 1        | 0.52%   |
| 5.9.14  | 1        | 0.52%   |
| 5.9.11  | 1        | 0.52%   |
| 5.8.8   | 1        | 0.52%   |
| 5.8.4   | 1        | 0.52%   |
| 5.8.18  | 1        | 0.52%   |
| 5.7.11  | 1        | 0.52%   |
| 5.4.70  | 1        | 0.52%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 25       | 13.23%  |
| 5.15    | 21       | 11.11%  |
| 5.8     | 18       | 9.52%   |
| 5.3     | 15       | 7.94%   |
| 5.19    | 13       | 6.88%   |
| 5.13    | 12       | 6.35%   |
| 5.10    | 12       | 6.35%   |
| 4.18    | 10       | 5.29%   |
| 5.11    | 8        | 4.23%   |
| 4.15    | 8        | 4.23%   |
| 6.1     | 7        | 3.7%    |
| 6.0     | 6        | 3.17%   |
| 5.16    | 6        | 3.17%   |
| 4.9     | 5        | 2.65%   |
| 6.2     | 4        | 2.12%   |
| 5.18    | 3        | 1.59%   |
| 5.17    | 3        | 1.59%   |
| 5.0     | 3        | 1.59%   |
| 4.19    | 3        | 1.59%   |
| 5.9     | 2        | 1.06%   |
| 4.13    | 2        | 1.06%   |
| 5.7     | 1        | 0.53%   |
| 5.14    | 1        | 0.53%   |
| 5.1     | 1        | 0.53%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 168      | 96.55%  |
| i686   | 5        | 2.87%   |
| armv7l | 1        | 0.57%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 81       | 44.75%  |
| KDE5            | 49       | 27.07%  |
| XFCE            | 13       | 7.18%   |
| Unknown         | 11       | 6.08%   |
| X-Cinnamon      | 10       | 5.52%   |
| MATE            | 4        | 2.21%   |
| KDE             | 3        | 1.66%   |
| Unity           | 2        | 1.1%    |
| LXQt            | 2        | 1.1%    |
| Pantheon        | 1        | 0.55%   |
| openbox         | 1        | 0.55%   |
| LXDE            | 1        | 0.55%   |
| GNOME Flashback | 1        | 0.55%   |
| Budgie          | 1        | 0.55%   |
| awesome         | 1        | 0.55%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 148      | 85.06%  |
| Wayland | 16       | 9.2%    |
| Tty     | 5        | 2.87%   |
| Unknown | 5        | 2.87%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 105      | 58.66%  |
| SDDM    | 35       | 19.55%  |
| GDM3    | 15       | 8.38%   |
| LightDM | 11       | 6.15%   |
| GDM     | 11       | 6.15%   |
| TDM     | 2        | 1.12%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_PH   | 89       | 50%     |
| en_US   | 64       | 35.96%  |
| Unknown | 19       | 10.67%  |
| C       | 4        | 2.25%   |
| en_HK   | 1        | 0.56%   |
| de_DE   | 1        | 0.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 106      | 60.57%  |
| EFI  | 69       | 39.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 135      | 75.84%  |
| Btrfs   | 21       | 11.8%   |
| Overlay | 16       | 8.99%   |
| Unknown | 4        | 2.25%   |
| Xfs     | 1        | 0.56%   |
| Tmpfs   | 1        | 0.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 110      | 61.8%   |
| GPT     | 48       | 26.97%  |
| MBR     | 20       | 11.24%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 147      | 81.67%  |
| Yes       | 33       | 18.33%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 130      | 72.22%  |
| Yes       | 50       | 27.78%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 42       | 24.42%  |
| MSI                 | 33       | 19.19%  |
| ASUSTek Computer    | 33       | 19.19%  |
| ASRock              | 13       | 7.56%   |
| Hewlett-Packard     | 10       | 5.81%   |
| Dell                | 7        | 4.07%   |
| Biostar             | 7        | 4.07%   |
| ECS                 | 6        | 3.49%   |
| Foxconn             | 5        | 2.91%   |
| EMAXX TECHNOLOGY    | 4        | 2.33%   |
| Pegatron            | 2        | 1.16%   |
| YANYU               | 1        | 0.58%   |
| TriGem Computer     | 1        | 0.58%   |
| QTQD                | 1        | 0.58%   |
| NEC Computers       | 1        | 0.58%   |
| Lenovo              | 1        | 0.58%   |
| JOOYON              | 1        | 0.58%   |
| Intel               | 1        | 0.58%   |
| AMD                 | 1        | 0.58%   |
| Acer                | 1        | 0.58%   |
| Unknown             | 1        | 0.58%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| MSI MS-7309                   | 5        | 2.91%   |
| ASRock B450M Steel Legend     | 5        | 2.91%   |
| MSI MS-7721                   | 4        | 2.33%   |
| Gigabyte F2A68HM-S1           | 4        | 2.33%   |
| Gigabyte A320M-S2H V2         | 4        | 2.33%   |
| ASUS All Series               | 4        | 2.33%   |
| Foxconn G31MX Series          | 3        | 1.74%   |
| ECS G41T-R3                   | 3        | 1.74%   |
| ASUS P8H61-M LX3 PLUS R2.0    | 3        | 1.74%   |
| Pegatron IPMSB-H61            | 2        | 1.16%   |
| MSI MS-7C94                   | 2        | 1.16%   |
| Gigabyte Z590 AORUS ULTRA     | 2        | 1.16%   |
| Gigabyte H97M-D3H             | 2        | 1.16%   |
| Foxconn 500B Microtower       | 2        | 1.16%   |
| Biostar A320MH                | 2        | 1.16%   |
| ASUS PRIME B250M-K            | 2        | 1.16%   |
| ASUS EX-H310M-V3 R2.0         | 2        | 1.16%   |
| ASUS A68HM-K                  | 2        | 1.16%   |
| Unknown                       | 2        | 1.16%   |
| YANYU EPIC-C19                | 1        | 0.58%   |
| TriGem DreamSys               | 1        | 0.58%   |
| NEC Computers PC-MK36LBZCHEAM | 1        | 0.58%   |
| MSI MS-7D43                   | 1        | 0.58%   |
| MSI MS-7D23                   | 1        | 0.58%   |
| MSI MS-7D22                   | 1        | 0.58%   |
| MSI MS-7D18                   | 1        | 0.58%   |
| MSI MS-7D17                   | 1        | 0.58%   |
| MSI MS-7D14                   | 1        | 0.58%   |
| MSI MS-7C52                   | 1        | 0.58%   |
| MSI MS-7C02                   | 1        | 0.58%   |
| MSI MS-7B90                   | 1        | 0.58%   |
| MSI MS-7B89                   | 1        | 0.58%   |
| MSI MS-7A57                   | 1        | 0.58%   |
| MSI MS-7A38                   | 1        | 0.58%   |
| MSI MS-7A36                   | 1        | 0.58%   |
| MSI MS-7996                   | 1        | 0.58%   |
| MSI MS-7978                   | 1        | 0.58%   |
| MSI MS-7918                   | 1        | 0.58%   |
| MSI MS-7914                   | 1        | 0.58%   |
| MSI MS-7817                   | 1        | 0.58%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| Dell OptiPlex                 | 7        | 4.07%   |
| MSI MS-7309                   | 5        | 2.91%   |
| HP Compaq                     | 5        | 2.91%   |
| Gigabyte A320M-S2H            | 5        | 2.91%   |
| ASUS PRIME                    | 5        | 2.91%   |
| ASUS P8H61-M                  | 5        | 2.91%   |
| ASRock B450M                  | 5        | 2.91%   |
| MSI MS-7721                   | 4        | 2.33%   |
| Gigabyte F2A68HM-S1           | 4        | 2.33%   |
| ASUS All                      | 4        | 2.33%   |
| HP ProDesk                    | 3        | 1.74%   |
| Gigabyte B450                 | 3        | 1.74%   |
| Foxconn G31MX                 | 3        | 1.74%   |
| ECS G41T-R3                   | 3        | 1.74%   |
| ASUS TUF                      | 3        | 1.74%   |
| ASUS ROG                      | 3        | 1.74%   |
| Pegatron IPMSB-H61            | 2        | 1.16%   |
| MSI MS-7C94                   | 2        | 1.16%   |
| Gigabyte Z590                 | 2        | 1.16%   |
| Gigabyte X570                 | 2        | 1.16%   |
| Gigabyte H97M-D3H             | 2        | 1.16%   |
| Gigabyte B550                 | 2        | 1.16%   |
| Foxconn 500B                  | 2        | 1.16%   |
| Biostar A320MH                | 2        | 1.16%   |
| ASUS EX-H310M-V3              | 2        | 1.16%   |
| ASUS A68HM-K                  | 2        | 1.16%   |
| Unknown                       | 2        | 1.16%   |
| YANYU EPIC-C19                | 1        | 0.58%   |
| TriGem DreamSys               | 1        | 0.58%   |
| NEC Computers PC-MK36LBZCHEAM | 1        | 0.58%   |
| MSI MS-7D43                   | 1        | 0.58%   |
| MSI MS-7D23                   | 1        | 0.58%   |
| MSI MS-7D22                   | 1        | 0.58%   |
| MSI MS-7D18                   | 1        | 0.58%   |
| MSI MS-7D17                   | 1        | 0.58%   |
| MSI MS-7D14                   | 1        | 0.58%   |
| MSI MS-7C52                   | 1        | 0.58%   |
| MSI MS-7C02                   | 1        | 0.58%   |
| MSI MS-7B90                   | 1        | 0.58%   |
| MSI MS-7B89                   | 1        | 0.58%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2014    | 20       | 11.63%  |
| 2018    | 18       | 10.47%  |
| 2012    | 15       | 8.72%   |
| 2010    | 14       | 8.14%   |
| 2020    | 12       | 6.98%   |
| 2015    | 12       | 6.98%   |
| 2013    | 12       | 6.98%   |
| 2021    | 11       | 6.4%    |
| 2019    | 11       | 6.4%    |
| 2017    | 11       | 6.4%    |
| 2009    | 10       | 5.81%   |
| 2011    | 8        | 4.65%   |
| 2016    | 6        | 3.49%   |
| 2007    | 4        | 2.33%   |
| 2006    | 4        | 2.33%   |
| 2008    | 2        | 1.16%   |
| 2022    | 1        | 0.58%   |
| Unknown | 1        | 0.58%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 172      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 167      | 97.09%  |
| Enabled  | 5        | 2.91%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 172      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 44       | 24.44%  |
| 3.01-4.0    | 35       | 19.44%  |
| 4.01-8.0    | 32       | 17.78%  |
| 16.01-24.0  | 32       | 17.78%  |
| 32.01-64.0  | 16       | 8.89%   |
| 1.01-2.0    | 8        | 4.44%   |
| 64.01-256.0 | 6        | 3.33%   |
| 2.01-3.0    | 5        | 2.78%   |
| 24.01-32.0  | 2        | 1.11%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 63       | 33.16%  |
| 2.01-3.0   | 43       | 22.63%  |
| 4.01-8.0   | 29       | 15.26%  |
| 3.01-4.0   | 20       | 10.53%  |
| 0.51-1.0   | 17       | 8.95%   |
| 8.01-16.0  | 9        | 4.74%   |
| 0.01-0.5   | 7        | 3.68%   |
| 24.01-32.0 | 1        | 0.53%   |
| 16.01-24.0 | 1        | 0.53%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 79       | 43.41%  |
| 2      | 58       | 31.87%  |
| 3      | 17       | 9.34%   |
| 4      | 16       | 8.79%   |
| 5      | 7        | 3.85%   |
| 0      | 2        | 1.1%    |
| 14     | 1        | 0.55%   |
| 13     | 1        | 0.55%   |
| 6      | 1        | 0.55%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 140      | 78.21%  |
| Yes       | 39       | 21.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 171      | 99.42%  |
| No        | 1        | 0.58%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 100      | 57.14%  |
| Yes       | 75       | 42.86%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 126      | 72.83%  |
| Yes       | 47       | 27.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Philippines | 172      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Quezon City       | 37       | 19.17%  |
| Davao City        | 11       | 5.7%    |
| Cagayan de Oro    | 11       | 5.7%    |
| Angeles City      | 9        | 4.66%   |
| Iligan City       | 7        | 3.63%   |
| Bacolod City      | 7        | 3.63%   |
| Zamboanga City    | 6        | 3.11%   |
| San Miguel        | 6        | 3.11%   |
| Cebu City         | 6        | 3.11%   |
| Caloocan City     | 6        | 3.11%   |
| Manila            | 5        | 2.59%   |
| Mandaluyong City  | 5        | 2.59%   |
| Bacoor            | 5        | 2.59%   |
| Santa Rosa        | 4        | 2.07%   |
| Paranaque City    | 4        | 2.07%   |
| Makati City       | 4        | 2.07%   |
| Tarlac City       | 3        | 1.55%   |
| Pasig             | 3        | 1.55%   |
| Manajao           | 3        | 1.55%   |
| Lipa City         | 3        | 1.55%   |
| Imus              | 3        | 1.55%   |
| Antipolo City     | 3        | 1.55%   |
| Mandaue City      | 2        | 1.04%   |
| Malolos           | 2        | 1.04%   |
| Magugpo Poblacion | 2        | 1.04%   |
| Dumaguete         | 2        | 1.04%   |
| Abaga             | 2        | 1.04%   |
| Tuguegarao City   | 1        | 0.52%   |
| Taytay            | 1        | 0.52%   |
| Tanza             | 1        | 0.52%   |
| Taguig            | 1        | 0.52%   |
| Tagbilaran        | 1        | 0.52%   |
| Tabaco            | 1        | 0.52%   |
| Sibulan           | 1        | 0.52%   |
| San Leonardo      | 1        | 0.52%   |
| San Jose          | 1        | 0.52%   |
| San Fernando City | 1        | 0.52%   |
| San Carlos City   | 1        | 0.52%   |
| San Carlos        | 1        | 0.52%   |
| Nagcarlan         | 1        | 0.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 69       | 99     | 21.84%  |
| WDC                       | 58       | 79     | 18.35%  |
| Samsung Electronics       | 21       | 32     | 6.65%   |
| Kingston                  | 21       | 28     | 6.65%   |
| Toshiba                   | 19       | 25     | 6.01%   |
| Hitachi                   | 18       | 32     | 5.7%    |
| SanDisk                   | 12       | 15     | 3.8%    |
| Transcend                 | 7        | 7      | 2.22%   |
| Lexar                     | 7        | 8      | 2.22%   |
| Gigabyte Technology       | 6        | 9      | 1.9%    |
| Crucial                   | 6        | 8      | 1.9%    |
| Team                      | 5        | 7      | 1.58%   |
| PNY                       | 4        | 4      | 1.27%   |
| HGST                      | 4        | 5      | 1.27%   |
| A-DATA Technology         | 4        | 4      | 1.27%   |
| WALRAM                    | 3        | 3      | 0.95%   |
| Unknown                   | 3        | 4      | 0.95%   |
| Ramsta                    | 3        | 3      | 0.95%   |
| Fujitsu                   | 3        | 3      | 0.95%   |
| Unknown                   | 3        | 3      | 0.95%   |
| XPG                       | 2        | 2      | 0.63%   |
| SK hynix                  | 2        | 8      | 0.63%   |
| Phison Electronics        | 2        | 2      | 0.63%   |
| Phison                    | 2        | 2      | 0.63%   |
| Patriot                   | 2        | 2      | 0.63%   |
| KingSpec                  | 2        | 2      | 0.63%   |
| Intel                     | 2        | 3      | 0.63%   |
| Indilinx                  | 2        | 2      | 0.63%   |
| HS-SSD-C100               | 2        | 2      | 0.63%   |
| ZOTAC                     | 1        | 1      | 0.32%   |
| XrayDisk                  | 1        | 1      | 0.32%   |
| Voyager                   | 1        | 1      | 0.32%   |
| USB                       | 1        | 1      | 0.32%   |
| TAMMUZ                    | 1        | 1      | 0.32%   |
| T-FORCE                   | 1        | 1      | 0.32%   |
| SKIHOTAR                  | 1        | 1      | 0.32%   |
| Realtek Semiconductor     | 1        | 1      | 0.32%   |
| Micron/Crucial Technology | 1        | 1      | 0.32%   |
| Kingmax                   | 1        | 1      | 0.32%   |
| KingFast                  | 1        | 1      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB  | 12       | 3.36%   |
| Seagate ST500DM002-1BD142 500GB | 11       | 3.08%   |
| Toshiba DT01ACA050 500GB        | 7        | 1.96%   |
| WDC WD10EZEX-08WN4A0 1TB        | 5        | 1.4%    |
| Seagate ST4000DM004-2CV104 4TB  | 5        | 1.4%    |
| Kingston SA400S37120G 120GB SSD | 5        | 1.4%    |
| Hitachi HDS721050CLA362 500GB   | 5        | 1.4%    |
| Seagate ST2000DM008-2FR102 2TB  | 4        | 1.12%   |
| Samsung SSD 860 EVO 500GB       | 4        | 1.12%   |
| Samsung SSD 860 EVO 250GB       | 4        | 1.12%   |
| Hitachi HDS721616PLA380 160GB   | 4        | 1.12%   |
| WDC WD5000AZLX-60K2TA0 500GB    | 3        | 0.84%   |
| WDC WD10EZEX-22MFCA0 1TB        | 3        | 0.84%   |
| Transcend TS128GSSD370S 128GB   | 3        | 0.84%   |
| Toshiba MQ01ABD100 1TB          | 3        | 0.84%   |
| Toshiba DT01ACA100 1TB          | 3        | 0.84%   |
| Seagate ST500DM002-1ER14C 500GB | 3        | 0.84%   |
| Seagate ST3160812AS 160GB       | 3        | 0.84%   |
| SanDisk SDSSDA240G 240GB        | 3        | 0.84%   |
| PNY CS900 240GB SSD             | 3        | 0.84%   |
| Lexar 128GB SSD                 | 3        | 0.84%   |
| Hitachi HTS543232A7A384 320GB   | 3        | 0.84%   |
| Hitachi HDS721050CLA660 500GB   | 3        | 0.84%   |
| Crucial CT500P2SSD8 500GB       | 3        | 0.84%   |
| Unknown                         | 3        | 0.84%   |
| WDC WD5003ABYZ-011FA0 500GB     | 2        | 0.56%   |
| WDC WD5000AAVS-00ZTB0 500GB     | 2        | 0.56%   |
| WDC WD20EARX-00ZUDB0 2TB        | 2        | 0.56%   |
| WDC WD10EZEX-08M2NA0 1TB        | 2        | 0.56%   |
| WDC WD10EZEX-00WN4A0 1TB        | 2        | 0.56%   |
| WDC WD10EZEX-00BN5A0 1TB        | 2        | 0.56%   |
| Transcend TS240GSSD220S 240GB   | 2        | 0.56%   |
| Toshiba THNSNJ128G8NU 128GB SSD | 2        | 0.56%   |
| Team T253X2256G 256GB SSD       | 2        | 0.56%   |
| Seagate ST3500418AS 500GB       | 2        | 0.56%   |
| Seagate ST3500413AS 500GB       | 2        | 0.56%   |
| Seagate ST3500312CS 500GB       | 2        | 0.56%   |
| Seagate ST31000524AS 1TB        | 2        | 0.56%   |
| Seagate ST250DM000-1BD141 250GB | 2        | 0.56%   |
| Seagate ST1000DM003-9YN162 1TB  | 2        | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 69       | 98     | 39.88%  |
| WDC                 | 56       | 72     | 32.37%  |
| Toshiba             | 18       | 22     | 10.4%   |
| Hitachi             | 18       | 32     | 10.4%   |
| HGST                | 4        | 5      | 2.31%   |
| Samsung Electronics | 3        | 4      | 1.73%   |
| Fujitsu             | 3        | 3      | 1.73%   |
| Unknown             | 1        | 1      | 0.58%   |
| ExcelStor           | 1        | 1      | 0.58%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 18       | 23     | 17.14%  |
| Samsung Electronics | 12       | 19     | 11.43%  |
| SanDisk             | 10       | 12     | 9.52%   |
| Transcend           | 6        | 6      | 5.71%   |
| Lexar               | 6        | 7      | 5.71%   |
| WDC                 | 5        | 7      | 4.76%   |
| Team                | 5        | 7      | 4.76%   |
| PNY                 | 4        | 4      | 3.81%   |
| A-DATA Technology   | 4        | 4      | 3.81%   |
| Gigabyte Technology | 3        | 3      | 2.86%   |
| Toshiba             | 2        | 2      | 1.9%    |
| SK hynix            | 2        | 8      | 1.9%    |
| Ramsta              | 2        | 2      | 1.9%    |
| Patriot             | 2        | 2      | 1.9%    |
| KingSpec            | 2        | 2      | 1.9%    |
| Intel               | 2        | 3      | 1.9%    |
| Crucial             | 2        | 3      | 1.9%    |
| ZOTAC               | 1        | 1      | 0.95%   |
| WALRAM              | 1        | 1      | 0.95%   |
| Unknown             | 1        | 2      | 0.95%   |
| TAMMUZ              | 1        | 1      | 0.95%   |
| SKIHOTAR            | 1        | 1      | 0.95%   |
| Kingmax             | 1        | 1      | 0.95%   |
| Kimtigo             | 1        | 2      | 0.95%   |
| Indilinx            | 1        | 1      | 0.95%   |
| HS-SSD-E100         | 1        | 1      | 0.95%   |
| HS-SSD-C100         | 1        | 1      | 0.95%   |
| Hikvision           | 1        | 2      | 0.95%   |
| GLOWAY              | 1        | 2      | 0.95%   |
| FORESEE             | 1        | 1      | 0.95%   |
| Dahua               | 1        | 1      | 0.95%   |
| Corsair             | 1        | 1      | 0.95%   |
| China               | 1        | 5      | 0.95%   |
| CERVVO              | 1        | 1      | 0.95%   |
| Unknown             | 1        | 1      | 0.95%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 137      | 238    | 53.31%  |
| SSD     | 79       | 140    | 30.74%  |
| NVMe    | 30       | 41     | 11.67%  |
| Unknown | 10       | 12     | 3.89%   |
| MMC     | 1        | 1      | 0.39%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 163      | 379    | 80.69%  |
| NVMe | 30       | 41     | 14.85%  |
| SAS  | 8        | 11     | 3.96%   |
| MMC  | 1        | 1      | 0.5%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 138      | 257    | 64.49%  |
| 0.51-1.0   | 52       | 90     | 24.3%   |
| 1.01-2.0   | 14       | 16     | 6.54%   |
| 3.01-4.0   | 9        | 14     | 4.21%   |
| 10.01-20.0 | 1        | 1      | 0.47%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 57       | 30.32%  |
| 251-500        | 45       | 23.94%  |
| 501-1000       | 18       | 9.57%   |
| 1001-2000      | 17       | 9.04%   |
| 51-100         | 12       | 6.38%   |
| More than 3000 | 10       | 5.32%   |
| 1-20           | 10       | 5.32%   |
| 2001-3000      | 8        | 4.26%   |
| Unknown        | 6        | 3.19%   |
| 21-50          | 5        | 2.66%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 63       | 33.33%  |
| 21-50          | 37       | 19.58%  |
| 101-250        | 23       | 12.17%  |
| 51-100         | 23       | 12.17%  |
| 251-500        | 12       | 6.35%   |
| 501-1000       | 12       | 6.35%   |
| 1001-2000      | 6        | 3.17%   |
| Unknown        | 6        | 3.17%   |
| 2001-3000      | 5        | 2.65%   |
| More than 3000 | 2        | 1.06%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Hitachi HDS721050CLA362 500GB   | 5        | 10     | 18.52%  |
| Hitachi HTS543232A7A384 320GB   | 3        | 5      | 11.11%  |
| HGST HTS541010A9E680 1TB        | 2        | 3      | 7.41%   |
| WDC WD5003ABYZ-011FA0 500GB     | 1        | 1      | 3.7%    |
| WDC WD5000LPCX-60VHAT0 500GB    | 1        | 2      | 3.7%    |
| WDC WD5000AAVS-00ZTB0 500GB     | 1        | 1      | 3.7%    |
| WDC WD5000AAKX-603CA0 500GB     | 1        | 1      | 3.7%    |
| WDC WD3200AAJS-08L7A0 320GB     | 1        | 1      | 3.7%    |
| WDC WD10EZEX-00MFCA0 1TB        | 1        | 1      | 3.7%    |
| Unknown S050 Hard drive 500GB   | 1        | 1      | 3.7%    |
| Toshiba MQ01ABD100 1TB          | 1        | 1      | 3.7%    |
| Toshiba DT01ACA100 1TB          | 1        | 1      | 3.7%    |
| Toshiba DT01ACA050 500GB        | 1        | 1      | 3.7%    |
| Seagate ST500DM002-1BD142 500GB | 1        | 2      | 3.7%    |
| Seagate ST380815AS 80GB         | 1        | 1      | 3.7%    |
| Seagate ST3500514NS 500GB       | 1        | 1      | 3.7%    |
| Seagate ST3500418AS 500GB       | 1        | 1      | 3.7%    |
| Seagate ST2000DM008-2FR102 2TB  | 1        | 1      | 3.7%    |
| SanDisk SDSSDA240G 240GB        | 1        | 1      | 3.7%    |
| Hitachi HDS721050CLA660 500GB   | 1        | 1      | 3.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 6        | 7      | 26.09%  |
| Hitachi | 6        | 16     | 26.09%  |
| Seagate | 5        | 6      | 21.74%  |
| Toshiba | 2        | 3      | 8.7%    |
| HGST    | 2        | 3      | 8.7%    |
| Unknown | 1        | 1      | 4.35%   |
| SanDisk | 1        | 1      | 4.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 6        | 7      | 27.27%  |
| Hitachi | 6        | 16     | 27.27%  |
| Seagate | 5        | 6      | 22.73%  |
| Toshiba | 2        | 3      | 9.09%   |
| HGST    | 2        | 3      | 9.09%   |
| Unknown | 1        | 1      | 4.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 18       | 36     | 94.74%  |
| SSD  | 1        | 1      | 5.26%   |

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
| Detected | 115      | 274    | 61.83%  |
| Works    | 52       | 121    | 27.96%  |
| Malfunc  | 19       | 37     | 10.22%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 93       | 44.5%   |
| AMD                          | 69       | 33.01%  |
| Phison Electronics           | 8        | 3.83%   |
| Nvidia                       | 8        | 3.83%   |
| Samsung Electronics          | 7        | 3.35%   |
| Micron/Crucial Technology    | 4        | 1.91%   |
| Silicon Motion               | 3        | 1.44%   |
| Marvell Technology Group     | 3        | 1.44%   |
| Kingston Technology Company  | 3        | 1.44%   |
| ASMedia Technology           | 3        | 1.44%   |
| SanDisk                      | 2        | 0.96%   |
| ADATA Technology             | 2        | 0.96%   |
| Toshiba America Info Systems | 1        | 0.48%   |
| Realtek Semiconductor        | 1        | 0.48%   |
| JMicron Technology           | 1        | 0.48%   |
| Broadcom / LSI               | 1        | 0.48%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 39       | 13.45%  |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 17       | 5.86%   |
| AMD 400 Series Chipset SATA Controller                                                  | 17       | 5.86%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 15       | 5.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 13       | 4.48%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 9        | 3.1%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 9        | 3.1%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 9        | 3.1%    |
| AMD FCH SATA Controller [IDE mode]                                                      | 9        | 3.1%    |
| Nvidia MCP61 SATA Controller                                                            | 8        | 2.76%   |
| Nvidia MCP61 IDE                                                                        | 8        | 2.76%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 8        | 2.76%   |
| AMD 500 Series Chipset SATA Controller                                                  | 8        | 2.76%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 7        | 2.41%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6        | 2.07%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6        | 2.07%   |
| AMD FCH SATA Controller D                                                               | 6        | 2.07%   |
| AMD 300 Series Chipset SATA Controller                                                  | 6        | 2.07%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 5        | 1.72%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 5        | 1.72%   |
| AMD FCH IDE Controller                                                                  | 5        | 1.72%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 4        | 1.38%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 4        | 1.38%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 1.38%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3        | 1.03%   |
| Samsung NVMe SSD Controller 980                                                         | 3        | 1.03%   |
| Phison PS5013 E13 NVMe Controller                                                       | 3        | 1.03%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 1.03%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3        | 1.03%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 1.03%   |
| Kingston Company NVMe Controller                                                        | 2        | 0.69%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2        | 0.69%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2        | 0.69%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 0.69%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2        | 0.69%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 0.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 0.69%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 2        | 0.69%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                    | 1        | 0.34%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1        | 0.34%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 129      | 58.9%   |
| IDE  | 53       | 24.2%   |
| NVMe | 30       | 13.7%   |
| RAID | 6        | 2.74%   |
| SAS  | 1        | 0.46%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 94       | 54.65%  |
| AMD    | 77       | 44.77%  |
| ARM    | 1        | 0.58%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 7        | 4.07%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 6        | 3.49%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 6        | 3.49%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 4        | 2.33%   |
| AMD Sempron Processor LE-1100                 | 4        | 2.33%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 4        | 2.33%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 3        | 1.74%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 3        | 1.74%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 3        | 1.74%   |
| AMD A8-7600 Radeon R7, 10 Compute Cores 4C+6G | 3        | 1.74%   |
| AMD A6-6400K APU with Radeon HD Graphics      | 3        | 1.74%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 2        | 1.16%   |
| Intel Pentium CPU G2020 @ 2.90GHz             | 2        | 1.16%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 2        | 1.16%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 2        | 1.16%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 2        | 1.16%   |
| Intel Core i5-4690K CPU @ 3.50GHz             | 2        | 1.16%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 2        | 1.16%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 2        | 1.16%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 2        | 1.16%   |
| Intel Core i3-4170 CPU @ 3.70GHz              | 2        | 1.16%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 2        | 1.16%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 2        | 1.16%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz         | 2        | 1.16%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz         | 2        | 1.16%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 2        | 1.16%   |
| Intel 12th Gen Core i5-12400                  | 2        | 1.16%   |
| Intel 11th Gen Core i9-11900K @ 3.50GHz       | 2        | 1.16%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz        | 2        | 1.16%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 2        | 1.16%   |
| AMD Ryzen 7 2700 Eight-Core Processor         | 2        | 1.16%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 2        | 1.16%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 2        | 1.16%   |
| AMD A6-7480 Radeon R5, 8 Compute Cores 2C+6G  | 2        | 1.16%   |
| AMD A6-7400K Radeon R5, 6 Compute Cores 2C+4G | 2        | 1.16%   |
| AMD A10-5800K APU with Radeon HD Graphics     | 2        | 1.16%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz           | 1        | 0.58%   |
| Intel Pentium Gold G6400 CPU @ 4.00GHz        | 1        | 0.58%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz        | 1        | 0.58%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz   | 1        | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 25       | 14.53%  |
| AMD Ryzen 5             | 24       | 13.95%  |
| Intel Core i7           | 15       | 8.72%   |
| Intel Core i3           | 15       | 8.72%   |
| Intel Core 2 Duo        | 11       | 6.4%    |
| AMD A6                  | 9        | 5.23%   |
| Other                   | 8        | 4.65%   |
| AMD Ryzen 3             | 6        | 3.49%   |
| Intel Core 2 Quad       | 5        | 2.91%   |
| Intel Pentium Dual-Core | 4        | 2.33%   |
| Intel Pentium           | 4        | 2.33%   |
| Intel Celeron           | 4        | 2.33%   |
| AMD Sempron             | 4        | 2.33%   |
| AMD Ryzen 7             | 4        | 2.33%   |
| AMD FX                  | 4        | 2.33%   |
| AMD A8                  | 4        | 2.33%   |
| AMD Phenom II X4        | 3        | 1.74%   |
| AMD Athlon II X2        | 3        | 1.74%   |
| AMD A4                  | 3        | 1.74%   |
| AMD A10                 | 3        | 1.74%   |
| Intel Pentium Gold      | 2        | 1.16%   |
| AMD Ryzen 9             | 2        | 1.16%   |
| AMD Athlon              | 2        | 1.16%   |
| Intel Xeon              | 1        | 0.58%   |
| Intel Core i9           | 1        | 0.58%   |
| Intel Core 2            | 1        | 0.58%   |
| AMD Ryzen 7 PRO         | 1        | 0.58%   |
| AMD Ryzen 5 PRO         | 1        | 0.58%   |
| AMD Phenom II X2        | 1        | 0.58%   |
| AMD Athlon X4           | 1        | 0.58%   |
| AMD Athlon 64 X2        | 1        | 0.58%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 59       | 34.3%   |
| 2      | 56       | 32.56%  |
| 6      | 30       | 17.44%  |
| 1      | 15       | 8.72%   |
| 8      | 7        | 4.07%   |
| 16     | 2        | 1.16%   |
| 12     | 1        | 0.58%   |
| 10     | 1        | 0.58%   |
| 3      | 1        | 0.58%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 171      | 99.42%  |
| 2      | 1        | 0.58%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 99       | 57.56%  |
| 1      | 73       | 42.44%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 170      | 98.27%  |
| Unknown        | 3        | 1.73%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 51       | 29.31%  |
| 0x306c3    | 14       | 8.05%   |
| 0x1067a    | 12       | 6.9%    |
| 0x306a9    | 7        | 4.02%   |
| 0x08701021 | 7        | 4.02%   |
| 0x0800820d | 7        | 4.02%   |
| 0x06001119 | 6        | 3.45%   |
| 0x906ea    | 5        | 2.87%   |
| 0x906e9    | 5        | 2.87%   |
| 0x506e3    | 5        | 2.87%   |
| 0x06003106 | 5        | 2.87%   |
| 0xa0671    | 4        | 2.3%    |
| 0x206a7    | 4        | 2.3%    |
| 0x10676    | 3        | 1.72%   |
| 0x08600106 | 3        | 1.72%   |
| 0x08108109 | 3        | 1.72%   |
| 0x6fb      | 2        | 1.15%   |
| 0x0810100b | 2        | 1.15%   |
| 0x0600611a | 2        | 1.15%   |
| 0x010000c8 | 2        | 1.15%   |
| 0x010000c7 | 2        | 1.15%   |
| 0xa0655    | 1        | 0.57%   |
| 0xa0653    | 1        | 0.57%   |
| 0x90675    | 1        | 0.57%   |
| 0x90672    | 1        | 0.57%   |
| 0x706a1    | 1        | 0.57%   |
| 0x6f6      | 1        | 0.57%   |
| 0x50654    | 1        | 0.57%   |
| 0x406f1    | 1        | 0.57%   |
| 0x40651    | 1        | 0.57%   |
| 0x30679    | 1        | 0.57%   |
| 0x106e5    | 1        | 0.57%   |
| 0x0a50000d | 1        | 0.57%   |
| 0x0a50000c | 1        | 0.57%   |
| 0x0a201016 | 1        | 0.57%   |
| 0x08101102 | 1        | 0.57%   |
| 0x08101016 | 1        | 0.57%   |
| 0x08101007 | 1        | 0.57%   |
| 0x0700010f | 1        | 0.57%   |
| 0x06000852 | 1        | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 19       | 11.05%  |
| Penryn           | 18       | 10.47%  |
| IvyBridge        | 14       | 8.14%   |
| Zen+             | 13       | 7.56%   |
| Zen 2            | 13       | 7.56%   |
| Piledriver       | 13       | 7.56%   |
| KabyLake         | 12       | 6.98%   |
| Zen              | 7        | 4.07%   |
| Skylake          | 7        | 4.07%   |
| K10              | 7        | 4.07%   |
| Zen 3            | 6        | 3.49%   |
| Steamroller      | 6        | 3.49%   |
| SandyBridge      | 6        | 3.49%   |
| K8 Hammer        | 5        | 2.91%   |
| Excavator        | 4        | 2.33%   |
| CometLake        | 4        | 2.33%   |
| Icelake          | 3        | 1.74%   |
| Core             | 3        | 1.74%   |
| Nehalem          | 2        | 1.16%   |
| Alderlake Hybrid | 2        | 1.16%   |
| Unknown          | 2        | 1.16%   |
| Silvermont       | 1        | 0.58%   |
| K10 Llano        | 1        | 0.58%   |
| Jaguar           | 1        | 0.58%   |
| Goldmont plus    | 1        | 0.58%   |
| Bulldozer        | 1        | 0.58%   |
| Broadwell        | 1        | 0.58%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 71       | 37.37%  |
| AMD    | 66       | 34.74%  |
| Intel  | 53       | 27.89%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 11       | 5.64%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 9        | 4.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7        | 3.59%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 6        | 3.08%   |
| Nvidia G72 [GeForce 7200 GS / 7300 SE]                                      | 6        | 3.08%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 6        | 3.08%   |
| Nvidia GT218 [GeForce 210]                                                  | 5        | 2.56%   |
| Nvidia GF108 [GeForce GT 730]                                               | 5        | 2.56%   |
| Nvidia GF108 [GeForce GT 630]                                               | 5        | 2.56%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 5        | 2.56%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 4        | 2.05%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 4        | 2.05%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 2.05%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 4        | 2.05%   |
| Intel HD Graphics 630                                                       | 4        | 2.05%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 4        | 2.05%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4        | 2.05%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 4        | 2.05%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4        | 2.05%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 4        | 2.05%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 1.54%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 1.54%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 3        | 1.54%   |
| Intel HD Graphics 530                                                       | 3        | 1.54%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 3        | 1.54%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 3        | 1.54%   |
| AMD Richland [Radeon HD 8470D]                                              | 3        | 1.54%   |
| AMD Renoir                                                                  | 3        | 1.54%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 3        | 1.54%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 1.03%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 1.03%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 1.03%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 2        | 1.03%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 2        | 1.03%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 1.03%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 1.03%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 1.03%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.51%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.51%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 63       | 35%     |
| 1 x Nvidia     | 62       | 34.44%  |
| 1 x Intel      | 43       | 23.89%  |
| Intel + Nvidia | 6        | 3.33%   |
| 2 x Nvidia     | 2        | 1.11%   |
| Other          | 1        | 0.56%   |
| 2 x AMD        | 1        | 0.56%   |
| Intel + AMD    | 1        | 0.56%   |
| AMD + Nvidia   | 1        | 0.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 128      | 73.56%  |
| Proprietary | 38       | 21.84%  |
| Unknown     | 8        | 4.6%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 77       | 43.26%  |
| 1.01-2.0   | 28       | 15.73%  |
| 0.51-1.0   | 18       | 10.11%  |
| 0.01-0.5   | 17       | 9.55%   |
| 3.01-4.0   | 14       | 7.87%   |
| 7.01-8.0   | 10       | 5.62%   |
| 5.01-6.0   | 7        | 3.93%   |
| 8.01-16.0  | 5        | 2.81%   |
| 2.01-3.0   | 2        | 1.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 26       | 14.69%  |
| Dell                 | 25       | 14.12%  |
| AOC                  | 17       | 9.6%    |
| Acer                 | 16       | 9.04%   |
| Hewlett-Packard      | 8        | 4.52%   |
| Goldstar             | 8        | 4.52%   |
| ASUSTek Computer     | 7        | 3.95%   |
| Sony                 | 5        | 2.82%   |
| IPS                  | 5        | 2.82%   |
| BenQ                 | 5        | 2.82%   |
| ViewSonic            | 4        | 2.26%   |
| Lenovo               | 4        | 2.26%   |
| Ancor Communications | 4        | 2.26%   |
| Philips              | 3        | 1.69%   |
| Mi                   | 3        | 1.69%   |
| Unknown              | 3        | 1.69%   |
| VIE                  | 2        | 1.13%   |
| Unknown (XXX)        | 2        | 1.13%   |
| Unknown              | 2        | 1.13%   |
| MSI                  | 2        | 1.13%   |
| eMachines            | 2        | 1.13%   |
| Eizo                 | 2        | 1.13%   |
| SMC                  | 1        | 0.56%   |
| Sharp                | 1        | 0.56%   |
| SGT                  | 1        | 0.56%   |
| SANYO                | 1        | 0.56%   |
| SAC                  | 1        | 0.56%   |
| RGT                  | 1        | 0.56%   |
| Pixio                | 1        | 0.56%   |
| NVISION              | 1        | 0.56%   |
| NVI                  | 1        | 0.56%   |
| NEX                  | 1        | 0.56%   |
| MStar                | 1        | 0.56%   |
| LLL                  | 1        | 0.56%   |
| HON                  | 1        | 0.56%   |
| HKC                  | 1        | 0.56%   |
| HGC                  | 1        | 0.56%   |
| GDH                  | 1        | 0.56%   |
| EXP                  | 1        | 0.56%   |
| ELSA International   | 1        | 0.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch  | 4        | 2.14%   |
| Dell SE177FP DELF001 1280x1024 338x270mm 17.0-inch                | 4        | 2.14%   |
| AOC 1970W-1 AOC1970 1366x768 410x230mm 18.5-inch                  | 4        | 2.14%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch | 3        | 1.6%    |
| Lenovo LT1952p Wide LEN0990 1440x900 408x255mm 18.9-inch          | 3        | 1.6%    |
| Dell P170S DEL4058 1280x1024 338x270mm 17.0-inch                  | 3        | 1.6%    |
| AOC 2060W3 AOC2060 1920x1080 435x239mm 19.5-inch                  | 3        | 1.6%    |
| Unknown                                                           | 3        | 1.6%    |
| VIE A/G1956 VIE1850 1366x768 414x257mm 19.2-inch                  | 2        | 1.07%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch | 2        | 1.07%   |
| Mi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                  | 2        | 1.07%   |
| IPS R220 IPS2150 1920x1080 480x260mm 21.5-inch                    | 2        | 1.07%   |
| IPS IP22V1 IPS2200 1920x1080 409x330mm 20.7-inch                  | 2        | 1.07%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch         | 2        | 1.07%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                  | 2        | 1.07%   |
| Dell P170S DEL4059 1280x1024 338x270mm 17.0-inch                  | 2        | 1.07%   |
| Dell E228WFP DELD015 1680x1050 473x296mm 22.0-inch                | 2        | 1.07%   |
| Dell E198FP DELA028 1280x1024 380x300mm 19.1-inch                 | 2        | 1.07%   |
| ASUSTek Computer VG27AQL1A AUS2705 2560x1440 597x336mm 27.0-inch  | 2        | 1.07%   |
| AOC 22V2WG5 AOC2202 1920x1080 476x268mm 21.5-inch                 | 2        | 1.07%   |
| Acer S200HQL ACR0359 1600x900 434x236mm 19.4-inch                 | 2        | 1.07%   |
| Acer R230H ACR046E 1920x1080 509x286mm 23.0-inch                  | 2        | 1.07%   |
| Acer EB192Q ACR0517 1366x768 410x230mm 18.5-inch                  | 2        | 1.07%   |
| ViewSonic XG2705 VSC0E39 1920x1080 598x336mm 27.0-inch            | 1        | 0.53%   |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch     | 1        | 0.53%   |
| ViewSonic VA1917 SERIES VSCAD30 1366x768 410x230mm 18.5-inch      | 1        | 0.53%   |
| ViewSonic VA1601W-LED VSC1A25 1366x768 344x193mm 15.5-inch        | 1        | 0.53%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                             | 1        | 0.53%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch         | 1        | 0.53%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch     | 1        | 0.53%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch    | 1        | 0.53%   |
| Sony TV SNYAB03 1920x1080                                         | 1        | 0.53%   |
| Sony TV SNYA301 1920x1080                                         | 1        | 0.53%   |
| Sony TV SNY4B03 1920x1080 1063x598mm 48.0-inch                    | 1        | 0.53%   |
| Sony TV SNY2A01 1360x768                                          | 1        | 0.53%   |
| Sony TV SNY1A02 1920x1080                                         | 1        | 0.53%   |
| SMC LCD Monitor SMC0001 1920x540 720x420mm 32.8-inch              | 1        | 0.53%   |
| Sharp LL-153A-B SHP2163 1024x768 304x228mm 15.0-inch              | 1        | 0.53%   |
| SGT Monitor SGT2360 1920x1080 521x299mm 23.6-inch                 | 1        | 0.53%   |
| SANYO LED MONITOR SAN309A 1920x1080 443x249mm 20.0-inch           | 1        | 0.53%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 76       | 45.51%  |
| 1366x768 (WXGA)    | 28       | 16.77%  |
| 1280x1024 (SXGA)   | 18       | 10.78%  |
| 1600x900 (HD+)     | 12       | 7.19%   |
| 3840x2160 (4K)     | 9        | 5.39%   |
| 1440x900 (WXGA+)   | 5        | 2.99%   |
| 3440x1440          | 4        | 2.4%    |
| 2560x1440 (QHD)    | 3        | 1.8%    |
| 1920x1200 (WUXGA)  | 2        | 1.2%    |
| 1680x1050 (WSXGA+) | 2        | 1.2%    |
| 1360x768           | 2        | 1.2%    |
| 1024x768 (XGA)     | 2        | 1.2%    |
| 3200x1080          | 1        | 0.6%    |
| 2288x1287          | 1        | 0.6%    |
| 1920x540           | 1        | 0.6%    |
| Unknown            | 1        | 0.6%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 23       | 12.78%  |
| 18      | 23       | 12.78%  |
| 23      | 18       | 10%     |
| 24      | 15       | 8.33%   |
| Unknown | 15       | 8.33%   |
| 20      | 14       | 7.78%   |
| 17      | 14       | 7.78%   |
| 19      | 13       | 7.22%   |
| 27      | 12       | 6.67%   |
| 15      | 6        | 3.33%   |
| 72      | 4        | 2.22%   |
| 32      | 4        | 2.22%   |
| 31      | 4        | 2.22%   |
| 34      | 3        | 1.67%   |
| 22      | 3        | 1.67%   |
| 54      | 2        | 1.11%   |
| 52      | 2        | 1.11%   |
| 142     | 1        | 0.56%   |
| 58      | 1        | 0.56%   |
| 50      | 1        | 0.56%   |
| 40      | 1        | 0.56%   |
| 39      | 1        | 0.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 68       | 39.31%  |
| 501-600        | 42       | 24.28%  |
| 301-350        | 20       | 11.56%  |
| Unknown        | 15       | 8.67%   |
| 701-800        | 7        | 4.05%   |
| 1001-1500      | 6        | 3.47%   |
| 601-700        | 4        | 2.31%   |
| 351-400        | 4        | 2.31%   |
| 1501-2000      | 4        | 2.31%   |
| 801-900        | 2        | 1.16%   |
| More than 2000 | 1        | 0.58%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 112      | 67.47%  |
| 5/4     | 17       | 10.24%  |
| Unknown | 15       | 9.04%   |
| 16/10   | 14       | 8.43%   |
| 21/9    | 3        | 1.81%   |
| 6/5     | 2        | 1.2%    |
| 4/3     | 2        | 1.2%    |
| 1.00    | 1        | 0.6%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 42       | 24.28%  |
| 151-200        | 36       | 20.81%  |
| 141-150        | 35       | 20.23%  |
| Unknown        | 15       | 8.67%   |
| 301-350        | 12       | 6.94%   |
| More than 1000 | 11       | 6.36%   |
| 351-500        | 11       | 6.36%   |
| 101-110        | 5        | 2.89%   |
| 251-300        | 3        | 1.73%   |
| 501-1000       | 2        | 1.16%   |
| 91-100         | 1        | 0.58%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 100      | 60.24%  |
| 101-120 | 38       | 22.89%  |
| Unknown | 15       | 9.04%   |
| 1-50    | 12       | 7.23%   |
| 161-240 | 1        | 0.6%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 136      | 77.27%  |
| 2     | 28       | 15.91%  |
| 0     | 12       | 6.82%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 129      | 53.53%  |
| Intel                                 | 40       | 16.6%   |
| Ralink Technology                     | 16       | 6.64%   |
| Qualcomm Atheros                      | 13       | 5.39%   |
| TP-Link                               | 8        | 3.32%   |
| Nvidia                                | 6        | 2.49%   |
| Samsung Electronics                   | 4        | 1.66%   |
| JMicron Technology                    | 3        | 1.24%   |
| Huawei Technologies                   | 3        | 1.24%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3        | 1.24%   |
| Xiaomi                                | 2        | 0.83%   |
| OPPO Electronics                      | 2        | 0.83%   |
| D-Link                                | 2        | 0.83%   |
| Broadcom                              | 2        | 0.83%   |
| Tenda                                 | 1        | 0.41%   |
| Sundance Technology Inc / IC Plus     | 1        | 0.41%   |
| Ralink                                | 1        | 0.41%   |
| Qualcomm Atheros Communications       | 1        | 0.41%   |
| Qualcomm                              | 1        | 0.41%   |
| ICS Advent                            | 1        | 0.41%   |
| D-Link System                         | 1        | 0.41%   |
| Broadcom Limited                      | 1        | 0.41%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                                  | Desktops | Percent |
|--------------------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                                      | 113      | 41.09%  |
| Realtek RTL8125 2.5GbE Controller                                                                      | 8        | 2.91%   |
| Intel Wi-Fi 6 AX200                                                                                    | 8        | 2.91%   |
| Realtek 802.11ac NIC                                                                                   | 7        | 2.55%   |
| Ralink MT7601U Wireless Adapter                                                                        | 7        | 2.55%   |
| Nvidia MCP61 Ethernet                                                                                  | 6        | 2.18%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                                  | 5        | 1.82%   |
| Intel I211 Gigabit Network Connection                                                                  | 5        | 1.82%   |
| Intel Ethernet Controller I225-V                                                                       | 5        | 1.82%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                                  | 4        | 1.45%   |
| Ralink RT5370 Wireless Adapter                                                                         | 4        | 1.45%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                            | 3        | 1.09%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                                     | 3        | 1.09%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                                  | 3        | 1.09%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                                                    | 3        | 1.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                                       | 3        | 1.09%   |
| Intel 82579V Gigabit Network Connection                                                                | 3        | 1.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                                  | 3        | 1.09%   |
| 802.11g Adapter [Linksys WUSB54GC v3] WUSB600N v1 Dual-Band Wireless-N Network Adapter [Ralink RT2870] | 3        | 1.09%   |
| Samsung E2530 Phone (Samsung Kies mode)                                                                | 2        | 0.73%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                                    | 2        | 0.73%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                                      | 2        | 0.73%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                                       | 2        | 0.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                         | 2        | 0.73%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                                          | 2        | 0.73%   |
| OPPO KALAMA-MTP_CID:0437_SN:AEEEF597                                                                   | 2        | 0.73%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                                 | 2        | 0.73%   |
| Intel Ethernet Connection I217-V                                                                       | 2        | 0.73%   |
| Intel Ethernet Connection (2) I219-V                                                                   | 2        | 0.73%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                                       | 2        | 0.73%   |
| Intel 82567LM-3 Gigabit Network Connection                                                             | 2        | 0.73%   |
| Huawei ATU-L21                                                                                         | 2        | 0.73%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                                         | 1        | 0.36%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                                                   | 1        | 0.36%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                           | 1        | 0.36%   |
| TP-Link Archer T4U ver.3                                                                               | 1        | 0.36%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                                    | 1        | 0.36%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                             | 1        | 0.36%   |
| TP-Link 802.11ac WLAN Adapter                                                                          | 1        | 0.36%   |
| Tenda U12                                                                                              | 1        | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 22       | 26.83%  |
| Intel                                 | 21       | 25.61%  |
| Ralink Technology                     | 16       | 19.51%  |
| TP-Link                               | 8        | 9.76%   |
| Qualcomm Atheros                      | 5        | 6.1%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3        | 3.66%   |
| D-Link                                | 2        | 2.44%   |
| Tenda                                 | 1        | 1.22%   |
| Samsung Electronics                   | 1        | 1.22%   |
| Ralink                                | 1        | 1.22%   |
| Qualcomm Atheros Communications       | 1        | 1.22%   |
| Broadcom                              | 1        | 1.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                                  | Desktops | Percent |
|--------------------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                                    | 8        | 9.64%   |
| Realtek 802.11ac NIC                                                                                   | 7        | 8.43%   |
| Ralink MT7601U Wireless Adapter                                                                        | 7        | 8.43%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                                  | 4        | 4.82%   |
| Ralink RT5370 Wireless Adapter                                                                         | 4        | 4.82%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                            | 3        | 3.61%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                                     | 3        | 3.61%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                                  | 3        | 3.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                                       | 3        | 3.61%   |
| 802.11g Adapter [Linksys WUSB54GC v3] WUSB600N v1 Dual-Band Wireless-N Network Adapter [Ralink RT2870] | 3        | 3.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                                    | 2        | 2.41%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                                      | 2        | 2.41%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                                       | 2        | 2.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                         | 2        | 2.41%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                                 | 2        | 2.41%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                                       | 2        | 2.41%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                           | 1        | 1.2%    |
| TP-Link Archer T4U ver.3                                                                               | 1        | 1.2%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                                    | 1        | 1.2%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                             | 1        | 1.2%    |
| TP-Link 802.11ac WLAN Adapter                                                                          | 1        | 1.2%    |
| Tenda U12                                                                                              | 1        | 1.2%    |
| Samsung WIS09ABGN LinkStick Wireless LAN Adapter                                                       | 1        | 1.2%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                               | 1        | 1.2%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                             | 1        | 1.2%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                                 | 1        | 1.2%    |
| Realtek RTL8188EE Wireless Network Adapter                                                             | 1        | 1.2%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                                | 1        | 1.2%    |
| Realtek 802.11n WLAN Adapter                                                                           | 1        | 1.2%    |
| Ralink RT3072 Wireless Adapter                                                                         | 1        | 1.2%    |
| Ralink RT3062 Wireless 802.11n 2T/2R                                                                   | 1        | 1.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                             | 1        | 1.2%    |
| Qualcomm Atheros AR9271 802.11n                                                                        | 1        | 1.2%    |
| Intel Wireless-AC 9260                                                                                 | 1        | 1.2%    |
| Intel Wireless 7260                                                                                    | 1        | 1.2%    |
| Intel Wireless 3165                                                                                    | 1        | 1.2%    |
| Intel Tiger Lake PCH CNVi WiFi                                                                         | 1        | 1.2%    |
| Intel Comet Lake PCH CNVi WiFi                                                                         | 1        | 1.2%    |
| Intel Centrino Wireless-N 2230                                                                         | 1        | 1.2%    |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]                                   | 1        | 1.2%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 127      | 67.91%  |
| Intel                             | 29       | 15.51%  |
| Qualcomm Atheros                  | 9        | 4.81%   |
| Nvidia                            | 6        | 3.21%   |
| JMicron Technology                | 3        | 1.6%    |
| Xiaomi                            | 2        | 1.07%   |
| OPPO Electronics                  | 2        | 1.07%   |
| Huawei Technologies               | 2        | 1.07%   |
| Sundance Technology Inc / IC Plus | 1        | 0.53%   |
| Samsung Electronics               | 1        | 0.53%   |
| Qualcomm                          | 1        | 0.53%   |
| ICS Advent                        | 1        | 0.53%   |
| D-Link System                     | 1        | 0.53%   |
| Broadcom Limited                  | 1        | 0.53%   |
| Broadcom                          | 1        | 0.53%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 113      | 59.79%  |
| Realtek RTL8125 2.5GbE Controller                                          | 8        | 4.23%   |
| Nvidia MCP61 Ethernet                                                      | 6        | 3.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 5        | 2.65%   |
| Intel I211 Gigabit Network Connection                                      | 5        | 2.65%   |
| Intel Ethernet Controller I225-V                                           | 5        | 2.65%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                        | 3        | 1.59%   |
| Intel 82579V Gigabit Network Connection                                    | 3        | 1.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 3        | 1.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 2        | 1.06%   |
| OPPO KALAMA-MTP_CID:0437_SN:AEEEF597                                       | 2        | 1.06%   |
| Intel Ethernet Connection I217-V                                           | 2        | 1.06%   |
| Intel Ethernet Connection (2) I219-V                                       | 2        | 1.06%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 2        | 1.06%   |
| Huawei ATU-L21                                                             | 2        | 1.06%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 1        | 0.53%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 1        | 0.53%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.53%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 1        | 0.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 1        | 0.53%   |
| Qualcomm Nokia XR20                                                        | 1        | 0.53%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 1        | 0.53%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 1        | 0.53%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                  | 1        | 0.53%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 1        | 0.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 1        | 0.53%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 1        | 0.53%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 1        | 0.53%   |
| Intel PRO/100 VM Network Connection                                        | 1        | 0.53%   |
| Intel I210 Gigabit Network Connection                                      | 1        | 0.53%   |
| Intel Ethernet Connection I217-LM                                          | 1        | 0.53%   |
| Intel Ethernet Connection (2) I219-LM                                      | 1        | 0.53%   |
| Intel Ethernet Connection (2) I218-V                                       | 1        | 0.53%   |
| Intel Ethernet Connection (2) I218-LM                                      | 1        | 0.53%   |
| Intel Ethernet Connection (10) I219-V                                      | 1        | 0.53%   |
| Intel 82574L Gigabit Network Connection                                    | 1        | 0.53%   |
| Intel 82566DM Gigabit Network Connection                                   | 1        | 0.53%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                    | 1        | 0.53%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                            | 1        | 0.53%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                            | 1        | 0.53%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 171      | 68.67%  |
| WiFi     | 75       | 30.12%  |
| Modem    | 3        | 1.2%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 139      | 75.14%  |
| WiFi     | 46       | 24.86%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 135      | 78.03%  |
| 2     | 29       | 16.76%  |
| 3     | 8        | 4.62%   |
| 0     | 1        | 0.58%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 163      | 92.61%  |
| Yes  | 13       | 7.39%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 20       | 42.55%  |
| Cambridge Silicon Radio    | 15       | 31.91%  |
| Realtek Semiconductor      | 5        | 10.64%  |
| Broadcom                   | 4        | 8.51%   |
| Lite-On Technology         | 1        | 2.13%   |
| Integrated System Solution | 1        | 2.13%   |
| IMC Networks               | 1        | 2.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 15       | 31.91%  |
| Intel AX200 Bluetooth                                 | 7        | 14.89%  |
| Realtek Bluetooth Radio                               | 5        | 10.64%  |
| Intel AX201 Bluetooth                                 | 4        | 8.51%   |
| Intel Wireless-AC 3168 Bluetooth                      | 3        | 6.38%   |
| Intel Bluetooth wireless interface                    | 2        | 4.26%   |
| Intel AX210 Bluetooth                                 | 2        | 4.26%   |
| Broadcom BCM2035 Bluetooth                            | 2        | 4.26%   |
| Lite-On Bluetooth Device                              | 1        | 2.13%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1        | 2.13%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1        | 2.13%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 2.13%   |
| IMC Networks Bluetooth Device                         | 1        | 2.13%   |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 1        | 2.13%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1        | 2.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 93       | 33.21%  |
| AMD                         | 82       | 29.29%  |
| Nvidia                      | 68       | 24.29%  |
| C-Media Electronics         | 7        | 2.5%    |
| Generalplus Technology      | 4        | 1.43%   |
| Kingston Technology         | 3        | 1.07%   |
| DCMT Technology             | 3        | 1.07%   |
| SteelSeries ApS             | 2        | 0.71%   |
| Razer USA                   | 2        | 0.71%   |
| Logitech                    | 2        | 0.71%   |
| GN Netcom                   | 2        | 0.71%   |
| Giga-Byte Technology        | 2        | 0.71%   |
| ZOOM                        | 1        | 0.36%   |
| XMOS                        | 1        | 0.36%   |
| FiiO Electronics Technology | 1        | 0.36%   |
| FIFINE 683 Microphone       | 1        | 0.36%   |
| Elgato Systems              | 1        | 0.36%   |
| Corsair                     | 1        | 0.36%   |
| Cooler Master               | 1        | 0.36%   |
| ASUSTek Computer            | 1        | 0.36%   |
| Arturia                     | 1        | 0.36%   |
| AKAI Professional M.I.      | 1        | 0.36%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD FCH Azalia Controller                                                         | 21       | 6.09%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 17       | 4.93%   |
| AMD Family 17h/19h HD Audio Controller                                            | 16       | 4.64%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 13       | 3.77%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 13       | 3.77%   |
| AMD Starship/Matisse HD Audio Controller                                          | 13       | 3.77%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 12       | 3.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 11       | 3.19%   |
| Nvidia GF108 High Definition Audio Controller                                     | 10       | 2.9%    |
| Intel 200 Series PCH HD Audio                                                     | 10       | 2.9%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 10       | 2.9%    |
| Nvidia MCP61 High Definition Audio                                                | 8        | 2.32%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 8        | 2.32%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 8        | 2.32%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 7        | 2.03%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 7        | 2.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 7        | 2.03%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 7        | 2.03%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 6        | 1.74%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 6        | 1.74%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 6        | 1.74%   |
| Nvidia GA102 High Definition Audio Controller                                     | 5        | 1.45%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 5        | 1.45%   |
| AMD Trinity HDMI Audio Controller                                                 | 5        | 1.45%   |
| AMD Kaveri HDMI/DP Audio Controller                                               | 5        | 1.45%   |
| Nvidia TU116 High Definition Audio Controller                                     | 4        | 1.16%   |
| Nvidia GP104 High Definition Audio Controller                                     | 4        | 1.16%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 4        | 1.16%   |
| Generalplus Technology USB Audio Device                                           | 4        | 1.16%   |
| Nvidia TU106 High Definition Audio Controller                                     | 3        | 0.87%   |
| Nvidia High Definition Audio Controller                                           | 3        | 0.87%   |
| Nvidia GP108 High Definition Audio Controller                                     | 3        | 0.87%   |
| Nvidia GP106 High Definition Audio Controller                                     | 3        | 0.87%   |
| Nvidia GM204 High Definition Audio Controller                                     | 3        | 0.87%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3        | 0.87%   |
| Intel Smart Sound Technology (SST) Audio Controller                               | 3        | 0.87%   |
| DCMT Technology USB Condenser Microphone                                          | 3        | 0.87%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3        | 0.87%   |
| Kingston Technology HyperX 7.1 Audio                                              | 2        | 0.58%   |
| Intel Cannon Lake PCH cAVS                                                        | 2        | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 20       | 26.32%  |
| Unknown             | 9        | 11.84%  |
| Team                | 8        | 10.53%  |
| G.Skill             | 7        | 9.21%   |
| Corsair             | 6        | 7.89%   |
| SK hynix            | 4        | 5.26%   |
| Samsung Electronics | 4        | 5.26%   |
| PNY                 | 2        | 2.63%   |
| Patriot             | 2        | 2.63%   |
| Kingmax             | 2        | 2.63%   |
| Crucial             | 2        | 2.63%   |
| Unknown             | 2        | 2.63%   |
| Uroad               | 1        | 1.32%   |
| Unifosa             | 1        | 1.32%   |
| Transcend           | 1        | 1.32%   |
| Silicon Power       | 1        | 1.32%   |
| Nanya Technology    | 1        | 1.32%   |
| Mitsubishi          | 1        | 1.32%   |
| Carry               | 1        | 1.32%   |
| A-DATA Technology   | 1        | 1.32%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s          | 4        | 5%      |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s           | 3        | 3.75%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s          | 3        | 3.75%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s           | 2        | 2.5%    |
| Patriot RAM PSD34G160081 4GB DIMM DDR3 1600MT/s              | 2        | 2.5%    |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s         | 2        | 2.5%    |
| Kingston RAM KF2666C16D4/8G 8GB DIMM DDR4 2667MT/s           | 2        | 2.5%    |
| Corsair RAM CMT128GX4M4C3200C16 32GB DIMM DDR4 3200MT/s      | 2        | 2.5%    |
| Corsair RAM CML8GX3M2A1600C9 4096MB DIMM DDR3 1867MT/s       | 2        | 2.5%    |
| Unknown                                                      | 2        | 2.5%    |
| Uroad RAM WJD8G4M16P12800 8192MB DIMM DDR3 1600MT/s          | 1        | 1.25%   |
| Unknown RAM Module 8192MB DIMM                               | 1        | 1.25%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                  | 1        | 1.25%   |
| Unknown RAM Module 4GB DIMM DDR4 2133MT/s                    | 1        | 1.25%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 1        | 1.25%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                         | 1        | 1.25%   |
| Unknown RAM Module 4096MB DIMM DDR2                          | 1        | 1.25%   |
| Unknown RAM Module 1GB DIMM DDR2                             | 1        | 1.25%   |
| Unknown RAM Module 16384MB DIMM DDR4 2666MT/s                | 1        | 1.25%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                  | 1        | 1.25%   |
| Unknown RAM Module 1024MB DIMM DDR2                          | 1        | 1.25%   |
| Unknown RAM KZ24UE5116HAR8 8192MB DIMM DDR4 2400MT/s         | 1        | 1.25%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s            | 1        | 1.25%   |
| Transcend RAM TS2GLH64V4B 16384MB DIMM DDR4 2400MT/s         | 1        | 1.25%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s           | 1        | 1.25%   |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 2400MT/s           | 1        | 1.25%   |
| Team RAM TEAMGROUP-UD3-1600 4GB DIMM DDR3 1600MT/s           | 1        | 1.25%   |
| SK hynix RAM Module 8192MB DIMM DDR4 2133MT/s                | 1        | 1.25%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1648MT/s         | 1        | 1.25%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s         | 1        | 1.25%   |
| SK hynix RAM HMA81GR7MFR8N-UH 8GB DIMM DDR4 2400MT/s         | 1        | 1.25%   |
| SK hynix RAM HMA81GR7AFR8N-UH 8GB DIMM DDR4 2400MT/s         | 1        | 1.25%   |
| Silicon Power RAM SP008GBLFU266B02 8192MB DIMM DDR4 2400MT/s | 1        | 1.25%   |
| Samsung RAM Module 4096MB DIMM DDR4 2133MT/s                 | 1        | 1.25%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s          | 1        | 1.25%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s          | 1        | 1.25%   |
| Samsung RAM M3 78T2863QZS-CF7 1GB DIMM DDR2 800MT/s          | 1        | 1.25%   |
| PNY RAM 8GBF1X08QFHH38-135-K 8GB DIMM DDR4 3600MT/s          | 1        | 1.25%   |
| PNY RAM 16GF2X08QFHH36-135-K 16GB DIMM DDR4 3200MT/s         | 1        | 1.25%   |
| Nanya RAM NT4GC64B8HG0NF-CG 4GB DIMM DDR3 1333MT/s           | 1        | 1.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 39       | 57.35%  |
| DDR3    | 23       | 33.82%  |
| DDR2    | 3        | 4.41%   |
| Unknown | 2        | 2.94%   |
| SDRAM   | 1        | 1.47%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 68       | 98.55%  |
| SODIMM | 1        | 1.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 33       | 44.59%  |
| 4096  | 19       | 25.68%  |
| 16384 | 9        | 12.16%  |
| 32768 | 8        | 10.81%  |
| 1024  | 3        | 4.05%   |
| 2048  | 2        | 2.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 13       | 18.31%  |
| 3200    | 8        | 11.27%  |
| 2133    | 8        | 11.27%  |
| 3600    | 6        | 8.45%   |
| 2400    | 6        | 8.45%   |
| 2667    | 4        | 5.63%   |
| 3866    | 3        | 4.23%   |
| 3800    | 3        | 4.23%   |
| 3733    | 3        | 4.23%   |
| 1333    | 3        | 4.23%   |
| Unknown | 3        | 4.23%   |
| 2666    | 2        | 2.82%   |
| 1867    | 2        | 2.82%   |
| 1800    | 2        | 2.82%   |
| 3500    | 1        | 1.41%   |
| 3466    | 1        | 1.41%   |
| 1648    | 1        | 1.41%   |
| 800     | 1        | 1.41%   |
| 667     | 1        | 1.41%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Seiko Epson        | 3        | 50%     |
| Canon              | 2        | 33.33%  |
| Brother Industries | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Desktops | Percent |
|---------------------------|----------|---------|
| Seiko Epson L120 Series   | 2        | 33.33%  |
| Seiko Epson L3110 Series  | 1        | 16.67%  |
| Canon PIXMA MG2500 Series | 1        | 16.67%  |
| Canon G2010 series        | 1        | 16.67%  |
| Brother DCP-T700W         | 1        | 16.67%  |

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


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Microdia                    | 7        | 15.22%  |
| Logitech                    | 6        | 13.04%  |
| Z-Star Microelectronics     | 4        | 8.7%    |
| Jieli Technology            | 4        | 8.7%    |
| A4Tech                      | 4        | 8.7%    |
| Realtek Semiconductor       | 3        | 6.52%   |
| Pixart Imaging              | 3        | 6.52%   |
| Cubeternet                  | 3        | 6.52%   |
| Samsung Electronics         | 2        | 4.35%   |
| Razer USA                   | 2        | 4.35%   |
| Generalplus Technology      | 2        | 4.35%   |
| Silicon Motion              | 1        | 2.17%   |
| OPPO Electronics            | 1        | 2.17%   |
| KYE Systems (Mouse Systems) | 1        | 2.17%   |
| Aveo Technology             | 1        | 2.17%   |
| Apple                       | 1        | 2.17%   |
| Alcor Micro                 | 1        | 2.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Jieli USB PHY 2.0                                                   | 4        | 8.7%    |
| Z-Star Venus USB2.0 Camera                                          | 3        | 6.52%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                                | 3        | 6.52%   |
| Microdia Integrated Camera                                          | 3        | 6.52%   |
| Logitech Webcam C270                                                | 3        | 6.52%   |
| A4Tech FHD 1080P PC Camera                                          | 3        | 6.52%   |
| Razer USA Gaming Webcam [Kiyo]                                      | 2        | 4.35%   |
| Microdia Sonix USB 2.0 Camera                                       | 2        | 4.35%   |
| Logitech HD Webcam C910                                             | 2        | 4.35%   |
| Z-Star A4 TECH USB2.0 PC Camera J                                   | 1        | 2.17%   |
| Silicon Motion 300k Pixel Camera                                    | 1        | 2.17%   |
| Samsung USB2.0 UVC HQ WebCam                                        | 1        | 2.17%   |
| Samsung Galaxy series, misc. (MTP mode)                             | 1        | 2.17%   |
| Realtek Laptop_Integrated_Webcam_FHD                                | 1        | 2.17%   |
| Realtek Front Camera                                                | 1        | 2.17%   |
| Realtek BRI-S90AF                                                   | 1        | 2.17%   |
| OPPO SM4250-QRD _SN:C0CE5FDA                                        | 1        | 2.17%   |
| Microdia USB 2.0 Camera                                             | 1        | 2.17%   |
| Microdia rapoo camera                                               | 1        | 2.17%   |
| Logitech HD Webcam B910                                             | 1        | 2.17%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera                          | 1        | 2.17%   |
| Generalplus WEB CAM                                                 | 1        | 2.17%   |
| Generalplus 808 Camera                                              | 1        | 2.17%   |
| Cubeternet USB2.0 Camera                                            | 1        | 2.17%   |
| Cubeternet GL-UPC822 UVC WebCam                                     | 1        | 2.17%   |
| Cubeternet EtronTech CMOS based eSP570 WebCam [Onyx Titanium TC101] | 1        | 2.17%   |
| Aveo UVC camera (Bresser microscope)                                | 1        | 2.17%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                     | 1        | 2.17%   |
| Alcor Micro SHUNCCM2MP                                              | 1        | 2.17%   |
| A4Tech PC Camera                                                    | 1        | 2.17%   |

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
| 0     | 149      | 84.18%  |
| 1     | 24       | 13.56%  |
| 2     | 4        | 2.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 12       | 40%     |
| Graphics card            | 10       | 33.33%  |
| Unassigned class         | 1        | 3.33%   |
| Storage/raid             | 1        | 3.33%   |
| Sound                    | 1        | 3.33%   |
| Network                  | 1        | 3.33%   |
| Net/ethernet             | 1        | 3.33%   |
| Communication controller | 1        | 3.33%   |
| Chipcard                 | 1        | 3.33%   |
| Camera                   | 1        | 3.33%   |

