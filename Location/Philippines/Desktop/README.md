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

Total: 252

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04       | 14       | 8.75%   |
| Pop!_OS 20.04      | 9        | 5.63%   |
| Ubuntu 18.04       | 7        | 4.38%   |
| BlackPanther 18.1  | 7        | 4.38%   |
| Ubuntu 22.04       | 6        | 3.75%   |
| Zorin 15           | 5        | 3.13%   |
| KDE neon 20.04     | 5        | 3.13%   |
| Fedora 36          | 5        | 3.13%   |
| Endless 3.7.7      | 5        | 3.13%   |
| Pop!_OS 21.04      | 4        | 2.5%    |
| Pop!_OS 20.10      | 4        | 2.5%    |
| Endless 3.7.6      | 4        | 2.5%    |
| Ubuntu Unity 18.04 | 3        | 1.88%   |
| Pop!_OS 22.04      | 3        | 1.88%   |
| OpenMandriva 4.3   | 3        | 1.88%   |
| OpenMandriva 4.2   | 3        | 1.88%   |
| Manjaro            | 3        | 1.88%   |
| Linux Mint 20.2    | 3        | 1.88%   |
| Linux Mint 20.1    | 3        | 1.88%   |
| Fedora 32          | 3        | 1.88%   |
| BlackPanther 16.2  | 3        | 1.88%   |
| Ubuntu 21.10       | 2        | 1.25%   |
| Linux Mint 19.3    | 2        | 1.25%   |
| Kubuntu 22.04      | 2        | 1.25%   |
| Kali 2021.4        | 2        | 1.25%   |
| Fedora 33          | 2        | 1.25%   |
| Endless 3.9.4      | 2        | 1.25%   |
| Endless 3.3.20     | 2        | 1.25%   |
| Debian 10          | 2        | 1.25%   |
| Zorin 16           | 1        | 0.63%   |
| Xubuntu 20.04      | 1        | 0.63%   |
| Xubuntu 19.10      | 1        | 0.63%   |
| Ubuntu MATE 18.04  | 1        | 0.63%   |
| Ubuntu 19.10       | 1        | 0.63%   |
| Solus 4.3          | 1        | 0.63%   |
| ROSA R11           | 1        | 0.63%   |
| ROSA R10           | 1        | 0.63%   |
| Reborn OS          | 1        | 0.63%   |
| Peppermint 10      | 1        | 0.63%   |
| Parrot 5.1         | 1        | 0.63%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 29       | 18.95%  |
| Pop!_OS      | 20       | 13.07%  |
| Endless      | 16       | 10.46%  |
| Fedora       | 12       | 7.84%   |
| Linux Mint   | 11       | 7.19%   |
| BlackPanther | 8        | 5.23%   |
| Manjaro      | 7        | 4.58%   |
| Zorin        | 6        | 3.92%   |
| OpenMandriva | 6        | 3.92%   |
| KDE neon     | 5        | 3.27%   |
| Kubuntu      | 4        | 2.61%   |
| Ubuntu Unity | 3        | 1.96%   |
| Kali         | 3        | 1.96%   |
| Debian       | 3        | 1.96%   |
| Xubuntu      | 2        | 1.31%   |
| ROSA         | 2        | 1.31%   |
| Elementary   | 2        | 1.31%   |
| Ubuntu MATE  | 1        | 0.65%   |
| Solus        | 1        | 0.65%   |
| Reborn OS    | 1        | 0.65%   |
| Peppermint   | 1        | 0.65%   |
| Parrot       | 1        | 0.65%   |
| MX           | 1        | 0.65%   |
| LMDE         | 1        | 0.65%   |
| Hash Linux   | 1        | 0.65%   |
| Gentoo       | 1        | 0.65%   |
| Garuda Linux | 1        | 0.65%   |
| BunsenLabs   | 1        | 0.65%   |
| BuildRoot    | 1        | 0.65%   |
| ArcoLinux    | 1        | 0.65%   |
| Arch         | 1        | 0.65%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 4.18.16-desktop-1bP      | 7        | 4.09%   |
| 5.8.0-7630-generic       | 6        | 3.51%   |
| 5.3.0-28-generic         | 6        | 3.51%   |
| 5.3.0-23-generic         | 4        | 2.34%   |
| 5.4.0-7634-generic       | 3        | 1.75%   |
| 5.4.0-58-generic         | 3        | 1.75%   |
| 5.16.7-desktop-1omv4003  | 3        | 1.75%   |
| 5.10.14-desktop-1omv4002 | 3        | 1.75%   |
| 4.9.20-desktop-pae-1bP   | 3        | 1.75%   |
| 5.8.0-36-generic         | 2        | 1.17%   |
| 5.8.0-14-generic         | 2        | 1.17%   |
| 5.4.0-80-generic         | 2        | 1.17%   |
| 5.4.0-73-generic         | 2        | 1.17%   |
| 5.4.0-65-generic         | 2        | 1.17%   |
| 5.3.0-46-generic         | 2        | 1.17%   |
| 5.15.0-48-generic        | 2        | 1.17%   |
| 5.15.0-41-generic        | 2        | 1.17%   |
| 5.15.0-27-generic        | 2        | 1.17%   |
| 5.13.0-7620-generic      | 2        | 1.17%   |
| 5.13.0-35-generic        | 2        | 1.17%   |
| 5.13.0-30-generic        | 2        | 1.17%   |
| 5.11.0-35-generic        | 2        | 1.17%   |
| 4.18.0-18-generic        | 2        | 1.17%   |
| 4.13.0-32-generic        | 2        | 1.17%   |
| 6.0.2-76060002-generic   | 1        | 0.58%   |
| 6.0.0-2parrot1-amd64     | 1        | 0.58%   |
| 5.9.14-100.fc32.x86_64   | 1        | 0.58%   |
| 5.9.11-zen2-1-zen        | 1        | 0.58%   |
| 5.8.8-200.fc32.x86_64    | 1        | 0.58%   |
| 5.8.4-200.fc32.x86_64    | 1        | 0.58%   |
| 5.8.18-300.fc33.x86_64   | 1        | 0.58%   |
| 5.8.0-7642-generic       | 1        | 0.58%   |
| 5.8.0-7625-generic       | 1        | 0.58%   |
| 5.8.0-55-generic         | 1        | 0.58%   |
| 5.8.0-41-generic         | 1        | 0.58%   |
| 5.8.0-40-generic         | 1        | 0.58%   |
| 5.7.11-200.fc32.x86_64   | 1        | 0.58%   |
| 5.4.70                   | 1        | 0.58%   |
| 5.4.0-99-generic         | 1        | 0.58%   |
| 5.4.0-81-generic         | 1        | 0.58%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 23       | 14.11%  |
| 5.8.0   | 15       | 9.2%    |
| 5.3.0   | 15       | 9.2%    |
| 5.15.0  | 13       | 7.98%   |
| 5.13.0  | 10       | 6.13%   |
| 4.15.0  | 8        | 4.91%   |
| 5.11.0  | 7        | 4.29%   |
| 4.18.16 | 7        | 4.29%   |
| 5.17.5  | 3        | 1.84%   |
| 5.16.7  | 3        | 1.84%   |
| 5.10.14 | 3        | 1.84%   |
| 5.0.0   | 3        | 1.84%   |
| 4.9.20  | 3        | 1.84%   |
| 4.19.0  | 3        | 1.84%   |
| 4.18.0  | 3        | 1.84%   |
| 5.16.0  | 2        | 1.23%   |
| 5.10.0  | 2        | 1.23%   |
| 4.13.0  | 2        | 1.23%   |
| 6.0.2   | 1        | 0.61%   |
| 6.0.0   | 1        | 0.61%   |
| 5.9.14  | 1        | 0.61%   |
| 5.9.11  | 1        | 0.61%   |
| 5.8.8   | 1        | 0.61%   |
| 5.8.4   | 1        | 0.61%   |
| 5.8.18  | 1        | 0.61%   |
| 5.7.11  | 1        | 0.61%   |
| 5.4.70  | 1        | 0.61%   |
| 5.19.7  | 1        | 0.61%   |
| 5.19.6  | 1        | 0.61%   |
| 5.19.16 | 1        | 0.61%   |
| 5.19.13 | 1        | 0.61%   |
| 5.19.11 | 1        | 0.61%   |
| 5.19.1  | 1        | 0.61%   |
| 5.19.0  | 1        | 0.61%   |
| 5.18.13 | 1        | 0.61%   |
| 5.18.10 | 1        | 0.61%   |
| 5.15.5  | 1        | 0.61%   |
| 5.15.49 | 1        | 0.61%   |
| 5.15.41 | 1        | 0.61%   |
| 5.15.32 | 1        | 0.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 24       | 14.91%  |
| 5.8     | 18       | 11.18%  |
| 5.15    | 18       | 11.18%  |
| 5.3     | 15       | 9.32%   |
| 5.10    | 12       | 7.45%   |
| 5.13    | 11       | 6.83%   |
| 4.18    | 10       | 6.21%   |
| 5.11    | 8        | 4.97%   |
| 4.15    | 8        | 4.97%   |
| 5.19    | 7        | 4.35%   |
| 5.16    | 5        | 3.11%   |
| 4.9     | 5        | 3.11%   |
| 5.17    | 3        | 1.86%   |
| 5.0     | 3        | 1.86%   |
| 4.19    | 3        | 1.86%   |
| 6.0     | 2        | 1.24%   |
| 5.9     | 2        | 1.24%   |
| 5.18    | 2        | 1.24%   |
| 4.13    | 2        | 1.24%   |
| 5.7     | 1        | 0.62%   |
| 5.14    | 1        | 0.62%   |
| 5.1     | 1        | 0.62%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 144      | 96%     |
| i686   | 5        | 3.33%   |
| armv7l | 1        | 0.67%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 72       | 46.75%  |
| KDE5            | 35       | 22.73%  |
| XFCE            | 11       | 7.14%   |
| Unknown         | 11       | 7.14%   |
| X-Cinnamon      | 8        | 5.19%   |
| MATE            | 4        | 2.6%    |
| KDE             | 3        | 1.95%   |
| Unity           | 2        | 1.3%    |
| LXQt            | 2        | 1.3%    |
| Pantheon        | 1        | 0.65%   |
| openbox         | 1        | 0.65%   |
| LXDE            | 1        | 0.65%   |
| GNOME Flashback | 1        | 0.65%   |
| Budgie          | 1        | 0.65%   |
| awesome         | 1        | 0.65%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 131      | 87.33%  |
| Wayland | 9        | 6%      |
| Tty     | 5        | 3.33%   |
| Unknown | 5        | 3.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 93       | 60.78%  |
| SDDM    | 28       | 18.3%   |
| GDM3    | 12       | 7.84%   |
| LightDM | 11       | 7.19%   |
| GDM     | 7        | 4.58%   |
| TDM     | 2        | 1.31%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_PH   | 73       | 48.34%  |
| en_US   | 54       | 35.76%  |
| Unknown | 19       | 12.58%  |
| C       | 3        | 1.99%   |
| en_HK   | 1        | 0.66%   |
| de_DE   | 1        | 0.66%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 91       | 60.26%  |
| EFI  | 60       | 39.74%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 122      | 79.22%  |
| Btrfs   | 15       | 9.74%   |
| Overlay | 12       | 7.79%   |
| Unknown | 4        | 2.6%    |
| Xfs     | 1        | 0.65%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 98       | 63.64%  |
| GPT     | 37       | 24.03%  |
| MBR     | 19       | 12.34%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 127      | 81.41%  |
| Yes       | 29       | 18.59%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 112      | 71.79%  |
| Yes       | 44       | 28.21%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 39       | 26.35%  |
| MSI                 | 29       | 19.59%  |
| ASUSTek Computer    | 27       | 18.24%  |
| ASRock              | 10       | 6.76%   |
| Hewlett-Packard     | 9        | 6.08%   |
| Dell                | 6        | 4.05%   |
| Foxconn             | 5        | 3.38%   |
| Biostar             | 5        | 3.38%   |
| ECS                 | 4        | 2.7%    |
| EMAXX TECHNOLOGY    | 3        | 2.03%   |
| Pegatron            | 2        | 1.35%   |
| YANYU               | 1        | 0.68%   |
| TriGem Computer     | 1        | 0.68%   |
| QTQD                | 1        | 0.68%   |
| NEC Computers       | 1        | 0.68%   |
| Lenovo              | 1        | 0.68%   |
| JOOYON              | 1        | 0.68%   |
| AMD                 | 1        | 0.68%   |
| Acer                | 1        | 0.68%   |
| Unknown             | 1        | 0.68%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| MSI MS-7721                   | 4        | 2.7%    |
| MSI MS-7309                   | 4        | 2.7%    |
| Gigabyte F2A68HM-S1           | 4        | 2.7%    |
| Gigabyte A320M-S2H V2         | 4        | 2.7%    |
| ASUS All Series               | 4        | 2.7%    |
| Foxconn G31MX Series          | 3        | 2.03%   |
| ASUS P8H61-M LX3 PLUS R2.0    | 3        | 2.03%   |
| ASRock B450M Steel Legend     | 3        | 2.03%   |
| Pegatron IPMSB-H61            | 2        | 1.35%   |
| Gigabyte Z590 AORUS ULTRA     | 2        | 1.35%   |
| Foxconn 500B Microtower       | 2        | 1.35%   |
| ASUS PRIME B250M-K            | 2        | 1.35%   |
| ASUS EX-H310M-V3 R2.0         | 2        | 1.35%   |
| Unknown                       | 2        | 1.35%   |
| YANYU EPIC-C19                | 1        | 0.68%   |
| TriGem DreamSys               | 1        | 0.68%   |
| NEC Computers PC-MK36LBZCHEAM | 1        | 0.68%   |
| MSI MS-7D43                   | 1        | 0.68%   |
| MSI MS-7D23                   | 1        | 0.68%   |
| MSI MS-7D22                   | 1        | 0.68%   |
| MSI MS-7D18                   | 1        | 0.68%   |
| MSI MS-7D14                   | 1        | 0.68%   |
| MSI MS-7C94                   | 1        | 0.68%   |
| MSI MS-7C52                   | 1        | 0.68%   |
| MSI MS-7C02                   | 1        | 0.68%   |
| MSI MS-7B89                   | 1        | 0.68%   |
| MSI MS-7A57                   | 1        | 0.68%   |
| MSI MS-7A38                   | 1        | 0.68%   |
| MSI MS-7A36                   | 1        | 0.68%   |
| MSI MS-7996                   | 1        | 0.68%   |
| MSI MS-7978                   | 1        | 0.68%   |
| MSI MS-7918                   | 1        | 0.68%   |
| MSI MS-7914                   | 1        | 0.68%   |
| MSI MS-7817                   | 1        | 0.68%   |
| MSI AY702AA-A2K p6390d        | 1        | 0.68%   |
| MSI A55PV.AR3510D             | 1        | 0.68%   |
| MSI *NP                       | 1        | 0.68%   |
| MSI *MF                       | 1        | 0.68%   |
| Lenovo IdeaCentre Q190 10115  | 1        | 0.68%   |
| JOOYON IPM41-D3               | 1        | 0.68%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| Dell OptiPlex                 | 6        | 4.05%   |
| Gigabyte A320M-S2H            | 5        | 3.38%   |
| ASUS PRIME                    | 5        | 3.38%   |
| ASUS P8H61-M                  | 5        | 3.38%   |
| MSI MS-7721                   | 4        | 2.7%    |
| MSI MS-7309                   | 4        | 2.7%    |
| HP Compaq                     | 4        | 2.7%    |
| Gigabyte F2A68HM-S1           | 4        | 2.7%    |
| ASUS All                      | 4        | 2.7%    |
| HP ProDesk                    | 3        | 2.03%   |
| Gigabyte B450                 | 3        | 2.03%   |
| Foxconn G31MX                 | 3        | 2.03%   |
| ASRock B450M                  | 3        | 2.03%   |
| Pegatron IPMSB-H61            | 2        | 1.35%   |
| Gigabyte Z590                 | 2        | 1.35%   |
| Gigabyte X570                 | 2        | 1.35%   |
| Foxconn 500B                  | 2        | 1.35%   |
| ASUS TUF                      | 2        | 1.35%   |
| ASUS ROG                      | 2        | 1.35%   |
| ASUS EX-H310M-V3              | 2        | 1.35%   |
| Unknown                       | 2        | 1.35%   |
| YANYU EPIC-C19                | 1        | 0.68%   |
| TriGem DreamSys               | 1        | 0.68%   |
| NEC Computers PC-MK36LBZCHEAM | 1        | 0.68%   |
| MSI MS-7D43                   | 1        | 0.68%   |
| MSI MS-7D23                   | 1        | 0.68%   |
| MSI MS-7D22                   | 1        | 0.68%   |
| MSI MS-7D18                   | 1        | 0.68%   |
| MSI MS-7D14                   | 1        | 0.68%   |
| MSI MS-7C94                   | 1        | 0.68%   |
| MSI MS-7C52                   | 1        | 0.68%   |
| MSI MS-7C02                   | 1        | 0.68%   |
| MSI MS-7B89                   | 1        | 0.68%   |
| MSI MS-7A57                   | 1        | 0.68%   |
| MSI MS-7A38                   | 1        | 0.68%   |
| MSI MS-7A36                   | 1        | 0.68%   |
| MSI MS-7996                   | 1        | 0.68%   |
| MSI MS-7978                   | 1        | 0.68%   |
| MSI MS-7918                   | 1        | 0.68%   |
| MSI MS-7914                   | 1        | 0.68%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2014    | 17       | 11.49%  |
| 2018    | 14       | 9.46%   |
| 2017    | 13       | 8.78%   |
| 2012    | 13       | 8.78%   |
| 2015    | 12       | 8.11%   |
| 2013    | 12       | 8.11%   |
| 2010    | 12       | 8.11%   |
| 2019    | 10       | 6.76%   |
| 2021    | 9        | 6.08%   |
| 2020    | 8        | 5.41%   |
| 2009    | 8        | 5.41%   |
| 2011    | 6        | 4.05%   |
| 2016    | 4        | 2.7%    |
| 2007    | 4        | 2.7%    |
| 2006    | 3        | 2.03%   |
| 2008    | 2        | 1.35%   |
| Unknown | 1        | 0.68%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 148      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 143      | 96.62%  |
| Enabled  | 5        | 3.38%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 148      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 38       | 24.52%  |
| 3.01-4.0    | 31       | 20%     |
| 4.01-8.0    | 27       | 17.42%  |
| 16.01-24.0  | 26       | 16.77%  |
| 32.01-64.0  | 13       | 8.39%   |
| 1.01-2.0    | 7        | 4.52%   |
| 64.01-256.0 | 6        | 3.87%   |
| 2.01-3.0    | 5        | 3.23%   |
| 24.01-32.0  | 2        | 1.29%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 57       | 34.97%  |
| 2.01-3.0   | 37       | 22.7%   |
| 4.01-8.0   | 23       | 14.11%  |
| 0.51-1.0   | 16       | 9.82%   |
| 3.01-4.0   | 13       | 7.98%   |
| 8.01-16.0  | 9        | 5.52%   |
| 0.01-0.5   | 7        | 4.29%   |
| 24.01-32.0 | 1        | 0.61%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 73       | 46.2%   |
| 2      | 49       | 31.01%  |
| 4      | 13       | 8.23%   |
| 3      | 13       | 8.23%   |
| 5      | 6        | 3.8%    |
| 0      | 2        | 1.27%   |
| 13     | 1        | 0.63%   |
| 6      | 1        | 0.63%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 118      | 76.13%  |
| Yes       | 37       | 23.87%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 148      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 87       | 57.62%  |
| Yes       | 64       | 42.38%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 111      | 75%     |
| Yes       | 37       | 25%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Philippines | 148      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Quezon City       | 36       | 21.82%  |
| Davao City        | 11       | 6.67%   |
| Cagayan de Oro    | 10       | 6.06%   |
| Angeles City      | 7        | 4.24%   |
| San Miguel        | 6        | 3.64%   |
| Iligan City       | 6        | 3.64%   |
| Bacolod City      | 6        | 3.64%   |
| Cebu City         | 5        | 3.03%   |
| Santa Rosa        | 4        | 2.42%   |
| Paranaque City    | 4        | 2.42%   |
| Mandaluyong City  | 4        | 2.42%   |
| Makati City       | 4        | 2.42%   |
| Bacoor            | 4        | 2.42%   |
| Zamboanga City    | 3        | 1.82%   |
| Manila            | 3        | 1.82%   |
| Manajao           | 3        | 1.82%   |
| Lipa City         | 3        | 1.82%   |
| Imus              | 3        | 1.82%   |
| Pasig             | 2        | 1.21%   |
| Mandaue City      | 2        | 1.21%   |
| Magugpo Poblacion | 2        | 1.21%   |
| Dumaguete         | 2        | 1.21%   |
| Caloocan City     | 2        | 1.21%   |
| Antipolo City     | 2        | 1.21%   |
| Abaga             | 2        | 1.21%   |
| Tuguegarao City   | 1        | 0.61%   |
| Taytay            | 1        | 0.61%   |
| Tarlac City       | 1        | 0.61%   |
| Tanza             | 1        | 0.61%   |
| Taguig            | 1        | 0.61%   |
| Tagbilaran        | 1        | 0.61%   |
| Sibulan           | 1        | 0.61%   |
| San Leonardo      | 1        | 0.61%   |
| San Fernando City | 1        | 0.61%   |
| San Carlos City   | 1        | 0.61%   |
| San Carlos        | 1        | 0.61%   |
| Nagcarlan         | 1        | 0.61%   |
| Marikina City     | 1        | 0.61%   |
| Malolos           | 1        | 0.61%   |
| Lucena City       | 1        | 0.61%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| Seagate               | 57       | 84     | 22.35%  |
| WDC                   | 51       | 70     | 20%     |
| Toshiba               | 19       | 25     | 7.45%   |
| Samsung Electronics   | 17       | 26     | 6.67%   |
| Kingston              | 16       | 22     | 6.27%   |
| Hitachi               | 15       | 28     | 5.88%   |
| SanDisk               | 9        | 11     | 3.53%   |
| Lexar                 | 7        | 8      | 2.75%   |
| Transcend             | 5        | 5      | 1.96%   |
| Team                  | 5        | 7      | 1.96%   |
| Gigabyte Technology   | 5        | 6      | 1.96%   |
| Crucial               | 4        | 6      | 1.57%   |
| Unknown               | 3        | 4      | 1.18%   |
| HGST                  | 3        | 3      | 1.18%   |
| A-DATA Technology     | 3        | 3      | 1.18%   |
| XPG                   | 2        | 2      | 0.78%   |
| WALRAM                | 2        | 2      | 0.78%   |
| SK hynix              | 2        | 8      | 0.78%   |
| Phison                | 2        | 2      | 0.78%   |
| Intel                 | 2        | 3      | 0.78%   |
| Indilinx              | 2        | 2      | 0.78%   |
| HS-SSD-C100           | 2        | 2      | 0.78%   |
| Fujitsu               | 2        | 2      | 0.78%   |
| ZOTAC                 | 1        | 1      | 0.39%   |
| XrayDisk              | 1        | 1      | 0.39%   |
| Voyager               | 1        | 1      | 0.39%   |
| USB                   | 1        | 1      | 0.39%   |
| T-FORCE               | 1        | 1      | 0.39%   |
| SKIHOTAR              | 1        | 1      | 0.39%   |
| Realtek Semiconductor | 1        | 1      | 0.39%   |
| Ramsta                | 1        | 1      | 0.39%   |
| PNY                   | 1        | 1      | 0.39%   |
| Patriot               | 1        | 1      | 0.39%   |
| KingSpec              | 1        | 1      | 0.39%   |
| Kingmax               | 1        | 1      | 0.39%   |
| Kimtigo               | 1        | 2      | 0.39%   |
| HUAWEI                | 1        | 1      | 0.39%   |
| HS-SSD-E100           | 1        | 1      | 0.39%   |
| Hikvision             | 1        | 2      | 0.39%   |
| GLOWAY                | 1        | 1      | 0.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB   | 11       | 3.78%   |
| Seagate ST500DM002-1BD142 500GB  | 9        | 3.09%   |
| Toshiba DT01ACA050 500GB         | 7        | 2.41%   |
| WDC WD10EZEX-08WN4A0 1TB         | 5        | 1.72%   |
| Seagate ST4000DM004-2CV104 4TB   | 5        | 1.72%   |
| Kingston SA400S37120G 120GB SSD  | 5        | 1.72%   |
| Hitachi HDS721050CLA362 500GB    | 5        | 1.72%   |
| Samsung SSD 860 EVO 250GB        | 4        | 1.37%   |
| Hitachi HDS721616PLA380 160GB    | 4        | 1.37%   |
| WDC WD5000AZLX-60K2TA0 500GB     | 3        | 1.03%   |
| WDC WD10EZEX-22MFCA0 1TB         | 3        | 1.03%   |
| Toshiba MQ01ABD100 1TB           | 3        | 1.03%   |
| Toshiba DT01ACA100 1TB           | 3        | 1.03%   |
| Seagate ST500DM002-1ER14C 500GB  | 3        | 1.03%   |
| Seagate ST3160812AS 160GB        | 3        | 1.03%   |
| Samsung SSD 860 EVO 500GB        | 3        | 1.03%   |
| Lexar 128GB SSD                  | 3        | 1.03%   |
| Hitachi HTS543232A7A384 320GB    | 3        | 1.03%   |
| WDC WD5003ABYZ-011FA0 500GB      | 2        | 0.69%   |
| WDC WD20EARX-00ZUDB0 2TB         | 2        | 0.69%   |
| WDC WD10EZEX-08M2NA0 1TB         | 2        | 0.69%   |
| WDC WD10EZEX-00BN5A0 1TB         | 2        | 0.69%   |
| Transcend TS128GSSD370S 128GB    | 2        | 0.69%   |
| Toshiba THNSNJ128G8NU 128GB SSD  | 2        | 0.69%   |
| Team T253X2256G 256GB SSD        | 2        | 0.69%   |
| Seagate ST3500312CS 500GB        | 2        | 0.69%   |
| Seagate ST31000524AS 1TB         | 2        | 0.69%   |
| Seagate ST2000DM008-2FR102 2TB   | 2        | 0.69%   |
| Seagate ST1000DM003-9YN162 1TB   | 2        | 0.69%   |
| Seagate ST1000DM003-1ER162 1TB   | 2        | 0.69%   |
| Seagate ST1000DM003-1CH162 1TB   | 2        | 0.69%   |
| SanDisk SDSSDA240G 240GB         | 2        | 0.69%   |
| Samsung SSD 980 500GB            | 2        | 0.69%   |
| Samsung SSD 970 EVO Plus 500GB   | 2        | 0.69%   |
| Kingston SV300S37A120G 120GB SSD | 2        | 0.69%   |
| Kingston SA400S37240G 240GB SSD  | 2        | 0.69%   |
| Hitachi HDT725025VLA380 250GB    | 2        | 0.69%   |
| Hitachi HDT722525DLA380 250GB    | 2        | 0.69%   |
| HGST HTS725050A7E630 500GB       | 2        | 0.69%   |
| Gigabyte GP-GSTFS31120GNTD 120GB | 2        | 0.69%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 57       | 83     | 38%     |
| WDC                 | 50       | 64     | 33.33%  |
| Toshiba             | 18       | 22     | 12%     |
| Hitachi             | 15       | 28     | 10%     |
| Samsung Electronics | 3        | 4      | 2%      |
| HGST                | 3        | 3      | 2%      |
| Fujitsu             | 2        | 2      | 1.33%   |
| Unknown             | 1        | 1      | 0.67%   |
| ExcelStor           | 1        | 1      | 0.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 14       | 19     | 17.5%   |
| Samsung Electronics | 11       | 17     | 13.75%  |
| SanDisk             | 8        | 9      | 10%     |
| Lexar               | 6        | 7      | 7.5%    |
| Team                | 5        | 7      | 6.25%   |
| WDC                 | 4        | 6      | 5%      |
| Transcend           | 4        | 4      | 5%      |
| A-DATA Technology   | 3        | 3      | 3.75%   |
| Toshiba             | 2        | 2      | 2.5%    |
| SK hynix            | 2        | 8      | 2.5%    |
| Intel               | 2        | 3      | 2.5%    |
| Gigabyte Technology | 2        | 2      | 2.5%    |
| ZOTAC               | 1        | 1      | 1.25%   |
| WALRAM              | 1        | 1      | 1.25%   |
| Unknown             | 1        | 2      | 1.25%   |
| SKIHOTAR            | 1        | 1      | 1.25%   |
| PNY                 | 1        | 1      | 1.25%   |
| Patriot             | 1        | 1      | 1.25%   |
| KingSpec            | 1        | 1      | 1.25%   |
| Kingmax             | 1        | 1      | 1.25%   |
| Kimtigo             | 1        | 2      | 1.25%   |
| Indilinx            | 1        | 1      | 1.25%   |
| HS-SSD-E100         | 1        | 1      | 1.25%   |
| HS-SSD-C100         | 1        | 1      | 1.25%   |
| Hikvision           | 1        | 2      | 1.25%   |
| GLOWAY              | 1        | 1      | 1.25%   |
| FORESEE             | 1        | 1      | 1.25%   |
| Crucial             | 1        | 2      | 1.25%   |
| Corsair             | 1        | 1      | 1.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 119      | 208    | 55.09%  |
| SSD     | 66       | 108    | 30.56%  |
| NVMe    | 22       | 28     | 10.19%  |
| Unknown | 8        | 8      | 3.7%    |
| MMC     | 1        | 1      | 0.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 140      | 314    | 82.35%  |
| NVMe | 22       | 28     | 12.94%  |
| SAS  | 7        | 10     | 4.12%   |
| MMC  | 1        | 1      | 0.59%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 119      | 209    | 64.32%  |
| 0.51-1.0   | 45       | 82     | 24.32%  |
| 1.01-2.0   | 11       | 13     | 5.95%   |
| 3.01-4.0   | 10       | 12     | 5.41%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 53       | 32.72%  |
| 251-500        | 36       | 22.22%  |
| 501-1000       | 15       | 9.26%   |
| 1001-2000      | 13       | 8.02%   |
| 51-100         | 10       | 6.17%   |
| More than 3000 | 9        | 5.56%   |
| 1-20           | 8        | 4.94%   |
| 2001-3000      | 7        | 4.32%   |
| Unknown        | 6        | 3.7%    |
| 21-50          | 5        | 3.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 55       | 33.74%  |
| 21-50          | 33       | 20.25%  |
| 101-250        | 20       | 12.27%  |
| 51-100         | 20       | 12.27%  |
| 501-1000       | 10       | 6.13%   |
| 251-500        | 7        | 4.29%   |
| Unknown        | 6        | 3.68%   |
| 2001-3000      | 5        | 3.07%   |
| 1001-2000      | 5        | 3.07%   |
| More than 3000 | 2        | 1.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Hitachi HDS721050CLA362 500GB   | 5        | 10     | 22.73%  |
| Hitachi HTS543232A7A384 320GB   | 3        | 5      | 13.64%  |
| WDC WD5003ABYZ-011FA0 500GB     | 1        | 1      | 4.55%   |
| WDC WD5000AAKX-603CA0 500GB     | 1        | 1      | 4.55%   |
| WDC WD3200AAJS-08L7A0 320GB     | 1        | 1      | 4.55%   |
| WDC WD10EZEX-00MFCA0 1TB        | 1        | 1      | 4.55%   |
| Unknown S050 Hard drive 500GB   | 1        | 1      | 4.55%   |
| Toshiba MQ01ABD100 1TB          | 1        | 1      | 4.55%   |
| Toshiba DT01ACA100 1TB          | 1        | 1      | 4.55%   |
| Toshiba DT01ACA050 500GB        | 1        | 1      | 4.55%   |
| Seagate ST500DM002-1BD142 500GB | 1        | 2      | 4.55%   |
| Seagate ST380815AS 80GB         | 1        | 1      | 4.55%   |
| Seagate ST3500514NS 500GB       | 1        | 1      | 4.55%   |
| Seagate ST3500418AS 500GB       | 1        | 1      | 4.55%   |
| Hitachi HDS721050CLA660 500GB   | 1        | 1      | 4.55%   |
| HGST HTS541010A9E680 1TB        | 1        | 1      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Hitachi | 6        | 16     | 33.33%  |
| WDC     | 4        | 4      | 22.22%  |
| Seagate | 4        | 5      | 22.22%  |
| Toshiba | 2        | 3      | 11.11%  |
| Unknown | 1        | 1      | 5.56%   |
| HGST    | 1        | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Hitachi | 6        | 16     | 33.33%  |
| WDC     | 4        | 4      | 22.22%  |
| Seagate | 4        | 5      | 22.22%  |
| Toshiba | 2        | 3      | 11.11%  |
| Unknown | 1        | 1      | 5.56%   |
| HGST    | 1        | 1      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 15       | 30     | 100%    |

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
| Detected | 98       | 226    | 62.42%  |
| Works    | 44       | 97     | 28.03%  |
| Malfunc  | 15       | 30     | 9.55%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 83       | 47.7%   |
| AMD                          | 56       | 32.18%  |
| Nvidia                       | 7        | 4.02%   |
| Phison Electronics           | 6        | 3.45%   |
| Samsung Electronics          | 4        | 2.3%    |
| Silicon Motion               | 3        | 1.72%   |
| Micron/Crucial Technology    | 3        | 1.72%   |
| Marvell Technology Group     | 3        | 1.72%   |
| Kingston Technology Company  | 2        | 1.15%   |
| ADATA Technology             | 2        | 1.15%   |
| Toshiba America Info Systems | 1        | 0.57%   |
| SanDisk                      | 1        | 0.57%   |
| Realtek Semiconductor        | 1        | 0.57%   |
| Broadcom / LSI               | 1        | 0.57%   |
| ASMedia Technology           | 1        | 0.57%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 31       | 12.81%  |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 13       | 5.37%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 13       | 5.37%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 12       | 4.96%   |
| AMD 400 Series Chipset SATA Controller                                                  | 11       | 4.55%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 9        | 3.72%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 9        | 3.72%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8        | 3.31%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8        | 3.31%   |
| Nvidia MCP61 SATA Controller                                                            | 7        | 2.89%   |
| Nvidia MCP61 IDE                                                                        | 7        | 2.89%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 7        | 2.89%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6        | 2.48%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 6        | 2.48%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6        | 2.48%   |
| AMD 300 Series Chipset SATA Controller                                                  | 6        | 2.48%   |
| AMD FCH SATA Controller D                                                               | 5        | 2.07%   |
| AMD FCH IDE Controller                                                                  | 5        | 2.07%   |
| AMD 500 Series Chipset SATA Controller                                                  | 5        | 2.07%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 4        | 1.65%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 1.65%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3        | 1.24%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 3        | 1.24%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3        | 1.24%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 0.83%   |
| Samsung NVMe SSD Controller 980                                                         | 2        | 0.83%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 0.83%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2        | 0.83%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2        | 0.83%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 0.83%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 0.83%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2        | 0.83%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 0.83%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 2        | 0.83%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 1        | 0.41%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1        | 0.41%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.41%   |
| Realtek Realtek Non-Volatile memory controller                                          | 1        | 0.41%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 0.41%   |
| Phison Electronics Non-Volatile memory controller                                       | 1        | 0.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 111      | 60%     |
| IDE  | 46       | 24.86%  |
| NVMe | 22       | 11.89%  |
| RAID | 5        | 2.7%    |
| SAS  | 1        | 0.54%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 84       | 56.76%  |
| AMD    | 63       | 42.57%  |
| ARM    | 1        | 0.68%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 6        | 4.05%   |
| AMD Ryzen 5 3600 6-Core Processor             | 5        | 3.38%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 5        | 3.38%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 4        | 2.7%    |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 4        | 2.7%    |
| AMD Sempron Processor LE-1100                 | 3        | 2.03%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 3        | 2.03%   |
| AMD A8-7600 Radeon R7, 10 Compute Cores 4C+6G | 3        | 2.03%   |
| AMD A6-6400K APU with Radeon HD Graphics      | 3        | 2.03%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 2        | 1.35%   |
| Intel Pentium CPU G2020 @ 2.90GHz             | 2        | 1.35%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 2        | 1.35%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 2        | 1.35%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 2        | 1.35%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 2        | 1.35%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 2        | 1.35%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 2        | 1.35%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2        | 1.35%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 2        | 1.35%   |
| Intel Core i3-4170 CPU @ 3.70GHz              | 2        | 1.35%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 2        | 1.35%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 2        | 1.35%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz         | 2        | 1.35%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 2        | 1.35%   |
| Intel 12th Gen Core i5-12400                  | 2        | 1.35%   |
| Intel 11th Gen Core i9-11900K @ 3.50GHz       | 2        | 1.35%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 2        | 1.35%   |
| AMD Ryzen 7 2700 Eight-Core Processor         | 2        | 1.35%   |
| AMD A6-7480 Radeon R5, 8 Compute Cores 2C+6G  | 2        | 1.35%   |
| AMD A10-5800K APU with Radeon HD Graphics     | 2        | 1.35%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz           | 1        | 0.68%   |
| Intel Pentium Gold G6400 CPU @ 4.00GHz        | 1        | 0.68%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz        | 1        | 0.68%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz   | 1        | 0.68%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz   | 1        | 0.68%   |
| Intel Pentium CPU G4600 @ 3.60GHz             | 1        | 0.68%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 1        | 0.68%   |
| Intel Core i9-10850K CPU @ 3.60GHz            | 1        | 0.68%   |
| Intel Core i7-7800X CPU @ 3.50GHz             | 1        | 0.68%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1        | 0.68%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 23       | 15.54%  |
| AMD Ryzen 5             | 15       | 10.14%  |
| Intel Core i7           | 14       | 9.46%   |
| Intel Core i3           | 13       | 8.78%   |
| Intel Core 2 Duo        | 10       | 6.76%   |
| AMD A6                  | 8        | 5.41%   |
| Other                   | 7        | 4.73%   |
| AMD Ryzen 3             | 6        | 4.05%   |
| Intel Pentium Dual-Core | 4        | 2.7%    |
| Intel Pentium           | 4        | 2.7%    |
| Intel Celeron           | 4        | 2.7%    |
| AMD Ryzen 7             | 4        | 2.7%    |
| AMD FX                  | 4        | 2.7%    |
| AMD A8                  | 4        | 2.7%    |
| Intel Core 2 Quad       | 3        | 2.03%   |
| AMD Sempron             | 3        | 2.03%   |
| AMD Athlon II X2        | 3        | 2.03%   |
| AMD A4                  | 3        | 2.03%   |
| AMD A10                 | 3        | 2.03%   |
| Intel Pentium Gold      | 2        | 1.35%   |
| AMD Ryzen 9             | 2        | 1.35%   |
| AMD Phenom II X4        | 2        | 1.35%   |
| AMD Athlon              | 2        | 1.35%   |
| Intel Xeon              | 1        | 0.68%   |
| Intel Core i9           | 1        | 0.68%   |
| AMD Ryzen 7 PRO         | 1        | 0.68%   |
| AMD Phenom II X2        | 1        | 0.68%   |
| AMD Athlon 64 X2        | 1        | 0.68%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 52       | 35.14%  |
| 2      | 51       | 34.46%  |
| 6      | 20       | 13.51%  |
| 1      | 13       | 8.78%   |
| 8      | 7        | 4.73%   |
| 16     | 2        | 1.35%   |
| 12     | 1        | 0.68%   |
| 10     | 1        | 0.68%   |
| 3      | 1        | 0.68%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 147      | 99.32%  |
| 2      | 1        | 0.68%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 83       | 56.08%  |
| 1      | 65       | 43.92%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 146      | 97.99%  |
| Unknown        | 3        | 2.01%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 41       | 27.33%  |
| 0x306c3    | 13       | 8.67%   |
| 0x1067a    | 12       | 8%      |
| 0x306a9    | 6        | 4%      |
| 0x08701021 | 6        | 4%      |
| 0x0800820d | 6        | 4%      |
| 0x06001119 | 6        | 4%      |
| 0x906ea    | 5        | 3.33%   |
| 0x906e9    | 5        | 3.33%   |
| 0x506e3    | 5        | 3.33%   |
| 0x206a7    | 4        | 2.67%   |
| 0x06003106 | 4        | 2.67%   |
| 0xa0671    | 3        | 2%      |
| 0x08108109 | 3        | 2%      |
| 0x6fb      | 2        | 1.33%   |
| 0x10676    | 2        | 1.33%   |
| 0x08600106 | 2        | 1.33%   |
| 0x0810100b | 2        | 1.33%   |
| 0x010000c8 | 2        | 1.33%   |
| 0x010000c7 | 2        | 1.33%   |
| 0xa0655    | 1        | 0.67%   |
| 0xa0653    | 1        | 0.67%   |
| 0x90675    | 1        | 0.67%   |
| 0x90672    | 1        | 0.67%   |
| 0x706a1    | 1        | 0.67%   |
| 0x50654    | 1        | 0.67%   |
| 0x406f1    | 1        | 0.67%   |
| 0x40651    | 1        | 0.67%   |
| 0x30679    | 1        | 0.67%   |
| 0x106e5    | 1        | 0.67%   |
| 0x08101102 | 1        | 0.67%   |
| 0x08101016 | 1        | 0.67%   |
| 0x08101007 | 1        | 0.67%   |
| 0x0700010f | 1        | 0.67%   |
| 0x0600611a | 1        | 0.67%   |
| 0x06000852 | 1        | 0.67%   |
| 0x0600063e | 1        | 0.67%   |
| 0x03000027 | 1        | 0.67%   |
| 0x010000db | 1        | 0.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 18       | 12.16%  |
| Penryn           | 15       | 10.14%  |
| Piledriver       | 13       | 8.78%   |
| Zen+             | 12       | 8.11%   |
| KabyLake         | 12       | 8.11%   |
| IvyBridge        | 11       | 7.43%   |
| Zen 2            | 10       | 6.76%   |
| Skylake          | 7        | 4.73%   |
| Zen              | 6        | 4.05%   |
| K10              | 6        | 4.05%   |
| Steamroller      | 5        | 3.38%   |
| SandyBridge      | 5        | 3.38%   |
| K8 Hammer        | 4        | 2.7%    |
| CometLake        | 4        | 2.7%    |
| Excavator        | 3        | 2.03%   |
| Nehalem          | 2        | 1.35%   |
| Icelake          | 2        | 1.35%   |
| Core             | 2        | 1.35%   |
| Alderlake Hybrid | 2        | 1.35%   |
| Unknown          | 2        | 1.35%   |
| Zen 3            | 1        | 0.68%   |
| Silvermont       | 1        | 0.68%   |
| K10 Llano        | 1        | 0.68%   |
| Jaguar           | 1        | 0.68%   |
| Goldmont plus    | 1        | 0.68%   |
| Bulldozer        | 1        | 0.68%   |
| Broadwell        | 1        | 0.68%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 61       | 37.2%   |
| AMD    | 55       | 33.54%  |
| Intel  | 48       | 29.27%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 4 Series Chipset Integrated Graphics Controller                       | 8        | 4.73%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7        | 4.14%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 6        | 3.55%   |
| Nvidia G72 [GeForce 7200 GS / 7300 SE]                                      | 6        | 3.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 6        | 3.55%   |
| Nvidia GF108 [GeForce GT 730]                                               | 5        | 2.96%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 4        | 2.37%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 2.37%   |
| Nvidia GF108 [GeForce GT 630]                                               | 4        | 2.37%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 4        | 2.37%   |
| Intel HD Graphics 630                                                       | 4        | 2.37%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 4        | 2.37%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 4        | 2.37%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4        | 2.37%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 4        | 2.37%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 4        | 2.37%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 1.78%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 1.78%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 3        | 1.78%   |
| Intel HD Graphics 530                                                       | 3        | 1.78%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 3        | 1.78%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.78%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 3        | 1.78%   |
| AMD Richland [Radeon HD 8470D]                                              | 3        | 1.78%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 3        | 1.78%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 1.18%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 1.18%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 1.18%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 1.18%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 1.18%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 2        | 1.18%   |
| Intel VGA compatible controller                                             | 2        | 1.18%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 2        | 1.18%   |
| AMD Renoir                                                                  | 2        | 1.18%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 1.18%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.59%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.59%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.59%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 0.59%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 53       | 34.19%  |
| 1 x Nvidia     | 52       | 33.55%  |
| 1 x Intel      | 40       | 25.81%  |
| Intel + Nvidia | 5        | 3.23%   |
| 2 x Nvidia     | 2        | 1.29%   |
| Other          | 1        | 0.65%   |
| 2 x AMD        | 1        | 0.65%   |
| AMD + Nvidia   | 1        | 0.65%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 109      | 72.67%  |
| Proprietary | 33       | 22%     |
| Unknown     | 8        | 5.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 66       | 42.86%  |
| 1.01-2.0   | 25       | 16.23%  |
| 0.51-1.0   | 17       | 11.04%  |
| 0.01-0.5   | 15       | 9.74%   |
| 3.01-4.0   | 12       | 7.79%   |
| 7.01-8.0   | 7        | 4.55%   |
| 5.01-6.0   | 6        | 3.9%    |
| 8.01-16.0  | 4        | 2.6%    |
| 2.01-3.0   | 2        | 1.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 23       | 14.74%  |
| Dell                 | 21       | 13.46%  |
| AOC                  | 15       | 9.62%   |
| Acer                 | 15       | 9.62%   |
| Hewlett-Packard      | 8        | 5.13%   |
| Goldstar             | 7        | 4.49%   |
| Ancor Communications | 7        | 4.49%   |
| ASUSTek Computer     | 6        | 3.85%   |
| Sony                 | 5        | 3.21%   |
| BenQ                 | 5        | 3.21%   |
| ViewSonic            | 4        | 2.56%   |
| Lenovo               | 3        | 1.92%   |
| VIE                  | 2        | 1.28%   |
| Unknown              | 2        | 1.28%   |
| Philips              | 2        | 1.28%   |
| Mi                   | 2        | 1.28%   |
| IPS                  | 2        | 1.28%   |
| eMachines            | 2        | 1.28%   |
| Eizo                 | 2        | 1.28%   |
| Unknown (XXX)        | 1        | 0.64%   |
| SMC                  | 1        | 0.64%   |
| Sharp                | 1        | 0.64%   |
| SGT                  | 1        | 0.64%   |
| SANYO                | 1        | 0.64%   |
| SAC                  | 1        | 0.64%   |
| Pixio                | 1        | 0.64%   |
| NVISION              | 1        | 0.64%   |
| NVI                  | 1        | 0.64%   |
| NEX                  | 1        | 0.64%   |
| MStar                | 1        | 0.64%   |
| MSI                  | 1        | 0.64%   |
| LLL                  | 1        | 0.64%   |
| HON                  | 1        | 0.64%   |
| HKC                  | 1        | 0.64%   |
| GDH                  | 1        | 0.64%   |
| EXP                  | 1        | 0.64%   |
| ELSA International   | 1        | 0.64%   |
| EKD                  | 1        | 0.64%   |
| CTV                  | 1        | 0.64%   |
| AUS                  | 1        | 0.64%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 4        | 2.44%   |
| Dell SE177FP DELF001 1280x1024 338x270mm 17.0-inch                    | 4        | 2.44%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                        | 4        | 2.44%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch     | 3        | 1.83%   |
| Lenovo L1951p Wide LEN0990 1440x900 408x255mm 18.9-inch               | 3        | 1.83%   |
| Dell P170S DEL4058 1280x1024 338x270mm 17.0-inch                      | 3        | 1.83%   |
| AOC 2060W AOC2060 1600x900 432x240mm 19.5-inch                        | 3        | 1.83%   |
| Ancor Communications ASUS VC239 ACI23C4 1920x1080 509x286mm 23.0-inch | 3        | 1.83%   |
| VIE A/G1956 VIE1850 1366x768 414x257mm 19.2-inch                      | 2        | 1.22%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 2        | 1.22%   |
| Mi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                      | 2        | 1.22%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2        | 1.22%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                      | 2        | 1.22%   |
| Dell E198FP DELA028 1280x1024 376x301mm 19.0-inch                     | 2        | 1.22%   |
| ASUSTek Computer VG27AQL1A AUS2705 2560x1440 600x340mm 27.2-inch      | 2        | 1.22%   |
| Acer S200HQL  ACR0359 1600x900 430x240mm 19.4-inch                    | 2        | 1.22%   |
| Acer R230H ACR046E 1920x1080 509x286mm 23.0-inch                      | 2        | 1.22%   |
| Acer EB192Q ACR0517 1366x768 410x230mm 18.5-inch                      | 2        | 1.22%   |
| ViewSonic XG2705 VSC0E39 1920x1080 598x336mm 27.0-inch                | 1        | 0.61%   |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch         | 1        | 0.61%   |
| ViewSonic VA1917 SERIES VSCAD30 1366x768 410x230mm 18.5-inch          | 1        | 0.61%   |
| ViewSonic VA1601W-LED VSC1A25 1366x768 344x193mm 15.5-inch            | 1        | 0.61%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                 | 1        | 0.61%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1        | 0.61%   |
| Unknown (XXX) Beyond TV XXX2851 1920x1080 1209x680mm 54.6-inch        | 1        | 0.61%   |
| Sony TV SNYAB03 1920x1080                                             | 1        | 0.61%   |
| Sony TV SNYA301 1920x1080                                             | 1        | 0.61%   |
| Sony TV SNY4B03 1920x1080 708x398mm 32.0-inch                         | 1        | 0.61%   |
| Sony TV SNY2A01 1360x768                                              | 1        | 0.61%   |
| Sony HD FORU SNY1A02 1920x1080                                        | 1        | 0.61%   |
| SMC LCD Monitor SMC0001 1920x540 720x420mm 32.8-inch                  | 1        | 0.61%   |
| Sharp LL-153A-B SHP2163 1024x768 304x228mm 15.0-inch                  | 1        | 0.61%   |
| SGT Monitor SGT2360 1920x1080 521x299mm 23.6-inch                     | 1        | 0.61%   |
| SANYO LED MONITOR SAN309A 1920x1080 443x249mm 20.0-inch               | 1        | 0.61%   |
| Samsung Electronics SyncMaster SAM0841 1920x1080 885x498mm 40.0-inch  | 1        | 0.61%   |
| Samsung Electronics SyncMaster SAM0381 1280x1024 338x270mm 17.0-inch  | 1        | 0.61%   |
| Samsung Electronics SyncMaster SAM01A9 1280x1024 338x270mm 17.0-inch  | 1        | 0.61%   |
| Samsung Electronics SMB2230 SAM063F 1920x1080 477x268mm 21.5-inch     | 1        | 0.61%   |
| Samsung Electronics SMB1740R SAM0692 1280x1024 338x270mm 17.0-inch    | 1        | 0.61%   |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch  | 1        | 0.61%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 66       | 44.9%   |
| 1366x768 (WXGA)   | 28       | 19.05%  |
| 1280x1024 (SXGA)  | 15       | 10.2%   |
| 1600x900 (HD+)    | 12       | 8.16%   |
| 3840x2160 (4K)    | 8        | 5.44%   |
| 1440x900 (WXGA+)  | 5        | 3.4%    |
| 2560x1440 (QHD)   | 3        | 2.04%   |
| 3440x1440         | 2        | 1.36%   |
| 1920x1200 (WUXGA) | 2        | 1.36%   |
| 3200x1080         | 1        | 0.68%   |
| 2288x1287         | 1        | 0.68%   |
| 1920x540          | 1        | 0.68%   |
| 1360x768          | 1        | 0.68%   |
| 1024x768 (XGA)    | 1        | 0.68%   |
| Unknown           | 1        | 0.68%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 18      | 22       | 14.01%  |
| 23      | 19       | 12.1%   |
| 21      | 15       | 9.55%   |
| 24      | 14       | 8.92%   |
| 19      | 13       | 8.28%   |
| Unknown | 13       | 8.28%   |
| 20      | 12       | 7.64%   |
| 17      | 12       | 7.64%   |
| 27      | 10       | 6.37%   |
| 15      | 5        | 3.18%   |
| 72      | 4        | 2.55%   |
| 32      | 4        | 2.55%   |
| 31      | 4        | 2.55%   |
| 52      | 2        | 1.27%   |
| 40      | 2        | 1.27%   |
| 142     | 1        | 0.64%   |
| 54      | 1        | 0.64%   |
| 50      | 1        | 0.64%   |
| 39      | 1        | 0.64%   |
| 34      | 1        | 0.64%   |
| 22      | 1        | 0.64%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 56       | 37.33%  |
| 501-600        | 40       | 26.67%  |
| 301-350        | 17       | 11.33%  |
| Unknown        | 13       | 8.67%   |
| 701-800        | 5        | 3.33%   |
| 601-700        | 4        | 2.67%   |
| 1501-2000      | 4        | 2.67%   |
| 1001-1500      | 4        | 2.67%   |
| 801-900        | 3        | 2%      |
| 351-400        | 3        | 2%      |
| More than 2000 | 1        | 0.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 101      | 70.14%  |
| 5/4     | 14       | 9.72%   |
| Unknown | 13       | 9.03%   |
| 16/10   | 12       | 8.33%   |
| 6/5     | 1        | 0.69%   |
| 4/3     | 1        | 0.69%   |
| 21/9    | 1        | 0.69%   |
| 1.00    | 1        | 0.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 36       | 23.84%  |
| 141-150        | 32       | 21.19%  |
| 151-200        | 31       | 20.53%  |
| Unknown        | 13       | 8.61%   |
| 301-350        | 10       | 6.62%   |
| More than 1000 | 9        | 5.96%   |
| 351-500        | 9        | 5.96%   |
| 101-110        | 4        | 2.65%   |
| 251-300        | 3        | 1.99%   |
| 501-1000       | 3        | 1.99%   |
| 91-100         | 1        | 0.66%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 94       | 64.83%  |
| 101-120 | 27       | 18.62%  |
| Unknown | 13       | 8.97%   |
| 1-50    | 10       | 6.9%    |
| 161-240 | 1        | 0.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 118      | 78.15%  |
| 2     | 23       | 15.23%  |
| 0     | 10       | 6.62%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 113      | 54.07%  |
| Intel                             | 31       | 14.83%  |
| Ralink Technology                 | 15       | 7.18%   |
| Qualcomm Atheros                  | 12       | 5.74%   |
| TP-Link                           | 7        | 3.35%   |
| Nvidia                            | 5        | 2.39%   |
| Samsung Electronics               | 3        | 1.44%   |
| Linksys                           | 3        | 1.44%   |
| Huawei Technologies               | 3        | 1.44%   |
| Xiaomi                            | 2        | 0.96%   |
| OPPO Electronics                  | 2        | 0.96%   |
| D-Link                            | 2        | 0.96%   |
| Broadcom                          | 2        | 0.96%   |
| Tenda                             | 1        | 0.48%   |
| Sundance Technology Inc / IC Plus | 1        | 0.48%   |
| Ralink                            | 1        | 0.48%   |
| Qualcomm Atheros Communications   | 1        | 0.48%   |
| Qualcomm                          | 1        | 0.48%   |
| JMicron Technology                | 1        | 0.48%   |
| ICS Advent                        | 1        | 0.48%   |
| D-Link System                     | 1        | 0.48%   |
| Broadcom Limited                  | 1        | 0.48%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 102      | 42.86%  |
| Ralink MT7601U Wireless Adapter                                            | 7        | 2.94%   |
| Realtek RTL8125 2.5GbE Controller                                          | 5        | 2.1%    |
| Nvidia MCP61 Ethernet                                                      | 5        | 2.1%    |
| Intel Wi-Fi 6 AX200                                                        | 5        | 2.1%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 4        | 1.68%   |
| Realtek 802.11ac NIC                                                       | 4        | 1.68%   |
| Intel I211 Gigabit Network Connection                                      | 4        | 1.68%   |
| Intel Ethernet Controller I225-V                                           | 4        | 1.68%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                         | 3        | 1.26%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                      | 3        | 1.26%   |
| Ralink RT5370 Wireless Adapter                                             | 3        | 1.26%   |
| Ralink RT2870/RT3070 Wireless Adapter                                      | 3        | 1.26%   |
| Linksys WUSB600N v1 Dual-Band Wireless-N Network Adapter [Ralink RT2870]   | 3        | 1.26%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 3        | 1.26%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                | 2        | 0.84%   |
| Samsung E2530 Phone (Samsung Kies mode)                                    | 2        | 0.84%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 2        | 0.84%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                          | 2        | 0.84%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 2        | 0.84%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 2        | 0.84%   |
| OPPO RMX2180                                                               | 2        | 0.84%   |
| Intel Ethernet Connection I217-V                                           | 2        | 0.84%   |
| Intel Ethernet Connection (2) I219-V                                       | 2        | 0.84%   |
| Intel Alder Lake-S PCH CNVi WiFi                                           | 2        | 0.84%   |
| Intel 82579V Gigabit Network Connection                                    | 2        | 0.84%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 2        | 0.84%   |
| Huawei LYA-L09                                                             | 2        | 0.84%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 1        | 0.42%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 1        | 0.42%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                               | 1        | 0.42%   |
| TP-Link Archer T4U ver.3                                                   | 1        | 0.42%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                        | 1        | 0.42%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 1        | 0.42%   |
| TP-Link 802.11ac WLAN Adapter                                              | 1        | 0.42%   |
| Tenda U12                                                                  | 1        | 0.42%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.42%   |
| Samsung WIS09ABGN LinkStick Wireless LAN Adapter                           | 1        | 0.42%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                   | 1        | 0.42%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                 | 1        | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 18       | 25.71%  |
| Intel                           | 16       | 22.86%  |
| Ralink Technology               | 15       | 21.43%  |
| TP-Link                         | 7        | 10%     |
| Qualcomm Atheros                | 4        | 5.71%   |
| Linksys                         | 3        | 4.29%   |
| D-Link                          | 2        | 2.86%   |
| Tenda                           | 1        | 1.43%   |
| Samsung Electronics             | 1        | 1.43%   |
| Ralink                          | 1        | 1.43%   |
| Qualcomm Atheros Communications | 1        | 1.43%   |
| Broadcom                        | 1        | 1.43%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                    | Desktops | Percent |
|--------------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                          | 7        | 9.86%   |
| Intel Wi-Fi 6 AX200                                                      | 5        | 7.04%   |
| Realtek 802.11ac NIC                                                     | 4        | 5.63%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                       | 3        | 4.23%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                    | 3        | 4.23%   |
| Ralink RT5370 Wireless Adapter                                           | 3        | 4.23%   |
| Ralink RT2870/RT3070 Wireless Adapter                                    | 3        | 4.23%   |
| Linksys WUSB600N v1 Dual-Band Wireless-N Network Adapter [Ralink RT2870] | 3        | 4.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                         | 3        | 4.23%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                              | 2        | 2.82%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                      | 2        | 2.82%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                        | 2        | 2.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                         | 2        | 2.82%   |
| Intel Alder Lake-S PCH CNVi WiFi                                         | 2        | 2.82%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                             | 1        | 1.41%   |
| TP-Link Archer T4U ver.3                                                 | 1        | 1.41%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                      | 1        | 1.41%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]               | 1        | 1.41%   |
| TP-Link 802.11ac WLAN Adapter                                            | 1        | 1.41%   |
| Tenda U12                                                                | 1        | 1.41%   |
| Samsung WIS09ABGN LinkStick Wireless LAN Adapter                         | 1        | 1.41%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                 | 1        | 1.41%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                               | 1        | 1.41%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                   | 1        | 1.41%   |
| Realtek RTL8188EE Wireless Network Adapter                               | 1        | 1.41%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                  | 1        | 1.41%   |
| Realtek 802.11n WLAN Adapter                                             | 1        | 1.41%   |
| Ralink RT3072 Wireless Adapter                                           | 1        | 1.41%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                     | 1        | 1.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter               | 1        | 1.41%   |
| Qualcomm Atheros AR9271 802.11n                                          | 1        | 1.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)           | 1        | 1.41%   |
| Intel Wireless-AC 9260                                                   | 1        | 1.41%   |
| Intel Wireless 7260                                                      | 1        | 1.41%   |
| Intel Wireless 3165                                                      | 1        | 1.41%   |
| Intel Tiger Lake PCH CNVi WiFi                                           | 1        | 1.41%   |
| Intel Comet Lake PCH CNVi WiFi                                           | 1        | 1.41%   |
| Intel Centrino Wireless-N 2230                                           | 1        | 1.41%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]     | 1        | 1.41%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                           | 1        | 1.41%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 112      | 69.14%  |
| Intel                             | 23       | 14.2%   |
| Qualcomm Atheros                  | 9        | 5.56%   |
| Nvidia                            | 5        | 3.09%   |
| Xiaomi                            | 2        | 1.23%   |
| OPPO Electronics                  | 2        | 1.23%   |
| Huawei Technologies               | 2        | 1.23%   |
| Sundance Technology Inc / IC Plus | 1        | 0.62%   |
| Qualcomm                          | 1        | 0.62%   |
| JMicron Technology                | 1        | 0.62%   |
| ICS Advent                        | 1        | 0.62%   |
| D-Link System                     | 1        | 0.62%   |
| Broadcom Limited                  | 1        | 0.62%   |
| Broadcom                          | 1        | 0.62%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 102      | 62.2%   |
| Realtek RTL8125 2.5GbE Controller                                          | 5        | 3.05%   |
| Nvidia MCP61 Ethernet                                                      | 5        | 3.05%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 4        | 2.44%   |
| Intel I211 Gigabit Network Connection                                      | 4        | 2.44%   |
| Intel Ethernet Controller I225-V                                           | 4        | 2.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 2        | 1.22%   |
| OPPO RMX2180                                                               | 2        | 1.22%   |
| Intel Ethernet Connection I217-V                                           | 2        | 1.22%   |
| Intel Ethernet Connection (2) I219-V                                       | 2        | 1.22%   |
| Intel 82579V Gigabit Network Connection                                    | 2        | 1.22%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 2        | 1.22%   |
| Huawei LYA-L09                                                             | 2        | 1.22%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 1        | 0.61%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 1        | 0.61%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 1        | 0.61%   |
| Qualcomm Mobile Router                                                     | 1        | 0.61%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 1        | 0.61%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 1        | 0.61%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                  | 1        | 0.61%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 1        | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 1        | 0.61%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 1        | 0.61%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 1        | 0.61%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                        | 1        | 0.61%   |
| Intel I210 Gigabit Network Connection                                      | 1        | 0.61%   |
| Intel Ethernet Connection I217-LM                                          | 1        | 0.61%   |
| Intel Ethernet Connection (2) I219-LM                                      | 1        | 0.61%   |
| Intel Ethernet Connection (2) I218-V                                       | 1        | 0.61%   |
| Intel Ethernet Connection (2) I218-LM                                      | 1        | 0.61%   |
| Intel Ethernet Connection (10) I219-V                                      | 1        | 0.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 1        | 0.61%   |
| Intel 82574L Gigabit Network Connection                                    | 1        | 0.61%   |
| Intel 82566DM Gigabit Network Connection                                   | 1        | 0.61%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                    | 1        | 0.61%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                            | 1        | 0.61%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                            | 1        | 0.61%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                   | 1        | 0.61%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 148      | 68.84%  |
| WiFi     | 64       | 29.77%  |
| Modem    | 3        | 1.4%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 122      | 77.22%  |
| WiFi     | 36       | 22.78%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 118      | 79.19%  |
| 2     | 24       | 16.11%  |
| 3     | 7        | 4.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 140      | 92.72%  |
| Yes  | 11       | 7.28%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 15       | 40.54%  |
| Cambridge Silicon Radio    | 12       | 32.43%  |
| Broadcom                   | 4        | 10.81%  |
| Realtek Semiconductor      | 3        | 8.11%   |
| Lite-On Technology         | 1        | 2.7%    |
| Integrated System Solution | 1        | 2.7%    |
| IMC Networks               | 1        | 2.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 12       | 32.43%  |
| Intel AX201 Bluetooth                                 | 4        | 10.81%  |
| Intel AX200 Bluetooth                                 | 4        | 10.81%  |
| Realtek Bluetooth Radio                               | 3        | 8.11%   |
| Intel Wireless-AC 3168 Bluetooth                      | 3        | 8.11%   |
| Intel Bluetooth wireless interface                    | 2        | 5.41%   |
| Broadcom BCM2035 Bluetooth                            | 2        | 5.41%   |
| Lite-On Bluetooth Device                              | 1        | 2.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1        | 2.7%    |
| Intel Centrino Bluetooth Wireless Transceiver         | 1        | 2.7%    |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 2.7%    |
| IMC Networks Bluetooth Device                         | 1        | 2.7%    |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 1        | 2.7%    |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1        | 2.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 82       | 34.75%  |
| AMD                         | 68       | 28.81%  |
| Nvidia                      | 58       | 24.58%  |
| C-Media Electronics         | 5        | 2.12%   |
| Generalplus Technology      | 4        | 1.69%   |
| SteelSeries ApS             | 2        | 0.85%   |
| Logitech                    | 2        | 0.85%   |
| GN Netcom                   | 2        | 0.85%   |
| DCMT Technology             | 2        | 0.85%   |
| ZOOM                        | 1        | 0.42%   |
| XMOS                        | 1        | 0.42%   |
| Razer USA                   | 1        | 0.42%   |
| Kingston Technology         | 1        | 0.42%   |
| Giga-Byte Technology        | 1        | 0.42%   |
| FiiO Electronics Technology | 1        | 0.42%   |
| FIFINE 683 Microphone       | 1        | 0.42%   |
| Elgato Systems              | 1        | 0.42%   |
| Corsair                     | 1        | 0.42%   |
| Cooler Master               | 1        | 0.42%   |
| ASUSTek Computer            | 1        | 0.42%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD FCH Azalia Controller                                                         | 19       | 6.57%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 13       | 4.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 13       | 4.5%    |
| AMD Family 17h/19h HD Audio Controller                                            | 12       | 4.15%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 11       | 3.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 10       | 3.46%   |
| Intel 200 Series PCH HD Audio                                                     | 10       | 3.46%   |
| Nvidia GF108 High Definition Audio Controller                                     | 9        | 3.11%   |
| AMD Starship/Matisse HD Audio Controller                                          | 9        | 3.11%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 8        | 2.77%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 8        | 2.77%   |
| Nvidia MCP61 High Definition Audio                                                | 7        | 2.42%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 7        | 2.42%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 7        | 2.42%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 7        | 2.42%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 7        | 2.42%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 6        | 2.08%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 6        | 2.08%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 5        | 1.73%   |
| AMD Trinity HDMI Audio Controller                                                 | 5        | 1.73%   |
| AMD Kaveri HDMI/DP Audio Controller                                               | 5        | 1.73%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 5        | 1.73%   |
| Nvidia TU116 High Definition Audio Controller                                     | 4        | 1.38%   |
| Nvidia GP104 High Definition Audio Controller                                     | 4        | 1.38%   |
| Nvidia GA102 High Definition Audio Controller                                     | 4        | 1.38%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 4        | 1.38%   |
| Generalplus Technology USB Audio Device                                           | 4        | 1.38%   |
| Nvidia GP106 High Definition Audio Controller                                     | 3        | 1.04%   |
| Intel Audio device                                                                | 3        | 1.04%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3        | 1.04%   |
| Nvidia GP108 High Definition Audio Controller                                     | 2        | 0.69%   |
| Nvidia GM204 High Definition Audio Controller                                     | 2        | 0.69%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2        | 0.69%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 2        | 0.69%   |
| Intel Cannon Lake PCH cAVS                                                        | 2        | 0.69%   |
| Intel Alder Lake-S HD Audio Controller                                            | 2        | 0.69%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 2        | 0.69%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 2        | 0.69%   |
| DCMT Technology USB Condenser Microphone                                          | 2        | 0.69%   |
| C-Media Electronics USB Audio Device                                              | 2        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 17       | 25%     |
| Unknown             | 9        | 13.24%  |
| G.Skill             | 7        | 10.29%  |
| Team                | 6        | 8.82%   |
| Corsair             | 6        | 8.82%   |
| SK hynix            | 4        | 5.88%   |
| Samsung Electronics | 4        | 5.88%   |
| Patriot             | 2        | 2.94%   |
| Kingmax             | 2        | 2.94%   |
| Unknown             | 2        | 2.94%   |
| Uroad               | 1        | 1.47%   |
| Transcend           | 1        | 1.47%   |
| Silicon Power       | 1        | 1.47%   |
| PNY                 | 1        | 1.47%   |
| Nanya Technology    | 1        | 1.47%   |
| Mitsubishi          | 1        | 1.47%   |
| Crucial             | 1        | 1.47%   |
| Carry               | 1        | 1.47%   |
| A-DATA Technology   | 1        | 1.47%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s          | 3        | 4.17%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s          | 3        | 4.17%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s           | 2        | 2.78%   |
| Patriot RAM PSD34G160081 4GB DIMM DDR3 1600MT/s              | 2        | 2.78%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s         | 2        | 2.78%   |
| Corsair RAM CMT128GX4M4C3200C16 32GB DIMM DDR4 3200MT/s      | 2        | 2.78%   |
| Corsair RAM CML8GX3M2A1600C9 4GB DIMM DDR3 1867MT/s          | 2        | 2.78%   |
| Unknown                                                      | 2        | 2.78%   |
| Uroad RAM WJD8G4M16P12800 8192MB DIMM DDR3 1600MT/s          | 1        | 1.39%   |
| Unknown RAM Module 8192MB DIMM                               | 1        | 1.39%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                  | 1        | 1.39%   |
| Unknown RAM Module 4GB DIMM DDR4 2133MT/s                    | 1        | 1.39%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 1        | 1.39%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                         | 1        | 1.39%   |
| Unknown RAM Module 4096MB DIMM DDR2                          | 1        | 1.39%   |
| Unknown RAM Module 1GB DIMM DDR2                             | 1        | 1.39%   |
| Unknown RAM Module 16384MB DIMM DDR4 2666MT/s                | 1        | 1.39%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                  | 1        | 1.39%   |
| Unknown RAM Module 1024MB DIMM DDR2                          | 1        | 1.39%   |
| Unknown RAM KZ24UE5116HAR8 8192MB DIMM DDR4 2400MT/s         | 1        | 1.39%   |
| Transcend RAM TS2GLH64V4B 16384MB DIMM DDR4 2400MT/s         | 1        | 1.39%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s          | 1        | 1.39%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s          | 1        | 1.39%   |
| Team RAM TEAMGROUP-UD4-2400 16GB DIMM DDR4 2400MT/s          | 1        | 1.39%   |
| Team RAM TEAMGROUP-UD3-1600 4GB DIMM DDR3 1600MT/s           | 1        | 1.39%   |
| SK hynix RAM Module 8192MB DIMM DDR4 2133MT/s                | 1        | 1.39%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s         | 1        | 1.39%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s         | 1        | 1.39%   |
| SK hynix RAM HMA81GR7MFR8N-UH 8GB DIMM DDR4 2400MT/s         | 1        | 1.39%   |
| SK hynix RAM HMA81GR7AFR8N-UH 8GB DIMM DDR4 2400MT/s         | 1        | 1.39%   |
| Silicon Power RAM SP008GBLFU266B02 8192MB DIMM DDR4 2400MT/s | 1        | 1.39%   |
| Samsung RAM Module 4096MB DIMM DDR4 2133MT/s                 | 1        | 1.39%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s          | 1        | 1.39%   |
| Samsung RAM M378A1K43CB2-CRC 8192MB DIMM DDR4 3500MT/s       | 1        | 1.39%   |
| Samsung RAM M3 78T2863QZS-CF7 1GB DIMM DDR2 800MT/s          | 1        | 1.39%   |
| PNY RAM 16GF2X08QFHH36-135-K 16GB DIMM DDR4 3200MT/s         | 1        | 1.39%   |
| Nanya RAM NT4GC64B8HG0NF-CG 4096MB DIMM DDR3 1333MT/s        | 1        | 1.39%   |
| Mitsubishi RAM Module 8GB DIMM DDR3 1600MT/s                 | 1        | 1.39%   |
| Kingston RAM Module 4GB DIMM DDR3 1600MT/s                   | 1        | 1.39%   |
| Kingston RAM Module 4096MB DIMM DDR3 1600MT/s                | 1        | 1.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 34       | 56.67%  |
| DDR3    | 20       | 33.33%  |
| DDR2    | 3        | 5%      |
| Unknown | 2        | 3.33%   |
| SDRAM   | 1        | 1.67%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 60       | 98.36%  |
| SODIMM | 1        | 1.64%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 29       | 43.94%  |
| 4096  | 18       | 27.27%  |
| 16384 | 9        | 13.64%  |
| 32768 | 6        | 9.09%   |
| 1024  | 3        | 4.55%   |
| 2048  | 1        | 1.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 13       | 20.63%  |
| 3200    | 7        | 11.11%  |
| 2133    | 7        | 11.11%  |
| 2400    | 6        | 9.52%   |
| 3600    | 5        | 7.94%   |
| 3866    | 3        | 4.76%   |
| 2667    | 3        | 4.76%   |
| Unknown | 3        | 4.76%   |
| 3800    | 2        | 3.17%   |
| 2666    | 2        | 3.17%   |
| 1867    | 2        | 3.17%   |
| 1800    | 2        | 3.17%   |
| 1333    | 2        | 3.17%   |
| 3733    | 1        | 1.59%   |
| 3500    | 1        | 1.59%   |
| 3466    | 1        | 1.59%   |
| 3266    | 1        | 1.59%   |
| 800     | 1        | 1.59%   |
| 667     | 1        | 1.59%   |

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
| Microdia                    | 6        | 13.95%  |
| Logitech                    | 6        | 13.95%  |
| Z-Star Microelectronics     | 4        | 9.3%    |
| Jieli Technology            | 4        | 9.3%    |
| A4Tech                      | 4        | 9.3%    |
| Realtek Semiconductor       | 3        | 6.98%   |
| Pixart Imaging              | 3        | 6.98%   |
| Cubeternet                  | 3        | 6.98%   |
| Samsung Electronics         | 2        | 4.65%   |
| Generalplus Technology      | 2        | 4.65%   |
| Silicon Motion              | 1        | 2.33%   |
| Razer USA                   | 1        | 2.33%   |
| KYE Systems (Mouse Systems) | 1        | 2.33%   |
| Aveo Technology             | 1        | 2.33%   |
| Apple                       | 1        | 2.33%   |
| Alcor Micro                 | 1        | 2.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Jieli USB PHY 2.0                                                   | 4        | 9.3%    |
| Z-Star Venus USB2.0 Camera                                          | 3        | 6.98%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                                | 3        | 6.98%   |
| Logitech Webcam C270                                                | 3        | 6.98%   |
| A4Tech FHD 1080P PC Camera                                          | 3        | 6.98%   |
| Microdia Sonix USB 2.0 Camera                                       | 2        | 4.65%   |
| Microdia Integrated Camera                                          | 2        | 4.65%   |
| Logitech HD Webcam C910                                             | 2        | 4.65%   |
| Z-Star A4 TECH USB2.0 PC Camera J                                   | 1        | 2.33%   |
| Silicon Motion 300k Pixel Camera                                    | 1        | 2.33%   |
| Samsung USB2.0 UVC HQ WebCam                                        | 1        | 2.33%   |
| Samsung Galaxy series, misc. (MTP mode)                             | 1        | 2.33%   |
| Realtek Laptop_Integrated_Webcam_FHD                                | 1        | 2.33%   |
| Realtek Front Camera                                                | 1        | 2.33%   |
| Realtek BRI-S90AF                                                   | 1        | 2.33%   |
| Razer USA Gaming Webcam [Kiyo]                                      | 1        | 2.33%   |
| Microdia USB Live camera                                            | 1        | 2.33%   |
| Microdia rapoo camera                                               | 1        | 2.33%   |
| Logitech HD Webcam B910                                             | 1        | 2.33%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera                          | 1        | 2.33%   |
| Generalplus GENERAL WEBCAM                                          | 1        | 2.33%   |
| Generalplus 808 Camera                                              | 1        | 2.33%   |
| Cubeternet USB2.0 Camera                                            | 1        | 2.33%   |
| Cubeternet GL-UPC822 UVC WebCam                                     | 1        | 2.33%   |
| Cubeternet EtronTech CMOS based eSP570 WebCam [Onyx Titanium TC101] | 1        | 2.33%   |
| Aveo UVC camera (Bresser microscope)                                | 1        | 2.33%   |
| Apple iPhone 5/5C/5S/6/SE                                           | 1        | 2.33%   |
| Alcor Micro USB 2.0 WebCamera                                       | 1        | 2.33%   |
| A4Tech PC Camera                                                    | 1        | 2.33%   |

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
| 0     | 126      | 83.44%  |
| 1     | 22       | 14.57%  |
| 2     | 3        | 1.99%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 11       | 40.74%  |
| Graphics card            | 10       | 37.04%  |
| Unassigned class         | 1        | 3.7%    |
| Storage/raid             | 1        | 3.7%    |
| Network                  | 1        | 3.7%    |
| Net/ethernet             | 1        | 3.7%    |
| Communication controller | 1        | 3.7%    |
| Chipcard                 | 1        | 3.7%    |

